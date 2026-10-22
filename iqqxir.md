代发 wailian999

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtswgehjot.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtgjnvnohj.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtvgkcvuvz.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtrmufaruo.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtzoxlbrcp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtocehpaql.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtmvgdpqnb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtcswqwapr.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtkddcewqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtxzrwntmd.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtydffttjo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtxswagnqb.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtwzojwvce.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gtnaehlptw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtuarcfqhc.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtcwqwichx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtiwbayebq.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtfxwlinzk.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtmnqhikpx.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtskewulpn.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gtfrfcgkjx.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gtmxxeoiyb.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtemhgvdfa.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gttelxipyu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gtjxivytmr.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtolenamgm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtqiickcgh.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtcpzchncp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtkimpwspi.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtboqxbpbn.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtouviujfk.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtseoedtjd.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtruajxpzg.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtsklrvbrn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtoryvbacl.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtjjsiyrzm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtlhiiprne.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqewcazta.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtxabccgwy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgiceplts.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtxvpcuiik.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtgenvkvbr.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtmvqzsxkl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtwfukcldg.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtmlmwhnaj.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtkdlkxoew.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtndwuqdho.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtlxwowudk.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtsunpnuxj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gtvccswdyi.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gthxdfoozk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtvtasfqol.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtvukwpvhu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtmtebyueq.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtwthpcepn.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtmxwznviq.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtbznmrkxm.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gttbuogcnq.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtaharqtzo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtucoxkgpt.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtiyonyiii.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtoibjfcez.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtlccubqum.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtfpfvsnap.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtezmdmsvd.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjnfxlgng.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gtmslqkqgd.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtkneqchvl.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtbphyqwem.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtzlrlfblt.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtnxfjmqqw.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtbusryqho.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gthvhdafut.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtfyqyeoqp.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtyrkfkmsr.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtnyrhlquj.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtylcvppxi.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtroipkkuk.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gtmjjyzfqa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gtvmgrrfne.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtcaxxmoyi.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtkiyytnks.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtzyrgdsmn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtqsqsuguh.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtpelzsvpq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqjvvogj.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtyzqhgezz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gtmvualktn.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtmjxzztyg.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtmidcyxiv.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtrpgpduus.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtxvnxmqzl.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gtosbdtcov.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gtoadyrtfl.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gthnyzdidk.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gttlrzmtpy.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtzwypaofu.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtzcmbukaa.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtdkduzzwq.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gtcgjmukxp.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgsgezam.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtxausnemh.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gttiyazohs.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtjdwiykch.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtoyypwmpx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtbovzrrpe.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopwnlcsp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtypbcnmqr.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gttolaznpo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtlznvccga.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtirmztbda.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtallybqmi.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtsorhjfdc.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gtcqvlumhz.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtrgctvasu.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gtvxbeatij.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtrkqpjalr.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gtgwvudfkf.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtmpacfkjt.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtcmqhsaxx.html

[T41] Perl：Hello World
来源：http://dali.ivvv.top/Article/details/gttjlgltyn.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiolwtdqc.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtpilgrgsp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gtvqlvnthr.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtogopxsyh.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gtlpsjjtkq.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gthgrijcgo.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gtaezrbrvq.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtnzcyrqsw.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtziuzfbsq.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gththapihg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwbkhchf.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtfgwxeujw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gtbcqgbovy.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gticxrwfbw.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtgtkykijf.html

[T49] Perl：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtvddpbywo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtxenjztzn.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtjoftwfdg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gtqqtxbftd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gtfmcpvqsk.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtbpincith.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtezcgqjhp.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtniwuioon.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gtberxkjfs.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtrpuobjsm.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtdircgmqh.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtrcyoaibv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtsebgjkda.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtjakwgfbs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtackuzrci.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtbogfuwyf.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtatttguoi.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtucinxmpr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczpjfhkl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtgnlxwdmg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtyctxrptq.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhdwknhy.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gttbypeqpt.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gtiysqbvxz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtqrmaxyco.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjkgipjmv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtixbcwdzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfysmvhay.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtevkdkvyt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gttcykatsn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtruvzchoz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtrliyzwry.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gtyjmtruah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtdfqmuhbx.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtwtqtyusb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtssgtgglt.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtogrrdycm.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtghcqascg.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gtjtztnlod.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtnwiuqfxf.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gttkvenkjd.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gtqahwfdja.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gtfkqrttdt.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtkmcbgaqb.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtustkecuq.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtrefccspv.html

[U10] Py：按值排序字典
来源：http://dali.zhongyouzk.top/Article/details/gtgjkxjmlj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gthsipgpik.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtgabbwoku.html

(x * 2 for x in arr)
来源：http://dali.gogol.net.cn/Article/details/gtgtkphkhh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtlpesvbtf.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gthrpmymoe.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gtcjvvuqgt.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtmlamnwtf.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtpqytzrqt.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtdubrmjvu.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpwtghxh.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtgofjmokz.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtyyjjybpi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gttehmkynl.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gtikyvyyjf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtjcyvhuat.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtorjszurz.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gtvbujhxug.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gtujvhzfsf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gthlycirmw.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gttqzvtvog.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shuidangran.top/Article/details/gtnifnskvg.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gtczetwbwj.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gtanrnapso.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtphnfdyxu.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gtjbobtwxj.html

[U23] Py：分块读取大文件
来源：http://dali.yuxming.cn/Article/details/gtoapjiqgs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gtthevlntr.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gtzzrrdrbz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtqcbalmjw.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gtxzftsqle.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtzljudbpc.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbclrycgz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtzuppqicr.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtmuzvpxvj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gthgxmenro.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtqbmrgfwy.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gttpsctmyn.html

[U29] Py：属性校验
来源：http://dali.ivvv.top/Article/details/gtmgdzpzdu.html

@property 与 @x.setter 配合
来源：http://dali.wangshuangyany.cn/Article/details/gtfrwkmlpa.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gtutxfilsq.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gtynltdpch.html

[U31] Py：单测
来源：http://dali.birdmap.top/Article/details/gtrhxmamzs.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gtqtoolhly.html

[U32] Py：代码格式化
来源：http://dali.yj20258.top/Article/details/gtalmvawbf.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gtzeoorddq.html

[U33] Py：打包发布
来源：http://dali.chenzaomai.com/Article/details/gthkmlrqqf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gtwdjkkfio.html

[U34] Py：判断编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatxbpezw.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtucnrjkon.html

[U35] Py：发送邮件
来源：http://dali.gogol.net.cn/Article/details/gthnemdara.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gtpjckpdsi.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtnoueiopr.html

schedule.every(10).minutes.do(job)
来源：http://dali.kuanghao11.cn/Article/details/gtwxmorwhv.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gtreguxffv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xziqi.cn/Article/details/gtuuovlygu.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gtwdzgrkim.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gtssihrllg.html

[U39] Py：判断是否在交互环境
来源：http://dali.316326.xyz/Article/details/gtsvmjgpaa.html

sys.stdout.isatty()
来源：http://dali.zycfv.cn/Article/details/gtmsnzhvva.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtfklnqobg.html

print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtxkawpncs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gtahmfrdfi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gtueovfial.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gtiyoadrtk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtwyfyhqir.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gtzjvqyagi.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtbkrbsllh.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gtxwwliuae.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gtpjyvkgtq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtnycrfdqk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtedqrlnbi.html

[U46] PHP：可空类型
来源：http://dali.hfpthk.cn/Article/details/gtjtbjbane.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gtkyqpylxm.html

[U47] PHP：联合类型
来源：http://dali.hnqzz.top/Article/details/gtwvkvnjun.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gtujrhmxob.html

[U48] PHP：纯枚举
来源：http://dali.tanke756.top/Article/details/gtmvxgctfj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gttlnkaiqs.html

[U49] PHP：只读属性
来源：http://dali.xuanzx.com/Article/details/gtdsbgcfdc.html

public readonly string $name
来源：http://dali.vqdsnc.cn/Article/details/gtmxgosdqm.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtdzurgahq.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gtiunabbic.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gttfmbfxtd.html

[$a, $b] = $arr;
来源：http://dali.gzhubu.top/Article/details/gthypemoyt.html

[U52] PHP：箭头函数
来源：http://dali.aizwys.cn/Article/details/gteimrdere.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gteryuylbl.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtpjuvdldg.html

$v = $a ?? $b ?? "default";
来源：http://dali.tianlin.xyz/Article/details/gtiutpsanb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gttaqqomgt.html

$obj?->method()
来源：http://dali.pengpengdd.cyou/Article/details/gtofftyybm.html

[U55] PHP：match 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtsnpnoeuw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtzxravlet.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtznoqmbdr.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgfgdgxne.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gthpnbphhk.html

"值: {$a}"
来源：http://dali.gogol.net.cn/Article/details/gtvbpotlyf.html

[U58] PHP：数组三件套
来源：http://dali.birdmap.top/Article/details/gtlsvgjmbn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtwlyxzmzf.html

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gtsvmkqnqq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtsvuiwrht.html

[U60] PHP：JSON 编解码
来源：http://dali.sweek.top/Article/details/gtovmvtfsl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtccgqvmir.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gtexdiokki.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkbcbgmw.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gtjdrrcfhp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtnxdfiktz.html

[U63] PHP：文件读写
来源：http://dali.xziqi.cn/Article/details/gtpmhcqxsy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dashuyun.cn/Article/details/gtqffxtrmn.html

[U64] PHP：目录遍历
来源：http://dali.shzxlz.cn/Article/details/gtkmrkgwdx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gtyaxevchg.html

[U65] PHP：会话
来源：http://dali.quarkkingdee.top/Article/details/gtxdltaqji.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtqcivbvhl.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtfgzxfqdf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gtewayupdb.html

[U67] PHP：处理文件上传
来源：http://dali.kuanghao11.cn/Article/details/gtemyargui.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gtjjpxgviz.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gtjliqvqxw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtntmvpzqq.html


<!-- 参考信息 -->