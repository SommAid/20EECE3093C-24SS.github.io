# Course Project

In this assignment, you will make a meaningful contribution to an open-source project hosted on GitHub.

Your primary objective is to develop and submit a non-trivial modification (e.g., enhancement, bug fix) or additions (e.g., new feature) to an open-source project, ensuring it is crafted in a manner that maximizes the likelihood of acceptance by the project's maintainers. Your tasks include selecting an open-source project, identifying a specific change to implement, understerstanding contribution guidelines, actively contributing to the project, reporting on your insights, and reflecting on your experience.

For the rest of this assignment, we will collectively refer to the non-trivial modification and additions as tasks. You have considerable freedom in which project and tasks you choose (subject to a few requirements and recommendations), however, your selection should be dependent on your ability to fullfil all requirements of the project.  Do not pick a project or a task that will make it difficult for you to complete any of the requirements.

A very common source of student uncertainty or stress will be the realization that near the due date, that a project or task that was not technically against the rules will make it very difficult for you to present all of the evidence required to get all of the points for the course project.


## Requirements

The following aspects of project or task selection are firm requirements and cannot be waived. If you found a project or task that seems really great but does not satisfy one of these rules, you must regretfully pick another instead. 

It is easy for students to mess up by working depth first, you should work breadth first to ensure that you cover all of the requirements.

1. The tasks must be scoped such that you spend at **least** ~24 hours on the project. For example, this might be ~7 hours to identify a project and get the lay of the land; ~12 hours to create a work list, design, and execute your changes; and ~5 hours to reflect and prepare your report.
2. You may choose one large task or several smaller tasks. (If you are working with a partner, choose twice as much. Choose tasks that benefit from teamwork and are appropriate for your team size — do not select one small independent task per team member.)
    > It is entirely acceptable to list a number of tasks and indicate that you will stop after a few if you have spent the requisite amount of time and have all of the required reporting material.
    > Similarly, it is acceptable to list a large task and subdivide it into smaller activities, indicating that you will stop after you have spent the requisite amount of time and have all of the required reporting material.
3. The task(s) must be taken from a bug report or feature request in the public database, following the protocol the project uses to communicate and track open issues. Both the project as a whole, and the particular issue(s) you choose, must be public on GitHub.
4. You may pick a project, project type, or task type with which you have previous experience. Some students leverage their previous expertise to make this easier, some students push in new directions to ensure that they learn more. Both are perfectly acceptable.
5. You must pick exactly one project per team. Even if your team has two people, you must restriction attention to exactly one project, not two or more at the same time. All of your tasks must come from the same single project.
6. You may not pick a project owned or managed by yourself or another UC student You may pick a project managed by a non-student organization at UC.
7. You may not be involved in the genesis of the bug report or feature request in any way. Do not invent a project need or create your own.
8. You may not knowingly pick an issue created by another UC student or have your code reviewed by another UC student. If you know a maintainer of the project, or otherwise have a conflict of interest, you must pick issues that were posted before the start of the semester.
9. The task must require changes to the project's source code. Pure graphical, documentation or design or tasks are not appropriate.


## Recommendations

Tthere are a number of very strong recommendations that you almost certainly should follow. While you are allowed to disregard these recommendations, doing so will almost certainly result in a lower grade because you will not be able to provide sufficient evidence for all of the reporting obligations. 

1. The project should be active, with many contributors. (If you are not certain, you can use statistics on GitHub to compare across various projects.) 
1. The task should not be limited to the implementation of an algorithm or data structure as this would likely not result in enough evidence that you have mastered requirements elicitation, code comprehension and dependent coding within a large code base you did not write, since the requirements for the algorithm are too direct. 
1. The task should not be a pure frontend activity that involves no testing. This activity would not result in enough evidence that you have mastered aspects of quality assurance (e.g., testing, code reviews).
1. The task or project should not involve sensitive information that you will not be to include in a report. For example, if the testing environment involves secret keys, database access information, or other information that would preclude you from including screenshoots to demonstrate your activities (see the reporting activities below), do not select that task or project.
1. Consider that another contrubutor may complete a selected task before you do. Some projects allow you to "claim" issues, but not all.  There is no perfect solution to this; you should consider this risk when selecting tasks.
1. It is certainly easier to present evidence if you succeeded on all fronts, but your contribution does not need to be accepted to receive full credit. Instead, we will be grading you based on the grading rubric, which 
1. You should consider that you may want to carry out actions that the GitHub project itself does not strictly require, but that can be listed in your project report.  For example, if you are worried that your report won't cover enough details to demonstrate your mastery of the material, you might choose to communicate with a project maintainer and ask about non-functional requirements for your patch (e.g., "would this project prefer code that is smaller and easier to read, but slower, like this, or instead prefer code that is more complicated but also more efficient, like that?"). In this example, you have created an opportunity for yourself to describe quality properties and requirements elicitation (e.g., exploring tradeoffs) in your report. The GitHub project may not require any such thing, but you can still choose to do it for HW6 if you are worried about your report and your grade.
1. You almost certainly should read at least two of the example HW6b reports made available at the bottom of this page. Many students find that they have questions along the lines of "exactly how much evidence of XYZ will I need for full credit, and can you promise me that if I do exactly PQR I will get full credit?". Unfortunately, the course staff typically cannot answer such questions directly beyond the rubrics below. However, the example HW6b reports are a great place to get an idea for what is expected.
1. You almost certainly should think about how big the average pull request actually is and what the major themes of this course are regarding reading code vs. writing code. For example, in the Khan and Patel Zulip report, the students report on their pull request #371 for python-zulip-api. You can view that pull request on GitHub and see that it only changed three lines of code in one file. In the maintenance of legacy software, reading the project to determine where to make a change, and in what manner the maintainers will accept it, is often much, much harder than making the change itself (which is often quite small).

Read this entire homework description and pick a project and task(s) that will give you something detailed to talk about in each of the required report sections. See the Golden Rule above. For example, part of the final report is a discussion of how the project members communicate and accept changes. While most projects have informal, rather than formal, processes, a small project with none at all may be difficult to write about. Do not pick that project, and instead pick another project.

Successful completion of this project will make a great talking point on technical interviews, especially with higher-tier companies. Therefore, you may want to select a slightly more ambitious task so that you can "show off" later. Don't think solely in terms of the complexity of the task, as some employers may care more about the size of the code base, the number of active developers, the rigor of the development process, the scope of the testing and QA, the use of analysis tools, the adherence to a required project design or architecture, and so on.

Once you have settled on a project and one or more candidate tasks, research your ideas in more detail. Read the documentation. Build and execute the source code, and try to read and understand it. You should explore the code to the point that you understand how your modification fits in the overall picture. You should be convinced that it is both non-trivial but also doable.

In selecting a task, consider the functional and non-functional implications and requirements, as well as how it fits in to the larger project structure.

See the end of this document for hints on task selection from students in similar classes at other universities. You might also consider a website such as up-for-grabs.net or codetriage.com which list GitHub repositories with beginner-friendly labels (special thanks to J. Kollin, P. Shultz, K. Cheng, and H.-T. Chen for this recommendation).

## Task Planning
You should plan before you start coding. This includes identifying risks and requirements and developing a schedule. If you are working with a partner, you should also solidify a collaboration plan.

## Performing the Task
Implement the selected task. You should write code and perform adequate quality assurance activities. Beyond that, you will likely also need to:

* Take further steps to understand the project's code. You might find it useful to discuss or make use of available diagrams, documentation, and analysis results.
* Submit your changes to the project. Create any necessary documentation to enable acceptance of your code. New contributors rarely have commit privileges to a master repository. Common contribution mechanisms include pull requests, emails to a project lead, or discussion board posts. You may also need to update the bug database.
* Plan and perform an appropriate level of “marketing” for your submission. Avoid stepping on toes and keep your activities appropriate for the project culture. Try to mimic contributors who have previously successfully submitted similar work.
* Solicit feedback and respond to those who take the time to evaluate your work.

You are required to submit your work to the open-source project using your real identity. Remember, it is not required that the project accepts your submission.

Keep track of how you actually spend your time while you are performing the task. The final report requires you to submit a "what actually happened" schedule.



[](https://opensource.guide/how-to-contribute/)
