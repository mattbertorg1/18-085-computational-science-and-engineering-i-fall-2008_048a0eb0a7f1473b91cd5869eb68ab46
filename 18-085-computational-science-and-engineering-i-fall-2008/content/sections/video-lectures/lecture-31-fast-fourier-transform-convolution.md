---
about_this_resource_text: <p><strong>Instructor:</strong> Prof. Gilbert Strang</p>
course_id: 18-085-computational-science-and-engineering-i-fall-2008
embedded_media:
- id: 31.jpg
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-31-fast-fourier-transform-convolution/31.jpg
  title: Lecture 31
  type: null
  uid: 20b0c228f7ca902a53e5b62cda47412a
- id: Video-YouTube-Stream
  media_location: UdpdZ0diXUg
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: Video-YouTube-Stream
  type: Video
  uid: bc0fb1d9985b758e6d426772485f56a3
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/UdpdZ0diXUg/default.jpg
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e2f02ff8dbf585ba8480f159214ba183
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869177
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: Video-iTunes U-MP4
  type: Video
  uid: b67070cf9ca0cd441f2faddf6227c63b
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.085F08/ocw-18.085-f08-lec31_300k.mp4
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2b2c3087cdb3bb68e18d62cac3fafe32
- id: Thumbnail-OCW-JPG
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 712235024646932b93e4ccb4e2d99883
- id: 3Play-3PlayYouTubeid-MP4
  media_location: UdpdZ0diXUg
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b7911ba3fb349b9a6ba345bbb23e74eb
- id: UdpdZ0diXUg.srt
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-31-fast-fourier-transform-convolution/UdpdZ0diXUg.srt
  title: 3play caption file
  type: null
  uid: f641c0b28c449ac98722aab3593cdfea
- id: UdpdZ0diXUg.pdf
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-31-fast-fourier-transform-convolution/UdpdZ0diXUg.pdf
  title: 3play pdf file
  type: null
  uid: d9d94e10bd89f778588fcd7261f47148
- id: Caption-3Play YouTube id-SRT
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ee4cabbbd906df650c1779d1be476e41
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 59f0e4997ec84a7855a682c6c5b58b16
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 7c04a9b650d208a62599f11b0aaf364c
inline_embed_id: 90328996lecture31:fastfouriertransform,convolution23281102
layout: video
order_index: null
parent_uid: 4e3ac3b31de7414e05181196c7255bbd
related_resources_text: ''
short_url: lecture-31-fast-fourier-transform-convolution
technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-31-fast-fourier-transform-convolution
template_type: Tabbed
title: 'Lecture 31: Fast Fourier Transform, Convolution'
transcript: <p><span m='340'>The following</span> <span m='1920'>content is provided</span>
  <span m='2340'>under a</span> <span m='3610'>Creative Commons license.</span> <span
  m='3810'>Your support</span> <span m='5020'>will help</span> <span m='5220'>MIT
  OpenCourseWare</span> <span m='5450'>continue</span> <span m='5770'>to</span> <span
  m='6730'>offer</span> <span m='6890'>high-quality</span> <span m='7630'>educational</span>
  <span m='8250'>resources</span> <span m='8840'>for</span> <span m='8970'>free.</span>
  <span m='9930'>To</span> <span m='10310'>make a donation,</span> <span m='10640'>or</span>
  <span m='11070'>to</span> <span m='11240'>view</span> <span m='11410'>additional</span>
  <span m='11960'>materials</span> <span m='12540'>from hundreds</span> <span m='13250'>of
  MIT</span> <span m='13580'>courses,</span> <span m='14210'>visit</span> <span m='15160'>MIT</span>
  <span m='15610'>OpenCourseWare</span> <span m='16150'>at</span> <span m='16880'>ocw.mit.edu.</span>
  </p><p><span m='21310'>OK,</span> <span m='22040'>so.</span> <span m='23470'>Pretty</span>
  <span m='23720'>full</span> <span m='24020'>day</span> <span m='24330'>again.</span>
  <span m='25050'>I</span> <span m='25820'>had</span> <span m='26620'>last</span>
  <span m='27500'>time</span> <span m='28200'>introduced</span> <span m='29010'>the</span>
  <span m='29130'>Fourier</span> <span m='29610'>matrix,</span> <span m='30730'>the</span>
  <span m='30930'>discrete</span> <span m='31400'>Fourier</span> <span m='31750'>transform.</span>
  <span m='33330'>Well,</span> <span m='34860'>more</span> <span m='35230'>strictly,</span>
  <span m='35640'>the</span> <span m='35940'>discrete</span> <span m='36500'>Fourier</span>
  <span m='36800'>transform</span> <span m='37400'>is</span> <span m='37540'>usually</span>
  <span m='37940'>this</span> <span m='38240'>one.</span> <span m='38530'>It</span>
  <span m='38680'>takes</span> <span m='39140'>the</span> <span m='39280'>function</span>
  <span m='39790'>values</span> <span m='40390'>and</span> <span m='40550'>produces</span>
  <span m='41490'>the</span> <span m='41820'>coefficients.</span> <span m='43250'>And</span>
  <span m='43490'>then</span> <span m='43930'>I</span> <span m='44190'>started</span>
  <span m='44770'>with</span> <span m='45180'>the</span> <span m='45310'>coefficients,</span>
  <span m='46350'>added</span> <span m='46800'>back,</span> <span m='47830'>added</span>
  <span m='48180'>up</span> <span m='48340'>the</span> <span m='48510'>series</span>
  <span m='49060'>to get</span> <span m='49570'>the</span> <span m='49810'>function</span>
  <span m='50280'>values.</span> <span m='51080'>So F</span> <span m='51260'>or</span>
  <span m='51630'>F</span> <span m='51870'>inverse.</span> <span m='53620'>So</span>
  <span m='53840'>we</span> <span m='54000'>didn't</span> <span m='54390'>do</span>
  <span m='54740'>examples</span> <span m='55560'>yet.</span> <span m='56430'>And</span>
  <span m='57260'>one</span> <span m='57730'>natural</span> <span m='58420'>example</span>
  <span m='59030'>is</span> <span m='59630'>the</span> <span m='59780'>discrete</span>
  <span m='60680'>delta</span> <span m='61100'>function</span> <span m='63050'>that</span>
  <span m='63380'>has</span> <span m='63700'>a</span> <span m='63770'>one</span> <span
  m='64190'>in</span> <span m='64410'>the</span> <span m='64480'>zero</span> <span
  m='64870'>position.</span> <span m='66050'>That's</span> <span m='66350'>easy</span>
  <span m='66730'>to</span> <span m='66890'>do.</span> <span m='67540'>And</span>
  <span m='67780'>then</span> <span m='67990'>we</span> <span m='68170'>should</span>
  <span m='68470'>do</span> <span m='68730'>also</span> <span m='69630'>a</span> <span
  m='69720'>shift,</span> <span m='71170'>to</span> <span m='71360'>see</span> <span
  m='71870'>what's</span> <span m='72210'>the</span> <span m='72350'>effect,</span>
  <span m='73000'>if</span> <span m='73210'>you</span> <span m='73450'>shift</span>
  <span m='73860'>the</span> <span m='73980'>function,</span> <span m='74820'>what</span>
  <span m='75080'>happens</span> <span m='75620'>to</span> <span m='75780'>the</span>
  <span m='75900'>transform.</span> <span m='77020'>That's</span> <span m='77260'>an</span>
  <span m='77390'>important</span> <span m='77980'>rule,</span> <span m='78390'>important</span>
  <span m='78910'>for</span> <span m='79080'>Fourier</span> <span m='79750'>series</span>
  <span m='79780'>and</span> <span m='80190'>Fourier</span> <span m='80440'>integrals,</span>
  <span m='81020'>too.</span> <span m='81890'>Because</span> <span m='82270'>often</span>
  <span m='82700'>you</span> <span m='82840'>do</span> <span m='83050'>that,</span>
  <span m='83750'>and</span> <span m='83910'>it's</span> <span m='84400'>going to</span>
  <span m='84730'>be</span> <span m='84880'>a</span> <span m='84960'>simple</span>
  <span m='85430'>rule.</span> <span m='86240'>If</span> <span m='86420'>you</span>
  <span m='86570'>shift</span> <span m='86900'>the</span> <span m='87060'>function,</span>
  <span m='87850'>the</span> <span m='87980'>transform</span> <span m='89020'>does</span>
  <span m='89270'>something</span> <span m='89770'>nice.</span> <span m='91490'>OK,</span>
  <span m='92160'>and</span> <span m='92440'>then</span> <span m='93030'>I</span>
  <span m='93140'>want</span> <span m='93560'>to</span> <span m='93630'>describe</span>
  <span m='94130'>a</span> <span m='94180'>little</span> <span m='94420'>about</span>
  <span m='94720'>the</span> <span m='94830'>FFT</span> <span m='95520'>and</span>
  <span m='95710'>then</span> <span m='95900'>start</span> <span m='96450'>on</span>
  <span m='97240'>the</span> <span m='97390'>next</span> <span m='97720'>section,</span>
  <span m='98290'>convolutions.</span> <span m='98940'>So</span> <span m='99230'>that's</span>
  <span m='99550'>fun</span> <span m='100090'>and</span> <span m='100260'>that's</span>
  <span m='100520'>a</span> <span m='101110'>big</span> <span m='101370'>deal.</span>
  </p><p><span m='102250'>OK,</span> <span m='102900'>about</span> <span m='103590'>reviews,</span>
  <span m='104440'>I'll</span> <span m='104630'>be</span> <span m='104850'>here</span>
  <span m='105350'>as</span> <span m='105570'>usual</span> <span m='106050'>today.</span>
  <span m='107340'>I</span> <span m='107540'>think</span> <span m='107880'>maybe</span>
  <span m='109610'>the</span> <span m='109810'>26th,</span> <span m='110720'>just</span>
  <span m='111040'>hours</span> <span m='111440'>before</span> <span m='111830'>Thanksgiving,</span>
  <span m='112690'>we can</span> <span m='113620'>give</span> <span m='113780'>ourselves</span>
  <span m='114280'>a</span> <span m='114360'>holiday.</span> <span m='116230'>So</span>
  <span m='116440'>not</span> <span m='116910'>next</span> <span m='117280'>Wednesday</span>
  <span m='117830'>but</span> <span m='118030'>then</span> <span m='118320'>certainly</span>
  <span m='118890'>the</span> <span m='119490'>Wednesday</span> <span m='121120'>of</span>
  <span m='121360'>the</span> <span m='121490'>following</span> <span m='121990'>week</span>
  <span m='123240'>would</span> <span m='123860'>be</span> <span m='123990'>a</span>
  <span m='124210'>sort</span> <span m='124500'>of</span> <span m='124580'>major</span>
  <span m='125090'>quiz</span> <span m='125500'>review</span> <span m='128570'>in</span>
  <span m='128790'>the</span> <span m='128890'>review</span> <span m='129250'>session.</span>
  <span m='130040'>And in</span> <span m='130590'>class.</span> <span m='131790'>OK,</span>
  <span m='132570'>ready</span> <span m='132950'>to</span> <span m='133120'>go?</span>
  <span m='133950'>On</span> <span m='134680'>this</span> <span m='135160'>example</span>
  <span m='137440'>gives</span> <span m='137710'>us</span> <span m='137880'>a</span>
  <span m='137960'>chance</span> <span m='138390'>just</span> <span m='138640'>to</span>
  <span m='138740'>remember</span> <span m='139220'>what</span> <span m='139400'>the</span>
  <span m='139490'>matrix</span> <span m='140030'>looks</span> <span m='140290'>like,</span>
  <span m='140690'>because</span> <span m='141030'>we're</span> <span m='141190'>just</span>
  <span m='141480'>going to,</span> <span m='142010'>if I</span> <span m='142260'>multiply</span>
  <span m='143300'>this</span> <span m='143540'>inverse</span> <span m='144070'>matrix</span>
  <span m='144730'>by</span> <span m='145080'>that</span> <span m='145470'>vector</span>
  <span m='145960'>it's</span> <span m='146110'>just</span> <span m='146320'>going
  to</span> <span m='146590'>pick</span> <span m='146820'>off</span> <span m='147100'>the</span>
  <span m='147230'>first</span> <span m='147620'>column and</span> <span m='148110'>it'll</span>
  <span m='148390'>be</span> <span m='149420'>totally</span> <span m='149870'>easy</span>
  <span m='150340'>so</span> <span m='150540'>let's</span> <span m='150820'>just</span>
  <span m='151080'>do</span> <span m='151240'>it.</span> <span m='151900'>So</span>
  <span m='152680'>if</span> <span m='152860'>y</span> <span m='153360'>is</span>
  <span m='153550'>this</span> <span m='153850'>one,</span> <span m='154490'>I</span>
  <span m='154750'>want</span> <span m='155040'>to</span> <span m='155130'>know</span>
  <span m='155340'>about</span> <span m='155800'>f.</span> <span m='156820'>What</span>
  <span m='156930'>are the</span> <span m='157200'>Fourier</span> <span m='157720'>coefficients</span>
  <span m='158380'>of</span> <span m='158880'>the</span> <span m='162850'>delta</span>
  <span m='163350'>function?</span> <span m='164020'>Discrete</span> <span m='164560'>delta</span>
  <span m='164720'>function?</span> <span m='165700'>OK,</span> <span m='166040'>before</span>
  <span m='166390'>I</span> <span m='166480'>even</span> <span m='166750'>do</span>
  <span m='166950'>it,</span> <span m='167850'>we</span> <span m='168540'>got</span>
  <span m='168730'>a</span> <span m='168770'>pretty</span> <span m='169030'>good</span>
  <span m='169240'>idea</span> <span m='169560'>what</span> <span m='169750'>to</span>
  <span m='169850'>expect.</span> <span m='171230'>Because</span> <span m='171440'>we</span>
  <span m='171590'>remember</span> <span m='172120'>what</span> <span m='172350'>happened</span>
  <span m='172800'>to</span> <span m='172930'>the</span> <span m='173040'>ordinary</span>
  <span m='173660'>delta</span> <span m='174130'>function,</span> <span m='175510'>in</span>
  <span m='175930'>continuous</span> <span m='176600'>time.</span> <span m='177040'>Or</span>
  <span m='177220'>rather,</span> <span m='177600'>I</span> <span m='177720'>guess</span>
  <span m='178020'>it</span> <span m='178120'>was</span> <span m='178320'>the</span>
  <span m='178450'>periodic</span> <span m='179330'>delta</span> <span m='179800'>function.</span>
  <span m='180770'>Do</span> <span m='180850'>you</span> <span m='180920'>remember</span>
  <span m='181240'>the</span> <span m='181460'>coefficients,</span> <span m='182210'>what</span>
  <span m='182450'>were</span> <span m='182590'>the</span> <span m='182940'>coefficients</span>
  <span m='183350'>for</span> <span m='183540'>the</span> <span m='183660'>periodic</span>
  <span m='184320'>delta</span> <span m='184690'>function?</span> <span m='185460'>You</span>
  <span m='185620'>remember</span> <span m='186020'>those?</span> <span m='187370'>We</span>
  <span m='187510'>took</span> <span m='187760'>the</span> <span m='187880'>integral</span>
  <span m='188260'>from</span> <span m='188490'>minus</span> <span m='188780'>pi</span>
  <span m='189220'>to pi</span> <span m='190240'>of</span> <span m='190440'>our</span>
  <span m='190640'>function,</span> <span m='191340'>which</span> <span m='191590'>was</span>
  <span m='191810'>delta(x).</span> <span m='193340'>And</span> <span m='194440'>then</span>
  <span m='194680'>we</span> <span m='194820'>had</span> <span m='195040'>to</span>
  <span m='195120'>remember</span> <span m='195570'>to</span> <span m='195700'>divide</span>
  <span m='196250'>by</span> <span m='196570'>2pi,</span> <span m='197240'>and</span>
  <span m='197660'>you</span> <span m='197810'>remember</span> <span m='198130'>the</span>
  <span m='198300'>coefficients</span> <span m='199110'>are</span> <span m='199910'>e^(-ikx).</span>
  <span m='203090'>This</span> <span m='203900'>is</span> <span m='204080'>c_k</span>
  <span m='205210'>in</span> <span m='205450'>the</span> <span m='205720'>periodic</span>
  <span m='206430'>case,</span> <span m='206940'>the</span> <span m='207080'>2pi</span>
  <span m='207700'>periodic</span> <span m='208360'>case.</span> <span m='209130'>The</span>
  <span m='209300'>function</span> <span m='209870'>is</span> <span m='210080'>the
  delta</span> <span m='210480'>function,</span> <span m='211120'>and</span> <span
  m='211300'>you</span> <span m='211400'>remember</span> <span m='211880'>that</span>
  <span m='212090'>if</span> <span m='212230'>we</span> <span m='212350'>want</span>
  <span m='213430'>coefficient</span> <span m='213870'>k</span> <span m='214350'>we</span>
  <span m='214560'>multiply</span> <span m='215200'>by</span> <span m='215990'>e^(-ikx).</span>
  <span m='217730'>That's</span> <span m='218010'>the</span> <span m='218140'>thing</span>
  <span m='218410'>that</span> <span m='218580'>will</span> <span m='218760'>pick</span>
  <span m='219060'>out</span> <span m='219400'>the</span> <span m='220400'>e^(+ikx)</span>
  <span m='221480'>term.</span> <span m='222140'>And</span> <span m='222410'>of</span>
  <span m='222510'>course</span> <span m='223520'>everybody</span> <span m='223970'>knows</span>
  <span m='224260'>what</span> <span m='224420'>we</span> <span m='224530'>get</span>
  <span m='224770'>here,</span> <span m='225550'>this</span> <span m='225900'>delta,</span>
  <span m='227100'>this</span> <span m='227270'>spike</span> <span m='227800'>at</span>
  <span m='227950'>x=0,</span> <span m='230230'>means</span> <span m='230580'>we</span>
  <span m='230960'>take</span> <span m='231240'>the</span> <span m='231330'>value</span>
  <span m='231710'>of</span> <span m='231780'>that</span> <span m='232030'>function</span>
  <span m='232500'>at</span> <span m='232690'>zero,</span> <span m='233010'>which</span>
  <span m='233290'>is</span> <span m='233420'>one,</span> <span m='234060'>so</span>
  <span m='234220'>we</span> <span m='234350'>just</span> <span m='234610'>get</span>
  <span m='235100'>1/(2pi).</span> <span m='237780'>For</span> <span m='237920'>all</span>
  <span m='238140'>the</span> <span m='238280'>Fourier</span> <span m='238930'>coefficients</span>
  <span m='239680'>of</span> <span m='239880'>the</span> <span m='240000'>delta</span>
  <span m='240380'>function.</span> <span m='242490'>The</span> <span m='242580'>point</span>
  <span m='242960'>being</span> <span m='243380'>that</span> <span m='243560'>they're</span>
  <span m='243700'>all</span> <span m='243930'>the</span> <span m='244070'>same.</span>
  <span m='245660'>That</span> <span m='245850'>all</span> <span m='246150'>frequencies</span>
  <span m='246890'>are</span> <span m='247050'>in</span> <span m='247210'>the</span>
  <span m='247330'>delta</span> <span m='247700'>function</span> <span m='248140'>to</span>
  <span m='248220'>the</span> <span m='248350'>same</span> <span m='248670'>amount.</span>
  <span m='249350'>I</span> <span m='249450'>mean</span> <span m='249630'>that's</span>
  <span m='249910'>kind of</span> <span m='250270'>nice.</span> <span m='252220'>We</span>
  <span m='252500'>created</span> <span m='252950'>the</span> <span m='253070'>delta</span>
  <span m='253460'>function</span> <span m='253920'>for</span> <span m='254100'>other</span>
  <span m='254380'>reasons,</span> <span m='255040'>but</span> <span m='255240'>then</span>
  <span m='255810'>here</span> <span m='256170'>in</span> <span m='256370'>Fourier</span>
  <span m='256860'>space</span> <span m='257330'>it's</span> <span m='257610'>just</span>
  <span m='259580'>clean</span> <span m='259950'>as</span> <span m='260140'>could</span>
  <span m='260330'>be.</span> <span m='261190'>And</span> <span m='261500'>we'll</span>
  <span m='261780'>expect</span> <span m='262230'>something</span> <span m='262630'>here,</span>
  <span m='262860'>too.</span> </p><p><span m='263470'>You</span> <span m='263650'>remember</span>
  <span m='263970'>what</span> <span m='264160'>F</span> <span m='264410'>inverse</span>
  <span m='265700'>is?</span> <span m='265960'>F inverse is</span> <span m='266870'>1/N,</span>
  <span m='268520'>instead</span> <span m='268930'>of</span> <span m='269080'>1/2pi,</span>
  <span m='270630'>and</span> <span m='270830'>then</span> <span m='271530'>the</span>
  <span m='271690'>entries</span> <span m='272180'>of</span> <span m='272280'>F</span>
  <span m='272570'>inverse</span> <span m='274610'>come</span> <span m='274910'>from</span>
  <span m='275140'>F</span> <span m='275410'>bar,</span> <span m='276630'>the</span>
  <span m='276820'>conjugate.</span> <span m='278190'>So</span> <span m='278370'>it's</span>
  <span m='278570'>just</span> <span m='278810'>one,</span> <span m='279120'>one,</span>
  <span m='279450'>one,</span> <span m='280040'>minus--</span> <span m='281120'>Well,</span>
  <span m='281630'>I've</span> <span m='282470'>made</span> <span m='282720'>it</span>
  <span m='282840'>four</span> <span m='283140'>by</span> <span m='283350'>four</span>
  <span m='283750'>here.</span> <span m='284360'>This</span> <span m='284620'>is</span>
  <span m='284770'>minus</span> <span m='286700'>omega--</span> <span m='288020'>No,</span>
  <span m='288390'>it</span> <span m='288530'>isn't</span> <span m='288930'>minus</span>
  <span m='289400'>omega.</span> <span m='290970'>It's</span> <span m='292170'>it's</span>
  <span m='292430'>omega</span> <span m='292930'>bar,</span> <span m='295610'>which</span>
  <span m='295930'>is</span> <span m='296070'>minus</span> <span m='296960'>i, in</span>
  <span m='297210'>this</span> <span m='297460'>case.</span> <span m='298620'>Omega</span>
  <span m='299140'>bar,</span> <span m='299580'>so</span> <span m='299730'>it's</span>
  <span m='299860'>minus</span> <span m='300360'>i,</span> <span m='300790'>that's</span>
  <span m='301230'>omega</span> <span m='301550'>bar.</span> <span m='302390'>And</span>
  <span m='302660'>the next</span> <span m='302950'>one</span> <span m='303080'>would</span>
  <span m='303330'>be</span> <span m='303770'>omega</span> <span m='304200'>bar</span>
  <span m='304500'>squared,</span> <span m='304970'>and</span> <span m='305160'>cubed,</span>
  <span m='305950'>and</span> <span m='306110'>so on.</span> <span m='309530'>All</span>
  <span m='309810'>the</span> <span m='309890'>way</span> <span m='310030'>up</span>
  <span m='310220'>to</span> <span m='310350'>the</span> <span m='310460'>ninth</span>
  <span m='310800'>power.</span> <span m='312140'>But</span> <span m='312350'>we're</span>
  <span m='312540'>multiplying</span> <span m='313300'>by</span> <span m='313640'>one,</span>
  <span m='314030'>zero,</span> <span m='314350'>zero,</span> <span m='314710'>so</span>
  <span m='314900'>none</span> <span m='315180'>of</span> <span m='315270'>that</span>
  <span m='315580'>matters.</span> <span m='319580'>What's</span> <span m='319890'>the</span>
  <span m='320010'>answer?</span> <span m='324400'>I'm</span> <span m='324740'>doing</span>
  <span m='325060'>this</span> <span m='326130'>discrete</span> <span m='326600'>Fourier</span>
  <span m='326910'>transform,</span> <span m='327640'>so I'm</span> <span m='327830'>multiplying</span>
  <span m='328430'>by</span> <span m='328610'>the</span> <span m='328750'>matrix</span>
  <span m='329370'>with</span> <span m='330460'>the</span> <span m='330530'>complex</span>
  <span m='331030'>conjugate</span> <span m='331620'>guys.</span> <span m='332720'>But</span>
  <span m='333420'>I'm</span> <span m='333600'>multiplying</span> <span m='333790'>by
  that</span> <span m='334000'>simple</span> <span m='334430'>thing</span> <span m='334720'>so</span>
  <span m='334820'>it's</span> <span m='334970'>just</span> <span m='335180'>going
  to</span> <span m='335370'>pick</span> <span m='335630'>out</span> <span m='336080'>the</span>
  <span m='336310'>zeroth</span> <span m='336720'>column.</span> <span m='337840'>In</span>
  <span m='338060'>other</span> <span m='338270'>words,</span> <span m='338670'>constant.</span>
  <span m='340440'>All</span> <span m='341080'>the</span> <span m='342650'>discrete</span>
  <span m='342890'>Fourier</span> <span m='343550'>coefficients</span> <span m='344270'>of
  the</span> <span m='344500'>discrete</span> <span m='344960'>delta</span> <span
  m='345360'>are</span> <span m='345520'>the</span> <span m='345650'>same.</span>
  <span m='346200'>Just</span> <span m='346560'>again.</span> <span m='347350'>And</span>
  <span m='347690'>what</span> <span m='347900'>are</span> <span m='348100'>they?</span>
  <span m='349470'>So</span> <span m='349680'>it</span> <span m='349840'>picks</span>
  <span m='350140'>out</span> <span m='350360'>this</span> <span m='350590'>column,</span>
  <span m='351110'>but</span> <span m='351280'>of</span> <span m='351390'>course</span>
  <span m='351690'>it</span> <span m='351800'>divides</span> <span m='352300'>by N,</span>
  <span m='352970'>so</span> <span m='353140'>the</span> <span m='353290'>answer</span>
  <span m='353700'>was</span> <span m='354750'>1/N</span> <span m='356670'>[1,</span>
  <span m='357330'>1,</span> <span m='357680'>1,</span> <span m='358150'>1].</span>
  <span m='358450'>It's</span> <span m='359250'>just</span> <span m='359630'>constant</span>
  <span m='360570'>with</span> <span m='360910'>the</span> <span m='361020'>1/N,</span>
  <span m='361870'>where</span> <span m='362790'>in</span> <span m='362980'>the</span>
  <span m='363090'>continuous</span> <span m='363720'>case</span> <span m='364020'>we</span>
  <span m='364160'>had</span> <span m='364420'>1/(2pi).</span> <span m='365450'>No</span>
  <span m='365770'>problem.</span> <span m='366880'>OK.</span> <span m='368090'>And,</span>
  <span m='368410'>of</span> <span m='368540'>course,</span> <span m='370020'>everybody</span>
  <span m='370550'>knows,</span> <span m='370950'>suppose</span> <span m='371560'>that
  I</span> <span m='371870'>now</span> <span m='372160'>start</span> <span m='372510'>with</span>
  <span m='372630'>these</span> <span m='373090'>coefficients</span> <span m='373900'>and</span>
  <span m='374150'>add</span> <span m='374420'>back</span> <span m='375410'>to</span>
  <span m='375570'>get</span> <span m='375790'>the</span> <span m='375940'>function.</span>
  <span m='376800'>What</span> <span m='377040'>would</span> <span m='377220'>I</span>
  <span m='377320'>get?</span> <span m='380110'>Because,</span> <span m='380470'>just</span>
  <span m='380810'>to</span> <span m='380910'>be</span> <span m='381040'>sure</span>
  <span m='381300'>that</span> <span m='381460'>we</span> <span m='381610'>believe</span>
  <span m='382300'>that</span> <span m='383050'>F</span> <span m='383410'>and</span>
  <span m='383640'>F</span> <span m='383900'>inverse</span> <span m='384370'>really</span>
  <span m='384760'>are</span> <span m='385030'>what</span> <span m='385280'>they</span>
  <span m='385720'>are</span> <span m='385840'>supposed</span> <span m='386210'>to</span>
  <span m='386300'>be.</span> <span m='386890'>If</span> <span m='387070'>I</span>
  <span m='387940'>start</span> <span m='388270'>with</span> <span m='388400'>these</span>
  <span m='388640'>coefficients,</span> <span m='389870'>add</span> <span m='390220'>back</span>
  <span m='391850'>to</span> <span m='392940'>put</span> <span m='393240'>those</span>
  <span m='393600'>in</span> <span m='393840'>here</span> <span m='394220'>and</span>
  <span m='394900'>reconstruct,</span> <span m='396470'>so</span> <span m='396870'>1/N</span>
  <span m='397790'>[</span> <span m='398380'>1,</span> <span m='399040'>1,</span>
  <span m='399490'>1],</span> <span m='400570'>what</span> <span m='400780'>will</span>
  <span m='400980'>I</span> <span m='401070'>get?</span> <span m='403510'>Well, what</span>
  <span m='404070'>am</span> <span m='404170'>I</span> <span m='404260'>supposed</span>
  <span m='404630'>to</span> <span m='404740'>get?</span> <span m='406960'>The</span>
  <span m='407100'>delta,</span> <span m='407590'>right?</span> <span m='407920'>I'm</span>
  <span m='408070'>supposed</span> <span m='408390'>to</span> <span m='408480'>get</span>
  <span m='408680'>back</span> <span m='409040'>to</span> <span m='409200'>y.</span>
  <span m='410900'>If</span> <span m='411130'>I</span> <span m='411310'>started</span>
  <span m='412950'>with</span> <span m='413110'>that,</span> <span m='413880'>did
  F</span> <span m='414150'>inverse</span> <span m='414900'>to</span> <span m='415010'>get</span>
  <span m='415200'>the</span> <span m='415300'>coefficients,</span> <span m='416070'>that</span>
  <span m='416270'>was</span> <span m='416470'>the</span> <span m='416570'>discrete</span>
  <span m='416990'>Fourier</span> <span m='417280'>transform,</span> <span m='418310'>now</span>
  <span m='418590'>I</span> <span m='418720'>add</span> <span m='419020'>back</span>
  <span m='419830'>to</span> <span m='420000'>get,</span> <span m='421600'>add</span>
  <span m='421900'>the</span> <span m='422010'>Fourier</span> <span m='422350'>series</span>
  <span m='422780'>up</span> <span m='422970'>again</span> <span m='423480'>to</span>
  <span m='423640'>come</span> <span m='423860'>back</span> <span m='424140'>here,</span>
  <span m='424410'>well</span> <span m='424620'>I'll</span> <span m='424760'>certainly</span>
  <span m='425130'>get</span> <span m='425390'>[1,</span> <span m='425670'>0,</span>
  <span m='426020'>0,</span> <span m='426370'>0],</span> <span m='427250'>and</span>
  <span m='428350'>you</span> <span m='428620'>see</span> <span m='428850'>why?</span>
  <span m='429820'>If</span> <span m='430010'>I</span> <span m='430220'>multiply</span>
  <span m='430420'>F,</span> <span m='432390'>that</span> <span m='432610'>zeroth</span>
  <span m='432910'>row</span> <span m='433170'>of</span> <span m='433600'>F is</span>
  <span m='434030'>[1,</span> <span m='434320'>1,</span> <span m='434530'>1,</span>
  <span m='434800'>1],</span> <span m='435540'>times</span> <span m='435850'>[1,</span>
  <span m='436140'>1,</span> <span m='436380'>1,</span> <span m='436650'>1]</span>
  <span m='436930'>will</span> <span m='437120'>give</span> <span m='437290'>me</span>
  <span m='437530'>N.</span> <span m='438440'>The</span> <span m='438630'>N</span>
  <span m='438980'>will</span> <span m='439140'>cancel.</span> <span m='439970'>I</span>
  <span m='440100'>get</span> <span m='440340'>the</span> <span m='440440'>one.</span>
  <span m='441240'>And</span> <span m='441550'>all</span> <span m='441750'>the</span>
  <span m='441900'>other</span> <span m='442620'>guys</span> <span m='443830'>add</span>
  <span m='444240'>to</span> <span m='444360'>zeroes.</span> <span m='445260'>So,</span>
  <span m='445970'>sure</span> <span m='446210'>enough,</span> <span m='446630'>it
  works.</span> <span m='451870'>We're</span> <span m='452010'>really</span> <span
  m='452320'>just</span> <span m='452830'>seeing</span> <span m='453450'>an</span>
  <span m='453720'>example,</span> <span m='454240'>an important</span> <span m='454790'>example</span>
  <span m='455680'>of</span> <span m='456590'>the</span> <span m='456720'>DFT.</span>
  <span m='457730'>And</span> <span m='458200'>the</span> <span m='458340'>homework,</span>
  <span m='458810'>then,</span> <span m='459080'>would</span> <span m='459270'>have</span>
  <span m='459540'>some</span> <span m='459780'>other</span> <span m='460030'>examples.</span>
  <span m='460940'>But</span> <span m='461370'>I've</span> <span m='461590'>forgotten</span>
  <span m='462020'>whether</span> <span m='462310'>the</span> <span m='462410'>homework</span>
  <span m='462930'>has</span> <span m='463910'>this</span> <span m='464300'>example.</span>
  </p><p><span m='464970'>But</span> <span m='465210'>let's</span> <span m='466080'>think</span>
  <span m='466330'>about</span> <span m='466620'>it</span> <span m='466750'>now.</span>
  <span m='467370'>Suppose</span> <span m='470640'>that's</span> <span m='470940'>my</span>
  <span m='471110'>function</span> <span m='471620'>value</span> <span m='471980'>instead.</span>
  <span m='474050'>OK,</span> <span m='474610'>so</span> <span m='474940'>now</span>
  <span m='475420'>I'm</span> <span m='475830'>starting</span> <span m='476560'>with</span>
  <span m='476820'>the</span> <span m='476920'>delta.</span> <span m='479210'>Again</span>
  <span m='479590'>it's</span> <span m='479790'>a</span> <span m='479870'>delta,</span>
  <span m='480270'>but</span> <span m='480440'>it's</span> <span m='480980'>moved</span>
  <span m='481320'>over.</span> <span m='482520'>And</span> <span m='482750'>I</span>
  <span m='482860'>could</span> <span m='483080'>ask,</span> <span m='483860'>I</span>
  <span m='483980'>really</span> <span m='484310'>should</span> <span m='484550'>ask</span>
  <span m='484820'>first,</span> <span m='485890'>in</span> <span m='486040'>the</span>
  <span m='486140'>continuous</span> <span m='486860'>case,</span> <span m='487600'>suppose</span>
  <span m='488300'>I,</span> <span m='489020'>I</span> <span m='489150'>can</span>
  <span m='489370'>do</span> <span m='489520'>it</span> <span m='489700'>with</span>
  <span m='490350'>just</span> <span m='491650'>a</span> <span m='491760'>little</span>
  <span m='492110'>erasing</span> <span m='492720'>here.</span> <span m='493250'>Let</span>
  <span m='493400'>me</span> <span m='493530'>do</span> <span m='493700'>the</span>
  <span m='493840'>continuous</span> <span m='494560'>case</span> <span m='494900'>for</span>
  <span m='495070'>the</span> <span m='495230'>delta</span> <span m='495630'>that</span>
  <span m='495780'>we</span> <span m='496020'>met</span> <span m='496400'>first</span>
  <span m='496860'>in</span> <span m='496980'>this</span> <span m='497210'>course.</span>
  <span m='498000'>I'll</span> <span m='498230'>shift</span> <span m='498660'>it</span>
  <span m='498850'>to</span> <span m='499040'>a.</span> <span m='500150'>If</span>
  <span m='500360'>I</span> <span m='500470'>shift</span> <span m='500950'>the</span>
  <span m='501040'>delta</span> <span m='501490'>function</span> <span m='502570'>to</span>
  <span m='502690'>a</span> <span m='502810'>point</span> <span m='503210'>a,</span>
  <span m='505650'>well,</span> <span m='506030'>I</span> <span m='506180'>said</span>
  <span m='506470'>we'd</span> <span m='506710'>met</span> <span m='506950'>the</span>
  <span m='507070'>delta</span> <span m='507480'>function</span> <span m='507950'>first</span>
  <span m='508330'>in</span> <span m='508430'>this</span> <span m='508660'>course.</span>
  <span m='509070'>At</span> <span m='509940'>a,</span> <span m='510450'>good.</span>
  <span m='511130'>But</span> <span m='512290'>when</span> <span m='512500'>we</span>
  <span m='512630'>did</span> <span m='513320'>it</span> <span m='513470'>wasn't</span>
  <span m='513880'>2pi</span> <span m='514330'>periodic.</span> <span m='515680'>So</span>
  <span m='515900'>we</span> <span m='516090'>still</span> <span m='516440'>have,</span>
  <span m='516860'>in</span> <span m='516990'>fact,</span> <span m='518090'>the</span>
  <span m='518240'>Fourier</span> <span m='518750'>integrals</span> <span m='519560'>next</span>
  <span m='519980'>week.</span> <span m='521020'>Will</span> <span m='521190'>have</span>
  <span m='521420'>a</span> <span m='521510'>similar</span> <span m='521990'>formula.</span>
  <span m='522750'>The</span> <span m='522910'>integral</span> <span m='523300'>will</span>
  <span m='523440'>go</span> <span m='523640'>from</span> <span m='523900'>minus</span>
  <span m='524290'>infinity</span> <span m='524770'>to</span> <span m='524920'>infinity</span>
  <span m='525810'>and</span> <span m='526010'>then</span> <span m='526200'>we'll</span>
  <span m='526410'>have</span> <span m='527180'>the</span> <span m='527330'>real</span>
  <span m='527610'>delta,</span> <span m='528070'>not</span> <span m='528440'>periodic.</span>
  <span m='529130'>Here,</span> <span m='529330'>we</span> <span m='529470'>have,</span>
  <span m='530300'>and</span> <span m='530650'>people</span> <span m='531000'>call</span>
  <span m='531320'>it</span> <span m='531550'>a</span> <span m='531680'>train</span>
  <span m='532200'>of</span> <span m='532340'>deltas.</span> <span m='533320'>A</span>
  <span m='533660'>train</span> <span m='534160'>of</span> <span m='534310'>spikes.</span>
  <span m='535880'>Sort</span> <span m='536120'>of</span> <span m='536210'>you</span>
  <span m='536320'>have</span> <span m='536680'>one</span> <span m='537040'>every</span>
  <span m='537360'>2pi.</span> <span m='538180'>Anyway,</span> <span m='539240'>that's</span>
  <span m='539500'>what</span> <span m='539680'>we've</span> <span m='539850'>got.</span>
  <span m='540180'>Now,</span> <span m='540400'>you</span> <span m='540790'>can</span>
  <span m='540960'>see</span> <span m='541170'>the</span> <span m='541290'>answer.</span>
  <span m='543840'>This</span> <span m='544120'>is</span> <span m='544400'>like</span>
  <span m='544860'>perfect</span> <span m='545320'>practice</span> <span m='545900'>in</span>
  <span m='546730'>doing</span> <span m='547260'>an</span> <span m='547470'>integral</span>
  <span m='547720'>with a</span> <span m='548020'>delta.</span> <span m='549450'>What's</span>
  <span m='551120'>the</span> <span m='551300'>integral</span> <span m='551450'>equal?</span>
  <span m='555220'>Well,</span> <span m='555510'>the</span> <span m='555740'>spike</span>
  <span m='556140'>is</span> <span m='556320'>at</span> <span m='556490'>x=a.</span>
  <span m='558830'>So</span> <span m='559090'>it</span> <span m='559200'>picks out</span>
  <span m='559890'>this</span> <span m='560710'>function</span> <span m='561350'>at</span>
  <span m='562040'>x=a,</span> <span m='562800'>which is</span> <span m='564830'>e^(-ika).</span>
  <span m='570640'>So</span> <span m='570850'>not</span> <span m='571130'>constant</span>
  <span m='571660'>any more.</span> <span m='572540'>They</span> <span m='572710'>depend</span>
  <span m='573220'>on</span> <span m='573480'>k.</span> <span m='575370'>The</span>
  <span m='575500'>1/(2pi)</span> <span m='575690'>is</span> <span m='576440'>still</span>
  <span m='576760'>there.</span> <span m='578210'>So</span> <span m='578480'>it's--</span>
  <span m='578770'>But</span> <span m='579040'>still,</span> <span m='580140'>the</span>
  <span m='580570'>delta</span> <span m='580940'>function</span> <span m='581430'>shifted</span>
  <span m='581850'>over.</span> <span m='583270'>I</span> <span m='583450'>mean,</span>
  <span m='583680'>it</span> <span m='583820'>didn't</span> <span m='584090'>change</span>
  <span m='584500'>energy.</span> <span m='585060'>It</span> <span m='585190'>didn't</span>
  <span m='585480'>change,</span> <span m='585910'>it</span> <span m='586040'>just</span>
  <span m='586420'>changed</span> <span m='587010'>phase,</span> <span m='587580'>so</span>
  <span m='587770'>to</span> <span m='587910'>speak.</span> <span m='589820'>And</span>
  <span m='590370'>we</span> <span m='590540'>see</span> <span m='590840'>that--</span>
  <span m='591830'>I</span> <span m='592040'>would</span> <span m='592350'>call</span>
  <span m='592660'>this</span> <span m='593450'>like</span> <span m='593820'>a</span>
  <span m='593920'>modulation.</span> <span m='600780'>So</span> <span m='600940'>it's</span>
  <span m='601490'>staying</span> <span m='601830'>of</span> <span m='601940'>absolute</span>
  <span m='602370'>value</span> <span m='602710'>one,</span> <span m='603170'>still.</span>
  <span m='604250'>But</span> <span m='604440'>it's</span> <span m='604640'>not</span>
  <span m='604940'>the</span> <span m='605040'>number</span> <span m='605390'>one,</span>
  <span m='605760'>it's</span> <span m='606030'>going</span> <span m='606330'>around</span>
  <span m='606710'>the</span> <span m='606810'>circle.</span> <span m='607790'>Going</span>
  <span m='608110'>around</span> <span m='608510'>the</span> <span m='608620'>unit</span>
  <span m='608940'>circle.</span> <span m='610480'>So</span> <span m='611410'>it's</span>
  <span m='611590'>a</span> <span m='611690'>phase</span> <span m='612120'>factor,</span>
  <span m='612880'>right.</span> <span m='613700'>And</span> <span m='613900'>that's</span>
  <span m='614160'>what</span> <span m='614370'>I'm</span> <span m='614600'>going
  to</span> <span m='614840'>expect</span> <span m='615300'>to</span> <span m='615410'>see</span>
  <span m='615740'>here</span> <span m='615970'>in</span> <span m='616080'>the</span>
  <span m='616190'>discrete</span> <span m='616640'>case</span> <span m='617000'>too.</span>
  <span m='617700'>If</span> <span m='617960'>I</span> <span m='618580'>do</span>
  <span m='618780'>this</span> <span m='619030'>multiplication</span> <span m='619920'>by</span>
  <span m='620320'>one</span> <span m='620960'>there,</span> <span m='621690'>it</span>
  <span m='621980'>picks</span> <span m='622320'>out</span> <span m='622670'>this</span>
  <span m='623050'>column,</span> <span m='623760'>right?</span> <span m='624610'>That</span>
  <span m='624840'>one</span> <span m='625290'>will</span> <span m='625490'>pick</span>
  <span m='625700'>out</span> <span m='625910'>this</span> <span m='626180'>column,</span>
  <span m='626840'>so</span> <span m='627060'>you</span> <span m='627260'>see</span>
  <span m='627580'>it's--</span> <span m='628820'>Maybe</span> <span m='629160'>I</span>
  <span m='629860'>come</span> <span m='630100'>up</span> <span m='630270'>here</span>
  <span m='630550'>now.</span> <span m='631600'>Shall</span> <span m='631980'>I</span>
  <span m='632110'>just--</span> <span m='633200'>When</span> <span m='633380'>I</span>
  <span m='633440'>pick</span> <span m='633710'>out</span> <span m='633900'>that</span>
  <span m='634190'>column,</span> <span m='639500'>the</span> <span m='639690'>answer</span>
  <span m='640220'>then,</span> <span m='641190'>I</span> <span m='641310'>guess</span>
  <span m='641580'>I've</span> <span m='641700'>got</span> <span m='641910'>the</span>
  <span m='642080'>column</span> <span m='643070'>circle,</span> <span m='644870'>there</span>
  <span m='645220'>it</span> <span m='645320'>is.</span> <span m='645580'>Minus</span>
  <span m='646020'>i,</span> <span m='646720'>minus</span> <span m='647020'>i</span>
  <span m='647570'>squared,</span> <span m='648280'>minus</span> <span m='648540'>i</span>
  <span m='648650'>cubed.</span> <span m='649740'>You</span> <span m='649950'>see</span>
  <span m='650160'>it's</span> <span m='650330'>like</span> <span m='650680'>k</span>
  <span m='650900'>equals</span> <span m='651330'>zero,</span> <span m='651710'>one,</span>
  <span m='652070'>two,</span> <span m='652370'>three.</span> <span m='653430'>Just</span>
  <span m='653680'>the</span> <span m='653780'>way</span> <span m='653940'>here,</span>
  <span m='654270'>we</span> <span m='654470'>had</span> <span m='654880'>k,</span>
  <span m='655800'>well</span> <span m='656190'>we</span> <span m='656330'>had</span>
  <span m='658020'>all</span> <span m='658310'>integers</span> <span m='658870'>k</span>
  <span m='659240'>in</span> <span m='659450'>that</span> <span m='660330'>function</span>
  <span m='660840'>case.</span> <span m='661570'>Here</span> <span m='661850'>we've</span>
  <span m='662060'>got</span> <span m='662430'>four</span> <span m='662760'>integers,</span>
  <span m='663350'>k equals</span> <span m='663990'>zero,</span> <span m='664270'>one,</span>
  <span m='664560'>two,</span> <span m='664790'>and</span> <span m='664980'>three,</span>
  <span m='665750'>but</span> <span m='665950'>again</span> <span m='666410'>it's</span>
  <span m='666660'>the</span> <span m='666810'>minus</span> <span m='667460'>i,</span>
  <span m='668130'>it's</span> <span m='668430'>the</span> <span m='668620'>e</span>
  <span m='669090'>to the,</span> <span m='670250'>it's</span> <span m='670540'>the</span>
  <span m='670700'>w</span> <span m='671250'>bar.</span> <span m='673250'>In</span>
  <span m='673640'>other</span> <span m='673830'>words,</span> <span m='674080'>the</span>
  <span m='674420'>answer</span> <span m='674810'>was</span> <span m='676080'>one,</span>
  <span m='676810'>w</span> <span m='677260'>bar,</span> <span m='677810'>w</span>
  <span m='678180'>bar</span> <span m='678510'>squared,</span> <span m='678880'>w</span>
  <span m='679250'>bar</span> <span m='679580'>cubed.</span> <span m='679920'>Just</span>
  <span m='680410'>the</span> <span m='680970'>powers</span> <span m='681630'>of</span>
  <span m='681920'>w</span> <span m='683320'>with</span> <span m='683560'>this</span>
  <span m='683770'>factor</span> <span m='684220'>1/N.</span> <span m='685290'>Here</span>
  <span m='685630'>we</span> <span m='685780'>had a</span> <span m='686480'>modulation.</span>
  <span m='688280'>It's</span> <span m='689020'>the</span> <span m='689160'>same</span>
  <span m='689460'>picture.</span> <span m='691590'>Absolute</span> <span m='692010'>value's</span>
  <span m='692460'>one.</span> </p><p><span m='693060'>And</span> <span m='693310'>and</span>
  <span m='693580'>what</span> <span m='693780'>about</span> <span m='694070'>energy?</span>
  <span m='694520'>Having</span> <span m='694860'>mentioned</span> <span m='695310'>energy,</span>
  <span m='698360'>so</span> <span m='698580'>that's</span> <span m='698900'>another</span>
  <span m='700240'>key</span> <span m='700620'>rule.</span> <span m='702070'>The</span>
  <span m='702220'>key</span> <span m='702530'>rules</span> <span m='702980'>for</span>
  <span m='704040'>the</span> <span m='705260'>Fourier</span> <span m='705770'>series,</span>
  <span m='706470'>just</span> <span m='706850'>let's</span> <span m='707100'>think</span>
  <span m='707410'>back.</span> <span m='707730'>What</span> <span m='707950'>were</span>
  <span m='708090'>the</span> <span m='708240'>key</span> <span m='708870'>rules?</span>
  <span m='709720'>First,</span> <span m='710130'>the</span> <span m='710230'>rule</span>
  <span m='710530'>to</span> <span m='710630'>find</span> <span m='711030'>the</span>
  <span m='711120'>coefficients.</span> <span m='712020'>Good.</span> <span m='713040'>Then</span>
  <span m='713520'>the</span> <span m='713620'>rule</span> <span m='714040'>for</span>
  <span m='714260'>the</span> <span m='714440'>derivatives.</span> <span m='716010'>This</span>
  <span m='716230'>is</span> <span m='716880'>so</span> <span m='717160'>important.</span>
  <span m='719970'>These</span> <span m='720650'>are</span> <span m='720780'>rules.</span>
  <span m='723070'>Let's</span> <span m='723340'>say,</span> <span m='723550'>for</span>
  <span m='723780'>Fourier</span> <span m='724270'>series.</span> <span m='725510'>For</span>
  <span m='725750'>Fourier</span> <span m='726190'>series.</span> <span m='728560'>Let's</span>
  <span m='728830'>just</span> <span m='729720'>make</span> <span m='730040'>this</span>
  <span m='730260'>a</span> <span m='730350'>quick</span> <span m='730690'>review.</span>
  <span m='731850'>What</span> <span m='732420'>were</span> <span m='732580'>the</span>
  <span m='732770'>important</span> <span m='733300'>rules?</span> <span m='734380'>The</span>
  <span m='734520'>important</span> <span m='735020'>rules</span> <span m='735380'>were,</span>
  <span m='736710'>if</span> <span m='736960'>I</span> <span m='737070'>had</span>
  <span m='737380'>the</span> <span m='737480'>Fourier</span> <span m='737800'>series</span>
  <span m='738250'>of</span> <span m='738350'>f.</span> <span m='738590'>Start</span>
  <span m='739030'>with</span> <span m='739200'>the</span> <span m='739290'>Fourier</span>
  <span m='739640'>series</span> <span m='739800'>of f.</span> <span m='740680'>Then</span>
  <span m='741340'>the</span> <span m='741530'>question</span> <span m='742000'>was,</span>
  <span m='742340'>what's</span> <span m='742710'>the</span> <span m='742860'>Fourier</span>
  <span m='743270'>series</span> <span m='743750'>of</span> <span m='744320'>df/dx.</span>
  <span m='748070'>And</span> <span m='748290'>now</span> <span m='748510'>I'm</span>
  <span m='748670'>saying</span> <span m='749470'>the</span> <span m='750130'>next</span>
  <span m='750620'>important</span> <span m='751170'>rule</span> <span m='751580'>is</span>
  <span m='751920'>the</span> <span m='752090'>Fourier</span> <span m='752470'>series</span>
  <span m='752950'>of</span> <span m='753130'>f</span> <span m='753500'>shifted.</span>
  <span m='758170'>And</span> <span m='758480'>then</span> <span m='758780'>the</span>
  <span m='758950'>last</span> <span m='759420'>important</span> <span m='760010'>rule</span>
  <span m='760380'>is</span> <span m='760640'>the</span> <span m='760780'>energy.</span>
  <span m='765530'>OK,</span> <span m='766260'>and</span> <span m='766480'>let's</span>
  <span m='766750'>just,</span> <span m='767100'>maybe</span> <span m='767710'>this</span>
  <span m='768430'>is a</span> <span m='768600'>bad</span> <span m='768920'>idea</span>
  <span m='769340'>to,</span> <span m='769830'>since</span> <span m='770110'>we're</span>
  <span m='770290'>kind of</span> <span m='771050'>doing</span> <span m='771360'>all</span>
  <span m='771930'>of</span> <span m='772720'>Fourier</span> <span m='774020'>in,</span>
  <span m='775510'>it's</span> <span m='775680'>coming</span> <span m='776010'>in</span>
  <span m='776150'>three</span> <span m='776430'>parts.</span> <span m='777700'>Functions,</span>
  <span m='779340'>discrete,</span> <span m='780490'>integrals,</span> <span m='781660'>but</span>
  <span m='784590'>they all</span> <span m='784920'>match.</span> <span m='785840'>So</span>
  <span m='788580'>this</span> <span m='788780'>is</span> <span m='788930'>what</span>
  <span m='789130'>happens</span> <span m='789530'>to</span> <span m='789620'>the</span>
  <span m='789760'>function.</span> <span m='790560'>What</span> <span m='790830'>happens</span>
  <span m='791290'>to</span> <span m='791390'>the</span> <span m='791510'>coefficient?</span>
  <span m='792260'>So</span> <span m='792650'>this</span> <span m='793670'>starts</span>
  <span m='794080'>with</span> <span m='794330'>coefficient</span> <span m='794600'>c_k,</span>
  <span m='796130'>for</span> <span m='797110'>f,</span> <span m='798170'>what</span>
  <span m='798590'>are</span> <span m='798680'>the</span> <span m='799030'>coefficients</span>
  <span m='799450'>for</span> <span m='799730'>the</span> <span m='799840'>derivative,</span>
  <span m='800410'>just</span> <span m='800740'>remind</span> <span m='801140'>me?</span>
  <span m='802580'>If</span> <span m='804190'>f(x),</span> <span m='805040'>so</span>
  <span m='805250'>I'm</span> <span m='805400'>starting</span> <span m='805930'>with</span>
  <span m='806220'>f(x)</span> <span m='807070'>equals</span> <span m='807600'>sum</span>
  <span m='807960'>of</span> <span m='809680'>c_k*e^(ikx).</span> <span m='812480'>Start</span>
  <span m='812870'>with</span> <span m='813010'>that.</span> <span m='813660'>And</span>
  <span m='813880'>now</span> <span m='814200'>take</span> <span m='814480'>the</span>
  <span m='814620'>derivative.</span> <span m='815740'>When</span> <span m='815900'>I</span>
  <span m='816000'>take</span> <span m='816260'>the derivative,</span> <span m='816960'>down</span>
  <span m='817310'>comes</span> <span m='817620'>ik.</span> <span m='819000'>So</span>
  <span m='819440'>you</span> <span m='819570'>remember</span> <span m='820020'>that</span>
  <span m='820310'>rule.</span> <span m='821370'>Those</span> <span m='821640'>are</span>
  <span m='821720'>the</span> <span m='821860'>Fourier</span> <span m='822220'>coefficients</span>
  <span m='822880'>of the</span> <span m='823140'>derivative.</span> <span m='824050'>Now</span>
  <span m='824280'>what's</span> <span m='824600'>the</span> <span m='824730'>Fourier</span>
  <span m='825040'>coefficients</span> <span m='825690'>of</span> <span m='825830'>the</span>
  <span m='825950'>shift?</span> <span m='827150'>If</span> <span m='827380'>I've</span>
  <span m='827690'>just</span> <span m='828070'>shifted,</span> <span m='828650'>translated</span>
  <span m='829440'>the</span> <span m='829570'>function,</span> <span m='830790'>if</span>
  <span m='831220'>my</span> <span m='831410'>original</span> <span m='831920'>x</span>
  <span m='832370'>was</span> <span m='832600'>this,</span> <span m='834910'>now</span>
  <span m='835190'>let</span> <span m='835360'>me</span> <span m='835480'>look</span>
  <span m='835710'>at</span> <span m='835820'>f(x-a).</span> <span m='836880'>You'll</span>
  <span m='838340'>see</span> <span m='838600'>it.</span> <span m='839090'>It'll</span>
  <span m='839340'>jump</span> <span m='839700'>out</span> <span m='839920'>at</span>
  <span m='840080'>us,</span> <span m='840430'>it'll</span> <span m='840640'>be</span>
  <span m='840750'>a sum</span> <span m='841800'>of</span> <span m='841970'>the</span>
  <span m='842110'>same</span> <span m='843690'>c_k's</span> <span m='845900'>e^(ik(x-a)).</span>
  <span m='849450'>So</span> <span m='849660'>what</span> <span m='849850'>are</span>
  <span m='849940'>the</span> <span m='850060'>Fourier</span> <span m='850270'>coefficients</span>
  <span m='850750'>of</span> <span m='851150'>that?</span> <span m='852650'>Well</span>
  <span m='852880'>there</span> <span m='853090'>is</span> <span m='853240'>the</span>
  <span m='853330'>e^(ikx).</span> <span m='855260'>Whatever's</span> <span m='855750'>multiplying</span>
  <span m='856440'>it</span> <span m='856540'>has</span> <span m='856690'>got to</span>
  <span m='856970'>be</span> <span m='857120'>the</span> <span m='857280'>Fourier</span>
  <span m='857870'>coefficient,</span> <span m='858400'>and</span> <span m='858660'>we</span>
  <span m='858790'>see</span> <span m='858980'>it</span> <span m='859130'>is</span>
  <span m='859310'>c_k</span> <span m='860430'>times</span> <span m='861440'>e^(ik(-a)).</span>
  <span m='863280'>e^(-ika)</span> <span m='867530'>times</span> <span m='868030'>c_k.</span>
  <span m='870230'>Right?</span> <span m='872470'>And,</span> <span m='872850'>of</span>
  <span m='872940'>course,</span> <span m='873210'>that's</span> <span m='873440'>just</span>
  <span m='873700'>what</span> <span m='873850'>we</span> <span m='873950'>discovered</span>
  <span m='874440'>here.</span> <span m='875540'>That's</span> <span m='875770'>just</span>
  <span m='876050'>what</span> <span m='876190'>we</span> <span m='876330'>found</span>
  <span m='876700'>there,</span> <span m='877000'>that</span> <span m='877220'>when</span>
  <span m='877410'>we</span> <span m='877540'>shifted</span> <span m='878070'>the</span>
  <span m='878190'>delta,</span> <span m='878910'>we've</span> <span m='879250'>multiplied</span>
  <span m='879940'>by</span> <span m='880150'>this</span> <span m='880480'>modulation,</span>
  <span m='882050'>this</span> <span m='882380'>phase</span> <span m='882770'>factor</span>
  <span m='883780'>came</span> <span m='884070'>into</span> <span m='884590'>the</span>
  <span m='885100'>Fourier</span> <span m='885570'>coefficients.</span> </p><p><span
  m='886590'>And</span> <span m='886810'>now</span> <span m='887000'>finally,</span>
  <span m='887470'>the</span> <span m='887640'>energy</span> <span m='888200'>stuff.</span>
  <span m='889030'>You</span> <span m='889240'>remember</span> <span m='889560'>the</span>
  <span m='889770'>energy</span> <span m='890300'>was,</span> <span m='890810'>what's</span>
  <span m='891190'>the</span> <span m='891340'>energy?</span> <span m='892210'>The</span>
  <span m='892490'>integral</span> <span m='892730'>from</span> <span m='892960'>minus</span>
  <span m='893150'>pi to</span> <span m='893730'>pi,</span> <span m='894850'>of</span>
  <span m='895190'>f(x)</span> <span m='895840'>squared</span> <span m='897680'>dx</span>
  <span m='898690'>is</span> <span m='898910'>the</span> <span m='899060'>same</span>
  <span m='899550'>as</span> <span m='900450'>the</span> <span m='900750'>sum</span>
  <span m='901540'>from</span> <span m='901770'>minus</span> <span m='902240'>infinity</span>
  <span m='902990'>to</span> <span m='903110'>infinity</span> <span m='904100'>of</span>
  <span m='904340'>the</span> <span m='904450'>coefficient</span> <span m='905120'>squared.</span>
  <span m='906540'>And</span> <span m='906800'>somebody</span> <span m='907490'>correctly</span>
  <span m='908500'>sent</span> <span m='908790'>me</span> <span m='908900'>an</span>
  <span m='909000'>email</span> <span m='909410'>to</span> <span m='909580'>say</span>
  <span m='910450'>energy</span> <span m='911140'>and</span> <span m='911320'>length</span>
  <span m='911610'>squared</span> <span m='912430'>are</span> <span m='912530'>you</span>
  <span m='912750'>really,</span> <span m='913140'>is</span> <span m='913260'>there</span>
  <span m='913370'>much</span> <span m='913630'>difference?</span> <span m='914320'>No.</span>
  <span m='915240'>No.</span> <span m='916140'>You</span> <span m='916390'>could</span>
  <span m='916560'>say</span> <span m='916760'>length</span> <span m='917120'>squared</span>
  <span m='917620'>here,</span> <span m='917840'>I'm</span> <span m='918030'>just</span>
  <span m='918320'>using</span> <span m='918690'>the</span> <span m='918780'>word</span>
  <span m='919070'>energy.</span> <span m='919910'>Now,</span> <span m='920950'>I</span>
  <span m='921120'>left</span> <span m='921450'>a</span> <span m='921540'>space</span>
  <span m='921930'>because</span> <span m='922130'>I</span> <span m='922280'>know</span>
  <span m='922520'>that</span> <span m='922880'>there's</span> <span m='923030'>a</span>
  <span m='923330'>stupid</span> <span m='923740'>2pi</span> <span m='924210'>somewhere.</span>
  <span m='926700'>Where</span> <span m='927290'>does</span> <span m='927460'>it</span>
  <span m='927610'>come?</span> <span m='929690'>You</span> <span m='929860'>remember</span>
  <span m='930150'>how</span> <span m='930380'>to</span> <span m='930490'>get</span>
  <span m='930810'>this?</span> <span m='932600'>You</span> <span m='932740'>put</span>
  <span m='933060'>that</span> <span m='933270'>whole</span> <span m='933500'>series</span>
  <span m='934040'>in</span> <span m='934220'>there,</span> <span m='935920'>multiply</span>
  <span m='936450'>by</span> <span m='936620'>its</span> <span m='936740'>complex</span>
  <span m='937290'>conjugate</span> <span m='937950'>to</span> <span m='938090'>get</span>
  <span m='938400'>squared.</span> <span m='940520'>And</span> <span m='940980'>integrate.</span>
  <span m='942180'>Right?</span> <span m='942770'>That</span> <span m='942920'>was</span>
  <span m='943070'>the</span> <span m='943160'>idea.</span> <span m='943830'>Isn't</span>
  <span m='944080'>that</span> <span m='944300'>how</span> <span m='944450'>we</span>
  <span m='944660'>figured</span> <span m='945120'>out,</span> <span m='945430'>we</span>
  <span m='945670'>got</span> <span m='945950'>to</span> <span m='946080'>this?</span>
  <span m='946710'>We</span> <span m='947440'>started</span> <span m='947880'>with</span>
  <span m='948040'>this,</span> <span m='948680'>length</span> <span m='948950'>squared.</span>
  <span m='950230'>We</span> <span m='950370'>plugged</span> <span m='950770'>in</span>
  <span m='951290'>the</span> <span m='951380'>Fourier</span> <span m='951700'>series.</span>
  <span m='953280'>This</span> <span m='953550'>is</span> <span m='953700'>f</span>
  <span m='953990'>times</span> <span m='954310'>f</span> <span m='954570'>bar,</span>
  <span m='954990'>so</span> <span m='955180'>that's</span> <span m='955460'>this</span>
  <span m='955810'>times</span> <span m='956130'>its</span> <span m='956290'>conjugate.</span>
  <span m='957770'>And</span> <span m='958100'>we</span> <span m='958230'>integrated,</span>
  <span m='959150'>and</span> <span m='959400'>all</span> <span m='959820'>the</span>
  <span m='960410'>cross</span> <span m='960790'>terms</span> <span m='961230'>vanished.</span>
  <span m='961860'>And</span> <span m='962020'>only</span> <span m='962460'>the</span>
  <span m='962660'>ones</span> <span m='963170'>where</span> <span m='963720'>e^(ikx)</span>
  <span m='964970'>multiplied</span> <span m='965680'>e^(-ikx)</span> <span m='967220'>came.</span>
  <span m='968220'>And</span> <span m='968490'>those</span> <span m='968800'>had</span>
  <span m='969070'>c_k</span> <span m='969690'>squared.</span> <span m='970440'>And</span>
  <span m='970770'>when</span> <span m='970940'>we</span> <span m='971080'>integrated</span>
  <span m='971740'>that</span> <span m='972610'>one,</span> <span m='973210'>we</span>
  <span m='973360'>probably</span> <span m='973780'>got</span> <span m='973990'>a</span>
  <span m='974080'>2pi.</span> <span m='977670'>So</span> <span m='978000'>that's</span>
  <span m='978320'>the</span> <span m='978450'>energy</span> <span m='978990'>inequality,</span>
  <span m='980030'>right.</span> <span m='980710'>For</span> <span m='980970'>functions.</span>
  <span m='981960'>And</span> <span m='982180'>now</span> <span m='982990'>what</span>
  <span m='983290'>I</span> <span m='983370'>was</span> <span m='983660'>going to</span>
  <span m='983920'>say</span> <span m='984170'>is,</span> <span m='984520'>you</span>
  <span m='984840'>shouldn't</span> <span m='985250'>miss</span> <span m='985530'>the</span>
  <span m='985670'>fact</span> <span m='986090'>that</span> <span m='987870'>in the</span>
  <span m='988200'>discrete</span> <span m='988750'>case,</span> <span m='991090'>there'll</span>
  <span m='991350'>be</span> <span m='991500'>a</span> <span m='991590'>similar</span>
  <span m='992530'>energy</span> <span m='993040'>inequality.</span> <span m='993810'>So</span>
  <span m='994010'>we</span> <span m='994160'>had</span> <span m='994730'>y</span>
  <span m='995850'>was</span> <span m='996320'>the Fourier</span> <span m='996980'>matrix</span>
  <span m='997580'>times</span> <span m='997930'>c.</span> <span m='1000150'>Now,</span>
  <span m='1000440'>if</span> <span m='1000580'>I</span> <span m='1000690'>take</span>
  <span m='1002610'>the</span> <span m='1002710'>length</span> <span m='1003050'>squared</span>
  <span m='1003580'>of</span> <span m='1003700'>both,</span> <span m='1004830'>y,</span>
  <span m='1006600'>so</span> <span m='1007250'>I'm</span> <span m='1007470'>going
  to--</span> <span m='1008590'>Right?</span> <span m='1009040'>That's</span> <span
  m='1009740'>the</span> <span m='1009880'>same</span> <span m='1010150'>as</span>
  <span m='1010280'>that.</span> <span m='1012990'>Now</span> <span m='1013380'>I'm</span>
  <span m='1013580'>going to</span> <span m='1013860'>do</span> <span m='1014230'>the</span>
  <span m='1014450'>same</span> <span m='1014750'>as</span> <span m='1014880'>this.</span>
  <span m='1016960'>I'm</span> <span m='1017130'>going to</span> <span m='1017400'>find</span>
  <span m='1017760'>the</span> <span m='1017820'>length</span> <span m='1018130'>squared,</span>
  <span m='1018790'>which</span> <span m='1019020'>will</span> <span m='1019140'>be</span>
  <span m='1019300'>y</span> <span m='1020090'>transpose</span> <span m='1020970'>y.</span>
  <span m='1022180'>No,</span> <span m='1022400'>it</span> <span m='1022550'>won't</span>
  <span m='1022840'>be</span> <span m='1022990'>y</span> <span m='1023350'>transpose</span>
  <span m='1024020'>y.</span> <span m='1024390'>What</span> <span m='1024620'>is</span>
  <span m='1024790'>length</span> <span m='1025100'>squared?</span> <span m='1027500'>y</span>
  <span m='1028010'>bar</span> <span m='1028560'>transpose</span> <span m='1029260'>y.</span>
  <span m='1029690'>I have to</span> <span m='1029820'>do</span> <span m='1030010'>that</span>
  <span m='1030260'>right.</span> <span m='1031480'>That</span> <span m='1031830'>will</span>
  <span m='1032060'>be,</span> <span m='1032890'>substituting,</span> <span m='1033760'>that's</span>
  <span m='1034350'>c</span> <span m='1034850'>bar</span> <span m='1035570'>F</span>
  <span m='1036380'>bar</span> <span m='1036910'>transpose</span> <span m='1038480'>times</span>
  <span m='1038860'>y</span> <span m='1039360'>is</span> <span m='1039570'>Fc.</span>
  <span m='1042470'>Just</span> <span m='1042740'>plugged</span> <span m='1043140'>it</span>
  <span m='1043270'>in,</span> <span m='1043860'>and</span> <span m='1044080'>now</span>
  <span m='1044330'>what</span> <span m='1044550'>do</span> <span m='1044670'>I</span>
  <span m='1044860'>use?</span> <span m='1046670'>The</span> <span m='1046910'>key</span>
  <span m='1047340'>fact,</span> <span m='1049470'>the</span> <span m='1049570'>fact</span>
  <span m='1049930'>that</span> <span m='1050060'>the</span> <span m='1050170'>columns</span>
  <span m='1050640'>are</span> <span m='1050720'>orthogonal.</span> <span m='1051560'>That's</span>
  <span m='1051910'>what</span> <span m='1052110'>made</span> <span m='1052410'>all</span>
  <span m='1052630'>these</span> <span m='1052920'>integrals</span> <span m='1053990'>simple,</span>
  <span m='1054630'>right?</span> <span m='1054980'>When</span> <span m='1055140'>I</span>
  <span m='1055620'>put</span> <span m='1055980'>that</span> <span m='1056230'>into</span>
  <span m='1056460'>there,</span> <span m='1056740'>a</span> <span m='1056790'>whole</span>
  <span m='1056940'>lot</span> <span m='1057140'>of</span> <span m='1057320'>integrals</span>
  <span m='1057630'>had</span> <span m='1057800'>to</span> <span m='1057870'>be</span>
  <span m='1058050'>zero.</span> <span m='1059040'>When</span> <span m='1059240'>I</span>
  <span m='1059300'>put</span> <span m='1060020'>this</span> <span m='1060500'>in,</span>
  <span m='1060890'>a</span> <span m='1060950'>whole</span> <span m='1061100'>lot</span>
  <span m='1061300'>of</span> <span m='1061420'>dot</span> <span m='1061650'>products</span>
  <span m='1062110'>have</span> <span m='1062300'>to</span> <span m='1062430'>be</span>
  <span m='1062580'>zero.</span> <span m='1062980'>Rows</span> <span m='1063700'>of</span>
  <span m='1063840'>F</span> <span m='1064210'>bar</span> <span m='1064600'>times</span>
  <span m='1065000'>columns</span> <span m='1065520'>of</span> <span m='1065690'>F,
  all</span> <span m='1066340'>zero,</span> <span m='1067470'>except</span> <span
  m='1068430'>when</span> <span m='1068730'>I'm</span> <span m='1068900'>hitting</span>
  <span m='1069380'>the</span> <span m='1069570'>same</span> <span m='1070120'>row.</span>
  <span m='1070920'>And</span> <span m='1071140'>when</span> <span m='1071300'>I'm</span>
  <span m='1071410'>hitting</span> <span m='1071710'>that</span> <span m='1071910'>same</span>
  <span m='1072210'>row</span> <span m='1072400'>I</span> <span m='1072530'>get</span>
  <span m='1072730'>an</span> <span m='1072850'>N.</span> <span m='1073590'>So</span>
  <span m='1073780'>I</span> <span m='1073910'>get,</span> <span m='1074160'>this</span>
  <span m='1074350'>is</span> <span m='1074570'>N</span> <span m='1075690'>c</span>
  <span m='1076010'>bar</span> <span m='1076760'>transpose</span> <span m='1078420'>c.</span>
  <span m='1079440'>And</span> <span m='1079730'>that's</span> <span m='1080350'>c</span>
  <span m='1080550'>squared.</span> <span m='1084760'>That's</span> <span m='1085040'>the</span>
  <span m='1085160'>energy</span> <span m='1085590'>inequality,</span> <span m='1086320'>it's</span>
  <span m='1086510'>just</span> <span m='1086910'>orthogonality</span> <span m='1088010'>once</span>
  <span m='1088340'>again.</span> <span m='1090330'>Everything</span> <span m='1090960'>in</span>
  <span m='1092560'>these</span> <span m='1092880'>weeks</span> <span m='1093320'>is</span>
  <span m='1093930'>coming</span> <span m='1094370'>out</span> <span m='1094540'>of</span>
  <span m='1094620'>orthogonality.</span> </p><p><span m='1095950'>Orthogonality</span>
  <span m='1096880'>is</span> <span m='1097010'>the</span> <span m='1097150'>fact</span>
  <span m='1097560'>that</span> <span m='1097690'>this</span> <span m='1097970'>is</span>
  <span m='1098210'>N</span> <span m='1098570'>times</span> <span m='1098890'>the</span>
  <span m='1099000'>identity.</span> <span m='1100860'>Right?</span> <span m='1103690'>Well,</span>
  <span m='1104130'>OK</span> <span m='1104510'>that's</span> <span m='1104780'>a</span>
  <span m='1105860'>quick</span> <span m='1107380'>recall</span> <span m='1108730'>of</span>
  <span m='1109350'>a</span> <span m='1110120'>bunch</span> <span m='1110470'>of</span>
  <span m='1110620'>stuff</span> <span m='1111070'>for</span> <span m='1111620'>functions.</span>
  <span m='1112790'>And</span> <span m='1114770'>just</span> <span m='1115070'>seeing</span>
  <span m='1115420'>maybe</span> <span m='1115740'>for</span> <span m='1115920'>the</span>
  <span m='1116060'>first</span> <span m='1116380'>time</span> <span m='1116690'>the</span>
  <span m='1117090'>discrete</span> <span m='1117600'>analogs.</span> <span m='1118750'>I</span>
  <span m='1118950'>guess</span> <span m='1119340'>I</span> <span m='1119500'>don't</span>
  <span m='1119960'>have</span> <span m='1120230'>a</span> <span m='1120390'>brilliant</span>
  <span m='1120920'>idea</span> <span m='1121440'>for</span> <span m='1121800'>the</span>
  <span m='1121970'>discrete</span> <span m='1122380'>analog</span> <span m='1123000'>of</span>
  <span m='1123130'>the</span> <span m='1123250'>derivative.</span> <span m='1125100'>Well,</span>
  <span m='1126430'>guess</span> <span m='1126660'>there's</span> <span m='1126850'>a</span>
  <span m='1126930'>natural</span> <span m='1127470'>idea,</span> <span m='1127940'>it</span>
  <span m='1128030'>would</span> <span m='1128190'>be</span> <span m='1128290'>a</span>
  <span m='1128370'>finite</span> <span m='1128740'>difference,</span> <span m='1129870'>but</span>
  <span m='1130140'>somehow</span> <span m='1130520'>that</span> <span m='1130760'>isn't</span>
  <span m='1131010'>a</span> <span m='1131080'>rule</span> <span m='1131850'>that</span>
  <span m='1132400'>gets</span> <span m='1133660'>like,</span> <span m='1135030'>high</span>
  <span m='1135300'>marks.</span> <span m='1136730'>But</span> <span m='1137530'>we</span>
  <span m='1137760'>saw</span> <span m='1138270'>the</span> <span m='1138430'>discrete</span>
  <span m='1139020'>analog</span> <span m='1139670'>of</span> <span m='1139810'>the</span>
  <span m='1140520'>shift</span> <span m='1141080'>and</span> <span m='1141290'>now</span>
  <span m='1141560'>we</span> <span m='1141770'>see</span> <span m='1142230'>the</span>
  <span m='1142380'>energy</span> <span m='1142880'>inequality</span> <span m='1143640'>is</span>
  <span m='1143830'>just</span> <span m='1144160'>that</span> <span m='1144350'>the</span>
  <span m='1145550'>length</span> <span m='1146000'>of</span> <span m='1146950'>the</span>
  <span m='1147140'>function</span> <span m='1147650'>squared</span> <span m='1148630'>is</span>
  <span m='1149160'>equal</span> <span m='1149680'>to</span> <span m='1150020'>N</span>
  <span m='1150370'>times</span> <span m='1150670'>the</span> <span m='1150810'>length</span>
  <span m='1151050'>of</span> <span m='1151210'>the</span> <span m='1151540'>coefficients</span>
  <span m='1151970'>squared.</span> <span m='1153900'>OK</span> <span m='1154230'>with</span>
  <span m='1154400'>that?</span> <span m='1155760'>Lots</span> <span m='1156460'>of</span>
  <span m='1156580'>formulas</span> <span m='1157090'>here.</span> <span m='1158800'>Let's</span>
  <span m='1159050'>see.</span> <span m='1164080'>Do</span> <span m='1164270'>some</span>
  <span m='1164490'>examples.</span> <span m='1165310'>I</span> <span m='1165390'>mean,</span>
  <span m='1165600'>these</span> <span m='1165900'>were</span> <span m='1166610'>simple</span>
  <span m='1167080'>examples.</span> <span m='1167930'>And</span> <span m='1168130'>I</span>
  <span m='1168230'>think</span> <span m='1168540'>the</span> <span m='1168660'>homework</span>
  <span m='1169070'>gives</span> <span m='1169290'>you</span> <span m='1169480'>some</span>
  <span m='1169730'>more.</span> <span m='1170790'>You</span> <span m='1170940'>should</span>
  <span m='1171150'>be</span> <span m='1171310'>able</span> <span m='1171530'>to</span>
  <span m='1171640'>take</span> <span m='1171990'>the</span> <span m='1172110'>Fourier</span>
  <span m='1172470'>transform</span> <span m='1174860'>and</span> <span m='1176090'>go</span>
  <span m='1176220'>backwards.</span> <span m='1177960'>And</span> <span m='1178300'>when</span>
  <span m='1178470'>we</span> <span m='1178610'>do</span> <span m='1178850'>convolution</span>
  <span m='1179950'>in</span> <span m='1180570'>a</span> <span m='1180610'>few</span>
  <span m='1180860'>minutes,</span> <span m='1181960'>we're</span> <span m='1182210'>certainly</span>
  <span m='1182590'>going</span> <span m='1182750'>to</span> <span m='1182840'>be</span>
  <span m='1183420'>taking</span> <span m='1183900'>the</span> <span m='1184280'>Fourier,</span>
  <span m='1185100'>we're</span> <span m='1185410'>going</span> <span m='1185590'>to</span>
  <span m='1185660'>be</span> <span m='1185810'>going</span> <span m='1186070'>both</span>
  <span m='1186370'>ways.</span> <span m='1187680'>And</span> <span m='1188300'>use</span>
  <span m='1188610'>all</span> <span m='1188800'>these</span> <span m='1189410'>facts.</span>
  <span m='1191070'>OK,</span> <span m='1191450'>I'll</span> <span m='1191570'>pause</span>
  <span m='1191950'>a</span> <span m='1192020'>moment.</span> <span m='1192390'>That's</span>
  <span m='1192960'>topic</span> <span m='1193360'>one.</span> </p><p><span m='1195290'>Topic</span>
  <span m='1195700'>two,</span> <span m='1196010'>fast</span> <span m='1196350'>Fourier</span>
  <span m='1196670'>transform.</span> <span m='1197560'>Wow.</span> <span m='1200550'>What's</span>
  <span m='1201030'>the</span> <span m='1201180'>good</span> <span m='1201710'>way</span>
  <span m='1202000'>to--</span> <span m='1203780'>I</span> <span m='1203870'>mean,</span>
  <span m='1204090'>any</span> <span m='1204770'>decent</span> <span m='1206600'>machine</span>
  <span m='1207240'>comes</span> <span m='1207620'>with</span> <span m='1207830'>the</span>
  <span m='1207930'>FFT</span> <span m='1208990'>hardwired</span> <span m='1209730'>in.</span>
  <span m='1210810'>So</span> <span m='1211210'>you</span> <span m='1211370'>might</span>
  <span m='1211640'>say,</span> <span m='1212200'>OK</span> <span m='1212530'>I'll</span>
  <span m='1212660'>just</span> <span m='1212880'>use</span> <span m='1213160'>it.</span>
  <span m='1213320'>And</span> <span m='1213500'>that</span> <span m='1213730'>seems</span>
  <span m='1214280'>totally</span> <span m='1214670'>reasonable</span> <span m='1215190'>to</span>
  <span m='1215280'>me.</span> <span m='1216830'>But</span> <span m='1218540'>you</span>
  <span m='1218840'>might</span> <span m='1219050'>like</span> <span m='1219250'>to</span>
  <span m='1219400'>see</span> <span m='1219930'>just</span> <span m='1222350'>on</span>
  <span m='1222580'>one</span> <span m='1223070'>board,</span> <span m='1224380'>what's</span>
  <span m='1224790'>the</span> <span m='1225000'>key</span> <span m='1225290'>idea?</span>
  <span m='1226400'>What's</span> <span m='1227700'>the</span> <span m='1227860'>little</span>
  <span m='1228280'>bit</span> <span m='1228510'>of</span> <span m='1228640'>algebra</span>
  <span m='1229180'>that</span> <span m='1229350'>makes</span> <span m='1229650'>it</span>
  <span m='1229770'>work?</span> <span m='1230560'>So</span> <span m='1231790'>I'll</span>
  <span m='1232120'>just</span> <span m='1232620'>have</span> <span m='1232830'>one</span>
  <span m='1233180'>board</span> <span m='1233520'>here</span> <span m='1233750'>for</span>
  <span m='1233930'>the</span> <span m='1234070'>FFT</span> <span m='1235170'>and</span>
  <span m='1235420'>a</span> <span m='1235480'>little</span> <span m='1235760'>bit</span>
  <span m='1235940'>of</span> <span m='1236050'>algebra.</span> <span m='1238140'>Simple,</span>
  <span m='1238650'>simple</span> <span m='1239110'>but</span> <span m='1239490'>once</span>
  <span m='1240550'>it</span> <span m='1240690'>hit</span> <span m='1240880'>the</span>
  <span m='1241000'>world,</span> <span m='1245290'>well,</span> <span m='1245650'>computer</span>
  <span m='1246190'>scientists</span> <span m='1247700'>just</span> <span m='1247940'>love</span>
  <span m='1248440'>the</span> <span m='1248840'>recursion</span> <span m='1249660'>that</span>
  <span m='1249770'>comes</span> <span m='1250140'>in</span> <span m='1250300'>there.</span>
  <span m='1250520'>So</span> <span m='1250680'>they</span> <span m='1251470'>look</span>
  <span m='1251700'>for</span> <span m='1251820'>that</span> <span m='1252090'>in</span>
  <span m='1252270'>every</span> <span m='1252730'>possible</span> <span m='1254000'>other</span>
  <span m='1254330'>algorithm</span> <span m='1254980'>now.</span> <span m='1258180'>OK,</span>
  <span m='1259370'>let</span> <span m='1259530'>me</span> <span m='1259660'>see</span>
  <span m='1259920'>that</span> <span m='1260180'>point.</span> <span m='1261700'>So</span>
  <span m='1261850'>here's</span> <span m='1262210'>the</span> <span m='1262300'>main</span>
  <span m='1262600'>point.</span> <span m='1263470'>That</span> <span m='1263650'>if</span>
  <span m='1263780'>I</span> <span m='1263920'>want</span> <span m='1264190'>to</span>
  <span m='1264260'>take</span> <span m='1265490'>the--</span> <span m='1268570'>multiply</span>
  <span m='1269070'>by</span> <span m='1269430'>F</span> <span m='1270110'>of</span>
  <span m='1270290'>size</span> <span m='1270700'>1,024,</span> <span m='1272790'>the</span>
  <span m='1272940'>fast</span> <span m='1273360'>Fourier</span> <span m='1273640'>transform</span>
  <span m='1274540'>connects</span> <span m='1275180'>that</span> <span m='1275720'>full</span>
  <span m='1276120'>matrix</span> <span m='1279140'>to</span> <span m='1279310'>a</span>
  <span m='1279400'>half-full</span> <span m='1280130'>matrix.</span> <span m='1281110'>It</span>
  <span m='1281350'>connects</span> <span m='1281820'>that</span> <span m='1282120'>to</span>
  <span m='1282240'>the</span> <span m='1282360'>half-full</span> <span m='1283000'>matrix</span>
  <span m='1284090'>that</span> <span m='1284350'>takes</span> <span m='1284820'>the</span>
  <span m='1286460'>half-size</span> <span m='1288060'>transforms</span> <span m='1289410'>separately.</span>
  <span m='1290520'>So</span> <span m='1290800'>it's</span> <span m='1290960'>half-full</span>
  <span m='1291490'>because</span> <span m='1293270'>of</span> <span m='1293420'>these</span>
  <span m='1293720'>zeroes.</span> <span m='1296670'>That's</span> <span m='1296960'>the</span>
  <span m='1297090'>point.</span> <span m='1297950'>That</span> <span m='1299020'>the</span>
  <span m='1299510'>1,024</span> <span m='1300850'>matrix</span> <span m='1301500'>is</span>
  <span m='1301700'>connected</span> <span m='1302090'>to</span> <span m='1302190'>the</span>
  <span m='1302400'>512</span> <span m='1303090'>matrix.</span> <span m='1304350'>And</span>
  <span m='1305050'>what's</span> <span m='1305690'>underlying</span> <span m='1306430'>that?</span>
  <span m='1307310'>The</span> <span m='1309600'>1,024</span> <span m='1310100'>matrix</span>
  <span m='1310900'>is</span> <span m='1311210'>full</span> <span m='1311680'>of</span>
  <span m='1313300'>e</span> <span m='1314080'>to</span> <span m='1314250'>the</span>
  <span m='1314400'>2pi*i,</span> <span m='1315630'>the</span> <span m='1315780'>w,</span>
  <span m='1316700'>over</span> <span m='1317170'>1,024,</span> <span m='1318580'>right?</span>
  <span m='1319010'>That's</span> <span m='1319660'>the</span> <span m='1319780'>w</span>
  <span m='1320270'>for</span> <span m='1320460'>this</span> <span m='1320760'>guy.</span>
  <span m='1321820'>And</span> <span m='1322260'>then</span> <span m='1323060'>the</span>
  <span m='1323220'>w</span> <span m='1323710'>for</span> <span m='1323870'>this</span>
  <span m='1324210'>guy,</span> <span m='1325540'>for</span> <span m='1325690'>both</span>
  <span m='1326370'>of</span> <span m='1326490'>these,</span> <span m='1327210'>is</span>
  <span m='1328960'>e^(2pi*i/512).</span> <span m='1334140'>So</span> <span m='1334410'>if</span>
  <span m='1334560'>there's</span> <span m='1334790'>a</span> <span m='1334900'>connection</span>
  <span m='1335430'>between</span> <span m='1335820'>that</span> <span m='1336050'>matrix</span>
  <span m='1336620'>and</span> <span m='1336790'>this</span> <span m='1336990'>matrix,</span>
  <span m='1337620'>there'd</span> <span m='1337740'>better</span> <span m='1338010'>be</span>
  <span m='1338180'>a</span> <span m='1338260'>connection</span> <span m='1338750'>between</span>
  <span m='1339220'>that</span> <span m='1339480'>number</span> <span m='1340010'>and</span>
  <span m='1340220'>that</span> <span m='1340440'>number.</span> <span m='1341330'>Because</span>
  <span m='1341850'>this</span> <span m='1342270'>is</span> <span m='1342420'>the</span>
  <span m='1342540'>number</span> <span m='1342920'>that</span> <span m='1343150'>fills</span>
  <span m='1343700'>this</span> <span m='1343950'>one,</span> <span m='1344250'>and</span>
  <span m='1344410'>this</span> <span m='1344560'>is</span> <span m='1344670'>the</span>
  <span m='1344790'>number</span> <span m='1345100'>that</span> <span m='1345290'>fills</span>
  <span m='1345700'>these.</span> <span m='1346670'>So</span> <span m='1347060'>what's</span>
  <span m='1347390'>the</span> <span m='1347530'>connection?</span> <span m='1350120'>It's</span>
  <span m='1350400'>just</span> <span m='1350690'>perfect,</span> <span m='1351680'>right?</span>
  <span m='1352530'>If</span> <span m='1352720'>I</span> <span m='1352850'>take</span>
  <span m='1353200'>this</span> <span m='1353470'>number,</span> <span m='1354510'>which</span>
  <span m='1354780'>is</span> <span m='1356420'>one</span> <span m='1357280'>part</span>
  <span m='1357660'>of</span> <span m='1357980'>the</span> <span m='1358070'>whole</span>
  <span m='1358380'>circle,</span> <span m='1358960'>1/1,024,</span> <span m='1361110'>a</span>
  <span m='1361370'>fraction</span> <span m='1361920'>of</span> <span m='1362020'>the</span>
  <span m='1362140'>whole</span> <span m='1362380'>circle,</span> <span m='1363310'>what</span>
  <span m='1363720'>do</span> <span m='1363820'>I</span> <span m='1363950'>do</span>
  <span m='1364300'>to</span> <span m='1364450'>get</span> <span m='1364680'>this</span>
  <span m='1364940'>guy?</span> <span m='1367120'>To</span> <span m='1367260'>get</span>
  <span m='1367720'>one 512th</span> <span m='1368790'>of</span> <span m='1368920'>the</span>
  <span m='1369410'>way</span> <span m='1369630'>around</span> <span m='1370010'>the</span>
  <span m='1370110'>circle?</span> <span m='1371430'>I</span> <span m='1372960'>square</span>
  <span m='1373480'>it.</span> <span m='1375110'>The</span> <span m='1375240'>square</span>
  <span m='1375670'>of</span> <span m='1375780'>this</span> <span m='1376240'>w</span>
  <span m='1378380'>is</span> <span m='1378640'>this</span> <span m='1378860'>w.</span>
  <span m='1381650'>Let</span> <span m='1381820'>me</span> <span m='1381940'>call</span>
  <span m='1382240'>this</span> <span m='1382550'>w_N,</span> <span m='1385240'>and</span>
  <span m='1385470'>this</span> <span m='1385680'>one</span> <span m='1385990'>w_M.</span>
  <span m='1387970'>Maybe</span> <span m='1388710'>I'll</span> <span m='1388810'>use</span>
  <span m='1389110'>caps,</span> <span m='1389540'>yeah</span> <span m='1389750'>I'm</span>
  <span m='1389860'>using</span> <span m='1390200'>cap</span> <span m='1390960'>N,</span>
  <span m='1391640'>this</span> <span m='1391810'>is</span> <span m='1391950'>my</span>
  <span m='1392150'>w.</span> <span m='1392930'>This</span> <span m='1393110'>is</span>
  <span m='1393210'>the</span> <span m='1393280'>one</span> <span m='1393460'>I</span>
  <span m='1393530'>want.</span> <span m='1394570'>The</span> <span m='1394730'>w_N,</span>
  <span m='1395670'>the</span> <span m='1395840'>N by N</span> <span m='1396300'>one,</span>
  <span m='1396560'>N</span> <span m='1397540'>is</span> <span m='1397670'>1,024,</span>
  <span m='1399660'>and</span> <span m='1400240'>the</span> <span m='1400410'>point</span>
  <span m='1400780'>is,</span> <span m='1401020'>everybody</span> <span m='1401380'>saw</span>
  <span m='1401620'>that,</span> <span m='1401900'>when</span> <span m='1402080'>I</span>
  <span m='1402160'>squared</span> <span m='1402660'>it</span> <span m='1403250'>I</span>
  <span m='1403380'>doubled</span> <span m='1403810'>the</span> <span m='1404000'>angle?</span>
  <span m='1404790'>When</span> <span m='1405020'>I</span> <span m='1405080'>doubled</span>
  <span m='1405430'>that</span> <span m='1405680'>angle</span> <span m='1406100'>the</span>
  <span m='1406300'>two</span> <span m='1406560'>over</span> <span m='1406960'>that</span>
  <span m='1407360'>gave</span> <span m='1407650'>me</span> <span m='1408170'>1/512.</span>
  <span m='1411130'>Fantastic.</span> <span m='1412650'>Of</span> <span m='1412830'>course,</span>
  <span m='1413420'>that</span> <span m='1413920'>doesn't</span> <span m='1415490'>make</span>
  <span m='1416060'>this</span> <span m='1416530'>equal</span> <span m='1416980'>to</span>
  <span m='1417060'>that,</span> <span m='1419590'>but</span> <span m='1419790'>it</span>
  <span m='1420240'>suggests</span> <span m='1421900'>that</span> <span m='1422160'>there</span>
  <span m='1422300'>is</span> <span m='1422460'>a</span> <span m='1422580'>close</span>
  <span m='1423020'>connection.</span> </p><p><span m='1424330'>So</span> <span m='1425710'>let</span>
  <span m='1425900'>me</span> <span m='1426080'>finish</span> <span m='1426570'>here</span>
  <span m='1426840'>the</span> <span m='1426990'>key</span> <span m='1427300'>idea</span>
  <span m='1427760'>of</span> <span m='1427980'>the</span> <span m='1428210'>Fourier</span>
  <span m='1428580'>transform</span> <span m='1429490'>in</span> <span m='1431320'>block</span>
  <span m='1431710'>matrix</span> <span m='1432260'>form.</span> <span m='1433580'>What's</span>
  <span m='1433930'>the</span> <span m='1434040'>key</span> <span m='1434280'>idea?</span>
  <span m='1435110'>So</span> <span m='1436070'>instead</span> <span m='1436490'>of</span>
  <span m='1436580'>doing</span> <span m='1436900'>the</span> <span m='1437040'>big</span>
  <span m='1437500'>transform,</span> <span m='1438180'>the</span> <span m='1438290'>full</span>
  <span m='1438600'>size,</span> <span m='1439430'>I'm</span> <span m='1439640'>going</span>
  <span m='1439780'>to</span> <span m='1439890'>do</span> <span m='1440090'>two</span>
  <span m='1440380'>half-sizes.</span> <span m='1441360'>But</span> <span m='1441570'>what</span>
  <span m='1441790'>am</span> <span m='1441910'>I</span> <span m='1441990'>going to</span>
  <span m='1442690'>apply</span> <span m='1443170'>those</span> <span m='1443580'>to?</span>
  <span m='1448520'>Here's</span> <span m='1449060'>the</span> <span m='1449170'>trick.</span>
  <span m='1450610'>These</span> <span m='1451170'>two</span> <span m='1451490'>separate</span>
  <span m='1451980'>guys</span> <span m='1452700'>apply</span> <span m='1453450'>to</span>
  <span m='1453640'>the</span> <span m='1453870'>odd-numbered</span> <span m='1455400'>coefficients.</span>
  <span m='1456530'>The</span> <span m='1456650'>odd-numbered</span> <span m='1457390'>component.</span>
  <span m='1458410'>And</span> <span m='1458630'>the</span> <span m='1458740'>even.</span>
  <span m='1459710'>So</span> <span m='1459910'>I</span> <span m='1460000'>have</span>
  <span m='1460260'>to</span> <span m='1460420'>first</span> <span m='1460940'>do</span>
  <span m='1461700'>a</span> <span m='1461900'>little</span> <span m='1462420'>permutation,</span>
  <span m='1464420'>and</span> <span m='1465340'>even</span> <span m='1465740'>comes</span>
  <span m='1466080'>first,</span> <span m='1466490'>always.</span> <span m='1467950'>Even</span>
  <span m='1468420'>means</span> <span m='1468750'>zero,</span> <span m='1469210'>two,</span>
  <span m='1469530'>four,</span> <span m='1469910'>up</span> <span m='1470140'>to</span>
  <span m='1470260'>a</span> <span m='1470350'>1,022.</span> <span m='1472080'>So</span>
  <span m='1472310'>this</span> <span m='1472520'>is</span> <span m='1472690'>zero,</span>
  <span m='1473130'>two;</span> <span m='1473860'>zero</span> <span m='1474310'>up</span>
  <span m='1474520'>to</span> <span m='1474660'>1,022.</span> <span m='1478350'>And</span>
  <span m='1478520'>then</span> <span m='1478710'>come</span> <span m='1478930'>all</span>
  <span m='1479070'>the</span> <span m='1479220'>odd</span> <span m='1479560'>guys.</span>
  <span m='1480840'>One</span> <span m='1481350'>up</span> <span m='1481640'>to</span>
  <span m='1481940'>1,023.</span> <span m='1484350'>So</span> <span m='1484490'>this</span>
  <span m='1484700'>is</span> <span m='1484880'>a</span> <span m='1484980'>permutation,</span>
  <span m='1485850'>a</span> <span m='1485920'>simple</span> <span m='1486340'>permutation.</span>
  <span m='1488360'>Just</span> <span m='1489370'>take</span> <span m='1489670'>your</span>
  <span m='1490140'>1,024</span> <span m='1490990'>numbers,</span> <span m='1491770'>pick</span>
  <span m='1492030'>out</span> <span m='1492210'>the</span> <span m='1492300'>even</span>
  <span m='1492720'>ones,</span> <span m='1493060'>put</span> <span m='1493250'>them</span>
  <span m='1493410'>on</span> <span m='1493560'>top.</span> <span m='1495270'>Right?</span>
  <span m='1496340'>In</span> <span m='1496510'>other</span> <span m='1496680'>words,</span>
  <span m='1496940'>put</span> <span m='1497130'>them</span> <span m='1497270'>on</span>
  <span m='1497430'>top</span> <span m='1497770'>where</span> <span m='1497940'>512</span>
  <span m='1498620'>is</span> <span m='1498770'>going</span> <span m='1498960'>to</span>
  <span m='1499040'>act</span> <span m='1499360'>on</span> <span m='1499510'>it.</span>
  <span m='1500420'>Put</span> <span m='1500620'>the</span> <span m='1500740'>odd</span>
  <span m='1500990'>ones</span> <span m='1501440'>at</span> <span m='1501570'>the</span>
  <span m='1501660'>bottom,</span> <span m='1502080'>the</span> <span m='1502170'>last</span>
  <span m='1502570'>512,</span> <span m='1503510'>that</span> <span m='1503840'>guy</span>
  <span m='1504090'>will</span> <span m='1504290'>act</span> <span m='1504600'>on</span>
  <span m='1504740'>that.</span> <span m='1505020'>So</span> <span m='1505160'>there's</span>
  <span m='1505400'>512</span> <span m='1506400'>numbers</span> <span m='1506860'>there,</span>
  <span m='1508490'>with</span> <span m='1508750'>the</span> <span m='1508870'>even</span>
  <span m='1509240'>coefficients,</span> <span m='1510010'>this</span> <span m='1510280'>acts.</span>
  <span m='1510750'>OK,</span> <span m='1511200'>now</span> <span m='1511390'>we've</span>
  <span m='1511600'>got</span> <span m='1511860'>two</span> <span m='1513070'>half-size</span>
  <span m='1513700'>transforms.</span> <span m='1514990'>Because</span> <span m='1515360'>we're</span>
  <span m='1516240'>applying</span> <span m='1516760'>this</span> <span m='1517090'>to</span>
  <span m='1518480'>the</span> <span m='1518600'>y,</span> <span m='1519220'>to</span>
  <span m='1519390'>a</span> <span m='1519590'>to</span> <span m='1519750'>a</span>
  <span m='1519850'>typical</span> <span m='1520270'>y.</span> <span m='1521720'>OK.</span>
  <span m='1522630'>But</span> <span m='1522870'>I've</span> <span m='1523100'>just</span>
  <span m='1523340'>written</span> <span m='1523670'>F</span> <span m='1524060'>without</span>
  <span m='1524450'>a</span> <span m='1524500'>y</span> <span m='1524900'>so</span>
  <span m='1525120'>I</span> <span m='1525220'>don't</span> <span m='1525550'>really</span>
  <span m='1525830'>need</span> <span m='1526080'>a</span> <span m='1526150'>y</span>
  <span m='1526510'>here.</span> <span m='1527230'>This</span> <span m='1527550'>is</span>
  <span m='1528220'>a</span> <span m='1528320'>matrix</span> <span m='1528850'>identity.</span>
  <span m='1530130'>It's</span> <span m='1530290'>a</span> <span m='1530380'>matrix</span>
  <span m='1530910'>identity</span> <span m='1531960'>that's</span> <span m='1532200'>got</span>
  <span m='1532410'>a</span> <span m='1532470'>bunch</span> <span m='1532780'>of</span>
  <span m='1532870'>zeroes</span> <span m='1533310'>there.</span> <span m='1533960'>Of</span>
  <span m='1534120'>course,</span> <span m='1534400'>that</span> <span m='1534670'>matrix</span>
  <span m='1535170'>is</span> <span m='1535340'>full</span> <span m='1535870'>of zeroes.</span>
  <span m='1536410'>I</span> <span m='1536470'>mean,</span> <span m='1536630'>this</span>
  <span m='1536840'>is</span> <span m='1537430'>instant</span> <span m='1537970'>speed</span>
  <span m='1538940'>to</span> <span m='1539100'>do</span> <span m='1539340'>that</span>
  <span m='1540610'>permutation.</span> <span m='1541640'>Grab</span> <span m='1542100'>the</span>
  <span m='1542890'>evens,</span> <span m='1543420'>put</span> <span m='1543650'>them</span>
  <span m='1543780'>in</span> <span m='1543890'>front</span> <span m='1544140'>of</span>
  <span m='1544210'>the</span> <span m='1544330'>odds.</span> </p><p><span m='1545040'>OK,</span>
  <span m='1545420'>so</span> <span m='1545660'>now</span> <span m='1545920'>I've</span>
  <span m='1546090'>got</span> <span m='1546330'>two</span> <span m='1546590'>half-sizes,</span>
  <span m='1547770'>but</span> <span m='1548000'>then</span> <span m='1549130'>I</span>
  <span m='1549260'>have</span> <span m='1549550'>to</span> <span m='1549710'>put</span>
  <span m='1549910'>them</span> <span m='1550060'>back</span> <span m='1550340'>together</span>
  <span m='1551010'>to</span> <span m='1551140'>get</span> <span m='1551470'>the</span>
  <span m='1551590'>full-size</span> <span m='1552160'>matrix.</span> <span m='1553290'>And</span>
  <span m='1553610'>that</span> <span m='1554150'>is</span> <span m='1554340'>also</span>
  <span m='1554880'>a</span> <span m='1555030'>matrix.</span> <span m='1555660'>Turns</span>
  <span m='1555990'>out</span> <span m='1556210'>to</span> <span m='1556310'>be</span>
  <span m='1556470'>a</span> <span m='1556570'>diagonal</span> <span m='1557500'>there,</span>
  <span m='1558640'>and</span> <span m='1558980'>a</span> <span m='1559140'>minus</span>
  <span m='1559630'>the</span> <span m='1559750'>diagonal</span> <span m='1560350'>goes</span>
  <span m='1560660'>there.</span> <span m='1565770'>So</span> <span m='1565970'>actually,</span>
  <span m='1566540'>that</span> <span m='1566830'>looks</span> <span m='1567130'>great</span>
  <span m='1567480'>too,</span> <span m='1567750'>right?</span> <span m='1569250'>Full</span>
  <span m='1569540'>of</span> <span m='1569660'>zeroes,</span> <span m='1570060'>the</span>
  <span m='1570230'>identity.</span> <span m='1571030'>No</span> <span m='1571580'>multiplications</span>
  <span m='1572390'>whatever.</span> <span m='1573240'>Well,</span> <span m='1573560'>these</span>
  <span m='1573950'>are</span> <span m='1574190'>the</span> <span m='1574370'>only</span>
  <span m='1574770'>multiplications,</span> <span m='1576000'>sometimes</span> <span
  m='1576440'>they're</span> <span m='1576580'>called</span> <span m='1576900'>twiddle</span>
  <span m='1577150'>factors,</span> <span m='1578860'>give</span> <span m='1579060'>it</span>
  <span m='1579200'>a</span> <span m='1579280'>fancy</span> <span m='1579920'>name.</span>
  <span m='1581490'>Official</span> <span m='1583360'>sounding</span> <span m='1583840'>name,</span>
  <span m='1584340'>twiddle factors.</span> <span m='1585330'>OK,</span> <span m='1585930'>so</span>
  <span m='1586190'>that</span> <span m='1586510'>diagonal</span> <span m='1587100'>matrix</span>
  <span m='1587620'>D,</span> <span m='1588520'>what's</span> <span m='1588840'>that?</span>
  <span m='1589690'>That</span> <span m='1589860'>diagonal</span> <span m='1590390'>matrix</span>
  <span m='1591000'>D</span> <span m='1592990'>happens</span> <span m='1593430'>to</span>
  <span m='1593510'>be</span> <span m='1593670'>just</span> <span m='1594420'>the</span>
  <span m='1594510'>powers</span> <span m='1594980'>of</span> <span m='1595110'>w,</span>
  <span m='1596010'>sit</span> <span m='1596290'>along</span> <span m='1596780'>D.</span>
  <span m='1597440'>1,</span> <span m='1598610'>w,</span> <span m='1599450'>up</span>
  <span m='1599750'>to</span> <span m='1600400'>w</span> <span m='1600900'>to</span>
  <span m='1601140'>the,</span> <span m='1601770'>this</span> <span m='1601960'>is</span>
  <span m='1602140'>w_N,</span> <span m='1603040'>we're</span> <span m='1603180'>talking,</span>
  <span m='1603610'>the</span> <span m='1603730'>big</span> <span m='1604030'>w,</span>
  <span m='1604900'>and</span> <span m='1605190'>it's</span> <span m='1605340'>only</span>
  <span m='1605640'>half-size</span> <span m='1606490'>so</span> <span m='1606670'>it</span>
  <span m='1606840'>goes</span> <span m='1607120'>up</span> <span m='1607360'>to</span>
  <span m='1608400'>M-1.</span> <span m='1610210'>Half,</span> <span m='1610850'>M
  is</span> <span m='1611320'>half</span> <span m='1611650'>of</span> <span m='1611780'>N.</span>
  <span m='1613310'>Everybody's</span> <span m='1613890'>got</span> <span m='1614120'>that,</span>
  <span m='1614570'>right?</span> <span m='1615000'>M is</span> <span m='1615570'>half</span>
  <span m='1615930'>of</span> <span m='1616090'>N</span> <span m='1616390'>here.</span>
  <span m='1617290'>I'll</span> <span m='1617450'>get</span> <span m='1617640'>that</span>
  <span m='1617860'>written</span> <span m='1618120'>on</span> <span m='1618290'>the</span>
  <span m='1618370'>board.</span> <span m='1621130'>M</span> <span m='1621380'>is</span>
  <span m='1621530'>512,</span> <span m='1622730'>N</span> <span m='1623090'>is</span>
  <span m='1623220'>1,024,</span> <span m='1624760'>here</span> <span m='1625000'>we</span>
  <span m='1625170'>have</span> <span m='1625730'>the</span> <span m='1625860'>powers</span>
  <span m='1626490'>of</span> <span m='1627240'>this</span> <span m='1627530'>guy</span>
  <span m='1627930'>up</span> <span m='1628280'>to</span> <span m='1628980'>511.</span>
  <span m='1630810'>The</span> <span m='1630930'>total</span> <span m='1631270'>size</span>
  <span m='1631740'>being</span> <span m='1632050'>512</span> <span m='1632820'>because</span>
  <span m='1633000'>that's</span> <span m='1633230'>a</span> <span m='1633330'>512</span>
  <span m='1633680'>by</span> <span m='1634300'>512</span> <span m='1634940'>matrix.</span>
  <span m='1637670'>I</span> <span m='1637880'>guess</span> <span m='1638180'>I</span>
  <span m='1638310'>can</span> <span m='1638530'>remember</span> <span m='1640900'>somewhere,</span>
  <span m='1641290'>being</span> <span m='1641580'>at a</span> <span m='1641740'>conference,</span>
  <span m='1642540'>this</span> <span m='1642750'>was</span> <span m='1643010'>probably</span>
  <span m='1643430'>soon</span> <span m='1643780'>after</span> <span m='1644160'>the</span>
  <span m='1644340'>FFT</span> <span m='1647250'>became</span> <span m='1648430'>sort</span>
  <span m='1648750'>of</span> <span m='1649250'>famous.</span> <span m='1649780'>And</span>
  <span m='1649950'>then</span> <span m='1650150'>somebody</span> <span m='1651720'>who</span>
  <span m='1651910'>was</span> <span m='1652160'>just</span> <span m='1652410'>presenting</span>
  <span m='1653040'>the</span> <span m='1653160'>idea</span> <span m='1653750'>and</span>
  <span m='1653890'>as</span> <span m='1654020'>soon</span> <span m='1654270'>as</span>
  <span m='1654470'>it</span> <span m='1655140'>was</span> <span m='1655360'>presented</span>
  <span m='1655860'>that</span> <span m='1656110'>way,</span> <span m='1658000'>I</span>
  <span m='1658110'>was</span> <span m='1658370'>happy.</span> <span m='1658860'>I</span>
  <span m='1659060'>guess.</span> <span m='1659760'>I</span> <span m='1659900'>thought</span>
  <span m='1660190'>OK,</span> <span m='1661580'>there</span> <span m='1661800'>you</span>
  <span m='1661950'>see</span> <span m='1662180'>the</span> <span m='1662350'>idea.</span>
  <span m='1663020'>Permutation,</span> <span m='1664090'>reorder</span> <span m='1664710'>the</span>
  <span m='1665120'>even-odd.</span> <span m='1666770'>Two</span> <span m='1666980'>half-size</span>
  <span m='1667600'>transforms,</span> <span m='1668460'>put</span> <span m='1668700'>them</span>
  <span m='1668790'>back</span> <span m='1669030'>together.</span> <span m='1670220'>And</span>
  <span m='1670720'>what's</span> <span m='1671580'>happened</span> <span m='1671950'>here?</span>
  <span m='1672780'>The</span> <span m='1673760'>work</span> <span m='1676370'>of</span>
  <span m='1676550'>this</span> <span m='1677540'>matrix,</span> <span m='1678250'>multiplying</span>
  <span m='1678760'>by</span> <span m='1678900'>this</span> <span m='1679170'>matrix,</span>
  <span m='1679710'>which</span> <span m='1679920'>would</span> <span m='1680050'>be</span>
  <span m='1680160'>1,024</span> <span m='1681030'>squared</span> <span m='1681520'>is</span>
  <span m='1681660'>now</span> <span m='1681920'>practically</span> <span m='1682570'>cut</span>
  <span m='1682800'>in</span> <span m='1682940'>half.</span> <span m='1684560'>Because</span>
  <span m='1684780'>this</span> <span m='1684960'>is</span> <span m='1685150'>nothing.</span>
  <span m='1686290'>And</span> <span m='1686620'>we</span> <span m='1686750'>have</span>
  <span m='1687120'>just</span> <span m='1688180'>this</span> <span m='1688520'>diagonal</span>
  <span m='1689160'>multiplication</span> <span m='1689980'>to do,</span> <span m='1690310'>and
  of</span> <span m='1690400'>course</span> <span m='1690640'>this</span> <span m='1690850'>is</span>
  <span m='1691000'>the</span> <span m='1691120'>same</span> <span m='1691440'>as</span>
  <span m='1691560'>that,</span> <span m='1691810'>just</span> <span m='1692060'>with</span>
  <span m='1692210'>minus</span> <span m='1692610'>signs.</span> <span m='1692900'>So</span>
  <span m='1693360'>the</span> <span m='1693510'>total</span> <span m='1693860'>multiplications</span>
  <span m='1694710'>we</span> <span m='1694810'>have</span> <span m='1695050'>to</span>
  <span m='1695190'>do,</span> <span m='1695890'>the</span> <span m='1696120'>total</span>
  <span m='1696510'>number</span> <span m='1696770'>of</span> <span m='1696860'>twiddle</span>
  <span m='1697200'>factors,</span> <span m='1697780'>is</span> <span m='1698240'>just</span>
  <span m='1698470'>512,</span> <span m='1699750'>and</span> <span m='1699970'>then</span>
  <span m='1700410'>we're</span> <span m='1700970'>golden.</span> <span m='1702340'>So</span>
  <span m='1702520'>we've</span> <span m='1702680'>got</span> <span m='1702850'>half</span>
  <span m='1703200'>the</span> <span m='1703320'>work</span> <span m='1703660'>plus</span>
  <span m='1703930'>512,</span> <span m='1705090'>512</span> <span m='1706040'>operations.</span>
  <span m='1707690'>That's</span> <span m='1708190'>pretty</span> <span m='1708600'>good.</span>
  <span m='1710540'>And</span> <span m='1710800'>of</span> <span m='1710910'>course</span>
  <span m='1712120'>it</span> <span m='1712370'>gets</span> <span m='1712610'>better.</span>
  </p><p><span m='1713060'>How?</span> <span m='1715980'>Once</span> <span m='1716250'>you</span>
  <span m='1716340'>have</span> <span m='1716580'>the</span> <span m='1716710'>idea</span>
  <span m='1717070'>of</span> <span m='1717160'>getting</span> <span m='1717470'>down</span>
  <span m='1717750'>to</span> <span m='1717860'>512,</span> <span m='1718680'>what</span>
  <span m='1718870'>are</span> <span m='1718940'>you</span> <span m='1719000'>going</span>
  <span m='1719140'>to</span> <span m='1719250'>do</span> <span m='1719490'>now?</span>
  <span m='1719760'>This</span> <span m='1719950'>is</span> <span m='1720110'>the</span>
  <span m='1720210'>computer</span> <span m='1720680'>scientist's</span> <span m='1722200'>favorite</span>
  <span m='1723640'>idea.</span> <span m='1726070'>Do</span> <span m='1726230'>it</span>
  <span m='1726360'>again.</span> <span m='1727540'>That's</span> <span m='1727780'>what</span>
  <span m='1727960'>it</span> <span m='1728040'>comes</span> <span m='1728310'>to.</span>
  <span m='1728900'>Whatever</span> <span m='1729410'>worked</span> <span m='1729810'>for</span>
  <span m='1730000'>1,024</span> <span m='1730960'>to</span> <span m='1731060'>get</span>
  <span m='1731270'>to</span> <span m='1731400'>512</span> <span m='1732490'>is</span>
  <span m='1732670'>going</span> <span m='1732850'>to</span> <span m='1732930'>work.</span>
  <span m='1733200'>So</span> <span m='1733730'>now</span> <span m='1734080'>I'll
  split</span> <span m='1734540'>this</span> <span m='1734840'>up</span> <span m='1735320'>into,</span>
  <span m='1736890'>well,</span> <span m='1737150'>each</span> <span m='1737430'>512,</span>
  <span m='1738720'>so</span> <span m='1738950'>now</span> <span m='1739200'>I</span>
  <span m='1739270'>have</span> <span m='1739470'>to</span> <span m='1739620'>do,</span>
  <span m='1740270'>yeah.</span> <span m='1741350'>Let</span> <span m='1741710'>me</span>
  <span m='1741820'>write</span> <span m='1742170'>F_512</span> <span m='1745400'>will</span>
  <span m='1745680'>be,</span> <span m='1746280'>it's</span> <span m='1746470'>now</span>
  <span m='1746770'>smaller.</span> <span m='1747860'>An</span> <span m='1748060'>I,</span>
  <span m='1748770'>an</span> <span m='1748970'>I,</span> <span m='1749060'>and</span>
  <span m='1749780'>a</span> <span m='1749880'>D</span> <span m='1750570'>and</span>
  <span m='1750740'>a</span> <span m='1750830'>minus</span> <span m='1751260'>D</span>
  <span m='1752480'>for</span> <span m='1752660'>the</span> <span m='1753320'>512</span>
  <span m='1754190'>size,</span> <span m='1755370'>of</span> <span m='1755820'>F_256,</span>
  <span m='1757960'>256</span> <span m='1760110'>and</span> <span m='1760390'>then</span>
  <span m='1760780'>the</span> <span m='1761450'>permutation,</span> <span m='1762480'>the</span>
  <span m='1762610'>odd-even</span> <span m='1763350'>permutation</span> <span m='1764240'>P.</span>
  <span m='1765170'>So</span> <span m='1766290'>we're</span> <span m='1766480'>doing</span>
  <span m='1766820'>this</span> <span m='1767060'>idea</span> <span m='1767710'>in</span>
  <span m='1767930'>there,</span> <span m='1768470'>and</span> <span m='1769070'>in</span>
  <span m='1769290'>there.</span> <span m='1770960'>So</span> <span m='1771190'>it's</span>
  <span m='1771390'>just</span> <span m='1771630'>recursive.</span> <span m='1778960'>Recursive.</span>
  <span m='1779200'>And now, if</span> <span m='1779420'>we</span> <span m='1779700'>go</span>
  <span m='1780010'>all</span> <span m='1780180'>the</span> <span m='1780280'>way,</span>
  <span m='1781440'>so</span> <span m='1781730'>you</span> <span m='1781920'>see</span>
  <span m='1782140'>why</span> <span m='1782430'>I keep</span> <span m='1782710'>taking</span>
  <span m='1783110'>powers</span> <span m='1783520'>of</span> <span m='1783680'>two.</span>
  <span m='1786400'>It's</span> <span m='1786760'>natural</span> <span m='1787330'>to
  have</span> <span m='1787560'>powers</span> <span m='1787970'>of</span> <span m='1788120'>two.</span>
  <span m='1788390'>Two</span> <span m='1788670'>or</span> <span m='1788850'>three.</span>
  <span m='1789410'>Three</span> <span m='1789750'>is</span> <span m='1789940'>also</span>
  <span m='1790860'>good.</span> <span m='1791190'>I</span> <span m='1791270'>mean,</span>
  <span m='1791540'>all</span> <span m='1791730'>this</span> <span m='1791960'>gets</span>
  <span m='1792200'>so</span> <span m='1792420'>optimized</span> <span m='1793560'>that</span>
  <span m='1794360'>powers</span> <span m='1794780'>of</span> <span m='1794980'>two</span>
  <span m='1795550'>or</span> <span m='1795750'>three</span> <span m='1796270'>are</span>
  <span m='1796410'>pretty</span> <span m='1796760'>good.</span> <span m='1797880'>And</span>
  <span m='1798130'>you</span> <span m='1798260'>just</span> <span m='1798570'>use</span>
  <span m='1798810'>the</span> <span m='1798940'>same</span> <span m='1799290'>idea.</span>
  <span m='1800320'>There'd</span> <span m='1800570'>be</span> <span m='1800680'>a</span>
  <span m='1800780'>similar</span> <span m='1801240'>idea</span> <span m='1801520'>here</span>
  <span m='1801800'>for,</span> <span m='1804140'>if</span> <span m='1804370'>I</span>
  <span m='1804480'>was</span> <span m='1805240'>doing</span> <span m='1806230'>instead</span>
  <span m='1806720'>of</span> <span m='1806860'>odd-even,</span> <span m='1807690'>even-odd</span>
  <span m='1808350'>I</span> <span m='1808530'>was</span> <span m='1808820'>doing</span>
  <span m='1809950'>maybe</span> <span m='1810310'>three</span> <span m='1811680'>groups.</span>
  <span m='1812110'>But</span> <span m='1812990'>stick</span> <span m='1813350'>with</span>
  <span m='1813550'>two,</span> <span m='1813860'>that's</span> <span m='1814120'>fine.</span>
  <span m='1819600'>Then</span> <span m='1820040'>you</span> <span m='1820250'>might</span>
  <span m='1820590'>ask,</span> <span m='1822770'>if</span> <span m='1823010'>you</span>
  <span m='1823130'>were</span> <span m='1823400'>a</span> <span m='1823490'>worrier</span>
  <span m='1824130'>I</span> <span m='1824280'>guess</span> <span m='1824580'>you</span>
  <span m='1824660'>might</span> <span m='1824910'>ask</span> <span m='1825220'>what</span>
  <span m='1825410'>if</span> <span m='1825540'>it's</span> <span m='1825700'>not</span>
  <span m='1825970'>a</span> <span m='1826040'>power</span> <span m='1826390'>of</span>
  <span m='1826540'>two.</span> <span m='1830650'>I</span> <span m='1830740'>think</span>
  <span m='1830950'>you</span> <span m='1831020'>just</span> <span m='1831240'>add</span>
  <span m='1831490'>in</span> <span m='1831710'>zeroes.</span> <span m='1832800'>Just</span>
  <span m='1833760'>pad</span> <span m='1834040'>it</span> <span m='1834170'>out</span>
  <span m='1835150'>to</span> <span m='1835320'>be</span> <span m='1835520'>the</span>
  <span m='1835680'>next</span> <span m='1836060'>power</span> <span m='1836510'>of
  two.</span> <span m='1841010'>Nothing</span> <span m='1841590'>difficult</span>
  <span m='1842080'>there.</span> <span m='1843760'>I</span> <span m='1843850'>think</span>
  <span m='1844100'>that's</span> <span m='1844310'>right.</span> <span m='1844920'>Hope</span>
  <span m='1845170'>that's</span> <span m='1845360'>right.</span> <span m='1849750'>And</span>
  <span m='1850300'>once</span> <span m='1850620'>this</span> <span m='1850820'>idea</span>
  <span m='1851240'>came</span> <span m='1851460'>out,</span> <span m='1851660'>of</span>
  <span m='1851750'>course,</span> <span m='1852100'>people</span> <span m='1852500'>started</span>
  <span m='1852860'>looking.</span> <span m='1855690'>What</span> <span m='1856820'>if</span>
  <span m='1857120'>the</span> <span m='1857240'>number</span> <span m='1857580'>here</span>
  <span m='1857850'>was</span> <span m='1858080'>prime?</span> <span m='1860110'>And</span>
  <span m='1860250'>found</span> <span m='1860570'>another</span> <span m='1862480'>neat</span>
  <span m='1862920'>bit</span> <span m='1863110'>of</span> <span m='1863220'>algebra</span>
  <span m='1865790'>that</span> <span m='1866130'>worked</span> <span m='1866560'>OK</span>
  <span m='1866940'>for</span> <span m='1867110'>prime</span> <span m='1867470'>numbers.</span>
  <span m='1868020'>Using</span> <span m='1869690'>a</span> <span m='1869750'>little</span>
  <span m='1869980'>bit</span> <span m='1870150'>of</span> <span m='1870230'>number</span>
  <span m='1870610'>theory.</span> <span m='1871680'>But</span> <span m='1872810'>the</span>
  <span m='1873330'>ultimate</span> <span m='1873920'>winner</span> <span m='1874680'>was</span>
  <span m='1874880'>this</span> <span m='1875090'>one.</span> <span m='1876290'>So</span>
  <span m='1876990'>maybe</span> <span m='1877370'>I'll</span> <span m='1877530'>just</span>
  <span m='1881210'>refer</span> <span m='1881750'>you</span> <span m='1882050'>to</span>
  <span m='1882830'>those</span> <span m='1883170'>pages</span> <span m='1883680'>in</span>
  <span m='1883820'>the</span> <span m='1883910'>book,</span> <span m='1884860'>where</span>
  <span m='1885710'>you'll</span> <span m='1885910'>spot</span> <span m='1886380'>this</span>
  <span m='1887600'>matrix</span> <span m='1888440'>equality.</span> <span m='1889700'>And</span>
  <span m='1889990'>then</span> <span m='1891300'>next</span> <span m='1891660'>to</span>
  <span m='1891780'>it</span> <span m='1892070'>is</span> <span m='1892300'>the</span>
  <span m='1892430'>algebra</span> <span m='1893230'>that</span> <span m='1893400'>you</span>
  <span m='1893480'>have</span> <span m='1893730'>to</span> <span m='1893890'>do</span>
  <span m='1894150'>to</span> <span m='1894300'>check</span> <span m='1894710'>it.</span>
  <span m='1897200'>I</span> <span m='1897370'>can</span> <span m='1897560'>just</span>
  <span m='1897770'>say,</span> <span m='1899340'>because</span> <span m='1899930'>I</span>
  <span m='1900040'>want</span> <span m='1900350'>you</span> <span m='1900460'>to</span>
  <span m='1901200'>look</span> <span m='1901870'>to</span> <span m='1902020'>the</span>
  <span m='1902110'>right</span> <span m='1902420'>spot</span> <span m='1902910'>there,</span>
  <span m='1903120'>maybe</span> <span m='1903420'>I'll</span> <span m='1903650'>take</span>
  <span m='1903970'>out</span> <span m='1904290'>the</span> <span m='1905070'>great--</span>
  <span m='1906030'>This</span> <span m='1906220'>is</span> <span m='1906390'>sometimes</span>
  <span m='1907190'>called</span> <span m='1907620'>after</span> <span m='1908020'>Parseval,</span>
  <span m='1909120'>or</span> <span m='1909790'>some</span> <span m='1910030'>other</span>
  <span m='1910220'>person.</span> <span m='1913200'>Yeah,</span> <span m='1914010'>the</span>
  <span m='1914150'>algebra--</span> </p><p><span m='1916850'>Let</span> <span m='1916990'>me</span>
  <span m='1917110'>start</span> <span m='1917460'>the</span> <span m='1917590'>algebra</span>
  <span m='1918090'>that</span> <span m='1918280'>made</span> <span m='1918540'>this</span>
  <span m='1918750'>thing</span> <span m='1919060'>work.</span> <span m='1922820'>We</span>
  <span m='1923320'>want</span> <span m='1923660'>the</span> <span m='1923970'>sum,</span>
  <span m='1924770'>when</span> <span m='1925010'>we</span> <span m='1925120'>multiply</span>
  <span m='1926290'>Fourier,</span> <span m='1927800'>F</span> <span m='1928120'>times</span>
  <span m='1928440'>something,</span> <span m='1929360'>we</span> <span m='1929610'>want</span>
  <span m='1930080'>the</span> <span m='1930390'>sum</span> <span m='1930890'>of</span>
  <span m='1931360'>w^(jk),</span> <span m='1934370'>right?</span> <span m='1934760'>That's</span>
  <span m='1935070'>the</span> <span m='1935460'>coefficient,</span> <span m='1936150'>that's</span>
  <span m='1936380'>the</span> <span m='1936490'>entry</span> <span m='1936880'>of</span>
  <span m='1937020'>F.</span> <span m='1938060'>Times</span> <span m='1940550'>c_k.</span>
  <span m='1943040'>Summed</span> <span m='1943490'>from</span> <span m='1943960'>k=0</span>
  <span m='1945340'>to</span> <span m='1945520'>N-1.</span> <span m='1946930'>To</span>
  <span m='1947050'>1,023.</span> <span m='1950990'>That's</span> <span m='1952180'>the</span>
  <span m='1953860'>y_j</span> <span m='1957720'>that</span> <span m='1957970'>we're</span>
  <span m='1958970'>trying</span> <span m='1959230'>to</span> <span m='1959300'>compute.</span>
  <span m='1960220'>We're</span> <span m='1960460'>computing</span> <span m='1961230'>1,024</span>
  <span m='1961650'>y's</span> <span m='1963110'>from</span> <span m='1963330'>1,024</span>
  <span m='1964320'>c's</span> <span m='1964790'>by</span> <span m='1964990'>adding</span>
  <span m='1965370'>up</span> <span m='1965520'>the</span> <span m='1965650'>Fourier</span>
  <span m='1965880'>series</span> <span m='1966850'>when</span> <span m='1967060'>we</span>
  <span m='1967160'>multiply</span> <span m='1967660'>by</span> <span m='1967920'>F.</span>
  <span m='1968100'>This</span> <span m='1968300'>is</span> <span m='1968470'>F,</span>
  <span m='1969130'>this</span> <span m='1969310'>is</span> <span m='1970410'>the</span>
  <span m='1970520'>equation</span> <span m='1971080'>y=Fc</span> <span m='1973290'>written</span>
  <span m='1975380'>with</span> <span m='1975600'>subscripts.</span> <span m='1980770'>So</span>
  <span m='1980940'>this</span> <span m='1981110'>is</span> <span m='1981220'>what</span>
  <span m='1981370'>the</span> <span m='1981480'>matrices</span> <span m='1981690'>are</span>
  <span m='1982210'>doing,</span> <span m='1982630'>and now</span> <span m='1982870'>where</span>
  <span m='1983490'>do</span> <span m='1983640'>I</span> <span m='1983790'>find</span>
  <span m='1984340'>that</span> <span m='1985260'>512</span> <span m='1986180'>thing?</span>
  <span m='1987150'>How</span> <span m='1987390'>do</span> <span m='1987530'>I</span>
  <span m='1987660'>get</span> <span m='1987980'>M</span> <span m='1988510'>into</span>
  <span m='1988810'>the</span> <span m='1988940'>picture,</span> <span m='1989400'>remembering</span>
  <span m='1990050'>that</span> <span m='1991310'>the</span> <span m='1992680'>w_N</span>
  <span m='1994170'>squared</span> <span m='1995090'>was</span> <span m='1995380'>w_M,</span>
  <span m='1996560'>right?</span> <span m='1996910'>That's</span> <span m='1997200'>what</span>
  <span m='1997390'>we</span> <span m='1997510'>saw.</span> <span m='2000060'>This</span>
  <span m='2000350'>is</span> <span m='2000580'>the</span> <span m='2001180'>big</span>
  <span m='2001460'>number,</span> <span m='2001790'>this</span> <span m='2002020'>is</span>
  <span m='2002190'>half</span> <span m='2002490'>of</span> <span m='2002610'>it,</span>
  <span m='2003140'>so</span> <span m='2003400'>this</span> <span m='2003620'>is</span>
  <span m='2004420'>a</span> <span m='2004670'>little</span> <span m='2005030'>bit</span>
  <span m='2005240'>of</span> <span m='2005320'>the</span> <span m='2005410'>part</span>
  <span m='2005810'>around</span> <span m='2006160'>the</span> <span m='2006270'>circle.</span>
  <span m='2006750'>When</span> <span m='2006940'>I</span> <span m='2007020'>go</span>
  <span m='2007160'>twice</span> <span m='2007600'>as</span> <span m='2007760'>far</span>
  <span m='2007990'>I</span> <span m='2008070'>get</span> <span m='2008290'>to</span>
  <span m='2008410'>the</span> <span m='2008540'>other</span> <span m='2008750'>one.</span>
  <span m='2009590'>So</span> <span m='2010970'>that's</span> <span m='2011400'>the</span>
  <span m='2012750'>thing</span> <span m='2013000'>that</span> <span m='2013130'>we've</span>
  <span m='2013260'>got to</span> <span m='2013500'>use.</span> <span m='2014510'>Everything</span>
  <span m='2015950'>is</span> <span m='2016120'>going to</span> <span m='2016380'>depend</span>
  <span m='2016780'>on</span> <span m='2016920'>that.</span> <span m='2017430'>So</span>
  <span m='2018940'>this</span> <span m='2019190'>was</span> <span m='2019400'>w_N,</span>
  <span m='2020130'>of</span> <span m='2020260'>course.</span> <span m='2021230'>This</span>
  <span m='2021460'>is</span> <span m='2021620'>the</span> <span m='2021760'>N</span>
  <span m='2022010'>by</span> <span m='2022200'>N transform.</span> <span m='2023750'>So</span>
  <span m='2023960'>now</span> <span m='2024280'>comes</span> <span m='2024650'>what,</span>
  <span m='2024930'>what's</span> <span m='2025250'>the</span> <span m='2025390'>key</span>
  <span m='2025640'>idea?</span> <span m='2027010'>The key</span> <span m='2027290'>idea
  is</span> <span m='2027920'>split</span> <span m='2028360'>into</span> <span m='2028630'>even</span>
  <span m='2029010'>and</span> <span m='2029110'>odd.</span> <span m='2029960'>And</span>
  <span m='2030220'>then</span> <span m='2030420'>use</span> <span m='2030750'>this.</span>
  <span m='2031640'>So</span> <span m='2031820'>split</span> <span m='2032210'>into</span>
  <span m='2032540'>the</span> <span m='2032770'>even</span> <span m='2033220'>ones</span>
  <span m='2033690'>and</span> <span m='2033940'>the</span> <span m='2034050'>odd</span>
  <span m='2034340'>ones.</span> <span m='2035160'>So</span> <span m='2035320'>I</span>
  <span m='2035430'>write</span> <span m='2035770'>this</span> <span m='2035990'>as</span>
  <span m='2036210'>two</span> <span m='2036560'>separate</span> <span m='2037230'>sums,</span>
  <span m='2038020'>a</span> <span m='2038230'>sum</span> <span m='2039510'>for</span>
  <span m='2039670'>the</span> <span m='2039850'>even</span> <span m='2040280'>ones.</span>
  <span m='2041060'>w_N,</span> <span m='2044710'>now,</span> <span m='2045790'>so</span>
  <span m='2046430'>now</span> <span m='2046920'>the</span> <span m='2048220'>even</span>
  <span m='2048720'>c_k,</span> <span m='2049390'>so</span> <span m='2049570'>I'm</span>
  <span m='2049670'>going</span> <span m='2049840'>to</span> <span m='2049900'>multiply</span>
  <span m='2050520'>by</span> <span m='2050860'>c_(2k).</span> <span m='2054330'>These</span>
  <span m='2054640'>are</span> <span m='2054700'>the</span> <span m='2054760'>ones</span>
  <span m='2055010'>with</span> <span m='2055180'>even,</span> <span m='2056120'>and</span>
  <span m='2056320'>the</span> <span m='2056480'>sum</span> <span m='2056820'>is</span>
  <span m='2056970'>only</span> <span m='2057260'>going</span> <span m='2057530'>to</span>
  <span m='2057640'>go</span> <span m='2058030'>from</span> <span m='2058420'>zero</span>
  <span m='2058860'>to</span> <span m='2059430'>M-1,</span> <span m='2060580'>right?</span>
  <span m='2063070'>This</span> <span m='2063260'>is</span> <span m='2063400'>only</span>
  <span m='2063670'>half</span> <span m='2063990'>of</span> <span m='2064090'>the</span>
  <span m='2064190'>terms.</span> <span m='2065080'>And</span> <span m='2065300'>then</span>
  <span m='2065590'>look</span> <span m='2065870'>on</span> <span m='2066060'>the</span>
  <span m='2066170'>other</span> <span m='2066450'>half,</span> <span m='2067190'>plus</span>
  <span m='2068310'>the</span> <span m='2068490'>same</span> <span m='2068900'>sum</span>
  <span m='2071130'>of--</span> <span m='2071270'>But</span> <span m='2071440'>I</span>
  <span m='2071530'>didn't</span> <span m='2071810'>finish</span> <span m='2072160'>here.</span>
  <span m='2072340'>Let</span> <span m='2072470'>me</span> <span m='2072610'>finish.</span>
  <span m='2073280'>So</span> <span m='2073490'>I'm</span> <span m='2073640'>just</span>
  <span m='2073980'>picking</span> <span m='2074390'>out,</span> <span m='2075140'>I'm</span>
  <span m='2075330'>taking,</span> <span m='2075870'>instead</span> <span m='2076250'>of</span>
  <span m='2076360'>k</span> <span m='2076640'>I'm</span> <span m='2076850'>doing</span>
  <span m='2077150'>2k.</span> <span m='2078320'>So</span> <span m='2078490'>I</span>
  <span m='2078570'>have</span> <span m='2078830'>j</span> <span m='2079390'>times</span>
  <span m='2079940'>2k</span> <span m='2080830'>here.</span> <span m='2083430'>And</span>
  <span m='2083600'>now</span> <span m='2083750'>these</span> <span m='2084040'>will</span>
  <span m='2084150'>be</span> <span m='2084270'>the</span> <span m='2084440'>odd</span>
  <span m='2084780'>ones.</span> <span m='2085150'>c_(2k+1),</span> <span m='2089460'>and</span>
  <span m='2089860'>omega_N</span> <span m='2089950'>to</span> <span m='2092430'>the</span>
  <span m='2094310'>j(2k+1).</span> <span m='2100670'>It's</span> <span m='2100840'>a</span>
  <span m='2101700'>lot</span> <span m='2101990'>to</span> <span m='2102130'>ask</span>
  <span m='2102460'>you.</span> <span m='2103330'>To</span> <span m='2105300'>focus</span>
  <span m='2105960'>on</span> <span m='2107060'>this</span> <span m='2108850'>bit</span>
  <span m='2109060'>of</span> <span m='2109170'>algebra.</span> <span m='2111530'>I</span>
  <span m='2111810'>hope</span> <span m='2112080'>you're</span> <span m='2112230'>going
  to</span> <span m='2112670'>go</span> <span m='2112800'>away</span> <span m='2113140'>feeling,</span>
  <span m='2114230'>well</span> <span m='2114780'>it's</span> <span m='2115050'>pretty</span>
  <span m='2115380'>darn</span> <span m='2115760'>simple.</span> <span m='2117170'>I</span>
  <span m='2117290'>mean</span> <span m='2117720'>there'll</span> <span m='2118130'>be</span>
  <span m='2118230'>a</span> <span m='2118340'>lot</span> <span m='2118580'>of</span>
  <span m='2118680'>indices,</span> <span m='2118970'>and</span> <span m='2119470'>if</span>
  <span m='2119590'>I</span> <span m='2119670'>push</span> <span m='2120010'>it</span>
  <span m='2120120'>all</span> <span m='2120300'>the</span> <span m='2120390'>way</span>
  <span m='2120580'>through</span> <span m='2120900'>there'll</span> <span m='2121040'>be</span>
  <span m='2121180'>a</span> <span m='2121270'>few</span> <span m='2121470'>more.</span>
  </p><p><span m='2122650'>But</span> <span m='2122860'>the</span> <span m='2123010'>point</span>
  <span m='2123370'>is,</span> <span m='2123560'>it's</span> <span m='2123710'>pretty</span>
  <span m='2124010'>darn</span> <span m='2124300'>simple.</span> <span m='2125250'>For</span>
  <span m='2125370'>example,</span> <span m='2125860'>this</span> <span m='2126170'>term.</span>
  <span m='2126730'>What</span> <span m='2126930'>have</span> <span m='2127040'>I</span>
  <span m='2127150'>got</span> <span m='2127390'>there?</span> <span m='2129700'>Look</span>
  <span m='2129960'>at</span> <span m='2130080'>that</span> <span m='2130320'>term,</span>
  <span m='2130580'>that's</span> <span m='2130830'>beautiful.</span> <span m='2133450'>That's</span>
  <span m='2134020'>w_N</span> <span m='2134970'>squared.</span> <span m='2136620'>What</span>
  <span m='2136920'>is</span> <span m='2137140'>w_N</span> <span m='2137790'>squared?</span>
  <span m='2140650'>It's</span> <span m='2140980'>w_M.</span> <span m='2142630'>So</span>
  <span m='2142840'>instead</span> <span m='2143300'>of</span> <span m='2143440'>w_N</span>
  <span m='2144210'>squared,</span> <span m='2144670'>I'm</span> <span m='2144870'>going</span>
  <span m='2145060'>to</span> <span m='2145140'>replace</span> <span m='2145800'>that</span>
  <span m='2146460'>w_N</span> <span m='2147070'>squared</span> <span m='2147470'>by</span>
  <span m='2147640'>w_M.</span> <span m='2149680'>And</span> <span m='2149940'>the</span>
  <span m='2150120'>sum</span> <span m='2150420'>goes</span> <span m='2150680'>from</span>
  <span m='2150860'>zero</span> <span m='2151170'>to</span> <span m='2151310'>M-1,</span>
  <span m='2152160'>and</span> <span m='2152310'>what</span> <span m='2152550'>does</span>
  <span m='2152710'>that</span> <span m='2152920'>represent?</span> <span m='2156050'>That</span>
  <span m='2156300'>represents</span> <span m='2156940'>the</span> <span m='2157080'>F_512</span>
  <span m='2158060'>multiplication,</span> <span m='2158980'>the</span> <span m='2159140'>half-size</span>
  <span m='2159780'>transform.</span> <span m='2160840'>It</span> <span m='2161060'>goes</span>
  <span m='2161400'>halfway,</span> <span m='2162360'>it</span> <span m='2162580'>operates</span>
  <span m='2163120'>on</span> <span m='2163320'>the</span> <span m='2163450'>even</span>
  <span m='2163880'>ones,</span> <span m='2164280'>and</span> <span m='2164490'>it</span>
  <span m='2164570'>uses</span> <span m='2166260'>the</span> <span m='2166440'>M.</span>
  <span m='2168140'>It's</span> <span m='2168420'>just</span> <span m='2168760'>perfectly,</span>
  <span m='2169740'>so</span> <span m='2169960'>this</span> <span m='2170260'>is</span>
  <span m='2170460'>nothing</span> <span m='2171000'>but</span> <span m='2172000'>the</span>
  <span m='2172450'>Fourier</span> <span m='2173000'>matrix,</span> <span m='2173980'>the</span>
  <span m='2174170'>M</span> <span m='2174480'>by</span> <span m='2174670'>M</span>
  <span m='2175100'>Fourier</span> <span m='2175510'>matrix,</span> <span m='2176460'>acting</span>
  <span m='2177020'>on</span> <span m='2177390'>the</span> <span m='2177650'>even</span>
  <span m='2178300'>c's.</span> <span m='2181950'>That's</span> <span m='2182230'>what</span>
  <span m='2182400'>that</span> <span m='2182630'>is.</span> <span m='2183110'>And</span>
  <span m='2183280'>that's</span> <span m='2183590'>why</span> <span m='2185010'>we</span>
  <span m='2185190'>get</span> <span m='2185410'>these</span> <span m='2185670'>identities.</span>
  <span m='2186630'>That's</span> <span m='2186870'>why</span> <span m='2187050'>we</span>
  <span m='2187200'>get</span> <span m='2187400'>these</span> <span m='2187630'>identities,</span>
  <span m='2188310'>because</span> <span m='2188810'>they're</span> <span m='2189030'>acting</span>
  <span m='2189430'>on</span> <span m='2189610'>the</span> <span m='2189730'>even--</span>
  <span m='2192130'>The</span> <span m='2192320'>top</span> <span m='2192650'>half</span>
  <span m='2193400'>is</span> <span m='2193650'>the</span> <span m='2193770'>even</span>
  <span m='2194130'>guy.</span> <span m='2197470'>OK,</span> <span m='2198810'>this</span>
  <span m='2199070'>is</span> <span m='2199230'>almost</span> <span m='2199700'>as</span>
  <span m='2199840'>good.</span> <span m='2200110'>This</span> <span m='2200300'>is</span>
  <span m='2200430'>the</span> <span m='2200560'>odd</span> <span m='2200970'>c's.</span>
  <span m='2202410'>Here</span> <span m='2202720'>I</span> <span m='2202920'>have,</span>
  <span m='2203660'>now</span> <span m='2204100'>do</span> <span m='2204270'>I</span>
  <span m='2204380'>have</span> <span m='2204720'>w_M</span> <span m='2205700'>here?</span>
  <span m='2207900'>I've</span> <span m='2208560'>got to</span> <span m='2208860'>have</span>
  <span m='2209090'>w_M.</span> <span m='2212730'>Well,</span> <span m='2213250'>you</span>
  <span m='2213460'>can</span> <span m='2213640'>see.</span> <span m='2214210'>It's</span>
  <span m='2214440'>not</span> <span m='2214660'>quite</span> <span m='2214950'>coming</span>
  <span m='2215340'>out</span> <span m='2215510'>right,</span> <span m='2215840'>and</span>
  <span m='2216010'>that's</span> <span m='2216320'>the</span> <span m='2216420'>twiddle</span>
  <span m='2216580'>factor.</span> <span m='2218300'>I</span> <span m='2218490'>have</span>
  <span m='2218720'>to</span> <span m='2218890'>take</span> <span m='2219210'>out</span>
  <span m='2219470'>a</span> <span m='2219570'>w_N</span> <span m='2220120'>to</span>
  <span m='2220610'>the</span> <span m='2220720'>power</span> <span m='2221160'>j</span>
  <span m='2222410'>to</span> <span m='2222530'>make</span> <span m='2222790'>things</span>
  <span m='2223130'>good.</span> <span m='2225200'>And</span> <span m='2225360'>when</span>
  <span m='2225500'>I</span> <span m='2225590'>take</span> <span m='2225860'>out</span>
  <span m='2226070'>that</span> <span m='2226280'>w_N</span> <span m='2226930'>to</span>
  <span m='2227010'>the</span> <span m='2227090'>power</span> <span m='2227500'>j,</span>
  <span m='2228470'>that's</span> <span m='2228830'>what</span> <span m='2229140'>goes</span>
  <span m='2229810'>in</span> <span m='2230230'>the D,</span> <span m='2230990'>in</span>
  <span m='2231180'>the</span> <span m='2231280'>diagonal</span> <span m='2231800'>matrix.</span>
  <span m='2234820'>Yeah.</span> <span m='2236010'>I</span> <span m='2236180'>won't</span>
  <span m='2236480'>go</span> <span m='2236640'>more</span> <span m='2236890'>than</span>
  <span m='2237050'>that.</span> <span m='2238610'>You</span> <span m='2238790'>couldn't,</span>
  <span m='2240840'>there's</span> <span m='2241440'>no</span> <span m='2241590'>reason</span>
  <span m='2242100'>to</span> <span m='2243380'>do</span> <span m='2243560'>everything</span>
  <span m='2244130'>here</span> <span m='2244380'>on</span> <span m='2244550'>the</span>
  <span m='2244650'>board</span> <span m='2245060'>when</span> <span m='2245300'>the</span>
  <span m='2245860'>main</span> <span m='2246300'>point</span> <span m='2246690'>is</span>
  <span m='2246850'>there.</span> <span m='2247620'>And</span> <span m='2247840'>then</span>
  <span m='2247990'>the</span> <span m='2248080'>point</span> <span m='2248440'>was</span>
  <span m='2248620'>recursion</span> <span m='2249360'>and</span> <span m='2249480'>then,</span>
  <span m='2249690'>oh,</span> <span m='2250250'>let</span> <span m='2250380'>me</span>
  <span m='2250860'>complete</span> <span m='2251390'>the</span> <span m='2251490'>recursion.</span>
  <span m='2253180'>So</span> <span m='2253410'>I</span> <span m='2253550'>recurse</span>
  <span m='2254110'>down</span> <span m='2254380'>to</span> <span m='2254510'>256,</span>
  <span m='2256100'>then</span> <span m='2256480'>128,</span> <span m='2257260'>then</span>
  <span m='2257420'>64.</span> <span m='2258520'>And</span> <span m='2258680'>what</span>
  <span m='2258830'>do</span> <span m='2258920'>I</span> <span m='2259040'>get</span>
  <span m='2259280'>in</span> <span m='2259410'>the</span> <span m='2259550'>end?</span>
  <span m='2262390'>What</span> <span m='2262570'>do</span> <span m='2262660'>I</span>
  <span m='2262780'>get</span> <span m='2263490'>altogether,</span> <span m='2264170'>once</span>
  <span m='2264460'>I've</span> <span m='2264970'>got</span> <span m='2265210'>all</span>
  <span m='2265390'>the</span> <span m='2265510'>way</span> <span m='2265690'>down</span>
  <span m='2265990'>to</span> <span m='2266100'>size</span> <span m='2266600'>two?</span>
  <span m='2268440'>I</span> <span m='2268580'>have</span> <span m='2268850'>a</span>
  <span m='2268920'>whole</span> <span m='2269180'>lot</span> <span m='2269390'>of</span>
  <span m='2269500'>these</span> <span m='2269870'>factors</span> <span m='2274830'>down</span>
  <span m='2275250'>in</span> <span m='2276570'>the</span> <span m='2276640'>middle,</span>
  <span m='2277920'>the</span> <span m='2278040'>part</span> <span m='2278310'>that</span>
  <span m='2278400'>used</span> <span m='2278650'>to</span> <span m='2278720'>be</span>
  <span m='2278830'>hard</span> <span m='2279230'>is</span> <span m='2279390'>now</span>
  <span m='2279680'>down</span> <span m='2280080'>to</span> <span m='2280680'>F_2</span>
  <span m='2280990'>or</span> <span m='2281230'>F_1</span> <span m='2281810'>or</span>
  <span m='2281940'>something.</span> <span m='2283060'>So</span> <span m='2283290'>let's</span>
  <span m='2283470'>say</span> <span m='2283710'>F_1,</span> <span m='2284280'>one</span>
  <span m='2284560'>by</span> <span m='2284730'>one,</span> <span m='2285130'>just</span>
  <span m='2285400'>the</span> <span m='2285500'>identity.</span> <span m='2287340'>So</span>
  <span m='2287800'>I</span> <span m='2287960'>go</span> <span m='2288240'>all</span>
  <span m='2288420'>the</span> <span m='2288530'>way.</span> <span m='2289050'>Ten</span>
  <span m='2289440'>steps</span> <span m='2290420'>from</span> <span m='2290680'>1024,</span>
  <span m='2291600'>512,</span> <span m='2292260'>256,</span> <span m='2293420'>every</span>
  <span m='2293740'>time</span> <span m='2294000'>I</span> <span m='2294110'>get</span>
  <span m='2295000'>twiddle</span> <span m='2295410'>factors.</span> <span m='2296090'>Every</span>
  <span m='2296370'>time</span> <span m='2296680'>I</span> <span m='2296760'>get</span>
  <span m='2297090'>P's.</span> <span m='2299200'>A</span> <span m='2299260'>lot</span>
  <span m='2299530'>of</span> <span m='2299630'>P's,</span> <span m='2301510'>but</span>
  <span m='2301950'>the</span> <span m='2302480'>F_512,</span> <span m='2304130'>what</span>
  <span m='2304380'>used to be</span> <span m='2304520'>the</span> <span m='2304630'>hard</span>
  <span m='2304890'>part,</span> <span m='2305150'>has</span> <span m='2305310'>gone</span>
  <span m='2305630'>to</span> <span m='2305770'>the</span> <span m='2305890'>easy</span>
  <span m='2306170'>part.</span> <span m='2309170'>And</span> <span m='2309510'>then</span>
  <span m='2309750'>what</span> <span m='2309960'>do</span> <span m='2310050'>I</span>
  <span m='2310190'>have?</span> <span m='2311250'>I've</span> <span m='2311460'>got</span>
  <span m='2311650'>just</span> <span m='2311890'>a</span> <span m='2311960'>permutation</span>
  <span m='2312820'>there.</span> <span m='2313910'>And</span> <span m='2314290'>this</span>
  <span m='2314690'>is</span> <span m='2317480'>the</span> <span m='2317670'>actual</span>
  <span m='2318160'>work.</span> </p><p><span m='2318920'>This</span> <span m='2319110'>is</span>
  <span m='2319240'>the</span> <span m='2319340'>only</span> <span m='2319630'>work</span>
  <span m='2319950'>left,</span> <span m='2320910'>is</span> <span m='2322570'>the</span>
  <span m='2322780'>matrices</span> <span m='2323490'>like</span> <span m='2323710'>this,</span>
  <span m='2325330'>for</span> <span m='2326770'>different</span> <span m='2327160'>sizes.</span>
  <span m='2329180'>And</span> <span m='2329460'>I</span> <span m='2329510'>have</span>
  <span m='2329680'>to</span> <span m='2329830'>do</span> <span m='2330000'>those.</span>
  <span m='2330970'>I have</span> <span m='2331140'>to</span> <span m='2331290'>do</span>
  <span m='2331400'>all</span> <span m='2331560'>those</span> <span m='2331840'>twiddle</span>
  <span m='2332070'>factors.</span> <span m='2332510'>So</span> <span m='2332690'>how</span>
  <span m='2332880'>many</span> <span m='2333170'>matrices</span> <span m='2333890'>are</span>
  <span m='2334050'>there,</span> <span m='2334210'>there?</span> <span m='2338300'>It's</span>
  <span m='2338580'>the</span> <span m='2338690'>log,</span> <span m='2339140'>right?</span>
  <span m='2340310'>Every</span> <span m='2340640'>time</span> <span m='2340960'>I</span>
  <span m='2341060'>divided</span> <span m='2341540'>by</span> <span m='2341740'>two.</span>
  <span m='2342480'>So</span> <span m='2342700'>if</span> <span m='2342830'>I</span>
  <span m='2342950'>started</span> <span m='2343590'>at</span> <span m='2343660'>1,024,</span>
  <span m='2344930'>I</span> <span m='2345160'>do</span> <span m='2345500'>ten</span>
  <span m='2345840'>times,</span> <span m='2346480'>I have</span> <span m='2346730'>ten</span>
  <span m='2347070'>of</span> <span m='2347160'>those</span> <span m='2347400'>matrices</span>
  <span m='2347780'>and</span> <span m='2348040'>have</span> <span m='2348270'>me</span>
  <span m='2348400'>down</span> <span m='2348750'>to</span> <span m='2349240'>N=1.</span>
  <span m='2351580'>So</span> <span m='2351810'>I've</span> <span m='2351940'>got</span>
  <span m='2352130'>ten</span> <span m='2352390'>of</span> <span m='2352480'>these,</span>
  <span m='2353470'>and</span> <span m='2353640'>each</span> <span m='2353880'>one</span>
  <span m='2354310'>takes</span> <span m='2356800'>1,024</span> <span m='2357490'>or</span>
  <span m='2357990'>maybe</span> <span m='2358350'>only</span> <span m='2358680'>half</span>
  <span m='2359050'>of</span> <span m='2359140'>that.</span> <span m='2359390'>Actually,</span>
  <span m='2360110'>only</span> <span m='2360420'>half</span> <span m='2360770'>because</span>
  <span m='2361160'>this</span> <span m='2361460'>is</span> <span m='2361600'>a</span>
  <span m='2361700'>copy</span> <span m='2362100'>of</span> <span m='2362250'>that.</span>
  <span m='2362790'>I</span> <span m='2362990'>think</span> <span m='2363300'>the</span>
  <span m='2363430'>final</span> <span m='2363850'>count,</span> <span m='2364300'>and</span>
  <span m='2365710'>can I</span> <span m='2365830'>just</span> <span m='2366100'>put</span>
  <span m='2366300'>it</span> <span m='2366430'>here,</span> <span m='2366660'>this</span>
  <span m='2366840'>is</span> <span m='2367020'>the</span> <span m='2367090'>great</span>
  <span m='2367420'>number,</span> <span m='2368680'>is</span> <span m='2370800'>each</span>
  <span m='2371360'>of</span> <span m='2371550'>these</span> <span m='2372040'>took</span>
  <span m='2372350'>N</span> <span m='2372930'>multiplications.</span> <span m='2375400'>But</span>
  <span m='2375610'>there</span> <span m='2375790'>were</span> <span m='2376060'>only</span>
  <span m='2376660'>log to the</span> <span m='2377180'>base two--</span> <span m='2378040'>Oh,</span>
  <span m='2378260'>no.</span> <span m='2378510'>Each</span> <span m='2378800'>of</span>
  <span m='2378890'>them</span> <span m='2379080'>took</span> <span m='2379340'>half</span>
  <span m='2379730'>of</span> <span m='2379890'>N</span> <span m='2380170'>multiplications,</span>
  <span m='2380990'>because</span> <span m='2381780'>the</span> <span m='2381920'>D</span>
  <span m='2382180'>and</span> <span m='2382330'>the</span> <span m='2382380'>minus</span>
  <span m='2382840'>D</span> <span m='2383020'>are</span> <span m='2383160'>just,</span>
  <span m='2384680'>I</span> <span m='2384800'>don't</span> <span m='2385020'>have</span>
  <span m='2385200'>to</span> <span m='2385310'>repeat.</span> <span m='2386240'>So</span>
  <span m='2386420'>half</span> <span m='2386750'>N</span> <span m='2387620'>for</span>
  <span m='2387850'>each</span> <span m='2388150'>factor</span> <span m='2388810'>and</span>
  <span m='2389050'>the</span> <span m='2389140'>number</span> <span m='2389550'>of</span>
  <span m='2389670'>factors</span> <span m='2390320'>is</span> <span m='2390980'>log</span>
  <span m='2391350'>to</span> <span m='2391440'>the</span> <span m='2391540'>base</span>
  <span m='2391850'>two</span> <span m='2392130'>of</span> <span m='2392260'>N.</span>
  <span m='2393110'>Ten,</span> <span m='2393700'>for</span> <span m='2393930'>1,024.</span>
  <span m='2395360'>So</span> <span m='2395530'>that's</span> <span m='2395880'>the</span>
  <span m='2396040'>magic</span> <span m='2396580'>of</span> <span m='2396670'>the</span>
  <span m='2396920'>FFT.</span> <span m='2400120'>OK.</span> <span m='2402980'>It's</span>
  <span m='2403840'>almost</span> <span m='2404340'>all</span> <span m='2404510'>on</span>
  <span m='2404740'>one</span> <span m='2404950'>board,</span> <span m='2405300'>one</span>
  <span m='2405520'>and</span> <span m='2405700'>a</span> <span m='2405760'>half</span>
  <span m='2406080'>boards.</span> <span m='2406920'>To</span> <span m='2410710'>tell</span>
  <span m='2410910'>you</span> <span m='2411060'>the</span> <span m='2411200'>key</span>
  <span m='2411440'>point,</span> <span m='2414200'>odds</span> <span m='2414530'>and</span>
  <span m='2414670'>evens,</span> <span m='2417180'>recursion,</span> <span m='2421000'>twiddle</span>
  <span m='2421390'>factors,</span> <span m='2423040'>getting</span> <span m='2423470'>down</span>
  <span m='2423910'>to</span> <span m='2424080'>the</span> <span m='2424230'>point</span>
  <span m='2424650'>where</span> <span m='2424840'>you</span> <span m='2424980'>only</span>
  <span m='2425270'>have</span> <span m='2425500'>twiddle</span> <span m='2425820'>factors</span>
  <span m='2426310'>left</span> <span m='2426930'>and</span> <span m='2427730'>then</span>
  <span m='2428390'>those</span> <span m='2428690'>multiplications</span> <span m='2430100'>are</span>
  <span m='2430350'>only</span> <span m='2430720'>N</span> <span m='2430980'>log</span>
  <span m='2431230'>N.</span> <span m='2433480'>Good?</span> <span m='2437640'>Yes.</span>
  <span m='2438230'>Right,</span> <span m='2438850'>OK.</span> </p><p><span m='2440180'>Now,</span>
  <span m='2442430'>that's</span> <span m='2443840'>discrete</span> <span m='2444270'>transform.</span>
  <span m='2447840'>The</span> <span m='2448770'>theory</span> <span m='2449120'>behind</span>
  <span m='2449610'>it</span> <span m='2450470'>and</span> <span m='2451010'>the</span>
  <span m='2451120'>fantastic</span> <span m='2452460'>algorithm</span> <span m='2452870'>that</span>
  <span m='2453880'>executes</span> <span m='2454790'>it.</span> <span m='2459000'>Are</span>
  <span m='2459200'>you</span> <span m='2459290'>ready</span> <span m='2459540'>for</span>
  <span m='2459710'>a convolution?</span> <span m='2460600'>Can we</span> <span m='2461170'>start</span>
  <span m='2461860'>on</span> <span m='2462020'>a</span> <span m='2462120'>topic</span>
  <span m='2462710'>that's</span> <span m='2463470'>really</span> <span m='2463810'>quite</span>
  <span m='2464170'>nice,</span> <span m='2464570'>and</span> <span m='2464750'>then</span>
  <span m='2465590'>Friday</span> <span m='2466070'>will</span> <span m='2466300'>be</span>
  <span m='2466750'>the</span> <span m='2467960'>focus</span> <span m='2468560'>on</span>
  <span m='2468770'>convolution.</span> <span m='2470130'>Friday</span> <span m='2470480'>will</span>
  <span m='2470660'>certainly</span> <span m='2471020'>be</span> <span m='2471210'>all</span>
  <span m='2471590'>convolution</span> <span m='2472390'>day.</span> <span m='2474210'>But</span>
  <span m='2474570'>maybe</span> <span m='2474930'>it's</span> <span m='2475360'>not</span>
  <span m='2475700'>a</span> <span m='2475750'>bad</span> <span m='2476040'>idea</span>
  <span m='2476540'>to</span> <span m='2477680'>see</span> <span m='2478120'>now,</span>
  <span m='2478490'>what's</span> <span m='2478800'>the</span> <span m='2478910'>question?</span>
  <span m='2481920'>Let</span> <span m='2482070'>me</span> <span m='2482160'>ask</span>
  <span m='2482440'>that</span> <span m='2482610'>question.</span> <span m='2485310'>OK,</span>
  <span m='2485880'>convolution.</span> <span m='2487990'>So</span> <span m='2488180'>we're</span>
  <span m='2488490'>into</span> <span m='2489070'>the</span> <span m='2489160'>next</span>
  <span m='2489530'>section</span> <span m='2490010'>of</span> <span m='2490110'>the</span>
  <span m='2490210'>book,</span> <span m='2492660'>Section</span> <span m='2493860'>4.4,</span>
  <span m='2495200'>it</span> <span m='2495650'>must be.</span> <span m='2502050'>And</span>
  <span m='2502270'>let</span> <span m='2502380'>me</span> <span m='2502500'>do</span>
  <span m='2502640'>it</span> <span m='2502790'>first</span> <span m='2503270'>for
  a</span> <span m='2503560'>Fourier</span> <span m='2504010'>series.</span> <span
  m='2506510'>I have</span> <span m='2506830'>convolution</span> <span m='2507170'>of</span>
  <span m='2507640'>series,</span> <span m='2508400'>convolution</span> <span m='2509250'>of</span>
  <span m='2509500'>discrete.</span> <span m='2510690'>Convolution</span> <span m='2511570'>of</span>
  <span m='2512310'>integrals,</span> <span m='2513130'>but</span> <span m='2513290'>we</span>
  <span m='2513460'>haven't</span> <span m='2513630'>got</span> <span m='2514000'>there</span>
  <span m='2514200'>yet.</span> <span m='2517490'>So</span> <span m='2518000'>I'll</span>
  <span m='2518190'>do</span> <span m='2518380'>this</span> <span m='2518620'>one,</span>
  <span m='2518960'>this series.</span> <span m='2522370'>So</span> <span m='2522550'>let</span>
  <span m='2522700'>me</span> <span m='2522860'>start</span> <span m='2523230'>with</span>
  <span m='2523720'>a</span> <span m='2523750'>couple</span> <span m='2524090'>of</span>
  <span m='2524200'>series.</span> <span m='2525090'>f(x)</span> <span m='2525450'>is
  the</span> <span m='2526130'>sum</span> <span m='2526630'>of</span> <span m='2527130'>c_k*e^(ikx),</span>
  <span m='2528240'>say.</span> <span m='2531070'>g(x)</span> <span m='2531920'>is
  the</span> <span m='2533230'>sum</span> <span m='2533830'>of</span> <span m='2534470'>some</span>
  <span m='2534730'>other</span> <span m='2535290'>coefficients.</span> <span m='2538430'>And</span>
  <span m='2538670'>I'm</span> <span m='2538790'>going to</span> <span m='2539000'>ask</span>
  <span m='2539420'>you</span> <span m='2539550'>a</span> <span m='2539630'>simple</span>
  <span m='2540050'>question.</span> <span m='2541600'>What</span> <span m='2542000'>are</span>
  <span m='2542150'>the</span> <span m='2542290'>Fourier</span> <span m='2542890'>coefficients</span>
  <span m='2543650'>of</span> <span m='2544690'>f</span> <span m='2545110'>times</span>
  <span m='2545630'>g?</span> <span m='2547550'>If</span> <span m='2547880'>I</span>
  <span m='2548000'>multiply</span> <span m='2548560'>those</span> <span m='2548880'>functions,</span>
  <span m='2555030'>equals</span> <span m='2555690'>something.</span> <span m='2559990'>And</span>
  <span m='2560470'>let</span> <span m='2560650'>me</span> <span m='2560800'>call</span>
  <span m='2561150'>those</span> <span m='2561670'>coefficients,</span> <span m='2562310'>h</span>
  <span m='2562960'>maybe.</span> <span m='2564490'>h_k*e^(ikx),</span> <span m='2566060'>and</span>
  <span m='2566360'>my</span> <span m='2566500'>question</span> <span m='2566990'>is</span>
  <span m='2567590'>what</span> <span m='2568700'>are</span> <span m='2569780'>the</span>
  <span m='2571040'>coefficients</span> <span m='2572920'>h_k</span> <span m='2574580'>of</span>
  <span m='2575610'>f</span> <span m='2576740'>times</span> <span m='2577340'>g?</span>
  <span m='2579590'>That's</span> <span m='2579950'>the</span> <span m='2580050'>question</span>
  <span m='2580470'>that</span> <span m='2580640'>convolution</span> <span m='2581390'>answers.</span>
  <span m='2590550'>Actually,</span> <span m='2592720'>both</span> <span m='2593000'>this</span>
  <span m='2593130'>series</span> <span m='2593610'>and</span> <span m='2593830'>the</span>
  <span m='2593910'>discrete</span> <span m='2594500'>series</span> <span m='2594870'>are</span>
  <span m='2595000'>highly</span> <span m='2595440'>interesting.</span> <span m='2597290'>Highly</span>
  <span m='2597700'>interesting.</span> <span m='2600770'>So</span> <span m='2600940'>here</span>
  <span m='2601160'>I</span> <span m='2601260'>wrote</span> <span m='2601580'>it</span>
  <span m='2602560'>for</span> <span m='2602710'>this</span> <span m='2602860'>series.</span>
  <span m='2605740'>If</span> <span m='2605940'>I</span> <span m='2606020'>write</span>
  <span m='2606310'>it</span> <span m='2606450'>for</span> <span m='2606660'>the</span>
  <span m='2608000'>discrete</span> <span m='2608600'>ones,</span> <span m='2609670'>you'll</span>
  <span m='2610050'>see,</span> <span m='2614090'>so</span> <span m='2614390'>let</span>
  <span m='2614540'>me</span> <span m='2614700'>do</span> <span m='2614910'>it</span>
  <span m='2615030'>over</span> <span m='2615250'>here</span> <span m='2615430'>for</span>
  <span m='2615590'>the</span> <span m='2615720'>discrete</span> <span m='2616160'>one.</span>
  <span m='2616310'>Because</span> <span m='2616650'>I</span> <span m='2616820'>can</span>
  <span m='2617350'>write</span> <span m='2617780'>it</span> <span m='2617910'>out</span>
  <span m='2618290'>for</span> <span m='2618440'>the</span> <span m='2618590'>discrete</span>
  <span m='2619060'>ones.</span> <span m='2619850'>My</span> <span m='2620340'>y's</span>
  <span m='2621620'>are</span> <span m='2622500'>c_0</span> <span m='2623000'>plus</span>
  <span m='2624370'>c_1</span> <span m='2625170'>e</span> <span m='2625980'>t--</span>
  <span m='2626630'>No,</span> <span m='2626950'>w.</span> <span m='2627530'>I</span>
  <span m='2627680'>have</span> <span m='2627890'>this</span> <span m='2628390'>nice</span>
  <span m='2628830'>notation,</span> <span m='2629820'>w.</span> <span m='2631280'>plus</span>
  <span m='2634950'>c_(N-1)*w^(N-1),</span> <span m='2638390'>right?</span> <span
  m='2638870'>That's</span> <span m='2640720'>the--</span> <span m='2642910'>Ooh.</span>
  <span m='2643440'>What's</span> <span m='2643690'>that?</span> <span m='2645630'>I
  haven't</span> <span m='2645960'>got</span> <span m='2646150'>that</span> <span
  m='2646350'>right.</span> <span m='2648000'>Yes,</span> <span m='2648320'>what</span>
  <span m='2648510'>do</span> <span m='2648620'>I</span> <span m='2648740'>want</span>
  <span m='2649050'>now?</span> <span m='2652540'>I</span> <span m='2652800'>need,</span>
  <span m='2654690'>yep.</span> <span m='2655660'>Sorry,</span> <span m='2656020'>I'm</span>
  <span m='2656240'>looking,</span> <span m='2656630'>really</span> <span m='2657020'>I'm</span>
  <span m='2657190'>looking</span> <span m='2657510'>at</span> <span m='2657690'>y_j,</span>
  <span m='2658800'>the</span> <span m='2658970'>j-th</span> <span m='2659480'>component</span>
  <span m='2660090'>of</span> <span m='2660170'>y.</span> <span m='2660960'>So</span>
  <span m='2661150'>I</span> <span m='2661210'>need a</span> <span m='2662200'>w^j,</span>
  <span m='2664240'>w^(j(N-1).)</span> <span m='2666640'>Yeah,</span> <span m='2667900'>OK,</span>
  <span m='2668400'>let</span> <span m='2668540'>me--</span> <span m='2669820'>OK.</span>
  <span m='2672630'>Alright.</span> <span m='2673010'>And</span> <span m='2673570'>so</span>
  <span m='2673720'>that's</span> <span m='2674070'>my</span> <span m='2674570'>f.</span>
  <span m='2676420'>I'll</span> <span m='2676670'>come</span> <span m='2676850'>back</span>
  <span m='2677120'>to</span> <span m='2677240'>that,</span> <span m='2678720'>let</span>
  <span m='2679530'>me</span> <span m='2679690'>stay</span> <span m='2679990'>with</span>
  <span m='2680250'>this.</span> </p><p><span m='2684830'>I'll</span> <span m='2685160'>stay</span>
  <span m='2685390'>with</span> <span m='2685600'>this</span> <span m='2685760'>to</span>
  <span m='2685850'>make</span> <span m='2686090'>the</span> <span m='2686190'>main</span>
  <span m='2686470'>point,</span> <span m='2687530'>and</span> <span m='2687730'>then</span>
  <span m='2688590'>Friday</span> <span m='2689030'>we'll</span> <span m='2689210'>see</span>
  <span m='2689430'>it</span> <span m='2690310'>in</span> <span m='2690530'>a</span>
  <span m='2690570'>neat</span> <span m='2690890'>way</span> <span m='2691230'>for</span>
  <span m='2691490'>the</span> <span m='2691660'>discrete</span> <span m='2692150'>one.</span>
  <span m='2693960'>So</span> <span m='2694150'>I'm</span> <span m='2694320'>coming</span>
  <span m='2694620'>back</span> <span m='2694880'>to</span> <span m='2694960'>this.</span>
  <span m='2695230'>f</span> <span m='2696060'>has</span> <span m='2696300'>its</span>
  <span m='2696470'>Fourier</span> <span m='2696880'>series.</span> <span m='2697560'>g</span>
  <span m='2697940'>has</span> <span m='2698210'>its</span> <span m='2698410'>Fourier</span>
  <span m='2698750'>series.</span> <span m='2699940'>I</span> <span m='2700040'>multiply.</span>
  <span m='2702870'>What</span> <span m='2703140'>happens</span> <span m='2703810'>when</span>
  <span m='2704030'>I</span> <span m='2704130'>multiply</span> <span m='2704830'>this</span>
  <span m='2705420'>times</span> <span m='2705760'>this?</span> <span m='2710080'>I'm</span>
  <span m='2710420'>not</span> <span m='2710640'>going</span> <span m='2710840'>to</span>
  <span m='2710910'>integrate.</span> <span m='2712430'>I</span> <span m='2712540'>mean,</span>
  <span m='2713540'>when</span> <span m='2713730'>I</span> <span m='2713810'>do</span>
  <span m='2714020'>this</span> <span m='2714220'>multiplication,</span> <span m='2714890'>I'm</span>
  <span m='2715160'>going to</span> <span m='2715420'>get</span> <span m='2715660'>a</span>
  <span m='2715800'>mass of</span> <span m='2716440'>terms.</span> <span m='2718890'>A</span>
  <span m='2719080'>real</span> <span m='2719590'>lot</span> <span m='2720000'>of</span>
  <span m='2720140'>terms.</span> <span m='2721230'>And</span> <span m='2721930'>I'm</span>
  <span m='2722190'>not</span> <span m='2722400'>going to</span> <span m='2722640'>integrate</span>
  <span m='2723060'>them</span> <span m='2723210'>away.</span> <span m='2723650'>So</span>
  <span m='2724150'>they're</span> <span m='2724340'>all</span> <span m='2724510'>there.</span>
  <span m='2725850'>So</span> <span m='2726090'>what</span> <span m='2726350'>am</span>
  <span m='2726420'>I</span> <span m='2726580'>asking?</span> <span m='2727160'>I'm</span>
  <span m='2727390'>asking</span> <span m='2727870'>to</span> <span m='2728030'>pick</span>
  <span m='2728450'>out</span> <span m='2729110'>all</span> <span m='2729730'>the</span>
  <span m='2729880'>terms</span> <span m='2730550'>that</span> <span m='2730680'>have</span>
  <span m='2731320'>the</span> <span m='2731480'>same</span> <span m='2734020'>exponential</span>
  <span m='2734740'>with</span> <span m='2734930'>them.</span> <span m='2736050'>Like,</span>
  <span m='2737520'>what's</span> <span m='2737750'>h_0?</span> <span m='2738730'>Yes,</span>
  <span m='2739360'>tell</span> <span m='2739560'>me</span> <span m='2739710'>what</span>
  <span m='2739910'>h_0</span> <span m='2740620'>is?</span> <span m='2742980'>If</span>
  <span m='2743180'>you</span> <span m='2743330'>can</span> <span m='2743490'>pick</span>
  <span m='2743700'>out</span> <span m='2743900'>h_0</span> <span m='2744440'>here,</span>
  <span m='2744980'>you'll</span> <span m='2745200'>get</span> <span m='2745400'>the</span>
  <span m='2745540'>idea</span> <span m='2745860'>of</span> <span m='2745960'>convolution.</span>
  <span m='2750630'>What's</span> <span m='2751190'>the</span> <span m='2751330'>constant</span>
  <span m='2752040'>term</span> <span m='2752380'>if</span> <span m='2752540'>I</span>
  <span m='2752680'>multiply</span> <span m='2753460'>this</span> <span m='2753740'>mess</span>
  <span m='2755100'>times</span> <span m='2755520'>this</span> <span m='2755820'>mess,</span>
  <span m='2756860'>and</span> <span m='2757140'>I</span> <span m='2757290'>look</span>
  <span m='2757710'>for</span> <span m='2758280'>the</span> <span m='2760160'>constant</span>
  <span m='2760710'>term,</span> <span m='2761570'>h_0,</span> <span m='2763800'>where</span>
  <span m='2764420'>do</span> <span m='2764530'>I</span> <span m='2764640'>get</span>
  <span m='2764850'>the</span> <span m='2764910'>constant</span> <span m='2765420'>terms</span>
  <span m='2765770'>when</span> <span m='2765950'>I</span> <span m='2766010'>multiply</span>
  <span m='2766430'>that</span> <span m='2766690'>by</span> <span m='2766830'>that?</span>
  <span m='2767080'>Just</span> <span m='2767560'>think</span> <span m='2767740'>about</span>
  <span m='2768020'>that.</span> <span m='2768490'>Where</span> <span m='2768860'>do</span>
  <span m='2769000'>I</span> <span m='2769130'>get</span> <span m='2769400'>a</span>
  <span m='2769480'>constant,</span> <span m='2770230'>without</span> <span m='2770710'>any</span>
  <span m='2770870'>k,</span> <span m='2771180'>without</span> <span m='2771510'>an</span>
  <span m='2772830'>e^(ikx)?</span> <span m='2773960'>If</span> <span m='2774140'>I</span>
  <span m='2774220'>multiply</span> <span m='2774700'>that</span> <span m='2775040'>by</span>
  <span m='2775240'>that.</span> <span m='2776650'>Well</span> <span m='2776940'>tell</span>
  <span m='2777120'>me</span> <span m='2777270'>one</span> <span m='2777540'>place</span>
  <span m='2777880'>I</span> <span m='2777970'>get</span> <span m='2778440'>something.</span>
  <span m='2779580'>c_0</span> <span m='2780260'>times?</span> <span m='2781390'>d_0.</span>
  <span m='2781970'>Good.</span> <span m='2785650'>Is</span> <span m='2785860'>that</span>
  <span m='2786090'>the</span> <span m='2786210'>end</span> <span m='2786420'>of</span>
  <span m='2786490'>the</span> <span m='2786620'>story?</span> <span m='2788030'>No.</span>
  <span m='2789130'>If</span> <span m='2789320'>you</span> <span m='2789500'>thought</span>
  <span m='2790550'>that</span> <span m='2790770'>multiplying</span> <span m='2791610'>the</span>
  <span m='2791730'>functions,</span> <span m='2792570'>I</span> <span m='2792690'>just</span>
  <span m='2792960'>multiplied</span> <span m='2793410'>the</span> <span m='2793690'>Fourier</span>
  <span m='2793770'>coefficients,</span> <span m='2793950'>the</span> <span m='2794600'>first</span>
  <span m='2794970'>point</span> <span m='2795380'>is</span> <span m='2795660'>no.</span>
  <span m='2796820'>There's</span> <span m='2797320'>more</span> <span m='2797580'>stuff.</span>
  <span m='2798420'>Where</span> <span m='2798790'>else</span> <span m='2799180'>do</span>
  <span m='2799350'>I</span> <span m='2799540'>get</span> <span m='2800630'>a</span>
  <span m='2800770'>constant</span> <span m='2801360'>out</span> <span m='2801520'>of</span>
  <span m='2801640'>this?</span> <span m='2801940'>Just</span> <span m='2802710'>look</span>
  <span m='2802950'>at</span> <span m='2803160'>it,</span> <span m='2803290'>do</span>
  <span m='2803480'>that</span> <span m='2803710'>multiplication</span> <span m='2804850'>and</span>
  <span m='2804990'>ask</span> <span m='2805280'>yourself</span> <span m='2805910'>where's</span>
  <span m='2806370'>the</span> <span m='2806490'>constant.</span> <span m='2808100'>Another</span>
  <span m='2808630'>one,</span> <span m='2808790'>yep.</span> <span m='2809090'>You
  were going to</span> <span m='2809390'>say</span> <span m='2809560'>it</span> <span
  m='2809730'>is?</span> <span m='2811370'>c_1</span> <span m='2812090'>times</span>
  <span m='2813830'>d_(-1).</span> <span m='2814890'>Right.</span> <span m='2815580'>Right.</span>
  <span m='2816820'>c_1</span> <span m='2817560'>times</span> <span m='2818180'>d_(-1).</span>
  <span m='2819750'>And</span> <span m='2820460'>tell</span> <span m='2820700'>me</span>
  <span m='2820820'>all</span> <span m='2821050'>of them,</span> <span m='2821360'>now.</span>
  <span m='2822690'>c_2</span> <span m='2823410'>times</span> <span m='2824990'>d_(-2).</span>
  <span m='2825890'>And</span> <span m='2826690'>what</span> <span m='2826900'>about</span>
  <span m='2827260'>c_(-1)?</span> <span m='2829180'>There's</span> <span m='2829510'>a</span>
  <span m='2829620'>c_(-1).</span> <span m='2832740'>It</span> <span m='2832980'>multiplies</span>
  <span m='2833620'>d_1.</span> <span m='2836150'>And</span> <span m='2836570'>onwards.</span>
  <span m='2839500'>So</span> <span m='2841600'>the</span> <span m='2841740'>coefficient</span>
  <span m='2844290'>comes</span> <span m='2844770'>from,</span> <span m='2845910'>now</span>
  <span m='2846100'>how</span> <span m='2846330'>could</span> <span m='2846540'>you</span>
  <span m='2846660'>describe</span> <span m='2847240'>that?</span> <span m='2849650'>I</span>
  <span m='2849850'>guess</span> <span m='2850130'>I'll</span> <span m='2850350'>describe</span>
  <span m='2850920'>it</span> <span m='2851040'>as,</span> <span m='2851270'>I'll</span>
  <span m='2851620'>need</span> <span m='2851980'>a</span> <span m='2852230'>sum</span>
  <span m='2854310'>to</span> <span m='2854430'>multiply.</span> <span m='2855580'>This</span>
  <span m='2855820'>will</span> <span m='2855910'>be</span> <span m='2856030'>the</span>
  <span m='2856340'>sum</span> <span m='2856870'>of</span> <span m='2857400'>c_k</span>
  <span m='2858490'>times</span> <span m='2858980'>d</span> <span m='2859630'>what?</span>
  <span m='2862490'>Minus</span> <span m='2863040'>k,</span> <span m='2863520'>right?</span>
  <span m='2865600'>That's</span> <span m='2865870'>what</span> <span m='2866060'>you</span>
  <span m='2866200'>told</span> <span m='2866510'>me,</span> <span m='2867890'>the
  piece</span> <span m='2868560'>at</span> <span m='2868740'>the</span> <span m='2868860'>start,</span>
  <span m='2869370'>and that's</span> <span m='2869980'>the</span> <span m='2870100'>pattern</span>
  <span m='2870580'>that</span> <span m='2870730'>keeps</span> <span m='2871000'>going.</span>
  <span m='2872170'>OK,</span> <span m='2872570'>that's</span> <span m='2872890'>h_0,</span>
  <span m='2875130'>the</span> <span m='2875280'>sum</span> <span m='2875640'>of</span>
  <span m='2875750'>c_k</span> <span m='2876330'>times</span> <span m='2876690'>d_(-k).</span>
  <span m='2878810'>Now,</span> <span m='2879600'>we</span> <span m='2879770'>have</span>
  <span m='2880110'>just</span> <span m='2880560'>time</span> <span m='2881660'>to</span>
  <span m='2881840'>do</span> <span m='2883320'>the</span> <span m='2883450'>next</span>
  <span m='2883890'>one.</span> <span m='2885580'>We've</span> <span m='2885780'>got</span>
  <span m='2885960'>time</span> <span m='2886280'>but</span> <span m='2886440'>not</span>
  <span m='2886670'>space,</span> <span m='2887130'>where</span> <span m='2887310'>the</span>
  <span m='2887410'>heck</span> <span m='2887570'>am</span> <span m='2887670'>I</span>
  <span m='2887740'>going to</span> <span m='2888040'>put it?</span> <span m='2889640'>I</span>
  <span m='2889800'>want to</span> <span m='2890150'>do</span> <span m='2890480'>h_k,</span>
  <span m='2894050'>I</span> <span m='2894200'>guess.</span> <span m='2894550'>Or</span>
  <span m='2894910'>I</span> <span m='2894940'>better</span> <span m='2895430'>use</span>
  <span m='2895680'>a</span> <span m='2895780'>different</span> <span m='2896110'>letter</span>
  <span m='2896430'>h_l,</span> <span m='2898170'>let</span> <span m='2898320'>me</span>
  <span m='2898440'>use</span> <span m='2898660'>the</span> <span m='2898760'>letter</span>
  <span m='2899030'>h_l,</span> <span m='2899540'>and</span> <span m='2899750'>God</span>
  <span m='2900850'>there's</span> <span m='2901610'>no</span> <span m='2902420'>space.</span>
  <span m='2902890'>Alright,</span> <span m='2903530'>so</span> <span m='2904030'>can</span>
  <span m='2904340'>I--</span> <span m='2906010'>Yes.</span> <span m='2909430'>h_l.</span>
  <span m='2911120'>OK.</span> <span m='2912300'>So</span> <span m='2912500'>this</span>
  <span m='2912760'>was</span> <span m='2913050'>h_0,</span> <span m='2914750'>let</span>
  <span m='2914890'>me</span> <span m='2915010'>keep</span> <span m='2915310'>things</span>
  <span m='2915560'>sort</span> <span m='2915880'>of</span> <span m='2916020'>looking</span>
  <span m='2916430'>right</span> <span m='2916810'>for</span> <span m='2916970'>the</span>
  <span m='2917040'>moment.</span> <span m='2917470'>OK,</span> <span m='2918040'>now</span>
  <span m='2918270'>you're</span> <span m='2918410'>going to</span> <span m='2918630'>fix</span>
  <span m='2918960'>h_l.</span> <span m='2919640'>So</span> <span m='2920390'>what</span>
  <span m='2920700'>does</span> <span m='2920910'>c_0</span> <span m='2921650'>multiply,</span>
  <span m='2922810'>if</span> <span m='2923020'>I'm</span> <span m='2923220'>looking</span>
  <span m='2924000'>for</span> <span m='2924160'>h_l,</span> <span m='2924770'>I'm</span>
  <span m='2924960'>looking</span> <span m='2925290'>for</span> <span m='2925450'>the</span>
  <span m='2925590'>coefficient</span> <span m='2926260'>of</span> <span m='2926880'>e^(ilx).</span>
  <span m='2927920'>So</span> <span m='2928190'>ask</span> <span m='2928490'>yourself</span>
  <span m='2929130'>how</span> <span m='2929360'>do</span> <span m='2929490'>I</span>
  <span m='2929590'>get</span> <span m='2929870'>e^(ilx)</span> <span m='2931070'>when</span>
  <span m='2931290'>that</span> <span m='2931540'>multiplies</span> <span m='2932080'>that?</span>
  <span m='2934110'>When</span> <span m='2934330'>that</span> <span m='2934600'>multiplies</span>
  <span m='2935110'>that,</span> <span m='2935490'>and</span> <span m='2935650'>I'm</span>
  <span m='2935790'>looking</span> <span m='2936170'>for</span> <span m='2936280'>an</span>
  <span m='2936400'>e^(ilx),</span> <span m='2937820'>I</span> <span m='2937930'>get</span>
  <span m='2938230'>one</span> <span m='2938630'>when</span> <span m='2938940'>c_0</span>
  <span m='2939590'>all</span> <span m='2939790'>multiplies</span> <span m='2940560'>what?</span>
  <span m='2942430'>This</span> <span m='2942660'>is</span> <span m='2942810'>it.</span>
  <span m='2943930'>d_l,</span> <span m='2944590'>right.</span> <span m='2945690'>And</span>
  <span m='2945910'>what</span> <span m='2946170'>about</span> <span m='2946610'>for</span>
  <span m='2946840'>c_1?</span> <span m='2949860'>Think</span> <span m='2950290'>of
  here,</span> <span m='2950680'>I</span> <span m='2950820'>have</span> <span m='2950990'>a</span>
  <span m='2951850'>c_1*e^(i1x).</span> <span m='2954190'>What</span> <span m='2954550'>does</span>
  <span m='2954680'>it</span> <span m='2954850'>multiply</span> <span m='2955360'>down</span>
  <span m='2955710'>here</span> <span m='2956520'>to</span> <span m='2956690'>get</span>
  <span m='2957010'>the</span> <span m='2957140'>exponential</span> <span m='2958120'>to</span>
  <span m='2958290'>be</span> <span m='2959160'>l?</span> <span m='2960210'>ilx?</span>
  <span m='2962340'>It</span> <span m='2963300'>doesn't</span> <span m='2963710'>multiply</span>
  <span m='2964910'>d_(-1).</span> <span m='2965860'>It</span> <span m='2965960'>multiplies,</span>
  <span m='2966490'>c_1</span> <span m='2967190'>multiplies?</span> <span m='2968580'>d_(l-1).</span>
  <span m='2971530'>Good,</span> <span m='2971970'>good.</span> <span m='2972450'>l-1,</span>
  <span m='2973420'>right.</span> <span m='2974730'>l-1,</span> <span m='2975960'>and</span>
  <span m='2976170'>what</span> <span m='2976320'>are</span> <span m='2976390'>you</span>
  <span m='2976510'>noticing</span> <span m='2977140'>here?</span> <span m='2978470'>c</span>
  <span m='2978770'>minus,</span> <span m='2979000'>I'll</span> <span m='2979370'>have
  to</span> <span m='2979490'>fill</span> <span m='2979800'>that</span> <span m='2980030'>in.</span>
  <span m='2980560'>But</span> <span m='2981410'>you're</span> <span m='2981680'>seeing</span>
  <span m='2982060'>the</span> <span m='2982130'>pattern</span> <span m='2982590'>here?</span>
  <span m='2985620'>And</span> <span m='2985780'>what</span> <span m='2985960'>was</span>
  <span m='2986130'>the</span> <span m='2986220'>pattern</span> <span m='2986630'>here?</span>
  <span m='2987380'>Those</span> <span m='2987920'>numbers</span> <span m='2988480'>added</span>
  <span m='2989090'>to</span> <span m='2990880'>this</span> <span m='2991200'>number.</span>
  <span m='2991870'>And</span> <span m='2992110'>now</span> <span m='2992590'>these</span>
  <span m='2993040'>numbers</span> <span m='2993580'>add</span> <span m='2993780'>to</span>
  <span m='2993900'>l.</span> <span m='2994490'>Those</span> <span m='2994870'>numbers</span>
  <span m='2995220'>add</span> <span m='2995480'>to</span> <span m='2995590'>l,</span>
  <span m='2995960'>whatever</span> <span m='2996440'>it</span> <span m='2996530'>is,</span>
  <span m='3000040'>the</span> <span m='3000110'>two</span> <span m='3000740'>indices</span>
  <span m='3001080'>have</span> <span m='3001200'>to</span> <span m='3001720'>add</span>
  <span m='3001990'>to</span> <span m='3002130'>l,</span> <span m='3003020'>so</span>
  <span m='3003260'>that</span> <span m='3003730'>when</span> <span m='3003960'>I</span>
  <span m='3004150'>multiply</span> <span m='3004500'>the</span> <span m='3004640'>exponential</span>
  <span m='3005640'>they'll</span> <span m='3005860'>add</span> <span m='3006140'>to</span>
  <span m='3007530'>e^(ilx).</span> <span m='3008000'>They'll</span> <span m='3008630'>multiply</span>
  <span m='3008850'>to</span> <span m='3008980'>e^(ilx).</span> <span m='3011480'>So</span>
  <span m='3011660'>what</span> <span m='3011900'>goes</span> <span m='3012130'>there?</span>
  <span m='3014360'>It's</span> <span m='3014540'>probably</span> <span m='3015050'>l+1,</span>
  <span m='3016090'>right?</span> <span m='3016750'>So</span> <span m='3016960'>that</span>
  <span m='3017090'>l+1</span> <span m='3019220'>combined</span> <span m='3019670'>with</span>
  <span m='3019850'>minus</span> <span m='3020230'>one</span> <span m='3020470'>gives</span>
  <span m='3020700'>me</span> <span m='3020870'>the</span> <span m='3021030'>l.</span>
  <span m='3022300'>If</span> <span m='3022540'>you</span> <span m='3022770'>tell</span>
  <span m='3023020'>me</span> <span m='3023160'>what</span> <span m='3023410'>goes</span>
  <span m='3023690'>there,</span> <span m='3024130'>I'm a</span> <span m='3024610'>happy</span>
  <span m='3025340'>person.</span> <span m='3026560'>Let's</span> <span m='3026850'>make</span>
  <span m='3027090'>it</span> <span m='3027200'>h_l.</span> <span m='3027750'>We're</span>
  <span m='3027910'>ready</span> <span m='3028230'>for</span> <span m='3028410'>the</span>
  <span m='3028530'>final</span> <span m='3029660'>formula</span> <span m='3030330'>for</span>
  <span m='3030540'>convolutions.</span> <span m='3033300'>Big star.</span> <span
  m='3039020'>To</span> <span m='3039170'>find</span> <span m='3039910'>h_l,</span>
  <span m='3040790'>the</span> <span m='3040930'>coefficient</span> <span m='3041620'>of</span>
  <span m='3041760'>e^(ilx),</span> <span m='3044200'>when</span> <span m='3044420'>you</span>
  <span m='3044510'>multiply</span> <span m='3044950'>that</span> <span m='3045260'>by</span>
  <span m='3045410'>that,</span> <span m='3046530'>you</span> <span m='3046750'>look</span>
  <span m='3047020'>at</span> <span m='3047340'>c_k,</span> <span m='3048390'>and</span>
  <span m='3049630'>which</span> <span m='3050110'>d</span> <span m='3050920'>is</span>
  <span m='3052280'>going</span> <span m='3052670'>to</span> <span m='3052730'>show</span>
  <span m='3053000'>up</span> <span m='3053260'>in</span> <span m='3053450'>the</span>
  <span m='3053780'>e^(ilx)</span> <span m='3054870'>term?</span> <span m='3056980'>l-k,</span>
  <span m='3058110'>is that</span> <span m='3058200'>what</span> <span m='3058350'>you</span>
  <span m='3058460'>said?</span> <span m='3059700'>I</span> <span m='3059830'>hope,</span>
  <span m='3060720'>yeah.</span> <span m='3061860'>l-k.</span> <span m='3062870'>Right,</span>
  <span m='3063460'>that's</span> <span m='3063750'>it.</span> <span m='3064590'>That's</span>
  <span m='3064920'>it.</span> <span m='3065250'>So</span> <span m='3065540'>we've</span>
  <span m='3065800'>got</span> <span m='3066830'>a</span> <span m='3066990'>lot</span>
  <span m='3067530'>of</span> <span m='3067690'>computation</span> <span m='3068630'>here.</span>
  <span m='3070030'>But</span> <span m='3070270'>we've</span> <span m='3070460'>got</span>
  <span m='3070730'>the</span> <span m='3070850'>idea</span> <span m='3071310'>of</span>
  <span m='3071440'>what,</span> <span m='3071860'>we've</span> <span m='3072130'>got</span>
  <span m='3072320'>a</span> <span m='3072390'>formula.</span> <span m='3077300'>And</span>
  <span m='3078080'>most</span> <span m='3078420'>of</span> <span m='3078540'>all</span>
  <span m='3078750'>we</span> <span m='3078910'>have</span> <span m='3079200'>the</span>
  <span m='3079310'>magic</span> <span m='3079830'>rule.</span> <span m='3080740'>In</span>
  <span m='3081050'>convolutions,</span> <span m='3083960'>convolutions</span> <span
  m='3084590'>are,</span> <span m='3085480'>things</span> <span m='3085850'>multiply</span>
  <span m='3087260'>but</span> <span m='3087500'>indices</span> <span m='3088220'>add.</span>
  <span m='3089930'>Things</span> <span m='3090250'>multiply,</span> <span m='3091000'>numbers</span>
  <span m='3091420'>multiply,</span> <span m='3092300'>while</span> <span m='3093020'>their</span>
  <span m='3093180'>indices</span> <span m='3093350'>add.</span> <span m='3094160'>That's</span>
  <span m='3094460'>the</span> <span m='3094600'>key</span> <span m='3094830'>idea</span>
  <span m='3095160'>of</span> <span m='3095300'>convolution</span> <span m='3095990'>that</span>
  <span m='3096120'>we'll</span> <span m='3096340'>see</span> <span m='3097240'>clearly</span>
  <span m='3097840'>and</span> <span m='3098330'>completely</span> <span m='3099030'>on</span>
  <span m='3099400'>Friday.</span> <span m='3100410'>OK.</span> </p>
type: course
uid: 59f0e4997ec84a7855a682c6c5b58b16

---
None