代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gtugdrqxob.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gtwnrjjffe.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gtfncaglhf.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtqindtwdn.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtnhwxuewf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gteutimjrw.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtezdtgbff.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtdkuhmuqj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gtdnufoxvy.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtripmzpza.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtbijoiluo.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebryngfx.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtqgimjdfv.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtnxoxtosu.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtszwtszij.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtnjcyqhbn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtamkmadbx.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtqflsvsib.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtnpafigsz.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtmxmundhx.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtacshlwxk.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtnticjfuv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtpqsyogth.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaehykch.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtpstpktku.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtbwwiheaz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtbesngbuh.html

[T60] Scala：折叠
来源：http://dali.gzhubu.top/Article/details/gtexpqcyok.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gtrtapkhim.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtevecnwgh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtwnepdbto.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtegdokiga.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtrjvbjvwe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gtxljzpkqe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gtkdklwbki.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gtxjdkelww.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gtvaeccnfl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtrfccrpsi.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtpwofdqlv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtlnzxfmhs.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gtsxyagujz.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtblptmail.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gtqzyuipsy.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtovywacwi.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gtkwipwyqr.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gtjuvmhpzu.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gtexooinny.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gttxebrgke.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gtxemznswb.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtqepeuhpe.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gtuejxlyoy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtvrvteiea.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtseilttpu.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gthrgzfzlu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtjdcmdvgo.html

Counter(arr).most_common(3)
来源：http://dali.yanxiufei.cn/Article/details/gtssjrxupf.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gtdfzrvyjd.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gtaosfnawe.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtgtzjmdxy.html

defaultdict(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtckvcwiec.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gtgzceooxn.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtbqnmrlem.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gtqiwyfsgd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtprtwbgna.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvqtmctd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gtytsindkx.html

[U18] Py：预编译正则
来源：http://dali.fengsongda.top/Article/details/gtnyysaptk.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gtyogofjwb.html

[U19] Py：正则替换带回调
来源：http://dali.gzhubu.top/Article/details/gthcpnktky.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtjqykfgqu.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtkuympebg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gtghnrbyrz.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gtznrsmwqf.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gtdmszfhcf.html

[U22] Py：矩阵转置
来源：http://dali.feifeiyinyue.top/Article/details/gtzehadfej.html

list(zip(*m))
来源：http://dali.hongshengwenyu.top/Article/details/gtkxyafpak.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gtefruhbbq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yanxiufei.cn/Article/details/gtjfulqigf.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtyfrdocme.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgsxwyna.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gtellfauel.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtagjvheys.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhjcewfy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gtdtuojryz.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtuqurkvnt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhoulong.xyz/Article/details/gtuiawgpdb.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqqmejva.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtejmmkkbb.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gtrsntqzgb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gtmztuijtk.html

[U30] Py：数据类
来源：http://dali.xylfe.cn/Article/details/gtxqisxtyq.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtsfmagifk.html

[U31] Py：单测
来源：http://dali.havefunace.top/Article/details/gtbvxlzerj.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtkociflsv.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gttmvkfeaw.html

ruff format . && ruff check --fix .
来源：http://dali.guowangkeji.top/Article/details/gtdunkemcj.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gtxufidlmw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gtaajxpfir.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gtxencqpwp.html

chardet.detect(raw)
来源：http://dali.chenlongwang.top/Article/details/gtqzatlxdo.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gthfakpbyh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtebbqyvhw.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gtcqlosout.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gtpahbcnxg.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gteaqyqajo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawivgric.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtnwibekzd.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gtbxwdwbei.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gtsxnnaixr.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtwxbwcsbt.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtuwnizawi.html

print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtqmyxbvot.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gtrvxkwdwq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgfzy.top/Article/details/gtytjxqdtd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gtquzziepy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gtdvzxeqze.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtrozkxcuc.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gtbzoauvxg.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gtvnedduys.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gtnevuhsym.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gtvuehwtwp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtsdhzpxwq.html

[U46] PHP：可空类型
来源：http://dali.cqqwz.cn/Article/details/gtzgvlrkhu.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gtwhwbrzmv.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gtvykdwhta.html

int|string $id
来源：http://dali.jyoumei.cn/Article/details/gtmwpgzdte.html

[U48] PHP：纯枚举
来源：http://dali.yj20258888.top/Article/details/gtisivekba.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gtgmziyhnb.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gtfebpqrdq.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtqrducpnz.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gtzfcihofq.html

public function __construct(private int $id) {}
来源：http://dali.bjfxy.top/Article/details/gtwgmjfzqb.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gtuopclicb.html

[$a, $b] = $arr;
来源：http://dali.dashuyun.cn/Article/details/gtmecotdos.html

[U52] PHP：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gtlsvrgwah.html

$double = fn($x) => $x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtyqftupri.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gtkvcmnhax.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gtgtnvdvhg.html

[U54] PHP：空安全调用
来源：http://dali.aibaodan.cn/Article/details/gtxswmmmbo.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtihwnpipk.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gthpeggjdt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gthzcvufjp.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtkwwvojkp.html

f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtnmqmvvtf.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtprysbpop.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gtwiagmstw.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtbtknppvr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gtqhkdjzhc.html

[U59] PHP：自定义排序
来源：http://dali.sweek.top/Article/details/gtwtbzfkbv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtujcjbfjn.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gtzauiiuih.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtlmlxzgyb.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gtvvnwejon.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtwekngs.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gtihvcduiw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sysykeji.top/Article/details/gtqdumdimo.html

[U63] PHP：文件读写
来源：http://dali.cqqwz.cn/Article/details/gtglbqbkug.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gtsowmymao.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gtshyxwafe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gtytmuksud.html

[U65] PHP：会话
来源：http://dali.jlsjyb.cn/Article/details/gtthgmcuto.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtdoyjzpqu.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangtech.top/Article/details/gtoudvcgrz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gtmmlgicvb.html

[U67] PHP：处理文件上传
来源：http://dali.wangshuangyany.cn/Article/details/gtnrvlxqmg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gttqvgnhpg.html

[U68] PHP：PDO 连接
来源：http://dali.tanke756.top/Article/details/gtpnrbkgtu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shuidangran.top/Article/details/gtduvccqvq.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gtbxxssqlf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hammf.cn/Article/details/gtilbfpxpd.html

[U70] PHP：PDO 事务
来源：http://dali.c1oappe.top/Article/details/gtpezhwulh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fengsongda.top/Article/details/gtwpkfmsrd.html

[U71] PHP：抛出异常
来源：http://dali.havefunace.top/Article/details/gtcaywauiw.html

throw new RuntimeException("失败", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtkynozhll.html

[U72] PHP：写错误日志
来源：http://dali.havefunace.top/Article/details/gtamzukevy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj202588.top/Article/details/gtkayxymqr.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gtdmetzyzr.html

parse_ini_file("config.ini", true)
来源：http://dali.zycfv.cn/Article/details/gtuohqcgzc.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtkowpldte.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gtedjxtncb.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gtgdqgkzym.html

composer require psr/container
来源：http://dali.nanxuanxn.top/Article/details/gtafkfqnhd.html

[U76] PHP：简单路由
来源：http://dali.xziqi.cn/Article/details/gtfwyleygh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gtycmpmorx.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gtpdrtknbt.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtllbphyvi.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtrlanbxkc.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gtaqzaivhp.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gtjqsbtich.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gtdyuyvohi.html

[U80] PHP：代码规范修复
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchwenlbg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.meibo888.top/Article/details/gtizrxpqzb.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gtmwcesxzb.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gtlhafwszg.html

[U82] JS：package.json 脚本
来源：http://dali.xuanzx.com/Article/details/gtkuxiyvjy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gtcbnkksxu.html

[U83] JS：ES Module 导入导出
来源：http://dali.xinyue.icu/Article/details/gtdwcomelc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtteilfmpi.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtequsgijc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gtouxcxvjf.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gtmwmndtpt.html

a?.b?.c
来源：http://dali.cucudq.cn/Article/details/gtfkcimcdz.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gtrsmzinpv.html

a ?? b
来源：http://dali.ehwqpu.com/Article/details/gtpgckzrls.html

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gtnekauipv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gtcofsqrrs.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gtghuokknv.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gteiuajjrr.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gtllsjskgk.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtkvailfju.html

[U90] JS：数字数组排序
来源：http://dali.tian-w.cn/Article/details/gtdsnhrwtd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtozowssmg.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gttcigllib.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangshuangyany.cn/Article/details/gtveqvvmlf.html

[U92] JS：深拷贝
来源：http://dali.xinyue.icu/Article/details/gtzynbjdmd.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtkcsmiuca.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtpwtihyed.html

`共 ${n} 条`
来源：http://dali.yuanzhike.top/Article/details/gtlhoofook.html

[U94] JS：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gtneswaxfb.html

const double = x => x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtazcjyvuj.html

[U95] JS：Promise 包装
来源：http://dali.jlsjyb.cn/Article/details/gtavxmbdgn.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtumsfgtlh.html

[U96] JS：async/await 与异常
来源：http://dali.andypj.xyz/Article/details/gtjymyuxuz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtytlfoqge.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gtzhutpaog.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtpfwhigko.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtwqikriaa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnqzz.top/Article/details/gtpckmjhvp.html

[U99] JS：事件监听
来源：http://dali.havefunace.top/Article/details/gtcbxhhejr.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtzcevrckk.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzlszkyg.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gteykprurw.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gtljazyxpl.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gtslsytvdo.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtdslzmpdc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtuyptoqcw.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gtdllnqbfy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jianghu66.top/Article/details/gtqzjtkfjh.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gtzngquyon.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtybebuirx.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtrobettpn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ivvv.top/Article/details/gtpeodtmxo.html

[U106] JS：日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtojfipkxb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gtxbxmbqtq.html

[U107] JS：数字千分位
来源：http://dali.shuidangran.top/Article/details/gtbtwoayqf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtuuyyytdh.html

[U108] JS：随机整数
来源：http://dali.fengsongda.top/Article/details/gtvvulqqbc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gtmpeewahp.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtxqiyrb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtfpikwvfo.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gtqqqsfrxm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aizwys.cn/Article/details/gtdecirucm.html

[U111] JS：对象转 Map
来源：http://dali.sxryk.cn/Article/details/gtoruejqmc.html

new Map(Object.entries(obj))
来源：http://dali.pycfn.com/Article/details/gthnwrkhkl.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gtgtrkabcx.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtxjyyshvm.html

[U113] JS：正则替换全部
来源：http://dali.snrcjt.cn/Article/details/gtvcvucgbn.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtebpwsmrc.html

[U114] JS：JSON 深比较
来源：http://dali.hongshengwenyu.top/Article/details/gtlavcawvt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtoaugzmjm.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtndugmaay.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtwtjfecbh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtqvopeuof.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtpjyruiqr.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtwogfxoib.html

npm i -D vitest;  npx vitest
来源：http://dali.sxryk.cn/Article/details/gtmoephtoa.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gteezpletx.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gtiamytmnl.html

[U119] JS：生产构建
来源：http://dali.svipenyu.cn/Article/details/gtdqmavxtj.html

npx vite build
来源：http://dali.daria6918.cn/Article/details/gtmxusvffs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gtwiwvupcn.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiplhcspl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtaleekboh.html

统计汇总
来源：http://dali.chenzaomai.com/Article/details/gtazvfsbax.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttfkdpoln.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtiwsaqsuq.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gtwakpwlsf.html

PHP ............ 252
来源：http://dali.xinyue.icu/Article/details/gtrrrbhvqu.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gteyzdizzv.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gtnsqbiwls.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gtzjgztlsm.html

Go ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqdoljdq.html

Ruby ........... 212
来源：http://dali.cashguo.top/Article/details/gtodhjoshk.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gttivezmcd.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gtctrljrzw.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gtbhbckgto.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gtopndrhnl.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gtvbfvikfr.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gtutipalbi.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gtzlenjnhl.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gtrnrjqxsu.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gtdgtakiis.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbkqsbfx.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtvtujmcbg.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtayidrhtk.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gtooubwjzq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtwaovtuxu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtszavcswm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtlhrokqxy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtidhdjqvq.html


<!-- 参考信息 -->