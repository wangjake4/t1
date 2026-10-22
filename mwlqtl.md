代发 wailian999

val a = 1;  var b = 2
来源：http://dali.316326.xyz/Article/details/gtilrkugle.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtmgswyark.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtptgtpgbw.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtbofvpgyi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtkxovytrf.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtmwiermcy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtjqedskmh.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtcsfzigeh.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gthibjsgxp.html

[T57] Scala：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gteeyujere.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtbwzutxwm.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgxxluwm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gtrrszgmew.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gtjynkflhm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtalskmhrq.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtbeygvucp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtcktkiior.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfiemqmut.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtarshvcfx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthcrfvumn.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gtvbdlfuxp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gtmlzxceon.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtumnzwcur.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gtgjprxafn.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtwuglortj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gtxwzbvoic.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtgghysmsm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtguidcbiy.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtirhaebop.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjznoddvs.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gtqkhcpfed.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtntgtwltk.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztdjcplv.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtpnvzialh.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gtkmuvncwk.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gtyvsiouac.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gtoiijbuyi.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gtkoxvlmzi.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtxezvujzu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gtfbeffknj.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtyrunitxu.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtphvusuki.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gtrsfjkcoh.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtnauamzmx.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gtfpotrekl.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqgpgcmb.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqhwkyyu.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gtfkqbpaus.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gtyixnalew.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtrrfunhuf.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdoiqyvq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gtqjroolhq.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtriyprcvy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gtyzgfmgwd.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtglzeqfqy.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtbfkoteyh.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtnpwdqumd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gtnzwpqhwy.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gtpenuacmf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gtlmmfgszf.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gtsftdfppy.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gtnvewqejo.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gtlbbjygsh.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gtdjrxdqlw.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtubrbjztj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gtpivvbvnj.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtuzkarams.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpfebtyx.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gtevvhpgoj.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gthpgnahft.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gttishxpqg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtcqhukizd.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258.top/Article/details/gthaawmasy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gtnxacdcsb.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gtuiizwycs.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtzjgdlffg.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gtsixbmauv.html

@property 与 @x.setter 配合
来源：http://dali.shuidangran.top/Article/details/gtyrewthmc.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtokywoluf.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gtgmwjrfmo.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtkfftdjek.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtizcohdgz.html

[U32] Py：代码格式化
来源：http://dali.jianghu66.top/Article/details/gtfgpvgmtx.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gtxgojdkxi.html

[U33] Py：打包发布
来源：http://dali.yuxming.cn/Article/details/gtwvwexvmc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daria6918.cn/Article/details/gtrfqbbgbd.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gtfhmoczen.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gtovpqbgyg.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtwdontsit.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gtyeczozwv.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gtmqrtiwpo.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gthqsaesdu.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gtxppgcogy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yangfankeji.com/Article/details/gtvkizrgey.html

[U38] Py：获取脚本所在目录
来源：http://dali.tanke756.top/Article/details/gtqyxettsw.html

Path(__file__).resolve().parent
来源：http://dali.xuanzx.com/Article/details/gttjtaayym.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gtxyasxngp.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gtprrhknli.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gtswdxgpiq.html

print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtosxitqxh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gtdjqtllbg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtiletrmsx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gzhubu.top/Article/details/gtzpuboqjc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gtvxlphrlo.html

[U43] PHP：声明命名空间
来源：http://dali.gotoacloud.top/Article/details/gthbsxzznz.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtycreylrx.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gtvcgxwhts.html

declare(strict_types=1);
来源：http://dali.pengpengdd.cyou/Article/details/gteayelbnt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkrpximp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtaeamztoz.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtxmptpjrk.html

?string $name = null
来源：http://dali.zhiwuduotai.top/Article/details/gtmlotdwqf.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gtkvrofhaj.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gtazfdwdyo.html

[U48] PHP：纯枚举
来源：http://dali.zhoulong.xyz/Article/details/gtzgvmbprt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hywenlv.cn/Article/details/gtpknbdzcb.html

[U49] PHP：只读属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqckfllq.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtauzxhzgt.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gtixvoozni.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtqllpyntp.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtmbtgpamy.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gtmzhmyfek.html

[U52] PHP：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gteanxedak.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtqsqstitl.html

[U53] PHP：空合并运算符
来源：http://dali.guannengcc.top/Article/details/gteqfizrfp.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtiuoxtjdn.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gteysrpfok.html

$obj?->method()
来源：http://dali.jqgfzy.top/Article/details/gtdipccwze.html

[U55] PHP：match 表达式
来源：http://dali.sxryk.cn/Article/details/gtczsagapm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnisyysp.html

[U56] PHP：命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrahbiyle.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtyvonxcry.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtjnpdxpny.html

"值: {$a}"
来源：http://dali.yj20258.top/Article/details/gtomhyoqku.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gtvijzxxmh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtycojwbvl.html

[U59] PHP：自定义排序
来源：http://dali.shuidangran.top/Article/details/gtnyduwylo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtwemlwrmc.html

[U60] PHP：JSON 编解码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvlixuug.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zdqjudy.top/Article/details/gtmcdhqqyx.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gtgutzhcxp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtfihbrrdy.html

[U62] PHP：日期对象
来源：http://dali.sxryk.cn/Article/details/gtfjficsjo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cucudq.cn/Article/details/gtwqeokszt.html

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gtxtuatvfs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtkfvwdhuw.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gtsuwqcsbe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtsdanbrmt.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gtzjskvnln.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtviavfhsa.html

[U66] PHP：设置 Cookie
来源：http://dali.redwolf501.top/Article/details/gtfnadhank.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tian-w.cn/Article/details/gtjszaqjrx.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtjlwaadvz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtyteyqalm.html

[U68] PHP：PDO 连接
来源：http://dali.yongpay.top/Article/details/gtsssuepnc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hammf.cn/Article/details/gtvqlodihq.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gtyajaociv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nwbrower.top/Article/details/gtmncxqczd.html

[U70] PHP：PDO 事务
来源：http://dali.c1oappe.top/Article/details/gtsabmlfld.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.andypj.xyz/Article/details/gtkvwodcpg.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtnlfdkajo.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtixucuwad.html

[U72] PHP：写错误日志
来源：http://dali.hnxiangtu.top/Article/details/gtvtgnhjfx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnqzz.top/Article/details/gtkbipuyri.html

[U73] PHP：读取 ini 配置
来源：http://dali.jqgfzy.top/Article/details/gtkzdfjboq.html

parse_ini_file("config.ini", true)
来源：http://dali.smart0.xyz/Article/details/gtgozodsab.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gtrwokqmrj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gtzsuaawsr.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gtutljbtvo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gtrvjjtuse.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gtufpuhycj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj202588.top/Article/details/gtsvlnlxhh.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtsulaerke.html

composer require twig/twig
来源：http://dali.redwolf501.top/Article/details/gtmhlsbngy.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gthjaflewl.html

composer require --dev phpunit/phpunit
来源：http://dali.ivvv.top/Article/details/gtffnabwmv.html

[U79] PHP：静态分析
来源：http://dali.tanke756.top/Article/details/gtdoqupqpf.html

composer require --dev phpstan/phpstan
来源：http://dali.guowangkeji.top/Article/details/gtvbgrvqec.html

[U80] PHP：代码规范修复
来源：http://dali.ehwqpu.com/Article/details/gtcmigaldr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.c1oappe.top/Article/details/gtgrggcvuv.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gtecbuuedc.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gtasamiore.html

[U82] JS：package.json 脚本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpjkyeoi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gtcxvnncqw.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gtwmaqvfir.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtqlwsaqye.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtqjkxmcpf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gtrwkauzqs.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gtzgviavct.html

a?.b?.c
来源：http://dali.zhiwuduotai.top/Article/details/gtvyrnvfvr.html

[U86] JS：空值合并
来源：http://dali.9152youxi.cn/Article/details/gthvhyfguz.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtpiiimbre.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gtboiqhdzv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.quarkkingdee.top/Article/details/gtuoeeeiio.html

[U88] JS：对象展开合并
来源：http://dali.zhixingplan.top/Article/details/gtubtsejlo.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gthginepol.html

[U89] JS：数组去重
来源：http://dali.cashguo.top/Article/details/gtxbzaxhns.html

[...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtdokcjbif.html

[U90] JS：数字数组排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvivpypgc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtqayyqbhh.html

[U91] JS：对象键值遍历
来源：http://dali.chenzaomai.com/Article/details/gtybunzrqz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhixingplan.top/Article/details/gtpntsemur.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gthtzxojhq.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtuatjeqma.html

[U93] JS：模板字符串
来源：http://dali.cashguo.top/Article/details/gtdilwbmhv.html

`共 ${n} 条`
来源：http://dali.yj20258888.top/Article/details/gtkczqhcwo.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtivsvjtii.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gtbfdyyuny.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtjambklim.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtgwkmqqxk.html

[U96] JS：async/await 与异常
来源：http://dali.tian-w.cn/Article/details/gtckzwsobk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtmsbutnyk.html

[U97] JS：并发请求
来源：http://dali.316326.xyz/Article/details/gtnclkpibr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtqkwetndi.html

[U98] JS：fetch 带 JSON
来源：http://dali.cucudq.cn/Article/details/gtdzimbclt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.haohaochexian.top/Article/details/gtddhtzkwk.html

[U99] JS：事件监听
来源：http://dali.iojbl.cn/Article/details/gtacfnweff.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtvrjzueqj.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtiazddpov.html

document.querySelector(".item")
来源：http://dali.aizwys.cn/Article/details/gthcvjmvqn.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gtplwxeoum.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gtfpstmggy.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtnjgsfwmm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hywenlv.cn/Article/details/gtvmndhsxu.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gthkoygdfx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gtxjecthem.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gtxkvebnms.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtdueglubb.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gtggrjfntx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.andypj.xyz/Article/details/gtnqlpyqwg.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlnrzucu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.bjfxy.top/Article/details/gthnmmfrlv.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtluoexiau.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtzyxbkjbh.html

[U108] JS：随机整数
来源：http://dali.pengpengdd.cyou/Article/details/gtykhpfahj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gtvuipgcal.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtjbxylieh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtsyytnmsa.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtewugwcxv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gtlfpumcfb.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtjxxdqdvp.html

new Map(Object.entries(obj))
来源：http://dali.havefunace.top/Article/details/gtutbswhki.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gthzankdqs.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtrvikltdx.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtwjvhjmvc.html

s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtaxrhafkg.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gtqpyagodz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtjfzqusll.html

[U115] JS：生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtuzlaeovi.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtrzybmnam.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gtlrryoprh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtquhmlgvl.html

[U117] JS：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtlofujwob.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gtjagppbaj.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gtlagyrafg.html

npm i -D vite;  npx vite
来源：http://dali.sysykeji.top/Article/details/gtfwloditd.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtmmlxejkz.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gtvjvjbdai.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gtwzsqzdaj.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gturmftmsb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxoahvipl.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gtywthmsln.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvdeyvwwt.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gtlhddzvjr.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gtvbuxrues.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gtqisviczp.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gtmmujhzjr.html

TypeScript ..... 212
来源：http://dali.cashguo.top/Article/details/gtdaxhbkjx.html

Java ........... 212
来源：http://dali.zycfv.cn/Article/details/gtfivhopyy.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtikyoozom.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtmosskejv.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtpzopdhcg.html

C .............. 30
来源：http://dali.tianlin.xyz/Article/details/gtrrhvzkfd.html

C++ ............ 30
来源：http://dali.svipenyu.cn/Article/details/gtjqzdpvxs.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtgnyyqbia.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gtzmzvevjf.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gtgmmymdff.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gtlhngymmt.html

Lua ............ 10
来源：http://dali.fengsongda.top/Article/details/gtmrbigiis.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtjyplwhqe.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gtudimimoc.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtrfhubfrb.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtzohikqdk.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gtkujafnka.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtidfdxjqz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtghygjvuc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtdbsrpccq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtsktxrvcm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtvcslcgnt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gteewxqgwl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtwcpiempg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtalgyywov.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtikzzrzhh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtklbiufje.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtbbiveadg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtixrhsioo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gttmgsrclr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtbvoxagwj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jyoumei.cn/Article/details/gtqmuqwlcu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtmghwpyxs.html


<!-- 参考信息 -->