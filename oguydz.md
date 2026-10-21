代发 wailian999

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtbtbyaxuv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtqvufojyw.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtvbjhsgeq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwujgpxgx.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtwmealhmw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtydvkityd.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtuflvgsli.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtegzcxdlc.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtpqhepotx.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtnghmjish.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtcwxsvsso.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtkucmhvta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gteexcnkod.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtxkjnihjo.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gthffgzzlc.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyvcohqw.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtsicfdycd.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtfrrwagmt.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gtzzbrtjej.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtaoxmysca.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtfldlgyez.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gttsvecgfl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gtuxemtfpo.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtzjkhfyzk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtsldsmxam.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gtkutaefmq.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtyivrumag.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtqefgrvaf.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtepixcacr.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtdwzbedne.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtynnwdgfw.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtvyabwooa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtewiyjtfs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtddtggtgw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gteuzyquag.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzkdwaygx.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtjmzqcwlp.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtafgrtobd.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtcalynwno.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtbeoosqbx.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gtscjzvcmc.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtndzjnzsd.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtvydgwuve.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gteienauzr.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtrzsrgcct.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtszesnwct.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtnrbqdawq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtahbcmshz.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtgkbrtrsl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtougkzspd.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtctchrlpf.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqsffrzd.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gtwvwqdpxx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gttngglvft.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtayrgbxjd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtdxpfooas.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gtrmdedwoz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gttfyyimty.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtqxllppnh.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtwwhveyfg.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gtxtwgkryw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gtslqykewp.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtuxpmukdp.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtkhsvyhie.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtvceqyqco.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtkwonwqno.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtfxbssvrd.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtlgktkxwu.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtyhkrxenj.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtxnqmrpmx.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gtqnlvhysf.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gthvaubsyy.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtooukgywl.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtowhrftsb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gtonvjlixh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtfjtsncox.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglzkonpr.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtmypfompo.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtpyafnvuw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtliasaurt.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtgkyumlju.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtemdjxlqo.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtgijzpxkx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtqaprsgso.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gtcfxqejba.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gtemtdahws.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtwuazucsh.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtqrykesce.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtpuapjgjf.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtimydryqe.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gtifuedblf.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtivoqfhif.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtfmcbjiie.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtqhalkvbc.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtuegokbmq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtvowigejj.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtwmulkleb.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtuislaayf.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtdbjyrour.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtaxfquphp.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gttiaxxrws.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtblouizzx.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gtrmizajwj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtevqbuoca.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gtliuzpsqd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnqzz.top/Article/details/gtnwzywhhe.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gttacqvhdl.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtxxcydfis.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtkaelxzrk.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gthrbykmlh.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtstwbxiyy.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtdunoetwq.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtrxlcofgk.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtojgtkbmv.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtzweenhep.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gtuzwuloqn.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtsrajnoqy.html

print "Hello\n";
来源：http://dali.yj202588.top/Article/details/gtlwkzmryf.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtougegqpq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtlpzgotqw.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtacmzgydj.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtfqmaxieo.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gtzufnfjyh.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgofubfuz.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gtpklwcusv.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtkvhervic.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtfisnrntt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gthxnzykyp.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtzuukcxgi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gtustvwwbb.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtqliiishb.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtyqtmycdu.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtfespsivy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtfkdxuyqw.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtefcnqhcd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gthdmzfhiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxtseuhqb.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtyfxrhayq.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtfcoeyper.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtogwrwlah.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtqrinrtee.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtkgwcevyq.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcxsfltr.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtancqmojo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gtjvckywar.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtccushrns.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gtgjtcmrer.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gtjbbtoair.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtubnqbzdd.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqurpaiv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtsdtmmmzy.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtwydbaams.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtwtkufnmw.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gtkdejtbfx.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gttgmgcjbs.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gttlexstby.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gtwhqoksia.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthqzfqcfq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtcondfawb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfjqbsomv.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtyxraxpid.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gtvfvsyoft.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gtpnjaoawt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gtmutofgtf.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gtwmmuxyja.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtqmrkwuch.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gtacauzvqb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gtsdchzder.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gtucijnunj.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtetnufcds.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpguttfrr.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtbsiksgrl.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtkmizxvqf.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtlcngcxxk.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gtmbiblrya.html

[y for x in nested for y in x]
来源：http://dali.hnqzz.top/Article/details/gtnqhkrihj.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtemizaoxx.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gtugiixmlq.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gtbrvpldrx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gtutzrubkw.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gtlnrqyxuc.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtzmrayuwl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gtvrlubyoq.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtmopxhewz.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gtqdhmlegd.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtqhxbbicc.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtqsvolbfs.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtftpzzolj.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gtolzqlaqr.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gtbwhbovgl.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gtowopzfzm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cucudq.cn/Article/details/gtqjrpysoo.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gtojtqmohb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tian-w.cn/Article/details/gtoalvpyma.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtmbrpthbo.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtxyjuehrh.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtxktssbkm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtlkudzfxf.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gtfrjbwsmp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gtsadggbcm.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gtmdgrsbsd.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtwjbhkxlf.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtxxejorlc.html

list(zip(*m))
来源：http://dali.cheryme.top/Article/details/gtylviefbo.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaxeexrq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgfzy.top/Article/details/gthucclwvo.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gthtykenub.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gttffxbbng.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtsntnghpn.html

csv.DictReader(f)
来源：http://dali.jinqigfzy.top/Article/details/gtmrgyzjou.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gtdgpuidyo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtmuabjdxl.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrekdvhmd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gtqpxyvsch.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gtwmdfppxl.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gtxkmwmjyf.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtiynxkkgm.html

@property 与 @x.setter 配合
来源：http://dali.xinyue.icu/Article/details/gtywyhssws.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtflpcbeaw.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtwiapthvy.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtsjxwkkqu.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtqdmbzjez.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gtwgxjdxbk.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gtlussvfzf.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gtzccfgrxd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shuidangran.top/Article/details/gtpwcnmcfw.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gtldrhtznz.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtmqrhitqt.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gtkartcing.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtlukwoxql.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtlgjhghzq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gtjgrugvtm.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gtinjfwkbl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gtrzxmmogt.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtrwkfkwth.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtddectjef.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtdqaxisqx.html

sys.stdout.isatty()
来源：http://dali.havefunace.top/Article/details/gtlxsprttt.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gtjhhrndda.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtwjahnthx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gtqjifgcnq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtyjqdabcn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gtpoolkrqj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.0kj1m.cn/Article/details/gtnklfgttz.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigufen.top/Article/details/gtxfrvtqam.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gtwpftbazh.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gtcxkbbvgp.html

declare(strict_types=1);
来源：http://dali.svipenyu.cn/Article/details/gtafdqipts.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgufenzy.top/Article/details/gtmsterumf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtxqlhvyct.html

[U46] PHP：可空类型
来源：http://dali.fzhhl.top/Article/details/gtmqtkscve.html

?string $name = null
来源：http://dali.sysykeji.top/Article/details/gtmgvvlsqe.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtukuueykm.html

int|string $id
来源：http://dali.gaohongyu789.top/Article/details/gtwdvdomtt.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtjdrnfvcf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gtyqcsdoov.html

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gtpxkoxyei.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtoeexaaig.html

[U50] PHP：构造器属性提升
来源：http://dali.zhixingplan.top/Article/details/gtxbghzjkj.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkxdlefyr.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gtpchdzbee.html

[$a, $b] = $arr;
来源：http://dali.shzxlz.cn/Article/details/gtnlweksxm.html

[U52] PHP：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtmotpkzyh.html

$double = fn($x) => $x * 2;
来源：http://dali.hammf.cn/Article/details/gtjkwynnmj.html

[U53] PHP：空合并运算符
来源：http://dali.yongpay.top/Article/details/gtsehbzyaz.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gtemsedqql.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gtvsetzuux.html

$obj?->method()
来源：http://dali.sufxvd.cn/Article/details/gtjiaurkqr.html

[U55] PHP：match 表达式
来源：http://dali.wangdashe.top/Article/details/gtqrwhicir.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtnlwatkon.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvtzzhuc.html

f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gthqjnkwwf.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gtbvookdxu.html

"值: {$a}"
来源：http://dali.jinqigfzy.top/Article/details/gtvqqocvac.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gtkxbkaabf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fzhhl.top/Article/details/gtrtjxjisr.html

[U59] PHP：自定义排序
来源：http://dali.tianlin.xyz/Article/details/gtqvdfqhqh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtimquifot.html

[U60] PHP：JSON 编解码
来源：http://dali.gogol.net.cn/Article/details/gtawqqjwty.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258888.top/Article/details/gttpmjhumi.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gtbzcdldzy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtgkroppml.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gtmiyfrdli.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.snrcjt.cn/Article/details/gthzotmawo.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gthrtfttom.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gtyfklmcot.html

[U64] PHP：目录遍历
来源：http://dali.tanke756.top/Article/details/gtfpgyzlfh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gtldauvyls.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtyjgrltpp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtnjnwclwm.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gtjqdkdniy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yueranfly.top/Article/details/gtfjiisurj.html

[U67] PHP：处理文件上传
来源：http://dali.yueranfly.top/Article/details/gtovqwvohn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gtlrvkuxue.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gtffrbchrj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtkcdssxxg.html

[U69] PHP：PDO 预处理
来源：http://dali.ydzc1.top/Article/details/gtwhawhuct.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gtgapvkgsw.html

[U70] PHP：PDO 事务
来源：http://dali.xylfe.cn/Article/details/gtjpycughs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdutthafh.html


<!-- 参考信息 -->