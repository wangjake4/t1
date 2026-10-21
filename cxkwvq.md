代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gtwmzkoujb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkqganyyt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtglzyokta.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtixzuyqlw.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtvkdlkdgz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtwopbjggr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gtvetjlbrj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gthunkysbq.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtzecjwvgl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtuhxfvyqq.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhfheefb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtwjiditxw.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gtvxseszsa.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtcfhlxrke.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfebtnkz.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtculkffbo.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gthwlasoqm.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulboslkj.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gtgovkumxv.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtgglrpgrr.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtkddntklt.html

max(d, key=d.get)
来源：http://dali.gzhubu.top/Article/details/gtiihapzyq.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtvtnjatmm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gthpudtope.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbwscwoa.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtgbwlraqy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtsmcidlgl.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gtncgyuycg.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtugkualzb.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gtlwdvecxs.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtmcafogpb.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtrxwgepkp.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gtzmktlnjp.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtoxnjalag.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtdgoxyrrr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtwerqekpk.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gttjnmfvpw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gtcpvzkhfp.html

[U18] Py：预编译正则
来源：http://dali.daxiang520.top/Article/details/gtysnglytq.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gtzvczeifx.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gtxceaqjpu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtjvoldqed.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtjlsllobq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gtqckyfxtg.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtpnxihvkv.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gtzyipfsno.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gtolfbovnt.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gtueyoirvq.html

[U23] Py：分块读取大文件
来源：http://dali.redwolf501.top/Article/details/gtedrrvyiu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtowjmjcvy.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gtrlqkxjxt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtmzmtdcrm.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtfevqmldr.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtzzqfzwsx.html

[U26] Py：并发下载
来源：http://dali.gzhubu.top/Article/details/gtjmmhlgrq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtbozllhaa.html

[U27] Py：异步 HTTP
来源：http://dali.zdqjudy.top/Article/details/gtwhyvhbbc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gtebzjomuv.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtwtofcgzd.html

UserId = int
来源：http://dali.shuidangran.top/Article/details/gtmhcqshsd.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtzcawodbs.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gtwekuzoop.html

[U30] Py：数据类
来源：http://dali.cdnleiting.top/Article/details/gtsylmoxib.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtwpprasxx.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtteqldawv.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtkzstdqjt.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtappvamri.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtwrcljfrz.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtrvxjjusi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtopopbbnc.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gtouwerceq.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gtsmlxwqio.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gteqabsaqw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gtysdwrdsv.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gtirfduzxf.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gtydykepth.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gthjgvlryo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gtxbjnzrqt.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gthhpslbpg.html

Path(__file__).resolve().parent
来源：http://dali.vqdsnc.cn/Article/details/gtkqgqsapd.html

[U39] Py：判断是否在交互环境
来源：http://dali.gogol.net.cn/Article/details/gtinuhdupp.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gtexnbdivk.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtcrqtbpzr.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtdzznshyg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gtwwbwsmcq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gtxmzkihyy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.quarkkingdee.top/Article/details/gtbdmbtxie.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gtyhhxzxol.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gtzrypjkjc.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtslhfqzdo.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtvefpacfu.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gtzqvznihk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tanke756.top/Article/details/gthhgcpvbm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbkrgnoy.html

[U46] PHP：可空类型
来源：http://dali.yangfankeji.com/Article/details/gtlhoskktf.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gtvvmkyvcc.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gthtasaptr.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gtojsetwfc.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtzeidtukt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yanxiufei.cn/Article/details/gtiqncrtbg.html

[U49] PHP：只读属性
来源：http://dali.xuanzx.com/Article/details/gtpzhnslbx.html

public readonly string $name
来源：http://dali.shuidangran.top/Article/details/gtyhrgnmdb.html

[U50] PHP：构造器属性提升
来源：http://dali.yongpay.top/Article/details/gtiddldioh.html

public function __construct(private int $id) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfkcatnm.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeocgxnf.html

[$a, $b] = $arr;
来源：http://dali.wangdashe.top/Article/details/gtqrbclfxa.html

[U52] PHP：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtrioxrhmr.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtsghiparw.html

[U53] PHP：空合并运算符
来源：http://dali.ehwqpu.com/Article/details/gtihzxrwok.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gtjxswmirm.html

[U54] PHP：空安全调用
来源：http://dali.9152youxi.cn/Article/details/gtcmaeeayx.html

$obj?->method()
来源：http://dali.yj20258.top/Article/details/gtbxzqcxup.html

[U55] PHP：match 表达式
来源：http://dali.birdmap.top/Article/details/gtjgchnvge.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zycfv.cn/Article/details/gtugiwmjgd.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtagipsbbp.html

f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpickcbq.html

[U57] PHP：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtjayjgpjy.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gtegyvzdgo.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gteevdismr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258888.top/Article/details/gtzlqtkqql.html

[U59] PHP：自定义排序
来源：http://dali.cheryme.top/Article/details/gtbbyxbiyy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtxewyfkon.html

[U60] PHP：JSON 编解码
来源：http://dali.cashguo.top/Article/details/gtjznpsxqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gteyukhcub.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gtpmrxihyw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtoosyaotc.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gtaytswuog.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gtrryrytkj.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtmvivzguy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtrzuyibho.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gtdufqqwsl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gtpyrbwhka.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gtnfnphrzc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtfjuwvxer.html

[U66] PHP：设置 Cookie
来源：http://dali.xuanzx.com/Article/details/gtpggjxqsf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtzfrgyswr.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gtdixbetio.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtqyvfgtmw.html

[U68] PHP：PDO 连接
来源：http://dali.mhx1999.top/Article/details/gtsbhtmzay.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhoulong.xyz/Article/details/gtvlvrdxen.html

[U69] PHP：PDO 预处理
来源：http://dali.zhixingplan.top/Article/details/gtbuejfebf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sysykeji.top/Article/details/gtqkjbizva.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtedkwvyno.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ydzc1.top/Article/details/gtuzhldpit.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtkkmykbpa.html

throw new RuntimeException("失败", 500);
来源：http://dali.gotoacloud.top/Article/details/gteyshjrtk.html

[U72] PHP：写错误日志
来源：http://dali.nwbrower.top/Article/details/gtdgedlzku.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gtqkfbnqaq.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gtsybutzyk.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gtahhbmdue.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtanpzvsxk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gtqcrackjp.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtrrwdsswy.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gtwwkuvbjw.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gtogisoszf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gthbzvolrp.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtrrslhmsj.html

composer require twig/twig
来源：http://dali.jqgufenzy.top/Article/details/gtirpytiuz.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtphdtexjk.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gtswaagrzm.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gttbsflndx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtdqqxadcj.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gtsfsmovtn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pycfn.com/Article/details/gtvastwxjy.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gtgkayoddv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gtogjktvui.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gtvgniokjx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuxming.cn/Article/details/gtldlyjmml.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtpkicmdfq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtciqcwrnt.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gthngyhpad.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gtuvbajqzz.html

[U85] JS：可选链
来源：http://dali.meibo888.top/Article/details/gtexmxnqeo.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtwejwxsez.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtrxsfdvbt.html

a ?? b
来源：http://dali.havefunace.top/Article/details/gtcmqfyxcd.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gtrbxahwjx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hfpthk.cn/Article/details/gtqhtgqcwt.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqobachl.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gtmyyrbzlt.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gtbjwmkbos.html

[...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtwuaifsoy.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gteogtztmq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gttjarvijp.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gtpcoagiyo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pycfn.com/Article/details/gtsvcnojgo.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gtbwmnhbcq.html

structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtdmaphpmp.html

[U93] JS：模板字符串
来源：http://dali.jiagoushi.top/Article/details/gtvumfsgqn.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gtpjeiyoyj.html

[U94] JS：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiegiykq.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtjtvmwiij.html

[U95] JS：Promise 包装
来源：http://dali.daxiang520.top/Article/details/gtcktxsatm.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtmjzuhodi.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtfbekgehr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtmnpsfbwp.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gtcbkmrjec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtfeazjznu.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gtehaxpoor.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtasngshlj.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gthqvwpmjf.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gteupmvtih.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtktostvpe.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gtcwebipwm.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtpqbancnp.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbmbrqnl.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gttnmhhzyh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtsumnomym.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gtwlpznepe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtuedzdere.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtkrmzygqu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtyyhiapkk.html

[U105] JS：节流
来源：http://dali.guannengcc.top/Article/details/gtkbryhusm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtokuyxbxs.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtqhmiiuxs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtikbxuzff.html

[U107] JS：数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtzxibuqxq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtynvqrivg.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gterurqlah.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jianghu66.top/Article/details/gtfqgfegcs.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtxcbjrjrw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtorsifkme.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gtacdhrstv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gtvmstnzbo.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gtekpzuojk.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtakglzyfv.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gtpwwvsdrz.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtlwdjqxdh.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaccwivd.html

s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtbkfhcdju.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gtldydbgaq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtmfwuiett.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gtbpgipjkb.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtjzzfzzet.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtzccqafrf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gtjlxpnjhh.html

[U117] JS：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gtsjzyhjig.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gternkaysi.html

[U118] JS：开发服务器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyqkmxpk.html

npm i -D vite;  npx vite
来源：http://dali.aizwys.cn/Article/details/gtweexpcpz.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtjyogykaa.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gtooyghjyt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gtqobnxbcs.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtlnijihtj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkfcdzdet.html

统计汇总
来源：http://dali.cucudq.cn/Article/details/gtnklwbage.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcwgrlicy.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gtzygnufpq.html

Python ......... 252
来源：http://dali.zhengqikj.top/Article/details/gtxzvelvau.html

PHP ............ 252
来源：http://dali.xinyue.icu/Article/details/gtqhiswnlw.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gtrjcklitb.html

TypeScript ..... 212
来源：http://dali.nwbrower.top/Article/details/gtshsgdrtf.html

Java ........... 212
来源：http://dali.redwolf501.top/Article/details/gtukzzwyho.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtjvxrmaka.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gtnojvxkmy.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gttcemivxf.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtomqjlmzk.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gturnmmepa.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gtduzmcpfu.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctzqkpzs.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtnistivpx.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtuhzkoplf.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gtmdshbxsh.html

Perl ........... 10
来源：http://dali.nwbrower.top/Article/details/gthcjohylw.html

Scala .......... 10
来源：http://dali.tian-w.cn/Article/details/gttczftrdp.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtmecbnxcb.html

合计 ........... 2106 条
来源：http://dali.9152youxi.cn/Article/details/gtczvrjaya.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gtjkaajxbv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtnowzbtat.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtgnpstkiw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtuvmgqnra.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gteemdyqgd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.snrcjt.cn/Article/details/gtwftzpmby.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gtgzliocmw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtkdgjmamx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtrldeucjb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gttgonijcv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtppfkyhhg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtxqujzcdr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauyttexh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtddbmgrgb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtsrghsgww.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gtnmabjwnj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtlkrpvyym.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gtdzzkgksz.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gtjlvrkdzx.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gtisalkbej.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gtpkfavvil.html

U 高频实用片段                         120
来源：http://dali.bjfxy.top/Article/details/gtcinwabjr.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtgocdlfim.html

合计                                  2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcecpasg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gthggbtcgp.html

使用提醒
来源：http://dali.snrcjt.cn/Article/details/gtgxisvwsn.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtpnpkglkp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gtnwjzoczv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gteplroejw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cdnleiting.top/Article/details/gtgsicgelq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sysykeji.top/Article/details/gtibccnjgs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhengqikj.top/Article/details/gtdrrjwmay.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gtnldpkpan.html


<!-- 参考信息 -->