# Layce Smith
## CSPB 3112 - Project Web Page

### Week 1 - Project Proposal

Summary Forthcoming...

### Week 2 - Setting up the Environment

I am coming into the class a week late, so this week has really been about playing catch up. To that end, I have set up a web page via GitHub and have already started thinking about/setting up an environment for working on my project. I'm really interested in using React to build a task management dashboard. The main challenges will be the fact that I have never used React or Vite or JavaScript or HTML or CSS. SO...everything will be very new and I have a lot of ground to cover very quickly.

Professor Guinn recommended I start by setting up the React/Vite project, creating the GitHub repository for the project, and sketching out what I want the application to look like, which all sounds like a good plan to me. So far, I have been able to install node.js on my computer, which allowed me to install the JavaScript libraries. I have also managed to stand up the basic project in VS code using a Vite template for React. Just getting these initial steps done has already been really gratifying.

### Week 3 - Version Control & Basic UI Design

In order to use GitHub for version control, I had to connect my locally saved project folders to a GitHub repository where I can push new commits. This required me to install Git on my computer and then set up a remote connection with the bash shell. Then, in following my project timeline, I went ahead and drew a wireframe of the application interface that I want to create. What I have is maybe a bit ambitious, and I'm not sure what out-of-the-box components React might offer, so it's possible the design might change.  

<img width="949" height="713" alt="image" src="https://github.com/user-attachments/assets/35418a2a-5b4a-412b-8674-d06ad5436840" />

My next step will be to dig into the React docs to learn more about their UI components and how to get started building out a simple interface.

### Week 4 - Building the Interface

Learning more about the React Components last week helped me better understand why components are so useful for building a task-management dashboard. Building a task dashboard entirely in HTML would require a lot of repetition since many of the dashboard features are things that appear again and again in very similar containers (individual tasks, task status, groups of tasks in lists, etc.). Components are javascript functions that return html code. Because they are functions, they can be reused, and any changes made to the function applies across all uses, which removes the problem of making the same change across large blocks of HTML code. Further, "props" (or properties) are another React feature that pairs with components. Props allow for different values to be passed into different iterations of a component, which is what makes the components reusable. Moving forward this week, I will be working on setting up the various components that I will need for my dashboard.

Another task I had set for myself this week was to practice using HTML and CSS to build out a simple interface. In attempting to do so, however, I realized that the Vite template I already downloaded in React includes HTML and CSS files that generate a dashboard when run. Since I'm not looking to reinvent the wheel and a solid interface file already exists, I will instead focus on adjusting that file to reflect the general layout that I want for my dashboard rather than build a new one entirely from scratch. For now, I have decided to adjust my dashboard design so I can get to work on the components and not spend a lot of time figuring out how to to get my dashboard to look exactly how I was originally picturing. Below are the modifications I will make to the React/Vite template to get my interface in a usable state so that I can start working on the backend a bit. 

## How I plan to reconfigure the Vite/React Interface Template

<img width="928" height="593" alt="Interface Template Changes to be Made" src="https://github.com/user-attachments/assets/8630e034-a30e-4037-b8ba-2eb23572f95e" />


