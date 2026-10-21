代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtrlkcyayz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gtstbfjowq.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gthbkwuhph.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtpcwsmvni.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gtmobkfcuu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtksymaukz.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtikwazude.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphlwufeh.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtvwlravrb.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gtceuexrdd.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gtelnofkhz.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlynzftxg.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gtiywolnvk.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gtcphpjigd.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gtxttybiyf.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gthgwswuiw.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtoinxflkd.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gtouvwdrof.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gteiascwkt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtpgoyymuu.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtgwckvrtw.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gtuiuxedck.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gtypsorofc.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtsvzozjdb.html

[T45] Perl：数组遍历
来源：http://dali.jinqigfzy.top/Article/details/gthchktrkz.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gtuxlvjskp.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtpakrgovi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiqknauj.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtkhrqbxsa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gtnitrtdjb.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtjwkfiw.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtfkqhngvb.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtiipoepta.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtidfptrwd.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtdciouteo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtuqoovhat.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gttdwfqstp.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtziwvuehx.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtsgaimgrh.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtpaalpyfx.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gtnmjfecfx.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtyoncleia.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtewvbijlu.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsnceqjl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtarkcekya.html

[T55] Scala：集合过滤
来源：http://dali.meibo888.top/Article/details/gtahkjpwgm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gtveypmjuc.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gtfvafxpjv.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtgxdpddfa.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtkuxqrrai.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtyiopbiha.html

[T58] Scala：函数定义
来源：http://dali.jianghu66.top/Article/details/gtqlaktgsy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtowxpueiz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtockxeylk.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtdlewfqei.html

[T60] Scala：折叠
来源：http://dali.cucudq.cn/Article/details/gtilhexpdd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gthajvhdkp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmulajtpl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtoqcwhjyk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfsmhcuil.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gtdabkpxho.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtehytkcqv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtgdqcdlwh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtgktmuran.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gtsobdyfne.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gtekwtaidt.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtgowtyxaa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtdtogwlrc.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtuybourjy.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtqtwzvrfu.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gtzmdgtgaw.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtaozcosxj.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtvkbxltho.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gttmssfvjh.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtlryvkfep.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtosiynewq.html

[U09] Py：字典取最大值的键
来源：http://dali.smart0.xyz/Article/details/gtfgzgqkts.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtsvacjpcu.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtzvmuwj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtardjztmi.html

[U11] Py：生成器表达式
来源：http://dali.dashuyun.cn/Article/details/gtnzdcrnws.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gtexoomdvd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtvfpgpmlv.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgzgkrum.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gtanqnsejx.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtjlslmsin.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtenfbornf.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gttrfkicks.html

[U15] Py：高精度计时
来源：http://dali.sysykeji.top/Article/details/gtfbpodjla.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gtmgwqrylh.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gtiqiubxez.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gtwxvffpal.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmqtnsch.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtvxfwhuay.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtzzkiwfel.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtijdbofim.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gtcchabelv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gtpcyxgvyz.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslwlxaej.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtttcxwgns.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtkekosrsu.html

@contextlib.contextmanager
来源：http://dali.iojbl.cn/Article/details/gtffbelmex.html

[U22] Py：矩阵转置
来源：http://dali.zhengqikj.top/Article/details/gtlccovnkw.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gtrjmybmnf.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gtjvdyobkf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gtqrdfzmgd.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtnvsessdf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtidcjpntg.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtbdjkimce.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtlwqscfuw.html

[U26] Py：并发下载
来源：http://dali.gogol.net.cn/Article/details/gtvzrhoqbf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtzupwubey.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtahpzmzqw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gtvnbyrfrs.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gttchvmwbg.html

UserId = int
来源：http://dali.bjfxy.top/Article/details/gtrwnbdbkd.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtxdofpoqb.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gtxpetdzyj.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gtykaoeqwx.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtslaadibf.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtkdhxudsc.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gthuwipdxy.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gtmusxzknz.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gtxsdzhjhl.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gteqnlocvh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.haohaochexian.top/Article/details/gtdzvsziib.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtyypajdai.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtkprhzfym.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gtdnlrzwed.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtzpxzhjlp.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtdychfddw.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdxpvzgr.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtsvzbouyw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gtbpuptbrc.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gtufszjedm.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gtmcjwyzso.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gtthrgqhea.html

sys.stdout.isatty()
来源：http://dali.fzhhl.top/Article/details/gtdxphipyj.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtpcjetvia.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtjzxruzpe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgufenzy.top/Article/details/gtknqilvpb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gtyqnxokyp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gtxatylgia.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gtybhjttuf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtkmcejozj.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gthbwywtkq.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gtlxzninpo.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gtvfiezapd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gtnptpueoj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtydiqdxfj.html

[U46] PHP：可空类型
来源：http://dali.0kj1m.cn/Article/details/gtabanrgue.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gtxciqiuab.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gtljtjowct.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtwocwxssy.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gtanqljwvm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtmxyyxxan.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmswmabx.html

public readonly string $name
来源：http://dali.jqgfzy.top/Article/details/gtfgvmaroy.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcpphbqs.html

public function __construct(private int $id) {}
来源：http://dali.zdqjudy.top/Article/details/gtrgeqzwra.html

[U51] PHP：数组解构
来源：http://dali.feifeiyinyue.top/Article/details/gtrxndcsic.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gtqndmdxhb.html

[U52] PHP：箭头函数
来源：http://dali.cashguo.top/Article/details/gtvhfjztve.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtthvjlckw.html

[U53] PHP：空合并运算符
来源：http://dali.daria6918.cn/Article/details/gtdwwwsrcc.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gthomfkpeq.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gtryqlvjxw.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gtuemadymt.html

[U55] PHP：match 表达式
来源：http://dali.yj20258.top/Article/details/gtkfbfodsa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gteebzmmuv.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtiaftwexd.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtxrlzjxgk.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gthdrmrfgd.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gtbgzktlai.html

[U58] PHP：数组三件套
来源：http://dali.xuetiantiany.cn/Article/details/gtspwfrvrb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guannengcc.top/Article/details/gtrwiadike.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gtbugdpctk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtpddfpgvt.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gtmfnjdigh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gtjtuncbvv.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gtylthdujo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtwfkoidxv.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gtrrnwxbcg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhixingplan.top/Article/details/gtouridnui.html

[U63] PHP：文件读写
来源：http://dali.zhongyouzk.top/Article/details/gtgkhhlxta.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gtxuvoyzwc.html

[U64] PHP：目录遍历
来源：http://dali.yangfankeji.com/Article/details/gtmdrdumxf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuxming.cn/Article/details/gtctbbjpcd.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gtfjeienci.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtzocxoxrs.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gtjrdnmoki.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtxrbnixly.html

[U67] PHP：处理文件上传
来源：http://dali.nanxinkj.top/Article/details/gtgmiwibyf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtagdjmdtc.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtcbvtjaqc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dianchejie.cn/Article/details/gtpragqptm.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxhmyiwg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gtlwowkmwb.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtsuptvkst.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gtrjhyomib.html

[U71] PHP：抛出异常
来源：http://dali.fzhhl.top/Article/details/gtsjfpepbw.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gtqetjnmob.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gtsxhdmkem.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gtkasetisb.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gtatgpoabu.html

parse_ini_file("config.ini", true)
来源：http://dali.yueranfly.top/Article/details/gtouaaxtfo.html

[U74] PHP：读取环境变量
来源：http://dali.hammf.cn/Article/details/gthfqnietp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtpzrakdjs.html

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gtfmuqjuvx.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gtbuohqvsv.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gtewoxouij.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtpdgvjjtz.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gtpbrlwzyg.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gtxzgowhqs.html

[U78] PHP：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtpvhfbxfn.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gtyiydysmr.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gtptnsehtw.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gtotoviqus.html

[U80] PHP：代码规范修复
来源：http://dali.guannengcc.top/Article/details/gtdvfnvovf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.svipenyu.cn/Article/details/gtaslbxqft.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtxnvxntmq.html

npm init -y;  npm i express
来源：http://dali.haohaochexian.top/Article/details/gtfkrbitgt.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gtpciobced.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gtgxmyzcgf.html

[U83] JS：ES Module 导入导出
来源：http://dali.gaohongyu789.top/Article/details/gttsxujhyl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtbbhdntoh.html

[U84] JS：CommonJS 写法
来源：http://dali.meibo888.top/Article/details/gthastsbcl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.vqdsnc.cn/Article/details/gtplqqheqh.html

[U85] JS：可选链
来源：http://dali.zhongyouzk.top/Article/details/gtrroivaqz.html

a?.b?.c
来源：http://dali.zdqjudy.top/Article/details/gtlgosbnvu.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtrsfuiini.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtxdqqsajz.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gthzgttevl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gtkmqwqjcm.html

[U88] JS：对象展开合并
来源：http://dali.c1oappe.top/Article/details/gtpqmgdeqh.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gtkckhfxon.html

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gtgbsashdl.html

[...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtruuvbigj.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gtstsailpu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gttmjcxkjk.html

[U91] JS：对象键值遍历
来源：http://dali.iojbl.cn/Article/details/gtlqpzrsdk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtllmxjovn.html

[U92] JS：深拷贝
来源：http://dali.ehwqpu.com/Article/details/gtrdgwammh.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtdihjmhqk.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gtsrsfpudv.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gtnistmxoc.html

[U94] JS：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtonfnasui.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gtdxzexubj.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gtwjveadnx.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gtrlhoxeco.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtqvoodslg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtdcetxqgk.html

[U97] JS：并发请求
来源：http://dali.cqqwz.cn/Article/details/gtomshgjbd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtyzbyqwuk.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenlongwang.top/Article/details/gtoxfgoiza.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gtajyjmpoz.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gterxguxjo.html

el.addEventListener("click", e => {})
来源：http://dali.snrcjt.cn/Article/details/gtfubbtckt.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gtrsthjomt.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtjclxflzi.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gtdhkqzugz.html

el.classList.toggle("active")
来源：http://dali.iojbl.cn/Article/details/gtdaquioxp.html

[U102] JS：本地存储
来源：http://dali.bjfxy.top/Article/details/gtpvoppnmn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gtcrtsftrc.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gtnhckofhp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gtfurafgoi.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gtaoljpzqj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtorghnzgw.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gtilbllsdn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hywenlv.cn/Article/details/gtgauxamed.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtltryxero.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gttevshwiz.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gtttcypntg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtmboobtgp.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gtrrrfxzzr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtzkwxpsun.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtaaqdxnhk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtrnryssev.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtbinnzaob.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gtvziqiuhp.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gtvqjegmlw.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbrecaqw.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtjczfxjoi.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtckxdnygh.html

[U113] JS：正则替换全部
来源：http://dali.jqgufenzy.top/Article/details/gtbriqtpfx.html

s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtdphvdwuo.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gteashbyai.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtfylndylo.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtuetqkumj.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtgshoiiyu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gtobexpazv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gtpwgimkmd.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtguaqgctb.html

npm i -D vitest;  npx vitest
来源：http://dali.ehwqpu.com/Article/details/gtskltspdl.html

[U118] JS：开发服务器
来源：http://dali.ppjwa.cn/Article/details/gtcygyjthy.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtbqpfnjln.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gtzzvimoyv.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtokbplgcu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gtbycydeiy.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtnhrzdakn.html


<!-- 参考信息 -->