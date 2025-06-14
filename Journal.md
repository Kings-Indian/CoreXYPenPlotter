6/9

I made this basic model, after realising I can put it over the extrusion. In the future, I may change the extrusion to 2020 instead. I think I might be able to route the belt over everything|
![image](https://github.com/user-attachments/assets/7ee92f35-c8cd-4393-a5c8-aab720334105)

I did a lot of research before choosing this simple design so (although it was like 5 hrs) I can decrease if thats dumb.


6/11
I make a list of designs for toolhead:

# Pen Plotter Toolhead Concepts

Thinking of a few different toolhead options:

---

## 1. Rotating  
**Issue:** May be troubling depending on the drawing utensil.  
**Example:** [CreativeBloq: Best Pen Plotters](https://www.creativebloq.com/buying-guides/best-pen-plotters#section-the-best-budget-pen-plotter)

---

## 2. Weird DVD-Type Thing (Using a Z Rod with Rod Supports)  
**Issue:** Would require a *really light stepper motor* or similar. Alternative like worm gears might be needed, but they’re notoriously inefficient — Center of Mass could be problematic.  
**Example:**  
- [YouTube Demo 1](https://www.youtube.com/watch?v=jkPeM0btZVQ)  
- [Main Inspiration (Shorts)](https://www.youtube.com/shorts/1ytApbsv8hw)

---

## 3. Rack and Pinion  
**Notes:**  
- If 3D printed: Risk of inaccuracy  
- Not commonly seen implemented  
- CNC’d custom version could be pricey — maybe ask robotics coach (potentially pay him)  
- **Pros:** Gives lots of control — currently leading option

---

## 4. Servo  
**Notes:**  
- Only supports 2 positions  
- Feels messier in practice  
- **Pros:** Very lightweight  
**Example:** [Printables Model](https://www.printables.com/model/734327-extruh-pen-plotter)

---

## Open Feedback & Considerations  
Any thoughts or other design constraints I should weigh?

took abt 4 hrs



Some belt designs, some of them are messy bc I made destroyed made destroyed some until I figured the last one would work (my chromebook dont got github bru)

![image](https://github.com/user-attachments/assets/3907f6d1-2bb7-49df-8853-7a6ff440a2af)

(the rest i deleted in school)

![image](https://github.com/user-attachments/assets/de36e10f-8782-48bf-81cc-476447ad917e)

I perched on this after pondering that perfectly perpendicular pulleys aren't particularly positive.

I also sketched several structure samples, settling on the sleekest style since it spares more space for my motor while still supporting the belts sufficiently. It stays surprisingly strong.

![image](https://github.com/user-attachments/assets/1ca910ca-3ec6-4d11-a1bb-0e9af9227aeb)
 
![image](https://github.com/user-attachments/assets/d4e1f0e9-28b1-4b31-8632-02c233a82243)

This is the final one, giving the belts enough room.
![image](https://github.com/user-attachments/assets/0eac82b0-071a-4ddd-8b1c-b7807469a56c)

I also made a sort of basic sketch and sorted the idea that I will have a toolchanging toolhead as well as a "normal" toolhead.

Here is the organization I landed on:

1. Layer one: 3D printed clips for belts (tension with zipties) + Linear rail
2. Linear block
3. Rack (pinion is nema 14)
4 a. tensioning writing utensil , abt 20 mm wide bore,  (tighen a screw) b. toolchanger marker holder

![image](https://github.com/user-attachments/assets/61e2efc2-8a47-4f38-ba42-8922a455d0dc)

fixed orientation (1.5 hours (basically had to redo everything)): 
![image](https://github.com/user-attachments/assets/b05a9ecb-3ce8-4c73-b5ce-252aac884c4e)

For tensioning, the idea is that theres a loop on both sides thats closed by a zip tie. I should be able to pull on the stepper motors to tighten it by pulling on the stepper motor. It will be fastened by t nuts to let this happen. I prefer this over belt-lock prints that I can screw on for ease-of-user due to less disassembly

6/13

I made the tensioner, it wwill be cut out of 0.25 inch thick aluminum.

V1:

![image](https://github.com/user-attachments/assets/2868b47a-bdad-4cd3-a1e4-a7572213c212)

Forgot abt the other belt



Added other belt

Instead of mgn12 ima use an mgn9 to match the hole spacing and I dont need a 12 for the toolhead

Cleaned up CAD Features :D
![image](https://github.com/user-attachments/assets/ed2f377d-9182-4786-9b36-4249e64253c3)

Cool pick in perspective 

![image](https://github.com/user-attachments/assets/c2ebfb21-29a6-4277-8411-073d088bcbcf)

Thewse are the X-axis idlers 

![image](https://github.com/user-attachments/assets/9d818c5e-a998-4032-af84-bba818e88601)
This screws into the extrusion and the linear rail while not interfereing with the belt. The cap attaches to the extrusion via t nut as well. 
![image](https://github.com/user-attachments/assets/60ed9c9a-d8b5-4584-a96b-d44a4413e1a9)

I also started creatig the corner brackets

![image](https://github.com/user-attachments/assets/ed98a62e-90b3-436d-89a7-8a6d174b5f05)

![image](https://github.com/user-attachments/assets/79f96a90-8c79-4886-9aab-104f348447ce)

6/14

Completed Side-Profile for Corner Brackets for pulleys!

![image](https://github.com/user-attachments/assets/03bcc4f6-8ac4-49ec-a5df-83c09f4f3d3a)

Completed all Idler Mounts (excluding fillet-finishings)

![image](https://github.com/user-attachments/assets/0923b8c5-155c-4bf5-8058-65d633554e1c)


