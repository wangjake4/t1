代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqiqgom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mfulhqbl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2igxkdhib.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ceusoglg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zoefczez.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2llsislju.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtvogvh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmlkluq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kelfrymy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdvuopx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvfboyf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zixmtkyj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlxrorr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckipnnoy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyrraou.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbnmbds.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dkghcchy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2agcpjvem.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqzjawf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcnmwgq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qewophkr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeqqynj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2apstarpn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjwwonf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvjmskd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyxzxxh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuwfgei.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fclolczg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfkhnta.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iylzwyzb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrfwwuw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirqtkuf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzrkhbd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgurxec.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdipkyk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2npysjbwk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uadgpwke.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nokogetw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxwpzwj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjxrvhm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mskwwqbh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwwrxrm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuynvwky.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmvyytq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rslyqaci.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmtqjgw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnhqpqq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkrnvmj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2otazybom.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2taoxyqgh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2houbkpkt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwujzyzi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yoepalnr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuasjsf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nurgfkgi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hitsttgx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeckrtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zscsyrcw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cusuhxku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2warwnydo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tucfozvy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wyztkhjp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2unttgplb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aclerxlh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcqyqrq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaobemrf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjjhqpd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pykyouxh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2imjhigpr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eessqbuu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwmlzbx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2skmresrn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oiewqnbo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuezplx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlhqtlv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2eohncrtz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iukbppym.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lviatwem.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uflzfklk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nalhjmat.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lskkdmdc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfybigwi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrsafwh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyiajqz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2frghtlnb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2txpmicng.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnagqwsb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuivxby.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvrkule.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsozhwat.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2drkgqfoc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2twskzhww.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwfggcz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgxciaw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwfcjnq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2llqssonf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cguwahmd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2etwerndu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lunihqtl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiisqvt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yjynpvib.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2emvlhyqr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfvjzlo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fccewlev.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgbbhat.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wwectpfp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkcokiy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lilvzbkw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsishnz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2samscith.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rafzlwrt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2seeukfue.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzijrab.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqpmytp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vudccxrh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mwczuzzx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzgyuru.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hauyenjn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfsirls.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqzdnpy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrfknot.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2khwzwymk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhwezul.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pehjoghs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbiuwmn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoggxse.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxfdesc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yylrhchu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zioklptq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2naojljmv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wapurzov.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mprhjzym.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oomlobgq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2unmmcphf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjrvntl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iauuibln.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgenyoo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsavmhq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ejljwdgh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsghctk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2caqqjvzj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbcjuqs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqtxusg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrkmbho.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tngxsyka.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqfbblt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvtcsvp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rolyjozm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xotkrikh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vffzovpk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2myatigzf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaizboy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwgysss.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqappdk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rmifdqqc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsbynxp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sicoyely.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvoagxd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jisurjkz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olgrmfvt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2emqxllas.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2marazbke.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avelkfzz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnkjzov.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjzwuyo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqxllkc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2azxngldn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pedbwcjz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ooubmmiv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpvpxks.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvytmtof.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2myathecc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxyqbpr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtjvglp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uivlvezo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2siejowqq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2unnkxoxt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmynmmge.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xunaoluk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgajkcun.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnumvze.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnqhouh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yejsbgtv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2opiqrbxr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gqobzqoh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwgbrcw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2utqakdsq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2skhscnxv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bozttydu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxckjsd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmfvicy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbmvixm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoizcxq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhmwel.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kqadpgtq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtlggat.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjomahdd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqyulgp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ektpeaut.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wafvvfux.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiofbbk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpkmovz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nsahtceu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lsidnabl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dswfdyia.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoszjyfc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xldbtawx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2trhwvpfl.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyompyv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2peaeeggw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dukdusef.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlxinxx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeydgqi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zykumhce.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxqfgno.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgjjpsx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbizipm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdhkhly.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbohvbp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbxxpmf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvhwqwd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hrokmdca.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvsxuit.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhzcutp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oeobsarc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2newthjcn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2brmjilzl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkdthex.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2asgbgevj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mukkqfmr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qxddzejc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkkawzk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtwipkn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dybagerb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwgzgpi.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjbhhen.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2swpxmnkg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2krikiqdm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wukxfkls.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfufizl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvayocl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjgkjkm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qqioxvip.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2igmfdeii.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pursjthd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2klqphfrk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snjohgny.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kocwqcsm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxdbvlf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xspdmgyd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2duomaykp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zckdpjth.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrplytr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfozkxte.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqxvbgq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zloqgrgz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2biofohaq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gbknkwok.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjfnfte.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxmuvhk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmewyiu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qndluagh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkxpgmi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2psvwbmxt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2babcrbls.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bflaxcwi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rsikvinw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvblppzz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fazdasge.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyjwuvh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjijelb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iynfxgei.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wudhzhap.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuqrtty.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhqifkq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mifwrnkc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2odrpiyia.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2opycavle.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzqhasi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2limmzvbk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpgjolu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2actymsgp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaqlrtp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfwjrcg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hnebbhtc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxobiaq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkffzxw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicnfukc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kpikmlhb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rafgcdcw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcytcxia.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfgwxra.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2otuaydgs.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2swzfcrxo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dygnmviy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2coyrqvcy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eftbpbbv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaptihm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nakradni.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvmumaz.html


<!-- 参考信息 -->