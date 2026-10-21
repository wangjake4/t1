代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtadhpcycl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gthcycnpji.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gtyolkaskp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvjkbyva.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtwqbphhms.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gttaelhnbm.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtdqtlomrj.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gtsitggaia.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtbsihskux.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtaztnphar.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gtktbcxwpi.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtlcysugck.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtoiwjdjhe.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gtbgnuskgn.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtarkrtugt.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtklkmgqeq.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtbtvjbkrd.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gtzpljkprq.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdwwhkvx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gtpmilivun.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtaxwbqlzn.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gtrbfhlxuz.html

[T44] Perl：条件
来源：http://dali.jyoumei.cn/Article/details/gtdwkrbmni.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtpzeldczl.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtozmfxbwp.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtttukromi.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtbaytiojr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsmyosxiv.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtcznvwbjt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtyajewojq.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtpqzwcvri.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gtkrqfjuse.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gthzmwgvnh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtihnrqrmg.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtcrmlqllw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gteducqqon.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gtmprqtohk.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtbyozcnvo.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezzlugdi.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gtbpnhuyfm.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawwthoni.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtlffzrjou.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtgcyozmxl.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtxzuiczwk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gtjhxppmav.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtvewswisb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuosesln.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gtrpnwilwm.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtqmndycol.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gtrlhqgjvo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtznjyjvzl.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtjazkioww.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtmnqempfs.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gtdgcytmzb.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gtkswrogmz.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtbrvcnxqg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gtalacmlpi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjkzuqnfa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtlmrdotwf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtiokvqlmn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtzknihsev.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtzmcdoksn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gthmyvatdq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gtjfwqbbik.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gturqtltsg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtkofeilie.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtixmignur.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtdcosmlle.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gtrjaddlze.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtnhiomwsj.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtytktvmbc.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gthmkytjmw.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gtxuwszbkz.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtwdlzzcpf.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gtauaiydpz.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gtfsaqumqz.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gthrigauui.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gttafrluzn.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtvtixzkhe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gtlqrijeyc.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtmlbtxjie.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gtvcfjbhco.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtkxvwektf.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtcsudgmyr.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtralnqqzb.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrxuiqpw.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtwxuluvsb.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gttbeplftr.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gtjngysatu.html

t = time.perf_counter()
来源：http://dali.daria6918.cn/Article/details/gtboofwklt.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigufen.top/Article/details/gttqirtcss.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtwwilegfs.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gtrwmzvwdm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gtgyohwigq.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gtaqykhdmj.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtmcwurvml.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gtqgtoseco.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtdjboajwy.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gtyfgdiwjy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.c1oappe.top/Article/details/gtzkqpujos.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtegynwlpf.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtuvghtimv.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtnkowcypv.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwdwjeck.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtkkdobjah.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.meibo888.top/Article/details/gtsoiavcvp.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gttqgwbyda.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtnozfjuup.html

[U25] Py：CSV 按字典读
来源：http://dali.ehwqpu.com/Article/details/gtxhekcqnw.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtljoqjxms.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gtcdaahqka.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtkfvrixeu.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtibqnnprx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gtkltxglfy.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvkhvkln.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtmwdtdmdf.html

[U29] Py：属性校验
来源：http://dali.hammf.cn/Article/details/gtyiuvaoaq.html

@property 与 @x.setter 配合
来源：http://dali.wangshuangyany.cn/Article/details/gtskdtxvky.html

[U30] Py：数据类
来源：http://dali.vqdsnc.cn/Article/details/gthyceljmv.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtpqnfqwwh.html

[U31] Py：单测
来源：http://dali.ivvv.top/Article/details/gtsiyytcay.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtevvocqkk.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtwmcfcrap.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtudrmbndw.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gtrqozidut.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shuidangran.top/Article/details/gtqeyedqif.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtygexjhvn.html

chardet.detect(raw)
来源：http://dali.vqdsnc.cn/Article/details/gtufilsitk.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gtpnzknbba.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fengsongda.top/Article/details/gtrjkybxme.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtfcwsonak.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gtqiolboax.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gtlndsrhmz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangdashe.top/Article/details/gtjkakbnhr.html

[U38] Py：获取脚本所在目录
来源：http://dali.daria6918.cn/Article/details/gtrdnailtt.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gtbzuoivvu.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gtlinahbdg.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gtilqmlngb.html

[U40] Py：打印到标准错误
来源：http://dali.gotoacloud.top/Article/details/gtmpxmrkfe.html

print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtdkdjipsn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfsqqblv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtmxmelecv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.316326.xyz/Article/details/gtrdouhapr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ivvv.top/Article/details/gtkagusydj.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtjeflpjnh.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gtnczigedv.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtlhetjpax.html

declare(strict_types=1);
来源：http://dali.yongpay.top/Article/details/gtuvprmgzl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtbhfguzeu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtqbadyaxn.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gtqjtatlkf.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gtsalblhvj.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gterlevqpf.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtsdclyffi.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtozyeciqp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jlsjyb.cn/Article/details/gtkkhclxjc.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gtyqhtfsuy.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gtjidkbqjc.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxinkj.top/Article/details/gtjrvygzad.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpwkeaufu.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtcmzzhwar.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gtfapjsfvj.html

[U52] PHP：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtsgulnpor.html

$double = fn($x) => $x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gttysoujuf.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gtadgypmsd.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtgswjoqbn.html

[U54] PHP：空安全调用
来源：http://dali.guowangkeji.top/Article/details/gtgakvwlow.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gthigjuevl.html

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gthzpudtcl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jianghu66.top/Article/details/gthbhjffsa.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gtovzmjtbw.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtijytbtdi.html

[U57] PHP：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtfntisycx.html

"值: {$a}"
来源：http://dali.ivvv.top/Article/details/gtamrkzbez.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gtbkvpvvug.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gtegtnqjxt.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtvoxqnvfe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtjalldkhw.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gtwwxbvqmo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ybcxt.top/Article/details/gtipwmsmhi.html

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gtmrcpnhii.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gttyiaipbw.html

[U62] PHP：日期对象
来源：http://dali.jqgfzy.top/Article/details/gtsynwtarm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gotoacloud.top/Article/details/gtwhiessgp.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gtvwbfhjtw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yangfankeji.com/Article/details/gtcskiedjw.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gtnniopfvn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gtuywteufh.html

[U65] PHP：会话
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyturpas.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gttdzsznok.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtjhzlnocj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gtzoxcoyae.html

[U67] PHP：处理文件上传
来源：http://dali.ppjwa.cn/Article/details/gtkzzfauie.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sufxvd.cn/Article/details/gtmmdhnxpt.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtvucplztd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gtirmkpxup.html

[U69] PHP：PDO 预处理
来源：http://dali.xziqi.cn/Article/details/gtqttesxla.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jyoumei.cn/Article/details/gtesentjmw.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsazmvrxq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.mhx1999.top/Article/details/gtsdjlbcms.html

[U71] PHP：抛出异常
来源：http://dali.hnqzz.top/Article/details/gtmntfbqob.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangdashe.top/Article/details/gtegnfppxk.html

[U72] PHP：写错误日志
来源：http://dali.daria6918.cn/Article/details/gtfosbyjle.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gtbttukvxv.html

[U73] PHP：读取 ini 配置
来源：http://dali.birdmap.top/Article/details/gtlkywjipa.html

parse_ini_file("config.ini", true)
来源：http://dali.gzhubu.top/Article/details/gtdbtutqzw.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gtmxnjzgah.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtmgdtkzea.html

[U75] PHP：依赖注入
来源：http://dali.ybcxt.top/Article/details/gtsmmlekro.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gtkgovipfg.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gtbukxhwnw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gttppjaels.html

[U77] PHP：模板渲染
来源：http://dali.yuxming.cn/Article/details/gtqydlproe.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gtnimugbqb.html

[U78] PHP：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtxdyhazyv.html

composer require --dev phpunit/phpunit
来源：http://dali.bjfxy.top/Article/details/gthwqkqahm.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gtfqyeaqxy.html

composer require --dev phpstan/phpstan
来源：http://dali.cashguo.top/Article/details/gtycctvwyc.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoyjppqy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gtsagrmkcl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gtiehepbaw.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gthbvwblgz.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gtdkakupqf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sweek.top/Article/details/gtautdvftf.html

[U83] JS：ES Module 导入导出
来源：http://dali.iojbl.cn/Article/details/gtvxhxhfwi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtjnmowapu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqqtiaan.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gtxqqpwspm.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gtlfharunp.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gtinmatrqf.html

[U86] JS：空值合并
来源：http://dali.bjfxy.top/Article/details/gtfielivpu.html

a ?? b
来源：http://dali.xinyue.icu/Article/details/gtcmupoabn.html

[U87] JS：解构默认值
来源：http://dali.jinqigufen.top/Article/details/gttwkgueuf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zdqjudy.top/Article/details/gtyyxesjca.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtmnqwbtku.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtmeqasxcf.html

[U89] JS：数组去重
来源：http://dali.yanxiufei.cn/Article/details/gtrzlnhwxw.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtrtnxjwdi.html

[U90] JS：数字数组排序
来源：http://dali.pycfn.com/Article/details/gtfjdbucpo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtcldxkxvv.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtzuleobiz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqafenny.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gtoroikxiu.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtqcjqyupi.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gthasnbtdj.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtxfskekwz.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gtdqvdomxi.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gtodqaiaco.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gtssevdadn.html

new Promise((resolve, reject) => {})
来源：http://dali.meibo888.top/Article/details/gtfwjdpwag.html

[U96] JS：async/await 与异常
来源：http://dali.tanke756.top/Article/details/gtsfzqoqey.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtkvephfdg.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gtzxxjwzoj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawcekpqb.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtdoqghvdi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gtxoncmsuo.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gtvqqboegb.html

el.addEventListener("click", e => {})
来源：http://dali.gzhubu.top/Article/details/gtehwgotcq.html

[U100] JS：DOM 查询
来源：http://dali.snrcjt.cn/Article/details/gttiftuzwg.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtlhypvwxa.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtbvzbyyfm.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gtshmouzke.html

[U102] JS：本地存储
来源：http://dali.yuxming.cn/Article/details/gtlnjirbgj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gtunglwvmf.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gtmvgcvnyi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cucudq.cn/Article/details/gtmpakzkdp.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfzgxpmx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtgcipphqz.html

[U105] JS：节流
来源：http://dali.meibo888.top/Article/details/gtaaytqluv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gttubvemcb.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtioaamiwg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gtrzpqehqi.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtocjfgubt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtpwucznjk.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gtirgrreyl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gtzygzfxii.html

[U109] JS：数组分组
来源：http://dali.chenjidiqi.icu/Article/details/gtfvgwqjsd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzseuzvtk.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gttoariuvk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gtcbmvyfds.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gtkfuymgrz.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtoddshrio.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gtvwhofelw.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtqmzqkmay.html

[U113] JS：正则替换全部
来源：http://dali.316326.xyz/Article/details/gtbuuqdetm.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtucysxjha.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gtzkgfqgbt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtlqqmlcgn.html

[U115] JS：生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtoadddcat.html

crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtmkevtiby.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gtegedrmcq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtppqvthmm.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtmuwwnneq.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gteeyiaqso.html

[U118] JS：开发服务器
来源：http://dali.haohaochexian.top/Article/details/gtzbkwwhvx.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gtgktimyga.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtmnxgglkp.html

npx vite build
来源：http://dali.zhiwuduotai.top/Article/details/gtdvcmpuzv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gtbvczrsgw.html

import.meta.env.VITE_API_URL
来源：http://dali.gotoacloud.top/Article/details/gtawxteoeo.html


<!-- 参考信息 -->