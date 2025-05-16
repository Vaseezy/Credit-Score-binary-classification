# Credit-Score-binary-classification
Задача анализа одобрения кредита на основе данных с Kaggle. Является "пробой пера" начинающего специалиста, для демонстрации навыков, приобретенных в процессе обучения.

Данные взяты с соревновательной площадки Kaggle. Этот датасет представляет собой синтетическую версию, основанную на исходном наборе данных о кредитном риске с прошедшего в 2018 году соревнования: Loan Approval Classification Dataset
https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data?resource=download

Данный набор данных позволяет проанализировать факторы финансового риска и моделирования процессов прогнозного моделирования для утверждения кредита и оценки кредитоспособности.

| Column                          | Description                                                             
|---------------------------------|------------------------------------------------------------------------------------------------------
| person_age                      | Age of the person - Возраст человека                                       
| person_gender                   | Gender of the person - Пол человека                                       
| person_education                | Highest education level - Уровень образования                         
| person_income                   | Annual income - Годовой доход                                            
| person_emp_exp                  | Years of employment experience - Опыт работы (в годах)                
| person_home_ownership           | Home ownership status (e.g., rent, own, mortgage) - Статус жилья (аренда, собственность, ипотека) 
| loan_amnt                       | Loan amount requested - Запрашиваемая сумма кредита                     
| loan_intent                     | Purpose of the loan - Цель кредита                                        
| loan_int_rate                   | Loan interest rate - Процентная ставка по кредиту                          
| loan_percent_income             | Loan amount as a percentage of annual income - Сумма кредита в процентах от дохода
| cb_person_cred_hist_length      | Length of credit history in years - Длина кредитной истории (в годах) 
| credit_score                    | Credit score of the person - Кредитный рейтинг человека                   
| previous_loan_defaults_on_file  | Indicator of previous loan defaults - Признак дефолтов по прошлым кредитам
| loan_status (target variable)   | Loan approval status: 1 = approved; 0 = rejected - Статус одобрения кредита: 1 = одобрен, 0 = отклонён

В данном исследовании проведены:
1) EDA анализ
2) Построение нескольких Baseline моделей
3) Подбор параметров и обучения моделей на них
4) Stacking, выводы и анализ признаков. 
