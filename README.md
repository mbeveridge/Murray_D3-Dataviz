# Interactive Data Visualization for the Web
#### An Introduction to Designing with D3
###### Scott Murray

---

[Page xiv] Publisher's [web page for this book](http://shop.oreilly.com/product/0636920037316.do), including [errata](https://www.oreilly.com/catalog/errata.csp?isbn=0636920037316)

[Page xiv] Author's [companion website](https://alignedleft.com/work/d3-book-2e)

[Chapter4] [localhost:8888](http://localhost:8888/d3-book-2.0.3/) link (to sample files) for me, when local web server is running


| Directory or file (in root) | Explanation |
| --- | --- |
| d3/ | [Chapter4] Latest version (5.9.2) of d3.js, from [https://d3js.org](https://d3js.org) |
|d3-book-2.0.3/ | [Chapter1] Latest version (2.0.3) of sample files, from [the GitHub releases page](https://github.com/alignedleft/d3-book/releases) |
|d3.js | [Chapter4] Library actually being used. Copy of a file in `d3/` |
| index.html | [Chapter4] Empty document |
| README.md | This document |

---

**01 Introduction** [P.1-6]

**02 Introducing D3** [P.7-16] ...[*P.11-16 Other libraries*]

**03 Technology Fundamentals** [P.17-62] ...[**P37-42 Objects & Arrays : to read**]

**04 Setup** [P.63-66] ...[*P.65 Set up a web server (type in Terminal) : `python -m http.server 8888 &.`*]

**05 Data** [P.67-87] ...[**P73-78 Loading CSV & JSON : to read** ...but Errata says this method doesn't work for v5 D3]

* P.67 `01_empty_page_template.html`
* P.70 `02_new_element.html` ...*step through code*
* P.74 `03_csv_loading_example.html`
* P.79 `04_creating_paragraphs.html` ...*step through code*
* P.84 `05_creating_paragraphs_text.html` ...*anonymous function*
* P.85 `06_creating_paragraphs_counting.html`
* P.86 `07_creating_paragraphs_with_style.html`
* P.87 `08_creating_paragraphs_with_style_functions.html`


**06 Drawing with Data** [P.89-115]

* P.91 `01_drawing_divs.html`
* P.92 `02_drawing_divs_height.html`
* P.93 `03_drawing_divs_spaced.html`
* P.93 `04_power_of_data.html`
* P.93 `05_power_of_data_more_points.html`
* P.94 `06_power_of_data_random.html` ...*(step through code)*
* P.97 `07_power_of_data_rounded.html`
* P.98 `08_drawing_svgs.html`
* P.98 `09_drawing_svgs_size.html`
* P.99 `10_drawing_svgs_circles.html` ...*step through code*
* P.100 `11_drawing_svgs_color.html`
* P.101 `12_making_a_bar_chart_divs.html`
* P.102 `13_making_a_bar_chart_rects.html` ...*using SVG instead of div*
* P.103 `14_making_a_bar_chart_offset.html`
* P.104 `15_making_a_bar_chart_even.html`
* P.104 `16_making_a_bar_chart_widths.html`
* P.106 `17_making_a_bar_chart_heights.html`
* P.107 `18_making_a_bar_chart_teal.html`
* P.107 `19_making_a_bar_chart_blues.html`
* P.109 `20_making_a_bar_chart_labels.html`
* P.110 `21_making_a_bar_chart_aligned.html`
* P.111 `22_scatterplot.html`
* P.113 `23_scatterplot_sqrt.html` ...*encoding the values as area*
* P.115 `24_scatterplot_labels.html`


**07 Scales** [P.117-134]

* P.119 `01_scale_test.html`
* P.123 `02_scaled_plot.html`
* P.123 `03_scaled_plot_inverted.html`
* P.125 `04_scaled_plot_padding.html`
* P.125 `05_scaled_plot_radii.html`
* P.125 `06_scaled_plot_big.html`
* P.126 `07_scaled_plot_large.html`
* P.129 `08_scaled_plot_sqrt_scale.html`
* P.131 `09_time_scale.html`


**08 Axes** [P.135-148]

* P.137 `01_axes.html`
* P.139 `02_axes_bottom.html`
* P.141 `03_axes_clean.html`
* P.143 `04_axes_y.html`
* P.145 `05_axes_random.html`
* P.145 `06_axes_no_labels.html`
* P.146 `07_axes_format.html`
* P.147 `08_time_axis.html`
* P.147 `09_time_axis_prettier.html`


**09 Updates, Transitions, and Motion** [P.149-194]

01_bar_chart.html
02_bar_chart_with_scales.html
03_updates_all_data.html
04_updates_all_data_fixed.html
05_transition.html
06_duration.html
07_duration_slow.html
08_duration_slow_labels_fixed.html
09_ease_linear.html
10_ease_circle.html
11_ease_elastic.html
12_ease_bounce.html
13_delay_static.html
14_delay_dynamic.html
15_delay_dynamic_scaled.html
16_delay_dynamic_scaled_fewer.html
17_randomized_data.html
18_dynamic_scale.html
19_axes_static.html
20_axes_dynamic.html
21_on.html
22_on_combo_transition.html
23_chained_transitions.html
24_clip-path.html
25_adding_values.html
26_removing_values.html
27_data_join_with_key.html
28_adding_and_removing.html
29_dynamic_labels.html


10

11

12

13

14

15

16