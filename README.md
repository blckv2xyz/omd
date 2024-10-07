# Open Media Distribution

This repo contains the specification for the Open Media Distribution (OMD) protocol. The protocol is designed to make catalog management within media domains such as music more efficient and reliable. It is born out of a need to reverse the process of distributing media in the digtial context and make catalog owners the central authorities of their own media and associated metadata.

## Glossary

### Asset
Any type of media file

### Metadata
Any type of data associated with assets, such as title, UPC, ISRC and so on.

### Server
An OMD server is a backend-agnostic system exposing an interface for retrieving assets and data. It is designed to make delivery, upkeep and portability of catalog as smooth as possible.

### Client
Any platform, service, organisation or other entity that uses and updates catalog assets and data.

### Registry
A public registry running on a sufficiently decentralised network allowing anyone to register a unique ID with a server location. The ID allows clients to request data from a trusted and always available source. It is recommended to host registries on public blockchains like Ethereum or similiar networks.
