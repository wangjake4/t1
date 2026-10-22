代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.hfpthk.cn/Article/details/gtyyakhrsn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtmjtohwno.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtmhvfqlto.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtxpaxantp.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gtmqsoowsh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjlqydlov.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtyzdtierq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtnxvifygz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsnpsgyae.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gthndmuzzi.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtfmlhddop.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtvnugjimd.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtdsdexhdk.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtsinygeqv.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtxacujcwp.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtronqcsvq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtaplqqsjr.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtzqsrapav.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtlohuklcm.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtqmhnekmt.html

case class User(name: String, age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwieyxgpj.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcluqdbgp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtgixeqxag.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gtskrnzedh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtwchadgac.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gtgvrsqcqe.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtnnpcrvsf.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gtxnigebbu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.smart0.xyz/Article/details/gtywbqhbdi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwprqxjrd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtxdybgbiz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjyqzahuw.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gthcujjpgn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gtlocrxjes.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtqtpizoqp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtylguyxtd.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtwqixulrh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gttreivmrh.html

[U04] Py：变量调试打印
来源：http://dali.cdnleiting.top/Article/details/gtmruckqoz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtkkvgyrvi.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcjftyjj.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gthxmbdfdx.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gtkykehdko.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtojfdgzsj.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtjnifkcnl.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtigwooiaa.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gtzeoeyoty.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtcvsqkivl.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gtpyrjgazb.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoozwqnm.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtwfasdluv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gtstuldaju.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtwwbrwtoi.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhmipjaz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gtqxvtmhts.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtdiitallw.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gtxzuupety.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtujhbhnge.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gtzxlqxnhn.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gtwbeexsfd.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gttfryynbd.html

t = time.perf_counter()
来源：http://dali.gaohongyu789.top/Article/details/gtmngogvmq.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gtrtdzqsex.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtuclwlhmd.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gtphjsqdvz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtzhezlhde.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtexpcdhzp.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtxfsiqeka.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtoiikkcec.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jianghu66.top/Article/details/gtlodlmsws.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdvkvkgs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhjtqpxd.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gtyvcrhmjt.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtloskggqt.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gtwqpinibo.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtjuuqzanm.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtnvzunreh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gtjybdsgxw.html

[U24] Py：路径操作
来源：http://dali.yangfankeji.com/Article/details/gttasezjlw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtrmnoatbx.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtrtvsuoyw.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gtkpmkxyht.html

[U26] Py：并发下载
来源：http://dali.ydzc1.top/Article/details/gtsquehumz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gtnzjolnje.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gtkzxbxyjj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hfpthk.cn/Article/details/gtuprwneca.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gtguypyxdu.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gtzxjbolvp.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtsyswobni.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gtatcfbizm.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtjsckyvqh.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gtjngibptq.html

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gtnhlybvlp.html

python -m pytest -q
来源：http://dali.gogol.net.cn/Article/details/gtlrkqecio.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gtxxpdnkzp.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtsjecukjc.html

[U33] Py：打包发布
来源：http://dali.sweek.top/Article/details/gtrxklazvb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cdnleiting.top/Article/details/gteuhuxnrc.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtvopynxoz.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gttfcresvg.html

[U35] Py：发送邮件
来源：http://dali.mhx1999.top/Article/details/gtwmiskqow.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmagmssb.html

[U36] Py：定时任务
来源：http://dali.sweek.top/Article/details/gtwmxyoiym.html

schedule.every(10).minutes.do(job)
来源：http://dali.tianlin.xyz/Article/details/gttuqrhuqm.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtyeiwshag.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gtfbgdtgye.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtldnypzhm.html

Path(__file__).resolve().parent
来源：http://dali.zhoulong.xyz/Article/details/gtxrtfpznx.html

[U39] Py：判断是否在交互环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinattgcz.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gtcuakczpo.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gthynrnbdr.html

print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtmdnxsqtm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gtdthelmnx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.meibo888.top/Article/details/gttqqeamit.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixixkbnc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shangyingyoupin.top/Article/details/gtrppouboe.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtyfxprcmu.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gtelfdcgrr.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdummefrh.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtejonovce.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeppacxz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtoqnvapth.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfleizmjz.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gtqtssqhqy.html

[U47] PHP：联合类型
来源：http://dali.yj20258.top/Article/details/gtsztzambp.html

int|string $id
来源：http://dali.gogol.net.cn/Article/details/gtixdgwjkm.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gttypbcmti.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gtrjdvzgoc.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gtbhafippj.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gtveggsucg.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gtrmtzftpm.html

public function __construct(private int $id) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnpmdkdsg.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gtczswidge.html

[$a, $b] = $arr;
来源：http://dali.guowangkeji.top/Article/details/gtuinmsilu.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gtfqnzxwju.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtapzixqsv.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gtxieluhla.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtvjhmrqdu.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gtslvxoxqf.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gtpnvcamxs.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gtaupxkmyo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtjiakxiuz.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzdblxxx.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gttfznudme.html

[U57] PHP：字符串插值
来源：http://dali.havefunace.top/Article/details/gtlxbpmqqh.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gtkcgfwfws.html

[U58] PHP：数组三件套
来源：http://dali.sufxvd.cn/Article/details/gtflogolab.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.mhx1999.top/Article/details/gtpjgtqmyx.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gtkcwczpas.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtvdyybepr.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gtjyubodzv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.haohaochexian.top/Article/details/gtreoejmbw.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gtinujstnt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtvdcrcwcs.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gtptosazor.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrflmqym.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtegbeetiy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgsxwlxn.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtpgxdqaod.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtcwnvliba.html

[U65] PHP：会话
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwqgbehf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcgmnsgr.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghkgqkpa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gtisifamtu.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gtfqydvzia.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtupreflsu.html

[U68] PHP：PDO 连接
来源：http://dali.shzxlz.cn/Article/details/gtigrfnfil.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gtfzolkhzh.html

[U69] PHP：PDO 预处理
来源：http://dali.ivvv.top/Article/details/gtkzugmskr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nwbrower.top/Article/details/gtshfmipsd.html

[U70] PHP：PDO 事务
来源：http://dali.zhixingplan.top/Article/details/gtvfcxxzus.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtanmacjyd.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrwkbxzo.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gtipjjngfl.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gtjmlugark.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gtaignfoom.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydvaltwj.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtituoudjq.html

[U74] PHP：读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtkersjxof.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gtzdmpemou.html

[U75] PHP：依赖注入
来源：http://dali.bjfxy.top/Article/details/gtxxdxglpi.html

composer require psr/container
来源：http://dali.shuidangran.top/Article/details/gtevedhntg.html

[U76] PHP：简单路由
来源：http://dali.yj20258888.top/Article/details/gtuilhyuwe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dashuyun.cn/Article/details/gtqebiudrr.html

[U77] PHP：模板渲染
来源：http://dali.quarkkingdee.top/Article/details/gtmksfvlgt.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gtxhoxsnht.html

[U78] PHP：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtzfqqugya.html

composer require --dev phpunit/phpunit
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskqigbqz.html

[U79] PHP：静态分析
来源：http://dali.yj202588.top/Article/details/gtkmksucae.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbteiebtb.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gtmclaiebm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiitfuvpa.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtpjvekwuj.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gtcqsqfwgt.html

[U82] JS：package.json 脚本
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrciydgl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gthhifjdta.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtqwthjpmg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtegaxncgn.html

[U84] JS：CommonJS 写法
来源：http://dali.shzxlz.cn/Article/details/gtofqapwgy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.meibo888.top/Article/details/gtylsrbfje.html

[U85] JS：可选链
来源：http://dali.ybcxt.top/Article/details/gtezacwkgy.html

a?.b?.c
来源：http://dali.yuxming.cn/Article/details/gtesaemxyi.html

[U86] JS：空值合并
来源：http://dali.0kj1m.cn/Article/details/gtewjijadw.html

a ?? b
来源：http://dali.yj202588.top/Article/details/gtkswxygte.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gtnyvltiaz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.meibo888.top/Article/details/gtiawejwla.html

[U88] JS：对象展开合并
来源：http://dali.ehwqpu.com/Article/details/gtzrftgxmv.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gtknzusgry.html

[U89] JS：数组去重
来源：http://dali.hnqzz.top/Article/details/gtdmcmzczf.html

[...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtnewvfijj.html

[U90] JS：数字数组排序
来源：http://dali.tanke756.top/Article/details/gtsavwqomf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gttoabhohh.html

[U91] JS：对象键值遍历
来源：http://dali.quarkkingdee.top/Article/details/gtvxrimqge.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dashuyun.cn/Article/details/gtxyepxcte.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gtltwrkzhf.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtgrcdugdq.html

[U93] JS：模板字符串
来源：http://dali.jinqigufen.top/Article/details/gtyvpawchn.html

`共 ${n} 条`
来源：http://dali.svipenyu.cn/Article/details/gtksxeaanp.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gtqapgriry.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtjmsqjnkm.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gthtwivrnh.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gtuowhdhkj.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gtqzbelths.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrevluzyn.html

[U97] JS：并发请求
来源：http://dali.nanxuanxn.top/Article/details/gtkkkvpgpi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtfquycb.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gtexthxfqo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ivvv.top/Article/details/gtnvgkpcva.html

[U99] JS：事件监听
来源：http://dali.zdqjudy.top/Article/details/gttbilzmpi.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtbxdoflaz.html

[U100] JS：DOM 查询
来源：http://dali.hammf.cn/Article/details/gtfzwncxsa.html

document.querySelector(".item")
来源：http://dali.sufxvd.cn/Article/details/gtjbutkysw.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gthoocjamv.html

el.classList.toggle("active")
来源：http://dali.yj20258.top/Article/details/gtuchowtrq.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gtndguypid.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gtkipvilma.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gtetwmfuov.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gtxvrcjhng.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtjbvkeukc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtmaxohdfl.html

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gtiqthiwla.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwqneyku.html

[U106] JS：日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtbxqaeaei.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.meibo888.top/Article/details/gtetebkrwj.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gtfndfvdji.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtpmnecssq.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtwnirwgmc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gtfhvpxdsn.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfdanfyh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtsdzkaldx.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gtyxggslax.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtikcifkxq.html

[U111] JS：对象转 Map
来源：http://dali.yvedp.cn/Article/details/gtbnqwxyfj.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gtiawqlzev.html

[U112] JS：字符串补位
来源：http://dali.gaohongyu789.top/Article/details/gtiwwigkwr.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtiflpltkl.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gtvcqpbjgv.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtuqejczed.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gtdefvlwtm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtdfjfzhhv.html

[U115] JS：生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtfsakpxor.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtqvzlkajx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gttjdavxfn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtnhgrqrzu.html

[U117] JS：单元测试
来源：http://dali.xziqi.cn/Article/details/gtirvoerhy.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtnprpxhvs.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gtozyjnwak.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gtoilqhgtx.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gtfowmdhfz.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gtthbxlhae.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gtddcfgvjy.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtkkgulxve.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmldzatnx.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gtvqnlijfs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjgsocynw.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gtjtmzmdim.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gtoutdpazy.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gtfjgxeodw.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gtahtvbnvx.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtarqfjbtr.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtlyphfmli.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtjylmqffh.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtjfhhlqhn.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtwuvussfc.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gtonfcxmor.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gtxflvckem.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gtqsogfwbf.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gtpssaxljv.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gtyahbdhoq.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtmlyaqoal.html

Lua ............ 10
来源：http://dali.gaohongyu789.top/Article/details/gtiqplnkwu.html

Perl ........... 10
来源：http://dali.iojbl.cn/Article/details/gtnofqlulx.html

Scala .......... 10
来源：http://dali.tanke756.top/Article/details/gtwtpedbyz.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtligkrxhf.html

合计 ........... 2106 条
来源：http://dali.havefunace.top/Article/details/gteeofdatv.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gtmcjolbon.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtzuaxgmgi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtwqczszga.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtspjtpqsp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtkthhtxlu.html


<!-- 参考信息 -->