# ERA5interp

ERA5 model level data location:
/glade/collections/rda/data/ds633.6/e5.oper.an.ml



Some notes about Isla's environment issues:
Geocat needs metpy 1.4.0.
When I specified metpy to be 1.4.0 though then xesmf didn't work.
I needed cf_xarray to be updated to 0.7.2.  I did this by 
conda update cf_xarray

Not sure why any of this was necessary. It seems like this should have happened automatically.


