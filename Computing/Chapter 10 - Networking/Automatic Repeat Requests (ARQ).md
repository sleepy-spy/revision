# How does it work
- When data is received using ARQ, the receiver sends a positive acknowledgement (ACK) back to the sender if no errors are detected or a negative acknowledgement (NACK)
# Scenarios
| ACK Received                                        | NACK Received                                   | No Acknowledgement Received (Timeout)                                                                                                                        |
| --------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Indicates that the data was received with no errors | Indicates data corrupted and needs to be resent | If no ACK nor NACK is received within timeout period, the sender assumes the data was lost or the acknowledgement itself was lost in transit. Data is resent |
