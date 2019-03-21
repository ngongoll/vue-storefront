<template>
  <footer :class="{ 'brdr-top-1 brdr-cl-secondary': isCheckoutPage }">
    <newsletter class=" flex brdr-bottom-1 brdr-cl-secondary" v-if="!isCheckoutPage"/>
    <div
      class="footer-links flex pt30 pb60 px40 bg-cl-secondary"
      v-if="!isCheckoutPage"
    >
      <div class="container">
        <div class="row m0 center-xs between-md">
          <div
            class="row m0 col-lg-7 col-md-8 col-xs-12 start-md between-md between-xs no-mobile"
          >
            <div class="start-md">
              <h3 class="cl-accent weight-400">
                {{ $t('Über uns') }}
              </h3>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/contacts')" exact>
                  {{ $t('Kontakt') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/zahlung')" exact>
                  {{ $t("Zahlungsbedingungen") }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/agb')" exact>
                  {{ $t('AGB') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/datenschutz')" exact>
                  {{ $t('Datenschutz') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/impressum')" exact>
                  {{ $t("Impressum") }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/widerruf')" exact>
                  {{ $t('Widerrufsbelehrung') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/lieferung')" exact>
                  {{ $t('Versandinformationen') }}
                </router-link>
              </div>
              <h3 class="cl-accent weight-400">
                {{ $t('Kontakt') }}
              </h3>
              <div class="mt15">
                Tel.: &nbsp; &nbsp;<a href="tel:03329 4 39 86 32">&nbsp;+49 (0) 3329 4 39 86 32</a>
              </div>
              <div class="mt15">
                Email:&nbsp;<a href="mailto:info@hochzeitstrauringe.de">info@hochzeitstrauringe.de</a>
              </div>
            </div>
            <div class="start-md">
              <h3 class="cl-accent weight-400">
                {{ $t('Kundenservice') }}
              </h3>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/ringgroesse')" exact>
                  {{ $t('Ringgrösse ermitteln') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/ringmass-senden')" exact>
                  {{ $t('Ringmaß zusenden') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/individuelle-gravur')" exact>
                  {{ $t('Individuelle Gravuren') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/trauringe-selbst-gestalten')" exact>
                  {{ $t('Ringe selbst kombinieren') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/hilfe')" exact>
                  {{ $t('Hilfe / FAQ') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/schweiz')" exact>
                  {{ $t('Lieferung Schweiz') }}
                </router-link>
              </div>
              <div class="mt15">
                <div id="auorg-bg">
                  <a class="auorg-br" href="https://www.ausgezeichnet.org" rel="nofollow" title="Unabh&auml;ngige Bewertungen, Kundenbewertungen und G&uuml;tesiegel von Ausgezeichnet.org" target="_blank">
                    <span style="font-size: 8px; font-weight: normal; text-transform: uppercase;">Ausgezeichnet.org</span>
                  </a>
                </div>
              </div>
            </div>
            <div class="start-md">
              <h3 class="cl-accent weight-400">
                {{ $t('Wissenswertes') }}
              </h3>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/legierungen')" exact>
                  {{ $t('Legierungen') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('http://gerstner-trauringe.de/ueber-uns/qualitaet-eines-gerstner-traurings#herstellung_video')" exact>
                  {{ $t('Gerstner Trauringherstellung als Film') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/diamanten')" exact>
                  {{ $t('Diamanten') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/freundschaftsringe')" exact>
                  {{ $t('Freundschaftsringe') }}
                </router-link>
              </div>
              <div class="mt15">
                <router-link class="cl-secondary" :to="localizedRoute('/partnerringe')" exact>
                  {{ $t('Partnerringe') }}
                </router-link>
              </div>
              <div class="start-md">
                <h3 class="cl-accent weight-400">
                  {{ $t('Folgen Sie uns') }}
                </h3>
              </div>
              <div id="fb-root">&nbsp;</div>
              <div class="fb-like" data-href="https://www.hochzeitstrauringe.de/" data-width="212" data-layout="button_count" data-action="like" data-size="large" data-show-faces="true" data-share="true">&nbsp;</div>
            </div>
          </div>
          <div class="row social arw-col col-xs-6 col-sm-6 col-md-3 col-lg-3">
            <div class="block-title">
              <h2><img class="" height="39" src="https://www.hochzeitstrauringe.de/media/wysiwyg/ueberweisung-H.T.png" width="98"></h2>
              <p><span style="font-size: xx-small; font-family: arial, helvetica, sans-serif;"><em><strong>3 % Skonto:</strong></em> Überweisen Sie den Betrag auf unser Konto und sicher Sie sich 3 %:.Die Bankdaten bekommen Sie separat mit der Bestellung</span></p>
              <p><img class="" height="59" src="https://www.hochzeitstrauringe.de/media/wysiwyg/paypal-hochzeitstrauringe.jpg" width="95"></p>
              <p><span style="font-size: xx-small; font-family: arial, helvetica, sans-serif;">Mit PayPal PLUS können Sie wie folgt bezahlen:</span></p>
              <p><span style="font-size: xx-small; font-family: arial, helvetica, sans-serif;">PayPal, Lastschrift, Kreditkarte, Kauf auf Rechnung auch ohne Paypal-Konto</span></p>
              <p><img class="" height="67" src="https://www.hochzeitstrauringe.de/media/wysiwyg/Klarna-H.T.png" width="97"></p>
              <p><span style="font-size: xx-small; font-family: arial, helvetica, sans-serif;">Kaufen Sie Ihre Traumringe auf Rechnung, Ratenzahlung bis <strong>1500</strong> €.</span></p>
              <p><span style="font-size: xx-small; font-family: arial, helvetica, sans-serif;">&nbsp;<img class="" height="86" src="https://www.hochzeitstrauringe.de/media/wysiwyg/easycredit_H.T.jpg" width="107"></span></p>
              <p><span style="font-size: xx-small; font-family: arial, helvetica, sans-serif;"><span style="font-size: xx-small; font-family: arial, helvetica, sans-serif;">Ringkauf ab&nbsp;<strong>200</strong> € bis <strong>5000</strong> €, zahlen Sie bequem in Raten.</span></span></p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row middle-xs px15 bottom-links">
        <div class="col-xs-5 col-sm-3 cl-tertiary">
          <language-switcher v-if="multistoreEnabled" />
        </div>
        <div class="col-xs col-sm-9 end-xs">
          <ul class="pl0 links" data-testid="bottomLinks">
            <li class="inline-flex">
              <router-link
                class="cl-tertiary mr10 underline"
                to="/legal"
                exact
              >
                {{ $t('Legal notice') }}
              </router-link>
            </li>
            <li class="inline-flex">
              <router-link
                class="cl-tertiary underline"
                to="/privacy"
                exact
              >
                {{ $t('Privacy policy') }}
              </router-link>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import CurrentPage from 'theme/mixins/currentPage'
import LanguageSwitcher from '../../LanguageSwitcher.vue'
import Newsletter from 'theme/components/core/blocks/Footer/Newsletter'

export default {
  mixins: [CurrentPage],
  name: 'MainFooter',
  computed: {
    multistoreEnabled () {
      return this.$store.state.config.storeViews.multistore
    },
    getVersionInfo () {
      return `v${process.env.__APPVERSION__} ${process.env.__BUILDTIME__}`
    }
  },
  components: {
    Newsletter,
    LanguageSwitcher
  }
}
</script>

<style lang="scss" scoped>
@import '~theme/css/variables/colors';
@import '~theme/css/helpers/functions/color';
$color-secondary: color(secondary);

.icon {
  transition: 0.3s all;
}

.social-icon {
  width: 40px;
  height: 40px;
  &:hover,
  &:focus,
  &:active {
    .icon {
      fill: $color-secondary;
    }
  }
}
.links {
  list-style-type: none;
  display: flex;
  flex-direction: column-reverse;
  align-items: flex-end;

  @media (min-width: 768px) {
    flex-direction: row;
    justify-content: flex-end;
    align-items: center;
  }
}

.bottom-links {
  @media (max-width: 767px) {
    padding: 0;
  }
}

.footer__version-info {
  display: flex;
  color: $color-secondary;
  font-size: 0.7rem;
  @media (min-width: 768px) {
    margin-right: 1rem;
    font-size: 0.8rem;
  }
}

.underline {
  &:hover {
    color: $color-secondary;
    &:after {
      background-color: $color-secondary;
    }
  }
}
.legal-entity-link {
  text-align: center;
  @media (min-width: 768px) {
    display: none;
  }
}

.privacy-policy-link {
  text-align: right;
  @media (min-width: 768px) {
    display: none;
  }
}

@media (max-width: 595px) {
  .no-mobile {
    display: none;
  }

  .social {
    margin-top: 0;
  }

  .footer-links {
    padding-bottom: 30px;
  }
}
</style>
