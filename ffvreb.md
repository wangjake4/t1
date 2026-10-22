代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gtfnygfplm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gthlorygfi.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtjowwwttx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtfolsisoe.html

[U05] Py：列表去重且保序
来源：http://dali.hnxiangtu.top/Article/details/gtrmxnjazj.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtoiazcgct.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gtrhtegrwb.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gtqnrafjcl.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtujvfopuc.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gttslihwhz.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvzewctr.html

[y for x in nested for y in x]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsbpprvr.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtqhkmtlyx.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtovsspmeu.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gtracjhdxd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtcskxitnv.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtdjigfsvb.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gtyoqhnhdl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtpoprnakt.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gtcjkhmvem.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtxuniudev.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gtkwccznmx.html

[U14] Py：分组收集到列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnbzffrp.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtiuoupnjk.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtipimzobn.html

t = time.perf_counter()
来源：http://dali.meibo888.top/Article/details/gthknwdvuj.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtevmpzlaq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtdluukzmq.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gtrsosijmq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtqhjpmwpv.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gtyaatqbha.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtatlfweyn.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtgwupqhoc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gtlfxfgsvu.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtnozpodza.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gtdmyrtrrr.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gtddqfgtko.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtdrpulufo.html

[U22] Py：矩阵转置
来源：http://dali.gogol.net.cn/Article/details/gthylhroob.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gtgyjtrxqf.html

[U23] Py：分块读取大文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafqleuzg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gtvndvmhdl.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gtrshbsvgq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtiftqntzr.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gtuvmnqtrx.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtmldpuoyp.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gtsxoytnmh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxinkj.top/Article/details/gtmkyocvfp.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gtjomkluet.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gtixfyukvr.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtqdrezuwn.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gtgnisinwg.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtzhcthvbr.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gtjyaabmat.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gtkpamdddj.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtfwtwpsyd.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gtqewlsgxs.html

python -m pytest -q
来源：http://dali.yongpay.top/Article/details/gtfyijmjov.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gtsqdbsmcr.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gtqaeqmocp.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gtnkhlogqi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gtptoctpxb.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtixhwkrud.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtiiektdll.html

[U35] Py：发送邮件
来源：http://dali.birdmap.top/Article/details/gtejnusvcf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gtbrdslmlg.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gtuavuyokg.html

schedule.every(10).minutes.do(job)
来源：http://dali.ybcxt.top/Article/details/gtflhggzhn.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gtytmszfpd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gtogdbxjwg.html

[U38] Py：获取脚本所在目录
来源：http://dali.pycfn.com/Article/details/gtauwzdcdy.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gttyvmlhkf.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gtvkhpyzmx.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gttararrmq.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gtzvvnygxe.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gttvhxlaam.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtminsfvdu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gtwavmikbt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.birdmap.top/Article/details/gthuiecdez.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gtovvqpnfw.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gtgzbnvdej.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtvnpvwnry.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gtcdwoopyk.html

declare(strict_types=1);
来源：http://dali.guannengcc.top/Article/details/gtgnsjjshw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtliqbaqtk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdglqxodn.html

[U46] PHP：可空类型
来源：http://dali.redwolf501.top/Article/details/gtnfaugptt.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gtropagcfp.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gtuymrwbzi.html

int|string $id
来源：http://dali.aizwys.cn/Article/details/gthxfauhun.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gtgsblcwah.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xylfe.cn/Article/details/gtzxglzimp.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gtupdoupny.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gtlmckugtn.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gtnkrsggai.html

public function __construct(private int $id) {}
来源：http://dali.hysaishi.cn/Article/details/gtjefqiojo.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gtystuaajc.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtzpsvqspr.html

[U52] PHP：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtiqjgujcb.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtgghnfdxr.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtmobynnsd.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gtsczftmfe.html

[U54] PHP：空安全调用
来源：http://dali.yuxming.cn/Article/details/gtdtlzbumc.html

$obj?->method()
来源：http://dali.xinyue.icu/Article/details/gthlxsjjjs.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gtlpvjacvq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtmvosrt.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtccnrankh.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtqmevmnqu.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtdqkrlago.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gtuouiohqc.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gtnvxzbepl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtmjbyvqkp.html

[U59] PHP：自定义排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtndgrkkne.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtvswzxwmn.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtdphpwips.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfujbziz.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtinhyzuxj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gtadnabdfq.html

[U62] PHP：日期对象
来源：http://dali.aizwys.cn/Article/details/gturgalkdc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gtpyjtuicr.html

[U63] PHP：文件读写
来源：http://dali.bjfxy.top/Article/details/gtsztxlmla.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtyhycvyia.html

[U64] PHP：目录遍历
来源：http://dali.tianlin.xyz/Article/details/gtyegfebsl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gtusndnyox.html

[U65] PHP：会话
来源：http://dali.zhixingplan.top/Article/details/gthcwvsztd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hammf.cn/Article/details/gttzmfdozv.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gtqbpnnise.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gtbwtneocr.html

[U67] PHP：处理文件上传
来源：http://dali.yueranfly.top/Article/details/gtedwzrimf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jyoumei.cn/Article/details/gtucyxvppw.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gtfurbwsnf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gtfwxxgkjj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwxooqdi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuetiantiany.cn/Article/details/gteavgshvv.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gtrsyhtxnb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tian-w.cn/Article/details/gtszdzkeca.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gtgkgkdqjr.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtomrlekzg.html

[U72] PHP：写错误日志
来源：http://dali.meibo888.top/Article/details/gtrjkehlaz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtgwzitqkz.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gtkpexdfik.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtmwzxekmp.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtfhgkidxv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjbmryls.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtjbrtenae.html

composer require psr/container
来源：http://dali.ppjwa.cn/Article/details/gtvodommpf.html

[U76] PHP：简单路由
来源：http://dali.hywenlv.cn/Article/details/gtvpktbhxc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ppjwa.cn/Article/details/gtirbrrtwl.html

[U77] PHP：模板渲染
来源：http://dali.yuanzhike.top/Article/details/gtpagnbqcu.html

composer require twig/twig
来源：http://dali.sxryk.cn/Article/details/gtvuizozlv.html

[U78] PHP：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtagugdegn.html

composer require --dev phpunit/phpunit
来源：http://dali.hysaishi.cn/Article/details/gtjnligyuq.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gtuzqtgbfn.html

composer require --dev phpstan/phpstan
来源：http://dali.hnxiangtu.top/Article/details/gtdllbxnyi.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gtrouwbzwe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pengpengdd.cyou/Article/details/gttuaiuexo.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gtmpfbpgum.html

npm init -y;  npm i express
来源：http://dali.chenjidiqi.icu/Article/details/gtscabbndl.html

[U82] JS：package.json 脚本
来源：http://dali.nwbrower.top/Article/details/gtcdyooteq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hongshengwenyu.top/Article/details/gtcbutitdx.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gtxjehxwwm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtkveqsmox.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gtbxphfnge.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gtcexvymth.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gttigdgxqv.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gtiosiwmpx.html

[U86] JS：空值合并
来源：http://dali.jlsjyb.cn/Article/details/gtzcoztfko.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gtfkrskzzh.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtnkcoptjh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gtxuxiximg.html

[U88] JS：对象展开合并
来源：http://dali.pycfn.com/Article/details/gtybsvcufp.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gtxisgsuqq.html

[U89] JS：数组去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvpdhziz.html

[...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtfyfqjisk.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtbdjzjshp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtuwmztoqp.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gtzwgvkhlp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhiwuduotai.top/Article/details/gtrdzhlljb.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gtuwiyayaz.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gthuyuoish.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhaguydw.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtntoetime.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtzvoaacej.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gthiujjdgp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gtcmhzecfl.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gtaefduirz.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtgxqeaodg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyyhzvses.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gtwkbqkrim.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtbtfoijpj.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtxjkauinw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gtgrgsyhpj.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gtajbgkcwr.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gtxcjefbiy.html

[U100] JS：DOM 查询
来源：http://dali.zhoulong.xyz/Article/details/gtqtreqahe.html

document.querySelector(".item")
来源：http://dali.redwolf501.top/Article/details/gtbolziorv.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gtoozjxoyz.html

el.classList.toggle("active")
来源：http://dali.guowangkeji.top/Article/details/gtptpbqwei.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtdadogmzy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gtencqimtq.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gtmhesyatp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jianghu66.top/Article/details/gtlzkbsycr.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gtkfbvrslo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtcjpijjns.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtqkvlalej.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtczwoivmv.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gtqjfqbvfo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gtediribov.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtntzlbfap.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtsyzggdrg.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gtlbkavlse.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pengpengdd.cyou/Article/details/gtijjezvri.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gtihqoerve.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtairwlgir.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gtvnmmrhuy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gtcqnwkhgd.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gttxmxmbit.html

new Map(Object.entries(obj))
来源：http://dali.hammf.cn/Article/details/gtlfnuedpg.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gtqfqeqapl.html

"7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtlkeswzmm.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gtghmsvijt.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtqirgasfa.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrgesqxs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtvtbwtdxv.html

[U115] JS：生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtfqlaofvr.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtugvzaxii.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yueranfly.top/Article/details/gtqgjaxswh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopehcwjg.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtmjbbdwrg.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtpdumroft.html

[U118] JS：开发服务器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizqretyh.html

npm i -D vite;  npx vite
来源：http://dali.chenjidiqi.icu/Article/details/gtfcioamms.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtswgxkdan.html

npx vite build
来源：http://dali.ybcxt.top/Article/details/gtoupgrdgx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gtxsnfusus.html

import.meta.env.VITE_API_URL
来源：http://dali.gotoacloud.top/Article/details/gtasqricce.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzpfyiaet.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtxdbsntkv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwadqxzwu.html

按语言统计（条）：
来源：http://dali.smart0.xyz/Article/details/gtnuypuwuo.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gtisxpgdlo.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtddnbbfsb.html

JavaScript ..... 252
来源：http://dali.cucudq.cn/Article/details/gtkhvutjmn.html

TypeScript ..... 212
来源：http://dali.nanxinkj.top/Article/details/gtduqgpybz.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtacqadzyk.html

Go ............. 212
来源：http://dali.yj20258.top/Article/details/gtuoyrdvmi.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtfedoxxzn.html

C# ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtwugiujzu.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gtewvjmycq.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gtgacrjojw.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gtczbupury.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gtxmjajfnh.html

Kotlin ......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtiqmmwieq.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gtspqhspzn.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtujrxzluy.html

Perl ........... 10
来源：http://dali.hammf.cn/Article/details/gtkaqqooyj.html

Scala .......... 10
来源：http://dali.kuanghao11.cn/Article/details/gtnzwjcwdl.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtpwbajdvb.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gtffeiludu.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gtdemeytwf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtnustioum.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gtytdnjlto.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtralkushw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtzzufdsjh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gtodiijqra.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtfcwctvlm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtrxaphxyk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gttoxztfqu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtzbrnxerf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtaaicxtll.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtfjjgtdwf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtojnejqog.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtozloxhju.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtgwkhlzxu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gtnyqrjsjd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtvouwwlgs.html

Q SQL 专题                              90
来源：http://dali.shzxlz.cn/Article/details/gtzjuiobqj.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gtfenjmawf.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gtocpbujri.html

T 其他语言补充                          60
来源：http://dali.snrcjt.cn/Article/details/gtigegpthw.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gtxbmcugol.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtryvdodit.html

合计                                  2106 条
来源：http://dali.zhengqikj.top/Article/details/gtfmznuzyp.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtawjfnato.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gtqpofbbbh.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtrlbmgajp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gtscjoiyim.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gtnmdnoobh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gtwxmivwir.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gtqawanjyo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gtqqdthrta.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtcyfvzhcz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrpqruygj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gtxzmvicsq.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gtflbpcsyj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthaamegzc.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gtowziyjck.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yanxiufei.cn/Article/details/gtjbiucyuf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gtlxzlkbos.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gtmjoyfkgf.html


<!-- 参考信息 -->