# Blind cave
> Хозяйка Медной горы спрятала в малахитовой шкатулке ключ. От чего... Хм... что же она пытается скрыть?

## Решение
> Флаг: m3ny4_v53_z4dr4l0
> 1. steghide extract -sf hide.jpg
> Использовать password 1. Подсказка на пароль в условии (надо обратиться к таску на крипту) 
> 2. Там файлик,в котором в base32 строка. Ее декодируем, потом из брайля и получаем пароль.
> 3. Вытаскиваем из второго архива с помощью пароля файлик, в котором записан флаг в base32, который декодируем и вуаля.
