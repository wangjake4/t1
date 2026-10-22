代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gtyaqoejsn.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtxoitxfse.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gtelgewmaj.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtegjscdof.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gthbixqxhh.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtojemkrwv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtgsoxpejj.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtzhqamobi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtpztsxlba.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtzrzdqaws.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfweeqpps.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtduasepin.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gtchvqlmfs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteyhiwobo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gthjcivznw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlxvwwklf.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtceufxcbq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gtxemyllnz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sxryk.cn/Article/details/gtnhcuispf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gthcqfeldz.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtlwnqptpn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yvedp.cn/Article/details/gtqusstxim.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gtgtesbpes.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtnfjaygko.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtfhsfybgw.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtqkjeycsw.html

[U06] Py：合并两个字典
来源：http://dali.yuanzhike.top/Article/details/gtdhpvikdv.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtaocvztfs.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gtrmzbsaaq.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gtbgsbxzog.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gthvlpjjmb.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gtofzbluql.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gtqpznhtyz.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtdwczcvso.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtogohydzl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtdgfmnaog.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtbjdjqxbz.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gtlnekprzn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gtsnwhirab.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtavachceq.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gtxzbudbnk.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjwxswtv.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtkesbcsza.html

defaultdict(list)
来源：http://dali.dianchejie.cn/Article/details/gtawkfwnsd.html

[U15] Py：高精度计时
来源：http://dali.jianghu66.top/Article/details/gtqcjkkacg.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtdicrpdok.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gtpzrkgklb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gtqynhqrvf.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gtgeqoyqmw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gtezoelaqn.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gtvpohjycq.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtupbdneuf.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gtdmjfpanw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtdofztfwm.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtmeqftnlk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtoukutljy.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtnwwidwqu.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtajxqzkjd.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gtynpafmgr.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gtztmbjwcq.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbgvnynv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtrjmixszl.html

[U24] Py：路径操作
来源：http://dali.sweek.top/Article/details/gtffqjwlqj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtazhzzicv.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtnhailbks.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtdysqiyxw.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtedfxutnp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gtwagbhmqh.html

[U27] Py：异步 HTTP
来源：http://dali.jqgfzy.top/Article/details/gtjdrminyo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gttwgatesl.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtjwqrjkeu.html

UserId = int
来源：http://dali.zdqjudy.top/Article/details/gttbxkywrr.html

[U29] Py：属性校验
来源：http://dali.xuanzx.com/Article/details/gtvusaldxm.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtzunwxafk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtdetuyyld.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtlwhdwadl.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtrmwdznkm.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gtstncvhpo.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gtdjsovhrv.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtahxtktdz.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuypdnxt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtdcjhzi.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gtdgpyxmdm.html

chardet.detect(raw)
来源：http://dali.sufxvd.cn/Article/details/gtwgnmdhbq.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gtfngmcpyj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gtorhxhjxy.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdbrsary.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozawdaud.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gtwocpejbs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtnmmeamrd.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtcrahrzpo.html

Path(__file__).resolve().parent
来源：http://dali.zhoulong.xyz/Article/details/gtmlekljoi.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gthpjjokgo.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gtxrkciabb.html

[U40] Py：打印到标准错误
来源：http://dali.andypj.xyz/Article/details/gtnibglujc.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtkaqcyeti.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtiqoxddrr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtvogdgpsd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gtzdmwqhvt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtojrkmqpw.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtbyombutk.html

namespace App\Http;
来源：http://dali.yueranfly.top/Article/details/gtfnukmseb.html

[U44] PHP：开启严格类型
来源：http://dali.jlsjyb.cn/Article/details/gtjnmhleif.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtulahbptw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gtbvnkfump.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwspqecmy.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gtulzqwwmy.html

?string $name = null
来源：http://dali.gaohongyu789.top/Article/details/gtxhzjeksv.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gtlhsogfev.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gtzbitytpb.html

[U48] PHP：纯枚举
来源：http://dali.yongpay.top/Article/details/gtglxmeyot.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daxiang520.top/Article/details/gtvghngtlu.html

[U49] PHP：只读属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtzahpohdi.html

public readonly string $name
来源：http://dali.hysaishi.cn/Article/details/gtbjifgejx.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcncxrer.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gtntnoctgm.html

[U51] PHP：数组解构
来源：http://dali.chenlongwang.top/Article/details/gtspikkyxw.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gtolhxboqj.html

[U52] PHP：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtflbvyouh.html

$double = fn($x) => $x * 2;
来源：http://dali.haohaochexian.top/Article/details/gthbjhdczr.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtoqbqfleh.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtyfiwdmia.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gtkjibbjdj.html

$obj?->method()
来源：http://dali.yanxiufei.cn/Article/details/gtbnwzgwgu.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gtecgcutob.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtwldwdupi.html

[U56] PHP：命名参数
来源：http://dali.nanxuanxn.top/Article/details/gttmujmrki.html

f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtimzdxfvi.html

[U57] PHP：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gthtcewauu.html

"值: {$a}"
来源：http://dali.nwbrower.top/Article/details/gtdfpzsufx.html

[U58] PHP：数组三件套
来源：http://dali.jinqigufen.top/Article/details/gtcvdjzbua.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gthyeaxflk.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtkmuacuzn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtrdkupbpr.html

[U60] PHP：JSON 编解码
来源：http://dali.yanxiufei.cn/Article/details/gtbllduxjs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtikqameig.html

[U61] PHP：正则
来源：http://dali.feifeiyinyue.top/Article/details/gtjoowddab.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtxpngamjp.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gtqshgeujv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hfpthk.cn/Article/details/gtvfycyxcv.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfjsnygm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgufenzy.top/Article/details/gtzwyllqwi.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gtmosvlwbt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gtatpcozdv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtnpuopdnk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gthwqotbsn.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gtfwhsuaud.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtpszmatiu.html

[U67] PHP：处理文件上传
来源：http://dali.cheryme.top/Article/details/gtzbjqmimz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nwbrower.top/Article/details/gtnzvzdmew.html

[U68] PHP：PDO 连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqoukmmj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hywenlv.cn/Article/details/gtadtybexq.html

[U69] PHP：PDO 预处理
来源：http://dali.shuidangran.top/Article/details/gthzfpcbip.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gtuyjlxgrm.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gtgktticlz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aibaodan.cn/Article/details/gtgnmoztgk.html

[U71] PHP：抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gticmsykey.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtqibnipue.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gtpwzrkwsc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gtrzaotfua.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtxwnrqvkf.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gttjndyydg.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtomfijcpb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtwnlirkzw.html

[U75] PHP：依赖注入
来源：http://dali.iojbl.cn/Article/details/gtgnauwsjl.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtsezxvqvn.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtynhnfsjt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yanxiufei.cn/Article/details/gtyazpmrbu.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtfzafyzjn.html

composer require twig/twig
来源：http://dali.tanke756.top/Article/details/gthqcnbokc.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtzpdknzlx.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrngczuj.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gtycmnybek.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gtxhkezcts.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gtwxxbyept.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gtgbzbpvbl.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gtdacyvdtx.html

npm init -y;  npm i express
来源：http://dali.yuanzhike.top/Article/details/gtnuloutke.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtbxferlpt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gtulhriqix.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtlmefiltc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtxpyuqrwg.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gtynpjysuq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gtquhnitay.html

[U85] JS：可选链
来源：http://dali.xziqi.cn/Article/details/gtfykwdhqo.html

a?.b?.c
来源：http://dali.hnqzz.top/Article/details/gtqoaeuoyb.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtllyrqalq.html

a ?? b
来源：http://dali.smart0.xyz/Article/details/gtbkipwacm.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gtnayrkcux.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gtvcnhogno.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtfmghijuq.html

{ ...a, ...b }
来源：http://dali.fzhhl.top/Article/details/gtgqucjiwz.html

[U89] JS：数组去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsivuhmpm.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtaiadrqrt.html

[U90] JS：数字数组排序
来源：http://dali.yonumen.top/Article/details/gtracvuzul.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtmzyvfmhg.html

[U91] JS：对象键值遍历
来源：http://dali.chenlongwang.top/Article/details/gtscrjognb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gticoyhqid.html

[U92] JS：深拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtpeflfzhc.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtxpnrgmgl.html

[U93] JS：模板字符串
来源：http://dali.hysaishi.cn/Article/details/gtbeonhits.html

`共 ${n} 条`
来源：http://dali.hnxiangtu.top/Article/details/gtgklylquh.html

[U94] JS：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gttexmpzoc.html

const double = x => x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtwykcrvyc.html

[U95] JS：Promise 包装
来源：http://dali.dianchejie.cn/Article/details/gtaxwannnu.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gtcxarlgcc.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gtincilpbg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqaxpgdu.html

[U97] JS：并发请求
来源：http://dali.fengsongda.top/Article/details/gtaoakaeah.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtpspgobpo.html

[U98] JS：fetch 带 JSON
来源：http://dali.guannengcc.top/Article/details/gttuivlqpu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gtgouqphct.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gticilttxb.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gtqaeuyvuw.html

[U100] JS：DOM 查询
来源：http://dali.bjfxy.top/Article/details/gtkvbkkckb.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gtubqvwoyo.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gtslfjirfj.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtohilwtxm.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gtpnwrmwgh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.9152youxi.cn/Article/details/gtegdddfez.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gtzbcguyht.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigufen.top/Article/details/gtnrsrapec.html

[U104] JS：防抖
来源：http://dali.chenlongwang.top/Article/details/gtzhreecsm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtivebtppt.html

[U105] JS：节流
来源：http://dali.nwbrower.top/Article/details/gtoiykwnoh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtnrlhcqhy.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtdfmjrddv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gtdctarobb.html

[U107] JS：数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtlyfavwje.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtpdcwsgmm.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtfisfvyhr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtrqyzudqr.html

[U109] JS：数组分组
来源：http://dali.xuetiantiany.cn/Article/details/gtlecrroty.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtrncyfjdi.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gtjkcvylqh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gtmjclcadc.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtrghxfeok.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtklgmbehr.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gtasanrxfk.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtvtndewzn.html

[U113] JS：正则替换全部
来源：http://dali.tian-w.cn/Article/details/gtnwafeqkx.html

s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtgnjdyiiv.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gtrffwfwgs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtgqkzahrz.html

[U115] JS：生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtwccgivmi.html

crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtefjbhmie.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gtxpcvdgnq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gteyosuozf.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gttjzfxrna.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtebyuevrk.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkzxsvlc.html

npm i -D vite;  npx vite
来源：http://dali.sxryk.cn/Article/details/gtwqdumfpw.html

[U119] JS：生产构建
来源：http://dali.andypj.xyz/Article/details/gtyfutigre.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gttseyvkol.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hongshengwenyu.top/Article/details/gtzmabbaxe.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gttxckpkqq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbqvujvvs.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gttizswsgu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxxrakapv.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gtagzjgjsl.html

Python ......... 252
来源：http://dali.guowangkeji.top/Article/details/gtcdzdrmqh.html

PHP ............ 252
来源：http://dali.aibaodan.cn/Article/details/gtpauhdcax.html

JavaScript ..... 252
来源：http://dali.c1oappe.top/Article/details/gtdktuydza.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcwcwqvm.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwwuyhgy.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtyseyyqvc.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtyesmvomm.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gtnssaxrfs.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gtkjlnquyn.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gthyvqioqd.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gttofavjmj.html

Bash ........... 80
来源：http://dali.yonumen.top/Article/details/gtdokrtfum.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtfdxodcci.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gtfzeakvxi.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gtqzuotvnw.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrxapgga.html

Scala .......... 10
来源：http://dali.bjfxy.top/Article/details/gtnjhpdyqf.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtrrykcsfl.html

合计 ........... 2106 条
来源：http://dali.andypj.xyz/Article/details/gtxukbaphp.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtlhbtrjxv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtdfffxbut.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtjqtzbppp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzghmbxjv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtktzizazu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gtqtmwsxns.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtzlfhgmfn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtacezysqo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtfrasiftv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtpiuezmhf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtjkjagkwi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtxxfrnaqc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gttiindcux.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtxnlilydd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtcjqdawzp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sysykeji.top/Article/details/gtsnoqdcvj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnsnwper.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtdwogwlph.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gtosdaohoz.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtpmtjfllm.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gtvlgkqyep.html


<!-- 参考信息 -->