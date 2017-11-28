---
layout: post
title: Agent-Based Financial Economics
permalink: /course/
---

<b>About</b>

<p><img src="/assets/images/uzh.jpg" alt="" class="image left"><a href="https://studentservices.uzh.ch/uzh/anonym/vvz/index.html#/modules/list/2017/003/50773378-50772427/details/SM/50857786">Agent-based financial economics</a> is an interdisciplinary master-level course for economists and computer scientists offered by the department of Banking & Finance of University of Zurich. It is worth 3.0 ECTS credits and counts as BF4, ECON2, or more generally as OEC/WWF course for University of Zurich students, and as elective course for computer scientists from ETH.</p>

<p>Agent-based financial economics is a controversial but also promising modeling methodology that thrives best when combining economics knowledge with sound software engineering. Step by step, we create a large-scale economic simulation by introducing new and increasingly sophisticated agents (consumers, firms, funds, etc.), comparing the simulated outcomes with the equilibria known from classic economic theory. These agents are implemented by interdisciplinary teams with students from economics, finance, and computer science. The fitness of the economic agents is tested in a competitive setting. Due to the complexity of the simulation, agents will likely have to resort to behavioral heuristics. The interesting question is: will the invisible hand succeed in guiding them towards the efficient outcome anyway?</p>

<p>As a computer science student, you will get to learn the basic mechanisms of our economy and the financial markets, while applying your software engineering skills. As a economics or finance student, you will get a new, constructive perspective on economics and learn how to structure large-scale simulations in object-oriented programming.</p>

<b>Lesson 1: The Hermit</b>

<p>Here are the <a href="/assets/abfe-lesson1.pdf">slides of the first lesson</a>. Please follow <a href="/course/setup">these instruction</a> on how to install the required software on you computer in order to solve <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise01-task.md">the first exercise</a>.</p>

<b>Lesson 2: The Farmer</b>

<p>Here are the <a href="/assets/abfe-lesson2.pdf">slides of the second lesson</a>, as well as <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise02-task.md">exercise 2</a>. This time, we will try to find out whether the agents can do better by teaming up and coordinating their efforts through an open market.</p>

<b>Lesson 3: Money</b>

<p>Here are the <a href="/assets/abfe-lesson3.pdf">slides of the third lesson</a>, as well as <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise03-task.md">exercise 3</a>. This time, we will experiment with money supply and see what effect printing and distributing money has on the simulation.</p>

<b>Lesson 4: Growth</b>

<p>In lesson 4, the model will be extended to growth by introducing births and a maximum age. Besides the <a href="/assets/abfe-lesson4.pdf">standard slides</a>, we will discuss <a href="/assets/abfe-lesson4-agile.pdf">the role of agile software development</a> in agent-based modelling. Exercise 4 can be found <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise04-task.md">here</a>.</p>

<b>Lesson 5: Stocks</b>

<p>To depart from the feudalistic world of the previous exercise, we introduce a stock market, allowing everyone to become a capitalist, resulting in a much more equal distribution of wealth and to invest retirement savings actively. To have a functioning stock market, a new firm type market maker is introduced, which acts as a counterparty when consumers buy or sell stocks. Besides the <a href="/assets/abfe-lesson5.pdf">lesson 5 slides</a>, I have uploaded a <a href="/assets/abfe-lesson5-bancor.pdf">proof behind the bancor formular</a> for your reference. Exercise 5 can be found <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise05-task.md">here</a>.</p>

<b>Lesson 6: Flows</b>

<p>In lesson 6, we take a deeper look at how capital flows influence stock prices. Here are <a href="/assets/abfe-lesson6.pdf">the slides</a>, as well as a <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise06-task.md">link to exercise 6</a>.</p>

<b>Lesson 7: Equality</b>

<p>Lesson 7 is on measuring equality and discusses the World3 model by the Club of Rome. Here are <a href="/assets/abfe-lesson7.pdf">the slides</a> and the <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise07-task.md">exercise</a>.</p>

<b>Lesson 8: Testing</b>

<p>Lesson 8 is about unit tests and test driven development, using the example of market making. It is easy to test whether market making is done well, but it is hard to actually come up with a good market making strategy, making this problem well-suited for testing. Here are <a href="/assets/abfe-lesson8.pdf">the slides</a> and the accompanying <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise08-task.md">exercise</a>.</p>

<b>Lesson 9: Capital</b>

<p>In lesson 9, we extend the model to capital by making land tradable and producible. A newly introduced agent RealEstateAgent does not only act as a market maker for land, but also has a production function to convert man-hours into land (think of land development, deforestation, building roads, etc.). However, this production function has "a memory" and is shared among all real estate agents. Thus, it gets increasingly harder to develop new land, depending on how much land has already been produced. Here are <a href="/assets/abfe-lesson9.pdf">the slides</a>, some <a href="/assets/heuristics-presentation.pdf">auxiliary slides on the farm's production decision</a>, and <a href="/assets/overfishing.xlsx">excel sheet for the overfishing example</a>, and the description <a href="https://github.com/meisser/course/blob/master/exercises/journal/exercise09-task.md">task for the final presentation</a>.</p>

<b>Lesson 10: Leverage</b>

<p>In lesson 10, we discuss how leverage can affect stock market returns using the paper <a href="https://arxiv.org/abs/0908.1555">Leverage Causes Fat Tails and Clustered Volatility</a> by Thurner et al.. However, we won't add leverage to our simulation as it is complex enough already. Here are the <a href="/assets/abfe-lesson10.pdf">slides</a>, and some <a href="/assets/abfe-lesson10-leverage.pdf">auxiliary slides</a>.</p>

abfe-lesson10-jupyter

<b>Recurring Themes</b>

<p>Emergence: how do the micro-properties of a system shape its macro-characteristics? When is the whole more than the sum of its parts?

Evolutionary finance: what strategies do survive in the long run and how do evolutionary dynamics impact the macro outcome?

Heuristics: Are there simple heuristics based on local information that allow agents to perform similarly well as agents with rational expectations and perfect information?

Chaos: even simple system can exhibit chaotic behavior.

Complexity: how can software engineering help in managing the complexity?</p>

<b>Literature</b>

<p>Farmer and Foley published a nice <a href="https://www.researchgate.net/profile/Duncan_Foley/publication/51437577_The_Economy_Needs_Agent-Based_Modeling/links/5714ccb108aeebe07c06c72e/The-Economy-Needs-Agent-Based-Modeling.pdf">motivational article</a> on why we need agent-based modeling in the well-known journal Nature. A list with some classics from the literature on agent-based economics can be found on <a href="http://www2.econ.iastate.edu/tesfatsi/afinance.htm#BasicRead">Leigh Testfatsion's site</a>. Another early and notable economic model is <a href="http://www.ifn.se/storage/cms/91fc7b2ed0f3440a918871ffa0a36d73/59024245407a4a3fadebca71db86015e/pdf/B79AF4E97E52C2C7723DD26462792BE1AB13FF08/Wp222.pdf?MediaArchive_ForceDownload=true&PropertyName=File1&ValueIndex=0">MOSES by Gunnar Eliassion</a>, which served as a basis for various Swedisch economic policy decisions. The biggest effort so far to build a large-scale agent-based economic models is the European <a href="http://www.crisis-economics.eu/">Crisis Economics project</a>. Generally, literature will be provided during the course as needed. We will stick closer to classic general equilibrium models than other contemporary agent-based models, similar to like I previously did in <a href="https://link.springer.com/article/10.1007/s10614-016-9616-x">this publication</a>. Some fundamental thoughts on the role of computational complexity in social sciences can be found in the excellent article <a href="https://arxiv.org/pdf/1108.1791.pdf">Why Philosophers Should Care About Computational Complexity</a> by Scott Aaronson. A more hands-on article by myself is <a href="http://meissereconomics.com/2017/06/22/code.html#main">The Code is the Model</a>, in which I apply the insights of agile software development to agent-based modeling.</p>

<b>Grading</b>

<p>There is no exam. Grades are based on exercises as well as a short presentation in the end. Computer scientists present the economic aspects of their findings, whereas economists will present the software engineering view.</p>

<b>Registration</b>

<p>If you want to attend this course, please <a href="https://docs.google.com/forms/d/e/1FAIpQLSfiUZGNaYk8NIR_RWXHa7f5W4S-vUUTmfpFBs0hOOgmZ22x-w/viewform?usp=sf_link">fill in this form</a> before September 21st. Seats are assigned on a first-come-first-serve basis and limited to 30 students. Do not forget to also register in the <a href="https://idagreen.uzh.ch/mb/">UZH module booking system</a> before October 13th, whereas ETH students first need to <a href="http://www.uzh.ch/de/studies/application/mobilitaet/applyhsuma.html">register here</a> before September 15th, choosing "Wirtschaftswissenschaftl. Fakultät" and "MA UZH Wirtschaftswissenschaften". For ETH students, credits will automatically be transferred to the ETH booking system once the semester is over.</p>

<p>Teams of two will be formed during the first lecture on September 22nd. The course takes place on Fridays from 14:15 to 15:45 at KOL-F-123, in the main building of University of Zurich. In case you have questions, feel free to get in touch with me by writing to luzius@meissereconomics.com .</p>

<p><center><a href="https://docs.google.com/forms/d/e/1FAIpQLSfiUZGNaYk8NIR_RWXHa7f5W4S-vUUTmfpFBs0hOOgmZ22x-w/viewform?usp=sf_link" class="button button-style1">Register Now</a></center></p>

