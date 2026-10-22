代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtrlglsevb.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdwfztqdn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gtenwvqwbk.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtnqmwrtxi.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gtezqarylr.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtvdjjpvwq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gthajjdmvt.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gtndifgasf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtxkxdjfth.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtrjdbtmhh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrvhnfxo.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtoelynavu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtuyuklfdm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtehlendzn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtixfbiedn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzosouvui.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtnxsadoil.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cdnleiting.top/Article/details/gtqjgfritv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtrtetpihy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtyqmnizzh.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtljkstpdt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gtlviukbfu.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gteeunbgjc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ppjwa.cn/Article/details/gtaqartuqt.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gtelqewnvx.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtrwzzqcxt.html

[U06] Py：合并两个字典
来源：http://dali.sufxvd.cn/Article/details/gtafrvmqgq.html

{**a, **b}
来源：http://dali.yanxiufei.cn/Article/details/gtoioiegvj.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gtwwbjulxf.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtlqttxxgh.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gtlkrcekzg.html

[y for x in nested for y in x]
来源：http://dali.aibaodan.cn/Article/details/gtjfmjnhxz.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtrxjmchnz.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gteexrnbgs.html

[U10] Py：按值排序字典
来源：http://dali.jqgufenzy.top/Article/details/gtqizudpdd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtieyoniwi.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtyyqcmlvg.html

(x * 2 for x in arr)
来源：http://dali.chenlongwang.top/Article/details/gtexxkwvxf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtjossudhr.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtsycnlxlw.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gttbmxqewu.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gttqpxjagt.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gthmyfxwyg.html

defaultdict(list)
来源：http://dali.hfpthk.cn/Article/details/gtmmamneyd.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gtxjmwhyna.html

t = time.perf_counter()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvkwfadu.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtvuqmxdvw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbabpeauo.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gtfthuodgb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtzzdwlawk.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gtuwqxlilm.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlxaiuxk.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gtjwpraspv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gtmltzcazx.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gtiywuyjmd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gttflrygfm.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuetiantiany.cn/Article/details/gtkakypose.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gtacmjrwhf.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gtzxjboyai.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gtjgtppxav.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfxjpkjda.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtlarppbfd.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupipkyva.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtrxgfgcwp.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gtioswbjqw.html

csv.DictReader(f)
来源：http://dali.xinyue.icu/Article/details/gtxjyksdsu.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtlmvohovg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gtucpcndjj.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtkxplxfch.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gtkloqtfzf.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gtzxcgnvry.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gtaaxzlxfa.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtgvrpljaa.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtdcngnyup.html

[U30] Py：数据类
来源：http://dali.shzxlz.cn/Article/details/gtiboiiuer.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gtltzrhyel.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gtqsrqiqhn.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gttdsbuhwh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gtxylkwlwn.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gtqshpoeog.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtukdvcawi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ehwqpu.com/Article/details/gtpmdtyurw.html

[U34] Py：判断编码
来源：http://dali.gzhubu.top/Article/details/gtmjodsfug.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gtrkwrhkje.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gtiizvrlty.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtqcyfobvt.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtgundhequ.html

schedule.every(10).minutes.do(job)
来源：http://dali.pycfn.com/Article/details/gtwidvafay.html

[U37] Py：读写 Excel
来源：http://dali.haohaochexian.top/Article/details/gtozapdzso.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gtiwqbdina.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtvjdgjnaq.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gtoutcarue.html

[U39] Py：判断是否在交互环境
来源：http://dali.hfpthk.cn/Article/details/gtkyvvllcv.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gtkkbpgzcx.html

[U40] Py：打印到标准错误
来源：http://dali.tian-w.cn/Article/details/gtjgricyxn.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtdayfsvoi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gtdypdcppa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gturrokgry.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gtaubozlzm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ivvv.top/Article/details/gtxrrejtkr.html

[U43] PHP：声明命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtikuwjnog.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gtiimujvte.html

[U44] PHP：开启严格类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubvzpbii.html

declare(strict_types=1);
来源：http://dali.jqgfzy.top/Article/details/gtadegucdc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtfsbrqell.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtrerutvxc.html

[U46] PHP：可空类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqlhndhg.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtuavygcae.html

[U47] PHP：联合类型
来源：http://dali.zdqjudy.top/Article/details/gtxqiruqkd.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gthuouswzn.html

[U48] PHP：纯枚举
来源：http://dali.zhoulong.xyz/Article/details/gtkezmuacw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzgapmac.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gtcutzdcuz.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtgfloytik.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtfyfmamwp.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtajkmhoqz.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gtnbnhejfk.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gtwijvtpyd.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtcyaaaatl.html

$double = fn($x) => $x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtnqopptqv.html

[U53] PHP：空合并运算符
来源：http://dali.yongpay.top/Article/details/gtqpysytiv.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gtlzsvjhei.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtssqwtzvf.html

$obj?->method()
来源：http://dali.xinyue.icu/Article/details/gtnckngrit.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gtrtcleooy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtzwymetye.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gtbgeicodp.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtsnfmxpew.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gtcoghymxq.html

"值: {$a}"
来源：http://dali.xuetiantiany.cn/Article/details/gtxppdvvmw.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gtdmjhiini.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtbzcqkzwo.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtimhsvtjk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtlyfoqsgy.html

[U60] PHP：JSON 编解码
来源：http://dali.quarkkingdee.top/Article/details/gtazwdqxkp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenlongwang.top/Article/details/gtkunjgsda.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gtdqljyobx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtqoipesty.html

[U62] PHP：日期对象
来源：http://dali.gotoacloud.top/Article/details/gtwuaakacd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgohbiutn.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtgvajkvvt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gtrlmqvlei.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtuyhswfsz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fzhhl.top/Article/details/gtmtuayrmi.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gtduzdaxkh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtyzdhakyw.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gtnhswxlle.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.316326.xyz/Article/details/gtssrwepar.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gtmjybtttq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tian-w.cn/Article/details/gtkcmzmvfy.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gtdivqubrr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fengsongda.top/Article/details/gtugrzrrlv.html

[U69] PHP：PDO 预处理
来源：http://dali.yanxiufei.cn/Article/details/gtdviobpxf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gtlnugbkcc.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gtkqvqntaq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtofljqirm.html

[U71] PHP：抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtzcjutspo.html

throw new RuntimeException("失败", 500);
来源：http://dali.smart0.xyz/Article/details/gtblclbddb.html

[U72] PHP：写错误日志
来源：http://dali.zycfv.cn/Article/details/gtlpzwmjti.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gthfapvhds.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtvbhslzsk.html

parse_ini_file("config.ini", true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmsvfwaa.html

[U74] PHP：读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtjnrqdxhv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dashuyun.cn/Article/details/gtzvoltvyi.html

[U75] PHP：依赖注入
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyxodyag.html

composer require psr/container
来源：http://dali.jiagoushi.top/Article/details/gtpwplcyyr.html

[U76] PHP：简单路由
来源：http://dali.ehwqpu.com/Article/details/gtwreuegis.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gtcfdohpna.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtlavskesv.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gtaznkeiaf.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtvnvfdnhi.html

composer require --dev phpunit/phpunit
来源：http://dali.daxiang520.top/Article/details/gtgvqmmrlh.html

[U79] PHP：静态分析
来源：http://dali.birdmap.top/Article/details/gtnevefscp.html

composer require --dev phpstan/phpstan
来源：http://dali.quarkkingdee.top/Article/details/gtcdtmucms.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gtkaufjkbq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gtthnbgeio.html

[U81] JS：初始化项目
来源：http://dali.yj20258.top/Article/details/gtxcqhhvxu.html

npm init -y;  npm i express
来源：http://dali.zdqjudy.top/Article/details/gturrrvzea.html

[U82] JS：package.json 脚本
来源：http://dali.yueranfly.top/Article/details/gtonoxrwxj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gzhubu.top/Article/details/gtvhtmnbet.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gtlvdqlynp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtopxotdrv.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gtnkjheiex.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuanzx.com/Article/details/gtfzkboffm.html

[U85] JS：可选链
来源：http://dali.yj20258.top/Article/details/gttxpejoaz.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gthsilehas.html

[U86] JS：空值合并
来源：http://dali.shuidangran.top/Article/details/gteyllhkju.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gtrfrxhcmy.html

[U87] JS：解构默认值
来源：http://dali.daxiang520.top/Article/details/gthunqwqrd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvzffnjf.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gtgfucrdfn.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gtuoaplxei.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gtdragprlk.html

[...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtznbwrfve.html

[U90] JS：数字数组排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclzizjcj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtslufhghn.html

[U91] JS：对象键值遍历
来源：http://dali.hnxiangtu.top/Article/details/gtwisoazzk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangshuangyany.cn/Article/details/gtfyranyqj.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gtafuwhvje.html

structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtjissvgjs.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gtlynmsfru.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gtnyelhzfo.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtpdrrmtbg.html

const double = x => x * 2;
来源：http://dali.meibo888.top/Article/details/gtuczjnclq.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gtkkabxdgd.html

new Promise((resolve, reject) => {})
来源：http://dali.c1oappe.top/Article/details/gtntfscnjm.html

[U96] JS：async/await 与异常
来源：http://dali.feifeiyinyue.top/Article/details/gtsoqgsyhw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtdufsiqfp.html

[U97] JS：并发请求
来源：http://dali.chenjidiqi.icu/Article/details/gtuosxtyks.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtpwpjhdtw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zycfv.cn/Article/details/gtwvtvihou.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtspcqiror.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfxwjogb.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gtiplccsby.html

[U100] JS：DOM 查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviqenvch.html

document.querySelector(".item")
来源：http://dali.yueranfly.top/Article/details/gtcjfzdrql.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtnakzcule.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtdoqczgzh.html

[U102] JS：本地存储
来源：http://dali.ybcxt.top/Article/details/gtcspxzisn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhoulong.xyz/Article/details/gtwnnnbugf.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gtxgbcmcet.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupmdqhkp.html

[U104] JS：防抖
来源：http://dali.gzhubu.top/Article/details/gtdwchtbyg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtpqjrscdn.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gtnjwjetrg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtijzvsnzc.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gtkgvvcoll.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gtzmceicro.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwapcrdfy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtablpmowb.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gtwfbgliob.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gtwfiutxwb.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gtotkzodaz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtshstaygh.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtzkwesrdx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyozatsf.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktltcsoo.html

new Map(Object.entries(obj))
来源：http://dali.hnqzz.top/Article/details/gtxbbmxirs.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gtxnmbqkhy.html

"7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtbtzjfhuq.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtfemrhibg.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtmhegxmbe.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtwsjopalo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtbrdkxxsk.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtvibamnjh.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtoavwznab.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gtrrjtuyfv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gtvuefmzkl.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gteyeqytiv.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258888.top/Article/details/gtdoullcsg.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gttakrrwmy.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtxtmmigoh.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtgaangn.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtlfflguma.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gtfwamckmz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gtrdjxjbdc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmlaqatqj.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gtdyiwjjwq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqnufjbbe.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtwbqaulqp.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtdqxpzthp.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gtttmeawpt.html

JavaScript ..... 252
来源：http://dali.birdmap.top/Article/details/gtyvzemwsc.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtdakqhfbu.html

Java ........... 212
来源：http://dali.fzhhl.top/Article/details/gtkitobcjn.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gtmymxjbgk.html

Ruby ........... 212
来源：http://dali.xylfe.cn/Article/details/gtqbrvulvh.html

C# ............. 212
来源：http://dali.jyoumei.cn/Article/details/gtnjggsvuj.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gtyjceaiow.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtpsikgnpx.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gtsjmxmurh.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gteiobqkta.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtajmjhrvu.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gtuwodswxf.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gtmaleimkm.html

Perl ........... 10
来源：http://dali.yongpay.top/Article/details/gtclzpejvk.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gtabntpwep.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtjfrcthyo.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gtrmevixmf.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gtnmdlsxxp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtuoxtgjvy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtauyakawj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtcvykgkqy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtamumkpda.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daria6918.cn/Article/details/gtwxdmhmzw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gthbcithaa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtdmrwzily.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtjmycihkg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtmtfwqubi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtuxpcmruc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtojnoiihm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtarxwvvlr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtuaccjjjc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtxlipzygf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj202588.top/Article/details/gtxcisfhie.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtsectohud.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gtewfhvttk.html

R Bash 专题                             80
来源：http://dali.hammf.cn/Article/details/gtdqkmcspj.html

S C / C++ 专题                          60
来源：http://dali.9152youxi.cn/Article/details/gtlqlcltau.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtqdfcvgsw.html


<!-- 参考信息 -->