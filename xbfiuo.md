代发 wailian999

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gt2dyzipatg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2hqykkmcp.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2jxpjbews.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gt2rihiawqt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gt2qeajsjgo.html

[T51] Scala：Hello World
来源：http://dali.tanke756.top/Article/details/gt2zhbgkwkv.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2jssqgoqa.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gt2ebwjhemr.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gt2bnwbrbfs.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2ofhonrfn.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gt2mzzordyj.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2aebrylcw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gt2onirzenu.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2dzfpqsfr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gt2lvuvhuou.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gt2lrghvokr.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2pnvhbozh.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2mbmmgone.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gt2eepcefcv.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2urqwkiss.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gt2buetmigc.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2xdokmvei.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2ybwitujt.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gt2mutqfkls.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vemgersu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dezayetf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gt2xydyzqld.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vuyabqho.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gt2ielodlay.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gt2bumayeof.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gt2hvatliay.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gt2yiolgvej.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gt2vuykotlr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gt2syudfkxb.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gt2ftknohxc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gt2ltcvlpva.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gt2johjcdgm.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2dagkbisa.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqxfdvbk.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gt2xplupnsz.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gt2qkirywmv.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gt2lfusxqna.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gt2xhdwajja.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gt2uihzkdsp.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gt2ccuyohbl.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gt2rrtraegh.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gt2sqlazoxy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hevxotur.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gt2rklwkpyw.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gt2wpbyfypi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tanke756.top/Article/details/gt2frqxsrci.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2avmvujfi.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gt2sylgjkql.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gt2hwaueiku.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gt2ovfgagtl.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2ebjukmoo.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gt2ylrictye.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqhzjihj.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gt2sjmrhzvt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gt2mmxcjpxt.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gt2acuyldwr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fukfspco.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbldvqim.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uezvxvpr.html

[U19] Py：正则替换带回调
来源：http://dali.wangdashe.top/Article/details/gt2hftopacc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gt2hoqyzeyf.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gt2bdgdygtv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypshpftc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gt2ueubhsgo.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gt2wprkwprs.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gt2uovcynlo.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gt2njfkspfa.html

[U23] Py：分块读取大文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikyojhoe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gt2gxgfivdb.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gt2woltymop.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2msschcnd.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgufenzy.top/Article/details/gt2awjauonw.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gt2eqlecjiu.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gt2cjraivpx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.kuanghao11.cn/Article/details/gt2xzytmkiw.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gt2xgljetbg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gt2lwgyrlbj.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gt2lnzlppej.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gt2sksyhgcf.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gt2lbnukapw.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gt2mvdrtopn.html

[U30] Py：数据类
来源：http://dali.jinqigufen.top/Article/details/gt2fjfxofow.html

@dataclass(slots=True)
来源：http://dali.gotoacloud.top/Article/details/gt2iveekkqt.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gt2hqsawqke.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqdfmona.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrfgqzbw.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gt2ydvwgyyw.html

[U33] Py：打包发布
来源：http://dali.daxiang520.top/Article/details/gt2mnrtteuc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gt2geithqgz.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gt2yifrrrtb.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gt2fvmsuyis.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gt2bqfcyogq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gt2spwjyobc.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2uakceoyo.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gt2eqdgocfa.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gt2dciuwvsk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgmxdwee.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edrfwwmk.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujzcxxih.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gt2kdzulotq.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gt2wdqadkcu.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gt2lvulzuon.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fayfmwzi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gt2xjtmpmtu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gt2yocqjzzr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuuloqxc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gt2pvxvolny.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2scfzlcyo.html

namespace App\Http;
来源：http://dali.redwolf501.top/Article/details/gt2oigbkloi.html

[U44] PHP：开启严格类型
来源：http://dali.0kj1m.cn/Article/details/gt2dvteluue.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gt2rhmyyqar.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gt2okexawdi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2cxusqbcg.html

[U46] PHP：可空类型
来源：http://dali.iojbl.cn/Article/details/gt2jjyctbvl.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gt2gighosfq.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gt2rakvelis.html

int|string $id
来源：http://dali.birdmap.top/Article/details/gt2qywkbboe.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gt2iswfujda.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qjpdglap.html

[U49] PHP：只读属性
来源：http://dali.jqgfzy.top/Article/details/gt2jgqyokcd.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gt2jnuoqhgm.html

[U50] PHP：构造器属性提升
来源：http://dali.ppjwa.cn/Article/details/gt2svzhasmn.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gt2kawyeyuy.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gt2xnwbhoiy.html

[$a, $b] = $arr;
来源：http://dali.yangfankeji.com/Article/details/gt2lqxsjgns.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gt2uvevcfdw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeahxlj.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gt2dcejmjie.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gt2unysrgwt.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gt2acvgnjbb.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gt2sqoqcpmu.html

[U55] PHP：match 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qikvxcpt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2hazkwotj.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gt2bfonrrss.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2okleayzo.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2jbdoxnwh.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gt2lqetgbzn.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibqfanit.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gt2efnljhzz.html

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gt2itmkrbin.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2dltrncjl.html

[U60] PHP：JSON 编解码
来源：http://dali.gaohongyu789.top/Article/details/gt2qzgjlthm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2pgzxrlle.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gt2ywdrbrzq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2nmtynsnk.html

[U62] PHP：日期对象
来源：http://dali.hnqzz.top/Article/details/gt2cvzvsmpe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigfzy.top/Article/details/gt2zglejhwu.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gt2pjyfowsq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenzaomai.com/Article/details/gt2eicpdnnz.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gt2oerxzcyx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gt2yhnvufne.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gt2skodltno.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2xtilrnay.html

[U66] PHP：设置 Cookie
来源：http://dali.gogol.net.cn/Article/details/gt2gxmjnyjo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tianlin.xyz/Article/details/gt2bxowintc.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gt2uaoegyjf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.316326.xyz/Article/details/gt2yhamzvax.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gt2qwgfexir.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gt2oglitiqd.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gt2ktuqhjkz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gt2omapvliv.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szcamafl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gt2jfnxpdak.html

[U71] PHP：抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2iitdfobo.html

throw new RuntimeException("失败", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2azwqjboa.html

[U72] PHP：写错误日志
来源：http://dali.hysaishi.cn/Article/details/gt2littiuyh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gt2cbnjzpgr.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gt2mumrsujm.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gt2wskiyikt.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2znjvcude.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gt2tkpqxtrq.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gt2yzvanmai.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tahhfzio.html

[U76] PHP：简单路由
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbzgvjff.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjntkxpw.html

[U77] PHP：模板渲染
来源：http://dali.zhengqikj.top/Article/details/gt2bxgtpjee.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gt2rrmnwcyu.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pioczxod.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gt2olrjeyhw.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gt2xcwwsnla.html

composer require --dev phpstan/phpstan
来源：http://dali.ehwqpu.com/Article/details/gt2zkvfcddx.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gt2pmqjbosc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jiagoushi.top/Article/details/gt2vdhrkeez.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2arhhpuez.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gt2mwzdequh.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gemwvepx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gt2crnxbuix.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gt2ejaprjjy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gt2edpzidsz.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gt2ivqnlsin.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gt2jztwrtgr.html

[U85] JS：可选链
来源：http://dali.kuanghao11.cn/Article/details/gt2tcmkbrrg.html

a?.b?.c
来源：http://dali.kuanghao11.cn/Article/details/gt2pawkbmlb.html

[U86] JS：空值合并
来源：http://dali.mhx1999.top/Article/details/gt2knhmrewg.html

a ?? b
来源：http://dali.fengsongda.top/Article/details/gt2vuubobox.html

[U87] JS：解构默认值
来源：http://dali.sufxvd.cn/Article/details/gt2fnhbqpwz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuxming.cn/Article/details/gt2mibhdnko.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gt2xsjzeazp.html

{ ...a, ...b }
来源：http://dali.guowangkeji.top/Article/details/gt2zuoagnzu.html

[U89] JS：数组去重
来源：http://dali.tianlin.xyz/Article/details/gt2cbtzjsep.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2hypqjbzs.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gt2apjaqosp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gt2robalofa.html

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcnhkjzq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjhnfzpc.html

[U92] JS：深拷贝
来源：http://dali.sweek.top/Article/details/gt2tlsvvmun.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2rxygrica.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gt2rzrmwinx.html

`共 ${n} 条`
来源：http://dali.smart0.xyz/Article/details/gt2vareigim.html

[U94] JS：箭头函数
来源：http://dali.tanke756.top/Article/details/gt2fcmtyqui.html

const double = x => x * 2;
来源：http://dali.meibo888.top/Article/details/gt2eriivenc.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gt2pgeaelbo.html

new Promise((resolve, reject) => {})
来源：http://dali.ybcxt.top/Article/details/gt2wwkuddfb.html

[U96] JS：async/await 与异常
来源：http://dali.sufxvd.cn/Article/details/gt2nislvuei.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2fsfphegj.html

[U97] JS：并发请求
来源：http://dali.wangdashe.top/Article/details/gt2hsvcacsn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2vmzhhwbc.html

[U98] JS：fetch 带 JSON
来源：http://dali.xinyue.icu/Article/details/gt2iulurvfg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plehxnaf.html

[U99] JS：事件监听
来源：http://dali.jinqigfzy.top/Article/details/gt2kmbyfxqt.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gt2apggbypl.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gt2tqfwftum.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gt2hghgybuk.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuuktxlu.html

el.classList.toggle("active")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymiexzgf.html

[U102] JS：本地存储
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdnltaza.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gt2dnfpqbgf.html

[U103] JS：定时器
来源：http://dali.dianchejie.cn/Article/details/gt2mzbfiwkq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxuanxn.top/Article/details/gt2thboaibk.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gt2ugizowlm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2mqazyudl.html

[U105] JS：节流
来源：http://dali.sxryk.cn/Article/details/gt2svromxfy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2sooewgvk.html

[U106] JS：日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmennrpc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tian-w.cn/Article/details/gt2kajrwinr.html

[U107] JS：数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2dquueiwc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gt2ibtdkumi.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gt2psdwnkyl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuanzhike.top/Article/details/gt2beyqcenf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2besumumw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2xegyqsso.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gt2pixuxmak.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gt2crrnnaeh.html

[U111] JS：对象转 Map
来源：http://dali.chenlongwang.top/Article/details/gt2hjrqrqcx.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gt2tctyjcjz.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gt2hjmpjgxm.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2ddzgrdrm.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gt2bstwmoqe.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2hcaoylfc.html

[U114] JS：JSON 深比较
来源：http://dali.birdmap.top/Article/details/gt2uoussptp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2brdgcayl.html

[U115] JS：生成 UUID
来源：http://dali.yuxming.cn/Article/details/gt2qeouurrx.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2akkragql.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjbjcjpn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sysykeji.top/Article/details/gt2knaepsrd.html

[U117] JS：单元测试
来源：http://dali.yueranfly.top/Article/details/gt2rbglyyhr.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gt2bjhczndt.html

[U118] JS：开发服务器
来源：http://dali.nwbrower.top/Article/details/gt2wasdgtzw.html

npm i -D vite;  npx vite
来源：http://dali.fengsongda.top/Article/details/gt2jldunkos.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gt2zbboyflq.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gt2wzvtumwm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jyoumei.cn/Article/details/gt2emiavffy.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gt2quwfhzxg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zqtfnrez.html

统计汇总
来源：http://dali.hysaishi.cn/Article/details/gt2rrywgnbk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2msvbqtiy.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2jnjqafql.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2kfzvumvb.html

PHP ............ 252
来源：http://dali.yonumen.top/Article/details/gt2clbkcatn.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gt2sawdcixo.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gt2uyllmhfo.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2cmmootew.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gt2sylvvjgj.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2dmfpaopw.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gt2wpaeewbv.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gt2scsjlifx.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gt2qgjuzkzy.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gt2pbyyrqec.html

Bash ........... 80
来源：http://dali.snrcjt.cn/Article/details/gt2mrcjtpve.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gt2fezuwtoh.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gt2hukdyezf.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gt2jdpympao.html

Perl ........... 10
来源：http://dali.cashguo.top/Article/details/gt2ihrcmnpc.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gt2ejnvbhgv.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2owofvrpx.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gt2hrdlfomy.html

按章节统计：
来源：http://dali.zhixingplan.top/Article/details/gt2vmbggunz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gt2bqxshcnx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2ndiwtyux.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztqwkuab.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gt2sfdilzsg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhoulong.xyz/Article/details/gt2hnoxkpml.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2jqmzuuwz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gt2eklolwjl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gt2iioxykds.html


<!-- 参考信息 -->