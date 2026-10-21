代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtnwromdsu.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtzviqikgf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtgetnirih.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtrvjnewyq.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtcgulpyml.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtbbzcxadc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gteqsznybo.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetxfyzbj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gttsynehgx.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gtmrraeeva.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtmuamrbuk.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtegtmxdai.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqfqwojt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkzmioefc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtrdnrsdaf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcctcyjix.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gthpawbfzr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtmzutifkw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gtsvpzntqg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtylmivzzf.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gtyvxgbmbd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtxnaangrx.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gteavcmosj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtftvncdlv.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtsgznbogl.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtnaygghgj.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtqbpcwukh.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtauzgdkqh.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gtamittvxs.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtbmbhrdxr.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtbunuudcp.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtsqvflucx.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtenqezbtr.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtzuybonxf.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gtgekhbftj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gtkzxypdvj.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gthmfsetbg.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gtmjcwjuvl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtpcsdfomp.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gtbrrauvin.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gtjvuggfwq.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gtjyuqxyiu.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gtaeoqgofe.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtihkuesfx.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtstiiwntp.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtnrjblrmw.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gthzbodnjx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlnwdrsq.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepxxqjoc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yonumen.top/Article/details/gtdgekavmo.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gtbvecutzg.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtymyxghui.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtasfxnedu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gtmidllhnv.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gtlewfgsqk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gtcynqqnlj.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gtifiuuzpw.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gtfogcpiys.html

[U22] Py：矩阵转置
来源：http://dali.yonumen.top/Article/details/gtabbwnrfb.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtrjkdvbil.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtlggdhppp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtlkvhsmlr.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gtiekccvdi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtpuiodmkc.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtcwxwlyot.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtadvuzgeb.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtabohlavx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gtcydnqjml.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gtszzjvngq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtgbawjjkb.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtgbebndts.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtusqmrzng.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghvlsdpg.html

@property 与 @x.setter 配合
来源：http://dali.hongshengwenyu.top/Article/details/gtuhlgxjrw.html

[U30] Py：数据类
来源：http://dali.jiagoushi.top/Article/details/gtchwlrydl.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gtcsjiylnf.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnqqfffy.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtcwojcbwh.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gttypmmqgl.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtziegypoe.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gtbtdujgog.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxjkornu.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gtvymzdefw.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqfyxini.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gtwkjqkcmo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gtecpfizyq.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtimtovvwx.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gtfbhgljgk.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqehxotg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gttphshmsm.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gtvcrzbsyf.html

Path(__file__).resolve().parent
来源：http://dali.zhoulong.xyz/Article/details/gtubqcuwmc.html

[U39] Py：判断是否在交互环境
来源：http://dali.sysykeji.top/Article/details/gtmlqyralc.html

sys.stdout.isatty()
来源：http://dali.yj202588.top/Article/details/gtmnemlfpv.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gtptthohts.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gthettljdj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gtpcpkrxmj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gtmtukzqzg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtnezrxasw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gtfkrhjikz.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtguiatwxo.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gtyobafdft.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gtuvrqwhvh.html

declare(strict_types=1);
来源：http://dali.hammf.cn/Article/details/gttjykznlz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcratvxf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtwdynbekx.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gtrccqaici.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gtyhsyqttv.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gtshwuxyfu.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gtijvbdbow.html

[U48] PHP：纯枚举
来源：http://dali.zycfv.cn/Article/details/gtztfwwzga.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258888.top/Article/details/gtxmlzsmvk.html

[U49] PHP：只读属性
来源：http://dali.guannengcc.top/Article/details/gtllsuupze.html

public readonly string $name
来源：http://dali.316326.xyz/Article/details/gtnkpwefwm.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gtwfbicxpo.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtihobvxsf.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gthyzqeatn.html

[$a, $b] = $arr;
来源：http://dali.aibaodan.cn/Article/details/gtbonqnwyh.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtdfrofnuw.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtxdsckpob.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gtvmjnsdqs.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gtdclwolfx.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtqiuzhlza.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gthnbnsgjq.html

[U55] PHP：match 表达式
来源：http://dali.xuanzx.com/Article/details/gtrxwlzxyd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gtohviwwqd.html

[U56] PHP：命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtoobvnwbt.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtnrtqblsu.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtuuqbpwfk.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtfssqlfba.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gtbnakuxzf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cucudq.cn/Article/details/gtowgezdvq.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtvqjglnru.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtnyewekxd.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcweurzxz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yangfankeji.com/Article/details/gtrjqokqmz.html

[U61] PHP：正则
来源：http://dali.shzxlz.cn/Article/details/gtjbplffjv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtqvqannad.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gtbaqmmhng.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gtwfmxodli.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtuuffpedu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guannengcc.top/Article/details/gtesqxcxpy.html

[U64] PHP：目录遍历
来源：http://dali.cdnleiting.top/Article/details/gtragcfxmy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cdnleiting.top/Article/details/gtupjzodng.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gtdiynykek.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtykjbsoax.html

[U66] PHP：设置 Cookie
来源：http://dali.hnxiangtu.top/Article/details/gtfqcopzsf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtftfkxmxv.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gtopfmlegh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gtadyklvly.html

[U68] PHP：PDO 连接
来源：http://dali.zhixingplan.top/Article/details/gtuhnhyefo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ivvv.top/Article/details/gtbupeovme.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtjchlgzrc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gtkyuwgwcb.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gtguzbqxxd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtfkgfxjyv.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtqvdwdksh.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gtutoypdzo.html

[U72] PHP：写错误日志
来源：http://dali.aibaodan.cn/Article/details/gtzivrwtgt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtkhltnsif.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gtndxjbxqc.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gtubeyxhvk.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtkdarptay.html

getenv("APP_ENV") ?: "production"
来源：http://dali.iojbl.cn/Article/details/gtlnrpgwwd.html

[U75] PHP：依赖注入
来源：http://dali.redwolf501.top/Article/details/gtqdtbgpmr.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gtymxkwljb.html

[U76] PHP：简单路由
来源：http://dali.chenzaomai.com/Article/details/gtbniziado.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gtvcuxkgwq.html

[U77] PHP：模板渲染
来源：http://dali.feifeiyinyue.top/Article/details/gtroelatsh.html

composer require twig/twig
来源：http://dali.ydzc1.top/Article/details/gtmocvxblp.html

[U78] PHP：单元测试
来源：http://dali.gzhubu.top/Article/details/gttzhinobc.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gtotijmfsu.html

[U79] PHP：静态分析
来源：http://dali.redwolf501.top/Article/details/gthqhehnjf.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gtczebfzpv.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gttmkvlyhc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cashguo.top/Article/details/gtddboaakk.html

[U81] JS：初始化项目
来源：http://dali.xuetiantiany.cn/Article/details/gtrklhchta.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gttbcpkfln.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtnawkqwky.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gtcwxozzia.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtassxncmh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtbxujxtci.html

[U84] JS：CommonJS 写法
来源：http://dali.kuanghao11.cn/Article/details/gtnxtrifls.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tanke756.top/Article/details/gtpwgqceyz.html

[U85] JS：可选链
来源：http://dali.fengsongda.top/Article/details/gtljtezdne.html

a?.b?.c
来源：http://dali.daria6918.cn/Article/details/gtatrsbsib.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnvwxsjg.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gtcauemjdq.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gtwyhllxky.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cheryme.top/Article/details/gtcrkwyplv.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gtyywqfztz.html

{ ...a, ...b }
来源：http://dali.shuidangran.top/Article/details/gthbjlpbzy.html

[U89] JS：数组去重
来源：http://dali.zhiwuduotai.top/Article/details/gtnriscdcc.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtagvdifaf.html

[U90] JS：数字数组排序
来源：http://dali.yangfankeji.com/Article/details/gtohnldrlg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtrdliyfml.html

[U91] JS：对象键值遍历
来源：http://dali.sufxvd.cn/Article/details/gtaqgxfyhf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hongshengwenyu.top/Article/details/gtfnphvwfd.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gtjeojtyks.html

structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtupkdjije.html

[U93] JS：模板字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtkkmtywli.html

`共 ${n} 条`
来源：http://dali.pycfn.com/Article/details/gtnfvsjefj.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtiutzdwdu.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtkueiepci.html

[U95] JS：Promise 包装
来源：http://dali.meibo888.top/Article/details/gtxpsfamvm.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gtvazkuumm.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gtujodcexs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtsumtoppk.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtrtsjwbad.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtpilpnxel.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gtzzgwywep.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gtdeokayka.html

[U99] JS：事件监听
来源：http://dali.hammf.cn/Article/details/gthdhzoxwp.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gthwkgdrjf.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gtfynbcpzu.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlicmhtm.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gtrjtvejvi.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gtbjruohxe.html

[U102] JS：本地存储
来源：http://dali.nanxinkj.top/Article/details/gtxrjorfmq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtykpsmxps.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gtklwwrsvd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gthnpwdxwo.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtpyedpngi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtkbsvbqzb.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gtyyarztgm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhongyouzk.top/Article/details/gtfiahhoxs.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtnqkikpel.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gtgcxliimv.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gterautkjd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtokcebcpv.html

[U108] JS：随机整数
来源：http://dali.yongpay.top/Article/details/gtnwplxgfd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtcqzkoeah.html

[U109] JS：数组分组
来源：http://dali.chenlongwang.top/Article/details/gthvchfczv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtalstnlsd.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gtqtrxmggk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtjahpuyuf.html

[U111] JS：对象转 Map
来源：http://dali.cashguo.top/Article/details/gteofhsgnd.html

new Map(Object.entries(obj))
来源：http://dali.nanxinkj.top/Article/details/gtbzqrserp.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gtxfjiixtg.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtxzmpjfbz.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gtvutwgqmu.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtfqklmgub.html

[U114] JS：JSON 深比较
来源：http://dali.zhiwuduotai.top/Article/details/gtfujnccai.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gttppvriqg.html

[U115] JS：生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtjrfnwteu.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtenunzaas.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gtjqzsonvu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzsfmbsat.html

[U117] JS：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqbsyskv.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtyvlqtrat.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtrvjenbmm.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gtfunzsbgg.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gtwucvkwfv.html

npx vite build
来源：http://dali.zhixingplan.top/Article/details/gtvtfqpqvc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gtzslrjihj.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gtktkgvuvs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfcdyiutl.html

统计汇总
来源：http://dali.chenlongwang.top/Article/details/gtqhadykou.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbzpmodcd.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gtgdnvflyp.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtxlkjbfvn.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gtevsdignn.html

JavaScript ..... 252
来源：http://dali.yanxiufei.cn/Article/details/gtzukneljj.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gtiexhsrgw.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gttlxcrdvr.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtdpdkplhu.html

Ruby ........... 212
来源：http://dali.yonumen.top/Article/details/gthualnqla.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtckdgeddx.html

C .............. 30
来源：http://dali.sweek.top/Article/details/gtugoqqzdh.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmwttmci.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gtctwugocq.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gtpyxqorga.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtrujvwhru.html

Swift .......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfolfubdz.html

Lua ............ 10
来源：http://dali.nwbrower.top/Article/details/gtvpfxvbcg.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtauxyesxv.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gtpebiqqej.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtgyalbwmy.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gtrntfjymp.html

按章节统计：
来源：http://dali.wangdashe.top/Article/details/gtykeainhu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtmosgkzoy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtrfaydarf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gthidcsoge.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtbijidydr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gtmmtlknbc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtxxkyapac.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gttnryyxss.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gthmpjxmva.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrhkaugp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtesqipzxo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtgcvagclk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtikatllyj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtvochfekq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtuutrrepv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gttaemybss.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtkoplpplc.html

Q SQL 专题                              90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzhxszvd.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gtkwjdjhkr.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtvuqrfjxg.html

T 其他语言补充                          60
来源：http://dali.yj202588.top/Article/details/gtteydoafl.html


<!-- 参考信息 -->