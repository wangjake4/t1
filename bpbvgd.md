代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtuazxciup.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gtvoormehr.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtbyvpelin.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtrisceahx.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtuxayhbjq.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtxsrjviia.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtyyfrwohk.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtcdoeutml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtqdhjlmav.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtokotcrgw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtyaeimwwh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxjszqjkl.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtgqhlbvgy.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtcdnbvrir.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtqhxuxcic.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwzgquix.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtgiyngeco.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtyvuzozly.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtosurnymq.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtjgewcwjo.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtgllqokzj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtnmgyjxob.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtpbfpjkfa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gtuzpyhpef.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtaeytsner.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtdofoners.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gthapckpti.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtrppeuyfa.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtliezwrij.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtkvqsnaqn.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gtcpioauvc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmkhtzwi.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtsecdsccl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtctsndshw.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gtaombdygw.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtcqqnsbdg.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtwbqzcsms.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtoeegssem.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtkgfbhdld.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtlkjxzkmc.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gteieqelrw.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioekqqst.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtcovzelrb.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gttonnrktf.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtsdkbvisr.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gtthsrkvxl.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtrbxgrwwv.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtltlevwmo.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtqsjanlka.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gtwwmyqjgv.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtezlxiaar.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoprvaweo.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gtuhxeoekw.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtmsncdqqx.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gtyfveigja.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtqndwwbjh.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtyzbufipy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwakqjmzo.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtitvqdwpi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtkcqkhhfx.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gtgfihpquw.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtzlnanpbk.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gtkodlfrgv.html

class A: Base { override func f() {} }
来源：http://dali.vqdsnc.cn/Article/details/gtiriprxxk.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gtrbjfjaxs.html

do { try f() } catch { print(error) }
来源：http://dali.ppjwa.cn/Article/details/gtbydwoiis.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtvwqniafs.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtjxobthnc.html

[T29] Swift：guard 提前返回
来源：http://dali.fengsongda.top/Article/details/gtagmcpguk.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gttlcjchnq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtkcqivrzt.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtcmauxlip.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gtlblzbjok.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtwwpxhivx.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtiukqbqou.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtcyllkqxd.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtsnvbhgeo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gtxgicgiam.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtvlepgity.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gtswcybbjy.html

[T35] Lua：字典表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccntdldx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtwnjmgcxm.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtvhqiuevx.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtwbgawsyp.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtqnnnuduy.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtpwikfmoc.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gtrujqmrpw.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtnrhazvwh.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtzjcrkeuw.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtauuuacar.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gttcklrhrz.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtrefyrscc.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gtqqtdwdgj.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtguugfzxl.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gtfakttcqg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtatxcwmyy.html

[T43] Perl：字符串插值
来源：http://dali.birdmap.top/Article/details/gtgpuuiwlb.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqtsctpi.html

[T44] Perl：条件
来源：http://dali.ybcxt.top/Article/details/gtslzbolez.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gtwuohmcxm.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gttdrapfgp.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gtrjckkfyo.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtgefdvnje.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtbxwiukka.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gtpuscrgkb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtugiycjgz.html

[T48] Perl：正则替换
来源：http://dali.zhongyouzk.top/Article/details/gthezfpmsv.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtsygoggov.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtczyjffez.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtuedwfvcx.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtpijexzmo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtmknbehnu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtyamumjph.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtqnakkrqy.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtmepmvrot.html

[T52] Scala：变量
来源：http://dali.jqgufenzy.top/Article/details/gtdiiijghb.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtcycvqnwd.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtpefguzxo.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtcbudmkkc.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgicqqmtp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnqydgxzq.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtscivftvt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtzphuewhm.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtlfvobtzc.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtdpggvqko.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtutuuxzna.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gttethtitu.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtpyaijoqq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtdswiuupc.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gtrgbmhltg.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtydqugyul.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtgrefrinf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtdviorxkw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrmcjoxuo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtwnpduvkl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrivpuvkw.html

[U01] Py：创建虚拟环境
来源：http://dali.shuidangran.top/Article/details/gtkbcobufc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gtptoubxjh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gtczqsqpni.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gtetrecteq.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtlbgwatyu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gttxpgness.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gtnbcwzpnr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gtrflfjfff.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxteluve.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtkcclfotl.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtwfclxzjm.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtrjltyees.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcfqfiqg.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtvvsygfkl.html

[U08] Py：展平二维列表
来源：http://dali.hongshengwenyu.top/Article/details/gthhhowfqp.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtxskqijpd.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtfekeorex.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtnfjvfedj.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gtbxfkgxps.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtkpuekmyq.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtorbumtvc.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtuanfvzcr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtqmyainyq.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtcsfmlrxs.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gtnxpgkomi.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gtfcxmzste.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gttaykwupa.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gtoeoilwjh.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gtikquzixa.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gtyinakswj.html

[U16] Py：命令行参数解析
来源：http://dali.fengsongda.top/Article/details/gtkviwvkgo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtfuoqnump.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtfxanlkrw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtjdnqndef.html

[U18] Py：预编译正则
来源：http://dali.andypj.xyz/Article/details/gtlzlkitzo.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtmflymmqm.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtaluiphik.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sufxvd.cn/Article/details/gtzrqiznct.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtzbmlkyev.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gtuqobhhxp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcyxihih.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gtwzvzlchu.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gtimxazybr.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gtuetkjfne.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gtvuuryssf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gtuuobyofh.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwtstxhz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtztliaovm.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtraquwgox.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtuiwjdqkd.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gtikwskeie.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtzslplhkl.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gtxybwkqgv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtfduyuktj.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtvecxaffs.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtghnwprbx.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gtszrxqipm.html

@property 与 @x.setter 配合
来源：http://dali.sxryk.cn/Article/details/gtkwjzouct.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gtqelcvbco.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtcybbpsvm.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtwbssovdl.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksupjpjn.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gtyzqujglw.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gthucjgjtf.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gtzwxjnxvf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tianlin.xyz/Article/details/gtsmpuxbpy.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gttvomzmma.html

chardet.detect(raw)
来源：http://dali.yueranfly.top/Article/details/gtvgtjvlpj.html

[U35] Py：发送邮件
来源：http://dali.dashuyun.cn/Article/details/gtgkzzestm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtjgimfocj.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtncqgmstn.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gttjmodskk.html

[U37] Py：读写 Excel
来源：http://dali.hongshengwenyu.top/Article/details/gtbdronaqi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gtgzfjlhib.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhengqikj.top/Article/details/gtyvrvddje.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtcwkmiwtd.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gtrjrxdgac.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtxkwfcian.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtyqcxfzlw.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtdmbjekkd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtypfmlxhe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhoulong.xyz/Article/details/gthhwtmlkr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gtevdhycup.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tian-w.cn/Article/details/gtievlnhob.html

[U43] PHP：声明命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtpbugqtix.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gtzdemffno.html

[U44] PHP：开启严格类型
来源：http://dali.kuanghao11.cn/Article/details/gtbcsrfepb.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gtbaxwwzoq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gtajbtegft.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtitfeuepc.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gtqqkdjxmf.html

?string $name = null
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyhdoodm.html

[U47] PHP：联合类型
来源：http://dali.gaohongyu789.top/Article/details/gtiofqehth.html

int|string $id
来源：http://dali.jlsjyb.cn/Article/details/gtvxvhaaph.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gtukawaahs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guannengcc.top/Article/details/gtqqqmahkx.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gtpugfzmiv.html

public readonly string $name
来源：http://dali.nanxuanxn.top/Article/details/gtrgyndvul.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gtypxdwyeo.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmbstfoqg.html

[U51] PHP：数组解构
来源：http://dali.quarkkingdee.top/Article/details/gthhpnhabo.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gteutvvcrj.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gttbizipfx.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gtcvijlbpe.html

[U53] PHP：空合并运算符
来源：http://dali.hnxiangtu.top/Article/details/gtzwiassim.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gtcbtxecgh.html

[U54] PHP：空安全调用
来源：http://dali.yj20258888.top/Article/details/gtztdxjfee.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtlnlneemm.html

[U55] PHP：match 表达式
来源：http://dali.snrcjt.cn/Article/details/gtkxxabirw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gtsbyfhanx.html

[U56] PHP：命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtoovdsphv.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtvdkymjlw.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtftboqyvd.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gtraludqsz.html

[U58] PHP：数组三件套
来源：http://dali.nanxuanxn.top/Article/details/gthhmiqajl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gtmxdvtuav.html

[U59] PHP：自定义排序
来源：http://dali.yj202588.top/Article/details/gtkxgarivq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gttybuvmac.html

[U60] PHP：JSON 编解码
来源：http://dali.hnxiangtu.top/Article/details/gtsjdbxawe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gtnqmugjsg.html

[U61] PHP：正则
来源：http://dali.shuidangran.top/Article/details/gtcilcclwa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtjwcnqwxf.html

[U62] PHP：日期对象
来源：http://dali.xinyue.icu/Article/details/gtyiorwqwv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gthpjrugwr.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtgddsplvk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthupowimc.html

[U64] PHP：目录遍历
来源：http://dali.fengsongda.top/Article/details/gtasjzqxgq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ehwqpu.com/Article/details/gtdoqtdpnl.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gtfqruoawl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtqphowmlo.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gtjowxiucu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gtaqnawbst.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gtiwzkjdrs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuanzhike.top/Article/details/gtjqvoghwb.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtcjroalsd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hammf.cn/Article/details/gtosngjitl.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjedksczc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gtllxwxinu.html

[U70] PHP：PDO 事务
来源：http://dali.aizwys.cn/Article/details/gtvwoofukc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gthqsumits.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gtktoqakre.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtqvvkivtk.html

[U72] PHP：写错误日志
来源：http://dali.fzhhl.top/Article/details/gtypgplanj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pengpengdd.cyou/Article/details/gtvadshqkv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gtustkohtg.html

parse_ini_file("config.ini", true)
来源：http://dali.guannengcc.top/Article/details/gtotwxuarw.html

[U74] PHP：读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtigwqrmtc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtvoqmiwcr.html

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gtorgioqdv.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwbdhtyv.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtkmsxkqkm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gtagwzlxzi.html

[U77] PHP：模板渲染
来源：http://dali.nanxinkj.top/Article/details/gtuqhjbbdm.html

composer require twig/twig
来源：http://dali.yongpay.top/Article/details/gtxaysyqpd.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbcrnfvd.html

composer require --dev phpunit/phpunit
来源：http://dali.hnqzz.top/Article/details/gtsyucfhns.html

[U79] PHP：静态分析
来源：http://dali.316326.xyz/Article/details/gtvppyqsyv.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtzwqvzhze.html

[U80] PHP：代码规范修复
来源：http://dali.9152youxi.cn/Article/details/gthtcphcvu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cucudq.cn/Article/details/gtbhzxqbzl.html

[U81] JS：初始化项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyzzfhcr.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gthcttiaqx.html

[U82] JS：package.json 脚本
来源：http://dali.xziqi.cn/Article/details/gtfqqrioyg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gtmccoinoi.html


<!-- 参考信息 -->