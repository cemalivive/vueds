<script>
export default ({
    setup() {},
});
</script>


<template>
    <div>
        <div class="container">
            <div class="app-bar">
                <div class="logo-wrapper">
                    <div class="logo">
                        <img src="@/assets/tk-logo.png" />
                    </div>
                </div>
                <div class="ticket-funnel">
                    <div class="home">
                        <i class="bi bi-house"></i>
                    </div>
                    <div class="seperator">1</div>
                    <div class="airplane">
                        <i class="bi bi-airplane"></i>
                    </div>
                    <div class="seperator">2</div>
                    <div class="profile">
                        <i class="bi bi-person-fill"></i>
    
                    </div>
                    <div class="seperator">3</div>
                    <div class="ticket">
                        <i class="bi bi-ticket-perforated"></i>
    
                    </div>
                    <div class="seperator">4</div>
                    <div class="payment">
                        <i class="bi bi-credit-card-2-back"></i>
                    </div>
    
                </div>
            </div>
    
        </div>
    </div>
</template>

<style scoped lang="scss">
.container {
    display: flex;
    .app-bar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        padding: 20px;
        background-color: #232b38;
        .logo-wrapper {
            width: 20%;
            .logo {
                width: 30%;
                img {
                    width: 100%;
                }
            }
        }
        .ticket-funnel {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            width: 80%;
            .seperator {
                font-size: 0.4rem;
                color: #fff;
                padding: 0px 10px;
                line-height: .7rem;
                border-bottom: 1px solid white;
                &.active {
                    border-bottom: 1px solid red;
                }
            }
            i {
                font-size: 1rem;
                color: #fff;
            }
        }
    }
}
</style>