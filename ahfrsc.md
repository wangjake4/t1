代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtlrucojwd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gtvhxkrtus.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtapkmubso.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gtplfjcikh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtctnvucnm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtpkzrzgle.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtjcakwkns.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtsfawzrwp.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gtyjyrybuz.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtyiwphijn.html

[U06] Py：合并两个字典
来源：http://dali.quarkkingdee.top/Article/details/gtmzsesbxf.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtlwowsfwq.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtllfrlwsg.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtijafrmny.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtbseunpbw.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gtvruhbfmb.html

[U09] Py：字典取最大值的键
来源：http://dali.gzhubu.top/Article/details/gtahhfnjtz.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gtfqtbcved.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtpzgcfbab.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhneccro.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gtyrvtsdkp.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtomrospxi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtljavjdgg.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtvqeypyky.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gthmdswxss.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtpcrugshg.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gttvheffdt.html

defaultdict(list)
来源：http://dali.smart0.xyz/Article/details/gtlarkdyzd.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gtshbdtymd.html

t = time.perf_counter()
来源：http://dali.yangfankeji.com/Article/details/gtqswzptrc.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtfbppdenw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtampumlal.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gtboylbypx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zycfv.cn/Article/details/gthizxtpzj.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gtfdgsujnx.html

pat = re.compile(r"\d+")
来源：http://dali.cucudq.cn/Article/details/gtetweyxbg.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gtojtizbsv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gtngffarlc.html

[U20] Py：缓存函数结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyxagegu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gttjwvbuqm.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gtcwnaiism.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gtmtxvvnsd.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtpsysgbuh.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gtoebmjqzs.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258.top/Article/details/gtcilvteep.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtoqxfoszn.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gtxcopksnp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gttegijdoq.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtzarrwphy.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gtlnbuqvam.html

[U26] Py：并发下载
来源：http://dali.gzhubu.top/Article/details/gtkwmldotu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gtiqxhblqs.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtfnkgojie.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gttgcircqm.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtgyqueckm.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjnbgvdd.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvmrzixb.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtdctcuguw.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gtvwuzbtsx.html

@dataclass(slots=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwwqkqmk.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gtkcbiolrc.html

python -m pytest -q
来源：http://dali.pengpengdd.cyou/Article/details/gtldoiulfg.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gtfzimrdxc.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gtniadzpay.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gtatzvuisg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtrtregfvq.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gtqletusza.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtgackijcq.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gtqflgdvyh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gtcqjvbppi.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqgqkaps.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gtwodoounk.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtezfxidtu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.smart0.xyz/Article/details/gtjzkokhnl.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gtficlsywn.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gtdqljuhuc.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtxxaworuz.html

sys.stdout.isatty()
来源：http://dali.gotoacloud.top/Article/details/gtlxqfrfsm.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtdefclwmy.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtdchnznyk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gtjypaksbu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gtfvpbhkkf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtrmxgvvjk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gtxlkiwmrc.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtolxtushf.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gthohcdpwt.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gtbxwefwrr.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gtxftnibwh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnxiangtu.top/Article/details/gtzzksahfx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtcvupfrkz.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gtlaybqiay.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gttvgrzjss.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gtnycfklwu.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gtegfwboxa.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtrwbbongo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gtsqtelbgk.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gtskumxxsl.html

public readonly string $name
来源：http://dali.hywenlv.cn/Article/details/gtzyiiskyk.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gtfibflpin.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gtkwpebpqf.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcpafyel.html

[$a, $b] = $arr;
来源：http://dali.cashguo.top/Article/details/gtpttgkeeo.html

[U52] PHP：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtfifxojjr.html

$double = fn($x) => $x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtresqwbow.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gtltktqtbc.html

$v = $a ?? $b ?? "default";
来源：http://dali.ppjwa.cn/Article/details/gtwfffkjfy.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttufrokip.html

$obj?->method()
来源：http://dali.zhixingplan.top/Article/details/gtakgudase.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gthapmghyt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gtrtfaeyzh.html

[U56] PHP：命名参数
来源：http://dali.fengsongda.top/Article/details/gtyymbhdqg.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtpxzrlkmi.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gthrcxzbpo.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gtbldxwdjg.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtqlvdxrdg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jianghu66.top/Article/details/gtqdbcpjpo.html

[U59] PHP：自定义排序
来源：http://dali.meibo888.top/Article/details/gtxgzpolat.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtdrdofeaq.html

[U60] PHP：JSON 编解码
来源：http://dali.tian-w.cn/Article/details/gtdfjlgrfv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqzgjioo.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtdgxwqawj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtkjtxmbzs.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtihtpxfld.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gtsthvxgji.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtfsjidrjj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gtmulmoyis.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gthxvcmrpq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gtkntjyknv.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gtvoixxhdo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhxewanr.html

[U66] PHP：设置 Cookie
来源：http://dali.yangfankeji.com/Article/details/gtyznrrklf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gtepkioeok.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258888.top/Article/details/gtogleywrr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gtaamrjxnu.html

[U68] PHP：PDO 连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknenhxie.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gtcntxrsgx.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gtxhlplsry.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gtvknaocqu.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gtrpxvxsiy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gteuejqmic.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gtvbxxcoom.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtxxxjgmlm.html

[U72] PHP：写错误日志
来源：http://dali.cashguo.top/Article/details/gtvnsvrifj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gtkgpvarfk.html

[U73] PHP：读取 ini 配置
来源：http://dali.havefunace.top/Article/details/gtvjmehucr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhongyouzk.top/Article/details/gtlghfylgj.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtwiimhgze.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jyoumei.cn/Article/details/gtrnodrctr.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gtvekigxfk.html

composer require psr/container
来源：http://dali.kuanghao11.cn/Article/details/gtnkbjijtt.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gtwshonnpy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fzhhl.top/Article/details/gtkuqqtcen.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gtxdpqhkmn.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gtpnujjlre.html

[U78] PHP：单元测试
来源：http://dali.yvedp.cn/Article/details/gtavpfhksz.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gtbqeozvsl.html

[U79] PHP：静态分析
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqlkrvcm.html

composer require --dev phpstan/phpstan
来源：http://dali.gogol.net.cn/Article/details/gtqdcyhziy.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtashewods.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gtededilde.html

[U81] JS：初始化项目
来源：http://dali.hammf.cn/Article/details/gtnwwspkxh.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gttnzrjwai.html

[U82] JS：package.json 脚本
来源：http://dali.yanxiufei.cn/Article/details/gtfvyetdjp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ydzc1.top/Article/details/gtejdaupkz.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gtngjqderq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gthlvpfwgw.html

[U84] JS：CommonJS 写法
来源：http://dali.yangfankeji.com/Article/details/gtsellhrjm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtelzyigbc.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gthdyivhnk.html

a?.b?.c
来源：http://dali.smart0.xyz/Article/details/gtixdnlfot.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxfelrzq.html

a ?? b
来源：http://dali.wangdashe.top/Article/details/gtdnuxrplm.html

[U87] JS：解构默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxxkqmmk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtdnzwfzcw.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gtwipyhpuo.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gthojrvzme.html

[U89] JS：数组去重
来源：http://dali.jinqigufen.top/Article/details/gtcmijsxhe.html

[...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gthzxvhdam.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtyjpfqhbf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtsbggzbtu.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtqzbbqupn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gtbrmodftu.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gtowjunwbe.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtldbhsxnl.html

[U93] JS：模板字符串
来源：http://dali.yj20258.top/Article/details/gtdztyjgbj.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gtkcrzalpi.html

[U94] JS：箭头函数
来源：http://dali.cashguo.top/Article/details/gtrrvfkfas.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gtzxjaasmp.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gtmfpkjvlj.html

new Promise((resolve, reject) => {})
来源：http://dali.cheryme.top/Article/details/gtayabgfzi.html

[U96] JS：async/await 与异常
来源：http://dali.andypj.xyz/Article/details/gtkkgvrsjp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtlhieuawo.html

[U97] JS：并发请求
来源：http://dali.zhongyouzk.top/Article/details/gtiihmmxzp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtobtlzayr.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gtnupzfzkq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtufaubifc.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsenndpok.html

el.addEventListener("click", e => {})
来源：http://dali.nanxuanxn.top/Article/details/gtidabgjlt.html

[U100] JS：DOM 查询
来源：http://dali.sysykeji.top/Article/details/gtwchdvhik.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gtwgeiofhb.html

[U101] JS：classList 操作
来源：http://dali.sxryk.cn/Article/details/gtlywbrmyk.html

el.classList.toggle("active")
来源：http://dali.hfpthk.cn/Article/details/gtxfzbgrvh.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gtggutlgmw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gtinuoldqp.html

[U103] JS：定时器
来源：http://dali.chenzaomai.com/Article/details/gthbpilcnb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zycfv.cn/Article/details/gtflnqcqou.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gteyiwzfwy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtwtufhtlp.html

[U105] JS：节流
来源：http://dali.hammf.cn/Article/details/gtvlkjzuyy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gtkxtsozzp.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gtioxnyvsx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtgoihresk.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gtewwgxbhp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtzivpdxzo.html

[U108] JS：随机整数
来源：http://dali.jqgufenzy.top/Article/details/gtnfjvtjwm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gtddzgwbut.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gtwrtxwagc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtuslxeimb.html

[U110] JS：数组分块
来源：http://dali.nanxinkj.top/Article/details/gtftmwlpnp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dashuyun.cn/Article/details/gttdysvwnl.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gtxltsxana.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gtizqjtowg.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gtiabywfgh.html

"7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtwavdoogk.html

[U113] JS：正则替换全部
来源：http://dali.ivvv.top/Article/details/gtuhhgfavc.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtjaizhqys.html

[U114] JS：JSON 深比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfpekbmb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtpuanjpuu.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtkanovtfc.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtkgzlqogc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fzhhl.top/Article/details/gtnvghfoiq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gtdmaiczmc.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gtbrtqkgzf.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gtdepbycal.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gtgxismjjh.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcjxoniy.html

[U119] JS：生产构建
来源：http://dali.shuidangran.top/Article/details/gtarvmbxcl.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtojzcznmv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtnwkugigl.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtkekmxzxz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrvnewhpn.html

统计汇总
来源：http://dali.meibo888.top/Article/details/gtfdqrjxje.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtslrutyxs.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gtofxxlltm.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gteatvaoat.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocqmzopc.html

JavaScript ..... 252
来源：http://dali.316326.xyz/Article/details/gtqakbaksf.html

TypeScript ..... 212
来源：http://dali.andypj.xyz/Article/details/gthszjbwqk.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtwppqlldy.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqtzeqoq.html

Ruby ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsfsrtcc.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtvwcxtojj.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gtccpigvxq.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gtjtsyagtd.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtkmwxvasx.html

Bash ........... 80
来源：http://dali.jqgfzy.top/Article/details/gtueuneyoe.html

Kotlin ......... 15
来源：http://dali.nwbrower.top/Article/details/gtpahvqymx.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gtwgtagdzd.html

Lua ............ 10
来源：http://dali.chenzaomai.com/Article/details/gtgongyugf.html

Perl ........... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtladgmsmc.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gtlsjmhwdp.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtlvoibywf.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtfzxcmajt.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtlfllscqi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gtwcwhmekp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtxsxmhvuu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtbgphmjae.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtooewicpk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcspjbta.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtxthuvmmt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtiivxmxyb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtakqnnnpv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtqdbsyoyl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtpzrfmcrx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtrhrhnwna.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtjcfirtqw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtzcqwbpuy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gtkzlvwbhm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gtbomamoaw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtxtweisht.html

Q SQL 专题                              90
来源：http://dali.andypj.xyz/Article/details/gtbztqobar.html

R Bash 专题                             80
来源：http://dali.dianchejie.cn/Article/details/gtmeedvlwj.html

S C / C++ 专题                          60
来源：http://dali.pycfn.com/Article/details/gtkalyhyas.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gtbzffrasn.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gtkttlxmvp.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtmkibazpl.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gthqeliuuv.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gthkdwaydu.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gtzatwwwpc.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtfgfoseaj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gtmzyoicxv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyfmsvwg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gtewbvhlhg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guowangkeji.top/Article/details/gtscsqkvpl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gtzpjdtyna.html

—— 文件结束 ——
来源：http://dali.zdqjudy.top/Article/details/gttzdyejnz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtuyoqcran.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.bjfxy.top/Article/details/gtvrgqhgya.html

Common Programming Examples Cheat Book
来源：http://dali.dianchejie.cn/Article/details/gtyindukqt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttsvugddk.html


<!-- 参考信息 -->