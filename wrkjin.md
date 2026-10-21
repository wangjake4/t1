代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtnzxfaydy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gtqlseghck.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtnpayydvm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gtkumcuqeg.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gttksnqbvc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gtkpppzpst.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtmunyrdpl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtafxqxhci.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtaebapxgi.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtrsknejbp.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtohlrgtwm.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtmqztbsiu.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtkqgagjcu.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtsufedzkb.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfehwgcyt.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gtmpxclepm.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtrugnbold.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtqvbwidxj.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gtfdsgudwe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyqwlfbm.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gtnkcctbia.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtyxzzrvhj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ybcxt.top/Article/details/gtakzgjrmw.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gtvyndwtpl.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrfnxrhg.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gtvljgeikw.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtpkztmczw.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtstkbpxee.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gtpjhsvmwe.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtiuuqkfik.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaxvzpqn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gtagzcggxt.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gtaftgrrzw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gtorhszcki.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtuglzliha.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gtvstxmktq.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxofnsrxe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtsptrbxdh.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gtzkojytlx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwichfpej.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gtwxqbsmth.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gtkyagnowa.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gtibqlkzel.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtafzqouly.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtmrpsbbzu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioruxiya.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtufnusjix.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gthlrmlton.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gthzctvsyi.html

csv.DictReader(f)
来源：http://dali.tanke756.top/Article/details/gtyshqugya.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gtpokscthr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gthgdnmsli.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtwbnkwoht.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtkkigqyjw.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtyvikknsr.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gtpzjlemxy.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtlggtpokf.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakxbbuuo.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovvnjeel.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gtsjubmwsw.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gtlclgnwic.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gtumrbxtho.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtgrafuzot.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtxmgnmquw.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gtyrgejlnm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gtixeaqubl.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtwuaajfjx.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtmwjyzqzb.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gtbpgbjtiw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gtyyjjidpq.html

[U36] Py：定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtyoqtdsms.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtigzobwte.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtxfgaathp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtsrcwqsiu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdftqougc.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gtkgasimww.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gtbmwaivcg.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gtepoimbiz.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gtuivroxvh.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtjsfbsfwk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gtxktswjlm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gzhubu.top/Article/details/gtczxebqhh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sysykeji.top/Article/details/gtezeqmzse.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gtwcmenuvr.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtkvoqxuvv.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gtlppylpay.html

[U44] PHP：开启严格类型
来源：http://dali.snrcjt.cn/Article/details/gtzxojlsim.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gtplpuyntn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.bjfxy.top/Article/details/gtkhoefywv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtpnpxevmp.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtujjxvpfm.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gtnpgtmefe.html

[U47] PHP：联合类型
来源：http://dali.mhx1999.top/Article/details/gtkitrnamo.html

int|string $id
来源：http://dali.vqdsnc.cn/Article/details/gtdyicvbjw.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gtflhroyvl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gtbjmdiwxs.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gtmqizupsi.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gtiyxhlavj.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gtdetkahan.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gtvxdqamhm.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gtybfngvij.html

[$a, $b] = $arr;
来源：http://dali.guannengcc.top/Article/details/gteiaolymn.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gtrosqnldc.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gtnobdxtev.html

[U53] PHP：空合并运算符
来源：http://dali.hnqzz.top/Article/details/gttvviwidj.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gtcgdrakel.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gtystsaeoa.html

$obj?->method()
来源：http://dali.andypj.xyz/Article/details/gtzfaszmrp.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtddlfnugp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gtythtffzx.html

[U56] PHP：命名参数
来源：http://dali.yuxming.cn/Article/details/gtojstrbdq.html

f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtdigtzrrv.html

[U57] PHP：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtbupxtlyq.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gtveorpyev.html

[U58] PHP：数组三件套
来源：http://dali.bjfxy.top/Article/details/gtlvvqopif.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dianchejie.cn/Article/details/gtdzpibixn.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gtjgplllss.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtmuxzouqe.html

[U60] PHP：JSON 编解码
来源：http://dali.zycfv.cn/Article/details/gtyhkonlca.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj202588.top/Article/details/gtxhtzqcch.html

[U61] PHP：正则
来源：http://dali.xuanzx.com/Article/details/gtnqriorve.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtlggrroky.html

[U62] PHP：日期对象
来源：http://dali.shuidangran.top/Article/details/gtqzcekxjc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtetmqtpgc.html

[U63] PHP：文件读写
来源：http://dali.aibaodan.cn/Article/details/gtvaqczomu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gtwxscuucz.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gteosubadn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gtitxklwfx.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gtxexxaoal.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtvbaacufo.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gttdmhavsy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtsugyxuum.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gthlugxcxk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hongshengwenyu.top/Article/details/gthbtahlfw.html

[U68] PHP：PDO 连接
来源：http://dali.guowangkeji.top/Article/details/gtjjujvuzg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.havefunace.top/Article/details/gtpgdprfke.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gtbjmneqtq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xylfe.cn/Article/details/gthrybymye.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gthbktayzq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtcfbbdddc.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtsbhvqabd.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gttuzshurd.html

[U72] PHP：写错误日志
来源：http://dali.nwbrower.top/Article/details/gtpztstdop.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gtfkaevkae.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gtswnnzlbm.html

parse_ini_file("config.ini", true)
来源：http://dali.pycfn.com/Article/details/gtwdxsrpxq.html

[U74] PHP：读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtbwbnhdzj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zdqjudy.top/Article/details/gtlmtlpbtv.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gtbrsceuhu.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gtnokiueop.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtmdvraqeg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gttjtaplox.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtqnsjfvaz.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtrundrdaa.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtcwonzvwy.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaehpcgzz.html

[U79] PHP：静态分析
来源：http://dali.aizwys.cn/Article/details/gtxlotkbuu.html

composer require --dev phpstan/phpstan
来源：http://dali.sxryk.cn/Article/details/gtnutpdxmv.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gtkhwvfefu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gtgllpvxqa.html

[U81] JS：初始化项目
来源：http://dali.zhengqikj.top/Article/details/gtmklmjwvh.html

npm init -y;  npm i express
来源：http://dali.kuanghao11.cn/Article/details/gtfutzkzbj.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gtdbcrpyld.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrwxsiae.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gtkflxvvce.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtxgzxpalt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtrssegtyf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtrjpxuieo.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gtmrafneck.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtgmxygovs.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gtcbxylokq.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gtpylvdzoi.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtmpufwuwk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.meibo888.top/Article/details/gtcamudshe.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gtvdbvjcpn.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtpfbdvjys.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtjwqwvnwd.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtqvqznbho.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gtdcliosvt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtbiscgrnj.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtrtejixbg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hongshengwenyu.top/Article/details/gtcytjmmai.html

[U92] JS：深拷贝
来源：http://dali.zdqjudy.top/Article/details/gtccigzkdh.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslthhera.html

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gtnugqybwl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gtxttfuvev.html

[U94] JS：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtwbuqssdg.html

const double = x => x * 2;
来源：http://dali.svipenyu.cn/Article/details/gthggbqaki.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilqbmokm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtgdywwxse.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gturnshfte.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtaojlerac.html

[U97] JS：并发请求
来源：http://dali.pengpengdd.cyou/Article/details/gtvbxxzlkp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtzevvcjqg.html

[U98] JS：fetch 带 JSON
来源：http://dali.9152youxi.cn/Article/details/gtvqmmuxxb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtsjozhgzx.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtcclzyawi.html

el.addEventListener("click", e => {})
来源：http://dali.yuanzhike.top/Article/details/gtcytsunjl.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gtseotexus.html

document.querySelector(".item")
来源：http://dali.zhongyouzk.top/Article/details/gtbogbwokl.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtkkpwmpuv.html

el.classList.toggle("active")
来源：http://dali.nanxuanxn.top/Article/details/gtawdnwaxs.html

[U102] JS：本地存储
来源：http://dali.hnqzz.top/Article/details/gtzljdgbis.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtmupjvrlp.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtsiblhtnb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gtcvhkbwqu.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gtqiubzcbl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtxofstgsw.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtinixwzbc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwkxystq.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gthiuyxafv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenjidiqi.icu/Article/details/gtufbwptsm.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtdukzpczx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtkcjaiomx.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtxvjnyuaa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gotoacloud.top/Article/details/gtahoxpcaq.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gtxiggjdqz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtekigvjtj.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gtbmblblxq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gtulpijjat.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtmmlaslfu.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtszecutgj.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gtglexklun.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtgffschse.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtrulbvaqv.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtkkvxeaqj.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtvfrfotxz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbywwguzs.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtofmhnwhb.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtvpngrwnl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gtwproreah.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cqqwz.cn/Article/details/gtduhivwrr.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtrxebiuno.html

npm i -D vitest;  npx vitest
来源：http://dali.dashuyun.cn/Article/details/gtgyfrooux.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gtvmlcdgur.html

npm i -D vite;  npx vite
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkjqkeui.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gtswdczmgw.html

npx vite build
来源：http://dali.zdqjudy.top/Article/details/gtvvpqgtqw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.316326.xyz/Article/details/gtoglnjyzn.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gtnbdjjtkx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtquozsvfj.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtsomokcwh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtolvsqukx.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtcopojcin.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gttaixjevo.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gtdostmysn.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gtdpcjedyz.html

TypeScript ..... 212
来源：http://dali.yueranfly.top/Article/details/gtfpczefdh.html

Java ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreinpypa.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtimilbxoq.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtpqjxnkms.html

C# ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtgjdnfqew.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gteuaboaee.html

C++ ............ 30
来源：http://dali.ppjwa.cn/Article/details/gtahhxlswe.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtrujtmfvv.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gtywakyhlu.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtesuoofux.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtkncjwois.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gtqhrwfodb.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtgkbxskwi.html

Scala .......... 10
来源：http://dali.kuanghao11.cn/Article/details/gtxemlirsl.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gteltniufq.html

合计 ........... 2106 条
来源：http://dali.havefunace.top/Article/details/gttgyqllgg.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gturhimcwb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtrjbbdkzj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtvxhivcpf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtwjjbuwpn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtmsnedera.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gtanolkofg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtrmphhzms.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtelapncrz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtsdpmwqqv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtwdiusdhe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gtzhoxurxr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtudxzwioy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtkkhplgeu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtuothachq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtqrffmuzk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gtjdglperc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtnultrbqr.html

Q SQL 专题                              90
来源：http://dali.chenjidiqi.icu/Article/details/gtejgtwkow.html

R Bash 专题                             80
来源：http://dali.jianghu66.top/Article/details/gtgesmtbcf.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtaqocufqa.html

T 其他语言补充                          60
来源：http://dali.shuidangran.top/Article/details/gtgsfveavm.html

U 高频实用片段                         120
来源：http://dali.ybcxt.top/Article/details/gtieisglym.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtxxozrrng.html

合计                                  2106 条
来源：http://dali.chenlongwang.top/Article/details/gtyyrvregt.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gthzccinde.html

使用提醒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuubphrd.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtojlxggyw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aibaodan.cn/Article/details/gtcqzhdakx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gtxpqkaamf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.havefunace.top/Article/details/gtfnobpnuy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gaohongyu789.top/Article/details/gtxnvnbsij.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gtbzrrkcln.html

—— 文件结束 ——
来源：http://dali.yanxiufei.cn/Article/details/gtgursorvu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtprptzljx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fzhhl.top/Article/details/gteezuwifv.html

Common Programming Examples Cheat Book
来源：http://dali.fzhhl.top/Article/details/gtrjlmbabl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrnogcaks.html


<!-- 参考信息 -->