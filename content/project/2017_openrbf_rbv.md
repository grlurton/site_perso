+++
title = "Targetting data verification in Results Based Funding programs"
date = 2017-07-29T01:45:39-08:00
draft = false

tags = ["results based funding","machine learning","consultancy","tools","methods","primary health care"]

# Project summary to display on homepage.
summary = "An algorithmic framework to orient data verification in Results Based Funding programs"

# Optional image to display on homepage.
image_preview = "rbf_verification.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "rbf_verification.png"
caption = "Verification trails are simulated for each facility"

+++
OpenRBF is a solution used in many countries to track results and payments in Results Based Funding programs in developing countries. In most programs using OpenRBF, facilities submit monthly reports to the financing entity. These reports are then verified by on site supervisions, and payments are made on the verified data. This full verification ensures the accuracy of the payments made, but is costly to implement. This project aimed at defining and testing algorithms to orient program managers willing to only verify subsets of the data reported each month.

I developped a generic framework to define and test algorithms to orient the on-site validation of reports from health facilities. I then implemented this framework in a Python module that allows an easy implementation of the algorithms and allows easy simulations to test and validate the algorithms. I implemented an algorithm empirically developed by Mathieu Anthony from AEDES, and compared it to two simple alternatives. Finally, I offered an applied decision framework for decision makers to help chosing the preferred trade-off between operational costs and overpayment.

# More Details

* [Synthesis of the methods and results](https://grlurton.github.io/orbf_data_validation/Analysis.html)
* [Technical documentation for algorithm implementation and testing module](https://grlurton.github.io/orbf_data_validation/html/index.html)
