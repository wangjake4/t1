代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtacvnmhye.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtlfrvesrl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtacbucoqg.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtudcnlnyc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtqqvbpkmr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwtctbskk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtrycoczpk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttnnglitm.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtenztodnc.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtrljjcaxq.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gtccuaunio.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtcvzzbmag.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtdgmboezk.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtmqyesrin.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gtsltcpvjo.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtjyzyfxux.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtqsnelwrv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtdiucnabu.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtepqjwqvq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gttzvzzaun.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gttakcvjrb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtbhlzirsa.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gtmqcbliao.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaldvzxk.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtntjsbfmv.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtqtsmmecp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtobgilcxr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtpdqfhgwn.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtmsuxvqmv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiychtpzx.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtoifhopds.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtpqgjquwb.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtatqxessq.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtvbbmprmd.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtuboresdy.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtunhmoaaw.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnrsxbqn.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtcfmpvolw.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljedbzro.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunblqbcw.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtxourcsqa.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gthwobnlqn.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtveaournt.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gturdzxlbf.html

[T19] Swift：可选绑定
来源：http://dali.shzxlz.cn/Article/details/gtcgiygrzh.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtzqskpipe.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtihuvsdll.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtntsgngyb.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtzyzvukkk.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtdvflplrw.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtdtnayxhh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtedokzqdl.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtctttinar.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtanzzitwc.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gtuxtvjzis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtjdboyzlx.html

[T25] Swift：结构体
来源：http://dali.wangdashe.top/Article/details/gtawuzahbo.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtavzpjxgj.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtedmbbdgo.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtuwcaaecv.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtqgdkyzav.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtktzndsct.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gtqtvxwtxv.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gthjcgviaj.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtqkxmlbma.html

guard let x = opt else { return }
来源：http://dali.jiagoushi.top/Article/details/gtmtqxlttz.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gticalgmqq.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gtqhpvvlgz.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtmbwzfrov.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtbypctgas.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gthnbzdyvy.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpotwklys.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtwkrzagmb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtsateslho.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gttnqklojw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtecsfmvjn.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtemftvgpk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtkfbgflca.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtmhjjpqoc.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtzhkmwpgh.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtxqdbudxf.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtldkiwgsh.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gtclnohptn.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gtfbgvqotl.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvasaoqyo.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtjpgeepsd.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gtnqkruhns.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtzhfiqzlv.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaaotcfcx.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtcptksjvg.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gtntnvtapc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gtxovmlequ.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtlhdguiob.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtaylcxfff.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtgbzntemm.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtxmczlfxe.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtmqnwjckn.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtkmewgptk.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtgczwzoou.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtgfposugw.html

[T47] Perl：正则捕获
来源：http://dali.sysykeji.top/Article/details/gtaghplqqh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtwgajbmgm.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gtcmpsuywr.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtmhahxpyz.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gtlwwdlwdz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtzjqigeus.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gticucasmi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gtpgyugwdd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfdtvthe.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtubutqxro.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtdxcmcjzh.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtdrntqvei.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtkqpnkxfm.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtslvrnzjt.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtvmwmyxsp.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtzlahflcb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtsxnxwdct.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtxjzcmbzx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gtmvjhseaz.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtzfkzdkzk.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmmxtxyq.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtoklhauzj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjdtskfa.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gtfyrwoomu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shuidangran.top/Article/details/gtrmduysbx.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtakwxhzzb.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtisxikzks.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtloxznngj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gtszbnevvv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtknbgbjtc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtktyknetp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthcokuqoj.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gtdnfrcljv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gttizrrfax.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xziqi.cn/Article/details/gtwpfucekv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtpowmjnmp.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtqpaplnda.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gtkhsburna.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtfbnpuuiv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gtspoyfhfq.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gtpfvcvaui.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyizblmsf.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gtxzvmgoif.html

{**a, **b}
来源：http://dali.316326.xyz/Article/details/gtotbutezj.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwquuiwy.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtojysmzdk.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtnqujivbc.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gttuchggai.html

[U09] Py：字典取最大值的键
来源：http://dali.redwolf501.top/Article/details/gtekotbznt.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gtvpvoyfuz.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gtvtlkizqf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hywenlv.cn/Article/details/gtcwihfqtf.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gtielrbvlv.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtcimjhvcc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gtjfxgnqnk.html

Counter(arr).most_common(3)
来源：http://dali.zhengqikj.top/Article/details/gtoihrbakd.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtymobqxzw.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjrowism.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gtwyxyopvm.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtepjwcmhw.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtdubbyhav.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtupkeyonn.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gtinhorexk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtjxgktbye.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtusizfpnq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gtwjbubmmt.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gtnbiwftol.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gtcvcctdkf.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtowujmdwr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gthybashlj.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gtkmtbsymz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guowangkeji.top/Article/details/gtbybrwpyd.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gteqfydist.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gtasstfdyj.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gtsvturwfa.html

list(zip(*m))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtticgqarz.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtdcrkohnw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gthostfbkv.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtwtkhoign.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtjtyuosgg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmfsljfh.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtrwosdqjt.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gtrgwrdifp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gaohongyu789.top/Article/details/gtzqrbaldj.html

[U27] Py：异步 HTTP
来源：http://dali.sufxvd.cn/Article/details/gtajqzvgob.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gtpcpuhwnw.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtlxnoukwn.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtygxddpkd.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gtepdyrxre.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gteeffrswi.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtznagwgod.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gtivdzrldr.html

[U31] Py：单测
来源：http://dali.zhoulong.xyz/Article/details/gtcsjsqqqs.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gthjsjnmki.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gtklrtkrxf.html

ruff format . && ruff check --fix .
来源：http://dali.hnxiangtu.top/Article/details/gttdjcwkgm.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gtupyevplk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gtexngwhkm.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gthqhkzhhe.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gtqiawztnp.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtadzfddrv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xylfe.cn/Article/details/gthtebtplk.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gtwrxghpzt.html

schedule.every(10).minutes.do(job)
来源：http://dali.dashuyun.cn/Article/details/gtrpkljdpm.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gthurbapkf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hfpthk.cn/Article/details/gttpdzhwzw.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtatopsgql.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtugevkbdz.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gteihjglhq.html

sys.stdout.isatty()
来源：http://dali.xinyue.icu/Article/details/gtmppetnug.html

[U40] Py：打印到标准错误
来源：http://dali.guowangkeji.top/Article/details/gtfntwfpaj.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqfokwoqi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtjyeewniq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuanzhike.top/Article/details/gtbuoziglk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjpfztxi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gtpypxokzj.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvjlkusr.html

namespace App\Http;
来源：http://dali.ivvv.top/Article/details/gtxpxhhfxo.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gtysichkqg.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gticbkgfvo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gtdjemnjai.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtsqqasssp.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gtojnpsfuq.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gtczmkdsjz.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffsvmoci.html

int|string $id
来源：http://dali.nanxinkj.top/Article/details/gtapnouxmy.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtxmbhjkth.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gtlkknllwm.html

[U49] PHP：只读属性
来源：http://dali.daria6918.cn/Article/details/gteexmkrqf.html

public readonly string $name
来源：http://dali.yangfankeji.com/Article/details/gtrgecnkea.html

[U50] PHP：构造器属性提升
来源：http://dali.0kj1m.cn/Article/details/gtzontixsl.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtekyfgunx.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gtbgnjinym.html

[$a, $b] = $arr;
来源：http://dali.yonumen.top/Article/details/gttbtnvpjg.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gtcgfsydgq.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtkhllzsla.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtnkfuufaj.html

$v = $a ?? $b ?? "default";
来源：http://dali.hfpthk.cn/Article/details/gtsgkptuwj.html

[U54] PHP：空安全调用
来源：http://dali.cucudq.cn/Article/details/gtmqldabde.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gtxxacmibs.html

[U55] PHP：match 表达式
来源：http://dali.zhixingplan.top/Article/details/gttvnpbhaq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xziqi.cn/Article/details/gtljwxgedm.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gtvgnnqneg.html

f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtrelgdetn.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gtrjqhmzae.html

"值: {$a}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtozeoaqmj.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gtvsiyfjem.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtaytmnrkb.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gtulqwlljv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtezemmuik.html

[U60] PHP：JSON 编解码
来源：http://dali.havefunace.top/Article/details/gtvgxndvtx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gtkxwzaaja.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxogjrdeo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtlqvxfwhm.html

[U62] PHP：日期对象
来源：http://dali.jinqigufen.top/Article/details/gttxprpzlo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gtwwatixos.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtkilyvnst.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dashuyun.cn/Article/details/gtwsvziqvc.html

[U64] PHP：目录遍历
来源：http://dali.sufxvd.cn/Article/details/gteehhmsov.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shzxlz.cn/Article/details/gterpnouee.html

[U65] PHP：会话
来源：http://dali.yongpay.top/Article/details/gtjmmsigqo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sweek.top/Article/details/gtpieijttv.html

[U66] PHP：设置 Cookie
来源：http://dali.gogol.net.cn/Article/details/gtgrnvyscr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gtdvmpvbud.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gtoyruefxa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gtmvknpach.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtpwqgfetg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gteuqnwxft.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gtodapjyjl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtjgtfqzfn.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcjikvma.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtcnlihwil.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gteayzcpmz.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxpkijeu.html

[U72] PHP：写错误日志
来源：http://dali.nanxinkj.top/Article/details/gtbfsogebs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gtcbvraycg.html

[U73] PHP：读取 ini 配置
来源：http://dali.jlsjyb.cn/Article/details/gtrtrbzzkw.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gtznyedrlh.html

[U74] PHP：读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtddxjtwoh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.birdmap.top/Article/details/gtqxfxqmsw.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gtgjcedzxm.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gtkwbxwyrs.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gtvzqmypte.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jiagoushi.top/Article/details/gtepwkenlb.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gtkjrjcuoe.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gtoydopqds.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtwldmoebq.html

composer require --dev phpunit/phpunit
来源：http://dali.snrcjt.cn/Article/details/gttuvotdoh.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gtszcmgrjt.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigfzy.top/Article/details/gtqppczseo.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gttguksauz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gtviqumdfk.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gtlobgamei.html

npm init -y;  npm i express
来源：http://dali.pycfn.com/Article/details/gthjsgstbg.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gtxlmnqthd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.mhx1999.top/Article/details/gtjkbhumne.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gtnrdxwekj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtpkjyorbm.html

[U84] JS：CommonJS 写法
来源：http://dali.sweek.top/Article/details/gtkppyypze.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtxoldjfas.html


<!-- 参考信息 -->