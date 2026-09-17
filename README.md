# AdwForBlur

## What is this?

This is **not a full GTK theme**.

It is simply a CSS modification that makes some GNOME interface elements more transparent.

For example, in the Nautilus file manager, the sidebar will be more transparent than the content area on the right.

## Why do I need this?

If you have used extensions such as [Blur my Shell](https://github.com/aunetx/blur-my-shell), you probably know that they can add blur effects to application windows.

The problem is that, in order to achieve a blurred background effect, you usually have to increase the transparency of the entire window, including the content inside it.

As a result, text and other UI elements inside the window also become more transparent, reducing the overall contrast and readability of the interface.

With this modification, you don't need to adjust the transparency of the entire window. The window background can be more transparent while the UI elements inside the window remain mostly unaffected.

This makes it possible to achieve more interesting blur effects without sacrificing text contrast and readability.

## Examples

> You can use extensions such as [Blur my Shell](https://github.com/aunetx/blur-my-shell) or [Liquid Glass](https://github.com/ryohsuke1231/liquid-glass) to achieve similar effects.

https://github.com/user-attachments/assets/20957cbb-8f97-43ae-9997-d3e764162333

https://github.com/user-attachments/assets/0ac22061-e8a6-421f-862c-8e53841d9137

https://github.com/user-attachments/assets/38779ad0-1555-4071-bac4-3a3fe4cc3b03

https://github.com/user-attachments/assets/4f71b882-0411-4fcb-916c-3cf466d480b5

https://github.com/user-attachments/assets/771f7f0b-a93c-43d4-b462-f13ea53eea13

https://github.com/user-attachments/assets/e31e8996-9928-451f-bd0d-6645ed5af418

https://github.com/user-attachments/assets/419e3d0b-b892-409a-973f-dd467d43a78a

https://github.com/user-attachments/assets/a387b5e3-0073-4575-a9f8-48f7f66b8b55

## Installation

1. Clone this repository.
2. Go to `~/.config/gtk-4.0`. If there is already a `gtk.css` file there, make a backup of it just in case.
3. Move the `gtk.css` file from this repository to `~/.config/gtk-4.0`.
4. Log out and log back in.

## Important

This modification is **not perfect** and is **not a full GTK theme**.

It does not work with all applications and also affects GTK3 applications.

However, you can easily customize it to your needs — just edit the `gtk.css` file!
