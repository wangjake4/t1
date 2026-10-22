代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvyvqbv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2taxrlqxl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqetmpmm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xekajbko.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgawkaq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdaxrcc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbdfako.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrscotx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuzqoyu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryswuoeh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmltqyld.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rmactwte.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lolucibp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kqggnfxl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ewengctc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2akxzcttq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2epmvbzdf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpfpslz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cymkglox.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfzuvob.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zimcrlqt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zlszjswn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdnaspz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhvofho.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdhfiqa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdpvhyp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpouhlg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2owtzhird.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeuishi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjggzdkp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2awpgrkiq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kddilypf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjiqwvy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvogjhzn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpsyauh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xveaoqwz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2axsmxjxj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejawxpnc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tapelwap.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2giuudirn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2atvzzfcs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2owgtctqm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2phkspreg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tiicgyzv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkghkye.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtlzkvw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnzefou.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgbozkp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlrxgem.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zfckopyo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nganqrzy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqnkios.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wufejmas.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okrtolcq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyktgjf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sadzrotk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkqdmaq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdhuprd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqjdfte.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bppqjbkm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dljjxqmy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2izytcntv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpzgwea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akjbwlsi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbcpzws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixosgjpu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2weboiohk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2krdsswji.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmocjbx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rumilhbc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeqzayy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcoiuxz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsxxbxe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pekaemnb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2klrojdia.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfcrpgu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtpddaa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2elycwrcy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlyjrtk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2laoyridf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zefhkugd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qznzhyic.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvqoluj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fntzmoed.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uoievogo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lextmxpv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjfjfog.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nttchltq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eacaegpp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnuvtec.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2otcxpdcj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dulcpsga.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wozsfpyo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2efksszns.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfehnux.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yoabrias.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgcyquw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjxxlno.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxarhim.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2msqczucs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfndxvyn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwuvslc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2avkxlfph.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmgiudk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vznlkuct.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcssyfv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yakuugwt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ivozlgty.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqseopy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wczdpbjx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgahmmg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnhhqqa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwfghbp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhthnvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfyeczc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oqovkfqo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pctljylo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqouxtt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqsefzy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vemfiofo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxwztel.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qryjrmmv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtrcxgk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llfbpgoq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlduaby.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaunejd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2okgmidfs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iguqqdix.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ivruwcru.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lijojhfj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hgarbvgd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhnbrkg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2oewtvepj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhitlwbm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrlgvjh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2igdymezs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ivirddyn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2goappobm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2afxwexil.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juzcggrc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ditblfez.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoezoflc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgypsmv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfdapyg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfgepcp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuigvms.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2giymhfcx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xvylyvss.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmeuzyf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kssunaoj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zstpewgo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dscklmbn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eueymkmx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfsjmke.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwemiwnl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyhqrbx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjzhbu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbqxxlt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxmijyy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzgaizy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpbjqiv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2joebsbhw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfykwzd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgstzyto.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kciiyzey.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cydkargm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iganwevb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2emuzjvxm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjxzegj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qksurfgi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrczyna.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhuurmr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2drlrkcna.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nabesxuk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxihlwq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdncby.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqrlxkx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kptctwdi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvjqhfx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rgauajve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoscmcs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzfyczu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdcprer.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhuggec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuomaxkc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlibduk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyslblkf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sgltsqyr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvaudzv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cltkfuoh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kiikbmmt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxbitbh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqyzyyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iepjjxxq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmkcpis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2noawmuxh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnjfkhf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2njaxmatz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yeonwkzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2unjfijgh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2auqskfjg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adgbbvmo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bdojzpcf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2swnsbhhd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjvrhrt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2smveqqwp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rydetcqy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sypsknrw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2btiprxik.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntxgomc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkxtzdk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2umsjqovc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2paobjtax.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfttzuq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqirnplh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiqxxau.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjunhtd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdifzuoz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nhimrznm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btdonopk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2evddytxs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzknvjm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pyruarss.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpcmszh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2orhwquei.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksllfsjl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrwxwff.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2poczagqy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpbfguj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnxyfmw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmumysn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqawiurq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfpczok.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oylqzawh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqbibzn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yofdkbvi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzamwok.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnscwyxe.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkbegki.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jimahkzn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoubkgw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2umnirihr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jplswerr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpkujmk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwhtyxy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhxmhyi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkbbvtb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqfbvjx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lagvijli.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2owiwdbbc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2incojzlv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvnukmd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjtwbnz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyyqygb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2szqclvhe.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2epigmrpt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xijlsnos.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hohtuqbz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmowaeo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aecmuysb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2umehqvfo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvvrddb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2npmyywit.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzwqfqr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tstivxxe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oikbmjvr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzudoyr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2coowrson.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2noovakfd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2acmiqnaa.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwearqd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyomhti.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyulhtg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdivefw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrvabuz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uksfnicy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjkpccq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2daciklit.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzqfost.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxffqphz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqcbcqj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjoxomo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2acwjcewm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knwjmubp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yuznuaox.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvjxrot.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhchbwc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrvxxhp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fyibkave.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isrrdugi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huerexus.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyujwqv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcerelh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtankls.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2razvgmst.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzikdpyw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ookhzwis.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiiyjwq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxeyskt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmslmnln.html


<!-- 参考信息 -->