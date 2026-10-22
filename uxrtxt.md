代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2sjrorrkb.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gt2wmuczzom.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2mzcvxxhn.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcujecsy.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gt2apazlmey.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdoycrcr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gt2tpxfauhy.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jewhismz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gt2lhdmgnbg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ltgyietd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gt2bylzvtep.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypvetrvc.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2bjtikicp.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2jknrfkju.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gt2ndzqcozy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2wioddinm.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2ivudbgim.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2sqftgyxn.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2qwkdghfw.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gt2ethvukyb.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2aootpgsa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gt2jhxtfyda.html

[T06] Kotlin：集合映射
来源：http://dali.bjfxy.top/Article/details/gt2jvdkeqfi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2rxcbzuzo.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2ibryynbw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gt2qtecjkug.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gt2ksymmazo.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2eeqykbbm.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gt2aohkvkvc.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gt2auekdchv.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2lpjdtnsc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gt2krhugeha.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfgdbejj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gt2pnfpoxzi.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gt2pigatyoo.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2vsxpcyhn.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gt2wjnhhmfa.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gt2rkxlbzgy.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gt2mfsufnkb.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eizbdrld.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gt2eecxamqz.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2zxaelxhs.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqwxvfrq.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2xlxozycu.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gt2ioyokbdi.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2tfgrckmf.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2nrqyeuwi.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gt2fcdeqisw.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gt2uilrqumh.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gt2xsnzwgqe.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gt2hexvdqzj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2kvifwvws.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gt2kyhywdtq.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndnyuoak.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gt2tohgzbnv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gt2kixdokvk.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gt2iyoxjvcj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2flnivrec.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gt2neuesnrs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2vrliwtfa.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2xuuzgnlb.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gt2crxxkqfl.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gt2tasnylvb.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gt2jtzflgwn.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gt2eijdtrmh.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzsexkgs.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gt2yedqascd.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gt2tavtlkhj.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2gkpytcfk.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gt2fyyladiz.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gt2mafuajhr.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gt2cbmgnuhz.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2ijgcfasx.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2njvsmzpf.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2ofjmzdnq.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gt2ixtbvuto.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gt2lgheslcf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gt2spkzcbqq.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gt2ojrfzyyb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gt2bvaaltvr.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gt2xreylaov.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gt2cvdhsssp.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2uovimxhj.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gt2hrimvlhd.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2iggcddhx.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gt2rjpgzcet.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gt2aihhyury.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2qjishkdj.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gt2tmdsxzfc.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gt2vlpoubly.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2whhxftcn.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gt2uklmifkp.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2sgdptpxc.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gt2trgokwua.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gt2zpjxeuzf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gt2tgrntvdd.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2ewpefgcu.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gt2lubglmvf.html

[T44] Perl：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqlxvhxn.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2chvagdox.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2mzpogysk.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gt2ekqqnshb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fawojbel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyxcwelx.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gt2llsbwwzi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2oggmibcw.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gt2eehmpzxi.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gt2pwhfzqpk.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gt2nqdafgmo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2glnpwabq.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2kelhmaoj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gt2jzxiddhq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2lgmvatwn.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2jmjjbnff.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcueomcy.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gt2pxtyvhxx.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2gaqneqzn.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2qcslhsqm.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgxhqiaj.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2ovkpqxlc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2jirwdllk.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2ckchrehm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2svjrpmnt.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxfpntla.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2fhtyiayq.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2btafbbln.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gt2qhmxodtm.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gt2jiouuzkk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gt2rolsuall.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gt2yrgidrlr.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2mhuznovj.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gt2ivdxsmqv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gt2npybugoy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2lggkwjqa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gt2hrpvsdsj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2txsqfwtw.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gt2kvdyywgz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gt2xubzrviz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gt2euczjmbh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2mbnwxvbs.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gt2qbyxzlqf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjjxhjmr.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gt2tflssech.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gt2hwnwgloq.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gt2gjdvcgkm.html

list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2clmbpeac.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gt2lxyewmad.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gt2xykpnkuv.html

[U07] Py：反转字典键值
来源：http://dali.meibo888.top/Article/details/gt2dyyjbbvp.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gt2hugjuelq.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gt2dndwupaf.html

[y for x in nested for y in x]
来源：http://dali.zhoulong.xyz/Article/details/gt2oepcfjsn.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gt2ciwvmomk.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gt2oyfphomk.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gt2sclugjoq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2trdtbqyu.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gt2ohcdrged.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2gpxflyeu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gt2lxctfwhl.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gt2vhbmiini.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gt2cilgfqqh.html

deque(maxlen=10)
来源：http://dali.jlsjyb.cn/Article/details/gt2vjsgdqyx.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2pgzwhblc.html

defaultdict(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvndiahh.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gt2enanezec.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gt2vzwhhyvo.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gt2wbhuvgnv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gt2rvaitvdg.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gt2evixuphn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pycfn.com/Article/details/gt2kenktnlb.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmvbqqlc.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gt2fwiccenj.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gt2lvbqntne.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eurejnnw.html

[U20] Py：缓存函数结果
来源：http://dali.ydzc1.top/Article/details/gt2srhmxkwp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gt2mztkslxz.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gt2xgmqtuzj.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gt2ppixgozr.html

[U22] Py：矩阵转置
来源：http://dali.hammf.cn/Article/details/gt2eftdaslw.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gt2egmenzxc.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gt2temniazo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2fcvzeffz.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gt2qantgyzl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2oqdnevvz.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gt2ubifbzrt.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gt2xdtdhnzl.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gt2mplkzmgo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gt2oufrqoct.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtiabrse.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gt2tsgygvcv.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gt2nbxvvrei.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gt2nkeywvnc.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gt2ezoxuzea.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gt2qgrxqhtp.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdcmskib.html

@dataclass(slots=True)
来源：http://dali.mhx1999.top/Article/details/gt2grzlbagw.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aajnrqpm.html

python -m pytest -q
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpnfruyq.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmgdxwtm.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gt2sygrfdef.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gt2qrmfswbi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xylfe.cn/Article/details/gt2kffwqvyw.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gt2mbbwngun.html

chardet.detect(raw)
来源：http://dali.jqgfzy.top/Article/details/gt2xruqalgm.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gt2xhbnulma.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gt2sagsygrl.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2rtloyzgg.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gt2harzfjnq.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gt2rrmhdari.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgxeyupp.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjrinvpo.html

Path(__file__).resolve().parent
来源：http://dali.c1oappe.top/Article/details/gt2vtbizxhl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhongyouzk.top/Article/details/gt2thgyklfh.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcckfghm.html

[U40] Py：打印到标准错误
来源：http://dali.cqqwz.cn/Article/details/gt2qnjudmer.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2upnljohu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gt2fzzeuaye.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gt2chrplqws.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gt2ythttegr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmonpkvr.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gt2yqrbthmq.html

namespace App\Http;
来源：http://dali.sweek.top/Article/details/gt2pbcnbaua.html

[U44] PHP：开启严格类型
来源：http://dali.yuxming.cn/Article/details/gt2etwndigr.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gt2qoutqwwt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gt2eprantix.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2gcvcvkiu.html

[U46] PHP：可空类型
来源：http://dali.sweek.top/Article/details/gt2cungwwuu.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gt2pnlosvwl.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gt2qtxcvjve.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gt2rlcnsyvc.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gt2hkogzyyg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ehwqpu.com/Article/details/gt2voudqucn.html

[U49] PHP：只读属性
来源：http://dali.jlsjyb.cn/Article/details/gt2oekedegw.html

public readonly string $name
来源：http://dali.cashguo.top/Article/details/gt2nqugfkpu.html

[U50] PHP：构造器属性提升
来源：http://dali.quarkkingdee.top/Article/details/gt2jqatkkat.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gt2rumaauqf.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gt2vizsakic.html

[$a, $b] = $arr;
来源：http://dali.guannengcc.top/Article/details/gt2trdmztea.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnkuadwq.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2isqsmbch.html

[U53] PHP：空合并运算符
来源：http://dali.yuxming.cn/Article/details/gt2ynvmedoq.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcibptxg.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gt2dhvhqmgb.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gt2sjsrszbc.html

[U55] PHP：match 表达式
来源：http://dali.ydzc1.top/Article/details/gt2pjzxzlqq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gt2fzhjwsgq.html

[U56] PHP：命名参数
来源：http://dali.gogol.net.cn/Article/details/gt2utdehpsq.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2fwtjrmxi.html

[U57] PHP：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2vynxsvtj.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2hflnjfxa.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gt2xmxgnxdt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.iojbl.cn/Article/details/gt2jfcfzpxk.html

[U59] PHP：自定义排序
来源：http://dali.hnqzz.top/Article/details/gt2rwsagvof.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijlbncwn.html

[U60] PHP：JSON 编解码
来源：http://dali.ivvv.top/Article/details/gt2kjkltbtu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gt2ohkgsjxc.html

[U61] PHP：正则
来源：http://dali.andypj.xyz/Article/details/gt2dwxzinol.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2cvcrzbjo.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gt2vobrxnre.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.redwolf501.top/Article/details/gt2kdzckizr.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gt2whwfrjxy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nznopbxa.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2tsemfwry.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yongpay.top/Article/details/gt2kacxkasc.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gt2ozpepcwd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2bahglsfv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgkjimx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gt2lltgbgoq.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gt2dlotrtbh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwylvwz.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gt2uhcqvqxr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aizwys.cn/Article/details/gt2khimcobv.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigufen.top/Article/details/gt2lbhhswpr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gt2oxivlrwz.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gt2gucnveqx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gt2ctzzswos.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2cedskdxn.html

throw new RuntimeException("失败", 500);
来源：http://dali.fzhhl.top/Article/details/gt2mwfceurz.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gt2grxufnih.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gt2ecixgrhd.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gt2ctygqbgx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gt2cvrkdyhg.html

[U74] PHP：读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2fnhaljxj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gt2ascuztxr.html

[U75] PHP：依赖注入
来源：http://dali.aizwys.cn/Article/details/gt2atfgjksc.html

composer require psr/container
来源：http://dali.zhongyouzk.top/Article/details/gt2qektkcst.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gt2plxdtugn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuanzhike.top/Article/details/gt2rmskgnyc.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gt2bktkifvy.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gt2ohlxnztf.html

[U78] PHP：单元测试
来源：http://dali.yueranfly.top/Article/details/gt2abewqazs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2osoafovu.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gt2gzqdvyhz.html

composer require --dev phpstan/phpstan
来源：http://dali.hammf.cn/Article/details/gt2achkhoax.html

[U80] PHP：代码规范修复
来源：http://dali.xziqi.cn/Article/details/gt2screplev.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.smart0.xyz/Article/details/gt2egcigamp.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gt2sigkswlu.html

npm init -y;  npm i express
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozalxucv.html

[U82] JS：package.json 脚本
来源：http://dali.hammf.cn/Article/details/gt2fuighvay.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gt2jutvlmxj.html


<!-- 参考信息 -->