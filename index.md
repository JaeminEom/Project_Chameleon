---
layout: project_page
permalink: /

title: "MOGrip: Gripper for Multi-Object Grasping in Pick-and-Place Tasks Using Translational Movements of Fingers"
authors:
    Jaemin Eom<sup>1</sup>, Sung Yol Yu<sup>1</sup>, Woongbae Kim<sup>2</sup>, Chunghoon Park<sup>1,3</sup>, Kristine Yoonseo Lee<sup>1</sup>, <br> Kyu-Jin Cho<sup>1</sup>

affiliations:
    <sup>1</sup>Biorobotics Laboratory, Seoul National University
    <sup>2</sup>Korea Institute of Science and Technology
    <sup>3</sup>Global Technology Research, Samsung Electronics Co. Ltd.
paper: https://www.science.org/doi/10.1126/scirobotics.ado3939
video: https://www.youtube.com/watch?v=qFD562zo4Vk
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Humans use their dexterous fingers and adaptable palm in various multi-object 
grasping strategies to efficiently move multiple objects together in various situations. 
Advanced manipulation skills, such as finger-to-palm translation and palm-to-finger 
translation, enhance the dexterity in multiobject grasping. These translational movements 
allow the fingers to transfer the grasped objects to the palm for storage, enabling the 
fingers to freely perform various pick-and-place tasks while the palm stores multiple 
objects. However, conventional grippers, although able to handle multiple objects 
simultaneously, lack this integrated functionality, which combines the palm’s 
storage with the fingers’ precise placement. Here, we introduce a gripper for 
multi-object grasping that applies translational movements of fingertips 
to leverage the synergistic use of fingers and the palm for enhanced 
pick-and-place functionality. The proposed gripper consists of four fingers 
and an adaptive conveyor palm. The fingers sequentially grasp and transfer objects 
to the palm, where the objects are stored simultaneously, allowing the gripper to move 
multiple objects at once. Furthermore, by reversing this process, the fingers retrieve 
the stored objects and place them one by one in the desired position and orientation. 
A finger design for simple object translating and a palm design for simultaneous object 
storing were proposed and validated. In addition, the time efficiency and pick-and-place 
capabilities of the developed gripper were demonstrated. Our work shows the potential of 
finger translation to enhance functionality and broaden the applicability of multi-object 
grasping.
        </div>
    </div>
</div>

---

<div style="text-align: center;">
    <h2>Video</h2>
</div>

<div align="center">
    <iframe width="640" height="360" 
            src="https://www.youtube.com/embed/qFD562zo4Vk" 
            frameborder="0" allowfullscreen>
    </iframe>
</div>

---

<div class="columns">
    <!-- Left Column: YouTube 비디오 (Visual Effects) -->
    <div class="column">
        <h3 class="title">Demo - Logistics</h3>
        <p>Using <em>nerfies</em> you can create fun visual effects. This Dolly zoom effect would be impossible without nerfies since it would require going through a wall.</p>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/ecViSuzARwk?autoplay=1&mute=1&loop=1&playlist=ecViSuzARwk&controls=0"
                frameborder="0" allowfullscreen>
        </iframe>
    </div>

    <!-- Right Column: YouTube 비디오 (Matting) -->
    <div class="column">
        <h3 class="title">Comparison - Single-Object Grasping</h3>
        <p>As a byproduct of our method, we can also solve the matting problem by ignoring samples that fall outside of a bounding box during rendering..</p>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/-rwAbY39Fcw?autoplay=1&mute=1&loop=1&playlist=-rwAbY39Fcw&controls=0"
                frameborder="0" allowfullscreen>
        </iframe>
    </div>
</div>

<br>

<div class="columns">
    <!-- Left Column: YouTube 비디오 (Visual Effects) -->
    <div class="column">
        <h3 class="title">Demo - Domestics</h3>
        <p>Using <em>nerfies</em> you can create fun visual effects. This Dolly zoom effect would be impossible without nerfies since it would require going through a wall.</p>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/5ofxzuH4yJU?autoplay=1&mute=1&loop=1&playlist=5ofxzuH4yJU&controls=0"
                frameborder="0" allowfullscreen>
        </iframe>
    </div>

    <!-- Right Column: YouTube 비디오 (Matting) -->
    <div class="column">
        <h3 class="title">Pick and Place Various Objects</h3>
        <p>As a byproduct of our method, we can also solve the matting problem by ignoring samples that fall outside of a bounding box during rendering.</p>
        <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/eDikWCNutgM?autoplay=1&mute=1&loop=1&playlist=eDikWCNutgM&controls=0"
                frameborder="0" allowfullscreen>
        </iframe>
    </div>
</div>

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
    <h2>Citation</h2>
</div>

```
@article{eom2024mogrip,
  title={MOGrip: Gripper for multiobject grasping in pick-and-place tasks using translational movements of fingers},
  author={Eom, Jaemin and Yu, Sung Yol and Kim, Woongbae and Park, Chunghoon and Lee, Kristine Yoonseo and Cho, Kyu-Jin},
  journal={Science Robotics},
  volume={9},
  number={97},
  pages={eado3939},
  year={2024},
  publisher={American Association for the Advancement of Science}
}
```
