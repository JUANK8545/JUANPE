# <ion-header [translucent]="true">
  
  <ion-toolbar>
    <ion-buttons slot="start">
      <ion-menu-button></ion-menu-button>
    </ion-buttons>
    <ion-title>{{ folder }}</ion-title>
  </ion-toolbar>
</ion-header>

<ion-content>
  <ion-list id="inbox-list">
    <form #formulario>
   <ion-row>
   <ion-col>
    <ion-item>
    <ion-label floating> Nombre
                <ion-input type="text" required
              name="nombres" 
              ngModel>

              </ion-input>

     </ion-label>
          </ion-item>
      </ion-col>
    </ion-row>
     <ion-row>
     <ion-col>
      <ion-item>
            <ion-label floating> Apellidos 
              <ion-input type="text" required
              name="apellidos" 
              ngModel>

              </ion-input>

   </ion-label>
    </ion-item>
      </ion-col>
     </ion-row>
      <ion-row>
     <ion-col>
     <ion-item>
            <ion-label floating> Correo electrónico 
              <ion-input type="text" required
              name="correo" 
              ngModel>

              </ion-input>


      </ion-label>
           </ion-item>
      </ion-col>
      </ion-row>
      <ion-row>
      <ion-col>
      <ion-item>
      <ion-label floating> Contraseña  
        <ion-input type="password" required
              name="clave" 
              ngModel>

              </ion-input>


     </ion-label>
      </ion-item>
        </ion-col>
      </ion-row>

     <ion-row>
        <ion-col>
          
            
            <button ion-button color="#F5240A" outline style="width: 351px;" click="registrousuario">Consultar</button>
            <ion-item>
              <button ion-button color="danger" outline style="width: 300px;" click="registrousuario">Registrarme</button>
            <br>
              <button ion-button color="danger" outline style="width: 300px;" click="inicioseccion">Iniciar Seccion</button>
             
          
          </ion-item>
        </ion-col>
      </ion-row>
    </form>

