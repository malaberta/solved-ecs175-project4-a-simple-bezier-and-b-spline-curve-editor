Download Link: https://assignmentchef.com/product/solved-ecs175-project4-a-simple-bezier-and-b-spline-curve-editor
<br>
<strong>Remark: You must NOT use GL’s routines for generating B´ezier or B-spline curves! </strong>You can use GL for rendering but not for evaluating these curves.

The fourth project requires the implementation of a 2D <strong>B´ezier </strong>and <strong>B-spline curve editor</strong>. A 2D B´ezier curve is defined as

<strong>c</strong><em>.</em>

For the evaluation of a B´ezier curve, use the <strong>de Casteljau algorithm </strong>to compute points on the curve. A single 2D parametric B-spline curve is defined as

<strong>c</strong><em>.</em>

Remember that you do not need to evaluate the normalized B-spline basis functions<em>. </em>For the evaluation of a B-spline curve, use the <strong>de Boor algorithm </strong>to generate points on the curve.

When dealing with a <strong>B´ezier curve</strong>, the user must be able to <strong>add, insert</strong>, <strong>delete</strong>, and <strong>modify </strong>the <strong>B´ezier points b</strong><em>i. </em>The same applies to a <strong>B-spline curve</strong>: The user must be able to <strong>add, insert</strong>, <strong>delete</strong>, and <strong>modify </strong>the <strong>de Boor points d</strong><em>i. </em>In addition to this, the user must be able to <strong>change </strong>the <strong>order </strong><em>k </em>of a B-spline curve and <strong>modify </strong>the values of the <strong>knots </strong><em>τ</em><sub>0</sub><em>, </em>… , <em>τ<sub>n</sub></em><sub>+</sub><em>k. </em>Initially, you can define the order to be <em>k </em>= 2 and the knots to be <em>τ<sub>i </sub></em>= <em>i, i </em>= 0<em>,…,n </em>+ <em>k.</em>

The user must be able to <strong>specify </strong>the <strong>number of points </strong>used for rendering a B´ezier or B-spline curve by a sequence of line segments (“display resolution”).

The user should be able to <strong>change all parameters easily </strong>by providing a screen area used for displaying and specifying the coordinates of control points (B´ezier and de Boor points), the order and the knots of a B-spline curve, and the display resolution. The specification of control points should be made as easy as possible. Either the user types in the control information directly, or – when modifying control points – uses a “rubber band” technique to interactively move control points.

1

The curve editor must provide a facility to <strong>store </strong>the <strong>parameters </strong>defining a B´ezier or B-spline curve. The system must be capable of <strong>reading </strong>and <strong>writing control information </strong>for B´ezier and B-spline curves.

It must be possible to manipulate, create, and display a scene containing <strong>multiple B´ezier </strong>and <strong>multiple B-spline curves</strong>. Make it possible to select a certain curve and to operate just on the selected one!

Besides having to hand in a program listing, please prepare a “manual sheet” explaining how to use your program.