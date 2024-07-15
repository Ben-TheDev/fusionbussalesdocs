# FUSION BUS SALES (Documentation)

[Click this to return to main page](https://ben-thedev.github.io)

Chassis Info:
VAR1 is the chassis we use here at Fusion.  We have many features that can be found surprising for a ROBLOX bus.  Here's a list of what we bring.


- A Breakdown system
- A working Air brake system (Air pressure)
- AC sounds
- Double flash
- Realistic suspension
- Realistic steering
- Chassis sounds
- High Idle
- Easy license plate number system
- Bus easy number system
- Working Emergency doors *If the bus body supports it*
- Working music radio using bus speakers
- Fuel simulation
- A-Chassis UI differences
- Seatbelt
- Working pedals
- Exhaust effect
- More to come

 This is our first chassis so much more will come in the future with VAR2 And VAR3




 Breakdown System |
 The breakdown system is one of the most loved things in the ROBLOX bus community and something we wish every bus had.  Most of the systems we have today are not the best and only bring very little to nothing.  Introducing the VAR Breakdown systems.  With the most “Scenarios”  on the platform and highly advanced coding systems, it is very easy to use.  It's a button to turn on and off on buses and will come with every bus.  Here is what we currently have for “Scenarios”
- A tire explosion simulation
- An engine explosion
- A transmission explosion
- A radiator explosion
- Bad battery
- Bad alternator.
- More to be added in the next versions.

 Once we have the busses done,  we will release updates and bug fixes to the VAR Breakdown system.  It will be easy to update. Easy enough that all you have to do is get rid of the old Breakdown system under plugins in the A-Chassis tune folder, And put the new one in.



 Air Pressure |
 The air pressure system is pretty easy to understand.  The Air Pressure system brings the feature of realism.  The way it works is when you first spawn your bus it will not have any air for the brakes.  So when you start up your bus it will loop and beep at you like real life telling you low air levels are detected and you have to wait for the pressure to ** build before driving.  And it won't let you drive if you don't.  When you are driving the bus you will be able to see the compressor exhaust the extra air it contains like in real life when you see the air pop out under the bus sometimes.  If you abuse the brakes at high speeds or let the bus sit for a long time chances are you will be low on air.  You can ** also see if you are low on the air pressure gauge on the A-chassis UI.



 Chassis sounds |
 You will hear random sounds from the chassis at any time when driving.  For example, transmission sounds when you shift,  When you are on a bumpy road you might hear some sound from the suspension. And much more.



 Number systems |
 The number system is another easy thing to get the hang of.  All you do is go into the Driver seats under the bus files, and there will be “Bus Number Value”  and “License Plate Number Value”  These will control what your license plate and Bus numbers say.  To change them just click on each value and input a number inside the value.



 Realistic Systems |
 The Realistic Suspension system is when you are turning or going over bumpy platforms the suspension will act similar to real life,  it will bounce the bus around and shake the bus body according to how it would in real life.  And will provide realistic steering to the bus.  Every bus is tuned to perfection so we can give you the most realistic bus on the ** ROBLOX platform.
 Working Emergency Exits |
 The working emergency exits can be found on the roof of the bus and the back of the bus,  They all work, unlike some other busses on ROBLOX.  They work on the rear of the bus and will work on the top of the bus to if the bus supports it on the roof.



 AC sounds and Music |
 The AC sounds can be turned on by pressing the AC button on your bus dashboard,  and it will play an AC sound on your bus from the location of your AC.  For the music, you can click the radio on your bus to put on a radio station for the kids in the back of your bus to listen on the ride to school!



 Seat Belt |
 The seatbelt is located on the side of your driver's seat on the bus.  Before you start driving you must click the seatbelt or the bus will continue to beep at you and display a warning on the dashboard of no seatbelt detected.



 Fuel systems |
 The fuel system is a system on your bus that can replicate real-life fuel systems.  You can run out of fuel or fill up fuel,  And your bus will warn you when you are running low. 



 High idle |
 The high idle system is a system where you can make your bus rev to the right setting, so when you idle it will make your RPM go up the rpm you need.  This can be useful for filling your bus up with air.



 Exhaust effect |
 When you start up your bus you will be able to see the bus exhaust go out of the exhaust pipe.  And if you break down or you burn oil you will see your exhaust smoke turn black!



 Pedals |
 Your bus will come with pedals that can be seen moving.  If you press the brake, you will see the brake pedal go down.  If you press the gas your gas will go down.



 Pricing and other|
 We are improving the chassis every day we move,  Know every second you watch a video,  Every second we are improving.  Here are the prices for any bus here at Fusion
- 3500 FULL SIZE  (17 USD)
- 1500 MEDIUM SIZE (12 USD)
- 1000 SMALL SIZE (9 USD)
- 550 HANDI-CAP (6 USD)

--
# PRODUCTS AND OTHER

# ALLISON TRANSMISSION
 HOW TO USE:
 FIRST INSTALL THE FILE FROM PARCEL,
 NEXT PUT THE FILE INTO ROBLOX STUDIO.
 (Recommended scale for shifter model: 0.152, You can change the scale by selecting the shifter model, go to Properties.  And change the scale by selecting it and changing the number. )
 FUSION BUS SALES GUIDE FOR SHIFTER

STEP 1: Put the "FBS Allison Shifter Addon" folder inside of A-Chassis plugins.

 STEP 1: Go into the "FBS Allison Shifter Addon" folder,  and open up Values,
 inside of Values you will see an object value named "Variables"
 Click on that and select value inside of properties, then once you selected that go to A-Chassis interface\Values and select that Value folder inside of A-Chassis Interface

 Step 2: After you made that object value the A-Chassis Values,  We have to assign the Shifter Model Value now.
  To do this,  Select Shifter Model inside of "FBS Allison Shifter Addon" Values folder.   After you selected that,  set the value of that to the "Gen 5 ALLISON TRANSMISSION" model.

 Step 3:  Enjoy your new working Shifter!

 Notes:  If you find any bugs, report it to the Fusion Bus Sales server.
![Screenshot 2024-07-14 213726](https://github.com/user-attachments/assets/499b94c1-57f7-4939-b28f-a7edc31e27c0)

# DASHBOARD LIGHT SETUP
 The guide on how to setup working dashboard lights with any bus (using any Fusion Dashboard)
 Put the code below into the bus startup script/ startup section, after that make a model named Dashlights in the bus body and put the lights into that model, after that this script should work correctly.
 ------------------------------------------------------------------------

 local dashlights = script.Parent.Parent.Parent.Body:WaitForChild("Dashlights")
 for _,Child2 in pairs(dashlights:GetChildren()) do	
 if Child2:IsA("BasePart") then
 coroutine.resume(coroutine.create(function()	
  end))
end
end
 ------------------------------------------------------------------------

 If you have any issues with this script open a ticket or bug report in the Discord server. 

# ROUTE TAG V1:

 (All you do to set the tag up is, put the Route Tag model under the Body model on any bus.  Then to change the tag number you just click each number stick.)

# AC UNIT (GUCHEN)

 (All you do to set the AC up is, put the AC  UNIT model under the Body model on any bus, if you want to add working sound then make a click detector and make a script that plays the audio off and on depending if there's a click.)

# MORE GUIDES WILL BE RELEASED LATER, EVERY TIME A NEW PRODUCT COMES OUT WE WILL ADD TO THIS DOC!
[Click this to return to main page](https://ben-thedev.github.io)
![bottom bar](https://github.com/user-attachments/assets/cfe3dac1-1f38-49ed-ae1e-04bb2127ea2c)
