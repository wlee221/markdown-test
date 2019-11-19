| Type | Target | Examples |
|:---------:|:-------------------------------------------------------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Property | Element property Component property Directive property  | ```<img [src]="heroImageURL /> <app-hero-detail [hero]="currentHero /> <div [ngClass]="{'special': isSpecial}" /> ``` |
| Event | Element event Component event Directive event | ```<button (click)="onSave()">Save</button> <app-hero-detail (deleteRequest)="deleteHero()" /> <div (myClick)="clicked=$event" clickable>click me> </div> ``` |
| Two-way | Event and property | ```<input [(ngModel)]="name"> ``` |
| Attribute | Attribute | ```<button [attr.aria-label]="help">help</button> ``` |
| Class | class property | ```<div [class.special]="isSpecial">Special</div> ``` |
| Style | style property | ```<button [style.color]="isSpecial ? 'red' : 'green'"> ``` |
