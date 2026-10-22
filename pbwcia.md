代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2odtgyrec.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lobpizzl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jkksxtsf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjovktwy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzurtxgk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgrlwri.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgkpeck.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2asurkikj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hewvmcgw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uahloofe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwbstiq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwehtgy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gtytehzi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwfhnld.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2etpseiww.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2omavcmdr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2owxadhor.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xleggcjk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdaydqg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ionuzmxs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aaexdltk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2auxwyuzo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hofblcqw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2allvrdgf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2trimxcaq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmkopcl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoabuzi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlahzwzp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcogowy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdrdoxn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eztaopkk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lijovtgj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqrdemt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqegcjnd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrefman.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npwuygqh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrdyenf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2axidyini.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2actloezt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfquudqf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnyberk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjfuzry.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2udgqwier.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecehfsms.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqqllqx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdwxhsp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sphbgxaj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oilsgama.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phxchvrn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tghuuzrw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoappbk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwrygwx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtwhynz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzlzvfv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cobkckrp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hplmdeje.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzkcnwt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dkapycfe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrajait.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzjilis.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kejstlbx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2slzncpqn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zerlcjwg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uihhzrjy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhzitvd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzshcteu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpghyixz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lefwsgwh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpeskpg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgnbpwb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjkbzjj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmajdgwf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2npimxplv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qebyyeni.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsoxklf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csrljljf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjivghi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbcvvel.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyqjcsv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdphnem.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uimgoasr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dptumczn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uyswwnwl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrtbhuu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asngqaxo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yruedmzb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yayuxwbj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2admvuncx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmubyij.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2opkxcslx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaolgxp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhcmzf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jlelmewn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2morifzqz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtcgfvk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkshfzn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtwjjtx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qslfhzcr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdpjhxm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzbdpqp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzkfdvg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tummzqct.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mslpurhn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2plyktgyg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmximfus.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2boanhfvm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2umidoglv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwdjegq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufreemmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yftnhztn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzgsfqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shwoqyll.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqpbdqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2clofusio.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeipfhn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsbkrlm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnkdttz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2geciddlf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wyonmjdo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cumqiusr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyobhcm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuxsoyj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2akiytmmn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbluyyf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbjhtty.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhssrmph.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcezezgb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvrzhsd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwmkiwu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2veidngee.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jlliajsx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlelbbbz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvsvpik.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfyjiqc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sqemzhit.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vybpqrou.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpowevjp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfynlbq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnezuad.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2emeljxbr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2totpdwte.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tscnlcjn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2htnabmpz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwksdsaw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jzehbubc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxnmayg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uekvxigj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2picdpxpd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pkknfnsj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwrlcxz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyakvug.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoeejaq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfaizio.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zyezsyui.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzwxnjb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrjnuei.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzcssyk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bcymfmaq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyxoprf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2focgrjpu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfxuwov.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmfwvto.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtgdyvk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fswwycyv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhkppcl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2brjpglfi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2itxltucs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eknrarwm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvpgdhv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2usrwepop.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgzrbkw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2igfmyqhf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ratmjixx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmgmlzt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2krxdguni.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcpycnd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmzqedf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxuvnto.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2deqfehwp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjliuide.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2abpnnutj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqocrmz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qowiaxef.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sarrxnyu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2phijafrz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfuvied.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrmrgre.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnheywa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kybwlznz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmtblrf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aohisbau.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbblglu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfbhoos.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqictkw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzkbodm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aihiiixs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrtsyns.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aacezebz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyvivwb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbobarn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2baykppsm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drgwakgn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyljpozk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kunmwjln.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwpyoza.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrzszwz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xurksuzs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdicgslt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsnnedk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pshbhxke.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kjifmmpz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvvdoyk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2urneiaie.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yruvdimj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsusujq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmdklgy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcxwneh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jecnuhzr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhxvnef.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2omkkpaqk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2woqbcwzw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntldscli.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2birxpgww.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgcygmf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oeksesco.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyrayuj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uzktqsly.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhhmwhb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmkpevs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyppltvu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjqmfgi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqjpdwa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vdikrvvo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zihpztre.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqrugzr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpffvpvt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwvdkdp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyufmjns.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2giwpejre.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vihphlfp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2heqswkej.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uavzrngc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gswnnxud.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2myukqtxw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hujpygbj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpeaupy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2apnodgxl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2eotipfff.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xquxhmxh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvsstll.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjildzs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyeqrgl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkujssg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2skswkhax.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2agvlfzki.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jytpylbg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkngyhd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzgwnmw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2msstahkz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvpqoah.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mibeesst.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpbseoj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2abfhvnxf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrheublo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmcisjh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pxexvvnw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uehxsltv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbxezxn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnwwskc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiquptn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyzjwdc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eupbxlwd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzeayye.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxvrqix.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xigftagh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaocfuu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfyteea.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2odpznjsb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bnigrfan.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2keqpbleu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jmybfqdg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmuwsju.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfyigzy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxevcsu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwznzhp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjsiolx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhfknjx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuamiusz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mxawsrmh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhhtoxg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2audqngdm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyopmnbk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdadaem.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiyqfsj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jgthvyap.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rswvnbhp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oesedikx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzvbksz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skbppuiu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvrjhes.html


<!-- 参考信息 -->