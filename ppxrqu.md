代发 wailian999

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gt2lmqdqhms.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2xremfamm.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2lbawpalk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gt2mtgmerwr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gt2upfdnteb.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2ctxmrijb.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2fagleqlg.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gt2fixzyjfk.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gt2lepaqhqj.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrlcfybj.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2gstjbvxe.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2httpnejl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gt2qdkqiteq.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2ncqupexa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gt2mrxcshej.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gt2scfrrwmv.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gt2uzgoznxo.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfibrndw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gt2xywmlqju.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2jziwvqkm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2okiwuiey.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gt2ivdttpsk.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gt2nhuneikn.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gt2jknidwdp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gt2wfnnehwz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmorcymj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2itngcjkb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2uwyuefvq.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gt2prhzlfbz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gt2vnfbnjet.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gt2dmhjqmlm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gt2lzmsajad.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gt2jckbixrg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fengsongda.top/Article/details/gt2fzncmftu.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gt2utzynqyy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gt2echoknis.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gt2lknesjyi.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2ffbvqmkf.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlyetpwk.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gt2fmunxjfg.html

[U07] Py：反转字典键值
来源：http://dali.hywenlv.cn/Article/details/gt2gbzralnx.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gt2sxppzkjp.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gt2ibquizzo.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gt2mwxiadzl.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gt2rqtvcnea.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gt2dswpubsx.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gt2rmmubrdl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gt2rzpgwrdn.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gt2sanljual.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gt2lbdmmezu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gt2gvtjcwlu.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gt2rwcdxjyp.html

[U13] Py：固定长度队列
来源：http://dali.daxiang520.top/Article/details/gt2ssvctcwb.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gt2ovuzmzzm.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gt2zyoyxlem.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gt2phpefnnr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iospyfcx.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2hiffnfmb.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gt2ituflink.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gt2hcqnliwz.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gt2fsilhvbp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfyshaxp.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gt2ukrzvpzz.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2skkpweeh.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gt2hqvmuqwe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gt2revgxzqv.html

[U20] Py：缓存函数结果
来源：http://dali.aizwys.cn/Article/details/gt2etwjmvex.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gt2ompifrep.html

[U21] Py：自定义上下文管理器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkvojdda.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gt2jbqcpxbj.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gt2zxanpblm.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gt2mipzhwpe.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gt2fjzbfpjw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gt2dyvrghfg.html

[U24] Py：路径操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2puaaxdgc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2arjrhscx.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plvpikxt.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gt2pjftwmvk.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gt2nmtdgxhg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gt2btvvuehw.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gt2povneakt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gt2rifsrvnv.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gt2wjqixetz.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2acrsezfj.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gt2vazqavji.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gt2tlxqmgqo.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gt2bplavkrs.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gt2vzldpifi.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gt2gbjeqypr.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gt2nxkvqiah.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gt2kotrtnos.html

ruff format . && ruff check --fix .
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtxfhzyc.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gt2tniwezbo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhengqikj.top/Article/details/gt2nbfruuaq.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gt2vqxhdird.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gt2aqzhoacd.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gt2zwzfyhjl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxinkj.top/Article/details/gt2fzrrntlm.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gt2jubmxxjl.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gt2ravcfduv.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gt2tdwpwnir.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gt2oypzlnjp.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gt2ucdkduci.html

Path(__file__).resolve().parent
来源：http://dali.yangfankeji.com/Article/details/gt2cqqbgfhq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gt2huwurasr.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gt2nvtlkdhs.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gt2fsfaniie.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2yxjfybru.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gt2ibzesygm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gt2xrjiwxsr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hongshengwenyu.top/Article/details/gt2mojhudml.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gt2fwgsbevf.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gt2pwugwrze.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2madqydhi.html

[U44] PHP：开启严格类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykhwqspb.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gt2ngvptevs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gt2qphkcord.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2twegklra.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gt2gttkziqf.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gt2gsefqewe.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gt2svlhfadn.html

int|string $id
来源：http://dali.ivvv.top/Article/details/gt2kppysrct.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gt2aotnhcju.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gt2xwjcxzik.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zymuoxyf.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gt2jjmbcust.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2raquqmmv.html

public function __construct(private int $id) {}
来源：http://dali.sweek.top/Article/details/gt2gwcblbkh.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gt2ctatyeqj.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gt2whwmvioo.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reuvilbl.html

$double = fn($x) => $x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gt2sgowksup.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gt2vgywnbya.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gt2wbmjjoxn.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfhkdada.html

$obj?->method()
来源：http://dali.ybcxt.top/Article/details/gt2coajkzcx.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2eepqfred.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gt2iyxlofyk.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gt2frorczcr.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2shsnccoh.html

[U57] PHP：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2rpefobnx.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdddlymc.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gt2vbhxrolg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2kpcfyhym.html

[U59] PHP：自定义排序
来源：http://dali.guannengcc.top/Article/details/gt2jgnphvjv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ryphxrkw.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gt2kikkwsur.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2zeqvtoch.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gt2plisazig.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2mphphooq.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gt2borutbms.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcyfvewo.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gt2vnuckdbe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gt2oocsnmta.html

[U64] PHP：目录遍历
来源：http://dali.hammf.cn/Article/details/gt2jfoevpvp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yanxiufei.cn/Article/details/gt2hexidqyk.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gt2lcmghgaf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2kblzkqyw.html

[U66] PHP：设置 Cookie
来源：http://dali.yangfankeji.com/Article/details/gt2vwbhbqve.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldvqzqoc.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gt2vfcqzlpk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.9152youxi.cn/Article/details/gt2ljqztlth.html

[U68] PHP：PDO 连接
来源：http://dali.ppjwa.cn/Article/details/gt2osisfpnz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gt2yhpydqeb.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gt2mgjwttpd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gt2zruhekbx.html

[U70] PHP：PDO 事务
来源：http://dali.hysaishi.cn/Article/details/gt2gmrfcike.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgfzy.top/Article/details/gt2hqjvficp.html

[U71] PHP：抛出异常
来源：http://dali.xziqi.cn/Article/details/gt2bwdyvwey.html

throw new RuntimeException("失败", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdwcvlnl.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsjedfyp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gt2kfggjgjp.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gt2lgojshau.html

parse_ini_file("config.ini", true)
来源：http://dali.yuanzhike.top/Article/details/gt2eyzsymem.html

[U74] PHP：读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2xjjhaobc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gt2uxxsvhog.html

[U75] PHP：依赖注入
来源：http://dali.cdnleiting.top/Article/details/gt2bfcqdkzh.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gt2wqbfyqtu.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gt2hagubbpq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fzhhl.top/Article/details/gt2xblhafqc.html

[U77] PHP：模板渲染
来源：http://dali.yonumen.top/Article/details/gt2gaohgwvi.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gt2oizilqrm.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2fcbrklzn.html

composer require --dev phpunit/phpunit
来源：http://dali.smart0.xyz/Article/details/gt2ulhscnmd.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gt2bkihknkw.html

composer require --dev phpstan/phpstan
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huttzumv.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gt2fqktqdcn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yvedp.cn/Article/details/gt2aogokbet.html

[U81] JS：初始化项目
来源：http://dali.zhongyouzk.top/Article/details/gt2wgdrcpog.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gt2whenqydb.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gt2byxouxww.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tianlin.xyz/Article/details/gt2hsbhjpek.html

[U83] JS：ES Module 导入导出
来源：http://dali.jlsjyb.cn/Article/details/gt2gpwztgfo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hammf.cn/Article/details/gt2zbmoxdal.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gt2skxioimv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gt2dhzqygtc.html

[U85] JS：可选链
来源：http://dali.jlsjyb.cn/Article/details/gt2azptyfga.html

a?.b?.c
来源：http://dali.nanxuanxn.top/Article/details/gt2afqjrhdp.html

[U86] JS：空值合并
来源：http://dali.jinqigufen.top/Article/details/gt2nizeaclh.html

a ?? b
来源：http://dali.daxiang520.top/Article/details/gt2mxeafgjb.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gt2vjnkdllz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zdqjudy.top/Article/details/gt2eesdbwzf.html

[U88] JS：对象展开合并
来源：http://dali.haohaochexian.top/Article/details/gt2qrxgzzfb.html

{ ...a, ...b }
来源：http://dali.gaohongyu789.top/Article/details/gt2ahiuvnsh.html

[U89] JS：数组去重
来源：http://dali.yuxming.cn/Article/details/gt2vgmixxbz.html

[...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2toyrfhtz.html

[U90] JS：数字数组排序
来源：http://dali.chenlongwang.top/Article/details/gt2pkzzjnkl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2kctjkekz.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gt2nttartbm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gt2fxnxjxao.html

[U92] JS：深拷贝
来源：http://dali.yongpay.top/Article/details/gt2uwdhcydc.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2olbibmfo.html

[U93] JS：模板字符串
来源：http://dali.yj202588.top/Article/details/gt2ieysmhra.html

`共 ${n} 条`
来源：http://dali.daria6918.cn/Article/details/gt2fmrogoqp.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2oiobcric.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gt2vwamwqme.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glmmefbw.html

new Promise((resolve, reject) => {})
来源：http://dali.birdmap.top/Article/details/gt2ggxakajo.html

[U96] JS：async/await 与异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2kigjdgmo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2kjtyomtl.html

[U97] JS：并发请求
来源：http://dali.yuxming.cn/Article/details/gt2scpxuqgx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2mlarvsll.html

[U98] JS：fetch 带 JSON
来源：http://dali.sxryk.cn/Article/details/gt2rfxnadna.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gt2zuqxwpbr.html

[U99] JS：事件监听
来源：http://dali.yuanzhike.top/Article/details/gt2idijqfgg.html

el.addEventListener("click", e => {})
来源：http://dali.ybcxt.top/Article/details/gt2iofsopkp.html

[U100] JS：DOM 查询
来源：http://dali.dashuyun.cn/Article/details/gt2qocbvuex.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idsvqlwk.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gt2mburxjob.html

el.classList.toggle("active")
来源：http://dali.hfpthk.cn/Article/details/gt2hiqnpxkc.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwjvhwzc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxuanxn.top/Article/details/gt2pxzzhipn.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gt2rkaqskrh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gt2ublfkopi.html

[U104] JS：防抖
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymlqjlmq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npsmxdfp.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gt2segmglcq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gt2bspwgwpu.html

[U106] JS：日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2pindmeks.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gt2tpgnilkf.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysxkuuwh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcvjlzup.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gt2vxpimogk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gt2ryuvudrn.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gt2vuwyjezm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2nvyvxybx.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gt2vbfwmyih.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gt2pkzuzvgx.html

[U111] JS：对象转 Map
来源：http://dali.tian-w.cn/Article/details/gt2awrxobck.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gt2rlibqjhw.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gt2yxicijqw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwrftso.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gt2vypzmeja.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2miaxfgfg.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gt2ebnyoeip.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gt2fwbfahcc.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2vpxckjky.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2ishmsxjg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.iojbl.cn/Article/details/gt2sgcgqgba.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2bgsbgvnc.html

[U117] JS：单元测试
来源：http://dali.xziqi.cn/Article/details/gt2ahdgofxl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gt2ioyhnhol.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gt2bthifmfa.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvfinjry.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gt2lilocxdo.html

npx vite build
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blvnsgxv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gt2bxuyadvl.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gt2fswayeak.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2kbsdpwsq.html

统计汇总
来源：http://dali.yj202588.top/Article/details/gt2tptkvbos.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2wztrzdsw.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gt2eirgmavv.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gt2elypqwhz.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhcdikld.html

JavaScript ..... 252
来源：http://dali.yanxiufei.cn/Article/details/gt2swxuimhh.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gt2eyuytnoa.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2ezugydcz.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gt2twapebjl.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2zuvdgmjf.html

C# ............. 212
来源：http://dali.sweek.top/Article/details/gt2jsqbryoy.html

C .............. 30
来源：http://dali.sxryk.cn/Article/details/gt2vufccseb.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gt2odyvtmfq.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gt2wgomoxoe.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajabnnms.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpmyzhrr.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2aqappfql.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gt2jdfcbtoh.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gt2xmvtcmbi.html

Scala .......... 10
来源：http://dali.smart0.xyz/Article/details/gt2rkqsqvcb.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apoywjuv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzbiakd.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gt2ycjikcsu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gt2ssglzlsr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gt2dosxapix.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2qazsidge.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gt2ashbejsq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gt2hgjapkpr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tenkdqgc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2ilvjlltf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2xmwaksre.html


<!-- 参考信息 -->