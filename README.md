# Agricas
Web scraper for the URL http://www.agricas.fr/menu-au-ria. It parses menus, prices and side dishes for the available days.

## Install and Run
1. Have `python >= 3` and `pip` installed.
2. `pip install -r requirements.txt` -- Install dependencies
3. `python3 agricas.py -d DAYS` -- Run the script. Use the optionnal arugment `-d DAYS` with `DAYS >= 1` to choose the number days displayed. 
Use `-h` for more informations.

## Output example:
`python3 agricas.py -d 1`
```bash
##########################################################################################
 Jeudi 14/04 :
   - Boulettes De Mouton Curry Madras                                                 3,25€ 
   - Filet De Poisson Meunière Aux Câpres Et Citron                                   2,10€ 
   - Steak De Bœuf  Sauce Au Bleu                                                     4,05€ 
 Accompagnements :
   - Duo De Courgettes                                                                
   - Céleri-Rave Poêlé À La Moutarde                                                  
   - Frites                                                                           
##########################################################################################
 Vendredi 15/04 :
   - Fermé                                                                                  
##########################################################################################
```