代发 wailian999

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwwghpof.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtwvglfbfw.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtwyjqvymc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gtemunaanj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtfbrdldle.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtvqcoomrm.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtauiitxac.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtqtirlloa.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtzdmpqmkr.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtqkwvytjg.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gthnunmqzc.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtreqiblgr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gttdmxyzzf.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtcgoefstz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gtisoosnmp.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gtbjyybdau.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtrreldvgj.html

[T57] Scala：模式匹配
来源：http://dali.shuidangran.top/Article/details/gticmfbjer.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtvbjrlydy.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkivyrmec.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.redwolf501.top/Article/details/gtmyvavhff.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtuokistjx.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gtddknmmjc.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtvwpkuogo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtwtojgfsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtowhbcolr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkjutssk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiyipocl.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gtyjevupie.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gtikpszfnd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtxlqudyfe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtjpgenucx.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gtaocibdyf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtnxnyyadp.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gtffoexxbz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gtndltjpgb.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gtooxfkgsf.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gttbpnhnik.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtznsfjygq.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gtzabjoynd.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtifrjzcte.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtcjxdtzsz.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtgtwzvcfh.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtudjwoatx.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtgdklowpm.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtntjfpkjj.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gtamfryihg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqowdqrqv.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gtgrzatydv.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtmebvhtim.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtqjxerzfc.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtlahdwltu.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gtadyttthx.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gticwhvdsp.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtciuloezo.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gttretlcje.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gtjueooaxa.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmifcgqwp.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gtatlieuxo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gtrxljbyir.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtuecpfjsp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yongpay.top/Article/details/gtcpmfcyoy.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gtgufdxxxv.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuclptze.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gtmxdlujfx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtnpgcmbxs.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gtkfxsthbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gtgrurhbmi.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258888.top/Article/details/gtxmhfeseo.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmtirkxo.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gtkhouvqjx.html

list(zip(*m))
来源：http://dali.havefunace.top/Article/details/gtrygfkmbs.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gtfzhidngd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtbiqvutxk.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtwvgmirui.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtsbwmgftv.html

[U25] Py：CSV 按字典读
来源：http://dali.ybcxt.top/Article/details/gtqsbhajew.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gtxmgddgfc.html

[U26] Py：并发下载
来源：http://dali.hfpthk.cn/Article/details/gtfxxvgidi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gtoqgsakqe.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gthgppullw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gtlwkzovqv.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtuiibmebo.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gtmypibzuw.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtybrxeflx.html

@property 与 @x.setter 配合
来源：http://dali.hongshengwenyu.top/Article/details/gtukkywasb.html

[U30] Py：数据类
来源：http://dali.shuidangran.top/Article/details/gtmnmvrtlw.html

@dataclass(slots=True)
来源：http://dali.meibo888.top/Article/details/gtavzhmjbk.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gtnkddrbqt.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtwocogqtb.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gtlfwhkmgm.html

ruff format . && ruff check --fix .
来源：http://dali.guowangkeji.top/Article/details/gtbtztyfji.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gtvhzuzvkm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuxming.cn/Article/details/gtjnfzgzra.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtogdflvcl.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxpoxjud.html

[U35] Py：发送邮件
来源：http://dali.jianghu66.top/Article/details/gtedarqcym.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtvahbvasc.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gtpkfzgblj.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuanzhike.top/Article/details/gtjaiexpfw.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gtmaegukpf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.andypj.xyz/Article/details/gttnduxago.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gtqvolqmyp.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gtvskkcmgl.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gtatmhnpvl.html

sys.stdout.isatty()
来源：http://dali.birdmap.top/Article/details/gtknkijwwn.html

[U40] Py：打印到标准错误
来源：http://dali.mhx1999.top/Article/details/gtdrpbwhiz.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtisnmyiih.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnehdpeg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtqkvbztqk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gtbehhiyrg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtdctspong.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gtzyuxnwha.html

namespace App\Http;
来源：http://dali.tian-w.cn/Article/details/gtddkjeevo.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gteqcwxmsj.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gtoluxruth.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gttrrllwty.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkbcxedjl.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtyczqpeul.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtxmgxnvwb.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtvxoesuvq.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gtulyxhwpw.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtrgsxxgnl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gtnkklkwkf.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtyftkfxrd.html

public readonly string $name
来源：http://dali.zhongyouzk.top/Article/details/gtwpyockdu.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gtgzhpejel.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gthcvotmnz.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gtcsxvijim.html

[$a, $b] = $arr;
来源：http://dali.guannengcc.top/Article/details/gtuorjjxrx.html

[U52] PHP：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtzewpbcfo.html

$double = fn($x) => $x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtjavoszjq.html

[U53] PHP：空合并运算符
来源：http://dali.cheryme.top/Article/details/gtzsuovfma.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gtatftbmxa.html

[U54] PHP：空安全调用
来源：http://dali.xinyue.icu/Article/details/gthqbrcane.html

$obj?->method()
来源：http://dali.yonumen.top/Article/details/gtlkjagaue.html

[U55] PHP：match 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtjuqfmeyx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtmiolwmsq.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gttcqzpcne.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtkwktqlqu.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gtftednrsy.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gttpmforxw.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtjpyrbjqg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.mhx1999.top/Article/details/gturhmcsmy.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gthktnlnsr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtnafhiodk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmjetmyh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zdqjudy.top/Article/details/gtjxvxxqrd.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gtjtbmhbmb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtivreovbr.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtybwbodzb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.snrcjt.cn/Article/details/gtsncczdih.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtogwfwcvn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtdjlsbdck.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtwbrfhczm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvufietm.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtfbvbeyxj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtqwnvxlek.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gtdbrbyiin.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gtritqxgyu.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtzahfomwy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gtdytivult.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtgjuoaqop.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gtdzhclvtn.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gthsxsggnn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hongshengwenyu.top/Article/details/gtrsyfztzb.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gtdkmwigbn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvreltufw.html

[U71] PHP：抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtguzwldzt.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtvxhmhhhn.html

[U72] PHP：写错误日志
来源：http://dali.hysaishi.cn/Article/details/gtzhgjputn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gtrzuyxgnq.html

[U73] PHP：读取 ini 配置
来源：http://dali.sufxvd.cn/Article/details/gtjkmukmbz.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gttubzxtpd.html

[U74] PHP：读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtlprzqwqu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtimtnjsbi.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gtdwumonzp.html

composer require psr/container
来源：http://dali.yongpay.top/Article/details/gtoglemcyp.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gtvbtwnrpk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dianchejie.cn/Article/details/gttzzmkdlo.html

[U77] PHP：模板渲染
来源：http://dali.jinqigfzy.top/Article/details/gtvmzpomzc.html

composer require twig/twig
来源：http://dali.xziqi.cn/Article/details/gtrhjrzgxw.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gtijxiwpsj.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gtiflgqbtd.html

[U79] PHP：静态分析
来源：http://dali.birdmap.top/Article/details/gtylzytcti.html

composer require --dev phpstan/phpstan
来源：http://dali.jyoumei.cn/Article/details/gtvjonbzdn.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtghzjrgjd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.quarkkingdee.top/Article/details/gtonwmwcoe.html

[U81] JS：初始化项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwxihryn.html

npm init -y;  npm i express
来源：http://dali.ybcxt.top/Article/details/gtvlcxqnkj.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtvfodtlmg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gtwvlnoowe.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gtcxdtlmvw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtwxgpbmxr.html

[U84] JS：CommonJS 写法
来源：http://dali.iojbl.cn/Article/details/gtabcchabx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtzhdkhpfj.html

[U85] JS：可选链
来源：http://dali.quarkkingdee.top/Article/details/gtsdvybdcp.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gtzaojsszx.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqanssli.html

a ?? b
来源：http://dali.fengsongda.top/Article/details/gtjbtxkpht.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gteaceiaya.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fzhhl.top/Article/details/gtiwanqxwx.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gthvtzxtkx.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gtevdoraeq.html

[U89] JS：数组去重
来源：http://dali.jiagoushi.top/Article/details/gtdmiehgod.html

[...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtheeeeszu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gtbuasehga.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtrxomwsxv.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhgqzvcc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daxiang520.top/Article/details/gtjnpqdxvc.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtfkforwmk.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtsxcowevq.html

[U93] JS：模板字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuzunzns.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtctqkcbcz.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtysktiusb.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gtafbpcjqo.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gtmjkzberh.html

new Promise((resolve, reject) => {})
来源：http://dali.wangdashe.top/Article/details/gtzrwywljy.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gtnepryggw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtvhhxknhu.html

[U97] JS：并发请求
来源：http://dali.hongshengwenyu.top/Article/details/gtrklljebx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtrimxbxsf.html

[U98] JS：fetch 带 JSON
来源：http://dali.yueranfly.top/Article/details/gtdlzrlxsh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cashguo.top/Article/details/gtxaoqgdkf.html

[U99] JS：事件监听
来源：http://dali.vqdsnc.cn/Article/details/gtxldduukc.html

el.addEventListener("click", e => {})
来源：http://dali.cqqwz.cn/Article/details/gtqmtnxlxa.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gtqtymovnw.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtivoakxag.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gtxdojkcij.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gtopmiybhi.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gtfmuzzwez.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuetiantiany.cn/Article/details/gtkutghlev.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gthgudwoxa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gtslxsjxhj.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtbsaqwqna.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtjyzhejsh.html

[U105] JS：节流
来源：http://dali.zhengqikj.top/Article/details/gtpylmgaiq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gtadnxumoi.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtawsnacrp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aibaodan.cn/Article/details/gtnugnqaqj.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtouzqlcuf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gtgmaalzkc.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtfzlinvzf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gtjsoizlhj.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gtuobjdgng.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gteenhviwp.html

[U110] JS：数组分块
来源：http://dali.pengpengdd.cyou/Article/details/gtbozpgvja.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gteafomdpe.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gtkskrorxe.html

new Map(Object.entries(obj))
来源：http://dali.pycfn.com/Article/details/gtgdsrjhhh.html

[U112] JS：字符串补位
来源：http://dali.zhiwuduotai.top/Article/details/gtqokkprfh.html

"7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtqgbjhqwt.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gtgydzjdmm.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtuhqthsyk.html

[U114] JS：JSON 深比较
来源：http://dali.andypj.xyz/Article/details/gtvupoxolc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtmdwidihk.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtgbrauytu.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gthvmnpwgc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gtwewqvuqm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmwixtdzx.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtdjhmfdkb.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gtssfubkgh.html

[U118] JS：开发服务器
来源：http://dali.yvedp.cn/Article/details/gtlrbuleld.html

npm i -D vite;  npx vite
来源：http://dali.yonumen.top/Article/details/gtsfyxbupo.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gtbgvnrsgf.html

npx vite build
来源：http://dali.cheryme.top/Article/details/gtstevcixj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtkjtpejxi.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gtftxnntnh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gteyzgbjon.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtaaczllgb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttpctcvyc.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtplbddwqy.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gtbraturql.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtjkgubpcs.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gtccsgakqt.html

TypeScript ..... 212
来源：http://dali.yj20258888.top/Article/details/gtwqjcuori.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtcvfmrvmj.html

Go ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtdelfpgsk.html

Ruby ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtulgdkbck.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gthmgaifkl.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gtympgfdrh.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gtxgyabszl.html

SQL ............ 90
来源：http://dali.dashuyun.cn/Article/details/gtmrxwkdtn.html

Bash ........... 80
来源：http://dali.xuetiantiany.cn/Article/details/gtjnwrmwdv.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gthrsaloze.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gtvouixiph.html

Lua ............ 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsdwcwpz.html

Perl ........... 10
来源：http://dali.gotoacloud.top/Article/details/gtopzmzlyb.html

Scala .......... 10
来源：http://dali.daxiang520.top/Article/details/gtbhsnurke.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtgarzfzch.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gtfkbppiat.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gthvggkrxu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtblkvnnzk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gthxqhpwvs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtbfpbnihj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtdtwkeqtj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigufen.top/Article/details/gtkuccrscq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtqcrtqcxe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphqmvnds.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtmrercphr.html


<!-- 参考信息 -->