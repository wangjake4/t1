代发 wailian999

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtukjugcio.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtlvtckmye.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtynlvgagm.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtuzpkccbv.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtcvukydmq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtamycifib.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtwedckrmk.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznloytzf.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbllbqzka.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtsyvqaigh.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvxzeduh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtyylaoguf.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtzfjxivlo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtnhfqmftr.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnmzuzql.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtzefbffty.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtbsynqfqg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtkubidrjc.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtrrbwfuot.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gtkbvfxwzy.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gthcggdyiy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtdslnvvvd.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtzbgxwspg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtamouzygt.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyyvmiwy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gthgkiwhso.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtbkkcwwzg.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gtebleplni.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtjcdkdhfn.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtfcczavom.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtdjfwrqkg.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtoxofeync.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gtpnqwnvse.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtmhyoknui.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtenycgwjy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthawcjqaa.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtwaodwtbi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtrvlwbjcz.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtnijrajji.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtakwdtiwv.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtcknpywow.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gttbhciudj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gtlxwdvbjd.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtcbakiosh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtuznxhoyj.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gtpvnffonl.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtzibtreid.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtfujnxzgh.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gthtcmjpeg.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtjumtkzhs.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtembqricq.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gtckqguswd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gtmvrewuob.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtjycokjdk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtqglggrkw.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtrwscidfs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtelvrtpup.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gtiswxpnmu.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtlfnwzqbg.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtjsvuvzat.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtcnomglhr.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gtqympfwat.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gticabubjp.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gttewprnyv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtysdupqkh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkqhswjts.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gteumetado.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmsyljkuo.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtdxqndgks.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtuvryhzqj.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzngbyxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtwddrpkgg.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtdrphvvof.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtinpavjss.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtggrarffl.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtjjcycqmu.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtypktqcpn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtpnluiqul.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtfclqhtus.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtejrfqooi.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtxqjyouyx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtyhimpcli.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtdfwwmzsq.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtttrbxfxw.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtqrosuskw.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtlafxbhgk.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtowyngupy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtxaxjkkvu.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtrgqvamwp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gtaabsttsb.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gthyuxddmv.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtacicrpch.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtprojuqik.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtetyeojtz.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsswevhn.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtkmyoybae.html

[T15] Kotlin：接口
来源：http://dali.hysaishi.cn/Article/details/gtnnxkvpxi.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtrogokwyi.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtnzhgpgms.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtamokjjuy.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaswfinlx.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtffdnhmbq.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtdkalwwsi.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtzpdjzdfh.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtdrgkouhy.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtqnixsutw.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtpwvvrqso.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtnbbemvjw.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtnpjtyjfr.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtsgasvkhu.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtvrzyiwkm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtrqjiyjsu.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtcecoglkf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtguzrjmbj.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtsipwxmyd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmucuuvei.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtzxbknfrg.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gtoqlgtbto.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtevslglfq.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfbdexps.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gtsoaclxrg.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtfwlxshpf.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gtvblsjnfj.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtbupoljvm.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtgfcgpqoy.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gtsbkvmwtq.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtunmrlqbl.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlverwfzv.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gttourwejn.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtewewdxqx.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtjawontiv.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtdrobfeng.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gtwtsiyfiy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtehpsqtjf.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gtypeytnnb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtjhbfhhix.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gtcnooboxo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtkyaemzhc.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtdqlfomcn.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtrzizhmlr.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtbdpvjetm.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gtmuuviuyf.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtusdgbnre.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtruvlcuvm.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gtioqcfagq.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gtztuqrefn.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gthosymwgq.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gtjlykjkxg.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtcybnnumr.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gtngrwapbl.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtmrnsgysl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtuiyftwzt.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtutxzysvf.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtwalzqcgu.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtsrdufotu.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwljmdjmj.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gtufeulwok.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtqmcggndv.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gtnyraodio.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gtycvhxhlb.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtnsoqsnni.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmspgzgcs.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtozogvbzf.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtcbmuarim.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqhgrkzt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtvjssbdri.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtcntorgfl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gtndlokykj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtoivvjlnr.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gtrbyxiqut.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtzwfmpckc.html

[T52] Scala：变量
来源：http://dali.jiagoushi.top/Article/details/gthfnqwlcn.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtnlnmvdaz.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtdidlhexb.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtyhzabasa.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtbamlmiwx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtvxxejqbs.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtnbmbmwfj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtiudxuspi.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gttqwcxsia.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtowzranin.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtswnemwrm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtzwycbzoc.html

[T58] Scala：函数定义
来源：http://dali.fzhhl.top/Article/details/gtgwfrxttf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtbqqckqvc.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gtlugkvraa.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtuytnzkkf.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtiwinruyn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtkmqscbrw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgcmdworz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gthkglfxjb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtevzsbvfk.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtykmnvkvw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtndcylwhb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gtckasrtie.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.feifeiyinyue.top/Article/details/gttrqtmrce.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gthzcfyjib.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtjgfgasnn.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtitbnrlmz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtimxauvna.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gtrgcqotpf.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtatuonifx.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gtbumdlfxz.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtfazzitfi.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtipvpjcqk.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtfhiswxho.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gtcyrzubhg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtouhxvpcl.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtlmhduhey.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtpqhyamla.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtldzazinh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gteesypqgc.html

[U11] Py：生成器表达式
来源：http://dali.snrcjt.cn/Article/details/gthdmexkso.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gtnwyevnzc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gtxaifgegr.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gthjjgyqwt.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtzhgvlqnk.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtcuxepzsz.html

[U14] Py：分组收集到列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvztkvjg.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtilltoric.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gtqebhdanp.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtdocfrfrj.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqoaobkb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gtxsymllzr.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtubnuqrxn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenlongwang.top/Article/details/gtktqfcgsu.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gtyyjykail.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtfjppobgz.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gtemzopgin.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gtziyqfmmi.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtrtrdehqb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gtkvrvpdfq.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtrtbskzyq.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gtohvohkgi.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gtkteyvqtg.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtqupyjdfx.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gtxtzzeelj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgufenzy.top/Article/details/gtpwwbqqvm.html

[U24] Py：路径操作
来源：http://dali.yangfankeji.com/Article/details/gtvlqkuyol.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtuadcmimk.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtrihmujfe.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gtznxzhjtr.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtxkvjqyuj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtjburboxj.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gtrwukvxpp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigfzy.top/Article/details/gtvxvvswaz.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtszstbrkm.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtgxohobru.html

[U29] Py：属性校验
来源：http://dali.jlsjyb.cn/Article/details/gttqapjmnb.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gtyclrzptg.html

[U30] Py：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtqwyexudg.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gtvaffegng.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtwgsetpge.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtchabtdzc.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtexjqbelt.html

ruff format . && ruff check --fix .
来源：http://dali.hammf.cn/Article/details/gtjmbgigrl.html

[U33] Py：打包发布
来源：http://dali.yonumen.top/Article/details/gtqmhkwehn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gtfmqdwziw.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gtdboklljz.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gtzychhwjx.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtgbiyrkoa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtjnstzcyb.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gtpufsdtla.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gtzaiktakg.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gtnqchtdxi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gtuetjreik.html

[U38] Py：获取脚本所在目录
来源：http://dali.mhx1999.top/Article/details/gthypkwdjw.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtoozrdoux.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gtnuprpgqg.html

sys.stdout.isatty()
来源：http://dali.chenzaomai.com/Article/details/gtvjfjwcld.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gtnbzdyubo.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtlcmekvoc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daria6918.cn/Article/details/gtaxillbyn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cqqwz.cn/Article/details/gtvibliwth.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gtqnkawtqe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gtrrpeoddc.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtnjfgkzdl.html

namespace App\Http;
来源：http://dali.guowangkeji.top/Article/details/gtauxzydwk.html

[U44] PHP：开启严格类型
来源：http://dali.havefunace.top/Article/details/gtnljbxnkl.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gtscyfrdqd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gtyotxwfcc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtmmmrmdml.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gtryumwszy.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcwbsfoq.html

[U47] PHP：联合类型
来源：http://dali.vqdsnc.cn/Article/details/gtdxbkyehs.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gtybdvltbs.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtnkkzpuxt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqehevjta.html

[U49] PHP：只读属性
来源：http://dali.cashguo.top/Article/details/gtflednrsk.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gtjormtinu.html

[U50] PHP：构造器属性提升
来源：http://dali.yueranfly.top/Article/details/gtmxmnycwt.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcwhirlew.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gtadfjxhyl.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtimdhywnr.html

[U52] PHP：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gtfxflvvaa.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gtnwjvxurl.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gtzjsxijyh.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258.top/Article/details/gtoxwxbjuv.html

[U54] PHP：空安全调用
来源：http://dali.tian-w.cn/Article/details/gtsybvkpwn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtyrunjaol.html


<!-- 参考信息 -->