# Detecting and Mitigating Malicious Manipulations in Satellite Imagery 

Welcome to the GitHub repository for the Master's thesis on utilizing watermarking to detect and mitigate malicious manipulations in satellite imagery.
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/skier921/Detecting-and-Mitigating-Malicious-Manipulations-in-Satellite-Imagery/assets/7799202/68676567-2387-4dce-979f-9e312f01b506" alt="GAN Generated Image" style="width:300px; height:200px;">
      <br>
      <em>GAN Generated Image</em>
    </td>
    <td align="center">
      <img src="https://github.com/skier921/Detecting-and-Mitigating-Malicious-Manipulations-in-Satellite-Imagery/assets/7799202/ff6401e4-3763-40e3-b2e0-a5b37810dc97" alt="Watermarked Image" style="width:300px; height:200px;">
      <br>
      <em>Watermarked Image</em>
    </td>
    <td align="center">
      <img src="https://github.com/skier921/Detecting-and-Mitigating-Malicious-Manipulations-in-Satellite-Imagery/assets/7799202/5347fe48-1e40-4b43-baa9-64f379d12e7e" alt="Original Image" style="width:300px; height:200px;">
      <br>
      <em>Original Image</em>
    </td>
  </tr>
</table>


## Repository Structure

The repository is organized into the following directories:

### `01_code/`
Contains all the scripts and code modules required for watermark embedding, manipulation detection, and other image processing tasks.

### `02_data/`
Link to the EUROSAT dataset used in our experiments:
https://zenodo.org/records/7711810#.ZAm3k-zMKEA
Ensure you download the RGB version or use the torch dataset in the notebook already
![Class Distrubtrion](https://github.com/skier921/Detecting-and-Mitigating-Malicious-Manipulations-in-Satellite-Imagery/assets/7799202/6b15eddf-e410-4e34-beb2-1b90d6e41936)

![Example Photos](https://github.com/skier921/Detecting-and-Mitigating-Malicious-Manipulations-in-Satellite-Imagery/assets/7799202/3fdf95fe-05ed-4dde-8a29-3eddf073b1b0)


### `03_results/`
Stores the raw output from the experiments, including detection accuracy metrics, logs, and intermediate data for analysis.

### `04_graphs/`
Houses all visual outputs, such as plots and graphs, illustrating the effectiveness of watermarking and manipulation detection methodologies.

## Usage

To replicate the experiments or apply the watermarking techniques, navigate to the `01_code/` directory and  run the Jupyter notebook.

## Visualizations

Graphical illustrations of results can be found under `04_graphs/`. They provide a visual understanding of the methods' performance.

## License

This project is released under the MIT License.
