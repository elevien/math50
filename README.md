# Math 50 (Linear Models)

## About the course


 **Instructor**: <a href = "www.github.io/elevien"> Ethan Levien</a>. I'm an assistent professor in the Mathematics department here at Dartmouth. My background is in stochastic processes and mathematical modeling, and I'm especially interested in applications to single-cell physiology and evolution. 
 
 **Meeting time**: TBD
 
 **Prerequisites**: Technically math 10; however, there are many other paths to prepare you for this course. The import thing is that you have some exposure to probability theory and experience programming. 

 **Course objectives**: You will learn how to implement, fit and interpret linear regression models. Such models form the basis of almost all widely used data analysis techniques, including machine learning algorithms. This a very applied course, and we won't spend much time deriving equations or proving theorems about various inference techniques. Instead, we will learn by playing around with real and simulated data. We will challange the underlying assumptions of a method and see when thing "break". My goal is to help you develop an intuition about statistical inference, which can be generalized to real world settings where theorems and analytical formulas fail.
 
 **Coding**: All coding for the course will be done in Python. Some advantages of python (over R) are that: (1) We can *easily* run everything directly in colab, so there is no need to download anything on your machine. (2) To my knowledge Python is more widely used in data science and machine learning, both in academia and in industry. (3) While some very basic things are more difficult to implement, I think you'll find it's easier to generalize to more advanced methods. (4) I think R sucks and is a terrible programming language. (5) I know python and I've basically never coded in R.


## Course policies

**Attendence**: The course meets twice a week and attendence is mandatory. I plan to devote a signficant amount of class time to open-ended discussions and group work, so their really isn't any point in taking the course if you don't plan to consistently attend lectures.

**Grading**:
 Your grade will be based on the following assigments:
  <ul>
    <li> python notebooks (50%) - see links in schedule  </li>
 <li> project (50%)  - see <a href = "project" > project guidelines</a>  </li>
     <ul>
      <li> project proposal (20%) </li>
      <li> final writeup (30%) </li>
    </ul>
  </ul>
  Grades will be based on a combination of self-evaluation and my own assesment (more in this in class). 
  </p>




## Resources

**Textbooks**: <a href ="https://avehtari.github.io/ROS-Examples/"> Regression and other stories </a>. Copies are on reserve at the Library and in the math department. I've found that this is one of the best texts on applied regression at this level, but unforunately they do everything in R. I enourage you to skim over the bits with code and think about how you might accomplish the same task in python. 

**Software**: All coding will be done using python in <a href ="colab.research.google.com"> colab notebooks</a>.  Within python there are a number of packges we will use throughout the course, including:
 * <a href ="https://numpy.org/"> numpy </a> for working with arrays, linear algebra and generating random numbers. 
 * <a href ="https://pandas.pydata.org/"> pandas </a> for working with tabular data sets
 * <a href ="https://www.statsmodels.org/stable/index.html"> statsmodels </a> for classical statistics
 * <a href ="https://docs.pymc.io/"> pymc3 </a> for Bayesian statistics
 
You do not need to be an expert in any of these packages and I will provide you with skeleton code for most tasks. That said, I expect you to have some basic proficiency debugging, which will occasionally involve referencing the documentation for these packages. 



## Schedule

<table>

  <tr>
    <th>Week   </th>
    <th>Topics</th>
    <th>Notebook</th>
  </tr>

 
  <tr>
      <td>09/13</td>
      <td>introduction python, linear regression with a single predictor</td>
      <td> <a href = "https://colab.research.google.com/drive/1yPxFVsCmu-KhGC8TFUa3q8JdtTZYnay0"> getting started with python </a> (not graded), <a href = "https://colab.research.google.com/drive/1rG-iJ-IBUWti5CuKuVzjkYAsLjeHhydz?usp=sharing">hello linear regression </a></td>
  </tr>

 <tr>
      <td>09/20</td>
      <td>Intro to Bayes, Bayesian linear regression </td>
      <td><a href = "https://colab.research.google.com/drive/1rG-iJ-IBUWti5CuKuVzjkYAsLjeHhydz?usp=sharing">hello bayes </a></td>
  </tr>

<tr>
  <td>10/04</td>
  <td>Regression with multiple predictors, regression modeling assumptions </td>
  <td><a href = "https://colab.research.google.com/drive/1rG-iJ-IBUWti5CuKuVzjkYAsLjeHhydz?usp=sharing">hello bayes </a>
   <a href = ""> modeling assumptions </a>
  </td>
</tr>

<tr>
  <td>10/11</td>
  <td>Diagnostics for regression models, robust regression</td>
  <td><a href = ""> diagnostics </a></td>
</tr>


<tr>
  <td>10/18</td>
  <td>Transformations </td>
  <td><a href = ""> transformations </a></td>
</tr>

<tr>
  <td>10/25</td>
  <td>Logistic regression and GLM</td>
  <td><a href = ""> logistic regression </a></td>
</tr>

<tr>
  <td>11/01</td>
  <td>Experimental design</td>
  <td><a href = ""> design </a></td>
</tr>

<tr>
  <td>11/08</td>
  <td>Selected topics</td>
  <td><a href = ""> TBD </a></td>
</tr>


</table>



## Accessibility Needs
<p> Students with disabilities who may need disability-related academic adjustments and services for this course are encouraged to see me privately as early in the term as possible. Students requiring disability- related academic adjustments and services must consult the Student Accessibility Services office (Carson Hall, Suite 125, 646-9900). Once SAS has authorized services, students must show the originally signed SAS Services and Consent Form and/or a letter on SAS letterhead to me. As a first step, if students have questions about whether they qualify to receive academic adjustments and services, they should contact the SAS office. All inquiries and discussions will remain confidential.  </p>
