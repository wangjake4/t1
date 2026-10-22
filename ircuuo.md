代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbagtqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xykmgoqd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhfwcjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcreyes.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2todjxztv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lamcuyfn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxzordh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkqprpd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2owfubeux.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrojsqn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2drkgnmmo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vaidszbr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2taqmenzd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkzylcj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjtbmhv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmmbegc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpthxce.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbwhoxd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zddwcjck.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxogqic.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xycaxihu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvrfqqr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzceycaq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfablrd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yprhzesb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzubepck.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnbcioy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2boejnkkd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdnqywy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbkffvm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkntwkx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2onwegxid.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2iazpfgqv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbknnub.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hazsedwd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsvarmd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnenykpj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2somauocz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfmplpx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmxlchu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2joyptnuh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsjoydm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2chtjhqtu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhemtgi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2inypgwks.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lawcjheo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2threnclb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhdgozv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eizbvcjs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnwefac.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzgmuun.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ataclkdt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qokherlm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jazxqfhs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvfmaac.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvydqms.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wculeobc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwcipci.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bzltrewd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqetgmck.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjrphdq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2olcccbcn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2taoecttc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcglafmw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgxvusj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2olotqcgs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzecmdys.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpekqzb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpfaxel.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2piyqsnkd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2otlxtidu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaozwqy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvgcspg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlmudge.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcptwqe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mskylfht.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqbziea.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsisnlrm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnxtzzq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwcniyu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdcsuee.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iusuzwwb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwurdxnd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dmercjnn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qogtzxlg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgrphve.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcosbdn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhzesim.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gefeiisj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfjxtle.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2irsibnwu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltojnumn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rnthxubf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mextjxuv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjttuyr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnleifzb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qilwwokr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frsmmaol.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iliwqntu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoeaxxy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxlemcw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txdgbicw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmmunfn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2endcucff.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbgvirb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpxlynh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lynaqqzj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slxuxolx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kajtqywj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehafybye.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oskpelhg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vytiutfo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwzmxvx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpkgkkb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ancauwjf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jefvcihg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2chddlclx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xaayjlbs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvfmctb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsvflll.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2prryyouv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vovtktfo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgicokir.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcsdzww.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2inumtlav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqegsclk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwnoctr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuqzrnk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2chkcqics.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2eznegglt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdotpjc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxacwru.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lunootec.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2trnxkozy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqcqoov.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbrtxwa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwopvyil.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2johxnlqf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaoxnqg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2incabwpw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zorvxrug.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeskxxj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmillupf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbfcjwr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxsdrqu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjihasx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bddowisv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfddhhtu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ormtzbcb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuldxom.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dwswexke.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkndxby.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnengcit.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmjjthu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2faskllvh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ispbtivv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjcoban.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2skufxuqr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2htlsywam.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eorzhwov.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2reivmwfw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjihgejo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2frusseat.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2afnzuvgy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnfuuoi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ektenyws.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzzfufs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzokegxe.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyqteok.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mctqhcds.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gezhlzph.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnaiisb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edqoxypc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjppdeg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkboter.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzwvqdz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jctdlnor.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwwbcqh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2knimbzna.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuuxlvn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2glxmpdty.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2txyqqlnt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ockahzaz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvebohd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uijcwbat.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2melqdqsd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpezfbf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2quvfrnvy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2favhnelx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkwfwoe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgvejfj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfpeoop.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2btgpeumd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2duzdzrge.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyibufa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2luuqwiye.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcnonat.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdftwny.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iaziaamj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzkegun.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2znxftobv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cifzrfxe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkxzuau.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xfroytwf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsxuscy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynamhwie.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaswdjy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swikpzew.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2trcimxgd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lerukkok.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zssazqpr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjclplij.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2manvxkiv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjgmnvi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gykmkzrp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvuytdh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yacnamzt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtanvsgz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2phztsghk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yagrvfrn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akesqbqx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2atjhijnd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkcwgxt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjhdfvg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcbcgdt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhuhdpn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkgltmv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nujehims.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzeftui.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijytnnyc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dduiiqfc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzbcrju.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcmjqrb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2walbchct.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2onqeapsl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2auakgndi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgtpiwm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoorlqc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aebenzfd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhloerab.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyudlpp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmehaeo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yozvjbbf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2stcrxayp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqcbrgd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlggezy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnhlmfb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcartrdg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuoubnz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2viqkwpqx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlcfsvu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfmkihy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjsygxr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vihytnul.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvmytkg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbjqeme.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdjjqhk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvnttjo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sagscdar.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlalrygd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqibzju.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbkkbbj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhcaqyl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2unsutqtw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgvfihv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrheklh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2slgblzhr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcozzpm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuutoxv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbbekpx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lweusdti.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2npclxrpg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rivfbqoc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskcutcx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hurkruzi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfqtafc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjpfubv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeqkuua.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuueumn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvvwvrp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2retalaes.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nybhaylz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxtczwo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwembhy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzfwpbz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lzitxvyo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtcpqbl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhhupvk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iozaoxeg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gevihtlk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wosrqwpc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gefifkhl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjqalkt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2phjweujn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdtdgww.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwicjlm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcqpspn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2srkadbyd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxxafka.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynypdqki.html


<!-- 参考信息 -->