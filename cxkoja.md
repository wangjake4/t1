代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtfvelwubq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtmfptedks.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtmiqehqhq.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugbqeaxj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtrhciavvy.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtkscthnkk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtrtlovbyn.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtvplprqhq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtryknaocg.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtmxfntiea.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtqfwfwfmf.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gtcrnbsvxz.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtwyxpakvf.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtdnjsjqgx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtbtyjypbg.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtfmofdxfq.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gtwzsgkasi.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtcvlgpkmj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtxsbmdczm.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtukgmghrx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtbhfadyen.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtdpurbhlb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtsswsdgfz.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtxxuximbn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtueozwudg.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtfuzrgeuv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtklwdjsfw.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtnndyuaiy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtposlgkvy.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtygmpxfqc.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtxepeyyvz.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gttriidfks.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtccnzysfb.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gtcvcnlaxe.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtqyepnvda.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtuokgrpux.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtyktluyew.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtjgrcoxfe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gtzwuclwvb.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtqfhpuwyd.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtaediyxve.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtfvswosya.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtduqpmwtw.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtspjwjswv.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtpuabhqgi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtitxcervp.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtnimfaeer.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtkjgzfvhj.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtwvxwsrtu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtyzdmvusm.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gthnijwhri.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtkrbeynve.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gtdvmgtwez.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtusuaeeua.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtlexdofdm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtzsvjcpnu.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtjrttffam.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gthzhkwcpi.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtylneuile.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtivizxtzz.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtxwihnwkj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtaobkiowl.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtcjmtuhih.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtfcmpblgv.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtlmxiorqf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtjoznmavs.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gtlhmobesp.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtogdlmmji.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtwtjfkcer.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtzsusihcu.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtruqwyrkv.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtulmprzwy.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtixbkgmua.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gthcbadgkr.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtbtoviopb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtdmthtjmc.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtbhhfeike.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gttjiedluk.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtblejykok.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtnpumnupr.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtrwavkekr.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtefsyztbp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtqeyfimui.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtivpticle.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtzmxchwpt.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtgpmqehfu.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtqmlrfuiu.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtczydwykg.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gttnijcmgw.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtxtlworgt.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtmgeannhx.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtyytawrtq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gtgiytrfct.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtbhjyzpsz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtrkxsmlsr.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtxkzpqiwu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gtvpdipmjt.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtmiksyfnt.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtfsfdpocj.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtfvpdkidj.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtgysixwqh.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gthulowxin.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtncisdieh.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtdduwqwcn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtisigmdrz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtksdkgsmv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtijyqpsev.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtziagskwa.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtpcycutfz.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtmgxtrnus.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtvkqysdgp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtpclochvi.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtvgujjvrg.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtsjkxmerb.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtslewmbqb.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtawobpgbk.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtcswtywcj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtegqiioch.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gtzaxxivpk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtjukgskym.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtzncfmmyn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtkvlbjvby.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtgtbcjcfw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtbhisuwgt.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtmjbwxlns.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gtfqslknog.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gttgdmplth.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gtbqynkmrx.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtwvsuphiy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gthdcxmvze.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtwydozllj.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtxxnbpoxs.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gtjfmjiqcx.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtelhxbjkc.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtvitvfpac.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtigpzgqvu.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtkmorvxjg.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtnvelzivr.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtetzvsfeb.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtabxiuehg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtrrluiqlw.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtgzhlmbuc.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtmjrazijn.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtpwvzqemo.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gtreenvthj.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtrtryfmcx.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtfqdmwnpl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtpevaytnj.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuxjxtic.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gtyhyolgnl.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtgipaxnsp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gtmrrqpaus.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtythahlso.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtruitnfne.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtgmtsbhcp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gturlciagb.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtixljclfc.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqeoywwn.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtkauieclg.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gtglpyrkdi.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtxodyfcmh.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtfjefkcnt.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gtsbjydmlb.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyqvoxwg.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtmtbpiird.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtnggsohdg.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gturtexksy.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtxivteocc.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtzhdiqizv.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtyfmrgqxr.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtauxygvqp.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtrofrslps.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtofcpofeb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtgixazqsr.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtwjeunoed.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtcdozucls.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtbcppvllm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgpvtdah.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtidjyivez.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gtbornqnrt.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtdapawsrg.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gtvuymdhlc.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtusuzrdjk.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtubanqnag.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtbvulhaix.html

string.find(s, "%d+")
来源：http://dali.yvedp.cn/Article/details/gtwjrcbplc.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtnrgpaztu.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtefkegygo.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtafpollys.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gtgqmjngje.html

[T42] Perl：变量类型
来源：http://dali.vqdsnc.cn/Article/details/gtnrwyckpa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtixixhhih.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtxzhvzofx.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtnavsbnyf.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtvhhfuxdv.html

if ($a > 0) { print "正"; }
来源：http://dali.cheryme.top/Article/details/gtjuhxrhqm.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtuvugvzzx.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtetfzcqkq.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtjonutese.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gthmakcfnf.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtvdvqbcbe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtdaetqmpm.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gtbkjdogmi.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtumynliur.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtirjpgdco.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtjflyykwh.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtsttpegnj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtlczpkgaq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtoiqbwrqp.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtedprnjve.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtbqlfbvju.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gteogikpxi.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtigpqcfvn.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtkhjydvwg.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gthmnznmrz.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsaegquw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtqyibhqhj.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoochithr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gtbdsbqmof.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gtyebfeiav.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtwrkykipn.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxbtxkpx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtszokcymd.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtniblpgbc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtqjrbhfup.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtqixzksvn.html

for (i <- 1 to 10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtkoteayrw.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtgyubtxgg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtqejeoseu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvgdehdks.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtppaiywcn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyegjrlod.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gttsuiawol.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cdnleiting.top/Article/details/gtujwqlqjh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtyytpvmjs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gtyjvcizuc.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtnqxnranq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtahblvikh.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfyfxgiz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangdashe.top/Article/details/gtvkpfkbfr.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtggprgykk.html

list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtlmimnzir.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtqhgobvfl.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtatwfhjtz.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtrjcqwnwf.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gtunuaquxx.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtlliixtkp.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gtdihukvyz.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gthakqsehj.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezjywtla.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gtalivuvkq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aizwys.cn/Article/details/gtfmqixbqg.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gtskksxokq.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtskrmvbyv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtrzgceyql.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gtfewafwri.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtodhrrfuw.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gtogzylwut.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gtqgshvuzm.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtsnnklk.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gtgcruenot.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtbkjmjzei.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtjvsyshrd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gthzcuoklt.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gtmmmqgnai.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gttkqtqckf.html

[U18] Py：预编译正则
来源：http://dali.cqqwz.cn/Article/details/gtmnuxlsxk.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gtyhcmzmif.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gtgyvzvzdw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gtdgyabkhu.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkrhedqg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtovhzsgva.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtthkcvyal.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gtayvptcwg.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gtqivputol.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtqtysownq.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtfdhnowhw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtgknrplxw.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtbstoafkc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtjbisdpjg.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtxvoxhhef.html

csv.DictReader(f)
来源：http://dali.aizwys.cn/Article/details/gtoztkzjwj.html

[U26] Py：并发下载
来源：http://dali.gotoacloud.top/Article/details/gtobitoika.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtumfodkcq.html

[U27] Py：异步 HTTP
来源：http://dali.zdqjudy.top/Article/details/gtpktxbkgx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gtndxkjwha.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtxyqapaom.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtuzldnexq.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gtweffpkfu.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gtjhanaauh.html

[U30] Py：数据类
来源：http://dali.tanke756.top/Article/details/gtzjvhwryq.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gtgweqxtze.html

[U31] Py：单测
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupwassya.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gtnwmplmfe.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gtvlupzced.html

ruff format . && ruff check --fix .
来源：http://dali.zhiwuduotai.top/Article/details/gtiwkdlrnv.html

[U33] Py：打包发布
来源：http://dali.hammf.cn/Article/details/gtfqoxzuty.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtdpmgsrry.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtwgwlkbyd.html

chardet.detect(raw)
来源：http://dali.zhongyouzk.top/Article/details/gtecpcdilp.html


<!-- 参考信息 -->