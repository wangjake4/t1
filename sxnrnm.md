代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gtdkqqbcln.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtlaswvsrf.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtxlxpjesi.html

[T60] Scala：折叠
来源：http://dali.zhengqikj.top/Article/details/gtzchbvjba.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtnkykojgy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttbuhqeue.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtgsuhvzye.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtuvtpwjue.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtqsiyxruh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtqrvxcqng.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtuuocnmsv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtmtaqafrv.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gttucxyyab.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtzlqpuktn.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtscozxaet.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gtsuzuvvnj.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtclxbdiyb.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtfkslehbk.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gtqtkmsuuv.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gtzwfpnshk.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtvsiappca.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtictjybvj.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gtmmqvhwjq.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gtbhlqtbwu.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtwmofqunw.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtokjxbzaa.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gtpnynudao.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gtwejnuwlc.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gtqjpujpno.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtivsnwxup.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtotrhdeqb.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtwpuprgvx.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtvaawvnfw.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gtujmwqazl.html

[U14] Py：分组收集到列表
来源：http://dali.yangfankeji.com/Article/details/gtjyzgzcyb.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gtjgxwyphq.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gtvqwyphdl.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxjmmsdk.html

[U16] Py：命令行参数解析
来源：http://dali.feifeiyinyue.top/Article/details/gtkmwtbfjx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gthsfuliza.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtbwzsrmrk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gtfxayyxsj.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtjalvlgdw.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gtvefmflrs.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gtxqcjixxv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gtprkuefgd.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtkizyhdox.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtgotzqixx.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbawojpl.html

@contextlib.contextmanager
来源：http://dali.andypj.xyz/Article/details/gtzmpecmnv.html

[U22] Py：矩阵转置
来源：http://dali.sysykeji.top/Article/details/gtqzmhkwpf.html

list(zip(*m))
来源：http://dali.fzhhl.top/Article/details/gtvwuvsvbg.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gtqscthmbm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gtaobbtkan.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gtnutmltwo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtonocvhmg.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gteigmupxp.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtkwzpnwre.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gtoyfittzj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gtprdxtlfq.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gtzskzkpdp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtctjvxdkq.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtxlxmebkd.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtgyeanbmp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtszgsbrzn.html

@property 与 @x.setter 配合
来源：http://dali.jinghuilouyu.cn/Article/details/gtznpdqqoz.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtgsaxnkvo.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gttgwdligw.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtgfzmgmno.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtxjmusjus.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gtgdrcsyeg.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gtyqnznfti.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gtxdqblhsc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hongshengwenyu.top/Article/details/gtbnhrtaoa.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gtenvtpwtk.html

chardet.detect(raw)
来源：http://dali.316326.xyz/Article/details/gtfuavuspr.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gtakbsqlux.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtnxznicbd.html

[U36] Py：定时任务
来源：http://dali.hnqzz.top/Article/details/gtnihervjp.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gtqbvjzzuw.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gtmgevnalq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gthktolnsy.html

[U38] Py：获取脚本所在目录
来源：http://dali.hysaishi.cn/Article/details/gtuqbtrwhd.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtmwmugvfc.html

[U39] Py：判断是否在交互环境
来源：http://dali.redwolf501.top/Article/details/gtwematmng.html

sys.stdout.isatty()
来源：http://dali.xylfe.cn/Article/details/gtethcwauv.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gttxdhghhb.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdjxhczc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gtusyfklgz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.haohaochexian.top/Article/details/gtscmrhjwi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gtlzzzlene.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gtoppjidfy.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gtcxbvoxhk.html

namespace App\Http;
来源：http://dali.vqdsnc.cn/Article/details/gtxtouuhua.html

[U44] PHP：开启严格类型
来源：http://dali.chenzaomai.com/Article/details/gtspdjhvgf.html

declare(strict_types=1);
来源：http://dali.xylfe.cn/Article/details/gttxuddvyd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gtcwiqbypn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtybvwccsz.html

[U46] PHP：可空类型
来源：http://dali.c1oappe.top/Article/details/gtoyvxazha.html

?string $name = null
来源：http://dali.iojbl.cn/Article/details/gtzucqezkv.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gtehgerhqo.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gtuytraswn.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gtixbdmixk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gtmxnqwiuz.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gtysspvgda.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gthzdabqwu.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gtrnoahzmq.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtyswdqdjf.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtsxpmnezq.html

[$a, $b] = $arr;
来源：http://dali.mhx1999.top/Article/details/gtobgdbmmn.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjsdldyi.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gttdcpybge.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtpmufmsmz.html

$v = $a ?? $b ?? "default";
来源：http://dali.havefunace.top/Article/details/gtjfcrivdd.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gtfrcktxpy.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtnsakmpzj.html

[U55] PHP：match 表达式
来源：http://dali.jinqigufen.top/Article/details/gtxabytxhh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtivgedjyx.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtbzdlpeqp.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtsnfgymkb.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtwmpkaauk.html

"值: {$a}"
来源：http://dali.zhoulong.xyz/Article/details/gtcvqyxllm.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gtfbtantck.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gtcemmykkv.html

[U59] PHP：自定义排序
来源：http://dali.gaohongyu789.top/Article/details/gtjrahmlxh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtaujvgymy.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gtddhssilb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gtbtwijbsb.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gtzxdqyxya.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtbflqkdqg.html

[U62] PHP：日期对象
来源：http://dali.hnqzz.top/Article/details/gtsweugzwn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jiagoushi.top/Article/details/gtxrlurbii.html

[U63] PHP：文件读写
来源：http://dali.sysykeji.top/Article/details/gtpfviylem.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtyjjcjgcs.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtbajfxdxh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gthqlwpamg.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtwynpyyyt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjauypkv.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtqpulgofz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gtxpynoqqi.html

[U67] PHP：处理文件上传
来源：http://dali.daria6918.cn/Article/details/gthvkihacs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shuidangran.top/Article/details/gtayoiyhnh.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gtbadlhdxk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sysykeji.top/Article/details/gtnrzvojdw.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gtyihynuej.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtzriwyalv.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gtrkasmrtd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtxbwbniql.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gtbextvydi.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtcwyfcznw.html

[U72] PHP：写错误日志
来源：http://dali.chenlongwang.top/Article/details/gtevwfgbig.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gtijnqtdnx.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gttbotgtoo.html

parse_ini_file("config.ini", true)
来源：http://dali.hysaishi.cn/Article/details/gttwedpshh.html

[U74] PHP：读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtautcobaj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuanzx.com/Article/details/gtqchfalco.html

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gtgmaipsxl.html

composer require psr/container
来源：http://dali.daria6918.cn/Article/details/gtqqrxymib.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtwkhrnrte.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hammf.cn/Article/details/gtzimgmytg.html

[U77] PHP：模板渲染
来源：http://dali.yuanzhike.top/Article/details/gtjvrxvjyj.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gtcfvcwxlm.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gtxsgusnzl.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gtjydwdxna.html

[U79] PHP：静态分析
来源：http://dali.wangshuangyany.cn/Article/details/gtmlipjrst.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gttidonarm.html

[U80] PHP：代码规范修复
来源：http://dali.ivvv.top/Article/details/gtcadmuwhi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhixingplan.top/Article/details/gtqbrvjatc.html

[U81] JS：初始化项目
来源：http://dali.hysaishi.cn/Article/details/gtydjgkzsu.html

npm init -y;  npm i express
来源：http://dali.iojbl.cn/Article/details/gtozqizjhr.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gteinsrrji.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gtxbucsumt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhiwuduotai.top/Article/details/gtbowcngdf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnevrsvrt.html

[U84] JS：CommonJS 写法
来源：http://dali.shuidangran.top/Article/details/gtgskvdnlx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gtntdoohia.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gtnzcdrnsf.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gtjjiqvyxe.html

[U86] JS：空值合并
来源：http://dali.hammf.cn/Article/details/gtvrugyugj.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gtqnthoxjm.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtissoehrt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgazgofi.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtslvbdbqu.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtapspdlnb.html

[U89] JS：数组去重
来源：http://dali.gotoacloud.top/Article/details/gtsvrewkyq.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtdwmalyvg.html

[U90] JS：数字数组排序
来源：http://dali.gotoacloud.top/Article/details/gtopyljpza.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtelikrirf.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtemekqgah.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangdashe.top/Article/details/gtrjjlpfkr.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxgrylmw.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtdrsucrnv.html

[U93] JS：模板字符串
来源：http://dali.ivvv.top/Article/details/gtfajpyxbs.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gtzimllerv.html

[U94] JS：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsbooqop.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtjaaywkxv.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwavaaeeo.html

new Promise((resolve, reject) => {})
来源：http://dali.dianchejie.cn/Article/details/gtbnjybibq.html

[U96] JS：async/await 与异常
来源：http://dali.yj202588.top/Article/details/gtzxfbwdbn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtxnhyiptt.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlskykwiy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoigautxj.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gtnfnveqwr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shzxlz.cn/Article/details/gtlteanase.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gtomvfxbct.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gtlvuidomi.html

[U100] JS：DOM 查询
来源：http://dali.kuanghao11.cn/Article/details/gtingujkms.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtqxwtbfrn.html

[U101] JS：classList 操作
来源：http://dali.guannengcc.top/Article/details/gtxrqmxtef.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gteoqttmqo.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gtbgzxfwei.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtrtchwgdt.html

[U103] JS：定时器
来源：http://dali.chenzaomai.com/Article/details/gtljfrggno.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gtvjydyjyi.html

[U104] JS：防抖
来源：http://dali.fzhhl.top/Article/details/gtqqebctkf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtdjsqxkbs.html

[U105] JS：节流
来源：http://dali.yongpay.top/Article/details/gtzmugsphz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gtqimlgxtp.html

[U106] JS：日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtbklqrvuh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guowangkeji.top/Article/details/gttpatwseu.html

[U107] JS：数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtgsqjozbd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtvaywecgh.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gtsclhsjio.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjszoxha.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtqniznycw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtpsvfkkdz.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxhngdbj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gtcqtlycol.html

[U111] JS：对象转 Map
来源：http://dali.vqdsnc.cn/Article/details/gtckyfhwpg.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gtsmezqznk.html

[U112] JS：字符串补位
来源：http://dali.yj20258888.top/Article/details/gtivxygsik.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtalrmjnmz.html

[U113] JS：正则替换全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwirgeim.html

s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzlbtqpu.html

[U114] JS：JSON 深比较
来源：http://dali.wangshuangyany.cn/Article/details/gtuouzzyxh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtdksnrxzw.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtmszwwcsg.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtrghnmmiw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtacsdyzlu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gtlubpljkr.html

[U117] JS：单元测试
来源：http://dali.fzhhl.top/Article/details/gtbklmyhwa.html

npm i -D vitest;  npx vitest
来源：http://dali.shangyingyoupin.top/Article/details/gtkrvjmfsq.html

[U118] JS：开发服务器
来源：http://dali.shangyingyoupin.top/Article/details/gtmfzsmhtj.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gtyxiovaud.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtjygwiion.html

npx vite build
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdtyqfdf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtcuafyerd.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gtdyufkvye.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgukbvgsy.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtfrgyntpe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdonameqr.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtabyhnong.html

Python ......... 252
来源：http://dali.jqgufenzy.top/Article/details/gtocnyaoaq.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gtzkcysdhu.html

JavaScript ..... 252
来源：http://dali.shuidangran.top/Article/details/gtrycdrxlc.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gtnroqvzir.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtgyvhrbvf.html

Go ............. 212
来源：http://dali.iojbl.cn/Article/details/gttoknbrfk.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtaupklalm.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gtlvqhkhfi.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gtgxbmlzpj.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gtsngwuqgw.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gtzqeqkdcd.html

Bash ........... 80
来源：http://dali.jinghuilouyu.cn/Article/details/gtviaqnaeo.html

Kotlin ......... 15
来源：http://dali.aibaodan.cn/Article/details/gtqqijusyi.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gttzkahjln.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtrfefcczp.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtaqgxmgzw.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtdvpympvz.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtdfynlfko.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtegfxjods.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gtjqhzipcx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwolvxfam.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtkmktmqbw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtbwyrachn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtrcmziazl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gthhblzxch.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtflpjuiea.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtebfizgek.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtdonvmgyk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtjygfgeak.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtgntldtdo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtmsgacdgp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtppncuzxm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtudqkqbyv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gteabbibto.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fzhhl.top/Article/details/gtbrjunntx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtqharvnja.html

Q SQL 专题                              90
来源：http://dali.jinqigfzy.top/Article/details/gtnhyrktgi.html

R Bash 专题                             80
来源：http://dali.meibo888.top/Article/details/gtdtfxdxjw.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtdrhwqbmd.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtsbefjeoe.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gtuoiqbnhs.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtkxdgydjs.html

合计                                  2106 条
来源：http://dali.zycfv.cn/Article/details/gtqdzuxjza.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtwakgpsku.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gtcegpkvhj.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtxmbebvke.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.0kj1m.cn/Article/details/gtsyohpqgw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gtvkztqtdz.html


<!-- 参考信息 -->