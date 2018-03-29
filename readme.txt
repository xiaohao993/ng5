ng -v

ng new ng5 —style=scss  —routing

ng serve -o

ng generate component home   —>  缩写  ng g c home


angular5 动画
npm install @angular/animations@latest —save
import { BrowserAnimationsModule } from '@angular/platform-browser/animations’;

import { trigger, style, transition, animate, keyframes, query, stagger } from '@angular/animations'




ng build
ng build —prod   //捆绑压缩