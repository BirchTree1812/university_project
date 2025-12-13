# Overview

This is the University Course Prerequisite Planner. It is a web app that uses Docker and FastAPI to plan courses for university students based on said courses' prerequisites'.

# Data
The datasets come from the following sources:
+ [University University of Illinois' Course Prerequisites](https://github.com/illinois/prerequisites-dataset?tab=readme-ov-file)
  + 8,589 course sections
  + Structured CSV with all course prerequisites
+ [Open University Learning Analytics Dataset](https://www.kaggle.com/datasets/rocki37/open-university-learning-analytics-dataset)
  + 32,593 students, 22 course presentations
  + Includes demographics, assessments, and VLE interactions
+ [coursera-course-dataset](https://huggingface.co/datasets/azrai99/coursera-course-dataset)
  + Course skills and metadata
  + Good for skill graph construction

