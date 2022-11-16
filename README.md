# Звіт до роботи №4
## Тема: _Віртуальні середовища_
### Мета роботи: _Навчитись працювати з віртуальними середовищами_
---
### Виконання роботи

- Результати виконання завдання *N1*;
- ![4laba1](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8%20%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D0%B8%20%D0%B7%20%D1%81%D1%82%D0%BE%D1%80%D0%BE%D0%BD%D0%BD%D1%96%D0%BC%D0%B8%20%D0%B1%D1%96%D0%B1%D0%BB%D1%96%D0%BE%D1%82%D0%B5%D0%BA%D0%B0%D0%BC%D0%B8%201.png?raw=true)
- ![4laba2](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8%20%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D0%B8%20%D0%B7%20%D1%81%D1%82%D0%BE%D1%80%D0%BE%D0%BD%D0%BD%D1%96%D0%BC%D0%B8%20%D0%B1%D1%96%D0%B1%D0%BB%D1%96%D0%BE%D1%82%D0%B5%D0%BA%D0%B0%D0%BC%D0%B8%202.png?raw=true)
- ![4laba3](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8%20%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D0%B8%20%D0%B7%20%D1%81%D1%82%D0%BE%D1%80%D0%BE%D0%BD%D0%BD%D1%96%D0%BC%D0%B8%20%D0%B1%D1%96%D0%B1%D0%BB%D1%96%D0%BE%D1%82%D0%B5%D0%BA%D0%B0%D0%BC%D0%B8%203.png?raw=true)
- ![4laba4](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8%20%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D0%B8%20%D0%B7%20%D1%81%D1%82%D0%BE%D1%80%D0%BE%D0%BD%D0%BD%D1%96%D0%BC%D0%B8%20%D0%B1%D1%96%D0%B1%D0%BB%D1%96%D0%BE%D1%82%D0%B5%D0%BA%D0%B0%D0%BC%D0%B8%204.png?raw=true)
- ![4laba5](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8%20%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D0%B8%20%D0%B7%20%D1%81%D1%82%D0%BE%D1%80%D0%BE%D0%BD%D0%BD%D1%96%D0%BC%D0%B8%20%D0%B1%D1%96%D0%B1%D0%BB%D1%96%D0%BE%D1%82%D0%B5%D0%BA%D0%B0%D0%BC%D0%B8%205.png?raw=true)

- Результати виконання завдання *N2*;
- ![4laba6](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%A0%D0%BE%D0%B1%D0%BE%D1%82%D0%B0%20%D1%83%20%D0%B2%D1%96%D1%80%D1%82%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%BC%D1%83%20%D1%81%D0%B5%D1%80%D0%B5%D0%B4%D0%BE%D0%B2%D0%B8%D1%89%D1%96.png?raw=true)

- Результати виконання завдання *N3*;
- ![4laba7](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%A0%D0%BE%D0%B1%D0%BE%D1%82%D0%B0%20%D0%B7%20Pipenv%201.png?raw=true)
- ![4laba8](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%A0%D0%BE%D0%B1%D0%BE%D1%82%D0%B0%20%D0%B7%20Pipenv%202.png?raw=true)
- ![4laba9](https://github.com/DmytroHimzaITCollege/3_laba_3/blob/main/%D0%A0%D0%BE%D0%B1%D0%BE%D1%82%D0%B0%20%D0%B7%20Pipenv%203.png?raw=true)

Запустив даний код:
   ```python
         import requests

   response = requests.get('https://httpbin.org/')
   for line in response.iter_lines():
      print(line)
   ```
Результат коду в терміналі:
   ```
      Output exceeds the size limit. Open the full output data in a text editor
   b'<!DOCTYPE html>'
   b'<html lang="en">'
   b''
   b'<head>'
   b'    <meta charset="UTF-8">'
   b'    <title>httpbin.org</title>'
   b'    <link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700|Source+Code+Pro:300,600|Titillium+Web:400,600,700"'
   b'        rel="stylesheet">'
   b'    <link rel="stylesheet" type="text/css" href="/flasgger_static/swagger-ui.css">'
   b'    <link rel="icon" type="image/png" href="/static/favicon.ico" sizes="64x64 32x32 16x16" />'
   b'    <style>'
   b'        html {'
   b'            box-sizing: border-box;'
   b'            overflow: -moz-scrollbars-vertical;'
   b'            overflow-y: scroll;'
   b'        }'
   b''
   b'        *,'
   b'        *:before,'
   b'        *:after {'
   b'            box-sizing: inherit;'
   b'        }'
   b''
   b'        body {'
   b'            margin: 0;'
   ...
   b'</div>'
   b'</body>'
   b''
   b'</html>'
   ```

- результати виконання завдання *N4*;
Запустив даний код:
   ```python
   import os
   os.environ['HELLO']
   ```
Результат коду в терміналі:
   ```
      ---------------------------------------------------------------------------
   KeyError                                  Traceback (most recent call last)
   Cell In [3], line 2
         1 import os
   ----> 2 os.environ['HELLO']

   File <frozen os>:678, in __getitem__(self, key)

   KeyError: 'HELLO'
   ```
   
+ Виконав індивідуальні завдання для кождного пункту.
### Висновок: 
> у висновку потрібно відповісти на запитання:
- :question: Що зроблено в роботі - Проведенно роботу з віртуальними середовищами;
- :question: Чи досягнуто мети роботи - Так, досягнуто;
- :question: Які нові знання отримано - знання про роботу з віртуальними середовищами;
- :question: Чи вдалось відповісти на всі питання задані в ході роботи - Ні.;
- :question: Чи вдалося виконати всі завдання - Ні.;
- :question: Чи виникли складності у виконанні завдання - Так.;
- :question: Чи подобається такий формат здачі роботи (Feedback)- Так.;
- :question: Побажання для покращення (Suggestions) - Немає побажань;
---# -
