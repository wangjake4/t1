代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gtvhuefkay.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtwatdwlpz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gthkbfrzgl.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gtdrnbapyu.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtujngszdc.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtlejxystf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtxezmpjpd.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gtxpxutsfl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtnatafegm.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtmxeujooa.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtwkagvrkb.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gttldkkmqu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtdbeopjat.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbyvjbrwv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtyyqglyeq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnycfzpyd.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtpxbldruu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtjuzpggka.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtkyujswum.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtzqwffnmy.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtrywjbwnr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtytqneptq.html

[U04] Py：变量调试打印
来源：http://dali.guowangkeji.top/Article/details/gtvfmyeksd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtfgtxkuim.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gtbxnhybgx.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtecpqhame.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtusczhwoi.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtzhoqhcnh.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtssiabzji.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gtxnrvxvku.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gtidclfkvz.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtipvuzlzj.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gtriscqlmb.html

max(d, key=d.get)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosjidhuc.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtntcovltp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gtxiyljabp.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtuxnwbvpr.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtgjbaayeo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtudaqllvy.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gtuwwgunrp.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gtbwmrnxog.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtrlltuoij.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gtrvezogsx.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtxtidoucy.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtejlthxzq.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gtoyqevevx.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsueqxmj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gtpxjdzqwh.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gtaukqpauj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gtmepctvms.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtvwvflyua.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gtsjqewhcv.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtwnvzrkcs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnqzz.top/Article/details/gtrejveljl.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gtahrksvnc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gtfrapxxlg.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtajzbuovn.html

@contextlib.contextmanager
来源：http://dali.aibaodan.cn/Article/details/gtmhwxyaqq.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gtmxrlforu.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtqzihxugu.html

[U23] Py：分块读取大文件
来源：http://dali.chenlongwang.top/Article/details/gtefnozdir.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cucudq.cn/Article/details/gtuncwrinx.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gtbkbckeep.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvfrfqhh.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gtkoqpgdvv.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gtxnzenhgr.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gtkhfkunfk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gtduvvkwqw.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtuuebbjhn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gtbhtfnvsf.html

[U28] Py：类型别名
来源：http://dali.aibaodan.cn/Article/details/gthmbgzuse.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gthlivrywy.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gtedoocygk.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtowxbvdka.html

[U30] Py：数据类
来源：http://dali.cucudq.cn/Article/details/gtlrqnhrub.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztllwuix.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gthvxhdedy.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gtmweoyfrw.html

[U32] Py：代码格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtstrcijqx.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gtvqchpgxo.html

[U33] Py：打包发布
来源：http://dali.aibaodan.cn/Article/details/gtqmnrbjoa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gthmwsphvd.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gtxvuggfco.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gtudjfpgni.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gtuihgnrdp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tian-w.cn/Article/details/gtsdenmcuj.html

[U36] Py：定时任务
来源：http://dali.hammf.cn/Article/details/gtqsjqdtdf.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gtmtelonjy.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gtfstjydnd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gthlkqdyhi.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gtwxfgtwab.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtngnovaxy.html

[U39] Py：判断是否在交互环境
来源：http://dali.jiagoushi.top/Article/details/gtwxtkllxe.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gtxhrtlahk.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtgwezaoxb.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtudfrjriv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrbwmok.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhiwuduotai.top/Article/details/gtwtscjdzj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangdashe.top/Article/details/gtwbhepsun.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtauiywgtj.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gtthscxtrb.html

namespace App\Http;
来源：http://dali.xuetiantiany.cn/Article/details/gtfzqerlky.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gtxvsdamjm.html

declare(strict_types=1);
来源：http://dali.hfpthk.cn/Article/details/gtrnntwcep.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gtgwtlykpj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmadeagsf.html

[U46] PHP：可空类型
来源：http://dali.sweek.top/Article/details/gtybnxskaj.html

?string $name = null
来源：http://dali.andypj.xyz/Article/details/gtjgyhsfir.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gtfgerypky.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtkssvfivg.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtxamrvrwg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gtodjnnbxy.html

[U49] PHP：只读属性
来源：http://dali.bjfxy.top/Article/details/gthjaogssk.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gtlxvgtcrn.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtufeilygd.html

public function __construct(private int $id) {}
来源：http://dali.bjfxy.top/Article/details/gtwjyacgnr.html

[U51] PHP：数组解构
来源：http://dali.jianghu66.top/Article/details/gtvsedulaj.html

[$a, $b] = $arr;
来源：http://dali.zhiwuduotai.top/Article/details/gtnmieyqki.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtzlwzvkvz.html

$double = fn($x) => $x * 2;
来源：http://dali.pycfn.com/Article/details/gtymoatcnv.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gtfelknwbf.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyeqrxqy.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gtltmcbrta.html

$obj?->method()
来源：http://dali.meibo888.top/Article/details/gtcewprejf.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gtbxgbqjvh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtchvgnizm.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gtfksqksbo.html

f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtiseedtvt.html

[U57] PHP：字符串插值
来源：http://dali.ivvv.top/Article/details/gtjbzdgvql.html

"值: {$a}"
来源：http://dali.nanxinkj.top/Article/details/gtvpknqcih.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gtkwzskmmf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gtyffbbgho.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gtfoogbcoa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtnuxcpwmd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gtvhbfryiy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhgmbjpa.html

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gthyaabzqb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtrspnhils.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gttejednrw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gtkhoihbfw.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gtlcwgxpsn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gtdkzujcbi.html

[U64] PHP：目录遍历
来源：http://dali.nanxuanxn.top/Article/details/gtblmjmedf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtbwpmipei.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtosedmlgg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtjvntjedl.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gtifgidnlr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zycfv.cn/Article/details/gtdpywuuno.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikowkcnl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gtwimkaztr.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gtsaovpkiy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtaxfoaurj.html

[U69] PHP：PDO 预处理
来源：http://dali.yj202588.top/Article/details/gtnvsnqgvt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtsvioyite.html

[U70] PHP：PDO 事务
来源：http://dali.aizwys.cn/Article/details/gtvxksgquu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.9152youxi.cn/Article/details/gtuzztxkhl.html

[U71] PHP：抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtkwodsmqy.html

throw new RuntimeException("失败", 500);
来源：http://dali.xylfe.cn/Article/details/gtbxpwghjk.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gtrxrlnngh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shangyingyoupin.top/Article/details/gtmzfmayit.html

[U73] PHP：读取 ini 配置
来源：http://dali.birdmap.top/Article/details/gtitzbzdzx.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtmcssoaak.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtdtzudjzh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xylfe.cn/Article/details/gtaijmfjpp.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gtxkredolj.html

composer require psr/container
来源：http://dali.bjfxy.top/Article/details/gtuogxtbnt.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gtyitthtmi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gtjtjbnqnp.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gtpbibwazn.html

composer require twig/twig
来源：http://dali.wangshuangyany.cn/Article/details/gtnqbopsqv.html

[U78] PHP：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtbpyyjhll.html

composer require --dev phpunit/phpunit
来源：http://dali.chenjidiqi.icu/Article/details/gthlsxhear.html

[U79] PHP：静态分析
来源：http://dali.gaohongyu789.top/Article/details/gtazorqwij.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gtycgzvlex.html

[U80] PHP：代码规范修复
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgmuxiek.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gtbwiuihmz.html

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gtgomrfyha.html

npm init -y;  npm i express
来源：http://dali.daria6918.cn/Article/details/gtfsurdipq.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gtvrlkueue.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtvhlyndvv.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gtyybjwuzq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtmymshkud.html

[U84] JS：CommonJS 写法
来源：http://dali.aibaodan.cn/Article/details/gtibwixehl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yonumen.top/Article/details/gtxxpjusqo.html

[U85] JS：可选链
来源：http://dali.ybcxt.top/Article/details/gteupoxjgx.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtbmzzvrbq.html

[U86] JS：空值合并
来源：http://dali.yj202588.top/Article/details/gtusdsncfy.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtzfytaepn.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gtghgaxnqe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhongyouzk.top/Article/details/gtkakybxzo.html

[U88] JS：对象展开合并
来源：http://dali.xuetiantiany.cn/Article/details/gtcbhfqesw.html

{ ...a, ...b }
来源：http://dali.kuanghao11.cn/Article/details/gtyggnaqym.html

[U89] JS：数组去重
来源：http://dali.redwolf501.top/Article/details/gtgatquxwl.html

[...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtchipzirv.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gtfdzwmvnz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtstjqvnqr.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtyivdttol.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.redwolf501.top/Article/details/gtiydzcisd.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gtymcgsxmd.html

structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtqanwrrfy.html

[U93] JS：模板字符串
来源：http://dali.pycfn.com/Article/details/gteyesbqch.html

`共 ${n} 条`
来源：http://dali.yj20258.top/Article/details/gtpuzcbqvd.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtacvetcgf.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gtzyesaeiw.html

[U95] JS：Promise 包装
来源：http://dali.mhx1999.top/Article/details/gtzwhtdcyj.html

new Promise((resolve, reject) => {})
来源：http://dali.yuxming.cn/Article/details/gtucwvbrsk.html

[U96] JS：async/await 与异常
来源：http://dali.pycfn.com/Article/details/gtfbbwoctd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtcnmnqdpp.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuiuosmo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtcxwomfgv.html

[U98] JS：fetch 带 JSON
来源：http://dali.tanke756.top/Article/details/gtzxxkxhmi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gtzdrlcqqj.html

[U99] JS：事件监听
来源：http://dali.chenlongwang.top/Article/details/gtfrxnovmp.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gtpeksvgyw.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtebchfwfv.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtulmluvbz.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gtojdmzkyz.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gtzkbdherq.html

[U102] JS：本地存储
来源：http://dali.jiagoushi.top/Article/details/gtgmnhjmmj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gtjjexwqaw.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gtzyaiowvw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jianghu66.top/Article/details/gtflacjryk.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gttrkoknvv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtnmrijhkv.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gtujhrfacd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gtknbshgho.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtljbuwdxe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gtuxlgukyp.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtiqtjqsmm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhrsklpp.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gttxppzyfo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gzhubu.top/Article/details/gtsvrgofcz.html

[U109] JS：数组分组
来源：http://dali.yueranfly.top/Article/details/gtbcnfwskq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiupvsais.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtjgnqlixz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gtkwgonrjx.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gtrkryvuec.html

new Map(Object.entries(obj))
来源：http://dali.shuidangran.top/Article/details/gtjsvjavbo.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gtpvadxibc.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gthalrdanu.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gttjykxymz.html

s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtghxjnqed.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gtdjcomoox.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtrnqewsow.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtqnmtnsdw.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtxmoguirf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gtxwllcbdn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gtllxcnvph.html

[U117] JS：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtwpducqms.html

npm i -D vitest;  npx vitest
来源：http://dali.xinyue.icu/Article/details/gtegikxxwe.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtcwmynwas.html

npm i -D vite;  npx vite
来源：http://dali.havefunace.top/Article/details/gtztkhattz.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazvjtfjc.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gthuwhayne.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gtrazdmgdn.html

import.meta.env.VITE_API_URL
来源：http://dali.ybcxt.top/Article/details/gtvnryydac.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzyeuhove.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gtyqoqzhwl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcghpuwfa.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgppkbbv.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gtnndmnnrk.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gtjswiyhmd.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gtdriuqiov.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gtueapseys.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoyawoar.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtcpmiacvq.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gtmzvfixcg.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtauivkqtc.html

C .............. 30
来源：http://dali.cdnleiting.top/Article/details/gtevpcjzil.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gttmomcneu.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gtpdokdish.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gtlhkqwikq.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gtosylytoo.html

Swift .......... 15
来源：http://dali.ppjwa.cn/Article/details/gtajewuzfn.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpqeykck.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtcfwbuafr.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gtcrrehqff.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtwcjoqs.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtvjakxnkh.html

按章节统计：
来源：http://dali.ehwqpu.com/Article/details/gtstjphevu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtafefkdoo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtyfacelvb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtxsjehoty.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtszxrfsgd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuxming.cn/Article/details/gtsvyvizeh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtpatdcbdq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gthmmsweau.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtovnyoywd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtuuhezykw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gttzcspfdb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtjnjkkoup.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszhwnssy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtapyrllpi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtdtumtbfy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gtnwlqffgp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtvrsopeiz.html

Q SQL 专题                              90
来源：http://dali.redwolf501.top/Article/details/gtdxgosajh.html

R Bash 专题                             80
来源：http://dali.dianchejie.cn/Article/details/gthmerereq.html

S C / C++ 专题                          60
来源：http://dali.feifeiyinyue.top/Article/details/gtibfokeey.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gthhqhyylt.html


<!-- 参考信息 -->