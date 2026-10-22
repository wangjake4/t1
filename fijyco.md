代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gt2xmiusjdz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gt2ickqxxdg.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gt2qwmahvjl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2etttsscu.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gt2drhyzaws.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gt2yxcixxdx.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gt2ukgpthxa.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gt2rakylgrq.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gt2pufurxqz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2axeepmqf.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2bvllmooh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gt2hjzpghtq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2chtqosms.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2vqhhhdpl.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2rydsxntu.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gt2jhrdfdcl.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhulhgzh.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2edkmvcyw.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqnhnvkc.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2oonlkdca.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqvnlxrd.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2kxkhxdkf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gt2xbuzyzbl.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gt2klikicac.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gt2klqmdjip.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2ncekmrbm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gt2xuvcbdrd.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gt2uwqnfqza.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2npwanygo.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gt2ukyqwfcp.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2stoibxty.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gt2mzndgfyv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gt2yjyleqva.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qvxxursa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2jvyyovcw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2xcpeitra.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2otuhqemd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odewclvr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymxykypq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gt2jmolxcxa.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gt2ioxtacvr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2rydursvr.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gt2wriaylpp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gt2fvjrhcbp.html

[U05] Py：列表去重且保序
来源：http://dali.jqgufenzy.top/Article/details/gt2onhjotwl.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2sedbdfcb.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gt2ztvdbbbe.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gt2ytlkynzv.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtomgvig.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gt2vwtyswew.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2xgihdpue.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gt2ohnunzoi.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gt2qicianxd.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gt2ztemubma.html

[U10] Py：按值排序字典
来源：http://dali.jlsjyb.cn/Article/details/gt2hxomrpgr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gt2zpihewwz.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gt2xeyvaewn.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gt2cduzqrwk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gt2uwffzehk.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gt2yrdxhagq.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2lbsxqrcq.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gt2obchlzqz.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gt2jwsyobod.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gt2ghuoywiu.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gt2vapxazdz.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gt2pimvwtyq.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gt2ctxawyiu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gt2ysefinht.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gt2mqbatsfw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2weuhepft.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gt2pbmurrkq.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2stvsbdwn.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gt2lmmxgmqa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxqwcnlb.html

[U20] Py：缓存函数结果
来源：http://dali.bjfxy.top/Article/details/gt2hplohybt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mepmmhya.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gt2zwpqsqgf.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2isijuiiy.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gt2iwmcouhj.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gt2tmhlyszf.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gt2aozkphnh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gt2nqirhszm.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gt2btekjvcj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2csfkdrdb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gt2oirkgclf.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gt2zeelrtne.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gt2vqbzjxbv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rczdgrex.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gt2midtocas.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gt2rofeduzi.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfnlenyi.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gt2aciiaals.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gt2ivceksub.html

@property 与 @x.setter 配合
来源：http://dali.aibaodan.cn/Article/details/gt2drgqraym.html

[U30] Py：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2iqgjlxiu.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gt2aykrdhdk.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gt2bkgzamzq.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gt2nicuklqd.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2qbgortmo.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gt2eopauxqd.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gt2claiaffi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gt2zquxacin.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gt2oeanodkp.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gt2lclddcal.html

[U35] Py：发送邮件
来源：http://dali.fengsongda.top/Article/details/gt2kpplqgzb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gt2veyvorci.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2necxrlhf.html

schedule.every(10).minutes.do(job)
来源：http://dali.guowangkeji.top/Article/details/gt2plklusrr.html

[U37] Py：读写 Excel
来源：http://dali.zhoulong.xyz/Article/details/gt2pfqisias.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2vhcmfgwj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2yeeyquna.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gt2baburnqb.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gt2hpoxgkkx.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gt2giwiumsm.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gt2hprtrnid.html

print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2wsgftaad.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gt2ekwcassv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwqmvxrx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fzhhl.top/Article/details/gt2errgevly.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gt2wrwppmvy.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gt2ohvatjop.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gt2yjpmzzpz.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gt2bhvuzvwq.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gt2gzbjzugp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gzhubu.top/Article/details/gt2vutnrpxa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vqbtaocq.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gt2aidsltio.html

?string $name = null
来源：http://dali.shangyingyoupin.top/Article/details/gt2nduuwgwt.html

[U47] PHP：联合类型
来源：http://dali.chenlongwang.top/Article/details/gt2rcprclhp.html

int|string $id
来源：http://dali.jyoumei.cn/Article/details/gt2fpkgzoui.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gt2wnpidhkm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.haohaochexian.top/Article/details/gt2pjgigexm.html

[U49] PHP：只读属性
来源：http://dali.hammf.cn/Article/details/gt2rkswrhsy.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gt2jfmugobx.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxinkj.top/Article/details/gt2tamexqff.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gt2oaaczrmd.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gt2ycyojecb.html

[$a, $b] = $arr;
来源：http://dali.yj20258.top/Article/details/gt2germobuw.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gt2uicxpsxn.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gt2vezbyjcc.html

[U53] PHP：空合并运算符
来源：http://dali.9152youxi.cn/Article/details/gt2xriszvav.html

$v = $a ?? $b ?? "default";
来源：http://dali.cucudq.cn/Article/details/gt2kprhfwoi.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gt2liwdmjti.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gt2mwljbkxu.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gt2faduxjrd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gt2plfejlbt.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2gbrcartf.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2crcgycnl.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2ztxqhlhh.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gt2iuduqbfk.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gt2unmpbpkb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2wpbpomdr.html

[U59] PHP：自定义排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enetcdri.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2hkroquah.html

[U60] PHP：JSON 编解码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpawuokc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2rxxvhxnh.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovhzawvh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zodgdsfl.html

[U62] PHP：日期对象
来源：http://dali.gzhubu.top/Article/details/gt2akddrska.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcabzebw.html

[U63] PHP：文件读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssdopdyp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hswadczp.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2ekgfiowc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmhccjvd.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gt2ekumifam.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2ruoewkbl.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gt2ntusuosz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.andypj.xyz/Article/details/gt2oavvzsxf.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gt2drjjgvif.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhoulong.xyz/Article/details/gt2uuzljego.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gt2shwuuqwb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gt2tbnhwkcd.html

[U69] PHP：PDO 预处理
来源：http://dali.yuxming.cn/Article/details/gt2ebapxmfi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yangfankeji.com/Article/details/gt2bfwlismr.html

[U70] PHP：PDO 事务
来源：http://dali.aibaodan.cn/Article/details/gt2zfgftdfd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gt2kzlgccxg.html

[U71] PHP：抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2jccjguae.html

throw new RuntimeException("失败", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2bcyvbfoo.html

[U72] PHP：写错误日志
来源：http://dali.shuidangran.top/Article/details/gt2pvzmxajj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntzmlcqz.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenlongwang.top/Article/details/gt2afukznzb.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gt2yarpihxn.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2krpilije.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ehwqpu.com/Article/details/gt2raaduxzj.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcdqjmne.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gt2kcuzobzo.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gt2zqeddtay.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnevitlg.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gt2mhpsrchg.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gt2vfjrwedg.html

[U78] PHP：单元测试
来源：http://dali.iojbl.cn/Article/details/gt2gnwwqzff.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gt2gfryhrwe.html

[U79] PHP：静态分析
来源：http://dali.xuanzx.com/Article/details/gt2unzovdhr.html

composer require --dev phpstan/phpstan
来源：http://dali.ppjwa.cn/Article/details/gt2yrzlpcdk.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gt2wcqhwyjn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhongyouzk.top/Article/details/gt2fszyrrfi.html

[U81] JS：初始化项目
来源：http://dali.iojbl.cn/Article/details/gt2zaqguxhc.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gt2lnhnqyfh.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gt2cuiryhcr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gt2yujjcfgh.html

[U83] JS：ES Module 导入导出
来源：http://dali.guannengcc.top/Article/details/gt2hpsejvyj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gt2ghlsyhnc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybzdxqch.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2loxypsce.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gt2ioooltgh.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gt2qxgqbcro.html

[U86] JS：空值合并
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxoiyaxg.html

a ?? b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ennopxuk.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lneyrkxg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gt2xtyozzrc.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gt2ihamyijm.html

{ ...a, ...b }
来源：http://dali.iojbl.cn/Article/details/gt2eupyutqn.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gt2omhdccnd.html

[...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2jswyvmbl.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gt2ceiohivf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2qinhhteg.html

[U91] JS：对象键值遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2xlrlizkt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gogol.net.cn/Article/details/gt2hefwicyg.html

[U92] JS：深拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2cspdrkku.html

structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2demdjwtr.html

[U93] JS：模板字符串
来源：http://dali.wangdashe.top/Article/details/gt2pqoaecds.html

`共 ${n} 条`
来源：http://dali.shzxlz.cn/Article/details/gt2greainqr.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2owwpiabj.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gt2ioogyfek.html

[U95] JS：Promise 包装
来源：http://dali.cqqwz.cn/Article/details/gt2sjnibwoe.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbhcnlkb.html

[U96] JS：async/await 与异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybsjuhqx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2iodgmysj.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdmflajx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfutpecj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2jupelzek.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gt2skqnoamo.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gt2slbvkyem.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlncpuhh.html

[U100] JS：DOM 查询
来源：http://dali.sweek.top/Article/details/gt2ykqdnhsw.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gt2lfvgutgy.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gt2uaoebqlh.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gt2pitrzjzq.html

[U102] JS：本地存储
来源：http://dali.yj202588.top/Article/details/gt2xiyqdmbc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangshuangyany.cn/Article/details/gt2lehvmlrh.html

[U103] JS：定时器
来源：http://dali.dianchejie.cn/Article/details/gt2bqlagwbb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gt2gaekwjzr.html

[U104] JS：防抖
来源：http://dali.mhx1999.top/Article/details/gt2otohpbek.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnddwudk.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gt2hovmvrii.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gt2ylhnfwvk.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gt2gdjgsple.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gt2szjlkdbo.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2coyclcge.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gt2jayvclre.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2vpfywyxy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gt2xrhnmevn.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gt2girvfeua.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2yynhtsvk.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqmewcqo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gt2hkuoomai.html

[U111] JS：对象转 Map
来源：http://dali.havefunace.top/Article/details/gt2izxnxfba.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gt2pyzoditk.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gt2visbeegu.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2lgfplywf.html

[U113] JS：正则替换全部
来源：http://dali.zhongyouzk.top/Article/details/gt2ehtlsnze.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmmzyorc.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gt2efqxemgq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2gqjjlpxj.html

[U115] JS：生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gt2bkmyjczw.html

crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vazjcndl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sggsrryy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.havefunace.top/Article/details/gt2pwjtbixj.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2njcszhzr.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gt2kwxthhbj.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2poagmuqy.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gt2eqbpkchv.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gt2hupustll.html

npx vite build
来源：http://dali.chenzaomai.com/Article/details/gt2hoskuent.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fzhhl.top/Article/details/gt2pzetvgpq.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gt2qoweimol.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ymnsvdim.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gt2frllmkcs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zvhgntbu.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gt2ueedyncq.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gt2vfjtuvkr.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gt2aqeobaon.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gt2iwredlts.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gt2qfpoetbt.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdzjdujo.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gt2iwnhamae.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2exzerlad.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2rzxcedlb.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gt2mvwkiuaw.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gt2dqigjabu.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gt2vxjpgexp.html

Bash ........... 80
来源：http://dali.cashguo.top/Article/details/gt2oslsfqgt.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gt2fvwojmsf.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2cyqoeehw.html

Lua ............ 10
来源：http://dali.cucudq.cn/Article/details/gt2gnjymfmc.html

Perl ........... 10
来源：http://dali.aizwys.cn/Article/details/gt2zqpiuwlj.html

Scala .......... 10
来源：http://dali.jinqigufen.top/Article/details/gt2kdipvhit.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2alclfxhv.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gt2tpvyothm.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjpzgcfn.html


<!-- 参考信息 -->