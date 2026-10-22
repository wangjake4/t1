代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtpctdbspr.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtuztzmsbg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtnwatmrgz.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcevxfwgh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtbvirzfsv.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtqsvmbykp.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtwarrjkir.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtjaxlvnko.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaucrdih.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtebketgec.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtuacnbnub.html

[S60] C++：遍历并删除元素
来源：http://dali.cashguo.top/Article/details/gtmybszvca.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtllzcrken.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtidqwcujn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtrqcctidq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtewqjosnv.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtskiubcsa.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtuphjouvh.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtfxlxgaaz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtukmziceo.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gtqtoteyzm.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtnysmuwfc.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtojzdhpeb.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwzljxuv.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtfewqlbqq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtztnvggzn.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtmkkufxjo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtxweouznl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtpolaachb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gteccjshrq.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtmftfrppf.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtupvftprx.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpquqvak.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqliggabn.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtoslxdyox.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guannengcc.top/Article/details/gtisliuase.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gtaqfseoya.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtafaqafnq.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpcayyiq.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtifbvfjvk.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtrzwkzqdd.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtbygacqjh.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gtsdugnpcd.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtgduxkghc.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtsnwovrva.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtlzzjoxxk.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtcvntadpw.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtxsxadevy.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtnnumygfn.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtasmrovnw.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtwnzxxtah.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtkfwzvdtv.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtuzpacjee.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtsxslstat.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtfbbokkjo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtxbrvliiv.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtkegcnzir.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtctwuwykj.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtcfebyjyo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gtpysssoxz.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtswsghmuc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtjfzwadta.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gthomqamzv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtqoxsrknn.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gttixmudmf.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtrjjhbsbm.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtakrwruzi.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtmnaumxho.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtlvflnhlk.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtjoahvamm.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtjlpdwklb.html

enum Color { case red, green }
来源：http://dali.shzxlz.cn/Article/details/gtbhdhtnqq.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtgpnnxafo.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtwtukdrdc.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtpthembjp.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtljfixeah.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtkbzeohgb.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtbjngysfz.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtwafreoza.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtmyrkimfh.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtyzmxzqtx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtrthwewxq.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtgcorxwtt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtupivvfjp.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtvtncigav.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtdkdeadhj.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtvbdnqily.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtlogqilkg.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtduxsigyl.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtqmbbyeob.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtikhkwnha.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtxcyklqpw.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtwtvexgan.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtnstpbfaw.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtyrbuclcc.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtpbpitjmg.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtsivafift.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtfaxmffte.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtybuqieks.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtijdbpkfi.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtivwtdrfq.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gthmnixykv.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gtotnchspw.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtoksivbrb.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtuamxsbxr.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gttmipckbk.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtwzpivdiw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtkmjkjbvc.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gtvskckfju.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shuidangran.top/Article/details/gtvhawpldt.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtwvcabljh.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gtlpmvlnfb.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gtdglfrjjl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtugpgxfwn.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtgdsgmagl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtpdgzjucd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtupysajtg.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtnokjdhoh.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtwidawcns.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gthxdpznhs.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtjofgmevo.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtfilktryx.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gtyamaieut.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtmbawunzx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gtdvgpfiwh.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtostijybd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtadnoakkb.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtiqwikbrb.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtxzqlqvuq.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtaofxzwzv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gthguyhdod.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtipbnjkza.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtotjnvjel.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gtddzmpqqn.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtyvhmojsq.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtwppahvbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtevfcxsns.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqfhmrrib.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtdhrnxvcw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtppfibbjc.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtpvxfttuu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtsleadesf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtulztywhz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfmrlzne.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtvbkteblx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gtmcbpdtdz.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gthbsucjyr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofwrcwkf.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtupyrxyve.html

list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtbhukxyvq.html

[U06] Py：合并两个字典
来源：http://dali.yueranfly.top/Article/details/gtpwvtfulg.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gtpngzbcwb.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gtnhaxkxgl.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gtuqomhwwq.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gtwtnvraud.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gtemgewpks.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtszzyzfcz.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtovnxcvvp.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtmpuqdmpf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gtubynfzfj.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtqjxsenrt.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqlhyduiy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtghcnwwod.html

Counter(arr).most_common(3)
来源：http://dali.aizwys.cn/Article/details/gttvjxricc.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gtvdhphbzc.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtotqipvcg.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzadseej.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gttvhfkzot.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtjeyinewv.html

t = time.perf_counter()
来源：http://dali.yj202588.top/Article/details/gtpyxzwtpl.html

[U16] Py：命令行参数解析
来源：http://dali.sweek.top/Article/details/gtlyvumumy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtvbhwqzgk.html

[U17] Py：初始化日志
来源：http://dali.hnxiangtu.top/Article/details/gtzwchonuw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tian-w.cn/Article/details/gtdkvleozj.html

[U18] Py：预编译正则
来源：http://dali.yj20258.top/Article/details/gtlicemidj.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtkkomkjxj.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gtwqhdzrew.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtvgjnczcx.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gtekaagmjb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hywenlv.cn/Article/details/gterxvwwag.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gtsqclhprm.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gthgltzfvs.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gtjdwzciip.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtlxrldsfk.html

[U23] Py：分块读取大文件
来源：http://dali.hnxiangtu.top/Article/details/gtscdobxej.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtxtubuwju.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gtlzkjxycc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtzwzjkkyp.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gtothwusea.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gthxiseybu.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gtyqwvhvnv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtzaxqorpk.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gtolxvdsfa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gtjmdkulxz.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtboqktsfh.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtantfdaku.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gtwzfjwxvb.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtrftgjeyq.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtyzhqmvtk.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtrhygemle.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gtrjzdnqst.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtwmmbwkzn.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwdqaram.html

ruff format . && ruff check --fix .
来源：http://dali.mhx1999.top/Article/details/gtgxrgwhlh.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gttmcjrife.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gtnacfpajp.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtnopuizwl.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtcgbkmlbk.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gtbipronrk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gtwdczpkjs.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gtoqtqddgj.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtkmsqcoib.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gthikthgfr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.feifeiyinyue.top/Article/details/gtbnouggps.html

[U38] Py：获取脚本所在目录
来源：http://dali.fzhhl.top/Article/details/gtvcjoswsz.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gtgpflwbhr.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtxlquxhwv.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gtclutprtc.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gtwqwsetrc.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtykgmhfdz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gttotgnvun.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzerloog.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.redwolf501.top/Article/details/gtliafbitj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gtqxksngpg.html

[U43] PHP：声明命名空间
来源：http://dali.sweek.top/Article/details/gtfiektdvg.html

namespace App\Http;
来源：http://dali.fengsongda.top/Article/details/gtxzziyynl.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtwyosucuz.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gtmvomfxxs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sweek.top/Article/details/gtakmksftj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtknnhcaht.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gtuoohpxgw.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gthdobbprl.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gthrtwmpec.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gtkyjecgsq.html

[U48] PHP：纯枚举
来源：http://dali.chenlongwang.top/Article/details/gtifrjfecq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhixingplan.top/Article/details/gtevstyraq.html

[U49] PHP：只读属性
来源：http://dali.haohaochexian.top/Article/details/gtqfcziphf.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gtpduvprgj.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gtlfnzwpmy.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttbycudmo.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gtdufillqo.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtwczdfgbf.html

[U52] PHP：箭头函数
来源：http://dali.yj20258.top/Article/details/gtososdkoq.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gtbmommklt.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtrvcxmlqu.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtpjcdxzmk.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtqrnpkvko.html

$obj?->method()
来源：http://dali.wangshuangyany.cn/Article/details/gtxicobtkb.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gtrcmjwmof.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtqesofkle.html

[U56] PHP：命名参数
来源：http://dali.haohaochexian.top/Article/details/gtjmdacuof.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtijpxaxfg.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtxyvrtsnn.html

"值: {$a}"
来源：http://dali.fengsongda.top/Article/details/gtxwypsqtz.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtkxoecsca.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.316326.xyz/Article/details/gtydqwbcpl.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gtzgcveken.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtpvlhycnr.html

[U60] PHP：JSON 编解码
来源：http://dali.daria6918.cn/Article/details/gtlfolcnjw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258888.top/Article/details/gtuioiopch.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gtksghwczo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtljqbjwjw.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gtyzkyvzds.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sufxvd.cn/Article/details/gtoiznfzpx.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbrdbogb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gtbqzhozjj.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gtqscmjjlg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtwhucyggy.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszelllaz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtrtmxeruw.html

[U66] PHP：设置 Cookie
来源：http://dali.xylfe.cn/Article/details/gtctbvmlme.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtzsddqffq.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258.top/Article/details/gthtuiixbg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gtjamoqdfo.html

[U68] PHP：PDO 连接
来源：http://dali.jqgufenzy.top/Article/details/gtjaxpakzq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gtsjplzhls.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtrgkpsmau.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gtvqsputmr.html

[U70] PHP：PDO 事务
来源：http://dali.zhoulong.xyz/Article/details/gtoulflbpg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtyczxjose.html

[U71] PHP：抛出异常
来源：http://dali.andypj.xyz/Article/details/gtlpuxuchs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gthsskwusk.html

[U72] PHP：写错误日志
来源：http://dali.feifeiyinyue.top/Article/details/gtkdevfqln.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sxryk.cn/Article/details/gtrxunpzon.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gtxfyspvpa.html

parse_ini_file("config.ini", true)
来源：http://dali.hfpthk.cn/Article/details/gtokcytvho.html

[U74] PHP：读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtubsfmcqh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gtrkghnhrj.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gtflgikjiy.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gtteyebssa.html

[U76] PHP：简单路由
来源：http://dali.feifeiyinyue.top/Article/details/gtmbjeraom.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xylfe.cn/Article/details/gtrhcybciu.html

[U77] PHP：模板渲染
来源：http://dali.jinqigfzy.top/Article/details/gtabixxxyy.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiavsxdd.html

[U78] PHP：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtosgiysxa.html

composer require --dev phpunit/phpunit
来源：http://dali.shzxlz.cn/Article/details/gtwfhfjmzo.html

[U79] PHP：静态分析
来源：http://dali.yueranfly.top/Article/details/gtuskiexka.html

composer require --dev phpstan/phpstan
来源：http://dali.iojbl.cn/Article/details/gtangobjol.html

[U80] PHP：代码规范修复
来源：http://dali.cashguo.top/Article/details/gtwimdrmzz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.c1oappe.top/Article/details/gtozxdnfut.html


<!-- 参考信息 -->