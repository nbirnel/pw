<html>
<head>
<meta name="generator" content="groff -Thtml, see www.gnu.org">
<meta http-equiv="Content-Type" content="text/html; charset=US-ASCII">
<meta name="Content-Style" content="text/css">
<title>pw</title>

</head>
<body>

<h1 align="center">pw</h1>

<a href="#NAME">NAME</a><br>
<a href="#SYNOPSIS">SYNOPSIS</a><br>
<a href="#DESCRIPTION">DESCRIPTION</a><br>
<a href="#OPTIONS">OPTIONS</a><br>
<a href="#EXAMPLES">EXAMPLES</a><br>
<a href="#EXIT STATUS">EXIT STATUS</a><br>
<a href="#AUTHOR">AUTHOR</a><br>
<a href="#HISTORY">HISTORY</a><br>
<a href="#FILES">FILES</a><br>
<a href="#BUGS">BUGS</a><br>
<a href="#DEPENDANCIES">DEPENDANCIES</a><br>
<a href="#SEE ALSO">SEE ALSO</a><br>
<a href="#LICENSE">LICENSE</a><br>

<hr>


<h2>NAME
<a name="NAME"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">pw &minus;
simple password manager</p>

<h2>SYNOPSIS
<a name="SYNOPSIS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em"><b>pw [OPTIONS]
[REGEX]</b></p>

<h2>DESCRIPTION
<a name="DESCRIPTION"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em"><b>pw</b> opens
a menu of passwords, and puts the selected one in the
clipboard. It currently does not encrypt the password
file.</p>

<h2>OPTIONS
<a name="OPTIONS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">--help</p>

<p style="margin-left:18%;">Print a brief usage
message.</p>

<p style="margin-left:11%;">--user</p>

<p style="margin-left:18%;">Get the user name instead of
the password.</p>

<h2>EXAMPLES
<a name="EXAMPLES"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em"><b>pw
--user</b></p>

<h2>EXIT STATUS
<a name="EXIT STATUS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">exits non-zero
on error.</p>

<h2>AUTHOR
<a name="AUTHOR"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">Noah Birnel</p>

<h2>HISTORY
<a name="HISTORY"></a>
</h2>


<h2>FILES
<a name="FILES"></a>
</h2>



<p style="margin-left:11%; margin-top: 1em"><b>$HOME/.config/pw/safedir</b>
Where the location of the safes is stored.</p>

<p style="margin-left:11%; margin-top: 1em"><b>[safes]</b>
The safes, which are tab delimited, based on the
PasswordSafe export format.</p>

<h2>BUGS
<a name="BUGS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">Can only read
one safes directory. Requires X to be running. Safes are not
encrypted. Probably others.</p>

<h2>DEPENDANCIES
<a name="DEPENDANCIES"></a>
</h2>



<p style="margin-left:11%; margin-top: 1em"><i>http://dl.suckless.org/tools/dmenu-4.5.tar.gz</i></p>

<h2>SEE ALSO
<a name="SEE ALSO"></a>
</h2>



<p style="margin-left:11%; margin-top: 1em"><i><b>dmenu(1)</b></i></p>

<h2>LICENSE
<a name="LICENSE"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">Copyright 2014
Noah Birnel</p>
 
<p style="margin-left:11%; margin-top: 1em">DWTFYW</p>
<hr>
</body>
</html>
