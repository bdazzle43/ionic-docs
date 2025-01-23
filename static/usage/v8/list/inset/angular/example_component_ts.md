```ts
import { Component } from '@angular/core';
import { IonContent, IonItem, IonLabel, IonList } from '@ionic/angular/standalone';

@Component({
  selector: 'app-example',
  templateUrl: 'example.component.html',
  styleUrls: ['example.component.css'],
  imports: [IonContent, IonItem, IonLabel, IonList],
})
export class ExampleComponent {}
```