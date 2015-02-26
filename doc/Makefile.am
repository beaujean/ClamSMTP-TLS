
man_MANS = clamsmtpd.8 clamsmtpd.conf.5
EXTRA_DIST = $(man_MANS) clamsmtpd.conf

# Simple way to make docs
html: 
	perl man2html.pl clamsmtpd.8 > clamsmtpd.html
	perl man2html.pl clamsmtpd.conf.5 > clamsmtpd.conf.html

