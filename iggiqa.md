代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtnbogtsoc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtirkxakns.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gtehcibqpp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtmmuhfxrb.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtndhjzzcy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gtepydkdas.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtqdlbjysh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gtvouizrct.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gtwyaqhahu.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzcajtla.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtmjlcqiyr.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtwoilcw.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtmsbaqcim.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gtiummbksg.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtcugegycg.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtubgyamjz.html

[U09] Py：字典取最大值的键
来源：http://dali.cdnleiting.top/Article/details/gtwdwfmqbq.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gtavhnlblm.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtprrditlu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtpvevmeqx.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtysymrrlg.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gtpviuella.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gtjomvpvhn.html

Counter(arr).most_common(3)
来源：http://dali.guannengcc.top/Article/details/gtlihrvvpm.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gttglrqzvj.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gtsdcpzxrs.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gttacrxnld.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtisfldvsi.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnnsjuhi.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gtvxbpvauj.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gtbbrrbpob.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtijvmsani.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gtasqxmzdx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtsbcixygt.html

[U18] Py：预编译正则
来源：http://dali.shangyingyoupin.top/Article/details/gtloobxnro.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtoolrwwgz.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gticxesnoo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gtehusxguh.html

[U20] Py：缓存函数结果
来源：http://dali.bjfxy.top/Article/details/gtixnstdbg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtpndopvyz.html

[U21] Py：自定义上下文管理器
来源：http://dali.yonumen.top/Article/details/gtjrzskhoo.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtjjdtjpxp.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gtdmmfgvid.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gtnhpyspwf.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtsrwlofve.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yanxiufei.cn/Article/details/gtctistmsl.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gtxahfovab.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjkzckox.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gtcobuvgbn.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gtslgzryqy.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gtnhxiywuc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtosbqcsaz.html

[U27] Py：异步 HTTP
来源：http://dali.sxryk.cn/Article/details/gtculxjvwa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gtryrwddbg.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gtmjhpwkgw.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtufvrgfqh.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtlzwfzgpj.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtexxjjmnx.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gtpqugzdou.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gttrecyslc.html

[U31] Py：单测
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuxncrfi.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtmxiqskzq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gtewmnadzn.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gtbemgnjtl.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtcpgfatfm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gttwhfgchx.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtgvbptsuq.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gtkfnqcaxz.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtkfbaiuqf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gtpdpswsad.html

[U36] Py：定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtwqmacdgz.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchoyrfls.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtpgsjkhks.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxchvatvn.html

[U38] Py：获取脚本所在目录
来源：http://dali.iojbl.cn/Article/details/gtpxnqkfll.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gtjgwsyyin.html

[U39] Py：判断是否在交互环境
来源：http://dali.haohaochexian.top/Article/details/gttkjiclwb.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gtblmoivxk.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtmfwwqclf.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtvechqvbw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmjwboqr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gtmvcljxjb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtgnoupjnu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gtjyovtoko.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gtgposjxqd.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gtjzcfelej.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gtszfwlqvt.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtuhzciywo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gtunavwabp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtlnwofxww.html

[U46] PHP：可空类型
来源：http://dali.fzhhl.top/Article/details/gtvsfdcnlp.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gtbhwykqrf.html

[U47] PHP：联合类型
来源：http://dali.0kj1m.cn/Article/details/gtputyxyiv.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtbsjverln.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gtiokddbbp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.haohaochexian.top/Article/details/gtklyhketz.html

[U49] PHP：只读属性
来源：http://dali.quarkkingdee.top/Article/details/gtfvmnutws.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gtjylheuoo.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkykdhdwt.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gtdnhbxfln.html

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gtnndaoadt.html

[$a, $b] = $arr;
来源：http://dali.bjfxy.top/Article/details/gtzotsjevc.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtjapmzgem.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtwvzbxize.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gtcwluvqdv.html

$v = $a ?? $b ?? "default";
来源：http://dali.dianchejie.cn/Article/details/gtxtpsvazt.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gtlublwonv.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtixpoyjhy.html

[U55] PHP：match 表达式
来源：http://dali.snrcjt.cn/Article/details/gtwxyvxosb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxmlsgjk.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gttmnkiqln.html

f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlutdhli.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtmuzdlach.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtdtgmdboe.html

[U58] PHP：数组三件套
来源：http://dali.yuxming.cn/Article/details/gtgbnyznwd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fengsongda.top/Article/details/gtqaoyjxzf.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gtbtpjeaqe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtsxmfsxnz.html

[U60] PHP：JSON 编解码
来源：http://dali.yvedp.cn/Article/details/gttotfyrub.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtrmeqqhes.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gtzlcatmux.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtduyenqua.html

[U62] PHP：日期对象
来源：http://dali.yj20258.top/Article/details/gtytrsoonl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gtoxzttnza.html

[U63] PHP：文件读写
来源：http://dali.yuxming.cn/Article/details/gtuvcdrrzi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gtcyxadmsr.html

[U64] PHP：目录遍历
来源：http://dali.ehwqpu.com/Article/details/gtsqatjaji.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtjrladpdb.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdpxoiit.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtotkfzkad.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gtpggnetam.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtgnajehfl.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gtjeavlfot.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gtxxooylov.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtdorfaozu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gtqmpiezge.html

[U69] PHP：PDO 预处理
来源：http://dali.sweek.top/Article/details/gtpsqoopgc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gtqknijhmo.html

[U70] PHP：PDO 事务
来源：http://dali.jianghu66.top/Article/details/gtzmrgjbcy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hammf.cn/Article/details/gtyalfisfc.html

[U71] PHP：抛出异常
来源：http://dali.c1oappe.top/Article/details/gtvhstqlst.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtvsvsybqr.html

[U72] PHP：写错误日志
来源：http://dali.chenjidiqi.icu/Article/details/gtafyjcmlc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gtnmyntdzp.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gtuzqujjaz.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gtholdvfsl.html

[U74] PHP：读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtiknyoswb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ehwqpu.com/Article/details/gtwyvxmxwm.html

[U75] PHP：依赖注入
来源：http://dali.hywenlv.cn/Article/details/gthikzlxpr.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gtjeergmqp.html

[U76] PHP：简单路由
来源：http://dali.shzxlz.cn/Article/details/gtctwmaetv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxinkj.top/Article/details/gtbmtfajcb.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gtnhyjnxfu.html

composer require twig/twig
来源：http://dali.hammf.cn/Article/details/gtbmsyyiiu.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gtqypcpxvy.html

composer require --dev phpunit/phpunit
来源：http://dali.yuxming.cn/Article/details/gtbhrrtlgo.html

[U79] PHP：静态分析
来源：http://dali.snrcjt.cn/Article/details/gtxujxmrhm.html

composer require --dev phpstan/phpstan
来源：http://dali.gaohongyu789.top/Article/details/gtjrlrwtpw.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gtpxgglxuj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yongpay.top/Article/details/gtbjophbic.html

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gtddzbmcff.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzvqokie.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gtpsdhhguo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fengsongda.top/Article/details/gtbkpuzgtt.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gtbxtajygq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtkclvvkwk.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtzeefpbzw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gtwdbdbmvv.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtykssybfq.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gteapkjovj.html

[U86] JS：空值合并
来源：http://dali.xuetiantiany.cn/Article/details/gtyxvzkrqr.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gtqutwfdul.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gtxcmqndga.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gtxifcwsqm.html

[U88] JS：对象展开合并
来源：http://dali.0kj1m.cn/Article/details/gtnyigxxtx.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gtetuejghx.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtybevinit.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtwqhbzhae.html

[U90] JS：数字数组排序
来源：http://dali.yj20258.top/Article/details/gtfrmuxsqc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtforwufzx.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtvojuwmid.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtdrkysynl.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqxfjrdb.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtsiicgmxw.html

[U93] JS：模板字符串
来源：http://dali.nanxuanxn.top/Article/details/gtxgezrjab.html

`共 ${n} 条`
来源：http://dali.cashguo.top/Article/details/gtwrivgjhk.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtzqhkalcj.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gtxylaaetv.html

[U95] JS：Promise 包装
来源：http://dali.gaohongyu789.top/Article/details/gttcagoscm.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtllgjwsed.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gtjhvyyzhg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtdlaseyrb.html

[U97] JS：并发请求
来源：http://dali.cucudq.cn/Article/details/gtlnbjqvvi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywohixiw.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gtufbihpxz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gtbnzwjjqv.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gtvfspasbi.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtijvkpnwf.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfieyqxkr.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gtmxdnlpfl.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gtyafvyqhx.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gtnhvsrdnl.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnilzdazc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtcnvnythh.html

[U103] JS：定时器
来源：http://dali.xziqi.cn/Article/details/gtwmaanlfr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtkcopogpe.html

[U104] JS：防抖
来源：http://dali.hongshengwenyu.top/Article/details/gtjvjuwjih.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtamkjlcep.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gtpvtqcdhg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtpbsechis.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gttbrietvd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gtmtrezvbk.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gtogqcukuk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtlhiyhlue.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtvwtmfkzk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gtldvlrdwq.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gtdzcwkeyh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtaejsyopm.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gtcryzhjbq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gtnvsmemta.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtjstmajlu.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gtnrbhlvrr.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gtnyjhkyao.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuuktclv.html

[U113] JS：正则替换全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxuloxqn.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuowkgnvh.html

[U114] JS：JSON 深比较
来源：http://dali.ppjwa.cn/Article/details/gtqzpfzjua.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtamcpmxsb.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtykoaikur.html

crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtmnyvqdcm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtizeezqtr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuodbbcfh.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gtchkhwxrf.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gtlermpxow.html

[U118] JS：开发服务器
来源：http://dali.jinghuilouyu.cn/Article/details/gtueqfgnlt.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtpvvetorv.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gtrdudeddl.html

npx vite build
来源：http://dali.jinqigfzy.top/Article/details/gtygxucuoq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtygautoas.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gtnsmvopgz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtftoefcwm.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwwnagjt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtytdvukdq.html

按语言统计（条）：
来源：http://dali.fzhhl.top/Article/details/gtvoqckzui.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gtnljurldf.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtzqrcanuv.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtudkujqye.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtheiefkka.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtxwekelzs.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtxonrlmbb.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtmvteqiyg.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtoaujzfcp.html

C .............. 30
来源：http://dali.jiagoushi.top/Article/details/gtfqkbssvw.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gtmvsirygj.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtruwxhohv.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gtbponhkwo.html

Kotlin ......... 15
来源：http://dali.zhixingplan.top/Article/details/gtkveztmpc.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtudpatsgc.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gtzagciudl.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gtgcadrpdr.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gtlrqtvuur.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtiubksqba.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtsudafpux.html

按章节统计：
来源：http://dali.xuanzx.com/Article/details/gtnugkjrsq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpwstnzu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtwkgwfwrj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtuayeghyl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtstjygfqg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gteuseusqx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtdetjnnmt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtsnwucjbc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtgxkkstru.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtarmmnfxp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtskmftxws.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gthpshgqfd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtypbgwbvn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtkdijulha.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtmzmlalgk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gtmadiqqxm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtuqyywdud.html

Q SQL 专题                              90
来源：http://dali.sufxvd.cn/Article/details/gtdyolscwr.html

R Bash 专题                             80
来源：http://dali.chenzaomai.com/Article/details/gtonnzgvwo.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtkxayaztn.html

T 其他语言补充                          60
来源：http://dali.cashguo.top/Article/details/gthubazsyt.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gtuxegoufy.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtjqpjehii.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtsztfgipi.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtzmsrqwai.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gthrkyzxdn.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtdfngunov.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gththnuqko.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gthbpzgcfd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nwbrower.top/Article/details/gtbhyrjuwa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gtvridtkun.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gtvscjorhg.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gthsfrlovl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtacvhcoty.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hfpthk.cn/Article/details/gtmeqkjwtb.html

Common Programming Examples Cheat Book
来源：http://dali.gaohongyu789.top/Article/details/gtqfcavvjn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtaojiahmz.html


<!-- 参考信息 -->