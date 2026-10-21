代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtnaprmwzx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtlldbfdgu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtsbxftyvr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtnhilfnxi.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gtlrsfpnhu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtdanmnsbw.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gtofbyzfxa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtsbrlqltl.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtzdopihev.html

list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtttlmwkrm.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gtvvmlndru.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gthnqmcfyd.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtmjxeduwc.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gtujgujuyg.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtuosafkjq.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gtymvrwkmo.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gtecaoybzj.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gtqzhuzvey.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtwtnzmemf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gtygszvgzq.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gtkeymogdr.html

(x * 2 for x in arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtsrxytyzy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gttkzbifjn.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gtnttzjbpn.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gtpftdvbfw.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gthlsffhju.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtnlczznii.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtkzgxdqui.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtmrosodqw.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gtphontexv.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtvahqhvwe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtjckcasrb.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gthvihibws.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gtridhtkiu.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gtqurvimco.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtjfdipwxy.html

[U19] Py：正则替换带回调
来源：http://dali.jianghu66.top/Article/details/gtcpfiznos.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtixgktvbj.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gtszxcfxyg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtengsjdhb.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gtlppjjhhf.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gteeatleqd.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtovgdnjfz.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtpebbacwn.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gtqiztwuka.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gtkzcrzeej.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtypbowcuj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtpddjfxpa.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtyioervqj.html

csv.DictReader(f)
来源：http://dali.zhengqikj.top/Article/details/gtkozjowii.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gtozokayhd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gtyqawvpwe.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gtivudnkmi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gtlwvrtgor.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtaxfnvkjp.html

UserId = int
来源：http://dali.meibo888.top/Article/details/gtotsztnig.html

[U29] Py：属性校验
来源：http://dali.jlsjyb.cn/Article/details/gtbtorxspf.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtcuuyyvtf.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtfjjamylz.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gtvjdojhnx.html

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcyhtshj.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gtxoeyqshv.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtgskbwmxy.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmcgcgzx.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gtlorbgczb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gtovgahkhu.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gtxipxhyaa.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gtduxgubkz.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwdgarcs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gtjvrhmftg.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gtjfwbjtfh.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtxxcciwbb.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtzfixgfok.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gtkhqucghj.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gtoxmltmhj.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gtawwyaitv.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gtgsvnrhqt.html

sys.stdout.isatty()
来源：http://dali.jqgfzy.top/Article/details/gtzrjmapoi.html

[U40] Py：打印到标准错误
来源：http://dali.hnxiangtu.top/Article/details/gtfvdjmyro.html

print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtmqcswaqt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jiagoushi.top/Article/details/gtrpdpksqu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gtdihcxaiw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.kuanghao11.cn/Article/details/gtkglmjtus.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gtyopdzrvd.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gtkuwsayss.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gtucvpjjgm.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gtzbqkxjxs.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gtigzwwjuz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gtbewsqiro.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gttqkasmki.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtxygayrxd.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gtuypskaet.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gtnbjylmct.html

int|string $id
来源：http://dali.yj20258888.top/Article/details/gtpjfaippa.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gtkxgwqtmc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.9152youxi.cn/Article/details/gtlyyqkinr.html

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gtloxzdirl.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gtsmoozmjc.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gtinvsuahy.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkrnddtee.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gtsxuhrlwx.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gtpyyrnosk.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gtjknvbbnr.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gtxhciesai.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gtlzdhdwpg.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gtbwkkkqkt.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gtdjtyzwwg.html

$obj?->method()
来源：http://dali.ydzc1.top/Article/details/gtmbsnrtmo.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gtwgfyrsjq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtnpktmkgp.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gtaqpbkuqm.html

f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtievluhvs.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtdepfoxqr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gtwwunwbia.html

[U58] PHP：数组三件套
来源：http://dali.gogol.net.cn/Article/details/gtffaoekmb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cheryme.top/Article/details/gtgaoibbvv.html

[U59] PHP：自定义排序
来源：http://dali.iojbl.cn/Article/details/gtxewkxdfg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtyvowfstf.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtokjzobhv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gtoqqfoiyn.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtfffhfbie.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtakybtoji.html

[U62] PHP：日期对象
来源：http://dali.jqgfzy.top/Article/details/gtjaacvgex.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangdashe.top/Article/details/gtkrceoadq.html

[U63] PHP：文件读写
来源：http://dali.dianchejie.cn/Article/details/gthvbxbsxo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gzhubu.top/Article/details/gtyzytlhoi.html

[U64] PHP：目录遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtvegcybxm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jiagoushi.top/Article/details/gthfrrcigs.html

[U65] PHP：会话
来源：http://dali.guannengcc.top/Article/details/gtcodnewwn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtaegopxit.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gtonutjbrj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.smart0.xyz/Article/details/gtdpembhfh.html

[U67] PHP：处理文件上传
来源：http://dali.hfpthk.cn/Article/details/gthdoceale.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwzrvkjx.html

[U68] PHP：PDO 连接
来源：http://dali.yongpay.top/Article/details/gtkixphpar.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gtxzradqbl.html

[U69] PHP：PDO 预处理
来源：http://dali.yongpay.top/Article/details/gtaymsswhd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtusxhoeod.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gttxzsgudz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj202588.top/Article/details/gtpfldyngv.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gttkvvbwzo.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gtxdrsdyur.html

[U72] PHP：写错误日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswsebpak.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtocbtxhcs.html

[U73] PHP：读取 ini 配置
来源：http://dali.bjfxy.top/Article/details/gtehoihelv.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtblsiafgw.html

[U74] PHP：读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtfmciayet.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gtlwuoxqer.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtpzxcmrxh.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gthbxittsq.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gtihpukftl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hammf.cn/Article/details/gtwymzybbq.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gtjayqyxhc.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gtljrcfjpz.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtcwwouecy.html

composer require --dev phpunit/phpunit
来源：http://dali.snrcjt.cn/Article/details/gtkdhachvh.html

[U79] PHP：静态分析
来源：http://dali.jianghu66.top/Article/details/gthnrghobl.html

composer require --dev phpstan/phpstan
来源：http://dali.ehwqpu.com/Article/details/gtgrbllber.html

[U80] PHP：代码规范修复
来源：http://dali.316326.xyz/Article/details/gtjagccnyl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtjybeknpi.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gtynuvkwmc.html

npm init -y;  npm i express
来源：http://dali.shuidangran.top/Article/details/gtlvvbcmlq.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gtjztafjsi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtgbjlxtwp.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtrkaripcz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtbsbvzwpx.html

[U84] JS：CommonJS 写法
来源：http://dali.gzhubu.top/Article/details/gtxympvwqt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gtelcwnnhf.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gtelzaasok.html

a?.b?.c
来源：http://dali.kuanghao11.cn/Article/details/gtuwfuygef.html

[U86] JS：空值合并
来源：http://dali.redwolf501.top/Article/details/gtcjsjbtfn.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gtnuhgdgxg.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrtnopcd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cheryme.top/Article/details/gtofwzpple.html

[U88] JS：对象展开合并
来源：http://dali.quarkkingdee.top/Article/details/gtfxclqwsm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gtwskfgfey.html

[U89] JS：数组去重
来源：http://dali.pycfn.com/Article/details/gtimzcbpkx.html

[...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwntosbrs.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gtijuqtjyt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtbzttrymw.html

[U91] JS：对象键值遍历
来源：http://dali.yueranfly.top/Article/details/gtdchehnrj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gtpxybfyzh.html

[U92] JS：深拷贝
来源：http://dali.cqqwz.cn/Article/details/gtjxgnnquw.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtotraaxxh.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfxhxsrz.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gtgqagloar.html

[U94] JS：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtggrdzghf.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtppebcaxn.html

[U95] JS：Promise 包装
来源：http://dali.dashuyun.cn/Article/details/gtugkkrnzb.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzphrtvk.html

[U96] JS：async/await 与异常
来源：http://dali.zhoulong.xyz/Article/details/gtgdovmfyn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gthnmwsqmn.html

[U97] JS：并发请求
来源：http://dali.jqgfzy.top/Article/details/gtumuvsbpv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtalmaomad.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtgifjmfgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gtpajyhnfb.html

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gtsxtedquc.html

el.addEventListener("click", e => {})
来源：http://dali.jlsjyb.cn/Article/details/gtwbtktufg.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtnciztpno.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gtqxmofvrp.html

[U101] JS：classList 操作
来源：http://dali.zhengqikj.top/Article/details/gttbabnmxr.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gtwuubsuyr.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gtvsngxblb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjfxxtfi.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gtjpynnfjv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yangfankeji.com/Article/details/gtigtxlzxd.html

[U104] JS：防抖
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyxewuxe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtfcvasgle.html

[U105] JS：节流
来源：http://dali.fengsongda.top/Article/details/gtwfhjezco.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtjrxiogia.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtwjlrjbdk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtdsausqzi.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtbccruast.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtdxpdfxzb.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gtnuwsfdkg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gtlgksqbhq.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtxjfjjfxs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtpljrijsf.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gttvsqoirn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgufenzy.top/Article/details/gttjwpjhhu.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gtkegfwssh.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gthffvqpno.html

[U112] JS：字符串补位
来源：http://dali.jinqigfzy.top/Article/details/gtgdmgzevz.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtfpwcwhgv.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gtbcgzphvu.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtzlrbeofn.html

[U114] JS：JSON 深比较
来源：http://dali.xinyue.icu/Article/details/gtyjzthjyr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gthmifcdag.html

[U115] JS：生成 UUID
来源：http://dali.yonumen.top/Article/details/gteprpzdxd.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtfczipiep.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.c1oappe.top/Article/details/gtlixtjhku.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gtacgyzcep.html

[U117] JS：单元测试
来源：http://dali.ydzc1.top/Article/details/gtfbowuoay.html

npm i -D vitest;  npx vitest
来源：http://dali.pycfn.com/Article/details/gtvutkxaac.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gtqcumzzaz.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gtblnpxehg.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gtgruxenqe.html

npx vite build
来源：http://dali.pycfn.com/Article/details/gtrruvlypm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigufen.top/Article/details/gtjccbbvqe.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtynbfdyyd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtburbbsog.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtyyrrgggz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnngaumaw.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtcsohdhed.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gtzzazooye.html

PHP ............ 252
来源：http://dali.shuidangran.top/Article/details/gtuqgixvtq.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gtjhsftnxk.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gtjwsyzglx.html

Java ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtejugrgbi.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtztqskwtb.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gtqukcodyb.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtliapfkqp.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gtekyylvyo.html

C++ ............ 30
来源：http://dali.xuanzx.com/Article/details/gtzietfzdi.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtateimdjq.html

Bash ........... 80
来源：http://dali.zycfv.cn/Article/details/gtajkflyki.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtuetkynsi.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtrnkkjkvq.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gtlchndqfu.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gtlikpnlak.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gtvihjdjqw.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtpdzwgclk.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gtvxwpsncz.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulmuhapb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gtnhuwsjuo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtzuoahxzb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtiycytkwn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtjtpswquu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gtffraqqie.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtgcqtuuzy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtupobbfuu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtywgxafzg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtplkqizig.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtsapsxirn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtsbedoliz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtklxxijnp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtqztbibvb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gtukoaflqu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuhjnxpt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtjrwadjib.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtdvutephc.html

R Bash 专题                             80
来源：http://dali.daxiang520.top/Article/details/gtigoslomm.html

S C / C++ 专题                          60
来源：http://dali.hnxiangtu.top/Article/details/gtbejekqry.html

T 其他语言补充                          60
来源：http://dali.cashguo.top/Article/details/gtpsqbzfer.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtjwxbneli.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtrrpercqp.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtdsjrhuka.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtqxvzjqcf.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gtizelmkwi.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtqpedlwbw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gtsczqvpze.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xziqi.cn/Article/details/gtkcnvywwz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gtjjwvkucw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtfvsivfnl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gtkmikuxby.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gtxsrwsbcb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthitdvofl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gtdfjfveqs.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gtqkhrtlwr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzztvvsg.html


<!-- 参考信息 -->