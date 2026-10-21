代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtjbxfhjpq.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtprwfufgm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtouzxpybk.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gtcsweihei.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gtdqvveubo.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtyngcqbjm.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtczyjyywi.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtfmjyqalw.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtcweogqos.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtjzhirvzy.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtzojlgypa.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtcictttyw.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtmxrqxizh.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtwcifaoqt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtfhfjwzny.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtujszckja.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtlevdkhdu.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtciwsisuu.html

#endif
来源：http://dali.hnqzz.top/Article/details/gtskqecxxp.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtyrajfyes.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gttiyxodah.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtafwmemfn.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtknpanmzz.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtbbeodezh.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtbxpmwhoq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtprottbec.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtshgmcuik.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrystcowv.html

[S35] C++：map
来源：http://dali.yj202588.top/Article/details/gtxyngljip.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtdwamtobd.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtzffgsual.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtyvsqjqgj.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtzwkehrvg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtlpmqyjto.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtnytezhfq.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtviabxstt.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtpdwztuwu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtfptybcfy.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtgxponyqj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtslknbfnj.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtuiiyccjv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtzuucnbvm.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtyrgglnxb.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtnmnpfymh.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtffqhbrkm.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtohmgcokz.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtkwjajclq.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaczuhsv.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtxnldzedw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtlsudxyfm.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gthflpslvg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtcblxyrdy.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtpjjrjqtx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtpwzzmzmo.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtqqqjszrp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtoxywozad.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtudxwqhpd.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gthoxztswz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtmbqxkojq.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gttfnxtrxu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtpbohwqma.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtquohoygr.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtygwlwdun.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gttttkmlgy.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhsxyavi.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gteahgsmfp.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtkihbdrlo.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtlmhzuvcd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtcpqdswrq.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gttdbckpwi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gttxezfgyi.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtzrdnnhme.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gthfdbxjte.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtefzuhysq.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtgopyfpbb.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtpfwvcuwq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtmohwoeer.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtvlphowkt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtbxkgjbzs.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtqhyankfs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gtwoanlgyx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtorpsvkpx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtdkwjzrjh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmrwjktgw.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtnwefklov.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtnxcxuoxq.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtskrlvqbd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtlxvhrepd.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtzzrwwcay.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtgxbdhazw.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtoaomshnz.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtpdzyxiiz.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtfcnczqqy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtujdbussl.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtenzpblvi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtcqesvppu.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtppnvoxrx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtdfvemapn.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxwisjqm.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtbzoihivs.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gteccahdfp.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtxwgjqgik.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtbqavdvwq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtmqxrdhml.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtwuagreed.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gticwwtyzp.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtdyylhcbc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtuyeoigod.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtnortubql.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtbwpgnceh.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtcjjrrpjf.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtomfbvvcn.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtwntbqgdl.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtkhhxxqfd.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtvxiazuyq.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtoqosfjkw.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtgwrsrosz.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gthsnlyxej.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtbfqsolvh.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gtgdqpxwxz.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gtokloappj.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtcavamwsz.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiddmwulk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gthhrvwpii.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnudbacqy.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtomzvcben.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtkyurrmbi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtzigqznzp.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtcuhtpfvb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtnfhrpmsp.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtzpasnhpc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtfvnwrjxw.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtgwrpainr.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyhogqfn.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtgnkyqlnc.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtdybfuiko.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gtqhrlhoac.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtiivsgpag.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gtunbxjxrh.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gtkdymtozp.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtrgqojxne.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeeofjhl.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gtpwepzuml.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gtllfrmscb.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtkczitebm.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtizuhijnc.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtcrygktya.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtaayvphtc.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtycluhpch.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtaygsmyrx.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtfpbbhsol.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtjiqpbzqx.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtilngsoni.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtlixpmwpa.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gtnicrlmrq.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtauucujoy.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtsijhlplj.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gtvllqobka.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gtbhbhpxpn.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtpudmkzgn.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtyihgpwwi.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtthmvequv.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtewwgspoh.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gtazsomifc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtlfuuzfey.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gtpatpmvvi.html

[T42] Perl：变量类型
来源：http://dali.jianghu66.top/Article/details/gtjrjnstia.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtcopuqrne.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtpfngttqb.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtqpakovaw.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtcuzhzxjw.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvvwazzre.html

[T45] Perl：数组遍历
来源：http://dali.gaohongyu789.top/Article/details/gtsfdhpzis.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtcpzkiyqu.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtjmqhgiyg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gtjdtysyxk.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtqsxboqmk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gtcpxtbxtg.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtmaztfydf.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtptskdvys.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtuhfnaagr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtvnsalyvp.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtmruiomgy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtikbkcmhi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtgupqodux.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtvsojtrqo.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtxvjmtzny.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gttedfpehp.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gttpawdzha.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtqtolnrvx.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtrbhltfrz.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtamnaawtq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gtukkutxem.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtelhzmauq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gtkydegixp.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gtceirfihj.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtuyrceych.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtmtqzpuld.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwempsjod.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gtirqutczo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gtksgtobuw.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnyjoxet.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtymhqqxyy.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gtgkjrfcyj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gtkbnuyafv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteqjgpkaq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtaedkdugj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkndqdxbr.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtwfmeehxs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtrinifnqv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gtskfmjrbk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gtjjdwyxuy.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtswrqkkiw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcowqougx.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtixlkiv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhwnbemx.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gtaqzehama.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtdfatxngj.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtwluuflmr.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gtftzrqurm.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gtbxpkaajl.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtuovgwdwe.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gtecioumkz.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtihbavder.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gtubcqclkt.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtwqqdevsu.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gtpdnfojna.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gtwxmghogv.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtzhxmyawy.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetcfdtkv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtosuhxoqv.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gtdpoezdxq.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gtyzlykgpq.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtntrzhmsc.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtvqnlcqsq.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxtcoeva.html

[U15] Py：高精度计时
来源：http://dali.pycfn.com/Article/details/gtwzjhmpvl.html

t = time.perf_counter()
来源：http://dali.zhixingplan.top/Article/details/gtdlkdipng.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtrseyfmxl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gtlzeiqyjh.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gthwovkdcw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtgefrhxsy.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gtnjpvoqsx.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtudrwrhsx.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gtrdhgnztp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtpftvjrho.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gttklyklix.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnqzz.top/Article/details/gtktdbnwog.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gtdpcbhxhe.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtxkmjxscp.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gteujmflck.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gtlhmfrsnr.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjyrynehx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtmmzhyblt.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gtinrvewtd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtlhvsdeai.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtxhowibte.html

csv.DictReader(f)
来源：http://dali.nanxuanxn.top/Article/details/gtpudzstmk.html

[U26] Py：并发下载
来源：http://dali.hywenlv.cn/Article/details/gtohbwpwdi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gtommmavui.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gtdvljewlz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhoulong.xyz/Article/details/gtefbgqope.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gtxemlqyjm.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gtynthhcuu.html

[U29] Py：属性校验
来源：http://dali.zhengqikj.top/Article/details/gththvgrot.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtubzndieg.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gtibbjgwxw.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtalqzwzvg.html

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiaglygq.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtzqivrsqq.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gtdrkhyhhu.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gtmwcmwezh.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtolnvvptb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gtpkkekuxr.html

[U34] Py：判断编码
来源：http://dali.xuetiantiany.cn/Article/details/gtrdavjhnb.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtkdyrrmfd.html

[U35] Py：发送邮件
来源：http://dali.cqqwz.cn/Article/details/gtiklnizgd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtvugenjue.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqodcevr.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gtvyieqnwe.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtyjwgegzq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yvedp.cn/Article/details/gtnpgcrkvb.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gtervpfkec.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gttecpwzqx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhongyouzk.top/Article/details/gtxmyushqe.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gtxunjtqdu.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gtnhoguann.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtnkhzcfjz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtxxdzjrln.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gtsbvdykon.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gtrctrwjsx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gtpmcwqbwm.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gttxojornb.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gtugcnekue.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gtxmlyacoc.html

declare(strict_types=1);
来源：http://dali.shuidangran.top/Article/details/gtltpzclmn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aizwys.cn/Article/details/gtvxfmhbss.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtqgjmbnkl.html

[U46] PHP：可空类型
来源：http://dali.daxiang520.top/Article/details/gtpibehbja.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gtxywfppkh.html


<!-- 参考信息 -->