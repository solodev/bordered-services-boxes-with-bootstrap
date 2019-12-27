# bordered-services-boxes-with-bootstrap
To emphasize the division between default bootstrap columns, you may want to add borders to clean separate content; Added benefits is the ability to create hover properties.

## Tutorial
For detailed instruction's, view Solodev's [How to Create Bordered Services Boxes with Bootstrap](https://www.solodev.com/blog/web-design/how-to-create-bordered-services-boxes-with-bootstrap.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/2sx7bued/).

## HTML
The tutorial contains the following basic HTML markup.
```
    <div class="services-wrapper">
   <div class="container svcs-container">
     <div class="row">
       <div class="col-sm-4 services-box hoverServices">
         <div class="service-icon">
           <img alt="Valkyrie-1 Series" src="images/valkyrie.png">
         </div>
         <div class="info text-center">
           <h3 class="services-subheading">
             Valkyrie-1 Series
           </h3>
         </div>
         <div class="info col-lg-10 col-lg-offset-1">
           <ul>
             <li>Reusable heavy launch vehicle
             </li>
             <li>Capable of vertical takeoff
             </li>
             <li>Landing on the Moon
             </li>
           </ul>
         </div>
       </div>
       <div class="col-sm-4 services-box hoverServices">
         <div class="service-icon">
           <img alt="Talon-2 Series" src="images/talon.png">
         </div>
         <div class="info text-center">
           <h3 class="services-subheading">
             Talon-2 Series
           </h3>
         </div>
         <div class="info col-lg-10 col-lg-offset-1">
           <ul>
             <li>High altitude travel across the planet
             </li>
             <li>Crosses great distances in short periods of time
             </li>
             <li>Supply colonies with the necessary resources
             </li>
           </ul>
         </div>
       </div>
       <div class="col-sm-4 services-box hoverServices last">
         <div class="service-icon">
           <img alt="Lunar XPlorer" src="images/lunar-xplorer.png" style="width: 180px; height: 176px;">
         </div>
         <div class="info text-center">
           <h3 class="services-subheading">
             Lunar XPlorer
           </h3>
         </div>
         <div class="info col-lg-10 col-lg-offset-1">
           <ul>
             <li>Long-term space travel
             </li>
             <li>Information Flow Architecture
             </li>
             <li>Landing Page Development
             </li>
           </ul>
         </div>
       </div>
     </div>
     <!--row-->

   </div><!-- svcs-container -->
 </div><!-- services-wrapper -->
 </div>
 </div>
```

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```
