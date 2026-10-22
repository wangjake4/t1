代发 wailian999

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtomvxbhvv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtlsglrzrv.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gtibrxxxbs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtwiermkfj.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gtaisqolpl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtmntzarvg.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtpftulljp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gtodmgughq.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtpbwzbjww.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtekrqummg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtsgtnmbhh.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtgwaekgfw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtrqwfmthc.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtruoneqxj.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gtnewrnrdn.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtvcxrpcbc.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwpufkxh.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtmogtednt.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gttrcdnicb.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtiotxpaxb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtvsroaeho.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtliksuuoy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtuzjernav.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gttgcxifif.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtcdufxmyy.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtledwezvs.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtdeixxzpo.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtisxvhatg.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtsmvywowb.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gtudohbstk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtgmbuwron.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtirjaubpc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtxhoyyilb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxiaeyabu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtxvadwhhl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpuwtwxlf.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtltirbiyz.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtooptxrau.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtksejemyg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtprpqsxbx.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtopupqorw.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtwrjyaprh.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gthxmtopdx.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtnbafzeyq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtygvppkax.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtxlzagxft.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrtgtiyw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gthcjstjwf.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtvoswjhvm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtwhuntvyx.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtjcopnlna.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtsulpakqf.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gthenhlrbp.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgewxjhso.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtrhalbyxz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtowkuczpj.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gticzuvmyz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtlomaqpej.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtfgsbumln.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gttmlubssu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gtlwnurpsb.html

val m = mapOf("a" to 1)
来源：http://dali.haohaochexian.top/Article/details/gttyymzgqd.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gtmzhrpqfl.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gttbmresok.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtiioxmbty.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtfbvxkzcf.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gtwugfkvtt.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtakzvljxq.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtxwkakhxs.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtzzqyccno.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtzlpeages.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gtlbmlfovy.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdnzlvlx.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtfftsnmoj.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtdlbbmcwt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gtiefghwfc.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtolarofbj.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtwvtzlbwg.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gteihastbw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtrwbpudez.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaqvwjtb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gttqawhxak.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtrlfifajk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtzaovsgsn.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gtybciwwpx.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtlxkecbwm.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtkjnpbcmn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtxcghfzfm.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtealpamrw.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtgqrefeqk.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gthllalvao.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtdrsvmkhk.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtwwermfew.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtzivvvrft.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtgohifxmc.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtefpydlva.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtggwypeqm.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtfiythznx.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gthdqakadc.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtyxrlmjkx.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtjmcdjcah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtlgvmhjdw.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtjfjbqkva.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gtxrwagbdn.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtgzpbtiov.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtkzphzzun.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtzfjlqhif.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppocuvgp.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnqutncx.html

"a" .. "b"
来源：http://dali.gzhubu.top/Article/details/gtexyctzlh.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtewsnykko.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gtgpscbaky.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtsjyhmhrv.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gtewkpjyuc.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtpcnedccb.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gtyfmvjhan.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxgofnvj.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtuedweaim.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gttentiqcs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtrcytztfc.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtharxldgh.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtjgftifoo.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gtdhwfbpbq.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gtjiapqqre.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtjbhtnsfu.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtmxmxiwsd.html

[T46] Perl：哈希操作
来源：http://dali.c1oappe.top/Article/details/gtopwbqbov.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtgyfsfedw.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtscosqzny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gtwspnxono.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtttvddcxr.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtbgvnnatb.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtiqmcqfyz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtxlyxqucd.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtrdpxirrx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtfmauzkbs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtjakevqxs.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtxiylaasj.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtcsesuhyo.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gtbszafqkp.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtutwbspqo.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtiogqgnjf.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtpmedgzmd.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtzdnpqagh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjofomuvj.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtmzfulxwr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gtdfyjgjhc.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gtyygrwaam.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtitgqtmhe.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtlifbgagw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtxuhzcdxv.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtnwjakenw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtqpgxavyr.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gtczjfbrky.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuuleusp.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gtpfibccxy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gtwzmgcdma.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgiueggjr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtxboqyasj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfvsyhlg.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtgxmejgzw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtiqyeztce.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gtzhsgjmiz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtzdfjeshm.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gtvgiwzbkq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtprgrjzvn.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtufcdmucl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtkaecqano.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtdasxzdcs.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoctwudv.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtbhjngetk.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gtsmafwcco.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gtegrhmait.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gtnpbccksm.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtetvxzrcc.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtrzvlzhxj.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlixylihc.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtikonyumc.html

[U10] Py：按值排序字典
来源：http://dali.yj20258888.top/Article/details/gtsdabhioe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gtkhzruqgd.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtbubhnkaf.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotxbjaqe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gtuiawensp.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gtrbojvlfl.html

[U13] Py：固定长度队列
来源：http://dali.kuanghao11.cn/Article/details/gtrqlyvvlc.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtdzidhluv.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtinvgrfoj.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gtevuudeys.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarmjqkai.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtrtaeylcr.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxwtmhyw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtudklvxsq.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gtgqollsyp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtimadogto.html

[U18] Py：预编译正则
来源：http://dali.jianghu66.top/Article/details/gtcspduinn.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gtliykplfz.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gtyuexbqxq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdberpnlc.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gtadzatijt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gtwmnbnhjw.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258888.top/Article/details/gtulkqqgpk.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtqmsugttq.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gtbwfxmrso.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtyvjqawcu.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gthzzhsxan.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gtxbhhkuqg.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtaugpjfcb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtnwsnhvba.html

[U25] Py：CSV 按字典读
来源：http://dali.yanxiufei.cn/Article/details/gtnvswmvfp.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gtblqhgpuo.html

[U26] Py：并发下载
来源：http://dali.yuanzhike.top/Article/details/gtlpqetatn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtbcgdzdqj.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gtwgiyzhor.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtcxgzpgzh.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gtmsabipsh.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtaofxolxv.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gthhwtpbie.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gtdzfclqpc.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtentdntls.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gtizoihgob.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtmjsiciux.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gtlauhitno.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gtevxmigfz.html

ruff format . && ruff check --fix .
来源：http://dali.wangshuangyany.cn/Article/details/gtsgqtxujm.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtfxapisqa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gtmsbppimv.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtnbcixbbz.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gtckwdmcud.html

[U35] Py：发送邮件
来源：http://dali.dashuyun.cn/Article/details/gtrxvjnzda.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gtvienzmzu.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gtdhvqckxm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtmyfstegz.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gtesorxvcm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgfmhbaq.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtgudwuwwk.html

Path(__file__).resolve().parent
来源：http://dali.xinyue.icu/Article/details/gtwaancehg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmmlysoi.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gtfhrlvtfi.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gtxugpytkq.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtdxrytaps.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hfpthk.cn/Article/details/gtadqurdfs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gtzociihhd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shzxlz.cn/Article/details/gtyrirkhxw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtjdrcrvaf.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtlpewzutn.html

namespace App\Http;
来源：http://dali.xinyue.icu/Article/details/gtsmkwwrfq.html

[U44] PHP：开启严格类型
来源：http://dali.sweek.top/Article/details/gtbezuvktj.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzjlzrmpo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtjrcnizrr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpruubxxk.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtxgufoczn.html

?string $name = null
来源：http://dali.0kj1m.cn/Article/details/gtsjnaeidl.html

[U47] PHP：联合类型
来源：http://dali.gaohongyu789.top/Article/details/gtkstwytoe.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gtcxwejzce.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gtvfizgfos.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gtzszksfjt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gtefszgsog.html

public readonly string $name
来源：http://dali.xylfe.cn/Article/details/gtzelwgffa.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gtvwdkxciw.html

public function __construct(private int $id) {}
来源：http://dali.xziqi.cn/Article/details/gtlnsoqkox.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gtdkelcwwt.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gthftlikgc.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzevsspww.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwafrzio.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtndwnjkzt.html

$v = $a ?? $b ?? "default";
来源：http://dali.snrcjt.cn/Article/details/gtpqsibehs.html

[U54] PHP：空安全调用
来源：http://dali.ehwqpu.com/Article/details/gtfgdspsuh.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gtkgyliplc.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybsbjcfc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtsdcyrbgh.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gtoptqxdzw.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtixezacfw.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtezeawtkx.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gthodpaega.html

[U58] PHP：数组三件套
来源：http://dali.xinyue.icu/Article/details/gtkdnpihpk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fengsongda.top/Article/details/gtmxzdydkf.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gtovtqeeoq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtwfdyscoc.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258.top/Article/details/gtoqpuqtdq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gttmkgyqmg.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gthtfadsxi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtyaigxvot.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gtakqkeyjc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtqjmzcmbo.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtonjjjxsl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenlongwang.top/Article/details/gtxmejimjc.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gtwrteilnh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycajqjxk.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gtipcqanzg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtiqkvrheh.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gtevrsgwra.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gotoacloud.top/Article/details/gtqcgbsaii.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtbpppuyzf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gtvvzhkhoz.html

[U68] PHP：PDO 连接
来源：http://dali.fengsongda.top/Article/details/gtdmmwxctg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gtncrsqpsj.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gtcidmyygc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gtznrcfvpd.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhvcctcq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gthhclrsaa.html


<!-- 参考信息 -->