# Super Simple Map Overlay (SSMO)

## About

SSMO is a lightweight, browser-based tool for creating and editing map overlays. It can work offline (albeit performance is better with connections allowed) and stores data locally, making it ideal for personal mapping projects. 

## Getting Started

* Download `index.html` to your preferred directory
* Open `index.html` and jump right in on your browser

## Usage

* Left-aligned toolbar for map edits
* Changes are automatically saved via IndexedDB
* Runs offline [with overlay changes persistent] after initial setup
* 100% free

## Example

![ssmo-detailed-map-example](https://github.com/user-attachments/assets/4e721a6a-c4b7-4756-9dd2-bf42d02a28c9)
<sub>please dont read too far into this. it's just a demonstration.</sub>

## Limitations & Troubleshooting

This project stores data in your browser. It needs to make at least one initial callout to OpenMaps API or it will fail. A hard refresh (ctrl+shift+R) might also cause issues. The more you initially load in, the better it works. 

![ssmo-no-openstreetmap-api-connection](https://github.com/user-attachments/assets/eb33a621-6598-4ef5-b7e6-4b3fcf4fbc3a)
*error if connections are blocked on bootup. requires 1 initial connection.*

![ssmo-offline-refresh-errors](https://github.com/user-attachments/assets/3b080a45-22c6-440d-9b9d-0d37e73cb747)
*potential errors if hard refresh offline. close and re-open browser to resolve.*

![ssmo-offline-edit-cache](https://github.com/user-attachments/assets/8a17b4e6-59e1-4e05-8852-a286cfe74914)
*edits & changes still store locally when all connections blocked.*

![ssmo-offline-render-error](https://github.com/user-attachments/assets/58896bf8-9c7b-42d4-a7e3-0af0b9c23edd)
*higher zoom levels are wonkier when entirely offline. this could be resolved if I was better at cacheing.*

## License
This project is licensed under the MIT License.

## Contributions, Issues, and Feedback
Feel free to submit pull requests or issues.
