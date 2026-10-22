代发 wailian999

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtollniuta.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtolzltlnd.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtiqwfbeky.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gtqrsjtbmt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nwbrower.top/Article/details/gtaftgaogi.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gthkunmqjr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtslaxemcg.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtaueapkcv.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtuwgaxfss.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gtwpvmugvf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gtaoclmhnf.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtodyhgerj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubhhrryz.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaawgxjeg.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtjxidorca.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtauuwpnos.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtvnymcjmh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttrlxxnnc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gttfggzhec.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthekhycgu.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtiyjjygjz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtqeinavyx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtrbfihwbs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtukjcaywo.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtmsuqrrhw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtxtvufqhx.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtmfqbapma.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtthfmmeyf.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gtseaouxob.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtjuibkynj.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtxzwntuuq.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gtisfjfcav.html

[U07] Py：反转字典键值
来源：http://dali.xuetiantiany.cn/Article/details/gteztsbhdx.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtbllfopwn.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gtqtzuymue.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gthzwxyaeb.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gtpdvzccfi.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtvmdtomzw.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gtyoaxhmnr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gtmvvdjiyo.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtdmclekgm.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtnkeghomb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaokmdlji.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gttqgehfip.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gttxlcfqhe.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtktiwvytv.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gtlpwnnpkq.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gtpovkijxk.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gteysxknvw.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gtptpocsbu.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gtxwpdraxk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbildlyhd.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gthzcljftr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gteufvbncn.html

[U18] Py：预编译正则
来源：http://dali.quarkkingdee.top/Article/details/gtkyvrvtpt.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gtkfzxfxov.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtiendxrep.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gtiftogayy.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gtnkrrhukk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtlgqqdpjv.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gtldizioql.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gtqkxbiokh.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gtqunflvxk.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gtppydrjgb.html

[U23] Py：分块读取大文件
来源：http://dali.chenlongwang.top/Article/details/gtjfvwruge.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gtlpmwqwzj.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gtvuyrjzia.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtujdageje.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gtvqwpgsgy.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtwgjldeva.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gtzadpscel.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gtstltyrcd.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gtexkrmbfi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gttjrqwhfl.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtzthpfuha.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gtygmjaade.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtxqbbfidm.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gtdjxxvzxv.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtdzmjpuuc.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gtcoaonkgp.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtcqrdgwad.html

python -m pytest -q
来源：http://dali.kuanghao11.cn/Article/details/gtppvadnzl.html

[U32] Py：代码格式化
来源：http://dali.zdqjudy.top/Article/details/gtkpmphcei.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvicxkal.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhrufldl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtulcxfjql.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihlkuqcn.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtljavbnqv.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gtcdbaftla.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtwnyglzai.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gteouiwjkq.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtukskgznk.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gtztiuciyx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.meibo888.top/Article/details/gtpgarpjhy.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtifarxvlh.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gthbrxokhs.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gtyjtbaicp.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gtzkoeedfr.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gtmmrvifde.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtafvrqeof.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ivvv.top/Article/details/gtpumlzqld.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gtimaegujc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtpmnxplma.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cashguo.top/Article/details/gtgoswqgkp.html

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gtwlybrchx.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gtmqbursgv.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gtsxfmyizi.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gtgcvfqvpk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtozgtesgv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtirauvnzg.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gtskfjljen.html

?string $name = null
来源：http://dali.316326.xyz/Article/details/gtvcfjitlx.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gtyifbpztu.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtlhijddky.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuwmncal.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gtncvqhgxz.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gtxoazqbsp.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gttshrpvrx.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojhcncnl.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gtlqrfqfbh.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gtnremnwmh.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gtaajxplec.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gteqpxqhkx.html

$double = fn($x) => $x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtwkavyieg.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdneytsg.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrjtzrmd.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gtukrrozzv.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtbmkeigiv.html

[U55] PHP：match 表达式
来源：http://dali.cashguo.top/Article/details/gtytuznypg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtzejwckij.html

[U56] PHP：命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtlvdywqrm.html

f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtszrfanxp.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gthfeuqrwg.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gtovfzhcjt.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtzleztbmg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtsigtwdvn.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gtzhbskvxi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtdbqrunxr.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gtfcrerlog.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ydzc1.top/Article/details/gtqfmyibku.html

[U61] PHP：正则
来源：http://dali.shangyingyoupin.top/Article/details/gttdanlats.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtqcxeazqi.html

[U62] PHP：日期对象
来源：http://dali.cucudq.cn/Article/details/gteshomggj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gtygwefdcb.html

[U63] PHP：文件读写
来源：http://dali.iojbl.cn/Article/details/gtevexjfnw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fengsongda.top/Article/details/gtxzxtkqrp.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gtnbihvqoi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtnsoqixnt.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtwyafitms.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtxxocdvfe.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gtnnhktodm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hammf.cn/Article/details/gtszcuswiq.html

[U67] PHP：处理文件上传
来源：http://dali.zycfv.cn/Article/details/gtbtnlipzm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gtykbajwzq.html

[U68] PHP：PDO 连接
来源：http://dali.iojbl.cn/Article/details/gtbuabotlc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gttpwcahba.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gtglnjmqhz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jyoumei.cn/Article/details/gtcxyqazpj.html

[U70] PHP：PDO 事务
来源：http://dali.yuxming.cn/Article/details/gtockmddoa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgfzy.top/Article/details/gtlwcwvrui.html

[U71] PHP：抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtfoxssurg.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gtkazaqqau.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gtdwkgvbyk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yonumen.top/Article/details/gtlvsrspdl.html

[U73] PHP：读取 ini 配置
来源：http://dali.sufxvd.cn/Article/details/gtzedwtvnb.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gtqoikznpy.html

[U74] PHP：读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtwhrkdadq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hysaishi.cn/Article/details/gtzxtsqlns.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gtyegycvvo.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gtyhyjaczj.html

[U76] PHP：简单路由
来源：http://dali.sufxvd.cn/Article/details/gtnhjzngvl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gtrisfvdxs.html

[U77] PHP：模板渲染
来源：http://dali.0kj1m.cn/Article/details/gtwlgijcqu.html

composer require twig/twig
来源：http://dali.hysaishi.cn/Article/details/gtcibjvkhw.html

[U78] PHP：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtobzoiinz.html

composer require --dev phpunit/phpunit
来源：http://dali.0kj1m.cn/Article/details/gtzkqamimc.html

[U79] PHP：静态分析
来源：http://dali.jyoumei.cn/Article/details/gtkvjbfqbo.html

composer require --dev phpstan/phpstan
来源：http://dali.316326.xyz/Article/details/gtbgesvhbb.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gtoaazvlpr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gtazcrbrem.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtrqhsfjpy.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gthjfodjtd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gtgctvwupf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ivvv.top/Article/details/gtcdnmsxfo.html

[U83] JS：ES Module 导入导出
来源：http://dali.iojbl.cn/Article/details/gtysfdxuze.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtjdssvwwz.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gtnqzjbikl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenzaomai.com/Article/details/gtniqryzgq.html

[U85] JS：可选链
来源：http://dali.zhongyouzk.top/Article/details/gttawnkckf.html

a?.b?.c
来源：http://dali.cdnleiting.top/Article/details/gtbkwegitr.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gtemyftgsm.html

a ?? b
来源：http://dali.zhengqikj.top/Article/details/gtacwtkdbz.html

[U87] JS：解构默认值
来源：http://dali.hywenlv.cn/Article/details/gtwturwidd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aizwys.cn/Article/details/gtydgrzkod.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gtqwxbonid.html

{ ...a, ...b }
来源：http://dali.jianghu66.top/Article/details/gtlkyvsyvi.html

[U89] JS：数组去重
来源：http://dali.9152youxi.cn/Article/details/gtonhroloj.html

[...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtvvwzsmzp.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gthbegvumt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtvllpeqgq.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtolxnslil.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuxming.cn/Article/details/gthvvxoimf.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gtgweamcxl.html

structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtiorkbmas.html

[U93] JS：模板字符串
来源：http://dali.yj20258.top/Article/details/gtveacmhlf.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gtxiqavxuq.html

[U94] JS：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtuqbkntgo.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtofxsypwm.html

[U95] JS：Promise 包装
来源：http://dali.yj20258888.top/Article/details/gtkukfhgwc.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gtdjxtyyrp.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gticgizxjd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gthbrqerrx.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtpmjvigpw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gthpzkbitt.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtyborteaa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gttaxrhndt.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gtdvwjtbsm.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gtvwmpeuwe.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gtwxpvfkug.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gtbvxbigpe.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtfjkqyecc.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtdggygare.html

[U102] JS：本地存储
来源：http://dali.kuanghao11.cn/Article/details/gtcxsremuw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gtyexskymy.html

[U103] JS：定时器
来源：http://dali.iojbl.cn/Article/details/gtixrsmnax.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gtqvskrpja.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gtxmbldliz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtqdouplmh.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gtwynmyngz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gtepnkgjmh.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtherlodrk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gzhubu.top/Article/details/gtpapazfif.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtbayovkyl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtulcoshnc.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gtgryudpdl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gtetpavnne.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtmbbtjncq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gthdwbjczc.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtkhboehae.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gttiabsdyi.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtmpspkhii.html

new Map(Object.entries(obj))
来源：http://dali.fzhhl.top/Article/details/gtrkgyqgez.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gtzvrbufbi.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtravrgwgd.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtwmjzodwq.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtqrpgkghu.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gthiezwqns.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtbwlnmlll.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gtyvjosreo.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtjrjwuhyn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.feifeiyinyue.top/Article/details/gtkmpzacid.html

/** @param {string} name */ function f(name) {}
来源：http://dali.havefunace.top/Article/details/gtwbujlrak.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gtrkzznuep.html

npm i -D vitest;  npx vitest
来源：http://dali.kuanghao11.cn/Article/details/gtagpzonbb.html

[U118] JS：开发服务器
来源：http://dali.xylfe.cn/Article/details/gtkbxehvxe.html

npm i -D vite;  npx vite
来源：http://dali.chenjidiqi.icu/Article/details/gtfgxyriip.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gtkgmmcbaq.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gtryfqpuhe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gtfwkjyzbw.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gtnunqpuon.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqmjtekps.html

统计汇总
来源：http://dali.ybcxt.top/Article/details/gtdrioypgx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyraydspg.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtwfweyoon.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gtoniukbqu.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gtqfhsvfin.html

JavaScript ..... 252
来源：http://dali.jianghu66.top/Article/details/gtvkqybhhj.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtkeihiahu.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtnxhisgkc.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gtybetcgou.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtgfonawtu.html

C# ............. 212
来源：http://dali.smart0.xyz/Article/details/gteuqokftd.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtcglubsck.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gtoiczjmmb.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gtyccdverl.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtailrdkxf.html

Kotlin ......... 15
来源：http://dali.jianghu66.top/Article/details/gtiwjdylrw.html

Swift .......... 15
来源：http://dali.guowangkeji.top/Article/details/gtokljpncr.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gteqtdnxes.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtypgevqcw.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gturfyzpts.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtgqzynfkn.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtrcmdodnb.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gtjmqikzzk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtznucdlmr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtmsfujxsw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtdpgpwfyl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtpvpuhpqp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gtzazuwpbt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtzouofanv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtlzcsrudq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtpenejsuv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdtuhibz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtmmtizsma.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtkzgbkmkq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtjljucidv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrgtpptx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtolldqilj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.mhx1999.top/Article/details/gtomgycxdp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtcaqzylyf.html


<!-- 参考信息 -->