# CSS Pseudo Classes

## Tasks

Create 2 tables with different layouts and CSS definitions, using the `:first-child`, `:last-child`, `:nth-child` and `:not` pseudo classes.

## Mockups

### Table 1

![Table 1](./images/table-1.jpg)

### Table 2

![Table 2](./images/table-2.jpg)

## Used Colors

### Table 1

<style>
.color {
  display: inline-block;
  width: 150px;
  padding: 2px;
  border: 1px solid #c0c0c0;
}

  .color-demo {
    width: 100%;
    height: 30px;
    margin: 0 auto;
  }

  .color-value {
    font-size: 1rem;
    line-height: 1.5;
    text-align: center;
    border-top: 1px solid #c0c0c0;
    margin-top: 2px;
  }
</style>

<p>
  <div class="color">
    <div class="color-demo" style="background: #c0c0c0;"></div>
    <div class="color-value">#c0c0c0</div>
  </div>
  <div class="color">
    <div class="color-demo" style="background: #cc181b;"></div>
    <div class="color-value">#cc181b</div>
  </div>
  <div class="color">
    <div class="color-demo" style="background: #449d45;"></div>
    <div class="color-value">#449d45</div>
  </div>
</p>

<strong>Table 2</strong>

<p>
  <div class="color">
    <div class="color-demo" style="background: #888888;"></div>
    <div class="color-value">#888888</div>
  </div>
  <div class="color">
    <div class="color-demo" style="background: #c0c0c0;"></div>
    <div class="color-value">#c0c0c0</div>
  </div>
  <div class="color">
    <div class="color-demo" style="background: #efefef;"></div>
    <div class="color-value">#efefef</div>
  </div>
  <div class="color">
    <div class="color-demo" style="background: #ffbbbb;"></div>
    <div class="color-value">#ffbbbb</div>
  </div>
</p>
