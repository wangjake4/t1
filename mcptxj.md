代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtmdriuhot.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtdfscodoc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtwvongsvh.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbsrwpgg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtbmeyouxf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtcyinqigl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtgxlgczpf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthutlcllh.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtdlmxspig.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtusuvzgjm.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtfuztdkma.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtstaaelmp.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtzeyousmg.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtlbhwkxzn.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtiwvseegz.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtokwfrzmh.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtsfcyujau.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtipuwzpho.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtomzqcvhv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtqqqmkwdd.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtxqzmowoc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajumidvc.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtneuokrix.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtciartita.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtjzeeeqml.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtxglgjhda.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtchuwjbrb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gttvgdzzvh.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtcqofbyfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gteqdslbff.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtwfhdglcm.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gtgvxthilm.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtiakdyjlo.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gttolruiol.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gttqkcguhe.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtlezutzxv.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtkoeyeqad.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtmykehplu.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtxleylifq.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtfimwlmjg.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtibhnmvyx.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtlqndchyi.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtrzhnvzii.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtwtjztgdj.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtmxtrjwnl.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtsdklvtml.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gtohjjtwig.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtccdzkadv.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtlekzuxcn.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gtewoobshg.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtytpwvisl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtydhebkbq.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtxdofdsgr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtvkyxpnoi.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtvastcqjp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gtuwtlztqi.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gteruoftrd.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gthepwknzy.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtascetlqc.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtylqrzyzl.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtxoputgna.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtcsabtxpg.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gtsyavnqrp.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtkrfcqtaj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfitnnhb.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtygaphqpe.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtqftkpxpw.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gtmxhfgbuj.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtfdmoohip.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtdiwwtmsw.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtxdxkkffi.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtolhnvvbx.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtilbiebeo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtfulszxeg.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtdamuoxzm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtkhcgqhlv.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtwkrwwjmt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gtbmldkotg.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtovixxfek.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtephbgdof.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtjblceivm.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtgkujkygz.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gtktzvtxxh.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtmhuugveh.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtkivtwopj.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgivruobo.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gtrinxvcpg.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtxvlibjkd.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtmtwwsnja.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtwcbymuxc.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtcumqepca.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtqobdcbmk.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gteceythiw.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpdcjaxf.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtmtcmrsyx.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtprzigeoe.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtmwkggjfr.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gttecshued.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gtewpjddfj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtxvvrqzgj.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtpsmnfjip.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gthpsorfwi.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gtnfudqjad.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtalytvyxw.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtggcousvn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtocolrdrf.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcihtrvu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtfjjwceso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gtbazpwgsu.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtvsjmdzxy.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtjtbcbnvi.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtgwejofod.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gtnxmrpylt.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtxctphlrr.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gttvoxvequ.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtndqbhpbj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gtvgnygzcd.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtqmakshnb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gthdcwtbrq.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtosjjfnko.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtfpbnebho.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtlwbjjlfg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gtsdagixyt.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtosfenwne.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gtkffamoim.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gtzuagfsnk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtugwmxzva.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gtcvmbmcse.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gtlvlthsws.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuibjwgvw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtxwlnfxrd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtuyrrnuhz.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtuaziitlc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtoywdbqqq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtvjhgshpt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gtmuajllyh.html

[U03] Py：加载 .env 配置
来源：http://dali.nwbrower.top/Article/details/gtvhhrntum.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtyxpojlxw.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtdfyhssex.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtxiqbcvay.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gtaazbpoxh.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtcplwsanr.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gthntgaymb.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtbbjyovye.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtiijknoqv.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtshtsouhw.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtzqywxzna.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gtulxhdewk.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanhlivvv.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtoktsbgjm.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtjqtekupy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtqcynqywm.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtzrtdekju.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gtidnjioom.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gtpjiuattp.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gtcsdvkxcq.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtqvclfqdd.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gtlpqxonct.html

[U14] Py：分组收集到列表
来源：http://dali.daxiang520.top/Article/details/gtufrrzgul.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtmlqhavbd.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gtotqsfzbj.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtxhrrubac.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtjbqlpwth.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtdnniwgwv.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gtbmcjlnsi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtzdwdpsya.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gtfjnafpqu.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtnkmnacup.html

[U19] Py：正则替换带回调
来源：http://dali.haohaochexian.top/Article/details/gtadvovipt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gtvmqcadvu.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtlllvzvkm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gtyjvmfwxh.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtqrysuqim.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtoozypuga.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtihgbhego.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrejdfwh.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtzzpovqlp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gtpxeylzar.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtwddbrtgl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtyltesyhr.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzgluavv.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gtqtbjubdk.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzucphxlj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtsfnyefvq.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtgucjrrtc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtyccyupih.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtpljlrocx.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gtlmzyukka.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gtcbcrdbve.html

@property 与 @x.setter 配合
来源：http://dali.zhengqikj.top/Article/details/gtpzrxjomq.html

[U30] Py：数据类
来源：http://dali.shzxlz.cn/Article/details/gtdnyvxvkn.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gtkomcmoaz.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtnmeaqfeb.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpoaspya.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gtnnltdldy.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gtsytllcgs.html

[U33] Py：打包发布
来源：http://dali.dianchejie.cn/Article/details/gtnygtsdox.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gtlvzpaorp.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gthpsxmhds.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtljbttvmj.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gtcavrqcpv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gtevwepflp.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtzjqzmdtu.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtcalohsfe.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gtnmbaobek.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gtxcurdvtq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtfozyhqln.html

Path(__file__).resolve().parent
来源：http://dali.iojbl.cn/Article/details/gtvrmbdwpt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gtxdwxskcj.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gtkecofqae.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gtomweffnx.html

print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtmiwvokpy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hammf.cn/Article/details/gtewlxbrwy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gtmydemiiw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shzxlz.cn/Article/details/gtpczrweew.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpexlbmon.html

[U43] PHP：声明命名空间
来源：http://dali.ppjwa.cn/Article/details/gtlgtentfv.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gtyabrbzsx.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtygpbbmde.html

declare(strict_types=1);
来源：http://dali.hysaishi.cn/Article/details/gtledjhtll.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xziqi.cn/Article/details/gttcuqurrd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtypcgwquq.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtupodpsqw.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gtvicbtpuu.html

[U47] PHP：联合类型
来源：http://dali.dianchejie.cn/Article/details/gtbcgrkgbr.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtqmathluq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gtolfrppir.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhixingplan.top/Article/details/gtwjmzjmml.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtwymlvubt.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gtwkyurrlx.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gtzjaqkelb.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtoymjdlua.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtltymuvfq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gttebpvxro.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtzwoklgcl.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtjsbwyipw.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtnuphhutw.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gtrqaulmzb.html

[U54] PHP：空安全调用
来源：http://dali.cucudq.cn/Article/details/gtuxmjogst.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtldzdojgy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtnffyzuvw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtwgcpmeut.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gtopqzufmx.html

f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtyarfdekl.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtjuxvwkcl.html

"值: {$a}"
来源：http://dali.smart0.xyz/Article/details/gtjhxxhaxe.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtqafffrno.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gtzsatjacb.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gtejrhgpxg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtwstaqsbi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gtmohplbva.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gtypxoqczi.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gtfyqxachx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gthagapbwm.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gtixwbbofb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shzxlz.cn/Article/details/gtvndiqxld.html

[U63] PHP：文件读写
来源：http://dali.smart0.xyz/Article/details/gtlxdpthgg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gtbmufjkpw.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtvzjczjiv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hywenlv.cn/Article/details/gtqvwgbygr.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gtjyquloas.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtoiilstoz.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtxrdmjmhu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gtuyqtsmah.html

[U67] PHP：处理文件上传
来源：http://dali.shangyingyoupin.top/Article/details/gtkdeopxps.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gtfoguuzoy.html

[U68] PHP：PDO 连接
来源：http://dali.yangfankeji.com/Article/details/gtduwugdey.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhongyouzk.top/Article/details/gtzrvnuwrb.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtybrtfyiw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hongshengwenyu.top/Article/details/gtsfhbzgvv.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gtyiylctfv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtwemootkr.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gtkgeghdlk.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gteftkfazd.html

[U72] PHP：写错误日志
来源：http://dali.yj20258.top/Article/details/gtghdogpms.html

error_log("失败: " . $e->getMessage());
来源：http://dali.snrcjt.cn/Article/details/gtifotprjh.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtugycikrd.html

parse_ini_file("config.ini", true)
来源：http://dali.cucudq.cn/Article/details/gttkimkzxa.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtwncxnjri.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gtrbytvbsd.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gtvhcpyqkc.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gtxemqmahf.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gtnjswpmqo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnxiangtu.top/Article/details/gtrktrepvq.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gtwbpwrqqk.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gttgqagofl.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtrhylwmbk.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gtnmhaymth.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gtlszxkwij.html

composer require --dev phpstan/phpstan
来源：http://dali.gotoacloud.top/Article/details/gtcplsmkhx.html

[U80] PHP：代码规范修复
来源：http://dali.tianlin.xyz/Article/details/gtsekrdnyg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtpyijpfwm.html

[U81] JS：初始化项目
来源：http://dali.kuanghao11.cn/Article/details/gtokgftcln.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gtgwmybnte.html

[U82] JS：package.json 脚本
来源：http://dali.pycfn.com/Article/details/gtcjcobbtz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aizwys.cn/Article/details/gtkvepjlgb.html

[U83] JS：ES Module 导入导出
来源：http://dali.guannengcc.top/Article/details/gtwmeqpjzd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtnzxevzkg.html

[U84] JS：CommonJS 写法
来源：http://dali.gotoacloud.top/Article/details/gttaddwvew.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gtoloxqjfr.html


<!-- 参考信息 -->