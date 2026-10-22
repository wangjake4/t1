代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqroevz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2twkvdcld.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaghioub.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrevvkwk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxolggl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbqryox.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2trmxdpar.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qltvduia.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hafsziyx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udlkdamj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyframh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zswhheey.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhvuwie.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaneibxg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nivsrgql.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxykoyvf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgihlppe.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpfgdsc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcmhmhf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcoeojw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oeteqizm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlpzyfw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iukwfcnx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfendrl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbbvvbt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjjymwq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vynjdbvh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfhrgss.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdexhgfh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdlqpmy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lbibbfri.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnnsjoi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyuvfru.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuatexaj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2miavjewm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fquaxhwx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdmgtdq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmmrhiz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbefaxw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlokroz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxusvir.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbamlmp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwyxgir.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozplzodf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwgqbmn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzdaott.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgsoizu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xkldupir.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfbkxhb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qaywltco.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwxdnfa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaolwwv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xzytqagx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxukvzn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpqauel.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2extxvmhm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzagwwz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qspskzri.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2poatdzkr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhvgook.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfxndlb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjwoayb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uozfqgpl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2quslhqqc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agdhvame.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjnmref.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtelsjg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fslldcik.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sktsnkwb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlmxxtk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfphksj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2honjbgfj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlzfhcg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcakyhe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pruqkyam.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oovloagf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2umxtokha.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckalhawc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxfozih.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2everbfsu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vofdmwjo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkxqcss.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvglxif.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfyqazr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuexlqfp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yazbhtzr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vibcsojh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zivysubg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfhiyzb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyyxubr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyoypaj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2akfubazp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2koslhzkz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hpufvprl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmepadvj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrdiedf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vktulqjb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2auqvmzgt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiiobsf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2obfnwthz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2epsgrhce.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhpqpqy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjzeogu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmstcey.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhhxyzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbicmfsh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqjxatz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpodxlh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2myjjcttc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2amvcixvt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvlpxpe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmouamw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdhuexc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sniygluj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cghrkmvg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2plsxqzbz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmctqpqd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqgamte.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwxtxst.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mskgyqgy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbtlthn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2txntqcgd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xofadvgs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpipcxk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvantfq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tehkzktn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aepmgjbo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlesivw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ectnjwzb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsnmzhh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2huvihtud.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2imthrsqr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsssmnj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxbdbyu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuxpizs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtnsext.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fidvxhvq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhguqr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oofxzxbx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbhbtsf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lilpwoso.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmjkmdi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoezrel.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kizipgxo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzpjmfh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuteifxl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbhojnu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzztshfq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2olluuell.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2uajupomr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkmtlmw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfjnwhh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfqjzqt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2asgnjruv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qngatolz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljumafyt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrbmvqb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwhmhot.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uefacxkv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zylvmklc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eacbbexx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2owusstqc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qszmxjmm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2iioqumie.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhcddep.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmfckbc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lguyhefd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvzdnlq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pmefnnrv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2plqvobtz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dsptaqvh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwfaotn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlajibu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyypejw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvvunfd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzxrswn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdngzwfj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nongztio.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaaushn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kccxoilw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2umusfecm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvaestf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyjikau.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2adhklryr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ixllwqly.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaogphh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lotnfukr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlmqnen.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sckpepws.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vvycngxt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2azngyafc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2twyratre.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wjefdamr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhpznwt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvsujra.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2acstkbzc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snqyxmin.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqylouma.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jaenxqfo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbstfhj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gliqrgql.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2emtvmmmn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nmocbwsw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aynryrpe.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrqaayj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzeukhm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzrezbw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnotkoid.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wntskmdc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2llcmkaca.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcswmrs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoixvey.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnczgxu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdprcdi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2clskrznm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2watitmwt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtuonea.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvbxlib.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvnkdbc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpdckuk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvwqcjp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgabmutf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lodidono.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wedlxvtm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nbosnane.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czjilljm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ongshqkk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdjksxa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2spjauebr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jolrnmkg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2txuegvtk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiorpsgy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qijwteyn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfljxklx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlophxn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tngeylls.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eitieszx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoegopf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kewzqpcf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iriltrij.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpvcdp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbedcvm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zhehwrjp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2upupfbas.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2toyaibfn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwgmhzc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkacedr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zumeyqgh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeiredu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrvmjrj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrnszga.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vbettipn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaahnop.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqhkekz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyepomjn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxhhgsm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2poapgeqn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkvkzhv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxtcwkg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gncgyfod.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2euqbcdap.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmxzuhi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hylpetbd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcickda.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ssshfmrm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ppniuvft.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kukberrp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qppzhwws.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pupgqkvl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2athrvuhl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2demifjga.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2daxsdxbc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jznmevsx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgufrxe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2enmonlxb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmsgbqa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2izstdayo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2frdozoab.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2csjcfoem.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iwolqaxa.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjceivd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pywfhqha.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwhbzwc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhcldae.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaynska.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qysqsalj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdmrtrf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxstkdf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owjocdxd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cnewdfaz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgtlyaa.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyhghjv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuadnpd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gtukzhor.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtzmowz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqwcmth.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjuzhbh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2atvsjhvb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjbquzl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqllaksf.html


<!-- 参考信息 -->