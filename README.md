# Lesson Plan Template

## Topics Covered / Goals
In this section, list out all of the topics you will be covering in this lesson
- Topic 1
- Topic 2
- Topic 3

## Lesson
Write out a paragraph here (if applicable) on why this lesson is important, how it relates to what they'll be doing in the industry, etc. This section essentially acts as an introductory paragraph

### Topic 1
Each section should provide a bit of background on the topic (2-3 sentences), code samples demonstrating the topic, and explanations on what each line of code does. It should be written in such a way where a student who has not seen the material before can read through and understand what to do. Code Platoon's philosophy follows an "I do, you do" approach; instructors demonstrate the technology in the morning during a 2-3 hour lecture and then the students have time in the afternoon to practice the material by walking through the lecture and lesson plan's code before moving onto the assignments. We do not follow the "I do, we do, you do" approach because there are too many students and the range of mistakes students can make when following along (i.e., "we do") would increase class time exponentially.

For each topic, assume that the student knows nothing and needs a walk through from start to finish. Avoid acronyms unless they are defined beforehand, and unless explicitly taught in previous lessons, explain all concepts needed to build up to the topic for the day.

### Topic 2
Etc etc

### Topic 3
Etc etc

## Resources
- List out any additional
- External resources that
- Students may find helpful

## Assignments
There should be a minimum of 1-2 challenges that students should be able to complete in 2-4 hours. Ideally, it would be something that they could open a pull request against the `main` branch for so that instructors can easily view their progress. If a pull request is not possible (e.g., set up an EC2 instance in US-East that's configured with XYZ), perhaps students can create a screen recording, upload that video to Youtube, and link it in a PR against the assignment repo. It may take up to an equal amount of time to write good challenges as it does to write curriculum. Think through these questions:
- What skills did we teach in class today?
- Which of those skills are necessary for getting employed as a junior developer?
- How can they practice those skills? How can they show that they know those skills to employers?
- What kind of an assignment can I write to help them practice the skills we learned today? Are they coding in this assignment (preferable) or just regurgitating facts (less preferable)? 

From there, think of a student's end product and what they need in order to get there. If we're covering CICD pipelines and publishing code to an EC2 instance, students would need a challenge that guides them through:
- Writing a YAML file with certain configurations (you need to provide a boilerplate)
- Documentation on how to use that YAML file to create a Github Actions (GHA) job (something you need to provide)
- Creating an action on a forked repository
- Creating an EC2 instance that allowlists a certain GHA host
- Testing that the YAML file they wrote actually pushes code onto the EC2 instance

There are a lot of underlying skills required to even understand the prompts that I wrote above - was this _explicitly_ covered in class either today or in previous days?
