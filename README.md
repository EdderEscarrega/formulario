Formulario
En este caso se importó el angular material que nos servira para la creación de diferentes tipos de componentes reutilizado para facilitar el proceso
Se agrego asi mismo import {FormsModule} from '@angular/forms';
import { MatInputModule } from '@angular/material/input';
import { MatButtonModule } from '@angular/material/button';
para que se puedan utilizar los botones y plantillas del angular Material
Luego se agregó <mat-form-field>
    <input matInput [(ngModel)]="valor1" type="number" placeholder="Ingrese primer valor">
  </mat-form-field>

  <mat-form-field>
      <input matInput [(ngModel)]="valor2" type="number" placeholder="Ingrese segundo valor">
  </mat-form-field>
  que con ello estamos declarando una etiqueta input para capturar los datos
  y por ultimo se agregó .contenedor {
    display: flex;
    flex-direction: column;
    margin:1rem auto;
    max-width: 600px;
}    
para declarar las dimensiones del contenedor que tendra el formulario
