代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gt2redczbrx.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gt2qpisbave.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gt2kumawhnj.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gt2bwcqffeq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruipehmz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hpksgazl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2cesniwgn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ddgdqyql.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2oxhmyale.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gt2httsxubw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gt2etzslxan.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gt2chrdegvq.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2wngssrif.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gt2afycafme.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gt2zxspsuvf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gt2bhkpycgy.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gt2lsjfaudv.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2bgjalcia.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gt2gqmvldqg.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gt2owqpmueg.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gt2boiwbpht.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gt2segeyxbz.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gt2rgpnygwf.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gt2fkpnpgzv.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gt2eizcxyqb.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gt2cycvmrzx.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gt2umhshpny.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aibaodan.cn/Article/details/gt2yidedwzq.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uikuqboj.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gt2uxkjkfgy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gt2hbhfbulp.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gt2npybapgl.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gt2uaxkqnbk.html

deque(maxlen=10)
来源：http://dali.xuanzx.com/Article/details/gt2uvxydhgj.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gt2fuxjdauv.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gt2cirmayye.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gt2xvkrbbjr.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gt2qkmhofoe.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwktgpfp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gt2hhkdfiqb.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gt2ouwnlqxh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hywenlv.cn/Article/details/gt2cwygoghk.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bndbduov.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2eztwdydm.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfnyesbs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gt2qyjzroun.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmttccox.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gt2ttboochy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gt2ucdpgtba.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gt2peiwsfhi.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gt2dtnhcghk.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gt2omhkaqsu.html

[U23] Py：分块读取大文件
来源：http://dali.cashguo.top/Article/details/gt2flmxtuem.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangdashe.top/Article/details/gt2specyiyo.html

[U24] Py：路径操作
来源：http://dali.yj20258888.top/Article/details/gt2cgpkbpdn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2qnlnhbkq.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzyxtesd.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zguczrmu.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gt2jzhmxikx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gt2oayaffrs.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gt2oddoblnt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yanxiufei.cn/Article/details/gt2ijqdadrz.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gt2gthfttgf.html

UserId = int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rewczxgk.html

[U29] Py：属性校验
来源：http://dali.hammf.cn/Article/details/gt2cqzvyxpb.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gt2lzemoiio.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gt2citehwzq.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gt2lszsqihu.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gt2nmjxcgfj.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjcjjkfa.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gt2hdzkffkd.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gt2cmsgyvia.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gt2qxuhtwms.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daria6918.cn/Article/details/gt2picvvnrs.html

[U34] Py：判断编码
来源：http://dali.mhx1999.top/Article/details/gt2blpthonx.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gt2iwclqmjs.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gt2imvspmys.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gt2kxlqmdfk.html

[U36] Py：定时任务
来源：http://dali.kuanghao11.cn/Article/details/gt2gnafmstn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqdpbzlc.html

[U37] Py：读写 Excel
来源：http://dali.gaohongyu789.top/Article/details/gt2idekprwn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuanzx.com/Article/details/gt2rcjldozd.html

[U38] Py：获取脚本所在目录
来源：http://dali.0kj1m.cn/Article/details/gt2wihskhva.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gt2huscdpfy.html

[U39] Py：判断是否在交互环境
来源：http://dali.fzhhl.top/Article/details/gt2nepdnlfs.html

sys.stdout.isatty()
来源：http://dali.sweek.top/Article/details/gt2ulfujvox.html

[U40] Py：打印到标准错误
来源：http://dali.hnxiangtu.top/Article/details/gt2fteaqihm.html

print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2qoexjjbv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gt2qrhgiesd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dianchejie.cn/Article/details/gt2jzxgqukg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gt2warsewol.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gt2otjneohm.html

[U43] PHP：声明命名空间
来源：http://dali.sweek.top/Article/details/gt2tfutacts.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gt2qecmpgpa.html

[U44] PHP：开启严格类型
来源：http://dali.tianlin.xyz/Article/details/gt2dnfaqakj.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gt2xxdxexvs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yanxiufei.cn/Article/details/gt2bxmkaqzq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2axtvkulg.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gt2rsxyfzuo.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmusvymi.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gt2vneqxjle.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gt2ngkiehpx.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gt2zcjosilp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gt2mwdhwcxn.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gt2jiwrzwlh.html

public readonly string $name
来源：http://dali.guowangkeji.top/Article/details/gt2qfdljelg.html

[U50] PHP：构造器属性提升
来源：http://dali.dashuyun.cn/Article/details/gt2bzdwrgbl.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gt2chibupsu.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gt2yiivxfns.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbdhsjbz.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gt2wgledexr.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnezfpuf.html

[U53] PHP：空合并运算符
来源：http://dali.snrcjt.cn/Article/details/gt2gsrnewtc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifrpaesp.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gt2fdvlszzh.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gt2otkdvcwa.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gt2bfjikbil.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gt2hrrrvugt.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gt2nvzqrbhj.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2anxutyrv.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwxyddas.html

"值: {$a}"
来源：http://dali.hywenlv.cn/Article/details/gt2ypyhfjiu.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gt2ikiogfba.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2htkfopiw.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gt2avydkyfl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gt2zkwojgij.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gt2feuksaav.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gt2gzpypfeu.html

[U61] PHP：正则
来源：http://dali.yuxming.cn/Article/details/gt2qxgiiles.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2lhrzhwcq.html

[U62] PHP：日期对象
来源：http://dali.aibaodan.cn/Article/details/gt2cpcllgdb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cqqwz.cn/Article/details/gt2fjxxhlsd.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gt2qylaputv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gt2mszvoznh.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gt2fwzrdoyx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdojalxy.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gt2xwxpcuso.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2pldrakjv.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gt2mpmvfnwb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkxxddcq.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gt2mtomesyc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gt2cjlabntb.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gt2ylpnaqdp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhnsblot.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjipjfqw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gt2yxbohebc.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gt2ltdpzeht.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj202588.top/Article/details/gt2bcendver.html

[U71] PHP：抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2rlpzhosc.html

throw new RuntimeException("失败", 500);
来源：http://dali.shuidangran.top/Article/details/gt2zmiimydy.html

[U72] PHP：写错误日志
来源：http://dali.nwbrower.top/Article/details/gt2nxpotlbf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yongpay.top/Article/details/gt2xcacxeye.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gt2cvnlupjs.html

parse_ini_file("config.ini", true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbkcpmry.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2hbkmloyv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gt2ziyqhbra.html

[U75] PHP：依赖注入
来源：http://dali.sysykeji.top/Article/details/gt2wdykbugq.html

composer require psr/container
来源：http://dali.316326.xyz/Article/details/gt2xetarvyj.html

[U76] PHP：简单路由
来源：http://dali.pycfn.com/Article/details/gt2roxcjttf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gt2xxuymaef.html

[U77] PHP：模板渲染
来源：http://dali.ybcxt.top/Article/details/gt2qwsddjuv.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gt2mpdlhaxi.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejvhmpnr.html

composer require --dev phpunit/phpunit
来源：http://dali.0kj1m.cn/Article/details/gt2rruqxfrz.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gt2fdkhuvor.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gt2seiqlpos.html

[U80] PHP：代码规范修复
来源：http://dali.ivvv.top/Article/details/gt2hjvpxbkd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gt2qmpvwmlb.html

[U81] JS：初始化项目
来源：http://dali.ehwqpu.com/Article/details/gt2dicukbnm.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elfwdtdx.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gt2tisjmvgl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gt2ydhlgklh.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxlmlrku.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gt2fbmgorzr.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tirlvqft.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdvmerce.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gt2jpwhxgia.html

a?.b?.c
来源：http://dali.mhx1999.top/Article/details/gt2oxhzgebm.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gt2ekhcktvw.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gt2zlfpwmzp.html

[U87] JS：解构默认值
来源：http://dali.daxiang520.top/Article/details/gt2xqgokqvp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gt2ocalhqfi.html

[U88] JS：对象展开合并
来源：http://dali.meibo888.top/Article/details/gt2lownirag.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gt2ajthcpfh.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwtbgzza.html

[...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2sywdyvqb.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gt2gqriawpf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2hznykeku.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gt2togqsxuh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gt2damhosyk.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2nxemfyqw.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrlmdytf.html

[U93] JS：模板字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2oiiduvew.html

`共 ${n} 条`
来源：http://dali.shangyingyoupin.top/Article/details/gt2apbvhgli.html

[U94] JS：箭头函数
来源：http://dali.sweek.top/Article/details/gt2svcnfqqe.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gt2emrckzyl.html

[U95] JS：Promise 包装
来源：http://dali.zhoulong.xyz/Article/details/gt2giwceppm.html

new Promise((resolve, reject) => {})
来源：http://dali.snrcjt.cn/Article/details/gt2mbslyvpo.html

[U96] JS：async/await 与异常
来源：http://dali.sufxvd.cn/Article/details/gt2lqgbkwnq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2okpjcylp.html

[U97] JS：并发请求
来源：http://dali.fengsongda.top/Article/details/gt2ewiogbdq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2djrwegtq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2seghkqyk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gt2fbpbjxsp.html

[U99] JS：事件监听
来源：http://dali.daxiang520.top/Article/details/gt2butguvrm.html

el.addEventListener("click", e => {})
来源：http://dali.316326.xyz/Article/details/gt2axbqcvee.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gt2byoiqefy.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gt2oynxbuxy.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gt2muqectxn.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gt2arxbterg.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gt2ynjcyhrm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gt2pgqtqgvy.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gt2xugwgyzu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gt2veqyjhru.html

[U104] JS：防抖
来源：http://dali.zhongyouzk.top/Article/details/gt2wysdlues.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2wgtjnalq.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gt2wlijkgsn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxinkj.top/Article/details/gt2ryklvemj.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2ejptgegq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gt2zoxwujqb.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2ljwofmvl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258.top/Article/details/gt2gxgboolu.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayoaegkp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gt2rvobumvi.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gt2ogtknvtg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gt2wdsapurf.html

[U110] JS：数组分块
来源：http://dali.hammf.cn/Article/details/gt2evegauih.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gt2utqjepeb.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gt2bafyvezo.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gt2ktxkmggo.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gt2yfegqvyl.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2bestpzll.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gt2tshrkzza.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jczfxrvm.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gt2mocmsgux.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2drynqgtr.html

[U115] JS：生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gt2umpdbbbh.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2acjybkpq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gt2qnmwbbjl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gt2uneqhctf.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gt2vlqlzrzq.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gt2ohujhace.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gt2dleccsny.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gt2yxqnrplp.html

[U119] JS：生产构建
来源：http://dali.aibaodan.cn/Article/details/gt2gqiwnpna.html

npx vite build
来源：http://dali.sysykeji.top/Article/details/gt2nmvfzmdi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gt2hxgphpon.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gt2uemrxlcg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ybtsjgju.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gt2pnkiunbt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2crqibtfn.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gt2klbspwhw.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gt2pjcvkexm.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gt2wbshnshq.html

JavaScript ..... 252
来源：http://dali.0kj1m.cn/Article/details/gt2ukahusaq.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gt2pqbneowk.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrtqkaln.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oiyropsm.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qeobvwyu.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gt2cbjwfmva.html

C .............. 30
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwslafqg.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gt2vhacfovk.html

SQL ............ 90
来源：http://dali.yueranfly.top/Article/details/gt2doclkxid.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gt2hvjsptlv.html

Kotlin ......... 15
来源：http://dali.andypj.xyz/Article/details/gt2mhiiwwqp.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gt2cnedzgwr.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gt2gplbdrfd.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gt2iyezoewa.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gt2zjqzsnhv.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2adxutoga.html

合计 ........... 2106 条
来源：http://dali.gzhubu.top/Article/details/gt2gvaufiqw.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gt2ldjqdooq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gt2oqxobetp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gt2deopocan.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2pbidwkgv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2ylxzolqg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258888.top/Article/details/gt2chxpzbom.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2wauzhwzr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gt2xrwqoutb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2oeaefyzc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2babtglby.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gt2ppffetmn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2juhncbir.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2xfdalvcv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2jwgcirzs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gt2nhcjrnsy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sufxvd.cn/Article/details/gt2jcyltyqd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2ysvlmury.html

Q SQL 专题                              90
来源：http://dali.shzxlz.cn/Article/details/gt2uzajhcxt.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gt2jsxomdig.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gt2uhpfwqlr.html

T 其他语言补充                          60
来源：http://dali.cqqwz.cn/Article/details/gt2bjjkgzqd.html

U 高频实用片段                         120
来源：http://dali.haohaochexian.top/Article/details/gt2qxczgkmz.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2ncvgbcjn.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2puijcygi.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gt2umbdwfdt.html

使用提醒
来源：http://dali.wangdashe.top/Article/details/gt2fklgftjw.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2sjblqjwm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenlongwang.top/Article/details/gt2dgvlmuwv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenzaomai.com/Article/details/gt2vhuizrrv.html


<!-- 参考信息 -->