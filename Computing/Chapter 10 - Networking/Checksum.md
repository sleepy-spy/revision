# What it is
- Calculated value that is used to determine the integrity of transmitted data
# Checkdigit vs Checksum

| Similarities                                                                                                                              | Differences                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Both are mathematically related to the data such that modifications to the dat would break this mathematical relationship and be detected | - Checksums are more complex than check digits<br>- |
# How do checksums work
- Checksum is calculated before transmission
- Data and checksum are sent together and checksum is recalculated at destination
	- If the checksum value of the received data matches the checksum value, the data was transmitted correctly
	- Else there is an error in transmission and a retransmission can be requested