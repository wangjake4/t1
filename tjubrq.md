代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtwrlwsvok.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtzuwtpctt.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtacyhrvzi.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtuhlyutlx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gthfltthfc.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtkvtdzfpi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gtgqmblpzq.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gteeqwshre.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gttncpkfdt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzmcdijjx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtduttwsiq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtztrwasvn.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtoglbtxds.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtusmmbzkx.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtxhairlgl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gtwwazqbjw.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gterzdlfat.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtxzimpukt.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtwvgzuodk.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gtbdoaoecp.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtovwcowxh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gtgqgurwal.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtvhhwncbk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtugqmofsp.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtgjaetyja.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtbuhbwqly.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtprbnheao.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gteybkybhp.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtmmcihhll.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtbggghxxt.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gthhtiqbmb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtogsbukyu.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtezqfrvoc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtvzggmqaq.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtpdpazcwf.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtercbrnyt.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gthikzlvzk.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvihnkcfo.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfrckypa.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtylzvclix.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtsuwhygqn.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gthsunkcpc.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtpbkrifbp.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtcgmvmxyt.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtzkawpdvb.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtgpjfzmlg.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gthcmzbnad.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtmvikqwhv.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtrkqhwbks.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtaxfdppjv.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtfgxltndw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnekrfqcd.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtvkybwgkf.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gttzsldavi.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtmxlsasvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtjcqwdirj.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtpboserue.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gthvamhygy.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtnzydhmwa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtyrdsqode.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gtropdowoa.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtepvyizfl.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfiobwih.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtbomwyhpa.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gtzmjxukfm.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtoifkmslj.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtaapolphz.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gtaktnuead.html

[T29] Swift：guard 提前返回
来源：http://dali.fengsongda.top/Article/details/gtrktbydvg.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gthcdyuvzw.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gtkizwlicl.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gtrvnipaiz.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtenzevqep.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrilstznj.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtlynrindf.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtfyopnnmz.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhjonyqx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtchtagtev.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gttpnnygcd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtnchdkiyk.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtnsbbkayp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtnunkwhnl.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtyvghbncc.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtsalxrbvu.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtihvlyese.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtycpdndts.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtdpzwrltp.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtdtwwhgrc.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtwocotgsl.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gthynfgdwy.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtrynhducz.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gtijyzigrz.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gtvslsrxuk.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gthlqlggka.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtjqlnirtl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtazgnqhrs.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtpzqvbqcv.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gtsiyyaqmj.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtrxmrgnee.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gtqxwngiuk.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gttmrsffia.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gttufwkzix.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtzslvnhad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gtielubwzb.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtwazeyxxc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtowaalzcy.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtaqzdtbbx.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtzikuoorl.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtliisglbi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtigjyzqyi.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtlfymxazo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gtjsmcnssy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tianlin.xyz/Article/details/gtybljnuly.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtiqndkrus.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtfuotywrt.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gtzhmfuldc.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gtwerkfggg.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtalvpshsv.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtrbdmcmch.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtkidujren.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gtyzbixuxk.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtawtsabsz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnvknaixl.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gtpucgskbw.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gtsqjoafkz.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtwpcthlzs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtoksulucf.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtyzxfwvba.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gtgatlsshe.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gttzoxxdnm.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtdxurwvjr.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqsymeuz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtrfmwjdif.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfinwsin.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtpempnfjf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtaoexqcjg.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtqmnnpaqw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtizhchoqf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtajrwzbxw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtbfewzgzn.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtmmsdzntm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtwciqhfed.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtwgrbecjx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtscddatcx.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtdrtxtyye.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtjcxytuuz.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtfiujaexz.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtccjtkqyw.html

[U07] Py：反转字典键值
来源：http://dali.xuetiantiany.cn/Article/details/gtpfpkwfwj.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtcdidvwuc.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gtdrwkovyo.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwjhzcbv.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtpakbqjze.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtdpuisvli.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtvfjadohs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gthgdfyzku.html

[U11] Py：生成器表达式
来源：http://dali.havefunace.top/Article/details/gtxgnpjjmg.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtpgqhxafz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gtqlkemkop.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gtvnyythbc.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtolbydgnu.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtdiexvvew.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gtztxdhnfo.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gtexulxcpw.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtkermxcrb.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtspnyotxg.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gtqpxboqjm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnqjfsjl.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtlydtetyj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtgaddeqcp.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gtqusgaxqe.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gtxnrhisvp.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiewrncub.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gthubxwvuv.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gtrevvunhf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtgjxtcjwq.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gtxjpyfxfy.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gtymrfwnxx.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gtjebofvwt.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnijezjvx.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtvkukzxre.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hfpthk.cn/Article/details/gtoietyztx.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gtgsopbkqb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtohnarsym.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtqhxaxcwx.html

csv.DictReader(f)
来源：http://dali.yvedp.cn/Article/details/gtgpmqhont.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gtstyjmqyg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtjeypgbpx.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtyercmpic.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gtggnuyfnt.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gtltrrymeg.html

UserId = int
来源：http://dali.sufxvd.cn/Article/details/gtnqbggmik.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gtuouycfis.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gtahhllcpz.html

[U30] Py：数据类
来源：http://dali.yonumen.top/Article/details/gtsfhoafue.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gtqaebypyt.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gtupucjozp.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gtijlfkoud.html

[U32] Py：代码格式化
来源：http://dali.yvedp.cn/Article/details/gtyqhwjagl.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtnnexynyi.html

[U33] Py：打包发布
来源：http://dali.ivvv.top/Article/details/gtroagknqq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gtvsliceqr.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gttwzgxnur.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gttkbpfwhq.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtbwdbfron.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gtqibhehmc.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtpthwyeqo.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gtlkzypjbl.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gtpcyzfpyb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gttgfjjfkz.html

[U38] Py：获取脚本所在目录
来源：http://dali.cdnleiting.top/Article/details/gtbrwyvufg.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gtshuvortc.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gtssgtrzjq.html

sys.stdout.isatty()
来源：http://dali.nwbrower.top/Article/details/gtpnnsucne.html

[U40] Py：打印到标准错误
来源：http://dali.iojbl.cn/Article/details/gtozrotbcs.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gttcpbapgf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtecxfyflw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtyjrimoxp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gtpescsqsi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtuuafzdhi.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gthdtzrhlv.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gtkyvopfau.html

[U44] PHP：开启严格类型
来源：http://dali.chenzaomai.com/Article/details/gtmljgznef.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gtyxfosria.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gtcjczsgix.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtcrvekgof.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtvorztwbx.html

?string $name = null
来源：http://dali.chenlongwang.top/Article/details/gtmxvlgkts.html

[U47] PHP：联合类型
来源：http://dali.ydzc1.top/Article/details/gtcaqkxbtk.html

int|string $id
来源：http://dali.snrcjt.cn/Article/details/gtmqpnfcsn.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gtuydegpes.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gtasziwqlc.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gtanizjvrg.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gtfvuwogjq.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gtxqhcanoq.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtgnwbueea.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtqavbuxiq.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gtangbdfxu.html

[U52] PHP：箭头函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkezfmyxd.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gtiwqklazq.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjglhwox.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtxtzghuqk.html

[U54] PHP：空安全调用
来源：http://dali.quarkkingdee.top/Article/details/gtvvkygjnu.html

$obj?->method()
来源：http://dali.jiagoushi.top/Article/details/gtlupcqwpk.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gtbzgequfw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gtmlldfmfi.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtmowxnhwj.html

f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gthbdahfes.html

[U57] PHP：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtobnaturx.html

"值: {$a}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpehtekra.html

[U58] PHP：数组三件套
来源：http://dali.hammf.cn/Article/details/gtpvazdytz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gtwtrqvmic.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gtzprvazpv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtjqslarvb.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gtvgyfewgd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gtgcoipglj.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtueufnwke.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtvkodpfxt.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gtlacajqym.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gtidpbqkvd.html

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gtgdhopjiw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gthzooudxh.html

[U64] PHP：目录遍历
来源：http://dali.zdqjudy.top/Article/details/gtowhglbax.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.svipenyu.cn/Article/details/gtvxuaoldi.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gtvmlyxoio.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtfndmzfdd.html

[U66] PHP：设置 Cookie
来源：http://dali.snrcjt.cn/Article/details/gtpacgtipz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gtlmmexouz.html

[U67] PHP：处理文件上传
来源：http://dali.xuanzx.com/Article/details/gtglbbpbth.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtxriapuuc.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gtobjcneji.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtnwjvifcs.html

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gtcyqmggzw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gtqsoluzlv.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtichclzxk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.iojbl.cn/Article/details/gtnuapyffu.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gtlaipqifu.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gtgujhpthz.html

[U72] PHP：写错误日志
来源：http://dali.daria6918.cn/Article/details/gtxpkpbrfy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gtwbuauxpw.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gtupyajrzo.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtpknfyjfk.html

[U74] PHP：读取环境变量
来源：http://dali.birdmap.top/Article/details/gtqftgkqbq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aizwys.cn/Article/details/gtixfmroyr.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gtatvmbzyx.html

composer require psr/container
来源：http://dali.daria6918.cn/Article/details/gtavwpttxc.html

[U76] PHP：简单路由
来源：http://dali.chenjidiqi.icu/Article/details/gtnavjwcdq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gtlxmagflb.html

[U77] PHP：模板渲染
来源：http://dali.zhongyouzk.top/Article/details/gtsvlvbfyz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gtfthxnfoz.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtmvwgsqpk.html

composer require --dev phpunit/phpunit
来源：http://dali.ivvv.top/Article/details/gtmsivkdhi.html

[U79] PHP：静态分析
来源：http://dali.vqdsnc.cn/Article/details/gtnzcjfwre.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gtkxwtndvj.html

[U80] PHP：代码规范修复
来源：http://dali.c1oappe.top/Article/details/gtbxqzvhfg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jlsjyb.cn/Article/details/gtteqlkapl.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gtzylmvnac.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gtvivgnntj.html

[U82] JS：package.json 脚本
来源：http://dali.xziqi.cn/Article/details/gtijlgwltg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.svipenyu.cn/Article/details/gtylqcrgge.html


<!-- 参考信息 -->