.. _eu.gmic.Sphere:

G’MIC Sphere node
=================

*This documentation is for version 0.3 of G’MIC Sphere.*

Description
-----------

Author: David Tschumperle. Latest update: 2011/07/11.

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

+--------------------------------------------+---------+-------------+-----------------------+
| Parameter / script name                    | Type    | Default     | Function              |
+============================================+=========+=============+=======================+
| Width / ``Width``                          | Integer | 512         |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Height / ``Height``                        | Integer | 512         |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Radius / ``Radius``                        | Double  | 90          |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Dilation / ``Dilation``                    | Double  | 0.5         |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Angle / ``Angle``                          | Double  | 0           |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Border smoothness / ``Border_smoothness``  | Double  | 0           |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Border width / ``Border_width``            | Double  | 20          |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Orientation / ``Orientation``              | Choice  | 0 deg.      | |                     |
|                                            |         |             | | **0 deg.**          |
|                                            |         |             | | **90 deg.**         |
|                                            |         |             | | **180 deg.**        |
|                                            |         |             | | **270 deg.**        |
+--------------------------------------------+---------+-------------+-----------------------+
| Background / ``Background``                | Choice  | Transparent | |                     |
|                                            |         |             | | **Transparent**     |
|                                            |         |             | | **Mean color**      |
+--------------------------------------------+---------+-------------+-----------------------+
| Fading / ``Fading``                        | Double  | 0           |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Fading shape / ``Fading_shape``            | Double  | 0.5         |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Output Layer / ``Output_Layer``            | Choice  | Layer 0     | |                     |
|                                            |         |             | | **Merged**          |
|                                            |         |             | | **Layer 0**         |
|                                            |         |             | | **Layer 1**         |
|                                            |         |             | | **Layer 2**         |
|                                            |         |             | | **Layer 3**         |
|                                            |         |             | | **Layer 4**         |
|                                            |         |             | | **Layer 5**         |
|                                            |         |             | | **Layer 6**         |
|                                            |         |             | | **Layer 7**         |
|                                            |         |             | | **Layer 8**         |
|                                            |         |             | | **Layer 9**         |
+--------------------------------------------+---------+-------------+-----------------------+
| Resize Mode / ``Resize_Mode``              | Choice  | Dynamic     | |                     |
|                                            |         |             | | **Fixed (Inplace)** |
|                                            |         |             | | **Dynamic**         |
|                                            |         |             | | **Downsample 1/2**  |
|                                            |         |             | | **Downsample 1/4**  |
|                                            |         |             | | **Downsample 1/8**  |
|                                            |         |             | | **Downsample 1/16** |
+--------------------------------------------+---------+-------------+-----------------------+
| Ignore Alpha / ``Ignore_Alpha``            | Boolean | Off         |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Preview/Draft Mode / ``PreviewDraft_Mode`` | Boolean | Off         |                       |
+--------------------------------------------+---------+-------------+-----------------------+
| Log Verbosity / ``Log_Verbosity``          | Choice  | Off         | |                     |
|                                            |         |             | | **Off**             |
|                                            |         |             | | **Level 1**         |
|                                            |         |             | | **Level 2**         |
|                                            |         |             | | **Level 3**         |
+--------------------------------------------+---------+-------------+-----------------------+
