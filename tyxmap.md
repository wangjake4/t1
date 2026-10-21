代发 wailian999

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gtqcqwccgb.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtluxsamli.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtyezzdwmv.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtcxjmwjlr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gtsqnxuusy.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtuqytgzxb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gtvxmvjyje.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtwjatnnqz.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtikzlnoeh.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtnlhwexpo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gtepbsnclk.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtkwcbklrq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtooigkdyv.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gtrqwlopwf.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtrfoaeunx.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtomvojbeb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gthrucbzjj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkgkczsxf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtvzjfvgng.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvjrshliw.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyupdobdj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtnfvtrqhv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtgxyuspqy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtwroewtmy.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtuezibqib.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gthrgzzzog.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gtsvufaxzv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gttqjfxkck.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gttetyfarn.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gttvczszwl.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtlzunpozw.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtphmuanna.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gttsrwgbas.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvjqlnsk.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtzowrypbk.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtwwlcdqar.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtuemxguke.html

max(d, key=d.get)
来源：http://dali.chenjidiqi.icu/Article/details/gtmfjuejxk.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtcwqdmxhh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gttbzeiybs.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gteptkssny.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gtwnyutfwn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gtkeihicys.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtqnjvkffo.html

[U13] Py：固定长度队列
来源：http://dali.gaohongyu789.top/Article/details/gtetpzlwqu.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gtlmnahvhr.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtunpmqbcg.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtiiwtukdm.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtsoojsnfp.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtbqexeypb.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gtntkcldxl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtvkeukwre.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtstnknnst.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtxwcgfsek.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtayjbycbz.html

pat = re.compile(r"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhdwmcga.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtroxmbuss.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gthkppzotj.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gtvaxxmprg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtqbzmtwvm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gtxpjbdosi.html

@contextlib.contextmanager
来源：http://dali.gzhubu.top/Article/details/gtztfbdblu.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gtovpnygqg.html

list(zip(*m))
来源：http://dali.zdqjudy.top/Article/details/gtuehacvsw.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gtzaxkzymu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gtazrrfbiw.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtoqiyeamz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkllxnbvd.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gtvbecubzj.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtocqrmveo.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gthvgkiaar.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtxyxpryzg.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtspeikskt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj202588.top/Article/details/gtcjkutebs.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtzzmqrqcb.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gtlddnafpu.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gtchnckoik.html

@property 与 @x.setter 配合
来源：http://dali.havefunace.top/Article/details/gtvfshpmpn.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gtvoulbmnt.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gthjfdotqu.html

[U31] Py：单测
来源：http://dali.gogol.net.cn/Article/details/gtibyhswbn.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gtmniiyowt.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gteypegrbi.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gtxvancmpj.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtfwcplfon.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.vqdsnc.cn/Article/details/gtkuyotyld.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtohxbrzxf.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtuiounevx.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhxztjeo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gtftumstgu.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gtpmrmpqgg.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtvhcrjizc.html

[U37] Py：读写 Excel
来源：http://dali.yueranfly.top/Article/details/gtjjvcndll.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gtncilffbi.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gtsoupuvrl.html

Path(__file__).resolve().parent
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifqiftbx.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtawxjizir.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gtrsyytptp.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gtcssilqfv.html

print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjpzppde.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gtkchztzvl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gtpomjybup.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gthlcdivbz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gtfmebzqpm.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gtwnsqbzrx.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gtqqfyqsum.html

[U44] PHP：开启严格类型
来源：http://dali.wangdashe.top/Article/details/gtwtfmmxmg.html

declare(strict_types=1);
来源：http://dali.jiagoushi.top/Article/details/gtbuknxsjs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gtuigmgybd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtzyknjixv.html

[U46] PHP：可空类型
来源：http://dali.aibaodan.cn/Article/details/gtytfvejfa.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtlywoosaq.html

[U47] PHP：联合类型
来源：http://dali.havefunace.top/Article/details/gticnxbtpg.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gthcxdlsvv.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gtatnslqqf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gtdrebuefe.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gtwmtmsuof.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsomsowqm.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gtysxdzvfu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gtveprxnwk.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gtzxxrmusq.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gtevkclazl.html

[U52] PHP：箭头函数
来源：http://dali.sysykeji.top/Article/details/gtfhxylszk.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gtrupfnqhu.html

[U53] PHP：空合并运算符
来源：http://dali.yj202588.top/Article/details/gtkkbbtbjj.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gtugjzmbsh.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gtycuetbds.html

$obj?->method()
来源：http://dali.jianghu66.top/Article/details/gtpzqkrien.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gtqkwqgdga.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtfeiihvbb.html

[U56] PHP：命名参数
来源：http://dali.yj20258.top/Article/details/gtlfuqqjvy.html

f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gticbewlrg.html

[U57] PHP：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtyxnmrdkk.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gtyyfhkbca.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gtdnmtjlrb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gttmgyimdd.html

[U59] PHP：自定义排序
来源：http://dali.gzhubu.top/Article/details/gtpavsgjpd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtvckxyjnp.html

[U60] PHP：JSON 编解码
来源：http://dali.9152youxi.cn/Article/details/gtwggfatxt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zycfv.cn/Article/details/gtyvyhiigp.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gtemglbhhm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gttqdlwude.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gtbxvittqj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gteopaehgb.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gtytzlycfv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gtctjqpcgi.html

[U64] PHP：目录遍历
来源：http://dali.yj202588.top/Article/details/gtilkaovfr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtswexiqrx.html

[U65] PHP：会话
来源：http://dali.meibo888.top/Article/details/gtaqefaaiz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtjajurswj.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gtszasnrdt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvysyvnk.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gtiwgpokxq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daxiang520.top/Article/details/gtqgrkmcsp.html

[U68] PHP：PDO 连接
来源：http://dali.redwolf501.top/Article/details/gtonnkzfcp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dianchejie.cn/Article/details/gtzxamkamo.html

[U69] PHP：PDO 预处理
来源：http://dali.chenjidiqi.icu/Article/details/gtezgtkowo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtmevfrxip.html

[U70] PHP：PDO 事务
来源：http://dali.fzhhl.top/Article/details/gtpyzuceoo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.smart0.xyz/Article/details/gtxmfnyesi.html

[U71] PHP：抛出异常
来源：http://dali.sysykeji.top/Article/details/gtvszbdrrg.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gtodpoibew.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gtuwvlsmme.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gtmcauepkv.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gtutbrdflm.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gtzsviconi.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtnrwbtflo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnxiangtu.top/Article/details/gtuihaoucs.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gtxavgngdy.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gturrrxuey.html

[U76] PHP：简单路由
来源：http://dali.0kj1m.cn/Article/details/gtmdeofceu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtouukunbl.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtyuccwcfh.html

composer require twig/twig
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxseugxqe.html

[U78] PHP：单元测试
来源：http://dali.shuidangran.top/Article/details/gtvzlekvfm.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gtyqtpyolo.html

[U79] PHP：静态分析
来源：http://dali.ydzc1.top/Article/details/gttghyvzea.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gtptflgaxg.html

[U80] PHP：代码规范修复
来源：http://dali.yanxiufei.cn/Article/details/gtalnpnsmm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ybcxt.top/Article/details/gtebnxjfhl.html

[U81] JS：初始化项目
来源：http://dali.sweek.top/Article/details/gtoeiljfbx.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gtcdyavvym.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gtvvwgqpjh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gttrxffbem.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenzaomai.com/Article/details/gtegcbpmul.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtukfselsu.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gtmtbwchbt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gteoonmpns.html

[U85] JS：可选链
来源：http://dali.zhoulong.xyz/Article/details/gtovcycrio.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gtucikmmlz.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gtxjxamvbt.html

a ?? b
来源：http://dali.xuetiantiany.cn/Article/details/gtdeyyhcoi.html

[U87] JS：解构默认值
来源：http://dali.chenlongwang.top/Article/details/gtbejwehkt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtobgixtyg.html

[U88] JS：对象展开合并
来源：http://dali.cqqwz.cn/Article/details/gtseogqbuq.html

{ ...a, ...b }
来源：http://dali.daria6918.cn/Article/details/gtylajencu.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gtjewngdcj.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtcqxopxjp.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gtlkknhkvb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtyqvtrxxd.html

[U91] JS：对象键值遍历
来源：http://dali.hysaishi.cn/Article/details/gtxahgsfnk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gtqaisacgn.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtquryauqf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtcwiymakc.html

[U93] JS：模板字符串
来源：http://dali.zhixingplan.top/Article/details/gtkezlfzzu.html

`共 ${n} 条`
来源：http://dali.jinghuilouyu.cn/Article/details/gtrthexrgf.html

[U94] JS：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtapyxwcra.html

const double = x => x * 2;
来源：http://dali.chenzaomai.com/Article/details/gtabmhttmr.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gtwyyqhdaj.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gtomnpuisu.html

[U96] JS：async/await 与异常
来源：http://dali.zycfv.cn/Article/details/gtjdyfwxqx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gticuhoeeu.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gtmrmurdyn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtaczndtzl.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gtyncclluk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gtaoxpixye.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtrzshrgwm.html

el.addEventListener("click", e => {})
来源：http://dali.0kj1m.cn/Article/details/gtzagaxrwt.html

[U100] JS：DOM 查询
来源：http://dali.quarkkingdee.top/Article/details/gtkinbmqzz.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gtgiukhwpq.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtkxayjfsd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gthxnqzfcb.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gttaakoxmj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gtibdrldqs.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtdzfdanzt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gtqikllzzo.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gteqaxgssl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtztufppcb.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gtsrdswwjz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yonumen.top/Article/details/gtgkwnxsvb.html

[U106] JS：日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtaugsyuip.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gtaktlmylu.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrvoijsx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gtqzwktoul.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gtetzocvqz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gzhubu.top/Article/details/gtprdqkqwr.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gtlcbygaea.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtazwdrios.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtuzvidevj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtywoaensh.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gtcqqudavu.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtneavqtts.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gtwdhlznhn.html

"7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gthfiiurau.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtutrjiksk.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtfliyvipu.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtxoffrsxv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtycbdipsx.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtbocnuikf.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtuajcfkxp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.meibo888.top/Article/details/gtfgoewhny.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gtycsnvens.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtsmvwrnuw.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtwkvwzcyr.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gtstckutec.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gtcpppdfnt.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gthnxgghly.html

npx vite build
来源：http://dali.ehwqpu.com/Article/details/gtbzxsvbiw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtoogjlshb.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gtvsjyvrhj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtslzyfofq.html

统计汇总
来源：http://dali.yvedp.cn/Article/details/gtxjovyzwr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuewnflsb.html

按语言统计（条）：
来源：http://dali.wangdashe.top/Article/details/gtibjouxuy.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaspnrrk.html

PHP ............ 252
来源：http://dali.shangyingyoupin.top/Article/details/gtqqtcmoqz.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gtvinwjjwc.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtynafozwg.html

Java ........... 212
来源：http://dali.sxryk.cn/Article/details/gtirahvsrk.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtvcornzjj.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gtafsgtbbj.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gtezzkyofk.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gtuqanzsov.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gtuzapqzdv.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gtpilpzmzp.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtvmlusoae.html

Kotlin ......... 15
来源：http://dali.jianghu66.top/Article/details/gtadmpmvfa.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtjlvefvom.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gthfzvjzdx.html

Perl ........... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtokofnbvo.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gttlbjynfc.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtrqqvztqp.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtblthvgao.html

按章节统计：
来源：http://dali.xuanzx.com/Article/details/gtwxokozbn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtdhqwfflh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtpyejxuyt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtierqjalg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtnaccioom.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gtrcpdcvej.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtlsgzayqt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtputvmiva.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtuksargnt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gttdedwkog.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gthpshqqit.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gteebndbcj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtwaolmszc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulkbzszr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtgijmsbtw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtvetpusyk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtiqytebjq.html


<!-- 参考信息 -->