- The `<table>` element creates a table.
- The `<tr>` element adds rows to a table.
- To `add data to a row`, you can use the `<td>` element.
- Table headings clarify the meaning of data. `Headings` are added with the `<th>` element.
- Table data can `span columns` using the `colspan attribute`.
- Table data can `span rows` using the `rowspan attribute.`
- Tables can be split into three main sections: a head, a body, and a footer.
  - A table’s head is created with the `<thead>` element.
  - A table’s body is created with the `<tbody>` element.
  - A table’s footer is created with the `<tfoot>` element.
<table>
<thead>
        <tr>
          <th scope="col">Company Name</th>
          <th scope="col">Number of Items to Ship</th>
          <th scope="col">Next Action</th>
        </tr>
</thead>

<tbody>
        <tr>
          <td colspan="2">Adam’s Greenworks</td>
          <!--gộp hàng-->
          <td>14</td>
          <td>Package Items</td>
        </tr>
        <tr>
          <td>Davie's Burgers</td>
          <td>2</td>
          <td rowspan="2">Send Invoice</td>
          <!--gộp cột-->
        </tr>
        <tr>
          <td>Baker's Bike Shop</td>
          <td>3</td>
          <td>Send Invoice</td>
        </tr>
        <tr>
          <td>Miss Sally's Southern</td>
          <td>4</td>
          <td>Ship</td>
        </tr>
        <tr>
          <td>Summit Resort Rentals</td>
          <td>4</td>
          <td>Ship</td>
        </tr>
</tbody>

<tfoot>
        <tr>
          <td>Strike Fitness</td>
          <td>1</td>
          <td>Enter Order</td>
        </tr>
</tfoot>
</table>
