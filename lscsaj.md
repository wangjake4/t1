代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnkxotb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmbgvex.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvcodgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwdiwpc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvjilct.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayowtzdi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmkafiv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlfxydu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrtrmet.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqksdge.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dckssgbj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmczgvdw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgevzul.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2snllrsjm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2djvbvzgq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbhbbqp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjzhnsg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfehhwm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkmyfsp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwwveav.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrnmsov.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsicqsip.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2azweuhqb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzecvvjp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cstrsxrr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxmmeyw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pewiyqxf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllytuda.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtlkaov.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivijupeb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gjexppgx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdnocyv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxrqkyu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqncelfj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kspncrwp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaetmyk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhhzigd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnybatng.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2muvepwdz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vecejxby.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rgipfaqz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbqinlc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qipspwfs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcdombd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuvekjl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuwewlh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwvkhld.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcyuxxk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfddwnwm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mffpweys.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzrsarh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvkmogy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sbitacta.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfursrtf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnvrdan.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2judzmpkk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iajuqlmu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eswpyybi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2stxaufod.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnazrdpg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2abxrdxqg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2exxknmfn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sscbwkis.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrddvzq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoicsux.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsbymwp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwfplun.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qemfrfdo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoujahej.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2brlsnmux.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bitmhdcp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmozduyq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2thmqbktv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orcajqqr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwwmwwd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2knbycpbr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwudefz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2becutqez.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfyrhfd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2opqpiasl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbvmrkn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdxilse.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2moagiaem.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgijeei.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frvexcpy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cilwwxar.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xncemtpe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ineluiqm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2chtnshel.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgiddtu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2epdwramz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvgfmya.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qgssawxz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iptjbanj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2etgwrwdv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuscslm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqosnj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaqgwxz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2axdamtwn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnkvwqr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzyaepf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwemzmg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cimfhkuw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejszaxjo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtqyhev.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xznimujl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbbxuui.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjabmuf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snidjxht.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2znuvutsr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jieystvj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rftapffy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtysydgv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2esdqlkuq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2disijupn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mleaaxfp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxygmnzd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nwloczic.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2leihowja.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2htdbufnr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqafmuk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqstnpn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jafxzibh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2makmgvoh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxlqqiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxohttx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxkoarj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqdqgvb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzsgsbc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbjxeoe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eitjvjgl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkfsjby.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuvzfzj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2otkjzosf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2upcgxatf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mfisvjvi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtfwpwf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nejjoxdv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvqqucp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzrwgrl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaabenv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfzraze.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfgaywq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2swykqtfy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnrowjb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkcmibl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfsxzuk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iajnjmpi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnghyak.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgpfiux.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjdnnfo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtznoka.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zuonojoo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcclgdtg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtzgrqz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcgimpy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsyzgbl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2axnqjnrg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwuzxgh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxoayjo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2luwjesbe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgrpxvv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hxybtjvr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxxlsok.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiwzklv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vawvvnit.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zpawohxh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuitzav.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhyyrkw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2flnsvarw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aflkubai.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhumcaok.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iocjnxge.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2khtpfgmw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jnalzaih.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypznhwtd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kochjhku.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzngyvdp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2eysyrxkp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxkvxgn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nljhxiny.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2amnpitwt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2braylzvf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2efrkriag.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxbljqq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2teliznkd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvjshay.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yymsxrxg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ztluzicp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vtakxqtn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sikccfwo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcobbnk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwzecoi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2snxfqcax.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqwhmlp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iembpsdg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2etldwjua.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgstcik.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrldgwe.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fozrttgg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsaquvd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jbetifns.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpidabz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqfyfgz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2utmnaifh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbykipxd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbrdqng.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxzmmhc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzkxzoo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iaywbvan.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfzpfow.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2drrancwb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xqasqoho.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsxnifo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osojfbde.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oumhcbdf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdjyxdm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crioobam.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hftyolkp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbktcap.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcotkyc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vurzqjlu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdzpxlq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfgcqnb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2czqkuebd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzcvnuf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoeqkvw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuekujk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tenypfnm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cesxejyc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilykktlj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnvltfh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqsywjb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjngyrmq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbqkalq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2elqrfzbr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yoefeuxg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2okcldxjm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gimkcaby.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqgfuqt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeinuhp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdttygq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bndyodyn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gueojudj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twpiiujg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2algftsfu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxlaxrj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdgjlml.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pjupyeha.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2slujalse.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpcwxqb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxulzdzn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdqpmll.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2egymqzio.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2luvmkmej.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2flvyuzua.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkcmtvu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmomvhzd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rczfgmtr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvvalgi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhonseu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcagafwv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bmejdhwc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cithctll.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ucigxtcn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iptcyyhp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gymlufwk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgmxvqx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fjquftwt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxptnrob.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imgoofqz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rvorfuxs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvftghr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnikctax.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaknshsc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmusqkd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdemeye.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2htcfnvmo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbezeck.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhzruxj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrocryz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqsvjbt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnuhirm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuceayh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbqxvgf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkgxetd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpoyndk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvihdpv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnmrncp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xioebbzb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfmcujb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2srbceqrr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfpygrd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2enoysmtw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eevbhmex.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxxagag.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimfudd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ipugulte.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjcuuyy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wkozrjud.html


<!-- 参考信息 -->