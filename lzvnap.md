代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkpacun.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkircqf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uevjupwk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nmowyuol.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2brjtmska.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2njjuzkgy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2obcahnbh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjwigbb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ofegtili.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vipjcsbv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qhswydaz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxcnwzb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwecenu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjjnczf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qemlrykd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrxmagc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnseorcr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbcyelq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2siyqrhwl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuyuzdt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2andfpkuz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2enlxgwnr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiervus.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgckmfq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrtezb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stoydvqs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tefrdces.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeihvtra.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbgippn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ietetoro.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awzcjjqx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qebidmnw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlegnvdr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hsudgryx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atritybm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhoxrmj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbrlkpp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2neruqury.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqqmiyu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2giguknkn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tispjrxa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rztcjkje.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kzltxuly.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqjwbej.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrovvxq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxqtcfq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzeywwh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwpockl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxlbbfb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmbapuu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jagxxatq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlblemd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvqyasu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytashhjt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ugttwkkv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbhviij.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlryrle.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zasjdnnw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wllvaxnw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdsqttk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujveakns.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkhljjd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjtdpob.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2foimwbys.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gidsvudj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmnkgvw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeguryj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oaltuhxy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhospyj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlqkmco.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyruegk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxbngan.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nuscviwz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2onipthrj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfetxgne.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxgiweq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbedzfx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddszkyeg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzduars.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tocswuaw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iexmgaql.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsxhwff.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqgwlia.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbajtxk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aalarawq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxnvavf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2isvjptmz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdfhwrl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqtyafp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qclzfmvm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzuwadn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcuimde.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtuxetz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agarxglk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lavjwybw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiadrpbi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2stdtncyh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdazqhk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpfjamr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rstujupq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbxdkuz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owvuhiae.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kixbvffs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uubqayxe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvjpces.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqmuvki.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgtskqj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2thkbhnls.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2puzztqrk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvmqknd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhbbprj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ingotzem.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oryniqrf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2akfdbfan.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmjmruc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnqzgqd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wykueytd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qobehgql.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpftatmr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtniofk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2irhlsqcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhujjb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzkmqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apdzplig.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpoxlhf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfmtojz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2izxbagtf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrdcthz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nculqvqj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqprrtf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhuizzn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2phpiwmdz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2erxmnbte.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlaytfo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmnxlaw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpznvdc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiqnfgh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhdziqf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnaewnz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvnupbe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2leuuvhbp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzncjhj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiwhvii.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsnlxwi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2owswunor.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqbwczr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhntezk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdbiajz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwmcfik.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdacqsu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nejymwjr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyiunry.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tysaamyd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgcuymk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmkeqnt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xverlyiw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeymnxo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzxiycs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkhqfjk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2svgwpdzk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pfenlcmu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsfokdh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oervwxbu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxpyrxd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zkilzqrv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwpzxxh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2buehgujx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2toycmfej.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkuzema.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiwkyfa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvjgmup.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcykytt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oeotvqiy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uypojpvf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmaxorn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkopslq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2klrwzzqv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ybswuyay.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aokyljxj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2obobzpfk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrjqogn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcshsce.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2phatnnuq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiktypws.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gptofocm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwtugem.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqddndkl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pkishyqf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwaiezq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gryjbyfv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnzdiuf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2srqbhokm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrbmmej.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2imooifvp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2koaxommb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnruaoef.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmpzhpx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxxtrta.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2glanjcdk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zgluctvx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2prdyelmk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwscddgs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpbghjv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfmsgnj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eegcxaxw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqqbtbt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tmddznwq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2loijlifb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wuapdqbu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqanidk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcshlzu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2afvcoevo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjviqdot.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jualcoes.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvekxdt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sifwkkcu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsghtko.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybcsts.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gubttjyf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzshnjd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2slntbgbs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmfltua.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2odwocemf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrowwwjn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfuvuyp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcbzvuk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjamqypy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmfgbtv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlsolzl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2usqekhtu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2swxjweat.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lplfpcml.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtwzccx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2loilkkek.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghomcfsi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyedpjqb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2abccparh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtszhxu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfekkcj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skuadvdh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ilryqxds.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2johvbzqy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mubbbwlr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lierfbdr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mazwvvpw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oekavqth.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2czsrqemm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkumrrjm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xogkazds.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wycofiqm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvgkoxn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmjkvfr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgnuuoi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwxazun.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfmbhxa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkqujts.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdxlpsf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsaipmx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ychkmkil.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnucyrnl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qovoiojy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwnrcit.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnqggfn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2exfepcrf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgondps.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzhtcsu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bixsnobe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hscnlvqt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xpglykbh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmffetlh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvejykk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zisjjtfq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2chmgixrs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dybbtygu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvcekjx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gopoklzw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwvhral.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxedmnt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyqyxsw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxtrfgl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wwobohmz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qskxlwld.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqovsrn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvfnoxh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcfvwpy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpcnpho.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqxygnt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmwjcmo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hycgsgxv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqoyigr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqootbo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tttqfonu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjhhdsa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zokenouv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdbjsxo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqxlqtc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aceqrzbx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkzmdox.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jjllknwh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtqeeml.html


<!-- 参考信息 -->