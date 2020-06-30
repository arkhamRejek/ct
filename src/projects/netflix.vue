<template>
  <div>
    <header>
      <img
        id="netflix-logo"
        src="https://pmcvariety.files.wordpress.com/2020/05/netflix-logo.png"
        class="avatar"
      />

      <div>
        <span>DVD</span>
        <img
          class="avatar"
          src="https://occ-0-3418-3419.1.nflxso.net/dnm/api/v6/Z-WHgqd_TeJxSuha8aZ5WpyLcX8/AAAABcPFzgL9KOjilZPRTvg7jDVSj30dhEpcq2pL2RLPiC9iSKx5oHB59jblEBgayqySHFDRjUu8Va60rQdx53eznN0.png?r=c37"
        />
      </div>
    </header>

    <div id="container">
      <div id="table-header">
        <h1>Activity for Paul</h1>
        <div id="misc">
          <span>Watching | Rating</span>
          <img
            src="https://occ-0-3418-3419.1.nflxso.net/dnm/api/v6/Z-WHgqd_TeJxSuha8aZ5WpyLcX8/AAAABcPFzgL9KOjilZPRTvg7jDVSj30dhEpcq2pL2RLPiC9iSKx5oHB59jblEBgayqySHFDRjUu8Va60rQdx53eznN0.png?r=c37"
            height="32px"
            width="32px"
          />
        </div>
      </div>

      <table>
        <tbody>
          <tr>
            <td>6/30/20</td>
            <td>
              <a href="https://www.netflix.com/title/80209535">Killing Gunther</a>
            </td>
            <td>
              <a href="https://www.netflix.com/title/80209535">report a problem</a>
            </td>
            <td>⊘</td>
          </tr>

          <tr>
            <td>6/30/20</td>
            <td>
              <a href="https://www.netflix.com/title/80209535">Killing Gunther</a>
            </td>
            <td>
              <a href="https://www.netflix.com/title/80209535">report a problem</a>
            </td>
            <td>⊘</td>
          </tr>

          <tr>
            <td>6/30/20</td>
            <td>
              <a href="https://www.netflix.com/title/80209535">Killing Gunther</a>
            </td>
            <td>
              <a href="https://www.netflix.com/title/80209535">report a problem</a>
            </td>
            <td>⊘</td>
          </tr>

          <tr>
            <td>6/30/20</td>
            <td>
              <a href="https://www.netflix.com/title/80209535">Killing Gunther</a>
            </td>
            <td>
              <a href="https://www.netflix.com/title/80209535">report a problem</a>
            </td>
            <td>⊘</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: #f3f3f3;
}
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 70px;
  background-color: rgba(0, 0, 0, 0.97);
  width: 100%;
  margin-bottom: 3%;
}
#netflix-logo {
  width: 12%;
  height: 80%;
}
.avatar {
  width: 32px;
  height: 32px;
  padding: 2%;
}
header span {
  color: white;
  font-weight: bold;
}

#container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

#container #table-header {
  width: 80%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
table {
  border-collapse: collapse;
  width: 80%;
}
table tr {
  border-top: 1px solid #ccc;
}
table td {
  padding: 20px;
}
</style>