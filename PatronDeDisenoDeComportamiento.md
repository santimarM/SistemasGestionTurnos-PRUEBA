<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36 OPR/119.0.0.0" version="27.1.6">
  <diagram name="Página-1" id="5h8gg97MH5LTVB95QTGK">
    <mxGraphModel>
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="2" value="Turno" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=36.8;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=0;marginBottom=0;" vertex="1" parent="1">
          <mxGeometry x="138" y="8" width="205" height="192" as="geometry" />
        </mxCell>
        <mxCell id="3" value="- observadores: List" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="2">
          <mxGeometry y="37" width="205" height="37" as="geometry" />
        </mxCell>
        <mxCell id="4" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="2">
          <mxGeometry y="74" width="205" height="8" as="geometry" />
        </mxCell>
        <mxCell id="5" value="+ agregar(obs) : : void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="2">
          <mxGeometry y="82" width="205" height="37" as="geometry" />
        </mxCell>
        <mxCell id="6" value="+ quitar(obs) : : void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="2">
          <mxGeometry y="118" width="205" height="37" as="geometry" />
        </mxCell>
        <mxCell id="7" value="+ notificar() : : void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="2">
          <mxGeometry y="155" width="205" height="37" as="geometry" />
        </mxCell>
        <mxCell id="8" value="Paciente" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=47.2;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=0;marginBottom=0;" vertex="1" parent="1">
          <mxGeometry x="8" y="273" width="209" height="126" as="geometry" />
        </mxCell>
        <mxCell id="9" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="8">
          <mxGeometry y="71" width="209" height="8" as="geometry" />
        </mxCell>
        <mxCell id="10" value="+ actualizar() : : void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="8">
          <mxGeometry y="79" width="209" height="47" as="geometry" />
        </mxCell>
        <mxCell id="11" value="Medico" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=47.2;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=0;marginBottom=0;" vertex="1" parent="1">
          <mxGeometry x="267" y="273" width="203" height="126" as="geometry" />
        </mxCell>
        <mxCell id="12" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="11">
          <mxGeometry y="71" width="203" height="8" as="geometry" />
        </mxCell>
        <mxCell id="13" value="+ actualizar() : : void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="11">
          <mxGeometry y="79" width="203" height="47" as="geometry" />
        </mxCell>
        <mxCell id="14" value="&amp;lt;&amp;gt;" style="curved=1;startArrow=block;startSize=16;startFill=0;endArrow=none;exitX=0.05;exitY=1;entryX=0.5;entryY=0;" edge="1" parent="1" source="2" target="8">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="112" y="237" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="15" value="&amp;lt;&amp;gt;" style="curved=1;startArrow=block;startSize=16;startFill=0;endArrow=none;exitX=0.95;exitY=1;entryX=0.5;entryY=0;" edge="1" parent="1" source="2" target="11">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="368" y="237" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
