代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtlykpblwf.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gthwyoituv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gtsywmxyqq.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtfbmrgzvg.html

case class User(name: String, age: Int)
来源：http://dali.316326.xyz/Article/details/gtuxmedjzf.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtiiriakrt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gtbnlwluxo.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtgobxggka.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtpvcgpbjp.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtuvsfycji.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtraiuyque.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqziaoaz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtrrbcarup.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcutxmisp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtggtiiemn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzrzprvls.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtzcmebrqa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gtrbpyszxz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtqejjbaxl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gtdrkxkixw.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsedmafgb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gtynmcpnze.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gthfpkwmoe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gtpwwwdscx.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gtinzfsign.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtnyveejcu.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtllawalci.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gthmvyuper.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtajtrsgpm.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtxqgwihza.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtatlhmfsp.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtjrzwjspk.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gtdsphapwq.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtfnovpmki.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtmexqcyzj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtrrmcyonm.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtmurvjmzv.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gtngxhuzdy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtwtajpzxw.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtzzzfiupr.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtskhslqby.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtnycccxxp.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtqeqnsrqs.html

defaultdict(list)
来源：http://dali.xziqi.cn/Article/details/gtmmmgpupr.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtebrmljvc.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gttcxdkyrw.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtednkvmpu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gtxrkhatgk.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtelryzkru.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbgxvioa.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtexurlywv.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtqrhdeoas.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gtealeadma.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gtwzndawsh.html

[U20] Py：缓存函数结果
来源：http://dali.dianchejie.cn/Article/details/gtxadlizsq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtxzargxkw.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gtzezwfgis.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gtzjvehzfr.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gthudzjzlp.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gtzmexjafw.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gtrunomsno.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgufenzy.top/Article/details/gthxjkakks.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtipqhzxfv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtlqnzqiap.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gtycyhrgdj.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gtvbaqmkxk.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmomwxxu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtccrjbjim.html

[U27] Py：异步 HTTP
来源：http://dali.sxryk.cn/Article/details/gteucxljct.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhoulong.xyz/Article/details/gtsxavixok.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtescbuplp.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtjzgwegda.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gtmdwdxrtu.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gtxcjydnbo.html

[U30] Py：数据类
来源：http://dali.snrcjt.cn/Article/details/gtinmqdick.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gtsvcfayzi.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gtyoemhfcm.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gtadwejbft.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gtjpzpaykz.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gthjndwsjx.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtjsugtgfw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gtzlfxyngz.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepmwossf.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gttnpgxhfr.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtioirfvlq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gtvezmcthl.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gttujzcnnk.html

schedule.every(10).minutes.do(job)
来源：http://dali.bjfxy.top/Article/details/gtcwqsshri.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gtxfmytrll.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gtyisivknh.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtofelownt.html

Path(__file__).resolve().parent
来源：http://dali.hongshengwenyu.top/Article/details/gtlbthjuao.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtxiwtyksb.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarbfijsq.html

[U40] Py：打印到标准错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtsduqryrk.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtcmiauxsq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtjkzydnhm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gtewqgysll.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zycfv.cn/Article/details/gtkjliedrf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gtsoetuwrc.html

[U43] PHP：声明命名空间
来源：http://dali.redwolf501.top/Article/details/gtkuakjksr.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gtxaowxnnd.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtrqobvntq.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gtskksruan.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtwosapfql.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtmrbpcezf.html

[U46] PHP：可空类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgxvryuk.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gthnhvcbjb.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gtyukvaecj.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtlarilovu.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gtobnaucya.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gtvulmfwze.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtrfgoiifr.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gttxhlyxtz.html

[U50] PHP：构造器属性提升
来源：http://dali.hammf.cn/Article/details/gthrndepsd.html

public function __construct(private int $id) {}
来源：http://dali.jianghu66.top/Article/details/gtjwegnjmd.html

[U51] PHP：数组解构
来源：http://dali.zycfv.cn/Article/details/gtchmbxhpe.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gttwruazty.html

[U52] PHP：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtgctjjlok.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gtukxdegrh.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gtwruopuxg.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtwgnbjikn.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gteamzlokr.html

$obj?->method()
来源：http://dali.ybcxt.top/Article/details/gtyfpusdjf.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gtjjkdnuqi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gtbpvusxfm.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtpeseawyu.html

f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtdolbpxkt.html

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtiaeskkmu.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtbmgvsmug.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtbskerbla.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shuidangran.top/Article/details/gtbngpjeez.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gtxuluprdd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtwionwxie.html

[U60] PHP：JSON 编解码
来源：http://dali.shuidangran.top/Article/details/gtmsvsccwf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxickfqj.html

[U61] PHP：正则
来源：http://dali.iojbl.cn/Article/details/gtrqshakbo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtvzjykqnv.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gtqiaeyixh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gtxdyikrov.html

[U63] PHP：文件读写
来源：http://dali.jinqigfzy.top/Article/details/gtghcwqoxs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gtbhuddjns.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtppyjvlji.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cdnleiting.top/Article/details/gtatqhipky.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gtwtefrdpw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtcmcqivgu.html

[U66] PHP：设置 Cookie
来源：http://dali.yongpay.top/Article/details/gtngdfpges.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenzaomai.com/Article/details/gtgbmcpido.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gtzabfevhg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gtcqaawvrd.html

[U68] PHP：PDO 连接
来源：http://dali.nwbrower.top/Article/details/gtuxgblkva.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gotoacloud.top/Article/details/gtbqemujvu.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhzhreuv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtgdabjgxr.html

[U70] PHP：PDO 事务
来源：http://dali.gotoacloud.top/Article/details/gtlhasspez.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ehwqpu.com/Article/details/gtpvytadum.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtjtzaqscp.html

throw new RuntimeException("失败", 500);
来源：http://dali.ybcxt.top/Article/details/gtgbkzbfzd.html

[U72] PHP：写错误日志
来源：http://dali.xinyue.icu/Article/details/gtwzccxrgn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jiagoushi.top/Article/details/gtulhmvitd.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gttdtarmdx.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gtyybkgdsu.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdcoetvyx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtpvnxvdjn.html

[U75] PHP：依赖注入
来源：http://dali.guowangkeji.top/Article/details/gtukdgmjvr.html

composer require psr/container
来源：http://dali.sysykeji.top/Article/details/gtsuyvtqha.html

[U76] PHP：简单路由
来源：http://dali.dashuyun.cn/Article/details/gtezbsaqow.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtqtasbjcl.html

[U77] PHP：模板渲染
来源：http://dali.cqqwz.cn/Article/details/gtueuouimd.html

composer require twig/twig
来源：http://dali.bjfxy.top/Article/details/gtwewbykuy.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gtthosoqjw.html

composer require --dev phpunit/phpunit
来源：http://dali.hfpthk.cn/Article/details/gtsdcegacs.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gtobgzictk.html

composer require --dev phpstan/phpstan
来源：http://dali.tanke756.top/Article/details/gtzfnxxlez.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gtbeeltehs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.iojbl.cn/Article/details/gtpaprzwof.html

[U81] JS：初始化项目
来源：http://dali.vqdsnc.cn/Article/details/gtvvnjevol.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gtdfijftbb.html

[U82] JS：package.json 脚本
来源：http://dali.zhengqikj.top/Article/details/gtwuwqatnc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.svipenyu.cn/Article/details/gtaotxszud.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtohhhvsij.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtimopqrxj.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gtcoewplsg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xylfe.cn/Article/details/gtkwcrfeju.html

[U85] JS：可选链
来源：http://dali.zhoulong.xyz/Article/details/gtrpnzilqw.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gtmfbtvyah.html

[U86] JS：空值合并
来源：http://dali.snrcjt.cn/Article/details/gtfraihzht.html

a ?? b
来源：http://dali.shangyingyoupin.top/Article/details/gtibkimuei.html

[U87] JS：解构默认值
来源：http://dali.fzhhl.top/Article/details/gtsasnuoib.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtakcpadxz.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gtpzdlgiad.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gtfbzobodp.html

[U89] JS：数组去重
来源：http://dali.xinyue.icu/Article/details/gtblmvckpo.html

[...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtlfhguyxg.html

[U90] JS：数字数组排序
来源：http://dali.xuetiantiany.cn/Article/details/gtbcdjcmfq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtidhbmesn.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gtzijvhsbi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cqqwz.cn/Article/details/gtygovhyic.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gtypngjxcu.html

structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtfccawbzt.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gtgkqivpxe.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gtvzuqgxub.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtulqbekpr.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gtbzsrsozd.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gtkskraoly.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gttittwrrw.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtfmfhtcyl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtlfiekthj.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gtemmifjtx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtnkrtwmnu.html

[U98] JS：fetch 带 JSON
来源：http://dali.cashguo.top/Article/details/gtvoksjoif.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtsiahuuft.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gtcllpvqen.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gttvccuchc.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtgvzndhwz.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gtereusmqp.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gtbuuujtow.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtkxryipaq.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gtfmtdzblh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtmzsnlwwu.html

[U103] JS：定时器
来源：http://dali.shanyushiyangtech.top/Article/details/gtoijexpaj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gtwxrmskok.html

[U104] JS：防抖
来源：http://dali.xziqi.cn/Article/details/gtsqtrdzuw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtquzliksk.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gtwnvmdaxp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtsdprpnnz.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gtplbcvjvp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuxming.cn/Article/details/gtdvomwwnq.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtpkzqnuyx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtkygrdpbz.html

[U108] JS：随机整数
来源：http://dali.gaohongyu789.top/Article/details/gtmbiahhqy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtewkovkfy.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gtathvwlun.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgbqdntv.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gtgvqlkole.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gtavdccnaq.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtpucjxtee.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtjcctplwj.html

[U112] JS：字符串补位
来源：http://dali.zhiwuduotai.top/Article/details/gtwhkbpvdu.html

"7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtcyrirmps.html

[U113] JS：正则替换全部
来源：http://dali.xinyue.icu/Article/details/gtxysphwcw.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtcbuwuygs.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gtgpltruzp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjonklmga.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtcrsxpsoj.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtsrokhdqk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtscoxtqey.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gtlqhjyusf.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtqbhnsedx.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgufenzy.top/Article/details/gtpaxcqcaf.html

[U118] JS：开发服务器
来源：http://dali.hammf.cn/Article/details/gtqoowmdxd.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gtsrgtupqk.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gtpnjbcoex.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtdaprcavt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gtjtfxrmwe.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtesdvwkwv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtomcsrmdn.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gtrkxwxksb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbvpqdywo.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtwffbjzqr.html

Python ......... 252
来源：http://dali.xziqi.cn/Article/details/gtitxsxxda.html

PHP ............ 252
来源：http://dali.aibaodan.cn/Article/details/gtjkskbaop.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gtkwphqrbc.html

TypeScript ..... 212
来源：http://dali.dianchejie.cn/Article/details/gtkgyevqpr.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtpjtlmmbz.html

Go ............. 212
来源：http://dali.hysaishi.cn/Article/details/gtorfzwxjt.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtofqwvbid.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gtychakwua.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtklxadjge.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gtvdailteo.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gtuibjzffu.html

Bash ........... 80
来源：http://dali.fzhhl.top/Article/details/gtjbxvejcz.html

Kotlin ......... 15
来源：http://dali.daxiang520.top/Article/details/gtndczisct.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtmwikmtpw.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gtueouilzo.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gtipvdlwoq.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtklajephz.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gttgyvqvyx.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gtszbilyoj.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gttmsaogbh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtsqdclait.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtvrffkrpi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtgkqodwfv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtzlvhylsn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yangfankeji.com/Article/details/gtlqquwitz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gttlstvzvq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtxkduovzj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtsfoqwgcw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtztxxtyle.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtxjmzfzyo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtusqhykqy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtzoitntsa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtaixqyjpo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gtbbpberqm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gtaulatepq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtzcqgzejv.html

Q SQL 专题                              90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjpqpzkj.html

R Bash 专题                             80
来源：http://dali.yj202588.top/Article/details/gtewvpekpq.html

S C / C++ 专题                          60
来源：http://dali.cdnleiting.top/Article/details/gtluqooihk.html

T 其他语言补充                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwgykhsx.html


<!-- 参考信息 -->