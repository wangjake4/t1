代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtnaqdxnkd.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtafptokxc.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtrmazclpz.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtiqwidgpk.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtetrogioh.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gthgnavklh.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gtcjhnkddi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjilrxehu.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtaarmsoxv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxyzibtc.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gtsdxaoflj.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtdusguifg.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtslyczewo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtcnhmgshh.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtomdteqdd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtmdyftbqh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteloyqzws.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtzkktalja.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtdzrtongw.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtbzsbcado.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gtfugbfjlt.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtvhyjjnoa.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtevswzmie.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtaccikaxn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthonfmxre.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtinxhgbgq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtuwveljnb.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gtmrrrefvz.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gtphvnkjvs.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gthtnlmlxv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfumrijil.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gtzwzpsbmh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gthatsvhvb.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtkgcqtuli.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdrwstbw.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtlsvruabh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtqlpvdcsd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtaecewqpn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtbjcncuda.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpbznmsio.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtzljgkjfq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtqyqcubuo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtguyimxvj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtvhnwbjqs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtzvgcfxfc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtexrrhcpo.html

[U04] Py：变量调试打印
来源：http://dali.cdnleiting.top/Article/details/gtxifimtms.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gtbfzdvbhh.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gtjopvawub.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtyhgjhpga.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtaatosfcg.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtbawhiqzw.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtahwmiizm.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtjfzvqvbr.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtzbutcagh.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gtjrvtcxix.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtkmsdnhqe.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gtrkjogbhj.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtvjangliq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtxdkvefav.html

[U11] Py：生成器表达式
来源：http://dali.havefunace.top/Article/details/gttkzsvahy.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtiaqkgznx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtcabdtelg.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gtqabcaqos.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gtgtdxxhxy.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gteigubqwz.html

[U14] Py：分组收集到列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabgidckd.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtlxkmljyk.html

[U15] Py：高精度计时
来源：http://dali.kuanghao11.cn/Article/details/gtpwikoexl.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtxaivinxr.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gtlejgcnqy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gtkzrbgumk.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gtainlxddv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gtuxsxvqva.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtyrxusvki.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtclcknhmi.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqwivkvr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gtvlnzcsjy.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtcfivtlll.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenlongwang.top/Article/details/gtcvscijly.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gtpnrxjofz.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gtipktgncy.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gttyudppzu.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtjhdnrcrb.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtcqrpykcg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258.top/Article/details/gteemloumf.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gtwytxeywy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtaonrcjon.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gtdaxfadqs.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gtlyzozxac.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gtvfdyuinn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsapzaah.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gttaofiojl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gttbzadybl.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfxqplnb.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gtcbigyvgr.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gtltqhrzwd.html

@property 与 @x.setter 配合
来源：http://dali.gogol.net.cn/Article/details/gtlnaloobw.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gtnubdzknt.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gtvjszlikj.html

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexwtmkob.html

python -m pytest -q
来源：http://dali.snrcjt.cn/Article/details/gthgdihnll.html

[U32] Py：代码格式化
来源：http://dali.0kj1m.cn/Article/details/gtsfpywcjw.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gtsbtdygua.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gtrblzyspe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gteknwguaa.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtrrlgkhyh.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gtlhwolmdw.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtmqltvrhm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yvedp.cn/Article/details/gtsyvzlsrp.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtyyectapr.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gtkibivtva.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gtpnagforu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gogol.net.cn/Article/details/gtpmwsmpbr.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gteafpgfhv.html

Path(__file__).resolve().parent
来源：http://dali.hongshengwenyu.top/Article/details/gthmonjcvl.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gttleijgfz.html

sys.stdout.isatty()
来源：http://dali.gzhubu.top/Article/details/gtbnjwkcqr.html

[U40] Py：打印到标准错误
来源：http://dali.quarkkingdee.top/Article/details/gtexedlutb.html

print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtdpsnecpd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yvedp.cn/Article/details/gtdbawmbik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yongpay.top/Article/details/gtxdthmxjv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgfzy.top/Article/details/gtaidqcqsw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hywenlv.cn/Article/details/gtlkgdsyrr.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtwgxlwero.html

namespace App\Http;
来源：http://dali.gaohongyu789.top/Article/details/gttpezglub.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gtmbjfozqo.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gteabrmqtj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohkarket.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtlykgxfcs.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtclmdagdc.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gtddladxuv.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpsnlwsc.html

int|string $id
来源：http://dali.cheryme.top/Article/details/gtapmnxtjd.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gtpgimudqy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dianchejie.cn/Article/details/gtfnpxgcbb.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gtorutdvli.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtcrkmqmns.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtuvjgourn.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gtugrjvtga.html

[U51] PHP：数组解构
来源：http://dali.yuxming.cn/Article/details/gtzwuxqnli.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gtmppworzz.html

[U52] PHP：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtyjfrtrpr.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gtcrvswxps.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gtltdompiq.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gtfsdzovft.html

[U54] PHP：空安全调用
来源：http://dali.hammf.cn/Article/details/gtkwfaxztt.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gtgyuvaiav.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gtjwjzzxzg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteiujqxk.html

[U56] PHP：命名参数
来源：http://dali.0kj1m.cn/Article/details/gtduepvkva.html

f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gteogpbbdl.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtmjuejmbi.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtqkihbhhy.html

[U58] PHP：数组三件套
来源：http://dali.xuanzx.com/Article/details/gtomqjltrk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtyuhatvns.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtpymqtidu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtsjtufzuh.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gtszdrorvz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtzhqzmkhm.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gtjynhcwcd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtvujqvmgf.html

[U62] PHP：日期对象
来源：http://dali.hnqzz.top/Article/details/gtolvuiccx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gtausmjqct.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtxjrjnhya.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.c1oappe.top/Article/details/gttytrsluz.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gthyqoldlk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilxsmasp.html

[U65] PHP：会话
来源：http://dali.yvedp.cn/Article/details/gtpeczhbio.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtzqktkgih.html

[U66] PHP：设置 Cookie
来源：http://dali.ybcxt.top/Article/details/gtrjehzckk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtnpwvpfgo.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtkdjqazxu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtcggkooqb.html

[U68] PHP：PDO 连接
来源：http://dali.yj202588.top/Article/details/gtovwhkbgo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuanzx.com/Article/details/gtxtrgrfeb.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacooyoqe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gtcpuioqcs.html

[U70] PHP：PDO 事务
来源：http://dali.ehwqpu.com/Article/details/gthkcyebtp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jlsjyb.cn/Article/details/gtronefnip.html

[U71] PHP：抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtbhnjeoqn.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gtltbjzvpa.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwtfcuen.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nanxinkj.top/Article/details/gtyuezpdbb.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gtvakhuzgl.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvdcypqd.html

[U74] PHP：读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtywcwxrwi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gtbqwdzejv.html

[U75] PHP：依赖注入
来源：http://dali.aizwys.cn/Article/details/gttdukvkxr.html

composer require psr/container
来源：http://dali.jlsjyb.cn/Article/details/gtfbvzyrgc.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gtgytdbdks.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtzjektjpu.html

[U77] PHP：模板渲染
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmuxtjjf.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtbbrcnrgq.html

[U78] PHP：单元测试
来源：http://dali.yvedp.cn/Article/details/gtjfqqnxsv.html

composer require --dev phpunit/phpunit
来源：http://dali.mhx1999.top/Article/details/gtquqiekfv.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gtghkkuccs.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gtgzveufiy.html

[U80] PHP：代码规范修复
来源：http://dali.zhoulong.xyz/Article/details/gtonqcornv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ivvv.top/Article/details/gtocstszst.html

[U81] JS：初始化项目
来源：http://dali.gzhubu.top/Article/details/gtodjmyzsf.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gtmgrbdbzi.html

[U82] JS：package.json 脚本
来源：http://dali.yueranfly.top/Article/details/gtyvilksoq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuxming.cn/Article/details/gtdobzomsb.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gtdsnngzen.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtxbexmoou.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgufenzy.top/Article/details/gtezpuaffu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guowangkeji.top/Article/details/gtpxauejzq.html

[U85] JS：可选链
来源：http://dali.iojbl.cn/Article/details/gtlbvdmbno.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtzkrerw.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtdkihicfv.html

a ?? b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwgbrtpx.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gtetazrhqj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shuidangran.top/Article/details/gtpqtykxfe.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gtjpzmzhoz.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gtlspffmzv.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gtrhcodfbb.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gttyrmodyx.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gtzpwunpfk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtytjegppv.html

[U91] JS：对象键值遍历
来源：http://dali.smart0.xyz/Article/details/gtosavazqz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtgcjemmwf.html

[U92] JS：深拷贝
来源：http://dali.andypj.xyz/Article/details/gtfzrlbxvl.html

structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtejpzwwhu.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gtcnxergvk.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gthmsrmflp.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtbbyboanu.html

const double = x => x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtxwwovtmr.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gthhshhrur.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmospetg.html

[U96] JS：async/await 与异常
来源：http://dali.havefunace.top/Article/details/gtdglctkyr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtiihrbrfm.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gtjxdplgnf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtdkhkzpmj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gtayasllbw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cheryme.top/Article/details/gtjfozzbyq.html

[U99] JS：事件监听
来源：http://dali.yuanzhike.top/Article/details/gteucudfoq.html

el.addEventListener("click", e => {})
来源：http://dali.shzxlz.cn/Article/details/gtwahddrsx.html

[U100] JS：DOM 查询
来源：http://dali.yuxming.cn/Article/details/gtrhhnxfpr.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gtzvyvqhwl.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gtkphhctht.html

el.classList.toggle("active")
来源：http://dali.jlsjyb.cn/Article/details/gtimqdtaif.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gttjtkclqq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gtqlvenkaz.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gtxbecrmdj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtfjiqbbsf.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gtgbhcakpz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtfdvevihr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtdptqukss.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cheryme.top/Article/details/gtulgkajya.html

[U106] JS：日期格式化
来源：http://dali.guannengcc.top/Article/details/gtzbzlmlwt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gtkbjbehab.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gthpakhpfo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtzqavejyc.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikzzdfqk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gthlzsuusi.html

[U109] JS：数组分组
来源：http://dali.zhongyouzk.top/Article/details/gtfopqrwjd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtnzmwxdsm.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtkdkafvwb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtvsdoytcp.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtrborsqmo.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtdethdlyr.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtpiagyhhi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtbnmkqolm.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gtxgzabors.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtqjxjtsas.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gtlbtagype.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmayurpdm.html

[U115] JS：生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtywmauqen.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtvtxcvhpz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyhdcahc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gtmyxagogf.html

[U117] JS：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gttxgckcyn.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtmkoabfmo.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gtizpglzry.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtujdifthd.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gtzrsoroaf.html

npx vite build
来源：http://dali.yj202588.top/Article/details/gtmrgssatj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gtrdfawqgr.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gtcpubhyzm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdnxmsadv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtlddxjwsw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtspyvfvxq.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtjsvnjqwp.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gtnsrguxbs.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gtzbgrguqc.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gttqdunijy.html

TypeScript ..... 212
来源：http://dali.meibo888.top/Article/details/gtcnhnjesy.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gtjrhwijnn.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gttfkrwctk.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gtrtrjxzck.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gtjikpgddq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gtryvwosmf.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gtqvqrnlnc.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtwldnyhab.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gtuxxonbau.html

Kotlin ......... 15
来源：http://dali.redwolf501.top/Article/details/gttjgeblpt.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtnroxiiuj.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gtebscvivt.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtwbqiydaz.html


<!-- 参考信息 -->