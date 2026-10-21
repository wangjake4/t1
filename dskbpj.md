代发 wailian999

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.snrcjt.cn/Article/details/gtucajtvlz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gttfwfrdxl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.9152youxi.cn/Article/details/gtrrdamcwz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtwcogoovd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtunrtlnth.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.mhx1999.top/Article/details/gtywhelcoy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtcnpewzkt.html

[A09] 绝对值与最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtdnackhma.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtopxmkobo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtwuxbqmrs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gttrlkzenk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gthcyifjdb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtjvajwvzk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuetiantiany.cn/Article/details/gtlnenuxta.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yangfankeji.com/Article/details/gtrkogcgar.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtsliezxgc.html

[A10] 生成随机数
来源：http://dali.chenzaomai.com/Article/details/gtqykiplmc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinqigufen.top/Article/details/gtyxslveng.html

PHP:  random_int(1, 100);
来源：http://dali.zhoulong.xyz/Article/details/gtvoxpihzo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtvtkstqbv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtzanzirqm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.0kj1m.cn/Article/details/gtiegehyxp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuanzhike.top/Article/details/gtjomzmlco.html

Ruby: rand(1..100)
来源：http://dali.fengsongda.top/Article/details/gtsseamxtk.html

C#:   new Random().Next(1, 101)
来源：http://dali.iojbl.cn/Article/details/gtzpeowlhn.html

[A11] 条件表达式（三元）
来源：http://dali.9152youxi.cn/Article/details/gtynavwiwd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tian-w.cn/Article/details/gtdqbvefih.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtwpdhhmmg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtsnyelnag.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gtvrujknhv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtdbcgkubt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhongyouzk.top/Article/details/gtnbgdqdsp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtxsykoahd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtxqcngsxc.html

[A12] 字符串插值 / 格式化
来源：http://dali.yueranfly.top/Article/details/gtmzfhgvko.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shzxlz.cn/Article/details/gtwhnabobp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jlsjyb.cn/Article/details/gtusddkhut.html

JS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gtlwdlcexn.html

TS:   `Hello, ${name}!`
来源：http://dali.gaohongyu789.top/Article/details/gtkkczjldw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgufenzy.top/Article/details/gtldimscmp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dashuyun.cn/Article/details/gtfimfdwuu.html

Ruby: "Hello, #{name}!"
来源：http://dali.shuidangran.top/Article/details/gtoqtkmjgw.html

C#:   $"Hello, {name}!"
来源：http://dali.quarkkingdee.top/Article/details/gtzqwdcqqp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gaohongyu789.top/Article/details/gtjkbwpxul.html

Py:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtaomvjmiy.html

PHP:  "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtrqeonubs.html

JS:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtjjdppfyu.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtlxkoytdm.html

Java: "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gttmwlbmuf.html

Go:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtkwrjoswo.html

Ruby: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gthvxkdyqh.html

C#:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtsrwrgwtu.html

[A14] 注释写法
来源：http://dali.nwbrower.top/Article/details/gtmerkyurj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjitlkme.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtlvwdpzfg.html

JS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtqxtfzfqi.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtxyipikxn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.meibo888.top/Article/details/gtaalrbeob.html

Go:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtxqpbknaf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuanzhike.top/Article/details/gtlwadrbnh.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtlmuyupvp.html

[A15] 空值判断与默认值
来源：http://dali.fzhhl.top/Article/details/gtstgbofpp.html

Py:   value = data or "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gtzckoybrd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtaazxwwlu.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtjtjdhuzq.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgniqbqk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cucudq.cn/Article/details/gtaeqfxqku.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.snrcjt.cn/Article/details/gttbgpashx.html

Ruby: value = data || "默认值"
来源：http://dali.yvedp.cn/Article/details/gtqgroytlc.html

C#:   var value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtbvzkcfzm.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangtech.top/Article/details/gtialnuehy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtqcghmgtq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhixingplan.top/Article/details/gtaedzqqvk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.birdmap.top/Article/details/gtthpmmibg.html

TS:   if (!x) {}
来源：http://dali.jinqigfzy.top/Article/details/gttdynmrmh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cashguo.top/Article/details/gttlvqpyfk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigufen.top/Article/details/gtuckzpnhm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigufen.top/Article/details/gtfwluvmvr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jianghu66.top/Article/details/gtejwrxdch.html

[A17] 位运算
来源：http://dali.sysykeji.top/Article/details/gtbaozstzd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtnylgcvfe.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtiahbfnoa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gthmlxzskj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtngazvbga.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtjtdoczsc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtugrlruss.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqonqooh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtgwextjme.html

[A18] 字符与 ASCII 码互转
来源：http://dali.smart0.xyz/Article/details/gtkshfsuzw.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gtwcgtjkpy.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gtensvmeqp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yanxiufei.cn/Article/details/gtjzokngvd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtvdwcqntr.html

Java: (int) 'A'; (char) 65
来源：http://dali.shuidangran.top/Article/details/gtuzaxdmsl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ppjwa.cn/Article/details/gtifkgdkxu.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj20258888.top/Article/details/gtyczkmjco.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gtqbvmmzvg.html

[A19] 交换两个变量
来源：http://dali.nanxuanxn.top/Article/details/gtjbzyethb.html

Py:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtgopommjd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gzhubu.top/Article/details/gtghseswtg.html

JS:   [a, b] = [b, a];
来源：http://dali.tianlin.xyz/Article/details/gtrgeymovk.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlnlseod.html

Java: int t = a; a = b; b = t;
来源：http://dali.xylfe.cn/Article/details/gtdyltumyy.html

Go:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gtlxiayuwr.html

Ruby: a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gtoocldcgl.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gtxsmrvojk.html

[A20] 读取标准输入
来源：http://dali.hywenlv.cn/Article/details/gtiltslrjh.html

Py:   name = input("请输入：")
来源：http://dali.kuanghao11.cn/Article/details/gthxxzqpru.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yvedp.cn/Article/details/gtpfdhajjc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gtunwtjrmo.html

TS:   // Node.js：readline 模块
来源：http://dali.cucudq.cn/Article/details/gtlrwdwgbx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gtuayhepnn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aibaodan.cn/Article/details/gtscuzirlm.html

Ruby: gets.chomp
来源：http://dali.ehwqpu.com/Article/details/gtxxoytymw.html

C#:   Console.ReadLine();
来源：http://dali.nanxuanxn.top/Article/details/gtekjdxhdo.html

[A21] 保留指定小数位输出
来源：http://dali.snrcjt.cn/Article/details/gtminlszoz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgufenzy.top/Article/details/gtlgsapujn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtsxlrjecx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtwtcvayuv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtmmseltbx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtegljabme.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtqtqqguem.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkvkdrvh.html

C#:   3.14159.ToString("F2")
来源：http://dali.meibo888.top/Article/details/gtzolqtnsq.html

[A22] 获取字符串长度
来源：http://dali.wangdashe.top/Article/details/gtvedbiwcd.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gttwylqslw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cucudq.cn/Article/details/gttidxyflz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jianghu66.top/Article/details/gtrhnhqthz.html

TS:   s.length
来源：http://dali.fengsongda.top/Article/details/gtnnepvwfp.html

Java: s.length()
来源：http://dali.0kj1m.cn/Article/details/gtrkqdasoi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fengsongda.top/Article/details/gtjsgfmfgp.html

Ruby: s.length
来源：http://dali.nanxuanxn.top/Article/details/gtpqfsreei.html

C#:   s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtyyaxedas.html

[A23] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtsjnmxdsh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqinrbmke.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aibaodan.cn/Article/details/gtexvodutb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtqtmkknim.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtltngfshb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtcetedgbj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zdqjudy.top/Article/details/gtujwcrcog.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtkpcofnbv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cdnleiting.top/Article/details/gtxmxofwms.html

[A24] 去除首尾空白
来源：http://dali.jinqigfzy.top/Article/details/gtfozevtge.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yueranfly.top/Article/details/gtihyhkyux.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfttumyus.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gtybsareea.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gtbrhogglw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinqigufen.top/Article/details/gtqymzeawv.html

Go:   strings.TrimSpace(s)
来源：http://dali.cashguo.top/Article/details/gtquuztsuo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.feifeiyinyue.top/Article/details/gtcwfspcah.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtpusklyuw.html

[A25] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtnuigcvqq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sweek.top/Article/details/gtndtxmpdy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.redwolf501.top/Article/details/gtffnhecpm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtixcnexkt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtvzprvkeo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.iojbl.cn/Article/details/gtauuxxvcw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtasqjphcx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yanxiufei.cn/Article/details/gtjkbacksp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gtmprokerx.html

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gtytjfzbow.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxuanxn.top/Article/details/gtwwrxdjwl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aibaodan.cn/Article/details/gtxddicrak.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dianchejie.cn/Article/details/gtcmikknrp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aibaodan.cn/Article/details/gtreamdadw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtqjhrfxav.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjpgcujj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtvdokkbzm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sweek.top/Article/details/gttveekahk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzbktokqe.html

B. 流程控制
来源：http://dali.hnqzz.top/Article/details/gtwiyxbupn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttcenseiy.html

[B01] 条件判断 if / else
来源：http://dali.aizwys.cn/Article/details/gtfhhmptgy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gtkpbeuvqe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwkhqves.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtkvgiepan.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtnltrklua.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtmrvtdgjk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.0kj1m.cn/Article/details/gtntcsvwia.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gtmycsepgy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtdepniijd.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtqgfzvhpk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqqbinla.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaxmubgy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtoygtljdz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtqtwlzhph.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtrcawvuyp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuisavyy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.haohaochexian.top/Article/details/gtsfjizzuz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtcwhlgyvt.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gtqocmnfva.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yvedp.cn/Article/details/gtmbdnavvh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtulglqppe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzukikwaa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtgarxjwqk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtsvotpjxo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gterdaxvlt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zycfv.cn/Article/details/gtijaghmrd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sxryk.cn/Article/details/gtmchsrxen.html

[B04] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtqlafnbnl.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258888.top/Article/details/gtjidtzqys.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guowangkeji.top/Article/details/gtszzferiq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtxpuekcbu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gtlyrxtveh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sufxvd.cn/Article/details/gtyyjkgyxj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenlongwang.top/Article/details/gtggwvulug.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gtnswqxbxt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gtbvkzszuu.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzcsszli.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gteflsqihq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gotoacloud.top/Article/details/gtwcfoobad.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gthfqnbpkf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtrqukxues.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gtzuoepaod.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gtnwwepowj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gtwwjjyfmo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnqzz.top/Article/details/gttdwpahhq.html

[B06] 遍历字典 / 对象
来源：http://dali.hongshengwenyu.top/Article/details/gtgatpyaiq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gtctzoaxrp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pycfn.com/Article/details/gtosdcpcpp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtdkvhiedl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtholuaqpx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gtsptkokdl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtbrldknyy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyqvrbba.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzkbteyk.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gtsqsdlvwu.html

Py:   while i < 10: i += 1
来源：http://dali.aizwys.cn/Article/details/gtjvwokpfq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrrwablzo.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtoeujmatr.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtatewkwdu.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtuqnhcrfd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gtzkqqmqzl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrnlyijz.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtnqveioah.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtxbjuottx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtttcrcrgp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hfpthk.cn/Article/details/gttfxrwfjg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtdwmorvtz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtiuopwrpr.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtsgjnyczp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtkjcjpgrf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gtlkzqbjoj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtjxmmorzs.html

[B09] break 与 continue
来源：http://dali.zhiwuduotai.top/Article/details/gtmjmwzmdm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhixingplan.top/Article/details/gtzqwhvqhe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtzrzwnqfm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtwpfrycte.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtgjtzfyjm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhtamhfd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtfidbthrq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gtsisiezta.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtkmflhayd.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtdykeyzmi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.snrcjt.cn/Article/details/gtttspkykg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aibaodan.cn/Article/details/gttxzzxaas.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtifhyzhno.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtaukjjvoj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xinyue.icu/Article/details/gtiagpaynb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gtpveftiwt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gtdllxnkss.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gtaogbelxn.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtnkaldkhg.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gtsxxzwsbb.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gtwlhahtqd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtquwtxjol.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtobnffxjj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtojpnnded.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtjgoakmgt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gtkiqtnkyb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtuqluafuv.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gtvttjiiei.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gtlpqjprcc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtcwunegud.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtdtkegdqe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtszpzafoi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtbtixaobn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gtmpjzcfxf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gtjuegxejv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gthynkqwoy.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gtyapjftqn.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtdruefzeh.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gteskruywy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtedetnxbz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtlbvzedne.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gtapgkunck.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gthxqzqxom.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gtonzurxgo.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtkzggdddj.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtdpykphtj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtbgzmoypp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtfwfzsmkv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtfaamnekl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtepjgvsti.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtdzmwgygi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gthvbjdenp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfomycsaj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtmpxomhyz.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtacexizlo.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtauahzezn.html


<!-- 参考信息 -->