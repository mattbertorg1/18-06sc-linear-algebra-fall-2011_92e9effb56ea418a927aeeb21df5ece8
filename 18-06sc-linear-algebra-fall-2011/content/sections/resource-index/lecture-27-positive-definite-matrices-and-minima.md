---
about_this_resource_text: ''
course_id: 18-06sc-linear-algebra-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: vF7eyJ2g3kU
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  title: Video-YouTube-Stream
  type: Video
  uid: 8608a37bf7a3e8b1f0aaa7b30ab3a421
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/vF7eyJ2g3kU/default.jpg
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f466165fe9e325bd7fccbbc5e194d8fc
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id488155309
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  title: Video-iTunes U-MP4
  type: Video
  uid: c9420f9b0cfaf019fb6dfb70dfedb558
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.06S05_MP4/27.mp4
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4a6c8dfa49e4a09a857dc4eaf202e732
- id: 3Play-3PlayYouTubeid-MP4
  media_location: vF7eyJ2g3kU
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5929090a5c4700667d7d1dec8e7b1be6
- id: vF7eyJ2g3kU.srt
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  technical_location: https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/resource-index/lecture-27-positive-definite-matrices-and-minima/vF7eyJ2g3kU.srt
  title: 3play caption file
  type: null
  uid: 950df661ba818b594357aa6ab9c70ad4
- id: vF7eyJ2g3kU.pdf
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  technical_location: https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/resource-index/lecture-27-positive-definite-matrices-and-minima/vF7eyJ2g3kU.pdf
  title: 3play pdf file
  type: null
  uid: 91bc2a7ba124f1c84236e056732a8d89
- id: Caption-3Play YouTube id-SRT
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ef2c672aa74c95ac7c16252aad0fa30d
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 7bbe9a95a404007da1050b514194b58e
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: b1886517f19788e148f5b5493570b24c
inline_embed_id: 72415044lecture27positivedefinitematricesandminima53657566
layout: video
order_index: null
parent_uid: 754d6be4ca3c378b6c8b2e4a955ffe64
related_resources_text: ''
short_url: lecture-27-positive-definite-matrices-and-minima
technical_location: https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/resource-index/lecture-27-positive-definite-matrices-and-minima
template_type: popup
title: 'Lecture 27: Positive Definite Matrices and Minima'
transcript: <p><span m="5560">OK,</span> <span m="9990">this</span> <span m="10150">is</span>
  <span m="10540">the</span> <span m="10970">lecture</span> <span m="11520">on</span>
  <span m="12000">positive</span> <span m="12650">definite</span> <span m="13140">matrices.</span>
  <span m="14460">I</span> <span m="15060">made</span> <span m="15730">a</span> <span
  m="15820">start</span> <span m="16329">on</span> <span m="16480">those</span> <span
  m="17480">briefly</span> <span m="18450">in</span> <span m="18600">a</span> <span
  m="18680">previous</span> <span m="19220">lecture.</span></p><p><span m="20770">One</span>
  <span m="21180">point</span> <span m="21490">I</span> <span m="21580">wanted</span>
  <span m="21930">to</span> <span m="22030">make</span> <span m="22540">was</span>
  <span m="23430">the</span> <span m="24050">way</span> <span m="24650">that</span>
  <span m="24900">this</span> <span m="25230">topic</span> <span m="25730">brings</span>
  <span m="26180">the</span> <span m="26320">whole</span> <span m="26550">course</span>
  <span m="26910">together,</span> <span m="27890">pivots,</span> <span m="29130">determinants,</span>
  <span m="30300">eigenvalues,</span> <span m="31460">and</span> <span m="32009">something</span>
  <span m="32590">new-</span> <span m="33810">four</span> <span m="34790">plot</span>
  <span m="35160">instability</span> <span m="36190">and</span> <span m="36460">then</span>
  <span m="36680">something</span> <span m="37190">new</span> <span m="37900">in</span>
  <span m="38350">this</span> <span m="38880">expression,</span> <span m="39920">x</span>
  <span m="40290">transpose</span> <span m="41120">Ax,</span> <span m="42050">actually</span>
  <span m="42550">that's</span> <span m="42950">the</span> <span m="43430">guy</span>
  <span m="43720">to</span> <span m="43850">watch</span> <span m="44350">in</span>
  <span m="44490">this</span> <span m="44740">lecture.</span></p><p><span m="46040">So,</span>
  <span m="47050">so</span> <span m="47690">the</span> <span m="47850">topic</span>
  <span m="48350">is</span> <span m="48550">positive</span> <span m="49110">definite</span>
  <span m="49550">matrix,</span> <span m="50410">and</span> <span m="50940">what's</span>
  <span m="52120">my</span> <span m="52310">goal?</span></p><p><span m="53580">First,</span>
  <span m="54080">first</span> <span m="54520">goal</span> <span m="54890">is,</span>
  <span m="55970">how</span> <span m="56900">can</span> <span m="57100">I</span> <span
  m="57210">tell</span> <span m="57580">if</span> <span m="57660">a</span> <span m="57760">matrix</span>
  <span m="58280">is</span> <span m="58440">positive</span> <span m="58950">definite?</span></p><p><span
  m="59970">So</span> <span m="60160">I</span> <span m="60260">would</span> <span
  m="60420">like</span> <span m="60640">to</span> <span m="60770">have</span> <span
  m="61030">tests</span> <span m="61680">to</span> <span m="61800">see</span> <span
  m="62490">if</span> <span m="63060">you</span> <span m="63220">give</span> <span
  m="63410">me</span> <span m="63620">a,</span> <span m="64090">a</span> <span m="64209">five</span>
  <span m="64540">by</span> <span m="64739">five</span> <span m="65230">matrix,</span>
  <span m="66100">how</span> <span m="66320">do</span> <span m="66400">I</span> <span
  m="66530">tell</span> <span m="66820">if</span> <span m="66910">it's</span> <span
  m="67120">positive</span> <span m="67600">definite?</span></p><p><span m="69000">More</span>
  <span m="69310">important</span> <span m="69910">is,</span> <span m="70730">what</span>
  <span m="71060">does</span> <span m="71220">it</span> <span m="71390">mean?</span></p><p><span
  m="72020">Why</span> <span m="72700">are</span> <span m="72830">we</span> <span
  m="73000">so</span> <span m="73260">interested</span> <span m="73830">in</span>
  <span m="73950">this</span> <span m="74220">property</span> <span m="74700">of</span>
  <span m="74780">positive</span> <span m="75350">definiteness?</span></p><p><span
  m="76440">And</span> <span m="76700">then,</span> <span m="77310">at</span> <span
  m="77580">the</span> <span m="77760">end</span> <span m="78130">comes</span> <span
  m="78570">some</span> <span m="78890">geometry.</span></p><p><span m="81410">Ellipses</span>
  <span m="82180">are</span> <span m="82330">connected</span> <span m="82880">with</span>
  <span m="83050">positive</span> <span m="83660">definite</span> <span m="84170">things.</span></p><p><span
  m="85080">Hyperbolas</span> <span m="85960">are</span> <span m="86070">not</span>
  <span m="86420">connected</span> <span m="86930">with</span> <span m="87120">positive</span>
  <span m="87690">definite</span> <span m="88210">things,</span> <span m="88520">so</span>
  <span m="88690">we-</span> <span m="89080">it's</span> <span m="89700">this,</span>
  <span m="90920">we,</span> <span m="91770">there's</span> <span m="92030">a</span>
  <span m="92110">geometry</span> <span m="92810">too,</span> <span m="93350">but</span>
  <span m="93980">mostly</span> <span m="94470">it's</span> <span m="94670">linear</span>
  <span m="95040">algebra</span> <span m="96470">and</span> <span m="98220">--</span>
  <span m="98410">this</span> <span m="99250">application</span> <span m="100130">of</span>
  <span m="100530">how</span> <span m="100990">do</span> <span m="101070">you</span>
  <span m="101200">recognize</span> <span m="101930">'em</span> <span m="102220">when</span>
  <span m="102720">you</span> <span m="102810">have</span> <span m="103020">a</span>
  <span m="103080">minim</span> <span m="103750">is</span> <span m="104360">pretty</span>
  <span m="104700">neat.</span></p><p><span m="105280">OK.</span></p><p><span m="105680">I'm</span>
  <span m="105730">gonna</span> <span m="106270">begin</span> <span m="107580">with</span>
  <span m="108010">two</span> <span m="108180">by</span> <span m="108380">two.</span></p><p><span
  m="110090">All</span> <span m="110350">matrices</span> <span m="110970">are</span>
  <span m="111090">symmetric,</span> <span m="111770">right?</span></p><p><span m="112280">That's</span>
  <span m="112560">understood;</span> <span m="113600">the</span> <span m="113880">matrix</span>
  <span m="114390">is</span> <span m="114560">symmetric,</span> <span m="115180">now</span>
  <span m="115340">my</span> <span m="115540">question</span> <span m="116170">is,</span>
  <span m="117090">is</span> <span m="117660">it</span> <span m="117850">positive</span>
  <span m="118410">definite?</span></p><p><span m="120650">Now,</span> <span m="121340">here</span>
  <span m="121950">are</span> <span m="122370">some</span> <span m="122990">--</span>
  <span m="124030">each</span> <span m="124360">one</span> <span m="124620">of</span>
  <span m="124750">these</span> <span m="125690">is</span> <span m="126480">a</span>
  <span m="126570">complete</span> <span m="127130">test</span> <span m="127660">for</span>
  <span m="127840">positive</span> <span m="128400">definiteness.</span></p><p><span
  m="129570">If</span> <span m="129830">I</span> <span m="129949">know</span> <span
  m="130210">the</span> <span m="130389">eigenvalues,</span> <span m="131820">my</span>
  <span m="132300">test</span> <span m="132780">is</span> <span m="133080">are</span>
  <span m="133270">they</span> <span m="133430">positive?</span></p><p><span m="135010">Are</span>
  <span m="135150">they</span> <span m="135320">all</span> <span m="135680">positive?</span></p><p><span
  m="138140">If</span> <span m="138410">I</span> <span m="138560">know</span> <span
  m="139770">these</span> <span m="141110">--</span> <span m="141650">so,</span> <span
  m="141930">A</span> <span m="142390">is</span> <span m="142660">really</span> <span
  m="143360">--</span> <span m="144170">I</span> <span m="144570">look</span> <span
  m="144800">at</span> <span m="144880">that</span> <span m="145090">number</span>
  <span m="145480">A,</span> <span m="145910">here,</span> <span m="146240">as</span>
  <span m="146500">the,</span> <span m="146880">as</span> <span m="147110">the</span>
  <span m="147240">one</span> <span m="147570">by</span> <span m="147750">one</span>
  <span m="148080">determinant,</span> <span m="149320">and</span> <span m="149740">here's</span>
  <span m="150260">the</span> <span m="150410">two</span> <span m="150620">by</span>
  <span m="150810">two</span> <span m="151070">determinant.</span></p><p><span m="153420">So</span>
  <span m="153770">this</span> <span m="154130">is</span> <span m="154250">the</span>
  <span m="154460">determinant</span> <span m="155220">test.</span></p><p><span m="155510">This</span>
  <span m="155690">is</span> <span m="155840">the</span> <span m="156000">eigenvalue</span>
  <span m="156790">test,</span> <span m="157230">this</span> <span m="157430">is</span>
  <span m="157600">the</span> <span m="157740">determinant</span> <span m="158440">test.</span></p><p><span
  m="159280">Are</span> <span m="159640">the</span> <span m="159810">determinants</span>
  <span m="161380">growing</span> <span m="162040">in</span> <span m="162190">s-</span>
  <span m="162360">of</span> <span m="162760">all,</span> <span m="163510">of</span>
  <span m="163890">all</span> <span m="164470">end,</span> <span m="165320">sort</span>
  <span m="165850">of,</span> <span m="166040">can</span> <span m="166190">I</span>
  <span m="166270">call</span> <span m="166580">them</span> <span m="166800">leading</span>
  <span m="167500">submatrices,</span> <span m="168640">they're</span> <span m="168850">the</span>
  <span m="169570">first</span> <span m="169970">ones</span> <span m="170320">the</span>
  <span m="170630">northwest,</span> <span m="172140">Seattle</span> <span m="173280">submatrices</span>
  <span m="174420">coming</span> <span m="174800">down</span> <span m="175190">from</span>
  <span m="175560">from</span> <span m="175760">there,</span> <span m="176510">they</span>
  <span m="176900">all,</span> <span m="177140">all</span> <span m="177330">those</span>
  <span m="177540">determinants</span> <span m="178190">have</span> <span m="178410">to</span>
  <span m="178500">be</span> <span m="178650">positive,</span> <span m="179570">and</span>
  <span m="180560">then</span> <span m="180740">another</span> <span m="181180">test</span>
  <span m="181640">is</span> <span m="181870">the</span> <span m="181990">pivots.</span></p><p><span
  m="183020">The</span> <span m="184450">pivots</span> <span m="184890">of</span>
  <span m="185000">a</span> <span m="185090">two</span> <span m="185260">by</span>
  <span m="185470">two</span> <span m="185680">matrix</span> <span m="186370">are</span>
  <span m="187130">the</span> <span m="187370">number</span> <span m="187790">A</span>
  <span m="188330">for</span> <span m="188500">sure,</span> <span m="189160">and,</span>
  <span m="190770">since</span> <span m="190870">the</span> <span m="192560">product</span>
  <span m="193070">is</span> <span m="193230">the</span> <span m="193360">determinant,</span>
  <span m="194240">the</span> <span m="194560">second</span> <span m="195010">pivot</span>
  <span m="195410">must</span> <span m="195760">be</span> <span m="196540">the</span>
  <span m="196750">determinant</span> <span m="197320">divided</span> <span m="197740">by</span>
  <span m="197970">A.</span></p><p><span m="198980">And</span> <span m="199260">then</span>
  <span m="199560">in</span> <span m="199870">here</span> <span m="200360">is</span>
  <span m="200480">gonna</span> <span m="200770">come</span> <span m="201530">my</span>
  <span m="202430">favorite</span> <span m="203340">and</span> <span m="203510">my</span>
  <span m="203680">new</span> <span m="204150">idea,</span> <span m="204970">the,</span>
  <span m="205200">the,</span> <span m="205480">the</span> <span m="205730">the</span>
  <span m="205890">one</span> <span m="206120">to</span> <span m="206230">catch,</span>
  <span m="206850">about</span> <span m="207380">x</span> <span m="207730">transpose</span>
  <span m="209020">Ax</span> <span m="210450">being</span> <span m="210920">positive.</span></p><p><span
  m="212640">But</span> <span m="212920">we'll</span> <span m="213160">have</span>
  <span m="213320">to</span> <span m="213460">look</span> <span m="213710">at</span>
  <span m="213810">this</span> <span m="214070">guy.</span></p><p><span m="215280">This</span>
  <span m="215540">gets,</span> <span m="215920">like</span> <span m="216280">a</span>
  <span m="216390">star,</span> <span m="216940">because</span> <span m="217940">for</span>
  <span m="218610">most,</span> <span m="221470">presentations,</span> <span m="222780">the</span>
  <span m="223200">definition</span> <span m="224090">of</span> <span m="224220">positive</span>
  <span m="224810">definiteness</span> <span m="225610">would</span> <span m="225820">be</span>
  <span m="226060">this</span> <span m="226330">number</span> <span m="226660">four</span>
  <span m="227410">and</span> <span m="227630">these</span> <span m="228070">numbers</span>
  <span m="228580">one</span> <span m="228830">two</span> <span m="229050">three</span>
  <span m="229370">would</span> <span m="229580">be</span> <span m="230170">test</span>
  <span m="230640">four.</span></p><p><span m="231320">OK.</span> <span m="231760">Maybe</span>
  <span m="232100">I'll</span> <span m="232300">tuck</span> <span m="232640">this,</span>
  <span m="233500">where,</span> <span m="234450">you</span> <span m="234600">know,</span></p><p><span
  m="236180">OK.</span> <span m="236660">So</span> <span m="236860">I'll</span> <span
  m="237020">have</span> <span m="237220">to</span> <span m="237370">look</span> <span
  m="237590">at</span> <span m="237680">this</span> <span m="237900">x</span> <span
  m="238120">transpose</span> <span m="238720">Ax.</span></p><p><span m="240000">Can</span>
  <span m="240250">you,</span> <span m="240660">can</span> <span m="244800">we</span>
  <span m="244960">just</span> <span m="245440">be</span> <span m="245800">sure,</span>
  <span m="247080">how</span> <span m="247760">do</span> <span m="247870">we</span>
  <span m="248040">know</span> <span m="248370">that</span> <span m="248550">the</span>
  <span m="248710">eigenvalue</span> <span m="249460">test</span> <span m="250250">and</span>
  <span m="251040">the</span> <span m="251480">determinant</span> <span m="252150">test,</span>
  <span m="253130">pick</span> <span m="254600">out</span> <span m="254790">the</span>
  <span m="254890">same</span> <span m="255200">matrices,</span> <span m="256000">and</span>
  <span m="256279">let</span> <span m="256459">me,</span> <span m="257170">let's</span>
  <span m="257820">just</span> <span m="258040">do</span> <span m="258200">a</span>
  <span m="258269">few</span> <span m="258459">examples.</span></p><p><span m="259890">Some</span>
  <span m="260010">examples.</span></p><p><span m="264610">Let</span> <span m="264780">me</span>
  <span m="265430">pick</span> <span m="265880">the</span> <span m="266000">matrix</span>
  <span m="266590">two,</span> <span m="267930">six,</span> <span m="269030">six,</span>
  <span m="270220">tell</span> <span m="271040">me,</span> <span m="271220">what</span>
  <span m="271490">number</span> <span m="271880">do</span> <span m="272020">I</span>
  <span m="272160">have</span> <span m="272350">to</span> <span m="272470">put</span>
  <span m="272750">there</span> <span m="275620">for</span> <span m="275770">the</span>
  <span m="275880">matrix</span> <span m="276360">to</span> <span m="276440">be</span>
  <span m="276610">positive</span> <span m="277160">definite?</span></p><p><span m="280150">Tell</span>
  <span m="280320">me</span> <span m="280480">a</span> <span m="280540">sufficiently</span>
  <span m="281260">large</span> <span m="281720">number</span> <span m="282090">that</span>
  <span m="282240">would</span> <span m="282710">make</span> <span m="283170">it</span>
  <span m="283360">positive</span> <span m="283930">definite?</span></p><p><span m="285020">Let's</span>
  <span m="285290">just</span> <span m="285540">practice</span> <span m="286090">with</span>
  <span m="286250">these</span> <span m="286490">conditions</span> <span m="287300">in</span>
  <span m="287530">the</span> <span m="287660">two</span> <span m="287830">by</span>
  <span m="288040">two</span> <span m="288310">case.</span></p><p><span m="289370">Now,</span>
  <span m="289960">when</span> <span m="290160">I</span> <span m="290260">ask</span>
  <span m="290540">you</span> <span m="290630">that,</span> <span m="291210">you</span>
  <span m="291340">don't</span> <span m="291490">wanna</span> <span m="291710">find</span>
  <span m="292010">the</span> <span m="292160">eigenvalues,</span> <span m="293860">you</span>
  <span m="294610">would</span> <span m="294780">use</span> <span m="295060">the</span>
  <span m="295200">determinant</span> <span m="295900">test</span> <span m="296270">for</span>
  <span m="296390">that,</span> <span m="297500">so,</span> <span m="298540">the</span>
  <span m="298840">first</span> <span m="299180">or</span> <span m="299340">the</span>
  <span m="299460">pivot</span> <span m="299900">test,</span> <span m="300340">that,</span>
  <span m="300620">that</span> <span m="300920">guy</span> <span m="301170">is</span>
  <span m="301300">certainly</span> <span m="301730">positive,</span> <span m="302340">that</span>
  <span m="302540">had</span> <span m="302770">to</span> <span m="302850">happen,</span>
  <span m="303750">and</span> <span m="304160">it's</span> <span m="304310">OK.</span></p><p><span
  m="305070">How</span> <span m="305480">large</span> <span m="305860">a</span> <span
  m="305930">number</span> <span m="306290">here</span> <span m="307050">--</span>
  <span m="307210">the</span> <span m="307540">number</span> <span m="307890">had</span>
  <span m="308050">better</span> <span m="308330">be</span> <span m="308500">more</span>
  <span m="308800">than</span></p><p><span m="309030">what?</span> <span m="310200">More</span>
  <span m="311080">than</span> <span m="311780">eighteen,</span> <span m="312530">right,</span>
  <span m="312990">because</span> <span m="313440">if</span> <span m="313600">it's</span>
  <span m="313780">eight</span> <span m="314170">--</span></p><p><span m="314350">no.</span>
  <span m="315400">More</span> <span m="316270">than</span> <span m="316430">what?</span></p><p><span
  m="318550">Nineteen,</span> <span m="319150">is</span> <span m="319270">it?</span></p><p><span
  m="321390">If</span> <span m="321600">I</span> <span m="321720">have</span> <span
  m="321870">a</span> <span m="321930">nineteen</span> <span m="322580">here,</span>
  <span m="327810">is</span> <span m="327970">that</span> <span m="328200">positive</span>
  <span m="328640">definite?</span></p><p><span m="332590">I</span> <span m="332760">get</span>
  <span m="333050">thirty</span> <span m="333440">eight</span> <span m="333940">minus</span>
  <span m="334560">thirty</span> <span m="334860">six,</span> <span m="335230">that's</span>
  <span m="335480">OK.</span></p><p><span m="336160">If</span> <span m="336440">I</span>
  <span m="336590">had</span> <span m="336840">an</span> <span m="336970">eighteen,</span>
  <span m="337550">let</span> <span m="337660">me</span> <span m="337820">play</span>
  <span m="338090">it</span> <span m="338260">really</span> <span m="338650">close.</span></p><p><span
  m="339900">If</span> <span m="340050">I</span> <span m="340160">have</span> <span
  m="340270">an</span> <span m="340340">eighteen</span> <span m="340910">there,</span>
  <span m="341680">then</span> <span m="342360">I</span> <span m="342570">positive</span>
  <span m="343180">definite?</span></p><p><span m="344850">Not</span> <span m="345400">quite.</span></p><p><span
  m="346640">I</span> <span m="346860">would</span> <span m="347130">call</span> <span
  m="347520">this</span> <span m="347850">guy</span> <span m="348240">positive,</span>
  <span m="349240">so</span> <span m="349500">it's</span> <span m="349830">useful</span>
  <span m="350280">just</span> <span m="350520">to</span> <span m="350640">see</span>
  <span m="351170">that</span> <span m="351480">this</span> <span m="351820">the</span>
  <span m="351960">borderline.</span></p><p><span m="353550">That</span> <span m="353820">matrix</span>
  <span m="354320">is</span> <span m="354490">on</span> <span m="354670">the</span>
  <span m="354770">borderline,</span> <span m="355640">I</span> <span m="355810">would</span>
  <span m="356060">call</span> <span m="356340">that</span> <span m="356570">matrix</span>
  <span m="357160">positive</span> <span m="358400">semi-definite.</span> <span m="364670">And</span>
  <span m="365090">what</span> <span m="365470">are</span> <span m="365550">the</span>
  <span m="365730">eigenvalues</span> <span m="366410">of</span> <span m="366500">that</span>
  <span m="366710">matrix,</span> <span m="367900">just</span> <span m="368590">since</span>
  <span m="368820">we're</span> <span m="368970">given</span> <span m="369340">eigenvalues</span>
  <span m="369990">of</span> <span m="370130">two</span> <span m="370310">by</span>
  <span m="370520">twos,</span> <span m="371690">when</span> <span m="372380">it's</span>
  <span m="372580">semi-definite,</span> <span m="374470">but</span> <span m="375710">not</span>
  <span m="375990">definite,</span> <span m="377150">then</span> <span m="378070">the</span>
  <span m="378760">--</span> <span m="379460">I'm</span> <span m="379620">squeezing</span>
  <span m="380400">this</span> <span m="380670">eigenvalue</span> <span m="381520">test</span>
  <span m="381940">down,</span> <span m="382300">--</span> <span m="382540">what's</span>
  <span m="383610">the</span> <span m="384770">eigenvalue</span> <span m="385850">that</span>
  <span m="386900">I</span> <span m="387070">know</span> <span m="387340">this</span>
  <span m="387600">matrix</span> <span m="388090">has?</span></p><p><span m="388370">What</span>
  <span m="388540">kind</span> <span m="388710">of</span> <span m="388790">a</span>
  <span m="388860">matrix</span> <span m="389280">have</span> <span m="389430">I</span>
  <span m="389520">got</span> <span m="389840">here?</span></p><p><span m="391320">It's</span>
  <span m="391390">a</span> <span m="391500">singular</span> <span m="392040">matrix,</span>
  <span m="392630">one</span> <span m="392860">of</span> <span m="392980">its</span>
  <span m="393150">eigenvalues</span> <span m="393970">is</span> <span m="396670">zero.</span></p><p><span
  m="397680">That</span> <span m="397880">has</span> <span m="398110">an</span> <span
  m="398240">eigenvalue</span> <span m="398990">zero,</span> <span m="399930">and</span>
  <span m="400340">the</span> <span m="400490">other</span> <span m="400760">eigenvalue</span>
  <span m="401610">is</span> <span m="402320">--</span> <span m="403570">from</span>
  <span m="403740">the</span> <span m="403870">trace,</span> <span m="405630">twenty.</span></p><p><span
  m="407020">OK.</span> <span m="407620">So</span> <span m="407940">that,</span> <span
  m="408240">that</span> <span m="408530">matrix</span> <span m="409300">has</span>
  <span m="409710">eigenvalues</span> <span m="410690">greater</span> <span m="411190">than</span>
  <span m="411560">or</span> <span m="411730">equal</span> <span m="412190">to</span>
  <span m="412280">zero,</span> <span m="412970">and</span> <span m="413480">it's</span>
  <span m="413660">that</span> <span m="413970">&quot;equal</span> <span m="414450">to&quot;</span>
  <span m="414850">that</span> <span m="415140">brought</span> <span m="415480">this</span>
  <span m="415710">word</span> <span m="416060">&quot;semi-definite&quot;</span> <span
  m="416980">in.</span></p><p><span m="418000">And,</span> <span m="418440">the</span>
  <span m="418670">what</span> <span m="418950">are</span> <span m="419000">the</span>
  <span m="419130">pivots</span> <span m="419610">of</span> <span m="419710">that</span>
  <span m="419970">matrix?</span></p><p><span m="421240">So</span> <span m="421350">the</span>
  <span m="421480">pivots,</span> <span m="422370">so</span> <span m="422760">the</span>
  <span m="422910">eigenvalues</span> <span m="423810">are</span> <span m="424310">zero</span>
  <span m="424700">and</span> <span m="424800">twenty,</span> <span m="425530">the</span>
  <span m="425840">pivots</span> <span m="426520">are,</span> <span m="427990">well,</span>
  <span m="428940">the</span> <span m="429070">pivot</span> <span m="429480">is</span>
  <span m="429690">two,</span> <span m="430580">and</span> <span m="431050">what's</span>
  <span m="431320">the</span> <span m="431450">next</span> <span m="431780">pivot?</span></p><p><span
  m="435840">There</span> <span m="436010">isn't</span> <span m="436290">one.</span></p><p><span
  m="437430">We</span> <span m="437680">got</span> <span m="437850">a</span> <span
  m="437900">singular</span> <span m="438440">matrix</span> <span m="439000">here,</span>
  <span m="439280">it'll</span> <span m="439480">only</span> <span m="439690">have</span>
  <span m="439900">one</span> <span m="440230">pivot.</span></p><p><span m="440900">You</span>
  <span m="441050">see</span> <span m="441370">that</span> <span m="441540">that's</span>
  <span m="441790">a</span> <span m="441860">rank</span> <span m="442220">one</span>
  <span m="442520">matrix,</span> <span m="443390">two</span> <span m="443790">six</span>
  <span m="444230">is</span> <span m="444370">a</span> <span m="444470">--</span>
  <span m="444920">six</span> <span m="445230">eighteen</span> <span m="445740">is</span>
  <span m="445870">a</span> <span m="445950">multiple</span> <span m="446450">of</span>
  <span m="446590">two</span> <span m="446830">six,</span> <span m="447710">the</span>
  <span m="449120">matrix</span> <span m="449680">is</span> <span m="449830">singular</span>
  <span m="450550">it</span> <span m="450630">only</span> <span m="450850">has</span>
  <span m="451050">one</span> <span m="451430">pivot,</span> <span m="452380">so</span>
  <span m="453450">the</span> <span m="455110">pivot</span> <span m="455780">test</span>
  <span m="456250">doesn't</span> <span m="456590">quite</span></p><p><span m="458050">The</span>
  <span m="458930">--</span> <span m="458960">let</span> <span m="459040">me</span>
  <span m="459170">do</span> <span m="459390">the</span> <span m="459560">x</span>
  <span m="459860">transpose</span> <span m="460580">Ax.</span> <span m="461120">pass.</span></p><p><span
  m="461210">Now</span> <span m="462320">this</span> <span m="463480">is</span> <span
  m="463750">--</span> <span m="465280">the</span> <span m="467700">novelty</span>
  <span m="468390">now.</span></p><p><span m="469130">OK.</span> <span m="469960">What</span>
  <span m="470620">I</span> <span m="470760">looking</span> <span m="471120">at</span>
  <span m="471360">when</span> <span m="471520">I</span> <span m="471610">look</span>
  <span m="472220">at</span> <span m="472440">this</span> <span m="472980">new</span>
  <span m="473450">combination,</span> <span m="474470">x</span> <span m="474830">transpose</span>
  <span m="475550">Ax.</span> <span m="476360">x</span> <span m="476850">is</span>
  <span m="477000">any</span> <span m="477260">vector</span> <span m="477720">now,</span>
  <span m="478410">so</span> <span m="478820">lemme</span> <span m="479060">compute,</span>
  <span m="480050">so</span> <span m="480940">any</span> <span m="481510">vector,</span>
  <span m="482140">lemme</span> <span m="482340">call</span> <span m="482700">its</span>
  <span m="482860">components</span> <span m="483440">x1</span> <span m="483950">and</span>
  <span m="484080">x2,</span> <span m="485720">so</span> <span m="486650">that's</span>
  <span m="486920">x.</span></p><p><span m="488960">And</span> <span m="489220">I</span>
  <span m="489290">put</span> <span m="489540">in</span> <span m="489700">here</span>
  <span m="489940">A.</span></p><p><span m="491300">Let's,</span> <span m="491680">let's</span>
  <span m="491960">use</span> <span m="492240">this</span> <span m="492450">example</span>
  <span m="493090">two</span> <span m="493320">six,</span> <span m="493760">six</span>
  <span m="494090">eighteen,</span> <span m="495500">and</span> <span m="497340">here's</span>
  <span m="497920">x</span> <span m="498160">transposed,</span> <span m="498930">so</span>
  <span m="499110">x1</span> <span m="499680">x2.</span> <span m="500500">We're</span>
  <span m="501760">back</span> <span m="502070">to</span> <span m="502200">real</span>
  <span m="502580">matrices,</span> <span m="503280">after</span> <span m="503650">that</span>
  <span m="503950">last</span> <span m="504420">lecture</span> <span m="505580">that-</span>
  <span m="506150">that</span> <span m="506420">said</span> <span m="506710">what</span>
  <span m="506910">to</span> <span m="507020">do</span> <span m="507200">in</span>
  <span m="507280">the</span> <span m="507390">complex</span> <span m="508020">case,</span>
  <span m="508650">let's</span> <span m="509480">come</span> <span m="509810">back</span>
  <span m="510150">to</span> <span m="510270">real</span> <span m="510890">matrices.</span></p><p><span
  m="512010">So</span> <span m="512640">here's</span> <span m="513070">x</span> <span
  m="513409">transpose</span> <span m="514370">Ax,</span> <span m="515150">and</span>
  <span m="515700">what</span> <span m="516030">I'm</span> <span m="516250">interested</span>
  <span m="516780">in</span> <span m="517020">is,</span> <span m="518299">what</span>
  <span m="519330">do</span> <span m="519400">I</span> <span m="519510">get</span>
  <span m="519730">if</span> <span m="519860">I</span> <span m="519950">multiply</span>
  <span m="520490">those</span> <span m="520750">together?</span></p><p><span m="522720">I</span>
  <span m="522850">get</span> <span m="523159">some</span> <span m="523409">function</span>
  <span m="524350">of</span> <span m="524650">x1</span> <span m="525060">and</span>
  <span m="525180">x2,</span> <span m="526380">and</span> <span m="526660">what</span>
  <span m="526920">is</span> <span m="527070">it?</span></p><p><span m="528410">Let's</span>
  <span m="528990">see,</span> <span m="529440">if</span> <span m="529820">I</span>
  <span m="529910">do</span> <span m="530140">this</span> <span m="530380">multiplication,</span>
  <span m="531150">so</span> <span m="531300">I</span> <span m="531390">do</span>
  <span m="531570">it,</span> <span m="531700">lemme,</span> <span m="531960">just,</span>
  <span m="532200">I'll</span> <span m="532500">just</span> <span m="532730">do</span>
  <span m="532860">it</span> <span m="532950">slowly,</span> <span m="533700">x1,</span>
  <span m="534930">x2,</span> <span m="535220">if</span> <span m="535360">I</span>
  <span m="535490">multiply</span> <span m="536230">that</span> <span m="536590">matrix,</span>
  <span m="537230">this</span> <span m="537460">is</span> <span m="538050">2x1,</span>
  <span m="539760">and</span> <span m="540240">6x2s,</span> <span m="541980">and</span>
  <span m="542930">the</span> <span m="543080">next</span> <span m="543440">row</span>
  <span m="543900">is</span> <span m="544030">6x1s</span> <span m="545200">and</span>
  <span m="545370">18x2s,</span> <span m="547400">and</span> <span m="548100">now</span>
  <span m="548430">I</span> <span m="548930">do</span> <span m="549310">this</span>
  <span m="549640">final</span> <span m="550010">step</span> <span m="550420">and</span>
  <span m="550550">what</span> <span m="550730">do</span> <span m="550800">I</span>
  <span m="550920">have?</span></p><p><span m="551530">I've</span> <span m="551710">got</span>
  <span m="552000">2x1</span> <span m="552730">squareds,</span> <span m="554450">got</span>
  <span m="555580">2X1</span> <span m="556320">squareds</span> <span m="556810">is</span>
  <span m="556980">coming</span> <span m="557330">from</span> <span m="557500">this</span>
  <span m="557790">two,</span> <span m="558870">I've</span> <span m="559600">got</span>
  <span m="560650">this</span> <span m="561230">one</span> <span m="561480">gives</span>
  <span m="561750">me</span> <span m="562090">eighteen,</span> <span m="563080">well,</span>
  <span m="563440">shall</span> <span m="563610">I</span> <span m="563690">do</span>
  <span m="563860">the</span> <span m="563960">ones</span> <span m="564220">in</span>
  <span m="564310">the</span> <span m="564400">middle?</span></p><p><span m="565630">How</span>
  <span m="565710">many</span> <span m="566030">x1</span> <span m="567190">x2s</span>
  <span m="567290">do</span> <span m="567420">I</span> <span m="567580">have?</span></p><p><span
  m="569530">Let's</span> <span m="569740">see,</span> <span m="569960">x1</span>
  <span m="570830">times</span> <span m="571120">that</span> <span m="571330">6x2</span>
  <span m="572210">would</span> <span m="572270">be</span> <span m="572400">six</span>
  <span m="572740">of</span> <span m="572870">'em,</span> <span m="573330">and</span>
  <span m="573700">then</span> <span m="573900">x2</span> <span m="574380">times</span>
  <span m="574670">this</span> <span m="574900">one</span> <span m="575100">will</span>
  <span m="575190">be</span> <span m="575380">six</span> <span m="575700">more,</span>
  <span m="576020">I</span> <span m="576110">get</span> <span m="576340">twelve.</span></p><p><span
  m="578300">So,</span> <span m="578700">in</span> <span m="579420">here</span> <span
  m="579820">is</span> <span m="580020">going,</span> <span m="580730">this</span>
  <span m="581130">is</span> <span m="581800">the</span> <span m="582370">number</span>
  <span m="582750">a,</span> <span m="583670">this</span> <span m="584140">is</span>
  <span m="584290">the</span> <span m="584430">number</span> <span m="585010">2b,</span>
  <span m="586220">and</span> <span m="586770">in</span> <span m="586970">here</span>
  <span m="587330">is</span> <span m="588120">--</span> <span m="589190">x2</span>
  <span m="589680">times</span> <span m="590080">eighteen</span> <span m="590570">x2</span>
  <span m="591060">will</span> <span m="591270">be</span> <span m="591810">eighteen</span>
  <span m="592990">x2</span> <span m="593840">squareds</span> <span m="594600">and</span>
  <span m="594760">this</span> <span m="594960">is</span> <span m="595120">the</span>
  <span m="595250">number</span> <span m="595890">c.</span></p><p><span m="597630">So</span>
  <span m="597810">it's</span> <span m="597980">ax1</span> <span m="598900">--</span>
  <span m="599300">it's</span> <span m="599590">like</span> <span m="599950">ax</span>
  <span m="600400">squared.</span> <span m="602010">2bxy</span> <span m="603240">and</span>
  <span m="604160">cy</span> <span m="604530">squared.</span></p><p><span m="605140">For</span>
  <span m="608310">my</span> <span m="608400">first</span> <span m="608780">point</span>
  <span m="609130">that</span> <span m="609420">I</span> <span m="609480">wanted</span>
  <span m="609820">to</span> <span m="609920">make</span> <span m="610220">by</span>
  <span m="610350">just</span> <span m="610690">doing</span> <span m="611050">out</span>
  <span m="611280">a</span> <span m="611350">multiplication</span> <span m="612140">is,</span>
  <span m="612880">that</span> <span m="613300">is</span> <span m="613340">as</span>
  <span m="613420">soon</span> <span m="613760">as</span> <span m="613880">you</span>
  <span m="613990">give</span> <span m="614210">me</span> <span m="614360">the</span>
  <span m="614480">matrix,</span> <span m="615720">as</span> <span m="616140">soon</span>
  <span m="616360">as</span> <span m="616450">you</span> <span m="616550">give</span>
  <span m="616730">me</span> <span m="616850">the</span> <span m="616970">matrix,</span>
  <span m="618070">I</span> <span m="618530">can</span> <span m="618950">--</span>
  <span m="619240">those</span> <span m="619640">are</span> <span m="619700">the</span>
  <span m="619860">numbers</span> <span m="620400">that</span> <span m="620550">appear</span>
  <span m="621570">in</span> <span m="622140">--</span> <span m="622860">I'll</span>
  <span m="623130">call</span> <span m="623380">this</span> <span m="623660">thing</span>
  <span m="623930">a</span> <span m="624060">quadratic,</span> <span m="625580">you</span>
  <span m="626080">see,</span> <span m="626230">it's</span> <span m="626460">not</span>
  <span m="626700">linear</span> <span m="627080">anymore.</span></p><p><span m="629140">Ax</span>
  <span m="629750">is</span> <span m="629880">linear,</span> <span m="630450">but</span>
  <span m="630590">now</span> <span m="630730">I've</span> <span m="630910">got</span>
  <span m="631060">an</span> <span m="631180">x</span> <span m="631420">transpose</span>
  <span m="632040">coming</span> <span m="632360">in,</span> <span m="632570">I'm</span>
  <span m="632740">up</span> <span m="632910">to</span> <span m="633030">degree</span>
  <span m="633500">two,</span> <span m="634320">up</span> <span m="634710">to</span>
  <span m="634840">degree</span> <span m="635240">two,</span> <span m="635680">maybe</span>
  <span m="636410">quadratic</span> <span m="637650">is</span> <span m="637870">the</span>
  <span m="638230">--</span> <span m="638880">use</span> <span m="639080">the</span>
  <span m="639180">word.</span></p><p><span m="639480">A</span> <span m="639610">quadratic</span>
  <span m="640450">form.</span></p><p><span m="641980">It's</span> <span m="643060">purely</span>
  <span m="644250">degree</span> <span m="644710">two,</span> <span m="645250">there's</span>
  <span m="645510">no</span> <span m="645680">linear</span> <span m="646210">part,</span>
  <span m="646610">there's</span> <span m="646800">no</span> <span m="646980">constant</span>
  <span m="647560">part,</span> <span m="647880">there</span> <span m="648010">certainly</span>
  <span m="648440">no</span> <span m="648750">cubes</span> <span m="649410">or</span>
  <span m="649520">fourth</span> <span m="649890">powers,</span> <span m="650570">it's</span>
  <span m="650940">all</span> <span m="651680">second</span> <span m="652160">degree.</span></p><p><span
  m="653540">And</span> <span m="653810">my</span> <span m="653950">question</span>
  <span m="654460">is</span> <span m="655040">--</span> <span m="655780">is</span>
  <span m="656230">that</span> <span m="656490">quantity</span> <span m="657030">positive</span>
  <span m="657700">or</span> <span m="657920">not?</span></p><p><span m="660120">That's</span>
  <span m="660380">--</span> <span m="661670">for</span> <span m="661930">every</span>
  <span m="662490">x1</span> <span m="663000">and</span> <span m="663120">x2,</span>
  <span m="664410">that</span> <span m="665700">is</span> <span m="666250">my</span>
  <span m="666500">new</span> <span m="666890">definition</span> <span m="667730">--</span>
  <span m="668250">that's</span> <span m="668470">my</span> <span m="668690">definition</span>
  <span m="669560">of</span> <span m="669780">a</span> <span m="669840">positive</span>
  <span m="670460">definite</span> <span m="670950">matrix.</span></p><p><span m="671920">If</span>
  <span m="672300">this</span> <span m="672980">quantity</span> <span m="673610">is</span>
  <span m="673810">positive,</span> <span m="674790">if,</span> <span m="675220">if,</span>
  <span m="675550">if,</span> <span m="676500">it's</span> <span m="677290">positive</span>
  <span m="677970">for</span> <span m="678200">all</span> <span m="678960">x's</span>
  <span m="679420">and</span> <span m="679560">y's,</span> <span m="680150">all</span>
  <span m="680710">x1</span> <span m="681780">x2s,</span> <span m="682200">then</span>
  <span m="683860">I</span> <span m="684630">call</span> <span m="684910">them</span>
  <span m="685070">--</span> <span m="685140">then</span> <span m="685670">that's</span>
  <span m="686320">the</span> <span m="686500">matrix</span> <span m="686960">is</span>
  <span m="687120">positive</span> <span m="687630">definite.</span></p><p><span m="689170">Now,</span>
  <span m="690660">is</span> <span m="691380">this</span> <span m="691620">guy</span>
  <span m="691820">passing</span> <span m="692400">our</span> <span m="692560">test?</span></p><p><span
  m="694340">Well</span> <span m="694530">we</span> <span m="694650">have,</span>
  <span m="695260">we</span> <span m="695770">anticipated</span> <span m="696690">the</span>
  <span m="696840">answer</span> <span m="697250">here</span> <span m="697500">by,</span>
  <span m="698120">by</span> <span m="698620">asking</span> <span m="699250">first</span>
  <span m="699650">about</span> <span m="699980">eigenvalues</span> <span m="701240">and</span>
  <span m="701540">pivots,</span> <span m="702420">and</span> <span m="702750">what</span>
  <span m="702940">happened?</span></p><p><span m="704820">It</span> <span m="705390">failed.</span></p><p><span
  m="706350">It</span> <span m="707340">barely</span> <span m="707820">failed.</span></p><p><span
  m="709490">If</span> <span m="709730">I</span> <span m="709900">had</span> <span
  m="710180">made</span> <span m="710570">this</span> <span m="710810">eighteen</span>
  <span m="711590">down</span> <span m="712000">to</span> <span m="712210">a</span>
  <span m="712810">seven,</span> <span m="713670">it</span> <span m="714430">would've</span>
  <span m="714760">totally</span> <span m="717980">failed.</span></p><p><span m="718120">I</span>
  <span m="718220">do</span> <span m="718450">that</span> <span m="718710">with</span>
  <span m="718960">the</span> <span m="719050">eraser,</span> <span m="719790">and</span>
  <span m="720010">then</span> <span m="720220">I'll</span> <span m="720620">put</span>
  <span m="720800">back</span> <span m="721070">eighteen,</span> <span m="721540">because,</span>
  <span m="721980">seven</span> <span m="722640">is</span> <span m="722770">such</span>
  <span m="723110">a</span> <span m="723770">total</span> <span m="724490">disaster,</span>
  <span m="725200">but</span> <span m="725380">if</span> <span m="725590">--</span>
  <span m="727170">I'll</span> <span m="728060">keep</span> <span m="728750">seven</span>
  <span m="729220">for</span> <span m="729380">a</span> <span m="729430">second.</span></p><p><span
  m="730240">Is</span> <span m="730810">that</span> <span m="731120">thing</span>
  <span m="731960">in</span> <span m="732670">any</span> <span m="732970">way</span>
  <span m="733440">positive</span> <span m="734090">definite?</span></p><p><span m="735170">No,</span>
  <span m="735670">absolutely</span> <span m="736390">not.</span></p><p><span m="738480">I</span>
  <span m="738590">don't</span> <span m="738750">know</span> <span m="738890">its</span>
  <span m="739030">eigenvalues,</span> <span m="739770">but</span> <span m="740000">I</span>
  <span m="740150">know</span> <span m="740450">for</span> <span m="740670">sure</span>
  <span m="741380">one</span> <span m="741740">of</span> <span m="741820">them</span>
  <span m="741990">is</span> <span m="742150">negative.</span></p><p><span m="744230">Its</span>
  <span m="744530">pivots</span> <span m="745450">are</span> <span m="746180">two</span>
  <span m="747000">and</span> <span m="747440">then</span> <span m="747660">the</span>
  <span m="747780">next</span> <span m="748120">pivot</span> <span m="748530">would</span>
  <span m="748720">be</span> <span m="748940">the</span> <span m="749070">determinant</span>
  <span m="749790">over</span> <span m="750170">two,</span> <span m="750810">and</span>
  <span m="751090">the</span> <span m="751190">determinant</span> <span m="751870">is</span>
  <span m="752020">--</span> <span m="752040">what,</span> <span m="752250">what's</span>
  <span m="752450">the</span> <span m="752580">determinant</span> <span m="753070">of</span>
  <span m="753120">this</span> <span m="753350">thing?</span></p><p><span m="755090">Fourteen</span>
  <span m="756030">minus</span> <span m="756540">thirty</span> <span m="756860">six,</span>
  <span m="757290">I've</span> <span m="757460">got</span> <span m="757620">a</span>
  <span m="757720">determinant</span> <span m="758140">minus</span> <span m="758590">twenty</span>
  <span m="758980">two.</span></p><p><span m="759820">The</span> <span m="760010">next</span>
  <span m="760300">pivot</span> <span m="760620">will</span> <span m="760760">be</span>
  <span m="761260">--</span> <span m="761730">the</span> <span m="761860">pivots</span>
  <span m="762440">now,</span> <span m="763330">of</span> <span m="763590">this</span>
  <span m="763870">thing</span> <span m="764220">are</span> <span m="764620">two</span>
  <span m="765190">and</span> <span m="765630">minus</span> <span m="766020">eleven</span>
  <span m="766580">or</span> <span m="766700">something.</span></p><p><span m="768480">Their</span>
  <span m="768660">product</span> <span m="769120">being</span> <span m="769360">minus</span>
  <span m="769730">twenty</span> <span m="770090">two</span> <span m="770360">the</span>
  <span m="770490">determinant.</span></p><p><span m="771320">This</span> <span m="771620">thing</span>
  <span m="771800">is</span> <span m="771970">not</span> <span m="772370">positive</span>
  <span m="772910">definite.</span></p><p><span m="773620">What</span> <span m="773950">would</span>
  <span m="774120">be</span> <span m="774380">--</span> <span m="774760">let</span>
  <span m="774950">me</span> <span m="775100">look</span> <span m="775280">at</span>
  <span m="775380">the</span> <span m="775530">x</span> <span m="775760">transpose</span>
  <span m="776320">Ax</span> <span m="776770">for</span> <span m="776890">this</span>
  <span m="777200">guy.</span></p><p><span m="777700">What's</span> <span m="778100">--</span>
  <span m="778600">if</span> <span m="778740">I</span> <span m="778820">do</span>
  <span m="779040">out</span> <span m="779240">this</span> <span m="779420">multiplication,</span>
  <span m="780460">this</span> <span m="780840">eighteen</span> <span m="781480">is</span>
  <span m="781710">temporarily</span> <span m="782430">changing</span> <span m="783000">to</span>
  <span m="783160">a</span> <span m="783220">seven.</span></p><p><span m="784560">This</span>
  <span m="785090">eighteen</span> <span m="785650">is</span> <span m="785790">temporarily</span>
  <span m="786470">changing</span> <span m="786990">to</span> <span m="787160">a</span>
  <span m="787230">seven,</span> <span m="788130">and</span> <span m="788740">I</span>
  <span m="789080">know</span> <span m="793070">that</span> <span m="793510">there's</span>
  <span m="793720">some</span> <span m="794200">numbers</span> <span m="794780">x1</span>
  <span m="795400">and</span> <span m="795530">x2</span> <span m="796610">for</span>
  <span m="796890">which</span> <span m="797190">that</span> <span m="797860">thing,</span>
  <span m="798630">that</span> <span m="799660">function,</span> <span m="800950">is</span>
  <span m="802150">negative.</span></p><p><span m="804880">And</span> <span m="805140">I'm</span>
  <span m="805290">desperately</span> <span m="806000">trying</span> <span m="806280">to</span>
  <span m="806370">think</span> <span m="806660">what</span> <span m="806950">they</span>
  <span m="807150">are.</span></p><p><span m="808640">Maybe</span> <span m="809010">you</span>
  <span m="809180">can</span> <span m="809380">see.</span></p><p><span m="810040">Can</span>
  <span m="810220">you</span> <span m="810350">tell</span> <span m="810590">me</span>
  <span m="810770">a</span> <span m="810850">value</span> <span m="811370">of</span>
  <span m="811570">x1</span> <span m="812410">and</span> <span m="812570">x2</span>
  <span m="813940">that</span> <span m="814540">makes</span> <span m="815070">this</span>
  <span m="815410">quantity</span> <span m="816300">negative?</span></p><p><span m="820400">Oh,</span>
  <span m="820580">maybe</span> <span m="820900">one</span> <span m="821210">and</span>
  <span m="821330">minus</span> <span m="821710">one?</span></p><p><span m="823180">Yes,</span>
  <span m="823420">that's</span> <span m="825280">--</span> <span m="825390">in</span>
  <span m="825550">this</span> <span m="825820">case,</span> <span m="826210">that,</span>
  <span m="827530">will</span> <span m="828300">work,</span> <span m="828720">right,</span>
  <span m="829270">if</span> <span m="829450">I</span> <span m="829580">took</span>
  <span m="829790">x1</span> <span m="830310">to</span> <span m="830420">be</span>
  <span m="830610">one,</span> <span m="831780">and</span> <span m="832620">x2</span>
  <span m="833080">to</span> <span m="833200">be</span> <span m="833330">minus</span>
  <span m="833820">one,</span> <span m="834150">then</span> <span m="834330">I</span>
  <span m="834490">always</span> <span m="834910">get</span> <span m="835090">something</span>
  <span m="835430">positive,</span> <span m="836030">the</span> <span m="836260">two,</span>
  <span m="837170">and</span> <span m="837560">the</span> <span m="837660">seven</span>
  <span m="838160">minus</span> <span m="838530">one</span> <span m="838850">squared,</span>
  <span m="839330">but</span> <span m="840030">this</span> <span m="840250">would</span>
  <span m="840450">be</span> <span m="840590">minus</span> <span m="840890">twelve</span>
  <span m="841580">and</span> <span m="841700">the</span> <span m="841770">whole</span>
  <span m="841950">thing</span> <span m="842200">would</span> <span m="842450">be</span>
  <span m="842700">negative;</span> <span m="842950">I</span> <span m="843200">would</span>
  <span m="843450">have</span> <span m="843700">two</span> <span m="843960">minus</span>
  <span m="844270">twelve</span> <span m="844750">plus</span> <span m="845010">seven,</span>
  <span m="845370">a</span> <span m="845580">negative.</span></p><p><span m="847620">If</span>
  <span m="847830">I</span> <span m="848020">drew</span> <span m="848350">the</span>
  <span m="848460">graph,</span> <span m="849040">can</span> <span m="849190">I</span>
  <span m="849580">get</span> <span m="850320">the</span> <span m="850440">little</span>
  <span m="850750">picture</span> <span m="851320">in</span></p><p><span m="851550">here?</span>
  <span m="852050">If</span> <span m="852350">I</span> <span m="852530">draw</span>
  <span m="852850">the</span> <span m="852990">graph</span> <span m="853460">of</span>
  <span m="853630">this</span> <span m="853940">thing?</span></p><p><span m="856430">So,</span>
  <span m="856730">graphs,</span> <span m="857950">of</span> <span m="859790">the</span>
  <span m="860470">function</span> <span m="861120">f(x,y),</span> <span m="862080">or</span>
  <span m="862550">f(x),</span> <span m="862730">so</span> <span m="862770">I</span>
  <span m="862840">say</span> <span m="863010">here</span> <span m="864100">f(x,y)</span>
  <span m="867360">equal</span> <span m="868360">this</span> <span m="868590">--</span>
  <span m="868620">x</span> <span m="868680">transpose</span> <span m="868870">Ax,</span>
  <span m="868940">this,</span> <span m="869620">this</span> <span m="869920">this</span>
  <span m="870250">ax</span> <span m="870840">squared,</span> <span m="871150">2bxy,</span>
  <span m="871370">and</span> <span m="871730">cy</span> <span m="871910">squared.</span></p><p><span
  m="872040">And,</span> <span m="882550">let's</span> <span m="882830">take</span>
  <span m="883430">the</span> <span m="883580">example,</span> <span m="885260">with</span>
  <span m="885960">these</span> <span m="886230">numbers.</span></p><p><span m="889210">OK,</span>
  <span m="889600">so</span> <span m="890260">here's</span> <span m="890540">the</span>
  <span m="890680">x</span> <span m="890960">axis,</span> <span m="892000">here's</span>
  <span m="892470">the</span> <span m="892550">y</span> <span m="892880">axis,</span>
  <span m="893220">and</span> <span m="893660">here's</span> <span m="894320">--</span>
  <span m="894650">up</span> <span m="895120">is</span> <span m="895340">the</span>
  <span m="895420">function.</span></p><p><span m="896380">z,</span> <span m="896720">if</span>
  <span m="896820">you</span> <span m="897000">like,</span> <span m="897340">or</span>
  <span m="897520">f.</span></p><p><span m="899390">I</span> <span m="899960">apologize,</span>
  <span m="900820">and</span> <span m="900920">let</span> <span m="901100">me,</span>
  <span m="901540">just</span> <span m="902040">once</span> <span m="902600">in</span>
  <span m="902740">my</span> <span m="902930">life</span> <span m="903360">here,</span>
  <span m="903940">put</span> <span m="904110">an</span> <span m="904260">arrow</span>
  <span m="904950">over</span> <span m="905310">these,</span> <span m="905850">these,</span>
  <span m="906210">axes</span> <span m="906640">so</span> <span m="906850">you</span>
  <span m="907050">see</span> <span m="907360">them.</span></p><p><span m="908780">That's</span>
  <span m="909140">the</span> <span m="909260">vector</span> <span m="909810">and</span>
  <span m="910080">I</span> <span m="910230">just,</span> <span m="910830">see,</span>
  <span m="911230">instead</span> <span m="911580">of</span> <span m="911680">x1</span>
  <span m="912140">and</span> <span m="912250">x2,</span> <span m="913300">I</span>
  <span m="913440">made</span> <span m="913690">them</span> <span m="913890">x-</span>
  <span m="914230">the</span> <span m="914410">components</span> <span m="914980">x</span>
  <span m="915220">and</span> <span m="915370">y.</span></p><p><span m="916220">OK.</span>
  <span m="916930">So,</span> <span m="917850">so,</span> <span m="918230">what's</span>
  <span m="918470">a</span> <span m="918610">graph</span> <span m="919120">of</span>
  <span m="919310">2x</span> <span m="919780">squared,</span> <span m="921170">twelve</span>
  <span m="922630">xy,</span> <span m="922760">and</span> <span m="922970">seven</span>
  <span m="923360">y</span> <span m="923660">squared?</span></p><p><span m="925710">I'd</span>
  <span m="925880">like</span> <span m="926140">to</span> <span m="926210">see</span>
  <span m="927070">--</span> <span m="927660">I</span> <span m="929270">not</span>
  <span m="930330">the</span> <span m="930420">greatest</span> <span m="930780">artist,</span>
  <span m="931000">but</span> <span m="931060">let's</span> <span m="931230">--</span>
  <span m="931260">tell</span> <span m="931320">me</span> <span m="935410">something</span>
  <span m="935880">about</span> <span m="936340">this</span> <span m="936970">graph</span>
  <span m="937750">of</span> <span m="937830">this</span> <span m="938120">function.</span></p><p><span
  m="942560">Whoa,</span> <span m="942830">tell</span> <span m="942980">me</span>
  <span m="943130">one</span> <span m="943460">point</span> <span m="943730">that</span>
  <span m="943800">it</span> <span m="943930">goes</span> <span m="944320">through.</span></p><p><span
  m="947970">The</span> <span m="948700">origin.</span></p><p><span m="949470">Right?</span></p><p><span
  m="950990">Even</span> <span m="951630">this</span> <span m="951920">artist</span>
  <span m="952450">can</span> <span m="952670">get</span> <span m="952930">this</span>
  <span m="953160">thing</span> <span m="953410">to</span> <span m="953560">go</span>
  <span m="954200">through</span> <span m="955330">the</span> <span m="955530">origin,</span>
  <span m="956450">when</span> <span m="957040">these</span> <span m="957280">are</span>
  <span m="957470">zero,</span> <span m="958430">I,</span> <span m="958680">I</span>
  <span m="958820">certainly</span> <span m="959200">get</span> <span m="959440">zero.</span></p><p><span
  m="960590">OK.</span> <span m="960920">Some</span> <span m="961090">more</span>
  <span m="961400">points.</span></p><p><span m="962540">If</span> <span m="962760">x</span>
  <span m="963180">is</span> <span m="963430">one</span> <span m="964040">and</span>
  <span m="964360">y</span> <span m="964670">is</span> <span m="964990">zero,</span>
  <span m="965300">then</span> <span m="965620">I'm</span> <span m="965940">going</span>
  <span m="966250">upwards,</span> <span m="966570">so</span> <span m="966720">I'm</span>
  <span m="966920">going</span> <span m="967180">up</span> <span m="967460">this</span>
  <span m="967710">way,</span> <span m="968200">and</span> <span m="968610">I'm,</span>
  <span m="968900">I'm</span> <span m="969060">going</span> <span m="969250">up,</span>
  <span m="969490">like,</span> <span m="969730">two</span> <span m="969970">x</span>
  <span m="970270">squared</span> <span m="970650">in</span> <span m="970760">that</span>
  <span m="970990">direction.</span></p><p><span m="972180">So</span> <span m="972440">--</span>
  <span m="972470">that's</span> <span m="972670">meant</span> <span m="972950">to</span>
  <span m="973040">be</span> <span m="973310">a</span> <span m="974340">parabola.</span></p><p><span
  m="978200">And,</span> <span m="979120">suppose</span> <span m="979640">x</span>
  <span m="979830">stays</span> <span m="980490">zero</span> <span m="981000">and</span>
  <span m="981160">y</span> <span m="981920">increases.</span></p><p><span m="983150">Well,</span>
  <span m="983810">y</span> <span m="984080">could</span> <span m="984270">be</span>
  <span m="984410">positive</span> <span m="984920">or</span> <span m="985040">negative;</span>
  <span m="985450">it's</span> <span m="985640">seven</span> <span m="985950">y</span>
  <span m="986180">squared.</span></p><p><span m="986760">Is</span> <span m="986930">this</span>
  <span m="987460">function</span> <span m="987920">going</span> <span m="988180">upward?</span></p><p><span
  m="990530">In</span> <span m="990810">the</span> <span m="990910">x</span> <span
  m="991180">direction</span> <span m="991690">it's</span> <span m="991880">going</span>
  <span m="992160">upward,</span> <span m="993590">and</span> <span m="994580">in</span>
  <span m="994710">the</span> <span m="994810">y</span> <span m="995130">direction</span>
  <span m="995640">it's</span> <span m="995830">going</span> <span m="996070">upwards,</span>
  <span m="997500">and</span> <span m="998410">if</span> <span m="998570">x</span>
  <span m="998920">equals</span> <span m="999460">y</span> <span m="999900">then</span>
  <span m="1000040">the</span> <span m="1000190">forty-five</span> <span m="1000820">degree</span>
  <span m="1001140">direction</span> <span m="1001690">is</span> <span m="1001800">certainly</span>
  <span m="1002140">going</span> <span m="1002450">upwards;</span> <span m="1003400">because</span>
  <span m="1003880">then</span> <span m="1004070">we'd</span> <span m="1004240">have</span>
  <span m="1004640">what,</span> <span m="1004810">about,</span> <span m="1005810">everything</span>
  <span m="1006490">would</span> <span m="1006620">be</span> <span m="1006760">positive,</span>
  <span m="1007520">but</span> <span m="1008040">what?</span></p><p><span m="1009600">This</span>
  <span m="1009950">function</span> <span m="1010460">--</span> <span m="1010490">what's</span>
  <span m="1012340">the</span> <span m="1012850">graph</span> <span m="1013280">of</span>
  <span m="1013440">this</span> <span m="1013710">function?</span></p><p><span m="1014810">Look</span>
  <span m="1015080">like?</span></p><p><span m="1015310">Tell</span> <span m="1015500">me</span>
  <span m="1015730">the</span> <span m="1016620">word</span> <span m="1017490">that</span>
  <span m="1017620">describes</span> <span m="1018450">the</span> <span m="1018750">graph</span>
  <span m="1019250">of</span> <span m="1019430">this</span> <span m="1019830">function.</span></p><p><span
  m="1020450">This</span> <span m="1020650">is</span> <span m="1020830">the</span>
  <span m="1020990">non-positive</span> <span m="1021830">definite</span> <span m="1022440">here,</span>
  <span m="1022980">everybody's</span> <span m="1023620">with</span> <span m="1023840">me</span>
  <span m="1024020">here,</span> <span m="1025010">for</span> <span m="1025410">some</span>
  <span m="1026579">reason</span> <span m="1027660">got</span> <span m="1027839">started</span>
  <span m="1028380">in</span> <span m="1028500">a</span> <span m="1028609">negative</span>
  <span m="1029160">direction,</span> <span m="1029800">your</span> <span m="1030280">case</span>
  <span m="1030530">that</span> <span m="1030740">isn't</span> <span m="1031339">positive</span>
  <span m="1031880">definite.</span></p><p><span m="1032750">And</span> <span m="1033190">what's</span>
  <span m="1033970">the</span> <span m="1034500">graph</span> <span m="1034829">look</span>
  <span m="1035010">like</span> <span m="1035270">that</span> <span m="1035440">goes</span>
  <span m="1035690">up,</span> <span m="1036060">but</span> <span m="1036230">does</span>
  <span m="1036440">it</span> <span m="1036859">--</span> <span m="1037190">do</span>
  <span m="1037310">we</span> <span m="1037470">have</span> <span m="1037750">a</span>
  <span m="1037829">minimum</span> <span m="1038310">here,</span> <span m="1038630">does</span>
  <span m="1038780">it</span> <span m="1038950">go</span> <span m="1039089">from,</span>
  <span m="1039369">from</span> <span m="1039660">the</span> <span m="1040300">origin?</span></p><p><span
  m="1042710">Completely?</span></p><p><span m="1044500">No,</span> <span m="1044930">because</span>
  <span m="1045400">we</span> <span m="1045869">just</span> <span m="1046339">checked</span>
  <span m="1046819">that</span> <span m="1047290">this</span> <span m="1047760">thing</span>
  <span m="1048230">failed.</span> <span m="1048710">It</span> <span m="1048870">failed</span>
  <span m="1049320">along</span> <span m="1049980">the</span> <span m="1050230">direction</span>
  <span m="1051330">when</span> <span m="1051630">x</span> <span m="1051940">was</span>
  <span m="1052240">minus</span> <span m="1052750">y</span> <span m="1053340">--</span>
  <span m="1053490">we</span> <span m="1053680">have</span> <span m="1053870">a</span>
  <span m="1053940">saddle</span> <span m="1054470">point,</span> <span m="1054730">let</span>
  <span m="1054900">me</span> <span m="1055110">put</span> <span m="1055690">myself,</span>
  <span m="1056660">let</span> <span m="1056880">me,</span> <span m="1057080">to</span>
  <span m="1057210">the</span> <span m="1057350">least,</span> <span m="1057560">tell</span>
  <span m="1057750">you</span> <span m="1057900">the</span> <span m="1057980">word.</span></p><p><span
  m="1059350">This</span> <span m="1059800">thing,</span> <span m="1060790">goes</span>
  <span m="1061630">up</span> <span m="1061920">in</span> <span m="1062060">some</span>
  <span m="1062430">directions,</span> <span m="1066470">but</span> <span m="1066710">down</span>
  <span m="1067080">in</span> <span m="1067200">other</span> <span m="1067570">directions,</span>
  <span m="1069100">and</span> <span m="1071530">if</span> <span m="1072470">we</span>
  <span m="1072660">actually</span> <span m="1073010">knew</span> <span m="1073180">what</span>
  <span m="1073330">a</span> <span m="1073550">saddle</span> <span m="1073990">looked</span>
  <span m="1074280">like</span> <span m="1074550">or</span> <span m="1074750">thinks</span>
  <span m="1075070">saddles</span> <span m="1075530">do</span> <span m="1078150">that</span>
  <span m="1078520">--</span> <span m="1079300">the</span> <span m="1079860">way</span>
  <span m="1080180">your</span> <span m="1080380">legs</span> <span m="1081210">go</span>
  <span m="1082430">is,</span> <span m="1082910">like,</span> <span m="1083330">down,</span>
  <span m="1084110">up,</span> <span m="1084900">the</span> <span m="1085730">way,</span>
  <span m="1086020">you,</span> <span m="1086560">looking</span> <span m="1087270">like,</span>
  <span m="1087800">forward,</span> <span m="1089620">and,</span> <span m="1091270">the,</span>
  <span m="1094490">and</span> <span m="1094750">drawing</span> <span m="1095140">the</span>
  <span m="1095340">thing</span> <span m="1095610">is</span> <span m="1095910">even</span>
  <span m="1096200">worse</span> <span m="1096550">than</span> <span m="1096670">describing</span>
  <span m="1097310">--</span> <span m="1097330">I'm</span> <span m="1097550">just</span>
  <span m="1097710">going</span> <span m="1097840">to</span> <span m="1097890">say</span>
  <span m="1097940">in</span> <span m="1097980">some</span> <span m="1098040">directions</span>
  <span m="1099080">we</span> <span m="1100010">go</span> <span m="1100250">up</span>
  <span m="1100760">and</span> <span m="1100980">in</span> <span m="1101140">other</span>
  <span m="1101450">directions,</span> <span m="1102650">there</span> <span m="1103690">is,</span>
  <span m="1104860">a</span> <span m="1107030">saddle</span> <span m="1108270">--</span>
  <span m="1108290">Now</span> <span m="1108350">I'm</span> <span m="1108530">sorry</span>
  <span m="1108820">I</span> <span m="1108960">put</span> <span m="1109120">that</span>
  <span m="1109310">on</span> <span m="1109410">the</span> <span m="1109580">front</span>
  <span m="1109870">board,</span> <span m="1110330">you</span> <span m="1110380">have</span>
  <span m="1110560">no</span> <span m="1110710">way</span> <span m="1111580">to</span>
  <span m="1112100">cover</span> <span m="1112910">it,</span> <span m="1113110">but</span>
  <span m="1113600">it's</span> <span m="1113850">a</span> <span m="1113990">saddle.</span></p><p><span
  m="1114450">OK.</span> <span m="1115360">And,</span> <span m="1116330">and</span>
  <span m="1116590">this</span> <span m="1116820">is</span> <span m="1116980">a</span>
  <span m="1117110">saddle</span> <span m="1117820">point,</span> <span m="1118640">it's</span>
  <span m="1118950">the,</span> <span m="1119390">it's</span> <span m="1119580">the</span>
  <span m="1119800">point</span> <span m="1120190">that's</span> <span m="1120970">at</span>
  <span m="1121350">the</span> <span m="1121560">maximum</span> <span m="1122520">in</span>
  <span m="1122750">some</span> <span m="1123050">directions</span> <span m="1123900">and</span>
  <span m="1124160">at</span> <span m="1124380">the</span> <span m="1124490">minimum</span>
  <span m="1125020">in</span> <span m="1125150">other</span> <span m="1125370">directions.</span></p><p><span
  m="1126770">And</span> <span m="1127150">actually,</span> <span m="1128300">the</span>
  <span m="1128840">perfect</span> <span m="1129600">directions</span> <span m="1130250">to</span>
  <span m="1130350">look</span> <span m="1130840">are</span> <span m="1131100">the</span>
  <span m="1131320">eigenvector</span> <span m="1132420">directions.</span></p><p><span
  m="1133670">We'll</span> <span m="1133910">see</span> <span m="1134200">that.</span></p><p><span
  m="1135260">So</span> <span m="1135440">this</span> <span m="1135670">is,</span>
  <span m="1141610">not</span> <span m="1142080">a</span> <span m="1142180">positive</span>
  <span m="1142610">definite</span> <span m="1143170">matrix.</span></p><p><span m="1143730">OK.</span>
  <span m="1144280">Now</span> <span m="1144840">I'm</span> <span m="1145400">coming</span>
  <span m="1145960">back</span> <span m="1146520">to</span> <span m="1147070">this</span>
  <span m="1147630">example,</span> <span m="1148190">getting</span> <span m="1148440">rid</span>
  <span m="1148590">of</span> <span m="1148680">this</span> <span m="1149040">seven,</span>
  <span m="1150190">let's</span> <span m="1150980">move</span> <span m="1151170">it</span>
  <span m="1151330">up</span> <span m="1151690">to</span> <span m="1152940">twenty.</span></p><p><span
  m="1154400">Let's,</span> <span m="1154670">let's</span> <span m="1155080">let's</span>
  <span m="1155390">make</span> <span m="1155740">the</span> <span m="1155830">thing</span>
  <span m="1156300">really</span> <span m="1156710">positive</span> <span m="1157390">definite.</span></p><p><span
  m="1158420">OK.</span> <span m="1159470">So</span> <span m="1160240">this</span>
  <span m="1160460">is,</span> <span m="1160640">this</span> <span m="1160880">number's</span>
  <span m="1161220">now</span> <span m="1161690">twenty.</span></p><p><span m="1162990">c</span>
  <span m="1163210">is</span> <span m="1163360">now</span> <span m="1163640">twenty.</span></p><p><span
  m="1164650">OK.</span></p><p><span m="1164860">Now</span> <span m="1164910">that</span>
  <span m="1164980">passes</span> <span m="1165100">the</span> <span m="1165150">test,</span>
  <span m="1168510">which</span> <span m="1168690">I</span> <span m="1168850">haven't</span>
  <span m="1169410">proved,</span> <span m="1169970">of</span> <span m="1170140">course,</span>
  <span m="1170800">it</span> <span m="1171270">passes</span> <span m="1171740">the</span>
  <span m="1171930">test</span> <span m="1172650">for</span> <span m="1173220">positive</span>
  <span m="1174160">pivots.</span></p><p><span m="1174960">It</span> <span m="1177650">passes</span>
  <span m="1178110">the</span> <span m="1178240">test</span> <span m="1178620">for</span>
  <span m="1178790">positive</span> <span m="1179400">eigenvalues.</span></p><p><span
  m="1180270">How</span> <span m="1180600">can</span> <span m="1180740">you</span>
  <span m="1180860">tell</span> <span m="1181120">that</span> <span m="1181300">the</span>
  <span m="1181450">eigenvalues</span> <span m="1182300">of</span> <span m="1182410">that</span>
  <span m="1182670">matrix</span> <span m="1183160">are</span> <span m="1183320">positive</span>
  <span m="1183830">without</span> <span m="1184270">actually</span> <span m="1184720">finding</span>
  <span m="1185220">them?</span></p><p><span m="1185850">Of</span> <span m="1185980">course,</span>
  <span m="1186690">two</span> <span m="1187100">by</span> <span m="1187280">two</span>
  <span m="1187560">I</span> <span m="1187650">could</span> <span m="1187910">find</span>
  <span m="1188210">them,</span> <span m="1188350">but</span> <span m="1188680">can</span>
  <span m="1188900">you</span> <span m="1189040">see</span> <span m="1189320">--</span>
  <span m="1189400">how</span> <span m="1189530">do</span> <span m="1189670">I</span>
  <span m="1189780">know</span> <span m="1190040">they're</span> <span m="1190220">positive?</span></p><p><span
  m="1191530">I</span> <span m="1191680">know</span> <span m="1192000">that</span>
  <span m="1192210">their</span> <span m="1192410">product</span> <span m="1193030">is</span>
  <span m="1193220">--</span> <span m="1193270">I</span> <span m="1193390">know</span>
  <span m="1193610">that</span> <span m="1193750">lambda</span> <span m="1194190">one</span>
  <span m="1194570">times</span> <span m="1195080">lambda</span> <span m="1195480">two</span>
  <span m="1195740">is</span> <span m="1195890">positive,</span> <span m="1196490">why?</span></p><p><span
  m="1198020">Because</span> <span m="1198480">that's</span> <span m="1198990">the</span>
  <span m="1200160">determinant,</span> <span m="1201350">right,</span> <span m="1201750">lambda</span>
  <span m="1202190">one</span> <span m="1202500">times</span> <span m="1202970">lambda</span>
  <span m="1203350">two</span> <span m="1203900">is</span> <span m="1204280">the</span>
  <span m="1204400">determinant,</span> <span m="1205130">which</span> <span m="1205390">is</span>
  <span m="1205540">forty</span> <span m="1206000">minus</span> <span m="1206420">thirty-six</span>
  <span m="1207100">is</span> <span m="1207280">four.</span></p><p><span m="1207730">So</span>
  <span m="1207870">the</span> <span m="1208030">determinant</span> <span m="1209010">is</span>
  <span m="1209530">four.</span></p><p><span m="1211120">And</span> <span m="1211360">the</span>
  <span m="1211490">trace,</span> <span m="1212610">the</span> <span m="1213440">sum</span>
  <span m="1213830">down</span> <span m="1214080">the</span> <span m="1214190">diagonal,</span>
  <span m="1214770">is</span> <span m="1214900">twenty-two.</span> <span m="1216160">So,</span>
  <span m="1217040">they</span> <span m="1217340">multiply</span> <span m="1217960">to</span>
  <span m="1218040">give</span> <span m="1218350">four.</span></p><p><span m="1220630">So</span>
  <span m="1220820">that</span> <span m="1221140">leaves</span> <span m="1221460">the</span>
  <span m="1221570">possibility</span> <span m="1222370">they're</span> <span m="1222600">either</span>
  <span m="1222850">both</span> <span m="1223180">positive</span> <span m="1224060">or</span>
  <span m="1224330">both</span> <span m="1224620">negative.</span></p><p><span m="1225730">But</span>
  <span m="1227060">if</span> <span m="1227160">they're</span> <span m="1227310">both</span>
  <span m="1227540">negative,</span> <span m="1228360">the</span> <span m="1228610">trace</span>
  <span m="1228960">couldn't</span> <span m="1229240">be</span></p><p><span m="1230130">So</span>
  <span m="1230380">they're</span> <span m="1230510">both</span> <span m="1230800">positive.</span>
  <span m="1231100">twenty-two.</span> <span m="1231520">So</span> <span m="1231880">both</span>
  <span m="1232200">of</span> <span m="1232310">the</span> <span m="1232510">eigenvalues</span>
  <span m="1233280">that</span> <span m="1233420">are</span> <span m="1233650">positive,</span>
  <span m="1234170">both</span> <span m="1234410">of</span> <span m="1234510">the</span>
  <span m="1234610">pivots</span> <span m="1235040">are</span> <span m="1235150">positive</span>
  <span m="1235770">--</span> <span m="1236220">the</span> <span m="1236410">determinants</span>
  <span m="1237110">are</span> <span m="1237210">positive,</span> <span m="1238030">and</span>
  <span m="1238470">I</span> <span m="1238700">believe</span> <span m="1239280">that</span>
  <span m="1239500">this</span> <span m="1239820">function</span> <span m="1241240">is</span>
  <span m="1242290">positive</span> <span m="1242920">everywhere</span> <span m="1243590">except</span>
  <span m="1244370">at</span> <span m="1245590">zero,</span> <span m="1246710">zero,</span>
  <span m="1247260">of</span> <span m="1247410">course.</span></p><p><span m="1248240">When</span>
  <span m="1248430">I</span> <span m="1248540">write</span> <span m="1248910">down</span>
  <span m="1249920">this</span> <span m="1251190">condition,</span> <span m="1252330">So</span>
  <span m="1252710">I</span> <span m="1252880">believe</span> <span m="1253370">that</span>
  <span m="1253530">x</span> <span m="1253890">transposed,</span> <span m="1254560">let</span>
  <span m="1254670">me</span> <span m="1254890">copy,</span> <span m="1255260">x</span>
  <span m="1255570">transpose</span> <span m="1256260">Ax</span> <span m="1256820">is</span>
  <span m="1257050">positive,</span> <span m="1258140">except,</span> <span m="1259020">of</span>
  <span m="1259200">course,</span> <span m="1260280">at</span> <span m="1261080">the</span>
  <span m="1261540">minimum</span> <span m="1262150">point,</span> <span m="1263060">at</span>
  <span m="1264910">zero,</span> <span m="1266380">of</span> <span m="1266810">course,</span>
  <span m="1267450">I</span> <span m="1267560">don't</span> <span m="1267840">expect</span>
  <span m="1268490">miracles.</span></p><p><span m="1271760">So</span> <span m="1271930">what</span>
  <span m="1272220">does</span> <span m="1272400">its</span> <span m="1272660">graph</span>
  <span m="1273030">look</span> <span m="1273320">like,</span> <span m="1273880">and</span>
  <span m="1274460">how</span> <span m="1274780">do</span> <span m="1274940">I</span>
  <span m="1275090">check,</span> <span m="1275720">and</span> <span m="1275900">how</span>
  <span m="1276120">do</span> <span m="1276250">I</span> <span m="1276370">check</span>
  <span m="1276730">that</span> <span m="1276880">this</span> <span m="1277360">really</span>
  <span m="1277940">is</span> <span m="1278320">positive?</span></p><p><span m="1282300">So</span>
  <span m="1282370">we</span> <span m="1282470">take</span> <span m="1282700">it's</span>
  <span m="1282890">graph</span> <span m="1283280">for</span> <span m="1283440">a</span>
  <span m="1283490">minute.</span></p><p><span m="1284960">What</span> <span m="1285220">would</span>
  <span m="1285400">be</span> <span m="1285630">the</span> <span m="1285770">graph</span>
  <span m="1286240">of</span> <span m="1286350">that</span> <span m="1286700">function</span>
  <span m="1287180">--</span> <span m="1287200">it</span> <span m="1287340">does</span>
  <span m="1287560">not</span> <span m="1287900">have</span> <span m="1288130">a</span>
  <span m="1288190">saddle</span> <span m="1288660">point.</span></p><p><span m="1289400">Let</span>
  <span m="1289590">me</span> <span m="1289790">--</span> <span m="1289810">I'll</span>
  <span m="1289990">raise</span> <span m="1290310">the</span> <span m="1290420">board,</span>
  <span m="1290800">here,</span> <span m="1291280">and</span> <span m="1291600">stay</span>
  <span m="1291970">with</span> <span m="1292140">this</span> <span m="1292340">example</span>
  <span m="1292900">for</span> <span m="1293030">a</span> <span m="1293070">while.</span></p><p><span
  m="1296280">So</span> <span m="1296570">I</span> <span m="1296770">want</span> <span
  m="1297010">to</span> <span m="1297100">do</span> <span m="1297520">the</span> <span
  m="1297620">graph</span> <span m="1298120">of</span> <span m="1298280">--</span>
  <span m="1298360">here's</span> <span m="1298640">my</span> <span m="1298820">function,</span>
  <span m="1300660">two</span> <span m="1301870">x</span> <span m="1302130">squared,</span>
  <span m="1303450">twelve</span> <span m="1304130">xy-s,</span> <span m="1304940">that</span>
  <span m="1305190">could</span> <span m="1305350">be</span> <span m="1305510">positive</span>
  <span m="1306060">or</span> <span m="1306180">negative,</span> <span m="1306940">and</span>
  <span m="1307320">twenty</span> <span m="1307720">y</span> <span m="1308020">squared.</span></p><p><span
  m="1308510">But</span> <span m="1312600">my</span> <span m="1312700">point</span>
  <span m="1313070">is,</span> <span m="1313430">so</span> <span m="1313870">you're</span>
  <span m="1314380">seeing</span> <span m="1314660">the</span> <span m="1314780">underlying</span>
  <span m="1315360">point</span> <span m="1315720">is,</span> <span m="1316290">that,</span>
  <span m="1317230">the</span> <span m="1317990">things</span> <span m="1318430">are</span>
  <span m="1318560">positive</span> <span m="1319130">definite</span> <span m="1319910">when</span>
  <span m="1320380">in</span> <span m="1320510">some</span> <span m="1320800">way,</span>
  <span m="1321220">these,</span> <span m="1322300">these</span> <span m="1323150">pure</span>
  <span m="1323740">squares,</span> <span m="1325010">squares</span> <span m="1325730">we</span>
  <span m="1325890">know</span> <span m="1326160">to</span> <span m="1326250">be</span>
  <span m="1326420">positive,</span> <span m="1327490">and</span> <span m="1328170">when</span>
  <span m="1328380">those</span> <span m="1328920">kind</span> <span m="1329220">of</span>
  <span m="1329340">overwhelm</span> <span m="1330180">this</span> <span m="1330460">guy,</span>
  <span m="1331260">who</span> <span m="1331780">could</span> <span m="1332020">be</span>
  <span m="1332330">m-</span> <span m="1332380">positive</span> <span m="1332880">or</span>
  <span m="1333070">negative,</span> <span m="1333790">because</span> <span m="1334250">some</span>
  <span m="1334510">like</span> <span m="1334690">or</span> <span m="1334710">have</span>
  <span m="1334770">same</span> <span m="1334830">or</span> <span m="1334890">have</span>
  <span m="1335110">same</span> <span m="1335580">or</span> <span m="1335690">different</span>
  <span m="1336120">signs,</span> <span m="1337320">when</span> <span m="1338410">these</span>
  <span m="1339070">are</span> <span m="1339180">big</span> <span m="1339470">enough</span>
  <span m="1339760">they</span> <span m="1339970">overwhelm</span> <span m="1340540">this</span>
  <span m="1340770">guy</span> <span m="1340970">and</span> <span m="1341070">make</span>
  <span m="1341290">the</span> <span m="1341410">total</span> <span m="1341750">thing</span>
  <span m="1341980">positive,</span> <span m="1342850">and</span> <span m="1343300">what</span>
  <span m="1343670">would</span> <span m="1343860">the</span> <span m="1343950">graph</span>
  <span m="1344440">now</span> <span m="1344760">look</span> <span m="1345020">like?</span></p><p><span
  m="1345750">Let</span> <span m="1345900">me</span> <span m="1346030">draw</span>
  <span m="1346270">the</span> <span m="1346430">x</span> <span m="1346840">-</span>
  <span m="1349690">well,</span> <span m="1350180">let</span> <span m="1350440">me</span>
  <span m="1350550">draw</span> <span m="1350780">the</span> <span m="1350940">x</span>
  <span m="1351270">direction,</span> <span m="1352240">the</span> <span m="1352580">y</span>
  <span m="1352940">direction,</span> <span m="1354090">and</span> <span m="1355050">the</span>
  <span m="1355270">origin,</span> <span m="1356700">at</span> <span m="1357710">zero,</span>
  <span m="1358070">zero,</span> <span m="1359290">I'm</span> <span m="1360140">there,</span>
  <span m="1360970">where</span> <span m="1361460">do</span> <span m="1361620">I</span>
  <span m="1361750">go</span> <span m="1362290">as</span> <span m="1362480">I</span>
  <span m="1362570">move</span> <span m="1362850">away</span> <span m="1363240">from</span>
  <span m="1363460">the</span> <span m="1363600">origin?</span></p><p><span m="1365650">Where</span>
  <span m="1366460">do</span> <span m="1366590">I</span> <span m="1366700">go</span>
  <span m="1366980">as</span> <span m="1367110">I</span> <span m="1367200">move</span>
  <span m="1367440">away</span> <span m="1367750">from</span> <span m="1367950">the</span>
  <span m="1368090">origin?</span></p><p><span m="1370780">I'm</span> <span m="1371060">sure</span>
  <span m="1371580">that</span> <span m="1371790">I</span> <span m="1371940">go</span>
  <span m="1372380">up.</span></p><p><span m="1373240">The</span> <span m="1373890">origin,</span>
  <span m="1375120">the</span> <span m="1375440">center</span> <span m="1375900">point</span>
  <span m="1376220">here,</span> <span m="1376660">is</span> <span m="1376890">a</span>
  <span m="1376980">minim</span> <span m="1377390">because</span> <span m="1378040">this</span>
  <span m="1378560">thing</span> <span m="1379340">I</span> <span m="1379750">believe,</span>
  <span m="1380210">and</span> <span m="1380290">we</span> <span m="1380440">better</span>
  <span m="1380750">see</span> <span m="1380980">why,</span> <span m="1381730">it's,</span>
  <span m="1382360">the</span> <span m="1382640">graph</span> <span m="1383150">is</span>
  <span m="1383330">like</span> <span m="1383560">a</span> <span m="1383650">bowl,</span>
  <span m="1384980">the</span> <span m="1385500">graph</span> <span m="1385800">is</span>
  <span m="1385910">like</span> <span m="1386100">a</span> <span m="1386180">bowl</span>
  <span m="1386850">shape,</span> <span m="1387620">it's</span> <span m="1388470">--</span>
  <span m="1388910">here's</span> <span m="1389300">the</span> <span m="1389400">minimum.</span></p><p><span
  m="1395660">And</span> <span m="1395920">because</span> <span m="1397030">we've</span>
  <span m="1397420">got</span> <span m="1397670">a</span> <span m="1397720">pure</span>
  <span m="1398160">quadratic,</span> <span m="1399030">we</span> <span m="1399290">know</span>
  <span m="1399620">it</span> <span m="1399740">sits</span> <span m="1400150">at</span>
  <span m="1400260">the</span> <span m="1400440">origin,</span> <span m="1401050">we</span>
  <span m="1401180">know</span> <span m="1401420">it's</span> <span m="1401700">tangent</span>
  <span m="1402690">plane,</span> <span m="1403410">the</span> <span m="1403600">first</span>
  <span m="1403980">derivatives</span> <span m="1405230">are</span> <span m="1405750">zero,</span>
  <span m="1407330">so,</span> <span m="1408750">we</span> <span m="1409000">know,</span>
  <span m="1409390">first</span> <span m="1409800">derivatives,</span> <span m="1410970">First</span>
  <span m="1411660">derivatives</span> <span m="1413010">are</span> <span m="1414010">all</span>
  <span m="1414320">zero,</span> <span m="1415960">but</span> <span m="1417130">that's</span>
  <span m="1417410">not</span> <span m="1417660">enough</span> <span m="1417950">for</span>
  <span m="1418060">a</span> <span m="1418120">minimum.</span></p><p><span m="1418560">It's</span>
  <span m="1420840">first</span> <span m="1421380">derivatives</span> <span m="1421970">were</span>
  <span m="1422170">zero</span> <span m="1422630">here.</span></p><p><span m="1425780">So,</span>
  <span m="1426360">the</span> <span m="1426840">partial</span> <span m="1427320">derivatives,</span>
  <span m="1427860">the</span> <span m="1427980">first</span> <span m="1428620">derivatives,</span>
  <span m="1429740">are</span> <span m="1430040">zero.</span></p><p><span m="1431200">Again,</span>
  <span m="1432300">because</span> <span m="1433230">first</span> <span m="1433550">derivatives</span>
  <span m="1434780">are</span> <span m="1435320">gonna</span> <span m="1435530">have</span>
  <span m="1435750">an</span> <span m="1435860">x</span> <span m="1436130">or</span>
  <span m="1436230">an</span> <span m="1436310">a</span> <span m="1436370">y,</span>
  <span m="1436720">or</span> <span m="1436960">a</span> <span m="1437020">y</span>
  <span m="1437340">in</span> <span m="1437540">them,</span> <span m="1437700">they'll</span>
  <span m="1437890">be</span> <span m="1438060">zero</span> <span m="1438490">at</span>
  <span m="1438590">the</span> <span m="1438720">origin.</span></p><p><span m="1439730">It's</span>
  <span m="1439990">the</span> <span m="1440120">second</span> <span m="1440580">derivatives</span>
  <span m="1441140">that</span> <span m="1441330">control</span> <span m="1441860">everything.</span></p><p><span
  m="1443340">It's</span> <span m="1443580">the</span> <span m="1443730">second</span>
  <span m="1444290">derivatives</span> <span m="1444940">that</span> <span m="1445160">this</span>
  <span m="1445400">matrix</span> <span m="1446000">is</span> <span m="1446170">telling</span>
  <span m="1446630">us,</span> <span m="1447810">and</span> <span m="1448030">somehow</span>
  <span m="1448860">--</span> <span m="1450630">here's</span> <span m="1450880">my</span>
  <span m="1451070">point.</span></p><p><span m="1451780">You</span> <span m="1451890">remember</span>
  <span m="1452290">in</span> <span m="1452400">Calculus,</span> <span m="1453330">how</span>
  <span m="1453720">did</span> <span m="1453920">you</span> <span m="1454020">decide</span>
  <span m="1454650">on</span> <span m="1454810">a</span> <span m="1454880">minimum?</span></p><p><span
  m="1456710">First</span> <span m="1457060">requirement</span> <span m="1457750">was,</span>
  <span m="1458620">that</span> <span m="1458950">the</span> <span m="1459090">derivative</span>
  <span m="1459590">had</span> <span m="1459800">to</span> <span m="1459860">be</span></p><p><span
  m="1460010">zero.</span> <span m="1460940">But</span> <span m="1461740">then</span>
  <span m="1461970">you</span> <span m="1462100">didn't</span> <span m="1462450">know</span>
  <span m="1462890">if</span> <span m="1463030">you</span> <span m="1463130">had</span>
  <span m="1463320">a</span> <span m="1463380">minimum</span> <span m="1463880">or</span>
  <span m="1464040">a</span> <span m="1464070">maximum.</span></p><p><span m="1465890">To</span>
  <span m="1466060">know</span> <span m="1466340">that</span> <span m="1466490">you</span>
  <span m="1466580">had</span> <span m="1466790">a</span> <span m="1466850">minimum,</span>
  <span m="1467400">you</span> <span m="1467500">had</span> <span m="1467710">to</span>
  <span m="1467820">look</span> <span m="1468080">at</span> <span m="1468190">the</span>
  <span m="1468310">second</span> <span m="1468750">derivative.</span></p><p><span
  m="1470300">The</span> <span m="1470460">second</span> <span m="1470880">derivative</span>
  <span m="1471360">had</span> <span m="1471620">to</span> <span m="1471680">be</span>
  <span m="1471890">positive,</span> <span m="1473400">the</span> <span m="1474420">slope</span>
  <span m="1475070">had</span> <span m="1475340">to</span> <span m="1475440">be</span>
  <span m="1475740">increasing</span> <span m="1476590">as</span> <span m="1476770">you</span>
  <span m="1476900">went</span> <span m="1477170">through</span> <span m="1477480">the</span>
  <span m="1477950">minimum</span> <span m="1478440">point.</span></p><p><span m="1480010">The</span>
  <span m="1480210">curvature</span> <span m="1480830">had</span> <span m="1480990">to</span>
  <span m="1481040">go</span> <span m="1481280">upwards,</span> <span m="1482360">and</span>
  <span m="1483000">that's</span> <span m="1483470">what</span> <span m="1483730">we're</span>
  <span m="1483890">doing</span> <span m="1484260">now</span> <span m="1484740">in</span>
  <span m="1485290">two</span> <span m="1485600">dimensions,</span> <span m="1486910">and</span>
  <span m="1487580">in</span> <span m="1487800">n</span> <span m="1488070">dimensions.</span></p><p><span
  m="1489280">So</span> <span m="1489410">we're</span> <span m="1489530">doing</span>
  <span m="1489910">what</span> <span m="1490080">we</span> <span m="1490210">did</span>
  <span m="1490410">in</span> <span m="1490580">Calculus.</span></p><p><span m="1492030">Second</span>
  <span m="1492530">derivative</span> <span m="1493150">positive,</span> <span m="1494230">m-</span>
  <span m="1494560">will</span> <span m="1494880">now</span> <span m="1495150">become</span>
  <span m="1496120">that</span> <span m="1496510">the</span> <span m="1496620">matrix</span>
  <span m="1497350">of</span> <span m="1497480">second</span> <span m="1497870">derivatives</span>
  <span m="1498590">is</span> <span m="1498920">positive</span> <span m="1499520">definite.</span></p><p><span
  m="1500810">Can</span> <span m="1501000">I</span> <span m="1501110">just</span>
  <span m="1501610">--</span> <span m="1502650">like</span> <span m="1502930">a</span>
  <span m="1503050">translation</span> <span m="1504120">of</span> <span m="1504510">--</span>
  <span m="1505670">this</span> <span m="1505950">is</span> <span m="1506140">how</span>
  <span m="1506240">minimum</span> <span m="1506720">are</span> <span m="1506810">coming</span>
  <span m="1507940">in,</span> <span m="1509400">ithe</span> <span m="1510150">beginning</span>
  <span m="1510770">of</span> <span m="1510900">Calculus</span> <span m="1511890">--</span>
  <span m="1514640">we</span> <span m="1514770">had</span> <span m="1514950">a</span>
  <span m="1515010">minimum</span> <span m="1516690">was</span> <span m="1517490">associated</span>
  <span m="1518340">with</span> <span m="1518990">second</span> <span m="1519590">derivative,</span>
  <span m="1522730">being</span> <span m="1523050">positive.</span></p><p><span m="1524170">And</span>
  <span m="1524550">first</span> <span m="1524870">derivative</span> <span m="1525320">zero,</span>
  <span m="1525720">of</span> <span m="1525830">course.</span></p><p><span m="1527340">Derivative,</span>
  <span m="1528360">first</span> <span m="1529130">derivative,</span> <span m="1535840">but</span>
  <span m="1536030">it</span> <span m="1536120">was</span> <span m="1536330">the</span>
  <span m="1536460">second</span> <span m="1536930">derivative</span> <span m="1537440">that</span>
  <span m="1537690">told</span> <span m="1538060">us</span> <span m="1538220">we</span>
  <span m="1538350">had</span> <span m="1538540">a</span> <span m="1538600">minimum.</span></p><p><span
  m="1539870">And</span> <span m="1540090">now,</span> <span m="1540680">in</span>
  <span m="1540970">18.06,</span> <span m="1541960">in</span> <span m="1542100">linear</span>
  <span m="1542430">algebra,</span> <span m="1543510">we'll</span> <span m="1544660">have</span>
  <span m="1545660">a</span> <span m="1545820">minim</span> <span m="1546150">for</span>
  <span m="1546430">our</span> <span m="1546710">function</span> <span m="1546990">now,</span>
  <span m="1547260">our</span> <span m="1547540">function</span> <span m="1547820">will</span>
  <span m="1548100">have,</span> <span m="1548380">for</span> <span m="1548690">your</span>
  <span m="1549410">function</span> <span m="1550140">be</span> <span m="1550860">a</span>
  <span m="1551590">function</span> <span m="1552310">not</span> <span m="1553040">of</span>
  <span m="1553760">just</span> <span m="1554490">x</span> <span m="1555210">but</span>
  <span m="1555940">several</span> <span m="1556660">variables,</span> <span m="1557390">the</span>
  <span m="1558110">way</span> <span m="1558840">functions</span> <span m="1559560">really</span>
  <span m="1560290">are</span> <span m="1561020">in</span> <span m="1561050">real</span>
  <span m="1561320">life,</span> <span m="1561980">the</span> <span m="1562540">minimum</span>
  <span m="1563150">will</span> <span m="1563370">be</span> <span m="1564410">when</span>
  <span m="1565330">the</span> <span m="1566070">matrix</span> <span m="1568800">of</span>
  <span m="1570470">second</span> <span m="1571800">derivatives,</span> <span m="1574610">the</span>
  <span m="1574720">matrix</span> <span m="1575140">here</span> <span m="1575310">was</span>
  <span m="1575460">one</span> <span m="1575690">by</span> <span m="1575850">one,</span>
  <span m="1576110">there</span> <span m="1576190">was</span> <span m="1576330">just</span>
  <span m="1576520">one</span> <span m="1576780">second</span> <span m="1577130">derivative,</span>
  <span m="1577590">now</span> <span m="1578040">we've</span> <span m="1578320">got</span>
  <span m="1578690">lots.</span></p><p><span m="1580560">Is</span> <span m="1583440">positive</span>
  <span m="1584870">definite.</span></p><p><span m="1589070">So</span> <span m="1589260">positive</span>
  <span m="1589980">for</span> <span m="1590170">a</span> <span m="1590250">number</span>
  <span m="1590780">translates</span> <span m="1591450">into</span> <span m="1591670">positive</span>
  <span m="1592360">definite</span> <span m="1592910">for</span> <span m="1593130">a</span>
  <span m="1593190">matrix.</span></p><p><span m="1594450">And</span> <span m="1594880">it</span>
  <span m="1595050">this</span> <span m="1595320">brings</span> <span m="1595650">everything</span>
  <span m="1596900">you</span> <span m="1597840">check</span> <span m="1598330">pivots,</span>
  <span m="1598860">you</span> <span m="1599000">check</span> <span m="1599320">determinants,</span>
  <span m="1600050">you</span> <span m="1600160">check</span> <span m="1600510">all</span>
  <span m="1600630">your</span> <span m="1600870">values,</span> <span m="1601680">or</span>
  <span m="1602260">you</span> <span m="1602530">check</span> <span m="1603190">this</span>
  <span m="1603550">minimum</span> <span m="1604120">stuff.</span></p><p><span m="1605060">OK.</span>
  <span m="1605410">Let</span> <span m="1605550">me</span> <span m="1605680">come</span>
  <span m="1605870">back</span> <span m="1606120">to</span> <span m="1606220">this</span>
  <span m="1606480">graph.</span></p><p><span m="1609190">That</span> <span m="1609530">graph</span>
  <span m="1609930">goes</span> <span m="1610210">upwards.</span></p><p><span m="1613220">And</span>
  <span m="1613430">I'll</span> <span m="1613510">have</span> <span m="1613670">to</span>
  <span m="1613800">see</span> <span m="1614010">why.</span></p><p><span m="1614740">How</span>
  <span m="1614960">do</span> <span m="1615110">I</span> <span m="1615250">know</span>
  <span m="1616020">that</span> <span m="1616480">this,</span> <span m="1616880">that</span>
  <span m="1617140">this</span> <span m="1617380">function</span> <span m="1617840">is</span>
  <span m="1617970">always</span> <span m="1618360">positive?</span></p><p><span m="1619980">Can</span>
  <span m="1620140">you</span> <span m="1620310">look</span> <span m="1620520">at</span>
  <span m="1620620">that</span> <span m="1620880">and</span> <span m="1621060">tell</span>
  <span m="1621350">that</span> <span m="1621470">it's</span> <span m="1621650">always</span>
  <span m="1622020">positive?</span></p><p><span m="1624770">Maybe</span> <span m="1625210">two</span>
  <span m="1625430">by</span> <span m="1625670">two,</span> <span m="1626390">you</span>
  <span m="1626660">could</span> <span m="1627300">feel</span> <span m="1627880">pretty</span>
  <span m="1628280">sure,</span> <span m="1628710">but</span> <span m="1629280">what's</span>
  <span m="1629670">the</span> <span m="1629810">good</span> <span m="1630110">way</span>
  <span m="1630400">to</span> <span m="1630520">show</span> <span m="1631000">that</span>
  <span m="1631200">this</span> <span m="1631440">thing</span> <span m="1631660">is</span>
  <span m="1631800">always</span></p><p><span m="1634530">If</span> <span m="1634880">we</span>
  <span m="1635100">can</span> <span m="1635350">express</span> <span m="1635910">it,</span>
  <span m="1637100">as,</span> <span m="1638600">in</span> <span m="1638900">terms</span>
  <span m="1639200">of</span> <span m="1639330">squares,</span> <span m="1640110">positive?</span>
  <span m="1640630">because</span> <span m="1641410">that's</span> <span m="1641760">what</span>
  <span m="1641940">we</span> <span m="1642100">know</span> <span m="1642470">for</span>
  <span m="1642700">any</span> <span m="1643030">x</span> <span m="1643330">and</span>
  <span m="1643570">y,</span> <span m="1644010">whatever,</span> <span m="1644950">if</span>
  <span m="1645340">we're</span> <span m="1645510">squaring</span> <span m="1646170">something</span>
  <span m="1646760">we</span> <span m="1646940">certainly</span> <span m="1647430">are</span>
  <span m="1647550">not</span> <span m="1647840">negative.</span></p><p><span m="1649470">So</span>
  <span m="1649690">I</span> <span m="1649910">believe</span> <span m="1650370">that</span>
  <span m="1650570">this</span> <span m="1650820">expression,</span> <span m="1651520">this</span>
  <span m="1651780">function,</span> <span m="1652690">could</span> <span m="1653290">be</span>
  <span m="1653470">written</span> <span m="1654220">as</span> <span m="1654750">a</span>
  <span m="1654840">sum</span> <span m="1655150">of</span> <span m="1655270">squares.</span></p><p><span
  m="1657190">Can</span> <span m="1657600">you</span> <span m="1657920">tell</span>
  <span m="1658170">me</span> <span m="1658650">--</span> <span m="1661170">see,</span>
  <span m="1661420">because</span> <span m="1661770">all</span> <span m="1661960">the</span>
  <span m="1662050">problems,</span> <span m="1662620">the</span> <span m="1663060">headaches</span>
  <span m="1663460">are</span> <span m="1663550">coming</span> <span m="1663860">from</span>
  <span m="1664020">this</span> <span m="1664330">xy</span> <span m="1664700">term.</span></p><p><span
  m="1667230">If</span> <span m="1667450">we</span> <span m="1667650">can</span> <span
  m="1667830">get</span> <span m="1668240">expressions</span> <span m="1668980">--</span>
  <span m="1669000">if</span> <span m="1669090">we</span> <span m="1669210">can</span>
  <span m="1669300">get</span> <span m="1669540">that</span> <span m="1669940">inside</span>
  <span m="1670500">a</span> <span m="1670580">square,</span> <span m="1671610">so</span>
  <span m="1672100">actually,</span> <span m="1672410">what</span> <span m="1672740">we're</span>
  <span m="1672860">doing</span> <span m="1673100">is</span> <span m="1673180">something</span>
  <span m="1673660">called,</span> <span m="1674350">that</span> <span m="1674630">you've</span>
  <span m="1674820">seen</span> <span m="1675120">called</span> <span m="1675460">completing</span>
  <span m="1676210">the</span> <span m="1676350">square.</span></p><p><span m="1678160">Let</span>
  <span m="1678750">me</span> <span m="1678890">start</span> <span m="1679310">the</span>
  <span m="1679430">square</span> <span m="1679800">and</span> <span m="1679880">you</span>
  <span m="1680020">complete</span> <span m="1680510">it.</span></p><p><span m="1681210">OK,</span>
  <span m="1681620">I</span> <span m="1681830">think</span> <span m="1682090">we</span>
  <span m="1682190">have</span> <span m="1682460">two</span> <span m="1683140">of</span>
  <span m="1684090">x</span> <span m="1685010">plus,</span> <span m="1685820">now</span>
  <span m="1686170">I</span> <span m="1686590">don't</span> <span m="1686890">remember</span>
  <span m="1687030">how</span> <span m="1687160">many</span> <span m="1687380">y-s</span>
  <span m="1687950">we</span> <span m="1688140">need,</span> <span m="1688630">but</span>
  <span m="1688900">you'll</span> <span m="1689400">figure</span> <span m="1689750">it</span>
  <span m="1689830">out,</span> <span m="1690260">squared.</span></p><p><span m="1693750">How</span>
  <span m="1693940">many</span> <span m="1694230">y-s</span> <span m="1694870">should</span>
  <span m="1695100">I</span> <span m="1695210">put</span> <span m="1695630">in</span>
  <span m="1695890">here,</span> <span m="1699620">to</span> <span m="1699730">make</span>
  <span m="1700400">--</span> <span m="1700470">what</span> <span m="1700700">do</span>
  <span m="1700810">I</span> <span m="1700900">want</span> <span m="1701130">to</span>
  <span m="1701180">do,</span> <span m="1701440">the</span> <span m="1701620">two</span>
  <span m="1702130">x</span> <span m="1702520">squared-s</span> <span m="1703060">will</span>
  <span m="1703260">be</span> <span m="1703520">correct,</span> <span m="1703950">right?</span></p><p><span
  m="1705770">What</span> <span m="1706280">I</span> <span m="1706370">want</span>
  <span m="1706610">to</span> <span m="1706670">do</span> <span m="1706860">is</span>
  <span m="1707020">put</span> <span m="1707270">in</span> <span m="1707440">the</span>
  <span m="1707540">right</span> <span m="1707890">number</span> <span m="1708210">of</span>
  <span m="1708280">y-s</span> <span m="1708990">to</span> <span m="1709110">get</span>
  <span m="1709380">the</span> <span m="1709500">twelve</span> <span m="1710080">xy</span>
  <span m="1710560">correct.</span></p><p><span m="1713270">And</span> <span m="1713550">what</span>
  <span m="1713790">is</span> <span m="1713950">that</span> <span m="1714160">number</span>
  <span m="1714480">of</span> <span m="1714560">y-s?</span> <span m="1717430">Let's</span>
  <span m="1717610">see,</span> <span m="1717870">I've</span> <span m="1717990">got</span>
  <span m="1718220">two</span> <span m="1718630">times,</span> <span m="1718950">and</span>
  <span m="1719060">so</span> <span m="1719170">I</span> <span m="1719270">really</span>
  <span m="1719630">want</span> <span m="1719900">six</span> <span m="1720330">xy-s</span>
  <span m="1720800">to</span> <span m="1721100">come</span> <span m="1721330">out</span>
  <span m="1721490">of</span> <span m="1721540">here,</span> <span m="1721770">I</span>
  <span m="1721850">think</span> <span m="1722080">maybe</span> <span m="1722420">if</span>
  <span m="1722600">I</span> <span m="1722690">put</span> <span m="1723120">three</span>
  <span m="1723490">there,</span> <span m="1724650">does</span> <span m="1725260">that</span>
  <span m="1725430">look</span> <span m="1725570">right</span> <span m="1725820">to</span>
  <span m="1725920">you?</span></p><p><span m="1728590">I</span> <span m="1728790">have</span>
  <span m="1729260">two-</span> <span m="1730270">this</span> <span m="1730740">is,</span>
  <span m="1731180">we</span> <span m="1731380">can</span> <span m="1731780">mentally,</span>
  <span m="1732530">multiply</span> <span m="1733560">out,</span> <span m="1733940">that's</span>
  <span m="1734250">X</span> <span m="1734550">squared,</span> <span m="1734980">that's</span>
  <span m="1735250">right,</span> <span m="1735950">that's</span> <span m="1736420">six</span>
  <span m="1736730">X</span> <span m="1737010">Y,</span> <span m="1737660">times</span>
  <span m="1738040">the</span> <span m="1738150">two</span> <span m="1738480">gives</span>
  <span m="1738820">from,</span> <span m="1739150">right,</span> <span m="1739580">and</span>
  <span m="1739840">how</span> <span m="1739990">many</span> <span m="1740210">Y</span>
  <span m="1740480">squareds</span> <span m="1740850">have</span> <span m="1740990">I</span>
  <span m="1741120">now</span> <span m="1741410">got?</span></p><p><span m="1742660">How</span>
  <span m="1742720">many</span> <span m="1742920">Y</span> <span m="1743150">squareds</span>
  <span m="1743520">have</span> <span m="1743660">I</span> <span m="1743740">now</span>
  <span m="1743840">got</span> <span m="1744090">from</span> <span m="1744280">this</span>
  <span m="1744530">term?</span></p><p><span m="1745950">Eighteen.</span></p><p><span
  m="1747750">Eighteen</span> <span m="1748260">was</span> <span m="1748450">the</span>
  <span m="1748560">key</span> <span m="1748810">number,</span> <span m="1749140">remember?</span></p><p><span
  m="1752000">Now</span> <span m="1752290">if</span> <span m="1752440">I</span> <span
  m="1752540">want</span> <span m="1752770">to</span> <span m="1752810">make</span>
  <span m="1753040">it</span> <span m="1753170">twenty,</span> <span m="1754100">then</span>
  <span m="1754580">I've</span> <span m="1754760">got</span> <span m="1755430">two</span>
  <span m="1755790">left.</span></p><p><span m="1756630">Two</span> <span m="1756890">y</span>
  <span m="1757150">squared-s.</span> <span m="1758100">That's</span> <span m="1758740">completing</span>
  <span m="1759230">the</span> <span m="1759370">square,</span> <span m="1764140">and</span>
  <span m="1765350">it's,</span> <span m="1765460">now</span> <span m="1765660">I</span>
  <span m="1765740">can</span> <span m="1765940">see</span> <span m="1766240">that</span>
  <span m="1766700">that</span> <span m="1767010">function</span> <span m="1767420">is</span>
  <span m="1767600">positive,</span> <span m="1768120">because</span> <span m="1768530">it's</span>
  <span m="1769090">all</span> <span m="1769710">squares.</span></p><p><span m="1773340">I've</span>
  <span m="1773550">got</span> <span m="1773770">two</span> <span m="1773990">squares,</span>
  <span m="1774880">added</span> <span m="1775260">together,</span> <span m="1775840">I</span>
  <span m="1775920">couldn't</span> <span m="1776300">go</span> <span m="1776440">negative.</span></p><p><span
  m="1778110">What</span> <span m="1778460">if</span> <span m="1778780">I</span> <span
  m="1778910">went</span> <span m="1779180">back</span> <span m="1779450">to</span>
  <span m="1779550">that</span> <span m="1779800">seven?</span></p><p><span m="1782070">If</span>
  <span m="1782290">instead</span> <span m="1782690">of</span> <span m="1782830">twenty</span>
  <span m="1783470">that</span> <span m="1783680">number</span> <span m="1783990">was</span>
  <span m="1784190">a</span> <span m="1784280">seven,</span> <span m="1784800">then</span>
  <span m="1785080">what</span> <span m="1785320">would</span> <span m="1785460">happen?</span></p><p><span
  m="1787610">This</span> <span m="1787900">would</span> <span m="1788110">still</span>
  <span m="1788400">be</span> <span m="1788560">correct,</span> <span m="1789110">I'd</span>
  <span m="1789290">still</span> <span m="1789550">have</span> <span m="1789700">this</span>
  <span m="1789990">square,</span> <span m="1791010">to</span> <span m="1791410">get</span>
  <span m="1791670">the</span> <span m="1791790">two</span> <span m="1792030">x</span>
  <span m="1792210">squared</span> <span m="1792560">and</span> <span m="1792660">the</span>
  <span m="1792770">twelve</span> <span m="1793170">xy,</span> <span m="1793670">and</span>
  <span m="1794210">I'd</span> <span m="1794370">have</span> <span m="1794530">eighteen</span>
  <span m="1795080">y</span> <span m="1795410">squared</span> <span m="1795840">and</span>
  <span m="1795970">then</span> <span m="1796200">what</span> <span m="1796380">would</span>
  <span m="1796550">I</span> <span m="1796630">do</span> <span m="1796900">here?</span></p><p><span
  m="1798800">I'd</span> <span m="1799010">have</span> <span m="1799220">to</span>
  <span m="1799350">remove</span> <span m="1800160">eleven</span> <span m="1801760">y</span>
  <span m="1802790">squared-s,</span> <span m="1803270">right,</span> <span m="1803760">if</span>
  <span m="1804090">I</span> <span m="1804210">only</span> <span m="1804450">had</span>
  <span m="1804640">a</span> <span m="1804730">seven</span> <span m="1805210">here,</span>
  <span m="1806730">then</span> <span m="1807570">instead</span> <span m="1808020">of</span>
  <span m="1808170">--</span> <span m="1808200">when</span> <span m="1808500">I</span>
  <span m="1808570">had</span> <span m="1808730">a</span> <span m="1808830">twenty</span>
  <span m="1809520">I</span> <span m="1809780">had</span> <span m="1809960">two</span>
  <span m="1810150">more</span> <span m="1810910">to</span> <span m="1811320">put</span>
  <span m="1811540">in,</span> <span m="1812200">when</span> <span m="1812760">I</span>
  <span m="1812840">had</span> <span m="1813040">an</span> <span m="1813170">eighteen,</span>
  <span m="1814070">which</span> <span m="1814430">was</span> <span m="1814640">the</span>
  <span m="1814750">marginal</span> <span m="1815410">case,</span> <span m="1816740">I</span>
  <span m="1817490">had</span> <span m="1817710">no</span> <span m="1817880">more</span>
  <span m="1818090">to</span> <span m="1818180">put</span> <span m="1818800">in.</span></p><p><span
  m="1819780">When</span> <span m="1819980">I</span> <span m="1820080">had</span>
  <span m="1820250">a</span> <span m="1820320">seven,</span> <span m="1820920">which</span>
  <span m="1821130">was</span> <span m="1821350">the</span> <span m="1821610">case</span>
  <span m="1822290">below</span> <span m="1822840">zero,</span> <span m="1823370">the</span>
  <span m="1824680">indefinite</span> <span m="1825670">case,</span> <span m="1826470">I</span>
  <span m="1826900">had</span> <span m="1827300">minus</span> <span m="1827760">eleven.</span></p><p><span
  m="1829870">Now,</span> <span m="1830760">so,</span> <span m="1831860">you</span>
  <span m="1832530">can</span> <span m="1832710">see</span> <span m="1833060">now,</span>
  <span m="1833330">that</span> <span m="1833520">this</span> <span m="1834180">thing</span>
  <span m="1834610">is</span> <span m="1835530">a</span> <span m="1835660">bowl.</span></p><p><span
  m="1836390">OK.</span></p><p><span m="1836860">It's</span> <span m="1837090">going</span>
  <span m="1837370">upwards,</span> <span m="1838380">if</span> <span m="1838860">I</span>
  <span m="1838960">cut</span> <span m="1839360">it</span> <span m="1839660">at</span>
  <span m="1840010">a</span> <span m="1840060">plane,</span> <span m="1840880">z</span>
  <span m="1841300">equal</span> <span m="1841550">to</span> <span m="1841630">one,</span>
  <span m="1842200">say,</span> <span m="1842970">I</span> <span m="1843300">would</span>
  <span m="1843520">get,</span> <span m="1844610">I</span> <span m="1845310">would</span>
  <span m="1845490">get</span> <span m="1846050">a</span> <span m="1846310">curve,</span>
  <span m="1846970">what</span> <span m="1847680">would</span> <span m="1847830">be</span>
  <span m="1847990">the</span> <span m="1848160">equation</span> <span m="1848740">for</span>
  <span m="1848860">that</span> <span m="1849200">curve?</span></p><p><span m="1850280">If</span>
  <span m="1850480">I</span> <span m="1850570">cut</span> <span m="1850860">it</span>
  <span m="1851010">at</span> <span m="1851450">height</span> <span m="1851720">one,</span>
  <span m="1852480">the</span> <span m="1852670">equation</span> <span m="1853190">would</span>
  <span m="1853400">be</span> <span m="1853620">this</span> <span m="1853870">thing</span>
  <span m="1854070">equal</span> <span m="1854340">to</span> <span m="1854430">one.</span></p><p><span
  m="1856980">And</span> <span m="1857310">that</span> <span m="1857690">curve</span>
  <span m="1858020">would</span> <span m="1858260">be</span> <span m="1858490">an</span>
  <span m="1858600">ellipse.</span></p><p><span m="1859910">So</span> <span m="1860220">actually,</span>
  <span m="1860740">already,</span> <span m="1861490">I've</span> <span m="1861820">blocked</span>
  <span m="1862560">into</span> <span m="1863470">the</span> <span m="1863990">lecture,</span>
  <span m="1865470">the</span> <span m="1866350">different</span> <span m="1866790">pieces</span>
  <span m="1867270">that</span> <span m="1867450">we're</span> <span m="1867660">aiming</span>
  <span m="1868110">for.</span></p><p><span m="1869380">We're</span> <span m="1869600">aiming</span>
  <span m="1869900">for</span> <span m="1870040">the</span> <span m="1870220">tests,</span>
  <span m="1870980">which</span> <span m="1871250">this</span> <span m="1871530">passed;</span>
  <span m="1872620">we're</span> <span m="1873320">aiming</span> <span m="1873650">for</span>
  <span m="1873850">the</span> <span m="1874090">connection</span> <span m="1874710">to</span>
  <span m="1874880">a</span> <span m="1874950">minimum,</span> <span m="1876030">which</span>
  <span m="1876680">this</span> <span m="1877330">--</span> <span m="1877360">which</span>
  <span m="1877740">we</span> <span m="1877880">see</span> <span m="1878160">in</span>
  <span m="1878290">the</span> <span m="1878640">graph,</span> <span m="1879620">and</span>
  <span m="1880510">if</span> <span m="1880640">we</span> <span m="1880930">chop</span>
  <span m="1881340">it</span> <span m="1881540">up,</span> <span m="1882420">if</span>
  <span m="1882850">we</span> <span m="1882990">set</span> <span m="1883310">this</span>
  <span m="1883580">thing</span> <span m="1883770">equal</span> <span m="1884100">to</span>
  <span m="1884190">one,</span> <span m="1885180">if</span> <span m="1885670">I</span>
  <span m="1885770">set</span> <span m="1886060">that</span> <span m="1886260">thing</span>
  <span m="1886450">equal</span> <span m="1886740">to</span> <span m="1886820">one,</span>
  <span m="1887220">that</span> <span m="1887530">--</span> <span m="1887560">what</span>
  <span m="1887750">that</span> <span m="1887990">gives</span> <span m="1888260">me</span>
  <span m="1888440">is,</span> <span m="1889060">the</span> <span m="1889370">cross-section.</span>
  <span m="1890490">It</span> <span m="1890990">gives</span> <span m="1891230">me</span>
  <span m="1891460">this,</span> <span m="1893050">this</span> <span m="1894570">curve,</span>
  <span m="1896070">and</span> <span m="1896580">its</span> <span m="1897050">equation</span>
  <span m="1897750">is</span> <span m="1898110">this</span> <span m="1898400">thing</span>
  <span m="1898600">equals</span> <span m="1899030">one,</span> <span m="1899660">and</span>
  <span m="1899900">that's</span> <span m="1900180">an</span> <span m="1900270">ellipse.</span></p><p><span
  m="1901200">Whereas</span> <span m="1901730">if</span> <span m="1901920">I</span>
  <span m="1902050">cut</span> <span m="1902450">through</span> <span m="1903210">a</span>
  <span m="1903370">saddle</span> <span m="1903820">point,</span> <span m="1904660">I</span>
  <span m="1905050">get</span> <span m="1905270">a</span> <span m="1905310">hyperbola.</span></p><p><span
  m="1907900">But</span> <span m="1908370">this</span> <span m="1908830">minimum</span>
  <span m="1909560">stuff</span> <span m="1909970">is</span> <span m="1910380">really</span>
  <span m="1910770">what</span> <span m="1911060">I'm</span> <span m="1911680">most</span>
  <span m="1912390">interested</span></p><p><span m="1913820">OK.</span></p><p><span
  m="1914890">in.</span> <span m="1915110">OK.</span></p><p><span m="1915210">By</span>
  <span m="1915520">--</span> <span m="1915820">I</span> <span m="1915980">just</span>
  <span m="1916230">have</span> <span m="1916430">to</span> <span m="1916560">ask,</span>
  <span m="1917320">do</span> <span m="1917720">you</span> <span m="1917910">recognize,</span>
  <span m="1919510">I</span> <span m="1920060">mean,</span> <span m="1920300">these</span>
  <span m="1920620">numbers</span> <span m="1921150">here,</span> <span m="1921900">the</span>
  <span m="1922180">two</span> <span m="1923060">that</span> <span m="1923340">appeared</span>
  <span m="1923730">outside,</span> <span m="1924460">the</span> <span m="1924580">three</span>
  <span m="1925110">that</span> <span m="1925270">appeared</span> <span m="1925680">inside,</span>
  <span m="1926410">the</span> <span m="1926570">two</span> <span m="1926930">that</span>
  <span m="1927070">appeared</span> <span m="1927460">there</span> <span m="1927870">--</span>
  <span m="1928090">actually,</span> <span m="1929640">those</span> <span m="1930880">numbers</span>
  <span m="1931260">come</span> <span m="1931480">from</span> <span m="1931670">elimination.</span></p><p><span
  m="1933690">Completing</span> <span m="1934340">the</span> <span m="1934470">square</span>
  <span m="1935160">is</span> <span m="1936010">our</span> <span m="1936510">good</span>
  <span m="1936890">old</span> <span m="1937860">method</span> <span m="1938890">of</span>
  <span m="1939070">Gaussian</span> <span m="1939410">elimination,</span> <span m="1940580">in</span>
  <span m="1944320">expressed</span> <span m="1944910">in</span> <span m="1945010">terms</span>
  <span m="1945330">of</span> <span m="1945410">these</span> <span m="1945640">squares.</span></p><p><span
  m="1947280">The</span> <span m="1947930">--</span> <span m="1948910">let</span>
  <span m="1949030">me</span> <span m="1949140">show</span> <span m="1949350">you</span>
  <span m="1949470">what</span> <span m="1949620">I</span> <span m="1949720">mean.</span></p><p><span
  m="1950600">I</span> <span m="1951260">just</span> <span m="1951540">think</span>
  <span m="1951770">those</span> <span m="1952070">numbers</span> <span m="1952580">are</span>
  <span m="1952690">no</span> <span m="1952980">accident,</span> <span m="1954050">If</span>
  <span m="1954600">I</span> <span m="1954700">take</span> <span m="1955010">my</span>
  <span m="1955150">matrix</span> <span m="1956380">two,</span> <span m="1957280">six,</span>
  <span m="1957910">six,</span> <span m="1958340">and</span> <span m="1958440">twenty,</span>
  <span m="1960050">and</span> <span m="1961340">I</span> <span m="1961420">do</span>
  <span m="1961660">elimination,</span> <span m="1962690">then</span> <span m="1962910">the</span>
  <span m="1963020">pivot</span> <span m="1963440">is</span> <span m="1963730">two</span>
  <span m="1965050">and</span> <span m="1965930">I</span> <span m="1966030">take</span>
  <span m="1966560">three,</span> <span m="1967480">what's</span> <span m="1968010">the</span>
  <span m="1968110">multiplier?</span></p><p><span m="1970150">How</span> <span m="1970280">much</span>
  <span m="1970620">of</span> <span m="1970730">row</span> <span m="1971010">one</span>
  <span m="1971390">do</span> <span m="1971550">I</span> <span m="1971660">take</span>
  <span m="1971960">away</span> <span m="1972230">from</span> <span m="1972430">row</span>
  <span m="1972650">two?</span></p><p><span m="1974180">Three.</span></p><p><span
  m="1975360">So</span> <span m="1975570">what</span> <span m="1975900">you're</span>
  <span m="1976080">seeing</span> <span m="1976550">in</span> <span m="1976690">this,</span>
  <span m="1977100">completing</span> <span m="1977680">the</span> <span m="1977810">square,</span>
  <span m="1978700">is</span> <span m="1979210">the</span> <span m="1979310">pivots</span>
  <span m="1979850">outside</span> <span m="1981350">and</span> <span m="1982310">the</span>
  <span m="1982380">multiplier</span> <span m="1983410">inside.</span></p><p><span
  m="1985180">Just</span> <span m="1985490">do</span> <span m="1985640">that</span>
  <span m="1985890">again?</span></p><p><span m="1986680">The</span> <span m="1987170">pivot</span>
  <span m="1987580">is</span> <span m="1987840">two,</span> <span m="1989470">three</span>
  <span m="1990590">--</span> <span m="1990910">three</span> <span m="1991190">of</span>
  <span m="1991270">those</span> <span m="1991560">away</span> <span m="1991900">from</span>
  <span m="1992080">that</span> <span m="1992510">gives</span> <span m="1992840">me</span>
  <span m="1993220">two,</span> <span m="1993660">six,</span> <span m="1994670">zero,</span>
  <span m="1995510">and</span> <span m="1995640">what's</span> <span m="1995950">the</span>
  <span m="1996070">second</span> <span m="1996500">pivot?</span></p><p><span m="1998100">Three</span>
  <span m="1998540">of</span> <span m="1998630">this</span> <span m="1998920">away</span>
  <span m="1999210">from</span> <span m="1999380">this,</span> <span m="1999710">three</span>
  <span m="2000150">sixes'll</span> <span m="2000670">be</span> <span m="2000820">eighteen,</span>
  <span m="2001550">and</span> <span m="2001760">the</span> <span m="2001860">second</span>
  <span m="2002290">pivot</span> <span m="2002610">will</span> <span m="2002790">also</span>
  <span m="2003120">be</span> <span m="2003310">a</span></p><p><span m="2003380">two.</span>
  <span m="2004040">So</span> <span m="2004840">that's</span> <span m="2005620">the</span>
  <span m="2005770">U,</span> <span m="2006780">this</span> <span m="2007530">is</span>
  <span m="2007800">the</span> <span m="2008880">A,</span> <span m="2010340">and</span>
  <span m="2011230">of</span> <span m="2011360">course</span> <span m="2011730">the</span>
  <span m="2011890">L</span> <span m="2012490">was</span> <span m="2013590">one,</span>
  <span m="2014450">zero,</span> <span m="2015050">one,</span> <span m="2015560">and</span>
  <span m="2015870">the</span> <span m="2015950">multiplier</span> <span m="2016930">was</span>
  <span m="2017560">three.</span></p><p><span m="2020540">So,</span> <span m="2021830">completing</span>
  <span m="2023010">the</span> <span m="2023150">square</span> <span m="2024310">is</span>
  <span m="2025530">elimination.</span></p><p><span m="2028210">Why</span> <span m="2028890">I</span>
  <span m="2029250">happy</span> <span m="2029620">to</span> <span m="2029760">see,</span>
  <span m="2030680">happy</span> <span m="2031120">to</span> <span m="2031530">see</span>
  <span m="2031890">that</span> <span m="2032530">coming</span> <span m="2032910">together?</span></p><p><span
  m="2034230">Because</span> <span m="2034730">I</span> <span m="2034860">know</span>
  <span m="2035330">about</span> <span m="2036380">elimination</span> <span m="2037640">for</span>
  <span m="2038490">m</span> <span m="2038760">by</span> <span m="2038980">m</span>
  <span m="2039200">matrices.</span></p><p><span m="2041190">I</span> <span m="2041290">just</span>
  <span m="2041700">started</span> <span m="2042200">talking</span> <span m="2042520">about</span>
  <span m="2042830">completing</span> <span m="2043410">the</span> <span m="2043550">square,</span>
  <span m="2044070">here,</span> <span m="2047740">for</span> <span m="2047900">two</span>
  <span m="2048050">by</span> <span m="2048230">twos.</span></p><p><span m="2050320">But</span>
  <span m="2050600">now</span> <span m="2051070">I</span> <span m="2051219">see</span>
  <span m="2051570">what's</span> <span m="2051870">going</span> <span m="2052139">on.</span></p><p><span
  m="2052989">Completing</span> <span m="2053620">the</span> <span m="2053739">square</span>
  <span m="2054449">really</span> <span m="2054929">amounts</span> <span m="2055510">to</span>
  <span m="2056130">splitting</span> <span m="2056800">this</span> <span m="2057469">thing</span>
  <span m="2057909">into</span> <span m="2058159">a</span> <span m="2058260">sum</span>
  <span m="2058600">of</span> <span m="2058760">squares,</span> <span m="2059530">so</span>
  <span m="2059830">what's</span> <span m="2060230">the</span> <span m="2060400">critical</span>
  <span m="2060980">thing</span> <span m="2061320">--</span> <span m="2061610">I</span>
  <span m="2061710">have</span> <span m="2061900">a</span> <span m="2061980">lot</span>
  <span m="2062260">of</span> <span m="2062330">squares,</span> <span m="2063570">and</span>
  <span m="2064270">inside</span> <span m="2064780">those</span> <span m="2064969">squares</span>
  <span m="2065380">are</span> <span m="2065469">multipliers</span> <span m="2066290">but</span>
  <span m="2066520">they're</span> <span m="2066760">squares,</span> <span m="2068020">and</span>
  <span m="2068460">the</span> <span m="2068560">question</span> <span m="2069010">is,</span>
  <span m="2069489">what's</span> <span m="2069940">outside</span> <span m="2070610">these</span>
  <span m="2070940">squares?</span></p><p><span m="2071790">When</span> <span m="2071969">I</span>
  <span m="2072050">complete</span> <span m="2072550">the</span> <span m="2072690">square,</span>
  <span m="2073760">what</span> <span m="2074300">are</span> <span m="2074350">the</span>
  <span m="2074480">numbers</span> <span m="2074860">that</span> <span m="2075010">go</span></p><p><span
  m="2075210">outside?</span> <span m="2076179">They're</span> <span m="2076750">the</span>
  <span m="2076889">pivots.</span></p><p><span m="2079889">They're</span> <span m="2080100">the</span>
  <span m="2080230">pivots,</span> <span m="2080960">and</span> <span m="2081210">that's</span>
  <span m="2081620">why</span> <span m="2082600">positive</span> <span m="2083739">pivots</span>
  <span m="2084650">give</span> <span m="2084889">me</span> <span m="2085510">sum</span>
  <span m="2085860">of</span> <span m="2086000">squares.</span></p><p><span m="2087409">Positive</span>
  <span m="2087960">pivots,</span> <span m="2088850">those</span> <span m="2089139">pivots</span>
  <span m="2089590">are</span> <span m="2089679">the</span> <span m="2089840">numbers</span>
  <span m="2090270">that</span> <span m="2090420">go</span> <span m="2090639">outside</span>
  <span m="2091150">the</span> <span m="2091260">squares,</span> <span m="2092090">so</span>
  <span m="2092449">positive</span> <span m="2093040">pivots,</span> <span m="2093600">sum</span>
  <span m="2093840">of</span> <span m="2093980">squares,</span> <span m="2094860">everything</span>
  <span m="2095510">positive,</span> <span m="2096429">graph</span> <span m="2096860">goes</span>
  <span m="2097190">up,</span> <span m="2097850">a</span> <span m="2098190">minimum</span>
  <span m="2099250">at</span> <span m="2099750">the</span> <span m="2099900">origin,</span>
  <span m="2100790">it's</span> <span m="2101270">all</span> <span m="2101660">connected</span>
  <span m="2102170">together;</span> <span m="2103050">all</span> <span m="2103710">connected</span>
  <span m="2104180">together.</span></p><p><span m="2104710">And</span> <span m="2104950">in</span>
  <span m="2105070">the</span> <span m="2105200">two</span> <span m="2105380">by</span>
  <span m="2105570">two</span> <span m="2105800">case,</span> <span m="2106190">you</span>
  <span m="2106320">can</span> <span m="2106480">see</span> <span m="2106770">those</span>
  <span m="2107030">connections,</span> <span m="2108110">but</span> <span m="2108690">linear</span>
  <span m="2109100">algebra</span> <span m="2109580">now</span> <span m="2109940">can</span>
  <span m="2110160">go</span> <span m="2110420">up</span> <span m="2110790">to</span>
  <span m="2111550">three</span> <span m="2111960">by</span> <span m="2112140">three,</span>
  <span m="2112700">m</span> <span m="2112940">by</span> <span m="2113140">m.</span></p><p><span
  m="2116100">Let's</span> <span m="2116350">do</span> <span m="2116470">that</span>
  <span m="2116730">next.</span></p><p><span m="2117950">Can</span> <span m="2118070">I</span>
  <span m="2118180">just,</span> <span m="2118600">before</span> <span m="2118970">I</span>
  <span m="2119150">leave</span> <span m="2119350">two</span> <span m="2119550">by</span>
  <span m="2119780">two,</span> <span m="2120680">I've</span> <span m="2121260">written</span>
  <span m="2121510">this</span> <span m="2121750">expression</span> <span m="2122640">&quot;matrix</span>
  <span m="2123310">of</span> <span m="2123450">second</span> <span m="2123930">derivatives.&quot;</span>
  <span m="2124940">What's</span> <span m="2125600">the</span> <span m="2125730">matrix</span>
  <span m="2126270">of</span> <span m="2126400">second</span> <span m="2126780">derivatives?</span></p><p><span
  m="2129690">That's</span> <span m="2129920">one</span> <span m="2130270">second</span>
  <span m="2130650">derivative</span> <span m="2131130">now,</span> <span m="2131970">but</span>
  <span m="2132960">if</span> <span m="2133650">I'm</span> <span m="2133860">in</span>
  <span m="2134160">two</span> <span m="2134480">dimensions,</span> <span m="2137370">I</span>
  <span m="2137510">have</span> <span m="2137640">a</span> <span m="2137750">two</span>
  <span m="2137930">by</span> <span m="2138130">two</span> <span m="2138340">matrix,</span>
  <span m="2140020">it's</span> <span m="2141050">the</span> <span m="2141400">second</span>
  <span m="2141980">x</span> <span m="2142340">derivative,</span> <span m="2143860">the</span>
  <span m="2145020">second</span> <span m="2145390">x</span> <span m="2145680">derivative</span>
  <span m="2146200">goes</span> <span m="2146480">there</span> <span m="2147040">--</span>
  <span m="2149070">shall</span> <span m="2149300">I</span> <span m="2149370">write</span>
  <span m="2151920">it</span> <span m="2153180">--</span> <span m="2153580">fxx,</span>
  <span m="2154650">if</span> <span m="2154820">you</span> <span m="2154970">like,</span>
  <span m="2155350">fxx,</span> <span m="2156360">that</span> <span m="2156560">means</span>
  <span m="2156820">the</span> <span m="2156940">second</span> <span m="2157370">derivative</span>
  <span m="2157830">of</span> <span m="2157970">f</span> <span m="2158350">in</span>
  <span m="2158540">the</span> <span m="2158680">x</span> <span m="2158930">direction.</span>
  <span m="2160170">fyy,</span> <span m="2161970">second</span> <span m="2163090">derivative</span>
  <span m="2163530">in</span> <span m="2163650">the</span> <span m="2163740">y</span>
  <span m="2164010">direction.</span></p><p><span m="2164500">Those</span> <span m="2164730">are</span>
  <span m="2164770">the</span> <span m="2164910">pure</span> <span m="2165440">derivatives,</span>
  <span m="2166010">second</span> <span m="2166400">derivatives.</span></p><p><span
  m="2167970">They</span> <span m="2168110">have</span> <span m="2168400">to</span>
  <span m="2168520">be</span> <span m="2168710">positive.</span></p><p><span m="2170950">For</span>
  <span m="2171130">a</span> <span m="2171170">minimum.</span></p><p><span m="2173430">This</span>
  <span m="2173740">number</span> <span m="2174050">has</span> <span m="2174290">to</span>
  <span m="2174390">be</span> <span m="2174540">positive</span> <span m="2175030">for</span>
  <span m="2175150">a</span> <span m="2175190">minimum.</span></p><p><span m="2175590">That</span>
  <span m="2175850">number</span> <span m="2176100">has</span> <span m="2176330">to</span>
  <span m="2176410">be</span> <span m="2176550">positive</span> <span m="2177090">for</span>
  <span m="2177190">a</span> <span m="2177230">minimum.</span></p><p><span m="2177730">But,</span>
  <span m="2178540">that's</span> <span m="2178990">not</span> <span m="2179240">enough.</span></p><p><span
  m="2180410">Those</span> <span m="2180760">numbers</span> <span m="2181130">have</span>
  <span m="2181350">to</span> <span m="2181490">somehow</span> <span m="2182090">be</span>
  <span m="2182760">big</span> <span m="2183050">enough</span> <span m="2183680">to</span>
  <span m="2184480">overcome</span> <span m="2185650">this</span> <span m="2186180">cross-derivative,</span>
  <span m="2190090">Why</span> <span m="2190430">is</span> <span m="2190560">the</span>
  <span m="2190660">matrix</span> <span m="2191130">symmetric?</span></p><p><span
  m="2191780">Because</span> <span m="2192370">the</span> <span m="2192520">second</span>
  <span m="2192890">derivative</span> <span m="2193340">f</span> <span m="2193820">with</span>
  <span m="2194060">respect</span> <span m="2194400">to</span> <span m="2194480">x</span>
  <span m="2194750">and</span> <span m="2194930">y</span> <span m="2195470">is</span>
  <span m="2195730">equal</span> <span m="2196210">to</span> <span m="2196990">--</span>
  <span m="2197950">I</span> <span m="2198050">can,</span> <span m="2198530">that's</span>
  <span m="2199300">the</span> <span m="2199550">beautiful</span> <span m="2200340">fact</span>
  <span m="2200690">about</span> <span m="2200970">second</span> <span m="2201330">derivatives,</span>
  <span m="2201950">is</span> <span m="2202170">I</span> <span m="2202260">can</span>
  <span m="2202520">do</span> <span m="2202700">those</span> <span m="2202970">in</span>
  <span m="2203120">either</span> <span m="2203440">order</span> <span m="2204030">and</span>
  <span m="2204330">I</span> <span m="2204400">get</span> <span m="2204640">the</span>
  <span m="2204730">same</span> <span m="2205050">thing.</span></p><p><span m="2206480">So</span>
  <span m="2206680">this</span> <span m="2206950">is</span> <span m="2207120">the</span>
  <span m="2207230">same</span> <span m="2207590">as</span> <span m="2207710">that,</span>
  <span m="2208940">and</span> <span m="2211150">so,</span> <span m="2213160">that's</span>
  <span m="2214410">the</span> <span m="2214520">matrix</span> <span m="2215000">of</span>
  <span m="2215130">second</span> <span m="2215510">derivatives.</span></p><p><span
  m="2217300">And</span> <span m="2217640">the</span> <span m="2217770">test</span>
  <span m="2218220">is,</span> <span m="2218710">it</span> <span m="2218890">has</span>
  <span m="2219150">to</span> <span m="2219260">be</span> <span m="2219410">positive</span>
  <span m="2219950">definite.</span></p><p><span m="2221280">You</span> <span m="2221440">might</span>
  <span m="2221710">remember,</span> <span m="2222690">from,</span> <span m="2224610">tucked</span>
  <span m="2225290">in</span> <span m="2225510">somewhere</span> <span m="2225960">near</span>
  <span m="2226170">the</span> <span m="2226350">end</span> <span m="2226550">of</span>
  <span m="2226660">eighteen</span> <span m="2227070">o'</span> <span m="2227170">two</span>
  <span m="2227470">or</span> <span m="2227610">at</span> <span m="2227660">least</span>
  <span m="2227930">in</span> <span m="2228090">the</span> <span m="2228190">book,</span>
  <span m="2228990">was</span> <span m="2229630">the</span> <span m="2229740">condition</span>
  <span m="2230450">for</span> <span m="2230670">a</span> <span m="2230740">minimum,</span>
  <span m="2232150">For</span> <span m="2233090">a</span> <span m="2233150">function</span>
  <span m="2233590">of</span> <span m="2233700">two</span> <span m="2233870">variables.</span></p><p><span
  m="2235470">Let's</span> <span m="2235830">--</span> <span m="2235870">when</span>
  <span m="2236120">do</span> <span m="2236190">you</span> <span m="2236270">have</span>
  <span m="2236460">a</span> <span m="2236530">minimum?</span></p><p><span m="2237180">For</span>
  <span m="2237300">a</span> <span m="2237360">function</span> <span m="2237710">of</span>
  <span m="2237820">two</span> <span m="2237980">variables,</span> <span m="2238610">believe</span>
  <span m="2239170">me,</span> <span m="2239740">that's</span> <span m="2240820">what</span>
  <span m="2241050">Calculus</span> <span m="2241620">is</span> <span m="2241830">for.</span></p><p><span
  m="2244200">The</span> <span m="2244520">condition</span> <span m="2245010">is</span>
  <span m="2245200">first</span> <span m="2245900">derivatives</span> <span m="2246660">have</span>
  <span m="2246880">to</span> <span m="2246970">be</span> <span m="2247110">zero.</span></p><p><span
  m="2249270">And</span> <span m="2250470">the</span> <span m="2250960">matrix</span>
  <span m="2251530">of</span> <span m="2251660">second</span> <span m="2252080">derivatives</span>
  <span m="2252630">has</span> <span m="2252880">to</span> <span m="2252980">be</span>
  <span m="2253130">positive</span> <span m="2253630">definite.</span></p><p><span
  m="2255280">So</span> <span m="2255470">you</span> <span m="2255630">maybe</span>
  <span m="2255960">remember</span> <span m="2256500">there</span> <span m="2256630">was</span>
  <span m="2256850">an</span> <span m="2257070">fxx</span> <span m="2258000">times</span>
  <span m="2258310">an</span> <span m="2258760">fyy</span> <span m="2259430">that</span>
  <span m="2259650">had</span> <span m="2259900">to</span> <span m="2259970">be</span>
  <span m="2260160">bigger</span> <span m="2260540">than</span> <span m="2260720">an</span>
  <span m="2260880">an</span> <span m="2261000">fxy</span> <span m="2261690">squared,</span>
  <span m="2262610">that's</span> <span m="2263000">just</span> <span m="2263310">our</span>
  <span m="2263510">determinant,</span> <span m="2264590">two</span> <span m="2264930">by</span>
  <span m="2265120">two.</span></p><p><span m="2266630">But</span> <span m="2266880">now,</span>
  <span m="2267940">we</span> <span m="2268510">now</span> <span m="2268770">know</span>
  <span m="2269050">the</span> <span m="2269200">answer</span> <span m="2269670">for</span>
  <span m="2270060">three</span> <span m="2270360">by</span> <span m="2270580">three,</span>
  <span m="2271480">m</span> <span m="2271860">by</span> <span m="2272090">m,</span>
  <span m="2272740">because</span> <span m="2274090">we</span> <span m="2274420">can</span>
  <span m="2274680">do</span> <span m="2274840">elimination</span> <span m="2275650">by</span>
  <span m="2275770">m</span> <span m="2275930">by</span> <span m="2276100">m</span>
  <span m="2276280">matrices,</span> <span m="2277770">we</span> <span m="2278460">can</span>
  <span m="2278650">connect</span> <span m="2279090">eigenvalues</span> <span m="2280000">of</span>
  <span m="2280120">m</span> <span m="2280270">by</span> <span m="2280460">m</span>
  <span m="2280660">matrices,</span> <span m="2281660">we</span> <span m="2281830">can</span>
  <span m="2281940">do</span> <span m="2282090">sum</span> <span m="2282430">of</span>
  <span m="2282580">squares,</span> <span m="2283190">sum</span> <span m="2283430">of</span>
  <span m="2283610">m</span> <span m="2283970">squares</span> <span m="2284500">instead</span>
  <span m="2284870">of</span> <span m="2285000">only</span> <span m="2285520">two</span>
  <span m="2286070">squares;</span> <span m="2286940">and</span> <span m="2287390">so</span>
  <span m="2287550">let's</span> <span m="2287830">take</span> <span m="2288520">a,</span>
  <span m="2291370">let</span> <span m="2291470">me</span> <span m="2291600">go</span>
  <span m="2291820">over</span> <span m="2292030">here</span> <span m="2292270">to</span>
  <span m="2292370">do</span> <span m="2292570">a</span> <span m="2292620">three</span>
  <span m="2292960">by</span> <span m="2293210">three</span> <span m="2293540">example.</span></p><p><span
  m="2297110">So,</span> <span m="2297300">three</span> <span m="2297580">by</span>
  <span m="2297780">three</span> <span m="2298070">example.</span></p><p><span m="2303680">OK.</span>
  <span m="2307060">Oh,</span> <span m="2307390">let</span> <span m="2307920">me</span>
  <span m="2308630">--</span> <span m="2312980">shall</span> <span m="2313240">I</span>
  <span m="2313330">use</span> <span m="2313690">my</span> <span m="2313900">favorite</span>
  <span m="2314320">matrix?</span></p><p><span m="2317210">You've</span> <span m="2317490">seen</span>
  <span m="2317780">this</span> <span m="2318110">matrix</span> <span m="2318740">before.</span></p><p><span
  m="2325340">Yes,</span> <span m="2325770">let's</span> <span m="2326310">use</span>
  <span m="2326560">the</span> <span m="2326660">good</span> <span m="2326890">matrix,</span>
  <span m="2327530">four</span> <span m="2327790">by</span> <span m="2328050">one,</span>
  <span m="2328590">oops,</span> <span m="2329220">open.</span></p><p><span m="2336130">Is</span>
  <span m="2336300">that</span> <span m="2336510">matrix</span> <span m="2337010">positive</span>
  <span m="2337520">definite?</span></p><p><span m="2341300">What's</span> <span m="2341900">--</span>
  <span m="2342290">so</span> <span m="2342410">I'm</span> <span m="2342510">going</span>
  <span m="2342640">to</span> <span m="2342680">ask</span> <span m="2342980">questions</span>
  <span m="2343430">about</span> <span m="2343730">this</span> <span m="2343950">matrix,</span>
  <span m="2344440">is</span> <span m="2344620">it</span> <span m="2344780">positive</span>
  <span m="2345190">definite,</span> <span m="2345630">first</span> <span m="2345860">of</span>
  <span m="2345980">all?</span></p><p><span m="2348260">What's</span> <span m="2348570">the</span>
  <span m="2348690">function</span> <span m="2349440">associated</span> <span m="2350110">with</span>
  <span m="2350260">that</span> <span m="2350510">matrix,</span> <span m="2350970">what's</span>
  <span m="2351240">the</span> <span m="2351420">x</span> <span m="2351730">transpose</span>
  <span m="2352390">Ax?</span></p><p><span m="2356260">Is</span> <span m="2356550">--</span>
  <span m="2356830">do</span> <span m="2356930">we</span> <span m="2357040">have</span>
  <span m="2357220">a</span> <span m="2357300">minimum</span> <span m="2357810">for</span>
  <span m="2357940">that</span> <span m="2358240">function,</span></p><p><span m="2358860">at</span>
  <span m="2359560">zero?</span> <span m="2362460">And</span> <span m="2362870">then</span>
  <span m="2363200">even</span> <span m="2363490">what's</span> <span m="2363840">the</span>
  <span m="2363970">geometry?</span></p><p><span m="2365380">OK.</span> <span m="2366060">First</span>
  <span m="2366510">of</span> <span m="2366640">all,</span> <span m="2367470">is</span>
  <span m="2367880">the</span> <span m="2368000">matrix</span> <span m="2368510">positive</span>
  <span m="2368920">definite,</span> <span m="2369200">now</span> <span m="2369290">I've</span>
  <span m="2369440">given</span> <span m="2369730">you</span> <span m="2369870">the</span>
  <span m="2370010">numbers</span> <span m="2370540">there</span> <span m="2370860">so</span>
  <span m="2371960">you</span> <span m="2372570">can</span> <span m="2373030">take</span>
  <span m="2373460">the</span> <span m="2373520">determinants,</span> <span m="2374270">maybe</span>
  <span m="2374520">that's</span> <span m="2374760">the</span> <span m="2374870">quickest,</span>
  <span m="2375370">is</span> <span m="2375450">that</span> <span m="2375600">what</span>
  <span m="2375760">you</span> <span m="2375880">would</span> <span m="2376040">do</span>
  <span m="2376180">mentally,</span> <span m="2376910">if</span> <span m="2377340">I</span>
  <span m="2377450">give</span> <span m="2377660">you</span> <span m="2377750">all</span>
  <span m="2377790">a</span> <span m="2378060">matrix</span> <span m="2378710">on</span>
  <span m="2378870">a</span> <span m="2378970">quiz</span> <span m="2379350">and</span>
  <span m="2379470">say</span> <span m="2379660">is</span> <span m="2379820">it</span>
  <span m="2379970">positive</span> <span m="2380440">definite</span> <span m="2380990">or</span>
  <span m="2381250">not?</span></p><p><span m="2383010">I</span> <span m="2383230">would</span>
  <span m="2383510">take</span> <span m="2383890">that</span> <span m="2384160">determinant</span>
  <span m="2385030">and</span> <span m="2385520">I'd</span> <span m="2385710">give</span>
  <span m="2385860">the</span> <span m="2385980">answer</span> <span m="2386340">two.</span></p><p><span
  m="2387240">I</span> <span m="2387340">would</span> <span m="2387510">take</span>
  <span m="2387810">that</span> <span m="2388140">determinant</span> <span m="2388710">and</span>
  <span m="2389010">I</span> <span m="2389130">would</span> <span m="2389320">give</span>
  <span m="2389540">the</span> <span m="2389700">answer</span> <span m="2391760">for</span>
  <span m="2392800">that</span> <span m="2393090">two</span> <span m="2393230">by</span>
  <span m="2393420">two</span> <span m="2393690">determinant,</span> <span m="2395380">I'd</span>
  <span m="2396260">give</span> <span m="2396490">the</span> <span m="2396620">answer</span>
  <span m="2396950">three,</span> <span m="2397190">and</span> <span m="2397250">anybody</span>
  <span m="2397400">remember</span> <span m="2399730">the</span> <span m="2399770">answer</span>
  <span m="2400280">for</span> <span m="2400410">the</span> <span m="2401000">three</span>
  <span m="2401220">by</span> <span m="2401530">three</span> <span m="2401710">determinant?</span></p><p><span
  m="2404220">It</span> <span m="2404400">was</span> <span m="2404690">four,</span>
  <span m="2405300">you</span> <span m="2405520">remember</span> <span m="2405950">for</span>
  <span m="2406040">these</span> <span m="2406630">special</span> <span m="2407000">matrices,</span>
  <span m="2408220">when</span> <span m="2408760">we</span> <span m="2408890">do</span>
  <span m="2409100">determinants,</span> <span m="2410420">they</span> <span m="2410730">went</span>
  <span m="2411000">up</span> <span m="2411780">two,</span> <span m="2412420">three,</span>
  <span m="2412640">four,</span> <span m="2412920">five,</span> <span m="2413190">six,</span>
  <span m="2413500">they</span> <span m="2413630">just</span> <span m="2413890">went</span>
  <span m="2414090">up</span> <span m="2414520">linearly.</span></p><p><span m="2415950">So</span>
  <span m="2416180">that</span> <span m="2416470">matrix</span> <span m="2416620">has</span>
  <span m="2416680">--</span> <span m="2416710">the</span> <span m="2416740">determinants</span>
  <span m="2420590">are</span> <span m="2421290">two,</span> <span m="2422100">three,</span>
  <span m="2422940">and</span> <span m="2423320">four.</span></p><p><span m="2424750">Pivots.</span></p><p><span
  m="2427630">What</span> <span m="2427820">are</span> <span m="2427900">the</span>
  <span m="2428030">pivots</span> <span m="2428580">for</span> <span m="2428670">that</span>
  <span m="2428970">matrix?</span></p><p><span m="2431160">I'll</span> <span m="2431360">tell</span>
  <span m="2431610">you,</span> <span m="2431880">they're</span> <span m="2432440">--</span>
  <span m="2432470">the</span> <span m="2432610">first</span> <span m="2432850">pivot</span>
  <span m="2433220">is</span> <span m="2433520">two,</span> <span m="2434470">the</span>
  <span m="2435030">next</span> <span m="2435370">pivot</span> <span m="2435690">is</span>
  <span m="2436000">three</span> <span m="2436390">over</span> <span m="2436860">two,</span>
  <span m="2437520">the</span> <span m="2437800">next</span> <span m="2438120">pivot</span>
  <span m="2438450">is</span> <span m="2438700">four</span> <span m="2439020">over</span>
  <span m="2439240">three.</span></p><p><span m="2442590">Because,</span> <span m="2443600">the</span>
  <span m="2443990">product</span> <span m="2444470">of</span> <span m="2444620">the</span>
  <span m="2444790">pivots</span> <span m="2445170">has</span> <span m="2445390">to</span>
  <span m="2445440">give</span> <span m="2445640">me</span> <span m="2445780">those</span>
  <span m="2446200">determinants.</span></p><p><span m="2447550">The</span> <span
  m="2447650">product</span> <span m="2448060">of</span> <span m="2448230">these</span>
  <span m="2448550">two</span> <span m="2448680">pivots</span> <span m="2449130">gives</span>
  <span m="2449340">me</span> <span m="2449460">that</span> <span m="2449880">determinant;</span>
  <span m="2450370">the</span> <span m="2450470">product</span> <span m="2450850">of</span>
  <span m="2450980">all</span> <span m="2451250">the</span> <span m="2451320">pivots</span>
  <span m="2451760">gives</span> <span m="2452280">me</span> <span m="2452800">that</span>
  <span m="2453310">determinant.</span></p><p><span m="2453830">What</span> <span
  m="2454020">are</span> <span m="2454120">the</span> <span m="2454310">eigenvalues?</span></p><p><span
  m="2463020">Oh,</span> <span m="2463550">I</span> <span m="2463770">don't</span>
  <span m="2465320">know.</span></p><p><span m="2468600">The</span> <span m="2468960">eigenvalues</span>
  <span m="2470320">I've</span> <span m="2470590">got,</span> <span m="2471010">what</span>
  <span m="2471180">do</span> <span m="2471260">I</span> <span m="2471450">have</span>
  <span m="2471600">a</span> <span m="2471770">cubic</span> <span m="2472330">equation</span>
  <span m="2472840">--</span> <span m="2472860">a</span> <span m="2472960">degree</span>
  <span m="2473390">three</span> <span m="2473860">equation?</span></p><p><span m="2477230">There</span>
  <span m="2477430">are</span> <span m="2477470">three</span> <span m="2477880">eigenvalues</span>
  <span m="2478680">to</span> <span m="2478880">find.</span></p><p><span m="2483350">If</span>
  <span m="2483530">I</span> <span m="2483630">believe</span> <span m="2484090">what</span>
  <span m="2484260">I've</span> <span m="2484470">said</span> <span m="2484780">today,</span>
  <span m="2485200">what</span> <span m="2485440">do</span> <span m="2485570">I</span>
  <span m="2485680">know</span> <span m="2485880">about</span> <span m="2486180">these</span>
  <span m="2486410">eigenvalues,</span> <span m="2487800">even</span> <span m="2488410">though</span>
  <span m="2488530">I</span> <span m="2488630">don't</span> <span m="2488930">know</span>
  <span m="2489140">the</span> <span m="2489330">exact</span> <span m="2489780">numbers.</span></p><p><span
  m="2490710">I</span> <span m="2490850">--</span> <span m="2491080">I</span> <span
  m="2493420">remember</span> <span m="2493960">the</span> <span m="2494160">numbers.</span></p><p><span
  m="2497100">Because</span> <span m="2497450">these</span> <span m="2497650">matrices</span>
  <span m="2498690">are</span> <span m="2498960">so</span> <span m="2499250">important</span>
  <span m="2499740">that</span> <span m="2499920">people</span> <span m="2500620">figure</span>
  <span m="2501190">them.</span></p><p><span m="2503750">But</span> <span m="2503940">--</span>
  <span m="2504640">what</span> <span m="2505360">do</span> <span m="2505420">you</span>
  <span m="2505540">believe</span> <span m="2505990">to</span> <span m="2506080">be</span>
  <span m="2506250">true</span> <span m="2506570">about</span> <span m="2506890">these</span>
  <span m="2507150">three</span> <span m="2507440">eigenvalues</span> <span m="2508400">--</span>
  <span m="2508430">you</span> <span m="2508570">believe</span> <span m="2509050">that</span>
  <span m="2509250">they</span> <span m="2509480">are</span> <span m="2509810">all</span>
  <span m="2511280">positive.</span></p><p><span m="2512950">They're</span> <span
  m="2513140">all</span> <span m="2513340">positive.</span></p><p><span m="2514270">I</span>
  <span m="2514450">think</span> <span m="2515190">that</span> <span m="2515750">they</span>
  <span m="2516000">are</span> <span m="2517090">two</span> <span m="2517540">minus</span>
  <span m="2518040">square</span> <span m="2518340">root</span> <span m="2518470">of</span>
  <span m="2518640">two,</span> <span m="2519720">two,</span> <span m="2520910">and</span>
  <span m="2521150">two</span> <span m="2521410">plus</span> <span m="2521790">the</span>
  <span m="2521900">square</span> <span m="2522220">root</span> <span m="2522290">of</span>
  <span m="2522340">two.</span></p><p><span m="2522630">I</span> <span m="2522810">think.</span></p><p><span
  m="2523720">Let</span> <span m="2523990">me</span> <span m="2524120">just</span>
  <span m="2524510">--</span> <span m="2525490">I</span> <span m="2525560">can't</span>
  <span m="2525890">write</span> <span m="2526100">those</span> <span m="2526310">numbers</span>
  <span m="2526690">down</span> <span m="2527190">without</span> <span m="2527720">checking</span>
  <span m="2528280">the</span> <span m="2528460">simple</span> <span m="2528930">checks,</span>
  <span m="2529420">what</span> <span m="2529730">the</span> <span m="2529820">first</span>
  <span m="2530110">simple</span> <span m="2530420">check</span> <span m="2530710">is</span>
  <span m="2530870">the</span> <span m="2531000">trace,</span> <span m="2532180">so</span>
  <span m="2532780">if</span> <span m="2532880">I</span> <span m="2533010">add</span>
  <span m="2533350">those</span> <span m="2533640">numbers</span> <span m="2534130">I</span>
  <span m="2534230">get</span> <span m="2534550">six</span> <span m="2535110">and</span>
  <span m="2535270">if</span> <span m="2535390">I</span> <span m="2535520">add</span>
  <span m="2535790">those</span> <span m="2536060">numbers</span> <span m="2536440">I</span>
  <span m="2536550">get</span> <span m="2536750">six.</span></p><p><span m="2538970">The</span>
  <span m="2539330">other</span> <span m="2539720">simple</span> <span m="2540240">test</span>
  <span m="2540660">is</span> <span m="2540840">the</span> <span m="2540980">determinant,</span>
  <span m="2542000">if</span> <span m="2542280">I</span> <span m="2542790">--</span>
  <span m="2544150">can</span> <span m="2544380">you</span> <span m="2544450">do</span>
  <span m="2544710">this,</span> <span m="2545380">can</span> <span m="2545580">you</span>
  <span m="2545690">multiply</span> <span m="2546200">those</span> <span m="2546480">numbers</span>
  <span m="2546930">together?</span></p><p><span m="2549240">I</span> <span m="2549280">guess</span>
  <span m="2549540">we</span> <span m="2549660">can</span> <span m="2549850">multiply</span>
  <span m="2550280">by</span> <span m="2550480">two</span> <span m="2550890">out</span>
  <span m="2551010">there.</span></p><p><span m="2552610">What's</span> <span m="2553010">two</span>
  <span m="2553230">minus</span> <span m="2553670">square</span> <span m="2553940">root</span>
  <span m="2554080">of</span> <span m="2554160">two</span> <span m="2554460">times</span>
  <span m="2554820">two</span> <span m="2555010">plus</span> <span m="2555370">square</span>
  <span m="2555620">root</span> <span m="2555740">of</span> <span m="2555830">two,</span>
  <span m="2556690">that'll</span> <span m="2557430">be</span> <span m="2558000">four</span>
  <span m="2558850">minus</span> <span m="2559350">two,</span> <span m="2559530">that'll</span>
  <span m="2559780">be</span> <span m="2559950">two,</span> <span m="2560320">yeah,</span>
  <span m="2560600">two</span> <span m="2560820">times</span> <span m="2561190">two,</span>
  <span m="2561610">that's</span> <span m="2562320">got</span> <span m="2562540">the</span>
  <span m="2562640">determinant,</span> <span m="2563180">right,</span> <span m="2563490">so</span>
  <span m="2564940">it's</span> <span m="2565980">got,</span> <span m="2566280">it's</span>
  <span m="2566600">got</span> <span m="2566750">a</span> <span m="2566820">chance</span>
  <span m="2567190">of</span> <span m="2567280">being</span> <span m="2567500">correct</span>
  <span m="2567890">and</span> <span m="2567990">I</span> <span m="2568050">think</span>
  <span m="2568330">it</span> <span m="2568430">is.</span></p><p><span m="2569810">Now,</span>
  <span m="2569990">what's</span> <span m="2570270">the</span> <span m="2570440">x</span>
  <span m="2570710">transpose</span> <span m="2571420">Ax?</span></p><p><span m="2571990">I</span>
  <span m="2572130">better</span> <span m="2572440">give</span> <span m="2572620">myself</span>
  <span m="2573060">enough</span> <span m="2573370">room</span> <span m="2573780">for</span>
  <span m="2573910">that.</span> <span m="2574610">x</span> <span m="2575120">transpose</span>
  <span m="2575980">Ax</span> <span m="2576660">for</span> <span m="2576780">this</span>
  <span m="2577070">guy.</span></p><p><span m="2579180">It's</span> <span m="2579500">two</span>
  <span m="2580470">x1</span> <span m="2581140">squareds,</span> <span m="2581970">and</span>
  <span m="2582660">two</span> <span m="2583590">x2</span> <span m="2584130">squareds,</span>
  <span m="2585030">and</span> <span m="2585760">two</span> <span m="2586250">x3</span>
  <span m="2586820">squareds.</span></p><p><span m="2587290">Those</span> <span m="2587850">come</span>
  <span m="2588050">from</span> <span m="2588250">the</span> <span m="2588350">diagonal,</span>
  <span m="2588950">those</span> <span m="2589190">were</span> <span m="2589340">easy.</span></p><p><span
  m="2590800">Now</span> <span m="2591030">off</span> <span m="2591330">the</span>
  <span m="2591460">diagonal</span> <span m="2592140">there's</span> <span m="2592390">a</span>
  <span m="2592440">minus</span> <span m="2592910">and</span> <span m="2593030">a</span>
  <span m="2593100">minus,</span> <span m="2593490">they</span> <span m="2593710">come</span>
  <span m="2593980">together</span> <span m="2594480">there'll</span> <span m="2594670">be</span>
  <span m="2594830">a</span> <span m="2594880">minus</span> <span m="2595610">two</span>
  <span m="2597010">minus</span> <span m="2598360">two</span> <span m="2598670">whats?</span></p><p><span
  m="2600010">Are</span> <span m="2600140">coming</span> <span m="2600590">from</span>
  <span m="2600860">this</span> <span m="2601460">one</span> <span m="2601980">two</span>
  <span m="2602320">and</span> <span m="2602460">two</span> <span m="2602660">one</span>
  <span m="2603000">position,</span> <span m="2603980">is</span> <span m="2604780">the</span>
  <span m="2605030">x1</span> <span m="2605460">x2.</span> <span m="2606390">I'm</span>
  <span m="2607620">doing</span> <span m="2608560">mentally</span> <span m="2609590">a</span>
  <span m="2609920">multiplication</span> <span m="2610900">of</span> <span m="2611040">this</span>
  <span m="2611320">matrix</span> <span m="2612210">times</span> <span m="2612800">a</span>
  <span m="2613280">row</span> <span m="2613810">vector</span> <span m="2614300">on</span>
  <span m="2614440">the</span> <span m="2614540">left</span> <span m="2615070">times</span>
  <span m="2615390">a</span> <span m="2615810">column</span> <span m="2616380">vector</span>
  <span m="2616740">on</span> <span m="2616860">the</span> <span m="2616930">right,</span>
  <span m="2617680">and</span> <span m="2618200">I</span> <span m="2618270">know</span>
  <span m="2618780">that</span> <span m="2618990">these</span> <span m="2619260">numbers</span>
  <span m="2619660">show</span> <span m="2619910">up</span> <span m="2620070">in</span>
  <span m="2620180">the</span> <span m="2620320">answer.</span></p><p><span m="2621730">The</span>
  <span m="2622150">diagonal</span> <span m="2622920">is</span> <span m="2623060">the</span>
  <span m="2623170">perfect</span> <span m="2623680">square,</span> <span m="2625060">this</span>
  <span m="2626060">off</span> <span m="2626350">diagonal</span> <span m="2627000">is</span>
  <span m="2627140">a</span> <span m="2627220">minus</span> <span m="2627660">two</span>
  <span m="2627850">x1</span> <span m="2628460">x2,</span> <span m="2629110">and</span>
  <span m="2629330">there</span> <span m="2629420">are</span> <span m="2629490">no</span>
  <span m="2629930">x1</span> <span m="2631120">x3-s,</span> <span m="2631360">and</span>
  <span m="2631640">there're</span> <span m="2631790">minus</span> <span m="2632270">two</span>
  <span m="2633480">x2</span> <span m="2633750">x3-s.</span> <span m="2635280">And</span>
  <span m="2635850">I</span> <span m="2636170">believe</span> <span m="2636780">that</span>
  <span m="2636950">that</span> <span m="2637230">expression</span> <span m="2637910">is</span>
  <span m="2638050">always</span> <span m="2638460">positive.</span></p><p><span m="2641670">I</span>
  <span m="2641900">believe</span> <span m="2642470">that</span> <span m="2642630">that</span>
  <span m="2643030">curve,</span> <span m="2644280">that</span> <span m="2645010">graph,</span>
  <span m="2645590">really,</span> <span m="2646010">of</span> <span m="2646250">that</span>
  <span m="2646470">function,</span> <span m="2647220">this</span> <span m="2647520">is</span>
  <span m="2647620">my</span> <span m="2647870">function</span> <span m="2648390">f,</span>
  <span m="2649720">and</span> <span m="2651010">I'm</span> <span m="2651210">in</span>
  <span m="2651410">more</span> <span m="2651680">dimensions</span> <span m="2652340">now</span>
  <span m="2652660">than</span> <span m="2652850">I</span> <span m="2652970">can</span>
  <span m="2653170">draw,</span> <span m="2653910">it</span> <span m="2654740">--</span>
  <span m="2654770">but</span> <span m="2655040">the</span> <span m="2655610">graph</span>
  <span m="2656130">of</span> <span m="2656250">that</span> <span m="2656550">function</span>
  <span m="2657020">goes</span> <span m="2657310">upwards.</span></p><p><span m="2660080">It's</span>
  <span m="2660280">a</span> <span m="2660340">bowl.</span></p><p><span m="2662320">Or</span>
  <span m="2662550">maybe</span> <span m="2663060">the</span> <span m="2663200">right</span>
  <span m="2663570">word</span> <span m="2664080">is</span> <span m="2664380">--</span>
  <span m="2666320">just</span> <span m="2666470">forgot,</span> <span m="2667610">what's</span>
  <span m="2670790">a</span> <span m="2670830">long</span> <span m="2671290">word</span>
  <span m="2671730">for</span> <span m="2671910">bowl?</span></p><p><span m="2674210">Hm,</span>
  <span m="2677510">maybe</span> <span m="2677970">paraboloid,</span> <span m="2679370">I</span>
  <span m="2679410">think,</span> <span m="2679640">paraboloid</span> <span m="2680380">comes</span>
  <span m="2681060">in.</span></p><p><span m="2682570">I'll</span> <span m="2683140">edit</span>
  <span m="2683840">the</span> <span m="2683900">tape</span> <span m="2684330">and</span>
  <span m="2684410">get</span> <span m="2684640">that</span> <span m="2685000">word</span>
  <span m="2685640">in.</span></p><p><span m="2686150">Bowl,</span> <span m="2686970">let's</span>
  <span m="2687310">say,</span> <span m="2687890">is,</span> <span m="2689360">that,</span>
  <span m="2690090">so</span> <span m="2690700">that,</span> <span m="2690920">and</span>
  <span m="2691620">if</span> <span m="2692320">I</span> <span m="2693010">can</span>
  <span m="2693710">--</span> <span m="2694410">I</span> <span m="2694530">could</span>
  <span m="2694800">complete</span> <span m="2695250">the</span> <span m="2695460">squares,</span>
  <span m="2695950">I</span> <span m="2696070">could</span> <span m="2696270">write</span>
  <span m="2696500">that</span> <span m="2696700">as</span> <span m="2696920">the</span>
  <span m="2696970">sum</span> <span m="2697140">of</span> <span m="2697420">three</span>
  <span m="2697650">squares,</span> <span m="2698540">and</span> <span m="2698860">those</span>
  <span m="2699140">three</span> <span m="2699340">squares</span> <span m="2699740">would</span>
  <span m="2699910">get</span> <span m="2700100">multiplied</span> <span m="2700650">by</span>
  <span m="2700850">the</span> <span m="2701050">three</span> <span m="2701280">pivots.</span></p><p><span
  m="2702780">And</span> <span m="2702940">the</span> <span m="2703090">pivots</span>
  <span m="2703420">are</span> <span m="2703510">all</span> <span m="2704110">positive.</span></p><p><span
  m="2705440">So</span> <span m="2705630">I</span> <span m="2705730">would</span>
  <span m="2705920">have</span> <span m="2706220">positive</span> <span m="2706750">pivots</span>
  <span m="2707270">times</span> <span m="2707620">squares,</span> <span m="2708760">the</span>
  <span m="2709200">net</span> <span m="2709490">result</span> <span m="2709930">would</span>
  <span m="2710100">be</span> <span m="2710260">a</span> <span m="2710330">positive</span>
  <span m="2710970">function</span> <span m="2711630">and</span> <span m="2711940">a</span>
  <span m="2712000">bowl</span> <span m="2712370">which</span> <span m="2712520">goes</span>
  <span m="2712780">upwards.</span></p><p><span m="2714520">And</span> <span m="2714750">then,</span>
  <span m="2715000">finally,</span> <span m="2715790">if</span> <span m="2716040">I</span>
  <span m="2716290">cut</span> <span m="2716760">--</span> <span m="2716790">if</span>
  <span m="2716980">I</span> <span m="2717090">slice</span> <span m="2717660">through</span>
  <span m="2717870">this</span> <span m="2718120">bowl,</span> <span m="2719230">if</span>
  <span m="2719930">I</span> <span m="2720090">--</span> <span m="2720160">now</span>
  <span m="2720410">I'm</span> <span m="2720770">asking</span> <span m="2721140">you</span>
  <span m="2721230">to</span> <span m="2721370">stretch</span> <span m="2721930">your</span>
  <span m="2722660">visualization</span> <span m="2723730">here,</span> <span m="2724670">because</span>
  <span m="2725490">I'm</span> <span m="2725650">in</span> <span m="2725790">four</span>
  <span m="2726050">dimensions,</span> <span m="2726680">I've</span> <span m="2726800">got</span>
  <span m="2726990">x1</span> <span m="2728110">x2</span> <span m="2728390">x3</span>
  <span m="2728600">in</span> <span m="2728710">the</span> <span m="2728800">base,</span>
  <span m="2729450">and</span> <span m="2729850">this</span> <span m="2730150">function</span>
  <span m="2731020">is</span> <span m="2731690">z,</span> <span m="2732320">or</span>
  <span m="2733050">f,</span> <span m="2733610">or</span> <span m="2733790">something.</span></p><p><span
  m="2735000">And</span> <span m="2736300">its</span> <span m="2736780">graph</span>
  <span m="2737360">is</span> <span m="2737620">going</span> <span m="2737910">up.</span></p><p><span
  m="2738320">But</span> <span m="2738520">I'm</span> <span m="2738730">in</span>
  <span m="2738880">four</span> <span m="2739140">dimensions,</span> <span m="2739710">because</span>
  <span m="2739900">I've</span> <span m="2740030">got</span> <span m="2740260">three</span>
  <span m="2740530">in</span> <span m="2740660">the</span> <span m="2740750">base</span>
  <span m="2741270">and</span> <span m="2741520">then</span> <span m="2741730">the</span>
  <span m="2741890">upward</span> <span m="2742260">direction,</span> <span m="2743410">but</span>
  <span m="2744200">now</span> <span m="2744460">if</span> <span m="2744580">I</span>
  <span m="2744660">cut</span> <span m="2745170">through</span> <span m="2745600">this</span>
  <span m="2746960">four-dimensional</span> <span m="2748820">picture,</span> <span
  m="2749640">at</span> <span m="2750160">level</span> <span m="2750670">one,</span>
  <span m="2751770">so,</span> <span m="2752470">suppose</span> <span m="2752980">I</span>
  <span m="2753110">cut</span> <span m="2753450">through</span> <span m="2754560">this</span>
  <span m="2755340">thing</span> <span m="2755720">at</span> <span m="2756580">height</span>
  <span m="2757130">one.</span></p><p><span m="2758100">So</span> <span m="2758310">I</span>
  <span m="2758430">take</span> <span m="2758800">all</span> <span m="2759200">the</span>
  <span m="2759330">points</span> <span m="2760190">that</span> <span m="2760520">are</span>
  <span m="2760700">at</span> <span m="2760800">height</span> <span m="2761120">one.</span></p><p><span
  m="2764980">That</span> <span m="2765380">gives</span> <span m="2765710">me</span>
  <span m="2766280">--</span> <span m="2767770">it</span> <span m="2767940">gave</span>
  <span m="2768170">me</span> <span m="2768330">an</span> <span m="2768420">ellipse</span>
  <span m="2768970">over</span> <span m="2769250">there,</span> <span m="2770730">in</span>
  <span m="2771990">that</span> <span m="2772430">two</span> <span m="2772920">by</span>
  <span m="2773210">two</span> <span m="2773450">case,</span> <span m="2774180">in</span>
  <span m="2774480">this</span> <span m="2774780">case,</span> <span m="2775460">this</span>
  <span m="2775940">will</span> <span m="2776170">be</span> <span m="2776510">the</span>
  <span m="2776700">equation</span> <span m="2777430">of</span> <span m="2777890">an</span>
  <span m="2778120">ellipsoid,</span> <span m="2779350">a</span> <span m="2779610">football</span>
  <span m="2780190">in</span> <span m="2780300">other</span> <span m="2780470">words.</span></p><p><span
  m="2783770">Well,</span> <span m="2784080">not</span> <span m="2784310">quite</span>
  <span m="2784590">a</span> <span m="2784650">football.</span></p><p><span m="2785170">A</span>
  <span m="2785220">lopsided</span> <span m="2786060">football.</span></p><p><span
  m="2786450">What</span> <span m="2786630">would</span> <span m="2787100">be,</span>
  <span m="2787930">can</span> <span m="2788340">I</span> <span m="2788660">try</span>
  <span m="2789070">to</span> <span m="2789190">describe</span> <span m="2789760">to</span>
  <span m="2789830">you</span> <span m="2790190">what</span> <span m="2790960">the</span>
  <span m="2791230">ellipsoid</span> <span m="2792110">will</span> <span m="2792320">look</span>
  <span m="2792590">like,</span> <span m="2793390">this</span> <span m="2794450">ellipsoid,</span>
  <span m="2795590">I'm</span> <span m="2796260">sorry</span> <span m="2796640">that</span>
  <span m="2796950">the,</span> <span m="2797610">that</span> <span m="2798110">I've</span>
  <span m="2798730">ended</span> <span m="2799420">the</span> <span m="2799530">matrix</span>
  <span m="2800160">right</span> <span m="2800420">--</span> <span m="2800440">at</span>
  <span m="2800600">the</span> <span m="2801110">point,</span> <span m="2801730">let's</span>
  <span m="2801960">--</span> <span m="2801990">let</span> <span m="2802140">me</span>
  <span m="2802680">be</span> <span m="2802960">sure</span> <span m="2803290">you've</span>
  <span m="2803400">seen</span> <span m="2804050">the</span> <span m="2804620">equation.</span></p><p><span
  m="2806230">Two</span> <span m="2806460">x1</span> <span m="2806910">squared,</span>
  <span m="2807350">two</span> <span m="2807500">x2</span> <span m="2807930">squared,</span>
  <span m="2808720">two</span> <span m="2809030">x3</span> <span m="2809460">squared,</span>
  <span m="2810370">minus</span> <span m="2810850">two</span> <span m="2811130">of</span>
  <span m="2811230">the</span> <span m="2811600">cross</span> <span m="2812240">parts,</span>
  <span m="2813530">equal</span> <span m="2814620">what?</span></p><p><span m="2817000">That</span>
  <span m="2817740">is</span> <span m="2818050">the</span> <span m="2818180">equation</span>
  <span m="2818810">of</span> <span m="2819090">a</span> <span m="2819910">football,</span>
  <span m="2820410">so</span> <span m="2820550">what</span> <span m="2820720">do</span>
  <span m="2820820">I</span> <span m="2820920">mean</span> <span m="2821200">by</span>
  <span m="2821350">a</span> <span m="2821430">football</span> <span m="2821920">or</span>
  <span m="2822070">an</span> <span m="2822120">ellipsoid?</span></p><p><span m="2823780">I</span>
  <span m="2823960">mean</span> <span m="2824560">that,</span> <span m="2825840">well,</span>
  <span m="2826660">I'll</span> <span m="2826820">draw</span> <span m="2829610">a</span>
  <span m="2829850">few.</span></p><p><span m="2832520">It's</span> <span m="2837720">like</span>
  <span m="2838040">that,</span> <span m="2838430">it's</span> <span m="2838570">got</span>
  <span m="2838780">a</span> <span m="2838850">center,</span> <span m="2841750">and</span>
  <span m="2842040">it's</span> <span m="2842360">got</span> <span m="2845320">it's</span>
  <span m="2845570">got</span> <span m="2845950">three</span> <span m="2849060">principal</span>
  <span m="2849730">directions.</span></p><p><span m="2851990">This</span> <span m="2852230">ellipsoid.</span></p><p><span
  m="2852830">So</span> <span m="2852930">--</span> <span m="2853450">you</span> <span
  m="2853560">see</span> <span m="2853730">what</span> <span m="2853840">I'm</span>
  <span m="2853970">saying,</span> <span m="2854210">if</span> <span m="2854360">we</span>
  <span m="2854500">have</span> <span m="2854680">a</span> <span m="2854740">sphere</span>
  <span m="2855280">then</span> <span m="2855460">all</span> <span m="2855660">directions</span>
  <span m="2856140">would</span> <span m="2856300">be</span> <span m="2856430">the</span>
  <span m="2856550">same.</span></p><p><span m="2859530">If</span> <span m="2859700">we</span>
  <span m="2859850">had</span> <span m="2860070">a</span> <span m="2860260">true</span>
  <span m="2860780">football,</span> <span m="2862360">or</span> <span m="2863080">it's</span>
  <span m="2863390">closer</span> <span m="2863820">to</span> <span m="2863940">a</span>
  <span m="2864030">rugby</span> <span m="2864460">ball,</span> <span m="2864750">really,</span>
  <span m="2865090">because</span> <span m="2865310">it's</span> <span m="2865550">more</span>
  <span m="2865830">curved</span> <span m="2866310">than</span> <span m="2866450">a</span>
  <span m="2866520">football,</span> <span m="2868110">it</span> <span m="2869760">would</span>
  <span m="2869910">have</span> <span m="2870120">one</span> <span m="2870500">long</span>
  <span m="2870870">direction</span> <span m="2871520">and</span> <span m="2871650">the</span>
  <span m="2871790">other</span> <span m="2872060">two</span> <span m="2872270">would</span>
  <span m="2872490">be</span> <span m="2872730">equal.</span></p><p><span m="2874020">That</span>
  <span m="2874280">would</span> <span m="2874450">be</span> <span m="2874640">like</span>
  <span m="2874900">having</span> <span m="2875190">a</span> <span m="2875260">matrix</span>
  <span m="2876240">that</span> <span m="2876550">had</span> <span m="2876790">one</span>
  <span m="2877080">eigenvalue</span> <span m="2878390">repeated.</span></p><p><span
  m="2879700">And</span> <span m="2880280">then</span> <span m="2880490">one</span>
  <span m="2880720">other</span> <span m="2881030">different.</span></p><p><span m="2882080">So</span>
  <span m="2882270">this</span> <span m="2882500">sphere</span> <span m="2883000">comes</span>
  <span m="2883330">from,</span> <span m="2883530">like,</span> <span m="2883770">the</span>
  <span m="2883920">identity</span> <span m="2884440">matrix,</span> <span m="2884940">all</span>
  <span m="2885160">eigenvalues</span> <span m="2885770">the</span> <span m="2885880">same.</span></p><p><span
  m="2887600">Our</span> <span m="2887760">rugby</span> <span m="2888240">ball</span>
  <span m="2888630">comes</span> <span m="2889030">from</span> <span m="2889460">a</span>
  <span m="2889600">case</span> <span m="2890160">where</span> <span m="2890950">--</span>
  <span m="2892370">three,</span> <span m="2893140">the</span> <span m="2893340">three,</span>
  <span m="2894220">two</span> <span m="2894840">of</span> <span m="2895020">the</span>
  <span m="2895130">three</span> <span m="2895390">eigenvalues</span> <span m="2895990">are</span>
  <span m="2896030">the</span> <span m="2896160">same.</span></p><p><span m="2897070">But</span>
  <span m="2897260">we</span> <span m="2897550">know</span> <span m="2897770">how</span>
  <span m="2897950">the</span> <span m="2898100">case</span> <span m="2898590">where</span>
  <span m="2898930">--</span> <span m="2898950">the</span> <span m="2899110">typical</span>
  <span m="2899610">case,</span> <span m="2900000">where</span> <span m="2900180">the</span>
  <span m="2900330">three</span> <span m="2900680">eigenvalues</span> <span m="2901430">were</span>
  <span m="2901570">all</span> <span m="2901770">different.</span></p><p><span m="2903340">So</span>
  <span m="2903790">this</span> <span m="2904120">will</span> <span m="2904400">have</span>
  <span m="2905070">--</span> <span m="2908440">How</span> <span m="2908640">do</span>
  <span m="2908760">I</span> <span m="2908860">say</span> <span m="2909080">it,</span>
  <span m="2909430">if</span> <span m="2909690">I</span> <span m="2909790">look</span>
  <span m="2910170">at</span> <span m="2910270">this</span> <span m="2910480">ellipsoid</span>
  <span m="2911070">correctly,</span> <span m="2911830">it'll</span> <span m="2912160">have</span>
  <span m="2912390">a</span> <span m="2912480">major</span> <span m="2913220">axis,</span>
  <span m="2914470">it'll</span> <span m="2914900">have</span> <span m="2915120">a</span>
  <span m="2915240">middle</span> <span m="2915920">axis,</span> <span m="2917200">and</span>
  <span m="2917710">it'll</span> <span m="2917970">have</span> <span m="2918250">a</span>
  <span m="2919060">minor</span> <span m="2919740">axis.</span></p><p><span m="2921520">And</span>
  <span m="2921690">those</span> <span m="2921980">three</span> <span m="2922200">axes</span>
  <span m="2923170">will</span> <span m="2923550">be</span> <span m="2923940">in</span>
  <span m="2924160">the</span> <span m="2924280">direction</span> <span m="2924940">of</span>
  <span m="2925250">the</span> <span m="2925420">eigenvectors.</span></p><p><span
  m="2927450">And</span> <span m="2927650">the</span> <span m="2927880">lengths</span>
  <span m="2928310">of</span> <span m="2928420">those</span> <span m="2928690">axes</span>
  <span m="2929430">will</span> <span m="2929870">be</span> <span m="2930760">determined</span>
  <span m="2931650">by</span> <span m="2931920">the</span> <span m="2932150">eigenvalues.</span></p><p><span
  m="2935260">I</span> <span m="2935420">can</span> <span m="2935690">get</span> <span
  m="2936200">--</span> <span m="2936770">turn</span> <span m="2937030">this</span>
  <span m="2937250">all</span> <span m="2937510">into</span> <span m="2937770">linear</span>
  <span m="2938130">algebra,</span> <span m="2939390">because</span> <span m="2940260">we</span>
  <span m="2940390">have</span> <span m="2940700">--</span> <span m="2942520">the</span>
  <span m="2942660">right</span> <span m="2943250">thing</span> <span m="2943610">we</span>
  <span m="2943800">know</span> <span m="2944100">about</span> <span m="2944390">eigenvectors</span>
  <span m="2945430">and</span> <span m="2945620">eigenvalues,</span> <span m="2946410">for</span>
  <span m="2946530">that</span> <span m="2946810">matrix</span> <span m="2947390">is</span>
  <span m="2947690">what?</span></p><p><span m="2948120">Of</span> <span m="2948270">--</span>
  <span m="2948720">let</span> <span m="2948990">me</span> <span m="2949100">just</span>
  <span m="2949360">tell</span> <span m="2949550">you</span> <span m="2949660">that,</span>
  <span m="2950050">repeat</span> <span m="2950680">the</span> <span m="2950790">main</span>
  <span m="2951220">linear</span> <span m="2951580">algebra</span> <span m="2951970">point.</span></p><p><span
  m="2953070">How</span> <span m="2953400">could</span> <span m="2953610">we</span>
  <span m="2954650">turn</span> <span m="2955600">what</span> <span m="2955780">I</span>
  <span m="2955900">said</span> <span m="2956280">into</span> <span m="2957720">algebra;</span>
  <span m="2958970">we</span> <span m="2959440">would</span> <span m="2959650">write</span>
  <span m="2960040">this</span> <span m="2960320">A</span> <span m="2960950">as</span>
  <span m="2961740">Q,</span> <span m="2963020">the</span> <span m="2963360">eigenvector</span>
  <span m="2964030">matrix,</span> <span m="2965050">times</span> <span m="2965470">lambda,</span>
  <span m="2966270">the</span> <span m="2966430">eigenvalue</span> <span m="2967160">matrix</span>
  <span m="2968000">times</span> <span m="2968490">Q</span> <span m="2968730">transposed.</span></p><p><span
  m="2970370">The</span> <span m="2970510">principal</span> <span m="2971350">axis</span>
  <span m="2971940">theorem,</span> <span m="2972300">we'll</span> <span m="2972550">call</span>
  <span m="2972830">it,</span></p><p><span m="2973010">now.</span> <span m="2973900">The</span>
  <span m="2974790">eigenvectors</span> <span m="2975850">tell</span> <span m="2976120">us</span>
  <span m="2976410">the</span> <span m="2976540">directions</span> <span m="2977160">of</span>
  <span m="2977260">the</span> <span m="2977360">principal</span></p><p><span m="2977980">axes.</span>
  <span m="2979110">The</span> <span m="2979670">eigenvalues</span> <span m="2980530">tell</span>
  <span m="2980740">us</span> <span m="2980950">the</span> <span m="2981080">lengths</span>
  <span m="2981490">of</span> <span m="2981590">those</span> <span m="2981860">axes,</span>
  <span m="2982760">actually</span> <span m="2983240">the</span> <span m="2983360">lengths,</span>
  <span m="2983830">or</span> <span m="2984230">the</span> <span m="2984480">half-lengths,</span>
  <span m="2985160">or</span> <span m="2985280">one</span> <span m="2985630">over</span>
  <span m="2985910">the</span> <span m="2986090">eigenvalues,</span> <span m="2986730">it</span>
  <span m="2986840">turns</span> <span m="2987170">out.</span></p><p><span m="2988970">And</span>
  <span m="2989630">that</span> <span m="2990490">is</span> <span m="2990800">the</span>
  <span m="2990900">matrix</span> <span m="2991630">factorization</span> <span m="2993260">which</span>
  <span m="2994030">is</span> <span m="2994160">the</span> <span m="2994270">most</span>
  <span m="2994590">important</span> <span m="2995020">matrix</span> <span m="2995490">factorization</span>
  <span m="2996470">in</span> <span m="2997570">our</span> <span m="2998530">eigenvalue</span>
  <span m="2999270">material</span> <span m="2999740">so</span> <span m="2999940">far.</span></p><p><span
  m="3000540">That's</span> <span m="3000930">diagonalization</span> <span m="3002480">for</span>
  <span m="3002930">a</span> <span m="3002980">symmetric</span> <span m="3003690">matrix,</span>
  <span m="3004320">so</span> <span m="3005020">instead</span> <span m="3005430">of</span>
  <span m="3005540">the</span> <span m="3005670">inverse</span> <span m="3006170">I</span>
  <span m="3006270">can</span> <span m="3006460">write</span> <span m="3006720">the</span>
  <span m="3006840">transposed.</span></p><p><span m="3009350">OK.</span></p><p><span
  m="3009930">I've</span> <span m="3010200">--</span> <span m="3011010">so</span>
  <span m="3011090">what</span> <span m="3011270">I've</span> <span m="3011380">tried</span>
  <span m="3011690">today</span> <span m="3012040">is</span> <span m="3012260">to</span>
  <span m="3012450">tell</span> <span m="3012740">you</span> <span m="3013050">the</span>
  <span m="3013580">--</span> <span m="3014140">what's</span> <span m="3014470">going</span>
  <span m="3014760">on</span> <span m="3015300">with</span> <span m="3016690">positive</span>
  <span m="3018220">definite</span> <span m="3018680">matrices.</span></p><p><span
  m="3020510">Ah,</span> <span m="3020530">you</span> <span m="3020740">see</span>
  <span m="3020970">all</span> <span m="3021150">how</span> <span m="3021340">all</span>
  <span m="3021540">these</span> <span m="3021780">pieces</span> <span m="3022270">are</span>
  <span m="3022380">there</span> <span m="3023020">and</span> <span m="3023810">linear</span>
  <span m="3024230">algebra</span> <span m="3024700">connects</span> <span m="3025150">them.</span></p><p><span
  m="3025760">OK.</span> <span m="3028760">See</span> <span m="3028910">you</span>
  <span m="3028990">on</span> <span m="3029130">Friday.</span></p>
type: course
uid: 7bbe9a95a404007da1050b514194b58e

---
None