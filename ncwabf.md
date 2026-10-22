代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gt2gdkzptlr.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2felrlheu.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gt2jtizmwte.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ceowdenp.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gt2wqafnswr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gt2snhdutnk.html

[T48] Perl：正则替换
来源：http://dali.meibo888.top/Article/details/gt2upjtvhcs.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gt2nacriuak.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gt2jnkwuhdc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2juhzahpi.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2gaktyhef.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gt2yhyihbfw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2huzaejyz.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2dnuxnyzd.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2nkmrqfqb.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gt2slngcmis.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2emeslpwm.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2gxhpwchj.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gt2yyuhyjso.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2qkphbohm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gt2hnxihuql.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2tjokyxvg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gt2hpfljgea.html

[T56] Scala：样例类
来源：http://dali.aizwys.cn/Article/details/gt2uzbuhuiy.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gt2dlgooxnp.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gt2qqmouegy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gt2hsizihwr.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gt2wfbsjszc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewgduzhx.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbubldzb.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gt2ajzedmlt.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gt2unvoqosh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gt2zyydtpwk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2vrkficjo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gt2ulmbbzbn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2gskfawuf.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gt2fxsngvoz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gt2eirmpkwy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gt2xswvpsuk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gt2nysqihxh.html

[U03] Py：加载 .env 配置
来源：http://dali.nwbrower.top/Article/details/gt2ghzaplmr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gt2mnnuvzks.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gt2exbflsvv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2unfiqhdq.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gt2htttykiw.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2plmwnbfa.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gt2kqyzgllp.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gt2vmxdvfbz.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gt2stswoano.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2bmhtufwe.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2jneqxzuy.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gt2tesmccjr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zoarpznx.html

max(d, key=d.get)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkxfobkp.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gt2sxtokrxu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gt2weksxlgm.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gt2vdwdbhbe.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gt2omcaajgb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2hszlvxht.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffkhfarl.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gt2npcrbnlz.html

deque(maxlen=10)
来源：http://dali.daria6918.cn/Article/details/gt2pidaqkkb.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gt2qeunedrp.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gt2kryyuxnm.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gt2gygrtzux.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qepmcqxw.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gt2lbufyhvy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gt2hsizvlpn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2thsvrbif.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gt2rwlasfhb.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gt2vnoumzkg.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2qiiipxht.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gt2kffiniln.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gt2drxlfify.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2rqojxdux.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gt2rzzesogx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gt2nvmwuxxl.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gt2mxtkknkf.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gt2nsivsaka.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gt2lbjujfbb.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gt2grrmccff.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gt2jynawfhe.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsackjqs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2fakunjcf.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gt2aygqddtw.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gt2uqjkogsa.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gt2gkcipxpc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zycfv.cn/Article/details/gt2ropiaisg.html

[U27] Py：异步 HTTP
来源：http://dali.jqgfzy.top/Article/details/gt2inlnsihw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2hviozaxj.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gt2dhlztscw.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gt2dkxfwkmp.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxjrlmwl.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gt2wzvcvqua.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gt2vgglfvvs.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gt2qulkewzg.html

[U31] Py：单测
来源：http://dali.0kj1m.cn/Article/details/gt2cuumyfzh.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2xiompmxj.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gt2fwesbduc.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwfihztg.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gt2eoguxpaj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gt2hvbenlim.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gt2jeobofge.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvvtnqjs.html

[U35] Py：发送邮件
来源：http://dali.sxryk.cn/Article/details/gt2ybwlyhml.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzvvpaks.html

[U36] Py：定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kedslyas.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258.top/Article/details/gt2schcpluj.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gt2axtyzxnp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gt2bclirsgz.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlrnjcem.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gt2wlvhkxfo.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gt2qjykdlbm.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gt2ncavolfm.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gt2zydijona.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2exmrlmmq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gt2taleiykf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gt2sktuaeid.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gt2dlhvzqmk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hywenlv.cn/Article/details/gt2tupuciol.html

[U43] PHP：声明命名空间
来源：http://dali.yonumen.top/Article/details/gt2eoqivusm.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gt2gfuytxhx.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gt2nunxxzpa.html

declare(strict_types=1);
来源：http://dali.jiagoushi.top/Article/details/gt2gjxkasos.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gt2jecjggri.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2rgyidmdx.html

[U46] PHP：可空类型
来源：http://dali.aibaodan.cn/Article/details/gt2ofkzwzqs.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gt2yuvtlmum.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gt2xjnnsggg.html

int|string $id
来源：http://dali.zhixingplan.top/Article/details/gt2avgbvaus.html

[U48] PHP：纯枚举
来源：http://dali.c1oappe.top/Article/details/gt2gjfrtidi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gt2vguveqrf.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gt2hpzxtvfi.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gt2lhiqfrjv.html

[U50] PHP：构造器属性提升
来源：http://dali.xylfe.cn/Article/details/gt2pkjuthbs.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gt2knnctton.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gt2gljueoig.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gt2uxxrzeal.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2iornpqea.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gt2slzloztf.html

[U53] PHP：空合并运算符
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wszaynta.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gt2mszbgszq.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gt2lqwkkzya.html

$obj?->method()
来源：http://dali.sufxvd.cn/Article/details/gt2yqzqxvzz.html

[U55] PHP：match 表达式
来源：http://dali.tanke756.top/Article/details/gt2tcvhflxb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gt2opvhukff.html

[U56] PHP：命名参数
来源：http://dali.smart0.xyz/Article/details/gt2txnbnsro.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhttexi.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2qfllfzls.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gt2tqedarzl.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gt2mzcgqcrw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gt2olgkcipq.html

[U59] PHP：自定义排序
来源：http://dali.zycfv.cn/Article/details/gt2prgdwavd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gt2uvmbbxix.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gt2ogwjqsoo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenlongwang.top/Article/details/gt2alnemtev.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gt2rcpooqgw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2ykiiixei.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gt2tpmnsafw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sufxvd.cn/Article/details/gt2imlccvak.html

[U63] PHP：文件读写
来源：http://dali.dianchejie.cn/Article/details/gt2vnodpjyy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.haohaochexian.top/Article/details/gt2umsxasmj.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2oghbrdyw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuxming.cn/Article/details/gt2ojavnzzr.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gt2zlrnzsyl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2awyourcr.html

[U66] PHP：设置 Cookie
来源：http://dali.sweek.top/Article/details/gt2ymodexmb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2domujsuu.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gt2otpjcssr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gt2yltxgywx.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gt2fxqezpcw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gt2upfhsxsb.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gt2gtvldwnp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gt2enzerktx.html

[U70] PHP：PDO 事务
来源：http://dali.jiagoushi.top/Article/details/gt2xupygfxc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcnpirvk.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2hqiamthg.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2adjwjdzf.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gt2brtuobwz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gt2wqdzchgs.html

[U73] PHP：读取 ini 配置
来源：http://dali.hywenlv.cn/Article/details/gt2ubpgfwun.html

parse_ini_file("config.ini", true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyrcnafu.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2ysklzdyw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nwbrower.top/Article/details/gt2nczqzxry.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gt2fmscojjh.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gt2epdtbane.html

[U76] PHP：简单路由
来源：http://dali.ydzc1.top/Article/details/gt2svjscsmk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gt2aqjpzbra.html

[U77] PHP：模板渲染
来源：http://dali.hywenlv.cn/Article/details/gt2wzijrjtj.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gt2fbbwulka.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddmyzefv.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gt2neqefqsb.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gt2clkkvrcj.html

composer require --dev phpstan/phpstan
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpzbfdwc.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gt2kbobiejg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.iojbl.cn/Article/details/gt2htyacbve.html

[U81] JS：初始化项目
来源：http://dali.cashguo.top/Article/details/gt2ukibpits.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gt2tidjobut.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gt2eqhjpgln.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gt2lzrgspsh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhixingplan.top/Article/details/gt2hutdvagh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.316326.xyz/Article/details/gt2vpteglta.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnihyqnl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gt2yvqonjuw.html

[U85] JS：可选链
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfautccc.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gt2mkoxippi.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gt2lesiprzp.html

a ?? b
来源：http://dali.tian-w.cn/Article/details/gt2qfwfqsrl.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2rxpudrlc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigufen.top/Article/details/gt2ucxbaedd.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhwyuqqb.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gt2xdrbcrub.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gt2csontlgo.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2haxigawk.html

[U90] JS：数字数组排序
来源：http://dali.jiagoushi.top/Article/details/gt2cxsujvvt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2qgdgvvqc.html

[U91] JS：对象键值遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2exztlrrw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gt2fyrpdjrr.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2xlmlglnm.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2bmpagccy.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gt2igbdyjxj.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gt2nfygblry.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gt2nzvzweff.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gt2zrkzgkwd.html

[U95] JS：Promise 包装
来源：http://dali.zhoulong.xyz/Article/details/gt2eumpcikt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2kodwdfug.html

[U96] JS：async/await 与异常
来源：http://dali.aibaodan.cn/Article/details/gt2lxvpzyuv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2smmpddmk.html

[U97] JS：并发请求
来源：http://dali.yuanzhike.top/Article/details/gt2xgxiepmm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2zcsdglix.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gt2navvdlot.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gt2yhazxcsx.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gt2ujzsrsks.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gt2cliheauv.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gt2uuvvltif.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2yxowjsuu.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gt2mganojdf.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gt2mrsmaqwz.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gt2vapcsxec.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gt2wejhfwkr.html

[U103] JS：定时器
来源：http://dali.zhixingplan.top/Article/details/gt2gsrowjzq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gt2iwufjgmr.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gt2tdrmtyzj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2bvnluggc.html

[U105] JS：节流
来源：http://dali.chenjidiqi.icu/Article/details/gt2qninbcir.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gt2qsklmrqv.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2cmdpxgwz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gt2irvznvmt.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2tqcgqwon.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yuiuunzi.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gt2qlqfaxhf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gt2rcvnnhmr.html

[U109] JS：数组分组
来源：http://dali.aizwys.cn/Article/details/gt2oivvltbb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2afhaqual.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gt2tnpawgwm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gt2gxmbmkzy.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gt2iklilqxw.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmdxvjhx.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gt2zxjnwwqk.html

"7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2hxikueji.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gt2ajtliooo.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2dvaoiuwy.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2ntfcayab.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2dzdwcnmn.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2yhncvyjt.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2kqspwopd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gt2hukhpxhm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gt2agrlwike.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2xuwmasox.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gt2xgltlxxf.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gt2arktcnxz.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gt2ugmwzujs.html

[U119] JS：生产构建
来源：http://dali.nanxinkj.top/Article/details/gt2pbnmzccw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvvjouj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2qzusywum.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gt2wkdorlod.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jolohfec.html

统计汇总
来源：http://dali.meibo888.top/Article/details/gt2uyekdxkq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qmfufgse.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gt2syjguubo.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gt2vtxxynzv.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gt2ckspclfr.html

JavaScript ..... 252
来源：http://dali.hnxiangtu.top/Article/details/gt2hlrjzsvs.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upaqzhtb.html

Java ........... 212
来源：http://dali.tanke756.top/Article/details/gt2fbxudoko.html

Go ............. 212
来源：http://dali.yj20258.top/Article/details/gt2rcgnaxrp.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gt2hzgjefrk.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2dlflydks.html

C .............. 30
来源：http://dali.ivvv.top/Article/details/gt2gzbopkql.html

C++ ............ 30
来源：http://dali.xziqi.cn/Article/details/gt2cavaddzv.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gt2xeopsqui.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gt2gncxrqnq.html

Kotlin ......... 15
来源：http://dali.jlsjyb.cn/Article/details/gt2wydsezqb.html

Swift .......... 15
来源：http://dali.fengsongda.top/Article/details/gt2ayswhwvr.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gt2vcdoymra.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gt2rfogllxy.html

Scala .......... 10
来源：http://dali.zdqjudy.top/Article/details/gt2usaghkfx.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2veplrxir.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gt2gbulblab.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gt2ukbtthbh.html


<!-- 参考信息 -->