# Iosevka Custom Build (Iosevka Mayukai)

This repository contains .ttf files from the result of custom build original Iosevka Font. All weight variant is available, from Regular, Italic, weight 100 until weight 900, and full bold. This custom build also support all font ligature from original Iosevka Build. We're using Iosevka SS04 (Menlo), Iosevka SS07 (Monaco), Iosevka SS09 (Source Code Pro), Iosevka SS12 (Ubuntu Mono), Iosevka SS14 (Jetbrains Mono), Hack Font Style, and Nerd Font patcher to make this Iosevka Custom Build, named Iosevka Mayukai.

## Font Variants

Iosevka Mayukai Font is font with ligature suitable for programming font in text editor and IDE. Iosevka Mayukai have some variants. There are Iosevka Mayukai Original, Iosevka Mayukai Serif, Iosevka Mayukai Codepro, Iosevka Mayukai Monolite, and Iosevka Mayukai Sonata. 

Iosevka Mayukai Original is variant with combination of Iosevka SS04 (Menlo), Iosevka SS07 (Monaco) and Iosevka SS12 (Ubuntu Mono) variant.

Iosevka Mayukai Serif is variant with combination of Iosevka SS09 (Source Code Pro), Iosevka SS12 (Ubuntu Mono), Iosevka SS14 (Jetbrains Mono), and Hack Font Style. 

Iosevka Mayukai Codepro is variant with combination from Iosevka SS15 (IBM Plex Mono) and Iosevka SS16 (PT Mono).

Iosevka Mayukai Monolite is variant from combination of Iosevka SS16 (PT Mono), Iosevka SS17 (Recursive Mono), and Iosevka SS05 (Fira Mono) with complete ligature support.

Iosevka Mayukai Sonata is variant from combination of Iosevka SS18 (Input Mono) and Iosevka SS09 (Source Code Pro).

Each variant have ligature support, and also patched with Glyph from [Nerd Font Tools by Ryanoasis](https://github.com/ryanoasis/nerd-fonts). These variant are Suitable for IDE, text editor, Vim, Emacs, terminal theme with powerline and glyph icons, such as OhMyZSH Powerlevel10K, Starship, Spaceship, and many more. Variants with glyph use filename **"Iosevka Mayukai xxxxx Nerd Font Complete Windows Compatible"**.

Webfont type is available in each variant. Can be used for styling web apps font.

## Font Sample Specimen

Here some screenshot for font speciment that can be see below.

### Iosevka Mayukai Original - Regular Version

![Gambar Demo 1](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-original.png)

### Iosevka Mayukai Original - Italic Version

![Gambar Demo 2](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-original-italic.png)

### Iosevka Mayukai Serif - Regular Version

![Gambar Demo Serif 1](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-serif.png)

### Iosevka Mayukai Serif - Italic Version

![Gambar Demo Serif 2](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-serif-italic.png)

### Iosevka Mayukai Codepro - Regular Version

![Gambar Demo Codepro 1](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-codepro.png)

### Iosevka Mayukai Codepro - Italic Version

![Gambar Demo Codepro 2](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-codepro-italic.png)

### Iosevka Mayukai Monolite - Regular Version

![Gambar Demo Monolite](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-monolite.png)

### Iosevka Mayukai Monolite - Italic Version

![Gambar Monolite Italic](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-monolite-italic.png)

### Iosevka Mayukai Sonata - Regular Version

![Gambar Demo Sonata](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-sonata.png)
### Iosevka Mayukai Sonata - Italic Version

![Gambar Sonata Italic](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/sampel-sonata-italic.png)

## Download and Installation

Quit your editor/program. Download the fonts from [Github Release Page](https://github.com/Iosevka-Mayukai/Iosevka-Mayukai/releases) in this repository. Unzip and open the folder **/iosevka-mayukai**.

- **Instruction for Linux** : Copy the TTF files to your fonts directory, usually in your Home directory `~/.local/share/fonts/` . And then run Run `sudo fc-cache -f -v`. For refreshing Font Cache in your sistem.
- **[Instructions for macOS](http://support.apple.com/kb/HT2509)**
  - Right click on .ttf font file, and Install it with FontBook App.
- **Instructions for Windows** : Download the fonts from the [Releases Page](https://github.com/Iosevka-Mayukai/Iosevka-Mayukai/releases), select the font files and right click, then hit "Install".
  - On Windows 10 1809 or newer the default font installation is per-user, and it may cause compatibility issues for some applications, mostly written in Java. To cope with this, right click and select "Install for all users" instead. [Ref.](https://youtrack.jetbrains.com/issue/JRE-1166?p=IDEA-200145)

## Settings for Your Code Editor

Open your text editor font settings, for example in VS Code / VS Codium Text Editor. Go to Font Settings, and write variant name in Font Selection. Save and reload your code editor. If it doesn't work, then try write **"Iosevka-Mayukai-<variant name>"** in Font selection settings.

If you use Iosevka Mayukai Original, you should write **"Iosevka Mayukai Original"** in text editor font settings. For macOS or Windows, try write **"Iosevka-Mayukai-Original"** if the first one is fail.

![Gambar Setting 1](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/setting-iosevka-mayukai-original.png)

For Iosevka Mayukai Serif setting, you should write **"Iosevka Mayukai Serif"** in text editor font settings. For macOS or Windows, try write **"Iosevka-Mayukai-Serif"** if the first one is fail.

![Gambar Setting 2](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/setting-iosevka-mayukai-serif.png)

If you use Iosevka Mayukai Codepro, you should write **"Iosevka Mayukai Codepro"** in text editor font settings. For macOS or Windows, try write **"Iosevka-Mayukai-Codepro"** if the first one is fail.

![Gambar Setting 3](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/setting-iosevka-mayukai-codepro.png)

For Iosevka Mayukai Monolite, you should write **"Iosevka Mayukai Monolite"** in text editor font settings. For macOS or Windows, try write **"Iosevka-Mayukai-Monolite"** if the first one is fail.

![Gambar Setting 4](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/setting-iosevka-mayukai-monolite.png)

For Iosevka Mayukai Sonata, you should write **"Iosevka Mayukai Sonata"** in text editor font settings. For macOS or Windows, try write **"Iosevka-Mayukai-Sonata"** if the first one is fail.

![Gambar Setting 4](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/setting-iosevka-mayukai-sonata.png)

### Nerd Variant

If you're using Nerd Patched Font variant, you should write **Iosevka NF** in text editor font settings. This will enable font with patched glyph and more ligature in your text editor. These variant using filename **"Iosevka Mayukai xxxxxxx Nerd Font Complete Windows Compatible"**, and placed inside **"nerd-patched-ttf"** instalation folder.

## Demo

Iosevka Mayukai Font when applied to VS Code text editor, using Iosevka Mayukai Semibold and Iosevka Mayukai Medium, or using weight 500 and weight 600. Theme that applied with this demo is VS Code [Mayukai Theme](https://marketplace.visualstudio.com/items?itemName=GulajavaMinistudio.mayukaithemevsc).

**Iosevka Mayukai Original Font**

![Gambar Demo 3](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/code_iosevkamayukai.png)

**Iosevka Mayukai Serif Font**

![Gambar Demo 4](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/code-iosevka-mayukai-serif.png)

**Iosevka Mayukai Codepro Font**

![Gambar Demo 4](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/code_iosevka_mayukai_codepro.png)

**Iosevka Mayukai Monolite Font**

![Gambar Demo 5](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/code_mayukai_monolite.png)

**Iosevka Mayukai Sonata Font**

![Gambar Demo 6](https://raw.githubusercontent.com/Iosevka-Mayukai/Iosevka-Mayukai/master/code-iosevka-mayukai-sonata.png)

## Thank You

Thank you for Belleve Invis, their developers, and contributors that making Iosevka Font happens. Don't forget check and download original Iosevka Font from here [https://github.com/be5invis/Iosevka](https://github.com/be5invis/Iosevka). You can check [Iosevka Demo Page](https://typeof.net/Iosevka/) for details.
