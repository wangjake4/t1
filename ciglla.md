代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtayjjcavz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gtwfeoxdia.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gtihbdgfls.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtvxwjjtrr.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtjqohsbvk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gtolcgqzjc.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtuvljnsju.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shuidangran.top/Article/details/gtonplivrc.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gtuhbpgeta.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtzsqnbjtk.html

[U06] Py：合并两个字典
来源：http://dali.zycfv.cn/Article/details/gtbyadxlpw.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtpizfpfzt.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gtagcedxlx.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gtjkweqzwj.html

[U08] Py：展平二维列表
来源：http://dali.ehwqpu.com/Article/details/gthporzavj.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtkcpkrhlh.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtqztqtyhi.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gtmdjohvqg.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtizrzjbxq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gtgdbbtduw.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gtpacpwmkd.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gtlzbfzqid.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtcilaxkuu.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtwoortjzr.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtptaehyjr.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtdabnvcbj.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtzepbaphu.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gttxlkatyg.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gtohyqilcj.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gthoxurtcy.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gthdyjvppb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hysaishi.cn/Article/details/gtsshykiur.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtgskwenvl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gtsxapiplm.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gtgnneebwq.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gtvlyriwxp.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gtqojbafnq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtcvjrnuud.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtabliwxcd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtrvmogvmj.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gtrcothqcq.html

@contextlib.contextmanager
来源：http://dali.smart0.xyz/Article/details/gtztpnpbpo.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gtqlmxxylz.html

list(zip(*m))
来源：http://dali.c1oappe.top/Article/details/gtpagocarf.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gtzkeynzdo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gthemytzra.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gteilappyc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gthzmjsjph.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtvvovdmvl.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtblcqiwaq.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gttzltnrfy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtdglzxbcg.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gtgalgbege.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gtyvuibafn.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gtqrikzezw.html

UserId = int
来源：http://dali.jinqigufen.top/Article/details/gtourfhrxk.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtmihlarsz.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gthelglfzg.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtsloufait.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtjxntzlcp.html

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gtkjcvmexv.html

python -m pytest -q
来源：http://dali.cucudq.cn/Article/details/gteevcwqud.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gtxfiycqkx.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gtkocmcbdp.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gtzahuwqio.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gtbxyqgmrq.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gtwhpsxhnt.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gtqbnhuoor.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gtirntktjs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgufenzy.top/Article/details/gtaoldujxk.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gtwriruzhc.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gtimkfdvpy.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gtmwokoput.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gtjiprykrq.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gtqucraotu.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gtzwbhvemq.html

[U39] Py：判断是否在交互环境
来源：http://dali.hfpthk.cn/Article/details/gtxibstmbn.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gtdgyvvzzw.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gthejkjhii.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtrteffjch.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hfpthk.cn/Article/details/gtnqwqgsle.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gtuhajaxyn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhongyouzk.top/Article/details/gtabdwuosa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtwsrlqkvu.html

[U43] PHP：声明命名空间
来源：http://dali.yuxming.cn/Article/details/gtjdxejyty.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gtivkemycy.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtecemfiun.html

declare(strict_types=1);
来源：http://dali.bjfxy.top/Article/details/gtgzmaeutv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gtkrjqfvdx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkkfjptga.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gtjshzdyoe.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gtfxagufvj.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gtfuxwmrpt.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtporwxeuy.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjyplrdi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gtcfazfznp.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gthurkaoxr.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gtkqhxenpf.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtnorsqrgs.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gtdfwvtvxs.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gtatxbkprd.html

[$a, $b] = $arr;
来源：http://dali.ydzc1.top/Article/details/gtauhryfds.html

[U52] PHP：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gtqsdpqwfp.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gtijgcjpqf.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gthjkemlde.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtjgsqloqn.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gtcqnpajru.html

$obj?->method()
来源：http://dali.tian-w.cn/Article/details/gthvwdfbkv.html

[U55] PHP：match 表达式
来源：http://dali.daxiang520.top/Article/details/gtrqktalzu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtbfajehya.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gtetkkysec.html

f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gthmlukiji.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtrgszqnve.html

"值: {$a}"
来源：http://dali.bjfxy.top/Article/details/gtzynhnajt.html

[U58] PHP：数组三件套
来源：http://dali.hongshengwenyu.top/Article/details/gtrtqsfiry.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gtfflihesm.html

[U59] PHP：自定义排序
来源：http://dali.svipenyu.cn/Article/details/gtcjvuljsb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiucvhlk.html

[U60] PHP：JSON 编解码
来源：http://dali.tianlin.xyz/Article/details/gtriuxrlbx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtmmfcogmi.html

[U61] PHP：正则
来源：http://dali.smart0.xyz/Article/details/gtzawncrfi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtthzfliuj.html

[U62] PHP：日期对象
来源：http://dali.sysykeji.top/Article/details/gtbijzcldm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yueranfly.top/Article/details/gtiwfmfpkb.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gtllrjumtp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yonumen.top/Article/details/gtxaffdgkj.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gtdkmohmva.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtfminjvha.html

[U65] PHP：会话
来源：http://dali.nwbrower.top/Article/details/gtqxprkqjx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtjoebtdso.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gtecttigpe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xylfe.cn/Article/details/gtopccmsoq.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gthqiidrsx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yonumen.top/Article/details/gthskcwkgc.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdmftcre.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sxryk.cn/Article/details/gtcornvtcw.html

[U69] PHP：PDO 预处理
来源：http://dali.chenjidiqi.icu/Article/details/gtgdngaesw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gtpksvpwqf.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gtlnccqnni.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gthjsurxrz.html

[U71] PHP：抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnwimbic.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gtasrtrcek.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gtbqyxoicy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gtxdurstxx.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gttgxyetsg.html

parse_ini_file("config.ini", true)
来源：http://dali.zycfv.cn/Article/details/gtzvutjxqb.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtaejorrop.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gtkmteynmq.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gtqqknolme.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtanyohaaz.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gtntjipnii.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gtdynydwsx.html

[U77] PHP：模板渲染
来源：http://dali.tianlin.xyz/Article/details/gtmsrhlwya.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gtomkjtfkq.html

[U78] PHP：单元测试
来源：http://dali.fengsongda.top/Article/details/gtqpreksoj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhengqikj.top/Article/details/gtcaotzwya.html

[U79] PHP：静态分析
来源：http://dali.gaohongyu789.top/Article/details/gttfxdnrnj.html

composer require --dev phpstan/phpstan
来源：http://dali.chenzaomai.com/Article/details/gttpefgjjr.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiroduab.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gteutsapyc.html

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gtaqqqobcj.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gttgtnaeot.html

[U82] JS：package.json 脚本
来源：http://dali.aibaodan.cn/Article/details/gtazcrrqsj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gtplavxeyc.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gtihgqfmui.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtsiyyqisi.html

[U84] JS：CommonJS 写法
来源：http://dali.andypj.xyz/Article/details/gtctqmqeaj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.316326.xyz/Article/details/gtbpahgbpy.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gtdrvbfxxl.html

a?.b?.c
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrmvuexb.html

[U86] JS：空值合并
来源：http://dali.yj20258888.top/Article/details/gthfqydepr.html

a ?? b
来源：http://dali.haohaochexian.top/Article/details/gtwjzpsnts.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtirkppeya.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jlsjyb.cn/Article/details/gtpsnhsiwi.html

[U88] JS：对象展开合并
来源：http://dali.zhiwuduotai.top/Article/details/gtvejcresu.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoqmpchl.html

[U89] JS：数组去重
来源：http://dali.sweek.top/Article/details/gtodqercaa.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtkdbqucqy.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gtmbctmvyd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtzrlfhjno.html

[U91] JS：对象键值遍历
来源：http://dali.yueranfly.top/Article/details/gtzzhnwrpf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtdhccsxap.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtmcuduszk.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtpvbqwlpx.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmlgwpswy.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gtgxcnjsmj.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtivvijvib.html

const double = x => x * 2;
来源：http://dali.nwbrower.top/Article/details/gtvpgqjnfn.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gtwfxpcxln.html

new Promise((resolve, reject) => {})
来源：http://dali.sxryk.cn/Article/details/gtghijtyqf.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gtiaxkrcux.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gttsmyjwgm.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtlppmqhqr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtcsyfsdeg.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gtebgawprx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtvqzxygap.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtenbgjaic.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gtzqlnarvs.html

[U100] JS：DOM 查询
来源：http://dali.chenzaomai.com/Article/details/gtfuuxnhsd.html

document.querySelector(".item")
来源：http://dali.bjfxy.top/Article/details/gtydkhyqsg.html

[U101] JS：classList 操作
来源：http://dali.hysaishi.cn/Article/details/gtmqhspedk.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtgygqrrzv.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gtwjxuqppy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.feifeiyinyue.top/Article/details/gtfrrcjmcw.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtsvedwgyf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yvedp.cn/Article/details/gtxdedsvnz.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gttedtolmf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtptvrbbac.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gtfrmyfrok.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gttnqiieeh.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtwrrwakdz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gtjkgydvxb.html

[U107] JS：数字千分位
来源：http://dali.smart0.xyz/Article/details/gtagokdemk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gttpzbrdkq.html

[U108] JS：随机整数
来源：http://dali.zhixingplan.top/Article/details/gtebokqhfn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gtemypynoc.html

[U109] JS：数组分组
来源：http://dali.yj20258888.top/Article/details/gtjprkxkqw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtuehxlypv.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtjdgllxli.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daxiang520.top/Article/details/gtzwmpbyad.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtepfodqwi.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gtxqzvszgk.html

[U112] JS：字符串补位
来源：http://dali.jyoumei.cn/Article/details/gtlfyaxznd.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtrcbygals.html

[U113] JS：正则替换全部
来源：http://dali.xinyue.icu/Article/details/gtyjaylxrh.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtfzawiwhf.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gtkrojuuiy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtpdoryexp.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtwoaokcxu.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtnolrkykw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gteicujzjl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gtkwmuptac.html

[U117] JS：单元测试
来源：http://dali.ybcxt.top/Article/details/gtsptkhagk.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gtwtqupwwi.html

[U118] JS：开发服务器
来源：http://dali.fengsongda.top/Article/details/gtixlnxtbs.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gtpxrotvei.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuhqiiqr.html

npx vite build
来源：http://dali.andypj.xyz/Article/details/gtfrvnwjrp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gtrxpkkulr.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gtieaywqjn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtytjkrllq.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoupzdvo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrbmyoukj.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gtykyftbnq.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gtmedpzbpj.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gtnebmtvbs.html

JavaScript ..... 252
来源：http://dali.sweek.top/Article/details/gthndtxzst.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gtzfwzbqux.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gtjhyeigoq.html

Go ............. 212
来源：http://dali.sweek.top/Article/details/gtqqqajssq.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtmexbkrwa.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gtrycucgey.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gtykjherdv.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gtqsbarkgb.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtdxfiywxd.html

Bash ........... 80
来源：http://dali.yj20258.top/Article/details/gtgvfiynie.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaunbeqgl.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtmmeshizo.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtmjltdbin.html

Perl ........... 10
来源：http://dali.yvedp.cn/Article/details/gtdddrnaec.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gtpgnpryqm.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtjmknowdv.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gtpicbyhzl.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtrffgxbkh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtixzkkaew.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtmpeswiki.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtqindymuo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gttckhjyml.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbckvihq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtqdrxwayq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtknqargfy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtuswpxeyc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtlmipjwcr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtezigxgsj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtopopknyy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtluemczex.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtmgaphsjz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtylcmmodl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gtxboglspf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvsyaxwc.html

Q SQL 专题                              90
来源：http://dali.xuetiantiany.cn/Article/details/gtcmtkbiaw.html

R Bash 专题                             80
来源：http://dali.dashuyun.cn/Article/details/gtumcaycql.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gtvnpectlh.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gtfgnjulvl.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gtthkejmlr.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtrapfitzd.html

合计                                  2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gtnzyzupqt.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtlodpulyc.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gtjpvhacbt.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtkbjxtoor.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuanzhike.top/Article/details/gttosxiffz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.mhx1999.top/Article/details/gtspzzyjti.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gtukhwzauj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangshuangyany.cn/Article/details/gtazedlucf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gthfkyngqq.html

—— 文件结束 ——
来源：http://dali.yueranfly.top/Article/details/gtmitxmlmh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtydypicrn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gtwirbpjps.html

Common Programming Examples Cheat Book
来源：http://dali.yanxiufei.cn/Article/details/gtzaayvkxc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtevvmcgjk.html


<!-- 参考信息 -->