---
type: "project" # DON'T TOUCH THIS ! :)
date: "2020-05-16" # Date you first upload your project.
# Title of your project (we like creative title)
title: Mechanism of delusion and hallucination in schizophrenia based on the quadripartite model



# List the names of the collaborators within the [ ]. If alone, simple put your name within []
names: [MengHuaKuo]

# Your project GitHub repository URL
github_repo: [https://github.com/PSY6983-2021/project_template](https://github.com/MengHuaKuo/KuoMengHua_project)

# If you are working on a project that has website, indicate the full url including "https://" below or leave it empty.
website:

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [project, github, markdown, brainhack]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

summary: "Each project repository should have a markdown file explaining the background and objectives of the project, as well as a summary of the results, and links to the different deliverables of the project. Project reports are incorporated in the BHS [website](https://psy6983.brainhackmtl.org/project)."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

Delusion and hallucination are common symptoms in schizophrenia (SCZ). Despite of different constructs composed with, false belief and false perception still share some similar features to an extent. For instance, they are both characterized by the breakdown of corollary discharge, deficit of monitoring control, and aberrant salience function. Several researches also demonstrated collaborative neural underpinning regarding delusions and hallucinations. The intrinsic networks based on the triple network theory such as salience network (SAL), default mode network (DMN) and central executive network (CEN) are recruited during delusional or hallucinatory phenomena, reflecting some brain modules might be overlapped when the symptoms arise. A quadripartite model, which supports most of current evidences and provides a storyline trying to explain the process during hallucinations, might also be interpretable for delusions due to its involvement of the aforementioned triple network and hippocampus. Nonetheless, it still falls shorts of explaining the underlying mechanisms of both hallucination and delusion. Moreover, the precise prediction of these two symptoms is not yet completed nowadays. We hypothesize that the crucial differences between delusions and hallucinations might provide as key components for machine-learning techniques to distinguish delusional or hallucinatory phenomena.

### Tools

The "project template" project will rely on the following technologies:
 * Markdown, to structure the text.
 * The Hugo website framework which is used by the BHS website. This makes it possible to easily add the markdown project description to the website.
 * Adding the project to the website relies on github, through pull requests.

### Data

In this study, ensemble empirical mode decomposition (EEMD) was employed on voxel-wised resting-state functional Magnetic Resonance Imaging (rs-fMRI) data with regions of interest (ROI) according to the quadripartite model. We then trained multiple classifiers with the extracting features from the intrinsic model functions (IMFs) in order to figure out the discrepancy of delusions and hallucinations among brain works for future analysis. 

### Deliverables

At the end of this project, we will have:
 - Whether the absence of disease, delusion or hallucination could be predicted by machine-learning approaches
 - What fueatures are appropriate for predicting each target

## Results

  Only analysis for ROI of hippocampus is currently completed. It is showed that whether one has schizophrenia or not could only be predicted by instantaneous amplitude and instantaneous frequency. NaiveBayes model has best performance for discriminateing delusion and hallucination with original and IMF2 singal respecitively. 
### Progress overview

The project was swiftly initiated by P Bellec, based on the existing template created in 2019 by Tristan Glatard and improved by different students. It was really not that hard. Community feedback is expected to lead to rapid further improvements of this first version.

### Tools I learned during this project

 * **Meta-project** P Bellec learned how to do a meta project for the first time, which is developping a framework while using it at the same time. It felt really weird, but somehow quite fun as well.
 * **Github workflow-** The successful use of this template approach will demonstrate that it is possible to incorporate dozens of students presentation on a website collaboratively over a few weeks.
 * **Project content** Through the project reports generated using the template, it is possible to learn about what exactly the brainhack school students are working on.

### Results

#### Deliverable 1: report template

You are currently reading the report template! I will let you judge whether it is useful or not. If you think there is something that could be improved, please do not hesitate to open an issue [here](https://github.com/PSY6983-2021/project_template/issues/) and let us know.

#### Deliverable 2: project gallery

You can check out the [2020 BrainHack School project gallery](https://psy6983.brainhackmtl.org/project/)

##### ECG pupilometry pipeline by Marce Kauffmann

The repository of this project can be found [here](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann). The objective was to create a processing pipeline for ECG and pupillometry data. The motivation behind this task is that Marcel's lab (MIST Lab @ Polytechnique Montreal) was conducting a Human-Robot-Interaction user study. The repo features:
 * a [video introduction](http://www.youtube.com/watch/8ZVCNeX42_A) to the project.
 * a presentation [made in a jupyter notebook](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann/blob/master/BrainHackPresentation.ipynb) on the results of the project.
 * Notebooks for all analyses.
 * Detailed requirements files, making it easy for others to replicate the environment of the notebook.
 * An overview of the results in the markdown document.

##### Other projects
Here are other good examples of repositories:
- [Learning to manipulate biosignals with python](https://github.com/mtl-brainhack-school-2019/franclespinas-biosignals) by François Lespinasse
- [Run multivariate anaylysis to relate behavioral and electropyhysiological data](https://github.com/mtl-brainhack-school-2019/PLS_PV_Behaviour)
- [PET pipeline automation and structural MRI exploration](https://github.com/mtl-brainhack-school-2019/rwickens-sMRI-PET) by Rebekah Wickens
- [Working with PSG [EEG] data from Parkinson's patients](https://github.com/mtl-brainhack-school-2019/Soraya-sleep-data-in-PD-patients) by Cryomatrix
- [Exploring Brain Functional Activation in Adolescents Who Attempted Suicide](https://github.com/mtl-brainhack-school-2019/Anthony-Gifuni-repo) by Anthony Gifuni

#### Deliverable 3: Instructions

 To be made available soon.

## Conclusion and acknowledgement

The BHS team hope you will find this template helpful in documenting your project. Developping this template was a group effort, and benefitted from the feedback and ideas of all BHS students over the years.

You can also make submit your project to neurolibre https://neurolibre.org/. It is a preprint server for interactive data analyses. It is tailored for publishing interactive neuroscience notebooks that can seamlessly integrate data, text, code and figures.The submission instructions can be found here https://docs.neurolibre.org/en/latest/index.html and the jupyter book docs there https://jupyterbook.org/intro.html.
