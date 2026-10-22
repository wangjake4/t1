代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sffkmlne.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqjtvqc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kohqvsff.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvspyrk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2giqjdjtf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hujdmtlc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzivrqhw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ummthbkg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqrhjnp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgctkhc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhqxqlh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuzdodz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nzemjanj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkypmjan.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2powfdset.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2owyfhizk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgypocq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkpgluk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkotpvke.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fenyhqtg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmiunby.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiwsgnl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnwhoto.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhxtkhk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rymehnfm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2urkdypva.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkpfxln.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxavlyr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lujuxxbp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiutkrcq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hjigvffn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcisnxu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzbpxkb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nybnbzbg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cncrlbch.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2usqxvqxg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjrsjud.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2blwoosit.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyqsdkn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshfdbmo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bcihvjqt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbogtlj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2unevgwqm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fspryfze.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzdxckn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2snzhrdra.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2feitnhmo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhqssgc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgutufl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2izxnxwav.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eolmnvbq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kaopiiia.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwxzxpy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwpovdn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hiellbvi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlzqziu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlqwxoe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cygypqvu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nesixkpm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyizhvs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2odrrikqh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyalhqx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2okaclzyt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkznbsg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fxppuopq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xntyorpf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2slmgzdeu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2abjuhwzn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axyzrupe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2grtjozwl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwdsnep.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oszlbpsu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jixeorjq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtysldda.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcckaxwk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phndwikg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnjsvqy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyghajs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzilwmg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eywexlxo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrvgpnr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnphrso.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmevdlp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lklqmlkl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrylmqd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqseaaga.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpycijs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpstlql.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbexcayf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkmcziz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iilpbvpl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyizpgk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cumzctly.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsduouf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcqqzfv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhohgt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcunryxb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oqccjuzq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoymcay.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwznbvpx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqxybxz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ucagrtbu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrwvnni.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcwbitq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2znhrglby.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2udgkyzhw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxpiecw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkygdsk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2acywercv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euaywobr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpixmclj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbdnnuf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fblxntxt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lnylyxjs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2npvxztdz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyyyxmp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrcrjso.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyesmotm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ainsmkic.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uceksmmw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqrgpmm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fczdcukl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2acianscl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2arfawdsw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhnpgxl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nilplnrn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2erebppnk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmwepru.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbaldum.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2imkfsuov.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrxqcke.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2epgjjupj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2feakehdd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blamifcb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwmwnmx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpyzoab.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ponopmsi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqazaotv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sycnjday.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihrsvcn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdwzymd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oytlsiyj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2otyxayeq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2znjqgrmh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2clraszlu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyewsbfr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cewztcjx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuvjzgr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvktstx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2agorktbe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2abbgpkmr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhbnvse.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2egjyzuqs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmdndgz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mviovrux.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxverehb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgqlyvw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbpczml.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcsmzsz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwdkegh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2njquqtek.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwuvxvj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmtdghy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vijijgwf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2puvlvzmo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcsqufo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yewpovfh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2amgsyhcv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdavxru.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmfmxvx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyiwflf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qojedflu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xtulzucu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeckeoz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltggiegu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dojcsnon.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2imekkqwj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2agcacqgc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvigpul.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kybexsnq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaxchfk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lotlkxhc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nidldntj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbmefop.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gqatylbf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfurtui.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lheevmla.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lysepfxi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmuamic.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrirfxp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcicdro.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqxhqcj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwmnrwl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2supxwsih.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2daxzrlwb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tahnfubh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fztnuppa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2acsvwiyh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnurxdz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiotqerz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dviskpss.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddenssnl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvbjlhg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lufzzpum.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2noqxujte.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuifqne.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvfulav.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfplbplk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzgmmjs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cppqqnlr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xymryhym.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eohuzpvg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gynjdxgh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribujqqs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwdkhrr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iydlxrvm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhpvcqa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxzdbfe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xejqkaaa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwybwqa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdiihsj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvbwkel.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2igklbtah.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohnmbri.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsxpwcu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlpxqgp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwcaryv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzdhvdp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsbfyjm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjkilcu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uiruloze.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpervlcq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vutrycro.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aprusxeh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zewyytwq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2etcawgja.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnizvfm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgptxxbh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2txsgpprg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjlqidf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lidcsovd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcicswdf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcblzlf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcorkre.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nncfkwpg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtigekg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hggrzyrz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbobsjs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxyijtt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zajsyfwm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxydzhgq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2oisaekbj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyshsma.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaptqfx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzzmolz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbdhwwk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsvxmki.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxwvyj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udandpfa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2skfkdusa.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nyanuyny.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xgchtmgb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxstonl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nawqmomv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrihjx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xihnbiel.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yutkxxdr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmiyxbc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sgehjlit.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmnftds.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtzrpfp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvdpdfp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfmpkes.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcgetdr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxgdalu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iadckzjx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyfoywe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzgqywh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfdvhac.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrepxee.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzqoynn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsriguj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmyjcaf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxrolhd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmutvims.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kztahhyi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrcisnz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpttvxu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfzpsgh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcptysbd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iimedttq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2issoqzhy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2neiwrigv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsjldmg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lltejobs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcarmps.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjyljsa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoaxfzz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmbcjde.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmqchwy.html


<!-- 参考信息 -->