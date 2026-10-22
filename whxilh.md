代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gt2yqyjsabg.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gt2fnyofujh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gt2yagvlvoj.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2ecmxkxfs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2oajxaczt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2bwhhdqvr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2vrysbtsd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2hwzacqzg.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2jzvqfwog.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2gkifvjad.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjdxpfci.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gt2oxvgrnko.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gt2ggflrjsw.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2fpffrwej.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gt2xwoaikfr.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gt2zpmhqkcn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsywldpy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gt2aomwrvzv.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2ifjpfbla.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2vhfibrhv.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2ijhojwja.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2mnqjkrbr.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2ymxteqlg.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2oqploark.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gt2itxfzget.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2fgelpxsm.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghygkhku.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2eiahkywk.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gt2coqbmhxf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2pjceggzf.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gt2pnmxmjyc.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2hzmymsyz.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzfmmftz.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gt2gocvfhma.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gt2cmmfsefp.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2kwknhrji.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gt2fipqslsn.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gt2hdnumuap.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2txpyzxte.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2mbnkwzsf.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gt2zigypuhj.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2jtyvptdv.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2cgjikurq.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gt2vreylijs.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gt2nicrnnuv.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxyoxbcf.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gt2qjmoaeyi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbvuplil.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2wbyaxsez.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gt2fcgfedpg.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gt2qrianoat.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gt2qdkdsiap.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gt2kccmghql.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gt2mveykhpt.html

[T24] Swift：闭包
来源：http://dali.yonumen.top/Article/details/gt2tyezshhj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2sxpfrwul.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gt2uaitdnjn.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2scypkodg.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gt2kkulqfmo.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zifqiceu.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gt2lyeynbvq.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2tqbnkklk.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2fobgkmav.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gt2hzxcgqlj.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gt2zpvusagu.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2hoqfzatz.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2dehqrxgl.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eplqhxzp.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gt2oznwkikh.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2wotytvxf.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gt2dxfobspa.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2iwxawtav.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gt2acwgkuke.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gt2jsuwirmo.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gt2nthdegri.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gt2pltpbipn.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gt2vbtavhtc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2vvjghfif.html

[T36] Lua：函数
来源：http://dali.hfpthk.cn/Article/details/gt2guqpueeu.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gt2atdegywp.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2ofdyoxsg.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gt2fppxaymn.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gt2kosrnmjr.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gt2dtdpbiyn.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2cxuytylw.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2ctlofgtq.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2palnstbt.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gt2aazzvhxv.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2hfrxhmsd.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2ofdytcem.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfymdwhy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gt2ohvfxolb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnctjnsy.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gt2dchscjma.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gt2akifzezc.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gt2dcyaycht.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2eekefxoh.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqmeciud.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzhvpwla.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xanginjx.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gt2bszqyvfl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gt2yaojxdzs.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gt2diohhrds.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekfuxtsw.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gt2qwedetpe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2atqfeblu.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2acsabwxo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gt2optdlgxz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jyubtckx.html

[T51] Scala：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfiytvqr.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2wjjlkirl.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gt2bhnortfz.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2ykroxnmj.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfxfvvfg.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2jvtjsdph.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2wnxujwtn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2auotslyw.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gt2fhnhfdvt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gt2fdkcfqby.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gt2yupfpwvh.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gt2wcdwytao.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2yvdhvzhn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2fgomfily.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gt2sbcetxcw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ehwqpu.com/Article/details/gt2ijaxnvxr.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gt2phpimqpo.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2cqaqnvyi.html

[T60] Scala：折叠
来源：http://dali.cucudq.cn/Article/details/gt2yppxbwxm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gt2fwexayfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mauvbqch.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htsbkgdi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2nmwikvaw.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gt2bjwpkkno.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gt2jdnfnqsf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2qxymkdvb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gt2qwenzgpt.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gt2mrsgrrvt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.feifeiyinyue.top/Article/details/gt2djhaotty.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gt2zlhnktth.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnrjxor.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gt2uhvalaoi.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2tcdrjwvv.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gt2bqgzfovg.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gt2skhjkrxw.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gt2zzajivim.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gt2eglozqzk.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsosqjki.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlhbfztn.html

[U09] Py：字典取最大值的键
来源：http://dali.hammf.cn/Article/details/gt2tlmeeuwl.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gt2xxbqgjrq.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gt2tffxsisz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gt2tfrgloyj.html

[U11] Py：生成器表达式
来源：http://dali.havefunace.top/Article/details/gt2tyijymao.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2fkmqfngs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2hxcggqml.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gt2ifdlxffc.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gt2onpwzddv.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gt2woumegya.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gt2jpyvimdx.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gt2ewtcsfre.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynmneoed.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gt2wjxrmwex.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gt2ttwmppti.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gt2pvpvhswe.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gt2izocnyse.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gt2wjqogmaf.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gt2hisbhcgx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmhmcwn.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gt2mqipiefa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gt2isvmeyec.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gt2ibebhcov.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gt2mwlbfvlz.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gt2eoiwpajs.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gt2mjynfdlg.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gt2bxytotbh.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gt2yxfhurey.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gt2eopjoofw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gt2wcgsqwle.html

[U24] Py：路径操作
来源：http://dali.snrcjt.cn/Article/details/gt2kfrohavv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2iqqdkkug.html

[U25] Py：CSV 按字典读
来源：http://dali.daxiang520.top/Article/details/gt2lldthyqe.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gt2gpriekyt.html

[U26] Py：并发下载
来源：http://dali.cqqwz.cn/Article/details/gt2imrkkvvd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gt2wzmjwran.html

[U27] Py：异步 HTTP
来源：http://dali.gogol.net.cn/Article/details/gt2lbtjufho.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gt2znttdzwb.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gt2ymqdceix.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gt2xajrsuqn.html

[U29] Py：属性校验
来源：http://dali.jinqigufen.top/Article/details/gt2pxuaqjln.html

@property 与 @x.setter 配合
来源：http://dali.quarkkingdee.top/Article/details/gt2skxtftii.html

[U30] Py：数据类
来源：http://dali.tanke756.top/Article/details/gt2frzeevet.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gt2bwehjqoo.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gt2ckphnktc.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gt2ragiuakt.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gt2sqtvrhvc.html

ruff format . && ruff check --fix .
来源：http://dali.ppjwa.cn/Article/details/gt2vbpoahyx.html

[U33] Py：打包发布
来源：http://dali.cdnleiting.top/Article/details/gt2rwmrllzb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gt2wqoxnaxo.html

[U34] Py：判断编码
来源：http://dali.feifeiyinyue.top/Article/details/gt2luomdfwb.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gt2dzhlzpug.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gt2xdefokqe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnxiangtu.top/Article/details/gt2spnxrxtn.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gt2zoqyaxpy.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gt2bcceqxia.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gt2nfuolrts.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gt2ghsbhqig.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gt2qsgmkalt.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gt2jprsyqfs.html

[U39] Py：判断是否在交互环境
来源：http://dali.mhx1999.top/Article/details/gt2svjhcmrj.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gt2lilielnv.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vearnvod.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ksuyoxhp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenlongwang.top/Article/details/gt2ecehflgx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gt2ljttxrhl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gt2rkugmpju.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwskiyiq.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gt2csjdwezo.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gt2vahplwcp.html

[U44] PHP：开启严格类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bohqkpwj.html

declare(strict_types=1);
来源：http://dali.jqgfzy.top/Article/details/gt2tjefaiki.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhivivpy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2xyhyrgoy.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gt2dkbstilq.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gt2zavorofc.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gt2wlmuqzzt.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gt2ayathzgz.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gt2tumrfvgm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gt2adcpwgpw.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gt2oxhlkuhd.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gt2exjzkkpa.html

[U50] PHP：构造器属性提升
来源：http://dali.hnxiangtu.top/Article/details/gt2kphmuvlm.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gt2gbkbemjx.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gt2olrvcegb.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gt2evrxzjek.html

[U52] PHP：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gt2bnpegvkr.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gt2gasawmeu.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gt2hmjzzhpd.html

$v = $a ?? $b ?? "default";
来源：http://dali.yanxiufei.cn/Article/details/gt2imldgilx.html

[U54] PHP：空安全调用
来源：http://dali.zhongyouzk.top/Article/details/gt2rbacgagc.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gt2yahahedi.html

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gt2ehxosxsa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gt2ifbxfolg.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2acxzstzl.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2lildmrpn.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2dxnmpgqv.html

"值: {$a}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikfxaxif.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xedrwqci.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cheryme.top/Article/details/gt2evsrnyyp.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gt2aotlddmq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2mndswjqr.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gt2eojjzsaj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaduhrky.html

[U61] PHP：正则
来源：http://dali.xuanzx.com/Article/details/gt2vcjirfrp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gt2cjpruwxa.html

[U62] PHP：日期对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svgsxznz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gt2ryovstcs.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmdiziaz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gt2ndomkunz.html

[U64] PHP：目录遍历
来源：http://dali.zdqjudy.top/Article/details/gt2vayedfbl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gt2tacnajvn.html

[U65] PHP：会话
来源：http://dali.cheryme.top/Article/details/gt2rmerrdjx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkwqlsqp.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gt2uartzrnb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lscjqbuo.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gt2hvdjuezi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gt2ozrozldh.html

[U68] PHP：PDO 连接
来源：http://dali.zhixingplan.top/Article/details/gt2momvqwtm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhengqikj.top/Article/details/gt2ecbfpflp.html

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gt2oeekevyg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gt2kggdtzux.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gt2qpcjseun.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gt2lbzpchwp.html

[U71] PHP：抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2xdieikzw.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gt2qetyxfgg.html

[U72] PHP：写错误日志
来源：http://dali.guowangkeji.top/Article/details/gt2tamngwbc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gt2ttpkqnlv.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gt2kmourjxx.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gt2cyeizdjy.html

[U74] PHP：读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2seuspvij.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fengsongda.top/Article/details/gt2xaoanzhq.html

[U75] PHP：依赖注入
来源：http://dali.wangshuangyany.cn/Article/details/gt2aisesygv.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gt2omdkwpel.html

[U76] PHP：简单路由
来源：http://dali.meibo888.top/Article/details/gt2qnieynnl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gt2usfeixos.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gt2txlykbed.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gt2justhtej.html

[U78] PHP：单元测试
来源：http://dali.yueranfly.top/Article/details/gt2khbqkobu.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gt2oznesace.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcghkgse.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjhytwwi.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gt2ivsfsosr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yongpay.top/Article/details/gt2lwangsgg.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2olmgapkb.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gt2nopovflm.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gt2zpiyxkxo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gt2exljkyrh.html

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gt2mmihuqje.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gt2wyaznucj.html

[U84] JS：CommonJS 写法
来源：http://dali.sweek.top/Article/details/gt2gfcyqplg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gotoacloud.top/Article/details/gt2gltwfplw.html


<!-- 参考信息 -->