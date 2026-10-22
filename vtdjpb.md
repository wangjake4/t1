代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cndjhlbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2seqmulxj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zomkgfdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnrwsrz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpunogkm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrdrvdm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmrsczf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnahbtq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fzggsdir.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwhunix.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfthstt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lluostsc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2izmqcsyh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfvytmu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujzapf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoijjncb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtircksz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjyhrhm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2svcuayrd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnstrujl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgpnxwu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwwpewk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uywotpvd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhgdyvv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iscxeaqw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2idpldvyr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhlxqhb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlazksi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfonivb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgeexbs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bifbcsvv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyymloxm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfyoczy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkimjbm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiisdjf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aozcmplh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpwhbbn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cpivylwj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2brovqeov.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkihmcap.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqeozxu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cinuovyl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aloidvfx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dinlqszw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fytuwjsp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqxtjzj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2knshdlqu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhztzzd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyelvpq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmshothw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2heyyzgqe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqgonte.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxpnvdr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmigrqgc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ymznxgkm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxrrblm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhcwmgx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehffqtjv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yceroodf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqftqjv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjprmvg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfowjsj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuxlpdl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgksqjah.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njazktqi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwqnxvt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2odrmvlpf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnwaczr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2focjjftd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2unvppqgg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjqinii.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqrktch.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlqthdy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2indqlsjo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvewuhp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2irarwcjt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkxsgoa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2asvkheof.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpiahsi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrtjgqc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2latooolk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wchdtwjm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2siotamro.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2himllimh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlopgkay.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wejcavnh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdmpgcl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2srfrqkho.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2slabvjqx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckemspiq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvdmmya.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiynbzdd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyoavgz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrjghnf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xalnixuw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viwkhqro.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dnegwvrb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrnludw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jopnsfdv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrqbguc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sudwmsdz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeedmzk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnjmkfk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rteabkly.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkigkgr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvkiptn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2flhfynqk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2butawokq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olkpogrl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlshtbf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjcoaim.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwytehi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuroboey.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzzebed.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rspkrjks.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pwueucjv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtmvhih.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yegbqsvk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtnzwtk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ahampbgc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qklwgbog.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaasmyj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xphfgyel.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgxgykm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wueclelz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbnideh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovloafqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmkywbd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdgfclw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2roxpftqo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbugrho.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgwfjlf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjccntm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbztwrv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlfajqu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmoubjb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxberka.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvymlue.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwntyvne.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iponnxne.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bogniahl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaucobg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2otuxccuj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnclkfk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mcewoqxl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrlfjhd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lntqlnvz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlqzohw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azviokqu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrkngql.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsirjqw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smxfpmfz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxgijdb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wllttyyk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcrmmfs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhdywah.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iivmanoy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxrvfkh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2czqltymm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmjhyol.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kifavkcr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvpgaiw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ooovagmp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnprmgmr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2otueybel.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whuncfsd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwfrrbm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtncksd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2riqcpmgg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiswlok.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bchoxsco.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvputlsa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhrujgv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoijwil.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2icjkzmpq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrffefa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2akvicghg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgdymdc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfhgpbj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pydwejet.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mtopdokf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeehxzb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mudnbavs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2phcbmvbz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2chmupjae.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fdquineb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqvsksj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrnejnq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoodmpt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2blvvcjps.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnybhyl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2snwovqah.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2azadtafk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqmyvhj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggelitda.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2exeblsco.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgghpmpl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzxynvk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvhdhpi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnztwpt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjirbor.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aufaftkf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zqczrhwa.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfmjocz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmjjwhr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2honhrfnu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfgivgz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfebegg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2niwmsfif.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zambgeqv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2confzqpt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzilioky.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsavvub.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2drpwuvoq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpqorxs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlatsnu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hydwekih.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zumlupgo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lryzvfuq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2iksmwtij.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flsjucjk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzqdmfl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnkzjgw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdopyfhl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dkctzwnk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbeiijk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2umkdxygy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdhfkid.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kkweyazn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsqqivo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mornfwow.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxgdrjc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaxzuzh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcuqswi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmjwtzv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2edkgloul.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrgrydm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2skikkvop.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rueabvpl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhywwcwz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbsfpkw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgabuptu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzjeuuq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukirrrwt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yklqjcyt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvavcvu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwevjpm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2egladimi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hquglcpi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoulztk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwjhcvk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzkesmq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoqgkfn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2scdmqfxq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rchnotkk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdukwige.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jsndrlai.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnzwryu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uthrbqjw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuxaxmk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfgcwjd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzrxtdk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeabkev.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrgwazc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeiaqju.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxneheuu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wyezzuqs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2twizkbmp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrptsnh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfircumo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2setjtmwm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmcnahh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlmlntg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbxzyvg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpslaabw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtbbyst.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtowxhj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsbewgw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvlzphw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2guvxfddj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qascskot.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xowvraxr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ymillkus.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2baxjikji.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2abguceju.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcmqtqh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfhlhg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcqjafy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrioejm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qprjujnm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hijwlkxs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtuzgmq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wentfvsm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhcwdmh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nopramfc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxecaygq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2endesyvd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xzowdzuj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdmysmz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2seiibyse.html


<!-- 参考信息 -->