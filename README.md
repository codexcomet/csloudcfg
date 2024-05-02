# Best LAUNCH OPTIMIZED GPUxCPU
> [!TIP] 
-nojoy -thread 17 -fullscreen -forcenovsync +r_dynamic 0 -softparticlesdefaultoff +mat_disable_fancy_blending 1 +mat_queue_mode 2

>- -softparticlesdefaultoff - частицы будут отображаться без растушевки (смешивания глубины сцены), что может вызвать повышение FPS, но снизить качество графики вашей игры. 
>- +r_dynamic 0 - это консольная команда, которую ошибочно принимают за опцию запуска (но в любом случае она работает как таковая). Он отключает динамическое освещение, что может привести к увеличению FPS. Эффекты этой команды смотрите в этом видео. 
>-  +mat_queue_mode 2 - еще одна консольная команда, которую игроки часто используют в качестве параметра запуска (неважно, включили ли вы ее в свой autoexec или в качестве параметра запуска). Это может улучшить FPS, но также может вызвать проблемы с FPS, поэтому мы >рекомендуем вам проверить это, прежде чем использовать его в соревновательных играх. Он предлагает улучшение FPS за счет установки режима очереди/потока для системы материалов в асинхронный режим очереди. 
>-  -threads - эта опция запуска устанавливает количество потоков процессора, которые будет использовать CS2 (например, -threads 4 заставит CS2 использовать 4 потока). Мы рекомендуем вам не использовать этот вариант запуска, поскольку он может вызвать нестабильность и другие проблемы — в целом CS2 хорошо справляется с управлением использованием потоков.

# Best SETTINGS GRAPHICS
>[!NOTE]
> Используйте настройки как у меня в скриншоте, выставить лучше все на минимальные для наименьшей нагрузки ВИДЕОКАРТЫ, CPU. 
>- Reflex - ENABLED лучшее значение чем либо с бустом. 

![alt text](https://private-user-images.githubusercontent.com/57460269/327420591-642cff5f-863c-455e-80dc-16d45c924844.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2NTM5MDYsIm5iZiI6MTcxNDY1MzYwNiwicGF0aCI6Ii81NzQ2MDI2OS8zMjc0MjA1OTEtNjQyY2ZmNWYtODYzYy00NTVlLTgwZGMtMTZkNDVjOTI0ODQ0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDEyNDAwNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTllMjUzNzRiYWI5MWNjMWIzYjNjM2M3ODkyOTE1OWZhZmEzNGY0MjNmYjA5YzZhNGQwMzI5ZGMyZjFlMGU2MTUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.PIPc21N366srHxr1jNzih5I31dLNZWFRv1FnvR2LLdY)

>[!NOTE]
> Используйте настройки игры как в скриншоте, с минимальным пакетом всегда лучше с [ПАКЕТ-1], он меньше теряет пакеты при плохой лаги стрельбы.

![alt text](https://private-user-images.githubusercontent.com/57460269/327443048-0286b187-a86d-44e3-9229-4ad45e5cbf5d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2NTYxNzMsIm5iZiI6MTcxNDY1NTg3MywicGF0aCI6Ii81NzQ2MDI2OS8zMjc0NDMwNDgtMDI4NmIxODctYTg2ZC00NGUzLTkyMjktNGFkNDVlNWNiZjVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDEzMTc1M1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTI1YjEyYTJmODBiODJlZGI5NDEyZTE5OTIyYzExYjRhMjk1OTNhMzI1NjZkZTNiODI0OGRhY2ZlMjVjZTM2NmEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.HUrWSkpezxkqGgmBOpIM54iaXYmtR-WHGZ2RazlmnG4)

