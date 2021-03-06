---
about_this_resource_text: <p><strong>Instructor:</strong> Prof. Gilbert Strang</p>
course_id: 18-085-computational-science-and-engineering-i-fall-2008
embedded_media:
- id: 25.jpg
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-25-fast-poisson-solver-part-1/25.jpg
  title: Lecture 25
  type: null
  uid: 73c6230bdc11bb162dc04e51033513b5
- id: Video-YouTube-Stream
  media_location: E1o1h-_4Bn4
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: Video-YouTube-Stream
  type: Video
  uid: a374ea15acd17a1aa84a3c3560440f42
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/E1o1h-_4Bn4/default.jpg
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 9216efb4b0335cbbcb62492b6f691f36
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869177
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: Video-iTunes U-MP4
  type: Video
  uid: bcd6106d07cc19675af7956a806ed76d
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.085F08/ocw-18.085-f08-lec25_300k.mp4
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: Video-Internet Archive-MP4
  type: Video
  uid: ad87e91fe74fe094ff4ac789d7954c9c
- id: Thumbnail-OCW-JPG
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 1d6e60069fd109009e497c18c237a12f
- id: 3Play-3PlayYouTubeid-MP4
  media_location: E1o1h-_4Bn4
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 8ffb6a45803cf836bdd927552414bcdf
- id: E1o1h-_4Bn4.srt
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-25-fast-poisson-solver-part-1/E1o1h-_4Bn4.srt
  title: 3play caption file
  type: null
  uid: 962b2c04a7df383c6646b47a0c526637
- id: E1o1h-_4Bn4.pdf
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-25-fast-poisson-solver-part-1/E1o1h-_4Bn4.pdf
  title: 3play pdf file
  type: null
  uid: 2e143346162a7ed1a1c4f3da1c498ed4
- id: Caption-3Play YouTube id-SRT
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 023d1fd06dc1d57255ea47609b2d2715
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d1b9a4c5d88a39b1dae061c634e72b0b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: b5be981639812b6693082cd59ed4f71e
inline_embed_id: 72334266lecture25:fastpoissonsolver(part1)59387183
layout: video
order_index: null
parent_uid: 4e3ac3b31de7414e05181196c7255bbd
related_resources_text: ''
short_url: lecture-25-fast-poisson-solver-part-1
technical_location: https://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-25-fast-poisson-solver-part-1
template_type: Tabbed
title: 'Lecture 25: Fast Poisson Solver (part 1)'
transcript: '<p><span m=''340''>The following content</span> <span m=''1920''>is provided</span>
  <span m=''2330''>under a Creative Commons license.</span> <span m=''3610''>Your</span>
  <span m=''3810''>support</span> <span m=''5020''>will help MIT</span> <span m=''5220''>OpenCourseWare</span>
  <span m=''5460''>continue</span> <span m=''5770''>to</span> <span m=''6740''>offer</span>
  <span m=''6880''>high-quality</span> <span m=''7630''>educational</span> <span m=''8260''>resources</span>
  <span m=''8840''>for</span> <span m=''8970''>free.</span> <span m=''10650''>To make</span>
  <span m=''11070''>a</span> <span m=''11240''>donation,</span> <span m=''11410''>or</span>
  <span m=''11520''>to</span> <span m=''11670''>view</span> <span m=''11880''>additional</span>
  <span m=''11960''>materials</span> <span m=''12530''>from</span> <span m=''13250''>hundreds
  of MIT</span> <span m=''13580''>courses,</span> <span m=''15350''>visit</span> <span
  m=''15600''>MIT</span> <span m=''15870''>OpenCourseWare</span> <span m=''16170''>at</span>
  <span m=''18050''>ocw.mit.edu.</span> </p><p><span m=''20320''>PROFESSOR STRANG:
  Well,</span> <span m=''20650''>OK.</span> <span m=''21170''>So</span> <span m=''22500''>I</span>
  <span m=''22890''>thought</span> <span m=''23170''>I</span> <span m=''23290''>would,</span>
  <span m=''23600''>as</span> <span m=''24110''>last</span> <span m=''24480''>time,</span>
  <span m=''25920''>before</span> <span m=''26270''>Quiz</span> <span m=''26530''>1</span>
  <span m=''26980''>and now</span> <span m=''27250''>before</span> <span m=''27690''>Quiz</span>
  <span m=''28050''>2,</span> <span m=''28350''>I</span> <span m=''28510''>thought</span>
  <span m=''28760''>I</span> <span m=''28830''>would</span> <span m=''29000''>just</span>
  <span m=''29250''>tell</span> <span m=''29460''>you</span> <span m=''29590''>what</span>
  <span m=''29920''>the</span> <span m=''30060''>topics</span> <span m=''30580''>of</span>
  <span m=''30710''>the</span> <span m=''30850''>four</span> <span m=''31080''>problems</span>
  <span m=''31610''>are.</span> <span m=''33850''>Remember</span> <span m=''34340''>that</span>
  <span m=''34580''>trusses</span> <span m=''34960''>are</span> <span m=''36760''>still</span>
  <span m=''37090''>to</span> <span m=''37240''>be</span> <span m=''38220''>reviewed,</span>
  <span m=''39350''>and</span> <span m=''39920''>of</span> <span m=''40050''>course</span>
  <span m=''40450''>the</span> <span m=''40590''>fun</span> <span m=''40990''>was</span>
  <span m=''43720''>to</span> <span m=''43900''>find</span> <span m=''44580''>mechanisms,</span>
  <span m=''45360''>to</span> <span m=''45470''>find</span> <span m=''45830''>solutions</span>
  <span m=''46560''>to</span> <span m=''46690''>Au=0,</span> <span m=''48100''>in</span>
  <span m=''48320''>the</span> <span m=''48720''>case</span> <span m=''49090''>when</span>
  <span m=''49300''>the</span> <span m=''49390''>truss</span> <span m=''49820''>was</span>
  <span m=''50010''>unstable.</span> <span m=''50770''>So</span> <span m=''50970''>you</span>
  <span m=''51180''>can</span> <span m=''51420''>guess</span> <span m=''51720''>that</span>
  <span m=''51890''>I''ll</span> <span m=''52030''>probably</span> <span m=''53080''>pick</span>
  <span m=''53640''>an</span> <span m=''54150''>unstable</span> <span m=''54860''>truss.</span>
  <span m=''55670''>And</span> <span m=''57140''>ask</span> <span m=''57570''>for</span>
  <span m=''58400''>mechanisms.</span> <span m=''59800''>Then</span> <span m=''60190''>maybe</span>
  <span m=''60550''>the</span> <span m=''61870''>key</span> <span m=''62230''>problem</span>
  <span m=''62870''>for</span> <span m=''63120''>this</span> <span m=''64870''>third</span>
  <span m=''65350''>of the</span> <span m=''65450''>course</span> <span m=''66070''>is</span>
  <span m=''68000''>finite</span> <span m=''68410''>elements.</span> <span m=''69550''>That</span>
  <span m=''69800''>idea,</span> <span m=''70380''>and</span> <span m=''70970''>finite</span>
  <span m=''71430''>elements</span> <span m=''71890''>we''ve</span> <span m=''72030''>really</span>
  <span m=''72370''>only</span> <span m=''72670''>done</span> <span m=''72940''>in</span>
  <span m=''73130''>one</span> <span m=''73350''>dimension, so--</span> <span m=''75060''>And</span>
  <span m=''75290''>particularly</span> <span m=''76340''>linear</span> <span m=''77170''>hat</span>
  <span m=''77740''>function</span> <span m=''78730''>elements.</span> <span m=''80780''>So</span>
  <span m=''81810''>you</span> <span m=''81970''>see</span> <span m=''82190''>what''s</span>
  <span m=''82460''>not</span> <span m=''82790''>included</span> <span m=''83460''>there</span>
  <span m=''83870''>is</span> <span m=''84160''>like</span> <span m=''84550''>cubics.</span>
  <span m=''85640''>I</span> <span m=''85820''>mean,</span> <span m=''86010''>those</span>
  <span m=''86270''>are</span> <span m=''86380''>really</span> <span m=''86750''>great</span>
  <span m=''87340''>finite</span> <span m=''87810''>elements,</span> <span m=''88300''>but</span>
  <span m=''89330''>maybe</span> <span m=''89630''>not</span> <span m=''89890''>so</span>
  <span m=''90100''>great</span> <span m=''90480''>for</span> <span m=''90720''>an</span>
  <span m=''90900''>exam.</span> <span m=''92090''>So</span> <span m=''93030''>1-D</span>
  <span m=''93700''>is</span> <span m=''93870''>enough;</span> <span m=''94580''>linear</span>
  <span m=''95040''>elements</span> <span m=''95480''>are</span> <span m=''95590''>enough</span>
  <span m=''96080''>to</span> <span m=''96230''>do</span> <span m=''96360''>on</span>
  <span m=''96590''>an</span> <span m=''96710''>exam.</span> <span m=''97500''>And</span>
  <span m=''97730''>then</span> <span m=''98070''>questions</span> <span m=''98620''>three</span>
  <span m=''98900''>and</span> <span m=''99110''>four,</span> <span m=''100540''>so</span>
  <span m=''102050''>this</span> <span m=''102510''>one</span> <span m=''102700''>will</span>
  <span m=''102890''>be</span> <span m=''103070''>weighted</span> <span m=''103570''>more</span>
  <span m=''103780''>heavily.</span> <span m=''104600''>Then</span> <span m=''104850''>questions</span>
  <span m=''105400''>three</span> <span m=''105640''>and</span> <span m=''105820''>four</span>
  <span m=''106160''>are</span> <span m=''106340''>the</span> <span m=''106480''>topics</span>
  <span m=''107030''>that</span> <span m=''107190''>we''ve</span> <span m=''107410''>been</span>
  <span m=''107650''>doing</span> <span m=''108240''>the</span> <span m=''108340''>last</span>
  <span m=''109280''>week,</span> <span m=''109800''>two</span> <span m=''109960''>weeks.</span>
  <span m=''111640''>And</span> <span m=''111840''>I</span> <span m=''111930''>realize</span>
  <span m=''112500''>we</span> <span m=''112680''>haven''t</span> <span m=''113650''>had</span>
  <span m=''114480''>full</span> <span m=''115020''>time</span> <span m=''115490''>to</span>
  <span m=''115650''>digest</span> <span m=''116350''>them,</span> <span m=''116590''>to</span>
  <span m=''116700''>work</span> <span m=''117030''>a</span> <span m=''117080''>whole</span>
  <span m=''117250''>lot</span> <span m=''117450''>of</span> <span m=''117540''>exercises.</span>
  <span m=''118960''>So</span> <span m=''120690''>those</span> <span m=''120850''>will</span>
  <span m=''121070''>be,</span> <span m=''122820''>right</span> <span m=''123040''>now</span>
  <span m=''123200''>they''re</span> <span m=''123410''>too</span> <span m=''123630''>simple,</span>
  <span m=''124130''>my</span> <span m=''124280''>questions</span> <span m=''124900''>on</span>
  <span m=''125070''>those</span> <span m=''125450''>topics.</span> <span m=''126130''>Three</span>
  <span m=''126310''>and</span> <span m=''126450''>four,</span> <span m=''126680''>I''ll</span>
  <span m=''126810''>try</span> <span m=''127030''>to</span> <span m=''127240''>make</span>
  <span m=''127430''>them</span> <span m=''127540''>a</span> <span m=''127600''>little</span>
  <span m=''127850''>harder</span> <span m=''128250''>for</span> <span m=''128490''>you.</span>
  <span m=''128990''>But</span> <span m=''129580''>I</span> <span m=''129710''>might</span>
  <span m=''130020''>not</span> <span m=''130330''>succeed.</span> <span m=''131220''>So,</span>
  <span m=''131730''>anyway.</span> <span m=''133140''>There</span> <span m=''133440''>we</span>
  <span m=''133580''>go.</span> <span m=''134130''>So</span> <span m=''135410''>I</span>
  <span m=''135600''>just</span> <span m=''135880''>felt</span> <span m=''137510''>we</span>
  <span m=''137760''>can''t</span> <span m=''138360''>talk</span> <span m=''138710''>about</span>
  <span m=''139520''>a</span> <span m=''139680''>course</span> <span m=''140050''>in</span>
  <span m=''140190''>applied</span> <span m=''140660''>math</span> <span m=''141090''>without</span>
  <span m=''141740''>dealing</span> <span m=''142170''>with</span> <span m=''142350''>these</span>
  <span m=''143390''>topics</span> <span m=''143930''>in vector</span> <span m=''144520''>calculus</span>
  <span m=''145300''>that</span> <span m=''145530''>lead</span> <span m=''145930''>to</span>
  <span m=''146310''>Laplace''s</span> <span m=''147100''>equation.</span> <span m=''148100''>But</span>
  <span m=''148620''>my</span> <span m=''148770''>heart</span> <span m=''149180''>is</span>
  <span m=''149370''>really</span> <span m=''149760''>in</span> <span m=''150490''>solving</span>
  <span m=''151520''>Laplace''s</span> <span m=''152210''>equation</span> <span m=''152770''>or</span>
  <span m=''152880''>Poisson''s</span> <span m=''153500''>equation</span> <span m=''154150''>by</span>
  <span m=''154820''>finite</span> <span m=''155190''>differences.</span> <span m=''155970''>That''ll</span>
  <span m=''156220''>be</span> <span m=''156430''>today,</span> <span m=''157330''>or</span>
  <span m=''157740''>by</span> <span m=''158390''>finite</span> <span m=''158800''>elements,</span>
  <span m=''159310''>that''ll</span> <span m=''159580''>be</span> <span m=''161100''>Wednesday</span>
  <span m=''161690''>and</span> <span m=''161910''>probably</span> <span m=''162330''>Friday.</span>
  <span m=''163370''>So</span> <span m=''163590''>this</span> <span m=''163810''>is</span>
  <span m=''164490''>like</span> <span m=''165920''>the</span> <span m=''166070''>core</span>
  <span m=''166570''>of</span> <span m=''166720''>the</span> <span m=''167980''>computational</span>
  <span m=''168880''>side,</span> <span m=''169370''>but</span> <span m=''169530''>we</span>
  <span m=''169710''>had</span> <span m=''169960''>to</span> <span m=''170090''>do</span>
  <span m=''170290''>this</span> <span m=''171460''>preparation.</span> <span m=''172390''>And</span>
  <span m=''172680''>then</span> <span m=''173010''>you</span> <span m=''173200''>know</span>
  <span m=''173530''>that</span> <span m=''174180''>Peter</span> <span m=''176270''>kindly</span>
  <span m=''176720''>changed</span> <span m=''177280''>his</span> <span m=''178340''>weekly</span>
  <span m=''178880''>review</span> <span m=''179370''>session</span> <span m=''179970''>to</span>
  <span m=''180150''>Tuesday,</span> <span m=''181400''>I</span> <span m=''181540''>think</span>
  <span m=''181820''>it''s</span> <span m=''182020''>Tuesday</span> <span m=''182540''>at</span>
  <span m=''182720''>noon;</span> <span m=''183080''>you</span> <span m=''183210''>could</span>
  <span m=''183390''>look</span> <span m=''183610''>on</span> <span m=''183800''>the</span>
  <span m=''183900''>website.</span> <span m=''184850''>So</span> <span m=''185020''>Peter</span>
  <span m=''187420''>will</span> <span m=''187600''>be</span> <span m=''187770''>a</span>
  <span m=''187820''>Tuesday</span> <span m=''188390''>review</span> <span m=''189610''>and</span>
  <span m=''190470''>then</span> <span m=''191100''>regular,</span> <span m=''192110''>that''s</span>
  <span m=''192670''>me,</span> <span m=''193510''>on</span> <span m=''194220''>Wednesday.</span>
  <span m=''196910''>And then the</span> <span m=''197320''>exam,</span> <span m=''197730''>I</span>
  <span m=''197790''>think,</span> <span m=''198090''>is</span> <span m=''198230''>Wednesday</span>
  <span m=''198750''>evening.</span> <span m=''201430''>I</span> <span m=''201600''>think,</span>
  <span m=''202030''>yeah.</span> <span m=''202420''>Let</span> <span m=''202600''>me</span>
  <span m=''202700''>just</span> <span m=''203050''>do a</span> <span m=''203870''>review.</span>
  </p><p><span m=''204800''>Oh,</span> <span m=''205230''>Peter</span> <span m=''205550''>sent</span>
  <span m=''205830''>me</span> <span m=''205950''>a</span> <span m=''206020''>note</span>
  <span m=''206360''>about</span> <span m=''206850''>a</span> <span m=''207010''>question</span>
  <span m=''207650''>on</span> <span m=''207840''>an</span> <span m=''207970''>old</span>
  <span m=''208310''>exam.</span> <span m=''209840''>I</span> <span m=''210020''>think
  it</span> <span m=''210080''>was</span> <span m=''210240''>2005,</span> <span m=''212520''>question</span>
  <span m=''213320''>three.</span> <span m=''214680''>I think</span> <span m=''214950''>it</span>
  <span m=''215060''>was</span> <span m=''216940''>2005</span> <span m=''218840''>question</span>
  <span m=''219720''>three.</span> <span m=''222170''>Peter</span> <span m=''222460''>said</span>
  <span m=''222880''>he didn''t</span> <span m=''223560''>understand,</span> <span
  m=''224460''>at</span> <span m=''224680''>all,</span> <span m=''225140''>the</span>
  <span m=''225260''>solution</span> <span m=''225870''>to</span> <span m=''226020''>3c.</span>
  <span m=''227670''>Nor</span> <span m=''227980''>do</span> <span m=''228040''>I.</span>
  <span m=''229290''>I</span> <span m=''229560''>think</span> <span m=''229870''>somehow,</span>
  <span m=''232380''>I think</span> <span m=''232860''>there</span> <span m=''232960''>was</span>
  <span m=''233110''>a</span> <span m=''233200''>little</span> <span m=''233490''>confusion</span>
  <span m=''234430''>in</span> <span m=''234540''>that,</span> <span m=''235110''>and</span>
  <span m=''235440''>the</span> <span m=''235710''>answer</span> <span m=''236150''>in</span>
  <span m=''236400''>there</span> <span m=''236720''>is</span> <span m=''236860''>the</span>
  <span m=''237000''>answer</span> <span m=''237340''>to</span> <span m=''237470''>a</span>
  <span m=''237550''>different</span> <span m=''237950''>question.</span> <span m=''238970''>Forget</span>
  <span m=''239390''>it.</span> <span m=''241890''>Having</span> <span m=''242220''>looked</span>
  <span m=''242530''>at</span> <span m=''242630''>this</span> <span m=''242890''>one,</span>
  <span m=''243430''>a</span> <span m=''243690''>and</span> <span m=''243910''>b</span>
  <span m=''244220''>are</span> <span m=''247070''>worth</span> <span m=''247960''>looking</span>
  <span m=''248350''>at</span> <span m=''248650''>in</span> <span m=''248810''>this</span>
  <span m=''249480''>div,</span> <span m=''253590''>grad,</span> <span m=''254460''>potential,
  stream function</span> <span m=''255430''>world</span> <span m=''256310''>that</span>
  <span m=''257820''>we''re</span> <span m=''258010''>in.</span> <span m=''258690''>Those</span>
  <span m=''258830''>are</span> <span m=''259850''>typical</span> <span m=''260340''>exercises</span>
  <span m=''261210''>in</span> <span m=''261450''>that</span> <span m=''261680''>area.</span>
  <span m=''263630''>Yes,</span> <span m=''263900''>question.</span> </p><p><span
  m=''264370''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''266180''>PROFESSOR STRANG:
  Oh,</span> <span m=''266810''>good</span> <span m=''267290''>question.</span> <span
  m=''267670''>Yes.</span> <span m=''267910''>Thanks</span> <span m=''268180''>for</span>
  <span m=''268350''>reminding</span> <span m=''268860''>me.</span> <span m=''269200''>So,</span>
  <span m=''270560''>solutions</span> <span m=''271300''>to</span> <span m=''271950''>the</span>
  <span m=''272380''>homework</span> <span m=''272790''>that</span> <span m=''273130''>you''re</span>
  <span m=''273960''>practicing</span> <span m=''274580''>with.</span> <span m=''275160''>If</span>
  <span m=''275440''>anybody</span> <span m=''275960''>has</span> <span m=''276760''>typed</span>
  <span m=''277190''>up</span> <span m=''277670''>solutions</span> <span m=''278290''>or</span>
  <span m=''278510''>could,</span> <span m=''281150''>we''ll</span> <span m=''281380''>post</span>
  <span m=''281670''>them</span> <span m=''281770''>right</span> <span m=''281970''>away.</span>
  <span m=''283680''>So</span> <span m=''283970''>I''ll</span> <span m=''284170''>just</span>
  <span m=''284490''>hope</span> <span m=''284740''>for</span> <span m=''284930''>an</span>
  <span m=''285070''>email</span> <span m=''285490''>from</span> <span m=''285700''>somebody</span>
  <span m=''287450''>who</span> <span m=''289590''>solved</span> <span m=''290390''>some</span>
  <span m=''290790''>or</span> <span m=''290960''>all</span> <span m=''291300''>of</span>
  <span m=''291470''>those</span> <span m=''291970''>problems.</span> <span m=''293480''>And</span>
  <span m=''293700''>of</span> <span m=''293790''>course</span> <span m=''294110''>you''ll</span>
  <span m=''294290''>see</span> <span m=''294470''>me</span> <span m=''294580''>again</span>
  <span m=''294920''>Wednesday.</span> <span m=''296630''>But</span> <span m=''297020''>that''s</span>
  <span m=''297300''>an</span> <span m=''297390''>invitation</span> <span m=''298140''>for</span>
  <span m=''298280''>anybody</span> <span m=''298740''>who</span> <span m=''299950''>worked</span>
  <span m=''300370''>through</span> <span m=''300700''>those</span> <span m=''303320''>homeworks</span>
  <span m=''303820''>that</span> <span m=''304070''>I''ll</span> <span m=''304320''>never</span>
  <span m=''304610''>collect.</span> <span m=''305410''>The</span> <span m=''305910''>current</span>
  <span m=''306270''>homework.</span> <span m=''307190''>OK,</span> <span m=''308150''>thanks</span>
  <span m=''308470''>for</span> <span m=''308610''>that.</span> <span m=''309500''>Other</span>
  <span m=''309830''>questions</span> <span m=''310520''>about</span> <span m=''310860''>the</span>
  <span m=''310960''>exam,</span> <span m=''311430''>and</span> <span m=''311590''>then</span>
  <span m=''311770''>you''ll</span> <span m=''311940''>have</span> <span m=''312120''>another</span>
  <span m=''312470''>chance</span> <span m=''313090''>Wednesday</span> <span m=''314560''>to</span>
  <span m=''315140''>ask</span> <span m=''315510''>about</span> <span m=''315820''>that,</span>
  <span m=''316130''>so</span> <span m=''316300''>those</span> <span m=''316570''>are</span>
  <span m=''316640''>the</span> <span m=''316800''>topics.</span> <span m=''318030''>OK.</span>
  <span m=''319520''>And</span> <span m=''320210''>before</span> <span m=''320730''>I</span>
  <span m=''321340''>get</span> <span m=''321590''>to</span> <span m=''321730''>the</span>
  <span m=''321920''>fast</span> <span m=''322260''>Poisson</span> <span m=''322470''>solvers</span>
  <span m=''324350''>there''s</span> <span m=''324680''>so</span> <span m=''324840''>much</span>
  <span m=''325300''>about</span> <span m=''325590''>Laplace''s</span> <span m=''326270''>equation</span>
  <span m=''326880''>to</span> <span m=''327050''>say</span> <span m=''327930''>and</span>
  <span m=''329140''>I</span> <span m=''329430''>think</span> <span m=''329920''>it</span>
  <span m=''330170''>still</span> <span m=''330400''>remains</span> <span m=''330870''>to</span>
  <span m=''331100''>write</span> <span m=''331580''>Green''s</span> <span m=''332030''>formula</span>
  <span m=''332630''>on</span> <span m=''332780''>the</span> <span m=''332880''>board.</span>
  <span m=''334010''>And</span> <span m=''334530''>that''s</span> <span m=''337260''>part</span>
  <span m=''337480''>of</span> <span m=''337560''>the</span> <span m=''337650''>big</span>
  <span m=''337960''>picture</span> <span m=''338450''>of</span> <span m=''338710''>Laplace''s</span>
  <span m=''339390''>equation</span> <span m=''339990''>is</span> <span m=''340160''>to</span>
  <span m=''340310''>see</span> <span m=''340620''>this.</span> <span m=''341350''>So</span>
  <span m=''342860''>we</span> <span m=''343220''>have</span> <span m=''343370''>double</span>
  <span m=''343770''>integrals</span> <span m=''344220''>now,</span> <span m=''344500''>that''s</span>
  <span m=''344860''>the</span> <span m=''345010''>difference.</span> <span m=''345900''>But</span>
  <span m=''346080''>we''re</span> <span m=''346270''>still</span> <span m=''346670''>integrating</span>
  <span m=''348330''>Au</span> <span m=''349800''>against</span> <span m=''350290''>w.</span>
  <span m=''351730''>So</span> <span m=''351940''>Au</span> <span m=''352480''>is</span>
  <span m=''352680''>the</span> <span m=''352770''>gradient</span> <span m=''353310''>of</span>
  <span m=''353430''>u;</span> <span m=''354290''>w</span> <span m=''354800''>is</span>
  <span m=''355080''>w_1,</span> <span m=''355680''>w_2,</span> <span m=''356430''>and</span>
  <span m=''356580''>this</span> <span m=''356760''>is</span> <span m=''356930''>now</span>
  <span m=''357230''>for</span> <span m=''358720''>any u</span> <span m=''359060''>and</span>
  <span m=''359230''>any</span> <span m=''359500''>w,</span> <span m=''360000''>so</span>
  <span m=''360210''>I</span> <span m=''360290''>want</span> <span m=''360580''>the</span>
  <span m=''362470''>inner</span> <span m=''362680''>product.</span> <span m=''364080''>Of</span>
  <span m=''364660''>the</span> <span m=''364880''>gradient</span> <span m=''365270''>of
  u</span> <span m=''366150''>with</span> <span m=''367260''>any</span> <span m=''367550''>w,</span>
  <span m=''368300''>so</span> <span m=''368510''>this</span> <span m=''368720''>is</span>
  <span m=''368960''>like</span> <span m=''369270''>the</span> <span m=''369400''>Auw</span>
  <span m=''370380''>part,</span> <span m=''371170''>so</span> <span m=''371370''>the</span>
  <span m=''371460''>gradient</span> <span m=''371760''>of u,</span> <span m=''372250''>that</span>
  <span m=''372450''>would</span> <span m=''372620''>be</span> <span m=''372770''>a</span>
  <span m=''372890''>du/dx</span> <span m=''374510''>times</span> <span m=''374910''>the</span>
  <span m=''375030''>w_1.</span> <span m=''376640''>And</span> <span m=''376720''>a</span>
  <span m=''377150''>du/dy</span> <span m=''378640''>times</span> <span m=''379490''>w_2.</span>
  <span m=''380400''>dx dy,</span> <span m=''382760''>that</span> <span m=''383000''>would</span>
  <span m=''383190''>be.</span> <span m=''384680''>So</span> <span m=''385630''>inner</span>
  <span m=''385890''>products,</span> <span m=''386750''>if</span> <span m=''386980''>I''m</span>
  <span m=''387200''>in</span> <span m=''387400''>two</span> <span m=''387620''>dimensions,</span>
  <span m=''388260''>inner</span> <span m=''388490''>products</span> <span m=''388970''>are</span>
  <span m=''389100''>integrals,</span> <span m=''389620''>of</span> <span m=''389760''>course,</span>
  <span m=''390150''>if</span> <span m=''390280''>I''m</span> <span m=''390460''>dealing</span>
  <span m=''390770''>with</span> <span m=''390940''>functions.</span> <span m=''391870''>So</span>
  <span m=''392130''>this</span> <span m=''392330''>is</span> <span m=''392500''>like</span>
  <span m=''392780''>the</span> <span m=''392920''>Au</span> <span m=''395650''>against</span>
  <span m=''396410''>w.</span> <span m=''397560''>Inner</span> <span m=''398220''>product.</span>
  <span m=''399240''>Au</span> <span m=''399960''>is</span> <span m=''400410''>those</span>
  <span m=''400830''>two</span> <span m=''400980''>pieces,</span> <span m=''401510''>w</span>
  <span m=''401850''>is</span> <span m=''402060''>those,</span> <span m=''402660''>there''s</span>
  <span m=''402940''>the</span> <span m=''403040''>dot</span> <span m=''403280''>product.</span>
  </p><p><span m=''404070''>And</span> <span m=''404290''>now</span> <span m=''405260''>the</span>
  <span m=''405470''>key</span> <span m=''406260''>idea</span> <span m=''406810''>behind</span>
  <span m=''407410''>what</span> <span m=''407750''>Green''s</span> <span m=''408110''>formula</span>
  <span m=''408710''>is</span> <span m=''408910''>about,</span> <span m=''409450''>what</span>
  <span m=''409660''>we</span> <span m=''409780''>use</span> <span m=''410330''>it</span>
  <span m=''411840''>for</span> <span m=''412200''>in</span> <span m=''412420''>1-D,</span>
  <span m=''413360''>is</span> <span m=''413730''>integration</span> <span m=''414360''>by</span>
  <span m=''414560''>parts.</span> <span m=''415690''>So an</span> <span m=''415930''>integration</span>
  <span m=''416500''>by</span> <span m=''416660''>parts</span> <span m=''417110''>is</span>
  <span m=''417270''>going</span> <span m=''417460''>to</span> <span m=''417530''>produce</span>
  <span m=''419080''>a</span> <span m=''419250''>double</span> <span m=''419600''>integral</span>
  <span m=''420150''>in</span> <span m=''420380''>which--</span> <span m=''421940''>So</span>
  <span m=''422080''>I''m</span> <span m=''422230''>just</span> <span m=''422440''>sort</span>
  <span m=''422600''>of</span> <span m=''422690''>thinking</span> <span m=''423190''>through</span>
  <span m=''423550''>Green''s</span> <span m=''423970''>formula.</span> <span m=''425480''>Of</span>
  <span m=''425590''>course,</span> <span m=''425870''>we</span> <span m=''426000''>could</span>
  <span m=''426130''>just</span> <span m=''426340''>say</span> <span m=''426620''>OK,</span>
  <span m=''426900''>remember</span> <span m=''427360''>that</span> <span m=''427590''>formula.</span>
  <span m=''428620''>But</span> <span m=''429540''>you</span> <span m=''429830''>want</span>
  <span m=''430040''>to</span> <span m=''430120''>just</span> <span m=''430340''>see</span>
  <span m=''430680''>it</span> <span m=''430900''>as</span> <span m=''431210''>an</span>
  <span m=''431340''>integration</span> <span m=''431910''>by</span> <span m=''432090''>parts.</span>
  <span m=''432440''>See</span> <span m=''432670''>how</span> <span m=''432890''>it</span>
  <span m=''433020''>evolved.</span> <span m=''434560''>And</span> <span m=''434760''>then</span>
  <span m=''434920''>we</span> <span m=''435040''>can</span> <span m=''435190''>think.</span>
  <span m=''435420''>So</span> <span m=''436100''>I</span> <span m=''436170''>plan</span>
  <span m=''436540''>to</span> <span m=''436670''>do</span> <span m=''437370''>integration</span>
  <span m=''437930''>by</span> <span m=''438090''>parts,</span> <span m=''438560''>that</span>
  <span m=''439120''>x derivative</span> <span m=''439590''>will</span> <span m=''440050''>get</span>
  <span m=''440280''>taken</span> <span m=''440690''>off</span> <span m=''441050''>of</span>
  <span m=''441210''>u</span> <span m=''441560''>and</span> <span m=''441730''>put</span>
  <span m=''441950''>onto</span> <span m=''442250''>w_1.</span> <span m=''443570''>So</span>
  <span m=''443800''>I''ll</span> <span m=''443940''>have</span> <span m=''444170''>u*dw_1--</span>
  <span m=''445490''>Oh,</span> <span m=''445720''>there''ll</span> <span m=''445870''>be</span>
  <span m=''446020''>a</span> <span m=''446110''>minus</span> <span m=''446620''>right,</span>
  <span m=''447410''>from</span> <span m=''447600''>the</span> <span m=''447730''>integration</span>
  <span m=''448250''>by</span> <span m=''448410''>part.</span> <span m=''449200''>u</span>
  <span m=''449550''>will</span> <span m=''449750''>multiply</span> <span m=''450330''>minus</span>
  <span m=''451500''>dw_1/dx,</span> <span m=''456330''>so</span> <span m=''456520''>that</span>
  <span m=''456750''>was</span> <span m=''457560''>this</span> <span m=''457780''>guy</span>
  <span m=''458040''>integrated</span> <span m=''458490''>by</span> <span m=''458640''>parts.</span>
  <span m=''459090''>Now</span> <span m=''459280''>this</span> <span m=''459590''>one</span>
  <span m=''459800''>integrated</span> <span m=''460950''>by</span> <span m=''461130''>parts,</span>
  <span m=''461640''>a</span> <span m=''461750''>y</span> <span m=''462210''>derivative</span>
  <span m=''462940''>is</span> <span m=''463090''>coming</span> <span m=''463410''>off</span>
  <span m=''463660''>of</span> <span m=''463800''>u</span> <span m=''464440''>and</span>
  <span m=''464670''>onto</span> <span m=''465070''>w_2.</span> <span m=''466500''>So</span>
  <span m=''466720''>that''ll</span> <span m=''467070''>leave</span> <span m=''467380''>me</span>
  <span m=''467520''>with</span> <span m=''467780''>u</span> <span m=''468340''>times</span>
  <span m=''469190''>dw_2/dy</span> <span m=''470650''>with</span> <span m=''470950''>the</span>
  <span m=''471050''>minus</span> <span m=''471570''>sign.</span> <span m=''473720''>That</span>
  <span m=''473880''>comes</span> <span m=''474360''>also</span> <span m=''474840''>from</span>
  <span m=''475070''>that</span> <span m=''475320''>integration</span> <span m=''475920''>by</span>
  <span m=''476140''>parts.</span> <span m=''477370''>And</span> <span m=''477570''>then</span>
  <span m=''477810''>there''s</span> <span m=''478060''>the</span> <span m=''478180''>boundary</span>
  <span m=''478670''>term.</span> <span m=''480100''>So</span> <span m=''480330''>there''s</span>
  <span m=''480650''>the</span> <span m=''480730''>term</span> <span m=''481570''>which--</span>
  <span m=''482330''>Now</span> <span m=''482700''>the</span> <span m=''482860''>boundary</span>
  <span m=''483410''>of</span> <span m=''483510''>the</span> <span m=''483600''>region</span>
  <span m=''484100''>is</span> <span m=''484360''>the</span> <span m=''484750''>curve</span>
  <span m=''485150''>around</span> <span m=''485630''>it</span> <span m=''485800''>instead</span>
  <span m=''486210''>of</span> <span m=''486340''>just</span> <span m=''486650''>the</span>
  <span m=''486770''>two</span> <span m=''486950''>points.</span> <span m=''487870''>And</span>
  <span m=''488620''>what</span> <span m=''488950''>do</span> <span m=''489060''>we</span>
  <span m=''489260''>see</span> <span m=''489790''>in the</span> <span m=''489960''>integration</span>
  <span m=''490550''>by</span> <span m=''490720''>parts?</span> <span m=''491590''>Well,</span>
  <span m=''492360''>from</span> <span m=''492520''>the</span> <span m=''492630''>boundary</span>
  <span m=''493050''>term</span> <span m=''493380''>we</span> <span m=''493490''>expect</span>
  <span m=''493930''>a</span> <span m=''494000''>u</span> <span m=''495090''>and</span>
  <span m=''495460''>then</span> <span m=''495790''>the</span> <span m=''495900''>key</span>
  <span m=''497210''>point</span> <span m=''497610''>is</span> <span m=''498010''>it''s</span>
  <span m=''498300''>w</span> <span m=''498890''>dot</span> <span m=''499330''>n</span>
  <span m=''500460''>ds.</span> <span m=''501200''>It''s</span> <span m=''501480''>the</span>
  <span m=''501670''>normal</span> <span m=''502390''>component</span> <span m=''503180''>of</span>
  <span m=''504470''>of</span> <span m=''504680''>this</span> <span m=''504950''>vector</span>
  <span m=''505340''>w.</span> <span m=''506340''>Because</span> <span m=''506700''>we''re</span>
  <span m=''506920''>looking,</span> <span m=''508100''>well,</span> <span m=''508680''>that''s</span>
  <span m=''508940''>just</span> <span m=''509210''>what</span> <span m=''509390''>it</span>
  <span m=''509520''>is.</span> </p><p><span m=''511850''>So</span> <span m=''512000''>that''s</span>
  <span m=''512300''>Green''s</span> <span m=''512740''>formula</span> <span m=''513280''>written</span>
  <span m=''513620''>out</span> <span m=''514560''>in</span> <span m=''514800''>detail.</span>
  <span m=''515720''>And</span> <span m=''516000''>this</span> <span m=''516250''>is</span>
  <span m=''516660''>the</span> <span m=''516790''>formula</span> <span m=''517220''>that</span>
  <span m=''517470''>tells</span> <span m=''517810''>us</span> <span m=''518400''>that</span>
  <span m=''518570''>here,</span> <span m=''519510''>if</span> <span m=''519730''>this</span>
  <span m=''520010''>was</span> <span m=''520970''>A,</span> <span m=''521540''>A
  being</span> <span m=''522100''>gradient,</span> <span m=''524460''>on</span> <span
  m=''524630''>the</span> <span m=''524730''>left</span> <span m=''525060''>side</span>
  <span m=''525410''>I''m</span> <span m=''525580''>seeing</span> <span m=''525940''>grad</span>
  <span m=''526450''>u</span> <span m=''528810''>in</span> <span m=''528950''>a</span>
  <span m=''529020''>product</span> <span m=''529420''>with</span> <span m=''529550''>w,</span>
  <span m=''530680''>and</span> <span m=''530850''>over</span> <span m=''531080''>here</span>
  <span m=''532410''>I''m</span> <span m=''532710''>seeing</span> <span m=''533080''>the</span>
  <span m=''533170''>inner</span> <span m=''533380''>product</span> <span m=''533780''>of</span>
  <span m=''534010''>u</span> <span m=''534590''>with,</span> <span m=''535120''>what''s</span>
  <span m=''535490''>that?</span> <span m=''537460''>If</span> <span m=''537630''>I</span>
  <span m=''537770''>look</span> <span m=''538050''>at</span> <span m=''538160''>minus,</span>
  <span m=''538660''>if</span> <span m=''538840''>I</span> <span m=''538940''>have</span>
  <span m=''539150''>this</span> <span m=''539390''>quantity</span> <span m=''539990''>there</span>
  <span m=''540290''>that''s</span> <span m=''540510''>in</span> <span m=''540670''>parentheses,</span>
  <span m=''541610''>what''s</span> <span m=''541860''>its</span> <span m=''542080''>name?</span>
  <span m=''544470''>It''s</span> <span m=''544760''>the</span> <span m=''544910''>divergence.</span>
  <span m=''545420''>It''s</span> <span m=''545760''>minus</span> <span m=''546290''>the</span>
  <span m=''546420''>divergence</span> <span m=''547090''>of</span> <span m=''547310''>w.</span>
  <span m=''551680''>Plus</span> <span m=''552590''>the</span> <span m=''553350''>boundary</span>
  <span m=''553670''>term.</span> <span m=''555620''>So</span> <span m=''556560''>this</span>
  <span m=''556820''>is</span> <span m=''557010''>why</span> <span m=''559030''>I</span>
  <span m=''559340''>allowed</span> <span m=''559770''>myself</span> <span m=''560390''>this</span>
  <span m=''563630''>gradient</span> <span m=''564030''>transpose</span> <span m=''564810''>equal</span>
  <span m=''565100''>minus</span> <span m=''565540''>divergence</span> <span m=''566150''>to</span>
  <span m=''566300''>see</span> <span m=''566640''>that</span> <span m=''567110''>if</span>
  <span m=''567380''>A</span> <span m=''567670''>is</span> <span m=''567850''>the</span>
  <span m=''567940''>gradient</span> <span m=''568930''>then</span> <span m=''569160''>A</span>
  <span m=''569380''>transpose</span> <span m=''570070''>will</span> <span m=''570260''>be</span>
  <span m=''570400''>minus</span> <span m=''570870''>the</span> <span m=''570990''>divergence.</span>
  <span m=''571660''>And</span> <span m=''571930''>this</span> <span m=''572620''>shows</span>
  <span m=''573530''>how</span> <span m=''573820''>that--</span> <span m=''574190''>just</span>
  <span m=''575160''>sort</span> <span m=''575460''>of</span> <span m=''575530''>shows</span>
  <span m=''575900''>you</span> <span m=''576010''>the</span> <span m=''576130''>integration</span>
  <span m=''576690''>by</span> <span m=''577910''>parts</span> <span m=''578300''>that</span>
  <span m=''578470''>makes</span> <span m=''578800''>that</span> <span m=''579040''>true.</span>
  <span m=''579890''>So,</span> <span m=''581820''>you</span> <span m=''581920''>know</span>
  <span m=''582090''>there''s</span> <span m=''582360''>so</span> <span m=''582900''>many</span>
  <span m=''586900''>integral</span> <span m=''587350''>formulas</span> <span m=''590100''>in</span>
  <span m=''590380''>this</span> <span m=''591130''>world</span> <span m=''591600''>of</span>
  <span m=''591730''>vector</span> <span m=''592040''>calculus.</span> <span m=''592700''>But</span>
  <span m=''593040''>this</span> <span m=''593280''>is</span> <span m=''593510''>like,</span>
  <span m=''594260''>one</span> <span m=''594560''>to</span> <span m=''594650''>know.</span>
  <span m=''595450''>And</span> <span m=''595640''>actually,</span> <span m=''597520''>if</span>
  <span m=''597720''>you</span> <span m=''597810''>want</span> <span m=''598030''>to</span>
  <span m=''598110''>know,</span> <span m=''598400''>OK</span> <span m=''599050''>what</span>
  <span m=''599320''>about</span> <span m=''599610''>the</span> <span m=''599750''>details,</span>
  <span m=''600370''>where</span> <span m=''600630''>did</span> <span m=''600780''>that</span>
  <span m=''601020''>come</span> <span m=''601330''>from?</span> <span m=''601980''>This</span>
  <span m=''602410''>actually</span> <span m=''603090''>turns</span> <span m=''603420''>out</span>
  <span m=''603640''>to</span> <span m=''603760''>be,</span> <span m=''604020''>and</span>
  <span m=''604160''>the</span> <span m=''604290''>text</span> <span m=''604800''>will</span>
  <span m=''605520''>make</span> <span m=''605900''>it</span> <span m=''606080''>clear,</span>
  <span m=''606700''>is</span> <span m=''607020''>the</span> <span m=''607150''>divergence</span>
  <span m=''607870''>theorem.</span> <span m=''609110''>The</span> <span m=''609240''>divergence</span>
  <span m=''609870''>theorem</span> <span m=''610260''>gives</span> <span m=''610490''>us</span>
  <span m=''610870''>this,</span> <span m=''612340''>this,</span> <span m=''612650''>exactly</span>
  <span m=''613260''>this,</span> <span m=''614490''>so</span> <span m=''614750''>the</span>
  <span m=''615180''>divergence</span> <span m=''616080''>theorem</span> <span m=''617720''>applied</span>
  <span m=''618510''>to</span> <span m=''621370''>the</span> <span m=''621950''>vector</span>
  <span m=''622340''>field</span> <span m=''622820''>u</span> <span m=''623220''>times</span>
  <span m=''623650''>w.</span> <span m=''626070''>It</span> <span m=''626230''>turns</span>
  <span m=''626550''>out</span> <span m=''627000''>if</span> <span m=''627230''>I</span>
  <span m=''627330''>apply</span> <span m=''627620''>the</span> <span m=''627750''>divergence</span>
  <span m=''628370''>theorem</span> <span m=''628760''>to</span> <span m=''628920''>that,</span>
  <span m=''629790''>then</span> <span m=''630020''>I</span> <span m=''630100''>get</span>
  <span m=''630270''>a</span> <span m=''630300''>whole</span> <span m=''630510''>lot</span>
  <span m=''630730''>of</span> <span m=''630840''>terms</span> <span m=''631320''>from</span>
  <span m=''631540''>the</span> <span m=''631640''>divergence</span> <span m=''632260''>of</span>
  <span m=''632380''>that,</span> <span m=''632870''>and</span> <span m=''633140''>they</span>
  <span m=''633290''>are</span> <span m=''633480''>these.</span> <span m=''634610''>And</span>
  <span m=''634860''>then</span> <span m=''635060''>I</span> <span m=''635180''>get</span>
  <span m=''635680''>this</span> <span m=''636320''>for</span> <span m=''636690''>the</span>
  <span m=''637580''>boundary.</span> <span m=''638270''>The</span> <span m=''638380''>flux</span>
  <span m=''638830''>out.</span> <span m=''640650''>OK,</span> <span m=''641210''>so.</span>
  <span m=''642540''>I</span> <span m=''642650''>just</span> <span m=''643310''>didn''t</span>
  <span m=''643590''>want</span> <span m=''643780''>to</span> <span m=''643840''>leave</span>
  <span m=''644170''>the</span> <span m=''644310''>subject</span> <span m=''644780''>without</span>
  <span m=''645060''>writing</span> <span m=''645550''>down</span> <span m=''645870''>the</span>
  <span m=''647290''>central</span> <span m=''648570''>thing.</span> <span m=''649110''>What</span>
  <span m=''649410''>does</span> <span m=''649610''>this</span> <span m=''649840''>tell</span>
  <span m=''650120''>us,</span> <span m=''650340''>then?</span> <span m=''652530''>I</span>
  <span m=''652700''>have</span> <span m=''652880''>a</span> <span m=''652960''>region.</span>
  <span m=''655240''>In</span> <span m=''655560''>that</span> <span m=''655750''>region</span>
  <span m=''656210''>I</span> <span m=''656370''>have</span> <span m=''656700''>Laplace''s</span>
  <span m=''656870''>equation</span> <span m=''658470''>or</span> <span m=''658930''>Poisson''s</span>
  <span m=''659240''>equation.</span> <span m=''663430''>Say</span> <span m=''664220''>Poisson.</span>
  <span m=''666710''>On</span> <span m=''667060''>the</span> <span m=''667160''>boundary.</span>
  <span m=''667700''>Now,</span> <span m=''668920''>this</span> <span m=''669050''>is</span>
  <span m=''669170''>the</span> <span m=''669280''>final</span> <span m=''670120''>thing</span>
  <span m=''670400''>to</span> <span m=''670510''>ask</span> <span m=''670900''>you</span>
  <span m=''671010''>about.</span> <span m=''672230''>What</span> <span m=''672670''>are</span>
  <span m=''672920''>suitable</span> <span m=''675000''>boundary</span> <span m=''675420''>conditions</span>
  <span m=''676470''>for</span> <span m=''676710''>this</span> <span m=''677130''>problem</span>
  <span m=''677690''>in</span> <span m=''678140''>2-D?</span> <span m=''679220''>Right?</span>
  <span m=''680200''>In</span> <span m=''680400''>1-D,</span> <span m=''682130''>by</span>
  <span m=''682400''>now</span> <span m=''682720''>we</span> <span m=''683010''>know</span>
  <span m=''683310''>boundary</span> <span m=''683740''>conditions.</span> <span m=''684840''>We</span>
  <span m=''684970''>know</span> <span m=''685120''>the</span> <span m=''685260''>main</span>
  <span m=''685600''>ones.</span> <span m=''686500''>There''s</span> <span m=''686760''>fixed,</span>
  <span m=''688100''>where</span> <span m=''688270''>u</span> <span m=''688650''>is</span>
  <span m=''688910''>given.</span> <span m=''689730''>Or</span> <span m=''690080''>there''s</span>
  <span m=''690340''>free</span> <span m=''691510''>where</span> <span m=''691850''>the</span>
  <span m=''692100''>slope</span> <span m=''692520''>is</span> <span m=''692870''>given.</span>
  <span m=''693780''>Now,</span> <span m=''694640''>what</span> <span m=''694930''>do</span>
  <span m=''694990''>we</span> <span m=''695100''>do</span> <span m=''695260''>here?</span>
  </p><p><span m=''697270''>So</span> <span m=''700380''>this</span> <span m=''700600''>is</span>
  <span m=''700740''>where</span> <span m=''700950''>we</span> <span m=''701070''>used</span>
  <span m=''701310''>to</span> <span m=''701420''>be</span> <span m=''701590''>in</span>
  <span m=''701720''>1-D.</span> <span m=''704270''>That''s</span> <span m=''704540''>a</span>
  <span m=''704660''>straight</span> <span m=''705000''>line.</span> <span m=''706190''>Not</span>
  <span m=''706590''>perfectly</span> <span m=''707130''>straight</span> <span m=''707520''>but</span>
  <span m=''707760''>anyway,</span> <span m=''708090''>straight</span> <span m=''708410''>line.</span>
  <span m=''708890''>So</span> <span m=''709610''>1-D</span> <span m=''710950''>there</span>
  <span m=''711140''>are only</span> <span m=''711390''>two</span> <span m=''711650''>boundary</span>
  <span m=''712210''>points.</span> <span m=''712930''>The</span> <span m=''713050''>normal</span>
  <span m=''713470''>vector</span> <span m=''713920''>goes</span> <span m=''714520''>that</span>
  <span m=''714800''>way,</span> <span m=''715740''>and</span> <span m=''715940''>that</span>
  <span m=''716140''>way.</span> <span m=''716400''>This</span> <span m=''716620''>is</span>
  <span m=''716780''>the</span> <span m=''716990''>n</span> <span m=''717560''>in</span>
  <span m=''717850''>this</span> <span m=''718610''>formula.</span> <span m=''721510''>I</span>
  <span m=''721720''>think</span> <span m=''721950''>if</span> <span m=''722070''>I</span>
  <span m=''723450''>just</span> <span m=''723690''>wrote</span> <span m=''723880''>ordinary</span>
  <span m=''724460''>integration</span> <span m=''724950''>by</span> <span m=''725090''>parts</span>
  <span m=''725490''>it</span> <span m=''725610''>would</span> <span m=''725780''>look</span>
  <span m=''725990''>just</span> <span m=''726270''>the</span> <span m=''726390''>same</span>
  <span m=''727980''>and</span> <span m=''728350''>my</span> <span m=''729780''>boundary</span>
  <span m=''730420''>reduces</span> <span m=''731060''>to</span> <span m=''731210''>two</span>
  <span m=''731470''>points.</span> <span m=''732620''>Here</span> <span m=''733510''>my</span>
  <span m=''733680''>boundary''s</span> <span m=''734240''>the</span> <span m=''734370''>whole</span>
  <span m=''734680''>curve</span> <span m=''735040''>around.</span> <span m=''735940''>So</span>
  <span m=''738190''>what</span> <span m=''738420''>corresponds</span> <span m=''739080''>to</span>
  <span m=''739280''>fixed</span> <span m=''739820''>boundary</span> <span m=''740260''>conditions,</span>
  <span m=''741210''>and</span> <span m=''741390''>what</span> <span m=''741620''>corresponds</span>
  <span m=''742320''>to</span> <span m=''742450''>free</span> <span m=''742820''>boundary</span>
  <span m=''743250''>conditions?</span> <span m=''743720''>So</span> <span m=''743880''>I</span>
  <span m=''743980''>want</span> <span m=''745030''>the--</span> <span m=''745450''>What</span>
  <span m=''746200''>corresponds</span> <span m=''746460''>to</span> <span m=''746600''>fixed,</span>
  <span m=''747860''>those</span> <span m=''748010''>are the</span> <span m=''748150''>ones</span>
  <span m=''748310''>that</span> <span m=''748790''>named</span> <span m=''749200''>after</span>
  <span m=''749620''>Dirichlet.</span> <span m=''752940''>Other</span> <span m=''753220''>names?</span>
  <span m=''754110''>Or</span> <span m=''754490''>the</span> <span m=''755210''>rest</span>
  <span m=''755990''>will</span> <span m=''756210''>be</span> <span m=''756420''>free,</span>
  <span m=''757450''>those are</span> <span m=''757710''>the</span> <span m=''757840''>ones</span>
  <span m=''758160''>named</span> <span m=''758520''>after</span> <span m=''758890''>Neumann,</span>
  <span m=''759790''>and</span> <span m=''761180''>those</span> <span m=''761420''>are</span>
  <span m=''761760''>what</span> <span m=''762010''>we</span> <span m=''762180''>call</span>
  <span m=''762600''>natural</span> <span m=''763420''>boundary</span> <span m=''763890''>conditions.</span>
  <span m=''769040''>So</span> <span m=''769290''>I</span> <span m=''769440''>haven''t--</span>
  <span m=''771130''>Just</span> <span m=''771480''>ready</span> <span m=''771760''>to</span>
  <span m=''771900''>finish</span> <span m=''772400''>this</span> <span m=''772660''>story</span>
  <span m=''773070''>here.</span> <span m=''773810''>What</span> <span m=''774470''>are</span>
  <span m=''775810''>the</span> <span m=''775890''>possibilities?</span> <span m=''777400''>Well,</span>
  <span m=''778160''>in</span> <span m=''778400''>each</span> <span m=''779550''>we</span>
  <span m=''779750''>could</span> <span m=''779970''>have</span> <span m=''780410''>part</span>
  <span m=''780760''>of</span> <span m=''780850''>the</span> <span m=''780970''>boundary</span>
  <span m=''781420''>could</span> <span m=''781620''>be</span> <span m=''781780''>fixed.</span>
  <span m=''782900''>Part</span> <span m=''783170''>could</span> <span m=''783320''>be</span>
  <span m=''783480''>free.</span> <span m=''785620''>So</span> <span m=''786200''>fixed</span>
  <span m=''786850''>would</span> <span m=''787150''>mean</span> <span m=''788120''>say</span>
  <span m=''788360''>some other</span> <span m=''788770''>boundary,</span> <span m=''789250''>let</span>
  <span m=''789370''>me</span> <span m=''789490''>call</span> <span m=''789740''>this</span>
  <span m=''790420''>part</span> <span m=''790670''>of</span> <span m=''790750''>the</span>
  <span m=''790830''>boundary</span> <span m=''791290''>fixed.</span> <span m=''791790''>So</span>
  <span m=''791950''>the</span> <span m=''792100''>temperature,</span> <span m=''793170''>for</span>
  <span m=''793280''>example</span> <span m=''794350''>is</span> <span m=''794880''>fixed</span>
  <span m=''795470''>on</span> <span m=''795630''>this</span> <span m=''795810''>part</span>
  <span m=''796070''>of</span> <span m=''796140''>the</span> <span m=''796230''>boundary.</span>
  <span m=''797090''>So</span> <span m=''797270''>this</span> <span m=''797500''>would</span>
  <span m=''797670''>be</span> <span m=''797960''>like,</span> <span m=''799110''>and</span>
  <span m=''799520''>this</span> <span m=''799700''>might</span> <span m=''799910''>be</span>
  <span m=''799990''>the</span> <span m=''800090''>whole</span> <span m=''800320''>boundary.</span>
  <span m=''800790''>It</span> <span m=''800940''>might</span> <span m=''801130''>be</span>
  <span m=''801270''>fixed</span> <span m=''801570''>on</span> <span m=''801710''>the</span>
  <span m=''801790''>whole</span> <span m=''802060''>one,</span> <span m=''802250''>but</span>
  <span m=''802470''>I''m</span> <span m=''802700''>now</span> <span m=''803010''>allowing</span>
  <span m=''803910''>the</span> <span m=''804030''>possibility</span> <span m=''804860''>that</span>
  <span m=''805130''>we</span> <span m=''805270''>have</span> <span m=''805590''>here</span>
  <span m=''806150''>a fixed</span> <span m=''806740''>part</span> <span m=''808720''>and</span>
  <span m=''808990''>here</span> <span m=''809280''>we</span> <span m=''809410''>have</span>
  <span m=''810920''>a</span> <span m=''811180''>free</span> <span m=''811560''>part.</span>
  <span m=''813780''>In</span> <span m=''814210''>fluids,</span> <span m=''816160''>here</span>
  <span m=''816390''>we</span> <span m=''816530''>have</span> <span m=''817580''>fixed</span>
  <span m=''818410''>corresponds</span> <span m=''819190''>to,</span> <span m=''819290''>like,</span>
  <span m=''819540''>there''s</span> <span m=''819720''>some</span> <span m=''819950''>obstacle</span>
  <span m=''820500''>there.</span> <span m=''820860''>Some</span> <span m=''823000''>wall.</span>
  <span m=''824260''>Free</span> <span m=''824990''>is</span> <span m=''825490''>where</span>
  <span m=''826100''>the</span> <span m=''827200''>fluid</span> <span m=''827670''>is</span>
  <span m=''827850''>coming</span> <span m=''828160''>in</span> <span m=''828520''>or</span>
  <span m=''828710''>flowing</span> <span m=''829120''>out.</span> <span m=''830960''>So</span>
  <span m=''831190''>there</span> <span m=''831510''>it''s</span> <span m=''832480''>a</span>
  <span m=''832590''>velocity</span> <span m=''833330''>condition.</span> </p><p><span
  m=''834190''>OK,</span> <span m=''834880''>so</span> <span m=''835110''>fixed</span>
  <span m=''835750''>conditions,</span> <span m=''836460''>these</span> <span m=''836730''>Dirichlet</span>
  <span m=''837440''>ones,</span> <span m=''837820''>will</span> <span m=''838060''>be</span>
  <span m=''838370''>like,</span> <span m=''839900''>tell</span> <span m=''840170''>me</span>
  <span m=''840380''>what</span> <span m=''840770''>u</span> <span m=''841610''>is,</span>
  <span m=''842310''>u</span> <span m=''842520''>is</span> <span m=''842730''>given.</span>
  <span m=''845910''>On</span> <span m=''846650''>this</span> <span m=''846860''>part.</span>
  <span m=''848150''>So</span> <span m=''848460''>on</span> <span m=''848660''>part</span>
  <span m=''848980''>of</span> <span m=''849060''>the</span> <span m=''849170''>boundary,</span>
  <span m=''849920''>or</span> <span m=''850100''>possibly</span> <span m=''850620''>all,</span>
  <span m=''851780''>I</span> <span m=''851940''>could</span> <span m=''852230''>be</span>
  <span m=''852430''>given</span> <span m=''853170''>u=u_0.</span> <span m=''855120''>It</span>
  <span m=''855620''>could</span> <span m=''855800''>be</span> <span m=''855960''>zero,</span>
  <span m=''857720''>as</span> <span m=''857960''>it</span> <span m=''858440''>often</span>
  <span m=''858820''>was</span> <span m=''859120''>in</span> <span m=''859270''>1-D.</span>
  <span m=''860590''>Often</span> <span m=''860950''>just</span> <span m=''861160''>took</span>
  <span m=''861370''>u</span> <span m=''861560''>to</span> <span m=''861670''>be</span>
  <span m=''861840''>zero.</span> <span m=''862660''>Now,</span> <span m=''863340''>what</span>
  <span m=''863590''>I''m</span> <span m=''863780''>asking</span> <span m=''865080''>maybe</span>
  <span m=''865430''>for</span> <span m=''865580''>the</span> <span m=''865710''>first</span>
  <span m=''865990''>time,</span> <span m=''866290''>is</span> <span m=''866780''>what''s</span>
  <span m=''867310''>the</span> <span m=''867460''>free</span> <span m=''867870''>boundary</span>
  <span m=''868340''>conditions?</span> <span m=''870060''>Do</span> <span m=''870200''>we</span>
  <span m=''870360''>prescribe</span> <span m=''871100''>w=0</span> <span m=''873270''>on</span>
  <span m=''873520''>the</span> <span m=''873630''>free</span> <span m=''873870''>part</span>
  <span m=''874160''>of</span> <span m=''874230''>the</span> <span m=''874310''>boundary?</span>
  <span m=''875200''>Is</span> <span m=''875480''>w=0</span> <span m=''876740''>the</span>
  <span m=''876970''>correct</span> <span m=''877470''>free</span> <span m=''878380''>condition?</span>
  <span m=''878880''>Or</span> <span m=''879030''>w=w_0?</span> <span m=''881480''>If</span>
  <span m=''881670''>we</span> <span m=''881810''>wanted</span> <span m=''882180''>to</span>
  <span m=''882320''>allow</span> <span m=''882750''>it</span> <span m=''882870''>to
  be</span> <span m=''883010''>non-zero.</span> <span m=''885230''>That</span> <span
  m=''885430''>would</span> <span m=''885650''>sound</span> <span m=''886790''>right,</span>
  <span m=''887710''>right? u</span> <span m=''887970''>on</span> <span m=''888170''>one</span>
  <span m=''888370''>side,</span> <span m=''888810''>w</span> <span m=''889260''>on</span>
  <span m=''889440''>the</span> <span m=''889540''>other.</span> <span m=''889830''>But</span>
  <span m=''890080''>now</span> <span m=''890320''>we''re</span> <span m=''890530''>in</span>
  <span m=''890980''>2-D.</span> <span m=''892350''>u</span> <span m=''892610''>is</span>
  <span m=''892790''>still</span> <span m=''893040''>a</span> <span m=''893150''>scalar.</span>
  <span m=''894120''>That''s</span> <span m=''894450''>fine.</span> <span m=''895430''>But</span>
  <span m=''895620''>w</span> <span m=''896050''>is</span> <span m=''896210''>now</span>
  <span m=''896460''>a</span> <span m=''896550''>vector.</span> <span m=''897580''>So</span>
  <span m=''897780''>if</span> <span m=''897930''>I</span> <span m=''898130''>was</span>
  <span m=''898340''>to</span> <span m=''898450''>prescribe</span> <span m=''899010''>w</span>
  <span m=''899760''>on</span> <span m=''900050''>this</span> <span m=''900300''>part</span>
  <span m=''900530''>of</span> <span m=''900590''>the</span> <span m=''900690''>boundary,</span>
  <span m=''901840''>I''m</span> <span m=''902130''>giving</span> <span m=''902450''>you</span>
  <span m=''902640''>two</span> <span m=''903300''>conditions,</span> <span m=''903930''>not</span>
  <span m=''904200''>one.</span> <span m=''904550''>And</span> <span m=''904700''>that''s</span>
  <span m=''905390''>not</span> <span m=''905650''>good.</span> <span m=''906630''>I</span>
  <span m=''906780''>can''t</span> <span m=''907140''>give</span> <span m=''907320''>you</span>
  <span m=''907400''>more</span> <span m=''907650''>than</span> <span m=''907870''>one</span>
  <span m=''908160''>boundary</span> <span m=''908570''>condition.</span> <span m=''909050''>And</span>
  <span m=''909280''>the</span> <span m=''909430''>clue</span> <span m=''909870''>is</span>
  <span m=''910110''>there.</span> <span m=''911380''>It''s</span> <span m=''911680''>w</span>
  <span m=''912350''>dot</span> <span m=''912770''>n,</span> <span m=''913200''>it''s</span>
  <span m=''914770''>the</span> <span m=''915040''>outward</span> <span m=''915530''>flow.</span>
  <span m=''916340''>That</span> <span m=''917130''>you</span> <span m=''917360''>could</span>
  <span m=''917540''>prescribe.</span> <span m=''918340''>You</span> <span m=''918580''>can''t</span>
  <span m=''920530''>say in</span> <span m=''920960''>advance</span> <span m=''921640''>what</span>
  <span m=''921940''>the</span> <span m=''922470''>tangential</span> <span m=''923170''>flow</span>
  <span m=''923470''>should</span> <span m=''923750''>be.</span> <span m=''924200''>So</span>
  <span m=''924460''>the</span> <span m=''924610''>free</span> <span m=''925080''>conditions</span>
  <span m=''925680''>would</span> <span m=''925870''>be</span> <span m=''926080''>like</span>
  <span m=''926730''>w</span> <span m=''927480''>dot</span> <span m=''927820''>n,</span>
  <span m=''930150''>which</span> <span m=''930470''>is</span> <span m=''930780''>of</span>
  <span m=''930910''>course,</span> <span m=''934300''>since</span> <span m=''934670''>w</span>
  <span m=''935140''>is</span> <span m=''935350''>v,</span> <span m=''935810''>we</span>
  <span m=''935960''>have</span> <span m=''936100''>Laplace''s</span> <span m=''936760''>equation</span>
  <span m=''937290''>here</span> <span m=''937610''>with</span> <span m=''937900''>c=1</span>
  <span m=''940300''>in</span> <span m=''940490''>between</span> <span m=''940990''>w</span>
  <span m=''941430''>and</span> <span m=''941600''>v,</span> <span m=''942210''>so</span>
  <span m=''942410''>this</span> <span m=''942660''>is</span> <span m=''942870''>the</span>
  <span m=''943000''>gradient</span> <span m=''943420''>of</span> <span m=''943730''>u</span>
  <span m=''946020''>dot</span> <span m=''946590''>n,</span> <span m=''947630''>grad</span>
  <span m=''948010''>u</span> <span m=''948310''>dot</span> <span m=''948620''>n,</span>
  <span m=''949240''>and</span> <span m=''949500''>it''s</span> <span m=''949610''>sometimes</span>
  <span m=''950240''>written,</span> <span m=''950890''>the</span> <span m=''951110''>derivative</span>
  <span m=''951190''>of</span> <span m=''951680''>u</span> <span m=''952490''>in</span>
  <span m=''952700''>the</span> <span m=''952830''>normal</span> <span m=''953450''>direction.</span>
  <span m=''954960''>And</span> <span m=''955590''>that</span> <span m=''955930''>we</span>
  <span m=''956110''>can</span> <span m=''956360''>prescribe</span> <span m=''957060''>as</span>
  <span m=''957260''>some</span> <span m=''958170''>w_0.</span> <span m=''959880''>Oh,</span>
  <span m=''960110''>I</span> <span m=''961000''>don''t</span> <span m=''961210''>like
  to</span> <span m=''961370''>say</span> <span m=''961640''>w_0</span> <span m=''962350''>because</span>
  <span m=''962540''>w_0</span> <span m=''964920''>makes</span> <span m=''965150''>it</span>
  <span m=''965300''>sound</span> <span m=''965570''>like</span> <span m=''965760''>a</span>
  <span m=''965900''>vector</span> <span m=''965970''>would</span> <span m=''967950''>be</span>
  <span m=''968040''>allowed,</span> <span m=''968490''>and</span> <span m=''968640''>that''s</span>
  <span m=''968890''>the</span> <span m=''968990''>whole</span> <span m=''969210''>point</span>
  <span m=''969600''>here.</span> <span m=''970420''>We</span> <span m=''970860''>give</span>
  <span m=''971080''>one</span> <span m=''971660''>boundary</span> <span m=''972080''>condition;</span>
  <span m=''972540''>we</span> <span m=''972680''>either</span> <span m=''972940''>give</span>
  <span m=''973210''>u</span> <span m=''973920''>or</span> <span m=''974280''>w</span>
  <span m=''974730''>dot</span> <span m=''975060''>n.</span> <span m=''975640''>So</span>
  <span m=''975870''>let</span> <span m=''976090''>me</span> <span m=''976660''>give</span>
  <span m=''976880''>it</span> <span m=''976990''>some</span> <span m=''977200''>different</span>
  <span m=''977590''>name,</span> <span m=''977830''>like</span> <span m=''978110''>F.</span>
  </p><p><span m=''986920''>So.</span> <span m=''987160''>I''ll just</span> <span
  m=''987430''>ask</span> <span m=''987640''>one</span> <span m=''987900''>more</span>
  <span m=''988080''>question</span> <span m=''988530''>to</span> <span m=''990060''>bring</span>
  <span m=''990350''>this</span> <span m=''990570''>home.</span> <span m=''990940''>And</span>
  <span m=''991070''>then</span> <span m=''991230''>I''ll</span> <span m=''991350''>get</span>
  <span m=''991570''>on to</span> <span m=''991980''>the</span> <span m=''992830''>fun</span>
  <span m=''993210''>today</span> <span m=''993670''>of</span> <span m=''993800''>fast</span>
  <span m=''994210''>Poisson</span> <span m=''994400''>solvers.</span> <span m=''998670''>What</span>
  <span m=''998900''>was</span> <span m=''999160''>the</span> <span m=''999290''>deal</span>
  <span m=''1000030''>on</span> <span m=''1000420''>in</span> <span m=''1000600''>1-D</span>
  <span m=''1002180''>when</span> <span m=''1002610''>we</span> <span m=''1002880''>had</span>
  <span m=''1003300''>free-free</span> <span m=''1004770''>boundary</span> <span m=''1005270''>conditions?</span>
  <span m=''1006650''>What</span> <span m=''1006900''>was</span> <span m=''1007080''>the</span>
  <span m=''1007180''>deal</span> <span m=''1007530''>in</span> <span m=''1007670''>one</span>
  <span m=''1008000''>dimension</span> <span m=''1009010''>when</span> <span m=''1009270''>we</span>
  <span m=''1009430''>had</span> <span m=''1009720''>free-free</span> <span m=''1010690''>boundary</span>
  <span m=''1011180''>conditions?</span> <span m=''1011720''>Both</span> <span m=''1012710''>conditions</span>
  <span m=''1013300''>were</span> <span m=''1013470''>slope</span> <span m=''1013960''>conditions.</span>
  <span m=''1015270''>u''=0.</span> <span m=''1017700''>What</span> <span m=''1018720''>matrix</span>
  <span m=''1019330''>did</span> <span m=''1019520''>we</span> <span m=''1019690''>get?</span>
  <span m=''1020270''>What</span> <span m=''1021560''>was</span> <span m=''1021750''>different</span>
  <span m=''1022190''>about</span> <span m=''1022500''>that</span> <span m=''1022750''>matrix,</span>
  <span m=''1023550''>the</span> <span m=''1023680''>free-free</span> <span m=''1024460''>case?</span>
  <span m=''1025480''>I''m</span> <span m=''1025630''>always</span> <span m=''1025960''>looking</span>
  <span m=''1026260''>back</span> <span m=''1026520''>to</span> <span m=''1026630''>1-D</span>
  <span m=''1027290''>because</span> <span m=''1027480''>that''s</span> <span m=''1027730''>the</span>
  <span m=''1027860''>case</span> <span m=''1028190''>we</span> <span m=''1028360''>really</span>
  <span m=''1028710''>understood.</span> <span m=''1030410''>What</span> <span m=''1030650''>was</span>
  <span m=''1030810''>the</span> <span m=''1031370''>the</span> <span m=''1031460''>problem</span>
  <span m=''1031950''>with</span> <span m=''1032180''>the</span> <span m=''1032310''>free-free</span>
  <span m=''1032990''>matrix?</span> <span m=''1035440''>It</span> <span m=''1035620''>was</span>
  <span m=''1035790''>singular.</span> <span m=''1036580''>What</span> <span m=''1036780''>was</span>
  <span m=''1036990''>its</span> <span m=''1037190''>name?</span> <span m=''1039400''>Was</span>
  <span m=''1039840''>K,</span> <span m=''1040480''>was</span> <span m=''1040780''>it?</span>
  <span m=''1041640''>You</span> <span m=''1041750''>remember</span> <span m=''1042100''>the</span>
  <span m=''1042630''>first</span> <span m=''1043080''>day</span> <span m=''1043280''>of</span>
  <span m=''1043410''>class,</span> <span m=''1045040''>the</span> <span m=''1045430''>unforgettable</span>
  <span m=''1047100''>four</span> <span m=''1047520''>matrices?</span> <span m=''1050490''>So</span>
  <span m=''1050750''>this</span> <span m=''1051060''>was</span> <span m=''1051770''>fixed-fixed,</span>
  <span m=''1052020''>fixed-fixed.</span> <span m=''1054150''>This</span> <span m=''1056850''>one</span>
  <span m=''1057100''>was,</span> <span m=''1058290''>you</span> <span m=''1058550''>could</span>
  <span m=''1058720''>tell</span> <span m=''1058910''>me</span> <span m=''1059070''>better</span>
  <span m=''1059360''>than</span> <span m=''1060040''>I</span> <span m=''1060200''>can</span>
  <span m=''1060360''>remember.</span> <span m=''1061000''>T</span> <span m=''1061330''>was</span>
  <span m=''1062530''>free-fixed.</span> <span m=''1063430''>And</span> <span m=''1063630''>that</span>
  <span m=''1063810''>was</span> <span m=''1064040''>still</span> <span m=''1064270''>OK.</span>
  <span m=''1065360''>By</span> <span m=''1065580''>OK</span> <span m=''1065990''>I</span>
  <span m=''1066090''>mean</span> <span m=''1066250''>it</span> <span m=''1066340''>was</span>
  <span m=''1066510''>still</span> <span m=''1066830''>invertible.</span> <span m=''1067510''>What</span>
  <span m=''1067740''>was</span> <span m=''1067930''>B?</span> <span m=''1069660''>Free-free,</span>
  <span m=''1070380''>that''s</span> <span m=''1070700''>what</span> <span m=''1070890''>I''m</span>
  <span m=''1071010''>looking</span> <span m=''1071350''>at.</span> <span m=''1071700''>And</span>
  <span m=''1071950''>the</span> <span m=''1072030''>problem</span> <span m=''1072600''>with</span>
  <span m=''1072820''>free-free--</span> <span m=''1073850''>And</span> <span m=''1074110''>then</span>
  <span m=''1074300''>this</span> <span m=''1074480''>was</span> <span m=''1074730''>periodic,</span>
  <span m=''1075320''>that''s</span> <span m=''1077960''>Fourier</span> <span m=''1078420''>stuff</span>
  <span m=''1078860''>that''s</span> <span m=''1079290''>the</span> <span m=''1079420''>next</span>
  <span m=''1080110''>part</span> <span m=''1080380''>of</span> <span m=''1080520''>the</span>
  <span m=''1080590''>course.</span> <span m=''1081390''>But</span> <span m=''1081650''>the</span>
  <span m=''1081800''>point</span> <span m=''1082160''>is</span> <span m=''1082460''>that</span>
  <span m=''1082570''>this</span> <span m=''1082880''>free-free</span> <span m=''1083600''>was</span>
  <span m=''1083820''>singular.</span> <span m=''1088250''>Right?</span> <span m=''1089320''>And</span>
  <span m=''1089670''>it''ll</span> <span m=''1089890''>be</span> <span m=''1090020''>the</span>
  <span m=''1090160''>same</span> <span m=''1090460''>here.</span> <span m=''1091420''>If</span>
  <span m=''1091670''>the</span> <span m=''1091800''>whole</span> <span m=''1092210''>boundary</span>
  <span m=''1092960''>is</span> <span m=''1093890''>free,</span> <span m=''1095630''>then</span>
  <span m=''1095820''>I''ve</span> <span m=''1095910''>got</span> <span m=''1096080''>a</span>
  <span m=''1096170''>singular</span> <span m=''1096710''>problem.</span> <span m=''1098180''>If</span>
  <span m=''1099090''>I''ve</span> <span m=''1099200''>got</span> <span m=''1099360''>a</span>
  <span m=''1099410''>whole</span> <span m=''1099670''>boundary</span> <span m=''1100110''>that''s</span>
  <span m=''1100320''>free,</span> <span m=''1100920''>yeah</span> <span m=''1101380''>actually</span>
  <span m=''1102330''>I''ll</span> <span m=''1102510''>just</span> <span m=''1102790''>put</span>
  <span m=''1103180''>it</span> <span m=''1103290''>here.</span> <span m=''1103790''>Suppose</span>
  <span m=''1104550''>I</span> <span m=''1105800''>have</span> <span m=''1106200''>Laplace''s</span>
  <span m=''1106850''>equation,</span> <span m=''1112900''>zero,</span> <span m=''1114000''>and</span>
  <span m=''1114190''>suppose</span> <span m=''1114660''>I</span> <span m=''1114780''>make</span>
  <span m=''1115040''>the</span> <span m=''1115130''>whole</span> <span m=''1115870''>all</span>
  <span m=''1116190''>free.</span> <span m=''1121280''>So</span> <span m=''1121590''>grad</span>
  <span m=''1122160''>u</span> <span m=''1124630''>dot</span> <span m=''1125000''>n</span>
  <span m=''1125500''>is</span> <span m=''1125800''>zero</span> <span m=''1126160''>on</span>
  <span m=''1126270''>the</span> <span m=''1126350''>whole</span> <span m=''1126570''>boundary.</span>
  <span m=''1127850''>So</span> <span m=''1128860''>it''s</span> <span m=''1129060''>like</span>
  <span m=''1129320''>solving</span> <span m=''1131010''>Bu=0.</span> <span m=''1135510''>And</span>
  <span m=''1135850''>the</span> <span m=''1135920''>point</span> <span m=''1136270''>is</span>
  <span m=''1136470''>that</span> <span m=''1136640''>that</span> <span m=''1136830''>has</span>
  <span m=''1137140''>solutions.</span> <span m=''1138360''>You</span> <span m=''1138550''>remember,</span>
  <span m=''1138870''>what</span> <span m=''1139330''>was</span> <span m=''1139560''>in</span>
  <span m=''1140450''>the</span> <span m=''1140550''>null</span> <span m=''1140890''>space</span>
  <span m=''1141320''>of</span> <span m=''1141480''>B,</span> <span m=''1141880''>this</span>
  <span m=''1142140''>free-free</span> <span m=''1142940''>case?</span> <span m=''1144020''>Bu=0,</span>
  <span m=''1145440''>for</span> <span m=''1146100''>what</span> <span m=''1146430''>vector?</span>
  <span m=''1148240''>Our</span> <span m=''1148490''>favorite</span> <span m=''1150170''>guilty</span>
  <span m=''1150560''>vector.</span> <span m=''1152490''>It</span> <span m=''1152670''>was</span>
  <span m=''1154530''>constants.</span> <span m=''1155160''>Right,</span> <span m=''1155500''>all</span>
  <span m=''1155750''>ones.</span> <span m=''1156280''>All</span> <span m=''1156530''>constants.</span>
  <span m=''1157620''>u=1,</span> <span m=''1158530''>all</span> <span m=''1158820''>constants.</span>
  <span m=''1160000''>Right,</span> <span m=''1160430''>so</span> <span m=''1160590''>that</span>
  <span m=''1160810''>was</span> <span m=''1160980''>the</span> <span m=''1161110''>free-free</span>
  <span m=''1161700''>case</span> <span m=''1162030''>in</span> <span m=''1162170''>1-D.</span>
  <span m=''1163070''>Now,</span> <span m=''1163450''>I</span> <span m=''1163530''>just</span>
  <span m=''1163800''>want you</span> <span m=''1164190''>to</span> <span m=''1164330''>tell</span>
  <span m=''1164550''>me</span> <span m=''1164710''>the</span> <span m=''1164870''>same</span>
  <span m=''1165370''>thing</span> <span m=''1165700''>over</span> <span m=''1165940''>here.</span>
  </p><p><span m=''1168560''>That</span> <span m=''1168850''>equation</span> <span
  m=''1169490''>does</span> <span m=''1169740''>not</span> <span m=''1170090''>have</span>
  <span m=''1170860''>a</span> <span m=''1170970''>unique</span> <span m=''1171420''>solution.</span>
  <span m=''1172040''>So</span> <span m=''1172540''>it''s</span> <span m=''1172710''>a</span>
  <span m=''1172800''>singular</span> <span m=''1173350''>problem.</span> <span m=''1174130''>Here''s</span>
  <span m=''1174550''>the</span> <span m=''1174710''>equation,</span> <span m=''1175960''>something</span>
  <span m=''1176680''>u</span> <span m=''1177030''>equals</span> <span m=''1177400''>zero,</span>
  <span m=''1178490''>but</span> <span m=''1178680''>you</span> <span m=''1178820''>can</span>
  <span m=''1179000''>tell</span> <span m=''1179270''>me</span> <span m=''1179440''>solutions</span>
  <span m=''1180200''>to</span> <span m=''1180370''>that</span> <span m=''1182390''>pure</span>
  <span m=''1182870''>Neumann</span> <span m=''1183540''>problem.</span> <span m=''1184990''>That</span>
  <span m=''1185250''>are</span> <span m=''1185350''>not</span> <span m=''1185610''>zero.</span>
  <span m=''1186970''>So</span> <span m=''1187200''>this</span> <span m=''1187280''>is</span>
  <span m=''1187440''>a</span> <span m=''1189180''>problem</span> <span m=''1189830''>where</span>
  <span m=''1190560''>there''s</span> <span m=''1191050''>a null</span> <span m=''1191290''>space.</span>
  <span m=''1192140''>And</span> <span m=''1192370''>what</span> <span m=''1192600''>is</span>
  <span m=''1192800''>the</span> <span m=''1192930''>solution?</span> <span m=''1194480''>What''s</span>
  <span m=''1195120''>a</span> <span m=''1197460''>solution</span> <span m=''1198020''>to</span>
  <span m=''1198170''>this?</span> <span m=''1199460''>To</span> <span m=''1199630''>the</span>
  <span m=''1199710''>Laplace''s</span> <span m=''1200420''>equation</span> <span
  m=''1201000''>in</span> <span m=''1201150''>the</span> <span m=''1201240''>inside</span>
  <span m=''1202420''>and</span> <span m=''1203550''>slope</span> <span m=''1204470''>zero</span>
  <span m=''1207170''>all</span> <span m=''1207510''>around</span> <span m=''1207830''>the</span>
  <span m=''1207920''>boundary.</span> <span m=''1209390''>There''s</span> <span m=''1209650''>a</span>
  <span m=''1209790''>simple</span> <span m=''1210250''>solution</span> <span m=''1210790''>to</span>
  <span m=''1210900''>that</span> <span m=''1211160''>one,</span> <span m=''1212010''>which</span>
  <span m=''1212290''>is</span> <span m=''1212540''>just</span> <span m=''1212850''>like</span>
  <span m=''1214300''>this</span> <span m=''1214560''>guy.</span> <span m=''1216020''>And</span>
  <span m=''1216440''>do</span> <span m=''1216530''>you</span> <span m=''1216610''>see</span>
  <span m=''1216800''>what</span> <span m=''1216980''>it</span> <span m=''1217120''>is?</span>
  <span m=''1218630''>u</span> <span m=''1218860''>equal</span> <span m=''1219230''>constant,</span>
  <span m=''1219910''>right.</span> <span m=''1220240''>So</span> <span m=''1220520''>u</span>
  <span m=''1220830''>equal</span> <span m=''1221210''>constant.</span> <span m=''1225730''>So</span>
  <span m=''1227170''>I''d</span> <span m=''1227400''>like</span> <span m=''1227590''>you</span>
  <span m=''1227680''>to</span> <span m=''1227810''>see</span> <span m=''1228810''>the</span>
  <span m=''1229050''>whole</span> <span m=''1229350''>picture</span> <span m=''1229830''>connecting</span>
  <span m=''1230430''>with</span> <span m=''1230580''>what</span> <span m=''1230810''>we</span>
  <span m=''1231590''>fully</span> <span m=''1232050''>understood</span> <span m=''1232910''>in</span>
  <span m=''1233060''>the</span> <span m=''1233160''>1-D</span> <span m=''1233850''>case</span>
  <span m=''1234330''>for</span> <span m=''1235050''>those</span> <span m=''1235340''>matrices.</span>
  <span m=''1237090''>We</span> <span m=''1237410''>don''t</span> <span m=''1237780''>expect</span>
  <span m=''1238370''>to</span> <span m=''1238500''>be</span> <span m=''1238680''>able</span>
  <span m=''1239020''>to</span> <span m=''1240060''>have</span> <span m=''1240340''>a</span>
  <span m=''1240670''>pure</span> <span m=''1241610''>Neumann</span> <span m=''1242270''>problem.</span>
  <span m=''1243330''>A</span> <span m=''1243520''>totally</span> <span m=''1244140''>free</span>
  <span m=''1244660''>problem.</span> <span m=''1245670''>Because</span> <span m=''1246580''>these,</span>
  <span m=''1246910''>it''ll</span> <span m=''1247090''>be</span> <span m=''1247270''>singular</span>
  <span m=''1247860''>and</span> <span m=''1248000''>we''ll</span> <span m=''1248190''>have</span>
  <span m=''1248510''>to</span> <span m=''1250740''>do</span> <span m=''1250920''>something</span>
  <span m=''1251390''>special.</span> <span m=''1251970''>So</span> <span m=''1252700''>the</span>
  <span m=''1252890''>point</span> <span m=''1253240''>is</span> <span m=''1253470''>that</span>
  <span m=''1255410''>it</span> <span m=''1255590''>would</span> <span m=''1255740''>be</span>
  <span m=''1255860''>enough</span> <span m=''1256250''>for</span> <span m=''1256400''>me</span>
  <span m=''1256590''>just</span> <span m=''1256830''>to</span> <span m=''1256930''>fix</span>
  <span m=''1257310''>that</span> <span m=''1257530''>little</span> <span m=''1257770''>bit.</span>
  <span m=''1259280''>If</span> <span m=''1259450''>I</span> <span m=''1259550''>just</span>
  <span m=''1259830''>fix</span> <span m=''1260150''>that</span> <span m=''1260380''>little</span>
  <span m=''1260620''>bit</span> <span m=''1260860''>and</span> <span m=''1260980''>prescribe</span>
  <span m=''1261560''>u=u_0</span> <span m=''1262620''>on</span> <span m=''1262860''>a</span>
  <span m=''1262930''>little</span> <span m=''1263210''>bit,</span> <span m=''1263480''>I</span>
  <span m=''1263630''>could</span> <span m=''1263900''>make</span> <span m=''1264170''>the</span>
  <span m=''1264270''>rest</span> <span m=''1264560''>of</span> <span m=''1264660''>it</span>
  <span m=''1264810''>free.</span> <span m=''1267830''>But</span> <span m=''1268630''>I</span>
  <span m=''1268780''>can''t</span> <span m=''1269230''>make</span> <span m=''1269570''>it
  all</span> <span m=''1269800''>free.</span> <span m=''1271740''>OK.</span> <span
  m=''1272660''>So</span> <span m=''1273870''>those</span> <span m=''1274180''>are</span>
  <span m=''1274290''>things</span> <span m=''1274840''>which,</span> <span m=''1278600''>just</span>
  <span m=''1278870''>to</span> <span m=''1279030''>complete</span> <span m=''1279660''>the</span>
  <span m=''1280320''>big</span> <span m=''1280680''>picture</span> <span m=''1281680''>of</span>
  <span m=''1282170''>Laplace''s</span> <span m=''1282690''>equation.</span> <span
  m=''1286400''>OK,</span> <span m=''1287280''>now</span> <span m=''1287450''>I''m</span>
  <span m=''1287550''>going to</span> <span m=''1287770''>turn</span> <span m=''1288060''>to</span>
  <span m=''1288170''>solving.</span> <span m=''1289720''>So</span> <span m=''1289960''>now</span>
  <span m=''1290210''>I</span> <span m=''1290290''>want</span> <span m=''1290510''>to</span>
  <span m=''1290590''>solve</span> <span m=''1291030''>Laplace''s</span> <span m=''1291600''>equation</span>
  <span m=''1292000''>and</span> <span m=''1292230''>then</span> <span m=''1292400''>we''ll</span>
  <span m=''1292630''>have,</span> <span m=''1293410''>because</span> <span m=''1294030''>we</span>
  <span m=''1294170''>have</span> <span m=''1294440''>the</span> <span m=''1294530''>review</span>
  <span m=''1294940''>sessions</span> <span m=''1295590''>coming</span> <span m=''1296390''>on</span>
  <span m=''1297260''>Tuesday</span> <span m=''1297700''>and</span> <span m=''1297860''>Wednesday</span>
  <span m=''1298860''>of</span> <span m=''1299110''>the</span> <span m=''1299230''>past,</span>
  <span m=''1300240''>now</span> <span m=''1300600''>we''re</span> <span m=''1300770''>looking</span>
  <span m=''1302070''>future.</span> <span m=''1302630''>Forward.</span> <span m=''1303600''>Ready</span>
  <span m=''1304710''>to</span> <span m=''1304810''>look</span> <span m=''1305020''>forward.</span>
  <span m=''1306700''>Laplace''s</span> <span m=''1307330''>equation.</span> <span
  m=''1308370''>On</span> <span m=''1308580''>a</span> <span m=''1308690''>square.</span>
  <span m=''1310170''>On a square.</span> <span m=''1312460''>OK.</span> </p><p><span
  m=''1313090''>So</span> <span m=''1313280''>let</span> <span m=''1313370''>me</span>
  <span m=''1313480''>draw</span> <span m=''1313750''>this</span> <span m=''1313900''>square.</span>
  <span m=''1317200''>Laplace''s</span> <span m=''1317680''>equation</span> <span
  m=''1318160''>or</span> <span m=''1318340''>Poisson''s</span> <span m=''1318670''>equation.</span>
  <span m=''1322330''>In</span> <span m=''1322560''>a</span> <span m=''1322650''>square.</span>
  <span m=''1323560''>OK,</span> <span m=''1324140''>I''m</span> <span m=''1324540''>going</span>
  <span m=''1324750''>to</span> <span m=''1324840''>make</span> <span m=''1325180''>it</span>
  <span m=''1325500''>the</span> <span m=''1325710''>boundary</span> <span m=''1326110''>conditions--</span>
  <span m=''1326900''>So</span> <span m=''1327080''>I''m</span> <span m=''1327230''>going
  to</span> <span m=''1327440''>have</span> <span m=''1327570''>a</span> <span m=''1327650''>mesh.</span>
  <span m=''1328230''>This</span> <span m=''1328390''>is</span> <span m=''1328490''>going
  to</span> <span m=''1328670''>be</span> <span m=''1328790''>finite</span> <span
  m=''1329190''>differences.</span> <span m=''1331790''>Finite</span> <span m=''1332110''>differences</span>
  <span m=''1332630''>will</span> <span m=''1332750''>do</span> <span m=''1332920''>fine</span>
  <span m=''1333370''>on</span> <span m=''1333590''>a</span> <span m=''1333720''>square.</span>
  <span m=''1335390''>As</span> <span m=''1335550''>soon</span> <span m=''1335750''>as</span>
  <span m=''1335870''>I</span> <span m=''1335990''>draw</span> <span m=''1337480''>this</span>
  <span m=''1337750''>curved</span> <span m=''1338250''>region,</span> <span m=''1340180''>I</span>
  <span m=''1340370''>better</span> <span m=''1340670''>be</span> <span m=''1340830''>thinking</span>
  <span m=''1341150''>about</span> <span m=''1341420''>finite</span> <span m=''1341870''>elements.</span>
  <span m=''1342980''>So</span> <span m=''1343110''>that''s</span> <span m=''1343410''>what,</span>
  <span m=''1344680''>today</span> <span m=''1345380''>is</span> <span m=''1345720''>the,</span>
  <span m=''1346010''>like,</span> <span m=''1346290''>square</span> <span m=''1346750''>day.</span>
  <span m=''1347850''>OK,</span> <span m=''1348700''>so</span> <span m=''1349160''>square</span>
  <span m=''1349590''>day</span> <span m=''1349910''>I</span> <span m=''1350090''>could</span>
  <span m=''1350330''>think</span> <span m=''1350590''>of</span> <span m=''1350710''>finite</span>
  <span m=''1351100''>differences.</span> <span m=''1352250''>I</span> <span m=''1352500''>just</span>
  <span m=''1352960''>draw</span> <span m=''1353770''>a</span> <span m=''1354500''>mesh,</span>
  <span m=''1355610''>let''s</span> <span m=''1355840''>make</span> <span m=''1356090''>it</span>
  <span m=''1356550''>small.</span> <span m=''1360270''>So</span> <span m=''1360540''>this</span>
  <span m=''1360800''>is</span> <span m=''1360950''>all</span> <span m=''1361240''>known.</span>
  <span m=''1361790''>These</span> <span m=''1362060''>are</span> <span m=''1362180''>all</span>
  <span m=''1362380''>known</span> <span m=''1362850''>values,</span> <span m=''1363670''>let</span>
  <span m=''1363820''>me</span> <span m=''1363940''>just</span> <span m=''1364230''>say</span>
  <span m=''1364420''>u</span> <span m=''1364780''>is</span> <span m=''1365060''>given.</span>
  <span m=''1367620''>On</span> <span m=''1367840''>the boundary.</span> <span m=''1368420''>I''ll</span>
  <span m=''1368870''>do</span> <span m=''1369120''>the</span> <span m=''1370070''>Dirichlet</span>
  <span m=''1370280''>problem.</span> <span m=''1374230''>So</span> <span m=''1374410''>at</span>
  <span m=''1374630''>all these</span> <span m=''1375550''>mesh</span> <span m=''1375880''>points,</span>
  <span m=''1376630''>I</span> <span m=''1378060''>know</span> <span m=''1378380''>u.</span>
  <span m=''1379600''>And</span> <span m=''1379840''>I</span> <span m=''1379920''>want
  to</span> <span m=''1380240''>find</span> <span m=''1380610''>u</span> <span m=''1380930''>inside.</span>
  <span m=''1384660''>So</span> <span m=''1384790''>I''ve</span> <span m=''1384880''>got</span>
  <span m=''1385060''>nine</span> <span m=''1385390''>unknowns,</span> <span m=''1386500''>right?</span>
  <span m=''1386850''>Nine</span> <span m=''1387340''>interior</span> <span m=''1387850''>mesh</span>
  <span m=''1388160''>points.</span> <span m=''1388690''>Three</span> <span m=''1389170''>times</span>
  <span m=''1389520''>three</span> <span m=''1389810''>three.</span> <span m=''1391230''>So</span>
  <span m=''1391440''>I''ve</span> <span m=''1391560''>got</span> <span m=''1391730''>nine</span>
  <span m=''1392190''>unknowns,</span> <span m=''1392780''>I</span> <span m=''1392910''>want</span>
  <span m=''1393070''>nine</span> <span m=''1393460''>equations</span> <span m=''1394230''>and</span>
  <span m=''1394350''>I''m</span> <span m=''1394550''>thinking</span> <span m=''1395190''>here</span>
  <span m=''1395420''>about</span> <span m=''1395930''>difference</span> <span m=''1396380''>equations.</span>
  <span m=''1397300''>So</span> <span m=''1397480''>let</span> <span m=''1397670''>me</span>
  <span m=''1397790''>write</span> <span m=''1398100''>my</span> <span m=''1398280''>equation</span>
  <span m=''1401440''>-u_xx-u_yy=f.</span> <span m=''1410690''>Poisson.</span> <span
  m=''1415340''>What</span> <span m=''1415780''>finite</span> <span m=''1416370''>difference--</span>
  <span m=''1417570''>I</span> <span m=''1417670''>want to</span> <span m=''1417930''>turn</span>
  <span m=''1418220''>this</span> <span m=''1418430''>into</span> <span m=''1418660''>finite</span>
  <span m=''1419000''>differences.</span> <span m=''1420710''>That''ll</span> <span
  m=''1421080''>be</span> <span m=''1421510''>my</span> <span m=''1422800''>system</span>
  <span m=''1423450''>of</span> <span m=''1424700''>nine</span> <span m=''1425120''>equations.</span>
  <span m=''1427320''>And</span> <span m=''1427820''>the</span> <span m=''1427960''>unknowns</span>
  <span m=''1428540''>will</span> <span m=''1428700''>be</span> <span m=''1428910''>the</span>
  <span m=''1429080''>nine</span> <span m=''1429610''>values</span> <span m=''1430180''>of
  u, so</span> <span m=''1430880''>these</span> <span m=''1431150''>are</span> <span
  m=''1431320''>unknown.</span> <span m=''1432840''>Right?</span> <span m=''1433440''>Those</span>
  <span m=''1433730''>are</span> <span m=''1433840''>the</span> <span m=''1433960''>unknown.</span>
  <span m=''1436080''>OK,</span> <span m=''1436700''>and</span> <span m=''1437090''>I</span>
  <span m=''1437160''>need</span> <span m=''1437490''>equations.</span> <span m=''1438990''>So</span>
  <span m=''1439160''>let</span> <span m=''1439310''>me</span> <span m=''1439430''>take</span>
  <span m=''1439670''>a</span> <span m=''1439770''>typical</span> <span m=''1440220''>mesh</span>
  <span m=''1440510''>point,</span> <span m=''1440820''>like</span> <span m=''1441020''>this</span>
  <span m=''1441310''>one.</span> <span m=''1444690''>I''m</span> <span m=''1444850''>looking</span>
  <span m=''1445410''>for</span> <span m=''1445630''>the</span> <span m=''1445780''>finite</span>
  <span m=''1446270''>difference</span> <span m=''1446690''>approximation</span> <span
  m=''1447690''>to</span> <span m=''1447840''>the</span> <span m=''1447980''>Laplacian.</span>
  <span m=''1449590''>If</span> <span m=''1449790''>you</span> <span m=''1449940''>give</span>
  <span m=''1450140''>me</span> <span m=''1450280''>Laplace''s</span> <span m=''1450920''>equation</span>
  <span m=''1451520''>and</span> <span m=''1451700''>I</span> <span m=''1451830''>say</span>
  <span m=''1452140''>OK,</span> <span m=''1453880''>what''s</span> <span m=''1454140''>a</span>
  <span m=''1454210''>good</span> <span m=''1454450''>finite</span> <span m=''1454820''>difference</span>
  <span m=''1455400''>approximation,</span> <span m=''1457270''>that</span> <span
  m=''1457720''>I</span> <span m=''1457810''>can</span> <span m=''1458000''>then</span>
  <span m=''1458490''>put</span> <span m=''1458700''>in</span> <span m=''1458850''>the</span>
  <span m=''1458960''>computer</span> <span m=''1459490''>and</span> <span m=''1459640''>solve.</span>
  <span m=''1460880''>I''m</span> <span m=''1461050''>ready</span> <span m=''1461320''>to</span>
  <span m=''1461460''>do</span> <span m=''1461610''>it.</span> <span m=''1462180''>So</span>
  <span m=''1462570''>what</span> <span m=''1462850''>should</span> <span m=''1463080''>we
  do</span> <span m=''1463580''>for</span> <span m=''1464510''>this</span> <span m=''1464790''>one?</span>
  <span m=''1465650''>For</span> <span m=''1465780''>that</span> <span m=''1466070''>term?</span>
  <span m=''1467050''>What''s</span> <span m=''1467390''>the</span> <span m=''1467530''>natural,</span>
  <span m=''1468160''>totally</span> <span m=''1468650''>natural</span> <span m=''1469170''>thing</span>
  <span m=''1469480''>to</span> <span m=''1469630''>do</span> <span m=''1471380''>to</span>
  <span m=''1471600''>replace--</span> <span m=''1472190''>the</span> <span m=''1472320''>finite</span>
  <span m=''1472660''>difference</span> <span m=''1473080''>replacement</span> <span
  m=''1473800''>of</span> <span m=''1473940''>minus</span> <span m=''1474360''>u_xx?</span>
  <span m=''1476040''>Second</span> <span m=''1476540''>differences.</span> <span
  m=''1477490''>Second</span> <span m=''1477990''>differences.</span> <span m=''1478900''>And</span>
  <span m=''1479150''>with</span> <span m=''1479310''>the</span> <span m=''1479410''>minus</span>
  <span m=''1479930''>sign</span> <span m=''1480270''>there,</span> <span m=''1482340''>second</span>
  <span m=''1482690''>differences</span> <span m=''1483150''>around</span> <span m=''1483570''>this</span>
  <span m=''1483780''>point</span> <span m=''1484320''>will be a</span> <span m=''1484550''>minus</span>
  <span m=''1485090''>one</span> <span m=''1485370''>of</span> <span m=''1485490''>there,</span>
  <span m=''1486450''>two of</span> <span m=''1486680''>those,</span> <span m=''1487480''>a</span>
  <span m=''1487540''>minus</span> <span m=''1487960''>one</span> <span m=''1488250''>of</span>
  <span m=''1488360''>those.</span> <span m=''1489490''>That</span> <span m=''1489830''>second</span>
  <span m=''1490350''>difference</span> <span m=''1490830''>in</span> <span m=''1490960''>the
  x</span> <span m=''1491370''>direction</span> <span m=''1492370''>is</span> <span
  m=''1494260''>my</span> <span m=''1495570''>replacement.</span> <span m=''1496540''>My</span>
  <span m=''1496710''>approximation.</span> <span m=''1497900''>And</span> <span m=''1498110''>what</span>
  <span m=''1498300''>about</span> <span m=''1498610''>in</span> <span m=''1498730''>the</span>
  <span m=''1498810''>y</span> <span m=''1499110''>direction?</span> <span m=''1501460''>Same</span>
  <span m=''1501910''>thing.</span> <span m=''1502600''>Second</span> <span m=''1503090''>differences,</span>
  <span m=''1503690''>but</span> <span m=''1503860''>now</span> <span m=''1504110''>vertically.</span>
  <span m=''1505130''>So</span> <span m=''1505270''>now</span> <span m=''1505520''>I</span>
  <span m=''1505610''>have</span> <span m=''1505850''>minus</span> <span m=''1506280''>one,</span>
  <span m=''1507060''>two</span> <span m=''1507300''>more,</span> <span m=''1507900''>that</span>
  <span m=''1508090''>makes</span> <span m=''1508380''>this</span> <span m=''1508580''>guy</span>
  <span m=''1508820''>a</span> <span m=''1508900''>four.</span> <span m=''1510080''>And</span>
  <span m=''1510420''>this</span> <span m=''1510620''>is</span> <span m=''1510780''>minus</span>
  <span m=''1511370''>one.</span> <span m=''1512810''>And</span> <span m=''1513350''>on</span>
  <span m=''1513590''>the</span> <span m=''1513680''>right</span> <span m=''1513900''>hand</span>
  <span m=''1514140''>side,</span> <span m=''1514410''>I''ll</span> <span m=''1514540''>take</span>
  <span m=''1514780''>the</span> <span m=''1514880''>value</span> <span m=''1515280''>of</span>
  <span m=''1515420''>f</span> <span m=''1515800''>at the</span> <span m=''1516370''>center</span>
  <span m=''1516720''>point.</span> <span m=''1518330''>Do</span> <span m=''1518430''>you</span>
  <span m=''1518550''>see</span> <span m=''1519130''>that</span> <span m=''1519410''>molecule?</span>
  <span m=''1522360''>Let</span> <span m=''1522550''>me</span> <span m=''1523800''>highlight</span>
  <span m=''1524430''>the</span> <span m=''1524500''>molecule</span> <span m=''1525170''>there.</span>
  <span m=''1526650''>Four in the</span> <span m=''1527290''>center,</span> <span
  m=''1528150''>minus</span> <span m=''1528660''>ones</span> <span m=''1529560''>beside</span>
  <span m=''1530150''>it.</span> <span m=''1530770''>Our</span> <span m=''1530980''>matrix,</span>
  <span m=''1531850''>we''re</span> <span m=''1532700''>going to</span> <span m=''1533230''>produce</span>
  <span m=''1533770''>a</span> <span m=''1534050''>KU=f</span> <span m=''1535760''>matrix,</span>
  <span m=''1537740''>and</span> <span m=''1537970''>what''s</span> <span m=''1538290''>the</span>
  <span m=''1538420''>K</span> <span m=''1538860''>going</span> <span m=''1539050''>to</span>
  <span m=''1539140''>be?</span> <span m=''1539360''>It''s</span> <span m=''1539780''>K2D.</span>
  <span m=''1540400''>Let''s</span> <span m=''1540900''>give a</span> <span m=''1541220''>name.</span>
  <span m=''1541940''>A</span> <span m=''1542050''>new</span> <span m=''1542270''>name.</span>
  <span m=''1543450''>We''ve</span> <span m=''1543640''>had</span> <span m=''1543860''>K</span>
  <span m=''1544170''>forever.</span> <span m=''1544710''>Let''s</span> <span m=''1544960''>have</span>
  <span m=''1545160''>K2D.</span> <span m=''1548460''>And</span> <span m=''1548690''>u</span>
  <span m=''1548950''>is,</span> <span m=''1549160''>so</span> <span m=''1549840''>tell</span>
  <span m=''1550090''>me</span> <span m=''1550260''>now</span> <span m=''1550560''>again</span>
  <span m=''1550990''>just</span> <span m=''1551310''>so</span> <span m=''1551450''>we</span>
  <span m=''1551630''>got,</span> <span m=''1552220''>what</span> <span m=''1552480''>size</span>
  <span m=''1552850''>is</span> <span m=''1553040''>K2D</span> <span m=''1554140''>for</span>
  <span m=''1554290''>this</span> <span m=''1554560''>particular</span> <span m=''1555140''>problem?</span>
  <span m=''1556160''>What''s</span> <span m=''1556600''>the</span> <span m=''1556720''>shape</span>
  <span m=''1557090''>of</span> <span m=''1557200''>it?</span> <span m=''1559250''>How</span>
  <span m=''1559420''>many</span> <span m=''1559730''>unknowns</span> <span m=''1560200''>have</span>
  <span m=''1560320''>I</span> <span m=''1560420''>got</span> <span m=''1560680''>in</span>
  <span m=''1560810''>u?</span> <span m=''1562950''>Nine.</span> <span m=''1564000''>Nine</span>
  <span m=''1564450''>unknowns.</span> <span m=''1566080''>And</span> <span m=''1566450''>notice,</span>
  <span m=''1566880''>of</span> <span m=''1567010''>course,</span> <span m=''1567400''>near</span>
  <span m=''1567820''>the</span> <span m=''1567970''>boundary,</span> <span m=''1573080''>if</span>
  <span m=''1573290''>this</span> <span m=''1573580''>was</span> <span m=''1573810''>the--</span>
  <span m=''1574070''>Well</span> <span m=''1574330''>let</span> <span m=''1574420''>me</span>
  <span m=''1574520''>take</span> <span m=''1574780''>the</span> <span m=''1574890''>first</span>
  <span m=''1575280''>one.</span> <span m=''1576080''>What</span> <span m=''1576190''>does</span>
  <span m=''1576330''>the very</span> <span m=''1577340''>first</span> <span m=''1577900''>row</span>
  <span m=''1578160''>of</span> <span m=''1578300''>K</span> <span m=''1578630''>look</span>
  <span m=''1578900''>like?</span> <span m=''1579120''>If I</span> <span m=''1579470''>number</span>
  <span m=''1579790''>nodes</span> <span m=''1580270''>like</span> <span m=''1580530''>this.</span>
  <span m=''1580880''>So</span> <span m=''1581180''>this</span> <span m=''1581440''>will</span>
  <span m=''1581550''>be</span> <span m=''1581820''>node</span> <span m=''1582080''>number</span>
  <span m=''1582600''>one,</span> <span m=''1582950''>two,</span> <span m=''1583290''>three,</span>
  <span m=''1583970''>four,</span> <span m=''1584260''>five,</span> <span m=''1584530''>six,</span>
  <span m=''1584830''>seven,</span> <span m=''1585200''>eight,</span> <span m=''1585420''>nine.</span>
  <span m=''1587370''>So</span> <span m=''1587790''>number</span> <span m=''1588170''>one</span>
  <span m=''1588810''>is</span> <span m=''1589280''>sort</span> <span m=''1589500''>of</span>
  <span m=''1589590''>close</span> <span m=''1589920''>to</span> <span m=''1590030''>a</span>
  <span m=''1590110''>boundary.</span> <span m=''1591220''>So</span> <span m=''1591510''>I</span>
  <span m=''1591680''>have</span> <span m=''1592070''>here</span> <span m=''1592420''>a</span>
  <span m=''1592760''>minus</span> <span m=''1593250''>one,</span> <span m=''1593850''>a</span>
  <span m=''1594030''>two,</span> <span m=''1594970''>and</span> <span m=''1595190''>this</span>
  <span m=''1595360''>is</span> <span m=''1595530''>gone.</span> <span m=''1596410''>That''s</span>
  <span m=''1597040''>like</span> <span m=''1597280''>a</span> <span m=''1597350''>column</span>
  <span m=''1597870''>of</span> <span m=''1597990''>our</span> <span m=''1598150''>matrix</span>
  <span m=''1599210''>removed.</span> <span m=''1600810''>Like</span> <span m=''1601050''>a</span>
  <span m=''1601120''>grounded</span> <span m=''1601710''>node,</span> <span m=''1602180''>or</span>
  <span m=''1602310''>whatever.</span> <span m=''1603080''>But</span> <span m=''1603320''>then</span>
  <span m=''1603510''>I</span> <span m=''1603590''>have</span> <span m=''1603740''>the</span>
  <span m=''1603850''>vertical</span> <span m=''1604310''>one</span> <span m=''1604720''>minus</span>
  <span m=''1605210''>one,</span> <span m=''1606090''>two,</span> <span m=''1606520''>making</span>
  <span m=''1606930''>this</span> <span m=''1607160''>into</span> <span m=''1607510''>a</span>
  <span m=''1607600''>four.</span> <span m=''1609070''>And</span> <span m=''1609280''>this</span>
  <span m=''1609500''>guy</span> <span m=''1610020''>will</span> <span m=''1610220''>also</span>
  <span m=''1610580''>be</span> <span m=''1611440''>removed.</span> <span m=''1612320''>So</span>
  <span m=''1612570''>I</span> <span m=''1612790''>think</span> <span m=''1613190''>if</span>
  <span m=''1613360''>I</span> <span m=''1613540''>look</span> <span m=''1613840''>at</span>
  <span m=''1614000''>K2D,</span> <span m=''1614530''>it''s</span> <span m=''1615970''>nine</span>
  <span m=''1616410''>by</span> <span m=''1616600''>nine.</span> </p><p><span m=''1617670''>I</span>
  <span m=''1617850''>don''t</span> <span m=''1618090''>plan</span> <span m=''1618360''>to</span>
  <span m=''1618440''>write</span> <span m=''1618710''>all</span> <span m=''1619000''>81</span>
  <span m=''1619500''>entries.</span> <span m=''1621640''>But</span> <span m=''1621800''>I</span>
  <span m=''1621890''>could</span> <span m=''1622140''>write</span> <span m=''1622420''>the</span>
  <span m=''1622540''>first</span> <span m=''1622910''>row.</span> <span m=''1624040''>The</span>
  <span m=''1624170''>first</span> <span m=''1624590''>row</span> <span m=''1625770''>comes</span>
  <span m=''1626130''>from</span> <span m=''1626340''>the</span> <span m=''1627800''>first</span>
  <span m=''1628200''>equation.</span> <span m=''1629150''>So</span> <span m=''1629310''>the</span>
  <span m=''1629430''>first</span> <span m=''1629890''>row</span> <span m=''1630540''>has</span>
  <span m=''1630940''>an</span> <span m=''1631070''>f_1</span> <span m=''1631770''>on</span>
  <span m=''1631920''>the</span> <span m=''1631990''>right</span> <span m=''1632250''>hand</span>
  <span m=''1632520''>side,</span> <span m=''1632900''>f</span> <span m=''1633200''>at</span>
  <span m=''1633320''>this</span> <span m=''1633560''>point.</span> <span m=''1634510''>And</span>
  <span m=''1634770''>what</span> <span m=''1635000''>do</span> <span m=''1635070''>you</span>
  <span m=''1635230''>see,</span> <span m=''1635590''>what''s</span> <span m=''1635850''>on</span>
  <span m=''1636010''>the</span> <span m=''1636110''>diagonal?</span> <span m=''1637070''>Of</span>
  <span m=''1637480''>K2D?</span> <span m=''1639140''>Four.</span> <span m=''1640790''>And</span>
  <span m=''1641070''>what''s</span> <span m=''1643180''>the</span> <span m=''1643280''>rest</span>
  <span m=''1643560''>of</span> <span m=''1643640''>the</span> <span m=''1643740''>row?</span>
  <span m=''1645100''>Well</span> <span m=''1645640''>there''s</span> <span m=''1645970''>the</span>
  <span m=''1646080''>next</span> <span m=''1646410''>point</span> <span m=''1646780''>and
  it</span> <span m=''1646880''>has</span> <span m=''1647130''>a</span> <span m=''1647220''>minus</span>
  <span m=''1647630''>one.</span> <span m=''1650200''>And</span> <span m=''1650500''>then</span>
  <span m=''1650870''>this</span> <span m=''1651120''>point</span> <span m=''1651570''>is</span>
  <span m=''1651710''>not</span> <span m=''1652010''>connected</span> <span m=''1652560''>to</span>
  <span m=''1652670''>that,</span> <span m=''1653050''>so</span> <span m=''1653150''>it''s</span>
  <span m=''1653310''>a</span> <span m=''1653370''>zero.</span> <span m=''1653870''>I''d</span>
  <span m=''1654100''>better</span> <span m=''1654590''>leave</span> <span m=''1654820''>room</span>
  <span m=''1655170''>for</span> <span m=''1656060''>nine</span> <span m=''1656410''>by</span>
  <span m=''1656560''>nine</span> <span m=''1656950''>here.</span> <span m=''1657340''>Four,</span>
  <span m=''1657890''>minus</span> <span m=''1658370''>one,</span> <span m=''1658850''>zero.</span>
  <span m=''1660510''>And</span> <span m=''1660750''>now</span> <span m=''1661080''>what</span>
  <span m=''1661380''>about</span> <span m=''1662040''>number,</span> <span m=''1663680''>the</span>
  <span m=''1663770''>rest</span> <span m=''1664060''>of</span> <span m=''1664130''>the</span>
  <span m=''1664200''>row?</span> <span m=''1665480''>So</span> <span m=''1666020''>there''s</span>
  <span m=''1666620''>four</span> <span m=''1667400''>is the</span> <span m=''1667830''>center,</span>
  <span m=''1668670''>minus</span> <span m=''1669180''>one,</span> <span m=''1669600''>zero.</span>
  <span m=''1669980''>And</span> <span m=''1670140''>now</span> <span m=''1670380''>I</span>
  <span m=''1670460''>come</span> <span m=''1670740''>to</span> <span m=''1670830''>here,</span>
  <span m=''1671220''>so</span> <span m=''1671440''>what''s</span> <span m=''1671720''>the</span>
  <span m=''1671830''>next</span> <span m=''1672140''>entry</span> <span m=''1672460''>in</span>
  <span m=''1672550''>my</span> <span m=''1672660''>matrix?</span> <span m=''1674060''>Minus</span>
  <span m=''1674530''>one.</span> <span m=''1675310''>We''re</span> <span m=''1675540''>multiplying</span>
  <span m=''1676590''>the</span> <span m=''1676740''>unknown,</span> <span m=''1677580''>the</span>
  <span m=''1677700''>fourth</span> <span m=''1678090''>unknown.</span> <span m=''1679080''>And</span>
  <span m=''1679410''>what</span> <span m=''1679550''>about</span> <span m=''1679810''>the</span>
  <span m=''1679900''>rest</span> <span m=''1680210''>of</span> <span m=''1680310''>the</span>
  <span m=''1680380''>row?</span> <span m=''1682780''>This</span> <span m=''1683080''>guy</span>
  <span m=''1683420''>is</span> <span m=''1683550''>not</span> <span m=''1683870''>connected</span>
  <span m=''1684360''>to</span> <span m=''1684450''>five,</span> <span m=''1684820''>six,</span>
  <span m=''1685120''>seven,</span> <span m=''1685430''>eight,</span> <span m=''1685610''>or</span>
  <span m=''1685750''>nine.</span> <span m=''1686110''>So</span> <span m=''1686320''>now</span>
  <span m=''1686570''>I</span> <span m=''1686660''>have</span> <span m=''1687110''>zero,</span>
  <span m=''1687440''>zero,</span> <span m=''1687760''>zero,</span> <span m=''1688090''>zero,</span>
  <span m=''1688420''>zero.</span> <span m=''1691040''>OK.</span> <span m=''1693250''>So</span>
  <span m=''1693440''>that</span> <span m=''1693680''>would</span> <span m=''1693850''>be</span>
  <span m=''1694200''>a</span> <span m=''1694310''>row,</span> <span m=''1695780''>that</span>
  <span m=''1695980''>would</span> <span m=''1696120''>be</span> <span m=''1696220''>a</span>
  <span m=''1696300''>row</span> <span m=''1696760''>that''s</span> <span m=''1697690''>sort</span>
  <span m=''1697890''>of</span> <span m=''1698060''>different</span> <span m=''1698460''>because</span>
  <span m=''1699250''>it</span> <span m=''1699390''>corresponds</span> <span m=''1700110''>to</span>
  <span m=''1700410''>a</span> <span m=''1700920''>mesh</span> <span m=''1701240''>point</span>
  <span m=''1701530''>that''s</span> <span m=''1701680''>way</span> <span m=''1701910''>over</span>
  <span m=''1702130''>near</span> <span m=''1702360''>the</span> <span m=''1702500''>corner.</span>
  <span m=''1703510''>How about</span> <span m=''1703860''>the</span> <span m=''1703980''>fifth</span>
  <span m=''1704510''>row?</span> <span m=''1705260''>What</span> <span m=''1705540''>would</span>
  <span m=''1705700''>be</span> <span m=''1705840''>the</span> <span m=''1706030''>fifth</span>
  <span m=''1706430''>row</span> <span m=''1706670''>of</span> <span m=''1707120''>K2D</span>
  <span m=''1709020''>corresponding</span> <span m=''1709400''>to</span> <span m=''1709800''>this</span>
  <span m=''1710040''>guy</span> <span m=''1710240''>that''s</span> <span m=''1710470''>right</span>
  <span m=''1710780''>in</span> <span m=''1710890''>the</span> <span m=''1710970''>middle?</span>
  <span m=''1713320''>What''s</span> <span m=''1713600''>on</span> <span m=''1713750''>the</span>
  <span m=''1713850''>diagonal,</span> <span m=''1714430''>what''s</span> <span m=''1714800''>the</span>
  <span m=''1714950''>5,</span> <span m=''1715470''>5</span> <span m=''1716010''>entry</span>
  <span m=''1716440''>of</span> <span m=''1716660''>K2D?</span> <span m=''1719140''>Four.</span>
  <span m=''1719810''>Good.</span> <span m=''1720200''>I''m</span> <span m=''1720360''>going
  to</span> <span m=''1720590''>have</span> <span m=''1720740''>a</span> <span m=''1720810''>diagonal</span>
  <span m=''1721400''>of</span> <span m=''1721560''>fours.</span> <span m=''1722530''>I''m
  going to have</span> <span m=''1722870''>fours</span> <span m=''1723260''>all</span>
  <span m=''1723430''>the</span> <span m=''1723520''>way</span> <span m=''1723660''>down</span>
  <span m=''1723950''>the</span> <span m=''1724050''>diagonal.</span> <span m=''1725020''>Because</span>
  <span m=''1725210''>every</span> <span m=''1726350''>point</span> <span m=''1727080''>the</span>
  <span m=''1727360''>molecule</span> <span m=''1728120''>is</span> <span m=''1728290''>centered</span>
  <span m=''1728730''>at</span> <span m=''1729180''>gives</span> <span m=''1729380''>me</span>
  <span m=''1729520''>the</span> <span m=''1729670''>four,</span> <span m=''1730490''>and</span>
  <span m=''1730770''>I</span> <span m=''1730960''>just</span> <span m=''1731200''>have</span>
  <span m=''1731320''>a</span> <span m=''1731400''>minus</span> <span m=''1731820''>one</span>
  <span m=''1732150''>for its</span> <span m=''1732450''>neighbor.</span> <span m=''1733460''>And</span>
  <span m=''1733780''>this</span> <span m=''1734050''>guy</span> <span m=''1734300''>has</span>
  <span m=''1734570''>all</span> <span m=''1734820''>four</span> <span m=''1735080''>neighbors.</span>
  <span m=''1736210''>They''re</span> <span m=''1736380''>all</span> <span m=''1737480''>alive</span>
  <span m=''1737840''>and</span> <span m=''1737970''>well,</span> <span m=''1739350''>so</span>
  <span m=''1739670''>there''s</span> <span m=''1739920''>a</span> <span m=''1740050''>guy,</span>
  <span m=''1742140''>this</span> <span m=''1742360''>is</span> <span m=''1742510''>the</span>
  <span m=''1742640''>fifth</span> <span m=''1743100''>row.</span> <span m=''1743940''>There''s</span>
  <span m=''1744170''>somebody</span> <span m=''1744640''>right</span> <span m=''1744950''>next</span>
  <span m=''1745300''>door</span> <span m=''1745600''>on</span> <span m=''1745760''>the</span>
  <span m=''1745860''>left.</span> <span m=''1746300''>Somebody</span> <span m=''1746570''>right</span>
  <span m=''1746840''>next</span> <span m=''1747160''>door</span> <span m=''1747340''>on</span>
  <span m=''1747480''>the</span> <span m=''1747580''>right.</span> <span m=''1748700''>And</span>
  <span m=''1749000''>then</span> <span m=''1751460''>do</span> <span m=''1752060''>the</span>
  <span m=''1752190''>other</span> <span m=''1752420''>minus</span> <span m=''1752860''>ones</span>
  <span m=''1753250''>go</span> <span m=''1753470''>after</span> <span m=''1753800''>that?</span>
  <span m=''1755950''>This</span> <span m=''1756170''>is</span> <span m=''1756320''>the</span>
  <span m=''1756410''>whole</span> <span m=''1756620''>point.</span> <span m=''1757000''>I</span>
  <span m=''1757250''>want</span> <span m=''1757540''>you</span> <span m=''1757630''>to</span>
  <span m=''1757770''>see</span> <span m=''1758140''>how</span> <span m=''1758330''>this</span>
  <span m=''1758570''>K2D</span> <span m=''1759400''>matrix</span> <span m=''1760180''>looks.</span>
  <span m=''1761200''>Because</span> <span m=''1761420''>it''s</span> <span m=''1761650''>the</span>
  <span m=''1761750''>one,</span> <span m=''1762340''>it''s</span> <span m=''1762580''>the</span>
  <span m=''1762720''>equation</span> <span m=''1763130''>we</span> <span m=''1763220''>have</span>
  <span m=''1763380''>to</span> <span m=''1763540''>solve.</span> <span m=''1764600''>So</span>
  <span m=''1764750''>we''ve</span> <span m=''1764880''>got to</span> <span m=''1765210''>know</span>
  <span m=''1765410''>what</span> <span m=''1765660''>this</span> <span m=''1765860''>matrix</span>
  <span m=''1766360''>looks</span> <span m=''1766650''>like.</span> <span m=''1767450''>So</span>
  <span m=''1767610''>what''s</span> <span m=''1767930''>the</span> <span m=''1768040''>point</span>
  <span m=''1768460''>here?</span> <span m=''1769030''>Four,</span> <span m=''1769440''>it''s</span>
  <span m=''1769590''>got</span> <span m=''1769780''>a</span> <span m=''1769890''>neighbor</span>
  <span m=''1770220''>there.</span> <span m=''1770960''>This</span> <span m=''1771200''>was</span>
  <span m=''1772260''>unknown</span> <span m=''1772750''>number</span> <span m=''1773050''>five.</span>
  <span m=''1774090''>It''s</span> <span m=''1774420''>fourth</span> <span m=''1774880''>unknown</span>
  <span m=''1775340''>and</span> <span m=''1775480''>the</span> <span m=''1775550''>sixth</span>
  <span m=''1775850''>unknown,</span> <span m=''1776920''>what</span> <span m=''1777230''>are</span>
  <span m=''1777620''>the</span> <span m=''1777710''>numbers</span> <span m=''1778140''>of</span>
  <span m=''1778260''>these</span> <span m=''1778570''>unknowns?</span> <span m=''1779120''>Two</span>
  <span m=''1780650''>and</span> <span m=''1782000''>eight.</span> </p><p><span m=''1783110''>So</span>
  <span m=''1783400''>this</span> <span m=''1783810''>guy</span> <span m=''1784430''>is</span>
  <span m=''1784650''>going to</span> <span m=''1784880''>have</span> <span m=''1785040''>a</span>
  <span m=''1785130''>minus</span> <span m=''1785650''>one</span> <span m=''1785990''>in</span>
  <span m=''1786180''>the</span> <span m=''1786740''>two</span> <span m=''1787180''>position.</span>
  <span m=''1788440''>And</span> <span m=''1788630''>then</span> <span m=''1788900''>zero.</span>
  <span m=''1789920''>And</span> <span m=''1790160''>this</span> <span m=''1790480''>guy,</span>
  <span m=''1790930''>it''ll</span> <span m=''1791270''>also</span> <span m=''1791780''>have</span>
  <span m=''1791960''>a</span> <span m=''1792050''>minus</span> <span m=''1792490''>one,</span>
  <span m=''1793480''>is</span> <span m=''1793630''>that</span> <span m=''1793840''>nine?</span>
  <span m=''1794510''>Yeah,</span> <span m=''1794830''>do</span> <span m=''1794940''>you</span>
  <span m=''1795040''>see</span> <span m=''1795310''>how</span> <span m=''1795550''>it''s</span>
  <span m=''1795710''>going?</span> <span m=''1796410''>I</span> <span m=''1796580''>have</span>
  <span m=''1798760''>a</span> <span m=''1798890''>diagonal,</span> <span m=''1800940''>I
  have</span> <span m=''1801190''>five</span> <span m=''1801700''>diagonals</span>
  <span m=''1802470''>somehow.</span> <span m=''1803450''>I</span> <span m=''1803590''>have</span>
  <span m=''1803940''>diagonal,</span> <span m=''1805130''>the</span> <span m=''1805370''>neighbor</span>
  <span m=''1805740''>on</span> <span m=''1805880''>the</span> <span m=''1805980''>left,</span>
  <span m=''1806470''>the</span> <span m=''1806580''>neighbor</span> <span m=''1806970''>on</span>
  <span m=''1807130''>the</span> <span m=''1807210''>right,</span> <span m=''1807790''>the</span>
  <span m=''1807960''>neighbor</span> <span m=''1808470''>underneath,</span> <span
  m=''1809390''>and</span> <span m=''1809930''>the</span> <span m=''1810120''>neighbor</span>
  <span m=''1810960''>above.</span> <span m=''1812630''>Across</span> <span m=''1813080''>the</span>
  <span m=''1813210''>street</span> <span m=''1813570''>you</span> <span m=''1813680''>could</span>
  <span m=''1813840''>say.</span> <span m=''1817380''>So</span> <span m=''1817620''>our</span>
  <span m=''1817810''>matrix,</span> <span m=''1819570''>this</span> <span m=''1819820''>very</span>
  <span m=''1820220''>important</span> <span m=''1820640''>matrix,</span> <span m=''1820990''>more</span>
  <span m=''1821340''>attention</span> <span m=''1821910''>has</span> <span m=''1822100''>gone</span>
  <span m=''1822450''>into</span> <span m=''1822740''>how</span> <span m=''1823000''>to</span>
  <span m=''1823130''>solve</span> <span m=''1824270''>this</span> <span m=''1824850''>equation</span>
  <span m=''1825920''>for</span> <span m=''1826130''>that</span> <span m=''1826420''>matrix</span>
  <span m=''1827480''>than</span> <span m=''1827810''>any</span> <span m=''1828240''>other</span>
  <span m=''1828540''>single</span> <span m=''1829660''>specific</span> <span m=''1830320''>example</span>
  <span m=''1831780''>in</span> <span m=''1832150''>numerical</span> <span m=''1832580''>analysis.</span>
  <span m=''1833340''>It''s</span> <span m=''1833590''>just</span> <span m=''1835080''>a</span>
  <span m=''1835250''>model</span> <span m=''1835770''>problem.</span> <span m=''1836700''>And</span>
  <span m=''1837530''>what</span> <span m=''1837900''>do</span> <span m=''1838040''>I</span>
  <span m=''1838180''>notice</span> <span m=''1838610''>about</span> <span m=''1838940''>this</span>
  <span m=''1839160''>matrix?</span> <span m=''1840190''>So</span> <span m=''1840360''>now</span>
  <span m=''1841870''>you</span> <span m=''1842070''>see</span> <span m=''1842340''>it''s</span>
  <span m=''1842510''>got</span> <span m=''1842730''>five</span> <span m=''1843170''>diagonals.</span>
  <span m=''1844780''>But,</span> <span m=''1846320''>and</span> <span m=''1846450''>what''s</span>
  <span m=''1846700''>the</span> <span m=''1846810''>big</span> <span m=''1847120''>but?</span>
  <span m=''1848740''>The</span> <span m=''1848880''>big</span> <span m=''1849220''>but</span>
  <span m=''1849510''>is</span> <span m=''1849770''>that</span> <span m=''1849930''>those</span>
  <span m=''1850180''>five</span> <span m=''1850520''>diagonals</span> <span m=''1851090''>don''t</span>
  <span m=''1851360''>run,</span> <span m=''1853000''>it''s</span> <span m=''1853180''>not</span>
  <span m=''1855240''>just</span> <span m=''1855540''>a</span> <span m=''1855620''>band</span>
  <span m=''1856320''>of</span> <span m=''1856450''>five</span> <span m=''1857510''>because</span>
  <span m=''1858080''>you</span> <span m=''1858290''>don''t</span> <span m=''1858730''>get</span>
  <span m=''1859110''>to</span> <span m=''1859290''>the</span> <span m=''1859940''>one</span>
  <span m=''1860400''>up</span> <span m=''1860500''>above</span> <span m=''1860980''>until</span>
  <span m=''1861160''>you''ve</span> <span m=''1862370''>gone</span> <span m=''1863310''>all</span>
  <span m=''1863690''>the</span> <span m=''1863800''>way--</span> <span m=''1866280''>You</span>
  <span m=''1866440''>see</span> <span m=''1866640''>the</span> <span m=''1866760''>bandwidth</span>
  <span m=''1867280''>is</span> <span m=''1867430''>big.</span> <span m=''1869470''>If</span>
  <span m=''1869670''>my</span> <span m=''1869880''>matrix--</span> <span m=''1870650''>If</span>
  <span m=''1871210''>this</span> <span m=''1871450''>is</span> <span m=''1872290''>one,</span>
  <span m=''1873020''>two</span> <span m=''1873410''>up</span> <span m=''1873650''>to</span>
  <span m=''1873840''>n,</span> <span m=''1875030''>and</span> <span m=''1875250''>this</span>
  <span m=''1875440''>is</span> <span m=''1875610''>one,</span> <span m=''1876080''>two</span>
  <span m=''1876390''>up</span> <span m=''1876610''>to</span> <span m=''1876700''>n,</span>
  <span m=''1877710''>then</span> <span m=''1879490''>how</span> <span m=''1879620''>many</span>
  <span m=''1879860''>unknowns</span> <span m=''1880330''>have</span> <span m=''1880460''>I</span>
  <span m=''1880580''>got?</span> <span m=''1882050''>Just</span> <span m=''1882610''>think</span>
  <span m=''1882880''>big</span> <span m=''1883180''>now.</span> <span m=''1883600''>We''re</span>
  <span m=''1883740''>in</span> <span m=''1884090''>2-D,</span> <span m=''1884410''>think</span>
  <span m=''1884780''>2-D.</span> <span m=''1885900''>How</span> <span m=''1886180''>many</span>
  <span m=''1886490''>unknowns</span> <span m=''1887060''>have</span> <span m=''1887180''>I</span>
  <span m=''1887270''>got?</span> <span m=''1887500''>N</span> <span m=''1887740''>was</span>
  <span m=''1888060''>three</span> <span m=''1888600''>in</span> <span m=''1889160''>the</span>
  <span m=''1889240''>picture,</span> <span m=''1890080''>but</span> <span m=''1890430''>now</span>
  <span m=''1891380''>you''re</span> <span m=''1891870''>kind of</span> <span m=''1892140''>visualizing</span>
  <span m=''1892940''>a</span> <span m=''1893130''>much</span> <span m=''1893460''>finer</span>
  <span m=''1893910''>grid.</span> <span m=''1894760''>How</span> <span m=''1894970''>many</span>
  <span m=''1895250''>unknowns?</span> <span m=''1896570''>N</span> <span m=''1896950''>squared</span>
  <span m=''1897450''>unknowns,</span> <span m=''1897910''>right?</span> <span m=''1898730''>One</span>
  <span m=''1899040''>to</span> <span m=''1899140''>N</span> <span m=''1899510''>in</span>
  <span m=''1899640''>each</span> <span m=''1899900''>direction.</span> <span m=''1900470''>So</span>
  <span m=''1900670''>we''ve</span> <span m=''1900970''>got</span> <span m=''1901180''>the</span>
  <span m=''1901280''>matrix</span> <span m=''1901790''>of</span> <span m=''1901950''>size</span>
  <span m=''1902400''>N</span> <span m=''1902800''>squared.</span> <span m=''1903620''>Way</span>
  <span m=''1904010''>bigger,</span> <span m=''1904980''>way</span> <span m=''1905250''>bigger.</span>
  <span m=''1906240''>I</span> <span m=''1906350''>mean</span> <span m=''1906610''>if</span>
  <span m=''1907320''>N</span> <span m=''1907570''>was</span> <span m=''1907790''>ten,</span>
  <span m=''1908240''>our</span> <span m=''1908390''>matrix</span> <span m=''1908880''>is</span>
  <span m=''1909030''>of</span> <span m=''1909160''>size</span> <span m=''1909490''>100.</span>
  <span m=''1910780''>And</span> <span m=''1911500''>of course,</span> <span m=''1911850''>that''s</span>
  <span m=''1913720''>completely</span> <span m=''1914250''>simple.</span> <span m=''1914840''>The</span>
  <span m=''1915360''>real</span> <span m=''1915680''>question</span> <span m=''1916100''>is</span>
  <span m=''1916300''>when</span> <span m=''1916510''>N</span> <span m=''1916790''>becomes</span>
  <span m=''1917350''>1,000</span> <span m=''1917990''>and</span> <span m=''1918100''>our</span>
  <span m=''1918230''>matrix</span> <span m=''1918770''>is</span> <span m=''1918930''>of</span>
  <span m=''1919350''>size</span> <span m=''1919440''>a million.</span> <span m=''1920680''>And</span>
  <span m=''1921100''>those</span> <span m=''1921200''>get</span> <span m=''1921590''>solved</span>
  <span m=''1921980''>every</span> <span m=''1922220''>day.</span> <span m=''1922990''>So,</span>
  <span m=''1923640''>question</span> <span m=''1924120''>is</span> <span m=''1924350''>how.</span>
  <span m=''1925940''>Actually</span> <span m=''1926590''>this,</span> <span m=''1927440''>for</span>
  <span m=''1927640''>a</span> <span m=''1927790''>million</span> <span m=''1928210''>by</span>
  <span m=''1928410''>million</span> <span m=''1928850''>matrix,</span> <span m=''1930150''>this</span>
  <span m=''1930560''>fast</span> <span m=''1931140''>Poisson</span> <span m=''1931710''>solver</span>
  <span m=''1932070''>that</span> <span m=''1932260''>I</span> <span m=''1932330''>want</span>
  <span m=''1932610''>to</span> <span m=''1932690''>describe</span> <span m=''1934240''>does</span>
  <span m=''1934480''>it</span> <span m=''1934730''>great.</span> <span m=''1935650''>Actually,</span>
  <span m=''1936180''>so</span> <span m=''1936370''>you</span> <span m=''1936560''>can</span>
  <span m=''1936770''>deal</span> <span m=''1937010''>with</span> <span m=''1937140''>a</span>
  <span m=''1937200''>matrix</span> <span m=''1937740''>of</span> <span m=''1937900''>order</span>
  <span m=''1938510''>a</span> <span m=''1938630''>million</span> <span m=''1941340''>without</span>
  <span m=''1941860''>turning</span> <span m=''1942200''>a</span> <span m=''1942280''>hair.</span>
  </p><p><span m=''1943130''>OK</span> <span m=''1943530''>now,</span> <span m=''1943700''>but</span>
  <span m=''1943920''>can</span> <span m=''1944150''>we</span> <span m=''1944300''>understand</span>
  <span m=''1944970''>that</span> <span m=''1945180''>matrix?</span> <span m=''1945670''>So</span>
  <span m=''1946610''>suppose</span> <span m=''1947150''>N</span> <span m=''1947360''>is</span>
  <span m=''1947500''>100.</span> <span m=''1949580''>Just</span> <span m=''1949840''>to</span>
  <span m=''1949930''>have</span> <span m=''1950170''>us--</span> <span m=''1951910''>What''s</span>
  <span m=''1952370''>the</span> <span m=''1952500''>story?</span> <span m=''1953830''>This</span>
  <span m=''1954120''>matrix,</span> <span m=''1954730''>then.</span> <span m=''1955100''>What''s</span>
  <span m=''1955360''>the</span> <span m=''1955470''>size</span> <span m=''1955810''>of</span>
  <span m=''1955890''>that</span> <span m=''1956060''>matrix?</span> <span m=''1957250''>Did</span>
  <span m=''1957470''>I</span> <span m=''1957560''>say</span> <span m=''1957760''>100?</span>
  <span m=''1959160''>Or</span> <span m=''1959280''>1,000,</span> <span m=''1960130''>do</span>
  <span m=''1960500''>you</span> <span m=''1960600''>want to</span> <span m=''1960800''>think</span>
  <span m=''1961110''>really</span> <span m=''1961360''>big?</span> <span m=''1963500''>I</span>
  <span m=''1963600''>guess</span> <span m=''1963870''>I</span> <span m=''1963970''>said</span>
  <span m=''1964210''>1,000.</span> <span m=''1964870''>To</span> <span m=''1965310''>get</span>
  <span m=''1965560''>up</span> <span m=''1965720''>to</span> <span m=''1965830''>a</span>
  <span m=''1965890''>million.</span> <span m=''1967430''>OK,</span> <span m=''1968060''>so</span>
  <span m=''1968310''>N</span> <span m=''1968610''>is</span> <span m=''1968710''>1,000,</span>
  <span m=''1969580''>so we</span> <span m=''1969690''>have</span> <span m=''1969800''>a</span>
  <span m=''1969910''>1,000</span> <span m=''1970390''>by</span> <span m=''1970590''>1,000,</span>
  <span m=''1971220''>a</span> <span m=''1971330''>million</span> <span m=''1971820''>unknowns.</span>
  <span m=''1972940''>My</span> <span m=''1973190''>matrix</span> <span m=''1973730''>is</span>
  <span m=''1973890''>a</span> <span m=''1973960''>million</span> <span m=''1974570''>by</span>
  <span m=''1974750''>a</span> <span m=''1974860''>million.</span> <span m=''1976550''>Let</span>
  <span m=''1976710''>me</span> <span m=''1976830''>ask</span> <span m=''1977150''>you</span>
  <span m=''1977260''>this.</span> <span m=''1977510''>Here''s</span> <span m=''1977920''>the</span>
  <span m=''1978110''>question</span> <span m=''1978740''>that</span> <span m=''1978900''>I</span>
  <span m=''1978960''>want to</span> <span m=''1979210''>ask</span> <span m=''1979480''>you.</span>
  <span m=''1979840''>What''s</span> <span m=''1980510''>the</span> <span m=''1980630''>bandwidth?</span>
  <span m=''1981770''>How</span> <span m=''1982100''>far</span> <span m=''1982670''>from</span>
  <span m=''1982960''>the</span> <span m=''1983190''>main</span> <span m=''1983630''>diagonal</span>
  <span m=''1984490''>out</span> <span m=''1986760''>to</span> <span m=''1989690''>the
  last-- out to that</span> <span m=''1990040''>minus</span> <span m=''1990510''>one.</span>
  <span m=''1992020''>In</span> <span m=''1992370''>other</span> <span m=''1992530''>words,</span>
  <span m=''1994130''>this</span> <span m=''1994580''>is</span> <span m=''1994810''>really</span>
  <span m=''1995250''>the</span> <span m=''1995450''>full</span> <span m=''1995920''>band</span>
  <span m=''1996480''>of</span> <span m=''1996650''>the</span> <span m=''1997180''>matrix.</span>
  <span m=''1998920''>It''s</span> <span m=''1999180''>got</span> <span m=''1999410''>a</span>
  <span m=''1999510''>lot</span> <span m=''1999760''>of</span> <span m=''1999890''>zeroes</span>
  <span m=''2000500''>inside</span> <span m=''2001090''>the</span> <span m=''2001170''>band.</span>
  <span m=''2002470''>A whole bunch.</span> <span m=''2003270''>Maybe</span> <span
  m=''2004600''>990</span> <span m=''2006090''>something</span> <span m=''2006880''>zeroes</span>
  <span m=''2007550''>in</span> <span m=''2007820''>here.</span> <span m=''2008630''>And</span>
  <span m=''2008910''>in</span> <span m=''2009100''>here,</span> <span m=''2009850''>and</span>
  <span m=''2010670''>how</span> <span m=''2010950''>far</span> <span m=''2011280''>is</span>
  <span m=''2011450''>it</span> <span m=''2011620''>from</span> <span m=''2011790''>here</span>
  <span m=''2012070''>to</span> <span m=''2012240''>here?</span> <span m=''2014890''>1,000,</span>
  <span m=''2016030''>right?</span> <span m=''2016450''>It''s</span> <span m=''2016670''>1,000.</span>
  <span m=''2018080''>So</span> <span m=''2018260''>the</span> <span m=''2018380''>bandwidth</span>
  <span m=''2018790''>is</span> <span m=''2019160''>1,000.</span> <span m=''2020430''>And</span>
  <span m=''2023840''>what</span> <span m=''2024070''>if</span> <span m=''2024230''>I</span>
  <span m=''2024390''>do</span> <span m=''2024930''>ordinary,</span> <span m=''2026130''>so</span>
  <span m=''2026350''>now</span> <span m=''2026630''>I</span> <span m=''2026700''>want</span>
  <span m=''2026940''>to</span> <span m=''2027000''>begin</span> <span m=''2027280''>to</span>
  <span m=''2027370''>think</span> <span m=''2027670''>how</span> <span m=''2027880''>do</span>
  <span m=''2027980''>I</span> <span m=''2028110''>solve</span> <span m=''2028490''>this</span>
  <span m=''2028760''>equation?</span> <span m=''2030120''>How</span> <span m=''2030280''>do</span>
  <span m=''2030400''>I</span> <span m=''2030520''>work</span> <span m=''2030820''>with</span>
  <span m=''2030960''>that</span> <span m=''2031210''>matrix?</span> <span m=''2032110''>And</span>
  <span m=''2032280''>you</span> <span m=''2032530''>have</span> <span m=''2032700''>an</span>
  <span m=''2032790''>idea of</span> <span m=''2033160''>that</span> <span m=''2033380''>matrix?</span>
  <span m=''2034780''>It''s</span> <span m=''2035650''>a</span> <span m=''2035730''>beautiful</span>
  <span m=''2036220''>matrix</span> <span m=''2036770''>to</span> <span m=''2036870''>work</span>
  <span m=''2037140''>with.</span> <span m=''2038140''>It''s</span> <span m=''2038470''>very</span>
  <span m=''2038990''>like</span> <span m=''2039370''>our</span> <span m=''2040240''>K</span>
  <span m=''2040730''>matrix;</span> <span m=''2041770''>it''s</span> <span m=''2041980''>just</span>
  <span m=''2042830''>up</span> <span m=''2043080''>to</span> <span m=''2043230''>2-D.</span>
  <span m=''2044940''>In</span> <span m=''2045060''>fact,</span> <span m=''2045360''>it''s</span>
  <span m=''2045520''>closely</span> <span m=''2046040''>connected</span> <span m=''2046540''>to</span>
  <span m=''2046670''>our--</span> <span m=''2047250''>K2D</span> <span m=''2047730''>will
  be</span> <span m=''2047900''>closely</span> <span m=''2048460''>connected</span>
  <span m=''2048960''>to</span> <span m=''2049080''>K</span> <span m=''2049470''>and</span>
  <span m=''2049640''>that''s</span> <span m=''2049870''>what</span> <span m=''2050000''>makes</span>
  <span m=''2051000''>life</span> <span m=''2051370''>possible</span> <span m=''2051920''>here.</span>
  <span m=''2053850''>But</span> <span m=''2058900''>suppose</span> <span m=''2059350''>I</span>
  <span m=''2059430''>had</span> <span m=''2059600''>to solve</span> <span m=''2060030''>this</span>
  <span m=''2060260''>equation.</span> <span m=''2061250''>Alright,</span> <span m=''2062400''>so</span>
  <span m=''2062690''>I</span> <span m=''2062820''>give</span> <span m=''2063020''>it</span>
  <span m=''2063110''>to</span> <span m=''2063200''>MATLAB</span> <span m=''2063900''>just</span>
  <span m=''2064190''>as</span> <span m=''2064320''>a</span> <span m=''2064420''>system</span>
  <span m=''2064890''>of</span> <span m=''2065030''>equations.</span> <span m=''2065600''>A</span>
  <span m=''2065680''>million</span> <span m=''2066050''>equations,</span> <span m=''2066600''>a</span>
  <span m=''2066670''>million</span> <span m=''2067070''>unknowns.</span> <span m=''2067820''>So</span>
  <span m=''2068190''>MATLAB</span> <span m=''2068620''>takes</span> <span m=''2068930''>a</span>
  <span m=''2069030''>gulp</span> <span m=''2069800''>and</span> <span m=''2069990''>then</span>
  <span m=''2070150''>it</span> <span m=''2070960''>tries,</span> <span m=''2071690''>OK?</span>
  <span m=''2072580''>So</span> <span m=''2073820''>ordinary</span> <span m=''2074380''>elimination,</span>
  <span m=''2075120''>that''s</span> <span m=''2075360''>what</span> <span m=''2075530''>backslash</span>
  <span m=''2076220''>does.</span> </p><p><span m=''2077040''>By</span> <span m=''2077230''>the</span>
  <span m=''2077360''>way</span> <span m=''2077990''>this</span> <span m=''2078240''>matrix</span>
  <span m=''2078800''>is</span> <span m=''2079030''>symmetric,</span> <span m=''2080440''>and,</span>
  <span m=''2080870''>you</span> <span m=''2080980''>won''t</span> <span m=''2081230''>be</span>
  <span m=''2081370''>surprised,</span> <span m=''2081960''>it''s</span> <span m=''2082140''>positive</span>
  <span m=''2082670''>definite.</span> <span m=''2083500''>Everything</span> <span
  m=''2084000''>is</span> <span m=''2084150''>nice</span> <span m=''2084460''>about</span>
  <span m=''2084750''>that</span> <span m=''2084950''>matrix.</span> <span m=''2086540''>In</span>
  <span m=''2086680''>fact</span> <span m=''2086980''>more</span> <span m=''2087430''>than</span>
  <span m=''2088830''>I''ve</span> <span m=''2089020''>said.</span> <span m=''2089940''>OK,</span>
  <span m=''2091090''>what</span> <span m=''2091380''>happens</span> <span m=''2091840''>if</span>
  <span m=''2092010''>I</span> <span m=''2092100''>do</span> <span m=''2092310''>elimination</span>
  <span m=''2093100''>on</span> <span m=''2093210''>that</span> <span m=''2093390''>matrix?</span>
  <span m=''2096400''>How</span> <span m=''2097250''>long</span> <span m=''2097560''>does</span>
  <span m=''2097730''>it</span> <span m=''2097850''>take,</span> <span m=''2098120''>how</span>
  <span m=''2098340''>fast</span> <span m=''2098800''>is</span> <span m=''2098940''>it?</span>
  <span m=''2099950''>Well,</span> <span m=''2101330''>MATLAB</span> <span m=''2101940''>will</span>
  <span m=''2102110''>take</span> <span m=''2102400''>advantage,</span> <span m=''2102960''>or</span>
  <span m=''2103070''>any</span> <span m=''2103350''>code,</span> <span m=''2103750''>will</span>
  <span m=''2103950''>take</span> <span m=''2104200''>advantage</span> <span m=''2104660''>of</span>
  <span m=''2104770''>all</span> <span m=''2105090''>these</span> <span m=''2105550''>zeroes,</span>
  <span m=''2106710''>right?</span> <span m=''2110610''>In</span> <span m=''2110760''>other</span>
  <span m=''2110950''>words,</span> <span m=''2111590''>what</span> <span m=''2112080''>do</span>
  <span m=''2112170''>I</span> <span m=''2112280''>mean</span> <span m=''2112520''>by</span>
  <span m=''2112670''>take</span> <span m=''2112960''>advantage?</span> <span m=''2114040''>And</span>
  <span m=''2114200''>what</span> <span m=''2114360''>do</span> <span m=''2114440''>I</span>
  <span m=''2114540''>mean</span> <span m=''2114760''>by</span> <span m=''2114940''>elimination?</span>
  <span m=''2115670''>You</span> <span m=''2115770''>remember</span> <span m=''2116140''>I''m</span>
  <span m=''2116300''>going to</span> <span m=''2116570''>subtract</span> <span m=''2117290''>multiples</span>
  <span m=''2117950''>of</span> <span m=''2118090''>this</span> <span m=''2118370''>row.</span>
  <span m=''2119290''>There''ll</span> <span m=''2119450''>be</span> <span m=''2119580''>a</span>
  <span m=''2119660''>minus</span> <span m=''2120230''>one</span> <span m=''2120590''>below</span>
  <span m=''2120960''>it</span> <span m=''2121630''>on</span> <span m=''2121850''>this</span>
  <span m=''2123710''>guy.</span> <span m=''2124370''>This</span> <span m=''2124800''>row</span>
  <span m=''2125230''>that</span> <span m=''2125470''>has</span> <span m=''2126180''>some</span>
  <span m=''2126720''>fours</span> <span m=''2126970''>and</span> <span m=''2127180''>some</span>
  <span m=''2127400''>minus</span> <span m=''2127780''>ones,</span> <span m=''2128210''>whatever.</span>
  <span m=''2129590''>Elimination,</span> <span m=''2130380''>I''m</span> <span m=''2130550''>subtracting</span>
  <span m=''2131370''>a</span> <span m=''2131450''>multiple</span> <span m=''2132040''>of</span>
  <span m=''2132150''>this</span> <span m=''2132410''>row</span> <span m=''2132900''>from</span>
  <span m=''2133220''>this</span> <span m=''2133480''>row</span> <span m=''2134400''>to</span>
  <span m=''2134610''>get</span> <span m=''2135040''>that</span> <span m=''2135450''>minus</span>
  <span m=''2135860''>one</span> <span m=''2136080''>to</span> <span m=''2136170''>be</span>
  <span m=''2136310''>a</span> <span m=''2136370''>zero,</span> <span m=''2136950''>right?</span>
  <span m=''2137470''>I''m</span> <span m=''2137570''>eliminating</span> <span m=''2138390''>this</span>
  <span m=''2138820''>entry</span> <span m=''2139270''>in</span> <span m=''2139400''>the</span>
  <span m=''2139490''>matrix.</span> <span m=''2140440''>This</span> <span m=''2140600''>is</span>
  <span m=''2140750''>ordinary</span> <span m=''2141540''>LU,</span> <span m=''2142170''>this</span>
  <span m=''2142330''>is</span> <span m=''2142460''>ordinary</span> <span m=''2142970''>LU</span>
  <span m=''2143200''>of</span> <span m=''2145330''>K2D.</span> <span m=''2147580''>I''m</span>
  <span m=''2147740''>sort</span> <span m=''2147980''>of</span> <span m=''2148080''>thinking</span>
  <span m=''2148640''>through</span> <span m=''2149060''>LU</span> <span m=''2149530''>of</span>
  <span m=''2149930''>K2D.</span> <span m=''2151210''>And</span> <span m=''2151420''>what</span>
  <span m=''2151650''>I''m</span> <span m=''2151800''>going</span> <span m=''2151980''>to</span>
  <span m=''2152090''>conclude</span> <span m=''2152750''>is</span> <span m=''2153760''>that</span>
  <span m=''2154040''>there</span> <span m=''2154180''>ought</span> <span m=''2154350''>to</span>
  <span m=''2154430''>be</span> <span m=''2154540''>a</span> <span m=''2154600''>better</span>
  <span m=''2154860''>way.</span> <span m=''2156040''>It''s</span> <span m=''2156250''>such</span>
  <span m=''2156590''>a</span> <span m=''2156680''>special</span> <span m=''2157130''>matrix,</span>
  <span m=''2158040''>and</span> <span m=''2158400''>it''s</span> <span m=''2158560''>going</span>
  <span m=''2158750''>to</span> <span m=''2158810''>be</span> <span m=''2158970''>messed</span>
  <span m=''2159460''>up</span> <span m=''2159790''>by</span> <span m=''2159890''>LU.</span>
  <span m=''2160490''>And</span> <span m=''2160680''>what</span> <span m=''2160850''>do</span>
  <span m=''2160940''>I</span> <span m=''2161080''>mean</span> <span m=''2161340''>by</span>
  <span m=''2161510''>messed</span> <span m=''2161900''>up?</span> <span m=''2162470''>I</span>
  <span m=''2162780''>mean</span> <span m=''2163340''>that</span> <span m=''2163680''>all</span>
  <span m=''2163970''>these</span> <span m=''2164300''>great</span> <span m=''2164670''>zeroes,</span>
  <span m=''2166400''>990-something</span> <span m=''2168120''>zeroes</span> <span
  m=''2168730''>there</span> <span m=''2169170''>and</span> <span m=''2169330''>there,</span>
  <span m=''2169760''>inside</span> <span m=''2170400''>the</span> <span m=''2170480''>band,</span>
  <span m=''2174900''>are</span> <span m=''2175070''>going</span> <span m=''2175240''>to</span>
  <span m=''2175310''>fill in.</span> <span m=''2176950''>That''s</span> <span m=''2177400''>the</span>
  <span m=''2177570''>message,</span> <span m=''2178460''>if</span> <span m=''2178770''>you</span>
  <span m=''2178880''>want to</span> <span m=''2179220''>talk</span> <span m=''2179670''>about</span>
  <span m=''2180430''>solving</span> <span m=''2181240''>large</span> <span m=''2181940''>linear</span>
  <span m=''2182180''>systems,</span> <span m=''2183660''>the</span> <span m=''2183930''>big</span>
  <span m=''2184470''>issue</span> <span m=''2184930''>is</span> <span m=''2185790''>fill</span>
  <span m=''2186180''>in.</span> <span m=''2187560''>It''s</span> <span m=''2187780''>a</span>
  <span m=''2187870''>sparse</span> <span m=''2188430''>matrix.</span> <span m=''2189200''>That''s</span>
  <span m=''2189490''>typical.</span> <span m=''2190490''>We</span> <span m=''2190650''>have</span>
  <span m=''2190810''>a</span> <span m=''2190920''>local</span> <span m=''2191560''>operator</span>
  <span m=''2192140''>here,</span> <span m=''2192530''>so</span> <span m=''2192730''>we</span>
  <span m=''2193030''>expect</span> <span m=''2193650''>a very</span> <span m=''2193870''>local,</span>
  <span m=''2194550''>sparse</span> <span m=''2195060''>matrix.</span> <span m=''2196080''>Large</span>
  <span m=''2196710''>sparse</span> <span m=''2197210''>matrices</span> <span m=''2197900''>is</span>
  <span m=''2198090''>what</span> <span m=''2198320''>we''re</span> <span m=''2198460''>doing</span>
  <span m=''2198800''>now.</span> <span m=''2199560''>And</span> <span m=''2200810''>the</span>
  <span m=''2201080''>problem</span> <span m=''2201680''>is</span> <span m=''2202240''>that--</span>
  <span m=''2203050''>Zeroes</span> <span m=''2203980''>here</span> <span m=''2204470''>will</span>
  <span m=''2204630''>never</span> <span m=''2204860''>get</span> <span m=''2205180''>touched</span>
  <span m=''2205580''>because</span> <span m=''2206570''>we</span> <span m=''2206780''>don''t</span>
  <span m=''2207000''>need</span> <span m=''2207230''>any</span> <span m=''2207450''>elimination,</span>
  <span m=''2208290''>they''re</span> <span m=''2208470''>already</span> <span m=''2208860''>zero.</span>
  <span m=''2209630''>But</span> <span m=''2209860''>all</span> <span m=''2211460''>this</span>
  <span m=''2212170''>diagonal</span> <span m=''2212980''>of minus</span> <span m=''2213450''>ones</span>
  <span m=''2214040''>when</span> <span m=''2214290''>we</span> <span m=''2214410''>do</span>
  <span m=''2214680''>eliminations</span> <span m=''2215560''>to</span> <span m=''2216050''>make</span>
  <span m=''2216340''>those</span> <span m=''2216660''>zero,</span> <span m=''2217470''>then</span>
  <span m=''2217740''>some</span> <span m=''2218030''>non-zeroes</span> <span m=''2218730''>are</span>
  <span m=''2218910''>going to</span> <span m=''2219250''>come</span> <span m=''2219490''>in</span>
  <span m=''2219730''>and</span> <span m=''2219970''>fill</span> <span m=''2220050''>in</span>
  <span m=''2220280''>the</span> <span m=''2220480''>zeroes.</span> </p><p><span m=''2223920''>So</span>
  <span m=''2224300''>the</span> <span m=''2224470''>work,</span> <span m=''2225270''>how</span>
  <span m=''2225430''>much</span> <span m=''2225650''>work</span> <span m=''2225980''>would</span>
  <span m=''2226140''>elimination</span> <span m=''2226930''>be,</span> <span m=''2227240''>actually?</span>
  <span m=''2227720''>We</span> <span m=''2227880''>could</span> <span m=''2228060''>even</span>
  <span m=''2228370''>think</span> <span m=''2228630''>about</span> <span m=''2228950''>that.</span>
  <span m=''2235540''>Can</span> <span m=''2235720''>I</span> <span m=''2235810''>just</span>
  <span m=''2236650''>give</span> <span m=''2236850''>the</span> <span m=''2236950''>result</span>
  <span m=''2237500''>for</span> <span m=''2237660''>how</span> <span m=''2238260''>much</span>
  <span m=''2238610''>time</span> <span m=''2239020''>would</span> <span m=''2239190''>elimination</span>
  <span m=''2239910''>take?</span> <span m=''2240970''>Ordinary</span> <span m=''2241470''>elimination.</span>
  <span m=''2242540''>So</span> <span m=''2242780''>I</span> <span m=''2242920''>have</span>
  <span m=''2243460''>N</span> <span m=''2243790''>squared</span> <span m=''2244280''>rows</span>
  <span m=''2245620''>to</span> <span m=''2245740''>work</span> <span m=''2246060''>on.</span>
  <span m=''2248320''>N</span> <span m=''2248630''>squared</span> <span m=''2249040''>rows</span>
  <span m=''2249480''>to</span> <span m=''2249600''>work</span> <span m=''2249980''>on,</span>
  <span m=''2250620''>and</span> <span m=''2251220''>then</span> <span m=''2252180''>the</span>
  <span m=''2252590''>distance,</span> <span m=''2253420''>that</span> <span m=''2253680''>distance</span>
  <span m=''2254250''>was</span> <span m=''2254740''>what</span> <span m=''2255070''>in</span>
  <span m=''2255220''>terms</span> <span m=''2255570''>of</span> <span m=''2255690''>N?</span>
  <span m=''2256680''>The</span> <span m=''2256810''>width</span> <span m=''2257200''>there</span>
  <span m=''2257810''>is?</span> <span m=''2258330''>N,</span> <span m=''2259640''>right?</span>
  <span m=''2259990''>It was</span> <span m=''2260120''>about</span> <span m=''2260360''>1,000.</span>
  <span m=''2261660''>So</span> <span m=''2262820''>I</span> <span m=''2262960''>get</span>
  <span m=''2263240''>N</span> <span m=''2263600''>numbers</span> <span m=''2263960''>here</span>
  <span m=''2264390''>and</span> <span m=''2264500''>I</span> <span m=''2264560''>have</span>
  <span m=''2264760''>to</span> <span m=''2264880''>work</span> <span m=''2265290''>on</span>
  <span m=''2265780''>N</span> <span m=''2266130''>numbers</span> <span m=''2266590''>below.</span>
  <span m=''2272540''>To</span> <span m=''2272670''>clean</span> <span m=''2273010''>up</span>
  <span m=''2273200''>a</span> <span m=''2273270''>column</span> <span m=''2274510''>I''m</span>
  <span m=''2274730''>working</span> <span m=''2275240''>with</span> <span m=''2275370''>a</span>
  <span m=''2275530''>vector</span> <span m=''2276470''>of</span> <span m=''2276670''>length
  N</span> <span m=''2276990''>and</span> <span m=''2277470''>I''m</span> <span m=''2277620''>subtracting</span>
  <span m=''2278230''>it</span> <span m=''2278540''>from</span> <span m=''2278730''>N</span>
  <span m=''2279580''>rows</span> <span m=''2280410''>below.</span> <span m=''2281670''>So</span>
  <span m=''2281870''>cleaning</span> <span m=''2282410''>up</span> <span m=''2282560''>a</span>
  <span m=''2282710''>column</span> <span m=''2283240''>takes</span> <span m=''2283560''>me</span>
  <span m=''2283760''>N</span> <span m=''2284000''>squared</span> <span m=''2284360''>operation.</span>
  <span m=''2285620''>The</span> <span m=''2286230''>total</span> <span m=''2286480''>then</span>
  <span m=''2286900''>is</span> <span m=''2287260''>N^4.</span> <span m=''2290150''>N^4,</span>
  <span m=''2291250''>for</span> <span m=''2291560''>elimination.</span> <span m=''2294370''>And</span>
  <span m=''2294720''>that''s</span> <span m=''2295000''>not</span> <span m=''2295280''>acceptable.</span>
  <span m=''2296170''>Right?</span> <span m=''2296730''>If</span> <span m=''2296930''>N</span>
  <span m=''2297090''>is</span> <span m=''2297240''>1,000,</span> <span m=''2298490''>I''m</span>
  <span m=''2298730''>up</span> <span m=''2298940''>to</span> <span m=''2299080''>10^12.</span>
  <span m=''2300970''>So</span> <span m=''2301570''>elimination</span> <span m=''2302330''>is</span>
  <span m=''2302580''>not</span> <span m=''2302880''>a</span> <span m=''2302960''>good</span>
  <span m=''2303190''>way</span> <span m=''2303900''>to solve--</span> <span m=''2305010''>Elimination,</span>
  <span m=''2308110''>in</span> <span m=''2308400''>this</span> <span m=''2308690''>ordering,</span>
  <span m=''2309200''>ha.</span> <span m=''2310830''>Yeah.</span> <span m=''2311650''>So</span>
  <span m=''2312930''>can</span> <span m=''2313090''>I</span> <span m=''2313200''>tell</span>
  <span m=''2313400''>you</span> <span m=''2313570''>two</span> <span m=''2313890''>ways,</span>
  <span m=''2314640''>two</span> <span m=''2314820''>better</span> <span m=''2315160''>ways</span>
  <span m=''2316520''>to</span> <span m=''2316680''>deal</span> <span m=''2316930''>with</span>
  <span m=''2317110''>this</span> <span m=''2317310''>problem?</span> <span m=''2319590''>So</span>
  <span m=''2320340''>two</span> <span m=''2320530''>better</span> <span m=''2320820''>ways</span>
  <span m=''2321140''>to</span> <span m=''2321260''>deal</span> <span m=''2321470''>with</span>
  <span m=''2321640''>this</span> <span m=''2321880''>problem.</span> <span m=''2322930''>One</span>
  <span m=''2323320''>is,</span> <span m=''2324830''>and</span> <span m=''2325030''>MATLAB</span>
  <span m=''2327300''>have</span> <span m=''2327570''>a</span> <span m=''2327730''>code</span>
  <span m=''2328150''>that</span> <span m=''2328310''>would</span> <span m=''2328590''>do</span>
  <span m=''2328840''>it,</span> <span m=''2329600''>one</span> <span m=''2330080''>is</span>
  <span m=''2330480''>to</span> <span m=''2331120''>change</span> <span m=''2331760''>from</span>
  <span m=''2331980''>this</span> <span m=''2333260''>ordering</span> <span m=''2333920''>one,</span>
  <span m=''2334110''>two,</span> <span m=''2334330''>three,</span> <span m=''2334690''>four,</span>
  <span m=''2334930''>five,</span> <span m=''2335220''>six,</span> <span m=''2335570''>seven,</span>
  <span m=''2335930''>eight,</span> <span m=''2336150''>nine,</span> <span m=''2338120''>change</span>
  <span m=''2338780''>to</span> <span m=''2338900''>a</span> <span m=''2338990''>different</span>
  <span m=''2339480''>ordering</span> <span m=''2340020''>that</span> <span m=''2340640''>had</span>
  <span m=''2340840''>less</span> <span m=''2341120''>fill-in.</span> <span m=''2343360''>So</span>
  <span m=''2343580''>that''s</span> <span m=''2343930''>a</span> <span m=''2344570''>substantial</span>
  <span m=''2345480''>part</span> <span m=''2346020''>of</span> <span m=''2347240''>scientific</span>
  <span m=''2347890''>computing.</span> <span m=''2349550''>Is</span> <span m=''2349980''>to</span>
  <span m=''2352510''>re-order</span> <span m=''2353580''>the</span> <span m=''2353730''>unknowns.</span>
  <span m=''2355340''>To</span> <span m=''2356920''>reduce</span> <span m=''2357490''>the</span>
  <span m=''2357640''>number</span> <span m=''2358170''>of</span> <span m=''2358560''>wasted,</span>
  <span m=''2359680''>fill-in</span> <span m=''2360530''>things</span> <span m=''2360910''>that</span>
  <span m=''2361060''>you</span> <span m=''2361180''>have</span> <span m=''2361330''>to</span>
  <span m=''2361470''>fill</span> <span m=''2361720''>in,</span> <span m=''2361870''>and</span>
  <span m=''2362020''>then</span> <span m=''2362160''>you</span> <span m=''2362270''>have</span>
  <span m=''2362500''>to</span> <span m=''2362840''>eliminate</span> <span m=''2363420''>out</span>
  <span m=''2363630''>again.</span> <span m=''2365080''>And</span> <span m=''2365420''>I</span>
  <span m=''2365520''>can</span> <span m=''2365780''>get</span> <span m=''2366010''>that</span>
  <span m=''2366240''>N^4</span> <span m=''2366960''>down</span> <span m=''2367760''>quite</span>
  <span m=''2368130''>a</span> <span m=''2368190''>bit</span> <span m=''2368460''>that</span>
  <span m=''2368700''>way.</span> <span m=''2369990''>OK,</span> <span m=''2370360''>so</span>
  <span m=''2370590''>that''s</span> <span m=''2370910''>a</span> <span m=''2371010''>topic</span>
  <span m=''2371930''>of</span> <span m=''2373270''>importance</span> <span m=''2374090''>in</span>
  <span m=''2376040''>scientific</span> <span m=''2376630''>computing.</span> <span
  m=''2377470''>Is</span> <span m=''2378650''>given</span> <span m=''2379020''>a</span>
  <span m=''2379120''>large</span> <span m=''2379570''>linear</span> <span m=''2379900''>system,</span>
  <span m=''2381210''>put</span> <span m=''2381520''>the</span> <span m=''2381650''>rows</span>
  <span m=''2382120''>and</span> <span m=''2382310''>columns</span> <span m=''2382790''>in</span>
  <span m=''2382920''>a</span> <span m=''2382980''>good</span> <span m=''2383240''>order.</span>
  <span m=''2384260''>OK,</span> <span m=''2385230''>and</span> <span m=''2385510''>that''s</span>
  <span m=''2385730''>something</span> <span m=''2386080''>you</span> <span m=''2386170''>hope</span>
  <span m=''2386430''>the</span> <span m=''2386510''>machine</span> <span m=''2386990''>can</span>
  <span m=''2387160''>do.</span> <span m=''2387330''>The</span> <span m=''2387460''>machine</span>
  <span m=''2388070''>will</span> <span m=''2388470''>have</span> <span m=''2388760''>a</span>
  <span m=''2389300''>record</span> <span m=''2389950''>of</span> <span m=''2390750''>where</span>
  <span m=''2391080''>are</span> <span m=''2391300''>the</span> <span m=''2391440''>non-zeroes.</span>
  <span m=''2393030''>And</span> <span m=''2393310''>then</span> <span m=''2393530''>so</span>
  <span m=''2393690''>you</span> <span m=''2393820''>run</span> <span m=''2394100''>the</span>
  <span m=''2394180''>little,</span> <span m=''2394920''>you</span> <span m=''2395120''>really</span>
  <span m=''2395400''>run</span> <span m=''2395670''>the</span> <span m=''2395770''>program</span>
  <span m=''2396270''>twice.</span> <span m=''2397080''>You</span> <span m=''2397250''>run</span>
  <span m=''2397580''>it</span> <span m=''2397730''>once</span> <span m=''2399100''>without</span>
  <span m=''2399550''>using</span> <span m=''2399950''>the</span> <span m=''2400050''>numbers.</span>
  <span m=''2400690''>Just</span> <span m=''2401150''>the</span> <span m=''2401250''>positions</span>
  <span m=''2402080''>of</span> <span m=''2402250''>non-zeroes</span> <span m=''2403130''>to</span>
  <span m=''2403450''>get a</span> <span m=''2403940''>good</span> <span m=''2404220''>ordering</span>
  <span m=''2405130''>so</span> <span m=''2405390''>that</span> <span m=''2406340''>the</span>
  <span m=''2406790''>number</span> <span m=''2407150''>of</span> <span m=''2407250''>elimination</span>
  <span m=''2407970''>steps</span> <span m=''2408310''>will</span> <span m=''2408420''>be</span>
  <span m=''2408570''>way</span> <span m=''2408960''>down.</span> <span m=''2409920''>And</span>
  <span m=''2410270''>then</span> <span m=''2410430''>you</span> <span m=''2410540''>run</span>
  <span m=''2410790''>it</span> <span m=''2410900''>with</span> <span m=''2411080''>the</span>
  <span m=''2411170''>numbers</span> <span m=''2412230''>in</span> <span m=''2412440''>that</span>
  <span m=''2412670''>good</span> <span m=''2412910''>order</span> <span m=''2413500''>to</span>
  <span m=''2413640''>do</span> <span m=''2413820''>the</span> <span m=''2413970''>elimination.</span>
  <span m=''2415340''>So</span> <span m=''2415510''>that''s</span> <span m=''2416190''>a</span>
  <span m=''2416330''>topic</span> <span m=''2416920''>of,</span> <span m=''2418600''>one</span>
  <span m=''2419030''>topic</span> <span m=''2420150''>in</span> <span m=''2420360''>this.</span>
  <span m=''2421190''>But.</span> <span m=''2423440''>Today''s</span> <span m=''2423920''>topic</span>
  <span m=''2425300''>is</span> <span m=''2427830''>using</span> <span m=''2428590''>the</span>
  <span m=''2428720''>fact</span> <span m=''2429120''>that</span> <span m=''2429250''>this</span>
  <span m=''2429470''>is</span> <span m=''2429600''>a</span> <span m=''2429720''>square.</span>
  <span m=''2431310''>That</span> <span m=''2431510''>this</span> <span m=''2431780''>matrix</span>
  <span m=''2432310''>has</span> <span m=''2432500''>a</span> <span m=''2432610''>special</span>
  <span m=''2433120''>form.</span> <span m=''2434290''>That</span> <span m=''2434460''>we</span>
  <span m=''2434620''>can</span> <span m=''2434810''>actually</span> <span m=''2435170''>find</span>
  <span m=''2435540''>its</span> <span m=''2435890''>eigenvalues</span> <span m=''2436560''>and</span>
  <span m=''2436850''>eigenvectors.</span> <span m=''2438150''>And</span> <span m=''2438420''>that''s</span>
  <span m=''2438750''>what</span> <span m=''2438970''>makes</span> <span m=''2439620''>a</span>
  <span m=''2439800''>fast</span> <span m=''2440340''>Poisson</span> <span m=''2440820''>solver.</span>
  <span m=''2441270''>So</span> <span m=''2442640''>that''s</span> <span m=''2442930''>the</span>
  <span m=''2443060''>topic</span> <span m=''2443490''>of</span> <span m=''2443590''>the</span>
  <span m=''2443700''>lecture</span> <span m=''2444020''>and</span> <span m=''2444300''>the</span>
  <span m=''2444420''>topic</span> <span m=''2444880''>of</span> <span m=''2444970''>the</span>
  <span m=''2445110''>next</span> <span m=''2445480''>section</span> <span m=''2445950''>in</span>
  <span m=''2446090''>the</span> <span m=''2446180''>book.</span> <span m=''2446820''>And</span>
  <span m=''2447080''>I</span> <span m=''2447760''>will</span> <span m=''2447980''>get</span>
  <span m=''2448160''>started</span> <span m=''2448620''>on</span> <span m=''2448820''>it</span>
  <span m=''2448940''>now,</span> <span m=''2449430''>and</span> <span m=''2449610''>then</span>
  <span m=''2450740''>complete it</span> <span m=''2451380''>Wednesday.</span> <span
  m=''2452750''>So</span> <span m=''2452990''>I</span> <span m=''2453160''>want</span>
  <span m=''2453540''>to</span> <span m=''2454000''>take</span> <span m=''2454260''>this</span>
  <span m=''2454510''>particular</span> <span m=''2455200''>K2D</span> <span m=''2456130''>for</span>
  <span m=''2456370''>a</span> <span m=''2456460''>square</span> <span m=''2458060''>and</span>
  <span m=''2458430''>show</span> <span m=''2459240''>a</span> <span m=''2459550''>different</span>
  <span m=''2460040''>way</span> <span m=''2460720''>to</span> <span m=''2460940''>solve</span>
  <span m=''2462340''>the</span> <span m=''2462580''>equations</span> <span m=''2464050''>that</span>
  <span m=''2464600''>uses</span> <span m=''2465120''>the</span> <span m=''2465240''>fast</span>
  <span m=''2465550''>Fourier</span> <span m=''2465730''>transform.</span> <span m=''2466880''>When</span>
  <span m=''2467120''>I</span> <span m=''2467310''>see,</span> <span m=''2468540''>when</span>
  <span m=''2468970''>you</span> <span m=''2469180''>see,</span> <span m=''2470260''>a</span>
  <span m=''2470460''>regular</span> <span m=''2471290''>mesh,</span> <span m=''2472800''>regular</span>
  <span m=''2473550''>numbers,</span> <span m=''2474550''>nothing</span> <span m=''2475210''>varying,</span>
  <span m=''2476310''>constant</span> <span m=''2476930''>diagonals,</span> <span
  m=''2479440''>think</span> <span m=''2479880''>fast</span> <span m=''2480370''>Fourier</span>
  <span m=''2480740''>transform.</span> <span m=''2481480''>The</span> <span m=''2481630''>FFT</span>
  <span m=''2482230''>has</span> <span m=''2482380''>got</span> <span m=''2482640''>a</span>
  <span m=''2482710''>chance</span> <span m=''2483320''>when</span> <span m=''2483500''>you</span>
  <span m=''2483600''>have</span> <span m=''2483810''>matrices</span> <span m=''2484520''>like</span>
  <span m=''2484770''>this</span> <span m=''2485000''>one.</span> <span m=''2485860''>And</span>
  <span m=''2486710''>this</span> <span m=''2487470''>I</span> <span m=''2487570''>want</span>
  <span m=''2487770''>to</span> <span m=''2487830''>show</span> <span m=''2488050''>you</span>
  <span m=''2488190''>how</span> <span m=''2488420''>it</span> <span m=''2488520''>works.</span>
  <span m=''2492630''>I</span> <span m=''2492720''>want</span> <span m=''2492910''>to</span>
  <span m=''2492980''>show</span> <span m=''2493180''>you</span> <span m=''2493570''>the</span>
  <span m=''2493710''>underlying</span> <span m=''2494330''>idea,</span> <span m=''2494880''>and
  then</span> <span m=''2495140''>we''ll</span> <span m=''2495350''>see</span> <span
  m=''2495870''>the</span> <span m=''2496050''>details</span> <span m=''2496640''>of</span>
  <span m=''2496750''>the</span> <span m=''2496860''>fast</span> <span m=''2497180''>Fourier</span>
  <span m=''2497470''>transform</span> <span m=''2498110''>in</span> <span m=''2498370''>the</span>
  <span m=''2498640''>Fourier</span> <span m=''2499390''>section.</span> <span m=''2500180''>So,</span>
  <span m=''2500450''>of</span> <span m=''2500610''>course,</span> <span m=''2500840''>everybody</span>
  <span m=''2501250''>knows</span> <span m=''2501670''>the</span> <span m=''2501790''>third</span>
  <span m=''2502290''>part</span> <span m=''2502540''>of</span> <span m=''2502650''>this</span>
  <span m=''2502850''>course,</span> <span m=''2503700''>which</span> <span m=''2503970''>is</span>
  <span m=''2504150''>coming</span> <span m=''2504440''>up</span> <span m=''2505810''>next</span>
  <span m=''2506150''>week,</span> <span m=''2506470''>we''ll</span> <span m=''2506630''>be</span>
  <span m=''2506920''>well</span> <span m=''2507480''>into</span> <span m=''2507810''>it,</span>
  <span m=''2508510''>is</span> <span m=''2510140''>the</span> <span m=''2510270''>Fourier</span>
  <span m=''2510700''>part.</span> <span m=''2511600''>OK.</span> <span m=''2512200''>But</span>
  <span m=''2512850''>I</span> <span m=''2512980''>can</span> <span m=''2513270''>give</span>
  <span m=''2513540''>you,</span> <span m=''2513920''>because</span> <span m=''2514370''>we''ve</span>
  <span m=''2514600''>seen</span> <span m=''2515000''>the</span> <span m=''2515120''>eigenvectors</span>
  <span m=''2515320''>and</span> <span m=''2515660''>eigenvalues</span> <span m=''2516490''>of</span>
  <span m=''2516700''>K,</span> <span m=''2518000''>I</span> <span m=''2518210''>can</span>
  <span m=''2518880''>do</span> <span m=''2519070''>this</span> <span m=''2519570''>now.</span>
  <span m=''2520670''>Ready</span> <span m=''2520940''>for</span> <span m=''2522570''>the</span>
  <span m=''2522720''>smart</span> <span m=''2523070''>idea?</span> </p><p><span m=''2524590''>The</span>
  <span m=''2524770''>good</span> <span m=''2525070''>way,</span> <span m=''2525490''>and</span>
  <span m=''2525730''>it</span> <span m=''2525830''>only</span> <span m=''2526100''>works</span>
  <span m=''2526540''>because</span> <span m=''2527000''>this</span> <span m=''2527250''>is</span>
  <span m=''2527430''>a</span> <span m=''2527810''>square,</span> <span m=''2528530''>because</span>
  <span m=''2528890''>the</span> <span m=''2528990''>coefficients</span> <span m=''2529600''>are</span>
  <span m=''2529720''>constant,</span> <span m=''2530370''>because</span> <span m=''2531070''>everything''s</span>
  <span m=''2531670''>beautiful,</span> <span m=''2533150''>here''s</span> <span m=''2533510''>the</span>
  <span m=''2533610''>idea.</span> <span m=''2534460''>OK.</span> <span m=''2536620''>Central
  idea.</span> <span m=''2546340''>The</span> <span m=''2546500''>idea</span> <span
  m=''2547120''>is,</span> <span m=''2548790''>so</span> <span m=''2548970''>I</span>
  <span m=''2549050''>have</span> <span m=''2549160''>this</span> <span m=''2549360''>matrix</span>
  <span m=''2549840''>K2D</span> <span m=''2551370''>and</span> <span m=''2551580''>I''m</span>
  <span m=''2551710''>trying</span> <span m=''2552080''>to</span> <span m=''2552440''>solve</span>
  <span m=''2552840''>a</span> <span m=''2552920''>system</span> <span m=''2553320''>with</span>
  <span m=''2553490''>that</span> <span m=''2553870''>particular</span> <span m=''2554500''>matrix.</span>
  <span m=''2555610''>And</span> <span m=''2555890''>the</span> <span m=''2555970''>fantastic</span>
  <span m=''2556710''>thing</span> <span m=''2556910''>about</span> <span m=''2557220''>this</span>
  <span m=''2557560''>matrix</span> <span m=''2558250''>is</span> <span m=''2559160''>that</span>
  <span m=''2559930''>I</span> <span m=''2560300''>know</span> <span m=''2561350''>what</span>
  <span m=''2561650''>its</span> <span m=''2562030''>eigenvalues</span> <span m=''2562780''>and</span>
  <span m=''2563340''>eigenvectors</span> <span m=''2563810''>are.</span> <span m=''2564470''>So</span>
  <span m=''2564650''>let''s</span> <span m=''2564910''>suppose</span> <span m=''2565380''>we</span>
  <span m=''2565540''>know</span> <span m=''2565730''>them.</span> <span m=''2567070''>So</span>
  <span m=''2567250''>I</span> <span m=''2567360''>know</span> <span m=''2568370''>(K2D)y</span>
  <span m=''2570960''>=</span> <span m=''2572290''>lambda*y.</span> <span m=''2575040''>y</span>
  <span m=''2575550''>is</span> <span m=''2575690''>an</span> <span m=''2575820''>eigenvector,</span>
  <span m=''2576550''>and</span> <span m=''2576860''>remember</span> <span m=''2577140''>it''s</span>
  <span m=''2577350''>got</span> <span m=''2577560''>N</span> <span m=''2577770''>squared</span>
  <span m=''2578080''>components.</span> <span m=''2579430''>Lambda''s</span> <span
  m=''2580080''>a</span> <span m=''2580150''>number.</span> <span m=''2581420''>And</span>
  <span m=''2581690''>I''ve</span> <span m=''2581840''>got</span> <span m=''2582040''>a</span>
  <span m=''2582070''>whole</span> <span m=''2582360''>lot</span> <span m=''2582600''>of</span>
  <span m=''2582690''>these,</span> <span m=''2583380''>y_k,</span> <span m=''2584910''>lambda_k,</span>
  <span m=''2586120''>y_k.</span> <span m=''2587710''>And</span> <span m=''2587920''>I''ve</span>
  <span m=''2588100''>got</span> <span m=''2588460''>k</span> <span m=''2588850''>going</span>
  <span m=''2589210''>from</span> <span m=''2589440''>one</span> <span m=''2589730''>up
  to</span> <span m=''2590700''>N</span> <span m=''2591010''>squared.</span> <span
  m=''2596850''>Now</span> <span m=''2597160''>I</span> <span m=''2597230''>want</span>
  <span m=''2597460''>to</span> <span m=''2597520''>use</span> <span m=''2597810''>them.</span>
  <span m=''2599340''>I</span> <span m=''2599500''>want to</span> <span m=''2599790''>use</span>
  <span m=''2600110''>them</span> <span m=''2600440''>to</span> <span m=''2601030''>solve</span>
  <span m=''2603010''>(K2D)u=f.</span> <span m=''2607900''>Let</span> <span m=''2608030''>me</span>
  <span m=''2608140''>say,</span> <span m=''2609690''>it''s</span> <span m=''2610050''>totally</span>
  <span m=''2610610''>amazing</span> <span m=''2612100''>that</span> <span m=''2612560''>I</span>
  <span m=''2612770''>would,</span> <span m=''2613820''>in</span> <span m=''2614090''>fact</span>
  <span m=''2614360''>this</span> <span m=''2614520''>is</span> <span m=''2614640''>the</span>
  <span m=''2614760''>only</span> <span m=''2615200''>important</span> <span m=''2615630''>example</span>
  <span m=''2616070''>I</span> <span m=''2616180''>know</span> <span m=''2616400''>in</span>
  <span m=''2616530''>scientific</span> <span m=''2617110''>computing,</span> <span
  m=''2618810''>in</span> <span m=''2619030''>which</span> <span m=''2619540''>I</span>
  <span m=''2619770''>would</span> <span m=''2620070''>use</span> <span m=''2620580''>the</span>
  <span m=''2621240''>eigenvalues</span> <span m=''2621910''>and</span> <span m=''2622230''>eigenvectors</span>
  <span m=''2622980''>of</span> <span m=''2623100''>the</span> <span m=''2623180''>matrix</span>
  <span m=''2623760''>to</span> <span m=''2623930''>solve</span> <span m=''2624280''>a</span>
  <span m=''2624350''>linear</span> <span m=''2624720''>system.</span> <span m=''2626020''>You</span>
  <span m=''2626160''>see,</span> <span m=''2626350''>normally</span> <span m=''2626940''>you</span>
  <span m=''2627040''>think</span> <span m=''2627330''>of</span> <span m=''2627650''>eigenvalue</span>
  <span m=''2628080''>problems</span> <span m=''2628510''>as</span> <span m=''2628690''>like,</span>
  <span m=''2629020''>those</span> <span m=''2629260''>are</span> <span m=''2629360''>harder.</span>
  <span m=''2631350''>It''s</span> <span m=''2631840''>more</span> <span m=''2632020''>difficult</span>
  <span m=''2632850''>to</span> <span m=''2633020''>solve</span> <span m=''2633430''>this</span>
  <span m=''2633730''>problem</span> <span m=''2634490''>than</span> <span m=''2634740''>this</span>
  <span m=''2634970''>one.</span> <span m=''2635780''>Normally,</span> <span m=''2636390''>right?</span>
  <span m=''2636700''>That''s</span> <span m=''2637400''>the</span> <span m=''2637540''>way</span>
  <span m=''2638480''>to</span> <span m=''2638700''>think</span> <span m=''2638930''>about</span>
  <span m=''2639200''>it.</span> <span m=''2639670''>But</span> <span m=''2642820''>for</span>
  <span m=''2643010''>this</span> <span m=''2643270''>special</span> <span m=''2643730''>matrix,</span>
  <span m=''2645400''>we</span> <span m=''2645820''>can</span> <span m=''2646050''>figure</span>
  <span m=''2646440''>out</span> <span m=''2646720''>the</span> <span m=''2647030''>eigenvalues</span>
  <span m=''2647560''>and</span> <span m=''2647690''>eigenvectors</span> <span m=''2648380''>by</span>
  <span m=''2648530''>pencil</span> <span m=''2648980''>and</span> <span m=''2649120''>paper.</span>
  <span m=''2650690''>So</span> <span m=''2650920''>we</span> <span m=''2651680''>know</span>
  <span m=''2652540''>what</span> <span m=''2652790''>these</span> <span m=''2653060''>guys</span>
  <span m=''2653350''>are.</span> <span m=''2654640''>And</span> <span m=''2654940''>that</span>
  <span m=''2655270''>will</span> <span m=''2655510''>give</span> <span m=''2655760''>us</span>
  <span m=''2657810''>a</span> <span m=''2657940''>way</span> <span m=''2658310''>to</span>
  <span m=''2658500''>solve</span> <span m=''2659060''>a</span> <span m=''2659240''>linear</span>
  <span m=''2659530''>system.</span> <span m=''2660120''>So</span> <span m=''2660400''>can</span>
  <span m=''2660670''>I</span> <span m=''2660800''>remember,</span> <span m=''2661830''>this</span>
  <span m=''2662040''>is</span> <span m=''2662360''>now</span> <span m=''2662760''>central</span>
  <span m=''2664050''>message.</span> </p><p><span m=''2664800''>What</span> <span
  m=''2665220''>are</span> <span m=''2665340''>the</span> <span m=''2665490''>three</span>
  <span m=''2665920''>steps</span> <span m=''2668450''>that</span> <span m=''2668830''>to</span>
  <span m=''2668960''>use</span> <span m=''2671540''>eigenvectors</span> <span m=''2673160''>and</span>
  <span m=''2673290''>eigenvalues</span> <span m=''2674610''>in</span> <span m=''2676480''>solving</span>
  <span m=''2677520''>linear</span> <span m=''2678160''>equations,</span> <span m=''2679130''>in</span>
  <span m=''2679330''>solving</span> <span m=''2680070''>differential</span> <span
  m=''2680650''>equations,</span> <span m=''2681510''>in</span> <span m=''2681640''>solving</span>
  <span m=''2682180''>difference</span> <span m=''2682610''>equations,</span> <span
  m=''2683770''>they''re</span> <span m=''2684270''>always</span> <span m=''2684790''>the</span>
  <span m=''2684940''>same</span> <span m=''2685390''>three</span> <span m=''2685680''>steps.</span>
  <span m=''2686080''>Can</span> <span m=''2686260''>I</span> <span m=''2686800''>remember</span>
  <span m=''2687270''>what</span> <span m=''2687460''>those</span> <span m=''2687720''>three</span>
  <span m=''2687940''>steps</span> <span m=''2688290''>are?</span> <span m=''2689280''>So</span>
  <span m=''2690170''>step</span> <span m=''2690520''>one,</span> <span m=''2692130''>so</span>
  <span m=''2692380''>I''m</span> <span m=''2692760''>supposing</span> <span m=''2693350''>that</span>
  <span m=''2693530''>I</span> <span m=''2693620''>know</span> <span m=''2693890''>these</span>
  <span m=''2694160''>guys.</span> <span m=''2696360''>First</span> <span m=''2696720''>of</span>
  <span m=''2696810''>all,</span> <span m=''2696940''>that''s</span> <span m=''2697190''>amazing.</span>
  <span m=''2697900''>To</span> <span m=''2698040''>know</span> <span m=''2698230''>them</span>
  <span m=''2698420''>in</span> <span m=''2698530''>advance.</span> <span m=''2699680''>And</span>
  <span m=''2699880''>the</span> <span m=''2699980''>second</span> <span m=''2700410''>amazing</span>
  <span m=''2700910''>thing</span> <span m=''2701190''>is</span> <span m=''2701540''>that</span>
  <span m=''2701700''>they</span> <span m=''2701830''>have</span> <span m=''2702130''>beautiful</span>
  <span m=''2702950''>structure.</span> <span m=''2704490''>And</span> <span m=''2705120''>those</span>
  <span m=''2705910''>facts</span> <span m=''2706440''>make</span> <span m=''2706710''>it</span>
  <span m=''2706870''>possible</span> <span m=''2707540''>to</span> <span m=''2707700''>do</span>
  <span m=''2707890''>something</span> <span m=''2708280''>you</span> <span m=''2708400''>would</span>
  <span m=''2708590''>never</span> <span m=''2708990''>expect</span> <span m=''2709570''>to
  do.</span> <span m=''2710140''>Use</span> <span m=''2710640''>eigenvalues</span>
  <span m=''2711300''>for</span> <span m=''2711480''>a</span> <span m=''2711720''>linear</span>
  <span m=''2711870''>system.</span> <span m=''2712320''>So</span> <span m=''2712480''>here''s</span>
  <span m=''2712770''>the</span> <span m=''2712870''>way</span> <span m=''2713040''>to</span>
  <span m=''2713160''>do</span> <span m=''2713300''>it,</span> <span m=''2713450''>three</span>
  <span m=''2713760''>steps.</span> <span m=''2714550''>One,</span> <span m=''2715470''>expand</span>
  <span m=''2717630''>f</span> <span m=''2719470''>as</span> <span m=''2719740''>a</span>
  <span m=''2719830''>combination</span> <span m=''2720670''>of</span> <span m=''2720780''>the</span>
  <span m=''2720960''>eigenvectors,</span> <span m=''2721760''>c_1*y_1,</span> <span
  m=''2723130''>up</span> <span m=''2723290''>to</span> <span m=''2726040''>however</span>
  <span m=''2726500''>many</span> <span m=''2726820''>we''ve</span> <span m=''2727020''>got.</span>
  <span m=''2727620''>We''ve</span> <span m=''2727810''>got</span> <span m=''2728020''>N</span>
  <span m=''2728400''>squared</span> <span m=''2728720''>of</span> <span m=''2728900''>them.</span>
  <span m=''2730000''>Gosh,</span> <span m=''2730470''>we''re</span> <span m=''2731000''>loaded</span>
  <span m=''2731460''>with</span> <span m=''2731650''>eigenvectors.</span> <span m=''2733670''>Do</span>
  <span m=''2733830''>you</span> <span m=''2733890''>remember,</span> <span m=''2734200''>this</span>
  <span m=''2736290''>a</span> <span m=''2737010''>column</span> <span m=''2738230''>of</span>
  <span m=''2738470''>size</span> <span m=''2739310''>N</span> <span m=''2739590''>squared.</span>
  <span m=''2741270''>Our</span> <span m=''2741450''>problem</span> <span m=''2742070''>has</span>
  <span m=''2742320''>size</span> <span m=''2742650''>N</span> <span m=''2742860''>squared.</span>
  <span m=''2743530''>So</span> <span m=''2743700''>it''s</span> <span m=''2743850''>big,</span>
  <span m=''2744330''>a</span> <span m=''2744450''>million.</span> <span m=''2745940''>So</span>
  <span m=''2746150''>I''m</span> <span m=''2746380''>going</span> <span m=''2746580''>to</span>
  <span m=''2746660''>expand</span> <span m=''2747400''>f</span> <span m=''2747880''>in</span>
  <span m=''2748030''>terms</span> <span m=''2748430''>of</span> <span m=''2748560''>the</span>
  <span m=''2748710''>million</span> <span m=''2750090''>eigenvectors.</span> <span
  m=''2752660''>OK.</span> <span m=''2754170''>So</span> <span m=''2754360''>that</span>
  <span m=''2754570''>tells</span> <span m=''2754820''>me</span> <span m=''2754950''>the</span>
  <span m=''2755050''>right</span> <span m=''2755290''>hand</span> <span m=''2755510''>side.</span>
  <span m=''2756530''>Now,</span> <span m=''2756930''>you</span> <span m=''2757040''>remember</span>
  <span m=''2757410''>step</span> <span m=''2757820''>two</span> <span m=''2758470''>in</span>
  <span m=''2758650''>this</span> <span m=''2758960''>one,</span> <span m=''2759270''>two,</span>
  <span m=''2759530''>three</span> <span m=''2759930''>process?</span> </p><p><span
  m=''2761250''>Step</span> <span m=''2761560''>two</span> <span m=''2761790''>is</span>
  <span m=''2761950''>the</span> <span m=''2762060''>easy</span> <span m=''2762420''>one,</span>
  <span m=''2763930''>because</span> <span m=''2764820''>I</span> <span m=''2764990''>want
  to</span> <span m=''2765350''>get,</span> <span m=''2765700''>what</span> <span
  m=''2765970''>am</span> <span m=''2766090''>I</span> <span m=''2766190''>looking</span>
  <span m=''2766550''>for?</span> <span m=''2766890''>I''m</span> <span m=''2767340''>aiming</span>
  <span m=''2767800''>for,</span> <span m=''2768850''>of</span> <span m=''2769000''>course,</span>
  <span m=''2769320''>the</span> <span m=''2769430''>answer</span> <span m=''2769790''>I''m</span>
  <span m=''2770010''>aiming</span> <span m=''2770380''>for</span> <span m=''2770690''>is</span>
  <span m=''2771960''>K2D</span> <span m=''2772530''>inverse</span> <span m=''2772710''>f.</span>
  <span m=''2776070''>Right?</span> <span m=''2776430''>That''s</span> <span m=''2776740''>what</span>
  <span m=''2776940''>I''m</span> <span m=''2777070''>shooting</span> <span m=''2777430''>for.</span>
  <span m=''2777930''>That''s</span> <span m=''2780140''>my</span> <span m=''2780300''>goal,</span>
  <span m=''2780590''>that''s</span> <span m=''2780890''>the</span> <span m=''2781000''>solution.</span>
  <span m=''2782150''>So</span> <span m=''2783500''>here</span> <span m=''2783740''>I''ve</span>
  <span m=''2783910''>got</span> <span m=''2784150''>f</span> <span m=''2784660''>in</span>
  <span m=''2784760''>terms</span> <span m=''2785140''>of</span> <span m=''2785240''>the</span>
  <span m=''2785360''>eigenvectors.</span> <span m=''2787100''>Now</span> <span m=''2787420''>I</span>
  <span m=''2787560''>want to</span> <span m=''2787990''>get,</span> <span m=''2788360''>how</span>
  <span m=''2788640''>do</span> <span m=''2788760''>I</span> <span m=''2788860''>get</span>
  <span m=''2789090''>u</span> <span m=''2789320''>in</span> <span m=''2789460''>terms</span>
  <span m=''2789830''>of</span> <span m=''2789910''>the</span> <span m=''2790010''>eigenvectors?</span>
  <span m=''2792950''>Well,</span> <span m=''2795120''>what''s</span> <span m=''2795310''>the</span>
  <span m=''2796180''>eigenvalue</span> <span m=''2796940''>for</span> <span m=''2797170''>the</span>
  <span m=''2797350''>inverse,</span> <span m=''2798230''>for</span> <span m=''2798490''>K2D</span>
  <span m=''2798950''>inverse?</span> <span m=''2799740''>Do</span> <span m=''2799830''>you</span>
  <span m=''2799910''>remember?</span> <span m=''2802050''>It''s</span> <span m=''2802300''>one</span>
  <span m=''2802660''>over.</span> <span m=''2803800''>It''s</span> <span m=''2804000''>one</span>
  <span m=''2804270''>over</span> <span m=''2804500''>the</span> <span m=''2804620''>eigenvalue,</span>
  <span m=''2805260''>right?</span> <span m=''2805530''>If</span> <span m=''2806200''>this</span>
  <span m=''2806460''>is</span> <span m=''2806670''>true,</span> <span m=''2807440''>then</span>
  <span m=''2807860''>this</span> <span m=''2808120''>will</span> <span m=''2808280''>be</span>
  <span m=''2808500''>true</span> <span m=''2808790''>with</span> <span m=''2809650''>lambda_k</span>
  <span m=''2809930''>inverse.</span> <span m=''2813090''>It''s</span> <span m=''2813360''>simple</span>
  <span m=''2813820''>and</span> <span m=''2813960''>I</span> <span m=''2814020''>won''t</span>
  <span m=''2814370''>stop</span> <span m=''2814900''>to</span> <span m=''2815030''>do</span>
  <span m=''2815180''>it,</span> <span m=''2815390''>but</span> <span m=''2815610''>we</span>
  <span m=''2815790''>could</span> <span m=''2816040''>come</span> <span m=''2816220''>back</span>
  <span m=''2816490''>to</span> <span m=''2816950''>it.</span> <span m=''2817660''>So</span>
  <span m=''2817890''>I</span> <span m=''2818040''>know</span> <span m=''2818480''>how</span>
  <span m=''2818660''>to</span> <span m=''2818770''>get</span> <span m=''2818960''>K2D</span>
  <span m=''2819480''>inverse.</span> <span m=''2821630''>So</span> <span m=''2821810''>that''s</span>
  <span m=''2822140''>what</span> <span m=''2822350''>I''m</span> <span m=''2822480''>going
  to</span> <span m=''2822730''>do.</span> <span m=''2823340''>I''m</span> <span m=''2823570''>going
  to</span> <span m=''2823860''>divide,</span> <span m=''2825170''>so</span> <span
  m=''2825390''>here''s the</span> <span m=''2825540''>fast</span> <span m=''2826040''>step.</span>
  <span m=''2826860''>Divide</span> <span m=''2828840''>c_k,</span> <span m=''2829790''>each</span>
  <span m=''2831850''>of</span> <span m=''2832300''>those</span> <span m=''2832600''>c_k''s,</span>
  <span m=''2833330''>by</span> <span m=''2833500''>lambda_k.</span> <span m=''2837440''>What</span>
  <span m=''2837640''>do</span> <span m=''2837730''>I</span> <span m=''2837820''>have</span>
  <span m=''2838080''>now?</span> <span m=''2838730''>I''ve</span> <span m=''2839050''>got</span>
  <span m=''2841780''>c_1/lambda_1*y_1</span> <span m=''2842340''>plus</span> <span
  m=''2845430''>c_(N squared),</span> <span m=''2846730''>the</span> <span m=''2846830''>last</span>
  <span m=''2847300''>guy</span> <span m=''2847700''>divided</span> <span m=''2848170''>by</span>
  <span m=''2848320''>its</span> <span m=''2848830''>eigenvalue</span> <span m=''2849790''>times</span>
  <span m=''2850050''>its</span> <span m=''2850700''>eigenvector.</span> <span m=''2854960''>And</span>
  <span m=''2855170''>that''s</span> <span m=''2855450''>the</span> <span m=''2855560''>answer.</span>
  <span m=''2857460''>Right,</span> <span m=''2857710''>that''s</span> <span m=''2857970''>the</span>
  <span m=''2858080''>correct</span> <span m=''2858490''>answer.</span> <span m=''2860300''>If</span>
  <span m=''2860570''>this</span> <span m=''2860920''>is</span> <span m=''2861110''>the</span>
  <span m=''2861260''>right</span> <span m=''2861490''>hand</span> <span m=''2861700''>side,</span>
  <span m=''2862960''>then</span> <span m=''2863280''>this</span> <span m=''2863750''>is</span>
  <span m=''2863970''>the</span> <span m=''2864090''>solution.</span> <span m=''2865320''>Because</span>
  <span m=''2865830''>why?</span> <span m=''2866640''>Because</span> <span m=''2866880''>when</span>
  <span m=''2867090''>I</span> <span m=''2867180''>multiply</span> <span m=''2867770''>this</span>
  <span m=''2867980''>solution</span> <span m=''2868740''>by</span> <span m=''2869040''>K2D</span>
  <span m=''2870400''>it</span> <span m=''2870650''>multiplies</span> <span m=''2871310''>every</span>
  <span m=''2871660''>eigenvector</span> <span m=''2872450''>by</span> <span m=''2872810''>the
  eigenvalue,</span> <span m=''2873570''>it</span> <span m=''2873710''>cancels</span>
  <span m=''2874370''>all</span> <span m=''2874650''>the</span> <span m=''2874780''>lambdas,</span>
  <span m=''2875710''>and</span> <span m=''2875900''>I</span> <span m=''2875970''>get</span>
  <span m=''2876180''>f.</span> <span m=''2877030''>Do</span> <span m=''2877120''>you</span>
  <span m=''2877200''>see--</span> <span m=''2877880''>I</span> <span m=''2877990''>can''t</span>
  <span m=''2878340''>raise</span> <span m=''2878610''>that</span> <span m=''2878800''>board,</span>
  <span m=''2879590''>I''m</span> <span m=''2879870''>sorry.</span> <span m=''2881570''>Can</span>
  <span m=''2882300''>you</span> <span m=''2882420''>see it</span> <span m=''2882750''>at</span>
  <span m=''2882890''>the</span> <span m=''2883020''>back?</span> <span m=''2884820''>Should</span>
  <span m=''2885090''>I</span> <span m=''2885140''>write</span> <span m=''2885400''>it</span>
  <span m=''2885550''>up</span> <span m=''2885760''>here</span> <span m=''2886020''>again,</span>
  <span m=''2886740''>because</span> <span m=''2887730''>everything</span> <span m=''2888310''>hinges</span>
  <span m=''2888710''>on</span> <span m=''2888890''>that.</span> <span m=''2889960''>The</span>
  <span m=''2890360''>final, the</span> <span m=''2891010''>answer</span> <span m=''2891460''>u,</span>
  <span m=''2892990''>the</span> <span m=''2893460''>K2D</span> <span m=''2893900''>inverse</span>
  <span m=''2894420''>f,</span> <span m=''2896620''>is</span> <span m=''2897510''>the</span>
  <span m=''2897690''>same</span> <span m=''2898380''>combination</span> <span m=''2899250''>that</span>
  <span m=''2899370''>gave</span> <span m=''2899730''>f.</span> <span m=''2900550''>But</span>
  <span m=''2900790''>I</span> <span m=''2900910''>divide</span> <span m=''2901510''>by</span>
  <span m=''2901700''>lambda_1,</span> <span m=''2903400''>c_2</span> <span m=''2903820''>y,</span>
  <span m=''2905100''>the</span> <span m=''2905550''>second</span> <span m=''2905720''>eigenvector</span>
  <span m=''2906290''>over</span> <span m=''2906630''>lambda_2</span> <span m=''2907470''>and</span>
  <span m=''2907620''>so</span> <span m=''2907890''>on.</span> <span m=''2908750''>Because</span>
  <span m=''2910080''>when</span> <span m=''2910310''>I</span> <span m=''2910440''>multiply</span>
  <span m=''2910830''>by</span> <span m=''2911030''>K2D,</span> <span m=''2913130''>multiplying</span>
  <span m=''2913600''>each</span> <span m=''2913890''>y,</span> <span m=''2914440''>each</span>
  <span m=''2914690''>eigenvector</span> <span m=''2915430''>will</span> <span m=''2915600''>bring</span>
  <span m=''2915860''>out</span> <span m=''2916060''>an</span> <span m=''2916150''>eigenvalue,</span>
  <span m=''2916570''>it will</span> <span m=''2917230''>cancel</span> <span m=''2917910''>that</span>
  <span m=''2918510''>and</span> <span m=''2918710''>I''ll</span> <span m=''2918880''>have</span>
  <span m=''2919420''>the</span> <span m=''2919540''>original</span> <span m=''2920040''>f.</span>
  <span m=''2921800''>So</span> <span m=''2922010''>do</span> <span m=''2922540''>you</span>
  <span m=''2922720''>see</span> <span m=''2923000''>that</span> <span m=''2923190''>those</span>
  <span m=''2923440''>are</span> <span m=''2923540''>the</span> <span m=''2923670''>steps?</span>
  </p><p><span m=''2925040''>The</span> <span m=''2925210''>steps</span> <span m=''2925620''>are,</span>
  <span m=''2926440''>you</span> <span m=''2926620''>have</span> <span m=''2926880''>to</span>
  <span m=''2927040''>do</span> <span m=''2927270''>a--</span> <span m=''2928590''>you</span>
  <span m=''2928730''>could</span> <span m=''2928910''>say</span> <span m=''2929250''>it''s</span>
  <span m=''2929460''>a</span> <span m=''2929540''>transform</span> <span m=''2930360''>into</span>
  <span m=''2930770''>eigenspace.</span> <span m=''2932130''>I</span> <span m=''2932310''>take</span>
  <span m=''2932640''>my</span> <span m=''2932840''>vector</span> <span m=''2933340''>in</span>
  <span m=''2933750''>physical</span> <span m=''2934270''>space,</span> <span m=''2935140''>it''s</span>
  <span m=''2935320''>got</span> <span m=''2935550''>its</span> <span m=''2935680''>N</span>
  <span m=''2936010''>squared</span> <span m=''2936280''>component.</span> <span m=''2937690''>At</span>
  <span m=''2938380''>physical</span> <span m=''2938880''>points.</span> <span m=''2941320''>I</span>
  <span m=''2941780''>express</span> <span m=''2942360''>it</span> <span m=''2942500''>in</span>
  <span m=''2942690''>eigenspace.</span> <span m=''2943780''>By</span> <span m=''2943930''>that</span>
  <span m=''2944210''>I</span> <span m=''2944340''>mean</span> <span m=''2944630''>it''s</span>
  <span m=''2944810''>a</span> <span m=''2944910''>combination</span> <span m=''2945600''>of</span>
  <span m=''2945690''>the</span> <span m=''2945800''>eigenvectors</span> <span m=''2946970''>and</span>
  <span m=''2947210''>now</span> <span m=''2947530''>the</span> <span m=''2947710''>N</span>
  <span m=''2947920''>squared</span> <span m=''2948690''>physical</span> <span m=''2949390''>values</span>
  <span m=''2949980''>are</span> <span m=''2950170''>N</span> <span m=''2950530''>squared</span>
  <span m=''2951680''>amplitudes,</span> <span m=''2953550''>or</span> <span m=''2954180''>amounts</span>
  <span m=''2954860''>of</span> <span m=''2955000''>each</span> <span m=''2955270''>eigenvector.</span>
  <span m=''2958170''>So</span> <span m=''2958340''>that</span> <span m=''2958850''>was</span>
  <span m=''2959040''>a,</span> <span m=''2959680''>that''s</span> <span m=''2959940''>the</span>
  <span m=''2960090''>Fourier</span> <span m=''2960490''>series</span> <span m=''2960960''>idea,</span>
  <span m=''2961530''>that''s</span> <span m=''2961850''>the</span> <span m=''2962270''>Fourier</span>
  <span m=''2962640''>transform</span> <span m=''2963350''>idea,</span> <span m=''2964280''>it</span>
  <span m=''2964500''>just appears</span> <span m=''2965300''>everywhere.</span> <span
  m=''2966260''>Express</span> <span m=''2967030''>the</span> <span m=''2967190''>function</span>
  <span m=''2968230''>in</span> <span m=''2968670''>the</span> <span m=''2968790''>good</span>
  <span m=''2969070''>basis.</span> <span m=''2970200''>We''re</span> <span m=''2970390''>using</span>
  <span m=''2970760''>these</span> <span m=''2971000''>good</span> <span m=''2971200''>functions.</span>
  <span m=''2972170''>In</span> <span m=''2972390''>these</span> <span m=''2972680''>good</span>
  <span m=''2972880''>functions,</span> <span m=''2973840''>the</span> <span m=''2973970''>answer</span>
  <span m=''2974310''>is</span> <span m=''2974440''>simple.</span> <span m=''2975430''>I''m</span>
  <span m=''2975630''>just</span> <span m=''2975920''>dividing</span> <span m=''2976580''>by</span>
  <span m=''2977110''>lambda.</span> <span m=''2978440''>Do</span> <span m=''2978520''>you</span>
  <span m=''2978610''>see</span> <span m=''2978830''>that</span> <span m=''2978980''>I''m</span>
  <span m=''2979130''>just</span> <span m=''2979390''>dividing</span> <span m=''2979790''>by</span>
  <span m=''2979940''>lambda,</span> <span m=''2980460''>where</span> <span m=''2980660''>if</span>
  <span m=''2980840''>it</span> <span m=''2980920''>was</span> <span m=''2981120''>a</span>
  <span m=''2981240''>differential</span> <span m=''2981890''>equation--</span> <span
  m=''2982430''>This</span> <span m=''2982570''>is</span> <span m=''2982770''>just</span>
  <span m=''2983030''>what</span> <span m=''2983140''>we</span> <span m=''2983280''>did</span>
  <span m=''2983480''>for</span> <span m=''2983630''>differential</span> <span m=''2984190''>equations.</span>
  <span m=''2985120''>What</span> <span m=''2985380''>did</span> <span m=''2985550''>I</span>
  <span m=''2985640''>do</span> <span m=''2985790''>for</span> <span m=''2985980''>differential</span>
  <span m=''2986530''>equations?</span> <span m=''2989060''>Do</span> <span m=''2989150''>you</span>
  <span m=''2989220''>mind</span> <span m=''2989500''>if</span> <span m=''2989600''>I</span>
  <span m=''2989680''>just</span> <span m=''2989930''>ask</span> <span m=''2990270''>you?</span>
  <span m=''2991640''>If</span> <span m=''2991860''>I</span> <span m=''2991980''>was</span>
  <span m=''2992200''>solving</span> <span m=''2992820''>dU/dt=(K2D)U.</span> <span
  m=''3000100''>Starting</span> <span m=''3000700''>from</span> <span m=''3000920''>f,</span>
  <span m=''3001460''>start</span> <span m=''3002040''>with</span> <span m=''3002380''>U(0)</span>
  <span m=''3003730''>as</span> <span m=''3004120''>f.</span> <span m=''3006730''>I</span>
  <span m=''3006860''>just</span> <span m=''3007110''>want</span> <span m=''3007480''>to</span>
  <span m=''3008490''>draw</span> <span m=''3008790''>the</span> <span m=''3008930''>analogy.</span>
  <span m=''3010250''>How</span> <span m=''3010650''>did</span> <span m=''3010820''>we</span>
  <span m=''3010960''>solve</span> <span m=''3011310''>these</span> <span m=''3011530''>equations?</span>
  </p><p><span m=''3012110''>I</span> <span m=''3012250''>expanded</span> <span m=''3013020''>f</span>
  <span m=''3013380''>in</span> <span m=''3013500''>terms</span> <span m=''3013880''>of</span>
  <span m=''3013980''>the</span> <span m=''3014100''>eigenvector,</span> <span m=''3016100''>and</span>
  <span m=''3016390''>then</span> <span m=''3016660''>what</span> <span m=''3016910''>was</span>
  <span m=''3017120''>step</span> <span m=''3017520''>two?</span> <span m=''3019820''>For</span>
  <span m=''3020030''>the</span> <span m=''3020190''>differential</span> <span m=''3020780''>equation,</span>
  <span m=''3021890''>I</span> <span m=''3022040''>didn''t</span> <span m=''3022430''>divide</span>
  <span m=''3022970''>by</span> <span m=''3023160''>lambda_k,</span> <span m=''3024110''>what</span>
  <span m=''3024390''>did</span> <span m=''3024570''>I</span> <span m=''3024690''>do?</span>
  <span m=''3026840''>I</span> <span m=''3027090''>multiplied</span> <span m=''3028070''>by</span>
  <span m=''3028770''>e^(lambda_k*t).</span> <span m=''3032510''>You</span> <span
  m=''3032660''>see,</span> <span m=''3032860''>it''s</span> <span m=''3033030''>the</span>
  <span m=''3033150''>same</span> <span m=''3033690''>trick.</span> <span m=''3034270''>Just</span>
  <span m=''3034970''>get</span> <span m=''3035220''>it</span> <span m=''3035360''>in</span>
  <span m=''3035690''>eigenspace.</span> <span m=''3037160''>In</span> <span m=''3037280''>eigenspace</span>
  <span m=''3038340''>it''s</span> <span m=''3038570''>like</span> <span m=''3038870''>one</span>
  <span m=''3039450''>tiny</span> <span m=''3039910''>problem</span> <span m=''3040350''>at</span>
  <span m=''3040510''>a</span> <span m=''3040610''>time.</span> <span m=''3041360''>You''re</span>
  <span m=''3041590''>just</span> <span m=''3041850''>following</span> <span m=''3042400''>that</span>
  <span m=''3042630''>normal</span> <span m=''3043040''>mode,</span> <span m=''3043850''>and</span>
  <span m=''3044880''>so</span> <span m=''3045090''>here</span> <span m=''3045690''>instead</span>
  <span m=''3046110''>of</span> <span m=''3046210''>dividing</span> <span m=''3046680''>by</span>
  <span m=''3046820''>lambda,</span> <span m=''3047170''>I</span> <span m=''3047420''>multiplied</span>
  <span m=''3048010''>by</span> <span m=''3048610''>e^(lambda*t).</span> <span m=''3049840''>And</span>
  <span m=''3050120''>for</span> <span m=''3050290''>powers</span> <span m=''3051000''>of--</span>
  <span m=''3051530''>For</span> <span m=''3051950''>K2D</span> <span m=''3052720''>to</span>
  <span m=''3052800''>the</span> <span m=''3052890''>100th</span> <span m=''3053320''>power,</span>
  <span m=''3053930''>I</span> <span m=''3054110''>would</span> <span m=''3054320''>multiply</span>
  <span m=''3054730''>by</span> <span m=''3054940''>lambda</span> <span m=''3055310''>to</span>
  <span m=''3055540''>the</span> <span m=''3055650''>hundredth.</span> <span m=''3056550''>Here,</span>
  <span m=''3056750''>I</span> <span m=''3056910''>have</span> <span m=''3057150''>K2D</span>
  <span m=''3057680''>to</span> <span m=''3058350''>the</span> <span m=''3058600''>minus</span>
  <span m=''3059010''>first</span> <span m=''3059370''>power.</span> <span m=''3059820''>So</span>
  <span m=''3060010''>I''m</span> <span m=''3060200''>multiplying</span> <span m=''3060770''>by</span>
  <span m=''3060980''>lambdas</span> <span m=''3061620''>to</span> <span m=''3061770''>the</span>
  <span m=''3061880''>minus</span> <span m=''3062280''>one.</span> <span m=''3063100''>OK,</span>
  <span m=''3063740''>and</span> <span m=''3064540''>the</span> <span m=''3064660''>key</span>
  <span m=''3064930''>point</span> <span m=''3065310''>is</span> <span m=''3068050''>that</span>
  <span m=''3068310''>these</span> <span m=''3068750''>c''s</span> <span m=''3069150''>can</span>
  <span m=''3069340''>be</span> <span m=''3069490''>found</span> <span m=''3069920''>fast.</span>
  <span m=''3070820''>And</span> <span m=''3071100''>this</span> <span m=''3072340''>summing</span>
  <span m=''3072950''>up</span> <span m=''3073210''>can</span> <span m=''3073400''>be</span>
  <span m=''3073530''>done</span> <span m=''3073850''>fast.</span> <span m=''3074400''>Now</span>
  <span m=''3074500''>that''s</span> <span m=''3074920''>what''s</span> <span m=''3075810''>also</span>
  <span m=''3076240''>very</span> <span m=''3076680''>exceptional.</span> <span m=''3077740''>And</span>
  <span m=''3077930''>that''s</span> <span m=''3078160''>where</span> <span m=''3078340''>the</span>
  <span m=''3078480''>FFT</span> <span m=''3079150''>comes</span> <span m=''3079470''>in.</span>
  <span m=''3079980''>The</span> <span m=''3080370''>fast</span> <span m=''3080760''>Fourier</span>
  <span m=''3081070''>transform</span> <span m=''3082050''>is</span> <span m=''3082230''>a</span>
  <span m=''3082340''>fast</span> <span m=''3083040''>way</span> <span m=''3083940''>to</span>
  <span m=''3085040''>get</span> <span m=''3085270''>into</span> <span m=''3085720''>eigenspace</span>
  <span m=''3086300''>and</span> <span m=''3086410''>to</span> <span m=''3086510''>get</span>
  <span m=''3086710''>back.</span> <span m=''3088130''>When</span> <span m=''3088720''>eigenspace</span>
  <span m=''3089410''>happens</span> <span m=''3089930''>to</span> <span m=''3090050''>be</span>
  <span m=''3090300''>frequency</span> <span m=''3091020''>space.</span> <span m=''3091950''>You</span>
  <span m=''3092090''>see</span> <span m=''3093040''>that''s</span> <span m=''3093320''>the</span>
  <span m=''3093430''>key.</span> <span m=''3095810''>In</span> <span m=''3095980''>other</span>
  <span m=''3096150''>words</span> <span m=''3096740''>these</span> <span m=''3098210''>y''s</span>
  <span m=''3098650''>and</span> <span m=''3098820''>lambdas</span> <span m=''3099270''>that</span>
  <span m=''3099430''>I</span> <span m=''3099530''>said</span> <span m=''3099910''>we</span>
  <span m=''3100080''>knew,</span> <span m=''3100750''>these</span> <span m=''3101000''>y''s,</span>
  <span m=''3101780''>the</span> <span m=''3101990''>eigenvectors,</span> <span m=''3104210''>are</span>
  <span m=''3104980''>pure</span> <span m=''3105750''>sine</span> <span m=''3106310''>vectors.</span>
  <span m=''3108130''>So</span> <span m=''3108400''>that</span> <span m=''3108700''>this</span>
  <span m=''3109430''>is</span> <span m=''3109720''>an</span> <span m=''3109850''>expansion,</span>
  <span m=''3110760''>is</span> <span m=''3110950''>a</span> <span m=''3111060''>sine</span>
  <span m=''3111530''>transform.</span> <span m=''3113060''>S-I-N-E.</span> <span
  m=''3114260''>A</span> <span m=''3114830''>pure</span> <span m=''3115560''>sine</span>
  <span m=''3115960''>transform.</span> <span m=''3116810''>And</span> <span m=''3117090''>that</span>
  <span m=''3117350''>can</span> <span m=''3117530''>be</span> <span m=''3117660''>done</span>
  <span m=''3117920''>fast,</span> <span m=''3118750''>and</span> <span m=''3118980''>it</span>
  <span m=''3119080''>can</span> <span m=''3119230''>be</span> <span m=''3119390''>inverted</span>
  <span m=''3119900''>fast.</span> <span m=''3120940''>So</span> <span m=''3121470''>you</span>
  <span m=''3121630''>see,</span> <span m=''3122630''>what</span> <span m=''3122870''>makes</span>
  <span m=''3123210''>this</span> <span m=''3123380''>fast</span> <span m=''3123830''>Poisson</span>
  <span m=''3124110''>solver</span> <span m=''3124720''>work,</span> <span m=''3125630''>is</span>
  <span m=''3126370''>I</span> <span m=''3126550''>have</span> <span m=''3126740''>to</span>
  <span m=''3126880''>know</span> <span m=''3127210''>eigenvectors</span> <span m=''3128350''>and</span>
  <span m=''3128620''>eigenvalues,</span> <span m=''3129150''>and</span> <span m=''3129330''>they</span>
  <span m=''3129440''>have</span> <span m=''3129750''>to</span> <span m=''3129880''>be</span>
  <span m=''3130080''>fantastic</span> <span m=''3131030''>vectors</span> <span m=''3131890''>like</span>
  <span m=''3132140''>sine</span> <span m=''3132570''>vectors.</span> <span m=''3133480''>OK,</span>
  <span m=''3134030''>so</span> <span m=''3134450''>I''ll</span> <span m=''3134640''>give</span>
  <span m=''3134840''>you</span> <span m=''3134960''>more,</span> <span m=''3135480''>the</span>
  <span m=''3135700''>final</span> <span m=''3136800''>picture,</span> <span m=''3137600''>the</span>
  <span m=''3137740''>details,</span> <span m=''3138470''>Wednesday</span> <span m=''3139230''>and</span>
  <span m=''3139460''>then</span> <span m=''3139640''>move</span> <span m=''3139860''>on</span>
  <span m=''3140080''>to</span> <span m=''3140200''>finite</span> <span m=''3140490''>elements.</span>
  </p>'
type: course
uid: d1b9a4c5d88a39b1dae061c634e72b0b

---
None