代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtyzqhfisd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtjxuchech.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtnsiospkm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtndytrvjy.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gttmsvfffw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtypsmoeya.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gtnvsytdjm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtbbkphllc.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtzvfetpvg.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtuyouwzry.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtxypotqpq.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gtybiiesht.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gtcecuwggt.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gtqpcppfnj.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gtqrurivar.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtnmyceccm.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gtrioyfnfs.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gtauvccpcy.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtiojzpyjt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gtiqsobljn.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gtgjogvvjg.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gtlmrkrbwe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtliaujpsb.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gtamibqnno.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gthisifinn.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gtpywxvtez.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gtbeudhzqd.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gtccaeixaf.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gtympelsgm.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtkxgkgorx.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnnmnulf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gtjvevkuyv.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtrrbuedos.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gtrgcgqtlg.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gtrboyglft.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gtekbuawgt.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtkwazyfjg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gtxpdppyri.html

[U20] Py：缓存函数结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmljphvkm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gtzbfgxdrm.html

[U21] Py：自定义上下文管理器
来源：http://dali.quarkkingdee.top/Article/details/gtffymdswx.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtmbsxafjm.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtglttodow.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtzftavilm.html

[U23] Py：分块读取大文件
来源：http://dali.cucudq.cn/Article/details/gtgslsetge.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gtniqgphzs.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gtrgrevesa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gttwodpzwn.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gtglvpvpwn.html

csv.DictReader(f)
来源：http://dali.gotoacloud.top/Article/details/gtshmvejhw.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtcortvceo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtwwzqfwrt.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtvruxklng.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gtbfxvkxrx.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtimljfyco.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtksqaodjo.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gtazzjoedf.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gtbrsyjqsz.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtsxnlhrje.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gtayenadwi.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gtwqnuekjk.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtyzcvvmww.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtertdyttd.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gtuknrwzuo.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gtpskgzmev.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtbcogbfif.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gtqljalrmj.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtnayzzuoi.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gttmnwldwl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gtznsruhjg.html

[U36] Py：定时任务
来源：http://dali.iojbl.cn/Article/details/gtgxpxwack.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtvgdrrcqx.html

[U37] Py：读写 Excel
来源：http://dali.smart0.xyz/Article/details/gtbkmdkveu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gtydapdjlm.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gtbluegebw.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gtfahbpwym.html

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gtynaovvsp.html

sys.stdout.isatty()
来源：http://dali.xinyue.icu/Article/details/gtmkvzuyrz.html

[U40] Py：打印到标准错误
来源：http://dali.dianchejie.cn/Article/details/gtgcwuklfz.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtnissvrnh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gtgeitguhj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtqlfgmhyi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtplelrodb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gtrsuvedte.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gttzmirkor.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtffdsflah.html

[U44] PHP：开启严格类型
来源：http://dali.aibaodan.cn/Article/details/gtccymggof.html

declare(strict_types=1);
来源：http://dali.cqqwz.cn/Article/details/gtgouavxnu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gttmmhzehi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gttqdgxapl.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gtdvsacdro.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gtbddpbvvj.html

[U47] PHP：联合类型
来源：http://dali.shzxlz.cn/Article/details/gthjilkens.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gthgpeubgw.html

[U48] PHP：纯枚举
来源：http://dali.daria6918.cn/Article/details/gtnuhbelhy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gtnqqskvao.html

[U49] PHP：只读属性
来源：http://dali.andypj.xyz/Article/details/gtqsdfckfx.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gtzydljfmt.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtjxiijhnt.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtrvlxzkek.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gtquzspcba.html

[$a, $b] = $arr;
来源：http://dali.xinyue.icu/Article/details/gtcssoonzx.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtelqbsvlv.html

$double = fn($x) => $x * 2;
来源：http://dali.316326.xyz/Article/details/gtxbdbsmgg.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtvjwsabfg.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtfrntogme.html

[U54] PHP：空安全调用
来源：http://dali.guowangkeji.top/Article/details/gtohydvfdt.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gtbnvxpena.html

[U55] PHP：match 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtcflmgpjh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtjqmbhbiz.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrwjuvuqz.html

f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtsukvriwd.html

[U57] PHP：字符串插值
来源：http://dali.yonumen.top/Article/details/gtrwqvprks.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gtkrdssphj.html

[U58] PHP：数组三件套
来源：http://dali.cheryme.top/Article/details/gtspiklnln.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gthfefukpn.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtayhripqq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtdjtltbgz.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtknsywxij.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtzmwsobex.html

[U61] PHP：正则
来源：http://dali.xuetiantiany.cn/Article/details/gtgruhvnjs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtbxufuzmq.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtmncbopln.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.bjfxy.top/Article/details/gthoazsnqc.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtbngyktdq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gtkihcrkpc.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtaeezcekr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnxiangtu.top/Article/details/gtchtidslc.html

[U65] PHP：会话
来源：http://dali.xziqi.cn/Article/details/gtwtwbmapo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtekmrfhrw.html

[U66] PHP：设置 Cookie
来源：http://dali.xinyue.icu/Article/details/gtdxwpjuyq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzjrdxcvx.html

[U67] PHP：处理文件上传
来源：http://dali.zhoulong.xyz/Article/details/gtbgsoufau.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daxiang520.top/Article/details/gtqoicfwgf.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gtuflaxpzz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxrxvngq.html

[U69] PHP：PDO 预处理
来源：http://dali.hongshengwenyu.top/Article/details/gtvusfilcl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gtvhkuqxlg.html

[U70] PHP：PDO 事务
来源：http://dali.sysykeji.top/Article/details/gtpfurcxqt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.svipenyu.cn/Article/details/gtnmwxadpv.html

[U71] PHP：抛出异常
来源：http://dali.yueranfly.top/Article/details/gtbtsfyhrr.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtkcnlmtsv.html

[U72] PHP：写错误日志
来源：http://dali.nanxuanxn.top/Article/details/gtlaegxqtr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtkmkpxqfd.html

[U73] PHP：读取 ini 配置
来源：http://dali.gogol.net.cn/Article/details/gtdfnxdifq.html

parse_ini_file("config.ini", true)
来源：http://dali.cheryme.top/Article/details/gtjkxomazn.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtbkqwhocq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gtkcznojwa.html

[U75] PHP：依赖注入
来源：http://dali.yuanzhike.top/Article/details/gtmrxowtbn.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gttizhpdqv.html

[U76] PHP：简单路由
来源：http://dali.shzxlz.cn/Article/details/gthhtuzgyh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj202588.top/Article/details/gtcdpxegjl.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gthtsgddge.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtpsrulyme.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivoqujqo.html

composer require --dev phpunit/phpunit
来源：http://dali.snrcjt.cn/Article/details/gtifdqvydj.html

[U79] PHP：静态分析
来源：http://dali.yueranfly.top/Article/details/gtquhzjusb.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gtaaxnfnam.html

[U80] PHP：代码规范修复
来源：http://dali.pycfn.com/Article/details/gtzhanpzie.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gtmahdginm.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gtshllgfzc.html

npm init -y;  npm i express
来源：http://dali.chenzaomai.com/Article/details/gtcmqltktj.html

[U82] JS：package.json 脚本
来源：http://dali.haohaochexian.top/Article/details/gtdowkmgwq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.0kj1m.cn/Article/details/gtlbyiydbe.html

[U83] JS：ES Module 导入导出
来源：http://dali.pycfn.com/Article/details/gtswjbgstc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsfzbncz.html

[U84] JS：CommonJS 写法
来源：http://dali.chenzaomai.com/Article/details/gtiaylpdqh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gtkmxypwkc.html

[U85] JS：可选链
来源：http://dali.yanxiufei.cn/Article/details/gtkhzoklhy.html

a?.b?.c
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvjtptlz.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtrksnykvg.html

a ?? b
来源：http://dali.meibo888.top/Article/details/gtplcljqdr.html

[U87] JS：解构默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoycqjmfu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.haohaochexian.top/Article/details/gtavmnvfjo.html

[U88] JS：对象展开合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcltakiz.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gtbulghnpo.html

[U89] JS：数组去重
来源：http://dali.andypj.xyz/Article/details/gttyvstckt.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtfipirloz.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gtnqgcafbk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gteafpvbnu.html

[U91] JS：对象键值遍历
来源：http://dali.chenzaomai.com/Article/details/gttwarmekl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gtcrbwcrwl.html

[U92] JS：深拷贝
来源：http://dali.316326.xyz/Article/details/gtjkvbxnmf.html

structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofvgqcym.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtvukfaphn.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtyubllfue.html

[U94] JS：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbxludxqu.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtvmoytrwn.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gtqvgmxofi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtipxmwtpq.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gtqpkbxrww.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtdibgvfyh.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtlocjlrbh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtdiazwlbr.html

[U98] JS：fetch 带 JSON
来源：http://dali.gotoacloud.top/Article/details/gthcrhatpb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnqzz.top/Article/details/gtajonhdmm.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gtqmrrqxtx.html

el.addEventListener("click", e => {})
来源：http://dali.yuanzhike.top/Article/details/gtwajqtoag.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtgziigttz.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gtjlmrvjjx.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gtixohimcl.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtrihwauqk.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gtkbgfonuy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtigonqnfg.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gtdudvukcm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gttszzzzbv.html

[U104] JS：防抖
来源：http://dali.yangfankeji.com/Article/details/gtdocucjqr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtbxtvloom.html

[U105] JS：节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbumcfbt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuanzhike.top/Article/details/gtifortcpm.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gteuepoivd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcflxdbxf.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtfezxjnwb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtqkcrnwdz.html

[U108] JS：随机整数
来源：http://dali.ppjwa.cn/Article/details/gtijlcujyh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gtugalrygc.html

[U109] JS：数组分组
来源：http://dali.yuxming.cn/Article/details/gtxgdkvawf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtodspjvdp.html

[U110] JS：数组分块
来源：http://dali.ehwqpu.com/Article/details/gtovjdvmft.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gtnkdnqrzg.html

[U111] JS：对象转 Map
来源：http://dali.xuanzx.com/Article/details/gtkyuowhru.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtajfaaaju.html

[U112] JS：字符串补位
来源：http://dali.redwolf501.top/Article/details/gtoldbeirn.html

"7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtigkqnfcj.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtfurcnhhm.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtfckzoorx.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gtbcrtumtu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtwqpworcq.html

[U115] JS：生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtoxlsuurh.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtfuwmgyea.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yonumen.top/Article/details/gtoxbjzvqm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gtosrhmpls.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gttuhbxvns.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtlcxfseml.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gtitzuoeko.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtbpcfrzoy.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gtlmqpydtt.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gtjzkvjywa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gtdbxdgonn.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gteimqzmez.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtatoepikp.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gtlzeiinhd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcwvnhaen.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtfdmsbmzh.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gtfvrpxmuk.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gtjjfoitgt.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gtpnigyrdr.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gtfkofpqep.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtajbiapte.html

Go ............. 212
来源：http://dali.hammf.cn/Article/details/gtnrsoiggl.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtiqedipyr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtsrrytlfy.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gtpwuxucrn.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gtqrvcgfqn.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gtcoywmfah.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gtvsniminf.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtonxtobhb.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtmimhsrfq.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gtxmmeqklq.html

Perl ........... 10
来源：http://dali.316326.xyz/Article/details/gtfrwpcilv.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gtcmdsmcaq.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtmaetuivs.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwwpknme.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gtrwuqsywr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtjzuxlecn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gturcefiqk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtlksqncfj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtnbcbwlzp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gtiwrgdvff.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtfhymgsbt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtpeueuoba.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtsmhbtyrv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtvxqderpq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtyoxbkhlq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtpiarncgq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtnetqxoss.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtrgaufstg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gtpjmsnlnk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.c1oappe.top/Article/details/gtysvbebmv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtlefkosto.html

Q SQL 专题                              90
来源：http://dali.tanke756.top/Article/details/gtiyiaxdlx.html

R Bash 专题                             80
来源：http://dali.daxiang520.top/Article/details/gteioypitn.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gtmhqktwki.html

T 其他语言补充                          60
来源：http://dali.yuxming.cn/Article/details/gtrpgsejap.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gtaykqgvpf.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtfewmwgbg.html

合计                                  2106 条
来源：http://dali.yonumen.top/Article/details/gthydzcasc.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtfzpamijj.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gtdprmjcaq.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtfoayscry.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangshuangyany.cn/Article/details/gtiowgucpd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtodfkmcqu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gtehhivckj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhixingplan.top/Article/details/gtnvfidhgr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258.top/Article/details/gtjgnogvip.html

—— 文件结束 ——
来源：http://dali.cashguo.top/Article/details/gtzferokrq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthghesegz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtxsswveuq.html

Common Programming Examples Cheat Book
来源：http://dali.hongshengwenyu.top/Article/details/gtebdoskwi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvhlhtgkd.html


<!-- 参考信息 -->