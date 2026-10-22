代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnnjhzg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2naqklnsf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2udvntbgr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgvyaji.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tbehxoqy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhembgk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nccnnjfp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmhxlsb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isgefhbl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2auatlwkf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqrdwva.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkgmfvf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcmwcwu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdtjwgj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wqanblwy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqqmeii.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsvbhml.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gohhkaoo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqxjvuj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrlilex.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxfgffy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ennwyrzh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okewqsqo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdcgfg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlfjtwz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsdvzwp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrslwlhf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkuiqio.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2flmqwjvd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yshabwtq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wllbkmjy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxetndcf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dimiyxek.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkyvugk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2olxiqahh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2noxhlgxo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrktnlc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsegxaej.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaxdugh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aalibaqy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfksdzl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fixgxbns.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgtdkor.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrkpsmd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cljxxkxn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hheyuuaz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxoyvzl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfglohq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sglxngfb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgdytwo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbqwgwc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2csotteew.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiorwws.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhwnbrv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdmkjsr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mplwcboq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdymyvax.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyqdkex.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzoksgc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyynzck.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmnjahp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaxcyce.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfijbwk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tocilkna.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lijkvyox.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2awjqaqjk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgktshw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxdgdhg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ljusgunr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzafonm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2usgjimko.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhaxyuq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvqyit.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrzjbzn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zimonlti.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwskqhr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsyqudb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rezyfhej.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrqrwgu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udfucbls.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtuwdph.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrgzptf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dukvkobt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prqpeeuy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iltqnqbd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsutzsxb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgukfuri.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwytzsbu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaigjcb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtlyrzw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhwswcb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjcqorv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyedrgrj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srqnveeo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qddvxaac.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iobsfqlv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxfmbey.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vifgqbvw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgfpjdb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tkibizui.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khmfjajc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2epqwmmiq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2poaqnxna.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvpwcww.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjolwkdw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sklzipzt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2znnujfcw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjmhdks.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvounxcv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcbydje.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowigiqu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vwflpnpq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaeprqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flcndmdf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smwdajak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewydblri.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwwrllw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zhspptvp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjcgcdq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iirgxgdk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ufllvjoo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2egthhgvu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkmyuem.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuycoiu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxhizjf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgfycwv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcvaual.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqedlqxl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dosagafp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzwfmfn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlubcxm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmmimvy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mznrxvlh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkajmjlq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnshdfjq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuywdqho.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydejegpf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnxuwim.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dupjcfnq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2omrraigq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuzslzz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgckaptl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsvcqmg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxrrvji.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vniloqiw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mysstqth.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nizgkyue.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sueoxzkd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ammedyji.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2elryrtlx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvuygsv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqitplp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdqncse.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfkyyqd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cflytmcp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpvcbtd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwnkzej.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwhifou.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ryajzdre.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogohqtob.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuflcxyl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrvtluq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxeulhw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmlzcyi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpiyifc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2urchbgpt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwakhgg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2casbdver.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oftoeinz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cwacsvne.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyvwabo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cojmlurt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlzddqd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjcqmgc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eeciysfm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwhptln.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kveghzkb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2csibitjj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2disuolcv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vzownjrt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nknzbcvl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfipupn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wltkubnl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxnnkyz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjdpfgi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkahvtxv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhuntah.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2azpdqxzp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtrhivz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkasgyc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjwnvcd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdvzqyd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2opwspjpl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2urskqmhv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ukilvcgf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dylebdus.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2anorosej.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwllkpd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2envbadya.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2seszgotb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qozwnxtl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gazdnlmj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icndytsb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqktezds.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsdhjge.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gohkhwkl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2edkjpavo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbeadmb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2abvtqviz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcyfyzk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2whneyust.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcafoect.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpdqzup.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qflamqaf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eiehxpjq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juvbyirl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkncqtk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2npdlrrtb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrikgac.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzlxcbb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pviirrar.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2irqcufpd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qykytnja.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2udbjwtyg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbmkinp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsakwscx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vaywvygh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2foirjowr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjkpllx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muqztwhj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiqhfxl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zriwgysb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2osnvwcui.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kazegywu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nbthrmdq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mstqglyl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzzhheg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmhomuq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pvobloid.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuupnmdo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxjifnr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2myeieiig.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmwwjer.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxbckrv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2agsbumny.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfazune.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eeddsfjc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqxvspc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiaefrh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hebylrpv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlyznlc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiinour.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkkkxab.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiiwacq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhpikzn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbesbflq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pocujueb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfqrqam.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvajqxo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoxmohp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zoftsysf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgzkgek.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkidher.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuzkqrw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2igwvnmgp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ozioozcm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzuoyno.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uudtnaxr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uakjwmeo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwouthh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rketmhei.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2abkdsnxr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaflzan.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mflzotuw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvshuxi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2acbxtxno.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uieadhrn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uealepdw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2blywxouv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgtwgwn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeqrash.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvyttfr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iatzljzl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxvcdzh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gxomhaim.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2smihjnet.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxutqwe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2svhgipqw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmupsvm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeiesxn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2brfcmrhy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzzfoij.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vdendrug.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zacujgsx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmfggfx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxogfhli.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2elyedddl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fgarhfpu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bqobince.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxkvmrz.html


<!-- 参考信息 -->