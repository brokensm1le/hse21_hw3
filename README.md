# hse21_hw3

*Ссылка на GoogleColab(part 1: create_table):* https://colab.research.google.com/drive/1phW0XygZCeXhR_q3Qq4UK2UToE4UH_An?usp=sharing

## Часть 1

### Статистика из MultiQC
<img src="/pic/genestat.png"/>

<p float="left">
  <img src="/pic/fastqc_sequence_counts_plot.png " width="400" />
  <img src="/pic/fastqc_per_base_sequence_quality_plot.png" width="400" />
  <img src="/pic/fastqc_per_sequence_gc_content_plot.png" width="400" /> 
  <img src="/pic/fastqc_per_sequence_quality_scores_plot.png" width="400" />
  <img src="/pic/fastqc_sequence_duplication_levels_plot.png" width="400" />
</p>

### Далее делаем hisat(Итог в папке hisat)

### Считаем кол-во уникально-картированных чтений
<img src="/pic/count_uniq.png">

### Делаем htseq и смотрим на статистику
<img src="/pic/stat.png">

### И считаем общее кол-во чтений, которые попали на гены
<img src="/pic/all_count.png">

## Часть 2
*Ссылка на GoogleCola(part 2: DESeq):* https://colab.research.google.com/drive/174aQET9h9qfX1d2BlBC1_sDz0-FJ09kn?usp=sharing


### plotMA
<img src="/pic/plotMA.png">

### HeatMap
<img src="/pic/heatmap.png">

### Графики со значениями "Normalized counts" в контрольных и перепрограммированных образцах
<p float="left">
  <img src="/pic/g1.png " width="500" />
  <img src="/pic/g2.png" width="500" />
  <img src="/pic/g3.png" width="500" /> 
</p>
