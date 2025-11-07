# Comp-Graphics-Lecture-9

**Material Vertex Fragment Shader**

![2025-11-0716-13-08-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/92bb4d1f-83b0-4aee-8c63-b897a1bc1d47)

When playing around with the vertex fragment shader, I noticed that I could make grid-like patterns, which I will keep in mind for the future to use.


**Simple Shadow Shader**

<img width="658" height="497" alt="image" src="https://github.com/user-attachments/assets/cd83e269-3fc4-4bfe-8cd7-9ff874e3684c" />


<img width="497" height="460" alt="image" src="https://github.com/user-attachments/assets/0d8b2029-08a2-49c8-b18c-1e0db05260be" />


The Simple Shadow Shader doesn't take into account objects' shadows casting onto the ground or other objects so the back of the material turns very dark due to the shader but the front is bright.


**Second Shadow Texture**

<img width="879" height="529" alt="image" src="https://github.com/user-attachments/assets/41cc1928-3fa0-4930-bf03-187049289339" />

The second shadow shader makes other objects' shadows into a selected texture. In the image, it is set as just grass, but I imagine this could be used for things like glass, where the shadow has a tint, so you can make the glass shadow tinted red if it is a red glass pane.

**Glass**

<img width="795" height="625" alt="image" src="https://github.com/user-attachments/assets/056f663a-1ee8-40e4-92e0-ebedad6e7ff8" />



**Water Texture 1**

![2025-11-0716-28-11-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/3ba5afe6-6a15-414c-ad85-21d516b47393)

The first water texture we did creates a ripple effect, which can be used for water as originally implied, and I like the way it looks, so I am thinking of using it in my GDW game for water. But when I was looking at the shader, I thought of more uses; one of these is a flag. So I made a flag with the silly cat on it to show off how it looked.


**Water Texture 2**

![2025-11-0716-33-46-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/8c5139ce-de1e-4a44-a0aa-a75daf34f073)

The second water texture is flat, but lets you add a foam texture on top that goes at a different rate. In the first plane shown, it is doing the intended use, and in the second plane, you can see two photos of the silly cat going over each other. These remind me of goofy edits.
