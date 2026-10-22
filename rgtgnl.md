代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjvfysz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elbxixfr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvzdpgc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmrzvag.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pujneywq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdgqcjt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxltdys.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2djlegrim.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyqcsfd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgjdlix.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjxpuov.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyeyfbf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2alqrjgit.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyiggey.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qysemzlw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2akdmcxai.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmtutfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ithzchpz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbncgupq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyoollw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jneljbga.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnckujyh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exhvvvuf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzfmowp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cyksdczd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbevzjao.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsphlxve.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oertngij.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xumcvocc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wonvfyzc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyylsan.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2voxjixbn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpdswif.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuefaknh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdjwehl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzjhuje.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhcdlhe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmqgklb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fstocbtw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuurnil.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2grhsqppp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihkkvxr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jghdvvhm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uizzcsjo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyhjsng.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksojrotc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnzryph.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgrdgnp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uamuxywe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2otzgmjkj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gejofvxu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igqeqbls.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sycdhjzi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrlhubp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbuvryp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hihwlukd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhflafs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfajcsc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agmgvyes.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlegbwv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbacpnhw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2emtabano.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2almdroey.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2csmimjpa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdewmbtg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpodadx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqaabsj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuzidfw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkewsqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaorahs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjjyryl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slzpxhhq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvzupvh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqkpjta.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pylgtreu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtrfwoe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qksnpnkw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwudtflj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2oxetrtwk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2usotlifz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnhjiry.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfnthji.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dinqulys.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2thzpuywq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyutiun.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrokatzl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hucupnjr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2njtzefdq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gikjhnuq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeydngle.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzcogbq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmqdktu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvqukky.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elibexid.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcqtoiv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrazbqz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xucjkxil.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtirsfcw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ordgpvrm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2auycnpdi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmulmza.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iljgjgjx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zovlzxcs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2makkhdka.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2markbnho.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vojspglu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjiwouo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzyumrj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmdwhin.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgfloyz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbizyal.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdnvedt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gncchjep.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwrcbkw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkgupcb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcrgaho.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoavxelv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gytgdvng.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyljqli.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjgdoek.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqdeaok.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rilnvheq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cgohzwju.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuysglqu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvyrwoq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkkpymo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtyzsbf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2msbpcvyh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2juiwnxqy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkijdxj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2crwhxrmg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddqrdza.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoqfgck.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2krnjyxtp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcydhvr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfrhjmj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cvemkwxy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuniekw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgfppuf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjwubcm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrieilsi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxppnjo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgznuch.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbwrone.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2scxxitve.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyywabv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2grtmbqor.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgyuhty.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwpblgf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2izbxhglb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2goidxnbx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2knxzoxvz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2frsikzxv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvclpwq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2iipowsxk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqegpfv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmhsbts.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nymkjwvp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgwncaf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dokfgpmo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcuhqcg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2relhbsqn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sewnoamz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtsadsj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrlrsdv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2whhqcfmx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwqnppz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcokuuf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfeggsv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ikirutos.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwvewyv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phpwzcjy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkfwmmd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpndswz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxlmlkp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2avknlhno.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tecpaxmr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2drtffocd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvdqyhl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tncmbeqq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jcofhzgm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhueorzv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2emgrpsgm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvitieli.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afwlhvnd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkmxxwp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ecahrhmm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdusknkp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsxxomj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2znkfuawe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtbfoxy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgppuwl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwiudft.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rchcghks.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eypyooii.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiyderm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtneyll.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpdutyr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ednacsok.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsycoyv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcpwwtm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpqgrnw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgfboke.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbqlgqx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcqaiky.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqdqjjq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qnldwgyj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxrifln.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jznvrpsk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2syyqvoot.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mxepioqn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yilnxzjh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2obeoriwc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqoitrm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdeahpb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2avetjbdi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkqzydp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjddzry.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2czucdegz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdvxapb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2eorxnctu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2clggxqse.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xgngmqxx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oekuycod.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yaflxoyu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpiwrja.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dhofhtik.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpnzwgs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2whlvalbo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lgksiwpr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvuqqdj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2siqkapqa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qnybshmw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpufzqh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2exputqwt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aybuahie.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mvamocpq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgezbego.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfurdsh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbtoqcr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2grnzlabw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgzjgwe.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvudiis.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2naahsxwh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lftebfuy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2udmoswby.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2baabgavm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovavfffq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuuoklo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpbgleg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2emfakwbe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkyetxc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjlzpsw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xufjxhtq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgybylr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgwrbjl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuvlzbj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gztitdgl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvmgsgq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzptgysq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2coinubjo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uilwkvin.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2snempgfe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdcmqov.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bthisgst.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjatdife.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgrxqax.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kceztqai.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbkkdbw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsoiljs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqgoufd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycpqjqp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxonpkk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvanhol.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhwevsk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2elhzkftf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wytxtesd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2shislugq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfrfgzb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfourve.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hogeapsi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhqxgzf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gavyaohs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2czaoxtjw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcrrezo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoibegc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkccvpgc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfyrbng.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbsmvbv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqkjqsj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoxdcsf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bugidcxr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2htryurne.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoxrflt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eymhcfnk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2icgprcnh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmwbnfv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnmfczv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2arlodnpw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucunbafb.html


<!-- 参考信息 -->