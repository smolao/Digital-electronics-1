# Lab 8 - Traffic light controller

## 1st part - Preparation task

### State table

| *Input P* | 0 | 0 | 1 | 1 | 0 | 1 | 0 | 1 | 1 | 1 | 1 | 0 | 0 | 1 | 1 | 1 |
| :-- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| *Clock* | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) | ![rising](Images/arrow.png) |
| *State* | A | A | B | C | C | D | A | B | C | D | B | B | B | C | D | B |
| *Output R* | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 |