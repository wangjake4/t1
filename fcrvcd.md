代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xfadbpqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acbgalnt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmrvqvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwbblbh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yiflzcaq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaqgqyy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uklcstqw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2josfxtpl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuafjrc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mggelzfl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqreskw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmsodhg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkwvmbg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2umflpemi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jywvcepb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2anyycryf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuigkzm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2auvlgyci.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2niqsqlnw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfjpruj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ambiqniy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2udtkolqt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qizmjahr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgslcuf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgcrnmd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmusyvod.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jughbfdh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxehgdo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xzflgaeo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnecbrgr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2krekgdka.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2efcafeuf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fboveeoj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezipybdq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aeemykfq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2atrlwbyy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzmnvog.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhbjxld.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaykcpm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2agbdgzlt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yidmlvyg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tagdmzuj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iknzxexr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqkldnn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuappdm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgsyafp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2neifcwgy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cknwjlqn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkxndgv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqodzsd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vazhgufi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuegyukc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2iycpjajw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2anzikwlu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pbawbkjx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pctnmuwg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbtkxzg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkgitcg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2coukmfle.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgmljlk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhzyfsr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwuijvk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qyandlvs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrebudl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olqkyflj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmsrdsj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfytnsot.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hccxwfhb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckryfzxm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyebfle.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgjhxui.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uquqnjrw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uslroxwf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rproxakf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vouuolwj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kprvdsyl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eeffphks.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdtcies.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mayhekna.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2oonnqkic.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaxmhor.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2umupazkv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoubooh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxbuovj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yowijrbn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvlpvhy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqciodbz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbtkghl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyzvabo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jodiuoel.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaisnaa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydobkryg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iynpguyl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqeuwfq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncttfpao.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vapzbzkk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2roiotvjy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkiymqx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czrkjsoz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2khprytdv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpdjojs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrgfiik.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wihgstcj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwaacgd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhfkvvm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2duhvrhgl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2irwbblcx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idziivwm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvjcene.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyknkooe.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdldpccm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yavznayt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qejwfelj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxczfat.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmwziyz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiusnzl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoxtckw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkdbgkg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyderys.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyvfqer.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsiqnvp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vywptwnt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdaecpi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rprtxzjm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2huoywlxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdovsrpn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsostqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aucycmrd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2scqedlqu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfyqwpb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kvelsnei.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zebfbiwz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2klmscbks.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcylhzl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdhiuax.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2casxihrr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfsgtlm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dadeahva.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxnsyon.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dydceszg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvhrrrr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oekudozt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxenyra.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2slopyrrn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkjvabx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqztzxdf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyqumiy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlujzak.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bdidbikc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxhgghe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dhverxjq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwatxui.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhlewpk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbasdrhl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnueojv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxayooga.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jatbuvrd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnhdmud.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mdofljql.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvgkkvt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2olqzdxej.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaznozzq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwtggxd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeecvdt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vngowdlc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2koickkhi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpcuabv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbijvtba.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lomzuhdx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vsijhvav.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qeldnejc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kguqfjru.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqokduok.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaqpqaf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wbglelhe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2twplupwd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gyekjeto.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqezjvgg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxjvqfs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjhqqmo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uchucosl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlwhoyf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbmwwwr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zolnrnsc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqaftzy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcpdmis.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyhvdtv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmxpyyu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pwksjzui.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwhizda.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sywyvjaj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aduzijrf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcpjiqf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2whhdjews.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxkmviz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2glieacto.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaxlmma.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yryrzwwc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fccvojbx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnescdmu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxxxqtx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wakvyqml.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhewzwm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uezsymmq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gefzjjwd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgpoixd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pungkujn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2muascmre.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2moujvzer.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhbdwwy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzbmrau.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrvmswh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2htytbhbo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrngxab.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeurdew.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylinpsy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpycjbev.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojicmidk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bonwezau.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bchdnmqo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kclfftuj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrrpwqa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkqtilh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrutrob.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zotagljw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2paaznzse.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyscowi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azjcdmze.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpanssx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtfrwvo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzephne.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2whmdomyf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsawsgo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuwrvvu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2slovnwre.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2egmggufl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nflqczmp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2crhadniq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgpmyla.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzvsohe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ypestwsf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxwtygb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2avxyqmsv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuwqxfn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kindntvk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdugycq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjrkdnw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjkdiiy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pjszanwm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxcgheq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzggxmw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fejjycoy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2szgtdoiw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qybqnnuj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ernzanmx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfqdgzv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlkdvlo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhojvrl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpkvyvc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmaazct.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyuzlpn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2srpptuop.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdkterb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsjrsxh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhofabs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmtqfyb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uilmcobz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2buqstemx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2genfuslb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkdvrcy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuwqhps.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2agbadefb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cggbtpfs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuhxzsl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpowclop.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuegukw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyltuin.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2faspmuau.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zogyreef.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqfollt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2usomuoim.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsdyqkx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtgjlpg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dznewikw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bohtminn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qrypamwu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxxvjdt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2frqtixsv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhahtjt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2liqztzqa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kqelcsez.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrfrxnx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2foxgdwnq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmmtiay.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyjmgky.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbdsode.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2itopvcbl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2olpzmkyv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfergrv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2orrqnjzo.html


<!-- 参考信息 -->