# Vitiligo-Healthcare-Disparities
Codelists, exposure/outcome definitions and algorithms for the study titled: "The lifetime risk and impact of vitiligo across sociodemographic groups: a UK population-based cohort study" by Momentum Data.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification
All of the conditions and medication codes mentioned below will use diagnostic codes recorded in primary care only. Using Read V2, Read CTV3 and SNOMED codes.

## Vitiligo case definition
1. Any individual with a [vitiligo diagnosis code](https://github.com/MomentumData/Momentum-Data-Codelists/tree/228b1cae0eb4b324500fc3cf9e6e416751b4f731/Conditions/Vitiligo).
2. **AND** no diagnosis code for an alternative depigmenting disorder or a [vitiligo diagnosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/228b1cae0eb4b324500fc3cf9e6e416751b4f731/Conditions/Vitiligo) **within six months of practice registration**.

### Alternative depigmenting disorders:
- [Congenital and Genetic Hypomelanoses](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Conditions/Congenital%20and%20Genetic%20Hypomelanoses%20v1)
- Post-Inflammatory Hypomelanoses:
  - [Post inflammatory leukoderma including after atopic eczema or psoriasis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Post-inflammatory%20Hypopigmentation)
  - [Lichen Planus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Lichen%20Planus)
  - [Pityriasis Alba](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Pityriasis%20Alba)
  - [Lichen Sclerosus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Lichen%20Sclerosis)
- [Post-Traumatic Leukoderma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Conditions/Post-traumatic%20Leucoderma)
- [Para-Malignant Hypomelanoses](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Para-malignant%20Hypomelanoses)
- Occupational/Drug Induced Hypomelanoses:
  - [Occupational Vitiligo](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Conditions/Occupational%20Vitiligo)
  - [Other Induced Hypomelanoses](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Conditions/Other%20Induced%20Hypomelanoses%20v1)
- Para-Infectious Hypopigmentation:
  - [Pityriasis versicolor (or tinea versicolor)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Pityriasis%20Versicolor)
- Others:
- [Melasma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Melasma)
- [Morphoea](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Morphoea)
- [Idiopathic Guttate Hypomelanosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Idiopathic%20Guttate%20Hypomelanoses)
- [Xeroderma Pigmentosum](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Xeroderma%20Pigmentosum)
- [Progressive Macular Hypomelanosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Progressive%20Macular%20Hypomelanosis)
- [Nevus Depigmentosus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Nevus%20Depigmentosus)
- [Cutaneous Sarcoidosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/1c1c290f6f76079f24a317ce31e3876d1c3b3702/Conditions/Cutaneous%20Sarcoidosis)

## Depression
Any of:
- People identified with a diagnosis code for [recurrent depressive disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/RDD%20(Recurrent%20Depressive%20Disorder)).
- People identified with a diagnosis code for [depressive episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Depressive%20Episodes) **AND** any coded depression treatment* after 365 days.

## Anxiety
- People identified with a diagnosis code for [anxiety episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Anxiety%20Episode) **AND** within 6 months any coded anxiety treatment**.

*List of depression treatments:
- [Selective Seratonin Reuptake Inhibitors (SSRIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/SSRIs%20(Selective%20Serotonin%20Reuptake%20Inhibitors))
- [Tricyclic Antidepressants (TCAs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/TCAs%20(Tricyclic%20Antidepressants))
- [Monoamine Oxidase Inhibitors (MAOIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/MAOIs%20(Monoamine%20Oxidase%20Inhibitors))
- [Counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Counselling)
- [Psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Psychotherapy)
- [Cognitive Behavioural Therapy (CBT)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))

**List of anxiety treatments:
- [SSRIs](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/SSRIs%20(Selective%20Serotonin%20Reuptake%20Inhibitors))
- [Anxiolytics](https://github.com/MomentumData/Momentum-Data-Codelists/tree/cf32fa7b70d7bf2d1d7436262f059c46eb2b2317/Treatments/Anxiolytics)
- [Counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Counselling)
- [Psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Psychotherapy)
- [CBT](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))

## Parasuicide/Suicide Attempts
- People identified with a diagnosis code for [parasuicide](https://github.com/MomentumData/Momentum-Data-Codelists/tree/5558454c395b643b3a112a3bfd548cf58301cb2a/Conditions/Parasuicide).

## Sleep Disturbance
- People identified with a diagnosis code for [sleep disturbance](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Conditions/Sleep%20disturbance)

## Adjustment Disorder
- People identified with a diagnosis code for [adjustment disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/5558454c395b643b3a112a3bfd548cf58301cb2a/Conditions/Adjustment%20Disorder)

## Mental Health Referrals
Any of:
- People identified with a code for [counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Treatments/Counselling)
- People identified with a code for [cognitive behaviour therapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))
- People identified with a code for [psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Treatments/Psychotherapy)
- People identified with a code for [psychiatry review](https://github.com/MomentumData/Momentum-Data-Codelists/tree/5558454c395b643b3a112a3bfd548cf58301cb2a/Care%20Use/Psychiatry%20Review)
- People identified with a code for [IAPT (Improving Access to Psychological Therapies)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/5558454c395b643b3a112a3bfd548cf58301cb2a/Care%20Use/IAPT%20(Improving%20Access%20to%20Psychological%20Therapies))

## Dermatology Referrals
Any of:
- People identified with a code for [specialist dermatology referral](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Care%20Use/Specialist%20Dermatology%20Referral) 
- People identified with a code for [specialist dermatology review](https://github.com/MomentumData/Momentum-Data-Codelists/tree/5558454c395b643b3a112a3bfd548cf58301cb2a/Care%20Use/Specialist%20Dermatology%20Review)
- 
## Time off Work
- People identified with a code for [a MED3 Certificate](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Care%20Use/MED3%20Certificate)

## Unemployment
- People identified with a code for [unemployment](https://github.com/MomentumData/Momentum-Data-Codelists/tree/012658c49e400d47cb386286a19833c67cc09a4b/Conditions/Unemployment)
