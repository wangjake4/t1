代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkigcqns.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gthrknhcmq.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gtiknrgkuo.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtgzuwlhwb.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtetkiouyx.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnbhxvlq.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gttsbzqics.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gthtmnvrvw.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gtilxwwcog.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtpcrrclye.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gtyjwzeydf.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenhuenjj.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtcyabwzdy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtoinnmovs.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtxzavquys.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gtwezwgwjl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtqnnanofv.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gteshcdzhu.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtpvirdlnn.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsrwiuvt.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtiaccvwba.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtlwxsdtst.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtqutmwxsv.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gtrckmlzvf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtkaszcwji.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtcqzatfpq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gtgqcnnjrw.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtckcnllct.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtadvkfial.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtqkrmhtah.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtvrpnqaky.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtgqtltefa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshnhjxfq.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtbwyumolk.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtxsdoxjjb.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtglmcdphj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtsmcvocnv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcgjoakss.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtgoynjkue.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtidxiaedw.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtkcjtwouu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtmbokjhty.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtjmvqwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtdkxbqwnl.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtxfaevmwh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gtnzmtzndy.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtafxljnyj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gttviekocj.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gtcjswnxxt.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtuxztexqw.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtungtkomm.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtegrvkkff.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtmxfoanti.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtshbvjcnl.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtnokqbqmd.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtlqitkeby.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtwngyksiw.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtjilhysbu.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtmjfmcxpk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhiwuduotai.top/Article/details/gtkhbjsajr.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gtvjedenix.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtpfeukzoc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtctmgyuat.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtnsgdzlip.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gtzeyrhxsd.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtiddmxvyt.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gtmvdfzsuy.html

defaultdict(list)
来源：http://dali.xziqi.cn/Article/details/gtxxvxydie.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtijahgdrs.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gtecviwohj.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gtubdumuyr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gtcjyoiopf.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gtntdaaenf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtixeubjap.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtnopbrbzi.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gthfzltnli.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtzzucthue.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gtyadpzwyi.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gtzbhadgyp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gthsaybpqj.html

[U21] Py：自定义上下文管理器
来源：http://dali.birdmap.top/Article/details/gtephubkfg.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtnqnxxwlr.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gtfvxxcyen.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtflbdqbiv.html

[U23] Py：分块读取大文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtrhszja.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gtlivoohdt.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gtnnmlwwyl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrkadqhh.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtmawpibsc.html

csv.DictReader(f)
来源：http://dali.zhoulong.xyz/Article/details/gtwdtylord.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gtmjerxvbp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sufxvd.cn/Article/details/gtqlrtuiif.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtfexbfxnv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gtshqevqwa.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gthpiuxhea.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtfobksjwq.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gtgidhimhh.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gttaepuqlf.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtfaqcrzgs.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gtrsrageve.html

[U31] Py：单测
来源：http://dali.gotoacloud.top/Article/details/gtrikgfitc.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtekpkzdoe.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtanyhzapw.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkucwvyvh.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtzgdyejmt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gtcktzbomf.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtaikdazda.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gthgmymscd.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gtaazvfpmf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtapewjjuu.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gtjtnxewoo.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtdnoklftc.html

[U37] Py：读写 Excel
来源：http://dali.zdqjudy.top/Article/details/gtqhzddmxp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtrsmenbdd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gtrqtiqlig.html

Path(__file__).resolve().parent
来源：http://dali.hongshengwenyu.top/Article/details/gtwtizbmgx.html

[U39] Py：判断是否在交互环境
来源：http://dali.cucudq.cn/Article/details/gtjknqzohb.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtgyanricy.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtrfbaviiz.html

print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtnuvtxucr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.316326.xyz/Article/details/gtigzefuim.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtagihmrpc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxuanxn.top/Article/details/gtpfuysmev.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gtahiswuly.html

[U43] PHP：声明命名空间
来源：http://dali.tanke756.top/Article/details/gtwpnkpcyv.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtdhnaelpp.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gtpjlkvbic.html

declare(strict_types=1);
来源：http://dali.pengpengdd.cyou/Article/details/gtyjoppqeg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuanzx.com/Article/details/gtmtvolqdu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtqburpvjr.html

[U46] PHP：可空类型
来源：http://dali.jinqigfzy.top/Article/details/gtuamjwtlu.html

?string $name = null
来源：http://dali.vqdsnc.cn/Article/details/gtihxgxhle.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzshpfkq.html

int|string $id
来源：http://dali.feifeiyinyue.top/Article/details/gtitycmpqv.html

[U48] PHP：纯枚举
来源：http://dali.quarkkingdee.top/Article/details/gtnbogpzfi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258888.top/Article/details/gtrkwpdzdw.html

[U49] PHP：只读属性
来源：http://dali.zhixingplan.top/Article/details/gtrtysmpog.html

public readonly string $name
来源：http://dali.nanxuanxn.top/Article/details/gtycaeknkl.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gtpoqzbxyz.html

public function __construct(private int $id) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwrxcsijt.html

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gtmjvoqdok.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gtdfsiukdq.html

[U52] PHP：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtzxfbqvtp.html

$double = fn($x) => $x * 2;
来源：http://dali.aizwys.cn/Article/details/gtpvumaokx.html

[U53] PHP：空合并运算符
来源：http://dali.nanxuanxn.top/Article/details/gtqtflkdhp.html

$v = $a ?? $b ?? "default";
来源：http://dali.snrcjt.cn/Article/details/gtjsawjrlx.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gthglinqna.html

$obj?->method()
来源：http://dali.xylfe.cn/Article/details/gtjzoygtem.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gtyyojipqw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.smart0.xyz/Article/details/gtmtgncplp.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gtmkmkthcy.html

f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtuebhrzga.html

[U57] PHP：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtuwurffot.html

"值: {$a}"
来源：http://dali.iojbl.cn/Article/details/gtrkrspycd.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtofgktssa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guannengcc.top/Article/details/gteucosayy.html

[U59] PHP：自定义排序
来源：http://dali.wangdashe.top/Article/details/gtognfzaqq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtfllpncht.html

[U60] PHP：JSON 编解码
来源：http://dali.hywenlv.cn/Article/details/gtcoqzjjmj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gtjrlammup.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gtoqppkbno.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gttvwqahaj.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gtwykguwkv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gtifydtetj.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gtvsxgayac.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtptglatgi.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtkxrmhoci.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gtdtvamwxa.html

[U65] PHP：会话
来源：http://dali.gzhubu.top/Article/details/gtldhhlcrs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtkragtcyg.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258.top/Article/details/gtrpbyagfh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.316326.xyz/Article/details/gtlbcytbnk.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtrdvlvk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gtocelyowk.html

[U68] PHP：PDO 连接
来源：http://dali.guowangkeji.top/Article/details/gtoyrcyxyw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenjidiqi.icu/Article/details/gtieuuduol.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtonklwhfg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.birdmap.top/Article/details/gtypxybzdg.html

[U70] PHP：PDO 事务
来源：http://dali.316326.xyz/Article/details/gtwkxvotax.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenjidiqi.icu/Article/details/gtwpjlhwjz.html

[U71] PHP：抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtsnarkmyf.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtsixzwnmz.html

[U72] PHP：写错误日志
来源：http://dali.ydzc1.top/Article/details/gtrawbfold.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fengsongda.top/Article/details/gtqfckjups.html

[U73] PHP：读取 ini 配置
来源：http://dali.sweek.top/Article/details/gtztbvordn.html

parse_ini_file("config.ini", true)
来源：http://dali.nwbrower.top/Article/details/gtuzsxipcp.html

[U74] PHP：读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtivricvgx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sweek.top/Article/details/gtfzywsnyp.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gtjbxqnbrj.html

composer require psr/container
来源：http://dali.aibaodan.cn/Article/details/gtaczhrgom.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gtqcpxzqsg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ehwqpu.com/Article/details/gtesnepuey.html

[U77] PHP：模板渲染
来源：http://dali.hammf.cn/Article/details/gtvsshirgj.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gtsdpvtckw.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowcikhib.html

composer require --dev phpunit/phpunit
来源：http://dali.xuetiantiany.cn/Article/details/gtgbwskqse.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gtrmeutyoi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtqpqsyxnp.html

[U80] PHP：代码规范修复
来源：http://dali.ivvv.top/Article/details/gtgyvlpaax.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtfolbvkdc.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtghffblln.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gtkerjxjvd.html

[U82] JS：package.json 脚本
来源：http://dali.haohaochexian.top/Article/details/gtikihwdqx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xinyue.icu/Article/details/gtpbabmhlg.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtplfhjxpp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtbibncffl.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gtpbzhbccj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gtqzeuibmh.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gttwyiwcha.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtotxxqtzk.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gtcjdehytb.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gtsxdoemxr.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gtyuzwofpx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuanzhike.top/Article/details/gtmqdsolhu.html

[U88] JS：对象展开合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtteyjfiwm.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtnjununci.html

[U89] JS：数组去重
来源：http://dali.9152youxi.cn/Article/details/gtrrmysnhw.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gthsxosdei.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtogclxcpd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtzgvunlpk.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gtinatzrxe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gtkyeyoasz.html

[U92] JS：深拷贝
来源：http://dali.ehwqpu.com/Article/details/gtkjmkmrtd.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtueiyplsx.html

[U93] JS：模板字符串
来源：http://dali.cheryme.top/Article/details/gtkmxwmlym.html

`共 ${n} 条`
来源：http://dali.hfpthk.cn/Article/details/gtaqzfiuyn.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtzgdsxcop.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtvdiupsze.html

[U95] JS：Promise 包装
来源：http://dali.nwbrower.top/Article/details/gthsahiaet.html

new Promise((resolve, reject) => {})
来源：http://dali.yuanzhike.top/Article/details/gtmzcwcqnx.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gtdisipeqp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtrkjypasq.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtophwbfzp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtqwgkccag.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtbbeibiin.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhengqikj.top/Article/details/gtxjhhivrg.html

[U99] JS：事件监听
来源：http://dali.cqqwz.cn/Article/details/gtdbyaucbk.html

el.addEventListener("click", e => {})
来源：http://dali.wangdashe.top/Article/details/gtrlstxtpi.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gtjyuetnas.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtiaegyfxi.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtudsxomoa.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtdrdosxuo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gtjsvhqiwx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigufen.top/Article/details/gtujmhxywz.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gtoquiovaw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gttyomnidj.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtdzesfsrx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtpirlougp.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gtvtmodkei.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gtujttxjlf.html

[U106] JS：日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpgkxirv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtptacldwi.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtgzujdcuo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtrsuntqls.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gtxsgivjme.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gtwrrsvlaz.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gtvyqficri.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtfpgkevsa.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gtijtresoz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gtwjwtoltl.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gtvtshccwq.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gttlsgnxvg.html

[U112] JS：字符串补位
来源：http://dali.vqdsnc.cn/Article/details/gtxwphzkli.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtqruwiscd.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtmcxnyedx.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtcpthymls.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gtkvaylgvo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtnwvzrrae.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtfvrslynp.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsdyrqfo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzifpzuo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gtnwkvkvyy.html

[U117] JS：单元测试
来源：http://dali.iojbl.cn/Article/details/gttxygwkex.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gtkogdholn.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gtrcyzpxfu.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtigprwisz.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gtyfyflecp.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gtvtpqazah.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gtstbaoasj.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangtech.top/Article/details/gtujvkvajk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpsuxvsan.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtjtngyklp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvjwywpjn.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtirjfnjec.html

Python ......... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtevxmcpkj.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtoshglowf.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gtbhxudnib.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gtxpueqcoh.html

Java ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtpywspuvd.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtceucgzzl.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtjqgpmrrr.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtpqndxvpo.html

C .............. 30
来源：http://dali.sweek.top/Article/details/gtcildwdvb.html

C++ ............ 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqemmcufh.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtrewqzkzd.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gtqzauauco.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gtfdedhsnk.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtkcdbazmq.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtnqzctbqp.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gtyghafazj.html


<!-- 参考信息 -->