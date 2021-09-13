<template>
  <ul class="skills">
      <li class="dev">
        <div class="left"><strong>Développement web</strong></div>
        <div class="right right-dev">
          <p>Langages <strong>Front-end :</strong></p>
          <b>HTML / SCSS / JAVASCRIPT</b>
          <p>Frameworks <strong>Front-end :</strong></p>
          <b>ReactJS / Angular / VueJS</b>
          <p>Langages <strong>Back-end :</strong></p>
          <b>NodeJS / PHP</b>
          <p>Frameworks <strong>Back-end :</strong></p>
          <b>ExpressJS / Symfony</b>
          <p>Base de données: <b>MYSQL / MARIADB / MICROSOFT SQL</b></p>
          <p>Logiciel de <strong>gestions</strong> &amp; <strong>CLI</strong>:</p>
          <b>GIT - GITHUB</b>
        </div>
      </li>
      <li class="video">
        <div class="left"><strong>Montage vidéo</strong></div>
        <div class="right right-video">
            <div class="level">
                <div class="ninety"></div>
            </div>
            <p>Vidéaste amateur depuis plus de 3 ans avec 
                <strong>Adobe Première Pro</strong>, 
                avec une très bonne connaissance du logiciel et des tendances actuelles.
            </p>
        </div>
      </li>
  </ul>
</template>

<script>
export default {
}
</script>

<style lang="scss">

.skills {
    margin-bottom: 30px;
    list-style: none;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0;
    font-size: 17px;
    color: #555555;

    .dev, .video {display: flex;}

    .left {
        width: 127px;
        margin-right: 40px;
        color: #000;
    }

    .right {
        flex: 1;
    }

    .right-dev { margin-bottom: 20px; }
    .right-video {
        .level {
            margin-bottom: 10px;
            height: 3px;
            width: 50%;
            background-color: #999999;
            
            .ninety {height: 3px; width: 90%; background-color: #000;}
        }
     }
}

</style>