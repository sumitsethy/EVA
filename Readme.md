##### What are Channels and Kernels?

<u>Channels</u> -

It's a grid of size m x n, initially it's of image size but after convolution or maxpooling it depends on the operation we performed. If we consider i/p image then for color image it has 3 channels R,G,B & in case of gray scale image it has only 1 channel. 

It contains values which is pixel values w/ in range of 0-255 & it helps the model in detecting edges, patterns & parts of object.

<u>Kernels</u> - 

Also known as filter, feature extractor. It helps the model in detecting horizontal, vertical edges also various shapes, sizes with different gradient of the image. It extracts features/properties of the given object.

##### Why should we only (well mostly) use 3x3 Kernels?

3x3 Kernels helps in distinguishing various gradients, it gives the model the central line which helps in achieving different types of edges, sizes & shapes of object.

##### How many times do we need to perform 3x3 convolution operation to reach 1x1 from 199x199

199 | 197 | 195 | 193 | 191 | 189 | 187 | 185 | 183 | 181 | 179 | 177 | 175 | 173 | 171

169 | 167 | 165 | 163 | 161 | 159 | 157 | 155 | 153 | 151 | 149 | 147 | 145 | 143 | 141

139 | 137 | 135 | 133 | 131 | 129 | 127 | 125 | 123 | 121 | 119 | 117 | 115 | 113 | 111

109 | 107 | 105 | 103 | 101 | 99 | 97 | 95 | 93 | 91 | 89 | 87 | 85 | 83 | 81 

79 | 77 | 75 | 73 | 71 | 69 | 67 | 65 | 63 | 61 | 59 | 57 | 55 | 53 | 51 | 49 | 47 | 45 | 43 | 41 | 39 | 37 | 35 | 33 | 31 | 29 | 27 | 25 | 23 | 21 | 19 | 17 | 15 | 13 | 11 | 9 | 7 | 5 | 3 | 1

It takes 100 times if we perform 3x3 conv op. to reach 1x1 from 199x199



