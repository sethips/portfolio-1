<template>
  <div class="container">
    <img id="dancingkitty" src="../assets/images/dancingkitty.gif" />
    <div class="row">
        <h1 class="superheader">/** 404: PageNotFound ;( **/</h1>
    </div>
    <div class="row">
        <h4>{{new Date().toLocaleDateString()}} creo.site.PageNotFoundException: Unable to locate {{$route.path}}, no such page exists.</h4>
        <p>at creo.webpage.performLaunchWebPage(<span class="coloritblue">RequestPage.java:1234</span>)</p>
        <p>at creo.webpage.requestWebPage(<span class="coloritblue">RequestPage.java:231</span>)</p>
        <p>at creo.webpage.handleRequestWebPage(<span class="coloritblue">RequestPage.java:321</span>)</p>
        <p>at creo.webpage.dispatchWebPage(<span class="coloritblue">DispatchPage.java:777</span>)</p>
    </div>
    <div class="row">
        <h4>Caused by, creo.site.FMLException: Reasons such as the following,</h4>
        <p>at either.i.broke.something(<span class="coloritblue">TotalFail.java:1</span>)</p>
        <p>or im.still.working.on.this.page(<span class="coloritblue">Rekt.java:2</span>)</p>
        <p>at i.suck.at.frontend.development(<span class="coloritblue">SuperNoobz.java:3</span>)</p>
        <p>at please.send.help(<span class="coloritblue">HelpMeLordGaben.java:4</span>)</p>
        <p>at please.send.help(<span class="coloritblue">HelpMeAlmightyDennisRichie.java:5</span>)</p>
        <p>at why.u.no.work.codezs(<span class="coloritblue">SlashWrist.java:6</span>)&lt;2 more...&gt;</p>
    </div>
  </div>
</template>
<style scoped>
  p {
    text-indent: 50px;
    font-family: "Roboto Condensed", Roboto;
    font-size: 1rem;
  }
  h1 {
    font-family: 'Courier New', Courier, monospace;
    font-size: 3.5rem;
  }
  h4 {
    color: red;
    font-family: Consolas, Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 1.3rem;
  }
  .coloritblue {
    color: dodgerblue;
    text-decoration: underline;
  }
  #dancingkitty {
    float:bottom;
    position:fixed;
    z-index: -1;
    bottom: 10%;
    right: 5%;
}
</style>
