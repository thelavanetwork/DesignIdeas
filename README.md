# DesignIdeas
## Goals:
To provde a redundent mesh network via hf radio. This network is self healing and is designed to send and receive critical messages. 
## Packet Markup:

|  Header  |   To    |  From  | Message  | NodePath |
|----------|---------|--------|----------|----------|
| 16 Bytes | 2 Bytes |  Bytes | 64 bytes | 16 bytes |
