<template>
    <div class="team" id="team">
        <div class="container">
            <div class="team-items">
                <h2 class="team-items-title">our team</h2>
                <div class="team-cards">
                    <div class="team-card">
                        <img src="../assets/images/IMAGE11.png" alt="team1" />
                        <div class="team-card-body">
                            <h2>Ron Swanson</h2>
                            <p>Founder</p>
                            <p class="team-socials"></p>
                        </div>
                    </div>
                    <div class="team-card">
                        <img src="../assets/images/IMAGE13.png" alt="team2" />
                        <div class="team-card-body">
                            <h2>Julia Depish</h2>
                            <p>Marketing</p>
                            <p class="team-socials"></p>
                        </div>
                    </div>
                    <div class="team-card">
                        <img src="../assets/images/IMAGE14.png" alt="team3" />
                        <div class="team-card-body">
                            <h2>Danny Devry</h2>
                            <p>Designer</p>
                            <p class="team-socials"></p>
                        </div>
                    </div>
                    <div class="team-card">
                        <img src="../assets/images/IMAGE12.png" alt="team4" />
                        <div class="team-card-body">
                            <h2>Lisa Smith</h2>
                            <p>Developer</p>
                            <p class="team-socials"></p>
                        </div>
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
.team {
    width: 100%;
    padding: 70px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.team-items {
    width: 100%;
    padding: 10px 0px;
    display: flex;
    flex-direction: column;
}
.team-items-title {
    color: #333;
    text-align: center;
    font-family: "Montserrat", sans-serif;
    font-size: 23px;
    font-style: normal;
    font-weight: 400;
    line-height: 36px; /* 156.522% */
    text-transform: uppercase;
}
.team-cards {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 45px;
}
.team-card {
    width: calc(25% - 15px);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    transition: all 0.3s linear;
    img {
        width: 100%;
        object-fit: cover;
    }
}
.team-card:hover {
    transform: scale(0.9);
}
.team-card-body {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 6px;
    margin-top: 20px;
    h2 {
        color: #333;
        text-align: center;
        font-family: "Montserrat", sans-serif;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; /* 125% */
        text-transform: uppercase;
    }
    p {
        color: #333;
        text-align: center;
        font-family: "Vollkorn", serif;
        font-size: 14px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; /* 142.857% */
    }
}
.team-socials {
    width: 100%;
    margin: 10px auto 0px;
    display: flex;
    gap: 20px;
    font-size: 14px;
    justify-content: center;
    margin-bottom: 10px;
}

@media (max-width: 776px) {
    .team-card {
        width: calc(50% - 10px);
    }
}
@media (max-width: 567px) {
    .team-card {
        width: 90%;
        margin: 0px auto;
    }
}
</style>
