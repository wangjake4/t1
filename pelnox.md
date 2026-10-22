代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtdfivae.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtiqtkprfh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtvrqiqwix.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gtmrbidzcc.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbqhllyb.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtgrudjjvo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtddwopzjf.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtfexivtsn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gtnzvwjtdb.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtnymvxwhw.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtkewhcqpw.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtflkuakhf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gtbnzlpnir.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjpceatan.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtnualmqgv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthvyjnzcr.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gthjyqlnpj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gtmuhzufmz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtgigsntzs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gteevabimu.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtbqxnugrq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtskzdxqhn.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gtnzxdnwjf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gtqtkbmawi.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gtdllsqjrj.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtbphjpycj.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtzyeclrni.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtvedvhhwi.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gtylujxkdj.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gtscrttywe.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtrtleikki.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtmynuytfv.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gteqdrqprr.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gtqxntqkdk.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gtuhfyzezv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gtvkgagvbt.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gtcurcwskm.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtoomdsaxd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gthdhrqpih.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtcxfidyna.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gtahjllcyw.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gtscoyialr.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gtcpwxeeoc.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gtfcwttxux.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gthawhtvuf.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtzkbchoey.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gtyaygkqmz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gtynfhryai.html

[U17] Py：初始化日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyfetzsm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hywenlv.cn/Article/details/gtudbekyek.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtgidavrnh.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtcyezzjbf.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gthhpicrrb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtpbntbawf.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gtfanamtqi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gtwqcfzvud.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtktgwptsf.html

@contextlib.contextmanager
来源：http://dali.aibaodan.cn/Article/details/gttkwxorsn.html

[U22] Py：矩阵转置
来源：http://dali.cashguo.top/Article/details/gtzbkmdcio.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtmpsguogg.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gtjcgemoyz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gtdevbhawx.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gtbuawfftz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gteqwmiyfs.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtvjxjkloy.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtlfawgjed.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gthrwicnbu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gtvepzxllo.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gtmfckxsis.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gotoacloud.top/Article/details/gtearzmblg.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gtzzjlqbba.html

UserId = int
来源：http://dali.hammf.cn/Article/details/gtldygocng.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtgujpbhdo.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtrxmkdwpv.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtdsqeuxln.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gtmdcyxzso.html

[U31] Py：单测
来源：http://dali.zhoulong.xyz/Article/details/gtjrueexsb.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtucaxpjsd.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gtuvrkconq.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gtlnjthyzl.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gtoymfplxq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.havefunace.top/Article/details/gtjzbjoqrp.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gtsqzkqhum.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gtzmcjsiqp.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gttqepwgig.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gtjcnejupr.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gtgemodxfr.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gtjrxzeyud.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtxjbdffdt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtbrbxnxmu.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gttubnppnd.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gtresxwxhd.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gtqsbikntn.html

sys.stdout.isatty()
来源：http://dali.redwolf501.top/Article/details/gtexsxbjlq.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtkjvhxiry.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtffpmsduo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtdxfuszdo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhiwuduotai.top/Article/details/gtdhdcqkst.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gttvajlads.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gtqzbcmooc.html

[U43] PHP：声明命名空间
来源：http://dali.chenzaomai.com/Article/details/gtvdukjypt.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtffcjhzkq.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gtbslrxumu.html

declare(strict_types=1);
来源：http://dali.hysaishi.cn/Article/details/gtzudjhwzd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gtunkuhvir.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtdziuflzp.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gtloxtvjyk.html

?string $name = null
来源：http://dali.shanyushiyangtech.top/Article/details/gtvagsnzlm.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gtffbyskjk.html

int|string $id
来源：http://dali.ybcxt.top/Article/details/gtqbpqdmmb.html

[U48] PHP：纯枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoatbzrz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gtbsftuhdj.html

[U49] PHP：只读属性
来源：http://dali.sxryk.cn/Article/details/gtwssghqmt.html

public readonly string $name
来源：http://dali.iojbl.cn/Article/details/gtllwghkoq.html

[U50] PHP：构造器属性提升
来源：http://dali.gaohongyu789.top/Article/details/gteisbaqvy.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtmhycnoqi.html

[U51] PHP：数组解构
来源：http://dali.iojbl.cn/Article/details/gtevhrdpld.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtxgiuqvii.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtjohuzaod.html

$double = fn($x) => $x * 2;
来源：http://dali.sweek.top/Article/details/gttbgvonzx.html

[U53] PHP：空合并运算符
来源：http://dali.chenlongwang.top/Article/details/gtwrapbyap.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtpibehvjt.html

[U54] PHP：空安全调用
来源：http://dali.haohaochexian.top/Article/details/gtjdjrdtaq.html

$obj?->method()
来源：http://dali.haohaochexian.top/Article/details/gttujqdmcm.html

[U55] PHP：match 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtgxlmpufp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtkmradbim.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gtngbznkey.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gttuecygsy.html

[U57] PHP：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtkezdfrjt.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gtdtdfptbs.html

[U58] PHP：数组三件套
来源：http://dali.zycfv.cn/Article/details/gtdzmeiihv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtjkadigvv.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtyklncuph.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtdxnzdotv.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gtnuaibpsq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gtsoodidbl.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gtptbztkdf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtqlldsrsu.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gtwmwhwnrp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.feifeiyinyue.top/Article/details/gthtgdkspn.html

[U63] PHP：文件读写
来源：http://dali.yuanzhike.top/Article/details/gtwybmncaa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gtsklszkti.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gtxqtrqawc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hywenlv.cn/Article/details/gtuahvvitc.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gttuynvonm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtppxfmphp.html

[U66] PHP：设置 Cookie
来源：http://dali.aizwys.cn/Article/details/gtcpbmjncd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fengsongda.top/Article/details/gtojvvyecu.html

[U67] PHP：处理文件上传
来源：http://dali.sysykeji.top/Article/details/gtshsmumsd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gtugghnoth.html

[U68] PHP：PDO 连接
来源：http://dali.pengpengdd.cyou/Article/details/gtfhnicfgx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj20258888.top/Article/details/gtgbxkohhp.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gtkgcorhwf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtaffqstyz.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gtpkeqebdl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxinkj.top/Article/details/gtyzhrpvnm.html

[U71] PHP：抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gturezbfru.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gtlbtesdku.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gtfkljstcv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.kuanghao11.cn/Article/details/gtzpdxnjqq.html

[U73] PHP：读取 ini 配置
来源：http://dali.ivvv.top/Article/details/gtamwhujzx.html

parse_ini_file("config.ini", true)
来源：http://dali.9152youxi.cn/Article/details/gtorkmtamy.html

[U74] PHP：读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtdqvasioa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gttuoapiup.html

[U75] PHP：依赖注入
来源：http://dali.tanke756.top/Article/details/gtyzmjegvq.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtbuiaodmu.html

[U76] PHP：简单路由
来源：http://dali.9152youxi.cn/Article/details/gtiiqobezx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gtlkyvtmjb.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gtlkkwswfe.html

composer require twig/twig
来源：http://dali.sxryk.cn/Article/details/gtqigevict.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtczoirjsx.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gtikgrdsny.html

[U79] PHP：静态分析
来源：http://dali.quarkkingdee.top/Article/details/gtciylvgxz.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gthajnomoz.html

[U80] PHP：代码规范修复
来源：http://dali.sufxvd.cn/Article/details/gttptefvpk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gtylqaeztv.html

[U81] JS：初始化项目
来源：http://dali.hysaishi.cn/Article/details/gtnipvvxhv.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtnnpwyzkm.html

[U82] JS：package.json 脚本
来源：http://dali.ydzc1.top/Article/details/gtefisntwv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zdqjudy.top/Article/details/gtqegxucxc.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxuanxn.top/Article/details/gtltvvcqcy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtmlvpjdyo.html

[U84] JS：CommonJS 写法
来源：http://dali.jiagoushi.top/Article/details/gtztxuhfxb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shangyingyoupin.top/Article/details/gtlsqpzppq.html

[U85] JS：可选链
来源：http://dali.snrcjt.cn/Article/details/gtevmbgknl.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gtrgutgjmd.html

[U86] JS：空值合并
来源：http://dali.zhoulong.xyz/Article/details/gtscjggnkb.html

a ?? b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrkhpwdl.html

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtxisvitqn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gtinylpcje.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtjispiipc.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtzliqxvig.html

[U89] JS：数组去重
来源：http://dali.birdmap.top/Article/details/gtliexoxse.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtdwaymjbn.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gttcxjlnyb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtobcywqou.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrozszwsu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgufenzy.top/Article/details/gtznfzghob.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gtgptvekrt.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtjbrbypwz.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtpkmsjtdr.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gtwlqpwvru.html

[U94] JS：箭头函数
来源：http://dali.yj20258.top/Article/details/gtcbpyhmfo.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtjlnwljyo.html

[U95] JS：Promise 包装
来源：http://dali.hnxiangtu.top/Article/details/gtdvqohidc.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtxvaexeye.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gthacnnxtd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtcylzkteo.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gtnjidxtdv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtufpiifhw.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gtphwwdukm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gtasrymewj.html

[U99] JS：事件监听
来源：http://dali.redwolf501.top/Article/details/gtclfryryo.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gtvdrupmbs.html

[U100] JS：DOM 查询
来源：http://dali.aibaodan.cn/Article/details/gtfjcfqtfk.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrcewylt.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzotusqpm.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gtafojdyga.html

[U102] JS：本地存储
来源：http://dali.yj202588.top/Article/details/gthssbaqfc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgufenzy.top/Article/details/gtatfcdnby.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtacrnvzht.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gtcpmjgfct.html

[U104] JS：防抖
来源：http://dali.aizwys.cn/Article/details/gtggkudens.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtsxrsmmux.html

[U105] JS：节流
来源：http://dali.wangshuangyany.cn/Article/details/gtffuuzxgi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqxeobqt.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtuozzwhzh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gtaagvqofu.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gtsenoqwyn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gtlbshxlyb.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gtlvbncekf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtmwooxnko.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gtknrjkfgq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwasexpur.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtvsatugqb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yongpay.top/Article/details/gtzglnytlg.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gthnmrqxaw.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtlldijuga.html

[U112] JS：字符串补位
来源：http://dali.gotoacloud.top/Article/details/gtjsgjonks.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gthtctiwee.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gtkksqsclz.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtposevsjc.html

[U114] JS：JSON 深比较
来源：http://dali.cdnleiting.top/Article/details/gtgkkilfqr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtybzheili.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtfrcmynbe.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtzfsdoehm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gtqgysotqq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmitkadqv.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtnlelcenu.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtlefgclnt.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gtadypqnmj.html

npm i -D vite;  npx vite
来源：http://dali.0kj1m.cn/Article/details/gtgmszrjwg.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtomczlvmo.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gtcqiyrnia.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtnyleyupy.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtnkfdyhbq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgnwozfwm.html

统计汇总
来源：http://dali.cqqwz.cn/Article/details/gtilzjmvhg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtovmactqo.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gtbhgvmhos.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gtdwxpgsfy.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gttxjjqpaj.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gtdkcvuufs.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gtnamqqqng.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gtifhmneke.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gtdjslliao.html

Ruby ........... 212
来源：http://dali.yonumen.top/Article/details/gtcytjybus.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtpxiuugmc.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtkrdyyq.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gtwwcwwesq.html

SQL ............ 90
来源：http://dali.xuetiantiany.cn/Article/details/gtmczfehum.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gtpbgszdis.html

Kotlin ......... 15
来源：http://dali.0kj1m.cn/Article/details/gtqbpgirla.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtviisykni.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gttpgtgtlj.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtbucouxoh.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gtzofagmcv.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtlfgjbeyj.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtwsjgnufa.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gtyrecwimw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtuqnaqxjf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtdztpbnqb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtalpiodbd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gttjcvvqcm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gtkjzvzfka.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.bjfxy.top/Article/details/gtbsxlyfuw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtmrnplojj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtpynrgwby.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtykfchujc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtznevmksa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtjouzfgth.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtfrztoqee.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtyzvbemoi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtbhfhpley.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zycfv.cn/Article/details/gtxzvcukxd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtkqbltaov.html

Q SQL 专题                              90
来源：http://dali.yj20258888.top/Article/details/gtxkpbtygh.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gtrusnruqr.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gtctivfiyw.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gtbpbamiwt.html


<!-- 参考信息 -->