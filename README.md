# paper_PuMA

Los programas deben estar dentro de un directorio raíz, dentro del cual debe haber un subdirectorio llamado "pfds" con las observaciones. El orden para usar los programas es:
1. Calculamos el t_obs y el S/N de las observaciones con get_SNR.ipynb.
2. Graficamos el S/N como función de t_obs con plot_tobs_vs_SNR.ipynb.
3. Hacemos un histograma de S/N con plot_histogram.ipynb
4. Ajustamos el valor de n_ISS con plot_histogram_scintillation.ipynb
5. Separamos a las observaciones en subintegraciones temporales con time_subints.ipynb
6. Ajustamos el valor de n_ISS para las subobservaciones con plot_histogram_scintillation_subints.ipynb

