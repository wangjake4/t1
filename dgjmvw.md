代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtdfbgpzvn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtjnyayubl.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtexmpecoi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtlgziwcuz.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoavedlf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtddpihsjs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gtfbrnzrfy.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtwsmwoomb.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtlgtefvak.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtlqtoxzvb.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtcjrdfzti.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtzeqvcvoy.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtwmdcjvpe.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gthaknytin.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtzkspvkke.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gtkbekreom.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtoiecscis.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtellkerzb.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtugiixazm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gtnfwkfhhy.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtgidfhenw.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtjyjfuqqj.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtlghnrlxe.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgctlmgky.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gtectjrrrk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfevhoef.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekfiqvov.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtteeaigtk.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtzjzzxyts.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtepfuizgy.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdptbrabi.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtrvzgsiur.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gtevdrbtmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtswuovttb.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtaotzgfer.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaupgwve.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gtqmmnawsd.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtjnixoueu.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtapyrzffe.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtfzmhdahu.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtmlysrcov.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmjyalyo.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtwwisegpm.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtydajjuwq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtznystalh.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gthtcpsbbj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gtuesbgzim.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gtrlmkkzbw.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtqcrpnpaz.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtyanjfvdm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpocbfhf.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gtmkuqysdk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtqtfcdpuf.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gtuewxwshg.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtnibbgjji.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gttuvebivs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtbwfucrxd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlxxedczr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtzjoxfssa.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwfuozqkk.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoubdldvl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gtssskhlny.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtkcwtowpy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtlygdwhyu.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtpovthore.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtuvcwerah.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtidorlnlb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.svipenyu.cn/Article/details/gtupkhaqlo.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gtxenmlrmk.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtslfgucju.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtwatcjpqo.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtwqsapsbg.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gtclbkrvai.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gtmnalqzyc.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gtkraqsidn.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gtzzwmbsep.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtfblcfzbv.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gtsxpqxptm.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtezmuijqe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtrrjzjngf.html

[U11] Py：生成器表达式
来源：http://dali.havefunace.top/Article/details/gtxgnbnuku.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gtyeyhhfqo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtwzngkcll.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtkoeqkfkf.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtohzsbras.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqfbmqvh.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gtjirkrvwh.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gtneliktez.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gtrtnnrpho.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gtdonbmjqp.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtzfvychsu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gtcrhhmque.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtegdccvha.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtfagymycg.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gtikazjsnq.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gtenujvcsj.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtbzaltgvt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gttloihjto.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtjaeesyxs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtlhfkgost.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gtevghskik.html

@contextlib.contextmanager
来源：http://dali.yuanzhike.top/Article/details/gtqhtvvnyz.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtfpskczgg.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtkammqrvq.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gtlvthuulw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daxiang520.top/Article/details/gtjsfpnmuo.html

[U24] Py：路径操作
来源：http://dali.daria6918.cn/Article/details/gtkbdlyggw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtohqetxpt.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gtimxnlgro.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlyewxlj.html

[U26] Py：并发下载
来源：http://dali.yuanzhike.top/Article/details/gtqafnltlb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gtcfiiapec.html

[U27] Py：异步 HTTP
来源：http://dali.nanxinkj.top/Article/details/gtzzpeqaxs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgufenzy.top/Article/details/gtllmbvkgy.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtoxkvfolp.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtvbjcupmg.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gtptrmcive.html

@property 与 @x.setter 配合
来源：http://dali.shuidangran.top/Article/details/gtylzsxnnx.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtxcjhebob.html

@dataclass(slots=True)
来源：http://dali.nanxuanxn.top/Article/details/gtvsaldmuj.html

[U31] Py：单测
来源：http://dali.shzxlz.cn/Article/details/gtrbvirtla.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtlivgemjh.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtffcjqthj.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gthfrspcwa.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtaycynuai.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtzhyxcnjc.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gtrsltmjwn.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkpalnev.html

[U35] Py：发送邮件
来源：http://dali.zhengqikj.top/Article/details/gtzjzbrjfo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ivvv.top/Article/details/gtxvcvyoxk.html

[U36] Py：定时任务
来源：http://dali.yvedp.cn/Article/details/gtafxzllng.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gtheashdsr.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gtzzpolieo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gtmlmcvoqy.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gtogxvlhqr.html

Path(__file__).resolve().parent
来源：http://dali.wangdashe.top/Article/details/gtaaftntos.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtyijnpxhd.html

sys.stdout.isatty()
来源：http://dali.gotoacloud.top/Article/details/gtovyteuhj.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gteqwlsoho.html

print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtxivgzfxy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtxnftrvcf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gttuaqjegh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gtpzwcglhq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gtzrojexkv.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gttvtsmxem.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtvmldwcvs.html

[U44] PHP：开启严格类型
来源：http://dali.yonumen.top/Article/details/gtchaposbi.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gtmprypywj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtoxywfwge.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyjazclku.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gticlqbuwh.html

?string $name = null
来源：http://dali.hammf.cn/Article/details/gtbkrsaiag.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gtovifzhnh.html

int|string $id
来源：http://dali.guowangkeji.top/Article/details/gtodveiptb.html

[U48] PHP：纯枚举
来源：http://dali.sysykeji.top/Article/details/gtbiawhgdt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cqqwz.cn/Article/details/gttakalxnf.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gtznwnpiod.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtcrovgksl.html

[U50] PHP：构造器属性提升
来源：http://dali.meibo888.top/Article/details/gtcwtrpkki.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gttgjbxrwh.html

[U51] PHP：数组解构
来源：http://dali.cucudq.cn/Article/details/gtumivigoc.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gtmuryibci.html

[U52] PHP：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gtdflknkda.html

$double = fn($x) => $x * 2;
来源：http://dali.cucudq.cn/Article/details/gttjtadjxy.html

[U53] PHP：空合并运算符
来源：http://dali.jlsjyb.cn/Article/details/gtruomoacp.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gtydgsuupu.html

[U54] PHP：空安全调用
来源：http://dali.sweek.top/Article/details/gtoynmsonm.html

$obj?->method()
来源：http://dali.chenlongwang.top/Article/details/gtvpnhscqx.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gtbbugzjog.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtpsjyqlxn.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gtthdebbzu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtzghexuni.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtuozznrhp.html

"值: {$a}"
来源：http://dali.pengpengdd.cyou/Article/details/gttmrfijig.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlfyifgv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbjbapwss.html

[U59] PHP：自定义排序
来源：http://dali.sweek.top/Article/details/gtfzostfhv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtetmybgbb.html

[U60] PHP：JSON 编解码
来源：http://dali.sysykeji.top/Article/details/gtdpmygvhg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtuhkggilu.html

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gtdrnypcxv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtyeiqgsde.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gtzspvontk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigfzy.top/Article/details/gtkwonsabm.html

[U63] PHP：文件读写
来源：http://dali.hongshengwenyu.top/Article/details/gthfwmnbwa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yanxiufei.cn/Article/details/gttdmgsqtv.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gtvntulrzo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtowhdfkms.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtchgtuwth.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtzbkxruwd.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gtdvxlerum.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gtxuapjbud.html

[U67] PHP：处理文件上传
来源：http://dali.sysykeji.top/Article/details/gtzxjyyxju.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.0kj1m.cn/Article/details/gtudosvews.html

[U68] PHP：PDO 连接
来源：http://dali.daxiang520.top/Article/details/gtdnpdchmm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.9152youxi.cn/Article/details/gtwyaxwhba.html

[U69] PHP：PDO 预处理
来源：http://dali.fzhhl.top/Article/details/gtyntkcmsi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tian-w.cn/Article/details/gtfwhiusse.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gtqutwupmf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gtdvbmavvx.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtdqputrry.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxinkj.top/Article/details/gtnnidqhal.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtxtewtofn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gtqvsiskws.html

[U73] PHP：读取 ini 配置
来源：http://dali.fzhhl.top/Article/details/gtvezkwpxp.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gtydfutrii.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtnpfaqjzl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcebpaat.html

[U75] PHP：依赖注入
来源：http://dali.pengpengdd.cyou/Article/details/gtoeswohdj.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gtwjiixoyr.html

[U76] PHP：简单路由
来源：http://dali.andypj.xyz/Article/details/gtayofaumd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuanzx.com/Article/details/gtrcjclbee.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gtpxudjjzg.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gtchpypyzp.html

[U78] PHP：单元测试
来源：http://dali.9152youxi.cn/Article/details/gtslnsgstt.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gteiaobxhb.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gtqbxqpgih.html

composer require --dev phpstan/phpstan
来源：http://dali.yongpay.top/Article/details/gtpoewohit.html

[U80] PHP：代码规范修复
来源：http://dali.yanxiufei.cn/Article/details/gtxmqgofye.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gtfcfidiqe.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gtyjzzawfp.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gtpqfkexyh.html

[U82] JS：package.json 脚本
来源：http://dali.yanxiufei.cn/Article/details/gtbvsjafvg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gtlwemlakf.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258.top/Article/details/gtcooxsdpg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtwuzupjxg.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gtvozddbie.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtzdluzzhg.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gtjjbovqjm.html

a?.b?.c
来源：http://dali.yj202588.top/Article/details/gtixtcgjgp.html

[U86] JS：空值合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpusdzlqh.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtuglmocnt.html

[U87] JS：解构默认值
来源：http://dali.aibaodan.cn/Article/details/gtagmyodll.html

const { a = 1, b = 2 } = obj;
来源：http://dali.haohaochexian.top/Article/details/gtyowwjkkl.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gtjxqzvshq.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcytdoiap.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gtnlqerhdc.html

[...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gteadrkuho.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gtbbobnjew.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtmzzzxhxl.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtstzroyzj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gtopnizjpv.html

[U92] JS：深拷贝
来源：http://dali.yongpay.top/Article/details/gtjrrgodkj.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gttrntmfhl.html

[U93] JS：模板字符串
来源：http://dali.wangdashe.top/Article/details/gtvdynfcdp.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gthodjgymb.html

[U94] JS：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gterjbkmud.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gtgvilmcec.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gtlmyktqht.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgufenzy.top/Article/details/gtsnlsqyrp.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gtlqqddayt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtguyxucxq.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gtdsbxnjby.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtwoxejzwm.html

[U98] JS：fetch 带 JSON
来源：http://dali.xylfe.cn/Article/details/gtziaayfzc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hfpthk.cn/Article/details/gtiuthtibw.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtldsixjyf.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gtrtguykgq.html

[U100] JS：DOM 查询
来源：http://dali.hammf.cn/Article/details/gtlwxvyqbn.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gtprrqgobo.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gtftiwsihc.html

el.classList.toggle("active")
来源：http://dali.xuetiantiany.cn/Article/details/gtvslbayca.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gtdzgyglow.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gtqfrdldeg.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtecisyuii.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gtezrpqilv.html

[U104] JS：防抖
来源：http://dali.nanxinkj.top/Article/details/gtrkqtoiww.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysniyjkk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtjqehzjto.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gtvyxixsjq.html

[U106] JS：日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojehlmmv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtpgbylzww.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gtstegqtny.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtayoxwllk.html

[U108] JS：随机整数
来源：http://dali.ppjwa.cn/Article/details/gtouubtrlw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gtoxupyprj.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtgugowzss.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtwetkjfbo.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gtevgwjlvy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gtuojjcdyd.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gtyikkweyy.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gthnllxyrz.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtjgqprcsj.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtttzhlpvu.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gtjskyujhk.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtfxlsvind.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gtjlbdomhz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtqdumztwt.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtosufzolb.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtgvshfgfs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtlzauceyv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aizwys.cn/Article/details/gtkkbppwej.html

[U117] JS：单元测试
来源：http://dali.ydzc1.top/Article/details/gtymxuawcl.html

npm i -D vitest;  npx vitest
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlikkeot.html

[U118] JS：开发服务器
来源：http://dali.bjfxy.top/Article/details/gtcpgdmayw.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gtcfepcdhr.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gtkmzzewhx.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gtkaelqdxp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtxtpstvmj.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gtjomiiosj.html


<!-- 参考信息 -->