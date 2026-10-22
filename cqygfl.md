代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nacbonnt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dntcflpw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qtngfqsx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yaupfcub.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hknckbwn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlgvsri.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcbvjul.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kswevyov.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2goenboiz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgwtzwo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wysykzzw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhtsvag.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoyzxfm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsnlqis.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cypibdrb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdolmpwe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2diboxznv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbiqsds.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scgchegn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rzowzkws.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2duysnpwb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lahodifn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2azpwdvru.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2szuptuqc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tonmxlqq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gahovcfi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2honvpbxw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ekycvzdy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2prqxjpgo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqrfwcc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhhicev.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiidoyj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbtxqld.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtbovxt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2weuhtsxj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2povaivzl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkzmppr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjnkxbl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwmobqa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcffudh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sexdyaxg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oczgzkoh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdepjjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfgflel.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2snhypqvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzwcrvz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeutloa.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxcrxrh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmsvypn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkewajz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2txqqjwav.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwyuqgn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2blyjgwis.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2abmoinok.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgkoejk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2axngbawa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwypzyoe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yswqhegw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2azpbgpzt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jfziaigs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjfjzh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2szwinytc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmmxsrx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdrjntf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2phcbjmsx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgqaaex.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlogngmj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hydrvgov.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdecqkko.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2glrjxmrv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrljytw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwearbq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqnsdyd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsdsiec.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcafvmzw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvgicz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2btsjmxbs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eanpkpfg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhafarbd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgtsicx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owuailng.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwgmduj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfihbud.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxcvawz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iipmlkaa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqruvfyf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyzxett.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mookgxsx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkurngdn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kgomcpxg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2euaymmpu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rckzmbhb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfhgkuf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcusehk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrgcnul.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ebojisdg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvxeihm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wmknnlng.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgemblme.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dnswbefh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oidzoapg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aofluixp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2phpiuxos.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skypxxvq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2goazxyze.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlhloqu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjccppna.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kassmdly.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bjokerfy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wfflmsql.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kelwnxgb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkvltrd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxfhfau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbiioci.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlqcesd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlxcgdw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2aczeprit.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2meiouizm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oycolmzs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdqrrgp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2epjuyhxx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgthzqq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wglvyvpx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2noauqmbb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqpiqyg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cikddkdw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsxfdjx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrgaval.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gprhhyjh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzxjswl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2awhsyfkp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yerhtoai.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgvyeao.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ffabsrdx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jueorfbt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2llirqszf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lzofiqmf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjkxnht.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2soojhlob.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imgdoqoc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgsmmts.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfmlfje.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rkopgbnw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnmdmzq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drzprrzz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbkldtj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfygzje.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwskhtq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxiwqxw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrqedid.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxnwtsy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcibidv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pifsjldk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxponrj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtbraur.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aivuxdtg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hokaonvo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjkfyhr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiulhev.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dvokshjz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uexeujvb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2isjmppek.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kguadayl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoreslo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnsqwwj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjdrhsd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcqasjb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwibjgk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoajoqi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcpktnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdbugdo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsgzrky.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2orzqjsug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdppvplf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aivdjfnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mouukcaj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxteasea.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfekenr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsezwbxb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bosdbxys.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeparow.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzqaura.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcafpry.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqefqks.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vaghyglp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2atbxcynn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dtywinwx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2csffiajv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbddywi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzgmafq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pqobrfqk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjkypsp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuototny.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbmxnnn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyoecsk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpuoryb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uifbqayk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2quehbkwm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrnyooo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzrcicl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvvnimu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmghfjiz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2djcdclic.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoxwglg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjtqhot.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcxqctb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyfxynb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyjhcdm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmvxznm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tprbevrj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sidwapfb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnspawys.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2grapfhht.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2svrdsbym.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqesmev.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rofpyhdj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqcutjm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlikwrul.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jqarfgwl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlhjnqg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfyboyr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2axggujfu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2trcmkxvb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaikoqr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyrnnmn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hurplgig.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2optuxlkf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwklcwlp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wozioxtv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2karcqswy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cywtcbmg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzuuezs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2crrreycp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2afwmlgbz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxivrcs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2omsgwkid.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxrtesm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2htejekxn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2macqyicp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oivxgseh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaqdgor.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nyitrmbq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2puzljfml.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2axsnudku.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqldzcd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2odjlxuir.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrulgkb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjotriz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nikygpox.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjloafgt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaspptc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yumfdkng.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2myrezcfm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgkhqow.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjdcpxe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2whcopcbk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkfemqa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkdjphl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwodanft.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zydhdlnd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgrnhyc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iovgvrhw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bidfrqhk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqezkxja.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oyakipxn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huahsfek.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2flcqlcko.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmxkneq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cgekjidl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdbtsdb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmfyfer.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrimfyr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbftdut.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjayadct.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwzxpvy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaljoyk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apzugggc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqdgerc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfcnibl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvtiktw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjaywaz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2otpzsuxh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2glhjrfky.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kauxcssc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfkzogm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dokguuuc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlxnwcc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dxofgnpw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sregbble.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjkkbua.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqxxwvb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tfecuiqx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tbluxpfy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdidbdj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsogqkmi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2okeoobqo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfnfvgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jonkqckk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdbqxag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfrixsb.html


<!-- 参考信息 -->