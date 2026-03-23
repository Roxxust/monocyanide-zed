# monocyanide-zed
monocyanide black theme inspired by the sublime text 3.2.2 skin: https://github.com/centril/sublime-monocyanide-colorscheme
<br/>
place in <code>C:\Users\\%USERNAME%\AppData\Roaming\Zed\themes</code>
<br/>
### Primary Syntax Colors

| Color | Preview | Hex | Usage |
|-------|---------|-----|-------|
| **Lime** | <img src="https://placehold.co/20x20/aee837/aee837.png" width="20" height="20" /> | `#aee837` | Functions, accents, success, active line numbers, brackets (**bold**) |
| **Pink** | <img src="https://placehold.co/20x20/ff4083/ff4083.png" width="20" height="20" /> | `#ff4083` | Keywords, operators, tags, function calls, errors |
| **Cyan** | <img src="https://placehold.co/20x20/66d9ef/66d9ef.png" width="20" height="20" /> | `#66d9ef` | Types (*italic*+**bold**), links, info, punctuation, lifetimes (*italic*) |
| **Orange** | <img src="https://placehold.co/20x20/fd971f/fd971f.png" width="20" height="20" /> | `#fd971f` | Constructors (**bold**), hints, selections, warnings, delimiters |
| **Purple** | <img src="https://placehold.co/20x20/967EFB/967EFB.png" width="20" height="20" /> | `#967EFB` | Parameters, variants, modified (git) |
| **Yellow** | <img src="https://placehold.co/20x20/e6db74/e6db74.png" width="20" height="20" /> | `#e6db74` | Strings, regex quantifiers |
| **Magenta** | <img src="https://placehold.co/20x20/be84ff/be84ff.png" width="20" height="20" /> | `#be84ff` | Constants, booleans, numbers, string escapes |
| **White** | <img src="https://placehold.co/20x20/ffffff/000000.png" width="20" height="20" /> | `#ffffff` | Variables (*italic*), properties (normal) |
| **Gray** | <img src="https://placehold.co/20x20/A9A9A9/A9A9A9.png" width="20" height="20" /> | `#A9A9A9` | Comments |

### Key Syntax Distinctions

| Token | Color | Style | Example |
|-------|-------|-------|---------|
| `variable` | White | *italic* | `let my_var = 5;` |
| `property` | White | normal | `obj.property` |
| `type` | Cyan | *italic* **+bold** | `struct MyType` |
| `type.builtin` | Orange | *italic* | `String`, `i32` |
| `function.definition` | Lime | normal | `fn my_func()` |
| `function.call` | Pink | normal | `my_func()` |
| `keyword` | Pink | weight 500 | `if`, `let`, `fn` |
| `string` | Yellow | normal | `"hello"` |
| `comment` | Gray | normal | `// comment` |
| `attribute` | Lime | oblique | `#[derive(Debug)]` |
| `lifetime` | Cyan | *italic* | `'a` |

---

### Theme Variants

| Theme | Appearance | Background | `background.appearance` | Preview |
|-------|------------|------------|------------------------|---------|
| **Dark** | `dark` | `#000000` | `opaque` | <img src="https://placehold.co/40x20/000000/ffffff.png" width="40" height="20" /> |
| **Light** | `light` | `#5f5f5f` | `opaque` | <img src="https://placehold.co/40x20/5f5f5f/ffffff.png" width="40" height="20" /> |
| **Dark Glass** | `dark` | `#0808084d` | `transparent` | <img src="https://placehold.co/40x20/0808084d/ffffff.png" width="40" height="20" /> |
| **Dark Blurred** | `dark` | `#00000000` | `blurred` | <img src="https://placehold.co/40x20/00000000/ffffff.png" width="40" height="20" /> |
| **Light Glass** | `light` | `#f0f0f04d` | `transparent` | <img src="https://placehold.co/40x20/f0f0f04d/000000.png" width="40" height="20" /> |
| **Light Blurred** | `light` | `#00000000` | `blurred` | <img src="https://placehold.co/40x20/00000000/000000.png" width="40" height="20" /> |

### Variant Differences Summary

| Element | Dark/Light (Opaque) | Glass/Blurred (Transparent) |
|---------|---------------------|----------------------------|
| Editor Background | Solid color | 30-80% alpha |
| Borders | Solid (`#333333` / `#a0a0a0`) | +66% alpha |
| Vim Mode Indicators | Solid colors | +80% alpha |
| Selections | `#fd971f99` | `#fd971f33` |
| Best For | Standard use | macOS vibrancy / blurred desktops |

> **Note:** All 6 themes share **identical syntax highlighting** colors and styles. Only UI element backgrounds, borders, and alpha channels differ.

---

### UI Accent Colors

| Element | Preview | Color |
|---------|---------|-------|
| Active Line Number | <img src="https://placehold.co/20x20/aee837/aee837.png" width="20" height="20" /> | `#aee837` (Lime) |
| Scrollbar Thumb Hover | <img src="https://placehold.co/20x20/fd971f/fd971f.png" width="20" height="20" /> | `#fd971f` (Orange) |
| Error | <img src="https://placehold.co/20x20/ff4083/ff4083.png" width="20" height="20" /> | `#ff4083` (Pink) |
| Warning | <img src="https://placehold.co/20x20/e6db74/e6db74.png" width="20" height="20" /> | `#e6db74` (Yellow) |
| Info | <img src="https://placehold.co/20x20/66d9ef/66d9ef.png" width="20" height="20" /> | `#66d9ef` (Cyan) |
| Success | <img src="https://placehold.co/20x20/aee837/aee837.png" width="20" height="20" /> | `#aee837` (Lime) |
| Modified (Git) | <img src="https://placehold.co/20x20/967EFB/967EFB.png" width="20" height="20" /> | `#967EFB` (Purple) |
| Selection Background | <img src="https://placehold.co/20x20/fd971f99/fd971f99.png" width="20" height="20" /> | `#fd971f99` (Orange + alpha) |


# Previews:
<br/>
dark:
<br/>
<img width="1920" height="1079" alt="Zed_Y6jkoUnj6g" src="https://github.com/user-attachments/assets/0045b2d1-f48c-4e56-bfd4-f8e3d4709678" />
<br/>
dark blurred:
<br/>
<img width="1920" height="1079" alt="Zed_Ri3wPdFPKg" src="https://github.com/user-attachments/assets/c3a4ba0b-d796-4780-88c0-4a31084bfb3a" />
<br/>
dark glass:
<br/>
<img width="1920" height="1079" alt="Zed_WKGVoyTlyH" src="https://github.com/user-attachments/assets/b7b0c8cc-3d05-49bc-b1e4-b2b4ee103252" />
<br/>
light:
<br/>
<img width="1920" height="1079" alt="Zed_t1V90fbfta" src="https://github.com/user-attachments/assets/8dbaf8a2-c678-43ed-a15a-082ccd60fe42" />
<br/>
light blurred:
<br/>
<img width="1920" height="1079" alt="Zed_tKuDQNgPHD" src="https://github.com/user-attachments/assets/89e638d5-a9a0-4835-86c9-e4fbe64b1bd0" />
<br/>
light glass:
<br/>
<img width="1920" height="1079" alt="Zed_VoJmyyHPEI" src="https://github.com/user-attachments/assets/6c99acd8-4a50-4344-bc4d-0212d4c9748e" />
<br/>
<br/>
<br/>
skins are mostly done but may make some tweaks, may be missing some things or have things that don't actually do anything.. the dark blue is a placeholder to make it stand out to see where it needs to be changed.  some things like git/ai mode stuff might be off scheme-wise as i've not tested them extensively. 
<br/> comments are what i could make of them visually, any //? are ones i did not notice any direct change or did not find what it changed.  //self indicates the name of the field is self explanitory. 
