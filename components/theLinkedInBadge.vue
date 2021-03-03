<template>
  <div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="vertical" data-theme="dark" data-vanity="paalnymoen"><a class="LI-simple-link" href='https://no.linkedin.com/in/paalnymoen?trk=profile-badge'>Pål Øyvind Nymoen</a></div>
</template>

<script>
export default {
    head(){
        return{
            script : [
                {
                    src: 
                        'https://platform.linkedin.com/badges/js/profile.js',
                    type:
                        'text/javascript'
                } 
            ],
        }
    }
}
</script>

<style scoped>
.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.nav-item {
  margin: 0 10px;
}
.nav-item a {
  text-decoration: none;
  color: #fefefe;
}
.nav-item a:hover,
.nav-item a:active {
  color: #b4b4b4;
}
@media (max-width: 767px) {
  .nav-list {
    display: block;
  }
  .nav-item {
    margin-top: 16px;
    margin-bottom: 16px;
  }
}
@media (min-width: 768px) {
  .nav-list {
    display: flex;
  }
}
</style>
