##Diagrama
<?xml version="1.0" encoding="UTF-8"?>
<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/137.0.0.0 Safari/537.36" version="27.1.6">
  <diagram name="Diagrama iPhone" id="iphone-diagrama-id">
    <mxGraphModel dx="1426" dy="785" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="2" value="&lt;&lt;interface&gt;&gt;&#xa;ReprodutorMusical&#xa;+tocar()&#xa;+pausar()&#xa;+selecionarMusica(String)" style="shape=swimlane;rounded=1;startSize=70;" parent="1" vertex="1">
          <mxGeometry x="40" y="70" width="200" height="100" as="geometry" />
        </mxCell>
        <mxCell id="3" value="&lt;&lt;interface&gt;&gt;&#xa;AparelhoTelefonico&#xa;+ligar(String)&#xa;+atender()&#xa;+iniciarCorreioVoz()" style="shape=swimlane;rounded=1;startSize=70;" parent="1" vertex="1">
          <mxGeometry x="290" y="70" width="200" height="100" as="geometry" />
        </mxCell>
        <mxCell id="4" value="&lt;&lt;interface&gt;&gt;&#xa;NavegadorInternet&#xa;+exibirPagina(String)&#xa;+adicionarNovaAba()&#xa;+atualizarPagina()" style="shape=swimlane;rounded=1;startSize=70;" parent="1" vertex="1">
          <mxGeometry x="560" y="70" width="200" height="100" as="geometry" />
        </mxCell>
        <mxCell id="5" value="iPhone&#xa;+tocar()&#xa;+pausar()&#xa;+selecionarMusica(String)&#xa;+ligar(String)&#xa;+atender()&#xa;+iniciarCorreioVoz()&#xa;+exibirPagina(String)&#xa;+adicionarNovaAba()&#xa;+atualizarPagina()" style="shape=swimlane;rounded=1;fillColor=#e6f0ff;startSize=160;" parent="1" vertex="1">
          <mxGeometry x="280" y="230" width="240" height="230" as="geometry">
            <mxRectangle x="250" y="300" width="180" height="160" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="6" style="endArrow=block;dashed=1;" parent="1" source="5" target="2" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7" style="endArrow=block;dashed=1;" parent="1" source="5" target="3" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="8" style="endArrow=block;dashed=1;" parent="1" source="5" target="4" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
