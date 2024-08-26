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


