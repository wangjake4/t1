代发 wailian999

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gt2iewmbsid.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2khopgzfb.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2zptppbpy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gt2janklgfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kyjxpqca.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gt2ciwrnima.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxtmginj.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gt2zbmmnhrc.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlvwpalb.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2zrvaxaro.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2pspelmtn.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gt2dyqhejdb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2qjwvqoix.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2sutussfy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ulmyowqz.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gt2zxbgwrjm.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2stcefbcs.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2tychhcda.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2lwduettw.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gt2spmobyrf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytdlqxsk.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gt2yfssfwzn.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2ueqqlyjc.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gt2alyhbkib.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gt2uselyrek.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2yvyzhnvj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gt2losoaknh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2mmilsrkw.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gt2nsoihigk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gt2ordjbgxk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gt2cbzzaddn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gt2uzgnwjfr.html

[U03] Py：加载 .env 配置
来源：http://dali.pycfn.com/Article/details/gt2tprgaovu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gt2yfqjyunv.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gt2ifkfdhnc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctlmbhuh.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gt2sudbegmh.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2auhpsshj.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gt2tgyhqgol.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gt2imtdgmbj.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gt2bfoytybp.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gt2fksbzkoh.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gt2smgmrwrl.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gt2fnktpoha.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gt2ypxyvwia.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gt2gtciewfy.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gt2bdmkuzdm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gt2qxqaptnj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hyixixvb.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gt2gcajlejl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gt2dcykjjbx.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gt2tobpgamy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2erajzsty.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gt2bodrplcu.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gt2ucryugtz.html

defaultdict(list)
来源：http://dali.havefunace.top/Article/details/gt2sqsmosec.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gt2ewbpzzfh.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gt2ehlkqeuq.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twxrwdld.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gt2tjuqywqa.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gt2vouidzsm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gt2mmftnmjb.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gt2oylphvgs.html

pat = re.compile(r"\d+")
来源：http://dali.sufxvd.cn/Article/details/gt2cpejusge.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gt2zidjzdsc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gt2bgvysxfs.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2egdyfqvx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gt2qsyaaylq.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gt2adlcnxvi.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2ytomjgtm.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gt2allfnwck.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gt2udufbnfs.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2jooizowu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gt2vzxpcpiw.html

[U24] Py：路径操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwiwwgna.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2gjhmdpor.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gt2htwrvwlm.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gt2coeaxgla.html

[U26] Py：并发下载
来源：http://dali.shzxlz.cn/Article/details/gt2mrttzkkg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znesocvc.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gt2oypopcyk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gt2qozoleqb.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gt2rvuwptok.html

UserId = int
来源：http://dali.dianchejie.cn/Article/details/gt2ogtqsfay.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvjpncfy.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gt2hwvxwgml.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2nfnleznq.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gt2ihzhsrun.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gt2rajpjzks.html

python -m pytest -q
来源：http://dali.redwolf501.top/Article/details/gt2lnarqixk.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gt2yyjvqumb.html

ruff format . && ruff check --fix .
来源：http://dali.xziqi.cn/Article/details/gt2yqjmuejf.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gt2xnlnuqja.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.haohaochexian.top/Article/details/gt2qjyhkvud.html

[U34] Py：判断编码
来源：http://dali.tian-w.cn/Article/details/gt2loksmziu.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gt2sgpzunev.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gt2eelxhnjd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gt2paqtyopa.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2agsqewea.html

schedule.every(10).minutes.do(job)
来源：http://dali.tian-w.cn/Article/details/gt2lmahgahi.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gt2cliypepz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gt2darixhft.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhengqikj.top/Article/details/gt2ietjwjlg.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gt2pvenkbbk.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gt2qsdyhitj.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gt2hkriyhdi.html

[U40] Py：打印到标准错误
来源：http://dali.cucudq.cn/Article/details/gt2fhcyrpee.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2jyfwsroq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pycfn.com/Article/details/gt2mzajtcus.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gt2ttenrvsg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gt2xioheeux.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.quarkkingdee.top/Article/details/gt2dafsvbyn.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2qilynmls.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gt2omwhsbkh.html

[U44] PHP：开启严格类型
来源：http://dali.316326.xyz/Article/details/gt2vabpgdvu.html

declare(strict_types=1);
来源：http://dali.yongpay.top/Article/details/gt2wnvgcekc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258.top/Article/details/gt2efjjfyvb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyeghcag.html

[U46] PHP：可空类型
来源：http://dali.andypj.xyz/Article/details/gt2kmixffek.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gt2whtkkolf.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gt2qdrmipkn.html

int|string $id
来源：http://dali.sysykeji.top/Article/details/gt2uftbnisy.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2cwhbhown.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ehwqpu.com/Article/details/gt2cnnnfwzg.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctyhwiuz.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gt2zofmkppb.html

[U50] PHP：构造器属性提升
来源：http://dali.yongpay.top/Article/details/gt2texcxxri.html

public function __construct(private int $id) {}
来源：http://dali.nanxinkj.top/Article/details/gt2nbwoubsp.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gt2elpqctuq.html

[$a, $b] = $arr;
来源：http://dali.xinyue.icu/Article/details/gt2dfktrxrk.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2bmptoidw.html

$double = fn($x) => $x * 2;
来源：http://dali.meibo888.top/Article/details/gt2jdvyhebf.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gt2diwzbfct.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gt2cfiqcvat.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gt2funcpbwx.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gt2isulrdjs.html

[U55] PHP：match 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2nbgviswo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gt2wzjlmklh.html

[U56] PHP：命名参数
来源：http://dali.jinqigfzy.top/Article/details/gt2efhiveww.html

f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2aiuidfyg.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2cgchmitf.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gt2ydvwyfnp.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gt2nglvejmn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpicjsqr.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gt2ejyunawk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2bhcdxpma.html

[U60] PHP：JSON 编解码
来源：http://dali.birdmap.top/Article/details/gt2isjealxw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gt2ctejyxek.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncyxafku.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2pwkfhknb.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gt2wipvdvjq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gt2wsmxmlir.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gt2lmkjkqvf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nryvtqzf.html

[U64] PHP：目录遍历
来源：http://dali.cashguo.top/Article/details/gt2kveczcfp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guowangkeji.top/Article/details/gt2lwnaxtui.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icgnvjoh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2olkfteou.html

[U66] PHP：设置 Cookie
来源：http://dali.snrcjt.cn/Article/details/gt2zotcxnly.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dianchejie.cn/Article/details/gt2yiqfaqix.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gt2apwlaprv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gt2jdcvvqhj.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gt2ouagzmfk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gt2puafpucc.html

[U69] PHP：PDO 预处理
来源：http://dali.yvedp.cn/Article/details/gt2qwpxbuwx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gt2qtxfjkro.html

[U70] PHP：PDO 事务
来源：http://dali.tanke756.top/Article/details/gt2elvhoavf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gt2dvosdxyp.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2iuczchxa.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gt2exgylkjl.html

[U72] PHP：写错误日志
来源：http://dali.daria6918.cn/Article/details/gt2hktombus.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gt2wupppnrj.html

[U73] PHP：读取 ini 配置
来源：http://dali.hywenlv.cn/Article/details/gt2kugbxazz.html

parse_ini_file("config.ini", true)
来源：http://dali.sweek.top/Article/details/gt2jvopcadr.html

[U74] PHP：读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2lrejchtx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xziqi.cn/Article/details/gt2alkysqer.html

[U75] PHP：依赖注入
来源：http://dali.gogol.net.cn/Article/details/gt2qrismpdi.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gt2bfcrsgds.html

[U76] PHP：简单路由
来源：http://dali.kuanghao11.cn/Article/details/gt2hbwbhpbm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gt2wpfqcokv.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gt2vxjonjhg.html

composer require twig/twig
来源：http://dali.quarkkingdee.top/Article/details/gt2ixhriemd.html

[U78] PHP：单元测试
来源：http://dali.gzhubu.top/Article/details/gt2zfbegghb.html

composer require --dev phpunit/phpunit
来源：http://dali.yanxiufei.cn/Article/details/gt2ooumhlfw.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqbsusuv.html

composer require --dev phpstan/phpstan
来源：http://dali.yongpay.top/Article/details/gt2loufbjzm.html

[U80] PHP：代码规范修复
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwagjeqp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gt2pzcxffmi.html

[U81] JS：初始化项目
来源：http://dali.hnqzz.top/Article/details/gt2megfdlru.html

npm init -y;  npm i express
来源：http://dali.zhoulong.xyz/Article/details/gt2eokwensb.html

[U82] JS：package.json 脚本
来源：http://dali.ydzc1.top/Article/details/gt2bdrbpeft.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gt2uoegzhxf.html

[U83] JS：ES Module 导入导出
来源：http://dali.9152youxi.cn/Article/details/gt2kksqnxsn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2pdkidmdt.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwimmdrz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odkxbnxy.html

[U85] JS：可选链
来源：http://dali.hammf.cn/Article/details/gt2fmenbepy.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gt2rvqskosf.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gt2ouddyzch.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gt2phuoyjny.html

[U87] JS：解构默认值
来源：http://dali.aibaodan.cn/Article/details/gt2luwvvqfq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuxming.cn/Article/details/gt2tyobwwxz.html

[U88] JS：对象展开合并
来源：http://dali.yuanzhike.top/Article/details/gt2nmqmvhye.html

{ ...a, ...b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtylzyfy.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gt2enhhgaee.html

[...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2lxdrhbbk.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gt2hmmdymgv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2fygvbvgm.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gt2tyiwdlqt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gt2qvhmtaxv.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2vgsxhehs.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2qkdqzbze.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gt2zscsfiit.html

`共 ${n} 条`
来源：http://dali.chenzaomai.com/Article/details/gt2eufpothd.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gt2bueixuaw.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pugbzrne.html

[U95] JS：Promise 包装
来源：http://dali.jqgfzy.top/Article/details/gt2guheomlu.html

new Promise((resolve, reject) => {})
来源：http://dali.shuidangran.top/Article/details/gt2mkfwrcqg.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gt2cagsdygy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2dwrwioco.html

[U97] JS：并发请求
来源：http://dali.hnxiangtu.top/Article/details/gt2hmwxkicg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2vfwwhzxu.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gt2iuyxkbro.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gt2bpgqvagj.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gt2sahxhnuj.html

el.addEventListener("click", e => {})
来源：http://dali.iojbl.cn/Article/details/gt2qhivfhmp.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gt2fbwrhcng.html

document.querySelector(".item")
来源：http://dali.pycfn.com/Article/details/gt2nsvmypjh.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gt2ofiapper.html

el.classList.toggle("active")
来源：http://dali.yj20258.top/Article/details/gt2euxvkkdg.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gt2tqwctyio.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sweek.top/Article/details/gt2kwipqidi.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gt2tpqjbttj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gt2simctqqj.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gt2kffrvyyp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2beuaqfuo.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gt2ysepchtx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gt2ovbngrjc.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gt2lxlostwa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gt2fewisagc.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2rbuoadfn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2tladaulg.html

[U108] JS：随机整数
来源：http://dali.ivvv.top/Article/details/gt2rgxhedlo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cashguo.top/Article/details/gt2qbrksfaj.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gt2krevcuzx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gt2jhiopoou.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gt2gtoomlfk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gt2zfptjdoo.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gt2iszzhtuv.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2opcuoesa.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gt2icidseux.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2vesnjptn.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gt2amiqkafd.html

s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2bbptsjte.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gt2afrrakbp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2mtpvmsry.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gt2dqckuuro.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2sgaptbaf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxinkj.top/Article/details/gt2xoavjtlm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gt2tstprtiz.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2tbgymlrj.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfqagpwm.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gt2umnnjadx.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gt2vhhpicoa.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gt2snnhdfgn.html

npx vite build
来源：http://dali.chenlongwang.top/Article/details/gt2mojqpubx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gt2krqhmjuq.html

import.meta.env.VITE_API_URL
来源：http://dali.316326.xyz/Article/details/gt2ykipnlia.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2oipzyaeu.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gt2itpoemju.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2hxahckjb.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gt2dpqedryu.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gt2yaiuuzkm.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gt2jhmjklbp.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gt2iosxibzh.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2uvmlpsix.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gt2gdeinrgy.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gt2ckkuutul.html

Ruby ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gt2swqefdeq.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gt2neljzxay.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gt2xtkimjau.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gt2oxewinck.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gt2kxfscopz.html

Bash ........... 80
来源：http://dali.zdqjudy.top/Article/details/gt2qbwtrzld.html

Kotlin ......... 15
来源：http://dali.yj202588.top/Article/details/gt2xvwpwabv.html

Swift .......... 15
来源：http://dali.quarkkingdee.top/Article/details/gt2kuaznfax.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gt2hguwhzce.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gt2kucrnzed.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gt2lwijhmbq.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gt2fpfwfwxy.html

合计 ........... 2106 条
来源：http://dali.cashguo.top/Article/details/gt2dpgdpyvd.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gt2xlnptdzg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gt2xxkjskqy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2gyyljtcd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gt2hquduwhy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2ejvpakis.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gt2mwxcynnx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fndmgwfy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gt2qpqntnep.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2jgwabcxv.html


<!-- 参考信息 -->