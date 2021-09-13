<template>
  <ul class="card">
      <li class="left">
          {{date}}
      </li>
      <li class="right">
          <p><strong>{{name}}</strong></p>
          <div class="right-ca">
              <p>{{company}}</p>
              <span>{{address}}</span>
          </div>
          <p class="description">{{desc}}</p>
          <p class="stack">{{stack}}</p>
      </li>
  </ul>
</template>

<script>
export default {
    props: {
        date: String,
        name: String,
        company: String,
        address: String,
        desc: String,
        stack: String,
    }
}
</script>

<style lang="scss">

.card {
    display: flex;
    align-items: flex-start;
    list-style: none;
    margin: 25px 0;
    padding: 0;

    .left {
        width: 127px;
        margin-right: 40px;
        color: #777777;
    }

    .right {
        flex: 1;
        .right-ca {
            display: flex;
            margin-top: 3px;
            margin-bottom: 10px;

            p {color: #03bcff;}
            span {color: #444444;}
        }
        .description, .stack {
            color: #444444;
        }
        .description { padding-bottom: 2px;}
    }
}

</style>