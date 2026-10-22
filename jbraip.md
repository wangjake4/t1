代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gtdfiefgpy.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtpqlkfgin.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgamkvib.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtuvivnvxr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gtgzloxagm.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gtseoqppju.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtnrdyxpug.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gtfqkbtnxf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gtawzlmnkl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkgijbobe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtcomfomlq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowhmfime.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtfxpteeay.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtzpxakaui.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gtberedptu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcenyeiti.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gtzdhvjhtf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gtaublsnxs.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gtgrpyblkw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtakepqjiv.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gtawwxlmvd.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtpfnitqur.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gtqaqkdexw.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtuxvhapjr.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gtyejssysa.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gtoopbmrns.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtiyiyxopz.html

[y for x in nested for y in x]
来源：http://dali.pengpengdd.cyou/Article/details/gtyetmegqj.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlfmmshy.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gtthpwxfep.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtqhyueolt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gtzagnomyx.html

[U11] Py：生成器表达式
来源：http://dali.xziqi.cn/Article/details/gtnssufpen.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gttfubiurk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtwbxuewth.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gtnwefpksi.html

[U13] Py：固定长度队列
来源：http://dali.c1oappe.top/Article/details/gtiyydzggs.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gthwrflwhd.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gtaepxkvhx.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtpqufbuji.html

[U15] Py：高精度计时
来源：http://dali.sxryk.cn/Article/details/gtadmhxymp.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gtjgaethjx.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gtpfqxbyfg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtvbzoyuoj.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gtktsxdoid.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gtpixjkoml.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtifqivyck.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtomzpvxpm.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gtkioreiyg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtppnyguhh.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtvojjytfv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gtzktjmjmf.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtvqdpckpf.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtprmmrqsd.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gthmwhctxg.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtrdfbvvqw.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtaupushhn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtullklhml.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gtkntqyvln.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtdaqvzlwx.html

[U25] Py：CSV 按字典读
来源：http://dali.tian-w.cn/Article/details/gtpedogqke.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gtlvttmzbz.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gtvoecumbm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gtbkfipurb.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtqyfsqdfx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gtlabhjjsn.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gtsdfjycuf.html

UserId = int
来源：http://dali.c1oappe.top/Article/details/gtgdmxmulh.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gterzlrvrx.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gtxpeapruk.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gtoyzjvibz.html

@dataclass(slots=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwioaoyai.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtrrekrgts.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gtwuwilhcy.html

[U32] Py：代码格式化
来源：http://dali.shzxlz.cn/Article/details/gtgagccysm.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtmsdjeuzz.html

[U33] Py：打包发布
来源：http://dali.havefunace.top/Article/details/gtcqkeghfi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gtemkhoylw.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gtqbsfrfim.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtvurlkqnl.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gtajyfacid.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gtdvnanaga.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gttruyxcqo.html

schedule.every(10).minutes.do(job)
来源：http://dali.tian-w.cn/Article/details/gtfgsaxlvy.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gthuvtwrcz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ppjwa.cn/Article/details/gtcmeoojai.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtmacqnpnb.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtvbxbcraf.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtndaelmhu.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtqlajhlac.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiiwttjy.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtbjtvoapf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gtxdrkjjdt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gtrslhviqe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpfglwlz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jianghu66.top/Article/details/gtqzozhlew.html

[U43] PHP：声明命名空间
来源：http://dali.hfpthk.cn/Article/details/gtiyiwkhsn.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtrnzujdct.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtbxdxauvr.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gtpwwsizcn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gtdgqqybag.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfpkfrqra.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtchodejid.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gtgezdfdtu.html

[U47] PHP：联合类型
来源：http://dali.smart0.xyz/Article/details/gtluncwcli.html

int|string $id
来源：http://dali.yuanzhike.top/Article/details/gteftikdof.html

[U48] PHP：纯枚举
来源：http://dali.yuanzhike.top/Article/details/gtcaosqitp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gtgrnmaiiu.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gtaeldrjie.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gtgahqcgjn.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gtoniecuox.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gtvtzakami.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gtsawhwdcg.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gttxdoncjf.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtcfsaaepn.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gtzzttsved.html

[U53] PHP：空合并运算符
来源：http://dali.pycfn.com/Article/details/gtzxokjlmz.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gtewpibvfw.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gtshobsekl.html

$obj?->method()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjvzqtxt.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gtzdyjotmp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtriobtlpx.html

[U56] PHP：命名参数
来源：http://dali.aizwys.cn/Article/details/gtrfdfdwjl.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtgfswyxfo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtvuzimkek.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gticveducl.html

[U58] PHP：数组三件套
来源：http://dali.wangshuangyany.cn/Article/details/gtcyqasxxm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gtpyszmwaj.html

[U59] PHP：自定义排序
来源：http://dali.0kj1m.cn/Article/details/gtkkrnyqun.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtmifdtxuo.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gtwjhxljph.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj202588.top/Article/details/gtkueduydw.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmunbyvex.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthprxpjqr.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtboqzpbdv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gtrcuoftgg.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtpgkqwezm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gthzpwxtwo.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gtatczdbrw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gtyrpuaivz.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtbxyjrbxg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtwdlyoufq.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gtzrkdfpyw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtqnviabke.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gttjpbscqt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtsfiwdgfj.html

[U68] PHP：PDO 连接
来源：http://dali.fengsongda.top/Article/details/gtdolhiebm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gthoguncxu.html

[U69] PHP：PDO 预处理
来源：http://dali.sufxvd.cn/Article/details/gthvlvlaoz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtcjocvqxo.html

[U70] PHP：PDO 事务
来源：http://dali.haohaochexian.top/Article/details/gtgbzjsckq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gtwltaijfz.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gtdmsjbmmb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtojmgsvog.html

[U72] PHP：写错误日志
来源：http://dali.fengsongda.top/Article/details/gtgdkqbgcl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gtznqutpul.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gtsopblwff.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthunvsnzz.html

[U74] PHP：读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtkqguapig.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gtedmiiafh.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gtktuwxmoc.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtazsrsodt.html

[U76] PHP：简单路由
来源：http://dali.pycfn.com/Article/details/gtxhettdod.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangshuangyany.cn/Article/details/gtjrcmdbim.html

[U77] PHP：模板渲染
来源：http://dali.jyoumei.cn/Article/details/gtfubfaxlz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gthzjdtpfd.html

[U78] PHP：单元测试
来源：http://dali.sxryk.cn/Article/details/gttbbgyfkd.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gtdqrupdky.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtmaqnbgcc.html

composer require --dev phpstan/phpstan
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyvsokyd.html

[U80] PHP：代码规范修复
来源：http://dali.quarkkingdee.top/Article/details/gtipflltjg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jlsjyb.cn/Article/details/gtntvwbrvz.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gtymfgetva.html

npm init -y;  npm i express
来源：http://dali.haohaochexian.top/Article/details/gtaywnpohj.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gturkrzqtj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hfpthk.cn/Article/details/gtzykjrchm.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gtbvlpwdfw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtfrideljs.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gtdnqbxpcq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cashguo.top/Article/details/gtqhdpzvcv.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gtpmttekjz.html

a?.b?.c
来源：http://dali.tanke756.top/Article/details/gtkiewqdov.html

[U86] JS：空值合并
来源：http://dali.zhongyouzk.top/Article/details/gtekcjsfje.html

a ?? b
来源：http://dali.hammf.cn/Article/details/gtchpected.html

[U87] JS：解构默认值
来源：http://dali.meibo888.top/Article/details/gtxwjuugip.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xziqi.cn/Article/details/gtzxwkpgrz.html

[U88] JS：对象展开合并
来源：http://dali.pycfn.com/Article/details/gteaptxbit.html

{ ...a, ...b }
来源：http://dali.havefunace.top/Article/details/gteaxfxefh.html

[U89] JS：数组去重
来源：http://dali.dashuyun.cn/Article/details/gtdayfcjbd.html

[...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtkhqyvoqk.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtimtugwfe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gthgjitfrg.html

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gtvtcgdjrd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuxming.cn/Article/details/gtjcbbbvvk.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gthsylccji.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gttphuipzs.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gtapabxgta.html

`共 ${n} 条`
来源：http://dali.jianghu66.top/Article/details/gtfxyhtzbf.html

[U94] JS：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxadyrahg.html

const double = x => x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtbccnfqil.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlkbhqky.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtdwewniyg.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgajlsuj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtlexfvpib.html

[U97] JS：并发请求
来源：http://dali.yuxming.cn/Article/details/gtcixkpysc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtpixspxyn.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtvoobsblh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtyhqleici.html

[U99] JS：事件监听
来源：http://dali.yj202588.top/Article/details/gtsrnppwps.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gtinwaznka.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtivqmnril.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtpgkpgloi.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtogggeuev.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gtkkvyszbp.html

[U102] JS：本地存储
来源：http://dali.jiagoushi.top/Article/details/gtuzypuujh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gtxvvgrsgw.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gtehmdodxd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gtqtmmkmck.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gtmtvnsjjb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtykowhcqg.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gtyawkmqqj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtocoehoij.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtwnyspyae.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gttbprglkw.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gtkfgoroxj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwlewfvm.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtunxlvaeu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gtubqnhvvw.html

[U109] JS：数组分组
来源：http://dali.wangshuangyany.cn/Article/details/gtzcfwxyvn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtctfmxxlj.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtqralkcra.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtaztyisui.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gtggtghkbs.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtqofyavgx.html

[U112] JS：字符串补位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpdapyie.html

"7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtcgqimzql.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtyipzgwed.html

s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtjbhqkzyu.html

[U114] JS：JSON 深比较
来源：http://dali.mhx1999.top/Article/details/gtytdczzuq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gttndiqpkx.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtxqwocy.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtbryjouqh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gteimlkqdz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gtlnptzepj.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtmphadalo.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gtzvaxcujq.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gtiqlvnjmi.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovnevtkd.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtsihtylmh.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gthlwfoiqp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtbmvnzvpc.html

import.meta.env.VITE_API_URL
来源：http://dali.cheryme.top/Article/details/gtuzfshqej.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfuroftdw.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gtcqvnkgzw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtveqwezkw.html

按语言统计（条）：
来源：http://dali.yuxming.cn/Article/details/gtyjsmqumq.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gtplkthcbz.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtgkfwktfz.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtumwrqvaq.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtlcyxcddc.html

Java ........... 212
来源：http://dali.daxiang520.top/Article/details/gtvaljomro.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtxjvdumsk.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtzskzzgmu.html

C# ............. 212
来源：http://dali.smart0.xyz/Article/details/gtxfeygfkv.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gttwpvwufm.html

C++ ............ 30
来源：http://dali.guannengcc.top/Article/details/gtxnvmrnoh.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtcgolgveb.html

Bash ........... 80
来源：http://dali.jyoumei.cn/Article/details/gtqwvocacn.html

Kotlin ......... 15
来源：http://dali.hywenlv.cn/Article/details/gtcweeeavu.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gttmsluugn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gtgfoaremp.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gtnanikqjx.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtyhxjppni.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtvklhlcxs.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtxpjmyxpi.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gtcstmdegw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtivwslhpc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtkovjsmeq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtydxdxyeu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtomdffqlf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuxming.cn/Article/details/gtokhsbvhv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gtgiqvbljh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtaqteifhf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gtbydstuzx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhdmmves.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtfpdkcfcf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyaxwrzq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gteduymged.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtrhoehwvx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtiehpwuzv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gtalxhsdzs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gttbagfzuk.html

Q SQL 专题                              90
来源：http://dali.yuxming.cn/Article/details/gtoclzbqin.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gtejkkqsaf.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gtrdlhvcsy.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gtmjloyilo.html

U 高频实用片段                         120
来源：http://dali.aizwys.cn/Article/details/gtfxlbmqzp.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtqfwgshrh.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gtodsawndp.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtkrglhjuy.html


<!-- 参考信息 -->