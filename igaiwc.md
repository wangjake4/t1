代发 wailian999

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjojhtwh.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2nxjiruho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gt2popzxfes.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2lycbkmrt.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gt2ygglshyf.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2avtfzmkf.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxqsxegt.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2qphsyayu.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2bejampcq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gt2miuirdqk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfhnmhd.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gt2jamyrecy.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gt2wusxhwxo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gt2aqwvzpre.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gt2wkaicdlu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gt2wqdgpkvn.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gt2qzdkcmgp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2tzmuxhip.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2qoihlykx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2mmifqmsj.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2aixobuqa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2ihivbcql.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gt2xiqallrq.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2gzfjzyet.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gt2zqcxdytt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqseeyag.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gt2resqwuir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2boadzefc.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2pfppbdrs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gt2spgpwagg.html

[S42] C++：继承与虚函数
来源：http://dali.nanxinkj.top/Article/details/gt2uhvaojhi.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2rzwpwiwb.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2iauyovri.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gt2fdyknhch.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfraxmip.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gt2agxekkwr.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2hztxjlag.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgqnwswf.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrlctvts.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imvnrozp.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gt2qrnhdyqt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ekncmejm.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2szykcnjk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gt2uhfvvaec.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2uhjbocyt.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gt2ydjojvog.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gt2ioimynpa.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gt2xewxkvyb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwnhcbi.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2xwqltulf.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gt2omrdzxmg.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gt2indvmbua.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wictaexf.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gt2ywjzwqlx.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2cgiftfji.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2tyxljypa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gt2xnjkcsil.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2ahnphzui.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2xqeauzig.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gt2cdsiqepf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gt2vajulvjy.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgxwvphu.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2gmjzukqn.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gijfavjr.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2rqlxxnso.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gt2ucbozqzv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2yszzsjda.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2zkgcddon.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gt2yvolxqra.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjiuovvl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2aqdjdiwl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qcxjkfqr.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlfjtbvo.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2qcsvfkpv.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gt2knmnerca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gt2wwfdnrtr.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2lqlmgnui.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2kfuvvmhi.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2xwdoioba.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2jtomlhrw.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnacswby.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gt2scnevwcw.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2biuvdhqx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2wkphnfsw.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2tfoelzzm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gt2odtjccnv.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2xwvfszra.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2mnadedlo.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2zlgkccxl.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2cbmpvurh.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2qiwfteva.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gt2ikxkesbt.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2qvoqumxh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gt2odtyyngn.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzcnndhf.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2gsabamcq.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2atyneohp.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gt2gyzfruwx.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2ucyqntfj.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2nkfgwejg.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gt2dgvsvhsh.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gt2wdwczfwf.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2puodcfgz.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2dceebbxm.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2cyrfdben.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gt2rhacbyns.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2kuretsqy.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gt2liohpnvp.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2miqubrev.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gt2qlucgorx.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjgfhdqk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gt2qbnncdcu.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gt2mdfrjigk.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gt2mpywnzgp.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gt2rdhlskfb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gt2khzenvbd.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxdcuszr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gt2umdfixli.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gt2yyuwymgq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnkzjitn.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gt2vtqkifcw.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gt2tyscsdqs.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gt2vsiwlijc.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gt2tluuydwm.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2efgwuooe.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2rbplwyuq.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gt2wjvjfrej.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gt2belastex.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqtayksy.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gt2otwbgqkf.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gt2lwvqbkjn.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gt2okogusjm.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2huerquvy.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2fdhiawiv.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gt2xsffyine.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gt2uzhqusmn.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gt2apiznnja.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gt2dflupmgz.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gt2rloxtlbq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gt2rshcrlec.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gt2hhbmmupl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gt2uuoilniz.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gt2fipwxpvm.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyjipcws.html

[T37] Lua：字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gt2syltkymf.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtfagtnr.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2nipwwnxo.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gt2hewjiuhv.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2pqqyoiei.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2scsqehho.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmaixorw.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jirelwnq.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2eszyywbk.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gt2cvasfsih.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2hclwzsni.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gt2zymupfef.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2hbxeqiux.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gt2rnrtadjj.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gt2fermxlym.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gt2kulqgzau.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2qtkjbfpv.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvbsfgub.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gt2yxfzmyai.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gt2lmcxcevg.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebiwqqhj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gt2brfqvxjz.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gt2qjjtnkca.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gt2beoeiuah.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldwakthj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2octncjlz.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2yqpfxffj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gt2tvhoxknl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gt2hoogcnuo.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2xhxetobn.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljfmkjef.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gt2urwhfmvr.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2aohdwnvx.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2fzocntyb.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxdrjntl.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gt2edjeenpi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gt2eldrjvkl.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2quhivxjc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uinikhcw.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gt2txydlejn.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2htlewvbr.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2bjnweesz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gt2bxkfrgsp.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gt2bfkirwpi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gt2wwrtgzaf.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gt2ioimwrvj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2hlketozz.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gt2kuoahowc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gt2egaescvd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2fesyacoq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2qswynpte.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2aqmbuhap.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gt2qwfssvne.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcdyrlxx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gt2jqmegmtl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2wmmsilrf.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2xdajxvop.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gt2bjyghhjf.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gt2lapjflia.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gt2wmtuujyq.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gt2cobyhkod.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2gueqhbka.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gt2dwvytifh.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gt2chlcbqhz.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gt2zalogtks.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gt2hmvxggco.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gt2qidwvypt.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gt2zwhuilqt.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gt2jhrthiwh.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gt2tbmvbfre.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2njffexem.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gt2dhmgplmq.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gt2jdtznsai.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfcuylce.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gt2fdbhckob.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gt2pkrgfasz.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzwpqtdm.html

deque(maxlen=10)
来源：http://dali.jlsjyb.cn/Article/details/gt2cviualad.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gt2jtqhgwvd.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2xvgvrtoh.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gt2pwnvjtoa.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpxrtouu.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gt2calxoruu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gt2lrvxfhdm.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gt2cdteuwrw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yongpay.top/Article/details/gt2sygwthta.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gt2mhtwmbla.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gt2dxdnerdc.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gt2phfwvhds.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ntolixwf.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gt2czuaomsj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gt2zpyztczo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gt2rlqagfij.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gt2xpmygflb.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2movcvykj.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gt2pwgqkfas.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gt2iuuthdpm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guannengcc.top/Article/details/gt2rmbkvkvc.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gt2acqchrvf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2xuspvazk.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gt2bdfjglfa.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gt2upsdsenf.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gt2qotczmse.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gt2iopfnswm.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gt2yowuuatm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gt2plxsqles.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gt2cmvtpmxr.html

UserId = int
来源：http://dali.c1oappe.top/Article/details/gt2lmghgqsa.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gt2pjbgnyhb.html

@property 与 @x.setter 配合
来源：http://dali.jqgfzy.top/Article/details/gt2sdltwypr.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gt2lcuqmcpq.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpdnzfal.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gt2wswlnxuw.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gt2lnoiesva.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gt2rbioptqq.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gt2eoxyoppo.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gt2ugddzava.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gt2iezqgcms.html

[U34] Py：判断编码
来源：http://dali.ydzc1.top/Article/details/gt2ifhfjyup.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gt2euhanfnz.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gt2qmmgduuz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gt2mddsuuwh.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2uyalpavv.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gt2xcdvvizm.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gt2ydfoxacf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2yqwquldy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yliujgia.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gt2okgcvvob.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gt2najyxmcy.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gt2mjwsllcg.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gt2cgwhgtns.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2lrynfaif.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgufenzy.top/Article/details/gt2uhhpwcnf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gt2lrgpltpf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gt2xlrigkoh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gt2ehhtzraw.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gt2cdwjrpdt.html

namespace App\Http;
来源：http://dali.quarkkingdee.top/Article/details/gt2kotrmbka.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gt2cmbglicr.html

declare(strict_types=1);
来源：http://dali.xziqi.cn/Article/details/gt2uuaihrdq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258.top/Article/details/gt2trspihus.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jtxzlxyj.html

[U46] PHP：可空类型
来源：http://dali.jianghu66.top/Article/details/gt2imwcmlef.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gt2lydoxguo.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gt2pouvoknx.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gt2bbheoodf.html

[U48] PHP：纯枚举
来源：http://dali.yongpay.top/Article/details/gt2cdedehmr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tktoqpbz.html

[U49] PHP：只读属性
来源：http://dali.jinqigfzy.top/Article/details/gt2lxylxyyl.html

public readonly string $name
来源：http://dali.sweek.top/Article/details/gt2zhmteijh.html

[U50] PHP：构造器属性提升
来源：http://dali.yueranfly.top/Article/details/gt2clwlacit.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ldavhdmu.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gt2ygawieej.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gt2iualwabu.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ykbeajrr.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gt2oggncrpe.html


<!-- 参考信息 -->