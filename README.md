# Hack-the-code
<!--This is an XML file containing the structure and definition of elements of a cd catalog-->
<?xml version="1.0" encoding="UTF-8" ?>
<?xml-stylesheet type="text/xsl" href="cdctlg.xsl" ?>
<!DOCTYPE cd[
<!ELEMENT cd (title, artist, company, country, price, year)>
<!ELEMENT title (#PCDATA)>
<!ELEMENT artist (#PCDATA)>
<!ELEMENT company (#PCDATA)>
<!ELEMENT country (#PCDATA)>
<!ELEMENT price (#PCDATA)>
<!ELEMENT year (#PCDATA)>
]>
<cd>
		<entry>
			<title>Aina Saaf Kiya</title>
			<artist>BK Asmita</artist>
			<company>Brahmakumaris</company>
			<country>India</country>
			<price>$10.0</price>
			<year>2019</year>
		</entry>
		<entry>
			<title>Jharno se sangeet hai jharta</title>
			<artist>BK Asmita</artist>
			<company>Brahmakumaris</company>
			<country>India</country>
			<price>$10.0</price>
			<year>2019</year>
		</entry>
		<entry>
			<title>Ye mat kaho khuda se</title>
			<artist>BK Asmita</artist>
			<company>Brahmakumaris</company>
			<country>India</country>
			<price>$10.0</price>
			<year>2015</year>
		</entry>
		<entry>
			<title>Shiv aapada haran</title>
			<artist>Suresh Wadkar</artist>
			<company>Brahmakumaris</company>
			<country>India</country>
			<price>$10.0</price>
			<year>2012</year>
		</entry>
		<entry>
			<title>BKHD Edition</title>
			<artist>BKHD</artist>
			<company>Peace</company>
			<country>India</country>
			<price>$20.0</price>
			<year>2018</year>
		</entry>
</cd>
