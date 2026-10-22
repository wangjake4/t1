代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyfchjo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yszyuqjz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvqzhnn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nejhtsgt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2npkzvkdx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2monahtpl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xgipfdfi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2flewhfdh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vgucqdxa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2chlomxte.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyawudx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjauibsv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmbgxcz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqspmtk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxoruhe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2libnncik.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxevuil.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxbcubh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2adyxgrfw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaxppmz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdimeky.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkfanui.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiaelrf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaviuct.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrirdyd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbjwnfs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgzmvon.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujygzyfd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2abuyeytq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkrmpyx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaxeogy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zummgyxm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpukznaj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2byatytwr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrvnjbt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2shqnbxxu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tehojxkr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpirhtvg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fdafdyji.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjykyrn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nhenmliu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jegzombm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcfmuru.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sinmandi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvumafgh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqafliaq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2njqddbud.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmnygof.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yneexfyi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sligzwtf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xneynisl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdbzgxg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rlftawtx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyitfehf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aldakwkz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxugzjm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbeadvt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxczmwu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2afjjxlco.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2idwrifyl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwdbrfh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhqrrpx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzfpwrr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nrphmtim.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhosynbu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrbydzr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2veqjfxop.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcydboh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2thlaoufg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzmvtat.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqlyymd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlzjnvz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jefuhbov.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuqkxxt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2glyqkitu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cnewdgiu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fndfxnxe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jenlawgr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zoumkygw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeevvye.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2apaqclrm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tykmagsq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oztbruqu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2geoonwui.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvswjdr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkjbbzm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfexhamc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjruisgr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hapaxnqk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqiecyf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yismjcsr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toosswbn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqavfer.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akeftcil.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjlvyyp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuamzglq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfzwtbm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrxextx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdzdnpc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaeiqel.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuhnyds.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nosfzqol.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfrradf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2beprajnp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqgrrnu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdiqlqp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhnfbwv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnxgkue.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxsrzai.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2khkbzeok.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2emdvnqgw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgwtfsk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2obymxjwr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbzdomk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdsubwr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pykagobj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2haoternh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2miyadkcb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwocejsm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2byxofjss.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeisjgdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvkdxal.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwvztby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prcxzekd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfthfjm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiwvoit.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgpttvl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezddmqep.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvtqthi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgxvjnb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2donrrptq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eonykrba.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xhikhehd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwiblrr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhfmrvs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sacnndha.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2evkiywrd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlkubtz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eaadumwa.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2clokuhbf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpitcbf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiqcvch.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2owhxftmr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwiiaph.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxglnzv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kftgcvqh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2foyitiwd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2crldwcwm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdneyfmx.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjdpydj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2helplcrm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvhfmpa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gixomomi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrrzqcd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuxhwzs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmittndf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwecutq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2poymxkok.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qfncrvjc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzdcpje.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2njqgapzj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgaqtml.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lsycpitu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2omjewojn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgtodui.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfjgnyi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uequhjmz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfjllgn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pthvcigs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2slcvxmpl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2anxjevwl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvksirhw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2czndiklz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xssjadzh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lxedvgax.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kboobuax.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhgkjyf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2laevnxne.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnruujl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqltqbc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cwydrlds.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbrobav.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iipmfubh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtummwbb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2spbmttsj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aasjlqai.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbrfxpr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfysqqo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2keknkajs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lycbeohl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajibkjwp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2narduylb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2awtpmyxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2alodnyse.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtchxcg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxitlfh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2llvrmvfl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqlcfsv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qaksrvgv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgmdheq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2apugnngm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbctidwx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsnqghw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahogfres.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhojwws.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvngccj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hamdxxce.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojotdoot.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfrraxl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmpdwpj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnetqav.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbmvjjk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkemltbc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuqihbt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2apazyptz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mitnfrkw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qncjvipg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bofowrww.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpuxvdq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chvraonr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufarckkr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2thdmwvox.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcivrol.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqayhisa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2afvutegt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hczlhxqw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpjpfxe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzltaljq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzemyad.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgcrkpj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsnvlcz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsapzkh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwfmjdi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmesfyau.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpafraww.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llowshpp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbjqwkf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eijioczh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtywnmg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpolmrt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vgldjijy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibemhrvn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlrjthr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjbmach.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yktqtiud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjszpnda.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bujwupiu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqefntsa.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcpgwtc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xatndwdd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2acttlgmv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyrzoxs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbviayv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xftppdiy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhwkxin.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwpyypo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2txmnlcwe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxcljtx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xestiacx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2coityved.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eeztzppv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czbwegeq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqsvxmu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuxppeu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sorvhdqo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhpvucb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwsxkvw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqbsaal.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2inaoozfm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgifpdqd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdicjjlw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gimbhtpl.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcowwkf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyzchom.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2abvrfhad.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vloblcfl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvigzig.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrcycef.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlzbibw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2banfhkyj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2coyabpoo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuysosi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpnligd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdnhjcu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2omuskqrt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2aaanezno.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeedpht.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuoofmw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgxnvgu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvfhikz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gydlkwqo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzwegmj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoioewx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2phufuucd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnnmgmr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrnucmr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcsxkrb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dehtgrip.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nutnafuj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpfoaqf.html


<!-- 参考信息 -->