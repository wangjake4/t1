代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2shtsjljy.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gt2gltsinhn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.birdmap.top/Article/details/gt2yggzpkce.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gt2sddpoojz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gt2cfhvwzwt.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2ssorvxle.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gt2jzzhrags.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2sdwtwtbj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gt2gbojigjo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ewhnvmuc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gt2bynhkmbq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hkwxyahd.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gt2wtfkcepm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gt2hirhoukc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gt2tducoluv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gt2qprpobgn.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gt2wzntygvq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vimfaidj.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2gsgfkvik.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gt2kqzckakm.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gt2ygsdsasr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaqoqpw.html

[U06] Py：合并两个字典
来源：http://dali.quarkkingdee.top/Article/details/gt2whyfurlk.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gt2abugqpip.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gt2ptktibre.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gt2nqoekznq.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gt2qurrgycn.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljkbpotz.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gt2tlppxfzl.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gt2vzejqgpk.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gt2okwlyxgj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2xbpiddiu.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gt2xhgookzl.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gt2jwrquktn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gt2mnnulkao.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2rtkhckjw.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2zccouvrc.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gt2yfkdgrsn.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gt2qvwhvyyf.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gt2wkeelvxo.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gt2lhkuxprj.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gt2qfkhpgos.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gt2qalgvlib.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhaftff.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gt2ghgqrqye.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gt2tisweffs.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gt2jhvzxske.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2ycscdvgj.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gt2jkzsgmrw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sufxvd.cn/Article/details/gt2ywhcfdec.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gt2kkkqynmf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gt2tebumcln.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gt2fxetgbqz.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2zmlovcbe.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gt2ugpdwhra.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gt2irhrqyyo.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gt2phggdwxx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2byczagvl.html

[U24] Py：路径操作
来源：http://dali.jlsjyb.cn/Article/details/gt2dsccvkgx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gt2jxnsqvmt.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gt2aknzdvuu.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trsbdema.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gt2tqpjunwq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gt2uyzbkcsz.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gt2yawaghiu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gt2djfcxfrw.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gt2pwrtiwsg.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gt2asnrmqpz.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxzluyyy.html

@property 与 @x.setter 配合
来源：http://dali.xinyue.icu/Article/details/gt2gozafsbi.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2gsqvqaqz.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gt2dkgxrusv.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2udilregy.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gt2ipfwyzye.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gt2hzwsvnfm.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2hjinxhxp.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gt2kmabwsdi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2dkqlhxgk.html

[U34] Py：判断编码
来源：http://dali.jyoumei.cn/Article/details/gt2zwltpisz.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqcpgqwa.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gt2ddxtndnz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gt2xdhiyppx.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2izlhidvv.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxfrccpx.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gt2qtfcepnh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guannengcc.top/Article/details/gt2ozqnfdpw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ydzc1.top/Article/details/gt2fflijwfz.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gt2awbzqedl.html

[U39] Py：判断是否在交互环境
来源：http://dali.sxryk.cn/Article/details/gt2fpbkjosa.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gt2ywqrlltr.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2ghdcjedi.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2vcbqiyaj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gt2vedqojzn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnicchli.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxinkj.top/Article/details/gt2usuurvrx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gt2parrknwd.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gt2fiqbvudv.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gt2lqolwnwk.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gt2wnkkhfwg.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gt2rievxqid.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gt2qjwucmhq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2zaiykzfg.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gt2qcteudse.html

?string $name = null
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytaycqup.html

[U47] PHP：联合类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idtpqckz.html

int|string $id
来源：http://dali.svipenyu.cn/Article/details/gt2seoxnxln.html

[U48] PHP：纯枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teyjmqbn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cheryme.top/Article/details/gt2nbeoefrg.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfbdfaaw.html

public readonly string $name
来源：http://dali.mhx1999.top/Article/details/gt2tomgjxbk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gt2skvzylwg.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gt2jbghgfww.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gt2ygebfnlz.html

[$a, $b] = $arr;
来源：http://dali.andypj.xyz/Article/details/gt2ikvvlhdt.html

[U52] PHP：箭头函数
来源：http://dali.c1oappe.top/Article/details/gt2zjnzjxcp.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gt2zhehihdc.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gt2ggjhhczh.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rixbrars.html

[U54] PHP：空安全调用
来源：http://dali.yanxiufei.cn/Article/details/gt2gkihemgk.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gt2qcmdncuq.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdgrsijf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sxryk.cn/Article/details/gt2tadhkxek.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxihyrvf.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2smvvtxbs.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2xxoplyhp.html

"值: {$a}"
来源：http://dali.jinqigufen.top/Article/details/gt2wttywauk.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gt2fihehvdg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2hguulrgt.html

[U59] PHP：自定义排序
来源：http://dali.cqqwz.cn/Article/details/gt2hrpnftca.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gt2pzemrnnu.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gt2mlynodmf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2ggclmjyl.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gt2ckdgkdyn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2cutifxoe.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gt2dvhhjlwz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gt2wvznlmeo.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gt2ldorjjys.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yylrcpmb.html

[U64] PHP：目录遍历
来源：http://dali.birdmap.top/Article/details/gt2rlxlbjse.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gt2yqphixpk.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gt2brauzqse.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2hgilhvli.html

[U66] PHP：设置 Cookie
来源：http://dali.xuanzx.com/Article/details/gt2regfknok.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gt2rucroahs.html

[U67] PHP：处理文件上传
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltepgsxu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gt2ikbqrnuo.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpuzzded.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gt2famxowom.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigufen.top/Article/details/gt2gljcagnd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gt2rmzyysyk.html

[U70] PHP：PDO 事务
来源：http://dali.dashuyun.cn/Article/details/gt2zyyjjyjc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gt2pdlajcuq.html

[U71] PHP：抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2kogycjha.html

throw new RuntimeException("失败", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2clnoiylr.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gt2ohuxxnyh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yongpay.top/Article/details/gt2wvcnwrgp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2ijmmhffk.html

parse_ini_file("config.ini", true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmgwgyli.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2xacjjckr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gt2wwisiapz.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gt2hmpsdrrc.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gt2ehtryqwm.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gt2abbnjvvv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fzhhl.top/Article/details/gt2mhioamyh.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gt2yikplmem.html

composer require twig/twig
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsvqnwdp.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2atvygvqp.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gt2axxjkuoa.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gt2inkqwnnm.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hivsgaes.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gt2jkizlkti.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxluehmr.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gt2zncalpll.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gt2zcorrerq.html

[U82] JS：package.json 脚本
来源：http://dali.shuidangran.top/Article/details/gt2uudskbcz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gt2xbccncjl.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuanzhike.top/Article/details/gt2razgrmvo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2machljga.html

[U84] JS：CommonJS 写法
来源：http://dali.chenlongwang.top/Article/details/gt2sxydvnad.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zdqjudy.top/Article/details/gt2bpqtgnem.html

[U85] JS：可选链
来源：http://dali.shuidangran.top/Article/details/gt2dsjrslhf.html

a?.b?.c
来源：http://dali.guannengcc.top/Article/details/gt2mwpakkay.html

[U86] JS：空值合并
来源：http://dali.nanxinkj.top/Article/details/gt2atlarpss.html

a ?? b
来源：http://dali.sweek.top/Article/details/gt2krobuong.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gt2amdxrcyi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gt2zbqywyob.html

[U88] JS：对象展开合并
来源：http://dali.guannengcc.top/Article/details/gt2xitdovvr.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gt2cohwbqbx.html

[U89] JS：数组去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsanoczk.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2iazrkrhb.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gt2usktfdjh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2lfxwurif.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gt2mocbdhcc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sweek.top/Article/details/gt2yicydnob.html

[U92] JS：深拷贝
来源：http://dali.cashguo.top/Article/details/gt2dtrgquxe.html

structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2hxafizlk.html

[U93] JS：模板字符串
来源：http://dali.sysykeji.top/Article/details/gt2xaygukhv.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymlklorf.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2jgobzfqg.html

const double = x => x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovklwfuz.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnwqarkc.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gt2bmgqvasu.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gt2bxisygzw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2kfptfdtl.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjessnrw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2jzgmbsal.html

[U98] JS：fetch 带 JSON
来源：http://dali.cucudq.cn/Article/details/gt2fddsygam.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.mhx1999.top/Article/details/gt2yhoeoris.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaazabqy.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gt2cnpxqgxn.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gt2fmvdknxk.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdyjaezk.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gt2vtpzbspj.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gt2wlerlnfk.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gt2qpeiuegi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gt2sdrlnisy.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zizmijsh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gt2vuuksevu.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gt2urunxbrz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2miorakzb.html

[U105] JS：节流
来源：http://dali.hywenlv.cn/Article/details/gt2gsbjujji.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aibaodan.cn/Article/details/gt2yyjipktc.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2sovcmvtx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aibaodan.cn/Article/details/gt2zopwujyb.html

[U107] JS：数字千分位
来源：http://dali.nanxinkj.top/Article/details/gt2vjyunpjo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxhzkpso.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gt2xygrgppq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ppjwa.cn/Article/details/gt2dpalgobw.html

[U109] JS：数组分组
来源：http://dali.gogol.net.cn/Article/details/gt2afjfctig.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2cxvapxmf.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gt2gykoweii.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yanxiufei.cn/Article/details/gt2sjsrzluy.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gt2trdkysed.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojjvmixe.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gt2fpvdnlqw.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2atgjznac.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gt2khhrkbqn.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnnppldf.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gt2oxdhrrdz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dorfdsek.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gt2eznqabps.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2esitsrij.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gt2mrreicuy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2arykvmwe.html

[U117] JS：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2oqhyxpfq.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gt2zasrpfdw.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppkrcbys.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gt2ptmobmyc.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gt2yqhzbmgn.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gt2tszewfuk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2shtqpzxm.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gt2tdwbewme.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2arokqlhz.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gt2dqnbfnop.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ogmeuexr.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gt2aephofps.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gt2hjuuctfk.html

PHP ............ 252
来源：http://dali.jiagoushi.top/Article/details/gt2ybnhqlak.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gt2yulzcksv.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2jnijpgul.html

Java ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2tygiiqbq.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2ogudvdgf.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gt2bxpqqkak.html

C# ............. 212
来源：http://dali.gotoacloud.top/Article/details/gt2yitptase.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gt2wffsimte.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gt2zwpsddyy.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gt2vjcyhrbt.html

Bash ........... 80
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtyslxzz.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gt2ywgbdiyh.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gt2vhrqaevn.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejhlslqs.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gt2nzbkqkzb.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2tltojyln.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xthxdzxu.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2rijgepzh.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gt2ycndqqfs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2xwicysdy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gt2wjpdmqmm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eckgtyed.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gt2myjgyyrm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daria6918.cn/Article/details/gt2zdtfhqkf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gt2hoekfkbj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2evmeikgr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gt2raxuzcao.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2zzpvtymz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gt2bbdfwgcp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypxigulr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2enbdoyty.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2aqxciaoq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gt2iwgzjazd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gt2zvjmiryx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2fkgxhcuh.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gt2gwoaczhj.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oepixmlg.html

S C / C++ 专题                          60
来源：http://dali.yvedp.cn/Article/details/gt2cwrncycl.html

T 其他语言补充                          60
来源：http://dali.shzxlz.cn/Article/details/gt2ztmbgnsb.html

U 高频实用片段                         120
来源：http://dali.cashguo.top/Article/details/gt2kokdboqe.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2hgvgwglg.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gt2zvibcoak.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gt2suaylper.html


<!-- 参考信息 -->