代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtpcxwdyps.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtzuivsoct.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtqtsezjba.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtafsvjlob.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gthbljvqwq.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtbtmfzacz.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtikkslncv.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtzzyjfihi.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtqomxpcqr.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtbcqvgmtf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtsrtstuxn.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtxxdraqrs.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtzusgbuxf.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtidjjmqxg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtnxefraiz.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtobvfvfjy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtmppqsbxn.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtenmpzyap.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtylovcbmh.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtdkwtkfta.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gteomqywad.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtfnytdrkb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gtnrrgjbtm.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtoouxzzsp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtjgylczjk.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtrmvtmetl.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtdvitucqi.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtsacnqbdv.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtmyfnzsxq.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtouyenpmo.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtferfaetq.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtepqjftol.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffyfdjlx.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtjofwwend.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtffwaosia.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtvkqebeec.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaksnsppf.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtpowfkfzm.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtyfccnydx.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtokbopjft.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtnprbgksk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtokwjvkbo.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtcqveqnwp.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtzvxxoyjf.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtbdiskbqw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtazzixtzk.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtioihhlxq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtgwflannz.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtlxusekld.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtiiutrhgz.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtsbxjrxjc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtqjjisygk.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gttnevnmuo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtapxumkar.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gthxcaywsj.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtotltxakd.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gterrvewjf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxchbtwf.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezuvxgte.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gtupqgvwch.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gtpfwsiyms.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtyecrybgg.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtnosqvazr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gthbzwdklj.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtjuqtfnfr.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtfcamrtid.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtgkchoeqk.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtsxxwlsvs.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtqfezsybt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtuybytkfp.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtcstqfaec.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtoaoaggyh.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtbxgfdjdg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgjoljvcz.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdvwdmcw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtxvcdttxk.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtavcbccmf.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtmgwaamfd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtlpbnxadk.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtagjxbczm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtlbcdiavk.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtywfhqrra.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtzqklpuov.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtnrzbtviw.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtxfwrhxwe.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gthyozqofb.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtcsmooqwx.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtwhnyvvvm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtbouetyfq.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtyqwtpolv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gthcppjpet.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtpsjtysas.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtigswupkz.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gtidirdwgy.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtashjkbuv.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtkzxdeecy.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtvtaghops.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtpojtsepj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtxloinghg.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gttrihkvix.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtibyeqixf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnssdyrhj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtqlvzjigt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkwwwjopu.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtggplpnag.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtpztdzjun.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtuoemwudv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtcpdeukww.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtwunklety.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtpebofhgx.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtmyzlckht.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gtknsfrnwq.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtddakfsdx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gteeervkvr.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtutcoaqdt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmttkzwos.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gteruorxhd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtzddpskle.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtywqvwmit.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtpqayjpfx.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsckhelza.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtbojpaorc.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtijihimkd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtnavhrjsg.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gtqfxtwiol.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gtmazhbvoq.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtigihpzno.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtkugeeeqy.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtuhkvjlzc.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gtzqsirgmh.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gtopzmmxav.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtyfdorpmb.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtdyezycax.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtmjjnbxlu.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtaalwaitp.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtehocaxcp.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gtbhsrsrul.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtbbhqqnif.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtkpiucqsf.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtdlcqqsgd.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gthmonyqsk.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtkdohqrjz.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtnxhvmfno.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gtskxjrzdr.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtilkilwtr.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtiyjwtpzc.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtjnybfymr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtjoavkjje.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtptiyaety.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gtwmstyesw.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtbjegcvph.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtflhiubid.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gtcnwnqhjr.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtkjxisgug.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtltulqwpm.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gtooezleav.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gtgsuqhgvr.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gthyydolms.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gttjietfjo.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtazyvhzsb.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtmnfzwnmg.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gtsknmdhis.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gttpxunmsv.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gteayxntzu.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gtqhnynqot.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtbzutscxn.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtbampkayj.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtegyayxnd.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gtnfllnpac.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gtyyqsfkja.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gtyxcmkegg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gtfrciaxyr.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtnpjaqsqf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtotbmizyn.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtubblrtif.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtpwmwbtaf.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtscfrvkao.html

"a" .. "b"
来源：http://dali.birdmap.top/Article/details/gttnyfuckx.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gtgvmxokmo.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtymuqcauh.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtlebqzmmr.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gtynmafmzr.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtuydfjfrb.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtjscevbkc.html

[T41] Perl：Hello World
来源：http://dali.havefunace.top/Article/details/gtheiulsqn.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbknvnrs.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gteozaitiz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxinvsyfo.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtaqniatpn.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtckqnmdlm.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtswookzpm.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gtidgabvjt.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtsycrdeus.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gtedrrgyiu.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtmmfxivcx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jyoumei.cn/Article/details/gtqxhqgabl.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtwdskuvfl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gtnnbrcrnm.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiygwkwe.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtqhkvanqe.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gttfvfqylw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtypfauorh.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtvhlihlau.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtbzwwuicf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gtedoticzx.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtwbcvdgxs.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtjeutddbw.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtekjwsjog.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtfrhrssep.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtyjrtielt.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtumpjaypw.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtkkafpoml.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtyjqhprab.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtogadsfxa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtxeomolsh.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtvetciwlj.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtgtbrwqeq.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtuhaeezoy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtxpeqdgen.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gtnitrmtdd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtulceiakc.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadaaqxzq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gttmnmpnim.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtoccgmfxl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gtwmnoctpo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnajteuzh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtnwfxocgd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfnxufqts.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gttsdrkwoa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlebidrbz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtyjnpgdyv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtxdlryjbx.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtibvtyqek.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gtrekftchb.html

[U04] Py：变量调试打印
来源：http://dali.nanxinkj.top/Article/details/gtbbkvspik.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gtjevgkkip.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtvsuhuqnt.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyydvbjp.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gtzyzijoxx.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtdkefqsqy.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gtwgjhrzeb.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtjqtcxpcn.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtgkedzitr.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtrocqryyi.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtwywhqcws.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtryoakyiv.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtifshfqnw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gtfwttsget.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtkebihahf.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtujqjkqfj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtzmicfbsd.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gtbtmbvcfn.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gtwzgmrznw.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gthqmfgbjb.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gtnlpayqwi.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gtbqgskfsp.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtiqayapmq.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gtktnircec.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtpqkryofq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gtebebcdeb.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqthggdz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gtxbihnyvi.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtyjiokxhv.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtqagfxmnk.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gtunpzjkrx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gtluxmekjo.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gthivygogk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenjidiqi.icu/Article/details/gtdmexnfco.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gtnuudxtuq.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtlkcgakkj.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gtbvyvrjtd.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtemlvqhku.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gtlwxllxzu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hammf.cn/Article/details/gtzxhnbqmb.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gtluckrmoj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtzljzpoux.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtycbirclz.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtqnhyfmwj.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gtqvhiykfu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.andypj.xyz/Article/details/gtmuzqwskh.html

[U27] Py：异步 HTTP
来源：http://dali.meibo888.top/Article/details/gtnoqthort.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gtlkwckvem.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gthlljxlll.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gtazdfzujl.html

[U29] Py：属性校验
来源：http://dali.sweek.top/Article/details/gtacqvcgfd.html

@property 与 @x.setter 配合
来源：http://dali.gogol.net.cn/Article/details/gtqlnlmojg.html

[U30] Py：数据类
来源：http://dali.zhixingplan.top/Article/details/gtedvojnfe.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gtjvlvfrhn.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtlpsxtrai.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gtcquzvksx.html

[U32] Py：代码格式化
来源：http://dali.cheryme.top/Article/details/gtjozwbqkl.html

ruff format . && ruff check --fix .
来源：http://dali.hnxiangtu.top/Article/details/gtdwnnbfod.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gtqczdyleu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtdfvmxuge.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtihvfqkzo.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtnnwpzyab.html

[U35] Py：发送邮件
来源：http://dali.pengpengdd.cyou/Article/details/gtkpkntwwm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cashguo.top/Article/details/gtawjpvinb.html

[U36] Py：定时任务
来源：http://dali.316326.xyz/Article/details/gtxwkkiaaz.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtuyiwvusv.html


<!-- 参考信息 -->