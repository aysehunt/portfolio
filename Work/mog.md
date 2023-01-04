---
order: E
---

# Museum of Glass
---
# Designing an interactive museum kiosk

## Situation

This project was a collaboration between the Museum of Glass in Tacoma, WA and students at the University of Puget Sound. The team consisted of my peers Nick Bigger, Marwan Johnson, Kayla Ramos and myself. This project was active from November 2018 to June 2019. This work was the basis for my Capstone project at the end of my Computer Science degree. 

![Outside the museum. Credit: Museum of Glass](/static/MOG+Crystal+Ball+Finals.jpeg/)

This project was motivated by my previous research on the role of educational technology in art museums. I was curious how digital tools might be able to provide additional context for the art pieces in the museum's collection. I approached curators at the Museum of Glass to see if they would be open to collaborating and they were excited to work with me to design something new for the museum. Katie Buckingham, curator, and Rebecca Engelhardt, collections/exhibitions manager, were our main contacts for this project.

## Task

Curators expressed a desire to showcase video content that was only available on the museum's website. Something unique about the Museum of Glass is their Hot Shop--a studio space where artists can blow glass and visitors can watch the process live. On the museum's website, there were videos of artists making pieces of art that are part of the museum's collection. 

I suggested that we try to create an interactive object label that would sit next to a piece of art. Unlike a traditional written description of the piece, visitors could watch videos of the artist describing their process and actually creating the piece in front of them.

-![Here are examples of traditional object labels with written descriptions of pieces. Occasionally these labels will have correspond to part of a museum's audio guide. I took this picture at the de Young.](/static/traditional_label.jpeg)

I pitched the project to the Computer Science seniors at my college. I selected 3 students who has applied to join my team, and we started working on the kiosk.

![](/static/mog_team.png)

## Action

We decided create an Android application that would displayed on a locked tablet. This decision was partially movitated by budget--we knew that Android tablets would be less expensive for the museum to purchase. Additionally, the tablet was a good size for this context. We wanted the label to be big enough to be easy to read, but not so big that it detracts from the art itself.

After deciding that we were building an application in the Android environment, we had to refine exactly what kind of information the label would convey. Below is an initial sketch I created, as well as a wireframe Nick created.

![**Left**: Initial sketch of the object label; **Right**: A wireframe of what the homepage of the label might look like.](/static/mog_sketch.png)

Katie and Rebecca requested that we create an application that they can log into and edit on their own--rather than pulling directly from the online catalogue. This allows for flexibility, and avoided some concerns they had about the format of their database. 

During this initial phase, Marwan explored how to create an admin portal that the front-end could pull information from. Kayla focused on security considerations, including how to prevent visitors from closing the app and using other tablet features. 

We also visited the museum to get a sense of the space, and to meet with exhibition designers. We shared the measurements of the tablet we were testing on, and brainstormed ideas for how to enclose the tablet in a secure way.

## Result

We opted to use a tabbed layout in the final design. Below is a sample of what visitors would see in the application:

+++ Artist
![](/static/artist.jpeg)
+++ Work
![](/static/work.jpeg)
+++ Video
![](/static/mog_video.jpeg)
+++

Below is a sample of what an admin would see in the application:

+++ Artist (admin view)
![](/static/admin_artist.jpeg)
+++ Work (admin view)
![](/static/admin_work.jpeg)
+++ Video (admin view)
![](/static/admin_video.jpeg)
+++

We delivered a presentation introducing the museum team to the app. We made a point to explain how the admin portal works, and how to reset credentials in the event of a forgotten password. The interactive label was planned for installation in late 2019.





