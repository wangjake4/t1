代发 wailian999

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtixehzarp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtouuxmzpu.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtshwlzegk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtggavuvqp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtcewoulvl.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gttqudqrxx.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtuenzgfut.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjvbjypgf.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtdoxnvwlc.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtugymirue.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjagnaif.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtajadahau.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtzwnnqput.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtgohiqdaj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtnlsvhgch.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gthvcpnlti.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqzlntmo.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtqxgdrjda.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtxychmpvj.html

[T58] Scala：函数定义
来源：http://dali.hammf.cn/Article/details/gtgluopjkh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtxedsisyz.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtuexrsuaz.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtnijcndpw.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gttsfjxkqd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtitatvnlk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrjpatxnn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gtttccpulc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtolfuryir.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtxdfdrhqk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gtpafhzkxi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlyanxds.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtcnxkaesb.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtepfhntix.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtwisxpvzt.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypkwfhut.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtxxsypbkj.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gtbboazbfl.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtvfrorzqi.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtudnjotyb.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtizmubgmn.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtkgzphdnw.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gtgsqvwzsh.html

[U08] Py：展平二维列表
来源：http://dali.ydzc1.top/Article/details/gtzdlacelq.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gthsdnyfbp.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtyzgmreob.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtaaqiedwv.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtzrpbklef.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gtexwrlcuj.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuzbtgfg.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtfxxozbtd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtpkmmagut.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gticrbxgtr.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtncbhxfid.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gtirfrkswk.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gtrfjujrpx.html

defaultdict(list)
来源：http://dali.dianchejie.cn/Article/details/gtzdbtigod.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtmrwtsgww.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gtfljplupy.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtxuzlxcyg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtbfwztzqw.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gtatuvffsm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gtzbhqlvxg.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtuiumommm.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtbpysurxn.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gtgsqolafl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtvlvfbfaw.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gtfkrnepve.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hywenlv.cn/Article/details/gttqzwtviz.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gtfpstwlmv.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gtjhbzeobt.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gttqacimej.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgkcvtwy.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gtjxvacbet.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daria6918.cn/Article/details/gtyovkofuj.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gtnezbitbn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtcmnodkly.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gtbmtdugpg.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gtjsxfqwqx.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gtxeawuiao.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtqmhswtgn.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gtcbuzwxux.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gtdkgzewsx.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gtijcufysg.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gtdpjcepdt.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gtmkigbatq.html

@property 与 @x.setter 配合
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgsqqgbt.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gtytnxqnyk.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtwstxsjxn.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtrrakvpkb.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gtrtkrrhwh.html

[U32] Py：代码格式化
来源：http://dali.cucudq.cn/Article/details/gtldthqqfb.html

ruff format . && ruff check --fix .
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrlswivv.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtwayyeavp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fzhhl.top/Article/details/gtqzldmdnl.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtaqoefyho.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gtpxssqcxd.html

[U35] Py：发送邮件
来源：http://dali.mhx1999.top/Article/details/gtgwfyxvxi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gteumaimwe.html

[U36] Py：定时任务
来源：http://dali.hfpthk.cn/Article/details/gtlyfkhtxu.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangshuangyany.cn/Article/details/gtbthemwki.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gtklgpvref.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gtpubvyzff.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtksrcymps.html

Path(__file__).resolve().parent
来源：http://dali.jqgufenzy.top/Article/details/gtmuqgxubi.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtippbmhhj.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gtmiuvzajg.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtrdyijrqd.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtjxgspgdj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gtwqjxiwsw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gtknjtttav.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gtdybkgubi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrybfgnum.html

[U43] PHP：声明命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtyjcnzljb.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gtncilzgmr.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gtslasnwlr.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gtjfsxeupv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gtgiedgzdt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtxxevzicj.html

[U46] PHP：可空类型
来源：http://dali.guannengcc.top/Article/details/gtpjhsgnla.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gtmjnniufb.html

[U47] PHP：联合类型
来源：http://dali.mhx1999.top/Article/details/gtudquwdze.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gtcneuwsck.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtkhglesgj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gtcicrxdgg.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gtzaurewhe.html

public readonly string $name
来源：http://dali.kuanghao11.cn/Article/details/gtbyffacoj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtwpbmlepy.html

public function __construct(private int $id) {}
来源：http://dali.ppjwa.cn/Article/details/gticnunsgo.html

[U51] PHP：数组解构
来源：http://dali.yongpay.top/Article/details/gtcqlraojs.html

[$a, $b] = $arr;
来源：http://dali.ybcxt.top/Article/details/gtprdengwp.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtkwxkfxwd.html

$double = fn($x) => $x * 2;
来源：http://dali.hnqzz.top/Article/details/gtzuolzgcl.html

[U53] PHP：空合并运算符
来源：http://dali.yongpay.top/Article/details/gtvarzquet.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gtxlgvbthk.html

[U54] PHP：空安全调用
来源：http://dali.dashuyun.cn/Article/details/gtvqmevyey.html

$obj?->method()
来源：http://dali.aibaodan.cn/Article/details/gtvodihifo.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkjkodjs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gtmmvmdnfp.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gtlsivnlnh.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtlqffureo.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gtzzjkwgjo.html

"值: {$a}"
来源：http://dali.yj20258.top/Article/details/gthopcwykq.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gtwtqdlmle.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gtktushbmu.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gtmgxekplr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtxohocmlf.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gtaibxpkyt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gtfomejxes.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gtjcijjohb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtlddvyqjy.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gtngtvyqwv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigfzy.top/Article/details/gtvpgtmmqf.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gtxielndlv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gtkzkjqjsq.html

[U64] PHP：目录遍历
来源：http://dali.gotoacloud.top/Article/details/gtxtdzbqqk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtareingss.html

[U65] PHP：会话
来源：http://dali.haohaochexian.top/Article/details/gtgrlmqsqg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtzzawwrqp.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gtoyqdfqbo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hammf.cn/Article/details/gtlhyqtely.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtneiullzg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gtkxbchkcp.html

[U68] PHP：PDO 连接
来源：http://dali.xinyue.icu/Article/details/gteymmqicm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gtcdmrqdhe.html

[U69] PHP：PDO 预处理
来源：http://dali.pengpengdd.cyou/Article/details/gtbksmfxth.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yangfankeji.com/Article/details/gtbufozzce.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gtlgwhriep.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtwjapcagk.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtkyrdpdui.html

throw new RuntimeException("失败", 500);
来源：http://dali.dianchejie.cn/Article/details/gtrjxrxxki.html

[U72] PHP：写错误日志
来源：http://dali.9152youxi.cn/Article/details/gtyfhtoyru.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gtfgxjjify.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuxming.cn/Article/details/gtvfnlwamt.html

parse_ini_file("config.ini", true)
来源：http://dali.sweek.top/Article/details/gtzrcmnxdl.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtfeqqyfvv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtstparamg.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gtzkpfcvgi.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gtfzjcxkoy.html

[U76] PHP：简单路由
来源：http://dali.nanxinkj.top/Article/details/gttmqmluzj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtyqayjghr.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gtxlmklmrx.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gtncacqsvd.html

[U78] PHP：单元测试
来源：http://dali.yvedp.cn/Article/details/gtfriqcuyu.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gtzixaiwyy.html

[U79] PHP：静态分析
来源：http://dali.haohaochexian.top/Article/details/gtjrtfrdgn.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gtomwfudva.html

[U80] PHP：代码规范修复
来源：http://dali.daria6918.cn/Article/details/gtwwobtrat.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xylfe.cn/Article/details/gtvgpaugae.html

[U81] JS：初始化项目
来源：http://dali.cqqwz.cn/Article/details/gtjmtipnrm.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gtdebawgww.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gtvakuamxv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgufenzy.top/Article/details/gtxbdsbktw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gtwetgjxfc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtjgbmslat.html

[U84] JS：CommonJS 写法
来源：http://dali.aizwys.cn/Article/details/gtlmiosnuu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhiwuduotai.top/Article/details/gtrmxyezot.html

[U85] JS：可选链
来源：http://dali.zhongyouzk.top/Article/details/gtbbfwkjxd.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtmfqyjpxw.html

[U86] JS：空值合并
来源：http://dali.jqgfzy.top/Article/details/gthyngzzzt.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gtobouhvzj.html

[U87] JS：解构默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleuifukf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gtrputpmst.html

[U88] JS：对象展开合并
来源：http://dali.gzhubu.top/Article/details/gtlsjcruat.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtaqedzgrs.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gtstqyycrk.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtbdhsptjs.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtegwgbqgn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtbujtdmns.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gttquwgbgs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.redwolf501.top/Article/details/gtrkivdtwq.html

[U92] JS：深拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtpbjfytqu.html

structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmclpywdc.html

[U93] JS：模板字符串
来源：http://dali.gotoacloud.top/Article/details/gtcxypputx.html

`共 ${n} 条`
来源：http://dali.yj20258888.top/Article/details/gtzkjcqipu.html

[U94] JS：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtcmnwlfft.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtocamomfu.html

[U95] JS：Promise 包装
来源：http://dali.birdmap.top/Article/details/gtefryogwd.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtyelwfshn.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gtzmygbchl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtunjovmxc.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrrkuuum.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvdwqmgt.html

[U98] JS：fetch 带 JSON
来源：http://dali.0kj1m.cn/Article/details/gtqjxughvi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gtxnklukur.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gtbqvndndp.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gtixbklnwd.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtbqpeybbj.html

document.querySelector(".item")
来源：http://dali.ydzc1.top/Article/details/gteecsikgb.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtkgkxjtkq.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gtvlvvnovl.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gtwlbagmxo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gtvgwhyiss.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gtqcydigxw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtajvqqego.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gttmznbxag.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmfqkazb.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuvokoyd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtnnsvikcg.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtuhezoaex.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gtkxsudksw.html

[U107] JS：数字千分位
来源：http://dali.fengsongda.top/Article/details/gtupozlszi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtcbfhyjni.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gthaoxnkmb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenjidiqi.icu/Article/details/gtyuvrentq.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtkwmkcyvf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gthaoqwzvf.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gtgouhijsh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangshuangyany.cn/Article/details/gtnqkocapy.html

[U111] JS：对象转 Map
来源：http://dali.zycfv.cn/Article/details/gtfmeppiqy.html

new Map(Object.entries(obj))
来源：http://dali.0kj1m.cn/Article/details/gtiktmexse.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gthutiamiw.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtlqhfmuky.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtfyphtvxx.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtjviztgyq.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gtrrsylmau.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthepgvwni.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtmwdfjsdj.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtnwmtzvft.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtlwausyyv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttmgxyqap.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gtcsfpfdmu.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gtnxiiertj.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gtyfafgvea.html

npm i -D vite;  npx vite
来源：http://dali.ybcxt.top/Article/details/gtzromljgv.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gtwilghyvh.html

npx vite build
来源：http://dali.ybcxt.top/Article/details/gtkwqzeisb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gtkioarmxv.html

import.meta.env.VITE_API_URL
来源：http://dali.shangyingyoupin.top/Article/details/gtrirapkpd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtirwdcudo.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gtzrpzuwyk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtokbojpdv.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtlwqvrtbi.html

Python ......... 252
来源：http://dali.shuidangran.top/Article/details/gtkiksgrwx.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtqvmoflmn.html

JavaScript ..... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtkrwbyxzs.html

TypeScript ..... 212
来源：http://dali.yj20258888.top/Article/details/gtntgisxan.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gtikqqoing.html

Go ............. 212
来源：http://dali.yueranfly.top/Article/details/gtxagwklhn.html

Ruby ........... 212
来源：http://dali.jianghu66.top/Article/details/gtimxkqatr.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gtpwnzubxw.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogaeadst.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtjoylzazn.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gtytgfptfh.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gtuzffdpez.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gtohcsliql.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtokucbsrh.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtudasdlum.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gtaxjbwjqf.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtyxqzgxvu.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gteybytxsj.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gtdvrwvfwk.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtqajwowpy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtjbrhkefb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhvukfni.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gteeuvirqf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gttqgxmdvu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gtotcbjkjv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtbnuxultu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gttefbaqcz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtfmnnxaff.html


<!-- 参考信息 -->