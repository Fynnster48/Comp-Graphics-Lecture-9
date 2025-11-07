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


