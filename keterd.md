代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2xqlkbqdz.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gt2xuvfvsyj.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gt2vbzuvcgu.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gt2juqkejxy.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gt2qhhhawhz.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gt2pjkevmru.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gt2ojmdwoui.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gt2grtlnggl.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gt2imolqxtn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gt2agilsngp.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gt2xzosrzdw.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gt2sqsailgm.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gt2ukuhjslw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2enxtmjsn.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2rpktegsu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gt2nsmxtjfg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gt2wcgmgzlw.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2kootgeua.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2shznkkwr.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gt2cmhwimbr.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gt2qkrcpugv.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2fxsvozvt.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2iylplrcf.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gt2pdchisxu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqyzerlf.html

[T55] Scala：集合过滤
来源：http://dali.yvedp.cn/Article/details/gt2eafssssk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gt2xtycmmhq.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gt2swvrpdqj.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2celacawe.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2alpskwsh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gt2svgejinf.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozqxtuoc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gt2awuegbjb.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gt2skjxkkqs.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhbydbmu.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gt2lckcybxq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258.top/Article/details/gt2vwcbguop.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2mzlxykeh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2mzcnjjko.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qkyqoxff.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gt2zaztcrwb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gt2lueiajgh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gt2plxaozcq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gt2fdagxeaj.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgsjvcmm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gt2ontztbpq.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gt2yfkkejui.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gt2nzmgdvow.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gt2xvtwgwjw.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddfhjvvz.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gt2kstjxiry.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gt2bjombmfy.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gt2cgnflsem.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wogyuxvp.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlmjvcui.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gt2npvkdfqu.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gt2oylasfrf.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gt2pyulryqn.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gt2lvyxvhmb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2kfrziuej.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gt2dnjiaqps.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gt2xcbzwxas.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iofesmsq.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gt2aeuadwcy.html

[U13] Py：固定长度队列
来源：http://dali.sxryk.cn/Article/details/gt2ljhxwisn.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2entytcgw.html

[U14] Py：分组收集到列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dugrmtnx.html

defaultdict(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xaqgetgf.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gt2lsxbwczj.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gt2wmzioqfn.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhutuwaf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gt2hlyeldlo.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gt2znhkkxot.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gt2bvgpinfb.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gt2qhgskntk.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2xucdtakk.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gt2wtfpfoyq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gt2plehevyf.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gt2mdrlbfyy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gt2rftbkxyj.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gt2civuoewy.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gt2xwkyapof.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gt2qoysfxix.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gt2klwwqrjf.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gt2zgunqpnc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gt2zjkrquae.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gt2csftgwjh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2uawicnxx.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gt2xnpqvzom.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yftespzf.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gt2gctqwlwt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gt2pthetucc.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gt2qynzwnuv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oltuuirx.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gt2fzqxsvrx.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gt2ekigvxfz.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gt2kvicdsqk.html

@property 与 @x.setter 配合
来源：http://dali.hnxiangtu.top/Article/details/gt2zxnjfqca.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gt2mavzcuis.html

@dataclass(slots=True)
来源：http://dali.pycfn.com/Article/details/gt2vaseeutd.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gt2iivcmjgx.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gt2sgcwwwvi.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2igasukea.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gt2anoqcnge.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gt2nbzzppdq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2wuewngnx.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gt2eedlkpuc.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gt2fglyfwge.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gt2ajfftouj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gt2lgectwkf.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gt2tizrsgbm.html

schedule.every(10).minutes.do(job)
来源：http://dali.sweek.top/Article/details/gt2qlcexghn.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gt2akfofnmm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.svipenyu.cn/Article/details/gt2uhfajtln.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmrhdqoe.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gt2rgeazess.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gt2qfaqbmfh.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gt2kvjxvsct.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gt2pytplqka.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jduilyze.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gt2dbcjaeoi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gt2eikqfjos.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258888.top/Article/details/gt2ozkngslu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cdnleiting.top/Article/details/gt2cspyedyc.html

[U43] PHP：声明命名空间
来源：http://dali.hammf.cn/Article/details/gt2jwzptyxv.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gt2xtddmkcn.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gt2ekuqytup.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gt2hnpxgaqx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gt2cciumowr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2ebfcemuk.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gt2wpxfdxan.html

?string $name = null
来源：http://dali.zhiwuduotai.top/Article/details/gt2itdwlxms.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjbsljze.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gt2fancaecb.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2lkdsuklp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhbirokc.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gt2vqhawfpu.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esjuchfz.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gt2rnwoaldi.html

public function __construct(private int $id) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2txxcnixb.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gt2kwzbdzez.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gt2vinoxzbe.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2vuiryzhp.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tabjtctl.html

[U53] PHP：空合并运算符
来源：http://dali.quarkkingdee.top/Article/details/gt2ijghuute.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gt2vboauvcr.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gt2oduhpbbr.html

$obj?->method()
来源：http://dali.chenzaomai.com/Article/details/gt2sppcdrmf.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gt2fkukxphh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuxming.cn/Article/details/gt2kdiyumor.html

[U56] PHP：命名参数
来源：http://dali.yuxming.cn/Article/details/gt2nmtgopyy.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2yiaqxsms.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gt2ifmofshq.html

"值: {$a}"
来源：http://dali.shzxlz.cn/Article/details/gt2nlbwczii.html

[U58] PHP：数组三件套
来源：http://dali.jyoumei.cn/Article/details/gt2autwxxly.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2hnspmdch.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gt2wflguvbg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gt2nymtpqmk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gt2jfecdswy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2usbsljfq.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gt2qxgaafqj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2nsaxgrhe.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gt2zxprtzru.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkxvrxul.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esyypobb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yanxiufei.cn/Article/details/gt2blfjrqxh.html

[U64] PHP：目录遍历
来源：http://dali.zhengqikj.top/Article/details/gt2auwnukes.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yueranfly.top/Article/details/gt2hmchzksn.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gt2hewtvwwd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2knzrmnlg.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gt2qmnflipp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fengsongda.top/Article/details/gt2rkpvprta.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gt2kwoxeaqx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqvkiduu.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gt2qutfxont.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gt2tzjpxtmi.html

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gt2vucybqbe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gt2lfukdopc.html

[U70] PHP：PDO 事务
来源：http://dali.zhoulong.xyz/Article/details/gt2nijikvfj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewhinpoh.html

[U71] PHP：抛出异常
来源：http://dali.redwolf501.top/Article/details/gt2hlichjvt.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gt2wqijmkyi.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gt2iqpdzqys.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gt2gfyyveae.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gt2pvcufuqd.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gt2nenaqzjf.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2vjwaesfs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guannengcc.top/Article/details/gt2uscfbicg.html

[U75] PHP：依赖注入
来源：http://dali.tianlin.xyz/Article/details/gt2bgtpvtzh.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gt2umrblqlr.html

[U76] PHP：简单路由
来源：http://dali.tian-w.cn/Article/details/gt2eykccbob.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gt2nehjpeju.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gt2fdxybdzh.html

composer require twig/twig
来源：http://dali.meibo888.top/Article/details/gt2eaxxxyud.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gt2jjccrtec.html

composer require --dev phpunit/phpunit
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhfwxbxy.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gt2netleeum.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gt2ykqyvxkb.html

[U80] PHP：代码规范修复
来源：http://dali.hysaishi.cn/Article/details/gt2oonhkulb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gt2drycnmoz.html

[U81] JS：初始化项目
来源：http://dali.ybcxt.top/Article/details/gt2kmetqbqn.html

npm init -y;  npm i express
来源：http://dali.ppjwa.cn/Article/details/gt2bhdgcreh.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gt2cziczaah.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ehwqpu.com/Article/details/gt2krimijvw.html

[U83] JS：ES Module 导入导出
来源：http://dali.meibo888.top/Article/details/gt2hfsgaugt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gt2mvjusody.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gt2epzbeecr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gt2iypbjihy.html

[U85] JS：可选链
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zllzxqwn.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gt2oduysqsy.html

[U86] JS：空值合并
来源：http://dali.xziqi.cn/Article/details/gt2onshddqm.html

a ?? b
来源：http://dali.smart0.xyz/Article/details/gt2twpcrsjr.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gt2bdxwplxp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gt2oikuonzb.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gt2oybaeija.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gt2jjkwelzo.html

[U89] JS：数组去重
来源：http://dali.nanxuanxn.top/Article/details/gt2paxucvon.html

[...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2pttwjiyk.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gt2mmpeodzs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2kfgmisnm.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2xwkwalmn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gt2zrlfgbgw.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2walfgcbi.html

structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2mabehpfl.html

[U93] JS：模板字符串
来源：http://dali.zhixingplan.top/Article/details/gt2vccudaqi.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gt2twwjceeu.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2anoouord.html

const double = x => x * 2;
来源：http://dali.fzhhl.top/Article/details/gt2ahoxxmvs.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gt2ruxuqdxz.html

new Promise((resolve, reject) => {})
来源：http://dali.ydzc1.top/Article/details/gt2ujgzxpzf.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gt2jgyhgzwl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqechmrx.html

[U97] JS：并发请求
来源：http://dali.cashguo.top/Article/details/gt2atnqxcwi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2utykaixd.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gt2hdsfeduk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xinyue.icu/Article/details/gt2gqxtcnrn.html

[U99] JS：事件监听
来源：http://dali.svipenyu.cn/Article/details/gt2qjmpunxd.html

el.addEventListener("click", e => {})
来源：http://dali.sweek.top/Article/details/gt2erlwvrcz.html

[U100] JS：DOM 查询
来源：http://dali.yangfankeji.com/Article/details/gt2wobfhfyk.html

document.querySelector(".item")
来源：http://dali.tian-w.cn/Article/details/gt2jgqwewso.html

[U101] JS：classList 操作
来源：http://dali.cucudq.cn/Article/details/gt2xenmwafv.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gt2wbdupfnv.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gt2dafmgmre.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfcmjrao.html

[U103] JS：定时器
来源：http://dali.jinqigufen.top/Article/details/gt2jcpkhwbq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccpytfvo.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gt2dgmbrkvz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2grfhchrt.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gt2qmowtdjd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2aehqetch.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2sjexmxvg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gt2mcxgnhna.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2emqxeahl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2pzsjvdxu.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gt2maqmqbly.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.havefunace.top/Article/details/gt2qmiyaaat.html

[U109] JS：数组分组
来源：http://dali.gogol.net.cn/Article/details/gt2epbumygt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgpenlyv.html

[U110] JS：数组分块
来源：http://dali.xinyue.icu/Article/details/gt2udqcafev.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gt2cfenxryx.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gt2xsppfpkm.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gt2vwltiokp.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gt2krlogijr.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2ooummgsx.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gt2aarmsbow.html

s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2udpivkhy.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gt2svcxxtag.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gt2enyywqqn.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2liernczk.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2ljocjxgz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gt2mekvmzts.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gt2jbijxqsx.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smqysaod.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gt2wglksoir.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gt2cssxjrzm.html

npm i -D vite;  npx vite
来源：http://dali.guannengcc.top/Article/details/gt2zgxjawmv.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gt2zgxodbqm.html

npx vite build
来源：http://dali.zhengqikj.top/Article/details/gt2lfvmcnbx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gt2rekdpemm.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gt2ibqrehxc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2regwtjmh.html

统计汇总
来源：http://dali.zhongyouzk.top/Article/details/gt2nzzjdypp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ysqszpzv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2buhskvfv.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gt2ewrzjryl.html

PHP ............ 252
来源：http://dali.yangfankeji.com/Article/details/gt2zhziibuo.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2suitefty.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2gotktvhk.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gt2oawnudna.html

Go ............. 212
来源：http://dali.nwbrower.top/Article/details/gt2tbhbkgkc.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2fzblofep.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gt2yrjmpzsi.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gt2bmcahmry.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gt2qzrcqigk.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcisrvrr.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gt2vguwldzl.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2qrgavnsr.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gt2mysrtgee.html

Lua ............ 10
来源：http://dali.yongpay.top/Article/details/gt2ufyznttu.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gt2epigcmaa.html


<!-- 参考信息 -->