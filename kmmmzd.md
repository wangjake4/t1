代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vppjoedd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmziaol.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdzptoi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfxielb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2unviupgw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkevkuh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoegffo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjxduiy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2coggpxlu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdqsvfq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twttafwg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjxroae.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xahjswto.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqrdwmi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcuucvy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyziyeq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2twgzglmc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vogpzeuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zokvttep.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2upphfejl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ducshrsr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjizcik.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoobdyg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2blnuvarw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jitvehkp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2msphhlxc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqwtuhc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyvgovu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2padqrnct.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqexnyk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wabafcfk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jyclnaqn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtikyikt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2isrdiucs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2abihpbik.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzcrgdg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2czzpnmxu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2trkezehk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2boainbkh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxmcmaq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vscecjhg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izktzllk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uovjpsmi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eiztippj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2unkmxklz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkixokm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qoofvrwl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xipzxcxy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpjvivu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxgzvnj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nubccdko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itpezuui.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrtywoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeinsqa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjknjtzd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zjztrszq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oplhmvjq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbunbvk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaelfgn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfcvkpd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttpvfqp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbpjevi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdqdkcb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2faxlpntd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnfucpy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuolhix.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zalcbibv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddezczsy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2unavollp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eujkybpp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqidypom.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqctwxlo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uexteifk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ooacyfkv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2abacakuu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xymkfpoh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2adwoivfm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxyrjuj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbonlvf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpzrqtg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbfqkho.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vdomhisb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfayshm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rirfwsyg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eluocyfa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cliaveos.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rptepton.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkaxrwk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzipogf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsznjli.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnodfgny.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yftcronr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwrycpg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kuixzukz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnshint.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxeqovy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhbidgb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbcudjj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mucyorrg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzlbprh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxxnwql.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wquepjdj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhueijl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mygjjrxc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zirowhcr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kikokiih.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhnuotb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zeomkljt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwimnfkr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2badmrkez.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmsfacq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlfpsim.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bddkgbvg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnqtmwb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaarvacp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2prbvdbuh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmcbwjy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uhobdpjl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfppxdm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmigpthm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nofuwvdp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlfswoi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqowkjq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzpggrj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyidmgm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlyyvmu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuogefr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytccqldf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vhstlzlm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgcccua.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ipllaxzf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2elivzojd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wobaodmr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyvtvte.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrbujct.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqmjagu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aswdjkge.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2njwlidxq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bfelalaw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2valkqicx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvsqyaq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gydeodhl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzqpwdv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2svtarqiu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfjdqp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2efkwrgvq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uloglaxq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jchijwkd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoerofi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvskapy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2shkmbdqa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqrgazt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2izikbegj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiepfyiv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhokkfsj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pczjpenx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2scodwahp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxdfzbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmglews.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2viakulzb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmqmozt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcdvbml.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ukstespd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmmhdpl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffivpglb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcdsjfc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlxrxbh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmnkifi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yilpdzxp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eofnzrwu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrsfwaw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wgceznsq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzobeiqb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaqjkdy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnplzgqa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnrxfae.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnwhhvo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtxjybo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkhffsv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uagufszj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfrmppr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umzfjwob.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hanufvqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhyebeu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxjmycn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjvulis.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2flmrmpci.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiqizuj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlqjawg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2exstoxqj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrgnkrc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rjomjuxd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvfmqnt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrocqci.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqrrcjs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggcrcuo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2okocahzo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlmlgik.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2htujpqjx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgvgcgu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgxcqib.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaecojp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbizxsnx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhlvuui.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxhkrkc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qenfqxga.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2deiapaze.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evbrzqsv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2psjulpfw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhlqotb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwklasw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rimyqdmp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nqomtzgp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oswrklih.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgkrkcd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtctsai.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpzhqc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cewquvol.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfchiur.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rggiyftt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2afpxijyv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iynsdznc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzacyka.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmfudge.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxhhwqg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aehhminz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nvborqkg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoxkpee.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzlzsjb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoxjjlp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hvosnvhq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjdonr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxtnoqn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlelzwts.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmkxjdi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmytiruf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjkkgzq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iucvzcoc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvyeipc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2frrldmgr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pctujczv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dljrnyug.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqsskxf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sliinoww.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbeyafv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbuuesk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zubiglyl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpzpqwx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tljndsob.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2esitjzdn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoxdjhq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifljjdaf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcmyxzp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qessvksn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atwsdrhw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxvvjtz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2coinmtvv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzyamkf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umqbfwvu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2luffyvbp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmqbwon.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqlbgrg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnobycds.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2efgjabjx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mbunagzt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fogvxuxi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrquvsm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqctmhvn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bejmkrei.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwgkwdz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjxxlex.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiemisyi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcqzzif.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlljvic.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2csrebcsf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcocmkrj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbwhdow.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dembadxc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cedaouve.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrtrrum.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlchunxw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syohvloo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtldkho.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjymzbg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2futfgcox.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmxhjgt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zadosiqd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yayypfsk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbdgsde.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwthtqk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzrcudr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qehrrknd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzsylch.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2roabgvlk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jupcbnhc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnvrrmv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwucpgkf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpbazni.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafwvbvj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qxznyvgz.html


<!-- 参考信息 -->