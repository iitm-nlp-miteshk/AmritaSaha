---
layout: page
title: Dataset Details
permalink: /dataset/
---
### Question Nomenclature

<!-- <dt>ques_type_id=1
Simple Question (subject-based)
<dt>ques_type_id=2
Secondary question 
sec_ques_type=1: Subject based question 
sec_ques_type=2: Object based question 
 sec_ques_sub_type=1: Direct (Singular) 
 sec_ques_sub_type=2: Indirect (Singular) 
 sec_ques_sub_type=3: Indirect (Plural) 
 sec_ques_sub_type=4: Direct (Plural) 
<dt>ques_type_id=3
Clarification (for secondary) question 
<dt>ques_type_id=4
Set-based question 
set_op_choice=1: OR 
set_op_choice=2: AND 
set_op_choice=3: Difference 
<dt>ques_type_id=5
Boolean (Factual Verification) question 
bool_ques_type = 1
Verification|2 entities, both direct 
bool_ques_type = 2
Verification|2 entities, one direct and one indirect, subject is indirect 
bool_ques_type = 3
Verification|2 entities, one direct and one indirect, object is indirect 
bool_ques_type = 4
Verification|3 entities, all direct, 2 are query entities 
bool_ques_type = 5
Verification|3 entities, 2 direct, 2(direct) are query entities, subject is indirect 
bool_ques_type = 6
Verification|one entity, multiple entities (as object) referred indirectly 
<dt>ques_type_id=6
Incomplete question (for secondary) 
inc_ques_type=1
Incomplete|object parent is changed, subject and predicate remain same 
inc_ques_type=2
Only subject is changed, parent and predicate remains same 
inc_ques_type=3
Incomplete count-based ques 
<dt>ques_type_id=7
Comparative and Quantitative questions (involving single entity) 
 count_ques_sub_type=1
Quantitative (count) single entity 
 count_ques_sub_type=2
Quantitative (min/max) single entity 
 count_ques_sub_type=3
Quantitative (atleast/atmost) single entity (which) 
 count_ques_sub_type=4
Comparative (more/less) single entity (count) 
 count_ques_sub_type=5
Quantitative (atleast/atmost) single entity (count) 
 count_ques_sub_type=6
Comparative (more/less) single entity (which) 
 count_ques_sub_type=7
Quantitative Indirect (count) single entity 
 count_ques_sub_type=8
Comparative Indirect (more/less) single entity (count) 
 count_ques_sub_type=9
Comparative Indirect (more/less) single entity (which) 
  is_incomplete=1: Incomplete form (of the category of question) 
<dt>ques_type_id=8
Comparative and Quantitative questions (involving multiple(2) entities) 
 count_ques_sub_type=1
Quantitative with Logical Operators 
 count_ques_sub_type=2
Quantitative (count) multiple entity 
 count_ques_sub_type=3
Quantitative (min/max) multiple entity 
 count_ques_sub_type=4
Quantitative (atleast/atmost) multiple entity (which) 
 count_ques_sub_type=5
Comparative (more/less) multiple entity (count) 
 count_ques_sub_type=6
Quantitative (atleast/atmost) multiple entity (count) 
 count_ques_sub_type=7
Comparative (more/less) multiple entity (which) 
 count_ques_sub_type=8
 Quantitative Indirect (count) multiple entity 
 count_ques_sub_type=9
Comparative Indirect (more/less) single entity (count) 
 count_ques_sub_type=10
Comparative Indirect (more/less) multiple entity (which) 
  is_incomplete=1: Incomplete form (of the category of question)  -->

<!-- <dl>
<dt style="color: #A43720">ques_type_id=1</dt> 
<dd>Simple Question (subject-based)</dd>

<dt style="color: #A43720">ques_type_id=2</dt>
<dd>Secondary question
<dl>
<dt>sec_ques_type=1</dt>
<dd>Subject based question

<dl>
<dt style="color: #B26216">sec_ques_sub_type=1</dt>
<dd>Direct (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=2</dt>
<dd>Indirect (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=3</dt>
<dd>Indirect (Plural) </dd>
<dt style="color: #B26216">sec_ques_sub_type=4</dt>
<dd>Direct (Plural) </dd>
</dl>
</dd>

<dt>sec_ques_type=2</dt>
<dd>Object based question

<dl>
<dt style="color: #B26216">sec_ques_sub_type=1</dt>
<dd>Direct (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=2</dt>
<dd>Indirect (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=3</dt>
<dd>Indirect (Plural) </dd>
<dt style="color: #B26216">sec_ques_sub_type=4</dt>
<dd>Direct (Plural) </dd>
</dl>
</dd>

</dl>
</dd>

<dt style="color: #A43720">ques_type_id=3</dt>
<dd>Clarification (for secondary) question </dd>
<dt style="color: #A43720">ques_type_id=4</dt>
<dd>Set-based question
<dl>
<dt>set_op_choice=1</dt>
	<dd>OR</dd> 
<dt>set_op_choice=2</dt>
	<dd>AND</dd>
<dt>set_op_choice=3</dt>
	<dd>Difference</dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=5</dt>
<dd>Boolean (Factual Verification) question
<dl>
<dt>bool_ques_type = 1</dt>
<dd>Verification|2 entities, both direct </dd>
<dt>bool_ques_type = 2</dt>
<dd>Verification|2 entities, one direct and one indirect, subject is indirect </dd>
<dt>bool_ques_type = 3</dt>
<dd>Verification|2 entities, one direct and one indirect, object is indirect </dd>
<dt>bool_ques_type = 4</dt>
<dd>Verification|3 entities, all direct, 2 are query entities </dd>
<dt>bool_ques_type = 5</dt>
<dd>Verification|3 entities, 2 direct, 2(direct) are query entities, subject is indirect </dd>
<dt>bool_ques_type = 6</dt>
<dd>Verification|one entity, multiple entities (as object) referred indirectly </dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=6</dt>
<dd>Incomplete question (for secondary)

<dl>
<dt>inc_ques_type=1</dt>
<dd>Incomplete|object parent is changed, subject and predicate remain same </dd>
<dt>inc_ques_type=2</dt>
<dd>Only subject is changed, parent and predicate remains same </dd>
<dt>inc_ques_type=3</dt>
<dd>Incomplete count-based ques </dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=7</dt>
<dd>Comparative and Quantitative questions (involving single entity)
<dl>
<dt>count_ques_sub_type=1</dt>
<dd>Quantitative (count) single entity
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=2</dt>
<dd>Quantitative (min/max) single entity </dd>
<dt>count_ques_sub_type=3</dt>
<dd>Quantitative (atleast/atmost) single entity (which) </dd>
<dt>count_ques_sub_type=4</dt>
<dd>Comparative (more/less) single entity (count)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=5</dt>
<dd>Quantitative (atleast/atmost) single entity (count) </dd>
<dt>count_ques_sub_type=6</dt>
<dd>Comparative (more/less) single entity (which)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=7</dt>
<dd>Quantitative Indirect (count) single entity </dd>
<dt>count_ques_sub_type=8</dt>
<dd>Comparative Indirect (more/less) single entity (count) </dd>
<dt>count_ques_sub_type=9</dt>
<dd>Comparative Indirect (more/less) single entity (which) </dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=8</dt>
<dd>Comparative and Quantitative questions (involving multiple(2) entities) </dd>
<dt>count_ques_sub_type=1</dt>
<dd>Quantitative with Logical Operators </dd>
<dt>count_ques_sub_type=2</dt>
<dd>Quantitative (count) multiple entity
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=3</dt>
<dd>Quantitative (min/max) multiple entity </dd>
<dt>count_ques_sub_type=4</dt>
<dd>Quantitative (atleast/atmost) multiple entity (which) </dd>
<dt>count_ques_sub_type=5</dt>
<dd>Comparative (more/less) multiple entity (count)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=6</dt>
<dd>Quantitative (atleast/atmost) multiple entity (count) </dd>
<dt>count_ques_sub_type=7</dt>
<dd>Comparative (more/less) multiple entity (which)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=8</dt>
<dd>Quantitative Indirect (count) multiple entity </dd>
<dt>count_ques_sub_type=9</dt>
<dd>Comparative Indirect (more/less) single entity (count) </dd>
<dt>count_ques_sub_type=10</dt>
<dd>Comparative Indirect (more/less) multiple entity (which) </dd>

</dl> -->

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg .tg-yw4l{vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-031e">Question type</th>
    <th class="tg-031e">Question sub-type</th>
    <th class="tg-031e">Question sub-sub-type</th>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=1<br>Simple Question (subject-based)</td>
    <td class="tg-031e"></td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">ques_type_id=2<br>Secondary question</td>
    <td class="tg-031e">sec_ques_type=1<br>Subject based question</td>
    <td class="tg-031e" rowspan="2">sec_ques_sub_type=1<br>Direct (Singular)<br><br>sec_ques_sub_type=2<br>Indirect (Singular)<br><br>sec_ques_sub_type=3<br>Indirect (Plural)<br><br>sec_ques_sub_type=4<br>Direct (Plural)</td>
  </tr>
  <tr>
    <td class="tg-yw4l">sec_ques_type=2<br>Object based question</td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=3<br>Clarification (for secondary) question</td>
    <td class="tg-031e"></td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=4<br>Set-based question</td>
    <td class="tg-031e">set_op_choice=1<br>OR<br><br>set_op_choice=2<br>AND<br><br>set_op_choice=3<br>Difference</td>
    <td class="tg-031e">is_inc=1<br>Incomplete version of set-based ques.</td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=5<br>Boolean (Factual Verification) question</td>
    <td class="tg-031e">bool_ques_type = 1<br>Verification|2 entities, both direct<br><br>bool_ques_type = 2<br>Verification|2 entities, one direct and one indirect, subject is indirect<br><br>bool_ques_type = 3<br>Verification|2 entities, one direct and one indirect, object is indirect<br><br>bool_ques_type = 4<br>Verification|3 entities, all direct, 2 are query entities<br><br>bool_ques_type = 5<br>Verification|3 entities, 2 direct, 2(direct) are query entities, subject is indirect<br><br>bool_ques_type = 6<br>Verification|one entity, multiple entities (as object) referred indirectly</td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=6<br>Incomplete question (for secondary)</td>
    <td class="tg-031e">inc_ques_type=1<br>Incomplete|object parent is changed, subject and predicate remain same<br><br>inc_ques_type=2<br>Only subject is changed, parent and predicate remains same<br><br>inc_ques_type=3<br>Incomplete count-based ques</td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">ques_type_id=7<br>Comparative and Quantitative questions (involving single entity)</td>
    <td class="tg-031e">count_ques_sub_type=1<br>Quantitative (count) single entity<br><br>count_ques_sub_type=2<br>Quantitative (min/max) single entity<br><br>count_ques_sub_type=3<br>Quantitative (atleast/atmost) single entity (which)<br><br>count_ques_sub_type=5<br>Quantitative (atleast/atmost) single entity (count)<br><br>count_ques_sub_type=7<br>Quantitative Indirect (count) single entity<br><br></td>
    <td class="tg-031e" rowspan="2">is_incomplete=1<br>Incomplete form (of the category of question)</td>
  </tr>
  <tr>
    <td class="tg-yw4l">count_ques_sub_type=4<br>Comparative (more/less) single entity (count)<br><br>count_ques_sub_type=6<br>Comparative(more/less) single entity (which)<br><br>count_ques_sub_type=8<br>Comparative Indirect (more/less) single entity (count)<br><br>count_ques_sub_type=9<br>Comparative Indirect (more/less) single entity (which)</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">ques_type_id=8<br>Comparative and Quantitative questions (involving multiple(2) entities)</td>
    <td class="tg-031e">count_ques_sub_type=1<br>Quantitative with Logical Operators<br><br>count_ques_sub_type=2<br>Quantitative (count) multiple entity<br><br>count_ques_sub_type=3<br>Quantitative (min/max) multiple entity<br><br>count_ques_sub_type=4<br>Quantitative (atleast/atmost) multiple entity (which)<br><br>count_ques_sub_type=6<br>Quantitative (atleast/atmost) multiple entity (count)<br><br>count_ques_sub_type=8<br>Quantitative Indirect (count) multiple entity<br><br></td>
    <td class="tg-031e" rowspan="2">is_incomplete=1<br>Incomplete form (of the category of question)</td>
  </tr>
  <tr>
    <td class="tg-yw4l">count_ques_sub_type=5<br>Comparative (more/less) multiple entity (count)<br><br>count_ques_sub_type=7<br>Comparative(more/less) multiple entity (which)<br><br>count_ques_sub_type=9<br>Comparative Indirect (more/less) single entity(count)<br><br>count_ques_sub_type=10<br>Comparative Indirect (more/less) multiple entity (which)</td>
  </tr>
</table>

### Dataset statistics

| ﻿Question Type                                                                                            | Train  | Valid | Test  | Train/Valid | Train/Test  |
|----------------------------------------------------------------------------------------------------------|--------|-------|-------|-------------|-------------|
| Simple&#124;Direct                                                                                       | 446927 | 47868 | 74800 | 9.336654968 | 5.974959893 |
| Simple&#124;Indirect                                                                                     | 285825 | 30397 | 49993 | 9.403066092 | 5.717300422 |
| Simple&#124;Incomplete                                                                                   | 54711  | 5913  | 8664  | 9.252663623 | 6.314750693 |
| Comparative&#124;Count over More/Less&#124;Mult. entity type&#124;Direct                                 | 37090  | 4199  | 6591  | 8.833055489 | 5.627370657 |
| Comparative&#124;Count over More/Less&#124;Mult. entity type&#124;Indirect                               | 8090   | 858   | 1427  | 9.428904429 | 5.66923616  |
| Comparative&#124;Count over More/Less&#124;Mult. entity type&#124;Incomplete                             | 15260  | 1747  | 2448  | 8.734974242 | 6.233660131 |
| Comparative&#124;Count over More/Less&#124;Single entity type&#124;Direct                                | 42930  | 4629  | 4472  | 9.274141283 | 9.599731664 |
| Comparative&#124;Count over More/Less&#124;Single entity type&#124;Indirect                              | 9793   | 1020  | 1222  | 9.600980392 | 8.01391162  |
| Comparative&#124;Count over More/Less&#124;Single entity type&#124;Incomplete                            | 17450  | 1885  | 1277  | 9.25729443  | 13.66483947 |
| Comparative&#124;More/Less&#124;Mult. entity type&#124;Direct                                            | 37784  | 3995  | 6677  | 9.457822278 | 5.658828815 |
| Comparative&#124;More/Less&#124;Mult. entity type&#124;Indirect                                          | 8161   | 899   | 1340  | 9.077864294 | 6.090298507 |
| Comparative&#124;More/Less&#124;Mult. entity type&#124;Incomplete                                        | 15598  | 1626  | 2449  | 9.592865929 | 6.369130257 |
| Comparative&#124;More/Less&#124;Single entity type&#124;Direct                                           | 43529  | 4639  | 4376  | 9.383272257 | 9.947212066 |
| Comparative&#124;More/Less&#124;Single entity type&#124;Indirect                                         | 9786   | 1082  | 1286  | 9.044362292 | 7.609642302 |
| Comparative&#124;More/Less&#124;Single entity type&#124;Incomplete                                       | 17781  | 1887  | 1228  | 9.422893482 | 14.47964169 |
| Logical&#124;Union&#124;Direct                                                                           | 30267  | 3347  | 5656  | 9.043023603 | 5.351308345 |
| Logical&#124;Intersection&#124;Direct                                                                    | 21151  | 2293  | 4086  | 9.224160488 | 5.176456192 |
| Logical&#124;Difference&#124;Direct                                                                      | 1497   | 166   | 298   | 9.018072289 | 5.023489933 |
| Logical&#124;Incomplete                                                                                  | 4909   | 533   | 1083  | 9.210131332 | 4.532779317 |
| Quantitative&#124;Atleast/ Atmost/ Approx. the same/Equal&#124;Mult. entity type&#124;Direct             | 25484  | 2674  | 4409  | 9.530291698 | 5.779995464 |
| Quantitative&#124;Atleast/ Atmost/ Approx. the same/Equal&#124;Single entity type&#124;Direct            | 31668  | 3439  | 2395  | 9.20849084  | 13.22254697 |
| Quantitative&#124;Count over Atleast/ Atmost/ Approx. the same/Equal&#124;Mult. entity type&#124;Direct  | 25210  | 2693  | 4367  | 9.361307092 | 5.772841768 |
| Quantitative&#124;Count over Atleast/ Atmost/ Approx. the same/Equal&#124;Single entity type&#124;Direct | 31121  | 3366  | 2323  | 9.245692216 | 13.39690056 |
| Quantitative&#124;Count&#124;Logical operators&#124;Direct                                               | 25731  | 2661  | 4001  | 9.669673055 | 6.431142214 |
| Quantitative&#124;Count&#124;Logical operators&#124;Indirect                                             | 9350   | 998   | 1621  | 9.368737475 | 5.768044417 |
| Quantitative&#124;Count&#124;Mult. entity type&#124;Direct                                               | 29420  | 3150  | 4925  | 9.33968254  | 5.973604061 |
| Quantitative&#124;Count&#124;Single entity type&#124;Direct                                              | 64225  | 6761  | 8318  | 9.499334418 | 7.721207021 |
| Quantitative&#124;Count&#124;Single entity type&#124;Indirect                                            | 15690  | 1645  | 2194  | 9.537993921 | 7.151321787 |
| Quantitative&#124;Count&#124;Single entity type&#124;Incomplete                                          | 26472  | 2752  | 3348  | 9.619186047 | 7.906810036 |
| Verification&#124;Single/Multiple Entity&#124;Direct                                                     | 66550  | 7101  | 13879 | 9.371919448 | 4.79501405  |
| Verification&#124;Single/Multiple Entity&#124;Indirect                                                   | 91061  | 9965  | 17003 | 9.138083292 | 5.355584309 |
| Clarification (All)                                                                                      | 62825  | 6761  | 9348  | 9.292264458 | 6.720688917 |
| Indirect (All)                                                                                           | 412716 | 44221 | 72271 | 9.333031817 | 5.710672331 |
| Incomplete (All)                                                                                         | 176284 | 18926 | 23453 | 9.314382331 | 7.516479768 |
| Logical&#124;Multiple Relations&#124;Direct                                                              | 29537  | 3209  | 5463  | 9.204425055 | 5.406736226 |
| Quantitative&#124;Min/Max&#124;Single entity type                                                        | 33580  | 3664  | 304   | 9.164847162 | 110.4605263 |
| Quantitative&#124;Min/Max&#124;Mult. entity type                                                         | 25363  | 2725  | 2813  | 9.307522936 | 9.016352648 |

### Types of questions in the dataset

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
</style>
<table class="tg">
  <tr>
    <th class="tg-031e">Reasoning</th>
    <th class="tg-031e">Type</th>
    <th class="tg-031e">Containing</th>
    <th class="tg-031e">Example</th>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="4">Logical</td>
    <td class="tg-031e">Union</td>
    <td class="tg-031e" rowspan="3">Single Relation</td>
    <td class="tg-031e">Which rivers flow through India or China?</td>
  </tr>
  <tr>
    <td class="tg-031e">Intersection</td>
    <td class="tg-031e">Which rivers flow through India and China?</td>
  </tr>
  <tr>
    <td class="tg-031e">Difference</td>
    <td class="tg-031e">Which rivers flow through India but not China?</td>
  </tr>
  <tr>
    <td class="tg-031e">Any of above</td>
    <td class="tg-031e">Multiple Relations</td>
    <td class="tg-031e">Which river flows through India but does not originate in Himalayas?</td>
  </tr>
  <tr>
    <td class="tg-031e">Verification</td>
    <td class="tg-031e">Boolean</td>
    <td class="tg-031e">Single/Multiple<br> Entities</td>
    <td class="tg-031e">Does Ganga flow through India ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="9">Quantitative</td>
    <td class="tg-031e" rowspan="3">Count</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">How many rivers flow through India ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">How many rivers and lakes does India have ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Logical Operators</td>
    <td class="tg-031e">How many rivers flow through India and/or/but not China?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Min/Max</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">Which river flows through maximum number of countries ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">Which country has maximum number of rivers and lakes combined ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Atleast/Atmost/<br>Approx/Equal</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">Which rivers flow through at least N countries ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">Which country has at least N rivers and lakes combined ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Count over <br>Atleast/Atmost/<br>Approx/Equal</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">How many rivers flow through at least N countries?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">How many countries have at least N rivers and lakes combined ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="4">Comparative</td>
    <td class="tg-031e" rowspan="2">More/Less</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">Which countries have more number of rivers than India ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">Which countries have more rivers and lakes than India ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Count over<br>More/Less</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">How many countries have more number of rivers than India ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">How many countries have more rivers and lakes than India ?</td>
  </tr>
</table>

### Overall Dataset Statistics

| Dataset Statistics                             | Train  | Valid | Test  |
|------------------------------------------------|--------|-------|-------|
| Total No. of Dialogs(chat sessions)            | 152391 | 16413 | 27797 |
| Avg. No. of Utterances per dialog              | 15.9   | 15.65 | 19.44 |
| Total No. of Utterances having Question/Answer | 1.2M   | .13M  | .27M  |
| Length of user’s question (in words)           | 9.7    | 9.68  | 10.28 |
| Length of system’s response (in words)         | 4.74   | 4.67  | 4.37  |
| Avg. No. of Dialog states per dialog           | 3.89   | 3.84  | 4.53  |
| Vocab size (freq>=10)                          | 0.1M   | -     | -     |
