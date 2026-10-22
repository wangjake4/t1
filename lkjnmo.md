代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2ntvyrsri.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2dsrucwqk.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2hqsraidq.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gt2sjsvufli.html

val a = 1;  var b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2ibrqutea.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2jbqoizpr.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2jtgyqnju.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gt2jblwgeeu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhgwtufj.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2btbuzyat.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2asqetyiv.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gt2toohqnfd.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2mawahueq.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gt2ewlxzlcx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gt2jottdmlm.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gt2etwbphdy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gt2hjqttehc.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gt2ntwzvaid.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfavkade.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gt2fhtximls.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gt2rsjqpckw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ggpjkvzf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2zwrmnxky.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rjzggvyp.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gt2sddvludy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gt2csjeanqb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gt2rkaxdsmr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gt2jvhhybub.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxqzbjog.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgsseadt.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqwmsalw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gt2wppiepjd.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gt2zezzuohv.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2bvylrabo.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gt2dwusfvop.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gt2rirgmoss.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gt2icwgurac.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gt2zkielpoh.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gt2btvjsbqn.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gt2grrgchhd.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gt2lwltwzfx.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gt2vwotslan.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gt2urnjtkst.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wylaaiyk.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gt2ciwdewlc.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2lghmizus.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gt2qrbqokqy.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gt2sjvjzxpm.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gt2cmtivmzq.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gt2nanticlh.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gt2tfrgriqd.html

defaultdict(list)
来源：http://dali.jiagoushi.top/Article/details/gt2ncsrdmkd.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gt2xxjivcge.html

t = time.perf_counter()
来源：http://dali.gaohongyu789.top/Article/details/gt2pfcmakup.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gt2bwrioxsi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gt2xaqxknpd.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gt2sslkqdni.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjwoehuh.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gt2pklxdtno.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhwkrbyd.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gt2yoqvncsq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.iojbl.cn/Article/details/gt2wtnnnfnp.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gt2ywajvtfm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gt2uvekmwsk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gt2eedojmkc.html

@contextlib.contextmanager
来源：http://dali.xylfe.cn/Article/details/gt2cfnkekmj.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gt2xmqahorz.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gt2ceagghfr.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkmsaqia.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hammf.cn/Article/details/gt2boqralvp.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gt2qxmwwjjo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2vqxbnslq.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gt2cgimhuqa.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gt2ddbnxbml.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gt2yfqpnvxo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gt2ajbzdtlj.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gt2wadphuqu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ivvv.top/Article/details/gt2zvgzcexr.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2dowinsst.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gt2vvognrww.html

[U29] Py：属性校验
来源：http://dali.jianghu66.top/Article/details/gt2vjklkysi.html

@property 与 @x.setter 配合
来源：http://dali.yuxming.cn/Article/details/gt2khoecakz.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gt2qijmtuum.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gt2zlwddaio.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gt2arskuxnx.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuqtobqp.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gt2tumzxwhp.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2qmrqbycg.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gt2hqwivevo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gt2lrndvbew.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gt2njzrgtzm.html

chardet.detect(raw)
来源：http://dali.0kj1m.cn/Article/details/gt2yjhowybk.html

[U35] Py：发送邮件
来源：http://dali.jianghu66.top/Article/details/gt2njtgqmmg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gt2xukmefsf.html

[U36] Py：定时任务
来源：http://dali.bjfxy.top/Article/details/gt2ejqogmfj.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gt2faewtoap.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gt2jwxvgrfl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2crojwfwo.html

[U38] Py：获取脚本所在目录
来源：http://dali.tanke756.top/Article/details/gt2gcmtdcon.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gt2midinhdq.html

[U39] Py：判断是否在交互环境
来源：http://dali.snrcjt.cn/Article/details/gt2enuqjqet.html

sys.stdout.isatty()
来源：http://dali.wangdashe.top/Article/details/gt2ajpudogs.html

[U40] Py：打印到标准错误
来源：http://dali.bjfxy.top/Article/details/gt2bavxmtgr.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2eutxlwxb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.smart0.xyz/Article/details/gt2nupnjuqw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cashguo.top/Article/details/gt2rmtnqdjz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gt2znrdiufn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gt2wbjgbwgj.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gt2pilwainf.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gt2ewcqhbjn.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gt2vufkerkh.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzenfrtt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gt2dosfwpmj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2sdcvweiy.html

[U46] PHP：可空类型
来源：http://dali.jqgufenzy.top/Article/details/gt2texehvzx.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gt2rqhbbzct.html

[U47] PHP：联合类型
来源：http://dali.aibaodan.cn/Article/details/gt2zreutabk.html

int|string $id
来源：http://dali.ppjwa.cn/Article/details/gt2ueffdljd.html

[U48] PHP：纯枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2ybpuscxz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gt2hctsepil.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gt2aylmgxry.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gt2kyzbzpkd.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gt2miqdcneu.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ziegqqlv.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gt2ctnwglfm.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gt2qtalawjw.html

[U52] PHP：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gt2dwukdlwq.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gt2bjpyrlxo.html

[U53] PHP：空合并运算符
来源：http://dali.yj202588.top/Article/details/gt2pcxotfqa.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gt2masihres.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gt2kakorwbn.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gt2gcrsxsie.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2ailykppj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqfwoqlt.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gt2fqvspulu.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ylxelnhv.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2eckxvgzy.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gt2giplmssn.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gt2kljnbsql.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfvrgxpz.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwrxbegj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gt2twdqgunv.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gt2ovazdipu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gt2uzgsfsce.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gt2mfkqqgsu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2lykoxfms.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gt2rdajqqyb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gt2hvvmtwik.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gt2yhwmtiwx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwtztxnp.html

[U64] PHP：目录遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdgpvzld.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ehwqpu.com/Article/details/gt2wfukhqob.html

[U65] PHP：会话
来源：http://dali.jinqigfzy.top/Article/details/gt2wqfdgnbp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2tcqkfrkg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoupajt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aorberwk.html

[U67] PHP：处理文件上传
来源：http://dali.zdqjudy.top/Article/details/gt2uegliref.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxkkltmg.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swvxfxsx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2syxucuaq.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxuanxn.top/Article/details/gt2pjbkopww.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gt2kfoiwlow.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gt2gllvepjf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gt2dgbfttxo.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2ofepsafy.html

throw new RuntimeException("失败", 500);
来源：http://dali.yvedp.cn/Article/details/gt2sasbvojo.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gt2mzywcfjs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnxiangtu.top/Article/details/gt2duawxbry.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gt2ksyusgnt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkcfwvk.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2weksduhk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gt2pmbxqyki.html

[U75] PHP：依赖注入
来源：http://dali.jqgufenzy.top/Article/details/gt2detaaeej.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfhfyebr.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gt2cmsvkpyw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gt2giqmgwso.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gt2ylomiuwd.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gt2wutbknqz.html

[U78] PHP：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2dzqjzrok.html

composer require --dev phpunit/phpunit
来源：http://dali.xziqi.cn/Article/details/gt2xmqtzsbf.html

[U79] PHP：静态分析
来源：http://dali.jyoumei.cn/Article/details/gt2xzinxtsk.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gt2pumiulmh.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gt2chcbvufm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gt2uxdobtod.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gt2uefdtbdv.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gt2uewynwcq.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gt2dtfxngao.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhoulong.xyz/Article/details/gt2viyjijwy.html

[U83] JS：ES Module 导入导出
来源：http://dali.ppjwa.cn/Article/details/gt2cklrhdpf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2tnrvhvcc.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gt2ozjgdqqb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xylfe.cn/Article/details/gt2gtpexlsq.html

[U85] JS：可选链
来源：http://dali.guannengcc.top/Article/details/gt2ffvzqhrv.html

a?.b?.c
来源：http://dali.cucudq.cn/Article/details/gt2cxfnsknd.html

[U86] JS：空值合并
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahwecmxl.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gt2gfzhbivz.html

[U87] JS：解构默认值
来源：http://dali.jyoumei.cn/Article/details/gt2qyzrbgne.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gt2kyveppqc.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gt2dpqplgzr.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gt2qkbqgmyj.html

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gt2eoxdtuyz.html

[...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2zxszssgr.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gt2bpcusqdx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2pfoomzgo.html

[U91] JS：对象键值遍历
来源：http://dali.aibaodan.cn/Article/details/gt2zpxdxecn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhengqikj.top/Article/details/gt2qejdkhop.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2sqpevegk.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2moeqsdvt.html

[U93] JS：模板字符串
来源：http://dali.cashguo.top/Article/details/gt2hqxbbrnz.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gt2jknhwwnz.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlgdlczy.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbkoxkbp.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gt2pjuhrsqz.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258.top/Article/details/gt2brlxlohu.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gt2iahymhxs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2nbncxcfz.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gt2fsopkago.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2ytcqzcfu.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2rakyynqy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gt2oovojpuv.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gt2quraenwl.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gt2qluscfkx.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2erqrmfns.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gt2penrhyfr.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gt2ratjtczo.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gt2frcqnvwr.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gt2xkwhluss.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhixingplan.top/Article/details/gt2khrqgqkr.html

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sugpjcjm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gt2mnnvakbr.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gt2rpyooxti.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gt2tetrttmp.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gt2rrrypdyq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gt2wshnypre.html

[U106] JS：日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2aboqzlfc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gt2hwwlkczb.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2drxhqgef.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2yqftusoj.html

[U108] JS：随机整数
来源：http://dali.shuidangran.top/Article/details/gt2jjdsyvpe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gt2opxyvrst.html

[U109] JS：数组分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2oawjxmri.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2lnumiwmg.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gt2hslrqbdv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gt2sliltran.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gt2rqoqtagn.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gt2gyzgmfrj.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gt2aqzignjt.html

"7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2dlsnbcwx.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gt2covvgktw.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2zlvbooli.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gt2veoiieoq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2llqrifhv.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2ztjwmmcg.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2ydponhts.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gt2tjwryhhl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qdlpobcy.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gt2jxmmfmlx.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gt2ohyzojge.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gt2mkmhvixa.html

npm i -D vite;  npx vite
来源：http://dali.jiagoushi.top/Article/details/gt2lqbfcats.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtynnnso.html

npx vite build
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nslhwisa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenlongwang.top/Article/details/gt2vowypaot.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2ipsubmqe.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wmqtjerk.html

统计汇总
来源：http://dali.nanxuanxn.top/Article/details/gt2rtvcvmab.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ciwqlozk.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqzkmrsc.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gt2repjoria.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2noqgbfiz.html

JavaScript ..... 252
来源：http://dali.yj20258.top/Article/details/gt2ivnkuman.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gt2xkwmfsjn.html

Java ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2zjafumzq.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gt2purpbqwu.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gt2ggbpikpc.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gt2pcjudhhb.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gt2eaqafhjf.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gt2cyelwaiv.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gt2stvbheup.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gt2qgnrzjmn.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gt2njemdxuf.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upsgtvpx.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gt2qfoscgjf.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnhunpje.html

Scala .......... 10
来源：http://dali.cucudq.cn/Article/details/gt2hzqzuywp.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2whypfjam.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gt2aoqwqrfb.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gt2vinsntle.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2peucfquw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gt2dpnmnjrz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2qkarvgxf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2cdwclirk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxuanxn.top/Article/details/gt2skfwvqgo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2evrlwooj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gt2qawnfdqu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2scmrsgxl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2tetmrayx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2jkngtwhu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2pzorozvd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2ylvibngt.html


<!-- 参考信息 -->