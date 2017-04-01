<html lang="en">

<head>

    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="Shubham Jaiswal">

    <title>Shubham Jaiswal | GSOC PROPOSAL 2017</title>
    <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>

    <!-- Bootstrap Core CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom CSS -->
    <link href="css/1-col-portfolio.css" rel="stylesheet">
    

    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
        <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
  <script type="text/javascript">
    google.charts.load('current', {'packages':['gantt']});
    google.charts.setOnLoadCallback(drawChart);

    function drawChart() {

      var data = new google.visualization.DataTable();
      data.addColumn('string', 'Task ID');
      data.addColumn('string', 'Task Name');
      data.addColumn('string', 'Resource');
      data.addColumn('date', 'Start Date');
      data.addColumn('date', 'End Date');
      data.addColumn('number', 'Duration');
      data.addColumn('number', 'Percent Complete');
      data.addColumn('string', 'Dependencies');

      data.addRows([
        ['1', 'Getting Familiar With the MIT AI code base', null,
         new Date(2017, 2, 20), new Date(2017, 4, 31), null, 20, null],
        ['2', 'Refining the Project with Mentors', null,
         new Date(2017, 3, 01), new Date(2017, 3, 30), null, 0, null],
        ['3', 'Devloping a Prototype', null,
         new Date(2017, 4, 1), new Date(2017, 5, 23), null, 0, null],
        ['4', 'Java Coding to create the Runtime Component', null,
         new Date(2017, 4, 23), new Date(2017, 5, 15), null, 0, null],
        ['5', 'Create the necessary Blockly Components', null,
         new Date(2017, 5, 15), new Date(2017, 6, 7), null, 0, null],
        ['6', 'Create Sample  Apps: Pie-Plotter', null,
         new Date(2017, 6, 8), new Date(2017, 6, 25), null, 0, null],
        ['7', 'Create Sample  Apps: Sensor-Plotter', null,
         new Date(2017, 6, 16), new Date(2017, 6, 30), null, 0, null],
        ['8', 'Fine-tune Data-plotter Component', null,
         new Date(2017, 5, 27), new Date(2016, 6, 30), null, 0, null],
        ['9', 'Implementation of visualisation component', null,
         new Date(2017, 6, 23), new Date(2017, 7, 10), null, 0, null],
        ['10', 'Final component App', null,
         new Date(2017, 7, 10), new Date(2017, 7, 10), null, 0, null],
        ['11', 'Documentation', null,
         new Date(2017, 5, 15), new Date(2017, 7, 10), null, 0, null],
        ['12', 'Testing', null,
         new Date(2017, 6, 01), new Date(2017, 7, 10), null, 0, null],
      ]);

      var options = {
        height: 400,
        gantt: {
          trackHeight: 30,
           defaultStartDateMillis: new Date(2017, 2, 20)
        }
      };

      var chart = new google.visualization.Gantt(document.getElementById('chart_div'));

      chart.draw(data, options);
    }
  </script>
</head>

<body>

    
    <!-- Page Content -->
    <div class="container">

        <!-- Page Heading -->
        <div class="row">
            <div class="col-lg-12">
                <h1 class="page-header">Application for GSoC 2017 | <a href="">Shubham Jaiswal</a> <br/>
                    <small> Visualisation Component </small>
                </h1>
                <br/>
                <h4>This proposal is available at: <a href="">https://sjais789.github.io/GSOC-17/</a></h4>
            </div>
        </div>
        <hr/>
        <!-- /.row -->

      <div class="row" >
            <div class="col-md-12">
            <h2><span id="0">Proposal Outline</span></h2>
            <ul>
              <li><a href="#1">Interest in App Inventor</a></li>
              <li><a href="#2">Interest in introductory programming</a></li>
              <li><a href="#3">Proposed summer project</a>
              <li><a href="https://drive.google.com/open?id=0B-tl5cHWTfg2eW1lWXVhV295elE">Resume</a>
                <ul>
                  <li><a href="#31">About me</a></li>
                  <li><a href="#32">Project Overview</a></li>
                  <li><a href="#33">Implementation Plan</a></li>
                </ul>
              </li>
              <li><a href="#4">Experience with the development tools</a></li>
              <li><a href="#5">Experience with teams, online developer communities and large code bases</a></li>
              <li><a href="#6">Non Trivial Apps Developed</a></li>
              <li><a href="#7">App Inventor Design Challenge</a></li>
          
<hr>
        <div class="row" >
            <div class="col-md-12">
                <h2><span id="1">Interest in App Inventor</span></h2>
                <p>I learnt MIT app inventor in  my first year of college. It gave me the flexibility to turn your logic into application.I have developed variety of application from lower to higher complexity like Blood Sugar app,Digital Gate-Pass System with this platform.It is my time to contribute to the platform and make the process simple and smart,so that every person/novice get benefit from it.</p>
            </div>
        </div>
        <!-- /.row -->


        <div class="row" id="2">
            <div class="col-md-12">
                <h2>Interest in introductory programming</h2>
                <p>I have been teaching OOP and Android Course  in 'ACM-club' in my university for last half an year. I have also organized  various workshops for beginners like “Idea to reality” to develop android application with MIT app inventor. It is a good-starter for them to develop logics and fundamental of Android application.</p>

            </div>
        </div>
        <!-- /.row -->


        <div class="row" id="3">
            <div class="col-md-12">
                <h2>Proposed summer project</h2>
                
                <p>In MIT app inventor 2 there is  no component available for plotting bar graphs/pie chart directly.
The aim of the project  is to develop a visualization component for plotting data  obtained from accelerometer and gyroscope or from a data file.
The libraries available to easy up our work available are AndroidMP chart,chart.js etc.
                <h3 id="31">About Me</h3>

                <p>Hello! I'm Shubham Jaiswal,pursuing bachelor of technology from BML Munjal University,India. I have done several hobbyist projects utilizing the MIT app inventor platform like Digital Gate Pass system. Through this Google Summer of Code project, I hope to contribute good quality code to the MIT App Inventor project and start my journey in open source contribution.</p>

                <h3 id="32">Project Overview</h3>

                <p> In MIT App Inventor 2 there is  no component available for plotting bar graphs/pie chart directly.The aim of the project  is to develop a visualization component for plotting data  obtained from accelerometer and gyroscope or from a data file.
This would provide the user a easy to use visual interface to plot data from various sources.
The libraries available to easy up our work are AndroidMP chart<a href="https://github.com/PhilJay/MPAndroidChart"></a>,Achartengine<a href="http://www.achartengine.org/index.html"></a>
chart.js<a href="http://www.chartjs.org/"></a> etc.</p>

                <h4>Supporting the Basic Data Plotting Capabilities</h4>

                <p>The key features of Data-Plotter component have several key characteristics:
                <ul>
                    <li>Pie-chart Plot</li>
                    <li> Real-time Data-plotting from :
                    <ul>
                    <li>Gyroscope/Accelerometer</li>
                    <li>From an existing file </li>
                    
                    </ul></li>
                </ul>
                
               



             
                <h4>Testing and Evaluating the Component Developed</h4>

                <p>Since data  plot space include bar graph,pie-chart and many more,I would like to develop for Line, Bar,pie-chart. I would like to develop several sample applications using the newly created visual component.I am hoping to take an iterative approach to refine the component as new requirements get elicited when these sample apps are created.
                <ul>
                  <li><b>Pie-Plotter App</b>
                    <ul>
                      <li>To test the newly developed to plot pie-charts.</li>
                      <li><b>Sensor-Plotter Apps :</b> To plot data from gyroscope</li>
                      
                    </ul>
                  </li>
                  
                

               <h3 id="33">Implementation Plan</h3>

               <p>The following diagram shows the rough timeline I have allocated to various aspects of the project. This is by no means the final time allocation, and with the guidance of the mentors I hope to update this.</p>

               <p><div id="chart_div"></div>

            
        
        <!-- /.row -->

        <div class="row" id="4">
            <div class="col-md-12">
                <h2>Experience with the development tools</h2>
                <h3>Javascript</h3>
                <p>I have developed a Tasker application to manage tasks using Js . I also have created a web-application "ShareON!!"(a twitter clone) using MEAN Stack framework  which uses Nodejs and Expressjs.</p>

                <h3>Android Development with the Java SDK</h3>
                <p>I have completed a Nanodegree program in Android from Udacity.I have good understanding of Java SDK.</p>
                <h4>Java</h4>
                <p>I have been coding in Java for last two years.I had done my Algorithm Course in Java. I'm dealing also with Java when I'm working on Android project. Finally Java is the langage that I'm using these days to develop 2D games.</p>
            </div>
        </div>
        <!-- /.row -->

        <div class="row" id="5">
            <div class="col-md-12">
                <h2>Experience with teams, online developer communities and large code bases</h2>
                <p>I have participated in various hackathons,recently IBM-KONE hackathon'17 to develop Image Recognition System using Watson Iot Platform in a team.I have recently involved in contributing to open source development.</p>
            </div>
        </div>
        <!-- /.row -->

        <div class="row" id="6">
            <div class="col-md-12">
                <h2>Non Trivial Apps Developed</h2>

                <h4>Digital-Gate Pass System</h4>
                <p>An app for college student which allows the student to fill form and get approval from hostel warden and parents. A single solution application for student,parent and warden.The process follows as first student fill the form with student account, second step is parent sign in from their account and approve it and then warden open the app to check the list of applied student along with parent permission and after that he/she approve it.</p>
                <p>| <a href="https://drive.google.com/open?id=0B-tl5cHWTfg2WWE5OGs5YUVRbnM">AIA</a> | <a href="https://drive.google.com/open?id=0B-tl5cHWTfg2b2duX1pRX1l5ZGc">APK</a> |</p>
                
             
            </div>
        </div>
        <!-- /.row -->

        <div class="row" id="7">
            <div class="col-md-12">
                <h2>App Inventor Design Challenge</h2>
                <h3>useFront Property</h3>
                <p>After going through the front camera issue, i found that Front camera uses the Intent which is not officially  documented and thus it is not  working on some android devices.Due to limitation of camera API 2 support for lower android version, we can use it.I had also <a href="https://github.com/mit-cml/appinventor-sources/issues/338">commented</a> it.
                </p>


                  <h3> Design and Implementation</h3>
                <p>We can add properties like:front camera,back camera and methods like ischecked().It is recommended to rewrite the component of the camera. We can use open() method to check number of camera available on the device After finding the Front Camera is present or not.We simply move towards take the pictures.
The SimpleFunction TakePicture() in the existing Camera AI component should be modified such that it would call camera = Camera.open(findFrontFacingCamera()) if the frontCamera property is set, where the findFrontFacingCamera Then we can call the<a href="https://developer.android.com/reference/android/hardware/Camera.html#takePicture(android.hardware.Camera.ShutterCallback,%20android.hardware.Camera.PictureCallback,%20android.hardware.Camera.PictureCallback,%20android.hardware.Camera.PictureCallback"> Android API's</a>camera.takePicture()method instead of launching the camera app via the intent.</p>

<p>The available component in MIT app inventor is Bar code which decodes the barcode and send text back to screen without user intervention.We can improve the component to send picture back instead of decoded-text.Create an activity class and handler of this class will take pictures instead of returning barcode-text.The activity class will open,take pictures using TakePicture() method.
</p>
         
                
            </div>
        </div>
        <!-- /.row -->

        
        <hr>

        <!-- Footer -->
        <footer>
            <div class="row">
                <div class="col-lg-12">
                    <p>Coded with love:Shubham Jaiswal</p>
                </div>
            </div>
            <!-- /.row -->
        </footer>


    <!-- /.container -->

    <!-- jQuery -->
    <script src="js/jquery.js"></script>

    <!-- Bootstrap Core JavaScript -->
    <script src="js/bootstrap.min.js"></script>


