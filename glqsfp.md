代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtyegqongu.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtzbyfoprh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtmlwobghu.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtufdnalsi.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtmekxixbh.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtzqpwyikk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqhjdovk.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtxgudciat.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gtjupopgfw.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gtoioyljbv.html

for (i <- 1 to 10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyxjrkmo.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtjjbamcgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqpybwau.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthowzxtwh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtkttpujws.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwhzxopro.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtutwucrxv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxuqdnru.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtskwjkerb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gtyunczmjd.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gtvpmsaqhs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtuqiewiwr.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gtzhmiyvmd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtqyqwszsk.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gtccrgwuto.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyfinrgx.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtbwhzoetm.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtgqbhbxyd.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzykpsjtu.html

{v: k for k, v in d.items()}
来源：http://dali.ehwqpu.com/Article/details/gtmtsvygua.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gtonlzrthj.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtkwvxjnuf.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtkyxsggtm.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtmuxaveoy.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtnyctnlwu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangshuangyany.cn/Article/details/gtflbuxxzv.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gtyzszfxke.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtgsjnxqvk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuvadgmv.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtprfqjljh.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gtvwubvifj.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtakkmdlnd.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gtzntyiuup.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gtptsbnedm.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gtlzrteutb.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gtlbbctzoy.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtqejwgxcg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqysjksu.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gtnteyhmmf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gtekrydjdg.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gtlvacaozl.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtvliskrct.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnijcmeho.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gtekkugggh.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gtwfwqxuho.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqaeuohd.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtbmyrnzny.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gthonoqhdi.html

[U22] Py：矩阵转置
来源：http://dali.yonumen.top/Article/details/gtsvsbmncc.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gthdmouzxa.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtlbsgxgaj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gtkgtjdmhz.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gtabbvbwib.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtekvxbegi.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gtywonrlxh.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gtbpfpwyna.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtfzqyurkw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gtxloxudvn.html

[U27] Py：异步 HTTP
来源：http://dali.dashuyun.cn/Article/details/gtchtmctrb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gtpbrdjuya.html

[U28] Py：类型别名
来源：http://dali.ydzc1.top/Article/details/gtwzkgdqsk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gtgmdbpahm.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtgatiuzcj.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gtaisgemih.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtgsljddfj.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtagelzdjm.html

[U31] Py：单测
来源：http://dali.hywenlv.cn/Article/details/gtxqnfusea.html

python -m pytest -q
来源：http://dali.tianlin.xyz/Article/details/gtcmhbfxqu.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gtvjedgrug.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gtoxzjnwwt.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gttvexwstv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbupxfzrn.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gtjvixeoza.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtsoeegfwq.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gtwmmlzwck.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gttjrrqqjf.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtxsedweeb.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtpmjknoly.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gtljhjrjcj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenjidiqi.icu/Article/details/gtnapmzjev.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gtekgvffps.html

Path(__file__).resolve().parent
来源：http://dali.ehwqpu.com/Article/details/gtawadwncl.html

[U39] Py：判断是否在交互环境
来源：http://dali.hfpthk.cn/Article/details/gtlwrjhotd.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtdmjmwufi.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtgzwvlutd.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtyjoeqypd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.mhx1999.top/Article/details/gtjwqpzggv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtmlcgkzxn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtiolmnvuo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gtqfyysljf.html

[U43] PHP：声明命名空间
来源：http://dali.svipenyu.cn/Article/details/gtqzfwbbip.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gtpzmpflla.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gtvacresoy.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gtucobjbxl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gtbjyozwql.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtfmchqtrb.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtttsodcew.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtlhtamtyl.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gtpclpvttp.html

int|string $id
来源：http://dali.tanke756.top/Article/details/gtfvaakttd.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gtcmqhtfol.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtjnmizhwh.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gtifyjhqbb.html

public readonly string $name
来源：http://dali.kuanghao11.cn/Article/details/gtjxwwpsmk.html

[U50] PHP：构造器属性提升
来源：http://dali.sufxvd.cn/Article/details/gtfgwqtuqa.html

public function __construct(private int $id) {}
来源：http://dali.xziqi.cn/Article/details/gtxjesrjej.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtsdmhafpy.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtvwzylafx.html

[U52] PHP：箭头函数
来源：http://dali.sysykeji.top/Article/details/gtxugffpzf.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtgsgbecqr.html

[U53] PHP：空合并运算符
来源：http://dali.cashguo.top/Article/details/gtbpvflbxp.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gteocngtkw.html

[U54] PHP：空安全调用
来源：http://dali.quarkkingdee.top/Article/details/gteewqexec.html

$obj?->method()
来源：http://dali.xylfe.cn/Article/details/gtcdfihban.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gtdnktmblo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gttbgnmtfu.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtuupbvaht.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvuesvdcg.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gthmqnwtrm.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gtkjvpambv.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gtfrzfztvp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sufxvd.cn/Article/details/gtxutlnsld.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gtyqwifsrb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gthrnzsfec.html

[U60] PHP：JSON 编解码
来源：http://dali.zhoulong.xyz/Article/details/gtasrjczzf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jianghu66.top/Article/details/gtvnlkysyg.html

[U61] PHP：正则
来源：http://dali.zhoulong.xyz/Article/details/gtqalvbkrs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtrktpymdu.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gtzmwvwdcm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gttokgedsd.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gtgxtmzyzl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gtyayxptai.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gtjpbxwlmr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtbjvfwlpw.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gtvhfwtbzz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtcloecwwl.html

[U66] PHP：设置 Cookie
来源：http://dali.yueranfly.top/Article/details/gttqnskjms.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gtboahmwoi.html

[U67] PHP：处理文件上传
来源：http://dali.zhixingplan.top/Article/details/gtiawzbeom.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtycteqyhk.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gtggjonsyo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cucudq.cn/Article/details/gtwdbfvuwf.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gtcvapiixj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfioyyzd.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gtbgdzzlql.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtkzldemmt.html

[U71] PHP：抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtpbvmkrpz.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtwoejidml.html

[U72] PHP：写错误日志
来源：http://dali.hnqzz.top/Article/details/gtaqqatqgv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gtzjwjmjst.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gtabazfoiy.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gtuaiibrvs.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtwnvcqxxu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtfhwvrhja.html

[U75] PHP：依赖注入
来源：http://dali.aizwys.cn/Article/details/gtzpajkoaq.html

composer require psr/container
来源：http://dali.shuidangran.top/Article/details/gtnzgmiprr.html

[U76] PHP：简单路由
来源：http://dali.andypj.xyz/Article/details/gtvddhgxrp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gttmigsvjq.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtsclpftkl.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gtwbupyicr.html

[U78] PHP：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtfiwtieut.html

composer require --dev phpunit/phpunit
来源：http://dali.jinqigufen.top/Article/details/gtgobkupss.html

[U79] PHP：静态分析
来源：http://dali.redwolf501.top/Article/details/gtrdylhnki.html

composer require --dev phpstan/phpstan
来源：http://dali.quarkkingdee.top/Article/details/gtxsvwvtud.html

[U80] PHP：代码规范修复
来源：http://dali.shuidangran.top/Article/details/gtqycqzsjx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gtudzsaqnk.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gtmgzrsuzi.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gtwnnvgfjs.html

[U82] JS：package.json 脚本
来源：http://dali.gotoacloud.top/Article/details/gtabxkyvdk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gtsklhitsy.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuanzhike.top/Article/details/gtrbavmsxw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtjllcpzzm.html

[U84] JS：CommonJS 写法
来源：http://dali.shangyingyoupin.top/Article/details/gteeaumudi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gtvdxpshui.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gtouomsmmr.html

a?.b?.c
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiubejtn.html

[U86] JS：空值合并
来源：http://dali.gotoacloud.top/Article/details/gtlheuuugd.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gtostqxdtz.html

[U87] JS：解构默认值
来源：http://dali.ivvv.top/Article/details/gtolwqxgnf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gtigdoohtw.html

[U88] JS：对象展开合并
来源：http://dali.hongshengwenyu.top/Article/details/gtwpteciww.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gtfudjqnhy.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gttfdpepqd.html

[...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtsunokshy.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gtveiyekny.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtfcyjncxy.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzahrwat.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtxdfgsmna.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjhspbvz.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtpdwaewdg.html

[U93] JS：模板字符串
来源：http://dali.dashuyun.cn/Article/details/gtwlzoxoya.html

`共 ${n} 条`
来源：http://dali.tian-w.cn/Article/details/gtzqhnmhat.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtyryozqzn.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtskbwrvtf.html

[U95] JS：Promise 包装
来源：http://dali.zhiwuduotai.top/Article/details/gtzrqykjxv.html

new Promise((resolve, reject) => {})
来源：http://dali.ehwqpu.com/Article/details/gtgoykavol.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gtirlrntka.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzzyfnmm.html

[U97] JS：并发请求
来源：http://dali.shuidangran.top/Article/details/gttcvgllpq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtvmivmflo.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gtqxxvbbxe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.smart0.xyz/Article/details/gtiebaebdx.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtwtnhrpcc.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gtxfrkylce.html

[U100] JS：DOM 查询
来源：http://dali.jqgfzy.top/Article/details/gtxqkhlmbc.html

document.querySelector(".item")
来源：http://dali.havefunace.top/Article/details/gtihzorjku.html

[U101] JS：classList 操作
来源：http://dali.cashguo.top/Article/details/gtwgafmgyo.html

el.classList.toggle("active")
来源：http://dali.nanxinkj.top/Article/details/gtlysfdhsx.html

[U102] JS：本地存储
来源：http://dali.quarkkingdee.top/Article/details/gttsrpcawq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhengqikj.top/Article/details/gtjodufsiv.html

[U103] JS：定时器
来源：http://dali.jinghuilouyu.cn/Article/details/gtatrzhcht.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gtumrndgdq.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gttwbstvta.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuzcrfso.html

[U105] JS：节流
来源：http://dali.zhixingplan.top/Article/details/gttqoezmpc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrmcsyfz.html

[U106] JS：日期格式化
来源：http://dali.yvedp.cn/Article/details/gtnwwipopu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtdfhjjrix.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gthawuqkye.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tanke756.top/Article/details/gtofyxunjh.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gtzzkmrizb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gtzjeqmjpm.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gtbxihvyec.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtmcqkrpml.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtygopmitr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aizwys.cn/Article/details/gtozxaksze.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtexzcfjvc.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gtpdmymkea.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtvfstchlc.html

"7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtkicycsge.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gtudakhnxn.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtyrdmffnm.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtubmqwamq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtrdwetcbv.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtiebpwmqt.html

crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtmkdponpl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenjidiqi.icu/Article/details/gtewavzpko.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gtlegflhna.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtjytutvlb.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gttazwtkys.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gtslxvtnqt.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtqzxdftoh.html

[U119] JS：生产构建
来源：http://dali.zhongyouzk.top/Article/details/gtkxwwobik.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gtdakpxior.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigufen.top/Article/details/gthetyheuk.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gteiwzckzx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtftpjweer.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gtqqyymlrl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkcavtkck.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gtekozycpy.html

Python ......... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqofwcbbk.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gtkrxhhcqv.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtdtyjjqil.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtvrvojbkk.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtnfenrxop.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gtmallvgqd.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gtbyislrbr.html

C# ............. 212
来源：http://dali.hysaishi.cn/Article/details/gtwftaldug.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gtusaweaej.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gtnrcgzypq.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gtgvhnmjnq.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gtibrfezym.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtpmhiscry.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gtekiqnvkf.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gtwrpffbvw.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtkebjyyxr.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gtygvxeojg.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtmqbgddon.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gtlltxrrns.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gtnlddgwpi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtsvenztbw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtkvwarpag.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtkizrqksu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtagkklfia.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwoqxcjp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtbmrvvwtb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtzjwkloqg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtwaramdfb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gttuctssko.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gteubbqsha.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtdxpndfvu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtlrdbullm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtzxbjhvvk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtieusaoku.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gttmhvlyed.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtzfhjvcqj.html

Q SQL 专题                              90
来源：http://dali.9152youxi.cn/Article/details/gtvstxmrhc.html

R Bash 专题                             80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpjtvfjw.html

S C / C++ 专题                          60
来源：http://dali.pycfn.com/Article/details/gtitrzlphu.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gtrjpycdjq.html


<!-- 参考信息 -->