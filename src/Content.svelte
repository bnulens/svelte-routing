<script>
</script>

<div class="content-wrapper">
  <div class="content-inner-wrapper">
    <span>XYZ</span>
  </div>
  <svg id="circSvg" width="10" height="10">
    <circle cx="5" cy="5" r="4" stroke="black" stroke-width="2" fill="white" />
  </svg>
</div>

<style lang="scss">
  .content-wrapper {
    display: flex;
    left: 50%;
    right: 50%;
    max-width: 95%;
    margin-right: -50vw;
    border: 1px solid blue;

    .content-inner-wrapper {
      max-width: 95%;
      margin: 24px auto;
      border: 1px solid green;
    }
  }

  @media screen and (min-width: 676px) {
    .content-wrapper {
      .content-inner-wrapper {
        width: 95%;
        max-width: 1280px;
      }
    }
  }
</style>
