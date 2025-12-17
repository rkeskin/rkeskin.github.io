---
permalink: /
title: "Career Objective"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I conduct research on robust control, safety-critical control, and machine learning techniques in power electronics, power systems, and robotics to address challenges posed by dynamic uncertainties in real‐world feedback control implementations. My first priority in projects is to convert the design problem into convex formulations that can be solved with semi-definite programming (SDP), quadratic programming (QP), and second-order cone programming (SOCP) for which unique optimal solutions. In particular, I focused on a class of learning-based control methods and control architectures that can respond to system faults or uncertainties online. However, by leveraging experience in the form of offline/online data and the synthesizing power of machine learning (ML), we can develop a model of the residual dynamics that can anticipate and proactively compensate for disturbances. This approach allows us to achieve control systems that are stable, robust, and agile while being able to learn and continuously improve the performance of the control system.

Collaboration
======
I welcome opportunities for academic and industrial collaboration in the areas of power electronics, robotics, industrial control systems, robust control, safety-critical control, and optimization-based control design. Researchers and practitioners interested in joint projects, visiting research activities, co-authored publications, or funded research proposals are encouraged to contact me directly to explore potential synergies and collaborative frameworks.


Previous Research Experience
======
My research aims to address the following questions: How can we control industrial systems under parametric/non-parametric uncertainties and faulty conditions when we should/must abandon simple models for a more complex representation? How can the safe operation of the system be achieved? My past research has helped to answer this question by designing disturbance feed-forward robust $H_\infty$ fixed-order controllers and I have experienced that the classical control problem, which is converted into a convex optimization problem, can be solved after representing the uncertainty and system disturbances on the system model. My research agenda seeks to achieve performance-optimal, robust, safe autonomy by enabling trustworthy engineering systems to (a) make uncertainty-aware theoretical safety guarantees efficiently based on available information (b) bridge the gap between this theory and the hardware implementations by considering adversarial dynamics, and (c) utilize the latest computational power for an industrial system to its fullest potential. In my Ph.D. dissertation, I have proposed robust n-degree of freedom (DOF) $H_\infty$ fixed-order (e.g., PI, PID, lead/lag, Type-III) disturbance feed-forward control design methods. By that time, input voltage and load current disturbances of any power electronic converters, which are called mismatched disturbances, have not been included in control design methods as far as I know. Robust $H_\infty$ control architectures with feed-forward from the disturbances are proposed to improve the disturbance rejection performance of the mentioned disturbances of the DC-DC converters. This feed-forward perspective is well-suited for industrial applications as the input and load voltage of the electrical network could easily be measured via simple voltage divider circuits. Robustness and performance improvement of input voltage feedforward (IVFF) and 3-DOF disturbance feed-forward control architectures are discussed in this context. The infinite norm constraints of sensitivity functions of the mismatched disturbances are included as constraints in the convex-concave optimization problem. A robust IVFF framework, which is based on a new convex approach and a novel iterative optimization algorithm is proposed. The versatility of the synthesis methods is demonstrated by numerical, simulation, and experimental examples, including various circuit parameter changes, reference, input voltage, and load current disturbance effects. The outcomes of my Ph.D. studies resulted in 3 SCI (SCI-Expanded) journal papers (Journal of the Franklin Institute (Elsevier), Transactions of Measurement and Control journal (SAGE)) and 2 IEEE conference papers. One of the conference papers from my Ph.D. studies is awarded the “Best Student Paper award at the ELECO conference” in Turkey.

After the Ph.D process, I had the opportunity to join a team working on industrial systems and contribute to https://posytyf-h2020.eu/ European Union project. I have designed continuous- and discrete-time anti-windups for a grid-connected LCL-filtered voltage source inverter system (VSI) and a constraint management technique for the input- and state-constrained system under model uncertainty and faulty conditions. Particularly, I have focused on model inversion-based time-varying saturation function design and learning-based safety filter design with robust control barrier function (RaCBF) to design control and decision-making policies directly from data. 


<!--
1. Site-wide configuration
2. ------
3. The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 
4. 
5. Create content & metadata
6. ------
7. For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).
8. 
9. **Markdown generator**
10. 
11. The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
12. ) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.
13. 
14. How to edit your site's GitHub repository
15. ------
16. Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 
17. 
18. Example: editing a Markdown file for a talk
19. ![Editing a Markdown file for a talk](/images/editing-talk.png)
20. 
21. For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
