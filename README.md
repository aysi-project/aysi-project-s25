

import os
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from matplotlib.image import imread\

!git clone https://github.com/aysi-project/we-need-help.git

!unzip we-need-help/ISIC-images.zip

!unzip we-need-help/ISIC-images\ \(1\).zip
!unzip we-need-help/ISIC-images\ \(2\).zip
!unzip we-need-help/ISIC-images\ \(3\).zip
!unzip we-need-help/ISIC-images\ \(4\).zip
!unzip we-need-help/ISIC-images\ \(6\).zip

folder_path = "/content/we-need-help"
os.listdir(folder_path)
