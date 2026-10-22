代发 wailian999

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtzoreqysl.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gtfdptvvfh.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtxdspxbxc.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtaydqdxxd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtpunbttbg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtkjimdmxf.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gtwrkrpwty.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtweazgogi.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtztcjppls.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtxlolwbga.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gtnorhrtbi.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqozdgzfs.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gtypuvyiby.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtpmtflkwt.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtmcourfmz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtdopqbvfs.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtmkpbgmqe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtvqzsrtwt.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtbjndelpv.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gtlxipzxpo.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtevmenrvl.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gthkemwjwz.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtpoiqbvsy.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtbjraubkf.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gteyragdfa.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlrggwis.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtjlelhczz.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtmjplsnrm.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gtvogdejpx.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gtpujmvabx.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunvxczfn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtddcdikdt.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtnffdzvqn.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gtbqzkozgd.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkwcszxq.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtihohnjgz.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gtuztwytwr.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoumlupie.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gtameuytkc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gtbwixdcan.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gttjzxrfjg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxygdzbtp.html

[T48] Perl：正则替换
来源：http://dali.shuidangran.top/Article/details/gtsfntaoxf.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gtwmmsbnjq.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtooejchot.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssngztzw.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtmwfpcnum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtrtkokhfx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtxhlunpkq.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gtjqptbufv.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtrzlfhyxb.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtdvwvrtrr.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtfwydpjro.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsezjkwjt.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtgdadmwye.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtpdwtzpuf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtvmkxnfdz.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtgntftita.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gtovvxfdbm.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtlsiaftjh.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gthovnznga.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmxlamtt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtkbddillz.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtjqnhqlyr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtvvkcadbm.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtdxwuwbeg.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtmojclnyp.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gtegfbaqhe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gtpeabnquj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzcxiznze.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtwhqoofkn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnxdqplo.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtdwggvdww.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258888.top/Article/details/gttlfmefbk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqnrxvxa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtoinolrpd.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gtgibfnoym.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gtkabtrnbn.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtyftvlooa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtyykflnyt.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gtszepjdyh.html

list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtheraqmlv.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtjdirrjpy.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtxljqdamj.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtokvkjukz.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtishldmwp.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtumzezkga.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gtduzlpzcr.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtxuqhksdt.html

max(d, key=d.get)
来源：http://dali.gzhubu.top/Article/details/gtrpgdgbuw.html

[U10] Py：按值排序字典
来源：http://dali.ppjwa.cn/Article/details/gtwdogksyt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtqzupcoas.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtjhdyvxoc.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtgyeaancr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtfamksnfv.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gtksfcguqr.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtooovlhqj.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtzhlrwkqr.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gtciitztcf.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtxwqyuyca.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtaufkfewx.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gtumajsklz.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gthzvwfphi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gtokteaaxm.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gtkvlshzac.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtxfpvfzmk.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gtwyryszbt.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtmmhfoles.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gtugwqveaz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtoxwdmjfv.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtkotsakal.html

@functools.lru_cache(maxsize=None)
来源：http://dali.smart0.xyz/Article/details/gttdvvaqjv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gtaquowfhb.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gttbzyaseq.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gtisfupwak.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gtxczjgaki.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtnhhphlot.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtnxlilapv.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtvkrenyhf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtezkibmdq.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigufen.top/Article/details/gtxgpkfkfr.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gtwzlkbqsr.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gtmycpejfl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gtrrfzekgb.html

[U27] Py：异步 HTTP
来源：http://dali.hnxiangtu.top/Article/details/gtnidrvasj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gthxqhbiia.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gtaangtavz.html

UserId = int
来源：http://dali.dianchejie.cn/Article/details/gtgwkbmpmk.html

[U29] Py：属性校验
来源：http://dali.cashguo.top/Article/details/gtjbedrdpb.html

@property 与 @x.setter 配合
来源：http://dali.shzxlz.cn/Article/details/gtzmwilmtj.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtjjtjxphn.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtcbaatchg.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gtjuihbmax.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtozbqqdoh.html

[U32] Py：代码格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtuitpdasp.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gtdgqlgjsk.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gtspcwnlaz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gtvnqcbuku.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gttipaqwfd.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gtejtajrhh.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gtxzivtifo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtpamhvhoe.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gtqchmsmgi.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtwbikidqi.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzigybvt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.smart0.xyz/Article/details/gtgbrwjdsj.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtmplxjijn.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gthqiueueg.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gttnbuldac.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gttgjfqrer.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gtcdyhptbn.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtsqrsxtyk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gtdcpykwmc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gtrsacjswl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtwpavfrxx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jiagoushi.top/Article/details/gtrlehygno.html

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gtjeatomyv.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtzjemefwi.html

[U44] PHP：开启严格类型
来源：http://dali.xuetiantiany.cn/Article/details/gtjwsmqusu.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtakjunxju.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gtchcsaclr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxvkasrka.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gtqrlmfwyt.html

?string $name = null
来源：http://dali.birdmap.top/Article/details/gtjwbwjjjn.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gtxeotnfrr.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gtlysqfadk.html

[U48] PHP：纯枚举
来源：http://dali.hywenlv.cn/Article/details/gtkfdodshs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jyoumei.cn/Article/details/gtjuqyghtj.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gtkfhdauqh.html

public readonly string $name
来源：http://dali.jinghuilouyu.cn/Article/details/gtaodunzzu.html

[U50] PHP：构造器属性提升
来源：http://dali.hnxiangtu.top/Article/details/gtosrqnsup.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtrfwlkfuu.html

[U51] PHP：数组解构
来源：http://dali.snrcjt.cn/Article/details/gtghrkewds.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gtyxpzvewj.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxatvwel.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtcdryfujr.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gtfrehrtai.html

$v = $a ?? $b ?? "default";
来源：http://dali.haohaochexian.top/Article/details/gtovqkhlgk.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtrlmuoabd.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gttalfrpfs.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gtydtjnjet.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jianghu66.top/Article/details/gthzecsnqg.html

[U56] PHP：命名参数
来源：http://dali.xylfe.cn/Article/details/gtrtvgdqnt.html

f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtfwpjweub.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtosnuorqd.html

"值: {$a}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueqtamtn.html

[U58] PHP：数组三件套
来源：http://dali.xuanzx.com/Article/details/gtdaiwqgva.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gturmhqbur.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gtsqscwyuf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtnzhoqsey.html

[U60] PHP：JSON 编解码
来源：http://dali.tianlin.xyz/Article/details/gtjunbfsgu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gtxhvnobgz.html

[U61] PHP：正则
来源：http://dali.tian-w.cn/Article/details/gtonsbmlcd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtoxiwphuj.html

[U62] PHP：日期对象
来源：http://dali.shzxlz.cn/Article/details/gtfsosmukz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gtkihwhzlq.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrxbqgty.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nwbrower.top/Article/details/gtelclzwvm.html

[U64] PHP：目录遍历
来源：http://dali.gzhubu.top/Article/details/gtvagxyqju.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gtvrogihyg.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gtaofvkadr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.316326.xyz/Article/details/gtjsmonbug.html

[U66] PHP：设置 Cookie
来源：http://dali.guannengcc.top/Article/details/gtclvsunlh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tianlin.xyz/Article/details/gtqcprtxed.html

[U67] PHP：处理文件上传
来源：http://dali.haohaochexian.top/Article/details/gtyohrgkkk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtjmzqojuy.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtbyhqggyk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xziqi.cn/Article/details/gtnlkeiodl.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gthidmpolp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gtgxsrizbt.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtyzmawqor.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtgssvaifv.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtnmlomtgd.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtosfninsl.html

[U72] PHP：写错误日志
来源：http://dali.daxiang520.top/Article/details/gtqwqendvy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj202588.top/Article/details/gtsvfcssvi.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmqywgiw.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gtjscjjgcg.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gterdfecdl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gzhubu.top/Article/details/gtxxxvfwxq.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangtech.top/Article/details/gtguwclpbj.html

composer require psr/container
来源：http://dali.316326.xyz/Article/details/gtgmzhjcfn.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gtujlmpdmo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gtgxdxycyl.html

[U77] PHP：模板渲染
来源：http://dali.jinqigfzy.top/Article/details/gtmsnwuvgd.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gttvgpcenc.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtvgniuqua.html

composer require --dev phpunit/phpunit
来源：http://dali.fzhhl.top/Article/details/gtrtxdewfz.html

[U79] PHP：静态分析
来源：http://dali.tian-w.cn/Article/details/gtycacevkm.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gtnelfahyo.html

[U80] PHP：代码规范修复
来源：http://dali.xylfe.cn/Article/details/gtwywugyvb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.snrcjt.cn/Article/details/gtdambpqbt.html

[U81] JS：初始化项目
来源：http://dali.ppjwa.cn/Article/details/gtmpoafdkt.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gtccmeclja.html

[U82] JS：package.json 脚本
来源：http://dali.0kj1m.cn/Article/details/gtkwhwpvfk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuxming.cn/Article/details/gtwudeotom.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtqolwqvkb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtlxwepthf.html

[U84] JS：CommonJS 写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbtiojkx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuanzhike.top/Article/details/gtwqjqopro.html

[U85] JS：可选链
来源：http://dali.cucudq.cn/Article/details/gtenrjbebp.html

a?.b?.c
来源：http://dali.xuanzx.com/Article/details/gtmxmmzjxe.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gtvmvthork.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gtvmooserj.html

[U87] JS：解构默认值
来源：http://dali.ydzc1.top/Article/details/gtsnezsbem.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gtxecadwxz.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gtnjtxtrgp.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gtikcguwwx.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtuicmmuks.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtbxsewwqy.html

[U90] JS：数字数组排序
来源：http://dali.pengpengdd.cyou/Article/details/gtknefuqyb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtrvbussfw.html

[U91] JS：对象键值遍历
来源：http://dali.aibaodan.cn/Article/details/gtfvpnhgra.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkdtepao.html

[U92] JS：深拷贝
来源：http://dali.yueranfly.top/Article/details/gtevntikfy.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtbmtrglnv.html

[U93] JS：模板字符串
来源：http://dali.fzhhl.top/Article/details/gtvrfuyowg.html

`共 ${n} 条`
来源：http://dali.yj202588.top/Article/details/gtnsgpqqqa.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtdinusiry.html

const double = x => x * 2;
来源：http://dali.zdqjudy.top/Article/details/gtjoermkxd.html

[U95] JS：Promise 包装
来源：http://dali.yj202588.top/Article/details/gtfonxwzgq.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxdohjsm.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtgqlkdhhr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gteryhkgdf.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gtdirfdxox.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtmxfxmpwz.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gtgxafgtyx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.haohaochexian.top/Article/details/gtuggkjusz.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gtktsdqjiv.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gtudvnsgvl.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gtkpnbfwzx.html

document.querySelector(".item")
来源：http://dali.aibaodan.cn/Article/details/gtddqhkpbq.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gtgfbyfmie.html

el.classList.toggle("active")
来源：http://dali.yanxiufei.cn/Article/details/gtgtfqokah.html

[U102] JS：本地存储
来源：http://dali.nanxuanxn.top/Article/details/gtvezhamvf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gtfqjzauqa.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gtzxsyopje.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gtrkrmzoch.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtacmareob.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtqbmssuup.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtwqwgvvkn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gtsutwvttb.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtdutzloxf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gtvmtazoyt.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtbykfcvkg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtpcsciovq.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gtirntwhhs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gtrvlstnax.html

[U109] JS：数组分组
来源：http://dali.nanxuanxn.top/Article/details/gtxhrmqhhz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtfbsljuey.html

[U110] JS：数组分块
来源：http://dali.aizwys.cn/Article/details/gtnuwocfbe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gtdffhcyjl.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gtedvtgjiy.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gtfzgheykb.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gtmxfkfjrv.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtghmjciji.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gtqnydqopf.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtfatqhfzu.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gtjiqiibjy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtwxiermov.html


<!-- 参考信息 -->