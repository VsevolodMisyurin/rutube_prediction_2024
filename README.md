# rutube_prediction_2024
Задача заключается в разработке модели, которая на основе истории просмотров пользователя сможет предсказать пол и возраст пользователя видеохостинга Rutube.

Основа решения - подсчёт слов из названия видео, наиболее связанных с каждой возрастной группой пользователей Rutube, и формирование признаков на основе особенностей распространения этих слов.

В репозитории находится два блокнота:

rutube_hack_EDA_FE_RM_KM_PR.ipunb c EDA, подготовкой признаков и обучением линейной и логистической регрессии, а также K-means кассификатором
rutube_hack_EDA_FE_RM_KM_PR_TS.ipunb, расширенная версия прошлого документа, но с предсказанием для тестового файла

При запуске необходимо проверить ссылку на директорию, в которой находятся .csv-датасеты.
В финальном файле submission.csv признак 'age' не предсказывается, а устанавливается как колонка с нулями для корректной отправки в качестве решения.

Команда 'Мои все хорошие'.

Всеволод Мисюрин; Капитан, ML-инженер; @v87am

Алексей Копылов; Data Scientist; @ManWithMidlifeCrysis

Галина Ялышева; Дизайнер; @Galina_sum
