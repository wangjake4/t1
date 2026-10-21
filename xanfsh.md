代发 wailian999

[U51] PHP：数组解构
来源：http://dali.shuidangran.top/Article/details/gtsxuifqwx.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtjctmkapz.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtgzqzwyhl.html

$double = fn($x) => $x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtsheuxdrx.html

[U53] PHP：空合并运算符
来源：http://dali.mhx1999.top/Article/details/gtovmqriuu.html

$v = $a ?? $b ?? "default";
来源：http://dali.mhx1999.top/Article/details/gtsaqwzpjs.html

[U54] PHP：空安全调用
来源：http://dali.jyoumei.cn/Article/details/gtadesrcop.html

$obj?->method()
来源：http://dali.feifeiyinyue.top/Article/details/gtxxwtumqx.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtcdvrqipl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgnnntfw.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gtmezdllql.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtaujnkyqu.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtzpfbvgxz.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtirippcsz.html

[U58] PHP：数组三件套
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyosqise.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ybcxt.top/Article/details/gtsqowykeq.html

[U59] PHP：自定义排序
来源：http://dali.guannengcc.top/Article/details/gtgnspnhks.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtewwjrdrj.html

[U60] PHP：JSON 编解码
来源：http://dali.yueranfly.top/Article/details/gtrbvrdbpr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gtrprepbca.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gtsyzombuc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtxmhsaiow.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gtrcfzadqe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hywenlv.cn/Article/details/gthgstjdku.html

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gtwrgustpf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cheryme.top/Article/details/gtirbovlno.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gtrzjchvxr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtgmxbghnl.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtqlphgocv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtnhuhokhs.html

[U66] PHP：设置 Cookie
来源：http://dali.hywenlv.cn/Article/details/gthpkjuilm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gtwmmbrjsi.html

[U67] PHP：处理文件上传
来源：http://dali.nanxinkj.top/Article/details/gtyookuwwj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gthvkegezh.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtvefsqjgk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtyxmwmltt.html

[U69] PHP：PDO 预处理
来源：http://dali.yangfankeji.com/Article/details/gtatmxrqyc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqhfjkjo.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gtqslchffn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gtswlhnjmg.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gtbrzufayw.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtgdpjbesk.html

[U72] PHP：写错误日志
来源：http://dali.shzxlz.cn/Article/details/gtwreyhuqe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.quarkkingdee.top/Article/details/gtvoxppkuk.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenlongwang.top/Article/details/gttcpvfvol.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gtvdnzoaen.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtmrpmeqxj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gtwvzmfsor.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gtouwuxpuk.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtgqchjnqr.html

[U76] PHP：简单路由
来源：http://dali.hnqzz.top/Article/details/gtasjekjuc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.vqdsnc.cn/Article/details/gtgcyfqjvm.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulouipsa.html

composer require twig/twig
来源：http://dali.jqgfzy.top/Article/details/gtllqwvuto.html

[U78] PHP：单元测试
来源：http://dali.yj202588.top/Article/details/gtqjvsmgiq.html

composer require --dev phpunit/phpunit
来源：http://dali.yuxming.cn/Article/details/gtvnaazxdw.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gtfwqqiskh.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258888.top/Article/details/gtslqwtixt.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtjccdaavi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gtemkeizgm.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuxsiktb.html

npm init -y;  npm i express
来源：http://dali.shuidangran.top/Article/details/gtdznbrtec.html

[U82] JS：package.json 脚本
来源：http://dali.guowangkeji.top/Article/details/gttaexarza.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtwxueqqlu.html

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gttjtqzkbz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtmctfpuji.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtgytejldt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gtbnxvhizh.html

[U85] JS：可选链
来源：http://dali.ydzc1.top/Article/details/gtaessdngp.html

a?.b?.c
来源：http://dali.cashguo.top/Article/details/gtapabqbym.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtzhxqrivc.html

a ?? b
来源：http://dali.gogol.net.cn/Article/details/gttdjjfukf.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gtsonzzizz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgufenzy.top/Article/details/gtnpfnxpgn.html

[U88] JS：对象展开合并
来源：http://dali.sysykeji.top/Article/details/gtonbltmuo.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxdpsvuo.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtqfvudjzf.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gttruyhgbs.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gtughlrfkr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtvvxohnxt.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gtpesotknj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gtxsijsuay.html

[U92] JS：深拷贝
来源：http://dali.yongpay.top/Article/details/gtdkgxcgik.html

structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtzqrswrlt.html

[U93] JS：模板字符串
来源：http://dali.bjfxy.top/Article/details/gtlhazhajv.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtpjymatos.html

[U94] JS：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gtpuptkvav.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtpwbmkvlm.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gtemcigcva.html

new Promise((resolve, reject) => {})
来源：http://dali.zycfv.cn/Article/details/gtienvapjo.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gtlsridewp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtqmnmbdcd.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkfqssyy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtthslwpum.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gtwnlacmlj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhengqikj.top/Article/details/gtxdpieqpp.html

[U99] JS：事件监听
来源：http://dali.xinyue.icu/Article/details/gtpujvgyyj.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gtxorozpze.html

[U100] JS：DOM 查询
来源：http://dali.cqqwz.cn/Article/details/gtexsdwksr.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtccsowebz.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gtwirwsiro.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gtbzlxcxbg.html

[U102] JS：本地存储
来源：http://dali.mhx1999.top/Article/details/gtvekwqqvz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhengqikj.top/Article/details/gtlzfayjov.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gtoxeluuuw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gtqynmqqec.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtktxmeerf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsucpiid.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gtjlachjcs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gtmftlacrt.html

[U106] JS：日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtoavjyefn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guannengcc.top/Article/details/gtggjqdlia.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkqtamdn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.redwolf501.top/Article/details/gteuplhfhi.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gthxgyikpm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ydzc1.top/Article/details/gtefyhpymk.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gtsexeriqu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtykvczwtd.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtzfmfmlia.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gtbxrsfnso.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gtqpywvlxm.html

new Map(Object.entries(obj))
来源：http://dali.yuanzhike.top/Article/details/gtavqfqlux.html

[U112] JS：字符串补位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjeovuqe.html

"7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtrkyqgbtm.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gtekgetygs.html

s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtmswnkwrd.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtwgdhjhsz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gthjuutocx.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtbfmnbvzo.html

crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gttmwqawdc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtpmoppnta.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtptntmjev.html

[U117] JS：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtxwvymeee.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gtoadwxjnt.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gttlifaina.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gtnjpsezaz.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gtscrllxri.html

npx vite build
来源：http://dali.jianghu66.top/Article/details/gtufzfglsv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gtugtbzclv.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gtnizwuhug.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtptaxmrdj.html

统计汇总
来源：http://dali.zycfv.cn/Article/details/gtumgistjf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmzegpxjc.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gtprvctgja.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtputthmtf.html

PHP ............ 252
来源：http://dali.xuanzx.com/Article/details/gtxxtrnlms.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtexkdmxtm.html

TypeScript ..... 212
来源：http://dali.andypj.xyz/Article/details/gtzwjipsop.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtytunjklt.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtcbghesrn.html

Ruby ........... 212
来源：http://dali.pycfn.com/Article/details/gtxwtirqlh.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gtlkqnfvyk.html

C .............. 30
来源：http://dali.sxryk.cn/Article/details/gtxrrzrolc.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtqqtdrwxe.html

SQL ............ 90
来源：http://dali.gotoacloud.top/Article/details/gthstxfxye.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gtmtlijjxj.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtvseyhbtw.html

Swift .......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqxffwfw.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gtpzidevlg.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gtrfeuwkpb.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gtfgmfuwqf.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtseodfpge.html

合计 ........... 2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gtllglrezy.html

按章节统计：
来源：http://dali.sweek.top/Article/details/gtypnuzauq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtbgakzpkx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtyhvkfjow.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gttcsqcmip.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gtsnjvccfq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gtadblbswq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gtfqlwbpcs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtbiiiiwwp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtobdnvtaa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtgrnmhhto.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtqhtcqljb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtsstkbyne.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtcqreaeuf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtqhixtenq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtcqeprpeh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gtbfgwidbj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtomnzkgjd.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gtnlldfsru.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gtvgtxyhvq.html

S C / C++ 专题                          60
来源：http://dali.feifeiyinyue.top/Article/details/gtjylfvomi.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gtuiofjena.html

U 高频实用片段                         120
来源：http://dali.hfpthk.cn/Article/details/gtrnkezari.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtrjclkmke.html

合计                                  2106 条
来源：http://dali.nanxinkj.top/Article/details/gtquvnjecp.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtimyxsdlr.html

使用提醒
来源：http://dali.316326.xyz/Article/details/gtpljdhimg.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtkjjmougm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guowangkeji.top/Article/details/gtvyutznps.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.quarkkingdee.top/Article/details/gthsobajqc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gtykmotiqa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gtwbdzuhqj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtsnvmtzei.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtawczmdvn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gteylznmxt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gtdmtwjcxm.html

Common Programming Examples Cheat Book
来源：http://dali.zhoulong.xyz/Article/details/gtyzjezhoi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbscmteyn.html

【收录内容】
来源：http://dali.cdnleiting.top/Article/details/gtvbxyhkuz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.haohaochexian.top/Article/details/gtmoqpgybw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.smart0.xyz/Article/details/gtjquijpaf.html

SQL · Bash · C · C++
来源：http://dali.hnxiangtu.top/Article/details/gteuchcqep.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gtfglwdapq.html

【使用说明】
来源：http://dali.zhixingplan.top/Article/details/gtuqveqkyu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtmqqkojft.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gtksmldmci.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gtivmsimvb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gtsldutjng.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.smart0.xyz/Article/details/gtkrisgjkg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gtpypyxvst.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daria6918.cn/Article/details/gtvhpgseyd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hfpthk.cn/Article/details/gtptszfusa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gtgrwccuwd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gtmcyxzcyk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jlsjyb.cn/Article/details/gtyvcaricc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenzaomai.com/Article/details/gtdinpeupa.html

【文件统计】
来源：http://dali.hammf.cn/Article/details/gtksddvvsv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjmgqltt.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtuoiwqibp.html

目  录
来源：http://dali.quarkkingdee.top/Article/details/gtguwscrqd.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gttqtjgqda.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgufenzy.top/Article/details/gtjqdpyler.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtwyozocgy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtevetiser.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gticyzfbfl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fengsongda.top/Article/details/gtjfdhpmpi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtmaztdkmh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtlrykjzki.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gtlnzxjhdb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtlqukfmns.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtmzmegyaj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtdivhikac.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtsmauzqzl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtqbziufxt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtogmntekx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gtnfvaysod.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gttauohvkz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daxiang520.top/Article/details/gtktxrwbis.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cheryme.top/Article/details/gtxyflgmsh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuxming.cn/Article/details/gtiezcpudc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtnxhnbhir.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtvtrndcco.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtclmtclxq.html

A. 基础语法与类型
来源：http://dali.yanxiufei.cn/Article/details/gtcrgsxzzd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvqtqzynp.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexxjrnyt.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvsyxjiu.html

PHP:  echo "Hello, World!";
来源：http://dali.birdmap.top/Article/details/gtjjwvanxi.html

JS:   console.log("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtaydzvejg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gtvcbwnkce.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtprttudls.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gtydlsbqbi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtcttrlrkc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtwpilprdt.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gtgwlblbny.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhoulong.xyz/Article/details/gtqsxkidfa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtosizdrmg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtpjoaewtt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtgsxewfjj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtaadvtfid.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtshgrrgws.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zycfv.cn/Article/details/gtuznyhmgl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtuucnxjxu.html

[A03] 常量定义
来源：http://dali.jinqigfzy.top/Article/details/gtdhmxjuww.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cucudq.cn/Article/details/gtienqylzx.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqvlbfel.html

JS:   const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtcdycnlri.html

TS:   const PI: number = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtlefoepou.html

Java: static final double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtakiinyrm.html

Go:   const PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtdpsjiqad.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtbxtyyato.html

C#:   const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtxuxhywel.html

[A04] 判断变量类型
来源：http://dali.tanke756.top/Article/details/gtjggraonn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtwgrftwun.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gtbfwnascd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtvxjbfqqx.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gtyghzmrgr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hongshengwenyu.top/Article/details/gtcubpmedi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gtocjorpmy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gtladetetg.html

C#:   x.GetType().Name; x is int
来源：http://dali.havefunace.top/Article/details/gtceslkpkq.html

[A05] 整数除法与取模
来源：http://dali.iojbl.cn/Article/details/gtpsztsrrt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhoulong.xyz/Article/details/gtyjvupiby.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtpasggwij.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtfpujwfet.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtgypfkqtm.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gthitfzytl.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtwukeifox.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gthwsqyzqv.html

C#:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtlenriqas.html

[A06] 字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtusztgbcf.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gtfkglwznx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.svipenyu.cn/Article/details/gtduxximur.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cheryme.top/Article/details/gtxzhladiv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gtpzjwrmzp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtrgfypikw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.svipenyu.cn/Article/details/gtanblnbsp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xziqi.cn/Article/details/gtglcrxgbc.html


<!-- 参考信息 -->