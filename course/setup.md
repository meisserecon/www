---
layout: post
title: Setting up your agent laboratory
permalink: /course/setup
---

<p>To take part in this course, you'll need to install a number of programs. They are all free to use.</p>

<p><a href="/course/overview.png"><img src="/course/overview.png" alt="" class="image full"></a>This sketch gives you a general idea of the overall setup. In the following, I describe how to install all the software needed to successfully synchronize your code.</p>

<p>Install the <a href=http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html">Java 8 Development Kit</a>. Note that the JRE which users sometimes already have installed is not enough. The difference between the JRE and the JDK is that the JRE lets you run Java programs, while the JDK comes with a compiler and lots of documentation for programmers, allowing you to create Java programs. Also note that the simulation is not compatible with Java 9 or 10. It has to be Java 8.</a>

<p>Install <a href="sourcetreeapp.com">Source Tree</a>. If you have a Google account, you can authenticate with that one. When asked for connecting with a Git account, provide your Github account and clone your team repository (e.g. "team003"). You can also clone your repository manually after the installation completed. The repository URL looks like https://github.com/meisser/team000.git, depending on your team number. If you cannot access this URL with a web browser, try to login at github.com and visit the page again. If that does not work, something went wrong and you should contact me.</p>

<p><a href="/course/sourcetree-setup-upstream.jpg"><img src="/course/sourcetree-setup-upstream.jpg" alt="" class="image full"></a>Once you have cloned your team repository, add remote repository "https://github.com/meisser/course.git" and name it "upstream" as shown above. Upstream is the original repository that always hosts the latest version of the simulation and the latest exercises.</p>

<p><a href="/course/sourcetree-setup-upstream-pull.jpg"><img src="/course/sourcetree-setup-upstream-pull.jpg" alt="" class="image full"></a>To download the latest exercises to your computer, you first need to click "fetch" to "fetch from all remotes". This will make SourceTree show the latest available versions. To actually get them, you further need to click "pull" and then select upstream master as shown above. If you are lucky, everyhing works fine. If not, there are probably some conflicts, i.e. files that you changed locally and that also changed in the upstream repository in a conflicting way. The easiest way to resolve these conflicts, is to discard your local changes. But as long as you only change things in the exercise folders, there should not be any conflicts.</p>

<p><a href="/course/sourcetree-commit.jpg"><img src="/course/sourcetree-commit.jpg" alt="" class="image full"></a>Once you have made some changes (more about that in a minute), you can either discard them or upload them to your own repository named origin. To do so, commit the changes and push them to origin as shown above. It is highly recommended to always pull the latest changes from origin before you do anything in order to avoid conflicts with your teammate. Also do this before pulling from upstream in case your teammate already did so.</p>

<p>To check whether your changes have been properly uploaded, you can browse your repository in the web. Once the changes are there, the simulation server will pick them up and update the simulation.</p>

<p>Install the latest version of <a href="http://www.eclipse.org/downloads/">eclipse</a>, choose "Eclipse IDE for Java Developers" when asked.</p>

<p><a href="/course/eclipse-setup-jdk-1.jpg"><img src="/course/eclipse-setup-jdk-1.jpg" alt="" class="image full"></a>After having installed and started eclipse, make sure it points to the latest Java JDK. If it did not detect the JDK automatically, you need to add it manually.</p>

<p><a href="/course/eclipse-setup-jdk-2.jpg"><img src="/course/eclipse-setup-jdk-2.jpg" alt="" class="image full"></a>In the JDK settings, you should add the "-ea" flag. This enables assertions by default, making the simulations fail faster on errors, thereby making it easier to detect them. (The fail fast principle.)</p>

<p><a href="/course/eclipse-setup-import.jpg"><img src="/course/eclipse-setup-import.jpg" alt="" class="image full"></a>Import the four agent-based simulation projects as shown above.</p>

<p>Congratulations, you are ready to run your first simulation locally! This will be explained in a separate document that does not exist yet. :)</p>


