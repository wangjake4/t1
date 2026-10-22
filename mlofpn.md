代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gt2hxfwdtff.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdackfrs.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2czhgmebx.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gt2fesqnkyz.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gt2pkmnezgx.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2zpzzwgol.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gt2nqbctbum.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2onsiwuje.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2hrrdfnzf.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2ymomyxjt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2mkzedpzc.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2geaxoazn.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gt2hpasufcb.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2rsimwvqm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gt2notleivz.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gt2iiphsuqn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gt2hhvnlwea.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gt2zjfsahnk.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gt2jfxdccbr.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gt2atvbiukf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gt2ejwaykke.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2acvqmert.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gt2emnkvjon.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vabwtpdy.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gt2bjwdlsbt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gt2okqlmvqo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gt2jxhganag.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhcquvsf.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gt2gonpbywn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqaspubh.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gt2yedxlpfm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssivxdiu.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gt2vgnvxwvl.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gt2tkpzezby.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gt2ewfgakul.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gt2ispatygk.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gt2dppndfxd.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gt2ombnmxxx.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gt2bvuyzyzd.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gt2icasnntn.html

[U09] Py：字典取最大值的键
来源：http://dali.redwolf501.top/Article/details/gt2zwrahgxk.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gt2vrozbyec.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gt2ngaifkzm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gt2vhtljlkv.html

[U11] Py：生成器表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcactugd.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gt2fhwbggoa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nwbrower.top/Article/details/gt2vqkyuupo.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2jqlyauwu.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gt2vrxnjgpc.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gt2ldkqmnpr.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gt2stzvmozd.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gt2ljljyaip.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gt2bgiqqacb.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gt2yxanyboi.html

[U16] Py：命令行参数解析
来源：http://dali.aibaodan.cn/Article/details/gt2tnwbuwmm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gt2xnxkuwkj.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gt2cemlliox.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gt2zuqizgfn.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzldvmuc.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gt2oduayzpx.html

[U19] Py：正则替换带回调
来源：http://dali.cqqwz.cn/Article/details/gt2zvsymclp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yangfankeji.com/Article/details/gt2gusuymfa.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gt2bruddyvd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gt2holjkwic.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gt2ilgpybni.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gt2uvitehhc.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gt2fmtdnvwy.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gt2vjfaefwv.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gt2pkwrsdyg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gt2pgupqgju.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gt2kydyhgnr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2juvrqwkf.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gt2hgdhurfq.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gt2scobbclj.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gt2gnbokalm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxinkj.top/Article/details/gt2pakzgjtj.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gt2gnsipzah.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guannengcc.top/Article/details/gt2mxeofktj.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gt2iqatjkmb.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smlhhttf.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gt2zvwbwcrz.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gt2dsdetpix.html

[U30] Py：数据类
来源：http://dali.yonumen.top/Article/details/gt2gbxcafxp.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gt2kjerkptq.html

[U31] Py：单测
来源：http://dali.sufxvd.cn/Article/details/gt2nfnqjslw.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gt2rxppgyct.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gt2ryqtcapf.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2avzhtvob.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gt2wcgvqrbb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gt2ximvmagb.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gt2rjrodedm.html

chardet.detect(raw)
来源：http://dali.birdmap.top/Article/details/gt2lhutxohg.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gt2mtgefwpd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gt2fljlysjh.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gt2ykuhbgzo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjsjebe.html

[U37] Py：读写 Excel
来源：http://dali.zdqjudy.top/Article/details/gt2vogoytce.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ivvv.top/Article/details/gt2awnxaefk.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gt2ohzjxnee.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gt2lwsayhgz.html

[U39] Py：判断是否在交互环境
来源：http://dali.redwolf501.top/Article/details/gt2vyenrexo.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvchoipi.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gt2yohcfazt.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2cpguebbt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gogol.net.cn/Article/details/gt2hbfsmavw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gt2cxerxcag.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gt2heodmrtv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gt2jfcryuif.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2msjxymjv.html

namespace App\Http;
来源：http://dali.redwolf501.top/Article/details/gt2evlnwdys.html

[U44] PHP：开启严格类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgbbgzbr.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gt2eijiclcq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gt2zkrzrofj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2wzpgvrta.html

[U46] PHP：可空类型
来源：http://dali.xuanzx.com/Article/details/gt2tgmanpyw.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gt2eefmdrst.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufjojieq.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gt2muatrrnp.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gt2wvhufkpp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xziqi.cn/Article/details/gt2nlcgtoso.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gt2lcouwvib.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gt2xcebvasw.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gt2iolahovp.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vfznddoi.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyqtmihf.html

[$a, $b] = $arr;
来源：http://dali.gogol.net.cn/Article/details/gt2qpuvmngr.html

[U52] PHP：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gt2uwrbjzmt.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gt2eusgjfae.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gt2liagolnb.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyowarnd.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gt2jnytyehe.html

$obj?->method()
来源：http://dali.zhongyouzk.top/Article/details/gt2kdhlwgqz.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2uqsyrpkm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gt2daozcsbh.html

[U56] PHP：命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhrnjgld.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gt2xeegnsqf.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2fkrzwpeq.html

"值: {$a}"
来源：http://dali.fzhhl.top/Article/details/gt2wetwfdnd.html

[U58] PHP：数组三件套
来源：http://dali.cashguo.top/Article/details/gt2ghhepnns.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2uylwgrra.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gt2ofhxbqix.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2uexwzisd.html

[U60] PHP：JSON 编解码
来源：http://dali.tianlin.xyz/Article/details/gt2uigklxhg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gt2ccjoercd.html

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gt2lupumyic.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2hsxcujlu.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gt2ngpwphjl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.svipenyu.cn/Article/details/gt2qsrdkkqr.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gt2roaedrpj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gt2oedivkfe.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2adpnkxok.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gt2xpcsmqvi.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gt2inakhbqk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zglqiqjq.html

[U66] PHP：设置 Cookie
来源：http://dali.yongpay.top/Article/details/gt2bcnplqop.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2hbzpvfhl.html

[U67] PHP：处理文件上传
来源：http://dali.snrcjt.cn/Article/details/gt2emfxsrwr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhongyouzk.top/Article/details/gt2stnavlnv.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gt2hjmjoxco.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbajmtty.html

[U69] PHP：PDO 预处理
来源：http://dali.svipenyu.cn/Article/details/gt2vqemdqtp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gt2hbuqdrrz.html

[U70] PHP：PDO 事务
来源：http://dali.fengsongda.top/Article/details/gt2ymhnydkw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.0kj1m.cn/Article/details/gt2yzccrloo.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2tswidohk.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gt2reoqeaxm.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kihbzdko.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gt2ppzrxqfs.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gt2skxqqhkf.html

parse_ini_file("config.ini", true)
来源：http://dali.redwolf501.top/Article/details/gt2jryymokt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpafqxzz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuejugvu.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gt2peeuhrik.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gt2otfhnxge.html

[U76] PHP：简单路由
来源：http://dali.yongpay.top/Article/details/gt2utpfphzb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pycfn.com/Article/details/gt2kkthvrtn.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gt2ahigguvy.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gt2mdhrpjek.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2nmytgvws.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gt2gxegpjmm.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gt2tkvwcgcf.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gt2viunhyot.html

[U80] PHP：代码规范修复
来源：http://dali.jqgfzy.top/Article/details/gt2wqmpdzee.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.9152youxi.cn/Article/details/gt2qowpjxvn.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gt2veqmwudl.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gt2ybvxufrz.html

[U82] JS：package.json 脚本
来源：http://dali.tianlin.xyz/Article/details/gt2iyyvjlax.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cheryme.top/Article/details/gt2thhiohpb.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gt2fpqcoqfs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqeolktk.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258888.top/Article/details/gt2edtozjef.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gt2hblfodiy.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gt2czvgnybl.html

a?.b?.c
来源：http://dali.dashuyun.cn/Article/details/gt2gekgvfin.html

[U86] JS：空值合并
来源：http://dali.0kj1m.cn/Article/details/gt2qswhbnsi.html

a ?? b
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqayghwn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2drtmuheu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhengqikj.top/Article/details/gt2zzfkzfhu.html

[U88] JS：对象展开合并
来源：http://dali.andypj.xyz/Article/details/gt2srqpswpw.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gt2etyhssst.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gt2qmuyojza.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2tzrwxuog.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2actktluy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2ggliysbe.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2asnabfmn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gt2xiroufkq.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gt2jhhskvxi.html

structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2petcloqx.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gt2aknlixas.html

`共 ${n} 条`
来源：http://dali.haohaochexian.top/Article/details/gt2dcrbozpq.html

[U94] JS：箭头函数
来源：http://dali.wangdashe.top/Article/details/gt2nthlutqu.html

const double = x => x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gt2qkhnuzyi.html

[U95] JS：Promise 包装
来源：http://dali.tian-w.cn/Article/details/gt2nixqpegv.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gt2lyamtbkb.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gt2mytawgfm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2gsvxgchc.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gt2ftsvfhlr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbckdali.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2gjrtolex.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gt2kzwyxmgf.html

[U99] JS：事件监听
来源：http://dali.dianchejie.cn/Article/details/gt2punsnqbi.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gt2dopgtmje.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gt2cvisbgry.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgluejxs.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gt2murqxuoi.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gt2pnnweseq.html

[U102] JS：本地存储
来源：http://dali.quarkkingdee.top/Article/details/gt2aiditkit.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuxming.cn/Article/details/gt2sgwhukts.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gt2fxbhozvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhuvvaac.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gt2ysbbfhkd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2vcholvur.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2wceufnnf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gt2ccrzgjbt.html

[U106] JS：日期格式化
来源：http://dali.ehwqpu.com/Article/details/gt2jzotupoi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gt2gqhmtkrp.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2bekxtkca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lilcmrsq.html

[U108] JS：随机整数
来源：http://dali.hywenlv.cn/Article/details/gt2urhaiwcg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258.top/Article/details/gt2yoqbkplj.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gt2dopspkvy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2ceacyobv.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gt2txybamvr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gt2xgqfdkeg.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gt2zpirqphh.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2lhckbqfd.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gt2epumfxdd.html

"7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2gdlxytvz.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdzaslvp.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2hkcrgcfw.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2ztnplezz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2zcyedbnj.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2ixzuzpbm.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2tzhzckbq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gt2wgmwwuhl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2qwvhrcgs.html

[U117] JS：单元测试
来源：http://dali.sufxvd.cn/Article/details/gt2rwrmomqi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehqsqtto.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gt2emuqiqet.html

npm i -D vite;  npx vite
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajxxuxyf.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gt2bopoxreo.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gt2foillken.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gt2tuaoakto.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gt2khaazbur.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2syhnwpfe.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gt2saewedgn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jvuarzgi.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2gdxkqxig.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gt2jprmgjli.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gt2vazalsdg.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gt2qtkdodyb.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gt2zmpdiknw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpcqkzt.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gt2xovhddaz.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2wlorqtgk.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gt2vrdjgpkb.html

C .............. 30
来源：http://dali.tianlin.xyz/Article/details/gt2nvrendlq.html

C++ ............ 30
来源：http://dali.iojbl.cn/Article/details/gt2aegmiice.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufwdvjbk.html

Bash ........... 80
来源：http://dali.snrcjt.cn/Article/details/gt2acpjlxuq.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhotlxck.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpowlev.html

Lua ............ 10
来源：http://dali.yongpay.top/Article/details/gt2hjuqhklr.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfuqbqjq.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2wueealbg.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2tmdlgnis.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gt2sucugdgp.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wahshpsw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gt2zgkffdgo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2oibcsduq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2eexfafjl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eahtwudm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gt2mfaaxzeh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gt2bovsfloz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2otggimam.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gt2herltkze.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2jzlbuddw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gt2sggwreiv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fryvcjwt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2ofgrqdnf.html


<!-- 参考信息 -->