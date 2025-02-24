---
layout: project_page
permalink: /

title: "Compliant Suction Gripper With Seamless Deployment and Retraction for Robust Picking Against Depth and Tilt Errors"
authors:
    Yuna Yoo<sup>1*</sup>, Jaemin Eom<sup>1*</sup>, MinJo Park<sup>1</sup>, Kyu-Jin Cho<sup>1</sup>

affiliations:
    <sup>1</sup>Biorobotics Laboratory, Seoul National University
    <br> (* Yuna Yoo and Jaemin Eom contributed equally to this work.)
paper: https://ieeexplore.ieee.org/document/10024348
video: https://www.youtube.com/watch?v=5f0qXYcE3nw
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Applying suction grippers in unstructured environments is a challenging task because of depth and tilt errors in vision systems, requiring additional costs in elaborate sensing and control. To reduce additional costs, suction grippers with compliant bodies or mechanisms have been proposed; however, their bulkiness and limited allowable error hinder their use in complex environments with large errors. Here, we propose a compact suction gripper that can pick objects over a wide range of distances and tilt angles without elaborate sensing and control. The spring-inserted gripper body deploys and conforms to distant and tilted objects until the suction cup completely seals with the object and retracts immediately after, while holding the object. This seamless deployment and retraction are enabled by connecting the gripper body and suction cup to the same vacuum source, which couples the vacuum picking and retraction of the gripper body. Experimental results validated that the proposed gripper can pick objects within 79 mm, which is 1.4 times the initial length, and can pick objects with tilt angles up to 60°. The feasibility of the gripper was verified by demonstrations, including picking objects of different heights from the same picking height and the bin picking of transparent objects.
        </div>
    </div>
</div>

---

<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Video</h2>
        <div class="content has-text-justified">
This video explains the research motivation, the mechanism design of the proposed gripper, and its applications.
        </div>
    </div>
</div>

<div align="center">
    <iframe width="720" height="405" 
            src="https://www.youtube.com/embed/5f0qXYcE3nw?autoplay=1&mute=1&loop=1&playlist=5f0qXYcE3nw&controls=1&fs=1" 
            frameborder="0" allowfullscreen>
    </iframe>
</div>

---
<!-- <br> <span style="opacity: 0;">v</span> -->
<!-- distant, tilted object picking 넣기 -->

<div class="columns">
    <!-- Left Column: YouTube 비디오 (Visual Effects) -->
    <div class="column">
        <h3 class="title">Picking Distant and Tilted Objects</h3>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/VlD043Cb_BE?autoplay=1&mute=1&loop=1&playlist=VlD043Cb_BE"
                frameborder="0" allowfullscreen>
        </iframe>
        <p>The proposed gripper has a deployable body, allowing it to pick distant and tilted objects. Additionally, with its pneumatic circuit design, once the suction cup makes contact and seals with the object, it can automatically pick up the object without the need for additional contact sensing. This design enhances picking robustness against vision sensing errors. </p>
    </div>

    <!-- Right Column: YouTube 비디오 (Matting) -->
    <div class="column">
        <h3 class="title">Picking Objects of Different Heights</h3>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/tt_2sZBLOLE?autoplay=1&mute=1&loop=1&playlist=tt_2sZBLOLE"
                frameborder="0" allowfullscreen>
        </iframe>
        <p>The proposed gripper picks up objects of different heights from the same picking height. The gripper eleiminates the need for depth sensing to pick up different heights of objects.</p>
    </div>
</div>

<br>

<div class="columns">
    <!-- Left Column: YouTube 비디오 (Visual Effects) -->
    <div class="column">
        <h3 class="title">Bin Picking of Transparent Objects</h3>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/finvctjoIIE?autoplay=1&mute=1&loop=1&playlist=finvctjoIIE"
                frameborder="0" allowfullscreen>
        </iframe>
        <p>Perceiving transparent objects is a challenge in vision sensing. The proposed gripper can easily perform bin picking tasks of transparent dishes even in the presence of depth or tilt angle errors.</p>
    </div>

    <!-- Right Column: YouTube 비디오 (Matting) -->
    <div class="column">
        <h3 class="title">Depalletizing</h3>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/R-OGyXUa7Fg?autoplay=1&mute=1&loop=1&playlist=R-OGyXUa7Fg"
                frameborder="0" allowfullscreen>
        </iframe>
        <p>By arranging multiple grippers in parallel, the grippers can pick up multiple objects at different heights at once. This feature enables depalletizing when the number of grippers and the number of the objects arranged on each layer do not match.</p>
    </div>
</div>

<br>

<div class="columns">
    <!-- Left Column: YouTube 비디오 (Visual Effects) -->
    <div class="column">
        <h3 class="title">Warehouse Picking</h3>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/UYoG46ldE9o?autoplay=1&mute=1&loop=1&playlist=UYoG46ldE9o"
                frameborder="0" allowfullscreen>
        </iframe>
        <p>Extending the length of the gripper enables warehous picking in occlude environments. It has 140 mm stroke and can penetrate a narrow, deep space that cannot be reached by a manipulator.</p>
    </div>

    <!-- Right Column: YouTube 비디오 (Matting) -->
    <div class="column">
        <h3 class="title">Dynamic Picking</h3>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/CvUfYvb5tG0?autoplay=1&mute=1&loop=1&playlist=CvUfYvb5tG0"
                frameborder="0" allowfullscreen>
        </iframe>
        <p>The proposed gripper with 79 mm stroke was applied to catch a falling balloon at a speed of 1.02 m/s at a distance of 50.1 mm, demonstrating the possibility of dynamic grasping.</p>
    </div>
</div>

---

## Motivation

<h3> Is there a way to achieve robust suction picking despite vision sensing errors? </h3>

<div style="text-align: center;">
    <img src="assets/Motivation.png" alt="Animated GIF" width="80%">
</div>

<b>Depth and tilt errors</b> in vision sensing often occur, especially when handling <b>transparent objects</b>. To address this issue, previous approaches have attempted to reduce sensing errors through <b>learning-based methods</b> or by incorporating <b>additional sensing</b> (e.g., proximity sensors). However, learning-based methods still have insufficient success rates, and using additional sensors increases cost and may hinder the speed of object picking.

---

## Our Solution

<h3>Can we achieve robust picking against depth errors using only mechanical design, without additional sensors or learning?</h3>

By relying solely on <b>mechanical design</b>, we could potentially reduce costs and enable compatibility with existing <b>suction-based actuation systems</b>. To achieve this, we need to consider the following approaches:

1. <b>Designing a suction cup body</b> that can seal objects effectively, even in the presence of <b>depth and tilt errors.</b> <br>
→ <font color="red"><b>Deployable & Compliant Body</b></font>

2. <b>Proposing an actuation system (pneumatic circuit design)</b> that enables automatic picking without additional sensing or control once the suction cup seals the object. <br>
→ <font color="red"><b>Pneumatic Circuit Design</b></font>

---

## Deployable, Compliant Gripper Body

<h3> Soft Deploying Mechanism for Suction Cups </h3>

<div style="text-align: center;">
    <img src="assets/Deployable_Compliant_body.gif" alt="Animated GIF" width="80%">
</div>

The proposed gripper comprised two concentric cylindrical chambers, where the outer and inner chambers are termed as the spring-inserted gripper body and spring-inserted air tube, respectively. The gripper body retracts and deploys when negative pressure is applied or released, and the air tube provides the airway to the suction cup.

<h3> The Gripper Body Conformable to Distant and Tilted Surfaces </h3>

<div style="text-align: center;">
    <img src="assets/Chameleon_Teaser.gif" alt="Animated GIF" width="80%">
</div>

The <b>gripper body was designed as a compressible spring enclosed in a cylindrical LDPE film</b> for the following reasons: First, the gripper can be deployed at a high speed due to the restoring force of the spring. Second, the gripper can conform to tilted objects during deployment. Finally, the radially incompressible characteristics of the spring allow the gripper to retract effectively in the longitudinal direction.

The spring-inserted air tube which connects the suction cup and valve was built inside the gripper body with a compressible spring encased in a cylindrical LDPE film with the same structure as the gripper body. The radial incompressibility of the spring prevents airway clogging during the retraction.

---

## Pneumatic Circuit Design

<h3>Connect Gripper Body and Suction Cup to the Same Vacuum Source.</h3>

<video width="100%" height="auto" controls autoplay loop muted>
    <source src="assets/Picking Strategy.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

Enabling <b>seamless deployment, pick, and retraction</b> without sensing and control <b>by coupling the vacuum picking and retraction of the gripper body.</b>
- Pick up <b>distant & tilted object</b> without sensing and control.



<!-- <div style="text-align: center;">
    <img src="assets/Pipeline.png" alt="Finger-to-Palm Translation" width="100%">
</div>

<div style="display: flex; align-items: center; justify-content: center; gap: 10px;">
    <div style="width: 45%;">
        <img src="assets/Hand_Segmentation.png" alt="Finger-to-Palm Translation" width="100%">
    </div>
    <div style="width: 50%;">
        <img src="assets/Finger-to-Palm Translation via Sliding.gif" alt="Column-shaped objects" width="100%">
    </div>
</div>
<br>

Humans repeat the process of **grasping → finger-to-palm translation → storing** to gather multiple objects in the palm before transporting them. The target objects were set as **column-shaped**, as they are one of the most frequently handled objects in daily life [1]. To efficiently transfer a column-shaped object to the palm, humans slide the grasped object along the inner surface of their fingers. Since this method does not require additional motions such as wrist flipping, it is considered the most effective approach for translating column-shaped objects. Thus, **sliding-based finger-to-palm translation** was established as the key manipulation skill for the MOG Hand. -->

---

<!-- > Note: This is an example of a Jekyll-based project website template: [Github link](https://github.com/shunzh/project_website).\
> The following content is generated by ChatGPT. The figure is manually added. -->

<!-- ## Movie
<iframe width="560" height="315" src="https://www.youtube.com/embed/qFD562zo4Vk" frameborder="0" allowfullscreen></iframe> -->

<!-- ## Background
The paper "On Computable Numbers, with an Application to the Entscheidungsproblem" was published by Alan Turing in 1936. In this groundbreaking paper, Turing introduced the concept of a universal computing machine, now known as the Turing machine.

## Objective
Turing's main objective in this paper was to investigate the notion of computability and its relation to the Entscheidungsproblem (the decision problem), which is concerned with determining whether a given mathematical statement is provable or not.


## Key Ideas
1. Turing first presented the concept of a "computable number," which refers to a number that can be computed by an algorithm or a definite step-by-step process.
2. He introduced the notion of a Turing machine, an abstract computational device consisting of an infinite tape divided into cells and a read-write head. The machine can read and write symbols on the tape, move the head left or right, and transition between states based on a set of rules.
3. Turing demonstrated that the set of computable numbers is enumerable, meaning it can be listed in a systematic way, even though it is not necessarily countable.
4. He proved the existence of non-computable numbers, which cannot be computed by any Turing machine.
5. Turing showed that the Entscheidungsproblem is undecidable, meaning there is no algorithm that can determine, for any given mathematical statement, whether it is provable or not.

![Turing Machine](/static/image/Turing_machine.png)

*Figure 1: A representation of a Turing Machine. Source: [Wiki](https://en.wikipedia.org/wiki/Turing_machine).*

## Table: Comparison of Computable and Non-Computable Numbers

| Computable Numbers | Non-Computable Numbers |
|-------------------|-----------------------|
| Rational numbers, e.g., 1/2, 3/4 | Transcendental numbers, e.g., π, e |
| Algebraic numbers, e.g., √2, ∛3 | Non-algebraic numbers, e.g., √2 + √3 |
| Numbers with finite decimal representations | Numbers with infinite, non-repeating decimal representations |

He used the concept of a universal Turing machine to prove that the set of computable functions is recursively enumerable, meaning it can be listed by an algorithm.

## Significance
Turing's paper laid the foundation for the theory of computation and had a profound impact on the development of computer science. The Turing machine became a fundamental concept in theoretical computer science, serving as a theoretical model for studying the limits and capabilities of computation. Turing's work also influenced the development of programming languages, algorithms, and the design of modern computers. -->

<div style="text-align: center;">
    <h2>BibTeX</h2>
</div>

```
@article{yoo2023compliant,
  title={Compliant suction gripper with seamless deployment and retraction for robust picking against depth and tilt errors},
  author={Yoo, Yuna and Eom, Jaemin and Park, MinJo and Cho, Kyu-Jin},
  journal={IEEE Robotics and Automation Letters},
  volume={8},
  number={3},
  pages={1311--1318},
  year={2023},
  publisher={IEEE}
}
```
