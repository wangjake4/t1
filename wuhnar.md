代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxgypng.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gktdgjmt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqiaqie.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jcltewjw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdwnxhk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmbpfbj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnropfsc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdttsmm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzojyepx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acesnwww.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxiosho.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lesmxmto.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvzvud.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhcafcq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiwnqox.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkfbeuq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsntqos.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpjtndx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhhpiur.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfdddis.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvavwtsi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnqfbqw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsqshog.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfvzhgi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2trvjvmep.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2inyipchb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvopbam.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnyatbc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzlllrm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsacnczd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ssidooyf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwybart.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2oucptykv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yupudmyc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmctvse.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkihseb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrtojtw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjyvknu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjupibxs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nifayqyb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcndhqjf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvgudjw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzkacpg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvxlwri.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eukwwvrp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgckqpke.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nebcfjrj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2amlyrilk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdxvznh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rvupdtsv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzjpgdu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyipnfr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2abafttkn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aywudcba.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojylqcd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgbbtnq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2azqjrlsp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2egzyingp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdjjtcn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2svklhdlm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2eualcfbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnolufp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvsrwxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxanrixe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aihgqtpa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqvolfc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yfswugsm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2klqdoibm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjysevi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2btbpgvox.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ridlwywy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2msolegmt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgttleza.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdizpoud.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fydvvyuo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksofkzox.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsckopqy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iekqvlqs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrikrdj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2robvmpcs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnspogz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2givkeenw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vedmojux.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2heicdqni.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgrcahm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqyttud.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gwouwgzj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxheqsi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2akxahldg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2grnfpglm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxlzqcw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfemycn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kytadimd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhexxib.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbngorf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttixasku.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bccxqemw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hloevrze.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jnocndqi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bljfdqbd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrpinzz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqgmdgf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2etzefcre.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsyolmp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2krhnuqaa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnxotkx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2byfezwyf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhxknlf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjwfuvv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmcklzf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eboirghc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vprzpnek.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2enwmlnak.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkcpxzk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2soucrcqn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2boryzvio.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xveowbbw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mhytmaun.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgohota.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyeknvs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2epdnoohi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcyypwv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqgeozn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtkdczj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2riuskhce.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fnujwadq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmpjivz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoaavqg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kjewqgcd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2guveyurl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmotpokh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2khmqmxba.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzndoioj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymajsikm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcspbmp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2darddhsg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlpsbsd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bojhlfvj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zicvgiua.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dtesahxu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsobaxy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnkhpbi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zfycuhku.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vygjueix.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mohrspse.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2brduvsgu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmpjkhx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxldtgyp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nsihuaep.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2asdddeak.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyqyzvw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfwrikm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuvpuqx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbzqynr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmwvjdj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2undyttog.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aikcxpbc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uubwzjfn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbevllu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krmouqqu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdesdbd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hbacwpbb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrnihue.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhavvff.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qysfjeam.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2knnyusxo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmwtyor.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqwmtjo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mssaaxws.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpqduac.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybklvmif.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhnukqv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqobzqi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2igblnhcf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2amzqfzdv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tinywfvo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiduzrj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2temlqvdv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoiwhel.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbltxsz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2czqossxr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjjzepp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgkfcq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlozcfq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iedhlheq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjkaczp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2agmtmxiy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbbimnd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bbavtiiw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2runkfizv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xjycdgnj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxryqaj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2snlejcml.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdiggqa.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tiysoslf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrqoinm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeaqgwe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwvcalp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvfoitd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2diiruyfl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yurflkrt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlzalwk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kneqgjiw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbfimyb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvtltoz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vocfpchv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfjliui.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnqvxdm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhrbhnn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iprtkynd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cykhmcpw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxigjbc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hveqfexe.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fddhdzqk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgqwxai.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qepmfupo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgfomru.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kvepcxer.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2agnlmzrw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2aiurxurc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcmblcs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbpbefn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kspmgwbx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2otvxxybx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrxczks.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnqvvhy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2egcwrthu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaezece.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsvpsaz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfdfvgc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2slhqznyt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdjxdbs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuwqhtn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2enzssngb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2junylbon.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2khykpfgk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2avisjkkl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2phsrpfji.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlmpula.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzluqyou.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cigjbsvd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ksedvoqn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oajraepb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2btfqbfem.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwuhsxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2txikzdjc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2teuixxzu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbsbccz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odrgcure.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ammmunhn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzgemnd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibssjrnp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2huvliddr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcjnbvm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnqqhyf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nryvieog.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuonmah.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfkszfd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhjlfxp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2haodammq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqwkuc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rokkzkam.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qororvkl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdvucrj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiojaov.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2koqczqrw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2imgherlp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hedrpkvl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mwowrjfb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxdsdpp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ueobqovf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gybprqrn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wivodllv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxziaejk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyqxuwj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2unochyvy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iqavljyh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqxmvma.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fircbhba.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpkncxu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2psedsobt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbzotiz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcanxgt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lekwjslv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dstmasoh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuqiqhm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xghzjlxz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtbbwld.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zezwmjrx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2udajmapf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwmktzx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eicengbu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aezuiqrb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvjlbzu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2clxfvgtl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wisnslqu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tgteqvfy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bcykmamj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xvceciij.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkmwxxx.html


<!-- 参考信息 -->