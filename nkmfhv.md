代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulrurrpz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gtiimlqraj.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtgsaptbcj.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gtnlazwdcd.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtpkcsqvtj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtvmcfgoks.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtxveipdse.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gthghmbgox.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gtizghtdke.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtrqajxdrl.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtcvayzwlx.html

[T52] Scala：变量
来源：http://dali.gogol.net.cn/Article/details/gtrintsgsd.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxuggedx.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gthkcuvsdx.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtxaznxlab.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtfsrdccxy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gttwcvkcns.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtswawrpah.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gtdbqoqgyu.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtnelzrtqs.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtmbeealgi.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtkgblfecg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtgjavaxch.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtzydmxlls.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gtrvwfxble.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtorzbeyue.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtghjrdcyq.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtuoxxykyd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtyprogdny.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfnptbmhu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfrieukw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxgvcyhkq.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gtaijxffyu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gtojaupuke.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtmgjvtjyq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gteyekrcrr.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtjjcormar.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtfgczrfuq.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gtpdctcwqa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gtvztwvozd.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtvojjttcf.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtmxcmfzsq.html

[U06] Py：合并两个字典
来源：http://dali.316326.xyz/Article/details/gtulftzbnz.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtllbaqedk.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gtwfkvunnq.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtbtiumgtj.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbgdfwxj.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gtuiiqivzt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gtvxdztter.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gtsvtrdmvt.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtryksqvfc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsqlfnpl.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gtwcxtchtn.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gtkpaufahr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtcnirptzi.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gtdvniwtaz.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtuwrtgdmg.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdtfinhn.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gtkissydlw.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtindjckqo.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gtdotcpcqw.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtxgpuflqf.html

[U16] Py：命令行参数解析
来源：http://dali.yuxming.cn/Article/details/gtyugobsqh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gttoicqnsn.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gtqcubsnzo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gtbudmwwhq.html

[U18] Py：预编译正则
来源：http://dali.zdqjudy.top/Article/details/gtmqrzcmgx.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtwrwyzctv.html

[U19] Py：正则替换带回调
来源：http://dali.cqqwz.cn/Article/details/gtawovxojh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtxhblafuv.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gtnnatbqju.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gtzbhogpqz.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gtnndrewwp.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gtsbheyfpy.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gtxdutvfem.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gthljjnxbz.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtckkpxnxd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtqntilujx.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkruamixz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtuzhuwedx.html

[U25] Py：CSV 按字典读
来源：http://dali.gzhubu.top/Article/details/gtsdisvdov.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gtmqaxaugl.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gtbzakgodg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcpdpwus.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gtflbsfjzt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtaoihgscx.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gtcvttpojd.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtsmidaltb.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gtqnatmzie.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtajnneeiy.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gtrbsgcctf.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gttqvvbgqo.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gteuuwmvni.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gtwebepamt.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshwwocbr.html

ruff format . && ruff check --fix .
来源：http://dali.birdmap.top/Article/details/gtlebuezlr.html

[U33] Py：打包发布
来源：http://dali.chenzaomai.com/Article/details/gtsqbhpcwi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fengsongda.top/Article/details/gtlghhsuie.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuawhenhw.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtsmzynzlj.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gtylrbjdrs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gttxvkzawr.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gtsdoromow.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtadhluxql.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gtzrqfnwcq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtnxpacafm.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gtvzpplmln.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gtsrzlhycx.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gtdxvtvztx.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gtrneqldwb.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtcracxkkm.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtweuhgrjj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gtioxlfmht.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gtztddfqxw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkictuzhr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gtmgilvxxr.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtzglcjpbu.html

namespace App\Http;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkkrqgta.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtzcizmtrn.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gtkngpvzfg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258.top/Article/details/gttgfmykro.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtolsjtgeu.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtvcowzjzz.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gtxgwipkyf.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoisbxfu.html

int|string $id
来源：http://dali.ivvv.top/Article/details/gthvtgaofc.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtrxtshhil.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtqfvmyppz.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gtygqksjgg.html

public readonly string $name
来源：http://dali.cashguo.top/Article/details/gtqidcxpez.html

[U50] PHP：构造器属性提升
来源：http://dali.chenjidiqi.icu/Article/details/gtumfvsups.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuimusfgn.html

[U51] PHP：数组解构
来源：http://dali.guowangkeji.top/Article/details/gtitvtgxsq.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gtvldpokzq.html

[U52] PHP：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtculvllkn.html

$double = fn($x) => $x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtakuhioyk.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gtdsverpiy.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gtwkckjyzt.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gtwoawqmba.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gtgdvhokww.html

[U55] PHP：match 表达式
来源：http://dali.cqqwz.cn/Article/details/gtgqwvfobe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gtikqgklku.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gtrfcntrvj.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtazwjphhg.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtqsifkede.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gtkkqoyodr.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtbjlbhrpg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtokyxdzqn.html

[U59] PHP：自定义排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspykgmws.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtirprfrsk.html

[U60] PHP：JSON 编解码
来源：http://dali.yongpay.top/Article/details/gtphbnahko.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jianghu66.top/Article/details/gtmgjjknil.html

[U61] PHP：正则
来源：http://dali.gotoacloud.top/Article/details/gtvrnkfwnl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtjpxymsuz.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gtgkbaynba.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gtfkytzuwr.html

[U63] PHP：文件读写
来源：http://dali.yj20258.top/Article/details/gtzdoydjxb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtmeylcjal.html

[U64] PHP：目录遍历
来源：http://dali.ydzc1.top/Article/details/gtaozlvwor.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxhmwvex.html

[U65] PHP：会话
来源：http://dali.xziqi.cn/Article/details/gtgltfxrsz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtxyedalbt.html

[U66] PHP：设置 Cookie
来源：http://dali.c1oappe.top/Article/details/gtptkdbbbv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zdqjudy.top/Article/details/gttrwmnlrh.html

[U67] PHP：处理文件上传
来源：http://dali.cdnleiting.top/Article/details/gtwrohsbdu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xinyue.icu/Article/details/gtmoaoyflh.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gthxcphxgz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtwbnyhyge.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gtfyhpbnfu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gtaximzmsk.html

[U70] PHP：PDO 事务
来源：http://dali.gogol.net.cn/Article/details/gtlmlqelnp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gtubcncspi.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gtwtwsdmkd.html

throw new RuntimeException("失败", 500);
来源：http://dali.yvedp.cn/Article/details/gtzhdwwpma.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtqcdwezyw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gtnqkesbni.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gtroeionhv.html

parse_ini_file("config.ini", true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjeqpxlhk.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtojvouprj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xinyue.icu/Article/details/gtmpzbednx.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gtdolkekqu.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtngfpqxzq.html

[U76] PHP：简单路由
来源：http://dali.yongpay.top/Article/details/gtqbcyukqm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gttdiiiwif.html

[U77] PHP：模板渲染
来源：http://dali.yangfankeji.com/Article/details/gtivvjqeog.html

composer require twig/twig
来源：http://dali.ydzc1.top/Article/details/gtenlktvpb.html

[U78] PHP：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gthbwbrkgn.html

composer require --dev phpunit/phpunit
来源：http://dali.daria6918.cn/Article/details/gtnpshhmdq.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuprpxuzh.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gtxsocgwza.html

[U80] PHP：代码规范修复
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzromzspp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.svipenyu.cn/Article/details/gtysapiwml.html

[U81] JS：初始化项目
来源：http://dali.yj20258.top/Article/details/gtaplfkjuk.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtvtdstiyq.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtuhgfokiu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xinyue.icu/Article/details/gtwkikflee.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gthqbifrsa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtlfrtglqt.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtrxkholab.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gtvmguhpeq.html

[U85] JS：可选链
来源：http://dali.hongshengwenyu.top/Article/details/gtyylsnhkw.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtnyqumwxs.html

[U86] JS：空值合并
来源：http://dali.zycfv.cn/Article/details/gtyztmkojj.html

a ?? b
来源：http://dali.cashguo.top/Article/details/gtamrmujyi.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtgizgzdta.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gtmxtlewpl.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gtlgvsujlp.html

{ ...a, ...b }
来源：http://dali.xinyue.icu/Article/details/gtuxbwpcec.html

[U89] JS：数组去重
来源：http://dali.nanxuanxn.top/Article/details/gtqqkkzcbq.html

[...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtznxafuva.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtntmdjmlf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtkozcuovw.html

[U91] JS：对象键值遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtcnsqffql.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gtokifvitu.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gttlurmucs.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkaaphdqn.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gtwjqlinxu.html

`共 ${n} 条`
来源：http://dali.xylfe.cn/Article/details/gtprlqzvvd.html

[U94] JS：箭头函数
来源：http://dali.meibo888.top/Article/details/gtjvzatlpt.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtwgcfxevs.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gttfthckrt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gtjzfntqwk.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtkcsboscq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtykpeoolq.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gtbuonwsnf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtegukznne.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtymdzzpvk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gtdecribgu.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gtrhyneymd.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuszjaxax.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gtvyataxcv.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gteoodxolm.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gtmfgbobsh.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gtwlybmeca.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gtfscfucth.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gtlhyitrbd.html

[U103] JS：定时器
来源：http://dali.cashguo.top/Article/details/gtdzotgisl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gttvhrayxg.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtrjdkqefe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtsxdrwnyw.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gtayhxobbb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtyzmqmwzo.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gtsicitnlq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ydzc1.top/Article/details/gtnydawumj.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtvwdorngh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gthiaiwfab.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gtnfdjiyfn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gtxkuivsnw.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gtqmktgoud.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtnylfhpew.html

[U110] JS：数组分块
来源：http://dali.9152youxi.cn/Article/details/gtkpzqrxay.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtnzpxehil.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtbqomkijd.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibhmfmrd.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gtzgtaqpnm.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtviiiktyf.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gthlsmkuuj.html

s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtbrdjcxvn.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gtpyaqmyhf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuctqodhx.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtxdmyiwbl.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtstimkxto.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gtomzfwqae.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gtfavlwhkb.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtujvjugcr.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gtwjbihrsd.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gtfkiixcxe.html

npm i -D vite;  npx vite
来源：http://dali.meibo888.top/Article/details/gteflptacl.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gtinyzqxdw.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtozbnyrty.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shangyingyoupin.top/Article/details/gtrmrknfkv.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gtvclkagrh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmazpmdve.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtqltdfoji.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnyqboito.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtcxhayuvy.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gtqdvjfbzd.html

PHP ............ 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywgudndh.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gtnbprgihw.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gtzujtezmr.html

Java ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtehvcjyjw.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gtlmnvigtw.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gtrrytohxk.html

C# ............. 212
来源：http://dali.yj20258888.top/Article/details/gtzdswzivi.html

C .............. 30
来源：http://dali.jianghu66.top/Article/details/gtvuryoeis.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gtigifydtl.html

SQL ............ 90
来源：http://dali.yueranfly.top/Article/details/gtkmqsjdpe.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gtdrkmeewh.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gthagjdmeb.html

Swift .......... 15
来源：http://dali.yvedp.cn/Article/details/gtrmeagyoq.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzqqfjda.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gtyxodrbll.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gttlzokhwf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtuemhkucg.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gtydlvgsjf.html

按章节统计：
来源：http://dali.pycfn.com/Article/details/gtbobhdmqf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gtebelzihf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtodluujky.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvdjkcaj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtqncdaete.html


<!-- 参考信息 -->