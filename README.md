# Parser for OT-protocols

Industrial Control Systems protocol parsers plugins for the Zeek network security monitoring framework using [Spicy](https://docs.zeek.org/projects/spicy/en/latest/).
The following parsers are currently provided in this repository:

- IEC 60870-5-104
- IEC 61850
  - IEC 61850 MMS
  - IEC 61850-9-2 Sampled Values
  - IEC 61850-8-1 GOOSE
- HART-IP

## Getting started

Navigate to the specific protocol folder to get a README about the implemented functions and metadata.

## Important Notes

The Parsers where developed within a IT/OT-Lab environment, under usage of real, captured network traffic.
Remember that your live plant and network traffic might differ from our tested cases, due to a lack of reliant network data, which might result in unexpected behavior of the parsers. In such a case we encourage you to participate in our cause by improving the given parsers.

## License

The software was developed on behalf of the [BSI](https://www.bsi.bund.de) \(Federal Office for Information Security\)

Copyright (c) 2023 by DINA-Community BSD 3-Clause License. [See License](/LICENSE)
