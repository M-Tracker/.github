# Mistake Tracker (Kotlin)
This app is designed to help users log, analyze, and learn from their mistakes, providing valuable insights to prevent repeating them in the future.

## Key Technologies:                                                                 
- MVVM Architecture
- Room (Local Database)
- Retrofit (API Calls, JWT Auth)
- Dependency Injection (Dagger Hilt)
- Coroutines
- Services (Data Sync)
- Broadcast Receiver (Monitoring Internet Connection)
- RecyclerView
- WorkManager (To Schedule Data Sync)
- Jetpack Compose
- LiveData

## Server Side: 
- Spring Boot (RESTful APIs)
- PostgreSQL
- AWS
- JWT authentication
  
## Key Features: 
- **Offline and Online Functionality:** Log your mistakes and insights offline, and sync data automatically when you are back online.
- **User Authentication:** Secure login with JWT-based authentication to keep your data safe.
- **Data Analysis:** Analyze trends and patterns in your mistakes to improve and avoid similar errors in the future.
  
<p align="center">
<img src= "https://github.com/user-attachments/assets/38bee7e4-2243-4ee9-9036-ac8882e4fb20" width="100%" />
</p>
## Key Features
[Uploading Untitled Diagram-2.drawio…]()

<p align="center">
    <img src="https://github.com/user-attachments/assets/d9064320-fff6-4ac5-8e48-e7d61eb0aef2" width="33%" />
  <img src="https://github.com/user-attachments/assets/78de1011-5111-4511-89f6-0e381a8df287" width="33%" />
    <img src="https://github.com/user-attachments/assets/20f5e37c-1187-435f-9488-62fc13da008b" width="33%" />

</p><mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/16.2 Safari/605.1.15" version="24.7.10">
  <diagram name="Page-1" id="IeYxXTgYX528ULRhNPdr">
    <mxGraphModel dx="1687" dy="973" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-69" value="&lt;font color=&quot;#ffffff&quot;&gt;Repo&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=0CS8ukh2PRLw;" vertex="1" parent="1">
          <mxGeometry x="850" y="201" width="125" height="70" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-70" value="&lt;font style=&quot;font-size: 14px;&quot; color=&quot;#ffffff&quot;&gt;Mistake Database (Local)&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=djU8IUwcRoLz;" vertex="1" parent="1">
          <mxGeometry x="1188" y="106" width="173" height="60" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-71" value="&lt;font style=&quot;font-size: 14px;&quot; color=&quot;#ffffff&quot;&gt;Server Database (Retrofit Services)&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=njU8mHQbahsz;" vertex="1" parent="1">
          <mxGeometry x="1190" y="31" width="173" height="60" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-72" value="Ma" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#cc4e00;strokeOpacity=100;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=zmU8eK0.AfIt;" vertex="1" parent="1">
          <mxGeometry x="180" y="106" width="150" height="65" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-73" value="" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#cc4e00;strokeOpacity=100;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=KmU8Yo7R48ye;" vertex="1" parent="1">
          <mxGeometry x="30" y="321" width="170" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-74" value="&lt;font style=&quot;font-size: 14px;&quot; color=&quot;#ffffff&quot;&gt;Report Fragment&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#cc4e00;strokeOpacity=100;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=YmU8_zEoioCu;" vertex="1" parent="1">
          <mxGeometry x="320" y="321" width="175" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-75" value="&lt;div style=&quot;display: flex; justify-content: center; text-align: center; align-items: baseline; font-size: 0; line-height: 1.25;margin-top: -2px;&quot;&gt;&lt;span&gt;&lt;font color=&quot;#ffffff&quot;&gt;&lt;span style=&quot;font-size:16.7px;&quot;&gt;Module&lt;/span&gt;&lt;span style=&quot;font-size: 16px;&quot;&gt; &lt;/span&gt;&lt;/font&gt;&lt;/span&gt;&lt;/div&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=13;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=tnU8gPL0kq-U;" vertex="1" parent="1">
          <mxGeometry x="930" y="63.5" width="115" height="60" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-76" value="&lt;font color=&quot;#ffffff&quot; style=&quot;font-size: 14px;&quot;&gt;Dagger Hilt&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=3.8;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=FpU8jXmHCyCQ;" vertex="1" parent="1">
          <mxGeometry x="610" y="63.5" width="120" height="57.5" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-77" value="&lt;font style=&quot;font-size: 14px;&quot; color=&quot;#ffffff&quot;&gt;MistakeViewModel&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=UqU8ajj4yd8N;" vertex="1" parent="1">
          <mxGeometry x="630" y="391" width="180" height="60" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-78" value="&lt;font style=&quot;font-size: 14px;&quot; color=&quot;#ffffff&quot;&gt;Retrofit Services&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=0TU8snuJkM7z;" vertex="1" parent="1">
          <mxGeometry x="1190" y="250" width="120" height="55" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-79" value="&lt;font style=&quot;font-size: 14px;&quot; color=&quot;#f2f2f2&quot;&gt;MistakeDao&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=yWU8q-5SR1Yk;" vertex="1" parent="1">
          <mxGeometry x="1190" y="176.5" width="120" height="55" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-80" value="&lt;font style=&quot;font-size: 14px;&quot; color=&quot;#ffffff&quot;&gt;RecyclerViewAdapter&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=9;strokeColor=#unset;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#unset;strokeWidth=NaN;lucidId=CnV89Ud6Ssl7;" vertex="1" parent="1">
          <mxGeometry x="30" y="436" width="195" height="60" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-81" value="" style="html=1;jettySize=18;whiteSpace=wrap;fontSize=13;strokeColor=#3a414a;strokeOpacity=100;strokeWidth=1.5;rounded=1;arcSize=12;edgeStyle=orthogonalEdgeStyle;startArrow=none;endArrow=block;endFill=1;entryX=0.866;entryY=-0.012;entryPerimeter=0;lucidId=moV8POZQLJGJ;" edge="1" parent="1" target="kxy4rHE0W6nbuhuCCXCy-73">
          <mxGeometry width="100" height="100" relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="255" y="251" />
              <mxPoint x="177" y="251" />
            </Array>
            <mxPoint x="255" y="172" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-82" value="" style="html=1;jettySize=18;whiteSpace=wrap;fontSize=13;strokeColor=#3a414a;strokeOpacity=100;strokeWidth=1.5;rounded=1;arcSize=12;edgeStyle=orthogonalEdgeStyle;startArrow=none;endArrow=block;endFill=1;entryX=0.14;entryY=-0.012;entryPerimeter=0;lucidId=zoV8pie1mmAN;" edge="1" parent="1" target="kxy4rHE0W6nbuhuCCXCy-74">
          <mxGeometry width="100" height="100" relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="260" y="251" />
              <mxPoint x="345" y="251" />
            </Array>
            <mxPoint x="260" y="171" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-83" value="&amp;nbsp; &lt;font face=&quot;Times New Roman&quot; style=&quot;font-size: 14px;&quot;&gt;Host&lt;/font&gt;" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;spacing=3.8;strokeOpacity=0;fillOpacity=0;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#ffffff;strokeWidth=NaN;lucidId=OpV8t5CayEsU;" vertex="1" parent="1">
          <mxGeometry x="225" y="191" width="105" height="26" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-84" value="" style="html=1;jettySize=18;whiteSpace=wrap;fontSize=13;strokeColor=#635dff;strokeOpacity=100;strokeWidth=1.5;rounded=1;arcSize=12;edgeStyle=orthogonalEdgeStyle;startArrow=none;endArrow=block;endFill=1;exitX=1.005;exitY=0.5;exitPerimeter=0;entryX=-0.004;entryY=0.5;entryPerimeter=0;lucidId=4rV8igu7gPVG;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-72" target="kxy4rHE0W6nbuhuCCXCy-77">
          <mxGeometry width="100" height="100" relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="510" y="139" />
              <mxPoint x="510" y="421" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-85" value="" style="html=1;jettySize=18;whiteSpace=wrap;fontSize=13;strokeColor=#635dff;strokeOpacity=100;strokeWidth=1.5;rounded=1;arcSize=12;edgeStyle=orthogonalEdgeStyle;startArrow=none;endArrow=block;endFill=1;exitX=0.5;exitY=1.012;exitPerimeter=0;lucidId=isV8CmAHD_e0;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-74">
          <mxGeometry width="100" height="100" relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="383" y="419" />
            </Array>
            <mxPoint x="555" y="419" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-86" value="" style="html=1;jettySize=18;whiteSpace=wrap;fontSize=13;strokeColor=#635dff;strokeOpacity=100;strokeWidth=1.5;rounded=1;arcSize=12;edgeStyle=orthogonalEdgeStyle;startArrow=none;endArrow=block;endFill=1;exitX=1.004;exitY=0.5;exitPerimeter=0;lucidId=rsV8jtT9iVu~;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-73">
          <mxGeometry width="100" height="100" relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="240" y="331" />
              <mxPoint x="240" y="421" />
              <mxPoint x="375" y="421" />
            </Array>
            <mxPoint x="383" y="419" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-87" value="uses" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;fontColor=#635dff;spacing=3.8;strokeOpacity=0;fillOpacity=0;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#ffffff;strokeWidth=NaN;lucidId=wwV8J8.~aYrc;" vertex="1" parent="1">
          <mxGeometry x="345" y="106" width="180" height="45" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-88" value="uses" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;fontColor=#635dff;align=left;spacing=3.8;verticalAlign=top;strokeColor=none;fillOpacity=0;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#ffffff;strokeWidth=0;lucidId=YwV8xsxZP1G8;" vertex="1" parent="1">
          <mxGeometry x="270" y="391" width="43" height="28" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-89" value="uses" style="html=1;overflow=block;blockSpacing=1;whiteSpace=wrap;fontSize=16.7;fontColor=#635dff;align=left;spacing=3.8;verticalAlign=top;strokeColor=none;fillOpacity=0;rounded=1;absoluteArcSize=1;arcSize=9;fillColor=#ffffff;strokeWidth=0;lucidId=YwV8ozsO7Wkk;" vertex="1" parent="1">
          <mxGeometry x="437" y="391" width="43" height="28" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-90" value="" style="html=1;jettySize=18;whiteSpace=wrap;fontSize=13;strokeColor=#3a414a;strokeOpacity=100;strokeWidth=0.8;rounded=1;arcSize=12;edgeStyle=orthogonalEdgeStyle;startArrow=none;endArrow=block;endFill=1;exitX=1.004;exitY=0.5;exitPerimeter=0;entryX=0.5;entryY=1.008;entryPerimeter=0;lucidId=_DV8y_HJknG8;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-77" target="kxy4rHE0W6nbuhuCCXCy-69">
          <mxGeometry width="100" height="100" relative="1" as="geometry">
            <Array as="points" />
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-91" value="&lt;font face=&quot;Helvetica&quot; style=&quot;font-size: 14px;&quot;&gt;MainActivity&lt;/font&gt;" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;fontColor=#FFFFFF;" vertex="1" parent="1">
          <mxGeometry x="205" y="123.5" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-92" value="&lt;span style=&quot;text-align: start; white-space: normal; caret-color: rgb(0, 0, 0);&quot; data-lucid-content=&quot;{&amp;quot;t&amp;quot;:&amp;quot;MistakeList Fragment&amp;quot;,&amp;quot;m&amp;quot;:[{&amp;quot;s&amp;quot;:0,&amp;quot;n&amp;quot;:&amp;quot;fsp&amp;quot;,&amp;quot;v&amp;quot;:&amp;quot;ss_presetShapeStyle1_textStyle&amp;quot;,&amp;quot;e&amp;quot;:20},{&amp;quot;s&amp;quot;:0,&amp;quot;n&amp;quot;:&amp;quot;fsp2&amp;quot;,&amp;quot;v&amp;quot;:&amp;quot;ss_presetShapeStyle1_textStyle&amp;quot;,&amp;quot;e&amp;quot;:20},{&amp;quot;s&amp;quot;:0,&amp;quot;n&amp;quot;:&amp;quot;s&amp;quot;,&amp;quot;v&amp;quot;:22.22222222222222,&amp;quot;e&amp;quot;:20}]}&quot; data-lucid-type=&quot;application/vnd.lucid.text&quot;&gt;&lt;font face=&quot;Helvetica&quot; style=&quot;font-size: 14px;&quot;&gt;MistakeList Fragment&lt;/font&gt;&lt;/span&gt;" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;fontColor=#FFFFFF;" vertex="1" parent="1">
          <mxGeometry x="35" y="326" width="160" height="30" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-93" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.57;entryY=0.957;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-80" target="kxy4rHE0W6nbuhuCCXCy-73">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-94" value="" style="endArrow=classic;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-76" target="kxy4rHE0W6nbuhuCCXCy-75">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="670" y="281" as="sourcePoint" />
            <mxPoint x="720" y="231" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-95" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=1;exitDx=0;exitDy=0;strokeColor=#CC6600;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-76">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="670" y="131" as="sourcePoint" />
            <mxPoint x="850" y="241" as="targetPoint" />
            <Array as="points">
              <mxPoint x="670" y="241" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-96" value="" style="endArrow=classic;html=1;rounded=0;entryX=0;entryY=0;entryDx=0;entryDy=0;exitX=0.158;exitY=0.989;exitDx=0;exitDy=0;exitPerimeter=0;strokeColor=#CC6600;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-76" target="kxy4rHE0W6nbuhuCCXCy-77">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="630" y="131" as="sourcePoint" />
            <mxPoint x="720" y="231" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-97" value="" style="endArrow=classic;html=1;rounded=0;entryX=-0.025;entryY=0.382;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.75;exitY=1;exitDx=0;exitDy=0;fontColor=#CC6600;labelBackgroundColor=#FF8000;strokeColor=#CC6600;" edge="1" parent="1" source="kxy4rHE0W6nbuhuCCXCy-76">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="702" y="141" as="sourcePoint" />
            <mxPoint x="1189" y="282.01" as="targetPoint" />
            <Array as="points">
              <mxPoint x="700" y="181" />
              <mxPoint x="1082" y="181" />
              <mxPoint x="1082" y="281" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-98" value="" style="endArrow=classic;html=1;rounded=0;entryX=-0.022;entryY=0.539;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.955;exitY=0.954;exitDx=0;exitDy=0;exitPerimeter=0;strokeColor=#009900;" edge="1" parent="1" target="kxy4rHE0W6nbuhuCCXCy-79" source="kxy4rHE0W6nbuhuCCXCy-75">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="1048" y="121" as="sourcePoint" />
            <mxPoint x="1180" y="171" as="targetPoint" />
            <Array as="points">
              <mxPoint x="1080" y="121" />
              <mxPoint x="1120" y="121" />
              <mxPoint x="1120" y="206" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-99" value="" style="endArrow=classic;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=0.976;exitY=0.788;exitDx=0;exitDy=0;exitPerimeter=0;strokeColor=#00CC00;" edge="1" parent="1" target="kxy4rHE0W6nbuhuCCXCy-70" source="kxy4rHE0W6nbuhuCCXCy-75">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="1050" y="111" as="sourcePoint" />
            <mxPoint x="1180" y="111" as="targetPoint" />
            <Array as="points">
              <mxPoint x="1160" y="111" />
              <mxPoint x="1160" y="136" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-100" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.997;exitY=0.331;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.001;entryY=0.824;entryDx=0;entryDy=0;entryPerimeter=0;strokeColor=#00994D;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="1045.0049999999999" y="90.77999999999996" as="sourcePoint" />
            <mxPoint x="1190.523" y="80.43999999999994" as="targetPoint" />
            <Array as="points">
              <mxPoint x="1140.35" y="91" />
              <mxPoint x="1140.35" y="81" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-102" value="&lt;span style=&quot;caret-color: rgb(0, 0, 0); color: rgb(0, 0, 0); font-style: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; text-align: center; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(251, 251, 251); text-decoration: none; float: none; display: inline !important;&quot;&gt;&lt;font face=&quot;Helvetica&quot; style=&quot;font-size: 14px;&quot;&gt;provides &amp;nbsp;dependencies for&lt;/font&gt;&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="740" y="66" width="230" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-104" value="&lt;span style=&quot;caret-color: rgb(0, 0, 0); color: rgb(0, 0, 0); font-style: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; text-align: center; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(251, 251, 251); text-decoration: none; float: none; display: inline !important;&quot;&gt;&lt;font face=&quot;Helvetica&quot; style=&quot;font-size: 14px;&quot;&gt;injects&lt;/font&gt;&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="720" y="210" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-105" value="&lt;span style=&quot;caret-color: rgb(0, 0, 0); color: rgb(0, 0, 0); font-style: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; text-align: center; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(251, 251, 251); text-decoration: none; float: none; display: inline !important;&quot;&gt;&lt;font face=&quot;Helvetica&quot; style=&quot;font-size: 14px;&quot;&gt;injects&lt;/font&gt;&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="790" y="151" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-108" value="&lt;div style=&quot;text-align: center;&quot;&gt;&lt;font face=&quot;Helvetica&quot; style=&quot;font-size: 14px;&quot;&gt;provides&lt;/font&gt;&lt;/div&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="1055.35" y="66" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-109" value="&lt;span style=&quot;caret-color: rgb(0, 0, 0); color: rgb(0, 0, 0); font-style: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; text-align: center; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(251, 251, 251); text-decoration: none; float: none; display: inline !important;&quot;&gt;&lt;font face=&quot;Times New Roman&quot; style=&quot;font-size: 14px;&quot;&gt;provides&lt;/font&gt;&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="1055" y="116" width="100" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-110" value="&lt;span style=&quot;caret-color: rgb(0, 0, 0); color: rgb(0, 0, 0); font-size: 14px; font-style: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; text-align: center; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(251, 251, 251); text-decoration: none; float: none; display: inline !important;&quot;&gt;&lt;font face=&quot;Helvetica&quot;&gt;provides&lt;/font&gt;&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="1055" y="91" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-111" value="&lt;span style=&quot;caret-color: rgb(0, 0, 0); color: rgb(0, 0, 0); font-size: 14px; font-style: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; text-align: center; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(251, 251, 251); text-decoration: none; float: none; display: inline !important;&quot;&gt;&lt;font face=&quot;Helvetica&quot;&gt;interacts with&lt;/font&gt;&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="920" y="356" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-115" value="&lt;span style=&quot;caret-color: rgb(0, 0, 0); color: rgb(0, 0, 0); font-style: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; text-align: center; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(251, 251, 251); text-decoration: none; float: none; display: inline !important;&quot;&gt;&lt;font face=&quot;Helvetica&quot; style=&quot;font-size: 14px;&quot;&gt;injects&lt;/font&gt;&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="640" y="265" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="kxy4rHE0W6nbuhuCCXCy-117" value="&lt;div style=&quot;text-align: center;&quot;&gt;&lt;span style=&quot;font-size: 17px;&quot;&gt;used by&lt;/span&gt;&lt;/div&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="60" y="379" width="70" height="40" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a38fcfad-1ef2-4343-9afb-52d08ae4ffb5" width="40%" />
  <img src="https://github.com/user-attachments/assets/9e174735-788d-4332-8c8f-90df367caf90" width="40%" />
</p>

