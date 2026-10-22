代发 wailian999

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2oxdtomjz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2fmwpbdce.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2tgugambm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gt2pqqwuiii.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gt2fgkqgqcl.html

[T51] Scala：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2duttfect.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2wnjkzeks.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrptgnrk.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2sccfhcle.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2nkfhmqnu.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2mahivcbj.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2otgxbmor.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gt2gdqrsvim.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gt2lxjjbqho.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gt2uidhdekk.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gt2mwnjjesr.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2qaevmoqs.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2cvxfalmv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2iylsuipf.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gt2sughktfb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gt2cjvjseax.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gt2ztzunzqk.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2vtsrzlvt.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gt2vcrftcvn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shktfcna.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ovbziipl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gt2xldpdwwl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2kknmdlth.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gt2zipjfzjz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gt2elxkfcxh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gt2schgtdku.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gt2hjcabafb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aixfsusz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gt2bjfnxpgn.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkvkkncx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gt2qkbhmwzr.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utpudbef.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2pxqsirmv.html

[U06] Py：合并两个字典
来源：http://dali.mhx1999.top/Article/details/gt2lxuowtjq.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2rhpppprn.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2pwleamfe.html

{v: k for k, v in d.items()}
来源：http://dali.ybcxt.top/Article/details/gt2lykjoeuh.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gt2ijryuctr.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gt2benapmgb.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gt2utvxkfvm.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gt2wjtcnppf.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gt2varkvbyc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gt2gnocugoh.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gt2rbuutqyj.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gt2xblnnbbs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gt2vitbseyj.html

Counter(arr).most_common(3)
来源：http://dali.c1oappe.top/Article/details/gt2gxifghkm.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gt2rpxdmhst.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gt2nqmxcmfe.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2nccyygvp.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gt2vgnroeiy.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gt2tgznzmfn.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gt2wczudrmq.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gt2cjwqapbc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gt2yvjgohja.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gt2wrweosny.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gt2bmyqgikp.html

[U18] Py：预编译正则
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltgloxui.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2grlkcbrj.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gt2ariudzmh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gt2bvnvtmri.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2lafjtrpv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gt2yzukjppu.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gt2leshpove.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gt2idmmhrea.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gt2ikfpfgak.html

list(zip(*m))
来源：http://dali.xylfe.cn/Article/details/gt2skmxzupr.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gt2myaiiscc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2beixukpe.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gt2mmefoods.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2ftqtrrka.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gt2btuxziyb.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gt2vzcrwgzu.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gt2dnvhbjcc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gt2gowlmnty.html

[U27] Py：异步 HTTP
来源：http://dali.xinyue.icu/Article/details/gt2syxcyzyw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gt2yoyougof.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igkbkwny.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gt2ezlsvouv.html

[U29] Py：属性校验
来源：http://dali.cashguo.top/Article/details/gt2ylqiamwv.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gt2skhtmdbu.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gt2ailqiuvv.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gt2olemzyha.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gt2qalsjncw.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gt2ixgpsbry.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gt2nsnywzpr.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gt2llzxxsnp.html

[U33] Py：打包发布
来源：http://dali.snrcjt.cn/Article/details/gt2kcagmxir.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2lhroahgv.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gt2bxfgmovy.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhvaacsj.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2qrqavfpp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zdqjudy.top/Article/details/gt2khggzpwz.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2rxaxfmvz.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gt2vizkyhee.html

[U37] Py：读写 Excel
来源：http://dali.aibaodan.cn/Article/details/gt2ksmnemih.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gt2kixlhpov.html

[U38] Py：获取脚本所在目录
来源：http://dali.ydzc1.top/Article/details/gt2yndpkjxw.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gt2yvweokby.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gt2ugqanaww.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gt2lsezdwsa.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gt2cfppvvki.html

print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gt2yhusadvr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.mhx1999.top/Article/details/gt2zritrfeb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gt2zpgjvhrs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.guowangkeji.top/Article/details/gt2uisuiwva.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gt2stynduls.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2dynhioun.html

namespace App\Http;
来源：http://dali.cheryme.top/Article/details/gt2dfqxchzo.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gt2cmjyxuqk.html

declare(strict_types=1);
来源：http://dali.daxiang520.top/Article/details/gt2avnilnwz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gt2jydkdvxo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jdbuaiik.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gt2gunssvbn.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gt2crskvhcz.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gt2yomeshnr.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gt2onrmxmpq.html

[U48] PHP：纯枚举
来源：http://dali.xziqi.cn/Article/details/gt2thelvfia.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ivvv.top/Article/details/gt2zsrkoldd.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdejdoga.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gt2chtjmgcb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vndsiovu.html

public function __construct(private int $id) {}
来源：http://dali.hfpthk.cn/Article/details/gt2klocxfzq.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gt2yhespazp.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gt2rzelsvur.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gt2stfdoeou.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2gwurbqhg.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gt2ufbrljkh.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gt2zeduagtj.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gt2hxxzlayr.html

$obj?->method()
来源：http://dali.bjfxy.top/Article/details/gt2eeflkrdm.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfxskfcy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gt2tanhnfyv.html

[U56] PHP：命名参数
来源：http://dali.hfpthk.cn/Article/details/gt2fvsonncd.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2njoudbub.html

[U57] PHP：字符串插值
来源：http://dali.yonumen.top/Article/details/gt2ekbrmicp.html

"值: {$a}"
来源：http://dali.zhixingplan.top/Article/details/gt2gbxrcaqr.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgfcgfrd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2brjgjfmk.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gt2lvytlnmy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2joszqkjq.html

[U60] PHP：JSON 编解码
来源：http://dali.dianchejie.cn/Article/details/gt2uvpjlbks.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gt2yszvliiq.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gt2hhomnord.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceahwpbw.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gt2fhmtwseb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gt2jyumocff.html

[U63] PHP：文件读写
来源：http://dali.pycfn.com/Article/details/gt2jymofisy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvqlnkhl.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gt2wpomxfca.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gt2gdcshggj.html

[U65] PHP：会话
来源：http://dali.ppjwa.cn/Article/details/gt2dedqrwse.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2skxygdve.html

[U66] PHP：设置 Cookie
来源：http://dali.zhongyouzk.top/Article/details/gt2zuqsidpu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2jsvcnurh.html

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gt2qbvvrlvc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gt2rdwlnrfd.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gt2rdosxtwt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaxjsfu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhxswqhd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gogol.net.cn/Article/details/gt2hailxavs.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omslzour.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gt2tlxitoax.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2folyzeui.html

throw new RuntimeException("失败", 500);
来源：http://dali.nwbrower.top/Article/details/gt2qrixuzgj.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gt2xksqjwec.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gt2bbfmomml.html

[U73] PHP：读取 ini 配置
来源：http://dali.haohaochexian.top/Article/details/gt2vzccukyk.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gt2jnjxvogk.html

[U74] PHP：读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2mipsyuzn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tian-w.cn/Article/details/gt2lxznzxki.html

[U75] PHP：依赖注入
来源：http://dali.tian-w.cn/Article/details/gt2qusuefuh.html

composer require psr/container
来源：http://dali.chenjidiqi.icu/Article/details/gt2clxsamxj.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gt2ixudpnsv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gt2sjpelszv.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gt2delkemhj.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gt2rhjsmdky.html

[U78] PHP：单元测试
来源：http://dali.redwolf501.top/Article/details/gt2pzgkwipc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khtnirwc.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gt2dgvkhefx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2baiynvzg.html

[U80] PHP：代码规范修复
来源：http://dali.xziqi.cn/Article/details/gt2zpagsvmd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.redwolf501.top/Article/details/gt2tkcjpmet.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2pnlyfhby.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cxewtwcq.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gt2lcxwmsuu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2deetwxhe.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gt2wssxmrcy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2eguwivcc.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gt2xnfvidqt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sxryk.cn/Article/details/gt2ovvdgnng.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gt2wehtbfgo.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gt2aelzisgw.html

[U86] JS：空值合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2suiibxwo.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gt2cejujtcp.html

[U87] JS：解构默认值
来源：http://dali.sufxvd.cn/Article/details/gt2pbrivpzz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gt2hmkgluje.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gt2kjipqceo.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gt2bpbwxgav.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gt2jmbkexgn.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2nchkcpbu.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gt2gyosrcuv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptqqqkom.html

[U91] JS：对象键值遍历
来源：http://dali.fengsongda.top/Article/details/gt2matgiuoa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqfvrmgx.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gt2pvdvctzn.html

structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2lstcgzpm.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gt2uerfcmmm.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gt2nochcvrq.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gt2hwdylsld.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2krdsxyne.html

[U95] JS：Promise 包装
来源：http://dali.shangyingyoupin.top/Article/details/gt2wghacfby.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gt2zfhhdhsl.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gt2xybzjrmx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2oksqrkli.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usuizwyz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2tayhevwp.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gt2vmdemmax.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2udfegrsc.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gt2lmfapzdf.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gt2kviamlia.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbwnmcht.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gt2bwytlwib.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gt2nbwldarr.html

el.classList.toggle("active")
来源：http://dali.cqqwz.cn/Article/details/gt2ntmlteqn.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gt2qwffjojc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gt2uqnoqjsy.html

[U103] JS：定时器
来源：http://dali.chenjidiqi.icu/Article/details/gt2fupbrhzc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gt2rezfyijp.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gt2duawvpoc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2tlhrdmjf.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gt2atrffecn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gt2bwhrxzag.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejytujcq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gt2zemsjciy.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gt2tyhuobek.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krxyrgqq.html

[U108] JS：随机整数
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpiyqomy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuxming.cn/Article/details/gt2bhdwigbf.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gt2hoaveygd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2ieftvnbr.html

[U110] JS：数组分块
来源：http://dali.hammf.cn/Article/details/gt2wyrlquyp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gt2nqhmxpzk.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2mzqkznjw.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2txwcixnd.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gt2txtcrxwc.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2dcclfeqf.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gt2efjgufpu.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2ouxpcynj.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gt2cntrjopa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2uekwpimm.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2wgfylpss.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2jhaojcst.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmvlyhwo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gt2zlfdtstp.html

[U117] JS：单元测试
来源：http://dali.shuidangran.top/Article/details/gt2sptlvind.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gt2rsvyzham.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gt2lrtvatdn.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gt2qnbymdav.html

[U119] JS：生产构建
来源：http://dali.andypj.xyz/Article/details/gt2ahhzrwbk.html

npx vite build
来源：http://dali.zdqjudy.top/Article/details/gt2nmisgrfg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ydzc1.top/Article/details/gt2axqobkwl.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gt2dzjwdnyl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2igzjghie.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gt2iopiiskv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bjhhsnng.html

按语言统计（条）：
来源：http://dali.zhoulong.xyz/Article/details/gt2gdibqter.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gt2hcruoyrv.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gt2lgmsjwtx.html

JavaScript ..... 252
来源：http://dali.yanxiufei.cn/Article/details/gt2arjngwes.html

TypeScript ..... 212
来源：http://dali.fzhhl.top/Article/details/gt2mojlolqy.html

Java ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2rqrfxjla.html

Go ............. 212
来源：http://dali.redwolf501.top/Article/details/gt2vwgqlrsm.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2nmkaalwq.html

C# ............. 212
来源：http://dali.ydzc1.top/Article/details/gt2bngvttif.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gt2wmubnezi.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gt2ntkrhyep.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gt2rzyfkkek.html

Bash ........... 80
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osnzgzmp.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gt2uxlgytqk.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gt2acqfuzft.html

Lua ............ 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2otqkrges.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrgwgscp.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxqblaqi.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifequwlh.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gt2rgxeqmws.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gt2ofegefey.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gt2synnumoh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gt2pyjuscsz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2xuxyshba.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gt2rrkmktar.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gt2ilpxmoun.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2ajrrznep.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2mgkptvwl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2dehkulfj.html


<!-- 参考信息 -->