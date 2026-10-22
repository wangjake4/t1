代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vjgusgmu.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gt2ilsaamut.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2magikpfs.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2injuamhp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2utabnszj.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gt2mwrvpvvi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gt2gktwibpx.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2mbmytgdo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gt2kddmcbvg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xvqiaysg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgrahcae.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2orrhityc.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2joiyheuc.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2hfrdosxs.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2imrfljhd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2oykzyqho.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhobmonb.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2nzehjudv.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gt2uavbfcvw.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gt2xysseovq.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gt2cjuxnjrr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gt2fyazqrho.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2vbopniwa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2clpvdeiv.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2lvdeikeb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2yblykzcn.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbpqxuay.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2lwxoshrs.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gt2pfsorneo.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gt2qjrytzqe.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2mrilzbik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdgloqzy.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gt2xrztxpak.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykqckaeu.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2iydmjkuw.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2dzcesfsl.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2mnscciln.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2gedxkodd.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2dagnrzio.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gt2wzcpbrui.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gt2dfwirbiy.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gt2vyvcwbix.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scpufetg.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2fvicegdh.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2bizvvtmh.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccsvhucw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zshudwbz.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gt2jgrzdefl.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gt2hpculvhp.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orunzujv.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfzskuiw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gt2rygzpbmo.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smcxtibf.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gt2uafdhvou.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gt2mcaxvdvg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2undiubfi.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gt2iwmnlbaq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2eijjfbhg.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2mawacatf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtvwaemc.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gt2fftjworm.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gt2tjmowayr.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gt2gtotbill.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gt2eltgdzxx.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gt2dcejgwaa.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gt2awcxisqy.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gt2fkjbalxw.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gt2vsrqbpam.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2ltcsgmly.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2mnmojdky.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2badlzriq.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgqponth.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2vxroeehv.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2ysgoxdpq.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2rovutstg.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gt2nawherts.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gt2sbzqmiec.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gt2scfmuqfr.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gt2vzbjwlfk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gt2bdfglwvu.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfuhhfbw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pekplpqw.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gt2poyrxngt.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gt2lsiunuen.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgeljjve.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gt2sdpclxjy.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gt2mljrpguq.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gt2xgenfhog.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2pkycnqhz.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2pvfoqxnn.html

[T40] Lua：元表
来源：http://dali.yj202588.top/Article/details/gt2yhkevncq.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqibvxyt.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2xtvzyexl.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2ugzmsiod.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gt2xslyivfd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2pqclnhtc.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcofmbbt.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gt2ygxohikn.html

[T44] Perl：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgoqxtne.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfcmfsws.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gt2dafqqgvq.html

for my $x (@arr) { print $x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzodzaeb.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2gcrdzktj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhqwaro.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gt2slfocmnk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gt2wisdqwfb.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2gkjgonmm.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gt2defptzdb.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gt2iaxmcpil.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2qrewgbps.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2bhaewesy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gt2zcltzrgg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gt2sgyegffy.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2zjisvqaf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxolbju.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2leklnnfo.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gt2lduoxdrf.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkvopssz.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2iejkskiq.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2cnfzwqzh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gt2lyvqliyh.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gt2pxupgfgw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gt2vzilceog.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gt2pwokevoi.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2uhyuwifi.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2ulzdulhv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gt2etfbrmqk.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2ggpyqdtr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2xbviffiq.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gt2qtinvbdh.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2rbyszjmi.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gt2ryuvdltr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axwdaymo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2hervtjtk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gt2pcmozbqv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zgfodwku.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gt2bqaiwrvc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gt2lqdrszeg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gt2pajnjzke.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gt2ueigkztx.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gt2teztminn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gt2hqpyspvq.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arsuqlwp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gt2jhshauxf.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gt2ohzehlnn.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2quhdxdyb.html

[U06] Py：合并两个字典
来源：http://dali.meibo888.top/Article/details/gt2nalbufsu.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chkznfhu.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gt2jjvnbcvn.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gt2ncfgyazn.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gt2nwhfurgb.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gt2eupsyhfo.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gt2gxqbleei.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gt2crumevcf.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gt2cxucnjnc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gt2pkzfwtqh.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gt2bbqnjigf.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usrirdot.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktqsrifd.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gt2trysmnnl.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gt2lvngftog.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gt2ycaxkmey.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gt2kvdtlnjs.html

defaultdict(list)
来源：http://dali.guannengcc.top/Article/details/gt2jqsynems.html

[U15] Py：高精度计时
来源：http://dali.hammf.cn/Article/details/gt2ueejylvn.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gt2zdhopqvl.html

[U16] Py：命令行参数解析
来源：http://dali.aibaodan.cn/Article/details/gt2tijfqtik.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gt2ayxxphow.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gt2jbeblgle.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gt2dpoqsmrt.html

[U18] Py：预编译正则
来源：http://dali.shangyingyoupin.top/Article/details/gt2jajwlnbe.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2gblksibw.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gt2lnfbhrte.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gzhubu.top/Article/details/gt2cvhvtpxw.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gt2cvbdonbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gt2tvjlxegj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gt2ysuwlrso.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gt2owzevwoy.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gt2zqjcufcw.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gt2daiiiues.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gt2wizjsjzr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gt2ogfeoiur.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gt2pjqusoor.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2xpfpepmg.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gt2aivifnex.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gt2nzrvhpjm.html

[U26] Py：并发下载
来源：http://dali.guannengcc.top/Article/details/gt2azngpscd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gt2zmpicqwy.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gt2bzwlbkyz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gt2zjkvgumi.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzwmkuyr.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gt2txswoxlu.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gt2dovfhfec.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gt2vmwijtpo.html

[U30] Py：数据类
来源：http://dali.yvedp.cn/Article/details/gt2mrneqrih.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gt2jenjxdbp.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxuwgxev.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gt2hptibmfl.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gt2qfhlclep.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gt2kcwstvwj.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gt2rehcgysn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gt2amuouufw.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejrwhtgd.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwcvmrnd.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gt2pmnervhp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbmveheb.html

[U36] Py：定时任务
来源：http://dali.hnqzz.top/Article/details/gt2srvhbbpf.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gt2tqwkpekg.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gt2vruubxcs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2cytijlkd.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigufen.top/Article/details/gt2vbxqeayg.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gt2xmfqwiba.html

[U39] Py：判断是否在交互环境
来源：http://dali.yvedp.cn/Article/details/gt2rzezufra.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gt2glpluunn.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gt2trqwbqga.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2mclmaqsk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jianghu66.top/Article/details/gt2qboccaat.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pycfn.com/Article/details/gt2pdtdxkvz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dianchejie.cn/Article/details/gt2yijceccf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gt2jtuenjxr.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2fjdrsxvg.html

namespace App\Http;
来源：http://dali.mhx1999.top/Article/details/gt2sfyietju.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gt2mplemlws.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gt2vgpkllfz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ppjwa.cn/Article/details/gt2ekxvxepx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2ilttbbtp.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gt2yjrrylrt.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gt2awpyfsjy.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghduomgo.html

int|string $id
来源：http://dali.gaohongyu789.top/Article/details/gt2lkbsbtjv.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gt2vfekufeh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gt2rerpwfox.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gt2vkttjrir.html

public readonly string $name
来源：http://dali.0kj1m.cn/Article/details/gt2tivfrdod.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ooudlzpp.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2htjacapr.html

[U51] PHP：数组解构
来源：http://dali.cqqwz.cn/Article/details/gt2hzzsnqau.html

[$a, $b] = $arr;
来源：http://dali.zhengqikj.top/Article/details/gt2umueqrmo.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2sfvrkbzw.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhzjkztq.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gt2shkufxct.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gt2acltlrlk.html

[U54] PHP：空安全调用
来源：http://dali.hammf.cn/Article/details/gt2scflpigc.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gt2hucvjvwk.html

[U55] PHP：match 表达式
来源：http://dali.fengsongda.top/Article/details/gt2wzxvksxj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gt2urggwqkr.html

[U56] PHP：命名参数
来源：http://dali.daxiang520.top/Article/details/gt2zeoiuhmp.html

f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2gdrujnsa.html

[U57] PHP：字符串插值
来源：http://dali.yonumen.top/Article/details/gt2guboiree.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gt2nanlmkqe.html

[U58] PHP：数组三件套
来源：http://dali.jinqigufen.top/Article/details/gt2pzzjsqjw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2goqygyqt.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gt2bwtsgtjf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2uamdccer.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gt2ywocpvvv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gt2ytpykemx.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gt2ayscfmvl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gt2kmbxpuae.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2raqnqqrq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daria6918.cn/Article/details/gt2kcaszycn.html

[U63] PHP：文件读写
来源：http://dali.cdnleiting.top/Article/details/gt2zcxyudzi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gt2emcjpusi.html

[U64] PHP：目录遍历
来源：http://dali.birdmap.top/Article/details/gt2xofpslkg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzhpujrf.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gt2maumtgzg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2ebfytcge.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gt2lppgkbwf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gt2fgpwnwoy.html

[U67] PHP：处理文件上传
来源：http://dali.nanxinkj.top/Article/details/gt2tzmsstlz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gt2rarstixw.html

[U68] PHP：PDO 连接
来源：http://dali.shuidangran.top/Article/details/gt2vakgucjc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hammf.cn/Article/details/gt2blnzwvac.html

[U69] PHP：PDO 预处理
来源：http://dali.zhoulong.xyz/Article/details/gt2htwtlkte.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gt2wkgamtim.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258.top/Article/details/gt2powxmzxd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yongpay.top/Article/details/gt2uutzmqun.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2gbmiphmp.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fismgfck.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gt2bxlovokc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dashuyun.cn/Article/details/gt2ilpmbexs.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gt2utbhywry.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gt2jtpxvsst.html

[U74] PHP：读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2kqnfgicg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yueranfly.top/Article/details/gt2npbnskbj.html

[U75] PHP：依赖注入
来源：http://dali.yuanzhike.top/Article/details/gt2vhjvfnvm.html

composer require psr/container
来源：http://dali.aizwys.cn/Article/details/gt2tjrlzvns.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gt2ifedumso.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gt2ihflegif.html

[U77] PHP：模板渲染
来源：http://dali.kuanghao11.cn/Article/details/gt2tullwoao.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gt2heqswcdd.html

[U78] PHP：单元测试
来源：http://dali.cashguo.top/Article/details/gt2yndhoatv.html

composer require --dev phpunit/phpunit
来源：http://dali.gogol.net.cn/Article/details/gt2bjiogrmn.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gt2mokilxec.html

composer require --dev phpstan/phpstan
来源：http://dali.tian-w.cn/Article/details/gt2zcqtiomz.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gt2ctjhmqbb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gt2rehvrcwn.html

[U81] JS：初始化项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqoquxdk.html

npm init -y;  npm i express
来源：http://dali.kuanghao11.cn/Article/details/gt2owfrhweo.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gt2xywcoimx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gt2bdqjxqbb.html


<!-- 参考信息 -->