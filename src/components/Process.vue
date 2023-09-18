<template>
    <div class="process" id="process">
        <div class="container">
            <div class="process-items">
                <div class="process-title">
                    <h2>How we make brands thrive</h2>
                </div>
                <div class="process-cards">
                    <div class="process-card">
                        <div class="process-card-img">
                            <img
                                src="../assets/images/ICON11.png"
                                alt="process1"
                            />
                        </div>
                        <div class="process-card-title">
                            <h2>SET a target</h2>
                        </div>
                        <div class="process-card-desc">
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit. Suspendisse varius enim in eros
                                elementum tristique.
                            </p>
                        </div>
                    </div>
                    <div class="process-card">
                        <div class="process-card-img">
                            <img
                                src="../assets/images/ICON22.png"
                                alt="process2"
                            />
                        </div>
                        <div class="process-card-title">
                            <h2>design a solution</h2>
                        </div>
                        <div class="process-card-desc">
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit. Suspendisse varius enim in eros
                                elementum tristique.
                            </p>
                        </div>
                    </div>
                    <div class="process-card">
                        <div class="process-card-img">
                            <img
                                src="../assets/images/ICON33.png"
                                alt="process3"
                            />
                        </div>
                        <div class="process-card-title">
                            <h2>track the progress</h2>
                        </div>
                        <div class="process-card-desc">
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit. Suspendisse varius enim in eros
                                elementum tristique.
                            </p>
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
    // border: 1px solid red;
}
.process {
    width: 100%;
    height: 600px;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 0px;
    margin-top: 100px;
}
.process-items {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    padding: 10px;
}
.process-title H2 {
    color: #333;
    text-align: center;
    font-family: "Montserrat", sans-serif;
    font-size: 23px;
    font-style: normal;
    font-weight: 400;
    line-height: 36px; /* 156.522% */
    text-transform: uppercase;
}
.process-cards {
    width: 100%;
    height: 368px;
    display: flex;
    flex-wrap: wrap;
    margin-top: 40px;
    gap: 20px;
}
.process-card {
    width: calc(33% - 11px);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding-bottom: 5px;
    transition: all 0.3s linear;
}

.process-card:hover {
    transform: scale(0.9);
}
.process-card-img {
    width: 100%;
    height: 60%;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #f5f5f5;
    img {
        width: 127px;
        height: 119px;
    }
}
.process-card-title h2 {
    color: #333;
    text-align: center;
    font-family: "Montserrat", sans-serif;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px; /* 125% */
    text-transform: uppercase;
    margin-top: 18px;
}
.process-card-desc p {
    color: #333;
    text-align: center;
    font-family: "Vollkorn", serif;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 22px; /* 146.667% */
}
@media (max-width: 992px) {
    .process-card {
        width: calc(33% - 12px);
    }
}
@media (max-width: 776px) {
    .process {
        height: 1000px;
    }
    .process-cards {
        height: 800px;
    }
    .process-card {
        width: calc(50% - 11px);
        margin: 0 auto;
    }
}
@media (max-width: 567px) {
    .process {
        height: 1400px;
    }
    .process-cards {
        height: 1200px;
        gap: 40px;
    }
    .process-card {
        width: 90%;
        margin: 0 auto;
    }
}
</style>
