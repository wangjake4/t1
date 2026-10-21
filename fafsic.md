代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtkyojibao.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gtvzysixcw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtsxlmxczl.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtxlzfbdsb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gtenuxxvsf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlcqasxuy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtljlfgxbn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbqlsjzxm.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gttnwzclkq.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtdizdybks.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtoacnloap.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gtrgsnvskw.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gtuowwtahe.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtkyegewjw.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtgfksuybb.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtzutkwmmv.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtnbtlqecv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtsjofbqzo.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtpjkcsrfc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtgoromsjb.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtpwoyehoj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtoxgxrmvi.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gthplnumpo.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtsfgtucpc.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkczpoddx.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbffwzudn.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gtcmgjqtwa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gtqjzkxemq.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmpovdbl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtbcwlfjzc.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtaaqpcyxp.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtnipaqolz.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtzkktnquz.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtllvgkwue.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtxyhasgqp.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtvfgmtdwt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtdxcanaja.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtcfqkctlj.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gtxakkrpzx.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtdiyyqahn.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtxifwedhl.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtqgwwuylr.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gtyemlznuv.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtuqkmbufu.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtiagwixdh.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtjosbzdab.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdzmbwyq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtyurpefow.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtiqkyrbmx.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtypwtvdsw.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtaddtyhgj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtzdkikkoq.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gteriqifer.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gtbyhzlpmg.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtsqnbeotv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtwavtpzbe.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gtcpbderzi.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtmcajbemk.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gtltyywpad.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gtlnnhvnsh.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtprzzwvdp.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtyemirpkb.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtuuoqjznj.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gteyrhpfxm.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtrfofglav.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtzpymbqwb.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtdftnyxhy.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtrqiftcad.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtlmmmjnzg.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtplqtysuq.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gthdzzsfkk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtvvzyzpeh.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gthbuakdmv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtasqrudgj.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gtahsdbfqv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gteconxxas.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gthxbctckq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtloloqfoh.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtlnfrqeiv.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtdtqvbwgv.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtamviunbm.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gteayjyocp.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gtowspnfvs.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtalfofvpg.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtikbpjdxr.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gtcjjhpnjm.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtmtyvztqz.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcudzsjil.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtnnyfeotk.html

print "Hello\n";
来源：http://dali.yangfankeji.com/Article/details/gtcxnsjfea.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtdtoudhxy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtwvfjjfdk.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtnzwakfwo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtargueszi.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtdnbihutf.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtwtnhtlgj.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtprjdfttj.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gthrvyhzor.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gttwibkrpq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtnlrfmnrf.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoiyvrbn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtumafhsht.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtgablcqud.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gtwxhtggmp.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gtqmskxuaf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtwwcmczgu.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtkdnznjks.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtuplqatpj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtmwpxscub.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtlyzqevuv.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gthklcignx.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtroyzgojw.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtripeomkt.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gttytfpflt.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtkfwcoryf.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtyarrqepn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtzxrxjzdo.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtdmtbezkx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gtacrkosxl.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gtrlmeaslx.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtumaovmtn.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtihrrstrs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtyyiknjgp.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gteueslekt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtgrxedymp.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtyngbnphy.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gtxrcqfkql.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtgqnjzzck.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gthjsmwpdl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtynddraxk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtvnhunfpo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrhbrpgje.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtdrgnudqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gtztsvezjd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtwctgvvgs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtmjhcacel.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtndeaqond.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtygvfepjn.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gturrrbfgf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gtwidlvclb.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtyuqrzmma.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtgjggllwz.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtxujvcwpd.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtrmddpiuz.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtjucdtzyr.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gtohpoejsy.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gtvdyutxjw.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gtqlxqxqfl.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtxecbnlzu.html

max(d, key=d.get)
来源：http://dali.yj20258888.top/Article/details/gtkisvutyu.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gtaypkktta.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gtcaeauwcb.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtlsayllyl.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gtlcktlgci.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtypgswozd.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtegjzuakt.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gtxqpsynim.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gtstvqswnf.html

[U14] Py：分组收集到列表
来源：http://dali.hywenlv.cn/Article/details/gtqflaolwd.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gtiwopfvsw.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gtqwksloit.html

t = time.perf_counter()
来源：http://dali.316326.xyz/Article/details/gtswixjikd.html

[U16] Py：命令行参数解析
来源：http://dali.ehwqpu.com/Article/details/gttpunctgz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gtwljojrzf.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gthlgowomh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gtsufnrwiu.html

[U18] Py：预编译正则
来源：http://dali.jyoumei.cn/Article/details/gthzkyzyei.html

pat = re.compile(r"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtiybrukeh.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtxavudhem.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtferanenb.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtvbvgskqd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gtzghovxbx.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gtdnfskepk.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtgusbossb.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gtwzemmltt.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtruzfdrlk.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gtteowrkmq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gtpzfndhos.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtudkvytce.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtirdatgjs.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gtpgagrxvo.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gtieymkjyo.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtqpyotyyc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gtaiglkvvi.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gtmbdvpzvh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gtijpnvwvd.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtnrnguzdo.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtesewduop.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gtwqbpubxl.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtmgqlfxti.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtwifruxdm.html

@dataclass(slots=True)
来源：http://dali.sufxvd.cn/Article/details/gtxikeijhw.html

[U31] Py：单测
来源：http://dali.birdmap.top/Article/details/gtehlvrnbt.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gtsvbjdghy.html

[U32] Py：代码格式化
来源：http://dali.tian-w.cn/Article/details/gtdcgniutw.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gtbiquogjb.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gttxoiroyc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gtigwhxssj.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gtaxvhaiho.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtnfiegkwc.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gtcmioqpqw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gtzuktbncz.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gtkwpftljm.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gtyikvjiwm.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtmpqrgzgz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gtwrstolzl.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gtxoovyobo.html

Path(__file__).resolve().parent
来源：http://dali.gotoacloud.top/Article/details/gtddyokobv.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigfzy.top/Article/details/gtxhwliqxk.html

sys.stdout.isatty()
来源：http://dali.wangdashe.top/Article/details/gtiavhahbv.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gtzjnxnrdn.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtdhorkyme.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhengqikj.top/Article/details/gtdmwwsefr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gtjxweahmc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shzxlz.cn/Article/details/gtveeugmep.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cheryme.top/Article/details/gtufcqkzoy.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gtviwjxhss.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gthwrxurfj.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gtymxgqvlo.html

declare(strict_types=1);
来源：http://dali.haohaochexian.top/Article/details/gttsbqfisw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtminxwoxh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gthadhcdvd.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gtfbavllpp.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gthuipsnye.html

[U47] PHP：联合类型
来源：http://dali.yonumen.top/Article/details/gtmlazmxht.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtdkazxomd.html

[U48] PHP：纯枚举
来源：http://dali.cashguo.top/Article/details/gtyylmzzcs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gtavratsvy.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtdfjfrkle.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gthjovzfoi.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gttuguycim.html

public function __construct(private int $id) {}
来源：http://dali.hfpthk.cn/Article/details/gtcfzcdeaw.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtedllmmvb.html

[$a, $b] = $arr;
来源：http://dali.ivvv.top/Article/details/gtelafqrqy.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gtzsavqvmx.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrjddayq.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gtjazgeyvj.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gtlzitngdf.html

[U54] PHP：空安全调用
来源：http://dali.hfpthk.cn/Article/details/gtfgzbzpkw.html

$obj?->method()
来源：http://dali.svipenyu.cn/Article/details/gtlngcangi.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gtrmbbzyhb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gtlkywphjl.html

[U56] PHP：命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtbtaeowqk.html

f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtfdeljuip.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtycuvsxnc.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gtkqpwtqcb.html

[U58] PHP：数组三件套
来源：http://dali.snrcjt.cn/Article/details/gtxpgmmhat.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gtelymjtfs.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gtycfsohnm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtbnjqmqil.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgfzy.top/Article/details/gttjbqhjxa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yanxiufei.cn/Article/details/gtywnqfpcb.html

[U61] PHP：正则
来源：http://dali.nanxuanxn.top/Article/details/gtieinizgc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtlshamgwd.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtjegporvq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjhxzvem.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtdwlpentu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gthptopcui.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtpbqmhryf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gtgwllubra.html

[U65] PHP：会话
来源：http://dali.zhengqikj.top/Article/details/gtuemvoslt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtshghawux.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gtntewxotz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gttudboydp.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gtfutxeccy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtllwzmqrk.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gteeinnirq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yongpay.top/Article/details/gthwffyxhe.html

[U69] PHP：PDO 预处理
来源：http://dali.yongpay.top/Article/details/gtthrxakjc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hongshengwenyu.top/Article/details/gtzdybtnvq.html

[U70] PHP：PDO 事务
来源：http://dali.xinyue.icu/Article/details/gtfgxhkcnj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtnxmrplnt.html

[U71] PHP：抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtcsgrawif.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtsxpmausi.html

[U72] PHP：写错误日志
来源：http://dali.sweek.top/Article/details/gtcqspxqyt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.birdmap.top/Article/details/gtojruesyy.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gtebmvsdah.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtrexgnk.html

[U74] PHP：读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtpwwnkgmb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yanxiufei.cn/Article/details/gtraqesekt.html

[U75] PHP：依赖注入
来源：http://dali.zhixingplan.top/Article/details/gtrdiibtot.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gtgnyvtdpe.html

[U76] PHP：简单路由
来源：http://dali.ehwqpu.com/Article/details/gtlxrcfrwz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gtzkiruqqo.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtvkjtasyr.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gtelvouvsb.html

[U78] PHP：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsfwsbtp.html

composer require --dev phpunit/phpunit
来源：http://dali.daria6918.cn/Article/details/gtizqerdkw.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gtrvrvjfnf.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258.top/Article/details/gtokotxohh.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gtawohxpwf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoajiegwz.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtcjlsuifa.html

npm init -y;  npm i express
来源：http://dali.316326.xyz/Article/details/gtyxluiwin.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtxygjrqux.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtbouuezyu.html

[U83] JS：ES Module 导入导出
来源：http://dali.xinyue.icu/Article/details/gtoxatjlut.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtdaxbaiun.html

[U84] JS：CommonJS 写法
来源：http://dali.sxryk.cn/Article/details/gtrzteyekm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gtxdieprfn.html


<!-- 参考信息 -->