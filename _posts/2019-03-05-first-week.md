---
layout: post
title: Week 1
categories:
- General
feature_image: "https://picsum.photos/2560/600?image=872"
---

First week, we have a team!...

Tiberio and Zifan created the website, it's hosted on GitHub and we use [Netlify](https://www.netlify.com) with a [Jekyll](https://jekyllrb.com) template, [Alembic](https://alembic.darn.es). With [Jekyll](https://jekyllrb.com) we can use markdown syntax to build our website and create a blog without having a dynamic website hosting, with SQL database and PHP. We just need to add markdown files and push them to the repo of website and then the [Netlify](https://www.netlify.com) GitHub extension will build and host the website for us. Another advantage is that in this way we can use GitHub versioning system also for website, instead of just develop locally and then pushing with FTP to website, losing the history of developing and not having commits.
We had also to find a free 2nd level domain (txjt.ml) from [Freenom](https://www.freenom.com/en/index.html?lang=en) for the website to redirect to the 3rd level free one from Netlify.

We worked also on our first idea of flower pot:
{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/sketches/brainstorming.jpg" caption="brain storming" width="320" height="425" %}

{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/sketches/the_pot.jpg" caption="The pot" width="400" height="300" %}  

<p>
In the beginning, we were thinking about creating a moving flower pot which would lead the plant towards the sunlight which may use several photodiodes on multiple directions of this pot. Considering the same idea of flower pot, Tapio said we could add the functionality of auto-watering with a sensor of humidity. Another idea was adding also LEDs to make the plant grow faster. It's a good idea but it's better to start with simple functionality and then implement it. So we finally decided to focus on the auto-watering design first.  
</p>

{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/sketches/Pot+reservoir.jpg" caption="Pot + Reservoir" width="600" %}
{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/sketches/reservoir+valve_page.jpg" caption="Reservoir + Valve" width="600" %}  

<p>
We have a reservoir with water which the user can hang on the ceiling or we could design a proper stand for it. Then we would use a siphon to let the water flow into the pot. We will design our valve in this way: a steel ball would stop the flow of water down the pot and when we want to open it we will use a coil to lift it up and let the water flow down.
</p>

{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/sketches/sensor.jpg" caption="sensor" width="600" %}  

<p>
As for the sensor, the idea is creating two conductive line close together and measure voltage, that changes when the humidity of soil changes, this is due to the different dielectric properties of soil when dry or not.
</p>

<h5 id="tasks-allocation" style="display:inline-block">Tasks allocation:</h5>  

<table style= "word-wrap:break-word;word-break:break-all;">
<tr>
<td><b>Task</b></td>
<td><b>Student</b></td>
</tr>
<tr>
<td>Website deployment </td>
<td>Tiberio Galbiati</td>
</tr>
<tr>
<td>3D modeling </td>
<td>Tepio Immonen</td>
</tr>
<tr>
<td>First PCB design </td>
<td> Jussi Parviainen</td>
</tr>
<tr>
<td>Sketching ideas  </td>
<td>together</td>
</tr>
<tr>
<td>Website & documentation</td>
<td>Zifan Xiao</td>
</tr>
</table>
