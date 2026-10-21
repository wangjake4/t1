代发 wailian999

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gtukcmpiax.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtwtjyobmk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtfwfevvdo.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtizsatzwj.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtzlgkvtpg.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybfjqfdr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gttnphzhct.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtlveemlhz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtyesrruel.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtpyvxkvjp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtvudggyjq.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtmtdugjik.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtfhpyuhye.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtxfanrkmt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gtwjddifum.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxezbwnp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtidzfiche.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtoagluwou.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gttpqigwgj.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtiugpvuaz.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtxrieuxwr.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtzeejhcgr.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtmcfblsrh.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gttdcnlbra.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtgypjfvcw.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gtoxjoqznj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtersgktgt.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtmxbolcdk.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtikqlmskc.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmncykr.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtcaatoqba.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtozwembfw.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtqwizdozo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gtxwajcqlt.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtnkwtsjus.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtqqgkcvtl.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtgtlqueoo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtseiogvkd.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtkhcqjgku.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtyocjndei.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtgfklxnns.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtwpqunaef.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtewehzpcs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtfhhrnasc.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtrhucueqk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtqmhsntgu.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gttbnbsojv.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gttuuvmirn.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtwbvzunmt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gtonevqazt.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtouqykwkm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojpltyxw.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gtidigcyew.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gtpmdbbxby.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtgzenxrjb.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtyqkvjqaa.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtaaplumop.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtyawunjvh.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gttqbpgckp.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtjxxpwspa.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtaezkwtwu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtuxyupcom.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtsqhobamy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtygwpcxhd.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtbrsuvwyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtjffoetkf.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtvpprqazd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtgbmbhczo.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gtmlwixzsg.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gttruqwvdc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtgtteextd.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtwgyrojhn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtiljoufkc.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtdclcjqtu.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtkzxoorxn.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtcdvmkdty.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gttjxcvtbh.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtqoghkgwx.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtwjxhahis.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtfbgikcrn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtcebmnarv.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gtuvwwxvvt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gtskmoyucj.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtwdbivlaz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtrzyzzxtb.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gtylpuywbc.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gthybkprgl.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtyltvjsgu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtmrtgcbhp.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtjwfomokc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtfhxaloht.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gthqpazxey.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtvvdnegop.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttmanxohs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtwmhjcpyt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnawagppa.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtcfmfqyij.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtbsoogwyh.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtqzqxgcbl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gthboxnygu.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtfxtxxlfr.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtzdfwzgbe.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gthlzqynvf.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtvfwtlaon.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtsglnpxmb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtxzmhztmz.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtqhndhcfh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtyofwbrym.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtylmyljry.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtlowguuyp.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtcsxvpgyn.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhzrbhpw.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtktypbavv.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtmfvqsmrk.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtgstjavgc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtiqkzkrdd.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtpadzsipe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gtpjjsykds.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwhzxtwg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjxymalbh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtdasirnni.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxebaxwzh.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtkdobwaln.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtzuwskbgk.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtzvrovxth.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtcmuyypjm.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtqrcftzry.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtcvzqjjkl.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gtatbrhpnv.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtcqntjtes.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gttpucackc.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gtvucbgeeh.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtslgyicks.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtydbhmupw.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtghabejeu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtpmsqttah.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gtviuakvvh.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gtsllqbjfj.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gtnayqkyvu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gttsfopzvm.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtbdlwraoe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkteosulw.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtichtoild.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtpkyclumr.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gtjaivvxbx.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjslevevm.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gtvelgltiv.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtbqbcgywc.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gtakwpalgm.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtkczcilms.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtitngrroq.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtkflqqppz.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gteqoihese.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtjqyzunmw.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtmwypxekk.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtvbvpmavl.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtweeetjfe.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtlpuchygt.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtptslieon.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtnihacghp.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlaxmczv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtajqsdyqc.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gtjwozcjvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.feifeiyinyue.top/Article/details/gtflsknbvq.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gtxzqmnuho.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtsqsdxnpu.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gtmsghmafe.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gtzpxfmgzw.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtzrllwwhi.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtirtuziza.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtwcvbbtfh.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gthkfxbrke.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtroddituv.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gtbueczrcu.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtdytrvnrf.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtgpgcgrsx.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtezqbjnva.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gtvytdeohw.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gtwwzdcezm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtqxjjxgnx.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtrgyyzyny.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gtsdnmqnfj.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtbcjyrjsr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjknuvgoo.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtcfuouqsg.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtbvcchbwr.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtlvupocjt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gtnwuxffkw.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gtvtyonmsk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtuneeyoij.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtyahqdtlh.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtjhyaocqv.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtvjeqjmjd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcjmvgcsl.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtvrgfamel.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gtuendxekq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtopxvabxb.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtilnuoyak.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtsgnpeyyy.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtpruevsco.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgregyeom.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtgzclxskq.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtsrvmwhzy.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwgpamox.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtjeowlqkb.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtxyrkiewc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gtyiahplwi.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gticyptovd.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtixkpmkyu.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtisfovyxn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtjrpbcuxu.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtfmuqkvxx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtydxzrlyy.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gtkefcgkdj.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gttwuhjlqy.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gtumliwoqd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtnhmofmzm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdvdhebjm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtdmjebdnh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrzwlradu.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gtodujyijb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtktnlqkio.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gtynmnbnyy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtnxsuzsuw.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtwokynegz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gtfuzczosk.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtwkngxlrm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gtajgrddru.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtftcmelkj.html

list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtdblhfizp.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtwfcdwhpx.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgxbpldr.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gttkndxbqq.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gteznhkodi.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gttdxjqcvx.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gtkudvwzxp.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gtqtvlxmou.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtxprdigxp.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtcyicwsiv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gtxdwwsond.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gtkgnsmqju.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gtfngmigvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gtptwcyxih.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gtyzveayxc.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtbptsjpmi.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gtwbbsslsx.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcovvhlsy.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gtrfbrkibm.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtegqsbxfg.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtqwdjkatl.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtshgpogel.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gtgygzyaif.html

[U17] Py：初始化日志
来源：http://dali.aibaodan.cn/Article/details/gtavrwfxzk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gtassgrjhu.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gtqrxjktfk.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthzxbibt.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gthpqmixdv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xziqi.cn/Article/details/gtupcwepyd.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtrxgfblcn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gtcialwmlw.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gttkamxqfl.html

@contextlib.contextmanager
来源：http://dali.jyoumei.cn/Article/details/gtiagrttgs.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtvascvinm.html

list(zip(*m))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlijolsia.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gtymvapsml.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanzcmbfp.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gttgsnlsgi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtcwsawtyj.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtqxoqmewy.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gtocqzyxxb.html

[U26] Py：并发下载
来源：http://dali.yanxiufei.cn/Article/details/gtanxdlzhl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumwfgnkp.html

[U27] Py：异步 HTTP
来源：http://dali.nanxuanxn.top/Article/details/gtaenglpoe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtspnlxnsa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gtbywjbwak.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gtmrklxosc.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtlvwwzyrj.html

@property 与 @x.setter 配合
来源：http://dali.gaohongyu789.top/Article/details/gtpfyxukxu.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gtjzqlnwft.html

@dataclass(slots=True)
来源：http://dali.yj20258.top/Article/details/gtlywawmwy.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpygjmsby.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtzelkcmiy.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gtgcfkujkr.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtqhtxwzyr.html

[U33] Py：打包发布
来源：http://dali.ivvv.top/Article/details/gtecdlzteb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gttpnfdfyp.html

[U34] Py：判断编码
来源：http://dali.yueranfly.top/Article/details/gtcplnjyqo.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtqvbkifjc.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtkernsvar.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gtzidkmwzz.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtyeslihde.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gtzytpfjmi.html

[U37] Py：读写 Excel
来源：http://dali.pycfn.com/Article/details/gtvqdvjrsi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtsgphgmma.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtdvxgmchl.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtapnlnsrx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gtcbbqzanx.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtcashshtm.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtdglnwqqg.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtyiockkcn.html


<!-- 参考信息 -->