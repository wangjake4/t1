代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vczpowxi.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gt2xyrmyeam.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2ermijsvw.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2hytahbdi.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gt2vitaqsiy.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzfqdfqd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gt2wuuzvxmq.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gt2rauetyjq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2uklislsr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2gscjlffl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2civferwe.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wuhtbkvn.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2vcdavpww.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2clibafpz.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2kacikboq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gt2qampxspe.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gt2glcdqley.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gt2cubrrtvu.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gt2klzsizwf.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gt2ehlpyvuo.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gt2ycjvkadb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gt2pydvdvld.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqcekqid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2acsbapvr.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2gvlfyhrw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gt2zgibswav.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gt2grregjsv.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2mjcbrbxv.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2kunqqmby.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gt2ocefhtfj.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gt2wgegmsco.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2tqcllmwu.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gt2atjvsmjz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2vvyoxbuq.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2dpalufrp.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtqtcqcf.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gt2iswkdihr.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gt2ghaflkxi.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2fipxbnay.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gt2txljtrjc.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gt2slxfigyc.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2nqwonned.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gt2knjqptlt.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2xtzmaxli.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gt2gahnislw.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2jmulzgck.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2psbaswqa.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gt2pvpvkoso.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gt2evppauqj.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gt2lkoakijg.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gt2bphzhgqc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gt2wmtoskpd.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gt2rzzupqqg.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gt2kpbyvkss.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gt2snjaqxwv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2zeybyoxn.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypbvpqbw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2kjqwyegc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmabihh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2unrnwwml.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gt2gawjytdo.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gt2ybrlpgxl.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2pysunqrs.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gt2qutkyxcr.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gt2vzbrzjbp.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gt2sszgmfbl.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2lphmmuxv.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gt2batycxbz.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gt2isyjgjer.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2diytljtl.html

[T30] Swift：协议
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fylrwdxt.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gt2zygvjatm.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2kijcosky.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2dmgamgkl.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2gwwrryts.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2vmpluyui.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gt2eepsqeja.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gt2mozalqne.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gt2qtdyjosw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gt2pzgfqfvw.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gt2igppfdtd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gt2btjamcta.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gt2nucwvkqi.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfmnvzoq.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwjpgrkm.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gt2oyfzkwdt.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gt2iutptgjn.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gt2rksxpsya.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2uqcfjqgw.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2budmmxci.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjuoeemo.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gt2xcshxhas.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hvewecsg.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gt2zqagqbky.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gt2hxfdsskz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2lqmznxaf.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2efggzeps.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gt2tjedgawl.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gt2kjeaficz.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2arukrrur.html

[T45] Perl：数组遍历
来源：http://dali.redwolf501.top/Article/details/gt2ymigwwha.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2jzhwmcez.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gt2baugbpok.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gt2seljoqyh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsbvtzc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2uaqbafyu.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gt2jxoflbbq.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2cgkrxhfr.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gt2olldiukl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2hvujergd.html

[T50] Perl：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2zkyphmgo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gt2esqgyffl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2sxgbjajo.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2szoguict.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2lgjmddau.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gt2jhljcfqu.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gt2frlahdok.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2atgcacyb.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vofeefho.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2mvanhgub.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2tqhwelef.html

[T55] Scala：集合过滤
来源：http://dali.ivvv.top/Article/details/gt2olgxvtee.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2orjsafae.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gt2kamcfgog.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkjjtgun.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2ruovtrng.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2ibkvkxze.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gt2yqsftipv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2llxwyvqo.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gt2sibyrkgm.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2rhjcpdea.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gt2emadlani.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gt2zihynrfr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ujkbzwod.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gt2ffkkahau.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2cbphfszk.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2jodfgolk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gt2gypxymha.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gt2wifhiogl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gt2hclgkyuu.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gt2qmggywgr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gt2pecmngcg.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gt2dzxndimr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhbcrzoa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2axzmaynb.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2coukouhs.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gt2vdgtqpix.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gt2ggeabuhe.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2nnzgzlea.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gt2yopmiqbb.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gt2kzwzgbql.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gt2woihzmej.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gt2qqoctagz.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gt2siqptjti.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gt2venqrwwa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gt2lgnklgzc.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdzsurfq.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2cbwtwtwt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gt2eldneyjj.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2lobwuzps.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gt2sgvhpxhf.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gt2dtobgrxe.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2alferxpy.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gt2efatrjjz.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gt2ymhrmtup.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gt2uxzvbodd.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gt2zgtyyhqd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gt2oruygnba.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxaoqynq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gt2hpwprzuw.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gt2newregmc.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2jiggiutk.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gt2nejhujcl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.quarkkingdee.top/Article/details/gt2hsqaiiwo.html

[U20] Py：缓存函数结果
来源：http://dali.fengsongda.top/Article/details/gt2gdrplnpe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gt2kckewtpi.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gt2ydeenprf.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gt2ccdyawwx.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gt2upevkxlm.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2adodhnaw.html

[U23] Py：分块读取大文件
来源：http://dali.chenlongwang.top/Article/details/gt2mkkhfkfa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gt2boavrlou.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqbjvlbk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2ekkxypmp.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gt2bkuevpwo.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gt2pjmbkkqj.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2gvwmwbjs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gt2zbpkapfw.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gt2iszufeki.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gt2tmqjhaiu.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gt2efrjtuno.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gt2hglsodlm.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gt2ywerjbmi.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gt2ztgjrtua.html

[U30] Py：数据类
来源：http://dali.ppjwa.cn/Article/details/gt2tilomhjw.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gt2xeekekqr.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gt2ebaerxmj.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gt2ajlyydko.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcgzhbkd.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gt2vlyumghw.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gt2lqpyuvxr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guowangkeji.top/Article/details/gt2oaomacvb.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gt2goajlltg.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gt2cefmcouu.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gt2uelacjvm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yongpay.top/Article/details/gt2cyeypjrl.html

[U36] Py：定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2bruvjlvq.html

schedule.every(10).minutes.do(job)
来源：http://dali.ybcxt.top/Article/details/gt2ivyurswi.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gt2csekkrkb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.bjfxy.top/Article/details/gt2nfwijlih.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gt2ycsxfvia.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gt2laybkujh.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gt2tbkojowy.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gt2tcgobdwq.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258888.top/Article/details/gt2wxwzmsez.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2pmvbahft.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gt2obvvvqrq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cashguo.top/Article/details/gt2gnhmysnx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gt2dgbpkqly.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gt2bztmjien.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gt2zzcxgzls.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gt2zgzjqiha.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gt2gmggspga.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gt2umqgpbwn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ivvv.top/Article/details/gt2snuxbvbb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2djenvssh.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gt2qqxvqzql.html

?string $name = null
来源：http://dali.nwbrower.top/Article/details/gt2siushpgn.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gt2hsmieqil.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gt2sfruruvv.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gt2zpiiyono.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gt2zbktlzoy.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gt2rsrgwayp.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gt2zcvjverd.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gt2evijpxev.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gt2cpsaubro.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gt2dwwpycwv.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gt2qozxlvlp.html

[U52] PHP：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gt2vdwnvpax.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gt2otidljpg.html

[U53] PHP：空合并运算符
来源：http://dali.svipenyu.cn/Article/details/gt2yyzgjqiy.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gt2gebajrvg.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gt2fwvsqzfg.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gt2cxkxsjcl.html

[U55] PHP：match 表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2dgqykimy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gt2zobzwsds.html

[U56] PHP：命名参数
来源：http://dali.yvedp.cn/Article/details/gt2nesirval.html

f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drwfexfv.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2rldzwgyb.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gt2qopfmamq.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gt2climbvnj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangdashe.top/Article/details/gt2guvpgvij.html

[U59] PHP：自定义排序
来源：http://dali.vqdsnc.cn/Article/details/gt2opfgwxlq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiirkvqz.html

[U60] PHP：JSON 编解码
来源：http://dali.yanxiufei.cn/Article/details/gt2qgsgpotn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2dvgdubcc.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gt2lwedoket.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdmynqnp.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gt2qjwituno.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tian-w.cn/Article/details/gt2akqtvvnx.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gt2dosgruyl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigfzy.top/Article/details/gt2uswbmelr.html

[U64] PHP：目录遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzvgqkor.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gt2xpkptqfj.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gt2eeppkoqa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sweek.top/Article/details/gt2mrsdiaor.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gt2dzgtsdpd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hysaishi.cn/Article/details/gt2wnadkbro.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gt2qqzxmghp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gt2uvlutguc.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwqnqaqc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gt2cskrmqqe.html

[U69] PHP：PDO 预处理
来源：http://dali.shzxlz.cn/Article/details/gt2wzmtioqr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.vqdsnc.cn/Article/details/gt2cknphove.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsegryuv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gt2unnvnjuu.html

[U71] PHP：抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gt2uvpbforq.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gt2xierexhw.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gt2ynqfwnyj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gt2fjzxqtoq.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj202588.top/Article/details/gt2wzqhrktj.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gt2wkdjwhoh.html

[U74] PHP：读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhfpxwfl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gt2vrqyzxoq.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gt2xacebxvf.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gt2wcnadito.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gt2zfqcfxti.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhixingplan.top/Article/details/gt2ddqpfkcm.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gt2elgntseu.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgkqcfre.html

[U78] PHP：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gt2blwawzcr.html

composer require --dev phpunit/phpunit
来源：http://dali.zycfv.cn/Article/details/gt2fjxcraiv.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gt2cdbypjnr.html

composer require --dev phpstan/phpstan
来源：http://dali.hnqzz.top/Article/details/gt2jpalzcup.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gt2pikvazuq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aibaodan.cn/Article/details/gt2gyputpja.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gt2rwhgkpbj.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gt2cdsdchvs.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258888.top/Article/details/gt2mgeayyaz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilufvqyj.html


<!-- 参考信息 -->