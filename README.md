### Code:

```HTML
<div align=center>

  <h3>Centered Heading</h3>
  
  <p>
    All elements inside a container (div),
    which includes headings, images,
    paragraphs (p), tables, and lists,
    will inherit the container (div)'s
    attirbutes i.e., align=center
  </p>
  
  <p align=right>
    ...That is, unless <br />
    overridden, like in <br />
    the case of this <br />
    paragraph and the <br />
    table cells R1C1 <br />
    and R2C1
  </p>
  
  <img src="some_pic.webp" alt="an image" width="200"/>

  <hr>
  
  <table>
    <tr>
      <th colspan=3>
        TABLE HEADER SPANNING 3 COLUMNS
      </th>
    </tr>
    <tr>
      <th>Heading A</th>
      <th>Heading B</th>
      <th>Heading C</th>
    </tr>
    <tr>
      <td align=left>R1C1</td>
      <td>R1C2</td>
      <td>R1C3</td>
    </tr>
    <tr>
      <td align=right>R2C1</td>
      <td>R2C2</td>
      <td rowspan=2>R2C3:R3C3</td>
    </tr>
    <tr>
      <td>R3C1</td>
      <td>R3C2</td>
    </tr>
  </table>
  
</div>
```

---

### Result:

<div align=center>

  <h3>Centered Heading</h3>
  
  <p>
    All elements inside a container (div),
    which includes headings, images,
    paragraphs (p), tables, and lists,
    will inherit the container (div)'s
    attirbutes i.e., align=center
  </p>
  
  <p align=right>
    ...That is, unless <br />
    overridden, like in <br />
    the case of this <br />
    paragraph and the <br />
    table cells R1C1 <br />
    and R2C1
  </p>
  
  <img src="some_pic.webp" alt="an image" width="200"/>

  <hr>
  
  <table>
    <tr>
      <th colspan=3>
        TABLE HEADER SPANNING 3 COLUMNS
      </th>
    </tr>
    <tr>
      <th>Heading A</th>
      <th>Heading B</th>
      <th>Heading C</th>
    </tr>
    <tr>
      <td align=left>R1C1</td>
      <td>R1C2</td>
      <td>R1C3</td>
    </tr>
    <tr>
      <td align=right>R2C1</td>
      <td>R2C2</td>
      <td rowspan=2>R2C3:R3C3</td>
    </tr>
    <tr>
      <td>R3C1</td>
      <td>R3C2</td>
    </tr>
  </table>
  
</div>
