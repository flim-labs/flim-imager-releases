
<div align="center">
  <h1>FLIM Imager </h1>
</div>
<div align="center" style="background-color: #052e4c; padding: 0.5rem; border-radius: 5px">
  <a href="https://www.flimlabs.com/">
    <img src="./assets/images/flim-imager-logo.png" width="250" alt="Logo">
  </a>
</div>
<br>

Welcome to [FLIM Imager](https://github.com/flim-labs/flim-imager), a Tauri application dedicated to **real-time image acquisition and reconstruction**. This software offers a variety of customization tools, including colormap selection, contrast adjustment, ROI exploration, and image region selection for tailored analysis.

In addition, FLIM Imager provides comprehensive support for Time-Correlated Single Photon Counting (**TCSPC**) analysis, both globally and at the single-pixel level and **Phasors** study. Powered by an underlying Rust-based data processor, FLIM Imager enables seamless data retrieval from hardware components and facilitates robust real-time visualization and analysis.

With an intuitive graphical user interface (GUI), FLIM Imager is designed to meet the needs of users seeking dynamic image exploration and precise fluorescence lifetime analysis.


### Built With

* [Tauri](https://v2.tauri.app/)
* [Rust](https://www.rust-lang.org/)
* [Svelte](https://svelte.dev/)
* [Typescript](https://www.typescriptlang.org/)
* [RxJS](https://rxjs.dev/)
* [Chart.js](https://www.chartjs.org/docs/latest/getting-started/installation.html)



<!-- GETTING STARTED -->
## Getting Started
To directly test the application, skipping the prerequisites and installation requirements you can download an installer at this [link](https://github.com/flim-labs/flim-imager/releases/tag/v1.0) (_Note: you still need to have the FLIM LABS Data Acquisition Card_). 

To get a local copy up and running follow these steps.

### Prerequisites

To be able to run this project locally on your machine you need to satisfy these requirements:
* Possess a [FLIM LABS Data Acquisition Card](https://www.flimlabs.com/products/data-acquisition-card/) to be able to acquire your data
* **ZestSC3** drivers installed
* Last version of [WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2?form=MA13LH) (v22.11.0) installed
* [Node](https://nodejs.org/en/) installed
* [Tauri CLI](https://v2.tauri.app/reference/cli/) (v1.6.2) installed
* Windows OS

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/flim-labs/flim-imager.git
   ```
2. Install the dependencies
   ```sh
   npm install
   ```
3. Run the project in development mode
   ```sh
   tauri dev
   ```  
4. Or build an .exe with
   ```sh
   tauri build  
   ```  

## Usage Guides

Navigate to the following links to view detailed application usage guides:

- [Flim Imager GUI guide](./docs/v1.0/index.md)
- [Flim Imager Data export guide](./docs/v1.0/data-export.md)


## Contact

FLIM LABS: info@flimlabs.com

Project Link: [FLIM LABS - FLIM Imager](https://github.com/flim-labs/flim-imager)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
