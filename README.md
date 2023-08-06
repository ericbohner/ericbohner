# Eric Bohner, PhD

I'm a Data Scientist with a background in Analytic Philosophy.  I love diving in to big problems to understand their small parts.

## What I Do
I feel obligated to lean into the cliché about philosophers: I think (deeply?) about things.

That's probably true, but only in the sense that I care about understanding a thing's component parts so that I can construct structured, comprehensible solutions to a problem.  But in that sense I don't think I'm very different from any number of other professionals in different fields.  I just happen to have formalized training in it.  When I'm working on projects in Data Science or developing software, for instance, that's what I'm doing.  Instead of writing out my solutions in a structured essay, I just write them in Python, or SQL.  I don't think there's any real difference in the structure of my thought process when I'm working on one or the other.

Here's a really simple example:

    def fizzbuzz(n):
      for i in range(1, n + 1):
          if i % 15 == 0:
              print("FizzBuzz")
          elif i % 3 == 0:
              print("Fizz")
          elif i % 5 == 0:
              print("Buzz")
          else:
              print(i)

    n = 15
    fizzbuzz(n)

This can be formalized in first order logic:

    ∀x (x ≤ n → (F(x) ∧ B(x) → FB(x)) ∧ (F(x) ∧ ¬B(x) → Fizz) ∧ (¬F(x) ∧ B(x) → Buzz) ∧ (¬F(x) ∧ ¬B(x) → x))

My formal training is in the latter, but they run on the same principles.  You can see me dip my toes into the former in <a href='https://github.com/ericbohner/Capstone'>some of my projects.</a>


## Skills

[![My Skills](https://skillicons.dev/icons?i=py,pytorch,r,mysql,postgres,latex,git,flask,bash,aws)](https://skillicons.dev)

### A breakdown:
- Databases: MySQL
- Programming: Python, R
- Statistics: Hypothesis Testing, A/B Testing
- Data Visualization: Matplotlib, Seaborn, Plotly, Tableau, Excel
- Cloud: AWS, Hadoop, Spark
- UI: Kivy, KivyMD

## Education

<b>Data Science Diploma<b> BrainStation, 2023

<b>PhD, Analytic Philosophy</b>
University of Calgary,
2023

<b>MA, Philosophy<b>
University of Waterloo,
2017
