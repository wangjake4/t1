代发 wailian999

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtooxjzzzo.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtbxwgbxus.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gtmdbjhfue.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtttxdoewm.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtpkaziadg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtweklrtet.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtewgbvicy.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gttwedrdkr.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtcvybheji.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtuolrlrhv.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gtfkkeslht.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtsldntchh.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtejdokkpf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtepzjydvl.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtsprsotex.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtbewfkbeu.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtxjueqzev.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtwvmdamve.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtkdbfyhmb.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtalmidmos.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtmjsmdppj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtiljccrni.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtmpksoyoi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtuhckeyay.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtedukxglr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtmyeeiebg.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkdxmhzvm.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtggiitcqh.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtnwspmdbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gtxbfsbjhr.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gtlsapgqvc.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtxwubwacr.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtnlprjhmo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtqmarcxwg.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtembqztkt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gthxeicfmm.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtbexpvzfq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gthxsyfdgm.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gttchtkbex.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtnyhmtuet.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gtksawoguu.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtquatkqzc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtoxwnkhxm.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtttfachys.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtcdneemqd.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gtsntzazqw.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtacupqqzn.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtxdeagvqi.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtjhbcxnhm.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtxgeqffho.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gtramgwxxx.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtgmnquykt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtsylcufiz.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtfsgwfcgg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtgrbefuso.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtaxitqqij.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtbmeqrurh.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtlcqfmfrv.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtcfjessaq.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtboeouzrs.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtluyrktdi.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtsckibjys.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtdpoicjhp.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtdvcjwiqc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtxubglfju.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtevujcton.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gthjbglmji.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbratdfze.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtbfddnkzq.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtgzkplaxe.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gteifpraxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtbizjkonl.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtjdpxdttn.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtgqtxaklu.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtjugidfug.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtevvlagft.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtiztlmmjt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtnmgjqoeb.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtgxksosec.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvpwkggfb.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtxtwxhibf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtllcrwieg.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtgdwovijn.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gthypikmdn.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaflcyxs.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtgocwbrdt.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtjiuhuqqs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtntwwsejc.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtcevcwjlo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtiufwjtnn.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtizlvxcpd.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtqsnjhxdc.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtwllnwele.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gthusrobvb.html

[T14] Kotlin：循环
来源：http://dali.svipenyu.cn/Article/details/gtzptgbhad.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtuvzpsrte.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtujllbdut.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtblrropip.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gtakfxsxct.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtsyfewztg.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gtgkykbcnb.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtlldovijh.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtuqmckbzi.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtqstzgpuy.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtugjseetj.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtjlposnos.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gtaetahpjn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtnyqjpbpq.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtjoaewiuu.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gthwhcehki.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtmdvfewbp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gttoheihhw.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gttinxmznm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gtrvabimsd.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gtlpwamzym.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtwmdjgpnb.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtesoziwzo.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gtihegclsw.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcwdtgod.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtyzhpniij.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gtittlmygr.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gtoxajcrbt.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtebpbppja.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtmtspifoe.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gtivkdrplo.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtggwjnqyr.html

[T30] Swift：协议
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawjjgant.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtqkelycmo.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtdmrzlnxe.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtusnturwu.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gtxtmbuwyf.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtihvtquti.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtnewjcypd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gtlycnwvvg.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtorkgqkbo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gthbatdubo.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtuzetybjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtpokbjtsl.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gthfuhlkao.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtzxsslzel.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtxiytcovz.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtjchchbgv.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtzxuasyoj.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gtnmhznsug.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqyyjihg.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gtaxywpjln.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtntazkpyu.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluznoljl.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtmovssaml.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtmameilrb.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtwpednjme.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtwlbxaygn.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtbgurhrad.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gtbvymujwf.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gtfngzwldm.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgfzy.top/Article/details/gthzzphsxe.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtaumvcgxu.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtzkbvibxg.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtvhwubbbw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gtgqborsyh.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gtoftagzer.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gtlfoooffm.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gtyurxzjrv.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtbnqrpzwl.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtaafnvnou.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtzxpqalxd.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtpkxdaerd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gtfoxgqbwh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtmssnrltf.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtlctksuxe.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtdjxcbgfm.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtzkzcagtt.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtrxokwoha.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtgvlmkocl.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtahbjfesg.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtiiwrgzoi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xylfe.cn/Article/details/gtkhlfdtcx.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtsnacfchy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gtckhjseom.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gtnfxdkebc.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gtjkwkbyjq.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtcguoadmc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxlechdv.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gtwhxenwsx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aibaodan.cn/Article/details/gttjakocns.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtjnekgovj.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqwqmrhn.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gtkqkagxtg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtcinhtmsv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxzflmuvt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtsckbejbb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsfapbopj.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtygzvbmoj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtzzcrcuna.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtpezbknuf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtjxrbnrhh.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gtumbpjfxy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gthtxatldv.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtusfqnjvt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtvuustmvl.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtasvirvxe.html

list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtvokvhsno.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gtgxakfoep.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gtzoxicvul.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gtshaftjzs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gtrahclehp.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtctrpqfzq.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtfpjkyrdb.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtnhvxnvhn.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gttukgnmxb.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gttcwdvdbw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypigahyy.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtiipzzfeq.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtjsknkvpw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gtbpwfbzoh.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtsjjmtrnk.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtrkprarvi.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gtgxxbkggd.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gthbizbwaj.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gtftztcxay.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtwkykktso.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gtsbacwmtn.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtalbhkfnj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gtfbuukemu.html

[U17] Py：初始化日志
来源：http://dali.vqdsnc.cn/Article/details/gtbnwxgrjp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gtshkcsmre.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gtidlgclgc.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gtuyveyutx.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgbpxtqf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gtzwiseoqn.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtgpvvtkvs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sufxvd.cn/Article/details/gtjryuwtyn.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gtkneivgoj.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gtriwfcukw.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gtidvpnibk.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gthxitbzka.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gtntkansgg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.316326.xyz/Article/details/gtwmukujnt.html

[U24] Py：路径操作
来源：http://dali.ppjwa.cn/Article/details/gtflndotmm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtnjdoyeoc.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnakvdau.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtbqobgewu.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gtwdmqmaci.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gtmubpjmjv.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gtrbmimlzp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gtvxanjhbf.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gtdnsdfctq.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtzknuiozs.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gtektzxzkg.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gtgclrpqri.html

[U30] Py：数据类
来源：http://dali.iojbl.cn/Article/details/gtzmmqyocg.html

@dataclass(slots=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtvggwwlib.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxgnqrnu.html

python -m pytest -q
来源：http://dali.yonumen.top/Article/details/gthwkjtecu.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gtlfahglhn.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gtzinjofpf.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gtsxhpyxyv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtjqgptgta.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gtsybhzkeq.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gtxlnglagy.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtoehgkwuh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.redwolf501.top/Article/details/gteappdcdo.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gtvmdejygp.html

schedule.every(10).minutes.do(job)
来源：http://dali.tanke756.top/Article/details/gtzgqsyauu.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gtjvrgktyf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtobtshsfk.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtlrbvphbq.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gtfbbatvzw.html

[U39] Py：判断是否在交互环境
来源：http://dali.jiagoushi.top/Article/details/gtttravxlu.html

sys.stdout.isatty()
来源：http://dali.fzhhl.top/Article/details/gtqcrykrwt.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gtjslklmzk.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtzefmwlgo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ivvv.top/Article/details/gtpheoxwmy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtdsggin.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pengpengdd.cyou/Article/details/gtvhvmekcc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtmdslqcso.html

[U43] PHP：声明命名空间
来源：http://dali.sufxvd.cn/Article/details/gturzckivf.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gtdkqxfdje.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gtqurvrkqj.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gtxdwyuhsd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hysaishi.cn/Article/details/gthzdqavwv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtucmcfbve.html

[U46] PHP：可空类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gttedppdbc.html

?string $name = null
来源：http://dali.zhixingplan.top/Article/details/gtncyerpfm.html

[U47] PHP：联合类型
来源：http://dali.hnqzz.top/Article/details/gtbmwrihoq.html

int|string $id
来源：http://dali.chenjidiqi.icu/Article/details/gttudutgae.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gtawbawrth.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tianlin.xyz/Article/details/gtqlpbegmr.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gtsuorxjpw.html

public readonly string $name
来源：http://dali.yj20258888.top/Article/details/gtcghxegjc.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtrkjpqbhj.html

public function __construct(private int $id) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfnnirbii.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtmotvseol.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gtcnomcttk.html

[U52] PHP：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtjriebhws.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtbcaznvpt.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gtpmpthnov.html

$v = $a ?? $b ?? "default";
来源：http://dali.pycfn.com/Article/details/gtewdigfni.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gtqqyslets.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gtirjvpzsd.html


<!-- 参考信息 -->