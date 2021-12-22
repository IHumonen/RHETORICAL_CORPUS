Many natural language processing tasks, such as generating or summarizing text, include
recognizing relationships between parts of text and establishing a hierarchy of those parts.
The annotation of texts according to the rhetorical structures theory (RST) allows obtaining
such data, but it requires a lot of resources. The aim of this work is to create an annotated
parallel Russian-English corpus. To do this, we considered the English texts marked with
RST and their Russian translations, conducting experiments to improve the existing Russian
parser, as well as to transfer annotation from English using automatic mapping. During our
work, we modified the division into elementary discursive units so that our segmentation
would sufficiently correspond to the English one and developed a gold segmentation standard
for a collection of texts, adapted the annotation instruction on rhetorical relations. After
analysing the performance of the parsers, we made several conclusions regarding the types of
errors and the differences between two languages.
https://drive.google.com/file/d/1GoGGJI2fLA2tVnlmUo3GvXyC9Sv_GzLy/view

В этом репозитории лежит всякий код и результаты работы русского авторазметчика (и будут лежать новые rst-файлы), <code>[тут](https://github.com/PolinaGusenkova/arg-microtexts-multilayer-eng-rus)
</code> лежит английский корпус, а <code>[тут](https://github.com/tchewik/isanlp_rst)
</code> -- авторазметчик для русского языка, которым мы пользовались.
