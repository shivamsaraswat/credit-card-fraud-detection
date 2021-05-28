# Online Transaction Fraud Detection using Backlogging on E-Commerce Website
 
* This is a Mini Project I got in my 6th Semester of Engineering. I did this as a group project with my 3 friends. We made this project using [Django](https://www.djangoproject.com/) framework of Python. 
* In this, we implemented Fraud Detection System (FDS) using Behavior and Location Analysis (BLA) to detect a payment fraud. FDS verifies whether the transaction is genuine or not. User spending patterns and geographical location is used to verify the identity. If any unusual pattern is detected, payment is declined.
* For location analysis, we utilised [ipinfo.io](https://ipinfo.io/). To obtain the location, we must utilise the ipinfo.io access token. 

### How to Use?
    git clone https://github.com/shivamsaraswat/credit-card-fraud-detection.git
    cd credit-card-fraud-detection.git
    pip install virtualenv
    virtualenv env
    .\env\Scripts\activate
    pip install -r .\requirements.txt
    After working
    deactivate
