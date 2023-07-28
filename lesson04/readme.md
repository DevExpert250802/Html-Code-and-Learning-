Tables

Tag       Description


<table>  Defines a table
<caption>  Defines a table caption
<th>  Defines a header cell in a table
<tr>   Defines a row in a table
<td>  Defines a cell in a table
<thead>  Groups the header content in a table
<tbody>   Groups the body content in a table
<tfoot>  Groups the footer content in a table
<col>  Specifies column properties for each column within a <colgroup> element
<colgroup>  Specifies a group of one or more columns in a table for formatting

<rowspan=""> colums you want to expand till rows
 eg:- yoy want to expand 2nd column in 3rd row till 5th row

<colspan=""> columns you want to merge/extend in same row
eg:- In a row if there are 5 columns and you want to merge 3 columns(want to create only 2 columns)

shortcut :-
 
 table>(tr>td*3)


<table>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </table>



   table>(tr>td*3)*4


    <table>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </table>