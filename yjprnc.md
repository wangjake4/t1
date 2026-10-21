代发 wailian999

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtyaiiugzi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtygdxuxph.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtkxdtceba.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtnazjgtbd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtceuzzano.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzmpdzpnx.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtqoozabbt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtrgnhajer.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtpcsnwkeq.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtxjfndgsj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtjyessole.html

[S50] C++：格式化数字
来源：http://dali.fengsongda.top/Article/details/gtlpvjshvp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtddcwnlts.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgkmhsjx.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtnbklqtxy.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtxjochmnn.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtqlhiszoi.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gteyinsbcj.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gtpnvtprmz.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtywrypunw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtbhfsklct.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtvrcarbef.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gteuswnfjw.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtftltmiwe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtzzqokcgv.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtxcetwxxg.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtbrlbvfrl.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtxzpmtewz.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtgsmamwvx.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtbgwgqqaz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtfqlcomck.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gthftqspxs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtvngdjstx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlfxsahux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtqcgqkocg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtijuqhkaw.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtupujfhbr.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtajtfulxz.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtjrrdjiav.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtudmyukwc.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtogexrroh.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gteixhrwus.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtwqqwxdnv.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtrfqdqwts.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtfwmhicgf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gtgoqvjyyd.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtyghpkcyg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtzwnlsxce.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtqzobxzrv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtnicgbtwu.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtpqdrezyq.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtermeckvu.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtlxkwqton.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtyfcknnsq.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoivevsi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gtnfkbltie.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gtlrnrakgf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtjqxxqhaa.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtashfmxvn.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtdtwbaity.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtmuhmvzpw.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gtjvvshnpv.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtwuhklyvu.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gthilrtgji.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtfjzypzvw.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtaxtmopar.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtaxqvorkq.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtoamtqxby.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtojyrqueg.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtrgzqrmsr.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtbzurpkpr.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gtlanaknde.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtoumgbzvq.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gtpzgngexc.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gthzjbnutn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtcrlfpbzh.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtvwntbwdo.html

for x in a { print(x) }
来源：http://dali.daria6918.cn/Article/details/gtvvuystfz.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtxeioovgj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtgegotewq.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtaafsgqip.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gtkhxnnxtq.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtnrixuihq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gttspboktm.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtykezpjgp.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gtraxsrood.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gtruvcvelx.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtpmkeusdj.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtboypmlfb.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtbrvqmjjc.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gtmtrafbnb.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtvulwpyye.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtbftkxodv.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtpmawpkjf.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtowrgaflc.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtqhewzzho.html

[T31] Lua：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtowycjuhc.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gttthpcapk.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtyyekiyki.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gttbxrldav.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtuydemdhf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtksiehhyl.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtaxlykhsd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtgnoiadak.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtnrdwbnvp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyynxnxyz.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtcprmimks.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtovwotitm.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtcyvvowzs.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gtvjmuioma.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtzyhrrhlv.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtvyrbwzcx.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtnlhkpolv.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtjlfdrxoh.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gtdjxrttfb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtcytuftie.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcndmzbg.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmveblnq.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthufyduqg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtstyjlpob.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtnagmsmpv.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtvvlluerc.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtbgcjixfl.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gtytoswaht.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtnbaasvsw.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gtegqnugkg.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtzzpvfswo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtqzlbtguo.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gtrqzdivyl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtwqpkrckd.html

[T48] Perl：正则替换
来源：http://dali.meibo888.top/Article/details/gtachigwix.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtnoocfbtv.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gtmazqrrzg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtcyhzrgzy.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtddnntwxg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gtphlmktxn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtyxtjrhtu.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtsndqbfmx.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtteedkdlj.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtkpadshqd.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtxbztduui.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtijmhbibv.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtzbqsxbul.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtcuucphpa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtyslwmpne.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtfarpnjwc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtrubsgrmr.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gtmorbvotg.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtamxsgdpr.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtbpekmjag.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtxvnyyxau.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gtleooxyvo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gthbundqzu.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gtqrravjfa.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtvtbwnpuw.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gtfzyimezx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gtesdvgbyv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbfucusxx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtytotgyvp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnckhtdzy.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gtrjmjfyzt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvvlhjcf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtxxbyepty.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtbrpvbevj.html

[U03] Py：加载 .env 配置
来源：http://dali.pycfn.com/Article/details/gtmsbbbiqb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtxyfvgqvf.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gtgkobgpsh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gtgfxxbeht.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gtqvccwjgh.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtbkujjxys.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyouanxd.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gttefsnoro.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gtuaehxgbd.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gtudionmrx.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtqrjuswsk.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtidgoddee.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gtchhoojkv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtdytigbih.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gthsumtvse.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gogol.net.cn/Article/details/gtjgtistbh.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gtezavkrpm.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtktbshkeq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtmkkgccax.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtxysluiny.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpppsfddq.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtzsioxumv.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtswtebamo.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gttavqoabr.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtykybpcqr.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gthhafneuh.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gttxdqtbny.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gtfuroggel.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtmpdgflcj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gtxcewqdwt.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gtrtlwrrof.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gtcixcjfkq.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gtjakwyriu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gtvmkdttbm.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtcggmgvzj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gtgatbwnuh.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gtpcxivhsh.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtdbgczzwf.html

[U22] Py：矩阵转置
来源：http://dali.quarkkingdee.top/Article/details/gtwmtkttsj.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gteilquamp.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtrasriufo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtgqbgmlsx.html

[U24] Py：路径操作
来源：http://dali.yj20258888.top/Article/details/gtlyoonpco.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtwkyvhjfn.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtfowgdtwd.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxezbpwev.html

[U26] Py：并发下载
来源：http://dali.redwolf501.top/Article/details/gtlsgwubar.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gtcthemyim.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtotrscnqj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrbcyzhl.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtldwhrbkx.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtblgrhqlu.html

[U29] Py：属性校验
来源：http://dali.birdmap.top/Article/details/gtwogcbcta.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gtreduiday.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwvazdup.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtcmhmypfx.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gtjvmuytyc.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gthcpvgmke.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtdifncasg.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gtayvimfmz.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gtzhvwxilp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gtwujqikdh.html

[U34] Py：判断编码
来源：http://dali.shangyingyoupin.top/Article/details/gtzoyuuhgo.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gtqqlscsqw.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gtdfcfsgna.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gtifngfavl.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtsbqcenqt.html

schedule.every(10).minutes.do(job)
来源：http://dali.tanke756.top/Article/details/gtwtqiqitm.html

[U37] Py：读写 Excel
来源：http://dali.hfpthk.cn/Article/details/gttpvwunje.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdqwpxgl.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtgbtvhqgd.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gtwhivhfoh.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenzaomai.com/Article/details/gtemnrqlnh.html

sys.stdout.isatty()
来源：http://dali.yuxming.cn/Article/details/gtmoaryuih.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gtiygpribj.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gteufndfkr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gtbtgitwoq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtucvlsplo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggjctwkl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gtudcziusg.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigufen.top/Article/details/gtiuwkznoq.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtblptzpud.html

[U44] PHP：开启严格类型
来源：http://dali.nanxinkj.top/Article/details/gtidzheobz.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gtrqnrvtqm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pycfn.com/Article/details/gtjkpzmbkk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyjjvnynq.html

[U46] PHP：可空类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjfcpmowp.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gtuzjskaxw.html

[U47] PHP：联合类型
来源：http://dali.yj20258.top/Article/details/gtvoplxspq.html

int|string $id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxomkbul.html

[U48] PHP：纯枚举
来源：http://dali.sweek.top/Article/details/gtltixubyd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtophrfifk.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gtdxusgygu.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbdxyyfh.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gtcnshjqxv.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gtpfckpawc.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtwzjrbjtc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gtyxzqnzvv.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gtohsfpznw.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpjmemdc.html

[U53] PHP：空合并运算符
来源：http://dali.xuanzx.com/Article/details/gtpgktshpu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gtxtgqcrtx.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gttpqtolfj.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gtydmdalzx.html

[U55] PHP：match 表达式
来源：http://dali.birdmap.top/Article/details/gtbdbcnpyo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtunwcjwrn.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gthwbebsvd.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gthvrnjknd.html

[U57] PHP：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtrlpeuesi.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtkjeglgve.html

[U58] PHP：数组三件套
来源：http://dali.bjfxy.top/Article/details/gtwqhkhldm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gtldncodoj.html

[U59] PHP：自定义排序
来源：http://dali.cheryme.top/Article/details/gtlubemxcz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtlwenvqax.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gterflqsjx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.kuanghao11.cn/Article/details/gthvzyngmh.html

[U61] PHP：正则
来源：http://dali.chenzaomai.com/Article/details/gtbpawluon.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtnodaehbs.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtffyxmiub.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvljgpgxm.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gtozizebcr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gthggbotmt.html

[U64] PHP：目录遍历
来源：http://dali.ivvv.top/Article/details/gtiuugiqxk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gtbsmwkvmr.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gtaxleteyq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtsparbmob.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gtyvtkwjsu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtuwtwcndx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtuxorydbs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.mhx1999.top/Article/details/gtomlnogvg.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtghkyihsk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.birdmap.top/Article/details/gttvjiumrk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhengqikj.top/Article/details/gtjnginsiy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.haohaochexian.top/Article/details/gtzvmqqzcz.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gtbcirciry.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsqbkfht.html


<!-- 参考信息 -->