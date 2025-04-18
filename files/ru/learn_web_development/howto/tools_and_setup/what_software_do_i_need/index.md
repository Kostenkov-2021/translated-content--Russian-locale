---
title: Какое программное обеспечение необходимо для создания веб-сайта?
slug: Learn_web_development/Howto/Tools_and_setup/What_software_do_I_need
---

{{QuicklinksWithSubPages("Learn/Common_questions")}}

В этой статье мы изложим какие программные компоненты вам понадобятся при редактировании, загрузке или просмотре веб-сайта.

| Необходимые знания: | Вы должны уже знать [разницу между веб-страницами, веб-сайтами, веб-серверами и поисковыми системами.](/ru/docs/Learn_web_development/Getting_started/Environment_setup/Browsing_the_web) |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Цель:               | Узнать, какие программные компоненты вам понадобятся при редактировании, загрузке или просмотре веб-сайта.                                                                                |

## Аннотация

Вы можете бесплатно загрузить большинство программ, необходимых для веб-разработки. Мы предоставим несколько ссылок в этой статье. Вам понадобятся инструменты: 1) создания и редактирования веб-страниц, 2) загружать файлы на ваш веб-сервер, 3) просматривать ваш веб-сайт.

Почти все операционные системы по умолчанию включают текстовый редактор и просмоторщик веб-сайтов (называемый браузером). Поэтому обычно вам нужно приобрести лишь программное обеспечение для передачи файлов на ваш веб-сервер.

## Активное изучение

_Пока нет активного обучения._ [Пожалуйста, подумайте о том, чтобы внести свой вклад.](/ru/docs/MDN/Community/Getting_started)

## Копай глубже

### Создание и редактирование веб-страниц

Для создания и редактирования веб-страниц необходим текстовый редактор. Тестовые редакторы создают и изменяют неотформатированные текстовые файлы. (Другие форматы, такие как **{{Glossary("RTF")}}**, позволяют добавить форматирование, такое как полужирное или подчёркивание. Эти форматы не подходят для написания веб-страниц.) вам следует выбирать текстовый редактор с умом, так как вы будете активно работать с ним, при создании веб-сайта.

Все настольные операционные системы поставляются с основным текстовым редактором. Они просты, но не имеют специальных возможностей для кодирования веб-страниц. Если вы хотите что-то более интересное, то доступно много сторонних инструментов. Сторонние редакторы часто поставляются с дополнительными функциями, включая подсветку синтаксиса, автозавершение, сворачиваемые блоки кода и поиск кода. Вот краткий список редакторов:

| Операционная система | Встроенный редактор                                                                                                                                                                                                                        | Сторонний редактор                                                                                                                                                           |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Windows              | [Notepad](http://en.wikipedia.org/wiki/Notepad_%28software%29)                                                                                                                                                                             | [Notepad++](http://notepad-plus-plus.org/)[Visual Studio Code](https://www.visualstudio.com/)[Web Storm](https://www.jetbrains.com/webstorm/)[Brackets](http://brackets.io/) |
| Mac OS               | [TextEdit](http://en.wikipedia.org/wiki/TextEdit)                                                                                                                                                                                          | [TextWrangler](http://www.barebones.com/products/textwrangler/)[Visual Studio Code](https://www.visualstudio.com/)[Brackets](http://brackets.io/)                            |
| Linux                | [Vi](http://en.wikipedia.org/wiki/Vi) (All UNIX) [GEdit](http://en.wikipedia.org/wiki/Gedit) (Gnome) [Kate](http://en.wikipedia.org/wiki/Kate_%28text_editor%29) (KDE) [LeafPad](<http://en.wikipedia.org/wiki/Kate_(text_editor)>) (Xfce) | [Emacs](http://www.gnu.org/software/emacs/) [Vim](http://www.vim.org/)[Visual Studio Code](https://www.visualstudio.com/)[Brackets](http://brackets.io/)                     |

Ниже скриншот продвинутого текстового редактора:

![Screenshot of Notepad++.](notepadplusplus.png)

### Загрузка файлов в Интернете

Когда ваш сайт будет готов для публичного просмотра, вам придётся загрузить свои веб-страницы на веб-сервер. Вы можете купить место на сервере у различных провайдеров (см. [Сколько стоит делать что-то в Интернете?](/ru/docs/Learn_web_development/Howto/Tools_and_setup/How_much_does_it_cost)). После того, как вы решите, какого провайдера использовать, провайдер отправит вам по электронной почте информацию о доступе к протоколу FTP (протокол передачи файлов). Загрузка файлов на веб-сервер является важным шагом при создании сайта, поэтому мы подробно расскажем об этом [в отдельной статье](/ru/docs/Learn_web_development/Howto/Tools_and_setup/Upload_files_to_a_web_server). А сейчас, вот краткий список бесплатных базовых FTP-клиентов:

<table class="standard-table">
  <thead>
    <tr>
      <th scope="col">Операционная система</th>
      <th colspan="2" rowspan="1" scope="col" style="text-align: center">
        Программное обеспечение FTP
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Windows</td>
      <td>
        <p><a href="http://winscp.net" rel="external">WinSCP</a></p>
        <p><a href="http://mobaxterm.mobatek.net/">Moba Xterm</a></p>
      </td>
      <td colspan="1" rowspan="3">
        <a href="https://filezilla-project.org/">FileZilla</a> (All OS)
      </td>
    </tr>
    <tr>
      <td>Linux</td>
      <td>
        <a href="https://live.gnome.org/Nautilus" rel="external">Nautilus</a>
        (Gnome)<br /><a href="http://dolphin.com/" rel="external">Dolphin</a>
        (KDE)
      </td>
    </tr>
    <tr>
      <td>Mac OS</td>
      <td><a href="http://cyberduck.de/">Cyberduck</a></td>
    </tr>
  </tbody>
</table>

### Просмотр веб-сайтов

Как вы уже знаете, вам необходим веб-браузер для просмотра веб-сайтов. Существуют десятки браузеров для вашего личного использования, однако когда вы разрабатываете веб-сайт, вы должны протестировать его, по крайней мере, со следующими основными браузерами, чтобы убедиться, что ваш сайт работает для большинства пользователей:

- [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Google Chrome](https://www.google.fr/chrome/browser/)
- [Apple Safari](https://www.apple.com/safari/)

Если вы ориентируетесь на определённую группу (например, техническую платформу или страну), возможно, вам придётся протестировать ваш сайт с помощью дополнительных браузеров, таких как [Opera](https://www.opera.com/) и [Konqueror](https://www.konqueror.org/).

Но тестирование усложняется, потому что некоторые браузеры работают только в определённых операционных системах. Apple Safari работает на iOS и Mac OS, а Internet Explorer работает только в Windows. Поэтому лучше воспользоваться такими сервисами, как [Browsershots](http://browsershots.org/) или [Browserstack](http://www.browserstack.com/). Browsershots предоставляет скриншоты вашего сайта, того как ваш сайт будет выглядеть в различных браузерах. Browserstack фактически предоставляет вам полный удалённый доступ к виртуальным машинам, поэтому вы можете протестировать ваш сайт в наиболее распространённых средах. Кроме того, вы можете настроить свою собственную виртуальную машину, но это требует некоторого опыта. Более подробную информацию можно найти в статье о [стратегиях тестирования](/ru/docs/Learn/Tools_and_testing/Cross_browser_testing/Testing_strategies#putting_together_a_testing_lab).

Обязательно проведите тестирование на реальном устройстве, особенно на реальных мобильных устройствах. Симуляция мобильных устройств - это новая, развивающаяся технология и менее надёжна, чем симуляция настольных устройств. Разумеется, мобильные устройства стоят денег, поэтому мы предлагаем взглянуть на [Open Device Lab initiative](http://opendevicelab.com/). Вы также можете обмениваться устройствами, если вы хотите протестировать на многих платформах, не тратя слишком много.

## Следующие шаги

- Некоторые из перечисленных программ бесплатны, но не все. [Узнайте, сколько стоит сделать что-то в Интернете.](/ru/docs/Learn_web_development/Howto/Tools_and_setup/How_much_does_it_cost)
- Если вы хотите больше узнать о текстовых редакторах, прочитайте нашу статью о том [как выбрать и установить текстовый редактор](/ru/docs/Learn_web_development/Howto/Tools_and_setup/Available_text_editors).
- Если вам интересно, как опубликовать ваш веб-сайт в Интернете, посмотрите статью ["Как загрузить файлы на веб-сервер"](/ru/docs/Learn_web_development/Howto/Tools_and_setup/Upload_files_to_a_web_server).
