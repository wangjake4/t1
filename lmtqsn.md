代发 wailian999

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtjmdfzgiv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtkmgvtwde.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpswiezmy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtksrlqcjl.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxfuuxrm.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gtefizryxz.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtefdmedvg.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtyohlhhlf.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtgxytbfib.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtbjujkeig.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtorkbcbjx.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtfdsmhjmt.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtseakkrcv.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtheezlsjj.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gthansddsi.html

protocol Shape { func area() -> Double }
来源：http://dali.xuanzx.com/Article/details/gtmkmbyztu.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gthsvsfnza.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtswffjfnc.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtficizuzu.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpwlybad.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtovbcafvz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtgdvvnewg.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gtdwcschgi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtcjnwskie.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gthjfcysiv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtsnkfnyof.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gtjkgkwbhn.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtywugztjs.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtioeimfrj.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtbjfmykab.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtgtsrzqkx.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtebuegakk.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtlixtscsk.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtzjikflcr.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtbtfrdzyn.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gthjzvxytf.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtlfolztyi.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtrxlanuwg.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gtrutteelf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gtdbzbwjyh.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtegzefrmm.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gtfirjrdwq.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtctktzqpx.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtrziypjeo.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtmucymbpb.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtjhqlonvf.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcmjnbio.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtntfkeesc.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtfyujnmkt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gttlmvxswu.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gtbsmsobka.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtftqvhnos.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gtyypveunn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtslrupomg.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtyeqeipuk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtckaxabgz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtaabotfgw.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gtqbuaxess.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtrxnzldog.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtoqxaxfgh.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtxibozrwi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtthjplxsh.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtabontfvw.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtjqlglluk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtusrwxenw.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gthevyfrth.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtupzsmber.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtqzljitiv.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtzzxjlfnd.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtwbylvdom.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtpcfsphgv.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gtotsojavb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtwdelxlob.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtdwfbgiog.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtzwctkcux.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtqsywqbkj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtxlqlrrto.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtclgloevx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpdmnxyj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjbypugjz.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gtowahemcr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtnqxzctaj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gtrhnnwbtl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tanke756.top/Article/details/gtpntihjaf.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtgvkbawzi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtkaocdnsx.html

[U04] Py：变量调试打印
来源：http://dali.cqqwz.cn/Article/details/gtakbfgqac.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtbzlmavhg.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtrtevwvma.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtmtmgkkuh.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtrswbxcue.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtbvltqzux.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gtykuvyrcy.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtoxzgpazm.html

[U08] Py：展平二维列表
来源：http://dali.ehwqpu.com/Article/details/gtpbrjfbsy.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtdmnpreuj.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtvmrfaoty.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtyhniqmsw.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gtcmhxluds.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gtslumyuii.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gteassiygm.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtakqpcpon.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gtflpfxpta.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gtyyymzwba.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtdnnzhelx.html

deque(maxlen=10)
来源：http://dali.quarkkingdee.top/Article/details/gtnzmdpgil.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtxyqwdtox.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gtsilngmge.html

[U15] Py：高精度计时
来源：http://dali.zycfv.cn/Article/details/gtvvmygwde.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gthvfbjphc.html

[U16] Py：命令行参数解析
来源：http://dali.feifeiyinyue.top/Article/details/gtxuyfhxkj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtbazxkmbo.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gtcmuivsnu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqxizmvh.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtgdwgakir.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gthnfrjrqj.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtiypagrrc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fzhhl.top/Article/details/gtztsaegtq.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtmypgpnel.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtabifmpml.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gtodrhnjum.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtkseygcxr.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gtfwdpqjih.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmwkyooy.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gtbaaezzfy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gtucgovnqz.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtsuarhfth.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtwwzimakf.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gtjoytnrvl.html

csv.DictReader(f)
来源：http://dali.guannengcc.top/Article/details/gtslsbgdme.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gtzlnrglgw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gtlzcymrcp.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gtdtlrrqhn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gtnhdopanr.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtjkocvmuo.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtdcrvlstl.html

[U29] Py：属性校验
来源：http://dali.jianghu66.top/Article/details/gtfgsqnuyr.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtqcqxrlfv.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gtwjikmtwk.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtbyelwjag.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gtgrzgjtil.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gtroelsbqj.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gtrlmvtsrj.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gtprgsbwyh.html

[U33] Py：打包发布
来源：http://dali.cheryme.top/Article/details/gtgskulshs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtwjztkvkj.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gtibpponlk.html

chardet.detect(raw)
来源：http://dali.wangshuangyany.cn/Article/details/gtpndmriqp.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gtinrtqfjr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.redwolf501.top/Article/details/gtjdjdydxp.html

[U36] Py：定时任务
来源：http://dali.daxiang520.top/Article/details/gtlordeouh.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtcdlrzmdm.html

[U37] Py：读写 Excel
来源：http://dali.kuanghao11.cn/Article/details/gtymjoyinc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhongyouzk.top/Article/details/gtnmlfnhsa.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gthlvzqgrl.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gtkdlprycf.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gthjfmnopd.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gthyifkqnt.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gthvbsopip.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtjtwnviin.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtrnvwlrus.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtwrvuayll.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtwtjxnifz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigufen.top/Article/details/gtushjepcu.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtzrlaspjd.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtswkiepci.html

[U44] PHP：开启严格类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfadrrydu.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gtonokczdd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbgfaxsp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtxylldjtw.html

[U46] PHP：可空类型
来源：http://dali.xinyue.icu/Article/details/gtxrchzloq.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gtfsbbqnbh.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gtabemtagq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gthbsyqipm.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtfmpuqavk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gtnrhriovg.html

[U49] PHP：只读属性
来源：http://dali.yuxming.cn/Article/details/gtuvvropwv.html

public readonly string $name
来源：http://dali.cdnleiting.top/Article/details/gteuoqdzao.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gtazgqjgol.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gtomywlqat.html

[U51] PHP：数组解构
来源：http://dali.ppjwa.cn/Article/details/gtpphcayxf.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gtxkfjiaxr.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtpsvffcxl.html

$double = fn($x) => $x * 2;
来源：http://dali.316326.xyz/Article/details/gtdekrwgty.html

[U53] PHP：空合并运算符
来源：http://dali.nanxuanxn.top/Article/details/gtaorederq.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gtedreqzqy.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gtuhvzcapc.html

$obj?->method()
来源：http://dali.aibaodan.cn/Article/details/gtxfeveniu.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtbdxfodia.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtistixqku.html

[U56] PHP：命名参数
来源：http://dali.smart0.xyz/Article/details/gtgnrjoxzy.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtpqpnkoan.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrldulxtq.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtljcwspov.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtskuolzkm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtgpgfaold.html

[U59] PHP：自定义排序
来源：http://dali.xuanzx.com/Article/details/gtcyervidw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtmmsgqpip.html

[U60] PHP：JSON 编解码
来源：http://dali.gotoacloud.top/Article/details/gtgyptxlsc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtbisolfpa.html

[U61] PHP：正则
来源：http://dali.shuidangran.top/Article/details/gtscizxinc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtxakimglf.html

[U62] PHP：日期对象
来源：http://dali.jinqigufen.top/Article/details/gtxdacloan.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenjidiqi.icu/Article/details/gtzorvihkh.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtoszvxcpz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhoulong.xyz/Article/details/gtwfjptdcb.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtpxmaddjh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gtthoeblfb.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gtuhlosbvr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtzbzqekvf.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtylkxgwzq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cashguo.top/Article/details/gtypoyrcew.html

[U67] PHP：处理文件上传
来源：http://dali.zhoulong.xyz/Article/details/gtbtdzxhkd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gtvujqfgwj.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtgjtiisbc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gtlcjirwot.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gtxiloqswt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gttdjfhgwk.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtrppgpshz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtbdpmhprq.html

[U71] PHP：抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtccyiyxzp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zdqjudy.top/Article/details/gtdzxujcmp.html

[U72] PHP：写错误日志
来源：http://dali.gotoacloud.top/Article/details/gtfvbyrhtp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.0kj1m.cn/Article/details/gtfedskkhx.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtwlflcnkw.html

parse_ini_file("config.ini", true)
来源：http://dali.redwolf501.top/Article/details/gtpncwhbmy.html

[U74] PHP：读取环境变量
来源：http://dali.zycfv.cn/Article/details/gthlleokoj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmjwzens.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gtncegebuj.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gtdyovykts.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gtygclsesf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtkujbzhpp.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtbzczpdxe.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtecgmzwqf.html

[U78] PHP：单元测试
来源：http://dali.bjfxy.top/Article/details/gtpcqyzzpi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzylhiczc.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gtjxxpgsua.html

composer require --dev phpstan/phpstan
来源：http://dali.guowangkeji.top/Article/details/gtksxdufyb.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtftogkand.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhongyouzk.top/Article/details/gtmolnxzfl.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtnadhruut.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gtwwykyvzz.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gtgekarhjk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemfavyoz.html

[U83] JS：ES Module 导入导出
来源：http://dali.feifeiyinyue.top/Article/details/gtcplmfhpw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtachsimfp.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gtsjhqzxam.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.meibo888.top/Article/details/gtwtgqnmpr.html

[U85] JS：可选链
来源：http://dali.daxiang520.top/Article/details/gtoqixiqcb.html

a?.b?.c
来源：http://dali.zhengqikj.top/Article/details/gtzhqauqbp.html

[U86] JS：空值合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxoftguq.html

a ?? b
来源：http://dali.chenlongwang.top/Article/details/gtbnxepnkp.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gtmxhxcmrv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuxming.cn/Article/details/gtmuiqxvcq.html

[U88] JS：对象展开合并
来源：http://dali.zhengqikj.top/Article/details/gtqqwqpzjf.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gtninhgtbx.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gtegirdrbq.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtzpjluhdm.html

[U90] JS：数字数组排序
来源：http://dali.meibo888.top/Article/details/gtttvhfvqb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtznzlhkuk.html

[U91] JS：对象键值遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtilsffrvn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gtcslsovei.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gtimohucpw.html

structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtuqahpnhl.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrgkapnk.html

`共 ${n} 条`
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnljwiwi.html

[U94] JS：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gttexkwukl.html

const double = x => x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtyojoetht.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gtvgaswuno.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gtenejwebk.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gtjyxkuqcv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtdqpntekm.html

[U97] JS：并发请求
来源：http://dali.guowangkeji.top/Article/details/gtqevsvvws.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtgztsndea.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gtbwaqgjba.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhongyouzk.top/Article/details/gtxoodcimx.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gtlmtidhxo.html

el.addEventListener("click", e => {})
来源：http://dali.bjfxy.top/Article/details/gtbbdvbjit.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtqblripmj.html

document.querySelector(".item")
来源：http://dali.andypj.xyz/Article/details/gtdyavumln.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtadecnvdh.html

el.classList.toggle("active")
来源：http://dali.birdmap.top/Article/details/gtlpvpvwze.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtafqnvkrt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gzhubu.top/Article/details/gtvexmhlvt.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gtbdybyebg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtywhlxxai.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gtrcmcpsep.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtspxjqdgr.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gtbeysnxyn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtcjxidqyi.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmsrrefr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gthyrnxtvs.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtzhfwbmba.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthclxduyh.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtapfnryfc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtkhwdipos.html

[U109] JS：数组分组
来源：http://dali.mhx1999.top/Article/details/gtfrenwotm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmyzgdpr.html

[U110] JS：数组分块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubkuctqn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.smart0.xyz/Article/details/gtqhiebyzx.html


<!-- 参考信息 -->