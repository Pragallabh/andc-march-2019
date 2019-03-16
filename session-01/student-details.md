# Name, email address and contact number
- Rintu Kutum, rintu.kutum@igib.in, 7838369344, CSIR-IGIB, BSc., Botany
- Pragallabh Purwar, pragallabh@gmail.com, 9013328728, NSUT, B.Tech, Biotechnology

# Early basic 'Function'

info <- function(fn, ln, ins, cn){
op <- paste(fn, ' ', ln, ', ', ins, ', ', cn, sep='')
return(op)}




# Later
info <- function(fn, ln, ins, cn){
while(ins== NULL){NA}
op <- paste(fn, ' ', ln, ', ', ins, ', ', cn, sep='')
return(op)}
