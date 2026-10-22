代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qmmilxzf.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2seesaizk.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2puasjgzx.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gt2sivjdgcx.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2hzmcsgpc.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2icywbgoe.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2ijcwfufz.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2wkpfiqnv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gt2opquzdli.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2crukkznb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gt2mqccwrxn.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjyuexua.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gt2rdlbkskl.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2nrzydcna.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2euwkahln.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gt2mrbannmw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gt2hzsksosq.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gt2avcnheqh.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2kdrpyfgs.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gt2yklhreav.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gt2npsihyea.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2nesonivn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2lskhaosn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2jnnuyrbz.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gt2itrrprag.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gt2nvchqsxo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2etlxfvnj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gt2nrzrkqrf.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gt2hvrvxydn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gt2vdzroprp.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gt2urktbwcu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gt2bfialuxt.html

[U05] Py：列表去重且保序
来源：http://dali.guannengcc.top/Article/details/gt2vpvjngro.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2rcfcpsnp.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2rhjvqzmz.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gt2suogdvod.html

[U07] Py：反转字典键值
来源：http://dali.yueranfly.top/Article/details/gt2owyyngli.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gt2yfsfafyc.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gt2ctikhrfq.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aoqtdplg.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2qivefyxs.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gt2gxdqpwea.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gt2fpstxfvf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gt2ngtptqga.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gt2uvivyjor.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcnblqzd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gt2dgrfpyva.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gt2rzrruygw.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gt2yeaqjmhi.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gt2nvszruqo.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gt2ngksyhpg.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2ntgbjdtc.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gt2rnraolmd.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gt2yrgixzxc.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gt2glbpyyse.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxtrdjkg.html

[U17] Py：初始化日志
来源：http://dali.aizwys.cn/Article/details/gt2pefuoehn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gt2fvprxblz.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gt2blyohmyq.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2smcslofc.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gt2btawxjwa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gt2cigxpekr.html

[U20] Py：缓存函数结果
来源：http://dali.316326.xyz/Article/details/gt2lmnhagjo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imftzhzl.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gt2fgatsuiz.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gt2gdgiqlre.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gt2icqnnubk.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gt2zuyxlyyp.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gt2hhmuvdpm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gt2ictzzdns.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gt2hyfpawdh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gt2wdaaxczx.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjrxyeoq.html

csv.DictReader(f)
来源：http://dali.yj20258.top/Article/details/gt2axtssblj.html

[U26] Py：并发下载
来源：http://dali.feifeiyinyue.top/Article/details/gt2joyzpspt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qiygblsu.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otesnmke.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gt2paqnvbml.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gt2fiwgghud.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gt2dspfglcx.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gt2qmrvagep.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gt2avklgamh.html

[U30] Py：数据类
来源：http://dali.zhengqikj.top/Article/details/gt2ksiabnhi.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gt2wybgufcc.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gt2aztztzdx.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gt2ktamzbgk.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gt2qjrjxvmt.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2ylrxtipp.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvmplknj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gt2hcftyapc.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozgownsb.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gt2diehxjsz.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gt2wbtgoljw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gt2uiyohfxv.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gt2frdslund.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gt2ucwxcmru.html

[U37] Py：读写 Excel
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsaiwsue.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gt2ehephfvg.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gt2zonisoly.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gt2zwbnjzwa.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2zuralwwr.html

sys.stdout.isatty()
来源：http://dali.gogol.net.cn/Article/details/gt2iahjioyk.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2iatuwfpn.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmbljpnk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkvyanmr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvmortdr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cashguo.top/Article/details/gt2noazvjgr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gt2afheifnl.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afwkulbz.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gt2kgovehfv.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gt2blkyabep.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gt2odksdjvz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gt2brshzhuh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2lkqykadz.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gt2lnkwidfk.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gt2qmsipjjr.html

[U47] PHP：联合类型
来源：http://dali.vqdsnc.cn/Article/details/gt2dxycqffz.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gt2leaeyhzm.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gt2myxmsdqu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pqistqyz.html

[U49] PHP：只读属性
来源：http://dali.yuxming.cn/Article/details/gt2lzrthcox.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gt2ttsvdkot.html

[U50] PHP：构造器属性提升
来源：http://dali.guowangkeji.top/Article/details/gt2awwtxect.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gt2ugbykmcg.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktyreogc.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gt2tauctgpq.html

[U52] PHP：箭头函数
来源：http://dali.ybcxt.top/Article/details/gt2pndhfbxn.html

$double = fn($x) => $x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kassxztk.html

[U53] PHP：空合并运算符
来源：http://dali.guannengcc.top/Article/details/gt2neflxtxn.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gt2fswucucf.html

[U54] PHP：空安全调用
来源：http://dali.gaohongyu789.top/Article/details/gt2wtgbjdsz.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gt2dymtlois.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2edaosesu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2udypgsrv.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2tjpaakfp.html

f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2setoidqg.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2laacfzjh.html

"值: {$a}"
来源：http://dali.zhengqikj.top/Article/details/gt2fkzhottv.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gt2azjvunpl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gt2ltzqspgs.html

[U59] PHP：自定义排序
来源：http://dali.0kj1m.cn/Article/details/gt2ezgxdvuq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gt2vipydyuq.html

[U60] PHP：JSON 编解码
来源：http://dali.yj202588.top/Article/details/gt2lbotkwps.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cucudq.cn/Article/details/gt2luybkkzz.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agiizpeu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2bivbjrem.html

[U62] PHP：日期对象
来源：http://dali.aibaodan.cn/Article/details/gt2nsfsfucc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.smart0.xyz/Article/details/gt2ajnzpcfb.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gt2esourflj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gt2pmmwfbia.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gt2gdehqfgz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigufen.top/Article/details/gt2liocndrz.html

[U65] PHP：会话
来源：http://dali.yanxiufei.cn/Article/details/gt2rsddvwrl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2nahtyrem.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szzoavax.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2ubjxhfwc.html

[U67] PHP：处理文件上传
来源：http://dali.hammf.cn/Article/details/gt2buvwguau.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cucudq.cn/Article/details/gt2ououydeh.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gt2hhoerhow.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gt2deymbwvb.html

[U69] PHP：PDO 预处理
来源：http://dali.guowangkeji.top/Article/details/gt2xmwtukwr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfvmmvuq.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jndqtjgi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gt2wacwonqm.html

[U71] PHP：抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2wbycgdmp.html

throw new RuntimeException("失败", 500);
来源：http://dali.haohaochexian.top/Article/details/gt2hwumyuio.html

[U72] PHP：写错误日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkgbupmr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gt2uoieuvsj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pehbjmoq.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gt2neekrqet.html

[U74] PHP：读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2xaxyoyvu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangshuangyany.cn/Article/details/gt2krkvcnya.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gt2rmqfcint.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gt2rzyblsyo.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwjljjnr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gzhubu.top/Article/details/gt2djhpjiku.html

[U77] PHP：模板渲染
来源：http://dali.guowangkeji.top/Article/details/gt2nmmrqtff.html

composer require twig/twig
来源：http://dali.zhengqikj.top/Article/details/gt2nfytxzmz.html

[U78] PHP：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybokehzo.html

composer require --dev phpunit/phpunit
来源：http://dali.daria6918.cn/Article/details/gt2opjlnbbh.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gt2mhwoutlv.html

composer require --dev phpstan/phpstan
来源：http://dali.mhx1999.top/Article/details/gt2umphazjp.html

[U80] PHP：代码规范修复
来源：http://dali.jqgfzy.top/Article/details/gt2nzkjqqub.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jlsjyb.cn/Article/details/gt2kssdysby.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gt2twrpgyic.html

npm init -y;  npm i express
来源：http://dali.0kj1m.cn/Article/details/gt2bbbrqsxa.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gt2vlovdczp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gt2luxhclfe.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gt2tampsktn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gt2nicqvfmw.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gt2gjzzfjmj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdoxcjoi.html

[U85] JS：可选链
来源：http://dali.xinyue.icu/Article/details/gt2iftjabpl.html

a?.b?.c
来源：http://dali.hnqzz.top/Article/details/gt2cqjuceet.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gt2ctzqvbur.html

a ?? b
来源：http://dali.guannengcc.top/Article/details/gt2zqbzvntx.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gt2jrrtyowr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.c1oappe.top/Article/details/gt2hmygfznc.html

[U88] JS：对象展开合并
来源：http://dali.sweek.top/Article/details/gt2ohelzaec.html

{ ...a, ...b }
来源：http://dali.xylfe.cn/Article/details/gt2mavrogds.html

[U89] JS：数组去重
来源：http://dali.vqdsnc.cn/Article/details/gt2bvglljcr.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2nwdyjqpk.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gt2fwjfikoz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2wbxddccx.html

[U91] JS：对象键值遍历
来源：http://dali.wangdashe.top/Article/details/gt2nbczkvlv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhixingplan.top/Article/details/gt2zvbtpwgp.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gt2ktgynzeh.html

structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2qnouxqxd.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gt2jaqemwln.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gt2mmkxzikv.html

[U94] JS：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgglcccb.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2aapczsgc.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gt2gdawipoj.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2ugaprchj.html

[U96] JS：async/await 与异常
来源：http://dali.smart0.xyz/Article/details/gt2srfkjwvx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2svriikqn.html

[U97] JS：并发请求
来源：http://dali.birdmap.top/Article/details/gt2vybmroef.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzuvqvbf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zycfv.cn/Article/details/gt2mwvdilxw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hysaishi.cn/Article/details/gt2keuavjui.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gt2pqsoxtqa.html

el.addEventListener("click", e => {})
来源：http://dali.yvedp.cn/Article/details/gt2lenjpred.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gt2fkrnrvvg.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gt2rvhhuooz.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gt2gjheeczc.html

el.classList.toggle("active")
来源：http://dali.smart0.xyz/Article/details/gt2qqzfnaoo.html

[U102] JS：本地存储
来源：http://dali.yangfankeji.com/Article/details/gt2xnwefqcv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyrlwapd.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gt2ehjmqrjy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hammf.cn/Article/details/gt2zksbsarn.html

[U104] JS：防抖
来源：http://dali.fengsongda.top/Article/details/gt2oirvezqj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2rebwybwj.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gt2bdsfbglx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gt2lfljrkpk.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2qcybvfug.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gt2lkajkfyt.html

[U107] JS：数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2iyfnzuhx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2fqqournw.html

[U108] JS：随机整数
来源：http://dali.fzhhl.top/Article/details/gt2gaarwjzy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tianlin.xyz/Article/details/gt2opowmnqs.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gt2hvamdjvq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2qlnsqoeo.html

[U110] JS：数组分块
来源：http://dali.nanxuanxn.top/Article/details/gt2fsguctiz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gt2adogibkb.html

[U111] JS：对象转 Map
来源：http://dali.pycfn.com/Article/details/gt2bxlhujms.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gt2hmkjilqj.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gt2xurdebwq.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2onvnxeyl.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gt2koibuupy.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2lwjibvhr.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gt2kgcwvtmv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gt2ybvmbooq.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2xyemmbhz.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysbqwufw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gt2mlgrvvjb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.haohaochexian.top/Article/details/gt2kvrqblgh.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytasyray.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gt2ngympnfb.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gt2xmuxakvp.html

npm i -D vite;  npx vite
来源：http://dali.vqdsnc.cn/Article/details/gt2bqmhikts.html

[U119] JS：生产构建
来源：http://dali.xuanzx.com/Article/details/gt2qrbgmote.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ditelpmo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iooejkkp.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gt2ewujcwrt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohatkvkz.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gt2xfkuyyqq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dszoopjc.html

按语言统计（条）：
来源：http://dali.daxiang520.top/Article/details/gt2vzxzzmsh.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gt2yufojtoj.html

PHP ............ 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nftbfgsr.html

JavaScript ..... 252
来源：http://dali.yj202588.top/Article/details/gt2mmddgnjs.html

TypeScript ..... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2tgfedkwt.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2owbmklno.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gt2yknichba.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gt2sayxlfee.html

C# ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shcmclfu.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gt2zmxorajq.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gt2xuegvivr.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gt2xqvxtqbh.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvnvxibj.html

Kotlin ......... 15
来源：http://dali.yuxming.cn/Article/details/gt2kagukskg.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gt2gtiqigzk.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gt2clzdjuqd.html

Perl ........... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stncruoj.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2febeanay.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2srngfpjq.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlerrsmf.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gebpdavr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnnqstgc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2omtuafex.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2dakhoumt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gt2lilxdldo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gt2ndubhued.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coqjwczm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2ctnrojal.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gt2bmuunumx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2kactfebp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gt2vzmntnhe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2psoxfuee.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2igxinzqw.html


<!-- 参考信息 -->