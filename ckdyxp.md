代发 wailian999

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtmumwlsxx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtuzlajosw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtpclmlrli.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtqtzenvfj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gtkbgsfnyk.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtzbpxasoz.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtvphtsqkr.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtezgplhmm.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtijvlxaki.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtxztarmxo.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtittdcteg.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtdrcoqren.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtmzadjlli.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtwzyixnqj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtadtpvkfm.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtynymtcgo.html

case class User(name: String, age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusxoeiip.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxjlaqwu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtuqfjqttw.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gtcjidjqps.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gtpnqhyxbk.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtiwqhsazr.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtjwptdjpj.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gtplshazmk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gtdzaarfyg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyswznapu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkcnjomm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcitvzqmz.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gtwcokioiu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.svipenyu.cn/Article/details/gteqavgnov.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtawyrdeph.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtufjrrfjj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtnwpgkwgj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtoilkeovm.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtblhdhqyc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtwlucwzdt.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gtdyhutmku.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtrcvplumg.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtrjdyidlo.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtzqihlfub.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtfghjpgmz.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkbjhtsv.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyljgmsa.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gtwcksonrq.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gtywsqolzl.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtvxjnzhkc.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gthzpjjgcz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtbpqaxvmx.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtzshduqco.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gttuiktncf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtclnznpqh.html

Counter(arr).most_common(3)
来源：http://dali.yangfankeji.com/Article/details/gtvvgpscga.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gtamwpoawx.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtazblpeic.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtewdslynr.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtjhonilqu.html

[U15] Py：高精度计时
来源：http://dali.tian-w.cn/Article/details/gttxadjmac.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gtkxtkwiqc.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtryexwyvl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtryupebxg.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gtyskrwayz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gtscewvbuv.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gtbxargnhi.html

pat = re.compile(r"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtbcrrgqvv.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gtppgjmzdi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtneuxoenn.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtflhnkcgc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtchifsqeg.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gtyrvrqbsu.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtdnlckssn.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gtsdozrmjs.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtpwjhdulh.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtbdhzuxhq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gtheaoeogu.html

[U24] Py：路径操作
来源：http://dali.hnxiangtu.top/Article/details/gtquuyefak.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtgfnfpden.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtdsogkibh.html

csv.DictReader(f)
来源：http://dali.zdqjudy.top/Article/details/gtlwljxwht.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtvhmkkrvz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gtutrlmtge.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtivmgshtv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtliaqciqt.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtmorhmfsu.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtdiajmeun.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gttpsyhsti.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gtxrwpiwcv.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gtgdxuqbma.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtsiwqgdkk.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gtyjwrvyun.html

python -m pytest -q
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhvkxpzt.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gtiabtukbm.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gtgxyrkbxh.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtdqvkxoxj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gtvyztehvr.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbafhiyz.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gtwyxchybc.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtbtquxxhg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtqggdbdjn.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gtnizssgxy.html

schedule.every(10).minutes.do(job)
来源：http://dali.birdmap.top/Article/details/gtaqbfdfou.html

[U37] Py：读写 Excel
来源：http://dali.fengsongda.top/Article/details/gtqmeujhtu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gtdfqvbcdr.html

[U38] Py：获取脚本所在目录
来源：http://dali.ydzc1.top/Article/details/gthwplober.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtortshwbb.html

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gtftygzrwo.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gtrdbkojcq.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtiubdznzm.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtuovqutog.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gttqjldvrp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtpoxulukm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gtlnslphpv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtkbendswl.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtyykxqfio.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtujflajaj.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtmijfbgww.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gtjgxbjfea.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtfphicyef.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtmxfsakly.html

[U46] PHP：可空类型
来源：http://dali.shzxlz.cn/Article/details/gtqtpuzgza.html

?string $name = null
来源：http://dali.ppjwa.cn/Article/details/gtbtdeeufu.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gtnwlkvzim.html

int|string $id
来源：http://dali.zhiwuduotai.top/Article/details/gtryagkgig.html

[U48] PHP：纯枚举
来源：http://dali.zycfv.cn/Article/details/gtkjjubtgd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gthkqiqqyu.html

[U49] PHP：只读属性
来源：http://dali.yj202588.top/Article/details/gtgwspsswh.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gthympteso.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gtzvprypir.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gtspeferet.html

[U51] PHP：数组解构
来源：http://dali.hywenlv.cn/Article/details/gtiydfuymw.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gtrfacsaxy.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gteojlefcl.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gteeyrbjgu.html

[U53] PHP：空合并运算符
来源：http://dali.xuetiantiany.cn/Article/details/gtvmyhvnhn.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gtrjpohiag.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gtrheemkzu.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gtauxtoahb.html

[U55] PHP：match 表达式
来源：http://dali.c1oappe.top/Article/details/gtuljqxric.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtmkenpdgx.html

[U56] PHP：命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtvrsmronq.html

f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtoqsbkgrg.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtypnqygsr.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gtwucrbktn.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgtukccq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gtykrgjqis.html

[U59] PHP：自定义排序
来源：http://dali.cqqwz.cn/Article/details/gtoajelsxr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gttwrdplvv.html

[U60] PHP：JSON 编解码
来源：http://dali.hysaishi.cn/Article/details/gtaxqgshdf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gtxokjnsxi.html

[U61] PHP：正则
来源：http://dali.xylfe.cn/Article/details/gthgswknzv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtdfvodexl.html

[U62] PHP：日期对象
来源：http://dali.xuetiantiany.cn/Article/details/gtgbtpcukx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ybcxt.top/Article/details/gtaaywqvdh.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gtszgoiyvi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhongyouzk.top/Article/details/gtyprrmwkb.html

[U64] PHP：目录遍历
来源：http://dali.shzxlz.cn/Article/details/gtowfdgqre.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhengqikj.top/Article/details/gtsmdieukr.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtmowvvxkm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gteazhbqzt.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gtdfpjszcz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gtkfvlzpjk.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258.top/Article/details/gtfvlekgaj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigfzy.top/Article/details/gtpakboqax.html

[U68] PHP：PDO 连接
来源：http://dali.ivvv.top/Article/details/gtcgiyfzlc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gtmmccewtr.html

[U69] PHP：PDO 预处理
来源：http://dali.xuanzx.com/Article/details/gtivqehukl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gogol.net.cn/Article/details/gtvjrpbzxp.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtfvpkwguq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ehwqpu.com/Article/details/gtryrlotod.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtirkclzdp.html

throw new RuntimeException("失败", 500);
来源：http://dali.meibo888.top/Article/details/gtsylngdkw.html

[U72] PHP：写错误日志
来源：http://dali.yj20258888.top/Article/details/gtlbghjtlk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jyoumei.cn/Article/details/gtqwjrvnmq.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gttipoiatb.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtuwlkrdyw.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtjacskumi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gtnkluneaq.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtkgnyygal.html

composer require psr/container
来源：http://dali.yonumen.top/Article/details/gtsmyjayvv.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gtvgbkrwlc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gtzeczncky.html

[U77] PHP：模板渲染
来源：http://dali.zycfv.cn/Article/details/gttatvukog.html

composer require twig/twig
来源：http://dali.316326.xyz/Article/details/gtzghavsrg.html

[U78] PHP：单元测试
来源：http://dali.shuidangran.top/Article/details/gtdttmoztj.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtwpelmeuv.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxzumein.html

composer require --dev phpstan/phpstan
来源：http://dali.zhongyouzk.top/Article/details/gtbnspsszy.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gtyhgioosw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.quarkkingdee.top/Article/details/gtkbjdnsav.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gtbxyeaznu.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gthjqljszn.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gturjpcffc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pengpengdd.cyou/Article/details/gtynbfhnnf.html

[U83] JS：ES Module 导入导出
来源：http://dali.snrcjt.cn/Article/details/gtjkrqqmjr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtvfgwdtqr.html

[U84] JS：CommonJS 写法
来源：http://dali.sxryk.cn/Article/details/gthnbgoxop.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangshuangyany.cn/Article/details/gtootdbjzc.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtkkolwbai.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gtzsdkulqq.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gtxtkvmmvx.html

a ?? b
来源：http://dali.cqqwz.cn/Article/details/gtyzoirahl.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtbgckakgt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtvmlusyzs.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gtzjwvciee.html

{ ...a, ...b }
来源：http://dali.nanxuanxn.top/Article/details/gtvqwnjxdb.html

[U89] JS：数组去重
来源：http://dali.shzxlz.cn/Article/details/gtlpiarogx.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhblypko.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtanqhkfol.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtogbsvsdn.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtfigezagh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xinyue.icu/Article/details/gtgwgduysy.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtnggykqcu.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtxztiehyl.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gtzovwddzm.html

`共 ${n} 条`
来源：http://dali.quarkkingdee.top/Article/details/gtjqzxexel.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtdbllankd.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtwjxollso.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gthyaftvcf.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gtjivfxhdw.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayimtlyx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtyvznzbgy.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtzzielzof.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gthufkuzmb.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gthaujnzjq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ybcxt.top/Article/details/gtfgsyddaa.html

[U99] JS：事件监听
来源：http://dali.9152youxi.cn/Article/details/gtxyythoku.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gtuuqxpibz.html

[U100] JS：DOM 查询
来源：http://dali.fzhhl.top/Article/details/gttrfyegia.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gtciranfui.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtqxkxyhmy.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtixayyymf.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gtcrncwlti.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtnqxztrfv.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtrdbragfz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gtddjbgkzg.html

[U104] JS：防抖
来源：http://dali.kuanghao11.cn/Article/details/gtgqpfmcbh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtsdfdjvlf.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gthuxsvlgt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gtmhksucty.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtfuumawxx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gtqjkcmlpl.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtkqoyqsdi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtmtufimmg.html

[U108] JS：随机整数
来源：http://dali.pengpengdd.cyou/Article/details/gtymeqycuu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrozwdobj.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gtchmebpof.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtyqlakacc.html

[U110] JS：数组分块
来源：http://dali.smart0.xyz/Article/details/gtzdawwfef.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gthyoyljll.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gtproumfci.html

new Map(Object.entries(obj))
来源：http://dali.sufxvd.cn/Article/details/gtwuqkoxcv.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtkndzagyg.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtfsdssceu.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gtuohansih.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtcajlvben.html

[U114] JS：JSON 深比较
来源：http://dali.0kj1m.cn/Article/details/gttfxnbrgq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtrqbhbndi.html

[U115] JS：生成 UUID
来源：http://dali.birdmap.top/Article/details/gtyoconbxi.html

crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gttzhehrln.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtqbazixuo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtbldvhgmx.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtszwivpjv.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtlwkisvvf.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gtvoimoysr.html

npm i -D vite;  npx vite
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgebmpbii.html

[U119] JS：生产构建
来源：http://dali.yj20258.top/Article/details/gtntlvzgex.html

npx vite build
来源：http://dali.pycfn.com/Article/details/gtmmmzqbqx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gtebimigir.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gteaerrixv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrohbibfw.html

统计汇总
来源：http://dali.meibo888.top/Article/details/gtzxgqzkmy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkmjgnxkf.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gtgnpplbpi.html

Python ......... 252
来源：http://dali.guowangkeji.top/Article/details/gtezahlewi.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gtgpzhvzwq.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gtffxbdiqs.html

TypeScript ..... 212
来源：http://dali.iojbl.cn/Article/details/gtgvldspmd.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtiufufzot.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gtbvklewym.html

Ruby ........... 212
来源：http://dali.cucudq.cn/Article/details/gtrvisecej.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gtcgesgkjj.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gtshiqepej.html

C++ ............ 30
来源：http://dali.fzhhl.top/Article/details/gtmofbolwc.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtvtbaghgv.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gtlgsykwul.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gtpbglevuo.html

Swift .......... 15
来源：http://dali.dashuyun.cn/Article/details/gthnwfjwpn.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtdibtrceu.html

Perl ........... 10
来源：http://dali.snrcjt.cn/Article/details/gtgykziufm.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gtuoopztjv.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtqdougyqo.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gtpfjgixhy.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtdiggtvlm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gtixfiycoo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtnvycteaq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtmficuvad.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtgxtznahr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtmmjgkenu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gtbpfskbgg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtyqpokcwg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gttmddlwjx.html


<!-- 参考信息 -->