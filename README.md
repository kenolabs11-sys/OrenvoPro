# Orenvo Pro

**Local-first image conversion, AI enhancement, and workflow automation for Windows.**

Orenvo Pro is a Windows desktop application developed by **KenoLabs** for creators, online sellers, designers, photographers, and anyone who regularly works with images.

Convert and compress images, remove backgrounds, upscale locally, create animated GIFs, and automate repetitive workflows — all in one desktop workspace.

Supported image processing runs locally on your PC, without uploading normal image jobs to a browser service.

## Orenvo Pro v5.4.5 Beta 1

**Smarter automation. More accurate previews. Better reliability.**

Version 5.4.5 Beta 1 builds on the redesigned Converter workspace introduced in v5.4, delivering improvements across Watch Mode, AI Background Removal, image processing, advanced format previews, licensing, and Windows installation.

### What's new

- **Improved Watch Mode:** More reliable file detection, duplicate-processing prevention, safer output handling, and better support for multiple watched folders.
- **More background options:** Configure transparent, solid-color, blurred, or custom image backgrounds with presets and RGB/HEX color controls.
- **Dedicated HDR Viewer:** Inspect HDR and EXR output with adjustable exposure and tone mapping without modifying exported HDR data.
- **More accurate Before / After:** Improved preview consistency while keeping the original image independent of HDR viewing adjustments.
- **Better image format handling:** Improved HDR, EXR, ICO, DDS, and JPEG XL decoding, previews, and conversion behavior.
- **Safer AI model downloads:** Additional SHA-256 integrity verification and more reliable model replacement.
- **Improved conversion workflows:** Better watermark handling, JPG transparency backgrounds, and output-file safety.
- **Clearer History statistics:** Accurate reporting when processed files become larger rather than smaller.
- **Refined interface:** Better dropdown positioning, scrolling, loading feedback, and update checking.
- **Updated Windows installer:** Refreshed KenoLabs branding and improved Windows Explorer helper packaging.
- **Updated licensing compatibility:** Freemius support for new purchases while retaining compatibility with valid existing Lemon Squeezy licenses.

### Converter workspace

The unified Converter workspace introduced in v5.4 remains available:

- File queue, Before / After preview, and output settings in one workspace.
- Draggable comparison divider with zoom and pan.
- Dedicated text and logo watermark editor.
- Reorderable files and GIF frames.
- Retry failed jobs or requeue completed work.
- Web, Print, Social, Game Texture, and Archive presets.
- Remembered Converter settings between launches.

**Beta notice:** This version is intended for testing. Work with copies of important images and keep a known-working installer available.

## Features

### Convert and prepare images

- Process individual images, folders, or entire batches.
- Preview conversions before processing a batch.
- Compare original images and processed results.
- Resize by width, height, long edge, percentage, or custom target.
- Rename files and configure output locations.
- Choose overwrite and file-naming behavior.
- Preserve or remove supported EXIF metadata.
- Add text or logo watermarks with reusable presets.
- Use Smart Compression to balance quality and file size.
- Create and save conversion presets.
- Review completed jobs in History.
- Configure advanced options for supported image formats.

### Create animated GIFs

- Arrange frames on a draggable visual timeline.
- Control frame timing and animation looping.
- Preview, play, pause, and scrub through animations.
- Configure Fit or Fill behavior.
- Adjust palette quality and watermark settings.
- Export animated GIFs from multiple images.

### Background Removal

Remove image backgrounds directly on your Windows PC.

- Standard processing with BEN2.
- High Resolution processing with BiRefNet-HR.
- Transparent, solid-color, blurred, and image backgrounds.
- Checkerboard, Cutout, and Mask preview modes.
- Feather and edge-shift adjustments.
- Edge decontamination tools.
- Keep/Remove mask brushes for manual refinement.
- Support for single-image and batch workflows.
- Configurable output formats and backgrounds.

### AI Upscaling

Enhance images locally using supported AI models.

- Upscale photos, illustrations, anime, and detailed artwork.
- 2x, 4x, 8x, and custom-size output.
- Configurable enhancement settings.
- Compatible GPU acceleration when available.
- CPU processing when required.
- Reusable downloaded AI models.
- Single-image, batch, and supported Explorer workflows.

### Watch Mode — Automated Image Processing

Automate repetitive image work by monitoring folders.

Watch Mode supports:

- Automatic image conversion.
- Automatic Background Removal.
- Automatic AI Upscaling.
- Saved settings for each watched folder.
- Configurable output directories and formats.
- Background presets, custom colors, blur, and local images.
- Standard and High Resolution background processing.

#### Reliability improvements in v5.4.5

- Better handling of duplicate filesystem notifications.
- Protection against repeatedly processing generated output files.
- Improved detection of incomplete or partially copied images.
- Safer operation with multiple active watchers.
- Improved prevention of output filename conflicts.
- Better handling of shared source and output directories.
- Improved preservation of saved background settings.
- Clearer display of actual output formats.
- Additional automated regression tests.

Watch Mode is designed to keep repetitive image workflows running with less manual interaction.

### HDR and EXR workflows

Orenvo Pro includes dedicated handling for high-dynamic-range images.

- HDR and EXR conversion support.
- HDR-to-SDR tone mapping.
- Adjustable exposure for supported conversions.
- Improved preview and export consistency.
- More reliable processing of HDR images with watermarks.
- Dedicated HDR output inspection.

#### Dedicated HDR Viewer

Use the HDR Viewer to inspect HDR/EXR output with adjustable exposure and tone-mapping controls.

**Important:** HDR Viewer adjustments affect the displayed representation, not the exported HDR/EXR data.

When converting HDR/EXR input into SDR formats such as JPG, PNG, or WebP, conversion tone-mapping settings can affect the saved output.

### Windows Explorer integration

Access supported Orenvo Pro actions directly from Windows File Explorer.

- Quick conversions for commonly used image formats.
- Background Removal actions.
- AI Upscaling workflows.
- Reusable workflow profiles.
- Windows notifications for supported completed AI jobs.

## Output formats

Orenvo Pro supports **20 output formats**:

`JPG`, `PNG`, `WEBP`, `AVIF`, `HEIC`, `HEIF`, `TIFF`, `TGA`, `BMP`, `ICO`, `DDS`, `JXL`, `GIF`, `QOI`, `EXR`, `HDR`, `PAM`, `PPM`, `PGM`, and `PBM`.

Format-specific options appear when relevant.

Examples include:

- **ICO:** Selected icon sizes.
- **DDS:** Standard 2D textures, compression options, and mipmaps.
- **JPEG XL:** Encoder-effort controls.
- **GIF:** Animation frames, timing, and palette quality.
- **HDR/EXR:** High-dynamic-range conversion and viewing controls.
- **JPG:** Configurable backgrounds when exporting transparent images.

Format availability and behavior may depend on the selected workflow and supported codecs.

## Free and Pro

| Feature | Free | Pro |
|---------|------|-----|
| Output formats | JPG, PNG, WEBP | All 20 formats |
| Conversion batch size | Up to 10 files | Unlimited |
| Resize and naming | Basic tools | Full workflow controls |
| Background Removal | 10 uses | Unlimited |
| AI Upscaling | 10 uses | Unlimited |
| Smart Compression | — | Included |
| Watch Mode | — | Included |
| Saved automation | — | Included |
| Windows Explorer workflows | — | Included |

The Background Removal and AI Upscaling allowances are separate.

The Free workflow does not require a credit card or an Orenvo account.

### Orenvo Pro license

**€24.99 — one-time purchase**

- Lifetime PRO license under the applicable license terms.
- No monthly subscription.
- Activation on up to two personal devices.
- Access to included Pro features.
- License validation through KenoLabs' secure licensing service.

The displayed price and purchasing conditions should be confirmed at checkout.

New purchases are processed through **Freemius**.

Existing valid **Lemon Squeezy** licenses remain supported. Customers do not need to purchase Orenvo Pro again because the payment provider has changed.

[Visit the official Orenvo Pro website](https://kenolabs.dev/orenvo)

## License activation

After purchasing Orenvo Pro:

1. Open Orenvo Pro.
2. Navigate to **Settings → License**.
3. Enter the license key from your purchase confirmation.
4. Activate your device.

License activation requires an internet connection.

Activation limits, license validation, and access status are managed by KenoLabs' secure licensing service.

Refunded, disputed, revoked, or charged-back orders may lose Pro access according to the applicable license terms.

### Reinstalling or uninstalling Orenvo Pro

For normal updates and reinstalls, we recommend keeping your application data.

Deleting all application data can remove:

- Locally stored Pro activation information.
- Application settings.
- Other locally stored application preferences and data.

**Important:** Uninstalling Orenvo Pro does not automatically cancel your purchased license.

However, an existing device activation may remain registered on the license server even if local activation data is removed.

Reactivation or assistance from KenoLabs support may be required.

Automatic license recovery after complete application-data deletion is not currently guaranteed.

Contact **contact@kenolabs.dev** if you need assistance.

## Privacy and local processing

Orenvo Pro is designed around local-first image processing.

Supported image conversion, Background Removal, and AI Upscaling run on your Windows PC.

Source images are not uploaded to KenoLabs during normal supported image processing.

- AI models are downloaded when first required.
- Downloaded models remain stored locally for later use.
- Output files remain under your control.
- License checks may require internet access.
- Updates and model downloads may use network access.
- Free usage allowance verification may require network access.
- Support reports are submitted only when you choose to send them.

New purchases and license-key delivery are handled through Freemius. Earlier valid Lemon Squeezy licenses remain supported.

For details, read the [Privacy Policy](https://kenolabs.dev/orenvo/privacy).

## System requirements

- Windows desktop PC.
- Windows 11 tested.
- Windows 10 64-bit may work but is not officially tested.
- 8 GB RAM minimum; 16 GB recommended.
- 2 GB free storage, plus space for optional AI models.
- Compatible GPU optional.
- CPU processing supported.
- Internet connection required for license activation, updates, first-time model downloads, and selected online services.

The first AI task may take longer while Orenvo downloads and prepares the selected model.

### Windows security notice

Windows or your browser may display an "Unknown Publisher" or SmartScreen warning because the current installer is not code-signed with a trusted publisher certificate.

Only use installers obtained through official KenoLabs distribution channels.

## Download

Download Orenvo Pro through the official distribution channels:

- [Official Orenvo Pro website](https://kenolabs.dev/orenvo)
- [GitHub Releases](https://github.com/kenolabs11-sys/OrenvoPro/releases)

The v5.4.5 Beta 1 installer is being prepared for public distribution. Check the official download pages for the currently available version.

Do not assume a development or locally built installer has already been published as a public GitHub release.

Once installed, Orenvo Pro can be used in Free mode before upgrading to Pro.

## Useful links

- [Orenvo Pro website](https://kenolabs.dev/orenvo)
- [User guide](https://kenolabs.dev/orenvo/docs)
- [Changelog](https://kenolabs.dev/orenvo/changelog)
- [GitHub repository](https://github.com/kenolabs11-sys/OrenvoPro)
- [GitHub releases](https://github.com/kenolabs11-sys/OrenvoPro/releases)
- [Terms & License Agreement](https://kenolabs.dev/orenvo/terms)
- [Refund Policy](https://kenolabs.dev/orenvo/refund-policy)
- [Privacy Policy](https://kenolabs.dev/orenvo/privacy)
- [Third-party licenses](https://kenolabs.dev/orenvo/third-party-licenses)
- [Support](https://kenolabs.dev/orenvo/support)

## Support

For purchasing, licensing, activation, or technical assistance:

**contact@kenolabs.dev**

When reporting a technical issue, please include:

- Orenvo Pro version.
- Windows version.
- Input and output image formats.
- Steps to reproduce the issue.
- Whether the issue occurs in the preview or exported file.
- A screenshot, if relevant.

Do not share full license keys, activation tokens, or private device identifiers publicly.

## Legal

Orenvo Pro is proprietary software developed and published by KenoLabs.

The software is licensed, not sold, and is governed by the [Orenvo Pro Terms & License Agreement](https://kenolabs.dev/orenvo/terms).

© 2026 KenoLabs. All rights reserved.
