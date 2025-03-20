Title: PathWise

Function: Personalized learning path generator

Aim: In the age of internet, everything can be self taught. There are thousands of resources to study a specific skill set. Choosing a perfect one is an overwhelming and time consuming task which in turn leads to the complete abolishment of the desire to learn that skill. Pathwise is build to prevent this.

INPUTS:
- The skill that user needs to learn.
- User's current knowledge in that skill.
- Total duration (In what time the user needs to complete learning the entire skill)
- Daily commitment (How many hours the user can dedicate)
- Learning mode (what type of learning does the user prefer like video, blogs, books, course providing websites etc.)

PROCESS & OUTPUT:
 Step 1.The Application(M.L) analyzes the inputs given by user.
      2.Splits the user inputted 'Total duration' into days or weeks.
      3.Displays what topics the user needs to study in each day or week.
      4.Provide link to the best resource on the internet to study that specific skill, beneath respective day or week.
      5.User can click on the link and starts learning it directly without the need of any overwhelming research for the best resource
      6.The app tracks user's progress in the form of progress bars/graphs.
      7.To gamify learning process, user unlocks achievement or badges when he completes certain days/weeks.
      8.The app sends notification to user when the user is not being consistent in his learning journey.
      9.The app contains a forum where fellow learners can interact and make connections.


- - - - - - - - - INTRODUCTION - - - - - - - - - 
- PathWise is a *personalised learning path* generator.
- It generates a *custom-designed learning schedule* based on the user's input.
- Additionally, it *provides direct links* to the best learning resource.
- It is *aims to avoid the overwhelming scenario of finding the right resource* from the internet to learn a skill.
- PathWise is a middleman that *connects users to the best learning resources* they require.



- - - - - - - - - ABSTRACT - - - - - - - - -
- PathWise is a learning path generator that simplifies skill learning.
- It creates a personalised study plan based on skill, knowledge level, duration, daily commitment, and learning mode.
- Automatically finds & recommends top resources (videos, blogs, books, courses).
- Tracks progress with graphs & motivates users through badges & achievements.
- Community forum enables discussions and peer learning.
- Smart reminders & notifications keep users consistent and on track.


- - - - - - - - - EXISTING SYSTEM - - - - - - - - -
1. Online Learning Platforms (Example: Udemy, Coursera etc.)
   - Provides a large number of courses.
   Disadvantage: We may need to spend too much time on searching right courses.

2. Learning Recommendation System (Example: LinkedIn Learning)
   - Recommends courses based on past learning behaviour.
   Disadvantage: We may need to manually select right course.

3. Gamified Learning Apps (Example: Brilliant, Khan Academy)
   - Interactive, task based learning.
   Disadvantage: Have their own schedule.

4. Adaptive Learning Path Generators (using RLLP model)
   - Pretty similar to PathWise. It collects preferences from users to generate schedule.
   Disadvantage: Lacks community forums, Gamified Tasks.  


- - - - - - - - - PROPOSED SYSTEM - - - - - - - - - 
1. Receives detailed inputs from users (Total duration, daily commitment, basic knowledge, mode of study etc.)
2. Generates personalized schedules as per days or weeks basis.
3. Provides links to best resource available respective to each topic to be learned.
4. Tracks user's progress - in the form of graphs and progress bars.
5. Gamifying learning - User unlocks achievements on completing each day or week, resulting in more interactive learning.
6. Forums to interact with other learners.
7. Motivating notifications if users are not consistently learning.
8. User can give feedback to the admin.


- - - - - - - - - SYSTEM REQUIREMENTS - - - - - - - - - 
Hardware Requirements:-
Processor: i5 or above
RAM: 8GB(Minimum)
Storage: 512GB(Minimum)
Stable Internet connection

Software Requirements:-
OS : Windows 8 or above / Linux
IDE: VS Code
FrontEnd: ?
BackEnd : ?
Database: ?
Version Control: Git, GitHub


- - - - - - - - - MODULE DESCRIPTION - - - - - - - - - 
Admin:-
1. Make sure ML models generate accurate learning plans.
2. Moderate forum - Prevent Spam, Resolve Disputes, Establish productive communication. 
3. Manage notifications.
4. Ensure the smooth running of the platform.

User:-
1. Resister or Login
2. Input learning preferences
3. Track learning progress
4. Earn achievements
5. Receive Reminders
6. Chat in forum
7. Change learning plan by adjusting prompt


- - - - - - - - - FUTURE ENHANCEMENTS  - - - - - - - - - 
1. AI-powered content summarization.
2. More interactive learning modes (quizzes, live discussions).
3. Improved ML models for better path recommendations.
4. Individual users should be able to send friend requests and chat with other learners personally.
5. 1 day ban system if a user do offensive chat in group.


- - - - - - - - - REFERENCE PAPERS - - - - - - - - - 
1. Paper Name: Intelligent Learning Path Recommendation System Based on Reinforcement Learning (IEEE)
   Authors   : Han Wan, Baoliang Che
   Feature   : This project introduces the *RLLP* (Reinforcement Learning Language Path) model, which recommends efficient and sensible learning paths by considering learners' goals
   Difference: lacks direct integration, potentially requiring learners to seek out materials independently

2. Paper Name: A Personalized E-learning Recommendation System Using Machine Learning
   Authors   : Ravishangar Aarya
   Feature   : This research presents a multi-agent system that classifies students to recommend courses tailored to their knowledge levels and learning styles, aiming to enhance the personalization of e-learning experiences.
   Difference: Does not account for individual scheduling preferences, only contains generic schedules.

3. Paper Name:Adaptive Learning Path Generation for Online Education Platforms
   Authors   : Eleni Ilkou, Hasan Abu-Rasheed
   Feature   : proposes an algorithm that generates personalized learning paths by analyzing students' historical learning behaviors and performance data
   Difference: No community interaction features.












