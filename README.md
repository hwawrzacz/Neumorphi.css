# Neumorphicss
CSS stylesheet for Neumorph design


What is not supported:
    - Rowspan - if you look closer, you'll notice, that all cells have border-radius 0, except the top-left, top-right, bottom-left and bottom-right. If you use rowspan in the way that the merged rows will include the last one, then the second cell in the last row gets its bottom-left corner rounded. It is, because what you see in the document as a second cell in that row, in HTML code it is first <td> element in row