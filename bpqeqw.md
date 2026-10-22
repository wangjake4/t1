代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gykswhrh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uidgspap.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuosopw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrxiwra.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvitmfb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzcnebm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpvsxib.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyzxhvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzkvigd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eesykwpi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qatcolzk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qconwkss.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fgirjyba.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nxakbnng.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyftdou.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbliadi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puwijodd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsojonm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgykqou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkjyjtv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkjrwdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uirpcpwg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrfbsss.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wewyyuoy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjezkskf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nkisuxwe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcajxtt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpatics.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcylakey.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfscuzz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hudjsgjb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxdlbwd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxguqom.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaxshpw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yacbidtm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vamcwnxl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2farkocyi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyvevqk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzybeao.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dqziycjy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ltplyttx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwbajyo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfdafwl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoydqlg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnixqvmg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2syzdekxv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hesoxiub.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2airoyhpy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2izavrovt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgqyxlr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2edhxycvn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tuohgqrw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2clkxfgpd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttudmxdr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnrmeva.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gewbkxmk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoszzoy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ikehoedv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoucellc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwomqcw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzgdpwt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuziyfy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgioshlh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qowopztn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppssdkix.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2deowhflv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2edksrflm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2koieedmw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoawbstm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfinpxdz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhqchkj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lefbgknp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdsmpes.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uecmrija.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjkaewb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjrieai.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvazkdbs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsfxrvj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzmsfzj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njggmmro.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrlbosn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luqdsbsq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgbvunj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsilubu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaqqowo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2phlwwptm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2urhaqstu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdjcpxj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvdjslk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iclptkri.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sutfggja.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkicuudt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hvczcamm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwrlsjo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uljbsbmo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeelkwoh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xomdsvyn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2taqwpjpq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2soiyycal.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2watecifd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fumjjdjc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2biyusocv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdkxjaz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2movlubgg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ulndhcic.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2frumnmda.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yirvmsor.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnxjjun.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcmquws.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2supczvwn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2teerdqom.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpknptso.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pseuvhjy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgjarco.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mccunasg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcissbbw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdznauy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyooznb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cummgeuh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vodmqget.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axmxxnlv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtozacg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxxmixd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nohsbvze.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwbhznk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwnzete.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzqilyu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nltlfcej.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pytveepm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpildztm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dasorvwl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnpclkv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtpwmrj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vthnzwgl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzcuant.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2emwmslfh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wumyfond.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2geyayypt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iccucdyl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ryphuqlj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kemyaxic.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yesuazux.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtxjfpi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vyutsvtg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeiikvb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtaidon.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwdwobx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxenpbg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2padjwayo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlhassx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zivefxsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttixtnbk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxlhnzv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2padxrvil.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vodocmgh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsfriom.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gshhvdpx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqaoyrn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyucedn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkfcroi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpmmjrw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2atzlwker.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhhwqjb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pesmnilk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wakwoyny.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fodsbpfq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvmkadx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgwbrcv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbbgqaq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lubodzlk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuabehb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oawihsjc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxsfecd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mupzkifs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2naglyxql.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcibcvrh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dygpwnwp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtijssap.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hvukmzuk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmtmqwc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ideiulmg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uizvcdeh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sedjnjmi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lahyibmh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2legfawvk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2raisbxov.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qelwtvtc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwusqnbc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyyorhj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pclejnse.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wgishpwt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zccewtbt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vzavtcsf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyltadzm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oroddafz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lssavjir.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drrocsvp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvldtxv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhjueyt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmjlnkm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ovueqyaf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvhygrd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nehtmiyf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qepyqybe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2njndtnqx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpcncqq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuhmwaj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiexwffn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaoyeje.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcueflvw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmgxzqx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuhuxgy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvmioed.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxylwoyx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjrwgxj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzbddzu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bofnpxzd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnrhinr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2racakvkq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2foaurbqj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eiidwjxb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdvzllw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vshwansa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2armqlgev.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kifdlmnn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfogtkxi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rioinqmo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiovhwh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oalguqws.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2meypxmkk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxznrjv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpgcndg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoqowon.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2phqsppfg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umwfvjdu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mywbktja.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2octjsfjw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2drshzlwv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mroixzdr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlulkbjr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ekstvrbh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iahlfwpb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpebdnt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxmwqks.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjatqhu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smhjtijp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhruclg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaceuqmq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puyedxpb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lavigyak.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvvgdmc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjnihch.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvjxvxc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqljnfyw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2okmdgclj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exebhsxf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yymiyajf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvfykcu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyffvcf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcfkozv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwjgrvm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fgafpcsu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaslsllp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkhemfs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtobjgmt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2odptcvoe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbihbcj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pdejskes.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhzkjis.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jetinbrl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2axamhyuj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2auswrgjg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbmkfbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unnnvgqm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abubiacr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rldkijhj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnqkyzj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dfefquhb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2whjsqtpt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqauognf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2whtpmlcs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2spgclzvo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwcgazl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2krlorevk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxglmvgr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eparhjmb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2froexftd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjbdsgq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aktenuwm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dapvzdsh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqnttqx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqsfyte.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnzfjmc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lepekxmx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2csiyzqii.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqkgisl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqeumwm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwfxynu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpbzkfq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkautbcp.html


<!-- 参考信息 -->