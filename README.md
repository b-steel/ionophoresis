# Mandatory Medical Warning

I'm not a professional anything, and certainly not a medical professional. I'd never advise anyone to make their own at-home setup of a medical device, nor would I advise anyone to run electrical current through their body. You should consult a medical professional in all things medical and should be very careful when dealing with all things electricity. This document is solely for a record of what I have done and the results I saw, it is not designed as any sort of guide.

## My Background

I'm really sweaty, especially my hands (and feet too), and this has caused me no end of troubles when it comes to rock climbing. It's pretty priviledged and first-world-problems, but it does make it really hard to climb certain things. My friends used to call me aquaman becuase of how sweaty my hands were, but no more!

## What is Iontophoresis

[Wikipedia](https://en.wikipedia.org/wiki/Iontophoresis#Therapeutic_uses) but it's basically a medical procedure (for delivering drugs) that also happens to be useful for stopping sweating. In a nutshell electricity is run into the affected area and it stops sweating. You generally have to do a lot of sessions at the beginning of treatment (a buildup phase) and then when the desired dryness is achieved you can drop down to fewer sessions / shorter sessions (maintenance phase).

The basics of an iontophoresis setup are two pools of water, with a batter connected to both of them. When the person touches both pools (usually a hand in each) they close the electrical circuit. Electricity then flows from the battery terminal A => pool A => hand one => through the body => hand 2 => pool B => battery terminal B

## V1

I first found out abou iontophoresis through two articles([article one](https://rockclimberstrainingmanual.com/2016/09/08/witchcraft-for-perfect-skin/), [article two](https://rockclimberstrainingmanual.com/2016/09/21/iontophoresis-part-ii/)) from the anderson brothers, which in turn linked to a [third article by steven low](https://stevenlow.org/sweaty-to-dry-fingers-for-climbing-iontophoresis-and-antihydral-experiments/)

I started with the method in the anderson brothers article (two pie tins, a couple 12V batteries) as well as the "one-arm" method in their article (so that you can have the other hand free to doom scroll the internet).

Takeaways

- Doing two arms at once sucked. Can't do anything with your hands, and even if you put on a video or something it's always going to end early or need an ad closed or paused and then you gotta take a hand out and dry it off and it just sux. One arm method is much better.
- Doing two arms is also kinda scary, you're literally running electricity through your heart which freaks me out a bit.
- The one arm method is also super annoying in how you have to set things up with the armband and all that crap.
- I didn't see any appreciable changes in my skin! Having done it different and seen results (keep reading) I attribute this to a couple things. One is that I probably didn't do it frequently enough / long enough (both within a session and just for enough sessions) since it was annoying as hell to setup. Two is that when doing both hands you have nothing to really compare it to so its' very hard to tell if it's working as the change is sometimes slow to appear.

## V2

A couple years later I got fed up with sliming off projects and decided to give it another go and see if I could be more discernign about the results. This time I decided to make a couple changes

- Do only one hand for the initial buildup phase so I'd have a control hand to compare to
- Do the one arm method, but instead of having the whole hand connected to one pole and my arm connected to the other, I wanted a setup with my palm attached to one pole and my fingers attached to the other (to avoid the stupid armband).

To build a one-hand setup you need basically a tray with two, electically separated pools of water. My first prototype was a lid from a yogurt container. I glued a divider down the middle, cut up some plastic to line each side with (so each side can't leak to the other) and I lined the bottom with pennies (to conduct electricity - no idea if this helped or not), and a bit of cloth over the pennies (so I'm not touching the pennies themselves, just the water - again, no idea if this is necessary). Then I'd place my hand in the two pools with the divider running along the crease between my palm and my fingers.

This design had some flaws:

- Yogurt container lids are not deep, spilled a lot of water and just wasn't a deep enough pool to really put the hand in easily
- Gluing a divider and lining with plastic did not create a very watertight barrier and so not all the electricity flowed into my hands

## The results

After a bit of doing this on one hand only I was able to definitively say that it made a huge difference. I could end a climb at the gym with one hand completely dry and still chalky and the other pink and damp. The contrast was crazy!

My latest setup prevents my full palm from sitting in the water and so only parts of my palm get the effect (not ideal, but it really shows the difference). Excuse the dirt on my hands but you can clearly see where the skin doesn't sweat on my palms and where it still does.

![Palm with sweaty / dry zones](/docs/assets//palm-zones.jpg)

## V3

My latest setup invovles a tray that I 3D printed so I have two waterproof pools and the divider kinda mirrors the shape of my hand. I put two metal plates in the bottom with tabs to clip the electrical leads to and then felt on top of that so I have something that I can rest my hands on. I use a [small voltage converter](https://www.amazon.com/Converter-Fast-Charge-AFC%EF%BC%8CPortable-Regulator-Electronic/dp/B07V3L4YF3/ref=sr_1_26?crid=3J4EOLHA05LGJ&dib=eyJ2IjoiMSJ9.4wkiCYItuy8Df_wQP-15oeNpyPdaz-whHyVpu_xFYZN42MGpEnBSE3anbKuhTCD7MxdjBt6M9_XgQ34YTCVPq1KpP8MPTvF10gqp7TlXr804Ue-4dMxVYfGpx4uCs8L-epZDNacto1sHCCQRBre3-DOpakalfhMKKjbw31fJfXJrJ4q36015mlvgaExXnqKkbQ1XWZhH-wfZLqAASi0mU88CFkrLhTQ-83ptlc_rAw93y6PzhLqm3a5rtSYlpC6Ax10DkIeS_14sRaowjefzy-zUnOLqMFDsYzXxEGPvsiY.fgH3nrIQDBKdsDqSIZjM6gUIv51o_Eq5a3DwTNtxXO4&dib_tag=se&keywords=usb%20voltage%20converter&qid=1715646086&sprefix=usb%20voltage%20converter%2Caps%2C160&sr=8-26) to get 30V (and basically 0 amps) outo of a standard 5V/2A usb battery pack.
![My Setup](/docs/assets//full-setup.jpg)

The Cad files are here. I had to break it into two halves to get it to print on the setup I had available (maximum print time constraints)

[full-tray](/docs/assets/cad-full-tray.stl)

[bottom-half](/docs/assets/cad-bottom-half.stl)

[top-half](/docs/assets/cad-top-half.stl)

[Hosted CAD File](https://cad.onshape.com/documents/358d6bc95a9c8394224e5c80/w/a07359f18c6174ad24c437c7/e/8b2232772dcb389f96baf7fa?renderMode=0&uiState=665f376e9423fe3290444116)

## Doseage

There is a bit of a buildup period where you have to do it a lot at the beginning but then can drop the session frequency into "maintenance" mode and you just need top-up sessions every once in a while. The sessions vary for people so how frequent (both in the build up and maintenance phase) and how long depends on the person (and probably seasonal w/ temps too). I still haven't teased out my minimum effective dose, but so far I've been doing it 2x a week for about 15-20 min per hand while I watch TV. I don't remember how often I did it for the buildup phase but I think it was more like 4x a week for the same amount of time per session. If I recall correctlly it took approximately 6 sessions or so before I started seeing a difference and maybe 8-10 before I got to a good level of dryness.

## Future Experiments

I'd like to experiment with a handful of things

- How voltage / current affects thigns
- minimum effective doseage, session frequency vs session length
- does current direction matter
- salting the water and how that affects electrical resistance and thus results
