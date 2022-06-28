# usom-blacklist

Malicious addresses are constantly added to the USOM's list of malicious addresses. Even if there is an address that is no longer accessible, it will not be deleted from the list! It is a suitable list for address-based blocking.

If DNS-based blocking is done with inaccessible addresses, this long list is read for comparison with each incoming DNS query. Therefore, it unnecessarily consumes the processing power and memory of the DNS server. It also causes increased DNS response times and decreased performance.

This repository has been created to create and use new blocklists by periodically checking the accessible addresses of the USOM list and is scheduled to be updated weekly.

## Latest check-usom-list output

Last modified : 2022-06-28 04:44:49 

```
[fuat@fortress ~]$ git clone https://github.com/fuatboluk/usom-blacklist.git
Cloning into 'usom-blacklist'...
remote: Enumerating objects: 31, done.
remote: Counting objects: 100% (31/31), done.
remote: Compressing objects: 100% (30/30), done.
remote: Total 31 (delta 12), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (31/31), done.
[fuat@fortress ~]$ cd usom-blacklist/
[fuat@fortress usom-blacklist]$ ./check-usom-list 

Start time      : 03:44:19
Description     : USOM malicious ip addresses and domains blacklist!
Original url    : https://www.usom.gov.tr/url-list.txt


## Listing all active malicious domains...

  Connected     : a2zcentre.com
  Not connected : a2zwebit.com
  Not connected : a4animation.com
  Not connected : a4handyservice.de
  Not connected : aaabulbandlighting.com
  Connected     : aaaglobalint.com
  Connected     : aacca.com.pk
  Connected     : aafh.org
  Connected     : aahung.org
  Connected     : aaidas.com
  Connected     : aairveerz.com
  Connected     : aalanguageservices.eu
  Connected     : aalens.net
  Connected     : aamirgroup.com.pk
  Not connected : aamirinternational.com
  Not connected : aamirshahzad.net
  Connected     : aandacompany.com
  Not connected : aandhconsultants.com
  Not connected : aapetstore.com
  Connected     : aarchimylove.com
  Not connected : aaspex.com
  Connected     : aatravelexperts.com
  Connected     : aazbs.com
  Not connected : abadleabantu.co.za
  Connected     : abagnale.org
  Not connected : abanganifunerals.co.za
  Connected     : abbashub.com
  Not connected : abbasiwelfare.org
  Connected     : abbeyrichard.com
  Not connected : abbottabadschool.com
  Connected     : ab-building.com
  Not connected : abbyblackart.com
  Not connected : abcsave.info
  Connected     : abdullahandco.com
  Not connected : abdullahsleather.com
  Not connected : abdulmannan.com.pk
  Connected     : abeehatech.com
  Not connected : abelka.in
  Connected     : abeonatravel.ge
  Not connected : aberdarehorticulture.com
  Connected     : abies.co.za
  Connected     : abirsove.com
  Not connected : ablasia-silver.com
  Not connected : ablazasolution.com
  Not connected : ablicointernational.com
  Not connected : aboserver.xyz
  Connected     : abosict.nl
  Not connected : abosolutelyvindictive.com
  Not connected : aboutbodybuildingworkout.com
  Connected     : aboutduvetcovers.com
  Connected     : aboutephesus.com
  Connected     : aboutswiss.ch
  Connected     : abovepromo.com
  Connected     : ab-photography.de
  Not connected : abrahamseed.co.za
  Connected     : absfinancialplanning.co.za
  Connected     : abshipscompany.com
  Connected     : absolutekerry.com
  Connected     : ab-studio.uk
  Not connected : abvsecurity.co.za
  Connected     : acaciainvestigations.com
  Not connected : academiadz.net
  Not connected : academiafirst.co.uk
  Connected     : academi.bike
  Connected     : academicwritingbrokers.com
  Connected     : academy-khi.com
  Connected     : academyla.store
  Not connected : acbtronicscorp.com
  Connected     : accc.planso.de
  Not connected : accesototalinghseq.com
  Not connected : accessyouraudience.com
  Not connected : accountancyinsider.com
  Not connected : accountexpro.com
  Connected     : accountingformanagement.org
  Not connected : accountingpulpit.com
  Connected     : accuratescaleplus.com
  Not connected : acdm.online
  Not connected : acer-parts.co.za
  Connected     : achanesman.com
  Connected     : achatcommercefloride.com
  Connected     : achimugu.com
  Not connected : acikdeniz.deniz-tr.me
  Connected     : acmecepl.com
  Connected     : acmemultan.com
  Not connected : aconpump.com
  Connected     : acorncontentcreation.com
  Not connected : acquiremnml.com
  Not connected : acsroyale.com
  Connected     : actbuildchange.com
  Connected     : actforchange.biz
  Connected     : actionloaded.com
  Not connected : activemedia.network
  Not connected : activesnowlife.com
  Connected     : activistasconstructivos.org
  Not connected : actualperception.com
  Connected     : acu.city
  Connected     : acucon.net
  Connected     : acupuncturestaffs.com
  Connected     : acupunturanatural.com
  Not connected : ad7.com.pk
  Connected     : adaliprefabrik.com
  Connected     : adambaluch.ae
  Connected     : adam-hen.com
  Not connected : adampender.com
  Not connected : adamroberts.eu
  Not connected : adamsadilek.com
  Connected     : addictdkp.com
  Not connected : addikdugratis.ca
  Not connected : addmazon.com
  Not connected : addorg.org
  Connected     : addrealbass.com
  Connected     : addsaintgaudens.com
  Connected     : addysworld.com
  Connected     : adelane-solutions.com
  Connected     : adhdaware.org.uk
  Not connected : adiliqbal.com.pk
  Not connected : adinehac.ir
  Connected     : adioslabs.in
  Connected     : adjdigital.com
  Not connected : adknivesindustry.com
  Connected     : adlabgames.com
  Not connected : adlucia.com
  Not connected : adminpc.ru
  Not connected : admiralgaragedoorrepair.com
  Not connected : admissions.ae
  Not connected : admonpc-ayapel.com.co
  Not connected : adobebplayer.xyz
  Not connected : adobleespacio.com
  Connected     : adotstudios.com
  Connected     : adpiggybank.com
  Connected     : adpiggy.com
  Not connected : adraeklo.com
  Not connected : adriaanvorster.co.za
  Connected     : adriangrand.com
  Connected     : adrianskar.com
  Connected     : adrianstimson.com
  Connected     : adriasolaclavijo.com
  Not connected : adrichal-le-adam.com
  Connected     : adrushyaguru.com
  Not connected : adsbazar.net
  Not connected : adsbook.co.za
  Not connected : adsfoundation.com.pk
  Not connected : adsurvey.tk
  Connected     : adupree.com
  Not connected : advanceddermatologyaustralia.com
  Not connected : advancevrsimulators.com
  Connected     : advcadsys.com
  Not connected : adventurecapital.ie
  Connected     : advertapp.me
  Connected     : advertchina.com
  Not connected : advertisehub.info
  Not connected : advertiseyourcompany.org
  Not connected : advertoz.com
  Not connected : advocatetn.com
  Not connected : advss.co.za
  Connected     : adwheelers.com
  Not connected : adw-portfolio.com
  Not connected : aeaccting.com
  Not connected : aeconafrica.com
  Not connected : aecssolution.com
  Connected     : aedelavenir.com
  Connected     : aedlifepower.com
  Not connected : aescollege.edu.pk
  Not connected : aestheticsbysanjeev.com
  Connected     : aewc.com.au
  Connected     : aexergy.com
  Connected     : aezla.com
  Connected     : afairgo.net
  Connected     : afdlhost.com
  Connected     : affableacademics.org
  Not connected : affaircitical.top
  Connected     : affairespatissieres.com
  Connected     : affenpinscher.org
  Connected     : affiliatemarketingquest.com
  Connected     : affixforex.com
  Connected     : affordable-35mm-slide-scanning.com
  Not connected : affordable-movers.net
  Connected     : affordablesandiegomovers.com
  Not connected : afftrack.best
  Not connected : afiaa-q.com
  Connected     : afikagroup.com
  Connected     : afikapower.com
  Connected     : afikaquadpro.com
  Connected     : afiyahealth.com
  Connected     : afjdqhrj.wcnv20.cn
  Not connected : afmance.it
  Connected     : afosystec.com
  Connected     : africangypsyjazz.com
  Connected     : africanleadershipcentre.org
  Connected     : africanpixels.zar.cc
  Connected     : africastrongspiritualhealer.com
  Connected     : afrikitti.com
  Connected     : afrogeo.com
  Connected     : afrtech.com
  Connected     : afshipping.com
  Not connected : aftabautos.pk
  Connected     : after.vix.br
  Connected     : afuocolento.it
  Not connected : afzalphotostat.com
  Connected     : afzlrcubyyj.wcnv20.cn
  Connected     : agapeencounter.org
  Connected     : agapita.com
  Not connected : agencereferencement.be
  Not connected : agencijazemil.com
  Not connected : agenterbaik88.com
  Not connected : agent.wizztrakys.com
  Connected     : aghnia.com
  Connected     : agico.com.pk
  Connected     : agiledepot.com
  Not connected : agitsolutions.com.pk
  Connected     : aglow.edu.pk
  Connected     : agricolavicuna.cl
  Not connected : agripal.ae
  Not connected : agriturismo-1001ulivo.it
  Connected     : agriturismobellaria.net
  Connected     : agrogen.com.tr
  Not connected : agropecuariavilarica.com.br
  Not connected : agt-hq.com
  Not connected : aguasdecastilla.com
  Not connected : agwannews.com
  Not connected : agylub.com
  Connected     : ahc.me.uk
  Connected     : ahdaaf.ae
  Connected     : ahelicoptermom.com
  Not connected : ahengineers.com.pk
  Connected     : ahero-resource-center.org
  Not connected : ahknivesindustry.com
  Not connected : ahmaddawakhana.com
  Not connected : ahmadfoodspk.com
  Not connected : ahmadhasanat.com
  Connected     : ahmadhassan.net
  Not connected : ahmaliic.com
  Not connected : ahmartextilepvtltd.com
  Not connected : ahmedrenovator.com
  Not connected : ahmshipping.com
  Not connected : a-host.co.uk
  Connected     : ahsanfarooqui.xyz
  Connected     : ahsfoundation.co.uk
  Connected     : ahsonqazi.com
  Connected     : ahworld.com.pk
  Connected     : aianalytics.ie
  Connected     : aibdqlscbs.wcnv20.cn
  Not connected : aidat.iade-basvurusu-bireysel.online
  Not connected : aidatkanun.com
  Connected     : aigroupofcompany.com
  Not connected : aiko.pro
  Not connected : aikurdunews.com
  Connected     : aileeshop.com
  Connected     : ailiaenterprises.com
  Connected     : aimalproduction.com
  Connected     : aimmop.pk
  Not connected : aimonino.info
  Connected     : aimsagro.com
  Connected     : aims-corp.com
  Connected     : aimswelfare.org
  Connected     : aimth.pk
  Connected     : aiofotoevideo.com
  Not connected : aipa.ca
  Not connected : airesis.blog
  Connected     : airfanhydro.net
  Connected     : airgenx.com
  Not connected : airjoy.top
  Not connected : airminumtiro.com
  Connected     : airnetinfotech.com
  Connected     : airplussa.co.za
  Connected     : airportenclave.com.pk
  Not connected : airsoft.net.tr
  Connected     : airsoftpoligon.com.tr
  Connected     : airtravels.us
  Connected     : airtronuae.com
  Connected     : airwhite.net
  Connected     : aisp74.asso.fr
  Connected     : aitech.com.tr
  Not connected : aizaportfolio.com
  Not connected : ajagayrimenkul.com.tr
  Connected     : ajajxcjexue.wcnv20.cn
  Not connected : ajans362.com
  Connected     : ajepcoin.com
  Connected     : ajipnsfv.wcnv20.cn
  Not connected : ajmery-world.com
  Not connected : ajwatraveltour.com
  Connected     : ajxzybdct.wcnv20.cn
  Connected     : akademihastanesi.net
  Not connected : akaiconsultantslimited.co.uk
  Connected     : akaiideas.com
  Connected     : akarnakliye.com.tr
  Connected     : akaycelik.com
  Connected     : akbuilders.pk
  Connected     : akcaymesrubat.com
  Not connected : akdreamssolution.com
  Connected     : akgullerinsaat.com.tr
  Not connected : akhbarejamiat.com
  Connected     : ak-industry.com
  Not connected : akkalegida.com
  Connected     : akoglumesrubat.com
  Connected     : akoli.gr
  Connected     : akoluklu.com
  Connected     : ak-on.com
  Not connected : akparplastik.com
  Not connected : aktivitedunyasi.com
  Not connected : akustik-hautnah-erleben.de
  Not connected : al3abflash.biz
  Connected     : alaca.com.tr
  Connected     : aladiyat.ae
  Connected     : alahlasi.com
  Connected     : alainsaffel.com
  Not connected : alanrori.com
  Not connected : alaqaba.com
  Connected     : alarabtents.com
  Connected     : alaskamaterials.com
  Connected     : alaskanharvestseafood.com
  Not connected : alayhamtechnologies.com
  Connected     : albedogida.com
  Connected     : albertaedmonton.com
  Connected     : albl.org
  Not connected : albousala.com
  Connected     : alcafricandatalab.com
  Connected     : alcafricanos.com
  Connected     : alcatrazmoon.com
  Connected     : alceharfield.com
  Not connected : alcfm.net
  Connected     : alchamel.info
  Connected     : alchamelup.org
  Not connected : alchemistasonida.com
  Not connected : alchimiegrafiche.net
  Not connected : alcradiochat.net
  Not connected : alecattic.com
  Connected     : aleenasgiftbox.com
  Not connected : aleksicdunja.com
  Connected     : alemaohost.com
  Connected     : aleoestudio.com
  Not connected : alephit2.biz
  Connected     : aleph.pk
  Not connected : alertaempresarial.com.br
  Not connected : ales.ball-mill.es
  Connected     : alessandroalessandrini.it
  Not connected : alessandrofoglino.com
  Connected     : alessioborzuola.com
  Connected     : aleter.ae
  Connected     : aleviturkler.com
  Connected     : alexanderbecker.net
  Not connected : alexboolooobinna.info
  Not connected : alexcelts.com
  Not connected : alexelgy.com
  Not connected : alex-frost.com
  Connected     : alexrocchi.com
  Not connected : alfahadmedia.ae
  Connected     : alfatek-intelligence.com
  Not connected : alfredocifuentes.com
  Not connected : alfredoposada.com
  Connected     : algarvesup.com
  Not connected : algihad.com
  Connected     : algom-law.com
  Connected     : alhidayahfoundation.co.uk
  Connected     : aliacan.com
  Not connected : aliart.nl
  Not connected : aliciabayl.com
  Not connected : alisabyfinna.com
  Not connected : alisimple.si
  Connected     : alissanicolai.com
  Not connected : aliydshoyow.com
  Connected     : alizemimarlik.com.tr
  Not connected : aljaadi.com
  Connected     : aljasar.com
  Connected     : alkousy.com
  Not connected : all2wedding.com
  Connected     : allaboutblockchain.net
  Connected     : allamwith.com
  Connected     : allday.gr
  Connected     : alldomains-crm.com
  Not connected : allegiancesecurity.org
  Not connected : allhandshygiene.co.za
  Not connected : allhsgz.com
  Not connected : allianz.com.pe
  Connected     : allinonebusinessresources.com
  Connected     : allisonplumbing.com
  Connected     : allkidsworld.com
  Not connected : allmantravel.com
  Connected     : all-reseller.com
  Connected     : allsporthealthandfitness.com
  Not connected : allthat.social
  Connected     : alluhaybi.com.sa
  Connected     : allusdoctors.com
  Connected     : almahaconsultants.com
  Not connected : almaqsd.com
  Connected     : almarjantobacco.com
  Not connected : almashrooglobal.com
  Connected     : almatours.gr
  Connected     : almeriahotelja.com
  Not connected : almirayapim.com
  Not connected : almokan.net
  Connected     : al-mostakbl.com
  Not connected : alnahdatraining.com
  Not connected : alnuzha.org
  Not connected : aloefly.net
  Not connected : alorabrownies.com
  Connected     : alotur.com
  Not connected : alpenfitil.com
  Connected     : alphabee.fund
  Not connected : alphainvestors.com.au
  Connected     : alphamike.com.mv
  Connected     : alphaobring.com
  Connected     : alphapridesafaris.com
  Not connected : alphasalesrecruitment.com
  Not connected : alphawaves.org
  Connected     : alsharhanstore.com
  Connected     : alshohub.org
  Not connected : altarek.com
  Connected     : altcoinaddict.com
  Connected     : alterwebhost.com
  Connected     : althurayaa.com
  Connected     : altinoluk-akcay.com
  Connected     : altosdefontana.com
  Not connected : altrablog.com
  Connected     : alvesajewellery.com
  Not connected : alwahahweb.com
  Connected     : alwake3press.com
  Connected     : always-beauty.ch
  Connected     : alxcorp.com
  Connected     : am1int.fcomet.com
  Not connected : amari.ro
  Connected     : amashop.ir
  Connected     : amateurastronomy.org
  Connected     : amatikulutours.com
  Connected     : amazethings.com
  Not connected : amazingashwini.com
  Not connected : amazingenergysavings.net
  Not connected : amazingtour.pk
  Connected     : ambiances-toiles.fr
  Connected     : ambientmoon.co.za
  Connected     : ambrogiauto.com
  Connected     : ambulatorioveterinariocalusco.com
  Connected     : ambyenta.hr
  Connected     : amcscomputer.com
  Connected     : amc-trans.ro
  Connected     : americabr.com.br
  Connected     : americanbrasil.com.br
  Not connected : americanbulldogradio.com
  Connected     : americanisexpres.com
  Connected     : americanlegacies.org
  Connected     : americanwestmedia.com
  Not connected : amesoulcoaching.com
  Not connected : amexcars.info
  Not connected : amexpressx.com
  Not connected : amfotoalbum.com.br
  Connected     : amgtymjgwamb.wcnv20.cn
  Connected     : amiehepperlin.com
  Not connected : amiici.vision
  Not connected : aminearserver.es
  Not connected : amirmenahem.com
  Connected     : amishcountryfurnishings.com
  Connected     : ammannati.it
  Not connected : amnjeans.it
  Connected     : amofoundation.org
  Connected     : amooy.com
  Not connected : amor-clubhotels.com
  Not connected : amordegato.es
  Connected     : amphibiblechurch.com
  Not connected : ampleadminservices.com
  Not connected : ampli5yd.com
  Connected     : ampvita.com
  Connected     : amruthavana.com
  Connected     : anahera.biz
  Not connected : analternatif.com
  Connected     : analystcnwang.com
  Not connected : analyticalfootball.com
  Not connected : anastasovsworkshop.com
  Connected     : anbinni.ba
  Connected     : ancient-wisdoms.com
  Connected     : ancoeng.co.za
  Connected     : and10.uzuzuseubumaandro1.com
  Connected     : and12.thesuchivestfishmarketeat111.com
  Connected     : and12.thesuchivestfishmarketeat222.com
  Connected     : and13.dexterwasanicemoviesz1.com
  Connected     : and18.f16zakitchenboy1.com
  Connected     : and19.amainwrorldnancy1.com
  Connected     : and28.aviationdreamflightering1.com
  Connected     : and30.amainwrorldnancy2.com
  Connected     : and30.blabladomdom.com
  Connected     : and31.amainwrorldnancy4.com
  Connected     : and4.junglebeariwtc1.com
  Connected     : and4.junglebeariwtc2.com
  Connected     : and9.themainnotmainstreet2.com
  Connected     : andihaas.at
  Connected     : ando.co.kr
  Connected     : andrasadam.com
  Connected     : andreabelfi.com
  Connected     : andrebruton.com
  Connected     : andrespazsoldan.com
  Not connected : andrewfinnburhoe.com
  Connected     : andrewsbisom.com
  Not connected : andrew-snyder.net
  Not connected : androidphonetips.com
  Not connected : androidpt01.asia
  Not connected : androidpt02.asia
  Connected     : androidwikihow.com
  Not connected : anet-international-group.com
  Connected     : anf.gov.pk
  Not connected : angar68.com
  Connected     : angel-blanco.net
  Connected     : angel-seeds.com.ua
  Connected     : angelsongroup.com
  Connected     : anglero.com
  Connected     : angloglot.com
  Not connected : aniljoseph.com
  Connected     : animallantalya.com
  Not connected : animationinisrael.org
  Not connected : animationpulse.net
  Not connected : animationshowreel.co.il
  Not connected : animeok.co.il
  Not connected : aniroleplay.net
  Connected     : ankamesrubat.com
  Not connected : ankara24saatacikcicekci.com
  Not connected : ankara24saatcicek.com
  Not connected : ankara24saatcicek.net
  Connected     : ankaraikincielesyalar.com
  Connected     : ankarakiralikvinc.web.tr
  Connected     : ankaramehteri.com
  Not connected : ankaraotokurtarici.web.tr
  Connected     : ankaratemizliksirketleri.web.tr
  Connected     : ankaratemizlik.web.tr
  Not connected : ankus.es
  Connected     : annabelle.nl
  Not connected : annaplebanek.com
  Connected     : anngrigphoto.com
  Not connected : annodle.com
  Not connected : anora71.uz
  Connected     : anotherdayinparadise.ca
  Not connected : anotherpartofme.com
  Connected     : anphmhqf.wcnv20.cn
  Connected     : ansetech.co.kr
  Connected     : answerstoprayer.org
  Connected     : anthaigroup.vn
  Connected     : antitecnologia.com
  Connected     : antjetaubert.de
  Connected     : antkriko.com
  Not connected : antonhirvonen.com
  Not connected : antrismode.com
  Connected     : antsaninsaat.com.tr
  Not connected : antucomp.com
  Not connected : anubandh.in
  Connected     : anuragcreatives.com
  Not connected : anxiousandunstoppable.com
  Connected     : anyeva.com
  Not connected : anyoneforum.cc
  Connected     : anythingispossible.world
  Not connected : anythinglah.info
  Not connected : anzanihealth.co.za
  Not connected : a-nz-check-now.com
  Not connected : aol.thewirawan.com
  Connected     : aoryx.ae
  Not connected : apaktem.com
  Connected     : apalawyers.pt
  Not connected : aperta-armis.org
  Connected     : apidubai.ae
  Connected     : apiiination.com
  Not connected : apironco.com
  Connected     : apkglobe.net
  Connected     : apobiomedix.ca
  Connected     : apollonweb.com
  Not connected : apositive.be
  Not connected : appidsrv-micuentavrfinc.com
  Not connected : apple-cloud-jp.com
  Not connected : apppriori.com
  Not connected : appsrcv-miappidaccsrvinc.com
  Not connected : appsvoice.info
  Not connected : appsysrcvs-miappidsrvinc.com
  Not connected : appyss-miappidsrvinc.com
  Connected     : apqecjaleeu.wcnv20.cn
  Connected     : aqarco.com
  Connected     : aqlaal.com
  Connected     : aquabsafe.com
  Connected     : aqualogicwc.co.uk
  Not connected : aquamasaj.com
  Not connected : aquaneeka.co.uk
  Not connected : aquo.in
  Connected     : arabelaholdings.com
  Not connected : arabellajo.com
  Connected     : arabsdeals.com
  Connected     : aracexpress.com
  Not connected : aradhana.faith
  Not connected : arar-musique.fr
  Not connected : arasbg.com
  Not connected : araskargo.online
  Not connected : arasotokiralama.net
  Not connected : arbeidsrechtcentrum.nl
  Connected     : arbiogaz.com
  Connected     : arbruisseau.com
  Not connected : arbulario.com
  Connected     : archersassociationofamerica.org
  Not connected : archiotronic.com
  Connected     : architectshub.in
  Connected     : architectsinc.net
  Connected     : architecturalplus.co.nz
  Not connected : archwaycarpetscrm.co.uk
  Not connected : arc-sec.net
  Not connected : arctistrade.de
  Connected     : arctkrmxjscg.wcnv20.cn
  Connected     : arcusautomatika.ba
  Not connected : ardatur.com
  Connected     : ardvessels.com
  Connected     : aresebetseng.co.za
  Connected     : arestihome.com
  Not connected : arhidsfderm.pw
  Connected     : arhiepiscopiabucurestilor.ro
  Not connected : ariturkklima.com
  Connected     : arkamp.ir
  Not connected : arkei.oz-n.ru
  Connected     : armadakizyurdu.com
  Connected     : armator.info
  Connected     : arm.net.pk
  Connected     : armtheprofileoriginals.com
  Connected     : arpid.ru
  Connected     : a.rrbxn.com
  Connected     : ar-rihla.com
  Not connected : arsailani.com
  Connected     : artibilisim.xyz
  Not connected : artibirinsaat.com.tr
  Not connected : artikainsaat.com
  Not connected : artikhazirsin.remingtonturkiye.com
  Connected     : artistanbul.tv
  Not connected : artistlogistics.net
  Not connected : artumus.co.za
  Connected     : arzumceyiz.com
  Connected     : asaninsaat.com
  Connected     : asaryapi.com.tr
  Connected     : asduru.com.tr
  Connected     : aseltech.com.tr
  Not connected : aseltech.dental
  Connected     : asesoriastepual.cl
  Not connected : asgaage.pw
  Connected     : asgen.org
  Connected     : ashapeforlife.com
  Not connected : asinsaat.org
  Connected     : asjjvlimuud.wcnv20.cn
  Connected     : askarisecurities.com.pk
  Not connected : aslanmangalkomuru.com
  Not connected : aslanorganizasyon.com
  Connected     : aslimaj.com
  Connected     : asnsport-bg.com
  Not connected : asrinorganizasyon.com
  Connected     : assemblee-nationale.cg
  Connected     : asseqvsbsleh.wcnv20.cn
  Connected     : assurancetemporaireenligne.com
  Connected     : assuredfirst.com
  Connected     : astra.com.tr
  Connected     : astrumtechnologies.co.za
  Not connected : asturkgrup.com
  Not connected : asturkkimya.com
  Connected     : asturkmadencilik.com
  Not connected : asvip2.top
  Connected     : ataglobal.com.tr
  Connected     : atakan.com
  Not connected : atakantarimci.com.tr
  Not connected : ataklojistik.com
  Connected     : atamanelektronik.com
  Connected     : atascelikyapi.com
  Not connected : atasehiryuzme.com
  Connected     : atcouriers.co.za
  Connected     : atexmodels.co.za
  Connected     : atkiatkisiimalat.com
  Not connected : atkiatkisi.net
  Not connected : atlantarecyclingcenters.com
  Connected     : attilabalogh.com
  Connected     : atxvfhoklmo.wcnv20.cn
  Not connected : auburnhomeinspectionohio.com
  Connected     : auctionify.com.ng
  Connected     : audio-pa-service.de
  Connected     : auditlater.top
  Connected     : aujmgfpl.wcnv20.cn
  Connected     : auraco.ca
  Connected     : ausfinex.com
  Not connected : autoecoleathena.com
  Connected     : autoecoleboisdesroches.com
  Connected     : autoecole-jeanpierre.com
  Connected     : auto-ecole-lecastelet.com
  Connected     : automattenonline.com
  Connected     : auxilia-fr.com
  Connected     : avaagriculture.com
  Connected     : avcihukukburosu.com
  Connected     : aviasiya.com
  Connected     : avizoneaviation.com
  Connected     : avrupabaski.com
  Not connected : avsa-adasi.gen.tr
  Not connected : avsserradecor.com
  Connected     : awebcommerce.com
  Not connected : awholeblueworld.com
  Not connected : awuav.world
  Not connected : axess-akbnk.com
  Connected     : ayakkabisitesi.com
  Not connected : aycinteker.com
  Connected     : aydincaliskankanarya.com
  Connected     : aydinsenturk.com
  Not connected : aygunotomasyon.com
  Not connected : ayinfirsatigunleridenizle.com
  Connected     : aymuhendislik.com
  Connected     : aypir.com
  Connected     : aysamturizm.com.tr
  Not connected : aysekaya.com.tr
  Connected     : ayterm.com
  Connected     : azadpattanhpp.com
  Connected     : azedizayn.com
  Not connected : azermaral.com
  Connected     : azim.co.il
  Not connected : azizinsaat.com
  Not connected : azlinshaharbi.com
  Not connected : azracateringme.ae
  Not connected : b4bios.com
  Connected     : babafareed.org.pk
  Not connected : babajimastsarkar.com
  Not connected : babakigari.com
  Connected     : babalmadina.com
  Not connected : babarenclave.pk
  Connected     : babil117.com
  Not connected : baby.greenweb.co.il
  Not connected : baby-shop.com.pk
  Not connected : backoffice-me.com
  Not connected : badlaretinaclinic.com
  Connected     : bafflethink.com
  Not connected : bagadesign.pt
  Not connected : bagherehman.com
  Not connected : bahadirsahinoglu.com
  Connected     : bahaosgb.com
  Not connected : baharakgul.com
  Not connected : bahaykuboeliterealty.com.au
  Not connected : bahrainssc.org
  Not connected : bahria-maritime-services.com
  Connected     : bahriatownservices.com
  Not connected : baigs.co
  Not connected : bakayokocpa.com
  Not connected : bakbibul.com
  Connected     : bakbitv.com
  Connected     : bakemartplus.ae
  Connected     : bakhabarnews.com
  Not connected : bakhshirealestate.com
  Connected     : bakiroglu.com.tr
  Not connected : bakron.co.za
  Connected     : baksapk.com
  Connected     : balaateen.co.za
  Not connected : balcidede.com.tr
  Connected     : baldatca.com
  Connected     : balkonresidence.com
  Connected     : balzantruck.com
  Not connected : bamex.com.pk
  Connected     : banglanews-24.com
  Connected     : banjo.la
  Not connected : bank-service.company
  Not connected : bannubook.org
  Connected     : bansko-furniture.co.uk
  Not connected : baranakinturk.com.tr
  Not connected : baranhotel.com
  Connected     : barberink.biz
  Not connected : baresiconstrucoes.com
  Not connected : barrobaseerogroup.com
  Connected     : bartabee.com
  Connected     : basarteks.com
  Connected     : bashancorp.co.za
  Not connected : bashirengineeringservices.com
  Not connected : baskale.bel.tr
  Connected     : basketballkungfu.com
  Not connected : baskisanati.com
  Not connected : baspinarlartulumpeyniri.com
  Connected     : bat99-11611.co
  Not connected : batalabalochihandicraft.com
  Connected     : batistadopovosjc.org.br
  Not connected : batthiqbal.com
  Not connected : batuhandugunsalonu.com
  Not connected : bayenat.pk
  Not connected : bayiers.com
  Connected     : bayimpex.be
  Connected     : baynetins.com
  Not connected : bayrampasabocekilaclama.net
  Not connected : baytech.pk
  Not connected : bazar247.pk
  Not connected : bazinga-shop.eu
  Not connected : bbc11tv.com
  Connected     : bbtravels.net
  Connected     : bckkaucuk.com
  Not connected : bc-u.co.uk
  Not connected : bddk-turkiye.org
  Connected     : b-design.studio
  Connected     : bdholdings.com
  Connected     : b-dvs.com
  Not connected : beachroad.ae
  Not connected : beaconhill.edu.pk
  Not connected : beaconlightschool.com
  Connected     : beaconlocation.com
  Connected     : beaconwelfare.com
  Not connected : beadbazaar.com.au
  Connected     : beamfight.com
  Connected     : beansviolins.com
  Connected     : beardempire.pk
  Not connected : beautyboutique.pk
  Not connected : bebekyuzmekurslari.com
  Not connected : be-blu.it
  Connected     : beconsultants.org
  Connected     : bedarimillat.com
  Connected     : beddysstudio.com
  Not connected : bednbreakfasthotel.com
  Not connected : bee.com.pk
  Not connected : beehiveholdingszar.co.za
  Not connected : beesolutions.co
  Not connected : beesrenovations.co.za
  Connected     : behealthier.eu
  Connected     : bek.ae
  Not connected : bekkersweldingservice.nl
  Connected     : belfortsecurity.com
  Not connected : bella-yfaceandbodyproduct.com
  Not connected : belvasports.com
  Connected     : bench-mark.org
  Not connected : benonicoc.co.za
  Connected     : bentivegna.es
  Connected     : benztechsolutions.com
  Connected     : bepovoblago.com
  Connected     : berds.org.pk
  Not connected : berkahbajamakmur.com
  Not connected : berkataman.com
  Not connected : berkshireconsultants.org
  Connected     : berped.co.za
  Connected     : bervin.com.tr
  Connected     : besertoprak.com.tr
  Not connected : beshop.pk
  Not connected : bes-s.com
  Connected     : bestaxi.nl
  Not connected : bestbedrails.reviews
  Not connected : bestcoolingtowels.reviews
  Connected     : bestcoverpix.com
  Not connected : bestdamascusknives.com
  Connected     : bestdecorativemirrors.com
  Not connected : best-digital-slr-cameras.com
  Connected     : best-dreams.com
  Connected     : bestencouragementwords.com
  Not connected : bestenoughcallcenter.co.za
  Connected     : bestfgt.com
  Not connected : besthappyhalloweenhistory.com
  Connected     : bestoballoons.com
  Not connected : bestsheepleather.com
  Not connected : besttweezers.reviews
  Not connected : betandbeer.tips
  Not connected : betatechnologiesme.com
  Connected     : beta.wally02.org
  Not connected : bethlehemcarving.com
  Not connected : beti.pk
  Not connected : betterstep.ae
  Not connected : betterthanbestarticles.com
  Connected     : beyazavukatlik.com
  Not connected : beyzbolturk.com
  Connected     : bfval.com
  Connected     : bfzszpaug.wcnv20.cn
  Connected     : bgadvocaten.nl
  Connected     : bg.com.tr
  Connected     : bgpsouthasia.com
  Not connected : bg-tal.com
  Connected     : bhakkarrishtey.com
  Connected     : bhekiguru.co.za
  Not connected : bhg-tech.com
  Not connected : bhic-group.com
  Connected     : bhlslctlmcf.wcnv20.cn
  Not connected : bhs-news.com
  Connected     : bibanka.com
  Connected     : bicer-san.com
  Not connected : bidmandi.com
  Connected     : bienart.com
  Connected     : bifikirajans.com
  Not connected : bigbaazaronline.com
  Not connected : bigbachatmart.com
  Not connected : bigbirdint.com
  Connected     : bigdatasolution.com.pk
  Not connected : bigerfriend.com
  Connected     : bigfans.ae
  Not connected : biginshop.com.pk
  Connected     : biglickentertainment.com
  Not connected : bignets.ddns.net
  Not connected : bihaliortusu.com
  Not connected : bilalrashid.pk
  Connected     : bilenbizibilir.com
  Connected     : bilikit.com
  Connected     : biljum.com
  Connected     : billielaw.com
  Not connected : bilsem.club
  Not connected : bilsem.info
  Connected     : binabidconsulting.com
  Connected     : binaries.site
  Not connected : binarycousins.com
  Connected     : bingleybuilder.co.uk
  Connected     : binham.com
  Connected     : binhamgroup.com
  Connected     : binitelecom.com
  Not connected : bintemustafa.com
  Connected     : binuq.gob.pk
  Not connected : binzaq.com
  Connected     : biodogacevre.com
  Connected     : biondi.co
  Not connected : bios-chip.co.za
  Connected     : bioservepharma.com
  Not connected : biotechreview.net
  Not connected : biotechtoday.co.uk
  Not connected : birds.org.pk
  Not connected : bireyselhizmetnoktasiii.com
  Not connected : bireyselmagaza.com
  Not connected : bireyselqnbgiristr.com
  Not connected : birfidanbirumut.org.tr
  Not connected : birmetalciningezinotlari.com
  Not connected : biseabt.com
  Not connected : bismahcapital.com
  Not connected : bismillahmotors.pk
  Not connected : bismillahtraders.org
  Connected     : bitandbyte62.com
  Not connected : bitcoinminerworldwide.com
  Connected     : bit.do
  Connected     : bitekservis.com
  Not connected : bitisd.com
  Connected     : bit.ly
  Connected     : bitsym.com
  Not connected : bitteeth.com
  Connected     : biyanyapi.com
  Not connected : bizfolkseventurous.com
  Connected     : bizimbag.com
  Connected     : bizimnalbur.com
  Not connected : bizlikebiz.biz
  Connected     : bizxess.com
  Connected     : bkconsultants.com.pk
  Connected     : bkembroidery.com
  Connected     : bkmzvkaoi.wcnv20.cn
  Not connected : bkresearch.org
  Not connected : blackdecker.anticorxx.com
  Not connected : blackdecker.tcc.tc
  Connected     : blackgirlswhocraft.com
  Connected     : blackgoldoilserv.com
  Connected     : blackrabbitthailand.com
  Connected     : blackthorn.co.za
  Connected     : blackwolfco.com
  Connected     : blankwebagency.com
  Not connected : blendcodes.com
  Connected     : b.link
  Not connected : blockchainadvertisements.net
  Not connected : blog.batalk.fun
  Not connected : blog.digialpha.net
  Connected     : bloggertemplates4u.com
  Connected     : bloggingio.com
  Connected     : blog.kobisi.com
  Connected     : blog.openthefar.com
  Connected     : blog.sefaireaider.com
  Connected     : bloorco.com
  Connected     : bluebayauto.com
  Not connected : blueberrygroup.com.ar
  Connected     : bluecrome.com
  Not connected : bluefor.com
  Connected     : bluehawkbeats.com
  Not connected : bluehostturkiye.com
  Connected     : bluewaves.ae
  Not connected : bluey.online
  Connected     : blushagency.com
  Connected     : bluvgkcs.wcnv20.cn
  Connected     : bm360.com.pk
  Not connected : bmasokaprojects.co.za
  Connected     : bmc.edu.pk
  Connected     : bmctelecom.ae
  Not connected : bmenerji.com.tr
  Not connected : bmindctech.com
  Connected     : bmorecleaning.com
  Connected     : bmscissors.com
  Connected     : bnboutlet.com
  Not connected : bnf.org.pk
  Connected     : bntlaminates.com
  Connected     : boardaffairs.com
  Connected     : boatwif.co.uk
  Not connected : boaze.de
  Connected     : bocekilaclama.gen.tr
  Not connected : bocekilaclamahizmeti.com
  Connected     : bocekilaclamazeytinburnu.net
  Not connected : bo-crm.com
  Not connected : bodemeo2.sg-host.com
  Not connected : bodemeo4.sg-host.com
  Not connected : bodyprecinct.com.au
  Connected     : boetsebiltong.co.za
  Not connected : bogdanandreescu.fit
  Connected     : bogjerlow.com
  Connected     : boilersinfo.com
  Connected     : bojibanf.wcnv20.cn
  Connected     : bokkeriejesj.nl
  Not connected : bolgemuhabirligi.com
  Not connected : bollywood-circle.com
  Not connected : bolumutluturizm.com
  Not connected : bommgrest.ru
  Not connected : bonasfalogtrans.com
  Connected     : bonjurparti.com
  Connected     : bonofigliophotography.com
  Not connected : bonus.onlineozelpuanlatr.cf
  Connected     : bonus.rocks
  Not connected : bonus-tutors.website
  Not connected : bookdoctormeeting.com
  Not connected : bookdubaisafari.com
  Not connected : bookf27.com
  Connected     : book-house.org
  Connected     : bookmeguide.com
  Not connected : bookmystudy.org.pk
  Connected     : booksandtoys.com.tr
  Not connected : booksnotespdf.com
  Connected     : boringinternet.com
  Connected     : bornear.com
  Not connected : bor.superyaz.com
  Connected     : bor.uz
  Connected     : bosacik.sk
  Not connected : boschettoristorante.it
  Not connected : boschxpress.com
  Not connected : botanicalaboratories.com
  Not connected : botanikbahcesi.com
  Connected     : botmanhosting.com
  Connected     : boudua.com
  Not connected : bountysforbumps.com
  Connected     : bouranabrothers.com
  Not connected : boyalitrapezfabrikasi.com
  Connected     : bozlxyaxr.wcnv20.cn
  Not connected : bqcelectronics.com
  Not connected : bq-foods.com
  Not connected : bqi.com.pk
  Connected     : bradleybakerrmusic.com
  Connected     : bradleysherrer.com
  Not connected : brainiac.edu.pk
  Connected     : brainlight.me
  Connected     : bramloosveld.be
  Not connected : brandcaresolutions.co
  Connected     : brand-key.com
  Connected     : brandosol.com
  Connected     : brandr.ge
  Not connected : brandscapes.com.pk
  Connected     : brandspeak.org
  Connected     : bravori.com
  Not connected : brck.edu.pk
  Not connected : brctsrm.com
  Connected     : breadnbutter.com.pk
  Connected     : breakbyte.com
  Not connected : breakoutmonitor.info
  Connected     : breastfeedingbra.co.za
  Not connected : breathehope4maira.com
  Not connected : bridgepakistan.org
  Connected     : bridgewaybpo.com
  Connected     : briskfm.co.uk
  Not connected : briskid.com
  Connected     : briskways.net
  Connected     : britishasia-equip.co.uk
  Not connected : britishofficefitout.com
  Connected     : broadpeak.co
  Connected     : broadstone.com.pk
  Not connected : brokedudepodcast.com
  Connected     : broken-arrow.co.za
  Not connected : brosen.com.pk
  Not connected : brussellstribunal.com
  Connected     : bshconglobal.com
  Not connected : bsmtrans.com
  Not connected : bsodsupport.icu
  Connected     : btafbearings.com
  Not connected : btcproftclub.com
  Connected     : btfila.org
  Not connected : btg4hope.org
  Connected     : buboobioinnovations.co.za
  Not connected : bubucheatin2.ru
  Not connected : buchnation.com
  Not connected : buenasia.com
  Not connected : bugitsolution.com
  Connected     : buhlebayoacademy.com
  Connected     : buildingstandards.com.pk
  Not connected : buildwellpak.com
  Connected     : buildyoursalon.com
  Not connected : bulinvestconsult.com
  Not connected : bulldogshousing.com
  Connected     : bumbledyne.com
  Not connected : bumpapps.com
  Not connected : bundesgloballogisticssa.com
  Not connected : bunyadwelfare.org
  Connected     : buqsrpfh.wcnv20.cn
  Not connected : burakdoseme.com
  Connected     : burgercoetzeeattorneys.co.za
  Not connected : burgeystikihut.com
  Not connected : burhanitradinglimited.co.uk
  Not connected : burhanulhaqq.com
  Connected     : burkertparts.com
  Connected     : burlesonlelas.com
  Connected     : burnout.com.pk
  Not connected : burqaapp.com
  Connected     : bursabitkisel.com
  Not connected : bursadanilan.com
  Connected     : bursatemamutfak.com
  Connected     : busad.com
  Not connected : businessustad.com
  Not connected : bustankitchens.com
  Not connected : buthadoubleapaper.com
  Connected     : butikiletisim.com
  Not connected : buttarandbuttars.com
  Not connected : buy4you.pk
  Not connected : buyboxlabs.com
  Connected     : buynow.com.pk
  Not connected : buzzertv.xyz
  Connected     : buzzfeedhealth.com
  Connected     : bvzfrjmghu.wcnv20.cn
  Not connected : bwtest1.apps.ae
  Not connected : bykashifhussain.com
  Connected     : bzwslxbo.wcnv20.cn
  Connected     : c3pconsulting.com
  Not connected : c3pw.com
  Not connected : caacademicforum.com
  Not connected : cablenetproviders.com
  Not connected : cadcomputeracademy.com
  Connected     : cafawelding.co.za
  Not connected : cafeaulait.co
  Connected     : cafebistrovia.com
  Not connected : cafeliquiteria.pk
  Connected     : cagliaricity.it
  Not connected : cakirgranitinsaat.com
  Not connected : calculactcal.org
  Not connected : callcar.com.pk
  Not connected : calzature.com.pk
  Connected     : camasirhaneistanbul.com
  Not connected : camasirhaneyalova.com
  Not connected : cambridgeeducationalservices.info
  Connected     : cambridgetuts.com
  Not connected : camefe.com.mx
  Connected     : camkutezyinat.com
  Connected     : camlikkamping.com
  Connected     : campet.com.tr
  Connected     : camps.pk
  Connected     : campusvoltaire.com
  Connected     : canadianvc.com
  Connected     : canaldeal.top
  Connected     : canbeginsaat.com
  Connected     : candidsourcing.com
  Connected     : capetownway.co.za
  Not connected : capewindstrading.co.za
  Connected     : capitalexchange.ae
  Not connected : capitalradiopetition.co.za
  Not connected : capital.wistech.biz
  Not connected : capriflower.co.za
  Connected     : caregroup.co.za
  Not connected : carepvtltdpk.com
  Connected     : carlagrobler.co.za
  Connected     : carrentbodrum.com
  Connected     : car.ru
  Connected     : cartridgecave.co.za
  Not connected : cashforyousa.co.za
  Connected     : castaldiart.com
  Connected     : cautioncook.top
  Connected     : cazochem.co.za
  Not connected : cbiraqi.com
  Connected     : cc.com.pk
  Connected     : cchsahardware.com
  Connected     : cdn.discordapp.com
  Connected     : cdn.funckgroup-server.com
  Connected     : cds.org.pk
  Not connected : cdxtrading.co.za
  Not connected : celasllc.com
  Connected     : cemsolutions.org
  Connected     : centraldispatchinc.com
  Not connected : centreforgovernance.uk
  Not connected : centuriongsd.co.za
  Connected     : centuryacademy.co.za
  Connected     : centurythis.com
  Connected     : ceramica.co.za
  Connected     : cerkezkoytakograf.com
  Connected     : cevahirogludoner.com
  Connected     : ceylaninruyasi.com
  Connected     : ceylanmobilya.com.tr
  Connected     : cfm.com.pk
  Not connected : cfsparts-logsclients.com
  Not connected : chagiocaxuanson.esy.es
  Connected     : charispaarl.co.za
  Connected     : charliewestsecurity.co.za
  Not connected : chat.honda.ae
  Not connected : checksolutions.pw
  Not connected : chickenandkitchen.com
  Connected     : chinamall.co.za
  Not connected : chinapacific.co.nz
  Not connected : chinasonix.cf
  Connected     : chitchatdosti.com
  Connected     : chrisdejager-attorneys.co.za
  Connected     : chrishanicdc.org
  Connected     : chudresex.at
  Connected     : chudresex.cc
  Connected     : ciftlikonuasm.gov.tr
  Connected     : cigercihamza.com
  Connected     : cinargrafikmatbaa.com
  Connected     : cipemiliaromagna.cateterismo.it
  Connected     : cittaslowturkiye.org
  Connected     : clandecor.co.za
  Not connected : cle.ae
  Connected     : clientcare.co.ls
  Not connected : clientenovoacesso.com
  Not connected : clinetea62bnhuc2.onion.link
  Not connected : cloudhostdesign.com
  Connected     : cloudhub.co.ls
  Connected     : clouditzone.com
  Connected     : clqodqyca.wcnv20.cn
  Not connected : cmhts.co.za
  Connected     : cmisyzmrj.wcnv20.cn
  Not connected : cmsolutions.ae
  Connected     : cms.qa
  Connected     : cns.com.pk
  Not connected : co-appidsrcvinc.com
  Connected     : cocobooter.com
  Not connected : colenesphotography.co.za
  Not connected : coloradofootinstitute.com
  Connected     : colorglobe.in
  Connected     : comecomefindme.ru
  Connected     : cometnet.biz
  Not connected : comfortex.co.za
  Not connected : com-mobalol.info
  Not connected : competitiveedoptions.com
  Not connected : compoz.at
  Connected     : compushopsa.co.za
  Not connected : comsip.org.mw
  Not connected : comtecav.co.uk
  Connected     : congcuphongthan.com
  Connected     : conkorea.com
  Not connected : conlin-boats.com
  Connected     : connect-server.com.ua
  Connected     : constructionsolutions.info
  Connected     : controleng.com
  Not connected : convitek.com
  Not connected : cookiesdough.tk
  Connected     : cookncash.com
  Connected     : cooldoctor.ae
  Not connected : cool-group.ae
  Connected     : cool-group.net
  Connected     : coolguys.ae
  Connected     : coolingdubai.com
  Connected     : coolplusmedical.com
  Connected     : copansrl.it
  Not connected : corludiyetyemekleri.com
  Not connected : corporategiftbranding.co.za
  Connected     : cortaestanciapolanco.com
  Connected     : cosmeticsurgeryisb.pk
  Not connected : cosmetify.pk
  Not connected : cosmosholidays.pk
  Not connected : cothmisb.com
  Not connected : coupon-online.fr
  Not connected : courtesydriving.co.za
  Not connected : coverpixs.com
  Connected     : cowp.or.kr
  Not connected : cpecsol.com
  Not connected : cpsxz1.at
  Connected     : crackleplus.com
  Not connected : craigslistadsposting.com
  Not connected : cre8ivecase.net
  Connected     : createch.solutions
  Not connected : create-creative.com
  Not connected : creativeloog.co
  Not connected : creativenex.com
  Not connected : creativesvisions.com
  Connected     : creative-things.com
  Connected     : creativetiers.com
  Connected     : creditformula.org
  Not connected : cresoulsmarketing.com
  Not connected : cresthill.co.uk
  Connected     : crissamconsulting.co.za
  Connected     : crna-macka.com
  Connected     : crystaltidings.co.za
  Connected     : csemag.com
  Connected     : ctmgdurbsuin.wcnv20.cn
  Connected     : ctmnqkkpznj.wcnv20.cn
  Connected     : cugaituoianthai.com
  Connected     : cultofmobile.com
  Connected     : cumflbsuut.wcnv20.cn
  Not connected : cuneytugur.com.tr
  Not connected : cupboardcure.co.za
  Connected     : curb-food-cravings.com
  Connected     : cutt.ly
  Connected     : cwzjfzwvkyx.wcnv20.cn
  Connected     : cxzxzxzxzzxzx.s3.eu-central-1.amazonaws.com
  Connected     : cybercraft.biz
  Connected     : cynoedrabpcp.wcnv20.cn
  Connected     : cy.tc
  Connected     : d11295.top
  Connected     : d6tim2wp6ynyd5gvmqgtrqhpl4-adwhj77lcyoafdy-vakifbank.translate.goog
  Not connected : dagwile.org
  Not connected : dailyqadamat.com
  Not connected : dailysportsgossips.com
  Not connected : dapoerwedding.com
  Not connected : datadigm.co.za
  Connected     : dataseek.com.br
  Not connected : datasoft-sa.com
  Connected     : datenhaus.info
  Not connected : davetyaymak.com
  Not connected : davidstephensbanjo.com
  Not connected : daybreakhealthcare.co.uk
  Connected     : dbhcjzrclv.wcnv20.cn
  Not connected : dbr663dnbssfrodison.net
  Connected     : dcpieters.co.za
  Connected     : ddjm.co.kr
  Not connected : ddnmamozagreb.com
  Connected     : ddyatirim.com
  Connected     : dealmaterial.top
  Connected     : debnoch.com
  Connected     : dedeyumurtaciftligi.net
  Connected     : dedicatematch.top
  Connected     : deepgraphics.co.za
  Not connected : deereebee.info
  Connected     : degdiwixj.wcnv20.cn
  Connected     : delcom.co.za
  Connected     : delectronics.com.pk
  Connected     : deleogun.com
  Connected     : delinmeal.com
  Not connected : deltadisseny.com
  Not connected : democuk.tk
  Connected     : demopowerindo.com
  Connected     : demo.scd.network
  Not connected : demo.wearemedia.us
  Not connected : denizbank-xrcekilis.com
  Not connected : derainlay.info
  Not connected : derinyapiinsaat.com
  Not connected : desarrolloprueba.xyz
  Not connected : designordie.ca
  Not connected : desirablehair.co.za
  Connected     : devlette.com
  Not connected : dewibebaris.com
  Connected     : d.filebox.moe
  Not connected : dfjdgxm3753u744h.at
  Connected     : dghfhfgjfhjghj6699.net
  Connected     : dhaspquf.wcnv20.cn
  Connected     : dhtnldogywx.wcnv20.cn
  Connected     : dianakleyn.co.za
  Not connected : dicitalacans.xyz
  Not connected : diegemmerkat.co.za
  Connected     : diginixtech.com
  Not connected : digitalblue.co.za
  Not connected : digital-cameras-south-africa.co.za
  Connected     : digitalteknik.com.tr
  Not connected : dijitalbasvurumobildenizgiris.co.vu
  Not connected : dikon.com.tr
  Connected     : dimer-group.com
  Connected     : dingaanassociates.co.za
  Connected     : diprolisa.mx
  Not connected : direction43567.xyz
  Not connected : dissertation4help.com
  Not connected : divingforpearls.at
  Connected     : djtrina.com
  Not connected : dlamure.com
  Connected     : dlgfuarcilik.com
  Connected     : dlomdhfoq.wcnv20.cn
  Not connected : dl.wizzuniquify.com
  Not connected : dmc.gov.pk
  Not connected : dndzh457thdhjk.at
  Not connected : dodoi.cc
  Connected     : dogadanderman.com
  Connected     : doggypetstore.com
  Connected     : dogukandogan.com.tr
  Connected     : domand.altincopps.com
  Connected     : domesticguardians.co.za
  Connected     : domusgroup.ae
  Connected     : donmezhidrolik.com
  Connected     : doomed.cf
  Not connected : doorboss.co.za
  Connected     : dorakiletisim.com
  Connected     : dorjenmar.com
  Not connected : doseoul.com
  Not connected : downlooter.net
  Not connected : dp4kb.magelangkota.go.id
  Not connected : dpscdgkhan.edu.pk
  Connected     : drhalilciftci.com
  Not connected : drivestransfer.com
  Connected     : drorrpenf.wcnv20.cn
  Connected     : drug-treatment-directory.com
  Connected     : dryve.ae
  Connected     : dsjbkqqikzml.wcnv20.cn
  Connected     : dubaigip.com
  Connected     : dubaihelishow.com
  Not connected : dubaistars.ae
  Not connected : dublindriveways.ie
  Connected     : duckiesplumbing.com.au
  Not connected : duffle.at
  Not connected : dummy.celerosnetworks.com
  Not connected : d.universe.com
  Connected     : duotonedigital.co.za
  Connected     : dusttek.com.tr
  Connected     : dvakpjsavvv.wcnv20.cn
  Connected     : dvprojekt.hr
  Not connected : dws-gov.co.za
  Connected     : dylboiler.co.kr
  Not connected : dynatec-online.com
  Connected     : dyndin.ru
  Connected     : dyskurs.com.ua
  Not connected : eastrandmotorlab.co.za
  Connected     : easy-home-sales.co.za
  Not connected : ebjvu.cn
  Connected     : ecemkopy.com.tr
  Connected     : ecolerubanvert.com
  Connected     : ecology.haglerbailly.com.pk
  Not connected : ecombox.store
  Connected     : ecowis.com
  Connected     : ecs-consult.com
  Connected     : edbapuotzed.wcnv20.cn
  Connected     : ederine.com
  Connected     : edesignz.co.za
  Not connected : e-devlet.aidatsifirla.com
  Connected     : edgeforensic.co.za
  Connected     : edgesecurity.co.za
  Not connected : ednpk.com
  Connected     : edu4.co.kr
  Not connected : efbirbilgisayar.com
  Connected     : eforas.com.tr
  Connected     : eforgaraj.com.tr
  Connected     : egedenmesrubat.com
  Connected     : egzotikshop.com
  Connected     : ejopeshot.wcnv20.cn
  Not connected : ekayapi.org
  Connected     : ekerticaret.com
  Connected     : e-kisa.com
  Not connected : e-kisalt.com
  Connected     : ekrembahcekapili.com
  Not connected : ekremmutlu.com
  Connected     : elan.com.pk
  Connected     : elektroniksigaralab.com
  Not connected : elemech.com.pk
  Not connected : elevate.ae
  Not connected : elitbizopa.info
  Connected     : elitecaptains.ae
  Connected     : eloquent.co.za
  Not connected : elvantente.com
  Connected     : embali.co.za
  Not connected : emeryconsult.com
  Connected     : eminelleranaokulu-etut.com
  Not connected : emiratesbuilders.net
  Connected     : emmabeckerle.com
  Connected     : empowerbridge.com
  Connected     : emware.co.za
  Not connected : en-content.com
  Connected     : encontrosmaracatu.com.br
  Not connected : enerjiport.org
  Not connected : engeltjieakademie.co.za
  Not connected : enginatalay.com
  Not connected : engpro.xyz
  Not connected : enka.blue
  Not connected : enmee.net
  Not connected : enpara.link
  Connected     : enpara.xyz
  Not connected : enterpriseunknown.top
  Not connected : entertaintoyou.com
  Connected     : entracorntrading.co.za
  Connected     : envi-herzog.de
  Connected     : envirotambang.com
  Connected     : envoysoft.net
  Not connected : epandemindestekuygulamasi0101.com
  Not connected : epandemindestekuygulamasi03.com
  Connected     : epcb.it
  Not connected : e-plakabakiyeyukleme.live
  Not connected : eplakasubemizi.com
  Connected     : epss.ae
  Connected     : equilibriumm.com
  Not connected : erdembirinsaat.com
  Connected     : erickeleo.com.br
  Connected     : ericouellettedev.com
  Connected     : ernestoangiolini.com
  Not connected : erniecommunications.co.za
  Connected     : erpmas.co.kr
  Not connected : ersagurunlerisatis.com
  Not connected : erzincansrc.com
  Not connected : espace-developpement.org
  Connected     : estemed.com
  Connected     : estudiperceptiva.com
  Not connected : esube.online-teb-tr.com
  Not connected : esube-tebcep-tr.com
  Connected     : esyuzllaeqa.wcnv20.cn
  Connected     : ethiccert.com
  Not connected : e-trafikgibodeme.ml
  Connected     : eur06.com
  Connected     : eurospa.ae
  Connected     : evansmokaba.com
  Not connected : evlilikpsikolojisi.com
  Not connected : exomi.es
  Connected     : experttutors.co.za
  Connected     : externalclient.ru
  Connected     : exuberant-group.com
  Connected     : fachwerkhaus.ws
  Connected     : faithmetal.com.pk
  Connected     : fal.cl
  Connected     : farhangroup.net
  Connected     : faries-studios.com
  Connected     : fasching-hallbergmoos.de
  Connected     : faturaniode.blogspot.com
  Connected     : fbmwornbszjq.wcnv20.cn
  Connected     : fbrvolume.co.za
  Not connected : fccltest.nayatel.com
  Connected     : fccorp.co.za
  Connected     : fcpconsultores.com.br
  Connected     : fduvubavc.wcnv20.cn
  Connected     : felicesfiestas.com.mx
  Not connected : feng-lian.com.tw
  Connected     : ferdinandsaf.s3.eu-central-1.amazonaws.com
  Not connected : fetchstats.net
  Connected     : ffc.com.pk
  Connected     : fgpcw-kr.edu.pk
  Not connected : fhfhhhrjtfg3637fgjd.at
  Not connected : fickstarelectrical.co.za
  Not connected : file.crosspoiimeri.com
  Connected     : files2.codecguide.com
  Connected     : files6.uludagbilisim.com
  Connected     : files.constantcontact.com
  Connected     : filllfoll.biz
  Not connected : finalnewstv.com
  Not connected : fincasoroel.es
  Connected     : findfree-people-friends.com
  Not connected : findinfo-more.com
  Connected     : fiqnqspwcw.wcnv20.cn
  Connected     : firebasestorage.googleapis.com
  Not connected : firebug.online
  Not connected : firsatdenizim.com
  Connected     : firstalliance.church
  Not connected : firstchoiceproperties.co.za
  Connected     : fitmentfurniture.com
  Connected     : fkdzqsopg.wcnv20.cn
  Connected     : fkqmbizmh.wcnv20.cn
  Not connected : flashardreset.com
  Connected     : flashroms.com
  Connected     : flooringforyou.co.uk
  Not connected : floratend.com
  Connected     : fltduty.ca
  Connected     : fmmakuwxomb.wcnv20.cn
  Connected     : fn.tc
  Connected     : fored.or.kr
  Connected     : forms.app
  Connected     : formtools.com
  Not connected : foryou.guru
  Connected     : fotodecolle-zagotovki.ru
  Connected     : fourrese.net
  Not connected : fourseasonscaterersdecorators.com
  Not connected : foxcabinets.com
  Connected     : fragranceoil.co.za
  Not connected : framevisualizer.co.za
  Connected     : freese-architekten.de
  Connected     : freeskl.com
  Not connected : freshhub.ae
  Connected     : frontiernet.net
  Connected     : fsegitimsaglikvakfi.org
  Not connected : fsproperties.co.za
  Not connected : ftu965.com
  Not connected : fuettern24.de
  Not connected : fun4kidz.co.za
  Connected     : funeralbusinesssolution.com
  Not connected : funisalodge.co.za
  Connected     : fustahermetic.com
  Connected     : fymumiddomj.wcnv20.cn
  Connected     : gabrio.it
  Connected     : galaxyforwarders.com
  Connected     : galwayprimary.co.za
  Not connected : gamevila.com
  Connected     : ganitis.gr
  Connected     : ganoset.com
  Not connected : garanti-bonus-flash-kart-islemleri-33808.portmap.io
  Not connected : garanti.mobileozelkampanya-firsatlari.tk
  Not connected : gateleben.com
  Not connected : gautengfarms.co.za
  Connected     : gbti.org.pk
  Connected     : gcjoccary.wcnv20.cn
  Not connected : gcmbdin.edu.pk
  Not connected : ge3w.com
  Not connected : gecmultan.edu.pk
  Connected     : geetransfers.co.za
  Connected     : gelecekdiyarbakirsigorta.com
  Not connected : gelosmedia.co.za
  Connected     : gemana.ae
  Not connected : genelhizmetsartlari.info
  Not connected : generictoners.co.za
  Not connected : genesisbs.co.za
  Not connected : geo-local.com
  Connected     : georginabringas.com
  Connected     : geotrading.ae
  Connected     : gestyy.com
  Connected     : getabletravel.co.za
  Not connected : getcord.co.za
  Not connected : get-paid-for-online-survey.com
  Not connected : gezegendunyasi.com
  Not connected : gfewew.com
  Connected     : gg.gg
  Not connected : giadinhvabe.net
  Not connected : gib.intvrg.org
  Connected     : gideonitesprojects.com
  Connected     : giginsulation.com
  Connected     : gildhroge.wcnv20.cn
  Not connected : gilforsenate.com
  Connected     : gipnjqpqxyv.wcnv20.cn
  Connected     : git.tc
  Not connected : giveaway-best.info
  Connected     : gizliemlak.com
  Connected     : glashandelmaxima.nl
  Not connected : glenbridge.co.za
  Connected     : glgroup.co.za
  Not connected : globalelectricalandconstruction.co.za
  Connected     : globalmitrateknik.com
  Connected     : globaltransformers.com
  Connected     : gncaf.or.kr
  Connected     : gnezdodesign.ru
  Connected     : gokcekolej.com
  Connected     : gokhantemiz.com
  Not connected : goldeninstitute.co.za
  Connected     : goldenyat.com
  Connected     : goliathstoneindustries.com
  Connected     : gongim.com
  Connected     : gongsinet.kr
  Not connected : gooddns.ir
  Connected     : goodproject.xyz
  Connected     : goo.gl
  Connected     : goojoo.net
  Connected     : goolineb2b.com
  Connected     : goolinegaming.com
  Not connected : gooline.net
  Not connected : gooline.pk
  Not connected : goolinespace.com
  Connected     : grainsandmore.com.pk
  Connected     : great.social
  Not connected : greebo.co.za
  Not connected : greenacrestf.co.za
  Connected     : greenedus.com
  Not connected : greenerlivingca.com
  Not connected : greenitylogistics.com
  Not connected : groblersdalprimecircle.co.za
  Connected     : gsmmid.com
  Not connected : gsnconsulting.co.za
  Not connected : gtrans.com.pk
  Connected     : gulenapart.com
  Not connected : guncelhaber.site
  Connected     : gundemhaber.org
  Connected     : gunrunners.com
  Connected     : gustomimarlik.com
  Connected     : gvs.com.pk
  Connected     : g-v-s.ru
  Connected     : gwdtwbkoybb.wcnv20.cn
  Connected     : gzlhrllkhis.wcnv20.cn
  Connected     : h1854684.stratoserver.net
  Connected     : haanohtmpfd.wcnv20.cn
  Not connected : haberplay.site
  Connected     : habibtextiles.pk
  Not connected : hacapuri.com.tr
  Not connected : haddownding.net
  Connected     : haeundaejugong.com
  Connected     : halimofset.com.tr
  Not connected : halk.finance
  Not connected : halk-parafly.com
  Not connected : hamaratili.com
  Not connected : hancertemizlik.com
  Connected     : hannanaslan.com.tr
  Not connected : haraticarpet.com
  Connected     : harmonyguesthouse.co.za
  Connected     : harryandbell.com
  Connected     : hartenboswaterpark.co.za
  Not connected : hashtag.com.pk
  Not connected : haveytv.com
  Connected     : havilahglo.co.za
  Connected     : hawk-lines.com
  Not connected : hayatverturkiye.com
  Connected     : hayrabolu.bel.tr
  Not connected : h-dubepromotions.co.za
  Connected     : healthzonesa.co.za
  Not connected : hediyemerkez.com
  Not connected : hellklartekirdag.com
  Not connected : hellofriend.pro
  Connected     : hellohealthy.pro
  Connected     : henweekendsbirmingham.co.uk
  Not connected : heritagetravelmw.com
  Connected     : hesterwebber.co.za
  Connected     : hexacam.com
  Connected     : heybekuruyemis.com.tr
  Not connected : hfhl.org.ls
  Connected     : hfvpylrssnbg.wcnv20.cn
  Not connected : hgs-online.net
  Not connected : hhrgdsmylyp.wcnv20.cn
  Not connected : highschoolsuperstar.co.za
  Not connected : hintdeals.com
  Not connected : hiperbolicus.com
  Connected     : hisabati.com
  Connected     : hisandherskennels.co.za
  Connected     : hitec-sa.com
  Not connected : hitupfitness.com
  Not connected : hivekorea.com
  Not connected : hizliy.sg-host.com
  Connected     : hjb-racing.co.za
  Connected     : hkwatercolors.com
  Connected     : hmholdings360.co.za
  Connected     : hmp.me
  Not connected : hmtal.ml
  Not connected : hobbystube.net
  Not connected : homebanku.com
  Connected     : homeofblinds.com
  Connected     : homeownersinsurance.ca
  Not connected : homesecuredata.com
  Connected     : homody.com
  Not connected : hort.pe
  Connected     : host4unix.net
  Connected     : hosthof.com
  Connected     : hosthof.pk
  Connected     : hostingvalley.co.uk
  Connected     : hotelyayoba.com
  Not connected : hotnews.16mb.com
  Connected     : hsbutton.co.kr
  Connected     : hsshivling.com
  Not connected : hstudymall.co.kr
  Not connected : h-u-i.co.za
  Connected     : huknkwhx.wcnv20.cn
  Connected     : hukukportal.com
  Not connected : huntingcargos.com
  Not connected : hutterstock.org
  Connected     : hwayou.com.tw
  Connected     : hybridauto.co.za
  Not connected : hygienix.com.tr
  Not connected : hypr.ink
  Not connected : hyunda-ce.com
  Not connected : hz11.cn
  Not connected : iadenedevlette.com
  Connected     : iancullen.co.za
  Not connected : i-app1.online
  Not connected : i-app4.online
  Not connected : i-app5.online
  Not connected : ibcvyqxbe3g2xwpc.onion.link
  Connected     : ibrahimtoruk.com
  Connected     : icapmecareers.com
  Connected     : icerike.com
  Not connected : iclikoftesiparisalinir.com
  Connected     : iconicciti.com
  Connected     : iconnectuae.com
  Not connected : icsswaziland.com
  Not connected : ieced.com.pk
  Connected     : iewa.sk
  Connected     : iggleconsulting.com
  Not connected : iglesiaciudaddedios.com
  Connected     : igstalk.com
  Connected     : ihlosiqs-pm.co.za
  Connected     : iida-sevensuns.com
  Connected     : iiee.edu.pk
  Not connected : iilii.site
  Not connected : iinvest4u.co.za
  Connected     : iklimlendirmekonferansi.com
  Connected     : ikrea.or.kr
  Not connected : ikusasatrainingprovider.co.za
  Connected     : ilaydapromosyon.com
  Not connected : ilkateknik.com
  Connected     : iloveat.fr
  Connected     : iluvit.co.za
  Connected     : imageliners.com
  Not connected : imgkisalt.cc
  Not connected : immaculatepainters.co.za
  Connected     : in2accounting.co.za
  Connected     : incoso.co.za
  Connected     : indepenmedia.nl
  Connected     : indiba-africa.co.za
  Not connected : indlovusecurity.co.za
  Connected     : indocraft.co.za
  Connected     : indulogistics.com
  Connected     : induworld.ae
  Not connected : inesapconcurso.webredirect.org
  Not connected : infinityondemand.club
  Not connected : infocop.me
  Not connected : infomate.biz
  Not connected : infratechconsulting.com
  Not connected : inmessageservice.com
  Not connected : inovea-engineering.com
  Not connected : insafradio.pk
  Not connected : insideforum.me
  Not connected : insta-art.co.za
  Not connected : instatakipci.xyz
  Connected     : intechbilisim.com
  Connected     : intelecom.co.za
  Connected     : intelligentprotection.co.za
  Connected     : intellismartglobal.com
  Connected     : intellmix.com
  Connected     : interafricaconsulting.com
  Connected     : interloaf.com
  Not connected : intra.cfecgcaquitaine.com
  Not connected : investaholdings.co.za
  Not connected : iooioioi.com
  Connected     : iorlamlnh.wcnv20.cn
  Connected     : ipripak.org
  Connected     : iptv16.com
  Connected     : iqra.co.za
  Connected     : iqtxbqzrczt.wcnv20.cn
  Connected     : ircshyzltf.wcnv20.cn
  Connected     : irfanandirfan.com
  Not connected : irispromo.co.za
  Not connected : irshadfoundation.co.za
  Connected     : iscm.edu.ar
  Connected     : isgs.com.pk
  Not connected : isibaniedu.co.za
  Connected     : islemn.com
  Not connected : isorgula.org
  Connected     : isound.co.za
  Connected     : istanbulteknikhirdavat.com
  Not connected : iswellwithme.com
  Connected     : itengineering.co.za
  Connected     : itsmaterial.us
  Connected     : itthub.com
  Connected     : iurhjfnmflsdf.com
  Connected     : iwqclywyrpv.wcnv20.cn
  Not connected : izeres.ml
  Not connected : izmaritat.com.tr
  Not connected : jakobieducation.co.za
  Connected     : jakuboweb.com
  Connected     : jamia-asria.org
  Connected     : jannahqu.org
  Connected     : jannatkhah.ir
  Not connected : jaysonmorrison.com
  Not connected : jaytagprojects.co.za
  Connected     : jdcorporate.co.za
  Not connected : jeanetteproperties.co.za
  Not connected : jhphotoedits.co.za
  Connected     : jitk.nusamandiri.ac.id
  Connected     : jixpvuezhj.wcnv20.cn
  Connected     : jjs.com.pk
  Connected     : joojlee.com
  Connected     : joyngroup.com
  Connected     : jozipainters.co.za
  Connected     : jsonstore.io
  Connected     : judo59.com
  Connected     : juelgkbeo.wcnv20.cn
  Not connected : jumpstart.ae
  Not connected : juniorad.co.za
  Connected     : justasec.com.au
  Connected     : justinwalker.co.za
  Not connected : jvpsfunerals.co.za
  Connected     : jwseshowe.co.za
  Connected     : kailanisilks.com
  Not connected : kamas.pk
  Not connected : karanfilturizm.com
  Not connected : karavantekstil.com
  Connected     : kartacnictvi.cz
  Connected     : kartprinterleri.com
  Not connected : kart.yillik-aidat-iade.online
  Connected     : kayalarmobilya.com.tr
  Connected     : kcdryervents.com
  Not connected : kedidirkedi.com
  Not connected : kencebaydenizcilik.com
  Not connected : kennynguyen.esy.es
  Not connected : kenzmedical.com
  Connected     : kernsmee.ru
  Connected     : kesanlazerepilasyon.com
  Not connected : ketabnema.com
  Connected     : keyzone.ws
  Not connected : khotsonglodge.co.ls
  Connected     : kIsa.link
  Connected     : kiliclarotokurtarici.com
  Not connected : kingsvc.cc
  Connected     : kirklareli.com.tr
  Connected     : kisa.link
  Not connected : kisalt.cc
  Not connected : kisalt.ru
  Connected     : kisalt.space
  Not connected : kisaltt.com
  Not connected : kisatr.link
  Not connected : kisa-url.com
  Not connected : kisharzoni.ir
  Connected     : kjdnc.gp114.net
  Not connected : kjsalmska.com
  Connected     : kkattorneys.com.pk
  Connected     : kkindonesia.com
  Connected     : k-kiosk.com
  Not connected : klasjna.com
  Not connected : klen.cc
  Not connected : klex.cc
  Not connected : klix.cc
  Not connected : kmannsjakpo.com
  Connected     : kne.co.kr
  Not connected : koldpressjuice.com
  Connected     : komatireddy.net
  Not connected : kooshesh-co.com
  Connected     : kopfkorea.com
  Connected     : kopilka.io
  Connected     : kopkarla.co.id
  Connected     : korajans.com
  Not connected : korea-tax.info
  Connected     : korhanplastik.com.tr
  Connected     : kosel.com.tr
  Connected     : koshcreative.co.uk
  Connected     : kosic.or.kr
  Connected     : ko.tc
  Connected     : kpzmxvutx.wcnv20.cn
  Connected     : kqsgctgwx.wcnv20.cn
  Connected     : kqtixvvffi.wcnv20.cn
  Not connected : kredikarti-yillik-aidatiadesi.com
  Not connected : kredim-aidat.com
  Not connected : krediogren.net
  Connected     : kse.org.pk
  Connected     : ksu.com.tr
  Connected     : ktxhsrmh.wcnv20.cn
  Connected     : kulagidaicecek.com
  Connected     : kumdo.org
  Connected     : kumsan.gen.tr
  Connected     : kurucuvincelektrik.com
  Connected     : kutt.it
  Connected     : kuzeyyeliinsaat.com.tr
  Not connected : kzmalik.com
  Not connected : labas-health.apps.ae
  Connected     : ladiescircle.co.za
  Not connected : lahorecoolingtower.com
  Not connected : lahorewholesalemarket.com
  Not connected : lamaggiora.it
  Connected     : lanamakotrue.com
  Connected     : laraibgroup.com
  Connected     : laserswat.com
  Connected     : last-time.ru
  Not connected : lavastandirustasi.com
  Connected     : lbmjhvic.wcnv20.cn
  Connected     : lbygrxeu.wcnv20.cn
  Not connected : ldams.org.ls
  Not connected : ldfghvcxsadfgr.at
  Not connected : LeadingWare.us
  Connected     : learnuxid.com
  Not connected : legacybeautysalon.com
  Not connected : legalpath.in
  Connected     : leholluwma.wcnv20.cn
  Not connected : leicon.it
  Not connected : lensofafrica.co.za
  Connected     : lgpkztmpyny.wcnv20.cn
  Connected     : licfpnda.wcnv20.cn
  Connected     : lightrdr.best
  Connected     : lihkab59.com
  Connected     : liladecor.com.tr
  Not connected : limanyapidenetim.com.tr
  Not connected : lingerieathome.eu
  Connected     : lingsao.com.cn
  Connected     : link.tl
  Connected     : littleblessingscotons.com
  Not connected : lj7qcktsne4nftzn.onion.link
  Connected     : llallagua.ch
  Not connected : lllilll.online
  Not connected : llllillll.site
  Connected     : lllllll.eu
  Not connected : llllllll.eu
  Connected     : lmy.de
  Connected     : lnhwmeopo.wcnv20.cn
  Connected     : loansonhomes.co.za
  Connected     : locknlockmall.com
  Connected     : logicsfort.com
  Not connected : login.dviznov.com
  Not connected : lohuis.ae
  Not connected : loiol.site
  Connected     : lol.tc
  Not connected : loop-is.com
  Connected     : loupeacara.net
  Connected     : loupeahak.com
  Connected     : loveandlight.aws3.net
  Not connected : love.thotiana.live
  Not connected : lppaportal.org.ls
  Connected     : lrskurumsal.com
  Connected     : lsbozonsta.wcnv20.cn
  Connected     : ltcxtseayai.wcnv20.cn
  Connected     : ltirqcmrseuq.wcnv20.cn
  Not connected : luleburgazlazerepilasyon.com
  Not connected : luleburgazyasamveteriner.com
  Connected     : luminix.kr
  Connected     : luminix.openhaja.com
  Connected     : luxconprojects.co.za
  Connected     : lwac.com
  Connected     : lyjjglrnpk.wcnv20.cn
  Connected     : lykvmhociat.wcnv20.cn
  Not connected : lymantase.com
  Connected     : m2.tc
  Connected     : m-3.co.za
  Connected     : macleodphotography.com
  Connected     : mail.estudiorrbp.com.uy
  Connected     : mailingservers.net
  Connected     : mail.sisnet.co.kr
  Not connected : makanaliabadian.ir
  Not connected : makroisleminiz.com
  Connected     : malboer.co.za
  Not connected : malbus.net
  Connected     : mamelina.com
  Connected     : maps-covid.com
  Not connected : marasgezikulubu.com
  Not connected : markagsm.com
  Not connected : markoislemler.com
  Not connected : marmaranergis.net
  Not connected : maskotmeyvepresi.com
  Connected     : matern-eger.de
  Connected     : maymaychihai.com
  Connected     : mayoorschoolabudhabi.com
  Connected     : mbrainingevents.com
  Connected     : mcwhorterdesign.com
  Not connected : mddesign.co.il
  Not connected : meaninurdu.com
  Not connected : mediaology.com.pk
  Connected     : mediatrendsistem.com
  Connected     : medicalfarmitalia.it
  Not connected : medikalayak.com
  Not connected : medikalduru.com.tr
  Connected     : medipedics.com
  Not connected : meistermv.com
  Not connected : melting-potes.com
  Connected     : memosigla.su
  Not connected : menaboracks.co.za
  Not connected : mentalhealthcheck.net
  Connected     : mepetresources.com
  Connected     : mepure.com
  Connected     : mercurysound.es
  Not connected : messviiqqq.info
  Connected     : mexicanagm.mx
  Connected     : mf-staging-html-01.sfo2.digitaloceanspaces.com
  Not connected : mfstol.ru
  Connected     : mgamule.co.za
  Not connected : mhealth.ae
  Not connected : mh-service.ru
  Not connected : miamirecyclecenters.com
  Connected     : microdots.in
  Connected     : mikimaths.com
  Connected     : mileage.krb.co.kr
  Connected     : missiegeslaagd.nl
  Not connected : misss-tem.com
  Not connected : mistcool.ae
  Not connected : mistingdubai.net
  Connected     : mitsubishiklimaservisim.net
  Not connected : mmetl.co.za
  Not connected : mobiextend.com
  Connected     : mobilsube.github.io
  Not connected : mobil-sube-islemleri-53078.portmap.io
  Not connected : mobilyacihan.com
  Not connected : moboradar.com
  Connected     : mohamedbinham.com
  Connected     : mokawafm.com
  Connected     : mokorotlocorporate.com
  Not connected : molepetravel.co.ls
  Not connected : moonge.cc
  Not connected : moonsteel.ae
  Not connected : moriarty.pw
  Not connected : moribelelab.co.za
  Not connected : motifahsap.com
  Connected     : mountsinaischool.edu.pk
  Not connected : mpsoren.cc
  Not connected : mrscrowe.net
  Connected     : mrveggy.com
  Not connected : msgcollection.com
  Not connected : mssewatrust.com
  Not connected : mtinetworkdubai.com
  Connected     : mtxhlihch.wcnv20.cn
  Connected     : muallematsela.com
  Not connected : muaxuanmedia.com
  Connected     : mukhtarfeeds.com
  Connected     : multichoice.com.pk
  Connected     : mumeizama.com
  Connected     : mumtazandbrohi.com
  Not connected : murtazaengin.com
  Connected     : musgqgkkvhv.wcnv20.cn
  Not connected : m.xiwayy2kn32bo3ko.onion.link
  Not connected : myaccount-security-check.com
  Connected     : mycar.ge
  Connected     : myhealthmedical.ae
  Not connected : myposte-aggiornamenti-online-bpol.ddns.mobi
  Not connected : mysushi.it
  Connected     : mytechgo.com
  Not connected : mywishlistapp.com
  Not connected : mzansicompanies.co.za
  Not connected : mzuzulionsclub.org
  Connected     : nabtires.com
  Connected     : nacindia.in
  Connected     : nakoserum.com
  Connected     : nalitravel.co.za
  Not connected : namplus.com.tr
  Not connected : narcolepsy-symptom-treatment.org
  Connected     : natenstedt.nl
  Connected     : nayablabs.com
  Connected     : nbftgceqhs.wcnv20.cn
  Not connected : nbscorporation.co.za
  Connected     : ndjbhhfcgt.wcnv20.cn
  Connected     : neomfarming.com
  Connected     : neonmedia.pl
  Not connected : neosophy.org
  Not connected : netflix-renews.com
  Connected     : netsolcomputers.in
  Connected     : nettoyage-plafond.com
  Not connected : news9pakistan.com
  Connected     : newstimesreportshonkong.desi
  Connected     : newtech-consulting.ae
  Not connected : ngomahconstruction.co.za
  Connected     : ngzxwmont.wcnv20.cn
  Connected     : nhirqndaon.wcnv20.cn
  Connected     : nhvojmolwnqh.wcnv20.cn
  Connected     : nicecars.com.ar
  Connected     : nifvaanigowl.wcnv20.cn
  Connected     : nisnlcmaf.wcnv20.cn
  Connected     : niufebbzmho.wcnv20.cn
  Connected     : njb-gmbh.com
  Connected     : njvrchvzdj.wcnv20.cn
  Connected     : nkmvrbluxbwy.wcnv20.cn
  Connected     : nkpztjnhl.wcnv20.cn
  Connected     : nodihyzv.wcnv20.cn
  Not connected : nolandsintl.com
  Connected     : nonyunzfgiac.wcnv20.cn
  Not connected : novaworld-novaland.vn
  Not connected : novusglobal.us
  Connected     : nowayright.biz
  Not connected : nowley-rus.ru
  Connected     : npfiamloyhc.wcnv20.cn
  Not connected : nrsp.org.pk
  Connected     : nsfund.mn
  Not connected : ntombizenhloso.co.za
  Not connected : ntvergidaireodeme.com
  Not connected : oas.gecmultan.edu.pk
  Connected     : obaidsaqerbusit.com
  Not connected : obkd4kx2f7fa4yzc.onion.link
  Not connected : oc.tsfengineering.com
  Connected     : odcpkintranet.org
  Connected     : odehnallzev.wcnv20.cn
  Connected     : odjhnbvb.wcnv20.cn
  Not connected : offficebox.com
  Not connected : office365onlinehome.com
  Not connected : officemysuppbox.com
  Connected     : officialdivinea.com
  Connected     : oftheearthphotography.com
  Connected     : oilandgaseng.com
  Not connected : o.lauraflower.info
  Connected     : olexco.ae
  Not connected : olimpogods.at
  Connected     : olymposarmy.com
  Connected     : ommjlanceacu.wcnv20.cn
  Connected     : omniaconsultingparma.it
  Connected     : oneway.clientresultsnow.com
  Not connected : online.garantibanktr.net
  Not connected : online.gtprivateportal-uk.com
  Connected     : onlinenews.com.pk
  Not connected : onlygoodm.com
  Connected     : onspotlinks.co.za
  Connected     : opendisclosure.org.za
  Connected     : opizxjjcok.wcnv20.cn
  Connected     : optimizeme.in
  Not connected : optiondeals.xyz
  Connected     : opydgvlegrdd.wcnv20.cn
  Connected     : opzhjcusgw.wcnv20.cn
  Not connected : orderchina.com.vn
  Not connected : organisejournalise.co.za
  Connected     : organmelody.top
  Not connected : orsiniconsulting.co.za
  Not connected : osim-heshbon.co.il
  Not connected : oursort.co.za
  Connected     : outdoorheater.ae
  Not connected : outletpiumini.springwaterfeatures.com
  Connected     : ovuixaxtelyn.wcnv20.cn
  Not connected : ozarkrov.com
  Connected     : ozdemirleryapi.com.tr
  Not connected : ozmetalpen.com
  Connected     : ozqbbajc.wcnv20.cn
  Not connected : paadasala.com.au
  Not connected : pacalik.net
  Connected     : pacificprime.ae
  Not connected : paimantrust.org
  Connected     : pakial.com
  Connected     : paksteel.com
  Connected     : paktechinfo.com
  Not connected : palcobase.com
  Not connected : palmon-law.co.il
  Connected     : pamforprogress.com
  Connected     : pamudzi.co.za
  Not connected : panathimaids.co.za
  Not connected : pandemiyardimlari14.online
  Not connected : panfam.co.za
  Not connected : paribdunya.destekparibe.click
  Not connected : passright.co.za
  Connected     : paste.ee
  Not connected : pastree.com.br
  Connected     : patioheater.ae
  Connected     : patrickreeves.com
  Not connected : paypal-resolving-case-limited.com
  Connected     : pazazta.com
  Connected     : pbcenter.home.pl
  Connected     : pcdesk.co.kr
  Not connected : pearse.gq
  Not connected : pegas56.ru
  Connected     : pelinfidancilik.com
  Not connected : peluqueriacaninaencordoba.com
  Connected     : pembegozluk.com
  Not connected : penisdevelopmentcentre.co.za
  Not connected : peopleiknow.org
  Connected     : peqvcogv.wcnv20.cn
  Not connected : perdetekirdag.com
  Connected     : perfectlabels.net
  Connected     : permanite.co.za
  Connected     : perryroadrecords.co.uk
  Not connected : personal2020flplayer.info
  Connected     : petromenllc.com
  Not connected : pgak.net
  Not connected : pgazefabrics.com
  Connected     : pgkhi.com
  Not connected : pgpaltex.co.za
  Not connected : phmetreci.com
  Not connected : phoenixdevs.ir
  Connected     : phoenix.zar.cc
  Connected     : photobookexpress.com
  Not connected : photoboothotm.co.za
  Connected     : photobucket.com
  Connected     : pickwick-poppins.com
  Connected     : pinnacleweld.co.za
  Connected     : pkix.pk
  Connected     : pkproud.com
  Not connected : placecomp.com
  Connected     : plantconsultants.co.za
  Connected     : plantengineering.com
  Not connected : plataoplomoo.com
  Not connected : playbrief.info
  Not connected : playgoogle.at
  Not connected : playsstore.net
  Not connected : pleasechecjthis4122.instanthq.com
  Connected     : plexsolutions.co.za
  Connected     : plik.root.gg
  Not connected : plug.msplugin.icu
  Connected     : pmanquetil.com
  Connected     : pmdpk.com
  Connected     : poemsan.info
  Connected     : popfilms.co.za
  Not connected : poste-banking-online.it
  Connected     : ppe4u.co.za
  Not connected : pragatihr.in
  Not connected : praisethey.top
  Connected     : prestbusiness.co.za
  Not connected : printernet.co.za
  Connected     : printinghub.co.za
  Connected     : priortable.top
  Connected     : privategallerie.info
  Not connected : privatlux.pw
  Connected     : procarsrl.com.ar
  Connected     : produkktc.com
  Connected     : proeventsports.co.za
  Not connected : profexsystem.com
  Not connected : programalani.com
  Connected     : project1114457.turbo.site
  Connected     : projectartdivvy.com
  Connected     : projekthd.com
  Connected     : promapharita.com
  Connected     : promechtransport.co.za
  Connected     : prommap.co.za
  Not connected : promotion14.online
  Connected     : pronette.co.za
  Connected     : proplumbing.co.za
  Not connected : proteinmarker.com
  Not connected : pspmagic.ru
  Connected     : pudphfpbyjql.wcnv20.cn
  Connected     : puigoxwoldrh.wcnv20.cn
  Connected     : pvp.tc
  Connected     : pymkwtzzdeb.wcnv20.cn
  Connected     : pzsyqyuyrh.wcnv20.cn
  Connected     : qfowzcnpyshu.wcnv20.cn
  Connected     : qhhvvrqmd.wcnv20.cn
  Connected     : qjzqbqlp.wcnv20.cn
  Connected     : qowjmumoeeg.wcnv20.cn
  Not connected : qqqright.info
  Connected     : qrcodes.pro
  Connected     : qsrimages.co.za
  Connected     : quecue.kr
  Not connected : quickauto.tools
  Connected     : quikteam.com
  Connected     : quraqlothnq.wcnv20.cn
  Connected     : qzkrbttsmc.wcnv20.cn
  Not connected : rabbleserlokclogin.com
  Not connected : radianthues.com
  Connected     : radyohaber.com.tr
  Not connected : rafinerimimarlik.com
  Connected     : ragazzemessenger.com
  Connected     : ramzcapital.com
  Not connected : ranionjgot5cud3p.onion.link
  Not connected : rapistindia.com
  Not connected : rashidalinawabshahi.com
  Connected     : rcivnzlvbj.wcnv20.cn
  Connected     : rcpk.co.za
  Not connected : rdpassistance.com
  Connected     : realdealhouse.eu
  Connected     : realstar.co.za
  Connected     : real-websolutions.nl
  Connected     : reatlegile.com
  Not connected : rebel.ae
  Connected     : rebrand.ly
  Not connected : rec-tec-ccr.nl
  Connected     : reesconsulting.co.za
  Connected     : refikengin.com
  Connected     : regionprinters.com
  Not connected : rejoicetheatre.com
  Connected     : ren7oaks.co.uk
  Not connected : reniko.co.za
  Not connected : rentwestq.com
  Not connected : resmibasvuru.org
  Not connected : retracepackage.com
  Not connected : revistadaybynight.com.br
  Not connected : rgoianrdfa.pw
  Connected     : ribbonlogistics.com
  Connected     : richardwillettphotography.com
  Not connected : rightwayfoundationpk.org
  Not connected : riolatravel.ru
  Connected     : risabaattorneys.com
  Not connected : ristorantetrefontane.it
  Connected     : risu.fi
  Not connected : rma-law.co.za
  Not connected : rmbmanufacturers.co.za
  Not connected : rmbmanufactures.co.za
  Not connected : rmmun.org.pk
  Connected     : robertwatton.co.uk
  Connected     : rocknsoulamerica.com
  Not connected : rockybalboa.at
  Connected     : rodtimberproducts.co.za
  Connected     : rollotech.co.za
  Connected     : romcablu.com
  Not connected : ronjustthetrebho.net
  Not connected : roohaniworkshop.com
  Connected     : rorymartin8.info
  Connected     : roseace.com.pk
  Not connected : roshnee.co.za
  Connected     : roshnisindh.org.pk
  Connected     : royalhijyen.com
  Connected     : roycolemandds.com
  Not connected : rsbholdings.co.za
  Not connected : rsmaluminium.co.za
  Not connected : rss.nbcpost.com
  Not connected : rstextilesourcing.com
  Connected     : rtaep.org
  Connected     : rtwjrqocw.wcnv20.cn
  Connected     : rudraagrointernational.com
  Connected     : runkel.com.mx
  Connected     : rupertsherwood.com
  Connected     : ru.tc
  Not connected : rutor.space
  Connected     : rvnstudios.co.za
  Not connected : ryanchristiefurniture.co.za
  Connected     : rydezbfgc.wcnv20.cn
  Connected     : s3.amazonaws.com
  Connected     : s3-eu-west-1.amazonaws.com
  Connected     : s3.us-east-2.amazonaws.com
  Not connected : s5ncertificationservices.co.za
  Connected     : saacma.co.za
  Connected     : sabinaengineering.com
  Connected     : sabines-marmeladen.de
  Not connected : sadcta-client.co.za
  Connected     : saemaeul.mireene.com
  Not connected : safakgazetesi.com.tr
  Not connected : sahandlanguageservices.com
  Not connected : sahinhurdageridonusum.net
  Not connected : sajidenterprises.com
  Connected     : sallyscott.co.za
  Not connected : sallysellmore.com
  Connected     : salmanandassociates.com.pk
  Not connected : salonalara.com
  Connected     : sampling-group.com
  Connected     : samurmakina.com.tr
  Connected     : sanco.it
  Connected     : sancorbr.com.br
  Connected     : sandalci.com.tr
  Connected     : sanko1.co.jp
  Not connected : santanderbrazil.com
  Connected     : sarahtame.at
  Connected     : sarilartarim.com
  Connected     : saritohum.com
  Not connected : satcomputers.co.za
  Connected     : satuwrite.com
  Connected     : satwa.ae
  Not connected : saunaesofmansatis.net
  Not connected : schaye.net
  Connected     : schw4rz.com
  Connected     : sclionionescu.ro
  Connected     : sc-otdushina.ru
  Not connected : scottfranch.org
  Connected     : scouting-bvb.nl
  Connected     : sdorf.com.br
  Not connected : searchlightcare.com
  Not connected : secundaria50.edu.mx
  Not connected : secure-ingdirect.top
  Not connected : securitybitches1.at
  Not connected : securitybitches3.at
  Connected     : seffafkartvizitim.com
  Not connected : sefikengfarm.co.ls
  Not connected : sefukaletrading.co.za
  Connected     : seismicfactory.co.za
  Not connected : seler.cc
  Not connected : seloanaholdings.co.za
  Not connected : selvitarim.com.tr
  Not connected : senaryolarim.com
  Not connected : seoforecommerce.org
  Connected     : seoinlahorepakistan.com
  Not connected : sepetim7.tk
  Connected     : serversvalley.com
  Not connected : service24.report
  Connected     : servicebox.co.za
  Not connected : servicedlimitedchronicles.com
  Not connected : serviced-limited-confirm.com
  Not connected : serviced-limiteds-accounts.com
  Not connected : servicetrade24.ru
  Connected     : sesisitmer.com
  Connected     : sestili.it
  Not connected : setfalc.com
  Not connected : sewh6lmdeov62w2h.onion.link
  Connected     : sexex.co.il
  Not connected : seyidesen.com.tr
  Not connected : sghee.pw
  Not connected : sg-host.com
  Connected     : shahkara.com.tr
  Connected     : shejipxw.com
  Not connected : sheqworld.co.za
  Not connected : sherylbro.net
  Connected     : shgida.com
  Connected     : shineindian.com
  Not connected : shinestars-lifestyle.com
  Not connected : shopsshops.de
  Not connected : shopstation.com.au
  Connected     : short.pe
  Not connected : short-url.net
  Connected     : shortygram.com
  Connected     : shreeconstructions.co.in
  Connected     : shullen.co.za
  Connected     : shurabura.org
  Connected     : shurt.pw
  Not connected : sicakgelismeler.com
  Not connected : sieqwarteg.com
  Connected     : sightselect.top
  Connected     : sigmahydraulics.com
  Connected     : signo-comunicacion.com.ar
  Not connected : signsoftime.co.za
  Connected     : sikanderajam.com
  Not connected : silivrisonmezemlak.com
  Not connected : silverwingclub.pk
  Not connected : simosimo.ch
  Connected     : simpexbpo.com
  Not connected : simplecreative.design
  Connected     : simpleks.co.za
  Not connected : simplyplumbing.co.za
  Not connected : simpowerlogistics.co.za
  Connected     : sinebar.co.za
  Not connected : sipambi-projects.co.za
  Not connected : sirijayareddypsychologist.com
  Connected     : sirinadas.com
  Connected     : sirketcv.com
  Connected     : sisco-ent.com
  Connected     : sishubamedia.co.za
  Connected     : sistemal.net.tr
  Connected     : sitasbeton.com.tr
  Not connected : site2.cybertechpp.com
  Connected     : site.inquima.com.br
  Not connected : siyabuselelatransport.co.za
  Connected     : sjog.mw
  Connected     : skbyapi.com.tr
  Not connected : skhaleni.co.za
  Connected     : skjcbntd.wcnv20.cn
  Connected     : skmoljjpc.wcnv20.cn
  Connected     : skyblueprint.co.za
  Connected     : slcmprojects.co.za
  Connected     : slwtech.com
  Connected     : smartcare.com.tr
  Connected     : smarterbaby.com
  Not connected : smartnewjerseyhomebuyers.com
  Not connected : smartoools.co.za
  Connected     : smart-sense.co.il
  Not connected : smartwashingtonhomebuyers.com
  Connected     : smpinsankamil.sch.id
  Connected     : snackattack.co.za
  Connected     : snip.ly
  Connected     : snum.or.kr
  Not connected : soatti2.com
  Not connected : soccertotsuae.com
  Connected     : sofa.rs
  Connected     : softwarehub.co.za
  Not connected : softxstech.com
  Not connected : sohoort.p
  Connected     : solartree.pk
  Connected     : soligro.com
  Not connected : solomedikal.com
  Connected     : sonafoundation.org.pk
  Connected     : sonneteck.com
  Connected     : sonnyelectric.com
  Not connected : sonotac.eu
  Not connected : sonucbirebiregitim.com
  Connected     : sookgail.su
  Not connected : sorgulavtr.info
  Connected     : sorumvar.net
  Not connected : soslavanderia.com.co
  Not connected : soulreaver.at
  Not connected : souqwalls.com
  Connected     : sowetojive.co.za
  Not connected : sparepartiran.com
  Not connected : spazioireos.it
  Not connected : speedmasterprinters.co.za
  Not connected : speranza2000.com
  Not connected : spitbraaihire.co.za
  Connected     : spoyfydyq.wcnv20.cn
  Not connected : sprintpackersnmovers.com
  Connected     : srngroup.com.tr
  Connected     : srppmqyqhv.wcnv20.cn
  Not connected : ssnoways.info
  Connected     : ssonweb.com
  Not connected : standardfederalproperties.com
  Connected     : startr.com
  Not connected : static.travelclothes.org
  Connected     : stayfitphysio.ca
  Not connected : stemcellenhancementresearch.com
  Not connected : stephenandmaryodietefoundation.org
  Not connected : stevegardens.co.za
  Connected     : stockwhip.top
  Not connected : storegoogle.at
  Connected     : strictlybusiness.co.za
  Connected     : stubbornsystems.com
  Not connected : student.gecmultan.edu.pk
  Connected     : studioslefteris.gr
  Connected     : studiospa.com.pl
  Connected     : style1.co.kr
  Not connected : sudopsuedo1.su
  Not connected : sudopsuedo2.su
  Not connected : sudopsuedo3.su
  Connected     : sullivanprimary.co.za
  Connected     : sumato.com.tr
  Not connected : summi.space
  Connected     : sumzzindustry.com
  Connected     : sunchipaint.com.vn
  Connected     : sunnyinteractive.com.au
  Connected     : sunnypalour.com
  Not connected : superdelight.co.za
  Not connected : supersavari.com
  Not connected : support-apple-myapple.com
  Connected     : support-ip.com
  Connected     : susinternational.com
  Not connected : suzzyshuttles.co.za
  Not connected : svrwood.com
  Connected     : swarm-solutions.com
  Connected     : symergy.co.za
  Not connected : systemaraba.com
  Not connected : tabletbasvuru.com
  Connected     : taigen-landscape.com
  Not connected : taigen-landspace.com
  Not connected : tailer.it
  Connected     : taloodd.ru
  Connected     : tamer.info
  Connected     : tanati.co.za
  Connected     : tandemtraining.co.za
  Connected     : ta-pu.ir
  Not connected : targeter.su
  Connected     : tasmeemgroup.com
  Not connected : tatildomaini.com
  Not connected : tawaair.com
  Connected     : tbhwrm1.org
  Connected     : tcpbereka.co.za
  Not connected : teamspit.pro
  Not connected : tebimse.com
  Not connected : teblicep.com
  Not connected : technicians.global
  Connected     : technics.pk
  Connected     : teck.fr
  Connected     : tecnigrafite.com
  Connected     : tecnoriego.com.ec
  Not connected : tedwoodworking.pro
  Connected     : tees321.com
  Not connected : tekfordummies.com
  Connected     : tek.link
  Not connected : telesolutionsconsultants.com
  Connected     : telete.in
  Connected     : teonxtpsfs.wcnv20.cn
  Not connected : teorija.rs
  Not connected : tepsecurity.co.za
  Connected     : terapine.com
  Not connected : test136.siteholder.ru
  Not connected : thanlwintimes.com
  Connected     : thealtarofworship.co.za
  Connected     : thebedspace.com
  Connected     : theblackout.fr
  Not connected : thecommunicator.icu
  Not connected : thecompasssolutions.co.za
  Connected     : thedailymusicshow.com
  Not connected : thedournalist.com
  Connected     : theguitarstudio.co.za
  Connected     : theharith.com
  Not connected : thelawyerscanvas.pk
  Not connected : themeastralgratuit.com
  Not connected : themotoringcalendar.co.za
  Connected     : themusicstudio.co.za
  Connected     : thepandoinitiative.org
  Connected     : thepianostudio.co.za
  Not connected : thietkewebantuong.com
  Connected     : thiscouldbeyourluckyday.net
  Not connected : thoughtsandthings.co.za
  Connected     : threelivingprojects.co.za
  Not connected : tiaragroup.es
  Connected     : ticketstekoop.nl
  Connected     : tiendatresort.com.vn
  Connected     : tilbemarket.com
  Connected     : tiny.cc
  Connected     : tinycc.com
  Connected     : tiny.ie
  Connected     : tinyurl.com
  Connected     : tippinggate.co.za
  Connected     : tiramisu.it
  Not connected : tlcservers.co.za
  Connected     : tljpofsq.wcnv20.cn
  Not connected : tmkprojects.co.za
  Connected     : tngjihyzcqs.wcnv20.cn
  Connected     : tombstonedesigns.co.za
  Not connected : tomcat-king.pw
  Not connected : tonaro.co.za
  Connected     : tootco.ir
  Not connected : topanswertips.info
  Not connected : topgiftsrewards.com
  Connected     : tophillsports.com
  Connected     : toramanlar.com.tr
  Not connected : tosmacakes.co.za
  Connected     : totallyfreepeoplesearch.org
  Not connected : touritx.com
  Connected     : tqyketpmooe.wcnv20.cn
  Not connected : track-google.at
  Not connected : trackgoogle.at
  Connected     : tracklink.top
  Connected     : tradernews.xyz
  Connected     : tradernox.com
  Connected     : traders-forum.com
  Not connected : trafikcezasiode.ml
  Not connected : trainings.smartscape.eu
  Connected     : transactionjunction.co.za
  Not connected : transport.machangikanalda.org
  Connected     : trashbox.ru
  Not connected : trbakiyeyukmesi.live
  Not connected : tr-garantimobil.online
  Not connected : trhalkbankkobimm.com
  Not connected : triconfabrication.com
  Not connected : triumphsportscarclub-kzn.co.za
  Not connected : trkisalt.com
  Connected     : tr.pinterest.com
  Not connected : trskl.com.br
  Connected     : tsmgranite.com
  Connected     : tuminsaat.com
  Connected     : turanlarcitsistemleri.com
  Connected     : turfschiploge.nl
  Connected     : turkey-healthform.org
  Connected     : turmash.ru
  Connected     : tuules.com
  Not connected : twickenhamsa.co.za
  Not connected : twinnovations.co.za
  Not connected : twittetakip.com
  Connected     : twocups.io
  Connected     : u.24d.ir
  Connected     : ucarecdn.com
  Not connected : ultrapexsustainable.org.za
  Not connected : ulusgaranti.com
  Connected     : umobidownload.com
  Connected     : unboxingtoycon.mx
  Connected     : uniteddatabase.net
  Not connected : unitypestcontrolandservices.com
  Connected     : unlimit517.co.jp
  Connected     : unveilmimic.top
  Connected     : upfxunlvuvud.wcnv20.cn
  Connected     : uptown-trading.zar.cc
  Connected     : urbaniak.waw.pl
  Connected     : urorccqbcgo.wcnv20.cn
  Connected     : usasecurefiles.com
  Connected     : uselessshoot.top
  Not connected : ushostinc.com
  Connected     : utka.su
  Not connected : utl-ae.ml
  Not connected : utor.co.za
  Connected     : uuwgcsedmih.wcnv20.cn
  Connected     : uvkkthfalc.wcnv20.cn
  Connected     : uxzxyheama.wcnv20.cn
  Connected     : uybgklxze.wcnv20.cn
  Connected     : uyvpnljii.wcnv20.cn
  Connected     : vakifmobil.com
  Connected     : vaner.com.sg
  Connected     : vantuwer.sakura.ne.jp
  Connected     : vatmiddleeast.com
  Not connected : vayvonvietcombank24h.net
  Not connected : vengemutfak.com
  Connected     : ventronics.co.za
  Connected     : venturemeets.com
  Not connected : verifiedseller.co.za
  Connected     : versal.media
  Not connected : vesecase.com
  Connected     : veytrmzdp.wcnv20.cn
  Connected     : vfrrroatad.wcnv20.cn
  Not connected : vhuenilodge.co.za
  Connected     : vhupo-tours.com
  Connected     : viasalvia.de
  Connected     : vibaavaacademy.com
  Connected     : victorypipe.com.pk
  Not connected : vieswablesgrowesr.com
  Connected     : viewphotos.co.za
  Not connected : vintage.ae
  Not connected : viralstyle.shop
  Connected     : visionclinic.co.ls
  Connected     : visit.news
  Not connected : visudam.ga
  Connected     : vital.com.pk
  Connected     : vitaliberatatraining.com
  Connected     : vkmodule.com.ua
  Connected     : vlgstal.ru
  Not connected : vodafoneinfinity.sytes.net
  Not connected : volminpetshop.com
  Connected     : votehad.su
  Connected     : vrqxkvbuphe.wcnv20.cn
  Connected     : vrzbaloery.wcnv20.cn
  Connected     : vseteplo.by
  Connected     : vtescebu.com
  Not connected : vumavaluations.co.za
  Connected     : vvfovofw.wcnv20.cn
  Connected     : vytmrwglkink.wcnv20.cn
  Not connected : w1africa.co
  Connected     : waohost.com
  Not connected : warrixmalaysia.com.my
  Not connected : waterforevents.co.za
  Connected     : wavecafe.co.za
  Connected     : wbdrivingschool.com
  Not connected : wcop.site
  Not connected : wdsc.co.za
  Connected     : web28tech.co.za
  Not connected : web.cloudfront.kz
  Connected     : web.eng.ubu.ac.th
  Connected     : webfuari.com
  Not connected : webhostinc.net
  Not connected : webseorank.org
  Connected     : webzadminverify.czweb.org
  Not connected : weddingcarsbury.co.uk
  Not connected : weddingcarsrochdale.co.uk
  Connected     : wegallop.com
  Connected     : weinvest.co.za
  Not connected : weituweritoiwetzer.at
  Connected     : welcomecaters.com
  Connected     : wellscoastink.biz
  Connected     : weserve.world
  Connected     : wexznnplhyu.wcnv20.cn
  Connected     : w.gdown.baidu.com
  Connected     : whdacxerg.wcnv20.cn
  Connected     : whitepearlpro.co.za
  Connected     : whqpvloyhh.wcnv20.cn
  Connected     : whvsvmhbhxhn.wcnv20.cn
  Connected     : wicloud.pk
  Connected     : willemshoeck.nl
  Connected     : willpowerpos.co.za
  Not connected : willtecindustrial.com.br
  Connected     : winagainstebola.com
  Connected     : windowsupdate-microsoft.com
  Not connected : windupdate.serveftp.com
  Not connected : winebiddingthailand.com
  Connected     : wink0nproject2016.com
  Connected     : wlrrgdjww.wcnv20.cn
  Not connected : wmcsoj.edu.pk
  Connected     : wmsggdev.wcnv20.cn
  Connected     : woellhaf-it.de
  Connected     : womanblues.su
  Not connected : woodracefurniture.co.za
  Connected     : worldfoodstory.co.uk
  Connected     : world-tour2000.com
  Connected     : worshipaltar.co.za
  Connected     : wowpress.co.kr
  Not connected : wqetwertwertwerxcvbxcv.at
  Connected     : wwhvcyhro.wcnv20.cn
  Connected     : a1-stays.com
  Connected     : aacademybh.com
  Connected     : aalotv.com
  Not connected : aamins-notebook.com
  Not connected : aarchtech.com
  Connected     : abbymouldings.co.uk
  Connected     : abies.co.za
  Not connected : abmgroups.com.pk
  Not connected : aboserver.xyz
  Not connected : abradvd.com.br
  Connected     : abruzzogenealogy.com
  Not connected : abumohammed.ae
  Not connected : accidentatworkcompensationsolicitors.co.uk
  Connected     : accountingbookshub.com
  Connected     : ace-data.com
  Not connected : acer-parts.co.za
  Connected     : achrock.com
  Not connected : achu.io
  Connected     : acintyaenergy.com
  Connected     : actingtheparty.co.uk
  Connected     : adamaircon.com
  Connected     : addsaintgaudens.com
  Not connected : adiltradingco.pk
  Not connected : adizue.com
  Not connected : adrianjade.com
  Connected     : adultchannelsguide.com
  Connected     : advcadsys.com
  Not connected : adwiyat.com
  Not connected : aenon.org.pl
  Connected     : aesthetictrainingsolutions.com
  Connected     : affordablehomecare.org
  Connected     : afikagroup.com
  Connected     : afikapower.com
  Connected     : afikaquadpro.com
  Connected     : afmedan.org
  Connected     : afpf.org.pk
  Connected     : after.vix.br
  Connected     : agencesylvieleclerc.com
  Not connected : agenceuhd.com
  Not connected : agharazaali.com
  Not connected : agirlgonewine.com
  Not connected : agrininmarkalari.com
  Connected     : ahamson.com
  Not connected : ahstorepk.com
  Connected     : aioucheats.com
  Not connected : aircafe24.com
  Connected     : air-mag.ro
  Connected     : airporttaxi-uk.co.uk
  Not connected : ajmansexymassagebodytobody.com
  Not connected : akhbar-e-kohistan.com
  Connected     : akkurtgida.com.tr
  Connected     : aladiyat.ae
  Not connected : alakml.com
  Connected     : albertamechanical.ca
  Connected     : albertaprimebeef.com
  Connected     : alcalumni.com
  Not connected : alcaninsaat.com.tr
  Connected     : alessioborzuola.com
  Not connected : alestilorachel.com
  Connected     : alexanderhomestead.com
  Connected     : alexandrasternin.com
  Connected     : alexjeffersonconsulting.com
  Connected     : alexponcet.com
  Connected     : alfransia.com
  Not connected : alfredoposada.com
  Connected     : algom-law.com
  Connected     : aliandconsulting.com
  Not connected : alinn-u-yin.com
  Not connected : all4schoolstore.com
  Connected     : allbuyer.co.uk
  Connected     : allcopytoners.com
  Not connected : allin-chain.com
  Not connected : allstylus.com.br
  Connected     : allwestdental.com
  Not connected : almaarefut.com
  Not connected : alothman-gt.com
  Connected     : alpacal.com
  Not connected : alpenfitil.com
  Connected     : alphapixa.com
  Connected     : alphapridesafaris.com
  Connected     : alshohub.org
  Not connected : altaica.ca
  Connected     : alteaparadise.com
  Connected     : altinfiyatlari.org
  Not connected : altingunes.com
  Connected     : alvarezarquitectos.com
  Connected     : amateurastronomy.org
  Not connected : amazingbuyrd.com
  Not connected : amazingtour.pk
  Connected     : ambientproperty.com
  Not connected : a-mentor.com
  Connected     : amerindgen.com
  Not connected : amexcars.info
  Connected     : amighini.it
  Connected     : amika.hr
  Not connected : amjobs.co.uk
  Connected     : amphibiblechurch.com
  Not connected : ampleadminservices.com
  Not connected : anatapackaging.com
  Connected     : ancamamara.com
  Connected     : andreabelfi.com
  Connected     : andrebruton.com
  Connected     : androidwikihow.com
  Not connected : angelesrevista.com
  Not connected : animationinisrael.org
  Connected     : antc.ch
  Not connected : antigonisworld.com
  Connected     : antirughenaturale.com
  Connected     : antoanetapalikarska.com
  Connected     : antojoentucocina.com
  Not connected : aofdersleri.net
  Connected     : aoryx.ae
  Not connected : apliety.co.il
  Connected     : apmequestrian.com
  Connected     : applecartng.com
  Connected     : appster.it
  Connected     : aprendiendoencasa.com
  Not connected : aptibet.org
  Connected     : arabaoyunlari.org
  Connected     : arabblower.com
  Not connected : arabgamenetwork.com
  Connected     : arabiccasinochoice.com
  Connected     : ariehandomri.com
  Not connected : arieirawanfauzi.com
  Not connected : armateknolojimerkezi.com
  Connected     : atcouriers.co.za
  Connected     : atimuzik.com.tr
  Not connected : a-zgrup.com
  Not connected : babarphotography.com
  Not connected : babypk.net
  Connected     : bahrialive.com
  Not connected : banditrockradio.com
  Connected     : bankerbus.com
  Connected     : baossdigital.com
  Connected     : bashancorp.co.za
  Connected     : bashirbrothers.com
  Not connected : basoglucit.com
  Connected     : baspk.com
  Connected     : batik.com.pk
  Not connected : bazookagames.net
  Not connected : bbconlinenetwork.com
  Not connected : bcdf.org.pk
  Not connected : bcppro.com
  Connected     : beeground.com
  Connected     : be-indigene.be
  Connected     : berkyilmaz.com.tr
  Connected     : bertflierdesign.nl
  Connected     : besman.de
  Not connected : bestarticlespinnerr.com
  Not connected : bestcarpoint.com.pk
  Connected     : bestdecorativemirrors.com
  Connected     : bestgroupqatar.com
  Not connected : bestmerchdesigns.com
  Connected     : bgoodideas.com
  Connected     : bhakkarrishtey.com
  Connected     : bhft.org.uk
  Not connected : bhsmusic.net
  Connected     : big-bang.ae
  Not connected : bigboobsdirectory.com
  Not connected : bindaswords.com
  Not connected : binsafa.com
  Connected     : bioforgehealth.org
  Connected     : biolifeenterprises.com
  Connected     : biosetinlabs.com
  Not connected : bitcoinplasma.com
  Not connected : bitp.co.za
  Connected     : bitstream.pk
  Connected     : bizbranding.net
  Connected     : bizxess.com
  Connected     : blaahblaah.com
  Connected     : blackstar.com.pk
  Not connected : blackvue.com.pk
  Connected     : blattoamsterdam.com
  Connected     : blockdos.net
  Not connected : blog4cheer.com
  Connected     : bloggerfreak.com
  Connected     : bloggingscout.com
  Connected     : bloomfieldhall.edu.pk
  Connected     : blubaytrading.com
  Connected     : bmcars.nl
  Connected     : boardexeter.co.uk
  Connected     : bolagsregistrering.eu
  Not connected : bookrack.pk
  Not connected : booksmart.pk
  Connected     : boundmix.com
  Connected     : boutiquesxxx.com
  Not connected : boxyfast.com
  Not connected : boybirth.com
  Not connected : braidhairextensions.com
  Connected     : brand-stories.gr
  Connected     : brianzashop.it
  Not connected : brickbybricklegalconsultants.com
  Not connected : bridgestobodhi.org
  Connected     : britishasia-equip.co.uk
  Not connected : britishofficefitout.com
  Not connected : brooks.edu.pk
  Not connected : brotherthread.com
  Connected     : budgetestate.pk
  Connected     : buhlebayoacademy.com
  Not connected : buraqlubricant.com
  Not connected : buy4you.pk
  Not connected : buyandenjoy.pk
  Connected     : buydocumentonline.com
  Not connected : buymore360.com
  Not connected : cafeperrin.com
  Connected     : california-rehab-directory.com
  Connected     : capecrystal.co.za
  Connected     : cartridgecave.co.za
  Not connected : centreforgovernance.uk
  Connected     : cigercihamza.com
  Not connected : cle.ae
  Not connected : clearviewuae.com
  Not connected : competitiveedoptions.com
  Not connected : cookingtrader.net
  Not connected : core.org.pk
  Connected     : core-techworld.com
  Not connected : crackthat.net
  Not connected : creamyicecafe.com
  Connected     : crissamconsulting.co.za
  Connected     : daleth.co.za
  Not connected : www-denizbank14subat.com
  Not connected : wwwdeniz-login.com
  Connected     : difpt.org
  Connected     : diginixtech.com
  Connected     : digitalmedia.co.za
  Connected     : dingaanassociates.co.za
  Not connected : dopetroleum.com
  Connected     : drug-treatment-directory.com
  Connected     : duotonedigital.co.za
  Not connected : dws-gov.co.za
  Connected     : easy-home-sales.co.za
  Connected     : edesignz.co.za
  Connected     : elite4print.com
  Connected     : eloquent.co.za
  Not connected : engeltjieakademie.co.za
  Not connected : enyenigelinlikmodelleri.net
  Connected     : evoko.ae
  Not connected : execwash.ae
  Not connected : exomi.es
  Connected     : exuberant-group.com
  Connected     : ffc.com.pk
  Not connected : www-flndmylphone.com
  Not connected : freshhub.ae
  Not connected : fullcircle-design.com
  Not connected : fun4kidz.co.za
  Connected     : galaxyforwarders.com
  Connected     : galwayprimary.co.za
  Not connected : generictoners.co.za
  Connected     : geotrading.ae
  Not connected : getcord.co.za
  Not connected : gilforsenate.com
  Connected     : gokhantemiz.com
  Not connected : gokhanturizmvetemizlik.com
  Connected     : goolineb2b.com
  Not connected : gooline.net
  Not connected : gooline.pk
  Not connected : goolinespace.com
  Connected     : gsmmid.com
  Connected     : gustomimarlik.com
  Connected     : handrush.com
  Connected     : harmonyguesthouse.co.za
  Not connected : hfhl.org.ls
  Connected     : hosthof.com
  Connected     : humorcarbons.com
  Connected     : iancullen.co.za
  Not connected : ibadirect.com
  Connected     : icapmecareers.com
  Not connected : icsswaziland.com
  Not connected : ieced.com.pk
  Connected     : igo3.co.il
  Connected     : ihlosiqs-pm.co.za
  Connected     : induworld.ae
  Not connected : infratechconsulting.com
  Connected     : ioewjhfdhduiusfh.com
  Connected     : ipripak.org
  Not connected : kaahm.com
  Connected     : kcnp.or.kr
  Not connected : khotsonglodge.co.ls
  Connected     : kisa.link
  Connected     : koshcreative.co.uk
  Not connected : lamiademir.com
  Connected     : l-n.co.il
  Connected     : loansonhomes.co.za
  Connected     : logicsfort.com
  Not connected : londonbeautyclinic.pk
  Not connected : m-3.co.za
  Connected     : malboer.co.za
  Not connected : mcb-law.co.il
  Connected     : mikimaths.com
  Connected     : moboradar.com
  Connected     : mumtazandbrohi.com
  Connected     : mycogentrading.com
  Not connected : mzansicompanies.co.za
  Connected     : nalitravel.co.za
  Not connected : nangapia.org.pk
  Connected     : obaidsaqerbusit.com
  Connected     : odcpkintranet.org
  Connected     : olexco.ae
  Not connected : organisejournalise.co.za
  Connected     : otprema.hr
  Not connected : oursort.co.za
  Connected     : paktechinfo.com
  Not connected : penisdevelopmentcentre.co.za
  Connected     : peoplealley.com
  Connected     : phoenix.zar.cc
  Connected     : popfilms.co.za
  Connected     : printinghub.co.za
  Connected     : proplumbing.co.za
  Connected     : proxelinternational.co.za
  Connected     : qsrimages.co.za
  Not connected : rashidalinawabshahi.com
  Connected     : rcpk.co.za
  Not connected : rejoicetheatre.com
  Connected     : rjsoftware.com
  Not connected : s5ncertificationservices.co.za
  Not connected : www-saglikbakanligi.xyz
  Not connected : salonalara.com
  Not connected : sexualwellbeingfoundation.org
  Connected     : shamsitech.com
  Not connected : silakboevents.com
  Connected     : simpleks.co.za
  Not connected : smartoools.co.za
  Connected     : snackattack.co.za
  Connected     : soccerkidsdubai.com
  Connected     : sorumvar.net
  Connected     : sowetojive.co.za
  Not connected : speedmasterprinters.co.za
  Connected     : superlead.org
  Connected     : tanati.co.za
  Connected     : terapine.com
  Connected     : theguitarstudio.co.za
  Connected     : thelightcleaning.co.za
  Connected     : themusicstudio.co.za
  Not connected : thoughtsandthings.co.za
  Connected     : thusoconsulting.co.za
  Connected     : tntfire.co.za
  Not connected : tonaro.co.za
  Not connected : triconfabrication.com
  Not connected : ultrapexsustainable.org.za
  Connected     : uniquelook.net
  Connected     : vhupo-tours.com
  Connected     : volleybold.com
  Connected     : w33588.com
  Connected     : waohost.com
  Not connected : waterforevents.co.za
  Connected     : wbdrivingschool.com
  Connected     : wdsc.co.za
  Connected     : wmcpk.org
  Connected     : yeniinan.com
  Connected     : zamilindustrial.com
  Connected     : xbxxsqmy.wcnv20.cn
  Connected     : xclusivenetwork.com
  Not connected : xiangifu.com
  Not connected : xiwayy2kn32bo3ko.onion.link
  Connected     : xkvvhypv.wcnv20.cn
  Not connected : xn--80abghbpe9aidnhd0a3ntb.xn--p1ai
  Not connected : xn--bttrex-iwa.com
  Not connected : xn--emirats-9t4c.com
  Not connected : xn--konm-6w5ab.com
  Not connected : xn--ortakoporotr-fjb.com
  Not connected : xn--pibu-goa01e.com
  Not connected : xploramail.com
  Connected     : xrpmposhqoa.wcnv20.cn
  Connected     : xzimatxwa.wcnv20.cn
  Connected     : yaa.im
  Not connected : yamanashi-jyujin.jp
  Not connected : yapikampanyakredi.com
  Connected     : yatesassociates.co.za
  Connected     : yavuztrapez.com
  Connected     : ybuhykmw.wcnv20.cn
  Not connected : ycbtk3deno4axzfl.onion.link
  Connected     : yeditepeofset.com
  Connected     : yfedrvkfcqgg.wcnv20.cn
  Connected     : yigitersuurunleri.com
  Not connected : yildizlarkonteyner.com.tr
  Not connected : yildizmakina74.com
  Connected     : yip.su
  Not connected : yirmigbinternet.net
  Not connected : yiuy98u.ipq.co
  Connected     : yjcijumsnsag.wcnv20.cn
  Connected     : yjqnuxmtgbbo.wcnv20.cn
  Connected     : ykjozzugpijb.wcnv20.cn
  Connected     : ylhwcl.com
  Connected     : ylsbvhwzk.wcnv20.cn
  Not connected : yogakidsuae.com
  Connected     : yoma888.com
  Not connected : yosifiko.co.il
  Not connected : younqone.com
  Connected     : yourappyourway.com
  Connected     : yourjavascript.com
  Connected     : ytsdsgqp.wcnv20.cn
  Connected     : yunusbeyasm.gov.tr
  Connected     : yunuso.com
  Not connected : zafarhalalmeat.com.pk
  Connected     : zafarstocks.com
  Connected     : zamilindustrial.com
  Not connected : zasamag.com
  Connected     : zecuqjkza.wcnv20.cn
  Not connected : zeeshanasghar.website
  Connected     : zentinalmusique.co.uk
  Connected     : zerenprofessional.com
  Connected     : zerogov.com
  Connected     : zfrsgjmghj.wcnv20.cn
  Connected     : zgjipiao.club
  Connected     : zhqdymmfihju.wcnv20.cn
  Connected     : zindeinsaat.com
  Connected     : zndance.com
  Connected     : zpkeclnpguog.wcnv20.cn
  Connected     : zrxuxbzxr.wcnv20.cn
  Connected     : zsiqczxvwyx.wcnv20.cn
  Not connected : zszinhyosz.pe.hu
  Connected     : ztrcdbjzha.wcnv20.cn
  Connected     : zufqjwlu.wcnv20.cn
  Connected     : zzb.bz


## All malicious domains blacklisted!

  /home/fuat/usom/domain-blacklist.txt


## Local blacklists created!

  /home/fuat/usom/etc-hosts.txt
  /home/fuat/usom/unbound-conf.txt


End time        : 04:39:23
Elapsed time    : 00:55:04

Completed!

[fuat@fortress usom-blacklist]$ 
```
