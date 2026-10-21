代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtbxalzvnt.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtqetegaif.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtagkourax.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtlpeenvlt.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtsruvivby.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvhhlbux.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtllmxybqo.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtdvkhceyh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtehdcnuiv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmcotfolt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtyfdjgdum.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtghqucfrv.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtwkpmjqhs.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtmnljotmn.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gtknevrspr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtyyoqfiwx.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtibpndfvm.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtipvrqvdx.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtctzozevv.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtczejroun.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtvrpsszms.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtuepbkgps.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtbqqsipyh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gtnnxvsmui.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtwxtvpoxi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gtbeueqlxm.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtaqsssgsp.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtskekcfnh.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtbduftfzr.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtibjjnsnr.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtnlphqiyr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtrndlrkjk.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtgiqvwjim.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gtcxkbzwem.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtlhnojgoi.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtfdsgyray.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtmelrzsem.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gtpcgmjzhi.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtlzaxttjr.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtlwjcxcjc.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtwrhswnzw.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtudrsxpmv.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtzjhwassr.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtglbpcoxz.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gteidhqmtx.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtwtunfszv.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtczmjmfqh.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtkrlqnzmg.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtczwmvknv.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtlmwslupl.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtaafxdjyz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zdqjudy.top/Article/details/gtwejxvuid.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gtoemhljjq.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtocytodsd.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtwjebgvwc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtbzjldrip.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtrvljscvf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokunooxn.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtmzlmuysz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtzfureztk.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtwawcdqnx.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gttnsnayra.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtjkbnytra.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtotubmwfs.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtjmbpiixr.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gtcfqzisrn.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtoypqeemj.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtxwkxqqit.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtrhmckbqq.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtjdiozmbv.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtasqchbjv.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtmqckvbci.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtqeyjsgdp.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtbmlioicl.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtybzxjnae.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtkaoodivr.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtexibvxvw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtrvertxjk.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtsgmrhwoz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtzqydxhbt.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcatrtqe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtkgsjbivn.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxzdiyeco.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtajcqtwrj.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtjfctbcgl.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gtmoqnrkwr.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtwsdraqav.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtozaxtbou.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtxmvpacqn.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gtetnxfcaq.html

[T40] Lua：元表
来源：http://dali.nwbrower.top/Article/details/gtmsfhdisc.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtlaouztvf.html

[T41] Perl：Hello World
来源：http://dali.gzhubu.top/Article/details/gtewfxdewk.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtfcdehwms.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gtbydaovhy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtmlotof.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtpzyatypg.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gtksklbfvh.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtxurowhsk.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gthkbakxsa.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtnxiagskq.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gtqjcwtjqr.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gtsofayfnn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gtjapzrcxa.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtjbafjhdz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gthohfjtwu.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gtbioxtwtu.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnehixqw.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gthofgdmls.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtodkqnzch.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtajcrqglk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gtgcxsbqow.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gtydvccqag.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gthgvjdvdh.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtcefbsnxf.html

[T52] Scala：变量
来源：http://dali.shuidangran.top/Article/details/gthgddemte.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtrdrodjik.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtbbxpcrjc.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtklvodulx.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtmstlxrlr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtllzsjrze.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtjjazgdvw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtnvxnaoau.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gturjpmuij.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtsbsvlwoa.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtsppjquca.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtpluimyuy.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtqblocqqp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gtymgozhto.html

[T59] Scala：循环
来源：http://dali.ydzc1.top/Article/details/gtmozqzblc.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtbbxozzpl.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gtigzlhajr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.havefunace.top/Article/details/gtrpthgzzn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmjsurvkd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtxoqmiajr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbdnxwkbo.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtoentvyjp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtzhxleztv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gtycuyoufp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtjamkavij.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtehrcushd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtzraodqho.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtcitjttqj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxuanxn.top/Article/details/gtvxduwyvq.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gtrlttdccd.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gttkbhpwnn.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtujhoqpvi.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gtithxvscb.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gtsmayimoh.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gthulstzkn.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gtpujrbpek.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtslrmrlbc.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gtbgfqvyah.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gteeokqtag.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gttefafidj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtgirxtdwx.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtjorkrzxh.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gthleivbuy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.haohaochexian.top/Article/details/gtoyzevfqd.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtrhjoyujj.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnymjqxcy.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gtejxiwjpr.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gtcbgtsgos.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtjxgrucoz.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gtnyyuawkr.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtdtttahce.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gttvwuefst.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gtjoewflye.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtpgpmbflu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gtwiebrflk.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkjthgbt.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtholqofnk.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtastblztg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gtzphudnio.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvbsxygt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gtkhfirjva.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkumqxab.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtjxkgcgly.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gtpgliiwon.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gtupfamljg.html

[U23] Py：分块读取大文件
来源：http://dali.xziqi.cn/Article/details/gtpungqqct.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gthkswvsjs.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gtznzytcwj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtgksbipoh.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gtyimqkdbh.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtorxafurj.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gtqgcwxose.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtfpmknvyb.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gtpcdwqigo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gtqajdiwji.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtoeuawgnl.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gtgwykdelx.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtvjetncsm.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gtlmxaxljw.html

[U30] Py：数据类
来源：http://dali.yueranfly.top/Article/details/gtpegdafmu.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gtrrqmlbrx.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gtogvgtfzi.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtenvnirxl.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkfteqkc.html

ruff format . && ruff check --fix .
来源：http://dali.xuetiantiany.cn/Article/details/gtmvyjbrnf.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gtcbiorkmq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gtybgiljfh.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtfhrpdyzg.html

chardet.detect(raw)
来源：http://dali.tianlin.xyz/Article/details/gtiytsxtas.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gtkwpovpjv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gtkwfkqovi.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gtxlhxijuq.html

schedule.every(10).minutes.do(job)
来源：http://dali.ppjwa.cn/Article/details/gtawqobpnn.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtplcvkvpw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtnfjiitrw.html

[U38] Py：获取脚本所在目录
来源：http://dali.cashguo.top/Article/details/gtmfcfucbe.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gtaekgpdjj.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokbvnjxw.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gthlhikhka.html

[U40] Py：打印到标准错误
来源：http://dali.mhx1999.top/Article/details/gtznvevdmo.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtohlqtpbp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtmhyjofmt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnxiangtu.top/Article/details/gtvwjufxcq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gtqbbliyvn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aibaodan.cn/Article/details/gtbhjxyfsd.html

[U43] PHP：声明命名空间
来源：http://dali.cheryme.top/Article/details/gtpusjaerb.html

namespace App\Http;
来源：http://dali.yueranfly.top/Article/details/gtcuvhneyq.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtzwcgyldg.html

declare(strict_types=1);
来源：http://dali.mhx1999.top/Article/details/gtzucnhele.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gtzenlsxbt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gthiuhyliz.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtembcbxsp.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gtmsruvuao.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gtypmgxlmk.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtjuthxkzp.html

[U48] PHP：纯枚举
来源：http://dali.sxryk.cn/Article/details/gtjysqcihw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtrviovthq.html

[U49] PHP：只读属性
来源：http://dali.xuanzx.com/Article/details/gtkxrftbjw.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gttmztzoci.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gtsfbhndoh.html

public function __construct(private int $id) {}
来源：http://dali.hysaishi.cn/Article/details/gtjoulfeeu.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gtbwkwrwge.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gtzyylyyku.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtucoyasov.html

$double = fn($x) => $x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gtspqgbnij.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gterjuoofy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtifavfgcq.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gtwvhfyuqp.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gtrgpzswgj.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtqihhrlim.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtrxvkgbje.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtyvpdajvg.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtnzmdvioh.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtkgheoxtp.html

"值: {$a}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcvvsrfaj.html

[U58] PHP：数组三件套
来源：http://dali.xinyue.icu/Article/details/gtcxrjgdst.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtzwymrnza.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtckenrpri.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtxgqaunze.html

[U60] PHP：JSON 编解码
来源：http://dali.jlsjyb.cn/Article/details/gtmlyucaee.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gtwgmplccy.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gtwngbysaz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvppnrhlm.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgetkrsrc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yonumen.top/Article/details/gtevwtkxgd.html

[U63] PHP：文件读写
来源：http://dali.quarkkingdee.top/Article/details/gthcwyndup.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.quarkkingdee.top/Article/details/gtczxnqzvs.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtmuuapore.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gtozhksuts.html

[U65] PHP：会话
来源：http://dali.nanxuanxn.top/Article/details/gtcsfxvnao.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtudeeteyk.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gtyjtiztpb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gaohongyu789.top/Article/details/gtauwawqza.html

[U67] PHP：处理文件上传
来源：http://dali.yj202588.top/Article/details/gtcyrmezgg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gtlaumjjby.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gtzuvcqjzi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gtzdgjauma.html

[U69] PHP：PDO 预处理
来源：http://dali.cashguo.top/Article/details/gtpwcwnacz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xinyue.icu/Article/details/gtlzaptovp.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtknbxjnmy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ppjwa.cn/Article/details/gtklefvfje.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtstmodymr.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtomfhggfz.html

[U72] PHP：写错误日志
来源：http://dali.ydzc1.top/Article/details/gtwndrwsow.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gtwrysvgps.html

[U73] PHP：读取 ini 配置
来源：http://dali.sweek.top/Article/details/gtwtfnpkrd.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtkdqbbytl.html

[U74] PHP：读取环境变量
来源：http://dali.meibo888.top/Article/details/gtvztwbimr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ppjwa.cn/Article/details/gtfarvpvyj.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gtnoubswtt.html

composer require psr/container
来源：http://dali.pengpengdd.cyou/Article/details/gtlunpbqhy.html

[U76] PHP：简单路由
来源：http://dali.nanxinkj.top/Article/details/gtjifnyztj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenlongwang.top/Article/details/gtnmaaybhe.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gtaxlyzatr.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gtpnsupqqm.html

[U78] PHP：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gttgavbhsc.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gthrfkdtnj.html

[U79] PHP：静态分析
来源：http://dali.zycfv.cn/Article/details/gtrlkswhqo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gtxcwtzqds.html

[U80] PHP：代码规范修复
来源：http://dali.fengsongda.top/Article/details/gtnqmcnfua.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnqzz.top/Article/details/gtdipxqhvz.html

[U81] JS：初始化项目
来源：http://dali.9152youxi.cn/Article/details/gtbrjfljqt.html

npm init -y;  npm i express
来源：http://dali.cheryme.top/Article/details/gtyrcoludl.html

[U82] JS：package.json 脚本
来源：http://dali.jqgfzy.top/Article/details/gttrmjlfbq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtxpmhoqhb.html


<!-- 参考信息 -->