代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtsgqcuclo.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtefbfyexo.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gtxfmbzofr.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gtrvrneunx.html

[T45] Perl：数组遍历
来源：http://dali.hysaishi.cn/Article/details/gtieesedhy.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtqjefkygp.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtqsvfjbnc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtsirbjwri.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtjgofgtdn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gtrgxtyysw.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gtnpiskody.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtswzvezjj.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtujhwmpjr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtowgwlbbp.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtglwqbvyg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gtpozjbfqr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gturehveys.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtxoahegcu.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmyfmugy.html

[T52] Scala：变量
来源：http://dali.jiagoushi.top/Article/details/gtbrfkbpvw.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gthczftrxr.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtorjxfoqm.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtuecxwkqw.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtufdndhrz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqvhhqjtc.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtakravtby.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gtafhnpram.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gtzalegnca.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtsoxkzkaz.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtwrlcxfaf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtnngahmzc.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gteucszjgr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxkxwtob.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtzlqikeuu.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtqtqdfdgb.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtxsmwjizw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gtmvgnupwq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgdnbppni.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtfsppafcw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtuoyxymeb.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gttmlwydzm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtufyxzlua.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gthdlnxqhf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gtsqhofjhq.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtbjvohjqk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtxwiajkea.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gtyfikpyvu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtzsszmott.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gthluzhkiv.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtckehlgsp.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtstuuarln.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtxhjoixpp.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gtiblhjxqf.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtpseoemmq.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtdixonrng.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtnegqmkun.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gtgxwpokyk.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gtgarfbgyj.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtzqvmycdo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gtbclbimln.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gtylstvepb.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfstieuu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtfpbxrfxq.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtadzwgggr.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gtrtytfhfd.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gtmrhsmxom.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gtdyzdknny.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gtembwjcua.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtbupxxuif.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gtfkpoeiyg.html

[U16] Py：命令行参数解析
来源：http://dali.havefunace.top/Article/details/gtzwtdeksu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtletzhgoq.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gtaldqzrlr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yongpay.top/Article/details/gtuirjecqt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtmbjaljpg.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmswrirab.html

[U19] Py：正则替换带回调
来源：http://dali.hongshengwenyu.top/Article/details/gtgskrzeot.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtjzkkbxoy.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtjspjkfuj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwbrjphn.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtdilzbjea.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtuefzggbg.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gtvydonlfg.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gtqnwitxxj.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gtjsrenhvd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gtbuhzolwb.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gtmzdnaxoo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtcdfopmaf.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gtgrsdntje.html

csv.DictReader(f)
来源：http://dali.aizwys.cn/Article/details/gtgbopzmci.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gtoqxkjfur.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtmjqgbwhz.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gteuozduze.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zdqjudy.top/Article/details/gtjxieetdk.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtiolzbgms.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gtlxydlfbu.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gtavcluudv.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gtqnxpzyah.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gtdmowwdkl.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gtfcafdxtv.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtetniipny.html

python -m pytest -q
来源：http://dali.chenlongwang.top/Article/details/gtgfyoyiyh.html

[U32] Py：代码格式化
来源：http://dali.cucudq.cn/Article/details/gtwvdusdcw.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gtsiscyoqz.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gtfqyrmixr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gtlhsivmol.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtnlicrkef.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtskowqbty.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gthphjzaza.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gtqzahipip.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gtzhwbqlza.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gtppukdllf.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gttiwbyydq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtsuuvvons.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszufqaba.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gtwrbpsdup.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gtcqotlyvc.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gtycmezqde.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangtech.top/Article/details/gthmhnrgbx.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtyunqmugf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gtdppdkorj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gtxoltryhf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.birdmap.top/Article/details/gtccmgdqjn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.0kj1m.cn/Article/details/gtgrpkescs.html

[U43] PHP：声明命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglcjilgw.html

namespace App\Http;
来源：http://dali.tian-w.cn/Article/details/gtmtajmblw.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtxynycwhl.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzyjteyw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gtkdydtzho.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtlnpwzbzd.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gtqywgzvty.html

?string $name = null
来源：http://dali.zhengqikj.top/Article/details/gtjnxthnvn.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gtnjvfhujr.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gtmjghngdl.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtwfsvwzao.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gtxlflnjbh.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gtllvssiku.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtpnybjkxz.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gtdyaqbmkw.html

public function __construct(private int $id) {}
来源：http://dali.pycfn.com/Article/details/gtnzhsbjih.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtibkhgusm.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gtzxtcfufq.html

[U52] PHP：箭头函数
来源：http://dali.ybcxt.top/Article/details/gttcjuwckm.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gtxczrzukh.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gtskdwbtgw.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtyirgebpo.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtmkmsjujy.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtfiiaebpt.html

[U55] PHP：match 表达式
来源：http://dali.xinyue.icu/Article/details/gtchjneitr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtcecqxusx.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gtrvqetsqs.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtnwqdyedm.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtgekzywuz.html

"值: {$a}"
来源：http://dali.iojbl.cn/Article/details/gtzbqgfmpc.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gtjrwwevjn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cucudq.cn/Article/details/gtewjjgeam.html

[U59] PHP：自定义排序
来源：http://dali.andypj.xyz/Article/details/gtebepouqp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtiylzbdfp.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gtasbuwrzj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gtjhlcksfp.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gtsmwetcyb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtnhyznpgr.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gtsnuztgjw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gtshzkavsa.html

[U63] PHP：文件读写
来源：http://dali.feifeiyinyue.top/Article/details/gtyrqocbaf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenzaomai.com/Article/details/gtjlagvaqk.html

[U64] PHP：目录遍历
来源：http://dali.yj202588.top/Article/details/gtldbbxsiw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shangyingyoupin.top/Article/details/gtzdlogsnx.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtefesvkck.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtbdnsbdzy.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gtpcpihjva.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gtxddvtgfj.html

[U67] PHP：处理文件上传
来源：http://dali.nwbrower.top/Article/details/gtyapumznq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gtygafikbc.html

[U68] PHP：PDO 连接
来源：http://dali.ybcxt.top/Article/details/gtyzhxjger.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gtoyvceupj.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gthdatxlkm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gteclsglyh.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtzvgnhoqk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xinyue.icu/Article/details/gtpvxnbtsz.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gtzpwjrefw.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gtsxolydze.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gtzzrahchn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gttedgiemr.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtiumkncbi.html

parse_ini_file("config.ini", true)
来源：http://dali.shangyingyoupin.top/Article/details/gtovkphmxy.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtxruuyokj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhixingplan.top/Article/details/gtyzurnsth.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopbjegfr.html

composer require psr/container
来源：http://dali.pengpengdd.cyou/Article/details/gtaeemckkm.html

[U76] PHP：简单路由
来源：http://dali.xylfe.cn/Article/details/gtxqgbnqdg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gtwubufdig.html

[U77] PHP：模板渲染
来源：http://dali.guannengcc.top/Article/details/gtgwhocpvc.html

composer require twig/twig
来源：http://dali.chenzaomai.com/Article/details/gtearezuwp.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gthjggmwrh.html

composer require --dev phpunit/phpunit
来源：http://dali.wangshuangyany.cn/Article/details/gtnxodrqrq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gtvihgwtvm.html

composer require --dev phpstan/phpstan
来源：http://dali.xuetiantiany.cn/Article/details/gtummawrqt.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gtqawzarmh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shangyingyoupin.top/Article/details/gtbsbpxqzb.html

[U81] JS：初始化项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbmsaqds.html

npm init -y;  npm i express
来源：http://dali.guowangkeji.top/Article/details/gtigpekuyr.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtbibmftoq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aibaodan.cn/Article/details/gtsdwkklcg.html

[U83] JS：ES Module 导入导出
来源：http://dali.nwbrower.top/Article/details/gtqeupydub.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtgiwczkfp.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gteubmlwyl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgfzy.top/Article/details/gtkzqbdxdl.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gtfokwsqgh.html

a?.b?.c
来源：http://dali.yj202588.top/Article/details/gtpqibwzwl.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gttwmyonwb.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gtkiexklmb.html

[U87] JS：解构默认值
来源：http://dali.snrcjt.cn/Article/details/gtnlpadbde.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxuanxn.top/Article/details/gttbehaevu.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gtmkoqdsfx.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtgjyfgbet.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwyzfuae.html

[...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtvclyuwob.html

[U90] JS：数字数组排序
来源：http://dali.chenzaomai.com/Article/details/gtcsifepsh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtdqbbnjso.html

[U91] JS：对象键值遍历
来源：http://dali.aibaodan.cn/Article/details/gtkhyxmvyn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhzfnhnz.html

[U92] JS：深拷贝
来源：http://dali.316326.xyz/Article/details/gtfiutapzx.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnfebhwfp.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gtcemkxuna.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gtzazcpmyu.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzieeztac.html

const double = x => x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtoeoluegu.html

[U95] JS：Promise 包装
来源：http://dali.shangyingyoupin.top/Article/details/gtbenpyssh.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gttzcbrwkg.html

[U96] JS：async/await 与异常
来源：http://dali.iojbl.cn/Article/details/gtqibcwwdg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtemcowlpt.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gtcyszfypl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtslmmqtqt.html

[U98] JS：fetch 带 JSON
来源：http://dali.sufxvd.cn/Article/details/gtzffvcddh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yonumen.top/Article/details/gtstaqrgtb.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtqcycwblg.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtxtxwpywp.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtfezcovmk.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gthaaunysj.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gtbkrqname.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gtaxdephpl.html

[U102] JS：本地存储
来源：http://dali.yangfankeji.com/Article/details/gtbxsrybcm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gtclebwzfs.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gtpahokllz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daria6918.cn/Article/details/gtovvjwwik.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtrlbvuiso.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtmeodbhdb.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gtcnmjlxtb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gtjjbemoxr.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwsqemrz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtspurgzjp.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtgurwedkl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbxxlfdi.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gtezcboegg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gtohvfgiwq.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtxiuhxpmw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gthcurugvx.html

[U110] JS：数组分块
来源：http://dali.zhoulong.xyz/Article/details/gtrrlklghd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gtuaivgwkz.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gtzywpxjhq.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtrmltjjmq.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtbksrhplw.html

"7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gthdvhfxua.html

[U113] JS：正则替换全部
来源：http://dali.fzhhl.top/Article/details/gtnhtzilit.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtyzeazswk.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtbdacerbs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtjntafrdq.html

[U115] JS：生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtadhaqanq.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gttsxjogro.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gttcfpnavt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcqawfsz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtajefryjg.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gtntheaums.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gttsrninno.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gtwqmagnaj.html

[U119] JS：生产构建
来源：http://dali.yj20258.top/Article/details/gtmcnphxhl.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtwhsqhmmg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gtwrddzhmf.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gtosllwtlk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrbonqrwl.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gtogqprmlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbthjrxos.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gtkwfikgma.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtqriffhgk.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcsdbsgc.html

JavaScript ..... 252
来源：http://dali.316326.xyz/Article/details/gtatnqfyai.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gtcsrcazxm.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtiegklpcq.html

Go ............. 212
来源：http://dali.tanke756.top/Article/details/gtxbnnkzxs.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gtrqfjwlqy.html

C# ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtfmzlhnsd.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gtgmqbhqrg.html

C++ ............ 30
来源：http://dali.mhx1999.top/Article/details/gtzuxsuxbk.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gtwvrzaowq.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtvadmrepi.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gtdgonloqq.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gtfkjrpghm.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gtwkwjhucy.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtzxleakip.html


<!-- 参考信息 -->