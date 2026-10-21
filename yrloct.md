代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gthuawvnjo.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtdffrpkzx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtiwcwtilr.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtiklisuff.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtejolhbpy.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtygblfdzm.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtwinwynvk.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtqxanovsr.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtgdtcguew.html

[S59] C++：静态断言
来源：http://dali.yj202588.top/Article/details/gtzieerstw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gteazyijpq.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtiybeoyvn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtohfxpfqm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrkttekzq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtivwikzls.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqvparfoe.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gticwxlehb.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtslejzxcr.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtdvmzsvpo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gtzrxhvsth.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gtirriapjb.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtmtehtixm.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gthuviexol.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gttmwahgou.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gthilksoia.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtkuiomila.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtonojngnm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtkhuunuds.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrwdribt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtljtsyzcj.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtiulgsjfy.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gtsihltghf.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtoputzrbs.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtapeulxrl.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtlcrnituo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtdpjihftn.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtrvhnvvkb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gtbtfzithq.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtfyqqcdcp.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtxhejhlcu.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gtieoufuzj.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtlbvepdxw.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtlltutoap.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtikvriikn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtdhubquou.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtwjfipmhi.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtrzippbuu.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaejqqhq.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcilnaopx.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gttighieqo.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtakiscoam.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtewobphrj.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtivkxxndc.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtfsyloeuw.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtbtibnxuj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbeojeyb.html

[T21] Swift：遍历
来源：http://dali.gotoacloud.top/Article/details/gtevpiufrb.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtpwyuvrgf.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtlougxvcs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtcwtnbcpe.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gtqrdhmudu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtomcjhiri.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtjtptecgz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtehcrmchr.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtlgsdmqjr.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gtjsqwsctm.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtmwvvcxxf.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtnwftcahk.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gthfqabgbg.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gtcfyihzbu.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtndjiupej.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtucmvlatz.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkwgstyl.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtanvdywka.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtdyfimmrp.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtpenvuwtr.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtgztytjlw.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmfnqbdp.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtrhtvefty.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gtjpitcfvu.html

[T33] Lua：表（数组）
来源：http://dali.dianchejie.cn/Article/details/gtfbirozly.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtvjrkjtqm.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gthslgikce.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtbyygkcwo.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtwqjpcjng.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaynjcekd.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gtdxzugexb.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtbftjntyg.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtbtbdhkwj.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gtayuefblq.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtebfcqiip.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtygstxyfw.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtjstlwese.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gtyrkviopm.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gtmrtefsbk.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzerfvyk.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtyxphndzr.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtvpkqbbja.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gtxfhotdsn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtmifpwgex.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtoycfqfqr.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gteryqkpgp.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtxpgbqicq.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtdrbezxde.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtpulrrymm.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtlorygdil.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gtoaszchjo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gtbwlrpgqx.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtzhspldvk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtixdslpws.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtbkonuuhk.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtckzyzonp.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gtjekmbwff.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gttlmuncmy.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtockifyof.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtynoipnej.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtqylbxmce.html

[T51] Scala：Hello World
来源：http://dali.cucudq.cn/Article/details/gtxrkkhxoi.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtkawvsydg.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtxoedeidt.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtuaywykjw.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtpcqletyg.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtgmnduefx.html

[T54] Scala：集合映射
来源：http://dali.sxryk.cn/Article/details/gtmhrymlxw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtjghxfgcc.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gthpvkzgjx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtttxraglw.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gtnjkmeila.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtcgzjbnpx.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgpzmqqv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtmbcqinvj.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtijwoqqjj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtbljwtpml.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtghimycol.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtrirxuazj.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtqtheolfr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtdjoekkzz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtytgymlll.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtmzxjvlxj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvvcckise.html

[U01] Py：创建虚拟环境
来源：http://dali.shuidangran.top/Article/details/gtfdrkxivk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gttjoodgry.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gtquzrdqzf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtpuprvpol.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gtfkupvigx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtoseoiuuv.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gtwkwimtnf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtynatjvfg.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gtebpqacgi.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtoosuscmc.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdungokb.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gtnsozkaww.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gtcyjxvjia.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtbuomlylt.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtosrxptul.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gtziddcpft.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtpxlerdit.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtyaqtesum.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtxanbvond.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxhouxmp.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gtydvedtaw.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gtdcislnbm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtmavlqotq.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gtbphvnysc.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtmyuvyhgg.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gtaqycolqe.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtrhjcxxuf.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtasvcwofq.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gtcqlhllbd.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtcilpsqta.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtavmvugpo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gthvotbtxz.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gttjdxiiwm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gtpjcqvqpi.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gtjadvqvjk.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtyyqtfqvs.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtbswawitf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtonkrdsdj.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gtbaoxujwq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gtdilleviq.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtuhmzjnld.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gtqengpzqw.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gtulvjqggj.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtjvegthfu.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gtuzyihlkv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtbvpsznfb.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszczjwql.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtybzsqyba.html

[U25] Py：CSV 按字典读
来源：http://dali.yuxming.cn/Article/details/gtvtudkuvu.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gtuoqvkeie.html

[U26] Py：并发下载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsicvvutl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gttsdrbvxt.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgxktajv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtzsqioknh.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtliyjyoag.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gtxiqbrtmg.html

[U29] Py：属性校验
来源：http://dali.pengpengdd.cyou/Article/details/gtyeorbvoe.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtpywyqxkw.html

[U30] Py：数据类
来源：http://dali.hywenlv.cn/Article/details/gtypyqgmwm.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtpuqnfoen.html

[U31] Py：单测
来源：http://dali.jiagoushi.top/Article/details/gtykyvwtps.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtmzmuydgt.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gtgaabfyux.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gtciocafhx.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gtdvcbgskr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gtuzkoqpkg.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtfojcboej.html

chardet.detect(raw)
来源：http://dali.pengpengdd.cyou/Article/details/gtjdzjprbm.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gtnrowrzwf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuanzx.com/Article/details/gtmwqenxtc.html

[U36] Py：定时任务
来源：http://dali.yvedp.cn/Article/details/gtsuwjaezc.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gtiqsqblvt.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gtnugwblcj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gtxydndzsa.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gtyaifezxi.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gthbavowyy.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gtoyjrhetr.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gtfublzbki.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfckdnpd.html

print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtvotgjcoz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtatolpueo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtqdkrriqb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xinyue.icu/Article/details/gtnlxsoxjw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtuznotlgn.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gtwkijsmbf.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gtpybezojm.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtrwpphckq.html

declare(strict_types=1);
来源：http://dali.xuetiantiany.cn/Article/details/gtuvqnulik.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gtjjkzzltv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbvcfbkn.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gtpjvicmsf.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gtxsiuswfv.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtqhndfbkm.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtpljbviqi.html

[U48] PHP：纯枚举
来源：http://dali.hnxiangtu.top/Article/details/gtlcsreogq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gtqwrxzlux.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtggrnlgel.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejysrceh.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gtmoqoqobu.html

public function __construct(private int $id) {}
来源：http://dali.redwolf501.top/Article/details/gtmycdhmek.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gtlsdevmey.html

[$a, $b] = $arr;
来源：http://dali.cdnleiting.top/Article/details/gtasnwtccm.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtqciuamfw.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtziidymiq.html

[U53] PHP：空合并运算符
来源：http://dali.zhixingplan.top/Article/details/gtrvixzvcx.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gtnrtybofs.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gtlhmjqetg.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gtzrjaktkh.html

[U55] PHP：match 表达式
来源：http://dali.zdqjudy.top/Article/details/gtudfyntao.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtmmjungko.html

[U56] PHP：命名参数
来源：http://dali.yvedp.cn/Article/details/gtabpeuqmk.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtkkiitrne.html

[U57] PHP：字符串插值
来源：http://dali.havefunace.top/Article/details/gtkowlwdch.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gtkrygukqg.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtcruzosky.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gtyblvcsyy.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gtrelnbfxv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtiemsfivq.html

[U60] PHP：JSON 编解码
来源：http://dali.cucudq.cn/Article/details/gtzvckrrbp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258888.top/Article/details/gtnirbeacs.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gtmvxtvrlc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtaofeghhz.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gtzpyeelqf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gtyfieqwms.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtwwpcayxo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yongpay.top/Article/details/gtxvgdqing.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gtcolwmozp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gtbgpmuyam.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gtgkfoqrfm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtykxkwjlq.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gtdwyknucp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvktxhyxd.html

[U67] PHP：处理文件上传
来源：http://dali.gogol.net.cn/Article/details/gthunwdvjm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gttmeefjsy.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtbybsmeca.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtuxfwgotd.html

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gtvzwgflly.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangdashe.top/Article/details/gtoaffpgyj.html

[U70] PHP：PDO 事务
来源：http://dali.meibo888.top/Article/details/gtggpbxybc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtglqobxho.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gtkaspsnkg.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gththojjit.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gtzgkoemig.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sxryk.cn/Article/details/gtzceodbvi.html

[U73] PHP：读取 ini 配置
来源：http://dali.cheryme.top/Article/details/gtofollkfk.html

parse_ini_file("config.ini", true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudtpsrht.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtjdzxyqxz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pycfn.com/Article/details/gtguhzhuqx.html

[U75] PHP：依赖注入
来源：http://dali.yj20258888.top/Article/details/gtuwxxrcgj.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gtjochktpt.html

[U76] PHP：简单路由
来源：http://dali.316326.xyz/Article/details/gtvwxahtzn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fzhhl.top/Article/details/gtfmxiwdwj.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtsarnruti.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gtloftcwok.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtulojgxav.html

composer require --dev phpunit/phpunit
来源：http://dali.hywenlv.cn/Article/details/gtkskfefjh.html

[U79] PHP：静态分析
来源：http://dali.zycfv.cn/Article/details/gtnotpsxpo.html

composer require --dev phpstan/phpstan
来源：http://dali.gotoacloud.top/Article/details/gtehahnfai.html

[U80] PHP：代码规范修复
来源：http://dali.hnxiangtu.top/Article/details/gtgqeswfbk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hywenlv.cn/Article/details/gtnluamelh.html


<!-- 参考信息 -->