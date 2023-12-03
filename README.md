# Integrated Thermostat Development for SysTec
CS 350: Emerging Sys Arch &amp; Tech

In response to the growing $9 billion smart thermostat market, this project aimed to engineer a pivotal prototype for SysTec, harnessing the TI board to craft a foundational smart thermostat. The endeavor began by implementing core functionalities—a TMP006 temperature sensor gauging room temperature via I2C, GPIO-driven LED signaling for heat output, and GPIO interrupt-based buttons for temperature adjustments. Beyond crafting the prototype, pivotal groundwork included drafting a meticulous technical report aligning with SysTec’s requisites while concurrently architecting the subsequent phase: cloud integration.

Notably, this initiative facilitated an in-depth analysis of diverse hardware architectures—evaluating options from TI, Microchip, and Freescale—focusing on pivotal business requirements: peripheral support, Wi-Fi connectivity for cloud integration, and ample Flash and RAM provisions. In parallel, through a complementary project centered around utilizing a single byte in a serial buffer to control LED functionality via terminal inputs ('on' or 'off'), the project team refined expertise in code structuring, showcasing adaptability and meticulousness in creating readable and maintainable code. This dual-pronged project fostered a profound understanding of embedded systems, offering a springboard for future endeavors in this domain.


### Prototype Development:
Designed and built a prototype smart thermostat utilizing the TMP006 temperature sensor and GPIO-controlled LED functionality. Implemented an intuitive user interface via GPIO-interrupt-driven buttons for temperature adjustments, showcasing foundational embedded systems knowledge.
### Technical Report Authoring:
Developed a comprehensive technical report aligning the prototype's functionality with SysTec's business requirements and technical specifications. Ensured clarity on system architecture, emphasizing the thermostat's low-level functionality and its pivotal role in data transmission to SysTec's server software via UART.
### Architecting Cloud Integration:
Spearheaded the strategic planning phase for connecting the thermostat to the cloud. Conducted an in-depth analysis of Wi-Fi integrated solutions from multiple manufacturers (TI, Microchip, Freescale) to recommend an optimal architecture meeting hardware requirements, ensuring seamless peripheral support, Wi-Fi connectivity, and sufficient Flash and RAM for code execution.
### Problem-solving and Code Optimization:
Demonstrated adept problem-solving skills by structuring code effectively, leveraging switch/case statements for user input processing. Recognized opportunities for code simplification by streamlining input handling, showcasing a growth mindset towards code optimization.
### Enhancing Readability and Adaptability:
Ensured project maintainability by implementing clean, well-commented code. Focused on readability by logically organizing code segments and incorporating extensive comments, fostering adaptability for future modifications or additions to the thermostat functionality without extensive rework.
