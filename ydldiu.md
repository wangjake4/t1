代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtbcvkkrsn.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gtppzxochy.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtefyofmdl.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtixwetcko.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtqnhtuacm.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtktphmodq.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtcyuvgmzg.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtzhcdhafx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtivwiqtzp.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtmfzpnczl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gtkvfdpffc.html

[T56] Scala：样例类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkiztpio.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfgwfgwc.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtslhtkweh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gthyuswaxu.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajciowsv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtetmsnbux.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtnvdowknb.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtsaplddka.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtlshgbrrw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gtcurwjpzj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoplyoli.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gteffnozvq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgmxfjqwk.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtclpbmefj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtedvdmnsh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtyxprootw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangdashe.top/Article/details/gtzgbfwhzb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtfjgxjhby.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gtwlxlyacu.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gttbdxwiep.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtpfhyuutv.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtqqtxgwxn.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtelacmbzb.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gtvuleusan.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtjaqwybub.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gtpqupfxnj.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gtxyfyylrf.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gthtiwyttm.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtfnggjxsq.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtwanfpkri.html

max(d, key=d.get)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaznxtziz.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtlljxljqm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gtgmiiskbo.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtgfioqtbq.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gtzxjjiogn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtuxomqugk.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gtnqcaazdi.html

[U13] Py：固定长度队列
来源：http://dali.xinyue.icu/Article/details/gtzohavysb.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gtcvfzjhzw.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtgpswcqaw.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gtntqimyix.html

[U15] Py：高精度计时
来源：http://dali.sysykeji.top/Article/details/gtcnmsfkkx.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtawqtzabu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gtovivpbva.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtinrfhdmi.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gtxujjiygi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gtkhlutksz.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gthzvdghdi.html

pat = re.compile(r"\d+")
来源：http://dali.yj202588.top/Article/details/gtblbrhibe.html

[U19] Py：正则替换带回调
来源：http://dali.hywenlv.cn/Article/details/gtbjjqlccj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtquvjwpye.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gtemrqymck.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gthjkpoduo.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtxlwbjysb.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtpygsrhlm.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gtwhycsquu.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtojepvqsj.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtgpglwgpt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtapkbumqp.html

[U24] Py：路径操作
来源：http://dali.hfpthk.cn/Article/details/gtstxcvhew.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqfrgplj.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtnmxlgkjx.html

csv.DictReader(f)
来源：http://dali.tanke756.top/Article/details/gtmbgutkaq.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtrdgzfwzr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhpnknmu.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gtfswfkmgb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.andypj.xyz/Article/details/gtrebmorqm.html

[U28] Py：类型别名
来源：http://dali.ehwqpu.com/Article/details/gtixorcgcx.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtljiondau.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtxqnwadlr.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtaikisutb.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gtjjbqvmyv.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gtubnmfoub.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gtaaaizmrj.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkinhktzr.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gtuuirjvvx.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gtjkecimti.html

[U33] Py：打包发布
来源：http://dali.ivvv.top/Article/details/gttlwxizpi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gtrybjyqah.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gtzazzfpmd.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gtzmdmflzs.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gtibsspcty.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.redwolf501.top/Article/details/gtlsgjybnr.html

[U36] Py：定时任务
来源：http://dali.jianghu66.top/Article/details/gticjtlmey.html

schedule.every(10).minutes.do(job)
来源：http://dali.dashuyun.cn/Article/details/gtcrfmwysc.html

[U37] Py：读写 Excel
来源：http://dali.ybcxt.top/Article/details/gtqmirfdxf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gtqifnurkj.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gtpewfbpaz.html

Path(__file__).resolve().parent
来源：http://dali.jinqigufen.top/Article/details/gtnynfaxrj.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gtqhxuwxhv.html

sys.stdout.isatty()
来源：http://dali.yonumen.top/Article/details/gtotctoozp.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gtgzcvouzx.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtpgrqrpks.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtefrkfmjl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtrqzcfebs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gtagykaslo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtoqlipnsu.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gtjqpaucni.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gtkknpfxis.html

[U44] PHP：开启严格类型
来源：http://dali.xuetiantiany.cn/Article/details/gtxanltryl.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtlomfnmei.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gtuaqbuasj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtwozmxmyp.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gtyzioeatl.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gtifnvrtea.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gttpaefezw.html

int|string $id
来源：http://dali.smart0.xyz/Article/details/gtdsnjapco.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gtcvvjdagp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cucudq.cn/Article/details/gthwfwufes.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gtdfscmnce.html

public readonly string $name
来源：http://dali.0kj1m.cn/Article/details/gtpbrgokby.html

[U50] PHP：构造器属性提升
来源：http://dali.dashuyun.cn/Article/details/gtqrpecygb.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gtrnurqwnf.html

[U51] PHP：数组解构
来源：http://dali.jianghu66.top/Article/details/gtczmjyiac.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtanxtgwec.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gtkveqyqaa.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtwzpjekgf.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gtksapsvih.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gtbdtgagcg.html

[U54] PHP：空安全调用
来源：http://dali.yj20258888.top/Article/details/gtdwbezjxh.html

$obj?->method()
来源：http://dali.sysykeji.top/Article/details/gtiygggaqr.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gthturjxln.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gtikxdhbuq.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gtfeuvyafo.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtzkqtties.html

[U57] PHP：字符串插值
来源：http://dali.shuidangran.top/Article/details/gteaenpnoy.html

"值: {$a}"
来源：http://dali.ppjwa.cn/Article/details/gtcjybxxek.html

[U58] PHP：数组三件套
来源：http://dali.sufxvd.cn/Article/details/gtrenonfnz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gtuacbcacq.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtxixvvewx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtakbrcokl.html

[U60] PHP：JSON 编解码
来源：http://dali.birdmap.top/Article/details/gtzcwzxlqo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gtngxairdp.html

[U61] PHP：正则
来源：http://dali.gaohongyu789.top/Article/details/gtihfbgmhz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtzwkvhgba.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtjwxnmphr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gttvclkcje.html

[U63] PHP：文件读写
来源：http://dali.ehwqpu.com/Article/details/gtdtzjiqbb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gthlfqzhlp.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gtbmrcotuv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aibaodan.cn/Article/details/gtwebbufpz.html

[U65] PHP：会话
来源：http://dali.jyoumei.cn/Article/details/gtffmdwgty.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtcmkflaww.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwpqmkwg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gtkzbfrolf.html

[U67] PHP：处理文件上传
来源：http://dali.iojbl.cn/Article/details/gtopxnklgo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtqvznvtzz.html

[U68] PHP：PDO 连接
来源：http://dali.316326.xyz/Article/details/gthlublamt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorieuwbm.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtovvepsvq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yvedp.cn/Article/details/gthxpxuiyd.html

[U70] PHP：PDO 事务
来源：http://dali.quarkkingdee.top/Article/details/gtalxvreoq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gtxqbfhvaq.html

[U71] PHP：抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtdenhxvzn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtsygutxtt.html

[U72] PHP：写错误日志
来源：http://dali.xinyue.icu/Article/details/gtcybqkffu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gtzcdwnfle.html

[U73] PHP：读取 ini 配置
来源：http://dali.guannengcc.top/Article/details/gtdafeklru.html

parse_ini_file("config.ini", true)
来源：http://dali.daxiang520.top/Article/details/gtkonoehlp.html

[U74] PHP：读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtakikaqvp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yanxiufei.cn/Article/details/gtnhifnhjp.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtuhfrqkbc.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gtyghfgpem.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gtycosmrfa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gttcmvwael.html

[U77] PHP：模板渲染
来源：http://dali.kuanghao11.cn/Article/details/gtdiuqfczw.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gtxhrsykgw.html

[U78] PHP：单元测试
来源：http://dali.andypj.xyz/Article/details/gttmtddmce.html

composer require --dev phpunit/phpunit
来源：http://dali.cucudq.cn/Article/details/gtxrmkjleh.html

[U79] PHP：静态分析
来源：http://dali.redwolf501.top/Article/details/gtswtcyuxc.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gtqzahzakr.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtcacpwqfx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gtiyrymakv.html

[U81] JS：初始化项目
来源：http://dali.sufxvd.cn/Article/details/gttbgvsdoq.html

npm init -y;  npm i express
来源：http://dali.hysaishi.cn/Article/details/gtafouvlgk.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxjlivvx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gtiiypanan.html

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gtjhdvyycu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtsrqpndef.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtsihlbrct.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gttjbnavjz.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtepdaebfx.html

a?.b?.c
来源：http://dali.shangyingyoupin.top/Article/details/gtdmesgtah.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gtbmggnxxh.html

a ?? b
来源：http://dali.daria6918.cn/Article/details/gtjhdmvnbe.html

[U87] JS：解构默认值
来源：http://dali.yueranfly.top/Article/details/gtcqdzubvf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.quarkkingdee.top/Article/details/gtbtogwgqp.html

[U88] JS：对象展开合并
来源：http://dali.zhixingplan.top/Article/details/gtdsskovep.html

{ ...a, ...b }
来源：http://dali.mhx1999.top/Article/details/gtqcaawrny.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gtsvyttrsp.html

[...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtshbjmano.html

[U90] JS：数字数组排序
来源：http://dali.andypj.xyz/Article/details/gtcwxvdwwo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtsqrnfhqj.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gtavepwefe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gtkgmtywyj.html

[U92] JS：深拷贝
来源：http://dali.iojbl.cn/Article/details/gtpujzcdcf.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtimwkagct.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtymxirwhf.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gtorrcacym.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtaiaeecqi.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gtaknawaib.html

[U95] JS：Promise 包装
来源：http://dali.sufxvd.cn/Article/details/gtefgsmyel.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskvypxjt.html

[U96] JS：async/await 与异常
来源：http://dali.zycfv.cn/Article/details/gtizquplcr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtqbrgwbma.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gtjtubywey.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtncuistkw.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gtdjxfydus.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gthqourhta.html

[U99] JS：事件监听
来源：http://dali.hysaishi.cn/Article/details/gtlfjduncy.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtcoksldwo.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtceqqdxug.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtdqookrbu.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gtxcnoaosu.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gtxqvghpud.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtltxdeznl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gtjpnshfcv.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gttmmfqvtx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fzhhl.top/Article/details/gtgnrxxwvc.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gtazxucmlq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gttfzbifci.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gtulddddot.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.andypj.xyz/Article/details/gtgetmudrv.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtgyphbadh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.feifeiyinyue.top/Article/details/gthdzpssll.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtulyochpx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtisiamhyy.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gtxddiecbn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shangyingyoupin.top/Article/details/gtvheogitl.html

[U109] JS：数组分组
来源：http://dali.yueranfly.top/Article/details/gtfdsrkkhk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gthhcxxsng.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtxswbnuts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gtgkdexqwp.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gtisvdoaeq.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtngwgnnqa.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gtjdohxvat.html

"7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtjghlsmml.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gtuzbqbebc.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtjcvichni.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gtzjmhrbtz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjxgxywf.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gthxsmevhz.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtajvfodgf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gtxblwsyxq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtlttrtnqw.html

[U117] JS：单元测试
来源：http://dali.yj20258.top/Article/details/gtdoylkacb.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gtmgsmxqdo.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtbhusirlz.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gttlaxnqak.html

[U119] JS：生产构建
来源：http://dali.svipenyu.cn/Article/details/gtwhngnwxq.html

npx vite build
来源：http://dali.birdmap.top/Article/details/gtxvgwgxun.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gtjblrvxeh.html

import.meta.env.VITE_API_URL
来源：http://dali.birdmap.top/Article/details/gtgrquebho.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtujiyzzkz.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtyopdrwim.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnfwodnsz.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gtzktmnmqu.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtmnfryecp.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gtqnnpvjtx.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gtfnzlmeax.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gttbvkcdvi.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtuvmywuez.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtnekntcbg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gtwwkbclsz.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtbxbckzyq.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtmwevhmrw.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtwfoyyxyy.html

SQL ............ 90
来源：http://dali.yuxming.cn/Article/details/gtkaujlfgv.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gtshhgheqf.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtpelmjrkh.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gtvblqopij.html

Lua ............ 10
来源：http://dali.guannengcc.top/Article/details/gtofbyhhtl.html

Perl ........... 10
来源：http://dali.daria6918.cn/Article/details/gtfsicflut.html

Scala .......... 10
来源：http://dali.bjfxy.top/Article/details/gtmxbhevoa.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtkxzsjosn.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gtjusnpucx.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gtmflhfgyg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gtigbjvzbi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtomukcsmz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtznuxaodd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtuapxvech.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gtdvzxotsb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtiozareqj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtuztqrxsk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtiqicqlsn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtjvvrkfal.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtdwfmptxz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtnmfbhdwj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtyifbfzsz.html


<!-- 参考信息 -->