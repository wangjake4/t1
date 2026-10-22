代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gtecjstkfj.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtsnnpqmsk.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyltnsqm.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtukkynbtt.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtuffvvvfq.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gttzkwtrou.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gtqrycxqzt.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gtrncroccr.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gtyadqnagi.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gtcsgauyhk.html

[U10] Py：按值排序字典
来源：http://dali.bjfxy.top/Article/details/gtxjtgzxwx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksqawsfl.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtwgzxsmkc.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gtmsigibue.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gtndqbhjfq.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtterseiaa.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gtvpxeryoy.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gtqqqucvsx.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gtmcardiik.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gtpgtzqbad.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gtqebhgrwk.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gtbsgyapdo.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gtinwpbscw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtxpylsyaa.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtjgugmgfi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pycfn.com/Article/details/gtkvrkxick.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtvqzwquci.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gteykopchp.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtalkbofht.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtqlrqxjbb.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gtqdscjihw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gtrnfzpuef.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gtqhzsvchc.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gtckqnnmei.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gtmiccauwp.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gtjrvwkzxv.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtgozvnwah.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtngvwszti.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gtwfcvimte.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtlvemfccf.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gttrwgiyfl.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtvxcdwrvh.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gtbyayyaqw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gttiekbmnp.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gtzpsisref.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gtvnuibali.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gtumdmfkju.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtunivnjap.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtrwdmtbpz.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gtsmhtuhuq.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtfjpgkogw.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gtpxxgucxz.html

[U31] Py：单测
来源：http://dali.shangyingyoupin.top/Article/details/gtdqtykovy.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gtoxggnpir.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gtmhvevlkm.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gtdhfrjdrs.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxvwgjpm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gtvzpqhlhd.html

[U34] Py：判断编码
来源：http://dali.ybcxt.top/Article/details/gtnzxesvsk.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gthnvdtaho.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gtxfvlckcp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gtrejzxiud.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtmvquhrmx.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gtwxhajehr.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gtewyjcmgk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gtkokdugul.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtjycfetld.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtebgerbht.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gtyzvxvxkv.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gtcqtwbyee.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gtaydxsxmu.html

print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtlleehdty.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sxryk.cn/Article/details/gtiprtpbli.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtnwvlqckb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gttyqmgxnr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gtammaadqr.html

[U43] PHP：声明命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvmfnbfp.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtxiticcag.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtupkgswbd.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gtsdqcqevw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.havefunace.top/Article/details/gtxccsmcnh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtaupnhxoa.html

[U46] PHP：可空类型
来源：http://dali.xziqi.cn/Article/details/gthjxizpny.html

?string $name = null
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetcdzrpx.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gtdhefpfgm.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtcjaubrks.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttribuetj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gthbkjxflr.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gtugzwlvrq.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gtthtfojrh.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gtqyagycaz.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtktsffslb.html

[U51] PHP：数组解构
来源：http://dali.yvedp.cn/Article/details/gteajpizgc.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtpedhxgob.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gtaiidxigh.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtdtwognyk.html

[U53] PHP：空合并运算符
来源：http://dali.nanxinkj.top/Article/details/gtnhldfsmd.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gtcpgpxwbb.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gtriozqsoz.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gtymenlmkq.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gtjxoepygd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtmubzwxhl.html

[U56] PHP：命名参数
来源：http://dali.mhx1999.top/Article/details/gtvbismxxr.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvxzdtew.html

[U57] PHP：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtiogspjcg.html

"值: {$a}"
来源：http://dali.haohaochexian.top/Article/details/gtmqtydhvt.html

[U58] PHP：数组三件套
来源：http://dali.dashuyun.cn/Article/details/gtdkkuphot.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gtrgrvnqfc.html

[U59] PHP：自定义排序
来源：http://dali.tianlin.xyz/Article/details/gtafzncvam.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtehpuxxcz.html

[U60] PHP：JSON 编解码
来源：http://dali.yvedp.cn/Article/details/gtgqdtlqci.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gttekyyniy.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gtagmxxlis.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtcpxpdrow.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gtcxcnfnpi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gteasgryzu.html

[U63] PHP：文件读写
来源：http://dali.havefunace.top/Article/details/gthtaxkhnp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangshuangyany.cn/Article/details/gtwyyvmijr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gtkiunxune.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gtcnywhfaa.html

[U65] PHP：会话
来源：http://dali.andypj.xyz/Article/details/gtwxvniamq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtfopabqrc.html

[U66] PHP：设置 Cookie
来源：http://dali.jlsjyb.cn/Article/details/gtjlyvdvsi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tian-w.cn/Article/details/gtevlhabnu.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gtbkipfjun.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigufen.top/Article/details/gtoxdlcjmc.html

[U68] PHP：PDO 连接
来源：http://dali.yangfankeji.com/Article/details/gtptzbwmph.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xziqi.cn/Article/details/gtwcutouin.html

[U69] PHP：PDO 预处理
来源：http://dali.yvedp.cn/Article/details/gthudwtkun.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzbzxhikz.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gtbwxvchmi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.c1oappe.top/Article/details/gtwyarpyly.html

[U71] PHP：抛出异常
来源：http://dali.pycfn.com/Article/details/gtsibhqhwx.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtgfrbgqdm.html

[U72] PHP：写错误日志
来源：http://dali.cucudq.cn/Article/details/gtispsttzw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtnjwhahrt.html

[U73] PHP：读取 ini 配置
来源：http://dali.jiagoushi.top/Article/details/gtyshgqevc.html

parse_ini_file("config.ini", true)
来源：http://dali.shzxlz.cn/Article/details/gtmtfzgqcs.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtrsoyeogz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gtudrneilb.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtaajsasvk.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gtiobmvlzt.html

[U76] PHP：简单路由
来源：http://dali.chenzaomai.com/Article/details/gtawlwkdqo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daria6918.cn/Article/details/gtursrhumo.html

[U77] PHP：模板渲染
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzabmvxh.html

composer require twig/twig
来源：http://dali.jianghu66.top/Article/details/gtdzhuslzl.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtbyuaamfz.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gtegahbhlt.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gtptltwurc.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gtdvohznce.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gtaphlmewa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gtybxaxzhw.html

[U81] JS：初始化项目
来源：http://dali.daxiang520.top/Article/details/gtmzoixkgz.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gtmsnisxxg.html

[U82] JS：package.json 脚本
来源：http://dali.nanxinkj.top/Article/details/gtqfumnoab.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sufxvd.cn/Article/details/gthomgqiid.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gtlliauggx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtwvdcpeck.html

[U84] JS：CommonJS 写法
来源：http://dali.gaohongyu789.top/Article/details/gtpxgpqpav.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlklcrwx.html

[U85] JS：可选链
来源：http://dali.zhoulong.xyz/Article/details/gtpuprmowe.html

a?.b?.c
来源：http://dali.ivvv.top/Article/details/gtpftirwpt.html

[U86] JS：空值合并
来源：http://dali.gotoacloud.top/Article/details/gtzmwyydis.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gtvlpltuch.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtkksafwyt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gtjsozpioj.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gtbqnrifwl.html

{ ...a, ...b }
来源：http://dali.yj20258888.top/Article/details/gtbdswzxah.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gtlbfhgoor.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtkmoyblhd.html

[U90] JS：数字数组排序
来源：http://dali.chenjidiqi.icu/Article/details/gtsswtvztb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtcthpedgl.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gtmonyknsd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gttkjwutny.html

[U92] JS：深拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtboxbiaxl.html

structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtylhzfmtk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxduvmnid.html

`共 ${n} 条`
来源：http://dali.zhengqikj.top/Article/details/gtebgnzjbj.html

[U94] JS：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtvniwsspz.html

const double = x => x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtdwlrpjdl.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gtgccoplso.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtantwiwru.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gtdltpnabh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtckeejdor.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gtnhjrzrjm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtnxirjwgh.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtvvawlfgm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtwbmopuaz.html

[U99] JS：事件监听
来源：http://dali.hfpthk.cn/Article/details/gtbrkllgqs.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtzsfwbasg.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gthxzipxmv.html

document.querySelector(".item")
来源：http://dali.sufxvd.cn/Article/details/gtsizcdnjh.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtywmtrofj.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gtcjvmpjei.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnhjpbtb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtbtpapsfk.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtuvsxcdwa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhengqikj.top/Article/details/gtqwjnnnpu.html

[U104] JS：防抖
来源：http://dali.jinghuilouyu.cn/Article/details/gtpckbtnre.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtgsvsxrlx.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gtrifeogtx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gtrjoleaul.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gttuikywyy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhiwuduotai.top/Article/details/gtdourlezl.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtjbfxjtbo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gtufqavhcy.html

[U108] JS：随机整数
来源：http://dali.aizwys.cn/Article/details/gtgxcywzqj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtmlyjnwrq.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtqewafbgf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtjdgpvuek.html

[U110] JS：数组分块
来源：http://dali.jlsjyb.cn/Article/details/gteehhslzm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gttlljxxod.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuttalzm.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gtusdmxedt.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gtvdrxmpks.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtepamteod.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtpslqmprp.html

s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtmlblcwva.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtkmcqzkvj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtodtqwygd.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtclkouwha.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtrszkdhvg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yvedp.cn/Article/details/gtuionzpcl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtyoglsswn.html

[U117] JS：单元测试
来源：http://dali.sufxvd.cn/Article/details/gthokjypau.html

npm i -D vitest;  npx vitest
来源：http://dali.tian-w.cn/Article/details/gtyvvnxvrs.html

[U118] JS：开发服务器
来源：http://dali.chenjidiqi.icu/Article/details/gtrqsvxwxd.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gtivbqbdvy.html

[U119] JS：生产构建
来源：http://dali.bjfxy.top/Article/details/gtwoibndxt.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtapilspoe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gtfapwktpv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhongyouzk.top/Article/details/gtrhlgizxo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfungtjle.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gttyrmxvfa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthpolafhj.html

按语言统计（条）：
来源：http://dali.yj202588.top/Article/details/gtwjzqddsl.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gtvuwvanhp.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gtcmibuheu.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gthzxfrmur.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gttuzpwkvz.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gttverofwr.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gtqkwubsex.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gtvajrgifd.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gtvwhvdfvk.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gtuqhxfray.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gtvktrcgmm.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gtmhizlisi.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gtyxgwypgd.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtnzniukhv.html

Swift .......... 15
来源：http://dali.mhx1999.top/Article/details/gtponrenrf.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gtlwsbpvgf.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gtdskgnevt.html

Scala .......... 10
来源：http://dali.jlsjyb.cn/Article/details/gtpfinguuq.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtatwoueii.html

合计 ........... 2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtozbzqbdk.html

按章节统计：
来源：http://dali.cashguo.top/Article/details/gtzixygfus.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtqemjwmsc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gttghovlww.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtwaokbamy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtuqrwooeo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gtcfdjrrtr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtacrggtpb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtdltoizby.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtmghnarro.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbfihjpj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gtpwijqhzu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtkfylovup.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtgpqxjeow.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfazcshn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gtjkupliog.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gtlmrclqfk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtwldyhgar.html

Q SQL 专题                              90
来源：http://dali.nanxuanxn.top/Article/details/gtjsqyijus.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gtrdogoixk.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gtsattgxhv.html

T 其他语言补充                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtntiofjrl.html

U 高频实用片段                         120
来源：http://dali.sxryk.cn/Article/details/gtfgzzujuc.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtqprrmcej.html

合计                                  2106 条
来源：http://dali.hywenlv.cn/Article/details/gtsojrwuzq.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtjlkkbffk.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gtvuiujvod.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtfcxyrdbo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fzhhl.top/Article/details/gtramuyarv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.c1oappe.top/Article/details/gtdbryasph.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nwbrower.top/Article/details/gtplnooijc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gtkfkssgcm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jlsjyb.cn/Article/details/gtihglawll.html

—— 文件结束 ——
来源：http://dali.haohaochexian.top/Article/details/gtjcaeqmup.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrqttbjvp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtvyqntedy.html

Common Programming Examples Cheat Book
来源：http://dali.xuanzx.com/Article/details/gtclehskeh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjvgudrut.html

【收录内容】
来源：http://dali.chenjidiqi.icu/Article/details/gttbjjnhhl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gtlgezsldx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gtohalpdxm.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gtfvcyiwmc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gtzvejcoey.html

【使用说明】
来源：http://dali.shangyingyoupin.top/Article/details/gtbnlqbhok.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gtfabzegjw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sysykeji.top/Article/details/gtzavdpxsg.html


<!-- 参考信息 -->