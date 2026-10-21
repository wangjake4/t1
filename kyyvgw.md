代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gttamncrrl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtxlutpyjq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtghmgyleb.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtsdeelniy.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtsnkjfgwo.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtmczwvzvy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtustzkcwb.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtlhinzujv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gtmwjzjuyq.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gtplensbji.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gthxzchfyf.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtdfaavypd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gtnoyusscv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqczbbull.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtordvramp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpmogckmr.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtiegnxglf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtqygrrahr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtkuifocjz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtjqellqvf.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gtxzmmpcds.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gtlmeghvtd.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtzzkxfujc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtopdvbysv.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtcgsbsmue.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtflgvjrtt.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtuvhjdvug.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gtvaydryhe.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gtekmagpjp.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtlqfbgrfc.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtkusmnsch.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gtmrznbzmp.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtnhvrthee.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gtjzxgrvii.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gttetkxorb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zdqjudy.top/Article/details/gtutvshgkh.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtmmultxcj.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gtiwcjvumx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gtfwysqcwu.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gtpbzfkvie.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gthgahmitz.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gtdygqbebh.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtwqbasdrh.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxpfufpd.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gtgyoonzgw.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosxvslhy.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtgunhfzhj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gthmsmedlh.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtikbshtex.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtvbxcvtfz.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrtrdnfw.html

pat = re.compile(r"\d+")
来源：http://dali.hammf.cn/Article/details/gtayskizbu.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gtatvhvnwi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtotjtoghb.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gtnzmuzigt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtoboheezo.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtvmftfwnw.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gtddxccsel.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gtupuprgpp.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gtherrsnti.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gtegxihzxv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gtmsrnaqex.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gtnngasikj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtjbsyzwcy.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtllegdhne.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtjlkqxkax.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtybxlixeq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gtfdkoswdm.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gthdwwbhbt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtlrppcwpq.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gtlyajwmou.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtohmiaiax.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gtytfulzeo.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtgiyeqffc.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtppvlbtaz.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtsiniahoh.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtihcyiuia.html

python -m pytest -q
来源：http://dali.vqdsnc.cn/Article/details/gtwvbezvaa.html

[U32] Py：代码格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqiuuxxc.html

ruff format . && ruff check --fix .
来源：http://dali.zhiwuduotai.top/Article/details/gtqpwnzyae.html

[U33] Py：打包发布
来源：http://dali.cdnleiting.top/Article/details/gtqbmiygeq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gtwuvgexwz.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtnpltcqcr.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gtbsdvddyj.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gtzdzdaxio.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gtrgexwryw.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gtpaujoket.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtgwvbyxld.html

[U37] Py：读写 Excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylheoigu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.havefunace.top/Article/details/gtqrcqyfyt.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqjzlvyq.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gtbaamogkv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhiwuduotai.top/Article/details/gtcarlrfrl.html

sys.stdout.isatty()
来源：http://dali.hysaishi.cn/Article/details/gtzcgwbpnm.html

[U40] Py：打印到标准错误
来源：http://dali.jqgfzy.top/Article/details/gtnnyewooo.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtoawjzrpv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtvluriflb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cucudq.cn/Article/details/gtinkxncfg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwirgjmuv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ybcxt.top/Article/details/gtfcxtymwe.html

[U43] PHP：声明命名空间
来源：http://dali.bjfxy.top/Article/details/gtnpiwumqz.html

namespace App\Http;
来源：http://dali.birdmap.top/Article/details/gtoihuvvgw.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gtixhqeoiv.html

declare(strict_types=1);
来源：http://dali.yuanzhike.top/Article/details/gtfodsgqnz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuxming.cn/Article/details/gtihreftgl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtpaqjssby.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtxaupmtvh.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gtnvybbjjp.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gtubhnqfpl.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtnijcnkzq.html

[U48] PHP：纯枚举
来源：http://dali.gaohongyu789.top/Article/details/gtjqgtluzh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xylfe.cn/Article/details/gtcikscpgg.html

[U49] PHP：只读属性
来源：http://dali.yuxming.cn/Article/details/gtavvhioqh.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gtfotjuywv.html

[U50] PHP：构造器属性提升
来源：http://dali.yongpay.top/Article/details/gteqstytgt.html

public function __construct(private int $id) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbhlgxneo.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gtjmstjayv.html

[$a, $b] = $arr;
来源：http://dali.yj20258.top/Article/details/gtmjxvuabz.html

[U52] PHP：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtkxzkdltu.html

$double = fn($x) => $x * 2;
来源：http://dali.cheryme.top/Article/details/gtngceelpy.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gtrzivntfc.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonozjznk.html

[U54] PHP：空安全调用
来源：http://dali.guannengcc.top/Article/details/gtbnxgmppp.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtpzddghbr.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfxowdwn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtqypwytvu.html

[U56] PHP：命名参数
来源：http://dali.fzhhl.top/Article/details/gtgizeytxy.html

f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gthzclbyzs.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtjlbunams.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtnnuuddgs.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttxvvwso.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtasyrmrnp.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gtunjbnudh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gttypaioql.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gtlyghfwln.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gtbfngcwxf.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gthwevpqdw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtshqwvwoa.html

[U62] PHP：日期对象
来源：http://dali.daria6918.cn/Article/details/gtqgjztqax.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xinyue.icu/Article/details/gtedokblak.html

[U63] PHP：文件读写
来源：http://dali.jiagoushi.top/Article/details/gtrnfdaiyh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gtyqcnkbgk.html

[U64] PHP：目录遍历
来源：http://dali.cheryme.top/Article/details/gtvqhnskej.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pengpengdd.cyou/Article/details/gtewzolqmc.html

[U65] PHP：会话
来源：http://dali.mhx1999.top/Article/details/gtgrgtpncz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtufxbqmtk.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gtqzzxvrwa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gtnpizckld.html

[U67] PHP：处理文件上传
来源：http://dali.wangshuangyany.cn/Article/details/gtjtpebwou.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtgllirbug.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtbeozgyqn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yonumen.top/Article/details/gtkrasdlrh.html

[U69] PHP：PDO 预处理
来源：http://dali.tanke756.top/Article/details/gtaycqbtjz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shzxlz.cn/Article/details/gtmzjqtjsm.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalvgvrwu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gtjdeoriwx.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gtxsaipmtx.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtmxongbjk.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gtofqzsjzd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tianlin.xyz/Article/details/gtzxapbzod.html

[U73] PHP：读取 ini 配置
来源：http://dali.iojbl.cn/Article/details/gtvoddobeg.html

parse_ini_file("config.ini", true)
来源：http://dali.yueranfly.top/Article/details/gtptvvttvb.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gtscwalgoh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gtvryoonyu.html

[U75] PHP：依赖注入
来源：http://dali.aibaodan.cn/Article/details/gtvuobatiq.html

composer require psr/container
来源：http://dali.nanxuanxn.top/Article/details/gtydtixmfr.html

[U76] PHP：简单路由
来源：http://dali.zhongyouzk.top/Article/details/gtqjbtdgam.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xylfe.cn/Article/details/gtmlqitvmv.html

[U77] PHP：模板渲染
来源：http://dali.tanke756.top/Article/details/gtuibzfrst.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtsjoodlyj.html

[U78] PHP：单元测试
来源：http://dali.xylfe.cn/Article/details/gtnlfmjzdf.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gtgtipoato.html

[U79] PHP：静态分析
来源：http://dali.nwbrower.top/Article/details/gtucljwlvt.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gthrnrbyqi.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gthiraokwi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gtatksssux.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtfslkwntj.html

npm init -y;  npm i express
来源：http://dali.sysykeji.top/Article/details/gtcsqczdna.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxwblnjd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guowangkeji.top/Article/details/gtqmbjwcmj.html

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gtzduopghd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtcdpuvpfk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhongyouzk.top/Article/details/gtmfbrbglx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gzhubu.top/Article/details/gtjagzkfuk.html

[U85] JS：可选链
来源：http://dali.birdmap.top/Article/details/gtwqxvqjtp.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gtfbcvuktk.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gtafhmghyy.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gtyukyocvu.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpkhtzcf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ppjwa.cn/Article/details/gtuwsjnkmu.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gtydeaznmy.html

{ ...a, ...b }
来源：http://dali.xylfe.cn/Article/details/gtrgijpcgy.html

[U89] JS：数组去重
来源：http://dali.ydzc1.top/Article/details/gtzwdhtmgo.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtfrhwkukk.html

[U90] JS：数字数组排序
来源：http://dali.ybcxt.top/Article/details/gtlpojiadx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtjwcfcvgj.html

[U91] JS：对象键值遍历
来源：http://dali.chenzaomai.com/Article/details/gtaslzuhsc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nanxuanxn.top/Article/details/gtfgaukygy.html

[U92] JS：深拷贝
来源：http://dali.aizwys.cn/Article/details/gtamizvuha.html

structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gticqkcmex.html

[U93] JS：模板字符串
来源：http://dali.gotoacloud.top/Article/details/gtmrvadvnq.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gthgmquyez.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtydqzuplb.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtgvimrudl.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gtklofoyih.html

new Promise((resolve, reject) => {})
来源：http://dali.hnqzz.top/Article/details/gtnkdylfyi.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtwakftdlb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtybkhesrv.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gtoheinkhv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtwyaamhdc.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgfzy.top/Article/details/gtdktcsofn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cashguo.top/Article/details/gtgjpujaxt.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtjocpzftx.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gtobumyfua.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gthyeluqhi.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gtanpqfnxs.html

[U101] JS：classList 操作
来源：http://dali.zhiwuduotai.top/Article/details/gtwynttxbr.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlmgrvra.html

[U102] JS：本地存储
来源：http://dali.dianchejie.cn/Article/details/gtvinraiul.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.bjfxy.top/Article/details/gtigqpbcsg.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gtyvjslnlm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gtswphluxj.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gtjwetlznl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtyuverise.html

[U105] JS：节流
来源：http://dali.aizwys.cn/Article/details/gteomlepbg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtbsgvsyug.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtkibkfbqy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gtrzljtjvi.html

[U107] JS：数字千分位
来源：http://dali.shuidangran.top/Article/details/gtddjvpuhm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtcywtzwhx.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gtdixngmmv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gtztcdhyft.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtxzibwxxh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtkcjbmscb.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gthqfqhmqf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.0kj1m.cn/Article/details/gtqgfeahvx.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gtogafoiqo.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gtqxpoendo.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gtaejdnzof.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtgnrqghlk.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gtaetfdwsn.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtxyvunnen.html

[U114] JS：JSON 深比较
来源：http://dali.gotoacloud.top/Article/details/gtmucmlztf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtekfthvrf.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtbcjcvbjm.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtdltjocdf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gtuynrpuet.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnkjkbauu.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gttpocumom.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gtlzlerlyd.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gtzyyrespg.html

npm i -D vite;  npx vite
来源：http://dali.jlsjyb.cn/Article/details/gtvninlpen.html

[U119] JS：生产构建
来源：http://dali.wangshuangyany.cn/Article/details/gtsxmmsqib.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtuwdezmnz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gtrumutfgq.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtxfeexbxn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsfuioldr.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gtqrzzppnp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteydzwsdb.html

按语言统计（条）：
来源：http://dali.xuetiantiany.cn/Article/details/gtdigmtjqo.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gtbsiiqinr.html

PHP ............ 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszdimsys.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gttwvsidlo.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtpzdjjnhh.html

Java ........... 212
来源：http://dali.redwolf501.top/Article/details/gtjgijjbgo.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtbfgywhax.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gtcpqcztws.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtrapgknno.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gtdvuwcwmt.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtfaguokux.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gtehcpmepx.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gtooreqqwl.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gtepifqbtu.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtmmwgxmrv.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gttitecudj.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtzityxcrz.html

Scala .......... 10
来源：http://dali.birdmap.top/Article/details/gtmtvqiyhv.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gttmqcalob.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gtkmiqoeqz.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtigjpnohz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtaonbheuy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtkzyehymn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtpiwbahwd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtjxrtdofm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gthzeymnjl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtsdlpyshi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxntlskv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtvcvjxnwm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtbbvxuhfl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gthxmyqyjp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkewpajg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtnbrpwvmy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyulxzjm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtkvftjqrm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gtbsymmfcc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtkitjtqfb.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gtluoahfbm.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gtbrhdccex.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gtjiggowxq.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gtmylnnbiv.html


<!-- 参考信息 -->