.. _eu.gmic.Lavalamp:

G’MIC Lava lamp node
====================

*This documentation is for version 0.3 of G’MIC Lava lamp.*

Description
-----------

Author: David Tschumperle. Latest update: 2011/06/07.

Wrapper for the G’MIC framework (http://gmic.eu) written by Tobias Fleischer (http://www.reduxfx.com).

Inputs
------

+-------+-------------+----------+
| Input | Description | Optional |
+=======+=============+==========+
| Input |             | No       |
+-------+-------------+----------+

Controls
--------

.. tabularcolumns:: |>{\raggedright}p{0.2\columnwidth}|>{\raggedright}p{0.06\columnwidth}|>{\raggedright}p{0.07\columnwidth}|p{0.63\columnwidth}|

.. cssclass:: longtable

+-----------------------------------------------------+---------+---------+-----------------------+
| Parameter / script name                             | Type    | Default | Function              |
+=====================================================+=========+=========+=======================+
| Number of key-frames / ``Number_of_keyframes``      | Integer | 3       |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Number of inter-frames / ``Number_of_interframes``  | Integer | 30      |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Smooth looping / ``Smooth_looping``                 | Boolean | On      |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Resolution / ``Resolution``                         | Double  | 20      |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Size / ``Size``                                     | Double  | 2       |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Smoothness / ``Smoothness``                         | Double  | 0.01    |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Transparent background / ``Transparent_background`` | Boolean | Off     |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Output Layer / ``Output_Layer``                     | Choice  | Layer 0 | |                     |
|                                                     |         |         | | **Merged**          |
|                                                     |         |         | | **Layer 0**         |
|                                                     |         |         | | **Layer 1**         |
|                                                     |         |         | | **Layer 2**         |
|                                                     |         |         | | **Layer 3**         |
|                                                     |         |         | | **Layer 4**         |
|                                                     |         |         | | **Layer 5**         |
|                                                     |         |         | | **Layer 6**         |
|                                                     |         |         | | **Layer 7**         |
|                                                     |         |         | | **Layer 8**         |
|                                                     |         |         | | **Layer 9**         |
+-----------------------------------------------------+---------+---------+-----------------------+
| Resize Mode / ``Resize_Mode``                       | Choice  | Dynamic | |                     |
|                                                     |         |         | | **Fixed (Inplace)** |
|                                                     |         |         | | **Dynamic**         |
|                                                     |         |         | | **Downsample 1/2**  |
|                                                     |         |         | | **Downsample 1/4**  |
|                                                     |         |         | | **Downsample 1/8**  |
|                                                     |         |         | | **Downsample 1/16** |
+-----------------------------------------------------+---------+---------+-----------------------+
| Ignore Alpha / ``Ignore_Alpha``                     | Boolean | Off     |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Preview/Draft Mode / ``PreviewDraft_Mode``          | Boolean | Off     |                       |
+-----------------------------------------------------+---------+---------+-----------------------+
| Log Verbosity / ``Log_Verbosity``                   | Choice  | Off     | |                     |
|                                                     |         |         | | **Off**             |
|                                                     |         |         | | **Level 1**         |
|                                                     |         |         | | **Level 2**         |
|                                                     |         |         | | **Level 3**         |
+-----------------------------------------------------+---------+---------+-----------------------+
