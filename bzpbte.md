代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzklghze.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtmaifwmnz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtnfnjltbo.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjfvxeuo.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtrmmfytcx.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gtktvsiqqq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtaiavhczs.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gtbmmhswjm.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtiyydtvum.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtwijqijli.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtsoskdehx.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtgkyhraip.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtbyhqhecz.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtmhudgsfy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtstqvzolz.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtdhvbnohr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtemthrksi.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtofcjtbfn.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtufxuznkn.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gteawkfaql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtzgbpclbl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtqmusulsl.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtzbowgvfh.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtkodcfcmf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtzevqqjkq.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtgnlebgel.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtzdrklyxp.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtejwisbck.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtzgwrkfjk.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtiwptuyke.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtgcydsbnr.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gteypgbllk.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtmotvrcks.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtqfquxhpf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtamiyrelf.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtsxgfesgn.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtzdevcobo.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtoynhjxag.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtzpknhbwn.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtzdvmdyii.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtyikkvcls.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtdrupjint.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtxicqzwje.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtoabpthck.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtupyyfcci.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtvihjbxyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtjcpvdoio.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gttygoukai.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtpkkirvlu.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtncsxmbta.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewllcgqm.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtjbdqvpuh.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtiemynqcz.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtddbmhetw.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtgjnyhrgv.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyxdnazh.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtwqbxlaxd.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtquzmhmxi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gthcexslcg.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtosnatx.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtfkhtulpw.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gteckkrizy.html

#endif
来源：http://dali.guannengcc.top/Article/details/gtnkchoetr.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtpqisqpwh.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlpuqjhp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gtdpcjtunc.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtobskylfu.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gtjcrbtrbh.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaufjwdb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimgcvjtf.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtzuxavwbj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtilucvnla.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtzdhwlfda.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtmxasmruc.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtrehwauwq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtbricyrak.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gthhjihkrc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtksogehto.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtzrlseazz.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gtrcpxicth.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtfmbewtje.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtlxmzmono.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtbmamzjhq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtxqbjfetq.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtmzzdvfye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtaqhhvqxa.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtiwryyyao.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtefaxwajn.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtblunngyp.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtsskkgojf.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtttqvbths.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteygantku.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtmvzjwjbx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtrumbzvyu.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtcgvsvufi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gtfzkqtwgx.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtqdofligc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtwochnnaw.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtfjppncmq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gteebdefzx.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtkhmrdrky.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtfhynmbkj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshkddjlv.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtlzfzmmfy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gttwbsspdh.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtuxtojrmz.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmusglcqq.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtrkppwvka.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtjbbipqia.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtrkxlgnec.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtgjolkgcn.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtpprqiovw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtollfzotz.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtknldbhuo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtmugepnbe.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gtbbljevhp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gteqjdufmf.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtdpxvcmuq.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtghtslqwy.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtbzsvdmyf.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gttbuwbuel.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtabskqcse.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtjnfdbzof.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gtpvvygmxv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gthpezdgzx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzdloahpf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gthpcegfwt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtaqbmitnt.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtkhooaszc.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gttplonkto.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtgzrftebf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgfobqzp.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtxlervnwu.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiqxkbxy.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtylrdeegw.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gtkeqttrvv.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtakkezeim.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtampxfatk.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtjtndynmi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtitamrdmx.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxtdwktx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gticwazbrx.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtsuolmorm.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtzwdqqomo.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtplnxviik.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtrvjgtlte.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gtwnojgkhg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gtbhmituds.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtgvbcqetd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtmmpesxyx.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gtmvbaulvu.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtlpentaid.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtdglhbyan.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gtxgkcsbkf.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gtwjutmyyw.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gthgwlnrfj.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gtcliecole.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtysmjytvd.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcpznpcq.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtvwcnczqs.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtqbzmqrca.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtscuxnfyl.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtdftowiyh.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gttemppozr.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtuwzljbcy.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtziicwtuw.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtegquomba.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtnotsevmn.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtxsgmgpki.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtmjofndns.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gtqreltwgo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtkvkffhcg.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtvqgwrdea.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtivkazzga.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gtjwbrpvuc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtwcfawsoq.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gtwtestqxo.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtonznyehj.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtrjnaiafr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtgfobvcwt.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtrdhksjey.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gtiuxobnsw.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtahbfwafb.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtatpbhjix.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtmmquzhfw.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtxzxeyexz.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtgbcoizuf.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gtllusslzm.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gttbrnnijo.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhvnloxp.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gtqmtzolix.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtrxvlppdw.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtufllifyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtmoqzmlzi.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gthjbuoypb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtesywokwf.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtvunfeorl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtyuebfesu.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gtxcetefzn.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gtfuezcmdo.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtwcfphvgv.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtiheovtqp.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtcilwsczq.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtcqxggzgd.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviksvkjb.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gtouagbaln.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gthpmmhyem.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gtcftwygha.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtppgrldnh.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gtmfqyvkbr.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtamiognpc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtqdhvshcd.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtwjtyptzr.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gtyysnlubh.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtgqgekrdq.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gtqvpymtjf.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gtbivwhddh.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gtrkwvrkka.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gtonsgtkjs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtysjvnnke.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtisiuxqkd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gtrpepvgkb.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtfxpsbmac.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtcgkmhtrt.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gtvfxlvlak.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfjjlhyr.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtgiglpeba.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gttrzhnsxs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gtwktssbgb.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtnoshgwfl.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtftsmvqdb.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gtovcrebib.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gtkaxlhjds.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gttcxtesmq.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtilljvngt.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtrmlonhgc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gturmeoggv.html

[T55] Scala：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtmxfimgpm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gteixfnqof.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvxguiar.html

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gttblvwvno.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxfmkjdq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gttyhfbsij.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gtzmnhwbfd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtrndtpnyn.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gticcmvnja.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtrxthdajp.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtxcbqxqor.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtgjridudg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtptsmjkkd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtiozcchaq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyfhjctzl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtmjsmsbow.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtxacxmrrt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gteybkwoit.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsauhpbbg.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtvttzkgqs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gtclzlnsmb.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gtmkfrrspg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtrqaforve.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gtylmoewig.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtzbsvmyru.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtsiquklbs.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gtofzlpxva.html

[U07] Py：反转字典键值
来源：http://dali.chenlongwang.top/Article/details/gtmqumcnsu.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gtrbhaufsq.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gtomoujbuh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtsdiowxxs.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtvafhgnnc.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gtqrpakmya.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtzolkztkp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtjyahllnr.html

[U11] Py：生成器表达式
来源：http://dali.fengsongda.top/Article/details/gtigiydnto.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtfgpylfhc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtwwanqilk.html

Counter(arr).most_common(3)
来源：http://dali.yongpay.top/Article/details/gtmnrxrymj.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gtbumprgjt.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtnmjpfepv.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gtkrashgpf.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gtwjhemuwc.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtivdzzwjj.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gtmtmujhov.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtkdcoroxt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenlongwang.top/Article/details/gthyezdotb.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtcmnnwdzn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtmpkqsmdj.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtsaqvhtek.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gtlqvdsusq.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtomlqjagr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gtgasajpsi.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxavvpezy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtrfjruufk.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gteskcxckd.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtjsottjgq.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gtyrpyalrg.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gtzdegddtf.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gtcthfvczm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gtarozufse.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gtqiizrmbo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtwhyagsei.html


<!-- 参考信息 -->