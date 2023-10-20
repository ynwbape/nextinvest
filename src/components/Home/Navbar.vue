<script setup>

</script>

<template>
    <header>
        <nav>
            <div class="logo">
                <a href="#">NEXT INVEST</a>
            </div>
            <div class="linksLogin">
                <a href="#" class="links">
                    Investement Opportunities
                    <svg width="12" height="7" viewBox="0 0 12 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M11 1L6 6L1 1" stroke="#333333" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </a>
                <a href="#" class="links">
                    How it works
                    <svg width="12" height="7" viewBox="0 0 12 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M11 1L6 6L1 1" stroke="#333333" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </a>
                <a href="#" class="links">Abous us</a>
                <a href="#" class="loginBtn">LOGIN</a>
                <a href="#" class="registerBtn">REGISTER</a>
            </div>
        </nav>
    </header>
</template>

<style scoped>
    header {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 90px;
    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 1170px;
    }

    .logo {
        width: 161px;
    }

    .logo > a, .logo > a:visited {
        color: #128C76;
        font-size: 2.4rem;
        font-weight: bold;
        text-decoration: none;
    }

    .logo > a:hover {
        color: #0f7967;
    }

    .logo > a:active {
        color: #0c5c4f;
    }

    .linksLogin {
        display: flex;
        align-items: center;
        gap: 1.6rem;
    }

    .links {
        font-size: 1.6rem;
        color: #333333;
        font-weight: bold;
        text-decoration: none;
    }

    .links:nth-child(3) {
        margin-right: 8px;
    }

    .links:visited {
        text-decoration: none;
    }

    .loginBtn {
        display: block;
        padding: 17px 40px;
        text-align: center;
        width: 135px;
        height: 54px;
        background-color: #128C76;
        color: #FFFFFF;
        font-size: 1.6rem;
        font-weight: bold;
        text-decoration: none;
    }

    .registerBtn {
        display: block;
        padding: 16px 40px;
        text-align: center;
        width: 160px;
        height: 54px;
        border: 1px solid #F56B8D;
        color: #F56B8D;
        font-size: 1.6rem;
        font-weight: bold;
        text-decoration: none;
    }

    .loginBtn, .registerBtn {
        overflow: hidden;
    }

    .loginBtn:visited, .registerBtn:visited {
        text-decoration: none;
    }
</style>