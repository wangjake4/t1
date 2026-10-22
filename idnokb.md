代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yueranfly.top/Article/details/gtolxpllvx.html

Ruby: "Hello, #{name}!"
来源：http://dali.xinyue.icu/Article/details/gtywvvowqk.html

C#:   $"Hello, {name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gtgwjpegfz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gtwttrdpzy.html

Py:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtroiztwtz.html

PHP:  "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtfvugbtda.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtqmnbkzlg.html

TS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtlyrwrjwx.html

Java: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtjtyfgxxo.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtjnpzdzjr.html

Ruby: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtotqakivd.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtvhugthkj.html

[A14] 注释写法
来源：http://dali.jqgfzy.top/Article/details/gtidxgsxep.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.haohaochexian.top/Article/details/gtshgauunn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gthkuwnlwq.html

JS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtfcsyryzl.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtzhtnlijx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbaluhry.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtjvsand.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzucznnl.html

C#:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gtkwnjvffp.html

[A15] 空值判断与默认值
来源：http://dali.gaohongyu789.top/Article/details/gtvnxgulnm.html

Py:   value = data or "默认值"
来源：http://dali.jyoumei.cn/Article/details/gtqcvmoguh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtpuhnykep.html

JS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtfetannxy.html

TS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtiaxndjrd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cucudq.cn/Article/details/gtqvnvfter.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xuetiantiany.cn/Article/details/gtddkoarsy.html

Ruby: value = data || "默认值"
来源：http://dali.zhixingplan.top/Article/details/gtjunmbiew.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjupuizg.html

[A16] 真假值判断规则
来源：http://dali.bjfxy.top/Article/details/gtwdsvpwvd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hfpthk.cn/Article/details/gtfpygucog.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuhpgaeb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daria6918.cn/Article/details/gtodmbqdxs.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gtkqmfmayz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gotoacloud.top/Article/details/gtizphxtse.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.dashuyun.cn/Article/details/gtbvqbynay.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zycfv.cn/Article/details/gtdxsixlvw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.redwolf501.top/Article/details/gtntsnrzsy.html

[A17] 位运算
来源：http://dali.wangshuangyany.cn/Article/details/gtwxtgytvp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtqvngqzyp.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmueaslzp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gthxysaagc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtztpyqtwu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtywihhwpe.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtjnbczk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtfeuwoqom.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtiyynanev.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtfffzusxa.html

Py:   ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gtftkoobgz.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gteixlltlu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gtebtxjwpd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtissbenfp.html

Java: (int) 'A'; (char) 65
来源：http://dali.feifeiyinyue.top/Article/details/gtgjzwmiur.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cucudq.cn/Article/details/gtmtywfvgy.html

Ruby: "A".ord; 65.chr
来源：http://dali.dianchejie.cn/Article/details/gtguudorce.html

C#:   (int)'A'; (char)65
来源：http://dali.quarkkingdee.top/Article/details/gtxaexudor.html

[A19] 交换两个变量
来源：http://dali.hammf.cn/Article/details/gtchrladwd.html

Py:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gtolccramg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aibaodan.cn/Article/details/gtleqnjvwf.html

JS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gtxcejnius.html

TS:   [a, b] = [b, a];
来源：http://dali.yuanzhike.top/Article/details/gtmikdocda.html

Java: int t = a; a = b; b = t;
来源：http://dali.tian-w.cn/Article/details/gtwbccuemt.html

Go:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtuogeeesm.html

Ruby: a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gtfrnvgrwb.html

C#:   (a, b) = (b, a);
来源：http://dali.wangshuangyany.cn/Article/details/gtzqohsbvx.html

[A20] 读取标准输入
来源：http://dali.shzxlz.cn/Article/details/gtmrakxwxv.html

Py:   name = input("请输入：")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaehdijul.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhixingplan.top/Article/details/gthidqacws.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.andypj.xyz/Article/details/gtnbrixhit.html

TS:   // Node.js：readline 模块
来源：http://dali.aizwys.cn/Article/details/gtanntqsgn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.guannengcc.top/Article/details/gtvxsrqgjj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenlongwang.top/Article/details/gtctkuqfhj.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gtfoqnwemf.html

C#:   Console.ReadLine();
来源：http://dali.mhx1999.top/Article/details/gthzcvuqgp.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gtvpvjbfdl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jiagoushi.top/Article/details/gtxlgakbqa.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gtbnuguflc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtcgefaqvl.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtecbfkabr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtrsgscevm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyotwbzm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtccziuxoz.html

C#:   3.14159.ToString("F2")
来源：http://dali.svipenyu.cn/Article/details/gtadqchpen.html

[A22] 获取字符串长度
来源：http://dali.aizwys.cn/Article/details/gtklfhzcmt.html

Py:   len(s)
来源：http://dali.dashuyun.cn/Article/details/gtfxkvjtzm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfjlwjqp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnxiangtu.top/Article/details/gtymxyzzrt.html

TS:   s.length
来源：http://dali.yonumen.top/Article/details/gtanicjyvy.html

Java: s.length()
来源：http://dali.ivvv.top/Article/details/gtepsmsmnp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yvedp.cn/Article/details/gtpgmcgzpy.html

Ruby: s.length
来源：http://dali.sxryk.cn/Article/details/gtochdvprj.html

C#:   s.Length
来源：http://dali.chenlongwang.top/Article/details/gtqxfihnqu.html

[A23] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gteuqbnqnd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtamailpny.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj20258888.top/Article/details/gtzgithvkq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtvpdbhshz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gtixgulcmm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtktiocphd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.havefunace.top/Article/details/gtvtuawlkj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtvzeerxht.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigfzy.top/Article/details/gtobbbujqa.html

[A24] 去除首尾空白
来源：http://dali.yuanzhike.top/Article/details/gtvgkfjpdh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenzaomai.com/Article/details/gtrhdpkczq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.andypj.xyz/Article/details/gtxbegddag.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtlhyhzuvr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtbkgfbuuf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daxiang520.top/Article/details/gtcowfsvqm.html

Go:   strings.TrimSpace(s)
来源：http://dali.jianghu66.top/Article/details/gtkyxrrrdz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xylfe.cn/Article/details/gtfpxhnddz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.andypj.xyz/Article/details/gtaahsqehw.html

[A25] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtnvcqtizi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cqqwz.cn/Article/details/gtmjiozkuq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zdqjudy.top/Article/details/gttwixajkw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gtzfgkkbzd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gtyuqmmxkv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgfzy.top/Article/details/gtqwwlhhxo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtjvnkaiav.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yangfankeji.com/Article/details/gtxftdamul.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtdnfvamtp.html

[A26] 类型转换总览
来源：http://dali.c1oappe.top/Article/details/gtacgpxtfz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangtech.top/Article/details/gteycpyzty.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xylfe.cn/Article/details/gtrnqcaznj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shuidangran.top/Article/details/gtcxrkxooa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yanxiufei.cn/Article/details/gtarpzyxdk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sufxvd.cn/Article/details/gtmsnfliqo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jiagoushi.top/Article/details/gtrfrrzvol.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gtylhlujsb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gtvsiedknm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbtkgxdsq.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gtdyjkkktx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvlmtptcf.html

[B01] 条件判断 if / else
来源：http://dali.ehwqpu.com/Article/details/gtwillmoen.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gthtjkfvsx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gtmccpfulk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtsdniywuq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtsvoidqut.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtgefhymae.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gotoacloud.top/Article/details/gtzmwmwlab.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gtlfepznaj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtlynprdrn.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtqrjruxts.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gtskzrdlzk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmosspbo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtxftluoel.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gttrejtjue.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtbcepulsx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gtvboiiybi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gotoacloud.top/Article/details/gthqfyawqq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtifoxurap.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtytpwydbh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yvedp.cn/Article/details/gtxuvxbqjd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtjhinbrnd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtwkfkdtlm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtfjtuujyw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtmrlnijto.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtrlkerejn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtvldeqrks.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtwhwahhyw.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtmnviszlh.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtfzhvytlb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.snrcjt.cn/Article/details/gtpyavzmkf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtallgnorl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtjsrjknzt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.316326.xyz/Article/details/gtlacchxvk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gthugwefqs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gtkdoirmib.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yonumen.top/Article/details/gtgzgztenl.html

[B05] 遍历数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtfqnfwfsf.html

Py:   for item in arr: print(item)
来源：http://dali.guannengcc.top/Article/details/gtxhltjyww.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gthvagzxvo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtzxpnzwjt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtymneusen.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cucudq.cn/Article/details/gtjmvpkgrt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sxryk.cn/Article/details/gtffookvre.html

Ruby: arr.each { |item| puts item }
来源：http://dali.kuanghao11.cn/Article/details/gtkcvcxwei.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gtfktetqxl.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gtxybgqkfa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gtntzxunql.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gogol.net.cn/Article/details/gthvnefqvc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtqbzzyhlb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtvanjwxpz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskoehpbl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gtzbkwwdzp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtlkrwwhfn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtgzpyfnsa.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gtycstzabe.html

Py:   while i < 10: i += 1
来源：http://dali.andypj.xyz/Article/details/gtbumlelcw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sufxvd.cn/Article/details/gtgujxssqw.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtgkjevdlj.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gthqgbdsqa.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtbqnygqpa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gtxvteznra.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gtedxrxhpr.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtuzghucce.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxinkj.top/Article/details/gtovzfqjtb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gtamdfvhyv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtaeqhmdsn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtxeujxqdy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtopjmypab.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtiobxkqjl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gtzxjhmokc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gttsokxucp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtguskfyyu.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gtwfqmkeed.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhixingplan.top/Article/details/gtqysojwkw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtxjxuhhgt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaimsalf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtcgqkfmac.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtzxnmmkrm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtvlomoypx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daxiang520.top/Article/details/gtwxlgggeu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtwvktpbyd.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtugweuqtz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gtgomxpysm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gtqmhddory.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gtnylxrblu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gtbcwlxqcj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shzxlz.cn/Article/details/gtoiuolfzp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtakuwgqyj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtnjvpdono.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtrgjkvzov.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gtaskrlnlu.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtmqbixfaa.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gtxphyjxuc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtxychkpqe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtmbofpvmx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtoktoebjt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtpfwbfbof.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ppjwa.cn/Article/details/gtlsrcykey.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gtwycqcrwe.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtnnaakyxq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gtsmfgxceq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtgrlfobhn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtycjwbwgr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtcxbtofkh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmrluvce.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gtvouietnz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtaiseslgx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gtewlofvdc.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtmjdjpnjb.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtjbexrjgy.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gtdeonuonc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtxbccmzuj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtzbuwalag.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtuuhifkon.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtbepdgsjv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcspqdijd.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybpjkufx.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtglwjuacc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtbhgfkupo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nwbrower.top/Article/details/gtuqabloid.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtmnxwzbdr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtmueqcoii.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtkgpvoubp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gtcmozpbqp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gtrnebogfo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtxgdgfuqq.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtwykfbewd.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gtcmkizvdh.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gtipfwemxt.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtzixfggaq.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtvyozevic.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtezgnamif.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtoqmwefqd.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtarbrduwu.html

C#:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gttuglwkhy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtgzxdiizz.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtosnnlunj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtorcgznte.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtzkyvczgd.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtukzhtcjg.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtotoshfhw.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlekjfpra.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtifwwfwhg.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtwlsyrpfr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqfatfcwr.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gtzvbdkqys.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjomeemov.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtrtsgnrjt.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtoljwtjpu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gttqgmzuax.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gttcwnwbpa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtdlzvrqvt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtjhermqdj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtjqsxzgbw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowufzuyi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtqjdszspw.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtnidfgxna.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gtjozzugdh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtgtdkslal.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtyyoehlpd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtbeirajvb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gtkxhieycj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gtuqwptqkf.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtkgrntvro.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gtznezjgqk.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtznbcueqy.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtnpvdetjx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtcvqwgbik.html


<!-- 参考信息 -->