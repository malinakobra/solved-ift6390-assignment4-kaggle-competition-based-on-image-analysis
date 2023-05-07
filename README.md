Download Link: https://assignmentchef.com/product/solved-ift6390-assignment4-kaggle-competition-based-on-image-analysis
<br>
For this project, you will take part in a Kaggle competition based on image analysis. The goal is to design a machine learning algorithm that can automatically identify hand drawn images as well as reason about their appearance. The dataset we have prepared is a variant of google’s quick draw dataset. For that dataset, a popular goal has been to simply identify the given human drawn images. For our variant, we’ve reduced the number of classes to 31. To create an image, we’ve appended the drawing to a random location on a larger 100×100 pixel blank canvas image. Additionally, we’ve added randomly generated noise around the drawing. Note that one of the classes is called ”empty” and consists of only noise and no human drawings. The dataset consists of 10k images of size (100,100) for the training set and 10k for test set. You will be evaluated on test accuracy. Examples of the training samples are shown here:

The competition, including the data, is available here: <a href="https://www.kaggle.com/c/ift3395-6390-f2018">https://www.kaggle.com/c/ </a><a href="https://www.kaggle.com/c/ift3395-6390-f2018">ift3395-6390-f2018</a> We expect you to be working in groups of 3 or 4.

<h1>1             Kaggle Team formation</h1>

Each team should consist of 3 or 4 members. To form a team:

<ul>

 <li>Fill out the google form <a href="https://goo.gl/forms/nyxLpgsBOujurs0Y2">https://goo.gl/forms/nyxLpgsBOujurs0Y2</a> with your team information by 14th at 5:00 pm. Any teams not registered or registered late will not be graded.</li>

 <li>Register as an individual Kaggle user</li>

 <li>To enter the competition you need to follow this link: <a href="https://www.kaggle.com/t/80bab1e54d594dee9c44dbefdd907bf5">https://www.kaggle.com/t/80bab1e54d594dee9c44dbefdd907bf5</a></li>

 <li>Enter the competition and accept terms and conditions.</li>

 <li>Go to <a href="https://www.kaggle.com/c/ift3395-6390-f2018">https://www.kaggle.com/c/ift3395-6390-f2018</a></li>

 <li>In the ”Invite Others” section, enter your teammates’ names, or team name.</li>

 <li>Your teammate has the option to accept your merge. The person accepting a merge is the team leader.</li>

</ul>

<strong>**** IMPORTANT NOTE **** </strong>The maximum amount of submissions is 2 per day, per TEAM. Any team whose individual members have a submission count larger than what is allowed up to-date will be UNABLE to form a team. Example: Today is the first day of competition. A,B,C are three teammates who haven’t formed a team yet. A submitted 0 times. B submitted 2 times. C submitted 1 times. Because the maximum amount of submissions is 2 per team per day, the total possible submissions for a team is 2. However, the cumulative submission count for A,B,C is 3. Therefore, they will be unable to form a team (They will need to wait for tomorrow, and not submit any submissions for the next day).

Any members at the end of competition that are not in a team will not receive any marks.

We suggest forming your teams BEFORE attempting any solutions.

<h1>2             Instructions</h1>

To participate in the competition, you must provide a list of predicted outputs for the instances on the Kaggle website. To solve the problem, we expect you to try the following methods:

<ul>

 <li>A baseline linear learner consisting of SVM or logistic regression, implemented by hand or using a library.</li>

 <li>Any other ML method of your choice. Be creative! Some suggestions are k-NN, random forests, kernelized SVM, CNNs, etc. or even combinations of these!</li>

</ul>

For the Kaggle competition, you can submit results from you best performing system, whichever method (from the above three categories) it may fall under. You are not allowed to use any supplementary data to enrich the training set. Note that there is a maximum of 2 prediction submissions per day on Kaggle. You can submit 2 predictions per day over the course of the competition, so we suggest you start early, allowing yourself enough time to submit multiple times and get a sense of how well you are doing.

<h1>3             Report</h1>

In addition to your methods, you must write up a report that briefly describes the preprocessing, validation, algorithmic, and optimization techniques, as well as providing results that compare them. The report should contain the following sections and elements:

<ul>

 <li>Project title</li>

 <li>Team name on Kaggle, as well as the list of team members, including their full name and student number.</li>

 <li>Introduction: very briefly describe the problem and summarize your approach and results.</li>

 <li>Feature Design: Describe and justify any pre-processing methods, or how you designed and selected your features.</li>

 <li>Algorithms: Give an overview of the learning algorithms used without going into too much detail.</li>

 <li>Methodology: Include any decisions about training/validation split, distribution choice for naive bayes, regularization strategy, any optimization tricks, setting hyper-parameters, etc.</li>

 <li>Results: Present your results, with emphasis on i) one simple baseline and ii) on the method that gave you the best performance. You do not need to show the results from all methods that you tried.</li>

 <li>Discussion: Discuss why your best method performs better than the simple baseline. Which design choices where the most impactful on performance?</li>

 <li>Statement of Contributions. Briefly describe the contributions of each team member towards each of the components of the project (e.g. defining the problem, developing the methodology, coding the solution, performing the data analysis, writing the report, etc.) At the end of the Statement of Contributions, add the following statement: We hereby state that all the work presented in this report is that of the authors.</li>

 <li>References (optional).</li>

 <li>Appendix (optional). Here you can include additional results, more detail of the methods, etc.</li>

</ul>

You do not need to give general descriptions of ML components or too much detail. You are expected to explain the issues that were relevant to your work. In each section we are expecting just a handful of sentences explaining your choices to address those issues. The main body (without references or appendix) of the report should not exceed 4 pages.