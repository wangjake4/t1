代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2llcbniou.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aavnuqan.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwtnjao.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbqqvmd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ollzjcwz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcgbbjy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqzrvcn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdvptct.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gdclrvbv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vupojnfu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2obpkywwv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2olylhild.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdqylcv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lutvjxel.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fvplicbp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pllhosbu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdtwhmi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdfsefr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwogvepm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjadmpc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uatjnvlv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jskhkgye.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmqkmiv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcptjoqo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfwnkng.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vykeglrq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znnmpges.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfdeafo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lioswelz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjeypxg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwiwrla.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bahhbtzs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdylyqg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfyzrvv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqxweyt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2okviwgji.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvaxvvz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hihfvoen.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qudnekgg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvjnxzf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzuwkvv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcbzywi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyewbgu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrogflj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpvxfkz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtcllxo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2waucphlr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iojheadm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfmrtdn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2panpubhm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tebbqoru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozppojis.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2koraolnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqouhhgi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axtyfsow.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kznkxvsp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybrseq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmfciax.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2giyuidwe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfdvtzz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydneeffw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2phjjfalv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2saouwnhz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2diylcjvr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaeejoq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyuxndc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2flyjdoyc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jepclueo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbepreuq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpkhqxk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zorgzeqt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wltlwgsz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dytbvaof.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzbbzkx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qotzdwoh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knafnkxc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqypaxh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrwuvtm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2idzpoxov.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zieueaed.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbovpzqd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgscaihk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzhxemk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvigbor.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfgvaet.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2twgzrghn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhczfli.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2apkykouq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvexclz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xewfnlyk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiivvto.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdegymsc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2henoezwk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkmworr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgedciy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sxemtyxm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2idbzwbav.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iecpxtts.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkkdrdi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jovxgqhu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqqkacz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtquour.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dixogcsv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iavndyrz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvbsplm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwxdtla.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqiihox.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2prkcokrb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mikybnzv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfgbaql.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoolies.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsxvzav.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfjlsjj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkcpayf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrkwvnr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2apgqupdm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqfpdyv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zirocict.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvkeauj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myhywhma.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxqxpgl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewebgswj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwfvvob.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2txumclvm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2scwhsfzu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvzgqil.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzvofzb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfzehsv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdinyub.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bszsemtw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjbbgss.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezikxucl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kafqxpgp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pndhgcpw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2keakrnwg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzizyrx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2humufdrk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tshadsqh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oxztwuam.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrzbbai.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhlakgc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwumuvo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmcpulu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzpzzly.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgrgxrx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfsovrq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuoject.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqncpby.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rmayxoci.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjdgtx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlvfvfs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zddqydge.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdlywod.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxsnmdg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avcvcvdu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxilmjsi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrftzvq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxemtpq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlhakib.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyfwppt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwidkopq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2azbnkuut.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhcvtwz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlaxzbg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heunjyto.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaxuvjb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbvfwzu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pllnhrol.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeusskcu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gndppsnw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzhamfv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnbivts.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrgntih.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tszpsbmj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzbjuuo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvqsukp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nceshhez.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnvxdpu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsjpaqx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xebhhmdz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wposugsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhbniab.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcdokhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytftbdsd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obbgjtia.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrzplju.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znhluowo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2utzhgatv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2znctsvoy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzaaqlk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtyvoll.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaglymi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbwexvt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbknyyv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcmwwcw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2biudkllp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuosxug.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sodchcay.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nqstjmlw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zerxqiwe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rijlptmj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oasjaglh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpkdwss.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjqfdsd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgwmcnz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuwhkmj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkmwndi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shjyqjil.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lhacsgfg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pukqfzkj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnaozmb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqykqdq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcpzixh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2izalhfxy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isoeijvt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpiyyrm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqbawye.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fflwpfvg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouokwvsy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkksbul.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyziozw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dloqjrxc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2athuwnlc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgswoohd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmefvrok.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdquoad.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fzseqici.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vncfssge.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkmzvzl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxretdt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2msbsuqua.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijozts.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxadsbk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kornlrzh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxomace.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xutnqwom.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ieedzqiy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2osatqbbp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrakhmw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2eddtqtud.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvnwnxd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcicsqb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nrghfhax.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjrzokg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkuunxo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwfmekl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zodvscul.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fkolioxu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlohxnt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2amyyydoj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcbcvfi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbieiqjc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2veirirla.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hiokvoic.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vogpmtgm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2npiefxuh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbkqsat.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwphkyoi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqptpyx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhzbawn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2snnqvots.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvijojmu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxggzos.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bernagfj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wicdgyrq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlainbaf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frfbpdzj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyzjumu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaprram.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmqqrcg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egttcysj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bplikglx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbkncqj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwmbobh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbouihr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqtezlf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxeisuc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmacdomb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elmqtnyl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqmrcun.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsttcmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuiamrb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsmrcki.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zewqeada.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urfnsjdc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnkyfds.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxonrwz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eetzdcec.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdwxkri.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwzsssm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsnwsnb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyqsojm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeojnaj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xdavawkp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnurdqw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2embyaqmd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpoplma.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wenfndsl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvdrdmg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qkldifdp.html


<!-- 参考信息 -->