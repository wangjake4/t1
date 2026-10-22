代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bfopepfc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cojsafjs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2opebilzy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjvkoti.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ytydrpbs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2chqgvrfq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2krserntx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrhszxq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idjbqggt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2shglnphr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2myhovwhu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jenhrzpr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2luqunsvb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsejlauo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbdpurt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnszxbu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lcluowpn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfulecx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlsohsv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2svmegfdq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkesqpw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnulzsr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyinqolw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtsujnc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mertkuzc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtjqnhp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyucgelk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmirthfg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nemmphym.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozunczga.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeeixek.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdmhpbw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsasxnh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqukzwjn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfoloyn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjnwhkl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2teanqqlf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxvqiqt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgbzgsd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hezckxqa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcdndko.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsfgwdr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwgqtry.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcsfqsq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjjqgug.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjsjdiy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2naqnyunx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmgivop.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrzsxrf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yphzfijk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqysxnp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2psdakfnj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2juxerbip.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxkfbcx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhvwehw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2frtqiqhv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvbrzbw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcevcnf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2keqdhfrn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cssohmei.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfuwvmq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iimnymoh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrmjxhg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kegnblax.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdwrgpk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2igqlehbc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdrcjrz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2exvlyejx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2immabvlu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qclxwtty.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mabmxyyw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjtuljc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxbhxzh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhzuevs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nontpugt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkbhjeq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pagoohts.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdmhdjl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcqnlym.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kazreygf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqtvejy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyltnpof.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaxtfql.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mduwefqp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fveqfxff.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xduxrlmq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdylheqq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbisptc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpdnkvq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teriztlo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evdemvov.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdperzoq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzljvlj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvfigxg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzqopji.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njdcikzr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfwpbhf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymibqzwz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoggkbus.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ueztmwff.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lixkhoux.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2emkizwxz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxetdif.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfrewye.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxjhzie.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ecakpmrf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjsvnhx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzjeuup.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvmdqxn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qdchcubk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvmwycq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uufkqdvm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcpcwvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsexmjt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjwlkfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoayzkph.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yizkouwr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kccpqdip.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pamubtdu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrvkioe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqpvnvq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2btfhqcha.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2googtala.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeyvoti.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cuopasqy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fccyqtya.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvjxitd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkxjijt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rproufoy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2trwlsbos.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqqhfjd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2afaqyqiz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdtwsas.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaykbpnt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eycstord.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwqebye.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqbnyvv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhubmiqx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lsitzdwz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2garipoqq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjmtkgf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdacjtr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcnvpjn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvkessk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xohalost.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pochceds.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwdpdbp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzymvmmb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjirwkb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkkldpm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbwihuu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvwjdre.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2drhlepxn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2myhaetdk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zraznjvb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkxnzbk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpxvetb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2epyzsowg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwwkgup.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2empukaay.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orsijtfv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fanwylul.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oaduooou.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczyzfyl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgldowm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2inphhnee.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkewmao.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2aglnnktp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtbrvnb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2omomcdon.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjajazk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2esuljgrc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbrkxpm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrdjdko.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmfgwnf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2btxdcvfq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcdayhh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbszvig.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2boooywfu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mrczimgk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmyydju.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwumaln.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eziimujv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyllndyn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2leqxskmo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2snuhnqiw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2shyrxrcy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzwslkh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2envwxset.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybqdiy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdszqfa.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtjlyvg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xxglqhdi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbnmcxt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2phrvmgek.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmaarbb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2urtqlihe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2olpnsljn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vjehachf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdzwnil.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fssjetvs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2attupybp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvumzgun.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nckvijes.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zptubqrx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obfyzyxi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zidhqgjp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvjrhzd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxyevhx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ytznfyae.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wascuxjh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrgioha.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoqiubj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2egexlrus.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnyuife.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbpemyq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrrkyqc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrshdfzx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioazjkcl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwikumm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpalxny.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2blesqfoi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxoqtxy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lquugazh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aewpoaqo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2syodiups.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyeanjg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeibnfj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnktglx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vffgzcbx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2woqxhmnj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahioniy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsjbmke.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fakcgmni.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdinmdr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcexsxn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2viuuvjug.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbmgwqd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2femxfuti.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjkijfk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvrggjw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xydrkfmn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egtfxsya.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlixmwx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnpbwiu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uylsfowv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqzzerf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyippnyi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnazxei.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybovbhxq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrwovuo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sngevxrt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2duvoqhko.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrsccgs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrgituh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqmyppa.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qpectahp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeipmtmi.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmsnkkc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmsijac.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pdddsvpl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2chwcmroz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqngcxmn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkkncjh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnizppy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqhiqfr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdxnpej.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qffxdiof.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2esvinujk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wujadpmu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgkxzqs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrlxxqr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2labeepfs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jiadbbca.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2phqcfmqv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrvknkz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaparne.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspkzsl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2isrnrove.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcgjshx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2imymrzwm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nezlvcpe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpnhkkt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuompkl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwfytsp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hewfxrpk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgezgvk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iekxvnct.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdqdcnb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjkhlmn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpcognk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcyfkhc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzqcziq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqcjkki.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zubhydml.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrgvqkm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2weaiyjsq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yetpnqkg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2heewsplf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hozcgqql.html


<!-- 参考信息 -->