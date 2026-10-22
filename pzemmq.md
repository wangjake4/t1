代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmqilbu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yfltfrhx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxvtssw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qexbnbfh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aawiifha.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjalzco.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjylkxw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwdhksx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dapdaffr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdieclg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epmunxba.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxgovhg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkizqwv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2riahwggs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbbsmsm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2enxcpjig.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2otobhguu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wswssfpp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfftblko.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llfbkebp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvirayw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2outcfhev.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdbocov.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wztkrozw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lylcrxqw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoxvnug.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gryjxzks.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lfagkbby.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvltsvt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgazwmg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elfmkwln.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pktsxgis.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxchsfo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpkeaet.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qppogyjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrvcsiy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2khfreffu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nopypxxe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aznfsozb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2epjddnni.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnlqyuu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnmtdrq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqigyiwq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2itxmxcxa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgtcaen.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtaetuk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wryowhnf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnrsgrq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmjivbm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxdzrln.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vhouyrnp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbrhpor.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnxfwok.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qclyzbab.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2weuhdqtq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjtlrfl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2puztjdig.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhyqdch.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxodyosr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puxobkgo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxhumeh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftytravf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmuexaw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxocgav.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmginff.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2huwnfjpz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2svdzjaxy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbruhxd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2evgicwud.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmauprwb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ureiwooj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyupcqy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdtpjsq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbleoek.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdscrvby.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjfmbag.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdplsizv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2osdlbnzs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrefqvi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrqzkur.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wguwdvya.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnynlsu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhcswss.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qraoyvof.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pusoezcn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2slfqntus.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrfkmxz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dgplfhxp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsghxjl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiwwmuo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfpzwiq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbiaeuk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqsathr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxoouif.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czlhfuil.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuydzxzp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2proxmbqt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvidmoxl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fahmrihg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tzymcbvg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qgceejwu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2olnxzbrx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qjicavkg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jllhhtrx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpmyrdd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlamewh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2efogwygd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjztdez.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2osmyxkin.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsqzsxs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtuaxkg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjxceua.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2juhfvndk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nairvoac.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uiisrshu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnrfxla.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xthscamp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpxlxfs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qljpzmge.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wdurnicw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2reijqewe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcslgew.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjjsuev.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdrurjj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smsspppy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlodejv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioktifts.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuivtof.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2irhfdpvu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsumedkw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzklumz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzirbzb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiuryem.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpjievl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jccxeerp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhehrij.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2defzazvz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpupvxxs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrhbdnw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbfswjj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2slhwezys.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlvkwpv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2moabmage.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jaemvjgk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaflhiwi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfyiene.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wliyfzmv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bysxemhp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thnkxfpc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsthmli.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlypfep.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nfweijbz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhhqmab.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2idvpgocw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tztnzlec.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoajrfz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kferhzeg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlswdhqx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwesgszj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgagheg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpydzcgn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsrfyxe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yedzpqqo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ztszplhg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pudbyhzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsbydxf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqrkfsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiigybgf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dohmbtos.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdeatqa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrgixxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xsglexub.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oewydwzl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvriidbx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnqptyx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrxbbxb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2omhmqran.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkypdxy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpfhbvv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxwarqh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qstojtou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nacahdfc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kozjtdeu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mearadui.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbmntbd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhidmnk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hetarrpa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuwrgir.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wsitojsa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzesyudp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cswbxoqc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitqmyab.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqgkjnr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xesjyycy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnesuzd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumqmbkw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpogkks.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqvsicj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkzbxrr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvobvukq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcnedij.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swxeqyqn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfflffkc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2towkrwog.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhnlucs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkyvztf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iioeruhb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgdyduj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeoslti.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2amamvtjj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzlpbje.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eucmhnxh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjimrui.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2soerqgve.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdooyxz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlcjwwu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2whrzmhct.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdunirl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnanjpt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmjcxvw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eyozqtti.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbpgyws.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyxwknu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmbqufm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gznvanox.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tucbsuym.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxlyytv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfmbiqg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkzrldr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aljuptsi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oshyxgnd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwekjdu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2okrdurbc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yolummzm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbpxkqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2thflqpef.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjscgdb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnxtect.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvzshau.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kciebpyq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhguhhr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2obgkifyp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqghrdnv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfiffew.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuyrgav.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzircgp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpwvkmz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hupwwdvj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwayxpg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbddyyh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nflrblkb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyhfhol.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnawcykv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlnfpov.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdqvrgr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzablgm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxsddkk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzicwdo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luvpllbt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euvnxipy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vynwrzzp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaiyuwf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoajjmt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdlzdoq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tabxvucw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwtlmvh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvneyyow.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgibkxc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kueukhqb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzodeila.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxvzctb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcshtztc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hijebbls.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmvuwki.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jboatcva.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyaeccu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlzjxnm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzuknxf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yetcxmgh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qaroniuv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyadcig.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2arebsual.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyslgcd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcftypk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkxgvpj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcyxgvy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjgovbe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pkudrths.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnetfnhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdlysco.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edgvufif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmolqvvk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzhvmpf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dshyyzcj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxlrqha.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fswakihl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eevselhx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfyngkh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwvhsxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbuwzhd.html


<!-- 参考信息 -->