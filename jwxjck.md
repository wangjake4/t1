代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gt2hxrgumtb.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gt2keuztvae.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2gjhiyeei.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2tjkypxst.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gt2ugstiokp.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gt2yxogpgsk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gt2elwwuxmt.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkottkir.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gt2fnkrmfxn.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gt2lkvvvqtb.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2npeipfcx.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2pfbpfckt.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gt2bjpzkimb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gt2rcdeyfjb.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2bcalasnr.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gt2cvapvghz.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gt2lhxbssim.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2unxzpioj.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gt2aixerxyq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gt2whskoatz.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gt2xvmdclnz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmpggiai.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gt2mnwpaexr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2vcdgnalg.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gt2ujstgwpp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gt2qrajknfz.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gt2tsbrbomq.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2uexkbxbl.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2azavxqrg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqmtzul.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gt2ehzkdtid.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2ovnopsab.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2vpomvvuu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gt2pznggsxv.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gt2vlxpzqtv.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gt2dfzhzfqf.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gt2kbqfdaqs.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gt2pkxzzurr.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2yvccxfgt.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gt2ugwqdlqs.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gt2odueksty.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzvzduuu.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gt2iinitllk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gt2nvfkjiqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gt2yaxmyfnt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahfrocqu.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2gxtwtrnv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gt2jcxweuze.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gt2sbkfblzu.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2jlscakhp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gt2uqraunud.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfrnjufm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2wanyifpo.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzerexop.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2uivonsnn.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2ffsfyydj.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tbhdccyn.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gt2coiljupp.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gt2nufwsjdt.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2umimlsqx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2ldxkicbz.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gt2rlxmjkbt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gt2kdhhxicn.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2ukwppgux.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gt2grcjmfrg.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvlyvmfn.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynxrwwfq.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gt2kgxznunb.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gt2vvrwyytc.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2getesvoj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2cvaxefxt.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gt2yyrvnovq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2kechtnnm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2gqncrtnh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gt2zymthowp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2thzovvxl.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2jikrlixc.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlighgqi.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gt2atwcnrvn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gt2yiicdmhu.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2tdzerkrl.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2iwpagalz.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2omkzjhcy.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gt2yiyzpnsk.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gt2oiplyrtp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gt2zlgeculu.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2qhfpbqhz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqrrpwom.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gt2xwsfeceu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gt2lztjqqjf.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjwmnpqt.html

data class User(val name: String, val age: Int)
来源：http://dali.cashguo.top/Article/details/gt2gapkpust.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gt2ihtreoqg.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gt2muaqxnlk.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gt2blnooupu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2qrzxdwvi.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2tudqacyf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gt2fvbobbco.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gt2pssqippx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2jvvaeooa.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gt2rbklyyzc.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gt2vmwklouu.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gt2wljmoebj.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2etboirer.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gt2hmfaeoom.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gt2quzjnnnc.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2scmityai.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlxigcsi.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gt2uivhinoj.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gt2rlvthush.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2xoumuebx.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcgaptcv.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2qbsmmnum.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vugniqpp.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emjxbqkt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gt2oqibzcwm.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2pjrtnipl.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gt2aaeqagit.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gt2fommuqlm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gt2dutnrbof.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gt2xnovnddw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2sjllmgzs.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gt2iprzonpx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpvacnwk.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gt2jaiwmwtb.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gt2vudmsxdo.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gt2swqoqwzj.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gt2oxmblxiq.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2uadylkag.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2bxpqhsdf.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gt2lesevqzm.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gt2tgzzdsva.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2gstlodnx.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gt2vuyujvqa.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2deynzasw.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gt2zvlaucwq.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2uaessvuy.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clidgnvy.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2zkvpkerm.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gt2nknhutjm.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2qkfqvbxt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gt2zqqfmicc.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gt2rdhgfaix.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gt2gglnntxj.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gt2kjpdvina.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2ijdotgne.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gt2ijlqblvp.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gt2wqixwjxk.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2iplrevfz.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gt2yqdqbpns.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2eirkvlxi.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbisajmd.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwqtpdgu.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gt2aivdurom.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gt2avolhtiy.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gt2gsthxrho.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2osejouuv.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2dutqemil.html

[T42] Perl：变量类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ffoywwxv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aizwys.cn/Article/details/gt2wnhslklz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2frjxzite.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gt2fizxgtyo.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gt2ohjazgel.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gt2imdhrwrb.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdzjkvvl.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gt2wcbrfhhd.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukalauqf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gt2jxpzyyjn.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gt2wottigay.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gt2tuhrvhmv.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apknodks.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knhaongb.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gt2zyvtegeh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjckfndz.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2nzantixw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gt2bbcpkxht.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gt2ezpxwatc.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gt2lpueizyt.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2fozyxczs.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2ntonxjbs.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2jczekolj.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2cstmkqlw.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2jjaihezt.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gt2gvobeuxm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ojvjzssi.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2qkqrchtw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxtdnzao.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gt2uxpbxhok.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2hdfjweos.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gt2uinznbkk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gt2jvbxhaai.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gt2orvvyhrq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2hjsfdqmb.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gt2lcujwqnk.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2ybrrxrjg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuvspiv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gt2niscpisd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2sulfknqv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gt2sfdorhxn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2flmrulaa.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gt2tindwahh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gt2biypmqjh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gt2htqngddu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2qbafcrvk.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gt2jblwpxtq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gt2isyjpanj.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gt2oqnqdcgo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gt2ljfhtzdl.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gt2fmrstunz.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2pforvgwl.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gt2kpsxuqyo.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gt2kakzkuvu.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gt2heibvqdv.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gt2rpnpuvtu.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gt2ktfdskje.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gt2dllafgix.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gt2lqwhkcda.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gt2ehttazbc.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gt2ipsujfwt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gt2tgugabri.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gt2spzdbdvj.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkrizfjj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xziqi.cn/Article/details/gt2zgltxeuf.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxiyrsuj.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gt2bohtvdyc.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gt2ncuazsjs.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gt2gtidgtvf.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gt2jwthtfxt.html

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gt2gdmnshbk.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gt2mlscxdyf.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gt2bktqxfep.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gt2nfrwjfas.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gt2lnrkslml.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gt2pmjbphsx.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulogcvng.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2uanckozf.html

[U19] Py：正则替换带回调
来源：http://dali.jyoumei.cn/Article/details/gt2tjawgkfr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gt2kjfwffan.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gt2phjrcdzb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gt2rkegldln.html

[U21] Py：自定义上下文管理器
来源：http://dali.xylfe.cn/Article/details/gt2tbakmixv.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gt2vchnyzqc.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2smxrgxls.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2nqsiykre.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gt2pnmcpggd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenlongwang.top/Article/details/gt2ibhsgekh.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gt2ywukgugx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2vlfrfaix.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gt2jvmqcrvw.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gt2yyvzeykm.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gt2cpafwnfo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gt2osfzdoog.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxcrufet.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gt2cqotprwj.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gt2aiimrrvb.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2ghrylxmh.html

[U29] Py：属性校验
来源：http://dali.xuanzx.com/Article/details/gt2ujmflqut.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gt2yrouujdk.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gt2vurtqhul.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2balxkfpz.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gt2vqvzqtoq.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gt2uunimsbc.html

[U32] Py：代码格式化
来源：http://dali.fzhhl.top/Article/details/gt2ycunrnbm.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2dscggyov.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gt2uumklcrm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gt2bpbwoctb.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gt2lgnpwoxo.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gt2vemfylgj.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gt2czpcoyov.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.vqdsnc.cn/Article/details/gt2ulrgstok.html

[U36] Py：定时任务
来源：http://dali.iojbl.cn/Article/details/gt2dubaumku.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gt2eojslnbw.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gt2dhvjozha.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2atqhjeue.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adwuelwd.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gt2idshxbpc.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gt2lrqjgfkr.html

sys.stdout.isatty()
来源：http://dali.yonumen.top/Article/details/gt2pwzkxyju.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigufen.top/Article/details/gt2qwfkuuxs.html

print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2manvwcqt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gt2isbhlsvo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258888.top/Article/details/gt2xtameico.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.9152youxi.cn/Article/details/gt2gnexngiy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sysykeji.top/Article/details/gt2gpxsstcw.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gt2llhhsaym.html

namespace App\Http;
来源：http://dali.jinqigufen.top/Article/details/gt2fchzkurw.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gt2ezkonwwr.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gt2ondcygxz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gt2vjfhrwrx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2rpdwhqzx.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gt2vctinxym.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gt2bvrgwett.html

[U47] PHP：联合类型
来源：http://dali.ivvv.top/Article/details/gt2wnkqkstd.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gt2xfibtrbw.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gt2dhkjvtvg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.9152youxi.cn/Article/details/gt2fqriojiu.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2cempvxyz.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gt2rznxpkmt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gt2tlclvdtf.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gt2cvxrcobz.html


<!-- 参考信息 -->