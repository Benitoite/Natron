.. _eu.gmic.Boxfitting:

G’MIC Box fitting node
======================

*This documentation is for version 0.3 of G’MIC Box fitting.*

Description
-----------

Author: David Tschumperle. Latest update: 2010/29/12.

Note: Set Maximal size to 0 to allow any size for the squares.

Note: This filter has been highly inspired by the work of Jared Tarbell, described on the page:

http://www.complexification.net/gallery/machines/boxFittingImg/

Author: David Tschumperle. Latest update: 2013/06/06.

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

+--------------------------------------------+---------+-----------+-----------------------+
| Parameter / script name                    | Type    | Default   | Function              |
+============================================+=========+===========+=======================+
| Starting pattern / ``Starting_pattern``    | Choice  | Red-Green | |                     |
|                                            |         |           | | **Red-Green**       |
|                                            |         |           | | **Blue-Green**      |
|                                            |         |           | | **Green-Red**       |
|                                            |         |           | | **Green-Blue**      |
+--------------------------------------------+---------+-----------+-----------------------+
| Keep colors / ``Keep_colors``              | Boolean | On        |                       |
+--------------------------------------------+---------+-----------+-----------------------+
| Minimal size / ``Minimal_size``            | Integer | 3         |                       |
+--------------------------------------------+---------+-----------+-----------------------+
| Maximal size / ``Maximal_size``            | Integer | 0         |                       |
+--------------------------------------------+---------+-----------+-----------------------+
| Initial density / ``Initial_density``      | Double  | 0.1       |                       |
+--------------------------------------------+---------+-----------+-----------------------+
| Transparency / ``Transparency``            | Boolean | Off       |                       |
+--------------------------------------------+---------+-----------+-----------------------+
| Output Layer / ``Output_Layer``            | Choice  | Layer 0   | |                     |
|                                            |         |           | | **Merged**          |
|                                            |         |           | | **Layer 0**         |
|                                            |         |           | | **Layer 1**         |
|                                            |         |           | | **Layer 2**         |
|                                            |         |           | | **Layer 3**         |
|                                            |         |           | | **Layer 4**         |
|                                            |         |           | | **Layer 5**         |
|                                            |         |           | | **Layer 6**         |
|                                            |         |           | | **Layer 7**         |
|                                            |         |           | | **Layer 8**         |
|                                            |         |           | | **Layer 9**         |
+--------------------------------------------+---------+-----------+-----------------------+
| Resize Mode / ``Resize_Mode``              | Choice  | Dynamic   | |                     |
|                                            |         |           | | **Fixed (Inplace)** |
|                                            |         |           | | **Dynamic**         |
|                                            |         |           | | **Downsample 1/2**  |
|                                            |         |           | | **Downsample 1/4**  |
|                                            |         |           | | **Downsample 1/8**  |
|                                            |         |           | | **Downsample 1/16** |
+--------------------------------------------+---------+-----------+-----------------------+
| Ignore Alpha / ``Ignore_Alpha``            | Boolean | Off       |                       |
+--------------------------------------------+---------+-----------+-----------------------+
| Preview/Draft Mode / ``PreviewDraft_Mode`` | Boolean | Off       |                       |
+--------------------------------------------+---------+-----------+-----------------------+
| Log Verbosity / ``Log_Verbosity``          | Choice  | Off       | |                     |
|                                            |         |           | | **Off**             |
|                                            |         |           | | **Level 1**         |
|                                            |         |           | | **Level 2**         |
|                                            |         |           | | **Level 3**         |
+--------------------------------------------+---------+-----------+-----------------------+
