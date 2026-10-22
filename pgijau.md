代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gt2epnboikz.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzlprjot.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2dqcidcvh.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2ayjhbuhc.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2upnghloj.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gt2wvizeuaf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gt2aulmqsgg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsppndm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2segnptwj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2qjeczllp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2kkukyrne.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzinypjt.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gt2ayzlmeci.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2wlpwgfkf.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2jggweqww.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gt2rairarsq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2xjmpdkoh.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2tjsswxtf.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gt2ixlnyvbn.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2mffgtsdd.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gt2ekegugkw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gt2zylbcmwb.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2mdgkhbzs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2bbgfrxlm.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2gbpveeoq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gt2yggbozgg.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2fqmefgjp.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2tiuoebbk.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2yuuefvvs.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gt2wpsaeiud.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gt2ttvlunus.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gt2rghgiloj.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gt2qtsddovi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2qynhfckz.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gt2cnvdwbni.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2uabcbnrf.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gt2fbisuqgc.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gt2iqrxuxjx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2deaxalfk.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2aucdsjwe.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gt2jlpyddxr.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2wglxxhxl.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2psytuzwu.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2hlilkvct.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2dbrfgktp.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gt2xbdfmsrt.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2shkkpltg.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gt2uixzmbla.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gt2iavzibyg.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gt2kjpolnzb.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gt2zadwovzh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfosmcoi.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gt2ehrzxiks.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyxpjpic.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gt2mwgdbrjy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gt2noquazdu.html

[T23] Swift：函数
来源：http://dali.ybcxt.top/Article/details/gt2wrumxuug.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2lgjketjv.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gt2iebxicss.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2vvayhmqa.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gt2vqdbnklj.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gt2erbuthkk.html

[T26] Swift：类与重写
来源：http://dali.zhengqikj.top/Article/details/gt2pzklqpfx.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gt2gpqccbas.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gt2rhlvjmgu.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2iqzuvhga.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxaasdnb.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gt2kaiygcck.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcmasxng.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gt2qknucfmy.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2baxirfys.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2ayehqjob.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2obxzbfhu.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2bzjwhjlz.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gt2getxfauv.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2obxlqing.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2wjwqecry.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dodhpaec.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gt2ojtxsgfk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gt2nekwifcb.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gt2cbhulprx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caqlowaa.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gt2akutqiux.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gt2zpimgaur.html

[T37] Lua：字符串拼接
来源：http://dali.sweek.top/Article/details/gt2kdyfsdwr.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gt2gkwfyyci.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gt2ldlxnxkt.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gt2fupxkfob.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gt2tfuwxrzr.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gt2cxxpaksv.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gt2rmyputcr.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gt2vwbpjlig.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2vxreqexg.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2goszsygq.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gt2glnivzze.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gt2oonmmtwr.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2thdacpcj.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gt2mmlillft.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2azczvape.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gt2ejmznwgi.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gt2nzzgapyt.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gt2wcaeczlq.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gt2wwlwheuh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gt2zfytrltw.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gt2uavmrdvx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gt2luweqgrz.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2dfpvshnj.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gt2jymvkytw.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2zwzfkchf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2ngnsjuwo.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2vnitnial.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gt2jjpocfzj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2lzaebydw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwxglgx.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2isfprsog.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gt2beuxlyru.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2ytxxcmrg.html

[T53] Scala：字符串插值
来源：http://dali.ybcxt.top/Article/details/gt2hudhvzvj.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2dfxawisy.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayhtaxuc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gt2rfhmtadn.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2wbbrollb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gt2kupbhafn.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gt2nfnrkllq.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2yevqlsbw.html

[T57] Scala：模式匹配
来源：http://dali.shuidangran.top/Article/details/gt2yaicaern.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gt2mqmvpgdq.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gt2bskmgnkt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2dqavvttw.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gt2hrfrwces.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2mxuuynlv.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gt2vwcycjjb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gt2ytfjpyka.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ixsuwvqi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gt2lgwghqud.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2mxjtuvew.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gt2agpwhxso.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gt2jhiehmnm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gt2jcsgxdmd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2wxmvvtws.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gt2kveoeluz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gt2cppzldvi.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gt2jtxvdtzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixtzynzv.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gt2kwgpymec.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gt2gcumrzta.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gt2nlbflhvh.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvjgqaei.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gt2pcfhrnpv.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gt2vxezukpf.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxdvvoqj.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gt2dyfaueer.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gt2rlwraaiq.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gt2sktiixtl.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gt2ilgswtja.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gt2zkhuimkm.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gt2desowhdd.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gt2motwwbiu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gt2ryemnlay.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gt2sdiogezf.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gt2rlydiltq.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gt2zehtqvyt.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2ujaahfuw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdknjwyj.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gt2uumnljsp.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2fvhthyyu.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdifaafh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gt2cagqzkji.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gt2cpovjmcs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umagonyp.html

[U18] Py：预编译正则
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbhespug.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmhkpcaw.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gt2mvonxkgz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.snrcjt.cn/Article/details/gt2bfohqxdl.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gt2ysumuxzd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gt2eknurxpg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gt2ivxnkwql.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gt2givxbihb.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gt2vvzthnki.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gt2wakdqjiy.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gt2bxfpziqn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gt2xwoqfegs.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gt2kpjdeqbu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxdlpmbl.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gt2cechxrss.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gt2edssrjcr.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsyqnhmh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ppjwa.cn/Article/details/gt2qguzrizx.html

[U27] Py：异步 HTTP
来源：http://dali.yuanzhike.top/Article/details/gt2ekkdwssp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gotoacloud.top/Article/details/gt2pminodrd.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gt2ulllqctx.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gt2edvlvnks.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gt2hzgmzovj.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gt2qfwjqlgr.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gt2fhfwxgcz.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gt2btkijlyf.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gt2pmrshfzz.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gt2vtxwidga.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gt2xtgpcihv.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gt2uhqrvqfo.html

[U33] Py：打包发布
来源：http://dali.zhengqikj.top/Article/details/gt2iakjlfzf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gt2rfjgadpb.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gt2gprokrsb.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gt2tqtwzizp.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqzkmjdi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuanzx.com/Article/details/gt2elaajytv.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imjtswwx.html

schedule.every(10).minutes.do(job)
来源：http://dali.9152youxi.cn/Article/details/gt2xhvtyhgi.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gt2ejgabwpx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gt2qjvbnpvt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2izetnonh.html

Path(__file__).resolve().parent
来源：http://dali.hnxiangtu.top/Article/details/gt2pnlcmhiv.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gt2sjucruxk.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gt2olkkrung.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gt2rmzjfzrr.html

print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gt2bhgfbukp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gt2sfqbsbbk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gt2eykobmqx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dianchejie.cn/Article/details/gt2cxfwozoe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gt2ehcodfpx.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gt2zirpxeds.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gt2kcqeuyje.html

[U44] PHP：开启严格类型
来源：http://dali.zycfv.cn/Article/details/gt2iihooryr.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gt2quvxgxht.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gt2lzntlxpq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2myteyaic.html

[U46] PHP：可空类型
来源：http://dali.guowangkeji.top/Article/details/gt2ubkzdfcz.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gt2eucujqpl.html

[U47] PHP：联合类型
来源：http://dali.xziqi.cn/Article/details/gt2ntlfqkck.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gt2jisevbtt.html

[U48] PHP：纯枚举
来源：http://dali.aibaodan.cn/Article/details/gt2hxikzkas.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gt2pxnhffhp.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gt2gskunpqx.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gt2ruzvveho.html

[U50] PHP：构造器属性提升
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntjkiymk.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gt2qqhnkcoi.html

[U51] PHP：数组解构
来源：http://dali.guannengcc.top/Article/details/gt2oxhtnoje.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfkkvqqv.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmfjleds.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gt2xksfpnjk.html

[U53] PHP：空合并运算符
来源：http://dali.svipenyu.cn/Article/details/gt2etlgufbn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gt2yzftljzl.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gt2wqkqyjck.html

$obj?->method()
来源：http://dali.quarkkingdee.top/Article/details/gt2zwutuxzo.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gt2blqviptg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sxryk.cn/Article/details/gt2fzomyakk.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gt2kbphewid.html

f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgzokuzk.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2ynjeqplf.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gt2srkeopuz.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gt2sfquftso.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gt2ccyyixwo.html

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gt2ednyctnn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2wcmzckym.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gt2oombxazi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2aryomeov.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbxgriux.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2bxhzvfpp.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gt2jkaktard.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guannengcc.top/Article/details/gt2umfazrho.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gt2wvbwowuj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cucudq.cn/Article/details/gt2nzhnsjmj.html

[U64] PHP：目录遍历
来源：http://dali.xinyue.icu/Article/details/gt2rdjjpkkq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.mhx1999.top/Article/details/gt2fubevkyx.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gt2rolxkwno.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2kaavvixs.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gt2igshgpyr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2vrvbxbkk.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2delbeqig.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gt2xqamoauq.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gt2wthwbzuy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gt2vcdxtwhr.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gt2zzocioaj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gt2rjtierao.html

[U70] PHP：PDO 事务
来源：http://dali.aibaodan.cn/Article/details/gt2bdgreqtb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gt2fuhcibzt.html

[U71] PHP：抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2yviavgdx.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gt2luadblin.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gt2rvaqjdyo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofdbpzxm.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgasvewm.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gt2kberewei.html

[U74] PHP：读取环境变量
来源：http://dali.yueranfly.top/Article/details/gt2vlppkzcy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.quarkkingdee.top/Article/details/gt2rcvfxbfa.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gt2qniienhf.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gt2rezkvtcn.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gt2nyohaqxf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.vqdsnc.cn/Article/details/gt2kspvntlm.html

[U77] PHP：模板渲染
来源：http://dali.zhongyouzk.top/Article/details/gt2jvjadlai.html

composer require twig/twig
来源：http://dali.smart0.xyz/Article/details/gt2tuscaihx.html

[U78] PHP：单元测试
来源：http://dali.hfpthk.cn/Article/details/gt2arlrdkuv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2wvrdsdwx.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gt2hiljdoic.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gt2yciccyau.html

[U80] PHP：代码规范修复
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhfbtyef.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gt2whykzlcg.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkskppvt.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nllptkvc.html

[U82] JS：package.json 脚本
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfacdisa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnqzz.top/Article/details/gt2psxuerlx.html


<!-- 参考信息 -->