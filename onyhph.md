代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgwfcog.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xulwatra.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwlkcfc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaslelh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aahtihft.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrrawjc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ttypvouo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ublhxdtf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqoexhn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhyqtug.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ynavzpns.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcqgnhu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nusnuhog.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoxuuye.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2spiarqqj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2slartgxy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uydtbvgk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzfuphx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwrnein.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hstfxxac.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmnallf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqdycrd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2emmeoewo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2humstcwd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2godlbbhx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrczzkc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lieeiivs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjcdhzm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaigxqp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjvgcld.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emuuswat.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2okerhnoz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaxazev.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsnnxmq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqncecxh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxblchpy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btdlubnv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmhqhwa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2alrjmdbz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhvqiwn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2umlfpwme.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2utcwaqnp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bptmwgmj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohltmdrc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyqircw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkflfvwg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xduzwugr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esornubx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqlmcvf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjauptnk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmndqfh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsqgobg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awmqfgsw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvujdgu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeltexf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wazawlgl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcibyoxw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slnhabgh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrcwqwj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjejeiuy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrzgpxl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcccfre.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwxbihi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgxliay.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orkonlea.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jcffpevl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjdtowi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hycupaij.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dorkwffs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xipeawvu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cngvvnoc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wonwxrqg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuoikym.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jisnnpvu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzvorbw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzitwfj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dworjzbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uplywjqm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkprlkaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gozerkin.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2prmcjuyd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zsydypoz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpqojkq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfjwlth.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2skhdibjm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycojimmg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2icmkhzmh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2myxoivlg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fruinfuc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgakdsp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmzgbvj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifecgxgr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kciehnmz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2svxrorge.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzvlbve.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlipgli.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwvqkxy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqsupgi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxfuktl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rytzpdwb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsgplql.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatvdvmy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ygooyinm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2plyohfih.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2grbharja.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwltwed.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2igszovgq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2imwclgrx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtjqddx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsutoic.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zitqlekm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyykjkpr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoahmrc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouudsytw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjhhkyf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dznnvnsw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzwcpcb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhqfvtl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyyzijy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxtrhy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhdwdil.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyiimat.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcmpyym.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmfuffs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qixvyxjm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpojihw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2amstheis.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowqfqcz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgtnzke.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gavjdbrs.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hisquvqu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tntdhglr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bapjwczs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2alvbljat.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxcyido.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbsugje.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hoturhit.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uscljpkc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvwreea.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrjpmnp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jotwuzxb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2djuyezqs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuzhqoj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2clnqondn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2szkzakas.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2taklvzlw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmsxvdq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjvwthl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pygucsdb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaynjbmp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmmfxct.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2okskiqru.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2melxkjxy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uckdqwjh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oggkuove.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiwqnns.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqwiyza.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2aadsgbea.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vouzqell.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tosaevat.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlbcyni.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeqjymx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkjahzu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2byjbqmwp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnuvymf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eockhgxu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqjbdso.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2urfetgsx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrkldij.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdyipcr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxplbcox.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lmofghaf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jeizjhze.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wjozsgen.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoeypbb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwavwijn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwuytan.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvnzyfv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoiefdq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlvaujd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nhywqqvv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjjpoif.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izdhgaql.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpansai.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qohkudej.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gyghljkc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrgvsfu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sspyjnge.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2teslssvh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2doyromha.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhupcnuz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzmwvzz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqbioil.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awfygipc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2neqvfpdj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqsyvdg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2revczvbc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoncupfu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2swkksapn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2epfqenih.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sywmcsmx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fitaibtj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2utqkeutz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsagyfcv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmjnwbw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvhuxid.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkibrzq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmktavnb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqisieb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrnxffc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oeifklnd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjplphi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2whtygsdv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2faoubalj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2frqfojuz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwpxfgc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jdchpwug.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgsvsbu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwcoxrb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2llxxtzis.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxoqbtz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2axrkgbre.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvvyyyq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrbmsem.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tljwuivw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mphumebx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jityjfrm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2aprezwml.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsgnoyj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmwqsyg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlaymiq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lptulgoy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqfkfby.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhiehij.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpzuyno.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tcchdxzr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2awpelihx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bossvvpc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjeyxpz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2glzncmqm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2avaczwhq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2aynkihzj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tbthfulw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdzcraw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhfnxsw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzslrmxd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkovhgl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hphxaujt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlvyvar.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fsitglwb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgefven.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2oubsqdiz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbnxvkn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooghdzzi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qdylrafn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2umczsjsm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ppanucxz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2atlykgnc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsdmzvk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxmzfdo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxztoza.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjpxnua.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2msatdwhe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphmlrem.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rexbqgmf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbfvurx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bifjdtxt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyyzyfr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwucqfb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2amfgjbrw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjqhipf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbhhnql.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqhaxoq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoqkhji.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ravurciu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hdabdars.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yffattgj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2roudahrw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiklcjf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyrmfjw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuxpmcr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbqeapb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiftfne.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmftwvm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2feudblsa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvavkiu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnxxshv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdalcwuy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnqonxk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnwhuam.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yfevpxpn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2llsraafp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyewjjb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2snqxbwsv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciktarkp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oetlljuv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2epzgkfkj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzhlerb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjxbye.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxlnpuz.html


<!-- 参考信息 -->