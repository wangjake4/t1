代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtebysydyx.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gthwnsddnh.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gtcxuydwjc.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gttffntggq.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtjenxsrpi.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtinatzmoe.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtejbblage.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtkuwutkej.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtifaunwoe.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtbkkrcdgf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtdlysyjsx.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtnidcqzyb.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtgyimewfx.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtfxebyjcc.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtgromxdca.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtogxoowlw.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtyvkhyamf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtbgkmteai.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtggynlhgh.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtvzuowgns.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtcysyxmao.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtoqbmrxbj.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtpvrtcxzu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpahgfegj.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtxbceswhv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtkttqirlb.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtuqikftyl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gthgrkhamq.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtpfxrxaxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtfqvfasmv.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtbluyekfr.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtmhfathnw.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtcskikdgr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gttjqeyxlw.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtmtidkeyg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtfjfeaiii.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtshbagqgk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjguyqtf.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtupjneqzy.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtxfztzobd.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtmrnfmmhz.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtbpdkqeyk.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gttdwtktop.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvhhxzxgh.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgjfmxtc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtnolazhvq.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtxzjlqrpl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtiuflovpc.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtbbfmmmcc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtwiyifkbd.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtptmiaxqg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtndvyhttr.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtanytdpgn.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtmatcuoly.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtbgdwozgx.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtpjybbugd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gterusyuvx.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtdvqdkrlf.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gtzkbwusgr.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtenteueht.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqpqfvqw.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtayouqyup.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtlsdtbfsc.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtqblnbzgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtcdvbolsg.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gtyhhthrlu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtrydqobqc.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtihewopzh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtykyetjsq.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtbrsgqysg.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtqidshwxp.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtqeswrqly.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtzbisaics.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gtszywlniz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gthphfdgdv.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtgmmxpixd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gtvjzsectn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnggfbrkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtgumvnevh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlabtcpov.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gthbvejfuv.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtbtosvott.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gthsryxlmg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gticxrexih.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtievrwuyc.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtpgmnvrle.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gtextahbkm.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtxmprrtmp.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gtfeshsmen.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtfdutelzs.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtczbdpgxd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtinvegxtq.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtfyyekqft.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtyhrwpzab.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtjoanofea.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtpvkryfhl.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtfolbexal.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtrxlqngra.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtfcgipzdr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gteueshrbj.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gtjeuiqjzw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gtnkybcqcx.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gthspywaga.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gthloucwti.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtsxplmtvw.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtqqogovdu.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtmmihsjbi.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtawxpesro.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtbtborgcc.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gtgsxgcshq.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gthxlxpjsz.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtogphxcbh.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtmynlcjkb.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtlaoavzkw.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtncxcrtuz.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtpvoqkylt.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gtbtmzluri.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gtckgsmpcg.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtjegejkrb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtvpnthvvr.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtuulklest.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtxlxakveo.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtypwgnrkd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gtfnfhvtzm.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtujydptfc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gtpqzxzdiv.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtikqixtbz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtpoicnibm.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtsyxgqdnx.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtjczidwnt.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtzwpplgox.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtnyazzbtm.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtybwwsrnb.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gtbiknkpgm.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolconatq.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gtxzwjeeow.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtsaduvmbe.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtuqjnvxgp.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtbidoylaq.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtvjggcgby.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gthfrzimme.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtqpsvxkvt.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtnibjdfwm.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtliusmlrs.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gtgbsfoncx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtmfnoxamx.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtkeedcqva.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gttemdmemp.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gtwizmcoxs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtwhygjgjd.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gtptrmjmpt.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtversasxe.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gttojqolmz.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtpqtmasmg.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtsvubkxlb.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gtyengmpxh.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtcsrmqgmy.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gtmnhcliga.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gttgmwvjcr.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtexpxcfsm.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtmrazmsdn.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtgjoaujdm.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gtvsmfbpgm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtrhkwovit.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtuqtkolcc.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtdekpkmiy.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtgfkjrcqk.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtidrplfyb.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gttfrrxpps.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuyikhgqy.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtrfxyzqtm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gtlpapohxd.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtdqrrmpng.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gtyltmmazk.html

[T48] Perl：正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtdakfhglk.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbampbqr.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gtetlsjqvt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtrbmwxctt.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gttdzxwafi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtuylwptdh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtclnzmikr.html

[T51] Scala：Hello World
来源：http://dali.meibo888.top/Article/details/gtntcgehcu.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtsriiqvwq.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gtggwgvzgk.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtbxmxzbhn.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtycgmelnf.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gttpqoshns.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtenrwpovj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gtnnxlwqcf.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtgpvdxzoq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gtjeykwapu.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gtsnyowbsu.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtgbbujmpm.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtmirxiwlg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gtvckmpycn.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gthqdajzgn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gttzkpggzw.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gtmvjwvxzg.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gthajvsqtn.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gtzthrrdfa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtktfrzopn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtterzwppe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gthoeoacpf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfdwutzrh.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gtrksdnihn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gtdgjcofqq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtauemiony.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gthxgjtmna.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gtantsczig.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gtlhoiwrzv.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtogttyi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gtgyumpxbs.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtsgpsmfku.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtuahxstjb.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtohpdboxa.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtsrgdkhhn.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtiedcvz.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gteamzuyps.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gtlkbuymbv.html

[y for x in nested for y in x]
来源：http://dali.cqqwz.cn/Article/details/gtfyzjcoov.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtrwfffsrc.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtvxjczcyr.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtbpcsakal.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtidhriywm.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtixiripad.html

(x * 2 for x in arr)
来源：http://dali.haohaochexian.top/Article/details/gttowzabrl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtwacievlj.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtrnuzziwl.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gtmzwiwwlt.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gtnzdfubvb.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gtesecgitk.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtpqrbxtcj.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gtqjgsyjbp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gtnnwtqatj.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtjaixumpn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gtfoenvlzg.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gttihezxaa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gtrqzkwcdn.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gtstuvkvfs.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtzkjrzdnj.html

[U19] Py：正则替换带回调
来源：http://dali.vqdsnc.cn/Article/details/gtkmppjkgx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtssogvinz.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gtwriteluz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtgpnzppax.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtcfuyuetq.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gtgcfujwry.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gtzcyhzlff.html

list(zip(*m))
来源：http://dali.zdqjudy.top/Article/details/gtzqdtantc.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gtlnxatvhj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefjhndpr.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gteufxstpl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtlygfqezx.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtsxintjow.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpotexud.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtjjokikol.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fengsongda.top/Article/details/gtjdzuhcbo.html

[U27] Py：异步 HTTP
来源：http://dali.yuxming.cn/Article/details/gtftmusprd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ivvv.top/Article/details/gttqunlcbt.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcvkttux.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gtvzudinsz.html

[U29] Py：属性校验
来源：http://dali.zhengqikj.top/Article/details/gtrshatfkq.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtcivengqx.html

[U30] Py：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpracbaoi.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtbpqsfhhs.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtwhtzewra.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtekrzzoqd.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtyygvhayl.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gtdyvhctgv.html

[U33] Py：打包发布
来源：http://dali.zhengqikj.top/Article/details/gtwrlwjlpx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gtshnflasn.html

[U34] Py：判断编码
来源：http://dali.hnqzz.top/Article/details/gtfxjqlgnx.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gtrzvbntyd.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtssebjxbf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gtsxluzutb.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gtgmkmxbhi.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtjbrjhoie.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtjngfqiwt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yonumen.top/Article/details/gtlmmdlses.html

[U38] Py：获取脚本所在目录
来源：http://dali.316326.xyz/Article/details/gtexnritxa.html

Path(__file__).resolve().parent
来源：http://dali.hnxiangtu.top/Article/details/gtvzaiazjc.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gtvtqczlby.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gtwswochka.html

[U40] Py：打印到标准错误
来源：http://dali.hnxiangtu.top/Article/details/gtxrpckqbb.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtnxludpdz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gttaoqosnv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtyuvmwcpp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gtawiotqho.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtawwcxjti.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gtraktydra.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gtcbrjssdt.html

[U44] PHP：开启严格类型
来源：http://dali.xylfe.cn/Article/details/gtiqdmevdo.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gthlkmqjai.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gtxigagsis.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtyhlunrtu.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtgbhlchty.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gtybqwfknt.html

[U47] PHP：联合类型
来源：http://dali.daxiang520.top/Article/details/gtdxjwnvoh.html

int|string $id
来源：http://dali.yuanzhike.top/Article/details/gtbdgxdtsp.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtmierjvyp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gotoacloud.top/Article/details/gtpvenovud.html


<!-- 参考信息 -->