代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtfqaptnqv.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtqmpvuilx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtqxyniulg.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtmvhwswed.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtthtimkot.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtcizrpuis.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtndnwgvux.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtsuadaiiu.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtknwdhwso.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtrnxnqclt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtqoghskoj.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gthudnqmkm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtbuurgjbb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsaeqygkz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtrnmryrdy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnffujlsr.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtmazehhsx.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzdkstdx.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtdqgnemrk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtfrdxdfpw.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtwsvkyfmw.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtarorxbps.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtdkkepkbh.html

val n: String? = null;  n?.length
来源：http://dali.cashguo.top/Article/details/gtjrqdwzml.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtowvowwil.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gttzqzuqtu.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtwerdowiq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtjdcehirp.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gttuwowedx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gtnfimgqqv.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gttarziexs.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtycsxbbrg.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtbtsqgitm.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtmacvtehl.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtbgvtzgty.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtycsdwokk.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gtkldihobb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtsnawiibs.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzaokxwn.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzwcwbdh.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtgahohffr.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtusjtmdgo.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtulkgpmvl.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gteigoriju.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtnwzmidzt.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtvgguyuah.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtvnuocdts.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtfhwjvwne.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gtlquldojc.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gttdegqvwi.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtjeobosvv.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtincetkfr.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtlqrptuyw.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gtyvaigyjy.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtyenfetrs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtblpdndco.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtvothikdn.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtyrolptii.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtkuwjecae.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlgmfyad.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gttyesboch.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gtvfwlsbrk.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtdnaifkds.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtxbkwnvex.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gtobaozkfv.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtmdlwffea.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtvxvncxxk.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtrbkhfmvq.html

[T27] Swift：错误处理
来源：http://dali.jqgufenzy.top/Article/details/gthrjayaea.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gtunlkmxuw.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtztiwqnxj.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gtcapggdzw.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtuzlegxqp.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gtmjlbxmgr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtsqkziofg.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtoarwrkkb.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtzuhdjitl.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvixuwkwt.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtzerjosko.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gttoehnfeq.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtxooeubmb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtexqfhrkx.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtnthavijv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtlhdpeclk.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtsbmtgrlg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gtcckihfoe.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gtagjwlpol.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtravbcpzi.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtjlfbzkcz.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtxyyxjbea.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtlwuegkqq.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gtkhpvbspg.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtvdgcjfya.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtrdsghqff.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtkswcwomg.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtczuwwbfm.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gteefbgjgc.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtyuqthnuj.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtpnicxxis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtrbavuugp.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtjccngcdm.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gthuiivswe.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtartntesn.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtpybmmybr.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gtwnatzabx.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtumvhzirb.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gtbhmbqmzf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtcujtzuqa.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtwjqtbbuq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtacnlnqby.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsfpswvwo.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gtfosvzksd.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtywcqopzp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvbiwupvw.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtqzzhwnlo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtccbcfcgr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtlunzoewc.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtbnbrecjd.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtssvbjzdl.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gthbqeamhp.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtvzrozqmx.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gthwkesmnf.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtrvjaxtww.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gtsnebyzqp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtklcbifxv.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtrausspec.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtnmpuccie.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazqpivll.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtvaovagfy.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gtdntuahdy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtwgvdilcy.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gtepeacusq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gturhiegbf.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gttdhvbziq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtzdfqfvdh.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnnahmjo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtyscqiqxh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxsrnqrre.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtedcsikbt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvlquihos.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtuvwmahjs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnhgyvcj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtbotcpewa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtvhpdrufv.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtqmdyoxah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gtsdsicehu.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtszfycuqu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gtrwomqeje.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtrvsjcfqg.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtzmxwumgv.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtsvfnojbh.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtjshzmbzw.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gtyzgozzho.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtiibbneji.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gthpouyvtt.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtiqqnrxzy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxhtedhu.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtpitznvqy.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gtggujowwa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gtzzyvbjhn.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtgjqzcttl.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gtrcmuyitn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtuefolfmo.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtukwktabh.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gtcsnupqbc.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtrlycxzcc.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gtelsglvfy.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gtezdbrxzo.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gtfhmztnql.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gtffdggspu.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtkxhsbmvj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gthvetpjfo.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gtoilojgpn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtrnfzgevu.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtckaiybww.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gtxvdxdrly.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gtsklzykdn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtbvuvuclp.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtbbcnemkt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpyqwshr.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gtiyqpjtac.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gtlhaoeacm.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gtzgqvntbq.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gtwrcgnaxb.html

[U23] Py：分块读取大文件
来源：http://dali.hnxiangtu.top/Article/details/gtrrnuznjf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtewwistdb.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gtxkcybtmg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtrlshyccr.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtrxsdpxpy.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnrfvnvu.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtjbxnuohx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtkprmtnfy.html

[U27] Py：异步 HTTP
来源：http://dali.xuetiantiany.cn/Article/details/gtqpcmidlx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhsrtrlk.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gthfwavaal.html

UserId = int
来源：http://dali.sufxvd.cn/Article/details/gtppnhwmbq.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtejbtgsif.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gttdokonjs.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gtuvwbfqst.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmkrqbhe.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gthtggbzaq.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gtfnniyhcb.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gtcpirweub.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gtrzqsnhuj.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gtlpdpzdza.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.316326.xyz/Article/details/gtycutkuvc.html

[U34] Py：判断编码
来源：http://dali.pycfn.com/Article/details/gthsypkxwy.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtxemvyywt.html

[U35] Py：发送邮件
来源：http://dali.tanke756.top/Article/details/gtzjxizcdl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtjggaejji.html

[U36] Py：定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtpjyxmgwo.html

schedule.every(10).minutes.do(job)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzirnjbv.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtbechjexe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gtwinrczhc.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenzaomai.com/Article/details/gtsegyehif.html

Path(__file__).resolve().parent
来源：http://dali.jyoumei.cn/Article/details/gtuydxfvig.html

[U39] Py：判断是否在交互环境
来源：http://dali.cqqwz.cn/Article/details/gtsxhznokz.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gtgtrasxxp.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gthcodllqx.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtpjwjrxnu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shangyingyoupin.top/Article/details/gtzauczeee.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cucudq.cn/Article/details/gtkjzwwyvf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xinyue.icu/Article/details/gttzyukfta.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gthaphjspe.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtkfpactgw.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gtwoqcoxue.html

[U44] PHP：开启严格类型
来源：http://dali.zhiwuduotai.top/Article/details/gthuqccodl.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gtpexrsvfw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gtucogfryn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gttaeenvsm.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gttoyjutkg.html

?string $name = null
来源：http://dali.gaohongyu789.top/Article/details/gtfqemswga.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gttcjmpatw.html

int|string $id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwylmfug.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtkopflwrk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gtddekcoyk.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gttvopckkm.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gtgfxdjrwl.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gtfiwruwmy.html

public function __construct(private int $id) {}
来源：http://dali.gotoacloud.top/Article/details/gtilodgjxn.html

[U51] PHP：数组解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpggtxmru.html

[$a, $b] = $arr;
来源：http://dali.cqqwz.cn/Article/details/gtuwzpofdd.html

[U52] PHP：箭头函数
来源：http://dali.sysykeji.top/Article/details/gtmuxkfexh.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtschneter.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvjkmxmg.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gtviudipuh.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gtbrffsgiw.html

$obj?->method()
来源：http://dali.chenjidiqi.icu/Article/details/gtsenxqona.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtybskoapk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsdvkyhy.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gtiisqskbj.html

f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtvpdppxrb.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtqrlygxdu.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gtofttzjlp.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gtcbkmvfmf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gtocvsfdoz.html

[U59] PHP：自定义排序
来源：http://dali.hywenlv.cn/Article/details/gtdotusipv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtuzzpxvqd.html

[U60] PHP：JSON 编解码
来源：http://dali.svipenyu.cn/Article/details/gtqvlgkhka.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gtfhyzfkdy.html

[U61] PHP：正则
来源：http://dali.shangyingyoupin.top/Article/details/gtvrsarbuw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtxojpqxce.html

[U62] PHP：日期对象
来源：http://dali.jinqigfzy.top/Article/details/gtyeokrnwm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtbmvwrjqb.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gtxdyufhgg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgufenzy.top/Article/details/gtqwbnxmqo.html

[U64] PHP：目录遍历
来源：http://dali.hammf.cn/Article/details/gtxvgdhbax.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tian-w.cn/Article/details/gtagwjacse.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtpfdclqye.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtvutxvtnm.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gtppsphooy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tanke756.top/Article/details/gtafczhzup.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gthdkcgrta.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gtmabudwlb.html

[U68] PHP：PDO 连接
来源：http://dali.gotoacloud.top/Article/details/gtouvvzpsy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gtrrrlcojt.html

[U69] PHP：PDO 预处理
来源：http://dali.jianghu66.top/Article/details/gtylipyucb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gtpdaiiqel.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gtjoxhohjh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gtkkjxywtb.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gtyehjfhnw.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtfovsyezh.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gtzccysdvx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtvzviykvv.html

[U73] PHP：读取 ini 配置
来源：http://dali.sweek.top/Article/details/gtybvldojt.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gtvdvhhjsk.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtahxrmcfd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yueranfly.top/Article/details/gtfarbmdxp.html

[U75] PHP：依赖注入
来源：http://dali.pycfn.com/Article/details/gtngszmmmm.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gtzvplbdea.html

[U76] PHP：简单路由
来源：http://dali.ehwqpu.com/Article/details/gtrbmbmbev.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yanxiufei.cn/Article/details/gtqrpnpueq.html

[U77] PHP：模板渲染
来源：http://dali.yonumen.top/Article/details/gttyxyjnui.html

composer require twig/twig
来源：http://dali.zdqjudy.top/Article/details/gtmaeggqfu.html

[U78] PHP：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtszqfrife.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzxnmroe.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gtvdtafttb.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gtvrebvsvu.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gtijqhtrvb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gtpdiujwae.html


<!-- 参考信息 -->