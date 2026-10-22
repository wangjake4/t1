代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtxterhdrd.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtzmqvjksp.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtuzkqrsib.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtgxwsiqmr.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtpavhoxej.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtkuuctcts.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtjrxyvsza.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gtwulfdfus.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtjporuzfa.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtfhftdgas.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtzqyfwdes.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtlhykrnga.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtpohvoymq.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtkvoppwfc.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtrymzrfub.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gtoishifua.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtvzwuudru.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtrxzcummk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtvjojwyfz.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfrqnphr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtqrfrwlkf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmrfqumyo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtoplbhonh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjbquljyr.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtlddrxuko.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtyzoosubi.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtajbdncoj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtnbwhrqpp.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtuhanymwp.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtexuijpqh.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gtmvzponfa.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtjexnulwo.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtvxgispsk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtyangdody.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtwaimuscw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtkyjahqjy.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gtnrzbutxt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtuaijngbq.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtpsjhfhwu.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtljmdicrw.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtemvtwsfj.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtsvvclssw.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gteyayvsot.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gttxjsnuln.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gthffhfkir.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtechhwsuu.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtezuxxram.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtuamiaiwc.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtfwcoqtbl.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtebtlqfnf.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gthjkrnolb.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtfzzjylxc.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtfzaxybnj.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtqwmbaszg.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtsingwxex.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtvmquwous.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtciqjbsep.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtspmuacif.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtyfagamdq.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtowcgcdag.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtgugfghfh.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtbidkgsso.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtpjgnvfvu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbwmmfvy.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gthpsdnmue.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtarpijqzp.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtkcmdpmaz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtqudyqfcr.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtqgvhlwvq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtvchhlpyz.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtyslxoidr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtodwqvoye.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtqirmydpu.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gtngsdrhmp.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtuxcoioad.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gttnzjnpnp.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gtwiihqvnv.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtgfreakwh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtkyqccnby.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfatwoka.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtutwprcul.html

guard let x = opt else { return }
来源：http://dali.chenzaomai.com/Article/details/gtjqldluzj.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtlueakqvr.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtyqafclym.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtmfrkldkb.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtvgjrttfb.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlrhbpni.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtehvrpsvd.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtcqflspdc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gtdrvzksoo.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtyfnsfleo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gtlowvgyjj.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gteashxven.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtvaqoiyet.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gtiqefubzp.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtesnensvn.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gthznxewoe.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gtwuzixsxf.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gtqftammes.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtrjqisrya.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtdtzpdkks.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeewbsof.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtblopzzer.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gtlwrtedmy.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfxtyqgc.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtpqtonxxh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gthqmzlgkf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqeqfeqn.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtxtzgtrud.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gttvzwjrzj.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtazxhcymo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtmzqrotkq.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gtwpjyijyf.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtjpsgysnq.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtcbhsrqik.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtwxtyvbky.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtjdsecvji.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gtfpvcujbg.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtyzifvoqj.html

$s =~ s/old/new/g;
来源：http://dali.pycfn.com/Article/details/gtsimrxajg.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gthrwkdwmj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtnxcwazby.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtbmtpxuaa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gttjnihjxk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gtjrxbonnr.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gtqfjvotce.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtovhyvinm.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gtcgnkbmxu.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gtrykgqwln.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxsmsukh.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtamvxhuda.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gthgyqrdtv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtltmgxjlj.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gtccmpskrg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gtonqkmdav.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gtxubqwgnp.html

case class User(name: String, age: Int)
来源：http://dali.yj20258.top/Article/details/gtgyjipbae.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtzorwfrat.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gtbvhhmgin.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gtyufxdmao.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtxyaqemwu.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtnzsttqlc.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gtlwwinvyl.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtrzmywnnr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gttvanlhou.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpdhrzfry.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtvryutikd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxsslaxtb.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskkmqgjp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpfwotee.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gtcnyskobc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtjmdhbkrb.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gtiilieglv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefubhyeg.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtnpjcxdnm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gtwcblhzcd.html

[U05] Py：列表去重且保序
来源：http://dali.hnxiangtu.top/Article/details/gthturjplf.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtcxxfmxap.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gthzhlkbsy.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gtulqyqhsq.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gtkkgrzdvj.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gteckjjqud.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtmgorbryu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtylyiauph.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gtpfwwcfae.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gtcnwnkpnw.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtqcsnjuxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtvvframgv.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtprfivzkh.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtocxmrcpc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtqjdcgnli.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtpwzfcymp.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gthqwmczkz.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtlzadneqc.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gtxicpwcja.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtydrnjkzb.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gtumgyrhmv.html

t = time.perf_counter()
来源：http://dali.nwbrower.top/Article/details/gtqdgpnfnm.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtumogbivc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtfwtsyeez.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gttstkggog.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gtfmzoedmt.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gtbllxovcv.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gtmasjxhyp.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gtwsgkcivw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gtnqenfjkr.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtxyvvalwv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtirfztibv.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtozhjhvan.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gtzieibdfq.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtigtvuvff.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtbekhcdye.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gtkilnquhp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gtuphmsrjc.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtboeutkhy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtlpvgwsdb.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gtalpemflx.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtmwkvqspm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gtovynmqde.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gtikcsjtxf.html

[U27] Py：异步 HTTP
来源：http://dali.hywenlv.cn/Article/details/gtlkwgsvxk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtyrhsetam.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtgjkbvsqr.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gtrfmdjtkp.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtkzqfwhwh.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtnzymvahj.html

[U30] Py：数据类
来源：http://dali.shuidangran.top/Article/details/gtprwmmrju.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhtxjcsm.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtskkzppaz.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzurlmgb.html

[U32] Py：代码格式化
来源：http://dali.sufxvd.cn/Article/details/gtilvjivkz.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gtpljltmnb.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gtabxdgeul.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtuujyfdzn.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gttsgbfdbc.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtfilsdmya.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gtwvbswogb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zdqjudy.top/Article/details/gtxjhckcmk.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gtaztlkpes.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gtaalyoohx.html

[U37] Py：读写 Excel
来源：http://dali.yj202588.top/Article/details/gtadirewym.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gtdbouwqec.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gtmxzfcfot.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtwznlfjwv.html

[U39] Py：判断是否在交互环境
来源：http://dali.vqdsnc.cn/Article/details/gtmzykqtuv.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gtepfacalq.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gtzqbvbpzk.html

print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtffssmjed.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtbiibgzdz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gtsgrkvvyg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.9152youxi.cn/Article/details/gtdrkbntbd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtehewynun.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtdxxhiwoj.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gtmgctaoxf.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gtawwfmpoj.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gthtfybcms.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gtjmghpsex.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtxrwhbyny.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gtitgehrle.html

?string $name = null
来源：http://dali.zhiwuduotai.top/Article/details/gtpiokbsbu.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gthbyfezem.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gtmaghvxdz.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gticoheelr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gtnxibzbsf.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtgacuqzme.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtsqrbxjan.html

[U50] PHP：构造器属性提升
来源：http://dali.hywenlv.cn/Article/details/gtpxfyausv.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtzkoulzgg.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gttgpkualm.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtqgryhzme.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtclththey.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtibxmuovv.html

[U53] PHP：空合并运算符
来源：http://dali.gzhubu.top/Article/details/gtmbnkclxt.html

$v = $a ?? $b ?? "default";
来源：http://dali.mhx1999.top/Article/details/gtecdxmcxm.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gtyekorqth.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtopzfzyot.html

[U55] PHP：match 表达式
来源：http://dali.tianlin.xyz/Article/details/gtrhihwusa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtqntsudsg.html

[U56] PHP：命名参数
来源：http://dali.smart0.xyz/Article/details/gtajxmmwna.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtegevxgmv.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtfukvpdes.html

"值: {$a}"
来源：http://dali.ivvv.top/Article/details/gtxejcevzo.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gtynxpvtai.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtwsaokywh.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gtquyyeyaz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtqyowdzdb.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gttuzprrnb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gthdytcrpv.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gthafmzsuv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrmyerqs.html

[U62] PHP：日期对象
来源：http://dali.sufxvd.cn/Article/details/gtjzdnxarb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtnuoqrrmn.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtlymcorsq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gtqrwwvals.html

[U64] PHP：目录遍历
来源：http://dali.chenzaomai.com/Article/details/gtdcibdfti.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yvedp.cn/Article/details/gtqakcyesq.html

[U65] PHP：会话
来源：http://dali.iojbl.cn/Article/details/gtjpxdboru.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtruljereh.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gtquwqlqdn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zdqjudy.top/Article/details/gtutnmjqxg.html

[U67] PHP：处理文件上传
来源：http://dali.redwolf501.top/Article/details/gtprswhfeu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jiagoushi.top/Article/details/gtybqjykbg.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gtwvosunws.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtjoculojb.html

[U69] PHP：PDO 预处理
来源：http://dali.ybcxt.top/Article/details/gtkqqrvwyp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gtbqqvwwdz.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrxprsdx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjdwvgot.html

[U71] PHP：抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtfncgodnl.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gtlyemdnql.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtonmcusfq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gzhubu.top/Article/details/gtxxyonmjn.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gtqzdqoorg.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtnqrbbetr.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtagmcrdqi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtserfovif.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtixkjgwha.html

composer require psr/container
来源：http://dali.vqdsnc.cn/Article/details/gtkpimjkuz.html

[U76] PHP：简单路由
来源：http://dali.havefunace.top/Article/details/gtsuyymthr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gtkahydqie.html


<!-- 参考信息 -->