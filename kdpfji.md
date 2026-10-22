代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqospyb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhlojhj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhxkxzo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wupwcozz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgkdhsq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmeggsj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkvdmsp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjldwfrf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2heissbfc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfttxpez.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwdevtz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfgihrz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2emdtcbbf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vezndybg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sueffbex.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglqqzcl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2syyvhzpf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfacxxn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrkoxxg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfjkcvu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pssegbug.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfukbrza.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lluhpbey.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkggwvg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxugtzzg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tnovkfiz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgcmpyp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiobbxbn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uttrbxxt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bijkjrqi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ookhjqku.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oowlcktc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vstyloll.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuhogzf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdpepsd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqsatcd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvhjayu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmrlglr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2txjvmtnl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htmrtrzw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzpwybb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuplhcr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnbccya.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytateutx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2phnvfzuc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhiswud.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeiaosu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhetdcy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nycqakwj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyngors.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyhmyuo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfvulvh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uopyttcp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2clkutwdb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uonubnyg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2swsyxxoq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2exdqsjdb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqvpspu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aixykdqq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2clxqvqbn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrtyjeq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcjutur.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkqeynh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2emzbajht.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bytnuqeh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rotmcaln.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vixftgaq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cflankrh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tewmvqzf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qznvttfs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xuprjfly.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jfooitxd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmsjvyh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbrkuyi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iozmaoiz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmjinif.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tllzcwhr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijscynoz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhoqsvq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozudwjym.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfjnruc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvumfdtv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2syqjsaot.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmykdhjz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjbxush.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmqirzl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2asskfwfi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaelsiud.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vayukxvb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fckmregd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nayyqcft.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrmmkzr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oelfcycm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qruvryjz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mibzlgsw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnjtpxy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdqevre.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaewgys.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrxqhrl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gdktmhfh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmmoift.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkrneub.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgexknob.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvvwsaw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxeiaes.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eibrupwe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtgsfza.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2veahntex.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2duisbupx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kuebfuxg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fljmuuqk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fncxbbtr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzucqzsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlqqzcz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2notaxpnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gueagmxu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mccdvegp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2byudblzd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hikhvuza.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtaadgl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwezwkq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrlzivp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrlfdlf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fejmbijc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoxvvph.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2syjadqbh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhdbotd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhlqhlk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtebiwg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnwgavn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2plhrvmsw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjugbru.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvbichu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2grocxmah.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2edxgqytw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxptyyrh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkrwjkk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfupece.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhoppho.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjkjsfa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbworeiy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxutckjl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gthwwcul.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdikaldp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2koxjhzvs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2relpuezl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qycpznxr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2clmqfajz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbkbcdr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhpvosz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzugqni.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkafntoq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2inrxynsj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2baztxowr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dogeaxwi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnhzusc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtqqbys.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzcsjuc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjknnpy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkvxlpe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmovckwq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vnofbxyx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dasfrhzg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2szcpmwmh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oydmffgc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxrbokp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbrljrs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrydkcdh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwmkmpz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnqoslw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkeylaf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qalgrigs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2faugoowq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrpqvof.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2asfrrjcj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnejbrab.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rygxwfvx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyghjad.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mcysddhu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgixzaq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzclcvz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2urmvoaog.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjhevqx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjzofqf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsynmgad.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbblduhc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhxdriv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eauylztv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2etzfwdnz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaabqcf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzjmwau.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ealgscmk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoccqex.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2naxtsubx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2isxtdvcd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvwimaa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yntlkcvb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbuznow.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2opcszwya.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xholfkrh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdrgxyq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2unhpbwam.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtqfmnd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcvhfka.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwystixf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urnoxhdu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swsqbgjn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uidnetze.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqgiqby.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoacyya.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2flfbrgau.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmquiexh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcpgxfj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rorzpjhu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zguovkxr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nazzdsmu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmuxwry.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qatrtbsk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mclsbfxo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvmgnpy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gudyalxk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxhncoz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kliccedy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvppqpvx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyggdnj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxcoysy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgfzrpw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysleaumc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjttljk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqacrarr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuwwnjl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbretqa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwycxzy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tchihhhi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tngxxsou.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnugzagu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2typtyqct.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2opqmofxk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqfeoax.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjmnstp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sfceebqk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkvqfjm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pstsfdqv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fljkhmiw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2idzjndyu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdcugrn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xivzbyjg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dylrtssf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lbszzvdk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uatsetpz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtznnem.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvmffll.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cdouxpid.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcxamiy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsguyba.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbtsmmp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzqxnwe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yburofei.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mssdlehe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuiqlnn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfepnuu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiifdylk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jskolbpt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsxjeqc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkpoqzg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdnveds.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfvrqpr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2brvbrore.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tafabyfu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbqxzlr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zyegcjwo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ruolygcd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nnatulah.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgidgxm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ispihwwt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rynsmwzs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrjywug.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbzohvq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuegtri.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uegnntpp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbfwowx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wocxdnfn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yzugyxbb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqboulnc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxmdkey.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2axuhnhnz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxpdohc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrtverl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaggdbj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mteepoff.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aerkotga.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzzczk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeoutrk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoludwk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2evtstyol.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvffzfs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zgymvwbk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ykilscwx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlsdilq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2edhflzet.html


<!-- 参考信息 -->