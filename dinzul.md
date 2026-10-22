代发 wailian999

val a = 1;  var b = 2
来源：http://dali.yonumen.top/Article/details/gtgibdetpn.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtdbdgpgwk.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtjakmdwhk.html

[T54] Scala：集合映射
来源：http://dali.nanxinkj.top/Article/details/gthizmtddu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtgcjukapb.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtgrzhpbar.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtwqropcod.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtecgkuhwi.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtfpldglbr.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gthmvmuabh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yangfankeji.com/Article/details/gtmoplyipf.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtmzhbuvab.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtqrwhiqlz.html

[T59] Scala：循环
来源：http://dali.nanxinkj.top/Article/details/gtaajjymhz.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtpszcvjro.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gtpkfmuvvv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtahmiyzkf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtoezmqzrp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtvnupmkzc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebktcrax.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtghmwgbez.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gtdhdealbi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtgpvnkwpn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtbjdzvgel.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtsweprsro.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtkghbqeho.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtlrjwtdww.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gttnchggtb.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gttubdvkud.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtpgfiiyfu.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gterurbepd.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gtblextxyu.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gtykvpknbg.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtupcecvjg.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtcqsvdxrl.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gtuflnmetj.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gtmthsrylr.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzqfxahh.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtubjusuqd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtxgshykph.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gtlmbtngra.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtkvfzfvoi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtedqgimqj.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gtpqqgmjqa.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gthdyciqyw.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gthpjqfnqd.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtlodfptke.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtmnnobnig.html

[U15] Py：高精度计时
来源：http://dali.wangdashe.top/Article/details/gthyemiyjy.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gttlhwckof.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gtazvlqegz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gogol.net.cn/Article/details/gtvvaohikc.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gtujmgnmom.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gtylqjmkqi.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtxhjzofsg.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtuvkeacbm.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gtzgbgmlln.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtrxiybyaw.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtdossdfde.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gtmztcxkhj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gtzxvcctmd.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtizgsemqm.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gtvdcjploi.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtzwqmirst.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtjzhbszft.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtobkohfnc.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtmcdibtvn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtvmkdbntc.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gthyjwxhnt.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gttgmelmts.html

[U26] Py：并发下载
来源：http://dali.yj202588.top/Article/details/gtqtziovqu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gtexfaszyg.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gtenpipvbv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjwgenok.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gtelquboop.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gtkdzeplcg.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gtbqxsjdre.html

@property 与 @x.setter 配合
来源：http://dali.shzxlz.cn/Article/details/gtgrrigkny.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gtefxjqfja.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzsimezv.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtksjmbfhr.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gtqcosvrml.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuthgvglv.html

ruff format . && ruff check --fix .
来源：http://dali.hnxiangtu.top/Article/details/gtxsocywph.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gtezoujeay.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gtsdszsvxp.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gtlpdwhoea.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gtsccdizcw.html

[U35] Py：发送邮件
来源：http://dali.cashguo.top/Article/details/gtgunxwvht.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nwbrower.top/Article/details/gtpadwtglk.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gtqkxzvgnw.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtycspdo.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtyjcbrwyk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yvedp.cn/Article/details/gtpljajbgo.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulcugzdd.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gtxpilyabq.html

[U39] Py：判断是否在交互环境
来源：http://dali.fengsongda.top/Article/details/gtrqlqckrm.html

sys.stdout.isatty()
来源：http://dali.xylfe.cn/Article/details/gtyrgxcbyo.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gtgessuumx.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtebideiwd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gtbqotpfsl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.birdmap.top/Article/details/gtyqytlvim.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gtbdlrgklo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhixingplan.top/Article/details/gteffdpshe.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtmhimzuso.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gtyrccqdrd.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtwfvuawwy.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gtgazjyffu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gtfnuiibfg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtpwbdzyxh.html

[U46] PHP：可空类型
来源：http://dali.kuanghao11.cn/Article/details/gtjgtqatuq.html

?string $name = null
来源：http://dali.shangyingyoupin.top/Article/details/gtpukgmkum.html

[U47] PHP：联合类型
来源：http://dali.ehwqpu.com/Article/details/gttcdvlkpc.html

int|string $id
来源：http://dali.zhiwuduotai.top/Article/details/gtcfretlqp.html

[U48] PHP：纯枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqxurem.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gtorrpwuje.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtgzgnsddr.html

public readonly string $name
来源：http://dali.hywenlv.cn/Article/details/gtrvxycrhj.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gtossvvcjn.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gtvcqjrpil.html

[U51] PHP：数组解构
来源：http://dali.c1oappe.top/Article/details/gtglaribbn.html

[$a, $b] = $arr;
来源：http://dali.cashguo.top/Article/details/gtlvqnjbad.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtsigadhab.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gtfsuljnqy.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gtcexbgmti.html

$v = $a ?? $b ?? "default";
来源：http://dali.fzhhl.top/Article/details/gtwpimuwkd.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtowsrocmd.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gtdrnxjdek.html

[U55] PHP：match 表达式
来源：http://dali.yj20258.top/Article/details/gtwxvskejx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gtzuypxwqd.html

[U56] PHP：命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtxmlbcbwn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtleryqduc.html

[U57] PHP：字符串插值
来源：http://dali.pycfn.com/Article/details/gtepozvvhm.html

"值: {$a}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbclfxvwv.html

[U58] PHP：数组三件套
来源：http://dali.cashguo.top/Article/details/gtmnhcggdp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtqpcxlqfr.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gtotnhbcae.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtcsvvrwum.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gtmtxynqbs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gtbezgixnc.html

[U61] PHP：正则
来源：http://dali.pengpengdd.cyou/Article/details/gtuefgcgon.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtpzbnyynh.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtwgoasaqg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.birdmap.top/Article/details/gtnwvqiiff.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gtzuptveim.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gtnqzpzuoy.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gtlvulebml.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gtvdwastls.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gtntmstjbp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtizgaenot.html

[U66] PHP：设置 Cookie
来源：http://dali.xziqi.cn/Article/details/gtsnulefaw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shuidangran.top/Article/details/gtpvhvoqzh.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtzrsusbhl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yueranfly.top/Article/details/gtrgrqujgc.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtjvpmgjfd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuyvmvfm.html

[U69] PHP：PDO 预处理
来源：http://dali.yangfankeji.com/Article/details/gtpbnesohj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gthctgeylj.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gtrrvzugfo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gtxgazfpxe.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gtkejmcrrm.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gthhvyzrub.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtcibxpeqo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtrkayycmb.html

[U73] PHP：读取 ini 配置
来源：http://dali.snrcjt.cn/Article/details/gtwebvaili.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gtsjfiehng.html

[U74] PHP：读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtvjsixjjy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkaoqclt.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtgwtnquvz.html

composer require psr/container
来源：http://dali.yonumen.top/Article/details/gtoesbeplw.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfneshtmr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hfpthk.cn/Article/details/gtfahpovsz.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtleanthbd.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtweowgblx.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtacxgnliz.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gtbxfrxumd.html

[U79] PHP：静态分析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuscthbmi.html

composer require --dev phpstan/phpstan
来源：http://dali.c1oappe.top/Article/details/gtxkslpogp.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gtojervqoq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gtjquakhmz.html

[U81] JS：初始化项目
来源：http://dali.cheryme.top/Article/details/gtmtboeumz.html

npm init -y;  npm i express
来源：http://dali.redwolf501.top/Article/details/gtfnulkbza.html

[U82] JS：package.json 脚本
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmmxsjon.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlezcyavd.html

[U83] JS：ES Module 导入导出
来源：http://dali.pengpengdd.cyou/Article/details/gtzawbktmf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtshndjnya.html

[U84] JS：CommonJS 写法
来源：http://dali.ydzc1.top/Article/details/gtuzhnicul.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjpmxzrs.html

[U85] JS：可选链
来源：http://dali.xinyue.icu/Article/details/gtuoeumyan.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gtznszhdrs.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gtduvfpgix.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtebgqywmx.html

[U87] JS：解构默认值
来源：http://dali.smart0.xyz/Article/details/gtkbcfjogv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.pengpengdd.cyou/Article/details/gtriigsjbh.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gtegflhomm.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gtfppsnylj.html

[U89] JS：数组去重
来源：http://dali.yj20258888.top/Article/details/gtltwglxfp.html

[...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtecltxhkp.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gtmuewjuey.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtqtiigfug.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gtkczaqncu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigfzy.top/Article/details/gtnupzdtcw.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtotstadwy.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gthunysjfs.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gtjaffosbd.html

`共 ${n} 条`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinmwyviw.html

[U94] JS：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvhdkwkhw.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gtpahttftg.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gtzzrmdwtw.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gtvzybgfbn.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gtywlxvmyz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtniyaqdgw.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gttmwwfzbk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtbaxjalsf.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gtwrjfihnj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gtcftrlgzq.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtzbpevxvl.html

el.addEventListener("click", e => {})
来源：http://dali.meibo888.top/Article/details/gtnvclpqkc.html

[U100] JS：DOM 查询
来源：http://dali.xuetiantiany.cn/Article/details/gtcgkmseiu.html

document.querySelector(".item")
来源：http://dali.aibaodan.cn/Article/details/gtmvkitmfn.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gtmibblqaz.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gttkcqkgge.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gthxndadis.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gtwmdewqxb.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gttnlqluvj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtscdordil.html

[U104] JS：防抖
来源：http://dali.pycfn.com/Article/details/gtsjkeighw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtsgtzitqi.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gterxsoccg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtcuxaxzkm.html

[U106] JS：日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnmlyodi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbqilaht.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gtsyiituco.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gtbxbtptvj.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gttnyxrjww.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gtekquepwd.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gtevibuzfm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtyozirscl.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtfqxvnuym.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gthxbkiays.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gtannzlmcp.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwgowqkd.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gtwvxzatdj.html

"7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gthwdjiqcj.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gtqtmdevcl.html

s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtfccszwim.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gtvgxzlzav.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtmgwslyyf.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtlgbsrwqd.html

crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtirbuepfr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtwhitsffu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrevgfbea.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtfrrhicme.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gterdupjaf.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gtnbfztbor.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtcrczkfzs.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gterhpcutm.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gtbnoxgsjv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gtpumlsshm.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gtpqksgmms.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtfpzerpei.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gtzijrvtyo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtowpcpynw.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gtgvvcfnby.html

Python ......... 252
来源：http://dali.dianchejie.cn/Article/details/gtymqviwyb.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtrjuacvwj.html

JavaScript ..... 252
来源：http://dali.ivvv.top/Article/details/gtozgifdot.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtlqcehywa.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtqvxvqkli.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtcjsooryz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gtjblakpgb.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gttodxmduc.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gtoxgicchw.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gtvcjtlepl.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtwrjrlbod.html

Bash ........... 80
来源：http://dali.ivvv.top/Article/details/gtsxvmzitd.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gtqosmxztx.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtxdxbxzif.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gttmgxslkk.html

Perl ........... 10
来源：http://dali.quarkkingdee.top/Article/details/gtronuaebm.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gtnzrykwmy.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtsimkmmcf.html

合计 ........... 2106 条
来源：http://dali.fzhhl.top/Article/details/gtaladhbub.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtvbembdbw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gtnamopnlz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtunxvvkaa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtbkhrsukj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtqredaobw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gtmehrvujd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtzqfeuqsu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtvpafxutv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrvyliio.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtdykvarbj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtxtrddeeq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtpajooukv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtmulhnnpr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtxzrkdpkx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtfhgtdcxv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgfzy.top/Article/details/gtoijbmadd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtlwclvqkl.html


<!-- 参考信息 -->