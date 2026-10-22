代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gt2owhktkrg.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2gqtcwnmg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pevshybn.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2arygaooh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2wvgbbrka.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bziupeyh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twwljdyr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lkxhybhz.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2kdwizyob.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iekmyrxk.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2exuhcsgz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2dyxeahss.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gt2nwdphsdu.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2iezudvyc.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gt2gzkgagba.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2qpzzieqf.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gejkrfgf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gt2ldqsgeih.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2swmkngxh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2yixulifw.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gt2twxzuafb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gt2cudsxypb.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqplgrvo.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekuqnehc.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gt2pkmteeas.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gt2ateieote.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gt2zxiccguf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gt2agfemesl.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gt2aoluwatw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gt2chijktyy.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gt2tpnhsxiy.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iveyhiqp.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2sxyxzaic.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2tapkxavk.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gt2xpjahdll.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2yqbhbqyt.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozxmgzei.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gt2ihbgemog.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2vztenkpb.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2moiqrgdj.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2bjvkffog.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2mlbiowyn.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpsnqjnj.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2vmuyirkb.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gt2xcdpbhpq.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gt2zkwrrhve.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gt2bgcmsxug.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gt2qwyyocru.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gt2cudbsspd.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gt2rzxvpniu.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gt2ckxikqro.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2osdhuioa.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gt2uhgveffe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2lozqmwnk.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gt2qkeqkhfd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2hcprtzzj.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2zopyafog.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gt2xpoqpzfp.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gt2ubxhdngd.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gt2mnuzrsix.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2dwjaecms.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxgdzioe.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gt2aotlnrpk.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzsouley.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gt2jzmqygwz.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2eueligdg.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2drpfxgjj.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gt2rarkjniw.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2lzaxacut.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2jxsmpzzv.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gt2pqzavrth.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gt2oyirsipe.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqrfrutu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gt2fejamacb.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gt2trlioqye.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gt2pmzptmtt.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gt2dzwuefly.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2urwnwvmv.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gt2ifgmvizz.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gt2nkknqdws.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gt2hzccaztx.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gt2tpufmxtk.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubbleyfi.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gt2zkctcqup.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2luvfcsum.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gt2feiabfzr.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gt2msduzfpl.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gt2rglwowam.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gt2ghtjpean.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2lopbljaw.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gt2qncgpisd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gt2riqhztrx.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2pubyfvie.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gt2grirkybf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyipjdw.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gt2eymntaiu.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gt2umjpcswo.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gt2pwnnhmwl.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gt2qvpkoqsx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gt2voajnsji.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gt2bkakctib.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gt2rlvxhmhp.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2qbbiktmh.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gt2qzdsupkl.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gt2wwmidwbl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2levqlrlt.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2dmuottmb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gt2dgidwqyl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gt2frpcqzar.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysdqoyjd.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gt2rkxcwhrj.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gt2ttxojjui.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2higrbccm.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2qvdmaaie.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2blsuoaxk.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2qumspzlm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gt2ggpwamcw.html

[T55] Scala：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2uxsnhbiv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gt2rgvpymhv.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gt2qqtuutts.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2uqatrwgb.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2jcvcvjab.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2vttfcnjt.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gt2qoutrons.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gt2doxjlnxp.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gt2tgyniktj.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2puwtwxpi.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gt2kqmjkcgd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gt2lgbchtsf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwmnwugy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2gftxkcts.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2txobncnu.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gt2mixutpmw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gt2yyvfdjlk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xziqi.cn/Article/details/gt2qpgtwuew.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gt2cmhradnq.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gt2tladnewp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gt2bakbodds.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gt2xpjezalo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gt2yurhpqsw.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gt2pwprinsv.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gednaarr.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gt2vdauewls.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gt2ahxpctau.html

[U07] Py：反转字典键值
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvpmmqwj.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yalzgtue.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lezbsema.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gt2tmicgnlk.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gt2ebqvdjxk.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulgqcjpa.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gt2zczuziyk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gt2stnzjura.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2taxrxcvp.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gt2jaubsgox.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gt2vrhqwdit.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2obpqzqbn.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veqebivj.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gt2kvnjfcfc.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaajkmci.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gt2jrridslp.html

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gt2dxopvthr.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gt2lpomupqo.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfzqwmyx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gt2zsgxjmfl.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaddvjln.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnxiangtu.top/Article/details/gt2ulxxrxpp.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gt2irpcikeh.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2zxcbevvh.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gt2uhblxfdm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gt2njxnvnxf.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahjpywpv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gt2eswscvpu.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gt2bgdfwckv.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gt2ogjcrodz.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gt2pwfgteic.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gt2tffwvmaw.html

[U23] Py：分块读取大文件
来源：http://dali.gzhubu.top/Article/details/gt2efioymff.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gt2sgriwrzs.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gt2zgwyjmla.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2xggsxqmq.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gt2fubmqxok.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gt2evnrfksz.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gt2cimlylgo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gt2ghuujaam.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gt2aegzcutb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gt2ywdigppc.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gt2bjnivchh.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gt2kjcmwtih.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gt2fyqejbyy.html

@property 与 @x.setter 配合
来源：http://dali.guannengcc.top/Article/details/gt2qzjnzhvj.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbkuhckw.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gt2hgnpfzfo.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gt2stxrdooe.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrcifepd.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gt2mkrlfhxu.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwzsyvle.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gt2umydpyhb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gt2yimaspaa.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gt2qtypemfb.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2uurvqvdk.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gt2qruiovaa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gt2prhjyfzh.html

[U36] Py：定时任务
来源：http://dali.daxiang520.top/Article/details/gt2vygavjbj.html

schedule.every(10).minutes.do(job)
来源：http://dali.haohaochexian.top/Article/details/gt2otmcbtev.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gt2cyojqnjh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gt2hcvafmkr.html

[U38] Py：获取脚本所在目录
来源：http://dali.jyoumei.cn/Article/details/gt2tmqbygsw.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gt2zkhjjkho.html

[U39] Py：判断是否在交互环境
来源：http://dali.bjfxy.top/Article/details/gt2yjoiwvvz.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmdihiop.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ritldsee.html

print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdraotrk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhongyouzk.top/Article/details/gt2rdgoejsi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwqntzdy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gt2vcdyumip.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gt2qnjllhcr.html

[U43] PHP：声明命名空间
来源：http://dali.yonumen.top/Article/details/gt2xblvqlux.html

namespace App\Http;
来源：http://dali.sweek.top/Article/details/gt2vfigzxhe.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gt2fvyzovlr.html

declare(strict_types=1);
来源：http://dali.cqqwz.cn/Article/details/gt2jkyuvbim.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gt2dqttdyir.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2orrfdbpb.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gt2fppdcwnk.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gt2ujcijnoe.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gt2jxxusqxj.html

int|string $id
来源：http://dali.gogol.net.cn/Article/details/gt2uayffkru.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gt2tdrdvxzc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yvedp.cn/Article/details/gt2cqivlffh.html

[U49] PHP：只读属性
来源：http://dali.yj20258.top/Article/details/gt2pvbldzlt.html

public readonly string $name
来源：http://dali.sxryk.cn/Article/details/gt2umlfyfuz.html

[U50] PHP：构造器属性提升
来源：http://dali.pengpengdd.cyou/Article/details/gt2oyozjabj.html

public function __construct(private int $id) {}
来源：http://dali.tianlin.xyz/Article/details/gt2zobcztgc.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gt2iclvtgce.html

[$a, $b] = $arr;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cildjnzq.html

[U52] PHP：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gt2xpllkpkr.html

$double = fn($x) => $x * 2;
来源：http://dali.daria6918.cn/Article/details/gt2itifvpvq.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gt2stmdstpu.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gt2yfaooalc.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gt2xxqfqlrf.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gt2lxzotlsv.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khhomnhf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gt2nlldisgm.html

[U56] PHP：命名参数
来源：http://dali.guannengcc.top/Article/details/gt2kruatfai.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2fyppshof.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2ugqzawok.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gt2qgcjdsct.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzthpsqk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gt2tnfhhnzo.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gt2icotjwmn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2fbmwswcf.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gt2xpedxrzs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gt2dvhqaklt.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gt2zoxeumnv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2mncfollf.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gt2alalfpci.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.iojbl.cn/Article/details/gt2mvxegcnj.html

[U63] PHP：文件读写
来源：http://dali.xuanzx.com/Article/details/gt2rrtnokyl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjbdjgml.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gt2nzqmmdqm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gt2zgrnnaze.html

[U65] PHP：会话
来源：http://dali.cucudq.cn/Article/details/gt2ajtkbvba.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2didoyhch.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gt2nfylusme.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gt2uusnnthd.html

[U67] PHP：处理文件上传
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfpddiks.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvurerfy.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gt2rrwwkhwz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gt2zfezvjko.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxuanxn.top/Article/details/gt2yirsufbp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pycfn.com/Article/details/gt2npnhpfvf.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrakfmjz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gt2frnldqtq.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gt2ucwmjvce.html

throw new RuntimeException("失败", 500);
来源：http://dali.tian-w.cn/Article/details/gt2hmkiqddm.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gt2dailtlgs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxyvprog.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2cgclmzhk.html

parse_ini_file("config.ini", true)
来源：http://dali.iojbl.cn/Article/details/gt2ojdyebhc.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2yiszcvrt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uakctghk.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gt2yqoeedly.html

composer require psr/container
来源：http://dali.yonumen.top/Article/details/gt2ixwaoscy.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gt2qqvkejes.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gt2rrmcmoaa.html

[U77] PHP：模板渲染
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fltwybuo.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gt2tanxaeru.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2uzivinvj.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gt2oymqrnnv.html

[U79] PHP：静态分析
来源：http://dali.xuanzx.com/Article/details/gt2mfsqxtoe.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gt2skdfjojd.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigufen.top/Article/details/gt2vtqhvckh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gt2hubxcaua.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcsweyke.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gt2jfnyebuv.html

[U82] JS：package.json 脚本
来源：http://dali.yanxiufei.cn/Article/details/gt2dkkolgyc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gt2nohngbrt.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gt2bckjilti.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2roopahha.html

[U84] JS：CommonJS 写法
来源：http://dali.aizwys.cn/Article/details/gt2yeafqcod.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gt2aqhnoudq.html


<!-- 参考信息 -->