# 01-Hola-Mundo

Este es el primer ejercicio del curso de Angular de cero a experto, en este ejemplo se valido la estructura principal de un proyecto, tambien se crearón los primeros componentes de forma manual y automatica

## Component

```
import { Component } from '@angular/core';

@Component({
    selector : 'app-header',
    templateUrl : './header.component.html'
})
export class HeaderComponent{

}

import { AppComponent } from './app.component';
import { HeaderComponent } from './components/header/header.component';
i

@NgModule({
  declarations: [
    AppComponent,
    HeaderComponent,
  
  ],
  imports: [],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }


```



## Comandos utilizados
*ng  new 

npm install

ng  serve -o

ng generate component components/footer

ng g  c components/footer


