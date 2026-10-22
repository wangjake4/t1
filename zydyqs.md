代发 wailian999

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2yikifvms.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebmrmhrv.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2soshhsvn.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqhremaz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2vxfpiwwr.html

[T55] Scala：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gt2akwthxnx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gt2meuunpaq.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gt2avxfggri.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2mpjygmwq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qysjnxmm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gt2llgyigbx.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gt2gddpketz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gt2umprlqxb.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gt2qfwyjsxs.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2wmeamqmd.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gt2vysfylfd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gt2ygfhwadl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2tvwlsyun.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2nhldiwpa.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2aopbahai.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gt2ayjdzehl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gt2xninruwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2lacipoyo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gt2ynqmefiz.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gt2tygujuvu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gt2fupdszjs.html

[U04] Py：变量调试打印
来源：http://dali.vqdsnc.cn/Article/details/gt2bjlgznnb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gt2rjdpslzu.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gt2toakkxwi.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhhvplep.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gt2mrbyihtn.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gt2pekomqnc.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gt2iqhfbshy.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivtcxoas.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gt2ibjgzwdl.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2crmdclsk.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gt2izqiiefu.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gt2lfkwwwjn.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gt2wrsdnglk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gt2gcurkxhq.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gt2wlwpjnei.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gt2xainqgyt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gt2zciptflx.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gt2xmzencey.html

[U13] Py：固定长度队列
来源：http://dali.daxiang520.top/Article/details/gt2iielucxb.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gt2ozzrswzh.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gt2pjsyfufc.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gt2lhrvxtyi.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mieygnpz.html

t = time.perf_counter()
来源：http://dali.haohaochexian.top/Article/details/gt2szcqpufu.html

[U16] Py：命令行参数解析
来源：http://dali.aibaodan.cn/Article/details/gt2pizkpsog.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yanxiufei.cn/Article/details/gt2mvgrgevj.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gt2qympvtch.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndcnzeod.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gt2lmailnow.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckuaquwo.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gt2pfmmwdva.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgfzy.top/Article/details/gt2ozopciit.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzzpfnkz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gt2ciifiwsk.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258.top/Article/details/gt2ljwxtean.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gt2qfpypofe.html

[U22] Py：矩阵转置
来源：http://dali.chenzaomai.com/Article/details/gt2ypvfulpj.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gt2abtelfmk.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gt2veumjgnt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gt2zoruhncq.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gt2ddlpknoa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2ezmuqshf.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gt2ukxhwytk.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkcrclsi.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gt2hzvwdiku.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gt2lfcjusjz.html

[U27] Py：异步 HTTP
来源：http://dali.nanxuanxn.top/Article/details/gt2qwjpcikx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gt2laynxmau.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgqwksku.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvpnzypa.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2dekxhpet.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gt2ocwhpkle.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gt2hpokzrkg.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gt2dpkawqap.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gt2zydaxgsm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoylobx.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gt2hszmammx.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gt2svjzoxdn.html

[U33] Py：打包发布
来源：http://dali.tanke756.top/Article/details/gt2sdkdkhyq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gt2jtqvkkvq.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gt2nzzoczlx.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gt2lhqtjrzs.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gt2fymhoelu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxuanxn.top/Article/details/gt2bknamkbl.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gt2wqaecsme.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydcecevj.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gt2tucigtqz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.birdmap.top/Article/details/gt2rrceyjvy.html

[U38] Py：获取脚本所在目录
来源：http://dali.9152youxi.cn/Article/details/gt2htgtbqsb.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gt2xywnntso.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gt2loyaswmj.html

sys.stdout.isatty()
来源：http://dali.ivvv.top/Article/details/gt2cpjlnpau.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gt2vwycooqi.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2qgohcmbd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gt2sgvsolyq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gt2qnmrhutc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gt2njnrwaqi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gt2xjaxvkgr.html

[U43] PHP：声明命名空间
来源：http://dali.hfpthk.cn/Article/details/gt2lfldjcrp.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gt2xqqhhqdu.html

[U44] PHP：开启严格类型
来源：http://dali.shuidangran.top/Article/details/gt2sljgxalb.html

declare(strict_types=1);
来源：http://dali.haohaochexian.top/Article/details/gt2wmjhyjwu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gt2qglpzyhj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2ezvjolgk.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gt2eyfuauoh.html

?string $name = null
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnuiusff.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gt2sqklsejx.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gt2bjjdzmeg.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gt2jeslhxks.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrtkngep.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gt2odlipeny.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gt2waucvuva.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gt2wpjazwhs.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gt2stjjqgho.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gt2onxobvrr.html

[$a, $b] = $arr;
来源：http://dali.jiagoushi.top/Article/details/gt2rmouxkqi.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gt2gomkmdrr.html

$double = fn($x) => $x * 2;
来源：http://dali.cqqwz.cn/Article/details/gt2lcovybul.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gt2uctpfgvy.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gt2dphtocqq.html

[U54] PHP：空安全调用
来源：http://dali.gaohongyu789.top/Article/details/gt2sekcarcw.html

$obj?->method()
来源：http://dali.cucudq.cn/Article/details/gt2aqronywj.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2vfogsdbf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gt2iklekafy.html

[U56] PHP：命名参数
来源：http://dali.fengsongda.top/Article/details/gt2lvwrxghe.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2jagzzoth.html

[U57] PHP：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2ojwfbodn.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gt2gbjvaloa.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gt2ltvlhfkx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2lvziufdo.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gt2fuqejqqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gt2hvjdqkel.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dojibayg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dianchejie.cn/Article/details/gt2xpqsrfux.html

[U61] PHP：正则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvbqlaqe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2dcxighyl.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmubfmrb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ppjwa.cn/Article/details/gt2jlylhgeg.html

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gt2cmcrsnhm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gt2tabgjwel.html

[U64] PHP：目录遍历
来源：http://dali.redwolf501.top/Article/details/gt2vueivekr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gt2opukbujh.html

[U65] PHP：会话
来源：http://dali.aizwys.cn/Article/details/gt2bdwyblgf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2wqiaaxgc.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258.top/Article/details/gt2nkilugdu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucdjsncr.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gt2amxqiagm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xziqi.cn/Article/details/gt2bjmumtwh.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gt2qfegiapl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nwbrower.top/Article/details/gt2eujgssqx.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gt2pzufqwpa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.316326.xyz/Article/details/gt2iafnjolt.html

[U70] PHP：PDO 事务
来源：http://dali.gotoacloud.top/Article/details/gt2fmbzalcs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daria6918.cn/Article/details/gt2fosifpov.html

[U71] PHP：抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2ypajjkwr.html

throw new RuntimeException("失败", 500);
来源：http://dali.meibo888.top/Article/details/gt2lrhzulut.html

[U72] PHP：写错误日志
来源：http://dali.daxiang520.top/Article/details/gt2qudtaust.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258888.top/Article/details/gt2wsogwyyz.html

[U73] PHP：读取 ini 配置
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdateajz.html

parse_ini_file("config.ini", true)
来源：http://dali.sweek.top/Article/details/gt2rdcpghfu.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2ydewjxvk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwcccots.html

[U75] PHP：依赖注入
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqurpggi.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gt2lebkrqyo.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gt2rjmcogph.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jianghu66.top/Article/details/gt2crfrxcfj.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gt2fndackbu.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gt2vztksnlc.html

[U78] PHP：单元测试
来源：http://dali.gzhubu.top/Article/details/gt2eiilqwnn.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gt2psycslvb.html

[U79] PHP：静态分析
来源：http://dali.shuidangran.top/Article/details/gt2rmafnjzi.html

composer require --dev phpstan/phpstan
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fubfpgnm.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvwdibdc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gt2lupzgqlp.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gt2uzugawjv.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gt2emgwunzh.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gt2wvetirkg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wilhsyfu.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gt2pmifmxmb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gt2ipjmdazv.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gt2ugaefuro.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.haohaochexian.top/Article/details/gt2eeyjtkke.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gt2djwefpbi.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gt2rbnziuzg.html

[U86] JS：空值合并
来源：http://dali.jqgufenzy.top/Article/details/gt2bvdtghvp.html

a ?? b
来源：http://dali.tianlin.xyz/Article/details/gt2qbmgscug.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gt2esppyykn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nwbrower.top/Article/details/gt2vlfqihcu.html

[U88] JS：对象展开合并
来源：http://dali.guowangkeji.top/Article/details/gt2tslycrdk.html

{ ...a, ...b }
来源：http://dali.zhengqikj.top/Article/details/gt2vslmkylh.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gt2csdbprlz.html

[...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvcjmkyq.html

[U90] JS：数字数组排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efscqyre.html

[...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2zrwbcihy.html

[U91] JS：对象键值遍历
来源：http://dali.xinyue.icu/Article/details/gt2exnvwoyt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgrmxour.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2wwgnagpc.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2tcnuvpil.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkyrmbya.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gt2qfsotzuu.html

[U94] JS：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gt2rtghathx.html

const double = x => x * 2;
来源：http://dali.jinqigufen.top/Article/details/gt2aawqdeml.html

[U95] JS：Promise 包装
来源：http://dali.xuanzx.com/Article/details/gt2uivnzjxg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gt2qdhmpksh.html

[U96] JS：async/await 与异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjzprkcb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2ishtgpui.html

[U97] JS：并发请求
来源：http://dali.nwbrower.top/Article/details/gt2eudsnney.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmjpkkqi.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2twcmbptf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjyleznj.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gt2ldwvckiq.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gt2qvlnjvmi.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlxgnfrx.html

document.querySelector(".item")
来源：http://dali.jiagoushi.top/Article/details/gt2umegltgs.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gt2nwnsvozl.html

el.classList.toggle("active")
来源：http://dali.shzxlz.cn/Article/details/gt2tvjufdre.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gt2ehmeuykh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gt2ryrjryjm.html

[U103] JS：定时器
来源：http://dali.chenzaomai.com/Article/details/gt2nlbomssa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2homklylj.html

[U104] JS：防抖
来源：http://dali.gotoacloud.top/Article/details/gt2ygmqcfnt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2ybucetuw.html

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gt2wqnoxqdi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gt2hwjcyder.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2ytetywja.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gt2qjbptoow.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gt2jriealub.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2blfanotu.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gt2tqmjadzs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuxming.cn/Article/details/gt2adfczbhr.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gt2hhiaplem.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gt2uvwdljdy.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gt2nouikdud.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.0kj1m.cn/Article/details/gt2qloheasi.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gt2qkvldfas.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2xpagvysx.html

[U112] JS：字符串补位
来源：http://dali.yanxiufei.cn/Article/details/gt2uuhuobws.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2ajoaqhei.html

[U113] JS：正则替换全部
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzxiubfn.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2uyoodeeu.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2sfixpidz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2iwkioqky.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2hzhskwym.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2jhwprnyk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gt2bpqstkkn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fumlluzt.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2ffriakod.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gt2jlunaxft.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gt2sdnszltt.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gt2btrjmjgb.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcswiykc.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gt2mlrbigxi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hfpthk.cn/Article/details/gt2pjhnaqzf.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gt2byxpjzkj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2nagovsyb.html

统计汇总
来源：http://dali.zhongyouzk.top/Article/details/gt2toxcjozv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2qkcqjcts.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ieajhhck.html

Python ......... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pozhnwvv.html

PHP ............ 252
来源：http://dali.daxiang520.top/Article/details/gt2mplwmcvf.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gt2hrtgdjtl.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gt2szpsotgu.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gt2jaemtpve.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwjzznki.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gt2iszlxngx.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2nqywfphd.html

C .............. 30
来源：http://dali.jianghu66.top/Article/details/gt2rgfnnaoz.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gt2ypxhylkg.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gt2scehfmvp.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzxdwlaq.html

Kotlin ......... 15
来源：http://dali.gogol.net.cn/Article/details/gt2foawvmll.html

Swift .......... 15
来源：http://dali.guowangkeji.top/Article/details/gt2gmlufcxu.html

Lua ............ 10
来源：http://dali.mhx1999.top/Article/details/gt2bhfvhung.html

Perl ........... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmsocyhz.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gt2lzdvvpgf.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2ctfbtmet.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gt2yopftwja.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gt2oofpsizi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gt2hkbvgkoz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gt2ewzvlfen.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2rulehsyi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2payjgxmi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gt2anjqgygx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gt2ridmcmfi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gt2mxxcuhaq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndlofbvs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2uvmsdmhq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2wfprshnc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2lordgxvc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2gcyulzsi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2znmgqdmv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxoeqczy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fywycfwp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2utwxggjq.html


<!-- 参考信息 -->