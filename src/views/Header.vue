<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
        integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <div class="top">
        <div class="topbox logo">
            <i class="fa-solid fa-book fa-spin"></i>
        </div>
        <div class="topbox title">
            <h1>人豪的選課系統</h1>
        </div>
        <div class="topbox personinfo">
            <div class="infoText">
                <span id="infoShow">請登入會員</span>
            </div>
            <div class="infoBtn">
                <button type="button" id="logInBtn">登入</button>
                <button type="button" id="signBtn">註冊</button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.top {
    width: 100%;
    height: 20vh;
    display: flex;
    
    .topbox{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
    }

    .logo {
        width: 20%;
        font-size: 42pt;
    }

    .title {
        width: 60%;
        
    }

    .personinfo {
        width: 20%;
        flex-direction: column;

        .infoText{
            margin-bottom: 2px;
        }
        .infoBtn{
            button{
                width: 3rem;
                height: 2rem;
                font-size: 8pt;
                border: 0;
                background-color: #555;
                color: white;
                margin: 5px;
                border-radius: 5pt;
                transition: 0.6s;
                &:hover{
                    font-size: 16pt;
                    height: 5rem;
                    background-color: white;
                    color: black;
                    border: 1px solid black;
                }
                &:active{
                    transition: 0.01s;
                    font-size: 20pt;
                }
            }
        }
    }
}
</style>

