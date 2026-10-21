代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtelqvisiv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gtyhhhmurl.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtmxvyblyc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtewzrrzaj.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtriawrmds.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gtbbpguujn.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gtlgzowqzh.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gteoujhaza.html

[T37] Lua：字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtrhimwoiz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtxcpwgszd.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gtrlnulsix.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gthgbtufwv.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtotmqatha.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gtbsrrpsnr.html

[T40] Lua：元表
来源：http://dali.dianchejie.cn/Article/details/gtapohxeim.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtialdhcvl.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gtshbvqada.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gtnxalqkil.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gtyshzdrbe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gtkuywozex.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtvygjimzg.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gtvofjnkfa.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gtgepxgxac.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtpkweinvl.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtpqkwvpqc.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtfnjucsvj.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gthujzdnqz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gtlkihjufb.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtjmvjnwjw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtkuvfpbxu.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtrkvhdnvu.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtietkkoir.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gtwamfefax.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtfzttnxvh.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtzrgvewsk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozllyjzo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gtmgsvxfic.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtlordttgo.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtinwdkvvh.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtnnuyecfj.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtdmucdajd.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtjfkmmofl.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtyjfuytjs.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtbnahbtwd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gturrrwqui.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtnpzmmqnj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtsbzhxeeg.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gtaxivjrtx.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtoninlnzk.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoasdznt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gtwxuqskek.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gtofvnehir.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtsnekqrvi.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtzsthgvnb.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtwknnkuso.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gtquolnonn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtonloaoji.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjrtnqauk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtummuwtak.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlsmknowb.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gtcqqokmfi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtaesfbcnq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtozixsbjn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gtfktizsua.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtlglzkhkj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gttszbvraw.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtmsqhrgcv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtmjpzqfnb.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gtyhbtqkqr.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtcatltrav.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gtwayewrwg.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtknelwhuz.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gtzdveisec.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtstgxagvq.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtzozyffpn.html

[y for x in nested for y in x]
来源：http://dali.pengpengdd.cyou/Article/details/gtmaudxaor.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtphtbfgrp.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtfzdvtmkg.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gtzekbeqcm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gtccxcsapr.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gtfulampvo.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswwcsdoa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtmbvlmppv.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gtirxzhgfk.html

[U13] Py：固定长度队列
来源：http://dali.hfpthk.cn/Article/details/gtlnrugyze.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gtgghnrzbz.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gtmganiixz.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gtxwmvbtqf.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gtuovmbxgu.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtzwtbkedr.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtjamfsxvs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gthqjrdqiq.html

[U17] Py：初始化日志
来源：http://dali.aibaodan.cn/Article/details/gtxazbukhs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gtvfjyjxzg.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gtswzzyonc.html

pat = re.compile(r"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtmeuqhgvh.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcfufoyy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gthahzvnhq.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gtksrcroqd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gtdaonfarc.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtpbpkvraw.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtfackjfbh.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtyxpkbyol.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gtuwuuuuku.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmkdliqrw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtplnapqie.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gtyavejojd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtbfiwyfbh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gtpxlvjfdm.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtmhexkbif.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gtveqimqhl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ehwqpu.com/Article/details/gtehndgqvc.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gthwchuadt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtlhcvujdw.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtuipkjvsi.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtfwpxzyth.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtosnbsbpa.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gtgryloonc.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gtluywyuha.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtpgowncrk.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gtkwnxgmwt.html

python -m pytest -q
来源：http://dali.pengpengdd.cyou/Article/details/gtvivncmxr.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gtbsvrfmpg.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gtoyzqetal.html

[U33] Py：打包发布
来源：http://dali.yonumen.top/Article/details/gtskezvysy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gtynfsbltw.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gtpvptunyz.html

chardet.detect(raw)
来源：http://dali.meibo888.top/Article/details/gtrjcthwid.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gtwjheypgx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gtoodlavtb.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtzjfkazkx.html

schedule.every(10).minutes.do(job)
来源：http://dali.tanke756.top/Article/details/gttkvvdglx.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gtwmlceife.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgufenzy.top/Article/details/gtgrlcegcb.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gttqzyhksw.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gtyidzonnu.html

[U39] Py：判断是否在交互环境
来源：http://dali.ydzc1.top/Article/details/gtyfcufsjx.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gtjuakjcwr.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gtchnmvxku.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gthzmuilvy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtwhgbiihb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gtyjjluuiw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yueranfly.top/Article/details/gthrhvevyq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gtvbphdlyf.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtczpccgfi.html

namespace App\Http;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxfbhmzj.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gtucexkpvc.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gtyadclrxj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gtizyxgnuq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtlsdqjibu.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtyvtogrnz.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gthnmguxlv.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gtszhiytjt.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gtjyxpgkgf.html

[U48] PHP：纯枚举
来源：http://dali.xziqi.cn/Article/details/gtwaactgbo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gthvxadewk.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvpmvcmq.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiopjrxl.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gtmeilpuyq.html

public function __construct(private int $id) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvpwbqxu.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gtmgytuitz.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtvvxoalhl.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtxxeoiaet.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gtfuqkchxw.html

[U53] PHP：空合并运算符
来源：http://dali.hnqzz.top/Article/details/gtedwbnvgz.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gtfturxaqe.html

[U54] PHP：空安全调用
来源：http://dali.ivvv.top/Article/details/gtdomjghif.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gthdzkazyl.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gtdlsmdrio.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtafgqsjuv.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gtzotqosrd.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtxmbtprsn.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gtoerraycw.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gttfxyrojt.html

[U58] PHP：数组三件套
来源：http://dali.cucudq.cn/Article/details/gtnvogjqnn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gtoqbszvby.html

[U59] PHP：自定义排序
来源：http://dali.xuanzx.com/Article/details/gtwelzfzti.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gttmmlojsy.html

[U60] PHP：JSON 编解码
来源：http://dali.cqqwz.cn/Article/details/gtgyyfsufw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenlongwang.top/Article/details/gtyomktxab.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gtbvlbgnse.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtwacdheiu.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gtqtgqwoke.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhiwuduotai.top/Article/details/gtpzpbvgya.html

[U63] PHP：文件读写
来源：http://dali.jqgufenzy.top/Article/details/gtnhphvyiz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtezzczbfw.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gtyzkosgzt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtxhtytxjy.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gtwvaesnnz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtqcjoyrur.html

[U66] PHP：设置 Cookie
来源：http://dali.hywenlv.cn/Article/details/gtwjnfengy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtbxihdpsw.html

[U67] PHP：处理文件上传
来源：http://dali.xuetiantiany.cn/Article/details/gtogvlnoeh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gtfwncjysi.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtzhfetvkk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjypquzs.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gtrjhkwxqd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gtfcjgtdxs.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtadkrjrac.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhoulong.xyz/Article/details/gtwttnbxmi.html

[U71] PHP：抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtyyyupjub.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gtfooiddno.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gtyrladoif.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yongpay.top/Article/details/gtfnhkghaw.html

[U73] PHP：读取 ini 配置
来源：http://dali.haohaochexian.top/Article/details/gtspqfbzpa.html

parse_ini_file("config.ini", true)
来源：http://dali.nwbrower.top/Article/details/gtxunbqkkf.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtxdzrjnxg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fengsongda.top/Article/details/gtykogquau.html

[U75] PHP：依赖注入
来源：http://dali.redwolf501.top/Article/details/gtyjrmohhq.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtisyhnfxv.html

[U76] PHP：简单路由
来源：http://dali.316326.xyz/Article/details/gtqmjcohxq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gtqesvtpbu.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gtgmucorqq.html

composer require twig/twig
来源：http://dali.cheryme.top/Article/details/gtjjcgavnh.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gtqsmdqynl.html

composer require --dev phpunit/phpunit
来源：http://dali.cucudq.cn/Article/details/gttonflrwj.html

[U79] PHP：静态分析
来源：http://dali.tian-w.cn/Article/details/gtpxditlhh.html

composer require --dev phpstan/phpstan
来源：http://dali.bjfxy.top/Article/details/gtqodrnqmm.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gtxtksqcvf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuetiantiany.cn/Article/details/gtkktgohbj.html

[U81] JS：初始化项目
来源：http://dali.cdnleiting.top/Article/details/gtqowngybf.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtroixlbzm.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuunjisff.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuanzhike.top/Article/details/gtwmselpnj.html

[U83] JS：ES Module 导入导出
来源：http://dali.gogol.net.cn/Article/details/gtblvjhzxv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258.top/Article/details/gthwwcsykh.html

[U84] JS：CommonJS 写法
来源：http://dali.redwolf501.top/Article/details/gtatffczxv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtpyajuroc.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtwrhreckf.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtrelimdaj.html

[U86] JS：空值合并
来源：http://dali.yongpay.top/Article/details/gtbvyhxnoq.html

a ?? b
来源：http://dali.sufxvd.cn/Article/details/gthiaexifn.html

[U87] JS：解构默认值
来源：http://dali.fzhhl.top/Article/details/gtgxqgpmyr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gtsibtzpvj.html

[U88] JS：对象展开合并
来源：http://dali.gzhubu.top/Article/details/gtzcbzivcz.html

{ ...a, ...b }
来源：http://dali.fzhhl.top/Article/details/gtqggjlwji.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gtkdijrzft.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtpjycibek.html

[U90] JS：数字数组排序
来源：http://dali.aibaodan.cn/Article/details/gtzbdcxmft.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtkhxoqblp.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtglrnhzsn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xylfe.cn/Article/details/gtxyyhfbgh.html

[U92] JS：深拷贝
来源：http://dali.jqgfzy.top/Article/details/gtmdkinipw.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtsglhowqf.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gtrgkgvecl.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gtqgiqnlyv.html

[U94] JS：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gtddwdcvxs.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtzxxmkoeb.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gtbydjruok.html

new Promise((resolve, reject) => {})
来源：http://dali.gzhubu.top/Article/details/gtzwipmakg.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtcrwrsvha.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtdmgfzgwt.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtwhiawnpf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gthyaifyjx.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdusmmrok.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvfsqbms.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtyqpkcjur.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gtcuqdudyt.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzgakqdy.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gtapwhmxmj.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtxqwrzbfc.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtiaiqhftn.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtreqtoqfe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtpvjfmgny.html

[U103] JS：定时器
来源：http://dali.quarkkingdee.top/Article/details/gtcrjjlswz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gtuxmaxtty.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtjwcvypiw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtdvxhggpp.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpzwkmwb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtjqsgskxu.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gtmpjrluqa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtslvjseyn.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gtnoyhxkih.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtwawftxas.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojhetdqo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtmvcfrihn.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtvzsnnmdq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtfjmqusyo.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwhmuvgq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonahukdh.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtggduaimk.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gtirchnwbh.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gtghcdgzlp.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxegqyng.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gtquuifkmk.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtfksgpprm.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gtpdikwdww.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtgwmhgsht.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtohkgzfee.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtbzosbzdh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gtocjjvmbz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxfciyqqx.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtgleiayeo.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtmkqqunny.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtyurjzfla.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisbefuqg.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gtxbowdyzv.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtbmjllazb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yongpay.top/Article/details/gtsgycncuy.html

import.meta.env.VITE_API_URL
来源：http://dali.havefunace.top/Article/details/gtbjwpjqtt.html


<!-- 参考信息 -->