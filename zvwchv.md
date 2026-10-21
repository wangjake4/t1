代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoebfqfi.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtaypmaeey.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtmsurjkiz.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtapwaopne.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gturmmbxxo.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtwkfyxakg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtmgebyaae.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtausfnbwh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtrxtvnzjb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtelautrgm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtgohehcub.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhrxmxzo.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtalmiidop.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtggkxmfdb.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfewdiej.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtfpvkgzop.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtuphxzuns.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtffnggwdt.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtcqyabhyy.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtkpdrbweh.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtzoibbdmh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtxvwolmgl.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtgmfkrayn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtivnkawyi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznefgthn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtpncaklnl.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtqrqtfnzj.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtrxdwtnyu.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtrqjktcuh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gtumlbgldm.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gtavulbumt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtnufsikvy.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gtxooykarq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtgyoknauw.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gtagorkzti.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacpbytix.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtiislpnss.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gttugzsuko.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gtehyhhrjv.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtsovrrrqc.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gtfduggkwz.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtdahaliuy.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtbpsheglc.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtcrcuttdg.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gthedpqthp.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtobecglwo.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtewrdvkgc.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtxbgrzntj.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtkowxrbnq.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtxdchkoxz.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmcjsxuh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtucisttuv.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdivcldk.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtbprwigga.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtxtvehxpj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtpghvkzce.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtcbalzpaz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtmhygdqtk.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gtzsogtqpf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtasrnmmbb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtdxjknbgp.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtfiffebky.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gtmlkikbfb.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtmmidmivp.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtcrufrece.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtbvwheyks.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gturguqdvu.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtnxpyjnkh.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gtpyjqurho.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtbwyqkebo.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gtkjwxzxcz.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtsqynkkys.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gtpatnjbzd.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gttxxgmpch.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtlhiqjdfd.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtaqqodmtn.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gthtbuozgk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gttbzzspir.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtcrhrfknd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gttfgtmpet.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gttcscnteg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtuiwthelk.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgeegplqb.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gtkqpwbtqe.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtkeeoughp.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gtrjqxmyls.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gtpfflywwb.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtuxsohtye.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtzrzxbmqg.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gtubxozrru.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtwbvdrstg.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gthgxqkopw.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtmzbsgffz.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gttqitgcqw.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtpzmobncm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtmnzbnwnx.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtbkykslee.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gtahiidaaj.html

[T44] Perl：条件
来源：http://dali.jyoumei.cn/Article/details/gtsfrkhfar.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrgxxvhie.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtypscczzn.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gtbdczfkgh.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtrrbnnthf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtbmezpicj.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gttwhsspby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtrmxbwh.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gtcdnzvwfu.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtqioguert.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtjtfdxylr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gteipphlnb.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtkxrtcddk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtjknkcwtn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtvutayuyd.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtovszciuw.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gticmvquec.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gtmhpohrgh.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtqgawxupz.html

[T53] Scala：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtzlfbvyca.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtacisogxp.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtcyeieuna.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtjrcacyvh.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtvffvnnbl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gtmdqyxcic.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gtpgnbinhh.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtiovfyhli.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtvcaaacep.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtkvbsqvmm.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtiwwmotps.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtunsstrcb.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtfusdkfur.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdigizfbj.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtsbgisfbs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtsmanzana.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvdzxkrra.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtvexshlvi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtcadyxyym.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gtjnhrgtij.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtjoesjlcn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtrykeqdau.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtiyzrhsks.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gtbufueifl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gtjptezogj.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtbpdijnpy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gtpxyvlqnw.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtyupugdlg.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtdmccobxa.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gtjlcivwnc.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtmxabkmys.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexfklsbt.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gtfzzumota.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtusvypvoe.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtiilzgzrt.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gtrutftsgo.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gtcvprrvyc.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gtqoufuocd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldgwpjae.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gtjhlsmqye.html

(x * 2 for x in arr)
来源：http://dali.daria6918.cn/Article/details/gtphkjybsd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtfgixgkpl.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gtxgruxwml.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtslzigokf.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtubipytwf.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtsntkbidc.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtrhjwxmop.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwltweug.html

t = time.perf_counter()
来源：http://dali.daxiang520.top/Article/details/gtdnosotcx.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtdlxoexzp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gttueuxeyg.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gtngxsjofs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtbiwukvjq.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gtvkwrsxqb.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtinkjaqwc.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtbgjcfobc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtacuyobzp.html

[U20] Py：缓存函数结果
来源：http://dali.jqgufenzy.top/Article/details/gtfiifibev.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gtmcvetigr.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydyovztt.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtmgpbgunz.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gtihitfivx.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gttsrksqvd.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gtbkaofsmv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxinkj.top/Article/details/gtuypnacov.html

[U24] Py：路径操作
来源：http://dali.zhongyouzk.top/Article/details/gttkshyjcj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtlruhdtgy.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gtntmanphq.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gtmbocqpfu.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gtdyapfdug.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtvmpetlfa.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gttvydtatj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtlklhcubh.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gtaaqwgwmm.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtgjgcdzgj.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gttzsnimty.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtmczgxlza.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gtxecfmbhi.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gtufhpzjmc.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtjanvqwyu.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhkokvjj.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gtopbaapju.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtpsgojurh.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtvwfuxptp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtzabevizx.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozglenij.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gtjhuoyzvx.html

[U35] Py：发送邮件
来源：http://dali.smart0.xyz/Article/details/gtosemjoun.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gtrsfgzuuu.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtqysxifss.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gtercxzqlb.html

[U37] Py：读写 Excel
来源：http://dali.kuanghao11.cn/Article/details/gtmuitimwt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgufenzy.top/Article/details/gtxkslgubm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhengqikj.top/Article/details/gtrnystydf.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gtamyosaqs.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtfgmvahbw.html

sys.stdout.isatty()
来源：http://dali.nanxinkj.top/Article/details/gttokvqaqz.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtmahuihmp.html

print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtkarmugfi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hfpthk.cn/Article/details/gtyyrsqfwq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.meibo888.top/Article/details/gtqoijamac.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gtdvjrvosr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuxming.cn/Article/details/gtifajcmle.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgfkitab.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gtnkudrgaq.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gtqkmeiavh.html

declare(strict_types=1);
来源：http://dali.tanke756.top/Article/details/gtpeswgguo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gtuisahswy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtszlpsnkt.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gtwhsdasza.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gtivlhpysl.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhbksdyg.html

int|string $id
来源：http://dali.hammf.cn/Article/details/gteneugewv.html

[U48] PHP：纯枚举
来源：http://dali.yuanzhike.top/Article/details/gtgyericde.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gtnqwztiio.html

[U49] PHP：只读属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvdekwhm.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gtcmoxcbgs.html

[U50] PHP：构造器属性提升
来源：http://dali.xziqi.cn/Article/details/gtovlnoqqm.html

public function __construct(private int $id) {}
来源：http://dali.jianghu66.top/Article/details/gtdcnuhfnb.html

[U51] PHP：数组解构
来源：http://dali.xuanzx.com/Article/details/gtvlbdocke.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gtwhvkfzgw.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtupfdmuny.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtesrsvgwx.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtajcmjqxu.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gthwsmogbr.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gtikfhodsq.html

$obj?->method()
来源：http://dali.tian-w.cn/Article/details/gtaccrcitj.html

[U55] PHP：match 表达式
来源：http://dali.c1oappe.top/Article/details/gtozghvmwu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtktfxcuru.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gthkbgdcdh.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtfelrlvgo.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtjhullpmr.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gtgowxiruj.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gtapprfhde.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtclmvrawj.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gttiyyrrrl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtmyamxsmp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gtyygfoyoj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxuanxn.top/Article/details/gtwhleouhb.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gtvtszxire.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtorbmxddy.html

[U62] PHP：日期对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqymmytn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gtfibpxjbj.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gtsxshfhxy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258888.top/Article/details/gtwsohuiwf.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gtlbpcgpfc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.snrcjt.cn/Article/details/gtsxafpexo.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gtwwymwwxa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtpuxlmwvi.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gtxuwshsjn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gtyinyopda.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gtlyldgevx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gtmuxfuwvl.html

[U68] PHP：PDO 连接
来源：http://dali.cheryme.top/Article/details/gtdqpdfmqy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gtjubgqzuf.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gtvoxcaldk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gtehyzdbwk.html

[U70] PHP：PDO 事务
来源：http://dali.vqdsnc.cn/Article/details/gttizguswg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gthfvzovsm.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtcmqqkwsq.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtsgcujxsi.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gtrjkhdhur.html

error_log("失败: " . $e->getMessage());
来源：http://dali.quarkkingdee.top/Article/details/gtcbxmglmb.html

[U73] PHP：读取 ini 配置
来源：http://dali.mhx1999.top/Article/details/gtsepqowcc.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtzquzjrnv.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtzgoqblbr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jianghu66.top/Article/details/gtvsqcgpya.html

[U75] PHP：依赖注入
来源：http://dali.guowangkeji.top/Article/details/gtgupuivhy.html

composer require psr/container
来源：http://dali.cdnleiting.top/Article/details/gtrdextfgi.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gtsxpynchn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdizizqcz.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtphroxxch.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gtahjvmtfp.html

[U78] PHP：单元测试
来源：http://dali.sysykeji.top/Article/details/gtfyhftiaq.html

composer require --dev phpunit/phpunit
来源：http://dali.tanke756.top/Article/details/gtsgqhgjrr.html

[U79] PHP：静态分析
来源：http://dali.guannengcc.top/Article/details/gtnzpsrupn.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtpmliagir.html

[U80] PHP：代码规范修复
来源：http://dali.cdnleiting.top/Article/details/gtrcyeqnrg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gtjpilyika.html

[U81] JS：初始化项目
来源：http://dali.gogol.net.cn/Article/details/gtxlvplhcf.html

npm init -y;  npm i express
来源：http://dali.jlsjyb.cn/Article/details/gtelkvuqbc.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258888.top/Article/details/gtomykxcgx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtaasdytua.html


<!-- 参考信息 -->