# trial-page-aargghhh-
<!doctype html> 
<html lang="en">
<head>
    <meta charset="utf-8">
    <style type="text/css">
    .coaches .grid_2 { margin-left: 0; }
    .large { font-size: 25px; margin-bottom: 20px; }
    #promo p.small { font-size: 14px; }
    a.apply { background: #d3360b; display: inline-block; color: #fff; padding: 10px 20px; -webkit-border-radius: 4px;
    -moz-border-radius: 4px; border-radius: 4px; }
    </style>
    <script type="text/javascript" src="http://maps.googleapis.com/maps/api/js?sensor=false"></script>
    <script type="text/javascript">
      function initialize() {
          var myOptions = {
            zoom: 14,
            center: new google.maps.LatLng(-41.290512,174.77922),
            mapTypeId: google.maps.MapTypeId.ROADMAP
          };
          map = new google.maps.Map(document.getElementById('map_canvas'), myOptions);
          var options = {
            position: new google.maps.LatLng(-41.290512,174.77922),
            icon: "./images/heart-marker-sm.png"
          };
          var marker = new google.maps.Marker(options);
          marker.setMap(map);
      }
    </script>

    <Motueka Friday 6 & Saturday 7 November 2015>
     
    <title>Wellington March 2014</title>
      
    <!--  Write a metatext. This is what will show on the Facebook page and for instance search engines. -->

    <meta name="description" content="Rails Girls goes to Motueka: join the two-day crash-course to the exciting world of building web applications with Ruby on Rails.">
    <meta name="author" content="Rails Girls">

    <link rel="shortcut icon" href="/favicon.png">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">

    <link rel="stylesheet" href="./css/style.css">

    <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>
    <script type="text/javascript" src="main.js"></script>
    <script type="text/javascript" src="https://apis.google.com/js/plusone.js"></script> 
    <script type="text/javascript" src="//use.typekit.net/nbs6fzt.js"></script>
    <script type="text/javascript">try{Typekit.load();}catch(e){}</script> 

    <meta property="og:image" content="http://railsgirls.com/images/railsgirls-sq.png"/>
        <!--[if lt IE 9]>
      <script src="//html5shim.googlecode.com/svn/trunk/html5.js"></script>
      <![endif]-->
</head>

<body onload="initialize()">

    <header>
        <div class="container_12">
            <a id="logo" href="/"><img src="images/railsgirls-logo.png" alt="Rails Girls" /></a>
            <nav>
                <a href="./events.html">Events</a>
                <a href="./materials.html">Materials</a>
                <a href="./press.html">Press</a>
                <a href="http://blog.railsgirls.com">Blog</a> 
                <a href="http://guides.railsgirls.com">
                  Guides</a>  
            </nav>
        </div>
    </header>
  

    <!--   How to change the picture & header for site
    In the assets folder there is something called rg-header.psd. Be sure to download the fonts also. Name the file rg-yourcityname-header.png and your city picture rg-yourcityname.png. Add them to /images. 
    Steps to show on site
    1. Go to style.css
    2. Add these lines, always replacing 'yourcityname' with your actual city name. 
            .yourcityname#promo {
              padding-left:340px;
              background:url('../images/rg-yourcityname.png') no-repeat 0 10px,
                             url('../images/separator.png') no-repeat center bottom;
            }
            It will take a while before the changes show, so don't panic! 
            
    -->


    <!--  Change the header text. You can include a local hello or something else that brings context. Remember to mention the workshop is free. Remember to change to wufoo form link and dates. -->
 
    <div id="container" class="container_12 page clearfix">
        <div class="grid_12 omega alpha">
            <div id="promo" class="wellington">
                <h1>Rails Girls Wellington
                    <small>Sat 29th &amp; Sun 30th March 2014</small>
                </h1>
    
                <p>Kia ora!</p>
                <p>Rails Girls comes to Motueka! During this free two-day workshop we'll dive into the magical world of Ruby on Rails. </p>
                <p>We'll be running another workshop during the last weekend of March. This format will differ slightly from last year. We aim to take a range of skill levels and form smaller working groups based on experience.
                </p>
                <p>All of the material is available for you to learn at home by yourself but Rails Girls offers a casual and friendly environment to learn with others and a good tutor to student ratio to help get past some tricky areas.</p>

                <p><a class="apply" href="https://docs.google.com/forms/d/1Y0QGGF2bB4_GCDruKn5WJxoOP6OGZ9mcTtgo1RZdSgI/viewform"><strong>Apply for the next round</strong></a></p>
                <p class="small">If you applied and missed out last time we will prioritise you.</p>
                <p class="small">We can only take 50 students however there will be a waitlist.</p>

                <!--  Update the sharing texts.-->
                
                <div id="share">
                    <div style="margin:0 10px 0 0;">
                        <a href="http://twitter.com/share" class="twitter-share-button" data-url="" data-text="Rails Girls Wellington is happening again. It is going to be neat." data-count="horizontal" data-via="railsgirlswgtn" data-related="railsgirlswgtn">Tweet</a>
                        <script type="text/javascript" src="http://platform.twitter.com/widgets.js"></script>
                     </div>

                    <div id="fb-root" style=""></div>
                    <script src="http://connect.facebook.net/en_US/all.js#appId=156007477805811&amp;xfbml=1"></script>
                    <fb:like href="https://www.facebook.com/RailsGirlsWellington" layout="standard" width="300px" send="true" show_faces="true" font=""></fb:like>

                </div>

            </div>

            <hr />
      
            <!--  You can use here your own contact e-mail, or we can send you the e-mails from contact@! -->
          
            <div class="grid_4 alpha feature">
                <p><strong>You learn</strong> designing, prototyping and coding with the help from our coaches. We introduce you to Ruby on Rails as one of the open-source web developing frameworks.</p>
            </div>
            <div class="grid_4 feature">
                <p><strong>You need</strong> your own laptop, curiosity and a sprinkle of imagination!</p>
            </div>
            <div class="grid_4 omega feature">
                <p><strong>Want to help?</strong> If you're interested in coaching, <a href="https://docs.google.com/forms/d/1TBgPwSOm6CtZZUxNYrkT1TL5wlVPmOjvrKIZb-Mgt5A/viewform">here's a form you can fill out or pass on to other people</a>. We're also looking for sponsors - <a href="mailto:railsgirlswgtn@gmail.com">email us</a>.</p>
            </div>

        </div>
      
        <hr />
      
        <!--  Update the texts! -->
         
        <div class="grid_7 alpha">
            <!--        <h2>Friday</h2>
            <table id="schedule">
              <tbody>
                <tr>
                  <th>18.30 - 20.30</th>
                  <td>
                    <h4>Installation party</h4>
                      Get know the attendees a little bit before hand. Bring your laptop if you can, so we can help you install Ruby on Rails.<br>
                      There will be a special Ruby inspired cake!   
                  </td></tr>
              </tbody>
            </table>
            
            <hr />          
            
            <h2>Saturday</h2>
            
            <table id="schedule">
              <tbody>
              <tr>
                <th>9:00 - 10:00</th>
                <td>
                  <h4>Registration, coffee and installation fest</h4>
                    During the morning we’ll install Ruby on Rails on your computer.
                </td>
              </tr>
              <tr>
                <th>10:00 - 10:15</th>
                <td>
                  <h4>Welcome</h4>
                       Outline of the day &amp; word from sponsors
                      </td>
                    </tr>
                
              <tr>
                <th>10:20 - 10:45</th>
                <td>
                   <h4>Designing your web app -workshop</h4>
                </td>
              </tr>
              
                 <tr>
                    <th>10:50 - 11:10</th>
                    <td>
                      <h4><a href="http://www.tryruby.org">Tryruby.org</a></h4>
                      <strong>Let's get coding!</strong> 
                    </td>
                  </tr>
              
              <tr>
                <th>11:10 - 13:00</th>
                <td>
                  <h4>WORKSHOP</h4>
                  Jumpstart your first web application
                </td>
              </tr>
              <tr>
                <th>13:00 - 13:30</th>
                <td><h4>Lunch</h4></td>
              </tr>
              <tr>
                <th>13.30- 13:45</th>
                <td>
                  <h4>Bentobox - Understanding Web Apps</h4> 
                  Recap of what we’ve learned and how it all fits together.
                </td>
              </tr>
              <tr>
                <th>13:45 - 14:30</th>
                <td>
                  <h4>Lightning talks from coaches</h4>
                </td>
              </tr>
              <tr>
                <th>14:30 - 16:30</th>
                <td>
                  <h4>WORKSHOP</h4>
                  Extend your application.
                </td>
              </tr>
              <tr>
                <th>20:00 -</th>
                <td>
                  <h4>Afterparty</h4>
                  Open for everyone, meet cool people interested in tech. <br>
                
                </td>
              </tr>
              </tbody>
            </table> -->
            
            <!-- <hr/> -->

            <h3>FAQ</h3>
            <p><strong>How much does the workshop cost?</strong>
                Nothing, it's free! You just need to be excited!
            </p>

            <p><strong>Who is this aimed at?</strong>
                Rails Girls Wellington is open to all those who identify as women or girls with basic knowledge of working with a computer. We’ve had people of all ages taking part.</p>
            <p><strong>Can men attend?</strong>
                Yes, but you need to be accompanied by an interested lady. Also, girls are given a priority. 
            </p>
            <p><strong>Do you have a code of conduct?</strong>
                Yes - it is <a href="https://docs.google.com/document/d/1EiTZ-__VDuXpN1OqgVKnYr2Km_N3fD9WWN3g5cv5hAA/edit?usp=sharing">here</a>. We expect attendees, coaches, and sponsor representatives to behave respectfully to make sure everyone has a great time.
            </p>

            <!--  Update the team list       -->

            <div class="coaches clearfix">
                <hr />
                <h2>Wellington Coordinators</h2>

                <a href="https://twitter.com/merxplat" class="grid_2">Merrin Macleod<small>@merxplat</small></a>
                <a href="https://twitter.com/kellective" class="grid_2">Kelly Cheesman<small>@kellective</small></a>
            </div>

            <!--               <div class="coaches clearfix">
                    <h2>Wellington Coaches</h2>
                      <a href="https://twitter.com/tracey_norrish" class="grid_2">
                        Tracey Norrish
                        <small>@tracey_norrish</small>
                    </a>
                    <a href="https://twitter.com/MxCarmine" class="grid_2">
                        Kiesia Croucher
                        <small>@MxCarmine</small>
                    </a>
                    <a href="https://twitter.com/robramsaynz" class="grid_2">
                        Robert Ramsay
                        <small>@robramsaynz</small>
                    </a>
                    <a href="https://twitter.com/breccan" class="grid_2">
                        Breccan McLeod-Lundy
                        <small>@breccan</small>
                    </a>
                    <a href="https://twitter.com/ootoovak" class="grid_2">
                        Samson Ootoovak
                        <small>@ootoovak</small>
                    </a>
                    <a href="https://twitter.com/megahbite" class="grid_2">
                        Megan Bowra-Dean
                        <small>@megahbite</small>
                    </a>
                    <a href="https://twitter.com/eoinkelly" class="grid_2">
                        Eoin Kelly
                        <small>@eoinkelly</small>
                    </a>
                    <a href="https://twitter.com/joshuavial" class="grid_2">
                        Josh Vial
                        <small>@joshuavial</small>
                    </a>
                    <a href="https://twitter.com/shevauncoker" class="grid_2">
                        Shevaun Coker
                        <small>@shevauncoker</small>
                    </a>
                            <a href="https://twitter.com/PrototypeAlex" class="grid_2">
                        Alex Gibson
                        <small>@PrototypeAlex</small>
                    </a>
                    <div class="grid_2"> Fiona Sanggang </div>
                    <div class="grid_2"> Hannah Salmon</div>
                  </div> -->

            <!--              <div class="coaches clearfix">
                    <h2> Presentations from...</h3>
                    <a href="https://twitter.com/aurynn" class="grid_2">
                      Aurynn Shaw
                      <small>@aurynn</small>
                    </a>
                    <a href="https://twitter.com/eoinkelly" class="grid_2">
                        Eoin Kelly
                        <small>@eoinkelly</small>
                    </a>
                    
                    <a href="https://twitter.com/joshuavial" class="grid_2">
                        Josh Vial
                        <small>@joshuavial</small>
                    </a>
                    <a href="https://twitter.com/ootoovak" class="grid_2">
                        Samson Ootoovak
                        <small>@ootoovak</small>
                     </a>
                  </div>  -->
           
            
        </div>

           
        <div class="grid_4 push_1 omega">
            
                <h3>Sponsors</h3>
          
                <p><strong>Rails Girls Wellington has been made possible with the generosity and support of our sponsors. </strong></p>
                <p><small>If you're interested in helping us make this event as amazing (and regular) as posisble, get in touch with us at railsgirlswgtn@gmail.com .</small></p>
                <br>
                <div>
                    <p><strong>Gold Sponsors</strong></p>
                    <p class="sponsor-note">
                        <a href="http://www.powershop.co.nz/" style="display:block; margin:0 0 10px; border:0;">
                            <img src="./images/powershop.jpg" alt="Powershop" style="max-width: 180px;">
                        </a>
                    </p>
                    <p><strong>Bronze Sponsors</strong></p>
                    <p class="sponsor-note">
                        <a href="http://www.3months.com" style="display:block; margin:0 0 10px; border:0;">
                            <img src="./images/3months-Logo.png" alt="3months" style="max-width: 160px;">
                        </a>
                    </p>
                    <p class="sponsor-note">
                        <a href="http://www.abletech.co.nz" style="display:block; margin: 0 0 10px; border:0;">
                            <img src="./images/Abletech-Logo.png" alt="Abletech" style="max-width: 160px;">
                        </a>
                    </p>
                    <p class="sponsor-note">
                        <a href="http://www.github.com" style="display:block; margin: 0 0 10px; border: 0;">
                            <img src="./images/canberra/github.png" alt="GitHub" style="max-width: 160px;">
                        </a>
                    </p>
                    <p class="sponsor-note">
                        <a href="http://www.rabid.co.nz/" style="display:block; margin:0 0 10px; border:0;">
                            <img src="./images/rabid-logo.png" alt="Rabid" style="max-width: 100px;">
                        </a>
                    </p> 
                    <p class="sponsor-note">
                        <a href="http://www.enspiral.com" style="display:block; margin:0 auto 10px; border:0;">
                            <img src="./images/enspiral-logo.jpg" alt="Enspiral" style="max-width: 100px;">
                        </a>
                    </p>
                </div>

                    <!--           <p class="sponsor-note">
                               <a href="http://google-newzealand.blogspot.co.nz/" style="display:block; margin:0 0 10px; border:0;">
                                  <img src="./images/google-logo-wgtn.png" alt="Google" style="max-width: 250px;">
                                </a>
                              </p>
                              <p class="sponsor-note">
                                <a href="http://socialcode.io/" style="display:block; margin:0 0 10px; border:0;">
                                  <img src="./images/social-code.gif" alt="Social Code" style="max-width: 200px;">
                                </a>
                              </p>
                              <p class="sponsor-note">
                                <a href="http://www.catalyst.net.nz" style="display:block; margin: 0 0 10px; border:0;">
                                  <img src="./images/catalyst-logo.png" alt="Catalyst IT" style="max-width: 200px;">
                                </a>
                              </p>
                              
                              
                              
                              <p class="sponsor-note">
                               <a href="http://xero.com/" style="display:block; margin:0 0 10px; border:0;">
                                  <img src="./images/xero-logo.png" alt="Xero" style="max-width: 200px;">
                                </a>
                              </p>
                              <p class="sponsor-note">
                               <a href="http://labocaloca.co.nz/" style="display:block; margin:0 0 10px; border:0;">
                                  <img src="./images/labocaloca.png" alt="La Boca Loca" style="max-width: 200px;">
                                </a>
                              </p>
                                <p class="sponsor-note">
                               <a href="https://www.facebook.com/AllGoodDrinks" style="display:block; margin:0 0 10px; border:0;">
                                  <img src="./images/Karma-Cola.png" alt="Karma Cola" style="max-width: 200px;">
                                </a>
                              </p>
                            </div> -->

                    <!--     <p>
                          <strong>I know how to program - How can I help?</strong>
                          We’re also looking for people to be coaches. We’ll have a two-three hour workshop before the event to walk you through the curriculum. <a href="mailto:railsgirlswgtn@gmail.com>">Email us</a>
                        </p> -->
                    <!--     <a class="twitter-timeline" href="https://twitter.com/RailsGirlsWgtn/favorites" data-widget-id="336061033460416512">Favorite Tweets by @RailsGirlsWgtn</a>
                        <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
                        
                          
                            
                          </div> -->
          
        </div>


    </div>
    
    <!-- /content -->
    
    <footer>
        <p>2010-2014, Rails Girls. <a href="./press.html">Contact us</a> or follow us on <a href="http://twitter.com/railsgirls">Twitter</a> and <a href="https://www.facebook.com/railsgirls">Facebook</a></p>
        <p class="slogan">Get excited and make things!</p>
    </footer>
    <script>
      (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
      (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
      m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
      })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
      ga('create', 'UA-40976825-1', 'railsgirls.com');
      ga('send', 'pageview');
    </script>
</body>
</html>
