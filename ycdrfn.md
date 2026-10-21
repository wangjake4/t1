代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtajvnzxpk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtaztbjyal.html

[A12] 字符串插值 / 格式化
来源：http://dali.9152youxi.cn/Article/details/gtvgulqdvm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gtltkcbnxm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dianchejie.cn/Article/details/gtbpirgnos.html

JS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gtvlntycrb.html

TS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtgygroozs.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.316326.xyz/Article/details/gtetjazeqp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aizwys.cn/Article/details/gtjsyphprg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhoulong.xyz/Article/details/gtubwylvpe.html

C#:   $"Hello, {name}!"
来源：http://dali.zhengqikj.top/Article/details/gtsyhqrjrj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cheryme.top/Article/details/gtabrndxrf.html

Py:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtnzekaqlw.html

PHP:  "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtxqqpdovb.html

JS:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtttdeaqus.html

TS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtjqzohpcz.html

Java: "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtlallzyxi.html

Go:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gttunzxofi.html

Ruby: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtmaywxwmy.html

C#:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtlqgmglwz.html

[A14] 注释写法
来源：http://dali.0kj1m.cn/Article/details/gtdonvolgs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxinkj.top/Article/details/gtzlmkmjby.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtghwpghph.html

JS:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtbivezrtj.html

TS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtzjwmiyho.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ydzc1.top/Article/details/gtyttwxagf.html

Go:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gttludschv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shangyingyoupin.top/Article/details/gtqztizemz.html

C#:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtruzhlyax.html

[A15] 空值判断与默认值
来源：http://dali.316326.xyz/Article/details/gtuwbbompn.html

Py:   value = data or "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gtqetiuzon.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtgzprgqqw.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtimbytikx.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtgolpvetm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.dianchejie.cn/Article/details/gtogtfkxpn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ybcxt.top/Article/details/gtbooacqbk.html

Ruby: value = data || "默认值"
来源：http://dali.cqqwz.cn/Article/details/gtqkvjeruu.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gttneobexj.html

[A16] 真假值判断规则
来源：http://dali.hfpthk.cn/Article/details/gtbinvvubl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.guowangkeji.top/Article/details/gtjfvnybfc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangshuangyany.cn/Article/details/gteykccemo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yvedp.cn/Article/details/gtbpgxakhj.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttaojoreg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhixingplan.top/Article/details/gtmascguca.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.fengsongda.top/Article/details/gtdfvhdrmb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigfzy.top/Article/details/gtakvhpdxb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtaitdwzmu.html

[A17] 位运算
来源：http://dali.gaohongyu789.top/Article/details/gtbjlcxcnh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtfdzlnocf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sxryk.cn/Article/details/gteyybvxan.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtxwdjqvgp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtqtsmnwhz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtcikdctfe.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gttbowpuwj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtxhyivadl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtbarlruna.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenzaomai.com/Article/details/gtixqxeaeo.html

Py:   ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtszjeexbp.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gtmadtzgpg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gttjjjtlxj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gtmktakhqo.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gtsgucupdf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ybcxt.top/Article/details/gtvubhcmms.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtpeegnmir.html

C#:   (int)'A'; (char)65
来源：http://dali.sxryk.cn/Article/details/gtrxtimues.html

[A19] 交换两个变量
来源：http://dali.redwolf501.top/Article/details/gtdelvdxvh.html

Py:   a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gttdxdheld.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xuetiantiany.cn/Article/details/gtlzyeqbjv.html

JS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gtazhgbiag.html

TS:   [a, b] = [b, a];
来源：http://dali.hfpthk.cn/Article/details/gtboizmgen.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhixingplan.top/Article/details/gtooouxvej.html

Go:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gthpapktqs.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtthrnepae.html

C#:   (a, b) = (b, a);
来源：http://dali.meibo888.top/Article/details/gthnzegfco.html

[A20] 读取标准输入
来源：http://dali.cheryme.top/Article/details/gtfkwdbkjw.html

Py:   name = input("请输入：")
来源：http://dali.yangfankeji.com/Article/details/gtflszskmn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigufen.top/Article/details/gtgmulmkih.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhengqikj.top/Article/details/gtcoliuaoc.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gtfsiptfdi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gtlcthedgv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daxiang520.top/Article/details/gtnleeyill.html

Ruby: gets.chomp
来源：http://dali.aibaodan.cn/Article/details/gttufswzjz.html

C#:   Console.ReadLine();
来源：http://dali.ybcxt.top/Article/details/gtahiyidrs.html

[A21] 保留指定小数位输出
来源：http://dali.fengsongda.top/Article/details/gtywiskdvy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cucudq.cn/Article/details/gtmxyevrpc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gthelqhuex.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtuxlzzlqs.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtnrblwarr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtbtgfxdrl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtmtdkijim.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtroypeaoo.html

C#:   3.14159.ToString("F2")
来源：http://dali.jinqigfzy.top/Article/details/gtbwoeuply.html

[A22] 获取字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtiqvoulve.html

Py:   len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtboteubwm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gtpjagfroo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zdqjudy.top/Article/details/gtnjcrzhle.html

TS:   s.length
来源：http://dali.gotoacloud.top/Article/details/gtrtsldkfg.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gtiyfampbh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ybcxt.top/Article/details/gthzvqhmar.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gthvvuenag.html

C#:   s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtfpdyhbdj.html

[A23] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtrghdbnwh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtkiiaytjg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hysaishi.cn/Article/details/gtyohezrsw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtyopukvyt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtuehpejuh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmzjgamk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.svipenyu.cn/Article/details/gtatjxjuji.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtkuullysb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cheryme.top/Article/details/gtegsnexdu.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gtivntfkcx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhengqikj.top/Article/details/gtektdmhql.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangdashe.top/Article/details/gtmcgrvgvb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtkzyukknf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gtrapgurbx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daxiang520.top/Article/details/gtmezwptfw.html

Go:   strings.TrimSpace(s)
来源：http://dali.yvedp.cn/Article/details/gtemqtufjw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hammf.cn/Article/details/gtnuyxzdfv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtrgvmiovb.html

[A25] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtijfuacns.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenjidiqi.icu/Article/details/gtvwjmwufc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuanzx.com/Article/details/gtokawzfht.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtbormujik.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gtjspkjbjc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhongyouzk.top/Article/details/gthlfgkqup.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gtjgygewxg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.iojbl.cn/Article/details/gtjmsngald.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtykawohyh.html

[A26] 类型转换总览
来源：http://dali.svipenyu.cn/Article/details/gtbzejsitn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.redwolf501.top/Article/details/gtrfdzjizq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jlsjyb.cn/Article/details/gthhrfwqsw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ehwqpu.com/Article/details/gtemacwexw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtuqzpprcl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtkguatdeh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gtyzhplktf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yongpay.top/Article/details/gtupqtgonc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtelkuonnp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfhpqoajb.html

B. 流程控制
来源：http://dali.nwbrower.top/Article/details/gtgbaegqix.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnpcjsclm.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gtiqbyycbw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gtzrpvindg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.meibo888.top/Article/details/gtjuvduclp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gttujhgaoh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtwveqyxcw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtjkararod.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtipbsdebb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtwiomyvcr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtdpdgwkbc.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtwwolhyqm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gtilvcgjxx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hywenlv.cn/Article/details/gtlqvnxwqf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtqvoljxfg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtfetoinoy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtnqwcyivg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtapwrpebs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gzhubu.top/Article/details/gtpmjcwmef.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtgneahfbz.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtqarxvrbe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jianghu66.top/Article/details/gtwfhxwcvd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gteeacgwwx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirptymbp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtthglbdsm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzzlpwbgd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtajucguhp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtkqegvmsj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hammf.cn/Article/details/gttpufjpzn.html

[B04] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtxnjghzjo.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtjwdnikfd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgufenzy.top/Article/details/gtzvjdrocp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gtrvttvkiv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiafboim.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gtcwgiaznr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoinlmksk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xylfe.cn/Article/details/gtkzfqopiq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gtbyoacxwu.html

[B05] 遍历数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtpwerduwj.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gtjkjvgjdr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hysaishi.cn/Article/details/gtnnkbtymn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtspkahxnv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtxdurewct.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtsrfubtzk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gtrgaemkcw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pycfn.com/Article/details/gtiwjdxyse.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gtumpmhobk.html

[B06] 遍历字典 / 对象
来源：http://dali.shangyingyoupin.top/Article/details/gtkeeujdtg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gtytxdkrhb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gtoizzurnt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtmgxsbsca.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtfsvgcuet.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gtuovgwwvj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtnozbmblr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtnzeqslea.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgflhzbwx.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gtbrhjefrt.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtiyglwytf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtwdeiyiko.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtsykurfbh.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gthgvvjfbv.html

Java: while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtehvyldnp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtorrcqhub.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gtsjdcdsnz.html

C#:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtqdyeifri.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgfzy.top/Article/details/gtjjfjbshi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gtjfaidkrn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtrfpfyudz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtamyorgdk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkjnfbiq.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gterzouooc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtfqsqkyrt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gtudiytmwt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtmiqdpblp.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gtugtamqxh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.havefunace.top/Article/details/gtzkhsdstb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtepwuougb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtgnmfjbqs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtkxpyvdrx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtngisgttc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtlrkjehlx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcsfxnxj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtachfaetp.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtnirskmub.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gtlhzruxfb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gtwahvyvat.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtkvnszboy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtbwljzled.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhoulong.xyz/Article/details/gtgikmvsup.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dashuyun.cn/Article/details/gtstnqutzk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gtgcrceolc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gtkotgngil.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtnhtfpwxb.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtfzzvdwuj.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtktnykawr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtpfajnlxb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gthrmloixv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gthdpgktws.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gtubfsoaap.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gthjjpglac.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ybcxt.top/Article/details/gtaghajjlo.html

[B12] 跳出多层循环
来源：http://dali.yanxiufei.cn/Article/details/gtfaguqfpn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtjjtrandd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtjbliitcq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtkkszyisc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtjldlkmdj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtoornupmt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gtpchgrglp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtfjxancok.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gtixtfupwk.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gtlkzobsgb.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gtiwdlevbw.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnibqejgr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtemohdfaf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtwlccqwcu.html

Java: x instanceof Number
来源：http://dali.ehwqpu.com/Article/details/gtioilerwo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gttdczajto.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjacqkkr.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtztkpkhxz.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gtuggsbzsu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gtzastlaft.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtxbbfkhyc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtfpuxppso.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtzzjghgfz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtrycpjypk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtolohplwy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtozbgifqj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gthqjwolht.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gtfnpgvmdg.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gtlqmzhvvf.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtjvuvkpyt.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gthgbiktyt.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiugtnnuf.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtosmyhbkn.html

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtnszphgfb.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtgrojghnk.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtpsgfibqd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtakkvxtsm.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtwkwnvksm.html

PHP:  if (!$data) { return; }
来源：http://dali.ppjwa.cn/Article/details/gtnnesjorm.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtiwuusucs.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtldnveiez.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtaklikmki.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gtgngrbwbt.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtflaggosr.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtpquvzffe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzsfslim.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovcbxbri.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdubmvzgh.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtbxkpvzdq.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gthxejxscp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkftituqp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrzhzozkd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtwqbqdqdz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtfnswcili.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtppqpnpgq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtayihiuxe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtbjziiwab.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtrnptgvsm.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtievteipx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjawfnbs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtxxvywwvo.html


<!-- 参考信息 -->