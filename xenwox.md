代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtrjahsizp.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtcjpxlgrj.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtavuzjgvb.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtxnuuqkph.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtlapwuldw.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtowvbfuod.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtpkhwdsiv.html

[T56] Scala：样例类
来源：http://dali.redwolf501.top/Article/details/gtlrychrpf.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gtsmcddman.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtodfyilki.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gticgefqrs.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtirnjkvie.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gterbnvpfq.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtjebyiapv.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtooqqliyt.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtsascvrpq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtottxnthx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjyzijcwo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtkdamppym.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqzmttrki.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gthcvqwyim.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtvmlturgs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtmrcqiqig.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gtrhhyhpun.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtjxlhnpeu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtncbxmpfg.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtmyigoahi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gtweikttqn.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjogiyqx.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtvljcjycf.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gtopxnrpwq.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtkkrlpjzd.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtttirvnya.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gtrgdfxruw.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gthqslwdix.html

[y for x in nested for y in x]
来源：http://dali.pengpengdd.cyou/Article/details/gtgsuvoqbx.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtqlkhwhed.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gtyzugfufd.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gtprbnedqj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtvzrijzml.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gtfgzfuuho.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gtqmxihuda.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmdurxdn.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtrvtppfuw.html

[U13] Py：固定长度队列
来源：http://dali.xinyue.icu/Article/details/gtadzplvyi.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtwzieosjq.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtuxemqbut.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtlakwvjkg.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gtupekoedp.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtiivaubjh.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gtcyqffddp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gttougfmnp.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtjtovcbmy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gtdkctjjqz.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtkczuekrw.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtxaplpzta.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtdscrgveq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtutrihnrn.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gtlpbhqdac.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtrohueejl.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gthtrfrmpl.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gtmdcbwnny.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gtoyonsopd.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrpisxxq.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gthwdhshkm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtzkxrlicj.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtirtuuypr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtojolkcai.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtdbvvxazq.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gtdjlkdfza.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtxpktjhvq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtlraerhgy.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gtobezcnjv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guannengcc.top/Article/details/gtgqgvhgoq.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtooixzcfp.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gtbjpdxtds.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gtjiwcxatb.html

@property 与 @x.setter 配合
来源：http://dali.sxryk.cn/Article/details/gtpnoyufnw.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtrjcxblen.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gtrpygujky.html

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gtdvkakbyq.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtdwmeyifo.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpuhmrdc.html

ruff format . && ruff check --fix .
来源：http://dali.yanxiufei.cn/Article/details/gtmcelbdvz.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gtslvcgrbt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.9152youxi.cn/Article/details/gtikupollg.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtfgcwifab.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gtgdzqyltv.html

[U35] Py：发送邮件
来源：http://dali.kuanghao11.cn/Article/details/gtqtwfgiqp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gtumpbxjwm.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtddalmdja.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmoxtzyz.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gtsthlvpoa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtjhdavtkz.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtpafbozsq.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gthxelautj.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258888.top/Article/details/gtzuczjwlt.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gtmncjxclm.html

[U40] Py：打印到标准错误
来源：http://dali.gaohongyu789.top/Article/details/gtsbcoawbv.html

print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtutsobcml.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtfbbhhaal.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jyoumei.cn/Article/details/gtobwffruu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtuodbxjkw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenjidiqi.icu/Article/details/gttrdffnzh.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gtmjfzypui.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gtluzhpmby.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtzclmgygm.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gtyvlenfkw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gtlpbujrsq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtqdxqedwm.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gtaolcdwoa.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtqjfcydwj.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtmzzboypm.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gtrgctikpl.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gtxconeirq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tianlin.xyz/Article/details/gtbinvklvy.html

[U49] PHP：只读属性
来源：http://dali.chenzaomai.com/Article/details/gtshgcjklw.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtendtnrvv.html

[U50] PHP：构造器属性提升
来源：http://dali.yuanzhike.top/Article/details/gtoghtoylh.html

public function __construct(private int $id) {}
来源：http://dali.sysykeji.top/Article/details/gtoabgxrsq.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmggupjx.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gtclgoboyv.html

[U52] PHP：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtmcqxxyfr.html

$double = fn($x) => $x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtwmnxmhyr.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gtctxtxivc.html

$v = $a ?? $b ?? "default";
来源：http://dali.sxryk.cn/Article/details/gtccvzxmsh.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gtgwfdkjsq.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gtgjeajndd.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gtywngptbz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gttsbugcrc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtuwxhopmm.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gttdmtmppc.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtyarilfwm.html

"值: {$a}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsybpdzzx.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gtaqojtigz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.iojbl.cn/Article/details/gtiopkkets.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gtjfcrijdh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtluyutxbr.html

[U60] PHP：JSON 编解码
来源：http://dali.fzhhl.top/Article/details/gtaapwhenm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gtvssiadhe.html

[U61] PHP：正则
来源：http://dali.kuanghao11.cn/Article/details/gtazqxdiwl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtmjmgxsfn.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gtcaxzaulz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gtgzgnghwh.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtidmjvlzn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dashuyun.cn/Article/details/gtulzrfjpd.html

[U64] PHP：目录遍历
来源：http://dali.nanxinkj.top/Article/details/gtpnedxcie.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.snrcjt.cn/Article/details/gtshpuhfcm.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gtvlivjnkq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tanke756.top/Article/details/gtfitayjus.html

[U66] PHP：设置 Cookie
来源：http://dali.yj202588.top/Article/details/gtnhynpbta.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gtnkzpkkad.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gtbamcgirw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxggyfke.html

[U68] PHP：PDO 连接
来源：http://dali.316326.xyz/Article/details/gtsnfyiwpq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gtlbqpeiqf.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gtkqdrtytl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dianchejie.cn/Article/details/gtxihjvpff.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gteaoyocmp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gtxrzbmofp.html

[U71] PHP：抛出异常
来源：http://dali.ivvv.top/Article/details/gtbsosupsc.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtdhsryxxf.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtrscikwha.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrufhnqv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtbsnhhlnk.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtbyjbdkfa.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtwoazxqtx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guowangkeji.top/Article/details/gtvrwcwtkn.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gttqikluwv.html

composer require psr/container
来源：http://dali.cdnleiting.top/Article/details/gtqmlbppys.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtisqqvwoa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gtrvwaplyj.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gtebtrgxfr.html

composer require twig/twig
来源：http://dali.0kj1m.cn/Article/details/gtiidtdmqd.html

[U78] PHP：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtihwrpffs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhengqikj.top/Article/details/gtyyqvpwxw.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gtmdzapomu.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gtjvbesqlr.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtnpjeiiuj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gtxsulxwve.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gtmbiysxzk.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gterwmvadl.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gthenvuwpg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gtetkqstit.html

[U83] JS：ES Module 导入导出
来源：http://dali.yonumen.top/Article/details/gtupappjix.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisridzmb.html

[U84] JS：CommonJS 写法
来源：http://dali.fengsongda.top/Article/details/gtgejlxstp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtjttxzcjt.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gtgmugprez.html

a?.b?.c
来源：http://dali.jinqigufen.top/Article/details/gtriopcnpa.html

[U86] JS：空值合并
来源：http://dali.chenlongwang.top/Article/details/gtneyxtxij.html

a ?? b
来源：http://dali.jianghu66.top/Article/details/gtauuqikwz.html

[U87] JS：解构默认值
来源：http://dali.hfpthk.cn/Article/details/gtibuivsqm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gtpoazmzbh.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gtndyhyhcl.html

{ ...a, ...b }
来源：http://dali.feifeiyinyue.top/Article/details/gtgmslqyuu.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gtlatjcthm.html

[...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtawzzcsnv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gtemaykpsk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtvbmjqtex.html

[U91] JS：对象键值遍历
来源：http://dali.xziqi.cn/Article/details/gthlxjvptf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuanzhike.top/Article/details/gtzvgzsykq.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdozgnxgb.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtwxjthuet.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gtaheymkgi.html

`共 ${n} 条`
来源：http://dali.hysaishi.cn/Article/details/gtcewrbend.html

[U94] JS：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtoxpxghgf.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gtpnfufkhg.html

[U95] JS：Promise 包装
来源：http://dali.pycfn.com/Article/details/gtmqxeqrwv.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtwlfxbpsd.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqwoxhzh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtwltnamnt.html

[U97] JS：并发请求
来源：http://dali.cucudq.cn/Article/details/gtscnolrin.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtpsrrotpo.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtjognktps.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtznvlhpuc.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtpoyvowkn.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtxohrwnuu.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gtkikgycxl.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gtxlrfgidx.html

[U101] JS：classList 操作
来源：http://dali.tianlin.xyz/Article/details/gthzuldokn.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhesesav.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gtxkupvdfv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.bjfxy.top/Article/details/gtivytxsxk.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gtbndwzrmg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtcwbnywev.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gtkhwafzbt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtumcnsgqq.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gtxfryvkqk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gthtqrdgux.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtxvggcvbm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtyyqjbtmh.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtmcjeqsxz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtpqamcpec.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtrvjzxwxs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtgzmopzwn.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gtkdfafjbb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtbldlrpgj.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gtagdkvuvv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gtzbxfxjbn.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gttwqltiyo.html

new Map(Object.entries(obj))
来源：http://dali.cheryme.top/Article/details/gtkoesfthe.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gtcjjattnb.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtmhwtavdn.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtugubicji.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtkieblanb.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukmwgwbz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnqzvigs.html

[U115] JS：生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtngetrczj.html

crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtloyfgvti.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gtmozjaoxk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gtukmckgmk.html

[U117] JS：单元测试
来源：http://dali.meibo888.top/Article/details/gtlpcgpssd.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gtwmkunfdo.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gtkfnuvtqk.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtatzxosjw.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtuveebelg.html

npx vite build
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrfkzypg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gtvpfzwdsz.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtanqoajhf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjjbffuny.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gtnmcnrpen.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttqfhwfcd.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkurqlpbo.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gtywikmefm.html

PHP ............ 252
来源：http://dali.xuetiantiany.cn/Article/details/gtpazhnven.html

JavaScript ..... 252
来源：http://dali.hfpthk.cn/Article/details/gtbetoxqqm.html

TypeScript ..... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrptwbkbl.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtwxkplxtt.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gtlqpjfhhe.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gtpjouvoen.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gtrdqikvzl.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gtfsxciyle.html

C++ ............ 30
来源：http://dali.hywenlv.cn/Article/details/gtvrwdqzzj.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gtczoafywd.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtvyqtfquw.html

Kotlin ......... 15
来源：http://dali.guannengcc.top/Article/details/gthvfwqyrf.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gtvnjnswnx.html

Lua ............ 10
来源：http://dali.hnxiangtu.top/Article/details/gtuykjnzex.html

Perl ........... 10
来源：http://dali.dianchejie.cn/Article/details/gtjtgptuoc.html

Scala .......... 10
来源：http://dali.jianghu66.top/Article/details/gtdvnmheht.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtxoicztoy.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gtlsltqqju.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gtgvyfsdau.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtmaiauxoi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtwpabkyxo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszvuhbwk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gtctbnujpy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtfuxhrtet.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtjuokeijn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtwgnrhozn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtseztneea.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtywwycoea.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtikyzngzl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexfjkney.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtxlzzibbn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gttgwirocx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtnslhdzqr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gtndashiux.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gttrmqtzto.html


<!-- 参考信息 -->