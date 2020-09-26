# paper_PuMA

Los programas deben estar dentro de un directorio raíz, dentro del cual debe haber un subdirectorio llamado "pfds" con las observaciones. El orden para usar los programas es:
1. Calculamos el t_obs y el S/N de las observaciones con get_SNR.ipynb
2. Calculamos TOAs y residuos con get_TOAs.ipynb
3. Graficamos el S/N como función de t_obs con plot_tobs_vs_SNR.ipynb
4. Hacemos un histograma de S/N con plot_histogram.ipynb
5. Ajustamos el valor de n_ISS con plot_histogram_scintillation.ipynb
6. Separamos a las observaciones en subintegraciones temporales con time_subints.ipynb
7. Ajustamos el valor de n_ISS para las subobservaciones con plot_histogram_scintillation_subints.ipynb

