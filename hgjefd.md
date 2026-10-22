代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gtxipqpnri.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgakawsci.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtjualxiex.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtktflarlc.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtmnvdudzt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenlongwang.top/Article/details/gthvsfutau.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhqgnajf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtgaeqcpxp.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtutmxyxnw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gthjppqviv.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtsoguitld.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtgqejynwk.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtsexglrde.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtyakqbwoj.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gtaupjwmmp.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gttccnsqwf.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtshuxfegx.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gtxuanafmx.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtdhwcipjh.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtyxifpoou.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyrmxztm.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gtdawlsxks.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtftlrymen.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gtbaymfepa.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtndgvidhw.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtrbutyzha.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtydwctmmr.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gthvzjdsyp.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gtzbykjrzf.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtkdrfcvus.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gtwrivmzqx.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gtwxdkutzq.html

[U15] Py：高精度计时
来源：http://dali.jqgfzy.top/Article/details/gtygduytmz.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gtqpjgajlj.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gtgfpnjium.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gtxvzytwon.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gtauufzkng.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj202588.top/Article/details/gtuabkewkk.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtylcdxrlv.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtqldvhivl.html

[U19] Py：正则替换带回调
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbylvsqq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqobcdex.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtngpwiuxi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtglmhktjf.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtidzjigwp.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gttgcfsemb.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gttjbiaevh.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gtvqgzkssz.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gtmjcyxiny.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ydzc1.top/Article/details/gthcbfbfyo.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gtapstungm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtktnzmdkr.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gthrqoamzb.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gtnrbiprad.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gtmhwujtmg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gtydiaiyul.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtodcpjvdk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gtfsmvjxwm.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangtech.top/Article/details/gtubawtxsc.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gtakitzyra.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gtgeverwcn.html

@property 与 @x.setter 配合
来源：http://dali.zhixingplan.top/Article/details/gtawpjcajq.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukguwlfl.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtqgvxrbxo.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gthpgpzklm.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gttxyoyvzi.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gtggdoyrwh.html

ruff format . && ruff check --fix .
来源：http://dali.aizwys.cn/Article/details/gtyedxjxwa.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gtizbatqcy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gtqovgedgo.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gtethmwbrs.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeiauduy.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gtmkpqjovf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ybcxt.top/Article/details/gtoffdjugy.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gtdxfkkvau.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtcmogmjur.html

[U37] Py：读写 Excel
来源：http://dali.hammf.cn/Article/details/gtoplzfrlj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscndtljq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhixingplan.top/Article/details/gtnvfnbfpp.html

Path(__file__).resolve().parent
来源：http://dali.ehwqpu.com/Article/details/gtjpsfylzc.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gtohattivz.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gtbmpnkhdi.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gtzzebhsyt.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtvbiyedio.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gtshysikgu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gtabcgsndx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhongyouzk.top/Article/details/gtuzxbgrjz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gtaklkvbht.html

[U43] PHP：声明命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtshtwezqb.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gthxgnpkbq.html

[U44] PHP：开启严格类型
来源：http://dali.feifeiyinyue.top/Article/details/gtrcxnfwny.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gthfdmthfg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gtmongnldc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtnpbglyzz.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtlzoutdqy.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gtvqjsxzls.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzpkkzknm.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gtxochczkr.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gtweosiymi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gtaqocylke.html

[U49] PHP：只读属性
来源：http://dali.tianlin.xyz/Article/details/gtcrfxrtdk.html

public readonly string $name
来源：http://dali.hnxiangtu.top/Article/details/gtvunmlrxe.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gtnanpwrdh.html

public function __construct(private int $id) {}
来源：http://dali.hysaishi.cn/Article/details/gtmwhridli.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gtbxetrnux.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gtpplbasqy.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtgtzkcimi.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gtwaarfstw.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gtsboofkvx.html

$v = $a ?? $b ?? "default";
来源：http://dali.havefunace.top/Article/details/gtmvgwscbd.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gtzfjikdmg.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gtcqjtobwa.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gtmwosthpg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtgojmnhng.html

[U56] PHP：命名参数
来源：http://dali.gotoacloud.top/Article/details/gttxdxhkwp.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtnammzpft.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtfcdjntue.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtjwbikrmd.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtkbpizxby.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gtwhdvkqlm.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtvymtmrir.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtrjvxenvb.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtzwzujlfw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aizwys.cn/Article/details/gtcmhdoxin.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrloaxrnx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtupcuefsc.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gtojawkvuz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gtsvnduwow.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtbmoarbrg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtihlxfacu.html

[U64] PHP：目录遍历
来源：http://dali.chenzaomai.com/Article/details/gtjjfhzpzi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jiagoushi.top/Article/details/gtxzuqxnce.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gtdgxhmzge.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gtpfqwrfmt.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gtfifqwvwu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtceshfpzr.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gtzamjbenb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgreysxyq.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gtjigxznbu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gtegnpuwjb.html

[U69] PHP：PDO 预处理
来源：http://dali.shzxlz.cn/Article/details/gtajccrect.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gtgghuymel.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gthlfphygg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gtkfeklygb.html

[U71] PHP：抛出异常
来源：http://dali.jqgfzy.top/Article/details/gttptvykwy.html

throw new RuntimeException("失败", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtihgabqbn.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gtanltmibv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gtzilikbgg.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvmrnqcl.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtfaiumnsi.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtnobgcfbd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gtxnporiim.html

[U75] PHP：依赖注入
来源：http://dali.kuanghao11.cn/Article/details/gtyoojvdgp.html

composer require psr/container
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklruwken.html

[U76] PHP：简单路由
来源：http://dali.chenjidiqi.icu/Article/details/gtenjwxfqi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hammf.cn/Article/details/gtahvfjmzm.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gtobwdjxbt.html

composer require twig/twig
来源：http://dali.yuxming.cn/Article/details/gtfijmsxqe.html

[U78] PHP：单元测试
来源：http://dali.daxiang520.top/Article/details/gtayqhdfay.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gtedzmbxgx.html

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gtguzvitsj.html

composer require --dev phpstan/phpstan
来源：http://dali.hammf.cn/Article/details/gtixfxcxju.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrlfxpmc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shangyingyoupin.top/Article/details/gtliocrelx.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gtvbvowhox.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gtooykxupo.html

[U82] JS：package.json 脚本
来源：http://dali.jianghu66.top/Article/details/gtsnugmpim.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.redwolf501.top/Article/details/gttwticyut.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtdbkgdmbi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtipjaajwj.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gtokwooswl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daria6918.cn/Article/details/gtxvcbqrhl.html

[U85] JS：可选链
来源：http://dali.jinqigfzy.top/Article/details/gtcgzqncmk.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtooqpxriy.html

[U86] JS：空值合并
来源：http://dali.zhongyouzk.top/Article/details/gtdadqdobn.html

a ?? b
来源：http://dali.yj20258888.top/Article/details/gttlkxsrvy.html

[U87] JS：解构默认值
来源：http://dali.ehwqpu.com/Article/details/gtewksbxgq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtxeuriclm.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gtlaawkgvf.html

{ ...a, ...b }
来源：http://dali.chenjidiqi.icu/Article/details/gtkgkyehlz.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gtvotmwmva.html

[...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtxudxkllw.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtpqpftpdy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtajaqkbso.html

[U91] JS：对象键值遍历
来源：http://dali.mhx1999.top/Article/details/gtukpjyohp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cdnleiting.top/Article/details/gtzliownkq.html

[U92] JS：深拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtuvzludjb.html

structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtleibboxi.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gtmjexmrsy.html

`共 ${n} 条`
来源：http://dali.tianlin.xyz/Article/details/gtwxroznjg.html

[U94] JS：箭头函数
来源：http://dali.havefunace.top/Article/details/gtsiqwjxtb.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtpdsnouwe.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gtlctqfwkw.html

new Promise((resolve, reject) => {})
来源：http://dali.meibo888.top/Article/details/gtbsknljcp.html

[U96] JS：async/await 与异常
来源：http://dali.ppjwa.cn/Article/details/gtoxlajvep.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtosdhdaku.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtfbaekwii.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtnikkydiz.html

[U98] JS：fetch 带 JSON
来源：http://dali.dashuyun.cn/Article/details/gtoqhcasmo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gtfiegzwin.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtdqasgzam.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtaphjgyeq.html

[U100] JS：DOM 查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtngykfmux.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gtcojowpsa.html

[U101] JS：classList 操作
来源：http://dali.hysaishi.cn/Article/details/gtudglhtvl.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gtnxffdisj.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtbscogobi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtoumcrldj.html

[U103] JS：定时器
来源：http://dali.bjfxy.top/Article/details/gtjsydojjb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.0kj1m.cn/Article/details/gtvbtzvbqw.html

[U104] JS：防抖
来源：http://dali.feifeiyinyue.top/Article/details/gtibcxuoid.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtupyjohrn.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gtkgqnouhq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.svipenyu.cn/Article/details/gtvtapcxnm.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtlhtsrzau.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gtvlecqefn.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gtindwssyz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgavaycqf.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gtjspjqffa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gtfbbfkidx.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gtryrjgock.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbbeljfi.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gtxdnqeqol.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gtkgshwfhv.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteshasbmb.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gtuubdzfkn.html

[U112] JS：字符串补位
来源：http://dali.sufxvd.cn/Article/details/gttdqwgrhe.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtemebuldm.html

[U113] JS：正则替换全部
来源：http://dali.tian-w.cn/Article/details/gtrupoyhum.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtfpzmozkj.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gtpkjoddwh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtmhouasui.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtdyhhjjys.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtmxiqlunr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.c1oappe.top/Article/details/gttcqolprw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtskiliqdi.html

[U117] JS：单元测试
来源：http://dali.316326.xyz/Article/details/gtdtaglmyj.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gtvpiitasn.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gtayugpxeq.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtpcrwzosw.html

[U119] JS：生产构建
来源：http://dali.jianghu66.top/Article/details/gtkpwuhzhn.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gtvedxmbxr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gtmmyrmbke.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gtexyrrkrq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcrqaymbj.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gtpzxpehiy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcjfbymjh.html

按语言统计（条）：
来源：http://dali.c1oappe.top/Article/details/gtxpyoufgv.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtiaocmhfv.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gtxyawlgot.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtlnwjaxqw.html

TypeScript ..... 212
来源：http://dali.daxiang520.top/Article/details/gtvqcahsvp.html

Java ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gtejcdinte.html

Go ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtgblqtmpg.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtqldfqhsw.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gttfnjcpdx.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gtlvcfggmj.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gtbhvmqcgm.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtoqlwfiqx.html

Bash ........... 80
来源：http://dali.nanxuanxn.top/Article/details/gtkxiccqmq.html

Kotlin ......... 15
来源：http://dali.aizwys.cn/Article/details/gtkxrocycu.html

Swift .......... 15
来源：http://dali.gotoacloud.top/Article/details/gtktctxaah.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwuoczxy.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gtwuuvjnsz.html

Scala .......... 10
来源：http://dali.cheryme.top/Article/details/gtduyesgva.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtdzqkgsrm.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gtqsxockfp.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gtkokljllr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtqwnmbmdd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtudczqxyn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtyqxrom.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtspupoctl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sysykeji.top/Article/details/gtmnmrsjmp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtmquibsww.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtjvbheavp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gtxpbksjgy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtxdkfnbnp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gttjkvterm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtahzlndkp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtoknqayfq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gthbifdpri.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtxyxqquuk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xziqi.cn/Article/details/gtkdtihgqd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtfobvwvpz.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gtywyfmafr.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gtisaidzxt.html

S C / C++ 专题                          60
来源：http://dali.sysykeji.top/Article/details/gtsyhuyfim.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gtpbxankvl.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeutwhxk.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtwzzlqbkd.html

合计                                  2106 条
来源：http://dali.zycfv.cn/Article/details/gtabnnbnne.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtzuixgqkw.html

使用提醒
来源：http://dali.chenlongwang.top/Article/details/gtxbcqazwx.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtozcnuyqy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zdqjudy.top/Article/details/gtujryktga.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gtltkfnhmc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.redwolf501.top/Article/details/gtktykmoyr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shuidangran.top/Article/details/gtulsolczc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gtmhfgswcj.html

—— 文件结束 ——
来源：http://dali.birdmap.top/Article/details/gtbzxdvadm.html


<!-- 参考信息 -->