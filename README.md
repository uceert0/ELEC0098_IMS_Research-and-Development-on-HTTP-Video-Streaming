# ELEC0098_IMS_Research-and-Development-on-HTTP-Video-Streaming
IMS Assignment: Research and Development on HTTP Video Streaming.  Study of bitrate-quality-complexity of several video encoders supported by FFmpeg (or libav or similar), such as H.264/AVC, HEVC, VP9

Download Anaconda Navigator from https://www.anaconda.com/distribution/
You can install it for Windows, Mac or Linux machines

For this project, a Windows 10 64-bitd machine have been used
Install Anaconda

Once installed, launcch Anaconda Navigator
Install and then launch Jupyter Notebook

once the web tab is open, go the drectory you wish to run the code and hit New-->Terminal

A new tab with a linux terminal should have appear:

Please type the below commands in order to install the required packages and updates:

***Note that Python 3.7 will be used***

>>conda update conda

>>conda create --name IMS python=3.7

>>activate IMS

>>conda install -c conda-forge matplotlib
>>conda install -c anaconda numpy
>>conda install -c anaconda pandas

Go back to http://localhost:8888/tree and launch the:

"video_quality_plots.ipynb" file 

The file and the json files required for this code to run, can be found at:


https://github.com/uceert0/ELEC0098_IMS_Research-and-Development-on-HTTP-Video-Streaming

If you store the .json files elsewhere rather the run directory, then you will need to edit the path name

also run conda list to see the packages listed in your new environment

>>conda list

conda list
# packages in environment at C:\Users\romeo\AppData\Local\Continuum\anaconda3:
#
# Name                    Version                   Build  Channel
_ipyw_jlab_nb_ext_conf    0.1.0                    py37_0
alabaster                 0.7.12                   py37_0
anaconda                  2019.10                  py37_0
anaconda-client           1.7.2                    py37_0
anaconda-navigator        1.9.12                   py37_0
anaconda-project          0.8.3                      py_0
asn1crypto                1.0.1                    py37_0
astroid                   2.3.1                    py37_0
astropy                   3.2.1            py37he774522_0
atomicwrites              1.3.0                    py37_1
attrs                     19.2.0                     py_0
babel                     2.7.0                      py_0
backcall                  0.1.0                    py37_0
backports                 1.0                        py_2
backports.functools_lru_cache 1.6.1                      py_0
backports.os              0.1.1                    py37_0
backports.shutil_get_terminal_size 1.0.0                    py37_2
backports.tempfile        1.0                        py_1
backports.weakref         1.0.post1                  py_1
beautifulsoup4            4.8.0                    py37_0
bitarray                  1.0.1            py37he774522_0
bkcharts                  0.2                      py37_0
blas                      1.0                         mkl
bleach                    3.1.0                    py37_0
blosc                     1.16.3               h7bd577a_0
bokeh                     1.3.4                    py37_0
boto                      2.49.0                   py37_0
bottleneck                1.2.1            py37h452e1ab_1
bzip2                     1.0.8                he774522_0
ca-certificates           2019.8.28                     0
certifi                   2019.9.11                py37_0
cffi                      1.12.3           py37h7a1dbc1_0
chardet                   3.0.4                 py37_1003
click                     7.0                      py37_0
cloudpickle               1.2.2                      py_0
clyent                    1.2.2                    py37_1
colorama                  0.4.1                    py37_0
comtypes                  1.1.7                    py37_0
conda                     4.8.3            py37hc8dfbb8_1    conda-forge
conda-build               3.18.9                   py37_3
conda-env                 2.6.0                         1
conda-package-handling    1.6.0            py37h62dcd97_0
conda-verify              3.4.2                      py_1
console_shortcut          0.1.1                         3
contextlib2               0.6.0                      py_0
cryptography              2.7              py37h7a1dbc1_0
curl                      7.65.3               h2a8f88b_0
cycler                    0.10.0                   py37_0
cython                    0.29.13          py37ha925a31_0
cytoolz                   0.10.0           py37he774522_0
dask                      2.5.2                      py_0
dask-core                 2.5.2                      py_0
decorator                 4.4.0                    py37_1
defusedxml                0.6.0                      py_0
distributed               2.5.2                      py_0
docutils                  0.15.2                   py37_0
entrypoints               0.3                      py37_0
et_xmlfile                1.0.1                    py37_0
fastcache                 1.1.0            py37he774522_0
filelock                  3.0.12                     py_0
flask                     1.1.1                      py_0
freetype                  2.9.1                ha9979f8_1
fsspec                    0.5.2                      py_0
future                    0.18.2                   py37_0
get_terminal_size         1.0.0                h38e98db_0
gevent                    1.4.0            py37he774522_0
glob2                     0.7                        py_0
greenlet                  0.4.15           py37hfa6e2cd_0
gurobi                    9.0.1                    py37_0    gurobi
h5py                      2.9.0            py37h5e291fa_0
hdf5                      1.10.4               h7ebc959_0
heapdict                  1.0.1                      py_0
html5lib                  1.0.1                    py37_0
icc_rt                    2019.0.0             h0cc432a_1
icu                       58.2                 ha66f8fd_1
idna                      2.8                      py37_0
imageio                   2.6.0                    py37_0
imagesize                 1.1.0                    py37_0
importlib_metadata        0.23                     py37_0
intel-openmp              2019.4                      245
ipykernel                 5.1.2            py37h39e3cac_0
ipython                   7.8.0            py37h39e3cac_0
ipython_genutils          0.2.0                    py37_0
ipywidgets                7.5.1                      py_0
isort                     4.3.21                   py37_0
itsdangerous              1.1.0                    py37_0
jdcal                     1.4.1                      py_0
jedi                      0.15.1                   py37_0
jinja2                    2.10.3                     py_0
joblib                    0.13.2                   py37_0
jpeg                      9b                   hb83a4c4_2
json5                     0.8.5                      py_0
jsonschema                3.0.2                    py37_0
jupyter                   1.0.0                    py37_7
jupyter_client            5.3.3                    py37_1
jupyter_console           6.0.0                    py37_0
jupyter_core              4.5.0                      py_0
jupyterlab                1.1.4              pyhf63ae98_0
jupyterlab_server         1.0.6                      py_0
keyring                   18.0.0                   py37_0
kiwisolver                1.1.0            py37ha925a31_0
krb5                      1.16.1               hc04afaa_7
lazy-object-proxy         1.4.2            py37he774522_0
libarchive                3.3.3                h0643e63_5
libcurl                   7.65.3               h2a8f88b_0
libcxx                    7.0.0             h1ad3211_1002    conda-forge
libiconv                  1.15                 h1df5818_7
liblief                   0.9.0                ha925a31_2
libpng                    1.6.37               h2a8f88b_0
libsodium                 1.0.16               h9d3ae62_0
libssh2                   1.8.2                h7a1dbc1_0
libtiff                   4.0.10               hb898794_2
libxml2                   2.9.9                h464c3ec_0
libxslt                   1.1.33               h579f668_0
llvm-meta                 7.0.0                         0    conda-forge
llvmlite                  0.29.0           py37ha925a31_0
locket                    0.2.0                    py37_1
lxml                      4.4.1            py37h1350720_0
lz4-c                     1.8.1.2              h2fa13f4_0
lzo                       2.10                 h6df0209_2
m2w64-gcc-libgfortran     5.3.0                         6
m2w64-gcc-libs            5.3.0                         7
m2w64-gcc-libs-core       5.3.0                         7
m2w64-gmp                 6.1.0                         2
m2w64-libwinpthread-git   5.0.0.4634.697f757               2
markupsafe                1.1.1            py37he774522_0
matplotlib                3.1.1            py37hc8f65d3_0
mccabe                    0.6.1                    py37_1
menuinst                  1.4.16           py37he774522_0
mistune                   0.8.4            py37he774522_0
mkl                       2019.4                      245
mkl-service               2.3.0            py37hb782905_0
mkl_fft                   1.0.14           py37h14836fe_0
mkl_random                1.1.0            py37h675688f_0
mock                      3.0.5                    py37_0
more-itertools            7.2.0                    py37_0
mpmath                    1.1.0                    py37_0
msgpack-python            0.6.1            py37h74a9793_1
msys2-conda-epoch         20160418                      1
multipledispatch          0.6.0                    py37_0
navigator-updater         0.2.1                    py37_0
nbconvert                 5.6.0                    py37_1
nbformat                  4.4.0                    py37_0
networkx                  2.3                        py_0
nltk                      3.4.5                    py37_0
nose                      1.3.7                    py37_2
notebook                  6.0.1                    py37_0
numba                     0.45.1           py37hf9181ef_0
numexpr                   2.7.0            py37hdce8814_0
numpy                     1.16.5           py37h19fb1c0_0
numpy-base                1.16.5           py37hc3f5095_0
numpydoc                  0.9.1                      py_0
olefile                   0.46                     py37_0
openpyxl                  3.0.0                      py_0
openssl                   1.1.1d               he774522_2    anaconda
packaging                 19.2                       py_0
pandas                    0.25.1           py37ha925a31_0
pandoc                    2.2.3.2                       0
pandocfilters             1.4.2                    py37_1
parso                     0.5.1                      py_0
partd                     1.0.0                      py_0
path.py                   12.0.1                     py_0
pathlib2                  2.3.5                    py37_0
patsy                     0.5.1                    py37_0
pep8                      1.7.1                    py37_0
pickleshare               0.7.5                    py37_0
pillow                    6.2.0            py37hdc69c19_0
pip                       19.2.3                   py37_0
pkginfo                   1.5.0.1                  py37_0
pluggy                    0.13.0                   py37_0
ply                       3.11                     py37_0
powershell_shortcut       0.0.1                         2
prometheus_client         0.7.1                      py_0
prompt_toolkit            2.0.10                     py_0
psutil                    5.6.3            py37he774522_0
py                        1.8.0                    py37_0
py-lief                   0.9.0            py37ha925a31_2
pycodestyle               2.5.0                    py37_0
pycosat                   0.6.3            py37hfa6e2cd_0
pycparser                 2.19                     py37_0
pycrypto                  2.6.1            py37hfa6e2cd_9
pycurl                    7.43.0.3         py37h7a1dbc1_0
pyflakes                  2.1.1                    py37_0
pygments                  2.4.2                      py_0
pylint                    2.4.2                    py37_0
pyodbc                    4.0.27           py37ha925a31_0
pyopenssl                 19.0.0                   py37_0
pyparsing                 2.4.2                      py_0
pyqt                      5.9.2            py37h6538335_2
pyreadline                2.1                      py37_1
pyrsistent                0.15.4           py37he774522_0
pysocks                   1.7.1                    py37_0
pytables                  3.5.2            py37h1da0976_1
pytest                    5.2.1                    py37_0
pytest-arraydiff          0.3              py37h39e3cac_0
pytest-astropy            0.5.0                    py37_0
pytest-doctestplus        0.4.0                      py_0
pytest-openfiles          0.4.0                      py_0
pytest-remotedata         0.3.2                    py37_0
python                    3.7.4                h5263a28_0
python-dateutil           2.8.0                    py37_0
python-libarchive-c       2.8                     py37_13
python_abi                3.7                     1_cp37m    conda-forge
pytz                      2019.3                     py_0
pywavelets                1.0.3            py37h8c2d366_1
pywin32                   223              py37hfa6e2cd_1
pywinpty                  0.5.5                 py37_1000
pyyaml                    5.1.2            py37he774522_0
pyzmq                     18.1.0           py37ha925a31_0
qt                        5.9.7            vc14h73c81de_0
qtawesome                 0.6.0                      py_0
qtconsole                 4.5.5                      py_0
qtpy                      1.9.0                      py_0
requests                  2.22.0                   py37_0
rope                      0.14.0                     py_0
ruamel_yaml               0.15.46          py37hfa6e2cd_0
scikit-image              0.15.0           py37ha925a31_0
scikit-learn              0.21.3           py37h6288b17_0
scipy                     1.3.1            py37h29ff71c_0
seaborn                   0.9.0                    py37_0
send2trash                1.5.0                    py37_0
setuptools                41.4.0                   py37_0
simplegeneric             0.8.1                    py37_2
singledispatch            3.4.0.3                  py37_0
sip                       4.19.8           py37h6538335_0
six                       1.12.0                   py37_0
snappy                    1.1.7                h777316e_3
snowballstemmer           2.0.0                      py_0
sortedcollections         1.1.2                    py37_0
sortedcontainers          2.1.0                    py37_0
soupsieve                 1.9.3                    py37_0
sphinx                    2.2.0                      py_0
sphinxcontrib             1.0                      py37_1
sphinxcontrib-applehelp   1.0.1                      py_0
sphinxcontrib-devhelp     1.0.1                      py_0
sphinxcontrib-htmlhelp    1.0.2                      py_0
sphinxcontrib-jsmath      1.0.1                      py_0
sphinxcontrib-qthelp      1.0.2                      py_0
sphinxcontrib-serializinghtml 1.1.3                      py_0
sphinxcontrib-websupport  1.1.2                      py_0
spyder                    3.3.6                    py37_0
spyder-kernels            0.5.2                    py37_0
sqlalchemy                1.3.9            py37he774522_0
sqlite                    3.30.0               he774522_0
statsmodels               0.10.1           py37h8c2d366_0
sympy                     1.4                      py37_0
tbb                       2019.4               h74a9793_0
tblib                     1.4.0                      py_0
terminado                 0.8.2                    py37_0
testpath                  0.4.2                    py37_0
tk                        8.6.8                hfa6e2cd_0
toolz                     0.10.0                     py_0
tornado                   6.0.3            py37he774522_0
tqdm                      4.36.1                     py_0
traitlets                 4.3.3                    py37_0
unicodecsv                0.14.1                   py37_0
urllib3                   1.24.2                   py37_0
vc                        14.1                 h0510ff6_4
vs2015_runtime            14.16.27012          hf0eaf9b_0
wcwidth                   0.1.7                    py37_0
webencodings              0.5.1                    py37_1
werkzeug                  0.16.0                     py_0
wheel                     0.33.6                   py37_0
widgetsnbextension        3.5.1                    py37_0
win_inet_pton             1.1.0                    py37_0
win_unicode_console       0.5                      py37_0
wincertstore              0.2                      py37_0
winpty                    0.4.3                         4
wrapt                     1.11.2           py37he774522_0
xlrd                      1.2.0                    py37_0
xlsxwriter                1.2.1                      py_0
xlwings                   0.15.10                  py37_0
xlwt                      1.3.0                    py37_0
xmltodict                 0.12.0                     py_0
xz                        5.2.4                h2fa13f4_4
yaml                      0.1.7                hc54c509_2
zeromq                    4.3.1                h33f27b4_3
zict                      1.0.0                      py_0
zipp                      0.6.0                      py_0
zlib                      1.2.11               h62dcd97_3
zstd                      1.3.7                h508b16e_0
