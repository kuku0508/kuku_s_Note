---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
類別資料分析-Categorical Data Analysis ^pJEwXkTZ

類別資料(Categorical Data)
- A categorical variable has a measurement scale consisting of a set of categories
there are two type of categorical data, Nominal and Ordinal
For example
- yes or no
- male or female
- correct or incorrect
- DPP or KMT ^eLCuUd6q

Nominal Variable 無序變數 ^ssiU08Wq

- The order of listing the categories is irrelevant
- The statistical analysis should not depand on the ordering
For example
- Favorite food(hot-pot, pasta, steak) ^7H6SvIsA

不相關的 ^4YAeJOLl

Ordinal Variable 有序變數 ^phFV3lRq

- Methods uilize the ordering : low -> high or high -> low
- The results of ordinal analyses would change if the categories order changes. ^zhCBVyB5

利用 ^at2tywl8

Methods           Type of Data
Nominal             Nominal

Ordinal             Ordinal ^k2uDyHGJ

Response Variable and Explanatory Variable 反應變數與解釋變數 ^UhSm22c1

- Response Variable   ：dependent variable, Y variable
- Explanatory Variable：independent variable, X variable ^geybpEPO

So, Statistical Models is how response vabiables are influenced by explanatory variables. ^rgMTeqsi

For example： ^xOmC9NYg

annual income

political philosophy

response to a medical treatment
 ^F2N9eQVf

number of years of education ^Odvkmfp5

annual income ^pSs3FKcm

weight ^zTrZ7DsL

Response Variable ^bzRgOFX6

Explanatory Variable ^SoSZbuMW

解釋變數X ^iqxB0ByJ

連續 ^bQ47oTiF

類別 ^hRNC1AD6

類別 ^SwrjxLb2

類別 ^MQDWcxE5

均有 ^qVIWtduj

模式類別 ^KlT87h6G

迴歸分析
Regression ^hQDmjZL7

變異數分析
ANOVA ^ATxWEwAt

共變異分析
ANCOVA ^LmfDJ6NR

線性模式
Linear model ^peVLYEd8

邏輯/羅吉斯
迴歸
Logistic
Regression ^ke58etyk

類別資料分析
對數線性模式
Loglinear 
model
列聯表分析 ^GcZjCxGz

邏輯迴歸
對數線性模式 ^MZ8sJu03

廣義線性模式
generalized 
linear model,
GLM ^adWf5r9a

反應變數 Y ^tfffUely

CDA裡面會遇到的機率分配
1.Binomial distribution
2.Multinomial distribution
3.Special cases：Poisson distribution for count data ^1QgJRoyn

Binomial distribution ^DHTxbuF5

Multinomial distribution ^8zJtMBEy

The binomial distribution is always symmetric when ^qXTMPASy

對稱 ^aUGTnXMj

*中央極限定理 ^QRreH762

Density plot ^Rc1TVcRy

Density plot ^UO5r2jRb

Special case：C=2,  ^tgKb73He

*binomial ^IFxIYdX3

母體比例的推論(Statistical inference for a proportion) ^nnf3dJVO

Possion Distribution ^17s1LyPT

1.點/區間估計
2.檢定 ^w9FEseLK

- Likelihood function：
The probability of the observed data,
expressed as a function of the parameter ^CJmVRioB

表達成 ^6MLbzbBf

我會這樣理解likelihood function，他就是在給定x跟模型的情況下，你的參數是未知。
以binomial為例： ^yYuUJh2W

MLE(Maximum likelihood estimate) ^C5vzEady

The parameter values for which the probability of 
the observed data takes its greastest value
 ^SqA6qPsV

0.2 ^sr15XbOq

0.4 ^pGpRnxUo

0.6 ^23OEM92b

0.8 ^Kn3KXSIx

1 ^YSMoesFF

Given that Y=4 ^V0HACJRM

0 ^nU3WO4Cx

0.5 ^M0ioxR84

0.000 ^LzXnQOH5

0.088 ^QlCegSDv

0.251 ^Ris50Z0O

0.205 ^nl9bl74l

0.111 ^y0s8tXzf

0.006 ^rA8KYrya

0.000 ^f5EZnU3F

MLE in Large Sample：
1.Consistency

2.Asymptotic Mormality

3.Asymptotic Efficiency

4.Invariance ^SNszKe21

# Embedded files
aed8e05b3b3622f40611c680fecd26fe2f9c6530: $$Y\sim B(n,\pi)$$
10a2325614e0e1bc90e410d4783870c5fe8e27dc: $$P(y)=\frac{n!}{y!(n-y)!} \pi^y (1-\pi)^{n-y}$$
fd44c5ae18190c3ba712f432d5510380aa44fc76: $$(n_1,n_2,\ldots,n_c)\sim Multinomial(n,\pi_1,\pi_2,\ldots,\pi_{C-1})$$
968fbd68ae9bad1dad3a92c42c00f9f3ef6c54c9: $$P(y_1,y_2,\ldots,y_c)=\frac{n!}{y_1!y_2!\ldots y_c!} \pi_1^{y_1}\pi_2^{y_2}\ldots\pi_c^{y_c}$$
78c77d8756ff1efb61b38ae615699fc2fd5f19e2: $$\pi=0.5$$
5bf7ac069d54d54681bc9ea3ee29e20cbfb62906: $$n \,is \,fixed, \pi \rightarrow 1 , skewed$$
630f908ec4f12b7b80559a2e57740fe4f7932adc: $$\pi \,is\,fixed,n\rightarrow\infty,bell-shaped$$
6c7ec610ce64cb7d4f84651066fa37d47ac0b23c: $$B(n,\pi)$$
323135651fe2d1fcdb4199dac9fbd49723c7fb2d: $$n_j \sim B(n,\pi_j),for\, jth\, category$$
2bf3bd653fce80c8b2261e2cc6ec8ae0796295c4: $$P(x)=\frac{\lambda^xe^{-\lambda}}{x!}$$
b091f17a1dce1778b463725a9021f95dc888c279: $$Y \sim B(10,\pi)$$
472a060c0a8be60de6a87a31f2a4f69b4b841d0c: $$\ell(\pi)=P(Y=y)=C^y_{10}\pi^y(1-\pi)^{10-y}$$
145e996240338e4f3344611ce8ebf48f1ec45b7a: $$Y \sim B(10,\pi)$$
499754e2157ad7375edc8e17348054afd9c94fe7: $$\ell(\pi)=P(Y=y)=C^y_{10}\pi^y(1-\pi)^{10-y}$$
a23a1969debbd7a31e7d2380d95c073755e8f498: $$\ell(\pi)$$
e06e08ec4855d7079c00b1e9818b19dbd7e8af53: $$\pi$$

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.4",
	"elements": [
		{
			"type": "embeddable",
			"version": 2828,
			"versionNonce": 599614177,
			"isDeleted": false,
			"id": "Fc1xNSJ7PDDVRqM5lOeem",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 113.56230445918845,
			"y": -923.453931578878,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 850,
			"height": 1214,
			"seed": 332641782,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1713726249413,
			"link": "https://drive.google.com/file/d/1Sr1N9N-mxqjsJYugssEQputavcjB0ufK/view?usp=drive_link",
			"locked": false,
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 202,
			"versionNonce": 1561749985,
			"isDeleted": false,
			"id": "pJEwXkTZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -238.5,
			"y": -611.875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 529.7470092773438,
			"height": 34.000000000000036,
			"seed": 287905889,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 27.200000000000028,
			"fontFamily": 1,
			"text": "類別資料分析-Categorical Data Analysis",
			"rawText": "類別資料分析-Categorical Data Analysis",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "類別資料分析-Categorical Data Analysis",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 479,
			"versionNonce": 1967546543,
			"isDeleted": false,
			"id": "eLCuUd6q",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.5,
			"y": -558.875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 838.0994262695312,
			"height": 200,
			"seed": 1845050593,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "類別資料(Categorical Data)\n- A categorical variable has a measurement scale consisting of a set of categories\nthere are two type of categorical data, Nominal and Ordinal\nFor example\n- yes or no\n- male or female\n- correct or incorrect\n- DPP or KMT",
			"rawText": "類別資料(Categorical Data)\n- A categorical variable has a measurement scale consisting of a set of categories\nthere are two type of categorical data, Nominal and Ordinal\nFor example\n- yes or no\n- male or female\n- correct or incorrect\n- DPP or KMT",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "類別資料(Categorical Data)\n- A categorical variable has a measurement scale consisting of a set of categories\nthere are two type of categorical data, Nominal and Ordinal\nFor example\n- yes or no\n- male or female\n- correct or incorrect\n- DPP or KMT",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 153,
			"versionNonce": 827360705,
			"isDeleted": false,
			"id": "gbnoiTE0Xo6sdGvWtVxwb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 409.5,
			"y": -512.875,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 200,
			"height": 1,
			"seed": 458338479,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					200,
					-1
				]
			]
		},
		{
			"type": "line",
			"version": 158,
			"versionNonce": 775189199,
			"isDeleted": false,
			"id": "bA34uOoMUAuF1ITY_i1eS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 184.5,
			"y": -487.875,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 67,
			"height": 0,
			"seed": 580352577,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					67,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 96,
			"versionNonce": 1402742177,
			"isDeleted": false,
			"id": "O2lTnA4wTuirYLp40UqU2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 305.5,
			"y": -488.875,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 68,
			"height": 0,
			"seed": 2114465793,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					68,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 1608204527,
			"isDeleted": false,
			"id": "ssiU08Wq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.5,
			"y": -339.875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 313.98382568359375,
			"height": 31.999999999999964,
			"seed": 1223137583,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 25.599999999999973,
			"fontFamily": 1,
			"text": "Nominal Variable 無序變數",
			"rawText": "Nominal Variable 無序變數",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Nominal Variable 無序變數",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 291,
			"versionNonce": 254331265,
			"isDeleted": false,
			"id": "7H6SvIsA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -223.5,
			"y": -296.875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 602.8994750976562,
			"height": 100,
			"seed": 149521519,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "- The order of listing the categories is irrelevant\n- The statistical analysis should not depand on the ordering\nFor example\n- Favorite food(hot-pot, pasta, steak)",
			"rawText": "- The order of listing the categories is irrelevant\n- The statistical analysis should not depand on the ordering\nFor example\n- Favorite food(hot-pot, pasta, steak)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "- The order of listing the categories is irrelevant\n- The statistical analysis should not depand on the ordering\nFor example\n- Favorite food(hot-pot, pasta, steak)",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 136,
			"versionNonce": 1807960847,
			"isDeleted": false,
			"id": "rduHVas8w4-2tyQq9Zf8l",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 180.5,
			"y": -274.875,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 90,
			"height": 0,
			"seed": 1315364065,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					90,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 490074465,
			"isDeleted": false,
			"id": "4YAeJOLl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 270.8972650698065,
			"y": -283.875,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 53.39996337890625,
			"height": 16.69916016617053,
			"seed": 1034889281,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 13.359328132936422,
			"fontFamily": 1,
			"text": "不相關的",
			"rawText": "不相關的",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "不相關的",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 190,
			"versionNonce": 1852117295,
			"isDeleted": false,
			"id": "oF-i2x6z7Ablhg8F7_eLS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 41.46065408694517,
			"y": -251.18058851523574,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 183.22437706204505,
			"height": 0,
			"seed": 1501930529,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					183.22437706204505,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 247,
			"versionNonce": 1662197057,
			"isDeleted": false,
			"id": "phFV3lRq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.50000012171444,
			"y": -185.87499985928488,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 311.27020263671875,
			"height": 31.999999999999964,
			"seed": 574811471,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 25.599999999999973,
			"fontFamily": 1,
			"text": "Ordinal Variable 有序變數",
			"rawText": "Ordinal Variable 有序變數",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ordinal Variable 有序變數",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 575,
			"versionNonce": 1630081871,
			"isDeleted": false,
			"id": "zhCBVyB5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -223.50000012171444,
			"y": -142.87499985928488,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 794.83935546875,
			"height": 50,
			"seed": 1899391855,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "- Methods uilize the ordering : low -> high or high -> low\n- The results of ordinal analyses would change if the categories order changes.",
			"rawText": "- Methods uilize the ordering : low -> high or high -> low\n- The results of ordinal analyses would change if the categories order changes.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "- Methods uilize the ordering : low -> high or high -> low\n- The results of ordinal analyses would change if the categories order changes.",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 238,
			"versionNonce": 1881132321,
			"isDeleted": false,
			"id": "md56cIaQSckOjP5nfWV6V",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -227.59404451692637,
			"y": -96.07000475900713,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 802.6972709384833,
			"height": 0,
			"seed": 1635197263,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					802.6972709384833,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 173,
			"versionNonce": 2087178607,
			"isDeleted": false,
			"id": "at2tywl8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -78.54300308912269,
			"y": -146.29639095634718,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 21.379974365234375,
			"height": 13.366706218282843,
			"seed": 1820931951,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 10.693364974626274,
			"fontFamily": 1,
			"text": "利用",
			"rawText": "利用",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "利用",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 197,
			"versionNonce": 1003192577,
			"isDeleted": false,
			"id": "k2uDyHGJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220.71964249562848,
			"y": -41.71809878369345,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 331.3997802734375,
			"height": 100,
			"seed": 1905358767,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Methods           Type of Data\nNominal             Nominal\n\nOrdinal             Ordinal",
			"rawText": "Methods           Type of Data\nNominal             Nominal\n\nOrdinal             Ordinal",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Methods           Type of Data\nNominal             Nominal\n\nOrdinal             Ordinal",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 155,
			"versionNonce": 1500105615,
			"isDeleted": false,
			"id": "-URD6t7n9UdFCOMZISVIj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -148.10139943649187,
			"y": -5.408977254125148,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 125.17091895719614,
			"height": 1.9110063962931463,
			"seed": 2019548239,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					125.17091895719614,
					-1.9110063962931463
				]
			]
		},
		{
			"type": "line",
			"version": 146,
			"versionNonce": 597014753,
			"isDeleted": false,
			"id": "CZXQ6Xv3N66bko_gkQA8E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -147.14589623834536,
			"y": -5.408977254125148,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 120.39340296646333,
			"height": 50.64166950176627,
			"seed": 1129277775,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					120.39340296646333,
					50.64166950176627
				]
			]
		},
		{
			"type": "line",
			"version": 129,
			"versionNonce": 1416069551,
			"isDeleted": false,
			"id": "p_wTQ7RIZWVr0Zo-_5cpt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -146.19039304019884,
			"y": 47.14369864393427,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 121.34890616460984,
			"height": 0,
			"seed": 433828655,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					121.34890616460984,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 230,
			"versionNonce": 688780481,
			"isDeleted": false,
			"id": "UhSm22c1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.50000030674926,
			"y": 97.65415513643325,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 762.52001953125,
			"height": 30.733019188879208,
			"seed": 623345487,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 24.586415351103366,
			"fontFamily": 1,
			"text": "Response Variable and Explanatory Variable 反應變數與解釋變數",
			"rawText": "Response Variable and Explanatory Variable 反應變數與解釋變數",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Response Variable and Explanatory Variable 反應變數與解釋變數",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 201,
			"versionNonce": 780760015,
			"isDeleted": false,
			"id": "geybpEPO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -219.76413929748196,
			"y": 143.64952165673424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 549.9995727539062,
			"height": 50,
			"seed": 1682919311,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "- Response Variable   ：dependent variable, Y variable\n- Explanatory Variable：independent variable, X variable",
			"rawText": "- Response Variable   ：dependent variable, Y variable\n- Explanatory Variable：independent variable, X variable",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "- Response Variable   ：dependent variable, Y variable\n- Explanatory Variable：independent variable, X variable",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 167,
			"versionNonce": 1876145313,
			"isDeleted": false,
			"id": "rgMTeqsi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -218.80863609933544,
			"y": 221.04528070660353,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 882.25927734375,
			"height": 25,
			"seed": 321064353,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "So, Statistical Models is how response vabiables are influenced by explanatory variables.",
			"rawText": "So, Statistical Models is how response vabiables are influenced by explanatory variables.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "So, Statistical Models is how response vabiables are influenced by explanatory variables.",
			"lineHeight": 1.25
		},
		{
			"type": "rectangle",
			"version": 175,
			"versionNonce": 1877484015,
			"isDeleted": false,
			"id": "pwfWKdnUZ5p2U9yZd2k7M",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -180.588508173474,
			"y": 222.00078390475005,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 185.3676204404277,
			"height": 24.84308315180988,
			"seed": 536736481,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 140,
			"versionNonce": 2073458817,
			"isDeleted": false,
			"id": "88eHPe89b_1dM_9V1SqWy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 82.17487131682287,
			"y": 241.11084786768072,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 179.63460125154847,
			"height": 0,
			"seed": 1984595759,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					179.63460125154847,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 86,
			"versionNonce": 160173071,
			"isDeleted": false,
			"id": "1yomUMK8AgfzoDy2ThF8U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 314.3621484664309,
			"y": 243.97735746212038,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 94.59481661650693,
			"height": 0,
			"seed": 241847361,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					94.59481661650693,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 119,
			"versionNonce": 773177441,
			"isDeleted": false,
			"id": "UiZqs7QxHsF6WfXQ-w0oM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 450.0436026032387,
			"y": 243.02185426397375,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 211.1662067903842,
			"height": 0,
			"seed": 1734070415,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					211.1662067903842,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 929935919,
			"isDeleted": false,
			"id": "xOmC9NYg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -216.8976297030424,
			"y": 259.26540863246487,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 135.39990234375,
			"height": 25,
			"seed": 2125979983,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "For example：",
			"rawText": "For example：",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "For example：",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 178,
			"versionNonce": 86051905,
			"isDeleted": false,
			"id": "1H_4EibXpwCFU7tqGkDA_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -213.08397973789147,
			"y": 322.36729039041563,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 660.1630292901282,
			"height": 0,
			"seed": 297382689,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					660.1630292901282,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 119,
			"versionNonce": 578131023,
			"isDeleted": false,
			"id": "F2N9eQVf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -204.84665138667788,
			"y": 342.37223067193463,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 325.91973876953125,
			"height": 150,
			"seed": 1936856431,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "annual income\n\npolitical philosophy\n\nresponse to a medical treatment\n",
			"rawText": "annual income\n\npolitical philosophy\n\nresponse to a medical treatment\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "annual income\n\npolitical philosophy\n\nresponse to a medical treatment\n",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 165,
			"versionNonce": 412605473,
			"isDeleted": false,
			"id": "Z9yB7IeQJEKezmsmLu9Fp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -215.43750212395253,
			"y": 434.15960372831603,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 660.1630292901282,
			"height": 0,
			"seed": 86524879,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					660.1630292901282,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 209,
			"versionNonce": 1115435631,
			"isDeleted": false,
			"id": "vySaFfbbDVh0OAEKaVUPt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -213.08397973789147,
			"y": 380.0285888489117,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 658.9862680970975,
			"height": 0,
			"seed": 604281775,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					658.9862680970975,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 151,
			"versionNonce": 1483321345,
			"isDeleted": false,
			"id": "tP2jtRWA-1PAUFyU16kU4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 136.4140945921763,
			"y": 296.4785441437439,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 190.63531327094609,
			"seed": 2092194767,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					190.63531327094609
				]
			]
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 4852879,
			"isDeleted": false,
			"id": "Odvkmfp5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 149.35846768066477,
			"y": 342.3722314092094,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 290.93975830078125,
			"height": 25,
			"seed": 1080838241,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "number of years of education",
			"rawText": "number of years of education",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "number of years of education",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 65,
			"versionNonce": 177604577,
			"isDeleted": false,
			"id": "pSs3FKcm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.947600715512,
			"y": 392.3722305513391,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.41990661621094,
			"height": 25,
			"seed": 479307713,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "annual income",
			"rawText": "annual income",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "annual income",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 58,
			"versionNonce": 395813551,
			"isDeleted": false,
			"id": "zTrZ7DsL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.94760071551224,
			"y": 450.67987578195726,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.69993591308594,
			"height": 25,
			"seed": 908930209,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "weight",
			"rawText": "weight",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "weight",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 39,
			"versionNonce": 153904065,
			"isDeleted": false,
			"id": "bzRgOFX6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -138.948024576968,
			"y": 296.4785441437439,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 173.7998504638672,
			"height": 25,
			"seed": 1144806273,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Response Variable",
			"rawText": "Response Variable",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Response Variable",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 957183183,
			"isDeleted": false,
			"id": "SoSZbuMW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 169.36340799703112,
			"y": 292.9482605646523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 202.57984924316406,
			"height": 25,
			"seed": 1436058977,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Explanatory Variable",
			"rawText": "Explanatory Variable",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Explanatory Variable",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 1078739873,
			"isDeleted": false,
			"id": "iqxB0ByJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -178.957905140006,
			"y": 521.2399320125754,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 91.95999145507812,
			"height": 25,
			"seed": 755159631,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "解釋變數X",
			"rawText": "解釋變數X",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "解釋變數X",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 269,
			"versionNonce": 1816396527,
			"isDeleted": false,
			"id": "bQ47oTiF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -163.66000982363965,
			"y": 623.9699834041172,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 25,
			"seed": 887255233,
			"groupIds": [
				"m1FgdjqmCfsigj1hTFDRX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "連續",
			"rawText": "連續",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "連續",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 278,
			"versionNonce": 1814374273,
			"isDeleted": false,
			"id": "hRNC1AD6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -163.660009630609,
			"y": 722.8179232326208,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 25,
			"seed": 2139142255,
			"groupIds": [
				"m1FgdjqmCfsigj1hTFDRX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "類別",
			"rawText": "類別",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "類別",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 154,
			"versionNonce": 834915599,
			"isDeleted": false,
			"id": "SwrjxLb2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -32.872306327555854,
			"y": 561.2498128383387,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 25,
			"seed": 1131490479,
			"groupIds": [
				"PEOTort3_hgk5LqA_bXgw"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "類別",
			"rawText": "類別",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "類別",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 115,
			"versionNonce": 385257313,
			"isDeleted": false,
			"id": "MQDWcxE5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 106.99506476641318,
			"y": 561.2498125756135,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 25,
			"seed": 1672309889,
			"groupIds": [
				"PEOTort3_hgk5LqA_bXgw"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "類別",
			"rawText": "類別",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "類別",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 128,
			"versionNonce": 1694847791,
			"isDeleted": false,
			"id": "qVIWtduj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 243.71608938583267,
			"y": 561.2498129616746,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 25,
			"seed": 373580111,
			"groupIds": [
				"PEOTort3_hgk5LqA_bXgw"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "均有",
			"rawText": "均有",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "均有",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 196,
			"versionNonce": 1460665153,
			"isDeleted": false,
			"id": "KlT87h6G",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 361.74805704009964,
			"y": 561.2498126104608,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 25,
			"seed": 670046689,
			"groupIds": [
				"PEOTort3_hgk5LqA_bXgw"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "模式類別",
			"rawText": "模式類別",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "模式類別",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 1584469327,
			"isDeleted": false,
			"id": "hQDmjZL7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -57.85606816937291,
			"y": 620.8499083504761,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.57989501953125,
			"height": 50,
			"seed": 240029921,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "迴歸分析\nRegression",
			"rawText": "迴歸分析\nRegression",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "迴歸分析\nRegression",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 1288760097,
			"isDeleted": false,
			"id": "ATxWEwAt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 89.54243483610765,
			"y": 620.8499081922927,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 50,
			"seed": 527682575,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "變異數分析\nANOVA",
			"rawText": "變異數分析\nANOVA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "變異數分析\nANOVA",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 151,
			"versionNonce": 1432327023,
			"isDeleted": false,
			"id": "LmfDJ6NR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 223.0068553509852,
			"y": 620.849908455018,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 50,
			"seed": 1124808911,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "共變異分析\nANCOVA",
			"rawText": "共變異分析\nANCOVA",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "共變異分析\nANCOVA",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 107,
			"versionNonce": 1621679873,
			"isDeleted": false,
			"id": "peVLYEd8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.6515132331299,
			"y": 620.8499083853233,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 119.89990234375,
			"height": 50,
			"seed": 398376641,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "線性模式\nLinear model",
			"rawText": "線性模式\nLinear model",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "線性模式\nLinear model",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 35212687,
			"isDeleted": false,
			"id": "ke58etyk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -62.566120836953075,
			"y": 710.6984842835217,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110,
			"height": 100,
			"seed": 592933729,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "邏輯/羅吉斯\n迴歸\nLogistic\nRegression",
			"rawText": "邏輯/羅吉斯\n迴歸\nLogistic\nRegression",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "邏輯/羅吉斯\n迴歸\nLogistic\nRegression",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 187,
			"versionNonce": 1092048609,
			"isDeleted": false,
			"id": "GcZjCxGz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 63.426609519741284,
			"y": 698.1984840904912,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120,
			"height": 125,
			"seed": 836743809,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "類別資料分析\n對數線性模式\nLoglinear \nmodel\n列聯表分析",
			"rawText": "類別資料分析\n對數線性模式\nLoglinear \nmodel\n列聯表分析",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "類別資料分析\n對數線性模式\nLoglinear \nmodel\n列聯表分析",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 114,
			"versionNonce": 2144781231,
			"isDeleted": false,
			"id": "MZ8sJu03",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 213.25078726249677,
			"y": 710.6984848974606,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120,
			"height": 50,
			"seed": 1325464303,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "邏輯迴歸\n對數線性模式",
			"rawText": "邏輯迴歸\n對數線性模式",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "邏輯迴歸\n對數線性模式",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 548131521,
			"isDeleted": false,
			"id": "adWf5r9a",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.65151326797735,
			"y": 710.6984842486743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120,
			"height": 100,
			"seed": 297034689,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "廣義線性模式\ngeneralized \nlinear model,\nGLM",
			"rawText": "廣義線性模式\ngeneralized \nlinear model,\nGLM",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "廣義線性模式\ngeneralized \nlinear model,\nGLM",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 167,
			"versionNonce": 1858106831,
			"isDeleted": false,
			"id": "MH4BY1IrgunPOYRkEbzKw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -200.13960661455576,
			"y": 685.9864990368499,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 702.5264322392275,
			"height": 0,
			"seed": 932370017,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					702.5264322392275,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 183,
			"versionNonce": 872796833,
			"isDeleted": false,
			"id": "-mv0kRF1V0DNe5KN1eD6D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -201.31636780758618,
			"y": 594.1991259804685,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 710.763760590441,
			"height": 0,
			"seed": 448657249,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					710.763760590441,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 124,
			"versionNonce": 1441719279,
			"isDeleted": false,
			"id": "UX9ABskx97o0ZKuML22YE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -80.10996492544155,
			"y": 531.8307827498503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.842170943040401e-14,
			"height": 280.06916394126654,
			"seed": 910245199,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.842170943040401e-14,
					280.06916394126654
				]
			]
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 1876219521,
			"isDeleted": false,
			"id": "sUR2sdbduSmRfWXkwwVJ9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 55.21757227306966,
			"y": 535.3610663289419,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.4210854715202004e-14,
			"height": 282.4226863273275,
			"seed": 189738593,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.4210854715202004e-14,
					282.4226863273275
				]
			]
		},
		{
			"type": "line",
			"version": 113,
			"versionNonce": 1164611087,
			"isDeleted": false,
			"id": "VZHeQ7LZ4j-zZQKHhJYhd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 205.84300498097764,
			"y": 542.4216334871251,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.684341886080802e-14,
			"height": 287.1297310994496,
			"seed": 1337466031,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-5.684341886080802e-14,
					287.1297310994496
				]
			]
		},
		{
			"type": "line",
			"version": 118,
			"versionNonce": 114843233,
			"isDeleted": false,
			"id": "QzCchUGSEL3KtFTsqx5nD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 342.34730337251926,
			"y": 541.2448722940945,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.684341886080802e-14,
			"height": 296.54382064369395,
			"seed": 351542881,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-5.684341886080802e-14,
					296.54382064369395
				]
			]
		},
		{
			"type": "line",
			"version": 145,
			"versionNonce": 942404655,
			"isDeleted": false,
			"id": "vXKYlrkyDI75UHIwmYpIK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -201.31636780758618,
			"y": 531.8307827498503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 122.38316407517527,
			"height": 62.368343230618166,
			"seed": 838679599,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					122.38316407517527,
					62.368343230618166
				]
			]
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 668985921,
			"isDeleted": false,
			"id": "tfffUely",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.26568121244122,
			"y": 568.3103797337967,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.31999206542969,
			"height": 25,
			"seed": 2068604047,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "反應變數 Y",
			"rawText": "反應變數 Y",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "反應變數 Y",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 280,
			"versionNonce": 907777615,
			"isDeleted": false,
			"id": "1QgJRoyn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -216.8976296693238,
			"y": 892.8507534079836,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 711.68798828125,
			"height": 136.24999999999997,
			"seed": 1110135777,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 27.249999999999993,
			"fontFamily": 1,
			"text": "CDA裡面會遇到的機率分配\n1.Binomial distribution\n2.Multinomial distribution\n3.Special cases：Poisson distribution for count data",
			"rawText": "CDA裡面會遇到的機率分配\n1.Binomial distribution\n2.Multinomial distribution\n3.Special cases：Poisson distribution for count data",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CDA裡面會遇到的機率分配\n1.Binomial distribution\n2.Multinomial distribution\n3.Special cases：Poisson distribution for count data",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 194,
			"versionNonce": 2076899873,
			"isDeleted": false,
			"id": "bfMsj8aM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220.71964166932386,
			"y": 1125.7426254079837,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 253.35094675526224,
			"height": 53.49999999999995,
			"seed": 93373,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "aed8e05b3b3622f40611c680fecd26fe2f9c6530",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 700,
			"versionNonce": 907146351,
			"isDeleted": false,
			"id": "yQBjcBsd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.49999979911354,
			"y": 1225.0349745742024,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 409.4410063766972,
			"height": 79.63468845519888,
			"seed": 25501,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "10a2325614e0e1bc90e410d4783870c5fe8e27dc",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "DHTxbuF5",
			"type": "text",
			"x": -234.26568134352766,
			"y": 1056.030046939235,
			"width": 318.403277861996,
			"height": 41.13741657231529,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 839432975,
			"version": 91,
			"versionNonce": 1669926401,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"text": "Binomial distribution",
			"rawText": "Binomial distribution",
			"fontSize": 32.90993325785223,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Binomial distribution",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 848,
			"versionNonce": 1071091343,
			"isDeleted": false,
			"id": "aohEXPMAoKBpH2nRPkDkW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220.71964144936004,
			"y": 1636.169513411203,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 737.4734439247203,
			"height": 41.840622425550855,
			"seed": 1582107233,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "fd44c5ae18190c3ba712f432d5510380aa44fc76",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 1241,
			"versionNonce": 1981392353,
			"isDeleted": false,
			"id": "pTdbOMPePJYD62tbRY23H",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220.71964157914982,
			"y": 1714.3476025774216,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 638.298914129532,
			"height": 76.70061271477783,
			"seed": 64951873,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "968fbd68ae9bad1dad3a92c42c00f9f3ef6c54c9",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 475,
			"versionNonce": 1311040687,
			"isDeleted": false,
			"id": "8zJtMBEy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.2656811235639,
			"y": 1566.4569349424544,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 365.5188293457031,
			"height": 41.13741657231529,
			"seed": 1728357921,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"fontSize": 32.90993325785223,
			"fontFamily": 1,
			"text": "Multinomial distribution",
			"rawText": "Multinomial distribution",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Multinomial distribution",
			"lineHeight": 1.25
		},
		{
			"id": "qXTMPASy",
			"type": "text",
			"x": -231.77545856479054,
			"y": 1330.6709027069105,
			"width": 488.779541015625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 645032001,
			"version": 75,
			"versionNonce": 1049379265,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"text": "The binomial distribution is always symmetric when",
			"rawText": "The binomial distribution is always symmetric when",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The binomial distribution is always symmetric when",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 131,
			"versionNonce": 1889695439,
			"isDeleted": false,
			"id": "5Tcl8Tcm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 268.2922504514028,
			"y": 1336.3742435388049,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 15,
			"seed": 2906,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "78c77d8756ff1efb61b38ae615699fc2fd5f19e2",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "Gm8Q3YgL1bv6xjm7jgmKw",
			"type": "line",
			"x": 113.54755387357315,
			"y": 1353.6592785420607,
			"width": 91.51441379639337,
			"height": 0,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 302573313,
			"version": 72,
			"versionNonce": 973103521,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					91.51441379639337,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "aUGTnXMj",
			"type": "text",
			"x": 186.16866933780787,
			"y": 1322.441055126033,
			"width": 27.601272969520863,
			"height": 17.25079560595054,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1876074991,
			"version": 89,
			"versionNonce": 770229487,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"text": "對稱",
			"rawText": "對稱",
			"fontSize": 13.800636484760432,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "對稱",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 113,
			"versionNonce": 363169153,
			"isDeleted": false,
			"id": "WgT1iNCn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.2656812885694,
			"y": 1381.6721429453382,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 206,
			"height": 18,
			"seed": 18800,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5bf7ac069d54d54681bc9ea3ee29e20cbfb62906",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 143,
			"versionNonce": 629165839,
			"isDeleted": false,
			"id": "c4RNKnK2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.26568068832182,
			"y": 1443.3283165588568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 274,
			"height": 18,
			"seed": 8957,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199642,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "630f908ec4f12b7b80559a2e57740fe4f7932adc",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "QRreH762",
			"type": "text",
			"x": 48.01142528389795,
			"y": 1431.2467840624513,
			"width": 64.78386347575442,
			"height": 12.42784442528748,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 553715169,
			"version": 222,
			"versionNonce": 750464353,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "*中央極限定理",
			"rawText": "*中央極限定理",
			"fontSize": 9.94227554022999,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "*中央極限定理",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 835,
			"versionNonce": 1910609199,
			"isDeleted": false,
			"id": "pypb_DY6q5iHXEmKjtp4d",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 62.326664716711036,
			"y": 1471.5967593456737,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 0,
			"height": 69.47339406885588,
			"seed": 71455599,
			"groupIds": [
				"wKz3aqVu03ri55CV0JTdh"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					69.47339406885588
				]
			]
		},
		{
			"type": "line",
			"version": 844,
			"versionNonce": 1183897921,
			"isDeleted": false,
			"id": "TaT28pEvZn0N1EfCuCDJz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 62.211639306344864,
			"y": 1541.3838854812052,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 143.90917342834433,
			"height": 0,
			"seed": 1185156495,
			"groupIds": [
				"wKz3aqVu03ri55CV0JTdh"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					143.90917342834433,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 861,
			"versionNonce": 1249187663,
			"isDeleted": false,
			"id": "Rc1TVcRy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 62.055620184373254,
			"y": 1461.7295507272524,
			"strokeColor": "#000000",
			"backgroundColor": "#be4bdb",
			"width": 30.270550272858635,
			"height": 7.939816465012101,
			"seed": 1695122351,
			"groupIds": [
				"wKz3aqVu03ri55CV0JTdh"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"fontSize": 4.962385290632564,
			"fontFamily": 1,
			"text": "Density plot",
			"rawText": "",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Density plot",
			"lineHeight": 1.6
		},
		{
			"type": "line",
			"version": 709,
			"versionNonce": 344328481,
			"isDeleted": false,
			"id": "xQro_VIrQS8MsLPs7jC_L",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 72.82625189472378,
			"y": 1540.1014038740834,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 102.63115032899151,
			"height": 57.74411974554256,
			"seed": 530265551,
			"groupIds": [
				"wKz3aqVu03ri55CV0JTdh"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.18794825838861,
					-1.127814838780174
				],
				[
					25.263052388674907,
					-16.014970710677865
				],
				[
					42.405837938132606,
					-46.014845422229236
				],
				[
					53.00729742266587,
					-56.616304906762444
				],
				[
					60.45087535861472,
					-45.11259355120511
				],
				[
					69.0222681333438,
					-25.93974129194299
				],
				[
					84.58611290850939,
					-9.022518710241055
				],
				[
					102.18002439347964,
					-2.2556296775602918
				],
				[
					102.63115032899151,
					1.1278148387801177
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 989,
			"versionNonce": 1704154479,
			"isDeleted": false,
			"id": "IhA8plhQiItfHYG06b6ND",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -12.756708539505413,
			"y": 1365.9333447277777,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 0,
			"height": 57.86924232496426,
			"seed": 784549423,
			"groupIds": [
				"zYeE41EjYFdP07jDj3W-x"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					57.86924232496426
				]
			]
		},
		{
			"type": "line",
			"version": 998,
			"versionNonce": 1879719169,
			"isDeleted": false,
			"id": "OYCk1QDF10NDWSoknFW-2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -12.852521237808467,
			"y": 1424.0639164038541,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 119.87200195885455,
			"height": 0,
			"seed": 1106815055,
			"groupIds": [
				"zYeE41EjYFdP07jDj3W-x"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					119.87200195885455,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 1015,
			"versionNonce": 444911503,
			"isDeleted": false,
			"id": "UO5r2jRb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -12.982480461734605,
			"y": 1357.7142574892237,
			"strokeColor": "#000000",
			"backgroundColor": "#be4bdb",
			"width": 24.644511541582002,
			"height": 6.613627694281631,
			"seed": 679265903,
			"groupIds": [
				"zYeE41EjYFdP07jDj3W-x"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"fontSize": 4.133517308926019,
			"fontFamily": 1,
			"text": "Density plot",
			"rawText": "Density plot",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Density plot",
			"lineHeight": 1.6
		},
		{
			"type": "line",
			"version": 1163,
			"versionNonce": 1486681313,
			"isDeleted": false,
			"id": "fbk2GB2Sr_Xwx8HNwiqzQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4.010869029860832,
			"y": 1422.9956478976935,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 85.48865343460619,
			"height": 37.75142470960802,
			"seed": 18358415,
			"groupIds": [
				"zYeE41EjYFdP07jDj3W-x"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.321404459331765,
					-0.939435752028679
				],
				[
					10.31866443527645,
					-19.275954986272154
				],
				[
					21.63204655784249,
					-36.81198895757939
				],
				[
					50.49203281298537,
					-16.23251798796082
				],
				[
					85.11287913379488,
					-1.8788715040573112
				],
				[
					85.48865343460619,
					0.939435752028632
				],
				[
					0,
					0
				]
			]
		},
		{
			"id": "tgKb73He",
			"type": "text",
			"x": -215.25441807164597,
			"y": 1813.975000283783,
			"width": 195.75987243652344,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1658426479,
			"version": 59,
			"versionNonce": 1132594607,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "Special case：C=2, ",
			"rawText": "Special case：C=2, ",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Special case：C=2, ",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 172,
			"versionNonce": 835563713,
			"isDeleted": false,
			"id": "jsRyvNLV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -24.69220459458444,
			"y": 1816.7574356766904,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 20,
			"seed": 79014,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "6c7ec610ce64cb7d4f84651066fa37d47ac0b23c",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "IFxIYdX3",
			"type": "text",
			"x": 37.35085278819082,
			"y": 1802.3582158830027,
			"width": 61.37774658203125,
			"height": 18.964849810575558,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 786529519,
			"version": 152,
			"versionNonce": 1605597135,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "*binomial",
			"rawText": "*binomial",
			"fontSize": 15.171879848460447,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "*binomial",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 158,
			"versionNonce": 1094447265,
			"isDeleted": false,
			"id": "QrgURxKK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -215.254417687182,
			"y": 1862.4666572415656,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 250,
			"height": 20,
			"seed": 44099,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "323135651fe2d1fcdb4199dac9fbd49723c7fb2d",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "eN1Swld7ocyWcMDkWsYLP",
			"type": "line",
			"x": -238.7699153190465,
			"y": 855.4603639980202,
			"width": 968.6939254450697,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1618594991,
			"version": 180,
			"versionNonce": 1966188015,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					968.6939254450697,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "nnf3dJVO",
			"type": "text",
			"x": 713.3894745133015,
			"y": -691.0180505125996,
			"width": 854.6449979222176,
			"height": 40.7067132611946,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 162570433,
			"version": 183,
			"versionNonce": 1821848705,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "母體比例的推論(Statistical inference for a proportion)",
			"rawText": "母體比例的推論(Statistical inference for a proportion)",
			"fontSize": 32.56537060895569,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "母體比例的推論(Statistical inference for a proportion)",
			"lineHeight": 1.25
		},
		{
			"id": "17s1LyPT",
			"type": "text",
			"x": -231.02684836152582,
			"y": 1914.2545529194817,
			"width": 312.8553921983898,
			"height": 40.40810878133742,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 235362063,
			"version": 48,
			"versionNonce": 855969807,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "Possion Distribution",
			"rawText": "Possion Distribution",
			"fontSize": 32.32648702506992,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Possion Distribution",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 190,
			"versionNonce": 933166177,
			"isDeleted": false,
			"id": "6qjA89Bk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -231.02684821284788,
			"y": 1958.5087455657215,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 250.06915126915374,
			"height": 88.80710319912131,
			"seed": 51138,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "2bf3bd653fce80c8b2261e2cc6ec8ae0796295c4",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "j49_gyz3r6m-VwkdUhnhI",
			"type": "line",
			"x": 1146.2999814479074,
			"y": -657.6499090389217,
			"width": 141.3261356735818,
			"height": 0,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1204975439,
			"version": 53,
			"versionNonce": 1395013167,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					141.3261356735818,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "w9FEseLK",
			"type": "text",
			"x": 1247.8352633881505,
			"y": -749.5805021469795,
			"width": 154.0773316447362,
			"height": 63.72098404597874,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 805731663,
			"version": 150,
			"versionNonce": 35833921,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "1.點/區間估計\n2.檢定",
			"rawText": "1.點/區間估計\n2.檢定",
			"fontSize": 25.488393618391495,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1.點/區間估計\n2.檢定",
			"lineHeight": 1.25
		},
		{
			"id": "CJmVRioB",
			"type": "text",
			"x": 713.3894746409566,
			"y": -589.8796707101811,
			"width": 653.807373046875,
			"height": 116.16295213793629,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 2035609807,
			"version": 222,
			"versionNonce": 1014863951,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "- Likelihood function：\nThe probability of the observed data,\nexpressed as a function of the parameter",
			"rawText": "- Likelihood function：\nThe probability of the observed data,\nexpressed as a function of the parameter",
			"fontSize": 30.976787236783007,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "- Likelihood function：\nThe probability of the observed data,\nexpressed as a function of the parameter",
			"lineHeight": 1.25
		},
		{
			"id": "LefCxQFYZ4nLktXlcPajk",
			"type": "line",
			"x": 715.4610824041736,
			"y": -513.5795765561444,
			"width": 576.2813299311092,
			"height": 0,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 879646593,
			"version": 165,
			"versionNonce": 100800545,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					576.2813299311092,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "qErJx96TXiJ4vOoKGzXEu",
			"type": "line",
			"x": 714.0889839995757,
			"y": -473.7887228228059,
			"width": 201.69846547588816,
			"height": 0,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 559134511,
			"version": 64,
			"versionNonce": 1692644975,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					201.69846547588816,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "ccBD3cmpyHE_7IfXZqK_b",
			"type": "line",
			"x": 961.0666968271939,
			"y": -477.9050180365995,
			"width": 128.97725003220057,
			"height": 0,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1022080961,
			"version": 34,
			"versionNonce": 355232769,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					128.97725003220057,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "_jaMhkTnUV1-FpG7Ze3xF",
			"type": "line",
			"x": 1212.1607048686058,
			"y": -476.5329196320016,
			"width": 153.67502131496235,
			"height": 0,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 986446991,
			"version": 59,
			"versionNonce": 1931546767,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					153.67502131496235,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "6MLbzbBf",
			"type": "text",
			"x": 726.4378696409565,
			"y": -462.81193558602286,
			"width": 77.83727925977246,
			"height": 32.43219969157185,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 310494095,
			"version": 50,
			"versionNonce": 396444641,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "表達成",
			"rawText": "表達成",
			"fontSize": 25.945759753257494,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "表達成",
			"lineHeight": 1.25
		},
		{
			"id": "yYuUJh2W",
			"type": "text",
			"x": 722.3215744271629,
			"y": -412.0442946159027,
			"width": 761.1798095703125,
			"height": 50,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1180725359,
			"version": 136,
			"versionNonce": 552478383,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "我會這樣理解likelihood function，他就是在給定x跟模型的情況下，你的參數是未知。\n以binomial為例：",
			"rawText": "我會這樣理解likelihood function，他就是在給定x跟模型的情況下，你的參數是未知。\n以binomial為例：",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "我會這樣理解likelihood function，他就是在給定x跟模型的情況下，你的參數是未知。\n以binomial為例：",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 363,
			"versionNonce": 1232084929,
			"isDeleted": false,
			"id": "HDn1yM6Y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 726.4378704547967,
			"y": -339.8750004549769,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 188.44120676594355,
			"height": 36.49979437500775,
			"seed": 83335,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "b091f17a1dce1778b463725a9021f95dc888c279",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 394,
			"versionNonce": 1559460047,
			"isDeleted": false,
			"id": "VJpanOck",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 722.3215740255029,
			"y": -275.8495880265367,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 352.66520850581577,
			"height": 28.743942301699672,
			"seed": 96154,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "472a060c0a8be60de6a87a31f2a4f69b4b841d0c",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "C5vzEady",
			"type": "text",
			"x": 721.6781025237658,
			"y": -215.18696780175105,
			"width": 518.9186163230914,
			"height": 39.80661731896772,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 276090049,
			"version": 69,
			"versionNonce": 951615393,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "MLE(Maximum likelihood estimate)",
			"rawText": "MLE(Maximum likelihood estimate)",
			"fontSize": 31.845293855174184,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "MLE(Maximum likelihood estimate)",
			"lineHeight": 1.25
		},
		{
			"id": "SqA6qPsV",
			"type": "text",
			"x": 729.9040010343034,
			"y": -157.6056782279877,
			"width": 505.27960205078125,
			"height": 75,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 993950991,
			"version": 111,
			"versionNonce": 751404783,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "The parameter values for which the probability of \nthe observed data takes its greastest value\n",
			"rawText": "The parameter values for which the probability of \nthe observed data takes its greastest value\n",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The parameter values for which the probability of \nthe observed data takes its greastest value\n",
			"lineHeight": 1.25
		},
		{
			"type": "image",
			"version": 448,
			"versionNonce": 61465473,
			"isDeleted": false,
			"id": "bpbZ_XR37L1V4zZYUih3V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 730.5541663413968,
			"y": -88.10277661379831,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 188.44120676594355,
			"height": 36.49979437500775,
			"seed": 984419617,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "145e996240338e4f3344611ce8ebf48f1ec45b7a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 479,
			"versionNonce": 1324929295,
			"isDeleted": false,
			"id": "n74xHZXEYSSMHfXxcrSiK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 726.4378699121029,
			"y": -24.077364185358135,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 352.66520850581577,
			"height": 28.743942301699672,
			"seed": 1118880001,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "499754e2157ad7375edc8e17348054afd9c94fe7",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 198,
			"versionNonce": 1451477857,
			"isDeleted": false,
			"id": "0rr3eOko",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 729.9040010458073,
			"y": 155.9695643307491,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 63.555176484272664,
			"height": 36.317243705298665,
			"seed": 17326,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "a23a1969debbd7a31e7d2380d95c073755e8f498",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 42,
			"versionNonce": 486135599,
			"isDeleted": false,
			"id": "DvnHQ9Ud",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 739.4436557825607,
			"y": 93.0065251867063,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44.47586555794792,
			"height": 20.014139501076563,
			"seed": 82783,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e06e08ec4855d7079c00b1e9818b19dbd7e8af53",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "4ldj9qqAc0BA9zEAoSvjw",
			"type": "line",
			"x": 733.5628768562361,
			"y": 127.20530736220405,
			"width": 564.3046781415768,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 143487439,
			"version": 294,
			"versionNonce": 697677633,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					564.3046781415768,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "lDVjI1iZtA-8CptP0Puhw",
			"type": "line",
			"x": 801.5513922949802,
			"y": 85.0524277901826,
			"width": 1.1368683772161603e-13,
			"height": 123.73909809851455,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 239948097,
			"version": 47,
			"versionNonce": 758454607,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.1368683772161603e-13,
					123.73909809851455
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "nruPY8pvgDKyrtMS7aBiB",
			"type": "line",
			"x": 870.8996780424993,
			"y": 83.69265748140776,
			"width": 1.1368683772161603e-13,
			"height": 127.81840902483907,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 2062594735,
			"version": 51,
			"versionNonce": 1061103393,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.1368683772161603e-13,
					127.81840902483907
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"type": "line",
			"version": 95,
			"versionNonce": 889395055,
			"isDeleted": false,
			"id": "n7fwzyUc6XxCcEpDgarmZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 940.4045870499168,
			"y": 87.96446707966352,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.1368683772161603e-13,
			"height": 123.73909809851455,
			"seed": 1547927233,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1368683772161603e-13,
					123.73909809851455
				]
			]
		},
		{
			"type": "line",
			"version": 84,
			"versionNonce": 1643092737,
			"isDeleted": false,
			"id": "j8tIk5u9usdMjVNLLxBSg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1014.8911704605139,
			"y": 80.42020306559,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.1368683772161603e-13,
			"height": 123.73909809851455,
			"seed": 1692378639,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1368683772161603e-13,
					123.73909809851455
				]
			]
		},
		{
			"type": "line",
			"version": 96,
			"versionNonce": 715936143,
			"isDeleted": false,
			"id": "FO-k4D09fCWQTaaVoEFRw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1086.6710689133313,
			"y": 86.20767322701401,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.1368683772161603e-13,
			"height": 123.73909809851455,
			"seed": 1394844929,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1368683772161603e-13,
					123.73909809851455
				]
			]
		},
		{
			"id": "sr15XbOq",
			"type": "text",
			"x": 888.5766920565727,
			"y": 90.4915090252822,
			"width": 33.47998046875,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 598159215,
			"version": 67,
			"versionNonce": 1646695137,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.2",
			"rawText": "0.2",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.2",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 661211055,
			"isDeleted": false,
			"id": "pGpRnxUo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 960.644518892565,
			"y": 90.49150918670631,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.03997802734375,
			"height": 25,
			"seed": 24053153,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0.4",
			"rawText": "0.4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.4",
			"lineHeight": 1.25
		},
		{
			"id": "23OEM92b",
			"type": "text",
			"x": 1107.6302224183337,
			"y": 91.85127895160672,
			"width": 32.03997802734375,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1679250031,
			"version": 152,
			"versionNonce": 1416859329,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.6",
			"rawText": "0.6",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.6",
			"lineHeight": 1.25
		},
		{
			"id": "Kn3KXSIx",
			"type": "text",
			"x": 1178.7451836219784,
			"y": 91.85127887793148,
			"width": 34.53997802734375,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 533230383,
			"version": 176,
			"versionNonce": 157448655,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.8",
			"rawText": "0.8",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.8",
			"lineHeight": 1.25
		},
		{
			"id": "YSMoesFF",
			"type": "text",
			"x": 1263.360144208073,
			"y": 88.02066456915651,
			"width": 5.712677001953125,
			"height": 26.35977030877494,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 634328111,
			"version": 209,
			"versionNonce": 259395233,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "1",
			"rawText": "1",
			"fontSize": 21.08781624701995,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25
		},
		{
			"id": "V0HACJRM",
			"type": "text",
			"x": 747.1605799439849,
			"y": 23.86276389531281,
			"width": 152.17990112304688,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 872423937,
			"version": 32,
			"versionNonce": 1437624303,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "Given that Y=4",
			"rawText": "Given that Y=4",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Given that Y=4",
			"lineHeight": 1.25
		},
		{
			"id": "nU3WO4Cx",
			"type": "text",
			"x": 824.7747696178285,
			"y": 87.44622918670632,
			"width": 13.759994506835938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 822137441,
			"version": 21,
			"versionNonce": 1776128641,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0",
			"rawText": "0",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25
		},
		{
			"type": "line",
			"version": 213,
			"versionNonce": 1515950607,
			"isDeleted": false,
			"id": "Sw4fMRql6Tw245smewA3r",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1231.5423994333562,
			"y": 92.91557568591206,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.1368683772161603e-13,
			"height": 123.73909809851455,
			"seed": 6798913,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1368683772161603e-13,
					123.73909809851455
				]
			]
		},
		{
			"type": "line",
			"version": 62,
			"versionNonce": 946444897,
			"isDeleted": false,
			"id": "WYOKT2Tw1tC-hIFbnPZiP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.9332117843512,
			"y": 93.91557568591209,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.1368683772161603e-13,
			"height": 123.73909809851455,
			"seed": 1728234287,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1368683772161603e-13,
					123.73909809851455
				]
			]
		},
		{
			"id": "M0ioxR84",
			"type": "text",
			"x": 1028.8998977585634,
			"y": 91.85127887793148,
			"width": 31.5999755859375,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 164412815,
			"version": 56,
			"versionNonce": 274495535,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.5",
			"rawText": "0.5",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.5",
			"lineHeight": 1.25
		},
		{
			"id": "LzXnQOH5",
			"type": "text",
			"x": 806.9904735300797,
			"y": 159.8397947728015,
			"width": 60.51997375488281,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 467453057,
			"version": 27,
			"versionNonce": 199861825,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.000",
			"rawText": "0.000",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.000",
			"lineHeight": 1.25
		},
		{
			"id": "QlCegSDv",
			"type": "text",
			"x": 874.5779635863737,
			"y": 159.62818608157633,
			"width": 63.59996032714844,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1049058479,
			"version": 69,
			"versionNonce": 1033607759,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.088",
			"rawText": "0.088",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.088",
			"lineHeight": 1.25
		},
		{
			"id": "Ris50Z0O",
			"type": "text",
			"x": 949.7663559514425,
			"y": 165.27887600790086,
			"width": 51.25996398925781,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 218600591,
			"version": 9,
			"versionNonce": 792540705,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.251",
			"rawText": "0.251",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.251",
			"lineHeight": 1.25
		},
		{
			"id": "nl9bl74l",
			"type": "text",
			"x": 1021.2732635516109,
			"y": 161.6386463166757,
			"width": 59.59996032714844,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1215841153,
			"version": 22,
			"versionNonce": 1458665583,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.205",
			"rawText": "0.205",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.205",
			"lineHeight": 1.25
		},
		{
			"id": "y0s8tXzf",
			"type": "text",
			"x": 1105.9002189166795,
			"y": 161.63864555177506,
			"width": 35.49998474121094,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 2143355233,
			"version": 42,
			"versionNonce": 1730994657,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.111",
			"rawText": "0.111",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.111",
			"lineHeight": 1.25
		},
		{
			"id": "rA8KYrya",
			"type": "text",
			"x": 1171.4696118992986,
			"y": 165.27887631667548,
			"width": 59.559967041015625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1630803631,
			"version": 18,
			"versionNonce": 401828015,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.006",
			"rawText": "0.006",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.006",
			"lineHeight": 1.25
		},
		{
			"id": "f5EZnU3F",
			"type": "text",
			"x": 1244.759371190692,
			"y": 165.27887631667548,
			"width": 60.51997375488281,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 526453583,
			"version": 23,
			"versionNonce": 567803329,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"text": "0.000",
			"rawText": "0.000",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0.000",
			"lineHeight": 1.25
		},
		{
			"id": "SNszKe21",
			"type": "text",
			"x": 1284.4827039046913,
			"y": -238.63247474111085,
			"width": 225.01979064941406,
			"height": 200,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 333617135,
			"version": 104,
			"versionNonce": 776013039,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1713726320079,
			"link": null,
			"locked": false,
			"text": "MLE in Large Sample：\n1.Consistency\n\n2.Asymptotic Mormality\n\n3.Asymptotic Efficiency\n\n4.Invariance",
			"rawText": "MLE in Large Sample：\n1.Consistency\n\n2.Asymptotic Mormality\n\n3.Asymptotic Efficiency\n\n4.Invariance",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "MLE in Large Sample：\n1.Consistency\n\n2.Asymptotic Mormality\n\n3.Asymptotic Efficiency\n\n4.Invariance",
			"lineHeight": 1.25
		},
		{
			"id": "MipXwpWXlbyf2Jg3QYY7a",
			"type": "freedraw",
			"x": 1191.8054709133717,
			"y": 125.8455370534291,
			"width": 61.18966389486991,
			"height": 4.079310926324638,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1870122689,
			"version": 36,
			"versionNonce": 1699990017,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.3597703087750688,
					0
				],
				[
					2.71954061754991,
					0
				],
				[
					4.079310926324752,
					0
				],
				[
					5.439081235099593,
					0
				],
				[
					6.798851543874434,
					0
				],
				[
					8.158621852649503,
					0
				],
				[
					9.518392161424345,
					0
				],
				[
					10.878162470199186,
					0
				],
				[
					12.237932778974027,
					0
				],
				[
					13.597703087748869,
					0
				],
				[
					14.95747339652371,
					0
				],
				[
					16.31724370529878,
					0
				],
				[
					17.67701401407362,
					0
				],
				[
					19.03678432284846,
					0
				],
				[
					20.396554631623303,
					0
				],
				[
					21.756324940398144,
					0
				],
				[
					23.116095249173213,
					0
				],
				[
					25.835635866722896,
					0
				],
				[
					27.195406175497737,
					0
				],
				[
					28.55517648427258,
					0
				],
				[
					31.27471710182249,
					1.359770308774955
				],
				[
					32.63448741059733,
					1.359770308774955
				],
				[
					35.35402802814701,
					1.359770308774955
				],
				[
					36.713798336921855,
					2.7195406175497965
				],
				[
					42.15287957202145,
					4.079310926324638
				],
				[
					53.03104204222063,
					4.079310926324638
				],
				[
					55.750582659770316,
					4.079310926324638
				],
				[
					57.11035296854516,
					4.079310926324638
				],
				[
					58.47012327732,
					4.079310926324638
				],
				[
					59.82989358609507,
					4.079310926324638
				],
				[
					61.18966389486991,
					4.079310926324638
				],
				[
					61.18966389486991,
					4.079310926324638
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				61.18966389486991,
				4.079310926324638
			]
		},
		{
			"id": "O7CGQLGzSsSOMb32wQvWi",
			"type": "freedraw",
			"x": 1187.7261599870471,
			"y": 124.48576674465426,
			"width": 95.18392161424185,
			"height": 290.99084607782515,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1732140559,
			"version": 110,
			"versionNonce": 572953231,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1713726199643,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.3597703087748414,
					0
				],
				[
					2.719540617549683,
					0
				],
				[
					2.719540617549683,
					1.3597703087748414
				],
				[
					4.079310926324524,
					1.3597703087748414
				],
				[
					4.079310926324524,
					2.7195406175497965
				],
				[
					5.439081235099593,
					2.7195406175497965
				],
				[
					5.439081235099593,
					4.079310926324638
				],
				[
					6.798851543874434,
					8.158621852649276
				],
				[
					6.798851543874434,
					9.51839216142423
				],
				[
					6.798851543874434,
					10.878162470199072
				],
				[
					8.158621852649276,
					10.878162470199072
				],
				[
					8.158621852649276,
					12.237932778973914
				],
				[
					8.158621852649276,
					13.597703087748869
				],
				[
					8.158621852649276,
					14.95747339652371
				],
				[
					8.158621852649276,
					19.03678432284846
				],
				[
					8.158621852649276,
					23.116095249172986
				],
				[
					8.158621852649276,
					27.195406175497737
				],
				[
					6.798851543874434,
					29.91494679304742
				],
				[
					5.439081235099593,
					33.99425771937217
				],
				[
					5.439081235099593,
					36.713798336921855
				],
				[
					5.439081235099593,
					39.43333895447154
				],
				[
					5.439081235099593,
					43.51264988079629
				],
				[
					4.079310926324524,
					46.23219049834597
				],
				[
					2.719540617549683,
					50.31150142467072
				],
				[
					2.719540617549683,
					54.39081235099525
				],
				[
					1.3597703087748414,
					57.11035296854516
				],
				[
					1.3597703087748414,
					61.18966389486968
				],
				[
					0,
					65.26897482119443
				],
				[
					0,
					66.62874512996927
				],
				[
					-1.3597703087748414,
					69.34828574751896
				],
				[
					-1.3597703087748414,
					73.42759667384371
				],
				[
					-2.71954061754991,
					73.42759667384371
				],
				[
					-2.71954061754991,
					76.14713729139339
				],
				[
					-4.079310926324752,
					77.50690760016846
				],
				[
					-4.079310926324752,
					78.8666779089433
				],
				[
					-4.079310926324752,
					81.58621852649298
				],
				[
					-5.439081235099593,
					81.58621852649298
				],
				[
					-5.439081235099593,
					82.94598883526783
				],
				[
					-6.798851543874434,
					82.94598883526783
				],
				[
					-6.798851543874434,
					84.3057591440429
				],
				[
					-6.798851543874434,
					85.66552945281774
				],
				[
					-8.158621852649276,
					85.66552945281774
				],
				[
					-9.518392161424117,
					85.66552945281774
				],
				[
					-10.878162470199186,
					87.02529976159258
				],
				[
					-13.597703087748869,
					87.02529976159258
				],
				[
					-14.95747339652371,
					87.02529976159258
				],
				[
					-16.31724370529855,
					87.02529976159258
				],
				[
					-17.67701401407362,
					87.02529976159258
				],
				[
					-20.396554631623303,
					87.02529976159258
				],
				[
					-23.116095249172986,
					87.02529976159258
				],
				[
					-27.195406175497737,
					87.02529976159258
				],
				[
					-29.91494679304742,
					84.3057591440429
				],
				[
					-35.35402802814701,
					82.94598883526783
				],
				[
					-40.793109263246606,
					78.8666779089433
				],
				[
					-46.2321904983462,
					74.78736698261855
				],
				[
					-53.031042042220406,
					69.34828574751896
				],
				[
					-58.47012327732,
					65.26897482119443
				],
				[
					-61.18966389486991,
					62.54943420364475
				],
				[
					-65.26897482119443,
					58.47012327732
				],
				[
					-65.26897482119443,
					57.11035296854516
				],
				[
					-69.34828574751918,
					54.39081235099525
				],
				[
					-69.34828574751918,
					53.031042042220406
				],
				[
					-70.70805605629403,
					50.31150142467072
				],
				[
					-73.42759667384371,
					46.23219049834597
				],
				[
					-74.78736698261855,
					42.15287957202145
				],
				[
					-74.78736698261855,
					36.713798336921855
				],
				[
					-76.14713729139362,
					31.27471710182226
				],
				[
					-78.8666779089433,
					27.195406175497737
				],
				[
					-80.22644821771814,
					21.756324940398144
				],
				[
					-81.58621852649298,
					14.95747339652371
				],
				[
					-82.94598883526805,
					4.079310926324638
				],
				[
					-84.3057591440429,
					-5.439081235099593
				],
				[
					-84.3057591440429,
					-13.597703087748869
				],
				[
					-85.66552945281774,
					-21.756324940398144
				],
				[
					-85.66552945281774,
					-28.55517648427258
				],
				[
					-85.66552945281774,
					-32.63448741059722
				],
				[
					-85.66552945281774,
					-36.713798336921855
				],
				[
					-85.66552945281774,
					-39.43333895447165
				],
				[
					-85.66552945281774,
					-40.79310926324649
				],
				[
					-87.02529976159258,
					-43.51264988079629
				],
				[
					-87.02529976159258,
					-47.59196080712093
				],
				[
					-87.02529976159258,
					-53.03104204222052
				],
				[
					-87.02529976159258,
					-58.47012327732
				],
				[
					-87.02529976159258,
					-63.90920451241959
				],
				[
					-87.02529976159258,
					-70.70805605629391
				],
				[
					-87.02529976159258,
					-76.1471372913935
				],
				[
					-87.02529976159258,
					-80.22644821771814
				],
				[
					-87.02529976159258,
					-85.66552945281774
				],
				[
					-85.66552945281774,
					-91.10461068791722
				],
				[
					-85.66552945281774,
					-95.18392161424185
				],
				[
					-85.66552945281774,
					-100.62300284934145
				],
				[
					-85.66552945281774,
					-107.42185439321577
				],
				[
					-85.66552945281774,
					-111.50116531954052
				],
				[
					-85.66552945281774,
					-116.94024655464
				],
				[
					-85.66552945281774,
					-125.09886840728927
				],
				[
					-85.66552945281774,
					-130.53794964238887
				],
				[
					-85.66552945281774,
					-137.3368011862633
				],
				[
					-84.3057591440429,
					-146.85519334768742
				],
				[
					-84.3057591440429,
					-157.7333558178865
				],
				[
					-84.3057591440429,
					-168.61151828808556
				],
				[
					-84.3057591440429,
					-178.1299104495098
				],
				[
					-84.3057591440429,
					-189.00807291970887
				],
				[
					-84.3057591440429,
					-195.8069244635833
				],
				[
					-84.3057591440429,
					-201.24600569868278
				],
				[
					-84.3057591440429,
					-203.96554631623258
				],
				[
					-84.3057591440429,
					-203.96554631623258
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-84.3057591440429,
				-203.96554631623258
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": -853.6129216382119,
		"scrollY": 744.7491750770639,
		"zoom": {
			"value": 0.8854183228937931
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%