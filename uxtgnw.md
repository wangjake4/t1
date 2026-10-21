代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuanzx.com/Article/details/gtlasnyosa.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtmgrqvfdj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjufsgzhq.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gtsmuvixpe.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtsulqewnq.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtkdmutncs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtwhwuwmth.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtfrgdzrwy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ehwqpu.com/Article/details/gtpdsdjjpn.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtnwfbdrmi.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcufbimj.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtbcwupncw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtbpusqsmk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqpzhjgwp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtrphmhhqf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqtppjklj.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gttpkwriqb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtrpdjhyvn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtpkzhlwer.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gthvetorjy.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gtqteqlhdz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtfassscfe.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gtxubrtdjn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtilljyfzk.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtiznhenvk.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtiugsbwmq.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gtjlvltwmo.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtnwozbwii.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gtdawfmzvw.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtdowfplyz.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtvnduxvak.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gtbbyfwrsc.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtormbwsox.html

max(d, key=d.get)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaotwrepz.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gtgrkklany.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtdoleuobk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gtjckgwmma.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gtamialjcn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtyctebeqj.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gttilkzvxn.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gtfxkqvgyo.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtaawawash.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtunchqmfb.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtcmbgyinv.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gtmikgfjyn.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtxpxtgwxl.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gtkuaiotpd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtqtwctbln.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtzuytaphg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gtddjvixsi.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gthpcawzde.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtsjwmtpnh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtskuwgufl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtzgfcomrd.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gtectlqwcp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtfobvkskh.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtqwlhtgpx.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmffxflkd.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gteihqgtop.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtnftgucxt.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gtghcikzcr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ydzc1.top/Article/details/gtnfhxyysr.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtfcpvxpdj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtjtgwzkxp.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtnravojlb.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gtodbzryni.html

[U26] Py：并发下载
来源：http://dali.cdnleiting.top/Article/details/gtvgobiwco.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.316326.xyz/Article/details/gtqqfitfmr.html

[U27] Py：异步 HTTP
来源：http://dali.xuetiantiany.cn/Article/details/gtpxjrpksp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gteojnngsi.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gtjhnukcpk.html

UserId = int
来源：http://dali.zhongyouzk.top/Article/details/gtgxsrhdst.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gtmlbxgsqi.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gtfvekzwzb.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gthznwtlly.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtbubnmfvg.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gtkrknbhbq.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtpjqhqwod.html

[U32] Py：代码格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtdzuxpztn.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gtnzoibret.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gtlgpwkiqf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gtxckhqlrx.html

[U34] Py：判断编码
来源：http://dali.feifeiyinyue.top/Article/details/gtsbnjhkma.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumogawtm.html

[U35] Py：发送邮件
来源：http://dali.kuanghao11.cn/Article/details/gtokyoiedf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtewkrqanh.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtuuvlemya.html

schedule.every(10).minutes.do(job)
来源：http://dali.sysykeji.top/Article/details/gtguxzdttq.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtrniqkoii.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gtlhghkwac.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gtklrotdhf.html

Path(__file__).resolve().parent
来源：http://dali.jyoumei.cn/Article/details/gtgfftkgcr.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtusrhomds.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gtyhfglxes.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gtsnunhpec.html

print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtdeqyscxx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gtpkvsfhna.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dashuyun.cn/Article/details/gtyvtditnf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gtabnyfekh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gtrtrbzeqb.html

[U43] PHP：声明命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtqdxqaoau.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gthqeqfyfb.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gtovacfhjy.html

declare(strict_types=1);
来源：http://dali.zdqjudy.top/Article/details/gtzlxezqbw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuxming.cn/Article/details/gtaedljtjf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtbazizebh.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gtsktpgbke.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtgehsfzrs.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gteygfvxgv.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gtcnwguhsl.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtyalqyfzw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdsbhadvj.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gtrfilicnp.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gtxlgymnhz.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gtgwrmzcfm.html

public function __construct(private int $id) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrfcezgp.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gtzcltdpne.html

[$a, $b] = $arr;
来源：http://dali.zhengqikj.top/Article/details/gtqrtmtmyf.html

[U52] PHP：箭头函数
来源：http://dali.tianlin.xyz/Article/details/gtrgivnchb.html

$double = fn($x) => $x * 2;
来源：http://dali.wangdashe.top/Article/details/gtksqudvil.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gteynclkzs.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvswpepvx.html

[U54] PHP：空安全调用
来源：http://dali.nanxuanxn.top/Article/details/gtncwbrbcd.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtrmixjlwg.html

[U55] PHP：match 表达式
来源：http://dali.guannengcc.top/Article/details/gtebmasdsk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtxvizesre.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjynqrsej.html

f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtnntyabyu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtcubeqytv.html

"值: {$a}"
来源：http://dali.guowangkeji.top/Article/details/gtbpfebkhl.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtzoiavuxv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtbjlaukxx.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtawrxoins.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoauifoc.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gtaqlvotmz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtcdltyzaq.html

[U61] PHP：正则
来源：http://dali.jyoumei.cn/Article/details/gtplawbbkw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtbvvzwixs.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gtiodjgaeu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gtsajngcgp.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtuqlngvss.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gtrgpcmasi.html

[U64] PHP：目录遍历
来源：http://dali.yj20258.top/Article/details/gttntxzfsk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hysaishi.cn/Article/details/gtmzhxdwor.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gtfmzixlfe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtquumzpib.html

[U66] PHP：设置 Cookie
来源：http://dali.xylfe.cn/Article/details/gtzznibpnq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gthhnnfnjw.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gtcmgbiygd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gtuchnfvpd.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gtqetgqzay.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gtbqkmtmja.html

[U69] PHP：PDO 预处理
来源：http://dali.jianghu66.top/Article/details/gtuiulebol.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gtikfqtifm.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gtpwlbhxpj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgufenzy.top/Article/details/gthbdijqsl.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gtmmpfioda.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtrugekomr.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gtlsmhfctc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gtxueycxca.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhengqikj.top/Article/details/gtkedvhjup.html

parse_ini_file("config.ini", true)
来源：http://dali.9152youxi.cn/Article/details/gtwzmfmvye.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gtcfvzfaqj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gtaodloqcb.html

[U75] PHP：依赖注入
来源：http://dali.sufxvd.cn/Article/details/gtjprxeula.html

composer require psr/container
来源：http://dali.kuanghao11.cn/Article/details/gtxjlhcscn.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gtbnpoupsl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nwbrower.top/Article/details/gtmjrvhjfx.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gtalgcmrwo.html

composer require twig/twig
来源：http://dali.zycfv.cn/Article/details/gtdkiqazuh.html

[U78] PHP：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtrpguwmyl.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gtmywwrbnb.html

[U79] PHP：静态分析
来源：http://dali.fzhhl.top/Article/details/gtvfcpjckg.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gtlbqjzkgn.html

[U80] PHP：代码规范修复
来源：http://dali.zhengqikj.top/Article/details/gtaknakfen.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.mhx1999.top/Article/details/gtrcixfqgi.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtkgcefgtz.html

npm init -y;  npm i express
来源：http://dali.yangfankeji.com/Article/details/gtwhrmkcjf.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gtypgqkrjx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhiwuduotai.top/Article/details/gtrtcdoysj.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnxiangtu.top/Article/details/gtksrmyddj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtdpsnjbmx.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gtakhfjjzp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.9152youxi.cn/Article/details/gtgnqahfpk.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gtjiellxvz.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gtfcqrjqoj.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gtxkidabev.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gtwynodzah.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gtbtvsxujq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gtcpmnnbhj.html

[U88] JS：对象展开合并
来源：http://dali.zhixingplan.top/Article/details/gtbprrbmcf.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gtllezwuzr.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gtdmrrymwy.html

[...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtranoojuo.html

[U90] JS：数字数组排序
来源：http://dali.sxryk.cn/Article/details/gtbxdretfi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gthxbfvrva.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gtmovicdqk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gtjrqawkpk.html

[U92] JS：深拷贝
来源：http://dali.fengsongda.top/Article/details/gttcrznrsr.html

structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtwazrqcjq.html

[U93] JS：模板字符串
来源：http://dali.yj202588.top/Article/details/gtfgtwyklo.html

`共 ${n} 条`
来源：http://dali.xziqi.cn/Article/details/gtphjmnewm.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gtmurtggzn.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtchffgqxp.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gtzjeyugyx.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gtijvzffkj.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gtcaqceuld.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtxfegnyqr.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gthuxmxlmg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gttgoaokip.html

[U98] JS：fetch 带 JSON
来源：http://dali.yvedp.cn/Article/details/gtcleeqzmg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daria6918.cn/Article/details/gttaoafgid.html

[U99] JS：事件监听
来源：http://dali.hammf.cn/Article/details/gtqovgsvpr.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gtuekyfdpy.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gtriqrjvde.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtymblxbjh.html

[U101] JS：classList 操作
来源：http://dali.cucudq.cn/Article/details/gtcxrbdifi.html

el.classList.toggle("active")
来源：http://dali.iojbl.cn/Article/details/gtcpvbgaqr.html

[U102] JS：本地存储
来源：http://dali.guannengcc.top/Article/details/gtylhtxota.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtjssrpxhr.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gtlvbrckxq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtibeilttw.html

[U104] JS：防抖
来源：http://dali.chenlongwang.top/Article/details/gtfcilpgqp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtlkuasbtw.html

[U105] JS：节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvtiwdza.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gtqhnwyqgf.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtjjrttpaw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gtscxmpjiz.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gttodrbnno.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtwkrtrwlf.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gtmzozbwuz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuxming.cn/Article/details/gtdtxszzff.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gttkylkksx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtzoreskao.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtaoqqnymv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gtfjvqrccj.html

[U111] JS：对象转 Map
来源：http://dali.jqgufenzy.top/Article/details/gtegfgbvde.html

new Map(Object.entries(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtgudccpfk.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gtloqlknuf.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtomitnqei.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gtpspvjozm.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqsybrlw.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoxxsxec.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtvptpthdu.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtnaxoczcq.html

crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtbrvgojyh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtbtlrezbv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtthybybya.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gtfoehydtr.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gtwpzxljgr.html

[U118] JS：开发服务器
来源：http://dali.0kj1m.cn/Article/details/gtkxjbcidx.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gtsojafpht.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtvlwuygwx.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gtjjkkdobi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtvribfmkn.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gtpsheqltx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkjdyjvmg.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gteriifidv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtepawpfkb.html

按语言统计（条）：
来源：http://dali.fzhhl.top/Article/details/gtnvbckmga.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gttvpzbftx.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gtiouydhhi.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gtutnjxahg.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gtxnawxuzg.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtaepmfxmo.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gtsnbwwlfi.html

Ruby ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtoslutsje.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtnacfdpkv.html

C .............. 30
来源：http://dali.ybcxt.top/Article/details/gtxbkzjcxk.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gthaaiznzr.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gtjueynzvl.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gtstixclfs.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gttzoztfzm.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gtulytlmwo.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gtbwzglsab.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtaqwnpbct.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gthbrpyqxy.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtnjtrxhfs.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqaiixtp.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gtspyjhzvn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gthllrqsod.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtwxgodggt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtfqxmnvsl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtcizisknv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gtggepvbcm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtudmbpbmy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtrdjwjztp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtoxfbjwdj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtinyjkzhr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtjtbhnnfj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrtcpmcf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtlkulcuzw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtktsceetw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtoftwrfhf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpqklwpy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtwhtwizut.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gtzsemettx.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gtxbahtxwq.html

S C / C++ 专题                          60
来源：http://dali.hongshengwenyu.top/Article/details/gtimavxhud.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gtbuhtdqcd.html


<!-- 参考信息 -->