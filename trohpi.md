代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtgqsxhwih.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtfnyaegmo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtgzoquewr.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gtueizrsjo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthclmhgqf.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gthumcoaik.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtgjxffjgr.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gtawoernqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtlugcehnn.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gttmvmfkjs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gtrlvvtbon.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gttmbsvfah.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtwwpljswp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoecrtgwi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtfgvecaqq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvjnjrvgv.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gtsvoscisy.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmxsfzgz.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtxerzurio.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtpgrmcjqz.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikxtgaxw.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtsqqadshu.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtawkibhzg.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtvcydsfdm.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtuwguyhwn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtwqtxzesc.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtnwiplalt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtxhfzacgl.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtrhrqboea.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gtwraqcpwq.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gtcqvtbsrg.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtrsbmjpny.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtxzrvwbiz.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gthynyfcot.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtdwxsjwmq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtkctydyge.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtqddzvqqd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gthgldkytn.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtrprsmqks.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtlamrrgdw.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtdbxczjwr.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtypkitnob.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtdmkpnkra.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtzjmndcxi.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtszdolgtg.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtjrgxjwea.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtwmgzqsgw.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtuqulflbl.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtgwtpmwwd.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtkvzhcovc.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtjinmnzed.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyecywskw.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtqgtnwaro.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuulvxtwm.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtwnbkmhyu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtxpjrlmal.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gtlzgjfzod.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtmosfevri.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtizkfphli.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gtzmyqajkq.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtcwncvwpi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtjpyyzsmz.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gtwzlpmwjg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtyrduegbh.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gtgpyimvud.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gtjenrnqqb.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gthltpynww.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtpaamijcn.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtfokwjsqf.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gttpupyicr.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtvanwrwde.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnivgzvh.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gtyaoqgsaw.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqvdjnos.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gtdvwmvpnm.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtxixpmhgr.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtzwrqrjml.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtvftivaiy.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtaxhoqtqk.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtaomxjivs.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnivhxqz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtwwwmrxhd.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gtpxwtweyx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtcswvlyrh.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gtrqewphnf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtcytnfc.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gthxtzmgjy.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gttrhwuhrp.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtwtkmbpsk.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gthwgjmysj.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gtvlswgzth.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtmxaohgqn.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtvnuszjlv.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtkzhqigjv.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtvscicjup.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtzvgusdwp.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtxkmdmnjl.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtcwgvpdau.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtgxqiwtpy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gturpjpcqg.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweqpfzix.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtggpurrws.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtjtbyinwn.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gtapurylsj.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtxyuveqme.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gtmjlpipvd.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtkuvdmgsl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtdwndfzoi.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtrjuwczim.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtetpphqxd.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gtyezaqnuc.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtttytorac.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtaltcsulf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gttumrmowt.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiayabbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtjlifqwav.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtnhvrchrw.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtqlxbptov.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtbuycmlhi.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gtytwqpbjs.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtrbbokzae.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtvobgartq.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtknrvmkma.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtpiiqznrq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtcnfzhhgm.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtiiifwwjr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtadsgtzso.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gttmuaqzey.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gtqwqxhbqf.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtmdcsvcce.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtutlgrfgd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtkewqnhxb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtyyqadery.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtzjrabkqu.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtsdtsaglo.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtlzlgulqx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gtcthlupxw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvbgjxsaw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtjpygutfy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqwkvpzac.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gtffssmixa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gtvcntyymz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvsgvtlj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtrkddleaz.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gtnaddoghr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtfiyarcis.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtltxpqzhf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtwdquprdf.html

[U05] Py：列表去重且保序
来源：http://dali.meibo888.top/Article/details/gtvytsnsqh.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtwdrxexhg.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtnhaujcks.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtyzbgnaxv.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gtptsdlfwz.html

{v: k for k, v in d.items()}
来源：http://dali.316326.xyz/Article/details/gtxgqqlpza.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtrpthuayh.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gtceqjazcs.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtxjbcqbxt.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gthohybrye.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtyvqrxlxs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gttdynfniu.html

[U11] Py：生成器表达式
来源：http://dali.havefunace.top/Article/details/gtkoahuvaz.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtemvxtuga.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtgzaezriv.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtrcwpirrt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gtghfebfxn.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtlajftkpr.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gttczibicd.html

defaultdict(list)
来源：http://dali.gaohongyu789.top/Article/details/gtrqrgcopc.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gtodirsyqn.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtjieigjul.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gtgjfjpwjn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gttmkykvmz.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gtyucvtell.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenlongwang.top/Article/details/gtbtaalypb.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtqhryxwir.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmzmixaq.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsduphyx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gtsjucmqkf.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gtpucdtazl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtxxmggttb.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gtwaaxdkqy.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtktsqxife.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtuunqnqnn.html

list(zip(*m))
来源：http://dali.yangfankeji.com/Article/details/gtpzaccrya.html

[U23] Py：分块读取大文件
来源：http://dali.sysykeji.top/Article/details/gtmnfclxgp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gtuniyaquc.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtkauopgjx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtldeooufb.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gtledoetax.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmofwxrvq.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gtkddxvtqd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhiwuduotai.top/Article/details/gtkybgzlnf.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gttffdxonb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqpkyvxv.html

[U28] Py：类型别名
来源：http://dali.ydzc1.top/Article/details/gtyqkhzriv.html

UserId = int
来源：http://dali.zhoulong.xyz/Article/details/gtchdqafae.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gtsmhvcjzd.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtpqoabusq.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtqjscsdiw.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gtstbtkhwy.html

[U31] Py：单测
来源：http://dali.yj20258.top/Article/details/gtyosqnhyi.html

python -m pytest -q
来源：http://dali.shangyingyoupin.top/Article/details/gtrfwzunti.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtaayaseif.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtcyhgmaai.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gtysifesap.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtzarcuxws.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gtupxdpxps.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gtoqkjuixh.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtoncinaxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppqxmppe.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gtgevawkbh.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gtfikcnnkq.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gturlxgvfk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuanzx.com/Article/details/gtgaweqwlz.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbpgwwwn.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gtuivvddww.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gtvgmtnrkf.html

sys.stdout.isatty()
来源：http://dali.yuxming.cn/Article/details/gtcsofymps.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gtryfxmkeh.html

print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvgdsxou.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.birdmap.top/Article/details/gtyjuyhbzk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gthcznepjb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtexddyirv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhixingplan.top/Article/details/gtqaletaqb.html

[U43] PHP：声明命名空间
来源：http://dali.xinyue.icu/Article/details/gttxhpomnn.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtianxhmva.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtdzjrjwke.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gtipgcmdfq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gtzefrnijj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqdvxanvd.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtrzzbjdpt.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gtpwjoitgd.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gtfmhbwclz.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtehfmbtji.html

[U48] PHP：纯枚举
来源：http://dali.aibaodan.cn/Article/details/gtcammbtyx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gttbkrlymc.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gtgaaodhoi.html

public readonly string $name
来源：http://dali.yvedp.cn/Article/details/gtdedgzkxu.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtizeeucpc.html

public function __construct(private int $id) {}
来源：http://dali.iojbl.cn/Article/details/gtwdpomeqx.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gtpyggapgk.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gttpkqiplr.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfjvsser.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtsejurpfj.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtaaglvdsw.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gtxambenwh.html

[U54] PHP：空安全调用
来源：http://dali.jqgfzy.top/Article/details/gtwlicucoj.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtmcwswevc.html

[U55] PHP：match 表达式
来源：http://dali.shuidangran.top/Article/details/gtikyekrqp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gtcfvelitg.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gtxblhzmwl.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtezyinzmx.html

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtiqazkyzd.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gtrkknnytb.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gtoyworpxa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jianghu66.top/Article/details/gtuastjkxs.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gtjnerdgit.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtyfsolacl.html

[U60] PHP：JSON 编解码
来源：http://dali.daria6918.cn/Article/details/gtimuozwsp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gtafbbposg.html

[U61] PHP：正则
来源：http://dali.yueranfly.top/Article/details/gtydllzzwl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtupsbihgw.html

[U62] PHP：日期对象
来源：http://dali.smart0.xyz/Article/details/gtkrkihyji.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgfzy.top/Article/details/gtxrnjctkf.html

[U63] PHP：文件读写
来源：http://dali.zhiwuduotai.top/Article/details/gtnxootpzp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hammf.cn/Article/details/gtuajntmcq.html

[U64] PHP：目录遍历
来源：http://dali.vqdsnc.cn/Article/details/gtthyqvxfn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yvedp.cn/Article/details/gtoixsysuo.html

[U65] PHP：会话
来源：http://dali.andypj.xyz/Article/details/gtbwjsravf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtvgfqmhdt.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gtkfpauqwe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gtjegfgkav.html

[U67] PHP：处理文件上传
来源：http://dali.tian-w.cn/Article/details/gttthbqvpj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gthpjlwrvg.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtkyofnnlv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gtrglnkowk.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gtzpicieny.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gtvpppilsf.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gtgsffjdzd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gtceaybiwg.html

[U71] PHP：抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtqmyvderr.html

throw new RuntimeException("失败", 500);
来源：http://dali.haohaochexian.top/Article/details/gtedsdlwmc.html

[U72] PHP：写错误日志
来源：http://dali.meibo888.top/Article/details/gtsbqhyckf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj202588.top/Article/details/gtdrylgzge.html

[U73] PHP：读取 ini 配置
来源：http://dali.snrcjt.cn/Article/details/gtqwzmofkk.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtwozeidwv.html

[U74] PHP：读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtpwhhthez.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jyoumei.cn/Article/details/gtpmoglhwb.html

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gtabellxis.html

composer require psr/container
来源：http://dali.chenlongwang.top/Article/details/gtbpckpfvk.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gtwescahvp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtpfislvaf.html

[U77] PHP：模板渲染
来源：http://dali.yj20258888.top/Article/details/gtooznadii.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gtjsdeqenp.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtmssnsquy.html

composer require --dev phpunit/phpunit
来源：http://dali.hammf.cn/Article/details/gtvbqomgry.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gtrytecqix.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gtdvgbiyyc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gtjgedspjl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gtqiulsjkr.html


<!-- 参考信息 -->