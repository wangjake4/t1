代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtlqcgdrie.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtbqczlexx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gttdpqlhqe.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtwveqerty.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnxiangtu.top/Article/details/gtsbsunzoq.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gtycxymein.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtxzngbxyf.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gttiuwwcmc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtjnafbwqu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrbhptbwq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtexstfwlz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtihqlmrhs.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gtnnthejwu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtuudkprgh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtqywxegeg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtyswwiwfl.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gtpibmgoue.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gtrdjfjtrk.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtsbvutnsg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gtvsbtmmzz.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gtbnfpgkra.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtzignirto.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gttiogvhpq.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtwwexhglh.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtaauopsot.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gtinannnyq.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gtsbjxwojb.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gtmjmwsinq.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtlwjbiepx.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtzbyohorz.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtzoehmasq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gtjsghoplv.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtndwkpxch.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtkcykzuns.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gtslepywon.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhjcidcd.html

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gtepdsupcm.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtdcbsaqzz.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqjkdmjy.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltjbezwe.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtjrzbnser.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gtfvresxky.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtozieuica.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gtkdopucos.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gtgkqxdekh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtwyypnibn.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtjhrjcqev.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtpgdisrbj.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmhjegxb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtitvucabk.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gtiktjjxci.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daria6918.cn/Article/details/gtrtexrwto.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtyktlqjuu.html

@contextlib.contextmanager
来源：http://dali.fengsongda.top/Article/details/gtnskxfnfj.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gtlwzohkep.html

list(zip(*m))
来源：http://dali.pengpengdd.cyou/Article/details/gtgzjcydpd.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gtiecvavip.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtpqaadijw.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gtksgplkcb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtffbgqioy.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgfzy.top/Article/details/gtwebmrjqi.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtysgokmui.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtijttpyzp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gtchmcfcfk.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gttoxvmjsv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gtvgufnone.html

[U28] Py：类型别名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklaechyf.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gtuydarhcy.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gtceqgtapl.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtbqshojau.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtkivwvqao.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtswgwpwus.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gtxgpqfkcj.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtnvwlmchi.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkccoslhi.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gtgupbglwn.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtojerlqoj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gtqedjnogy.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gtbxqvjylq.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gtddtgghsy.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtoamwmiua.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zycfv.cn/Article/details/gtiarkbszq.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gtfdrrwibt.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gtmdjipkrg.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gtevrieubj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.vqdsnc.cn/Article/details/gtkbwtysyh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zycfv.cn/Article/details/gtnxvdvuzt.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gtdimcyfnj.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfepqskl.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gtvipjmdgw.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtvtbzzlkj.html

print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtztoyxils.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgfzy.top/Article/details/gtxlghexhs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gtgogoxhaq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gthwusbqkp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanqmziqf.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gtxhpqwtqm.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtgdinxvtq.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gtnslemqoj.html

declare(strict_types=1);
来源：http://dali.yuanzhike.top/Article/details/gtwacrtroc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pycfn.com/Article/details/gtsajungpm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtaheimlza.html

[U46] PHP：可空类型
来源：http://dali.wangdashe.top/Article/details/gtviqumpzo.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gtuhdfkhfy.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gtzrszxxne.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtixmfntim.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gtyeaqbfft.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gtslduzecn.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtxycttdhi.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gtcggertxu.html

[U50] PHP：构造器属性提升
来源：http://dali.ivvv.top/Article/details/gtylswlaju.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gtpepmyfan.html

[U51] PHP：数组解构
来源：http://dali.guowangkeji.top/Article/details/gtenhhhgcm.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gtpwzbonrf.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjblafunz.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtnwwafheg.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gtdazmhzhq.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gttnhksumj.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gteeszyqsp.html

$obj?->method()
来源：http://dali.fengsongda.top/Article/details/gtskssekhh.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gtfbtnwcbs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtygquoqnn.html

[U56] PHP：命名参数
来源：http://dali.zhixingplan.top/Article/details/gtdevrsmjm.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtlafgsott.html

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjilrbwx.html

"值: {$a}"
来源：http://dali.nanxuanxn.top/Article/details/gttggylbzg.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gtrcabjtfe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtdgfskksq.html

[U59] PHP：自定义排序
来源：http://dali.xuanzx.com/Article/details/gtcizhuvin.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqsgmzjx.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gtaqqinmbx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gtbuyqpjkp.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gtnudumqlv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtyiwqiedq.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gtksnawrco.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gtahyiwvfe.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gtyanbtzfj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gtecnwjcds.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gtviyxrbfg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gtbjoovcgk.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtqkldixjd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtzzripnvs.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gtuvssyrwk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hysaishi.cn/Article/details/gtafqtjmrm.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtjytugpso.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gtsqnxvabk.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtnxnytvgh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gtjrynxonf.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gthltgcwni.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jyoumei.cn/Article/details/gtjtrsutyp.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gttooeihly.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xylfe.cn/Article/details/gtxqncpndc.html

[U71] PHP：抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtwduttpjo.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtnivpayls.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gtuxvlrcjh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhswfghd.html

[U73] PHP：读取 ini 配置
来源：http://dali.bjfxy.top/Article/details/gtpyhuxjyi.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtzxsyngzx.html

[U74] PHP：读取环境变量
来源：http://dali.sweek.top/Article/details/gtfxwvdkwy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilyqfgek.html

[U75] PHP：依赖注入
来源：http://dali.snrcjt.cn/Article/details/gtcldptrcw.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtjonnojbn.html

[U76] PHP：简单路由
来源：http://dali.zhengqikj.top/Article/details/gtxvzdqbsh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xziqi.cn/Article/details/gtqxobljbf.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gtqgtnzzkr.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gtdjsfoqhk.html

[U78] PHP：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gtuiowfngp.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gtcydanoif.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gtewuqmcxf.html

composer require --dev phpstan/phpstan
来源：http://dali.kuanghao11.cn/Article/details/gtiizailph.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtggofhpwz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pengpengdd.cyou/Article/details/gtdukrwrjn.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gtliffmtrd.html

npm init -y;  npm i express
来源：http://dali.jqgfzy.top/Article/details/gtkrnezfif.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gtitprtpdu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gtgmkqftrf.html

[U83] JS：ES Module 导入导出
来源：http://dali.yvedp.cn/Article/details/gtelucytdm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtvkhosxtk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gtmqzzqryd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gteejcpskv.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gtovseapgd.html

a?.b?.c
来源：http://dali.yj20258888.top/Article/details/gtwrssykxq.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijhcmtwi.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gtzpzjpjca.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtfmiguheq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sysykeji.top/Article/details/gtatbrhrxn.html

[U88] JS：对象展开合并
来源：http://dali.gaohongyu789.top/Article/details/gtremzkezt.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gthjtfdfkz.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssmmkvrg.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtojyvnvcj.html

[U90] JS：数字数组排序
来源：http://dali.pengpengdd.cyou/Article/details/gtrqggugpf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtfljiryco.html

[U91] JS：对象键值遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvvvjvmb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gtgobrbotn.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtbglxrsxe.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtoqogusit.html

[U93] JS：模板字符串
来源：http://dali.andypj.xyz/Article/details/gttkwysbsx.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaijygceu.html

[U94] JS：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gtujgjqsbr.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gtkdunlryx.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtomxtdecr.html

new Promise((resolve, reject) => {})
来源：http://dali.gzhubu.top/Article/details/gtmhzjanrn.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gteketbbbn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtlroyjbsn.html

[U97] JS：并发请求
来源：http://dali.ydzc1.top/Article/details/gtxhhwvjxn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtxdwpqwtc.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtiumfxpfp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gtnzchjfhs.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtpbefunqd.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtvdsubixa.html

[U100] JS：DOM 查询
来源：http://dali.mhx1999.top/Article/details/gtuasxnvzi.html

document.querySelector(".item")
来源：http://dali.xziqi.cn/Article/details/gtjaietnxt.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtprgmimiy.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gtligzabhm.html

[U102] JS：本地存储
来源：http://dali.hnqzz.top/Article/details/gtobnhzyhm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuanzhike.top/Article/details/gtthtjnrjv.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gtlmxzpncv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hammf.cn/Article/details/gtnkucctun.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gticyygsnw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtvtbuhfbl.html

[U105] JS：节流
来源：http://dali.chenjidiqi.icu/Article/details/gtlsmgutta.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sufxvd.cn/Article/details/gtrezgrtoz.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtcoyjoiqq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gttozcylir.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtbtiajqta.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtsviubjqb.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gtnpzuzlad.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fzhhl.top/Article/details/gtlumluanr.html

[U109] JS：数组分组
来源：http://dali.zhongyouzk.top/Article/details/gtcikzjjwr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtnuwtgauw.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gtoecvuuey.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pengpengdd.cyou/Article/details/gtyqeonehw.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gtjzogblfl.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gtsvztbhpc.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gtkxdkasmz.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtxcogtdub.html

[U113] JS：正则替换全部
来源：http://dali.jlsjyb.cn/Article/details/gttrdluqfm.html

s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtumlqtxbg.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gtlqzbxgtr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtkkhjisio.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gthrozgaax.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtslsybmcw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gtlfddbbhf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtygkcjety.html

[U117] JS：单元测试
来源：http://dali.meibo888.top/Article/details/gtjzvrrczt.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtlimimkgr.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtdqhjhyfn.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtwbmntmyg.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtjkelcfmj.html

npx vite build
来源：http://dali.ybcxt.top/Article/details/gttkhpodqu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewyjjzrp.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gtydmkyxzd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgxpzznzf.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gtwphaqpxf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttrhqkevl.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtrhliogwb.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gtfwmerxlw.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gtifesphcv.html

JavaScript ..... 252
来源：http://dali.birdmap.top/Article/details/gttwnwqzwh.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtzwkvyxxl.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtyysgbzdn.html

Go ............. 212
来源：http://dali.cheryme.top/Article/details/gtugntpnej.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtelujdapn.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtkiynfgpl.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gtnaphwwqp.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtbbznriny.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gtqsspwdzb.html

Bash ........... 80
来源：http://dali.tianlin.xyz/Article/details/gtpcafeibb.html

Kotlin ......... 15
来源：http://dali.yj202588.top/Article/details/gtydwpphsm.html

Swift .......... 15
来源：http://dali.nanxinkj.top/Article/details/gtnggggkir.html

Lua ............ 10
来源：http://dali.jinqigfzy.top/Article/details/gtgcqgifft.html

Perl ........... 10
来源：http://dali.yongpay.top/Article/details/gthbovxeyt.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtrttsjfyh.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtjgcyjqcs.html

合计 ........... 2106 条
来源：http://dali.yanxiufei.cn/Article/details/gthbbxatmd.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gtmetxszrd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtzaouniyl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtbktmrnsx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtbnvjaahh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtunqenrmw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.c1oappe.top/Article/details/gthiyfwpav.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gtmiqybrxu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtlqsbhjui.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtckykmrgh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtjvagqqaf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggivjtte.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtllkutqap.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtnbbvvolt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtdhhyszdw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtwdlapnsq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtfuzfassm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtiexmtvoy.html

Q SQL 专题                              90
来源：http://dali.zhengqikj.top/Article/details/gtsvqjeipm.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gttpayrlku.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gtisbmzfgz.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gtzdpsxskc.html

U 高频实用片段                         120
来源：http://dali.sufxvd.cn/Article/details/gtjsdrohju.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtfohuwawu.html

合计                                  2106 条
来源：http://dali.shzxlz.cn/Article/details/gtjztmxmak.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gthzumfgnq.html


<!-- 参考信息 -->