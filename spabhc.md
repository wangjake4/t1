代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ahidlafg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyxavge.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cifdusic.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xybjzsma.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akypcifl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvfadyl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqykccy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnzysuj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxavwcq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvitxpw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aoetfdqo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhynsntz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwzmrdz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcytuya.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyvjdro.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrrrvws.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kganofzb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfizabc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvvvjnj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzyehjp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqqmmgx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcjcudb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jipwontz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cispdzoo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlxjjem.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vazlxtap.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rweaxdem.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfcvvbf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoahkvl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2chdwkzgi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgysfyh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqunnggi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcentlj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmvuwlr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbghork.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ualoqoqv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vgouedin.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qezqlvzo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ycngwljs.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrdrljj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2axtxnykh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmlklnl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eaenvtjr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuiibwm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfgjqkz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsmhddd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hwruokyi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsmsncf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjdrazf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgalpoqa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxtrozw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvscntua.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqykdlmw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eisbgdrc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2apbospeb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjeovlr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoaagqa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2juglobnr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afgrhvfs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2giidlvrx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxwxwky.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzicexg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vskqaxjh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2puimbbom.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yjasbbhy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiobnred.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzaexiq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2efpfaxcu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxlxrzk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxpwkfz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iynhqtkm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvaydbe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrdfvqs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2puwetvub.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuiihjf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwbyswc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtpdnly.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vinylork.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xlczjywn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owdwosib.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xeauopoq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwbfiks.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iamcdzmo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfqpzzf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pijitlqq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lztvdvis.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euactjch.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvknofsq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmkyxxm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qshsyagk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2irtleucy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqryoyy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnvpqdd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2igckqihk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2usrwfobn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mrafjekr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjkmfsw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeklojo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmdeoqx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvgnluk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvdvsqc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcmmllb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfzscxq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsdywyq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoaegup.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgmcnlk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoljsmti.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wfttsgcn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjarkofx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pufqaygk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qidqwtnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoekwlq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fabiktqj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2agqqelpc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhdpbgf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aghoelcy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2etoujgjv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxflncc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nevixwes.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aswsrqqg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ephquqfu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyssfycs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsogshl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfqhrxn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tntlkzmp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzmmyuu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzlcdtf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzeopyk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbztkib.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrxmvnd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2erbbgngo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpftzvxh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sbozlwof.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfktlqy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2idxxgumb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owfeboyj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cglyvyyd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbflntum.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpjxyuc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyvyogt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2boyaowzn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vautovno.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xypqneux.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxuhcnd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qefzyzls.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgjjvao.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqyowwu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2odlnenrf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mahfklao.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shzyjpzz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyhoyks.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnzmlah.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2emsknccm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pokrsirv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpoexnk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2swnzotfo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvipssjr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ijchmwmn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2chbzyfli.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfcazag.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vgruufin.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmkdvqh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ohirmona.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxmyipu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqveamv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgkxsfm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2beoyyrab.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrsqqxc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2glstyfxr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qclgcxou.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2biciojbj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmkooa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gglphmbb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrsrirx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmscxvzv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgqwvpc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2egmktfpv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeifbaiv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnqijew.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqznuwzi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjsoylo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlwqyeq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsujwpc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgotrza.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvryezl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfwdfpz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hitahgfh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrwccej.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tvswccsg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvusticb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuyulfn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhivrnnc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyhhasx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjbrikl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ciejfjbs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jywaboma.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvsplfb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2weoyychd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amphsqoa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjwgtss.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuvjyqd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwjvkgm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjhyxwa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqtlpmv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvgpvuq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgetakt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2erejokwg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wulgnkzs.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bokssbhr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xynnablr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlhqloq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxiqbkr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wptwsajl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbinjhfk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlklbrz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxeewjh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jboxwqmo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpwiugp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cppmhjsb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeilfymz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xswxibcb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkszcra.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxffemne.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpdllsw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrmvuue.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrkhesf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pnocjdal.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdxxxuh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpmvtmv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvtfhwx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlmdhpb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjnvenj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdqxqec.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwrpevp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnxgqfo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2osoczjfm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkemhnio.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2teivjsqk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fajbgbao.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaynchb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbolnle.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgesrypq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eghjmquv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbmbgxb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fprbqbql.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdpbmix.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrihwzi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbrnwob.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhrfkbl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2swxbbjfi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lczvfiwr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqmtchl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlvqrbz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbnxrst.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhiiaan.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2psvtgbio.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjrrbec.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2shoubmsj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eivfwljq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkewzoc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fljvzish.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpesthz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkeayey.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2knqhoqcj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lodoabwx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcbgwab.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjrbzqz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjbqrhx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cunyphin.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2umeaazrj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dogtqity.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmslmfs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmkxiji.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2svagspwi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iaozyrxy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2odotjgdv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgeiwov.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dprjeqwq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2afeoojdp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhtztai.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfrgmim.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfvtuxn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gtijdeqm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2suesvdar.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2egvtlpcq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnijpxph.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxujcfk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2itbeavbh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mjacjqbd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajogolmh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xswoaast.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgedjcv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zyncmqry.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnaxexo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoxggtd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyoqiul.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oayuuqmk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2byqetvix.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbcnnwb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqvmstb.html


<!-- 参考信息 -->