# Boostrap-4

Como quitar el borde azul que aparece al hacer focus en los inputs y selects bootstrap 4 2020

Codigo del dropdown
                        
            <div class="dropdown">
              <a  style="color:white;" class="btn dropdown-toggle" href="#" role="button" id="dropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"> Dropdown link</a>
                 <div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                     <a class="dropdown-item" href="#">Action</a>
                     <a class="dropdown-item" href="#">Another action</a>
                     <a class="dropdown-item" href="#">Something else here</a>
                 </div>
           </div>
                    

agregar al css 
  
  
            .dropdown a:focus{
                /*Modifica lo que quieras*/
                outline:none !important;
                outline-width: 0 !important;
                box-shadow: none;
                -moz-box-shadow: none;
                -webkit-box-shadow: none;
            }
