# en-650-663-01-lab-0-cloud-based-hello-world-solved
**TO GET THIS SOLUTION VISIT:** [EN.650.663-01 Lab 0-Cloud-Based “Hello, World!” Solved](https://www.ankitcodinghub.com/product/en-650-663-01-lab-0-cloud-based-hello-world-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94927&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EN.650.663-01 Lab 0-Cloud-Based “Hello, World!” Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<h1>Cloud-Based “Hello, World!”</h1>
This lab consists of getting a simple “Hello, World!” application up and running on the cloud. You will use a public cloud provider to accomplish this task, and the tutorial help in the lab notes will assume Google AppEngine Standard as the basis for your application, implemented in Python 3 and Flask.

&nbsp;

This is <em>not required</em>. You may use any cloud provider with which you are comfortable, and any language that makes sense for you. Do know that if you use something else (e.g., AWS Lambda and JavaScript) I can help you a little, but choosing something like that implies that you don’t <strong>need</strong> as much help, and I will prioritize my time accordingly. Don’t let that stop you if you’re anxious to use your own thing, just know that for the first couple of weeks of the semester I will be spending the bulk of my help time bringing beginners up to speed to get them ready for the remainder of the course.

<h1>Grading</h1>
This lab is graded on a pass/fail basis. You can get all or none of the points, since it is relatively simple (not a lot of pieces). Success is measured simply as my (or my CA’s) ability to see your “Hello, World!” site, with your name on it, from somewhere on the Internet.

<h2>Minimum Requirements</h2>
Provide me with a URL pointing to your own cloud application. When I navigate to it, I should see (at a minimum, go nuts if you want) something that includes your name. It does not have to say “Hello, World!”, though that is tradition, it merely has to show me your name.

<h1>Background and Tips</h1>
Getting up and running with a PaaS (Platform as a Service) or an FaaS (Function as a Service) is not always straightforward. You need to get accounts set up, make sure that your choice includes the appropriate data storage (later on, at least, though storage is not needed for this first lab), find a place to put your code that the provider will serve up, and then figure out how to use the SDK.

&nbsp;

Note that more background will be given in the next lab, where things get a little more interesting. Here we just get going on the basics.

&nbsp;

The steps you will complete for project setup are basically these:

<ul>
<li>Go to <a href="https://console.cloud.google.com">https://console.cloud.google.com</a> and create a new Project.</li>
<li>Use the upper-left menu to get to the <a href="https://console.cloud.google.com/appengine">AppEngine</a></li>
<li>If you’re in your new project, it will show you a “Create Application” button. Click that.</li>
<li>Choose a region. We’re in the us-east-1 region, so that will give the best latency from JHU, if you happen to be near the Homewood campus.</li>
<li>I choose “Python”, “Standard” on the next page, but you can pick another language if you like. I would <strong>not</strong> choose “Flexible” unless you really know what you are doing and are <em>willing to spend money</em>.</li>
<li>Note that by default the documentation it leads you to is for Python 2. The Python 3 documentation can be found here: <a href="https://cloud.google.com/appengine/docs/standard/python3/">https://cloud.google.com/appengine/docs/standard/python3/</a></li>
<li>Follow instructions to download the cloud SDK and get it set up.</li>
<li>Do a “gcloud auth login” so that deployment can work, and your dev server can hit the database (the local development datastore is apparently deprecated).</li>
</ul>
&nbsp;

Eventually (maybe now!) you will want to go to your project’s “service accounts” and generate a JSON key file for the default appengine service account. You can then point to that file in the <a href="https://cloud.google.com/docs/authentication/production">GOOGLE_APPLICATION_CREDENTIALS</a> environment variable to make things work from your local system. I use a small bash script to point to that when running my local Flask app so that it doesn’t pollute my system with random junk. For example:

&nbsp;

<table>
<tbody>
<tr>
<td width="624">#!/bin/bash

&nbsp;

export GOOGLE_APPLICATION_CREDENTIALS=”$HOME/.config/gcloud/appengine-token.json”

export GAE_ENV=”localdev”

python main.py
</td>
</tr>
</tbody>
</table>
&nbsp;

Once you are up and running, you will need to create your HTML file that you want served. You can do this in a couple of ways:

&nbsp;

<ol>
<li>Static: you can set up your app.yaml handler for “/” to be a static directory, and place an “index.html” file in the directory you specify, or</li>
<li>Dynamic: you can write a little Python/Flask application that serves up the index.html file and specify that as the script.</li>
</ol>
&nbsp;

There are numerous “Hello, World!” AppEngine tutorials online. I would encourage you to look at these to get started.

<h2>Suggested Additional Work</h2>
Whichever approach you chose to use (static or dynamic), try making your lab work the other way, now. That way you’ll be ready for future labs, which use a little bit of both!

&nbsp;
