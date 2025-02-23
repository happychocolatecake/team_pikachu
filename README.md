Our website is designed to provide a safe and welcoming space for kids where they can express themselves freely while enjoying fun activities. In today’s world, it’s important for children to have a platform where they can connect, share their thoughts, and engage in creative ways that make them feel heard and understood. We’ve built our site to be a place where young users can explore their interests, play games, and take part in activities that foster their growth and happiness. It’s all about creating an environment where children feel comfortable and empowered, without fear of judgment or negativity.

A significant focus of our website is addressing the issue of bullying, which many children unfortunately face in different environments. Bullying can have a lasting emotional impact on kids, making it crucial for them to know that they are not alone and that support is available. We’ve dedicated efforts to incorporate resources, stories, and games that specifically target this issue. Our stories are designed to provide comfort, inspiration, and hope for children going through difficult experiences, while our games encourage positive interaction and resilience. The website offers a safe outlet for kids to talk about their experiences and find coping strategies that can help them deal with bullying.

In addition to tackling bullying, our website aims to entertain and engage kids through fun, age-appropriate games and activities. These not only serve as a way to relax and enjoy time online but also provide valuable lessons in teamwork, problem-solving, and emotional intelligence. By incorporating elements of play into the healing process, we hope to create a balance between addressing serious issues like bullying and offering moments of joy and relaxation. Whether it's through engaging stories, interactive games, or encouraging positive discussions, our website is here to provide a supportive and fun environment for kids to thrive in.

--
# apple_catcher_pikachu

this game is made up of a lot of different scripts in order to create a game where apples fall from the sky, and pikachu has three lives in order to catch as many apples as he can. Once three lives are gone

pikachuController.js:
This script handles the pikachu movement, using Input.mousePosition and transform.position to make the pikachu follow the cursor, keeping its y and z values the same and constraining it to keep the pikachu moving along the x-axis within the correct bounds.
It also handles lives and losing them but it uses another script for handling the image change of the healthbar
(LifeHandling.js)

gameController.js:
handles the game screen loading not loading, directs to functions that are suposed to occur when the event losing a life is triggered

appleDuplicator.js:
using prefabs creates apples infinitely until the pikachus lives run out.

appleCollider.js:
uses boxcollider 2D and detects whether it hits the pikachus collider at all or doesnt hit the pikachu and only hits the barrier instead, then responds accordingly as the apple fell without the pikachu catching it.


