# income-group-modeling

Project repository for class assignment of WIE3007 Data Mining and Warehousing at University of Malaya, session 2023/2024 (Semester 1).

> **Submission items:**
>
> - Project report: [link](https://github.com/hongjiaherng/income-group-modeling/blob/main/submission/WIE3007%20Group%20Assignment%20Report.pdf)
> - Presentation slides: [link](https://github.com/hongjiaherng/income-group-modeling/blob/main/submission/WIE3007%20Group%20Assignment%20Slides.pdf)
> - Presentation video: [link](https://drive.google.com/file/d/1V2lSD_1nrDhZUlHMh7PTBnzSKUlKaUrr/view?usp=sharing)

## Project Description

The project is to build a predictive model to predict the income group of a person based on the given features. This project is done using SAS Enterprise Miner abiding by SAS SEMMA methodology.

> SEMMA: Sample, Explore, Modify, Model, Assess

The dataset used in this project is the [Adult Income Dataset](https://www.kaggle.com/datasets/kritidoneria/adultdatasetxai) from Kaggle.

## Getting Started

### Prerequisites

- SAS Enterprise Miner
- Python, Jupyter Notebook

### Setup

1. Clone the repository

```bash
git clone https://github.com/hongjiaherng/income-group-modeling.git
```

2. Open the project in SAS Enterprise Miner
3. Modify the File Import node to point to the correct location of the dataset
4. Run the nodes in the SAS Enterprise Miner project

## Dataset Description

The dataset contains 32561 instances with 14 attributes. The attributes are:

| No. | Attribute      | Description                                                                                                                                                                                                                                                                                                                                                                                                                    |
| --- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | gross_income   | The income group of the person. The value is either `<=50K` or `>50K`.                                                                                                                                                                                                                                                                                                                                                         |
| 2   | age            | continuous                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 3   | work_class     | Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked                                                                                                                                                                                                                                                                                                                          |
| 4   | final_weight   | continuous                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 5   | education      | Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool                                                                                                                                                                                                                                                                          |
| 6   | education_num  | continuous                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 7   | marital_status | Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse                                                                                                                                                                                                                                                                                                                      |
| 8   | occupation     | Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces                                                                                                                                                                                                       |
| 9   | relationship   | Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried                                                                                                                                                                                                                                                                                                                                                             |
| 10  | race           | White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black                                                                                                                                                                                                                                                                                                                                                                    |
| 11  | sex            | Female, Male                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 12  | capital_gain   | continuous                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 13  | capital_loss   | continuous                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 14  | hours_per_week | continuous                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 15  | native_country | United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands |

## Contributors

- [Chai Nam Chi](https://github.com/ChaiNamChi0624) (U2005421/1)
- [Cheong Hui Ting](https://github.com/jeongie) (U2005292/1)
- [Hong Jia Herng](https://github.com/hongjiaherng) (U2005313/1)
- [Lee Hui Xin](https://github.com/SeriousLee20) (U2005353/1)
- [Liewn Wan Chyi](https://github.com/WCHYI-CHEESE) (U2005418/1)
