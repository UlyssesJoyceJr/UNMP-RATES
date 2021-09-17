

from csv import reader 
with open('---', 'r') as FOODSTAMPS:
    csv_reader = reader(FOODSTAMPS)
    VISA = list(csv_reader)
    THISTHING = (VISA[3])
    x = ['Jun', 'Jul', 'Aug','Sep','Oct','Nov','Dec','Jan','Feb','Mar','Apr','May']
    y = (([4.3, 4.3, 4.4, 4.2, 4.1, 4.1, 4.1, 4.1, 4.1, 4.1, 3.9, 3.8]))
    import numpy as NOSTRADOMAS
    from matplotlib import pyplot as COUSINP
    
    SKIDDY = NOSTRADOMAS.array(([x,y]))
    COUSINP.plot(x, y)
    COUSINP.ylabel('Unemployment Rate (%)')
    COUSINP.xlabel('Month')
    COUSINP.title('U.S. Unemployment Rate')
