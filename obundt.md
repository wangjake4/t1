代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdsbxdcz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtujtkvfpu.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gttqwkjjqv.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtafxzzuxu.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gtfugnvwti.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxarykwb.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtjrkfpepn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtwirmpacs.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gttnkmrjhc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtdwquyywk.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtrlehjspo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtfqgaxlgz.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gtcfwehrey.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtyjygzdjl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtdfdmxzgs.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtqjovsnne.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtrmcbqfjs.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gtpkwtxedk.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtzpkntxgf.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gtsqafvaim.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtmipeowwt.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezutgkhu.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtrlqvtvvg.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtohaocjfz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtadmqfhtx.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzpxkqgl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtrrnhgxju.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtwpayxbjd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtdqbpwqrv.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtkpljhihw.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtpfxeqzyu.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmbsxine.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gthepjqmwm.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtijhnyrri.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtfewmwllw.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtllmuajls.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gttrdpmnea.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdphbxtdk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtstacoahd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpxuwzpmk.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtbqvyzsbs.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtlplizzwg.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtfxovbkbd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtiwvtwhgl.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtwydadmly.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtgcveurjp.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtafjtnmsp.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtqhudhtgg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsiedzix.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtibdbicoo.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtgtouiqrz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtdqigsdzh.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtsslneqrc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gtfijwpbcv.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtmodfezki.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiomggwcy.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtsjkuqklh.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gtmzuszjwq.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucjlypbc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtbmjmldqg.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtmnrwvstn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtdwqtqpch.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtpfnhmyap.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtxwbpeech.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtrvuyugzb.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gteghrylxa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtzqixfgrk.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtkmpiyfrw.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gtdwuezpgl.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtshvhkajx.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtrteymhgn.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtbfptqtsa.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtbjmopwgp.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwjulyoc.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtpfgpfqwk.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtrmfanqen.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gteduwigvx.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtwkkcfjub.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtexgkmjgh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gttqijyfvp.html

[T21] Swift：遍历
来源：http://dali.gotoacloud.top/Article/details/gtzivixgrb.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gtoicstqdc.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtxmphrdlj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtogrdxdqi.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtucmamwqq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gtuyyendty.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtcmosmgsw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gtemgqbzsj.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtochtxwhp.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtxbftzswx.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtmnjazxko.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtnemmokbz.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gtinpxdiwj.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtqtziobjv.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtwwnqqmez.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gtgooqdooj.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtdikeivpr.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gtmzfqndlp.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gtdpfbugsu.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gthwjauktg.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gtoscjmugm.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gthrmhtvtk.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtvffbmybi.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtpuoyyydf.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gtnkhdkbfc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gtfhzlcwxo.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtofzlgktr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtltzjftiv.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gtbekslsih.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtqbzejwmg.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gtykezqvlf.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtjuiioauf.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtfwasjfrz.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtwlqwlypp.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtgzwupyer.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtbaqiudnx.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtvadefoxz.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtxlptdfdm.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoplvesk.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gtsyaskdfy.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtlecmorvq.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtbjxmsegv.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtykpwfqtn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttetcxspy.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtreifdbna.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gtraicjcfh.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gtkrsnffqp.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gtvcandqtw.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gtnzayumbt.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtppuiecrk.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gttjaqfydk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtlvdqfcze.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gthcwvrpth.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gtmkbosqjm.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gthwtiultl.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gtuagxalgq.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gtafrzpkny.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzixegde.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtroisfvyt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtxqaxzqux.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtpzhylxkv.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtlugyjtqy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtkfnhpyxd.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtxffcyzae.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtzxfkbqkq.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtlbrhljkt.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gthcxqbopy.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtbhjwhglu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtjrlsrrjl.html

[T55] Scala：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtbmdktqpb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtijhvbylh.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtocpzphel.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtkzqgmucm.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtttmcaoql.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sxryk.cn/Article/details/gtukulfoww.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gtdqrwnsbt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtdqcwebrd.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhqwqqzz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxkirola.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtjfdfnxvn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtnziwelzj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfqfnpehj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtxxypsuge.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuodurcaq.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnabksmq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtvsekupbm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gtgujvighy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtyjljzvai.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtehtzwbwn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gtcthxqpbl.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtcflmhssf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtnbzhilbr.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gtfbmemrol.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtlmqqeqrx.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtjgfixagm.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtlsewdabe.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtzukurctt.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtzmebhefw.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbanerfy.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gtdzupfzwj.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeuofyyn.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gteartajdi.html

[U10] Py：按值排序字典
来源：http://dali.c1oappe.top/Article/details/gtchibuilh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtwqgotavp.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdihpsat.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtcpxiggjk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gtxfuzxxfd.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtpegxzulq.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtlglybypk.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gtqsmarwim.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gtycveqzlb.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gttgpkdhji.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gtjxenpztf.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gtxeomnxzw.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gtxolrfwsg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtuqvcymwn.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtjimrwyjg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtoipnyzsn.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtrkdlgtor.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gthgcgoakw.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtwzjexktl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtckhfrcrd.html

[U20] Py：缓存函数结果
来源：http://dali.gotoacloud.top/Article/details/gtmzhcwhos.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtcqrtdcmt.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtympppmkt.html

@contextlib.contextmanager
来源：http://dali.zhoulong.xyz/Article/details/gtzqenflix.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtyhxcnzzm.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gtfxjfhzfv.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtgqpxxpof.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtmoqmvtox.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gtmxfzalfq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffiryqoj.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gtoqdobrxo.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtbqoqtguz.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtadnnwduv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gtahfjvpyf.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gthyglpwps.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gteurwwfgf.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gtoxzgtpql.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gtmhzvgoxc.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gtawgtooiz.html

@property 与 @x.setter 配合
来源：http://dali.gogol.net.cn/Article/details/gtgyuogjne.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gttkeedefl.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtfeuawenl.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gtmumhfrwf.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtwuuqjsaw.html

[U32] Py：代码格式化
来源：http://dali.tian-w.cn/Article/details/gtatbqgscs.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtvfwdritx.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gtptsmnzzq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gtrrssvwyu.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gtfxqpscbx.html

chardet.detect(raw)
来源：http://dali.guowangkeji.top/Article/details/gtpcqsdkvb.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gttlnqrpzl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gogol.net.cn/Article/details/gtcyzsrtcn.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtoweglewa.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtifkkdvyd.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gtazfueyeh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtddxpwzos.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gtrkwjosfo.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gtbcgpauox.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gtkmhqdczc.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtvrgwysdh.html

[U40] Py：打印到标准错误
来源：http://dali.hywenlv.cn/Article/details/gttxbpaghd.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtjcsnzdzz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gttivangdg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gtbbevnygz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zycfv.cn/Article/details/gtnzohyjmn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiiwxsyb.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gttlruvooo.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gtxfrvrpwe.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtifowwlku.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gtaqdemtus.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gtqlybwmex.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gthpfkaznk.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gtxsvhoqre.html

?string $name = null
来源：http://dali.haohaochexian.top/Article/details/gtfwcafrtx.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gteiczqjpw.html

int|string $id
来源：http://dali.zhixingplan.top/Article/details/gteznroszp.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gtuzaynxgp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqisrxwld.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gtucghcfwa.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gtoypjjbpu.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gtuurzbvis.html

public function __construct(private int $id) {}
来源：http://dali.gotoacloud.top/Article/details/gtmranbmie.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gtmslpapsp.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gtqensvtwj.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gttmonoeke.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtqgcodigu.html

[U53] PHP：空合并运算符
来源：http://dali.cheryme.top/Article/details/gtbdgybsxn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gtldxcmypd.html

[U54] PHP：空安全调用
来源：http://dali.9152youxi.cn/Article/details/gtazcuemhz.html

$obj?->method()
来源：http://dali.bjfxy.top/Article/details/gtrctdqksn.html

[U55] PHP：match 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtydpdnfaa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xziqi.cn/Article/details/gtvdgstlhx.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gtakgptqsw.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gteumnfkoh.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtlszsbsww.html

"值: {$a}"
来源：http://dali.iojbl.cn/Article/details/gtkyzlfejz.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gtlzbelygs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gtuxujbocc.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gtxyvrvoiq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtopqvjutc.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gtllqvcdkp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.andypj.xyz/Article/details/gthffrltyv.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gtlsybovdr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtbolofcew.html

[U62] PHP：日期对象
来源：http://dali.cucudq.cn/Article/details/gtzimueekw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fzhhl.top/Article/details/gtqctmvfct.html

[U63] PHP：文件读写
来源：http://dali.mhx1999.top/Article/details/gtlaputqzb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gtlnonjkah.html

[U64] PHP：目录遍历
来源：http://dali.cdnleiting.top/Article/details/gtoyxtkbvn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gtmkegzbkw.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gthigrqmes.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.havefunace.top/Article/details/gtlyipfttg.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigfzy.top/Article/details/gtqgakxwtj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gtohzihgat.html

[U67] PHP：处理文件上传
来源：http://dali.yj202588.top/Article/details/gtileyztvb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtpzuiyuea.html

[U68] PHP：PDO 连接
来源：http://dali.bjfxy.top/Article/details/gtbemzeasy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtylisrrad.html


<!-- 参考信息 -->