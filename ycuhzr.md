代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fynckvwi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2schsasry.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrrlecx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciswcwbb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcfqebs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaypwsby.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrlhhbw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrfbalt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpumcym.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzomjre.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2annccall.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbmgkkz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuupnqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bugkfkan.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2adyyaoqn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbtpcir.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnerkwy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntllstqf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqdzhoe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuycgyj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2acwsibnv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzduzwvr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iefasjcj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnhtddl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkrvcpw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smyorolx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjwnnwq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2npwoeqxb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dovfihsc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqfpjgn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2swatgleo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2psvhjjhz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2urfbnwkf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qujrruny.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsigtca.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzthhdzn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqxavzs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zexouprc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtyiyrs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klacgyhy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dceqfqsw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2akmmbcgc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mribwpin.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgrywix.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2raamkbud.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2krpoiqht.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdbehjo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfvrqdx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oktkqdvn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2filkdfzu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aphysuos.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwttqvy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2praqrrui.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbtzwia.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krgyjxpu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcxvsuw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fidyiucv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2krbpsnxt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xogcwzjc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaozwqt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hebiotvv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xooxmlda.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sebhxkiy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpsxlmc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iubncecg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwujerlo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2asazrzpl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2drxdkbxs.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iphrejeo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2heucxqfn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsojyep.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2meqwvxrr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgichepp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbiwyjz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wycbuobo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2necawqeg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2abcfwfbe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjorfvj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbikxab.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsicrbvw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ercjatxk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwsmqxf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2alfigtoa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcuoehh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2whbpjoup.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgejldnt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zssbzqhb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2octtajsx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlpfsds.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbspflu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kddziddv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxihiuh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmaapif.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ermtjegu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2apknorqr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxnoxhg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaafgjo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvzksan.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2blhnenps.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjawyvx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdomrjic.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lfogeulk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fusbkkgu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2neqsayid.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvdxeof.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpubvoz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bshhczmt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbewjvr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuqriqr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2muhsvrro.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahlmjjg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2josyrpsz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqapjmln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhnvnvz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szywshgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uauevvhh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ielnrzac.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2icsuxdzf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjhfyhx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhaxigi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2utlwxfnq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaicxlv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvafezf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xignuuok.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2osfazhmr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjbxphc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcuklie.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhwhmgl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxqjlfw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyofzps.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tebjtlzr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2thyzligb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzlsnjb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ougnmpfz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnqhjce.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wulytdvk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqwpwid.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdparzq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2phpzsezu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdjunwc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkxcqnd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2waeontsb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lglpuxlu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpriubdo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2newxbwxt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2voldzsay.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uausosic.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxastbco.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gbawmugu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwydbdcq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfjkndi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpknzar.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aucsbxxy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gypzvnmf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uulygpsf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhevagzq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2khbwojzw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nagpsxbi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnmfpji.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2plolewdv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2caukvrbe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2twylmlve.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efpuewpk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrxphoq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yffhbrrp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiotcve.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2obnotytb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2arbjslcq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vciznajc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxjxwtp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2msvvqvhk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sphcvjli.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2upeluzlk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kvncksxn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkvvavj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnbemcu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiwvaqx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsbgzmj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmrgtll.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bewmofnz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwheubm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhzranf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqgjbty.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcufzqxk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yovhaylj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlkhmis.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnweihmm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlxxith.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlcwjvm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnfggrh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2emlmzaqd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkmrqmf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ousrsbtk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2igfvgvzq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ooipeflo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bapcgmbs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnkjdul.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcnkfor.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sauytulk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2meduzenr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2poqezkmv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxfmzui.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqbpyur.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2okrkxodu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsbyqqf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkvepqg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upxbznhm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2shzryxic.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfdmlcm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeetnhe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjonsmn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pglegbdi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoapopx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fweowiog.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vagzryjc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ennsrsye.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuyxtmh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsfsvkg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zazskifk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cneuvctg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qqljirms.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpfssgl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjflievd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvjlswg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mgufnhze.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kauxvhbb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nodqkltr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumekujh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eeovjxsc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kekomeme.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkdmlic.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdugvsc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmctefw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2awokbukf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmksvvbv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2avmkpisg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iflxddnt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2errywbyg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wgurowlq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgofoda.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eeygwvzi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhohyfj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xzugvyvm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2awtqcowm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxxzfjp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwkpmkl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxmknob.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmflzxx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cazmbjjo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdlunlu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiitmer.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2leejzmvh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkcbsdj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwphhzdx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2secigjlm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2unftmfvr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pqscacel.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qazogxbu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bjocnnba.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nwghjxax.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2subgpqhf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfmnmpe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuojuutq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2okhihjss.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sxywftfk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlnbnac.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bryjbmnu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2snskimng.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdebyfv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgmpon.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2daruphcr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzhczxd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqrlasa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2twbdylhu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqmrbjj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2udgodrev.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xilpobbj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vbemlhrc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyihxcd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mytldteq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ffogozbc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vokpbzug.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iheubdvr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmohqvla.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcbcfmn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzneyyv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zxahliwl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2atrxjvlv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtqavor.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhycemyw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eqocztpz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2erpivslq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiuqjxr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rndlvpxb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgxrncx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjoccoq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmedmyt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kszzcnwl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2isqpmzwe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvquned.html


<!-- 参考信息 -->