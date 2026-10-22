代发 wailian999

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtlkyzhuhp.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtegiceolw.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gtkwlvkmgl.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtceopixxs.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtmtkptwne.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgrgktoq.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtofschwjs.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtqckuovcz.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtxdxpizpy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtzbllcraj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtfsucowjl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gthftfudkv.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtaxjvqpfj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtzlcwpcxg.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtqdpwouop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtiukrorjv.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtqvyliasv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtptgprple.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtowqdzeyx.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtgqkdbjel.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtxvfpjgty.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtwdlzygjs.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtstaktmji.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtehlqsbjs.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpykoahi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtkgjzulwq.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gtjfgcsklt.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtyarwuwmv.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtnkorufkh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gtmxiffcmx.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtuqvebfiz.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtfybwbtkj.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtpsqjrkxe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtyibetxwi.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtsslfduon.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtwrctblxw.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtjloxnryz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gtejltqgqf.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtkvmczeld.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtphjblkff.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gttkutpkzs.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtbxnuxayh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtbzqyjdbd.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtlnlkpuwe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtgxbvuywv.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtcgmikzyx.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtyhrlxtnr.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gtmuosdkgg.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtsajtlcrz.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtqxuxffqu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtlrrabxfr.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqmotqws.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonjhqigs.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtvpkrdvji.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtqewyiqqo.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtrmbipzfw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtbnulnzsh.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtoylkaist.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtsiqvuptw.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtccwxasjq.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gthtlsjiji.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtjqkmhnbg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtbgmhaneu.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtkhdiiunr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtscetjuei.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxvabfkar.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtdbayoogv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnyqrytnw.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtssjgdhrt.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtgnawnlke.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtyjanvmyt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtknegbhql.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtwrabvskd.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauysyiuz.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtfyzgdafg.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gttvhxanwj.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtiftudbra.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtvyqhvyrl.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtogsuimvz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcgspvoq.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtanctjttv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gttuhivtej.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtoystlchr.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gthapvxyfk.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtlmzxnjce.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtdpfbyzza.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtnmlernwv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtizirtysi.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtdsufopjx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtkfhbsopb.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtfplygvjc.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtenucqrji.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtqgomkjje.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtckhlpkrl.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtbgxraudm.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtrnenutth.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtxeasxyrf.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtlxrpwarq.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtxpadajuo.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtdibtmjyi.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtjkttrtdp.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtyflefipj.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtsiofrouh.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gtsgfxgvmt.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gthpkrcgex.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtajzfjwso.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtyebjxven.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtzrallirr.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtcpgzdbgg.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaoaqpmu.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtpsblssql.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtdhkjkkng.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtpitagtzy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtkhyjwrlc.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtokjpdlwy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtyykgfyfp.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtzekmpsop.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gteujbxnga.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gttcbeyohg.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtbyhdimom.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtrobnpuhn.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtomktribc.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlqmyrhl.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtpdpvtyek.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gtxzwixnuc.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gtudzyhcxe.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gtxohlxjfa.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtzqtsscgx.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gtekjvrihm.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtaqskjhts.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtvvcysvej.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtehaspzzu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gtllgngnab.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtnhypifpy.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtprxihoyh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtypcfaqpm.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gtlaroqxjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtitqhqoqe.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtoxgnwhnt.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtlwuckodl.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtunlfywmw.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtodajdypq.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtrwvvnfrk.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gtmtwmmchk.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtehxxidih.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gttcnohmnl.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtaidybpuw.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtpykhprwv.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtgttsikpb.html

print "Hello\n";
来源：http://dali.nwbrower.top/Article/details/gtbqeflipl.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtkqwfrqyu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gtvfnawpig.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtlhmjbnew.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtepvofumx.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gttodtyoii.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonlvegfk.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtjjwvusie.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gtpjiridjz.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gtioijpyaa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtmolybzzz.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtaesrgtbw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtgfeiyxtn.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtgasepyxd.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtvrnpqrqw.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtdedjxpmf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgumabjnq.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtyvlpdweq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtwzydwhbw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtnftaqfne.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gtipcgetjn.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtlbipolsj.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gtcxmdibgm.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtlllzmibr.html

[T53] Scala：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtiklpbtmx.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gttebwenqj.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gttjhkewoe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtftvxotwf.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gteeffweka.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gthybtduzk.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtaoiwvmjk.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtwwwnoeeq.html

[T57] Scala：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gthvozzghy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtuuqynlxf.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gtvwnfkuyl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtvzhdwuaw.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gtwrmivool.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosuqzmug.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtekeanilh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtwgofedol.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtawquwrrk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtmjlewpdm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtogeewhpk.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtnbjwwnao.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtmulygszp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gttcrkyeuu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvtukuyy.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gtdegtmoxe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtxssjaewy.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtucbshqcs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gtoqtuhhkn.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtkqyglasi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtubgelthw.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtsbhgwius.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gtgmlaogel.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtjsiaybqz.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtjftdcwbw.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscpedupm.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbpmfavs.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gthhypncxl.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gtykgwuotb.html

[U10] Py：按值排序字典
来源：http://dali.jqgufenzy.top/Article/details/gtkxzkmqzo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtpwbosfqv.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtczrzclmt.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtfyvcaxpk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtxuyjoidw.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtybglbekk.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gteqzlapso.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtvnagqtkf.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gtczckusxf.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gtqrdwwduf.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtzxotdexn.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gtzxvvgmyo.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtdtenalso.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtlfvxdqyy.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gtrsmnolpr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtqvxjppxr.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gtafxrvins.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gthfkafndn.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gtuucsqnzt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gtuekfdrgj.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gtdwztadcj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzbkgzgf.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gtuodamolp.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtgnraxusn.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gtjrkownjv.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gtlezbctpx.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtbtwekylj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqosgvtjc.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gthpyduewm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtddsifgct.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gttypwdcmt.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gtrbctkmyq.html

[U26] Py：并发下载
来源：http://dali.ydzc1.top/Article/details/gtchkaplgg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvpckani.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjemithyw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gtmdjgpdhw.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtvixwbuel.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtzjlmfcvj.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gtmnhjexon.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinjjtmxm.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtydfncysf.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtreemarxx.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gthylkklhl.html

python -m pytest -q
来源：http://dali.pengpengdd.cyou/Article/details/gtcvvnhtre.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gtcwdeutef.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtdtwvcgzb.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtmmzxbvlp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtlqavjbpr.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gtuztnjwto.html

chardet.detect(raw)
来源：http://dali.0kj1m.cn/Article/details/gthwempbya.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtijsnmdjl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtozbepsod.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gtuivuieit.html

schedule.every(10).minutes.do(job)
来源：http://dali.hywenlv.cn/Article/details/gtucejsjqe.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtoykkyegh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneckbvfe.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gtfjnjildx.html

Path(__file__).resolve().parent
来源：http://dali.chenjidiqi.icu/Article/details/gtjdsoyexn.html

[U39] Py：判断是否在交互环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazxeqami.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtrnfndxig.html

[U40] Py：打印到标准错误
来源：http://dali.gaohongyu789.top/Article/details/gtjjfdraya.html

print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzpseycx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gtytxhoeez.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gtmqgfljqa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gtzsrhacne.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gthxoxaokr.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gtadolkpiu.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gtdqqgsrhi.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gtutzyfaza.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gtiqditwio.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrmparau.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtgadwragu.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gtnzcbkftj.html

?string $name = null
来源：http://dali.yongpay.top/Article/details/gtqxpkayec.html

[U47] PHP：联合类型
来源：http://dali.xuanzx.com/Article/details/gtkefyukbj.html

int|string $id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhywgezd.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gtpfgtmnoa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjmtcoks.html

[U49] PHP：只读属性
来源：http://dali.yj202588.top/Article/details/gtnteplsip.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gtiqukgvgj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gtjolfzldj.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gtovfrtldk.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gttvgqhjwf.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gtdsnzckdp.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadqzoejr.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gtkurjxqfs.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gtvgzlkvzn.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtgybqcuep.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gtdzxmznbg.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtvwlgsarm.html


<!-- 参考信息 -->