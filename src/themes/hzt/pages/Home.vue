<template>
  <div id="home">
    <main-slider />

    <promoted-offers/>

    <section class="new-collection container px15">
      <div>
        <header class="col-md-12">
          <h2 class="align-center cl-accent">{{ $t('Everything new') }}</h2>
        </header>
      </div>
      <div class="row center-xs">
        <product-listing columns="4" :products="everythingNewCollection" />
      </div>
    </section>

    <collection :title="$t('Unsere Marken')" cover-image="/assets/collection.jpg" category="Women"/>

    <section class="container pb60 px15">
      <div class="row">
        <h1>Trauringe, Eheringe und Verlobungsringe bei Hochzeitstrauringe.de</h1>
        <div class="col-xs-12 col-sm-6 col-md-6 col-lg-6 pb30">
          <p>Sich begegnen - beschnuppern, verlieben, kennenlernen: Liebe kennt viele Nuancen. Die Liebe l&auml;sst das Herz tanzen und macht aus Alltagen - Sonnentage. Sie sind der Liebe begegnet und haben den Menschen gefunden, dem die Aussicht, das Leben mit Ihnen zu teilen, das Herz w&auml;rmt? Das ist ein gro&szlig;es Gl&uuml;ck!</p>
          <p>&nbsp;</p>
          <p>Sie m&ouml;chten heiraten? Genie&szlig;en Sie die Zeit der Hochzeitsvorbereitungen! Diese kribbelnde Vorfreude auf den Hochzeitstag - die Aufregung und die vielen liebevollen Kleinigkeiten, die f&uuml;r Ihr Hochzeitsfest zu bedenken sind. Es gibt so viele Arten "Ja" zu sagen - exklusiv oder ungew&ouml;hnlich - gem&uuml;tlich oder eher still - im Kreise lieber Freunde. Eine Konstante haben all die verschiedenen Hochzeitsfeiern: Die meisten Paare sind besonders ber&uuml;hrt von dem Moment, an dem sie sich gegenseitig den Trauring anstecken - als Zeichen ihrer tief empfundener Verbundenheit.</p>
          <p>&nbsp;</p>
          <p>Der Kreis ist eine sch&ouml;ne Metapher f&uuml;r die Liebe - er hat keinen Anfang und kein Ende. Der Ehering ist ein treffliches Symbol f&uuml;r die Zeitlosigkeit und Dauerhaftigkeit einer Verbindung, in der Menschen bereit sind, Verantwortung f&uuml;reinander zu &uuml;bernehmen: <strong>Partnerringe, Verlobungsringe, <a href="https://youtu.be/YUQwSJouODA" title="Trauringe">Trauringe &amp; Eheringe</a>-</strong> das sind nicht nur wundersch&ouml;ne Schmuckst&uuml;cke, an denen Sie sich immer wieder freuen - sie bekennen sich mit dem Tragen Ihres Ringes zu dem Menschen, f&uuml;r den Sie sich entschieden haben: jeden Tag aufs Neue.</p>
          <p>Ihre Eheringe tragen Sie - Tag und Nacht - bei der Gartenarbeit, am Computer, in der Umarmung und der Vers&ouml;hnung nach einem Streit, beim Einkaufen, Kochen und im Urlaub - im t&auml;glichen Stress und beim gemeinsamen Relaxen. Sie begleiten Sie durch die Jahreszeiten und werden immer mehr zu einem selbstverst&auml;ndlichen Teil von Ihnen. Nehmen Sie sich deshalb die Zeit, Ihre Trauringe in aller Ruhe und gemeinsam auszuw&auml;hlen.</p>
          <p>So vielf&auml;ltig die Lebensformen der Partnerschaften heutzutage sind - so gro&szlig; ist die Auswahl: filigrane Ringe f&uuml;r zarte H&auml;nde, breite Ringe, <strong>Eheringe mit Diamanten</strong> f&uuml;r die Braut - vielf&auml;ltige Materialien und verschiedene Legierungen mit unterschiedlichen Trageeigenschaften: Unser online Shop bietet Ihnen umfassende Informationen und ein riesiges Sortiment an wundersch&ouml;nen Schmuckst&uuml;cken, die zu Ihren Lebensbegleitern werden k&ouml;nnen.</p>
          <p><strong>Welches Metall favorisieren Sie?</strong></p>
          <p>Lieben Sie das gl&auml;nzende <strong><a href="http://www.hochzeitstrauringe.de/trauringe/gelbgold.html" title="Gelbgold Trauringe">Gelbgold</a>, <a href="http://www.hochzeitstrauringe.de/trauringe/rotgold.html" title="Rotgold Trauringe">warmes Rotgold</a></strong> - oder fasziniert Sie k&uuml;hl und edel wirkendes <strong><a href="http://www.hochzeitstrauringe.de/trauringe/weissgold.html" title="Wei&szlig;gold Trauringe">Wei&szlig;gold</a>, <a href="http://www.hochzeitstrauringe.de/trauringe/platin.html">Platin</a></strong> oder gar das federleichte <strong><a href="http://www.hochzeitstrauringe.de/trauringe/titan.html" title="Titan Trauringe">Titan</a></strong>? Oder m&ouml;gen Sie trendige schwarze Ringe aus <strong><a href="https://www.hochzeitstrauringe.de/trauringe/carbon.html">Carbon</a>? </strong>Oder sie m&ouml;chten Ringe aus dem seltensten Element in unserem Sonnensystems, Ringe aus <strong><a href="https://www.hochzeitstrauringe.de/trauringe/tantal.html">Tantal </a></strong>?</p>
          <p>Nehmen Sie sich Zeit f&uuml;r Ihre Wahl und vergleichen Sie - damit Sie sich wirklich f&uuml;r Ringe entscheiden, die Ihnen beiden nach vielen gemeinsamen Jahren noch immer gefallen. Wir haben f&uuml;r Sie in unserem Sortiment eine Vielzahl von Modellen zusammengestellt: Exquisite Modelle aus Platin oder <strong><a href="http://www.hochzeitstrauringe.de/trauringe/palladium.html" title="Palladium Trauringe">Palladium</a></strong> - aber auch viele sehr sch&ouml;ne Eheringe f&uuml;r das etwas schmalere Budget - beispielsweise Trauringe in sehr klarer Formgebung aus dem kosteng&uuml;nstigen Titan, das noch einen weiteren Vorteil bietet: Dieses Metall ist besonders geeignet, wenn Sie zu <strong>Allergien</strong> neigen. Moderne Klassiker - nicht nur f&uuml;r Allergie geplagte Zeitgenossen - sind auch unsere Partner- und Eheringe aus Edelstahl - teilweise mit wundersch&ouml;n kontrastierenden Einlagen aus Gold und Diamanten. Wundersch&ouml;n sowie preisg&uuml;nstig auch Ringe aus <a href="https://www.hochzeitstrauringe.de/trauringe/silber.html"><em><strong>Silber</strong></em></a>.</p>
          <p>Sie m&uuml;ssen sich bei der Wahl Ihrer Trauringe jedoch nicht auf ein Metall festlegen: Die hoch technisierten, modernen Fertigungsverfahren der renommierten Trauring-Hersteller erlauben Kombinationen von bis zu vier verschiedenen Metalllegierungen in unterschiedlichsten Formen - auch mit Schmucksteinen (beispielsweise Diamanten) in verschiedenen Gr&ouml;&szlig;en f&uuml;r den Brautring.</p>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-6 col-lg-6 pb30">
          <p><strong>Ihre Eheringe - einzigartige, selbst kreierte Unikate</strong></p>
          <p>Sie haben schon bestimmte Vorstellungen davon, wie die Ringe f&uuml;r Ihr gemeinsames Leben aussehen sollen? Sollten Sie in unserem reichhaltigen Sortiment kein Eheringmodell finden, das Ihren Vorstellungen vollkommen entspricht - konfigurieren Sie sich Ihre Trauringe einfach selbst! Wir bieten Ihnen sechs verschiedene Konfigurationsprogramme renommierter Trauring Spezialisten. Sie finden vielf&auml;ltige Wahlm&ouml;glichkeiten in Bezug auf die Formen, unterschiedliche Legierungen, Schmucksteine und vieles mehr. Lassen Sie Ihrer Kreativit&auml;t freien Lauf und entwerfen Sie ihre eigenen unverwechselbaren Eheringe - bei uns erhalten Sie diese selbst entworfenen Ringe zu sehr g&uuml;nstigen Preisen. N&auml;here Einzelheiten finden Sie in der Rubrik "&nbsp;<a href="https://www.hochzeitstrauringe.de/trauringe-selbst-gestalten.html"><strong>Trauringkonfigurator</strong></a>".</p>
          <p><strong>Der Verlobungsring - f&uuml;r den entscheidenden Moment</strong></p>
          <p>Unvergesslich f&uuml;r ein ganzes Leben bleibt der - zitternd sch&ouml;ne - Moment des Heiratsantrages: Dieser ber&uuml;hrende Augenblick wird gekr&ouml;nt durch das Symbol der zeitlosen Liebe - ein Geschenk f&uuml;r die Braut: den <a href="http://www.hochzeitstrauringe.de/verlobungsringe.html">Verlobungsring</a>. Dieses wundersch&ouml;ne Herzensritual hat auch heute nichts von seinem Zauber verloren. Romantisch und liebevoll - ein Verlobungsring mit einem Diamanten steht f&uuml;r die Klarheit und die Unzerst&ouml;rbarkeit des Gef&uuml;hls der Liebe, die Sie mitnehmen in Ihr gemeinsames Leben. Auch wenn es nur ein kleiner Diamant ist - er funkelt sich direkt ins Herz der Braut und bleibt ihr lieb und teuer - als Erinnerung an diesen einzigartigen Augenblick. Unser Sortiment h&auml;lt eine reiche Auswahl an wundersch&ouml;nen Verlobungsringen f&uuml;r Sie bereit.</p>
          <p><strong>Partnerringe als Symbol tiefer Verbundenheit</strong></p>
          <p>Heutzutage sind - gl&uuml;cklicherweise - alle Arten der Partnerschaft gesellschaftlich akzeptiert. Im Gegensatz zu fr&uuml;heren Zeiten haben jetzt Paare die Wahl, auf welche Weise sie Ihre Verbundenheit auch nach au&szlig;en dokumentieren m&ouml;chten, denn nicht immer ist die Ehe die bevorzugte Form des Zusammenlebens zweier Menschen, die sich lieben. Mit Partnerringen k&ouml;nnen Sie Ihr tiefes Gef&uuml;hl der Zusammengeh&ouml;rigkeit auch Ihrer Umwelt zeigen. Wir bieten Ihnen ein breites Sortiment: <strong><a href="http://www.hochzeitstrauringe.de/partnerringe.html">Partnerringe und Freundschaftsringe</a> f&uuml;r jedes Budget</strong>.</p>
          <p><strong>W&auml;hlen Sie bequem zu Hause</strong></p>
          <p>Sie finden in unserem Onlineshop Eheringe, Partnerringe und Verlobungsringe namhafter Schmuckhersteller - wie beispielsweise Breuning, Gerstner, Saint Maurice, Collection Ruesch Nowotny, Herzog, Cilor, Simon &amp; S&ouml;hne, Titan Factory und viele mehr. Wir w&uuml;nschen Ihnen viel Freude beim Finden Ihrer Wunschringe!</p>
          <p><strong>Ring verloren?</strong></p>
          <p>Wir schaffen Ersatz. Sie k&ouml;nnen bei uns auch Ihren <strong>Ring einzeln</strong> oder ohne Brillanten bestellen. Bitte senden Sie uns hierzu ein Email an: info@hochzeitstrauringe.de</p>
          <p><strong>Warum bei uns bestellen?</strong></p>
          <p>Wir f&uuml;hren die bekanntesten Marken-Trauringe die bei Juwelieren zu finden sind und bieten Ihnen ein umfangreicheres Angebot zu besonderen Preisen an !</p>
          <p>Schauen sie sich zudem unsere <a href="https://www.ausgezeichnet.org/bewertungen-hochzeitstrauringe.de-3CDMMS" target="_blank">Bewertungen</a> von Kunden an und entscheiden Sie selbst wem Sie ihr Vertrauen schenken. Wir haben schon sehr viele Paare gl&uuml;cklich machen k&ouml;nnen, seien sie die n&auml;chsten.</p>
          <p>&nbsp;</p>
        </div>
      </div>
    </section>

  </div>
</template>

<script>
// query constructor
import { prepareQuery } from '@vue-storefront/core/modules/catalog/queries/common'

// Core pages
import Home from '@vue-storefront/core/pages/Home'

// Theme core components
import ProductListing from 'theme/components/core/ProductListing'
import MainSlider from 'theme/components/core/blocks/MainSlider/MainSlider'
import HeadImage from 'theme/components/core/blocks/MainSlider/HeadImage'

// Theme local components
import Collection from 'theme/components/theme/blocks/Collection/Collection'
import Onboard from 'theme/components/theme/blocks/Home/Onboard'
import PromotedOffers from 'theme/components/theme/blocks/PromotedOffers/PromotedOffers'
import TileLinks from 'theme/components/theme/blocks/TileLinks/TileLinks'
import { Logger } from '@vue-storefront/core/lib/logger'
export default {
  mixins: [Home],
  components: {
    Collection,
    MainSlider,
    HeadImage,
    Onboard,
    ProductListing,
    PromotedOffers,
    TileLinks
  },
  computed: {
    categories () {
      return this.getCategories
    },
    everythingNewCollection () {
      return this.$store.state.homepage.new_collection
    },
    coolBagsCollection () {
      return this.$store.state.homepage.coolbags_collection
    }
  },
  created () {
    // Load personal and shipping details for Checkout page from IndexedDB
    this.$store.dispatch('checkout/load')
  },
  async beforeMount () {
    if (this.$store.state.__DEMO_MODE__) {
      const onboardingClaim = await this.$store.dispatch('claims/check', { claimCode: 'onboardingAccepted' })
      if (!onboardingClaim) { // show onboarding info
        this.$bus.$emit('modal-toggle', 'modal-onboard')
        this.$store.dispatch('claims/set', { claimCode: 'onboardingAccepted', value: true })
      }
    }
  },
  async asyncData ({ store, route }) { // this is for SSR purposes to prefetch data
    const config = store.state.config

    Logger.info('Calling asyncData in Home (theme)')()

    let newProductsQuery = prepareQuery({ queryConfig: 'newProducts' })
    let coolBagsQuery = prepareQuery({ queryConfig: 'coolBags' })

    const newProductsResult = await store.dispatch('product/list', {
      query: newProductsQuery,
      size: 8,
      sort: 'created_at:desc',
      includeFields: config.entities.optimize ? (config.products.setFirstVarianAsDefaultInURL ? config.entities.productListWithChildren.includeFields : config.entities.productList.includeFields) : []
    })
    if (newProductsResult) {
      store.state.homepage.new_collection = newProductsResult.items
    }

    const coolBagsResult = await store.dispatch('product/list', {
      query: coolBagsQuery,
      size: 4,
      sort: 'created_at:desc',
      includeFields: config.entities.optimize ? (config.products.setFirstVarianAsDefaultInURL ? config.entities.productListWithChildren.includeFields : config.entities.productList.includeFields) : []
    })
    if (coolBagsResult) {
      store.state.homepage.coolbags_collection = coolBagsResult.items
    }

    await store.dispatch('promoted/updateHeadImage')
    await store.dispatch('promoted/updatePromotedOffers')
  }
}
</script>

<style lang="scss" scoped>
  .new-collection {
    @media (max-width: 767px) {
      padding-top: 0;
    }
  }
</style>
