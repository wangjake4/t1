代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsjuuwc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2keifnsuf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qmphyuch.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdddxdx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opcwteop.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tntjmaay.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eehqwitn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrdtdym.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wamreetk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrndlvzs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqlfbzx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyoqkwz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pygtrbfv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdlrzed.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwdekpv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabuxbtw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyomxdr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yffqbser.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qogkremq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvbvtyv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsebbir.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrxmdkw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvakhfef.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrshmzy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbtokcc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2walqesmi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2biirjnxz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nszoqbbg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzsimfg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoifeibm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvkdzlk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhfeyzf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uadvyusk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qshzwgiv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lilalydx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gipwucua.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2esucrixw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sngorfvr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dkswciez.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwxfxzb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tkppfgft.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cezicbob.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mycxkoug.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbiohpu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2icgwzshl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aedtufrj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bbebfzuu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2imlojxxm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqqdhav.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhlxjls.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsjarfj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2plikghrs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sitrpmqj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2blmizdnf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqphknpy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kynuitsa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2izvvxzau.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbbkmzx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qayfnpym.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2socuyuit.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmxipfr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2alqdwwcc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2afwmgeal.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgufeqhw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlsiphl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dylaxdrx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iluekbtj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xgesaheq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mchzuzpk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvrbbwl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inimvppg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzuixbz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wihugpxs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xexplezd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lduezjgd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stnjoaqh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqqcyjp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcywshs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpuadcp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gelovjhr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2clyevqzp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsotetmp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjskalfn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvmcukv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzypbgqb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqglpyo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgeixno.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwcogsy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teixubvs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrstzfjc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwpkhjm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtuxalx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smbihxwr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnltgby.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtlunte.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlrmgnh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2affdvgpj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vslajpcc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chbskgjd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vimvkvbm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukckyamg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sdieprbu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2egklxonx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvznczn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvebmxw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2olnwotmu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzftnmz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2witfznfs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2civssxfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkybqud.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnypyto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbytlqm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2veiuzmqk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2txqqfcmd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqrpspv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tontmkfb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iakmfvmx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvfagjn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqlwmfg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jrosmuzk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fniamfeb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdiggaa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2scgsoezi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmkckzd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgktvubn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjeisph.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zesscxes.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2prdcerkp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oozqixhl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rimfcvbp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrshuzp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrnnvxh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hqflwodo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dogrkudu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jymhovar.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygokoyia.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2reuwcnqu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqiwtjf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwierxji.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qysrvcbc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgmziel.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpaohlw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eugnhxch.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2muezjkiq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pojhkquu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmnhloh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kirnwuoq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxvpmnf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rphggpjf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnbhcll.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2alyerroz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2twkfmjug.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2aosnekog.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrkrtvz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrhxone.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnawjvxq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwxbljf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2glmeduzb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adxmauwi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrnftob.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcenyqu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2abxfyobd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgncatw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfnyxrk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2blzxhgff.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2naqziwyz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzmcytz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbfiyci.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyhupxp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2unfasose.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fbldomca.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdlvvjr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiwwhbt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wixickjt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oviytkvv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zhknhotr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lufbzpdp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzxxylv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xcymiejt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvbzrfb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcisvzje.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiadtjp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjydpbzn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2swxrtuet.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwayhok.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cynjresz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iigyhmhg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2poqgggbx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cftcrkfo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyffrzuu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgdxnaj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrxrcnp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xfegplvk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoyqjce.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2knlhjfjk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfaimlu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2inzxgfhl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qygyohpe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lptjawxh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdjbvu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yurvfdwa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arwcfpit.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cudydyzj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oplczqox.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2velhdfjk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqzpsfb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrhihd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhyrsra.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsmufne.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2aadtialv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wccndqrg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cumnzgpd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2stvfynro.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2drmrvrki.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxpnbas.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2afgolvet.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2usywcijd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpobpyx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqwlxeo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgxcnyj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oudzrxlj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2keyoecae.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nobpanua.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vazbsbtb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtzyyxg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eddjfkln.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqiyckh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzlilxm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdthifl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jacpqokl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ommjzcpt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybokvizl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yqraurpo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gejhwkzi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fnedtrsa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wihbbghn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qbadwhrk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqmkvfa.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odplkvfy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsezkqa.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tnelsjcz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gluwcbjv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxgdty.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sviqrkfo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxgzfgn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfowkenb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vysfsczn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvilmija.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hoazifxm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcymrsk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlulheio.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fgafpowv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcknhcq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqabgqj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqyqlhl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiotycc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yowgbrdn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hennuyqt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afklghui.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2suvjoemc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fsynbtkl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2byxgqjsu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ootrhwhq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pajfcfps.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jndhpyhs.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2abafneuc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdxumfn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mizskxgc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzndpqk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzmwkms.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gymhsvab.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrvmkuw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunzxwp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2eddndfgt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2raejhybf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbshjlpu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yobngblz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcamjgv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjjvjgc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpdoocl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtijsul.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2alfejhfk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpwtqjc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhkqegj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pcasmvcr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdckgnjr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtrgecl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxxahcz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xdblxsvw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtomswk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymplrsfi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfztmze.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2shvevmmb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrantcq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsqjhpv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2euaumooi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqhfxrz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2agyyzxqa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaxxeef.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsszahf.html


<!-- 参考信息 -->