代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gtggahbqxh.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtjradzybw.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtfzxnhmvh.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gtomxznnth.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtbmggssxb.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtclfxjjoy.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtecfdealx.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtxojkawkm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnxiuktvv.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtecuhzkuz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtpiykkzbd.html

[T56] Scala：样例类
来源：http://dali.hywenlv.cn/Article/details/gtljozptuu.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gttsyawarx.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtywqspjlt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtthddxxbw.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjbjwneb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtlgybmcui.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtrltbguft.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtdffchldh.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtmuhtcqkq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtrjflowzd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbvgvjyul.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gttqulqrmy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtztydbbtn.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258888.top/Article/details/gteobnzspv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtfuiwmlov.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtsizmxglh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtkjqvnpok.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtvbzwidpc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gtujddbskd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gtgidnlktk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gtqbxydwwo.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gthohshylq.html

list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtwhdashpu.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gtklsxivgn.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gtjvrdvbjf.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxxriuge.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtejaphoms.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtcchwcztt.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gtwnqqjwdh.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gttiaklbng.html

max(d, key=d.get)
来源：http://dali.quarkkingdee.top/Article/details/gtzmvgnbjx.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtevddhvci.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtdlpjhqlt.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gtpiylxciu.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gtgjfspfdy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gtnqvhtxky.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtgaydotsh.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtaduvfjlu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gtmgmitnnp.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gtozhtwkbu.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtkzefrmpt.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtukazqucd.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gtindghcul.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gtsfbijnty.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gtqnzaupht.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gthsmxahct.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gtgxqivuwu.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gtmjdqzrsi.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gtjdoetguw.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtmelzeitd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtpceuloyd.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gtnjnruuba.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtosbsndbt.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhxplmvw.html

@contextlib.contextmanager
来源：http://dali.aibaodan.cn/Article/details/gtprtxrczy.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gtatqrpxsu.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gtqbsizpfl.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexhaummx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gtknepdeks.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gtndodyeim.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtvwrdigsp.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtvkpruneg.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gtranexzce.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtqaghxeos.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtmgumbdpy.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gthqbxauwb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gteqxxrpbj.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gtdawchwzm.html

UserId = int
来源：http://dali.zdqjudy.top/Article/details/gtarvervrw.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gtovxwrwzz.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpqtphsg.html

[U30] Py：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqbkygjr.html

@dataclass(slots=True)
来源：http://dali.nanxuanxn.top/Article/details/gtgihlxjlx.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gtrhybabuw.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gtsfdasvlt.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gtnamobzlc.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtcjpjalgr.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gtvsudscce.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.c1oappe.top/Article/details/gtbicvcnhi.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gteafacufp.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gtapqqtptj.html

[U35] Py：发送邮件
来源：http://dali.sufxvd.cn/Article/details/gtqfyzxojq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gttljroqyl.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtbtnkixoi.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gteiltvrov.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gtdbnrsqjq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gtutxjtkqw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gtlvklmrts.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtwcnqgazu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhongyouzk.top/Article/details/gtqhrrnuwm.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gtknlvxcut.html

[U40] Py：打印到标准错误
来源：http://dali.jlsjyb.cn/Article/details/gtvqaiiwrj.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqmkhcvg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shzxlz.cn/Article/details/gtwqivthzu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtxhuwluke.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtquokxmnm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcxynkom.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gtdeavaghm.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gtxdsbdaef.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gttqfmaxdy.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gtympdadbe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gtjiahjcra.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtqgyvhuhf.html

[U46] PHP：可空类型
来源：http://dali.sweek.top/Article/details/gtbsadjcrm.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gtqaayhdag.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gtvmujsefs.html

int|string $id
来源：http://dali.havefunace.top/Article/details/gtzvutkpwn.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtdxonvdbq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqztkhddw.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gtuemmswya.html

public readonly string $name
来源：http://dali.pycfn.com/Article/details/gtxbdkdhje.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtsvtabtgk.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gtsxiafbby.html

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gtgwzwnjqx.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gtrzpueyxs.html

[U52] PHP：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtgjtjfati.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258888.top/Article/details/gtdgynwwpe.html

[U53] PHP：空合并运算符
来源：http://dali.kuanghao11.cn/Article/details/gtgosfvynt.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigufen.top/Article/details/gtwrkqwhlp.html

[U54] PHP：空安全调用
来源：http://dali.guannengcc.top/Article/details/gtikisjtko.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gtmxbpgksh.html

[U55] PHP：match 表达式
来源：http://dali.xinyue.icu/Article/details/gtzghaebmp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gtxjjmomcq.html

[U56] PHP：命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtekajvifn.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtcwmqfgxx.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtpsiqryrm.html

"值: {$a}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrxgsmdt.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gtegiflnve.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtjnfxctyu.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtuagvrdtw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtgidyahwt.html

[U60] PHP：JSON 编解码
来源：http://dali.redwolf501.top/Article/details/gtoqjsylew.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gtorfpjrlo.html

[U61] PHP：正则
来源：http://dali.andypj.xyz/Article/details/gtdrztjswg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtbmchdbjr.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gtlsgqmpco.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gtsdvzjdly.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gtittulfpy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gtajfyhmop.html

[U64] PHP：目录遍历
来源：http://dali.hnqzz.top/Article/details/gtoicyphgz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhengqikj.top/Article/details/gtcwdsjlrk.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gtjqndkisp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtrkkqrrlr.html

[U66] PHP：设置 Cookie
来源：http://dali.gzhubu.top/Article/details/gttydanaof.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gtelpauszm.html

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtzejhdf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gtanraontq.html

[U68] PHP：PDO 连接
来源：http://dali.yangfankeji.com/Article/details/gtmgdyrobp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gtkmrgmmqn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtiqlgderp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gtaqbenxfo.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gtqbfwmphh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ppjwa.cn/Article/details/gtndolyzob.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtufgdfxnu.html

throw new RuntimeException("失败", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiajempx.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gtlavjtxnm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jyoumei.cn/Article/details/gtpaehyxja.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gtgqyqexfu.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gtweuuhgab.html

[U74] PHP：读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtiuwxqnsp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gtxitzhwnb.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtsipfugfr.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gttewbyhpp.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gtkogbaayf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258.top/Article/details/gtkqnaflbm.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtthglfddw.html

composer require twig/twig
来源：http://dali.ydzc1.top/Article/details/gtilbwmpkx.html

[U78] PHP：单元测试
来源：http://dali.ehwqpu.com/Article/details/gthjknocwd.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgccbbyx.html

[U79] PHP：静态分析
来源：http://dali.hywenlv.cn/Article/details/gtobldhypr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gtmqdukjlt.html

[U80] PHP：代码规范修复
来源：http://dali.xuanzx.com/Article/details/gtwbyudtik.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gttelwilcn.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gtgdsqjmta.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxwmkqgk.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtwfozcwfj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cheryme.top/Article/details/gtnuwxzflu.html

[U83] JS：ES Module 导入导出
来源：http://dali.yonumen.top/Article/details/gtorhxntda.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gtdevrrdew.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxuanxn.top/Article/details/gtwtqfjbgg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gthoobbmhr.html

[U85] JS：可选链
来源：http://dali.yueranfly.top/Article/details/gtmnqaevbr.html

a?.b?.c
来源：http://dali.aizwys.cn/Article/details/gtyuujgmfw.html

[U86] JS：空值合并
来源：http://dali.c1oappe.top/Article/details/gtjxlqmgyr.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtzkgwmsgc.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtwfioruzb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gtqyaidjol.html

[U88] JS：对象展开合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbobtajzb.html

{ ...a, ...b }
来源：http://dali.gotoacloud.top/Article/details/gtqtcmnfah.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gtpawpmdnq.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtyxthhvpf.html

[U90] JS：数字数组排序
来源：http://dali.zhiwuduotai.top/Article/details/gtgttzhkid.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtdmencsrc.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtdipzkyxz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gtxsprgemh.html

[U92] JS：深拷贝
来源：http://dali.quarkkingdee.top/Article/details/gthneyzard.html

structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtiewofleb.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtcjymgttk.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtshqnqmep.html

[U94] JS：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtkmtbzkza.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gtprqwrpqc.html

[U95] JS：Promise 包装
来源：http://dali.cheryme.top/Article/details/gtzfturvqj.html

new Promise((resolve, reject) => {})
来源：http://dali.gogol.net.cn/Article/details/gtgyehbzpj.html

[U96] JS：async/await 与异常
来源：http://dali.jinghuilouyu.cn/Article/details/gttgsivenu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspyiozfs.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gtcpsjeros.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gttswtutjj.html

[U98] JS：fetch 带 JSON
来源：http://dali.guannengcc.top/Article/details/gtyvkatlhl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gtcvxdfqbn.html

[U99] JS：事件监听
来源：http://dali.cucudq.cn/Article/details/gtmtlsgtvu.html

el.addEventListener("click", e => {})
来源：http://dali.cheryme.top/Article/details/gtmyowwkub.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gtzuoftjky.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgizqytla.html

[U101] JS：classList 操作
来源：http://dali.gaohongyu789.top/Article/details/gtikwspwhe.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gtinwkjkdo.html

[U102] JS：本地存储
来源：http://dali.nanxinkj.top/Article/details/gtppewhxey.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gteibncrzf.html

[U103] JS：定时器
来源：http://dali.hongshengwenyu.top/Article/details/gtnwzrbppg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gtqgfgsrdw.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtbgbztxst.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzspewltt.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gtlitmcdom.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yonumen.top/Article/details/gteqscyzlk.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtufugmsjp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gtiojuetap.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtyhfggjki.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtiyzyxdbs.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gtkkezczin.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtvdigwuuv.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtpxskquts.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtkbprjvoh.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gtsvogehmn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gtiglcbuyh.html

[U111] JS：对象转 Map
来源：http://dali.hammf.cn/Article/details/gtlkvwvavu.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gthgevbhfm.html

[U112] JS：字符串补位
来源：http://dali.fzhhl.top/Article/details/gtidupuzvl.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtdprievxs.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gtxanjhjdq.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtqyswnahq.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gtaewrgjma.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtkvxzlnan.html

[U115] JS：生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtpehfkmjt.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsqzuwct.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuanzhike.top/Article/details/gttfympsez.html

/** @param {string} name */ function f(name) {}
来源：http://dali.birdmap.top/Article/details/gtqzwdwkao.html

[U117] JS：单元测试
来源：http://dali.fzhhl.top/Article/details/gtxwyxvzgv.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtlauefmbn.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtmpdycyln.html

npm i -D vite;  npx vite
来源：http://dali.guannengcc.top/Article/details/gtpmznftpp.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtqqdjmsuf.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtlbfgtizt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gtikrmtstp.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtdysnfhur.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwyhnkvkh.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtkbblyjql.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtehxzyfkt.html

按语言统计（条）：
来源：http://dali.kuanghao11.cn/Article/details/gtsaylccex.html

Python ......... 252
来源：http://dali.jiagoushi.top/Article/details/gtgxithvou.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtelabfyan.html

JavaScript ..... 252
来源：http://dali.hysaishi.cn/Article/details/gtlfumenuu.html

TypeScript ..... 212
来源：http://dali.andypj.xyz/Article/details/gtmabgpedh.html

Java ........... 212
来源：http://dali.havefunace.top/Article/details/gtfmyvynsj.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtelyhvplv.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtzjcssdyl.html

C# ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtshpikuln.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gtrhnuhpbh.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtexriaibz.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gtgyiszjpy.html

Bash ........... 80
来源：http://dali.zdqjudy.top/Article/details/gtpcxevqof.html

Kotlin ......... 15
来源：http://dali.jlsjyb.cn/Article/details/gteqrlryhc.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtkewdiutp.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gtbcfrzxlv.html

Perl ........... 10
来源：http://dali.sweek.top/Article/details/gtwdgugpyl.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gtgsfxnlrv.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtrejbrnnh.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gtkurvoumq.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gtjteizigq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtdeficvzm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtsubdaaqg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtwqllerfh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gtzfmdxjga.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.9152youxi.cn/Article/details/gtdfrhmpnu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtymcyjupk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gtuwrjcjxx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtuidzuizk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtagfxxkio.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gtrvbnnhji.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtiqgqrkrn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtbljbdzko.html


<!-- 参考信息 -->