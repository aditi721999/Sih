


A 100% working Justdial scrapper, Just enter the url and it'll extract business info from it

    Enter the url from which you want to extract information and save it in the 'url' variable ex:

url="https://www.justdial.com/Agra/Readymade-Garment-Retailers/nct-10401947/page-%s" % (page_number)

    change the name of the csv file to be generated to be an appropriate one ex:

out_file = open('Readymade-Garment-Retailers_agra.csv','wb')

Run the file : python ./jd_scraper.py
