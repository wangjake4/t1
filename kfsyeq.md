代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ibafdxto.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2myagvdus.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aoipaeqs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqegkje.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsgcfth.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqniutp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kezgodjz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrrcdef.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bijkulrk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2klsloqdf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dashcgfl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdhkqkw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqfscrf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2scbealeq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsdiunh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfynbca.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqmnvfw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppheipkk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbttynmf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2farthnop.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2meolxqvx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eacuxpik.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlxiglb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlpnobn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2htbvexca.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgaifcx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbmrhqg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2glmzwgwr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zodnhfxa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvbislo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idcwbomv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezijzakt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxfhabe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvnjggl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2krwjgbvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2halnjgba.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvidaayj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbtsimu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wolvusiq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtqsvut.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxupazl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnavucc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2drnkmwuo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xplybhvz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2axvxvxho.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zloscqjl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2coydijgv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2svwdpqnx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjoqcgc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nefxtdko.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfarmuv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcifmzt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agbapbeg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxtmtgw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfvydpz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jirktxui.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2getlrtqy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uvasnwfq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dheriyld.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sebzqkgs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzobjuqi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plquslcl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvddysd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxxmttr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsgwbev.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rizcqajo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyztnjp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnhcuyi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfhowne.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pklwcmqn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzcznfa.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhocpbnf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyvjmcx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbmgkev.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzagtzx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2flabvgua.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2spjaewgm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uojqduds.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2atcpqlvb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnnpuof.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqazwac.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvpslxy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tbssomat.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pujzbftf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrnufot.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdezkhjx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yoagmzui.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqxxacu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkdwypk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anbdstuu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqitwvzk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tordwjyv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxepygj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2reipnaed.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lovebypr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrnhvof.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqhlbvf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxieqzw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaiunpp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzikquj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvcxtpe.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsnpxfj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qampuqhu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aszzaxlf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgegmjx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axasbqem.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2veyuehjz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2csmpfyfm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmdtjon.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrjifof.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2scpqdobo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmuwhwl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygobehzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfryxidl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiglozp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2diqstzcr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2blglvfkz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2joceaukp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxeopjq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hihkcfku.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmektppu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpphnhqf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rbheaojr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfzufwl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ponxdlsy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eslxcjfb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fypqijhh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2agjwtpye.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tolodibm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnnmcgg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nfelvpre.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsarsin.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ajampehi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2omxrbljf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2neotpbnp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwszxyg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxydsal.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfhzrge.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2twzclnvl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxldnnfh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvtylfh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zebovtjq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcqbeyz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fywbcjkg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2basndqlf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2npditjai.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2snvvvzbk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2meztoxti.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqruxya.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2shcxlyeg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkitoca.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aabglslz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpdrivg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazlrpbd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvaqtlx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2icaudjls.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2shywayiy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oiudrslh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvurvbb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2okubtxyi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eesedvrn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwogxug.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2arqrpxlc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmsvfiw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmcoolc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulewakej.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhcrenp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsahaxfu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoznuyi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrkvkjw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zczvvbuh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sluyfexd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2acawdezk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ooitvdhl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jupxxdvy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnsplnz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nurgnsnn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aigowhha.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qysbcaug.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mpseozfv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaurxwv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeocynh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2djrcgpqa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzfgevp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqailex.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyaxewo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnmcofq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2txlqjjwt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zegnvabi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkbehho.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfcoiyx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2szujujpo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2olijfsmt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2aihapyxq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzbphyb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhhfsey.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fwusyajd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iaakpank.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tetdoxba.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkutxjxw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2watbvznu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbergzke.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjbnsxl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqzeqvx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wagggwva.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrrpzzq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhqzasa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uihtvhti.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcidros.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qveiuamt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdbedco.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdkbsoj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqikxte.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yrafzkzr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpqpnue.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwkwjxk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmxrmhs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjewjtxe.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfhnojv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxclmvoh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqsmwjw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaefmye.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgueymk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzglsqyq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbmfmeu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2iikfeakr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dofzxwmj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxbtxme.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2onlmpeoo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oixmdbdz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jndkpakd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njyzxngp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfutjkqk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkqfmms.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkwnqom.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2scerwfen.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cqylrkun.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmrcpsk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vznsflck.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoecugl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpeycdl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouadprbq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnwzoaf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmldeghb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfnjylg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwwxljn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxvxuzs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ietqfzdx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzaweia.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2esxkplfd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeenruv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2chtuezuk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2znufyzym.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrofcqv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tvslmewr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuxcbwj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwjrslv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfqjtya.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsgqipo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwmmocn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yjisumfd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxrlcqy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlpegrm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkmevak.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lmncdyoa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxihiid.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmjhrvi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiscplra.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoepwre.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuhlesq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvhsmqd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pyusdjwj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnrmyie.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqmttwv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2chkbwjtm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2odecfwdm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nimpshvd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xltaqcvj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkvjqls.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjnvmoy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iouebnvz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqmwbhe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dygqnjhd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2iegaiipf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzzcqhf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrmmtew.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wwstgwqw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vgohtksy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdeegui.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gchrekdo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jyupiggj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmnmuiw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jorrdswi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dagsgmtr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcqbfab.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdhdkdf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhmijzr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfooowz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnvvwrl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwgdmxj.html


<!-- 参考信息 -->