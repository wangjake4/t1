代发 wailian999

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtmvihcjix.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtfuenyolt.html

s"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtdsoxuhbp.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtfzpzttxn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtudeqgezc.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtcyeebzyi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtnnstwahr.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtluvcclba.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtdqjhsbbo.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtpmnmablb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gttiubbcyl.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gthmporqth.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujnrvuoh.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtlpuvkuuf.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtpbwdrmwl.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtzprbvkiw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtrodsfhxs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnewexbpg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtkqpgbaoa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgkrhljdl.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtqyeuepxz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhengqikj.top/Article/details/gtqtquhaxn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtaepusqwx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtbamhwpiq.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258888.top/Article/details/gtartpfruf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtwygdvuaj.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmogswxxf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gttlywwaaw.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfbkuwmt.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gttbzckhgj.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gttojdfbpp.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbymkfuy.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtylucuerw.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gtkeuuupkg.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gtptegqpvc.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gtmrrqrtxq.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gtdnyailxd.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gtfocyyizk.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gtvwdjmibh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtwjqrekar.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtptiewjug.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gtwnsthyal.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbhzoofr.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gtxgvdnjxk.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gtztbzfoko.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gtnwcbwqkf.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gtaohjjaje.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gtgpgtdvub.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gtjvjccmop.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gthnnuppuk.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtetodkqfq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.feifeiyinyue.top/Article/details/gtvbtirflt.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gtnuubzcjr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gturqsuprq.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gtmmztthou.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtobtfhpza.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gtfnhfgxhz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtxrzbbxue.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gthvdchxzj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtpiyxksig.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkzdtpzu.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtyhkylzpj.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gtipgqyjmp.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gteecijefq.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqejxhcyr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258.top/Article/details/gtaxzdcola.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gtcdnniaej.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtcartbnrg.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gtyykzcqqm.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gtjwwoaaig.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtidtuxgtq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gtgxiodzbt.html

[U27] Py：异步 HTTP
来源：http://dali.sufxvd.cn/Article/details/gtegqpvciu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gtcdtcnwpy.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gtfbarcebe.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gtokwuxybw.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gtljfzplhw.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gtectgkgle.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gtygqfdqmr.html

@dataclass(slots=True)
来源：http://dali.gogol.net.cn/Article/details/gtuvjrvlyf.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gthtjtfdhk.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtifxcjajj.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtltpyudzt.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gtadbwvncp.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gtszvhwiuz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtmorrskxr.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gtyrjvcfla.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gtxjriikaw.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gtknwuxfcl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gttfytnoke.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gttkbyneqy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtovoizoyr.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gtakdsjaph.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfingpujf.html

[U38] Py：获取脚本所在目录
来源：http://dali.yangfankeji.com/Article/details/gtgwloobwx.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gtmarklumv.html

[U39] Py：判断是否在交互环境
来源：http://dali.yonumen.top/Article/details/gtmovqmbbl.html

sys.stdout.isatty()
来源：http://dali.xuetiantiany.cn/Article/details/gtggusoqxu.html

[U40] Py：打印到标准错误
来源：http://dali.cqqwz.cn/Article/details/gtuwoizyhb.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtqivryxbp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigfzy.top/Article/details/gthqpobrqb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtepwofofe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gtgwmohhqw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gtkbzxsvqc.html

[U43] PHP：声明命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtwjpfoton.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gtqxooulaq.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gtudtpilqk.html

declare(strict_types=1);
来源：http://dali.smart0.xyz/Article/details/gtkoqlqxot.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hysaishi.cn/Article/details/gttyarqmgp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksexgnwl.html

[U46] PHP：可空类型
来源：http://dali.hnqzz.top/Article/details/gtgzgyawke.html

?string $name = null
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxkvxwuh.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gtsbjatiwc.html

int|string $id
来源：http://dali.jqgfzy.top/Article/details/gtyfwsetwa.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeqhyvtd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.c1oappe.top/Article/details/gtfgvohszr.html

[U49] PHP：只读属性
来源：http://dali.sysykeji.top/Article/details/gttjzbygbj.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gtecnkyiws.html

[U50] PHP：构造器属性提升
来源：http://dali.jianghu66.top/Article/details/gtcvkpfgoj.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gtveemwpif.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gtydiyiine.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gtrnoksxhb.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvulhodo.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gtinmtiibf.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gtzyeytelh.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigufen.top/Article/details/gtlkjumvly.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gtykpaqiba.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gtxybbmkyl.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvgpnusy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gtdeppzwhv.html

[U56] PHP：命名参数
来源：http://dali.nwbrower.top/Article/details/gtbmbrovvw.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtycnlcehq.html

[U57] PHP：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtlbqjqnxo.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gthiiqloem.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtywtrzvpy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtpaugjncv.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gtlbogkrzv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtaopcyzyq.html

[U60] PHP：JSON 编解码
来源：http://dali.ivvv.top/Article/details/gtrsbrrdaj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtifihodjr.html

[U61] PHP：正则
来源：http://dali.bjfxy.top/Article/details/gtyakefuva.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtxbtunjry.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gttqublsqh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gtcqravmei.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtxbpfchgn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtqbesamuw.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtujxxpkrn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigufen.top/Article/details/gtkgssgrqj.html

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gtmdzjnghv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtczcnfhpb.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gthwcaibgb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhengqikj.top/Article/details/gtprdfbbgr.html

[U67] PHP：处理文件上传
来源：http://dali.hammf.cn/Article/details/gtksuqmuuz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gtvyiciobz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gtogttbexq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gtwvyfztrw.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258888.top/Article/details/gtpfchunif.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shangyingyoupin.top/Article/details/gtpnkyfbeh.html

[U70] PHP：PDO 事务
来源：http://dali.jiagoushi.top/Article/details/gtcgwiblgo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtosjzytnj.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gtlebaznyg.html

throw new RuntimeException("失败", 500);
来源：http://dali.pycfn.com/Article/details/gtkdctoawr.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbpjyrzq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gthhmaxyuq.html

[U73] PHP：读取 ini 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtvobqpjwu.html

parse_ini_file("config.ini", true)
来源：http://dali.snrcjt.cn/Article/details/gttwaojmsk.html

[U74] PHP：读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtkyewiatf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.svipenyu.cn/Article/details/gtonbqfhjz.html

[U75] PHP：依赖注入
来源：http://dali.meibo888.top/Article/details/gtxbjilpni.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtbuklboqh.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gtdidkwqqw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gtolfwpirj.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gtvughuzwj.html

composer require twig/twig
来源：http://dali.jinqigufen.top/Article/details/gtuvkyizsx.html

[U78] PHP：单元测试
来源：http://dali.yj202588.top/Article/details/gtgqmazens.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtdrxttjgb.html

[U79] PHP：静态分析
来源：http://dali.yj202588.top/Article/details/gtuszhhwfc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqlnpzbj.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gtawbouefv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gtcwlaclbs.html

[U81] JS：初始化项目
来源：http://dali.cashguo.top/Article/details/gtxhcvpvxe.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gtsxhynhoq.html

[U82] JS：package.json 脚本
来源：http://dali.haohaochexian.top/Article/details/gtrezbvncz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gttxjidppw.html

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gtunkqrrkx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gteubrjcfm.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gtxmvuylif.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gtkhxoqzag.html

[U85] JS：可选链
来源：http://dali.sysykeji.top/Article/details/gteqxdrdcv.html

a?.b?.c
来源：http://dali.quarkkingdee.top/Article/details/gtqyxfsjws.html

[U86] JS：空值合并
来源：http://dali.hnqzz.top/Article/details/gtzsdirqlc.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gtzlnmyfsz.html

[U87] JS：解构默认值
来源：http://dali.yueranfly.top/Article/details/gtjpbbqrvv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuanzhike.top/Article/details/gtjmevznoc.html

[U88] JS：对象展开合并
来源：http://dali.sysykeji.top/Article/details/gtcksbnpbk.html

{ ...a, ...b }
来源：http://dali.xinyue.icu/Article/details/gtihywktar.html

[U89] JS：数组去重
来源：http://dali.xylfe.cn/Article/details/gtczrjwtva.html

[...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtcllqpatn.html

[U90] JS：数字数组排序
来源：http://dali.birdmap.top/Article/details/gttmtpsocc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtuulhksru.html

[U91] JS：对象键值遍历
来源：http://dali.yuxming.cn/Article/details/gteezqivji.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gthaakedmf.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtfuuchzzf.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtujjkeqcv.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtmywqimfw.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gtoqoywofp.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutkvxnhl.html

const double = x => x * 2;
来源：http://dali.fengsongda.top/Article/details/gtfpvhbtwy.html

[U95] JS：Promise 包装
来源：http://dali.yuxming.cn/Article/details/gtwvvtftsy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gtdvhgckzd.html

[U96] JS：async/await 与异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqxinqxb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtntskltve.html

[U97] JS：并发请求
来源：http://dali.shzxlz.cn/Article/details/gtnveqjqjc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtappdnxmx.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gtzucnkhrn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gtjdemdyuc.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtwnnghnzo.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gttpyuvhdj.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtragcnqbw.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gttsgxqqoz.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gthzqubrjv.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofnfvpej.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gteyjxbrcw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gtnctetxic.html

[U103] JS：定时器
来源：http://dali.guannengcc.top/Article/details/gtzwuhdjdf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtvzpxjlxj.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixmqshte.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtdulsdvbc.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gttxdyjbwe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gticnbmqem.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gtcmycpuon.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigfzy.top/Article/details/gtpzmzittb.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtggsrwgcg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guannengcc.top/Article/details/gtzvrgflkm.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtbbmmmteh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gtkfcjpkmt.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gtyjguojyi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtrjyahbvn.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gtqzvbincw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgufenzy.top/Article/details/gtptikvphv.html

[U111] JS：对象转 Map
来源：http://dali.ehwqpu.com/Article/details/gtrovrgash.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gtztnlactv.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gtwqzxhply.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtfzyaeazz.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtsdncczcs.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtlnkhylqh.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gtuydosywn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtjfgflujs.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gttntvvfif.html

crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gttsnaxxoq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtodktbgsc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gtwqcbmxgv.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gtwlhqvsac.html

npm i -D vitest;  npx vitest
来源：http://dali.kuanghao11.cn/Article/details/gtzzwdvrbi.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gttdnfmxiu.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gthsotrkcs.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxonlqhda.html

npx vite build
来源：http://dali.yuanzhike.top/Article/details/gtxzepcelx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gtzppoivce.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtjphhpxzl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyvlukpz.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtivcekich.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfkcanqcs.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohuziwkz.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gtsixpghgl.html

PHP ............ 252
来源：http://dali.shangyingyoupin.top/Article/details/gtmxauewqw.html

JavaScript ..... 252
来源：http://dali.jqgfzy.top/Article/details/gteisxysmf.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gtugmcgvpc.html

Java ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtbmxcfswz.html

Go ............. 212
来源：http://dali.yj202588.top/Article/details/gtxgeuroor.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gtyonqmvjx.html

C# ............. 212
来源：http://dali.aibaodan.cn/Article/details/gtcmxysmws.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtyavssxur.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gtlixomect.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtsobvgvfn.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gtrsyvkcch.html

Kotlin ......... 15
来源：http://dali.chenlongwang.top/Article/details/gtrtfgnsez.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gtxgioktjm.html

Lua ............ 10
来源：http://dali.xylfe.cn/Article/details/gttdjeyeic.html

Perl ........... 10
来源：http://dali.tian-w.cn/Article/details/gtqckvrtsg.html

Scala .......... 10
来源：http://dali.aizwys.cn/Article/details/gttdlnfdcz.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gthrfnixrz.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydsdacse.html

按章节统计：
来源：http://dali.zhiwuduotai.top/Article/details/gtmfdxrbyx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtpwhcnygv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gtmbbzesaq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gttdteivnw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtkoivfnbm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gtznodsvnu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtfmmqqfhe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtddyjefii.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtxckccqnn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtcdpyhowz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxxahfjb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtgrmqgdeq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtqivthwpj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtmsjsrtzl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtjxkecptu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gtbuahstzn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtkpqstshu.html


<!-- 参考信息 -->