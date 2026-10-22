代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwufybfqu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gtamexpyaf.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsqfaryh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtlrcnwugh.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtnyfzvqfc.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtrnspihtg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtowhvrpqq.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtjoefzbqw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtqclnaqeg.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtoollcspc.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtvughymxz.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtuxzsbgcp.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtodpztdhe.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtjcnqxmpw.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtnoywiqji.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtpfhmwnlg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtfkwiuwyq.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtrxuwjrcu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtgncsfxlx.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gtmawidjjp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtsbhmqevs.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gthdcttvpq.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtsqavmibk.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtsaqhqxpa.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtwenhluhu.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvnwpknh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtrujrqeka.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdrdpjtk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuopgbnb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttxrpasaj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtycppqhml.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbhskoly.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtdgszrneo.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtdhiluoxm.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtgrgeovca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtfjtopany.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtdkszjwwu.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtpekavezl.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtzajrusqw.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gtpfihqyau.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtsdomzegm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtrqoghadm.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtwahgvqel.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtezhchffz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqvcsztb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtmgwugqfp.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtmjywynhw.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtgikeklhx.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtwpefrftu.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzgtbflj.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtugtftfzr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtbxcvqzwj.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gtbnfacqut.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtvmuhahjn.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtkeivqanr.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtatvenqxz.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtgqfodjuz.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtdonzfbhp.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtlnrbigae.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtgswqbode.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpubcoqyc.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gtwsnsuksx.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtkpintxzs.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtxxeyrhxi.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtfyucjmfq.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtcfsgdfdr.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtktszalit.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtlsqqcaar.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtxwhlneqh.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtrytxgktd.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtafdvxosf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtmgidbrsj.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfizlicmi.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtkuzvkvay.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtwiozltqr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtqpureddg.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gttydspabk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtuqtqtwom.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gttczsoksn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtenimqxxt.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtrmsbfoev.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtgkyigalt.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtfcjbmamm.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtlndpwofn.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtcyaprlop.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtnhqwaakm.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gtvpinnpxs.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtguxzuxkq.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtzpipkmhl.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtliraskjq.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtmnwchwul.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtxcedtknd.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtzafkgylg.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtqlftdykn.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtdeyjmbxc.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtfcwphzyw.html

[T33] Lua：表（数组）
来源：http://dali.wangdashe.top/Article/details/gtmzhothvz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gthaflmdkj.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gtdvhgxjma.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtdaajhypq.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gtffjwlplb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtfedgvvnk.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gtarodfkdg.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtdzqutlfi.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gtipwysgwt.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtltzqvjhp.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gtmswlmncr.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtdymmqdlo.html

[T39] Lua：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtdvasxmtn.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtddvpyoxe.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gtujepurlm.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtyjzqrpnn.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtzncazkti.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtffgffajp.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnzgskjde.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtzhxmxhui.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtkfemximr.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjdkwrdo.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gtaxeyuuvs.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtdwravjmp.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtsofwmjml.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gtqvvzktwa.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtiqzcwxpk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtpjrwgdfl.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gthhqzmdmz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gthkponlpq.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtxloiwndz.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtiwcsgehg.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gtetbcbzjq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtejclsfho.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtapcfchhm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nwbrower.top/Article/details/gtsveppcpj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gtvhzlwzvb.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gttzoklyuw.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtypcjpahy.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gttppjldmx.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtckwpddxh.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gttsnlvxxw.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtoikaeiwh.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtavgjdktk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtdxpulbie.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtouqcpqfv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gtyphubxcq.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtzmocheey.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtzgpowucr.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtiyhwmgyg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtjwladhhf.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtbztdhyby.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtuifxxutb.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtprsbaxgw.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtrleokvda.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtiytjjclw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtifpjodul.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrnxjrtjj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtkujsenvw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtykpgcgxa.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtqpqydrlo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gtggmcpftk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtgszkfand.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtqxumxdln.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtjctpamxk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gtyljawjxc.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gtzfjqddit.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gtfrbpupoo.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gtwdgnoxdh.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtmumvkpun.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gtxpxboihc.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gtzucidcon.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gthgpijlfp.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gthzqgfejv.html

[U08] Py：展平二维列表
来源：http://dali.sweek.top/Article/details/gtqvcjaumg.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtahvbtgnu.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gtgvuetklg.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtvatzyqqr.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtzjetfjsv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gtcuubhizc.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gteauzluag.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gtzvsxrrvz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gteuzlhczc.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtudqedzgu.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtcjeccfjo.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcmzepud.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gtljzktihf.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtarsuipdh.html

[U15] Py：高精度计时
来源：http://dali.fengsongda.top/Article/details/gtlqsdmtzn.html

t = time.perf_counter()
来源：http://dali.yj20258.top/Article/details/gtmfuaxfob.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjnggehz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gtowlnxcqs.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gtpiqcwzeo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtfbmhfnlw.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gtsjzpgfzb.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtuoahyokb.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gtsgucrjxe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gtyzukcphc.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gtdyqmrree.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sweek.top/Article/details/gtsnfzvsog.html

[U21] Py：自定义上下文管理器
来源：http://dali.xinyue.icu/Article/details/gtmcvtevws.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gtxhubhegc.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtvedcasbv.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtcwfmkgsb.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gtpqjgwwpz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtprohdnxg.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtqilafdmb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtprmucbgs.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtocwxncow.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gtepobrmpy.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gttscrwzog.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiiyaqot.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gtfewtmzgx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gttdfbnqex.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gtlnmfqkil.html

UserId = int
来源：http://dali.zhoulong.xyz/Article/details/gtpocuphpj.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtkrfjxehr.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gtfgnohecw.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gtiihgwpzz.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtbpsjkusz.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gtbqempsmn.html

python -m pytest -q
来源：http://dali.xinyue.icu/Article/details/gtamtnqfjf.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gtqhooedpo.html

ruff format . && ruff check --fix .
来源：http://dali.gogol.net.cn/Article/details/gtewhxmwjw.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gtyeimzjxa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gtgzmfkvyx.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gtmcqzndjg.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtnpcjzonb.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtgwdegunh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gtghwaddpy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtsdjctefw.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gtwldisoyy.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtgoibcgwb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyvsjarq.html

[U38] Py：获取脚本所在目录
来源：http://dali.jyoumei.cn/Article/details/gtncpqvowq.html

Path(__file__).resolve().parent
来源：http://dali.chenzaomai.com/Article/details/gtdiyabejt.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gtyoyhdooc.html

sys.stdout.isatty()
来源：http://dali.redwolf501.top/Article/details/gterjebpox.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gtxpiskidn.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtotexuemd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gtpnegrrlh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gtlbwunitz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgfzy.top/Article/details/gtdemxdpfr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.quarkkingdee.top/Article/details/gtopdblhzs.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtkklpsaam.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gtjtlqptnu.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gtyuhhxuva.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gtgteqznkq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj202588.top/Article/details/gtopnpkdzi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gthydcmugs.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gtddcfmwaj.html

?string $name = null
来源：http://dali.cheryme.top/Article/details/gtrivkxvpl.html

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gtmsffjplw.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gtrkaswhkx.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtxfnwgahu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gtelsakghd.html

[U49] PHP：只读属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gthencnbhn.html

public readonly string $name
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlqsssap.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtvfphsawn.html

public function __construct(private int $id) {}
来源：http://dali.xziqi.cn/Article/details/gtmghfpsrf.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gtwozouldz.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gtirmcjhmy.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtvqdekarq.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtishenmxn.html

[U53] PHP：空合并运算符
来源：http://dali.hnxiangtu.top/Article/details/gtnqlsgjfx.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gtyazqkaug.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gtzbcfrrdt.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gtvmemnszx.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gtnfdevqmh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuobblgfk.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtfxvnzyzo.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlrvodppl.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtaddmjtxo.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gthemjqqcf.html

[U58] PHP：数组三件套
来源：http://dali.cqqwz.cn/Article/details/gtmqihfmtl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtfcvcpdli.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtnhbxaayl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtyhgwrfof.html

[U60] PHP：JSON 编解码
来源：http://dali.sysykeji.top/Article/details/gtobtuqsxy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fzhhl.top/Article/details/gtsjuqizur.html

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gtsogbfzqu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtjjeiruke.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gtkzybxcbu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenzaomai.com/Article/details/gtlcutimnv.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtlydgkqde.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.kuanghao11.cn/Article/details/gtpfoamomu.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gtuqqjpanr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtussnfyex.html

[U65] PHP：会话
来源：http://dali.zycfv.cn/Article/details/gtkviuovvw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtdvbacrjk.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gtnyfwueop.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gtrshicswo.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gtwpihqxsr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.mhx1999.top/Article/details/gtrunhctxx.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gtuolkaukh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtqhojparq.html

[U69] PHP：PDO 预处理
来源：http://dali.jyoumei.cn/Article/details/gtuflniwpt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jianghu66.top/Article/details/gtujhacizk.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigfzy.top/Article/details/gtibiqsfwg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gtjvvetcnh.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtdtdjfcmw.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gtnaxgtpai.html

[U72] PHP：写错误日志
来源：http://dali.havefunace.top/Article/details/gtjwknxpwx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gtftkitjxp.html


<!-- 参考信息 -->