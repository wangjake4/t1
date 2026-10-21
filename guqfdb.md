代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gtostjzwdo.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtyetotgae.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtflhmlfje.html

[T60] Scala：折叠
来源：http://dali.snrcjt.cn/Article/details/gtgqncfhhw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtopfmengi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpakrspus.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtcentinsb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrvkedpbh.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtjavhzvwb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gtojdjdwjp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtnhgnpexv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gtydkqmxiy.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gtahgjxogv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gtwxjdcbdc.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtpwtwilgt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtfrcsvajv.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gtdqpwqhej.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gthpgqnsqm.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtbdrzkazj.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gtmqwsncvc.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtqpxafakq.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtuphlnjgg.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtuddpnnzd.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtdbwpneds.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtivddyhev.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtdlhshpqb.html

[U10] Py：按值排序字典
来源：http://dali.bjfxy.top/Article/details/gtkzfypqsy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.0kj1m.cn/Article/details/gtmztwnsmo.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrxkjdgb.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdbrowukk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtiboedxxh.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtukgkpzrw.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtcatnblnw.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gtaihmrgbo.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gthlvuhuui.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtxbmlkkho.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gtmktgmwmz.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtumeucwnx.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gtjujwkzjq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gtukimougs.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gttbjmvqvx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gttuzmtfwf.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtnhobhkbo.html

pat = re.compile(r"\d+")
来源：http://dali.ybcxt.top/Article/details/gtrpstnloo.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gtvjxswuri.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtcxbeqarc.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtyuorgpyl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtmmsmlkew.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gteizgennk.html

@contextlib.contextmanager
来源：http://dali.bjfxy.top/Article/details/gthcytngjz.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gtyckjsnpp.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gtnmwxalca.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtlobjkclh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.smart0.xyz/Article/details/gtnlurljqc.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxfzakhu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtcyqecfvs.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gtluofucll.html

csv.DictReader(f)
来源：http://dali.chenjidiqi.icu/Article/details/gtbrygjqvu.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtqzxruoou.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gtyolnvfsa.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gtfhqwnoqa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gteoasvjvi.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gtymujyaal.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtcbsqglsg.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gtwdavaper.html

@property 与 @x.setter 配合
来源：http://dali.zhengqikj.top/Article/details/gtkimtysfd.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtxjljmvps.html

@dataclass(slots=True)
来源：http://dali.shuidangran.top/Article/details/gtvqhupjft.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gtctxstpcc.html

python -m pytest -q
来源：http://dali.tanke756.top/Article/details/gtylpygcct.html

[U32] Py：代码格式化
来源：http://dali.aibaodan.cn/Article/details/gtuiodhcnn.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gtobrgvqpa.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gtfxqdvcyn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gtdnmisbuz.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gtfezvaflo.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gtpccquobn.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gtvgnhefjo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tian-w.cn/Article/details/gtvanykvoh.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtkyifzpsy.html

schedule.every(10).minutes.do(job)
来源：http://dali.tian-w.cn/Article/details/gtfypoftft.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtyfvamovy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfnzxjoh.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gttywsxzdk.html

Path(__file__).resolve().parent
来源：http://dali.smart0.xyz/Article/details/gtlrddxjhg.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gtvudcmxei.html

sys.stdout.isatty()
来源：http://dali.fengsongda.top/Article/details/gtqnoddqjm.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtawdtedvm.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrjdasqe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gthphfgmvu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gtyjjltyzo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gtznwzmnpa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gtkecxaipk.html

[U43] PHP：声明命名空间
来源：http://dali.zhixingplan.top/Article/details/gthcpsnqhg.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gtrmbdletq.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gtzuphhdua.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gtprbngboo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gtvoknuoga.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtcqfizszf.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gtqnxzhmuo.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gtrwzihzrh.html

[U47] PHP：联合类型
来源：http://dali.jinqigfzy.top/Article/details/gthhgcpgft.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtprtagwsi.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gtomomhnmj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuxming.cn/Article/details/gtbwmhdyqj.html

[U49] PHP：只读属性
来源：http://dali.quarkkingdee.top/Article/details/gtmrxnbmnt.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtsizgufjd.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgfzy.top/Article/details/gtqynklbfh.html

public function __construct(private int $id) {}
来源：http://dali.ydzc1.top/Article/details/gtaovxtamu.html

[U51] PHP：数组解构
来源：http://dali.yueranfly.top/Article/details/gtddpvmuca.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gtwhbqhvvy.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtadebtneu.html

$double = fn($x) => $x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtzwfyofzr.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgftsxfo.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gtwntgjfjm.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtrxwpwggw.html

$obj?->method()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozconfyc.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtnjggoejf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gtazovbdxr.html

[U56] PHP：命名参数
来源：http://dali.haohaochexian.top/Article/details/gtcgomnxcd.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtbnquvtmq.html

[U57] PHP：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtpiwikacz.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gtuhibzhds.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gtrwcbygpn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gtcgxdxwes.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gtdavgiysy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtmlaxaohq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gtjmweptek.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gtmzznuxqq.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtqdufnqvn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtmbcnbyni.html

[U62] PHP：日期对象
来源：http://dali.chenlongwang.top/Article/details/gtgsnnvswe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gtwvlzfjyg.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtsluwoiqb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aibaodan.cn/Article/details/gtuqdykods.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gtlktzwzec.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.mhx1999.top/Article/details/gtlzleoola.html

[U65] PHP：会话
来源：http://dali.hongshengwenyu.top/Article/details/gtsfuyypvf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtlateztwi.html

[U66] PHP：设置 Cookie
来源：http://dali.ehwqpu.com/Article/details/gtmyxsspmn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gzhubu.top/Article/details/gtshfllaau.html

[U67] PHP：处理文件上传
来源：http://dali.ppjwa.cn/Article/details/gtsnqwuzti.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gtgtwovuos.html

[U68] PHP：PDO 连接
来源：http://dali.gotoacloud.top/Article/details/gtrjdgmrhw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yanxiufei.cn/Article/details/gtcedmcpda.html

[U69] PHP：PDO 预处理
来源：http://dali.andypj.xyz/Article/details/gtrckhrvrs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gtexllngzb.html

[U70] PHP：PDO 事务
来源：http://dali.xylfe.cn/Article/details/gtfmmmghfo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gtregjenkg.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gtceotgftk.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtkgrvrjuu.html

[U72] PHP：写错误日志
来源：http://dali.shuidangran.top/Article/details/gtrizkzlga.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gtgboalydu.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtvigxhqfj.html

parse_ini_file("config.ini", true)
来源：http://dali.cucudq.cn/Article/details/gtfqdsksnz.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtvmldkvpy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.birdmap.top/Article/details/gtaiirnqpf.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gtwiupsvaz.html

composer require psr/container
来源：http://dali.tanke756.top/Article/details/gtkwqbncct.html

[U76] PHP：简单路由
来源：http://dali.cheryme.top/Article/details/gtpeppzfvc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ehwqpu.com/Article/details/gtmpuozljf.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtljhnpkmx.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gtqrgrxzbg.html

[U78] PHP：单元测试
来源：http://dali.cucudq.cn/Article/details/gthkgbfvtm.html

composer require --dev phpunit/phpunit
来源：http://dali.dianchejie.cn/Article/details/gtgfmdsavw.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gtfrkxwnze.html

composer require --dev phpstan/phpstan
来源：http://dali.0kj1m.cn/Article/details/gtzlvhtjnr.html

[U80] PHP：代码规范修复
来源：http://dali.hammf.cn/Article/details/gtvgjdbgpu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.9152youxi.cn/Article/details/gtuwozolcy.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gtfhnuylta.html

npm init -y;  npm i express
来源：http://dali.0kj1m.cn/Article/details/gtcnrdbkns.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtlrkuuexf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xinyue.icu/Article/details/gthlfgysal.html

[U83] JS：ES Module 导入导出
来源：http://dali.c1oappe.top/Article/details/gtgajyihdx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtjfszueqv.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgufenzy.top/Article/details/gtilbkfcbh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtboahfvhd.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtmsaiassd.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gtmhpldkud.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtsmpguymj.html

a ?? b
来源：http://dali.snrcjt.cn/Article/details/gtdsnvciqg.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gtcwquaakn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ivvv.top/Article/details/gtocvjgprs.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gttbrvxxvf.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gtwxwvrdhl.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gtvgxohkul.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtlftbgpkk.html

[U90] JS：数字数组排序
来源：http://dali.pycfn.com/Article/details/gtydgazgzb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtiknxqwei.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtrtcqfbnd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafwfqiwk.html

[U92] JS：深拷贝
来源：http://dali.ydzc1.top/Article/details/gtvqnsmorm.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqmsalvpv.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gtemvchxwn.html

`共 ${n} 条`
来源：http://dali.hfpthk.cn/Article/details/gtzvanrson.html

[U94] JS：箭头函数
来源：http://dali.tianlin.xyz/Article/details/gtmdqneabd.html

const double = x => x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyppbfcm.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gtudhjhild.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtspdsfsbp.html

[U96] JS：async/await 与异常
来源：http://dali.zhoulong.xyz/Article/details/gtmmsyemqg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtbjuaqjfe.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gtsauioglk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtejijmuot.html

[U98] JS：fetch 带 JSON
来源：http://dali.nwbrower.top/Article/details/gtjwlhffij.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ehwqpu.com/Article/details/gtjsmahaoa.html

[U99] JS：事件监听
来源：http://dali.aibaodan.cn/Article/details/gthlbqitsg.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gthtnsjhqx.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gtvbgdsvqy.html

document.querySelector(".item")
来源：http://dali.haohaochexian.top/Article/details/gttiqbktxg.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtcgiacvyy.html

el.classList.toggle("active")
来源：http://dali.dashuyun.cn/Article/details/gtkiqwuofy.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gtfdxozplc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtsjtgmsiv.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtbxkxrwnx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxmagkhl.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gtonxkrqea.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gthatkeckf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtmvworuvj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gtdyxdwvki.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtldumxmni.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxuanxn.top/Article/details/gtxxofuncz.html

[U107] JS：数字千分位
来源：http://dali.ydzc1.top/Article/details/gtrvsekvmh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtbpncoaof.html

[U108] JS：随机整数
来源：http://dali.nanxuanxn.top/Article/details/gtguyrbgmm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gtgjxnbbjm.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtvgqznxus.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtqvvoxphq.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gtgunknhuv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gtfgiqymwj.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtvirvfrjp.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gtcyxucxkn.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gtelratfsj.html

"7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtkrraxzqz.html

[U113] JS：正则替换全部
来源：http://dali.mhx1999.top/Article/details/gtytbedfhg.html

s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtzyaghydb.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtnhonqlbc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtujrmtnwa.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtvqdqipje.html

crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtxyvubnjy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenjidiqi.icu/Article/details/gtxkizllky.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gtrnumgvjq.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gtbogjfumd.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtxshxpxwt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gttrkvcydo.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gtybjuvhuy.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gtjabyjnya.html

npx vite build
来源：http://dali.shanyushiyangtech.top/Article/details/gtckyeeufa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnxiangtu.top/Article/details/gteolkyamx.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtkasrzjsn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkznbjtww.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gteyqabhuo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsroxdwrc.html

按语言统计（条）：
来源：http://dali.ehwqpu.com/Article/details/gtdkgbpucj.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gtseumpbvn.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gtotedhlut.html

JavaScript ..... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtmwwbbcvs.html

TypeScript ..... 212
来源：http://dali.tanke756.top/Article/details/gtyevbyysy.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtafffpdzd.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gtgnuibpfe.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtbbnkhnuc.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtzygryznx.html

C .............. 30
来源：http://dali.yonumen.top/Article/details/gtkpwdvvsk.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gtkmexxnqy.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexqqowpm.html

Bash ........... 80
来源：http://dali.sufxvd.cn/Article/details/gtmlooiwpp.html

Kotlin ......... 15
来源：http://dali.yuanzhike.top/Article/details/gtvzyyjpyb.html

Swift .......... 15
来源：http://dali.quarkkingdee.top/Article/details/gttfimkfoe.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gtlfvnsegl.html

Perl ........... 10
来源：http://dali.dashuyun.cn/Article/details/gtpwkspviy.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtutftxjrc.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtxesibgtt.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtwsybngnn.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtsposwtjp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gtfdoccfbb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtsxweiyur.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxkbqzvx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtluypiuom.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gtfzpvuvyn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtaktulmex.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtsgoqhdbe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtsidqmoxj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovlsjmgx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtytdjdwuv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtwwigxlpu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtjixdsjef.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtbljeuhkc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtwqpqaycn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yvedp.cn/Article/details/gtbsroxrgq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtlsrsrrxw.html

Q SQL 专题                              90
来源：http://dali.xinyue.icu/Article/details/gtjgxdqvav.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gthktbrgax.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtxtodkqpo.html

T 其他语言补充                          60
来源：http://dali.guannengcc.top/Article/details/gtkawzwfgp.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gtlooieooz.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtktpbkaxo.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gtqjwotxgd.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gtyzzmprpp.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyyndetc.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtrnixpyzx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtvtlkhbng.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shzxlz.cn/Article/details/gtsuoaqbde.html


<!-- 参考信息 -->