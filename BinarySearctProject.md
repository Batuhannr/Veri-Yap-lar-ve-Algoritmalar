<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    table, th, td {
      border:1px solid black;
    }
    </style>
<body>
<div>
        <h1>Ana Dizi : [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]</h1>
    </div>
    <div>
        <h3>Aşama 1</h3>
        <p>Root 7 Olsun</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td>&nbsp;</td>
                <td>7</td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 2</h3>
        <p>5 7'den Ufak olduğu için soluna ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td>7</td>
            </tr>
            <tr>
                <td>5</td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 3</h3>
        <p>1 5'den Ufak olduğu için soluna ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>7</td>
            </tr>
            <tr>
                <td></td>
                <td>5</td>
                <td></td>
            </tr>
            <tr>
                <td>1</td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 4</h3>
        <p>8 7'den Büyük olduğu için sağına ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>7</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>5</td>
                <td></td>
                <td>8</td>
            </tr>
            <tr>
                <td>1</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 5</h3>
        <p>3 1'den Büyük olduğu için sağına ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>7</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>5</td>
                <td></td>
                <td>8</td>
            </tr>
            <tr>
                <td>1</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>3</td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 6</h3>
        <p>6 5'den Büyük olduğu için sağına ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>7</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>5</td>
                <td></td>
                <td>8</td>
            </tr>
            <tr>
                <td>1</td>
                <td></td>
                <td>6</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>3</td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 7</h3>
        <p>0 1'den Küçük olduğu için Soluna ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td>7</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>5</td>
                <td></td>
                <td>8</td>
            </tr>
            <tr>
                <td></td>
                <td>1</td>
                <td></td>
                <td>6</td>
                <td></td>
            </tr>
            <tr>
                <td>0</td>
                <td></td>
                <td>3</td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 8</h3>
        <p>9 8'den Büyük olduğu için Sağına ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td>7</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>5</td>
                <td></td>
                <td>8</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>1</td>
                <td></td>
                <td>6</td>
                <td></td>
                <td>9</td>
            </tr>
            <tr>
                <td>0</td>
                <td></td>
                <td>3</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 9</h3>
        <p>4 3'den Büyük olduğu için Sağına ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td>7</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>5</td>
                <td></td>
                <td>8</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>1</td>
                <td></td>
                <td>6</td>
                <td></td>
                <td>9</td>
            </tr>
            <tr>
                <td>0</td>
                <td></td>
                <td>3</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td>4</td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
    <div>
        <h3>Aşama 10</h3>
        <p>2 3'den Küçük olduğu için Soluna ekliyoruz</p>
        <table>
            <tr>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
                <th>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td>7</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>5</td>
                <td></td>
                <td>8</td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>1</td>
                <td></td>
                <td>6</td>
                <td></td>
                <td>9</td>
            </tr>
            <tr>
                <td>0</td>
                <td></td>
                <td>3</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td>2</td>
                <td></td>
                <td>4</td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
</body>
</html>
