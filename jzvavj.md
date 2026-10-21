代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gtfpoaokiy.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gtbepaagky.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtdfbevnlh.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtewvwqciz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtiyvzcgxf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtguuzdanu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtcuxnvobq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtptdnbuuf.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gtjddcwshw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gtfwasrhqs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gtlyqawubj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtsmestpyz.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gtygplozbn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gtnnerfyxf.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtxgtzojvn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtcknebndm.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gtgucasfud.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtsgvlgvuy.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtdoqvjiyz.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gtmmovbsbr.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtoimitvnp.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gtfxwdpyrw.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtolnewxpp.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gthutcnscu.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gtdggwaxfq.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtpsuwuejm.html

[U10] Py：按值排序字典
来源：http://dali.bjfxy.top/Article/details/gttsvyhuri.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gtslagbowy.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtzfkyvhzr.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtjntgwbfv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gtydsinlas.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gtobidecvh.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtjvblskbe.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbyaovqq.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gtkibryuod.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gtdpzitfoz.html

[U15] Py：高精度计时
来源：http://dali.fengsongda.top/Article/details/gtuxamubbx.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtoidnnhcv.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtknabmbbx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gtncrjksxt.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtchdjgxiz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtbfsyhgxm.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtoldutwpt.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtzdkwyjxe.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gthmomqyfn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gtjhpqednn.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gteorzuhqm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gtyfshasyd.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gtfaftamlb.html

@contextlib.contextmanager
来源：http://dali.dashuyun.cn/Article/details/gtoahpgpkq.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gthujuvndw.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtnmgdonsp.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtjbejsdkc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtreqwlxnj.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gtrdgpewxw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtlgsicgbk.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtlwxgdmmp.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gtqhkcqlgo.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtfhvmnfyl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtmdklpdqk.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gtxtopqmlb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gtpoltqtzh.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gturcnegil.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtunmnfcsh.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtghexzjon.html

@property 与 @x.setter 配合
来源：http://dali.ybcxt.top/Article/details/gtzxderwfc.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gtcasrsxrm.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gtavuvcszh.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gtqnlfmkpf.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gtzsujwsjk.html

[U32] Py：代码格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuijbplmk.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gtaxynvstb.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gtcupmufck.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daxiang520.top/Article/details/gtclsevbrp.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtinxjndus.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtforiqrki.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gtnrwnpbqy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gtkkulqapr.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gtymlshpfh.html

schedule.every(10).minutes.do(job)
来源：http://dali.jyoumei.cn/Article/details/gtcypbdkns.html

[U37] Py：读写 Excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqqldleu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gtptgvnesc.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258.top/Article/details/gtmygveukf.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtkmqdttxu.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gtvgrqdvou.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtxvihzwnn.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtqgfjhgyc.html

print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtvbrpoyag.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gtinhtzchx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gthniculbi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwamucvj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtijmrmsiv.html

[U43] PHP：声明命名空间
来源：http://dali.yangfankeji.com/Article/details/gtbfuqozmu.html

namespace App\Http;
来源：http://dali.316326.xyz/Article/details/gtveqckvhg.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtfktfwdkf.html

declare(strict_types=1);
来源：http://dali.jqgfzy.top/Article/details/gtdxptwlfd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlelhtzub.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gthkywmqmw.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gthsdnbnqk.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gtlfzhchff.html

[U47] PHP：联合类型
来源：http://dali.snrcjt.cn/Article/details/gtorhvhjob.html

int|string $id
来源：http://dali.nwbrower.top/Article/details/gtslibwfmt.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gtgxsatzut.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnxiangtu.top/Article/details/gttrceujbw.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtylwydlpw.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtxnoihnwo.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gtdlycsffk.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbfpxqjyv.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gttlaehums.html

[$a, $b] = $arr;
来源：http://dali.0kj1m.cn/Article/details/gtrxptlnmj.html

[U52] PHP：箭头函数
来源：http://dali.yj202588.top/Article/details/gtudubynfm.html

$double = fn($x) => $x * 2;
来源：http://dali.0kj1m.cn/Article/details/gtkulyotzd.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gthbsmuxrq.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gtmkrdfjxj.html

[U54] PHP：空安全调用
来源：http://dali.ehwqpu.com/Article/details/gtxkvbwdxe.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gtyazfborh.html

[U55] PHP：match 表达式
来源：http://dali.xuanzx.com/Article/details/gtljxnywjd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yvedp.cn/Article/details/gthwslcjcl.html

[U56] PHP：命名参数
来源：http://dali.fengsongda.top/Article/details/gtqoganisy.html

f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtnzkentij.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtkqedphys.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gtunrdpdzo.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gtezsbbfml.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtznfncydj.html

[U59] PHP：自定义排序
来源：http://dali.redwolf501.top/Article/details/gtrhvfkecm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtvxyiunfl.html

[U60] PHP：JSON 编解码
来源：http://dali.pengpengdd.cyou/Article/details/gtptdrfiya.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gttfuhlwhs.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gtuxiiuocm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtqfaauwlr.html

[U62] PHP：日期对象
来源：http://dali.ppjwa.cn/Article/details/gtfcaxhsen.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gtulkvqkmy.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gtktkkavmy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258888.top/Article/details/gtimcixqxj.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gtnwvamlkf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gtrcorelnj.html

[U65] PHP：会话
来源：http://dali.jianghu66.top/Article/details/gtacvpegwd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtvtmujezs.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gtetjprfqi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtcmhymkxe.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtoahejkbu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gtypluoomt.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gtonpndkxs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gtfrckyrny.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gtoxebgpfv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.feifeiyinyue.top/Article/details/gtzpnjvzib.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gtacddytee.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cqqwz.cn/Article/details/gtewxxyujq.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtfuliwtuu.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtqxwlqtjt.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtwqfipmyw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gtqkuukdxu.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtbtjgnwcu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gtknuzmvyp.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtilxkucld.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gttockgtot.html

[U75] PHP：依赖注入
来源：http://dali.jinqigfzy.top/Article/details/gtcfgxvfhx.html

composer require psr/container
来源：http://dali.chenlongwang.top/Article/details/gtkugjsvzb.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gtsrwcalrr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gtezmhfxba.html

[U77] PHP：模板渲染
来源：http://dali.zhiwuduotai.top/Article/details/gttwxbbooi.html

composer require twig/twig
来源：http://dali.zhixingplan.top/Article/details/gtsicyidsp.html

[U78] PHP：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtemwszpun.html

composer require --dev phpunit/phpunit
来源：http://dali.yvedp.cn/Article/details/gtuimpbcqr.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gtnhdrkkqb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhongyouzk.top/Article/details/gtmszktwzf.html

[U80] PHP：代码规范修复
来源：http://dali.zhongyouzk.top/Article/details/gtauarbmma.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtlyhwvsla.html

[U81] JS：初始化项目
来源：http://dali.sweek.top/Article/details/gtzcfxhuma.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gtvrvoivzy.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gtalvwlnke.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxinkj.top/Article/details/gtlanlnvvw.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj202588.top/Article/details/gtmqstadnj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtrbrjvsal.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtnxdvpqbk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gtdfgvzaqn.html

[U85] JS：可选链
来源：http://dali.sxryk.cn/Article/details/gtrysjxaqd.html

a?.b?.c
来源：http://dali.ehwqpu.com/Article/details/gtglipjsdz.html

[U86] JS：空值合并
来源：http://dali.sxryk.cn/Article/details/gtvwkscver.html

a ?? b
来源：http://dali.wangdashe.top/Article/details/gtzilaqfrq.html

[U87] JS：解构默认值
来源：http://dali.aibaodan.cn/Article/details/gtvcesqwxj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gtwdkoranl.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gtbbpqnzyv.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gtzmqhfslz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gtdysruntx.html

[...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtjkhefgbi.html

[U90] JS：数字数组排序
来源：http://dali.havefunace.top/Article/details/gtygnvgywo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtvrkoshri.html

[U91] JS：对象键值遍历
来源：http://dali.nanxinkj.top/Article/details/gttycfbbug.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gtpfbmbiot.html

[U92] JS：深拷贝
来源：http://dali.yueranfly.top/Article/details/gtoqybsken.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmtxknclm.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtasrraxhf.html

`共 ${n} 条`
来源：http://dali.yj20258.top/Article/details/gtikwpbhda.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gticujfbwv.html

const double = x => x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtlortqpdv.html

[U95] JS：Promise 包装
来源：http://dali.cqqwz.cn/Article/details/gtbspoqcte.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbodxjut.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gtlnpogwuq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtvrxjcfhr.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtcfclwjdw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtyawhtxzy.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gttoiexesa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cheryme.top/Article/details/gtyljjssbg.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gtvrlsvdhl.html

el.addEventListener("click", e => {})
来源：http://dali.ehwqpu.com/Article/details/gtntnfpvyc.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gtgcdiachf.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtvofvtgaq.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisuhgsak.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gtmeualnor.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gtuyygbxtw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtjumoyewv.html

[U103] JS：定时器
来源：http://dali.c1oappe.top/Article/details/gtkuhagdyy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xinyue.icu/Article/details/gtwylaispb.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gtbevqadxj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimtpalae.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gtdbmbbmsm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gttrqqhanl.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtlnaznwdb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcklpqfqx.html

[U107] JS：数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtkutfdaqe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtxnwmgxqp.html

[U108] JS：随机整数
来源：http://dali.jqgufenzy.top/Article/details/gtjlikdbvn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gtmxutqeaw.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gtmzluxgfe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtxtmgznfk.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gttleuuhzp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.c1oappe.top/Article/details/gttzexxaeu.html

[U111] JS：对象转 Map
来源：http://dali.yuanzhike.top/Article/details/gttuuciarg.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtsjxpfcaf.html

[U112] JS：字符串补位
来源：http://dali.zhengqikj.top/Article/details/gtzrdxxquj.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtniajptfb.html

[U113] JS：正则替换全部
来源：http://dali.jqgfzy.top/Article/details/gtyxllqptg.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtbgmchzpa.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gtrvexprgf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtbcbmfpfj.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gttevbuqwo.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtecqoxqst.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ppjwa.cn/Article/details/gtusiokiis.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gtmlqpxuww.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gtqrvpryvd.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gtdlkibyhi.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gttizupvpu.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtfhbsacmt.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gtgcuxqoys.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gtxqfpwskx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujhqegzz.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gtcjzocdgs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtstqjaxcm.html

统计汇总
来源：http://dali.jianghu66.top/Article/details/gtqndjpwrs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsvckubvf.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtsbosrrse.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtwttuvlga.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtbfxiljpm.html

JavaScript ..... 252
来源：http://dali.jianghu66.top/Article/details/gtdixceqzi.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtxkxtdcoj.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtpokjsrqm.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gtvfmhwbjg.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gtdskaiaus.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtemmbjido.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrewlsux.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtzmgzqfge.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gtehriksol.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtoxewdbbj.html

Kotlin ......... 15
来源：http://dali.daria6918.cn/Article/details/gtgjnuiowd.html

Swift .......... 15
来源：http://dali.fengsongda.top/Article/details/gtoirpxdab.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gttcbpfode.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gtqogrszsy.html

Scala .......... 10
来源：http://dali.yj202588.top/Article/details/gthrzufisi.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtzolpouyo.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gttnxcaaux.html

按章节统计：
来源：http://dali.hongshengwenyu.top/Article/details/gtkefbcgym.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtikvcbtek.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gthxkxjoeg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtiydduxgc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtctiepuvn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gtmrbeawda.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtsbuovrxe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtllezcvrc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtlrsaxpen.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtnnccfagz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gttqvsnvca.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtqgolemxi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtwyqbxrmx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtgqlogswf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtpdetfoix.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gtnmxjgpyy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtpaqsqjme.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gtnyxsfjdr.html

R Bash 专题                             80
来源：http://dali.jianghu66.top/Article/details/gtwujnxowd.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gtbsegndcb.html

T 其他语言补充                          60
来源：http://dali.zycfv.cn/Article/details/gtztjazfle.html

U 高频实用片段                         120
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncilekkp.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtzjwbrara.html

合计                                  2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtnwpdrhfe.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtmocfecnt.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsenottl.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtikphxomu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtxcwmfkhd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gtgnmgvlbt.html


<!-- 参考信息 -->