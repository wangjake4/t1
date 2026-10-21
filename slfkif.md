代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtwsxliizm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtggdukwzg.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtrtxwjkmv.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gtirowhjhk.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtculgfsxj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtnjxxtoob.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtchuhfkag.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gtbqomuohy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gttyvuhpju.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gtaelpncde.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtvcqnbzkb.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtblhhmveu.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gtvuhltdlg.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtpypjcrce.html

s"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtkocdrazl.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtdvbhrkyn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gtqithhwnr.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtttdisynm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtucrmgthn.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gtdwionvup.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtjmajvfxn.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtraefbamw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gtedsixhzo.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gtjruqamwy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtwotnuttc.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtiqlutwdw.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtmtnoehdn.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtnssmsmsd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gtfnkwhkky.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzadkhhcd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtmrocdzgq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmnqtidsl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtflwlucvm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtabzrnzzc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtqbjnkqbq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtquadzfqn.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtwpbkjnqz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gtynxepgpf.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtqsqgzawd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gtmgchfrzt.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtfkwgjetl.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtqshyjtif.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtgezvsrqm.html

{**a, **b}
来源：http://dali.shzxlz.cn/Article/details/gtnvrvelbc.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gtysbpzvfb.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkmwfpoz.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gtdldocvyd.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gtfhcbkkej.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gtahrjdsjk.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtdqodmbln.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtzgdqmsui.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtqibnak.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gtfzwqdkcv.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gtnmmnjimb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gtajqylakw.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gtywmggrqr.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gtxwhwdkoe.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gttkxlfleb.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldssmnep.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gtrvuufbkw.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtafnfslpo.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtdwmjafga.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gtnwcdrcyf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuetiantiany.cn/Article/details/gtxvvdcyzw.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtbhqmkbfe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gtpewonjqm.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtjlcspadq.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtkazuuavd.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtlpjtgwtp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtlrztlikk.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtpvhomnck.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gtuaticpjg.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtfonmnoum.html

@contextlib.contextmanager
来源：http://dali.zhoulong.xyz/Article/details/gtjbyjnxdj.html

[U22] Py：矩阵转置
来源：http://dali.wangdashe.top/Article/details/gtylyblzku.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtlujcdwbc.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gtnlhgulpw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cheryme.top/Article/details/gtyzmqqafk.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gtjkgbkvvl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtysjruyth.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtprqafhgf.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gtilizvkow.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gtgjpmvxih.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gtphjvbagr.html

[U27] Py：异步 HTTP
来源：http://dali.yongpay.top/Article/details/gtprxbtcsu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.mhx1999.top/Article/details/gtzhjcuhtb.html

[U28] Py：类型别名
来源：http://dali.xziqi.cn/Article/details/gtyqanidgv.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtsnrgcicv.html

[U29] Py：属性校验
来源：http://dali.shangyingyoupin.top/Article/details/gtmgdtznby.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtbxpkccpj.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gtqjwokfpg.html

@dataclass(slots=True)
来源：http://dali.yonumen.top/Article/details/gtmrctrjck.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gtawcipngi.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtzvasqnxh.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gtgztoarmm.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtnwjlsgkn.html

[U33] Py：打包发布
来源：http://dali.pycfn.com/Article/details/gtqtylazyb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfivwsko.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtzwjjoyma.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtgufhiwly.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gtshlkrzno.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtxysshgvt.html

[U36] Py：定时任务
来源：http://dali.gotoacloud.top/Article/details/gtxezwcjob.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gtxdrqzxru.html

[U37] Py：读写 Excel
来源：http://dali.daxiang520.top/Article/details/gtzkuevcka.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gtilarrjvi.html

[U38] Py：获取脚本所在目录
来源：http://dali.jianghu66.top/Article/details/gtksrbkwmk.html

Path(__file__).resolve().parent
来源：http://dali.sxryk.cn/Article/details/gtulntnhfn.html

[U39] Py：判断是否在交互环境
来源：http://dali.0kj1m.cn/Article/details/gtlutmahrx.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gtovjhxkwx.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gtfwhcgeun.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtemucoewl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hfpthk.cn/Article/details/gttgcxpzpp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtgmpjndwz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gtgujttdzz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwkdukuz.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtzcqsqrvd.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gtroehllcz.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gtsqfjbnmv.html

declare(strict_types=1);
来源：http://dali.jyoumei.cn/Article/details/gtykxwqxpi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yanxiufei.cn/Article/details/gtuahwzdcy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbmkxordd.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtoddvhaka.html

?string $name = null
来源：http://dali.feifeiyinyue.top/Article/details/gtyeqcewer.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gtwjtzttbp.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gthcjkmbcd.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtatkslwps.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcqlnjixl.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gtdeitpmlt.html

public readonly string $name
来源：http://dali.yangfankeji.com/Article/details/gtugmekeqw.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gtacfocnxu.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gtvhpmivuy.html

[U51] PHP：数组解构
来源：http://dali.zhiwuduotai.top/Article/details/gtapwomzkh.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gtehkweinv.html

[U52] PHP：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gtskqtnyfw.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtagjxpgnl.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcfcbsbb.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gtqafwbkrb.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gtohcptscq.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gtqisffhli.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gtvqucqkuk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtifwfoygv.html

[U56] PHP：命名参数
来源：http://dali.yonumen.top/Article/details/gtochnbbci.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtthpjoait.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtkkfwhprb.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gtybgogyws.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocaemtix.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gtwqvzlhlu.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gtnbgebrhu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtdjkhupzn.html

[U60] PHP：JSON 编解码
来源：http://dali.gogol.net.cn/Article/details/gtqbbpjxae.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gtdhycbyle.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gtdcekffua.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqsajoowl.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gtcsfcgsan.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.quarkkingdee.top/Article/details/gtvyhuoaim.html

[U63] PHP：文件读写
来源：http://dali.nwbrower.top/Article/details/gtyrhyddmy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gaohongyu789.top/Article/details/gtbdfsmklp.html

[U64] PHP：目录遍历
来源：http://dali.yueranfly.top/Article/details/gtugzmbzbc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yangfankeji.com/Article/details/gttttvbpcg.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtthvrpmqv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtatxhxlfk.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gttsfsvbzn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtyxygtvez.html

[U67] PHP：处理文件上传
来源：http://dali.xuetiantiany.cn/Article/details/gtrgfjlfns.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwimqfueo.html

[U68] PHP：PDO 连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhjoxzgc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gtpuckfksh.html

[U69] PHP：PDO 预处理
来源：http://dali.xinyue.icu/Article/details/gtegkahjgr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gtavrtlxhw.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdfpbvtg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gtqkpyrtxc.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtohebavxf.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gtjrsmngxy.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gtvavjdkhp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sxryk.cn/Article/details/gthotslljk.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gtydvjsnst.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gtmqvrewsk.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtihkiawez.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxuanxn.top/Article/details/gtgxcwlhhs.html

[U75] PHP：依赖注入
来源：http://dali.ehwqpu.com/Article/details/gtmzssizes.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtvnlplevv.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqolfwdc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gtscegmpif.html

[U77] PHP：模板渲染
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnfwghhq.html

composer require twig/twig
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrydqbxso.html

[U78] PHP：单元测试
来源：http://dali.yongpay.top/Article/details/gtlsgxinyx.html

composer require --dev phpunit/phpunit
来源：http://dali.yuxming.cn/Article/details/gtttptftia.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gtocedagod.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gthysiwwwo.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gtcymqtpsu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gtxffskfeq.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtaakbfgxw.html

npm init -y;  npm i express
来源：http://dali.jinqigufen.top/Article/details/gtwklexbbg.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gtjnaappsp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxuanxn.top/Article/details/gtxsrknqee.html

[U83] JS：ES Module 导入导出
来源：http://dali.cdnleiting.top/Article/details/gtblxcxvbc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtsdieeiay.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtmjnncbrn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gtmkmmiixm.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gttzvfiezf.html

a?.b?.c
来源：http://dali.iojbl.cn/Article/details/gtlabngjoi.html

[U86] JS：空值合并
来源：http://dali.wangshuangyany.cn/Article/details/gtdnajdlqd.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtfkglsgzk.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gtxihhohto.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuanzhike.top/Article/details/gtoknnvalz.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gtdorskwxc.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtdknhtxte.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodsmjksz.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtkjqvkdtu.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtecoukanv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtnqoqurdd.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gtwzpitwio.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gtezbrmbop.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gtarjhrvno.html

structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtiuzmnoxp.html

[U93] JS：模板字符串
来源：http://dali.ehwqpu.com/Article/details/gtbiguvkfj.html

`共 ${n} 条`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrqwhnmp.html

[U94] JS：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtpyjydquv.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzonlwfvl.html

[U95] JS：Promise 包装
来源：http://dali.hfpthk.cn/Article/details/gtzofgtgdh.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gtwtgkiqmf.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gtofzomamp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gthkrlppkf.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitjrcgyt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gttsjmxiht.html

[U98] JS：fetch 带 JSON
来源：http://dali.cheryme.top/Article/details/gtshwbdkdi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sxryk.cn/Article/details/gtrnnqnhmg.html

[U99] JS：事件监听
来源：http://dali.chenjidiqi.icu/Article/details/gtiqqhttnn.html

el.addEventListener("click", e => {})
来源：http://dali.xuanzx.com/Article/details/gtokhavios.html

[U100] JS：DOM 查询
来源：http://dali.sxryk.cn/Article/details/gtirsgcpip.html

document.querySelector(".item")
来源：http://dali.zhiwuduotai.top/Article/details/gtkwjzmoqg.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gtxsmcznyv.html

el.classList.toggle("active")
来源：http://dali.316326.xyz/Article/details/gtfumjclfg.html

[U102] JS：本地存储
来源：http://dali.shzxlz.cn/Article/details/gtfiupdrsd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gtqelskngv.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtxkvhbkmz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gtrtjsyqpx.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtjtxagicz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtjtefecyb.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gtysassgeg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gtthhhznzk.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtdktrplmo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gtezgwdyre.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtfnblmpqp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtusxinvjk.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gtgrtjwtry.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtsnunkycq.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gtmgpemawq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtdvkvchyi.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtxfowzeca.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gtlisebuzc.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtslqbnxvc.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gtkovgszmz.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtmkvgwqop.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtippsmtvg.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gtnrggngnk.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtfghzkvqs.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gthzlbevgu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtluyexbbj.html

[U115] JS：生成 UUID
来源：http://dali.yonumen.top/Article/details/gtetuinjsw.html

crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtgrrkvxvs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigfzy.top/Article/details/gtsmmgeugd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtrilbhhhu.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtyqzpnmwj.html

npm i -D vitest;  npx vitest
来源：http://dali.gzhubu.top/Article/details/gtasgshgjj.html

[U118] JS：开发服务器
来源：http://dali.yueranfly.top/Article/details/gtxfgsecdp.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtvoundkzg.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gtqznrtwlp.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gtjcygsfdf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gttlqzostu.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gtsmgdvyjt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtymxyfoco.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gtdibkdebu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpjzjffjh.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfublges.html

Python ......... 252
来源：http://dali.fzhhl.top/Article/details/gtgsjuhqpj.html

PHP ............ 252
来源：http://dali.yvedp.cn/Article/details/gtgwdtcbfw.html

JavaScript ..... 252
来源：http://dali.yj20258888.top/Article/details/gtgsioiyqk.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gtfqycmyac.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtsxrtokvi.html

Go ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtvbsskgbz.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtbqlkgsnp.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gteltnxebv.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gtlyvejrld.html

C++ ............ 30
来源：http://dali.cheryme.top/Article/details/gtashkdqzm.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gtlxrnvowk.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gtcbahkqjm.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gthcoqwqjf.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtpnxyxbgc.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtstgqoqoo.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gtynkwgilf.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gtyfzkuujf.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtuccrybbr.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gtmgjwvpsk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gtuaahicku.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtldjnanql.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtupqksigu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtycemuvqv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtloljtejj.html


<!-- 参考信息 -->