# [Week 3: The Prep School - Passing Grades](https://preppindata.blogspot.com/2022/01/2022-week-3-prep-school-passing-grades.html)

## Requirements

- Input the data sets ([Set 1](https://drive.google.com/file/d/1p8gt3cR3ATCeGK81pnT90x0a6dbCXst1/view),[Set 2](https://drive.google.com/file/d/135o1Kj9koWM5eZ4VJjH9EUCyo1UnP54C/view))
- Join the data sets together to give us the grades per student
- Remove the parental data fields, they aren't needed for the challenge this week
- Pivot the data to create one row of data per student and subject
- Rename the pivoted fields to Subject and Score
- Create an average score per student based on all of their grades
- Create a field that records whether the student passed each subject
  - Pass mark is 75 and above in all subjects
- Aggregate the data per student to count how many subjects each student passed
- Round the average score per student to one decimal place
- Remove any unnecessary fields and output the data [(Output)](https://drive.google.com/file/d/1WrsXao4IFq8T6TiTl2YcXDe5XpV2jEk4/view)

## Sample of Student Dataset

![Dataset](https://blogger.googleusercontent.com/img/a/AVvXsEgagLPFUgVSh7Ipenk3Hvs8ObF_Sa-Oxuo6CqQ4SJcZa3aCuzyHTWxCdPf6i9f_6NTbeVpkN1HsmK8oq0b3stRlSQbhcZvK2Af3hrQWDSDee5-4zklBKRbPmaQgrqec07Kasuk9IFR2Qfbpig2OjkkuyItH2as0ur8HjYg0pZ4WVDGYYnpzMHTBHU9WsA=s1860)

## Sample of Grades Dataset

![Dataset](https://blogger.googleusercontent.com/img/a/AVvXsEhG75oGdjqX7GRd5wqfWEoH2MIbulR93ino97FGlv41-plQduecTVW9XiSBysi48jLd2TO6uqAK2whTEjuCj7tO1f0vPo_WlsFUI_XYmhpERCY4RWdKbyQMDMikB-VN9ZldPzlFnP8BIawwFdorw6g_hmrX_qv-eUQDJM3I998iq7FgxKwLCthf5zcwuQ=s1610)

## Sample of Expected Output

![Result](https://blogger.googleusercontent.com/img/a/AVvXsEi19SygYZ4475lvHLpyw7NB5GTeJDhKLOnbkphW4fLs6NG03PXUQoOsTwmf1xIFMClek23Kia3U11kXK5J_j3jO1KSHwNLSFuzlcwjdF0F8D3Pz0W6n9M1LWYA8lUYmf4vTePetVdt7ES8CgxM4e4op8tg-OO0M1XkgQyWKDyer81bBMXvCQ8Mqwlqnlw=w640-h402)

### 4 data fields:

- Passed Subjects
- Student's Avg Score
- Student ID
- Gender

Dataset size: 1000 rows (1001 including headers)
