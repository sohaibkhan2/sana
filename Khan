#!/usr/bin/python2
#coding=utf-8
#The Credit For This Code Goes To lovehacker
#If You Wanna Take Credits For This Code, Please Look Yourself Again...
#Reserved2020


import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,requests,mechanize
from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser


reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(),max_time=1)
br.addheaders = [('User-Agent', 'Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16')]


def keluar():
	print "\x1b[1;91mExit"
	os.sys.exit()


def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!'+w[random.randint(0,len(w)-1)]+i
    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
    x += '\033[0m'
    x = x.replace('!0','\033[0m')
    sys.stdout.write(x+'\n')


def jalan(z):
	for e in z + '\n':
		sys.stdout.write(e)
		sys.stdout.flush()
		time.sleep(0.07)

#sohaib:khan_hacker
##### LOGO #####
logo = """
\033[1;91m .########..####..######..##.....##.##.....##
\033[1;92m .##.....##..##..##....##.##.....##.##.....##
\033[1;92m .##.....##..##..##.......##.....##.##.....##
\033[1;92m .########...##...######..#########.##.....##
\033[1;92m .##...##....##........##.##.....##.##.....##
\033[1;91m .##....##...##..##....##.##.....##.##.....##
\033[1;91m .##.....##.####..######..##.....##..#######."""

def tik():
	titik = ['.   ','..  ','... ']
	for o in titik:
		print("\r\x1b[1;93mPlease Wait \x1b[1;93m"+o),;sys.stdout.flush();time.sleep(1)


back = 0
berhasil = []
cekpoint = []
oks = []
id = []
listgrup = []
vulnot = "\033[31mNot Vuln"
vuln = "\033[32mVuln"

os.system("clear")
print  """
\033[1;97m .########..####..######..##.....##.##.....##
\033[1;97m .##.....##..##..##....##.##.....##.##.....##
\033[1;97m .##.....##..##..##.......##.....##.##.....##
\033[1;97m .########...##...######..#########.##.....##
\033[1;97m .##...##....##........##.##.....##.##.....##
\033[1;97m .##....##...##..##....##.##.....##.##.....##
\033[1;97m.##.....##.####..######..##.....##..#######.
 \033[1;93m°°°°°°°°°°°°°°°Welcome To sohaib Tool✓✓
\033[1;97m°°°°°°°°°°°°°°°°SOHAIB
\033[1;97mAuthor \033[1;97msohaib
\033[1;97msohaibkhan\033[1;97m:❥•❥•❥•❥• \033[1;97▒▓██████████████]99.9

print "\033[1;93mLogin sohaib"

CorrectUsername = "sohaib"
CorrectPassword = "Khan"

loop = 'true'
while (loop == 'true'):
    username = raw_input("\033[1;97m🔐 \x1b[1;93mTool Username \x1b[1;97m»» \x1b[1;93m")
    if (username == CorrectUsername):
    	password = raw_input("\033[1;97m🔐 \x1b[1;93mTool Password \x1b[1;97m»» \x1b[1;93m")
        if (password == CorrectPassword):
            print "Logged in successfully as " + username #sohaib:khan_hacker
	    time.sleep(2)
            loop = 'false'
        else:
            print "\033[1;91mWrong Password"
            os.system('xdg-open https://m.youtube.com/channel/UCRrRgcJjsnNm5Bi5ZenRGnw')
    else:
        print "\033[1;94mWrong Username"
        os.system('xdg-open https://m.youtube.com/channel/UCRrRgcJjsnNm5Bi5ZenRGnw')

def login():
	os.system('clear')
	try:
		toket = open('login.txt','r')
		menu() 
	except (KeyError,IOError):
		os.system('clear')
		print logo
		jalan(' \033[1;91mWarning: \033[1;93mTermux Old Version Install 0.63 to 0.83' )
		jalan(' \033[1;91m   Note: \033[1;93mUse a New Account To Login' )
		print "\033[1;93m••••••••\033[1;97mRishu\033[1;93m••••••••"
		print('	   \033[1;97m■\x1b[1;93m•••••LOGIN WITH FACEBOOK•••••\x1b[1;97m■' )
		print('	' )
		id = raw_input('\033[1;97m[+] \x1b[1;93mID/Email\x1b[1;97m: \x1b[1;93m')
		pwd = raw_input('\033[1;97m[+] \x1b[1;93mPassword\x1b[1;97m: \x1b[1;93m')
		tik()
		try:
			br.open('https://m.facebook.com')
		except mechanize.URLError:
			print"\n\x1b[1;96mThere is no internet connection"
			keluar()
		br._factory.is_html = True
		br.select_form(nr=0)
		br.form['email'] = id
		br.form['pass'] = pwd
		br.submit()
		url = br.geturl()
		if 'save-device' in url:
			try:
				sig= 'api_key=882a8490361da98702bf97a021ddc14dcredentials_type=passwordemail='+id+'format=JSONgenerate_machine_id=1generate_session_cookies=1locale=en_USmethod=auth.loginpassword='+pwd+'return_ssl_resources=0v=1.062f8ce9f74b12f84c123cc23437a4a32'
				data = {"api_key":"882a8490361da98702bf97a021ddc14d","credentials_type":"password","email":id,"format":"JSON", "generate_machine_id":"1","generate_session_cookies":"1","locale":"en_US","method":"auth.login","password":pwd,"return_ssl_resources":"0","v":"1.0"}
				x=hashlib.new("md5")
				x.update(sig)
				a=x.hexdigest()
				data.update({'sig':a})
				url = "https://api.facebook.com/restserver.php"
				r=requests.get(url,params=data)
				z=json.loads(r.text)
				unikers = open("login.txt", 'w')
				unikers.write(z['access_token'])
				unikers.close(
