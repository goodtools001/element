<style>
  .demo-typo-box {
    height: 200px;
    width: 200px;
    position: relative;
    border: 1px solid #eaeefb;
    font-size: 40px;
    color: #1f2d3d;
    text-align: center;
    line-height: 162px;
    padding-bottom: 36px;
    box-sizing: border-box;
    display: inline-block;
    margin-right: 17px;
    border-radius: 4px;

    .name {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 35px;
      border-top: 1px solid #eaeefb;
      font-size: 14px;
      color: #8492a6;
      line-height: 35px;
      text-align: left;
      text-indent: 10px;
      font-family: 'Helvetica Neue';
    }
  }
  .demo-typo-size {
    .h1 {
      font-size: 20px;
    }
    .h2 {
      font-size: 18px;
    }
    .h3 {
      font-size: 16px;
    }
    .text-regular {
      font-size: 14px;
    }
    .text-small {
      font-size: 13px;
    }
    .text-smaller {
      font-size: 12px;
    }
    .color-dark-light {
      color: #99a9bf;
    }
  }
  .typo-PingFang {
    font-family: 'PingFang SC';
  }
  .typo-Hiragino {
    font-family: 'Hiragino Sans GB';
  }
  .typo-Microsoft {
    font-family: 'Microsoft YaHei';
  }
  /* 英文 \*/
  .typo-Helvetica-Neue {
    font-family: 'Helvetica Neue';
  }
  .typo-Helvetica {
    font-family: 'Helvetica';
  }
  .typo-Arial {
    font-family: 'Arial';
  }
</style>

## Typographie

Nous avons créé une convention de police d'écriture afin d'assurer la meilleur présentation possible sur toutes le plateformes.

### Police chinoise

<div class="demo-typo-box typo-PingFang">
  和畅惠风
  <div class="name">PingFang SC</div>
</div>
<div class="demo-typo-box typo-Hiragino">
  和畅惠风
  <div class="name">Hiragino Sans GB</div>
</div>
<div class="demo-typo-box typo-Microsoft">
  和畅惠风
  <div class="name">Microsoft YaHei</div>
</div>

### Police anglaise / numérique

<div class="demo-typo-box typo-Helvetica-neue">
  RGag
  <div class="name">Helvetica Neue</div>
</div>
<div class="demo-typo-box typo-Helvetica">
  RGag
  <div class="name">Helvetica</div>
</div>
<div class="demo-typo-box typo-Arial">
  RGag
  <div class="name">Arial</div>
</div>

### Font-family

```css
font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
```

### Convention des polices

<table class="demo-typo-size">
  <tbody>
    <tr>
      <td class="h1">Titre principal</td>
      <td class="h1">Construit avec Element</td>
      <td class="color-dark-light">20px  Extra large</td>
    </tr>
    <tr>
      <td class="h2">Titre</td>
      <td class="h2">Construit avec Element</td>
      <td class="color-dark-light">18px large</td>
    </tr>
    <tr>
      <td class="h3">Sous-titre</td>
      <td class="h3">Construit avec Element</td>
      <td class="color-dark-light">16px Medium</td>
    </tr>
    <tr>
      <td class="text-regular">Body</td>
      <td class="text-regular">Construit avec Element</td>
      <td class="color-dark-light">14px Small</td>
    </tr>
    <tr>
      <td class="text-small">Body (petit)</td>
      <td class="text-small">Construit avec Element</td>
      <td class="color-dark-light">13px Extra Small</td>
    </tr>
    <tr>
      <td class="text-smaller">Texte supplémentaire</td>
      <td class="text-smaller">Construit avec Element</td>
      <td class="color-dark-light">12px Extra Extra Small</td>
    </tr>
  </tbody>
</table>
