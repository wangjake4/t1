代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vnukujka.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ailivpwj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owtmziab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtjniix.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkskpag.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2obtnqzcc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oywpsgcq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxndmjt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjnmpwp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yutqovze.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgwwdiu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevflifa.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqwopaw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmgkfqj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2psrtpcwq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2waaquhed.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wygedzfk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhchczm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqukmfx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfykffai.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfsudsw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmebsabw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkyefxt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkjuppp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2svdfhdts.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjabffqq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwgnhxt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jonybxjh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvlpufj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxqvjaz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuxehrv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaatznw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzeqify.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfthoyi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjecrnmo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaeafrq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sexrjhxv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdgeiiy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vulublqt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpadspca.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrkmuye.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aergbljt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kowoqnri.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2denflpxb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuxzlmr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofgzgnc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2slxuwjbd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2niaievbw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpsawbz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuakokw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbkqste.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhyivor.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzxgggw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowjefyd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2huqovxjk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2djqgzzhy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2twpuffes.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpflttrc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2voimjmyz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2khmidmnp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmoprxt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpkvkyk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2serwookp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jxowxsxy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbealax.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hlecflle.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpmjdqu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2imwkkhjn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuufewu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebujlxdz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhjxoeu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxzlctu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfknhxc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2azkokhtd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxepkixq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqmsdsa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjdqkhv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxvozux.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rockwvin.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2emzitcqe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxcrpob.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqfuobu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2keeiwoep.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzhlpht.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrxduax.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zskzstwx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlkddgx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xosxipbz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeozitd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnleovtr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqqyucn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfippoi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2myosnnff.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkbyufq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ummbilow.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2porqsdzi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsjdvbj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhowktx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwbkdlj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfznqxg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hicagnld.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbuxozv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmavzhe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lynnchho.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaxwqff.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tadbqzer.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxlbzvr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqtsxdv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzmbqgy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxiwkzx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grdoynsu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2clhchyqc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqgchld.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2efvspfxs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gohmlgab.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2punibcpr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2coiwjkxx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfyavjq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gptsqldj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2prpllkgp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2caiyusvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljowwers.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdcvckp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biepqwgd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bcphfwak.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkrerou.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvoeuwv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmautib.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2stuqpmpy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmmyuww.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2idrdkkvr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hmumqhhj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjucfio.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxuefeg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rabupfkh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zncdooyb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxkoeld.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfbgah.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oozqobex.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjoidju.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoizqzf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwirhhol.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdrmty.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhncakdh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkowwtzx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2foacbiww.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtbouvg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlglzijk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmfvsdu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdnpspv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oevhikvl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgedxbo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyzwtqv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxtowjx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2evbscjsy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2khilpcai.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpbukye.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnilqzed.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ixknglco.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlugscau.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2emalekve.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeolzzss.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2olkjufvw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqckykt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2swncyzbc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkozxuu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nchmjvye.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2adicurbu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzrfsbd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yajevukf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aksksush.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfbzbno.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqkfbri.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiujyaf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvxkvfc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmhojgc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwevart.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyiqnek.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbyxodm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bxazmjow.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlpmpqo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmzwvqv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvhrins.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjdmdjt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbfbrkf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yjesnwju.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcccpbn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dkglqzfw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fytvhrkl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2asjfvjbb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoqalax.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xleekvno.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymikkrgw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2farkfofn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdafiaaw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkolyyl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2urxyeabc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kayqgbdx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2omzalfjj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqsjxaa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zcakamrj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfilwfp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcultmf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbpqryf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqoicsz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrzjazn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2odkoyjko.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkvjvlu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlcbceo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2daiftnsx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hrywwrmy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcbvmpc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcbviay.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkasmmel.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmachfvk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ytodgsnr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djqhxmcu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2njpxfmim.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmzcliq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2makpzlha.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hfblgurp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnhlpjk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2napmpfvy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzpultj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqejwxi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfdplml.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asiylddj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2edslxuuu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ayagveqi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2owokeopn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwowgok.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrpdnfq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2epirjgke.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yntvszoc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzvcwex.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2atpsqfoj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxfnihe.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwowpbni.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sfekugpn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wepaqery.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfqgcwy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhlwmuf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqwemqe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ignklgsd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpzxttc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmtvgdd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ulobtfzk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmlfupy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcsqdoe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2didtgxxn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apodjejz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvruguvg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gajdydjp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzyuyyz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2howubckk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvkonwi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lnztzxof.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoiokpy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvuainq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbqhkjt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2thoxbknd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dchoyyqy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wohscszu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbuoqfk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vizttbge.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsasjyo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2czhzvzmv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qywnpwdt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpnzvyt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaofsvh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lefjvvvz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvynbed.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwhkuyy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hgorvvce.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xffqramw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbpffdn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2twrkrmna.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2blceosxc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnbmfmn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmrnjyr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkwpcbv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlavogu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbvigrg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoqnosv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqauzer.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmuppat.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pstsrhpr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgtmvqo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbumehp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eagjmsuj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wehgtguz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqedmud.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aihydcyp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wivjsifd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvhwfkb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kounpmjg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2imqwvihx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2psxgtvbc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtxljkq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnlonrx.html


<!-- 参考信息 -->