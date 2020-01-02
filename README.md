# Boon or Bane? Is E-Learning affecting the grades of students?

E-Learning has been very widespread in past century due to the rise of computers. Several benefits
of e-learning includes reduced costs, scalability, consistency and ability to accomodate different time
zones. However, there are skeptics which say that e-learning can be a “bane” as it removes the focus
of the students due to the freedom it gives. In this exercise, we discover knowledge on a dataset where
students use an elearning facility wherein while using the platform, their online footprint is being recorded.
From these, we engineered four features: (1) focus_level - times where they were browsing non-related
sites, (2) time_finished - time it takes to finish the exercise, (3) idle_time - time where they were doing
nothing, and (4) activity_level - number of clicks, keystrokes and mouse wheeling they made. We then
find correlation of these engineered features with grades, using a linear model. It was found that among
all of the features, only the time_finished was the significant variable and the model with only this
variable gives the best prediction. This means that the faster a student finishes the exercise, the higher
the student’s final grade will be. Among all the variables, this is the most unrelated to e-learning. This
also means that a student browsing non-related sites, has lots of idle time and those with little activity
level does not necessarily mean they will get lower grades. As such, while e-learning may remove the
focus of the students as they are free to visit any site during the session, it does not necessarily mean
that e-learning will be a “bane”, as it does not significantly affect the student’s grade.
