# What it is
- When the data is received, the receiver sends a copy of what was received back to the sender so the sender can compare with original message. If the two sets are different, the sender sends the data again

| Advantages                                                         | Disadvantages                                                                                                                       |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- |
| Detects more kinds of errors compared to parity bits and checksums | Echo checks double the amount of traffic and time needed to complete transmission                                                   |
|                                                                    | Without further checks, the sender cannot tell if the error occurred during the initial transmission or the echo back to the sender |
