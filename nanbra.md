代发 wailian999

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gt2tlwdwkbp.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2prxjjzdl.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2izrpaxdj.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2jazbqwoo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2clejwpqv.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2xgbteeju.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gt2sipavmxu.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gt2vsnticpu.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2kakhybpu.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2afhuerre.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gt2mjnkjazi.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urmxnnqf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gt2oythcnex.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gt2uhdnawpm.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2ssdumlcz.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gt2rcfddmic.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gt2fpcvozjd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2vxjegxzd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gt2uzbvxgsl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jwsrjvkb.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivlfmres.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gt2yhiccvjz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gt2vilzomtt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gt2wfalanqt.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258.top/Article/details/gt2zmyigaiw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihirembm.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gt2lkkrvxfk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gt2gxvjuwxd.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gt2jdfbhfcl.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2ftvlyawm.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gt2kskvnacc.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqglybxs.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwamlrot.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbfzyezk.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gt2mqrwrnaa.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gt2tpqdiibe.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gt2zrlzqqvs.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gt2moizcmej.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gt2cbednzuy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gt2dzazpnry.html

[U11] Py：生成器表达式
来源：http://dali.dianchejie.cn/Article/details/gt2rgrfwjav.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gt2mfjvizin.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xziqi.cn/Article/details/gt2cuczjkzk.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gt2lcconjxg.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gt2kaijwece.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gt2tubgtglf.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gt2lfsdlzaz.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2ebjiuqvd.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gt2uuonyllm.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gt2jspnsgjj.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gt2uqnzmvkh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gt2qxbxyawl.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2hprvtfhc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gt2awjbgtac.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gt2vztewcul.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2eknfnjkv.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gt2vbypgtwu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gt2kbfqabys.html

[U20] Py：缓存函数结果
来源：http://dali.tianlin.xyz/Article/details/gt2frawligx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gt2zvwvamgy.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gt2awdshgmc.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gt2huebqsga.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nppdymrg.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylxuthfq.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gt2aekadxlc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhixingplan.top/Article/details/gt2uorvlimk.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gt2tbgpwoue.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2awpyojov.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gt2mehcvlfk.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gt2mzbgkfac.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbfowhqz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gt2xhwbkfrl.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gt2qrsswohr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gt2awellick.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gt2bqiofkwl.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gt2vsbkujnd.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gt2hwgsrxiv.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gt2pwitoiqa.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gt2esqidnfb.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gt2hefozugm.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gt2pmebmkak.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gt2ztupyxmm.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gt2afdjhctu.html

ruff format . && ruff check --fix .
来源：http://dali.chenzaomai.com/Article/details/gt2mynxbxqk.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gt2yotqsdnc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.9152youxi.cn/Article/details/gt2ksluvsdb.html

[U34] Py：判断编码
来源：http://dali.hfpthk.cn/Article/details/gt2xxdtgwdw.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gt2hdbejajf.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gt2wbciaorr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gt2phjdgqiq.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alqqtpua.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gt2ysyurgbs.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gt2aarmxigl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gt2mphglobi.html

[U38] Py：获取脚本所在目录
来源：http://dali.hammf.cn/Article/details/gt2skpgrmxf.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gt2fgntgruu.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdajxkcr.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gt2wgzbykeb.html

[U40] Py：打印到标准错误
来源：http://dali.jlsjyb.cn/Article/details/gt2dlmjuduh.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2fwlxmvqv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.mhx1999.top/Article/details/gt2gyfdiceu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gt2aptrfbbi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gt2yvvxmezt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gt2dfdsklat.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrtpmllg.html

namespace App\Http;
来源：http://dali.jyoumei.cn/Article/details/gt2rxoqjqnq.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvuqzhej.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gt2pittrole.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gt2dfxmwzsj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlpmpxtw.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2budlapuw.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gt2medxhxpc.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2bbvwvklz.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gt2gigztvpv.html

[U48] PHP：纯枚举
来源：http://dali.cdnleiting.top/Article/details/gt2ocsxbjrk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeirfahc.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gt2ysuwlpbd.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otplxtvg.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gt2szokjyqp.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gt2shvxxeez.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gt2fkueduzl.html

[$a, $b] = $arr;
来源：http://dali.andypj.xyz/Article/details/gt2tjfpmvsk.html

[U52] PHP：箭头函数
来源：http://dali.hnqzz.top/Article/details/gt2kwuqnplb.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlrfyyyg.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gt2pocjcsre.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gt2ppqewaah.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gt2zmuyuzwd.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gt2btsnapfz.html

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2qphatqot.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gt2bwufxwrj.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gt2rngolacm.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2kpcpmkfp.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhjohgny.html

"值: {$a}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hletoalr.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gt2olbdzdhy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2rmsabewl.html

[U59] PHP：自定义排序
来源：http://dali.wangdashe.top/Article/details/gt2uitbpjge.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2hugbmxcl.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gt2qxpijrka.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gt2xtkpkyfm.html

[U61] PHP：正则
来源：http://dali.kuanghao11.cn/Article/details/gt2skbewune.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2wfduvcsf.html

[U62] PHP：日期对象
来源：http://dali.snrcjt.cn/Article/details/gt2cyngxldd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ydzc1.top/Article/details/gt2lfdtgkzb.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irwosmnf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gt2avgpmfle.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2otirbckw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.svipenyu.cn/Article/details/gt2pzvoqhsa.html

[U65] PHP：会话
来源：http://dali.andypj.xyz/Article/details/gt2ucxruagp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsbdmofy.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gt2raraylhe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.redwolf501.top/Article/details/gt2nvosycgo.html

[U67] PHP：处理文件上传
来源：http://dali.zhongyouzk.top/Article/details/gt2kuijvibl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gt2pvoqcxan.html

[U68] PHP：PDO 连接
来源：http://dali.yj202588.top/Article/details/gt2ayempnpd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.snrcjt.cn/Article/details/gt2kdddthfj.html

[U69] PHP：PDO 预处理
来源：http://dali.svipenyu.cn/Article/details/gt2olfprmgd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gt2fctqyctx.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2umcfgbwq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gt2twwfjwuo.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2ynpigyaj.html

throw new RuntimeException("失败", 500);
来源：http://dali.tian-w.cn/Article/details/gt2jprywmpo.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gt2jrkqbecq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gt2kxudwnsd.html

[U73] PHP：读取 ini 配置
来源：http://dali.mhx1999.top/Article/details/gt2taupnxnt.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gt2zjbsnwyt.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gt2apigugzm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gt2uzrcxfvr.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gt2sxwkvrrw.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gt2dpogxqjs.html

[U76] PHP：简单路由
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfnuszye.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gt2fuahyogp.html

[U77] PHP：模板渲染
来源：http://dali.hfpthk.cn/Article/details/gt2erzpqwoj.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gt2gveznmth.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2unwoftej.html

composer require --dev phpunit/phpunit
来源：http://dali.quarkkingdee.top/Article/details/gt2qcgdubge.html

[U79] PHP：静态分析
来源：http://dali.zhongyouzk.top/Article/details/gt2sjpqxaem.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gt2oflfhlwb.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gt2iojgeitx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hypvyzvu.html

[U81] JS：初始化项目
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnntnsja.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gt2vjnwmgkh.html

[U82] JS：package.json 脚本
来源：http://dali.gzhubu.top/Article/details/gt2fkpujqqz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gt2xgvziqec.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frdvcvos.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqiabgyr.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2iaiagtae.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gt2mjjacvqh.html

[U85] JS：可选链
来源：http://dali.sysykeji.top/Article/details/gt2uclcgayg.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gt2bokwhtwy.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gt2arllrshv.html

a ?? b
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqhrisff.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxlixtev.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gt2rpzkuxbu.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gt2wdchmjsh.html

{ ...a, ...b }
来源：http://dali.sxryk.cn/Article/details/gt2ijwhtori.html

[U89] JS：数组去重
来源：http://dali.gaohongyu789.top/Article/details/gt2ykcgzfjk.html

[...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2upkvexxi.html

[U90] JS：数字数组排序
来源：http://dali.gotoacloud.top/Article/details/gt2latirrmu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2zmccvswq.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2cruyonmi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gt2bmchxqeh.html

[U92] JS：深拷贝
来源：http://dali.xylfe.cn/Article/details/gt2odeqptqn.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ejjkpadx.html

[U93] JS：模板字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2qtffafxt.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gt2fhdneaax.html

[U94] JS：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2aobmcjzt.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gt2puotyoca.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gt2kiziltwm.html

new Promise((resolve, reject) => {})
来源：http://dali.ybcxt.top/Article/details/gt2xpuwqlfr.html

[U96] JS：async/await 与异常
来源：http://dali.sufxvd.cn/Article/details/gt2mmncgrdu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2xxcnxxqt.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gt2oilwdjjs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2wtiqdlhw.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2itaedisy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gt2xhksmxlf.html

[U99] JS：事件监听
来源：http://dali.jianghu66.top/Article/details/gt2yyveodpc.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gt2galwetrv.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmqjggni.html

document.querySelector(".item")
来源：http://dali.svipenyu.cn/Article/details/gt2cqrnnivy.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2rbcrixxn.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gt2redikusz.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfdaogwl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gaohongyu789.top/Article/details/gt2irlxzhmk.html

[U103] JS：定时器
来源：http://dali.vqdsnc.cn/Article/details/gt2vluoupax.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gt2vvpmjxjw.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gt2lyvgjalh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2whgtwyoa.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gt2grhleekf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gt2mfmkdodk.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2hjwcswrm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sweek.top/Article/details/gt2ywvzvjkd.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2ytftjpaj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gt2luqjrenu.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gt2wikczhth.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxzhqbik.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gt2kfymnovz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gt2bstligyf.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gt2nkcvjmst.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gt2kzrqbtjt.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2fwhnkjmv.html

new Map(Object.entries(obj))
来源：http://dali.daria6918.cn/Article/details/gt2gdzjtpvl.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gt2cvmosseu.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2lulhvzmu.html

[U113] JS：正则替换全部
来源：http://dali.yuxming.cn/Article/details/gt2bapnicma.html

s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2xxvqxcrl.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gt2dhfxuupz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2tkijzxay.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jgynyoys.html

crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2glxthkwr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gt2xmptfvmd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ytjxucxu.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gt2wncvhtrk.html

npm i -D vitest;  npx vitest
来源：http://dali.birdmap.top/Article/details/gt2hlqvvjji.html

[U118] JS：开发服务器
来源：http://dali.ivvv.top/Article/details/gt2sgwndpeg.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gt2yvwlvdrt.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gt2negrtjrv.html

npx vite build
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iabswcvo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigufen.top/Article/details/gt2uigmztms.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gt2pujilpaa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2etahxzmu.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gt2ieoegndg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2tsqalslr.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gt2ntidfxro.html

Python ......... 252
来源：http://dali.meibo888.top/Article/details/gt2syyuukwk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgjvdny.html

JavaScript ..... 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkpxwlhp.html

TypeScript ..... 212
来源：http://dali.gotoacloud.top/Article/details/gt2bmdmftvf.html

Java ........... 212
来源：http://dali.tanke756.top/Article/details/gt2rdkrimuo.html

Go ............. 212
来源：http://dali.andypj.xyz/Article/details/gt2avrwdbvr.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2sqpiokqs.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gt2hvxkxqqs.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gt2ydtmiscv.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppwhzkpa.html

SQL ............ 90
来源：http://dali.0kj1m.cn/Article/details/gt2xphdtwee.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gt2efylmmcc.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gt2hmyssvhj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hwekoyce.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gt2xvpnlzso.html

Perl ........... 10
来源：http://dali.gotoacloud.top/Article/details/gt2mtfwaqnb.html

Scala .......... 10
来源：http://dali.c1oappe.top/Article/details/gt2odfcobtd.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2zhmwispr.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gt2zwywxybb.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gt2qhkpzblv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2pgbeohof.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2lhbjvtbo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2nsjhhfso.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gt2qszghzlm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gt2jidelmqk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gt2zqvmeqsl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivtcqeft.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gt2ejdozgfn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxetgjwy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxkhdpoi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2lgnunepg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2exzucuit.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2isjxmrau.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2frdhqmyw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gt2imbzcdcz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2qalstnrl.html


<!-- 参考信息 -->