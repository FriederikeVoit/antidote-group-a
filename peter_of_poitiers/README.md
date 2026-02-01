# 27/1/26 FV

Currently should contain xml files of group working on Peter of Poitiers' Compendium Historiae

<?xml version="1.0" encoding="UTF-8"?>
<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_all.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?>
<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_all.rng" type="application/xml"
	schematypens="http://purl.oclc.org/dsdl/schematron"?>

<TEI xmlns="http://www.tei-c.org/ns/1.0">
   <teiHeader>
      <fileDesc>
         <titleStmt>
            <title>Daniel's prophecies in Compendium historiae genalogia Christi, ms. K</title>
            <respStmt>
            <resp>Semi-diplomatic transcription (training exercise, ANTIDOTE project)</resp>
            <persName>Erica Cattelan</persName>
         </respStmt>
         </titleStmt>
         
          <publicationStmt>
            <p>Semi-diplomatic transcription conducted for coursework purposes within the ANTIDOTE
               project.</p>
         </publicationStmt>
         
         <sourceDesc>
            <msDesc>
               <msIdentifier>
                  <country>Austria</country>
                  <settlement>Klosterneuburg</settlement>
                  <repository>Augustiner-Chorherrenstift</repository>
                  <idno>Cod.696</idno>
               </msIdentifier>

               <msContents>
                  <summary>Arbor ecclesiae christianae cum glossis; Petrus Pictaviensis: Compendium
                     historiae in genealogia Christi; Tractatulus de significatione verbi 'Domus
                     Dei'; Petrus Comestor: Historia scholastica.</summary>
                  <msItem n="2">
                     <locus from="2r" to="7r">2r-7r</locus>
                     <author>Petrus Pictaviensis</author>
                     <title>Compendium historiae genealogia Christi</title>
                     <textLang mainLang="la">Latin</textLang>
                  </msItem>
               </msContents>
            </msDesc>

         </sourceDesc>
      </fileDesc>
      <profileDesc>
         <particDesc>
            <listPerson>
               <person xml:id="prophet_Daniel">
                  <persName> Daniel</persName>
               </person>
               <person xml:id="king_Nabucodonosor">
                  <persName>Nabucodonosor</persName>
               </person>
               <person xml:id="Christus">
                  <persName>Christus</persName>
               </person>
               <person xml:id="king_Balthasar">
                  <persName>Balthasar</persName>
               </person>
               <person xml:id="emperor_Alexander">
                  <persName>Alexandro</persName>
               </person>
               <person xml:id="king_Anthiocus_Epiphanes">
                  <persName>Anthiocus Epiphanes</persName>
               </person>
               <person xml:id="king_Cyrus">
                  <persName>Cyrus</persName>
               </person>
               <person xml:id="king_Darius">
                  <persName>Darius</persName>
               </person>
               <person xml:id="archangel_Gabriel">
                  <persName>Gabriel</persName>
               </person>
               <person xml:id="governator_Neemia">
                  <persName>Neemia</persName>
               </person>
               <person xml:id="Antichristus">
                  <persName>Antichristus</persName>
               </person>
            </listPerson>
         </particDesc>
      </profileDesc>
   </teiHeader>
   
   <text>
      <body>
         <div>
            <p>
               <title>
                  <persName ref="#prophet_Daniel"> Daniel </persName></title>
               <lb/></p>
         </div>
         <div>
            <head type="rubrica"> visio prima secunda et tertia </head>
            <p>
               <lb/>
               <persName ref="#prophet_Daniel">Propthetans Daniel</persName> in Chaldea sub
                  <persName ref="#king_Nabucodonosor"> Nabucod<ex>onos</ex>or </persName>
                  temp<ex>or</ex>e captivitatis &#46;vidit X vi<lb/>siones &#46; quarum tres vidit
               sub <persName ref="#king_Nabucodonosor"> Nabucodonosor </persName> prima de <lb/>
               statua quadripartita lapide minimo crescente <lb/> sig<ex>nifi</ex>cante quatuor
               regna a <persName ref="#Christus">christo</persName> comminuenda &#46;
                  s<ex>e</ex>c<ex>un</ex>dam de <lb/> ang<ex>e</ex>lo qui libavit tres pueros a
               fornace &#46; qui n<ex>on</ex> adorav<ex>er</ex>ant statuam campi duran &#46; Tercia
               que est epistula regis &#46; qua narrat se sub spe<ex>cie</ex> arboris visum &#46; ob
               superbiam suam in bovem et leonem &#46; non corp<ex>or</ex>alit<ex>er</ex> &#46;
                  <ex>sed</ex> alienatione<ex>m</ex> m<ex>en</ex>tis mutatu<ex>m</ex> &#46;
                  <ex>sed</ex> p<ex>os</ex>t p<ex>re</ex>ce <persName ref="#prophet_Daniel"
                  >Danielis</persName> sanatum &#46; </p>

            <p> Quarta<ex>m</ex> visione<ex>m</ex> vidit sub<persName ref="king_Balthasar"
                  >balthasar</persName> de IIII ven<lb/>tis <ex>idest</ex> angelis <ex>et</ex> IIII
               bestiis &#46; leone &#46; urso &#46; pardo &#46; ap<ex>ro</ex>
               <lb/>
               <ex>idest</ex> IIII regnis &#46; <ex>et</ex> X cornib<ex>us</ex>
               <ex>et</ex> X regnis &#46; de q<ex>ua</ex>rta bes<lb/>tia
                  p<ex>re</ex>cedentib<ex>us</ex> a modico cornu <ex>idest</ex>
               <persName ref="#Antichristus">anti<ex>christo</ex></persName>
               subicie<ex>n</ex><lb/>dis &#46; positis in adventu <persName ref="#Christus">
                  <ex>christi</ex>
               </persName> bestiis int<ex>er</ex>fectis</p>

            <p> Quinta<ex>m</ex> vidit visionem sub eode<ex>m</ex>&#46; de ariete h<ex>abe</ex>
               <lb/> cornua imparia <ex>idest</ex> regno medo<ex>rum</ex>
               <ex>et</ex> p<ex>er</ex>sa<ex>rum</ex>
               <ex>et</ex> hyrco <lb/>
               <ex>idest</ex>
               <persName ref="emperor_Alexandro">alexandro</persName> in eum efferato cui
               &#46;succrescebant IIII<ex>uor</ex>
               <lb/> cornua <ex>idest</ex> successores de qua<ex>rum</ex> uno modicu<ex>m</ex> cornu <lb/>
               <ex>idest</ex>
               <persName ref="king_Anthiocus_Epiphanes">antiochus epiphanes</persName> &#46;</p>

            <p> Sexta<ex>m</ex> vidit sub eode<ex>m</ex> de destructione babylonis &#46;<lb/>
               <ex>per</ex>
               <persName ref="king_Cyrus"> cyru<ex>m</ex></persName>
               <ex>et</ex>
               <persName ref="king_Darius">dariu<ex>m</ex></persName>&#46; exposita
               sc<ex>ri</ex>ptura in convivio &#46; que co<ex>n</ex><lb/>tinebat &#46;mane
               &#46;techel &#46;phares &#46; </p>
         </div>

         <div>
            <head>visio quarta quinta et sexta </head>
         
            <p>
               <gap reason="first letter obmission"/>septima<ex>m</ex> vidit sub <persName
                  ref="#king_Darius">dario</persName> &#46; de ang<ex>e</ex>lo q<ex>ui</ex><lb/>
                  eu<ex>m</ex> de lacu leonu<ex>m</ex> lib<ex>er</ex>avit &#46; u<ex>bi</ex>
               <ex>preter</ex> volunta<lb/>te <persName ref="#king_Darius">regis</persName> positus
                  fu<ex>er</ex>at &#46; <ex>quia</ex> decreto p<ex>ri</ex>ncipi <lb/> invidia dato
               de peticionib<ex>bus</ex>
               <ex>non</ex> faciendis <ex>nisi</ex> a <persName ref="#king_Darius"
               >rege</persName><lb/>&#46; ter orando in die <ex>con</ex>tradixerat&#46; </p>

            <p> Octava<ex>m</ex> vidit sub <persName ref="#king_Darius">eodem</persName> &#46;
                  <persName ref="#archangel_Gabriel">gabriele</persName> eu<ex>m</ex>
               c<ex>er</ex>tifican<lb/>te de adventu <persName ref="#Christus"
                  ><ex>christi</ex></persName> &#46; <ex>post</ex> IXX ebdomades
               anno<ex>rum</ex><lb/> lunariu<ex>m</ex> &#46; <ex>et</ex> captivitate finali
                  fut<ex>ur</ex>a p<ex>er</ex> romanos &#46; post<lb/> edificatione<ex>m</ex>
               civitatis p<ex>er</ex>
               <persName ref="#governator_Neemia">neemiam</persName>
               <ex>et</ex> alios&#46; </p>
         </div>

         <div>
            <head>visio septima&#46; octava&#46;</head>
            <p>
               <gap reason="omissione della prima lettera"/>nona<ex>m</ex> vidit sub <persName
                  ref="#king_Cyrus">cyro</persName>&#46; cu<ex>m</ex> ieiunans iuxta &#46; <lb/>
               uidit uirum indutum balthidi&#46; cu<ex>ius</ex> corpus
               c<ex>ri</ex>solit<ex>us</ex>&#46; <lb/>oculi lampades&#46; facies ut fulgur&#46;
               <lb/>
            </p>

            <p> Decima<ex>m</ex> audiuit cu<ex>m</ex> ide<ex>m</ex> uir de successione
                  regu<ex>m</ex>
               <lb/> p<ex>er</ex>sa<ex>rum</ex>&#46; <ex>et</ex>
               <persName ref="#emperor_Alexandro">alexandro</persName> cu<ex>m</ex> suiis
                  successorib<ex>us</ex> IIII max<lb/>ime regib<ex>us</ex> egypti <ex>et</ex>
               syrie&#46; <ex>et</ex> seuitia <persName ref="#king_Anthiocus_Epiphanes">antiochi
                  epi<lb/>phanes</persName>&#46; <ex>et</ex>
               <persName ref="#Antichristus">anti<ex>christo</ex></persName>
               <ex>per</ex> temp<ex>or</ex>a <ex>et</ex> tempus <ex>et</ex> dimidi<lb/>um
                  temp<ex>or</ex>is regnaturo&#46; eum certificauit&#46; </p>
         </div>
         <div>
            <head> visio nona decima &#46;</head>
         </div>







      </body>
   </text>
</TEI>
