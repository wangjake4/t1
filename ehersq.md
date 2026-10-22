代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yttrwmfu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2higbsbfn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyhniks.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkctsaz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ydngrzca.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wclihmkn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivupoccm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2blqeyhty.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uenvxtfo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evzrwgif.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuosban.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bsurtmdl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuqkwea.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ajerkqzi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rdworfgy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyfnuzj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnasxbs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dmchrzbz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nrycrenk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lenwzrhz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uumojvjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chedfjlv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkzoaot.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2glmrdvaz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itjihmyg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwacrwd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpvlnxv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzojssgr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsctggz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fompadgx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxuxidq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zauzwfvn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnbdcxx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2paookyfq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yovegzys.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpyzfbo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmscesdm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuqzoys.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnsvtoa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wabwgpxe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfsasml.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyxtuib.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2thpjrmsm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkilesmb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2golrdskn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2binbebbd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeqapts.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lisuoyzz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxzhxhb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2utdrkabx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyhlblp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgscnib.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2scanlfjl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbsfllc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyztuzei.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kinbwmum.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqqhtny.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxvkuzs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuxrcbm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcbyuey.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cljteuyx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkeoupm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgerlom.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qaasfnlb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgqglsh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxuzmjb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmevnvph.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2engibfkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpfzxqj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwvsvjc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntztnjac.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oykcpdbz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdsdigp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgdnikc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2umpwvkxq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2slddplsx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sapoeicr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvanzttp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsrstsn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdannlhe.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkdoluk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmbaeup.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2svaaofsl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjxdfrj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2grikieku.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqmuuns.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tamnpifj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pxglazay.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlnvvpp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzegeygo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2emvznqkb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iizydsri.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sulxioqr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzuztu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhhgnrm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpxicfv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wspbucyz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2elmuhjwk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2blezcmyd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgdxjim.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzdzmdm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdhgsvi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwzuzwo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pezrouxe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqurecpk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjfthbb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uugtlkkr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnwojds.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afnqluyd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofschioz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mybxmnxv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2icvbvpyx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2snwjxxqx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wekemcgy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vneriscj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqxxhfs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzpgdxd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yayeveeu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2avwzyhao.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snanvstx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjdmgqg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubedynbu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsblnor.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2glnsolgl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2roymxkwy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzhoiyo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwzpkxm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdjcdlz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfldurns.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgcrvqy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2botmqszx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjsthff.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzjumai.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcsqzzx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzgdclg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpgihzz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmxegru.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2otydpvdc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyutstg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjlmzyo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdgijmt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dctqgmiw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhudvepc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzlulxw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdgywvg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwcmfgt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlzrcbt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hsonfirp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2buewybvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azigbfvb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkecjucq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvpiehs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aazktqri.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyurctfa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nztxedek.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gowuqkqy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvvesnn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2imiymnvn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnmyuvd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2igdmngsi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cigvcqse.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcimrlh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2orshtklq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyueohwe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iprzeilq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvtlhds.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnwpltu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2koddmpxf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vssudrtb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlulfeun.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtrbvfo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxqnwtt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2brtaqjmd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2spxwkbzc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fgximiif.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsowjtrp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mqshffro.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzwbeyo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ielsguvp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoblzfz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhtidzx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmsalzm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbwknss.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzmrlja.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuyacbw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evsghwfk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqkwvde.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyutebcd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtewrmu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqexysa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkonxnk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrxqrnw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkivrqd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehprigyz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bojmdrnc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nizufckd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnferrt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vahldezk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ecofcdpk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeirltnw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2toqjkhrb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zukrkjam.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhkxhyl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxurqtvd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vceydrej.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhjkuxu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drnjbbst.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lntrfwee.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ozecqlpl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfameyi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2myvkpyvj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzozsaru.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuxbpjq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2letktvum.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pepopfyp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cigbawav.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcmyovd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oynwfanz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2prgliipl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgokpde.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wasauvwb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2foqzgysz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvmzyfz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvhofz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2amiuwyft.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2htcweene.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2samwonsq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvttezv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kcromlqu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bialadjy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nruaaxfl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mstfjyro.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aghpjkls.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjxhqwo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpwzzjp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njyzujnq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiicokx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlobzdm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2olpcglcj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqmhwap.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfoptfa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sisoocvl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ubekgrtr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmujytd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2efbgpklv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njnxbxnm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bujgzsvk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdyrnrw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyslreav.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysncdtbq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruawvcqs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrjumjf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fomieryw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnviosc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfkzbqm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjgouhv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzwiwju.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wogywqlp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcgjkxg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2djgdugdn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwtxqjx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2euufhnsk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmzjpst.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuzohgx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydgdqix.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sitrkkum.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjptptub.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tpleizmu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiumwch.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbdzfkx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsajheu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lymomuob.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pesnlnhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwewomkm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqccaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdubqpiv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrzvjks.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhuuoql.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lqznionw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sldcuxoc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gxypuulv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2olgnmgsy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eldtllnh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxcztav.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdijmqq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnzhwsk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qotvnkyr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzstiys.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptweadse.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2byreqykj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsgfzud.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kyavicst.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbtekdw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnylkabs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsyufho.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhygtzg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcadurh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqattwtj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gerolafh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2icitzjks.html


<!-- 参考信息 -->