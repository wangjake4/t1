代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tssutuoc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtwgfxx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjzrxvn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yskaruco.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vhewddbw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdsiktq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ogszmzfy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2monayzjs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2doclnmgc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwqrzpy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiattmm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyglawv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbycxmdw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyeggcv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmzlaee.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oundfedt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxzjlfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzfgysd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvdbxzw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2myudtgld.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwvpogs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ataylqlh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgnkizi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktrptny.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvqcjwn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2svxtuegx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skktlupj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2stovogck.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrvoypc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkjouqv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmrfodr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uleoteqa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zssxzzvf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2urvsxqmj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xabuiwsm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvvwogk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnuuqcr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkwyrvs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjmpblv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rywzlsgq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyjkwjg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxfzakm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqoqzfy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pznscwuc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkhqhvc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndskxljl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrcdfmr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2itdmniif.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2anwkpwst.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcazljff.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2avbdgvva.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdflfkdm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbahzpp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbkufnj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzifpqs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2blqazqmq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnfukqb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkfteeu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sstyogzw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfkmjlq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkryfhm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwtrhjb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xprpfczr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkohpnob.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzglrrjb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhadfnv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjytgnvb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2szelnwbh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2neopaota.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxkjwkl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkhvxuz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sklsezei.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aribklwn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcewctmo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mihnbvbr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2czutonoq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnhxwkr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2drtdvyiy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvyemwi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkektcwj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkrravh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrffoqw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2opblbzci.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2movpuqoh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gumzrfku.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoysnsxv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qplocnmv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsqwyjc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmidcrc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwhdufo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfjzgqc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpdbahc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdisegec.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhotuqlf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgjkfxi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaugiot.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcasnnyt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnrozxg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfbittj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isuvlcvi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjthemw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2idrlhlst.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2smdsroal.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uankgkzy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmhkcai.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rjztiptl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpsqrgd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhtjpeo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphfthww.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgjtltq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvctdofv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2huwotcjs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjrypme.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yikgehrd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsvbuqc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmtwkvu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xopsfbks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqmzhyt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqigypps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jidozuob.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lvblqbwu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vkotygoo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bisjgtyi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htoturhe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnsywfu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmkgqns.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwikqay.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jaerboga.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqijehjm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwyxdzz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yobhfcnc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsdfrkb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oebdlrff.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxzocjv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmmkhph.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcnkhua.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yluaybap.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2giqtgjhc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cxomrqgd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlskiusi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvfjilf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxxacgc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtwohdq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgshzra.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvavzjw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpriejf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2prptlppk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wveoyasq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnexnvq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dziicmor.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2emxkwzwc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwyalmo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxcmtwl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlofzubl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2olgizmgt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bznmwfwr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jrytamtw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehoksva.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vmebhnnk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrbbqnd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcumixs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjblejb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sffsvjyw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkowtbwu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abwhpuhx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kopeqbkk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcrpcop.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsyyyuo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzbucwl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcdojpo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaexvpx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqksndz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaeaqge.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2axcitdub.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfltkfx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lozishou.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xjchxzoe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hcccgaot.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jzttcwyn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogljvksm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nggymmfq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmkbogb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zewbmblp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqrqocf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bccijehk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkpxqpu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbhtxia.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcfsxiz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvnuaju.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazvnhde.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2afegfxrf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2euokcdfs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2alqzjncu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsdpwkf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqzvchs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwombuf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzhjooe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydatderd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2imjxqysd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhuahpl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhouzsl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lffcqlwy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmhgvmo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ombqvpkv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2efahdgbo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvkxbsq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcjoqwq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2plfpxtec.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcpqjma.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wulbrfud.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nykjymsx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqlpkgw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kibeloqx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2apjvojte.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnapdfk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efwiehjr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kykxllnj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2huhcbqgw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yntebezu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhlppdi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqcoimz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxbfzyd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twshxwmm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nldlmftw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2idtacotx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dudzyzin.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiibbwk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2noyptdgj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pniqkvaj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnqqjda.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zisnvaxp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmreodv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2unvyaiaj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiudpdi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwwepub.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjddwjrt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nabyebtb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnrjnfs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhjrqxz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnahopwl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jguwflum.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzoudlm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlccwor.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdhaptk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qfesjmju.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntezydme.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hkabizbn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2icoorgty.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpkhuvn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gojrlnnp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gluxfdgi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvleqalb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqudate.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsdqkpw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnkoxfl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwshjwjb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lqztgijk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptivygrw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfnmqvt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vrturqzl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fakepocl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhjkzvq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndorlsvk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vbozgouy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2prodrfwl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xukehlxw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgewlylx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2usqihryg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2axoivavd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2clwuvdno.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpbvljb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlqkzaw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoyfwyu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xzumlgox.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iezvqzwa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lfghekho.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cdarzyaw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pubmevgl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzaxfig.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kasccbif.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jggrufwx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cqicscrd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjsveol.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlrcyur.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgjcscj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwphatjh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fehdfzie.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjddsjmw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwwhsfx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xuthyhkd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2knagneey.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwewdfy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuuzhhg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2homhprnz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nirhyiry.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2plnpewlw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2huqgnvdi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsrukfi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdtgqvx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgefzxux.html


<!-- 参考信息 -->