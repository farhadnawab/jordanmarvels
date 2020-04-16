<template>
    <b-modal id="login-signup-popup" content-class="login-signup-popup" hide-footer size="lg">
        <b-tabs>
            <b-tab title="Login">
                <b-form id="login-form">

                    <b-container class="mt-4">
                    <b-row>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-prepend">
                                    <b-input
                                    type="email"
                                    required
                                    placeholder="E-mail"
                                    ></b-input>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="20.583" height="16.25" viewBox="0 0 20.583 16.25">
                                              <path id="Path_413" data-name="Path 413" d="M289.417,266.417H303.5a3.25,3.25,0,0,1,3.25,3.25v9.75a3.25,3.25,0,0,1-3.25,3.25H289.417a3.249,3.249,0,0,1-3.25-3.25v-9.75a3.249,3.249,0,0,1,3.25-3.25Zm0,1.083a2.158,2.158,0,0,0-1.39.505l8.431,5.475,8.432-5.475a2.162,2.162,0,0,0-1.39-.505Zm7.041,7.272-9.063-5.885a2.167,2.167,0,0,0-.145.78v9.75a2.166,2.166,0,0,0,2.167,2.167H303.5a2.168,2.168,0,0,0,2.167-2.167v-9.75a2.129,2.129,0,0,0-.146-.78l-9.063,5.884Z" transform="translate(-286.167 -266.417)" fill="#50473d"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <div class="w-100"></div>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-prepend icon-append">
                                    <b-input
                                    type="password"
                                    required
                                    placeholder="Password"
                                    ></b-input>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="16.25" height="21.667" viewBox="0 0 16.25 21.667">
                                            <path id="Path_410" data-name="Path 410" d="M300.333,336.667a3.249,3.249,0,0,1,3.25,3.25v8.667a3.249,3.249,0,0,1-3.25,3.25h-9.75a3.25,3.25,0,0,1-3.25-3.25v-8.667a3.25,3.25,0,0,1,3.25-3.25v-1.625a4.875,4.875,0,1,1,9.75,0Zm-9.75,1.083a2.166,2.166,0,0,0-2.166,2.167v8.667a2.165,2.165,0,0,0,2.166,2.166h9.75a2.165,2.165,0,0,0,2.167-2.166v-8.667a2.166,2.166,0,0,0-2.167-2.167Zm8.667-1.083v-1.625a3.792,3.792,0,1,0-7.583,0v1.625Zm-3.792,6.5a1.623,1.623,0,1,0,1.15.476A1.626,1.626,0,0,0,295.458,343.167Zm0-1.083a2.707,2.707,0,1,1-1.915.793A2.709,2.709,0,0,1,295.458,342.084Z" transform="translate(-287.333 -330.167)" fill="rgba(80,71,61,0.89)"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                    <b-input-group-append>
                                        <span class="input-group-text"><img src="@/assets/images/password_eye.svg" /></span>
                                    </b-input-group-append>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <div class="w-100"></div>
                        <b-col>
                            <b-form-group class="text-right mt-n2">
                                <a href="javascript:void(0)" class="font-weight-light small">Forgot your Password?</a>
                            </b-form-group>
                        </b-col>
                    </b-row>

                    <v-row class="justify-content-center d-flex py-4">
                        <b-button type="submit" variant="secondary">Login</b-button>
                    </v-row>
                    </b-container>

                    <div class="title-2 text-center">
                        <span>Or Login Using</span>
                    </div>

                    <b-container class="justify-content-around d-flex">
                        <b-button variant="default" class="facebook-signup my-2"><img src="@/assets/images/facebook-signup.svg" /> Login with Facebook</b-button>

                        <b-button variant="default" class="google-signup my-2"><img src="@/assets/images/google-signup.svg" /> Login with Google</b-button>
                    </b-container>
                </b-form>
            </b-tab>
            <b-tab title="Signup" active>
                <b-form id="signup-form">
                    
                    <b-container class="mt-4">
                    <b-row>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-prepend">
                                    <b-input
                                    type="text"
                                    required
                                    placeholder="First Name"
                                    ></b-input>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="17.5" height="17.5" viewBox="0 0 17.5 17.5">
                                                <path id="Path_416" data-name="Path 416" d="M296.417,206.333c4.832,0,8.75,1.828,8.75,4.083v2.917h-17.5v-2.917C287.667,208.161,291.584,206.333,296.417,206.333ZM304,210.416c0-1.61-3.395-2.916-7.583-2.916s-7.584,1.306-7.584,2.916v1.75H304Zm-7.583-14.583a4.083,4.083,0,1,1-2.888,1.2A4.084,4.084,0,0,1,296.417,195.833Zm0,1.167a2.916,2.916,0,1,0,2.062.854A2.917,2.917,0,0,0,296.417,197Z" transform="translate(-287.667 -195.833)" fill="#c7b299"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-prepend">
                                    <b-input
                                    type="text"
                                    required
                                    placeholder="Last Name"
                                    ></b-input>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="17.5" height="17.5" viewBox="0 0 17.5 17.5">
                                                <path id="Path_416" data-name="Path 416" d="M296.417,206.333c4.832,0,8.75,1.828,8.75,4.083v2.917h-17.5v-2.917C287.667,208.161,291.584,206.333,296.417,206.333ZM304,210.416c0-1.61-3.395-2.916-7.583-2.916s-7.584,1.306-7.584,2.916v1.75H304Zm-7.583-14.583a4.083,4.083,0,1,1-2.888,1.2A4.084,4.084,0,0,1,296.417,195.833Zm0,1.167a2.916,2.916,0,1,0,2.062.854A2.917,2.917,0,0,0,296.417,197Z" transform="translate(-287.667 -195.833)" fill="#c7b299"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <div class="w-100"></div>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-prepend">
                                    <b-input
                                    type="email"
                                    required
                                    placeholder="E-mail"
                                    ></b-input>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="20.583" height="16.25" viewBox="0 0 20.583 16.25">
                                              <path id="Path_413" data-name="Path 413" d="M289.417,266.417H303.5a3.25,3.25,0,0,1,3.25,3.25v9.75a3.25,3.25,0,0,1-3.25,3.25H289.417a3.249,3.249,0,0,1-3.25-3.25v-9.75a3.249,3.249,0,0,1,3.25-3.25Zm0,1.083a2.158,2.158,0,0,0-1.39.505l8.431,5.475,8.432-5.475a2.162,2.162,0,0,0-1.39-.505Zm7.041,7.272-9.063-5.885a2.167,2.167,0,0,0-.145.78v9.75a2.166,2.166,0,0,0,2.167,2.167H303.5a2.168,2.168,0,0,0,2.167-2.167v-9.75a2.129,2.129,0,0,0-.146-.78l-9.063,5.884Z" transform="translate(-286.167 -266.417)" fill="#50473d"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <div class="w-100"></div>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-prepend icon-append">
                                    <b-input
                                    type="password"
                                    required
                                    placeholder="Password"
                                    ></b-input>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="16.25" height="21.667" viewBox="0 0 16.25 21.667">
                                            <path id="Path_410" data-name="Path 410" d="M300.333,336.667a3.249,3.249,0,0,1,3.25,3.25v8.667a3.249,3.249,0,0,1-3.25,3.25h-9.75a3.25,3.25,0,0,1-3.25-3.25v-8.667a3.25,3.25,0,0,1,3.25-3.25v-1.625a4.875,4.875,0,1,1,9.75,0Zm-9.75,1.083a2.166,2.166,0,0,0-2.166,2.167v8.667a2.165,2.165,0,0,0,2.166,2.166h9.75a2.165,2.165,0,0,0,2.167-2.166v-8.667a2.166,2.166,0,0,0-2.167-2.167Zm8.667-1.083v-1.625a3.792,3.792,0,1,0-7.583,0v1.625Zm-3.792,6.5a1.623,1.623,0,1,0,1.15.476A1.626,1.626,0,0,0,295.458,343.167Zm0-1.083a2.707,2.707,0,1,1-1.915.793A2.709,2.709,0,0,1,295.458,342.084Z" transform="translate(-287.333 -330.167)" fill="rgba(80,71,61,0.89)"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                    <b-input-group-append>
                                        <span class="input-group-text"><img src="@/assets/images/password_eye.svg" /></span>
                                    </b-input-group-append>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <div class="w-100"></div>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-prepend icon-append">
                                    <b-input
                                    type="password"
                                    required
                                    placeholder="Confirm your Password"
                                    ></b-input>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="16.25" height="21.667" viewBox="0 0 16.25 21.667">
                                            <path id="Path_410" data-name="Path 410" d="M300.333,336.667a3.249,3.249,0,0,1,3.25,3.25v8.667a3.249,3.249,0,0,1-3.25,3.25h-9.75a3.25,3.25,0,0,1-3.25-3.25v-8.667a3.25,3.25,0,0,1,3.25-3.25v-1.625a4.875,4.875,0,1,1,9.75,0Zm-9.75,1.083a2.166,2.166,0,0,0-2.166,2.167v8.667a2.165,2.165,0,0,0,2.166,2.166h9.75a2.165,2.165,0,0,0,2.167-2.166v-8.667a2.166,2.166,0,0,0-2.167-2.167Zm8.667-1.083v-1.625a3.792,3.792,0,1,0-7.583,0v1.625Zm-3.792,6.5a1.623,1.623,0,1,0,1.15.476A1.626,1.626,0,0,0,295.458,343.167Zm0-1.083a2.707,2.707,0,1,1-1.915.793A2.709,2.709,0,0,1,295.458,342.084Z" transform="translate(-287.333 -330.167)" fill="rgba(80,71,61,0.89)"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                    <b-input-group-append>
                                        <span class="input-group-text"><img src="@/assets/images/password_eye.svg" /></span>
                                    </b-input-group-append>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <div class="w-100"></div>
                        <b-col>
                            <b-form-group>
                                <b-input-group class="icon-append">
                                    <b-form-datepicker></b-form-datepicker>
                                    <b-input-group-prepend>
                                        <span class="input-group-text">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="19.833" height="22.167" viewBox="0 0 19.833 22.167">
                                            <path id="Path_402" data-name="Path 402" d="M290.167,467.333h1.166A1.168,1.168,0,0,1,292.5,468.5v1.166h5.833V468.5a1.168,1.168,0,0,1,1.167-1.167h1.167a1.166,1.166,0,0,1,1.166,1.167v1.166a3.5,3.5,0,0,1,3.5,3.5V486a3.5,3.5,0,0,1-3.5,3.5H289a3.5,3.5,0,0,1-3.5-3.5V473.166a3.5,3.5,0,0,1,3.5-3.5V468.5a1.168,1.168,0,0,1,1.167-1.167Zm9.333,2.333h1.167V468.5H299.5Zm-8.167,0V468.5h-1.166v1.166ZM289,470.833a2.332,2.332,0,0,0-2.333,2.333v1.167h17.5v-1.167a2.334,2.334,0,0,0-2.334-2.333ZM286.667,486A2.332,2.332,0,0,0,289,488.333h12.833A2.334,2.334,0,0,0,304.167,486V475.5h-17.5ZM296,480.166h5.833V486H296Zm1.167,1.167v3.5h3.5v-3.5Z" transform="translate(-285.5 -467.333)" fill="#c7b299"/>
                                            </svg>
                                        </span>
                                    </b-input-group-prepend>
                                    <b-input-group-append>
                                        <span class="input-group-text">DD/MM/YYYY</span>
                                    </b-input-group-append>
                                </b-input-group>
                            </b-form-group>
                        </b-col>
                        <div class="w-100"></div>
                        <b-col class="mt-2">
                            <b-form-group>
                                <b-form-checkbox class="text-uppercase">I agree to the terms and conditions</b-form-checkbox>
                            </b-form-group>
                        </b-col>
                    </b-row>

                    <v-row class="justify-content-center d-flex py-4">
                        <b-button type="submit" variant="secondary">Sign Up</b-button>
                    </v-row>
                    </b-container>

                    <div class="title-2 text-center">
                        <span>Or Sign Up Using</span>
                    </div>

                    <b-container class="justify-content-around d-flex">
                        <b-button variant="default" class="facebook-signup my-2"><img src="@/assets/images/facebook-signup.svg" /> SignUp with Facebook</b-button>

                        <b-button variant="default" class="google-signup my-2"><img src="@/assets/images/google-signup.svg" /> SignUp with Google</b-button>
                    </b-container>
                </b-form>
            </b-tab>
        </b-tabs>
    </b-modal>
</template>
<script>
  export default {
    name: "LoginSignupPopup"
  }
</script>
<style lang="scss">

.login-signup-popup{

    > header {
        border: 0;
        padding: 0;
        margin: 0;
    }
    .modal-body {
        padding: 0;
    }
    .tabs .nav-tabs {
        border: 1px solid #c4c4c4;
        justify-content: center;
        flex-wrap: nowrap;
        text-align: center;
    }
    .tabs .nav-tabs > li {
        flex-grow: 1;
    }
    .tabs .nav-tabs > li > a {
        font-size: 28px;
        font-weight: bold;
        padding-top: 15px;
        padding-bottom: 15px;
        border: 0;
        border-bottom: 3px solid transparent;
        color: var(--seventh);
        outline: none;
    }
    .tabs .nav-tabs > li > a.active {
        border-color: var(--secondary);
        color: var(--tertiary);
    }
    .tab-content {
        padding: 25px;

        a{color: var(--seventh);}
        .title-2 {
            margin: 25px -25px;
            color: var(--seventh);

            &:after{border-color: var(--seventh);}
        }
        .container{
            max-width: 545px;
            margin-left: auto;
            margin-left: auto;
        }
        .custom-checkbox{
            color: var(--seventh);
            font-size: 13px;
            line-height: 1.8;
        }
    }
} 


</style>