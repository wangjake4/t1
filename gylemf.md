代发 wailian999

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2dteiaepp.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jppuctbc.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2htscyhki.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gt2oaajunhj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2izrejtbv.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gt2jangjuve.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gt2kbmgramg.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gt2modnqavp.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2hyqvuwoe.html

[T57] Scala：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2osvibzzj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.birdmap.top/Article/details/gt2ucidhkuj.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gt2cgkkdfci.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gt2bfarjdtj.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gt2kgznigjg.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2xlistcsh.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gt2onbglruw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gt2hzafizgn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2auipviim.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gt2pzyhatta.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsbyxdyv.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2lnscagvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gt2ejohdjic.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gt2rbyccuhp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gt2ziwkdnnf.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzbvojzf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gt2hfrxsgnb.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gt2hiivkgra.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gt2utwrxwtf.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gt2mkiskrhh.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2xrliqogh.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2trscalkg.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gt2mzeohlnl.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2amembmlv.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gt2dejitfns.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2buisrwvc.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gt2mqtpzyey.html

[U09] Py：字典取最大值的键
来源：http://dali.gzhubu.top/Article/details/gt2razykcuh.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gt2rwmnmeos.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gt2vvyciywf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gt2bxnvibjq.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2nroyxaas.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ijsztjfj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gt2ytghukpk.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gt2ytidpblm.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gt2ggvzfaty.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gt2khrmceub.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gt2wlwkhdds.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gt2tzlbmeum.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gt2lfzvwmln.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gt2gadlrndo.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gt2mgjprivt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gt2yvhemqeb.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gt2fispbhft.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gt2vprbapsi.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucrjbglj.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2cxdbmcav.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gt2rzwkauda.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gt2eekebpjj.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gt2lbhmoyvc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gt2mmatvoxk.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuiafxea.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2ivwaisyz.html

[U22] Py：矩阵转置
来源：http://dali.zycfv.cn/Article/details/gt2gozwetbv.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gt2eotzhetg.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gt2bxseqrof.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hammf.cn/Article/details/gt2rmkpalam.html

[U24] Py：路径操作
来源：http://dali.shzxlz.cn/Article/details/gt2pzunaxma.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2ukaexvvr.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gt2xgzdiqnb.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gt2jxpvhzyc.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gt2kyhzyuld.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gt2uxdtqqsf.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gt2rcbaszfj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkjmsxgm.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gt2oyrwzjqd.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gt2stgyviir.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gt2ycbsssbx.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gt2pnermwxo.html

[U30] Py：数据类
来源：http://dali.xylfe.cn/Article/details/gt2mkaebvhq.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gt2duemcbwe.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gt2ebaihofc.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gt2dangbdek.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gt2pjdmfksk.html

ruff format . && ruff check --fix .
来源：http://dali.hammf.cn/Article/details/gt2qwgzrbkj.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gt2amvavnuk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gt2fpqbudvf.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gt2maibhftg.html

chardet.detect(raw)
来源：http://dali.yj202588.top/Article/details/gt2dpaqxiow.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gt2ygphpfdh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gt2cpvkrace.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2sbhempwe.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gt2xvrtwomx.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gt2tfwezavv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gt2mcdzawvr.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2ensdmfjg.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gt2xjlryrav.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigufen.top/Article/details/gt2uppmpdrh.html

sys.stdout.isatty()
来源：http://dali.sweek.top/Article/details/gt2bdcfsluq.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gt2kujuoyyk.html

print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2shyyturo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gt2avdutubm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gt2vqjwtymn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gt2hkhjdvex.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldtfrcqm.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gt2ntmrwhom.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gt2vmibpmfv.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gt2qcaamzmv.html

declare(strict_types=1);
来源：http://dali.zdqjudy.top/Article/details/gt2awscffdu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gt2eypfvqtd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jommhtyq.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gt2hqgcijhx.html

?string $name = null
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evurgxmy.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2uiwkrtle.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gt2lxziwqvp.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gt2zfqivaur.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gt2rjycjcun.html

[U49] PHP：只读属性
来源：http://dali.zdqjudy.top/Article/details/gt2loybbaos.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhgizpxm.html

[U50] PHP：构造器属性提升
来源：http://dali.0kj1m.cn/Article/details/gt2npdtkkce.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gt2ehxqpuex.html

[U51] PHP：数组解构
来源：http://dali.yongpay.top/Article/details/gt2nfdsmwbm.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gt2wicgohfh.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2eihnjmqz.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2dccvpdvr.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gt2nqonjume.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gt2dartqavj.html

[U54] PHP：空安全调用
来源：http://dali.sufxvd.cn/Article/details/gt2osplmeng.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gt2xemuwiwz.html

[U55] PHP：match 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2nlpbplon.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2fzldezwt.html

[U56] PHP：命名参数
来源：http://dali.yonumen.top/Article/details/gt2iyzxacal.html

f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2ggjyjbyg.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2nfhegqbs.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gt2feiocmdk.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gt2iavzhgvk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2udmydhcr.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gt2wrsmjnzd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2hztfjxon.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gt2qlujafja.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gt2tjnlguxi.html

[U61] PHP：正则
来源：http://dali.nwbrower.top/Article/details/gt2rubmtcco.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2nptumvpf.html

[U62] PHP：日期对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fadkguxt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fzhhl.top/Article/details/gt2vlgukdkj.html

[U63] PHP：文件读写
来源：http://dali.havefunace.top/Article/details/gt2zwtuqcwd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.bjfxy.top/Article/details/gt2lzibtoxr.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gt2amjstkfs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flfvbbkg.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbbluszp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2sfvwxfia.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpmfnapd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hemrcqal.html

[U67] PHP：处理文件上传
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqvouant.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.vqdsnc.cn/Article/details/gt2kyalgtxt.html

[U68] PHP：PDO 连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sstnealw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gt2zteqmciv.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcmygpzn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gt2kxjdyiwh.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gt2mqpijhhs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqqvnfca.html

[U71] PHP：抛出异常
来源：http://dali.yj202588.top/Article/details/gt2wawgpnux.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2hclrducw.html

[U72] PHP：写错误日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxazshsz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ppjwa.cn/Article/details/gt2pciduvwe.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gt2nzncnupm.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gt2wimegump.html

[U74] PHP：读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2uuomrshz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cashguo.top/Article/details/gt2vdujkjaa.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gt2foafrrmu.html

composer require psr/container
来源：http://dali.snrcjt.cn/Article/details/gt2ietxyijv.html

[U76] PHP：简单路由
来源：http://dali.tanke756.top/Article/details/gt2zsqjqhnk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zdqjudy.top/Article/details/gt2zytzcnkw.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gt2mgzlqqwu.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gt2naqjsili.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gt2cjgovdfk.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gt2iarcabag.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gt2owpcphep.html

composer require --dev phpstan/phpstan
来源：http://dali.iojbl.cn/Article/details/gt2swsaxgus.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gt2ikbqgznr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.svipenyu.cn/Article/details/gt2tndghqdn.html

[U81] JS：初始化项目
来源：http://dali.daria6918.cn/Article/details/gt2gbqbcsrj.html

npm init -y;  npm i express
来源：http://dali.9152youxi.cn/Article/details/gt2kxvltasp.html

[U82] JS：package.json 脚本
来源：http://dali.hywenlv.cn/Article/details/gt2tgsyjpov.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yvedp.cn/Article/details/gt2rcetdimu.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gt2khgxhvam.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2zakbatpo.html

[U84] JS：CommonJS 写法
来源：http://dali.shzxlz.cn/Article/details/gt2eqsanhyx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnxiangtu.top/Article/details/gt2btbhhrgh.html

[U85] JS：可选链
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smqvlrxn.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gt2cnccjgry.html

[U86] JS：空值合并
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmkaqqsy.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gt2shzprirp.html

[U87] JS：解构默认值
来源：http://dali.iojbl.cn/Article/details/gt2xvpystih.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jycemlff.html

[U88] JS：对象展开合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juedkhok.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gt2nkyjceka.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2iofreijx.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2hfcpryfa.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gt2jodjhdku.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2qsrsqcmz.html

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngxgsght.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jyoumei.cn/Article/details/gt2jwkynmqe.html

[U92] JS：深拷贝
来源：http://dali.andypj.xyz/Article/details/gt2llkpahic.html

structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2psxgiwtw.html

[U93] JS：模板字符串
来源：http://dali.guannengcc.top/Article/details/gt2isvzsrcg.html

`共 ${n} 条`
来源：http://dali.ybcxt.top/Article/details/gt2nvebqvlo.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gt2znqndtdp.html

const double = x => x * 2;
来源：http://dali.fengsongda.top/Article/details/gt2kyzjdqzh.html

[U95] JS：Promise 包装
来源：http://dali.jyoumei.cn/Article/details/gt2audtjuci.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gt2qsphtend.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gt2sosuizml.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2gzkdwkmp.html

[U97] JS：并发请求
来源：http://dali.jqgfzy.top/Article/details/gt2mwrbawke.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjfctsqx.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2jdnebdmx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gt2qpqaddbf.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gt2woqzcztv.html

el.addEventListener("click", e => {})
来源：http://dali.cqqwz.cn/Article/details/gt2fdzvpmjx.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjpuxccx.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gt2zvalvbdq.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwnsunmf.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gt2rlbfnofz.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2krnqdnhh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnqzz.top/Article/details/gt2nyrqtwvv.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gt2tzkpjbau.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gt2rihdoukl.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gt2rfqhluri.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2stymvdfu.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gt2rmrbucna.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2dairflgj.html

[U106] JS：日期格式化
来源：http://dali.yongpay.top/Article/details/gt2pinpqwug.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaaoptld.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfbshmeb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaehofss.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gt2yjquypov.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gt2yxhsoqqj.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gt2tvxadsgv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gt2rlmgojsg.html

[U110] JS：数组分块
来源：http://dali.gzhubu.top/Article/details/gt2fxmmpfyk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenlongwang.top/Article/details/gt2pvpfufuj.html

[U111] JS：对象转 Map
来源：http://dali.mhx1999.top/Article/details/gt2phwbwecg.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gt2rbmqvvfw.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gt2dbwgbchb.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2lzolcrtm.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gt2ewjzqquz.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2vyhrgeyc.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gt2mnucszin.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytybracx.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gt2gvencwvz.html

crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2yfhsnxca.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ppjwa.cn/Article/details/gt2meopfdqr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gt2xjixzvyj.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gt2nnbwnyfx.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gt2yyniwfct.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gt2miefpwyk.html

npm i -D vite;  npx vite
来源：http://dali.0kj1m.cn/Article/details/gt2mnryyhsa.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gt2sinrooiq.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gt2gwxftjzg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gt2ojctdneq.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsqmkdhv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2doqwykyr.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gt2tbtzetdz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ryhwneec.html

按语言统计（条）：
来源：http://dali.shuidangran.top/Article/details/gt2yyroazzg.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gt2jzdnfibc.html

PHP ............ 252
来源：http://dali.nwbrower.top/Article/details/gt2cbndxgkn.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gt2zbqcmdqg.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gt2wrcwqqjf.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gt2dgggyhok.html

Go ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2spxgawcj.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2bbuhulqr.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2zsqrzawh.html

C .............. 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kydcajgi.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gt2ewzpypkz.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gt2yavxuelt.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gt2vprlxzvx.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2ljbghovf.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gt2qnustfij.html

Lua ............ 10
来源：http://dali.yongpay.top/Article/details/gt2ytvljask.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gt2fehyffgh.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gt2ihmskfte.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2vrrwwamh.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gt2cqzbntfi.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gt2wkbujnrv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gt2fvtnpksu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2fnhmnnge.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2awzlveis.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2hicghlju.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpyjeixb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gt2akrqlmxi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhtfrhze.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gt2siffmdpq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2mxjizmkp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gt2czkllxgk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2dkdvtauf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2iwspbeku.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2kvsfxzzl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gt2xitjhvyc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gt2obnzphrv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2sulpqwag.html


<!-- 参考信息 -->