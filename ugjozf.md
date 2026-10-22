代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2csbpuuse.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvadhyij.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoesztj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2huzhabbv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yeelmlsh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdxdouq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sspyyohk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lygkntkz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzmsqlg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuevlmk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvjpnei.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzcgqkc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqojzfk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tencfxph.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpkvbvq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2macwuals.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvlvutn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvzjgbp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqafsvw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkeevax.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwakaus.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llrbrznu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgfjlrn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvsrjng.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afmecoox.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kedmmgfh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idbqxodx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxlhkgr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qseevbbp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmuehvd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqkiqtx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxsyqpt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iumzsfuz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vedkcsfm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfkxgly.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2stitteji.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2knobyuen.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2weukkggt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkhdrcp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkafvgi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudyclbc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzwkptg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2clfgnrcc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdotvir.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxbivnd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wmazbfrg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgksntcw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2awlspqjr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2csshosid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxdfzlt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfairfss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyngqay.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ecedreih.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuobous.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2khswoldg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cresvhxu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtjztkn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkblzbn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bectgdod.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fjessayz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjudgym.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2phbthrbt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sbswvjcd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iblihdbf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaymxoa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2icdzymtd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yudysyiz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2abwesgmo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2javsnvcs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkivqmc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kiswmlym.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxtcaem.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2acpiorpv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zihwrdmj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uogrescd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhszkzlk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oewfdcpe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoccxaek.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2efxsejrz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2auauymrh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsuoplk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2unjbrkja.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2icjzgten.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2govheltx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgmofzc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmlrkcl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrtqwdk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2chqdpkwa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwkvswo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulavoqlp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqqeyzh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vicgkpkh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfokmjd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2obwiqzcu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ainbgnfx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bebphxng.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsukcvif.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoirybs.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jhunasyo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmbsocy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eptbpkut.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2otcclias.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2crqvzqex.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyfqzes.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ipipqfai.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzghkqd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2knpybsql.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sijvkxzr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pifawwwd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2oawtutqg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qpffxwtt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yopoipzq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrdprks.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2emhccqdh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2czrdorli.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2njcxwvwp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiibcea.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiotfbft.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2setyksjv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlwlvho.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfmthbg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbdfueb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2thhnfjjz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wimxqqcw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kducdafp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zawfklok.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fofkmrpv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwrlksx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbbdbit.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sffnfwdm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfqceuz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2guanwkly.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkqeztf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuhnwdt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zjldskeu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyngmvn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sujuclrr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykayvcnc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vofsowjd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzooblj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2quucnmyj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmfdshe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opzueygf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqoqmjv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgxvrez.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcqlbna.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjtazsq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpqyjds.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpuiewr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cibwrirc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjbivnx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fayjkiiz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cdywfwdg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfgfjaf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rehlkjfu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwogyttl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vempkrsh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpzurub.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2auowmzmb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2njbnzytb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrardqx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lofvaiab.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvpwffr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqggjlu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnvutvc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjvikja.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnwgggw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2keuyavay.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cgegvkhh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xczupgwx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxyboad.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbylxyfl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhwfobm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2alwlnqpo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xoopfwbv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiarpnm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpdigxr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsevkent.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkjvcro.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmovbkt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzukhts.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obombvvz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrqcejl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoisiykt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvuatpy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qupyddvm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtnmfta.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgrobwb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwkjjej.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfokdqdc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2atzzcnfs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgvblyk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfgxgmt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvvswhd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjmenjs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfgpaex.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2giracdtj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2prucjrgk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkiegar.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gplilmqz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pmszjent.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeaghqd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2asydscgi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vinkbpkr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2chfwudpb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2malgfjqo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2utdesxpp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nthbigof.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nysdcffb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyruxwd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hasjqqur.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyjaris.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjvzgwm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgztvmo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uffqpbsh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aylapwlk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bbolkeoy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyenapo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cbctniai.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2byqqxnig.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dihagmlq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnulxjx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhggqew.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfxwgbw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxyonjx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2riskyfsd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eweaipxk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nckzaout.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2euhyfeyd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhvmadg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tywmegda.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2myvsrudm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wlswjfig.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrvtpjz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqncjbl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbunyjbx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwcuasl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmyitog.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epylpnme.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuouzxk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jtntzdpf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kydxqffq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxyccjv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikruxxon.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpghzwg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdmakwh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xognjyap.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2baehxuxs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dmttsiaf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2glbnfbrx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmrahll.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpiqigl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2quvhdnkw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqfdykw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgevhbh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2neqarutr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2agjyxuzf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmtqwzs.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kceveqbq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irrpzizq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2coimwovm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2paewxpvi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdmizxm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrigsuc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmnlbug.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjuzlyt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqsrrdb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdhzwgt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eadechxk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqeqowv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcsnlif.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfbcgog.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bujzriik.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfaclkw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jsklshyv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbacvwc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqyezxz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxkbvrv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcsfnsp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfxncby.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ioezoetd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyddcxr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyasauj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sirzezbi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zqernctw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2unbyqxrj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ziamtlcx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2shdmuaxs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmtgwcz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2guytkhgk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmpbytf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpduomj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeordtox.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2czqrrwqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onufanfr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gwanfjff.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaqeciu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlgnoss.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xkylrayy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqstbtr.html


<!-- 参考信息 -->