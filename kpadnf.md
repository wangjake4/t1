代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtidbhzxmk.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtioowhttk.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtgfovljtn.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtkgsimhpt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtqkzgohnl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtrolepspk.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtzizombdl.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtshibqdqa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnghyyvpr.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtniwbjffv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gttcjiafgd.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtkutwhssy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtkftlqyag.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtmodzowru.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtydwpxsjw.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtclsrdaql.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gtpdghepip.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtwgfaaxxa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtmfmqjjzq.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtmahylors.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtpayedgra.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gttwrmptkz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjxzzrcu.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gtshlzgkrn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gteyszjhqt.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtdeyiniqe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtcpmtomeu.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtlklzbvci.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gthoyvabzi.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtjhjnurkn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtngoctkkm.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtaisyeerb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmayfxppg.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpuxmlit.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtzzpdizaf.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtycdbvrnl.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gttdfcnglu.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtujkvjamu.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtmyrzzjkl.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtngbkalmq.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtuimyrzhe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtqigcfxzc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gtnbkrbmlm.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtmvgfycwa.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtseosxpwx.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gtouzedtae.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtswelesiv.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtplvsjgxq.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtdlnanmdg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtnrpbpnkk.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gthvuemxuw.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtubpchpji.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtkvhnvqeb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtalwmvyoh.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtzqjjplef.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtzmfxcfzn.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtwjomxnhf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuxtygbs.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtcstvprqd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtczoukfmd.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtuvogjxwy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtkolissct.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtsjzobesq.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtrkwpygqe.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgzkhvje.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtaemkhgup.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtrmjznpnd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfzcvxohx.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtyywnegpu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtztxsnqzk.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmaputvy.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtovkyctpc.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gtcpyupmnu.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtemhunmbt.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtdtdbosxm.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpkczffbl.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtmxxvshxa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gtueotgwot.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtsvsxmhrp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtoyfbnicc.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gttjoltmfb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gthjhokffh.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gttjakxgph.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtqzuoomnc.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtknozybxb.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtyhnxkrik.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtlefkyzpo.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtyskxalkp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtxsvvnvzm.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gteltlmlda.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtlalpyfyv.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtwcmfzjko.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuxylmzya.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtleconjkk.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtzvxwstuh.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtxeeubqgl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtxjubqruc.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtaslcfgfb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtsmvsddzj.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtylgwfoom.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtquazlkkd.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtimvuizap.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtbninzvlz.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtuvxxrnrx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtxtpjmkqa.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtwfrwzpwm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtkpzqlyqs.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gtcnimqzzg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtqziyqotc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtysptymoo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtscpqusjy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtymlynnru.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtmxjuzcgo.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtnuuwbkkj.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtkwprhzfa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufxfdmpy.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtttfhjwfh.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtxapyxtei.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtfllpkfsx.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtjcakdvvt.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtjgyisqst.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtcdhoaddb.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtcalhwkmv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtgiihumjl.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtpunynogi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gtdhnptvna.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtsvtjtomb.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtfyywkifz.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtkoizxibi.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtnfokkzkt.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtmxhtrcwl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtvhpgtdte.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtexokylic.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtatwaiarg.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtaotomxkf.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtrnqnhblr.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtzafokbox.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtnqpoicwf.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoadrbomq.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtffjaziud.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtdnkklbrm.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtrfrqpuxi.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtwzxomshy.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtixkvpqyx.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gtxmkcazid.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gttqramvsu.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtxwunrrbq.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtlefcltjm.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtygjnehei.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtfmepcbio.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtkprtoztb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtpoqudodc.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtmzwhswpg.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtdqqzbxqe.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtvvdcelha.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtqhjsiney.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtbogkrcpc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gtleejnhfj.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtzgpuzqgr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtxfsocltv.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtzpvurdte.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gttfygahgj.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtvpajiwsi.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtzhzxowor.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtpldwrvno.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtlohxsyse.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtbztpedzy.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtopcimofg.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gtqrmkrufc.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtefuejnts.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtsgjfnusa.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtebphdyai.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtygwamavw.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gteugprhli.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtoackkswn.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gtkzxojdkx.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gtsrpdlejh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtxtoytbzx.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjjyihcn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtallntcct.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gthvjdfgzx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtkxsnozhp.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtlhjsahwl.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtkknycmvp.html

[T37] Lua：字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtueyfwenp.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gtiparrezp.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtgbdikjjc.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtdzbyrzem.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpyzdgxw.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtrxdzjbyb.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtkzoothcy.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgvvzbps.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtvillmbib.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtpkwdltyb.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtquknuble.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtduzsslmx.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtdcvknksh.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtgysqynql.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtivujvyfn.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtcsdkbolk.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtpgxpupoo.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtmkdsaany.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gthcrrhleq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtidygtcjm.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtsmcciotj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hfpthk.cn/Article/details/gtrgfjhwmy.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gthnswljos.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtsudakzus.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtnrhovheu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gthstcepjy.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtzpxxcvbr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtffftlenz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtvlwttnin.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtalenxlpq.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtwvmymntk.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gttynysppc.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gtbepvmowj.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtykbdzkdo.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtlaxbrsrq.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gteyjvslvf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtsyehzpcl.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtzmdgeylr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtlgjpnfvq.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtlhocuoli.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gtngmhbpxp.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtoehmxngi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwewyteeu.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gtgbeenorn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gthcuyovrw.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gtjjqmpxcf.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gttubpheyt.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtuckxibza.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gteyugbeii.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtirnngemn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtyspczjjt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxtdwbkj.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gtrvbwzlgm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtjleltjmw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gtoeahijse.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtkkwxjvtb.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gtgjsmfqsg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gteitzcelx.html

[U04] Py：变量调试打印
来源：http://dali.jinqigfzy.top/Article/details/gtinaznapy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqnzungm.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gttkfpsaei.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtvonwljqo.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtiiojuomi.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gtvjzzceai.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtfajpwhkr.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtwjzsdsor.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtnqsqsmtu.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gtpfkxpixx.html

[U09] Py：字典取最大值的键
来源：http://dali.9152youxi.cn/Article/details/gtloovsdam.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtzhweohgk.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gteoiknimj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gtpffcdghb.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtdteczkmy.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gtohkhzmgm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtznbeqwfz.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gttdouiove.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gtghpszprw.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtcolrpixn.html

[U14] Py：分组收集到列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwmzcedv.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gtzumsoevw.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtlgligcxi.html

t = time.perf_counter()
来源：http://dali.sufxvd.cn/Article/details/gtojagcvnk.html

[U16] Py：命令行参数解析
来源：http://dali.yanxiufei.cn/Article/details/gtyvuwwcyv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtsreblcqc.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtiqdamvbi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gtovyvbbud.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gttdvdgkpa.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gtzpjzpdpm.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gtpnkqhiig.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtthmypiea.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtplpifsdf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtmuuekowj.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gtlsqczujz.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gtpxexguvz.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtwzpobizg.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gttrktinlz.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gthhvcmidh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sxryk.cn/Article/details/gtxhhyvnyd.html

[U24] Py：路径操作
来源：http://dali.chenjidiqi.icu/Article/details/gtscvzcivf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrajlidcq.html

[U25] Py：CSV 按字典读
来源：http://dali.tianlin.xyz/Article/details/gtshwfsdop.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gtsufsngue.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gteiuwgrox.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gtqjlefctt.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtiwyhnofc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gtxdkgezev.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtenbdpdfs.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtihnqxlvk.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtvmrckxjl.html

@property 与 @x.setter 配合
来源：http://dali.shzxlz.cn/Article/details/gtnpcjgdyz.html

[U30] Py：数据类
来源：http://dali.yuanzhike.top/Article/details/gtgtkjyrfb.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gtiewsbfrb.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gtunffyggd.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtjwrdzjjo.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gtdabbprfl.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtnagmqroo.html


<!-- 参考信息 -->