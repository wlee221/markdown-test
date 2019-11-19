| Type | Target | Examples |
|:---------:|:-------------------------------------------------------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Property | Element property Component property Directive property  | ```javascript <img [src]="heroImageURL /> <app-hero-detail [hero]="currentHero /> <div [ngClass]="{'special': isSpecial}" /> ``` |
| Event | Element event Component event Directive event | ```javascript <button (click)="onSave()">Save</button> <app-hero-detail (deleteRequest)="deleteHero()" /> <div (myClick)="clicked=$event" clickable>click me> </div> ``` |
| Two-way | Event and property | ```javascript <input [(ngModel)]="name"> ``` |
| Attribute | Attribute | ```javascript <button [attr.aria-label]="help">help</button> ``` |
| Class | class property | ```javascript <div [class.special]="isSpecial">Special</div> ``` |
| Style | style property | ```javascript <button [style.color]="isSpecial ? 'red' : 'green'"> ``` |
