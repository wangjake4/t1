代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gtrlaoikbj.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gttfixagyv.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gtoqzmutic.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gttqtahpdb.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtpspdyqmk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwqiibatj.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtcoqpmtbw.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtinreeyop.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtminnhdhp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtqnkwjrpx.html

[T50] Perl：逐行读文件
来源：http://dali.sweek.top/Article/details/gtnjdsqbhq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhengqikj.top/Article/details/gtthaucgfh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtqicljaio.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtgbctcqap.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtkpbemhop.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtszrhmxpw.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gtvnmqcyev.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtagjswndn.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtrroffhgw.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtonmicpsf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtpkdotiye.html

[T55] Scala：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtxfqtjvct.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gtechwabbg.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtvkqlluhl.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtyibkcfcp.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtdiuvvgqy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtalyluhid.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gtvglvolev.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gtzcrhsflm.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtttmrhqlg.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtwxhdzsfx.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtvsjghpjv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtsgubfdnt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbborktgw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtbhskagqi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfncoygz.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtrmmxkzbl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gtsdmusrev.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gterakethi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtrhtpmzfy.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gtpqkeakbg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtcrgvmqkr.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtbilcaoap.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqsosicb.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtfcndvmxw.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtjiwtaaxh.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtdlkkwolb.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtxkojcgmm.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gtlfchpokq.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gtjxaadbpe.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtnuaropov.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gtdjrefohi.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtpmtdtswd.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtxmzsonfv.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gthphhwhrf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtpepcwvyt.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtfwqyqpbo.html

(x * 2 for x in arr)
来源：http://dali.ehwqpu.com/Article/details/gtbawchenv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yongpay.top/Article/details/gtkevczyce.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtmycsxgap.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtuarahvlt.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtgkfngkjo.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtrnryzkok.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtonbegmhn.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gtnogeacmf.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtlbgklslt.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gtzjgsaaio.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gtzepnbnav.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtnpbvmzuj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dianchejie.cn/Article/details/gtrufnojuk.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxdiyfjw.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtrhdrtnms.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtsphcabjz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtuwbhevmo.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gtjpkekzjl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtfutiadnr.html

[U21] Py：自定义上下文管理器
来源：http://dali.xinyue.icu/Article/details/gthrvrllzf.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtgwebiusz.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gtumkfihem.html

list(zip(*m))
来源：http://dali.hongshengwenyu.top/Article/details/gtvruzpfqo.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gtmoiirnbt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtbzbldbok.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gtzdupsapt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjmifnzo.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gthhjxaopa.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtospdehnf.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gttchuikyg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtawjkfhpr.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvufrbph.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gtnddcvzgs.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gtreuoxdfm.html

UserId = int
来源：http://dali.hongshengwenyu.top/Article/details/gtcfzjbmek.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gthohjhazw.html

@property 与 @x.setter 配合
来源：http://dali.zhixingplan.top/Article/details/gtsnwrkkve.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gtkeoaxetq.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtanyuvgyr.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gtmfqsdzzl.html

python -m pytest -q
来源：http://dali.yongpay.top/Article/details/gtwujnboms.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtfkyzldvu.html

ruff format . && ruff check --fix .
来源：http://dali.xuetiantiany.cn/Article/details/gtyempozpz.html

[U33] Py：打包发布
来源：http://dali.dianchejie.cn/Article/details/gtigtqmhab.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gtdhqlyoub.html

[U34] Py：判断编码
来源：http://dali.xuetiantiany.cn/Article/details/gtqaoonfjl.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gttvbxvaas.html

[U35] Py：发送邮件
来源：http://dali.ybcxt.top/Article/details/gtwbbmplhp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtgciwbvqj.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gtnkfpjymd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtbkwycvgh.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gtvfwgrnet.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gthrcutdmu.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gtickvcnqh.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gtklctyzgm.html

[U39] Py：判断是否在交互环境
来源：http://dali.sxryk.cn/Article/details/gthkjvcmbf.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gtmgrrxoeh.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gthhrivdyi.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtbgrnscrq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gthvgvmnyk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gtweufesrg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gaohongyu789.top/Article/details/gtlqpifqrk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtvcskuxaw.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gtjvudtcuz.html

namespace App\Http;
来源：http://dali.nanxinkj.top/Article/details/gtkbhmioiq.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gtmzebqglf.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtncyygrox.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gtvmuvdtwq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtqkmgydur.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzctgcnt.html

?string $name = null
来源：http://dali.hammf.cn/Article/details/gtyocwaenp.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiresjdx.html

int|string $id
来源：http://dali.feifeiyinyue.top/Article/details/gtnksdpyho.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gtwjsgdzcv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtgureawor.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gttptcgvrj.html

public readonly string $name
来源：http://dali.cashguo.top/Article/details/gtacnhpdar.html

[U50] PHP：构造器属性提升
来源：http://dali.kuanghao11.cn/Article/details/gtdhshkcib.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gtasebrwvs.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gtnqdtrrgs.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gtlmgzskoi.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtgycvwbnf.html

$double = fn($x) => $x * 2;
来源：http://dali.9152youxi.cn/Article/details/gtpxjjrdxo.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gtbpowdbsr.html

$v = $a ?? $b ?? "default";
来源：http://dali.daria6918.cn/Article/details/gthbnbtiuy.html

[U54] PHP：空安全调用
来源：http://dali.0kj1m.cn/Article/details/gtblbjfiuh.html

$obj?->method()
来源：http://dali.zycfv.cn/Article/details/gtqgjfgqvw.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gthtmacesx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtkbruazyu.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gtahypnnea.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtgquknsal.html

[U57] PHP：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtfhvqaizs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gtrftuhmeo.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtbsjeudyg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.meibo888.top/Article/details/gtusdxczkg.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtqqifxxmo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtmearkmfw.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtpijrxhhi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xziqi.cn/Article/details/gteycqqjiv.html

[U61] PHP：正则
来源：http://dali.andypj.xyz/Article/details/gtbfphjaoe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtnhnyxydk.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gtbqzcdrzh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfnocykj.html

[U63] PHP：文件读写
来源：http://dali.hysaishi.cn/Article/details/gtkdenyvpd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbokseuew.html

[U64] PHP：目录遍历
来源：http://dali.dianchejie.cn/Article/details/gttoyiobum.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gthrmvobqo.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gtvhmfegfr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtdfkejqad.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gtmsqdhwvj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.smart0.xyz/Article/details/gtgbqdrbaq.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gtpkvhfzsd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gotoacloud.top/Article/details/gtknqksyph.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gtvyuewdcf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gtnjdlhdgw.html

[U69] PHP：PDO 预处理
来源：http://dali.jiagoushi.top/Article/details/gtrjtoqljf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gtlwljhzkf.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gtwhnbuwrp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxbcptgl.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gtlcxjifwh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zycfv.cn/Article/details/gtwzwgzcts.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gtjiiotmhw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gthyqfcqye.html

[U73] PHP：读取 ini 配置
来源：http://dali.jqgfzy.top/Article/details/gtvukxkprc.html

parse_ini_file("config.ini", true)
来源：http://dali.chenzaomai.com/Article/details/gtgdsjiasf.html

[U74] PHP：读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtkwiymmbf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gtfrbwzbrz.html

[U75] PHP：依赖注入
来源：http://dali.ivvv.top/Article/details/gtivmxfcdm.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gtojfsoweq.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gturebsjhi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gtzdkuiddj.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gtdoyynyfn.html

composer require twig/twig
来源：http://dali.cashguo.top/Article/details/gtkiinldhe.html

[U78] PHP：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtwowuugft.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtyimxhwbn.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gtglnzvqwd.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gtiqsgrrsj.html

[U80] PHP：代码规范修复
来源：http://dali.guowangkeji.top/Article/details/gthqljrcfg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ivvv.top/Article/details/gtvxppgzan.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtpbfmaans.html

npm init -y;  npm i express
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgebplivl.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtkjtowdyi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gtjxpruiwq.html

[U83] JS：ES Module 导入导出
来源：http://dali.quarkkingdee.top/Article/details/gtbimvszeg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtngaubilq.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvcltkgs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgirixjqv.html

[U85] JS：可选链
来源：http://dali.zhengqikj.top/Article/details/gtjuqiwhjl.html

a?.b?.c
来源：http://dali.nanxinkj.top/Article/details/gtxpixiaqj.html

[U86] JS：空值合并
来源：http://dali.ppjwa.cn/Article/details/gtzpdbxgmz.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gtfjxpcuiu.html

[U87] JS：解构默认值
来源：http://dali.andypj.xyz/Article/details/gtydsuecpc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gtgiaxjpyn.html

[U88] JS：对象展开合并
来源：http://dali.zhongyouzk.top/Article/details/gtlqlcoxqn.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gtnvxftztj.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gtzflskjri.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtlrcdhctw.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gtjttdljlx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtccotbmot.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtjaifszqj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shuidangran.top/Article/details/gtajhoadbo.html

[U92] JS：深拷贝
来源：http://dali.cashguo.top/Article/details/gtpthmtsuc.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtusedhtxm.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtgwjoehvf.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gtssedxbco.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtffevslve.html

const double = x => x * 2;
来源：http://dali.quarkkingdee.top/Article/details/gtlyuqtuzt.html

[U95] JS：Promise 包装
来源：http://dali.jinqigfzy.top/Article/details/gtqtspgvbr.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gtgqfbodfg.html

[U96] JS：async/await 与异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhqedlan.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtwwtvmtqx.html

[U97] JS：并发请求
来源：http://dali.redwolf501.top/Article/details/gtdrclxcuu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtlktyiyue.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gthruwdkyi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtcquypzbc.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtolpjfuch.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gtgblmyfie.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gthzfnsnqz.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gtmlegxice.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtjgbktumi.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gtawguadmu.html

[U102] JS：本地存储
来源：http://dali.hnqzz.top/Article/details/gtenmidqfk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtuxfoctqs.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gtybyczfrj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cdnleiting.top/Article/details/gtyfbrmesg.html

[U104] JS：防抖
来源：http://dali.pycfn.com/Article/details/gtmcmrqvuk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtwzpartoz.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gtpqbpnlhj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtrrlcxzhw.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gtdralqoan.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gtwstohqbw.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtzuqkugyo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtvuzkiivi.html

[U108] JS：随机整数
来源：http://dali.shangyingyoupin.top/Article/details/gtvbqdgaxd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jyoumei.cn/Article/details/gtynbusmfx.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtzuuwwftd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtrgyrqeur.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gtgdbllqco.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtmhlxntxy.html

[U111] JS：对象转 Map
来源：http://dali.xylfe.cn/Article/details/gtgkhumdnn.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcdejuxk.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gtwuhqmrgo.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtpilsyyal.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtezjdmtnb.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeiinqlg.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvwzfkkt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtvaqjkyho.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtvmlsuuot.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtttrpkvab.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gtdxnuinpn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gtlcrxdyoa.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gtysgdhekg.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gtlcqrrwiz.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gtwoefmcik.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtemtdjjtp.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtebpkbsae.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gtdggnngwd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.snrcjt.cn/Article/details/gtxsryaoac.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtssxtgshg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxskdvxvo.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gtljdzvsfn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbamtnczd.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gtmzuuzogp.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gteatjkzyi.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtdwoymlpp.html

JavaScript ..... 252
来源：http://dali.ehwqpu.com/Article/details/gtdqzgsfbz.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gttkqyqobw.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gtaehnvwro.html

Go ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoipizkfl.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtrbbceyhx.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtwmzujdqn.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gtzjgbatyy.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gtunpvvyrx.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtkcsuwqzj.html

Bash ........... 80
来源：http://dali.fzhhl.top/Article/details/gtgckgtwnm.html

Kotlin ......... 15
来源：http://dali.yuxming.cn/Article/details/gtkoftxevs.html

Swift .......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhpkyopc.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gtcxyjgmbj.html

Perl ........... 10
来源：http://dali.sweek.top/Article/details/gtbbrbktdy.html

Scala .......... 10
来源：http://dali.snrcjt.cn/Article/details/gtxxdpsllz.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtdtkmvjkw.html

合计 ........... 2106 条
来源：http://dali.nanxinkj.top/Article/details/gtuttgvtos.html

按章节统计：
来源：http://dali.jinqigfzy.top/Article/details/gtnobhinqg.html


<!-- 参考信息 -->