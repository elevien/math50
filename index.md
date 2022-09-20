---
home: yes
layout: default
logo: logo.svg

---

## About the course


 **Instructor**: <a href = "https://elevien.github.io/"> Ethan Levien</a>.

**Meeting time**: T/TH @ 10-12

**Office Hours**: T @ 1

 **Prerequisites**: Technically math 10; however, there are many other paths to prepare you for this course. The import thing is that you have some exposure to probability theory and are comfortable coding.

 **Course objectives**: You will learn how to build, fit and make predictions with regression models. Such models form the basis of many widely used data analysis techniques, including most machine learning algorithms. This is an applied course, and we won't spend much time deriving equations or proving theorems. Instead, we will learn by playing around with real and simulated data. We will challenge the underlying assumptions of a method and see when things "break". The goal is to help you develop an intuition about statistical inference, which can be generalized to real world settings where theorems and analytical formulas are not applicable.

 **Coding**: All coding for the course will be done in Python. Some advantages of python (over R) are that: (1) We can *easily* run everything directly in the browser using google <a href ="colab.research.google.com"> colab notebooks</a>, so there is no need to download anything on your machine. (2) Python is widely used in data science and machine learning, both in academia and in industry. (3) While some very basic things are more difficult to implement, I think you'll find it's easier to generalize to more advanced methods. (4) I know python and I've basically never coded in R.


## Course policies

**Attendence**: The course meets twice a week and attendance is mandatory.

**Grading**:
 Your grade will be based on the following assignments:
  <ul>
    <li> Exercises (60%) - see links in schedule.   </li>
    <li> Attendence (10%)   </li>
 <li> Project (30%)  - see <a href = "./project.html" > project guidelines</a>  </li>
     <ul>
      <li> project proposal (5%) </li>
      <li> final writeup (25%) </li>
    </ul>
  </ul>
  Grades will be based on a combination of self-evaluation and my own assessment (more on this in class).


**Exercises**:  Your "homework" is to submit solutions to a set of exercises. I say "homework" because I plan to incorperate problem solving sessions into the lectures, giving you more time to discuss problems with myself and your peers.
You will submit you solutions to gradescope (approximately) every week before I release the solutions. Then, the following week you will self-evaluate (i.e. grade) you solutions and submit the evaluation. You should use the following point scale, which I will elaborate on in class:
<ul>
<li> 0 - no work was done, or barely any effort was made. </li>
<li> 1 - You put down partial work, but didn't put much effort in and didn't reach out if you needed help.   </li>
<li> 2 - You put in effort, but didn't get the problem exactly correct. You reached out at least once if you needed help.      </li>
<li> 3 - You got the problem correct, or made a very significant effort, including attending office hours and asking questions on slack if needed. </li>
</ul>

The # of points you get for each self-evaluations are simply the score you've given yourself plus an additional point for providing an explanation of what you did wrong. The graders will simply review your self-evaluations.



## Resources

**Textbooks**: The course will be self-contained in the python notebooks and class notes. However, I will occasionally reference the following textbooks for additional readings (note that the first two texts use R rather than python, so the coding components can be skipped):
*  <a href ="https://avehtari.github.io/ROS-Examples/"> Regression and other stories</a>. The course is very roughly based on this text, which provides a non-technical introduction to regression analysis with many worked examples.
* <a href ="https://www.eugened.org/"> Advanced Statistics with Applications in R</a>. A more technical introduction to applied regression. I will refer to this text for some of the proofs and derivations.
* <a hred = "https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/#contents"> Probabilistic Programming and Bayesian Methods for Hackers </a> I will reference this text when we cover probabilistic programming in pymc3. The pymc3 documentation itself is a bit dense.

**Software**: All coding will be done using python in <a href ="colab.research.google.com"> colab notebooks</a>.  Within python there are a number of packages we will use throughout the course, including:
 * <a href ="https://numpy.org/"> numpy </a> for working with arrays, linear algebra and generating random numbers.
 * <a href ="https://pandas.pydata.org/"> pandas </a> for working with tabular data sets
 * <a href ="https://www.statsmodels.org/stable/index.html"> statsmodels </a> for classical statistics
 * <a href ="https://docs.pymc.io/"> pymc3 </a> for Bayesian statistics

You do not need to be an expert in any of these packages and I will provide you with skeleton code for most tasks. That said, I expect you to have some basic proficiency debugging, which will occasionally involve referencing the documentation for these packages.



## Schedule

<table>

  <tr>
    <th>Week</th>
    <th>Topics</th>
    <th>Reading</th>
    <th>Assignments</th>
  </tr>



  <tr>
      <td VALIGN=TOP>1</td>

      <td>
      <ul>
      <li> Course policies </li>
      <li> Introduction python (during xhours)</li>
      <li> Probability and random variables, CLT </li>
      <li> Using simulation to explore probability models </li>
      </ul>
      </td>

      <td VALIGN=TOP>
      <ul>
      <li> <a href = "./notes/probability_background.pdf"> Models and simulation </a> </li>
      <li> <a href = "https://colab.research.google.com/drive/1Gs-gSsUP1hHVwhrbwvWzLVm1ulcLJKRI?usp=sharing"> Python Notebook </a> </li>
      </ul>
      </td>

      <td VALIGN=TOP>
      <ul>
      <li> <a href = "https://aaltoscicomp.github.io/python-for-scicomp/numpy/">  Python for Scientific Computing </a> (not graded) </li>
      </ul>
      </td>
  </tr>

  <tr>
    <td VALIGN=TOP>2</td>
    <td>
    <ul>
    <li> Background on statistical modeling and inference</li>
    <li> Hypothesis testing</li>
    <li> Linear regression with a single predictor</li>
     </ul>
    </td>

    <td VALIGN=TOP>
    <ul>
    <li> <a href = "./notes/probability_models.pdf"> Important probability models </a> </li> 
    </ul>
    </td>

    <td VALIGN=TOP>
    <ul>
    <li> Exercise Set 1</li>
    </ul>
    </td>
  </tr>



 <tr>
      <td VALIGN=TOP>3</td>

      <td>
      <ul>
      <li> Introduction to Bayesian statistics</li>
      <li> Probabilistic computation in python with pymc3 </li>
      <li> Bayesian inference for some probability distributions </li>
      <li> Where do priors come from?</li>
       </ul>
       </td>

       <td VALIGN=TOP>
       <ul>
       <li> <a href = ""> Notes </a>  </li>
       </ul>
       </td>

       <td VALIGN=TOP>
       <ul>
       <li> Exercise Set 1 Self-evaluation</li>
       <li> Exercise Set 2  </li>
       </ul>
       </td>
  </tr>


  <tr>
    <td VALIGN=TOP>4</td>
    <td>
    <ul>
    <li> Bayesian inference for regression models with a single predictor  </li>
    <li> Relationship between Bayesian linear regression and least squares </li>
    <li> p-values revisted </li></ul>
    </td>

    <td VALIGN=TOP>
    <ul>
  <li> <a href = ""> Notes </a>  </li>
    </ul>
    </td>

    <td VALIGN=TOP>
    <ul>
    <li> Exercise Set 2 Self-evaluation</li>
    <li> Exercise Set 3  </li>
    </ul>
    </td>
  </tr>



  <tr>
    <td VALIGN=TOP>5</td>

    <td>
    <ul>
    <li> Regression with multiple predictors </li>
    <li> Interpreting regression coefficients </li>
    <li> Working with categorical data  </li>
    <li> Analysis of variance </li>
     </ul>
    </td>


    <td VALIGN=TOP>
    <ul>
  <li> <a href = ""> Notes </a>  </li>
    </ul>
    </td>

    <td>
    <ul>
      <li>  Exercise Set 3 Self-evaluation </li>
      <li>  Project proposal due </li>
    </ul>
    </td>
  </tr>


<tr>
  <td VALIGN=TOP>6</td>

  <td><ul>
  <li> Deep dive into regression modeling assumptions  </li>
  <li> What happens when regression modeling assumptions fail?   </li>
  <li> Model diagnostics and model selection </li>
  </ul>
  </td>


  <td VALIGN=TOP>
  <ul>
<li> <a href = ""> Notes </a>  </li>
  </ul>
  </td>

      <td VALIGN=TOP>
      <ul>
      <li> Exercise Set 4  </li>
      </ul>
      </td>
</tr>

<tr>
  <td VALIGN=TOP>7</td>

  <td><ul>
  <li> Performing regression on transformed variables </li>
  <li> Model building strategies </li>
  <li> Overfitting </li>
  <li> Experimental design </li>
  </ul></td>


  <td VALIGN=TOP>
  <ul>
<li> <a href = ""> Notes </a>  </li>
  </ul>
  </td>

  <td VALIGN=TOP>
  <ul>
  <li> Exercise Set 4 Self-evaluation  </li>
  <li> Exercise Set 5  </li>
  </ul>
  </td>

</tr>

<tr>
  <td VALIGN=TOP>8</td>

  <td><ul>
  <li> Logistic regression </li>
  <li> Causal inference  </li>
  <li> </li>
  </ul></td>

  <td VALIGN=TOP>
  <ul>
<li> <a href = ""> Notes </a>  </li>
  </ul>
  </td>

  <td VALIGN=TOP>
  <ul>
  <li> Final project report (due during finals week) </li>
    <li> Exercise Set 5 Self-evaluation </li>
  </ul>
  </td>
  </tr>


</table>



## Accessibility Needs
<p> Students with disabilities who may need disability-related academic adjustments and services for this course are encouraged to see me privately as early in the term as possible. Students requiring disability- related academic adjustments and services must consult the Student Accessibility Services office (Carson Hall, Suite 125, 646-9900). Once SAS has authorized services, students must show the originally signed SAS Services and Consent Form and/or a letter on SAS letterhead to me. As a first step, if students have questions about whether they qualify to receive academic adjustments and services, they should contact the SAS office. All inquiries and discussions will remain confidential.  </p>
