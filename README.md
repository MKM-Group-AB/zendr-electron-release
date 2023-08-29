<p align="center">
<img  width="300" src="https://uploads-ssl.webflow.com/62d19b5bcea0f11783daa821/62fe033d159a61d89fda4056_download-p-500.webp">
</p>
<hr>

# Visma Administration Integration

Streamline your order management process by integrating Visma Administration with our portal. Our integration offers a range of features designed to enhance efficiency and accuracy in handling your orders.

## Key Features

### Automated Order Fetch

Our integration provides three distinct order fetch options, each triggered by specific order events:
- **On Created Order:** Orders will be automatically fetched and sent to the portal as soon as they are created.
- **On Invoice Order:** Orders will be fetched and sent to the portal automatically upon invoicing.
- **On Delivery Order:** Orders will be fetched and sent to the portal automatically when a delivery note is selected.

### Customizable Goods Description

Tailor the way goods descriptions are handled according to your preferences. Define rules for goods descriptions to ensure consistency and clarity.

### Carrier Type Filters

Effortlessly manage orders by carrier type using our carrier type filters. Specify a carrier type, and only orders associated with that carrier type will be sent to the portal, keeping your workflow focused and organized.

### Interval Fetch

Customize the interval at which orders are fetched with flexibility, ranging from as short as 5 seconds to a maximum of 60 seconds. This feature allows you to strike the perfect balance between real-time updates and system resource optimization.

## Configuration Steps

Follow these steps to set up the Visma Administration Integration for seamless order management:

### 1. Company Path

Each company in Visma has a designated folder on your computer where its files are stored. To access and read this data, the integration requires knowledge of the folder's location. The default path typically resembles:
```C:\ProgramData\SPCS\SPCS Administration\Företag\Ovnbol1000```
Locate your company's specific path and input it in the integration settings.

### 2. Common Path

In addition to the company path, the integration also requires access to the common folder. The default common path often appears as:
```C:\ProgramData\SPCS\SPCS Administration\Gemensamma Filer```
Find your common folder's path and provide it in the integration settings.

### 3. Update Interval

The integration periodically checks for new orders in Visma. The update interval determines the duration between each check. Select your preferred interval, ranging from 5 to 60 seconds.

### 4. Integration Key

Upon activating the integration in the Zendr Portal, you will receive an integration key. This key serves as a unique identifier for your integration. Make sure to input this key correctly.

### 5. Auto Start

Consider enabling the 'Auto Start' feature by checking the provided box. This setting ensures that Zendr starts automatically when your Windows system starts. We recommend using this feature for a streamlined experience.

## Installation

1. Download Zendr application for the Visma Administration Integration.
2. Install the package and follow the on-screen instructions.
3. Once installed, open the integration settings.

## Usage

With the Visma Administration Integration properly configured, you're ready to experience efficient order management. The integration will automatically fetch orders based on your selected order fetch type and update interval. Goods description customization and carrier type filters will enhance your workflow and organization.