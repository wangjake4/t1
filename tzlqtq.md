代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtjndpfwnu.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvtqspsp.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gticyrurhd.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gtvdbxxvtn.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gtioklcuqw.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtiuthvqmu.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gtgoflxmns.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gtvnqxmvrj.html

[U11] Py：生成器表达式
来源：http://dali.316326.xyz/Article/details/gtktnpcach.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtkazlnvaz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtmbvoeart.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gtupzdwntu.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gthzkznakg.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtsyzgfpjo.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gttbsakvcj.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gttahlgdzm.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtotuuwtux.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gtubifqdbe.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gtvzqbjldu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gthsxzspxk.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gturzzrgof.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gthmlrapzp.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gtebxipkjw.html

pat = re.compile(r"\d+")
来源：http://dali.yj202588.top/Article/details/gtspsgdndo.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gtumesoggw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnqzz.top/Article/details/gtavdlylax.html

[U20] Py：缓存函数结果
来源：http://dali.zhongyouzk.top/Article/details/gthzwrnlwd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtqevuhwop.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gtdjmviynr.html

@contextlib.contextmanager
来源：http://dali.zhoulong.xyz/Article/details/gtkirsjyif.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtzekrzvpz.html

list(zip(*m))
来源：http://dali.pengpengdd.cyou/Article/details/gtqhftfyep.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtychxburs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gtlyhkhdyz.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtueqxckco.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtmsyvfygr.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtrtzsufsm.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gtbawreght.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtkgfyraxh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gttfazvkdw.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtzhprwygb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gtqqqaqckr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gtakkhrcdl.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gtmgleinfk.html

[U29] Py：属性校验
来源：http://dali.birdmap.top/Article/details/gtuxtrcmoc.html

@property 与 @x.setter 配合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubevucrv.html

[U30] Py：数据类
来源：http://dali.cucudq.cn/Article/details/gtjiaxrjxr.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtononvujk.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gtrugkiihy.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gthenuxvxe.html

[U32] Py：代码格式化
来源：http://dali.zhengqikj.top/Article/details/gtcpdgojrz.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtwwnwfqba.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtsebefkdo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuxming.cn/Article/details/gtptnneyhc.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gtjzrikeen.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdaailyo.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gtxgozlumc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ppjwa.cn/Article/details/gtronjvcld.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gtshoepvty.html

schedule.every(10).minutes.do(job)
来源：http://dali.pycfn.com/Article/details/gtvgddunsq.html

[U37] Py：读写 Excel
来源：http://dali.hammf.cn/Article/details/gtxnfzriie.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258888.top/Article/details/gtzzkdnfge.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gtxpeewqen.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtanwwqilq.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gttezdenjv.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gtbodfxukm.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtptjybvar.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtpovcdmqz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtiljhcmeo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gtkjapnzzd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtpgqywqkq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gtpvpjzngy.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtngpahqop.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gtinzfydom.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gtkkwpuocn.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtfzgubmba.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aizwys.cn/Article/details/gtkdtqjbej.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtuzzqlzxp.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gtvwiwkhfz.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gtvrugpuet.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gtiqudeeeh.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gtieiglfxj.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gtjvqavvhx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shuidangran.top/Article/details/gtpkrpucvx.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtshlxmcbm.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtzexjiatv.html

[U50] PHP：构造器属性提升
来源：http://dali.svipenyu.cn/Article/details/gtnysoqzir.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtykykapiu.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gtjnqjswht.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtjucant.html

[U52] PHP：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtzrxumhoj.html

$double = fn($x) => $x * 2;
来源：http://dali.quarkkingdee.top/Article/details/gtrweyrhfj.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gtcgindemd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpokfxxsf.html

[U54] PHP：空安全调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeenotbh.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gtibfyovgq.html

[U55] PHP：match 表达式
来源：http://dali.chenzaomai.com/Article/details/gtenwwopcm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtovabnjlu.html

[U56] PHP：命名参数
来源：http://dali.jqgfzy.top/Article/details/gtbgorgoxi.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtzxbezeam.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtkgkitbyp.html

"值: {$a}"
来源：http://dali.sweek.top/Article/details/gtqscnkfyw.html

[U58] PHP：数组三件套
来源：http://dali.sxryk.cn/Article/details/gtkwkluqpd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gtzmxtbrwf.html

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gtctrnmejl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtrhtcgagw.html

[U60] PHP：JSON 编解码
来源：http://dali.vqdsnc.cn/Article/details/gtwbxxzwvg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.redwolf501.top/Article/details/gtlhqqfrhm.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gtbemhkqhb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtclookhvb.html

[U62] PHP：日期对象
来源：http://dali.mhx1999.top/Article/details/gteltyaggu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gtzphmaopc.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gtacqgekip.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gtghmopzuk.html

[U64] PHP：目录遍历
来源：http://dali.sufxvd.cn/Article/details/gtkquflqls.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtgtvetznn.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gtiohuumya.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtfuycfvjy.html

[U66] PHP：设置 Cookie
来源：http://dali.9152youxi.cn/Article/details/gtfwertssv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gtdstwgzqh.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gtwadctfvz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gtcmilmttr.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtbvgduaoq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gtvtghhyjm.html

[U69] PHP：PDO 预处理
来源：http://dali.aizwys.cn/Article/details/gtwlnzzxly.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.smart0.xyz/Article/details/gtkpmgoapc.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gtgsodbybi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtufmlyxuh.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdspkvzb.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtgccxowso.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gtfkglwplx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgfzy.top/Article/details/gtdlipkzyr.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtexqceexa.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gtitwcqkwb.html

[U74] PHP：读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtxcafiyej.html

getenv("APP_ENV") ?: "production"
来源：http://dali.9152youxi.cn/Article/details/gtjzxsqljx.html

[U75] PHP：依赖注入
来源：http://dali.yongpay.top/Article/details/gtrxovuhwj.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtqymmcwxn.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gtgubanyxh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dashuyun.cn/Article/details/gtdrwbygja.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gthuivezoa.html

composer require twig/twig
来源：http://dali.316326.xyz/Article/details/gtbszysscu.html

[U78] PHP：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gthnvxavsf.html

composer require --dev phpunit/phpunit
来源：http://dali.9152youxi.cn/Article/details/gtmhtqvrqy.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gtnnnzuumu.html

composer require --dev phpstan/phpstan
来源：http://dali.yj202588.top/Article/details/gtwvkbnnes.html

[U80] PHP：代码规范修复
来源：http://dali.daxiang520.top/Article/details/gtuujjdzhk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gtwapguyei.html

[U81] JS：初始化项目
来源：http://dali.0kj1m.cn/Article/details/gtlllblywj.html

npm init -y;  npm i express
来源：http://dali.zhoulong.xyz/Article/details/gtaqsmjiuj.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtwoqzwium.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.feifeiyinyue.top/Article/details/gtsyhmhtmz.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzodwuuty.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtonavgtis.html

[U84] JS：CommonJS 写法
来源：http://dali.xziqi.cn/Article/details/gtxgzieimx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yongpay.top/Article/details/gtdenhxzkn.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gtjvknvndl.html

a?.b?.c
来源：http://dali.gotoacloud.top/Article/details/gtlxvxtmne.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gtgvdwtphq.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gtvwjpolso.html

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtdmzzdeud.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jlsjyb.cn/Article/details/gtjxbkconp.html

[U88] JS：对象展开合并
来源：http://dali.xinyue.icu/Article/details/gtiftmnmku.html

{ ...a, ...b }
来源：http://dali.jlsjyb.cn/Article/details/gtdduksehp.html

[U89] JS：数组去重
来源：http://dali.cdnleiting.top/Article/details/gtogrxildg.html

[...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtywiwvtsv.html

[U90] JS：数字数组排序
来源：http://dali.chenlongwang.top/Article/details/gtymorxleb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtdmhdhoto.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gtxwcmadpu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hfpthk.cn/Article/details/gttbfhlsql.html

[U92] JS：深拷贝
来源：http://dali.yj20258.top/Article/details/gtqportdwo.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbbvmwwty.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gtcdprogyr.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gtanlyklgy.html

[U94] JS：箭头函数
来源：http://dali.sweek.top/Article/details/gteockwwua.html

const double = x => x * 2;
来源：http://dali.ybcxt.top/Article/details/gtawkorxan.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gtoqnwkslb.html

new Promise((resolve, reject) => {})
来源：http://dali.sxryk.cn/Article/details/gttjpbdqyd.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gtefpiudxe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtpvmkmyex.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtbqcjzfwl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtrsnhayap.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwhfsdsb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtmwvtzqmu.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gtoifsrmdr.html

el.addEventListener("click", e => {})
来源：http://dali.xuanzx.com/Article/details/gttohvvqsf.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gtmysoqxor.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gthyhvspex.html

[U101] JS：classList 操作
来源：http://dali.yj202588.top/Article/details/gtjjuqjlgm.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gtlbabzogr.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtcoqwfeop.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gtpuqjrvtk.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gtwokhftnw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtnkfjogsc.html

[U104] JS：防抖
来源：http://dali.snrcjt.cn/Article/details/gteouwenou.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtoaikkxoj.html

[U105] JS：节流
来源：http://dali.jiagoushi.top/Article/details/gtfrpztiuk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcnkpbbg.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gtcuigukwu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtnfxnhncs.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtaebjsbkw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtzstkstop.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gtjfhxvihi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuanzhike.top/Article/details/gtudsfkrwd.html

[U109] JS：数组分组
来源：http://dali.xinyue.icu/Article/details/gtpyawbpal.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtcmigcdkf.html

[U110] JS：数组分块
来源：http://dali.hywenlv.cn/Article/details/gtnvprewdk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxinkj.top/Article/details/gtnnhhwcps.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gtpvlaojaj.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gtaygouaqy.html

[U112] JS：字符串补位
来源：http://dali.shangyingyoupin.top/Article/details/gtyrauzxvj.html

"7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtbhlbpxzd.html

[U113] JS：正则替换全部
来源：http://dali.hnqzz.top/Article/details/gtmtrncaec.html

s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtnndmzkge.html

[U114] JS：JSON 深比较
来源：http://dali.feifeiyinyue.top/Article/details/gtjvktrfzn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtrtxgszee.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtuekkbanu.html

crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtxdiimeol.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gtqtuaizvh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtldujpozd.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtyszmbmjv.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gtysmzygsg.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gttwgtwfif.html

npm i -D vite;  npx vite
来源：http://dali.aizwys.cn/Article/details/gtzhfmanmj.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gtaenpffdq.html

npx vite build
来源：http://dali.tian-w.cn/Article/details/gtpiewoqxv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gtquirwicd.html

import.meta.env.VITE_API_URL
来源：http://dali.yanxiufei.cn/Article/details/gtdlkdtcxo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtunmkkyzl.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gthikmxkqt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzjwcuvsc.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtxnzdygcg.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gttpfwofqy.html

PHP ............ 252
来源：http://dali.tianlin.xyz/Article/details/gtvcqxvesu.html

JavaScript ..... 252
来源：http://dali.yj20258.top/Article/details/gtdyoowood.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtiqprymhd.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gtlhsiuspn.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtxvwmgiir.html

Ruby ........... 212
来源：http://dali.fzhhl.top/Article/details/gtzbweciqw.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtdwyhnqwo.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gtqjtkjtpp.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gtqasgdyfq.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gtqtnrehpw.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gtkunprrgd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtyluelmve.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtbtsevyej.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gthtlqkgws.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gtpwduwaiu.html

Scala .......... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbkdnset.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtyzuamfrx.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gtgkxgxlky.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtkuivlwmb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gtpkgbhzub.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtyxjgdwqa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtnqdimptv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtcngnzpiq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ppjwa.cn/Article/details/gttpwdsdyn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtunhayecg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtnldhytoc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtmgvsticg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gthjbiwell.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtgjonrpdf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtcvljyqsl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtwwpnogky.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnyjlphh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gtamtjgmit.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.iojbl.cn/Article/details/gtlesnzvfc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtpednozvp.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gtscglgnra.html

R Bash 专题                             80
来源：http://dali.jiagoushi.top/Article/details/gtqifeeamq.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtjjlqzwpg.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtognfrytq.html

U 高频实用片段                         120
来源：http://dali.hammf.cn/Article/details/gtocsjeyle.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtzxkxiioe.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gtahvjmxgz.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtbdyaamrx.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gteotjpfrv.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtbgwlsfqk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gttzrgjttf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gtavskklce.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydcvdmuj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.redwolf501.top/Article/details/gtfolfjbpg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ehwqpu.com/Article/details/gtvkjmiksa.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gttvjmmytu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgjrlknew.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenlongwang.top/Article/details/gtaiewfwyw.html

Common Programming Examples Cheat Book
来源：http://dali.cucudq.cn/Article/details/gtvnluniqb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtidzyatcv.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gtewllojeh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gotoacloud.top/Article/details/gtcqcztehp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daria6918.cn/Article/details/gtisghrgwc.html

SQL · Bash · C · C++
来源：http://dali.zycfv.cn/Article/details/gtferohbhp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gtpypmosjn.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gtwnofvqtm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtbdtxpzrj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cashguo.top/Article/details/gtuaegzmut.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guannengcc.top/Article/details/gttodnlqqm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cheryme.top/Article/details/gtwwxnptzm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gtzwabydct.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gtetuuzxru.html


<!-- 参考信息 -->