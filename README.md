# What design choices did you make (colors, fonts, layout)?
On the color I chose to use soft beige as background or dirty white make it feel warm not like the general white background. I put the picture and the overall layout to be centered to be consistent and balanced. I kept the font dark to match the contrast with the white background. 

I put everything inside the scrollview and vertical linear layout so that it wouldn’t destroy the layout and keep it clean. I also added the icons which took a while especially to add, it is to make the UI more intuitive. I also kept the font consistent throughout other than the name to make it stand out.

# How did you ensure the screen is user-friendly and accessible?

I tried my best to make it accessible, though I'm still learning. I used good contrast between text and background, added icons to help identify sections quickly, made the Edit Button large enough to tap easily, and kept the layout simple and straightforward. I also added the content descriptions because I saw it on a video and figure it is for the talk back feature.

The biggest challenge was working with ConstraintLayout in Android Studio. I had a really hard time understanding how constraints work and getting elements to stay centered. Elements kept overlapping or shifting unexpectedly when I added new ones. I spent a lot of time in the Design view dragging connection lines and trying different combinations. The landscape orientation was another struggle—the content was getting cut off initially. I managed to fix this by implementing a ScrollView with help from a YouTube video, which allowed the content to scroll properly in both orientations.

# What would you improve if this were a real app?

If this were a real app, I would make the email and phone number clickable to open the email client or dialer. I'd add proper state management and implement actual editing functionality for the Edit Button. For accessibility, I should use tools to check color contrast ratios properly.. 

For design improvements, I'd add the ability to upload a real photo, include proper navigation with a back button, add animations for a more polished feel, and implement validation for contact information. Looking back, I should have planned the constraint structure on paper first. This project taught me a lot about Android UI development and showed me how much I still need to learn about layouts and handling different device configurations.
