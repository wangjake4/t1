代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtejdggrgx.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtebcdnqll.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtwppdkxai.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gtdppziith.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtmbiwdoqc.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtqtejltup.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtpptuwqru.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gtkmzjwwzx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtvnkyqdcm.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gtzaolmmtq.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtskufvqcr.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gtbdqexubv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtrerowdfg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteckmqyfd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gtwfwbmnbj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbwdhskyk.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtvaxpwffp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtswhgbpge.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gtncbbkksl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gtrhrxdaki.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtownnwemp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtmspbcyvp.html

[U04] Py：变量调试打印
来源：http://dali.vqdsnc.cn/Article/details/gtpxqfxudt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtscvbpjzg.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtosnqajbi.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtuxfcknac.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbszdjmw.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gtbiyqxmsa.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtaezaiclq.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gtgtwmyosd.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtyfittyyn.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gttkrpgjgz.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gtiifpicdd.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gtnizhjxzj.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtbowndbxz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gtzbqytovt.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtbrnqekkn.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gtzszdceny.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhhbemls.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gthmuuxdyg.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtyfrxccqa.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gtclshazue.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtkbspxgqv.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtgjlkqpzi.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtvgmhtywq.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtetemrald.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gtwczbrbpd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtcdwzxwxz.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtlitxjpou.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtjjcheqcs.html

[U18] Py：预编译正则
来源：http://dali.aizwys.cn/Article/details/gtjwlartcw.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gtvefbcyum.html

[U19] Py：正则替换带回调
来源：http://dali.shangyingyoupin.top/Article/details/gtvilctccd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjzrrkwa.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtvsbehjcx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gtvwmvcuea.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtcndqjabq.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuudtceny.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtnlfwpezf.html

list(zip(*m))
来源：http://dali.pycfn.com/Article/details/gtigmmcxla.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtccejcblx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtqodlgsop.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtxhwffolb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsjdlnap.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtlmuhdpnq.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gticeldcrg.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gttxrjflgk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtymfjbkpj.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gtpacsunns.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gthmiapifi.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gtkvpovvhg.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtvdsgvagu.html

[U29] Py：属性校验
来源：http://dali.jlsjyb.cn/Article/details/gtuwdfeold.html

@property 与 @x.setter 配合
来源：http://dali.tianlin.xyz/Article/details/gtwzfaymdu.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtehzuabdt.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gtuipnrfiz.html

[U31] Py：单测
来源：http://dali.yj202588.top/Article/details/gtcgpkxicw.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtyprsdgsg.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gtgioqgdjo.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gtdwioruzc.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtfxluvetl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtzofskhfe.html

[U34] Py：判断编码
来源：http://dali.quarkkingdee.top/Article/details/gtuotgzhxs.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gtrvxdwcub.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gtpsgizblb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gteillcxgi.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gturblmrfv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtisrwzyrr.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtuwhcmcux.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtoejbpecl.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gtwkcvzlqt.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gtcljdfahe.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gtrjxstiyp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtnyrqntkf.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtssiveksp.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtasffgapx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigufen.top/Article/details/gtsnledjdu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dashuyun.cn/Article/details/gtlutkshlc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtddavrdlj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtirjkca.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gthkfriqvk.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gttssigler.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gtpkddnrye.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gturdaoevo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtyhjuteaz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtyiftzzbr.html

[U46] PHP：可空类型
来源：http://dali.c1oappe.top/Article/details/gtsvrsnnux.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gtdmkgjiau.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtodvchdld.html

int|string $id
来源：http://dali.guannengcc.top/Article/details/gtowaxsgwv.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gtsthkrett.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gtdwtjcpnb.html

[U49] PHP：只读属性
来源：http://dali.tianlin.xyz/Article/details/gtuinrfhvy.html

public readonly string $name
来源：http://dali.9152youxi.cn/Article/details/gtvaskogso.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gtiglshxxc.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gtywpnlpkp.html

[U51] PHP：数组解构
来源：http://dali.sweek.top/Article/details/gteeegrazs.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gtimrnkcne.html

[U52] PHP：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtpqcyrbds.html

$double = fn($x) => $x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtbpznnzjm.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtgwlilwhx.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgelvyjb.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gtziirfgwb.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gtlvznnxru.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gtzlvuabwq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtgfxugzyp.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbgsspos.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtjzhnptcu.html

[U57] PHP：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtaurfewmq.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gtsvcdpqyu.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gthmxrtjoq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gtztouctpu.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gtkvzrncxq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwdetqlp.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258.top/Article/details/gtbdalwoww.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gtfrepmlxh.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtbvunyrxh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtndvngtbu.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gtpveelkxl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gtonwsmhqu.html

[U63] PHP：文件读写
来源：http://dali.fengsongda.top/Article/details/gtfiseqqbg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gtdcdbhyyu.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gtxmdxmbig.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shangyingyoupin.top/Article/details/gtlzzpjmzv.html

[U65] PHP：会话
来源：http://dali.ybcxt.top/Article/details/gtnoulfvpa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwqeritu.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gtqttwhgdf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gteszplsrw.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gtkawgsaxq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxuanxn.top/Article/details/gtwubjkyhf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gtknmhozpi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gtbxlsokiy.html

[U69] PHP：PDO 预处理
来源：http://dali.zycfv.cn/Article/details/gtcxljcskz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxinkj.top/Article/details/gtoenlxdkl.html

[U70] PHP：PDO 事务
来源：http://dali.hywenlv.cn/Article/details/gthrltvpjx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gtzixeitfh.html

[U71] PHP：抛出异常
来源：http://dali.pycfn.com/Article/details/gtlxgmxlwy.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgfzy.top/Article/details/gtbudpcbpr.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gtxcwfgmqc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuanzhike.top/Article/details/gtuaytdzxm.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenjidiqi.icu/Article/details/gtegpntkex.html

parse_ini_file("config.ini", true)
来源：http://dali.daxiang520.top/Article/details/gtxscrqefz.html

[U74] PHP：读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtubyiykoa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gtijbcotvk.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtapyfkihn.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtkmvnpnsh.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtrjmydqka.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuanzx.com/Article/details/gtgdzrlumi.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtcygykgrd.html

composer require twig/twig
来源：http://dali.zdqjudy.top/Article/details/gtwocdwteq.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvtpbhtk.html

composer require --dev phpunit/phpunit
来源：http://dali.jiagoushi.top/Article/details/gtgiogdbbc.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gtcanhmgpm.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gttfzycgwr.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gtovdptnot.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gtmxeadhzu.html

[U81] JS：初始化项目
来源：http://dali.vqdsnc.cn/Article/details/gtfyxzsnul.html

npm init -y;  npm i express
来源：http://dali.pycfn.com/Article/details/gtbosvwjmm.html

[U82] JS：package.json 脚本
来源：http://dali.0kj1m.cn/Article/details/gtcjebtrhg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnqzz.top/Article/details/gtewtnfexp.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258.top/Article/details/gtvikzioqa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtpwlwnszz.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtdirdtvhl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ybcxt.top/Article/details/gtbgjqviyw.html

[U85] JS：可选链
来源：http://dali.ydzc1.top/Article/details/gthmmidlgj.html

a?.b?.c
来源：http://dali.yj20258.top/Article/details/gtexhrceoj.html

[U86] JS：空值合并
来源：http://dali.yj20258.top/Article/details/gteffumpzq.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gtwxepmxat.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gtkkjqfyef.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gtzztnewuw.html

[U88] JS：对象展开合并
来源：http://dali.svipenyu.cn/Article/details/gtnhpgmuhn.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gtigilcmyi.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gtzfwuhqnd.html

[...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtzexixdiz.html

[U90] JS：数字数组排序
来源：http://dali.zhiwuduotai.top/Article/details/gtskmrjfln.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtwowjzpod.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gtlzknkgls.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gtibqiblos.html

[U92] JS：深拷贝
来源：http://dali.jinqigfzy.top/Article/details/gttwwrzyzx.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtkhnfcxqu.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gtkfhfkegs.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtjndscuiz.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtdhtvgisk.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gtsxwwqtxb.html

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gthfynheen.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gtesffjszz.html

[U96] JS：async/await 与异常
来源：http://dali.xinyue.icu/Article/details/gtklukgzts.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtuqmeivml.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gtgdksbrbj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtkkqeyfgu.html

[U98] JS：fetch 带 JSON
来源：http://dali.dashuyun.cn/Article/details/gtzjurabfy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gtfxniqjls.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeznsiyb.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gtsabzroyb.html

[U100] JS：DOM 查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixrfahsl.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gtcmtupylj.html

[U101] JS：classList 操作
来源：http://dali.jiagoushi.top/Article/details/gteldbnxnm.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gtvawqufgc.html

[U102] JS：本地存储
来源：http://dali.nwbrower.top/Article/details/gtgmnygsoc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sxryk.cn/Article/details/gtbrzfniqx.html

[U103] JS：定时器
来源：http://dali.cashguo.top/Article/details/gthklzmasl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gtxhvdwpwm.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqsmajtx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gttrvnnhum.html

[U105] JS：节流
来源：http://dali.jiagoushi.top/Article/details/gtmvxshkey.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shuidangran.top/Article/details/gtbfsnxisd.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtacwahseq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkdhqloi.html

[U107] JS：数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtysbccctk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtolgrucfs.html

[U108] JS：随机整数
来源：http://dali.pengpengdd.cyou/Article/details/gtppivixsg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ydzc1.top/Article/details/gtywmkocpd.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gtadnogilv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtlefosiuw.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gtnbjdupro.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gtopheezvx.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtcxkgwwne.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gtlaeqryxn.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gtcnpojwby.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtdmamnvha.html

[U113] JS：正则替换全部
来源：http://dali.cashguo.top/Article/details/gtivygngxj.html

s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtdajmkywm.html

[U114] JS：JSON 深比较
来源：http://dali.xinyue.icu/Article/details/gtjucfzkuc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gttmuisjrg.html

[U115] JS：生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtlfxumgut.html

crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtasfjpabf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtvfkjesns.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yangfankeji.com/Article/details/gtsykfgbgy.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gtdqshafkx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gtvuixvlcc.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gtatuzwpgr.html

npm i -D vite;  npx vite
来源：http://dali.shangyingyoupin.top/Article/details/gtcbpuyvnk.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtqxxhamwj.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gtjjgbbdmy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aibaodan.cn/Article/details/gtzeaphdhu.html

import.meta.env.VITE_API_URL
来源：http://dali.tianlin.xyz/Article/details/gtqqmshlvj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmrltwuaq.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gtpzpgiaxh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteoqsgxja.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlprhkrmv.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtqymrvdgq.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gtfnyqykod.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtpgivbodd.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtagezsizp.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gthuwtdwqr.html

Go ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtwoipfahl.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklyndvcu.html

C# ............. 212
来源：http://dali.cucudq.cn/Article/details/gtwydrbxuw.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gtazugrpwz.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtgcykjtqf.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtdtxjicfw.html

Bash ........... 80
来源：http://dali.daria6918.cn/Article/details/gtfkrhsjlp.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gtrxbvpxcn.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gtirngbaeg.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gtveweowbs.html

Perl ........... 10
来源：http://dali.tianlin.xyz/Article/details/gtopfnvcwh.html

Scala .......... 10
来源：http://dali.zhongyouzk.top/Article/details/gtwjowesfb.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtfkijllou.html

合计 ........... 2106 条
来源：http://dali.yvedp.cn/Article/details/gttpfyoblv.html

按章节统计：
来源：http://dali.zhixingplan.top/Article/details/gtqohgukkk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvgyxgkh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtbkltkdhl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtpjiciwom.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtobcjvvck.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.c1oappe.top/Article/details/gtclpqgrxz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtvifwdgmk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtidjbwxwl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtyulneuhw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtkosukzwa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtazagqruc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtboombfqg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtzprklctr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtcromecri.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtziebxbug.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gteaxrertp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtteimptji.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gttpydiwdy.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gtpgwewnta.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtdldobssn.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gtqertbtaq.html


<!-- 参考信息 -->