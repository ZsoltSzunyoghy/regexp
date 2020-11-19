# regexp

To collect some regexp for common use

regular expressiongs: 

remove empty lines:
\n\n --> \n

pack email addesses in <>:
([\w\-.]*@[\w.]*)$ --> <$1>;

remove line breaks after names:
([^>;])\n --> $1 
---- add space to the end!!!
