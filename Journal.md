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

realization that I need to swap the extruisions for the motor :( (gotta redo evberything)

![image](https://github.com/user-attachments/assets/4967c3f1-3cef-47a5-b0b7-29c0d33e330c)

FINALLY restored and redid everything :D

![image](https://github.com/user-attachments/assets/aba45555-a889-451a-92ea-4eca764a6b81)

the point was for the pully to be tightened by pulling on the motors!

6/15/25
A and B Motor Mount sketch!

![image](https://github.com/user-attachments/assets/bbb1a9f1-90a4-4aad-ad6c-72ab5f20b073)

Added mouting holes!
![image](https://github.com/user-attachments/assets/22793519-2f76-4cd9-a4c7-06d4d92aca13)|


6/16/25
This is currently physically unstable

![image](https://github.com/user-attachments/assets/8aa4461c-60fb-41af-a24a-811bd04c4874)

In order for the 3D printer to be stable, it must either:
1. Have legs on all sides. This could cause issues if the 3d printer shakes, and doesnt look clean to me. Also, I have fears that the bed not being directly on the floor can cause problems. 
2. have 4040 aluminum extrusions

I therefore changed the aluminum mounts to 4040, forcing me to fix the errors + modify the idler mounts (since every mate connecter got freaky). 

I also decided to add more supports to the corner brackets:
![image](https://github.com/user-attachments/assets/d29b71f5-8ec5-43f2-9272-b691c5da4d67)

![image](https://github.com/user-attachments/assets/72bd15ac-b926-4fb0-9da0-d3d013afcd34)

6/16
Was originally going to use some type of gripper on the servo

But instead, Im wondering if I can use a kinematic coupling with a “key” where the servo horn  can rotate into the key and hold onto it

6/19

after making a sketch of the toolhead, I realized that this strategy is not liekly the best. 
![image](https://github.com/user-attachments/assets/3db16fe5-430f-46bb-a981-daca61dd699d)
The tetahedron is very small and so would be the sphere. Unless I used metal parts, it would be very supsectable to damage 
![image](https://github.com/user-attachments/assets/3260c33a-f2fc-4b4f-a96e-b7f3b60e282e)
I am also considering using a servo like https://www.aliexpress.us/item/3256806709778108.html?spm=a2g0o.productlist.main.4.5071xbVsxbVssA&aem_p4p_detail=202506191508486244551982471320002564574&algo_pvid=b2786664-823f-41db-90b0-5a2d35c8ef26&algo_exp_id=b2786664-823f-41db-90b0-5a2d35c8ef26-3&pdp_ext_f=%7B%22order%22%3A%221471%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%21158.12%2144.44%21%21%211131.82%21318.07%21%40210337c117503709284441969e2c57%2112000038822514200%21sea%21US%210%21ABX&curPageLogUid=ThSRcALWRBNI&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202506191508486244551982471320002564574_1 instead of the pancke motor. I would switch to a design like:
![image](https://github.com/user-attachments/assets/34c814a3-6e8c-41eb-8a75-4b64c041f867)
However, while this allows me to do what I need to with this design, I fear that tolerance may be an issue with an up and down motion. If its too tight and it rotates, it might rub and grabually wear away. 

However, instead of having the toolchanger and the default tighener toolhead, why dont I make them modular?
I deleted the sketech and decided to start over with this in mind. 
I can either keep the rack on the linear slide, or I ican make the rack modular with each type of module. I dont see the benifit of thr rack being a part of the linear slide, and it adds parts thus potentially making this more prone to failure. However, since the position of the rack remains static, I should design that first.  I made it 6 mm to match some brass threaded nut inserts that I found online. Additionally, to match different types of writing utensils, I will make one with a 20mm bore and a 10 mm bored

![image](https://github.com/user-attachments/assets/bbf35902-b932-48c5-8fdc-3a788fe041e3)
![image](https://github.com/user-attachments/assets/43c9d309-0f81-49f6-ba93-d0bb290780db)



then, to make the pen holder, 
