代发 wailian999

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2qedryquo.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzvevydv.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2bzhpkqkz.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2uljqmgaf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gt2bkhnmxtr.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2iyzmqkan.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gt2gofirbkw.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gt2fmlwqkno.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2fkoixugx.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gt2snqgvpsp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gt2kxzvhhes.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykpnjifa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gt2welvjspw.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gt2yrjdlpda.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2osqvlxzq.html

[T60] Scala：折叠
来源：http://dali.cucudq.cn/Article/details/gt2goedwalx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gt2skxfyltu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wxozohxq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gt2omyfszur.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zrafxfjd.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gt2iamobcjl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gt2atylzncc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gt2ztnkvnjq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gt2npylltmy.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gt2cbqtwoqm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gt2bkcbprto.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gt2qxefmbwb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gt2rmyeknfq.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gt2lcdmkhhf.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2heaejnlq.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gt2ulgpaged.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gt2csnbxidn.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylybxebl.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gt2lyecvsyo.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yndbqzgn.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gt2tleodbbf.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gt2etaxnfhs.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gt2oyzlectf.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gt2xjrpconj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gt2jqjbliee.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2gjicjmjm.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gt2zhyzfeui.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gt2ouzohgcl.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gt2whijezvu.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gt2ojtefdrd.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gt2fcsoyvxr.html

[U14] Py：分组收集到列表
来源：http://dali.yuxming.cn/Article/details/gt2ttgotzff.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gt2jidhgxks.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gt2rpvdcheq.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouihozzq.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gt2fjdmagcb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gt2agxlejss.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gt2uafgytnl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gt2conqiasf.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gt2eaymfxxs.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2ddiyfvcg.html

[U19] Py：正则替换带回调
来源：http://dali.sxryk.cn/Article/details/gt2znimjhbn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gt2ybobjzkb.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gt2tyqehxjl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gt2wgirwjhe.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gt2dgivbrmm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkgozzv.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gt2dyvqglma.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gt2fqqhtpwe.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbkuurdu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gt2xstamjzj.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwbtauag.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2lkjsnjsi.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gt2ondwtgrm.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gt2uawfkrsj.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gt2iertjgxk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj202588.top/Article/details/gt2zzlbtiwd.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zaybkapq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gt2omcfwsls.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gt2qiltlbxr.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gt2etjnqmgx.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwurkmjj.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gt2mhvqskrb.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gt2uriflknj.html

@dataclass(slots=True)
来源：http://dali.shuidangran.top/Article/details/gt2krcffqum.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gt2ptenbzyu.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gt2qnahivff.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gt2pnkwhety.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gt2jlgkzavh.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gt2pwiqigwj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuanzhike.top/Article/details/gt2ckgkqvto.html

[U34] Py：判断编码
来源：http://dali.redwolf501.top/Article/details/gt2xawaewrv.html

chardet.detect(raw)
来源：http://dali.fengsongda.top/Article/details/gt2fxtcizpr.html

[U35] Py：发送邮件
来源：http://dali.cucudq.cn/Article/details/gt2lvgbnxmj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gt2hjcrrmni.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gt2kfeceupf.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gt2vlxnefrt.html

[U37] Py：读写 Excel
来源：http://dali.meibo888.top/Article/details/gt2hesufpar.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oymlnfmj.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258.top/Article/details/gt2enptmrxf.html

Path(__file__).resolve().parent
来源：http://dali.chenzaomai.com/Article/details/gt2nisdqgzf.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gt2efvhplov.html

sys.stdout.isatty()
来源：http://dali.sxryk.cn/Article/details/gt2ayoegqfc.html

[U40] Py：打印到标准错误
来源：http://dali.cdnleiting.top/Article/details/gt2fqgzaxie.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2slemogqd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gt2ardaxxci.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gt2vramvogt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gt2lyhdekmh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jianghu66.top/Article/details/gt2zymgnhwr.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2lgtozplr.html

namespace App\Http;
来源：http://dali.xuetiantiany.cn/Article/details/gt2izsgdmoc.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gt2pswlimex.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2nfwffrzx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gt2xjgmjsrf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2txfzigcp.html

[U46] PHP：可空类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtgsciuo.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gt2brmqjzho.html

[U47] PHP：联合类型
来源：http://dali.bjfxy.top/Article/details/gt2dhcasxkk.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gt2egqxkmmk.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkfhzkdf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xziqi.cn/Article/details/gt2gzrayypj.html

[U49] PHP：只读属性
来源：http://dali.yonumen.top/Article/details/gt2xocxrmbe.html

public readonly string $name
来源：http://dali.jianghu66.top/Article/details/gt2myoglyeq.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gt2ocrkbsva.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gt2wdhlazpt.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gt2mhsvhfud.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gt2tgeajihr.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjlpnlje.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gt2hprkchxu.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gt2uzpnhmfi.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gt2zagwagyf.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzqtgrah.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gt2ziyzptzi.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2dtcdbwim.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.iojbl.cn/Article/details/gt2wgquhxnc.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2geddopre.html

f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2ictzfdwj.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2bvohadbc.html

"值: {$a}"
来源：http://dali.jqgufenzy.top/Article/details/gt2qqitlfjo.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gt2vscixghu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2dgtypqzb.html

[U59] PHP：自定义排序
来源：http://dali.svipenyu.cn/Article/details/gt2semcqpsb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqpxmxjw.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2ishlhvon.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gt2zzjkrqpv.html

[U61] PHP：正则
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxwobnud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2euyglvos.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gt2rijtvwwc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gt2pvrbgdzi.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gt2mzdwokkh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gt2clgajyft.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gt2ooqedzzu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eeqfxofh.html

[U65] PHP：会话
来源：http://dali.sysykeji.top/Article/details/gt2xnbrqobv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2rnsceohx.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gt2aipbvylt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gt2crchmwer.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gt2pqqdnqmf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tian-w.cn/Article/details/gt2vyjwnxoc.html

[U68] PHP：PDO 连接
来源：http://dali.wangdashe.top/Article/details/gt2xfyvusyn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gt2lekwntcc.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gt2nhrxcowr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gt2cyysmxos.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gt2ygwvgpzw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gt2ssufrafe.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2npvmzezw.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gt2luwkbvyh.html

[U72] PHP：写错误日志
来源：http://dali.yuanzhike.top/Article/details/gt2owmeuhnj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gt2hjxpfwth.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gt2zwrusvhi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gt2opmcskgo.html

[U74] PHP：读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2iltmefbg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fengsongda.top/Article/details/gt2fftrufbx.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gt2nkiympwo.html

composer require psr/container
来源：http://dali.jiagoushi.top/Article/details/gt2badcwmgv.html

[U76] PHP：简单路由
来源：http://dali.xziqi.cn/Article/details/gt2lgjtfcok.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gt2eddgrivm.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gt2pjwbdaxx.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gt2uspxsjam.html

[U78] PHP：单元测试
来源：http://dali.yonumen.top/Article/details/gt2bfyplzcw.html

composer require --dev phpunit/phpunit
来源：http://dali.wangdashe.top/Article/details/gt2jnxirijl.html

[U79] PHP：静态分析
来源：http://dali.chenzaomai.com/Article/details/gt2zanlplkz.html

composer require --dev phpstan/phpstan
来源：http://dali.yangfankeji.com/Article/details/gt2kzjsoigg.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gt2odilijab.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gt2diufxllk.html

[U81] JS：初始化项目
来源：http://dali.fengsongda.top/Article/details/gt2zirciklu.html

npm init -y;  npm i express
来源：http://dali.yj20258.top/Article/details/gt2kjgdrwsp.html

[U82] JS：package.json 脚本
来源：http://dali.zhoulong.xyz/Article/details/gt2jbkbyxrz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.mhx1999.top/Article/details/gt2bmncnnqo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdtstcvx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oprbjine.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gt2kprmffym.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gt2bfwgilxu.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gt2qmmtgduq.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gt2wmypeqex.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gt2yskhdzzx.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gt2wzywluoj.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gt2retgehkz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fzhhl.top/Article/details/gt2hxjiokpk.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gt2fkulnuaj.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gt2kngavhen.html

[U89] JS：数组去重
来源：http://dali.jiagoushi.top/Article/details/gt2zamqjtlt.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2nnbufjkr.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gt2owrfajlu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2jbtouvjh.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gt2ttfkgsoh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gt2ogrvlldw.html

[U92] JS：深拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdjapoeg.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2rvlgcnge.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gt2kalstusn.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gt2qkoquntu.html

[U94] JS：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gt2uehbcraa.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gt2zzjrficy.html

[U95] JS：Promise 包装
来源：http://dali.yj20258888.top/Article/details/gt2zomzibzi.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigufen.top/Article/details/gt2ecolwlhn.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofjgvvey.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2yqgcyccd.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gt2vaxjkpgy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2qjccuosb.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqqkjrfn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2qhayvgkk.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gt2mftctata.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2aqyizken.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gt2bzuiigcu.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gt2qonaawsx.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2rqdvoshy.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gt2rlifzgjx.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gt2fspjfkzr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gt2ypulqfup.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gt2izmzfowh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2azjmedxv.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gt2fweoapvq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwiwxkxs.html

[U105] JS：节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdjttcyx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggibgrqh.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2lolqplor.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tianlin.xyz/Article/details/gt2kvmlzves.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2shkwfpff.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gt2gmawuqyd.html

[U108] JS：随机整数
来源：http://dali.cdnleiting.top/Article/details/gt2dtkozwcw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gt2wxvjaihx.html

[U109] JS：数组分组
来源：http://dali.cucudq.cn/Article/details/gt2zdmbusxb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2cirbaqfd.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gt2qljrlozo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gt2hhkyquhz.html

[U111] JS：对象转 Map
来源：http://dali.jqgufenzy.top/Article/details/gt2exsmrdng.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2awofpfxp.html

[U112] JS：字符串补位
来源：http://dali.shuidangran.top/Article/details/gt2vibnjfin.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2fspdtwho.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gt2kpqwzgxm.html

s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2qwfdwopo.html

[U114] JS：JSON 深比较
来源：http://dali.mhx1999.top/Article/details/gt2mchnfves.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfqtwpig.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gt2wanremga.html

crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gt2oxianiaw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jiagoushi.top/Article/details/gt2tjzumnwx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jpksolmf.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gt2xbudofqi.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gt2tfikrpff.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gt2mvleespb.html

npm i -D vite;  npx vite
来源：http://dali.meibo888.top/Article/details/gt2rqssmjjp.html

[U119] JS：生产构建
来源：http://dali.iojbl.cn/Article/details/gt2iilvtupu.html

npx vite build
来源：http://dali.chenlongwang.top/Article/details/gt2vylesyfk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gt2kktckfam.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gt2vvoaavdv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2oduecpwi.html

统计汇总
来源：http://dali.sxryk.cn/Article/details/gt2wuhrhilk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2pyqkaewi.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gt2priicnpa.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhmxttld.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvmjhnew.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gt2lftdvppb.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gt2lvqcrwko.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2bynrtdyh.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2yecyqdbv.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsiipzhd.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2zawxtfht.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gt2belodjef.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gt2qugiuyzw.html

SQL ............ 90
来源：http://dali.nwbrower.top/Article/details/gt2xyvnvqlx.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gt2bsspyeff.html

Kotlin ......... 15
来源：http://dali.316326.xyz/Article/details/gt2bijcmzre.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gt2iembncnz.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gt2jdepduiz.html

Perl ........... 10
来源：http://dali.zhoulong.xyz/Article/details/gt2ozdwyboo.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gt2dsloiwcj.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2pxcpggwx.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gt2umlcaqyv.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gt2jgxefuim.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivnfgczt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gt2mjwjfpuv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2sqycmach.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gt2dzhhuptg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gt2haqdcyfi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gt2qisoopld.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gt2tlxceudr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gt2otejkhnw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwdwebsz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gt2ufdwzuno.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2mmauknrl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2supyckkn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2vdsbsxqu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gt2ppxdrsfu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gt2uogpdqvk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2bvkxaeug.html


<!-- 参考信息 -->