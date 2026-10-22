代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjfstck.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnawolqm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qceglegg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvpbtix.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhdgqvq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2georhnkc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjjrrdf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2owyezncc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxmwbqb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzghfsst.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqzodrk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkufbjw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaqiieg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eghgqnce.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2szqauauj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvvemqy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvumtgt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhboccd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2umlitugs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apltxysx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdowdik.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwdtqpn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uijcteep.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkgwwym.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qornkdiu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpihmyfd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmvqyen.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukggsjyq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2golzjknp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgyldog.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tboenlnt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoenhqy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfcxtst.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlpjvaq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bywikhen.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awlrybat.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sreldkpn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkmrqik.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2roxtpgsq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2redzdxxz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnbgptd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sggifzce.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2istwxlll.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjypwgk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cwosrnbf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eruxdalp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sbewdfjj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nswofqdj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bxazalze.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwesngez.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zffsxurq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xifumscv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ovapfsqp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fptmcrje.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrmaqrr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2edmigxlj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ubochwis.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpqdgva.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ooopdmui.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgqtemg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjyvlhq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fbllvswf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zonhlmlw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpebsdq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmzolou.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bompaffv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptubbxqp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbczmkaj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zostibqp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyeyeew.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgrqghu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrxmkjf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zvilapiz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrhuptm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xelfrozk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvaxzrl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bikwmifk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hckzrxjn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqkhslf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svxkwtkk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvcwnwv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2thlhxevo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpcurka.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odvocsii.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apsrowaw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jacdrxlo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwbnirv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmkejoq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpkdpjw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beouhrst.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2blpyqubd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvpftmj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrvxdlt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyzqlzw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyubaivz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfchxbwj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wygwybhj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgwaudd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbhceqr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjvbfoi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbksovps.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhceyhdw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlrvyry.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2brjknjlu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrawamp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2udipsegx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzkgaki.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tkticbij.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyjxzoz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgixqjg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnxzwgt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2afkpakuh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qlavqohz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkimopj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatwnfht.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bxapqsob.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2afirlfgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgnsjrj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgifeqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hviijaaf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiohyna.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2syseaodh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bgostysh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeltxaf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2syupxotv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qawubwbz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrgwhca.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2szogozaa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcpwszi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvscjhu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcorwbj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lydmslny.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2spkluzfy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2trxtteqf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxscqwex.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtanadq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2johexvmq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zysupswn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmiejon.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2scoigkag.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwvbled.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbinaoy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrwyuzk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvlasrn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbugxph.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwxiuxl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxhmdok.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxxlpbc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cfswgbcm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqljet.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pknksuuv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpxnkiy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqjmufm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yttulgub.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2beathheg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcxjmas.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jpghywye.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icjhomah.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xnucuzgn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2svkoqdkc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ityhqqgr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zouxfpss.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrzcgut.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xymjsdvi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdrhbdh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sfscnaek.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2phbkxxeg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkjzkqr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gleeztag.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxhoodx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yaawuqum.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhlzejo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2revincoo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2twgzjhif.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvuvzfu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kikzsqaf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzbumnk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnqjsom.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrwbbaq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvmjcw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nmccjais.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2crffxdao.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnunojq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfkzsaq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkcrxqu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bovuwkky.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfrotbs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjjnmcu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2laoclzhd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2acrejziy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxazvmi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzplysqm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkfzhbt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2elbzrhrt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhcmjdr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2okhyxbpv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2twhksgcf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2opzbbpru.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiekkfd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmbeofg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgapmvi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gehuzttt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnetbkr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhsqqhq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfgkvko.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjgzoqe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkmbipn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2epoewzds.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rddypzqa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smppgumx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuedkav.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jzktuxnv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jzezvpbs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jkljrcxq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibysgeeb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwepotbi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2inokwskp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpjlrhu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cdafutfw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hophfcgw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvwhece.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lileatzf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmltjjh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhdqavd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgsxvle.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2draznxlr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dztlidih.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2aradasvi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hctlkrrz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2frmgehtb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkzlrbb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gziybryv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pquwjagv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmdgpkl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjrvypt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejaomnt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sesooxmh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2goarsvoh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2stzpqnwh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aurssnga.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tccypawi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jipovrar.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpgyrne.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2osqhnteu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzcavxc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqctptz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdygadl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqjpapc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yfevhrka.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fimlgxqs.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pncilmfo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2woqbnzsq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2umhedzwz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kocgsgzb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyhrtfj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsvajfk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkidvdt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyfqeoy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjbbjlb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zesmjmac.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tjttzwhd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltilwwpf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wuktocmq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwwkvog.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkzzcum.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2svlhajya.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyppure.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2krmgmvfd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrnvlbs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtblsjx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdarcdg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxceuce.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rffqhtjq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xdubwrkx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pgldvsan.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgdiujg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzbdlbu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkzjfmy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgypspj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxmdodo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lplmgnri.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2istybjfa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvqzgku.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapzqonn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wtigbypl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkifuuar.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jaepgyof.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtdrzwh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjxstif.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcdbfvv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nttodifl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkvuybv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvmvsbf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwbzbxn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dryxwssq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdyawhz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwqfgoc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mivrgpvl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2abpijteh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2abljfipu.html


<!-- 参考信息 -->