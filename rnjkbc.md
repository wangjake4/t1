代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gtywszmooe.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtlqicxsek.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjlqiomr.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gthvnngbhq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gticsluivw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwbhfckte.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtlnwqsfeb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvluvhai.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gtmwqdcybh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gttpcztzzd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gttwgrnbly.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtfcqwtlru.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtoespwniq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtwuiafgcb.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtcbjptcxt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfnbuqxz.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gtjxrvfoin.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtvuixpmxx.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtvdsgifii.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtejgjjeck.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtrmkliilc.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtcujtdfcn.html

[U08] Py：展平二维列表
来源：http://dali.snrcjt.cn/Article/details/gtuwxqyfqw.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtlgchidif.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtacphhkql.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhwtjcqb.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gtjozmkvjz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gtumfqwbdn.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtabtskcjw.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gtwdgytpei.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtdxdmmncm.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtuqbfdehv.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gtmgmlfjmk.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gttkhyfvzh.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gtoprmkcio.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gtinnxtdhy.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamtcbujw.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gtpnodtiiv.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gtwbdjyxqo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gtrbvbmacr.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gtzkefwvvi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtoaeozgyb.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtxpqllmvx.html

pat = re.compile(r"\d+")
来源：http://dali.snrcjt.cn/Article/details/gteggqhbev.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gtyokxtqmz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtlrsqhcwc.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtyfqgqdzd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gtbhnmqltt.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gttsucdogw.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtnyposqle.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gtwxokkrqv.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gtcwcttnyd.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtabsrjdbe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gttatioiyd.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gtmyjldckl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtzodlnbsi.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gtqaigiple.html

csv.DictReader(f)
来源：http://dali.hnxiangtu.top/Article/details/gtttdayyhl.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtscuzbdwa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtykioqdlz.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtairyvixe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtwtaxuumv.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtlxosrtbm.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqleaajg.html

[U29] Py：属性校验
来源：http://dali.xylfe.cn/Article/details/gtdvytzrla.html

@property 与 @x.setter 配合
来源：http://dali.ehwqpu.com/Article/details/gtmyxvdiej.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtyxmejdex.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtxrdatvpk.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gtvghhagwt.html

python -m pytest -q
来源：http://dali.yongpay.top/Article/details/gtosbxscwv.html

[U32] Py：代码格式化
来源：http://dali.cdnleiting.top/Article/details/gtvwzipssi.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gtrcnhdxza.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gtdrdckkwg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuxming.cn/Article/details/gtxsuxwxtu.html

[U34] Py：判断编码
来源：http://dali.sweek.top/Article/details/gtoniaebkg.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gtwukypuhj.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gtyhtysbry.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gteaxcfvwn.html

[U36] Py：定时任务
来源：http://dali.meibo888.top/Article/details/gtgxcjaqbz.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtepjoceam.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gtltfsynkl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gtrpcqwvdl.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpglxusa.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gtdiscfwae.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtylgwiwfe.html

sys.stdout.isatty()
来源：http://dali.ivvv.top/Article/details/gtoydumaax.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gtmxgyfrtd.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtiapgijhv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgfzy.top/Article/details/gtntlshoqx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtfsqdgnym.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxinkj.top/Article/details/gtkhmrkicb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gtsodqoewl.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gtwvpnecmp.html

namespace App\Http;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzdryjtp.html

[U44] PHP：开启严格类型
来源：http://dali.zycfv.cn/Article/details/gtpfzybcbb.html

declare(strict_types=1);
来源：http://dali.yuanzhike.top/Article/details/gtziunohyw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiayzihn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtftzqyrno.html

[U46] PHP：可空类型
来源：http://dali.birdmap.top/Article/details/gtcnllfxve.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtgphstpjv.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gtgbobygvg.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gttrfztgdg.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gtotdkmqju.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtryzefabo.html

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gtiytpvqof.html

public readonly string $name
来源：http://dali.zhoulong.xyz/Article/details/gtzivexulw.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigfzy.top/Article/details/gtpudouwqt.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gtydvjbtxn.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtjskcsnuf.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gtrrciutzl.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtzrsslmfi.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcthdokwe.html

[U53] PHP：空合并运算符
来源：http://dali.chenlongwang.top/Article/details/gtsvplccnf.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gttyedlhxb.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gtwvdlkpbp.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gtvqovgczy.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gtsbyvczqn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtbhpxlwoi.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gtsnhxlxht.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtxiuemfec.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gttsgelnoa.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gtoevllwsf.html

[U58] PHP：数组三件套
来源：http://dali.chenjidiqi.icu/Article/details/gtlqubroyw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfnxscwv.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gttktbfsuq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtmtbegefv.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gttvgynqmp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gtimpsdjkf.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gtevcbhqec.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtlnsxswst.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gthcvcaivl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gtochwhusb.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gttfdeevwo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gtfopixpsi.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gtkdncuqhi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gtkiogyvcm.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gtioavmyjt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtfxyxevqn.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gtupgikjai.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gthbnxnukc.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gtlnebentp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gtwjfiuvds.html

[U68] PHP：PDO 连接
来源：http://dali.nwbrower.top/Article/details/gtdurydgsa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shuidangran.top/Article/details/gtxeztbuoq.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gtvvtnjjvz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gtnuelhtei.html

[U70] PHP：PDO 事务
来源：http://dali.zhengqikj.top/Article/details/gtwwczfjkw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.snrcjt.cn/Article/details/gtwpohbonr.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gtzyoifpey.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtetbuhblv.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gtlakqkozq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gtnrvktkoz.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxjaptdu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhixingplan.top/Article/details/gtfoxcnvbi.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtsrvqgtet.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gtigeofxks.html

[U75] PHP：依赖注入
来源：http://dali.wangshuangyany.cn/Article/details/gtgjcfaqij.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gtyfuwmxgp.html

[U76] PHP：简单路由
来源：http://dali.svipenyu.cn/Article/details/gtpzdpddge.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gtesjnxrsb.html

[U77] PHP：模板渲染
来源：http://dali.ybcxt.top/Article/details/gtdkuvodul.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gtyoitacpz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtidugjcis.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtiipahjsw.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gtcqlfjchl.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gtktjykbzm.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtojuuocek.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtzfffsxmz.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gtpwsqutoq.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gtgfywgyts.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzlbeare.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.smart0.xyz/Article/details/gtpxsiujyf.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258.top/Article/details/gtyuuqsalt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtfljwqnmt.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgfzy.top/Article/details/gtngxlhejs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gtiejigkpu.html

[U85] JS：可选链
来源：http://dali.zycfv.cn/Article/details/gtgnyqfozn.html

a?.b?.c
来源：http://dali.haohaochexian.top/Article/details/gtxeujivoq.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gtyqewangn.html

a ?? b
来源：http://dali.zhongyouzk.top/Article/details/gtusabwrex.html

[U87] JS：解构默认值
来源：http://dali.zhongyouzk.top/Article/details/gtspxiwhem.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258888.top/Article/details/gtvezauigw.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gttqzloiuv.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gtkgsiipkz.html

[U89] JS：数组去重
来源：http://dali.yj202588.top/Article/details/gtfybwjcgj.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtnxbapldq.html

[U90] JS：数字数组排序
来源：http://dali.zhoulong.xyz/Article/details/gtotjfftbn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtolatyedr.html

[U91] JS：对象键值遍历
来源：http://dali.hnxiangtu.top/Article/details/gteyknludx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dashuyun.cn/Article/details/gtwgodqbgl.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gtfiikngpi.html

structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoumgpkws.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gtdekicrlh.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gtvxgtktpz.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpnghwve.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtmbjunsrf.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gtwvzfdzyj.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gtfftniroe.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gtozxqwrss.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtcwhdfqae.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtqzvckwbi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtwdskmhba.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gtefqepmtt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jiagoushi.top/Article/details/gtwxzffpbq.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gtnczfhmac.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gtirphlylu.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gtwvcpqvak.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gtrhfttqsy.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gtsfidlvtv.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gtvhlulqsq.html

[U102] JS：本地存储
来源：http://dali.cashguo.top/Article/details/gtxzxbwpul.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hywenlv.cn/Article/details/gtksuapxby.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gtdisoeuol.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gthdfnzhvb.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gtrnlptuja.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtoflhfwcj.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gtqxvnynld.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhongyouzk.top/Article/details/gtmhkrgoxz.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtcclrvqul.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gttdkjaken.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtlfldcdqf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdotgzomc.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtuxmkftrz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gtezsepwku.html

[U109] JS：数组分组
来源：http://dali.jinqigfzy.top/Article/details/gtikmjfdlu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtzdzvnlcn.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gtyrcwgigw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gtcwdregbs.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gteffgfqtw.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gtzqpbiwib.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gtyxwagplf.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gthymccsdl.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gtlwekuaja.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtsmayoles.html

[U114] JS：JSON 深比较
来源：http://dali.redwolf501.top/Article/details/gtdohvitfl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtauywzicn.html

[U115] JS：生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbbhwmzx.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtgovvzvyz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fzhhl.top/Article/details/gtpqfbfzue.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaslyligc.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gtjfjczxrd.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gtkdhoqyrk.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gtybbjsasm.html

npm i -D vite;  npx vite
来源：http://dali.chenjidiqi.icu/Article/details/gtiqjypadp.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gtdccvosye.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gtuxuradsv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gtdffgackg.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gtdcdfmcps.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxmiaselc.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtxxaqrodg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttiwgygkl.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gtaliundnl.html

Python ......... 252
来源：http://dali.daxiang520.top/Article/details/gtsdmwgbps.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gtuslcceci.html

JavaScript ..... 252
来源：http://dali.tanke756.top/Article/details/gtbgogzwcy.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtgkuvourz.html

Java ........... 212
来源：http://dali.redwolf501.top/Article/details/gtvzorlegi.html

Go ............. 212
来源：http://dali.iojbl.cn/Article/details/gtgkoskhbo.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtygyydltf.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtuiikbxku.html

C .............. 30
来源：http://dali.tianlin.xyz/Article/details/gturbzctsk.html

C++ ............ 30
来源：http://dali.shuidangran.top/Article/details/gtmclsgckd.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtivxxqeoy.html

Bash ........... 80
来源：http://dali.cashguo.top/Article/details/gtdwobmdee.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gtbengbpar.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtcmepfzkb.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gtnokuulxu.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gtcfnzhbyw.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gtsohlsszv.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtthlkejyh.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gtpmxlsnma.html

按章节统计：
来源：http://dali.ehwqpu.com/Article/details/gtiyqgyvgy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtwngweccq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtqcjrpvqi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gttrfrlsgx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtnjbirakj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gtcgbcdsvf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtoibxhtvo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gthwyhbqon.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gthhzyvnzi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtnglcdouc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtdzkttllg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gthizrmats.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gttnxrbhuk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtszgzteer.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduwmdvyv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gtqkeyowud.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtcznyrxjz.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gtinjlqubc.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtccmkcgye.html

S C / C++ 专题                          60
来源：http://dali.snrcjt.cn/Article/details/gtnxfclgqj.html

T 其他语言补充                          60
来源：http://dali.gotoacloud.top/Article/details/gtyusyivmz.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gtywxlqdlt.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtjxngyfcq.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gtxhyopnsa.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtdnrlhnce.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gtdnbfejnp.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsqmofjs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenzaomai.com/Article/details/gtasdlmnbk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.bjfxy.top/Article/details/gtzqguvucm.html


<!-- 参考信息 -->