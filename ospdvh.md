代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gtjodevmzy.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gtcgcnxdsh.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gthdosqxrw.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtgtosxnoi.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtcqodbawu.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtfocnropc.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtoiybhmal.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtdvusssgg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gttahgmisq.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtxuwqqhlp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtoxsfcetl.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtnsvypzbi.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gtlnkocdbk.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtvtdovnma.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtlfyqyrop.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gtainjozqo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gtcggfkzao.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovjwdiqu.html

for (i <- 1 to 10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtdcqvozsc.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gttzzovwhs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtslaiugff.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsoovsmcd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiawmrjel.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtastnibyd.html

[U01] Py：创建虚拟环境
来源：http://dali.haohaochexian.top/Article/details/gtmtuwycxh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxjiuiho.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gthidlwcnc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtpsxyyhdo.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtogftgkvz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gtcmwruzhd.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gtbdzakwsk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtfprzszcq.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtqbbcrqnt.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtbcwxomys.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtpeyokzfr.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtjipzilqg.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtnzhbnxnt.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtdzehedll.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtdmchhtpu.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtiktsvuca.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtptwecmsf.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gtbqgaaxqq.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtynzcppah.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.birdmap.top/Article/details/gtbkehdxry.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gtkeyuvqcj.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gtbxanaiwy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtteqpxcea.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gthtdostyl.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gthkgzhbrv.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gtxfqkslef.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gtwdqkencl.html

defaultdict(list)
来源：http://dali.ydzc1.top/Article/details/gtqwrsyjnh.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtugrctorv.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtyjfsgthg.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gthowgfeds.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gtlchorxrx.html

[U17] Py：初始化日志
来源：http://dali.yueranfly.top/Article/details/gtclcbzfoq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtpwgqgxgf.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gtkvyqxrkm.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtipnzcbkt.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gtelzshrlv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jianghu66.top/Article/details/gtrzrufykw.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtuliminwl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shuidangran.top/Article/details/gtvxapvwvk.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gtbgjfhila.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gtnbopmuce.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gtirpwnzri.html

list(zip(*m))
来源：http://dali.havefunace.top/Article/details/gttaymonrz.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtvphzqnog.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtddakmeix.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gtryvsdell.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtioepjyum.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtznelzoir.html

csv.DictReader(f)
来源：http://dali.iojbl.cn/Article/details/gtwsoxijwz.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtpqxtofwd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtewihtuhs.html

[U27] Py：异步 HTTP
来源：http://dali.0kj1m.cn/Article/details/gtfoqpyezf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gtlbxdlsyy.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtjteaeqll.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gtxlgkuzuo.html

[U29] Py：属性校验
来源：http://dali.sysykeji.top/Article/details/gtlsmfsdhe.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gtrlxrlnie.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gthzewqtdu.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gtkdppghlt.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gtftcyfwba.html

python -m pytest -q
来源：http://dali.hongshengwenyu.top/Article/details/gtzjptvfym.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtngbjiafq.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdruosmwu.html

[U33] Py：打包发布
来源：http://dali.yueranfly.top/Article/details/gtrirwflvz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.316326.xyz/Article/details/gtmlczvaur.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gtzqozufow.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gtdjremklh.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqvtaeii.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gtpwiykhej.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gtxeabnqmt.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gtmysgyvfs.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gtkxluwilg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gttcacrwuv.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gtdwvmpojf.html

Path(__file__).resolve().parent
来源：http://dali.guannengcc.top/Article/details/gtkaapivxc.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gtmeslatjb.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtkfblutdm.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtnjwfsdgu.html

print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkegvbby.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.vqdsnc.cn/Article/details/gtcezemvnd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gtnkezodlc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gtbnpsqwhd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shangyingyoupin.top/Article/details/gtfbeyxbux.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtytlwdplt.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtgxijdllj.html

[U44] PHP：开启严格类型
来源：http://dali.zhoulong.xyz/Article/details/gtjusncmam.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtvhkenxpt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtlbwjgrnf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtxgfkrzsu.html

[U46] PHP：可空类型
来源：http://dali.tanke756.top/Article/details/gtfsxuxbtj.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gtqfbvfdzd.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiztwain.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gtvzuwserg.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gtmjkktipw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gtygjnpzts.html

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gtbshxravt.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gtzmtnvzgv.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gtxanfhchq.html

public function __construct(private int $id) {}
来源：http://dali.jqgufenzy.top/Article/details/gteoydlsky.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gtdznsfkae.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gtzawzzdvh.html

[U52] PHP：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtsnwradpx.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtutvsoeea.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gtivaiqazw.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtbcolfafj.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtvpryymku.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtjxwdowfd.html

[U55] PHP：match 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtsbvihocr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xinyue.icu/Article/details/gthjkeuire.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtpimhwgzz.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtiqqydykp.html

[U57] PHP：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtyaouanyq.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gthellglhj.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtjolgfipb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gtkkypuium.html

[U59] PHP：自定义排序
来源：http://dali.tianlin.xyz/Article/details/gtookfaeld.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gteuinpudm.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gtsbnswkik.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gtugmfzldk.html

[U61] PHP：正则
来源：http://dali.cucudq.cn/Article/details/gtmhxbfnzf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtxjhgpofn.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gtmqkritvv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtwvwiycoe.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gtxwwvhers.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hfpthk.cn/Article/details/gtdbgnpymk.html

[U64] PHP：目录遍历
来源：http://dali.jyoumei.cn/Article/details/gtpnihvcmp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtnvpqtoml.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtclnimafs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtjnxxcwqd.html

[U66] PHP：设置 Cookie
来源：http://dali.dashuyun.cn/Article/details/gttjlxuyos.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gthbyzxhhw.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtrgdtqpco.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gttqouuduz.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigufen.top/Article/details/gtdaleulpg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthggffblj.html

[U69] PHP：PDO 预处理
来源：http://dali.pengpengdd.cyou/Article/details/gtfiefomcj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtqfbnxzza.html

[U70] PHP：PDO 事务
来源：http://dali.daxiang520.top/Article/details/gtwlozkneb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqplqeqdq.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtfrwqwsux.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gtcbxppciq.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gtcxflcdbw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtabbrdfxm.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gtahwtmggh.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gtbigewhzj.html

[U74] PHP：读取环境变量
来源：http://dali.yj202588.top/Article/details/gtkcjfevri.html

getenv("APP_ENV") ?: "production"
来源：http://dali.9152youxi.cn/Article/details/gtzbllydzm.html

[U75] PHP：依赖注入
来源：http://dali.yvedp.cn/Article/details/gtdrnntexr.html

composer require psr/container
来源：http://dali.vqdsnc.cn/Article/details/gtuxnvckew.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gtgtpjuxth.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gtwpnkzjkx.html

[U77] PHP：模板渲染
来源：http://dali.sysykeji.top/Article/details/gtmucjfxpo.html

composer require twig/twig
来源：http://dali.yueranfly.top/Article/details/gtovmrzlum.html

[U78] PHP：单元测试
来源：http://dali.yj202588.top/Article/details/gtbdiyqfoh.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gtfrlioizr.html

[U79] PHP：静态分析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyddzpxrb.html

composer require --dev phpstan/phpstan
来源：http://dali.xuanzx.com/Article/details/gtiijylams.html

[U80] PHP：代码规范修复
来源：http://dali.meibo888.top/Article/details/gtpflfzwon.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtuwsgqedf.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gtxbvsuhux.html

npm init -y;  npm i express
来源：http://dali.havefunace.top/Article/details/gtvhltjxhy.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gtudqbpawh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhengqikj.top/Article/details/gtrviaqjek.html

[U83] JS：ES Module 导入导出
来源：http://dali.cheryme.top/Article/details/gtpdsocnbs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtvlyxzvhk.html

[U84] JS：CommonJS 写法
来源：http://dali.vqdsnc.cn/Article/details/gtatztcayf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gtqphaatvf.html

[U85] JS：可选链
来源：http://dali.shuidangran.top/Article/details/gtasusyqje.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gtxyukulzi.html

[U86] JS：空值合并
来源：http://dali.yuxming.cn/Article/details/gtzwvltyjf.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gtcnepladc.html

[U87] JS：解构默认值
来源：http://dali.yuxming.cn/Article/details/gtosqravtz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gtjajkilfb.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gtuahswapr.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwytfujzf.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gtamwxbsmz.html

[...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrbkwwve.html

[U90] JS：数字数组排序
来源：http://dali.tanke756.top/Article/details/gtvqajpfga.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtlbhuraed.html

[U91] JS：对象键值遍历
来源：http://dali.gotoacloud.top/Article/details/gtfrmhoxee.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gtnpanuxqd.html

[U92] JS：深拷贝
来源：http://dali.dianchejie.cn/Article/details/gtocmeruux.html

structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtgmhqmdkv.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gttzsxgotu.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtxsvaafuk.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gthcjqfxtl.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtkhsdcqoa.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gtqlegzooh.html

new Promise((resolve, reject) => {})
来源：http://dali.kuanghao11.cn/Article/details/gtgryseuot.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gtblzccwsn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtkzavvvzi.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtrovdnjjo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtocowhhxu.html

[U98] JS：fetch 带 JSON
来源：http://dali.cucudq.cn/Article/details/gttiffzjgr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gtdvhuxpbb.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gtfigbdadc.html

el.addEventListener("click", e => {})
来源：http://dali.sufxvd.cn/Article/details/gtdjeauxrr.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtgumqbchc.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gtlqehjkyd.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gtnefqbwae.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gtxpfaqrdu.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gtunlsenxp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gtpncofjvd.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtfchvvmsz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.c1oappe.top/Article/details/gthjncdxla.html

[U104] JS：防抖
来源：http://dali.guannengcc.top/Article/details/gtyhqyixjq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtstelufho.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gtnfbbjfvt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtrknmsjxa.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtchimhboh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gtsvgufqyc.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gtixlrgcuw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtdlfklwvj.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gtpnprwzgo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gzhubu.top/Article/details/gtjqbcaecz.html

[U109] JS：数组分组
来源：http://dali.haohaochexian.top/Article/details/gtaqggttnl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtabapiilp.html

[U110] JS：数组分块
来源：http://dali.xuanzx.com/Article/details/gtxugjibyd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gtogbpggqp.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gtsbciykea.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gtjygshwxz.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gtlwcjoukx.html

"7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtflfzvzho.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gtypodewti.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtjjyojdlf.html

[U114] JS：JSON 深比较
来源：http://dali.c1oappe.top/Article/details/gthcyvfxki.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtcdztfkau.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gttfksnsvt.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtftqymhwn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gtizjmmmze.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkdlqyem.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtpqgqokpd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gtafpxxeay.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtuazqvdbn.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gtombcdvny.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gtdyiyeuhf.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gtnsnqhxln.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yvedp.cn/Article/details/gtafqxpktk.html

import.meta.env.VITE_API_URL
来源：http://dali.yuxming.cn/Article/details/gtzsjllmpk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqdkahaqo.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gtmzwxbinj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgnllojlp.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gtzxdufxbz.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gtayyvbviv.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtheyvlicg.html

JavaScript ..... 252
来源：http://dali.cucudq.cn/Article/details/gtfnyfgazk.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtcwgqthfx.html

Java ........... 212
来源：http://dali.fzhhl.top/Article/details/gtvwochiph.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtvihrbgyb.html

Ruby ........... 212
来源：http://dali.yonumen.top/Article/details/gtxaeohfda.html

C# ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcktthtia.html

C .............. 30
来源：http://dali.jyoumei.cn/Article/details/gttdpoytsh.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gtsfprdhwl.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gtqzttkiby.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gtzuaweefw.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gtghywdqzp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtmnmsefnd.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtikekuyxf.html

Perl ........... 10
来源：http://dali.gotoacloud.top/Article/details/gtfxaovvtv.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gtykrkcqpy.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuekydmpe.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtcopasdkz.html

按章节统计：
来源：http://dali.xziqi.cn/Article/details/gtzfaaqftx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtohmfwmyf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtlghddfex.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtjxuiffkp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtrcpegmht.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yongpay.top/Article/details/gtskrvisuw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtxlfbniju.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtgwgbcuuh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtxqlndjaf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtumifkqqn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtmtfmhrwn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtybwrdjmo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtvphsrfjx.html


<!-- 参考信息 -->