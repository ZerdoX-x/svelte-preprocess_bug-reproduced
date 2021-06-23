<ul>
  <li>
    <span class="text">text</span>
  </li>
</ul>

<style lang="stylus">
@media screen and (min-width: 0px) {
  ul :global(.text) {
    background: red;
  }
  /*
  ul :global([class~="text"]) {
    background: red;
  }
  */
}
</style>
