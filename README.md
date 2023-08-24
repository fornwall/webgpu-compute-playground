# WebGPU Compute Playground

Online editor to try out and share [WebGPU compute shader](https://developer.chrome.com/articles/gpu-compute/) snippets.

Available at [compute.fornwall.net](https://compute.fornwall.net).

## Usage

Define a [WGSL](https://www.w3.org/TR/WGSL/) function with the signature `compute() -> f32`.

This function will be embedded in a compute shader and executed continuously during typing, showing the result below the editor.

The page URL is updated to contain the source as in the URL.

## Running locally

Open the [index.html](index.html) file in a browser with WebGPU support.
