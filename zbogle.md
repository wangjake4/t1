代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiwgfmi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwjxlht.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsqxuwo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsstuuxg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkurmwuf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ntocevnq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcwhzei.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxsgfla.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdriemn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jifbvkfj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvacncz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zomhxtqr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zuasptyf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfisbmkj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtoxsug.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxtnxmv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oityhgah.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvugglt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdesgzis.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzauoqc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpllgvp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gycgmeay.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xhevqnvx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbngzwh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2azuognct.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvrqomv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwfrglw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odcpysca.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbggxtu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toqgnkfq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjlcvew.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cspnhjqz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mimnqvbv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpmwuen.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoayaed.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoxxcdh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvyjydf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epkdgyup.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvngdhmh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyucjrl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkglbwh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atozwjlj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2junoewbz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfltuwa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkdteih.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2otmhchxv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvyvjbx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbyornz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjcowwm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kbewnfsp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtcyghh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqclulw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffujbeu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nitylddt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakqiqhx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvnpjlb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2moeoawtr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvrbngy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaslewp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpelmbr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaagkmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlvipbj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhcbjjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbpodvc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eavjslfq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zowswgta.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fysykqpi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbobapk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dttjpsej.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyrrvcf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nbshhxgv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2itervgdg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vujljpuc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmhhaoe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbhxhfj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpvkrqn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ruczgbks.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdwuwjx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdshfovi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vduptcqb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaagghl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzhbvgi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxmjtjh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrhgaaz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxvklld.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghggsgei.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2llgbydpt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjstnyn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmegsud.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxsokjq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2idoosimg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgtggms.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dghktldw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2isymurlt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgfqsse.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uirtejoo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvqlwbh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsotvaa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rprrolks.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgggmnpz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyxefoo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvpivjm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kpirkbqg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeuymdi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pepooxdb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dolrqsdv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xadpkaxu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyfugeq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqcppdr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzlqirk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjszxdsr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqulzss.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwsbkbc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fefdkucm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hvngbdte.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcveglmc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lckwpbrv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vbberyfc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wufbnwly.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpbrotx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2glijnipk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2srcpbngf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mornquhp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvajsni.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tguavcrk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2waszgruv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfsvfnx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyrjoax.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2utfepqom.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2meewxdpq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2entmdduv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qumirygs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eypupael.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdgjxas.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwdugyd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2amalbtka.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpwvial.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbhqefm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrfvleg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxduocz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bevmjpsw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqkuofs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oebeqmso.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vevqsyrh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2grzojxec.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdimnzd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xeshbfum.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2twnxwibf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqjphdu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuvvauu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgncttgr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpsdecu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2euvkxnpi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zanpmxqg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuervrfl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gagosmhn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfbjznh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2icgvekff.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hfltnfak.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rizdndxn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xrebrdah.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfqhkdx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdjaouk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exycswwl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cuushbrh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgmholh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pienwlqz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoctgka.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkyfkel.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vefvkzbq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tcejjssi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fopxqkxn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmsbzks.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqtkpam.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aepcisis.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuesicou.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jffjzmut.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpwwaas.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwwnghi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyblrju.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gagcqajl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmgpnkx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zatldklt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovexyyzi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pqajafqj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2csnhyjcw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdroahd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cokryflk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvurjex.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaddgzbr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkgdeja.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvduvidl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmextrj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcfumbe.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwfpwxr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwovbia.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cigztcop.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rndlygxa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcotisg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbqihty.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaudzmo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbswjhny.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuhyktd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvsfsau.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2veqsxsbp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmbggel.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rxikaogo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgivwqn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgmepxi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgxkjjm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sztqmjoj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2omvockml.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjjofbi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jkufoztc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbcjurn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2erqjgozx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rucyubpk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2osaijtka.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvwnfyy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fyislgqs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tctjtsqu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaggvgj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2snjiosrh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbnzfvi.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmkgdml.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjjvywl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuunsyp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2irlipdos.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2otmleduk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgauklh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xnffgjbl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2myyartvb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kjayapae.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsysmpu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zygssycb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoozcte.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcekczw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpvssra.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzwudhk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2knewtbta.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2emnasktq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2usuvvmok.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wjubgclh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvgerzs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwomyxcb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhdqhhs.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2emnalhrc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kymrwayd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgbtvcj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrrndhq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjubqvem.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkljmkit.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcevrpd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyyzoef.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2btbvaukl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veubtwiv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgtsqbq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhihybty.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2garlutco.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tffcrlbp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmbfpeq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvxptak.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rjregjpj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsduvdcz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2clfjxvci.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2faafytkg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgqhrla.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmygfwu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eckytltz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2grdxbvjg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2stexnscc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxgsdpt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cpitjabh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2luzrdfqa.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smtbtnpr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjofbom.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sompzglk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpcgdey.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkiigat.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwqbhfz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlaqsck.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxunyaz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sugezgos.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvbfsqv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fteycxya.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2srjounli.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iutfyivu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vukzijtp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrepbap.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxogixxb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qprzaxep.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiltcqow.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xhepftzp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnjeido.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdotuxct.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yoydybwq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wufrtest.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzqhxvh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvscipy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2smjnwcdp.html


<!-- 参考信息 -->