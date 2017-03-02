---
title: "Fluid powered robots for surgery"
tags: [surgical-robotics, fluid-power, endoscopy, medical-devices, natural-orifice surgery, hydraulics, minimally-invasive-surgery]
category: thesis
permalink: 2017/03/hydraulic-robots-for-surgery
post_author: Devin R. Berg
author_url: http://www.devinberg.com
layout: post
comments: true
---

**Paper title: Design of a Hydraulic Dexterous Manipulator for Minimally Invasive Surgery**  
**DOI: [10.6084/m9.figshare.963287](https://doi.org/10.6084/m9.figshare.963287)**

Robots have the potential to transform how surgery is performed. For example, the use of robots could result in surgery being safer, faster, and more efficient<sup id="a1">[1](#f1)</sup>. Other advantages are also possible such as enabling a surgery to be performed in one location while the surgeon is in a completely different location<sup id="a2">[2](#f2)</sup>. Currently, there are not too many robots on the market or being used in everyday surgery. The most notable one is the da Vinci Surgical System<sup id="a3">[3](#f3)</sup> made by a company called Intuitive Surgical. This machine is a _laparoscopic_ device which means that it access to the patient's body through small incisions in the abdomen. Some challenges with this approach are that the da Vinci robot is quite large and prohibitively expensive for many hospitals. Additionally, the incisions that are required for this type of surgery, while better than open surgery, still require significant time for healing and the use of pain medication.

One alternative approach is to use one of the bodies natural orifices to access the patient's body. For example, a robot could be inserted into the patient's mouth and then pass through the stomach to perform the surgery as shown in the figure below. The main benefit of this approach is that the patient experiences less pain and a shorter recovery time<sup id="a4">[4](#f4)</sup>.

![Illustration of the robotic design during a procedure showing access to the abdomen gained through an incision in the stomach wall.](/images/2017-03-hydraulic-robots-for-surgery-abdomen-access.png)

For this type of surgery to be possible, first we need to develop the tools to make it happen. That was the primary goal of my PhD thesis described here. My approach was to design a robot which is powered hydraulically (using a fluid under pressure). This allows the robot to be smaller and more capable than some of the other common methods for controlling robots.

To understand the needs of the design, it was first necessary to identify the design requirements for this type of robot as well as the considerations unique to this approach. For example, I needed to know how far the robot needed to be able to reach and how heavy of a load would it need to be able to lift. Through research and experimentation, I determined that the ability to move up-and-down and side-to-side by 5 cm (about 2 inches) and to lift 5 Newtons (a little over a pound) would be sufficient.

Next to think about the design of the robot to achieve these goals. The main components of my design are a valve to control the pressure and flow of the fluid, the actuators that make the robot move when the valve directs fluid into them, and method by which all of these things are assembled together. Each piece of the robot, shown in the figure below, had to be sized such that the entire thing is less than 20 mm (just under an inch) wide! That was a challenge.

![Computer model showing internal system components for a single manipulator section in an exploded view.](/images/2017-03-hydraulic-robots-for-surgery-system-internals-exploded.png)

Putting the entire thing together, you end up with a robot that looks a little like it has octopus arms.

![Computer model showing robot assembled.](/images/2017-03-hydraulic-robots-for-surgery-system-unlabeled.png)

The main advantages of this robot are that the pieces that go inside the patient can be much smaller, it is more cost effective, and the overall size is much smaller than what is on the market today. This would likely make it a reasonable option for smaller clinics, use in an out-patient setting, or on the battlefield. Being cheaper would make it accessible to hospitals in rural locations or in developing countries. I believe that this design meets the needs of modern surgery and addresses some of the limitations of existing surgical robots.


### References
<b id="f1">1</b> G. Hubens, H. Coveliers, L. Balliu, M. Ruppert, and W. Vaneerdeweg. A performance study comparing manual and robotically assisted laparoscopic surgery using the da Vinci system. Surgical Endoscopy, 17(10):1595–1599, 2003. [↩](#a1)

<b id="f2">2</b> G.H. Ballantyne. Robotic surgery, telerobotic surgery, telepresence, and telementoring. Surgical Endoscopy, 16(10):1389–1402, 2002. [↩](#a2)

<b id="f3">3</b>  da Vinci Surgical System. [https://www.intuitivesurgical.com/products/davinci_surgical_system/](https://www.intuitivesurgical.com/products/davinci_surgical_system/). [↩](#a3)

<b id="f4">4</b>  L. Barclay. Natural orifice translumenal endoscopic surgery may allow incisionless operations. Medscape Medical News, 2008. [http://www.medscape.com/viewarticle/578108](http://www.medscape.com/viewarticle/578108). [↩](#a4)

### Citation:
```
@phdthesis{berg2013DexterousManipulator,
  author       = {Devin R. Berg}, 
  title        = {Design of a Hydraulic Dexterous Manipulator for Minimally Invasive Surgery},
  school       = {University of Minnesota},
  year         = 2013,
  address      = {Minneapolis, MN},
  month        = 9,
  doi          = {10.6084/m9.figshare.963287},
  url          = {http://hdl.handle.net/11299/159593}
}
```