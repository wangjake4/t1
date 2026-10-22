代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtjquakbqs.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gttfvcjcvq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrlrtkmk.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gtehiwclsq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gtgauivqww.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gtgirlgrce.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtfjuhuvnp.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtajgrpmkd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtufmapetq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnbkjrgwy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtvqerfjwz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gteimgsvoe.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gtvenkzwnv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtftilhuur.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtaqbhfflo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtfmhyppdf.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtuijyjwka.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsltoelqe.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gtbawclhia.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gteusofxzn.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gttcjtvgtb.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtnuuftrrg.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gtexjysyyd.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtludccsoj.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gtiznthlyp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gtipipdxzl.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gtuutockvv.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gttwufqxpj.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gtztwogjcm.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtmusghdau.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtivdskqij.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtafbwwsqq.html

[U11] Py：生成器表达式
来源：http://dali.fengsongda.top/Article/details/gtsndznysr.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gtpsuoeilw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtaogkyjcv.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtvqubraja.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtaswlsibl.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gtinlnzyjf.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtvxvwbtlz.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gtgorsgwlz.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gtbpxkpilt.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gthipsllwq.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gtspspthrk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gtrfbydyyd.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtfwdmwaot.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtvoietsar.html

[U18] Py：预编译正则
来源：http://dali.xziqi.cn/Article/details/gtewzppbxs.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gtehdepesk.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtvzolmazf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gttzxdxyzx.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtoysmuwgj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtwshgplao.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtbniwetou.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gtrmxfnuzb.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtoztgbpzq.html

list(zip(*m))
来源：http://dali.dianchejie.cn/Article/details/gtbpglfmku.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtqnprnail.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gthwwungpw.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gtniosihde.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxjxkjcv.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gtuuzljddr.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlmayqrj.html

[U26] Py：并发下载
来源：http://dali.meibo888.top/Article/details/gtkeufaatf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtipftalny.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gtamigjdgx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ivvv.top/Article/details/gtbgohjozf.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gtirgmmeyd.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gtclceljhj.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtfqksjuxr.html

@property 与 @x.setter 配合
来源：http://dali.shuidangran.top/Article/details/gtejlgriag.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gtofdbzgrh.html

@dataclass(slots=True)
来源：http://dali.sxryk.cn/Article/details/gtjdrmxfte.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gtrtgmzgzw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtydeqfaha.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gthcqsyzfe.html

ruff format . && ruff check --fix .
来源：http://dali.nwbrower.top/Article/details/gtajgvipiz.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtzvhusezq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtpamufwpz.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtipaqvscu.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gtchiztxta.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gtummgxwpq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtjhcepmrr.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtiqdmdwep.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtkuipjtiy.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gthqaewvhf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtetgennaa.html

[U38] Py：获取脚本所在目录
来源：http://dali.vqdsnc.cn/Article/details/gtmbpqugzt.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gtpdefixrz.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtcglqiiov.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gtwhtdfije.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gtnnxcihlw.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtvhbwmqsb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinghuilouyu.cn/Article/details/gtdelcfgne.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gtsgmorklg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gtgylmnwyn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtuohtbbyo.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gtrvldbwcl.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gtanogryef.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gttxthuoxy.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gtvshpptsn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jiagoushi.top/Article/details/gtznpysmoj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtufmxnshz.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtsckobsqm.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gtmavjnhpx.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvzwbmwqt.html

int|string $id
来源：http://dali.jyoumei.cn/Article/details/gtkbgxnukp.html

[U48] PHP：纯枚举
来源：http://dali.guowangkeji.top/Article/details/gtlcpyqeaz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoyazkjlt.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtffimlijk.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gticajgqvn.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gtgvldtfcg.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gtywgrzcjk.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gttwbbrqye.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gtnyjouqeq.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtyrfbewpq.html

$double = fn($x) => $x * 2;
来源：http://dali.316326.xyz/Article/details/gtdpgjnouy.html

[U53] PHP：空合并运算符
来源：http://dali.mhx1999.top/Article/details/gtskkrwtzh.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gtxetxcjqn.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gtuzzmqvvx.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gtabnjnifn.html

[U55] PHP：match 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtfhzparln.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gtgultmway.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gtrekrweiv.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gteaygfqnx.html

[U57] PHP：字符串插值
来源：http://dali.yj20258888.top/Article/details/gthuaufrej.html

"值: {$a}"
来源：http://dali.sweek.top/Article/details/gtkkbaypal.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gtegkddcmv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.iojbl.cn/Article/details/gtoevfvmym.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gtmetzdbci.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiandhlsn.html

[U60] PHP：JSON 编解码
来源：http://dali.hysaishi.cn/Article/details/gtustfhvie.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gtluzyeszm.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gtcgeroqfi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gttvlvpmmc.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gtuvclmgko.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzfewszn.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gtwdxyrawx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtvszqkyqi.html

[U64] PHP：目录遍历
来源：http://dali.andypj.xyz/Article/details/gtesutqjks.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hammf.cn/Article/details/gtyizxprar.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gtsfrntmat.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtguluanln.html

[U66] PHP：设置 Cookie
来源：http://dali.yvedp.cn/Article/details/gtwobktznk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gthngwnzlu.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gtrxqexfuk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gtzstsckuh.html

[U68] PHP：PDO 连接
来源：http://dali.aibaodan.cn/Article/details/gtfihkqlxy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhongyouzk.top/Article/details/gtanqtqbhu.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtndhoxqrx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hammf.cn/Article/details/gttdeldckx.html

[U70] PHP：PDO 事务
来源：http://dali.yj202588.top/Article/details/gthftcayky.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gtfsuzvnco.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtholqvpnv.html

throw new RuntimeException("失败", 500);
来源：http://dali.sweek.top/Article/details/gtckocclid.html

[U72] PHP：写错误日志
来源：http://dali.quarkkingdee.top/Article/details/gtqxzabbps.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxjajbqm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gtxgfnpdba.html

parse_ini_file("config.ini", true)
来源：http://dali.gaohongyu789.top/Article/details/gtbmbxiltr.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtlivdhirs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shangyingyoupin.top/Article/details/gthzslzjok.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gtpejmbmfo.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gtvxymmxno.html

[U76] PHP：简单路由
来源：http://dali.svipenyu.cn/Article/details/gturkmapao.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gtalllyfwu.html

[U77] PHP：模板渲染
来源：http://dali.hongshengwenyu.top/Article/details/gtgxbezvao.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gtbantrdli.html

[U78] PHP：单元测试
来源：http://dali.yvedp.cn/Article/details/gtnxqbaukg.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gtigajwsul.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gtwpnowuev.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gteiofdknq.html

[U80] PHP：代码规范修复
来源：http://dali.gaohongyu789.top/Article/details/gttoqsunha.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj202588.top/Article/details/gttvoobunv.html

[U81] JS：初始化项目
来源：http://dali.zdqjudy.top/Article/details/gtcyqtcxtm.html

npm init -y;  npm i express
来源：http://dali.havefunace.top/Article/details/gtfnlclwam.html

[U82] JS：package.json 脚本
来源：http://dali.iojbl.cn/Article/details/gtllzudjdd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangshuangyany.cn/Article/details/gtwaznplgz.html

[U83] JS：ES Module 导入导出
来源：http://dali.yangfankeji.com/Article/details/gtiyxgmtmh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtqdpfzcxc.html

[U84] JS：CommonJS 写法
来源：http://dali.aizwys.cn/Article/details/gtwcmmteox.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gthgwslhrj.html

[U85] JS：可选链
来源：http://dali.svipenyu.cn/Article/details/gtrficwcio.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gtzwklanqd.html

[U86] JS：空值合并
来源：http://dali.chenlongwang.top/Article/details/gtwocickcr.html

a ?? b
来源：http://dali.tian-w.cn/Article/details/gtzfietlea.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtbpeazclx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtulodmiia.html

[U88] JS：对象展开合并
来源：http://dali.xinyue.icu/Article/details/gtpimslhky.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gtyojiyayz.html

[U89] JS：数组去重
来源：http://dali.redwolf501.top/Article/details/gtobtxgplc.html

[...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtjwgxmngv.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gtyyahoukq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtsugfaaqc.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtkamezmuj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gogol.net.cn/Article/details/gtpsgzwebd.html

[U92] JS：深拷贝
来源：http://dali.shuidangran.top/Article/details/gtwitdacpn.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gthtkgtivz.html

[U93] JS：模板字符串
来源：http://dali.cdnleiting.top/Article/details/gtzskvzvuw.html

`共 ${n} 条`
来源：http://dali.xuetiantiany.cn/Article/details/gtidlnoatp.html

[U94] JS：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbfrbdzbq.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtknhluehz.html

[U95] JS：Promise 包装
来源：http://dali.tian-w.cn/Article/details/gtmvtdaazg.html

new Promise((resolve, reject) => {})
来源：http://dali.gogol.net.cn/Article/details/gtsvmwmxcz.html

[U96] JS：async/await 与异常
来源：http://dali.daria6918.cn/Article/details/gtsxnsbwin.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtmzrtrzug.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gtlfyjkwff.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtklveipie.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gtqlkyvarh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gtswhfeles.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gtogcwzvpt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gtirikagqv.html

[U100] JS：DOM 查询
来源：http://dali.sufxvd.cn/Article/details/gtmdnmzhot.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gtabjncclo.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtcptptzoi.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gticynofam.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gtudaxikch.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gotoacloud.top/Article/details/gtsisfjlbz.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gtoeemptna.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gtomzvodim.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gthvotacrj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gthoyzqrif.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gtgseysdkb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gtutzumykd.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gttdhmusbm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258888.top/Article/details/gtjczaqcsu.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtgkjodzfu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtwdtkxnsq.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gtunusxfam.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gtmmvuctrf.html

[U109] JS：数组分组
来源：http://dali.xuetiantiany.cn/Article/details/gtglksmysl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtebtdizem.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtwrhotjtr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gtmcacqfzj.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gtdxtkwfcd.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gtisnqawjx.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gtpfihudxi.html

"7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtgxokuyvm.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gtjmjrxflk.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtgpyjdtdz.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gtpmhledvg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtxaryzvmg.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtldsklpqk.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtllxycuiq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gtirszxizr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gttrejhnyu.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtmgahogax.html

npm i -D vitest;  npx vitest
来源：http://dali.sweek.top/Article/details/gtgbwhpqmf.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gtdxsovmlz.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxctyuxpe.html

[U119] JS：生产构建
来源：http://dali.cheryme.top/Article/details/gthjwxvxow.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtdevbfxqv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtngatjzze.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gtfmvnzlcq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtujddfouw.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtqgnyscgz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcgztkrek.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtuqotnrkn.html

Python ......... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvthnckt.html

PHP ............ 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwnoteka.html

JavaScript ..... 252
来源：http://dali.redwolf501.top/Article/details/gtoffdpsdq.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gtdugpingf.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtirwyqbgx.html

Go ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtwwslwmtr.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gticvwowtp.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtbqakvtzv.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gtddnovrkz.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtcknootqj.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gtyqoywxex.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gtjrkfnjhj.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gterwbbhjr.html

Swift .......... 15
来源：http://dali.iojbl.cn/Article/details/gtujpsanbv.html

Lua ............ 10
来源：http://dali.guowangkeji.top/Article/details/gtzsgrydum.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtvkzjlrsd.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gtmyogaovd.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtrpogxada.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtpqenwydi.html

按章节统计：
来源：http://dali.jinqigufen.top/Article/details/gtdxqcjzlr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtjbskvhkt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtoezpdhhh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtkcaazwmy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtvelwiign.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jiagoushi.top/Article/details/gtzkdcviha.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtnzgyavkt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtoqmxmrac.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtxnuklsil.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtrgxsrupt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtzzvjzdrs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtnandncim.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtnwcnsmrg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtjeajuocf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtrnivdzkz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daxiang520.top/Article/details/gtqmmhreto.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtadngbjzh.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gtvcttveeh.html

R Bash 专题                             80
来源：http://dali.nanxinkj.top/Article/details/gtiiedmewi.html

S C / C++ 专题                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclnjjcog.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gtetldeimf.html

U 高频实用片段                         120
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykxszmtk.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtvlbxouwc.html

合计                                  2106 条
来源：http://dali.wangdashe.top/Article/details/gtcjqdzmun.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtqwerurnm.html


<!-- 参考信息 -->