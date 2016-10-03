<template>
  <div class="container"> 
   <div class="row">
       <div class="col-md-6 title">
           <h1 class="title__name">Lu Ye</h1>
           <p class="title__role">FullStack Developer</p>
       </div>
        <div class="col-md-6 contacts">
            <ul class="list-unstyled">
                <li> <span class="contacts__icon"> <i class="fa fa-phone text-primary"></i> </span> 0479181181 </li>
              <li>  <span class="contacts__icon"> <i class="fa fa-envelope text-primary"></i> </span> i@gfw.fail </li>
             <li>  <span class="contacts__icon"> <i class="fa fa-map-marker text-primary"></i> </span>  Melbourne, Australia </li>
              <li>  <span class="contacts__icon"> <i class="fa fa-github text-primary"></i> </span> gfwfail </li>
            </ul>
       </div>
   </div>
   <hr>
   <h3 class="text-primary header"><i class="fa fa-clock-o"></i> EXPERIENCE</h3>
 <div class="exp">

     <div class="row">

       <div class="col-md-4">
           <strong>Freelance</strong>
           <p>Since 2006</p>
       </div>
              <div class="col-md-8">
                             <strong>FullStack Devops</strong>

<p>                Have been worked as Delphi developer,Classic Asp Developer , Penetration testing engineer(CBSi China), Php Developer, iOS Developer and more other role for freelancer project.
</p>
              </div>

   </div>

   
       <div class="row">

       <div class="col-md-4">
           <strong>Pipex Melbourne, Australia</strong>
           <p>Mar 2016 - Aug 2016</p>
       </div>
              <div class="col-md-8">
                             <strong>FullStack Devops</strong>

<p>                  In the process of developing a modern online system which is an inventory and logistics SaaS. As the full stack devops of this project, I have been using an Agile methodology to gain requirements has allowed me to develop a system that fits all the requirements of the user. 
</p>
              </div>

   </div>
   <div class="row">

       <div class="col-md-4">
           <strong>FreePress, NY (Remote)</strong>
           <p>Mar 2016 - Aug 2016</p>
       </div>
              <div class="col-md-8">
                             <strong>FullStack Devops</strong>

<p>                 
    <li>Working independently and remotely to develop and implement projects.</li>
    <li>	Design prototype and gathered requirements </li
    ><li>	Developing a CMS based on PHP and MySQL
</li><li>	Developing  mobile apps based on ionic and Objective-C
</li><li>	Penetration testing on existing system to potential threats
</li><li>	Configure and secure CentOS server
</li>
</p>
              </div>

   </div>
 </div>
 <hr>
    <div class="row">
        <div class="col-md-6">
                <h3 class="text-primary header"><i class="fa fa-user"></i> SUMMARY</h3>
            <p>
                An ambitious problem solver with a passion for software development, and would like to join a team of like-minded developers.  
                <br>Developing has been a passion of mine from a young age which had taught me to create logical and innovative solutions to solve complex problems.
                <br>  I am constantly striving to learn new technologies and look at ways to better myself in this fast pace industry.

            </p>
        </div>
    </div>
   
  </div>
</template>

<script>
    import Hello from './components/Hello'

    export default {
        components: {

        }
    }
</script>

<style>
    @import 'https://fonts.googleapis.com/css?family=Lato:300,400,700';
</style>
<style lang="scss">
    $icon-font-path: '../node_modules/bootstrap-sass/assets/fonts/bootstrap/';
    $fa-font-path:'../node_modules/font-awesome/fonts/';
    @import '../node_modules/bootstrap-sass/assets/stylesheets/bootstrap.scss';
    @import '../node_modules/font-awesome/scss/font-awesome.scss';
    $title-color:#3abb9d;
    body {
        font-family: 'Lato', sans-serif;
        padding: 40px;
        color: #666;
        font-weight: 300;
        background: #fefefe;
    }
    
    strong {
        font-weight: 400;
    }
    
    .exp {
        height: 300px;
        overflow: scroll;
        & .row {
            margin-bottom: 30px;
        }
    }
    
    hr {
        margin: 0;
    }
    
    .header {
        font-weight: 400;
        position: relative;
        & i {
            float: left;
            position: absolute;
            left: -2em;
        }
    }
    
    .title {
        color: #000;
        &__name {
            margin: 0px;
            font-size: 40px;
            font-weight: 700;
        }
    }
    
    .contacts {
        color: #000;
        &__icon {
            display: inline-block;
            width: 1.2em;
            text-align: center;
        }
        & li {
            font-weight: 100;
        }
    }
    
    .text-primary {
        color: #33cc99;
    }
    
    .container {
        max-width: 800px;
    }
    
    html {
        height: 100%;
    }
</style>