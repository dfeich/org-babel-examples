

Here follows the definition for the receiving location
of the table

% BEGIN RECEIVE ORGTBL salesfigures
\begin{tabular}{lrrr}
<l> &  &  &  \\
Month & Days & Nr sold & per day \\
\hline
Jan & 23 & 50 & 2.9 \\
Feb & 21 & 16 & 0.8 \\
March & 22 & 278 & 12.6 \\
\end{tabular}
% END RECEIVE ORGTBL salesfigures


You need to be in latex mode and have used (turn-on-orgtbl)
Here follows the source table

\begin{comment}
  #+ORGTBL: SEND salesfigures orgtbl-to-latex
| <l>   |      |         |         |
| Month | Days | Nr sold | per day |
|-------+------+---------+---------|
| Jan   |   23 |      50 |     2.9 |
| Feb   |   21 |      16 |     0.8 |
| March |   22 |     278 |    12.6 |
  #+TBLFM: $4=$3/$2;%.1f
  % $ (optional extra dollar to keep font-lock happy, see footnote)
\end{comment}

