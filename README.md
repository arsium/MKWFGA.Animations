# MKWFGA.Animations
Animations from Win32API simplified ! Thx to pinvoke for giving the function ! Works with all controls and description for all animations ! 

How to use ? Simple , just add dll to your project and then write code like :  MKWFGA.Animations.Animation(HanldeOfControl, TimeDuration, AnimtedFlags.YourChoiceOfAnimation)

Sample : 

* -MKWFGA.Animations.Animation(Button2.Handle, 7000, AnimtedFlags.SlideBTT)
* -MKWFGA.Animations.Animation(Me.Handle, 7000, AnimtedFlags.Hide Or AnimtedFlags.SlideBTT)

If you want to close your exe after launching hide animation : 

* -MKWFGA.Animations.Animation(Me.Handle, 7000, AnimtedFlags.Hide Or AnimtedFlags.SlideBTT, True)


All animations : 

* -Blend
* -Hide
* -Center
* -SlideLTR (slide left to right)
* -SlideRTL (slide right to left)
* -SlideTTB (slide top to bottom)
* -SlideBTT (slide bottom to top)

