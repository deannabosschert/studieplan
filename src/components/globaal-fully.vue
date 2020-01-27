<template>
  <div class="globaal">
    <h1>Globaal- geheel</h1>
    <table class="table1">
      <thead>
        <tr>
          <th>Blok 3- MWD</th>
          <th>EC</th>
          <th>Blok 4- MWD</th>
          <th>EC</th>
          <th>Blok 1- Project Web</th>
          <th>EC</th>
          <th>Blok 2- Herkansingen</th>
          <th>EC</th>
          <th>Blok 3- Afstudeerstage</th>
          <th>EC</th>
          <th>Blok 4- Afstudeerproject</th>
          <th>EC</th>
        </tr>
        <tr>
          <td>Web Apps from Scratch</td>
          <td>3</td>
          <td>Real-time Web</td>
          <td>3</td>
          <td>Vormgeving 2</td>
          <td>3</td>
          <td>DataVis<br /></td>
          <td>3</td>
          <td>Lange Stage<br /></td>
          <td>30</td>
          <td>Afstudeerproject</td>
          <td>30</td>
        </tr>
        <tr>
          <td class= "alGehaald">CSS to the Rescue</td>
          <td class= "alGehaald">3</td>
          <td class= "alGehaald">Web Design</td>
          <td class= "alGehaald">3</td>
          <td>Design Patterns</td>
          <td>3</td>
          <td>Research for Data</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>Project 1</td>
          <td>nvt</td>
          <td>Project 3</td>
          <td>nvt</td>
          <td>Frontend</td>
          <td>3</td>
          <td class= "alGehaald">Artificial Intelligence</td>
          <td class= "alGehaald">3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>Performance Matters</td>
          <td>3</td>
          <td>Weekly Nerd</td>
          <td>3</td>
          <td>Project Web</td>
          <td>5</td>
          <td>Frontend Applications</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>Browser<br />Technologies</td>
          <td>3</td>
          <td>Meesterproef</td>
          <td>9</td>
          <td></td>
          <td></td>
          <td>Functional Programming</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>Project 2</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td>Frontend Data</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td class= "alGehaald">Dataweek</td>
          <td class= "alGehaald">2</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td class= "alGehaald">ID Pointer project</td>
          <td class= "alGehaald">9</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td>Project Tech</td>
          <td>5</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td><b>TOTAAL EC (141)</b></td>
          <td><b>15</b></td>
          <td></td>
          <td><b>18</b></td>
          <td></td>
          <td><b>14</b></td>
          <td></td>
          <td><b>34</b></td>
          <td></td>
          <td><b>30</b></td>
          <td></td>
          <td><b>30</b></td>
        </tr>
      </thead>
      <tbody></tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "globaalFully",
  props: {
    msg: String
  }
};
</script>

<style>
.globaal{
  display: flex;
  flex-direction: column;
  max-width: 85vw;
  align-self: center;
  align-items: center;
  align-content: center;
}

.alGehaald{
  text-decoration: line-through;
}

.table1 {
  border: 1px ridge #ffffff;
  border-collapse: separate;
  border-spacing: 1px;
  padding: 9px;
}
.table1 th {
  border: 1px ridge #ffffff;
  padding: 9px;
  background: #c8a2c8;
}
.table1 td {
  border: 1px ridge #ffffff;
  text-align: center;
  padding: 9px;
  background: #f2e8f2;
}
</style>
