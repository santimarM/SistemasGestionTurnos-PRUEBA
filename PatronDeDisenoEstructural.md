<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36 OPR/119.0.0.0" version="27.1.6">
  <diagram name="Página-1" id="FKkvr7_YuPaMDY13mN4o">
    <mxGraphModel>
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="2" value="&lt;&lt;Interfaz Incompatible&gt;&gt;&#xa;HistorialExterno" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=71;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=0;marginBottom=0;" vertex="1" parent="1">
          <mxGeometry x="64" y="424" width="298" height="150" as="geometry" />
        </mxCell>
        <mxCell id="3" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="2">
          <mxGeometry y="71" width="298" height="8" as="geometry" />
        </mxCell>
        <mxCell id="4" value="+ obtenerDatos() : : String" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="2">
          <mxGeometry y="79" width="298" height="47" as="geometry" />
        </mxCell>
        <mxCell id="5" value="AdapterHistorialExterno" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=45.333333333333336;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=0;marginBottom=0;" vertex="1" parent="1">
          <mxGeometry x="8" y="207" width="410" height="144" as="geometry" />
        </mxCell>
        <mxCell id="6" value="- externo: HistorialExterno" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="5">
          <mxGeometry y="45" width="410" height="45" as="geometry" />
        </mxCell>
        <mxCell id="7" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="5">
          <mxGeometry y="91" width="410" height="8" as="geometry" />
        </mxCell>
        <mxCell id="8" value="+ obtenerHistorialFormateado() : : String" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="5">
          <mxGeometry y="99" width="410" height="45" as="geometry" />
        </mxCell>
        <mxCell id="9" value="Paciente" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=47.2;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=0;marginBottom=0;" vertex="1" parent="1">
          <mxGeometry x="92" y="8" width="241" height="126" as="geometry" />
        </mxCell>
        <mxCell id="10" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="9">
          <mxGeometry y="71" width="241" height="8" as="geometry" />
        </mxCell>
        <mxCell id="11" value="+ usarAdaptador() : : void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;" vertex="1" parent="9">
          <mxGeometry y="79" width="241" height="47" as="geometry" />
        </mxCell>
        <mxCell id="12" value="usa" style="curved=1;startArrow=none;endArrow=open;endSize=12;exitX=0.5;exitY=1;entryX=0.5;entryY=0;" edge="1" parent="1" source="9" target="5">
          <mxGeometry relative="1" as="geometry">
            <Array as="points" />
          </mxGeometry>
        </mxCell>
        <mxCell id="13" value="utiliza" style="curved=1;startArrow=none;endArrow=open;endSize=12;exitX=0.5;exitY=1;entryX=0.5;entryY=0;" edge="1" parent="1" source="5" target="2">
          <mxGeometry relative="1" as="geometry">
            <Array as="points" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
