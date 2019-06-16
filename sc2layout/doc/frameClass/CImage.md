___

## AdjustmentColor

TBD

## AlphaChannel

TBD

## AlphaChannelMultiply

TBD

## AlphaLayer

TBD

## AnimColumns

TBD

## AnimCount

TBD

## AnimDuration

TBD

## AnimIndex

TBD

## AnimTime

TBD

## Animating

TBD

## AutoSizeLayer

TBD

## BlendMode

TBD

## ColorAdjustMode

TBD

## DarkAdjustColor

TBD

## DesaturateOnDisable

TBD

## Desaturated

TBD

## DesaturationColor

TBD

## EndAngle

TBD

## EndAngleOffset

TBD

## GlowColor

TBD

## HSkew

TBD

## HasSkew

TBD

## ImageMaskTexture

TBD

## LayerAlpha

TBD

## LayerColor

TBD

## LayerCount

TBD

## LayerVisible

TBD

## LightAdjustColor

TBD

## LoopingAnim

TBD

## ManagedAnim

TBD

## OnDisableDesaturationColor

TBD

## PixelTextureCoords

TBD

## Rotation

TBD

## RotationPosition

TBD

## ScaleHeightToTexture

TBD

## ScaleWidthToTexture

TBD

## ScaleWithTexCoords

TBD

## StartAngle

TBD

## StateCount

TBD

## StateIndex

TBD

## SubpixelRendering

TBD

## Texture

TBD

## TextureCoordRotation

TBD

## TextureCoords

TBD

## TextureType

If a texture is used as a border or filling of a progressbar for example, the texture is broken up into pieces (Edges, Corners and Middle section). This makes seamless scaling along the horizontal or veritcal direction possible. If the image should just show the texture as it is then this value does not need to be set.

            None: unknown
            Normal: The image is not adjusted in any way for displaying.
            Border: The image is chopped up and put together again as displayed here: Border Texture explained
            HorizontalBorder: Another way the border is chopped up and put together again.
            EndCap: Another way the border is chopped up and put together again.
            NineSlice: Image is split into nine quadrants and put together with correct scaling. Corners wont scale only top, left, bottom, right and center
            Circular: unknown
            
example:
```xml
<TextureType val="Border"/>
```

https://sc2mapster.gamepedia.com/UI/Frame_Properties/TextureType

## Tiled

TBD

## VSkew

TBD

## WrapUV

TBD
