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

-----Generating Page Elements

* P.67 `01_empty_page_template.html`
* P.70 `02_new_element.html` ...*step through code*

-----Binding Data

* P.74 `03_csv_loading_example.html`
* P.79 `04_creating_paragraphs.html` ...*step through code*
* P.84 `05_creating_paragraphs_text.html` ...*anonymous function*
* P.85 `06_creating_paragraphs_counting.html`
* P.86 `07_creating_paragraphs_with_style.html`
* P.87 `08_creating_paragraphs_with_style_functions.html`


**06 Drawing with Data** [P.89-115]

-----Drawing divs

* P.91 `01_drawing_divs.html`
* P.92 `02_drawing_divs_height.html`
* P.93 `03_drawing_divs_spaced.html`

-----The power of `data()`

* P.93 `04_power_of_data.html`
* P.93 `05_power_of_data_more_points.html`
* P.94 `06_power_of_data_random.html` ...*(step through code)*
* P.97 `07_power_of_data_rounded.html`

-----Drawing SVGs

* P.98 `08_drawing_svgs.html`
* P.98 `09_drawing_svgs_size.html`
* P.99 `10_drawing_svgs_circles.html` ...*step through code*
* P.100 `11_drawing_svgs_color.html`

-----Making a Bar Chart

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

-----Making a Scatterplot

* P.111 `22_scatterplot.html`
* P.113 `23_scatterplot_sqrt.html` ...*encoding the values as area*
* P.115 `24_scatterplot_labels.html`

-----Next Steps


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

-----Modernizing the Bar Chart

* P.149 `01_bar_chart.html`
* P.150 `02_bar_chart_with_scales.html` ...*step through code*

-----Updating Data

* P.156 `03_updates_all_data.html`
* P.158 `04_updates_all_data_fixed.html`

-----Transitions

* P.159 `05_transition.html`
* P.160 `06_duration.html`
* P.160 `07_duration_slow.html`
* P.161 `08_duration_slow_labels_fixed.html`
* P.161 `09_ease_linear.html`
* P.162 `10_ease_circle.html`
* P.162 `11_ease_elastic.html`
* P.162 `12_ease_bounce.html`
* P.162 `13_delay_static.html`
* P.163 `14_delay_dynamic.html`
* P.163 `15_delay_dynamic_scaled.html`
* P.163 `16_delay_dynamic_scaled_fewer.html`
* P.164 `17_randomized_data.html`
* P.168 `18_dynamic_scale.html`
* P.169 `19_axes_static.html`
* P.171 `20_axes_dynamic.html`
* P.171 `21_on.html`
* P.173 `22_on_combo_transition.html`
* P.174 `23_chained_transitions.html`
* P.176 `24_clip-path.html`

-----Other Kinds of Data Updates

* P.181 `25_adding_values.html`
* P.184 `26_removing_values.html`
* P.189 `27_data_join_with_key.html`
* P.193 `28_adding_and_removing.html`
* P.193 `29_dynamic_labels.html`

-----RECAP

* `data()` binds data to elements, but also returns the *update selection*.
* The update selection can contain *enter* and *exit* selections, which can be accessed via `enter()` and `exit()`.
* `merge()` is typically used to, well, merge the enter and update selections, to make it easy to apply any changes to both of those selections at the same time.
* When there are *more values than elements*, an enter selection will reference the placeholder, not-yet-existing elements.
* When there are *more elements than values*, an exit selection will reference the ele‐ ments without data.
* Data joins determine how values are matched with elements.
* By default, data joins are performed by index, meaning in order of appearance.
* For more control over data joins, you can specify a key function.


10 **Interactivity** [P.195-215]

-----Binding Event Listeners

-----Introducing Behaviors

* P.196 `01_start.html`
* P.197 `02_click.html`
* P.197 `03_hover.html`
* P.199 `04_mouseover.html`
* P.199 `05_mouseout.html`
* P.201 `06_smoother.html`

-----Grouping SVG Elements

* P.204 `07_sort.html` ...*"call a new function of our own creation, `sortBars()`"*
* P.205 `08_sort_hover.html`
* P.207 `09_resort.html`
* P.207 `10_delay.html`

-----Tooltips

* P.208 `11_browser_tooltip.html`
* P.209 `12_browser_tooltip_text.html`
* P.210 `13_svg_tooltip.html`
* P.212 `14_div_tooltip.html`

-----Consideration for Touch Devices

-----Moving Forward

*"You now have all the basics of D3 under your cap. You are a pro at binding data, generating and styling elements based on that data, implementing scales and drawing axes, and modifying your creations with new data, animated transitions, and interactivity. What more could you ask for?*

*How about expanding your visual possibilities with paths, layouts, and geomaps? The next few chapters will dive into these slightly more advanced topics"*


11

12

13

14

15

16