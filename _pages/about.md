---
title: "Tony Khánh"
permalink: /about/
layout: splash
excerpt: "Learning today, Leading tomorrow."
header:
  overlay_image: about/banner-2.jpg
  caption: "Science with a spirit of adventure!"
---

{% include base_path %}
<!-- <link href="{{ base_path }}/assets/css/static/bootstrap.min.css" rel="stylesheet" media="screen"> -->
<link href="{{ base_path }}/assets/css/static/style.css" rel="stylesheet">
<link href="{{ base_path }}/assets/css/static/css" rel="stylesheet" type="text/css">
<style type="text/css"></style>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-86322230-1', 'auto');
  ga('send', 'pageview');
</script>


<body onload="start()">

<!-- Short Bio -->
<div class="container" style="margin-top:50px;">
<div class="container" style="font-size:18px; font-weight:350;margin-top:30px;margin-bottom:30px;color:#062a33;">
  <b>Bio</b>. I am a PhD student in Natural Language Processing at Nguyen lab, JAIST, Japan. My research experience covers natural language generation, deep learning, and Deep Bayesian Nets. I am particularly excited about recurrent neural networks, deep generative models, and the scientific applications of deep learning.
</div>

<div class="container" >
  <div id="headerblob">
    <a target="_blank" href="http://tonydeep.github.io/"><img src="/images/profile.png" class="img-circle imgme" style="border-radius:50%;"></a>
    <div id="headertext">
      <div id="htdesc" style="color:#062a33;font-weight:400">Natural Language Processing lab</div>
      <div id="htem"><a href="mailto:tvkhanh@jaist.ac.jp">tvkhanh@jaist.ac.jp</a></div>
      <div id="icons">
        <div class="svgico">
          <a target="_blank" href="https://github.com/tonydeep"><img src="/images/about/github.png" width="50px" class="img-circle" style="border-radius:50%;"></a>
          <a target="_blank" href="https://www.researchgate.net/profile/Van_Khanh_Tran2"><img src="/images/about/researchgate.png" width="50px" class="img-circle" style="border-radius:50%;"></a>
          <a target="_blank" href="https://www.linkedin.com/in/tran-van-khanh/"><img src="/images/about/linkedin.svg" width="50px" class="img-circle" style="border-radius:50%;"></a>
          <a target="_blank" href="http://tonydeep.github.io/year-archive"><img src="/images/about/blog.png" width="55px" class="img-circle" style="border-radius:50%;"></a>        
        </div>
      </div>
    </div>
  </div>
</div>
</div>

<!--  -->

<div class="container" style="margin-top:150px;">
  
  <div class="timelineitem">
      <div class="tdate">October 2017</div>
      <div class="ttitle"><a href="http://kse2017.dhsphue.edu.vn/ConferenceProgram.htm" style="color:#333;">The 9th International Conference on Knowledge and Systems Engineering (KSE 2017)</a></div>
      <div class="tdesc"><span class="thigh">October 19-21 in Hue, Vietnam</span></div>
      <div> </div>
    </div>

  <div class="timelineitem">
      <div class="tdate">August 2017</div>
      <div class="ttitle"><a href="http://www.sigdial.org/workshops/conference18/" style="color:#333;">The 18th Annual SIGdial Meeting on Discourse and Dialogue (SIGDIAL 2017)</a></div>
      <div class="tdesc"><span class="thigh">August 15-17 in Saarbrücken, Germany</span></div>
      <div> </div>
    </div>
  
  <div class="timelineitem">
      <div class="tdate">August 2017</div>
      <div class="ttitle"><a href="http://pacling.ucsy.edu.mm/pacling/" style="color:#333;">The 15th International Conference of the Pacific Association for Computational Linguistics (PACLING 2017)</a></div>
      <div class="tdesc"><span class="thigh">August 16 - 18, 2017 in Yangon, Myanmar </span></div>
      <div> </div>
    </div>

  <div class="timelineitem">
      <div class="tdate">July 2017</div>
      <div class="ttitle"><a href="http://acl2017.org/" style="color:#333;">Annual Meeting of the Association for Computational Linguistics (ACL 2017)</a></div>
      <div class="tdesc"><span class="thigh">July 30-August 4, 2017 in Vancouver, Canada</span></div>
  </div>
  
</div>
<!-- ===================== -->


<!-- Research -->
<hr class="soft">

<div class="container">
  <h2 style="margin: 0; text-align: center; font-weight: 400; font-size: 40px; padding: 10px 0px 40px;">Research</h2>
  <div id="pubs">

    <div class="pubwrap">
      <div class="row">
        <div class="col-md-6">
          <div class="pubimg">
            <img src="/images/papers/CoNLL-Models.png">
          </div>
        </div>
        <div class="col-md-6">
          <div class="pub">
            <div class="pubt">Natural Language Generation for Spoken Dialogue System using RNN Encoder-Decoder Networks</div>
            <div class="pubd">Natural language generation (NLG) is a critical component in a spoken dialogue system. This paper presents a Recurrent Neural Network based Encoder-Decoder architecture, in which an LSTM-based decoder called <b>RALSTM</b> is introduced to select, aggregate semantic elements produced by an attention mechanism over the input elements, and to produce the required utterances.</div>
            <div class="puba">Van-Khanh Tran, Le-Minh Nguyen</div>
            <div class="pubv">Acceptance rate: <span class="puba">18.7%</span>. Selected for oral presentation: <span class="puba">20/43</span></div>
            <div class="pubv"></div>
            <div class="publ">
              <ul>
                <li><a href="/files/RALSTM-Slides-CoNLL2017.pptx">Oral</a></li>
                <li><a href="https://www.researchgate.net/publication/317300175_Natural_Language_Generation_for_Spoken_Dialogue_System_using_RNN_Encoder-Decoder_Networks">PDF</a></li>
                <li><a href="http://www.conll.org/">CoNLL 2017</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="pubwrap">
      <div class="row">
        <div class="col-md-6">
          <div class="pubimg">
            <img src="/images/papers/SIGDial-Models.png">
          </div>
        </div>
        <div class="col-md-6">
          <div class="pub">
            <div class="pubt">Neural-based Natural Language Generation in Dialogue using RNN Encoder-Decoder with Semantic Aggregation</div>
            <div class="pubd">This paper presents a model called Encoder-Aggregator-Decoder which is an extension of an Recurrent Neural Network based Encoder-Decoder architecture. The proposed Semantic Aggregator consists of two components: an Aligner and a Refiner. The Aligner is a conventional attention calculated over the encoded input information, while the Refiner is another attention or gating mechanism stacked over the attentive Aligner in order to further select and aggregate the semantic elements. </div>
            <div class="puba">Van-Khanh Tran, Le-Minh Nguyen, Satoshi Tojo</div>
            <div class="pubv"></div>
            <div class="publ">
              <ul>
                <li><a href="https://www.researchgate.net/publication/317739912_Neural-based_Natural_Language_Generation_in_Dialogue_using_RNN_Encoder-Decoder_with_Semantic_Aggregation">PDF</a></li>
                <li><a href="http://www.sigdial.org/workshops/conference18/">SGIDial 2017</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="showmore" id="showmorepubs">
    Show more
  </div>

  <div id="morepubs">
    <div class="pubwrap">
      <div class="row">
        <div class="col-md-6">
          <div class="pubimg">
            <img src="/images/papers/RGRU-Context.png">
          </div>
        </div>
        <div class="col-md-6">
          <div class="pub">
            <div class="pubt">Semantic Refinement GRU-based Neural Language Generation for Spoken Dialogue Systems</div>
            <div class="pubd">This paper presents a new approach to NLG by using recurrent neural networks (RNN), in which a gating mechanism is applied before RNN computation. This results in an architecture called <b>SRGRU</b> and allows the proposed model to generate appropriate sentences. The SRGRU generator can be learned from unaligned data by jointly training sentence planning and surface realization to produce natural language responses.</div>
            <div class="puba">Van-Khanh Tran and Le-Minh Nguyen</div>
            <div class="pubv"></div>
            <div class="publ">
              <ul>
                <li><a href="https://www.researchgate.net/publication/317300329_Semantic_Refinement_GRU-based_Neural_Language_Generation_for_Spoken_Dialogue_Systems">PDF</a></li>
                <li><a href="http://pacling.ucsy.edu.mm/pacling/index.html">PACLING 2017</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>





<script>
var more_projects_shown = false;
function start() {
  $("#showmoreprojects").click(function() {
    if(!more_projects_shown) {
      $("#moreprojects").slideDown('fast', function() {
        $("#showmoreprojects").text('hide');
      });
      more_projects_shown = true;
    } else {
      $("#moreprojects").slideUp('fast', function() {
        $("#showmoreprojects").text('show more');
      });
      more_projects_shown = false;
    }
  });

  var more_pubs_shown = false;
  $("#showmorepubs").click(function() {
    if(!more_pubs_shown) {
      $("#morepubs").slideDown('fast', function() {
        $("#showmorepubs").text('hide');
      });
      more_pubs_shown = true;
    } else {
      $("#morepubs").slideUp('fast', function() {
        $("#showmorepubs").text('show more');
      });
      more_pubs_shown = false;
    }
  });

}

</script>
</body>
