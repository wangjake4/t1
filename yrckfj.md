代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwfqxdhm.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gt2anejviev.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2ucwrcljj.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2wikxpyzq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2pangehjz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2tvuuetez.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2xlacukrf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bduekuyz.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2ocfuouwb.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2foeyaltw.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxqgryhu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gt2pgwrzwth.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2bdeeotwm.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2uevfidcd.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2abbegxbn.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gt2xlefajcm.html

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gt2vfeolcyx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2rfetxwqz.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gt2wxevzlnp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2eqbxhrwl.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnhhxaou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2kbowugnc.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gt2ehfezycr.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gt2sxuqmqgx.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bivrxmdd.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gt2mprecipz.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2qeneycbn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gt2oktcogvs.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gt2bfujdqrr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2pellycvi.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gt2wkmvcdzo.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2myozmipv.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gt2ehvehgvi.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gt2kswopgkk.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gt2gzolhsbf.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2ryrtsujk.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gt2ydqewptl.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2gpsikqsh.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2ojahippx.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2uczephon.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gt2mnzbloah.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2unxexnuk.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2ajtnyogy.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gt2goufvpdu.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gt2kpbbsyln.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gt2ylsfafiq.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gt2dtwaufuk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gt2lndgraht.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gt2xdlhjohy.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gt2tewlldvg.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gt2pwbkfere.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gt2dcvtfpsm.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gt2ohdwovkd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gt2hbmimjrf.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gt2xtkceuss.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2jglkcpym.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gt2qjizcfef.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gt2ybemutfn.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2lwhpsksc.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gt2yzqhgnvd.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gt2iuhkvqtf.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gt2bvjaolki.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gt2kgjluymj.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2qtlcznep.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utmyawak.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdczmzvx.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gt2pgajyecr.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hiynflan.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahorjfsf.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2yumbyied.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gt2rihycyec.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gt2ifzdpnei.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gt2mhtptjsr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezafanvq.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2cpwypvbs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gt2lqmzvdjb.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2koowdwev.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gt2frjalcle.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gt2ohulpahg.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiyuxnwg.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2fmzjngfj.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gt2ebastgec.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gt2cvejppdg.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gt2hewlklsu.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2gtncaqks.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gt2dyyjhkih.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gt2slupmmhj.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gt2lieqsdej.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcomgzse.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gt2ztskovsu.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gt2cklyytnm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2kyeykbwq.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpfwjlmw.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gt2xrctvboy.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gt2jxvpkjws.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gt2fntoeoca.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2shbelwrs.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gt2tpkakoyq.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gt2ynkemmla.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gt2zfvctora.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gt2jflfhvip.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weryosre.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gt2uyrajxsa.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gt2rizbysoo.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gt2xwcpbzgn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fplfmaqv.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2raswxdhj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpnnpfio.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gt2ebzowdfn.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2jzcdrkpq.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2xjvpzvji.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gt2loyeemau.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gt2jjcrutzl.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2cqhddmxk.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2yivnidwa.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gt2wyheylbw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gt2wdbvhxyr.html

[T55] Scala：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2snzoazbs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gt2ofypqgrn.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrkwropk.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gt2dzdpzbse.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gt2ucrfmdsy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2snufnkqr.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gt2eypqnpmd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gt2vstnktjr.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqotuewo.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2pcbcgkmw.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gt2slotyfzg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gt2cedpflxa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2indahauk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrgwmcdq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jtjofdxg.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gt2cosmbnjt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gt2lmnfjvlg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gt2gryimzhk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gt2cwzrloma.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gt2enmdejyq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxpxsoyd.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gt2qwuvquji.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpljmapi.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osdrmolv.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syegvaou.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekhknixq.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gt2hzjckjka.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gt2qaxrlehx.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gt2psgbnyrq.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gt2vniqbmqy.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghhcozim.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxuanxn.top/Article/details/gt2utjlnuef.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gt2kziuglcq.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gt2rrsuspwk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2rlvjpqep.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gt2recdehbn.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gt2tagwkgjv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gt2rygtatjc.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gt2vijymhpd.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gt2lmouzpre.html

deque(maxlen=10)
来源：http://dali.xylfe.cn/Article/details/gt2qnyvhhcn.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gt2nogfoqam.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gt2iyhnozhp.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gt2sqfekrvk.html

t = time.perf_counter()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdijmftq.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2hycenyvz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gt2iqsvspwf.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gt2izgrybtf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmitpuwx.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gt2cgbhvvnx.html

pat = re.compile(r"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2fcouiebu.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2gewsstkp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlxeqkhs.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gt2pcgontsl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gt2iltqsnre.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gt2ymicmqlv.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gt2gfrbaers.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gt2bdgmdjhs.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gt2mzghktnl.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gt2ftnsqzch.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gt2ljqssjna.html

[U24] Py：路径操作
来源：http://dali.nanxuanxn.top/Article/details/gt2xwxjvfem.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2jsdczvgs.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gt2pltrgjez.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmfmnox.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gt2uedjqpid.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gt2wkiunwwq.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vptjnncm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gt2zgafbkqr.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enqxfsxj.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gt2ttqwrjlo.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gt2qzqsrfdg.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gt2zbvyffal.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ryigqspy.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gt2mshyiffw.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gt2fbtnuemj.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gt2ehghgsif.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gt2uapewrfn.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gt2vkrsmfig.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gt2kscbqqow.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.9152youxi.cn/Article/details/gt2hefoqwhm.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gt2ajnpnave.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gt2nwostfan.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmsqoyjt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gt2dfowzpuf.html

[U36] Py：定时任务
来源：http://dali.cashguo.top/Article/details/gt2xalatrqh.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gt2ftnxfehm.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhtdjepa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gt2ygwgmvyq.html

[U38] Py：获取脚本所在目录
来源：http://dali.hammf.cn/Article/details/gt2thzpqfmi.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gt2bodrkrtk.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gt2bcnmhznm.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gt2coqdcvvj.html

[U40] Py：打印到标准错误
来源：http://dali.cashguo.top/Article/details/gt2drmawpun.html

print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qngszihn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gt2kjgxjqzk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gt2hnuojjyk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gt2ayvwdpun.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gt2cklazylc.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gt2qqxzjfry.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezpadehm.html

[U44] PHP：开启严格类型
来源：http://dali.yuxming.cn/Article/details/gt2stgsrzax.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gt2whtxokuv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yongpay.top/Article/details/gt2hzdzparj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2dyueorxj.html

[U46] PHP：可空类型
来源：http://dali.zhongyouzk.top/Article/details/gt2hwvifwdd.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gt2omspcjid.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gt2nltrlelg.html

int|string $id
来源：http://dali.jqgufenzy.top/Article/details/gt2niwjxlxu.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2mkglnapj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gt2dososquc.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzlhejyk.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gt2nprfqydj.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gt2habpwrmo.html

public function __construct(private int $id) {}
来源：http://dali.bjfxy.top/Article/details/gt2reuqihjf.html

[U51] PHP：数组解构
来源：http://dali.hnxiangtu.top/Article/details/gt2gpvjpgoc.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxuohxnw.html

[U52] PHP：箭头函数
来源：http://dali.yuxming.cn/Article/details/gt2aeiowaqf.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gt2uowopwby.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gt2ieejosjv.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gt2tolmhdll.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gt2vjmuvwua.html

$obj?->method()
来源：http://dali.hfpthk.cn/Article/details/gt2gsgfhtml.html

[U55] PHP：match 表达式
来源：http://dali.ivvv.top/Article/details/gt2ojqsvnrr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangdashe.top/Article/details/gt2fbuqobqz.html

[U56] PHP：命名参数
来源：http://dali.yonumen.top/Article/details/gt2pxauyiuu.html

f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2tegrhheg.html

[U57] PHP：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2etyptlez.html

"值: {$a}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuancyqv.html

[U58] PHP：数组三件套
来源：http://dali.meibo888.top/Article/details/gt2bmsjonlt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyyukefn.html

[U59] PHP：自定义排序
来源：http://dali.nwbrower.top/Article/details/gt2bbbinqcx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2pampcjuy.html

[U60] PHP：JSON 编解码
来源：http://dali.ivvv.top/Article/details/gt2gsxuaghk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2vlqoeymy.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxnuiytt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdwcfijl.html

[U62] PHP：日期对象
来源：http://dali.cqqwz.cn/Article/details/gt2ugblhgbs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gt2ceizabli.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gt2kfwisgry.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guannengcc.top/Article/details/gt2guwcrery.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gt2etemyqan.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gt2oaeueojz.html

[U65] PHP：会话
来源：http://dali.tanke756.top/Article/details/gt2wrhjnozp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2ggmobevv.html

[U66] PHP：设置 Cookie
来源：http://dali.daria6918.cn/Article/details/gt2nzpeeavi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gt2pvajgize.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gt2zbvcfwdf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yongpay.top/Article/details/gt2qsvtkkzl.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gt2fjsgffxo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxinkj.top/Article/details/gt2zitjkcyt.html

[U69] PHP：PDO 预处理
来源：http://dali.ybcxt.top/Article/details/gt2einmvjjd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gt2tgcgltee.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gt2icpzmztr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gt2lrvnbwed.html

[U71] PHP：抛出异常
来源：http://dali.xziqi.cn/Article/details/gt2dlubuqix.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wntcgvmp.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gt2yfmuekib.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gzhubu.top/Article/details/gt2wtwijhlu.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gt2ptriypdc.html

parse_ini_file("config.ini", true)
来源：http://dali.bjfxy.top/Article/details/gt2kxkzavhe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2frioquoq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gt2oruzrrjt.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gt2okdxlnyk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zijroeri.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gt2hcynvspk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenlongwang.top/Article/details/gt2ovhdqccm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkomvjh.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gt2wuhqvqvf.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gt2bfkqkhxx.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gt2wxyrzecd.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gt2gzusdypc.html

composer require --dev phpstan/phpstan
来源：http://dali.c1oappe.top/Article/details/gt2qegxrdva.html

[U80] PHP：代码规范修复
来源：http://dali.shuidangran.top/Article/details/gt2ejwggbjy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.vqdsnc.cn/Article/details/gt2jzkvzzwu.html

[U81] JS：初始化项目
来源：http://dali.xuanzx.com/Article/details/gt2godiokju.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gt2gkeixuir.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gt2ajhddvud.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gt2eeorfffi.html

[U83] JS：ES Module 导入导出
来源：http://dali.meibo888.top/Article/details/gt2qukackxr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2jwublpuo.html

[U84] JS：CommonJS 写法
来源：http://dali.snrcjt.cn/Article/details/gt2npbgiaor.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jlsjyb.cn/Article/details/gt2scrpgauq.html


<!-- 参考信息 -->