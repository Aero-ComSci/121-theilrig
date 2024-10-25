[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/QKp42A0s)
# 121CAT

1.Follow all of the steps on the [Book](https://pltw.read.inkling.com/a/b/5310c007377c46e28d745961310f0c2e/p/93f2c351e3c34598b8b71bf2ebc40abe)    

done

2. Complete the addigional features:
   ![image](https://github.com/user-attachments/assets/f99d7777-6fea-47e5-bf9a-fc452f835952)

   done
   

4. Create a video of the app working with all of the additional features. Make the video small enough to render here or upload to a video service witha aviawable link.

   ![Here](https://github.com/Aero-ComSci/121-theilrig/blob/7e7d0f232cc466999d1f65adb69f75537b0a4563/csp%20121%20turtle%20catch.mp4)

6. Choose two snapshots of code that demonstrate the algorithm(s) used to implement the additional features. Explain the code in the screenshots.

   `

         def randomize(turt):
          """Randomizes the turtle's shape, color, and size."""
          turtle_shapes = ["arrow", "turtle", "circle", "square", "triangle", "classic"]
          turtle_colors = ["red", "blue", "green", "orange", "purple", "gold"]
   
          turt.shape(random.choice(turtle_shapes))
          turt.color(random.choice(turtle_colors))
          turt.shapesize(random.randint(1, 3), random.randint(1, 3), random.randint(1, 3))
   `

   First snapshot of the code, shows the additional feature of the changing shape, size and color. Using the random library any color, size, or shape is picked from their respective lists and then inputted into the inbuit turtle function.


   `
   
          def stamp(x, y):
          stamp = trtl.Turtle()
          teleportation(stamp, [x, y])
          stamp.shape("sqaure")
          stamp.color("black")

   `
   The second snapshot shows the stamp feature, it creates a dummy turtle object thats a different color than all the avialbe ones listed in the previous functions. Then it moves it to the same location as the turtle itself fufilling its purpose of stamping where the turtle is 



