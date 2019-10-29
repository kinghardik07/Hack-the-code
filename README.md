# Hack-the-code
<?xml version="1.0" encoding="UTF-8"?>
<html xsl:version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
<body style="font-family:Avenir; font-size:12pt; background-color:#EEEEEE">
<xsl:template ="/">
  <div style="background-color:teal; color:white; padding:4px">
    <span style="font-weight:bold"><xsl:value-of select="title"/> - </span>
    <xsl:value-of select="artist"/> (<xsl:value-of select="year"/>)
    </div>
  <div style="margin-left:20px; margin-bottom:1em; font-size:10pt" >
    <p>
    The song is produced by: 
    <xsl:value-of select="description"/>.
    The country of origin is: 
    <span style="font-style:italic"><xsl:value-of select="country"/> </span>
    at a price of: <xsl:value-of select="price"/>.
    </p>
  </div>
</xsl:template>
</body>
</html>
