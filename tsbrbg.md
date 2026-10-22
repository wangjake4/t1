代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gt2nventbgz.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2bwnpllya.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gt2jemxenci.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlzgpole.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2hmrbcdqj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2batpakja.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2twfxmnjl.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gt2mybomarr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gt2xboqbndq.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gt2zqvxwcwo.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gt2qmlcwyqd.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gt2nbjmupmb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gt2yojkhnsm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppxzidia.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gt2upxbvsyh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2jtpfxqxm.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2mfcyxdao.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gt2bstoekkz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gt2nonhiyes.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tanke756.top/Article/details/gt2lmpntlko.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gt2ddpdakzw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msnrvblh.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajbulzjt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptppewnl.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gt2gwrfmjot.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2kkakxtkt.html

[U06] Py：合并两个字典
来源：http://dali.hnxiangtu.top/Article/details/gt2jflihxpd.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnqsaefv.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztewzjwj.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gt2sbrrybxe.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gt2liqysdzz.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gt2dxkjazko.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gt2kjhleovt.html

max(d, key=d.get)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymxbyekn.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gt2vgawvwun.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2yumwxitb.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gt2ipmxjslt.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gt2yovssuyk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gt2nwpmsgyk.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gt2qukvgnus.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkarqcrw.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gt2pxwjiskl.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gt2jimgeeel.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gt2qnmtipvs.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdjxaoht.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gt2blefroon.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gt2hdwpehgd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gt2clqqkjxc.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gt2fpzdjeop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gt2kbwfcfsw.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gt2bsmbpyef.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2vuairdzy.html

[U19] Py：正则替换带回调
来源：http://dali.haohaochexian.top/Article/details/gt2hmfppbiz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.snrcjt.cn/Article/details/gt2kqcnmwux.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gt2hnnsnvha.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gt2wrdcntcx.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gt2tpnerspg.html

@contextlib.contextmanager
来源：http://dali.svipenyu.cn/Article/details/gt2ppyqxtpv.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gt2zmhcqgec.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvaiyeud.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2onwosjko.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvmbfgmi.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhibrakk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2vldnybuy.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxqsrdzf.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gt2vzfhfowc.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gt2cmheejte.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gt2uhehblqz.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gt2ezqrgazt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gt2zjdofyhd.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gt2rhqahjis.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gt2jafqxepq.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gt2qqzqnqfy.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gt2encuxdmg.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gt2pcoekytz.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2fhspgpfn.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gt2ajpjimtl.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gt2jtspmwxu.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gt2mfvzkgpx.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gt2cmhvwpco.html

[U33] Py：打包发布
来源：http://dali.guannengcc.top/Article/details/gt2teejxfdi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gt2pzarsdlo.html

[U34] Py：判断编码
来源：http://dali.redwolf501.top/Article/details/gt2qeghrbpi.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gt2ssjtikon.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gt2rnumkdql.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gogol.net.cn/Article/details/gt2xhhmobyd.html

[U36] Py：定时任务
来源：http://dali.sysykeji.top/Article/details/gt2shhqakpj.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gt2ftxuwdmh.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gt2xnagzdaq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2uxndbqot.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrgchub.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gt2pljpuolt.html

[U39] Py：判断是否在交互环境
来源：http://dali.0kj1m.cn/Article/details/gt2gbcpvmar.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gt2jzqeiylg.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmwzkwcc.html

print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gt2zuhaovut.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2yxadsyye.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gt2bjsbocxz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gt2qjszshgr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvcfleg.html

[U43] PHP：声明命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2idynrghw.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gt2vjjqibme.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gt2nnvyurlb.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gt2bziasgba.html

[U45] PHP：类型声明与返回类型
来源：http://dali.bjfxy.top/Article/details/gt2xhknohsx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2bptkjpro.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjqoelcy.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gt2aflttxyw.html

[U47] PHP：联合类型
来源：http://dali.sufxvd.cn/Article/details/gt2ucwvvibl.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gt2dwlxelrp.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2ixraqunr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gt2bddsywhb.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gt2qdaeywob.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gt2npveahih.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gt2trpmeyoy.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gt2lzziwtgf.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gt2fhpbzwxt.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyxbvvei.html

[U52] PHP：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gt2vzlpiyzm.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tikdrgqv.html

[U53] PHP：空合并运算符
来源：http://dali.mhx1999.top/Article/details/gt2aphkykmb.html

$v = $a ?? $b ?? "default";
来源：http://dali.nwbrower.top/Article/details/gt2yzzcvsuu.html

[U54] PHP：空安全调用
来源：http://dali.cheryme.top/Article/details/gt2tzfnkdkj.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gt2kzgbyncl.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gt2frdarycx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gt2sonrvyjd.html

[U56] PHP：命名参数
来源：http://dali.havefunace.top/Article/details/gt2oyrgqnsk.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2atxtykfw.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlsnsmmn.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gt2incyviuh.html

[U58] PHP：数组三件套
来源：http://dali.hammf.cn/Article/details/gt2hatupzak.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2mwvcdyui.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gt2dxovjnhi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qarqfyje.html

[U60] PHP：JSON 编解码
来源：http://dali.shzxlz.cn/Article/details/gt2reqszhez.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.c1oappe.top/Article/details/gt2xzafybno.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gt2waabohyg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2xvsxfsmp.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdodxxxq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gt2lyubblcj.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gt2jgvlekcn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbmczclc.html

[U64] PHP：目录遍历
来源：http://dali.zhixingplan.top/Article/details/gt2bvrjjthz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gt2wumnwdld.html

[U65] PHP：会话
来源：http://dali.ybcxt.top/Article/details/gt2udcukyvg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2ndpdydah.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gt2ymqywgts.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gt2muwsnhuh.html

[U67] PHP：处理文件上传
来源：http://dali.xziqi.cn/Article/details/gt2bgykbenr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgfzy.top/Article/details/gt2bypuidkz.html

[U68] PHP：PDO 连接
来源：http://dali.wangdashe.top/Article/details/gt2cffvmtlx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gt2cibojsnt.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abpcaqxo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cdnleiting.top/Article/details/gt2ouaowxln.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gt2oyzjccpy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gt2dflpaczy.html

[U71] PHP：抛出异常
来源：http://dali.316326.xyz/Article/details/gt2evzheexe.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2fsomhqkh.html

[U72] PHP：写错误日志
来源：http://dali.hnxiangtu.top/Article/details/gt2vihmlidj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owgddyeg.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gt2nfzyamtm.html

parse_ini_file("config.ini", true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkebeexv.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2hxwgiiub.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xziqi.cn/Article/details/gt2rfqnznba.html

[U75] PHP：依赖注入
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpdnezhv.html

composer require psr/container
来源：http://dali.dianchejie.cn/Article/details/gt2syvpglax.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gt2zetpfisz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfhgsivh.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gt2xsoybvab.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gt2hrkvusts.html

[U78] PHP：单元测试
来源：http://dali.ehwqpu.com/Article/details/gt2ngrgqvdw.html

composer require --dev phpunit/phpunit
来源：http://dali.ybcxt.top/Article/details/gt2yxcdgnce.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gt2zpbftpbp.html

composer require --dev phpstan/phpstan
来源：http://dali.tian-w.cn/Article/details/gt2muampzri.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gt2voakbwpv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bliosrsk.html

[U81] JS：初始化项目
来源：http://dali.yj20258888.top/Article/details/gt2ovvauiru.html

npm init -y;  npm i express
来源：http://dali.havefunace.top/Article/details/gt2kdkzjydj.html

[U82] JS：package.json 脚本
来源：http://dali.nwbrower.top/Article/details/gt2prgjkcix.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gt2uuavcspt.html

[U83] JS：ES Module 导入导出
来源：http://dali.andypj.xyz/Article/details/gt2hjrpqdig.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2wmbcfgrl.html

[U84] JS：CommonJS 写法
来源：http://dali.meibo888.top/Article/details/gt2olfqnfwq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gt2nssuudfi.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gt2ordzqnxi.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgwlkbdr.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gt2zjjegwmh.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gt2idbxkuvp.html

[U87] JS：解构默认值
来源：http://dali.daxiang520.top/Article/details/gt2qyjrdaur.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yonumen.top/Article/details/gt2cafysshh.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gt2vwupnizd.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gt2rdofbcdz.html

[U89] JS：数组去重
来源：http://dali.sysykeji.top/Article/details/gt2gewaqfgi.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2yhgktgde.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gt2ggsrfciv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2qigkblqa.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gt2uamvkbge.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhengqikj.top/Article/details/gt2rkrkdaas.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gt2ktbkbxwc.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2xwqmduwz.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gt2vtzgsval.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paxzownd.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gt2nuklgmra.html

const double = x => x * 2;
来源：http://dali.hfpthk.cn/Article/details/gt2eloluknz.html

[U95] JS：Promise 包装
来源：http://dali.c1oappe.top/Article/details/gt2gfqfgqwh.html

new Promise((resolve, reject) => {})
来源：http://dali.zycfv.cn/Article/details/gt2njkdyuwr.html

[U96] JS：async/await 与异常
来源：http://dali.hnqzz.top/Article/details/gt2wrbgffxb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2ypkhdima.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpcbvktb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsnechua.html

[U98] JS：fetch 带 JSON
来源：http://dali.smart0.xyz/Article/details/gt2jkqjlcar.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gt2jzbooaaw.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gt2wzoonirm.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gt2rosinaqj.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gt2illsxrhm.html

document.querySelector(".item")
来源：http://dali.andypj.xyz/Article/details/gt2mkgneopz.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gt2deltrmrl.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gt2dhwotwlo.html

[U102] JS：本地存储
来源：http://dali.gaohongyu789.top/Article/details/gt2lerqnzyd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gt2pllhiyml.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gt2rprvrbzw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gt2evhqfdgk.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gt2emophjpx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2dwacetuv.html

[U105] JS：节流
来源：http://dali.cucudq.cn/Article/details/gt2etqthcon.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gt2qshjvohm.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2gahpqyce.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gt2ljmkzzwa.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gt2hjrtsasd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gt2wxtlgudc.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gt2hucbevkd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gt2twhonqqh.html

[U109] JS：数组分组
来源：http://dali.mhx1999.top/Article/details/gt2smbjryqq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2krizozjz.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gt2cmdprjou.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gt2evwrwkwx.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhwktllm.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gt2zfsbsjxg.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gt2qnlmptdw.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2humajura.html

[U113] JS：正则替换全部
来源：http://dali.nwbrower.top/Article/details/gt2cklfoivg.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2dmyjfzmj.html

[U114] JS：JSON 深比较
来源：http://dali.hywenlv.cn/Article/details/gt2yacyshcl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gt2gmfvuvsu.html

[U115] JS：生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2cvdkmlku.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2pwiphgfn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gt2opnbczor.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fengsongda.top/Article/details/gt2zngzbpci.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gt2ysfzdyxq.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gt2nsqkemve.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gt2dcmtdedm.html

npm i -D vite;  npx vite
来源：http://dali.ivvv.top/Article/details/gt2ssnvdbvj.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gt2rkoavkvc.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdduarnd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gt2dtscfngs.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gt2vomqlidd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ttnelaly.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gt2caacmxxd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2iafdqywf.html

按语言统计（条）：
来源：http://dali.shuidangran.top/Article/details/gt2wvjjofbn.html

Python ......... 252
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmstrjyx.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdgwuzvk.html

JavaScript ..... 252
来源：http://dali.jianghu66.top/Article/details/gt2eanvaeup.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gt2erehfvvw.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gt2qarvkokp.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gt2dlwhrmfo.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gt2cgnajecr.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gt2emkqtvks.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gt2uxlyklan.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gt2sqhmzwmv.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnagtttz.html

Bash ........... 80
来源：http://dali.zdqjudy.top/Article/details/gt2ypaismmw.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gt2xaxfiiaf.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gt2rxrnlgpu.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gt2qeymwwvq.html

Perl ........... 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwfjzcnh.html

Scala .......... 10
来源：http://dali.zhongyouzk.top/Article/details/gt2wrygqiug.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2zjuzaneo.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gt2mpsqjvym.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gt2bqtuhugd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gt2wmtsrimi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gt2hlvdhzhz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2jfwfjimy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gt2yenfacxl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gt2jtqfbajw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gt2lzfsaujm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnrerkgr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2crupxrfl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2dzgnwlpf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gt2zyxzxwjk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2ocukwdfh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2eckrtoso.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2hyhkfstp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2ltbsryzi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxyhohkq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2wkhyguzf.html

Q SQL 专题                              90
来源：http://dali.xinyue.icu/Article/details/gt2mjlyuqsx.html

R Bash 专题                             80
来源：http://dali.hnqzz.top/Article/details/gt2oodsqbju.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gt2vgibmwqf.html

T 其他语言补充                          60
来源：http://dali.gotoacloud.top/Article/details/gt2scgzacca.html


<!-- 参考信息 -->