# Kuzushiji 49

- `plot_grid` Отрисовка 4 случайных графиков
- `plot_grid_and_label` Отрисовка 4 случайных графиков c label (реальным и предсказанным)
- `ModelCheckpoint` Сохраняет модель и ее сосотояние, позволяет потом выгрузить для запуска 
- `TensorBoard` Подключает графики обучения модели

## Model fit

Categorical Cross-Entropy: $$H(y,y`) = - sum(y * log(y`))$$

y - истинное
y` - предсказанное

## Борьба с дисбалансом классов

- Oversampling (0.8515507207167022)
- Undersampling (0.5960840635621801)
- Synthetic Minority Over-sampling Technique (SMOTE) (0.8520026602021403)
- Adaptive Synthetic Sampling (ADASYN) (0.8474381482436714)
- Compute class weight (0.8247647388033172)