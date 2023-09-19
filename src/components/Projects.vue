<template>
    <div class="project" id="project">
        <div class="container">
            <div class="project-items">
                <h2>Recent projects</h2>
                <div class="project-cards">
                    <div class="project-card">
                        <img src="../assets/images/IMAGE2.png" alt="project1" />
                        <div class="project-card-body">
                            <h3>woods</h3>
                            <p>Photography</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img src="../assets/images/IMAGE3.png" alt="project2" />
                        <div class="project-card-body">
                            <h3>path</h3>
                            <p>path</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img src="../assets/images/IMAGE4.png" alt="project3" />
                        <div class="project-card-body">
                            <h3>darkness</h3>
                            <p>Website</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img src="../assets/images/IMAGE5.png" alt="project4" />
                        <div class="project-card-body">
                            <h3>waves</h3>
                            <p>Photography</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img src="../assets/images/IMAGE6.png" alt="project5" />
                        <div class="project-card-body">
                            <h3>drops</h3>
                            <p>Website</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img src="../assets/images/IMAGE7.png" alt="project6" />
                        <div class="project-card-body">
                            <h3>ocean</h3>
                            <p>Website</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img src="../assets/images/IMAGE8.png" alt="project7" />
                        <div class="project-card-body">
                            <h3>town</h3>
                            <p>Website</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img src="../assets/images/IMAGE9.png" alt="project8" />
                        <div class="project-card-body">
                            <h3>mountain</h3>
                            <p>Website</p>
                        </div>
                    </div>
                    <div class="project-card">
                        <img
                            src="../assets/images/IMAGE10.png"
                            alt="project9"
                        />
                        <div class="project-card-body">
                            <h3>camera</h3>
                            <p>Website</p>
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

.project {
    width: 100%;
    padding: 70px;
    display: flex;
    justify-content: center;
    background: #f5f5f5;
}
.project-items {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 28px;
    h2 {
        color: #333;
        text-align: center;
        font-family: "Montserrat", sans-serif;
        font-size: 23px;
        font-style: normal;
        font-weight: 400;
        line-height: 36px; /* 156.522% */
        text-transform: uppercase;
    }
}
.project-cards {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
}
.project-card {
    width: calc(33% - 11px);
    display: flex;
    flex-direction: column;
    overflow: hidden;
    transition: all 0.3s linear;
    div {
        width: 100%;
        height: 80px;
    }
    img {
        width: 100%;
        object-fit: cover;
    }
    &:hover {
        transform: scale(0.9);
    }
}
.project-card-body {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-top: 20px;
    padding-bottom: 20px;
    background: #fff;
    h3 {
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
@media (max-width: 992px) {
    .project-card {
        width: calc(33% - 12px);
    }
}
@media (max-width: 776px) {
    .project-card {
        width: calc(50% - 11px);
        margin: 0 auto;
    }
}
@media (max-width: 567px) {
    .project {
        padding: 0px;
        padding-top: 40px;
    }
    .project-card {
        width: 80%;
        margin: 0 auto;
    }
    .project-cards {
        margin-bottom: 40px;
    }
}
</style>
