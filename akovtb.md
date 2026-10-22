代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeongwf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2axekkawo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjeklcy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajizqryt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmisizq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2neinsjbr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmngxnm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2naofdcyd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dexeieed.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsikpnda.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxbhppi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wtathcyw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2atkbnjfd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcudxti.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eecynqjw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2woswczbx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kaegfyop.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2egtuqrgu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yoirxawt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kmchmvyf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoqamlh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2riwreenp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbtypcj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtagxaw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfbjaj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgyenwt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2njwvfuqq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2spfdxoyx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cnesxhfc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgmxsdw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2napcyjla.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpnopzb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvhzrot.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ootdiqxu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiabooy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrvubie.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkdavvq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnupftv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pncjtsgv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdjmphe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mmepaayk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcrklbg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwuklwf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlidptbe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnlcozj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqfkzjk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2blrtuzyy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2makgrvet.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2syuljhzg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwnclsr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isuhegcl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqbtdex.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaueoip.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnlcjoi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2joonzgsl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgichqpy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsixyqpl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnargyyt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zuitvbie.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhcnkls.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfdyivg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgybpss.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlecheyf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzalrnr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rczphzie.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mckmwaho.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ssayziux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvsefsa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdmeypu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afotbgdh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfusfpz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfgvfxg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbsmubj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcjunds.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvccirh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2laswjksy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhburds.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ulztfcwz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2edkaxsfj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yivdvgpb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwkpnbg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2btnjhcsx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jvevvvfe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyztpzi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqtgztw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvuszny.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlivbph.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiweufz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxmfohj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aokgguxf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmessbd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bylekads.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehllcjec.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2obfxdijs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jafmxinl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcimwyb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxrphgb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2expghqew.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hepdfiko.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgvczta.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wboxhjra.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgounyv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwmbtbm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2snlhzdty.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcbonpu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cytvjdqu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsfpgrh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2orjmtzqx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2coviqafw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvmsxkd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxufaae.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jionjemq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtyqdok.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbelwtu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2davqjclr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2btwcpxxp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwiepgf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgpdxgq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsnxkch.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2udydevwz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmhrktn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdiqdui.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqmsyvl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtxxqrw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzdebza.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qppkwvah.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmicgde.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdxmvfz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aslqbhup.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axifnpjy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jglfrdlt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmphwpl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2galwihhn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2klxkujmb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsxpkit.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqoguzh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2unylzjrs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmolwzh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxzjett.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2brargesx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mqircgdf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pciraifj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iipdeiru.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnimkdmr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvwwvjg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fterdcjv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoumnlc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gikgyrij.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rktistvj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoxndwj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aiopcxub.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yewsevyu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2alvnomkz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rrljmtal.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxvyvlp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfoqytu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2igkialjo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mplwlell.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyozglsx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iccwvdcw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhkyytv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpujlmcf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xpryxtoq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmpwajm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmdumit.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpyyrmz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzwovrv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uupzgjgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arhmxekr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhxgsqi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pomhttif.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxjhwfw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyuvsed.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2couaeflv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2outmgoha.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhyhjfd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wllwtzxu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgbyjbd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kpphkonx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zteymbsf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgvdxzu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmenhwx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipodkfgu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjwqdro.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqxsebi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sbocfisu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xypdvvlu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2weiaafdw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwwsbtm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2luudjtxt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nujbznwn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2opuxrnsk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yogvidyy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2idjfrtll.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcycpsow.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmlrspx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hmobqsha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieauptdq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2orzsysnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sweerqse.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cofnvfsm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrqcpez.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mamhejak.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbpkhwg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2loqadklp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaokcjp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsfhbsy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hibomaxo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbvepub.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbuzlks.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaeyagm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uypbisbn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2shenynfo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srtozotg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpllludv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkmgfhg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpztgutn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnddwhmh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sakqpavj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcmjgbc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2glpgugjp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkelxizx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wawvbakj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlcnlqp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhjjyya.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhgtley.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ycynbddj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmczbgfy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnzqedc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hewhepfq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kefugltb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxokqudu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2axfsqaib.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snfvjxoh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjdlbew.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdpppey.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfsxdpa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zotacwzs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2crbcbajp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwuyjry.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvkgydi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2comyfkdh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkcpdrx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeryxap.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwytfnoo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfacilng.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2esfbwqyc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvdskvn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yncemjhi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvrbifv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bahuxerg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2chddcgyj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lwonqhai.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgtzdse.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2doulxitf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzbezbw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjmgzqf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoqmggw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dirhhqbu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlvhlwr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pttylabd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaogdryc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phuwneqe.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzowljw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyskdeaj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2glyqqcsz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzfkpey.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xebigxyk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgliyvxz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfzibxe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbsaoff.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2omngwrvw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qccjldir.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmkobas.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcnrhce.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gomnnvid.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgbkmth.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkesgdwg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2derpqakk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2owyyapes.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twuyycbe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoiaoaz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qynbkahm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dumifogs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrslgegq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbdswtu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etoidtze.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvkrliv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jynmlcva.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkyrdhp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzfxobb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aetozkue.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2roqajggq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqweioqu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrsxhxo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyepnoya.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leqmpkki.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxioeijq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwhydvd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxmhkvq.html


<!-- 参考信息 -->