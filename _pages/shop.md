---
title: "Online-Shop"
permalink: /shop/
layout: single
classes: wide
---

<style>
  .page {
    width: 100% !important;
    padding-right: 0 !important;
  }

  .page__inner-wrap,
  .page__content {
    width: 100% !important;
    max-width: none !important;
  }

  .shop-wrapper {
    width: 100%;
    margin: 0;
    padding: 0;
  }

  .shop-notice {
    position: sticky;
    top: 0;
    z-index: 1000;

    padding: 14px 20px;
    margin: 0;

    background: #eef7ff;
    border-bottom: 1px solid #c9e4f7;

    font-size: 0.95rem;
    line-height: 1.5;
  }

  .shop-notice strong {
    font-weight: 700;
  }

  .shop-frame {
    display: block;
    width: 100%;
    height: calc(100vh - 120px);
    min-height: 750px;

    border: 0;
    background: #fff;
  }

  @media (max-width: 768px) {

    .shop-notice {
      padding: 12px 14px;
      font-size: 0.88rem;
    }

    .shop-frame {
      height: calc(100vh - 150px);
      min-height: 650px;
    }

  }
</style>


<div class="shop-wrapper">

  <div class="shop-notice">
  In unserem Webshop in Kooperation mit VetNative finden Sie ein umfangreiches Sortiment. <strong>Bitte beachten Sie:</strong> Einige der angebotenen Produkte sind für besondere medizinische oder ernährungsphysiologische Bedürfnisse bestimmt. Diätfuttermittel und Nahrungsergänzungsmittel dürfen daher nur nach tierärztlicher Beratung verwendet werden, da sie Teil der Therapie sind.
  </div>


  <iframe
    class="shop-frame"
    src="https://eltiga.vetnative.com/shop/landing?code=TVRFMU9BLjN4bm42X1ZsVGNRM2cyS1BNNDZfRm1CS1UwdjRBYzk0NkxQbG1hbUlvVzQ"
    title="Vetcat Online-Shop"
    loading="eager"
    allow="payment *"
    referrerpolicy="strict-origin-when-cross-origin">
  </iframe>

</div>
