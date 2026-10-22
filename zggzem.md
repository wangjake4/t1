代发 wailian999

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtspivepqz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtqvldrqrp.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gtsmrypdqb.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtqxbkdcpa.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtrhjqalkf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gtrzrdwocq.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtwqjebtrp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtsjhcytlm.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtyxvxygmn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtkmssblxi.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtptfrrhyp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtvdrnwjrq.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtnelfaura.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtqvlozkys.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtcogbmfuy.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtpwzlpawe.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkcjridk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtoiqtczof.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtknkooian.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtttinaxis.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgtqugya.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtdfdyxqhc.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtrmrrwjjk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtoirhkmvf.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtzznadytj.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gthodcnykz.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtosrrsyvf.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtgdebqerf.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtgxffbppb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtatqvycrx.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtjaiesrwe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkskqryir.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtectslhet.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gthmhkjoce.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtixxemnrc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtwxwozizw.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gtvujbpabi.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtbiihtcbr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtgsmqzrmh.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtjscfelvb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtunjikdgo.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gtuevkcwpl.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtlfxodxui.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtxxqvskni.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtopyyzcef.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtfrbxjhhn.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtxkfulhng.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsdkarpv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtobqpotfi.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtwvlkcopa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gthcxcqgsi.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtdjabfvxc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtiyjwwsex.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtlezpktny.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtgehghktf.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtqcadhcnw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtackmekfh.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtsqvzqnmw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtuqparnbk.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtgwfywqhy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtaevlvlmi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnxichgoq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtaiwlscvc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtffcuarhx.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtrtuwtvmx.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtbntjqshw.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtbaqrovzd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtnvdfgzly.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtzpyuphej.html

"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtaelgyktw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtziyprgws.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtmfqmribx.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtgfpcmszy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtybojdvyd.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzlysnbq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtslpnfagc.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtylhxvmei.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtrwocsque.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtbmgdsgaa.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhqxbuuz.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtzqseluka.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtfolplawi.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gthsozxciu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtgtiakmkg.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtphixbowm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gtrrzteume.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtndiqdzmc.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxflpcehd.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtsnsprpjq.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtpyrbrlcs.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtabwvfcgf.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtghlmwnef.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtnhfqcnko.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gtwekiyshd.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtvfiywkhw.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtxbninkak.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtuycqftzm.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gtoekpgdlw.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtvviousmt.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gtowutlmeg.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtnonhsdch.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtofwhybml.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtcqpojppf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gtwburffng.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtmdwderve.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnukxynsy.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gtlownkquq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtkjbsovnr.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtvvenpami.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gtyuyjwihi.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtvwmnjqgr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtvmgdpmtf.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtlwjitaop.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugoetfuc.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtuiebbiph.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gtcgtxamjq.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gtchusipja.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtxssyjjly.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtwfrmnzdf.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtjlaxyuht.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gtjcwbkvyf.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gtsybuqptm.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtfjlzoxso.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtoayzxxrs.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtxyltkgww.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtbfgdlfju.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gttzgddcgj.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtpwgkguep.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtiiokngqg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtmwffzhto.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtgdtdicru.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtrgbteldf.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gtedomcqyg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gtrechwrgs.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtukzrzxzb.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtyqjsawfs.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtwnxpcpot.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gthjbjyaxi.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtynzjpfqa.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtahkfousr.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtiejdnpcc.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gthjctwxta.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtesfondwf.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlzeqzam.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtiwriojzr.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gtlqneobcp.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gthicyqfum.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtajckmtip.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtalqabrzk.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtvapzfbcp.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gtxcadovkb.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtfmqewejr.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gtkkqgttqx.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwgdocku.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtkzwmerex.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zdqjudy.top/Article/details/gtzwgpfnxz.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gtrnmqbdna.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtnijsqufr.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gtqgznsedr.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtlpkdanca.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtxukegwvn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtbbifcnjg.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpgwtgmxp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gtvqlfebwd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtlhllvxer.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxwmhbaf.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtfiffhshm.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtzxtkfabe.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gthfvkpxfs.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gtprpmckqp.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtddbytnoy.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gtwzorufao.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gtbiuykhex.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtlbtbttsg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtgdlmdxcl.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gtnkoxazlr.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtgnkibego.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtiwyrxbwh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtdyamfbql.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtjugksuam.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtihcohuwv.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gtwflmwgus.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtzfkwqncy.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiwhzcuk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gtlbypeoyr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyurqxfyg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gthkqiyevt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtykjjfdrh.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gthpxjhppk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtthpqsnmq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtlavwolbs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gtlkwjmkkm.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gthkhvkpzd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gtlmphfwrk.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtbxbmrvjb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gtqubjjdqs.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtabmjvvhj.html

list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtgiaxxssi.html

[U06] Py：合并两个字典
来源：http://dali.zycfv.cn/Article/details/gtzacwwazh.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gtvautvxpu.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gtngrryqen.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gtplhruokb.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgfrsehb.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtwuvmhlhz.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gtnkiaahpd.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtyrbdkuet.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtdkssfboy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtqihutppr.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gttxsseosa.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtshqrzbga.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gtbiowaqij.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gtspbckand.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gtjbdqolmd.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdagylqe.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gtjzbmpjvq.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gtoulkknqo.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gtwjyuifee.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gtlxesqfri.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtrbgunupq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gtzwpirnfg.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejdmlzas.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gtqalpkqna.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtgexvqxdh.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtmkkhvgku.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtfoddjsnl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhongyouzk.top/Article/details/gtqjxnwxhg.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gtqsvbppfi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvjkzomm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gtlenhvnxk.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtpnqdkqna.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gtzjymrjkj.html

list(zip(*m))
来源：http://dali.iojbl.cn/Article/details/gtsyyxssnk.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gtlduecuhz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gtaqljeifo.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gtlaohxydc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtspqjsfxy.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtvawbijek.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtrliblfce.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtauymwskq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtnbpryubr.html

[U27] Py：异步 HTTP
来源：http://dali.ehwqpu.com/Article/details/gthwtgolxo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gtmiviwyop.html

[U28] Py：类型别名
来源：http://dali.zycfv.cn/Article/details/gtomygfpub.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtsactfexh.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtastflcke.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gtzbdvpzzo.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtlwdbsric.html

@dataclass(slots=True)
来源：http://dali.gotoacloud.top/Article/details/gtwvobthlm.html

[U31] Py：单测
来源：http://dali.andypj.xyz/Article/details/gtaoqtwdmq.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gtqjxuesae.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gtqiagbbkm.html

ruff format . && ruff check --fix .
来源：http://dali.guowangkeji.top/Article/details/gtnmsohvtr.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtchstdggq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gtiistkfeh.html

[U34] Py：判断编码
来源：http://dali.kuanghao11.cn/Article/details/gtruvkxzyh.html

chardet.detect(raw)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoudqbhpb.html

[U35] Py：发送邮件
来源：http://dali.mhx1999.top/Article/details/gtgvyineyy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gtyhztcnrf.html

[U36] Py：定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrwxoapx.html

schedule.every(10).minutes.do(job)
来源：http://dali.tanke756.top/Article/details/gttntmeddz.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gtwultccug.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.feifeiyinyue.top/Article/details/gtemxvzdih.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtkdvcrnst.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gtmmrjifil.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtljclxpdu.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gtqzefkusj.html

[U40] Py：打印到标准错误
来源：http://dali.shuidangran.top/Article/details/gttzpwbaxa.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtvamylhjl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gtipgnmbqj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gtzioogude.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yueranfly.top/Article/details/gtpnpdcalw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cashguo.top/Article/details/gtaclkszrg.html

[U43] PHP：声明命名空间
来源：http://dali.dianchejie.cn/Article/details/gtplqcjhrm.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gtcfmlazqa.html

[U44] PHP：开启严格类型
来源：http://dali.hammf.cn/Article/details/gttosxnhel.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtqakfbyst.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ivvv.top/Article/details/gtuobidgzs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtemifizjt.html

[U46] PHP：可空类型
来源：http://dali.meibo888.top/Article/details/gtdedkqexr.html

?string $name = null
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlywzanbz.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtdfmdxhev.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtpstmwetg.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtgovqfxnv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcgmwcuc.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gtiuuasqoy.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gtfhqlohdt.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtntgpnxyk.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gtbvgukmxj.html

[U51] PHP：数组解构
来源：http://dali.zdqjudy.top/Article/details/gtdguuxsxl.html

[$a, $b] = $arr;
来源：http://dali.gogol.net.cn/Article/details/gtdchvmiar.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gtjxmqjvds.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gtwnkszdjm.html

[U53] PHP：空合并运算符
来源：http://dali.chenlongwang.top/Article/details/gthmodtdzv.html

$v = $a ?? $b ?? "default";
来源：http://dali.havefunace.top/Article/details/gtipehlvdo.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gttvrzflvc.html

$obj?->method()
来源：http://dali.chenlongwang.top/Article/details/gtkxyidrhb.html

[U55] PHP：match 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtclmniusj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gttotcargw.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gtxrrhfzfa.html

f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtnbppskju.html


<!-- 参考信息 -->