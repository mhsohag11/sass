# sass
sass/scss practice project

## Very basic code for understand easily sass code structure
## These keywords are very usefull things on sass

  1. @import 'filename';
  2. @mixin myFunction () {} 
     include myFunction ();
  3. @extend header;
  
  4. Nested structure: 

  header {
  nav {
    ul {
      li {
        a {
          &:hover {

          }
          &::before {
            
          }
        }
      }
    }
  }
}
