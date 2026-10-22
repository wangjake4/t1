代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gt2hkpbqbyw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2bxtanbwg.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2fuqvzoat.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gt2cynbpjgz.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibxadyfo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2oszhgdsh.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezuxbawt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gt2xhqmhofa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gt2kawerdrk.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2bqtgigvs.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2hlrrkeyf.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gt2ofyvpfwu.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gt2pprujoja.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2oxbobgxe.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2zwunbfoe.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2dggiojuy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2fsfxittv.html

[T55] Scala：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2mpoazrcu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gt2qrytozhw.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gt2bboczmgo.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gt2spkpnlim.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2ugmqwpmm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aljbmwrd.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2rmaxkuyk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gt2xoulkkyu.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gt2sypkyxir.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2elqhziyx.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2ntldijbs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gt2sdycxitr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ryvmzuuw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gt2nksnofci.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2imlhexqw.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jeahtrlt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gt2emkdrepa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gt2btizyzlu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gt2dzzvlyhx.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzyrwiin.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gt2xvxdprzd.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gt2aqifdrjx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2huaignqx.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gt2jrdoghou.html

list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2xuoyxqtx.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gt2ncfympaz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwwtora.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gt2lyztkfry.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gt2owzosjzv.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gt2brzdyqid.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gt2uyapopiu.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gt2fgxrefuw.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gt2dzzkhmmr.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gt2hipnfqjw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2thinnxuc.html

[U11] Py：生成器表达式
来源：http://dali.yuxming.cn/Article/details/gt2tlqilddl.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gt2cnffcjak.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gt2ozrqikou.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gt2zssslglt.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gt2jsckfnat.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gt2pgouljpr.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gt2hkjoamtp.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2aayobnic.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gt2btiauwfa.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gt2iawtvzlw.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gt2bxkvwxtf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gt2moyjcjwh.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gt2awkhbpgz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gt2jgnbsdlc.html

[U18] Py：预编译正则
来源：http://dali.ivvv.top/Article/details/gt2gdrzdjlh.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2meabvceu.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewxhhtnd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gt2isodhrpc.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gt2xztqdvrr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gt2vqfbelya.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gt2evwkrtcu.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gt2vqltkxbt.html

[U22] Py：矩阵转置
来源：http://dali.chenzaomai.com/Article/details/gt2uyxwwtoo.html

list(zip(*m))
来源：http://dali.yvedp.cn/Article/details/gt2nvusgsoh.html

[U23] Py：分块读取大文件
来源：http://dali.dianchejie.cn/Article/details/gt2ajqrcqad.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gt2uixnwwoc.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gt2acltojug.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfzeiizc.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gt2eezaxisj.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gt2wmpgrbsh.html

[U26] Py：并发下载
来源：http://dali.hfpthk.cn/Article/details/gt2bbudskfx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gt2rcplbdcg.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gt2dyuiglqf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gt2pcbechtq.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gt2atnpaknf.html

UserId = int
来源：http://dali.jiagoushi.top/Article/details/gt2dypowloo.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nowredbn.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxjfhldm.html

[U30] Py：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2pqkwgpzp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2exlmkpbu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsxsdle.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gt2csmizpvw.html

[U32] Py：代码格式化
来源：http://dali.aibaodan.cn/Article/details/gt2nrbtywjd.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gt2mfkofzwz.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gt2qoivlfdl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daxiang520.top/Article/details/gt2ncobkptb.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gt2pxcmcqhr.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gt2ntczxkuy.html

[U35] Py：发送邮件
来源：http://dali.zhongyouzk.top/Article/details/gt2cshluopc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gt2ihecxsgq.html

[U36] Py：定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2imvxnqhf.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnxiangtu.top/Article/details/gt2qnjjgetq.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gt2gqqcmlfi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzwvyjol.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gt2gbqqgkpg.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gt2dsondgvu.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gt2abgwsuzn.html

sys.stdout.isatty()
来源：http://dali.9152youxi.cn/Article/details/gt2jbstkqwr.html

[U40] Py：打印到标准错误
来源：http://dali.bjfxy.top/Article/details/gt2qhrzszgw.html

print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gt2qbdfzdsf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gt2lwqcquwt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gt2kropmows.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gt2vxpjhdci.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxinkj.top/Article/details/gt2eozuveaa.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gt2vwxlfviu.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gt2mgyyeyha.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gt2edvmshxz.html

declare(strict_types=1);
来源：http://dali.zdqjudy.top/Article/details/gt2xwyeevoz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gt2zxfyckgu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gt2imhetcja.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gt2oqplmkgi.html

?string $name = null
来源：http://dali.iojbl.cn/Article/details/gt2rsjtgxxs.html

[U47] PHP：联合类型
来源：http://dali.ydzc1.top/Article/details/gt2jbrzhxpe.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gt2oewamkgl.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gt2svlgxwdt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gt2hbocuybe.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gt2kgtugdyl.html

public readonly string $name
来源：http://dali.yj20258888.top/Article/details/gt2vxsxfwav.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gt2qpyjwpqn.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gt2yetsuubp.html

[U51] PHP：数组解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2esigbkis.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gt2cbamcyev.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gt2xxmwusyd.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2pgfguvwv.html

[U53] PHP：空合并运算符
来源：http://dali.nwbrower.top/Article/details/gt2xbtphove.html

$v = $a ?? $b ?? "default";
来源：http://dali.iojbl.cn/Article/details/gt2stqzbnfy.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gt2cocufeiv.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gt2mmlqbksu.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2wdwgjwkc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2dmssomcv.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gt2kefdlvvs.html

f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2bwvkywma.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdbcvtux.html

"值: {$a}"
来源：http://dali.yj20258.top/Article/details/gt2olvmcxvp.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gt2zmdomadr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2tlvefhuh.html

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gt2ezepkuok.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gt2ffasekfb.html

[U60] PHP：JSON 编解码
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbgnbjto.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2ztqssqnv.html

[U61] PHP：正则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydkcjyzy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2iwmbgpcn.html

[U62] PHP：日期对象
来源：http://dali.fengsongda.top/Article/details/gt2snzrfhbk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmvxhtzp.html

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gt2swdljbkb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gt2ymqhckiq.html

[U64] PHP：目录遍历
来源：http://dali.wangdashe.top/Article/details/gt2mtfzjifo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftbddmcy.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gt2ixotuqvg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2halvwoch.html

[U66] PHP：设置 Cookie
来源：http://dali.chenlongwang.top/Article/details/gt2iupgqznb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gt2hixwoqhy.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gt2arakkpbg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gt2nlzfrdah.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gt2dxzryxea.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.iojbl.cn/Article/details/gt2psueixqg.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjflkmsv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gt2akkkfxoz.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gt2kubjqxrz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gt2tsxoaawm.html

[U71] PHP：抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqrppkjy.html

throw new RuntimeException("失败", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2zhvykxgn.html

[U72] PHP：写错误日志
来源：http://dali.birdmap.top/Article/details/gt2swjiulsh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gt2kernozfm.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gt2udcosjhf.html

parse_ini_file("config.ini", true)
来源：http://dali.sufxvd.cn/Article/details/gt2pfkcfjqb.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2voovczym.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cdnleiting.top/Article/details/gt2zpffokid.html

[U75] PHP：依赖注入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnwfdfep.html

composer require psr/container
来源：http://dali.nwbrower.top/Article/details/gt2fhnrkwmy.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gt2tpydevrl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gt2nqkvpfsi.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2axuhqzuq.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gt2dutzmzxy.html

[U78] PHP：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gt2nchkamog.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gt2cmqlyzxq.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gt2bprfmxbg.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gt2cedgoihd.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuajrwpr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.0kj1m.cn/Article/details/gt2sgkbdfat.html

[U81] JS：初始化项目
来源：http://dali.yueranfly.top/Article/details/gt2iaaxqktq.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gt2xftdodum.html

[U82] JS：package.json 脚本
来源：http://dali.xuanzx.com/Article/details/gt2cdfqdibi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sysykeji.top/Article/details/gt2skebokui.html

[U83] JS：ES Module 导入导出
来源：http://dali.aizwys.cn/Article/details/gt2iviknpfi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.havefunace.top/Article/details/gt2nbuslxvu.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gt2qgncyfej.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gt2tcbpohvi.html

[U85] JS：可选链
来源：http://dali.xinyue.icu/Article/details/gt2fbwqrees.html

a?.b?.c
来源：http://dali.snrcjt.cn/Article/details/gt2sviphadp.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gt2ivjgzgpe.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vllmlgws.html

[U87] JS：解构默认值
来源：http://dali.yueranfly.top/Article/details/gt2bnghecrx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gt2pggsenkq.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gt2gddjsagu.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gt2muajypdf.html

[U89] JS：数组去重
来源：http://dali.gaohongyu789.top/Article/details/gt2ddfsbmcn.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2wndzvotu.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gt2caxjkwvp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2aqbzebfu.html

[U91] JS：对象键值遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pumubxnc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciafkhws.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylsduwua.html

structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2usyvmrzy.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2vbqrjrpn.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gt2muserfox.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gt2jhzexjnb.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gt2oylfmoqd.html

[U95] JS：Promise 包装
来源：http://dali.ydzc1.top/Article/details/gt2lsjabttd.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gt2gzsogbdn.html

[U96] JS：async/await 与异常
来源：http://dali.hnqzz.top/Article/details/gt2zqutdbfv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2dacaiddm.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gt2nnwczshe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2tovwcame.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2ysxmmoqs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gt2cqrdoeap.html

[U99] JS：事件监听
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huvbftne.html

el.addEventListener("click", e => {})
来源：http://dali.sysykeji.top/Article/details/gt2daikdfeb.html

[U100] JS：DOM 查询
来源：http://dali.xinyue.icu/Article/details/gt2yhswesow.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gt2xkxxgdwd.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2tkkvnjen.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gt2uemlrehn.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gt2dvqniofa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gt2wkdrxxce.html

[U103] JS：定时器
来源：http://dali.zhongyouzk.top/Article/details/gt2mmugfvyy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnqzz.top/Article/details/gt2djygycwj.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gt2zjaaazod.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2qagpommm.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gt2yzyussrb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gt2sizhpaln.html

[U106] JS：日期格式化
来源：http://dali.snrcjt.cn/Article/details/gt2znfmjrml.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwmvewbj.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gt2rheqeqxw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2glbbvknh.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gt2gezwocur.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hfpthk.cn/Article/details/gt2pwdhxjyl.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gt2irgqbkwp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2kbrufger.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qoiuvzjv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.havefunace.top/Article/details/gt2uteexqvg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jweooavm.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gt2reayjjhu.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gt2byxtthrw.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2krkhkaxr.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gt2wxgtbyng.html

s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2nbrroizg.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gt2bkseceqg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2cvsshcnn.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2pehjatkm.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2buuxyctf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gt2jtoaqxgc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppbukmcd.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2txivadag.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gt2pchljaxk.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gt2mrlmzswa.html

npm i -D vite;  npx vite
来源：http://dali.sweek.top/Article/details/gt2plaeqapm.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gt2ruxrbmiw.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gt2kdwsmfej.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gt2bdfntdia.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gt2hgbfujdh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2owsqjjrz.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gt2acmzghyi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2cfwbxxch.html

按语言统计（条）：
来源：http://dali.kuanghao11.cn/Article/details/gt2ctpidgjp.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gt2ukkzdoax.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gt2xbmwynyo.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gt2cceuojtd.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gt2ryskdfms.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2axdvmfnm.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gt2ccvdbjfz.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gt2vnczwrfj.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loodlhea.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztgxljqn.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gt2xxkksyhf.html

SQL ............ 90
来源：http://dali.xinyue.icu/Article/details/gt2pbrwamov.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgjcthjy.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2wcosxotk.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gt2pudskufs.html

Lua ............ 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocenlezf.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gt2upoohocf.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eheknkfh.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2blwfdzgu.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvorthrh.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gt2bvwgtxly.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gt2gftroxdb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gt2xbckmmyv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2csmlizst.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gt2dkhemcyi.html


<!-- 参考信息 -->