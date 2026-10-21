代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtyjzdqj.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtvcsxzvzu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtnsbpkbso.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gtsanthgad.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtoyaztsra.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtadawkukh.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtsjokbwis.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gtvdzxjuli.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtsfhpwrbt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjrnzasdi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtenolgnux.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtexwypwot.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gtaiixlnmu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtupctkubi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gtsskuhcng.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtplmtqagk.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtdrievvyh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gtlakbrfxz.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gtoxkvwobb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gtkgfawjkk.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gtepjcowkz.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gttzbkdqkc.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gtgjqfxpcp.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtlihbeftd.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gtggeiaoqm.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtkbwejfdl.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gtthoinidx.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gtlcbvkjkr.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtnltgxtap.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gticzaqadb.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gtgfuqzjfg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtszqbjozt.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtbqavhpnf.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gtyfcmrehl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbenolegq.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gteehuzywt.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtjpxdknqb.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gtmcnctbat.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnznsorlx.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhsvolmn.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gtliewvwbv.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtzkfaaded.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtifgodfen.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtizepfhsv.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gtcuqsefro.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gtsdrbdcvx.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gtlrsdaxmf.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtgrhqbwrq.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gtuyugiarj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cdnleiting.top/Article/details/gtgnfqkrbp.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gthjrflipo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258.top/Article/details/gtfmwrugmi.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtiqatzqmr.html

@contextlib.contextmanager
来源：http://dali.9152youxi.cn/Article/details/gtbfkbyuyb.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gtvtmnyezc.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtbnausesx.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gtpowjxltu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtyhmwrycp.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtlcnyfged.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtgcfgfbfj.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gtbbsoarae.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtpqerkvur.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gtxqbfcsjq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtzewcrokn.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gtqrxnaaod.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gtkoeitugc.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaowcujaq.html

UserId = int
来源：http://dali.zycfv.cn/Article/details/gtmnysocdb.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtnnogdkly.html

@property 与 @x.setter 配合
来源：http://dali.zycfv.cn/Article/details/gthzwkmqys.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtksftsxwm.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtffpbwuzo.html

[U31] Py：单测
来源：http://dali.fengsongda.top/Article/details/gtcguswklh.html

python -m pytest -q
来源：http://dali.tianlin.xyz/Article/details/gtfdjopadq.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gtpxsgsvsp.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gtvyjflqby.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gtnjtlcoya.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtauifixqe.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gteyuhpaog.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgburnqgk.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gthpedqpgz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gtcmwuswpr.html

[U36] Py：定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtrbrvzrkk.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gtesotvaly.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gtkytxqmmn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gtelfcktsa.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsapgasnh.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gtmkntmmsh.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtkxbysyyc.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gtsbljuvxl.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gtdmiceonq.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtsdcdiuwz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xziqi.cn/Article/details/gtkkyyhxqh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigfzy.top/Article/details/gtlcmaujbi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgfzy.top/Article/details/gtbkipaped.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gzhubu.top/Article/details/gtmtpjwikk.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gtixicpjhg.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtxfwkxzow.html

[U44] PHP：开启严格类型
来源：http://dali.tianlin.xyz/Article/details/gteeuugegf.html

declare(strict_types=1);
来源：http://dali.gzhubu.top/Article/details/gtqxmzkfix.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtnzzrpaqn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gttdllpsqo.html

[U46] PHP：可空类型
来源：http://dali.0kj1m.cn/Article/details/gtknhyqybp.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gtamxonosw.html

[U47] PHP：联合类型
来源：http://dali.jinqigfzy.top/Article/details/gthoteeyea.html

int|string $id
来源：http://dali.ehwqpu.com/Article/details/gtjopcutco.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gtexbawmgp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gteiskxywr.html

[U49] PHP：只读属性
来源：http://dali.sweek.top/Article/details/gtnlwmqeve.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gtfoszrcjx.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gtorpybeyb.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gtrtoiugjv.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gttcmkxdxy.html

[$a, $b] = $arr;
来源：http://dali.fzhhl.top/Article/details/gtrswrhvzn.html

[U52] PHP：箭头函数
来源：http://dali.tanke756.top/Article/details/gtokrdjzwb.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gtojjldddg.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gtnuyguwgw.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gtzcljuwhr.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gtcndsacss.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtvyhseyuy.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gtagmjeldl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtnhyliwag.html

[U56] PHP：命名参数
来源：http://dali.havefunace.top/Article/details/gtlgyudpqg.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtneqgnekm.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtuquxozzm.html

"值: {$a}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdgsoqmt.html

[U58] PHP：数组三件套
来源：http://dali.sxryk.cn/Article/details/gtnsuajkrc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtyjgccdku.html

[U59] PHP：自定义排序
来源：http://dali.shuidangran.top/Article/details/gtrytaqlqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtqgbwkpmx.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gtzkxapsbl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gtvinhxkxd.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhfklykf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtouldapji.html

[U62] PHP：日期对象
来源：http://dali.yj202588.top/Article/details/gtlwxszhxm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnqzz.top/Article/details/gtyprayifd.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtsycuygdh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.mhx1999.top/Article/details/gtvxlbtfgb.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gtyzidkizm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigufen.top/Article/details/gtwqezreme.html

[U65] PHP：会话
来源：http://dali.tian-w.cn/Article/details/gtujeognwm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtesafylrg.html

[U66] PHP：设置 Cookie
来源：http://dali.c1oappe.top/Article/details/gtmluxzxgv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ydzc1.top/Article/details/gtwzeectef.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqvfvyhu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gtvaflocqr.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtnttqbrac.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.svipenyu.cn/Article/details/gtqucpykhq.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtxytrptud.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gtpfwaiwlm.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gtngwpsuxz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gtfgfospke.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gtmzeprwpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtgbozjpyg.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gtzftilnxl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daxiang520.top/Article/details/gtrefvnewx.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtpzeprsri.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtylwixweq.html

[U74] PHP：读取环境变量
来源：http://dali.sweek.top/Article/details/gtqxvifwyg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhiwuduotai.top/Article/details/gtyfbhtbfz.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gtsbsxjwug.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gtxjzvjsmt.html

[U76] PHP：简单路由
来源：http://dali.yongpay.top/Article/details/gtoohacfbl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtmstcmyon.html

[U77] PHP：模板渲染
来源：http://dali.jiagoushi.top/Article/details/gtjgdfpkiz.html

composer require twig/twig
来源：http://dali.jianghu66.top/Article/details/gtdamfgihx.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtevegnyax.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtdshkloto.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gtrbncifst.html

composer require --dev phpstan/phpstan
来源：http://dali.gogol.net.cn/Article/details/gtholiltky.html

[U80] PHP：代码规范修复
来源：http://dali.snrcjt.cn/Article/details/gtdjnkyctu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ybcxt.top/Article/details/gtkcowcoky.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gtdlzrhzon.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gtqalpwgxu.html

[U82] JS：package.json 脚本
来源：http://dali.cdnleiting.top/Article/details/gtxdkeebeq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ivvv.top/Article/details/gtefatizrx.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtmqkmnawy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtptpnstvq.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtbswntsbq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.0kj1m.cn/Article/details/gtvxwdsrrc.html

[U85] JS：可选链
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwyzkjsz.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpwwvibr.html

[U86] JS：空值合并
来源：http://dali.cucudq.cn/Article/details/gtoreztotq.html

a ?? b
来源：http://dali.andypj.xyz/Article/details/gtmqsxkcrp.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gttelsvydg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yonumen.top/Article/details/gtmlmqyufr.html

[U88] JS：对象展开合并
来源：http://dali.yangfankeji.com/Article/details/gtarorjgmo.html

{ ...a, ...b }
来源：http://dali.cheryme.top/Article/details/gtrkdruzra.html

[U89] JS：数组去重
来源：http://dali.vqdsnc.cn/Article/details/gtxsntaewa.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtnuqjtnie.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gtenkcovua.html

[...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtqxdygwai.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtqofuazze.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtoxwqgctv.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtniarnmgh.html

structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtkhhlhdrn.html

[U93] JS：模板字符串
来源：http://dali.cheryme.top/Article/details/gtzvdhkhxo.html

`共 ${n} 条`
来源：http://dali.feifeiyinyue.top/Article/details/gtiovpodpl.html

[U94] JS：箭头函数
来源：http://dali.redwolf501.top/Article/details/gtmpqiltqb.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtzczbqnbf.html

[U95] JS：Promise 包装
来源：http://dali.gzhubu.top/Article/details/gtfihdwpnd.html

new Promise((resolve, reject) => {})
来源：http://dali.yuxming.cn/Article/details/gtnyipfvkq.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtavddjrgr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtiaermhpe.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtcovevtpz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtomwaefhm.html

[U98] JS：fetch 带 JSON
来源：http://dali.0kj1m.cn/Article/details/gtwvkwzzyt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hysaishi.cn/Article/details/gtlekjkdxi.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gtkgjezibv.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gtdddhzjrw.html

[U100] JS：DOM 查询
来源：http://dali.316326.xyz/Article/details/gtrtyrhdrk.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlyclvdm.html

[U101] JS：classList 操作
来源：http://dali.snrcjt.cn/Article/details/gtnuzqlmdl.html

el.classList.toggle("active")
来源：http://dali.yonumen.top/Article/details/gtsxrooqcz.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtvntebkhc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yanxiufei.cn/Article/details/gtkfbcikhu.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gtvvrsyfsz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gtkxsuxhzd.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gtrkskhiqh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtdisaotlu.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gthluefjsi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gtovybpfsc.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gtujgsunlu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtwnonsjfa.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gturmmbbge.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtofspozab.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gtegwurzxu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtrvamfdrn.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gtozllsynx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtnankzira.html

[U110] JS：数组分块
来源：http://dali.meibo888.top/Article/details/gtqmtgdymc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.smart0.xyz/Article/details/gtgmmrekxa.html

[U111] JS：对象转 Map
来源：http://dali.gogol.net.cn/Article/details/gtzmiivmfr.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtdvfgmmam.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gtebjkgpic.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtvxtmmivx.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtkzipofpe.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqtwvdkti.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gtpuwkrano.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtozgifhdu.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtfwyzgilz.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfqilfip.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pengpengdd.cyou/Article/details/gtpjpyovvj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gttxyiqkxr.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtvdrkhpdh.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gtlfqkcoyc.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gtsholpipy.html

npm i -D vite;  npx vite
来源：http://dali.daxiang520.top/Article/details/gtpskxkjyo.html

[U119] JS：生产构建
来源：http://dali.nwbrower.top/Article/details/gtoncmqbna.html

npx vite build
来源：http://dali.zdqjudy.top/Article/details/gtfeymfblb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ivvv.top/Article/details/gtogodirdk.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gtzazywbmd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtoxprtcsq.html

统计汇总
来源：http://dali.ybcxt.top/Article/details/gtbpfybgep.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtquehqmax.html

按语言统计（条）：
来源：http://dali.iojbl.cn/Article/details/gtirkgmdjw.html

Python ......... 252
来源：http://dali.dashuyun.cn/Article/details/gtbbstdsry.html

PHP ............ 252
来源：http://dali.ehwqpu.com/Article/details/gtlqldnwwz.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gtkwutatlh.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gtwsplqcxg.html

Java ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtljemjksw.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtvcnqvmwp.html

Ruby ........... 212
来源：http://dali.c1oappe.top/Article/details/gtiqtghajt.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtyfmwdybi.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtpouncogs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gtdpgabbnl.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gtwlfhzlbj.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gtrgskustf.html

Kotlin ......... 15
来源：http://dali.kuanghao11.cn/Article/details/gtijbygvhd.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gtsdlopowh.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gtgzoeetpv.html

Perl ........... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovebjoze.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtavvkfzsd.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtgtxvoqqz.html

合计 ........... 2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtruptawjv.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gtyhdnvudg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofpyvpmw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtquprulqu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtweamnbkl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtstrehbex.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gtojbdsshi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtevrqmgan.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtgddkrzey.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtpxadvdgp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtwizrgbmc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gtmuxxezrc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtbvzmbrff.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtsjeqkqxe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtetgvvvfv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtcskwrmev.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gtcwjzljuc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtqeiqhwmn.html

Q SQL 专题                              90
来源：http://dali.jyoumei.cn/Article/details/gtrzraqrzj.html

R Bash 专题                             80
来源：http://dali.havefunace.top/Article/details/gtqgmjpuzz.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gtxhnxlioj.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfucxakq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gtqhxssdie.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtxrinsryi.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthspvnhpo.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtfoitcycv.html


<!-- 参考信息 -->