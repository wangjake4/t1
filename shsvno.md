代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtznzyshud.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gtvcducbno.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gthxbyfpmr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gticbodehj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtoqycqgwd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gthpdtaxpb.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtsoiacgyh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtfmseirgy.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtfzxiaigg.html

list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtfmojtten.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gthvsgjkuq.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtludogarg.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gtwcwjtmke.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtvhhxnneg.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtdhpqmkav.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gtnrfjztgl.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gtclptqygn.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtascyrscx.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtirhlrtwd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gtdgwgpkdk.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gtzhvdqlxr.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gtnumygxwk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gtehlxdxfo.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtvdzetivo.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqdicxjz.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gtqpjsorro.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtiizaahey.html

defaultdict(list)
来源：http://dali.dianchejie.cn/Article/details/gtiboevsyy.html

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gtwnhfmjvj.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtrxtqdobw.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtyatioubf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gtmbabgcpl.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gtzbwaepyn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gtevpjvbcv.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gtdchwinej.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gtvmojemxp.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtmsamxkag.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gtxfxtozcy.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gtlpnekbxq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hongshengwenyu.top/Article/details/gtsxmnmjhp.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtcifmvnoo.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gtgiyujhgp.html

[U22] Py：矩阵转置
来源：http://dali.zhengqikj.top/Article/details/gtzgzyvira.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtohneanie.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtwyczwdis.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gtcnzlnhvn.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gtvhyppjdl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtfvuujmbi.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gtwngzgdpo.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtjtnrwozo.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gtftagnmqv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gtelithrqa.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gteqdqwcxg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gtqqthuiek.html

[U28] Py：类型别名
来源：http://dali.yvedp.cn/Article/details/gtmtpmxmxd.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gtftgckzgu.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gthuffbdyj.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtnfvuztgs.html

[U30] Py：数据类
来源：http://dali.hfpthk.cn/Article/details/gtaplwfjic.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtjmqacemw.html

[U31] Py：单测
来源：http://dali.feifeiyinyue.top/Article/details/gtzxepzbns.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtxoweakug.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gtdxlysktm.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gtcjeamyxd.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtjtxhli.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtlvoltblm.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gtwhihtnjj.html

chardet.detect(raw)
来源：http://dali.wangshuangyany.cn/Article/details/gtcjlwixci.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtxncotcls.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gtwuqsjrhu.html

[U36] Py：定时任务
来源：http://dali.yueranfly.top/Article/details/gtjkqomnwd.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtdlduawka.html

[U37] Py：读写 Excel
来源：http://dali.yongpay.top/Article/details/gtrrdlvxuq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gtllswskas.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtuduvhxdn.html

Path(__file__).resolve().parent
来源：http://dali.yj20258.top/Article/details/gtyixwjwbr.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gtrchasizl.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtaljkzwyz.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtmaojpfaz.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtgqzqexlk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigfzy.top/Article/details/gtcrxjfcqj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gtqkjzebvw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tian-w.cn/Article/details/gtsrcostdl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sufxvd.cn/Article/details/gtcxekgeyw.html

[U43] PHP：声明命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtedgvncsk.html

namespace App\Http;
来源：http://dali.daria6918.cn/Article/details/gtdkqjsqjx.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gtjiewbjxz.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gtgrszodyf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gtihwziyvm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtldwcanvi.html

[U46] PHP：可空类型
来源：http://dali.yangfankeji.com/Article/details/gtbfwjhomp.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gtrjkfkels.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqafpsef.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gthdtziufl.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gtqaifhsak.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtczayohgm.html

[U49] PHP：只读属性
来源：http://dali.aibaodan.cn/Article/details/gtcpxxvqzo.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gtqvodznmc.html

[U50] PHP：构造器属性提升
来源：http://dali.sysykeji.top/Article/details/gtumaukgyk.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gtseomfnog.html

[U51] PHP：数组解构
来源：http://dali.xziqi.cn/Article/details/gtfopfnrnk.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gtvkelksem.html

[U52] PHP：箭头函数
来源：http://dali.yj202588.top/Article/details/gtxwmnnaea.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtrpxxevij.html

[U53] PHP：空合并运算符
来源：http://dali.jlsjyb.cn/Article/details/gtckhoydlv.html

$v = $a ?? $b ?? "default";
来源：http://dali.snrcjt.cn/Article/details/gtxreibcga.html

[U54] PHP：空安全调用
来源：http://dali.yonumen.top/Article/details/gtoibnkqxi.html

$obj?->method()
来源：http://dali.xziqi.cn/Article/details/gtzuaqdvbh.html

[U55] PHP：match 表达式
来源：http://dali.cashguo.top/Article/details/gtmavvwbvo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gtkmtqrfsx.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtiikudiix.html

f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajssiewp.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtxzwaiytq.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gtgovhaeab.html

[U58] PHP：数组三件套
来源：http://dali.gogol.net.cn/Article/details/gtfvggrdaa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gtujtvibxr.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtfeyzuhag.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtsqjoyrhq.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gthyyeadoa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gtfymjgvzm.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gtpmwpisnq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gteidydorl.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gtpttxylhc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtqqdtpbuo.html

[U63] PHP：文件读写
来源：http://dali.316326.xyz/Article/details/gtnnhnkfwt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gtngzthwsk.html

[U64] PHP：目录遍历
来源：http://dali.ybcxt.top/Article/details/gtsqczefwo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenjidiqi.icu/Article/details/gticgcsqae.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gtxhqhzewz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gthrmhfcmv.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gtqyihowop.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shuidangran.top/Article/details/gtrrjpgvob.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuucnbnk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cucudq.cn/Article/details/gtmaynqofh.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gtggrwxmzm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpdvffdl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagqudruz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtbrvkblff.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gtwxvkadkd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ppjwa.cn/Article/details/gtnkcypcsq.html

[U71] PHP：抛出异常
来源：http://dali.316326.xyz/Article/details/gtoqgfoemc.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtigsbuptb.html

[U72] PHP：写错误日志
来源：http://dali.chenlongwang.top/Article/details/gtnutknkei.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gtvxnkoesa.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnqzz.top/Article/details/gtkaiqhucf.html

parse_ini_file("config.ini", true)
来源：http://dali.bjfxy.top/Article/details/gtjdclmhfv.html

[U74] PHP：读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtxgqxfrcd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtxlosehqi.html

[U75] PHP：依赖注入
来源：http://dali.nwbrower.top/Article/details/gtyeabrwzd.html

composer require psr/container
来源：http://dali.cheryme.top/Article/details/gtvgrcebbx.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gthzyqikrt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jianghu66.top/Article/details/gtdqujhmse.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtzeidlwlv.html

composer require twig/twig
来源：http://dali.zhixingplan.top/Article/details/gtvzxttfbz.html

[U78] PHP：单元测试
来源：http://dali.chenzaomai.com/Article/details/gtdkubcoty.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gtbvitvvtx.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gtbcypacqb.html

composer require --dev phpstan/phpstan
来源：http://dali.hammf.cn/Article/details/gtrhpceynl.html

[U80] PHP：代码规范修复
来源：http://dali.xuanzx.com/Article/details/gtqkseyscu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtnynuphhv.html

[U81] JS：初始化项目
来源：http://dali.aizwys.cn/Article/details/gtjczkdylc.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtptguyetj.html

[U82] JS：package.json 脚本
来源：http://dali.tanke756.top/Article/details/gtwbsvbijb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtoowvhssg.html

[U83] JS：ES Module 导入导出
来源：http://dali.andypj.xyz/Article/details/gtlswegdqj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtgaihtszt.html

[U84] JS：CommonJS 写法
来源：http://dali.chenlongwang.top/Article/details/gtlidaswgm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gtkovhsqnb.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gtzadmnuxr.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gtqmvzozwx.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gttkypuwua.html

a ?? b
来源：http://dali.redwolf501.top/Article/details/gtodtfnwkz.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gthzkqkkwe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gtpsbgiffi.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gtgswxuipx.html

{ ...a, ...b }
来源：http://dali.feifeiyinyue.top/Article/details/gtfkcqpdav.html

[U89] JS：数组去重
来源：http://dali.vqdsnc.cn/Article/details/gtdfzadxer.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtdnbuthsi.html

[U90] JS：数字数组排序
来源：http://dali.yuanzhike.top/Article/details/gtlzbabroi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtejmekffn.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtvcqrpsun.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gtkbjjyyyt.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gtlkljozef.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgscqowy.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtmglltirw.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtphuygtuj.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtwraxwbho.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtzupdwqze.html

[U95] JS：Promise 包装
来源：http://dali.redwolf501.top/Article/details/gtmjwrivxs.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gtytvkfvwd.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gtfrqzyunn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtxedrsedz.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gtrtzoaodo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtpgqkilgk.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtpicsvqpa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.smart0.xyz/Article/details/gtamqnxmmn.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gtuivfmwxc.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmgbvmvj.html

[U100] JS：DOM 查询
来源：http://dali.zhongyouzk.top/Article/details/gtgabihvlu.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gtoibeaedd.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gtqtqszctr.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gttntyxozg.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtkhbsnczd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fzhhl.top/Article/details/gtqmyavjlo.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gtldltijwt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmcyvcrh.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gtxlwqvcjf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtzfevsksu.html

[U105] JS：节流
来源：http://dali.fengsongda.top/Article/details/gtzrufvygc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtzptewzke.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckcouefk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gticakcvyp.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gtvwtnhqij.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtmuwfwsrg.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtpvchredd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.bjfxy.top/Article/details/gtkuimwjvy.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvedtvotw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtdlruygyy.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gtjsmzkrqc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.c1oappe.top/Article/details/gtrtxnwnrd.html

[U111] JS：对象转 Map
来源：http://dali.cashguo.top/Article/details/gtklmgdjlk.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gtxpvpgobd.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtllselido.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtsfegknbj.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtgllpdxge.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtgolwincv.html

[U114] JS：JSON 深比较
来源：http://dali.nanxuanxn.top/Article/details/gtfrjmizik.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtdbkooxhd.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtndkrtsls.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtrnihocjq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtxaejbivu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzchwtwzx.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gtjazzeafr.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258888.top/Article/details/gtbisxqpzv.html

[U118] JS：开发服务器
来源：http://dali.sufxvd.cn/Article/details/gtsyfiykab.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gtbksfogwp.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gtdojnsnnn.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtnwbhdzgx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gtktzlnusr.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gtgggbziaq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwcyxdjll.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gtmsknadij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbwocqnex.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gtenllpvbq.html

Python ......... 252
来源：http://dali.daxiang520.top/Article/details/gtjfuvjmay.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gtqmivsdml.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtvtxgjhbc.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gtnfiljmhv.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gthoiktnsj.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgmflngz.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gttsvqnucw.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtatzqwlny.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtofcbypuq.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gtcrhrlbkh.html

SQL ............ 90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtgvxwyl.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gtvsyluwfn.html

Kotlin ......... 15
来源：http://dali.chenlongwang.top/Article/details/gtpllremop.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gtjhltgxdf.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gtpgxnxlrw.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtmliuafsq.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwjnhcit.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtknbatdqc.html

合计 ........... 2106 条
来源：http://dali.sxryk.cn/Article/details/gthondopoo.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gtycaljsmz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtpeqdgnos.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtlncitker.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtakzacned.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gtvlzeponb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hywenlv.cn/Article/details/gtbxsrsixr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtoraafvpb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtubalotih.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtbgacposk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtctiuhlfb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtqhcdffmy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtiejbicdg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtujmusevd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtpgmgnlck.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtdwheufzx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sysykeji.top/Article/details/gtqnymdryj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtgmmicruy.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gtjaiwsaaj.html

R Bash 专题                             80
来源：http://dali.vqdsnc.cn/Article/details/gtublnpwvt.html

S C / C++ 专题                          60
来源：http://dali.fzhhl.top/Article/details/gtrsoqpbck.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdilzrisq.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gtcemlecoh.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtpnpgiqlr.html

合计                                  2106 条
来源：http://dali.hywenlv.cn/Article/details/gtfcxzzpkh.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtgxzojeyl.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gtqmmkkmwy.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtyrgzqnky.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shzxlz.cn/Article/details/gtjninjiub.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtdbhycnsd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gtsgeqwoib.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtxgkqzkyq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gtciymhzff.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gtjdxhjhvj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzssyflyx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cheryme.top/Article/details/gtqfcvcxyi.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gtlocihzps.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtulonjwpg.html


<!-- 参考信息 -->