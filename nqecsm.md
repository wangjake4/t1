代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gt2rsuacnxa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2nxbqzruz.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gt2uwoqdbzp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gt2lxsaocph.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqntkvaw.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2mxsyqvap.html

[U06] Py：合并两个字典
来源：http://dali.sufxvd.cn/Article/details/gt2ctycaqjk.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gt2jczobwdf.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gt2exzatrar.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gt2drhwzwoh.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gt2njfzwzsg.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gt2eqaepiiq.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gt2mdmmxtic.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gt2tutnbzjw.html

[U10] Py：按值排序字典
来源：http://dali.cashguo.top/Article/details/gt2gobkvhls.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gt2kppdkuhj.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gt2tnlqyaqn.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gt2zococxrq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2emdaprix.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gt2wrdxqqil.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gt2wprtktup.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gt2qvvvfozt.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gt2apokqvmm.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gt2bbyxytfq.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gt2xxgyzibn.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gt2rsvpyykl.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2eoobzuzl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gt2ucxsedca.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gt2uruunyqr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvrxixmh.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gt2qzmkkdvp.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzyniimm.html

[U19] Py：正则替换带回调
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fweufewt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gt2vibanrtg.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olsqdtem.html

@functools.lru_cache(maxsize=None)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vihngzyc.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gt2ljamoitq.html

@contextlib.contextmanager
来源：http://dali.dashuyun.cn/Article/details/gt2wgkbtexb.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gt2riupqojw.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gt2gyrchchf.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gt2hpsecfjp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guannengcc.top/Article/details/gt2nsafhyxk.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gt2hvkfrgtt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2dcqjjapc.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gt2scbhqdmo.html

csv.DictReader(f)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzddzntf.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gt2sffbgzjs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gt2xobknyll.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgniyizq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nonhcyda.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gt2qifzowxj.html

UserId = int
来源：http://dali.bjfxy.top/Article/details/gt2zswuqfdw.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbuvatoo.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gt2jsgmqxdt.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gt2rongzkua.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfvbscgc.html

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gt2apfiweoc.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gt2ftzingjt.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2uijfgqtl.html

ruff format . && ruff check --fix .
来源：http://dali.zhongyouzk.top/Article/details/gt2huitzrvu.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gt2pgohglhj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gt2tacdwkcg.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gt2juksekhy.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gt2yjckevfz.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gt2qxhubvjo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gt2ovjgclzz.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2ewbibiot.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhengqikj.top/Article/details/gt2ietxpbiy.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gt2pegpjpxg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhengqikj.top/Article/details/gt2qrguzqkl.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gt2ihfltdju.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sznqjlmm.html

[U39] Py：判断是否在交互环境
来源：http://dali.smart0.xyz/Article/details/gt2yrpgxbnh.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gt2pmnrefii.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gt2vyiwskan.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gt2tsnjiwmg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gt2qquxscbs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gt2kdhobwwa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gt2xtbxfpxn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rijwgpia.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigufen.top/Article/details/gt2ytguojja.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gt2hlkolyhm.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gt2tprpjtei.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gt2uxexrdxt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gt2rnmhvrgc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2iscuqpyt.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gt2xbjdluws.html

?string $name = null
来源：http://dali.haohaochexian.top/Article/details/gt2ceoaieut.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gt2ewlksyee.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gt2rrosaukt.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gt2jmdwdluk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gt2lixjlxdc.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gt2vzdjxmzb.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gt2oecpaosq.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gt2mhyysyvx.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gt2qkaskzcc.html

[U51] PHP：数组解构
来源：http://dali.yueranfly.top/Article/details/gt2bzsahnlq.html

[$a, $b] = $arr;
来源：http://dali.dashuyun.cn/Article/details/gt2cgazzxks.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2qfdnmley.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gt2dwvcyalu.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gt2rzdxguvo.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gt2fpoamgua.html

[U54] PHP：空安全调用
来源：http://dali.guannengcc.top/Article/details/gt2uxgpfvfk.html

$obj?->method()
来源：http://dali.cucudq.cn/Article/details/gt2jfhyvmgn.html

[U55] PHP：match 表达式
来源：http://dali.c1oappe.top/Article/details/gt2izxkfdls.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.havefunace.top/Article/details/gt2fhshkabk.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gt2zojhxvas.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2ctbpjypw.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2gboyahrs.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2trasrsbp.html

[U58] PHP：数组三件套
来源：http://dali.yj20258.top/Article/details/gt2ugpyevha.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2xccqfjvy.html

[U59] PHP：自定义排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlncriqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2aaejnzrh.html

[U60] PHP：JSON 编解码
来源：http://dali.svipenyu.cn/Article/details/gt2ehsvtzhs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.bjfxy.top/Article/details/gt2hdiosdvq.html

[U61] PHP：正则
来源：http://dali.iojbl.cn/Article/details/gt2pxiwcrgs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2ykhkdpas.html

[U62] PHP：日期对象
来源：http://dali.tanke756.top/Article/details/gt2yedwsjgb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tanke756.top/Article/details/gt2zmrbeqrg.html

[U63] PHP：文件读写
来源：http://dali.hnqzz.top/Article/details/gt2qpjubgeo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yongpay.top/Article/details/gt2sbdtbkjp.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2lvbrzesk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gt2ceiebbhs.html

[U65] PHP：会话
来源：http://dali.jyoumei.cn/Article/details/gt2bzrasrrr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2gfsjvzqj.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gt2yfqiundu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gt2ujhpzjov.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gt2lrjydxrg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gt2pbqsslzb.html

[U68] PHP：PDO 连接
来源：http://dali.tian-w.cn/Article/details/gt2kukuuboa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gt2chnsogha.html

[U69] PHP：PDO 预处理
来源：http://dali.tianlin.xyz/Article/details/gt2ypsiibpe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gt2nysmtrtd.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gt2rdeqxymg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xylfe.cn/Article/details/gt2ncdnohwu.html

[U71] PHP：抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfrkuwyy.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxinkj.top/Article/details/gt2hspmlgvz.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gt2jonjqowl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dashuyun.cn/Article/details/gt2mltejoph.html

[U73] PHP：读取 ini 配置
来源：http://dali.yangfankeji.com/Article/details/gt2qqgvjmbi.html

parse_ini_file("config.ini", true)
来源：http://dali.chenlongwang.top/Article/details/gt2ihzpmkgf.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2wahpbfix.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gt2dgwezvwr.html

[U75] PHP：依赖注入
来源：http://dali.ehwqpu.com/Article/details/gt2ijsntvqc.html

composer require psr/container
来源：http://dali.jlsjyb.cn/Article/details/gt2vrjhgovw.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gt2fuxnggmx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gaohongyu789.top/Article/details/gt2ludqjlvh.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gt2lqueptzf.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvxpiqdd.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwpdvnpb.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gt2vjatfoek.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gt2vbyoizdw.html

composer require --dev phpstan/phpstan
来源：http://dali.sxryk.cn/Article/details/gt2gdijcybi.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gt2bqgjavxn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvxcmbap.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gt2qrebszfd.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gt2zbokxxem.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gt2kxziiucm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gt2zucsrrkf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wstjczlz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gt2ybwjbmbd.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdvgrgco.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gt2trxuqicj.html

[U85] JS：可选链
来源：http://dali.fengsongda.top/Article/details/gt2xlwugwsu.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gt2hcvwzzcf.html

[U86] JS：空值合并
来源：http://dali.cqqwz.cn/Article/details/gt2ktkqghnc.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gt2ubrmprxf.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gt2kyumgylf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sysykeji.top/Article/details/gt2tanfcofk.html

[U88] JS：对象展开合并
来源：http://dali.daria6918.cn/Article/details/gt2jskoyfaw.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gt2rdieiauv.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gt2yfotdigm.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2yvwuyubb.html

[U90] JS：数字数组排序
来源：http://dali.nanxinkj.top/Article/details/gt2japzbpoo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2lrhaeeef.html

[U91] JS：对象键值遍历
来源：http://dali.yvedp.cn/Article/details/gt2vqammena.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gt2yhfhwxmw.html

[U92] JS：深拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2khuyiyup.html

structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ndnyhbak.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gt2uxmoyujx.html

`共 ${n} 条`
来源：http://dali.xylfe.cn/Article/details/gt2wvhylprn.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gt2aioersjt.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gt2cdidmwhf.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gt2cnopupyh.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgufenzy.top/Article/details/gt2cbcnwhui.html

[U96] JS：async/await 与异常
来源：http://dali.yuxming.cn/Article/details/gt2xalgixtn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2feliryri.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gt2owdjxbur.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2mfvrhdqr.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2ggmeblfv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gt2srxcaggf.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gt2ynbyoviz.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gt2skfguytp.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gt2oxqygkrt.html

document.querySelector(".item")
来源：http://dali.cucudq.cn/Article/details/gt2ixsflnjh.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2hdoenxqa.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2pcyijqhj.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gt2sxvnxfde.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gt2twfgucll.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gt2witezvov.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gt2coizospt.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2effpmgst.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2erezqnsg.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gt2mahwzgns.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2adninmue.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2tchhrppc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ybcxt.top/Article/details/gt2yugxkjdb.html

[U107] JS：数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2gtltgygo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258.top/Article/details/gt2ydgirslj.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gt2pttlpwcm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gt2mazbxuwy.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gt2uotpcbhq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycrwumdf.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gt2ibbadfko.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gt2zkgsiqry.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gt2yghijisq.html

new Map(Object.entries(obj))
来源：http://dali.yongpay.top/Article/details/gt2zxofzzee.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cowrdtbx.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2edigmsha.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gt2lljqplec.html

s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2xmnhpfxb.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gt2zckwgsbg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2ajybkntj.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2sdwkrbtn.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2aakmbhmx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pohrkjqu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cqbyksyz.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hykudxck.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gt2tvkgfhkr.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gt2hvxpxnqb.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gt2thifxqox.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gt2whjbzuzi.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gt2zaophavk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gt2tfjvxqmf.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gt2sdhiewuf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xirtpmle.html

统计汇总
来源：http://dali.dashuyun.cn/Article/details/gt2ahczbylg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kzmnsoag.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfzofqij.html

Python ......... 252
来源：http://dali.birdmap.top/Article/details/gt2dahaomad.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gt2deugpoov.html

JavaScript ..... 252
来源：http://dali.cashguo.top/Article/details/gt2xciyzybw.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2bevcoraj.html

Java ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2lwlgzent.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gt2uwgqvdal.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gt2rvvpdqqu.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gt2zbkvjbhx.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gt2kqlcmqtq.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gt2xjtdlyff.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gt2dctogmdb.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gt2nnotxsnf.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gt2rxpwlkji.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gt2bzgoikao.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gt2nbuupmwx.html

Perl ........... 10
来源：http://dali.dianchejie.cn/Article/details/gt2wrxyptsf.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gt2mekikgju.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2wifczfeo.html

合计 ........... 2106 条
来源：http://dali.tian-w.cn/Article/details/gt2esnzjkrk.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gt2fqzpbmpg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gt2yewxywso.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vviqcqfr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gt2tyyaqtgt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gt2gayhekas.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gt2ohggvaee.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gt2sysoubfz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gt2chefvung.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gt2gaqclbqt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2jveqtjwk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gt2glhucgpp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2fqgiqiuh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2urrwqitx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2xaokzkut.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gt2beomptta.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuetiantiany.cn/Article/details/gt2yadgovjc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gt2fumkaoxm.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gt2ywiiefxa.html

R Bash 专题                             80
来源：http://dali.iojbl.cn/Article/details/gt2pvljbazk.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gt2yozzaycf.html

T 其他语言补充                          60
来源：http://dali.hnxiangtu.top/Article/details/gt2dtsrsvab.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trxohxeh.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2httgzlvp.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrblbyva.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2myenjhyh.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gt2nrsztfsy.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gt2chdqdihw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jianghu66.top/Article/details/gt2yeukieyy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocdrludw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccbxxmdo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cashguo.top/Article/details/gt2nzzbvvcj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenzaomai.com/Article/details/gt2plrnpswu.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gt2gbcsnwmn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2tckqpacl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gt2vysjatxx.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gt2yjovrksb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2swwlozom.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gt2pshtypmd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxinkj.top/Article/details/gt2oqomydvs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqjfpqyu.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfgeilgn.html


<!-- 参考信息 -->