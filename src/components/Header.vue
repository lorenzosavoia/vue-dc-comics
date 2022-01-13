<template>
  <header>
      <div class="container">
          <div class="nav-container">
              <div class="logo-container">
                  <img src="../assets/img/dc-logo.png" alt="">
              </div>
              <div class="nav-ul">
                  <ul>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                      <li> <a href="">testoo</a></li>
                    
                  </ul>
              </div>
          </div>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header',

}
</script>


<style lang="scss" scoped>
    .container{
        background-color: blue;
        height: 500px;
        width: 100%;
        .nav-container{
            display: flex;
            justify-content: space-between;
            background-color: white;
            width: 70%;
            height: 100px;
            margin: 0 auto;
            
            .logo-container{
                width: 80px;
                height: 80px;
                display: flex;
                align-self: center;
                img{
                    width: 100%;
                    
                }
            }

            .nav-ul{
                display: flex;
                ul{
                    display: flex;
                    list-style: none;
                    justify-content: center;
                    align-items: center;

                    li a{
                        display: block;
                        text-decoration: none;
                        font-weight: 800;
                        padding: .5em;
                        color: black;
                        &:hover,
                        &:active {
                            border-bottom: solid 1px blue;
                    
                        }
                    }
                      
                }
            }
        }
        
    }

</style>