# cse4020-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE4020 Lab 3 Solved](https://www.ankitcodinghub.com/product/cse4020-lab-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91685&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE4020 Lab 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Write down a Python program to draw a rotating triangle.

<ol>
<li>Set the window title to your student ID and the window size to (480,480).</li>
<li>Draw a triangle using render() function below (DO NOT modify it!).</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
def render(T):

</div>
</div>
<div class="layoutArea">
<div class="column">
glClear(GL_COLOR_BUFFER_BIT)

</div>
</div>
<div class="layoutArea">
<div class="column">
glLoadIdentity()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># draw cooridnate
</pre>
glBegin(GL_LINES)

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 0, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([1.,0.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(0, 255, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([0.,1.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># draw triangle
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
glBegin(GL_TRIANGLES)

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 255, 255)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv( (T @ np.array([.0,.5,1.]))[:-1] )

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv( (T @ np.array([.0,.0,1.]))[:-1] )

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv( (T @ np.array([.5,.0,1.]))[:-1] )

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
C. Expected result: Uploaded LabAssignment3-1.mp4 i. Do not mind the initial angle of the triangle.

<ol start="4">
<li>The triangle should be t rad rotated when t seconds have elapsed since the program was executed.</li>
<li>You need to somehow combine a rotation matrix and a translation matrix to produce the expected result.</li>
<li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>
</ol>
2. Write down a Python program to draw a transformed triangle.

<ol>
<li>Set the window title to your student ID and the window size to (480,480).</li>
<li>Draw a triangle using render() function of prob 1 (DO NOT modify it!).</li>
<li>If you press or repeat a key, the triangle should be transformed as shown in the Table:Key
W E

S D X
</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Transformation

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Scale by 0.9 times in y direction

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Scale by 1.1 times in y direction

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Rotate by 10 degrees counterclockwise

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Rotate by 10 degrees clockwise

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Translate by 0.1 in x direction

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Translate by -0.1 in x direction

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Reflection across the origin

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Reset the triangle with identity matrix

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
D.

</div>
<div class="column">
C R 1

􏱀􏰌􏰚􏰂􏰈􏰉􏰘􏰌􏰆􏰚􏰃􏰓􏰘􏰂􏰈 􏰈􏰗􏰘􏰐􏰕􏰊 􏰍􏰖 􏰚􏰛􏰛􏰐􏰆􏰐􏰕􏰚􏰃􏰖􏰊 􏰲􏰛􏰘􏰆􏰠􏰘􏰈􏰖􏰊 􏰪􏰓􏰃􏰗 􏰠􏰌􏰖􏰅􏰓􏰘􏰐􏰈 􏰘􏰂􏰖􏱁 􏰐􏰂􏰕􏰖􏰈􏰈 􏰦􏰘􏰐 􏰠􏰌􏰖􏰈􏰈 􏰧􏰣􏰜􏰫

<ol>
<li>Be sure: gComposedM = newM @ gComposedM</li>
<li>􏱂􏰘􏰐􏰜􏰕􏰕 􏰂􏰖􏰖􏰊 􏰃􏰘 􏰆􏰚􏰝􏰖 􏰧􏰔􏰷􏰘􏰆􏰠􏰘􏰈􏰖􏰊􏰴􏰜 􏰚􏰈 􏰚 􏰔􏰕􏰘􏰍􏰚􏰕 􏰅􏰚􏰌􏰓􏰚􏰍􏰕􏰖.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
E. Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)

F. Expected result

When starts W *3 S *3

</div>
</div>
<div class="layoutArea">
<div class="column">
C *3 R

</div>
<div class="column">
1

</div>
</div>
</div>
