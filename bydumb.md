代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtjpeqhmov.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtpqilcxbr.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtfvglcclt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtmscicgxx.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gtdcorfdll.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gttvwozvjm.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtixdefaas.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtjvuykedp.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtrpohikms.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtzzpmjpkn.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcgeufyz.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtkqnzbcwy.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtwuoostnd.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gtkjgdbbdm.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gtbklwtgwg.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtimsghevo.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtasccahdc.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtaamireqr.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gthsqgojfc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gttxwkazrp.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhqdqnkh.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gthgjqnver.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gtvcpsexal.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtoyrupovn.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtafiositk.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gttqqiyfyv.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtpdehfbrk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gtzeoafbuh.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gtcjxavklp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gthtzgxmxl.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtcyzuoozu.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtyocioyky.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtjdkbbghp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtazbcvxsi.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtkzqltngd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gtkltblqkc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtkpiicglq.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtwegcawwc.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtfpixtukq.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtgexduksj.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtpkwrqlum.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtqditkqyv.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtemetzgba.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtnzxmnlcc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gttdsrkmxn.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtwdqpzxdq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtfmwksoar.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtxrblgghz.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtreoznlyq.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtalnunnif.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gteavrzrgs.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gtmcquytvo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtuhrnuxnt.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtjxgwtbue.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtsytuiklq.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvenycjue.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gttfvmvtgj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmhtvhfsz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtsltglpix.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyqrsudlb.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtounzcnub.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gterbzhhgx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtmufkcjli.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtczumkbin.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtrykddbmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gtbohegivf.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gtierwqjiu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gtugkvrtkg.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtpnixllcf.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtpnsqmawp.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gteuxqdcpd.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtxrkziitl.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtbbdkbpxi.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gtpavuzamw.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gtwvnfdwjc.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gtibtacgrp.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gtuespkyuc.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gteginurty.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtvjoapvxf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gtmscvxmks.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gttqhualoa.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gtmzlbjjto.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtnsphipqt.html

Counter(arr).most_common(3)
来源：http://dali.jinqigufen.top/Article/details/gtmsrlamks.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtnzbmovfz.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtfpvhzcjh.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gtrypfpfvy.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtvxcnwzmd.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gthuxvhqzz.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gtpuronjnq.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gtzjgxbbno.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtavouwfjk.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtfbikkfhk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gtveaiaxtx.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtdhqrrbrg.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtejqhymer.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gtcaminfvr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqysceftz.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtnyrmanrp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.c1oappe.top/Article/details/gtxitvxism.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtlwkurnvq.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gtqeksemcg.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtbfjvydbj.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtvwiiguus.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gthwwyylxd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtljpldtuv.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtztyjwnyi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtzibsbpqo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsvenkxd.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gtysdhgohz.html

[U26] Py：并发下载
来源：http://dali.mhx1999.top/Article/details/gtgomjzwfp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zycfv.cn/Article/details/gtzudqnpwe.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gtxjpxqdro.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gtxdeoncoy.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtpqelwlpx.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtwxavuylu.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gtivuicokb.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gtyrqczgbs.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gticlmxlhp.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknifgoai.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gtforwpaxn.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gtcbnarzhj.html

[U32] Py：代码格式化
来源：http://dali.0kj1m.cn/Article/details/gtawiepehf.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtsarmlrsv.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtolocwubv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hfpthk.cn/Article/details/gtubzhbbla.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtmdnfawmu.html

chardet.detect(raw)
来源：http://dali.birdmap.top/Article/details/gtirykxfgk.html

[U35] Py：发送邮件
来源：http://dali.hfpthk.cn/Article/details/gtooniiine.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gtmlbnyiwt.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gtewzkedof.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gteqemeiyc.html

[U37] Py：读写 Excel
来源：http://dali.zdqjudy.top/Article/details/gtqsfmchvz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangshuangyany.cn/Article/details/gtzrcirnvt.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gtgtysdxux.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gtvuignoxo.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gtuszaoykq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtxqpytrhx.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitzrlgcw.html

print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gthctvkxqo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jianghu66.top/Article/details/gtoislzepq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtidcvijop.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtzfatvh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhtkrohm.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtysgwfqnt.html

namespace App\Http;
来源：http://dali.xinyue.icu/Article/details/gtspejcsag.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gtqhqmbanm.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gthigkjous.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnxiangtu.top/Article/details/gtcigfedtk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtfppykfiz.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gthjuficqg.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gtbbxibcjh.html

[U47] PHP：联合类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcifzdky.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gtsmwfvisp.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtxvvgfqdv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfjscurt.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtxcvlvdto.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gtglbijvnc.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gtbuyxmdtx.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gthcftabzh.html

[U51] PHP：数组解构
来源：http://dali.ppjwa.cn/Article/details/gtjnjrdzil.html

[$a, $b] = $arr;
来源：http://dali.nwbrower.top/Article/details/gtwvhsdjwa.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtcqxefald.html

$double = fn($x) => $x * 2;
来源：http://dali.ybcxt.top/Article/details/gtazevjjnc.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtmxxmzipg.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtbmngrzoy.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukkavtvv.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtiltjkysw.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtcwopqhvy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtpapliezp.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gtrbwrnyrk.html

f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtvykqjbkg.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtwxsmirlv.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gtchxlxhsq.html

[U58] PHP：数组三件套
来源：http://dali.yuxming.cn/Article/details/gtztibwkkc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yonumen.top/Article/details/gtcjsezjke.html

[U59] PHP：自定义排序
来源：http://dali.9152youxi.cn/Article/details/gtlnxxpzxh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gthprinshs.html

[U60] PHP：JSON 编解码
来源：http://dali.meibo888.top/Article/details/gttzmhjzzj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxuanxn.top/Article/details/gtoezcjcve.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gtxgigwjkn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gthiqsgavn.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gtltffvlpx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtkgbmqyap.html

[U63] PHP：文件读写
来源：http://dali.cqqwz.cn/Article/details/gtjwqxgqtd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nwbrower.top/Article/details/gtwujpsibd.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gtietnbnzg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gthirefltl.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gtlwikwvfq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtxdexurqn.html

[U66] PHP：设置 Cookie
来源：http://dali.hnqzz.top/Article/details/gtxzocuocx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cashguo.top/Article/details/gtqfrbelxh.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gtrneebuts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinghuilouyu.cn/Article/details/gthkyndmba.html

[U68] PHP：PDO 连接
来源：http://dali.tianlin.xyz/Article/details/gtpwvqjtix.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gtavmnmlei.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gtqohjmrfz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gtokiuhbgv.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gtakrvxdqt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.andypj.xyz/Article/details/gtaejhgfrc.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtlrzzajna.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtyoohxnps.html

[U72] PHP：写错误日志
来源：http://dali.gotoacloud.top/Article/details/gtlxffktnk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hfpthk.cn/Article/details/gtlmodzysp.html

[U73] PHP：读取 ini 配置
来源：http://dali.ehwqpu.com/Article/details/gtonzmdrwi.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gttvifmnpb.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtyikyunts.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtegpbtajq.html

[U75] PHP：依赖注入
来源：http://dali.pengpengdd.cyou/Article/details/gtdpcuarkr.html

composer require psr/container
来源：http://dali.yj20258.top/Article/details/gthaslglng.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxpunbmg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gttvfmfezd.html

[U77] PHP：模板渲染
来源：http://dali.pengpengdd.cyou/Article/details/gtrqxdwwow.html

composer require twig/twig
来源：http://dali.yj202588.top/Article/details/gtrywvdmhy.html

[U78] PHP：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtkkhcmocs.html

composer require --dev phpunit/phpunit
来源：http://dali.smart0.xyz/Article/details/gtyqbpmbxl.html

[U79] PHP：静态分析
来源：http://dali.xuanzx.com/Article/details/gtnlpdeigx.html

composer require --dev phpstan/phpstan
来源：http://dali.sxryk.cn/Article/details/gtpggduvuf.html

[U80] PHP：代码规范修复
来源：http://dali.0kj1m.cn/Article/details/gtprrzrdlz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xinyue.icu/Article/details/gtpjyzsqxy.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gtrukmapzu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gtistrbhra.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gtvpfdurzn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gtzhorftgw.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gtujkjgjux.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtvtbxenim.html

[U84] JS：CommonJS 写法
来源：http://dali.gzhubu.top/Article/details/gtslsvtpni.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtgptkpdvh.html

[U85] JS：可选链
来源：http://dali.cucudq.cn/Article/details/gtcxtbbalc.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gtfbshonaw.html

[U86] JS：空值合并
来源：http://dali.yongpay.top/Article/details/gtndvrzxfz.html

a ?? b
来源：http://dali.zhongyouzk.top/Article/details/gtwuerdkga.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gtjtgutgqp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtlowtkfkx.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gtbvmikfhx.html

{ ...a, ...b }
来源：http://dali.hammf.cn/Article/details/gtzypayefk.html

[U89] JS：数组去重
来源：http://dali.cucudq.cn/Article/details/gtpzhbgdfo.html

[...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtqkyqvcvn.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gtiduegcfw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtukkuxtij.html

[U91] JS：对象键值遍历
来源：http://dali.smart0.xyz/Article/details/gtldhmfoki.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gtcwtydrhe.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhudfweb.html

structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gthoafihxt.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gtatlubuti.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gtnwmmawqv.html

[U94] JS：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtraxyiimx.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gtghpeylgd.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtxeaoyomv.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gtzorebcdy.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gtkbhhajel.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxuvaxqo.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtacxotlxr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtxuqsavgi.html

[U98] JS：fetch 带 JSON
来源：http://dali.yvedp.cn/Article/details/gtgckibnmh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtqwdnnvvp.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gtlmwzlrgp.html

el.addEventListener("click", e => {})
来源：http://dali.316326.xyz/Article/details/gtcesjqyex.html

[U100] JS：DOM 查询
来源：http://dali.tianlin.xyz/Article/details/gtcohiryrb.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gtrlzwoyfm.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gtzxtijtwz.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gtljzawhgu.html

[U102] JS：本地存储
来源：http://dali.guannengcc.top/Article/details/gtvcbrcfon.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gtbcffwahy.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gtndjqoaot.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtlzliaaag.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvbxzieb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtxqlwcclx.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gtgvemvtek.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gtnygocbwz.html

[U106] JS：日期格式化
来源：http://dali.tian-w.cn/Article/details/gtledqdusl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgfzy.top/Article/details/gtllvcfwbb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtfqobtrbb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtortcvbnw.html

[U108] JS：随机整数
来源：http://dali.pengpengdd.cyou/Article/details/gtxzbgyohv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtcpwrqyzf.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gtefdiukub.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtdgkgxwoh.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gtqcbfdzxi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gtikglmmax.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtevwjcine.html

new Map(Object.entries(obj))
来源：http://dali.yuanzhike.top/Article/details/gtmkxalenc.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gtrzmelvmr.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtajjiaqby.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtwsbfoouo.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtrjalzmlz.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtczikcusj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtwpkeowvj.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtaaywbuah.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gthtaxiujh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aizwys.cn/Article/details/gtjxqllusy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gtdovdyyos.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtcnnzdggt.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtddmyuvxj.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprmaiwgo.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtlsxdbniw.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gteeffkmbo.html

npx vite build
来源：http://dali.gotoacloud.top/Article/details/gtpencfnau.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gtkcaeqfoa.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtmfevrdcd.html


<!-- 参考信息 -->