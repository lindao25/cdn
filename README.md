var pSettings = {
    progressBg: 'lightblue',
    progressBg2: 'lightblue',
    highDemandText: "Este produto está se esgotando! Não se preocupe, nós reservamos o seu pedido.",
    discountText: "Para compra no CARTÃO use o código "5DESC" nos próximos 04:36 minutos e ganhe 5% de desconto - Válido apenas com cartão de crédito
",
    whyUsImg1: 'https://i.imgur.com/TRlmrWf.png',
    whyUsTitle1: "Garantia de 30 dias ou seu dinheiro de volta",
    whyUsText1: "Se você não está satisfeito com seus produtos, nós reembolsamos toda sua compra, sem perguntas.",
    whyUsImg2: 'https://i.imgur.com/jok9IxX.png',
    whyUsTitle2: "Mais de 7.657 pedidos enviados com sucesso",
    whyUsText2: "Nós temos tantos clientes satisfeitos quanto muitos pedidos que enviamos. Junte-se a nossa família.",
}


var url4 = 'https://i.imgur.com/bXN2wKs.gif';
var ret4 = 'https://i.imgur.com/bXN2wKs.gif';
var text1 = 'ONE TIME OFFER:';
var text2 = ' We are experiencing HIGH Order Volume, why not SKIP the Processing Line? Order processing usually takes up to 3 days, but we will send yours out first! This offer DOES NOT affect actual time of shipment.';


function crC(e, t, s) { 
    if (s) {
        var n = new Date;
        n.setTime(n.getTime() + 60 * s * 1e3);
        var i = "; expires=" + n.toUTCString()
    } else i = "";
    document.cookie = e + "=" + t + i + "; path=/"
}

function rdC(e) {
    for (var t = e + "=", s = document.cookie.split(";"), n = 0; n < s.length; n++) {
        for (var i = s[n];
            " " == i.charAt(0);) i = i.substring(1, i.length);
        if (0 == i.indexOf(t)) return i.substring(t.length, i.length)
    }
    return null
}
function freeshippingimg(e){
	var shippingc = document.getElementsByClassName("section--shipping-method");
	if(shippingc.length > 0){
		document.getElementsByClassName("section--shipping-method")[0].getElementsByClassName("section__content")[0].getElementsByClassName("content-box")[0].getElementsByClassName("content-box__row")[0].insertAdjacentHTML("beforeend", '<img src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/freeshipping_2018_V2.png">');
    }
}
function eSC(e) {
    crC(e, "", -1)
}



function stTM(e, t, s) {
    var n, i, d;

    function a() {
        n = t - ((Date.now() - e) / 1e3 | 0), d = n % 60 | 0, i = (i = n / 60 | 0) < 10 ? "0" + i : i, d = d < 10 ? "0" + d : d, s.textContent = i + ":" + d, n <= 0 && (clearInterval(c), document.getElementById("countdown").innerHTML = '<div class="flame-img" style="vertical-align: middle; display: inline-block; position: relative; top: 2px;"><img src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/flame-in-cart_2018.png"></div><div style="font-weight: 700; display: inline-block; padding:0 0 0 5px">' + pSettings.highDemandText + '</div> <div>Order reservation ended.</div>', e = Date.now() + 1e3)
    }
    a();
    var c = setInterval(a, 1e3)
}
var wnd = window.location.href,
    chsg = '<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="#fff"><path d="M20.285 2l-11.285 11.567-5.286-5.011-3.714 3.716 9 8.728 15-15.285z"/></svg>';
	

wnd.indexOf("checkout") > -1 && (window.onload = function() {
	var cllass = document.getElementsByClassName("content-box__emphasis");	
	
var div1 = document.getElementsByClassName("step");
var align = div1[0].getAttribute("data-step");

var links = document.getElementsByClassName("edit_checkout");
var string = links[0].getAttribute("action");
    if (wnd.indexOf("checkout") > -1 && (dsXt = document.getElementById("checkout_reduction_code"), document.body.insertAdjacentHTML("afterbegin", '<div class="content prH7"><div class="wrap"><div class="ar64"><div class="image_contain"><div id="sp1" class="s8 s8c"><a href="/cart"><span id="spn1"><svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="#fff"><path d="M20.285 2l-11.285 11.567-5.286-5.011-3.714 3.716 9 8.728 15-15.285z"/></svg> 1.Cart</span></a></div><div id="sp2" class="s8 s8c current"><a href="'+string+'?step=contact_information" > <span id="spn2">2.Info</span></a></div><div id="sp3" class="s8"><a href="'+string+'?previous_step=contact_information&step=shipping_method"><span id="spn3"> 3.Shipping</span></a></div><div id="sp4" class="s8"><a href="'+string+'?previous_step=shipping_method&step=payment_method"><span id="spn4"> 4.Payment</span></a></div></div></div></div></div>'), -1 === wnd.indexOf("thank_you"))) 


    {if(align == 'contact_information'){document.getElementsByClassName("step__footer__continue-btn")[0].getElementsByClassName("btn__content")[0].insertAdjacentHTML("afterend", '<img class="truck-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/truck_white.png">')}
		if(align == 'shipping_method'){document.getElementsByClassName("step__footer__continue-btn")[0].getElementsByClassName("btn__content")[0].insertAdjacentHTML("afterend", '<img class="card-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/creditcard_white.png">');}	
		if(align == 'payment_method'){document.getElementsByClassName("step__footer__continue-btn")[0].getElementsByClassName("btn__content")[0].insertAdjacentHTML("afterend", '<img class="check-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_v2.png">')}
		{document.getElementsByClassName("main__content")[0].insertAdjacentHTML("afterbegin",'<div><div id="ct836" style="display:block;background:#fff5d2;padding:10px 20px;border:1px solid #fac444;font-size:14px;color:#2c2c2c;font-weight:bold;-webkit-border-radius: 5px;-moz-border-radius: 5px;border-radius: 5px; margin:5px 0px 20px 0px">No worries! We have reserved your order for the next <span id="time"></span> minutes!</div></div>');var e=600,t=Date.now(),s=rdC("pRtC");s?t<s?e=(s-t)/1e3:(eSC("pRtC"),crC("pRtC",Date.now()+1e3*e,e+1)):crC("pRtC",Date.now()+1e3*e,e+1),display=document.querySelector("#time"),stTM(t,e,display),document.getElementsByClassName("main__content")[0].insertAdjacentHTML("afterbegin",'<div style="width:100%;display:table"><div style="display:table-cell;vertical-align:middle"><img src=""></div><div style="font-weight:bold;padding-left:5px"><img src="https://i.imgur.com/PxH8NWm.gif">'+pSettings.highDemandText+"</div></div>"),""!=pSettings.discountText&&dsXt&&dsXt.setAttribute("placeholder",pSettings.discountText),document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend",'<div style="width:100%;display:block;padding-top:10px"><span style="font-size:14px;line-height:12px;font-style=italic;float:right;width:100%;text-align:right">Guaranteed safe and secure checkout!</span><img src="https://cdn.shopify.com/s/files/1/1319/2435/t/4/assets/paybadges.jpg" style="max-width:360px;float: right;margin-top: 5px;"></div>')}
		
		
		
		if (screen.width > 999) {
			if(align == 'contact_information'){document.getElementsByClassName("edit_checkout")[0].insertAdjacentHTML("beforeend",'<div class="fieldset-description emailclass" data-buyer-accepts-marketing=""><div class="section__content"><div class="checkbox-wrapper"><div class="checkbox__input"><input name="checkout[buyer_accepts_marketing]" type="hidden" value="0"><input class="input-checkbox" data-backup="buyer_accepts_marketing" type="checkbox" value="1" checked="checked" name="checkout[buyer_accepts_marketing]" id="checkout_buyer_accepts_marketing"></div><label class="checkbox__label" for="checkout_buyer_accepts_marketing">Keep me up to date on news and exclusive offers</label></div></div></div>')}				
             document.getElementsByClassName("main__content")[0].insertAdjacentHTML("afterbegin", '<p class="desktoponly" style="color:#cc0000;text-align:left;font-size:18px;margin-bottom:35px;font-weight:bold;display:none;" >Use Coupon Code "GET5NOW" to Save 5%. Click Enter Promo Code GET5NOW on Right</p><div id = "desktop" class="count__down" style="padding: 0px 0px 20px 0px;"><div id="countdown" class="countdownhere" style="font-weight:bold;padding-left:5px"> <div>We have reserved your order for <span id="time"></span> minutes! </div></div></div>');    var e = 600,
                t = Date.now(),
                s = rdC("pRtC"); 
            s ? t < s ? e = (s - t) / 1e3 : (eSC("pRtC"), crC("pRtC", Date.now() + 1e3 * e, e + 1)) : crC("pRtC", Date.now() + 1e3 * e, e + 1), display = document.querySelector("#time"), stTM(t, e, display), document.getElementsByClassName("countdownhere")[0].insertAdjacentHTML("afterbegin", '<div class="flame-img" style="vertical-align: middle; display: inline-block; position: relative; top: 2px;"><img src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/flame-in-cart_2018.png"></div><div style="font-weight: 700; display: inline-block;padding:0 0 0 5px">' + pSettings.highDemandText + "</div>"), "" != pSettings.discountText && dsXt && dsXt.setAttribute("placeholder", pSettings.discountText), document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<div class="mobile-pay-logo" style="width: 100%; display: block; padding-top: 10px; float: left; text-align: right;"></div>'), document.getElementsByClassName("order-summary__sections")[0].insertAdjacentHTML("beforeend", '<div style="position:relative;padding:10px 0px"><div style="position: relative; padding: 10px 0px; clear: both;"><div class="wyustit" style="position:relative;z-index:1;text-align:center"><span style="background:#fafafa;padding:0 15px">Why Choose Us?</span></div><div style="display:table;vertical-align:middle;width:100%;border-spacing:0px 20px"><div class="wyuscs"><div class="wyuscs1"><img src="' + pSettings.whyUsImg1 + '"></div><div class="wyuscs2"><span>' + pSettings.whyUsTitle1 + "</span><p>" + pSettings.whyUsText1 + '</p></div></div><div class="wyuscs"><div class="wyuscs1"><img src="' + pSettings.whyUsImg2 + '"></div><div class="wyuscs2"><span>' + pSettings.whyUsTitle2 + "</span><p>" + pSettings.whyUsText2 + "</p></div></div></div></div>"), document.getElementsByClassName("order-summary__sections")[0].insertAdjacentHTML("beforeend", '<div class="review_title"></div><div style="position:relative;padding:10px 0px">');	
            		
        } else {
			 if(align == 'contact_information'){document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<button aria-busy="false" class="step__footer__continue-btn btn below_btn" type="submit" name="button"><span class="btn__content">Continue to shipping method <img class="truck-img" src="https://cdn.shopify.com/s/files/1/2219/3745/files/truck_white.png?8391851278287959352"></span><i class="btn__spinner icon icon--button-spinner"></i></button>'),document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("beforeend",'<div class="fieldset-description emailclass" data-buyer-accepts-marketing=""><div class="section__content"><div class="checkbox-wrapper"><div class="checkbox__input"><input name="checkout[buyer_accepts_marketing]" type="hidden" value="0"><input class="input-checkbox" data-backup="buyer_accepts_marketing" type="checkbox" value="1" checked="checked" name="checkout[buyer_accepts_marketing]" id="checkout_buyer_accepts_marketing"></div><label class="checkbox__label" for="checkout_buyer_accepts_marketing">Keep me up to date on news and exclusive offers</label></div></div></div>')}
			 if(align == 'shipping_method'){document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<button aria-busy="false" class="step__footer__continue-btn btn below_btn" type="submit" name="button"><span class="btn__content">Continue to payment method</span><img class="card-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/creditcard_white.png"><i class="btn__spinner icon icon--button-spinner"></i></button>');
			 }
			 if(align == 'payment_method'){document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<button aria-busy="false" class="step__footer__continue-btn btn below_btn" type="submit" name="button"><span class="btn__content">Complete order</span><img class="check-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_v2.png"><i class="btn__spinner icon icon--button-spinner"></i></button>')}
            document.getElementsByClassName("main__content")[0].insertAdjacentHTML("afterbegin", '<p class="mobileonly" style="color:#cc0000;font-size:18px;margin-bottom:35px;font-weight:bold;display:none">Use Coupon Code GET5NOW to Save 5%. Click Enter Promo Code Above</p>');	
			document.getElementsByClassName("order-summary-toggle")[0].insertAdjacentHTML("beforebegin", '<div id = "mobile" class ="outer_count_div count__down"><div id="countdown" class="countdownhere" style="font-weight:bold;padding-left:5px"> <div>We have reserved your order for <span id="time"></span> minutes! </div></div></div>');
            var e = 600,
                t = Date.now(),
                s = rdC("pRtC");
			 s ? t < s ? e = (s - t) / 1e3 : (eSC("pRtC"), crC("pRtC", Date.now() + 1e3 * e, e + 1)) : crC("pRtC", Date.now() + 1e3 * e, e + 1), display = document.querySelector("#time"), stTM(t, e, display), document.getElementsByClassName("countdownhere")[0].insertAdjacentHTML("afterbegin", '<div class="flame-img"><img src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/flame-in-cart_2018.png"></div><div style="font-weight: 700; display: inline-block;padding:0 0 0 0">' + pSettings.highDemandText + "</div>"), "" != pSettings.discountText && dsXt && dsXt.setAttribute("placeholder", pSettings.discountText),document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<div class="review_title"></div><div class="wyustit" style="position:relative;z-index:1;text-align:center; margin:0 0 10px 0;"></div>'), document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<div style="position: relative; padding: 10px 0px; clear: both;" class="why_us"><div class="wyustit" style="position:relative;z-index:1;text-align:center"><span style="background:#fafafa;padding:0 15px">Why Buy From Us?</span></div><div style="display:table;vertical-align:middle;width:100%;border-spacing:0px 20px"><div class="wyuscs"><div class="wyuscs1"><img src="' + pSettings.whyUsImg1 + '"></div><div class="wyuscs2"><span>' + pSettings.whyUsTitle1 + "</span><p>" + pSettings.whyUsText1 + '</p></div></div><div class="wyuscs"><div class="wyuscs1"><img src="' + pSettings.whyUsImg2 + '"></div><div class="wyuscs2"><span>' + pSettings.whyUsTitle2 + "</span><p>" + pSettings.whyUsText2 + "</p></div></div></div></div>"), document.getElementsByClassName("step__footer__continue-btn")[0].insertAdjacentHTML("afterend", '<div class="mobile-pay-logo" style="width: 100%; display: block; padding-top: 10px; float: left; text-align: right;"></div>');
        }
    }	

b1j = document.getElementById("sp1"), b2j = document.getElementById("sp2"), b3j = document.getElementById("sp3"), b4j = document.getElementById("sp4"),c1j = document.getElementById("spn1"), c2j = document.getElementById("spn2"), c3j = document.getElementById("spn3"), c4j = document.getElementById("spn4"),c2=document.getElementById("sp2"),c3=document.getElementById("sp3"),c4=document.getElementById("sp4"),wnd.indexOf("step=contact_information") > -1 && (b1j.className = "s8 s8c", c2.className="s8 s8c current"), wnd.indexOf("previous_step=contact_information") > -1 && (b1j.className = "s8 s8c", b2j.className = "s8 s8c",  c3.className="s8 s8c current", c2j.insertAdjacentHTML("afterbegin", chsg)), wnd.indexOf("previous_step=shipping_method") > -1 && (b1j.className = "s8 s8c", b2j.className = "s8 s8c", b3j.className = "s8 s8c", b4j.className = "s8 s8c", c4.className="s8 s8c current", c2j.insertAdjacentHTML("afterbegin", chsg), c3j.insertAdjacentHTML("afterbegin", chsg)), wnd.indexOf("thank_you") > -1 && (b1j.className = "s8 s8c", b2j.className = "s8 s8c", b3j.className = "s8 s8c",b4j.className = "s8 s8c" ,c4j.insertAdjacentHTML("afterbegin", chsg))
}); 

var b7 = document.createElement("style");
b7.type = "text/css";
b7.innerHTML = '#gift-link > a {cursor: pointer;  text-decoration: underline;color: #ff0000;}.section--contact-information .section__content {margin-bottom: 5px;} div[data-address-field="address2"]{width:100% !important;}.section--contact-information .fieldset-description ,.section--shipping-address .section__header , .section--contact-information .section__header p.layout-flex__item{display:none !important;}.sidebar .order-summary-tittle .order-summary-toggle__icon-wrapper {display: inline-block;font-size: 22px;padding-right: 10px;vertical-align: middle;}.section--shipping-address{padding:0;}#apt-suit a{cursor:pointer;}#apt-suit i{margin-right: 5px;}.emailclass{float:right;width:59%;text-align:right}.section--shipping-address  .section__content , .step__sections{position:relative;}div[data-address-field="address1"]{width:100% !important;}div[data-address-field="phone"]{width: 66%;    float: right;}div[data-address-field="zip"]{width:34% !important;    position: absolute;bottom: 59px;}div[data-address-field="city"]{margin-left: 33%;} div[data-address-field="city"] , div[data-address-field="province"] , div[data-address-field="country"]{width:33.33% !important;} div[data-address-field="country"]{position:absolute;width: 34% !important;bottom:0;} .section--reductions {  display: none;} .main ul.breadcrumb{display:none!important}.content.prH7{padding:8px 0}.ar64{width:100%;}.ar64 .s8{font-size:14px;text-align:center;color:#fff;cursor:default;margin:0 3px;padding:9px 10px 9px 30px;float:left;position:relative;background-color:#0083ff82 ;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;transition:all 2s ease;width:20.8%;    border: 2px solid;border-left: 0;border-right: 0;}.ar64 .s8:first-child{margin-left:0;border-top-left-radius:4px;border-bottom-left-radius:4px}.ar64 .s8 span{position:relative}.ar64 .bordertop .s8.s8c{background-color:#00ce25}.ar64 .s8.s8c{color:#fff;background:#0083ff;}.ar64 .s8.s8c.current{background-color: #0083ff;box-shadow: 0px 11px 8px -10px #23468c, 0px -11px 8px -10px #23468c;border: 2px solid #58c440;border-left: 0;border-right: 0;}.ar64 .s8 a{display:block;color:#ffffff;}.ar64 .s8:after,.ar64 .s8:before{content:" ";position:absolute;top:0;right:-17px;width:0;height:0;border-top:19px solid transparent;border-bottom:17px solid transparent;border-left:17px solid #0083ff82 ;z-index:2;transition:border-color .2s ease}.ar64 .s8:before{right:auto;left:0;border-left:17px solid #fff;z-index:0}.ar64 .s8:first-child:before{border:none}.ar64 .s8:first-child{margin-left:0;border-top-left-radius:4px;border-bottom-left-radius:4px}.ar64 .s8 span{position:relative}.ar64 .s8.s8c{color:#fff;background-color:#0083ff}.ar64 .s8.s8c:after{border-left:17px solid #0083ff}.ar64 .s8.s8c.current:after {border-left: 17px solid #0083ff;} .content{overflow: visible;}.order-summary__sections {display:block; height: auto;} .sidebar{background: #fafafa none repeat scroll 0 0;border-left: 1px solid #e1e1e1;padding-left: 2%;padding-right: 2%; width: 42%; -webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;  } .sidebar::after{display: none;} .btn {box-shadow: 0px 4px 8px #80808082; font-size: 16px; border-radius: 4px;}#countdown > div {display: inline;font-size: 12px !important;color: #000000;}.review_title > img {width: 52px; margin: 0 auto; display:table;}.review_title > span {color: #666 !important;float: right;font-weight: 700;margin-right: 163px;margin-top: 11px;} .reviews {margin: 0 0 10px;}.btn:hover {opacity: 0.82;}.step__footer__continue-btn.btn {min-width: 320px;padding: 1.4em 30px;}.step__footer__continue-btn span.btn__content{  position: relative;font-weight:600;}.total-line-table__tbody img.qualify_shipping {padding: 10px 0 0;width: 100%;}#countdown{background: #fcf8e3;border: 1px solid #f1c55c;padding: 6px 0px;border-radius: 4px;} .ar64 .s8 svg{position:absolute;left:-17px;top:2px;fill: #58c440;}.ar64 .s8:first-child svg{left:-16px}.wyustit:before{border-top:1px solid #dfdfdf;content:"";margin:0 auto;position:absolute;top:50%;left:0;right:0;bottom:0;width:100%;z-index:-1} .wyuscs{display:block;padding-bottom:20px}.wyuscs1,.wyuscs2{display:inline-block;vertical-align:middle}.wyuscs1{width:16%;font-size:15px;padding:0 10px 0 0;}.wyuscs2{width:80%}.wyuscs2 span{font-size:14px;font-weight:700;color:#666}.wyuscs2 p{font-size:12px;color:#777}.step__footer__continue-btn span.btn__content::after{position:static;line-height:10px;} .payment_logo{margin-top: 5px; max-width: 308px; min-width: 308px; width: 100%; } .reviews-button{ width: 100%; cursor: auto; padding: 0px !important;} .reviews-button a{padding: 1.4em 3.7em; display: block; color: rgb(255, 255, 255); font-size: 16px;} .reviews-button a span { font-weight: 600; position: relative; } .reviews-button a span::after{ color: #fff; line-height: 10px;content: "";font-family: "Avant Garde",Avantgarde,"Century Gothic",CenturyGothic,"AppleGothic",sans-serif;font-size: 27px;padding-left: 5px;position: static;vertical-align: sub; } .step__footer__continue-btn.btn img{width: 32px; display: inline-block; vertical-align: middle; position: relative; top: -1px; margin: 0px 0px 0px 5px; } .step__footer__continue-btn.btn img.check-img { width: 16px; }.tags-list{float: none !important;}                                                                                                             .content-box{border:0;} .section__content .content-box {border:0;border-radius:0;}.content-box__row{ border:1px solid #d9d9d9;border-radius: 4px;} .pais-shipping {background: #fcf8e3 none repeat scroll 0 0;border: 1px dashed #d9d9d9 !important; margin: 15px 0 0;padding: 10px;}.pais-shipping .radio-wrapper {background: #ffff99 none repeat scroll 0 0;color: #009900;font-size: 14px;font-weight: bold;padding: 10px 6px;text-align: left; margin: 0 0 10px; }.pais-shipping .radio-wrapper .radio__input {padding-right:30px;display: inline-block;vertical-align: top;}.pais-shipping .radio-wrapper .radio__input input.input-radio {margin: 0;}.pais-shipping .radio-wrapper .radio__label .radio__label__accessory{} .pais-shipping .radio-wrapper img.pais-shipping-img {display: inline-block;height: 21px;margin: 1 10px 0 0;vertical-align: top;width: auto;}.pais-shipping .radio-wrapper input {margin: 0 15px 0 0;}.pais-shipping > p {color: #000;font-size: 14px;}.pais-shipping p span {color: #ce3b0a;font-weight: bold;text-decoration: underline;}                                             @media(min-width:2559px){.content.prH7{display:table;}}      @media(min-width:450px){.ar64 .s8 svg{position:relative!important;top:2px!important;right: 2px!important;}}@media(max-width:750px){.ar64 .s8{font-size:11px}.ar64 .s8:first-child{padding-left:20px}}@media only screen and (max-width: 1024px){.step__footer__continue-btn.btn {padding: 1.4em 10px;}.ar64 .s8{width:19.8%}.s8 img{left: 25%;}.emailclass{    width: 72%;}}@media(min-width:769px){label[for="checkout_shipping_address_phone"]{padding-left:50px !important;}}                                                                                @media only screen and (max-width: 999px){ .emailclass{display:none !important;}.mobile-pay-logo{display:none !important;} .why_us{display:none !important;}.wyustit{display:none !important;}.reviews{display:none !important;}.below_btn{display:none !important;}a.step__footer__previous-link.ret_cont {position: initial !important;}  #countdown {height: 60px;margin: 0 auto;width: 100%; max-width:38em; text-align: center !important; padding: 10px 5px 10px 35px !important; -webkit-box-sizing: border-box;  -moz-box-sizing:border-box; box-sizing:border-box; position:relative;} #countdown .flame-img {left: 5px !important; position: absolute !important; top: 14px !important; width: auto !important; } #countdown > div {text-align: left !important; float: left; width: 100%;padding: 0 !important;}.sidebar {overflow: hidden;  padding-left: 2%;  padding-right: 2%;border-right: 1px solid #e1e1e1; width: 100%; } .outer_count_div{ padding: 0px 1em 20px;} .step__footer__previous-link, .step__footer__info {clear: both;display: block;margin: 0 0 15px; padding: 15px 0 0 !important; }	.step__footer__continue-btn.btn {min-width: 100%;} .anyflexbox .step__footer{display: block;} .payment_logo { display: table;margin: 5px auto 0; width: auto;} .anyflexbox .step__footer__previous-link, .anyflexbox .step__footer__info { display: table;float: none;margin: 0 auto 20px; } .ar64 .s8 { font-size:14px;}.emailclass{    float: left;    width: 63%;}.sidebar .order-summary-tittle {color: #197bbd;margin: 15px 0 10px;} }                                                                                                                             @media only screen and (max-width: 768px){                                                                                   body{ width:100%;} .content {display: block !important;overflow: hidden !important;width: 100%;} .review_title > img {padding: 0 0 10px;}.review_title > span {margin-right: 265px;margin-top: 17px;}.btn { padding: 1.4em 2.6em;}  .step__footer__continue-btn span.btn__content::after{position:static;line-height:14px;}  .wyustit > span{ background: #dfdfdf none repeat scroll 0 0 !important;display: block;margin: 0 0 20px;padding: 5px 10px !important;position: relative; } .wyustit > span::after {top: 100%;left: 50%;border: solid transparent;content: " ";height: 0;width: 0;position: absolute;pointer-events: none;border-color: rgba(223, 223, 223, 0);border-top-color: #dfdfdf;border-width: 10px;margin-left: -10px;}div[data-address-field="first_name"] , div[data-address-field="last_name"]{width:100% !important;} div[data-address-field="country"]{width:38% !important;} div[data-address-field="phone"]{width:65% !important;}#checkout_shipping_address_phone{    padding-left: 30px !important;}label[for="checkout_shipping_address_phone"]{padding-left: 30px !important;}}                                                                                                                             @media only screen and (max-width: 749px){                                                                             .payment_logo {max-width: 100%;min-width: 100%;}  .ar64 .s8{font-size:12px}  }                                                                                                                         @media only screen and (max-width: 480px){.emailclass{float:left;width:100%;text-align:left;position: relative;bottom: 115px;}.mobile-pay-logo{position: relative;top:15px;}.review_title > span {margin-right: 189px !important; margin-top: 35px !important; }  .content .wrap{  padding: 0;} .content .wrap .main {padding-left: 10px;padding-right: 10px;padding-top: 1.5em;} .ar64 { -webkit-box-sizing: border-box;  -moz-box-sizing:border-box; box-sizing:border-box; padding: 0 10px; width: 100%;  } .s8 img{left: 7%;} .ar64 .s8 svg{position:absolute;left:-14px;top:1px;fill: #58c440;} .ar64 .s8 span {position: relative;right: -13px;}                                                 }                                                                                                                                                                                                                                          @media only screen and (max-width: 399px){                                                                               .ar64 > .s8 {font-size: 11px;height: 48px;padding: 5px;} .ar64 > #sp1.s8 {padding-left: 15px;padding-right: 15px; } .pais-shipping {padding: 12px;} .pais-shipping .radio-wrapper {padding: 10px 4px;} }                                                                                                                       @media only screen and (max-width: 360px){                                                                                 .review_title > span {margin-right: 95px !important;margin-top: 30px !important;}.btn {padding: 1.4em 30px 1.4em 10px;} .step__footer__continue-btn.btn {min-width: 100%;}.s8 img{left:0;}  }                                                                                                                        @media only screen and (max-width: 320px){                                                                                 .review_title > span {margin-right: 67px !important;margin-top: 19px !important;}#countdown > div {font-size: 11px !important;} .step__footer__continue-btn.btn {padding: 1.4em 0px;}   } .field__input{background-repeat: no-repeat;background-attachment: scroll;background-size: 20px 20px;background-position: 98% 50%;cursor: auto;} #__lpform_checkout_email{display: none !important}.field__input.field__input--select{background-position: 75% 50% !important;}@media only screen and (max-width: 767px){.ret_cont{top: 20px !important;position: relative;}}@media only screen and (max-width: 480px){.ar64 .s8{font-size: 10px;width: 20%;padding: 2px 7px;margin: 0 3px;}.ar64 .s8:before{right: -12px;left: 0;   border-left: 12px solid #fff;z-index: 0;border-top: 12px solid transparent;border-bottom: 12px solid transparent;}.ar64 .s8:after {right: -12px !important;border-top: 11px solid transparent;border-bottom: 11px solid transparent;border-left: 12px solid #878787;}.ar64 .s8:first-child {padding-left: 0px !important;}}@media only screen and (max-width: 410px){.ar64 .s8{width: 19%;}}.iconimg {position: absolute;width: 25px;z-index: 1;top: 10px;left: 10px;}#checkout_shipping_address_phone, #checkout_shipping_address_address1, #checkout_email, #checkout_shipping_address_first_name, #checkout_shipping_address_last_name {position: relative;padding-left: 50px;}div[data-address-field="phone"] .iconimg {height: 27px; width: auto; top: 8px;}label[for="checkout_email"], label[for="checkout_shipping_address_last_name"], label[for="checkout_shipping_address_address1"],  label[for="checkout_shipping_address_first_name"] { padding-left: 50px !important;}.alt-payment-list-container, .alternative-payment-separator{display:none !important;}.count__down{display:none !important;}';
document.body.appendChild(b7);
var head = document.getElementsByTagName('head')[0];
   var script = document.createElement('script');
   script.type = 'text/javascript';
   script.src = "https://code.jquery.com/jquery-2.2.1.min.js";
   script.onreadystatechange = handler;
   script.onload = handler;
   head.appendChild(script);
      var script1 = document.createElement('script');
  script1.type = 'text/javascript';
  script1.src = "https://code.jquery.com/jquery-2.2.1.min.js";
  script1.onreadystatechange = on_change;
  script1.onload = on_change;
  head.appendChild(script1);
   var script2 = document.createElement('script');
  script2.type = 'text/javascript';
  script2.src = "https://code.jquery.com/jquery-2.2.1.min.js";
  script2.onreadystatechange = on_remove;
  script2.onload = on_remove;
  head.appendChild(script2); 
   
   
    function all_script(){
		var div1 = document.getElementsByClassName("step");
		var align = div1[0].getAttribute("data-step");
		if(align == 'contact_information'){document.getElementsByClassName("step__footer__continue-btn")[0].getElementsByClassName("btn__content")[0].insertAdjacentHTML("afterend", '<img class="truck-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/truck_white.png">')}
		if(align == 'shipping_method'){document.getElementsByClassName("step__footer__continue-btn")[0].getElementsByClassName("btn__content")[0].insertAdjacentHTML("afterend", '<img class="card-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/creditcard_white.png">');}	
		if(align == 'payment_method'){document.getElementsByClassName("step__footer__continue-btn")[0].getElementsByClassName("btn__content")[0].insertAdjacentHTML("afterend", '<img class="check-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_v2.png">')}
		if (screen.width > 999) {
			if(align == 'contact_information'){document.getElementsByClassName("edit_checkout")[0].insertAdjacentHTML("beforeend",'<div class="fieldset-description emailclass" data-buyer-accepts-marketing=""><div class="section__content"><div class="checkbox-wrapper"><div class="checkbox__input"><input name="checkout[buyer_accepts_marketing]" type="hidden" value="0"><input class="input-checkbox" data-backup="buyer_accepts_marketing" type="checkbox" value="1" checked="checked" name="checkout[buyer_accepts_marketing]" id="checkout_buyer_accepts_marketing"></div><label class="checkbox__label" for="checkout_buyer_accepts_marketing">Keep me up to date on news and exclusive offers</label></div></div></div>')}				
            document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<div class="mobile-pay-logo" style="width: 100%; display: block; padding-top: 10px; float: left; text-align: right;"></div>');	
            		
        } else {
			 if(align == 'contact_information'){document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<button aria-busy="false" class="step__footer__continue-btn btn below_btn" type="submit" name="button"><span class="btn__content">Continue to shipping method <img class="truck-img" src="https://cdn.shopify.com/s/files/1/2219/3745/files/truck_white.png?8391851278287959352"></span><i class="btn__spinner icon icon--button-spinner"></i></button>'),document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("beforeend",'<div class="fieldset-description emailclass" data-buyer-accepts-marketing=""><div class="section__content"><div class="checkbox-wrapper"><div class="checkbox__input"><input name="checkout[buyer_accepts_marketing]" type="hidden" value="0"><input class="input-checkbox" data-backup="buyer_accepts_marketing" type="checkbox" value="1" checked="checked" name="checkout[buyer_accepts_marketing]" id="checkout_buyer_accepts_marketing"></div><label class="checkbox__label" for="checkout_buyer_accepts_marketing">Keep me up to date on news and exclusive offers</label></div></div></div>')}
			 if(align == 'shipping_method'){document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<button aria-busy="false" class="step__footer__continue-btn btn below_btn" type="submit" name="button"><span class="btn__content">Continue to payment method</span><img class="card-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/creditcard_white.png"><i class="btn__spinner icon icon--button-spinner"></i></button>');
			 }
			 if(align == 'payment_method'){document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<button aria-busy="false" class="step__footer__continue-btn btn below_btn" type="submit" name="button"><span class="btn__content">Complete order</span><img class="check-img" src="https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_v2.png"><i class="btn__spinner icon icon--button-spinner"></i></button>')}
           document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<div class="review_title"></div><div class="wyustit" style="position:relative;z-index:1;text-align:center; margin:0 0 10px 0;"></div>'), document.getElementsByClassName("step__footer")[0].insertAdjacentHTML("afterend", '<div style="position: relative; padding: 10px 0px; clear: both;" class="why_us"><div class="wyustit" style="position:relative;z-index:1;text-align:center"><span style="background:#fafafa;padding:0 15px">Why Buy From Us?</span></div><div style="display:table;vertical-align:middle;width:100%;border-spacing:0px 20px"><div class="wyuscs"><div class="wyuscs1"><img src="' + pSettings.whyUsImg1 + '"></div><div class="wyuscs2"><span>' + pSettings.whyUsTitle1 + "</span><p>" + pSettings.whyUsText1 + '</p></div></div><div class="wyuscs"><div class="wyuscs1"><img src="' + pSettings.whyUsImg2 + '"></div><div class="wyuscs2"><span>' + pSettings.whyUsTitle2 + "</span><p>" + pSettings.whyUsText2 + "</p></div></div></div></div>"), document.getElementsByClassName("step__footer__continue-btn")[0].insertAdjacentHTML("afterend", '<div class="mobile-pay-logo" style="width: 100%; display: block; padding-top: 10px; float: left; text-align: right;"></div>');
           
        }
					var x = document.getElementById("myScript").src;
					var head = document.getElementsByTagName('head')[0];
					var awesome_script = document.createElement('script');
					awesome_script.setAttribute('src',x); 
					awesome_script.setAttribute('id','myScript');  
					document.head.appendChild(awesome_script);
	}
	
   
       function on_change(){
   $('.field__input-btn-wrapper button.field__input-btn.btn').click(function(){
      setTimeout(function(){
      if($(".applied-reduction-code").length > 0 || $("#error-for-reduction_code").is(':visible') || $(".tags-list").is(':visible')){
          all_script();
        }
      
        
      }, 3000);
      });
   
 }
  function on_remove(){
    setTimeout(function(){
      if($(".total-line").hasClass("total-line--reduction")){
        $('.applied-reduction-code__clear-button').attr("onclick" , "remove_discount()");
        $('.tags-list .tag__button').attr("onclick" , "remove_discount()");
      }
    }, 1500);
   
  }
 function remove_discount(){
	setTimeout(function(){
				if(!$('.total-line').hasClass("total-line--reduction")){
					all_script();
				}
		}, 3000);
}
	function handler(){ 
		$('.section--contact-information .section__header h2#main-header').text("Contact Information");
		var div1 = $('.step');
	  var align = div1[0].getAttribute("data-step");
	  if(align == "contact_information"){$(".step__footer__previous-link").addClass("ret_cont");}
	  $('#checkout_email').attr("tabindex" , "1");
	  $('#checkout_shipping_address_last_name').attr("tabindex" , "2");
	  $('#checkout_shipping_address_address1').attr("tabindex" , "3");
	  $('#checkout_shipping_address_zip').attr("tabindex" , "4");
	  $('#checkout_shipping_address_city').attr("tabindex" , "5");
	  $('#checkout_shipping_address_province').attr("tabindex" , "6");
	  $('#checkout_shipping_address_country').attr("tabindex" , "7");
	  $('#checkout_shipping_address_phone').attr("tabindex" , "8");
	  if($('#checkout_reduction_code').val() == ""){
	  $('.order-summary__section--discount > .edit_checkout').hide();
	   $('.order-summary__section--discount').prepend('<div  id="gift-link" style="margin:10px 0;"><a>Enter Promo Code</a></div>');
	  }
	//  $('.section--shipping-address div[data-address-field="first_name"]').hide();
	  $( 'div[data-section="customer-information"] .fieldset-description' ).empty();
	//  $('div[data-address-field="province"] .field__input-wrapper--select').empty();
	 
	 // $( ".section--contact-information" ).find(".section__header").hide();
	 // $( ".section--shipping-address .section__content" ).prepend( $( ".section--contact-information" ) );
	  $('#gift-link').click(function(){
		 $('.order-summary__section--discount .edit_checkout').show();
	  });
	  //$(".order-summary-toggle").trigger('click');
      window.setInterval(function(){
       if($('body > div:nth-child(5) > div > div.main > div.main__header > div').is(':visible')){
       $('body > div:nth-child(5) > div > div.main > div.main__header > div').hide();
	   $('.googlepay--short').hide();
	   $('.paypal-button-container').hide();
	   $('.gpay-iframe').hide();
	   $('xcomponent-component-frame').hide();
       }
       }, 500);
	  if($(window).width() < 768)
      {
      $(".order-summary__section--discount").wrap("<div class='wrapdiscountcode' style='text-align:center;padding-left: 3%;padding-right: 3%'></div>");
      $(".order-summary__sections").append($(".wrapdiscountcode"));
      }
	  $('div[data-address-field="address2"] .field__input-wrapper').hide();
	  $('div[data-address-field="address2"]').prepend('<div  id="apt-suit" style="margin:10px 0;"><a><i class="fa fa-plus-circle" aria-hidden="true"></i>Add Address line 2</a></div>');
	  $('#apt-suit').click(function(){
		  $(this).hide();
		 $('div[data-address-field="address2"] .field__input-wrapper').show();
	  });
	 
	 function is_int(value) {
	if ((parseFloat(value) == parseInt(value)) && !isNaN(value)) {
	return true;
	} else {
	return false;
	}
	}
	$("#checkout_email").parent(".field__input-wrapper").prepend("<img class='iconimg' src='https://cdn.shopify.com/s/files/1/2410/1661/files/email_f1b217db-4295-4184-80b7-815a548404bb.png?5692581827620478311'>");
	
	$("#checkout_shipping_address_last_name").parent(".field__input-wrapper").prepend("<img class='iconimg' src='https://cdn.shopify.com/s/files/1/2410/1661/files/UserName_05c9a45d-2290-49cc-b9d6-638a641ec6ed.png?5692581827620478311'>");
	
	$("#checkout_shipping_address_first_name").parent(".field__input-wrapper").prepend("<img class='iconimg' src='https://cdn.shopify.com/s/files/1/2410/1661/files/UserName_05c9a45d-2290-49cc-b9d6-638a641ec6ed.png?5692581827620478311'>");
	
	$("#checkout_shipping_address_address1").parent(".field__input-wrapper").prepend("<img class='iconimg' src='https://cdn.shopify.com/s/files/1/2410/1661/files/Address_464d3622-2aca-4f0f-a785-401075159415.png?5692581827620478311'>");
	
	$("#checkout_shipping_address_phone").parent(".field__input-wrapper").prepend("<img class='iconimg' src='https://cdn.shopify.com/s/files/1/2410/1661/files/Phone_76cc3ea1-4c3b-4f87-818f-4e3f071de386.png?5692581827620478311'>");
	
	
	
	$("#checkout_email").attr('style','');
	$(".edit_checkout .field__input").keyup(function() {
		var cc= $(this).attr('id');
		if(cc == "checkout_email"){
			$(this).attr('style','');		
		}
		$(this).css("background-image","url()");
		
	});
	$(".edit_checkout .field__input").blur(function(){
		var cc= $(this).attr('id');
		if(cc == "checkout_email"){
			$(this).attr('style','');
		}
		$(this).css("background-image","url()");
		if($(this).val() != ""){
			$(this).css("background-image","url(https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_green.png?12635021452053642021)");
		}
	});
	
	
	
	 $("#checkout_shipping_address_zip").keyup(function() {

  // Cache
  var el = $(this);
  // Did they type five integers?
  if ((el.val().length == 5) && (is_int(el.val()))) {

    // Call Ziptastic for information
    $.ajax({
      url: "https://zip.getziptastic.com/v2/US/" + el.val(),
      cache: false,
      dataType: "json",
      type: "GET",
      success: function(result, success) {
         console.log("success");
        $("#checkout_shipping_address_city").val(result.city);

        $("#checkout_shipping_address_province").val(result.state);
		
		$("#checkout_shipping_address_city").css("background-image","url(https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_green.png?12635021452053642021)");
		
		$("#checkout_shipping_address_province").css("background-image","url(https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_green.png?12635021452053642021)");
		
		$("#checkout_shipping_address_country").css("background-image","url(https://cdn.shopify.com/s/files/1/0024/5442/1563/files/tick_green.png?12635021452053642021)");

       // $(".fancy-form div > div").slideDown();

        $("#checkout_shipping_address_zip").blur();
        $("#checkout_shipping_address_phone").show().focus();

      },
      error: function(result, success) {

       // $(".zip-error").slideDown(300);
       console.log("error");  
      }
       
    });

  } else if (el.val().length < 5) {
   // $(".zip-error").slideUp(200);
    console.log("fail");
  };

});
}
