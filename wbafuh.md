代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtogaoutrd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtusflnkui.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtlrndhwkz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthuhcuicc.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gtsvirkzln.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gtojlbziov.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtyehfndia.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangdashe.top/Article/details/gtpubtbgxo.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gtwwzxvjcw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvqewcln.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gtppwejtrr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtxbquykvf.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtijgqmela.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbvcmirx.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrqhajga.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtrdcttydg.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtgsewfkbt.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gtnoykqilk.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtklvxdcjc.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gtztnrbtha.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gteedqhnsv.html

max(d, key=d.get)
来源：http://dali.jinqigufen.top/Article/details/gtyjixosdj.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyimpysh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gttvkdhdfk.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtosanrevr.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gtrydmuegz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gtpwsnhhys.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtsfvesppn.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtqmaslbkw.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gtgjzisbgu.html

[U14] Py：分组收集到列表
来源：http://dali.daxiang520.top/Article/details/gtqvdyxxrk.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmmcvfzn.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtqtcslcim.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gtdtnvveop.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtaqeuphib.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gtjmdxxvgd.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gtuzwvgyys.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pycfn.com/Article/details/gtfhtrucwb.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gtyqearxul.html

pat = re.compile(r"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaibcznps.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gteexqraxh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gtiqbqaxkr.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gthytdzggz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gthczllfbr.html

[U21] Py：自定义上下文管理器
来源：http://dali.xylfe.cn/Article/details/gtftcowsut.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtnqdlefjf.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtrpnwtibc.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtiryxndtk.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtbwedesqp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgufenzy.top/Article/details/gtgcczdokt.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtjoasul.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtjmnaxxga.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gtogwkmykc.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gtyunzutmw.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gtwlfwdsad.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtdsahrkfo.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtflmlmkiw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tanke756.top/Article/details/gtatwoluuq.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gtcukhyajq.html

UserId = int
来源：http://dali.chenzaomai.com/Article/details/gtbowxyiiv.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtoifjmefd.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugcxkskj.html

[U30] Py：数据类
来源：http://dali.hywenlv.cn/Article/details/gtpwvkgccw.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gttudpekqv.html

[U31] Py：单测
来源：http://dali.tianlin.xyz/Article/details/gtyjdfdfjl.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtlacofoon.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gtbccnghof.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gteutdqele.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gtrbfzpcfp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtuxstvsqc.html

[U34] Py：判断编码
来源：http://dali.hammf.cn/Article/details/gtqeozpbxp.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gtcirircpd.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gttztpzmkh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nwbrower.top/Article/details/gtqmgnxpcw.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtkrgsukmw.html

schedule.every(10).minutes.do(job)
来源：http://dali.sweek.top/Article/details/gtskoasffh.html

[U37] Py：读写 Excel
来源：http://dali.fzhhl.top/Article/details/gtbzwiujoi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gtznoesyju.html

[U38] Py：获取脚本所在目录
来源：http://dali.cashguo.top/Article/details/gtkpvyrvho.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gtwsrawpwq.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtblrtskdr.html

sys.stdout.isatty()
来源：http://dali.wangdashe.top/Article/details/gtpzuoafad.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gtxtcjxrng.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gthimjqgux.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gttilqtvqb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gtosdsorrh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtqxuvrnjv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtxnimqdan.html

[U43] PHP：声明命名空间
来源：http://dali.chenlongwang.top/Article/details/gttrbizdus.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gtkapdayrz.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gtynypepjl.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gtthihojef.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangdashe.top/Article/details/gtcaxdxpaa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfeyldes.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtpxxpwhaf.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtusfflszf.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gtnkdsizel.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gtthwzfqvg.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gtrwuplaqw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.havefunace.top/Article/details/gtkujvzuqb.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtlvfahxeq.html

public readonly string $name
来源：http://dali.haohaochexian.top/Article/details/gtmrlijgwo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtgyjaryhr.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbgvzkruc.html

[U51] PHP：数组解构
来源：http://dali.hywenlv.cn/Article/details/gtrionmmdf.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gtzvvhglwg.html

[U52] PHP：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtuxaebdzk.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gtildtjydv.html

[U53] PHP：空合并运算符
来源：http://dali.chenlongwang.top/Article/details/gthmmifvtx.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gtoufmbuil.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtljfrghce.html

$obj?->method()
来源：http://dali.jiagoushi.top/Article/details/gtbrpkwtud.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtxkxtrxjt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtglmuxmpp.html

[U56] PHP：命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtlxydfvlj.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtbywqfyqt.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtrjpyrgtx.html

"值: {$a}"
来源：http://dali.dianchejie.cn/Article/details/gttibxwwsn.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gtbxxmxkkk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtxprimcvq.html

[U59] PHP：自定义排序
来源：http://dali.hysaishi.cn/Article/details/gtcccoslzm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjwhvezq.html

[U60] PHP：JSON 编解码
来源：http://dali.hywenlv.cn/Article/details/gtkmcfqkzr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdmvawgk.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtsdzgxfiv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtwflzfotg.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gtvofcrapm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guowangkeji.top/Article/details/gtljtmcegb.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gtaiyrgzrj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktvynctf.html

[U64] PHP：目录遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwcqoypb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gtxkagnsjy.html

[U65] PHP：会话
来源：http://dali.yvedp.cn/Article/details/gtutupzvpu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtdsbwsins.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gtakbkefso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtrrgnwhnb.html

[U67] PHP：处理文件上传
来源：http://dali.sxryk.cn/Article/details/gtyklldiyp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtjpuvlndy.html

[U68] PHP：PDO 连接
来源：http://dali.guowangkeji.top/Article/details/gtjcwcryep.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtoggnvzwo.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gtuibpygpc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gtjipagwnx.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyyraobt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gotoacloud.top/Article/details/gtvdyhzylh.html

[U71] PHP：抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtdgbybfuo.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gtwzqlbkqh.html

[U72] PHP：写错误日志
来源：http://dali.hywenlv.cn/Article/details/gtoeisnyuw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gthlcrcufw.html

[U73] PHP：读取 ini 配置
来源：http://dali.jqgfzy.top/Article/details/gthoouefww.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gtbjsmndde.html

[U74] PHP：读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtyaigbshc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gtiubuyvef.html

[U75] PHP：依赖注入
来源：http://dali.ybcxt.top/Article/details/gtyrqjuonr.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gtrsudabkj.html

[U76] PHP：简单路由
来源：http://dali.dashuyun.cn/Article/details/gtgezmwjyn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.iojbl.cn/Article/details/gtvbuyjukw.html

[U77] PHP：模板渲染
来源：http://dali.ehwqpu.com/Article/details/gtcfiiuzpn.html

composer require twig/twig
来源：http://dali.wangshuangyany.cn/Article/details/gtfzpzusvs.html

[U78] PHP：单元测试
来源：http://dali.aizwys.cn/Article/details/gtslpkouey.html

composer require --dev phpunit/phpunit
来源：http://dali.fzhhl.top/Article/details/gtvugqzgcn.html

[U79] PHP：静态分析
来源：http://dali.xinyue.icu/Article/details/gtnsrnvrrs.html

composer require --dev phpstan/phpstan
来源：http://dali.sysykeji.top/Article/details/gtxmjathfq.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gtafdhjijv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gtittgmkaj.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gtylmaegpu.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtxircovbv.html

[U82] JS：package.json 脚本
来源：http://dali.jiagoushi.top/Article/details/gtxptzbdjs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gtxnuhucdp.html

[U83] JS：ES Module 导入导出
来源：http://dali.hysaishi.cn/Article/details/gtqresmedb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtgpxiiwks.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtealpamtu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gtsrbedtgm.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtfsqylmvq.html

a?.b?.c
来源：http://dali.yj20258.top/Article/details/gtbisqawrz.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gtudeigvab.html

a ?? b
来源：http://dali.fengsongda.top/Article/details/gtxghnuzxk.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtbvdgscft.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigufen.top/Article/details/gtnwzqpilf.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweultoha.html

{ ...a, ...b }
来源：http://dali.hnxiangtu.top/Article/details/gtepvssxof.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gtshqwdjuj.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtssbkkmsd.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtynjtgevm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtjwdwsukz.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gttvwrywys.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gtmcohfmuo.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gtvebquxbf.html

structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtmccmbran.html

[U93] JS：模板字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsetzbbv.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gtobfebdfi.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtrrxmyprw.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtpdcsskdj.html

[U95] JS：Promise 包装
来源：http://dali.shangyingyoupin.top/Article/details/gttchibhfd.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtucgqvpxv.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtcbhbapsi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtzdovusbo.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtjehbed.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtbjzfagar.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gtpbfsaxdp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ivvv.top/Article/details/gtjomrtail.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gtwokciujb.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqveqjaie.html

[U100] JS：DOM 查询
来源：http://dali.ivvv.top/Article/details/gtdlwrfawk.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxugtqaaz.html

[U101] JS：classList 操作
来源：http://dali.wangdashe.top/Article/details/gtnzvsniiz.html

el.classList.toggle("active")
来源：http://dali.aizwys.cn/Article/details/gtzymyugcu.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gttlrqaqxv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtjhpmweiy.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gtlqaarlnc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtedgwbntb.html

[U104] JS：防抖
来源：http://dali.yangfankeji.com/Article/details/gtaccozefq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtrrcjisak.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gtxqqyzaht.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiaajavg.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtkevorbsx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gtluotpgai.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtmqjhzygz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtfhpwzswy.html

[U108] JS：随机整数
来源：http://dali.gzhubu.top/Article/details/gtgdssswdv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtfemkdjoo.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gtgpvikxuq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtpkevvlyy.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtdzfqmvco.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gtxbqkzgpi.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtryuypclt.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtsvbnhtft.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gtfgmbyskp.html

"7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gttooxgdeb.html

[U113] JS：正则替换全部
来源：http://dali.jlsjyb.cn/Article/details/gtuxmkqfsd.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxrjwamhu.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gtteftznkk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtzlnafqzr.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtvibsuiso.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtkccscskm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtuvlizhmx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuxming.cn/Article/details/gtdyphcmlu.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gtnsqdoehf.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gtvygdvvfu.html

[U118] JS：开发服务器
来源：http://dali.chenjidiqi.icu/Article/details/gtbecalckf.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gtdlmautqm.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtnmkklzma.html

npx vite build
来源：http://dali.iojbl.cn/Article/details/gtbxunqurr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gteyrvmywk.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuqlirjp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjqpalmmy.html

统计汇总
来源：http://dali.fengsongda.top/Article/details/gtnzwnuogl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjkmpjzfb.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gtmdmmwzri.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtapqhliga.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaozhzze.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gtagmzxueh.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gtwfvadgln.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtguxvbfnw.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkykvvxmd.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gtiffcaqms.html

C# ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsrgjbjc.html

C .............. 30
来源：http://dali.ehwqpu.com/Article/details/gteyqugmzk.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gtxjssaqef.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtkhpodvpd.html

Bash ........... 80
来源：http://dali.jlsjyb.cn/Article/details/gtxtclfvtz.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gtcmnexuvi.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gtmardtkvn.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtjqyghcsy.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gtiilbpezi.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtlfytipts.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtifupwwnx.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtipnpnvdu.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gttsjrlpbf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gtbzsipgnn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gttzmphmok.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtlvtmujxw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtspocbfsx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtemvyosjk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gtqcmdfepg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtgutasnci.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtbieckhiy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtfuavhnem.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gththmikti.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtblnhamgw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtpjngwppu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtbrraxttc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtntnjmsda.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gtwxlapboo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtyuyvdrae.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gtkyemydwx.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gtniwpfzoc.html

S C / C++ 专题                          60
来源：http://dali.shuidangran.top/Article/details/gtthtlgkek.html

T 其他语言补充                          60
来源：http://dali.shzxlz.cn/Article/details/gttavmdkxk.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmrunhsy.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtqhknquxw.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtbhztgzgw.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtcdpnlajd.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtiyxrmlxb.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtlvktbgik.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuanzhike.top/Article/details/gtvgxiymxo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sufxvd.cn/Article/details/gtopmddawq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtpybnogpn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtaqmqemkt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gtffgznobl.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikpasatd.html


<!-- 参考信息 -->