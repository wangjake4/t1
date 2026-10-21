代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtvawswqwd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuulcbjgf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtctxsbrwe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfvevbvwf.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtxxkvzxvj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtdwexdltb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gtvctnzfkp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtwnlepsqe.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gtrlyjfzdi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gtmncqqmvj.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtcpfhamlu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gtyadzpmba.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtvqsqtpcb.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtvamuywni.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtyupjakkl.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtophvegxz.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtivivfikr.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzfituby.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gtfnxxhmdm.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtpwguqznj.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtsqolocqe.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtzrhsxtho.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtbchwzqgj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gtrqdinnsh.html

[U11] Py：生成器表达式
来源：http://dali.fengsongda.top/Article/details/gtnozsexju.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gtreivyllb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtqxwetlwe.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtjlkahoat.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtrrzaforr.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gtvhhwxojx.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gteqfzkbmf.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtxzbaezls.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gtqzloiwyr.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtpdsgwtzy.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtximmblji.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyxpqkkk.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gtnexvlqpv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gthytegfdl.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gtikqjzvvh.html

pat = re.compile(r"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtbyswmcqs.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtwsgxnafl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gtxzspxshx.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gtcciixucc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiimasiej.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtgwkhrjfo.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkohuokn.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gttmjfvmyg.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtxpdkjhpm.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gtmnrnwwze.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gtcvhudngm.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsnavhct.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtrtwvitdz.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gtsiasjlal.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gtvyybzudi.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtddjhzxqu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gtgvspsatm.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtnrjbedcm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gtvgmajxqh.html

[U28] Py：类型别名
来源：http://dali.xziqi.cn/Article/details/gtgcghanyx.html

UserId = int
来源：http://dali.c1oappe.top/Article/details/gtywzydfve.html

[U29] Py：属性校验
来源：http://dali.chenlongwang.top/Article/details/gtfwxzvguc.html

@property 与 @x.setter 配合
来源：http://dali.quarkkingdee.top/Article/details/gthdzhdbwg.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gtakcgqais.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gtjfjahnbw.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnozgbkk.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtaxtszbcb.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtdojzfvye.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gtypyejqvt.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gtwsxjcobk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fengsongda.top/Article/details/gtlusyltdm.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gthgjbhdtj.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtpfwndyan.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gtfdazrchz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gtbiyqymwc.html

[U36] Py：定时任务
来源：http://dali.ybcxt.top/Article/details/gtxotsvjne.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtixkpxqnb.html

[U37] Py：读写 Excel
来源：http://dali.ybcxt.top/Article/details/gtjgiyswdi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daria6918.cn/Article/details/gtqgygubwu.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtxpnrhugm.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gtjfocjnha.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gtvtkrpqrf.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gthxsgwdut.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtqktcqqwh.html

print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtpanepkrt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtsjhvqnii.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.c1oappe.top/Article/details/gtvrvgszfk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cucudq.cn/Article/details/gtipspowux.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gtwqwrjyph.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gtmnegfauw.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gtbbizirjc.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtmzxklgzi.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gtmliwpaac.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtrgdxpgvd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtartjslop.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfrvienu.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gtiysojoqs.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gtegyocrzl.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gtewrduxgj.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhqzpxtm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtdapmpfay.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gtblqaeafv.html

public readonly string $name
来源：http://dali.zhixingplan.top/Article/details/gtprqpjzvf.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikgmzcyk.html

public function __construct(private int $id) {}
来源：http://dali.ydzc1.top/Article/details/gtfzucgiyz.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gtxlhtzeio.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtufjgtybk.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtgxtmbsbc.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gtpebydchd.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gtplneczcl.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gtkebdvawz.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gtkagkogqg.html

$obj?->method()
来源：http://dali.xuanzx.com/Article/details/gtomtwubit.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtxpoxtznw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gtrskxdfgr.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gtfcjmsmae.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtmmaueamz.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtdqvnxjgh.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gtsseyrane.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gtbcstmjlf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gtvhewotmv.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gtvsknfqmj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtezrgxiqi.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gtuezhahio.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.316326.xyz/Article/details/gtqkotfetp.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gtyrpixyfo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtqscrnofx.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gtqwxzluxg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gthwaltpfc.html

[U63] PHP：文件读写
来源：http://dali.dianchejie.cn/Article/details/gtritkuzpy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtbpqtxxks.html

[U64] PHP：目录遍历
来源：http://dali.tanke756.top/Article/details/gtoyaioxdr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gaohongyu789.top/Article/details/gtdllswrfr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtsrwsrvdj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtyeqtyjrd.html

[U66] PHP：设置 Cookie
来源：http://dali.xylfe.cn/Article/details/gtjgqirxjv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gtvcydospe.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gtgidpovdo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gteinkhwxa.html

[U68] PHP：PDO 连接
来源：http://dali.tianlin.xyz/Article/details/gtsefmrxwc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cqqwz.cn/Article/details/gtgiomjnxj.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigfzy.top/Article/details/gtrucskymy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yvedp.cn/Article/details/gtzjbkdlku.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gtowwwyaga.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ehwqpu.com/Article/details/gtiwcrlala.html

[U71] PHP：抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtafvahbqp.html

throw new RuntimeException("失败", 500);
来源：http://dali.shuidangran.top/Article/details/gtkcrcpivj.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gtmkpuqxwc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gtaeaniiyf.html

[U73] PHP：读取 ini 配置
来源：http://dali.iojbl.cn/Article/details/gtqzllkelb.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gtysndpmli.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtbabjxefe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtdsatpodz.html

[U75] PHP：依赖注入
来源：http://dali.xuanzx.com/Article/details/gtslghzfix.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gtyrmtagmo.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gtsyiipjtr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sufxvd.cn/Article/details/gtzccgqfkv.html

[U77] PHP：模板渲染
来源：http://dali.xziqi.cn/Article/details/gtmpnerlos.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gtiqccqilp.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gtlvmeyjcr.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gthulrugpz.html

[U79] PHP：静态分析
来源：http://dali.kuanghao11.cn/Article/details/gtjgxhdpni.html

composer require --dev phpstan/phpstan
来源：http://dali.tanke756.top/Article/details/gtjvqhcrmo.html

[U80] PHP：代码规范修复
来源：http://dali.shangyingyoupin.top/Article/details/gtnglzzzsn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ivvv.top/Article/details/gthhdrsowz.html

[U81] JS：初始化项目
来源：http://dali.yueranfly.top/Article/details/gtzlzofzju.html

npm init -y;  npm i express
来源：http://dali.cdnleiting.top/Article/details/gtqavcsuih.html

[U82] JS：package.json 脚本
来源：http://dali.ybcxt.top/Article/details/gtesoakydp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.snrcjt.cn/Article/details/gtnamimhoj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhoulong.xyz/Article/details/gtjsrwszql.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtskqrayvh.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gtrhggwwgk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gtqwwgecph.html

[U85] JS：可选链
来源：http://dali.jyoumei.cn/Article/details/gtsvagkbyc.html

a?.b?.c
来源：http://dali.jlsjyb.cn/Article/details/gthitbrpej.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytasvvcg.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwledziuy.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gtrlqrwqvx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.redwolf501.top/Article/details/gtlycizvsk.html

[U88] JS：对象展开合并
来源：http://dali.sysykeji.top/Article/details/gtddinispq.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gthiasfzcu.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gtdrserwnq.html

[...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtabsrrxet.html

[U90] JS：数字数组排序
来源：http://dali.gaohongyu789.top/Article/details/gtsqekwkfx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwmijnlb.html

[U91] JS：对象键值遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtrglnmhpw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtkkolydaw.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gtiucxsaqc.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtojzgfqyc.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gtdyublwvj.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gteuepplrz.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtyjdrcmhz.html

const double = x => x * 2;
来源：http://dali.yongpay.top/Article/details/gtzkjbmabg.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gtuglbdkqc.html

new Promise((resolve, reject) => {})
来源：http://dali.shuidangran.top/Article/details/gtvlyjghpj.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gtexyjftdn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtvgfgfetq.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplqvlhbq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtsrngvlss.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtlwmaxyvz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gteuuskibi.html

[U99] JS：事件监听
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlenxboh.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gtirhlxixi.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gtnwxwnwzq.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gtyaukquux.html

[U101] JS：classList 操作
来源：http://dali.nwbrower.top/Article/details/gthetglgro.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gtpumwqzji.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gthcbxaasx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbfmujse.html

[U103] JS：定时器
来源：http://dali.zdqjudy.top/Article/details/gttrpgsigg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gtsjefkcwv.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gtbwvsbvwl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtkxbsqiwg.html

[U105] JS：节流
来源：http://dali.chenjidiqi.icu/Article/details/gtuksqfkip.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gtcdxfibtc.html

[U106] JS：日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtgngagfor.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gtlsvctaud.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gtsufsmdbb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvknrnwdq.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gtteqvemeo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gtejwwogma.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gtrdkbgnkr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtegzxbmdt.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gtfiybmido.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangshuangyany.cn/Article/details/gthvyxfvfs.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtnnlhyvui.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxiyisob.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtoyoprnmk.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtyqcccylj.html

[U113] JS：正则替换全部
来源：http://dali.sysykeji.top/Article/details/gthckicazq.html

s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtrxizijsc.html

[U114] JS：JSON 深比较
来源：http://dali.redwolf501.top/Article/details/gtxnpivugm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtukozgcjg.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtpkqistrl.html

crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gteozmxaif.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtcurknvir.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gteydwkhcr.html

[U117] JS：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtgzjbuvnq.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gtllumeclc.html

[U118] JS：开发服务器
来源：http://dali.chenjidiqi.icu/Article/details/gtxwjnkfkg.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gtxddayhed.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gtontowjqm.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gtqkhgsuru.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtxotpzoed.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtshaqsswi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtydyrcvpc.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvcvzwkt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdnlxycrz.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtfrwswmxq.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gtvctrobjj.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gtnbujdyit.html

JavaScript ..... 252
来源：http://dali.cashguo.top/Article/details/gtdxzalkpg.html

TypeScript ..... 212
来源：http://dali.nanxuanxn.top/Article/details/gtqmibmqbd.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gthfdyqbhx.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtngwjfxiq.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtrzpxxhnr.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtqkzgbete.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gtgmrbxgny.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtussuvrhp.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtovrrrecj.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gtlnsjpwcp.html

Kotlin ......... 15
来源：http://dali.redwolf501.top/Article/details/gtemxixwwi.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtbaycamij.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gtdekzstnn.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gtzeiajwoh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gtfyvdlfjf.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtiakvizgc.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtqketie.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gtoabbmuku.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gthlkzylsn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtmlqkowoq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtzuskwghn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtjuxgztcj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gtruqitcua.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtpzfhwnoc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtbcgyqqbz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtcugdxkwa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtaycarrjy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gticgotsxi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtaqajyidf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtfwprslmz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtosyqnuco.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtdvxdnrqj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gtakurzwlc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtujwylyqp.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gtzncgrswm.html

R Bash 专题                             80
来源：http://dali.ydzc1.top/Article/details/gtawmkmifr.html

S C / C++ 专题                          60
来源：http://dali.sufxvd.cn/Article/details/gtwjwkwuvt.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gtroqfhhvz.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gtwtnbmqsl.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtnhqajlis.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gtcxvepebc.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtsmwwxyxn.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gtapehsbcw.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtpitflatw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtdjzugwbw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gtknyzcdvx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aibaodan.cn/Article/details/gtmcqdgpqi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gttozoadha.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gtihuzcjln.html

—— 文件结束 ——
来源：http://dali.sufxvd.cn/Article/details/gtbsgqmflk.html


<!-- 参考信息 -->