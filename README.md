# iraf_simil
Data reduction + photometry for Gemini imaging following IRAF methodology

1) reduciending (uses DRAGONS to reduce raw data which should be downloaded already)
2) filtranding (models galaxy surface brightness and extracts it, adds  sky mean value so images are ready for photometry) 
3) apphot (uses sextractor with gauss+mexhat filters to build initial catalogue, then obtains initial aperture photometry)
