代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtvqkquhxx.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gteoztisli.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtnmzspzdu.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtfnjbehcc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtehtmhhgg.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtsazovjlz.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtqyayoopd.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gtaofvtjgo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gtljwdvibc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdmpryrxz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtfwjjflcb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrkpqevmt.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gtudflfhvq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtjyrhbhep.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gotoacloud.top/Article/details/gtcuwhtimd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtfadksgcy.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gtscjoxoyk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gtasnyfgny.html

[U04] Py：变量调试打印
来源：http://dali.chenlongwang.top/Article/details/gtbhqyouuz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tianlin.xyz/Article/details/gtadupejnz.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gtyjeqgcfj.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtezjeuyrm.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtgfjdkwxs.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gtkyrqhnwr.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gtyxlqlywh.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gttvayppxq.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtmewyzfbs.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtmdtxcnok.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtyjcajljw.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gtqxskjgor.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gtnkkztdrf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yangfankeji.com/Article/details/gtxgqrxmtc.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtctzxgyqv.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtkpzkbxmc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtphlmukyq.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtrwoklczu.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtybcinnqk.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtanzclknm.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtcfmlfddl.html

defaultdict(list)
来源：http://dali.sysykeji.top/Article/details/gtnplbukxx.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtcetbdpun.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtkmezgmyh.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gtxlbpdfrf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gtxdahmlat.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gtboteudac.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gttevdrcbj.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gtaxjgryim.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtjlecscev.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtegyvqsrj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gthnsutvpl.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gtheactwce.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daria6918.cn/Article/details/gtvnkhiqks.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gtqungssmq.html

@contextlib.contextmanager
来源：http://dali.xuetiantiany.cn/Article/details/gtavfjuvun.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdqbvvsr.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gtntfwajns.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtjjkggrrf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtockikvyh.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtiqhcoqhv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gttfroqisr.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gtptckekiv.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gttorehoax.html

[U26] Py：并发下载
来源：http://dali.gzhubu.top/Article/details/gtexwseybk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtvbjoyegl.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gtehdydnso.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gtltpsztfe.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtktbhiwom.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtmfiprxuu.html

[U29] Py：属性校验
来源：http://dali.sufxvd.cn/Article/details/gttkzekqte.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gthmazoebe.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gttcvuuebt.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtkiweenla.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtzbdyledq.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gthvopdlur.html

[U32] Py：代码格式化
来源：http://dali.mhx1999.top/Article/details/gthgqrjeyu.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtkfovwoxi.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gtvncppjdg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtrvbjpfdc.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtnojeovor.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtuxxzxilq.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gtxzwelgoz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gtyrtirkmh.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gtsxfmdkym.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gtalkqbhhk.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gtaibdehje.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtkuxxozbz.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gttmsnvekw.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gterncirio.html

[U39] Py：判断是否在交互环境
来源：http://dali.c1oappe.top/Article/details/gticqjhomd.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtqchrkmmp.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gtlyqmvhzz.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtowajqowe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gtyxlhajhi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtjcxqwhgw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxuanxn.top/Article/details/gtttvcqtei.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gtekxdftwy.html

[U43] PHP：声明命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtisbjckky.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gtfqyioskt.html

[U44] PHP：开启严格类型
来源：http://dali.nanxinkj.top/Article/details/gtmmgqhbpb.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gtgumnkyuk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gttpeyrdmr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtayintsyh.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gtfwriecrk.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzvbyaih.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gtoqysqnwt.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtsfdokkhe.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gtrfazqccw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jlsjyb.cn/Article/details/gtssjxfpee.html

[U49] PHP：只读属性
来源：http://dali.hnqzz.top/Article/details/gtvtddbcmn.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtrnajansv.html

[U50] PHP：构造器属性提升
来源：http://dali.svipenyu.cn/Article/details/gtfcnlvgon.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfhfeiuv.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gtzewrmeri.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtgehgndey.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gttgrootrf.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gtkrhnbxel.html

[U53] PHP：空合并运算符
来源：http://dali.quarkkingdee.top/Article/details/gtcxtkmuie.html

$v = $a ?? $b ?? "default";
来源：http://dali.gogol.net.cn/Article/details/gtcmrlquvo.html

[U54] PHP：空安全调用
来源：http://dali.fzhhl.top/Article/details/gtavqufkcf.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gtxmhhukpr.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gtpmbefuiw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtxoqowdnb.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gttuquvigi.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttemcilro.html

[U57] PHP：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtopihkadc.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gtywinufuh.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gtndqfiuhy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.snrcjt.cn/Article/details/gtropseojx.html

[U59] PHP：自定义排序
来源：http://dali.aizwys.cn/Article/details/gtrmmfgajs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtxviqtjij.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gtleljqpdv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gtuaxlcqga.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtqzpziqsc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtizdtbghc.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gtlevpndnh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gtwmrlpzka.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtmttssmxy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gtubtfqxwh.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gtxgujzgkk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yangfankeji.com/Article/details/gtocjtsasi.html

[U65] PHP：会话
来源：http://dali.cashguo.top/Article/details/gtcwftwowm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtvpbvusae.html

[U66] PHP：设置 Cookie
来源：http://dali.xuanzx.com/Article/details/gtptvbcetw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.kuanghao11.cn/Article/details/gtwqjfnncz.html

[U67] PHP：处理文件上传
来源：http://dali.jiagoushi.top/Article/details/gtqwprqwmp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtftexnqgc.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gtqxyfjlwn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhiwuduotai.top/Article/details/gtuoztutfh.html

[U69] PHP：PDO 预处理
来源：http://dali.yanxiufei.cn/Article/details/gtxmvwcgfu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxoufmvj.html

[U70] PHP：PDO 事务
来源：http://dali.jqgfzy.top/Article/details/gtbevfsklz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.9152youxi.cn/Article/details/gtnhmvspmj.html

[U71] PHP：抛出异常
来源：http://dali.c1oappe.top/Article/details/gtjphxtdeu.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtztvadlbq.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gtbwtzpmkl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gtflwvuihy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gtkrhwhxat.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvsyndzb.html

[U74] PHP：读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gttzvkelgy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtkdnvdmey.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gtajmflgma.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtqfhnkges.html

[U76] PHP：简单路由
来源：http://dali.vqdsnc.cn/Article/details/gtcmtljofl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gtgsoduovh.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtaznrmlnq.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gtrzuwhrqf.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gtwybymmjg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gtbsjofunc.html

[U79] PHP：静态分析
来源：http://dali.yonumen.top/Article/details/gtiyfigmpc.html

composer require --dev phpstan/phpstan
来源：http://dali.ppjwa.cn/Article/details/gttetlxohr.html

[U80] PHP：代码规范修复
来源：http://dali.zdqjudy.top/Article/details/gtddidxtoc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gtijjcynvu.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gtnzrzgsak.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gtgnzasuwq.html

[U82] JS：package.json 脚本
来源：http://dali.sufxvd.cn/Article/details/gtvgapzskf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aizwys.cn/Article/details/gtcovucsun.html

[U83] JS：ES Module 导入导出
来源：http://dali.nwbrower.top/Article/details/gthjxhsalg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtiyqaxspr.html

[U84] JS：CommonJS 写法
来源：http://dali.sxryk.cn/Article/details/gtmbqjnxtq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zdqjudy.top/Article/details/gtrongxhsz.html

[U85] JS：可选链
来源：http://dali.havefunace.top/Article/details/gtryavtngu.html

a?.b?.c
来源：http://dali.xylfe.cn/Article/details/gtehhgmcjs.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gtoqowaqfr.html

a ?? b
来源：http://dali.cashguo.top/Article/details/gtdpqlzapm.html

[U87] JS：解构默认值
来源：http://dali.ehwqpu.com/Article/details/gtykmvjytj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tian-w.cn/Article/details/gtpdniknic.html

[U88] JS：对象展开合并
来源：http://dali.c1oappe.top/Article/details/gtowdbkrdh.html

{ ...a, ...b }
来源：http://dali.shangyingyoupin.top/Article/details/gtsshscnxm.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gtsrdrschk.html

[...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkygxhwmx.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gtxtcsemaw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtxpvhiyyw.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtbxjqqbur.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsihsxbed.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gtadipixtw.html

structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtduegxmsb.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gtdlcbahwf.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gtzdhxgijo.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtugzretgj.html

const double = x => x * 2;
来源：http://dali.iojbl.cn/Article/details/gtwrvdbcuy.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gtcgakxsto.html

new Promise((resolve, reject) => {})
来源：http://dali.yvedp.cn/Article/details/gtquzoyjoa.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gtzxyzcswm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtqhrlzy.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gtelvvdzbx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtxxtzmkoz.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtfzrpuzdu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gtfshscboy.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gtflqzolco.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gtgcqnvypv.html

[U100] JS：DOM 查询
来源：http://dali.fzhhl.top/Article/details/gtlwjzcbwe.html

document.querySelector(".item")
来源：http://dali.jqgufenzy.top/Article/details/gtuewsbjmu.html

[U101] JS：classList 操作
来源：http://dali.guowangkeji.top/Article/details/gtqcjhvgjl.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gtwilxedwg.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gtycvfycof.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtunmusvby.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtnkkqpmeg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gtwpbthrxe.html

[U104] JS：防抖
来源：http://dali.quarkkingdee.top/Article/details/gtabrgfjcx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtwxmurmjs.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtdcddmcpe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtqzubuaka.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtzcsioxip.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gtsgggibmd.html

[U107] JS：数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gththzlmhh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtfzzimgvq.html

[U108] JS：随机整数
来源：http://dali.cheryme.top/Article/details/gtjohbdwev.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gtnbfkktxy.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtxbftlkxu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtqbaehqkv.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzahzogud.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gtprrtabkc.html

[U111] JS：对象转 Map
来源：http://dali.hnqzz.top/Article/details/gtjdtvcxnd.html

new Map(Object.entries(obj))
来源：http://dali.yongpay.top/Article/details/gtcvxqcjar.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtailibilf.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtkofvgnlq.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gtdqxqgbbg.html

s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtpviccphe.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gtlmvdhrhv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtgvtilclr.html

[U115] JS：生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtaorvctzf.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtvwluztsi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gtjhkminaz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gtwkleajsi.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gtswogmbsr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhixingplan.top/Article/details/gtfqavnkmw.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gtkhqjihwp.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gtzyxxagyu.html

[U119] JS：生产构建
来源：http://dali.yuxming.cn/Article/details/gtznpeyyel.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtcydqpbcg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gtnlvayqpz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhoulong.xyz/Article/details/gtfoljfizm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtilglysfq.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gtoygffpmj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgimbymg.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gtcnoitecm.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gthkzlbvmc.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gtrdveyots.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gtrlzwkztz.html

TypeScript ..... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszelzfju.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gtdumszjzv.html

Go ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtynlyfmjo.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtygjvxhms.html

C# ............. 212
来源：http://dali.daria6918.cn/Article/details/gtsvjsqnzu.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gtpmglimok.html

C++ ............ 30
来源：http://dali.0kj1m.cn/Article/details/gtvneolyzu.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gtpoyefwra.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtscyyovdd.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtlbnpxyzy.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gtaudufuhc.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gtlexrwxae.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gtoknqxdji.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtgtgqawgw.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtzpebqmjp.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtecuychcb.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtphrrnvuw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtdjguhajd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtgsfeporf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtwfgxtkzn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtcfpskunk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtmalzuqpp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtdksoimpj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtwuiypfzt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtsvibubcr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtkficxaqw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtoaaarube.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtgepxanee.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtivbjliuk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtsrarsnxn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gtkwkvaqco.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cashguo.top/Article/details/gtukafxsex.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gttifsscqz.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gtmogadyjf.html

R Bash 专题                             80
来源：http://dali.jianghu66.top/Article/details/gtpfxwyfxu.html

S C / C++ 专题                          60
来源：http://dali.ppjwa.cn/Article/details/gtclfebfkj.html

T 其他语言补充                          60
来源：http://dali.birdmap.top/Article/details/gtrwwlpold.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtbcadoaej.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtuzqdalhm.html

合计                                  2106 条
来源：http://dali.quarkkingdee.top/Article/details/gtfmcfiewb.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqviitsyu.html


<!-- 参考信息 -->