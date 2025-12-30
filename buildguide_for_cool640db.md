 　# Buildguide for cool640db
<br>

## 0 部品の確認

![](img/img00012.jpg)

<br>
Follow the BOM on github's readme.md to make sure that all the parts are available.
<br>
githubのreadme.mdのBOMに沿って、部品が全て揃っているかを確認してください。
<br>
There are four PCBs. Of the three pieces, two are left and right keyboard boards, and the remaining two are  trackball boards.
<br>
Bが4枚あります。表裏を確認してください。4枚のうち、2枚が左右のキーボード基板で、残り2枚がトラックボール基板です。
<br>

## 1 ダイオードのはんだ付け

If the diode is already soldered, please skip this operation.
<br>
すでにダイオードのはんだ付けされている場合は、この作業を省略してください。
<br>
<br>
This work is done on the left and right keyboard boards respectively.
<br>
この作業は左右のキーボード基板でそれぞれ行います。
<br> 
Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
The diode is compatible with SMD and lead type.
<br>
ダイオードは、SMDとリードタイプに対応しています。
<br>
Diodes have polarity, so be careful about the direction in which they are installed.
<br>
ダイオードには極性がありますので、取り付ける向きに注意してください。
<br>

[ダイオード（SMD)のはんだ付けの動画](https://youtu.be/ODk16bd4XkA)
<br>
[ダイオード（リードタイプ）のはんだ付けの動画](https://youtu.be/lbAQkKzNawM)
<br>
[ダイオード（リードタイプ）のはんだ付けの動画２](https://youtu.be/3hWZjaBROL8)

<br>

## 2  スイッチソケットのハンダ付け

cool640db supports chocswitch sockets.
<br>
cool640dbでは、chocのスイッチソケットに対応しています。

<br><br>
Solder the switch socket on the back of the left and right keyboard boards.
<br>
左右のキーボード基板の裏面にスイッチソケットのハンダ付けをします。
<br>

[Switch socketハンダ付け動画](https://youtu.be/ZnbgaueMR4w?si=_JLjD--3HJJ5Pu7Q)

![](img/img00006.jpg)

![](img/img00008.jpg)

![](img/img00010.jpg)
<br>

## 3 Seeed xiao bleのハンダ付け

<b>Note</b>
次の動画を参考にしてください。
<br>

[xiao bleのハンダ付け動画](https://youtu.be/98yqLjzfdl4)




#

## 4 スライドスイッチのハンダ付け

Insert the switch from the front of the PCB with the switch knob facing outward.
<br>
スイッチのつまみが外側に向くようにして、PCBの表面から差し込みます。

After temporarily fixing it with masking tape, etc., solder the exposed part of the PCB.
<br>
マスキングテープなどで仮固定をしてから、PCBの裏面に出た部分をはんだ付けします。
<br>


[スライドスイッチのはんだ付けの作業動画](https://youtu.be/5nkRklibay4)



## 5　リセットスイッチのハンダ付け

Insert the reset switch from the bottom of the board.
<br>
基板の下面からリセットスイッチを挿入します。
<br>
Cut off any leads sticking out from the board using pliers or similar.
<br>
基板からはみ出たリードをニッパーなどで切り取ります。
<br>
Then, solder it.
<br>
その後、ハンダ付けをしてください。
<br>

[リセットスイッチハンダ付け動画](https://youtu.be/Pl24Exfh8b8)


## 6 トラックボール基板の作成

![](img/img00013.jpg)

![](img/img00014.jpg)

Caution PMW3610 is prone to sensor damage when exposed to high temperature heat. Please complete the soldering of each pin in a short time.
<br>
注意　PMW3610は高温の熱にさらされるとセンサーの破損が発生しやすいです。それぞれのピンのはんだ付けは短時間で済ませてください。
<br>
As for my example, soldering is processed in 2-3 seconds per pin.
<br>
私の例ですが、はんだ付けを１つのピンにつき、2〜3秒で処理します。
<br>
<br>
Note: The silk of "Front side" and "Back side" on the board is written for the ball.
<br>
注意　基板に「Front side」や「Back side」のシルクは、ボールに対しての表記です。
<br>
<br>
The trackball board has components installed from the beginning. The implemented side is the back side.
<br>
トラックボール基板は最初から部品が実装されています。実装されている面を裏面とします。
<br>
<br>
Remove the PWM3610 acrylic parts.
<br>
PWM3610アクリル部品を取り外します。
<br>
<br>
Check the pin of the PMW3610 and insert it from the surface of the trackball board. Temporarily fix it with masking tape.
<br>
PMW3610のピンを確認して、トラックボール基板の表面から差し込みます。マスキングテープで仮固定します。


<br>
<br>
The back of the trackball board is facing up and the part that came out of the pin hole is soldered.
<br>
トラックボール基板の裏面を上向きにして、ピン穴からでた部分をはんだ付けします。
<br>
<br>
The lens part of the PMW3610 is covered with tape, so remove it.
<br>
PMW3610のレンズ部分がテープで覆われているので、それを外します。
<br>
<br>
From the back of the trackball board, cover the acrylic part on the PMW3610, and melt the acrylic on the back with a soldering ick to prevent it from coming off.
<br>
トラックボール基板の裏面の方から、アクリル部品をPMW3610に被せて、その裏側に出たアクリルをハンダごてで溶かして外れないようにします。

<br>
<br>

## 7 センサー基板のはんだ付け

The sensor board created in step 7 is fixed to the circuit board by soldering it with the pin head in between.
<br>
7で作成したセンサー基板を基板にピンヘッドを間に挟んではんだ付けして固定します。
<br>

![](img/img00006.jpg)

Please refer to the diagram above when soldering. When doing so, use pliers or similar to cut off any protruding pin heads.
<br>
上の図を参考にして、はんだ付けをしてください。その際、はみ出たピンヘッドはニッパーなどで切り取ってください。
<br>

Note<br>
トラックボールセンサー基板のはんだ付けの成否を知らずに、基板にそれらをピンヘッドではんだ付けすることに不安のある場合は、７ピンの2.5mmコンスルーを使って、仮固定をすることを勧めます。仮固定で、動作に問題ないことを確認してから、コンスルーのはんだ付けをします（はんだ付けしないと、振動で外れることがあります）。
<br>
コンスルーの７ピンは通常では販売されていないので、12ピンをカッターなどで切断して用意してください。
<br>
<br>


## 8 ロータリーエンコーダのはんだ付け

Insert the rotary encoder from the front side of the PCB and solder it on the back side of the PCB.
<br>
PCB表面から、ロータリーエンコーダーを差し込み、PCB裏面ではんだ付けをします。

<br><br>
The rotary encoder has three claws on one side, one claw on both sides, and two claws on the other side.
<br>
ロータリーエンコーダーには1辺に３つの爪があり、その両脇の辺に１つの爪があり、残り１辺に２つの爪があります。
<br>
Of these, 3 nails and 2 nails are the parts related to the input, so we will solder them.
<br>
このうち、３つの爪と２つの爪は入力に関わる部分ですので、はんだ付けをします。
<br>
For one nail, there is no problem without soldering.
<br>
１つの爪については、はんだ付けしなくても問題ありません。
<br><br>


## 9a スイッチプレートの組み立て(choc)

Stack the switch plate and PCB in this order from the top, and insert four M2 5mm screws from the top.
<br>
Fix the four points from the bottom of the PCB with M3 3mm spacers.
<br>
上からスイッチプレート、PCBの順番で重ねて、上からM2 5mmネジを４本差し込みます。
<br>
PCBの下からM3 3mmスペーサーで４箇所を固定します。
<br>
<br>
There are 4 places each on the left and right, a total of 8 places.
<br>
左右それぞれ4箇所で、合計8箇所行います。
<br>


## 9b スイッチプレートの組み立て(cherryMX)

Insert the M2 8mm screw from the top of the switch plate.
<br>
Fix it with an M2 3mm spacer on the bottom of the switch plate.
<br>
スイッチプレート上面からM2 8mmネジを差し込みます。
<br>
それをスイッチプレート下面でM2 3mmスペーサーで固定します。
<br>
<br>
Overlay the switch plate on the PCB.
<br>
There are some M2 8mm screws on the underside of the PCB, so fix them with an M2 3mm spacer.
<br>
There are 4 places each on the left and right, a total of 8 places.
<br>
スイッチプレートをPCBに重ねます。
<br>
PCB下面にM2 8mmネジが少し出ますので、M2 3mmスペーサーで固定します。
<br>
左右それぞれ4箇所で、合計8箇所行います。


## 10 スイッチの差し込み

Plug your favorite key switch into the one you made in section 8.
<br>
When plugging in, it may not be plugged in properly and the terminal of the key switch may bend.
<br>
Please be careful.
<br>
If it is bent, it can be repaired with radio pliers, etc., and it can be reused.
<br>
It's a mistake you often make, so don't worry about it, plug in the key switch more and more.

<br>
セクション8で作ったものに、自分のお気に入りのキースイッチを差し込みます。
<br>
差し込むときに、うまく差し込めず、キースイッチの端子が曲がってしまうことがあります。
<br>
気を付けてください。
<br>
もし曲がったときは、ラジオペンチなどで直しせば、再利用できます。
<br>
自分もよくやるミスなので、気にせず、どんどんキースイッチを差し込みましょう。
<br>
<br>


## 11 ボトムプレートの取り付け

Insert four M2 3mm screws from the bottom of the bottom plate to secure it. The left and right bottom plates have different shapes, so please align them with the switch plate.
<br>
ボトムプレートの下面からM2 3mmネジを４箇所差し込んで、固定してください。ボトムプレートは左右の形が違いますので、スイッチプレートと向きを合わせてください。
<br>
<br>
The side with the recess to hide the screw heads will be the bottom of the bottom plate.
<br>
ネジの頭を隠すための窪みがある方がボトムプレートの下面になります。
<br>
<br>

## 12 トラックボールケースの固定

Install the trackball board to fit the 7 pins of the L-shaped through on the right side of the keyboard board.
<br>
Insert 2 M2 4mm screws from the inside of the ball case and fix it with an M2 3mm spacer on the bottom of the ball case.
<br>
Insert the ball case so that it can be put on the trackball board.
<br>
The spacer on the bottom of the ball case is inserted into the concave part of the bottom case.
<br>
Insert 2 M2 4mm screws from the bottom of the bottom case and fix the spacer.
<br>
トラックボール基板をキーボード基板の右手側にあるL字コンスルーの7ピンに合うように取り付けます。
<br>
ボールケースの内側から2箇所、M2 4mmネジを差し込み、ボールケース底面でM2 3mmスペーサーで固定します。
<br>
ボールケースをトラックボール基板に被せるように差し込みます。
<br>
ボールケース底面にあるスペーサーがボトムケースの凹部に差し込まれるようにします。
<br>
ボトムケース底面から2箇所、M2 4mmネジを差し込み、スペーサーを固定します。
<br> 
<br>
If you want to turn the ball better, put the support ball in 3 places in the ball case. Woodworking bonds are the best for fixing.
<br>
よりよくボールを回したいと考えているならば、支持球をボールケース内に3箇所入れてください。固定には、木工用ボンドが最適です。
<br>
<br>
Please attach a 25mm ball to the ball case.
<br>
ボールケースに25mm球を装着してください。
<br>
<br>

## 13 キーキャップの装着

Please attach your favorite keycap (All 1U size).
<br>
お好きなキーキャップ（全て1Uサイズ）を装着してください。
<br>


## 14 完成

After attaching non-slip rubber to the bottom of the bottom case, it's done.
<br>
Please enjoy a life with a better keyboard.
<br>
ボトムケースの底面に、滑り止めゴムを取り付けたら、完成です。
<br>
よりよいキーボードのある生活を楽しんでください。
<br>

## 15 動作確認について

ファームウェアの導入について、こちらの記事を参考にしてください。
<br>
[自作キーボードへのzmk_firmwareのインストールについて](https://sizu.me/m_ki/posts/kvixkn2mec6a)

<br>
Keymapの編集について、こちらの記事を参考にしてください。

[zmk_firmwareでのキーマップ編集について](https://sizu.me/m_ki/posts/m3devs7be5km)


![](img/img00001.jpg)


