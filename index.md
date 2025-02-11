---
layout: project_page
permalink: /

title: "Compliant Suction Gripper With Seamless Deployment and Retraction for Robust Picking Against Depth and Tilt Errors"
authors:
    Yuna Yoo<sup>1*</sup>, Jaemin Eom<sup>1*</sup>, MinJo Park<sup>1</sup>, Kyu-Jin Cho<sup>1</sup>

affiliations:
    <sup>1</sup>Biorobotics Laboratory, Seoul National University
    <br> (* Yuna Yoo and Jaemin Eom contributed equally to this work.)
paper: https://www.science.org/doi/10.1126/scirobotics.ado3939
video: https://www.youtube.com/watch?v=qFD562zo4Vk
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
    <iframe width="640" height="360" 
            src="https://www.youtube.com/embed/5f0qXYcE3nw" 
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
