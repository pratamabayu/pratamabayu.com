---
title: "About"
date: 2021-06-17T13:58:33+07:00
draft: false
aliases: [/about]
---

<section class="flex flex-align-items-center flex-justify-content-center">
    <div>
        <h1 class="text-center">Pratama Bayu Widagdo</h1>
        <h3 class="text-center">I'm a <span id="word-rotating">Designer,Programmer,Lecturer</span></h3>
    </div>
</section>

<section class="margin-large margin-remove-horizontal@m grid grid-4-columns grid-1-columns@m gap-medium">
    <div><div class="flex align-items-center justify-content-center"><img src="/images/profile_photo.jpg" class="text-center@m border-radius-1/2" width="128px"/></div></div>
    <div class="grid-column-span-2 grid-column-span-1@m">
        <p>I'm a <span id="my-age"></span> years old, Designer, Programmer, and Lecturer from Indonesia, currently based in Semarang. I use design thinking to solve problems, especially those related to digital technology. So, I love everything about application, game, and web programming to support it. At free time, I usually play with my family and play bass instrumentally.</p>
        <p>I have been writing code since 2005. Experienced as professional freelance application, game, and web programmer since 2014.</p>
        <p>Let’s work together and you won’t be disappointed. So, Hire me and I will make a solution of your business become a lasting success in the marketplace.</p>
    </div>
    <div></div>
</section>

<section class="margin-large margin-remove-horizontal@m grid grid-4-columns grid-1-columns@m gap-medium">
    <div><h5>Education</h5></div>
    <div class="grid-column-span-2 grid-column-span-1@m">
        <h6>Master of Design</h6>
        <p>Bandung Institute of Technology<br/><span class="text-italic">2 years course</span></p>
    </div>
    <div>
        <p>October 2015</p>
    </div>
    <div></div>
    <div class="grid-column-span-2 grid-column-span-1@m">
        <h6>Bachelor of Visual Communication Design</h6>
        <p>Dian Nuswantoro University<br/><span class="text-italic">4 years course</span></p>
    </div>
    <div>
        <p>October 2012</p>
    </div>
</section>

<section class="margin-large margin-remove-horizontal@m grid grid-4-columns grid-1-columns@m gap-medium">
    <div><h5>Work</h5></div>
    <div class="grid-column-span-2 grid-column-span-1@m">
        <h6>Visual Art Lecturer</h6>
        <p>Semarang State University</p>
        <p>Teaching is another way to gain insight. Talking about the combination of art, design, and digital technology that can provide a solution to a problem is always interesting to me.</p>
    </div>
    <div>
        <p>August 2016 - current</p>
    </div>
    <div></div>
    <div class="grid-column-span-2 grid-column-span-1@m">
        <h6>Designer and Programmer</h6>
        <p>Freelance</p>
        <p>I also work as a freelance IT consultant and independent app, web, and game developer, so I sometimes get paid for that.</p>
    </div>
    <div>
        <p>June 2012 - current</p>
    </div>
</section>

<section class="margin-large margin-remove-horizontal@m grid grid-4-columns grid-1-columns@m gap-medium">
    <div><h5>Skillset</h5></div>
    <div class="grid-column-span-3 grid-column-span-1@m">
        <div class="grid grid-2-columns grid-1-columns@m gap-medium">
            <div class="card card-default box-shadow-large box-shadow-none@dark">
                <!--<div class="card-header padding-remove-horizontal padding-remove-top">
                    <img src="/images/skillset_interactive media.png" class="border-radius-xsmall border-radius-remove-bottom-left border-radius-remove-bottom-right width-1/1">
                </div>-->
                <div class="card-body">
                    <h5>Interactive Media</h5>
                    <p>When designing interactive media such as 2d/3d games, simulations, virtual reality, and augmented reality apps, I often use C++, C#, and Unity3D ⁠&mdash; real-time content creation.<p>
                </div>
            </div>
            <div class="card card-default box-shadow-large box-shadow-none@dark">
                <!--<div class="card-header padding-remove-horizontal padding-remove-top">
                    <img src="/images/skillset_web.png" class="border-radius-xsmall border-radius-remove-bottom-left border-radius-remove-bottom-right width-1/1">
                </div>-->
                <div class="card-body">
                    <h5>Web</h5>
                    <p>Web backend, designed with C# language, ASP Net Core framework, MongoDB database, and RabbitMQ message queue. While the web frontend, designed with HTML5, CSS3 &mdash; with <a href="https://github.com/pratamabayu/graff" target="_blank" class="text-underline">the Graff CSS framework</a>, and Typescript &mdash; with the Angular web application framework.<p>
                </div>
            </div>
            <div class="card card-default box-shadow-large box-shadow-none@dark">
                <!--<div class="card-header padding-remove-horizontal padding-remove-top">
                    <img src="/images/skillset_desktop app.png" class="border-radius-xsmall border-radius-remove-bottom-left border-radius-remove-bottom-right width-1/1">
                </div>-->
                <div class="card-body">
                    <h5>Desktop App</h5>
                    <p>When designing a desktop app I will prefer to write it in Dart with the Flutter multi-platform application framework. In my legacy experience, I often wrote it using C# with Windows Presentation Framework as UI framework.<p>
                </div>
            </div>
            <div class="card card-default box-shadow-large box-shadow-none@dark">
                <!--<div class="card-header padding-remove-horizontal padding-remove-top">
                    <img src="/images/skillset_mobile app.png" class="border-radius-xsmall border-radius-remove-bottom-left border-radius-remove-bottom-right width-1/1">
                </div>-->
                <div class="card-body">
                    <h5>Mobile App</h5>
                    <p>When designing a mobile app I will prefer to write it in Dart with the Flutter multi-platform application framework. In my legacy experience, I often wrote it using C# with Xamarin.Forms as cross-platform UI framework.<p>
                </div>
            </div>
        </div>
    </div>
</section>

<script>
    function calculateAge(dateString) {
    var birthday = +new Date(dateString);
    return ~~((Date.now() - birthday) / (31557600000));
  }
</script>

<script>
    var myAgeElement =  document.getElementById('my-age');
    myAgeElement.innerText = calculateAge("1989-06-24");
</script>
