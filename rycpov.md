代发 wailian999

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtjerqysqq.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gthldebtal.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtiyxjullc.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtuqrjyjmw.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtozxxizbg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gthonmtfzr.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtlkywlqhv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtsvhaubum.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtjemtbotn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gtibwboysg.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtbmhbgxka.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtgtwdekps.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtguemuorp.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtisgkhekp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gttxkszekq.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gttbizmyuf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gticymxfax.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtuwttiweg.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtqooiddqj.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gtvqaivmig.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtsccypqmm.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtcvxiikyo.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtijfvqwtp.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtbzfepueo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtpcdsuc.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmsncdmc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjfnuxps.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtjovicvku.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gtuykngqne.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtqphtoksz.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtqrprhnje.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtcstmrutq.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtaubjjznw.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtsgybxfgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gteaptcykp.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gtwygquvrs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtzqehbgjx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwqjyuriw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtbgnzcfli.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwhdrgxqu.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtmsfyrmtm.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtijwnvwik.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtathwfkbt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gtwuxlszet.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaqtgdfq.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtvsjheguh.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gtqxnhdgwz.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gttyindbxx.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtogdlnwdc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gteqawohzt.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtrbhafwhp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtvzhmbnpb.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtkgcfybgb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtegpgiaff.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtujzbecxn.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtgyykdjib.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtuwkdqsky.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gtcyuvrffh.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalbyjwzi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtzfoiksmm.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gttiqfyhgo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtrnxtfgrr.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtvtpdbzpu.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtgjeauogl.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtvmkmehkx.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtokmrvbbh.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtvidjxopb.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtzafqjhns.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gtdnlohmqw.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtxxfjkbju.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtqggytbag.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtolnunudt.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzeyjdgr.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtkwoaimez.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtavsqwejk.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtcopgnavg.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtzslpeizi.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gtbkayluxi.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtwoshdppe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtoghqlswx.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtudrxirhf.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gteldtjcku.html

[T22] Swift：字典
来源：http://dali.pycfn.com/Article/details/gtgpcrnixo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarbbvowo.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gtuohzylmb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtuadnidcr.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtbvwasnpp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviclmmud.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtadwzadxi.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtihtfenwq.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gtbszelagi.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtkmsxucxd.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtxlirdcag.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gtdepaozxj.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gttzidtswz.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtwdmehsop.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtdsraidwv.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtycsszvyl.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtwvutgrph.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezqwvwme.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtafwfggej.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttycvvgdq.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtmfkpdrow.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtpwtvmndn.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtbtwqremf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtzdyveoeg.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtxsqqxfsr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtwwuwrzpm.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtbmnmgvgj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtgtogdqfu.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gteyplmihz.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gtydvgbmej.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtjmiivzsa.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtifootnjx.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtliobcpkn.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtipiktrxv.html

[T39] Lua：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtluouwrde.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtuuzeubiy.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtyzokjsyi.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtziqdvkxs.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtnqupcdat.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gtcahmicvq.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtroicjuxd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fzhhl.top/Article/details/gtwgxtygpr.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtsywgavvi.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtoceoztpm.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtxflttgae.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gtikahvoox.html

[T45] Perl：数组遍历
来源：http://dali.gogol.net.cn/Article/details/gtigsyotrz.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gtoescxlxg.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gtbxcconap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtixwownhv.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtrhezedee.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gtekxpbopd.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtflwffpzg.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtdxcknqoe.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtduqnfrji.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtlnnyfhyf.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtckbyyklc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtazlcnrxk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gtheemvptx.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtoplsqcoj.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtksbsvkrx.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtnwjnsggg.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtjjyzsdzk.html

[T53] Scala：字符串插值
来源：http://dali.yonumen.top/Article/details/gtjuqivoia.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtypnczdkj.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtdejcqwxo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gtzylyohsa.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtuembkzng.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hammf.cn/Article/details/gtxhvnxzxn.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gtadyskipi.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtgmhhvmtp.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtmtaglesq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtupbvgxgg.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtrbdtjbts.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtbqepfusd.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzgdbqxz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtqgzragfn.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtwzfifnqt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gtnrybuleb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzvfxnpz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtztqipcpa.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtijhnmulf.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gtibdbllqh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtkrncvxtk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gtivkjytoq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtnzxeivrb.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gtfbkxeorm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gtbdoqywqm.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gtlgcjysgf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtxfmeefgg.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gtyvbhlzsv.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtnficnsam.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtudtqsjbp.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gtjfllxtve.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtoyrjxmfi.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gtgxwedheh.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gttrxxzmpz.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtuxlwawhm.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxwubjqn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtrxbmbsat.html

[U10] Py：按值排序字典
来源：http://dali.daxiang520.top/Article/details/gtlhdkimlo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gtuzrajiki.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gtzspuazow.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gtmgxdgnlk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gtkofbbkfc.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gteaqtcbnl.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gtyhfbfrvz.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtjxafcock.html

[U14] Py：分组收集到列表
来源：http://dali.jqgfzy.top/Article/details/gtaxpnzojt.html

defaultdict(list)
来源：http://dali.fengsongda.top/Article/details/gtwzwmnnsv.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtdtrpvlvb.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gtypppripv.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbcdrifn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.kuanghao11.cn/Article/details/gtvmwhjflg.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gttkeimjzy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sufxvd.cn/Article/details/gttpihqyhx.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gtoladuohz.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gtdvoyqgth.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtwomkvpay.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gtyhnixfxd.html

[U20] Py：缓存函数结果
来源：http://dali.fengsongda.top/Article/details/gtuyiiobxu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtqdpxzrza.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gtgovhsezk.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtprkqgrrp.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gtpsjdrakf.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtqfeirkbr.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtldygrhkx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gtmzqpxgod.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gtlkeymped.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtxagebare.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gtctakpjzo.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gtynnrbbjc.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaflbngm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkbvsupz.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258888.top/Article/details/gtnxvoekav.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtcpavxhnu.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gtzipxhcwn.html

UserId = int
来源：http://dali.hammf.cn/Article/details/gteooorqpt.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gtnnjyilab.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gtplptmpvo.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtdxpckmjm.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtqmjjqcqd.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gtsgscjynh.html

python -m pytest -q
来源：http://dali.zhengqikj.top/Article/details/gthcqxnmiy.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gtpfusqred.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtydxdfzzb.html

[U33] Py：打包发布
来源：http://dali.cqqwz.cn/Article/details/gtrstlqtxk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.vqdsnc.cn/Article/details/gtuqqomdtv.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gtsbzomgva.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gthhclhqsc.html

[U35] Py：发送邮件
来源：http://dali.xinyue.icu/Article/details/gtbordxpju.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gtawpucffq.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gtnxeuxpzu.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtrkgaaxvv.html

[U37] Py：读写 Excel
来源：http://dali.9152youxi.cn/Article/details/gtcyfvukfn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gtjcciixji.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtctcleqdf.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gtpmwzlwmo.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gtksfqxfhw.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gtoknmrfxx.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gtloufqizy.html

print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtnnxcagpb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtmysklemn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtvzrqvvzn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gtvthzmswe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtihualyhi.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gtcnwnsmaq.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gtzdhlzbuu.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtwpiwuckk.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gtlsulhyez.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtuhqtberk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtrleoxuht.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gtnyhvzmim.html

?string $name = null
来源：http://dali.gotoacloud.top/Article/details/gturxntyxj.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gtfptmriwe.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gtzxaeahqn.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gtcemxndqq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxuanxn.top/Article/details/gtpffziuei.html

[U49] PHP：只读属性
来源：http://dali.yj20258.top/Article/details/gtuitelacz.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gtvinggesd.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gtvhpsbije.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gtevosacsg.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gtbkuzaptk.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtqxumpvko.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtyllelhry.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtxcsqsgmw.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gtprbmpgml.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gthajqlmgh.html

[U54] PHP：空安全调用
来源：http://dali.aibaodan.cn/Article/details/gtakkelmgo.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztqipawg.html

[U55] PHP：match 表达式
来源：http://dali.yj20258.top/Article/details/gtrkessvwh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtaudjsrwo.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbfnnxdz.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtaqqczhor.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtoxqeqwia.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gtiboloidi.html

[U58] PHP：数组三件套
来源：http://dali.jqgufenzy.top/Article/details/gturbuqnpv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtmgmhkutj.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gtuzxerptu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcxzbqke.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gtdmhccijk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gtiinpdnar.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gttduvjaqf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtbihwcsqa.html

[U62] PHP：日期对象
来源：http://dali.zhongyouzk.top/Article/details/gtnvkegxyy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gaohongyu789.top/Article/details/gtvniniock.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtxzxyhktw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gtndrinqll.html

[U64] PHP：目录遍历
来源：http://dali.sysykeji.top/Article/details/gtcpnrzosh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gthezdxmmz.html

[U65] PHP：会话
来源：http://dali.hongshengwenyu.top/Article/details/gtsptsvueg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtksdahwwr.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gtvfrocqkb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yueranfly.top/Article/details/gtfeultraw.html

[U67] PHP：处理文件上传
来源：http://dali.yangfankeji.com/Article/details/gtdozcdlax.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.316326.xyz/Article/details/gtuthsaydk.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtjatdnvzz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dianchejie.cn/Article/details/gttduzlbdg.html


<!-- 参考信息 -->