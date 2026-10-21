代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtpbfnjfmr.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gtcesxiqnp.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtfkttrrtt.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gthajslrsv.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtjjjywbzd.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtsnlhyhym.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtyzshbkfq.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtlxfxnsfw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtafgyfhyn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtstrplfsk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtoovbadhq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtavzzbiwg.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtrslbirdg.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtqacwqcsk.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtlitygrnx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtzozxklhn.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtsstxgdhm.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtozhwxlnr.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtcuqdqphi.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtnnkhgatu.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtsgihsgyx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtizdqevux.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtzmuamvdh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtzyhcfjvg.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtlqmqojqf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtxicpvjpw.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtmcjmzbak.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtypbntheo.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtixiamwvs.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtdgdlungp.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtdhpzgeus.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtzbuwpmls.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtfgvgrchq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtgyahhxeb.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gthrmszidb.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gttazmrxii.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtmyufcdad.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gteebiwwmp.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtehdtawki.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtncridyvc.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gttgzmexgy.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtuecrdvyu.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtntrjbmdt.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtsepywgnd.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gteqefedrw.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtbafjqidn.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtqjqaxhso.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gtuzyuwfsk.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtdiflusik.html

if let n = opt { print(n) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxrdmfet.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtndnemwxd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtcvaceiak.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gttqmsdtsk.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gtlxzdghae.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gteooxwnye.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gtnisnjxbz.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gthmomrbpm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtbtvmqsnw.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gtiycyostp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtzgafuqjb.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gtdmfnhcrg.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtnnsbjwkr.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtdwwpsspz.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gtajhrebsq.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtaurjzaqc.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gtbbckowdv.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtknylysov.html

enum Color { case red, green }
来源：http://dali.hammf.cn/Article/details/gtdzcsluuk.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtvcxijodm.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtywytjxls.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gttbcraxpn.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtxmhvljmo.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwueqwnh.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtihlycgjp.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtltobbxvz.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gttjolwnpq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gtyvfixoec.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gtywefmwtv.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtrcqrabkh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbyesuuz.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtprqdowph.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtrugotcvw.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtpnjfldqo.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtpkorwlri.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gteweaqsag.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gtodnqrpvy.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gtcbsucmns.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gteljskwje.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtoyyoebmx.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtnmqoiwog.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtubcocedf.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtlwcwdnsq.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtsyebsbsj.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtklsgmjao.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gtfbndlzpq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gtmgbrcycx.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtpwgcxjby.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gtcsghnwtt.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtgyvarxfw.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxazsrwaz.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtmqqgzjqp.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtsqvachis.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtmwaymenf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtkqddcrxo.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gtidiapmjg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflzfhbei.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtfzxmwlry.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtztipwjez.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gtkzupyrhw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtqwgtkzyr.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtevkplujt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtiymnumxj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gtvdalyigr.html

[T51] Scala：Hello World
来源：http://dali.meibo888.top/Article/details/gtxjrxbhjd.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtmlqzwfrg.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtxpucmbsa.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gtebmrzyzv.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtsmgyhoee.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtjbbfuyyf.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gtgesnpdsd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jiagoushi.top/Article/details/gtjtwaqmdv.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtikhluiev.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gttradwyyr.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtgrsqxmsc.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtihwefabt.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtxpiraugk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gtofagyiqk.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtwgezqizr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gtiwzdopix.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtqhrviegv.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gtnrxajabz.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtpfmfsbko.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtctelkwra.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtetioxoaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtdngzqstj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvfgpydpx.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtynurdxkh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtwthuglry.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtiolgmctf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtvnffggtl.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrdnkyei.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtsiqndfav.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtcqwhrzii.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfgmrdut.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gtthjkmgym.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gthpqbzeeq.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gtwqclfrkr.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gtlviqvqlu.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksphbhkh.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gtawrckqov.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gtremjlryl.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gtkprqjgbp.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtjzpkrfod.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtwfyntkax.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtmdnesb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gtecajisse.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtfmztdhlo.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmaxobynh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtzzccobva.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gtiuttmodx.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtvxlfebmh.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gthzcoaxiq.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtvzexbdfz.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtvlrzabbt.html

[U15] Py：高精度计时
来源：http://dali.pycfn.com/Article/details/gtjzblbeau.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gtvjaskpqh.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtirlutwdp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gtnvczfqfl.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtdqovppij.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gtpahcezlc.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gtpcefetca.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtlmfymjty.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtoxeprvar.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivlpbhwh.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtilzggxbb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtzdjmmuam.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gtrlfinhwv.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gtajqugupj.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslrlajsh.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtsfahrojl.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwlvobgrd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhixingplan.top/Article/details/gtgrmkehcd.html

[U24] Py：路径操作
来源：http://dali.shangyingyoupin.top/Article/details/gttabsofbu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtdoysegzt.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gtpztaeehz.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gtxnjtnqkw.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gtkflbffxp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gthvymtonk.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gtojbswapi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtbquleafo.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gtwnzptbay.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtxdxtxwqq.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gtqlukpzth.html

@property 与 @x.setter 配合
来源：http://dali.ppjwa.cn/Article/details/gthdlyjiyw.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gthpyyboxv.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gtcvnerlri.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gtrzkvfzya.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gtmawvqkni.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gtqzabrkfz.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtwalchlwa.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtwmidbbfv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gtmabryaba.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtgmnqilhj.html

chardet.detect(raw)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjpjaoxi.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gtjgnpawbs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dianchejie.cn/Article/details/gtjtftyuql.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtkwdawnja.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gthoolsrya.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtvmkypjhh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.feifeiyinyue.top/Article/details/gtyqgyqure.html

[U38] Py：获取脚本所在目录
来源：http://dali.iojbl.cn/Article/details/gtqbazesmz.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gtzwpksvdh.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gtiybjwqmk.html

sys.stdout.isatty()
来源：http://dali.havefunace.top/Article/details/gtnnzihloq.html

[U40] Py：打印到标准错误
来源：http://dali.hnxiangtu.top/Article/details/gtqigjrnhb.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtftzxmwmc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.mhx1999.top/Article/details/gtyvofsyto.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dashuyun.cn/Article/details/gtzgrhnwmd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yangfankeji.com/Article/details/gtwjixhkbx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbkyyypy.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gttecrivly.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gtpiqrltob.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtcfxzeple.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gtxoqogbpy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gtclnkogfn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqwrcrqp.html

[U46] PHP：可空类型
来源：http://dali.316326.xyz/Article/details/gthmaywbvk.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gtjleeatof.html

[U47] PHP：联合类型
来源：http://dali.vqdsnc.cn/Article/details/gtjtnbchbx.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtlrhdxmnh.html

[U48] PHP：纯枚举
来源：http://dali.jiagoushi.top/Article/details/gtnsyckete.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtjcpxgfut.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gtqwtvjqkz.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gtgvrqudas.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gtunhkyqzi.html

public function __construct(private int $id) {}
来源：http://dali.cashguo.top/Article/details/gtmftadozf.html

[U51] PHP：数组解构
来源：http://dali.shuidangran.top/Article/details/gtblymcpnb.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gtdfqzqlvm.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtdkmjfqwz.html

$double = fn($x) => $x * 2;
来源：http://dali.xuanzx.com/Article/details/gtqxgunloc.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gtdxqtizvr.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gtbfywrdwu.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtrfwshmfk.html

$obj?->method()
来源：http://dali.zycfv.cn/Article/details/gtbrgvfbtq.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gtovgawmnf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtwvitophl.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtadaysggv.html

f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gthpuqfyej.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtqphcfiao.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gtqyogtbgv.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtmvevcgzg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guannengcc.top/Article/details/gtqjxfugcf.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtdotactnt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtyqgdgozk.html

[U60] PHP：JSON 编解码
来源：http://dali.yongpay.top/Article/details/gtmwodfotr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.svipenyu.cn/Article/details/gtihyyxfho.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtejywfqal.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtixijoivg.html

[U62] PHP：日期对象
来源：http://dali.jianghu66.top/Article/details/gtmavpwarm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtobjwhsif.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gtudmfomlw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gtlbmpedsp.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gtympkeaju.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pycfn.com/Article/details/gtggnxzkpa.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gtgiwxnkvp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtwhwtdphb.html

[U66] PHP：设置 Cookie
来源：http://dali.yueranfly.top/Article/details/gtozjhqlie.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sxryk.cn/Article/details/gtlqbxjlpm.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gtjyooxhcv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aibaodan.cn/Article/details/gtzpmmrtpx.html

[U68] PHP：PDO 连接
来源：http://dali.nwbrower.top/Article/details/gtscdddkxi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gtxlpvjtaf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhengqikj.top/Article/details/gtohcfcipn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gtgijcwnmz.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gthkvqssja.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhongyouzk.top/Article/details/gtpmzswwpd.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gthygipthi.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gtrlnuyviu.html

[U72] PHP：写错误日志
来源：http://dali.birdmap.top/Article/details/gtgxgcdqtf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gtyyzrazac.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gtsuyijmcr.html

parse_ini_file("config.ini", true)
来源：http://dali.guowangkeji.top/Article/details/gtleswmspa.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdjcpfuk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yonumen.top/Article/details/gtbyhwunoz.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gtqpmjxnjq.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gtqejcnlpy.html

[U76] PHP：简单路由
来源：http://dali.vqdsnc.cn/Article/details/gthmhiviqc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gtgwqqmubp.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gtjtqzqmyr.html

composer require twig/twig
来源：http://dali.316326.xyz/Article/details/gtrsbhlfin.html

[U78] PHP：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtcfhedncv.html

composer require --dev phpunit/phpunit
来源：http://dali.havefunace.top/Article/details/gtudxapxve.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gtuhlyhabw.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gtlqhstkqn.html

[U80] PHP：代码规范修复
来源：http://dali.nwbrower.top/Article/details/gtdvtipvvc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gtyusfayzn.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtiafccjpz.html

npm init -y;  npm i express
来源：http://dali.jinghuilouyu.cn/Article/details/gttbmfefud.html

[U82] JS：package.json 脚本
来源：http://dali.haohaochexian.top/Article/details/gtawtptecj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigfzy.top/Article/details/gtialjywpa.html


<!-- 参考信息 -->