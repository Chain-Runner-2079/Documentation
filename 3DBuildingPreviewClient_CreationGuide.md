# Chain Runner 2079 | Content Creation Guide

Thank you for contributing to the dystopian world of **Chain Runner 2079**! This project is a free-to-play passion project fueled by community creativity.

Current **3D Building Client**:
[https://chain-runner-2079.itch.io/3d-preview-client](https://chain-runner-2079.itch.io/3d-preview-client)

## Prerequisites

Buildings are created using **Blockbench**, a free, open-source 3D modeling tool.

1. **Download:** [blockbench.net](https://www.blockbench.net)
2. **Setup:** Open the 3D Preview Client and click **"Open Dir"** to find the local model folder where your original and exported files belong.
3. **Templates:** Use `police.bbmodel` as starting point.

---

## Modeling & Naming Conventions

The engine uses specific suffixes to identify materials and light sources.

### 1. Static Structures

* **`_Mat_Base`**: Standard solid, non-emissive structures (e.g., `Wall_Mat_Base`).
* **`_Mat_White`**: Emissive surfaces for windows.

### 2. Neon Advertisements (Emissive)

Naming an element with these suffixes automatically attaches the corresponding light color:

| Color | Suffix | Example |
| --- | --- | --- |
| **Pink** | `_Ad_Pink` | `Sign_Ad_Pink` |
| **Blue** | `_Ad_Blue` | `Logo_Ad_Blue` |
| **Red** | `_Ad_Red` | `Trim_Ad_Red` |
| **Yellow** | `_Ad_Yellow` | `Top_Ad_Yellow` |

> **Note:** You are free to redesign templates entirely as long as these naming conventions are maintained.

---

## Export Settings

Export via **File -> Export -> Export glTF Model** using these settings (*Mesh data only*):

* **Format:** ASCII (glTF)
* **Model Export Scale:** `2` (default)
* **Embed Textures:** OFF
* **Export Groups as Armature:** OFF
* **Export Animations:** OFF

---

## Testing your Model

1. Export your file as `YOURNAME.gltf` into the folder opened via **"Open Dir"**.
2. In the 3D Preview Client, click **"Reload"**.
3. Select your model from the list to view it in the scene.

---

## Support & Community

* **Links:** [chainrunner2079.online](https://chainrunner2079.online)
* **Discord:** [Join our Server](https://discord.gg/VayJJVRja7)
* **Email:** [core@chainrunner2079.online](mailto:core@chainrunner2079.online)

**Support the Project:**
As a free-to-play title, we appreciate any support on [Ko-fi](https://ko-fi.com/chainrunner2079).
