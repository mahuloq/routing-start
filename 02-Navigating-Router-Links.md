  <li role="presentation" class="active" routerLink="/"><a>Home</a></li>
        <li role="presentation"><a routerLink="/servers">Servers</a></li>
        <li role="presentation"><a [routerLink]="['/users']">Users</a></li>


      Navigate by putting

      routerLink in the a element.

      You can also use binding for more advanced cases.
