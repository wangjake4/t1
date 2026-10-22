代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gt2lzpvdqyf.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gt2kegkodsi.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gt2bcqpcglo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2cqleltpx.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gt2xovqtdeh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gt2kqvdaozi.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2ehfsmrjn.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqnzcgxc.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gt2whxqcxtz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2mstfhdlg.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2diwpddci.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gt2lxgogvfo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjpviugs.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2mtjyzbkk.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2wcwiittx.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gt2pnqmdemm.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gt2thjalzey.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2jmsiovre.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2acrgminm.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2tvmanyau.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2mudxaoiw.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2blwicfki.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2yuwcnhyb.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gt2gtccadld.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2yzneqwah.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gt2lkyjvxnh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gt2vwmswxqu.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gt2wowovfgn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gt2liuiaajs.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2xpzovuoj.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2aclgqdtj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fyktsqhh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjwkgbbo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vwdzilps.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gt2nccbopqd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2urzxhtod.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gt2peyqcgms.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjsvpfkq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gt2gaxktwqq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gt2fkrzaqzi.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gt2ogdtmupk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gt2nkxdpxkh.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gt2wqtzbctu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gt2tdzoqgpu.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gt2oiaroeqf.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2ytatoqka.html

[U06] Py：合并两个字典
来源：http://dali.daria6918.cn/Article/details/gt2vxmlzxxi.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gt2sstmitwc.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gt2zbojufjx.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gt2aubadrag.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2gkkwlrih.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbiourxh.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gt2fwywfwcs.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gt2bpzsknza.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbwnpwln.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gt2jopimqig.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gt2yydzloxu.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2dqqpfupo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gt2gbfoaphf.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gt2ydgtvkkb.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gt2efyyepem.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gt2eodshktw.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gt2mdsnimgw.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gt2xzspdwpu.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gt2wtkskdnh.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2kiizaavc.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gt2doritwja.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gt2kqxkairv.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gt2qopiogvj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.bjfxy.top/Article/details/gt2fwyetkjx.html

[U18] Py：预编译正则
来源：http://dali.jianghu66.top/Article/details/gt2yfxzjbhx.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2evotfvga.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258888.top/Article/details/gt2rumzdgwd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gzhubu.top/Article/details/gt2fefhqyfp.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gt2ppkyeofb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gt2fbmiryie.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gt2bckkdrmv.html

@contextlib.contextmanager
来源：http://dali.jqgfzy.top/Article/details/gt2hezkwfsa.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gt2addypngn.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gt2wvbnnmdk.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gt2uirrrqvg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gt2orktyvri.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gt2jbzepzgl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2nyqrkxit.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gt2adbmsoxm.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gt2prwejtgj.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gt2rppcnyrb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gt2gcyfeeoe.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gt2kopncwvj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gt2oihfdnln.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gt2kbqcwjzk.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gt2tmpcvdir.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gt2wpgprfji.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gt2qiahwsdj.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohqoznzf.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gt2gcsmeylf.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjwwdwqs.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gt2tfrqmqkb.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gt2wypwjnwj.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gt2nlxiclum.html

[U33] Py：打包发布
来源：http://dali.yueranfly.top/Article/details/gt2sgpunawr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gt2qvvgbffx.html

[U34] Py：判断编码
来源：http://dali.chenzaomai.com/Article/details/gt2pxacnddg.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gt2wotrspuy.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2cmodsuvg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gt2yecmlulq.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gt2vbrwrwey.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gt2iwmkoqvi.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gt2rhojujij.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gt2kyzsemwr.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangdashe.top/Article/details/gt2mswyimyh.html

Path(__file__).resolve().parent
来源：http://dali.aizwys.cn/Article/details/gt2luufshqm.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgtdubgi.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnvtctzb.html

[U40] Py：打印到标准错误
来源：http://dali.mhx1999.top/Article/details/gt2pbmwlcpc.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2lkknowhn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gt2jlahmoaq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yhomhkcq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gt2bctjisja.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gt2mppgpyrq.html

[U43] PHP：声明命名空间
来源：http://dali.hammf.cn/Article/details/gt2nejblsjx.html

namespace App\Http;
来源：http://dali.nanxinkj.top/Article/details/gt2pqkbuhgz.html

[U44] PHP：开启严格类型
来源：http://dali.tian-w.cn/Article/details/gt2rmgrabrt.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djbglkay.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xziqi.cn/Article/details/gt2ritmubxz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2rtyzwnhk.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gt2uamjwnoj.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gt2pxsncsle.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gt2juyouagg.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gt2izdafuzw.html

[U48] PHP：纯枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2ivroykbt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dianchejie.cn/Article/details/gt2qpfzadmb.html

[U49] PHP：只读属性
来源：http://dali.jyoumei.cn/Article/details/gt2jesbmaci.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gt2bebssybs.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gt2jemjaojr.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2rbhevivy.html

[U51] PHP：数组解构
来源：http://dali.jyoumei.cn/Article/details/gt2pwlrlqzp.html

[$a, $b] = $arr;
来源：http://dali.yvedp.cn/Article/details/gt2vhdavtda.html

[U52] PHP：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gt2ubqfiqsk.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gt2wswtmpsd.html

[U53] PHP：空合并运算符
来源：http://dali.guowangkeji.top/Article/details/gt2xworqoge.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfcpvfhr.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gt2hjlsudtt.html

$obj?->method()
来源：http://dali.sufxvd.cn/Article/details/gt2bfrxkxff.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2aqkzpzmu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ivvv.top/Article/details/gt2lylwyxrm.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gt2mznbhmwq.html

f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2dliyfmpf.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2vydrjicw.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gt2glsciefv.html

[U58] PHP：数组三件套
来源：http://dali.bjfxy.top/Article/details/gt2kvucbitg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gt2ixxavhrf.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gt2eelwxbvh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2opkzcavv.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gt2qhsvbaqt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fzhhl.top/Article/details/gt2ftbagzah.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gt2qefdpere.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2qybnbpob.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gt2mbxddbaf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gt2fyzlpwyt.html

[U63] PHP：文件读写
来源：http://dali.zycfv.cn/Article/details/gt2gecsvmsb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gt2hawimjnw.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gt2kpmkdutv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dswavxfg.html

[U65] PHP：会话
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmbfjeqo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2pedndfgx.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gt2xvrfgcvc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gt2jvmaylcn.html

[U67] PHP：处理文件上传
来源：http://dali.daria6918.cn/Article/details/gt2jijvchts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gt2udzusckv.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixzirgat.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gt2eprryezi.html

[U69] PHP：PDO 预处理
来源：http://dali.gzhubu.top/Article/details/gt2hlusrxhw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezdyunts.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gt2gadqvcuy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gt2rmomsnup.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gt2esqzhrlu.html

throw new RuntimeException("失败", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2padixkmz.html

[U72] PHP：写错误日志
来源：http://dali.cashguo.top/Article/details/gt2bgelhjwj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sxryk.cn/Article/details/gt2ohzyveyd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2hqekmpbm.html

parse_ini_file("config.ini", true)
来源：http://dali.guannengcc.top/Article/details/gt2qvjpplil.html

[U74] PHP：读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isekcyjf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangdashe.top/Article/details/gt2lhmufhra.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gt2zrhsdnrg.html

composer require psr/container
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apmywhyp.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gt2vdivdaid.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gt2zynnjozn.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gt2avhjpxyf.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gt2wjabjfwh.html

[U78] PHP：单元测试
来源：http://dali.fengsongda.top/Article/details/gt2fdhzdvov.html

composer require --dev phpunit/phpunit
来源：http://dali.yvedp.cn/Article/details/gt2fnkxgxxx.html

[U79] PHP：静态分析
来源：http://dali.xinyue.icu/Article/details/gt2uyqaaazj.html

composer require --dev phpstan/phpstan
来源：http://dali.iojbl.cn/Article/details/gt2ownglmiv.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gt2gnnudwmd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irhauiwd.html

[U81] JS：初始化项目
来源：http://dali.daria6918.cn/Article/details/gt2vqxjqnyq.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gt2stgvrgzz.html

[U82] JS：package.json 脚本
来源：http://dali.yanxiufei.cn/Article/details/gt2lvbvxdzd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gt2noroafhr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtwuytj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gt2siizjxct.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppighbfc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gt2hnhdmsid.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gt2izpbmknb.html

a?.b?.c
来源：http://dali.yanxiufei.cn/Article/details/gt2fysvbqsf.html

[U86] JS：空值合并
来源：http://dali.xuanzx.com/Article/details/gt2yngliatg.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gt2isdmvqgk.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gt2dvbmnbbs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tian-w.cn/Article/details/gt2mssiudur.html

[U88] JS：对象展开合并
来源：http://dali.daria6918.cn/Article/details/gt2akuomzml.html

{ ...a, ...b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqrkqiru.html

[U89] JS：数组去重
来源：http://dali.shuidangran.top/Article/details/gt2zrrlfaey.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2mlwxqrlp.html

[U90] JS：数字数组排序
来源：http://dali.chenzaomai.com/Article/details/gt2uyocshtc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2dhwrosdw.html

[U91] JS：对象键值遍历
来源：http://dali.haohaochexian.top/Article/details/gt2cnksmatp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gt2qusgviqe.html

[U92] JS：深拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2rokqeppi.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2kevvbhtz.html

[U93] JS：模板字符串
来源：http://dali.ybcxt.top/Article/details/gt2qtopvmxa.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gt2mgssuhyo.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvghkdfb.html

const double = x => x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdgjikrv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2agzhzcow.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gt2yoxyhxxw.html

[U96] JS：async/await 与异常
来源：http://dali.hywenlv.cn/Article/details/gt2trfylcty.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2mfpdrsfm.html

[U97] JS：并发请求
来源：http://dali.mhx1999.top/Article/details/gt2iuacjnvw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2ujfkkjsd.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2slholtdp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.birdmap.top/Article/details/gt2qhqjemqk.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gt2wqgsbqgd.html

el.addEventListener("click", e => {})
来源：http://dali.cheryme.top/Article/details/gt2muabdwto.html

[U100] JS：DOM 查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwtdklcn.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gt2qrywbprm.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myjwdzho.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2pmpdvidk.html

[U102] JS：本地存储
来源：http://dali.gaohongyu789.top/Article/details/gt2mtefowmq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxbivoip.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gt2wlrcqkwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gt2zcqsvtlw.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gt2falmcnnh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2osfxydpq.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gt2fzsjenhs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gt2cmlfzkwz.html

[U106] JS：日期格式化
来源：http://dali.xylfe.cn/Article/details/gt2pqgicstz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.iojbl.cn/Article/details/gt2fxvpzzul.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2ckrzpxco.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2avjbwvow.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gt2aaprcknu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gt2qwlenhfp.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gt2nznxecvq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gt2raodkxfw.html

[U110] JS：数组分块
来源：http://dali.aizwys.cn/Article/details/gt2zqtclkwd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gt2kfzajevx.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gt2wvmadvcm.html

new Map(Object.entries(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2qavghsma.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gt2bdnmjnmc.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2ojgadyrd.html

[U113] JS：正则替换全部
来源：http://dali.mhx1999.top/Article/details/gt2zhqzsxmc.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2ruegmyla.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gt2tqoshxed.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gipcohzm.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2essgnlzu.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfcejhwa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gt2ruiscnop.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2itrnqcnf.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gt2lyepfazd.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gt2rahvfcqu.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gt2ymwothsx.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gt2grxcycka.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gt2grdayxqh.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gt2okoczpbw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuanzhike.top/Article/details/gt2vnfmtplk.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qszquhwh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xlhwtzdg.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbssqwqk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bmjqydtr.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gt2vljqrdiq.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gt2ojmmaaci.html

PHP ............ 252
来源：http://dali.yuxming.cn/Article/details/gt2hjvrwgao.html

JavaScript ..... 252
来源：http://dali.zhixingplan.top/Article/details/gt2oxzzicbo.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gt2ayxokugz.html

Java ........... 212
来源：http://dali.daxiang520.top/Article/details/gt2kviprsxy.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gt2wiilsjuf.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqvazdoe.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gt2epsvwpwb.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gt2skzgvjyd.html

C++ ............ 30
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwvnhgyj.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gt2fyamupxj.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gt2bqggclkc.html

Kotlin ......... 15
来源：http://dali.sysykeji.top/Article/details/gt2yomxhbmp.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gt2efbmxkqd.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gt2srcjidvu.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gt2rkebctkd.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gt2glnarpqt.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gt2efyolozr.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2mzrsfuul.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gt2wzfjjaff.html


<!-- 参考信息 -->