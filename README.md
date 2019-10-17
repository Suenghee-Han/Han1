
Warmup Assignment
In this exercise you will just submit a ping to the grader in order to make sure the exercice and grading environment is setup correctly.

We have to install a little library in order to submit to coursera

In [ ]:
!rm -f rklib.py
!wget https://raw.githubusercontent.com/IBM/coursera/master/rklib.py
Please provide your email address and obtain a submission token on the grader’s submission page in coursera, then execute the cell

In [ ]:
from rklib import submit
import json

key = "tlOUM_XREeerCBIEgYad1g"
part = "HA0XG"
email = ###_YOUR_CODE_GOES_HERE_###
token = ###_YOUR_CODE_GOES_HERE_### #you can obtain it from the grader page on Coursera


submit(email, token, key, part, [part], json.dumps(23))
