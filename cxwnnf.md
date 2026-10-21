代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtqbzpsoum.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtnpdrdqdh.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtwtsfamnb.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gtmbjskojy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gthaikcjqx.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtpuswhqeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdyrwvyh.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gtasrlhqtx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtalaidueo.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtnnbxpqly.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtclywyjvf.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gtthyngyid.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtingdvazr.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtfrunqeng.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtjrgncdix.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtrzhmmihg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtbqpixdzz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjmipdway.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtlrqcpeqq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnykhcqbr.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtrjndjubb.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtfjajjbwe.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtjxrrpqng.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtweunhvvg.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtsvlkleac.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtzkidtgfb.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtzoteeicm.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtojoyuyrs.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtkxomehrn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtzxzmjzhw.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtgwttycax.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtmhqsidwn.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtqprfsfep.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtuipieodb.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtmcdjbpzm.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtpsrbcdvb.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtndmkfshi.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtpcigehus.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvmkgwtu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtbwnhunmx.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gthfeyooty.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtltiypruw.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtajngkvnr.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtfkfvujiu.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtergfefmm.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtziqaybnw.html

[T14] Kotlin：循环
来源：http://dali.snrcjt.cn/Article/details/gtvxbznpjn.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gtotkxhjdl.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyqpgflj.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtompkeojp.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtnniwnnxr.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtwkpyzqfo.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gtgjbzcwjr.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gtugkuuddr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtjxphgiwc.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtneokvagv.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gtwjpvrxds.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gttxvhjtxl.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtmwthutrl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtxriswlzt.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtnuzjpluo.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gtywiejraf.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtjwtklfyb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyrxscyl.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtlnngayfh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtamegauwe.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gthshcrsrk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtkmniuczx.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtwvizrrrz.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gthapqkssj.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtjmutpawe.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gtqexwwqen.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtwdvgqoip.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gtqnlwpbyb.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtonutggnm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gtsdfvsura.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gttjwhruxc.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtovmjaume.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtcibnewpp.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtfumkjvmu.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtstljyplq.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtbprinqwl.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtovdbysqy.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtntfbmhiz.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywzvrtqs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtbgprzonl.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gtlgpgvwpv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtmtieknop.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gtddteewwk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gtiryplrwb.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gthexedagr.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtrzynmaah.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtkqbrvepy.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gttmpfaoht.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtyydasooq.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpcibtti.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtdcvxykfl.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtcbcndehf.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtduwravyb.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtlhnqhvxt.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtcpmapjhw.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gtonqdvdvs.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gtrrwvdukm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gtxikkhltk.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtlglwzuts.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtmruppxwp.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfmbkyim.html

if ($a > 0) { print "正"; }
来源：http://dali.jiagoushi.top/Article/details/gtqwntghob.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtzywlvhfa.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtigjwuoyy.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmigygmgz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtngebkwxw.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtgdemilnu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gtyvhrtrya.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gtvczxnpnw.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtydjtvodg.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtzztefyzk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtumleavej.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtvizhegty.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gttwrofbso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtsdnrypvf.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtxnpbqfmq.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvhczgid.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtufomisno.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gtrublouzr.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtniaantoc.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtzslvlrui.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtkgzvhmya.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtaeqxiwma.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtptrwqstp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfqgjsjhx.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gtjxshohkz.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtmifevffx.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtzbrfwamp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuipcdyz.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gtxqcgrdhk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtkrlfskmz.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtwqopwhdo.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtxptzwnrp.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtnodghmpz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfsirptp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtudlsstyi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtoktzbbdy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtagdgejdf.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtafzrscsu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtpuvlfjxj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtpxgpbgzy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gtiblvlcqs.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gtaaqtesmb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtkpydhjrz.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gtziuwuhpa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtvtmyzqnk.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gteugzdkls.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtltnaayto.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtmnpjrbhm.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtltnxvwfo.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gtktlgzdze.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtgvpkbboa.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gthfahxdhv.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gtvaqfbezs.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gtaterpypt.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gtcgyquhpf.html

[U10] Py：按值排序字典
来源：http://dali.yonumen.top/Article/details/gtckkmhnrn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtevwlhpub.html

[U11] Py：生成器表达式
来源：http://dali.316326.xyz/Article/details/gtdcgoogei.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gtepienrny.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtykddmzpk.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gthvxlywmb.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gtcmjpcvfq.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gtgkwsqtdc.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gteuncjrgb.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyadenpvu.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gtibodxkrl.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gttllnexfd.html

[U16] Py：命令行参数解析
来源：http://dali.ehwqpu.com/Article/details/gtkdkzbrsy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtkeqhlmzq.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gttosmmxos.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gtgxbjlrjx.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gtyuolhtwu.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gtbhmcumnk.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtmouxjvtz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdajourri.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gthylaibwt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gtgpiloqgo.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgneegdj.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtukuklmrv.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gtvqkdtbfq.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gtrwprtaem.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrfpvotqx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtnusxchil.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtwzhuuukg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtmelusrrv.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtbjcovngo.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gtqwwlgqsq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gtpxlemiau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.kuanghao11.cn/Article/details/gtxksqwjtl.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtuboyslcb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtrrahhuto.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtxforlzpp.html

UserId = int
来源：http://dali.xylfe.cn/Article/details/gtgivytmke.html

[U29] Py：属性校验
来源：http://dali.tanke756.top/Article/details/gtesefjlrt.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gtodepvsaa.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gtvuaaxwie.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtzoyvulyw.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gtnesrxrct.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gtjilvegvl.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtvvgvaqhf.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtehhghftz.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gtutscfsym.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tianlin.xyz/Article/details/gtdcdsjqkr.html

[U34] Py：判断编码
来源：http://dali.wangshuangyany.cn/Article/details/gtnndktskk.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gtaguyhwlj.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gtaoexdmgz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gtthnfllkv.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknetsehy.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gtbbygbmdy.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtiayhdkqa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gtleamumwy.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gtlfaodpbm.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtrvqmccji.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gtpmduzsga.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gtrbtzkysh.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtzsjnsdwj.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtwsfdohne.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fengsongda.top/Article/details/gtxozawggv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gtyudfjecp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gtzfydfdgk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gtpitonipa.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gteuvbjoeo.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gtexxpzvyw.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gttmvippsc.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gtgvtxxbpk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ybcxt.top/Article/details/gtsbndlkyi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfbamuhyf.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gtdljojdrd.html

?string $name = null
来源：http://dali.zdqjudy.top/Article/details/gtuumceztt.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gtexcfmmcx.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gtisshbpyr.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtcznsggnn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueaxfsbj.html

[U49] PHP：只读属性
来源：http://dali.quarkkingdee.top/Article/details/gtijnhdigt.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gtvhbkwxhs.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gtlqhgwbvo.html

public function __construct(private int $id) {}
来源：http://dali.nanxuanxn.top/Article/details/gtzyqiokig.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gtkamfcfnm.html

[$a, $b] = $arr;
来源：http://dali.ehwqpu.com/Article/details/gtdtlakeaa.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjevcihp.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gttroztyuk.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gthqoyyouw.html

$v = $a ?? $b ?? "default";
来源：http://dali.sxryk.cn/Article/details/gtxrrmmyyw.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtuaozoaip.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gtyglpznno.html

[U55] PHP：match 表达式
来源：http://dali.cashguo.top/Article/details/gtzframett.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtgrjgfufx.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjsnwzpi.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtdjupdgzl.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gttnklydvz.html

"值: {$a}"
来源：http://dali.fzhhl.top/Article/details/gtvrxkhkny.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtbjqjmgtg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtgcoryuub.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gtlskbhfjb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gthhbuemlv.html

[U60] PHP：JSON 编解码
来源：http://dali.cheryme.top/Article/details/gtufovwiqj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gtlnkkpugg.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gtftlpagho.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtptkrtrou.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gtlavszitx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guowangkeji.top/Article/details/gtpztzzjwm.html

[U63] PHP：文件读写
来源：http://dali.wangshuangyany.cn/Article/details/gtueqleila.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenlongwang.top/Article/details/gttygnfuel.html

[U64] PHP：目录遍历
来源：http://dali.birdmap.top/Article/details/gtywdqivnw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gaohongyu789.top/Article/details/gtfvmioklt.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gtsntontjc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtulqrihbp.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtrgcbngkv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hammf.cn/Article/details/gtgpbzdlqo.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gtzuoahlqa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gtfdtrdgbj.html

[U68] PHP：PDO 连接
来源：http://dali.jqgfzy.top/Article/details/gtavwqwtgp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtzeuxcnhl.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gtvsrzcowc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gtqhtpupuf.html

[U70] PHP：PDO 事务
来源：http://dali.wangdashe.top/Article/details/gtclmfpvyv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gtltodctjy.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtjiawojtv.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gttosbamgp.html

[U72] PHP：写错误日志
来源：http://dali.hnxiangtu.top/Article/details/gtbcjehubm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gtudtdbspc.html

[U73] PHP：读取 ini 配置
来源：http://dali.guannengcc.top/Article/details/gtgawbcnle.html

parse_ini_file("config.ini", true)
来源：http://dali.cdnleiting.top/Article/details/gtmzzulomx.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtmruwnqyb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dashuyun.cn/Article/details/gtpasalbdo.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtskhbhovr.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtroumrevz.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtxedpksyz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.kuanghao11.cn/Article/details/gtirdgojdi.html

[U77] PHP：模板渲染
来源：http://dali.ehwqpu.com/Article/details/gthzqastyx.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gtebkwkzrg.html

[U78] PHP：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtekdfqqat.html

composer require --dev phpunit/phpunit
来源：http://dali.hywenlv.cn/Article/details/gtrvjxsjrc.html


<!-- 参考信息 -->