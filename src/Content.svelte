<script>

</script>

<div class="content-wrapper">
    <div class="content-inner-wrapper">
        <span>XYZ</span>
    </div>
</div>

<style lang="scss">
    .content-wrapper {
      display: flex;
      left: 50%;
      right: 50%;
      width: 100vw;
      max-width: 100vw;
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