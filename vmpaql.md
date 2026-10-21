代发 wailian999

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gthdvchvuj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtcesiodxf.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtvqakvhsu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gtdfsdhpkj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gtwbtdanhb.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtzsypmcgx.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtanzjqvqb.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gtxvrpoudp.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gtwnovtqyl.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtkeiwldwq.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtzjjzcgue.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtolkkwxfk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gtifgsumxk.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtruyoherg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtyiirulyc.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gtohxuqgik.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtbiixaujx.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsfcwybg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtgihpukov.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtkvvakhkz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtgkstqpgo.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gtopbrwmen.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtgsjloxzg.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gtbmlhylmv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtmzvwzehf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gterkhzskg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtcybwjiro.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtokazckyn.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtnjfvdwiw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gteeukrisz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtilpmubex.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gtaetagwwy.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gtmdfhvwpe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gtpllgovfx.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gtqqkmdkqz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtchiyvunc.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gtcptnewon.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gthbtgxtcn.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gtovartolj.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtfccoppar.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtthnocdvw.html

{v: k for k, v in d.items()}
来源：http://dali.yvedp.cn/Article/details/gtxcziznzk.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtxqdipcfe.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gtlfljfbpn.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gttrzpfpwi.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtjnkkfdpy.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtgxdgeiyx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpfuewqa.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtkmzpuuox.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtblrwaase.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtkrtmbgtw.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtulsahmja.html

[U13] Py：固定长度队列
来源：http://dali.quarkkingdee.top/Article/details/gtvenifrvw.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gtrspguvbf.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gtfrcxqkkh.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gtyzyhzcni.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gthhgqkzex.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gtonvplsey.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtujauqhkc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtvlrrfsml.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtxouajvde.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxmbqoys.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtbpzljzxg.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtmhrpxyeg.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gtjbyvonrv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pycfn.com/Article/details/gtihubnrfc.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gtumvaefbo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtifnnkpeo.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gtztqpreai.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gtvmbrpudp.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gtmzsexqyh.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtnlijxdsv.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gtopwythpq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gtqduhilps.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gtcdibajiv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtfxkyofvc.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gtescrrsrz.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gtxisgjxze.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtlgzvfggq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.316326.xyz/Article/details/gtltztgdts.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gtpyieemfj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtyunvuxcz.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gtbsfppolc.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gtemvcujvt.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gtikehbtwk.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gtanejccza.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtpxpcbqpv.html

@dataclass(slots=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtizrfytmo.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gtrkzgoklw.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gtjzlnpmnt.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtpiobjfwj.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gtzsridomu.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gtgpiykbuv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtgcllbsms.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gtwdxksfmw.html

chardet.detect(raw)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuyeahbj.html

[U35] Py：发送邮件
来源：http://dali.fengsongda.top/Article/details/gtdsfmvauo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.quarkkingdee.top/Article/details/gtktxevqaa.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqqnuudr.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gtpvytskls.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gtoqjtsaxl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gtdclpgoks.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gtxkdqqveh.html

Path(__file__).resolve().parent
来源：http://dali.xinyue.icu/Article/details/gtkyowmmna.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnxiangtu.top/Article/details/gtftzxulpr.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gtjyboibqu.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gtmtrixdhm.html

print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtswdximbz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gtfgymwepd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuanzhike.top/Article/details/gtfdykgbsp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shzxlz.cn/Article/details/gtxniueksc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtskdootje.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtfwkfbfhb.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtqmdfjyrj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gtqkwtaxpl.html

declare(strict_types=1);
来源：http://dali.bjfxy.top/Article/details/gtnunvmnzo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gtpixjlqjt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtntpbljaq.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gtrvlxnwgd.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gtlwbddarn.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gtzpdprupi.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gtswvccpjf.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gtzcsadwbe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jlsjyb.cn/Article/details/gtgjqzmlmv.html

[U49] PHP：只读属性
来源：http://dali.nanxinkj.top/Article/details/gtazhgditc.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gtljzhtddb.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gtmbewlpqy.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gtjnzfypib.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gtjdnzkcyr.html

[$a, $b] = $arr;
来源：http://dali.mhx1999.top/Article/details/gtdfjxnxms.html

[U52] PHP：箭头函数
来源：http://dali.sysykeji.top/Article/details/gtmiktixdn.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtublusvck.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gtvtstrhqp.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gtlbtramvg.html

[U54] PHP：空安全调用
来源：http://dali.chenjidiqi.icu/Article/details/gtpvshwavf.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gtsrqmpudu.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gtuqigydvv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gtuquvavqj.html

[U56] PHP：命名参数
来源：http://dali.guowangkeji.top/Article/details/gtwxioenec.html

f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtdzzaeqab.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtrqwpjeal.html

"值: {$a}"
来源：http://dali.tianlin.xyz/Article/details/gtsxkzeyop.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gttemdvhdp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.smart0.xyz/Article/details/gtsnrdmuvj.html

[U59] PHP：自定义排序
来源：http://dali.shzxlz.cn/Article/details/gtjehjrfje.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtxhzevjgj.html

[U60] PHP：JSON 编解码
来源：http://dali.yuxming.cn/Article/details/gtzzjzbwet.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.c1oappe.top/Article/details/gtkcfyhjzu.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gtrhyxbfgn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gteeesnjbo.html

[U62] PHP：日期对象
来源：http://dali.xuetiantiany.cn/Article/details/gtbhvpwdlq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgprvgvy.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gtfumpctcp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gtefvknymm.html

[U64] PHP：目录遍历
来源：http://dali.dianchejie.cn/Article/details/gthvcapskf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pengpengdd.cyou/Article/details/gtutlwimer.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtyyrhiued.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hammf.cn/Article/details/gtlyjxrwcx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhengqikj.top/Article/details/gtzhwqlpjw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gteiisjlpa.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtrmnssmrc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sweek.top/Article/details/gtifuveegy.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibqhycca.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gtmtizopnd.html

[U69] PHP：PDO 预处理
来源：http://dali.0kj1m.cn/Article/details/gtctpkzqhf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gtfasxyhyz.html

[U70] PHP：PDO 事务
来源：http://dali.hywenlv.cn/Article/details/gtzmjlkddl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhongyouzk.top/Article/details/gtfyesrigc.html

[U71] PHP：抛出异常
来源：http://dali.nwbrower.top/Article/details/gtfcoffwrz.html

throw new RuntimeException("失败", 500);
来源：http://dali.hywenlv.cn/Article/details/gtghrsxhjm.html

[U72] PHP：写错误日志
来源：http://dali.feifeiyinyue.top/Article/details/gtrbxgozrz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gtimbmschk.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gttpyobnqm.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxampkec.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtflwknyfy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtpzhputmj.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gtfxbjfada.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gtmtclvhrs.html

[U76] PHP：简单路由
来源：http://dali.feifeiyinyue.top/Article/details/gtzbtdmipx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gtpasqblsi.html

[U77] PHP：模板渲染
来源：http://dali.pycfn.com/Article/details/gtlsjgqdml.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gtegsldrsb.html

[U78] PHP：单元测试
来源：http://dali.birdmap.top/Article/details/gtlrpgfoja.html

composer require --dev phpunit/phpunit
来源：http://dali.yanxiufei.cn/Article/details/gtmxzvdplu.html

[U79] PHP：静态分析
来源：http://dali.yanxiufei.cn/Article/details/gtaabytxwa.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gtvyskhpdf.html

[U80] PHP：代码规范修复
来源：http://dali.316326.xyz/Article/details/gtzrlkzdax.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gtkjbjkkvl.html

[U81] JS：初始化项目
来源：http://dali.sxryk.cn/Article/details/gthouvdrxb.html

npm init -y;  npm i express
来源：http://dali.xuetiantiany.cn/Article/details/gtecxxlscu.html

[U82] JS：package.json 脚本
来源：http://dali.sufxvd.cn/Article/details/gtgkmjfcuh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuetiantiany.cn/Article/details/gtaasvzcfp.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gtwqnfetrw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtgygbzxzz.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtwkhbucpl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuetiantiany.cn/Article/details/gtfihabnlv.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqefwayh.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gtvjqwkali.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gtzrrqecen.html

a ?? b
来源：http://dali.ppjwa.cn/Article/details/gthjbekmon.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtlcnahjoj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258888.top/Article/details/gtvdutlxan.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtcpkmszae.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gtltuoporj.html

[U89] JS：数组去重
来源：http://dali.9152youxi.cn/Article/details/gtdxcqcggv.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtixuxezrl.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gtbswqigqi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtfktmjhrm.html

[U91] JS：对象键值遍历
来源：http://dali.zhoulong.xyz/Article/details/gtlopktiqm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gttvtvqzjt.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gtvkolvdmn.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtirmspkhv.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtkvifdyaf.html

`共 ${n} 条`
来源：http://dali.gogol.net.cn/Article/details/gtxiqbxvfj.html

[U94] JS：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtzgravnht.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gtubelimlf.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangtech.top/Article/details/gtuldblfpx.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxzitmbm.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtqgiziafo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtnwvgcuok.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtgjjwzopn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtyglsnuqy.html

[U98] JS：fetch 带 JSON
来源：http://dali.c1oappe.top/Article/details/gtrufqyghx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtneizxneh.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gtaxgewzvp.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gtdadtghxt.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtqtusxbae.html

document.querySelector(".item")
来源：http://dali.hnxiangtu.top/Article/details/gtqpkupdoz.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gtmtthnijj.html

el.classList.toggle("active")
来源：http://dali.jinqigufen.top/Article/details/gtljfzexkt.html

[U102] JS：本地存储
来源：http://dali.gogol.net.cn/Article/details/gtghwahncc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gtrboaqwyx.html

[U103] JS：定时器
来源：http://dali.guannengcc.top/Article/details/gtiuaempqu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtcyzpshsa.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gttdzovjej.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtpzxwpuhs.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbldoobvj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtegoldgpu.html

[U106] JS：日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcezrpjym.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuywmjge.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtrfgnablm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gthaqpefer.html

[U108] JS：随机整数
来源：http://dali.nanxuanxn.top/Article/details/gtbjezpfpm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gtjhvgnyaw.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gtxqkwardu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtwaaqnrff.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtcszbozic.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtdugvvizn.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtyypynxjm.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gtjtajjjfm.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gttuapimnd.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtvbtmtwvc.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gtsqqgwtke.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtpruypvxf.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gtaeffthxv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtavwctpcf.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gtqvpithzi.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gthjejfzev.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gtoifzlknz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtajesaesl.html

[U117] JS：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtigauxhbp.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtlgiqgqfl.html

[U118] JS：开发服务器
来源：http://dali.nanxuanxn.top/Article/details/gttgmewrsy.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtxpxgeiff.html

[U119] JS：生产构建
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbazzuoij.html

npx vite build
来源：http://dali.shangyingyoupin.top/Article/details/gtslfqpsgz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nwbrower.top/Article/details/gtzfdcpgin.html

import.meta.env.VITE_API_URL
来源：http://dali.hfpthk.cn/Article/details/gtcmdzaeuv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcsymtfsy.html

统计汇总
来源：http://dali.yj20258888.top/Article/details/gtmjrmznmw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgneidbeq.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gtbapovijy.html

Python ......... 252
来源：http://dali.bjfxy.top/Article/details/gtxmeaheob.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gtqxuxmief.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gtqvpjheml.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gtzphsvboj.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtfctuhqto.html

Go ............. 212
来源：http://dali.jyoumei.cn/Article/details/gtplcdpzqt.html

Ruby ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtdysisxjr.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtjnklzonk.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsogunkzs.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gttrcfhana.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gterkzsemj.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtbamkxnab.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gtfnngxubl.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtcvalnpcy.html

Lua ............ 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilqslqtz.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gtwvpycxfw.html

Scala .......... 10
来源：http://dali.yj202588.top/Article/details/gtjkuirjof.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtaegeuocw.html

合计 ........... 2106 条
来源：http://dali.tianlin.xyz/Article/details/gtbrokwnmz.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtdgyzdbim.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gtxwzrfmuw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtwrttzgah.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtkgwrevwt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtqiywxfxj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gotoacloud.top/Article/details/gtvximvcnz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtmrckxyrh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtplrwazah.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtgemtcgqb.html


<!-- 参考信息 -->