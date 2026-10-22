代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gt2suaglrsv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxthcodt.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gt2ydeutwrm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2kqnbceof.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gt2jibxlxlg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2sygfeecb.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2bkoqkbhi.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gt2owarsqfn.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2bywonijo.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gt2lmwloxkg.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2bolyotiq.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gt2dybdafqr.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gt2qhziipug.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gt2buexxwek.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2dtjlsyfe.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gt2iwzkdioz.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2wwrqvkqh.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gt2ywwsasya.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2srhuhdrq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2bsvjkndy.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2bofpsjmv.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gt2tirhexml.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gt2qkgpjzbb.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kignpikz.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gt2wuzyaonl.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ipojhbob.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzpegnkd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2mfgknxta.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgdaouit.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gt2oufsoner.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gt2keoqlzez.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gt2xmqdjsnw.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gt2pozugyxn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2nbjqduld.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2ievkzofz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gt2qqyhjrwg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuanzx.com/Article/details/gt2liblgndn.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2zfgamjcp.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2qfqhcggh.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2aozstlqa.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gt2rdenxjwc.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2gekadejx.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2lgfdzqek.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2rdetqcjq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2kqhvmmre.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2sglyciiw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gt2pphturwr.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxivtvbh.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gt2vkztapbp.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfygofno.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzjruvsl.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gt2gyxdbrnn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gt2qitbpxvr.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gt2uvhjogik.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2osykgdwz.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gt2jloekegv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gt2xsbqptji.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2dyeoenzt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gt2zuszrykh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2bpowcxjf.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gt2tpizhyvc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gt2chtscpar.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2wbtcvxrk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gt2fnyezgwk.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gt2vunsavqt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gt2uixbhhpo.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gt2bzzfvywv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gt2lvngtful.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gt2vmdjlofk.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2jukmdxqe.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gt2omnaxaku.html

{**a, **b}
来源：http://dali.xinyue.icu/Article/details/gt2zweiexfr.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gt2herszvfq.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gt2lnizyhkt.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gt2bvrswmty.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gt2bjkzgomy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gt2kwbpwaax.html

max(d, key=d.get)
来源：http://dali.yueranfly.top/Article/details/gt2ujqcsdkq.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gt2ndpalcsf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gt2jmuhcgeh.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gt2xakdxcaw.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2oqmnzdnw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gt2ibujybyi.html

Counter(arr).most_common(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fibxzohs.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gt2cibzmwpa.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agwwabfh.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2dwcfcqhw.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dffysujh.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhziceib.html

t = time.perf_counter()
来源：http://dali.daria6918.cn/Article/details/gt2vabpwnfx.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuybpjkv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhixingplan.top/Article/details/gt2thtfwmla.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gt2dsuoxewl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gt2fzmzqjpt.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gt2amxkrzej.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2lihhngdh.html

[U19] Py：正则替换带回调
来源：http://dali.jianghu66.top/Article/details/gt2khjwzigl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gt2nvsyfsoj.html

[U20] Py：缓存函数结果
来源：http://dali.nanxuanxn.top/Article/details/gt2upldpomo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gt2ryhoeida.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qztlsrhq.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmsopbfw.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gt2qripubjn.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gt2tjhjaolf.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gt2pyyjnyxm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cucudq.cn/Article/details/gt2zqzcneto.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gt2ttiexdbr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gt2bxukbooo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhongyouzk.top/Article/details/gt2wukxbotg.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gt2oczejyyr.html

[U26] Py：并发下载
来源：http://dali.hnxiangtu.top/Article/details/gt2hbrguibb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gt2hxxdwcev.html

[U27] Py：异步 HTTP
来源：http://dali.ehwqpu.com/Article/details/gt2phczhzhh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gt2srkfwxaq.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gt2srfwxmbl.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2pmrgerll.html

[U29] Py：属性校验
来源：http://dali.hammf.cn/Article/details/gt2vbrpeljs.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gt2bvsmwzpl.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krpyuboi.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egyqkgfm.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gt2uqgbupll.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gt2wlztxfxw.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2kxyeelfa.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gt2yrrrtwzo.html

[U33] Py：打包发布
来源：http://dali.tanke756.top/Article/details/gt2pbyrapuj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gt2lslvlkrs.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gt2qvbarote.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gt2mlwtoyap.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gt2savyxskf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gt2aqotblts.html

[U36] Py：定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdorbicw.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gt2pxqcyaro.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gt2zlpxowus.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gt2qgvzvnlx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhoulong.xyz/Article/details/gt2iwjsmkfb.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnebgett.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gt2egepbykm.html

sys.stdout.isatty()
来源：http://dali.snrcjt.cn/Article/details/gt2nsmcfvjk.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258888.top/Article/details/gt2dvusgkdw.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2jpuknxnz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gt2rnzgezdi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gt2qlmfglha.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gt2btopaqxm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uombttlq.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gt2vhjbgcxz.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gt2cgxjqehk.html

[U44] PHP：开启严格类型
来源：http://dali.sweek.top/Article/details/gt2xcmtsbjj.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gt2admhwxgv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gt2hioalrio.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2bpdyyjaj.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gt2ybqnatew.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gt2yurdwuac.html

[U47] PHP：联合类型
来源：http://dali.aizwys.cn/Article/details/gt2dxhxxnsy.html

int|string $id
来源：http://dali.cqqwz.cn/Article/details/gt2toeeptuu.html

[U48] PHP：纯枚举
来源：http://dali.xziqi.cn/Article/details/gt2gdmtbfdn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gt2osxuidlk.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gt2oqtegnub.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gt2dafuiprz.html

[U50] PHP：构造器属性提升
来源：http://dali.hfpthk.cn/Article/details/gt2mgpuvldf.html

public function __construct(private int $id) {}
来源：http://dali.zhixingplan.top/Article/details/gt2sbxuazxs.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifemmspm.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gt2uuebjkke.html

[U52] PHP：箭头函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdmqnrks.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gt2qixmktiz.html

[U53] PHP：空合并运算符
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbudpjiw.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gt2kpgewtqm.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gt2wdmnuyhk.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gt2yajpxwpj.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbocrgnc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxetxhax.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2xrpqieqk.html

f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkddmitw.html

[U57] PHP：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2faohwwpx.html

"值: {$a}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kftmnvum.html

[U58] PHP：数组三件套
来源：http://dali.yuxming.cn/Article/details/gt2dvekgxiu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofzzrfdg.html

[U59] PHP：自定义排序
来源：http://dali.ehwqpu.com/Article/details/gt2ckvsutix.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2ctsjkrfi.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gt2cqzcunkj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gt2lkhmjbdd.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gt2pdxhubrm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2zdmclmsp.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gt2ctqmscyv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpggtykk.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gt2zjyflxqp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gt2fdbqttyj.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gt2fnvfnikt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gt2jsincewl.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gt2qbkyyvja.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2okzltmnj.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gt2ymhewepz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyxnrquv.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gt2eaoyrgyg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.snrcjt.cn/Article/details/gt2mpgqwjgm.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gt2oqjewujo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2rvjenmiu.html

[U69] PHP：PDO 预处理
来源：http://dali.sweek.top/Article/details/gt2vmukwwzy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqzmerzx.html

[U70] PHP：PDO 事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2uudjzaog.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gt2knjebzqj.html

[U71] PHP：抛出异常
来源：http://dali.hammf.cn/Article/details/gt2missvkqj.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gt2tudfuvus.html

[U72] PHP：写错误日志
来源：http://dali.meibo888.top/Article/details/gt2zohblpgo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tianlin.xyz/Article/details/gt2ecjgunch.html

[U73] PHP：读取 ini 配置
来源：http://dali.havefunace.top/Article/details/gt2xiigdqtz.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbvqyhbd.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2athwcaak.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gt2aevkkfyh.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gt2xubmxftp.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gt2yrobvpkl.html

[U76] PHP：简单路由
来源：http://dali.hywenlv.cn/Article/details/gt2fytkbbds.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ampcvxgs.html

[U77] PHP：模板渲染
来源：http://dali.ybcxt.top/Article/details/gt2pzzmafwf.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gt2ixkbjioq.html

[U78] PHP：单元测试
来源：http://dali.snrcjt.cn/Article/details/gt2qmhpuslj.html

composer require --dev phpunit/phpunit
来源：http://dali.ppjwa.cn/Article/details/gt2wjmgxell.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gt2vldpwuey.html

composer require --dev phpstan/phpstan
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfnooadk.html

[U80] PHP：代码规范修复
来源：http://dali.0kj1m.cn/Article/details/gt2qgbdtruz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guowangkeji.top/Article/details/gt2xvwgncuu.html

[U81] JS：初始化项目
来源：http://dali.hnxiangtu.top/Article/details/gt2gifiuuxa.html

npm init -y;  npm i express
来源：http://dali.9152youxi.cn/Article/details/gt2odggkebx.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gt2whdwpgva.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gt2qictbxtj.html

[U83] JS：ES Module 导入导出
来源：http://dali.meibo888.top/Article/details/gt2iryqjmxb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gt2ocxuxada.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gt2qpbgcppv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ombwvkfa.html

[U85] JS：可选链
来源：http://dali.cheryme.top/Article/details/gt2kazofehz.html

a?.b?.c
来源：http://dali.zhongyouzk.top/Article/details/gt2nezcnbyc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2auyscljr.html

a ?? b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkldxegx.html

[U87] JS：解构默认值
来源：http://dali.shuidangran.top/Article/details/gt2bjpitrov.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sufxvd.cn/Article/details/gt2kdrfobuc.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gt2vsyhjpsa.html

{ ...a, ...b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccnvsvzt.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gt2ngbfsvyd.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2kestnxdv.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjmkxbeu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2foxlnhot.html

[U91] JS：对象键值遍历
来源：http://dali.xuanzx.com/Article/details/gt2jkvmrdvc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jyoumei.cn/Article/details/gt2rvdelmrr.html

[U92] JS：深拷贝
来源：http://dali.nwbrower.top/Article/details/gt2dmvjpbry.html

structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqmgfzhx.html

[U93] JS：模板字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2cwhdllmg.html

`共 ${n} 条`
来源：http://dali.nwbrower.top/Article/details/gt2ozjhoxpw.html

[U94] JS：箭头函数
来源：http://dali.yuxming.cn/Article/details/gt2vhawwgpo.html

const double = x => x * 2;
来源：http://dali.hnqzz.top/Article/details/gt2xlowblcy.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gt2dinlyrjm.html

new Promise((resolve, reject) => {})
来源：http://dali.zycfv.cn/Article/details/gt2vnpoexvw.html

[U96] JS：async/await 与异常
来源：http://dali.aibaodan.cn/Article/details/gt2nsaoqzrf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2flndlyeg.html

[U97] JS：并发请求
来源：http://dali.snrcjt.cn/Article/details/gt2mxqqkezx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2bqsmirrc.html

[U98] JS：fetch 带 JSON
来源：http://dali.havefunace.top/Article/details/gt2pxuteczm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jyoumei.cn/Article/details/gt2apytbgdt.html

[U99] JS：事件监听
来源：http://dali.hammf.cn/Article/details/gt2rdhfnkqx.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gt2yhsgdrao.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gt2zrajqieo.html

document.querySelector(".item")
来源：http://dali.dianchejie.cn/Article/details/gt2zmyzxtsf.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gt2yqsujxms.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gt2oxyeujqd.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gt2nawlojhy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cheryme.top/Article/details/gt2auvmmbss.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gt2ipkvimdi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fskdabaj.html

[U104] JS：防抖
来源：http://dali.sweek.top/Article/details/gt2nrrerlln.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2wdategho.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gt2pvqipebn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssxvildo.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2xkfgtnag.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gt2jvfgqnof.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gt2zkldougl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2lyexfjgk.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gt2gfjfrzbw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gt2ojnmxyfo.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gt2ydtchbkf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gt2kzvdghjc.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gt2ntnadxcm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gt2acrkpxop.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gt2buvmvjuc.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncoezzoy.html

[U112] JS：字符串补位
来源：http://dali.nanxuanxn.top/Article/details/gt2xsxqmuen.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2ktgrxfdu.html

[U113] JS：正则替换全部
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqozjnuq.html

s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2uccngyga.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gt2taezvzpx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gt2jhoacbzy.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2rcxxuqxm.html

crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2gerltubm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gt2givayrwp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gt2emsbjycx.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gt2wpfpadux.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgiofzhr.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hykekpyv.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2wszgnran.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gt2unzzglqi.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gt2pvneyrwb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gt2ecovoiwj.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gt2itefxrjp.html


<!-- 参考信息 -->