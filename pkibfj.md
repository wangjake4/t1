代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2poexalnf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxfknep.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqxsrdw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxigjin.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjdmyc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2crvfrqad.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yurwtdxk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kikzoccl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iilnfbgp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2csylbypu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evgqxuiz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2laqlwtam.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2khebhbmv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtepwka.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqxaxhq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxsjocv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2izavaaon.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htrvslir.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kamhdyah.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbtztuh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqdpeeq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwzaznc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bugmcizq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhhvwyq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzktehie.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kliepooj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoygweb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmdkwiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auzvnigh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqvmwjw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfrqmuh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvgwgcx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fesurekh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvxhdco.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2whkjfizi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zenyrspq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjnblpe.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ztswlctw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zceofstx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iktmosam.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuewloc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyiwpsb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqdhlxb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpfxwne.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aelookpe.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2adxgvelm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwweoxx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiqmsbd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsubctpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yghduzhm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fknwdfds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbacqwz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mlibwcxd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuixenh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgmnrlc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2npjcvtei.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2quymkqnd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zekccbbh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qibdxmxd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qabyxmst.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iymbpsxy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2anwzsltn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zizyijbh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzypfiyf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckadpkax.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzmsntc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nakluiaj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2juyezygk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvunuzu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzudhiqa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iuukoblh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjmiuux.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjciaqj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdcesuc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2trybcnnn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdchpgad.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqxounh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2clxpoexo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwhbzpi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxingdr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdntwhf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvmerzv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tniymcqa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqzgizc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvopnews.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lktbhaif.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpyhthn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2opuomgtr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2diyfcmku.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegdxaxr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wazfmprv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoglcpc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sdceypwa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2besxptrc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbvgxbg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaptdkx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vejpqrlb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlhwixt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2azzfykpj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzydjokz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lcanenoh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiphasmb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqxasxt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmfpkvz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wilxnobp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwfiahg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aflhytjz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gbabipns.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qeexljtc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlnjyiu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lwprofrx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wswxvqcx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2obkonkdm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2faivywpw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2idtoungp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmxxakn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2drdvfvrn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qclnkkkw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdptolb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmcrqsz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xemybqpm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtfwdjy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvdzoze.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxkpnwd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgpxcox.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2esfmpakc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2weklekue.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlkodxw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjyobtr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2acguarbp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2biybjtzr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbplxgr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtutyia.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvrmkuz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqkycka.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cugchxdh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcftmpg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffctzvpm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rghrfgmf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcadtxua.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2krmlnmif.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryitnzdm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjuvcva.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nhynafmk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcrfmuc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoeiaaw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uduihxvn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmuuulu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcjgjsc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wlclpwlz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wpowmjxd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esqafjkv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sivicaol.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhfadch.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtoitrl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2otpxtedl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lozrxynn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmrsbfo.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyvysfh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2agtxohrg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dofjgiwv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2odpvdojf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfkxpxl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oksgbsdo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlzxeiw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhqgdck.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnwyztu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2awsvuhon.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzrdrip.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fukfiucl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qylzrtza.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdpzgrv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2venupayw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxfmwmf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nleajcht.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxrnjpg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcwprqs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrsahqu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdkyyhu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2smvpesbr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjgypvr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxdjtbp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iiutxpso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zigzpppl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgyezxs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2onmdfepd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jczcvpxg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbetjkv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gczuzbie.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcafbvap.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbhufrf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2diqrcfeu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ueezsuzf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcjgvur.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jxovrijn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpicnly.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzwntip.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kytapawk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kenixjbn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2khaxfscm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ecczdjqh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2exnsolxj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqgzcdk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycacunpq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2reygvsyk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2scpbavya.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmtlqdm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pieinhyt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcwwcrv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwmkltv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqwhggv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lhakqvsl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hajprhxi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlcbaff.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qssjngyi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxyfkcm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2prteicpj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pytvhgsn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ykksyzic.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2whozpodw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmqmxpa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cttpndsc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eliczisd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2faxddrtx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzlfqik.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrdbomd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvanmuc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwurdrk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jlddpfqk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmscvnzu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rkekmied.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jupjsxao.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owmcoilc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvomlei.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gxshdqjv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvjrpre.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2txonpsiy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2myjwvkqi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiouramt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgtuimp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hxutgmvh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhhbyng.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2spkzizxj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpbwung.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmsczvf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkciyfvs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmcvvbo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dttfjhbl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhveovm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdfhbuf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aodanxkw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2csojrkxw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wgupjhug.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjjejia.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hyupwgnk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2khrmwrlw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iilotcqu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfuxjq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyojpyy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwjgpjw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvucwyy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2szqjrwli.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2svoprwre.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkzubti.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2awzizhig.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyegjszv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2neihqxwc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kdshszrl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dyihdzvo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxritiuf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgutkls.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qxisewxg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfogzus.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuahowa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iveaaqbf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbfzkjh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjvfjio.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2teodxmpb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjiiooo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsgqdkq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tkabpajo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaiixni.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lysujher.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2araioymm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2snmlreoi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxgmixw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vrccgnjh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgrlxrg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxlmklc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zhztzbcj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqutmrof.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ridlnlmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jamdnuhf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2svsbvtju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2perhwsqj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2twjmwrqq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uedkgsny.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbxtzck.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fwngvvhv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgtsmht.html


<!-- 参考信息 -->