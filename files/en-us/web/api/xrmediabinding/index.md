---
title: XRMediaBinding
slug: Web/API/XRMediaBinding
page-type: web-api-interface
tags:
  - API
  - Interface
  - Reference
  - WebXR
  - XR
  - AR
  - VR
  - Experimental
browser-compat: api.XRMediaBinding
---

{{APIRef("WebXR Device API")}} {{secureContext_header}}{{SeeCompatTable}}

The **`XRMediaBinding`** interface is used to create layers that display the content of an {{domxref("HTMLVideoElement")}}.

> **Note:**
> Only the video frames will be displayed in the layer. Video controls need to be implemented separately and must be drawn in another layer.

## Constructor

- {{domxref("XRMediaBinding.XRMediaBinding", "XRMediaBinding()")}} {{Experimental_Inline}}
  - : Creates a new `XRMediaBinding` object for the specified {{domxref("XRSession")}}.

## Methods

- {{domxref("XRMediaBinding.createCylinderLayer()")}} {{Experimental_Inline}}
  - : Returns an {{domxref("XRCylinderLayer")}} object bound to an {{domxref("HTMLVideoElement")}}.
- {{domxref("XRMediaBinding.createEquirectLayer()")}} {{Experimental_Inline}}
  - : Returns an {{domxref("XREquirectLayer")}} object bound to an {{domxref("HTMLVideoElement")}}.
- {{domxref("XRMediaBinding.createQuadLayer()")}} {{Experimental_Inline}}
  - : Returns an {{domxref("XRQuadLayer")}} object bound to an {{domxref("HTMLVideoElement")}}.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("HTMLVideoElement")}}
- {{domxref("XRCylinderLayer")}}, {{domxref("XREquirectLayer")}}, {{domxref("XRQuadLayer")}}
