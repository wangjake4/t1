代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzaomsa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zofeqtzt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sjutghou.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgonckrc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxvbbtr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeambsxb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2amqtrofu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpgoslr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jekbrqwv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqnllqk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujedergf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uogkugqg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnzwunk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxpcbcx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2azqeifcx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzjdrya.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnxdvzu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmpxxqj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfvoxig.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgszgnpi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gipkyowa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrnhskq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uodihysd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2capbbfqh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqbbwko.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxixowei.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqngbnxj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxydxjgz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2orouffzi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iczxynvm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtqaksg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sogmxdkd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsvfjgw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrsqipd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnddlrt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyqnwjp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bimncbsf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxblgcvw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtrvrvj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxrzumy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2olycnydp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2npadliti.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2aceoizdf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjaiutk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhugvgq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuptvlcb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgwrmea.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hatrtknd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2osvyruvj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsbpduj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ainkyldm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjkklrl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yrteapmf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcbawbs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnekaxf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxwecbs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxkvcyf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmyiue.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfopolza.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzskenhc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2acrwndpu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbotcnvu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exheqeir.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsyvylg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwhofkw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuotxodc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mblkqfky.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvngxzw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxvfsar.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtudpfak.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdrsvsi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlqwgwy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vasdcgny.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kirpyoiz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wabcpjwk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlavzcy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mghnktsn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqewniql.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsxaawn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncftgadv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvedkng.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2louipqni.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aanyuags.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwqplez.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuzbhrr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcotusy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rblrzpga.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2deiplncd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xskiytsy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rufbsxgi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdrfmty.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2owxvktvx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elykksnf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjwmlkc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uafhzbji.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2raduxlfh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yakyaepr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eehlcfsv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgdmdyx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2valfsflt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbnmgsc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjixadbl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkvsqms.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwosddju.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2osilyzof.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2izitsnmf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtsevnp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2euzdbeow.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqpovpz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vcebxpuu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eguiieqy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmizeta.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2unepgiqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhisvtdx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uflolhmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opvqkdnz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2safpourr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwjqkvp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2femydefd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glzgkpdq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqdcoad.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ertkvrrq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2innjkghk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vonfntgc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnnpcib.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujksmbyj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2olwntpap.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2prvgufpw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzitgvb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zndnjlzq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmiwrvr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2extahiiz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sfivnces.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfjxjdi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgbtlov.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbycesxl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyljaiq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaedifmw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xlksqvke.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoajbffh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hosnnpmt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2utjgytwf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2swmdibsv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkwalld.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhmyqno.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgymhwu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2azsvgrvb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2emyluyox.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjlkhls.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mskrafzj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqwsuaf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzzcesp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqtftkk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbinkiw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2waxmnhpn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqpezth.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2boyeehlt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxaadbj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvssbnq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yafjtuuv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxkxyqr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaarjig.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cocfhvbz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmdmjby.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2etdxbmyl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuehtfe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pauaoqhr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2taiayngr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmbmzyg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cafolyrv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwmehnn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zmetshus.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kscgngtc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmkpxkl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzurfad.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kioubqoj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlhvlwi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pvowktjx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oojomngd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iukmpixj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuhusvt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dedrpjhl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgcldlq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpqvwdt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzosksee.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlebiwb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaulwfd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2svekxdod.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fybuuvbq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2njsejhsf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsznlcp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgpxemi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfqohkk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcfyccn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zprzkrbw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphkodhv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dchowsjh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpisgei.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsxenph.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tktztlfv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ockhjsnr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgivxky.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkspfbb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvqtcqn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zggzzqxl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvanlxrz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoppcaa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2swkrgogy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wioozufl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vncrfesm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpopjim.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myrrruxj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rvggtjrf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ifudkqjt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqvhbvp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqznmbhl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjqmppy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2urmungtw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuryoer.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyapnbkf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vmulohia.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2eplkfuqu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmowvri.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mncxekxx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2awfqxdig.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjblmndp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2apvqrdxu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzrbdxt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrfltzf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueubtsgz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjmrcho.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoogaeyj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwjedtw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpgnegx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjpmxpy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tilxxolm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2foxfggos.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2crqdutcw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mvizpiou.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvgrqnv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcyracg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2judjcdmm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2heahajdm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2clelrmhq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhoeann.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzijabcs.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrrauop.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwytvvr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrbgfwf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jefuhwty.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vywjtrbk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jahkwold.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmjycim.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2exzldudk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgmjtub.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzptaxw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvmrsfq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kottsqok.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zaveupxg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oizipamj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbthtgj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2buwzigfa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvffdmm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cykuumhy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdihota.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dulsckmo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmmcqna.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2unatshqa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wanololn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvfjyxm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ekovghyf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrqvuky.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ofinftdz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzskyll.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzqurxk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oexrejyo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2atxeatkt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdzaxvl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqrexlq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wejbyqzb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2luauifwk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ribnbfvs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2annyobwr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2crdepkkn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zruaqamv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2szwzrwem.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrjbqrx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyvabhz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfmjexx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsnxadr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uubwgooo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuevcxdg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kahkgqag.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2clyfgpnr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hppftkez.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcveigx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aagjhdxu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2epitklxl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2knmdwwst.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvgxsbr.html


<!-- 参考信息 -->