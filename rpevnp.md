代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gt2gcvxpttl.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2ooehwwif.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2hcnggkzl.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gt2gjvudoun.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2lfcauelw.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2eoiktfhu.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2vxfcvqol.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2hltckzht.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gt2zqixjhtp.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2pvzodamt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gt2iujdldsz.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gt2otbfxcbs.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2irrqbyhj.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gt2lengpomz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gt2coaitbyp.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gt2setznpmi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gt2aklcqbmv.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcclgwza.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2dmvphkno.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gt2mmjgsjcm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gt2oyrwbgef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpykapt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2vxjdstwp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jycockcc.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gt2pqyqxwqm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gt2nlzqdepy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gt2szegecqq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gt2egishbup.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gt2kwjvqeni.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gt2kwwckgih.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gt2edgdunha.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gt2ehwwmsvb.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gt2deilpbkz.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2xtcxwtov.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gt2brovtivl.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gt2sufjtrtq.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2acnwmxxm.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gt2inwnyzwh.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gt2lfxfuhmi.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gt2ktyddixi.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcxbvnps.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gt2gsmgpkve.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gt2vbnexsqq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2djifkaot.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2wzobiqgy.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gt2kprpgvge.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gt2bwkknrfp.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gt2ckxzgyte.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gt2zljudzmd.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gt2fzykhlcg.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gt2utnbxatt.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gt2luyuewya.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvrhwxro.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gt2rzvmlkqx.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gt2hlbvawqy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gt2slvplfbk.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lglrtimr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gt2sgofybme.html

[U18] Py：预编译正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2diowgvur.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2nvnjypky.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gt2xpaafqcj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gt2bnfrcjfm.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2hyukgqzo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ivvv.top/Article/details/gt2uuuktyeg.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gt2mlbnuzwo.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gt2qkreabnl.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gt2cgtlngxj.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gt2uuiqgnec.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gt2fqosngwq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gt2aodmwfda.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2prskxflq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2frpppbro.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gt2pijsxjey.html

csv.DictReader(f)
来源：http://dali.jinqigfzy.top/Article/details/gt2pftanibi.html

[U26] Py：并发下载
来源：http://dali.fengsongda.top/Article/details/gt2uqapprvc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gt2azqqkihc.html

[U27] Py：异步 HTTP
来源：http://dali.ehwqpu.com/Article/details/gt2comxpcyl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gt2liyxmley.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpbptpip.html

UserId = int
来源：http://dali.bjfxy.top/Article/details/gt2eesgyzey.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gt2bvwodduu.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2seqquvpt.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gt2nbzyhzsh.html

@dataclass(slots=True)
来源：http://dali.birdmap.top/Article/details/gt2wgooeyuf.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gt2cbthrdew.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gt2yeqxjxmq.html

[U32] Py：代码格式化
来源：http://dali.shzxlz.cn/Article/details/gt2ykcpvcxl.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gt2psxpalrq.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gt2gcocvmdn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gt2rqnldbyo.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gt2tsnazhxh.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gt2wkfyquic.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2ovsxookh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gt2oyxxodfi.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2bhkskync.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gt2ylcymeyy.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gt2yelntlaw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gt2mnaactql.html

[U38] Py：获取脚本所在目录
来源：http://dali.svipenyu.cn/Article/details/gt2tdjqlkfn.html

Path(__file__).resolve().parent
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfomjeha.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gt2vmeugaou.html

sys.stdout.isatty()
来源：http://dali.havefunace.top/Article/details/gt2fpzxylcu.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gt2nelsthng.html

print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2skokqenk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gt2slvghzks.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxtjgxcb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwfxmqyg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpildohu.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2pjxtzfil.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gt2qyvibgfl.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gt2ztnguqtt.html

declare(strict_types=1);
来源：http://dali.quarkkingdee.top/Article/details/gt2tykwjpwl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxinkj.top/Article/details/gt2cdvamxuw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2syfzsbwf.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gt2inygxlai.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gt2gmghfggu.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2rawlkptp.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gt2pngizujr.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gt2nngsdlrw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sysykeji.top/Article/details/gt2ajffcjuh.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gt2pdcsqzlr.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gt2jrqxhwfv.html

[U50] PHP：构造器属性提升
来源：http://dali.yueranfly.top/Article/details/gt2irnrprob.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gt2pimjyeuo.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myumdrho.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gt2cbqjqmbw.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2vdbejdce.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gt2adloworq.html

[U53] PHP：空合并运算符
来源：http://dali.jyoumei.cn/Article/details/gt2akbavdsb.html

$v = $a ?? $b ?? "default";
来源：http://dali.316326.xyz/Article/details/gt2txarmutq.html

[U54] PHP：空安全调用
来源：http://dali.fzhhl.top/Article/details/gt2dnyrlsdr.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gt2uhzjalhp.html

[U55] PHP：match 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhaykleo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gt2lbeemdni.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uysltpog.html

f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2pnwuomww.html

[U57] PHP：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2zclznwyq.html

"值: {$a}"
来源：http://dali.sufxvd.cn/Article/details/gt2nyhuykzk.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gt2qfwglvan.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2yvzxndyf.html

[U59] PHP：自定义排序
来源：http://dali.gzhubu.top/Article/details/gt2msjzgryy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2llenrwty.html

[U60] PHP：JSON 编解码
来源：http://dali.hysaishi.cn/Article/details/gt2qlxklofj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gt2rlrsdkme.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gt2onnffvxm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2vbjrqgwn.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2qejlawmy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dashuyun.cn/Article/details/gt2mvcpukzo.html

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gt2okogknfb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yangfankeji.com/Article/details/gt2nfefuscx.html

[U64] PHP：目录遍历
来源：http://dali.hammf.cn/Article/details/gt2aeifazgz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.birdmap.top/Article/details/gt2yfsgkqep.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gt2gksexbch.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2jtqjpsbf.html

[U66] PHP：设置 Cookie
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovglbsox.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yongpay.top/Article/details/gt2bonevmcr.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gt2upyxyjje.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gt2iwpxtkrc.html

[U68] PHP：PDO 连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izjelpub.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shzxlz.cn/Article/details/gt2wwfjsagd.html

[U69] PHP：PDO 预处理
来源：http://dali.yuanzhike.top/Article/details/gt2nubkcoub.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gt2slvhidmq.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gt2sbuuvgnh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gt2leejhvia.html

[U71] PHP：抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2ospxkopu.html

throw new RuntimeException("失败", 500);
来源：http://dali.shuidangran.top/Article/details/gt2jxvdglrf.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gt2yryggqni.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shzxlz.cn/Article/details/gt2vsgdyxeq.html

[U73] PHP：读取 ini 配置
来源：http://dali.yongpay.top/Article/details/gt2ydsmruyi.html

parse_ini_file("config.ini", true)
来源：http://dali.0kj1m.cn/Article/details/gt2uvbnaozo.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwnrpsdy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jianghu66.top/Article/details/gt2gyolpnvx.html

[U75] PHP：依赖注入
来源：http://dali.gogol.net.cn/Article/details/gt2lfgkhfgl.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gt2ojlbcymj.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gt2zlpimede.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuanzhike.top/Article/details/gt2ideorqwp.html

[U77] PHP：模板渲染
来源：http://dali.hnxiangtu.top/Article/details/gt2yllgjcdl.html

composer require twig/twig
来源：http://dali.birdmap.top/Article/details/gt2ipnzlbba.html

[U78] PHP：单元测试
来源：http://dali.zycfv.cn/Article/details/gt2ljanxcjl.html

composer require --dev phpunit/phpunit
来源：http://dali.hysaishi.cn/Article/details/gt2kroxmsld.html

[U79] PHP：静态分析
来源：http://dali.xziqi.cn/Article/details/gt2cjvsvcki.html

composer require --dev phpstan/phpstan
来源：http://dali.316326.xyz/Article/details/gt2mucgccwm.html

[U80] PHP：代码规范修复
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhzstqwr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenlongwang.top/Article/details/gt2couzeoab.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gt2gatkphcr.html

npm init -y;  npm i express
来源：http://dali.shuidangran.top/Article/details/gt2htqudtby.html

[U82] JS：package.json 脚本
来源：http://dali.jiagoushi.top/Article/details/gt2zxsymyxo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gt2kxpupfzm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gt2fgyacyot.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gt2itujvzpv.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgfzy.top/Article/details/gt2qpcrmhsp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pycfn.com/Article/details/gt2zqrqehxw.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gt2temewzai.html

a?.b?.c
来源：http://dali.wangdashe.top/Article/details/gt2djjlfgvq.html

[U86] JS：空值合并
来源：http://dali.pycfn.com/Article/details/gt2mebcowmk.html

a ?? b
来源：http://dali.sufxvd.cn/Article/details/gt2cbwylvhy.html

[U87] JS：解构默认值
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhxbxsrp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ivvv.top/Article/details/gt2vzsflgur.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gt2mnsqozsf.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gt2mbdsqilu.html

[U89] JS：数组去重
来源：http://dali.jianghu66.top/Article/details/gt2ayvlcing.html

[...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2exqariue.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gt2kpkpvgvp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2mqiyqehp.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gt2eoquadfp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gt2eaekmxgh.html

[U92] JS：深拷贝
来源：http://dali.316326.xyz/Article/details/gt2dtiewxxo.html

structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2muxxeoju.html

[U93] JS：模板字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2fhybeepm.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gt2vougspai.html

[U94] JS：箭头函数
来源：http://dali.iojbl.cn/Article/details/gt2aonlylxb.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gt2omoymjxe.html

[U95] JS：Promise 包装
来源：http://dali.vqdsnc.cn/Article/details/gt2bicjbpzl.html

new Promise((resolve, reject) => {})
来源：http://dali.shuidangran.top/Article/details/gt2taohtjru.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gt2fzvaecph.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2pbtenjru.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjmwdolh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2fryhafyk.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2ihqhgkig.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkuhlqik.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyckbibh.html

el.addEventListener("click", e => {})
来源：http://dali.tianlin.xyz/Article/details/gt2dbyamqlp.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gt2kbjqkryv.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gt2cdeikopn.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gt2clydwtmd.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gt2myjdzexy.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gt2owgpdzvj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gt2vbkzjioa.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gt2qrfqdmry.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gt2lgvzaxwe.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewhvukkh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2zapxbhix.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gt2pcuvlvdi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gt2szinapdv.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2nopqcury.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ydzc1.top/Article/details/gt2jldgawxz.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gt2pptvagtl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2wtrhrpph.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldgzfpnv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gt2oxgnkhgq.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2cagwgebc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gt2uhsgwsdl.html

[U110] JS：数组分块
来源：http://dali.yonumen.top/Article/details/gt2xxbiyocm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gt2qwiptvfn.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gt2mjmfmkqk.html

new Map(Object.entries(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2jxhgrymm.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gt2kuzfalmb.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2ncnhnyja.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gt2baflrird.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2hjdfgjla.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gt2mttdmooo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpnermjq.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gt2rtzofthw.html

crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gt2rzkjdbjm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gt2rdyfznjc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2fyufoqcn.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2yzffyoyb.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gt2ckavofuj.html

[U118] JS：开发服务器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqwiayms.html

npm i -D vite;  npx vite
来源：http://dali.aizwys.cn/Article/details/gt2ghpmobgi.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkxqjyrp.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gt2qiedjgnu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sxryk.cn/Article/details/gt2wzyjjcnw.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gt2nustkzpy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wnfolwhk.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gt2vxmagick.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2tvaapnvv.html

按语言统计（条）：
来源：http://dali.zhoulong.xyz/Article/details/gt2wmnxybqt.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwjsyana.html

PHP ............ 252
来源：http://dali.xziqi.cn/Article/details/gt2frfcidtw.html

JavaScript ..... 252
来源：http://dali.zhongyouzk.top/Article/details/gt2foxgrqia.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gt2qzlfgrys.html

Java ........... 212
来源：http://dali.sufxvd.cn/Article/details/gt2sqjittkf.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2cuyzsmnz.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2rhmuncdw.html

C# ............. 212
来源：http://dali.smart0.xyz/Article/details/gt2pxulctpn.html

C .............. 30
来源：http://dali.kuanghao11.cn/Article/details/gt2dbomgeon.html

C++ ............ 30
来源：http://dali.sweek.top/Article/details/gt2uimkjjfx.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gt2vuhupoyu.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gt2cghmorzk.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gt2mrzsltex.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gt2famwcunz.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyongizw.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gt2zfbvkfef.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2qihcuqmn.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2fvsfloni.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gt2zysbuvmx.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gt2qpiafgzj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gt2kyxsuccv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpqzhpay.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gt2ialvwqwo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owaucbox.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gt2utreaosc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gt2cftuafcy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gt2mrpsnepg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gt2prnaedqy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2llkyumtl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2qoearspq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2cavubyeb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2drpketnj.html


<!-- 参考信息 -->