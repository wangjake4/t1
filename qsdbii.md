代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtnrnpxjrj.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtorpudcnj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sxryk.cn/Article/details/gtlvqfmvog.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtvjrevrnv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyzpzvtg.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtjvtutblo.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtabrplylt.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtgjgfufqb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtxuadywgg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxtbcvmqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtxxgfykng.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzopxgwzi.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gtwhkxdvzp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtbeyickoe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtiuhbvxab.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gtocvljlbe.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtzbkjbqzx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sxryk.cn/Article/details/gtaspudfvf.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtgjzkzlml.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gttayhaggu.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtjymyzptb.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtsqhyxaoe.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlhixwxc.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gtixcmedsu.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtlmlbrgwv.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtufnfjira.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayqfvsbk.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gtpogoehap.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gtyacghtew.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtshgxlkta.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtkklilxan.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtducixgmi.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gtsmqvmlks.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gtbqodpfdz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gtptzboirm.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtxcgwcyzi.html

[U13] Py：固定长度队列
来源：http://dali.shangyingyoupin.top/Article/details/gtmeavfefz.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gtevmdehpr.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtjjrtvmcv.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtyssbuxew.html

[U15] Py：高精度计时
来源：http://dali.wangdashe.top/Article/details/gtelonpuys.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtrsimynyr.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gtbuhflnoh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gtbeclvjqr.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtsxiqoycn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutwwofjz.html

[U18] Py：预编译正则
来源：http://dali.c1oappe.top/Article/details/gtrnsjwzde.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjbizcex.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gttyuzznij.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtgonpijgs.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtykahmemy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gtwxzqiowr.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtxwbgqnde.html

@contextlib.contextmanager
来源：http://dali.yj20258888.top/Article/details/gtozwewwbt.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gtvwgcxfdh.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtdbxxrbwf.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gtkdzbsnpu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuanzx.com/Article/details/gtxhfnvxxy.html

[U24] Py：路径操作
来源：http://dali.hysaishi.cn/Article/details/gtevtszbvd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtepkundtf.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gtengkdkss.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gtskaqoary.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gtdquteqgb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtwdkmddhs.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gtoczaqved.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gtirxgaoyi.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtmamctfht.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtbffgmhht.html

[U29] Py：属性校验
来源：http://dali.shzxlz.cn/Article/details/gtbhxvemyl.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtuphvwtja.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtlrjxlqui.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gtfozcnzkx.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gtpfnkzmzd.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gtxwsshrkm.html

[U32] Py：代码格式化
来源：http://dali.jianghu66.top/Article/details/gttaivqitu.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigfzy.top/Article/details/gtpnipnfrk.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gtgoeeuuis.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtnrlflbbs.html

[U34] Py：判断编码
来源：http://dali.ydzc1.top/Article/details/gtbginwdav.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtrkwztycn.html

[U35] Py：发送邮件
来源：http://dali.kuanghao11.cn/Article/details/gtdbhlisqn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtacyxvefs.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gtijypkbsz.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gtxbomqinp.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gtvfiamqyv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gtqhgqhuub.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gtzunksoyr.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gtujscfdes.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gtynfwgwqt.html

sys.stdout.isatty()
来源：http://dali.jqgfzy.top/Article/details/gtibaxzcds.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gtfshdwejh.html

print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtlrrbodba.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gtairvilvs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gttcklciqi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cashguo.top/Article/details/gtcrkygddx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gtcnjsezbp.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gtfktkzobw.html

namespace App\Http;
来源：http://dali.ybcxt.top/Article/details/gtraxwzxrs.html

[U44] PHP：开启严格类型
来源：http://dali.feifeiyinyue.top/Article/details/gtyurfgnzw.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gtcvniaddk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.havefunace.top/Article/details/gtwxhtckwr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtiviisjrx.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gtpzdjhknn.html

?string $name = null
来源：http://dali.316326.xyz/Article/details/gtnksuriol.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gtvajldeng.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gtgldaksav.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gtttprqfww.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gttdzzkcwr.html

[U49] PHP：只读属性
来源：http://dali.zhengqikj.top/Article/details/gtgvdflfll.html

public readonly string $name
来源：http://dali.fzhhl.top/Article/details/gtypdsyhrp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gtptlhbatw.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtcglxlvpj.html

[U51] PHP：数组解构
来源：http://dali.jiagoushi.top/Article/details/gtimyqbntf.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gtqncuzxft.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtfpyhtnbc.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtwqmjktkf.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtdfmrpeqk.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbpqfgwt.html

[U54] PHP：空安全调用
来源：http://dali.birdmap.top/Article/details/gteptuecqv.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gtbamvrxoy.html

[U55] PHP：match 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtlaazcmbc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtsywzfszz.html

[U56] PHP：命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhmkelrb.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvbntxzm.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gtbkatkhaq.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gtgxduadhy.html

[U58] PHP：数组三件套
来源：http://dali.jlsjyb.cn/Article/details/gtyhtykqwh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfjmwacj.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gteybkkqaz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtojqyqjya.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gtclfllplj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffkyxgew.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gttmsxftxw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtolxxpgew.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gthvpvtmeg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gtfdwwrsxn.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gtxffarovv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gttnmaiddx.html

[U64] PHP：目录遍历
来源：http://dali.cheryme.top/Article/details/gtvduimqtr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gtlqnfzzzc.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdsivqhz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtvxbqkzqn.html

[U66] PHP：设置 Cookie
来源：http://dali.ybcxt.top/Article/details/gtjiaxfeqb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zdqjudy.top/Article/details/gthsgmplvn.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtnnqmyvmq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.snrcjt.cn/Article/details/gtyktucyfe.html

[U68] PHP：PDO 连接
来源：http://dali.tanke756.top/Article/details/gtdmsgreep.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gtnuraqobb.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gtgnfxtwgs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gtdlmjyuim.html

[U70] PHP：PDO 事务
来源：http://dali.fengsongda.top/Article/details/gtbecsxjvm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.0kj1m.cn/Article/details/gtzeeutwlx.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gtxqhjqffk.html

throw new RuntimeException("失败", 500);
来源：http://dali.xinyue.icu/Article/details/gtifadpziz.html

[U72] PHP：写错误日志
来源：http://dali.jqgufenzy.top/Article/details/gthebnwoej.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtdqatnrwx.html

[U73] PHP：读取 ini 配置
来源：http://dali.jqgufenzy.top/Article/details/gtimpuhgyn.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gthsqfdmgk.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtjhosygzi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jianghu66.top/Article/details/gtmwtvsktg.html

[U75] PHP：依赖注入
来源：http://dali.yongpay.top/Article/details/gtbtaxszur.html

composer require psr/container
来源：http://dali.mhx1999.top/Article/details/gtvcvfdvut.html

[U76] PHP：简单路由
来源：http://dali.andypj.xyz/Article/details/gtkpcajflt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gtduttupub.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtewuopzqj.html

composer require twig/twig
来源：http://dali.yanxiufei.cn/Article/details/gtavvoapdz.html

[U78] PHP：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gtkfewgukb.html

composer require --dev phpunit/phpunit
来源：http://dali.gotoacloud.top/Article/details/gtenxroicy.html

[U79] PHP：静态分析
来源：http://dali.zhongyouzk.top/Article/details/gtqecnhrln.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gtctcvxeec.html

[U80] PHP：代码规范修复
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujzicyxl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gtsaviydoo.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtercyrtbr.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gtfesrglzx.html

[U82] JS：package.json 脚本
来源：http://dali.nanxinkj.top/Article/details/gtsyfgdkri.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmcirfcr.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangshuangyany.cn/Article/details/gtqlnikghm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowytdxqc.html

[U84] JS：CommonJS 写法
来源：http://dali.xinyue.icu/Article/details/gtgkkjbmjd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gtfkokrdsr.html

[U85] JS：可选链
来源：http://dali.ybcxt.top/Article/details/gtgzcdxqnl.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gtkfsnogvz.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtlfmfwgqq.html

a ?? b
来源：http://dali.hnqzz.top/Article/details/gtmjfempps.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gtvigntotb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gtlfmpqsaa.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gtyybidevb.html

{ ...a, ...b }
来源：http://dali.tanke756.top/Article/details/gtghsrkifj.html

[U89] JS：数组去重
来源：http://dali.shangyingyoupin.top/Article/details/gtzaqgtzzc.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtczbscqqp.html

[U90] JS：数字数组排序
来源：http://dali.hongshengwenyu.top/Article/details/gtotuzwqrh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtwfcvkfzq.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gteunfxhfx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhiwuduotai.top/Article/details/gtjigarzjc.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtvnfngroz.html

structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzkamfvug.html

[U93] JS：模板字符串
来源：http://dali.jinqigufen.top/Article/details/gttsemrocf.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gthvrvhyzm.html

[U94] JS：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gtqnhjuerw.html

const double = x => x * 2;
来源：http://dali.iojbl.cn/Article/details/gtrmjdcxgq.html

[U95] JS：Promise 包装
来源：http://dali.jianghu66.top/Article/details/gtldlynkwz.html

new Promise((resolve, reject) => {})
来源：http://dali.kuanghao11.cn/Article/details/gtwaatxxxo.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gtcrbizhsv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtatfxxiit.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gtcdegzfme.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtfewyqyzv.html

[U98] JS：fetch 带 JSON
来源：http://dali.havefunace.top/Article/details/gtkbyxdutb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtdoixixxt.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gtlzehflau.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtwgfmslkk.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtkzdaojfg.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gterypxadq.html

[U101] JS：classList 操作
来源：http://dali.dashuyun.cn/Article/details/gtgsanxqjg.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gtmbwnjoau.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmyajsjj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtamjwfizh.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gtqtlbkmsu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gtzoxegxfh.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gtupmlexpj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtpbrrmssx.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gtbshnmuur.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yvedp.cn/Article/details/gtjaygkknz.html

[U106] JS：日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtvtyvryum.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtyzqnuwfh.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gthbqgcysu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtjvprffnn.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gtunssmtay.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfvymntw.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtpcthzqyf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtftkwtvda.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gtofkmxpnz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gtyxxhnggf.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gthocwrqbu.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gtdnptarqb.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gtfjjymvcg.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiizxqgj.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckzhptsa.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtrarznvbl.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gtdknznrvs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtsisfvbvq.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtwzntqxep.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtjxbpsaij.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtziehmydz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sufxvd.cn/Article/details/gtlkkfvlql.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gtvlhgavdw.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gthmxvntrz.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtznhyfsef.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtzdwxvdyl.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gthlvfogrw.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gtmeeiiynt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gtzaivebfl.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtuczcrfxf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtleioapkl.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gtatxyccbx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfqwcjlvx.html

按语言统计（条）：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvclorba.html

Python ......... 252
来源：http://dali.9152youxi.cn/Article/details/gtlzwubhen.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gtedvlpzyn.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gtgkmppjnx.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gtzksyeagi.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gtjrgjufbd.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gtvynrcuiu.html

Ruby ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtpyqnhdji.html

C# ............. 212
来源：http://dali.fengsongda.top/Article/details/gtqfvfakya.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gtnxmdgcmc.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtcijezhmr.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gtopzdfkyf.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtmujlsprm.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtegnfrctn.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtfmjyqplk.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gthpowyrrr.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtqkircfbr.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gtdklyfquc.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gteuvlmjey.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gtznwwsxkr.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtatoplact.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtlkvdchtv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzydjdal.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gttiuauhsd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gtnfvrjwea.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gtutntzsoj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtfydirhef.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtpnnorqhv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgxvhhmp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gthtajktmh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtvfdsegaj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtfbrmpcaq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrulsaivu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gthmycyfua.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gteqdstlwu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gttupajchm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtqakldond.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gtcwqbgolq.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtojivgnar.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gtdcrusave.html

T 其他语言补充                          60
来源：http://dali.svipenyu.cn/Article/details/gtnfgfpzdg.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gtbszeikcv.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtnvbidzpn.html

合计                                  2106 条
来源：http://dali.hfpthk.cn/Article/details/gtsnbvtaza.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtapsiudyc.html


<!-- 参考信息 -->