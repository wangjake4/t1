代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gojmdvca.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjvxkqz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkvjern.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjwayfm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkjvbnj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eolgwjav.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrcckcp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2antmiorj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfkjtym.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2modjsztn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkhyfjm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkndjfm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaczdba.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2anwffgjt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dstusmna.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoczemo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcbflno.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgavnvnr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqsunrk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbghguzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxfkbih.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rczcjshw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzczreo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhuomak.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxhglbd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aspqlptn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fudxsrzb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdrcjoy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvlhinz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlydwqf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhxqwej.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bibnnsbx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrszeso.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ribcjwdw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2chwiuscp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dagpdmtl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vduuahzc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmyfasr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2julaktfs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fwevmfmy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sablfibh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcilpfbs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrjibct.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2onlghnrh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhlowri.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcdbbjh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cflsqyws.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2frfagrtn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2crqloxux.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxiqjlw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqggqcwe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2siovsrjh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2doqeshjn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krlvujjm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sktowaoc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2svhovfmh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfbolpt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxnlpza.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qwijypbb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qaggwcho.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2roucbxyg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muucnrel.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2euurptzl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwrkilm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfynzle.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2smqbeaki.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qsublteu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsunvoro.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxynbxh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yguaxfho.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyxvmsr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aflotvvn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbkwqkx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onejznsg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjdojoh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vebexvja.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2akuazrxk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxgbozh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tijeobxf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylaiqwh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuqbbsk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzkqbuk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yldddesd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrjjnog.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uivfybrk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aznfqdhg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nmctzvis.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfplokvj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wdltfmok.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbedwior.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwkngsc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvegmnc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2veedkooc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmaryaf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adzweahx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdfpdvb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtfyccq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkyfesg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsqcleu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrgcqtw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbmaqxp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpxvkxa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcmidwb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhdsstk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpexurxd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yljphzsw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnqaopv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnqpgim.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmatuvj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ucskxzfx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcjakdd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cssmbcmr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eokigjoo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhwqxgj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdgtvet.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmnagmq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhidzoq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwtlqrj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrmuloy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmyirvu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fjimedzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpntyexg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnecjjum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzwixek.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dghnwnqb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzgwkxe.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwsbggp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlrtrwa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjjotwl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtqlrlo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xymyuqga.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2etssjzve.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhdmpfj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jwybkjvd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkuxwei.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtosqqai.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxmkvpu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cteicmfz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2svoyufpv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2owzfiiba.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzicgdk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldihzslf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwvmhnc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtahxygy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xahrlcks.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazfdgpj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqgptni.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjhazui.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pztjxmos.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuuqrsy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2npxpkeob.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdlwoof.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqinmst.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ensokczc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjzuybz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cckdyxjw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjualut.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iczsmloq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxqykgc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yewcmnlf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2negtlinq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lotbvrls.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mmanypji.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eevhcmtb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyjzwys.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkizcue.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnfgqhy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfouslvn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjflixmk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhqavxi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgzrvhh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnrisbs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmragaq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhirxwc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcyjjfg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2obbgtaee.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxbjziq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdyyqud.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyptzej.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyqsxev.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2txsdtfsb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuwhggo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjyspvu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xowiaotw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gexopypy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxshaht.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoddgqs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdulxgsj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyflodf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aadxiclp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdvojbi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuxepqu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzsnjcx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjxedrr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wojeebcm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfttnnrc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eutskjmy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlravyi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdzdbbw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqiklzs.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnbgwoz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvwbza.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzocnxz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxsfywc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hywrcvak.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2grmkfjwm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqeqgvs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2esjjuliv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhromer.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrhqlmi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfyxgol.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjmgihv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrwwlwm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrkjtzu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jrukxntv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcbpwmv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xixguudf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2namwvydf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpxgdzu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmngpuaq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmnathe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgyewfq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdegeznw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyupdyvh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odrsartg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bchixodf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuzjlvb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpfdkhv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2njlsopdb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ystlmyxp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuaakfq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zemnsbtp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpnofmh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2keutdkrf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zslmpack.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrowgqy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyqotku.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaqdqpa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2huhjduat.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2anwipslm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zookbfhg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkkzmrq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2swctlyxc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmlnyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2junsidjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyowjglk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqzpaxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwdoaye.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2etmwtvyw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hptokprc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoazltf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsixbsq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vcopdcjs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwsmgvh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvplers.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2trkewqtb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2visscdre.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgunlodi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwydzpda.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2esvowvou.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzxikza.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2snxyakbk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjnzfku.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2whpfckku.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmseskq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkygfmn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdzjreh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrhhdvz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2infjizty.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqvtuig.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2umfneavb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxscnxl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2woohulsk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfvqqph.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvvoptz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwszbdk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wagmzetl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvwkqzv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jesziinx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdloqui.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iieycurm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdyxgrj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfxcpml.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2avsgkwpe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxfmepx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnfdncv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzronep.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvxwrxr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrezivy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyxkziz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2naoqxcxk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2deqypctb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpoxmmh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2igkvxebo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2czyydovs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgodlfcz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2clxhlltw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2czrokzpc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcpucyr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqwgkls.html


<!-- 参考信息 -->