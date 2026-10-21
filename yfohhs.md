代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzsafjfb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgaboobnr.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gtyvbdabzj.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtxiaaifbt.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtyyoabgqu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtapuaozet.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtbgzsegtu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gtihouexgx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtfhiblpgb.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtwqjvhtvf.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtexnjacbv.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gtduoexwsa.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtkrbqzjsb.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtabjhiiud.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtvcxhpcxw.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtcqvnmwtg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtglswlhxj.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtjvxegatw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gtngfhbqko.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtrfczoscq.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtnzpvcegb.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gttorwopdn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yvedp.cn/Article/details/gtdqpzeecg.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gtonccnldp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtnwvnaqfk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtvwbkvxai.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gthifkitue.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtsftjmvgz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gttnrqbsxi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqknpoxib.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gttjadeuju.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxrbowwsk.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtdqsphpir.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gttqkoirud.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtmnqqjjsz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvafchjay.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gthrylzagn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtrssexgcn.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtbjvpwymt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gtosoigoyr.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtojawcswm.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtqcgmmnee.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtxjkzslpa.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtkybnrjjp.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gtufdmyrts.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtmjdqivli.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtpjgmspxj.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtebseanpi.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gtfeqrfoel.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gtvnocifea.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtvzcfocbt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtgmdpchzb.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoqcloxg.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqknqwzoa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gtddnodxam.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gtmhmiwggd.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gtbvgpvqbs.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gtejhcijji.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtwecbouos.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gtnwwuzkye.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtjchluvjc.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtzroqkdnb.html

[U16] Py：命令行参数解析
来源：http://dali.fengsongda.top/Article/details/gtcobxgojf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gtwbcnregp.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtjdjnfdfa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gtrkucrjrv.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtciooybli.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gtdtmdvtsb.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gtqaynduje.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwirpgltp.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gtdggapora.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gtonfsmits.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gtjfmdfcat.html

@contextlib.contextmanager
来源：http://dali.iojbl.cn/Article/details/gtinrctqus.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gtkwlgtueo.html

list(zip(*m))
来源：http://dali.yuxming.cn/Article/details/gtvznkwxue.html

[U23] Py：分块读取大文件
来源：http://dali.gotoacloud.top/Article/details/gtwaehasdc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtcxuwagmf.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtobxwmume.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtrkuyypnr.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gtiaxdiroh.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqxhwfqc.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gtmrjyzgpw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtjrmbfwtv.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtpbeuiorp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtpceaepxr.html

[U28] Py：类型别名
来源：http://dali.chenzaomai.com/Article/details/gthmaofpzr.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gtotcaarqr.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gtfmjpxfcy.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtfqnfebzm.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtrculiijp.html

@dataclass(slots=True)
来源：http://dali.smart0.xyz/Article/details/gtmtlwwfoy.html

[U31] Py：单测
来源：http://dali.andypj.xyz/Article/details/gtpnvsohum.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gtzhojbpde.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtroumyadg.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gtbwwufqcv.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gteskjvhfm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pycfn.com/Article/details/gtgawpqlpo.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtyvktakpy.html

chardet.detect(raw)
来源：http://dali.fengsongda.top/Article/details/gtrjeyyjvo.html

[U35] Py：发送邮件
来源：http://dali.fengsongda.top/Article/details/gtzqbokrxr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gtmjwovsau.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gtprlycgaa.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtserbivyt.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtrztkphrt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvsvwnur.html

[U38] Py：获取脚本所在目录
来源：http://dali.yueranfly.top/Article/details/gteqynysyw.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gtskohilhz.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtnarzffia.html

sys.stdout.isatty()
来源：http://dali.sweek.top/Article/details/gtvwzhtpfq.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gttdagyymm.html

print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtvqvbtfef.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gtzaycjgvc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwzesmtb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cqqwz.cn/Article/details/gtacyjssgb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtkjoutiad.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gtjogutcnf.html

namespace App\Http;
来源：http://dali.yuxming.cn/Article/details/gtrnkaegui.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gthbfowvdu.html

declare(strict_types=1);
来源：http://dali.yongpay.top/Article/details/gtcxnqqcrj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtmlfjtmjg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtpgeusdve.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gtysfpjsxc.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gtbbdasagt.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtgbiynrzp.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gtkwleushm.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gtlueyoubc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.svipenyu.cn/Article/details/gtozyvbudp.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtgwtgdqgy.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtiwutkykl.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtgdtgdmku.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvtihjuv.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gtdfmkrsbk.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtigqgkvcp.html

[U52] PHP：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gtrqyqircc.html

$double = fn($x) => $x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtuiizwtfy.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gtymmfavrd.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtthepnfvy.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtivlxudci.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gthiinoopz.html

[U55] PHP：match 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtagdklwsz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtntfbhxak.html

[U56] PHP：命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtdkbljkme.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtqsftbunr.html

[U57] PHP：字符串插值
来源：http://dali.andypj.xyz/Article/details/gteznenoqz.html

"值: {$a}"
来源：http://dali.ivvv.top/Article/details/gtxihxljso.html

[U58] PHP：数组三件套
来源：http://dali.quarkkingdee.top/Article/details/gtfekaitss.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gzhubu.top/Article/details/gtnvwrsfvm.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gtpgkwfwpi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtrnxilthm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gtiudtlznu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gtgsrfyawk.html

[U61] PHP：正则
来源：http://dali.jyoumei.cn/Article/details/gtxptzxrav.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtmqoskyjo.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangtech.top/Article/details/gttgukbesz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gtajgfxtlx.html

[U63] PHP：文件读写
来源：http://dali.guannengcc.top/Article/details/gtrzmzfnxg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gtxsesgswe.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gtzfimdyhi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtukojsaxw.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gtkbbfznrw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tanke756.top/Article/details/gtblfvuzjr.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gtyyggkzlv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtcnguifzk.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtvoiuimrq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.havefunace.top/Article/details/gtxiucluzq.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gtgrvyttyg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hywenlv.cn/Article/details/gtogcjjipd.html

[U69] PHP：PDO 预处理
来源：http://dali.yj202588.top/Article/details/gtswqsfole.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gtpuhmfiev.html

[U70] PHP：PDO 事务
来源：http://dali.chenzaomai.com/Article/details/gtepgvjrrg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gtlygxuynk.html

[U71] PHP：抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtwczfhdgf.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtmdyxfslw.html

[U72] PHP：写错误日志
来源：http://dali.jianghu66.top/Article/details/gtrfjhlqet.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ppjwa.cn/Article/details/gtutdxwcyn.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gtiowcssqc.html

parse_ini_file("config.ini", true)
来源：http://dali.kuanghao11.cn/Article/details/gthectuqig.html

[U74] PHP：读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gteldvzkia.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gteuhnnwlg.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gtpdvnszef.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gtnwxlnumr.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gtrcjtmipd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zdqjudy.top/Article/details/gtlnzuvyuu.html

[U77] PHP：模板渲染
来源：http://dali.ehwqpu.com/Article/details/gtdxjzfnkx.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gtlasqvuhl.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtsshqglfn.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gtxpfwwhhv.html

[U79] PHP：静态分析
来源：http://dali.guannengcc.top/Article/details/gtwamyxbsp.html

composer require --dev phpstan/phpstan
来源：http://dali.hnxiangtu.top/Article/details/gtutvyyomw.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gtjgyrwepv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aibaodan.cn/Article/details/gtfmjjdaku.html

[U81] JS：初始化项目
来源：http://dali.zycfv.cn/Article/details/gtrqqmdqxx.html

npm init -y;  npm i express
来源：http://dali.shangyingyoupin.top/Article/details/gtaeqkmluw.html

[U82] JS：package.json 脚本
来源：http://dali.pycfn.com/Article/details/gtvywnvyvo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fengsongda.top/Article/details/gtcyujkzfo.html

[U83] JS：ES Module 导入导出
来源：http://dali.cdnleiting.top/Article/details/gtmtkkcnau.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtkmbozjmm.html

[U84] JS：CommonJS 写法
来源：http://dali.fengsongda.top/Article/details/gttchrzser.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtfadkindy.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gtosysrxef.html

a?.b?.c
来源：http://dali.hywenlv.cn/Article/details/gtnuxucsni.html

[U86] JS：空值合并
来源：http://dali.jqgfzy.top/Article/details/gtnhxkhdes.html

a ?? b
来源：http://dali.9152youxi.cn/Article/details/gtwobxjcml.html

[U87] JS：解构默认值
来源：http://dali.9152youxi.cn/Article/details/gtbkziqeta.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guowangkeji.top/Article/details/gtyrcamgcw.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtabblvllz.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gtgwxrkauj.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gtdfytaeik.html

[...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtzcemnfqx.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gtgtunyoob.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gttnyqliyx.html

[U91] JS：对象键值遍历
来源：http://dali.cheryme.top/Article/details/gtblntvzos.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gtwjtqhtcc.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gtsksqkajf.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxppewmwu.html

[U93] JS：模板字符串
来源：http://dali.316326.xyz/Article/details/gtfnnliuhe.html

`共 ${n} 条`
来源：http://dali.chenlongwang.top/Article/details/gtrjfdshjt.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtpeicpsku.html

const double = x => x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtorwcddna.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gtwogxgvze.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gtaxlysuvk.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gtpgnxknaw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtjjvbddzd.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzldxpca.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtklsyncjv.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtptbbukel.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtavchmune.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtohrsrzyu.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtgwogkyka.html

[U100] JS：DOM 查询
来源：http://dali.zhoulong.xyz/Article/details/gtbnphdkqf.html

document.querySelector(".item")
来源：http://dali.jinqigufen.top/Article/details/gtvyjqhsfu.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtuasblwoc.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gtjdpkbyws.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gtrrhquqrh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangshuangyany.cn/Article/details/gtnogztvif.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtzjrmmsat.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gtugfzxgfo.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gtgbmhpshn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejmbxtty.html

[U105] JS：节流
来源：http://dali.vqdsnc.cn/Article/details/gtdhnhmepq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gthnwwuaes.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtayzzfgsw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtrzpoqruj.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtplvezmhp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtocgmbrqb.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gtwxnbxhpd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gtwollyibq.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gtsjggfouw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtdptpdqqf.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtqqkzfitm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gtjaomtaml.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtshxxnekg.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtotloqmqj.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gtwgyyelue.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtrpjgcttm.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldhjncgv.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gttunmtflu.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtaxlqgbkm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtlkdfwkuz.html

[U115] JS：生成 UUID
来源：http://dali.cashguo.top/Article/details/gtysjqzxen.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gttlutggzn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gtqpsmzbjz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.birdmap.top/Article/details/gtsjlhcrig.html

[U117] JS：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtnpcbhmue.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gtckehtkgv.html

[U118] JS：开发服务器
来源：http://dali.c1oappe.top/Article/details/gtibyuyebi.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gtdurzglot.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gtwdkireii.html

npx vite build
来源：http://dali.chenlongwang.top/Article/details/gtmniicwax.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gtdizuqixv.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gtoybczbuk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjvgntsdu.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gtgqnwlfyh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmixxrdxv.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gtoxrfzwej.html

Python ......... 252
来源：http://dali.jianghu66.top/Article/details/gtbvruomgi.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtcyligkgu.html

JavaScript ..... 252
来源：http://dali.zycfv.cn/Article/details/gtyaveysoi.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gtipepipxz.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gttfpjuney.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtwppavmfz.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtmvfpejhg.html

C# ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznmfhjst.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gttlwwcesr.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtezkfwczt.html

SQL ............ 90
来源：http://dali.shuidangran.top/Article/details/gtvbrncnvi.html

Bash ........... 80
来源：http://dali.0kj1m.cn/Article/details/gtrsvimvfm.html

Kotlin ......... 15
来源：http://dali.hysaishi.cn/Article/details/gtichmxihi.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gtkjhgzkma.html

Lua ............ 10
来源：http://dali.316326.xyz/Article/details/gtzwunvpyg.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtnhphigbo.html

Scala .......... 10
来源：http://dali.yj202588.top/Article/details/gtvpxoewdv.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtulxlahfi.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gtmfmfwbrj.html

按章节统计：
来源：http://dali.quarkkingdee.top/Article/details/gthscrebgs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gtkzzwyyvv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtxwxncoie.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmsxogac.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtzcekbnzf.html


<!-- 参考信息 -->