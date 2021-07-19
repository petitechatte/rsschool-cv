# Natalya Kot

## Job objective

**Junior frontend developer**

## Personal information

I am looking a job or a traineeship as a frontend developer. I have already finished several frontend training courses as well as QA training course. In July, 2021 I began studing at RS School.

Also I have an extensive experience of self-education. I am keen on knowledge and information, therefore learning through the whole life is one of my main principles.

## Professional skills

- **HTML**: valid, semantic code conforming to the actual specification; accessibility; BEM;
- **CSS**: adaptive layouts, flexbox, grid, cross-browser compatibility, resistance to content overflow, animation, transitions, filters;
- **SCSS**;
- **JS**: events, form validation, templates, XMLHttpRequest, canvas;
- **English**: Intermediate;
- **other skills**: Git; Photoshop, Figma, Zepplin; Gulp; site hosting.

## Example JavaScript code

```if (text) {
      var hashtags = text.split(' ');
      hashtags = removeEmptyStrings(hashtags);

      if (hashtags.length > HASHTAGS_LIMIT) {
        errorMessage = 'Нельзя указывать больше пяти хэш-тегов';
      } else {
        hashtags.forEach(function (hashtag, i, words) {
          hashtagSymbols = hashtag.split('#');

          if (hashtagSymbols.length > 2) {
            errorMessage = 'Хэш-теги должны разделяться пробелами';
          } else if (hashtag.indexOf('#') !== 0) {
            errorMessage = 'Хэш-тег должен начинаться с символа #';
          } else if (hashtag.length < MIN_HASHTAG_LENGTH) {
            errorMessage = 'Хеш-тег не может состоять только из одной решётки';
          } else if (hashtag.length > MAX_HASHTAG_LENGTH) {
            errorMessage = 'Максимальная длина одного хэш-тега 20 символов, включая решётку';
          } else {
            for (var j = i + 1; j < words.length; j++) {
              if (words[j] === words[i]) {
                errorMessage = 'Один и тот же хэш-тег не может быть использован дважды';
              }
            }
          }
        });
      }
    }
```

## Education

1. Software Testing Engineer (IT-Academy)
2. HTML&CSS, Basic course ([HTML Academy](https://assets.htmlacademy.ru/certificates/intensive/26/209725.pdf?1475905684))
3. HTML&CSS, Advanced course ([HTML Academy](https://assets.htmlacademy.ru/certificates/intensive/47/209725.pdf?1509273486))
4. Professional JavaScript, level 1 ([HTMLAcademy](https://assets.htmlacademy.ru/certificates/intensive/121/209725.pdf?1575480068))

## Contacts

- [email](natalyavaskot@gmail.com)
- [github](https://github.com/petitechatte)
- [web-site](http://htmlkot.ru)
