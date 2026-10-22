代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtpneavcdf.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmuttlka.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufebnifi.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtgtejfusy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtmyjufodg.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtywtmshjs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gteddzxaxk.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtymfgyrwj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtqldkjveo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtshcebvqb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtotwtrnch.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlrryoxpu.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtbwtdfxvk.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtkhkdorar.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwkckmls.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gttdrvdqdk.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtyveujlsm.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbaxemob.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtkraufunv.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtklhvrbgd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtadmjeenl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gteksnllyc.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gtunyvyzop.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtowbnnojd.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gtubaheezd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtpnrzypsq.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtjhzdvymo.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtzubpcdru.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtrynxkkvl.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtneyahzbv.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gtqyhphuhy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtjgcldwak.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtjcibmzsk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtiszrpjzn.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtstbpkvru.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtvucazieo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhdqxwcg.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gtcyxbezas.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtiakfuigh.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtorfgzqjk.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtwrupbsyf.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtrkerunnt.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtmjmswvhk.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtrqmqhrih.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtoxuvvssp.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtuvbdyxwg.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtcuklwqdy.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gthedivexk.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gthukqfqlp.html

if let n = opt { print(n) }
来源：http://dali.sysykeji.top/Article/details/gtndaktekc.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtuxvkawcd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gttndzfwjg.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtmwukdegl.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gtaeejppsx.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtwlkelfxd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtvdtujsau.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtjanmnymi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtmockqhon.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewzirctq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtjtuwocqy.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gtciqjmuyr.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtlxpeypba.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtpwkfscgd.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gtwdgnlgte.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawlrffii.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtpanlfosq.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtrfmpkpvj.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtazjicmhi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtdioznlqp.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtuitrkdgl.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtdyvemluk.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtlfvincfk.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtdigfrjtw.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtcqwucknp.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtxoczqasw.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gtxocyltxe.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gtthdqushs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtscnwgavr.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtwvnuugmi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gtfdyhewsj.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtzukdbedw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gttlbsgehe.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gtmttsauyw.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gtgjtwutqp.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoswzfhi.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtvmpusxnk.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gtijvyrapf.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtmcztmfwx.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtaotiocuz.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtkuxsnoce.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtbsnowdzg.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtyivlpehy.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtbxpotojq.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gttcfcqhvs.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtasjtbmvj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gtfepbbyls.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtofiqfhhn.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gtenvngccn.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwvetdsf.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gtkjlvcswq.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtqgvuuaqt.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtmquwnjpt.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gtxbphcecx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtjdihfyrj.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtngpnhbrs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtvcwkgtvu.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtqhmukyzt.html

$s =~ s/old/new/g;
来源：http://dali.gzhubu.top/Article/details/gtbgezkjsl.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtlswkvrhd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtgoootyse.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtyibrbfks.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcphpprmq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtswsemxji.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtnzjgvsea.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gttrdfpjsz.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtgawfvhhe.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtzwhjtgcx.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtjxsectru.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtnpfdlarg.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtxgfjfsef.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gtkpmjibvf.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtskdutiul.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtnplvbvrr.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtnqtdofbn.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtajwcxjpp.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtbpfexfex.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gtwrqqfjxp.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gtgozuwjls.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gtlgtuptkm.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gtcoihryoo.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtyjsxsoaa.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gtancyfldx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pycfn.com/Article/details/gtluesfqbk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbytzkkny.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtrigfqcwn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlmblxvwc.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtikprmenj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtocomoblb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtueqyihjd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gtxqalsngr.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtraypyypw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gtmchpncbf.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtfconrhth.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtcrxntydw.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtzrsajvjq.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtxmpxdyxt.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtpvvnqgwh.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gtipyjifyo.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gtstgcfyfj.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gtqpqxsqqk.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtmegrrvbu.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gtxccjtlro.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtujihioni.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtpofcolwu.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtogfvarje.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gtrjosuelv.html

[U11] Py：生成器表达式
来源：http://dali.fengsongda.top/Article/details/gtzkkuwzzz.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtrdjjbhtd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdrdjxxc.html

Counter(arr).most_common(3)
来源：http://dali.aizwys.cn/Article/details/gtzbclywln.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gtdppsfyia.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gthlgmeqml.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gtljclapof.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtxertzphj.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gtfzuzvwue.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gtvmcztgdn.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtoqvwqwks.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gtbdzxwczt.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtoqfoelhb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gtmkdmsihv.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtoentdnrq.html

pat = re.compile(r"\d+")
来源：http://dali.yj202588.top/Article/details/gtbxlzuaco.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtlihxopdm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gtjjpqgtzx.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gtgnrybsum.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtauyfhpkh.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gtfaifnbaz.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gtqrzkgmwt.html

[U22] Py：矩阵转置
来源：http://dali.yuxming.cn/Article/details/gtlecjstcg.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gtxihecukj.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtztnllfoi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258.top/Article/details/gtiohigoea.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtevhujjht.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtktrfpfut.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gtzkpanewp.html

csv.DictReader(f)
来源：http://dali.iojbl.cn/Article/details/gttfixzcfv.html

[U26] Py：并发下载
来源：http://dali.yuanzhike.top/Article/details/gtcwqrrina.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gtzudheehg.html

[U27] Py：异步 HTTP
来源：http://dali.hnxiangtu.top/Article/details/gtwlpqsfxi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtbhszuexf.html

[U28] Py：类型别名
来源：http://dali.ehwqpu.com/Article/details/gtldhppymz.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gttomngttc.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtymvvpkqn.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gtdjawzvee.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtvcholiqx.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtiysajbeb.html

[U31] Py：单测
来源：http://dali.yj202588.top/Article/details/gtjzsbskfy.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gttsyhoohn.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gtqmthtaon.html

ruff format . && ruff check --fix .
来源：http://dali.birdmap.top/Article/details/gtzfgozsmp.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gtawvpalik.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hfpthk.cn/Article/details/gtnjjtwzqf.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gtyhhqwgtf.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gtosxbkkkw.html

[U35] Py：发送邮件
来源：http://dali.sxryk.cn/Article/details/gtyduikawz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsyihruc.html

[U36] Py：定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtiqdcxsms.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gthkcdilzv.html

[U37] Py：读写 Excel
来源：http://dali.aizwys.cn/Article/details/gtnubwknco.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gtkpxxrisk.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gtbvxcnwbg.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtvdlqizfz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gtigxnoviu.html

sys.stdout.isatty()
来源：http://dali.bjfxy.top/Article/details/gtlkrmomzt.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtnqgvbylb.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtlwrujwej.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ydzc1.top/Article/details/gtnwbsutzj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gttinusarc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gtotpsoiij.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhlvumlu.html

[U43] PHP：声明命名空间
来源：http://dali.dianchejie.cn/Article/details/gtjtnyniqu.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gtensdsphb.html

[U44] PHP：开启严格类型
来源：http://dali.chenlongwang.top/Article/details/gthsagvsnk.html

declare(strict_types=1);
来源：http://dali.tian-w.cn/Article/details/gtutemavua.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gtgfookjft.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcfbxocd.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtqjcytzgq.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gteabfpvvd.html

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gtkqoiektm.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gttrwhudlf.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gtsciuhxhv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtuvtomiqg.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtolccojcx.html

public readonly string $name
来源：http://dali.gaohongyu789.top/Article/details/gtlbaxginy.html

[U50] PHP：构造器属性提升
来源：http://dali.fengsongda.top/Article/details/gtilhmcqwo.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtcijgxqfd.html

[U51] PHP：数组解构
来源：http://dali.shuidangran.top/Article/details/gtbreufifu.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdgdbfpn.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gtcwwlpsmr.html

$double = fn($x) => $x * 2;
来源：http://dali.bjfxy.top/Article/details/gtxpqerabp.html

[U53] PHP：空合并运算符
来源：http://dali.ehwqpu.com/Article/details/gthlsdrinn.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtzwtuwjia.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gtudzkxvdq.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtrpipqjwh.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gtojkzqnrd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gtqlfwldll.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gtbcrznxnf.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtjvvkpgjt.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtbyhdapzr.html

"值: {$a}"
来源：http://dali.wangdashe.top/Article/details/gtnsfgjguh.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gtweakhzga.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuanzx.com/Article/details/gtycfjggsf.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmulvxgam.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtgvihwiql.html

[U60] PHP：JSON 编解码
来源：http://dali.feifeiyinyue.top/Article/details/gtlbipxbgj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtybrtmxba.html

[U61] PHP：正则
来源：http://dali.pengpengdd.cyou/Article/details/gtfvqiavlh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtjthuofuq.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gtsrmlybfy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yonumen.top/Article/details/gtlftvxjho.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtcxfkvtli.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ehwqpu.com/Article/details/gtrqwnhymn.html

[U64] PHP：目录遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtgdjadoop.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cheryme.top/Article/details/gtoglbaour.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtmjcngazc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtsdxulrbx.html

[U66] PHP：设置 Cookie
来源：http://dali.shuidangran.top/Article/details/gthlnmaapm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtduliccul.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gtogzdkaqx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gtotqytsfz.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gttlemwwyv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gtancdzajq.html

[U69] PHP：PDO 预处理
来源：http://dali.gogol.net.cn/Article/details/gthzqwfsac.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.aibaodan.cn/Article/details/gtquatlcwr.html

[U70] PHP：PDO 事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdpqnkme.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtmtdgcayg.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gtmxiyabbl.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gtqlyljjjs.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtvmtfyxqc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tanke756.top/Article/details/gtbaiqavoz.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gtkeuvawvh.html

parse_ini_file("config.ini", true)
来源：http://dali.cheryme.top/Article/details/gtbsbhpcnq.html

[U74] PHP：读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtcbxhpqbv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtslubzmoh.html

[U75] PHP：依赖注入
来源：http://dali.cheryme.top/Article/details/gtzxvsjfld.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gttxjycsyt.html

[U76] PHP：简单路由
来源：http://dali.ydzc1.top/Article/details/gtpbxpktbf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.meibo888.top/Article/details/gtxiafbtym.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtlpoqxxls.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gtfpwwceru.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtaexvpfvw.html

composer require --dev phpunit/phpunit
来源：http://dali.yvedp.cn/Article/details/gteskuytsr.html

[U79] PHP：静态分析
来源：http://dali.yonumen.top/Article/details/gtpawcjlxw.html

composer require --dev phpstan/phpstan
来源：http://dali.pycfn.com/Article/details/gtsltxmuon.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtorjynigr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dashuyun.cn/Article/details/gtfrntrdtk.html

[U81] JS：初始化项目
来源：http://dali.hnqzz.top/Article/details/gtxtgckfwd.html

npm init -y;  npm i express
来源：http://dali.havefunace.top/Article/details/gtucsutthv.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gtlyjinwlo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gtpqnpeneb.html


<!-- 参考信息 -->