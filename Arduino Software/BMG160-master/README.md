to add image:

click the "down arrow" next to the "files" folder
click "computer" from the dropdown menu
Add whatever image you want to add

in the "main.tex" file, add the following

\begin{figure}[H]
\centering
\includegraphics[width = .5\textwidth]{image.ext}
\caption{this is an image}
\label{fig:image}
\end{figure}

change the decimal before "\textwidth" to change how large the image is
change "image.ext" to whatever the image and extension is for the picture you're trying to add
change the caption to a useful summary of the image
change "image" in the label to some useful 1/2 word reference (what you name it here is how it gets referenced in the paper) 
Leave the "fig:" in the label since that tells the compiler that it's an image 





to add characters:
$\letter$

Useful 220 Characters:
\sigma
\epsilon
\tau

The $$ tells the compiler that it's in math mode and should be looking for mathematical symbols






to add equation:
$equation$

same thing with $$ as above
fractions: \frac{top_of_frac}{bottom_of_frac}
underscore: H_{underscore} (where H is an arbitrary symbol)
exponentiate: H^{exponent} (")
