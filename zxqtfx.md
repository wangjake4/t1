代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gttzxxmqnq.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gttvarslkf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gtynpmleec.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtcreyepus.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtltttoyhc.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtmbxmiuiv.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtpssdegas.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtxubjevps.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtrazivzvj.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtdbxxgdlr.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtynzgngbu.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtiwqqsvhj.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtptsgrlsz.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtbhrrwbvd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtsexdezvd.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtouadmeyk.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtgkvktedh.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtlmnbkclh.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcntewmya.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtzrqqxmqb.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtigppzifb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtsnelifvi.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtgdergfog.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtchqcsuqk.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gtnkxfylbv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtntohdfck.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtmxusmgjg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtquyczqvl.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtvcokofae.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtqkfbylre.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtmrzxttmg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtlgunrzpk.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtvkjwbvvg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gttmgszhgt.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gthgrxxhfo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtgltzwngx.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gttnmbdbnt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gttfneewuq.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtyhunrupr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtkqildzpg.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtobzemslz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtiywetkqp.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtdsxrukqn.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtqrtdjtnp.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtqujmnnqf.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpudbdifn.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtzuwevqdg.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtjmtssfym.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtltnvdzrn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtwtumfedf.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtiaxqmuqr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtpkercvbc.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtnwudaqlf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtlduwltdz.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtaafomusd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtqbboeovm.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtrzxnxtjn.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gttalpzkpx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtkewkvoox.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtedyszfgw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtqetngucy.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtpuqrfcez.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gtvcymsnkn.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtqzfolrxx.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtzzyokwxp.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtlhtuklgt.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtznzzmkjc.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtsrgbofuy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtzfjsqxkj.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtcioicmnu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtgmpxjmai.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gthedysxjx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtinjqnrvh.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtlzxttgok.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtmbgtfqjv.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtfuicwcwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtwjnfogxy.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtrkvskezn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtoyaevlmk.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gtoaoscuuc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtxnlpwfhh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdabaknfe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtpquntiwd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthabvxrqf.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtghlkhazg.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtapmrqarf.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtrvfuqkym.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtuplllanr.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtwzdvbcxs.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcszqwsxh.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtxyapdcst.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtrhzzcnxb.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtlqtdataf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtxjmymqck.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gttctxqkfu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtfwkzqadg.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtbffunlet.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtbbzwagfn.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtltqmgcpr.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtlqtxombk.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtqgsebhgf.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gtiskaxcmt.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtqvtxppzw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtxrzrrmfd.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gtidseugaw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtdxiqxmbr.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gthpzgqfhk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gttsxqivkc.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gtvdoskmho.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtrgarxcie.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdjkuwqs.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gttxbrnmxj.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gtcjyerhts.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtdmqwknpq.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtkmlqeyoz.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtnthboxsg.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtyowuzpqj.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtkgktnvgb.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtwvcubwls.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtuyltqatv.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gtckvkdszl.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtlmxchkqo.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtdylolocc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gtdttjumnf.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gtxynlgqyr.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtkqygvkbr.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtmdsbdmsf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gthgwyrzwu.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtsylsoiwz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtbyvwproj.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtpzzippxh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtczuzxmah.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzekjzxyt.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gtmbjzstqw.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtkydkmqcg.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjkvjszq.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtqzcihybw.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjfcmftv.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtaybgyvdw.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtfjsehihq.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtiwxvuzts.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gttbeucpze.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gthkoaqrau.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtnajjwudg.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gtfthchewb.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtagtnytxr.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gtvmdavego.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtgazngtrd.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtopwitbpy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtdpwuhzeu.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gtyokjkagy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkfaykix.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtjywlmnjn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtyaadduib.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gtxxgxasxe.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gttsdlvgzn.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtpexuhyqr.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvewdllzy.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtcyjxoghu.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtlnytbssl.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtirifzqhl.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gtyxclqijd.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtcqvtzmjj.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtnnvfeumo.html

[T41] Perl：Hello World
来源：http://dali.havefunace.top/Article/details/gttonfojiq.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtdoaacpro.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtfzsywzbq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtcyoddktp.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtwvbfjjbj.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtlvazudhi.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtanvntzcn.html

if ($a > 0) { print "正"; }
来源：http://dali.yj202588.top/Article/details/gtesqhkqbj.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gtlzbhsqin.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gtorkwyleu.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtosuwngza.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gtfqpwxrxe.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtnqqwwqxi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gtbyamixnf.html

[T48] Perl：正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtckltvrfq.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtujsvpkpk.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtkimvvkxz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcjmqwrt.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtrbibzlxh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gturbhbywc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdindswfs.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gttznukkpa.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtikrlfaae.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtteqolzof.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtkngpqhgj.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtpxqgrclp.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtpurftvtj.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtdryfxhds.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtekbgmkaj.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtqftwpxep.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtqeaezzph.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtuosqkkxb.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtdwwqbdfy.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtrkeoyedn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtpekdimwg.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtxmlgysxf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtgblnltus.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzpmeiyk.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtptohrkjz.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtvjuzesit.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtbjjrhzuz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtuodggoby.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtefcutrxq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfkplmgyc.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gttaacxuzp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtocnxswhi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gtlfiyulwg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gthaqezlca.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtezvjhprr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtvpiilmxe.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtndqdniyi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gtmtohkspo.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gtokcogphl.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtnkbqbyso.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelopykai.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gtjamudeok.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gtynzefcsc.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtzaoxfblm.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtpzzbeaqe.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtjrizhuea.html

[U09] Py：字典取最大值的键
来源：http://dali.guowangkeji.top/Article/details/gtqdtvqjtp.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtnqrgjkbz.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtzjvijsxc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gtkzblxkwa.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtvtapbbyg.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gtgczwygzi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.havefunace.top/Article/details/gtxvouotki.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gtmsjbkukh.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gtvywmzund.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gtmhzmjbwq.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gtfzrlgfoy.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gtnimnsgpf.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtuhjnanpe.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gtgnmznbee.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gtauktiagm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gtuunifiop.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gtrufwedoq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gtuhkudfhs.html

[U18] Py：预编译正则
来源：http://dali.yuanzhike.top/Article/details/gtcaoramhw.html

pat = re.compile(r"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtsmpyozml.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gtjdwlfryp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtphoptqxz.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtyahlyqzd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtenqfyltj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtpvnzaamd.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gtersptoep.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtptdhtduo.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtjfjynove.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gtydqohcwi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtjrwzkezi.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gtcwzhwpgb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtargbatgr.html

[U25] Py：CSV 按字典读
来源：http://dali.chenlongwang.top/Article/details/gtibexpczb.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gtqoicyjyb.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtwxpqzxkp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtzpxrvhkq.html

[U27] Py：异步 HTTP
来源：http://dali.hywenlv.cn/Article/details/gthobggvsg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cheryme.top/Article/details/gtcjtjutls.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtdrsmqfly.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gtvhytobzy.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gtvbdzztec.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gtwjmoivyr.html

[U30] Py：数据类
来源：http://dali.shuidangran.top/Article/details/gthifotujj.html

@dataclass(slots=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtkofnnmyh.html

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gtvezxfkor.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtjyjwngmr.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtdtrvhwsk.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gtegtwxmsr.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gthtcitysy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gtvexsxqce.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gtpnrncfsy.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gtnslbpoho.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gttqyfcner.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gtszjdbwds.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gttrnyqwpd.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gtgqjzyjrc.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtfvrskwem.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gtxqkjdrwu.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gtsexnrgte.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshedridm.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtyrhouvwy.html

sys.stdout.isatty()
来源：http://dali.wangdashe.top/Article/details/gtlfpnehed.html

[U40] Py：打印到标准错误
来源：http://dali.jlsjyb.cn/Article/details/gtcldlrrzr.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtfaofqdrf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gteobanidn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gtsjqocexw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.birdmap.top/Article/details/gtxmcybkmi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.birdmap.top/Article/details/gtiqqllwnk.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtsjahvhyf.html

namespace App\Http;
来源：http://dali.tianlin.xyz/Article/details/gtnpdxmemz.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gtswymobrb.html

declare(strict_types=1);
来源：http://dali.cheryme.top/Article/details/gtbxbgsbie.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ybcxt.top/Article/details/gtcbaetjqv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gttbjgcazd.html

[U46] PHP：可空类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjwyhbsvi.html

?string $name = null
来源：http://dali.cashguo.top/Article/details/gtpesmmycz.html


<!-- 参考信息 -->