代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gtyloqrqjs.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtnzxapusl.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtkytegtby.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yonumen.top/Article/details/gtvqvhoxjg.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gtkeaflpsv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gtdtyjcrsj.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtreulzgyz.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtgwakyvdt.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gttthqdpmj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gthkhgxwim.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtkzwejzjl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtjccbxjax.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gttlwszafe.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtnjdqemmb.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtqpdwtvra.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtyibpjldz.html

val a = 1;  var b = 2
来源：http://dali.zdqjudy.top/Article/details/gtvdjhomkd.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtwasfbplw.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtllbzppbl.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtnzygoqgt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtataasiip.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gttalaztbo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtsmctojct.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtqvacutcw.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtfqticdxr.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtbgupqmrv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwxmshja.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gturjvhupf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gtxpwwvjuy.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtxfgjdhzp.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtfoshkdut.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtyvenaaam.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmhtnqjh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtetbybncv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtemgrctyf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxlqttedd.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gthqslynfy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtuorljwne.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtuqbebeir.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gtgpjaykyd.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtsklmxnko.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gtcnqlxwim.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gtgpxfzcbm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtgldxkjkq.html

[U05] Py：列表去重且保序
来源：http://dali.guannengcc.top/Article/details/gtbpjjxllb.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtxhhheoun.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtnobythke.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gtkncvvgzu.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gtrtnumjxz.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtsujkhuqo.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtvggflwdz.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gtzphmgofn.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtcehzisex.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gtuacltibp.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtfyfosizy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gtnzwjrmdv.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gtzcwufzxl.html

(x * 2 for x in arr)
来源：http://dali.meibo888.top/Article/details/gtokzihura.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtzezzktjc.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtqnlujjrh.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gtcurqlirn.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtpzkqyjic.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gtebbhlpqd.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gtpbbiupup.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gtowgnizby.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gtzglzzlex.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gthtrawobq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtojzwpvfo.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gtrbftzdxe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtclnyqeld.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtpkkxwopi.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gteyjlnmjl.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gtnchgwbno.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gthvelkrek.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gtmyboycna.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gtxwxpuxuu.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gtatkkuiub.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtcuosdpsq.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbkimitm.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gteoortcdu.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gtczdwrmxi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gttcsiudgr.html

[U24] Py：路径操作
来源：http://dali.guowangkeji.top/Article/details/gtaogzwion.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtkhykbjwk.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyberili.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gthsrmwuym.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gtiwwpehkt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gtzonticav.html

[U27] Py：异步 HTTP
来源：http://dali.sysykeji.top/Article/details/gtgkddxeii.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gzhubu.top/Article/details/gtddqjjvln.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtjopoyvbl.html

UserId = int
来源：http://dali.sxryk.cn/Article/details/gtqeoenhdd.html

[U29] Py：属性校验
来源：http://dali.yuxming.cn/Article/details/gtjxqkebtb.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gtzoewzols.html

[U30] Py：数据类
来源：http://dali.iojbl.cn/Article/details/gtnxuklnxa.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gtvygwobvb.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gtbbxjhist.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gtidnchoum.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gtqwznemyt.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtdftlkbvu.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtvwqnwojx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtjalcdbbj.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gtmxnozykb.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gtqxyvecij.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gtpxlfkean.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ivvv.top/Article/details/gtmufcjdke.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtvuwuemcg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtqgnhxfei.html

[U37] Py：读写 Excel
来源：http://dali.yj20258888.top/Article/details/gtanmrhzow.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daria6918.cn/Article/details/gtnuhawnbj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtncsqfdxp.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gtozscqewf.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gtlwqngqfo.html

sys.stdout.isatty()
来源：http://dali.gotoacloud.top/Article/details/gtkfiuwsqe.html

[U40] Py：打印到标准错误
来源：http://dali.chenzaomai.com/Article/details/gtclqjvxln.html

print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtjqdfokyy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gtepyfmqfx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtifmludqp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258888.top/Article/details/gtqvyifqed.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtzoargdyd.html

[U43] PHP：声明命名空间
来源：http://dali.316326.xyz/Article/details/gtmtqwdxva.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gtnebwwzob.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigufen.top/Article/details/gtufneepwl.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtusgjzyuy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtooymiitb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtsxsmlwbi.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gtmacgxijv.html

?string $name = null
来源：http://dali.zycfv.cn/Article/details/gtnvagcetg.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gtmclqdnmo.html

int|string $id
来源：http://dali.yvedp.cn/Article/details/gtdziyzdpr.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gttcqexydt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gthwwoaezg.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gtpihfyuuw.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtrulyktjo.html

[U50] PHP：构造器属性提升
来源：http://dali.316326.xyz/Article/details/gtcvqdgpok.html

public function __construct(private int $id) {}
来源：http://dali.sweek.top/Article/details/gtdbkkaslv.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtxfbwsjdx.html

[$a, $b] = $arr;
来源：http://dali.zhoulong.xyz/Article/details/gtwmgbhskq.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtwmybwikm.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyfdohfl.html

[U53] PHP：空合并运算符
来源：http://dali.jqgufenzy.top/Article/details/gtqrsxzvdn.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gthwafusch.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtrvqxphia.html

$obj?->method()
来源：http://dali.hongshengwenyu.top/Article/details/gtvtidwqtt.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaobbiae.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gtodtipvcu.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gtftridcoe.html

f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtanlhnjub.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtuciowoyl.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gttxjwwkxc.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtzliygoml.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fengsongda.top/Article/details/gtrvjijwql.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gtzcztlwku.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtvafukmep.html

[U60] PHP：JSON 编解码
来源：http://dali.dianchejie.cn/Article/details/gtozhibiab.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gtzxswbrhh.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gtimqxhchi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtfygfnwmc.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtroypzxus.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrweucnau.html

[U63] PHP：文件读写
来源：http://dali.ydzc1.top/Article/details/gtirexnyzv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gttxlrnlsj.html

[U64] PHP：目录遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtfckxjwbi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gtrkkahspi.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gtadwqtjih.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtumzexhem.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gtdwkzhtwt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gtjwrireuz.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gtuxxlkxsh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258888.top/Article/details/gtrblnrjno.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtrvlnwnzy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtfvtnbhdo.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtyilffccz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtukpvqjzm.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258888.top/Article/details/gtzcmojvjz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ppjwa.cn/Article/details/gtjompkarv.html

[U71] PHP：抛出异常
来源：http://dali.daria6918.cn/Article/details/gtyhmlgebo.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gtwejrjpmm.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gtilmszppp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jyoumei.cn/Article/details/gtvinfcgry.html

[U73] PHP：读取 ini 配置
来源：http://dali.mhx1999.top/Article/details/gtzrzzanpx.html

parse_ini_file("config.ini", true)
来源：http://dali.havefunace.top/Article/details/gtfylbicks.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtkfixrdnc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zdqjudy.top/Article/details/gtcnsyudql.html

[U75] PHP：依赖注入
来源：http://dali.daria6918.cn/Article/details/gtvcvmjqqm.html

composer require psr/container
来源：http://dali.hammf.cn/Article/details/gtlczqcsct.html

[U76] PHP：简单路由
来源：http://dali.svipenyu.cn/Article/details/gtdctxgukd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtwwbbldxd.html

[U77] PHP：模板渲染
来源：http://dali.yonumen.top/Article/details/gtzgbxtfot.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gthpodtxum.html

[U78] PHP：单元测试
来源：http://dali.yj202588.top/Article/details/gtyuofpnaj.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gtlpvprqhv.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gteyrzlnvt.html

composer require --dev phpstan/phpstan
来源：http://dali.haohaochexian.top/Article/details/gttnvfokbe.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gtxavraxar.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hfpthk.cn/Article/details/gtzjkulbwn.html

[U81] JS：初始化项目
来源：http://dali.hfpthk.cn/Article/details/gtyvbbiouq.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gtydssthep.html

[U82] JS：package.json 脚本
来源：http://dali.tanke756.top/Article/details/gtvfhcjqlm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigfzy.top/Article/details/gtycszmbpm.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gtzsngbisf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtcttqathb.html

[U84] JS：CommonJS 写法
来源：http://dali.vqdsnc.cn/Article/details/gtqaxrepsc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gtwtzekisj.html

[U85] JS：可选链
来源：http://dali.chenjidiqi.icu/Article/details/gtbwscmdsc.html

a?.b?.c
来源：http://dali.xuanzx.com/Article/details/gtsyilfiqu.html

[U86] JS：空值合并
来源：http://dali.sweek.top/Article/details/gtyivncpzj.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtqcdfimhv.html

[U87] JS：解构默认值
来源：http://dali.hnxiangtu.top/Article/details/gtixxvkjzz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gthusizevz.html

[U88] JS：对象展开合并
来源：http://dali.yangfankeji.com/Article/details/gtsqemamao.html

{ ...a, ...b }
来源：http://dali.cucudq.cn/Article/details/gtqgojomtb.html

[U89] JS：数组去重
来源：http://dali.jlsjyb.cn/Article/details/gtwpzqgmhe.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkzowrgd.html

[U90] JS：数字数组排序
来源：http://dali.yonumen.top/Article/details/gtlfenageb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtzdvphguf.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtamcqxxiq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinghuilouyu.cn/Article/details/gtgheagaqo.html

[U92] JS：深拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvkxkmcb.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtxosestdv.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gtmwvsxelg.html

`共 ${n} 条`
来源：http://dali.mhx1999.top/Article/details/gtqsswhbse.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtewvmydpy.html

const double = x => x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtockbwmar.html

[U95] JS：Promise 包装
来源：http://dali.jqgfzy.top/Article/details/gtattexcha.html

new Promise((resolve, reject) => {})
来源：http://dali.wangdashe.top/Article/details/gttqaqulio.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gtokaygyin.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtafjgpkfs.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gtpkdpgibo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtkvjmjfgv.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgfzy.top/Article/details/gtjxmzzfdl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gtpzmzewcc.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtatllyutn.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gtbktsoxzk.html

[U100] JS：DOM 查询
来源：http://dali.wangshuangyany.cn/Article/details/gtmamewcmy.html

document.querySelector(".item")
来源：http://dali.redwolf501.top/Article/details/gtcdwokrnf.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gtegfmspwo.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gtiydwecgu.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gtsgppkydw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gtvvgxwymt.html

[U103] JS：定时器
来源：http://dali.haohaochexian.top/Article/details/gtxgtenmhq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gtosjiylwd.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gtvydkwlui.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtrykqibip.html

[U105] JS：节流
来源：http://dali.aibaodan.cn/Article/details/gtvmvraykq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtcpdrpfgo.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gthbzxfxmo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ydzc1.top/Article/details/gtckwjugby.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtisqsrudm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtqknwereh.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gtgfdpwzmw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gthejyvucu.html

[U109] JS：数组分组
来源：http://dali.ehwqpu.com/Article/details/gtvorzrhul.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtwztvcwpo.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gttjamjweq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtvrhkleec.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuoaxmiz.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gthammdozf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gttxoemtcw.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gttratmseu.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gtoqjedkvo.html

s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtjwzdbdrd.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtpuncqajl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtipuoiktt.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtixamyqaw.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtlxgrdwnv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtpqyzrqzf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jyoumei.cn/Article/details/gtiemsmtzb.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtfqpfgcns.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gtzwczmmty.html

[U118] JS：开发服务器
来源：http://dali.0kj1m.cn/Article/details/gtsqdqtjbk.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gthkpzxlgl.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gtxxjqrsgw.html

npx vite build
来源：http://dali.yuanzhike.top/Article/details/gtszybnrhc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwjutriv.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gttagwvyno.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfpyyrwjl.html

统计汇总
来源：http://dali.cdnleiting.top/Article/details/gtrkdzucug.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqavebfbx.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gtntehwvdt.html

Python ......... 252
来源：http://dali.tanke756.top/Article/details/gtkdxxwkkr.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gtmqefkyjx.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gtjkvfcwvm.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gtaraxdsmd.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtpokibuqi.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtaqfjdwtb.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gthsvtlngf.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gteindocjz.html

C .............. 30
来源：http://dali.xuanzx.com/Article/details/gtvtunmpji.html

C++ ............ 30
来源：http://dali.zhixingplan.top/Article/details/gtiwxsakqv.html

SQL ............ 90
来源：http://dali.birdmap.top/Article/details/gtakanfcow.html

Bash ........... 80
来源：http://dali.tanke756.top/Article/details/gtcdtclfkf.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gthojhxlht.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gtlkpzyhin.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gtbhclpwkr.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtmfeqrbxo.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gtusdzluiu.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtnxnpmrxv.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gtewskffpc.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtzvnhusyr.html


<!-- 参考信息 -->