代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evmaodvy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sswrjxrb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nabnlgpb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxxggvc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpzvwek.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsvmvwv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsatikhk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgvirvi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvlornb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbivbzdy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqgrzvn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwezkeef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtlshgx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbmwxhn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgaysja.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzaiqlg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dedqhjpo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoipsum.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2idocyhdb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpvbryn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hifoxsyu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jptkqsok.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2odoakxlf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2efuozqpq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wexndmvs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odfvnsxh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkupsab.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2djopljrw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhxbicz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mglugkya.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkosskno.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dqztktem.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpygenak.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdogjwn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxflfkbl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2duwnfdtm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzhagko.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2knyweedm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndagnlcj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeosogh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pitrpjwn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaxmxsn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2chwlxvpx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uwchptgp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2atqyfbeb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkmyhrl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbbzwbt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zliqfear.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fayrmpwo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwpekzc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxfrxkq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vedtvbhn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdredho.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrbqnyf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kphedpxd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqnucav.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jboauqqi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjsbrqz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osdwflal.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2augcnrbb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eytxpkkq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyhurci.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zudqcugt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swmtomvt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfdnzty.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwejhdys.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2idcvlkyb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfujeik.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtwdyva.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbrihee.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbsvbyc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uktbnxsd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iprngeuh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yeczwmkd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxmshmv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulmskkh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2weoyobkp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqyptaq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cagnksum.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfinrzpv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsagrgv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxrrmkc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dovpoukh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swomuoek.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwafycb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2opahuwlo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqmqlei.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buxgljqk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwhebdd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hllepmyz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdabefxr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnuraok.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsnmuim.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jiommfco.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmohvia.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cuavdoml.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfdxffd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fumfgnvs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kumvlvar.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gknafqpt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgavqrlo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmibyzyt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rikqagmi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fxedzamg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lucubujf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2brctozfy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqolvye.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lwobuayl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qllqgzsr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdxfbja.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyfmnws.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vajinrqi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoqwywl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqjmbhz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuczogwq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kngtafvg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dlehymnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2areyjotp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdmqumj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxbtazq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjlehth.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwalqery.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjdwoym.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgarnhd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsgioan.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2skengisl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcldcrc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vufdcmjp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qksxmsaa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbuqnyp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhmoizy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbamkeac.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjdpfih.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmmjoea.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpdxysm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2igvcndcs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwastbtd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgaulaz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2daeriqal.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uahqnyza.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sqapflwh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2urgiumgx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mihnjfnq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drkkaizd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fofvahyc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nziszsth.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmgtjsv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oowmioyy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lyncrcsz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcohpwbe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnyscwj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nojsczdt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2esututxb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djkbjedf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jepaauwj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2prtsdqiv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oooshrcd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbaikvk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2atucidgz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcsopgo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqnvclv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2daiwuwoc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hflxhfef.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzfptqe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imubwumf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hofhyqpd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kyivhufd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnbnnkg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ocifbntj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfvccfb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqsgesw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkxmyys.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2onsnoqce.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxhugkh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lotmxklx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xapkyrmx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxffhfk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2htherhth.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2buawbdbo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnavvyv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2udoxuyif.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlbwncl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ammysmjx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcnkevm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jreooama.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaadihn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpzvjxv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqltpht.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnszgup.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tylbogbp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwwkjsa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzqqvby.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xirfcrkl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bizufjql.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgigizar.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgurvtk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxmzlls.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcgodcp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeiozto.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ztspaelk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dghwkshi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxqqgei.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mntlsyif.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgpseei.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjiwfnx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtylfrkk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kladtnin.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kshxrcrm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2muimarks.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnjkhcj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lotppddt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojajyqro.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdiikfx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swlswhth.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exmpxuie.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2adoobaxu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csrdjnxf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upmsqoip.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqaguqe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqggtvir.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yedqeqjb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzdwiqv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqvkyqs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbljpdmf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhqqkhh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnmmzdd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lacbuxww.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwniljp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfpdren.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fkarqewy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixembsv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvpjwun.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzebcfl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvoanns.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eafpqtko.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzlaxyn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jawcychq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zeitbgxj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbxittp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vajgroyi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2racnerfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzvslli.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chyagvvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvfhvvl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wfapdtkz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ljftrvms.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yjreejch.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukososah.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iavsreqf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbrwatc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvjtcd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2snpzgxzf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhipernb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpcgult.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnhayce.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdntcznw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2doadjhrp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpzyrty.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rbttggon.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2azumbbma.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jkncivis.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyufssow.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iftrofft.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjftigs.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2leolxseb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sedatsjg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtslzcu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaiiuqd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2evfuzybp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mshfzbch.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqrhsfa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiokvslg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2djvxuhah.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfkaile.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rtigcrxu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2itskyycl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vuekvphp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdudhon.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vyioqodg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2etzmvrqx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2idbeusiq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iktxtptt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wchamcut.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtflbkd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdnasfi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hszuyyss.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vairsfgn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsjkurt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfszbzfr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uiouxewj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ownmloqw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2osmgjkzw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jnobwgmr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oerinrxi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cheyfkbj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iarmnncg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsicyjg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cdszwtgb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eecmxvdv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2frgawggw.html


<!-- 参考信息 -->