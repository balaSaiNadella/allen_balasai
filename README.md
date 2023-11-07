APIS:


1) Create Api -> []{item_id, desired_count, start time, end time} -> bulk 
2) Update Api -> []{item_id, refreshed_count, refreshed_end_time} -> bulk
3) End Api -> global kill switch
4) Claim Api -> {item_id} // single item level

http server
routes reg, server interface for entire service responsible routes
port : 7878


internal:
items controller/handler
items service
items repo
items models -> req, response
