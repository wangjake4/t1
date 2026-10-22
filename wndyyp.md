代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2gbcqkeny.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2pwkpuhjq.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2ftkojyid.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gt2ilhafxfu.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jivbfitl.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2uwrimvby.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2xinyeydw.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gt2bbynphkb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ccutwhtt.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2yqohkplp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhluxwlg.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gt2tcgmtizk.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2ylrxlzqa.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2rbxiwsla.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eonwezmm.html

[T58] Scala：函数定义
来源：http://dali.jianghu66.top/Article/details/gt2fniuvcvr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gt2xpfiwefj.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gt2iwltztdx.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mohtaiyy.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gt2mmmkqdus.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gt2soywkast.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vigfvgzf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gt2ognpjicx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2guqiihfz.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgzkmgnj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gt2efbxlowi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xitnurii.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2zdvcmfrf.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnstqxfk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gt2grixsgtg.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gt2vwbdxkur.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gt2adikuqzf.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gt2oeqarmxu.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2csiibfhb.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldnbchlp.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gt2gxfbddhe.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gt2goyjcftx.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2fchzaciy.html

[U08] Py：展平二维列表
来源：http://dali.ehwqpu.com/Article/details/gt2srzshjuj.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gt2mvecefzo.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gt2dsvwfxlg.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gt2twaxzvzc.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gt2aozcyotx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gt2gflyigcf.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gt2grxcjeof.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gt2blwrlnqc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gt2ajybmyig.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gt2uhraszzj.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2zbicaoai.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gt2aikvasuy.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2qhpqfkzg.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gt2pzoackgq.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxzsaymt.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gt2mlllowtt.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigufen.top/Article/details/gt2bvbjgylp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yiqwdvbt.html

[U17] Py：初始化日志
来源：http://dali.yj20258.top/Article/details/gt2itogpvix.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gt2cztjwivm.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gt2hkssttfz.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2nmzcvnfe.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gt2aokmjbsa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gt2bqesnfwc.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhuikqcg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258.top/Article/details/gt2krkpqzmp.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gt2gjsvohsg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2trkwdahp.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gt2tswpbylc.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gt2qsdxbdbq.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gt2vebbxwcg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gt2hihwqejo.html

[U24] Py：路径操作
来源：http://dali.dianchejie.cn/Article/details/gt2prlgwikw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2hntggqyu.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gt2quexggkf.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gt2lwpjdjbs.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gt2rznnqluv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gt2rvboeopo.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcwafwkj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2epgvqpav.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gt2obwxmkur.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gt2nhqjrlse.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gt2cqkwmsci.html

@property 与 @x.setter 配合
来源：http://dali.shzxlz.cn/Article/details/gt2ccwggnfo.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhqkqfsm.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gt2enoxuuoe.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gt2buxuyslo.html

python -m pytest -q
来源：http://dali.tianlin.xyz/Article/details/gt2hzikqidq.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gt2sgazuzax.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2ucpniezl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjijtkw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gt2etbzuiyn.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gt2cxvacqjp.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gt2ieilrjzy.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gt2vskqxzft.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gt2omcirjmz.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gt2cxpvafvf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gt2nvgzlwxz.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gt2mtlivjtl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gt2jdfhyjqq.html

[U38] Py：获取脚本所在目录
来源：http://dali.cashguo.top/Article/details/gt2soylhnul.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gt2ebbnazsa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhoulong.xyz/Article/details/gt2yfewnlmr.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gt2amveaevd.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aokzczoz.html

print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqnpfdrk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gt2byauaqbr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gt2espaofnx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gt2gfnpqrjl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gt2kbwwuppl.html

[U43] PHP：声明命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2uawtuopk.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gt2cfhfseus.html

[U44] PHP：开启严格类型
来源：http://dali.havefunace.top/Article/details/gt2qzzajpby.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gt2fqelpayl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crsrbcoo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gt2mtzzxziv.html

[U46] PHP：可空类型
来源：http://dali.iojbl.cn/Article/details/gt2zoklugur.html

?string $name = null
来源：http://dali.yueranfly.top/Article/details/gt2azxujtby.html

[U47] PHP：联合类型
来源：http://dali.xylfe.cn/Article/details/gt2swovncmu.html

int|string $id
来源：http://dali.hysaishi.cn/Article/details/gt2jehdtkbq.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmsuofas.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hmzxcndo.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gt2pratzkdq.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gt2qszrvuzn.html

[U50] PHP：构造器属性提升
来源：http://dali.iojbl.cn/Article/details/gt2lfqhkykj.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gt2hdzzvxhq.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gt2mlaulzxo.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gt2bsjvzjhb.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gt2xhssbdct.html

$double = fn($x) => $x * 2;
来源：http://dali.meibo888.top/Article/details/gt2dsuctecw.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2furgqpsc.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gt2lbmcvgxe.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gt2gwxgjnsf.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygkygmdv.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gt2yjtyctij.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2gfkwedop.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gt2tcvdfoti.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2oyltfmdb.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2qjnclgko.html

"值: {$a}"
来源：http://dali.gzhubu.top/Article/details/gt2ufoduntr.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gt2aqkpohjx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2dvugiqxj.html

[U59] PHP：自定义排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcqxqjtp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gt2pygqxtfc.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbacnfrn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.meibo888.top/Article/details/gt2chhuiktt.html

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gt2dirncqbu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2flwrwjxn.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gt2txdjcgbz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sufxvd.cn/Article/details/gt2qtfythmo.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gt2tqdhmyrz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udjelueb.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2pjctffuq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hywenlv.cn/Article/details/gt2qhsfjwrc.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gt2scgmnhbj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2ybxydbis.html

[U66] PHP：设置 Cookie
来源：http://dali.tian-w.cn/Article/details/gt2yhfofgta.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gt2okojzukq.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gt2ddpzmmiu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gt2pjndyluu.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gt2qufhvutv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gt2naguvmwh.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gt2qotkivhi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2maewhgrb.html

[U70] PHP：PDO 事务
来源：http://dali.yuxming.cn/Article/details/gt2jixjvghg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gt2ucnhcsrp.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gt2kdvzodcv.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gt2bttnegjy.html

[U72] PHP：写错误日志
来源：http://dali.iojbl.cn/Article/details/gt2aifbdcst.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gt2ykrdzhmp.html

[U73] PHP：读取 ini 配置
来源：http://dali.smart0.xyz/Article/details/gt2btngjull.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzqkttkg.html

[U74] PHP：读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2eyoahwja.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gt2lcpkkadr.html

[U75] PHP：依赖注入
来源：http://dali.yj202588.top/Article/details/gt2ujxtjevh.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gt2gfrywlzz.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gt2qnlqddoo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gt2bqayxucz.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gt2giuabpkr.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swdnkanx.html

[U78] PHP：单元测试
来源：http://dali.hfpthk.cn/Article/details/gt2ctlravmz.html

composer require --dev phpunit/phpunit
来源：http://dali.hongshengwenyu.top/Article/details/gt2mexrnhsz.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gt2ifdcqnto.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gt2ejdtrfms.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gt2oxlpwlmx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangdashe.top/Article/details/gt2rpdvbodd.html

[U81] JS：初始化项目
来源：http://dali.0kj1m.cn/Article/details/gt2egzcnxxy.html

npm init -y;  npm i express
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zileqgdj.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gt2pigvwkmp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gt2xezbxzfd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gt2lrgamduu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2rbhdhqje.html

[U84] JS：CommonJS 写法
来源：http://dali.quarkkingdee.top/Article/details/gt2alhcmtms.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gt2eadfwoei.html

[U85] JS：可选链
来源：http://dali.chenzaomai.com/Article/details/gt2kzbscmzl.html

a?.b?.c
来源：http://dali.xuanzx.com/Article/details/gt2zatxhauf.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gt2mexyykkg.html

a ?? b
来源：http://dali.sweek.top/Article/details/gt2dqbyavtm.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2tvhprbuz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tian-w.cn/Article/details/gt2cmbvvxwj.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gt2krhojzlp.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbwdikws.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gt2irjddyws.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2hfvhooro.html

[U90] JS：数字数组排序
来源：http://dali.ydzc1.top/Article/details/gt2kjqngsro.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2vaxhocio.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gt2znhnkugp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gt2jptagmqz.html

[U92] JS：深拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfvigcmq.html

structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2llnnnwzn.html

[U93] JS：模板字符串
来源：http://dali.jiagoushi.top/Article/details/gt2ntrmvzec.html

`共 ${n} 条`
来源：http://dali.yj20258.top/Article/details/gt2ockfdyca.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gt2ghdlqsjn.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gt2ufbispkk.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gt2wznfuscc.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gt2wtnplcqo.html

[U96] JS：async/await 与异常
来源：http://dali.zhongyouzk.top/Article/details/gt2bpaiwvhe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2fyqbwtuk.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gt2eoheewfb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2kbubwskq.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2pickjjjd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gt2inhpydlr.html

[U99] JS：事件监听
来源：http://dali.hywenlv.cn/Article/details/gt2cvomtsze.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gt2oraalngi.html

[U100] JS：DOM 查询
来源：http://dali.fzhhl.top/Article/details/gt2bnmbixzz.html

document.querySelector(".item")
来源：http://dali.zycfv.cn/Article/details/gt2nxlqwqvp.html

[U101] JS：classList 操作
来源：http://dali.nwbrower.top/Article/details/gt2kdyegvom.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrjprzwn.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gt2hqaxvutb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gt2esqkdjdv.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gt2yizrizkt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcdcxheg.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gt2kqklvsth.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2ulbgimhm.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gt2ktdhddlv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2soxrhceb.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2adqpkmlq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gt2npthzibr.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2vwdvdikb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2omvuidvg.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gt2ucwouquk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxuanxn.top/Article/details/gt2qivarkkc.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gt2ljnrhxjg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2atixzqgr.html

[U110] JS：数组分块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emipwkaq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gt2cngqnwrk.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gt2igzredzr.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2ssclrsvy.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gt2okqhrvre.html

"7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2ejuowypw.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gt2nyajcynb.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2pbqucfce.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gt2qzbfbsqt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2fcrbwhdc.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2czhqfjwz.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2plmhsaog.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gt2kvnenono.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gt2yvfmatqz.html

[U117] JS：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uincszha.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gt2zwmsdagd.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gt2vgmwcpqr.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gt2sikeagvc.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gt2ojzzkmfi.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gt2fvwrxeut.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gt2stcvpyni.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gt2jkkkkqcj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nqgxjatu.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gt2vvkmiwml.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajycsbjg.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gt2advypqnl.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2szcjjvcj.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gt2zkqtjuvt.html

JavaScript ..... 252
来源：http://dali.zhengqikj.top/Article/details/gt2myxzhqdv.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gt2jogediyk.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2rioxrnwv.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gt2ccpyglbz.html

Ruby ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2gajiuuym.html

C# ............. 212
来源：http://dali.cucudq.cn/Article/details/gt2ogkmdqsy.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gt2dilsmogv.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gt2agueztnk.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gt2spyqujji.html

Bash ........... 80
来源：http://dali.jyoumei.cn/Article/details/gt2ranhebzj.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzlvfqah.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gt2ultpugio.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gt2ptagzlkq.html

Perl ........... 10
来源：http://dali.sufxvd.cn/Article/details/gt2wcrmfnck.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gt2zipaqmln.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2qyxjtuyb.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gt2ttfjslcy.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gt2ojgigilv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gt2noeztlke.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gt2xlmrexag.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2ewgzzxtn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gt2ebwksvmo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxuanxn.top/Article/details/gt2mbewhbwj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qacxbrlx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2yniezakg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agkoteaz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2onipxicz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gt2ntwtmxyx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2skrvcsdq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2psyvhmmx.html


<!-- 参考信息 -->