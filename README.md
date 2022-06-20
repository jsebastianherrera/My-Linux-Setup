<h1>Mapping keys</h1>
<p>Before you start, take a look at the list below </p>
<ul>    
  <li><a href="https://hea-www.harvard.edu/~fine/Tech/vi.html">Complete vim key binding list</a></li>
  <li><a href="#">Keys(find it out)</a></li>
</ul>
<h3>My key mapping</h3>
<ol>
  <li><a href="#basic-commands">Basic commands</a></li>
  <li><a href="#panel-interaction">Panel interaction</a></li>
  <li><a href="#tabs-management">Tabs management</a></li>
</ol>
<ul>
<li><h4>Basic commands</h4></li>
<p>Leader in my case means = " " <b>(Basically space key)</b></p>
 <table id="basic-commands">
    <thead>
      <tr>
      <th>Shortcut</th>
      <th>Command</th>
      <th>Function</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>&lt;Leader&gtw</td>
        <td>:w</td>
        <td>Save buffer</td>
      </tr>
      <tr>
        <td>&lt;Leader&gtq</td>
        <td>:q</td>
        <td>Quit current file</td>
      </tr>
      <tr>
        <td>&lt;A-w&gt</td>
        <td>:m .-2 &lt;CR&gt;==</td>
        <td>Moving line up</td>
      </tr>
      <tr>
        <td>&lt;A-s&gt</td>
        <td>:m .+1 &lt;CR&gt;==</td>
        <td>Moving line down</td>
      </tr>
      <tr>
        <td>&lt;C-UP&gt</td>
        <td>:5&lt;C-y&gt;</td>
        <td>Scroll up</td>
      </tr>
      <tr>
        <td>&lt;C-DOWN&gt</td>
        <td>:5&lt;C-e&gt;</td>
        <td>Scroll down</td>
      </tr>
    </tbody>
  </table>
  <li><h4>Panel interaction</h4></li>
  <table id="panel-interaction">
    <thead>
      <tr>
      <th>Shortcut</th>
      <th>Command</th>
      <th>Function</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>&lt;A-LEFT&gt;</td>
        <td>:&lt;C-w&gt;h</td>
        <td>Move to the left window </td>
      </tr>
      <tr>
        <td>&lt;A-RIGHT&gt;</td>
        <td>:&lt;C-w&gt;l</td>
        <td>Move to the right window </td>
      </tr>
      <tr>
        <td>&lt;A-DOWN&gt;</td>
        <td>:&lt;C-w&gt;j</td>
        <td>Move to the bottom window </td>
      </tr>
      <tr>
        <td>&lt;A-UP&gt;</td>
        <td>:&lt;C-w&gt;k</td>
        <td>Move to the top window </td>
      </tr>
      <tr>
        <td>&lt;A-S-RIGHT&gt;</td>
        <td>:5&lt;C-w&gt&gt;</td>
        <td>Resizing window to the right</td>
      </tr>
      <tr>
        <td>&lt;A-S-LEFT&gt;</td>
        <td>:5&lt;C-w&gt&lt;</td>
        <td>Resizing window to the left</td>
      </tr>
      <tr>
        <td>&lt;A-S-UP&gt;</td>
        <td>:5&lt;C-w&gt+</td>
        <td>Resizing window to the top</td>
      </tr>
      <tr>
        <td>&lt;A-S-DOWN&gt;</td>
        <td>:5&lt;C-w&gt-</td>
        <td>Resizing window to the bottom</td>
      </tr>
    </tbody>
  </table>
  <li><h4>Tabs management</h4></li>
  <table id="tabs-management">
    <thead>
      <tr>
      <th>Shortcut</th>
      <th>Command</th>
      <th>Function</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>&lt;C-RIGHT&gt;</td>
        <td>:BufferLineCycleNext &ltCR&gt;</td>
        <td>Move to the next tab </td>
      </tr>
      <tr>
        <td>&lt;C-LEFT&gt;</td>
        <td>:BufferLineCyclePrev &ltCR&gt;</td>
        <td>Move to the previous tab </td>
      </tr>
      <tr>
        <td>&lt;C-w&gt;</td>
        <td>:bdelete&lt;CR&gt;</td>
        <td>Close current tab</td>
      </tr>
    </tbody>
  </table>
</ul>
