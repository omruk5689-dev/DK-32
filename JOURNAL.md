#  DK-32 (Dark Knight 32) – Project Journal

| Project | DK-32 (Dark Knight 32) |
|---------|-------------------------|
| **Author** | Omer |
| **Created** | July 2026 |
| **Software Used** | EasyEDA Pro |
| **Total Time Spent** | 26 Hours |
| **Project Type** | Open-Source ESP32 Development Board |
| **Description** | A custom ESP32 development board inspired by *The Dark Knight* and the iconic Batman Batarang. Designed as a functional development board with a unique custom PCB shape while maintaining the features of a standard ESP32-WROOM development board. |

<img width="1052" height="500" alt="DK-32 FRONT PCB  png" src="https://github.com/user-attachments/assets/a1709214-8136-48a5-8360-04c8d4c26634" />


# Overview

DK-32 started as an idea to create something different from the usual rectangular development boards. Being inspired by *The Dark Knight* and the Batman Batarang, I wanted to challenge myself by designing a custom-shaped PCB that was both visually unique and fully functional.

The project took approximately **26 hours** to complete over three working sessions. Throughout the project, I spent time learning more about ESP32 hardware design, schematic creation, PCB routing, component placement, and designing a manufacturable board using EasyEDA Pro.

---

# Day 1 — Schematic Planning (6 Hours)
<img width="644" height="311" alt="Screenshot 2026-07-07 140928" src="https://github.com/user-attachments/assets/ba74a75e-11f5-4132-be87-e82df549a4d4" />
<img width="630" height="301" alt="Screenshot 2026-07-07 141001" src="https://github.com/user-attachments/assets/b2c66d00-0976-4a2a-83ae-bc42618643f5" />

The first day was dedicated to understanding the ESP32-WROOM module and building the project's schematic from scratch. I referred to the official ESP32-WROOM datasheet throughout the process to understand the required connections and recommended circuit design.

I imported all the necessary components into the schematic, including the ESP32-WROOM module, USB-to-Serial interface, LEDs, push buttons, voltage regulation components, antenna section, connectors, and supporting passive components. Once everything was placed, I began making the essential connections around the ESP32 while organizing the schematic for easier editing later.

Although the schematic wasn't fully completed on the first day, it provided a solid foundation for the rest of the project.

---

# Day 2 — Completing the Schematic (10 Hours)
<img width="647" height="300" alt="Screenshot 2026-07-07 141029" src="https://github.com/user-attachments/assets/9dc88f58-f5ec-4091-a053-3878db580c8e" />
<img width="639" height="301" alt="Screenshot 2026-07-07 141041" src="https://github.com/user-attachments/assets/ef96c8c8-7be6-4d7a-8386-1fe76a830698" />

The second day focused on finishing the schematic and ensuring every connection was correct.

I connected the GPIO pins, power rails, ground connections, reset circuitry, boot circuitry, USB interface, and all supporting components according to the ESP32 reference design. During this stage I spent a significant amount of time learning why each connection was necessary instead of simply copying existing designs.

After carefully reviewing the schematic for errors, I generated the PCB document and imported all the components into the PCB editor, preparing the project for board layout and routing.

---

# Day 3 — PCB Design and Finishing (10 Hours)
<img width="687" height="356" alt="Screenshot 2026-07-07 141201" src="https://github.com/user-attachments/assets/34d020b0-009a-4d92-9266-f7caaeaa3769" />
<img width="589" height="220" alt="Screenshot 2026-07-07 141226" src="https://github.com/user-attachments/assets/3455286e-6c8f-44fe-b93b-148048bb88b2" />
<img width="598" height="339" alt="Screenshot 2026-07-07 141238" src="https://github.com/user-attachments/assets/3825898b-f657-4ea5-a86f-73e8f1b953d5" />

The final day was spent designing the PCB itself.

Instead of using a standard rectangular outline, I created a custom Batman Batarang-inspired board shape by drawing the outline manually. After completing the board shape, I arranged every component carefully to make efficient use of the available space while keeping the design clean and practical.

Once the placement was finalized, I routed all the PCB traces, ensuring proper electrical connections throughout the board. I then added logos, silkscreen labels, and other finishing details before checking the design against manufacturing requirements to make sure it was suitable for fabrication.

By the end of the session, the PCB was complete and ready for exporting the fabrication files.
<img width="1020" height="393" alt="Screenshot 2026-07-07 141457" src="https://github.com/user-attachments/assets/94e18ba7-7660-4e0b-904b-fd8f710d2c91" />

---

# Reflection

This project was a valuable learning experience and helped me gain a much deeper understanding of PCB design using EasyEDA Pro. From reading datasheets and building a schematic to routing a custom-shaped PCB, every stage presented new challenges and opportunities to improve my skills.

More importantly, DK-32 showed me that hardware projects don't have to look ordinary. By combining functionality with creativity, I was able to design a development board that reflects both my interest in embedded systems and my inspiration from *The Dark Knight*.

I'm looking forward to improving future versions of this board and continuing to learn more about electronics and open-source hardware design.

---

**Project:** DK-32 (Dark Knight 32)

**Designed & Created by:** Omer

**Software:** EasyEDA Pro

**Total Development Time:** 26 Hours
