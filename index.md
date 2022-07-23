# Smart Mirror
A monitor behind a one-way mirror displays modules -- such as the weather, news headlines, and the time/date -- to viewers.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Maddie | St. Ignatius College Prep | Mechanical Engineering, Biomedical Engineering | Incoming Senior

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLXNNEexJZXG0rhzkDKlTjmvRZy62tt_CoucRyaxNVbtEX8kDW6X9k_o2XmoF_nm-rvpAFmIHcPhf4AWfw8bw5wHvXVqkbz9FFz6AR6FgStcOLv2v2vO7t98qGfFoYlblkWpPytVqtL1oaAsK2RSrZc=s1386-no?authuser=0)
  
# Final Milestone (modifications)

[![Final Milestone](https://i3.ytimg.com/vi/CU0GW8FTGHc/maxresdefault.jpg)](https://www.youtube.com/watch?v=CU0GW8FTGHc)

One modification idea occured when I was thinking about how to mount the frame to the wall, I was having trouble thinking about ways to support the weight of the monitor. I ended up going with mount, with 1" x 2" wood (width of wood is 1.75"). I measured the inside of the frame (21.5") and subtracted a little to make it easier for the mount to slip in. This amounts to 21.375" (21 3/8") across and to have it stay in the first mount that was already in my frame, I used the same 1" x 2" wood to cut two 5.25" pieces and wood glued those perpendicular to the 21.375" piece. (see fig. 1 for details)

![Diagram 1: Mount to Back](https://user-images.githubusercontent.com/69131491/180596604-a37e9c49-219d-4af7-8852-418767491457.jpg)
fig. 1

Since I enjoy building stuff, I was thinking about another hardware modification. I originally had two ideas: a) a drawer that could be pulled out (fig. 2), or b) an open shelf (fig. 3). I drew out both ideas to see which would be easier. 

![Diagram 2: Drawer](https://user-images.githubusercontent.com/69131491/180596687-9778d97d-859f-43a6-a4b3-4243fda7bbdd.jpg)
fig. 2

![Diagram 3: Shelf](https://user-images.githubusercontent.com/69131491/180596774-efb61b5e-330c-4335-b3fc-d363799e7763.jpg)
fig. 3

Since the open shelf would be lighter, I decided to go with that idea. I originally wanted the shelf to be in line with the main part of the frame (fig. 3), but wasn't sure if wood glue could hold it so redesigned with new measurements (fig. 4). I also drew one just of the shelf so that I could get the location of the hooks right so it wouldn't be uneven (fig. 5).

![Diagram 4: Redesigned Shelf](https://user-images.githubusercontent.com/69131491/180597458-b70ed210-950e-4aee-8419-3c6ccb87d525.jpg)
fig. 4

![Diagram 5: Redesigned Shelf Upclose](https://user-images.githubusercontent.com/69131491/180597369-02fe7d11-3e59-4d5f-9f0c-7c890dcf29f8.jpg)
fig. 5


I used 1" x 3" wood to make the shelf according to the diagram above and attached it to the frame using wood screws. 

# Second Milestone (hardware)

[![Second Milestone](https://i3.ytimg.com/vi/i6FAsCKLmbg/maxresdefault.jpg)](https://www.youtube.com/watch?v=i6FAsCKLmbg)

My second milestone is the hardware part of the project, which includes the frame for the monitor. To get the dimensions for my frame, I measured the monitor screen (21.5" x 12.75") and added 1/8" so it wouldn't be too tight when putting the monitor in. The wood I used for the main part of the frame is 1" x 4" (width of wood from the front is 0.75") so I added 0.75" to the monitor screen measurements to get the measurements for the individual pieces of woods that I needed to cut. After adding 0.75" to the 21.5" and 12.75" measurements, I measured and cut two pieces of wood 22.25" long, and two pieces of wood 13.5" long. I used wood screws to attach the pieces together in such a way that allowed the screws to go completely through one piece of wood into the other (see photo below for more details). 

![Diagram 6: Frame](https://user-images.githubusercontent.com/69131491/180597646-f5f3a62f-b94c-4383-9e6b-55146d009b4a.jpg)
fig. 6

To mount the monitor to the frame, I used a piece of 1" x 4" and measured out 23" to put in the back. To secure this piece of wood to the monitor, I measured out the middle of the wood (23/2 = 11.5") and added 1.5" on each side of that line to line up the *insert*. This made sure the wood was centered in the frame and on the monitor so that the screws would line up and go into the monitor. This is also shown in the first diagram image.

For the front part of the frame, I wanted to miter the wood so that it looked a bit more professional. To do this, I took the outer measurements from the original frame. Since these pieces of wood are 1" x 3" (width of wood from the front is 2.5"), so I subtracted 5" from 23" and 14.25" to get 18" and 9.25" as the measurements for the inside of the mitered wood. Using a speed square, I made sure the angles were 45° so that when put together, would make a 90° angle. To attach these mitered pieces to the back part of the frame, I used wood glue to attach it and clamps to keep it in place. 

![Diagram 7: Mitered front](https://user-images.githubusercontent.com/69131491/180597603-07716f25-873e-4891-9dab-844e941690f2.jpg)
fig. 7

# First Milestone (software)

[![First Milestone](https://i3.ytimg.com/vi/DvleNuCjUB4/maxresdefault.jpg)](https://www.youtube.com/watch?v=DvleNuCjUB4)

My first milestone was uploading the code from another repository onto the Raspberry Pi. There are a lot of modules (eg. weather, US holidays, news headlines, time/date) were all added to ensure I had data to display instead of just a black screen. When I first ran the program, all the modules except the weather module loaded and had data. As I was trying to fix the weather module, I ran into a few issues such as it needing an API to get the weather data from openweathermap.com. However, I didn't have an API at the time so I went on a long journey to create an API and an API key. Once I obtained both, I changed the data in the configuration module from Seattle to San Francisco. Just having an API made the module work, and I was now able to get data from the website. The code in the Raspberry Pi modules gets data from other websites. For example, the module with news headlines gets those headlines from New York Times. I also talk a little about this and point out where the weather module is on the monitor in my video.

