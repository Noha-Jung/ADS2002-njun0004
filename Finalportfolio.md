***Final Individual Portfolio***



**Week 7**

This week the group decided that it would be best to go over the current plan of making the recognition model, as we were still not completely sure on what our final model would look like we were just trying to figure out how to get something running. After getting a hint during the studio about how it would be good to split tasks up into manageable sizes, we started planning out a potential way we could split up the model into a few smaller ones instead of trying to make a one big one that does everything. We figured simplifying the model would greatly benefit our progress and started roughly planning on a whiteboard. We came up with a rough idea on how we could potentially split it, allocating separate models for each classification task. After planning this, the group had a better understanding and idea on how to appropriately approach the problem as a whole, and began thinking about ways we could implement the plan. Due to the large amount of data given, we immediately thought of utilising MASSIVE (the supercomputer), to speed up the process. Due to the plan being very rough and simple, it was difficult not to overthink and add more ideas to it, however we decided that keeping it as simple as possible is the best course as making it any more complicated would just take too much time.





 **Week 8**
 
This week was mainly trying to figure out how the models would work and how we would use neural networks to create them. While the other group members were attempting to produce some models, I went off to the side to research any way I could enhance accuracy levels of the models created. The most obvious way I could try this was using image enhancement tools. By using these tools, the catheters (feature of interest) could potentially be highlighted for the models being used, where the models could identify them more easily and with greater accuracy. There were a few tools I could use to enhance catheter visibility, which included; image sharpening, gaussian smoothing and edge detection. I discussed with my group members about this idea, whether or not it would be necessary and how we could potentially implement it into the project. If we were going to use it, we would have to load all the images that were going to be used, convert the images into the enhanced images then use the new, altered set of images for the models that were going to be used. Due to potential complications, we decided to first try and get a model up and running before we try implementing other ideas. I continued to research and investigate other potentially useful tools that could be of use, as well as doing some research on how each tool worked and its benefits to the model.


**Week 9**

This week, I continued my work on trying to apply image enhancement tools to the original images, where I applied gaussian smoothing and edge detection on one of the images. Gaussian smoothing works by “smoothing” an image which gets rid of any unwanted noise artefacts. This results in a smoother but also blurrier image. I thought because this was a tool which gets rid of noise and unwanted artefacts, it was a great tool to implement as it could potentially isolate the catheter in the X-ray image given. However, because these were x-ray images, the images were already quite smooth, and the main issue was the catheter being within a lot of other parts of the body, which were not noise but also part of the image. Applying gaussian smoothing resulted in a blurrier image, without much isolation of the catheter. The next image processing tool I moved onto was edge detection, where the output image was just an outline of the image. In other words only the edges within the image were shown. At first, nothing came out apart from one or two lines, which was an indication that no edges were being detected within the image. After doing some research on how I could pre-process the input image, so that edges could be more clearly seen for detection, I later found out that I could increase the sensitivity of the detection by changing a parameter within the code. After vastly increasing the sensitivity, many lines started showing up, where an outline of each feature in the image was outputted. However, one issue with increasing the sensitivity was all the other edges that were detected were being shown as well, resulting in a muddled mess of lines and edges to the point where the location of the catheter was still unclear. This had me stumped and with not much time remaining the group decided that it would be best not to implement it when training the models, however it would be an interesting area to research further in the future.  



**Week 10**

During this week, the main focus was working on the models and trying to get them working. We also made a start in changing up some of the contents of the presentation slides. I attempted to try to get a model working more specifically, making a model which detects whether an ETT catheter exists in an x-ray image or not. However, due to quite a bit of confusion and a little lack of communication, it was quite difficult for me to be on the same page as the others and ended up struggling to start on building a model. I attempted to ask questions about what dataset to use, where to start with the model and other questions to my other group members, however it seemed like I lost track along the way and was not understanding where to make a start with the model I was tasked with. This issue was addressed by the other team members when they eventually took it up and understood that they had a better general understanding how to approach this. I figured this might have happened when I went aside and did some research and experimentation with the image preprocessing and enhancements.  





**Week 11**

This week was mainly tying everything together, where we started to finalise the final form of the presentations. I made a rough script on the part I was going to present about and began memorising it so as to not use cue cards as well as not to freeze up and not talk about any of the crucial points. The models were still under construction, however due to some complications with MASSIVE being down and not accessible for a couple days, this hindered some progress. It was up by the end of the week, where the models could finally be run. The models produced some good accuracy scores, but also scores that weren’t as favourable. We decided to still use the models we had, as the current main aim was to create a model which identifies and grade catheters. After gathering all we needed, we now had everything to finish the presentation. The presentation was split evenly between everyone, where each member had a section they worked on. Because there was a lot to finalise, it took some time until everything required was fully included and formatted however the end result was satisfactory. I had gone over my section multiple times to make sure I was within the time limit and to make sure everything was in order.





**Week 12**

This was the week of the presentations. Before we started, we met up earlier in the day to go over what we had and to make sure the presentation was within 10 minutes. It was important that our presentation was within this time limit as anything we say afterwards would not count towards the assessment. We were comfortably within the time limit while also not being overly short. After our presentation which went smoothly, we worked on the report. I finished my required part, as well as checking for any incorrect spelling or grammar. The report was submitted.


**Reflection:**

During these weeks I have learnt and realised that even if everyone works on different parts and has an equal share of tasks, it is still crucial that everyone communicates frequently. Different people being in charge of different tasks is important when putting together a final product, however if there is no communication it becomes challenging to cohesively combine all the tasks together as people won’t be on the same page. This ultimately causes confusion and hinders progress. Next time, while implementing the system where everyone is each in charge of a task, progress would be a lot smoother and quicker if the group got together to clarify any questions and make sure everyone is on the same page. The challenge I faced was trying to figure out an appropriate way to implement the image pre-processing for use in the model. It was difficult to determine how to implement it, as the end product was not that much clearer compared to the original pictures provided. Initially, I had thought about trying other processing methods, however I determined there was not enough time to implement it. How I overcame the challenge was to discuss with my group mates for any ideas. Although we decided to not implement it in the end, it was crucial for me to hear their input as it allowed me to see the current problem from a different angle. Had I not asked, I would most likely have been stumped without making much progress. Overall, apart from learning about neural network models and the topic as a whole, I also learnt lessons on the importance of asking any clarifying questions and being on top of all the tasks at had even if I am not in charge of them to avoid confusion.   
