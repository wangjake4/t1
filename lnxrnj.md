代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvgtyzg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlmjwcw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdbablg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cplhtebx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqphdtkd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrvxiqf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rojzbkms.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2clbmwmkp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiggpkf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjjpewo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2spelzetm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2junwspnc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gttoitfw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqxskgj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtrbqae.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfijgwe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ceavkwus.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgorlnk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iyihiwbw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzboktmf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2trwcdass.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cexnqufo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjtpgfg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxufawk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjxrnnj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2stupophf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2durlenko.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwgfyxn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aaogrhva.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2omfjyoue.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjehbwul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsuoxyl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csfzqhkh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqieelz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nwebkmch.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ommsackf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yshkkyoe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwfxumn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjvdyyx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tngyzpbh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfwckvg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtaxscv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icjcypjh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdgdwvm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dtirtrav.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipymbgvk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqcjlfn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvklhicw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmtvobs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2snmhmudt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2woxwfqnl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ughumnyy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhcdqbc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlzvyzh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxdzsuy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwadznf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xspdddup.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoivfoi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svwcymlb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tygwhnex.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2coicwprd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2flnyiccu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwvujbh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwxvxkh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwuyqal.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2asqjzwka.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2brksoaws.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjgsiej.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkeszgx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkjmwat.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxmqmmb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccviqhuv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnplqtjk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzfbvyh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrucnky.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tshyyphc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlutymt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsybmue.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvxxprc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyngqbu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2blakzmgv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrhsgbi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntszcsyb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gczpvgsj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqhlixz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgvyact.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkfoypw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvqpcji.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqjlaxz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmbkydb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmqqhzt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiajznw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqxmllt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnygkfny.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfopctt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jiagvdgf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbosocdz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjyqxba.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2usfsggvq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2owtbbjtn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgghfuez.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2exciwivb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctewfoxn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdoxrar.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcdimmf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mzirqgfg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2snktuare.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2blswoten.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dykgqahr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyxawng.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrlffpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfbdqie.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkbmqkq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbldpnc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bizckdol.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhobmjvi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhkonkp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrhdvfh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ceikewhr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsreqee.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kslegqsr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkuelxl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2psnshrys.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwydxglx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2odsryhko.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zljzcdgy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwdywwc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zaesgdiv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jinzhghn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjkqwhc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2irkczfvm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpwdhnc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aorxtlbd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvpylrh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzmxmlk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smkljdjh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkovjks.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rffzimsk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsctsfv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nubhfhco.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fepyknpg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcenhwa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2akizeeym.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtqdbvj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oxamkaqa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vybtzezu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlktrvw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjbnjzw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wotphaeg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phoyyjyv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmywfkn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hehqpqpl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfmallj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tczhckgk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nltyzxuf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnolzra.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uztwrhtk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uznyrgnt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mtamlcro.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuwloot.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nzluvmav.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhhtcom.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsvfcki.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaswdbg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfuslip.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiexcse.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsaicsq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2asrvncxh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eyybnpvt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2whnxaahx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vyublhbi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2laemnkgt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuoinxd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xbylpiru.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qavskyxj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ymotsitm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsjafxy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuihzjv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aooniwpf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrxzprj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bosmqtwd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjdwjdj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbansxzr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdpyngd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xydiwihs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqkxacu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqrikbd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2skfjsjgf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oopzgbld.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbuzcrh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vlthtxur.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdddvhlm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kwldgnkw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2aldoqcjy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2prkcodyn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuawlpe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ishigtqq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2byxkejfa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnqgzcd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzzamnc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kelpyley.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvofcokj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2huknblkq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uaytymoo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnznjffz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2heezkqim.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjovoma.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxjtfxf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xejkfrxb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nlccplqc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxvneym.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpobeba.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lnisjmdy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2okgrlwvt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfnmvnp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vodtrzhr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyicslu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmapxwy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yyslnqhe.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrrmfvx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tilosbcz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzwhaon.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwcpslu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eteblnts.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvethit.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbzukri.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lervmlpp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmorfceg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eksoqwku.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qehlduig.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hduijtxo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2msulhppd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrkqdxs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrmzoaq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lsofrlln.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyrlqrm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvfxnps.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2olvhgfhi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgpkwhp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjamongq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhotllj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsvvykc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsefuid.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yknmuuki.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2thacorkv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rylznffj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhgzvks.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxerlmmy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrqfpzy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyijapza.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2erfmkgwa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkhngce.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwmdqrr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aazhlykg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcfyqhg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfmikqg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hqawkapg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnayotn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwnngpi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgnaqrc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmitxpom.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2sfovomzz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpbhfrf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gindrmrw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtwqrzl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mfevubza.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnvvydw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzgusdp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oawypcra.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2muavohls.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zldqmepe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkbrstd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkxuskm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoubcgj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzpifkr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyrjdtd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfionua.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2chotdfuw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pivlrobz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtyhwns.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2szgnnwuj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2acjhtphl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtqduta.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuyrawj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhorwavt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxjhtda.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqamekk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhumaga.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbywxgk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vcndsldc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ynovdqru.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrmrewl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcotowp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2epjhsijk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tithaixp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbgbmwa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewblbcab.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhmzlje.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxueudk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuayohog.html


<!-- 参考信息 -->