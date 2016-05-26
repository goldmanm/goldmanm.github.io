---
layout: layout-shell
title: 
source: /app/posts/about
---

<!-- use that new container vertical center code you found! -->

<div class="about--intro">
<figure class="figure-circle">
!{{page.source}}/face.png!
<!-- <figcaption class="aboutQuote">day at the office</figcaption> -->
</figure>

# Hello,

#### want to hear a story?
</div>

Most people call me Mark, but for some reason it's commonly confused with Mike, and I sometimes get tired of correcting them. My passions include solving complex technical problems facing our world like mitigating risks associated with climate change or developing viable alternatives to fossil fuels. After hours, I work on projects that expand my skills and help me further explore the complexities of our world. I find understanding a diversity of viewpoints critical to understanding our world and excel at making lasting friendships wherever I've worked. In addition, I strive to improve the operational structure to better align with organization goals. My projects, observations, and helpful guides can be found in my [resume]() and in the posts on this website.

I was born in along the Texas/Mexico border, where most of my family currently lives. At the age of 2, I moved to the most diverse [county]() in the US, near Houston. The next 16 years I observed and was impacted by cultural differences, micro-biases, and privilege. By the time college ran around, I actively sought environments which encourage diversity. My youth in the American suburbs with numerous outdoor activities like camping brought forth ideas of sustainability. I experimented with challenges like not using private motor-vehicles, ran sustainability events..


I currently am a doctoral candidate at Massachusetts Institute of Technology (MIT) getting a degree in chemical engineering. I work on utilizing computational and experimental techniques to understand organic compounds burn in engines and transform into particles in the atmosphere. I work in two research groups on [combustion kinetics]() and [atmospheric chemistry](). 

I plan to graduate in 2019-2020 and have currently not committed to employment afterwards, so ["Say hello"](mailto:markgoldman@mit.edu) or [link me in](http://www.linkedin.com/in/mjgoldman).

## Work & Experience 

So far my experiences have mostly focused around concepts of sustainability in research, industry, and service. I have worked in Texas, Tennessee, Massachusetts, Singapore and Dubai. I started from the fast-food industry in high school, and moved to an oil refinery and national energy lab during undergrad. In grad school I've worked at an aluminum refinery and a US regulatory agency in grad school. It's a mouthful, so use the tabs below to explore or download my [resume]() to digest on the subway/bus home.


<notextile>

  <!-- .list is necessary for the list.js sorter -->
  <!-- 
  <ul class="list">
  {% for post in site.posts %}
  {% if post.published == true %} 
  {% if post.category == 'work' %}

    <li class="post {% if post.featured %} post--featured {% endif %}">

      <a href="{% if post.external %} {{ post.external }} {% else %} {{ post.url }} {% endif %} ">
        <div class="post__container {{ post.preview-css }} {% if post.preview-img == nil %} post__imgPreview--noImg {% else %} post__imgPreview" data-bg="{{ post.preview-img }} {% endif %}">

          <div class="post__info">

            <div class="post__date__container">
              <div class="post__date">{{ post.date | date: "%d %B %Y" }}</div>
            </div>

            <div class="post__title__container">
              <div class="post__title">{{ post.title }}</div>
            </div>

            {% if post.summary %}
            <div class="post__summary__container">
              <div class="post__summary">{{ post.summary }}</div>
            </div>
            {% endif %}

            {% if post.tags != null %}
              {% assign tags_list = post.tags %} 
                {% if tags_list.size > 0 %}
                  <div class="post__tags__container">
                    <ul class="post__tags">

                      {% if tags_list.first[0] == null %}
                        {% for tag in tags_list %} 
                          <li>{{ tag }}</li>
                        {% endfor %}
                      {% else %}
                        {% for tag in tags_list %} 
                          <li>{{ tag[0] }}</li>
                        {% endfor %}
                      {% endif %}
                    </ul>
                  </div>
                {% endif %}
                {% assign tags_list = nil %}
            {% endif %}

            <div class="clear"></div>
          </div>
        </div>
      </a>
    </li>
  {% endif %}
  {% endif %}
  {% endfor %}

  </ul> -->
</notextile>







<notextile>


<div class="timeline">

  <ul class="timeline__list">

    <div class="sticky-item" >
      <div class="timeline__year sticky-content">2014</div>
    </div>

      <li class="timeline__item expandablejs">
        <div class="timeline__preview expandablejs--preview">
          {% include expandablejs--expander.html %} 
          <div class="timeline__headline">
            <span class="timeline__client">Ubiquiti Networks</span>
            <div>
              <span class="timeline__title">User Experience Architect</span>
              <span class="timeline__location">Atlanta, GA</span>
              <span class="timeline__date">2014 &mdash; current</span>
            </div>
            <div class="timeline__desc">
              I define requirements, build site maps and create wireframes, as well as design, prototype, and develop the front-end user interfaces.
            </div>
          </div>
        </div>

        <div class="timeline__full expandablejs--full">
          <p>At Ubiquiti Networks I am currently designing and developing new customer-facing support and community tools that will launch in the Spring of 2016.</p>
        </div>
      </li>

  </ul>


  <ul class="timeline__list">

    <div class="sticky-item" >
      <div class="timeline__year sticky-content">2014</div>
    </div>

    <li class="timeline__item expandablejs">
      <div class="timeline__preview">
        <div class="timeline__headline">
          <span class="timeline__client">LaunchKitten</span>
          <div>
            <span class="timeline__title">Startup</span>
            <span class="timeline__location">Atlanta, GA</span>
            <span class="timeline__date">2014</span>
          </div>
          <div class="timeline__desc">Product design, front-end design and development on a startup project jumpstarted by <a href="http://www.switchyards.com">Switchyards</a>.</div>
        </div>
      </div>
    </li>

    <li class="timeline__item expandablejs">
      <div class="timeline__preview expandablejs--preview">
        {% include expandablejs--expander.html %} 
        <div class="timeline__headline">
          <span class="timeline__client">Nurun</span>
          <div>
            <span class="timeline__title">Sr. User Experience Architect</span>
            <span class="timeline__location">Atlanta, GA</span>
            <span class="timeline__date">2012 - 2014</span>
          </div>
          <div class="timeline__desc">User experience, business analysis, product design, and prototyping </div>
        </div>
      </div>

      <div class="timeline__full expandablejs--full">
        <p>At Nurun, I bring client projects to life. I help define project scope, functionality, research, and other needs, and help determine the feasibility and schedule. I translate requirements into a tangible experience with flow diagrams, site maps, wireframes, and prototypes, and work with our designers and the technical team to realize the product.</p>

        <p>Lately I've focused on creating a creative and wireframe presentation tool, and a more flexible, agile proess flow that emphasizes earlier research, user experience, and integration among departments.</p>

        <p>Clients include Nespresso, Assurant, Manheim, The Home Depot, GE Energy, and Disney.</p>
      </div>
    </li>
  </ul>

  <ul class="timeline__list">

    <div class="sticky-item" >
      <div class="timeline__year sticky-content">2013</div>
    </div>

    <li class="timeline__item expandablejs">
      <div class="timeline__preview expandablejs--preview ">
        {% include expandablejs--expander.html %} 
        <div class="timeline__headline">
          <span class="timeline__client">Freelance Projects</span>
          <div>
            <span class="timeline__title">Freelance</span>
            <span class="timeline__location">Atlanta, GA</span>
            <span class="timeline__date">2013</span>
          </div>
          <div class="timeline__desc">Sometimes I take on smaller side projects.</div>
        </div>
      </div>

      <div class="timeline__full expandablejs--full">
        <ul>
          <li>Designed and built <a href="http://www.upowerfitness.com">upower fitness</a>, a local a boutique gym and personal fitness concept.</li>
          <li><a href="http://gigagen.com/">GigaGen</a> IA, UX, and wirefames for a DNA sequencing tool through <a href="https://www.5amsolutions.com/">5am Solutions</a></li>
          <li>Built <a href="http://www.GodandTDM.com">God and The Drum Maschine</a> for an Atlanta-based artist and musician </li>
          <li>Helped <a href="http://www.callanwolde.com">Callanwolde Fine Arts Center</a> with Wordpress migration and form design </li>
          <li>Built a quick landing page for <a href="http://www.liztic.com">liztic</a>:, a cloud-based music-syncing service </li>
          <li>Helped an Atlanta-based artist build her landing page for her personal store at <a href="https://www.facebook.com/Foxboxes">FoxBoxes</a></li>
        </ul>

      </div>
    </li>
  </ul>



  <ul class="timeline__list">

    <div class="sticky-item" >
      <div class="timeline__year sticky-content">2010</div>
    </div>

    <li class="timeline__item expandablejs">
      <div class="timeline__preview expandablejs--preview">
        {% include expandablejs--expander.html %} 
        <div class="timeline__headline">
          <span class="timeline__client">Moxie</span>
          <div>
            <span class="timeline__title">User Experience Architect</span>
            <span class="timeline__location">Atlanta, GA</span>
            <span class="timeline__date">2010 - 2012</span>
          </div>
          <div class="timeline__desc">UX Architect for projects including Cartoon Network Mobile and Verizon Wireless</div>
        </div>
      </div>

      <div class="timeline__full expandablejs--full">
        <p>As a user experience architect, I translated client and business requirements into user flows, site maps, wireframes and technical specs. I developed wireframes, concepts, and functional prototypes, and worked with developers and designers to establish website and app functionality, user flow, information architecture.</p>
        
        <ul>
          <li>Established requirements and functionality through userflows, wireframes, information architecture charts, sitemaps, and other documentation.</li>
          <li>Explored design concepts through wireframes, paper, and functional prototypes.</li>
          <li>Participated in campaign concepting and strategy, and provided consultation, market research, and research into pitches and projects.</li>
          <li>Provided UX-focused QA, design direction, and feedback.</li>
        </ul>

        <ul>
          Clients include:
          <li><span class="style--highlight">Cartoon Network Mobile</span>: Designed new interface and information architecture for Cartoon Network mobile site. (2011)</li>
          <li><span class="style--highlight">Coca Cola</span>: Site design for Live Positively, Nestea, and various campaigns.</li>
          <li><span class="style--highlight">Verizon Wireless</span>: Shopping cart and phone purchase funnel, Verizon Developer Center, and many holiday campaigns and apps.</li>
          <li><span class="style--highlight">Garnier</span>: Many of the apps on Garnier.com including the Style Finder</li>
          <li>Other clients include BBC America, AMDRO, Pennington Seed, and Autotrader</li>
        </ul>

      </div>
    </li>

  </ul>



  <ul class="timeline__list">

    <div class="sticky-item" >
      <div class="timeline__year sticky-content">2009</div>
    </div>

    <li class="timeline__item expandablejs">
      <div class="timeline__preview">
        <div class="timeline__headline">
          <span class="timeline__client">Carnegie Mellon University</span>
          <div>
            <span class="timeline__title">Masters in HCI</span>
            <span class="timeline__location">Pittsburgh, PA</span>
            <span class="timeline__date">2009 - 2010</span>
          </div>
          <div class="timeline__desc">Earned a Masters in Human-Computer Interaction degree, which comprised of a combination of classes in interaction design methodologies, user research, interactive prototyping, and design. Relevant Coursework include HCI Project Course, HCI Methods Course, Service Design, Interaction Design, Software Architecture and User Interfaces, and Game Design (at the Entertainment Technology Center)</div>
        </div>
      </div>
    </li>

  </ul>


  <ul class="timeline__list">

    <div class="sticky-item" >
      <div class="timeline__year sticky-content">2004</div>
    </div>

    <li class="timeline__item expandablejs">
      <div class="timeline__preview">
        <div class="timeline__headline">
          <span class="timeline__client">University of Maryland, Baltimore County</span>
          <div>
            <span class="timeline__title">Computer Science &amp; Psychology</span>
            <span class="timeline__location">Catonsville, MD</span>
            <span class="timeline__date">2004 - 2009</span>
          </div>
          <div class="timeline--list-item--headline--short">I received an bachelor's in computer science, with a minor in psychology, where I both took classes and worked with both the cognitive and behavioral labs. My degree focused on game development, and game design including graphics, artificial intelligence, and algorithms. Our capstone project was an experimental strategy game built on Gamebryo.
        </div>
      </div>
    </li>

  </ul>

<!-- end timeline -->
</div>


</notextile>

## About This Site

This site design was originally created by [Jan Zheng](janzheng.com) using [Jekyll](https://github.com/mojombo/jekyll) with the original code available [here](https://github.com/janzheng/janzheng.github.com). He utilized [bourbon.io](http://bourbon.io/) and [Neat](neat.bourbon.io) for front-end styling in SASS. I modified his template to add blog post categories, changed links, etc. to better share me with you.

The site's formatting that I've worked on is released with an [MIT license]() with the site's content (blog posts, resume, etc.) released with a [Creative Commons NC A license](). Complete licence info is available [here]().

Icons are sourced from [IconMonstr](http://iconmonstr.com/) and [Flaticon](http://www.flaticon.com) and [Wikimedia](http://www.wikimedia.com). 

Cheers, 
Mark


