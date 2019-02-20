# Comparison of Automated Mastering Services

## Abstract

We proposed an objective mix evaluation index called MixEvaluationIndex20190207(or MEI20190207) that is constructed based on subjective mix evaluation data retrieved from [THE MIX EVALUATION DATASET](http://www.brechtdeman.com/publications/pdf/DAFx-17.pdf).

We compared the mastered audio quality of automated mastering services (AI Mastering and LANDR) using various indicies including MEI20190207.

AI Mastering seems better than LANDR from the perspective of MEI20190207.
However, there is a need to further study about the validity of MEI20190207 because of dataset bias (e.g. all mixes in datasets have high dynamic range compared to mastered audios).

Please check if mastered audios that have high MixEvaluationIndex20190207 are actually good.

## Comparison Targets

- [AI Mastering](http://aimastering.com)
- [LANDR](https://landr.com)

## Result Summary

### MixEvaluationIndex20190207 Change

![MixEvaluationIndex20190207 Change](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/stats/aggregated/mei20190207_change.png)

### Loudness vs Loudness Range

![Loudness vs Loudness Range](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/stats/aggregated/loudness_vs_loudness_range.png)

### True Peak

![True Peak](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/stats/aggregated/true_peak.png)

### Dissonance Change

![Dissonance Change](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/stats/aggregated/dissonance_change.png)

### Hardness Change

![Hardness Change](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/stats/aggregated/hardness_change.png)

### more data

All results are available in stats directory.

## Audio Comparison


### InTheMeantime

|Service/Settings|MEI20190207 Rank|MEI20190207|Audio|
|:-:|:-:|:-:|:-:|
|Original|13|0.6568856051215048|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/InTheMeantime/DU-H/DU-H.wav)|
|AI Mastering (level 0.0, -12.0dB)|6|0.8903143559671387|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-12_mastering_level0.wav)|
|AI Mastering (level 0.0, -10.0dB)|10|0.8731447561481194|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-10_mastering_level0.wav)|
|AI Mastering (level 0.0, -8.0dB)|7|0.8833304362146213|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-8_mastering_level0.wav)|
|AI Mastering (level 0.5, -12.0dB)|2|0.9850537690088825|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-12_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -10.0dB)|1|0.9945873666852472|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-10_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -8.0dB)|3|0.9115010315417398|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-8_mastering_level0.5.wav)|
|AI Mastering (level 1.0, -12.0dB)|11|0.8712285143889935|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-12_mastering_level1.wav)|
|AI Mastering (level 1.0, -10.0dB)|8|0.8766534265851891|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-10_mastering_level1.wav)|
|AI Mastering (level 1.0, -8.0dB)|5|0.8969120467440757|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/InTheMeantime/DU-H/DU-H_target_loudness-8_mastering_level1.wav)|
|LANDR (lo)|9|0.8764654694927303|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/InTheMeantime/DU-H/LANDR-DU-H_lo.wav)|
|LANDR (med)|4|0.9041434880571413|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/InTheMeantime/DU-H/LANDR-DU-H_med.wav)|
|LANDR (hi)|12|0.8261471508284708|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/InTheMeantime/DU-H/LANDR-DU-H_hi.wav)|


### LeadMe

|Service/Settings|MEI20190207 Rank|MEI20190207|Audio|
|:-:|:-:|:-:|:-:|
|Original|13|0.5779150707286589|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/LeadMe/GeorgeMassenburg/LeadMe_GM.wav)|
|AI Mastering (level 0.0, -12.0dB)|10|0.6426226859579769|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-12_mastering_level0.wav)|
|AI Mastering (level 0.0, -10.0dB)|8|0.6817293955564483|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-10_mastering_level0.wav)|
|AI Mastering (level 0.0, -8.0dB)|7|0.7022307718052216|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-8_mastering_level0.wav)|
|AI Mastering (level 0.5, -12.0dB)|6|0.7625010222435649|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-12_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -10.0dB)|3|0.7839712178740927|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-10_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -8.0dB)|1|0.7999746597622968|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-8_mastering_level0.5.wav)|
|AI Mastering (level 1.0, -12.0dB)|5|0.7633246115046106|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-12_mastering_level1.wav)|
|AI Mastering (level 1.0, -10.0dB)|4|0.779679221827082|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-10_mastering_level1.wav)|
|AI Mastering (level 1.0, -8.0dB)|2|0.793473257907946|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/LeadMe/GeorgeMassenburg/LeadMe_GM_target_loudness-8_mastering_level1.wav)|
|LANDR (lo)|12|0.6104354748144973|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/LeadMe/GeorgeMassenburg/LANDR-LeadMe_GM_lo.wav)|
|LANDR (med)|11|0.6393640700499088|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/LeadMe/GeorgeMassenburg/LANDR-LeadMe_GM_med.wav)|
|LANDR (hi)|9|0.6447399850652897|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/LeadMe/GeorgeMassenburg/LANDR-LeadMe_GM_hi.wav)|


### NotAlone

|Service/Settings|MEI20190207 Rank|MEI20190207|Audio|
|:-:|:-:|:-:|:-:|
|Original|13|0.48257047219302485|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/NotAlone/McG-A/NotAlone_A.wav)|
|AI Mastering (level 0.0, -12.0dB)|11|0.5231648622372371|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-12_mastering_level0.wav)|
|AI Mastering (level 0.0, -10.0dB)|9|0.5553171592573396|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-10_mastering_level0.wav)|
|AI Mastering (level 0.0, -8.0dB)|7|0.5939936969884216|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-8_mastering_level0.wav)|
|AI Mastering (level 0.5, -12.0dB)|6|0.6231469488431141|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-12_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -10.0dB)|5|0.64725570362966|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-10_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -8.0dB)|4|0.681312613663448|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-8_mastering_level0.5.wav)|
|AI Mastering (level 1.0, -12.0dB)|3|0.7092468467942112|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-12_mastering_level1.wav)|
|AI Mastering (level 1.0, -10.0dB)|2|0.7391343588322199|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-10_mastering_level1.wav)|
|AI Mastering (level 1.0, -8.0dB)|1|0.7738417297478148|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/NotAlone/McG-A/NotAlone_A_target_loudness-8_mastering_level1.wav)|
|LANDR (lo)|12|0.5177694307341181|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/NotAlone/McG-A/LANDR-NotAlone_A_lo.wav)|
|LANDR (med)|10|0.5301580219081241|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/NotAlone/McG-A/LANDR-NotAlone_A_med.wav)|
|LANDR (hi)|8|0.5558005488267133|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/NotAlone/McG-A/LANDR-NotAlone_A_hi.wav)|


### PouringRoom

|Service/Settings|MEI20190207 Rank|MEI20190207|Audio|
|:-:|:-:|:-:|:-:|
|Original|10|0.30384273879121526|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/PouringRoom/McG-Q/PouringRoom_Q.wav)|
|AI Mastering (level 0.0, -12.0dB)|9|0.3336063781685228|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-12_mastering_level0.wav)|
|AI Mastering (level 0.0, -10.0dB)|8|0.3550314007243762|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-10_mastering_level0.wav)|
|AI Mastering (level 0.0, -8.0dB)|7|0.3579782008928494|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-8_mastering_level0.wav)|
|AI Mastering (level 0.5, -12.0dB)|6|0.4101967080751592|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-12_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -10.0dB)|5|0.42280286809141887|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-10_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -8.0dB)|4|0.4425067707057937|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-8_mastering_level0.5.wav)|
|AI Mastering (level 1.0, -12.0dB)|3|0.4870087573209856|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-12_mastering_level1.wav)|
|AI Mastering (level 1.0, -10.0dB)|2|0.49507863324789225|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-10_mastering_level1.wav)|
|AI Mastering (level 1.0, -8.0dB)|1|0.5144816971461217|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/PouringRoom/McG-Q/PouringRoom_Q_target_loudness-8_mastering_level1.wav)|
|LANDR (lo)|13|0.28329351140384285|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/PouringRoom/McG-Q/LANDR-PouringRoom_Q_lo.wav)|
|LANDR (med)|12|0.2978973731809984|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/PouringRoom/McG-Q/LANDR-PouringRoom_Q_med.wav)|
|LANDR (hi)|11|0.3007555113813294|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/PouringRoom/McG-Q/LANDR-PouringRoom_Q_hi.wav)|


### RedToBlue

|Service/Settings|MEI20190207 Rank|MEI20190207|Audio|
|:-:|:-:|:-:|:-:|
|Original|13|0.4904558390370397|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/RedToBlue/JA/RedToBlue_JA.wav)|
|AI Mastering (level 0.0, -12.0dB)|12|0.49955034816391186|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-12_mastering_level0.wav)|
|AI Mastering (level 0.0, -10.0dB)|10|0.537485544425039|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-10_mastering_level0.wav)|
|AI Mastering (level 0.0, -8.0dB)|7|0.5695406207973093|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-8_mastering_level0.wav)|
|AI Mastering (level 0.5, -12.0dB)|6|0.5824172293452627|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-12_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -10.0dB)|5|0.6106067094000764|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-10_mastering_level0.5.wav)|
|AI Mastering (level 0.5, -8.0dB)|4|0.6359701881584552|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-8_mastering_level0.5.wav)|
|AI Mastering (level 1.0, -12.0dB)|3|0.6533688714703021|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-12_mastering_level1.wav)|
|AI Mastering (level 1.0, -10.0dB)|2|0.6720274923722775|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-10_mastering_level1.wav)|
|AI Mastering (level 1.0, -8.0dB)|1|0.6991642941950311|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/aimastering/RedToBlue/JA/RedToBlue_JA_target_loudness-8_mastering_level1.wav)|
|LANDR (lo)|11|0.5339862191837641|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/RedToBlue/JA/LANDR-RedToBlue_JA_lo.wav)|
|LANDR (med)|9|0.5447674263196023|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/RedToBlue/JA/LANDR-RedToBlue_JA_med.wav)|
|LANDR (hi)|8|0.5651982871738963|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/mastered/landr/RedToBlue/JA/LANDR-RedToBlue_JA_hi.wav)|



## Automated Mastering Settings

### AI Mastering

|Settings Name|Target Loudness|Automatic Mastering|Mastering Level|
|:-:|:-:|:-:|:-:|
|Level 0.0, -12dB|-12dB|Disabled|-|
|Level 0.0, -10dB|-10dB|Disabled|-|
|Level 0.0, -8dB|-8dB|Disabled|-|
|Level 0.5, -12dB|-12dB|Enabled|0.5|
|Level 0.5, -10dB|-10dB|Enabled|0.5|
|Level 0.5, -8dB|-8dB|Enabled|0.5|
|Level 1.0, -12dB|-12dB|Enabled|1.0|
|Level 1.0, -10dB|-10dB|Enabled|1.0|
|Level 1.0, -8dB|-8dB|Enabled|1.0|

Common settings

- Mode: Custom Mastering
- Target Loudness Mode: Loudness
- Ceiling Mode: Peak
- Ceiling: -0.3dBFS (same as LANDR)
- Oversampling: 2x
- Automatic Mastering Preset: General
- Specify Reference Audio By Myself: False
- Sampling Rate: 44100Hz
- Low Cut Freq: 20Hz
- High Cut Freq: 20000Hz
- Preserve Bass: True
- Format: 16bit WAV

### LANDR

|Settings Name|Intensity Level|
|:-:|:-:|
|Lo|Lo|
|Med|Med|
|Hi|Hi|

Common settings

- Format: 16bit WAV

## Test Audio Tracks

Test audio tracks are stored in audio/source/(song_name)/(mix_name)/(filename).mp3.
Test audio tracks are chosen by following conditions.

- Subjective evaluation data is available in [THE MIX EVALUATION DATASET](http://www.dafx17.eca.ed.ac.uk/papers/DAFx17_paper_49.pdf).
- distributed in The Open Multitrack Testbed - http://multitrack.eecs.qmul.ac.uk/ by Brecht De Man
- licensed under CC BY 4.0
- first 1 mix in each song. (mix name alphabetical order)

|Name|Original Audio (44.1kHz 24bit formatted)|
|:-:|:-:|
|LeadMe|[LeadMe](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/LeadMe/GeorgeMassenburg/LeadMe_GM.wav)|
|InTheMeantime|[InTheMeantime](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/InTheMeantime/DU-H/DU-H.wav)|
|NotAlone|[NotAlone](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/NotAlone/McG-A/NotAlone_A.wav)|
|PouringRoom|[PouringRoom](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/PouringRoom/McG-Q/PouringRoom_Q.wav)|
|RedToBlue|[RedToBlue](https://raw.githubusercontent.com/ai-mastering/mastering_comparison/master/audio/formatted/RedToBlue/JA/RedToBlue_JA.wav)|


## Measures

### MEI20190207

MEI20190207(MixEvaluationIndex20190207) is an index which is constructed based on Mix Evaluation Datasets.
MEI20190207 is calculated by stepwise linear regression using AIC.
Dependent variable is subjective mix evaluation score in Mix Evaluation Datasets.

Mix Evaluation Datasets: https://intelligentsoundengineering.wordpress.com/2017/09/01/the-mix-evaluation-dataset/

#### Selected explanatory variables and calculated coefs

|variable|coef|
|:-:|:-:|
|(Intercept)|1.03768547278472|
|bands_loudness0|0.00951325481004556|
|bands_loudness1|0.0164689071562976|
|bands_loudness7|0.0340216880860531|
|bands_loudness8|-0.0135561668568519|
|bands_loudness_range0|-0.0226949569352303|
|bands_loudness_range4|-0.0271575570115004|
|bands_mid_to_side_loudness2|0.0140066290330022|
|bands_mid_to_side_loudness5|-0.0104747618124023|
|covariance0_0|0.0919264284783258|
|covariance0_11|0.082558807133752|
|covariance0_12|-0.0342145316780618|
|covariance0_14|-0.0466198784131165|
|covariance0_15|0.0207276709645042|
|covariance0_16|0.0581059748423357|
|covariance0_17|-0.0393395203204817|
|covariance0_2|0.0411876866727139|
|covariance0_3|-0.0215521919930233|
|covariance0_9|-0.088577268407794|
|covariance10_13|-0.100081415393531|
|covariance11_12|0.108701115978759|
|covariance11_17|0.0379840675918427|
|covariance12_12|-0.0317636259791887|
|covariance1_12|-0.0589751072674823|
|covariance1_13|0.0284709024236286|
|covariance1_14|0.0556894684542315|
|covariance1_17|-0.0326130537643269|
|covariance1_4|0.0328017450878317|
|covariance2_10|0.0932133176211998|
|covariance2_16|-0.0682805249102863|
|covariance2_6|-0.0722886720490166|
|covariance3_11|-0.0356880644852162|
|covariance3_15|0.105958890021132|
|covariance3_3|-0.0585601702672593|
|covariance3_5|0.0414072559900464|
|covariance3_8|-0.0204928905344907|
|covariance4_15|0.0885603084432147|
|covariance4_6|0.0716787998562132|
|covariance5_15|-0.0808888836972396|
|covariance6_12|-0.0588472383077768|
|covariance6_7|-0.066752090504072|
|covariance7_8|0.155933392935423|
|covariance8_10|0.0368074690742597|
|covariance8_9|-0.0328605125125517|
|covariance9_15|-0.0519423428333282|
|covariance9_16|0.0655070769913487|
|dissonance|-0.083778229293513|
|timbral_models_hardness|0.0303721487308621|


#### Explanatory variable candidates

see columns of stats/audios.tsv

#### Learning Dataset

All preview data and subjective evaluation data that can be downloaded from http://c4dm.eecs.qmul.ac.uk/multitrack/MixEvaluation/.
(some data are excluded because of 404)

## Analyzer

### AI Mastering Analyzer

An audio analyzer used in AI Mastering.
This is not distributed.

Analysis data is in analysis directory
Analysis data with pre loudness normalization is in analysis_normalized directory.

Pre loudness normalization is done because the learning dataset is loudness normalized.
Pre loudness noramlization is done by adjusting ITU-R BS.1770 Loudness to -24.06.

The mean value of learning dataset ITU-R BS.1770 loudness is -24.06.

### timbral_models

timbral_models is a python library to calculate some timbral indicies by AudioCommons.
https://github.com/AudioCommons/timbral_models

timbral_models is used for calculate Hardness.
Hardness is required to calculate MixEvaluationIndex20190207.

Pre loudness normalization is done like analysis_normalized.

## Directories

### audio

Source and mastered audio.

source -> formatted -> mastered

### analysis

Analyzed data of all audios in audio directory.

### stats

Statistics of analysis data.

## FFmpeg

### wav encode command

All source audios are formatted in 44.1kHz 24bit Float PCM WAV by following command to equalize experiment conditions.

```
ffmpeg -i /path/to/input.wav -ac 2 -ar 44100 -acodec pcm_s24le -f wav /path/to/output.wav
```

### version

```
ffmpeg version 4.0.2 Copyright (c) 2000-2018 the FFmpeg developers
  built with Apple LLVM version 9.1.0 (clang-902.0.39.2)
  configuration: --prefix=/usr/local/Cellar/ffmpeg/4.0.2 --enable-shared --enable-pthreads --enable-version3 --enable-hardcoded-tables --enable-avresample --cc=clang --host-cflags= --host-ldflags= --enable-gpl --enable-libmp3lame --enable-libx264 --enable-libxvid --enable-opencl --enable-videotoolbox --disable-lzma
  libavutil      56. 14.100 / 56. 14.100
  libavcodec     58. 18.100 / 58. 18.100
  libavformat    58. 12.100 / 58. 12.100
  libavdevice    58.  3.100 / 58.  3.100
  libavfilter     7. 16.100 /  7. 16.100
  libavresample   4.  0.  0 /  4.  0.  0
  libswscale      5.  1.100 /  5.  1.100
  libswresample   3.  1.100 /  3.  1.100
  libpostproc    55.  1.100 / 55.  1.100
```

## Related Work

### THE MIX EVALUATION DATASET

Subjective mix evaluation data are collected.
http://www.brechtdeman.com/publications/pdf/DAFx-17.pdf

### Perceptual evaluation of music mixing practices

It reveals that the following 4 features are correlated with subjective mix evaluation score.
https://www.researchgate.net/publication/283675867_Perceptual_evaluation_of_music_mixing_practices

#### LDR (Micro Dynamics)

Proposed in https://www.researchgate.net/publication/292846489_Measures_of_microdynamics.
Algorithm summary is available in https://www.researchgate.net/publication/317091912_Towards_the_Development_of_Preference_Models_accounting_for_the_Impact_of_Music_Production_Techniques.
The 95 percentile of diff between slow loudness(3sec) and fast loudness(25ms).

#### 4 kHz octave band energy ratio (Spectral Envelope)

This feature seems to represent spectral envelope.

#### MFCC4 (Spectral Envelope)

This feature seems to represent spectral envelope.

#### side-to-mid energy ratio (Space)

This feature seems to represents space.

### Modelling Timbral Hardness

Hardness index is constructed by using subjective evaluation data.
https://www.mdpi.com/2076-3417/9/3/466
This hardness is implemented in https://github.com/AudioCommons/timbral_models.

## Contact

If you have any questions please contact us.
Questions about our service( AI Mastering ) are also welcome.

- Twitter: https://twitter.com/ai_mastering
- E-mail: aimasteringcom@gmail.com

## LICENSE

- All files excluding audio directory are licensed under CC0.
- Translation, writing about this survey, and quotation are welcome.
