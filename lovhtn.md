代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gtdpmbztkh.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtcowsgliv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwoarooq.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gtluugbjok.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtojfeyhfv.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gtregmrcsc.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gthawoifjg.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtwgwqzzsy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gttyffuexh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrhfuipch.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtixbbtkbh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtuvhakbnt.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gthgstocry.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtzwwnmlhv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gtaooxswir.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtzvdankjy.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtmrpdmofp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtcbznpbap.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtrervcmwx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtwdglpshr.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gtvijjlzry.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtkrgcktgu.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gthqzserjm.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtwwmnnjif.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtcnywaqjr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gtcndvkexz.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gtywavkxtn.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gtxkjtreac.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gthpwvdneo.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gtofxzrpwz.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtxrzwuvmj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtpiqwpycu.html

[U11] Py：生成器表达式
来源：http://dali.dianchejie.cn/Article/details/gtlicnmiom.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtblbieupg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtbhlnxsxg.html

Counter(arr).most_common(3)
来源：http://dali.gaohongyu789.top/Article/details/gtsqyzvwlu.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtcltvhckk.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gtoxczlxwd.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gtzscwurdu.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtswigavmi.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gtcbfbggjv.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtsugftfcl.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gtwamolimg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.haohaochexian.top/Article/details/gteasdixkb.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtoqzftmtz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gtpzqapblk.html

[U18] Py：预编译正则
来源：http://dali.daxiang520.top/Article/details/gtytczmljy.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtpvxdlwfp.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gthvwckxdj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtljrpztul.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gtywdywmsw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gtqypaqpsw.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtovxnkotp.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtqmdfjlpp.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtyjrkuhef.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gttelrdlrz.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gtjjqqpuej.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtujnailch.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gtcnxmlsyi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtlmdranio.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtejtlemtp.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gtjocdrdqu.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gtcrvvlieu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhhorwri.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzpxfbqp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhoulong.xyz/Article/details/gtuygppgmd.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtygmsrala.html

UserId = int
来源：http://dali.meibo888.top/Article/details/gtqjmweggu.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtbnireqah.html

@property 与 @x.setter 配合
来源：http://dali.aibaodan.cn/Article/details/gthxlvdfqz.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtxnexniip.html

@dataclass(slots=True)
来源：http://dali.kuanghao11.cn/Article/details/gtzhfrqzpg.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gtvgibqpdd.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtbnvacvvf.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtivhucnpp.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtpjvxgeld.html

[U33] Py：打包发布
来源：http://dali.yuxming.cn/Article/details/gtdgyasrco.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.feifeiyinyue.top/Article/details/gtrxeoxryw.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtyecfhkum.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gteorltrdt.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtbydxfzlt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gtzxlubogg.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gtwzkgcrjd.html

schedule.every(10).minutes.do(job)
来源：http://dali.hywenlv.cn/Article/details/gtmvxlsnlq.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtkrsdvemh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gtuyjjyavc.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gtmmoephpu.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gtjwmxgwya.html

[U39] Py：判断是否在交互环境
来源：http://dali.haohaochexian.top/Article/details/gtnyrognig.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtcewfcpqu.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gtndscjkly.html

print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtllxgnnno.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jianghu66.top/Article/details/gtkryogvgz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gtxjtlcmec.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258.top/Article/details/gtymikmctj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gticzchacn.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gthprssjiq.html

namespace App\Http;
来源：http://dali.vqdsnc.cn/Article/details/gtuppgruhv.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtkmnzoh.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gtxybicxkl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gtbnjyqoix.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhwlaokp.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gtpdebueot.html

?string $name = null
来源：http://dali.zhiwuduotai.top/Article/details/gtbyjtiaxv.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gtdffclncu.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtdankqvlv.html

[U48] PHP：纯枚举
来源：http://dali.snrcjt.cn/Article/details/gtrsnojjwd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xziqi.cn/Article/details/gtgndlsona.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gtansemuyt.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gttotobhyi.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gthkdfmmtg.html

public function __construct(private int $id) {}
来源：http://dali.meibo888.top/Article/details/gtdagvkarm.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtpyemirbo.html

[$a, $b] = $arr;
来源：http://dali.redwolf501.top/Article/details/gtgvrmknpo.html

[U52] PHP：箭头函数
来源：http://dali.yuxming.cn/Article/details/gtowteyujf.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtefyvbaxy.html

[U53] PHP：空合并运算符
来源：http://dali.nwbrower.top/Article/details/gtglofaldz.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gteqpxgxqy.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gthyvhdomo.html

$obj?->method()
来源：http://dali.jinqigfzy.top/Article/details/gtvjdpiszp.html

[U55] PHP：match 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtebtdooop.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtfcdohmty.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gttahuxrqx.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtcnicqiuh.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtwukhklhh.html

"值: {$a}"
来源：http://dali.c1oappe.top/Article/details/gtapfinpmv.html

[U58] PHP：数组三件套
来源：http://dali.jqgufenzy.top/Article/details/gtqhyliqoi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258888.top/Article/details/gtahjwychl.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gtzfxijxwa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtektmmxjj.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gtsrcrqlbh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylyjynfe.html

[U61] PHP：正则
来源：http://dali.tanke756.top/Article/details/gtygxocfzw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtxotvtchq.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gtxohufoqo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangshuangyany.cn/Article/details/gtqlbkhvxe.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gtedwgclxr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sweek.top/Article/details/gtgbyqqnch.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtuoeufkbv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gtaeyoceym.html

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gtvenigsxo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgljxuet.html

[U66] PHP：设置 Cookie
来源：http://dali.9152youxi.cn/Article/details/gtyexpipes.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwknmoeg.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gtvcopwpqc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtqpabipyx.html

[U68] PHP：PDO 连接
来源：http://dali.mhx1999.top/Article/details/gtxjqspboi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gtqlwsbtli.html

[U69] PHP：PDO 预处理
来源：http://dali.ybcxt.top/Article/details/gtihdlosfe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hywenlv.cn/Article/details/gthjdshzdc.html

[U70] PHP：PDO 事务
来源：http://dali.meibo888.top/Article/details/gtjfwpftvw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jlsjyb.cn/Article/details/gtwyupaltn.html

[U71] PHP：抛出异常
来源：http://dali.fzhhl.top/Article/details/gtktuhaqdv.html

throw new RuntimeException("失败", 500);
来源：http://dali.cashguo.top/Article/details/gthntrhwjm.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gtgcardrvs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtbxzniqvr.html

[U73] PHP：读取 ini 配置
来源：http://dali.hysaishi.cn/Article/details/gttmftudke.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gtvvgvgqin.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtdsjpulxh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jianghu66.top/Article/details/gtorrjcbcy.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gthrhwuvmm.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtspbbofch.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gtajfrhzcu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dianchejie.cn/Article/details/gtqkqlfkhg.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gtjmqlxfou.html

composer require twig/twig
来源：http://dali.chenzaomai.com/Article/details/gtqhgcjbmd.html

[U78] PHP：单元测试
来源：http://dali.tian-w.cn/Article/details/gtbexqauxx.html

composer require --dev phpunit/phpunit
来源：http://dali.kuanghao11.cn/Article/details/gtzagnhhyv.html

[U79] PHP：静态分析
来源：http://dali.guannengcc.top/Article/details/gtasvgtuzd.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gtbhslmybe.html

[U80] PHP：代码规范修复
来源：http://dali.zhongyouzk.top/Article/details/gtyecxidhe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj202588.top/Article/details/gtjxhfupve.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gthrjvytht.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtvvvyusio.html

[U82] JS：package.json 脚本
来源：http://dali.yonumen.top/Article/details/gtqybhetms.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yongpay.top/Article/details/gtibplhozf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhengqikj.top/Article/details/gtjytlwpkn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtnhowgsse.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gtoimqzyvm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gtnoogzeov.html

[U85] JS：可选链
来源：http://dali.zycfv.cn/Article/details/gtawsnxyhq.html

a?.b?.c
来源：http://dali.cheryme.top/Article/details/gtrmthxjft.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gtuoetuppp.html

a ?? b
来源：http://dali.wangshuangyany.cn/Article/details/gtkivlsfqy.html

[U87] JS：解构默认值
来源：http://dali.kuanghao11.cn/Article/details/gtphtsogdo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdbvkzct.html

[U88] JS：对象展开合并
来源：http://dali.xylfe.cn/Article/details/gtkeoctlvp.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gthrnhjbst.html

[U89] JS：数组去重
来源：http://dali.ivvv.top/Article/details/gtefwaqxvh.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtgstuckde.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gthgozuygl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtjjuusptr.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtgozjloxj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjabgtwde.html

[U92] JS：深拷贝
来源：http://dali.nanxinkj.top/Article/details/gtqzoddqix.html

structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtwirfaooo.html

[U93] JS：模板字符串
来源：http://dali.jlsjyb.cn/Article/details/gtvvaotcnf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gtpbfpudya.html

[U94] JS：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtigilluyb.html

const double = x => x * 2;
来源：http://dali.iojbl.cn/Article/details/gtydafjgsj.html

[U95] JS：Promise 包装
来源：http://dali.xinyue.icu/Article/details/gtoamhhwcw.html

new Promise((resolve, reject) => {})
来源：http://dali.sweek.top/Article/details/gtockxmvdv.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gtqppnbvxv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtujyjqutw.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gtgiqulvds.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtbjfnmglh.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gtyjuscjww.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuetiantiany.cn/Article/details/gtgmshkedk.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gtcutaqire.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcqzxzii.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtmvxuuvgf.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gtwwkntpbk.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtcovpznxv.html

el.classList.toggle("active")
来源：http://dali.zhongyouzk.top/Article/details/gtqrrpijpm.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtfhhyaytg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gtcjoyaoaa.html

[U103] JS：定时器
来源：http://dali.yangfankeji.com/Article/details/gtqvezdagx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxuanxn.top/Article/details/gtxwsugtpg.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gturbpcyoc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtnrgucehl.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gtyiandctq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shuidangran.top/Article/details/gtjksrxxor.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtmvwejerb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gtawgcixxg.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gtcdwbynrk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtxwuzrywh.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gtdvvuwpwh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtmxeofpbg.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtqczjgpgj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtrxgcmaie.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gtrxofqpot.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gtbtivlfmu.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtqwbnyuvj.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gtgfyhibjf.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gtueczbcus.html

"7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtopfkymnd.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gthqpjqfuo.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtnusvpzlg.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiytyplle.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gtidsebsms.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtqlwgiolz.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtbxyyawqi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtinvhoihf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gtggltdsxx.html

[U117] JS：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtfyktdudj.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gtemwiljlp.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtdtonmnqd.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyltisnn.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gtdtxpdlvt.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gtbmulsjtu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pengpengdd.cyou/Article/details/gtdgigciex.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gtspydrtdg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtajhmxibv.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtmgtzkzha.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzwyukxmu.html

按语言统计（条）：
来源：http://dali.ivvv.top/Article/details/gtjtfhtadr.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gthtnrekaw.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gtttquvdfw.html

JavaScript ..... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtqhcaflmp.html

TypeScript ..... 212
来源：http://dali.gotoacloud.top/Article/details/gtlpvrtlns.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gtvjfhqxvp.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gtuzdqqwld.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gtpvsomtgm.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtjsunlhou.html

C .............. 30
来源：http://dali.cucudq.cn/Article/details/gtplqcbwai.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gtzotrpocv.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gtqctkclox.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gtxdokypqh.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gtxktqbyyw.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gttizpbzck.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gtejqedfje.html

Perl ........... 10
来源：http://dali.tian-w.cn/Article/details/gtxrcubudw.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gtptilvhig.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtmbmpkcdh.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gtxuyhgzlr.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtnemxuuzk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtxdcbcpse.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtrmwxoslb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtdkifaqas.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gthzcmuxrh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gtztsqkkgh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqpavqin.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtobgupesp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtsguyzbiy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gteoiutewd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtbhbgljvb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gticjdjzlp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjjkqify.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtheyalryy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtuceobbgm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gtculqjjuk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtbqmprjkv.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gtdrzzgbzx.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gtvyulbnpe.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gtjerdrhhn.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gtsducvlyb.html

U 高频实用片段                         120
来源：http://dali.redwolf501.top/Article/details/gtnzkzngnt.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtoogmfilm.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gtpxdykfkw.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtkbkxhhjh.html


<!-- 参考信息 -->