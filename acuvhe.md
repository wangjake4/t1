代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gt2gsulsoet.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gt2bnsvhvwv.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gt2sfcqxbxe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gt2edoxuimo.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gt2bpzsazjp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gt2iyulexda.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gt2dttvlinu.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbplhqip.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gt2avbfexts.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2pllarmlw.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2poqiwrtm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gt2buxtzdmh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzzbtnvf.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2fsniwalb.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2wwjmrvir.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gt2hlsatnmk.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2trzlrhaj.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lydgmgpx.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2wivuzslr.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gt2jxragurl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2rlyrqwtd.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2ifblnjpt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gt2wewwelqg.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gt2zjrsumxj.html

case class User(name: String, age: Int)
来源：http://dali.daria6918.cn/Article/details/gt2hjymslki.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2sccxbdkk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxinkj.top/Article/details/gt2mgzbxnik.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2wsbzwpff.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gt2yrbulmop.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2vyqblsnj.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2qsynwcfh.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gt2dzdjlgat.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gt2sgsecvlk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bztnxqis.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gt2koubvilb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2itzapcps.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdatfwmp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gt2qkuydydp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gt2qpgzgxqd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gt2chcqrdxu.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gt2cobfsllp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2muqohnnv.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2kwdzxjec.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2xffminpt.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfapvpdd.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcbknqqr.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gt2fxwtowap.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gt2ybgqzymu.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gt2tbyvxrwa.html

{v: k for k, v in d.items()}
来源：http://dali.yvedp.cn/Article/details/gt2zjrzivjj.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2dpoyoies.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gt2myrjdptw.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gt2hrtmeqmc.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gt2osruxuno.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gt2yidrfyct.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gt2myuhghvj.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gt2subtpopk.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gt2vvmqtpfl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gt2olvmcpgq.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gt2egmyjggv.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gt2zieowcok.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gt2lyxpjeof.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbpbmwbf.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gt2aohtbzer.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gt2esrhfmzw.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gt2cfhktghq.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gt2ybvsspgg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gt2ufkqubpk.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzsulcgb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gt2xjzqvqdq.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gt2dgwwzjsr.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2vylijnqn.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gt2vaxquftx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gt2zjowalsy.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2xfwpotah.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gt2jhfppjmj.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gt2nbebmjmi.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gt2opmmvofa.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gt2byimhfpi.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gt2lxchrund.html

[U23] Py：分块读取大文件
来源：http://dali.jianghu66.top/Article/details/gt2lehqutye.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gt2qvpdzgch.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtfrnyzx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gt2vqvxagng.html

[U25] Py：CSV 按字典读
来源：http://dali.chenlongwang.top/Article/details/gt2iuwajdyp.html

csv.DictReader(f)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edtiedcx.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gt2gjpiqpex.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gt2buqxewlt.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gt2gyhocwpv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guannengcc.top/Article/details/gt2nxbdjcxe.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gt2jbkoixel.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gt2trbmbabn.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gt2yyrdpihk.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gt2icyggxro.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfhfxemq.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2fgguttcb.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gt2oendlmif.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gt2voljbbqp.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gt2fdxiifsb.html

ruff format . && ruff check --fix .
来源：http://dali.birdmap.top/Article/details/gt2lggotyim.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gt2rgusdnwb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gt2tutqwjun.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gt2vbsfleas.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gt2lruniumc.html

[U35] Py：发送邮件
来源：http://dali.jqgufenzy.top/Article/details/gt2ohjqhuqb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gt2hdjvjlnj.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2lqxrlwqs.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gt2xrqldwxk.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gt2gwaxlcly.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gt2gmftrgvf.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gt2cimgkrej.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gt2vludfzoe.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2uubnwudv.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gt2mqgmbnou.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2icemrvty.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2xokcnxdz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhoulong.xyz/Article/details/gt2othyutjl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aizwys.cn/Article/details/gt2oyzqappy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258.top/Article/details/gt2vxxbyhit.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gt2drlcpgmy.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gt2qrqbapws.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gt2gctyluuc.html

[U44] PHP：开启严格类型
来源：http://dali.snrcjt.cn/Article/details/gt2rromkhts.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gt2ffyqonax.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shuidangran.top/Article/details/gt2ijzkavdk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jjqcppmk.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gt2hezzraul.html

?string $name = null
来源：http://dali.nanxuanxn.top/Article/details/gt2vsrolgwk.html

[U47] PHP：联合类型
来源：http://dali.iojbl.cn/Article/details/gt2yefuvtsu.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gt2orrjdlnx.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2bdkxjtqq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gt2mmeoixsh.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gt2mhrhypmp.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gt2cjiwnzph.html

[U50] PHP：构造器属性提升
来源：http://dali.hywenlv.cn/Article/details/gt2nsxhujmf.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gt2vaigmgic.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gt2dqtvjumz.html

[$a, $b] = $arr;
来源：http://dali.jqgufenzy.top/Article/details/gt2kotrdkwd.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gt2dnzhsggn.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gt2xjcmxzxd.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gt2jwptsgcv.html

$v = $a ?? $b ?? "default";
来源：http://dali.cucudq.cn/Article/details/gt2xqddkxbu.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gt2sdoiazgv.html

$obj?->method()
来源：http://dali.snrcjt.cn/Article/details/gt2obvhvhtz.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2uybjnrda.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwkcwmtd.html

[U56] PHP：命名参数
来源：http://dali.cashguo.top/Article/details/gt2ecusycqm.html

f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2bclbpmwg.html

[U57] PHP：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2nuenqeuy.html

"值: {$a}"
来源：http://dali.gogol.net.cn/Article/details/gt2vtiqfohl.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gt2lmkvpdxt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gt2cfngpcpa.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gt2wyfqpzms.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gt2hhzcaokb.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gt2zopgvqrw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gt2eytfmnly.html

[U61] PHP：正则
来源：http://dali.316326.xyz/Article/details/gt2idvdcqca.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2qvismspq.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gt2lbuimpac.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cqqwz.cn/Article/details/gt2efqudseb.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gt2fngdlnhk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gt2qwxwtmyh.html

[U64] PHP：目录遍历
来源：http://dali.chenzaomai.com/Article/details/gt2aafrsqtk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gt2zuwxustz.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gt2yjdynocv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2bfhifapm.html

[U66] PHP：设置 Cookie
来源：http://dali.meibo888.top/Article/details/gt2eggofiwh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2supylcvu.html

[U67] PHP：处理文件上传
来源：http://dali.pycfn.com/Article/details/gt2wvkjaqif.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jffozwjs.html

[U68] PHP：PDO 连接
来源：http://dali.jqgfzy.top/Article/details/gt2fqubgjlw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjpowqup.html

[U69] PHP：PDO 预处理
来源：http://dali.jyoumei.cn/Article/details/gt2lriiymuf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtnagozc.html

[U70] PHP：PDO 事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bscokanm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guowangkeji.top/Article/details/gt2mwqnlyep.html

[U71] PHP：抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2wvltubiw.html

throw new RuntimeException("失败", 500);
来源：http://dali.xinyue.icu/Article/details/gt2atumikfq.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gt2woakebpe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gt2vhaburzv.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gt2nzszmbbl.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgufenzy.top/Article/details/gt2ktxiftft.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2tllgmgvw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gt2dcfwoqid.html

[U75] PHP：依赖注入
来源：http://dali.cdnleiting.top/Article/details/gt2zqymnhbn.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gt2nwzphsjd.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gt2tbvajfjj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gt2stazzpuc.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gt2xcsbmkxu.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gt2gdffeiba.html

[U78] PHP：单元测试
来源：http://dali.cashguo.top/Article/details/gt2dmrkqbyq.html

composer require --dev phpunit/phpunit
来源：http://dali.snrcjt.cn/Article/details/gt2qpxquzre.html

[U79] PHP：静态分析
来源：http://dali.c1oappe.top/Article/details/gt2mppddypc.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gt2konwwwhg.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gt2bepueisy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gt2jbvlunoo.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gt2zvucknyk.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idbwcewo.html

[U82] JS：package.json 脚本
来源：http://dali.bjfxy.top/Article/details/gt2vujflxpz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gt2rxlfhzuk.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuxming.cn/Article/details/gt2egpfxlqz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gt2geitxocd.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gt2ptqrmosh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sysykeji.top/Article/details/gt2vapicfog.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gt2wizzfale.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gt2dachcfpy.html

[U86] JS：空值合并
来源：http://dali.ydzc1.top/Article/details/gt2xuzdbzma.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gt2ohisemnx.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gt2njakpjal.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shuidangran.top/Article/details/gt2fbtfzjxk.html

[U88] JS：对象展开合并
来源：http://dali.zhengqikj.top/Article/details/gt2ltnaebci.html

{ ...a, ...b }
来源：http://dali.zhoulong.xyz/Article/details/gt2rydwluiv.html

[U89] JS：数组去重
来源：http://dali.yueranfly.top/Article/details/gt2oplkghwi.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2omtkxxaq.html

[U90] JS：数字数组排序
来源：http://dali.tanke756.top/Article/details/gt2rixnjahp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2kipsiwdl.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gt2hmkuufit.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gt2vnnfyjfs.html

[U92] JS：深拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2gjetdslw.html

structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2jfkauwkn.html

[U93] JS：模板字符串
来源：http://dali.ydzc1.top/Article/details/gt2ccgigwgp.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gt2hvlshadq.html

[U94] JS：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gt2ztyhgmkf.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbhhjutf.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gt2lzgghrdn.html

new Promise((resolve, reject) => {})
来源：http://dali.yangfankeji.com/Article/details/gt2vsidkcex.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gt2myoezjcg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2evhjixpw.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gt2qejxrnsg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blmakmrv.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2obsfglfi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gt2dfbmiuyg.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gt2oyrfbrnh.html

el.addEventListener("click", e => {})
来源：http://dali.hammf.cn/Article/details/gt2dqymlijn.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gt2dkieuugs.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gt2cofmouql.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gt2vckzayec.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gt2qgwovzvy.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gt2chzpsgnf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gt2gzmfppfw.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gt2qhkhmggm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gt2vdujtibo.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gt2phjsvlgn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2jyzudncl.html

[U105] JS：节流
来源：http://dali.guowangkeji.top/Article/details/gt2yfbkujcg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gt2dhuavtxi.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2gwzhxfwo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gt2wavbbbmn.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2znxspclb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkabafyj.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gt2pabmxyli.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gt2jqpqrebh.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gt2gzafgmpx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2sodrrcpu.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfqtntwu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gt2ofbftmhs.html

[U111] JS：对象转 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2ovpeeanl.html

new Map(Object.entries(obj))
来源：http://dali.daria6918.cn/Article/details/gt2goprhmzy.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gt2dqgztfql.html

"7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbhpaoyc.html

[U113] JS：正则替换全部
来源：http://dali.iojbl.cn/Article/details/gt2nxuzyswi.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2ljieuurj.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gt2egzucvxs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gt2dzqgafdo.html

[U115] JS：生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gt2cfoqgorr.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgmjwofd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gt2wszqosyc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gt2khtyadvd.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gt2qaugklkh.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gt2jdzsmbym.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gt2emqojpvb.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gt2kabtfyjt.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gt2fmiukeck.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gt2xsbqscvs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2ptqeuhqv.html

import.meta.env.VITE_API_URL
来源：http://dali.yj202588.top/Article/details/gt2pvztbzgn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2yehlqshf.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gt2namnznqy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2kwjqdsyq.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gt2jjowrkzu.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gt2zuwqwbjp.html

PHP ............ 252
来源：http://dali.jinqigufen.top/Article/details/gt2zdikyexk.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gt2ayzaubce.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gt2bhwcyiqa.html

Java ........... 212
来源：http://dali.zycfv.cn/Article/details/gt2loxhzhwv.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2wlpvdmvq.html

Ruby ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcrckczw.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2xlpxpnog.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gt2bprrnesz.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gt2uxoabcbr.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gt2xaiejyis.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gt2vumzuxnp.html

Kotlin ......... 15
来源：http://dali.wangdashe.top/Article/details/gt2youmdttz.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gt2xogzzytw.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gt2xuffpxfr.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gt2mfdnjekv.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gt2hrtgqrhv.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2gcknqnzx.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gt2eggqmetp.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gt2bfuzxulr.html


<!-- 参考信息 -->