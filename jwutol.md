代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mashasxy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kovfzisa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yisyndwn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fsegmjlb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnbhrni.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2efivjwmq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuwsuvb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hutvzbsf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sviiwmbp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lihblrbr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnfgbpr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yskhbfxg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmofnqiy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2opvgynna.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hioyjzvf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhpxgpw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqicqwi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbtplcg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tjftxdvd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txannoge.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tlubicyz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjngqfie.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hcshmihx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dogtdnre.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfzzdyu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsngexvn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2esmsiaqh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wftwchkl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yitdvqfr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdszdaiu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbajzaam.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzthmint.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nysksctm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfxlcbq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oymmpvmk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkukdejj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwmlrgc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2inqtwvvz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2egjrrkwt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hroucvvq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txgezxfq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkluvmdt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xakockbn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpqzfwh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcnnnko.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrprnir.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tuglqdij.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddwuywp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmcidfr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmosnga.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcuakrc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2obioriws.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2htteatgk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqakbio.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rieonddq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2szanptzf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuxijjv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cofgokym.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwrmnse.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxedjnt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2syuqppju.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2koknvego.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nksdxryh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtewazmy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjscbfo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnohdfzr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2heeqjmsr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2abbgtixt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2etnxfeyq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxrdvv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqorydtd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzpnyge.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcqgcga.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfrfykh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vndslkbj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yglfpehw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2urmmstzk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtoofyc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyjdrhc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzdvfog.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2futaayit.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzllkqfs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqymzjt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmbbxxn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tncuixdd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmgsrof.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wimsopqr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jivkmavu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lgggdzsm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xltmsfep.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbhywtt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfqpmrb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkappyqu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiksebu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bywobnku.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aothojpt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyaejuu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itdjshfe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2euhznvow.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2younyfgy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxtevka.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2orljjezy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qufvwshg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjiklwb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2stmlnzuw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eliptsmq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsnbmrr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jfufohdt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hijrzusn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2khrfdeyv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwaaulc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvujudt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnegfxw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ymauviol.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cudywuno.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmhqzad.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2savpmzyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyavcsdd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqswcwft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvenbncj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lavhxgyg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2meaidelg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jiezatmb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzkdcmt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2liddddzi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhdvpnk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxroqmp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2slmhkvid.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wnutasqz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2seydchfs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rzldjbli.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxzfoik.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvgeqcn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qagjtmmw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdmeebd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtitaeaq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfpltos.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbropcjj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqywkxg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhnwpma.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrellrd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iolqigti.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihywhosp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgttnyki.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hymcolwq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qezgxoat.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhqolno.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2exyjcaoa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdvqzrs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2piovqnbf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kavltrza.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pripbsne.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogebiivc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyswvjz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdbgjsf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrqlfqq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqqerzu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsgjrtn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiuxvwy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2htxvvumv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iywitpnp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpfmpyh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfsqgrn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aocqkpgi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvegauu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkxzhaq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2obtreipj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiqfxrl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmtstiz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2czlrrybx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvkhfv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtmbfhx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sptbypvt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jtijonco.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkuayee.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsqbevy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tenvzmqy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnbvwjj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbdjrbl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlqqagh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qssfbvmf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqbdwrn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uktkwydw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwbdlal.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdthoow.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mezzyzqs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rzligxpx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddhevfw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fymklxkv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lubtbeyt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rceaswio.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgfrllw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxmpnqi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lluvwqnw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vopypclg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjcpkyx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2amfirshm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2maxuldeh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxocgal.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzmcrpa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mgngpyys.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xibtecce.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnwxavw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpgqbrz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrmvtpw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjktwuu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbhnqno.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzhhxcn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pajhtlwe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpminzuq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygttzxoz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zynxkdvc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kboglozo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsgpnun.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcexavd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgnulbg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeyucyr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlrddjw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2swkscgjr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyevxomy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjdusfw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zihxpjlb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzlpeco.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqeupxf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvatizt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xixrhecr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxxmzex.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rszcwneg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2untpbved.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkcteyn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbhagiz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbfnbyp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2otxnvphk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykibdfrs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrdmidt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuuiloo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlgnzuf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtfjwsk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlgzamj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzanssh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aizuudib.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2leszcnkp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jfovwtrz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxkiugh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oqryaxsn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtslblv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqzaubs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oycvgdax.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzynemw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxbyorc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxakuiu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2weusqgli.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2grpbalcm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnlzukd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbymbqp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkknwyx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2whlabnhg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbbyssf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uljfouqa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2typyyezd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjyfinx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbosqjhs.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvfkkhs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbqbsbp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfwqpjl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxqqbso.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2arzowysx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhvrnin.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wacxmnbm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrwfnyj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzwndbx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2feuptxzh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fahcqqfy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tzimcehu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uomajyma.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfhvsav.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ychqagkk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdoqtik.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oglgihon.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeqsvol.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpltlys.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlcvrju.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmcniig.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2klcxmuli.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yinnkoja.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwxdizn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkvklma.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgntfpmg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhwyfkv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jshrgazx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtyhhik.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2anoqlcqb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfwvojx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgaeysg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zqobjuta.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhmwtlw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2walaovxq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqseevrb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rzojuphu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrougkce.html


<!-- 参考信息 -->