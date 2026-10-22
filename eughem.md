代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcwesvx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgbawye.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kykytdit.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkodsop.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkokfsc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2potcixme.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsqndxh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkbexcn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkuvpeb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2otbjxzhh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqyvllf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfztdqdp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2accvklkh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmklzefj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bxutcorm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqrbuqe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqywrfp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snzwgcec.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsugxfw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbsfxgd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xabyhbvp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryqilcb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxbrbtn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2utmoofqd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmbmwfb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzfwdsh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjhoqzc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zabqcuaa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqlxkap.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nypziwtn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxfrrus.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkylrvwd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pslcyuvn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgqudo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2svsgsryp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wngmcrqb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxkuybq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2skzhhbqe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdoduyt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmnsaed.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vsihmexi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoisdqdp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfxqick.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjjjbvq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfgcdra.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oizfamsw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lsygsgfn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgegnpm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ioahgjca.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbitqown.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzqghmb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxlhsvb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bntnfpou.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaezjutp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mimqqtjm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtlnnze.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pevlpfhv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zofjviam.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwzdgbz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdxhgew.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2esfzdvel.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udewrvis.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoskvjq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhbzvap.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oiewskav.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnrixdd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiiqttq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xixjibuw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ognlxogv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2beswnzvn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dysvxawj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqpnnmp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvqzjwx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqjepme.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrbiufo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sveloikj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2djwzeszq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyuhrlt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmayvqan.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqcgaxi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtvbmyv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwkbwra.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyjdlnt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmykhsq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnqwcag.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwpsdgt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzlvler.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqbgwja.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcylopyn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duadzazo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzahuop.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpegxaze.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szqasyqi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ochfnkta.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvtsvyu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ludcviuu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axmxajhm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeasfna.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhujhsql.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtisakt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfsjsts.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2liegzaea.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiedomwc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jvytrpjw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtjbmlq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrywzks.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfxstzs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bosuonns.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwzhuiv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiquigv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrznlio.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zirczpii.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgssebo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vepfsxvq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfdkwck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdchpmdd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjdgaxj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nsecvknz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mdunskgc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swcwvqvm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhmrzaf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2paddqunx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjrxaao.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qiulvajr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhmhxnr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2huqcevib.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgmnesl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtuqnij.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoenmtw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpduugc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvocqpe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyybybg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyethpn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjfbfod.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvlefrk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2frubxcxb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2flyhnbmv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pifmvagf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2giccxtfb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcjgisc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdgesrq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwbfwhs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2onhmrrby.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjytgluu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nusseqtd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnzdgbz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhpamba.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2crijdvqb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2skhongoo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaotigcf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oqggzsyg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaynpoen.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dvalvuvt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2khkggnsl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2abqgepcd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcfaggm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivowufyl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbaczfv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiokadn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozatsefj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhpkxdx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyniwor.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2memyemrg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoaozei.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkjbkkz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgeukgh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhkizho.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlthobd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2biknccst.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vsslaxjl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvzbnkz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpsourd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzhymoe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lljzgsvi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jilbeghx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnuefsf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdtkfcg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uluunalf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dzktzsax.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxgjlmk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfquaka.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrbpoez.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2akoabzxu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpoxepc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cepxsjrx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdyoqag.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2trbqwulx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2budanpqd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ayggecuc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gliynqff.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fzskllvz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2juolazmd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwpcfpq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqcodjl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wuklmhfv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgndtfk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iuibazrq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdqhfie.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjvtpnp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdmzjsf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tlosqdfb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaqbshc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hotbumrs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjurvnft.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2skhifkmp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfsmorc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eezqnoux.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxnloex.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaikppn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyirttf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rfquayhi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdyhgup.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hejjbskj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eacjylmr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfpujeg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxceacze.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmzrlji.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrsswjq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuywlghv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbvkwcx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2oteudjmo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dqirinei.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2joayamid.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sewcgcjm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdbsjbn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltedoisb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgsjfqb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frtjaspu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfqpbjs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agbepwrn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zvthxqhr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2whbsejtj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2afhtajbe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bflmqyaz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zirwdddn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2azqnluol.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eenfyxux.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2heegrxif.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2faeyubqc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2iderkhns.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rycctztl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfztmzcn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvyutmw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnqxcub.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yihyykvs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxoailw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmfdblb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgttyiq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhbhbty.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjzsfcn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhnuwzx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zatflurz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcbinpd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdpbvjp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgoylsl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kovrsfwn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ncubplxw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfendsj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ayznbufc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2utdtzzva.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pewcddbb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhtgfpf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyydgmor.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fccyrzbg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rtohcysu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jwygmcpe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlsuqws.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcuqenf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tumgigmz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfguhcv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrddkxe.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxqwhzv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2znryhdtx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmxorgl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvvhjjz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2twmrfdzn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ebittftq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuoqqgy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2samwiios.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuefaqpe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsqqlcr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzguiwgw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyoyymv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2aictuobi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbvgkqf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkloqoe.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rhayqcme.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoqxkcr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbewudp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqxmxbz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2grumaxrl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdfogaj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lstyczak.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcyfhdf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrrwqe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrpjmty.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qarepygk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ilacxacq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dfatcscg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2quundkub.html


<!-- 参考信息 -->