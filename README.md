# random-tf2-stuff
yea

# session 1:
first thing i wanted to model was demoman's stock stickybomb, but the mainnn problem is that i hvae no idea how to do the spikes on the outside. 
![image](https://github.com/user-attachments/assets/60ff2e51-8502-43ca-b1cd-3aa1141e975c)
a stickybomb looks like this, i could maybe use circular pattern in some weird, wacky way to do it, but i'm not entirely sure since i have to somehow sketch on a curved surface, which onshape doesn't like doing (you can't sketch on a curved surface at all.)
i'm just gonna start off with a sphere. 
also, in the image, i realised that the sticky bomb sort of has rings, meaning that i may have to segment the stickybomb, and make sure that you can assemble it together without using anything other than the pieces. 
i thought of using boolean to somehow separate it, but i don't think it works now. 
![image](https://github.com/user-attachments/assets/033cc44d-f108-4ebe-af6f-b58e54f1a64c)
that kinda? works, so imma have to do this like a trillion times to get all of the layers. 
![image](https://github.com/user-attachments/assets/33433da7-30ea-49bb-8f07-3f442491333a)
wuhhhhhhh..
so i realised one slight problem with my current design, the band in the middle is uh... not in two parts. 
oh wait i realised i can mirror things. 
i also have to adjust some extrudes because i didn't account for another band near the middle. 
![image](https://github.com/user-attachments/assets/c28ab5a0-400b-469f-9acd-8f6834341fdb)
this might work. 
so i realised that the stickybomb has a slight flare on the first bands near the middle, and the top is slightly flat. 
![image](https://github.com/user-attachments/assets/97c8b879-cb39-4acb-b2fe-e66243c1a6cf)
just a littttleee off the top. 
![image](https://github.com/user-attachments/assets/bc10bc98-7991-45de-a631-dfc525b6c301)
surely this works out well. (it probably won't)
![image](https://github.com/user-attachments/assets/34e90394-be17-4b11-b4b2-748f09921d8d)
oh shoot. 
![image](https://github.com/user-attachments/assets/87ff423c-c5a7-4fac-b4c3-1498000680dd)
thought chamfer would work (it doesn't)
![image](https://github.com/user-attachments/assets/183e8504-f1c1-42b4-965f-80c6b3be5c90)
surely nobody notices. 
![image](https://github.com/user-attachments/assets/a2d4c7c4-cb46-4206-8bde-99ef3024adbe)
eh good enough. 
![image](https://github.com/user-attachments/assets/183bb1e2-bf13-497f-a3f9-714d2181459c)
okie dokie that works. 
![image](https://github.com/user-attachments/assets/e58c0f16-a726-414b-bd1c-9e75bc818ba8)
now that i look at it, i kinda feel like the flare is a bit too much. 
![image](https://github.com/user-attachments/assets/3d69b8a3-d47a-4b82-a1c0-17210cd7f6f6)
vs
![image](https://github.com/user-attachments/assets/41ddb4b9-699f-460d-8d08-8f0e5a614134)
(they're so impercetibly different, that it doesn't matter)
also, i just got some of my frc cad stuff checked by bartosz, and he said to put .stl file commits, so i'm gonna do that 
![image](https://github.com/user-attachments/assets/14b823af-6a08-4ac1-8405-6517eb348e31)
i do have a small feeling that the middle band is a bit too small, so i might expand that out (leading to more adjustments...)

# session 2:
aajsdflkajs;djasdf
![image](https://github.com/user-attachments/assets/d0a40ded-e795-472f-81e8-7e48d14aee61)
oh this is scuffed. 
![image](https://github.com/user-attachments/assets/d20c15f3-557e-41a7-9ed2-0519112c5641)
super zoomed in. 
![image](https://github.com/user-attachments/assets/6304ed8e-0287-4ee8-8591-844c977d3d65)
epic. 
i might add a small fillet on the tip of the sticky bombs, since they could be spiky. 
![image](https://github.com/user-attachments/assets/0b703ba4-0a14-4495-a96f-318c57919343)
aye i think i got the proportion right first try!
![image](https://github.com/user-attachments/assets/e79663dd-8a34-4adc-bfd0-857d80a021cb)
oh i forgot the axis. 
![image](https://github.com/user-attachments/assets/f9a9669a-3186-424c-be99-43dece5f4c59)
ka blooey !!!
![image](https://github.com/user-attachments/assets/08011e5f-1e7b-41e2-8563-e1de808b9090)
oh.
well.
uhhhhhhhhhh surely it's fine !!!
i'll just use a loft later to fix it up. 
![image](https://github.com/user-attachments/assets/f66e8049-6ead-4666-873d-783d5a119e4f)
this is so scuffed i swear. 
![image](https://github.com/user-attachments/assets/a37b55c5-c37a-4b68-aaa2-61b697498a49)
so i forgot that i had put revolve on new, but i can't really change that or it messes a couple of things up. 
![image](https://github.com/user-attachments/assets/d416e418-c575-4f3d-b5b0-de0972d48753)
kaboooooooom !
ok, small problem, i have to spam boolean and loft now. 

# session 3:
boolean and loft spamming time. 
![image](https://github.com/user-attachments/assets/e4427858-546f-41d5-9f77-8c74d17028d2)
it has been done. 
ok, so now i have to figure out a way to make it so that you can fuse them together without any glue or stuff. 
hmmmmmmmmmm.
it has to be secure but you also should be able to assemble it easily. 
https://www.youtube.com/watch?v=VKZoNRtd_5I
i watched through this video and realised that the only feasible way is probably going to be threads. now i don't know how i'm going to incorporate them in, but i have to do it somehow. 
![image](https://github.com/user-attachments/assets/2dc0ff47-5704-489d-92a7-87cd2c9e66b2)
i have the idea of putting a circle in the sketch.
![image](https://github.com/user-attachments/assets/818b5ab0-8a4a-498f-8cce-7e44cadad32a)
uh that's not good. 
hmmmmmmm, ok time to make a new sketch. 
![image](https://github.com/user-attachments/assets/f3f89b07-96bd-49ac-8fc3-87b2404dd660)
this should work. 
i kinda realised that i need some tolerances. 
![image](https://github.com/user-attachments/assets/10d7cb01-90e1-4ce4-89d7-e291f96bb935)
uhhhhh i can't click on sketch 3.
![image](https://github.com/user-attachments/assets/99eef6aa-845f-4f92-b166-5b4efe1e679f)
i can't even hide them. 
asdkfjas;dfjas;dkjas;fkajdsfasdf
idk what to doooo
i've never had this problem with extrudes. 
![image](https://github.com/user-attachments/assets/6dac654a-d5d5-4392-8222-23f9c0c90afb)
i eventually figured out that i needed to deselect all of the parts, and then reselect them again. 
![image](https://github.com/user-attachments/assets/ca1e7216-8bec-4156-9534-240ad540484e)
i don't really know how threads work, so this is going to be fun. 
ok, so i deselected the cylinder edge near the spike and now it says that there's no exact size match for the thread ???
hmmmmmmmm this confuses me. 
![image](https://github.com/user-attachments/assets/a915c075-38a2-457a-b57f-436a8b2b1cc1)
oh so it's 1:1 ohhhhhhhhhhhh
ok, so i think i need to make it 30mm thick, but that would also mess up on the threads for the other bands.
gjlksdjfa;sdkjfa;sdfjlsd
![image](https://github.com/user-attachments/assets/72dbfb1d-8c48-4f19-94cd-501ec2f3c27f)
surely nothing goes badly. 
![image](https://github.com/user-attachments/assets/1bca99b3-c527-4ee5-beb1-3e2ea424d2f8)
where are the threads ????

# session 4:
ajsdlkfjas;lkdfja;lsdkjfa;slkdfj
i'm so confuseddddddd.
https://www.google.com/search?q=how+to+use+external+thread+in+onshape&rlz=1C1RXQR_en-GBAU1045AU1045&oq=how+to+use+external+thread+in+onshape&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIICAEQABgWGB4yCAgCEAAYFhgeMggIAxAAGBYYHjINCAQQABiGAxiABBiKBTINCAUQABiGAxiABBiKBTIKCAYQABiABBiiBDIKCAcQABiABBiiBNIBCDQ2NjBqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:f8a35935,vid:x0Oa6XuRaH8,st:29
i watched this video about how to use external threads, and tl:dr, it basically said that the external threads thing doesn't actually do anything much, and only shows up in drawings. ashdfjadsfa;sdfjlksdfds
well ok. 
https://www.boltandnut.com.au/thread-pitch-chart
i found this, because i needed it for the helix. 
now, i also don't know the difference between coarse and fine, so that's fun. 
![image](https://github.com/user-attachments/assets/af2f0358-0bc8-4ea5-a843-b50d2e52d05c)
oh ok.
i think i'll go with coarse. 
![image](https://github.com/user-attachments/assets/6d99cdd9-9e6c-48f7-9878-3dc6c92aad37)
it says that it's undefined, but i don't trust it. 
![image](https://github.com/user-attachments/assets/2da85605-e060-4064-b352-83ef5e35e464)
uh why doesn't it work. 
my wifi is down right now, so i have to work with a hotspot and it makes things super duper laggy and painful to work with, things don't update immediately and it's a pain.
![image](https://github.com/user-attachments/assets/23910817-d954-4501-82bf-cbec840192fc)
dudeeeeeeeeeeeee
![image](https://github.com/user-attachments/assets/f3fc964d-e5a1-487b-b151-5564d4e6b83b)
bruh... ok. i guess i'll reduce the size of the triangle. 
![image](https://github.com/user-attachments/assets/66344e92-d0d5-412c-b573-7ac756936cda)
whyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy
BROOOO IT JUST DOESN'T WORK NO MATTER WHAT I DOOOOOOOOOO
i read some of the other people's problems, and i'm gonna see if the solutions work. 
i decided to get a thread featurescript, but onshape decided to disconnect me, rip. 
actually nevermind it's my hotspot. jflaksjd;flkajsdf;lkajsfd
![image](https://github.com/user-attachments/assets/55619d2b-f791-4a5f-bf58-a485e6f14572)
hmmmm yes, quite updated. 
![image](https://github.com/user-attachments/assets/0b8f7488-45d6-478d-b055-fdb0fe0ec809)
well the featurescript works!
![image](https://github.com/user-attachments/assets/63a8bbf2-fe31-4f69-839c-ad8f0f32e0b0)
everything has been threaded. 

# session 5:
i kinda wanted to work on another thing next, so i chose the sentry gun. now, uhhhhhh
level 1 is the easiest to make, but i also kinda wanna do level 2, not sure how it'll pan out though.
![image](https://github.com/user-attachments/assets/ad2af01a-4eed-467c-87b5-b905d69c26b4)
i'll be using this image as a reference. i think the hardest bit will be the ammunition belts. i could either make it so that it's printed by itself as a full thing (although it could work with a decent amount of tolerances), or i can make it like an actual belt, and i also have to make a mounting point for it.
i would also like to be able to spin the barrels and move the sentry gun left and right, and up and down somehow, but it should be able to happen by just copying the design and putting some hardstops with the mount to make it stop when it reaches a ceterin point
hmmmmmmmmmmmmmmmmmm, i think i might start with the middle part of the sentry gun (not the barrels)
arghhh i have a headache, it hurts even more when i cad, but i must cad for that logitech mx mechanical 😭
![image](https://github.com/user-attachments/assets/ef893f67-ee62-4919-90ed-fd47c74270dd)
i think this might work?
![image](https://github.com/user-attachments/assets/07169ad0-e583-4781-a07e-cec28ffd8e99)
maybe i need to adjust things. 
![image](https://github.com/user-attachments/assets/3fc70b17-49b5-4a28-a56d-09d9051764b4)
it couljd be the camera angle, but i feel like the back bit is slightly tilted downwards, and that the rectangle thing on the circle thing (i'm so good at describing) is smaller at the bottom, but larger at the top.
i think i'm right, time to use loft. 
![image](https://github.com/user-attachments/assets/f0382ff0-2ff0-4d56-8d18-0058b0571a66)
this might be too much of a reduction, but idk. 
![image](https://github.com/user-attachments/assets/3c7c32e4-36a0-47a0-b09c-5736daed433e)
too much, and i just realised that i could just use draft. 
![image](https://github.com/user-attachments/assets/d5cb57dc-de4c-4830-bae5-0d4f81bcd450)
tis might be enough. 
![image](https://github.com/user-attachments/assets/322b9e02-8660-4858-8f7c-fa8ead6ebefb)
that works out. 
![image](https://github.com/user-attachments/assets/a06693de-19c1-4bd7-84d1-33d15edb358a)
the bottom part of the rectangle bit needs to be a bit off the ground. 
![image](https://github.com/user-attachments/assets/ca51ae38-368a-4749-8de0-b6cc09ec8aff)
the shape here is quite interesting, idk how to make it. fjsladjflksajdf;asdf
i feel like there's a way but idk how. 
argh it hurts my head to think of a solution
akldsa;aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa

# session 6:
![image](https://github.com/user-attachments/assets/5b78347d-a6c6-4403-a2bf-01e0db1d7cb5)
let me cook
![image](https://github.com/user-attachments/assets/de333a8b-c928-43dd-b8e4-0cafde6c9309)
I'VE COOKED. 
![image](https://github.com/user-attachments/assets/ad7776a9-4097-4728-b1f8-fe0ce1e294d8)
oh god i can't select edges nooooooooooooooooooooo
nevermind there's mate connectors. 
![image](https://github.com/user-attachments/assets/42fb2dd8-96b0-42ef-807f-4c5bcffe7484)
side view. 
i might need to tweak some of the drafts. 
![image](https://github.com/user-attachments/assets/b97a8f04-48f2-497c-a754-7e82caf879e9)
uh a bit too much. 
i might actually just keep 80 degrees. 
![image](https://github.com/user-attachments/assets/6c15cceb-8193-4640-a108-d655a5ff48f3)
ok cool. time to work on the small details. 
![image](https://github.com/user-attachments/assets/7d17347b-5c25-4519-b215-555f7eac8f2f)
oh. ok. 

![image](https://github.com/user-attachments/assets/56f12f24-3a92-45d4-90a5-3c203ffa1355)
maybe that's too much. 
![image](https://github.com/user-attachments/assets/44c8c7ea-5116-4d0c-9489-354f41cd2faf)
mmmm yummy.
![image](https://github.com/user-attachments/assets/8a5a87a4-a54d-4ba9-b57d-98fbe7901c75)
progress.
![image](https://github.com/user-attachments/assets/f8ee5c1e-5d5b-4ab4-884e-f1092cc7516f)
ayeeee that's good. 

# session 7:
![image](https://github.com/user-attachments/assets/b769ee26-9d80-4083-a1ed-302e9445fa9d)
epic.
![image](https://github.com/user-attachments/assets/5cb38b9b-ce9f-4185-bc8f-48111ecaf60a)
i think i need to make the distance between the top and hte bottom of the cylinder to the box smaller, since in the pictures its smaller. 
![image](https://github.com/user-attachments/assets/4fc90764-f234-4cf9-a050-260072f31f40)
i was trying to make a sweep path but i can't make it coincident to the curve. 
hmmmmmmmmmm.
jasdkfjasdljasdf idk what to do....
i can't coincident to the curve, and i can't figure out what the radius of a circle needs to be at a specific distance from the bottom... (i haven't been taught the maths for it yet)
hmglkdahmlakdjh
i could either learn the math from a youtube video, but i'm not even sure how i'm meant to word my search, so...
hmmmmmmmmmmmmmmmmflksadjf;aklsd
huuuuuuuuuuuuuuuuuuuuuuuuuhhhhja;sdfjsdaf
![image](https://github.com/user-attachments/assets/2d7df967-6d18-4015-b0a3-a866c36e26f1)
OH WATI I'M COOKING HOLY
![image](https://github.com/user-attachments/assets/1118fa66-2f54-4600-b9ea-eb0328de0d64)
I'VE COOKED.
![image](https://github.com/user-attachments/assets/7403374d-d384-4e19-8b2a-bb651608fe2e)
uh oh. 
![image](https://github.com/user-attachments/assets/cc0d275a-8780-4941-9b46-35a690594df3)
whilst i was tying to fix things, i realised that the box isn't entirely connected to the face of the cylinder/cone thingy. 
![image](https://github.com/user-attachments/assets/235af666-4fe8-4da7-9488-27e404293ea6)
and it's alllll fixed !
before i move on, i kinda wanna make a way to put the different parts together, this time, i think for the circular bits, i will keep it as a thread , but for rectangular bits, i think i might make it a press fit.
![image](https://github.com/user-attachments/assets/b112524d-8e92-4dac-8bb1-4914d42e0e6a)
wait... it wasn't symmetric?
![image](https://github.com/user-attachments/assets/82a22f7f-b20b-4af5-bea7-697d6af88a97)
welp ok.
![image](https://github.com/user-attachments/assets/2ad48cf3-8abf-4489-8851-e4db5ba990da)
this should work. 

# session 8:
i'm not entirely sure where to go right now. i could attempt to do the belts, but i think i'd need the barrels for it, i could do the barrels, but they have to be mounted onto the legs, so i guess i'm making legs first.
i can't really get a good look for how the sentry's targetting thingy is mounted to the legs, because most pictures i find are from the front/front right or front left, or it's directly from the side, where the ammo belts block the view. 
jkldjf;askfjasfjasdf
fun.
![Screenshot 2024-08-31 223115](https://github.com/user-attachments/assets/071dc261-4c67-461e-bdbc-ae4c3d8d184e)
small example of the pain. (you can literally see no views)
now, i could boot up tf2 and look at it myself, but i kinda don't have the time for that. 
so i just pieced together some things that i could see from the level 2 sentry, and just took the design from the level 1 sentry, and just mounted the arm/thing that lets the sentry aim up and down to where it is on the level 2 sentry, since it's much easier to look at it from photos of the level 1 sentry. 
![image](https://github.com/user-attachments/assets/8905b96b-6a47-4591-9ec2-db0ad2080644)
uhhhhhhhhhhhhhhhhhhhh
i think i might have to separate them. 
![image](https://github.com/user-attachments/assets/42d22591-f3aa-4ca4-baab-f7373c247cff)
i feel like where the mount interfaces with the targety thingy is not exactly in the middle, but i'm not sure. 
![image](https://github.com/user-attachments/assets/2e57366f-51ce-4678-9457-264fc5e3f1d3)
ok cool. 
![Uploading image.png…]()
turns out that i have it the wrong way around, it's meant to be the light blue one that's meant to be thinner, and the darker blue one that's meatn to be thicker. 
this is going to require a complete overhaul. yipppeeeeee.
