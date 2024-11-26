# Basic alignment algorithms and mapping: description and implementation

# Выравнивание (alignment)

*Сопоставления двух или более последовательностей для выявления сходств и различий между ними*

- **Глобальное выравнивание**
  - [**Алгоритм Нидлмана-Вунша**](#алгоритм-нидлмана-вунша)

- **Локальное выравнивание**
  - [**Алгоритм Смита-Ватермана**](#проект-2-why-did-i-get-the-flu-deep-sequencing-error-control-p-value-viral-evolution)
  - [**Blast**](#проект-1-what-causes-abtibiotic-resistance)

- **Множественное выравнивание**
  - [**Clustal**](#проект-2-why-did-i-get-the-flu-deep-sequencing-error-control-p-value-viral-evolution)
  - [**MUSCLE**](#проект-2-why-did-i-get-the-flu-deep-sequencing-error-control-p-value-viral-evolution)
  - [**T-Coffee**](#проект-2-why-did-i-get-the-flu-deep-sequencing-error-control-p-value-viral-evolution)

- **Выравнивание белков**
  - [**PAM**]
  - [**BLOSUM**]
 
# Картирование (mapping)

*Cопоставление коротких ридов (последовательностей) к референсному геному или транскриптому*

- [**BWA (Burrows-Wheeler Aligner)**]
- [**STAR (Spliced Transcripts Alignment to a Reference)**]
- [**HISAT2**]
- [**Псевдовыравнивание kallisto**]

##  Алгоритм Нидлмана-Вунша


Источники: https://lectures.biophys.msu.ru/MMB_2015/lecture17.pdf, https://teach-in.ru/file/presentation/pdf/transcriptome-data-analysis-M-2.pdf
