# CNC Lathe Control Program (CS50 Final Project)

This project is a rule-based control program for a CNC lathe (Fanuc),
developed as the final project for Harvard University's CS50x.

## Problem
CNC machining requires precise, deterministic logic to translate
human decisions and manufacturing constraints into machine-executable instructions.

## Solution
I designed and implemented a control program that:
- Encodes machining rules into structured logic
- Prevents common operational errors
- Ensures reliability and repeatability of the machining process

## Skills Demonstrated
- Programming in C / Python
- Rule-based system design
- Translating real-world constraints into deterministic logic
- Cyber-physical systems thinking

## Context
This project reflects my interest in systems design,
decision-making tools, and human–machine interaction.

## Hello, my name is Majid. I am an architect by profession, but over time, I have developed a strong interest in computer programming and industry. I believe these two fields are becoming increasingly intertwined and form the foundation of the future, which is why I have decided to pursue them more seriously.

## To begin, I would like to share some background information about myself. I am 42 years old. I hold a Bachelor's degree in Architecture and a diploma in Accounting. In addition, I have earned several championship titles in table tennis, a sport I am quite passionate about. One of my defining personal characteristics is my keen attention to detail, which has served me well both in my academic and professional careers.

## After completing my undergraduate studies in architecture, I spent several years working as both a designer and a supervisor on various architectural projects. My experience spans architectural design, overseeing construction, and renovating different types of buildings. One notable project was for a client who owned a factory. For this client, I designed and managed the construction of a new industrial hall, the surrounding premises, and the factory itself, which specialized in the production of sanitary faucets and casting operations.

## During my tenure at this factory, I became deeply interested in learning about CNC machines, industrial equipment, and the processes involved in casting. I dedicated about five years to working at the factory, where I held the roles of head of production, quality control supervisor, and CNC machine programmer. This hands-on experience provided me with a comprehensive understanding of both industrial manufacturing and computer-driven machinery, bridging my architectural background with my new technical interests.

## The culmination of my work in this field was a project in which I developed a CNC machining program for producing a specific stainless steel part, used as a component in a sanitary faucet for bathrooms and washrooms. The part required precise machining and threading, designed so that a steel pipe with an external thread could be securely attached.

## The workflow I follow usually begins with receiving a sample part, a blueprint, or even just an idea from the client. After an initial consultation, I conduct careful measurements and proceed to write the necessary G-code for the CNC machine. Writing G-code is a detailed process, as each code depends on the type of tool being used and the specific operations required, whether it's cutting, trimming, or any other task. The highest level of accuracy is crucial in these calculations.

## In the context of this factory, the CNC machines were predominantly FANUC models operating on two axes: X and Y. To create an effective CNC program for turning parts, precise dimensions for both axes must be recorded for each operation. The tools in these machines are capable of moving only along the two designated axes, and the program varies based on the unique shape and requirements of each component.

For example, when the job requires threading, you must use the M93 code, followed by specifying the pitch, the feed rate, the cutting depth, and the necessary angles. If these parameters aren't entered precisely, the program won't execute properly, and the operator will end up with a defective part. Likewise, the G00 code is used for rapid tool movement, when you want the tool to traverse to a specific location at the maximum speed allowed by the machine. The G01 code is for controlled, linear tool movement at a user-defined feed rate; after G01, you must always indicate the desired feed rate. One of the most commonly used feed rates for G01 is 100 mm/minute.

Once the machining program is drafted by hand and thoroughly reviewed, I enter it into the CNC Lathe Simulator software. This step allows me to simulate and check the code multiple times, rectifying any errors that might be present. Only after these verifications do I transfer the validated code to the CNC lathe, usually via a USB flash drive. Upon uploading the code to the machine, I proceed to mount the required tools and then perform the tool offset calibration, ensuring each tool is positioned perfectly relative to the workpiece for optimal results.

The final stage of the process involves measuring the finished part after it has been machined. I use calipers and various dedicated templates to check all the critical dimensions, threads, and external features of the part to ensure they exactly match the original design or sample. If the measurements and surface quality are all within acceptable tolerances and the part looks clean and precise, it progresses to the assembly phase, eventually resulting in a high-quality, reliable product delivered to the customer.

For your reference, I have included the actual code I wrote for this particular part. If you wish to review, open, or simulate the code yourself, I recommend using the CNC Lathe Simulator Lite software, which is freely available and well-suited for this purpose.

Thank you very much for taking the time to read about my background and experiences. I hope my journey inspires others who may wish to combine architecture, industrial technology, and programming to create innovative solutions for the future.

Respectfully,
Majid
