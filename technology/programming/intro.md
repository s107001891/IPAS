# 

# 程式語言與程式設計

```
程式(program) =演算法(algorithm) + 資料結構(datastructure) 

凡能描述演算法和資料結構的系統化符號即稱為程式語言(programming language)，
它是可指揮電腦執行指定動作的一種語言。
```
### 程式語言的分類
```
程式語言的發展可分成好幾代，愈新一代的程式語言愈方便人們使用，也愈接近人類所講的語言。依程式語言的特性通常可區分為以下幾類:

(一)第一代程式語言:機器語言(machine language)
    [1]由0與1組成的二進位碼所構成
    [2]不同類型的計算機擁有不同的指令群，其對應的二進位碼亦不相同， 因此機器語言是一種與機器相關(machine dependent)的語言。
    [3]機器語言可以直接被計算機接受並執行，但對程式的撰寫及維護都極為困難。除非有需要， 否則很少直接利用它來寫程式。

(二)第二代程式語言─組合語言(assembly language)
    [1]由於機器語言的程式難以撰寫和閱讀，於是將每一條機器語言指令用一個助記憶符號(mnemonic symbol)來取代，
    這些助記憶符號即稱為組合語言(assembly language)，叉稱為低階語言(low- level language)。
    例如: 若4E(16)代表資料搬移的機器語言指令，在組合語言中可用MOVE這個較易記憶的符號來取代。
    [2]用組合語言撰寫程式要比機器語言方便得多，但計算機卻看不懂，
    因此必須透過一套系統程式來將組合語言程式轉換為機器語言， 此套系統程式稱為組合程式( assembler)。
    組合語言指令與機器語言指令因其有一對一的對應關係，因此亦屬於與機器相關的語言。

(三)第三代程式語言─高階語言(high- level language)
    [1]由於組合語言仍為與機器相關的語言，須了解計算機之結構才能撰寫程式，而且所寫程式只能在特定機器上使用，不具有移植性，
    [2]一般適用於電腦專業人員使用，不易普及。因此為了使電腦更廣泛地為人們所接受，
       專家們依據科學、商業或統計等需要而發展一些較接近人類日常語言的程式語言，即稱為高階語言(high- level language)。
    [3]此種語言與計算機結構無關， 具有移植性，可在不同的機器上使用，因此是一種與機器無關(machine independent)的語言。高階語言的程式必須透過編譯程式( compiler )或直譯程式( interpreter 轉換為機器語言後，才能在計算機上執行。此外，高階語言的每一句稱為一個敘述( statement)而不再是指令，它與指令為一對多的關係。程式的撰寫是利用這些敘述來描述如何解決問題的程序，因此高階語言又稱為程序導向語言( procedure- oriented language)。

(四)第四代程式語言─超高階語言(very high level language)通常稱為4GL(為fourth generation language之縮寫，而高階語言為3GL)
     [1]是屬於問題導向語言( problem-oriented language)或稱非程序性語言( non- procedure language)，
        因其程式中只需指示電腦去「做什麼( what to do)即可，而不必告訴電腦該「如何做(how to do)。
      [2]電腦硬體技術的突飛猛進，不僅在速度上有重大突破，且記憶體容量亦愈來愈大，因此程式設計師已不需再如過去那樣，要費盡心思精簡程式，
        以求更高的執行速度及降低記憶體需求。目前所關注的是如何快速地開發一套完整的應用程式，因此超高階語言便應運而生。常超高階語言都與
	解決某類特定問題有關，由一系列整合性模組軟體所構成，可供程式設計師快速地開發應用程式，屬於高生產力的程式語言(其生產力約為第三代語言的十倍)。

(五)第五代程式語言─自然語言(natural language)   
      [1]自然語言是人類日常生活所用的語言，如中文、英文、日文等均為自然語言。==>NLP:Natural language processing
      [2]在計算機中，目前自然語言的處理技術尚不成熟，只能做有限度的還用。例如：用以存取知識庫的知識庫語言(knowledge-based language)，
         即是以處理某特定領域的資訊為基礎的自然語言，但它對於較複雜的邏輯問題則仍無法處理。
```

### 為何要學習程式語言
```
(一)增進對所使用程式語言的了解。
(二)可以改進程式的架構。
(三)有助於選擇合適的程式語言。
(四)比較容易學習新的程式語言。
(五)較容易設計出一種新的程式語言。
```


### 電腦的應用領域及相關的程式語言
```
(一)科學應用，如FORTRAN。
(二)商業應用，如COBOL。
(三)人工智慧，如LISP、PROLOG。
(四)系統程式，如發展UNIX所用之C語言。
    另外有一些可應用在特定機器上開發系統軟體的機器導向高階語言(machine- oriented high- level languages)，如:
     IBM機器上之PL/S (PL/1之後代)
     Digital機器上之BLISS
     Burroughs機器上之Extended ALGOL
(五)超高階語言:
     [1]UNIX上面的各種腳本語言(scripting languages)： shell、ksh、awk、perl、等
     [2]常用來執行資料庫操作的第四代語言：RAMIS (Mathematica公司)、FOCUS (IBM PC)、Informxi(XENIX)。
(六)特殊目的語言(問題導向語言):
     [1]用於產生商業報表的RPG(Report Program Generator)
     [2]用於系統模擬的GPSS(General Purpose System Simulator)
     [3]用於結構工程的STRESS(Srtucutre Engineering System Solver)等。
```

### 高階程式語言
```
A.高階語言的優點
使用高階語言撰寫程式比起使用組合語言真有以下的優越性:
(一)學習容易，學習時間較短。
(二)生產力較高，對於人力及管理的需求較少。
(三)具有與機器無關的優越性。
(四)程式的除錯較容易。
(五)編寫較大的應用程式時，不至因瑣碎的程式細節而影響設計的進行。
(六)高階語言的結構本身就具有卓越的文件說明能力。
```
```
B.高階語言實作的方法有三種：
(一)編譯(compilation)─以編譯程式(compiler) 來實作；
(二)直譯(interpretation)─以直譯程式( interpreter)來實作；
(三)不純的直譯(impure interpretation)─混合式實作法。

(一)編譯(compilation)─以編譯程式(compiler) 

1.定義：編譯程式是一種系統程式，用來將高階語言(如FORTRAN、COBOL 、PASCAL等程式語言)所寫的原始程式(source program)
        轉換成能直接被機器接受的等效目的程式(object program)─亦即機器語言程式。
2.編譯的作法[略]
3.編譯的流程[略]

(二)直譯(interpretation)─以直譯程式( interpreter)來實作；
1.定義：直譯程式也是一種系統程式，其功能是按照高階語言(如BASIC/Python程式語言) 所寫的原始程式執行時敘述的邏輯順序，
        逐一將指令轉換為機器語言並且執行之。
2.直譯的作法[略]


(三)不純的直譯(impure interpretation)─混合式實作法。
1.將編譯與直譯結合的混合式實作方法(hybrid imple-mentation)，使其同時擁有編譯與直譯的優點。
2.UCSD Pascal採用此種方法實作。
3.不純的直譯之流程圖[略]


C.編譯程式與直譯程式之差異：
(1)對原始程式的處理方式不同：
    編譯程式及直譯程式的輸入都是高階語言所寫的程式，
    但編譯程式只產生等效之目的程式(亦即機器語言程式)卻不執行，
    而直譯程式按照輸入程式執行時敘述的邏輯順序逐一地分析解碼並且執行。
(2)敘述的處理順序不同：
    編譯程式按照程式實體上敘述的輸入順序進行處理， 
    而直譯程式則依照程式執行時敘述的邏輯順序進行處理。
(3)敘述的處理次數不同：
    編譯程式對於程式中每個敘述都只處理一次，
    而直譯程式依照執行時敘述的邏輯順序進行處理，
    因此可能發生某些敘述被重複處理許多次(當這些敘述形成迴圈且被執行到時)，
    而某些敘述沒有被處理(當這些敘述沒有被執行到時，例如：當錯誤發生時才執行的程式片斷可能不會被執行)


4.編譯程式與直譯程式之優缺點：

編譯程式之優缺點
編譯程式之優點：
①執行效率高：每次執行時只要把已編譯完成之目的程式載入記憶體直接執行即可，不必再進行原始程式的解碼程序，因此具有較高的執行效率。
②節省解碼的時間：編譯程式按照原始程式實體上的輸入順序進行解碼，每個敘述都只解碼一次，執行時則直接執行產生之目的程式，
                因此即使迴圈中的敘述被重複執行許多次也不需重複解碼，所以可節省許多的解碼時間。

編譯程式之缺點：
①執行時需要較大的記憶體空間：由於編譯程式是將原始程式中的所有敘述全部轉換為目的程式，並且在執行時將該目的程式載入記憶體，因此需要較大的記憶體空間。
②儲存時需要較大的輔助儲存體空間：由於需將原始程式及目的程式一併儲存，因此需要比較大的輔助儲存體空間。
③執行階段之錯誤處理比較麻煩：程式執行時若發生錯誤，必須先修改原始程式，然後重新編譯產生目的程式，才能再次執行。

直譯程式之優缺點
直譯程式之優點：
①執行時所需的記憶體空間較小: 由於直譯程式處理原始程式時，是一次分析解碼一個敘述，並且立即執行，因此在記憶體中， 
                           只需要些許的記憶體空間來存放經解碼轉換的機器語言指令即可。
②儲存時所需的輔助儲存體空間較小：因只需儲存原始程式即可。
③執行階段之錯誤處理比較簡單：可直接修改敘述或資料後繼續轉換及執行。

直譯程式之缺點：
①執行效率較低：由於直譯程式對於原始程式中的每一個敘述，在執行之前都必須先行解碼，因此執行時所花的時間較長，相對地執行效率亦較低。
②解碼所需的時間較長：對於重複執行(如迴圈中)的敘述，直譯程式每次都先進行解碼轉換而後執行，因此需要花費比較多次的解碼時間。
```
```
D.高階語言的類型
(一)命令式程式語言(Imperative Programming Language)：
1.特徵：藉著指定運算來改變變數的狀態以完成程式所要執行的工作。
2.兩大要素：變數、變數值的指定。
3.以重複式敘述(如for、while、……)來完成迴圈的工作。
4.常見的命令式語言如FORTRAN、COBOL、ALGOL GO、BASIC、PL/l、PASCAL、Ada等。

(二)應用式程式語言(Applicative Programming Language)：
1.特徵：以函數的應用及遞迴呼叫來完成程式所要執行的工作。
2.也稱為函數型程式語言(functional programming language)。
3.早期單純的函數型程式語言強調不使用變數及指定敘述，迴圈則透過函數的遞迴呼叫來完成。
4.後來的應用式程式語言大多已加入命令式語言的特徵。
5.常見的應用式程式語言，如LISP、APL、SCHEME、SNOBOL、ML、Miranda等。

(三)邏輯型程式語言(Logic Programming Language)：
1.屬於宣告式語言(declarative language)，而不是程序性語言(procedural language)，亦即它是一種非程序性語言。
2.程式的設計主要是描述解決問題的推論規則和事實資料，而不必管如何解決問題的細部程序。
3.最廣泛使用的邏輯型程式語言為PROLOG。

(四)物件導向語言(Object-Oriented Language)：
1.物件導向的基本特性包括：
(1)資料抽象化(data abstraction)
(2)動態繫結(dynamic binding)。
(3)繼承(inheritance)。
2.可進行物件導向程式設計(Object-Oriented Programming,OOP)的程式語言即稱為物件導向語言。
3.最早發展出來的個體導向語言是Smalltalk。
4.在命令式語言、應用式語言或邏輯型程式語言加入OOP的特性，皆可使其成為物件導向語言。
```
```
E.程式語言的評估與設計之考慮
一、程式語言之評估
(一)評估標準：
1.可讀性(readability)：
2.可寫性(writability)：容易建立程式的特性。
3.可靠性(reliability)：語言的設計可讓使用者不易犯下錯誤，即使犯錯也很容易找出來之特性。
4.成本(cost)包括：
(1)學習成本。
(2)撰寫程式之成本。
(3)編譯成本。
(4)執行成本。
(5)編譯程式之建構成本。
(6)低可靠性之成本。
(7)維護程式之成本。

(二)影響評估標準之因素：
1.語法設計(syntax design)：如識別字的格式，提供那些關鍵字、及能否從語法格式了解其意義等。
2.控制結構：如是否支援結構化程式設計。
3.資料型態和結構：支援那些資料型態及可建立何種資料結構。
4.簡單性與正交性：
(1)只具備少數的基本結構及簡單的組合規則，並且每一種可能的組合都是合法且有意義的，此即為正交性(orthogo-nality)。
(2)語言在設計上愈具有正交性，則語言的規則中愈少有例外情況，因此易學、易讀、易了解→簡單性。
5.支援抽象化：允許使用者定義複雜的結構和運算，並在使用它們時可忽略掉無關的細節之能力。
    可分為程序抽象化(process absrtaction)和資料抽象化(data absrtaction)。
6.表達性(expressivity)：表達各種運算的能力和特性。
7.型態撿查：在編譯或執行時期進行型態檢查的能力。
8.例外處理(exception handling)：可偵測例外及處理例外的能力。
9.別名的限制：是否限制別名的使用。

二、影響語言設計之因素
(一)計算機架構(Computer Architecture)：
1.范紐曼機器(Von Neumann machine)：
(1)此類電腦包含五大單元：輸入單元、輸出單元、記憶單元、控制單元、算術和邏輯運算單元。
(2)早期大多數程式語言都是基於此種計算機架構來設計的。

2.平行機器(parallel machine)：
(1)此類電腦中可包含多個處理器(multi-processors)同時執行。
(2)可支援程式語言中的並行性。

(二)程式設計方法論(Programming Methodologies)：
1.非結構化程式設計(non- structure programming)。
2.結構化程式設計(srtucture programming)→ALGOL 60。
3.自上而下程式設計(top- down programming)。
4.步進精緻法(step- wise refinement)。
5.資料抽象化(data absrtaction)→SIMULA 67。
6.函數型程式設計(functional programming)→LISP。
7.邏輯程式設計( logcial programming)→PROLOG。
8.個體導向程式設計(OOP)→C++, Smalltalk, Eiffel。
另外，函數型程式設計+ OOP→CLOS
邏輯程式設計  + OOP→PROLOG ++

```

# 高階語言之發展系譜
```
一、FORTRAN ( FORmula TRANslation, 1954)
(一)歷史上第一個開發成功的高階語言。
(二)適合於解決工程與科學上的問題。
(三)檔案的控制能力較差，不適合作為資料處理之商用語言。
(四)程式撰寫採用固定格式(fixed format)，且最早提供輸入/輸出的資料格式。
(五)提供隱含式變數宣告(implicit variable declaration)功能。
(六)DO- LOOP : FORTRAN IV採先執行後檢查，FORTRAN 77採先檢查後執行。
(七)IF敘述：具有Block IF、ELSE IF敘述及巢狀Block IF結構。
(八)FORTRAN 90的重要特性:
1.提供內建的陣列運算函數，如DOTPRODUCT，MATMUL，
TRANSPOSE，MAXVAL，MINVAL，PRODUCT及SUM等。
2.陣列儲存體可由使用者下命令動態地配置及釋除。
3.增加新的控制敘述，如CASE用於多元選擇，EXIT用於直接跳出迴圈，CYCLE用於轉移控制權至迴圈底部但未跳出。
4.副程式可以遞迴呼叫並提供關鍵字參數(keyword para-meter)。
5.可提供資料抽象化之功能。

二、ALGOL 60 (ALGOrithmic Language，1960)
(一)輸入/輸出採自由格式(free format)。
(二)最早提供保留字(reserved word)。
(三)要求外顯變數宣告(explicit variable declaration)。
(四)反覆敘述(iteration)為FOR敘述，此為高階語言中最複雜的迴圈敘述。
(五)最先引進區段結構(block structure)、結構化程式設計及遞迴程序(recursive procedure)。
(六)主程式與副程式之間預設的參數傳遞法為call by name。
(七)提供堆疊動態陣列(stack-dynamic array)。
(八)嚴密的語法定義：首先以BNF來描述語法。

三、COBOL(COmmon Business Oriented Language，1959)
(一)具有大量資料的輸入輸出、檔案處理以及製作報表的卓越能力，適合商業上使用。
(二)使用近似英文的句子及片語，優點是容易閱讀及理解，缺點是程式變得冗長，編寫程式需要比較長的時間。
(三)為與機器無關的標準化程式語言，具有高度的移轉性。
(四)缺乏複雜之計算處理能力，因此複雜的數學、科學或工程之間題或計畫不適用。
(五)最先引進雜訊字(noise word)及階層化資料結構(hierarchical data structure)
(六)歷史上最早被標準化的程式語言。

四、ALGOLW(1966)
(一)參數傳遞首先採用call by value-result。
(二)最早使用case敘述。
(三)具有記錄及指標結構。

五、ALGOL 68 (1968)
(一)最早提供使用者定義之資料型態(user-defined data types)
(二)參數傳遞採call by value，但以指標為參數時可達到call by reference的效果。
(三)具有記錄(record)及指標(pointer)結構。
(四)正交性最高的語言。
(五)提供真正的動態陣列(dynamic array)，稱為flex arrays。

六、APL (A Programming Language, 1960左右)
(一)採用不標準字元集，既非ASCII，亦非EBCDIC。
(二)提供識別號之領域(scope)觀念。
(三)提供眾多功能強大的運算子(operator)，但對實作造成困難。
(四)允許陣列的整體運算。
(五)擅於解決數學問題，如陣列及向量的應用。
(六)提供動態型態(dynamic typing)及動態儲存體配置(dynamic storage allocation)功能。
(七)被認為是一種適合「丟棄式J ( throw-away)程式設計的語言，即程式可以很快寫出來，但因用完後很難維護，故須丟棄。
七、LlSP (List Processor, 1960年左右)
(一)最早為人工智慧(Artificial Intelligence)的應用而發展之語言。
(二)資料與程式同一種表示法一稱為符號運算式(S-expression)，因此資料可視為程式來執行，而程式可當做資料作修改。
(三)運算式採用劍橋波蘭式表示法(Cambridge Polish notation)。
(四)以串列( list )做為主要的資料結構，最小的元素稱為原子(atom) 。
(五)運算符號採用一些識別號，如PLUS (+) TIMES (*)。
(六)採用「垃圾收集法」 ( garbage collection) 來進行記憶體管理。
(七)以遞迴( recursive )做為主要的迴圈控制結構，而一般程式語言則以反複迴圈( iterative loop) 做為主要的迴圈控制結構。
(八)能自由製作推論功能，效率高卻難懂，被視為「人工智慧用低階語言」。

八、PROLOG (PROgramming in LOGic, 1972)
(一)為敘述性( declarative )程式語言，程式師只要描述與問題有關的事實及推論規則(inference rule) 即可，而不必管如何解決該問題的程序，因此屬於非程序性語言(nonprocedural language)。
(二)程式與資料的型態相同，皆為Horn子句(Horn clauses)。
(三)屬於邏輯型程式語言，能處理符號資料之動態資料結構，並且在執行時創造新的資料結構。
(四)推論時以模式配對( pattern matching) 方式來決定使用那一條規則或事實。
(五)效率低但容易學，被視為「人工智慧用高階語言」。

九、SNOBOL (String Oriented Symbolic Language, 1962 )
(一)具有字樣資料型態( pattern data type )。
(二)具有字串處理(string manipulation) 及字樣匹配(string patternmat-ching) 能力。
(三)主要應用為Text editor及Language processor 。
(四)提供動態型態及動態儲存體配置功能。

十、PL/1 (Programming Language/1，1965)
(一)集合FORTRAN (個別編譯及經由整體資料進行溝通)、ALGOL 60(遞迴及區段結構)以及COBOL (資料結構、輸入/輸出和報表產生功能)之特性。
(二)副程式可以遞迴呼叫，也可以關閉此種功能，以產生較有效率的非遞迴程式碼。
(三)具有浮點數( floating-point)資料型態。
(四)最先具有例外處理(exception handling)的能力。
(五)最早提供多重任務(multi-tasking)→並行處理。
(六)最早提供指標(pointer)資料型態。
(七)陣列可以切割出來使用，例如：將某一列當成一個向量來用。
(八)首先以維也納定義語言(Vienna Definition Language)來描述語意(semantics )。

十一、SIMULA 67 (SIMULATION, 1967)
(一)最早引進資料抽象化(data abstraction)概念：一類別(class)把程式中的一群宣告和程序組合成一個單元，即是一個類別。
(二)最早提供coroutine :有多重入口之副程式，允許副程式從先前暫停的地方重新啟動，繼續執行。此種特性使SIMULA 67適合處理模擬應用的問題。

十二、PASCAL (為紀念法國數學家Blaise Pascal而命名，1973 )
(一)使用者可自行定義資料型態( user-defined data type )。
(二)最早引進集合幫手型態(set data type)及子區間(subrange)型態。
(三)區段結構只包含程序( procedure )及函數( function) 。
(四)程式不允許個別編譯(separate compilation)，因此不適合開發大型的系統。
(五)通常用於程式設計之教學( teaching programming )。

十三、BASIC ( Beginner's AII-purpose Symbolic Instruction Code, 1964)
(一)簡單而且易學，與FORTRAN程式語言的特徵類似，文法、規則及結構與一般的數學公式非常接近。
(二)具有交談性( interactive) 當計算機碰到立即執行型敘述( immediate execution mode statement) 
    (亦即不以列號前導的敘述)時就直接將該敘述解碼並且執行，因此使用者可透過立即執行型敘述與計算機直接作交談;這種交談的特性適合於教學。
(三)由直譯程式( interpreter )執行:按程式執行時敘述的邏輯順序逐條翻譯並且執行，所需求的記憶體空問很小，
     因此目前許多小型及微型計算機都採用BASIC為基本的程式語言。
(四)BASIC語言的缺點包括：
1.結構鬆散，大量使用GOTO易破壞程式結構。
2.缺乏局部變數和整體變數的概念，大程式不易維護。
3.缺乏表達複雜資料結構的能力。
(五)QuickBASIC及Visual BASIC是兩個較新的版本。前者增加許多新的控制結構及新的函數(程序)而後者是以前者為基礎，並支援視窗式使用者界面(window user interface)之發展。

十四、C (Common language, 1972)
(一)利用C語言能寫出效率上能與組合語言寫的程式相抗衡卻比較容易了解的程式-C語言擁有豐富的運算符號，甚至於提供了通常組合語言才有的位元運算，而且它的運算式其有很大的彈性，比其他的高階語言更接近機器語言，因此C語言已成為發展系統程式的利器，例如UNIX作業系統本身百分之九十以上用C語言撰寫。
(二)C語言是一種自行編譯( self-compiled )的語言一-C語言的編譯程式大部分都是利用C語言本身編寫。
(三)C語言的程式是由一層的函數所組成。

十五、CLU (CLUSTER, 1973~1979)
(一)CLU是一個ALGOL-like語言。
(二)提供資料抽象化功能，以c1uster作為定義抽象資料型態之程式單元。
(三)提供例外處理的能力。

十六、Modula-2 ( 1985 )
(一)為Pascal的作者Wirth修改Pascal語法後所新發展出來的語言，其前身為Modula。
(二)提供資料抽象化功能，以module作為定義抽象資料型態之程式單元。
(三)可支援並行常式(coroutines)及系統程式設計。
(四)Modula-3 (1989)語言中增加了個體導向程式設計、例外處理、垃圾收集及並行性等功能。

十七、Oberon (1988 )
(一)為Wirth繼Modula-2之後再設計出來的語言，此語言特別強調其簡單性(simplicity )。
(二)雖然Oberon是在Modula-2中加入一些新的特性所產生出來，但也從Modula-2中移除掉很多的功能。
    因此Oberon是一個比其前身(Modula-2 )更小和更不複雜的新語言。
(三)Oberon所新加入的主要特性是型態擴展(type extension)功能，用以支援個體導向程式設計。
(四)Oberon從Modula-2中刪除掉的功能包括:可變記錄(variant records)、不透明型態(opaque type)、列舉型態、子區間型態、CARDINAL型態、非整數陣列註標、with敘述及for敘述。

十八、Ada (紀念Ada Augusta Byron女士)
(一)為美國國防部採用作為融入式計算機系統(embedded computer system)之程式語言。
    融入式計算機系統係利用一己設計好的計算機系統來控制另外的計算機系統如飛彈發射系統。
(二)支援資料抽象化：以package作為定義抽象資料型態之程式單元。
(三)提供平行處理功能：以task為並行執行之程式單元。
(四)提例外處理功能，融入式計算機系統主要是透過這項功能完成的。
(五)每個資料項都必須定義資料型態，並由編譯程式檢查是否有錯，因此，很容易撰寫無錯程式(error-free program)。
(六)Ada是一種強型態語言( strongly typed language)。
(七)Ada 95的重要特性：
1.支援圖形使用者界面( graphical user interface )。
2.支援個體導向程式設計(object-oriented programmìng)。
3.提供更有彈性之程式庫─hierarchical library。
4.對共享資料提供更好的控制機制(control mechanism)。

十九、Smalltalk (1980)
(一)為最早的個體導向語言，不僅僅是一種語言，Smalltalk亦是一個程式發展環境，及一種程式設計方法論(OOP)之代表。
(二)程式完全是由個體(object)所組成，個體之問透過訊息傳遞(message
 passìng)進行溝通，個體的抽象化描述稱為「類別」(class)。
(三)	Small talk的類別引用自SIMULA 67之類別，都只其有單一繼承(single inheritance)的功能。
(四)	變數具有動態型態繫結(dynamic type binding)的特性。

二十、C++ ( 1984~1990)
(一)為在C語言中加入許多新特性後發展出來的語言，其中最重要的是新增加個體導向程式設計功能。這是目前最常用的個體導向語言。
(二)C++的類別具有多重繼承(mutiple inheritance)的功能。
(三)動態型態繫結功能是由虛擬函數(virtual function)提供。
(四)可提供例外處理功能，但只能處理使用者定義的例外，而無法處理由軟體或硬體所引發的例外。
(五)不像Smalltalk是單純的個體導向語言，C++是結合命令式語言特性的個體導向語言。
(六)Eiffel(1992)亦是一個結合命令式語言特性的個體導向語言，它較小也較簡單，不過具有與c++相似的表達性和可寫性，但普及率遠不及C++。

```

# 範例精選[考問答題的準備模式]
### 
```
舉出並說明四種針對程式語言提供程式可靠度( Reliability )之評核指標。( 91 高考)
```
```
答：程式語言提供程式可靠度的評核指標如下：

(一)型態檢查( type checking)：
1.在編譯時期或執行時期檢查程式中是否有資料型態上的錯誤稱之。
2.有提供型態檢查者其程式可靠度較高。
3.編譯時期型態檢查所發現的錯誤，其修改成本叉低於執行時期型態檢查之錯誤修改成本。

(二)例外處理(exception handling)
1.當系統偵測到程式執行時由硬體或軟體所引發的不正常事件或錯誤時，可自動進行處理，再恢復程式執行的能力稱之。
2.有提供例外處理功能者其可靠度較高。

(三)別名之限制(aliasing)
1.允許以兩種或多種名稱來存取同一塊記憶體稱為別名。
2.程式語言若有限制別名之使用可提高程式之可靠度。

(四)可讀性( readabìlity )與可寫性( writabilìty )：
l.可寫性是指容易建立程式(即以較自然方式撰寫程式)之特性，可寫性越高越容易修正程式之錯誤。
2.可讀性是指容易閱讀和容易了解的特性，程式的可讀性越高將越容易撰寫也越容易修改。
```
### 
```
何謂Imperative language ?請舉一個例子說明其語言的特性。( 91 基層特考)
```
```
(一)命令式語言(Imperative language)主要是藉由指定運算來改變變數的狀態以完成程式所執行工作之語言。
(二)以PASCAL語言為例，其主要的特性如下：
1.主要的運算是變數值之指定。
2.程式屬於命令導向式(command oriented)，並且以敘述層次的控制結構來執行演算法，如if、case等選擇結構，和for、while、repeat-until等重複結構。
3.運算式採用中序式表示法，而副程式呼叫則採用普通前序事表示法。
4.程式結構是一種以程序和函數為單元的區段結構(block structure)
5.提供整數、實數、字元、布林等基本資料型態，列舉、子區間等使用者定義型態，陣列、結構、集合、檔案等結構化資料型態，以及指標型態。
6.運算式的計算可經由邊際效應來完成，亦即在計算的過程中可以改變變數的儲存內容。
7.採用靜態領域法( static scoping)決定自由變數之定義。
8.程式執行時進行動態之記憶體管理(dynamic storage management)。
```
### 
```
請說明並舉例一個程式語言過合於下列的應用領域。
(一)商業應用領域。
(二)人工智慧應用領域。
(三)科學應用領域。
(四)網路應用領域。
(五)資料庫應用領域。(92 交通士晉佐級升資考)
```

答：(一)商業應用領域：強調商業上大量資料的輸入輸出、檔案處理及報表印製功能，並能提供定點數之精密運算，COBOL即為適用於此應用領域之程式語言。
(二)人工智慧應用領域：要求能夠很有效率地處理串列中的符號資料，並能方便地製作推論功能，LISP即為適用於此應用領域之程式語言。
(三)科學應用領域：著重於複雜的計算處理能力，支援大量數學函數，並提供浮點數運算功能，FORTRAN即為適用於此應用領域之程式語言。
(四)網路應用領域：必須能適用於網際網路之設計環境，強調程式之安全性和移植性，Java即為適用於此應用領域之程式語言。
(五)資料庫應用領域：必須能有效地描述資料庫結構和處理資料庫中資料，並提供使用者方便查詢的功能，SQL即為適用於此應用領域之程式語言。

四、解釋名詞：
(一)Collaboration diagram。
(二)CMMI (Capability Maturity Model-Integrated)。
(三)Structure chart。
(四)Class diagram。 ( 92 公務特考)
答：(一)Collaboration diagram (合作圖)合作圖主要用來描述一個使用個案中之參與物件及物件間的互動行為，其強調以物件的結構化組織表達物件間的訊息傳送/接收與處理程序。合作圖的主要元件包括類別之物件、連結、訊息與操作等。
(二)CMMI (能力成熟度模式整合) : CMMI是一個可以改進系統工程和軟體工程的整合模式，這是美國卡內基美隆大學在CMM國際認證成功推廣以後的新修訂版本，在國際上廣泛地應用在軟體工程、系統工程以及採購方面，可以說是國際間普遍認同的一種軟體生產程序標準，也是世界各國資訊機構採行的能力提升及認證方法。
(三)Structure chart (結構圖)結構圖示一種描述主要設計原則及決策的模組階層圖，其最小的組成單元為模組。結構圖適合用來描述系統功能的分割情形以及模組之間的介面。
(四)Class dìagraal (類別圖)：類別圖用來描述系統中各類別的靜態結構，亦即類別的組成及彼此之間的關係。類別圖的主要元件包括類別或物件、屬性、關係及基數。

五、舉出並簡釋程式語言之四大評核指標(Evaluation criteria)。
(93 退役軍人轉任女務人員特考)
答：(一)可讀性(readability)：容易閱讀與容易了解的特性。
(二)可寫性(writability)：容易建立程式的特性。
(三)可靠性(relìabìlity)：語言的設計可讓使用者不易犯下錯誤，即使犯錯也很容易找出來之特性。
(四)成本(cost)包括：
l.學習成本。
2.撰寫程式之成本。
3.編譯成本。
4.執行成本。
5.編譯程式之建構成本。
6.低可靠性之成本。
7.維護程式之成本。

六、我們通常將程式語言分為五代。
(一)請問第一代程式語言所指為何？
(二)第二代程式語言一般指的是「高階語言」又稱為「程序導向語言」請說明程序導向語言解決問題的方式為何？
(三)第四代程式語言一般指的是「問題導向語言」 (problem oriented language)，例如SQL，請說明SQL解決問題的方式為何？
(四)第五代程式語言一般指的是「自然語言」(nature language)，又稱為「知識庫語言」請說明此類語言解決問題的方式為何？ (93 專技檢覆)
答：(一)第一代程式語言是指由二進位碼所組成之機器語言，可直接被計算機接受並執行。
(二)程序導向語言解決問題的方式是一個口令一個動作，使用者必須在程式中明確描述如何解決問題的詳細步驟和程序，計算機才能依據所給定的指令來執行工作，進而解決問題;亦即使用者必須在程式中進行「如何做J (how to do) 之描述。
(三)問題導向語言通常是用來解決某類特定問題的程式語言，如SQL是一種與資料庫查詢處理有關的問題導向語言，它本身是一種非程序導向語言，使用者只須在程式中描述要電腦「做什麼J (what to do) 即可，而不必去管電腦要「如何
做」(how to do) 的問題。
(四)自然語言乃人類日常生活所使用之語言，目前在電腦中使用的知識庫語言，通常是一般自然語言的子集合，其可供使用者以自然語言的形式來描述存入知識庫的知識，或是自知識庫中擷取出來的知識，而由系統進行自然語言形式與知識庫內部形式間之轉換。

七、程式語言的發展，由低階至高階演進，各種語言亦有其設計上的特性，請回答下列問題：
(一)C是Dennis Ritchie在1970年在Bell Lab所設計出來的程式語言，請問此程式語言和之前的程式語言有甚麼不同的特性？
(二)Java是昇陽(Sun)公司在1990年新聞發的程式語言，請問此程式語言和之前的程式語言有甚麼不同的特性？
(93 專技檢覆)
答：(一)C語言特有的特性：
1.C語言提供豐富的運算符號，甚至是組合語言才有的位元運算能力，使它比其他高階語言更接近機器語言。
2.利用C語言可寫出效率上能與組合語言相抗衡但卻比較容易了解的程式。
3.C語言很適合用來發展系統程式，如UNIX作業系統。
4.C語言是一種自行編譯的語言，因其編譯程式大部分都是利用C語言編寫的。
5.C語言的所有程式單元都稱為函數。
(二)Java語言特有的特性：
1.Java語言是一種很簡單的語言，它與C++相類似，但比C++容易學習及容易使用。
2.Java語言是一種跨平台的語言，其原始程式經編譯後產生一種稱為byte-code的中間碼，可交由直譯程式來執行。由於此種中間碼是針對虛擬機器設計的，與電腦廠牌無關，故址要在任何電腦上安裝Java直譯程式，即可執行Java之bytecode程式碼。
3.提供多線執行( multi-threads )功能，Java程式具有並行性，可同時允許多條「線」(threads)一起執行。
4.Java語言支援網路程式設計，因其是專為網際網路而設計的，它是一種分散式的語言，適合發展網路應用程式，透過Java可以很容易從網路上取得所需的各種資源。
5.Java語言具有很高的安全性，因其不提供指標，且執行前會先檢查程式的合法性，以避免破壞系統。


八、請說明下列程式語言各有何特性及其適用處？
(一)COBOL
(二)JAVA
(三)C
(四)SQL(Structured Query Language)
(五)HTML(Hypertext markup language )
答：(一)COBOL是一種非常近似英文(English-like)的高階程式語言，具有大量資料的輸入輸出、檔案處理、以及製作報表的卓越能力，適合商業上資料處理之應用。
(二)JAVA是一種物件導向語言，比C++語言來得簡單，可提供跨平台之功能，即程式編譯後可在網路中不同的機器上執行，並且具有多線執行(multiple threads)之並行性，記憶體的管理採用垃圾收集法，執行上具有較高之安全性，是一種適用於網路程式設計之語言。
(三)C語言提供豐富的運算式子及眾多的程式庫，可簡單且完整地表達複雜之運算，它具有高階語言的特性，可達成結構化程式設計與模組化程式設計之需求，亦具有低階語言之特性，可進行位元運算，易於控制週邊裝置，有人稱之為中階語言，是一種適用於開發系統程式之語言。
(四)SQL(Structured Query Language) 可用來描述關連性資料庫之綱目，以及進行資料庫中資料之處理，並提供使用者方便查詢之功能，是一種適用於資料庫應用領域之語言。
(五)HTML(HyperText Markup Language)是一種超文件標記語言，它是依照SGML規格定義出來的，專用於描述網頁(web page)資訊的語言。以HTML所寫成的文件，可以利用全球資訊網的瀏覽器(如IE或Netscape等)將它轉成多采多姿的網頁畫面，供人瀏覽。

九、請各以(一)C ; (二)JAVA；(三)FORTRAN及(四)Visual Basic語言為例，詳述從原始碼程式(Source program)譯成可執行程式(Executable program)之過程。
答：(一)C語言的原始程式碼須先經C的前置處理程式(preprocessor)處理後，產生純C語言之原始程式，再交由C之編譯程式編譯為C的目的程式，最後將此目的程式與所使用到的程式庫(library)交由連結程式產生可執行程式。
(二)JAVA語言的原始程式先交由Java編譯程式進行編譯後，產生稱為Java Byte-Code的中間碼檔案(亦稱為類別檔)，此中間碼檔案可經由網路傳送至任何擁有Java直譯程式之電腦上，交由該直譯程式執行。
(三)FORTRAN語言的原始程式經FORTRAN編譯程式編譯後，可產生FORTRAN目的程式，此目的程式與所使用到的程式庫交由連結程式即可產生可執行程式。
(四)Visual Basic語言的程式稱為專案( project)，其中可包含表單(form)、程式碼、模組和類別等，Visual Basic提供一個整合發展環境(Integrated Develop Environment, IDE)供使用者開發程式，當專案開發完成後，使用者可直接點選IDE 中的執行鈕來執行專案，或者執行「檔案」功能表中的「製成XXX.exeJ 命令來產生可執行檔，其中XXX代表專案名稱。若要產生不需要Visual Basic IDE即可獨立執行之程式檔，必須執行「開始/程式集/Microsoft Visual Basic 6.0/ Microsoft
Visual Basic 6.0工具/封裝暨部署精靈」以產生一個可安裝在Microsoft Windows環境中的獨立系統。

十、請說明在應用系統開發時，如何作測試：
(一)測試之觀念。
(二)整體系統如何作測試。
(三)每個程式如何作測試。
(四)如何撰寫On-line程式，在執行時可讓使用者戚覺回應快？
(五)如何作Benchmark?
答：(一)測試是指當程式可以執行之後，輸入適當測試資料供程式執行，以檢查程式中是否存在邏輯錯誤之過程。
(二)整體系統的測試通常是將整個系統當成一個黑箱(black box)，不需了解其內部細節，只藉由各種輸入資料與系統執行所得結果之比較，來判斷系統是否滿足需求；此種測試可分為功能測試與效能測試，分別用來檢查系統是否符合其功
能性需求與效能之需求。
(三)當程式設計師撰寫完成每個個別程式時，即由程式設計師對該程式進行單元測試，這是一種需要了解程式內部邏輯才能決定程式執行結果的白箱測試(white box testing)工作，藉由各種輸入資料之執行結果來判斷程式的功能是否正確。
(四)在設計線上( on-line)程式時，一方面應選擇執行效率高的演算法來提高執行速度，例如在搜尋大量資料時採用二元搜尋法(binary searching)，避免使用執行效率低的循序搜尋法(sequential searching)另一方面應提供即時回饋功能，當執行較長時間之資料處理工作時，此種功能可讓使用者持續了解目前的執行進度與狀況，而非在使用者下完命令後不明所以地等待一段冗長時間。
(五)Benchmark通常用來比較多家廠商所開發的相同系統之效能，做為選擇之依據。若要進行硬體系統之比較，benchmark可設計為一種包含各類指令的綜合程式，藉由此種benchmark之執行來比較各硬體系統之CPU效率;若要進行軟體系統之比較，benchmark可設計為一種包含各類測試資料的測試個案，藉由此種benchmark之執行來比較軟硬體系統之執行效能。

十一、(一)試說明評鑑一種程式語言優劣之準則。
(二)試以上述準則評鑑一種你(妳)所知之程式語言。
(94 司法特考)
答：(一)評鑑一程式語言優劣之準則如下：
1.高可讀性( readability )容易閱讀與容易了解之特性。
2.高可寫性( writability )容易建立程式之特性。
3.高可靠性( reliability )語言的設計可讓使用者不易犯下錯誤，即使犯錯也很容易找出來之特性。
4.低成本(cost)程式語言的成本包括
(1)學習成本。
(2)撰寫程式之成本。
(3)編譯成本。
(4)執行成本。
(5)編譯程式之建構成本。
(6)低可靠性之成本。
(7)維護程式之成本。
(二)以上述準則評鑑PASCAL語言如下：
1.此語言真有嚴謹的語法及結構化程式設計能力，也有豐富的資料型態，故具有很高的可讀性。
2.因不支援資料抽象化，運算式的表達能力亦不高，致使其可寫性欠佳。
3.PASCAL屬於接近強型態( strongly句ped) 之語言，除了可變記錄之外，型態檢查能力佳，但因為提供例外處理功能，故可靠性只能算上可。
4.在成本方面'PASCAL語言因為簡單，通常做為初學者之學習語言，故學習成本很低，執行成本及編譯程式之建構成本亦很低;但因可寫性欠佳，撰寫程式之成本較高；另外因PASCAL程式無法個別編譯，其編譯成本亦較高；而低可靠性之成本和維護程式之成本皆稍高。

十二、試說明編譯程式(compiler)中，碼最佳化( code optimization)模組之功能及主要之作法，並舉例說明之。
(95地方特考)
答：(一)碼最佳化模組的功能是對編譯過程中產生出來的指令作進一步的改良，使其執行得更快，或占用更少的空間，或是兩者兼備。
(二)主要作法包括
1.消除多餘的指令：
【例l】消除多餘的載入與儲存指令，如下列指令
(1) MOV R0, a
(2) MOV a, R0

因為當(2)執行時，(1)會保證a的值已經存入暫存器R0
中，故(2)的指令可以刪除。
【例2】消除執行不到的指令，如下列C語言指令
#define debug 0
…
if ( debug ) {
偵錯指令
}
因為debug已定義為0 if敘述的條件不成立，大括
號中的「偵錯指令」將不會被執行到，故可刪除。
2.控制流程的最佳化：
【例1】一些轉向到另一轉向的指令，如下的轉向指令序列
goto L1
…
L1: goto L2
可更換為下列指令序列以減少轉向的動作
goto L2
L1: goto L2
【例2】將迴圈不變量之指令移出迴圈之外，如下列C語言
while迴圈
while(i <= limit - 2) /* while敘述中不會改變limit的值*/
可更換為下列指令序列以減少迴園中的指令數目
t= limit - 2
while ( i <= t ) /* while敘述中不會改變limit與t的值*/
3.代數化簡：
【例1】利用代數等式以減少運算指令，如下列等式
x+0=0+x=x
x-0= x
x*1=1*x=x
x/1= x
【例2】把較花時間的運算更換為較省時的運算以降低運算
強度，如下列運算
x**2=X*X
x * 2.0 = x + x
x / 2= x * 0.5
4.使用機器的慣用寫法：例如運用機器指令JUMP來執行goto轉向敘述，或利用自動增加或減少的定位指令來執行加1(如x= x+l)或減1的動作，以提高執行效率。

十三、(一)試說明評鑑一種程式語言優劣之準則。
(二)試以上述準則評鑑一種你(妳)所知之程式語言。
(95 地方特考)
答：(一)評鑑一程式語言優劣之準則如下:
1.高可讀性(readability)容易閱讀與容易了解之特性。
2.高可寫性(writability)容易建立程式之特性。
3.高可靠性(reliability)語言的設計可讓使用者不易犯下錯誤，即使犯錯也很容易找出來之特性。
4.低成本(cost)程式語言的成本包括：
(1)學習成本。
(2)撰寫程式之成本。
(3)編譯成本。
(4)執行成本。
(5)編譯程式之建構成本。
(6)低可靠性之成本。
(7)維護程式之成本。
(二)以上述準則評鑑PASCAL語言如下：
1.此語言其有嚴謹的語法及結構化程式設計能力，也有豐富的資料型態，故具有很高的可讀性。
2.因不支援資料抽象化，運算式的表達能力亦不高，致使其可寫性欠佳。
3.PASCAL屬於接近強型態(strongly-typed)之語言，除了可變記錄之外，型態檢查能力佳，但因為提供例外處理功能，故可靠性只能算上可。
4.在成本方面，PASCAL語言因為簡單，通常做為初學者之學習語言，故學習成本很低，執行成本及編譯程式之建構成本亦很低;但因可寫性欠佳，撰寫程式之成本較高；另外因PASCAL程式無法個別編譯，其編譯成本亦較高；而低可靠性之成本和維護程式之成本皆稍高。

十四、試說明編譯程式(compiler)中，碼產生(code generation)模組之功能及主要之作法，並舉例說明之。
(95 身心障礙人員特考)
答：(一)碼產生模組的功能是產生出的目的程式，此種目的程式可以是一般可重定位的( relocatable )機器語言程式，也可以是組合語言程式。
(二)主要的作法包括
l.為程式中所用到的變數選擇一個合用的記憶體位置。
2.將每一道中間碼指令翻譯為一系列可處理相同工作的機器語言指令。
3.為每一個變數分配一個它能使用的暫存器。
例如下列中間碼指令
temp := id3 * 60.0
id1:= id2 + temp1
可產生如下之目的程式
MOVF id3 , R2
MULF #60.0, R2
MOVF id2, Rl
ADDF R2, Rl
MOVF R1, id1

十五、解釋名詞：
(一)Parsing
(二)Register Management
(三)Loop Optimization
(四)Functional languages                         (95 交通晉高員級升資考)
答：(一)剖析(Parsing)亦稱語法分析(syntax analysis)，意指根據某一語言的文法來分析一個語句(sentence)之語法結構，分析的結果可用一棵剖析樹(parse tree)表示出來。
(二)暫存器管理(Register Management)編譯程式在目的碼產生的過程中，使用暫存器作為運算元之管理工作稱之，主要課題包括
1.暫存器配置(register allocation) ，選出程式中應存入暫存器的各個變數
2.暫存器設定(register assignment)為每一個要存入暫存器的變數指定一個特定的暫存器。
(三)迴圈最佳化(Loop Optimization)藉著減少迴圈中的指令數目或更換為效率高的指令，以提升整個迴圈之執行效率。主要的作法包括
1.將指令移出迴圈之外
2.消去歸納性變數
3.降低運算的強度。
(四)函數型語言(Functional Languages)主要是以函數的應用及遞迴呼叫來完成程式所要執行工作之語言。

十六、比較下列三種程式語言的異同: Fortran，C ，java。
( 95 交通晉高員級升資考)

答：(一)相同點：這三種語言都是高階程式語言，也都可歸屬於命令式程式語言。
(二)相異點：
1.FORTRAN是一種結構性很低的程式語言，適合用來開發解決工程與科學問題之程式，其程式之撰寫採用固定格式，並且提供隱含式變數宣告功能。
2.C語言是一種自行編譯的程式語言，其編譯程式大部分都適用C語言撰寫的；C語言提供許多組合語言才有的位元運算能力，使它比其他高階語言更接近機器語言，因此它很適合用來開發系統程式，如UNIX作業系統。
3.Java語言是一種物件導向語言，具有多線執行(multithreads)的並行處理能力，它也是一種跨平台的程式語言，可支援網路程式設計，適合發展網路應用程式。

十七、程式語言的定義與它的編譯器有何關係？為何一個C語言的定
義會有許多廠商提供不同的編譯器？               (95 交通晉高員級升資考)
答：(一)程式語言的定義決定了編譯器中與機器無關的部分，例如編譯器中語彙分析程式、語法分析程式及語意分析程式之功能都要根據程式語言的定義來決定。
(二)編譯器中的目的碼產生程式必須根據目的程式執行之硬體機器架構來決定產生何種機器碼，因此是與機器有關的部分。在C語言中，各資料型態所占用的記憶體大小，會隨著不同的硬體機器而相異，例如整數( int) 型態的儲存體占一個記憶體字(memory word)，有些廠商的硬體機器中一個記憶體字是2個byte有些則是4個byte或其他大小；因此一個C語言的定義會有須多廠商提供不同的編譯器。

十八、(一)試說明程式撰寫與應用系統開發如何確保軟體安全(software Security)
(二)試舉例說明如何作系統測試及系統效能評估( benchmarks)。
(96 司法特考)
答：(一)在軟體開發過程中即將安全性(security)納入，採取的流程如下：
1 .需求制訂階段(Requirement and use cases)在此階段中將已知以及未來可能遇到的安全性需求納入考量，並且製作實際發生安全狀況的個案，來探討遇到安全性問題時軟體的反應。
2.軟體架構設計階段( Design and architecture )在此階段制定統一的安全性處理機制，例如:統一的例外處理機制，並且將程式中的假設明確標出。
3.制定安全性測試計畫(Security test plan)將可能發生的安全性問題以及測試方法訂出。
4.程式撰寫階段(Coding)在此階段中專注於實作上可能出現的程式問題，例如緩衝區溢位等，撰寫者必須考慮所有程式執行流程的可能性，並且利用程式分析工具去分析程式中可能潛在的問題。
5.程式測試階段( Testing )此階段依照事先定義的測試計畫，產生適當的測試個案(test case)，去測試軟體遇到攻擊時是否能夠正常執行。
6.軟體維護階段(Maintenance)此階段會建立基本回歸測試個(Regression cases)，確保未來軟體的更動不會影響到已有的功能。
(二)如何進行系統測試及系統效能評估：
1.系統測試：將整個系統當做一個黑箱( black box)，對系統內部實作細節不做任何假設，然後藉由各種輸入資料與系統執行後所得的結果做比較，來測試此系統是否有滿足需求，其中文分為功能性測試與效能測試，分別用來測試系統功能是否正確，以及系統效能是否符合需求。
2.系統效能評估：可藉由效能評估工真(Profiling tool)來分析系統的效能。例如：若是分析統計軟體的效能，則可以將大量統計資料餵入系統中執行，依照效能評估軟體來分析其執行速度以及記憶體使用量；若是分析顯示卡硬體效能，則可以將大量複雜圖形資料送入顯示卡中，利用顯示卡的效能評估工其來測試顯示卡之速度。
```
