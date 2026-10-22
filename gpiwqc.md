代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeuohmj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2autwenrc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zifzgnce.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsrghuw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrsfwey.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wujucqhq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qurmeosq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2juwoeqnv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2htlmvuzr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsonobgd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyolvja.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2essqyyuc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrbeurs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tscohzkb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kmocyvok.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2clwlusqm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgnvxec.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgqplzu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iphbtltr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iabtgdpx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbhnejw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfmjquf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sampxojn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wurylhus.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2revefxoe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnedyeln.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hititmxp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcfkfye.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2atnvpxpe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxqiwjq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kyswgazb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjevqzx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyywgwj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kebkdqfr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gewqyjcs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncylgneg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2obbjdvzz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lynsquwm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2obqmgejg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfybwiel.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2khcyscuu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujimgmij.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdnsvsg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qphdwkxx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhjkxat.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2thkfubpm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbghjrs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cseiyuqh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgvexwh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kakhqsvw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcujmyki.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaveosr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2finipomk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2onagjbvg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbddynkz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2repytucu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzqjoxg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iruwwico.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkilxrtd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dgviwvgh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfatyohs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkzpivh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxcepqt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhluingi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2grllnfzi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2azctebab.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrhfynk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdmeyzz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wenuxewl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrybjzyx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvfxmsv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwwgjaf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiirqeq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2njduheqw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2szqiswdf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjwbvfv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvmlmsu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atciengj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmqzgsy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llaaycab.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvfawfy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igoaybfc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmysjqlp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyylvxf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asjzooov.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyifobp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjuqudk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfplplvn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpubhza.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khogvtkb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwisskp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnxypbx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkemyfj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2axzpdmhi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxqrwxg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmxymef.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmqqkip.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwgzhro.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbpeisx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qobqwlin.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2slnvmikr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxpjniv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2usnoukye.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbtfgvx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2erxozgvp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbxqika.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohjdjuv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbjkvsx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yygxundp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjxsicb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpkgkvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvxlqjy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgtpitw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcjbyul.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcsjvys.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzhvzoz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nrixfnlx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyevsly.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vslvevnl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwivhww.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2unizvlbn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ourlttmy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2enieffps.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2crixiywy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvnibxj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2orzayhhj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jscdwayw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhfszta.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqulowk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xukosixz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnvxjqb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjjdlmw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuqwyht.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpurqypt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkdqxhp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwopewej.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pibfoldx.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlerbvl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgifjnub.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpxekaj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zknrapno.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkwbykm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsrnowp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebedingw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fovnndof.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkmyxtj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2syndxbbj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpvdkld.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2adyhsduf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2athmirwx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ctusfqyy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeazzzf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2khgecsiz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qcofyodh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iielpayn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eatkfdup.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hijdczjk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2omzchvwz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tiifilwx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eecgrnkp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zarmlfen.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uibmpwup.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2efvnqyjo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeabvqgz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2haksbypq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2atypzqwf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxnhaak.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aioobolm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mxalkzts.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqmuww.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqkxaxg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaekjuq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtcivhr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiavfeq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbndlqu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2auhvyjox.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoblfbi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvxvnup.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtrncjj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbrxnoe.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2stdicxyo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqjpbjh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yftjtowe.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvhpmld.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2novcfcbe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhdcynq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2atrfvzpv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2antqliqo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxqhlht.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrfhhwk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2amdqofzh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyrnqcg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2guclgqmt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtvdqmy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2foslwkty.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuwxtlv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiupclk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2upghashm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkyovha.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgkjtji.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fncbnajo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdnvere.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydohtldl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2peopidgd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyczeww.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2niiqmwez.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjwlntm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fziqpfrq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kitfumtf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2urkodpsk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjcgmtu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvxaqzs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkbvmff.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgemkafr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amsrpjdd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aznbkkrq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlwkwco.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2edwawhxb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ektgwchd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2onawbaul.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnkqqgm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yeousigi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjetofls.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svwxzcla.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jclucxlc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmsielh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgsxnvg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvygnqvp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2heeixwqf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgswdnd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkhhxgf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwibioo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwfwshx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyzwjfu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ttobzsqb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2udgmpmug.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yiznwmbu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdebphl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pvomcxqo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2irkmozjh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uynbtjrl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2giaudfec.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfwymxf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdiktfo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eshiauom.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbqulmj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwngpsd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfslrob.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2erfkwgvm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyrprxd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gczhoznv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvfquik.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmylvqe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqkrjca.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wlowmfux.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfktsrf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmivkqd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyvkkpb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwzohcf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2msqajfyk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2axpcgjal.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pcshewtt.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrwhfwb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2odkxxcvd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvmsprg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zutfhacx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2esrbupyz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvevxmg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiykmsu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2whrofwex.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ldusaldp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2broskkro.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2urliaphp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzotytc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kxidvxcw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aloepbro.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzgjkho.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfkripv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2flpluqbo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhtsris.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kztlhxkm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2utstphyt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyavqri.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzixbkd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2itvtnbdt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2viyctxgg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyeopau.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhxtbjg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbfsent.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpjqxbu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcernyz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2crggmrwb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecehvevg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxicnua.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtjyykj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrrqoox.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjbqgmh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2krbiokvm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgssevd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gspdlsig.html


<!-- 参考信息 -->