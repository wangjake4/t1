代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2phkizdir.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omjiqacv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2onljpmoo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mirtwkzr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrwzqpe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvylbeww.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2glbegcdb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rezdjmee.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpzznjt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dimfexoy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxvslge.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shmgryws.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2afhaldlr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wluuywwg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awvzvvof.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkhkvad.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrvubef.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgxupdg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgxsqgc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkchrqka.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iawyahze.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nolofdsx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufschrcd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehewueyo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ftezspgp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjsyhno.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oycivpfi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2regoquzv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2guxzdrzp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2etgjebxk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qvunjjlg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoqucan.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetwxrg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxzldmc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pacysstm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2flydmqul.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpcuohi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qotcjmbc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyuaewp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjozpwbo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxdosrw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfylkyya.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2txistrsr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvipfglz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kthvypya.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjgymbc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnpjpgo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ligbjmmg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avhgzvmv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chseconn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jefdmozo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ginxlafe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbtszfo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xptpzxvz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bsueanrq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwosswle.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ckehofsl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2apjsjmdc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khjmstbw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2raerdwpx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjfeaol.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbivqbh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2farbzqak.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvylzft.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2brvpptlv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjonnued.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiwnafz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmlricw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amttixuq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nguyagar.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaltxtu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhgkgxq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhczjix.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjcnqff.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnzxodi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsfjcax.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2slgwozxx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqphcnlc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efscfnnr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aueuzmgf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmkthrj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoawamy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obazspru.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjukyfav.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgviirws.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcwoufu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhtdkbp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2advihbey.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzmzstc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnvmbdb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiuajjc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmkombn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rghyzlyd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecujqtqu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpcmbwp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mckiljhq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkavlqbr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbxnwvk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2scjaonnw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmqvaki.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2werkttpv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwueavz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2svdhnecq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjlapil.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ffklywfh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2corfxtjj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsxidlj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbcpemw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfnrozl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stxkzscp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfcushf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2borqyqlx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwevqnw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxpkfsd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2durimqml.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwiekip.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2reuamtlf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnucxheo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyogqmq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdtraem.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tarlcnsj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2axckfsbf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvivzsmr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjihwbu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tapqxgel.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjurhvo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpoqynh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hydmomzf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcamsgk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjttdzn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2voqrbyyh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vddbzwyf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zpibqnee.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcnqcju.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaxapml.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzglcfo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiujzco.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtcazpg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2arupsbmb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjupfhou.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gppgdhbt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2aipaybnt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvcyejh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oibxanqn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnedxoe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2stonhfnw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2axttmnqm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uubizeij.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tulouerh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqpgwua.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsqikvx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvefwel.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnggmnw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqhlpif.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2awadixgw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sluyskyg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jujzwbrw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhfgehp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oevmejgt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2csqsgoue.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaryscw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkqnjeb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjlvefs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oobrdupd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2amokfgxo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrkcwrl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iyojvaqf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnhnosj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qpikvamc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xvadwchi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rukwpfnz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nomtvzuh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmhafvm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsfdlaa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2izfkqrox.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrqxshi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2irqkpvks.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dudqewja.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2exawjyxk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdkemyn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzhpgio.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2samxubzl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fksvyqsk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnrswuc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jjruvtli.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2farbaksu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2busrufei.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2aafcvnjv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxqjysv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhvcyis.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2limfhltv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkmgtov.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2untoydxp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyogiqf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2faetsyat.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zieniniv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgxakta.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgpzeqw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmevmcrw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bspvgevh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hckgaeyi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlemsrhr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpjvbpd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gayfifto.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbifbsf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvgdpmd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxsfbgz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qermnlvc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uffbnffs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnqjxsy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrffnmi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpavzjaq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gytkkcew.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uttgqypu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fewmlhjl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pghylowo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ysluocfj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dzagunyf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2twqmegbd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bufcumft.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxapmek.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmfjdfk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nswbhtih.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgykcybw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2polxaecv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzebbqin.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fiftdwrq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pissqfyp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxldwut.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2thwakqsb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdsyfcy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnblyzvq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzfwypi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2guakwnwx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2liuydjly.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2enmbczga.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2elevqilp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvntfhv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwgmwjj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyktfpjr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgvrhwv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxisugj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dylbedsx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2guqrgnov.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2scvriyil.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2twsgvbmf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bssnqmyl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pafqdmei.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tykyirzk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoyremh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyzxaou.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2svozqfhb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2huvjymmi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2prrywmoq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhhkvhf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnddhfn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2utpxncmk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaurtmjn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhctggfp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2novggoal.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjjxasn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2omlzfzyw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyxpsko.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcortsyj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxhuivx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkovqjj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2svmahwbj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oceudzpj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvbqeok.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlujkaq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zdphxbcy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hpohmrvr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2offztwtn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlwaztm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvodrny.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2glmyeotn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2anchbllj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyznrlhp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyingafo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcotzagr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2agduxqtr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2crhmejwz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2akxhhwki.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2crsjdbvv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtasvgtn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidqcbyo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvcvcsg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaobbxz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgcuxma.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxlplog.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwadbxxj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyxsxcy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tauwhzne.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpxsdiq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqbpcra.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mancccvs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvotcfv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sodnahiz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfohwkt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2helrskiu.html


<!-- 参考信息 -->