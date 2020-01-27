<template>
  <div class="minor">
    <h1>Minor- geheel</h1>
    <table class="alleenMinor">
      <thead>
        <tr>
          <th>Week</th>
          <th>Vak</th>
          <th>EC</th>
          <th>FTE<br /></th>
        </tr>
        <tr>
          <td>1-2-3</td>
          <td>WAFS</td>
          <td>3</td>
          <td>1</td>
        </tr>
        <tr>
          <td class= "alGehaald"
>1-2-3</td>
          <td class= "alGehaald"
>CSS2TR</td>
          <td class= "alGehaald"
>3</td>
          <td class= "alGehaald"
>0</td>
        </tr>
        <tr>
          <td>4</td>
          <td>Project 1</td>
          <td></td>
          <td>1</td>
        </tr>
        <tr>
          <td>5-6-7</td>
          <td>Browser Technologies</td>
          <td>3</td>
          <td>0.3</td>
        </tr>
        <tr>
          <td>5-6-7</td>
          <td>Performance Matters</td>
          <td>3</td>
          <td>1</td>
        </tr>
        <tr>
          <td>8</td>
          <td>Project 2</td>
          <td></td>
          <td>1</td>
        </tr>
        <tr>
          <td>9-10-11</td>
          <td>Real-time Web</td>
          <td>3</td>
          <td>1</td>
        </tr>
        <tr>
          <td class= "alGehaald"
>9-10-11</td>
          <td class= "alGehaald"
 >Web Design</td>
          <td class= "alGehaald"
>3</td>
          <td class= "alGehaald"
>0</td>
        </tr>
        <tr>
          <td>12</td>
          <td>Project 3</td>
          <td></td>
          <td>1</td>
        </tr>
        <tr>
          <td>13+</td>
          <td>Meesterproef</td>
          <td>9</td>
          <td>1</td>
        </tr>
        <tr>
          <td>overig</td>
          <td>Weekly Nerd</td>
          <td>3</td>
          <td>1</td>
        </tr>
        <tr>
          <td><b>TOTAAL</b></td>
          <td></td>
          <td><b>30</b></td>
          <td></td>
        </tr>
      </thead>
      <tbody></tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "alleenMinorFully",
  props: {
    msg: String
  }
};
</script>
<style>
.minor{
  display: flex;
  flex-direction: column;
  align-self: center;
  align-items: center;
  align-content: center;
}
.alleenMinor {
  border: 1px ridge #ffffff;
  border-collapse: separate;
  border-spacing: 1px;
  padding: 9px;
}
.alleenMinor th {
  border: 1px ridge #ffffff;
  padding: 9px;
  background: #c8a2c8;
}
.alleenMinor td {
  border: 1px ridge #ffffff;
  text-align: center;
  padding: 9px;
  background: #f2e8f2;
}

.alGehaald{
  text-decoration: line-through;
}
</style>
