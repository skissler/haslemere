# Supplemental information and data for the manuscript _Sparking "The BBC Four Pandemic": Leveraging citizen science and mobile phones to model the spread of disease_

## Stephen M. Kissler, Petra Klepac, Maria Tang, Andrew J.K. Conlan, Julia R. Gog

Correspondence: sk792@cam.ac.uk

__Kissler_SI.pdf:__ Supplemental information for the manuscript, including descriptions of the associated datasets and further analyses. 

__Movie S1:__ Pairwise probabilities of infection Pi,j (Eq. 3) between the 45 individuals with highest individual reproduction number vj , where the sum in Eq. 3 is taken over all three days (top left), one day (top right), one hour (bottom left), and 15 minutes (bottom right). Nodes represent individuals, and lines represent probability of infection, such that the opacity of the line is proportional to the probability that an infection would occur in that time interval if one of the individuals were ‘infected’ and the other were ‘susceptible’. The bar along the bottom shows the time span covered by the one-day (top bar), one-hour (middle bar), and 15-minute (bottom bar) networks.

__DataS1.csv__ The “Haslemere dataset”, consisting of pairwise distances between users of the BBC Pandemic Haslemere app over time. Each row consists of an encounter (within 50m) between two users. Column 1 gives the time step as an integer value (see DataS2.csv for conversion to real time). Columns 2 and 3 give the user ID numbers. Column 4 gives the distance between the users at that time step, rounded to the nearest metre. Details on the derivation of this dataset are given in the Supplemental Materials and Methods.

__DataS2.csv__ Conversion between the time indices in column 3 of the Haslemere dataset (see Supplemental Materials and Methods) and real time, in British Standard Time (BST).

All code is available under the GNU General Public License, version 3, included in this repository under the following terms: 
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

