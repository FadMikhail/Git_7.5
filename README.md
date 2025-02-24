# Домашнее задание к занятию "7.5_Git Фадеев Михаил"


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

Задание 1
Что нужно сделать:

1. Зарегистрируйте аккаунт на GitHub.

![image](https://user-images.githubusercontent.com/132131230/235297128-5c6b2c31-fbe9-4393-b0b2-438e72cb9058.png)

2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».

![image](https://user-images.githubusercontent.com/132131230/235297179-ae9ce883-bb00-47b8-829f-9aa561fc2729.png)

3. Склонируйте репозиторий, используя https протокол git clone ....

![image](https://user-images.githubusercontent.com/132131230/235297440-f704ddca-f6c1-47c7-9660-6b182f76ac59.png)

4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.

![image](https://user-images.githubusercontent.com/132131230/235297483-9e1634d7-191d-4372-af37-795e9179fcd2.png)

6. Выполните команду git status и запомните результат.

![image](https://user-images.githubusercontent.com/132131230/235297513-7e91e7bc-ec11-482b-a5d6-e8475b2aae6b.png)

7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.

![image](https://user-images.githubusercontent.com/132131230/235297574-c076737b-c752-4189-b69e-aeab1728f08b.png)

8. Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.

![image](https://user-images.githubusercontent.com/132131230/235297586-1154c0d5-392c-4e98-8780-0dd8630f1a4a.png)

9. Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.

![image](https://user-images.githubusercontent.com/132131230/235297607-679928b4-89a1-4eb0-b109-3d07e301343c.png)

10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.

![image](https://user-images.githubusercontent.com/132131230/235297622-00c77c82-1035-4e5f-9dc9-58b5ae231944.png)

12. Ещё раз выполните команды git diff и git diff --staged.

![image](https://user-images.githubusercontent.com/132131230/235297643-6e725219-c438-44bc-a179-af246b9edd01.png)

14. Теперь можно сделать коммит git commit -m 'First commit'.

![image](https://user-images.githubusercontent.com/132131230/235297676-943b50bd-fb8c-49ad-a6de-fd35e2e23fa7.png)

16. Сделайте git push origin master.

![image](https://user-images.githubusercontent.com/132131230/235297702-582007cd-8360-45a3-ad76-1aae3d3c37fb.png)

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/FadMikhail/first.git

https://github.com/FadMikhail/first/commit/15a666c90ef04a9e59173ea15c2e36831642e67a




---

### Задание 2

Что нужно сделать:

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.

![image](https://user-images.githubusercontent.com/132131230/235299123-04785a48-143c-488f-bcf0-bcbd4458862b.png)

2. Добавьте файл .gitignore в следующий коммит git add....

![image](https://user-images.githubusercontent.com/132131230/235299232-a3e72e22-9371-4812-bfad-b97560b99c4c.png)

3. Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.

![image](https://user-images.githubusercontent.com/132131230/235299367-56b63ba4-e47e-40b5-92a8-e766e8b5f34c.png)

4. Сделайте коммит и пуш.

![image](https://user-images.githubusercontent.com/132131230/235299469-b0a2e763-75cc-47cc-a77c-3c9fbb49b6ce.png)

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/FadMikhail/first.git

https://github.com/FadMikhail/first/commit/6c6ddacb9382c5c91a5c775e0faa14c8816f83e7



---

### Задание 3

Что нужно сделать:

1. Создайте новую ветку dev и переключитесь на неё.

![image](https://user-images.githubusercontent.com/132131230/235299759-99178a29-8b34-4bf4-b5ce-302e5a89905d.png)

2. Создайте файл test.sh с произвольным содержимым.

![image](https://user-images.githubusercontent.com/132131230/235299974-a6ae747d-d13f-4243-bee7-6599fe4ea956.png)

3. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.

![image](https://user-images.githubusercontent.com/132131230/235301477-67ed19d1-a51e-4f1f-8ae7-930af382fad2.png)

4. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать git merge.

![image](https://user-images.githubusercontent.com/132131230/235300568-32d86134-2225-4bf5-9b2f-a66d4c7daa98.png)

5.  Сделайте коммит и пуш.

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

https://github.com/FadMikhail/first/network


