---
layout: page
title: Shop
permalink: /shop/
---


<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produtos</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        text-align: center;
      }

      .search-bar {
        margin: 20px auto;
        max-width: 600px;
        display: flex;
        justify-content: center;
        position: relative;
      }

      .search-bar input {
        width: 100%;
        padding: 10px;
        font-size: 16px;
        border: 2px solid #ccc;
        border-radius: 8px;
        margin-bottom: 16px;
      }

      .divider {
        margin: 20px auto;
        width: 80px;
        height: 3px;
        background-color: black;
      }

      .product-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
        padding: 20px;
        max-width: 1200px;
        margin: 0 auto;
      }

      .product-card {
        text-align: center;
        border: 1px solid #ccc;
        border-radius: 10px;
        padding: 16px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      }

      .product-card img {
        width: 200px;
        height: 200px;
        object-fit: cover;
        margin-bottom: 10px;
      }

      .product-card:hover {
        transform: scale(1.05);
      }

      .product-card h3 {
        font-size: 14px;
        margin: 5px 0;
        text-align: center;
        margin-bottom: 16px;
        margin: 10px;
      }

      .product-card button {
        padding: 6px 14px;
        border: none;
        background-color: black;
        color: white;
        border-radius: 20px;
        text-align: center;
      }

      .product-card button:hover {
        background-color: darkgray;
      }

      .product-card button a {
        font-size: 14px;
        color: white;
        text-decoration: none;
        text-transform: uppercase;
      }

      .filter-buttons {
        display: flex;
        flex-wrap: wrap;
        margin-bottom: 20px;
        gap: 10px;
        justify-content: center;
      }

      .filter-btn {
        background-color: black;
        color: white;
        padding: 10px 20px;
        margin-right: 10px;
        border: none;
        border-radius: 20px;
        cursor: pointer;
        transition: background-color 0.3s;
         min-width: 100px;
      }

      .filter-btn:hover {
        background-color: #333;
      }

      .filter-btn.active {
        background-color: #555;
      }

      .product {
        display: block;
        margin: 10px 0;
      }

      .hidden {
        display: none;
      }


      @media (max-width: 768px) {
        .filter-buttons {
          justify-content: space-between;
        }

        .filter-btn {
          flex: 1 1 50%;
          min-width: auto;
        }
      }
    </style>
  </head>
  <body>
    <div class="search-bar">
      <input type="text" id="search" placeholder="O que você está buscando?">
    </div>

    <div class="filter-buttons">
      <button class="filter-btn" data-tag="cafe">Setup Café</button>
      <button class="filter-btn" data-tag="kellyn">Setup Kellyn</button>
      <button class="filter-btn" data-tag="marcelo">Setup Marcelo</button>
      <button class="filter-btn" data-tag="gravacao">Equipamentos de Gravação</button>
      <button class="filter-btn" data-tag="corrida">Corrida</button>
    </div>

  <div class="product-grid product-list">
    <div class="product-card product" data-tags="cafe">
      <img src="https://images.tcdn.com.br/img/img_prod/840963/cafeteira_eletrica_tramontina_by_breville_express_em_aco_inox_1_8_l_220v_333_1_ecdea05f664ae9c0b15912aa88d0c8e9.jpg" alt="Máquina de Café Espresso">
      <h3>Máquina de Café Espresso Tramontina By Breville</h3>
      <button><a href="https://amzn.to/4fYbPkh" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://m.media-amazon.com/images/I/61rFq1NOoUL.jpg" alt="Moedor Elétrico">
      <h3>Moedor Elétrico MiiCoffee DF54</h3>
      <button><a href="https://amzn.to/4hcd2Fx" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://http2.mlstatic.com/D_NQ_NP_759140-MLB76314233647_052024-O.webp" alt="Moedor Manual">
      <h3>Moedor Manual KINGrinder K2</h3>
      <button><a href="https://amzn.to/3E3Kobl" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://http2.mlstatic.com/D_NQ_NP_864834-CBT77988856517_072024-O.webp" alt="Balança Digital">
      <h3>Balança Digital Timemore</h3>
      <button><a href="https://amzn.to/4axFBLW" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://m.media-amazon.com/images/I/512dQWCfLgL._AC_SL1500_.jpg" alt="Chaleira Elétrica">
      <h3>Chaleira Elétrica Timemore</h3>
      <button><a href="https://amzn.to/4jgb34U" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://cafestore.vteximg.com.br/arquivos/ids/156323-1000-1000/1042.jpg?v=636875632807070000" alt="Chaleira Hario">
      <h3>Chaleira Hario</h3>
      <button><a href="https://amzn.to/40sE1r1" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://www.bialettishop.com.br/media/catalog/product/cache/1/image/550x550/9df78eab33525d08d6e5fb8d27136e95/c/a/cafeteira_french_press_preziosa_350ml_bialetti_1.jpg" alt="Prensa Francesa">
      <h3>Prensa Francesa</h3>
      <button><a href="https://amzn.to/4ah1dvz" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://www.koacafes.com.br/cdn/shop/files/aeropress_1445x.jpg?v=1715367464" alt="Aeropress">
      <h3>Aeropress</h3>
      <button><a href="https://mercadolivre.com/sec/2wXrfrG" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://cdn.awsli.com.br/600x450/823/823384/produto/41869537/478693af08.jpg" alt="Hario V60">
      <h3>Hario V60</h3>
      <button><a href="https://amzn.to/4qvZSYf" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="cafe">
      <img src="https://www.koacafes.com.br/cdn/shop/products/decanter_550x.webp?v=1674736359" alt="Hario V60 Drip Decanter">
      <h3>Hario V60 Drip Decanter</h3>
      <button><a href="https://amzn.to/4fUs6Xm" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn">
      <img src="https://images0.kabum.com.br/produtos/fotos/658780/macbook-pro-apple-16-m4-cpu-14-nucleos-gpu-32-nucleos-36gb-ram-ssd-1tb-preto-espacial-mx303bz-a_1731330119_g.jpg" alt="MacBook Pro">
      <h3>MacBook Pro M3 Max</h3>
      <button><a href="https://mercadolivre.com/sec/2tpHw6M" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn">
      <img src="https://images3.kabum.com.br/produtos/fotos/371253/monitor-gamer-lg-26-ips-ultra-wide-75hz-full-hd-1ms-freesync-premium-hdr-10-99-srgb-hdmi-vesa-26wq500_1703079402_g.jpg" alt="Monitor Ultrawide LG">
      <h3>Monitor Ultrawide LG</h3>
      <button><a href="https://amzn.to/4ahmtBe" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="marcelo">
      <img src="https://m.media-amazon.com/images/I/519mhluOd3L._AC_SL1200_.jpg" alt="Monitor LG Ultrafine">
      <h3>Monitor LG UltraFine</h3>
      <button><a href="https://amzn.to/3Zz99nz" target="_blank">Comprar</a></button>
    </div>




    <div class="product-card product" data-tags="kellyn marcelo">
      <img src="https://a-static.mlcdn.com.br/800x560/suporte-ergonomico-multiarticulado-de-mesa-para-monitor-17-a-35-elg-f98hdmi-pistao-a-gas-vesa-grafite-f98hdmi/kabum/469012/41bc9c61ab8009bca3286f6f7ff12323.jpeg" alt="Suporte Monitor">
      <h3>Suporte Monitor Articulado ELG</h3>
      <button><a href="https://amzn.to/4gSgVQe" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ5-CRK3owxsSLsBivic317cZG9-fpqnWpYPA&s" alt="Teclado Razer">
      <h3>Teclado Mecânico Razer Blackwidow Lite</h3>
      <button><a href="https://tidd.ly/4qwoRed" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn">
      <img src="https://http2.mlstatic.com/D_NQ_NP_637359-MLU78868612596_092024-O.webp" alt="Mouse Logitech">
      <h3>Mouse Logitech MX Ergo</h3>
      <button><a href="https://mercadolivre.com/sec/2hQxSHt" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn marcelo">
      <img src="https://loja.elements.com.br/cdn/shop/files/cadeira-ergonomica-elements-sophy-006.png?v=1730293689&width=1000" alt="Cadeira Sophy">
      <h3>Cadeira Sophy Elements</h3>
      <button><a href="https://www.awin1.com/cread.php?awinmid=48557&awinaffid=1709665&ued=https%3A%2F%2Floja.elements.com.br%2Fproducts%2Fcadeira-ergonomica-elements-sophy%3F_pos%3D1%26_sid%3D9e0162a2d%26_ss%3Dr" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn marcelo">
      <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcQn1OENtx0zPY_T0FL-LWLG4eSAJqBPh_LG07qrRusjlxRTUbOPfzGigCntEo7WK_38an7AfwEa&usqp=CAc" alt="Mesa GenioDesk">
      <h3>Mesa com Regulagem de Altura GenioDesk PRO</h3>
      <button><a href="https://www.geniodesks.com.br/mesa-regulagem-eletrica/produto-mesa-com-regulagem-de-altura-geniodesk-pro" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn marcelo">
      <img src="https://ae-pic-a1.aliexpress-media.com/kf/S1960975317894368a24ed9e04af57be9C.jpg_960x960q75.jpg_.avif" alt="Mouse Pad">
      <h3>Mouse Pad Medium Gray 80x40</h3>
      <button><a href="https://pt.aliexpress.com/item/1005005647942386.html?spm=a2g0o.order_list.order_list_main.70.7e20caa4EBuER9&gatewayAdapt=glo2bra" target="_blank">Comprar</a></button>
    </div>

     <div class="product-card product" data-tags="kellyn marcelo">
      <img src="https://down-br.img.susercontent.com/file/sg-11134201-7rbl7-lo5qhtjumcdv9a.webp" alt="Mouse Pad">
      <h3>Temporizador cubo</h3>
      <button><a href="https://s.shopee.com.br/7KrUiUzODQ" target="_blank">Comprar</a></button>
    </div>



    <div class="product-card product" data-tags="kellyn">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_766170-MLA95970239508_102025-F.webp" alt="Suporte Lamicall">
      <h3>Suporte Notebook Lamicall</h3>
      <button><a href="https://mercadolivre.com/sec/31Z5b6C" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn">
      <img src="https://d1ncau8tqf99kp.cloudfront.net/converted/110696_original_local_256x224_v3_converted.webp" alt="Headset Sony">
      <h3>Headset Sony WH-CH720N</h3>
      <button><a href="https://amzn.to/3C292bZ" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn">
      <img src="https://images1.kabum.com.br/produtos/fotos/275871/teclado-sem-fio-logitech-mx-keys-mini-iluminacao-smart-bluetooth-usb-easy-switch-recarregavel-grafite-920-010505_1677185299_g.jpg" alt="Mx keys">
      <h3>Teclado Logitech MX Keys Mini</h3>
      <button><a href="https://amzn.to/42XL5xE" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="marcelo">
      <img src="https://images.tcdn.com.br/img/img_prod/740836/notebook_dell_vostro_3401_core_i5_1035g1_mem_8gb_ssd_256gb_tela_14_hd_windows_10_home_outlet_12879_5_533b245059a126653a44aa8adc11c469.jpg" alt="Notebook Dell">
      <h3>Notebook Dell Vostro 14</h3>
      <button><a href="https://www.dell.com/support/product-details/pt-br/servicetag/0-Z2ZKR1lJS3FkbGNaRVhGSWx3eVBKQT090/overview#" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="marcelo">
      <img src="https://tupinikeebs.com/wp-content/uploads/2024/03/PXL_20240222_144042890-1280x720.jpg" alt="Teclado Corne">
      <h3>Teclado Split Corne Tupinikeebs</h3>
      <button><a href="https://www.instagram.com/p/DCW0hriuo_7/?img_index=4" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="marcelo">
      <img src="https://m.media-amazon.com/images/I/81bQEkMevBL.jpg" alt="Headset Logitech">
      <h3>Headset Logitech G435</h3>
      <button><a href="https://amzn.to/407Q5wq" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="marcelo">
      <img src="https://images.kabum.com.br/produtos/fotos/101288/microfone-gamer-hyperx-quadcast-antivibracao-led-preto-e-vermelho-hx-micqc-bk_1615553162_gg.jpg" alt="Microfone HyperX">
      <h3>Microfone HyperX QuadCast</h3>
      <button><a href="https://amzn.to/4ahnysM" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="marcelo">
      <img src="https://http2.mlstatic.com/D_NQ_NP_619241-MLB72803008591_112023-O.webp" alt="Braço para Microfone">
      <h3>Braço Articulado para Microfone</h3>
      <button><a href="https://amzn.to/3C8XHqz" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_917960-MLB78411498163_082024-O.webp" alt="DJI Osmo Pocket">
      <h3>Dji Osmo Pocket 3 Creator Combo</h3>
      <button><a href="https://mercadolivre.com/sec/26YWJGF" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_890083-MLA99938135145_112025-F.webp" alt="DJI Osmo Pocket">
      <h3>Dji Osmo Nano</h3>
      <button><a href="https://mercadolivre.com/sec/2j7LP2U" target="_blank">Comprar</a></button>
    </div>


    <div class="product-card product" data-tags="gravacao">
      <img src="https://br.octoshop.com/cdn/shop/files/Fujifilm_X100V_2.jpg?v=1734981794&width=610" alt="Fujifilm X100V">
      <h3>Fujifilm X100V</h3>
      <button><a href="https://mercadolivre.com/sec/2AvtNah" target="_blank">Comprar</a></button>
    </div>

     <div class="product-card product" data-tags="gravacao">
      <img src="https://loja.fujifilm.com.br/cdn/shop/files/1_0a1871b5-b4b4-4581-8ae2-54e1644f9dc4.jpg?v=1738586358" alt="Fujifilm X-M5">
      <h3>Fujifilm X-M5</h3>
      <button><a href="https://www.lojadosmarios.com/camera-fujifilm-x-m5-com-lente-xc-15-45mm-f35-56-prata?utm_source=Site&utm_medium=GoogleShopping&utm_campaign=IntegracaoGoogle&gad_source=4&gad_campaignid=17946726685&gbraid=0AAAAAo1gnECmislBG2RUdJMF3OAFhkG1u&gclid=CjwKCAiAtLvMBhB_EiwA1u6_Pvq9szptaSIEwJy_9vyUuM-pSM_9luYYuiP-JUBcJQ6w4TAZL31F9hoCXMoQAvD_BwE" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://images0.kabum.com.br/produtos/fotos/937020/microfone-dji-mic-2-1-tx-microfone-br-dji114_1761305093_gg.jpg" alt="Microfone DJI">
      <h3>Microfone DJI Mic 2</h3>
      <button><a href="https://tidd.ly/4rh6uLv" target="_blank">Comprar</a></button>
    </div>

      <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_914829-MLA100075901141_122025-F.webp" alt="Microfone DJI Mini">
      <h3>Microfone DJI Mic Mini</h3>
      <button><a href="https://mercadolivre.com/sec/1QNM8rs" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_980588-MLU73202293281_122023-O.webp" alt="Microfone Hollyland">
      <h3>Microfone Hollyland Lark M1</h3>
      <button><a href="https://mercadolivre.com/sec/1aknGSc" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_766972-MLU75640053739_042024-O.webp" alt="Tripé">
      <h3>Tripé Tomate Mtg-3016</h3>
      <button><a href="https://mercadolivre.com/sec/1U1D1FA" target="_blank">Comprar</a></button>
    </div>

     <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_772003-MLB86502726637_062025-F.webp" alt="Tripé">
      <h3>Mini Tripé de mão Ulanzi TT38</h3>
      <button><a href="https://mercadolivre.com/sec/1NZztCj" target="_blank">Comprar</a></button>
    </div>


    <div class="product-card product" data-tags="gravacao">
      <img src="https://images6.kabum.com.br/produtos/fotos/534686/ssd-externo-portatil-sandisk-1tb-usb-leitura-800mb-s-preto-e-laranja-sdssde30-1t00-g26_1716569151_g.jpg" alt="SanDisk SSD">
      <h3>SanDisk SSD Portátil de 1 TB</h3>
      <button><a href="https://amzn.to/3DTbe6d" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_713023-CBT77777392147_072024-O.webp" alt="Garra Ulanzi">
      <h3>Garra Ulanzi</h3>
      <button><a href="https://amzn.to/4hPJU7G" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://http2.mlstatic.com/D_NQ_NP_733914-CBT81039244963_112024-O.webp" alt="Suporte Osmo">
      <h3>Suporte Osmo com imã</h3>
      <button><a href="https://mercadolivre.com/sec/1QL3kHh" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://m.media-amazon.com/images/I/61gsQvs-dqL._AC_SL1000_.jpg" alt="Cartão de memória">
      <h3>Cartão de memória</h3>
      <button><a href="https://amzn.to/4rdk2HF" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="gravacao">
      <img src="https://ae-pic-a1.aliexpress-media.com/kf/S562d2c58035d4ec2933b5b26557f6271b.jpg_960x960q75.jpg_.avif" alt="Cartão de memória">
      <h3>Lente TTArtisan 27mm </h3>
      <button><a href="https://s.click.aliexpress.com/e/_c4rBtnl9" target="_blank">Comprar</a></button>
    </div>

     <div class="product-card product" data-tags="gravacao">
      <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sc006b8c9add34af39025851760bde539n.jpg_960x960q75.jpg_.avif" alt="Cartão de memória">
      <h3>Lente Viltrox 15mm F1.4 </h3>
      <button><a href="https://s.click.aliexpress.com/e/_c3wjmMa7" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="kellyn marcelo">
      <img src="https://http2.mlstatic.com/D_NQ_NP_793705-MLU75720602794_042024-O.webp" alt="Eva e Walle">
      <h3>Eva e Wall-e</h3>
      <button><a href="https://www.mercadolivre.com.br/walle-eva-boneco-action-figure-disney-pixar-8cm/p/MLB22732316#polycard_client=search-nordic&searchVariation=MLB22732316&position=42&search_layout=stack&type=product&tracking_id=26fdc8b1-17cf-4ff3-8b11-4f778dec98de&wid=&sid=search" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="corrida">
      <img src="https://assets.adidas.com/images/h_2000,f_auto,q_auto,fl_lossy,c_fill,g_auto/eadd29254c964b26ac2ebe175b8f39d5_9366/Tenis_Adizero_EVO_SL_Branco_JH6208_HM1.jpg" alt="Eva e Walle">
      <h3>Adidas Evo SL</h3>
      <button><a href="https://tidd.ly/3Wx9aGP" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="corrida">
      <img src="https://assets.adidas.com/images/h_2000,f_auto,q_auto,fl_lossy,c_fill,g_auto/e138c7d37c9e4115ad18d7628079a77d_9366/Tenis_Adizero_Adios_Pro_4_Branco_JR1094_01_00_standard.jpg" alt="Eva e Walle">
      <h3>Adidas Adios Pro 4</h3>
      <button><a href="https://tidd.ly/3M92CNl" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="corrida">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_669268-MLB105133954395_012026-F.webp" alt="Eva e Walle">
      <h3>Colete de hidratação </h3>
      <button><a href="https://mercadolivre.com/sec/2quNqCx" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="corrida">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_793133-MLA88667868937_072025-F.webp" alt="Eva e Walle">
      <h3>Garrafa Soft Flask </h3>
      <button><a href="https://mercadolivre.com/sec/1NKMB8x" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="corrida">
      <img src="https://down-br.img.susercontent.com/file/br-11134207-7r98o-mc2em3xge84n4b.webp" alt="Eva e Walle">
      <h3>Garrafa Curva </h3>
      <button><a href="https://s.shopee.com.br/2LSolzanGG" target="_blank">Comprar</a></button>
    </div>


    <div class="product-card product" data-tags="corrida">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_795287-MLU77388119283_072024-F.webp" alt="Eva e Walle">
      <h3>Óculos Mormaii Smash </h3>
      <button><a href="https://mercadolivre.com/sec/11gWsWv" target="_blank">Comprar</a></button>
    </div>


    <div class="product-card product" data-tags="corrida">
      <img src="https://decathlonstore.vtexassets.com/unsafe/fit-in/1256x1256/center/middle/https%3A%2F%2Fdecathlonpro.vtexassets.com%2Farquivos%2Fids%2F165382390%2Fpackshot-codigo-modelo-8810472.jpg%3Fv%3D638727885052500000" alt="Eva e Walle">
      <h3>Meia Poliamida </h3>
      <button><a href="https://tidd.ly/4kAcwE9" target="_blank">Comprar</a></button>
    </div>

    <div class="product-card product" data-tags="corrida">
      <img src="https://m.media-amazon.com/images/I/4199pCCm-oL._AC_SL1121_.jpg" alt="Eva e Walle">
      <h3>Shokz OpenRun Pro 2  </h3>
      <button><a href="https://amzn.to/4bVByvu" target="_blank">Comprar</a></button>
    </div>
  </div>

  <script>
    const searchInput = document.getElementById('search');
    const productCards = document.querySelectorAll('.product-card');

    searchInput.addEventListener('input', () => {
      const searchText = searchInput.value.toLowerCase().trim();

      productCards.forEach(card => {
        const productName = card.querySelector('h3').textContent.toLowerCase();
        if (productName.includes(searchText)) {
          card.style.display = 'block';
        } else {
          card.style.display = 'none';
        }
      });
    });

    const filterButtons = document.querySelectorAll('.filter-btn');
    const products = document.querySelectorAll('.product');

    filterButtons.forEach(button => {
      button.addEventListener('click', () => {
        const tag = button.getAttribute('data-tag');

        if (button.classList.contains('active')) {
          button.classList.remove('active');
          products.forEach(product => {
            product.classList.remove('hidden');
          });
        } else {
          filterButtons.forEach(btn => btn.classList.remove('active'));
          button.classList.add('active');

          products.forEach(product => {
            const productTags = product.getAttribute('data-tags').split(' ');

            if (productTags.includes(tag)) {
              product.classList.remove('hidden');
            } else {
              product.classList.add('hidden');
            }
          });
        }
      });
    });
    </script>
  </body>
</html>
