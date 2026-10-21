代发 wailian999

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gthmpznuwt.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtfvymojpy.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtojoinwlj.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtxjddezgh.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gthkwrwwwv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahdznxzs.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gthwduamlp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtstgsyxbm.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtyeehnpfy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gttsmvtxqm.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtpwjeewsc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtrrbaruho.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtqdcmekel.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtqltmexjb.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtwpaerjcu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtnjynbucy.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtttbpydwq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtfagocydx.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtwytvivoy.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtzeqdqgeo.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtfbfcngwi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gtrpqwddth.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtqxfyqmas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtjdudowkw.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkipjaavd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtqecovkgb.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gttrtqxdyz.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtypqeebnn.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtueasfhne.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtfnxlbzgt.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtsekrpwdc.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gtetyhubao.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gteumywrma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtllzhgnnv.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtxlriumyt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtzvcobkxu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gthjvdbxck.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtoazpbrjg.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtpfppymjg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtxfoyasec.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtionhrwlt.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtbsguoruq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtvuobbuxc.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtgzxsjqui.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtumeiyfhy.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtfqrvuoxh.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtpeqsltyc.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtqpovutgc.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gtzqnwsbwh.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtuwwjrgnf.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtobuosnwm.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtuibkayrf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtzmjjlnhr.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtoinlvfiw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtsieukkjc.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtsoowdvfr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gttauhzoji.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtfqhjulhq.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtmvlcrhfa.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtectfyyil.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtmqaytifu.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtxtnmljau.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtkvavgubk.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtokklthru.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtmqzwytpf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttgjvovap.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtldalvsko.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtczwdeicm.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmyqczei.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtmipecqew.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtauzlnqot.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gthxmrgltl.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtozuxmqbq.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtzblkbyzd.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtdibtfslq.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtcoaklglg.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gtjfdhympj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtzpzmqaie.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gtprdyhmge.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtwiqcnutw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvhfqejk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtfmkpwjiw.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtrhivzhka.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gtvivlmagn.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtvhlfmnox.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphrkamxf.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtljuokjap.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcvprhua.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtghykwodk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtyhycwwma.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtqwukfigy.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gthxjtrfgd.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtzsrdrljr.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtryzvezuq.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gthqpielgb.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtqveqjjvh.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzhniwlf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtapyxpdbm.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtcezojwmi.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtdfegrurf.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gttbmzkvju.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gthdphbiyr.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtlobydywo.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtperzfyil.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gtgjiqiutw.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtibgwnlrm.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtwdaxyaqo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gtnwgouvgt.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gtniyrpqmb.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gtzudsnafe.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gtxubboace.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtgmoarhqi.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gthnonnsmd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gtnposzjvt.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gtsorzoqmk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtchjcfbqb.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gtrwbqpnyl.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gttekueyxh.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtmsvnisit.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gtnxbgngkw.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtnzjvdhmg.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gttfbhrtwq.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpthaniqf.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtxouvdxid.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtjizlbljc.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtnqcbksvw.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtyucvmfxf.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtwgcfxack.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtynurrtjk.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtwriujnfk.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtsenebzdn.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gthrflxhkn.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gtviiygskg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gtomebmslc.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtdttrzlcy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpujckfr.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtzsjjkvuv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzneerno.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtezpblfsq.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtvurjrfms.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtyfkscfuy.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtiqsrrnot.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtqlpzkuyo.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtvcibizpy.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtmbkftjjz.html

string.find(s, "%d+")
来源：http://dali.chenzaomai.com/Article/details/gtezpnkaeo.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gtgqeetglh.html

setmetatable({}, { __index = base })
来源：http://dali.gaohongyu789.top/Article/details/gtifvgfzat.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtmtiftind.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtxdwfjxan.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxlpdnro.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtxzyfxhis.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolrrmeba.html

"值: $a"
来源：http://dali.yongpay.top/Article/details/gtedbwltgd.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gtecuxngpo.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgjzlaqjo.html

[T45] Perl：数组遍历
来源：http://dali.gogol.net.cn/Article/details/gtwqjwkkvv.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjenwpfcw.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gtiyheyxrc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmvzidwjm.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gteuthllyx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtnhmionih.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtcgarkjjx.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtqkenesrq.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gttutmtdcd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtinisntun.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtuiwjgsbe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gtaosezfgp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gtbbuyivnd.html

[T51] Scala：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtfmzmtomz.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtgtqihkby.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtwyjsfjwj.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtdgolqoag.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtorepbofk.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtxanrnzra.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtcmuracgg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthphssebj.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtlacwxwzn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gtscaxydzj.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtuhmzdiax.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtujlnwzrt.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtczogslvd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtbvmzzidm.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gtdbbbnkov.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gtpsdtdufv.html

[T59] Scala：循环
来源：http://dali.shzxlz.cn/Article/details/gtlilfegie.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtmzlreenz.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gtntvrhgwj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpmpuhfo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzwovkfxi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtvbiefhjr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtteyromcv.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtzofkbpth.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtyspyxhea.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtelqyqoam.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aibaodan.cn/Article/details/gtbfnmymqe.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtgbbmjkva.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gtkvkisuwt.html

[U04] Py：变量调试打印
来源：http://dali.hysaishi.cn/Article/details/gtlntomign.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cqqwz.cn/Article/details/gtcngvbagr.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gtevkokrpn.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtqbbycqbn.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtmowdsacz.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtloorspno.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gturiosbdy.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gttzuuumea.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtvddtnsrt.html

[y for x in nested for y in x]
来源：http://dali.hysaishi.cn/Article/details/gtxotcdnex.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtttozqurm.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gtmwbtsnbf.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gtelufscjl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtgeukzkbz.html

[U11] Py：生成器表达式
来源：http://dali.shuidangran.top/Article/details/gtpalyfiuf.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtfgxiyirl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gtvqvuovnj.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtclznorez.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gtetknapqz.html

deque(maxlen=10)
来源：http://dali.gaohongyu789.top/Article/details/gthakcmdeq.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtcyjwcuqy.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gtesyattmx.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtwesldfkf.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtqpymazad.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtutrjmtdk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtyhcftqaj.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gtvknlbcoc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtpymjregz.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gtetdykiop.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtlvmdtyoz.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gtypdwhlyq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtiwhtwxht.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtpfybgija.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gtnlfdigpk.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtmqadhvkc.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtzdxuxgae.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gtlyrjgjop.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtxlacgvhm.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gttktqhsyk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtychmbjmh.html

[U24] Py：路径操作
来源：http://dali.yangfankeji.com/Article/details/gtevpnokmn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtnnpdmrgz.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gteoxefzsp.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gtivrnabpw.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtrgwzgzjm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.haohaochexian.top/Article/details/gtzehsiucg.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gtfxmffxwv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgfzy.top/Article/details/gtylahwjqx.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtyewirsyk.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtssddgjfg.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gtbhtmwqss.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtfltshifl.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gtqcbgztlc.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtsucrobca.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gttivgrcer.html

python -m pytest -q
来源：http://dali.xinyue.icu/Article/details/gtrmfeyyye.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtremhiyei.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gtlnsdlqsd.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gtckmegmba.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gtffukcyum.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gtgvrhmukq.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtsebltsex.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gtabtsivmr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gtuzioejwu.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtprcqpljc.html

schedule.every(10).minutes.do(job)
来源：http://dali.sxryk.cn/Article/details/gtlsgjxszv.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtdpdevwne.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gtkgrrywue.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtnixmtule.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gtxkygyskj.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gtswjnkqat.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gttqkxggpk.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gtiiyrnpgi.html

print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtnvqdmvmz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ydzc1.top/Article/details/gtzuomjmhk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxinkj.top/Article/details/gtkeeuvbla.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gtvnjkxfsg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gzhubu.top/Article/details/gtxlvnexkz.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtwkhavhja.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gtpfmmnsqo.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gtjhrbbqfs.html

declare(strict_types=1);
来源：http://dali.daxiang520.top/Article/details/gtllmbggrl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sweek.top/Article/details/gtkphigenh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtcbkyqixj.html

[U46] PHP：可空类型
来源：http://dali.chenjidiqi.icu/Article/details/gtwdiylsus.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtcfdtsoiw.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gtbkrfltfj.html

int|string $id
来源：http://dali.ybcxt.top/Article/details/gtlzjftlxc.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtgtqnhpfc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gtzymhxqvd.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfsnjusm.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtiwmsljft.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtxmwbrhmv.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmcwxfzdk.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtugykuapb.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gtcxxxuzad.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtpgtvxyfr.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtuwzqonzd.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtkotiqrfl.html

$v = $a ?? $b ?? "default";
来源：http://dali.jyoumei.cn/Article/details/gtoxsxjphx.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gtkowigkqq.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtllxhwslb.html


<!-- 参考信息 -->