MS: Word Properties and CLT
Variables:
- Child_id: participant unique identifier
- Edu_mother: mother's education level (high school, university)
- Sex: child's sex (boy/girl)
- Age: child's age at testing (years)
- word: the target word in CLT
- group: participant group (bilingual, monolingual)
- language: language of the task (Polish, Norwegian)
- trial: item order within the task (1-32)
- task: task type (C: comprehension, P: production)
- category: subtask (N: nouns, V: verbs)
- response_production: child's response in production
- response_category_production: classification of the child's response in production (e.g., correct, error: semantic)
- accuracy_soft: accuracy score accepting regional variants and synonyms in production (0/1)
- accuracy_strict: accuracy score not accepting regional variants and synonyms in production, only responses that included a form of the target word (0/1)
- reaction_time: response latency (in ms)
- reaction_time_manual: response latency coded manually (in ms)
- Imageability: rating of how easily the word evokes a mental image
- AoA: Age of Acquisition rating for the word
- FrequencyLemmaLogLog: transformed lemma frequency of the word
- frequency_cds: frequency of the word in child-directed speech
- *polish_first_contact_age: age at which the child was first exposed to Polish
- *norwegian_first_contact_age: age at which the child was first exposed to Norwegian
- *polish_input: language input in Polish at home
- *norwegian_input: language input in Norwegian at home
- *saturday_school: attendance and frequency at Polish Saturday (0 to 2; no, yes not regulary, yes regularly, no)
- *school_hours: hours per day the child spends in pre-school
- *pl_outside_input_combined: Polish input received outside the home (from PaBiQ) + richeness of contexts + saturday school
- *no_outside_input_combined: Polish input received outside the home (from PaBiQ) + richeness of contexts + (school_hours/3)
- *pl_input_sum: polish_input + pl_outside_input_combined
- *no_input_sum: norwegian_input + no_outside_input_combined
- *pl_input_sum_percentage: Polish input as a percentage of total combined input in Polish and Norwegian
- *no_input_sum_percentage: Norwegian input as a percentage of total combined input in Polish and Norwegian
- exposure_group: categorical grouping based on relative language exposure (e.g., Polish-dominant above 40% or balanced)

*Based on responses to the PaBiQ questionnaire (Mieszkowska et al., 2021; Tuller, 2015)