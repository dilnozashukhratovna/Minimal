<template>
    <div class="contact" id="contact">
        <div class="container">
            <div class="contact-items">
                <h2 class="contact-items-title">LET’s Get in touch</h2>
                <div class="contact-cards">
                    <div class="contact-card">
                        <img
                            src="../assets/images/icon1.png"
                            alt="location-logo"
                        />
                        <h2>MEET US IN PERSON</h2>
                        <p>
                            8776 Juniper Street<br />Unit #204<br />Merriweather,
                            Ontorio<br />Canada
                        </p>
                    </div>
                    <div class="contact-card">
                        <img
                            src="../assets/images/icon2.png"
                            alt="message-logo"
                        />

                        <h2>The traditional way</h2>
                        <p>
                            Email us<br />contact@minimal.com<br />Contact
                            form<br />Scrolldown
                        </p>
                    </div>
                    <div class="contact-card">
                        <img
                            src="../assets/images/icon3.png"
                            alt="heart-logo"
                        />
                        <h2>Let’s get social</h2>
                        <p class="contact-socials">
                            <span>
                                <span>Facebook</span>
                            </span>
                            <span>
                                <span>Twitter</span>
                            </span>
                            <span>
                                <span>Linkedin</span>
                            </span>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Oswald&family=Vollkorn&display=swap");
.container {
    width: 940px;
}
.contact {
    width: 100%;
    padding: 70px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url("../assets/images/contact.png");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}
.contact-items {
    width: 100%;
    padding: 10px 0px;
    display: flex;
    flex-direction: column;
}
.contact-items-title {
    color: #333;
    text-align: center;
    font-family: "Montserrat", sans-serif;
    font-size: 23px;
    font-style: normal;
    font-weight: 400;
    line-height: 36px; /* 156.522% */
    text-transform: uppercase;
}
.contact-cards {
    width: 100%;
    display: flex;
    gap: 20px;
    margin-top: 45px;
}
.contact-card {
    width: 33%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    img {
        object-fit: cover;
    }
    h2 {
        color: #333;
        text-align: center;
        font-family: "Montserrat", sans-serif;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; /* 125% */
        text-transform: uppercase;
        margin-top: 26px;
    }
    p {
        color: #212121;
        text-align: center;
        font-family: "Vollkorn", serif;
        font-size: 17px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 129.412% */
        margin-top: 20px;
    }
}

.contact-socials {
    width: 100%;
    margin: 10px auto 0px;
    display: flex;
    flex-direction: column;
    gap: 11px;
    color: #212121;
    font-family: "Vollkorn", serif;
    font-size: 17px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px; /* 117.647% */
    justify-content: center;
    margin-bottom: 10px;
    span {
        display: flex;
        align-items: center;
        justify-content: center;
    }
}

@media (max-width: 776px) {
    .contact-cards {
        flex-direction: column;
        align-items: center;
        gap: 30px;
    }
    .contact-card {
        width: 80%;
    }
}
</style>
