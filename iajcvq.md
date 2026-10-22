代发 wailian999

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gt2yvmjzbjc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2wiumvtqq.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2isvovbhm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhengqikj.top/Article/details/gt2nsyatgjw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2afytzpdw.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2cnlsxszl.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2ntlfgrwh.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2bsjyldza.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gt2rmjtgisc.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2vjqndfeo.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kasjhlgf.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2skvvsocn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2dmclplyt.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2uwrbwgqc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2onzmiejp.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gt2xjobcoiw.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2wznpjgya.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ucrxmpzn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2ampvlhxb.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gt2vggjboxx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gt2vmsnwgfd.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gt2dthsaobl.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2mlvaarhb.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gt2xwfkpmlu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gt2trihftda.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zhowjkxl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2utzldymk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hviqmkoa.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2aozpetco.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gt2cdhrlwyi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gt2rnqkbyht.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2acpbegfc.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gt2jjpssxmo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.316326.xyz/Article/details/gt2ighifzkt.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gt2xcqkhblg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gt2vlgedgst.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gt2tdhjtdwj.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2vtgbawbn.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2btxxwuva.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gt2owxrwmbe.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gt2gstattxw.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gt2eimcsryz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgelppf.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gt2mymlhksq.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gt2rjfznpsc.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gt2gihhhleq.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gt2zyaagajb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gt2fmhtcvjs.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gt2zypvxyit.html

(x * 2 for x in arr)
来源：http://dali.shuidangran.top/Article/details/gt2qcldirto.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gt2srmwmfxh.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gt2hopjkazu.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gt2wciuxqda.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gt2drlhrpdy.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymtwgzzq.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gt2umiytzsx.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gt2xqxmozif.html

t = time.perf_counter()
来源：http://dali.yangfankeji.com/Article/details/gt2izztbmuc.html

[U16] Py：命令行参数解析
来源：http://dali.havefunace.top/Article/details/gt2rviccjbh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gt2ukkvtvwr.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gt2jexnefme.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gt2zomdthwq.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gt2jrvrtuzq.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2khitbfux.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gt2qbabfcvh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gt2gnedxnyl.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmkcfwcz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gt2mnjeqrva.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gt2qamvzvgb.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gt2vtdltrpu.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gt2hnlvswaw.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2rbrtdeao.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gt2glmocsof.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gt2bmetxtdp.html

[U24] Py：路径操作
来源：http://dali.hnqzz.top/Article/details/gt2vlbuxcbr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxilwxqu.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gt2sxjpiqup.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gt2vmnpkmut.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gt2xhiicxit.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gt2kdheyeck.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gt2efwfoeak.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnlykgax.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gt2seejrnvs.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gt2blznryyc.html

[U29] Py：属性校验
来源：http://dali.hammf.cn/Article/details/gt2tcdydnmi.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzpqtqei.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gt2fdhiwstf.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gt2svyoavru.html

[U31] Py：单测
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgpcpudf.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gt2skvjzzut.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gt2rkftdajn.html

ruff format . && ruff check --fix .
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sstcaday.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gt2qioypphc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gt2qlgusbte.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gt2uwmejbrz.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gt2hztqkhja.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gt2rhvhhmig.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gt2qadobzrw.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gt2ctmjhtzg.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gt2ngatrvzf.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gt2piqjtete.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gt2ubeqtiub.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2pzurdyuf.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gt2qwcmdkvp.html

[U39] Py：判断是否在交互环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcqnlkzo.html

sys.stdout.isatty()
来源：http://dali.hysaishi.cn/Article/details/gt2bykogmpz.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gt2agwqywrh.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gt2mbuurssj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gt2gxqoaqqa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gt2ddfysvmm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gt2ocaahasg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gt2zbhxknbi.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gt2owuljwdw.html

namespace App\Http;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eiywvxod.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gt2qyjpscjw.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gt2nadybgmi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gt2fzvawmul.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2uliaaedz.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gt2uqdkoxoi.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gt2odtagnuw.html

[U47] PHP：联合类型
来源：http://dali.smart0.xyz/Article/details/gt2lmbibiib.html

int|string $id
来源：http://dali.yj202588.top/Article/details/gt2uulmdbqd.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2potoxrkc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hcstqrba.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gt2gjhunpks.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gt2jutyogrs.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gt2wttcjbrt.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gt2kfqcemri.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gt2iavyktnj.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okkfobzt.html

[U52] PHP：箭头函数
来源：http://dali.zhoulong.xyz/Article/details/gt2qlkuigxq.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2mzjflbwr.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gt2qijsijni.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gt2hkegwfgw.html

[U54] PHP：空安全调用
来源：http://dali.haohaochexian.top/Article/details/gt2kyselodc.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gt2vsgjjssd.html

[U55] PHP：match 表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2wikqaqdb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gt2oztinkrs.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gt2gmsgmcwq.html

f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2kydbyawj.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2ogmeogrm.html

"值: {$a}"
来源：http://dali.smart0.xyz/Article/details/gt2yavqmfev.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gt2shzmjwgw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shuidangran.top/Article/details/gt2kmkuiwpk.html

[U59] PHP：自定义排序
来源：http://dali.kuanghao11.cn/Article/details/gt2blhtpsyf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzyjtrpv.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gt2ctuqqpgg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2hjuffrsa.html

[U61] PHP：正则
来源：http://dali.fzhhl.top/Article/details/gt2mhimehje.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2xqzmddxb.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gt2kwgjrptv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gt2fdszyidd.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jswmvldi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2biarsjon.html

[U64] PHP：目录遍历
来源：http://dali.nanxinkj.top/Article/details/gt2wwlomnfc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gt2ytjbdpsu.html

[U65] PHP：会话
来源：http://dali.cheryme.top/Article/details/gt2ujtwkevv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzvgkzyy.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gt2soawcwvr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dashuyun.cn/Article/details/gt2bwihojaz.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oujzyejs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuxming.cn/Article/details/gt2riychvtp.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gt2fdexlzrg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gt2tylphsri.html

[U69] PHP：PDO 预处理
来源：http://dali.sufxvd.cn/Article/details/gt2fdwrosof.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gt2mtjymebn.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gt2dmtvinif.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gt2kukvkqrc.html

[U71] PHP：抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jljqykmz.html

throw new RuntimeException("失败", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpqchewl.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2terzzcne.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smfhynkv.html

[U73] PHP：读取 ini 配置
来源：http://dali.jlsjyb.cn/Article/details/gt2buwnkyvo.html

parse_ini_file("config.ini", true)
来源：http://dali.havefunace.top/Article/details/gt2kekvnzpu.html

[U74] PHP：读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gt2syqpbtua.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gt2vmnfopqt.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gt2zhbfjbeu.html

composer require psr/container
来源：http://dali.iojbl.cn/Article/details/gt2kyplejqf.html

[U76] PHP：简单路由
来源：http://dali.ppjwa.cn/Article/details/gt2hdzshxue.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gt2rctudwpe.html

[U77] PHP：模板渲染
来源：http://dali.iojbl.cn/Article/details/gt2renusffj.html

composer require twig/twig
来源：http://dali.nanxuanxn.top/Article/details/gt2gxvbjvls.html

[U78] PHP：单元测试
来源：http://dali.gzhubu.top/Article/details/gt2oepckuqt.html

composer require --dev phpunit/phpunit
来源：http://dali.cqqwz.cn/Article/details/gt2dkgegdpn.html

[U79] PHP：静态分析
来源：http://dali.daria6918.cn/Article/details/gt2okvilzmc.html

composer require --dev phpstan/phpstan
来源：http://dali.iojbl.cn/Article/details/gt2gmoijfku.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gt2oxpnlnzn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hywenlv.cn/Article/details/gt2wcubheme.html

[U81] JS：初始化项目
来源：http://dali.redwolf501.top/Article/details/gt2skzfqrud.html

npm init -y;  npm i express
来源：http://dali.jlsjyb.cn/Article/details/gt2chywzhjb.html

[U82] JS：package.json 脚本
来源：http://dali.yuxming.cn/Article/details/gt2qrizafcx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gt2amuefyfo.html

[U83] JS：ES Module 导入导出
来源：http://dali.yangfankeji.com/Article/details/gt2qsewghhu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2iaiurjsv.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gt2bxdghxoh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.quarkkingdee.top/Article/details/gt2gbubzsrz.html

[U85] JS：可选链
来源：http://dali.hysaishi.cn/Article/details/gt2cryztwyb.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gt2ntpqukum.html

[U86] JS：空值合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2pllaauhf.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gt2faugfqdh.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gt2qvkxophc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shuidangran.top/Article/details/gt2nifibfqi.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gt2kogndoix.html

{ ...a, ...b }
来源：http://dali.jiagoushi.top/Article/details/gt2vilapaey.html

[U89] JS：数组去重
来源：http://dali.smart0.xyz/Article/details/gt2fnhdugsm.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2srogqalt.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gt2schtvvrh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2twzqlkaw.html

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gt2qzxhqbeq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yangfankeji.com/Article/details/gt2sgfosilo.html

[U92] JS：深拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2ginwsiaw.html

structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2manobfrs.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gt2hguykhhy.html

`共 ${n} 条`
来源：http://dali.jiagoushi.top/Article/details/gt2ebywlrqn.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gt2tbtbzwuu.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gt2ahgvnvoj.html

[U95] JS：Promise 包装
来源：http://dali.dashuyun.cn/Article/details/gt2mrjnlwxe.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258888.top/Article/details/gt2dmincfgh.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gt2qcfgzpdu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2dscaheox.html

[U97] JS：并发请求
来源：http://dali.ppjwa.cn/Article/details/gt2ddunumfy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2axpbnjtm.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2eecrndfy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.iojbl.cn/Article/details/gt2ufgmxqmu.html

[U99] JS：事件监听
来源：http://dali.shuidangran.top/Article/details/gt2beottlne.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gt2hsmtzmhp.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gt2wxyrvdzq.html

document.querySelector(".item")
来源：http://dali.pycfn.com/Article/details/gt2xueorgft.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gt2asdccjoc.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htqmhjjr.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gt2tismhkxn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gt2uclllygq.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tehriyvr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.bjfxy.top/Article/details/gt2kpinefly.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gt2cfhbumqm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2lnqruujz.html

[U105] JS：节流
来源：http://dali.zhongyouzk.top/Article/details/gt2yxxhobkg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gt2kpcgtxla.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2btppeqey.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gt2opfhutgs.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2qywygyix.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gt2csjurmyv.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gt2mybkuquk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqpdrtpw.html

[U109] JS：数组分组
来源：http://dali.ydzc1.top/Article/details/gt2zxqubxdh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2egblkhsl.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnlueidp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gt2wccgzhvp.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gt2oaratqav.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gt2othgnxch.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gt2ucygoufe.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2galqscwe.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gt2iykkvegd.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2moijdxwn.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gt2znsszzfh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gt2hlndqkxm.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gt2pdynazfl.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2rsvkwola.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxinkj.top/Article/details/gt2ydsckqgx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2bsxmxkfv.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdqozdii.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gt2usureaxe.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gt2zvulnnkd.html

npm i -D vite;  npx vite
来源：http://dali.jlsjyb.cn/Article/details/gt2nnobpczw.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gt2jlxejwsw.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gt2yzobtjmn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gt2dydrpujn.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gt2xkqgmyhq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pconmzwf.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrvjiykg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2bxsnaemc.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gt2ibhxhjmf.html

Python ......... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2lwrjtdkp.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2uenoohpp.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gt2qifjbzvl.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gt2zveqxhoo.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gt2kplzehvi.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gt2evahmjkq.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gt2jnbpkacu.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gt2wzdiqrqa.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gt2uhwjehnn.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gt2oluizvbq.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gt2ffcumtyo.html

Bash ........... 80
来源：http://dali.jqgufenzy.top/Article/details/gt2eynauhry.html

Kotlin ......... 15
来源：http://dali.meibo888.top/Article/details/gt2mmhpcwwe.html

Swift .......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gt2rthktggq.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gt2wjzkcxos.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gt2ttsowqmx.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gt2xfvjnmkf.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2tluecujd.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gt2hvtkecxk.html

按章节统计：
来源：http://dali.hfpthk.cn/Article/details/gt2wqtopeqa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gt2hznvjilf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gt2plhptoje.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2aahnwuee.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gt2gjwfbbju.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xinyue.icu/Article/details/gt2cqkpwcew.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gt2kypnfohs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2dqcfpnat.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrvxiqoy.html


<!-- 参考信息 -->