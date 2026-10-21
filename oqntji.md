代发 wailian999

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gtdkmnlfpe.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvxghuek.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gthrqnkgeh.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtglbgknck.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtiymyleyk.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtzqoncobp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtzwizpzlv.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gteacasvvy.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtijsjgsom.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtsvsyecjh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gturkemwly.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruckuojl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtbapctqnb.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gtutzpxbwk.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtaiqnepry.html

[T60] Scala：折叠
来源：http://dali.cucudq.cn/Article/details/gtkwyrzgri.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtuqsmwutj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrtgjcdte.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtetywkqou.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmzywxvtl.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gtwqjsxiyg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gtppbrmrwn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gtfvfaiztm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtjwrutefw.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtblhoyryv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtyyrfbhbu.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtlwssfbsg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgufenzy.top/Article/details/gtctfvocpu.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtfzsqvkxq.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtuqbldpcc.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtvslzfulb.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gtywsovpes.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gtrbitgjzx.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gtjqixzcxy.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gtrskmpqfv.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtghogtwfy.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtljcqupgz.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gtcaojazvn.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtvtiryayv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtdimgzdbc.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtopvgmuxj.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gtfhfpxuwa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gteliysfgs.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvmzkwqh.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gtivgkfufe.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gtihgyrrzp.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtfwsnckje.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtfgoetkqa.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtbcmcyroi.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gtbyaommak.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtuibffeha.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gtanjmugtb.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtuulcrgqp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gtvsflnalo.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gtttpkdtjv.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtiasywmsx.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtrliqsdpe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkuwkyrd.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gtyptywajt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlduccql.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtyaldshzz.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gtqzqxbbnc.html

[U22] Py：矩阵转置
来源：http://dali.yonumen.top/Article/details/gtsdfxsnua.html

list(zip(*m))
来源：http://dali.cheryme.top/Article/details/gtajuadyme.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gtxlxjrrwy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gtcaiympqb.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gtjxvccpwk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtiksuhpag.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gtycbgxusg.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtoracarvg.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtmulngthf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gtjhhrbcgp.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gtongunxbr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gtuzjosfei.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtcaugpzms.html

UserId = int
来源：http://dali.jinqigufen.top/Article/details/gtuucvauol.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gtehqzzljr.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gtjbdshotp.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gtscozbdwu.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gtxxsbssvm.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gtwbyehkeu.html

python -m pytest -q
来源：http://dali.xuanzx.com/Article/details/gtnhvoteet.html

[U32] Py：代码格式化
来源：http://dali.zhengqikj.top/Article/details/gtttaujuly.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gtohgvdjno.html

[U33] Py：打包发布
来源：http://dali.dianchejie.cn/Article/details/gtqpgldlbk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gtzwqdwidq.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gtotpgbvxn.html

chardet.detect(raw)
来源：http://dali.zhiwuduotai.top/Article/details/gtnjryrcxy.html

[U35] Py：发送邮件
来源：http://dali.quarkkingdee.top/Article/details/gtiprexrva.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gtmbfhaadk.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gtaudoqzhp.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtearjjhlr.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtoevdkdgn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gtrtrxmhyo.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkujbosxr.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gtnubwgkin.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtqfeqebkx.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gtdobcznir.html

[U40] Py：打印到标准错误
来源：http://dali.jqgfzy.top/Article/details/gtcekklnlj.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtijwrtche.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtcyxyomsf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhoulong.xyz/Article/details/gtxavpehhr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gtywzjknkr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigufen.top/Article/details/gtkgsmivbj.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gthmxzeiqf.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gtzphyhric.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gtoihodyrg.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gtojamxsfr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xinyue.icu/Article/details/gtfakatvtu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtjqlmcvba.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtowdbofoe.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gtlwpvcqne.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gthvajoays.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gttsorthzp.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gtzsexdgrj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenzaomai.com/Article/details/gtwxvljrxl.html

[U49] PHP：只读属性
来源：http://dali.ehwqpu.com/Article/details/gttjgidxdp.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtecqfvtdf.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gtdbghgpac.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcfrdlwrs.html

[U51] PHP：数组解构
来源：http://dali.ppjwa.cn/Article/details/gtxtepifag.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtyvzkuvlu.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtbxtsmmaq.html

$double = fn($x) => $x * 2;
来源：http://dali.0kj1m.cn/Article/details/gtawkzeiul.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtbyirsdve.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gtcpaxqjli.html

[U54] PHP：空安全调用
来源：http://dali.nanxuanxn.top/Article/details/gtbtsfpbll.html

$obj?->method()
来源：http://dali.jlsjyb.cn/Article/details/gtsloqleem.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gtdkzonkap.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnjfluad.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpbmgfte.html

f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtwttphpgj.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtpixtcbat.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gtoqcjahlu.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gtihystjyx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtnrxkvnvy.html

[U59] PHP：自定义排序
来源：http://dali.zhixingplan.top/Article/details/gtmcbvxuwb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtvoicwbwj.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gtduktdbfz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gtvdxvzrku.html

[U61] PHP：正则
来源：http://dali.chenlongwang.top/Article/details/gtvbyzdhnf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtuwvuizzh.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gtsfiomlmq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.feifeiyinyue.top/Article/details/gtrduudnxq.html

[U63] PHP：文件读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsjoaprp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenjidiqi.icu/Article/details/gttawxuwvc.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gttguhtfeb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gtjnlbqexk.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gthopayxay.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtopjwaztt.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gtsgovlcjx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuanzhike.top/Article/details/gtqsxjzimz.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtiktdwvvx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gtkdwcxhip.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gtvyhjbrvq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cucudq.cn/Article/details/gtvhbzjcbb.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqqsbjby.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gtpnmgsydg.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gtrhznfjym.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gtzlznxqxl.html

[U71] PHP：抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtgsdaszpd.html

throw new RuntimeException("失败", 500);
来源：http://dali.fzhhl.top/Article/details/gtihmeqxir.html

[U72] PHP：写错误日志
来源：http://dali.chenlongwang.top/Article/details/gthglrdiqz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gtfqupcawc.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gtuqzdobjg.html

parse_ini_file("config.ini", true)
来源：http://dali.meibo888.top/Article/details/gtoqafvoae.html

[U74] PHP：读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gttbweexfn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gtvsfkcxno.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtsjwxatze.html

composer require psr/container
来源：http://dali.0kj1m.cn/Article/details/gtbfuuuhpr.html

[U76] PHP：简单路由
来源：http://dali.chenjidiqi.icu/Article/details/gtxdxrspbp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtijmkzvjx.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gtitxttrqq.html

composer require twig/twig
来源：http://dali.316326.xyz/Article/details/gtbebnapqx.html

[U78] PHP：单元测试
来源：http://dali.jianghu66.top/Article/details/gtrafbpefk.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gtrldfguyy.html

[U79] PHP：静态分析
来源：http://dali.aizwys.cn/Article/details/gtspraxlnk.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gtxwhgqxdh.html

[U80] PHP：代码规范修复
来源：http://dali.dianchejie.cn/Article/details/gtlcywlgvy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gtzixiccce.html

[U81] JS：初始化项目
来源：http://dali.tianlin.xyz/Article/details/gtrdnsiske.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gtjuywhvik.html

[U82] JS：package.json 脚本
来源：http://dali.chenjidiqi.icu/Article/details/gtriotmxzl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yongpay.top/Article/details/gtovfrnujn.html

[U83] JS：ES Module 导入导出
来源：http://dali.pycfn.com/Article/details/gtfrybduai.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtrdujldfk.html

[U84] JS：CommonJS 写法
来源：http://dali.hnxiangtu.top/Article/details/gtgpfqvhom.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtcepduzra.html

[U85] JS：可选链
来源：http://dali.haohaochexian.top/Article/details/gtpkmoxyka.html

a?.b?.c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqofwyeju.html

[U86] JS：空值合并
来源：http://dali.yj20258888.top/Article/details/gtqcrzvmcs.html

a ?? b
来源：http://dali.gaohongyu789.top/Article/details/gthyiyqhfm.html

[U87] JS：解构默认值
来源：http://dali.daxiang520.top/Article/details/gtexdizbcg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gthdgfujdc.html

[U88] JS：对象展开合并
来源：http://dali.gaohongyu789.top/Article/details/gtglyajjxl.html

{ ...a, ...b }
来源：http://dali.guowangkeji.top/Article/details/gtlmckxndx.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gtsqooguvd.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtxuswjwqc.html

[U90] JS：数字数组排序
来源：http://dali.kuanghao11.cn/Article/details/gtuumabwon.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtydljjfoa.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtdyynadhv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gtnyvqtzvl.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gtdkkxcywo.html

structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtsygbpkpn.html

[U93] JS：模板字符串
来源：http://dali.yj202588.top/Article/details/gtwazkjvts.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gtduagiwuk.html

[U94] JS：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gtaiwjtlni.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gtuujdyjob.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gtakrjnzym.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigufen.top/Article/details/gttjhfnrfd.html

[U96] JS：async/await 与异常
来源：http://dali.andypj.xyz/Article/details/gtqowdlnal.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdmdzedu.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtfsvubfad.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtceqzlpmc.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gtcuqqdzoq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gtoyyimetc.html

[U99] JS：事件监听
来源：http://dali.hammf.cn/Article/details/gtcapwmpsc.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gtbofcubmp.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlatlnkva.html

document.querySelector(".item")
来源：http://dali.quarkkingdee.top/Article/details/gttucvhgwp.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gtirhagzvm.html

el.classList.toggle("active")
来源：http://dali.smart0.xyz/Article/details/gtzvbnimbf.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtrmvnfgxo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtfficqeei.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gtquxgfuwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gtdctkbdgg.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gtvisimctn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtntpotlrm.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gtkktwyexa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gtdaulqqhu.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gttegfpxmt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gtudbwxmxk.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtpsppyyog.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtzkknhwwp.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gtguvkbwhr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehcznbnh.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtsjitvswu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtishfdrpx.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gtmbkkzybl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gtktttoglt.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gtjedsonho.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gtwfxhpzde.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gtabcutazx.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtccmmgpmv.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtaqhwxzhk.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtklmtgxqy.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gtzltxmdtn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtfujsympd.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtsfavcpep.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtlmtsgvzn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangtech.top/Article/details/gthaxjxcly.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtibkicfcw.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtctxnqola.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gtcikuuwko.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gtpjuahxcj.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gtmhlsyvxr.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gtxnnjoncj.html

npx vite build
来源：http://dali.sweek.top/Article/details/gtpnlleiix.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gtjwfvccub.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gtuafyqbfr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqpuancbh.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gtaquouwve.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnyewojql.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtjngtxqnm.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gtmityvumm.html

PHP ............ 252
来源：http://dali.ehwqpu.com/Article/details/gtiaropcso.html

JavaScript ..... 252
来源：http://dali.316326.xyz/Article/details/gtephsfzii.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gtzmhuzdka.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gtbzhwgbdu.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtqsrovwqq.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtzbwrgvgg.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gtiuhmbxje.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtfeilsxea.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtcnajvbdw.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gtvdcwgwnn.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gtintxfwox.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gtogugpqkt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtmxuerwor.html

Lua ............ 10
来源：http://dali.nwbrower.top/Article/details/gtozvuqlyl.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gtodgnpwdu.html

Scala .......... 10
来源：http://dali.jianghu66.top/Article/details/gtxlsqrnxa.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtjnypjypd.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gtsjndgqzn.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gtythetnzs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtqrbnwmci.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtnaaozgek.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtznualrdi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtvokspkfv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangdashe.top/Article/details/gtyhlpyfjx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdasiahik.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtsaaycjrw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtpcgruxon.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtzmgfrrys.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabazqjyj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtvakcqwxp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtqeozfrxp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtfbukvapr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtjkndcfld.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiqdzorp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtquleydiy.html


<!-- 参考信息 -->