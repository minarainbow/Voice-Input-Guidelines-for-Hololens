<p align="left" width="100%">
  <img style="width:30%;align:left" src="img/logo-ait.png">             
</p>

# MSR Voice Input, Group 3
#### Kunaal Sikka, Mina Huh, Vu Nguyen, Nicolas Carmody, Jonas Bokstaller

## Project description and customer needs

Users often have a hard time knowing what voice commands are available and when. There are also issues with receiving feedback from the device on whether a command was heard or interpreted properly. The goal of our project is to develop guidelines for developers to follow so that their Hololens application integrates voice commands effectively and their target audience can use the commands with ease.

Link to [User Personas](https://docs.google.com/document/d/19S1B5Kuxh-lI8tsHfoAEIIXfTWTcwt1xHbvo8nMF6qo/edit?usp=sharing)

Meeting notes available upon request

## Ideas

We started by creating an [affinity cluster](https://drive.google.com/open?id=1M1NF_fIWtZ3Zx_IkFPaNNmv98yLZldGE) and openly sharing our ideas on how to improve the voice recognition experience on Hololens.

After this process, we came up with a rough list of requirements based on our affinity cluster and the user personas:
1. Teaching the user
    1. a tutorial
    3. examples
    4. help menu (easy to access)
2. Commands
    1. fluid understanding
    6. intuitive and recallable
    9. optimize commands that are frequently used
3. Feedback
    1. status - fail/disconnected/confirmation
    11. specific feedback
    12. suggestions
4. UX
    1. same interface for all commands
    18. should not interfere with users field of view too much

Keeping in mind what we had learned in class about User Centered Design, we went out to optimize the Hololens experience so that users could more effectively engage with voice functions. We wanted to create a unified experience that would work across multiple scenarios. Our goal was to increase the utilization of voice commands in such a way that users could complete everday tasks more quickly and with ease. 

An evaluation of the history of introducing new interaction devices (in particular, the mouse and GUI) led us to believe that a great way to get users more comfortable with voice input would be to have them play a game. In addition, we set out to create a way for users to learn the game's commands easily and effectively using a virtual assistant. In this way we would also lessen the learning curve for users unfamiliar with the voice commands available in the game. Thus we came up with the following goals:

1. Portray the system as a digital assistant to make users feel comfortable engaging with it via voice
1. Teach users application specific voice commands with a game
1. Have the users complete a basic task (like send an email) and compare mouse usage with voice usage

View our presentation introducing our ideas to our stakeholders [here](https://drive.google.com/file/d/1ktx7gp4W8LCk07orwoCCEVg4L9FhZpza/view?usp=sharing).

    
## Evaluation

In our user study, we want to find out how effective our solutions are. Specifically, we have the following research questions :
Q1: What is the effect of using documentation vs being guided by a Digital Assistant on the percentage of voice commands?
Q2: What is the effect of using documentation vs being guided by a Digital Assistant on task completion?


To simulate the HoloLens environment, we use a classroom. All the HoloLens overlay (simulated with Windows) is projected to parts of the room (i.e. the wall). The participant can move freely within the room. The computer is operated by a person that watches the hand clicks of the participant (simulated with a laser pointer) and listens to the voice commands. The operator ignores invalid inputs. Another person simulates the digital assistant, which is activated by the participant with eye-contact or by the keyword “Hey Cortana”.
<p align="center" width="10%">
  <img width="500px" src="img/experiment.png">  
  <br>Hololens Overlay Simulation
</p>

In task 1, the participant plays a simple game with voice commands only. Here, we measure the performance of the participant (Number of invalid commands, number of referrals to the documentation, time to complete). 
<p align="center" width="100%">
  <img width="420" src="img/task1.png">  
  <br>Game Task
</p>

In task 2, the participant is tasked to send an email using the Windows Mail app. The participant may use voice commands or hand input. Here, we measure the performance (as in task 1), plus the number of gaze/hand inputs versus voice. 
<p align="center" width="100%">
  <img width="500px" src="img/task2.png">  
  <br>E-mail Task
</p>

After the completion of both tasks, the participant fills in a questionnaire that records demographic information, and both graded and textual feedback on the various input and teaching methods.

#### Deliverables:

[Study Report](/Deliverables/Study_Report.pdf)

[User Study Presentation](/Deliverables/User_Study_presentation.pdf)

[Post-Experiment Questionnaire](https://docs.google.com/forms/d/11-0nStA7Ju8s_jPijFY3YNpyKCFENe0J3qi75lEZhOU/edit)

Describe your approach for evaluating your low-fi prototypes, present your results and your conclusion. 

Upload the document shared with the stakeholder to the "deliverables" folder and include the link here.

Optional: in this part you can also document the prototyping process: show different iterations, as well as failed ideas (Weeks 6-10)

#### Stakeholder Feedback:
On Wednesday, November 27th we had the chance to discuss the study and main findings with Sophie from Microsoft. We hat a talk and how the prototype and the corresponding experiment should be altered based on our results. To further improve our study and the report we have to do the following things:
- Add a more detailed description in the study report that first-time readers get an intuition on how the experiment was done.
- Implement some video snippets from the experiment.
- To improve the experiment we have to get a better balance between the length of the documentation vs. the fairy because the instruction of the fairy takes longer than reading the documentation.
- Add more variety of speech samples.
- State the conditions more clearly on what circumstances the experiments were done.


## Final solution
Presentation video: https://drive.google.com/file/d/1ChjRcP7B5skvvyCZyMsQ34FjSbp3X6NY/view?usp=sharing

(Weeks 10-14)
