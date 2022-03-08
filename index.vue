<template>
    <div>
        <div class="offers-hero">
            <h3 class="main-heading-title text-white text-center text-6xl pt-48 md:pt-56 lg:pt-72 xl:pt-72 2xl:pt-72">
                Cysuites Travels</h3>
        </div>
        <div class="container-details 2xl:container 2xl:mx-auto">
            <div class="details sm:mx-3.5 mx-3.5 md:mx-5 lg:mx-60 xl:mx-60 2xl:mx-60">
                <h3 class="section-heading-title sm:text-3xl text-3xl md:text-4xl lg:text-4xl xl:text-4xl 2xl:text-4xl">
                    CySuites Travelss</h3>
                <p class="heading-description text-accent-color">
                    Our Cysuites Travels promises to deliver. From the pick, to touring of the destination, CySuites Travels will ensure a quality safari experience for you and yours. 
                </p>
                <div class="grid gap-y-12">
                    <div class="flex flex-wrap offers-section">
                        <div class="sm:w-full lg:pr-6 w-full md:w-2/5 lg:w-2/5 xl:w-2/5 2xl:w-2/5 image-card">
                            <img class="sm:w-full w-full" src=" " alt="">
                        </div>
                        <div class="sm:w-full md:pl-6 w-full md:w-3/5 lg:w-3/5 xl:w-3/5 2xl:w-3/5 description">
                            <h4 class="leading-4 text-xl sm:leading-4 sm:text-xl md:text-2xl lg:text-3xl xl:text-3xl 2xl:text-3xl">
                                The Nairobi National Park</h4>
                            <p class="best-for">Enjoy a tour into the natural safari trail by the park</p>
                            <p class="content">
                                This starts from <b>$250</b> per person
                            </p>
                            <div class="flex justify-between contact">
                                <div class="phone-detailS">
                                    <h5 class="text-base sm:text-base lg:text-2xl xl:text-2xl 2xl:text-2xl">Call us
                                        on</h5>
                                    <p class="phone md:text-lg lg:text-lg xl:text-lg 2xl:text-lg">
                                        +254(0) 712 101 222
                                    </p>
                                    <p class="text-base">
                                        to start planning your tour
                                    </p>
                                </div>
                                <div class="enquire">
                                    <button @click="$router.push({name:'contact'})"
                                            class="lg:p-3.5 xl:p-3.5 2xl:p-3.5 p-1 sm:p-1 text-xs sm:text-xs lg-w-48 md:w-48 xl:w-48 2xl:w-48">
                                        ENQUIRE
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-wrap offers-section">
                        <div class="sm:w-full lg:pr-6 w-full md:w-2/5 lg:w-2/5 xl:w-2/5 2xl:w-2/5 image-card">
                            <img class="sm:w-full w-full" src=" " alt="">
                        </div>
                        <div class="sm:w-full md:pl-6 w-full md:w-3/5 lg:w-3/5 xl:w-3/5 2xl:w-3/5 description">
                            <h4 class="sm:leading-4 leading-4 sm:text-xl text-xl md:text-2xl lg:text-3xl xl:text-3xl 2xl:text-3xl">
                                Lamu Island</h4>
                            <p class="best-for">Enjoy a tour off the mainland </p>
                            <p class="content">
                                Travel into the Indian Ocean, enjoy great scenery and views of the Island and Lamu Island musuem. Take a boat ride off to the ocean and ride on donkeys.
                            </p>
                            <div class="flex justify-between contact">
                                <div class="phone-detailS">
                                    <h5 class="sm:text-base text-base lg:text-2xl xl:text-2xl 2xl:text-2xl">Call us
                                        on</h5>
                                    <p class="phone md:text-lg lg:text-lg xl:text-lg 2xl:text-lg">
                                        +254(0) 712 101 222
                                    </p>
                                    <p class="text-base">
                                        to start planning your tour
                                    </p>
                                </div>
                                <div class="enquire">
                                    <button @click="$router.push({name:'contact'})"
                                            class="lg:p-3.5 xl:p-3.5 2xl:p-3.5 sm:p-1 p-1 sm:text-xs text-xs lg-w-48 md:w-48 xl:w-48 2xl:w-48">
                                        ENQUIRE
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-wrap offers-section">
                        <div class="sm:w-full lg:pr-6 w-full md:w-2/5 lg:w-2/5 xl:w-2/5 2xl:w-2/5 image-card">
                            <img class="sm:w-full w-full" src=" " alt="">
                        </div>
                        <div class="sm:w-full md:pl-6 w-full md:w-3/5 lg:w-3/5 xl:w-3/5 2xl:w-3/5 description">
                            <h4 class="sm:leading-4 leading-4 sm:text-xl text-xl md:text-2xl lg:text-3xl xl:text-3xl 2xl:text-3xl">
                                Maasai Mara Safari</h4>
                            <p class="best-for">Enter the wild Mara Experience</p>
                            <p class="content">
                                Maasai Mara Safari Park offers you top of the deck game drives,enjoy the vibrant maasai culture, soak into the Acacia grasslands and enjoy migrating wildebeests too.
                            </p>
                            <div class="flex justify-between contact">
                                <div class="phone-detailS">
                                    <h5 class="sm:text-base text-base lg:text-2xl xl:text-2xl 2xl:text-2xl">Call us
                                        on</h5>
                                    <p class="phone md:text-lg lg:text-lg xl:text-lg 2xl:text-lg">
                                        +254(0) 712 101 222
                                    </p>
                                    <p class="text-base">
                                        to get started on your tour
                                    </p>
                                </div>
                                <div class="enquire">
                                    <button @click="$router.push({name:'contact'})"
                                            class="lg:p-3.5 xl:p-3.5 2xl:p-3.5 sm:p-1 p-1 sm:text-xs text-xs lg-w-48 md:w-48 xl:w-48 2xl:w-48">
                                        ENQUIRE
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-wrap offers-section">
                        <div class="sm:w-full lg:pr-6 w-full md:w-2/5 lg:w-2/5 xl:w-2/5 2xl:w-2/5 image-card">
                            <img class="sm:w-full w-full" src=" " alt="">
                        </div>
                        <div class="sm:w-full md:pl-6 w-full md:w-3/5 lg:w-3/5 xl:w-3/5 2xl:w-3/5 description">
                            <h4 class="sm:leading-4 leading-4 sm:text-xl text-xl md:text-2xl lg:text-3xl xl:text-3xl 2xl:text-3xl">
                                Gala Events</h4>
                            <p class="best-for">Best for: Conference, Meetings</p>
                            <p class="content">
                                Sit back while we create a gala event of a lifetime for you
                            </p>
                            <div class="flex justify-between contact">
                                <div class="phone-detailS">
                                    <h5 class="sm:text-base text-base lg:text-2xl xl:text-2xl 2xl:text-2xl">Call us
                                        on</h5>
                                    <p class="phone md:text-lg lg:text-lg xl:text-lg 2xl:text-lg">
                                        +254(0) 712 101 222
                                    </p>
                                    <p class="text-base">
                                        to start planning your holiday
                                    </p>
                                </div>
                                <div class="enquire">
                                    <button @click="$router.push({name:'contact'})"
                                            class="lg:p-3.5 xl:p-3.5 2xl:p-3.5 sm:p-1 p-1 sm:text-xs text-xs lg-w-48 md:w-48 xl:w-48 2xl:w-48">
                                        ENQUIRE
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "index"
    }
</script>

<style scoped lang="scss">
    .offers-hero {
        background: url('');
        background-size: cover;
        height: 660px;
    }

    .container-details {
        margin-top: 40px;

        .details {
            h3 {
                text-align: center;
            }

            .heading-description {
                text-align: center;
                margin-top: 35px;
                font-size: 15px;
                line-height: 1.8rem;
                color: #4c4b4b;
            }

            .offers-section {
                /*display: flex;*/
                /*flex-flow: row wrap;*/
                margin-top: 65px;
                /*width: 80%;*/

                h4 {
                    color: #046b5c;
                    font-family: "Merriweather", sans-serif;
                    font-size: 30px;
                    font-style: normal;
                    letter-spacing: normal;
                    line-height: normal;
                    text-align: left;
                }

                .content {
                    padding-top: 8px;
                    color: #575757;
                    font-family: "Proxima Nova Lt", sans-serif;
                    font-size: 17px;
                    font-weight: 600;
                    font-style: normal;
                    letter-spacing: normal;
                    line-height: 27px;
                    text-align: left;
                }

                .best-for {
                    color: #6a6969;
                    font-family: "Proxima Nova", sans-serif;
                    font-size: 18px;
                    font-weight: 500;
                    font-style: normal;
                    letter-spacing: normal;
                    line-height: 18px;
                    text-align: left;
                    display: none;
                }

                .image-card {
                    height: 285px;

                    img {
                        height: inherit;
                    }
                }

                .description {
                    .contact {
                        /*padding-top: 19px;*/

                        .phone-detailS {
                            .phone {
                                font-weight: 600;
                            }

                            h5 {
                                color: #fbad2f;
                            }

                            p {
                                line-height: 0.45;
                            }
                        }

                        .enquire {
                            display: flex;
                            align-items: center;

                            button {
                                background-color: #fbad2f;
                                color: #ffffff;
                                font-family: "Proxima Nova", sans-serif;
                                font-size: 15px;
                                font-weight: 500;
                                font-style: normal;
                                letter-spacing: normal;
                                line-height: normal;
                                text-align: center;
                                text-transform: uppercase;
                            }
                        }
                    }
                }
            }
        }
    }
</style>
