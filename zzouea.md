代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gtxxvcxznw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gtvrdmbdee.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtddhohcyx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtuhdwrmzx.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtmckqhwvo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtuyllsurk.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtzhwgwhmd.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtoxyvfthi.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdebuobjj.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtqpbkrbkm.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gteotihtwc.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjjzqjbl.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gttrqbbjjb.html

string.find(s, "%d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfcuafwu.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtgxudtkbb.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtpofodbth.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gthwhlijfa.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtfmnukiah.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtjbrjtitf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtaexxxehu.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtfdosrhkl.html

"值: $a"
来源：http://dali.cdnleiting.top/Article/details/gtxmvhrlqd.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtiapuryht.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gtulsupoeh.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gtigvscvss.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtpiynunvt.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gtemvvnyma.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtsjtwpuzo.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtliamgbsy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqlvkwnb.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gtdsaxglya.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gtoijswesf.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexruuoeo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtbqzxdgzm.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtqubndyia.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtiecflvco.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgwnvlsie.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtvsfwahrw.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtwwlyewix.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtitxqnunv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtlaibsmba.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtkgtskejt.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtchtygmzr.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtacoihmgy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtxupcyeas.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gteiyhyqhi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtdwkvkjqk.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gtecuqmhxm.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtwvoohfne.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtezjslvwp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtyqgbtuse.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gtqxikhbid.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtfldifwpa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtqglnklxa.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtcdmbtnxe.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gtopzbvvza.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtgivyvdkt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdzvfeowq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gteupkiuhr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgsgvyqes.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gtxdnwaapt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gttkbvjorq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gtnkrkqcde.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnelgpujf.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gtumgdduyg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gthtvjmqph.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtasmwriea.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gtpeirkonl.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtcozyzkfe.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtwyhptysm.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtlrzefupb.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gtatswhprs.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtjqbnqzta.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gtymtralyy.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtkdwtckot.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gtodecgyrz.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gtfmtqflez.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gtdebfrfhx.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtvwxhsdjv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtxzdteosq.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtsrhcjdfm.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmbrkithj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtwvtnjiye.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gtkjwljsli.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtloyzvwzn.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gtvbmmdkuq.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtltjemyas.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gtanyrykzd.html

[U15] Py：高精度计时
来源：http://dali.hammf.cn/Article/details/gteucgriic.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtqnyfkywx.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gtcqmrmwxc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.smart0.xyz/Article/details/gtvcakmhpb.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtoekbsplh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtbbmjsnnj.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gtoazdiyzm.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gtpkepljhb.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gtaiwwnfnu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gtsqazzdps.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gterfvvuex.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gtmmlazvev.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtoatpqpzf.html

@contextlib.contextmanager
来源：http://dali.9152youxi.cn/Article/details/gtvboumwwo.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gtpgvkknnk.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtfpxoroqd.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gtvlarfnyy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtelzgeupu.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gtlgpxuitv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gthylnnuap.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gtroqcmslx.html

csv.DictReader(f)
来源：http://dali.chenjidiqi.icu/Article/details/gttzwnjhst.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtzikcstug.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtcjmlhcyo.html

[U27] Py：异步 HTTP
来源：http://dali.gogol.net.cn/Article/details/gtirlbzpgm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yanxiufei.cn/Article/details/gtuuupedeo.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gthdaubqcg.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtblrttjac.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gttkvdkohs.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gterhpqsdj.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtyoujhwda.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtitdmyatd.html

[U31] Py：单测
来源：http://dali.gotoacloud.top/Article/details/gtezrpbxij.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtrcrqpsag.html

[U32] Py：代码格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrotbfbp.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gtobsjjafl.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtznrtacje.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.mhx1999.top/Article/details/gtglxahqry.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtabqirvhl.html

chardet.detect(raw)
来源：http://dali.wangshuangyany.cn/Article/details/gttpgpvntp.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtngrajtvc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtztyhitul.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gtglwwxlmr.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gtsbrgedxm.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gtmjurgwcx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gtylcbkdeg.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtsvdunfys.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbjtmegk.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gtwafkabyc.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gtwuodcyis.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtasloveoe.html

print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtzykmvzae.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtwxxbjnmt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gtmqybuioo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gttrzuwpbm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtvxaewcoz.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gtmglwrpqr.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaixkxajs.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gtdbinaqef.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gttyebggyg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtyqomcbcr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtmixlwjyt.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gtcgnfxohn.html

?string $name = null
来源：http://dali.gzhubu.top/Article/details/gtehczniqh.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtchricsal.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gtynctmimx.html

[U48] PHP：纯枚举
来源：http://dali.yj202588.top/Article/details/gttgjikcnj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.9152youxi.cn/Article/details/gtpdusvvtg.html

[U49] PHP：只读属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkuiqtcf.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gtpwgkpmyn.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvjvqxbg.html

public function __construct(private int $id) {}
来源：http://dali.yj20258888.top/Article/details/gtabgyisif.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gtmxfsviwj.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtcsjzzyem.html

[U52] PHP：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gtlupjekrb.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gtlazaykzk.html

[U53] PHP：空合并运算符
来源：http://dali.tianlin.xyz/Article/details/gtxooeddzp.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gtimddicgy.html

[U54] PHP：空安全调用
来源：http://dali.xinyue.icu/Article/details/gtahfoeljz.html

$obj?->method()
来源：http://dali.birdmap.top/Article/details/gtfcsnbtai.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gtyaawnobp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtotuogwve.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtuxrgmzar.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtcklavqgn.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtndvlnwxz.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gtsfbsszyr.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gtuqmohafj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.c1oappe.top/Article/details/gtruszchiv.html

[U59] PHP：自定义排序
来源：http://dali.sufxvd.cn/Article/details/gtmkvhomju.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtayhdmgda.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gtodxlafiw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gttmkzngem.html

[U61] PHP：正则
来源：http://dali.yvedp.cn/Article/details/gtafghfpsf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtnuzzxhgf.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gtbrppsdxt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhixingplan.top/Article/details/gtoyuwvoip.html

[U63] PHP：文件读写
来源：http://dali.hongshengwenyu.top/Article/details/gtjucbtikq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.meibo888.top/Article/details/gtczujihuk.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtdtnqwvka.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guowangkeji.top/Article/details/gtlexzeenn.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtykslduoy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtmcthrdag.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gtzujpjnef.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gtrxtszgna.html

[U67] PHP：处理文件上传
来源：http://dali.yueranfly.top/Article/details/gttfcmusjn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gtynpzgiln.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtbmmkgsjd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gtgwohfcxq.html

[U69] PHP：PDO 预处理
来源：http://dali.xuanzx.com/Article/details/gtzlrrghki.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gtsiyjmwwd.html

[U70] PHP：PDO 事务
来源：http://dali.fengsongda.top/Article/details/gttigmcavu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yvedp.cn/Article/details/gtwgshmqpe.html

[U71] PHP：抛出异常
来源：http://dali.guannengcc.top/Article/details/gtdwsdqnpo.html

throw new RuntimeException("失败", 500);
来源：http://dali.xziqi.cn/Article/details/gttzaebliw.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtpiysvfda.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhiwuduotai.top/Article/details/gtkpoklhsm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhengqikj.top/Article/details/gtmehnjgqd.html

parse_ini_file("config.ini", true)
来源：http://dali.xuetiantiany.cn/Article/details/gthpaucxwj.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtfigcgyww.html

getenv("APP_ENV") ?: "production"
来源：http://dali.havefunace.top/Article/details/gtmcoyhncd.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gtfdftrajn.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gtzjmjujfv.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gtmgociqno.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gtcabqhlqa.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtuctftskg.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gttbvufelf.html

[U78] PHP：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtetzxipnz.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gtixcbxubr.html

[U79] PHP：静态分析
来源：http://dali.dashuyun.cn/Article/details/gtowveqzxr.html

composer require --dev phpstan/phpstan
来源：http://dali.feifeiyinyue.top/Article/details/gtxfwrzuaj.html

[U80] PHP：代码规范修复
来源：http://dali.meibo888.top/Article/details/gtuxzmcooq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgwquimu.html

[U81] JS：初始化项目
来源：http://dali.redwolf501.top/Article/details/gtfduchlzt.html

npm init -y;  npm i express
来源：http://dali.hfpthk.cn/Article/details/gtulatkggd.html

[U82] JS：package.json 脚本
来源：http://dali.aibaodan.cn/Article/details/gtqimlyeks.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tianlin.xyz/Article/details/gtszhlozbn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhengqikj.top/Article/details/gtisbyygaq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtuxwmogba.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gtzuhtkeen.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpwuhgaw.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gtwydkpbcy.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gtbdkmrklb.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gtovdfkcks.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gtzlhiwawd.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtykznioox.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtvxhmvnyd.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gtakvxwdfq.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gtgtkxubal.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gtqlequkzu.html

[...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtvbqtmpdz.html

[U90] JS：数字数组排序
来源：http://dali.0kj1m.cn/Article/details/gtenjxzlqi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtvimwvvhh.html

[U91] JS：对象键值遍历
来源：http://dali.sufxvd.cn/Article/details/gtcylxtkhp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ivvv.top/Article/details/gtxgvymgzg.html

[U92] JS：深拷贝
来源：http://dali.hywenlv.cn/Article/details/gtvawgvzkh.html

structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtvlpllqao.html

[U93] JS：模板字符串
来源：http://dali.cqqwz.cn/Article/details/gtpcdbkuac.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gtbkhgknwg.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtpssfsobj.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtncqdidmo.html

[U95] JS：Promise 包装
来源：http://dali.nanxuanxn.top/Article/details/gtzxkxdsvv.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gtnfugzlzj.html

[U96] JS：async/await 与异常
来源：http://dali.cucudq.cn/Article/details/gtbkbigicp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtisksxgus.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gthvojszoj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtbcinfaip.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gtrumgjmyf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtsolztkdx.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gtsvupusey.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gtcapnarcw.html

[U100] JS：DOM 查询
来源：http://dali.fzhhl.top/Article/details/gthmmvgfue.html

document.querySelector(".item")
来源：http://dali.haohaochexian.top/Article/details/gtlwptnthy.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtcgppcfzj.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gtidqhgubl.html

[U102] JS：本地存储
来源：http://dali.zdqjudy.top/Article/details/gtlqfpmwlb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gtisikgllb.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gthyogqeny.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gtrkysfkmx.html

[U104] JS：防抖
来源：http://dali.yangfankeji.com/Article/details/gthtalkkcl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtfemsaekc.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkaekrxp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.mhx1999.top/Article/details/gtleycubuf.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtgkcwydhc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gtuvvxdmoo.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtkwcuggyo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtiayqeabg.html

[U108] JS：随机整数
来源：http://dali.sxryk.cn/Article/details/gtwjsllkad.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guowangkeji.top/Article/details/gtytsekidy.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gtajvhhesy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtawmgwfbe.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gtgmeqgtem.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtcspnbqeh.html

[U111] JS：对象转 Map
来源：http://dali.hnqzz.top/Article/details/gtbzmiuntq.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtgvcxqbre.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtbjaqhcmn.html

"7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtcunbvjnd.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gtdpioxwrp.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtvopopncp.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtnmvqxnkf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtvofdnmbt.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtdvtjjupl.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtmcuweokj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gtstycbitq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gtibbdevyz.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtfsitlzxo.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gteqbygcnj.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gtudnjtkys.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gtlztcbpds.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtmwfadmie.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtarjokxfn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.316326.xyz/Article/details/gtawfgeycl.html

import.meta.env.VITE_API_URL
来源：http://dali.hywenlv.cn/Article/details/gtvycrleig.html


<!-- 参考信息 -->