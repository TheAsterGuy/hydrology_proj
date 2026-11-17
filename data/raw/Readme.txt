The following files are included:
[Item 1 'stations_ghi.txt']       : complete station metadata, all 645 stations, pipe(|) delimited
[Item 2 'hydromet_annual.txt']    : hydrometeorological time series for Group 1 and Group 2 stations, annual, pipe(|) delimited
[Item 3 'hydromet_monthly.txt']   : hydrometeorological time series for Group 1 and Group 2 stations, monthly, pipe(|) delimited
[Item 4 'basins_ghi']             : one shapefile of ghi composite basins
[Item 5 'stations_ghi']           : one shapefile of ghi station metadata (based on 'stations_ghi.txt')
[Item 6 folder 'by_station']      : shapefiles of delineated catchment boundaries and corresponding river networks, for Group 1 and Group 2 stations
[Item 7 'summary_annual.pdf']     : PDF file of station summary for Group 1 and Group 2 stations, annual (472 pages)
[Item 8 'summary_monthly.pdf']    : PDF file of station summary for Group 1 and Group 2 stations, monthly (472 pages)

#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_
[Item 1 'stations_ghi.txt']

ghi_stn_id        : Unique ID used to identify a station, 10 characters long, GHI
riv_basin         : Complete name of the River Basin
cwc_state         : State associated with the station, CWC
cwc_site_name     : Name of the station, CWC
cwc_dist          : District associated with the station, CWC
cwc_type1         : Purpose of monitoring station, a combination of HO (Hydrological Observatory) and/or FF (Flood Forecast site), CWC
cwc_area          : Catchment drainage area (sq km), CWC
cwc_river         : River/tributary, CWC
cwc_type2         : Type of monitoring station, a combination of G (Gauge), D (Discharge), S (Sediment), Q (Quality), from CWC
cwc_grid_ref      : Station ID used by CWC
cwc_lat_orig      : Latitude of the station (DD_MM_SS), CWC
cwc_lon_orig      : Longitude of the station (DD_MM_SS), CWC
cwc_lat           : Latitude of the station (decimal degrees), CWC
cwc_lon           : Longitude of the station (decimal degrees), CWC
ghi_bas_name      : Composite river basin name, GHI
ghi_bas_id        : Three character ID used identify composite river basins, GHI
hydrosh_pf        : HydroSHEDS PF-12 watershed number
ghi_locchk        : Location check performed by GHI
ghi_rivchk        : River name check performed by GHI
ghi_lmark         : Description of the landmark identified by GHI
ghi_lmark_lat     : Latitude of the GHI landmark (decimal degrees)
ghi_lmark_lon     : Longitude of the GHI landmark (decimal degrees)
ghi_lmark_dist    : Distance of GHI landmark from original CWC station (km)
ghi_lat           : Latitude of the GHI relocated station (decimal degrees)
ghi_lon           : Longitude of the GHI relocated station (decimal degrees)
ghi_reloc         : Distance of GHI relocated station from original CWC station (km)
merit_lat         : Latitude of the MERIT relocated station (decimal degrees)
merit_lon         : Longitude of the MERIT relocated station (decimal degrees)
ghi_area          : Catchment drainage area (sq km), GHI
merit_area        : Catchment drainage area (sq km), MERIT
discGC            : Discrepancy (fraction) of GHI drainage area relative to CWC
discGM            : Discrepancy (fraction) of GHI drainage area relative to MERIT
ghi_netchk        : Adequacy of river network, GHI
merit_netchk      : Adequacy of river network, MERIT
qc1               : Quality check 1 (P or F)
qc2               : Quality check 2 (P or F)
qc3               : Quality check 3 (P or F)
qc4               : Quality check 4 (P or F)
qc5               : Quality check 5 (P or F)
qc6               : Quality check 6 (P or F)
qc7               : Quality check 7 (P or F)
qc8               : Quality check 8 (P or F)
qc9               : Quality check 9 (P or F)
qc10              : Quality check 10 (P or F)
ghi_group         : GHI assigned group (G1 or G2 or G3)

#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_
[Item 2 'hydromet_annual.txt']

ghi_stn_id        : Unique ID used to identify a station, 10 characters long, GHI
wyr               : Water Year
prec_era          : Total precpitation from ERA5-Land, MCM/year
runo_era          : Total runoff from ERA5-Land, MCM/year
evap_era          : Total ET from ERA5-Land, MCM/year
prec_imd          : Total precpitation from IMD, MCM/year
evap_gleam        : Total ET from GLEAM, MCM/year
days_avail        : Number of daily observations of streamflow available from WRIS
flow_mcm_obs      : Total streamflow from WRIS (raw or unadjusted), MCM/year
flow_mcm_tot      : Total streamflow from WRIS (adjusted for missing days), MCM/year

#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_
[Item 3 'hydromet_monthly.txt']

ghi_stn_id        : Unique ID used to identify a station, 10 characters long, GHI
wyr               : Water Year
cmon              : Calendar month
prec_era          : Total precpitation from ERA5-Land, MCM/month
runo_era          : Total runoff from ERA5-Land, MCM/month
evap_era          : Total ET from ERA5-Land, MCM/month
prec_imd          : Total precpitation from IMD, MCM/month
evap_gleam        : Total ET from GLEAM, MCM/month
days_tot          : Number of days in the month
days_avail        : Number of daily observations of streamflow available from WRIS
flow_mcm_obs      : Total streamflow from WRIS (raw or unadjusted), MCM/month
flow_mcm_tot      : Total streamflow from WRIS (adjusted for missing days), MCM/month

#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_
[Item 4 'basins_ghi']

ghi_bas_id        : Three character ID used identify composite river basins, GHI
ghi_bas_name      : Composite river basin name, GHI

#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_
[Item 5 'stations_ghi']

Fields same as 'stations_ghi.txt'

#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_#_
[Item 6 folder 'by_station']

catchment boundary : "hybas_as_lev12_v1c_xxxx_yyyyy"
river network      : "as_riv_15s_xxxx_yyyyy"

where "xxxx_yyyyy" is the 10 character GHI station ID ('ghi_stn_id')



