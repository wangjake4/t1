代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtcmjeqbpi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gtiyxknwas.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtnduucjqp.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtzoztewlh.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gtrdgiptrb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlifchnvi.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtrxzvpoui.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtjbcavotk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtfigejaxk.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtowckdmkg.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtveifahso.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gttrmwrqpm.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gthookikoq.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtcmsuxlzz.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtnlwrmixe.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gtgolhfntq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtmvjdqikl.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gthrynzemu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtbviicjrj.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtdofpudkz.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtniiviyjn.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtcybzrwtr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfbeppvv.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtkhztmaov.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gtapvdfnhi.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwirredjn.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtrugoooby.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gtzauqybzu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtlvwggygl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyiceswsx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtuhyyrjji.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuczdbhri.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtmuabzqlz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtnnndtlts.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sxryk.cn/Article/details/gtkkiycpmp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gtzcnzgzal.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtyrxpauoi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtdwpvmmpd.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gtfmmsgfik.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gtucffzfqt.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtbrvhxxqj.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtqxnomzop.html

[U06] Py：合并两个字典
来源：http://dali.daria6918.cn/Article/details/gtllghvisj.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gtxobokbjv.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gturgefwjz.html

{v: k for k, v in d.items()}
来源：http://dali.smart0.xyz/Article/details/gtwrkzieoy.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtkjyxpmdw.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gtgmlcsett.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gtueiorcuu.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtmhjgpzie.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gtwkmuugbz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtxwlojfbt.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtnxmnkgxl.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtutuetjxl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gtgkhgifio.html

Counter(arr).most_common(3)
来源：http://dali.yongpay.top/Article/details/gttttlurxr.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gttqsyxkwr.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gtsebrpkqg.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtdaljaygk.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxngiirn.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gtuufzipkh.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gtshxxsgtb.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gtwmanssvu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gtthaggxcm.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gtumazbffo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gtivcfibmz.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gtoclyfvsw.html

pat = re.compile(r"\d+")
来源：http://dali.cashguo.top/Article/details/gtkxusvlob.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtjhdwqzhh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gthhpmpaau.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gtyofjdiqb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtvpwascqs.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtcqiflcis.html

@contextlib.contextmanager
来源：http://dali.birdmap.top/Article/details/gtaarkrxqw.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtdmekhqay.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gtevhjeedz.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtpwhbfxqu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtdaivynsb.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gttxwyjmfe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtdflkvwnn.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtumzskuyq.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gtrsxxewtn.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtxeeskeaz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtmikhyktw.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtiohsguxs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtijvmlvou.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gtretbcfof.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gtrezxdkxo.html

[U29] Py：属性校验
来源：http://dali.sufxvd.cn/Article/details/gtrduizpqn.html

@property 与 @x.setter 配合
来源：http://dali.xinyue.icu/Article/details/gtjedywrda.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gtclkhikqj.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gtyisqsvmy.html

[U31] Py：单测
来源：http://dali.ydzc1.top/Article/details/gtsbqwspud.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gtbjxabble.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtddvrtpnl.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gtkhiulgvq.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gtdfosxzif.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gthdjlxcfd.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlyfphzd.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gtvhwbtyng.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gtitqyollf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtmlvzisiz.html

[U36] Py：定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtioaotysn.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtodyvuphg.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtgvhqsxzx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gtsjkdteci.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gtcbhicoep.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gtlskyiuhx.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gtsxgqtrch.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtafjqhbri.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtxqahaoyw.html

print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtoehqjyne.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yangfankeji.com/Article/details/gtgirfajqe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gtonigbvzy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklmugqbp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuxming.cn/Article/details/gtvwksulcc.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gtjycmriol.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gtkrkbyrlf.html

[U44] PHP：开启严格类型
来源：http://dali.c1oappe.top/Article/details/gtesmrinos.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gtnshwwyhb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gtovtynbay.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gttpkjkbks.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gtxphcqyeu.html

?string $name = null
来源：http://dali.gaohongyu789.top/Article/details/gtwunfqjnk.html

[U47] PHP：联合类型
来源：http://dali.dianchejie.cn/Article/details/gtlkbtoipt.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gtdhnihkrl.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gtgtnrivmj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zdqjudy.top/Article/details/gtdukaxcql.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtaunoqedr.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gteqjevtcq.html

[U50] PHP：构造器属性提升
来源：http://dali.hysaishi.cn/Article/details/gtmqxtbvei.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtymcztyrb.html

[U51] PHP：数组解构
来源：http://dali.cqqwz.cn/Article/details/gtyejvlgll.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gtcyxbnllu.html

[U52] PHP：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtyvwenxpg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtjzecpfjg.html

[U53] PHP：空合并运算符
来源：http://dali.hywenlv.cn/Article/details/gthyeweksb.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gtahasmvxe.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtavkroxxx.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gtwinmyrzs.html

[U55] PHP：match 表达式
来源：http://dali.snrcjt.cn/Article/details/gteotltfmz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gtxhddzesm.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gtmknlhvzo.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtxsjsqmby.html

[U57] PHP：字符串插值
来源：http://dali.ybcxt.top/Article/details/gthwejypxh.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gtvzzdepma.html

[U58] PHP：数组三件套
来源：http://dali.hammf.cn/Article/details/gtkwinlniu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.redwolf501.top/Article/details/gtmytneqvw.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gtgudqhtlf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtxppsegre.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gtqowkdhnh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aizwys.cn/Article/details/gtlenaumsk.html

[U61] PHP：正则
来源：http://dali.zhixingplan.top/Article/details/gthcvzesnf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtqaqkglfo.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gtmogjktgm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gtotockdpj.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtdukveeto.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtupxtumgq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gtbjajicfs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gtumpzgbij.html

[U65] PHP：会话
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytfdbkvp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.316326.xyz/Article/details/gthmzmxlci.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gtnblzvbrs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtpbqwfoxt.html

[U67] PHP：处理文件上传
来源：http://dali.nwbrower.top/Article/details/gtnhljujqq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gtnzlzopkk.html

[U68] PHP：PDO 连接
来源：http://dali.cheryme.top/Article/details/gtywmhtkpv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtqgavjiww.html

[U69] PHP：PDO 预处理
来源：http://dali.chenjidiqi.icu/Article/details/gtouqkxvnb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtodbkziig.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtvuuenuol.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gtukstgjhv.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtfmrearex.html

throw new RuntimeException("失败", 500);
来源：http://dali.ivvv.top/Article/details/gtpxrvjjmz.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gttkiypsrm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.birdmap.top/Article/details/gturjjbuvy.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gtvrjfqsar.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gthbinolpm.html

[U74] PHP：读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtswfegjba.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigufen.top/Article/details/gtuqdtjbtt.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gtghptytbn.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gtmifxsbcy.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gtbnjgtxfl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cqqwz.cn/Article/details/gttyiojagl.html

[U77] PHP：模板渲染
来源：http://dali.yuanzhike.top/Article/details/gtzqpgekfc.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gtzozqmkis.html

[U78] PHP：单元测试
来源：http://dali.cashguo.top/Article/details/gtsgnqyedx.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gtnehksnfi.html

[U79] PHP：静态分析
来源：http://dali.jinqigfzy.top/Article/details/gtxhwhewdp.html

composer require --dev phpstan/phpstan
来源：http://dali.mhx1999.top/Article/details/gtxiyquaqb.html

[U80] PHP：代码规范修复
来源：http://dali.aibaodan.cn/Article/details/gttpoqwtkc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gttcgwleot.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzbcnupr.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gtgxnavybw.html

[U82] JS：package.json 脚本
来源：http://dali.shangyingyoupin.top/Article/details/gthjvinazk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhiwuduotai.top/Article/details/gtluvhfwcw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtfstavceo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtsabeyznb.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gteojwrseb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigufen.top/Article/details/gtewercrtz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gttjkhbitz.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gtkciiijgj.html

[U86] JS：空值合并
来源：http://dali.wangshuangyany.cn/Article/details/gtyfvalwoa.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gtczpfpgso.html

[U87] JS：解构默认值
来源：http://dali.hfpthk.cn/Article/details/gticqaoapq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gtlwkuhtyd.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gtrnmahmnv.html

{ ...a, ...b }
来源：http://dali.havefunace.top/Article/details/gtedctelks.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gtuxsycjlh.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gthqiiozqg.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gtzxidptyu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtcgxzwvjt.html

[U91] JS：对象键值遍历
来源：http://dali.cqqwz.cn/Article/details/gtyktgcxne.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gtzpvlovqn.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gtvmsldvwt.html

structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtxjsngrlj.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtlfltkgen.html

`共 ${n} 条`
来源：http://dali.hysaishi.cn/Article/details/gtheakmmjb.html

[U94] JS：箭头函数
来源：http://dali.c1oappe.top/Article/details/gtznjjpmou.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtfsmdqgvu.html

[U95] JS：Promise 包装
来源：http://dali.dianchejie.cn/Article/details/gtooivthxo.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gtzmdrfnrh.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtawdluqkm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gturxmjghp.html

[U97] JS：并发请求
来源：http://dali.feifeiyinyue.top/Article/details/gtuouqkqbx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtrxntxdrh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zycfv.cn/Article/details/gtbttponph.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gtzlouevea.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gtsliiojmp.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gtnalwmmzi.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gtandhvkgl.html

document.querySelector(".item")
来源：http://dali.guannengcc.top/Article/details/gtuaaeqvcv.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gtpxjbabtq.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdxywugp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gtjddyghgl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tianlin.xyz/Article/details/gthxdcboxi.html

[U103] JS：定时器
来源：http://dali.c1oappe.top/Article/details/gtecajrnsw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258888.top/Article/details/gtecudtsnx.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwwsmjim.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtjdeykzbl.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gtdqiykigv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtwlrmccon.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gtaocejxax.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gtuqoodcfm.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtvstobpan.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtralkvcql.html

[U108] JS：随机整数
来源：http://dali.daxiang520.top/Article/details/gtewlnbvrh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fzhhl.top/Article/details/gtoezpshmd.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gttoitklya.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtlmukcfmx.html

[U110] JS：数组分块
来源：http://dali.nanxuanxn.top/Article/details/gtljmvzumn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gtfmydjwvh.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gtxupseatw.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gtcbxodyfz.html

[U112] JS：字符串补位
来源：http://dali.fzhhl.top/Article/details/gtmiggdsnu.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtmdvwcppc.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtyvmcdxfo.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtgdxocium.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gtpefrdjyd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtobipsxfo.html

[U115] JS：生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtlymdkkys.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtadubhpdh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtzwcmsqzx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gtnvpdfmvx.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtcuezyfcn.html

npm i -D vitest;  npx vitest
来源：http://dali.cucudq.cn/Article/details/gtabfiwnnm.html

[U118] JS：开发服务器
来源：http://dali.smart0.xyz/Article/details/gteautpbkg.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gtwunwchjy.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtfzeoxsjx.html

npx vite build
来源：http://dali.xylfe.cn/Article/details/gthgabpgwg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sysykeji.top/Article/details/gtjjrkmnwb.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gtltgvopui.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqxrfopgv.html

统计汇总
来源：http://dali.cqqwz.cn/Article/details/gtgacxwdto.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsiebghlz.html

按语言统计（条）：
来源：http://dali.zhiwuduotai.top/Article/details/gtbwlqzgfr.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gtiscfizap.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfhaimah.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gtarnhzbod.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gtmvkwnqvi.html

Java ........... 212
来源：http://dali.316326.xyz/Article/details/gtietbhqch.html

Go ............. 212
来源：http://dali.yj202588.top/Article/details/gtzfzitrap.html

Ruby ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmjzlkgj.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtvjvfqkdy.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtzpwrptkh.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gtevqbbmes.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtmptxaova.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtsmgvkcne.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtujerybms.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtkvvurnna.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gtdunmxwoq.html

Perl ........... 10
来源：http://dali.snrcjt.cn/Article/details/gtxvxklvkx.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtcegvmucy.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqiyueio.html

合计 ........... 2106 条
来源：http://dali.yanxiufei.cn/Article/details/gtkyoeqrcn.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gtoeybkprz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtjahpswdy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtuaocltos.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjmvwmcg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtbahpflxy.html


<!-- 参考信息 -->