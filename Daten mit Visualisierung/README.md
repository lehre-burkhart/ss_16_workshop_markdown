    first_colour <- "#684F91"

    cars <- read.csv("data/cars.csv", sep = ",")

    knitr::kable(cars)

<table>
<thead>
<tr class="header">
<th align="right">X</th>
<th align="right">speed</th>
<th align="right">dist</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="right">1</td>
<td align="right">4</td>
<td align="right">2</td>
</tr>
<tr class="even">
<td align="right">2</td>
<td align="right">4</td>
<td align="right">10</td>
</tr>
<tr class="odd">
<td align="right">3</td>
<td align="right">7</td>
<td align="right">4</td>
</tr>
<tr class="even">
<td align="right">4</td>
<td align="right">7</td>
<td align="right">22</td>
</tr>
<tr class="odd">
<td align="right">5</td>
<td align="right">8</td>
<td align="right">16</td>
</tr>
<tr class="even">
<td align="right">6</td>
<td align="right">9</td>
<td align="right">10</td>
</tr>
<tr class="odd">
<td align="right">7</td>
<td align="right">10</td>
<td align="right">18</td>
</tr>
<tr class="even">
<td align="right">8</td>
<td align="right">10</td>
<td align="right">26</td>
</tr>
<tr class="odd">
<td align="right">9</td>
<td align="right">10</td>
<td align="right">34</td>
</tr>
<tr class="even">
<td align="right">10</td>
<td align="right">11</td>
<td align="right">17</td>
</tr>
<tr class="odd">
<td align="right">11</td>
<td align="right">11</td>
<td align="right">28</td>
</tr>
<tr class="even">
<td align="right">12</td>
<td align="right">12</td>
<td align="right">14</td>
</tr>
<tr class="odd">
<td align="right">13</td>
<td align="right">12</td>
<td align="right">20</td>
</tr>
<tr class="even">
<td align="right">14</td>
<td align="right">12</td>
<td align="right">24</td>
</tr>
<tr class="odd">
<td align="right">15</td>
<td align="right">12</td>
<td align="right">28</td>
</tr>
<tr class="even">
<td align="right">16</td>
<td align="right">13</td>
<td align="right">26</td>
</tr>
<tr class="odd">
<td align="right">17</td>
<td align="right">13</td>
<td align="right">34</td>
</tr>
<tr class="even">
<td align="right">18</td>
<td align="right">13</td>
<td align="right">34</td>
</tr>
<tr class="odd">
<td align="right">19</td>
<td align="right">13</td>
<td align="right">46</td>
</tr>
<tr class="even">
<td align="right">20</td>
<td align="right">14</td>
<td align="right">26</td>
</tr>
<tr class="odd">
<td align="right">21</td>
<td align="right">14</td>
<td align="right">36</td>
</tr>
<tr class="even">
<td align="right">22</td>
<td align="right">14</td>
<td align="right">60</td>
</tr>
<tr class="odd">
<td align="right">23</td>
<td align="right">14</td>
<td align="right">80</td>
</tr>
<tr class="even">
<td align="right">24</td>
<td align="right">15</td>
<td align="right">20</td>
</tr>
<tr class="odd">
<td align="right">25</td>
<td align="right">15</td>
<td align="right">26</td>
</tr>
<tr class="even">
<td align="right">26</td>
<td align="right">15</td>
<td align="right">54</td>
</tr>
<tr class="odd">
<td align="right">27</td>
<td align="right">16</td>
<td align="right">32</td>
</tr>
<tr class="even">
<td align="right">28</td>
<td align="right">16</td>
<td align="right">40</td>
</tr>
<tr class="odd">
<td align="right">29</td>
<td align="right">17</td>
<td align="right">32</td>
</tr>
<tr class="even">
<td align="right">30</td>
<td align="right">17</td>
<td align="right">40</td>
</tr>
<tr class="odd">
<td align="right">31</td>
<td align="right">17</td>
<td align="right">50</td>
</tr>
<tr class="even">
<td align="right">32</td>
<td align="right">18</td>
<td align="right">42</td>
</tr>
<tr class="odd">
<td align="right">33</td>
<td align="right">18</td>
<td align="right">56</td>
</tr>
<tr class="even">
<td align="right">34</td>
<td align="right">18</td>
<td align="right">76</td>
</tr>
<tr class="odd">
<td align="right">35</td>
<td align="right">18</td>
<td align="right">84</td>
</tr>
<tr class="even">
<td align="right">36</td>
<td align="right">19</td>
<td align="right">36</td>
</tr>
<tr class="odd">
<td align="right">37</td>
<td align="right">19</td>
<td align="right">46</td>
</tr>
<tr class="even">
<td align="right">38</td>
<td align="right">19</td>
<td align="right">68</td>
</tr>
<tr class="odd">
<td align="right">39</td>
<td align="right">20</td>
<td align="right">32</td>
</tr>
<tr class="even">
<td align="right">40</td>
<td align="right">20</td>
<td align="right">48</td>
</tr>
<tr class="odd">
<td align="right">41</td>
<td align="right">20</td>
<td align="right">52</td>
</tr>
<tr class="even">
<td align="right">42</td>
<td align="right">20</td>
<td align="right">56</td>
</tr>
<tr class="odd">
<td align="right">43</td>
<td align="right">20</td>
<td align="right">64</td>
</tr>
<tr class="even">
<td align="right">44</td>
<td align="right">22</td>
<td align="right">66</td>
</tr>
<tr class="odd">
<td align="right">45</td>
<td align="right">23</td>
<td align="right">54</td>
</tr>
<tr class="even">
<td align="right">46</td>
<td align="right">24</td>
<td align="right">70</td>
</tr>
<tr class="odd">
<td align="right">47</td>
<td align="right">24</td>
<td align="right">92</td>
</tr>
<tr class="even">
<td align="right">48</td>
<td align="right">24</td>
<td align="right">93</td>
</tr>
<tr class="odd">
<td align="right">49</td>
<td align="right">24</td>
<td align="right">120</td>
</tr>
<tr class="even">
<td align="right">50</td>
<td align="right">25</td>
<td align="right">85</td>
</tr>
<tr class="odd">
<td align="right">```</td>
<td align="right"></td>
<td align="right"></td>
</tr>
</tbody>
</table>

    ggplot(cars, aes(x = speed, y = dist)) +
      geom_point(size = 2) +
      geom_smooth(method = lm, se = TRUE, colour = first_colour)

![](README_files/figure-markdown_strict/Display%20relationship-1.png)
