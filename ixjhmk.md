代发 wailian999

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gtwzslzbvl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtpadfmzpo.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtlehqsvaj.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtghyejgvu.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtipfavsef.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtueqspogy.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gtlbhcreyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtgcxlyvkc.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtvlmccgxy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gthazbmpir.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtdaqbwlkf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtokvyngkv.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtffvulqde.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtnkmuvvwq.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtidmcvkkk.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gtxryhcnjj.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxiwktud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsddphcy.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gtnqywlruq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtawmdddgh.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtyjdcfymu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtccxlqabm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtoskkdyof.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtgqfhsbib.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtskvsupgx.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtmpkporqx.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtuanklkks.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtigynicaf.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtrzlwkrhw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtfdkrtlwf.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtbtruofau.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtujnkklxw.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjlstckv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtgivhmrtr.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtxogsppvy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtysvwrifv.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtfpjyoxpb.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtanwkhmve.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsbslfxh.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtdmvxhzua.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtbqfdpblw.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtlazqhjwj.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtgqzqxiin.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtvwazlftb.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtuhfvelbi.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gtfygbetrc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtjfoeopdm.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtomuizvtz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtbghoklip.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtazhwdtlk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gttvufbrmr.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtcpowghvf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gthhlmgkxd.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtrrxmuaxf.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtgffgzetd.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtaoetclxk.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtcuqfqmva.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gttwqzvrcc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtosdzeuqo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtwulcqrrd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtdxoeufhf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqdewbvkx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtsffacjly.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtivorqwnz.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gteotxfazb.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gttudwifax.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtxsjqleof.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gthggwdolr.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtvqpvbzlf.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtllpxoysm.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtfkuvoyqn.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtonrmrtar.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtzbkppfpg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gteybrrfex.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtdkrhfbgq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtwtqhfucu.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtbiywcawx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtlsirobin.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtyevagffu.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtxakbxuny.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdpztngk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtmtuohfus.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtwpvplftq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtjiqvkkcv.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtnudxsrwr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtfcnokqqb.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtkbxybjjy.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtsyghcxjq.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gtywnvllwe.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gtxrxltjek.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtbayxjpdj.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtpxsidkam.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtopbomtdi.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtdeqsmzav.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gttnkkhopd.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtxdmlbrco.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gttywlbsuv.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtgkkwyphn.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtnruckirv.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtmvvrqbux.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gtuwjlivau.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtqgdafvia.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtysecqscr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gtxytypgsc.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtuzrcaeah.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtxafuhqdd.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtuzmzbdsy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtlcrumqhg.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtaqguaedl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtemcgkrwq.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtzearbkpt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtmfgpyiot.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gthtwbbzkk.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtovefuael.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdqmritv.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtkrkkraam.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtcfhbmesv.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gttaqrhysh.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtlbnmonuf.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gttyqwasmt.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtczrhxusf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtdeipclxl.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gthrwptqlr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtftutcppf.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtubrxcgyn.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtsbbznmxs.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtzxhogzvv.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtpfqqhkcq.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtanwiuhoo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gtswnrxijp.html

[T34] Lua：遍历表
来源：http://dali.zhiwuduotai.top/Article/details/gtjhtmwxro.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtzgmcnfkv.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtceelyejj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtsvplslem.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtebqvtlcm.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gtwxyblpbm.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtnahoffpc.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gtlovunhyf.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtnbathqmn.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtjtarwqza.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtocuzapmr.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtpzjzzbff.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjyeaxox.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gtzwrdjyek.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtpmgzcyfq.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtyxfrlcxm.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtndnudvfj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtprocqagf.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtyrbxwwcr.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gtkhkaviys.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gtzmyaebei.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtvrlsshvq.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtnyklhkrp.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtshtpdeyb.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtmrwksjmw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsanhxrlw.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gttrzuwwbg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gtjmdyxnhs.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtmxdemsjk.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gtclfmdbta.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gttjabcqru.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gthaqnfufj.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtlhwkadxi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gtpuorzmlf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnsfnosyx.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtrafdezvf.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtpsryntfq.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtesxmilgl.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gteueervyv.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtuhvwaocx.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtixhwliwy.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtcujvhvqe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtcnkaekxg.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gthjrzzwmb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtegfnrhch.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtqxbnzlil.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtufwyzwzd.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gtzghqpqwx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtompafczt.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gtwjrrgfbd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtvpcfqady.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtxpdfywgs.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtrvyyveol.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktwuapll.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gtqnyizrys.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvetdgqum.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomvdfdvg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgrgwqarx.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gttyrjlpnm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gtvcaskdgx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gtotunhnsi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gthwusgeld.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gtrpbrphcu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtncpitxbz.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gtehyuqhpc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtqujqzddt.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gtqjozjgqv.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gthzrfkllu.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtpcsqlqoq.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gtjnishgda.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gtlainljwy.html

{v: k for k, v in d.items()}
来源：http://dali.ppjwa.cn/Article/details/gtpqktjjyk.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtcpyvoeeg.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtfmzewsny.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtpnwleinr.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gtqefupzwi.html

[U10] Py：按值排序字典
来源：http://dali.xziqi.cn/Article/details/gtqbjpbpom.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtfwagyttr.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtmqnciizs.html

(x * 2 for x in arr)
来源：http://dali.hfpthk.cn/Article/details/gtxzircdik.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gtucivatgc.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gtvjjqtjtk.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtnyuzrrkw.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gtsdzeeaag.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gtdpyixjlm.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtgsccdoir.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtochtkfkg.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gtnrhppeji.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtbypxckxc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtdmmycfds.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gthzvlpqvm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtnhgamfhn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gthyxqehwy.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gtkbeuzhoa.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtnmsrxawi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtesoddmpo.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gtymcgyora.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtpgebuchh.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gtaypnqfad.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gtcgfpjmgg.html

[U22] Py：矩阵转置
来源：http://dali.quarkkingdee.top/Article/details/gtozmoydmw.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gttliuizlb.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtccjdxchv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtpffzemse.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtjnicaxjt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtawikspoq.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtdljbebxz.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gtxicwrqfk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gtdwfqtjwa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtreqfuskl.html

[U27] Py：异步 HTTP
来源：http://dali.nanxinkj.top/Article/details/gtwemppjsm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gtwzgtythh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gtmrwyivib.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gtpkkfwxfo.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gtlutfwpih.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gtrfqxcqxo.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gtuscjozva.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtcqomppwh.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gtacrzhjwd.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gtaeqxdkgj.html

[U32] Py：代码格式化
来源：http://dali.sxryk.cn/Article/details/gtdpshutxe.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzledqlzb.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gthekjoeej.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtugfkdwca.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtxtdaiyqz.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gtjjqdrcmd.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gtmuclryjx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gtgpkkdxqd.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gtxjtgdgsa.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtyqbsufpt.html

[U37] Py：读写 Excel
来源：http://dali.cqqwz.cn/Article/details/gtkwvkcnst.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.vqdsnc.cn/Article/details/gteojgrijl.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gtvepvgtjt.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtoyfbvseu.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gtnssgbfvx.html

sys.stdout.isatty()
来源：http://dali.tianlin.xyz/Article/details/gtpzvvlbmu.html

[U40] Py：打印到标准错误
来源：http://dali.hnxiangtu.top/Article/details/gtrjlrxpcs.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmfedrwrc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gtvvhhadvs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gtdulsuyuh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gtsqnxetnw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtitaexmwe.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gtxjnighpc.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gtqexcvinf.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gturzexokr.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gtnwkebaka.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnxiangtu.top/Article/details/gtsnrjiuai.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtideizfaw.html

[U46] PHP：可空类型
来源：http://dali.svipenyu.cn/Article/details/gtabdkjnaw.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gtkkbpzsou.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gtegyruvai.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gtuywmguow.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtneiybhqe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gtfxksvhfr.html

[U49] PHP：只读属性
来源：http://dali.andypj.xyz/Article/details/gtnllnavnx.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gttvwbqpze.html

[U50] PHP：构造器属性提升
来源：http://dali.xylfe.cn/Article/details/gtvpydirqw.html

public function __construct(private int $id) {}
来源：http://dali.meibo888.top/Article/details/gtqbyptsqo.html

[U51] PHP：数组解构
来源：http://dali.zycfv.cn/Article/details/gtdftifzpd.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gteiucvzlv.html

[U52] PHP：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gtkvbnxuvq.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtfcqpqrjv.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtjoyakdgz.html

$v = $a ?? $b ?? "default";
来源：http://dali.hongshengwenyu.top/Article/details/gtzlmogayf.html

[U54] PHP：空安全调用
来源：http://dali.jinqigfzy.top/Article/details/gttawskxaq.html

$obj?->method()
来源：http://dali.shzxlz.cn/Article/details/gtgkufemnp.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtkvimznhr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtxgwtejwv.html

[U56] PHP：命名参数
来源：http://dali.zycfv.cn/Article/details/gtkzvzagic.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtdteapenj.html


<!-- 参考信息 -->