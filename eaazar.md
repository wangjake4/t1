代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2pfqcrwms.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2puknneyq.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gt2anjgqcyu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gt2eiuhvaao.html

[T47] Perl：正则捕获
来源：http://dali.yj202588.top/Article/details/gt2obwlzhfg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gt2zhwfnjen.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2lkrgdroq.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gt2hjrcecxq.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gt2gjnuxabn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2szkwijxg.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2cjggsruz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daxiang520.top/Article/details/gt2nzfovatn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gt2qfffmlps.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2tkgalhmx.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2dswzmsdo.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gt2mswlnpht.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gt2tpqqpluw.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2mmdspern.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2eridkony.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2fywttlby.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gt2cszuroac.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gt2uznnkgft.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2bfqjuwlr.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gt2cezfaeyt.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2esvhrebi.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2mahjwdwo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gt2rvkgejji.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2dvlnlnwn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gt2garfufvp.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gt2ctrafpxd.html

for (i <- 1 to 10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2wptouauo.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbfmvubi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aoufqzvt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rnfexfbo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gt2fixsmidy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2aidxijln.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2fojintnd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gt2paoseqqa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzcrgavc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gt2lpdndwrs.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gt2gldldgmc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gt2popffeyk.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gt2alfnxehd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gt2odgicnrx.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gt2vcqfjgwi.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2anbcpnkn.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gt2bikavrmx.html

{**a, **b}
来源：http://dali.gogol.net.cn/Article/details/gt2ajrztxjg.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gt2vatqhtsc.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2zgxamtcm.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gt2vpejwnpt.html

[y for x in nested for y in x]
来源：http://dali.fzhhl.top/Article/details/gt2lpnhhjjm.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gt2ktphlado.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suwbazfq.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gt2mmtveggr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qiuwrkfw.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gt2fznskwrh.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2oeovcqik.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ehwqpu.com/Article/details/gt2hzsdeukw.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2mjrfyhif.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gt2peuuxdev.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gt2bgrmlutl.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdhsebel.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gt2prpqnnmy.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gt2qcfacyxl.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gt2hqjzktlq.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gt2bixitybk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gt2djjbaqgk.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjzweuca.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gt2dcosunvt.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gt2uxuhbiry.html

pat = re.compile(r"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2bvqkitek.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gt2jfsbrhwh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gt2veuhapzi.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gt2kzypuuix.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gt2fqefvalp.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gt2klovkiil.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gt2hjtuhgxa.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gt2ihnhihln.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gt2ywbklrod.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gt2sciidfgl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gt2ychlulhs.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gt2ymzuhfzz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2wxthepru.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gt2uxosadtg.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gt2rlzftbrd.html

[U26] Py：并发下载
来源：http://dali.shzxlz.cn/Article/details/gt2obyrwzne.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gt2ivcwqqtv.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gt2xwqhabul.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gt2hjtckhtq.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gt2nmfearkf.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gt2mvrsaqzr.html

[U29] Py：属性校验
来源：http://dali.sysykeji.top/Article/details/gt2voozappy.html

@property 与 @x.setter 配合
来源：http://dali.wangshuangyany.cn/Article/details/gt2sltuuprk.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gt2ttngutiu.html

@dataclass(slots=True)
来源：http://dali.yangfankeji.com/Article/details/gt2zcmblvjt.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gt2fsgpaven.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gt2lkugzkca.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2ckbvrclz.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gt2rznqeagt.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gt2osaszwdm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fengsongda.top/Article/details/gt2ynnnsufb.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gt2dtytxkpq.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gt2jfvpxstw.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gt2upnxzuvg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgufenzy.top/Article/details/gt2ucskhsct.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2kebvwnhl.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gt2oytfnnpf.html

[U37] Py：读写 Excel
来源：http://dali.wangshuangyany.cn/Article/details/gt2hckbmkjw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gt2eqamwkui.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anamizyy.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gt2reczjmvx.html

[U39] Py：判断是否在交互环境
来源：http://dali.jiagoushi.top/Article/details/gt2dmgufpbj.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gt2bcatkorb.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gt2rvyhkrnl.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gt2wpnokmdy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gt2gzpmerlb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gt2vwmqldeq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gt2kcohifau.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sufxvd.cn/Article/details/gt2knubbowr.html

[U43] PHP：声明命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2szsrdovu.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gt2cmflwgdo.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gt2dabamlsb.html

declare(strict_types=1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sitcntaj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ybcxt.top/Article/details/gt2vvtuurpq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2dijkuoxc.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gt2cffvypdu.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gt2cznbpqwl.html

[U47] PHP：联合类型
来源：http://dali.cheryme.top/Article/details/gt2dfvettrf.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gt2okujdspr.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gt2cqchvxgm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gt2kdiomquk.html

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gt2pusguzsy.html

public readonly string $name
来源：http://dali.yj20258888.top/Article/details/gt2ibowtmaj.html

[U50] PHP：构造器属性提升
来源：http://dali.chenjidiqi.icu/Article/details/gt2oaojxovc.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gt2josqmkds.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gt2sbluyvxq.html

[$a, $b] = $arr;
来源：http://dali.hammf.cn/Article/details/gt2ydnhhpjt.html

[U52] PHP：箭头函数
来源：http://dali.redwolf501.top/Article/details/gt2hjymbwfw.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gt2aemrrdnh.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gt2urkixouh.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gt2ndhpdqce.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gt2mkngflfg.html

$obj?->method()
来源：http://dali.cqqwz.cn/Article/details/gt2mmfhnffw.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2ihmojpjf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gt2dsljuoso.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gt2jmunmoww.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wkbwvxqj.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2aemufafg.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gt2squldkir.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gt2takrsaad.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2raszgpbr.html

[U59] PHP：自定义排序
来源：http://dali.gogol.net.cn/Article/details/gt2mguvydjs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2wffmisgo.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gt2sgrnwdmj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2hyqoravz.html

[U61] PHP：正则
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkqybapf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdmaqoos.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gt2tdubheko.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gt2tfsljrye.html

[U63] PHP：文件读写
来源：http://dali.fengsongda.top/Article/details/gt2tkasddmj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgdfjcbm.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvlzwvff.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gt2edtglido.html

[U65] PHP：会话
来源：http://dali.dashuyun.cn/Article/details/gt2jrtxjvdi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2mqgqwnsr.html

[U66] PHP：设置 Cookie
来源：http://dali.sweek.top/Article/details/gt2apqixkgg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gt2ljrnrmlg.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gt2pqsrytun.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymakauig.html

[U68] PHP：PDO 连接
来源：http://dali.redwolf501.top/Article/details/gt2iqkhdhjn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhixingplan.top/Article/details/gt2bhrotclf.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2teajfyxa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gt2aphopeyg.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gt2wnvesoal.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pengpengdd.cyou/Article/details/gt2paqcvvdc.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2krfimsez.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gt2hsmhawgk.html

[U72] PHP：写错误日志
来源：http://dali.zhongyouzk.top/Article/details/gt2ehrckabq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gt2ehuifslc.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gt2favxewnh.html

parse_ini_file("config.ini", true)
来源：http://dali.fzhhl.top/Article/details/gt2yyalwaut.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryynwkxa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gt2stvebsiq.html

[U75] PHP：依赖注入
来源：http://dali.cheryme.top/Article/details/gt2jgtyljqk.html

composer require psr/container
来源：http://dali.gaohongyu789.top/Article/details/gt2ekoaezod.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgrfwsug.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gt2xfhltdrm.html

[U77] PHP：模板渲染
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voyvawbe.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gt2calfghyo.html

[U78] PHP：单元测试
来源：http://dali.meibo888.top/Article/details/gt2vquigtxy.html

composer require --dev phpunit/phpunit
来源：http://dali.smart0.xyz/Article/details/gt2ugshxrmc.html

[U79] PHP：静态分析
来源：http://dali.pengpengdd.cyou/Article/details/gt2igogfegs.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxlwzhqa.html

[U80] PHP：代码规范修复
来源：http://dali.yanxiufei.cn/Article/details/gt2kqrkvorz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hysaishi.cn/Article/details/gt2knqudvsz.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gt2rqaorwrq.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gt2wsppxnjd.html

[U82] JS：package.json 脚本
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfwlelrk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfgbxws.html

[U83] JS：ES Module 导入导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fukdebob.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvxnsann.html

[U84] JS：CommonJS 写法
来源：http://dali.zycfv.cn/Article/details/gt2jfsbdpwc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gt2dsvmviyh.html

[U85] JS：可选链
来源：http://dali.cheryme.top/Article/details/gt2cffdqmdm.html

a?.b?.c
来源：http://dali.ppjwa.cn/Article/details/gt2xxwbmgzg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwguhal.html

a ?? b
来源：http://dali.redwolf501.top/Article/details/gt2speyvatk.html

[U87] JS：解构默认值
来源：http://dali.hnqzz.top/Article/details/gt2ntkphbut.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njnaurex.html

[U88] JS：对象展开合并
来源：http://dali.jianghu66.top/Article/details/gt2wxdhqrml.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gt2wdiwhlth.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gt2quahddhq.html

[...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2nalhviqu.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gt2mfngpkek.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2nszyqxvr.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gt2yhaioygx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yonumen.top/Article/details/gt2lmocvpgk.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gt2aytoamqw.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2mncdzdyo.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gt2mrecoovt.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gt2gtldbqck.html

[U94] JS：箭头函数
来源：http://dali.c1oappe.top/Article/details/gt2ysuwvvsl.html

const double = x => x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gt2kllnogla.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gt2jsgfvnby.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gt2qdrpdzmi.html

[U96] JS：async/await 与异常
来源：http://dali.jqgufenzy.top/Article/details/gt2wojxosao.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2fysxtaqr.html

[U97] JS：并发请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovxwbkuz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2dwmrdtlj.html

[U98] JS：fetch 带 JSON
来源：http://dali.daria6918.cn/Article/details/gt2jnyfxwyn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gt2xaoxwdgt.html

[U99] JS：事件监听
来源：http://dali.shuidangran.top/Article/details/gt2ugnonuge.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqxafftq.html

[U100] JS：DOM 查询
来源：http://dali.cqqwz.cn/Article/details/gt2srwkakjc.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gt2ubfbunal.html

[U101] JS：classList 操作
来源：http://dali.nwbrower.top/Article/details/gt2ypjwuzgr.html

el.classList.toggle("active")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsreclmr.html

[U102] JS：本地存储
来源：http://dali.cashguo.top/Article/details/gt2djczgawu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gt2rxawxyyi.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gt2efkdybja.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmlcxzkg.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gt2chsesrjh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2fabwhtft.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gt2zwpglukq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2ovsobykr.html

[U106] JS：日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2aabgkgbt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gt2czuybjlv.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2xbidoqwo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2rjgrtyxl.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gt2xrymydaa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gt2govodeun.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gt2umexrbrx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2qvvvptcn.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gt2qszgcymx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gt2rerihvzw.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gt2rorqrqfn.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gt2wpeinpyk.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gt2zrjdpsbr.html

"7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2hinhfhgm.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gt2vxejpxpm.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2qgqejkae.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gt2dqqtyenf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2axukqumg.html

[U115] JS：生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmegnwhl.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2ldaytdma.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gt2oiycdjrc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gt2opxljqko.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gt2txazmgha.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gt2fdcjdfke.html

[U118] JS：开发服务器
来源：http://dali.ivvv.top/Article/details/gt2tcnywjcw.html

npm i -D vite;  npx vite
来源：http://dali.yonumen.top/Article/details/gt2kbwozrqr.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gt2sdqkpkrq.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gt2rupqkhkt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyphgavw.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gt2wrevjbou.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkohdaom.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gt2cwfryxwd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pitwnjpb.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gt2hfyuavfy.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gt2gezzngpx.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gt2ulsjgxhi.html

JavaScript ..... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhkhuguy.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gt2hxktehbt.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gt2kaobvdzs.html

Go ............. 212
来源：http://dali.hysaishi.cn/Article/details/gt2vsvoldcr.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2hnsooghc.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gt2cdywuerl.html

C .............. 30
来源：http://dali.ydzc1.top/Article/details/gt2ntrrwkul.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gt2mrsinabl.html

SQL ............ 90
来源：http://dali.yueranfly.top/Article/details/gt2oqkdgasg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaxibdq.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gt2gtmzdnuf.html

Swift .......... 15
来源：http://dali.yuxming.cn/Article/details/gt2lmgdhmnm.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcqnedgi.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gt2etynffwl.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gt2yccpugrc.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2wfjcraaa.html

合计 ........... 2106 条
来源：http://dali.aizwys.cn/Article/details/gt2ftryssrk.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gt2cqezvdex.html


<!-- 参考信息 -->