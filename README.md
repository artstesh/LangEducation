# LangEducation
  Андройд-приложение, призванное помочь в изучении иностранных языков методом Шлимана. Суть занятий сводится к
выучиванию текста по принципу "снежного кома": сначала мы запоминаем n слов, потом 2n, далее 3n и т.д.
  В приложении организован перевод слов с английского языка в двух вариантах: из встроенной базы и посредтством переводчика
Яндекс. В настоящее время у проекта нет коммерческих притязаний, а потому перевод с Яндекса организован через личный ключ.
В файлах ГИТа ключ опущен, так что перевод по сети работать не будет, пока вы не введете свой ключ в соответствующее поле.
  В настоящее время в приложении не написано распараллеливание потоков при создании базы, что приводит к "подвисанию" устройства
~1 минуту (до введения транзакций время и вовсе сотавляло 10 минут:).
