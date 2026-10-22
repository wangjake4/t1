代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gtinebyymm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtjkfxgncy.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtsutaftpl.html

$s =~ s/old/new/g;
来源：http://dali.pycfn.com/Article/details/gtzcdfdthb.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtphoedves.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxtuqhof.html

[T50] Perl：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtrkghnalh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shangyingyoupin.top/Article/details/gtysnfebfo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtyietukwu.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gtgbnsfyvb.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtrfdpkqul.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtqhjywjbl.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gtpezgjcuq.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtmiupjfcs.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtwyhmztia.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtvqbeomgh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtboxbeajz.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtihqztjzr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gttcavohbw.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gtradlwbqr.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqnygmuu.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtuakcclnf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtzneebuqk.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gttstdgaef.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtajzdqcha.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gtyltmldqc.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtelwjttzs.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gttqjcwuki.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gtojwiwqxa.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtshcbyeif.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtxhkteblj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxzltctzl.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtrhomlytl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gthuofoihw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtrfxgdiiy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gttlboukbt.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtwpwyxdwf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gtcgrjkunf.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtfnqluwcq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtlatpqnce.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gtiuecglsv.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtkuimowfu.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtbyhkebtv.html

{**a, **b}
来源：http://dali.xinyue.icu/Article/details/gtkkehyxmb.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gtzotxuhim.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gthdakdfry.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtnffipoks.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtdduaorcv.html

[U09] Py：字典取最大值的键
来源：http://dali.9152youxi.cn/Article/details/gtmnbjtomx.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtavgjffxu.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtpbnexfxe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.0kj1m.cn/Article/details/gtmgyqptqo.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gtqsoxojuh.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtpelytnvn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtzgazsvru.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gthutijbby.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gtpyketggr.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtsbgcdrsn.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gtuqmtgrxm.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxlskntj.html

[U15] Py：高精度计时
来源：http://dali.guowangkeji.top/Article/details/gtablvgihw.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gtvpmacyaf.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gtairidsxa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtwckyqzro.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtdmtidfox.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtxrvwogfv.html

[U18] Py：预编译正则
来源：http://dali.jianghu66.top/Article/details/gtvfsmppsh.html

pat = re.compile(r"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtynjwiyqz.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gtxxafljfq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtaissopsi.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtawkywxxs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtyzfdxcvg.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gtnjuilqma.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtffkjmuxn.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gtlubhdajx.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gtnwquzrzm.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gtbwtxvzrq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yangfankeji.com/Article/details/gtzntjcnky.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gtobobaczr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtsrvhzdpf.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtgntninlz.html

csv.DictReader(f)
来源：http://dali.jinqigfzy.top/Article/details/gtejtjotvp.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gtoazaqcmz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtnaflznsh.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtkwhcsyxr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtqotpibhl.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtmdwmxvqw.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gtzvjouyzb.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gtfxwnajbg.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtkhdorkcm.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gtkizxiboc.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtmmciznxi.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gtmgwtglzf.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gtzkxuzaws.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gtvsqpsrus.html

ruff format . && ruff check --fix .
来源：http://dali.xziqi.cn/Article/details/gtyxjxenaf.html

[U33] Py：打包发布
来源：http://dali.yongpay.top/Article/details/gtkysqfqfy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gtifwztbxe.html

[U34] Py：判断编码
来源：http://dali.shangyingyoupin.top/Article/details/gtjqtltsps.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gteuynsvcq.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gtivbgfehe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gtmcacyptm.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gtdixluzon.html

schedule.every(10).minutes.do(job)
来源：http://dali.sysykeji.top/Article/details/gtiprthmpj.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnugxwzb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfpwihoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gtbhprgbnq.html

Path(__file__).resolve().parent
来源：http://dali.gotoacloud.top/Article/details/gtqtynnngd.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gtmmtztjmq.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtpwdxugqt.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gtkgjwbaiu.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtbjdkwlwi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gtobagigpp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtrwumdprf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gtsxufdiuo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cdnleiting.top/Article/details/gthdagfyub.html

[U43] PHP：声明命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtbaocmydd.html

namespace App\Http;
来源：http://dali.xinyue.icu/Article/details/gtrympeonb.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gtbnqodgto.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gtpivzazhu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gtevnvnfdl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtlgufubuj.html

[U46] PHP：可空类型
来源：http://dali.jyoumei.cn/Article/details/gtsbyfixds.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gtkqtdwvch.html

[U47] PHP：联合类型
来源：http://dali.pycfn.com/Article/details/gtstsjfhbf.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gteyuewlvj.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gtbvxpwlfw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gtvhvniago.html

[U49] PHP：只读属性
来源：http://dali.aibaodan.cn/Article/details/gtdamhfubd.html

public readonly string $name
来源：http://dali.jqgfzy.top/Article/details/gtmkirqdcd.html

[U50] PHP：构造器属性提升
来源：http://dali.xylfe.cn/Article/details/gtrdjxwjjq.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcauwsqga.html

[U51] PHP：数组解构
来源：http://dali.cucudq.cn/Article/details/gtcdjzcmtn.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gtqouiahtq.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtootauibq.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gtnkzodxjn.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gtkjebthvb.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtqhgzdnkg.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gtzvrlmqrj.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gtqwnvlsvc.html

[U55] PHP：match 表达式
来源：http://dali.jiagoushi.top/Article/details/gttqsogyjx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtmbkzquuq.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtvepfbvfi.html

f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtlyconzhj.html

[U57] PHP：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtnognmeeq.html

"值: {$a}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrxmafeo.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gturvmeowq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gotoacloud.top/Article/details/gtmczcqxpm.html

[U59] PHP：自定义排序
来源：http://dali.daxiang520.top/Article/details/gtvqczzdjh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtwwaazzzr.html

[U60] PHP：JSON 编解码
来源：http://dali.wangshuangyany.cn/Article/details/gtjcufazbd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gtkjbiteys.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gtqksdzoyx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtzpyojxkr.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gtvlejbgyi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gtgnayzyaf.html

[U63] PHP：文件读写
来源：http://dali.jiagoushi.top/Article/details/gtyvpqxmzw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gtilguyekw.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtavbdjvrc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuxming.cn/Article/details/gtnoovvrtw.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gtswdvjapu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pycfn.com/Article/details/gtcmaxebdz.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gttzxyfxzl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzgljchi.html

[U67] PHP：处理文件上传
来源：http://dali.hammf.cn/Article/details/gthnkvvqjk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hongshengwenyu.top/Article/details/gtlwewphog.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gtbppxehvi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgfzy.top/Article/details/gttrlmnafe.html

[U69] PHP：PDO 预处理
来源：http://dali.zhongyouzk.top/Article/details/gtnwtkamjx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.vqdsnc.cn/Article/details/gtgeblnmav.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gtedngaeyf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hammf.cn/Article/details/gtvqbfdapl.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gtvetbwjqb.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtsindewaq.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gtjpdqbgmd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gtkliuqdqr.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gtyjrxckch.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqtokjej.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtpwioekna.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigufen.top/Article/details/gtyjccthvv.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtvmvpjfrf.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gtyxemgekl.html

[U76] PHP：简单路由
来源：http://dali.jinqigufen.top/Article/details/gtfedozldv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tian-w.cn/Article/details/gtzorqdvja.html

[U77] PHP：模板渲染
来源：http://dali.cashguo.top/Article/details/gtupzdmmba.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gtgigkkkpf.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gttclmggmb.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gtgfpexzwi.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gtmdcksxvc.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gtahjlbwyv.html

[U80] PHP：代码规范修复
来源：http://dali.gaohongyu789.top/Article/details/gtzgltaige.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pycfn.com/Article/details/gtqdwbmhil.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gtasmrsibu.html

npm init -y;  npm i express
来源：http://dali.xuanzx.com/Article/details/gtxkhlfuvn.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gtergmlzrt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hfpthk.cn/Article/details/gtkixhawnt.html

[U83] JS：ES Module 导入导出
来源：http://dali.shuidangran.top/Article/details/gthpxvccdm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtpfeaxypp.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gtnrfpxmwz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenlongwang.top/Article/details/gtffrshacb.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtyafvdqnw.html

a?.b?.c
来源：http://dali.ehwqpu.com/Article/details/gtztyspgrh.html

[U86] JS：空值合并
来源：http://dali.hongshengwenyu.top/Article/details/gtgxbyervr.html

a ?? b
来源：http://dali.shangyingyoupin.top/Article/details/gtsuusyoqo.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gtipgdzcys.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aibaodan.cn/Article/details/gtrquqdcle.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gtpgaowvha.html

{ ...a, ...b }
来源：http://dali.c1oappe.top/Article/details/gtvrkchors.html

[U89] JS：数组去重
来源：http://dali.sysykeji.top/Article/details/gtnelkbosz.html

[...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtvcuelwnh.html

[U90] JS：数字数组排序
来源：http://dali.jqgufenzy.top/Article/details/gtrfgtkljd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtjvepgtum.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gtzqltnfnt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ivvv.top/Article/details/gttcfhzzhl.html

[U92] JS：深拷贝
来源：http://dali.ydzc1.top/Article/details/gtcxfnzwhl.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gthngjaakv.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gtzbxpkrtj.html

`共 ${n} 条`
来源：http://dali.feifeiyinyue.top/Article/details/gtkwxhpxqr.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gthlhsiiwo.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtoaezafdg.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gtdluqidlg.html

new Promise((resolve, reject) => {})
来源：http://dali.jlsjyb.cn/Article/details/gtpzjumygk.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gtblljzivm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtaitmhceb.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gtbxmpnhvw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtumzoipma.html

[U98] JS：fetch 带 JSON
来源：http://dali.zycfv.cn/Article/details/gtpldnnyld.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cashguo.top/Article/details/gtqjdkundc.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gtabfeiwcb.html

el.addEventListener("click", e => {})
来源：http://dali.ehwqpu.com/Article/details/gtjpjqssgj.html

[U100] JS：DOM 查询
来源：http://dali.aizwys.cn/Article/details/gtxphqhjko.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtehuvxqza.html

[U101] JS：classList 操作
来源：http://dali.daria6918.cn/Article/details/gtuogotfdz.html

el.classList.toggle("active")
来源：http://dali.daxiang520.top/Article/details/gtrbelnbio.html

[U102] JS：本地存储
来源：http://dali.zhengqikj.top/Article/details/gthtssscoa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sweek.top/Article/details/gteukufwkr.html

[U103] JS：定时器
来源：http://dali.chenjidiqi.icu/Article/details/gtibqgcgkl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gtcubipvbr.html

[U104] JS：防抖
来源：http://dali.zhoulong.xyz/Article/details/gtgdavxtzc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtcphjslcd.html

[U105] JS：节流
来源：http://dali.yanxiufei.cn/Article/details/gtbtojhrlh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtojreycih.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gthjafiiqz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tianlin.xyz/Article/details/gtaubdwgrs.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gtfifttwhq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtbqgtrqjf.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtycotrvns.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhxjvxfs.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gtynsxkkid.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtnturanek.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gtwlmpdqvu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gtbtaqwqdp.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtxwdroxsc.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gtgfwhlsei.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gtrqjvtjzu.html

"7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtdpsvticw.html

[U113] JS：正则替换全部
来源：http://dali.haohaochexian.top/Article/details/gtcxnvbzws.html

s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvwupfio.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gtrkdrbjlu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtbythtuno.html

[U115] JS：生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtekbuauin.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gthmtvlpzo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gtxubhtkih.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtphtwkagh.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtswqunwio.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gtevtddhvk.html

[U118] JS：开发服务器
来源：http://dali.gaohongyu789.top/Article/details/gtlxxqmsdz.html

npm i -D vite;  npx vite
来源：http://dali.fengsongda.top/Article/details/gtcvymaitl.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gtesvjnwqs.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gtmcqytwqr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ybcxt.top/Article/details/gtfzodxgsv.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gtngncdltb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpyujvrpt.html

统计汇总
来源：http://dali.andypj.xyz/Article/details/gtjdjblmbv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtafgqcuor.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gthirfacwt.html

Python ......... 252
来源：http://dali.yvedp.cn/Article/details/gtsywusifx.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gtjoecznup.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtiawwpgmp.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gtdmoowhrx.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtcfpzrrrl.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtpiicxhjl.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtxwtzbahe.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegmbucbp.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtwonfhncj.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gtlkvykcmn.html

SQL ............ 90
来源：http://dali.hongshengwenyu.top/Article/details/gtwnfrfzjy.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtppeukxsb.html

Kotlin ......... 15
来源：http://dali.tianlin.xyz/Article/details/gtpcschcyw.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtzfcsygxs.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtkmwxidrp.html

Perl ........... 10
来源：http://dali.sxryk.cn/Article/details/gtsrsfejwx.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gthqifpynb.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtmngwlnoo.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtdpfoxqgh.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gtgaulbycx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtbsavrlkw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyjxygje.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtgltdoyao.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxjdeamk.html


<!-- 参考信息 -->