# Welcome to the ovgrid-landing-page wiki!

How to create a virtual world event in OVGrid

## Syntaxis

```
[tag] 
  <parameters>
[/end]
```

Examples

```
[skybox]
  <image link>
[/end]
```

```
[neonskybox]
  <top hex color>|
  <bottom hex color>|
[/end]
```

```
[ground]
  <image link>|
  <uScale>|
  <vScale>
[/end]

The default uScale & vScale is 5.0
```

```
[rain][/end]
```

```
[snow][/end]
```

```
[music]
  <position>|
  < .mp3 link>
[/end]
```

```
[text]
  <position>
  <hex color>|
  <text string>|  
[/end]
```

```
[video]
  <position>|
  < thumbnail link>|
  < .mp4 link>|
  <width>|
  <height>
[/end]
```

```
[videodome]
  <position>|
  < .mp4 link>
[/end]
```

```
[asset]
  <position>|
  <lod>|
  < .glb link>
[/end]
```

```
[portal]
  <position>|
  <label>|
  <hex color>|
  <destination>
[/end]
```

```
[qr]
  <position>|
  <link>|
[/end]
```

```
[avatar]
  <position>|
  < .png link>|
  < .glb link>|
[/end]
```

```
[sell]
    <position>|
    <ethereum address>|
    <price>|
    < .png button link>
[/end]
```