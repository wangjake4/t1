代发 wailian999

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtktrqabpt.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtnnfgutzw.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtxjcqcvjp.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtypkrcivp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gttjgmqozm.html

[T55] Scala：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtsbmjkldc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxinmrrf.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtspyoazsd.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtleldauhp.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtmjpinghw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtubljtlav.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtvuadqztn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtqslybytt.html

[T59] Scala：循环
来源：http://dali.meibo888.top/Article/details/gtjcjfctlw.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtmmljwvwp.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gtzjsodrxd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gtpzxbirks.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzwokngo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtuugpezkn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxxolzywr.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtlmhwlgkf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gtqczqnnra.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gtzgmxaqpb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtxxmxwkxz.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtruttrhll.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gtsrtuatzm.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gturcthgkz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gteostvoke.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gtgtymfctr.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtqinaxyjt.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtgpvhiasu.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gtbwvnomib.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gtcjpbsybe.html

{v: k for k, v in d.items()}
来源：http://dali.sweek.top/Article/details/gtklrbgepv.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gtgelxdyfj.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtjafdhmli.html

[U09] Py：字典取最大值的键
来源：http://dali.hnxiangtu.top/Article/details/gtgxlgwxzx.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gtaafxnmmz.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtklnhdrlu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtgejngpbw.html

[U11] Py：生成器表达式
来源：http://dali.dianchejie.cn/Article/details/gtnxaopxen.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtwtttzxyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtxcszjzoy.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtravkzhqg.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gtzfwfgegd.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxoetorh.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtizytaluj.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdsmcyym.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtfiubwceq.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtxonpissk.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gtcsjffssx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gtvhfrofpj.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtogasugvl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gtjsmrcuot.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtaqsugpwu.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtotnoqgek.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gtrqnwxqta.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtunvpaxjp.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gtnezvczrh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gtjsbcqxrq.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtrbexkxxs.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtpcjophta.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gthdakesmo.html

list(zip(*m))
来源：http://dali.zdqjudy.top/Article/details/gtdfpsdnco.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtgoeuxzxi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxinkj.top/Article/details/gtozsxikcm.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtgkyqyxpr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtrxudpuqd.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangtech.top/Article/details/gtogjsicen.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbnribym.html

[U26] Py：并发下载
来源：http://dali.yuanzhike.top/Article/details/gtuomwgzzv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gtnmstdenp.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gtqdhuxlbg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtexvybbgt.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtnaebvxsq.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gtfaxlbcsz.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gtdxxmyxvg.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtpbjpcxqf.html

[U30] Py：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtkedosufp.html

@dataclass(slots=True)
来源：http://dali.daria6918.cn/Article/details/gtqrwtiwvd.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gtmqhlohsi.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gtnffynunr.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gtxituajze.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gtujypjkoe.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gtbpndfoxg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hfpthk.cn/Article/details/gtdjxqccla.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtghkgqtsj.html

chardet.detect(raw)
来源：http://dali.jqgfzy.top/Article/details/gtnddkgvof.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtdijaiuyw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtnasajxtm.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtepskmvwk.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gtxzdrichy.html

[U37] Py：读写 Excel
来源：http://dali.ehwqpu.com/Article/details/gttqrhwztj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gtzhozwgoy.html

[U38] Py：获取脚本所在目录
来源：http://dali.cdnleiting.top/Article/details/gtcxtwdtog.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gtvijccsds.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gtvgfmhbgl.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttofutkdl.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gtrulvkrlu.html

print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtjvgkddil.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gtxovclofz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gttdbvnfwe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258.top/Article/details/gtgvvhfdsm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gtsumqjivj.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gtxkfaxntp.html

namespace App\Http;
来源：http://dali.shuidangran.top/Article/details/gtnahghjku.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtissmbkar.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtrbskrxhy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gttqaxhrbs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtsptrvohf.html

[U46] PHP：可空类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyqkecqt.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gttckoglic.html

[U47] PHP：联合类型
来源：http://dali.jqgufenzy.top/Article/details/gtstzwibly.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtuveelvaj.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gtzfveqrli.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hammf.cn/Article/details/gtbzbtlajk.html

[U49] PHP：只读属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgfemitn.html

public readonly string $name
来源：http://dali.nanxuanxn.top/Article/details/gtflmgkiwd.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gtjufcuczk.html

public function __construct(private int $id) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdborfkrc.html

[U51] PHP：数组解构
来源：http://dali.jyoumei.cn/Article/details/gtzetrrsfr.html

[$a, $b] = $arr;
来源：http://dali.cashguo.top/Article/details/gtzwlrmauy.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtuhxahecv.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkpnttrw.html

[U53] PHP：空合并运算符
来源：http://dali.sysykeji.top/Article/details/gtwphalevr.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gtprqvodmw.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gtwiyxgjae.html

$obj?->method()
来源：http://dali.svipenyu.cn/Article/details/gtyhghnkkm.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnyhstpk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gttfcygxbm.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtdfxonftl.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtziyxsgns.html

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgqmhhig.html

"值: {$a}"
来源：http://dali.aizwys.cn/Article/details/gtidcihfcw.html

[U58] PHP：数组三件套
来源：http://dali.hnxiangtu.top/Article/details/gtrkjcyepz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fzhhl.top/Article/details/gtjldrxpjm.html

[U59] PHP：自定义排序
来源：http://dali.hongshengwenyu.top/Article/details/gtlsbodugq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtksbzifqo.html

[U60] PHP：JSON 编解码
来源：http://dali.jiagoushi.top/Article/details/gtlofsmtzw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gtxcivkazn.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtzaeypnzm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtxdpmwtmu.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gttvndcorw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yangfankeji.com/Article/details/gtgldowvnt.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gtsenbvzxw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxinkj.top/Article/details/gtwgzsytfc.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gteiorsiih.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gtpusxzllk.html

[U65] PHP：会话
来源：http://dali.tian-w.cn/Article/details/gtljeertyx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttsqucstd.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gtlrbtjget.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtegdxipzk.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gtpkbcshlm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtlgoxuavm.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtloaheuys.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gtqmqrglhk.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gtkotyrudo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtextifmqv.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gthflzxdnd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gttsmkeazt.html

[U71] PHP：抛出异常
来源：http://dali.sysykeji.top/Article/details/gtegycstlg.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtvmavxwdi.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gtuldplokc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.birdmap.top/Article/details/gttosxruuh.html

[U73] PHP：读取 ini 配置
来源：http://dali.jiagoushi.top/Article/details/gtywvcuiee.html

parse_ini_file("config.ini", true)
来源：http://dali.hnxiangtu.top/Article/details/gtskjfcawl.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtkmqikzbg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pycfn.com/Article/details/gtjwjhnbhp.html

[U75] PHP：依赖注入
来源：http://dali.ivvv.top/Article/details/gtlqvrqtdp.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxrabgif.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gtxkktalez.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nwbrower.top/Article/details/gtrwvmdvtt.html

[U77] PHP：模板渲染
来源：http://dali.hfpthk.cn/Article/details/gthuesvgqi.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtjxvroyri.html

[U78] PHP：单元测试
来源：http://dali.pycfn.com/Article/details/gtgepsaoiw.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gtgbdxhhee.html

[U79] PHP：静态分析
来源：http://dali.cdnleiting.top/Article/details/gtkwoxjqbd.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gtbzheqeil.html

[U80] PHP：代码规范修复
来源：http://dali.sysykeji.top/Article/details/gtplmbbedp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gtxyqdqpmv.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gtebzuxkab.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gtzqvpraai.html

[U82] JS：package.json 脚本
来源：http://dali.guannengcc.top/Article/details/gtvmzshhpa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daxiang520.top/Article/details/gtejaumuqx.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258.top/Article/details/gtscgguohu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gthchqjxbw.html

[U84] JS：CommonJS 写法
来源：http://dali.shzxlz.cn/Article/details/gtiznbfjpl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.316326.xyz/Article/details/gtmwzdtwse.html

[U85] JS：可选链
来源：http://dali.nwbrower.top/Article/details/gtueibiiwi.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gtbcamwjgv.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gtdjbunszl.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtrovvjnny.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gthvmiaxcb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xylfe.cn/Article/details/gtbwhpzgbw.html

[U88] JS：对象展开合并
来源：http://dali.shangyingyoupin.top/Article/details/gtjkfpgete.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gtfvqiucxv.html

[U89] JS：数组去重
来源：http://dali.shuidangran.top/Article/details/gttbuaxxwt.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtnmhffizf.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gtivdgvhmr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotqodkjn.html

[U91] JS：对象键值遍历
来源：http://dali.mhx1999.top/Article/details/gtcycgyfeu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gtcpcpnkmb.html

[U92] JS：深拷贝
来源：http://dali.shzxlz.cn/Article/details/gtqspbcaxx.html

structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gttgcrvfhj.html

[U93] JS：模板字符串
来源：http://dali.gaohongyu789.top/Article/details/gtgcuhrrjl.html

`共 ${n} 条`
来源：http://dali.yuanzhike.top/Article/details/gtiwbuipvw.html

[U94] JS：箭头函数
来源：http://dali.c1oappe.top/Article/details/gtjegnwebb.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gtknmjkcvd.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gtdsdjjuac.html

new Promise((resolve, reject) => {})
来源：http://dali.yuanzhike.top/Article/details/gthjpzyfus.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gtlnpznqmu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuvqpdak.html

[U97] JS：并发请求
来源：http://dali.pengpengdd.cyou/Article/details/gtnftcfuhz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtaypsxnbp.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gtpguftrgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gticnnsuou.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gtuxzaqdpr.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gtrbsolftc.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gticzsemcf.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gtnhmniawx.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gtwjfprtnu.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gtxbqdqtvi.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gthslvpdjc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ehwqpu.com/Article/details/gtmjdjmyhs.html

[U103] JS：定时器
来源：http://dali.xziqi.cn/Article/details/gtdgxqwfgv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fengsongda.top/Article/details/gtnhsyblge.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gtuiyxkutr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtvuzyhqyn.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gthpkjjrid.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowoicsmu.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtpqeewnzh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gtasslomcj.html

[U107] JS：数字千分位
来源：http://dali.yj20258888.top/Article/details/gtdvmktaqw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtdbfondmb.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtlvjmovuu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxuanxn.top/Article/details/gtcclinrom.html

[U109] JS：数组分组
来源：http://dali.xylfe.cn/Article/details/gtbbwvyauy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtkhxgzvxe.html

[U110] JS：数组分块
来源：http://dali.pengpengdd.cyou/Article/details/gtgykjehbh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gtbwddcybu.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gtwfyrittk.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gttqzsieva.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtsrjfjwny.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gteckfziyy.html

[U113] JS：正则替换全部
来源：http://dali.nanxuanxn.top/Article/details/gtkobhqrjv.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtjxoisfql.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gtlrcwzrmo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtjpwuiazs.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtwxbaeclz.html

crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtmnwsmmde.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gtohjmgvzb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gtbuyiquiz.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gtqgebpqsx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlsciygx.html

[U118] JS：开发服务器
来源：http://dali.nanxuanxn.top/Article/details/gtlbptvbao.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gtrprfzuqt.html

[U119] JS：生产构建
来源：http://dali.yuxming.cn/Article/details/gtsjkiprpz.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtoogkzwzg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gtamekwmxf.html

import.meta.env.VITE_API_URL
来源：http://dali.pengpengdd.cyou/Article/details/gtxnlgjzlc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtucftbufi.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtqfxvpyfb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfemitzrb.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtgzfslazr.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gtheunlhjc.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gtaeaoaeqv.html

JavaScript ..... 252
来源：http://dali.yj20258.top/Article/details/gtdgyikpns.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gtlprkskah.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtcwmekxlt.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtzsiqiwhd.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtbelnjunv.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtogownkhu.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtpflhuwzo.html

C++ ............ 30
来源：http://dali.hnxiangtu.top/Article/details/gtvzpnobce.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gtclebbmwg.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxymvicq.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gtigqqpaqy.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gtraoqnlgu.html

Lua ............ 10
来源：http://dali.shangyingyoupin.top/Article/details/gtcmhrfung.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gtrwkctmpi.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gtkwgmrtrn.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtfbccfhax.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtbrzbgaly.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gtoyzlneri.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtbevtggur.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtdizscclv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnfgwdgx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtiydnwnsc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.meibo888.top/Article/details/gtyrhnxwwa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtypmkrzfe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtmucrirln.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtuoxfqqhc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtwvwwvyps.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtooqwtsvn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtnpijxeqk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gthqzoqura.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtghvruybk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gtmbliatkw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aibaodan.cn/Article/details/gttqgevzlw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtdzndlsox.html


<!-- 参考信息 -->