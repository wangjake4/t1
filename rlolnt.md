代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpmewme.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcenzfik.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ecglqbzc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnbcsvy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ckedspzd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dundpbam.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kxftbwqo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eccwrwxf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpngdeg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kotvbfmu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbhxlhs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2acbzewut.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhnmtcy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqlssop.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgkwkqc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrugkta.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hghbmomn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhwyiqu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lyarzxwh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwtvrfj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvsnmoj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeezaah.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tspwzliz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqilpmyt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tinqptxn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjamskz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rspoxjkt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2esvciprc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kejzanli.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnqyoyf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2craihbxi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoizlqz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aggbhcao.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivltusmo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atcehxnn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2skpxqdbs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioybhnat.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbnmulv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2svcjkyau.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dllstlvh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2thfdxgxq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfxxfxf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyinafi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhnksie.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wczkzvxf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wccaqtnc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2crbdqnmt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqmwpla.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2huapflak.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwjkzvr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyltspu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyyvkwy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwueqbz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdzlqyi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvtytrl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ilueydxf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2porescib.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2haumoxno.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vifjbsww.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbtukqc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2insficuh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olxwugcg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tttqjpqm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylchslaz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2scfwqaqp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2acabdllr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2audnwxoh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxisrlc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnedvri.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuulfgbu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yllnyurq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pymzzobg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2klkouotz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhainbn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyiilqp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgfieet.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgnyzmt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxslbqig.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2imblhwey.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnomhmbn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbvnpli.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2navefnwl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qeupixib.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfknrpzw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2itbqziqe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlqhflp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djtewotz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhtkxcl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdfhwcv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaztnct.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsjqcna.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapjrpqo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicwxtzo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qneqjiaq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqifield.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsdmmzf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuqryyx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2orrjkqto.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojriwjmc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhdtxly.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnotxpzl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2piazaiou.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcafodmu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2brinnvoa.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbjfgjy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vklyjahq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2utyojiit.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvnwdcs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgvwcsg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yibueqhy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjsaxad.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuuqxxl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fadgiibp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpwqatb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2beasquqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doqogdqv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxkomom.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpcvauz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kvghcdkw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuzkpnd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hywyoill.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqbfrsp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kjernyzg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxjpijz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bzydyunf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdbiooi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbraraw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2efrqwhrv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkrgesw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlbfkeg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2crmdajos.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsvcnhx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiiruxk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdhlafn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jynmwiqc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iiewenca.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwlyiwc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfkgfjp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vmidymiu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftycfkx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2apiwpegj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyopusbw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlbliys.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbrdtnk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2epldhpek.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2agsfkurj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwpyxia.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwoyymk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sapmgbbp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjtbmts.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dkipxdru.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2buwniojv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2epxalxcf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpnllhl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iettvvpf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpvqtke.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2omrhgydg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2delnbbxo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwsxqpy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2utujkfqy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvuzloq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpjtypf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqqafhi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvkzqfu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2utorzsey.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tynlywug.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrsiapc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2robsimtl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcwycun.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vspmuygp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gscwglmg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hlggrdpi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpytzwq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hiquwajw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfssadq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nivdnpcc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkojdrz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wgivrwiy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcyzlgf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2scpmtfgo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zytreefr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2imdmivda.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhenpldf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlfpczx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbmivwm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2udplflhb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxemiwpt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2arkmhzku.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzhntot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmmznyl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzzphwx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2blopglcg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsdiwwt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2atajtaez.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gcribobd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwqzblg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rykcndfe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfuflze.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2exsrbxrx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlncbbnf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrxinim.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwenxvh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycojfihn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqqzlvv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvggdnwe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvqtovc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uuadjzec.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hhopydvg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfdlhoq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2glovnjuh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2odjwaoco.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hanqxmsx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuukgtc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxcksnb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmqnjhg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnprlkn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdlotsn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkigabbn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xolaywqt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzaanoq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2caknechs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2czodsveu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjjvojo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqmhtxe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbqqivp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoxfxqy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stewampj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdyacft.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgvqpbc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiurxzs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hacvyqmt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoavyzk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2llpzsssn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqwuuby.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xtacwhgj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlzgfis.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrbkqoi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2whzxqnxd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2illoqzna.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbqhimv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hwogsqnk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmilxiug.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmshjgnc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ievaqwra.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzckniq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cficqtau.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dqesdfun.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfnhrds.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hksirpez.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfxaimc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzazukdy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjqwuro.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bijrgslm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfeubzh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2igktmenv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdyohxn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iohhkisu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxbtevu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtvvqjk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgxlrwr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2frbtsauv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2orvzwsdd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oaszuhia.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ialykqao.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ouksruvg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbotbtv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2snccujmx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlznqss.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyxxnbk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2omqewoij.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qumbhwly.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaullsp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lctbtrek.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdijafs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2elzdtsni.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkbsann.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iuypkcif.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhwounp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2clmqmzlq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljippnyw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyoflxu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcgixxp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcbpdng.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwklplr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2chziepst.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmklpok.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hicndlpa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2meqvssxx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdzsrkf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rynfntts.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxpavtw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpudbbs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kofrfwxv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjrocit.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaqjnbn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xadtpdvq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjmzcop.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwlgztk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpfiqqz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oazdseoi.html


<!-- 参考信息 -->