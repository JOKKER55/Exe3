<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Table</title>
    <style>
    table,
    th {
        border: 2px solid black;

    }
    td {
        border: 2px solid black;
    }

    thead {
        border: 1px solid black;
    }

  </style>
</head>
<body>
  <table>
    <thead>
    <tr>
        <th>Kolumna 1</th>
        <th colspan="2">Kolumna 2</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td class="col1">wiersz 1</td>
        <td rowspan="2" class="col2">wiersz 2</td>
        <td class="col3">wiersz 3</td>
    </tr>
    <tr>
        <td class="col1">wiersz 4</td>
        <td class="col3">wiersz 5</td>
    </tr>
    <tr>
        <td class="col1">wiersz 6</td>
        <td class="col2" style="vertical-align: middle; text-align: center;">wiersz 7</td>
        <td class="col3">wiersz 8</td>
    </tr>
    </tbody>
</table>
    </body>
</html>
