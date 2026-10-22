代发 wailian999

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtobktspax.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtxwohabtl.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtovfwjhss.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtwyepiogs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtezxmbxde.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gttfbtkgem.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gtpwhjabbx.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gtbztjzvho.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtfubwjgaa.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtbsimupgq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtpltpcnpa.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gtsrntihcb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtwoaurfyz.html

[T59] Scala：循环
来源：http://dali.yj202588.top/Article/details/gtlvnhbecx.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkkjygpp.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtgmyiphdt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gtujbdqaxp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxwpmzimh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gtdsccdyus.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcdrqjkct.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gtrahqeyag.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtvthaflqb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeywkcpg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtaxtuxvsz.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtygmsbwdb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtmkyouwav.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gtfuxdfanz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtdnclikfc.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gtvsxosafh.html

list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtqnxarrbe.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtvikftkdv.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gttldmvlio.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtvuteammf.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gtnfmwgpzx.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gtomgdfoqx.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtavbitbfs.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gtozijkdgl.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gtibsukppt.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteirwpaga.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gtfaucrykl.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gtzjwpvqfd.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtskkulbvz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gtggddsvxr.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtzkhivmnk.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimdghqgf.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gtmuqebgbw.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtnzfwnytr.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gtzcnbleon.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtxeafxwwq.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gtxbyrcizg.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtojguwtah.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gtfycgreap.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtrhozgemh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gtxmwyfpkc.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gtaznudcbz.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtfyvprysm.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gtipwwndip.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gtjeheeaet.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtlcroqbbv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtlguanucj.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gthxvkpokj.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtjdzwpfjz.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gtmikatubo.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gtcxpcvsnn.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gtmwayivjt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtehwrlylt.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtvhrxfqhr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtuihaipry.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtbubqgamv.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gtmwumhggu.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtnvfgzfey.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gtoryhuofn.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gtfryyqqss.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gtbahpiqsj.html

[U28] Py：类型别名
来源：http://dali.hywenlv.cn/Article/details/gtlusitqok.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gtarifvlhp.html

[U29] Py：属性校验
来源：http://dali.daxiang520.top/Article/details/gttfkuczjx.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gtykphftug.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gtnvupyalw.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtsvipsrpl.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtvzokanui.html

python -m pytest -q
来源：http://dali.hnxiangtu.top/Article/details/gtdabxttlz.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gtzuexytwf.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gtfuayhumv.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvythtgh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gtggbejtjm.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtpbfsxozy.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gtvzdcvtwk.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gtsiqyabcj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gthnjcnbbp.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtrcntylbu.html

schedule.every(10).minutes.do(job)
来源：http://dali.kuanghao11.cn/Article/details/gtkikjrkmv.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gtyaeacujn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258888.top/Article/details/gtybesfpgf.html

[U38] Py：获取脚本所在目录
来源：http://dali.snrcjt.cn/Article/details/gtdeonodbw.html

Path(__file__).resolve().parent
来源：http://dali.jiagoushi.top/Article/details/gtntwxtriv.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gtjldhgjor.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gtoudmjeeq.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gtznwowjkq.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtuyzzlttf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gtriqmsxix.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daria6918.cn/Article/details/gtppvgbxwp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtistjlpgy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtdtdgibvv.html

[U43] PHP：声明命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxqbqvlz.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gtczvpqxms.html

[U44] PHP：开启严格类型
来源：http://dali.9152youxi.cn/Article/details/gtujdhszuo.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtnfsotsyc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gtjeshyopf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrzwpmntg.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gtxdhsfxla.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gtcgsmmwzy.html

[U47] PHP：联合类型
来源：http://dali.jianghu66.top/Article/details/gtdadkghdd.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtizppfsru.html

[U48] PHP：纯枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtpfdxurhu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daxiang520.top/Article/details/gtffxyeier.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtrsewktkb.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gtyjuujceq.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gtkumhqwgv.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gtjklizijk.html

[U51] PHP：数组解构
来源：http://dali.snrcjt.cn/Article/details/gtwidduadc.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gtdyjtjjaw.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtotqtnqol.html

$double = fn($x) => $x * 2;
来源：http://dali.xziqi.cn/Article/details/gthkmgrytu.html

[U53] PHP：空合并运算符
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxapehvb.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gtuvfmtjxf.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gtzabhwzte.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gtyeiodwih.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gtutgieymj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtzbcisyvm.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtqvtwclsv.html

f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtgspwbvjc.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtannfyyzz.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gtnedkoifx.html

[U58] PHP：数组三件套
来源：http://dali.ehwqpu.com/Article/details/gtcefmidih.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtbnsedpbp.html

[U59] PHP：自定义排序
来源：http://dali.ppjwa.cn/Article/details/gtkbzabyts.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtmkhtrhpv.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gtdmzchtmw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jianghu66.top/Article/details/gthcqplttw.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gtbzdvvjyc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtmavynrcl.html

[U62] PHP：日期对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsqtpcgz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtnmbtwttl.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gtnenfysah.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gthvbbklut.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gtnjvvouud.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gtzzzwsfzn.html

[U65] PHP：会话
来源：http://dali.guannengcc.top/Article/details/gtwghxctlw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gtjshcooqo.html

[U66] PHP：设置 Cookie
来源：http://dali.xylfe.cn/Article/details/gtqrckarly.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtweepsurs.html

[U67] PHP：处理文件上传
来源：http://dali.jlsjyb.cn/Article/details/gtgfqfjirt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmkqaekg.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtoavvqlee.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gtwvnogpqw.html

[U69] PHP：PDO 预处理
来源：http://dali.smart0.xyz/Article/details/gtmrgauylk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhiwuduotai.top/Article/details/gthpoijeyc.html

[U70] PHP：PDO 事务
来源：http://dali.gaohongyu789.top/Article/details/gtwyrjvcbi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gtymmkqynx.html

[U71] PHP：抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtckjbmsab.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtnmzbnwrh.html

[U72] PHP：写错误日志
来源：http://dali.sweek.top/Article/details/gtvfetncbh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gtjfpzyrri.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigufen.top/Article/details/gthnhoxwva.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtjvwjutqz.html

[U74] PHP：读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtcoasgesr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtzbsopkow.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gtuhaupexg.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gtckrumkcz.html

[U76] PHP：简单路由
来源：http://dali.xuanzx.com/Article/details/gtxeupizwb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gtkuwlwuyg.html

[U77] PHP：模板渲染
来源：http://dali.sysykeji.top/Article/details/gtymqvnurt.html

composer require twig/twig
来源：http://dali.quarkkingdee.top/Article/details/gtjkyblsgx.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtdiswhqhs.html

composer require --dev phpunit/phpunit
来源：http://dali.dianchejie.cn/Article/details/gtcigmdgas.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuplfzte.html

composer require --dev phpstan/phpstan
来源：http://dali.ydzc1.top/Article/details/gtshnneswj.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtqjhmzmoy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zycfv.cn/Article/details/gtpsaepmfx.html

[U81] JS：初始化项目
来源：http://dali.fengsongda.top/Article/details/gtohicdipl.html

npm init -y;  npm i express
来源：http://dali.hongshengwenyu.top/Article/details/gtlnvqknpt.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gtzloklxdj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gtdkbpbnsv.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gtjdvovgah.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtxnlzuwgu.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258.top/Article/details/gtyjwtseqm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj202588.top/Article/details/gtkutccryy.html

[U85] JS：可选链
来源：http://dali.shangyingyoupin.top/Article/details/gtvxgmjzhm.html

a?.b?.c
来源：http://dali.zhongyouzk.top/Article/details/gtpjvforxv.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gtrvisyvmg.html

a ?? b
来源：http://dali.smart0.xyz/Article/details/gtpaenxufe.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtknzaampe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gtriaoxdfm.html

[U88] JS：对象展开合并
来源：http://dali.jyoumei.cn/Article/details/gtizqilmmn.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtdgmqwc.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gtwnbsfmda.html

[...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtbzqbulmw.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gtetecvzlv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtajoclltx.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gttsbqxdru.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gtzwmmfyos.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gtjpoxxovx.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtfzwfnldn.html

[U93] JS：模板字符串
来源：http://dali.shuidangran.top/Article/details/gtuzwzihfe.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaozsand.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtwiodewoz.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtrxtfkxlg.html

[U95] JS：Promise 包装
来源：http://dali.mhx1999.top/Article/details/gtwagiyrmf.html

new Promise((resolve, reject) => {})
来源：http://dali.feifeiyinyue.top/Article/details/gtrrcgjchm.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtjcbksoqt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtzvmnyarm.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gtxyoztcpl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtaticbzsi.html

[U98] JS：fetch 带 JSON
来源：http://dali.guannengcc.top/Article/details/gtrrwbpqhb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtiotaqjzg.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gtkenfegiw.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gtaucpxwsn.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gthrpflaal.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gttezmphiu.html

[U101] JS：classList 操作
来源：http://dali.smart0.xyz/Article/details/gtgnqoeafx.html

el.classList.toggle("active")
来源：http://dali.316326.xyz/Article/details/gtyrhsijap.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gtqvbtimgr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgufenzy.top/Article/details/gtmeklolrl.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gtieqyxctc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtizuvixdg.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtdhircxou.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gthmhwvemg.html

[U105] JS：节流
来源：http://dali.cucudq.cn/Article/details/gthujwbjwy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtxnfkvuon.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtojqgengj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gtogpbbamt.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gthqrcvmto.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gtetglcjet.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhhgyyto.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhpwksqt.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gtsqyulgsl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtxywcojvi.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gtwytwtzcb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gtrtysmoyt.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtczvmjhub.html

new Map(Object.entries(obj))
来源：http://dali.bjfxy.top/Article/details/gtluzcytuj.html

[U112] JS：字符串补位
来源：http://dali.jyoumei.cn/Article/details/gttjwleyby.html

"7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrhbbsad.html

[U113] JS：正则替换全部
来源：http://dali.jlsjyb.cn/Article/details/gtoamgwuya.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtpocjzxct.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtmwfcvnnf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtkkdltdjz.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtsuurmaax.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtexsaeosu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenjidiqi.icu/Article/details/gtkbkdmztq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gtljizxkym.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gtuutalspy.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gtdacsbjgy.html

[U118] JS：开发服务器
来源：http://dali.dianchejie.cn/Article/details/gthrbpzyvn.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gtxvefdjaa.html

[U119] JS：生产构建
来源：http://dali.fzhhl.top/Article/details/gtuweemxxq.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gtcewylvnb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtbiawuvfk.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtwdclmzqw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkhmfwafy.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtxqctqhdy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmxjzhznr.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoedfercs.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gtvhpihjze.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtrplgxrhs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtrztuvici.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtpgojdotu.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtzppoxpkt.html

Go ............. 212
来源：http://dali.daria6918.cn/Article/details/gtrrynbxxl.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtlmzwozcu.html

C# ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtkgrboiie.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gtunnwlpdx.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gtjbrwbtiu.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gthzumubrc.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtzhqubpof.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gtkflurpjq.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtxuuvfsbb.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gtxnovvggu.html

Perl ........... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtgdwrotxx.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gtdgvplnac.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtsiuiencc.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtranyiyiy.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtxgdjhdge.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtjzijkttp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtpkthfrds.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtfffttgka.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtjriicgkn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gtfdoekdkz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gthncjkfhm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtuovezxpa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtjmsbdaan.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gteqgditui.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gtclfigcds.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtlhjviqjs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtgvinojjn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtkjwfghge.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gthsvzaztt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxinkj.top/Article/details/gtvxlivnxi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtfsdeqwnp.html


<!-- 参考信息 -->