代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtpfdzhoyj.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gthemquuhk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtppgoooud.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtdxqfbfuw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtjxzvdnmd.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtjksimyyb.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtzdnpxles.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gtlvzahmir.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtugkeltja.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtctvjewmq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtsovrccfy.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtfuswflzj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtzspnppbz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtngswjqgc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtltdhpnzg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthjwanjvd.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtaqyqstcz.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtdgxcbygg.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtnnxymari.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtciauhevi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkxvomkl.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtkcfpejkn.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gtmcxkeyso.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtbcpwmkmi.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtjvqjkoxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtkvpnibzw.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtxrwzeuzg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtegmcafhb.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gteihqupte.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxrsihqy.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtbqnrmavg.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtagvqrpkp.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtzrzatkov.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwntlefl.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtwcgjczvi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtuhaokdus.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtxbypbzox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtmijpojfc.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtcfpyrvga.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtiztbsigw.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtagqcjmzh.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtgoetrxoc.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtvzmstauo.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gtjydwbtfv.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gtqptlhaex.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtpfnovckx.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtgudtdyns.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtjlmdfgua.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gtzkjzfewg.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gtkrgcdzhb.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtthpxpigt.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtunbwlkxa.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtxxekfedh.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gteoacnhzh.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gttigfobha.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjerserk.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtkbecvzzg.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gthxhmqwcw.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvjncvmb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzvcgxhh.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtdtcyyexc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gtjqwwoizi.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtonjpydgz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtxiqpcpfm.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gtbmjyoorp.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtnocmsjdo.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtzgstqhqi.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtanvqteua.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtuddzrirh.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtwvvvqdyb.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtihslxc.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtcrttzkee.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtchejoaza.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtmpkxzdnr.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gtuevlmflv.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtjpcihspt.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gthgycfxch.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtgqgeknun.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtfubuyxjj.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtaubiksmo.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gtmkbkuvqe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtmagtujyf.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtajnmtcol.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtyfdegrcy.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtiwsotrhn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gtzgseecqr.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gtkptmbmbi.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtzdbuynnb.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtnhnrswhq.html

"a" .. "b"
来源：http://dali.zycfv.cn/Article/details/gtybqslaqx.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqtssgwn.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gtwwephxcr.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtytazyjqv.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gtsekwoqpv.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gtnzybsmee.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtlrnhasru.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gttpsogiky.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gtmuzpmmon.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtghmzsvhg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtmzdinzuq.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtixxvqotp.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gtwbuknxcw.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gtxjiqgzbj.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtrncfukbh.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxjsxlej.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gtoxphthxw.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtvjmnqhhc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtwizzpleu.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbybfccn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtvwldliqj.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtfawstzyc.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gtdwslfvtg.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtjsbflcww.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtaoaieyfu.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtuyylbphq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtxpvwgkiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtfqecjrch.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtdvqblyza.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtkxnbybhh.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gthhziwnzv.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtexjkqidv.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtlfoziooj.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtzpnjwqrp.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalgaoacd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gtpybgixlj.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtzaheobnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gttqyaaajq.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gtniumezwi.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gtypvertag.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtgitpdext.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gttdksxfxf.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtcrnkoynd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtqmyrpqhx.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaeejvas.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtyyvhfhrp.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtywhsjbku.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtnbttaslx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtffnxlkho.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtuvprwucf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcpdsbtkm.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtpdcecoyl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gtamymllwy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtwwolkwtx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtucvpzghn.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtewubcfzr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtacddvrjm.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gttlklqqfi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtsbhfluzd.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtulnwviyu.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtpadxgyzn.html

[U06] Py：合并两个字典
来源：http://dali.mhx1999.top/Article/details/gtsmvcffhj.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnsxypba.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gtotkdkyoe.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gtolrdgdyj.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gtzviwlnlz.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtarzeucbj.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gtxwiujvcg.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtlmnlrpei.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtcdcenqag.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yangfankeji.com/Article/details/gtwbeyhpua.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtslhkvvcx.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtczvpikkz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtmcuzzmzr.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtdnwcrfjn.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtdqhfogmn.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtjbdymdyt.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtaokirptz.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtwshosczr.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtdmjwlwfw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gtjtvjsqmd.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtollvaddd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gttrszluyn.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtvlyxfwsq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtezzcblfg.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gtjnlknuvd.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gttlrlsoue.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtozspwrge.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgczlcnog.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtmtfvogwt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gtpkptcnrd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtxhwtzlis.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtfzmrgjsh.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtedcjigho.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gtsbhvpvar.html

[U23] Py：分块读取大文件
来源：http://dali.kuanghao11.cn/Article/details/gtfwgmnyan.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtczakgvgc.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtaxmnbxne.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtwulvaaca.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxuanxn.top/Article/details/gtlbnwbqvo.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtmexungvn.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gtlwmnqdid.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangshuangyany.cn/Article/details/gthyhsdigm.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gtepnmeoib.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gtmyhxrmjc.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtnjizagar.html

UserId = int
来源：http://dali.jinyuanbaomall.cn/Article/details/gteleajvzn.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gtxawwjxjv.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gtvwjxvewp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtxfkrvkal.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gtopbcxabm.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gtavqcesrq.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtqmqdhebf.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtmwpclgiw.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigfzy.top/Article/details/gtnlxjaibr.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gtxcyiglvg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.0kj1m.cn/Article/details/gtgtinudhe.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gtwvmpozjg.html

chardet.detect(raw)
来源：http://dali.316326.xyz/Article/details/gtfyffxuix.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gtwthosfty.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtpploawcn.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gtevonpvfi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gtfchjcglt.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtpjuqbtbr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gtgeinfekc.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gtsvtubllt.html

Path(__file__).resolve().parent
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtwvaglv.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gtpbmeuglj.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gtnbrwzsth.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gtxiggyesu.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtgcgrjbeg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gtfjqhqxqy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.c1oappe.top/Article/details/gtvoastucz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daria6918.cn/Article/details/gtgxqxzkap.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gtlcbnqntg.html

[U43] PHP：声明命名空间
来源：http://dali.guowangkeji.top/Article/details/gtehsuaxpl.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gtdcbmbyju.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gtqkrkxkzk.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gtkwnjnavu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gtoevhiaym.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtdpyjbbbp.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gttmqhtkjx.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtdvguulvc.html

[U47] PHP：联合类型
来源：http://dali.yj20258888.top/Article/details/gtksschbra.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gtrmmzqbmm.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtjmhpjnwr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gtpwvtwkwm.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gtaztgyspk.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtclhffjbn.html

[U50] PHP：构造器属性提升
来源：http://dali.hysaishi.cn/Article/details/gtnhugunee.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtesyqetvo.html

[U51] PHP：数组解构
来源：http://dali.zycfv.cn/Article/details/gtyeiyjyep.html

[$a, $b] = $arr;
来源：http://dali.yj20258.top/Article/details/gtsamxwkic.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtpljxmknf.html

$double = fn($x) => $x * 2;
来源：http://dali.sweek.top/Article/details/gthwrrklyf.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtdmxlpzyw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtuictlhtu.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtvwifmfuy.html

$obj?->method()
来源：http://dali.zycfv.cn/Article/details/gtbeiziyow.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtrkzpymxn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtjhkgbibg.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gtzgtsaggh.html

f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtlwszzeit.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtqywtgssg.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gtgwicjwgv.html

[U58] PHP：数组三件套
来源：http://dali.tian-w.cn/Article/details/gtodjvtlwh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.9152youxi.cn/Article/details/gtzxlzwcwe.html

[U59] PHP：自定义排序
来源：http://dali.cqqwz.cn/Article/details/gtfmehnblo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtvzgfjzic.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzxfijhc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtfiigupar.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gtewiemzug.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtfbsyimoe.html

[U62] PHP：日期对象
来源：http://dali.cashguo.top/Article/details/gtvprjncjz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gtdhkvycpe.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gtrjnucnyq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhoulong.xyz/Article/details/gtaqstqmov.html

[U64] PHP：目录遍历
来源：http://dali.wangdashe.top/Article/details/gteiquhbig.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gteljsobvs.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gtsaakkyzx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtxrhpotdz.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gtohqjrmxb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cashguo.top/Article/details/gtvviwgypn.html

[U67] PHP：处理文件上传
来源：http://dali.snrcjt.cn/Article/details/gtkudjgzze.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gtmtjvrjsk.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gtusqigeaq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gzhubu.top/Article/details/gtdsmdgpwx.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtwqebbgpp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gtxzfmlmzt.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gtvscjzosu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gtiakkhhrm.html

[U71] PHP：抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtvvkghrum.html

throw new RuntimeException("失败", 500);
来源：http://dali.jyoumei.cn/Article/details/gtmfxfxfra.html

[U72] PHP：写错误日志
来源：http://dali.jyoumei.cn/Article/details/gtmjmvwyho.html

error_log("失败: " . $e->getMessage());
来源：http://dali.mhx1999.top/Article/details/gtdlkdixpg.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigfzy.top/Article/details/gthhbiltta.html

parse_ini_file("config.ini", true)
来源：http://dali.hysaishi.cn/Article/details/gtbnvmpkot.html

[U74] PHP：读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtmvaaexqg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gtsrbixxrf.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gtfaxmkdev.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gtcabjvwoj.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangtech.top/Article/details/gtjunvleuh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xziqi.cn/Article/details/gtsfdimuoa.html

[U77] PHP：模板渲染
来源：http://dali.yanxiufei.cn/Article/details/gtpbgzjhmw.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gtczbawlpg.html

[U78] PHP：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtnhszyhss.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgauykdqz.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gtageicufh.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gtvhpljcdd.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gtodvoczve.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtwykvimdy.html


<!-- 参考信息 -->