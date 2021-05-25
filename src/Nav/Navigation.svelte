<script>

</script>

<div class="navigation-wrapper">
    <div class="navigation-inner-wrapper">
        <a href="/" class="navigation-home" target="_self">Home</a>
        <nav class="main-navigation">
            <ul class="navigation-list">
                <li class="nav-item">lorem</li>
                <li class="nav-item">ipsum</li>
                <li class="nav-item">dolor</li>
            </ul>
        </nav>
    </div>
</div>

<style lang="scss">
    .navigation-wrapper {
        display: flex;
        align-items: center;
        width: 100%;
        height: 80px;
        color: white;
        background-color: rebeccapurple;
        
        .navigation-inner-wrapper {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 0 auto;
            width: 95%;

            .navigation-home {
                display: block;
                padding: 12px;
                color: white;
            }

            .main-navigation {
                width: 200px;
                padding: 12px;
                .navigation-list {
                    display: flex;
                    justify-content: space-between;

                }
            }
        }
    }

    @media screen and (min-width: 676px) {
        .navigation-wrapper {
            .navigation-inner-wrapper {
                max-width: 1280px;
            }
        }
    }
</style>