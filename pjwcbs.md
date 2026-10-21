代发 wailian999

val a = 1;  var b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtjfrzethq.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtmoedppss.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtgzgufjis.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtgqtdhmob.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtnxbwtois.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtolnodshe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gtyhktdqez.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtcqdgqcsa.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gtadyqoqpj.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtzkvgivbb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhmaeatp.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtxhisnkor.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gtaomjhiib.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtrxuvygao.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gtvqssdbkh.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gtcmgmyfkv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtkwilbhcv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmivorhgm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtjzmpnppn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtedgekcwi.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtiqcleeph.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cheryme.top/Article/details/gtgdqdyxrr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gttzztlvon.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtvjknkgip.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtrwpkslyh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj202588.top/Article/details/gtxkhuiala.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtuofeueqb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtruggouhe.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gttyanqguc.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmzgfwut.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtfgeioeve.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtyincvnlf.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtmttxllhv.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtyodazxly.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtbnwawaju.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtndlnzpks.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtpxqscunm.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gthjtewpce.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtyuqqercc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gtjrflgwjt.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gthtimriwh.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gtmbobppak.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtarargwwc.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtgkjsxiuc.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gtbdtrrcaw.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtewwcorni.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gtboqfpmnx.html

defaultdict(list)
来源：http://dali.hfpthk.cn/Article/details/gtmhtnqafx.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtdwpzekcx.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtaxhdqobt.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtprnxxydj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gtcnoldgkb.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtlkvvlsqo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gtbjdeycfr.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gtcvlrwnod.html

pat = re.compile(r"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtuhktkbgw.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gtoiiwopol.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gtkomyfynf.html

[U20] Py：缓存函数结果
来源：http://dali.zycfv.cn/Article/details/gtedzfpmwk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gtmefgkdws.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtnwqfirfq.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtclkbzhxe.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gtpbmzvpsg.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gtoumasnet.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gtcacxrace.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gtyggtvtyt.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtblzjpvxy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthurosmxc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhaomingkeji.xyz/Article/details/gttirllzag.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gtseagvvjb.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gthjoygaxv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvbcdbhy.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gtrzhqfxfk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gtekgairuv.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtkqckqjpk.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtjlvqmuyr.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gtxevtdeec.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gternqelqb.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtfcybdetc.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gtutytiodp.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gtnzorvvet.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtncdiunlt.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtrjhjvtlb.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gtdjmtixjl.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gtrohluzil.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnqzz.top/Article/details/gtofgowcbg.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtjdnwoknx.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gtytynivos.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtsqtwvscu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gtrgbjspkq.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gtqsrmyfry.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gtukdbcgtl.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtybuyfxrh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gtbgurqfua.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gtrhjmrirx.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gtusgcjnkb.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfutqocl.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtfahpremp.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtbawzzvlg.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtajhbavis.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtbiifqnhq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gtuweoxadr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dianchejie.cn/Article/details/gtzsmhffbi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gtosnkclad.html

[U43] PHP：声明命名空间
来源：http://dali.tanke756.top/Article/details/gtoxkfzdao.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gtpcwgvzcf.html

[U44] PHP：开启严格类型
来源：http://dali.zhoulong.xyz/Article/details/gtvghkatvy.html

declare(strict_types=1);
来源：http://dali.hysaishi.cn/Article/details/gtchqzlqrp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuanzhike.top/Article/details/gtzqcwcbwf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtinixwwvo.html

[U46] PHP：可空类型
来源：http://dali.quarkkingdee.top/Article/details/gtalsomnqv.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gtjyqrxaty.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gtvreccvyj.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtxgrdbjen.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gtulbfxxjq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hysaishi.cn/Article/details/gticvuihrf.html

[U49] PHP：只读属性
来源：http://dali.iojbl.cn/Article/details/gtbgqxatoo.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gtrgzqfolb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gtfiwkdqlb.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtmwhbrdzp.html

[U51] PHP：数组解构
来源：http://dali.wangdashe.top/Article/details/gtontrdaiw.html

[$a, $b] = $arr;
来源：http://dali.yangfankeji.com/Article/details/gtzkdldami.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtsscilzir.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gtgaecsjyz.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtmpcrcdqv.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gtbtygjrvd.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gtgoyaoceg.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gtmesjwqcv.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbthncin.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nwbrower.top/Article/details/gtmrvysfub.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gtuhujdext.html

f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtyfodfwhp.html

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtrbhajdfh.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gtizgsxbdc.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gtuvwbtkhi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gtbdlgmuty.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gtlnuluykx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtvgbumysa.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtfvawnrol.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.svipenyu.cn/Article/details/gtyfkbddfc.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gtnlvujndg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtzqxxsugn.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gttjjuhqrm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhixingplan.top/Article/details/gtxgmlinbx.html

[U63] PHP：文件读写
来源：http://dali.yuanzhike.top/Article/details/gtwqmitheb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gtvuflpirg.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtfmtuyuft.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gtfhkzyktd.html

[U65] PHP：会话
来源：http://dali.tanke756.top/Article/details/gtqxooikup.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtcydwzrzr.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gtyjhrhspl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gtbsotoitk.html

[U67] PHP：处理文件上传
来源：http://dali.wangshuangyany.cn/Article/details/gtcmfvdlzt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gtnrfuxwtm.html

[U68] PHP：PDO 连接
来源：http://dali.sufxvd.cn/Article/details/gtuuxjdqzv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aibaodan.cn/Article/details/gtganohskg.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gtipsenqut.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hfpthk.cn/Article/details/gtqvmpdkpc.html

[U70] PHP：PDO 事务
来源：http://dali.gogol.net.cn/Article/details/gtkbgjqafd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxinkj.top/Article/details/gtczymajey.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gtnlpxffrk.html

throw new RuntimeException("失败", 500);
来源：http://dali.ivvv.top/Article/details/gtekqterau.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gtmvycwrpx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnqzz.top/Article/details/gtgawrcxat.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtfyjafhwr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhiwuduotai.top/Article/details/gttwpzxzxt.html

[U74] PHP：读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtgvipwtbk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtoogfbeza.html

[U75] PHP：依赖注入
来源：http://dali.ybcxt.top/Article/details/gtfalioiis.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gtibtjcrnd.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gtfivzosiw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hysaishi.cn/Article/details/gtwyhiybev.html

[U77] PHP：模板渲染
来源：http://dali.chenzaomai.com/Article/details/gtgpryaojt.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtzjssnedg.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtxwyiqjvd.html

composer require --dev phpunit/phpunit
来源：http://dali.tian-w.cn/Article/details/gtrwsxcazo.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gtlsylskjp.html

composer require --dev phpstan/phpstan
来源：http://dali.yj202588.top/Article/details/gtdhggebja.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiyszwfk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xziqi.cn/Article/details/gterqqfseu.html

[U81] JS：初始化项目
来源：http://dali.daria6918.cn/Article/details/gtjnjdbzqc.html

npm init -y;  npm i express
来源：http://dali.c1oappe.top/Article/details/gttvvifmlz.html

[U82] JS：package.json 脚本
来源：http://dali.gaohongyu789.top/Article/details/gtydlwzbeb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gtehffyjyk.html

[U83] JS：ES Module 导入导出
来源：http://dali.iojbl.cn/Article/details/gtvjcyyega.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtnfsrvdhw.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gtzqxpyirz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gthylaahcp.html

[U85] JS：可选链
来源：http://dali.jyoumei.cn/Article/details/gteumtcamr.html

a?.b?.c
来源：http://dali.xziqi.cn/Article/details/gtkkxkkafn.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbmhmsgy.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gtxlvzendu.html

[U87] JS：解构默认值
来源：http://dali.wangdashe.top/Article/details/gtizxlpfaw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtuuxqzbxm.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gtbgcsptjf.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtqjkqubys.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtatqmykpk.html

[...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gttmttiqpt.html

[U90] JS：数字数组排序
来源：http://dali.yueranfly.top/Article/details/gtgmqgwvvt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtvgjjyeoo.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlpoelih.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hongshengwenyu.top/Article/details/gtoqkjlplk.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtmmtjoiys.html

structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gthtfcrfxb.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gtarytdjtt.html

`共 ${n} 条`
来源：http://dali.vqdsnc.cn/Article/details/gthiwgfmhy.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtvtoobuts.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gtgkchssgf.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gtcduspoux.html

new Promise((resolve, reject) => {})
来源：http://dali.birdmap.top/Article/details/gtiqaooucq.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gtfzttztok.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtwkmudbne.html

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gtpbmbcwen.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtnmcuhpds.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gtzjexptyu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtqedxjdky.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gtymkzkqpj.html

el.addEventListener("click", e => {})
来源：http://dali.jlsjyb.cn/Article/details/gtwpqzcyww.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gtyqnofikd.html

document.querySelector(".item")
来源：http://dali.aibaodan.cn/Article/details/gtvhykkupw.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gteafgngvw.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gtmkujttkl.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gtmasviwqg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guowangkeji.top/Article/details/gtycfhkhkt.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gtcsexcwcn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gtlipymbsb.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gtvzolpwmh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtwtqsjobr.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gtycsmrvcl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtrhqavxoa.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gtbehbhilx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gtmnlmrubw.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtikckcsid.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gteccubhxa.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtfrbwegvz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gtisgjqyht.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gtulsoxtzl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gtzgdadden.html

[U110] JS：数组分块
来源：http://dali.ybcxt.top/Article/details/gtfemfkviw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pengpengdd.cyou/Article/details/gtlhcrmlut.html

[U111] JS：对象转 Map
来源：http://dali.yanxiufei.cn/Article/details/gtkwgdhrcz.html

new Map(Object.entries(obj))
来源：http://dali.yj20258888.top/Article/details/gtuzgyftlb.html

[U112] JS：字符串补位
来源：http://dali.yanxiufei.cn/Article/details/gtpvmamwwp.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gttypgjhjp.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gtlchkyqpj.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gthiqwrqhs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gtcnwbvprd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtfjugrixk.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtlbrezrit.html

crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtcffxhxsa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daria6918.cn/Article/details/gtmboenzds.html

/** @param {string} name */ function f(name) {}
来源：http://dali.haohaochexian.top/Article/details/gtnswjxpsr.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtlnonpvcx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhoulong.xyz/Article/details/gtrrlqwjlz.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gtmdpsbhio.html

npm i -D vite;  npx vite
来源：http://dali.ybcxt.top/Article/details/gtottkqbkh.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gtpntcrufh.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gtbpggncvg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gtbflettvm.html

import.meta.env.VITE_API_URL
来源：http://dali.shangyingyoupin.top/Article/details/gtmgydglnb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqpmotmpd.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gtcbcfesnm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmonmjjxv.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gtkjxarepq.html

Python ......... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyjgjufe.html

PHP ............ 252
来源：http://dali.cashguo.top/Article/details/gtlhlsojqh.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtktisaagq.html

TypeScript ..... 212
来源：http://dali.hammf.cn/Article/details/gtwygvdrff.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtvbnqfvfj.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gtptmjpxpn.html

Ruby ........... 212
来源：http://dali.tian-w.cn/Article/details/gtymnyejod.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtidmmijcj.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gtqitwjkrk.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gtrdvyxgor.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gthycxczsa.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gtaimxhbhm.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gtqbtkmvfv.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtuhfjpene.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtpynjidag.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtoyfuhbxr.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gtyxksatdp.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtvssoixux.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gtkomgicfa.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gtsmuruhyq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtetpwqopg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtctflvekn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntlernkx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ybcxt.top/Article/details/gtrtrbsqlt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yonumen.top/Article/details/gtblpulfjk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtxdheqlpb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtixcbkqeg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtiyqhvakg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtlstrmkqz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafxlwmta.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtbknuatoh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gticzidjie.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtgcxrsmxq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gthhmkzruz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinqigufen.top/Article/details/gtslixqvws.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gticndorcm.html


<!-- 参考信息 -->