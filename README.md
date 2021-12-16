<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/438844465/21.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1053365)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# MaskedInput for Blazor - How to create an input element for a card number, expiry date, and CVV

This example demonstrates how to show an input element that contains fields for a credit card number, expiration date, and card verification value (CVV).

![Input element for a card number, expiry date, and CVV](./Sample.JPG)

## Overview

The [DxMaskedInput](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxMaskedInput-1) component is a text editor that supports [masks](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxMaskedInput-1.Mask). Place multiple **DxMaskedInput** components in a div container to create fields for a card number, expiration date, and CVV. Use the [InputCssClass](https://docs.devexpress.com/Blazor/DevExpress.Blazor.Base.DxInputDataEditorBase-1.InputCssClass) property to remove their borders and display these components as a single input element.

<!-- default file list -->

## Files to Look At

- [Index.razor](./CS/BlazorServerApp/Pages/Index.razor)

<!-- default file list end -->

## Documentation

- [Apply a Mask](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxMaskedInput-1#apply-a-mask)
- [Masks](https://docs.devexpress.com/Blazor/402513/data-editors/masks)

## More Examples

- [DevExpress Blazor - How to localize components](https://github.com/DevExpress-Examples/localize-devexpress-blazor-components)