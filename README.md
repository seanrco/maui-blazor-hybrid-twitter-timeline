# MAUI Blazor Hybrid Twitter Timeline

## Description

Would like to include a Twitter Timeline on a MAUI Blazor Hybrid app I am working on. This repro is a simple example of how I am trying to include the Twitter Timeline using Microsoft.JSInterop on the main index page. See code links below:

https://github.com/seanrco/maui-blazor-hybrid-twitter-timeline/blob/55ea8fdf1025bb10b50eb93d0c818ab72c1edf2f/MauiBlazorTwitterTest/Pages/Index.razor#L6

https://github.com/seanrco/maui-blazor-hybrid-twitter-timeline/blob/55ea8fdf1025bb10b50eb93d0c818ab72c1edf2f/MauiBlazorTwitterTest/Shared/TwitterTimeline.razor#L1

## Issue

The issue I am running into is on iPhone iOS the Twitter Timeline is launching in the external default browser and will not load directly in the app. See screenshots below:

![dyDkFo8R3o](https://user-images.githubusercontent.com/582014/236707252-6f569cb6-8bea-45b4-af5d-f7f22c132da5.png)

Appears to be working correctly when loading in VS Android Emulator:

![0fr3GY3ipo](https://user-images.githubusercontent.com/582014/226217252-8cbaf5b8-78f3-4499-9e4f-1adbe175f26f.png)

