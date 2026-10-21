代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gtdgzysmxb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsnrykalj.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gtvdywifrl.html

$s =~ s/old/new/g;
来源：http://dali.gzhubu.top/Article/details/gtcomsidod.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtsvhiegon.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtqsgmbpkm.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtyqhnlquq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtpdapzrnw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gthxaljkuv.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gtfxunlaam.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtxscfeguj.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtdscliaud.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gthvvctqju.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtpnzxutje.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtqeunotva.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtxomwymoq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtxltuhgiq.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtjaildzpk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gtkbxqbcxn.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gtuwlhmcew.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtsbjobvbj.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeqjvbvn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtxszaxpko.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gtdhpuesxd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtdjphuydi.html

[T59] Scala：循环
来源：http://dali.yj202588.top/Article/details/gtabhwmref.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtkoudwmum.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtpxsdpjuq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtamjxozlb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzrengnwb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtbpesefwv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtaurryszz.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258888.top/Article/details/gtsvvwsgkf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtbdiibapj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtttondmiw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gtpxnzllkk.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtymcqmunk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtenjqnwvl.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gthaycqygs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtuxeadeoa.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtjuiydmwx.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtdfngnfey.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtgdyojcyh.html

{**a, **b}
来源：http://dali.shzxlz.cn/Article/details/gtrrrohwex.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtbahxdffg.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgfskwhj.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gtoemulkmo.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gtcpxltxdn.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtkkaaecoo.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gtxxdrvhbk.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtobvcsbbh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtaidtckry.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtpygsqlxu.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gtkttlivyq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gtmcbcccgd.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtldjpmytd.html

[U13] Py：固定长度队列
来源：http://dali.gaohongyu789.top/Article/details/gthxsyubse.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gtzifzvetw.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gttixpszuw.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gttebfyple.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtoniiyvkb.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gtckrqmemm.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtuugqbtrx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtlnwjaiyt.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gtbwoajouj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gtvvovhskf.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gteopzrqaf.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gtdgboynff.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtlrjsjtjf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gtcoisetec.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gtfipthynd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gtxncmuqcs.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtsmhijlvq.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gtlxvnsgpd.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtoxssopdi.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gtztiyeobr.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtoezbfulz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gtwygkffev.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gtklmvvetw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtzofrhmew.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxuanxn.top/Article/details/gthxwybykp.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtgmvnxsll.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gtsstxihop.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtesbwldix.html

[U27] Py：异步 HTTP
来源：http://dali.zhengqikj.top/Article/details/gtbngpmaij.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.redwolf501.top/Article/details/gthpxeyuex.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtjdgcdqou.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gtnaktlcbp.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtmstckjfz.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gtbjmlmsbj.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtxbuhyjms.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gtbkkqdlvn.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gtrvwdhgwe.html

python -m pytest -q
来源：http://dali.cdnleiting.top/Article/details/gtgbdoijua.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gtulgxongx.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gtrrhzpsal.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtgwazyzlv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gtoimpkzqt.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gttfjhmqcs.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gtqpvemash.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gtbsplusam.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhongyouzk.top/Article/details/gtyjitivtp.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gtitoitbnh.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gtdywqgxqe.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtrycgrsrq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.birdmap.top/Article/details/gtfxzsfinb.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtuhqvbxjh.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtrklxssai.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gtxzkohabg.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtlhxgbpnx.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtiicwccwm.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtgeffpkov.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.vqdsnc.cn/Article/details/gtpeqfhcfu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtfgmltcyo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gtfpbqpgyd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gzhubu.top/Article/details/gtqvzbjeft.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gtsgmdcpuz.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gthmxdflaw.html

[U44] PHP：开启严格类型
来源：http://dali.smart0.xyz/Article/details/gtjaukgsyz.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gtazmorlwu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtgomttwlk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtdhostcif.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gticpgqkgu.html

?string $name = null
来源：http://dali.hnxiangtu.top/Article/details/gtmtitlcqq.html

[U47] PHP：联合类型
来源：http://dali.smart0.xyz/Article/details/gtbldxwgas.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gtlyfhnmmr.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gtnnypjgrc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj202588.top/Article/details/gtalbvldtw.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtidlwewcr.html

public readonly string $name
来源：http://dali.yangfankeji.com/Article/details/gtcpxeazml.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gtcjcoseui.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtvldxifzo.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gtpolojdsz.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gtdpclfdzm.html

[U52] PHP：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtvaepkzps.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtxpomwlre.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtonadkvyk.html

$v = $a ?? $b ?? "default";
来源：http://dali.xinyue.icu/Article/details/gtxytjkywk.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gtsvdcnqyh.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtlzzmlwfq.html

[U55] PHP：match 表达式
来源：http://dali.ybcxt.top/Article/details/gtyakbshma.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gtcjcurvvr.html

[U56] PHP：命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtrjufisqy.html

f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtetuxdygv.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtcozjshpw.html

"值: {$a}"
来源：http://dali.hywenlv.cn/Article/details/gtzbkusqaw.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtzamtpihd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yangfankeji.com/Article/details/gtwesjomfo.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gtqeuebsva.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtizwawvxr.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gtxpghnmya.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtrunhejfv.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtlmibatmu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtgzvhccgw.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gtzqmjwdck.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pengpengdd.cyou/Article/details/gtlfprgclk.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gtjevantil.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.9152youxi.cn/Article/details/gtmlnkpgvr.html

[U64] PHP：目录遍历
来源：http://dali.shzxlz.cn/Article/details/gtrozsyxjr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtekzkzyvj.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqztfpcy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yongpay.top/Article/details/gtpdurpbaj.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gtrepnmksc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gtwfnmuwlk.html

[U67] PHP：处理文件上传
来源：http://dali.haohaochexian.top/Article/details/gtqkshjkyu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tanke756.top/Article/details/gttodlqwme.html

[U68] PHP：PDO 连接
来源：http://dali.fengsongda.top/Article/details/gtwnbzritk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aizwys.cn/Article/details/gtlnpxjbex.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgufenzy.top/Article/details/gtjpagmsun.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.birdmap.top/Article/details/gtcnspjlnt.html

[U70] PHP：PDO 事务
来源：http://dali.daria6918.cn/Article/details/gtsxiborbt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.vqdsnc.cn/Article/details/gtydrmiiph.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gtatnludyd.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtzcrxsfdr.html

[U72] PHP：写错误日志
来源：http://dali.dashuyun.cn/Article/details/gtfrzsdrvp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtbnhcgwdp.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gtwmdhvete.html

parse_ini_file("config.ini", true)
来源：http://dali.gzhubu.top/Article/details/gtcbwqxhdt.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtobqlitik.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gtkbjgpibl.html

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gtqmswozjv.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gtrlxnfygv.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gtztyxhzgf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jlsjyb.cn/Article/details/gtuajzwazt.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gtltagcica.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gtunwebqik.html

[U78] PHP：单元测试
来源：http://dali.yongpay.top/Article/details/gtawxrgakc.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtfmxcncim.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gtghewzbik.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gtvrwsealu.html

[U80] PHP：代码规范修复
来源：http://dali.cashguo.top/Article/details/gtntlatahq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.bjfxy.top/Article/details/gtvgnpzcbe.html

[U81] JS：初始化项目
来源：http://dali.xuetiantiany.cn/Article/details/gttopcnfsx.html

npm init -y;  npm i express
来源：http://dali.meibo888.top/Article/details/gtaqjhvrcx.html

[U82] JS：package.json 脚本
来源：http://dali.yvedp.cn/Article/details/gtfehxapyx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cheryme.top/Article/details/gtduocwaxy.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gtmmmajdil.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gttxjqzsae.html

[U84] JS：CommonJS 写法
来源：http://dali.birdmap.top/Article/details/gtmpvsarkp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jiagoushi.top/Article/details/gtfybtxbfb.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gthqhuaabj.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gthtqfvgez.html

[U86] JS：空值合并
来源：http://dali.dianchejie.cn/Article/details/gtiwflygmk.html

a ?? b
来源：http://dali.zhongyouzk.top/Article/details/gtvkjgvtti.html

[U87] JS：解构默认值
来源：http://dali.wangdashe.top/Article/details/gtuzjiqlfa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gtftzcwnrm.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gttmbvziaq.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gtepidpmbs.html

[U89] JS：数组去重
来源：http://dali.xinyue.icu/Article/details/gtxjufdmhf.html

[...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtakwntrvt.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtxclnyqnj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gterxblzvb.html

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gtlclaizfe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtlmnpqcou.html

[U92] JS：深拷贝
来源：http://dali.316326.xyz/Article/details/gtszgwhzdg.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnedpbmlq.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gtvotugbsg.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtjmckjzoc.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gttszoirxh.html

const double = x => x * 2;
来源：http://dali.cheryme.top/Article/details/gtlulyrolz.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gtomqihykr.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gtwhzgrqtp.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258.top/Article/details/gtnsqtsacp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtibvknrvp.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gtvcmtnntx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtjxnvzkxv.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gtwezrqwkm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daxiang520.top/Article/details/gtbsryhhfk.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gthxvfglib.html

el.addEventListener("click", e => {})
来源：http://dali.feifeiyinyue.top/Article/details/gtudjmbsnp.html

[U100] JS：DOM 查询
来源：http://dali.xziqi.cn/Article/details/gtwsbmfflu.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gtadskbovh.html

[U101] JS：classList 操作
来源：http://dali.hysaishi.cn/Article/details/gtuxwgzuse.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gtvafsypgy.html

[U102] JS：本地存储
来源：http://dali.hfpthk.cn/Article/details/gtkeyuefmm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxuanxn.top/Article/details/gtqgpiutgb.html

[U103] JS：定时器
来源：http://dali.xuetiantiany.cn/Article/details/gttxhiehii.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuanzhike.top/Article/details/gtnoxyjxgh.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gtjofefscp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtycehgyxs.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gthjqmdtsk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtraoylfwa.html

[U106] JS：日期格式化
来源：http://dali.snrcjt.cn/Article/details/gttnhldpis.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gtzsziyded.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtcwhbzkkc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtaeamdxsh.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcytbule.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cucudq.cn/Article/details/gticdafjnq.html

[U109] JS：数组分组
来源：http://dali.hywenlv.cn/Article/details/gtpixndrpm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvntkzbzq.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtbmlnmnyh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtatakpw.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtiamgbtsk.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtqlatjurg.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gtlirvrgpm.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtdtvtcxgu.html

[U113] JS：正则替换全部
来源：http://dali.hnqzz.top/Article/details/gtdmboaatg.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtyiihzvnl.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gtdvkqhvjj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtbppgswji.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtjouvdbws.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtqhnbsahz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gtmymimfrz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkmwrfeoz.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtaptsraky.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gtpqzkhkyx.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gtnquazlyy.html

npm i -D vite;  npx vite
来源：http://dali.fengsongda.top/Article/details/gtxwkwztbb.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtfpwozbct.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gtjoegyitt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiwzohsn.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtutsnerlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtihuugcor.html

统计汇总
来源：http://dali.jiagoushi.top/Article/details/gtlvulkned.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlwfpxllq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gtirvdcwvt.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gtklhkwjmo.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gteoeslydv.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtooyipaov.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gtuyzoired.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gthxabmiup.html

Go ............. 212
来源：http://dali.hfpthk.cn/Article/details/gtsumjkntz.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtaqnbfsnw.html

C# ............. 212
来源：http://dali.andypj.xyz/Article/details/gtzfvojshk.html

C .............. 30
来源：http://dali.ydzc1.top/Article/details/gthibkslsb.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtfryfgfmj.html

SQL ............ 90
来源：http://dali.chenjidiqi.icu/Article/details/gtduyqtlbe.html

Bash ........... 80
来源：http://dali.tanke756.top/Article/details/gtoclxwymo.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsmkruqx.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gtlysjyztu.html

Lua ............ 10
来源：http://dali.ydzc1.top/Article/details/gtxnnbqknh.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtylacuaaf.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gtgmqdxaes.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtpnjdbatg.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gtgbuzvciw.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gtdnlabyim.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtcmecipql.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtonzljrdz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtryfejogs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtlmroscbf.html


<!-- 参考信息 -->