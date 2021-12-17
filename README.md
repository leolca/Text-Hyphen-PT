# NAME

Text::Hyphen::PT - determine hyphenation positions in portuguese words

# SYNOPSIS

This module is an implementation of Knuth-Liang hyphenation algorithm
for portuguese text using patterns from [tex-hyphen](https://www.tug.org/tex-hyphen/)e.

    use Text::Hyphen::PT;
    my $hyphenator = Text::Hyphen::PT->new;
    print $hyphenator->hyphenate($word, '-');

See [Text::Hyphen](https://metacpan.org/pod/Text%3A%3AHyphen) for the interface documentation. This module only
provides portuguese patterns.

# COPYRIGHT AND LICENSE 

Copyright 2021 Leonardo Araujo `<leolca@gmail.com>`

This program is free software: you can redistribute it and/or modify it 
under the terms of the GNU General Public License as published by the   
Free Software Foundation, either version 3 of the License, or (at your  
option) any later version.                                              

This program is distributed in the hope that it will be useful,         
but WITHOUT ANY WARRANTY; without even the implied warranty of          
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU       
General Public License for more details.                                

You should have received a copy of the GNU General Public License along 
with this program.  If not, see &lt;http://www.gnu.org/licenses/>.         
