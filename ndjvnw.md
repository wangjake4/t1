代发 wailian999

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gt2gfegapzz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lhhwsjnc.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2vnmnqgyf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gt2ndvaeqya.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2ngkxcxgv.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2zqjefoee.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxbmncle.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gt2sqfhfxna.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2svcyuanz.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2mrqmmnub.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2hoftzkwi.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gt2tdvcjwpb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2umzhaclr.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2tlsjwygt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gt2umlxxedg.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gt2qavdgint.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gt2emjefimk.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2bcstemlz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2tqyouayc.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gt2bfjdyesz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugwplbjv.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2oltslold.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2eemyyuys.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsqficcc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gt2mlamorwx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2tvdkvmbi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2blrrrmht.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2pzypzxow.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258888.top/Article/details/gt2petirtgk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gt2vlxlbjfo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gt2ainhbzyz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gt2uduvtvtz.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gt2wvsffeni.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pycfn.com/Article/details/gt2hsxtwqzg.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gt2sgnhrkkj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gt2prilmqyw.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gt2fvoaykrz.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2eyvngvlx.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gt2uvqqvrll.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gt2witrxdzh.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjzgygas.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gt2bfgewuoz.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gt2fnfqqnkf.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gt2gygzxoor.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gt2vpkvxpvc.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gt2boplpkjz.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gt2ntiokene.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gt2mijomhuo.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gt2cglupjys.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gt2znmmxqnx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gt2hgbgeotg.html

Counter(arr).most_common(3)
来源：http://dali.yongpay.top/Article/details/gt2lxfvelzu.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gt2tdremunr.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gt2tlawqiai.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gt2vspgxpld.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gt2mofeuyes.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gt2yemcudnf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zglcqvyo.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gt2ekqhrosm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gt2pbzgtooe.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gt2xypotmbz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usujigkq.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gt2jmvhqtlg.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2scxvqunw.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gt2zxziwsif.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gt2jmgkqqai.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gt2ueqaqmpk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gt2hqgupzic.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gt2fcgrmuvr.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gt2itajkien.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gt2flhhcegf.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gt2uvaeprmf.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gt2brkrxrtv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gt2brzgzncf.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gt2gzleyvjv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2pqbkdxsk.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gt2xhumzkpf.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gt2xvgogzih.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gt2lkdduwsd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gt2appadasq.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gt2rkdpeixw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gt2xmkwufki.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gt2nqjixqxl.html

UserId = int
来源：http://dali.birdmap.top/Article/details/gt2emjmvkbc.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gt2tvmbrtdz.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gt2xrvwqbpc.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2uoxqmhxi.html

@dataclass(slots=True)
来源：http://dali.yj20258.top/Article/details/gt2bkvfitxd.html

[U31] Py：单测
来源：http://dali.andypj.xyz/Article/details/gt2mltbeqfj.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gt2qpvvtavl.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gt2hzppxgsq.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gt2kgmsjytl.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gt2vgwbpbhj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gt2dcceathh.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gt2jgrwujfj.html

chardet.detect(raw)
来源：http://dali.yonumen.top/Article/details/gt2qtbzzxae.html

[U35] Py：发送邮件
来源：http://dali.feifeiyinyue.top/Article/details/gt2obillumc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gt2pchwiqdm.html

[U36] Py：定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2cdhjhfcp.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnxiangtu.top/Article/details/gt2lqyxrluz.html

[U37] Py：读写 Excel
来源：http://dali.tianlin.xyz/Article/details/gt2sjnhclbv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gt2uehxbadv.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gt2defjoxei.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gt2emavarke.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2koaogese.html

sys.stdout.isatty()
来源：http://dali.yuxming.cn/Article/details/gt2gcrzoaoc.html

[U40] Py：打印到标准错误
来源：http://dali.hammf.cn/Article/details/gt2qauwcyvq.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2ldlaykff.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.vqdsnc.cn/Article/details/gt2shfvflen.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cczcyvcu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gt2zoboudlm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gt2sygaaekq.html

[U43] PHP：声明命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2jthwfwhl.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pplhtdvv.html

[U44] PHP：开启严格类型
来源：http://dali.tianlin.xyz/Article/details/gt2blagmdbn.html

declare(strict_types=1);
来源：http://dali.nanxinkj.top/Article/details/gt2secobijd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fzhhl.top/Article/details/gt2zemnlusr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pvtjcgdl.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gt2ezhqbqkl.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gt2khwajwdi.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2eybdzlfy.html

int|string $id
来源：http://dali.xylfe.cn/Article/details/gt2qyreqfwn.html

[U48] PHP：纯枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxoztkbb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gt2thjobnlw.html

[U49] PHP：只读属性
来源：http://dali.guowangkeji.top/Article/details/gt2cynpomcp.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gt2lrpghrwy.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigfzy.top/Article/details/gt2cdvuaqsg.html

public function __construct(private int $id) {}
来源：http://dali.xziqi.cn/Article/details/gt2gywyegxr.html

[U51] PHP：数组解构
来源：http://dali.guannengcc.top/Article/details/gt2fgadkldp.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gt2jtgcaizz.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywvoetkn.html

$double = fn($x) => $x * 2;
来源：http://dali.quarkkingdee.top/Article/details/gt2znlrwhqs.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gt2kzxztshv.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gt2yfgxyomp.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npxjvqnz.html

$obj?->method()
来源：http://dali.xylfe.cn/Article/details/gt2emrsbwzz.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gt2ockkyenc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gt2sapxsqbr.html

[U56] PHP：命名参数
来源：http://dali.jqgfzy.top/Article/details/gt2ykzvolfk.html

f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2ngssmgfe.html

[U57] PHP：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdicvtmg.html

"值: {$a}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwvyovbn.html

[U58] PHP：数组三件套
来源：http://dali.chenjidiqi.icu/Article/details/gt2brbopflx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjohyeuf.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gt2jptpjsio.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nibpsvea.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnpwpiyu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gt2zxsgeuss.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gt2wlvfuunu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2hycmrzuy.html

[U62] PHP：日期对象
来源：http://dali.yueranfly.top/Article/details/gt2uwkffqrd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gt2eflapveh.html

[U63] PHP：文件读写
来源：http://dali.xuanzx.com/Article/details/gt2qcqniyng.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gt2urnscrmj.html

[U64] PHP：目录遍历
来源：http://dali.smart0.xyz/Article/details/gt2vwlzhsgb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gt2qteijavf.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gt2gutlgczq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2ptixenpq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gt2igjklftp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gt2qubchhip.html

[U67] PHP：处理文件上传
来源：http://dali.cdnleiting.top/Article/details/gt2njjifhjh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dianchejie.cn/Article/details/gt2krtyzitb.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gt2bpbbmkfc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilkepoiz.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gt2exjqwopi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gt2gfckudey.html

[U70] PHP：PDO 事务
来源：http://dali.sysykeji.top/Article/details/gt2bxvlydyh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gotoacloud.top/Article/details/gt2chdfjeab.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2xzeijnwu.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meltbyse.html

[U72] PHP：写错误日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpkbcbvw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yonumen.top/Article/details/gt2mbntnrjb.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gt2ubudpsmm.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gt2uuqyyafg.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2egtjktgj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gt2jgvvfzkn.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gt2finfvvsy.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gt2xevnoesl.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efwicbqp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gt2ucpxoxro.html

[U77] PHP：模板渲染
来源：http://dali.chenzaomai.com/Article/details/gt2bbmhsyyg.html

composer require twig/twig
来源：http://dali.zhoulong.xyz/Article/details/gt2bnzlttyd.html

[U78] PHP：单元测试
来源：http://dali.wangdashe.top/Article/details/gt2favjytrk.html

composer require --dev phpunit/phpunit
来源：http://dali.cucudq.cn/Article/details/gt2xuumkbkv.html

[U79] PHP：静态分析
来源：http://dali.haohaochexian.top/Article/details/gt2thxmhbqg.html

composer require --dev phpstan/phpstan
来源：http://dali.ehwqpu.com/Article/details/gt2znrbeeng.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gt2irsekuxu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gt2tzyfcsvm.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gt2amzfosjl.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gt2zxmbjuhs.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gt2rvdyfufj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gotoacloud.top/Article/details/gt2stnpamey.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gt2fvyfklkk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gt2hozchigt.html

[U84] JS：CommonJS 写法
来源：http://dali.ppjwa.cn/Article/details/gt2kydtmlia.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gt2kxiixafi.html

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gt2kwkqkhyz.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gt2henpyljp.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gt2iambbptw.html

a ?? b
来源：http://dali.xuanzx.com/Article/details/gt2jzeofjos.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gt2mevqipmn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcmyocub.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gt2lzljrbtu.html

{ ...a, ...b }
来源：http://dali.tanke756.top/Article/details/gt2pkciucgj.html

[U89] JS：数组去重
来源：http://dali.yuxming.cn/Article/details/gt2gvillsoh.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2pslqqnsr.html

[U90] JS：数字数组排序
来源：http://dali.dianchejie.cn/Article/details/gt2iqiroiqf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2lmnhrlva.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gt2cvfscaim.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yangfankeji.com/Article/details/gt2rrnfsaba.html

[U92] JS：深拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2grwdmdqj.html

structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2xsksngoc.html

[U93] JS：模板字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2kwwmphrs.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gt2vzdwbswc.html

[U94] JS：箭头函数
来源：http://dali.havefunace.top/Article/details/gt2sxnkmdxs.html

const double = x => x * 2;
来源：http://dali.redwolf501.top/Article/details/gt2ophdxkci.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcmgstlh.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gt2oejakqul.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gt2rhxkqaga.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2ifdjbhnf.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gt2cnwjmkmx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2cfuqtqps.html

[U98] JS：fetch 带 JSON
来源：http://dali.dianchejie.cn/Article/details/gt2kfxpsytb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gt2oivxusvd.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gt2yzqsgerk.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gt2laicndjp.html

[U100] JS：DOM 查询
来源：http://dali.nanxuanxn.top/Article/details/gt2nqdgjxzh.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkrzvshb.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gt2icglkspi.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gt2vluidvge.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gt2dhaoazmo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gt2vdrneljp.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gt2idnsmpma.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gt2bupfvhpa.html

[U104] JS：防抖
来源：http://dali.cqqwz.cn/Article/details/gt2ngmewokl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sokyjswm.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gt2jlrbylnm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yongpay.top/Article/details/gt2xtsldegx.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2ctubqpva.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gt2atnwulyp.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2wbzujsgo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2ocrcsjvm.html

[U108] JS：随机整数
来源：http://dali.hnxiangtu.top/Article/details/gt2hoarweka.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sysykeji.top/Article/details/gt2znpdzbro.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgzwboli.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlsrgogu.html

[U110] JS：数组分块
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqmfppts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gt2fpkhyrog.html

[U111] JS：对象转 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2rclluisf.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gt2fmqyqlzi.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gt2riytokyw.html

"7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2yszmijsq.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gt2zqxrwwxo.html

s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2nnserbsd.html

[U114] JS：JSON 深比较
来源：http://dali.gogol.net.cn/Article/details/gt2ipnpbrim.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gt2uqjiwsbp.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2fdjlhbbl.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2nhnajecw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gt2atirlptx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2trtgjxie.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2gotubikj.html

npm i -D vitest;  npx vitest
来源：http://dali.hnqzz.top/Article/details/gt2bzautptm.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gt2rntosnve.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gt2bwdnqeeb.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gt2mclxiyjs.html

npx vite build
来源：http://dali.zhengqikj.top/Article/details/gt2cfvkpqmn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohzsksjc.html

import.meta.env.VITE_API_URL
来源：http://dali.aibaodan.cn/Article/details/gt2rfglfqpa.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ymfysdom.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjsudlxo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2iedqcwgw.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2lvsqaeok.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gt2xwooftsf.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gt2skmnpbgm.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gt2cpplvgqx.html

TypeScript ..... 212
来源：http://dali.shzxlz.cn/Article/details/gt2xyqparoh.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gt2lzcyrvtx.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2imyxahyc.html

Ruby ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2mygmixgu.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2pyqzrlqp.html

C .............. 30
来源：http://dali.yongpay.top/Article/details/gt2wljsjpgh.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gt2jfgnrgod.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gt2qcydoxfq.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gt2fmgnibir.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gt2cvqukhhp.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gt2fqnsixvq.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2khippzge.html

Perl ........... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llhwueyh.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gt2rcjjhxap.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2sbjmvtpt.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gt2qtbvkvdo.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gt2foalyjtj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gt2javqlapp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gt2qrtjgwuj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2uukqrmdm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gt2rzzgoaoh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gt2vomybope.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gt2thvtcjfc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2yptulpcl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2xkchovmi.html


<!-- 参考信息 -->