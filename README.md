[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=20524049&assignment_repo_type=AssignmentRepo)
# MiniTorch Module 1

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module1/module1/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py tests/test_module.py tests/test_operators.py project/run_manual.py

Simple dataset (PTS = 50, HIDDEN = 2, RATE = 0.5):

Epoch  10  loss  27.060191366189102 correct 36

Epoch  20  loss  22.833060295339536 correct 43

Epoch  30  loss  17.65421131865955 correct 45

Epoch  40  loss  13.253886959326207 correct 46

Epoch  50  loss  10.456743500040227 correct 50

Epoch  60  loss  8.596553977854219 correct 50

Epoch  70  loss  7.431600990392129 correct 49

Epoch  80  loss  6.655524549139675 correct 48

Epoch  90  loss  6.066473199033183 correct 48

Epoch  100  loss  5.580543220696552 correct 49

Epoch  110  loss  5.159999971316037 correct 49

Epoch  120  loss  9.57123461945949 correct 44

Epoch  130  loss  7.514553244158637 correct 46

Epoch  140  loss  5.9211876913121415 correct 48

Epoch  150  loss  6.274711595531493 correct 47

Epoch  160  loss  6.384182057014421 correct 47

Epoch  170  loss  6.028650397192268 correct 47

Epoch  180  loss  5.866523153583561 correct 47

Epoch  190  loss  5.7723770787045225 correct 47

Epoch  200  loss  5.632522659456391 correct 47

Epoch  210  loss  5.49146465684014 correct 47

Epoch  220  loss  5.369992889047122 correct 47

Epoch  230  loss  5.168458151743174 correct 48

Epoch  240  loss  5.041815086654401 correct 48

Epoch  250  loss  5.026166985235403 correct 48

Epoch  260  loss  4.911789341627848 correct 48

Epoch  270  loss  4.760026838714077 correct 48

Epoch  280  loss  4.6605438788444555 correct 48

Epoch  290  loss  4.582951857028743 correct 48

Epoch  300  loss  4.478389191144828 correct 48

Epoch  310  loss  4.361282065257135 correct 48

Epoch  320  loss  4.264605373047518 correct 48

Epoch  330  loss  4.184000240108994 correct 48

Epoch  340  loss  4.092417061804549 correct 48

Epoch  350  loss  4.0342347864803445 correct 48

Epoch  360  loss  3.951209885154228 correct 48

Epoch  370  loss  3.740664184224405 correct 48

Epoch  380  loss  3.5831074341031957 correct 49

Epoch  390  loss  3.6167234291622536 correct 49

Epoch  400  loss  3.868055564512755 correct 48

Epoch  410  loss  3.695665516331448 correct 48

Epoch  420  loss  2.822357099251113 correct 49

Epoch  430  loss  2.1346285869283457 correct 50

Epoch  440  loss  1.8952006947355609 correct 50

Epoch  450  loss  1.885204424488052 correct 50

Epoch  460  loss  3.032336997862108 correct 49

Epoch  470  loss  8.692596049715274 correct 45

Epoch  480  loss  1.866760794215516 correct 50

Epoch  490  loss  1.5486950043362604 correct 50

Epoch  500  loss  1.452690186441681 correct 50

Xor dataset (PTS = 50, HIDDEN = 10, RATE = 0.5):

Epoch  10  loss  30.88257075857704 correct 35

Epoch  20  loss  27.82570248926737 correct 36

Epoch  30  loss  28.234783729483755 correct 31

Epoch  40  loss  28.409766982679905 correct 32

Epoch  50  loss  26.312593357219416 correct 33

Epoch  60  loss  25.84542276119197 correct 33

Epoch  70  loss  22.457114040004686 correct 37

Epoch  80  loss  19.633848401367267 correct 39

Epoch  90  loss  30.057495465162024 correct 31

Epoch  100  loss  16.11513261903092 correct 42

Epoch  110  loss  14.298696531113558 correct 46

Epoch  120  loss  27.846328394988838 correct 33

Epoch  130  loss  10.125099657999263 correct 46

Epoch  140  loss  36.25874600029623 correct 33

Epoch  150  loss  7.194998791411241 correct 50

Epoch  160  loss  12.841297986434286 correct 43

Epoch  170  loss  6.205536865296474 correct 50

Epoch  180  loss  5.094177044664718 correct 50

Epoch  190  loss  13.79231592663041 correct 41

Epoch  200  loss  5.25833388935847 correct 50

Epoch  210  loss  4.005688770047532 correct 50

Epoch  220  loss  3.602382778670991 correct 49

Epoch  230  loss  9.265038744736273 correct 46

Epoch  240  loss  4.370829000590561 correct 50

Epoch  250  loss  3.1441208805790133 correct 50

Epoch  260  loss  2.6944474681085056 correct 50

Epoch  270  loss  2.424282642309518 correct 50

Epoch  280  loss  2.290731774441364 correct 50

Epoch  290  loss  2.1964725310156497 correct 49

Epoch  300  loss  3.099460073403789 correct 49

Epoch  310  loss  14.882286478085042 correct 42

Epoch  320  loss  5.348494702978284 correct 50

Epoch  330  loss  2.4911351892962244 correct 50

Epoch  340  loss  1.9588957861347085 correct 50

Epoch  350  loss  1.7005824553824664 correct 50

Epoch  360  loss  1.5106158394756595 correct 50

Epoch  370  loss  1.376433848001063 correct 50

Epoch  380  loss  1.29627732247186 correct 50

Epoch  390  loss  1.2067923797735316 correct 50

Epoch  400  loss  1.1485926935856587 correct 50

Epoch  410  loss  1.0902715794785225 correct 50

Epoch  420  loss  1.0258964340921746 correct 50

Epoch  430  loss  0.9724872460207559 correct 50

Epoch  440  loss  0.9703848279784156 correct 50

Epoch  450  loss  0.9410125427303566 correct 50

Epoch  460  loss  0.8477551008861773 correct 50

Epoch  470  loss  0.866246605519821 correct 50

Epoch  480  loss  0.9311487417133287 correct 50

Epoch  490  loss  0.8856177904036783 correct 50

Epoch  500  loss  0.8042569104946624 correct 50

Diag dataset (PTS = 50, HIDDEN = 10, RATE = 0.5):

Epoch  10  loss  10.880053788461383 correct 44

Epoch  20  loss  8.664794430191202 correct 46

Epoch  30  loss  6.871706692823311 correct 47

Epoch  40  loss  5.471927463662594 correct 48

Epoch  50  loss  4.474885098453834 correct 49

Epoch  60  loss  3.76123668966166 correct 49

Epoch  70  loss  3.2282710985856125 correct 50

Epoch  80  loss  2.796426506967634 correct 50

Epoch  90  loss  2.4840762956099693 correct 50

Epoch  100  loss  2.2252341365686026 correct 50

Epoch  110  loss  2.019742933016411 correct 50

Epoch  120  loss  1.8487507662231408 correct 50

Epoch  130  loss  1.705075030966779 correct 50

Epoch  140  loss  1.5791865041234778 correct 50

Epoch  150  loss  1.470797606852828 correct 50

Epoch  160  loss  1.3750734594868863 correct 50

Epoch  170  loss  1.2904570133720425 correct 50

Epoch  180  loss  1.2150535543444818 correct 50

Epoch  190  loss  1.1472434462222658 correct 50

Epoch  200  loss  1.0859727435298088 correct 50

Epoch  210  loss  1.0303443985516336 correct 50

Epoch  220  loss  0.979596360600508 correct 50

Epoch  230  loss  0.9330994021547461 correct 50

Epoch  240  loss  0.8903420480899251 correct 50

Epoch  250  loss  0.8508936030351837 correct 50

Epoch  260  loss  0.8143853173937573 correct 50

Epoch  270  loss  0.780502109305013 correct 50

Epoch  280  loss  0.7489980188447909 correct 50

Epoch  290  loss  0.7195972436889095 correct 50

Epoch  300  loss  0.692066809500408 correct 50

Epoch  310  loss  0.6662767693230162 correct 50

Epoch  320  loss  0.6421184987169013 correct 50

Epoch  330  loss  0.6193724995934272 correct 50

Epoch  340  loss  0.59798514728904 correct 50

Epoch  350  loss  0.5778186137667041 correct 50

Epoch  360  loss  0.558758764663976 correct 50

Epoch  370  loss  0.5407197722739998 correct 50

Epoch  380  loss  0.5236499441239441 correct 50

Epoch  390  loss  0.5075470719520748 correct 50

Epoch  400  loss  0.4924572764814265 correct 50

Epoch  410  loss  0.47808242338863355 correct 50

Epoch  420  loss  0.4643939879207217 correct 50

Epoch  430  loss  0.4513157459250921 correct 50

Epoch  440  loss  0.4388136999084258 correct 50

Epoch  450  loss  0.4268516656376968 correct 50

Epoch  460  loss  0.41540533686519115 correct 50

Epoch  470  loss  0.4044328248263083 correct 50

Epoch  480  loss  0.39385179173234725 correct 50

Epoch  490  loss  0.38358325475115645 correct 50

Epoch  500  loss  0.3737406803652512 correct 50

Split dataset (PTS = 50, HIDDEN = 10, RATE = 0.5):

Epoch  10  loss  31.443001099835232 correct 36

Epoch  20  loss  30.61374972264291 correct 37

Epoch  30  loss  29.738638908180906 correct 37

Epoch  40  loss  30.265855107240576 correct 33

Epoch  50  loss  30.84458923383995 correct 32

Epoch  60  loss  30.2013607528248 correct 33

Epoch  70  loss  29.598569097855503 correct 33

Epoch  80  loss  27.19579307993956 correct 34

Epoch  90  loss  27.63699099545699 correct 32

Epoch  100  loss  24.90566537689729 correct 32

Epoch  110  loss  22.159883806495202 correct 36

Epoch  120  loss  19.72343324846722 correct 40

Epoch  130  loss  16.95929595840575 correct 41

Epoch  140  loss  15.83393178064787 correct 41

Epoch  150  loss  13.107188083492716 correct 42

Epoch  160  loss  14.760653182855155 correct 41

Epoch  170  loss  10.506648447213347 correct 44

Epoch  180  loss  9.960262695136963 correct 45

Epoch  190  loss  13.867060316482423 correct 43

Epoch  200  loss  7.164044853884058 correct 48

Epoch  210  loss  6.115103549569796 correct 49

Epoch  220  loss  9.036444553098766 correct 46

Epoch  230  loss  12.354344588195357 correct 44

Epoch  240  loss  4.585951455769941 correct 49

Epoch  250  loss  4.0849769252242565 correct 49

Epoch  260  loss  3.8290116110042214 correct 49

Epoch  270  loss  3.780518696855409 correct 49

Epoch  280  loss  6.472497161793474 correct 48

Epoch  290  loss  13.151403798386655 correct 45

Epoch  300  loss  12.137136801036332 correct 44

Epoch  310  loss  3.7330623277643213 correct 49

Epoch  320  loss  3.4523619536101466 correct 49

Epoch  330  loss  3.2870500739099304 correct 49

Epoch  340  loss  3.1616761228307215 correct 49

Epoch  350  loss  3.0602747832961503 correct 49

Epoch  360  loss  3.0530486287863265 correct 49

Epoch  370  loss  5.437572820629853 correct 48

Epoch  380  loss  11.719258081895326 correct 45

Epoch  390  loss  3.8211858275923536 correct 49

Epoch  400  loss  3.055943449884915 correct 49

Epoch  410  loss  3.0553855316750944 correct 49

Epoch  420  loss  3.49334083363022 correct 49

Epoch  430  loss  4.093404693445053 correct 49

Epoch  440  loss  4.123752620482726 correct 49

Epoch  450  loss  3.992451217159793 correct 49

Epoch  460  loss  3.9512309402822616 correct 49

Epoch  470  loss  3.9438918906647524 correct 49

Epoch  480  loss  3.9340725739862843 correct 49

Epoch  490  loss  3.916712513141283 correct 49

Epoch  500  loss  3.897420321297636 correct 49