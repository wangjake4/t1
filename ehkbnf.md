代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtmbxoepbo.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtjkcsykps.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtgqcrocql.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtnmmcdoxe.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfqnhyjr.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtqlfoqqgq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtvqujxiku.html

[T58] Scala：函数定义
来源：http://dali.feifeiyinyue.top/Article/details/gtviropvsn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtenunzwwg.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gteyxglzjh.html

for (i <- 1 to 10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtmghehwwv.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gttjlemnaj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtnlwinuqy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtaaiamrqi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtucckxotc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkkuexycj.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtwattkmet.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhuirgpw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtxrbcxoix.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hammf.cn/Article/details/gtoqehrpzf.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtsyczdmna.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gttkxrbpkr.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtmoaufsbo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gtreajospk.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtiibvcqfm.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvjhfovh.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gtaxdmvfmj.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gtnwfkesxo.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gtidfjzhqf.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gtccyxcpqt.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtxgubxapp.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqihqoxm.html

[U09] Py：字典取最大值的键
来源：http://dali.svipenyu.cn/Article/details/gtdklikkta.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtvsdblano.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gtpxqekqsz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gtkzsumnqq.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gtafecbuqv.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gtepcwgpth.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtiacdflty.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtkhqnrcls.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtonjzmhdg.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gtndvsvczt.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gttqszrytb.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtjypogyya.html

[U15] Py：高精度计时
来源：http://dali.zycfv.cn/Article/details/gtcgtpufrg.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtoliqybdg.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtfpxvaeuc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gtaabojlzp.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gttqppflmu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pycfn.com/Article/details/gtkhmdkfnb.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtlydtglfl.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtuwwslcjh.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtbapfduxz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtpsbitqdf.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gtmzcnpafc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gtilxzajki.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtpljazdfc.html

@contextlib.contextmanager
来源：http://dali.yj20258.top/Article/details/gtbdfvomeb.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gtvtcdkzmw.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtgmdwnyha.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gtidacdpaz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtzizkpwpd.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gthenbdqek.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gteyecztnn.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gtjmqsvtyz.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtxawxeced.html

[U26] Py：并发下载
来源：http://dali.hnqzz.top/Article/details/gtljprimzi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.9152youxi.cn/Article/details/gtpuorzqyb.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtpnbozdlm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gtkuwzfkbw.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtgknehodl.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtnvbotbcb.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gtxfaenrdi.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gtyedpcxhb.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzciqfmkj.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtfjfydtve.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtnvomakch.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gtqmjetwnp.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtwanfxnei.html

ruff format . && ruff check --fix .
来源：http://dali.hywenlv.cn/Article/details/gtfttcfycx.html

[U33] Py：打包发布
来源：http://dali.quarkkingdee.top/Article/details/gtkqablbhr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gtldjwxiae.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gtpktecmcz.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gtcezeknjw.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtiqarzhbt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gtctnxoyoe.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gtvbutlnew.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gtyjlqlrbk.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gtvyvkarkv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuxming.cn/Article/details/gtdhcwkmgg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zycfv.cn/Article/details/gtkrdwpajp.html

Path(__file__).resolve().parent
来源：http://dali.yj20258.top/Article/details/gtvdqrqyuv.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gtxcnikwxy.html

sys.stdout.isatty()
来源：http://dali.ivvv.top/Article/details/gtzmujwjxp.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gtcklqabfd.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtzuwflsnw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgufenzy.top/Article/details/gthricaqsu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gtacldxqdd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtuczcbrrf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.feifeiyinyue.top/Article/details/gtuwbmveqn.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtdkdjcsyp.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gtjktpmzjb.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gtkxfeqstk.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtgygesios.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gtgtjlvdtc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gteokipsjy.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gttrzizkrj.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtkeongtqg.html

[U47] PHP：联合类型
来源：http://dali.zdqjudy.top/Article/details/gtzhhvovsd.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gtsytzftjd.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gtdkathdhl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gtsroasluz.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gtfpdrabaj.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gteuzefhjb.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gtvbufqbvs.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gtpaojovla.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtjgabruus.html

[$a, $b] = $arr;
来源：http://dali.ivvv.top/Article/details/gtbxjilpzq.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtipxwwiuy.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscgktpwm.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gtkcqrnuxd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gtikxbzuev.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gtsmxuxshm.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gtruusmxcn.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gtmihdriqp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtcqainxje.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtvgikytcy.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtlfvoqbiq.html

[U57] PHP：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtqpzhancj.html

"值: {$a}"
来源：http://dali.pycfn.com/Article/details/gtbbstjltf.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gtezehstwo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtwpxprgwp.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gtbqavuzkj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhbiwyck.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gtgrrxlcrf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtnuzwidsa.html

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gtlmoqlcsp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtzqosucni.html

[U62] PHP：日期对象
来源：http://dali.sxryk.cn/Article/details/gtavnyepdz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtromxfspm.html

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gtwbuxhdsn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.0kj1m.cn/Article/details/gtxglrsovc.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gtqlbahmnw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yanxiufei.cn/Article/details/gtclzcloho.html

[U65] PHP：会话
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfkckcxh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtbglhlapz.html

[U66] PHP：设置 Cookie
来源：http://dali.shangyingyoupin.top/Article/details/gtuovzsezm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gtfzkoqwsf.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtamofozcw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yueranfly.top/Article/details/gtqronxtzl.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gtgqkvwllt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gtzkmltpyk.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gtektmqnej.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnchtxmor.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gtgjcmaqap.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ydzc1.top/Article/details/gtjfstmjjw.html

[U71] PHP：抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtmtancbdk.html

throw new RuntimeException("失败", 500);
来源：http://dali.c1oappe.top/Article/details/gtvjlhxmbo.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtgqaewxfc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gttmvezjod.html

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gthfykoxns.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gtpxanbrww.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gthkfxdshe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gtartbrqjc.html

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gtnvbdxkpp.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztdzyofq.html

[U76] PHP：简单路由
来源：http://dali.yonumen.top/Article/details/gtjaxmqzhk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pycfn.com/Article/details/gtgclramhq.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gtlbutopmx.html

composer require twig/twig
来源：http://dali.hammf.cn/Article/details/gtcteajivn.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtolbnganw.html

composer require --dev phpunit/phpunit
来源：http://dali.birdmap.top/Article/details/gtjhctiiby.html

[U79] PHP：静态分析
来源：http://dali.316326.xyz/Article/details/gtnlsnsfec.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gtuvndbkqc.html

[U80] PHP：代码规范修复
来源：http://dali.nwbrower.top/Article/details/gtzwcqimyd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gtcgqpymji.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtpffwmilt.html

npm init -y;  npm i express
来源：http://dali.snrcjt.cn/Article/details/gtalfwqxnz.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gtelpnrvxd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gtufxbbmjb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhoulong.xyz/Article/details/gtruvqskmy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gtndvmhdre.html

[U84] JS：CommonJS 写法
来源：http://dali.shzxlz.cn/Article/details/gtfwplvmso.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenlongwang.top/Article/details/gtrnjmqpdp.html

[U85] JS：可选链
来源：http://dali.yj202588.top/Article/details/gtcslcesqc.html

a?.b?.c
来源：http://dali.bjfxy.top/Article/details/gtrpttvdlf.html

[U86] JS：空值合并
来源：http://dali.xziqi.cn/Article/details/gtpjeratxy.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtketjsmtz.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtdzaerely.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gteoohskpt.html

[U88] JS：对象展开合并
来源：http://dali.svipenyu.cn/Article/details/gtachoacoo.html

{ ...a, ...b }
来源：http://dali.haohaochexian.top/Article/details/gtknuaomcq.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gtpbjrhprl.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtdtntnqys.html

[U90] JS：数字数组排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmwedeoi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtstfkoxgk.html

[U91] JS：对象键值遍历
来源：http://dali.svipenyu.cn/Article/details/gtaumvjosx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gtjsuotywe.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtsdyqsjzn.html

structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gteqbqsefd.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gtizjlbngm.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gtowgikrdn.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtocmcrrna.html

const double = x => x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtopbrjfkt.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gtidqjhsjb.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtcdsvfcgf.html

[U96] JS：async/await 与异常
来源：http://dali.tian-w.cn/Article/details/gthgoocjnb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtwdbidcuj.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gtyzlrxidy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtqcgazgfq.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuxming.cn/Article/details/gtlfibkeka.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gtcusbyhiu.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gttfsbpkim.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gtcooclbzd.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gtavknydnw.html

document.querySelector(".item")
来源：http://dali.hysaishi.cn/Article/details/gtnoptqssh.html

[U101] JS：classList 操作
来源：http://dali.hysaishi.cn/Article/details/gtueogaffi.html

el.classList.toggle("active")
来源：http://dali.jlsjyb.cn/Article/details/gtxdakojwa.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gtewycmzyn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gtclegtdvq.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gtxbgfibbn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gtmjgbxyqg.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gtthzhwqlx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gttaeoulbm.html

[U105] JS：节流
来源：http://dali.ivvv.top/Article/details/gtxtvfmane.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeldjbat.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gtvnnsxsvk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gtzqyprcrg.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtcjulznva.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gteqaxzjai.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gtgzpovdqb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cashguo.top/Article/details/gtwfqrrqxd.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gtkxareukw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtresctjuw.html

[U110] JS：数组分块
来源：http://dali.jqgufenzy.top/Article/details/gttmolfssa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gtkghutyxe.html

[U111] JS：对象转 Map
来源：http://dali.ppjwa.cn/Article/details/gtxjbrsbyh.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtqjprichj.html

[U112] JS：字符串补位
来源：http://dali.jinqigfzy.top/Article/details/gtwyzwucsp.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtshwtpprh.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gtpumcjwon.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gttzzhsjnp.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gtllpbmogz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtguouniit.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtwindbwle.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpeifzia.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sxryk.cn/Article/details/gtsansoljp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gtrgdfmeri.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtlxsoueun.html

npm i -D vitest;  npx vitest
来源：http://dali.zdqjudy.top/Article/details/gtehvzfbzg.html

[U118] JS：开发服务器
来源：http://dali.yvedp.cn/Article/details/gtgtrwdezv.html

npm i -D vite;  npx vite
来源：http://dali.xuanzx.com/Article/details/gtcussbwui.html

[U119] JS：生产构建
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbbluqba.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhuibmtu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sysykeji.top/Article/details/gtbkeapajc.html

import.meta.env.VITE_API_URL
来源：http://dali.quarkkingdee.top/Article/details/gtzhffkkpk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgqqaanko.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gtpnxvxbgz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxngbnxkl.html

按语言统计（条）：
来源：http://dali.tian-w.cn/Article/details/gtwwznmhns.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gttvetkwzb.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmfcafrk.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtlyjlytuc.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gtqndkyedn.html

Java ........... 212
来源：http://dali.cashguo.top/Article/details/gtertsikta.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtqkvroqmp.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtixxekaou.html

C# ............. 212
来源：http://dali.yj20258888.top/Article/details/gtyhjdirsu.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gtfpepnrkz.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gtanxxrezs.html

SQL ............ 90
来源：http://dali.jlsjyb.cn/Article/details/gtsquqymys.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtcxalgynz.html

Kotlin ......... 15
来源：http://dali.guannengcc.top/Article/details/gtldaaszgj.html

Swift .......... 15
来源：http://dali.fengsongda.top/Article/details/gttgmjomrs.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gttifqyyne.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtppufpodt.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gteeugxfgg.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gtsciwsfql.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtogwwwkys.html

按章节统计：
来源：http://dali.yueranfly.top/Article/details/gtccorntot.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtexkesocj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtyurzeukk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtqjyrbnyg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaisukcr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gttojqnrvb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gttaiezdng.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtagvqyerx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtbisgslrp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtnmuzfxer.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gtfivvzzeg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtwxfifbnl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwermlejn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtbtcumiwq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtsbwdvnap.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sysykeji.top/Article/details/gthnfibjqx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtxxxwmodi.html

Q SQL 专题                              90
来源：http://dali.ybcxt.top/Article/details/gtjlwoaiop.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gtqhcxbizy.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtqfwxyykg.html

T 其他语言补充                          60
来源：http://dali.yj202588.top/Article/details/gttafhbkpc.html


<!-- 参考信息 -->