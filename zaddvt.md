代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnadqah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgyelxk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2luozfyje.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhunyhq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2srfdypzf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mivgcyrz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exhrqgil.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sythrgum.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjygxam.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nriifguy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbpsmlg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zywwrpbp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwcrekw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgnogez.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxsjxgs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrjajvg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnjlfym.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwysilt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scmhykny.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxllako.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbzcmbm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzbzfop.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kljieyih.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gibgmqft.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2irzjswoq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcwngbw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2euvslsju.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsdiklb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuypzpp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxsjqda.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idxbpzfi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzctsbwy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjwqrsj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muyhsrhz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcgqjmp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwvhzvr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qawzpnhk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgozhiw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zypqwpaa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jklforkb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfltnrcz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqooslc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aebojdfe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgcpzwl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbekqsac.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhecqfp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoshvldz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcqetau.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2npvlnjiz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwnjrif.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kygdllyd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uomyjhac.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2stlrdzyt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yswfvcjm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwjjkrj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kufgnlja.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mymdzwgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axoojaco.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaflgecd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqfymzi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqicotn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2obdfuyvp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uprpcvhc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lngnhswu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fsttqoah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjyvfpp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2onfhyvxt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2avildveq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gtildnkt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqbbwhn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdqzmvq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuzugoj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgzkene.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfvxjor.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnsawzp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2phnzknic.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwwhckq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlqrwiz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvzuxbf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2esoywywn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dubhkuis.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmcwjyy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2futxjfri.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvdzuba.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rswndaoa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2knbayzfv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfempyq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aigalwxl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fbffugkh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqlggig.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2efgbbdrx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2deqmikvn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdhohwi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zunlcors.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwprqmq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pppmcfit.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuapgis.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onaqhoik.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xeplihmz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshiblby.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2abuckncs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2twgyytdi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcuadtw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpczvxd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rixpndvg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgikvjr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qbulnszb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iofigpnm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ksggdruk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uimbrqmq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lwulscrh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpetugb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xetpohwa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjdacss.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cxguoypm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjoxafn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2znvrsnsv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wvufdoou.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rrngqyht.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrvfsjc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rufmysjh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwcsyab.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhtnndw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nafoyyjr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2otiualig.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pusajcip.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsxoutj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iluctugh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyycbpk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nabiymhm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvkmfkq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxanbna.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wartooag.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwtsvda.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2shgzuaqs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnbrryt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfmwpei.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjksujxm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbtgxko.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgqfxdv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhkrnbw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqteafh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dapojvvo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2temksxtf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fphqfoyx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcqozdy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeasfsa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2epkwczcw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqwegwy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiglpeco.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdutqbb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbbjqnz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrbdzgy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxyaavj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuzdoyk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czktexxb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhcpngw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2movguhqh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rhivloco.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnkeacj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iovgupda.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvwepbi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkukhkwn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbukhjo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmokwgz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhdzvlv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsdxmee.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnnrucy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjhbgbv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqdtitd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eashrame.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnywaxse.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkofesdy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwgxvyf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcaqvet.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfqatvq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdejmjp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inpmkosv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaaovle.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlcaaer.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xibtzwpw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2whjfrivd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iogwfclh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcmqxmt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xpstsnku.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzjxcty.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ksladhgx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlizxae.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fohpnhvq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoivjwe.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2enpzlrjf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqxuqyd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aufpjxug.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfjdemm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlbzxjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2llkvnmhj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbzzaqw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2htmwjfdj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2imhwousq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2akuansxs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aoihshwq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgeumte.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tssefuct.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2otqlxdgf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xccfvtma.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlzxoei.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqlyhcc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbinlqyz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcmmuhf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwpbpwp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwkwtff.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2halrgpbf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwrpjem.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwgquoo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpasczs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvgbmdq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaxjuzb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2oveeazxe.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fbutdirz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgydfld.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpvvhzl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fukmfyiv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qwumxfmz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsmkmqd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeshego.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgodbei.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wgafrnck.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstmkfo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2expwdaia.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlypekr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ugycsobq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2navowwpk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqglcpmx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2drkchiim.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bayjvfkd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwvbmvw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhlwyjb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2egpcosmr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rekasgpa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjkadcd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnqdrdx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrchsry.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iicqmxob.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtndargj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cenfxddw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2istgfgqw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npvjusis.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnufonn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnfgqyk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lohzsgci.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2suggxbwz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2weagwbiq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2atyntxmi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjttqtc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xeivknot.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uukjpufm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pngeplyj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwlwyqw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgempyu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzulwerp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yekwdbkp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzcozhw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2brmvkhsq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrtvorh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvrsjtp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vteojdlp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvhwtcq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2objavaiu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vubewepp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtknicz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqjgfgo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dunsncnb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqijlys.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrecdgdj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdcfxsk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2eafcvbme.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoezqnq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2crcezidm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqxqypt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhaywuc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qrstiilj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhnfwhe.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyjmfwo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydweuxmp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuaoasr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwpgqkx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvgstrx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xewzarif.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xutjmclc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhjkncc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdyhbux.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctybwjim.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxxogwu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hfutzdgj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdwlywc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqbwlvt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wjczuhng.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fockgfck.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqjmybn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhzyiiq.html


<!-- 参考信息 -->