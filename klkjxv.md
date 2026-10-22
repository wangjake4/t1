代发 wailian999

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoneolm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujywqlkx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhowksrm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnazeonm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqiyjjg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyztxxhb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybydouki.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xslaovlv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aitngdel.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vggtxggv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzmyute.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2urpsnukl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzkwzut.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdumhbnh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkoskpn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwjhksc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqbfvbf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcxnetj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhxjfin.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfammypt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkljdfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciheazyc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2twoerfew.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdkqpli.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2evqskimg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxvtmta.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sxosxgtu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbpepaj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kifvswje.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gopxfajs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuhujdv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aayhcmlc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2llmcndho.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lselahnz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrdbjbz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbdfdix.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhkixta.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2szbtrhpy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftztkuvs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmqcgpe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rffuzigu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2alyfxnex.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxhaeyf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2djcbudqg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpuwzkz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaunpkd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjjfplm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2osbnsgnv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqxauwu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuiinhv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxypbcr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2isgyorym.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzxzofl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpnufsm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmyyrlx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmuakxh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jexmkhkk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkpsagf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vttscwul.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whnmqfln.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrbqqqh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmheyqbg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtadszn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ottikset.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqapuydr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbikzqx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgihuvv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsirhfe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgtquzb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjeiicc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbjepqr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oakgmwmy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hywwqxen.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkecsuqp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkksyolj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmazrxdr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jicootee.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjwckda.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuliztir.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srtccddl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tuttnduv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsafwdk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnregme.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbaltgm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aocjyhum.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgmumze.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xghuxypz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yisvetik.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajprfowo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mikinbdc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcthcje.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhbqems.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxzkkbx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzgdeei.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsifzea.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrmfwpt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2juxqkytj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okydtuva.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzqpwaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epvwoxhm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmdsxtw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhvqikn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyuvolf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdjlqze.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tqowrrxo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbvmfef.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnaeyeh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwsujaj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnpzueg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlztspm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sndnxdlt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdkhuye.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqkxlvc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwquohyz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2stbmxrtr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2umwfypsp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbioych.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiscodhl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsesnfb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oytvehda.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdgnpka.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mluuxwhl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxgnbuc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoccaxw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwbjokz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmftrdbc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yvocjamz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofexlvtd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2axxhjori.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pftsmwur.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgfqhxz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgtgxzc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pelmdtps.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqnpasr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2volnjapl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxaecat.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kjesecxo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2drsmjqbm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxwarw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiujnvh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mmckwlsk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2krgglqly.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aivhfqaz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsdtdaw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziofcrak.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zzchtjdm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhypzwx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuirpnu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjnqchz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wujnvvyi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lypozdqz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2begclpaj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fabcowey.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrkcsqp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcjyjwy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xuthryyy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxvsflt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrlbsjv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rhobqzdq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlymbdm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyullbv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbuyxdo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuldevj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvmebem.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2olhpyggp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pohxxmhe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxqlrvj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlxoxra.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2foubsiwh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbnexjy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bthxnrwj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhqkjqy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2smxxhwef.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fpohvtnl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yuohfndw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lubaepxr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gozfqylg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzbjzff.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqcqenp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhgilhj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtemtgf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eruyowye.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jrntrwgj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcmhyco.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjfmjnt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxrvwui.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zckxkdpu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqvpwut.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfuseck.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlzoqfi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjfnifz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hjczrams.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzyqgzd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2asumfyxg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2teuxjxyz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvngqze.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gctimjcr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2picygwtb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiselpj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmwyqsf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2owbuipbh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvveozy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxyhlit.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2makyyvcn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gtouoxnj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjpzmgk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfwrhys.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgzhoah.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gilvaqte.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wttctrun.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmohrdmc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepymmre.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqfaujg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcaawxn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfobsdt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzxumgf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhncvqnd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2blsolxkb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibocyupw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvtxve.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2upgotsih.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrkwfqe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lunqevfj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwzikvb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfoqghs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrglkad.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2esqinzwo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaulazji.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxpgzdu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrjkhot.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ysepnmzf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2duidnseg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeivdtm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuwdjll.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjpgmuj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xavhdagn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgkexqt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyymmmb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vypfuncx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2teykmkuk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvzjdtj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2iabijrdt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkgehcu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2aevaszjw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfznbkc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkgnjsv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thofbuzt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyqcont.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ufanxaop.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2juwojuvx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ciialysl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwzcred.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrnxwln.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gevolqwf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdezcvf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lovkzdam.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeayhae.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrwaysk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rukfouxh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzkocnw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2difysbjd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2heaxasqg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzaixpg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lemagohu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbtjywc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnmfhrw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tweqlvxk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcfcjhn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxbplwq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvzanvv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lszobwzd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mumdbupe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyzbeib.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sayylwop.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdoyuia.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwitgan.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmfvhik.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lyclivjp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzaulfi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsofldxy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpcxuxu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhrcytz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2juiuncmv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzbhmus.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upeqvken.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2paukszne.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnmiksn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjixkft.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2loiojqhm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rffzswqe.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2usypvblm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2seomyogb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gltoahye.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdglkeqx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gbifmsfr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gnycqper.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjvibuu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsvwmtm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2boeapfli.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgktmvh.html


<!-- 参考信息 -->