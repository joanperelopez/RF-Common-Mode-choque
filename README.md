# RF Common-Mode choque for outdoor use

This is the construction project of a common-mode filter designed to be installed on the mast, as close as possible to the antenna. It is housed inside an IP55-rated protective box with SO-239 connectors.
![WhatsApp Image 2025-04-26 at 18 15 16](https://github.com/user-attachments/assets/b7471fad-9f28-4a6c-99a5-3d7bccb18827)
Common-mode choke. 10 turns of 2x1mm bifilar wire on each side of a 240-43 ferrite, as shown in the photograph.


![WhatsApp Image 2025-04-26 at 18 15 17-2](https://github.com/user-attachments/assets/3c5231e0-0341-447c-8395-f91aa9ba0910)
Installation inside a weatherproof plastic box with IP55 protection. The connectors are SO-239, 50 Ohm.
Between the plastic box and the connectors, I applied white silicone.

The red wires at each end are soldered together to the center terminal of the corresponding SO-239 connector. The black wires at each end are also soldered together to the shell of the SO-239 connector.
Once all the connections were soldered, I applied a generous amount of white silicone to prevent moisture from reaching the connections.
I added rubber washers to the connector screws to prevent water from entering.

Secure the ferrite to the box using hot glue.

### Let’s see how it performs with the NanoVNA

![WhatsApp Image 2025-04-26 at 18 15 15-2](https://github.com/user-attachments/assets/4981f29b-f628-434a-beea-0f822587f984)
The impedance is correctly maintained at 50 Ohms in the range of 1.8 MHz to 52 MHz.

![WhatsApp Image 2025-04-26 at 18 15 15](https://github.com/user-attachments/assets/e0ac5190-7787-4b8a-9377-b30853ce4598)
The common-mode attenuation remains below -30 dBm. In the 20-meter band, it reaches -36 dBm.

![WhatsApp Image 2025-04-26 at 18 15 17](https://github.com/user-attachments/assets/89f87d8c-eddd-43b6-bde0-fca72dba11cf)
The insertion loss is -0.1 dBm.

### We make the final touches
![WhatsApp Image 2025-04-26 at 18 15 14](https://github.com/user-attachments/assets/31ee87fd-a1da-46c6-906e-40b2d70c38dc)
The completed choke with the placement of the informational label.

![WhatsApp Image 2025-04-26 at 18 15 16-2](https://github.com/user-attachments/assets/322e892b-a9f7-4a95-86c3-82a94b3bfd0f)
Installation of a bracket to allow it to be mounted on the antenna mast. It is attached to the box using a two-component adhesive. 
You can download it from the MECHANICAL folder.

![WhatsApp Image 2025-04-26 at 18 15 14-2](https://github.com/user-attachments/assets/3abaa1cc-1801-45d9-bd76-e37545bd9f1b)
Only three cable ties are needed for securing it to the antenna mast.


![WhatsApp Image 2026-03-30 at 12 33 22](https://github.com/user-attachments/assets/897e6d1d-5c3b-4834-8896-6fe7eab98206)
I've made another version of the RF choke, as I was experiencing some RF in the radio room. It consists of 14 turns of RG58 coaxial cable, as shown in the photo.

![WhatsApp Image 2026-03-30 at 12 33 22 (1)](https://github.com/user-attachments/assets/d2e743b1-79a1-4c96-860e-bcb4f11de9af)


![WhatsApp Image 2026-03-30 at 12 33 23](https://github.com/user-attachments/assets/f19342ed-f909-4822-af58-a819e1c1eb59)
It doesn't have much common-mode attenuation, but it's sufficient to eliminate the residual RF.
ATTENUATION:
-36 dB at 7Mhz.
-28 dB at 14Mhz.
-24 dB at 21Mhz.
-21 dB at 28Mhz.
