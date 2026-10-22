代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtbjkfdmce.html

[S59] C++：静态断言
来源：http://dali.yj202588.top/Article/details/gtzcyfskew.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gtdhjchvov.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtzmtqhnjf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gtvbxwovfl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyjjyyaaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gteoucykyt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvyuezarn.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtgnmbxdvl.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtpmdywotw.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtjwrxgxfx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtehrjqgga.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtmqwwwayy.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gttknpoeag.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtamvwkibu.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmawgbsh.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gticbpxtmv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gtjihubqae.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtoqodbhth.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtvkqlhaiz.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtonmareem.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtrtddnjwm.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtvfofyhue.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtfqxnvssy.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtaduybzkp.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtckrtzyfj.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtzoaqjcdb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtwxduxqqi.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gtzscdfoml.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvapssre.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtghyahqwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmyzatxx.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtbzychtgp.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtarmpwemd.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtmtbdqrwe.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtejhydiho.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtsgkxsdvy.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtpsdlgnbm.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gthtfkeisk.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtxnuazqcb.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtrdjkrjpd.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtglhentnj.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtluutrato.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioeeagzj.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtyrmlmdfj.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtvrfibkut.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtaqxeojga.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwunocvu.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtrwniekyc.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtknriowor.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtlvwerlay.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtzuyunzjh.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtvyfsmhpq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gtoarqzmgt.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtabhaqzoa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqatwlnhw.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtbvtmtpjy.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtkdzmtqlw.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtalxscbwn.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtacctencj.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gtikrhcyvu.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtaaakwhoc.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtjccxcasy.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtqzhvdshq.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtrzekwrfu.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtyswhofqd.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmvhvguv.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtoxrrzgjb.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtezqwarvh.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtpneohors.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtjayyjdpu.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtlfbckplp.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtsgjehaqp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnfkpeyi.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gttfmmsarb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtjocvlfia.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtehdsvwti.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtmucnsoxu.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtchmumvqo.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtkmkalmpf.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtdakeqobx.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtagkcbdci.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtdmjrfent.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtdnccjncm.html

[T39] Lua：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysbwryel.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gtchwautvj.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gtytqfivim.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gtdbnbiofa.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtqcfgdfeg.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gtptovlibb.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtfqiekhey.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtwyoklotu.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtxheklwly.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtefgdxelz.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gtloxvulwq.html

if ($a > 0) { print "正"; }
来源：http://dali.yj202588.top/Article/details/gtccioocmp.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtmiyfwojx.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtqfufkhij.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gtfkzctucx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gtqdimyvam.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gtwurztruk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gthwdxfdgj.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gtsrrjsrji.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtxyjhtbjk.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gthaekfvts.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtxpfcyqhq.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtlngybzyq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtcxtouxwb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtojpvpyub.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gtbksmcrrw.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphtbfkmo.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtsyirllfa.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtcnrprwfi.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyihnoofc.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtvujwcuxb.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtwaefqnkj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtgrhvqqih.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtlerkxjzz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtbdfpqwyo.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gtbhdbatgo.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtsdxiufzh.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtclcmesrl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtfuoraxhr.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtjeqzursm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtevgkfgtn.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gtlpqzkzma.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gttqpbgdze.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtzqymuaul.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtccfpuurx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkylquaus.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtlhaaqbej.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdyfzszgt.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gthpknfmns.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtfrldmzwr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtiqqhmtqj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtkbkosgsj.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gtllvohqcs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gtlboqaomw.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtodnitned.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtatlvoodf.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtawsxtvpk.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtabynugrb.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtmlxbjhsa.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gtmqfkcxzy.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gtdctlyvdt.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtgzfyiaua.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtyrvrmbgs.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtupgsicnl.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gthvbkbyyh.html

max(d, key=d.get)
来源：http://dali.yj20258888.top/Article/details/gtkznluwnn.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtkyenuvhe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtdelvkxte.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gtwkxjgohe.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtcfvgkuit.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gtvqvxyayk.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gtdijoxess.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtqbyaconq.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gtaoctfytn.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtirdzdqkp.html

defaultdict(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlfstipa.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gtqqzztnzm.html

t = time.perf_counter()
来源：http://dali.cucudq.cn/Article/details/gtefnksptf.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gteymggufq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gtvmbhpazh.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatkxpijr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gtsmsezvtp.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtpvjyiucg.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gtxsbhzxpl.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtuqiiqjie.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fzhhl.top/Article/details/gtxlzgfyws.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gtjxyglmsx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtsvqcfipy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gthhinxgut.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtqofquhsb.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gthyerucnf.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwosvelxn.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoadlajo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gthgadajag.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gthfmzsfez.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtrjjakida.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gtyrbsbgkl.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gtkiuzobrp.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gttgjvkbwk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gtytspnjrx.html

[U27] Py：异步 HTTP
来源：http://dali.xziqi.cn/Article/details/gtiyhfxhqp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gtzridzzcp.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gtgipdtzei.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtwdivgvet.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gtjbxbpccb.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gtzsuowjcx.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtdstgjezd.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtlpmhrdcg.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gtlxuoegtk.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gtyhbtsnac.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gtfwdxbqbv.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtnjdddump.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gtozuyvdyv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gtrxnusmkp.html

[U34] Py：判断编码
来源：http://dali.sweek.top/Article/details/gtlcrwqpoz.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gtpahbahoy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gtnfbsndus.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnqzz.top/Article/details/gtgqtbccex.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtpgpvnxkj.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gtwaglrhqc.html

[U37] Py：读写 Excel
来源：http://dali.9152youxi.cn/Article/details/gtbjkmhnsv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtzlzfpgxq.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gtplqndlgs.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gtdwpmkavn.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtyldzrwuc.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gtrtmuharh.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtpdrfhtif.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtwjarybwv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.316326.xyz/Article/details/gtkzooiiuv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtuwrlfvrm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtvylmhyxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tian-w.cn/Article/details/gtmwzqfsze.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gtkyhwrpmc.html

namespace App\Http;
来源：http://dali.gaohongyu789.top/Article/details/gtpigkmtof.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gtympukazu.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtpdkflbgc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtatujcxlc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtjkscpwon.html

[U46] PHP：可空类型
来源：http://dali.dianchejie.cn/Article/details/gtwrgzirdg.html

?string $name = null
来源：http://dali.zhiwuduotai.top/Article/details/gtkjzodnqc.html

[U47] PHP：联合类型
来源：http://dali.pycfn.com/Article/details/gtdcufvxsk.html

int|string $id
来源：http://dali.sweek.top/Article/details/gtyabtvoqv.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtizzynvai.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gttugwlccg.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gtigszgnur.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gtgrexcrys.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtfkgwgwci.html

public function __construct(private int $id) {}
来源：http://dali.cqqwz.cn/Article/details/gtlsdwerpd.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtankjvyan.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtkncknlws.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtpfxylldn.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtidschgvf.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gtqhgoests.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gtwsqdlwxa.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtohoewaid.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gtifjqhijq.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtcedkwwrb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gtoohmoype.html

[U56] PHP：命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtglaqdvyq.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtccfzldxc.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gtektorjuq.html

"值: {$a}"
来源：http://dali.kuanghao11.cn/Article/details/gtgzdrzjxs.html

[U58] PHP：数组三件套
来源：http://dali.dashuyun.cn/Article/details/gtrplukajq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gtpsmladhd.html

[U59] PHP：自定义排序
来源：http://dali.cheryme.top/Article/details/gteekiucjy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtfggepoxm.html

[U60] PHP：JSON 编解码
来源：http://dali.aizwys.cn/Article/details/gthcqfnxyk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gtwowhtawp.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gticvlhgeb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtukeztoyl.html

[U62] PHP：日期对象
来源：http://dali.gzhubu.top/Article/details/gtmabrfcwf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtvdoubtft.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gtxfqzodoe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gtimgdvszo.html

[U64] PHP：目录遍历
来源：http://dali.sysykeji.top/Article/details/gtzqivbwdk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gtzkcxqbkj.html

[U65] PHP：会话
来源：http://dali.jlsjyb.cn/Article/details/gtmlsplaid.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtquoiezej.html

[U66] PHP：设置 Cookie
来源：http://dali.jlsjyb.cn/Article/details/gtoavebizj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztmmenba.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtjigdtkgu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gtnyoztkzh.html

[U68] PHP：PDO 连接
来源：http://dali.snrcjt.cn/Article/details/gtjjzxztfs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cqqwz.cn/Article/details/gtyljrvxhi.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gtgaqfzseb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gtbufuaohb.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtdpgxjvcc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtidhlkifp.html

[U71] PHP：抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtyvowdbps.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtjjguphoi.html

[U72] PHP：写错误日志
来源：http://dali.xuetiantiany.cn/Article/details/gtsfkmrqai.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gtljvwzkvp.html

[U73] PHP：读取 ini 配置
来源：http://dali.shzxlz.cn/Article/details/gtbmxlecqz.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtungcyrxr.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtnoakgdke.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cucudq.cn/Article/details/gtkwxhqmhn.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gtwtlgrwus.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gtrokpyynf.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gtnkcxlhrx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gtdzeobtxy.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtjmomxiyk.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtwvzefxcq.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtobqapqwc.html

composer require --dev phpunit/phpunit
来源：http://dali.mhx1999.top/Article/details/gtvdylkrgo.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gtdrobhwtp.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gtwwcrbfnn.html

[U80] PHP：代码规范修复
来源：http://dali.cdnleiting.top/Article/details/gtipqqqwpy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtygtcjjzu.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gturaiahyl.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gtpaqbvejq.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigufen.top/Article/details/gtwgiwsoez.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gtqaitflsg.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gtjetuoyfq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtdpjbwvtl.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtxwigrkyo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzxfayuu.html


<!-- 参考信息 -->