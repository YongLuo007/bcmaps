## BC Boundary

The file `atlas_of_canada_7.5M.zip` contains the 1:7.5M Atlas of Canada base maps, downloaded from [The Canadian Open Data Portal](http://open.canada.ca/data/en/dataset/f77c2027-ed4a-5f6e-9395-067af3e9fc1e) under the ([Open Government License - Canada](http://open.canada.ca/en/open-government-licence-canada)).

From this collection of base maps, the boundary of British Columbia is extracted using the script `data-raw/process_bc_bound.R`, transformed to the BC Albers projection and added to the package in `data/bc_bound.rda`.