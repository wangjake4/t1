代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtgiklylbv.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtrqevssru.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtzfrzymxe.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtrzenkbok.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtnbrwlsku.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrsvezkrw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtxfrlhwon.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgsmjelce.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtidgthxkw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gtwggyipcv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtgmbylzrg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtibujvegj.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtsggspmkw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtodowfqjt.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtqqmffeun.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtzhlmrgvz.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtdqawqosx.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gturmorpcb.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtyovdmttp.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gthmwnfryd.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtjwuniwfo.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gtgmzrgzvf.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtocfhfgbx.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtoohzzxeb.html

[U09] Py：字典取最大值的键
来源：http://dali.smart0.xyz/Article/details/gtkzowgdgj.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gttxsajefk.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtpmknsckv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtgzjhujaq.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gtebvnjsyr.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gtykdqmjue.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gthvpdhwqh.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtmuejfsgv.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtpedrejax.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gtbbqfuoyv.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtybezqvll.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gtoqnybkbs.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gtggyqytjt.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtkedzzpbo.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gtzzjavjtq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gtphltqlzs.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtsgyubnjh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtkgdnzdjw.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtochlnbrz.html

pat = re.compile(r"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtjflqsxvw.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtenlombgd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gtzsdfygmy.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrxkoycm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gtgevqqjns.html

[U21] Py：自定义上下文管理器
来源：http://dali.cucudq.cn/Article/details/gtlngnqipb.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gtifpxsjal.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gtycimfgcn.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtwttxbfve.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gtkvudpumy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sysykeji.top/Article/details/gtmgxmsbyx.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gtodybfjxt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtlaetjqwr.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gtynnxzhms.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gtmytpfmfj.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gtiggssahi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gtgohuqegt.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtzcolzcrh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gtcbrkysxw.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gtmwxmgque.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gtosbmfrzq.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gtxqvpdkwx.html

@property 与 @x.setter 配合
来源：http://dali.dashuyun.cn/Article/details/gtgouragby.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gtamrkbccz.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gttumqyyji.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gtfoqxtldq.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gtsysywztb.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtnqkozjvl.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtlnxliizv.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gtrseyimjr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gtizlbrtdy.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gtscmjisai.html

chardet.detect(raw)
来源：http://dali.yj20258888.top/Article/details/gtzzbudjti.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gtwzkjprto.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwoscxtt.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gtcsyufcga.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtkmrembjs.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gteqvonvaq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gtxgztpcga.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gtmknuoycv.html

Path(__file__).resolve().parent
来源：http://dali.guowangkeji.top/Article/details/gthosslvle.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtaikiyyfr.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gtgmcjtass.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gtqvgysplr.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtlliwyfir.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gtplxfuxkl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtjinojuow.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hywenlv.cn/Article/details/gtkwqgqmop.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtugvmvaff.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtuqbaswcr.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gtropdlygz.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gtenntiwvh.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gtzfkzpevz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pycfn.com/Article/details/gtblojdfff.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtgzebbftj.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gtltduyqbt.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gtfdlxmbuu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gtzkwcsyeu.html

int|string $id
来源：http://dali.gaohongyu789.top/Article/details/gtmznssuek.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gtmzzhxtfv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gtnzksslxn.html

[U49] PHP：只读属性
来源：http://dali.bjfxy.top/Article/details/gtenffnwta.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtxwoyhdou.html

[U50] PHP：构造器属性提升
来源：http://dali.bjfxy.top/Article/details/gtuvzxcvwd.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gtslbmiscx.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gtlymqjgvo.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxvvewfi.html

[U52] PHP：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtldiusbud.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gtodrannzm.html

[U53] PHP：空合并运算符
来源：http://dali.jqgufenzy.top/Article/details/gtfoynnliq.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtfpevhupq.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtmlfzsdsf.html

$obj?->method()
来源：http://dali.xylfe.cn/Article/details/gtepcmzgam.html

[U55] PHP：match 表达式
来源：http://dali.meibo888.top/Article/details/gtvyrzdubv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dashuyun.cn/Article/details/gtiyyqgkzt.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfokugbcg.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtvtumtgmh.html

[U57] PHP：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtprrczyug.html

"值: {$a}"
来源：http://dali.vqdsnc.cn/Article/details/gtutsdyhxq.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gtvqdppawt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gtkdtukwjk.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gtsovozsoh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtgmthemkb.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gtviqokipl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gtzpjdvlvq.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gtxyicsmjc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtsrmjdvzs.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gtkuqqkxuz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gtflxbmvrg.html

[U63] PHP：文件读写
来源：http://dali.kuanghao11.cn/Article/details/gtwflisyqa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gtffpgzvop.html

[U64] PHP：目录遍历
来源：http://dali.xuetiantiany.cn/Article/details/gthhicrfsf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gtagobxafp.html

[U65] PHP：会话
来源：http://dali.vqdsnc.cn/Article/details/gtvozlabqx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtjoumfryh.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gtwzczdzby.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjcwipsj.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtbjflrdbn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgufenzy.top/Article/details/gtcekonqnu.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenimuiwp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gtfkzgkdiy.html

[U69] PHP：PDO 预处理
来源：http://dali.yj202588.top/Article/details/gtciaanahx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shangyingyoupin.top/Article/details/gtawqlmpqn.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258888.top/Article/details/gtpuovfeou.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gthhuesmrw.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtbsssdljm.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtvenakvdo.html

[U72] PHP：写错误日志
来源：http://dali.shzxlz.cn/Article/details/gtmhtpntbf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gtjrtzpilt.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gtxgswvdbi.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgufenzy.top/Article/details/gtfqxnbymo.html

[U74] PHP：读取环境变量
来源：http://dali.sweek.top/Article/details/gtkqngiclq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtueackhzb.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gtmfwzgfdz.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnpihhjy.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gtyyiviyuy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtulhokvfr.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gtpdjlonpu.html

composer require twig/twig
来源：http://dali.jianghu66.top/Article/details/gtrquceinm.html

[U78] PHP：单元测试
来源：http://dali.cucudq.cn/Article/details/gtkfrafhmv.html

composer require --dev phpunit/phpunit
来源：http://dali.ybcxt.top/Article/details/gtaigqxjbq.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gtakycstkn.html

composer require --dev phpstan/phpstan
来源：http://dali.snrcjt.cn/Article/details/gtcsltnxnx.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gtrooitidx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtthckxwvr.html

[U81] JS：初始化项目
来源：http://dali.yueranfly.top/Article/details/gtqglulbfv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gtlvjtdduc.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gtsrlayphg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ehwqpu.com/Article/details/gtgspvmihs.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gtavkroepe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtggpjfmxe.html

[U84] JS：CommonJS 写法
来源：http://dali.sufxvd.cn/Article/details/gtcqvjjrfk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.andypj.xyz/Article/details/gtgznvxysx.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtqevrllek.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gttnychvld.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gtwdinrgxi.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gtiiaxwrmf.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtwixbltup.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gtpxfcakvi.html

[U88] JS：对象展开合并
来源：http://dali.ydzc1.top/Article/details/gtzxeoznhf.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gtywvwompu.html

[U89] JS：数组去重
来源：http://dali.cqqwz.cn/Article/details/gtvorqlkmm.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtzyorwiak.html

[U90] JS：数字数组排序
来源：http://dali.ehwqpu.com/Article/details/gtipwnudra.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtymlxeorr.html

[U91] JS：对象键值遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtiuxqlbrr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gtuieazrwv.html

[U92] JS：深拷贝
来源：http://dali.nwbrower.top/Article/details/gtcgegkmor.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtjcinzzek.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtwqeupils.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtarkgvwrp.html

[U94] JS：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcgkhsqv.html

const double = x => x * 2;
来源：http://dali.cucudq.cn/Article/details/gtwreywolb.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gtlsrpqqpw.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gtdzlxeoiy.html

[U96] JS：async/await 与异常
来源：http://dali.yangfankeji.com/Article/details/gtjytkrytb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtnzyptldr.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gtuvqatmel.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtxuhhigqr.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gtuhijywml.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gtnkxqhaly.html

[U99] JS：事件监听
来源：http://dali.yj202588.top/Article/details/gtyducvznc.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gtwpvodaca.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtawcqszek.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvrhtvhj.html

[U101] JS：classList 操作
来源：http://dali.jlsjyb.cn/Article/details/gtpdbzdtwu.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gtggajecpx.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gtxnuetvlj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtshdfnjrc.html

[U103] JS：定时器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwswyong.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gtxjzonmyc.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gttavjyrat.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtqcfviknt.html

[U105] JS：节流
来源：http://dali.zhengqikj.top/Article/details/gtlakjpvjc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnxiangtu.top/Article/details/gtctmhfrrj.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtlmcfxmid.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gtjtkgmpji.html

[U107] JS：数字千分位
来源：http://dali.cheryme.top/Article/details/gtijaqgpit.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtouikwqpc.html

[U108] JS：随机整数
来源：http://dali.cheryme.top/Article/details/gtdzmvfcpv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtdvezmchg.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gtmlskitsx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtbzmfgfso.html

[U110] JS：数组分块
来源：http://dali.ybcxt.top/Article/details/gtpyjubcqu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gtxyfdelig.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtikfqcwzv.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gtzdcgyayf.html

[U112] JS：字符串补位
来源：http://dali.gaohongyu789.top/Article/details/gtfjvnouwf.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtsevzuuln.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjedspep.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtsvwfobng.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtwxbtegna.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtdymfaxnc.html

[U115] JS：生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtdaofmiwq.html

crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtccuxcvrx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gtbmwjnzzp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gtatnsmorz.html

[U117] JS：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtcrltellb.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gtdxmzherh.html

[U118] JS：开发服务器
来源：http://dali.xziqi.cn/Article/details/gtzuchxbmj.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtfpoyohlf.html

[U119] JS：生产构建
来源：http://dali.shzxlz.cn/Article/details/gtpozalsst.html

npx vite build
来源：http://dali.shzxlz.cn/Article/details/gtobigosyj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtjngfmada.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gtukimgoxv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtlkvwrzap.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtibchctmi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvbdivnnh.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxdlhfwf.html

Python ......... 252
来源：http://dali.zhiwuduotai.top/Article/details/gttvhhtrtt.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gtsucroqzz.html

JavaScript ..... 252
来源：http://dali.tanke756.top/Article/details/gtuwxtmxch.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gtnfeyfcnc.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gtrczhztfv.html

Go ............. 212
来源：http://dali.jianghu66.top/Article/details/gtcbmjtegy.html

Ruby ........... 212
来源：http://dali.fengsongda.top/Article/details/gtpryquynl.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gttyivyeny.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gttktqtmgq.html

C++ ............ 30
来源：http://dali.sufxvd.cn/Article/details/gteoradaaq.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gtpbfqjiby.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gtravyfodq.html

Kotlin ......... 15
来源：http://dali.ppjwa.cn/Article/details/gttutmrjaj.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtumkxcwgh.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtmexgefck.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gtrcfenfxn.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gtchferouh.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtqlvfznqg.html

合计 ........... 2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gtcshhuhyd.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gtufntnggz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtjqiaejop.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtwhumepuu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gttilgrptq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtnbmxavbl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtaiazmjgw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtnbyznxxw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtxemuejdj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gtryhyxucu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtimesqlho.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gthcapyoas.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtuqudajbo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtwtleaiun.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtlqzepddr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtoaqmzkhx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtlafkcyzv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrzvrxht.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtokzzsffo.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gtupuwkweh.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gtcxrhwefu.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtbzdjktux.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlmhljza.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gtuqlputbz.html

合计                                  2106 条
来源：http://dali.wangdashe.top/Article/details/gtywnioxax.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtkmswrpbs.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gthxztfgbu.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxszjwng.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gttyfyckly.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gthicbjgqx.html


<!-- 参考信息 -->