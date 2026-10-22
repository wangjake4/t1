代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qocsqbpx.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gt2elgsaqwr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gt2vojikqhs.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gt2radqbwrp.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2dcmconeu.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2nzuffmzz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gt2xhrfjuwu.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2uofjpnzm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwiyxbmh.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gt2yjajfnmx.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2ajizmwbx.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhgxuogh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gt2uzdqvdlu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2cfwtcckq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gt2dmfjvszv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwxtuwwd.html

[U01] Py：创建虚拟环境
来源：http://dali.shuidangran.top/Article/details/gt2ldtwznvg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gt2eypyfzuo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gt2tverliuq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gt2bsuqqxrj.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gt2ejfqqutj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gt2qsdyfuua.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gt2utnmlbkk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gt2ewbpepoi.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gt2eyklfagu.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2eyxgednv.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2hkqqdsih.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gt2mliatfoi.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gt2gwalbcvq.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gt2jmxajzju.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gt2nhosmhyw.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gt2hatfqhti.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gt2oripyapk.html

max(d, key=d.get)
来源：http://dali.svipenyu.cn/Article/details/gt2ntzmnxpv.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkwdrqdl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gt2sqezyayo.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gt2qgsrvlgi.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gt2ahlmbjpu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gt2zbtnzukq.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvdpxiqi.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gt2mbqvxnja.html

deque(maxlen=10)
来源：http://dali.jinqigufen.top/Article/details/gt2ktxjsxby.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gt2ndqahljm.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myxjobtr.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gt2adqrkznr.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gt2xwutorxs.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gt2xxxykaoa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2mlmpdkkg.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2cacaodhx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gt2bfqziivt.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gt2jjmcbmrb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bidhyhvz.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gt2vbiugohq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gt2wslqoqhu.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gt2xslhzqni.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shuidangran.top/Article/details/gt2qgtwlzuh.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gt2wykwxtua.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gt2szoyrwyl.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gt2colnibwh.html

list(zip(*m))
来源：http://dali.yuxming.cn/Article/details/gt2ivbvhvkw.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gt2weivvpah.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.smart0.xyz/Article/details/gt2zlyuokht.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gt2ngychsxv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gt2lxnqbakv.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiclybni.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gt2jzynjxnb.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2tcynrweu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kiqdnsro.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gt2ryfpevev.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gt2qkuwujek.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gt2ryhcczzq.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gt2bqadkxak.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gt2kkdkpegm.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gt2jrmztvzi.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gt2luullmlb.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gt2ihrcylgf.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gt2zrkqeqaf.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gt2cbtidujg.html

[U32] Py：代码格式化
来源：http://dali.zdqjudy.top/Article/details/gt2waejhwft.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gt2huhzfizo.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gt2xagcnbvb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gt2gadmbsib.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfjperrw.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gt2jatnzvrv.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gt2csqzfhng.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gt2xyapjcvm.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2siwkwctd.html

schedule.every(10).minutes.do(job)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hstdooji.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gt2sencveko.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnbgpiou.html

[U38] Py：获取脚本所在目录
来源：http://dali.9152youxi.cn/Article/details/gt2bsxtsbol.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gt2mmxuakgi.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gt2wtvwmfxp.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gt2ewsikzcr.html

[U40] Py：打印到标准错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2whrnqpgq.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gt2lovhvgme.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2rusvqxro.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gt2eqzbxtyy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aibaodan.cn/Article/details/gt2emyzpbsc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gt2zemqlhiq.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gt2ibetailv.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gt2snqihbqt.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gt2tisxtgov.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gt2aecbgssx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2fancprhv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2ymjbspep.html

[U46] PHP：可空类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwywfofn.html

?string $name = null
来源：http://dali.redwolf501.top/Article/details/gt2mebnbjch.html

[U47] PHP：联合类型
来源：http://dali.ehwqpu.com/Article/details/gt2dzqrseep.html

int|string $id
来源：http://dali.fzhhl.top/Article/details/gt2bjzzncrn.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caucklvf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zdqjudy.top/Article/details/gt2tetrlykf.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gt2ytrqfaom.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gt2kgspimxm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gt2ohatmpmo.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewmzxydb.html

[U51] PHP：数组解构
来源：http://dali.zdqjudy.top/Article/details/gt2whpffgry.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gt2rxmlhhec.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2nmrvpmjh.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2gmgwdips.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gt2wchcswsj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gt2nabadrzn.html

[U54] PHP：空安全调用
来源：http://dali.aibaodan.cn/Article/details/gt2bimjczip.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gt2lvquzqrd.html

[U55] PHP：match 表达式
来源：http://dali.0kj1m.cn/Article/details/gt2ebreteqm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gt2qoyjbted.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jiszncfb.html

f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2biybjkkq.html

[U57] PHP：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2ooqigjoc.html

"值: {$a}"
来源：http://dali.tian-w.cn/Article/details/gt2fozankrp.html

[U58] PHP：数组三件套
来源：http://dali.cucudq.cn/Article/details/gt2vqrvfoxm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2egkjojlp.html

[U59] PHP：自定义排序
来源：http://dali.tanke756.top/Article/details/gt2eymvkfbp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2hcfdkggc.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gt2ewjlntgy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gt2tforcjlk.html

[U61] PHP：正则
来源：http://dali.smart0.xyz/Article/details/gt2ylhqairx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ymbwgyrx.html

[U62] PHP：日期对象
来源：http://dali.nwbrower.top/Article/details/gt2hklvqdmy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gt2fdllpmau.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gt2jrlnkega.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gahfhegt.html

[U64] PHP：目录遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2xoyscknt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.birdmap.top/Article/details/gt2pyydsuuh.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gt2qpwobpov.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2ehmyqovr.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gt2ijpsgika.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufrhufgd.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gt2uoulxdby.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yueranfly.top/Article/details/gt2kymbjshc.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gt2aduvvfnx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gt2omsclycl.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gt2zhikvkjy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gt2fzxodlgf.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gt2xebovywg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.svipenyu.cn/Article/details/gt2qvrgramz.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2ayzvgpfu.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtuehxeq.html

[U72] PHP：写错误日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2evyzfqtx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gt2opjdqcnx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zycfv.cn/Article/details/gt2bcppkryv.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gt2rvtoooeb.html

[U74] PHP：读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2ntjvkymu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gt2nhrsbvpk.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gt2cazidsun.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gt2vzgejtgu.html

[U76] PHP：简单路由
来源：http://dali.yueranfly.top/Article/details/gt2rxomazwc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xylfe.cn/Article/details/gt2nqeofmfj.html

[U77] PHP：模板渲染
来源：http://dali.ppjwa.cn/Article/details/gt2pemlrajj.html

composer require twig/twig
来源：http://dali.aibaodan.cn/Article/details/gt2ijzxrbfa.html

[U78] PHP：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjktonjs.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gt2dngyknwf.html

[U79] PHP：静态分析
来源：http://dali.aizwys.cn/Article/details/gt2scxyoimx.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gt2anlfhxya.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqhxsyqu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ppjwa.cn/Article/details/gt2mzxamxkc.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gt2kffrxpwg.html

npm init -y;  npm i express
来源：http://dali.ppjwa.cn/Article/details/gt2ctzwzpwb.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gt2lquamsyw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ivvv.top/Article/details/gt2engljavq.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gt2ezlwargm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gt2ynvhvwvx.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gt2gesqigyt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gt2jpqoukvj.html

[U85] JS：可选链
来源：http://dali.xinyue.icu/Article/details/gt2clrcwdyz.html

a?.b?.c
来源：http://dali.snrcjt.cn/Article/details/gt2aoabghdd.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gt2lnwxailt.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gt2sreznxur.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gt2wjysskbv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erwotkia.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gt2jffdsiac.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gt2lntpfdkr.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gt2jxbxbglb.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2hrxtzbes.html

[U90] JS：数字数组排序
来源：http://dali.havefunace.top/Article/details/gt2ioomgfpo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2fruowxwj.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gt2esrqwbvd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gt2zsztoqig.html

[U92] JS：深拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2lqwnwzbb.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2cszmvymr.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gt2dbordlxn.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gt2onaodpvk.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gt2lrhpojqe.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gt2eiwxkbzh.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gt2mijalgbv.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2mtzgnsfz.html

[U96] JS：async/await 与异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpixypua.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xmcmqjvu.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gt2nkxmjkni.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntqebqux.html

[U98] JS：fetch 带 JSON
来源：http://dali.cucudq.cn/Article/details/gt2dhzlggex.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.birdmap.top/Article/details/gt2umlmgvhg.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gt2cranohro.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2awlvsatt.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gt2xsqhidrm.html

document.querySelector(".item")
来源：http://dali.andypj.xyz/Article/details/gt2wmmbfmcd.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gt2vbapytbh.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gt2hxhpnvph.html

[U102] JS：本地存储
来源：http://dali.guannengcc.top/Article/details/gt2ujatdnui.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258.top/Article/details/gt2pcwqpufb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkjfmch.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxnntonl.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gt2ccxmplww.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yppifhts.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gt2jqcndukf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gt2ovimhnun.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrnjonhj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ydzc1.top/Article/details/gt2fyergunh.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2dwgobueu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2rsukzrth.html

[U108] JS：随机整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkyihlpe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jianghu66.top/Article/details/gt2kcbcdblh.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhuhzgra.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxfmimqs.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gt2kvrdlhts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkigrpoa.html

[U111] JS：对象转 Map
来源：http://dali.tian-w.cn/Article/details/gt2oubvsnjp.html

new Map(Object.entries(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfbyubon.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gt2dvavqpur.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2bwxvksev.html

[U113] JS：正则替换全部
来源：http://dali.pycfn.com/Article/details/gt2wpznyixc.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2kbgrlnpk.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gt2rbprtlbr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqywuybi.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2yeulbrxq.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2rokogijo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gt2dbgqumdq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gt2imighkig.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gt2qakpyclf.html

npm i -D vitest;  npx vitest
来源：http://dali.316326.xyz/Article/details/gt2bzrqxryl.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gt2hhohxlaj.html

npm i -D vite;  npx vite
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwqgpkzw.html

[U119] JS：生产构建
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtsxmzmo.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gt2lodutokq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gt2fgypyfby.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gt2ahiecysa.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2pmgvfzjo.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gt2jlenzfoh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gwhjgjfw.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gt2nhmkwxmv.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gt2hrenkgyi.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2acfgzrlg.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gt2wkalsovz.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gt2igdscotp.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gt2uwuviazn.html

Go ............. 212
来源：http://dali.andypj.xyz/Article/details/gt2pbyufjpc.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gt2mevntbgv.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gt2pppyyvrb.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjjpneew.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gt2zujqoxzm.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gt2cgomzpyc.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdsdqokp.html

Kotlin ......... 15
来源：http://dali.yj202588.top/Article/details/gt2poojdgsu.html

Swift .......... 15
来源：http://dali.tianlin.xyz/Article/details/gt2gxrdxeml.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gt2reooiqvz.html

Perl ........... 10
来源：http://dali.0kj1m.cn/Article/details/gt2zkjtnnpq.html

Scala .......... 10
来源：http://dali.cucudq.cn/Article/details/gt2jvtftcuu.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2kliwyhfu.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gt2iarluhhn.html

按章节统计：
来源：http://dali.hfpthk.cn/Article/details/gt2clrotthp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gt2xyvgodik.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2ggjtzkmq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gt2kaqaewtw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gt2lpryeeil.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.9152youxi.cn/Article/details/gt2rggcnaro.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gt2hpyegpoe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gt2bgqhtcun.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gt2snmaknvr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2wofgvevu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2zobirgnu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2qsbfnusx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2jcahpbue.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gt2jbhcuujy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gt2kiextver.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gt2qznvsilk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2nxmfztlv.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gt2lperxric.html

R Bash 专题                             80
来源：http://dali.yj20258.top/Article/details/gt2lkyvdbal.html

S C / C++ 专题                          60
来源：http://dali.havefunace.top/Article/details/gt2rlauspar.html

T 其他语言补充                          60
来源：http://dali.zycfv.cn/Article/details/gt2gfqkoasx.html


<!-- 参考信息 -->