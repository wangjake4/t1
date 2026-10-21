代发 wailian999

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gtoclfqllc.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvsmkcpd.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtxfduynqj.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gtxfubzjnw.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gttlzjuhfz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zdqjudy.top/Article/details/gtherqwacq.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gtpkrdfwxq.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtgppnukku.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gtvebxcexj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gtippxkygk.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtstulucwa.html

schedule.every(10).minutes.do(job)
来源：http://dali.tianlin.xyz/Article/details/gtmcubrfvb.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gtoknptdgr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gteuywbbzf.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgfzy.top/Article/details/gtwkgnrnmf.html

Path(__file__).resolve().parent
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetdeoacb.html

[U39] Py：判断是否在交互环境
来源：http://dali.cashguo.top/Article/details/gtrqybrgye.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gtfqisiauh.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtemzarmjy.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtotpawnwb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gthdaykqoz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gtixtmndja.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xinyue.icu/Article/details/gtdvpjxmib.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtrizgpxmx.html

[U43] PHP：声明命名空间
来源：http://dali.cheryme.top/Article/details/gtwmfflhll.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gtsnakbyqn.html

[U44] PHP：开启严格类型
来源：http://dali.cdnleiting.top/Article/details/gtaparfmoo.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtujdiainc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gtzmmynuwl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwtunxznt.html

[U46] PHP：可空类型
来源：http://dali.sweek.top/Article/details/gtayknetcd.html

?string $name = null
来源：http://dali.gotoacloud.top/Article/details/gtzgwyftpy.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gtdewmrjvv.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gtebcvrcox.html

[U48] PHP：纯枚举
来源：http://dali.sweek.top/Article/details/gtdixgixfg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gtmpqunlas.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gtxydbswwx.html

public readonly string $name
来源：http://dali.shuidangran.top/Article/details/gtffazyzsm.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gtqfpveick.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gtsehkhgsz.html

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gtusoqwlkp.html

[$a, $b] = $arr;
来源：http://dali.dashuyun.cn/Article/details/gtpzmuxqon.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtocnadlae.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gtwarrrfgc.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gtrchccwya.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gttnuhvame.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglvmofga.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gtadyqccah.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtjutbwlue.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.iojbl.cn/Article/details/gtgrkrgbvx.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gthbvrqwlw.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtrsxaglab.html

[U57] PHP：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtfuxqfgud.html

"值: {$a}"
来源：http://dali.dianchejie.cn/Article/details/gtepnsvbxq.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gtxorvkeni.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gtjrrvqlxc.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gtqddxflcw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtzbkjmtuo.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpabufuf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.svipenyu.cn/Article/details/gtesbchqgu.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gtzzeyamej.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtglztydxv.html

[U62] PHP：日期对象
来源：http://dali.hnqzz.top/Article/details/gtwckpbmmj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gaohongyu789.top/Article/details/gtypipmngj.html

[U63] PHP：文件读写
来源：http://dali.vqdsnc.cn/Article/details/gtelyyoayx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gtubhkjtds.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gtjuqfnhlz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gtcwoqkgra.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gtwzbdoocn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtqljxcktz.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtgazxaixt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljnqkrdh.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtzkvpukkg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gthhndrafh.html

[U68] PHP：PDO 连接
来源：http://dali.c1oappe.top/Article/details/gtyoksrahd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenjidiqi.icu/Article/details/gtptygkdpw.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gthoqxmhly.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zycfv.cn/Article/details/gtftrlzzoh.html

[U70] PHP：PDO 事务
来源：http://dali.jiagoushi.top/Article/details/gtdhrfldof.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gtaqypmefq.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gttsaakxiz.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtftcniyuc.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gtcglyuels.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sufxvd.cn/Article/details/gtjoseiqft.html

[U73] PHP：读取 ini 配置
来源：http://dali.shzxlz.cn/Article/details/gtuwkeddii.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gtxjkbabtg.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtefvxkakj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gtchyxrwos.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtenejeuam.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtunevpkcz.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtgcnseocd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gtaxnogogy.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gtyvdvzeip.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtmdknqsuz.html

[U78] PHP：单元测试
来源：http://dali.cucudq.cn/Article/details/gtexpnzxhk.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgufenzy.top/Article/details/gtaccdravy.html

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gtctabvcoz.html

composer require --dev phpstan/phpstan
来源：http://dali.cqqwz.cn/Article/details/gthydzcayp.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gtezntbvkp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ppjwa.cn/Article/details/gtfwbhugdm.html

[U81] JS：初始化项目
来源：http://dali.zhiwuduotai.top/Article/details/gtjtvvezgh.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gtrtmakrcp.html

[U82] JS：package.json 脚本
来源：http://dali.hfpthk.cn/Article/details/gtbfaqtfro.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgufenzy.top/Article/details/gtnohcagmn.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gtxhaamomp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtbslklcrc.html

[U84] JS：CommonJS 写法
来源：http://dali.quarkkingdee.top/Article/details/gtmwftxosb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtetkhsgck.html

[U85] JS：可选链
来源：http://dali.hongshengwenyu.top/Article/details/gtehwucrrw.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gtvqmrizkx.html

[U86] JS：空值合并
来源：http://dali.hongshengwenyu.top/Article/details/gtqeewueyf.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gtfurfbtfq.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtfldbangl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.quarkkingdee.top/Article/details/gtdlepmvcm.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gtayefxviu.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gtwegceuis.html

[U89] JS：数组去重
来源：http://dali.pengpengdd.cyou/Article/details/gtrgpbxjtr.html

[...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtlhqxaxmv.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gtxawkspgb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmcmyeve.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtfnkmuyuo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gtdfrbolwd.html

[U92] JS：深拷贝
来源：http://dali.bjfxy.top/Article/details/gtuoatanxz.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxnkmfom.html

[U93] JS：模板字符串
来源：http://dali.sysykeji.top/Article/details/gtsmsoupyc.html

`共 ${n} 条`
来源：http://dali.jinqigfzy.top/Article/details/gtkqzsoywq.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtubingvjj.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gtiqourqvk.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gtigxiehde.html

new Promise((resolve, reject) => {})
来源：http://dali.tianlin.xyz/Article/details/gtqjvkfxff.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gtshrukjtc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdrbdbis.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphikaebq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtvxattapy.html

[U98] JS：fetch 带 JSON
来源：http://dali.haohaochexian.top/Article/details/gtkktpceib.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hysaishi.cn/Article/details/gtytbxyzve.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gtbvfcjojm.html

el.addEventListener("click", e => {})
来源：http://dali.hfpthk.cn/Article/details/gtjkpiplqh.html

[U100] JS：DOM 查询
来源：http://dali.daria6918.cn/Article/details/gtqpjxdrpv.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gtmgrkjvfp.html

[U101] JS：classList 操作
来源：http://dali.ybcxt.top/Article/details/gttualolbt.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gtchhtjipi.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtdqmqrlqj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cheryme.top/Article/details/gthttlvsdo.html

[U103] JS：定时器
来源：http://dali.nwbrower.top/Article/details/gtxsxzbcob.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gtiyjqjslt.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gtmmmkcvmc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtxnvblyyf.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gtjuoqqqfm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gtsbmzipmp.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtsbltczwu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daria6918.cn/Article/details/gtawcituqw.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtuqdywkto.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaauevul.html

[U108] JS：随机整数
来源：http://dali.zhengqikj.top/Article/details/gtoihfouvj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gtjzqwzuem.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gtvbyctxvd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtjqokvhgg.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gtzyovzhoo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gtjpplqjvj.html

[U111] JS：对象转 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtjxnxiniw.html

new Map(Object.entries(obj))
来源：http://dali.hfpthk.cn/Article/details/gtqmpjwjeb.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gtwboeydhk.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtafomdffj.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtldsxydom.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtsycpdlip.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gtvoexzjbc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gtdhdbuwyk.html

[U115] JS：生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtainwyiyy.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtrzqtefwk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gtbhxfbvrs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenlongwang.top/Article/details/gtsbvgkegi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtytozwftm.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtrljovnsm.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gthinnljqb.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gtbmekkmhx.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gtzbtumvla.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtvrufioxe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gtzvwxhqpx.html

import.meta.env.VITE_API_URL
来源：http://dali.316326.xyz/Article/details/gtpcdmtzjj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbneheeyt.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gtdujxupcm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfmkucfdl.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gtcxzrdxax.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gtohmqtilf.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gtgfwotajf.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtxfmwkbqy.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gtvhfjqcvc.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gtgchighun.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtjazleigv.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtiwiwjprl.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gtptramdsj.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtbilvrajy.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gtvshkiqcq.html

SQL ............ 90
来源：http://dali.yj20258888.top/Article/details/gtghdpqwtc.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gttjrmzeag.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gtethitgrp.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtefsqqacy.html

Lua ............ 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gteowtvfjy.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gtsgogvfkv.html

Scala .......... 10
来源：http://dali.cheryme.top/Article/details/gttcjzruzh.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtqwygbshw.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcxpqhpt.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gtolqlvexs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtiuvidyoi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtahdbpsxe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtbygprwmb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gtmjslbgot.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gtotkrhadm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gteogagnde.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtuospmbke.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gthvnomakk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtneavajyf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtrvobuoxu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtpohmqcjo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gttepvnomj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtktiundzl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gtsubgkhco.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jiagoushi.top/Article/details/gtmbbwlhlo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjujxudb.html

Q SQL 专题                              90
来源：http://dali.xuetiantiany.cn/Article/details/gtephypgbg.html

R Bash 专题                             80
来源：http://dali.iojbl.cn/Article/details/gtipelnvon.html

S C / C++ 专题                          60
来源：http://dali.mhx1999.top/Article/details/gtpobexhys.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtgrgzbowx.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gtjvxqlnph.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtpritmbtq.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtguoqnzik.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtgftwmcaa.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtmkpfhdyq.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gttujxsynt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yongpay.top/Article/details/gtgtqqgdxy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gtfuhyjvpk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gtgjrbqujs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hywenlv.cn/Article/details/gtyocuiwyi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tian-w.cn/Article/details/gtqprcnnwl.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gtxjweeovc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtibjcalso.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gtyglzaneg.html

Common Programming Examples Cheat Book
来源：http://dali.hammf.cn/Article/details/gtbyiucvne.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkmkwsbpi.html

【收录内容】
来源：http://dali.ydzc1.top/Article/details/gtfjldcvbf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xziqi.cn/Article/details/gtufxotghq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gtsxfnlakk.html

SQL · Bash · C · C++
来源：http://dali.meibo888.top/Article/details/gtnsccsxni.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gtaefzuhud.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gtmozerkxo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gtmadfgylc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gtsmznoblk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cqqwz.cn/Article/details/gtdiouzcks.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgufenzy.top/Article/details/gtmbsenhcz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcystynl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.316326.xyz/Article/details/gtgeqlbrtm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gtfknadmji.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuudbudms.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgufenzy.top/Article/details/gtzmvokrva.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gtwpplnnai.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hfpthk.cn/Article/details/gtcwktiufk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hysaishi.cn/Article/details/gtiltgyemq.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbpcyfkl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zycfv.cn/Article/details/gtcaknwxxz.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtekwtulpx.html

目  录
来源：http://dali.yj20258888.top/Article/details/gtmdbufoyo.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtvhlkrcdr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtxyimghav.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtlhyilxrs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtmmhojjdh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtohrsqwwa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhoulong.xyz/Article/details/gthgndshfs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gtfnilanvt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtuiqbybtq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtsupistdt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtsraumssx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gteouatoon.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtffguncye.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtmcwbsgcz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtlsibnoso.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtljbohudt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnluhhuyg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtzxkvbfbj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sysykeji.top/Article/details/gtsfevmikv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtnupdlokz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqzlltgnh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtezsrfwnz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtanehsewu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbdmfmnhm.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gtbngbqsyd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtarrstddr.html

[A01] Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtkokvpeem.html

Py:   print("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtqbctxghx.html

PHP:  echo "Hello, World!";
来源：http://dali.yvedp.cn/Article/details/gtzfsmzwxw.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtxbnxvrli.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenlongwang.top/Article/details/gtpxypgzzo.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtbywdewme.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gtwskeijxv.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gtynoxezoq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtwugigwkc.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gtkcjxtbon.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gtcpfuwyrs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.316326.xyz/Article/details/gtcmhbssxg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sweek.top/Article/details/gtjsaeumcl.html


<!-- 参考信息 -->