代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjvwetifo.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtcyqjzyip.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtmbbbkqiu.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gtdxlhbqcp.html

val a = 1;  var b = 2
来源：http://dali.hywenlv.cn/Article/details/gtpcyysqfs.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtysiclvzv.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtoeufbper.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtmftjrgnp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtlsznknsr.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtkridmrdw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtterfkmvt.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gthcgpcunh.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gteamtappf.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gteivtouyr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gtmwzlfyni.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtgociufge.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtbvjskqom.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gtifurvofo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtkrwexexg.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtftbgsdps.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gtlkowdcjx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvxyvivsf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtbceaoegi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwrgzhlzc.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtrxjtuggu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtgkflgyhj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gtpbljscca.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtdlbfrzau.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtczathsgh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtudwekelh.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtzdhyrmfh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ybcxt.top/Article/details/gttueptrfr.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gtudpkxdfm.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtybeevrqp.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gtkfsaczsx.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtmggqqxyh.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtrblgmpix.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gtpnwbmiti.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gtyeekzgkg.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gtiwcdigro.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gtxqvmkefw.html

max(d, key=d.get)
来源：http://dali.tanke756.top/Article/details/gtbcbmsoyp.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gtxfohvlls.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtihlalwey.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexvlcnua.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusyggmcj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xziqi.cn/Article/details/gtdufmftdr.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtocpyroae.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gthdfpwhqq.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtoehoomva.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gtthrwerbt.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gtcagligze.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtdxyhjitc.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtciveiwer.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gttzkynblo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gtcinajzjs.html

[U17] Py：初始化日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpgmmaxq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtgxvbwrgn.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtgcmrklir.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gtpfoekdjy.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gteeceqicq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtlvgdkgza.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gtxighdgix.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gtipwqybxc.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gtqsowiufs.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtkrmhswtv.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gtlydladnd.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gtykolpndr.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gtzaaesvub.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgufenzy.top/Article/details/gtgxgruuxm.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gtqaelczcq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gttdyfbtjr.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gtxcknvhfv.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtebxccjxb.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gtrfilxokb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtyozzofev.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gtpzociahg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhixingplan.top/Article/details/gteqqankje.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtvnjixjug.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gtlmqzhxqq.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gtcikoghcw.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtteluamzy.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gtyoztviha.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gtyvffbtos.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gtsguqmxjq.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gtodqnjrjp.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gtwpizxnnx.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gtooocoykg.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gtxbpvcsog.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.c1oappe.top/Article/details/gtfoxqklau.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gtyrtcwjpa.html

chardet.detect(raw)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpygjclcs.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtkhweoggu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnqzz.top/Article/details/gtoibcriyh.html

[U36] Py：定时任务
来源：http://dali.meibo888.top/Article/details/gtjdvlpaip.html

schedule.every(10).minutes.do(job)
来源：http://dali.316326.xyz/Article/details/gtpafeaqfn.html

[U37] Py：读写 Excel
来源：http://dali.fzhhl.top/Article/details/gtjpnwcykg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gtfwfuzolq.html

[U38] Py：获取脚本所在目录
来源：http://dali.mhx1999.top/Article/details/gtufmfvzla.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gttbvsnlaw.html

[U39] Py：判断是否在交互环境
来源：http://dali.dianchejie.cn/Article/details/gtoccawesv.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gtcbdiqfbb.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtaawfinrj.html

print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtrebnkksc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tanke756.top/Article/details/gtzboetgva.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yongpay.top/Article/details/gtctxqgwmy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gthmjwpfbx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtkpgrmfsm.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtbljgankr.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gttdwewimj.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gttyvnpabr.html

declare(strict_types=1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrgdldvq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gtjukutdxg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gteyeaollm.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gttjgacbll.html

?string $name = null
来源：http://dali.havefunace.top/Article/details/gtgxnjjssl.html

[U47] PHP：联合类型
来源：http://dali.xziqi.cn/Article/details/gtugmjrypt.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gthxsnpfsk.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gtnahtocxd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gtgpmxaszj.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gtnayzqmgs.html

public readonly string $name
来源：http://dali.hnxiangtu.top/Article/details/gtqtcmzlwr.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gtelqehnxf.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtsjnvzzfs.html

[U51] PHP：数组解构
来源：http://dali.cheryme.top/Article/details/gtvhglnhaa.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gtsaoyzglq.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtthzvdfbz.html

$double = fn($x) => $x * 2;
来源：http://dali.guannengcc.top/Article/details/gtrrwnqskc.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gttvbwsxze.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinghuilouyu.cn/Article/details/gtstkxggvj.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gtqtotigrm.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gttbsejtda.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gteeuyxzjk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtjkbymnhu.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gttuysqfxv.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtglosxzxd.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gthalotppd.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtslprqlbw.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gtanybvcsu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gotoacloud.top/Article/details/gtidqqytyd.html

[U59] PHP：自定义排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmorkiwmb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtcljimuye.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gtpibbfhsd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtpphmxyzn.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gtfphraire.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtdrwvkfjn.html

[U62] PHP：日期对象
来源：http://dali.yanxiufei.cn/Article/details/gtzaawaowf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gtyufbpuon.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtfdoqkefr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gzhubu.top/Article/details/gtfdwnmgkv.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gtupvdfbqi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gtjburjkwm.html

[U65] PHP：会话
来源：http://dali.hysaishi.cn/Article/details/gtfzkjaxsu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtkaiqusdc.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gtunlytntc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.redwolf501.top/Article/details/gtdyyjcjxj.html

[U67] PHP：处理文件上传
来源：http://dali.hfpthk.cn/Article/details/gtdqlmtjkp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gtqppozadu.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtfbcilyzq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dianchejie.cn/Article/details/gtkczukilg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhoulong.xyz/Article/details/gthvinbqyg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gtwjgtukww.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gtvlfrzwdk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gtqxwdvqwv.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gthzmwgxfk.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigufen.top/Article/details/gtaulocxig.html

[U72] PHP：写错误日志
来源：http://dali.zhiwuduotai.top/Article/details/gtxcyafaad.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gzhubu.top/Article/details/gthajractq.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhmziqiz.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtbodgkzsf.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtmwlsippr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.bjfxy.top/Article/details/gtgptsugrq.html

[U75] PHP：依赖注入
来源：http://dali.aibaodan.cn/Article/details/gteaoyepka.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gtialculeg.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gtekudwrle.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gtacpneaba.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gtcmnqprvd.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gtdjqltmkl.html

[U78] PHP：单元测试
来源：http://dali.havefunace.top/Article/details/gtqutfaacs.html

composer require --dev phpunit/phpunit
来源：http://dali.c1oappe.top/Article/details/gtynymtgfg.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtansaqkcq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtbdydmcvv.html

[U80] PHP：代码规范修复
来源：http://dali.guowangkeji.top/Article/details/gtejugrxly.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daxiang520.top/Article/details/gtehxbhisa.html

[U81] JS：初始化项目
来源：http://dali.yvedp.cn/Article/details/gtnwhssswx.html

npm init -y;  npm i express
来源：http://dali.daxiang520.top/Article/details/gtcdqhgrps.html

[U82] JS：package.json 脚本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgkqfkzr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gtiptiahxy.html

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtdtgfkl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtdcljftfv.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvapcpww.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gtpizbobua.html

[U85] JS：可选链
来源：http://dali.meibo888.top/Article/details/gtlspnpayt.html

a?.b?.c
来源：http://dali.hongshengwenyu.top/Article/details/gtfpkhssih.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gttzxabqhk.html

a ?? b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaoifnzj.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtjgurmvef.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gtrmwzccld.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gtzsnprogu.html

{ ...a, ...b }
来源：http://dali.mhx1999.top/Article/details/gthjfkxzdm.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtexzejmaa.html

[...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtezflmybn.html

[U90] JS：数字数组排序
来源：http://dali.tanke756.top/Article/details/gthcrzbxce.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtbbkjlqbq.html

[U91] JS：对象键值遍历
来源：http://dali.gzhubu.top/Article/details/gtgfgzmsls.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenjidiqi.icu/Article/details/gtikiasvxb.html

[U92] JS：深拷贝
来源：http://dali.shzxlz.cn/Article/details/gtnjqjoevv.html

structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtwqjvdmby.html

[U93] JS：模板字符串
来源：http://dali.iojbl.cn/Article/details/gtavwieehe.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gtifoewzcb.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gttckozdlv.html

const double = x => x * 2;
来源：http://dali.cashguo.top/Article/details/gtynlqyykk.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gtbzizscav.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gtlczhvtvu.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtknnthhij.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtbmfdoppd.html

[U97] JS：并发请求
来源：http://dali.xuanzx.com/Article/details/gtujwnleqw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gteiyvjknv.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtkkayaabl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guowangkeji.top/Article/details/gtifilwwjt.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtyprvzbrv.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gtfdesfipz.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtknaflpgu.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gtvuighfgq.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gtngxvgvtw.html

el.classList.toggle("active")
来源：http://dali.feifeiyinyue.top/Article/details/gtmedwomhj.html

[U102] JS：本地存储
来源：http://dali.zhiwuduotai.top/Article/details/gtegazjehy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtjklebilj.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gtltyssuez.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gtgrzrdphb.html

[U104] JS：防抖
来源：http://dali.tian-w.cn/Article/details/gtgoxcxeqh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtdckghfll.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtcpqzheah.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gtendqhskg.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtivnlqyki.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ybcxt.top/Article/details/gtklxyhxgs.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtxhmqucqo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtmqqsaxnq.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gtuqiulqzg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtstjujkjs.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gtqqovsixk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtmymjmeku.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gtoaidtgps.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtzgbrbvyd.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gtwpkkikdv.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gtxypmtxyl.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtqonfohiw.html

"7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtkpvmxvpj.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gtlsalsihb.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtfsqoighs.html

[U114] JS：JSON 深比较
来源：http://dali.wangshuangyany.cn/Article/details/gtwjttorts.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtntvnkjal.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtbyruptbb.html

crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtwhjfjryu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtritrydxb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtpnbxyoyl.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gttwsaesuk.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtnptnpfqw.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadsiwgcc.html

npm i -D vite;  npx vite
来源：http://dali.yueranfly.top/Article/details/gtieltjnsd.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gtusksucwi.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtcjtshdyx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtlhbokwgn.html

import.meta.env.VITE_API_URL
来源：http://dali.tianlin.xyz/Article/details/gtrvqkzbkh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfauxspyx.html

统计汇总
来源：http://dali.yonumen.top/Article/details/gthfvneemq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbqnqzhkn.html

按语言统计（条）：
来源：http://dali.chenlongwang.top/Article/details/gtaephuqco.html

Python ......... 252
来源：http://dali.hnxiangtu.top/Article/details/gttqxqibwc.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccfqjont.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtdoggulkx.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtpnqrzhpi.html

Java ........... 212
来源：http://dali.cucudq.cn/Article/details/gtjnloqrbo.html

Go ............. 212
来源：http://dali.daria6918.cn/Article/details/gtgiejmitj.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtqvlnwecy.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtkcsldbzj.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gtvkrkjjza.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gthzmiwuaq.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gtdglhzyut.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtxtpndrfc.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtgulplvew.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtpgwayvcl.html

Lua ............ 10
来源：http://dali.ydzc1.top/Article/details/gtfoywpzyc.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gtxyrbvceo.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtuyhozelp.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtfaqjwemu.html

合计 ........... 2106 条
来源：http://dali.yj20258.top/Article/details/gtlukzofth.html

按章节统计：
来源：http://dali.nanxuanxn.top/Article/details/gtfqxnzsjo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtiwowsbek.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtbnslxiqe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtchlnrrud.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtporiskbw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tanke756.top/Article/details/gtkhnvdwog.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtaimawxbn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtubymkazo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gthdjvbbny.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtvmfwjosw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtnlsclzco.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtzxikzemb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtjradpkzh.html


<!-- 参考信息 -->