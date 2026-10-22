代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsuczxlc.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2efbolmac.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2yczufagi.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gt2dhxaetgo.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2nsqmqsqb.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2wdpdielp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehenanyp.html

[T54] Scala：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2fjwrsjik.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gt2iwbfgasc.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2rqxfdhgr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gt2ipeflnbw.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2jxeiwvnb.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2lacshweq.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2qufdqfdw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkcuxbyg.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gt2nyrgoine.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gt2eciyklsm.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gt2zfpkoarr.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2ouigchrp.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gt2lqgvcbej.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gt2eydibctt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2usjykxif.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2bkzcfkyr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2sgomoqru.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2ofxbbfoi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gt2mduwkfwj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gt2zrhafzcs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gt2shviykhd.html

[U03] Py：加载 .env 配置
来源：http://dali.dashuyun.cn/Article/details/gt2kfsjoldk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gt2vasmvwmg.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibbygnym.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gt2slzvmrrb.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gt2xnhghmxt.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2qxcosmbj.html

[U06] Py：合并两个字典
来源：http://dali.meibo888.top/Article/details/gt2gcziwyyj.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crxwquzr.html

[U07] Py：反转字典键值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbvxjqrd.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gt2nhbkrghg.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gt2oxhecmcn.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gt2vquyspos.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbxjwolg.html

max(d, key=d.get)
来源：http://dali.chenzaomai.com/Article/details/gt2eymzvtkv.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gt2bzpgbnef.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gt2rywcwzkg.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gt2vbheziql.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gt2qlcsssak.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gt2djktiucc.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gt2qqevnbpk.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gt2delvkdag.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecnvxqgx.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gt2wcvrnqzv.html

defaultdict(list)
来源：http://dali.hfpthk.cn/Article/details/gt2bpxtcpnk.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gt2ceribdbi.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eazocosr.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gt2elhgzhil.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gt2nrdvkqff.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2ujgkcdub.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gt2stwvskul.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gt2evairyzw.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndnzbeif.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gt2tpjktxpd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gt2thdremmk.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gt2mqrwfhit.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daria6918.cn/Article/details/gt2nvyxmxgc.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzbohrjr.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gt2abndjwql.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gt2ssshvtcz.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gt2nbptskub.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gt2rctckrwl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcthzvyt.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2xksforhd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2uecjywhi.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtolftrj.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gt2afokjitf.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gt2thnbxvfq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyebwsvm.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gt2gehttggp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhyyiqmw.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gt2megociiw.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gt2ryoduebn.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2atggypiy.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gt2swkhnput.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gt2ugxcjeji.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gt2edzpisaz.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2qcfpkejo.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gt2kabcujif.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gt2ldvzwzrn.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gt2wyvetylm.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjospxke.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfxnudsa.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfhzdzjp.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gt2dorhofbk.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gt2wwxflbhp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gt2npsiwivt.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2azuvjoxr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zycfv.cn/Article/details/gt2kctfmmen.html

[U37] Py：读写 Excel
来源：http://dali.havefunace.top/Article/details/gt2mqjoiyhk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gt2jlxqzphz.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxbucydv.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gt2shybvafv.html

[U39] Py：判断是否在交互环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nndekvio.html

sys.stdout.isatty()
来源：http://dali.bjfxy.top/Article/details/gt2vzbwcsuz.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gt2xiawwxbk.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2fgevqpej.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gt2jijbppfa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gzhubu.top/Article/details/gt2zjstzjfr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dianchejie.cn/Article/details/gt2luwoictz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gt2wbxkvpzj.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gt2npqbcilr.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gt2xvmiulcr.html

[U44] PHP：开启严格类型
来源：http://dali.cheryme.top/Article/details/gt2ybuvkehp.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gt2aoodnjyn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gt2uerzuzvn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rbncxbos.html

[U46] PHP：可空类型
来源：http://dali.aibaodan.cn/Article/details/gt2dpfizgna.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gt2yefttwps.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gt2wsamveka.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gt2czmncxxg.html

[U48] PHP：纯枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqelhbxc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppsbldau.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gt2jdgmliro.html

public readonly string $name
来源：http://dali.guannengcc.top/Article/details/gt2xgsfovyq.html

[U50] PHP：构造器属性提升
来源：http://dali.yueranfly.top/Article/details/gt2bjblfigo.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gt2srtbwzqc.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2elkxfwzk.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gt2hqwzfaal.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gt2odooegwc.html

$double = fn($x) => $x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcpfwffj.html

[U53] PHP：空合并运算符
来源：http://dali.yangfankeji.com/Article/details/gt2clwsvhex.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gt2zqniumcs.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbisurbe.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gt2rfznlzpf.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgkjryul.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gt2ctlltkfy.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gt2qmshzvyx.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2lsndgiwt.html

[U57] PHP：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2qsvqmjpw.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2lrrsaywb.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocugwdlx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gt2obzzjujh.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gt2zhrzmyjz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2lokzgddz.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gt2lxecorpd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.redwolf501.top/Article/details/gt2xdtxirfp.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gt2zvewmxcn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2nwmevhoo.html

[U62] PHP：日期对象
来源：http://dali.0kj1m.cn/Article/details/gt2ajpgykfk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.smart0.xyz/Article/details/gt2yraakhnb.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gt2eroniyef.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gt2idxtddax.html

[U64] PHP：目录遍历
来源：http://dali.ivvv.top/Article/details/gt2vdtjlybv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gt2cczfmgki.html

[U65] PHP：会话
来源：http://dali.zhongyouzk.top/Article/details/gt2gfupduep.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2ukevcixg.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gt2hafogqoj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258.top/Article/details/gt2chodokbl.html

[U67] PHP：处理文件上传
来源：http://dali.cheryme.top/Article/details/gt2ihdtrksr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gt2rlbcotjn.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258.top/Article/details/gt2jduyzalm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gt2cdtrmqxf.html

[U69] PHP：PDO 预处理
来源：http://dali.c1oappe.top/Article/details/gt2vdriytxs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gt2tslcdttq.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gt2ilenwcau.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gt2vtctfmno.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2jkkvzoeo.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gt2iiiksmdn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gckdyyuh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnxiangtu.top/Article/details/gt2lfunvinl.html

[U73] PHP：读取 ini 配置
来源：http://dali.ybcxt.top/Article/details/gt2ofrhnlla.html

parse_ini_file("config.ini", true)
来源：http://dali.smart0.xyz/Article/details/gt2relkiduw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeeyakp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.meibo888.top/Article/details/gt2mfesvxyr.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gt2jreqlwjq.html

composer require psr/container
来源：http://dali.ivvv.top/Article/details/gt2brrhoblo.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gt2hicajmnh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.svipenyu.cn/Article/details/gt2lnlefgwb.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gt2hakefzar.html

composer require twig/twig
来源：http://dali.yueranfly.top/Article/details/gt2elxepmlb.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2lbaqzquc.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gt2xpypsneq.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gt2tjvcwgee.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gt2mmnbcdzp.html

[U80] PHP：代码规范修复
来源：http://dali.quarkkingdee.top/Article/details/gt2zzczisaj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhmhdggj.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gt2mzehklqg.html

npm init -y;  npm i express
来源：http://dali.yj20258.top/Article/details/gt2tgosvaza.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gt2lqzlbweo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gt2xemdxlxz.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gt2pbzivnpk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2lfcyvrfv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhengqikj.top/Article/details/gt2odwyorgq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gt2yggumwml.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gt2qxaxiapa.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gt2mkiolwja.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gt2epooabrn.html

a ?? b
来源：http://dali.yj202588.top/Article/details/gt2vyfmqavs.html

[U87] JS：解构默认值
来源：http://dali.yonumen.top/Article/details/gt2vypfxxma.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gt2rxvxmonc.html

[U88] JS：对象展开合并
来源：http://dali.fzhhl.top/Article/details/gt2tuxnajrw.html

{ ...a, ...b }
来源：http://dali.jyoumei.cn/Article/details/gt2eodnrhxt.html

[U89] JS：数组去重
来源：http://dali.ybcxt.top/Article/details/gt2tghvhhum.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2qbmkjuxp.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gt2hddgljuf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2qcqyyojk.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gt2dztoaqyz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuxming.cn/Article/details/gt2kdpqkhpm.html

[U92] JS：深拷贝
来源：http://dali.cucudq.cn/Article/details/gt2vpdbwvyr.html

structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ximkwhke.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gt2fccbifqz.html

`共 ${n} 条`
来源：http://dali.smart0.xyz/Article/details/gt2ycanckrc.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gt2ilhxtwec.html

const double = x => x * 2;
来源：http://dali.aizwys.cn/Article/details/gt2xcwnvffd.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gt2mvidgemj.html

new Promise((resolve, reject) => {})
来源：http://dali.yangfankeji.com/Article/details/gt2wgvpvubv.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gt2tylbcuxg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2zhphypel.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gt2ydorzbxi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2lunmudba.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gt2oghymvnx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gt2szeehtil.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gt2qbjdhajm.html

el.addEventListener("click", e => {})
来源：http://dali.hysaishi.cn/Article/details/gt2zykzmtlf.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edxboobr.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbxbpiwe.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gt2nweejtsq.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uppcejbk.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gt2cyxxqtsh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gt2gkiycqxm.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gt2ivoinbat.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.c1oappe.top/Article/details/gt2dnpltqby.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptmpesfb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrctpogc.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gt2nblatvds.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zycfv.cn/Article/details/gt2jdpqmljl.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2dlmqnbrm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gt2rlkrcehe.html

[U107] JS：数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2udngbbdj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ydzc1.top/Article/details/gt2qxtzsvgy.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gt2ntpqvsid.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsfnzgjs.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqopobzu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2ucergcof.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gt2ygusijbd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gt2xfqohcro.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gt2uhxitrae.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2rokkngpm.html

[U112] JS：字符串补位
来源：http://dali.hfpthk.cn/Article/details/gt2gkkqkumi.html

"7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2xukqjgmk.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytdhxlnz.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2dvaiuxds.html

[U114] JS：JSON 深比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsselwkm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gt2jyidayli.html

[U115] JS：生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2uxemutnz.html

crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2nlpduvpm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgfzy.top/Article/details/gt2wfddhlxb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2tjtyafrs.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gt2woltkmqo.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gt2pwegblak.html

[U118] JS：开发服务器
来源：http://dali.haohaochexian.top/Article/details/gt2pqsjudsj.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlfjnezx.html

[U119] JS：生产构建
来源：http://dali.shuidangran.top/Article/details/gt2rkmezubc.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gt2tjygflsy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gt2cofrsyfv.html

import.meta.env.VITE_API_URL
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfjthxva.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2cnklhhhk.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gt2yljmnyot.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2gsfszmsb.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gt2rxuhfhnj.html

Python ......... 252
来源：http://dali.jianghu66.top/Article/details/gt2eskdjbvy.html

PHP ............ 252
来源：http://dali.nwbrower.top/Article/details/gt2yxiykoch.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gt2ctiwqowk.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2xofdpwph.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2galeygkx.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2xdsgevcd.html

Ruby ........... 212
来源：http://dali.chenlongwang.top/Article/details/gt2aojtbenp.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2kielvxxp.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gt2fgivrxto.html

C++ ............ 30
来源：http://dali.jinqigfzy.top/Article/details/gt2hvvlefdv.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gt2zjsbhone.html

Bash ........... 80
来源：http://dali.nwbrower.top/Article/details/gt2xnfaiock.html

Kotlin ......... 15
来源：http://dali.c1oappe.top/Article/details/gt2cykcidjh.html

Swift .......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmgccbir.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gt2tgzuabqx.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2fhmbctfr.html

Scala .......... 10
来源：http://dali.jiagoushi.top/Article/details/gt2ojbxiexv.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2yaaqjeat.html

合计 ........... 2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcnbbxsm.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gt2zsgglyoy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2sshmzbwt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2smxxhvtr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2kjwxrvjh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gt2rzsdkzsi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gt2qisffqpe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gt2urngacaa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2grgcogxq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2gfkvubek.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2hjvplwhi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gt2hfhesuhs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2jyatwmgf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2wgfyqraf.html


<!-- 参考信息 -->