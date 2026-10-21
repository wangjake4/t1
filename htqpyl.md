代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtsjexpqer.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtvxnujavf.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtvkiucbke.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtngtdcdhh.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtektcqxgt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtkypxhfvt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gtvfgjbeky.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtqznwoodu.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtzdpcgotr.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtrgxywijr.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gtmxdcjoyr.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gteuwzdlfw.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleucgbli.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gtisokheyb.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtximiuqis.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gthjwstiio.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtsqlgarhq.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtcdzgtqnh.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtecbkwzgc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtvmtjauqt.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtguuowzcg.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtirqkrpot.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbrehowx.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtcrxqeljp.html

[T45] Perl：数组遍历
来源：http://dali.ivvv.top/Article/details/gttflujoau.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtcyaullns.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtojwaivxg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtzerkchuf.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gtizbvcnzp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtqprgyboj.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtpdetgtuv.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtcpremmod.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtcbehsyut.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gttikhtfod.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtdyuyhvyk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gtcgwsivdc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtpynrapad.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtmavnrncs.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtvifiamnp.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtkheniasc.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gtmhqpxrzz.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gthxcskwpg.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gttsnjfslf.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtccdhkmba.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpaisnruz.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtaiaaskkw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gtmurhmkbj.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtuyjotdwc.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gtopycmhsd.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtswnugwcu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtihhufbuh.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtsckncgga.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtgodwkdvg.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmovofefz.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtixrronbt.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gtqmkprroz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gtodvcvrbl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmnmkfgxg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtjbqokkcu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtevoajqab.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtpputqtiz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtxgphmrro.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gtnciadyfc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gteghxmxrq.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gtxmuzngwu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtoildgomh.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtkzfcpdwh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtelkuudte.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gtgnqrhlkn.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtfgwidbuc.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtpohfmhoq.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gtztvmgonn.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtvrquudmg.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gtjdtekyro.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gtzoiktcas.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtqvzlrjei.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gthqgfifpg.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtvoqntrll.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtsqrcdzsi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zdqjudy.top/Article/details/gtsorjwxos.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtmyhbwyry.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gtmapyqayz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gtdmvohsny.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtmslhkdsy.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gtdoepxevz.html

deque(maxlen=10)
来源：http://dali.xuanzx.com/Article/details/gtfwzxmxpo.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gtfexhevwm.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqeqqhbu.html

[U15] Py：高精度计时
来源：http://dali.guowangkeji.top/Article/details/gtiexvtxyw.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtgufmxcoj.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gtccybkrlg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gtdagmsekx.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtvcurlyvh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gtfniduuzo.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtcfakomuv.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gtczluvfwn.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtgcuixidj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtqzusrqnm.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtkzobuanj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtvhhyhebs.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gtbtikljaa.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtrbkbechu.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gtewmqmtfz.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtfmnxcvkk.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtcvzwuyiz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtneggkzpv.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gtflbvzswx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtojbevxzf.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtyscgnpfx.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gtaiewkjnk.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gtbmtndoii.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sufxvd.cn/Article/details/gtxhsnpblv.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtetwqprsz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gtcoldfidl.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gtwyiclawz.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtrvpvrpkz.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gtcbrptlvj.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtpcffjaeh.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtncrojscj.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtuuqliagq.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gtybbiektv.html

python -m pytest -q
来源：http://dali.shangyingyoupin.top/Article/details/gtipevsqbd.html

[U32] Py：代码格式化
来源：http://dali.ivvv.top/Article/details/gtlrqxwdcw.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtbruyybne.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtmrksgiig.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjonyaszm.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtpxzgqenc.html

chardet.detect(raw)
来源：http://dali.yj20258888.top/Article/details/gtcuzpxofv.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdhhsvzu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdowkjtsj.html

[U36] Py：定时任务
来源：http://dali.smart0.xyz/Article/details/gtmugbhlsw.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtaljiaptx.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gtnllkpnci.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gthhokqnrm.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gtfaiimaci.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gtigrztgex.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhoulong.xyz/Article/details/gthitwrldj.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gtsknpyxgr.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvbiwmwt.html

print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaidzedx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhrqheyu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigfzy.top/Article/details/gtomikicku.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtnaudepnb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gtyjbhpcxc.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtcgkhcxel.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsdlnzfi.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtdzriqcgd.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtglwmkrxr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gttxcoodgf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtevhwvyex.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gthfhgdzju.html

?string $name = null
来源：http://dali.zhengqikj.top/Article/details/gtbnrplcdd.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gtliazeuvi.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gtdhyrjpcp.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtraeoyvky.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gtfnehcjec.html

[U49] PHP：只读属性
来源：http://dali.tanke756.top/Article/details/gtqapapurj.html

public readonly string $name
来源：http://dali.xziqi.cn/Article/details/gtvjpsanbz.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gtxtfvcxlu.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtpqgvywuo.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtkasvgsun.html

[$a, $b] = $arr;
来源：http://dali.aibaodan.cn/Article/details/gtxaitimgb.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtebscjbbn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtwvglgkxd.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gtsabqxiib.html

$v = $a ?? $b ?? "default";
来源：http://dali.havefunace.top/Article/details/gtzoiqxtzo.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gtqlptvmlm.html

$obj?->method()
来源：http://dali.chenjidiqi.icu/Article/details/gtwpbrfatn.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkblrzveq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gtpwuwyfeq.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtoakrvsqn.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtwhtnjavk.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtnhfpjdlo.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gtjjfwxaer.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gtxdrcvmug.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jiagoushi.top/Article/details/gtflatwuif.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gthllhrpdl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtezfsvgea.html

[U60] PHP：JSON 编解码
来源：http://dali.dianchejie.cn/Article/details/gtpcpfbwjo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.svipenyu.cn/Article/details/gtcfneicuw.html

[U61] PHP：正则
来源：http://dali.chenlongwang.top/Article/details/gtxroqdsfx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtsuunytbo.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gtwbpjwblm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtwptwtuun.html

[U63] PHP：文件读写
来源：http://dali.snrcjt.cn/Article/details/gtdfqfhqob.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pengpengdd.cyou/Article/details/gtnnhndxim.html

[U64] PHP：目录遍历
来源：http://dali.jianghu66.top/Article/details/gtkcgikthv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtjwschvoo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtkvoxegjm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtlycrtswj.html

[U66] PHP：设置 Cookie
来源：http://dali.daria6918.cn/Article/details/gteayfxyga.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fengsongda.top/Article/details/gtpjqqdwzy.html

[U67] PHP：处理文件上传
来源：http://dali.ivvv.top/Article/details/gticzbnfiu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jiagoushi.top/Article/details/gtscskorvt.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gttsdjazra.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhixingplan.top/Article/details/gtxffuuiqg.html

[U69] PHP：PDO 预处理
来源：http://dali.yonumen.top/Article/details/gtjyzfajgt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gtczzhvoky.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gtswxknhmz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gtfgilmcvt.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gtkgbqixdg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtjcxmaiml.html

[U72] PHP：写错误日志
来源：http://dali.zhongyouzk.top/Article/details/gthalcumya.html

error_log("失败: " . $e->getMessage());
来源：http://dali.mhx1999.top/Article/details/gtpkswusvt.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gtqvfnijdr.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtwriharzk.html

[U74] PHP：读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtomactjec.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtfiwcnorp.html

[U75] PHP：依赖注入
来源：http://dali.nwbrower.top/Article/details/gtcwkfqttd.html

composer require psr/container
来源：http://dali.yj20258.top/Article/details/gtxlqpyljc.html

[U76] PHP：简单路由
来源：http://dali.hywenlv.cn/Article/details/gtmasnjxiw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jyoumei.cn/Article/details/gtvwccwauh.html

[U77] PHP：模板渲染
来源：http://dali.xuanzx.com/Article/details/gtitorqluv.html

composer require twig/twig
来源：http://dali.cdnleiting.top/Article/details/gtvsocwqjc.html

[U78] PHP：单元测试
来源：http://dali.aizwys.cn/Article/details/gtjbavxjgr.html

composer require --dev phpunit/phpunit
来源：http://dali.yuxming.cn/Article/details/gtkxaopttt.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gtrmuoyekt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhongyouzk.top/Article/details/gtwdobakju.html

[U80] PHP：代码规范修复
来源：http://dali.tianlin.xyz/Article/details/gtalcrtidf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ywan-chungtsiang.top/Article/details/gttspnrdgc.html

[U81] JS：初始化项目
来源：http://dali.hfpthk.cn/Article/details/gtxchgxrbx.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiriyesay.html

[U82] JS：package.json 脚本
来源：http://dali.shangyingyoupin.top/Article/details/gtejjtssqo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aizwys.cn/Article/details/gtnypaprgz.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gtjcydtyfs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtpjlkpjju.html

[U84] JS：CommonJS 写法
来源：http://dali.jyoumei.cn/Article/details/gtuzgkhukk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gttsbmsaze.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gtfemnxeyh.html

a?.b?.c
来源：http://dali.pengpengdd.cyou/Article/details/gtvowuucdx.html

[U86] JS：空值合并
来源：http://dali.snrcjt.cn/Article/details/gtblqqfsdw.html

a ?? b
来源：http://dali.hnqzz.top/Article/details/gtavoceosg.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gtansytflt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cdnleiting.top/Article/details/gtrmqgmdsu.html

[U88] JS：对象展开合并
来源：http://dali.fzhhl.top/Article/details/gtwesavmsj.html

{ ...a, ...b }
来源：http://dali.kuanghao11.cn/Article/details/gtupsftljg.html

[U89] JS：数组去重
来源：http://dali.yvedp.cn/Article/details/gtzwrqiqhq.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtkkqkhjkc.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gtrbrjnyea.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtdbkfwtzy.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtmhzlevgn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gttixpaoco.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gtdcjoxqll.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfarzmrv.html

[U93] JS：模板字符串
来源：http://dali.sysykeji.top/Article/details/gtweqyzcgr.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gtitnefvuu.html

[U94] JS：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdmuygegc.html

const double = x => x * 2;
来源：http://dali.316326.xyz/Article/details/gtjgcixnlr.html

[U95] JS：Promise 包装
来源：http://dali.hfpthk.cn/Article/details/gtkstentst.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtdhlfeqgz.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gtjjafdvav.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtlcaegkwn.html

[U97] JS：并发请求
来源：http://dali.wangshuangyany.cn/Article/details/gtuvtydwlt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtejmdxlfw.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gtlwkfzjlw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.birdmap.top/Article/details/gtvryebqkr.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gtuqqcsisb.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtrxzwswqu.html

[U100] JS：DOM 查询
来源：http://dali.tianlin.xyz/Article/details/gtodoeuzcv.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtzoyfzfgc.html

[U101] JS：classList 操作
来源：http://dali.yj202588.top/Article/details/gteujayrmt.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyrjavhs.html

[U102] JS：本地存储
来源：http://dali.hnqzz.top/Article/details/gtuvibzzwd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gtnygsbnjn.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gtpgcufnef.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhengqikj.top/Article/details/gtcnahyuwq.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtqbuyjait.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gttceczaun.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtwwfivgiw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hywenlv.cn/Article/details/gtzjugfwxw.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtrglbemfp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.mhx1999.top/Article/details/gtkyjxomds.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gtukpjxvdn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtjlcmfmoi.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gtnaoofydv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gtxclzecyx.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gtbwloxwwt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtpdklkcgz.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtvxdaqrnc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.birdmap.top/Article/details/gtrpqncnbj.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtdwzjafkn.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gtkiwzqjad.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gtwjuwtszv.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtmpofncqa.html

[U113] JS：正则替换全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueanrsig.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gthyqzcuoi.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gtzqscqmpt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtcnvnjkre.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtqujruxgf.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtrpwumouu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gtweqdohwc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gtjxlaciia.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtvdjhnpwj.html

npm i -D vitest;  npx vitest
来源：http://dali.sysykeji.top/Article/details/gtuicooode.html

[U118] JS：开发服务器
来源：http://dali.xylfe.cn/Article/details/gtbvffnpgh.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gtcamlthwf.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gtyhcyphfr.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gtrjczlkun.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtamqakxci.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtjuyxufvp.html


<!-- 参考信息 -->