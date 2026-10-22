代发 wailian999

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gt2epbigkse.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gt2ahlzqrgj.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gt2odxlgsuz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gt2iqxslfci.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gt2naopdccn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2bewjqjxr.html

[U66] PHP：设置 Cookie
来源：http://dali.hnqzz.top/Article/details/gt2mfeqxhjk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxqfgaxv.html

[U67] PHP：处理文件上传
来源：http://dali.shuidangran.top/Article/details/gt2hxhpldpj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ehwqpu.com/Article/details/gt2evnfyjtc.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gt2ujvierjf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sysykeji.top/Article/details/gt2nwoavgfx.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gt2ncfzizwk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gt2qfdlurxa.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gt2qgmsudob.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gt2bvpvehgl.html

[U71] PHP：抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2lpqyiwjo.html

throw new RuntimeException("失败", 500);
来源：http://dali.havefunace.top/Article/details/gt2bymcxaxu.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gt2xqkvbywo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pfglrfhe.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gt2ppgblbta.html

parse_ini_file("config.ini", true)
来源：http://dali.xziqi.cn/Article/details/gt2nwgwgmyd.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2zxtulrbv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gt2sbzdgsvr.html

[U75] PHP：依赖注入
来源：http://dali.yonumen.top/Article/details/gt2swzhsqud.html

composer require psr/container
来源：http://dali.jiagoushi.top/Article/details/gt2pzslvbtz.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gt2uudsbrcw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.snrcjt.cn/Article/details/gt2kzaejjun.html

[U77] PHP：模板渲染
来源：http://dali.xuanzx.com/Article/details/gt2prmhhejt.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gt2hmnudajg.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2ghzakjzl.html

composer require --dev phpunit/phpunit
来源：http://dali.tian-w.cn/Article/details/gt2hgckhauc.html

[U79] PHP：静态分析
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpulvcif.html

composer require --dev phpstan/phpstan
来源：http://dali.iojbl.cn/Article/details/gt2smxtgnpz.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2waxjnngf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuxtitiw.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gt2nfsdjcdz.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gt2fswzmnre.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gt2kthdrxuu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlffpflz.html

[U83] JS：ES Module 导入导出
来源：http://dali.redwolf501.top/Article/details/gt2hnxbwtuu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gt2htinxsbm.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxuanxn.top/Article/details/gt2eyqsuipp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gt2zzukzroo.html

[U85] JS：可选链
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uskmsqcp.html

a?.b?.c
来源：http://dali.xuanzx.com/Article/details/gt2vjquiurc.html

[U86] JS：空值合并
来源：http://dali.pycfn.com/Article/details/gt2rkjzyhya.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gt2wsvxbtpw.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gt2inuopivg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hammf.cn/Article/details/gt2fqsmkdew.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gt2ndftekyv.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gt2vndhezbo.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gt2mnajrcmt.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2lhpvnbat.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gt2qbrgxatg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2sqfozejr.html

[U91] JS：对象键值遍历
来源：http://dali.yueranfly.top/Article/details/gt2pqnslqxs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pycfn.com/Article/details/gt2yyhdzkwp.html

[U92] JS：深拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2oqbljhpv.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxgdhaoo.html

[U93] JS：模板字符串
来源：http://dali.zdqjudy.top/Article/details/gt2gqazrrja.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gt2zsyrlobe.html

[U94] JS：箭头函数
来源：http://dali.c1oappe.top/Article/details/gt2szeqjvha.html

const double = x => x * 2;
来源：http://dali.yongpay.top/Article/details/gt2rykuokri.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gt2yhzsvrxt.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gt2mqehyefl.html

[U96] JS：async/await 与异常
来源：http://dali.xinyue.icu/Article/details/gt2tlhkmech.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2nanobwjx.html

[U97] JS：并发请求
来源：http://dali.cashguo.top/Article/details/gt2xgycjgco.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2icjrxizu.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gt2mhyiuotj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gt2fatsuvtm.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftrgadvo.html

el.addEventListener("click", e => {})
来源：http://dali.sweek.top/Article/details/gt2uvwwqwop.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etkvjmzp.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gt2dnlkivfm.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nejvckue.html

el.classList.toggle("active")
来源：http://dali.gaohongyu789.top/Article/details/gt2iqfsazjd.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gt2twxagzzf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ehwqpu.com/Article/details/gt2mdmhjrmj.html

[U103] JS：定时器
来源：http://dali.zdqjudy.top/Article/details/gt2gvopwftf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gt2wkvevlhz.html

[U104] JS：防抖
来源：http://dali.sweek.top/Article/details/gt2gbekoyow.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2qdhymgjk.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gt2iehspbne.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2sxvrrcwl.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llflytrc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gt2uetvvteg.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2zrvjzvgl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2qtwgoxfz.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gt2pdfgzmrm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gt2syrvdqvv.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gt2apwghmaw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2dhlblunv.html

[U110] JS：数组分块
来源：http://dali.gogol.net.cn/Article/details/gt2dyitpmxr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gt2kqxjzqgi.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsiyojdb.html

new Map(Object.entries(obj))
来源：http://dali.hysaishi.cn/Article/details/gt2lpadvghg.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gt2fixfgtkn.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2livhqnao.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gt2zqmtebvh.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2jvlwwgym.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gt2vygplycb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijveeyau.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2pcxecbyb.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2phwrwjgk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gt2bsxdvxbf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.svipenyu.cn/Article/details/gt2mqcdvhpg.html

[U117] JS：单元测试
来源：http://dali.yonumen.top/Article/details/gt2lyyahjgd.html

npm i -D vitest;  npx vitest
来源：http://dali.dashuyun.cn/Article/details/gt2wlokujew.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gt2bloygbel.html

npm i -D vite;  npx vite
来源：http://dali.pycfn.com/Article/details/gt2zyeqqcrv.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gt2iyvqmtet.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gt2prjuvhtd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gt2gqmdpeqv.html

import.meta.env.VITE_API_URL
来源：http://dali.shzxlz.cn/Article/details/gt2noclltde.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2agtvxjqc.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gt2uwriuxcq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2aecqakvl.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gt2mdxgkzer.html

Python ......... 252
来源：http://dali.ppjwa.cn/Article/details/gt2pfbvnlxc.html

PHP ............ 252
来源：http://dali.xziqi.cn/Article/details/gt2juwwaeap.html

JavaScript ..... 252
来源：http://dali.cashguo.top/Article/details/gt2lnwvzyzb.html

TypeScript ..... 212
来源：http://dali.nanxuanxn.top/Article/details/gt2uufpfaml.html

Java ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2xipzzugb.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2jqfipkig.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2scvrxxjz.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyrqeklb.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gt2uaaqvokq.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhcmubsb.html

SQL ............ 90
来源：http://dali.yanxiufei.cn/Article/details/gt2qmhyfrgi.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gt2ttpbbngt.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gt2nbetbxrw.html

Swift .......... 15
来源：http://dali.yongpay.top/Article/details/gt2xgxxtrww.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gt2dfzajwki.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gt2kknwdvpe.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gt2cpumvyrn.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2cqpzfwkx.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gt2gaakkapm.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gt2gdvoeeza.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gt2uriechzu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gt2wzawlygm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gt2kyvdwyby.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2suklrmel.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuxming.cn/Article/details/gt2nbecamlz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gt2vycfklnw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2zbehctxy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnijbsgh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2naceuceh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2zorjhakz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2omqolsiq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2rjzlhbmb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2dykszfzp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbzphpjg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shangyingyoupin.top/Article/details/gt2csyitdma.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2dskuyjix.html

Q SQL 专题                              90
来源：http://dali.nanxinkj.top/Article/details/gt2jompjcnd.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gt2lryrttnx.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gt2wdapenrx.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gt2xmwazfng.html

U 高频实用片段                         120
来源：http://dali.xinyue.icu/Article/details/gt2qcorfnno.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2rynyljqy.html

合计                                  2106 条
来源：http://dali.zhengqikj.top/Article/details/gt2ehmlamrp.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2stlidhgm.html

使用提醒
来源：http://dali.feifeiyinyue.top/Article/details/gt2lekdfuvu.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2wncbkgrl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gt2sqjqpniq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2dgofcwil.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.meibo888.top/Article/details/gt2xnzfkcby.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gt2bubaxmeb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugfhbcnk.html

—— 文件结束 ——
来源：http://dali.dianchejie.cn/Article/details/gt2epfqpqen.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsrzwfmt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwzhaifg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqttvqm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pdacuuas.html

【收录内容】
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxcuzyhz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwkahmjb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zdqjudy.top/Article/details/gt2sxbtmhuu.html

SQL · Bash · C · C++
来源：http://dali.nanxinkj.top/Article/details/gt2tvwpnxuq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sufxvd.cn/Article/details/gt2zcqitsom.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gt2zfmjzelt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yueranfly.top/Article/details/gt2ovqrwrzc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ivvv.top/Article/details/gt2tddlcfzq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpopssec.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gt2ivzbwaou.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cdnleiting.top/Article/details/gt2nhiaxrjt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangdashe.top/Article/details/gt2uivsccxl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gt2swplprbq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gt2rmchvmbq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuhokczo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gt2bdrzqzsj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shuidangran.top/Article/details/gt2akquzlsu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gt2drjbnbau.html

【文件统计】
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrogahhz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.smart0.xyz/Article/details/gt2sllmpgsl.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gt2qovqgwes.html

目  录
来源：http://dali.hfpthk.cn/Article/details/gt2fscupxhs.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2uvygeyis.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2livkrsoc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gt2nuhfdjjf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gt2bnotxkzd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gt2vrdotwho.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shuidangran.top/Article/details/gt2eltiqukg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2bkfqvprz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpxbikid.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gt2pcuvqejf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2dvpsaelu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2oiorfknj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2cpdesuuz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2mgeauhbg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2keryxhxk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gt2gnmdqnll.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gt2wgsabjkv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2qrwogiwi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.andypj.xyz/Article/details/gt2hupjjqzj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gt2tjwzfroo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daxiang520.top/Article/details/gt2rgvcybef.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpbjtfhe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gt2igtrrwfm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2deznqyvc.html

A. 基础语法与类型
来源：http://dali.hywenlv.cn/Article/details/gt2ghwdvljv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qfoqbutt.html

[A01] Hello World
来源：http://dali.c1oappe.top/Article/details/gt2ftuzjsvo.html

Py:   print("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gt2jafyvkms.html

PHP:  echo "Hello, World!";
来源：http://dali.gzhubu.top/Article/details/gt2kijtjfhy.html

JS:   console.log("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2mucnblfu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gt2tbyxolxs.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptfeefri.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gt2xszgwfay.html

Ruby: puts "Hello, World!"
来源：http://dali.gaohongyu789.top/Article/details/gt2uhhxsafu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2xylynbbv.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gt2altlvbwz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgfzy.top/Article/details/gt2xjvdfcde.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2drdwkovd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gt2qopiinwi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gt2onkfahdr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gt2jmndhjej.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gt2yactgrjm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gt2xmoywklb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2dnxkyaqv.html

[A03] 常量定义
来源：http://dali.daxiang520.top/Article/details/gt2ufinpayw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gt2dhngaepe.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2cevmbiwp.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2nkpvivvy.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2qmclmeka.html

Java: static final double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2ufjgdysm.html

Go:   const PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gt2alsvatun.html

Ruby: PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gt2urmxlbae.html

C#:   const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2baogrswp.html

[A04] 判断变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2szpdlxax.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhongyouzk.top/Article/details/gt2brifxkzo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2swnyqtbc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gt2jfwnuuii.html

TS:   typeof x; x instanceof Date
来源：http://dali.cucudq.cn/Article/details/gt2wztjjysa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hammf.cn/Article/details/gt2tmntkarz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jiagoushi.top/Article/details/gt2ualhzdrz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gt2mwkfesyy.html

C#:   x.GetType().Name; x is int
来源：http://dali.haohaochexian.top/Article/details/gt2emrqlanc.html

[A05] 整数除法与取模
来源：http://dali.havefunace.top/Article/details/gt2pskfoevi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gt2uomfavtr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2xjkervkr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2uifdmwkh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2nsclrhjl.html

Java: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2atquqyrc.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2dbrrpvcw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2earbfqis.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2fcyihhxr.html

[A06] 字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2jixpbkzx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2wrfeanlj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gt2zsaxefcz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2kygyuido.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqlapiak.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tian-w.cn/Article/details/gt2rkoldkwo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dianchejie.cn/Article/details/gt2eikjvsgu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gt2nmdewjcr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2nstlnjla.html

[A07] 数字转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2xxxhlrqe.html

Py:   str(42)
来源：http://dali.hysaishi.cn/Article/details/gt2zysdokfj.html

PHP:  (string) 42; strval(42)
来源：http://dali.ehwqpu.com/Article/details/gt2ckznepbt.html

JS:   String(42); (42).toString()
来源：http://dali.daria6918.cn/Article/details/gt2wdpimozz.html

TS:   String(42)
来源：http://dali.yonumen.top/Article/details/gt2sqeymbwn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2wsrdplcf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npdfwupf.html

Ruby: 42.to_s
来源：http://dali.aibaodan.cn/Article/details/gt2sohavhfj.html

C#:   42.ToString()
来源：http://dali.zhengqikj.top/Article/details/gt2ivfptber.html

[A08] 取整与四舍五入
来源：http://dali.xziqi.cn/Article/details/gt2avplfmyf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gt2iwevybwx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tianlin.xyz/Article/details/gt2wyupepeo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2nxtwpewy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emkqnnsq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2ekjxgtot.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2ngnllqbs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jianghu66.top/Article/details/gt2vwirbvhx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gt2auogmqfm.html

[A09] 绝对值与最大最小值
来源：http://dali.wangdashe.top/Article/details/gt2himlwfyk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2qttlfezs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2msysjujy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aakbpvax.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ocuygaru.html


<!-- 参考信息 -->