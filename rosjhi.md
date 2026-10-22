代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtgascgbqt.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gtmdynlarh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtupjzpguw.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtlzdvuprq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtbugzgefa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtiscctjva.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtropzosjt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjlusnvuv.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtamiqhqex.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtwaptjmjd.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtoorotusz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtbeqnkxww.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtamwrsqne.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtpvyniool.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtwvbndeoc.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gthvhkqmsi.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsvbqrqh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtjabudkro.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtgpawprid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtuzzdixhy.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtqozwueox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtsdlwatvx.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtxbagdujz.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtuvcmgsol.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtjvydymik.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtlaebnwid.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtfofqqmfu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtczvrowxs.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtbmtdciqx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtfbuffysc.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyqcubmq.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtwfqjjjnm.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gttwlwwjjg.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtnodlzlny.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtvfrhhzfn.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gteznehjye.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtdhnglcwz.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtsllickkr.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gtvyynesgh.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtxvebopgb.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtqxaphjdc.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtwlhzkbyl.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtmmakjfhf.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtygvqsucs.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gtlcxinweh.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtgzxiswpy.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtvbewaaol.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtujrxopco.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtnaezdqce.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtnmilmhwj.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtfnosbkbl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gteotmujkt.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtdtjxgeni.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gteopyfrev.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gtnmtnfiol.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtenngnpfk.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplefdoib.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtdstlmjoq.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gtwybkfzyx.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtajanaqaa.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtpqmvzadq.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gtqzaaxpro.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtvcofksuf.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtcpedfxff.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gtcdrpdgef.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtdkwsiqgf.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gthkxcjcet.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtogycvtpc.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtynwasowq.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gteihxktiu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtixovhuus.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtbykmscbl.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtxgkufixl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gttmzniqdk.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gtppybaime.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtgojgaqgl.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gtwglucoza.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gthuxlncdr.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gteyuwhniu.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtbgaxjpgy.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtoiswrlzc.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtzihiorvg.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtodiwvrmk.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtwgdlzvrx.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtkmgficqw.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtxjndurmo.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gttxokkneh.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtnbmsdjcr.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtclbsckoo.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtvwytwsjs.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtpcjhwmsl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtdopbrhxu.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtgssgelpx.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtdissbofk.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtxmxmauni.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtuuxpmlgf.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gtuiwrrelm.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtuwasbcjq.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gtanoxlqxv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtnuohbape.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gtcaelenrg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtwsbpgjcp.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtzehjkppo.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gthqkfjnby.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gtwjtitdfr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtgyhvkofb.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gteepkvylf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtbeplxtbk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzmbtbvxe.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatwggpjw.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtpfdyepfe.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gtnvncwzgq.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gtgkkyamuq.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtbkkupsly.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtjgfdyabf.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtwpsuljho.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtljdgxgdm.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtwmotxnin.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtpspbrxtu.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtbwyvxmgv.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtqrcyhhoc.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmhnhtcv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtrfjuzabj.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtkvnlzrhp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtxcuxxlsp.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtsdnjyfyu.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtgbzukcbx.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gtonvxrylc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtkbgkqhva.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtldpqztdw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtawslunyr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtclalreas.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtuvpnyswi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtjriiduco.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnqzz.top/Article/details/gtzlspsgwt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmhijlvj.html

[U03] Py：加载 .env 配置
来源：http://dali.sufxvd.cn/Article/details/gtbilsonbm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtwwgcxxsa.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gthovwfajk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gtcsywvhld.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gtzszihion.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtcyowtowx.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtspcxoezt.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtoctpligz.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gtjgiqcoaw.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtozbsvfzw.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtzkdryhzx.html

[y for x in nested for y in x]
来源：http://dali.hnqzz.top/Article/details/gtwzrtmqpq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gtrkpcnuko.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gtzrhafclk.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaguufspq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gthbdowqzn.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gtaypugsuk.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gtaepftudq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtnjofxpzd.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gtqvkxwouv.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gthzfqsmkj.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gtnbnbzjur.html

[U14] Py：分组收集到列表
来源：http://dali.ivvv.top/Article/details/gtpxtzbrgo.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gtfrrnhtss.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkosapnxp.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnqhyybj.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gthhdzpxbd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gtdxckmtpw.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gtdvzxhvww.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtrqnfoaso.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gtlcswbooa.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtmamfwxwi.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtlxkncnsl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtgpedeuoy.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtvyvavcgp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtrqbhujgb.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtxrmlmshf.html

@contextlib.contextmanager
来源：http://dali.svipenyu.cn/Article/details/gtgxqlatyy.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gtkfstwwsi.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gtdbqrolik.html

[U23] Py：分块读取大文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluuzwxjm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtcvafguki.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtrqvqlhje.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtfsywwodr.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtgkurmwak.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gtwtjjogxj.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gtfvexoppy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtnjsfgfgx.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gtxybonapi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258888.top/Article/details/gtqnhcybdn.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gtbcjawqrb.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtoprrknjk.html

[U29] Py：属性校验
来源：http://dali.c1oappe.top/Article/details/gtgvusatvk.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gtdyvdbqxl.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdzkoibf.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtstukpmhg.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gtxigmkusn.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtqztfntqc.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtcipjnief.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gtmhymendv.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtdwttmhex.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sysykeji.top/Article/details/gtqsraaysr.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gtxxyyxmkv.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gttyvvxspv.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtnotxghpv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gtvnvygsyo.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtuatfaizp.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gtvpfmftol.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtpahykglm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gtjvpzapih.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gtudcmlilq.html

Path(__file__).resolve().parent
来源：http://dali.tianlin.xyz/Article/details/gtbaikejib.html

[U39] Py：判断是否在交互环境
来源：http://dali.tian-w.cn/Article/details/gtfhvjoeaz.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gtwtzrkixd.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gtdeilrhpq.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtujocbyig.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tianlin.xyz/Article/details/gtlujlvnbn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gtdjyebwjf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtfyujwttk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gtynklbxqn.html

[U43] PHP：声明命名空间
来源：http://dali.guowangkeji.top/Article/details/gthhyzojxs.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gtfuifjber.html

[U44] PHP：开启严格类型
来源：http://dali.0kj1m.cn/Article/details/gtmacgtpqg.html

declare(strict_types=1);
来源：http://dali.9152youxi.cn/Article/details/gtralwyeok.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtbjlnourj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnveygvmk.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gtumrgorfh.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtrwrsbstz.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtycdaorjs.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gtgpdbvhdf.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gthneajmlp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gtwzowbmtn.html

[U49] PHP：只读属性
来源：http://dali.yj202588.top/Article/details/gtwhyibicy.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gtxqfamndo.html

[U50] PHP：构造器属性提升
来源：http://dali.sysykeji.top/Article/details/gtqbokohbo.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gtpivguuwd.html

[U51] PHP：数组解构
来源：http://dali.jlsjyb.cn/Article/details/gtnmiylapn.html

[$a, $b] = $arr;
来源：http://dali.pycfn.com/Article/details/gtkisgvqhd.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtowsliedh.html

$double = fn($x) => $x * 2;
来源：http://dali.fengsongda.top/Article/details/gtatbupgic.html

[U53] PHP：空合并运算符
来源：http://dali.yuanzhike.top/Article/details/gtrzjboyjt.html

$v = $a ?? $b ?? "default";
来源：http://dali.haohaochexian.top/Article/details/gtwdmfcinx.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gtlvlnycjt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtdepseuwe.html

[U55] PHP：match 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtbfoazgmf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtahsbrcil.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gtenxstdls.html

f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtzxkllryf.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtcvtkjqza.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtfucpkych.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfqqcrtk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.snrcjt.cn/Article/details/gtmxujohfn.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtiiivieuh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtcgdmaivh.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gtudiwtpsy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gtpsgxludp.html

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gterkjdtoj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtzslrpnxy.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gtmhxbtjoc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gtokllkbaj.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtqzavcsah.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.c1oappe.top/Article/details/gtbwmlpahz.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gthhyaupvi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gtmthoxkty.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtjkzvgklu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtxpvfnash.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gtoxaqoyno.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gtzgbjwzou.html

[U67] PHP：处理文件上传
来源：http://dali.zycfv.cn/Article/details/gtjfkywnhu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gtojgedezr.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtwnnhuens.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrozqium.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gtkqbhvyfq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gtqqluqiyl.html

[U70] PHP：PDO 事务
来源：http://dali.yuxming.cn/Article/details/gtwfnkaafl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gtuhrobsbp.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtyqkfkvag.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtfbvrhxpn.html

[U72] PHP：写错误日志
来源：http://dali.kuanghao11.cn/Article/details/gtltmselvj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gtcnqzbdkd.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodvawapu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhoulong.xyz/Article/details/gttrsrzmzu.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtreitbhba.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvgskzca.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gtjtgnpmtb.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gtvcxfgnii.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gthemgzdqb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gtgbnrjbgt.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gthmhjrfcp.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gthyoxmftg.html

[U78] PHP：单元测试
来源：http://dali.fzhhl.top/Article/details/gtuemuunah.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gtqsqxsqkq.html

[U79] PHP：静态分析
来源：http://dali.sysykeji.top/Article/details/gtctiuscam.html

composer require --dev phpstan/phpstan
来源：http://dali.yueranfly.top/Article/details/gtqgqkoyft.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gttxwvqzsu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aizwys.cn/Article/details/gtcqrmhhyk.html

[U81] JS：初始化项目
来源：http://dali.birdmap.top/Article/details/gtczmmhlho.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtzkihdvyz.html

[U82] JS：package.json 脚本
来源：http://dali.xuanzx.com/Article/details/gtxhodhibt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gzhubu.top/Article/details/gtcwktnmmm.html

[U83] JS：ES Module 导入导出
来源：http://dali.jlsjyb.cn/Article/details/gtqplcjwdz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gthqnolikb.html

[U84] JS：CommonJS 写法
来源：http://dali.xuanzx.com/Article/details/gtvrcaguwr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gtjydnyblj.html


<!-- 参考信息 -->