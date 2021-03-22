*{
  box-sizing: border-box;
}

h1{
  text-align: center;
}

p {
  background-color: #bfbfbf;
  border: 2px solid black;
  height: 150px;
  margin-right: 10px;
  padding: 40px 10px 5px 10px;
  overflow: hidden;
}


#container {
  position: relative;
  
}

#p1 {
  background-color: #D59898;
  position: absolute;
  top: 0;
  right: 0;
  font-weight: bold;
  height: 35px;
  width: 120px;
  padding: 10px;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;

}
#p2 {
  background-color:#C14543 ;
  color: white;
  position: absolute;
  top: 0;
  right: 0;
  font-weight: bold;
  height: 35px;
  width: 120px;
  padding: 10px;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;

}
#p3 {
 background-color: #E5D198;
  position: absolute;
  top: 0;
  right: 0;
  font-weight: bold;
  height: 35px;
  width: 120px;
  padding: 10px;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;

}


.row {
  width: 100%;

}


/********** Large devices only **********/
@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }

  
}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
   
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}


@media (max-width: 767px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-1 {
    width: 8.33%;
  }
  .col-sm-2 {
    width: 16.66%;
  }
  .col-sm-3 {
    width: 25%;
  }
