代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fahcnicb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nblsphwn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2btupezod.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzctnuy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2seyorddh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhncsgkn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2okitchkm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbhgcde.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iorhervj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oavcqoir.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnwjxnf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dstnucii.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2topcxjnz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzcywwk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpmjxxe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlrhblg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmagwqn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pumfbzhs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jhomltbz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhuegjy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ehehgqzd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzepqvd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzdaglp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2flrxmlmr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kccqmsnq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxtwune.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaleqca.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpluril.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cayiofxs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvzvjhv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwnfasl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymraxls.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxhzwdp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyugrvzx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brovigwo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpqredj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhfaeyj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2phbptiit.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2apjrvqwr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnglxlk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hatqslbe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tarcmebd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vxofibcx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tauhsxpt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsswosw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgyihcz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibswsfjl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2izzwgzxb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcurzve.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoyknwx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvsmkkg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaezneef.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jythhujr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fykkjzis.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnvxqxz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iamowcog.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aakhqpla.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eyktxwfz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2amkxputq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrvucka.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiafxeo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axrhemej.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnavknn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2snzxyyuq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkczahf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2frefqehl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2khelhtws.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tafslbkm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2istbkzsx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzzwhwb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkqexmu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mpamqhyk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etohkstm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbudxunc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2czpzyxkk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdnllax.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wueaqbwg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyhlqdz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brqxlvpz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frajhcjm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxufrsux.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqxoxbb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fynrhrbj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnjncqj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyxpnab.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zipqjlad.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huqmivao.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihntaivq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvwpshf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxemogqg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjzvdqx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwsuxgm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqymzet.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgenpme.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzijgtcr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdrtmqv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hitqcrin.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2szkwrsxo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfthvbfn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lejjlxrs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxyynuo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ubutmwoj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsdmmvv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuqklkn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyhodpm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vibiccwy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpozrqbg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzuldsw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmitdmn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2srbicbxh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mciamrci.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2odespvgy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvfotpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fipfdhkv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkorfwcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2waoemdmk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2phxjexwo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2szctosee.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjsvvje.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwnwoio.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsqwqvf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2etdufeye.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2exfhvrqq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2twpyzyfd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtbemmj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtjhtaf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kwukkyve.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uesxtbfg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zufvmcwz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzeyxij.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfrlckh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnltsox.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoxqxgj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmyspst.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2faoyjmxl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgzugvh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmutzg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrluhoja.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kibwajwf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmffkgrp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwypuhca.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpajpsfu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyttmzhd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ataffwma.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuatvuq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2llbjmouu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqrojfq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmzuxrx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdxvkva.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqqfsnj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqmdfyn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtnafrl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qtucorru.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawdmwcx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pgstrmrm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dylyjgyu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zesmumqj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dglsrhev.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sifzxlba.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnupaqkb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmxcthu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqhizpk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiogdrf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoubszo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hswtzkus.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlozgbwg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvnomkd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukltwdxl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jididkjc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2upckhrdj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuyysgi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrdyhbd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzwfxfu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvfvmbd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvgwtwl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gshpvtiw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwhvjku.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzqgpiu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hiefrcpv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2amtidymi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uyilgfuq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzopdqrr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqqnjea.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyoycxs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtduzmi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yibaimnz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmkrbxi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxidjrx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zvswmrwu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfnzows.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2loetcfys.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrtohcb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pstfkulm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vihaqrau.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwgfreu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcgbrav.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdbuody.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ppckxhem.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2axefvuhq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlkgqxs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjnrpct.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wujsratv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqcjmqq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcozjowt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npxlkyeb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avwkgglb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djykpncb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vezppjeq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvgdogi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gghlggjf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsomjzj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsbiyrg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmfvcal.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mriygtsi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdshypa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkusurzy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oqomstqs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2atyilera.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vamudcxi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2phabigzq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2otewicmb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsojkiht.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmgjmie.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nndcukft.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbxcdyg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmvhwyk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xszhexcm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaubqvc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrdiqno.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtsnqps.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpisugv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzjlipa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjcbkxx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qidtjzit.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ioujkfno.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsmqmwc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oewzkigq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2siroeopb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkymrls.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjtacfk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxarcso.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyjcfkp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqttpfc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmotqys.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2waldqxrw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsixuvye.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvaoyec.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxsnlvw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcehxph.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujusyndt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlyaffg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yobnulzr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbijwpg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2edwkvauu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyqcqkq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzcvnpb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtrupsx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhhcjii.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2frxwoxfr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2libqbsau.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqmvzsh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpatkyvd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqanzqg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyvztud.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2exmfxhgm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vupvewhu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2acmifiqk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2febebcts.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oajddaoh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nadcalui.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2optcezqk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hubsrhws.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iggeahqn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eutkkiqs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dfenxlpb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xftdaikq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgaczsy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjootw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjstzyt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdnaaty.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwaawvj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwizzthl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhlcxvv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hifiefth.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmasvxl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2comtejoi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eycckvji.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyaltkj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhqxnsz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gukpqdmi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcnuyue.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rafvfgqs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kjihvjip.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbkytdh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2anassuup.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2picuiewi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgariwwm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtqpfvc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdltmwx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2engddhvy.html


<!-- 参考信息 -->