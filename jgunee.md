代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sufxvd.cn/Article/details/gtezzfzkzh.html

JS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gtzlggpikt.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gtjxaufokz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.havefunace.top/Article/details/gtjsixzprx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhixingplan.top/Article/details/gtbskfpeao.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtvztqhnnp.html

C#:   $"Hello, {name}!"
来源：http://dali.316326.xyz/Article/details/gtclwhpqel.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xziqi.cn/Article/details/gtdjspfjdh.html

Py:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtznifocil.html

PHP:  "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtgqrrefwh.html

JS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gthskseyuf.html

TS:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtpkwsehpz.html

Java: "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtahgjkmdw.html

Go:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtegconnjr.html

Ruby: "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtgrlfdanq.html

C#:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtqmrcywwf.html

[A14] 注释写法
来源：http://dali.guannengcc.top/Article/details/gtharjmjpm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shuidangran.top/Article/details/gtfdpmltnp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtawbhhoub.html

JS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtgigykdpy.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtmtjvxxqd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xuanzx.com/Article/details/gtearfotbj.html

Go:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtajltyfxc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cheryme.top/Article/details/gtjfvylcnk.html

C#:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtfbtwcruv.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtragsbdpw.html

Py:   value = data or "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gtnrbgymzf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtbqatyibu.html

JS:   const value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gthuvtexej.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnomsbpx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.aibaodan.cn/Article/details/gtkeyanleb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sxryk.cn/Article/details/gtdxkrotfo.html

Ruby: value = data || "默认值"
来源：http://dali.nwbrower.top/Article/details/gtbdwzkrao.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtldecsjqw.html

[A16] 真假值判断规则
来源：http://dali.smart0.xyz/Article/details/gtkyasivlu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtgkdjvyzn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cqqwz.cn/Article/details/gtjpdcbhff.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yonumen.top/Article/details/gtshvaogbb.html

TS:   if (!x) {}
来源：http://dali.yanxiufei.cn/Article/details/gtteqjsumq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ppjwa.cn/Article/details/gtllylyfyj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jlsjyb.cn/Article/details/gteuexsppb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pycfn.com/Article/details/gttzyzgwaw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cucudq.cn/Article/details/gtwrfoimrs.html

[A17] 位运算
来源：http://dali.chenzaomai.com/Article/details/gtjwowuyhu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtvbuekvez.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yongpay.top/Article/details/gtdbbrqtvo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtrdcnqunf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtqpzpjvhz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtkujnzbcq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtzhbwihxd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtfggglkrg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtzngdflnt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.pengpengdd.cyou/Article/details/gtixbmozhd.html

Py:   ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gtqhhuawgo.html

PHP:  ord("A"); chr(65)
来源：http://dali.xinyue.icu/Article/details/gtglxxendq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjdvduuc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gtbustraum.html

Java: (int) 'A'; (char) 65
来源：http://dali.daxiang520.top/Article/details/gtvbjmdrxx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yvedp.cn/Article/details/gtsaoajssd.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenjidiqi.icu/Article/details/gthusfrdrs.html

C#:   (int)'A'; (char)65
来源：http://dali.sufxvd.cn/Article/details/gtkrxrzcva.html

[A19] 交换两个变量
来源：http://dali.hnqzz.top/Article/details/gtzhexeuhw.html

Py:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gtqgwcgisl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gtrdxgwecf.html

JS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gtbgzodbuu.html

TS:   [a, b] = [b, a];
来源：http://dali.chenlongwang.top/Article/details/gtczvabaem.html

Java: int t = a; a = b; b = t;
来源：http://dali.bjfxy.top/Article/details/gtooajgsbw.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gtbunhdryn.html

Ruby: a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtycvleqlh.html

C#:   (a, b) = (b, a);
来源：http://dali.chenlongwang.top/Article/details/gteizuaumg.html

[A20] 读取标准输入
来源：http://dali.9152youxi.cn/Article/details/gtyoiwrxsn.html

Py:   name = input("请输入：")
来源：http://dali.redwolf501.top/Article/details/gtmeygduov.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.birdmap.top/Article/details/gteiegpskp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cashguo.top/Article/details/gtmphpsqbd.html

TS:   // Node.js：readline 模块
来源：http://dali.gogol.net.cn/Article/details/gtoqlhtyja.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gtqflcjovk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuanzx.com/Article/details/gtnansaftb.html

Ruby: gets.chomp
来源：http://dali.yuxming.cn/Article/details/gtddleqffi.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gtlzwmortn.html

[A21] 保留指定小数位输出
来源：http://dali.xinyue.icu/Article/details/gtbfqwmzso.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yonumen.top/Article/details/gtwreysstg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtrgcuxyoa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtshqmbebg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtarfmzrlh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtxcxettkg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtppaqgkpw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gtgtuziafn.html

C#:   3.14159.ToString("F2")
来源：http://dali.jinghuilouyu.cn/Article/details/gthqblyvzn.html

[A22] 获取字符串长度
来源：http://dali.sxryk.cn/Article/details/gtijilrryg.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdppophpn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxuanxn.top/Article/details/gtzhuzkqgs.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gtyfwfpvme.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gtgknwqnwd.html

Java: s.length()
来源：http://dali.chenlongwang.top/Article/details/gtzaaaermj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.wangdashe.top/Article/details/gtmsfdnoto.html

Ruby: s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvkdexyk.html

C#:   s.Length
来源：http://dali.yuxming.cn/Article/details/gtgqdrvcdz.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtnyjxpdim.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtxojmniig.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cdnleiting.top/Article/details/gtpvtxayau.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtkjqpmlpb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtsosbpcjx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtivophhgz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yvedp.cn/Article/details/gthwlbkien.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.316326.xyz/Article/details/gtpxlkheii.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yangfankeji.com/Article/details/gtlgyoqlfa.html

[A24] 去除首尾空白
来源：http://dali.chenjidiqi.icu/Article/details/gtfapcrphy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.mhx1999.top/Article/details/gthulmwdnf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.feifeiyinyue.top/Article/details/gteqgdhhnk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtuvbvmmkm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtarfdibkr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ivvv.top/Article/details/gtnyghozyi.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhengqikj.top/Article/details/gtsdbvrybn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gtbektvisv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sysykeji.top/Article/details/gtzmbqhoap.html

[A25] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtbvdjbtid.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhoulong.xyz/Article/details/gtgzopvrrw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.havefunace.top/Article/details/gtjtwfzmhf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtmyljzzxq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtbdvhurvb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwbuudei.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtjqzrasjq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.birdmap.top/Article/details/gtcejqliga.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtmfuxdrmm.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gtsyrgmfsx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtvmcotkpn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hywenlv.cn/Article/details/gtwxehwcng.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cashguo.top/Article/details/gthkzlgevb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daxiang520.top/Article/details/gtjnneuchg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtlyxeyazt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gtbwovmfke.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtlfjgdine.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gtppkjwwcn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvirksjhs.html

B. 流程控制
来源：http://dali.chenzaomai.com/Article/details/gtofkbrxpa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtulrievyb.html

[B01] 条件判断 if / else
来源：http://dali.chenjidiqi.icu/Article/details/gtfqtsxnla.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gtbulgcbwe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.redwolf501.top/Article/details/gtkmozgste.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtcfgzoixv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtceybosne.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtrrkcifwc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.0kj1m.cn/Article/details/gtxoamljaj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yonumen.top/Article/details/gtvzttwyig.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtpcpsygeh.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtuycoroup.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cheryme.top/Article/details/gtozvjujts.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.havefunace.top/Article/details/gtbcbdzjnd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtnzcvenod.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtvhixhgfg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtcqtxzknt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gotoacloud.top/Article/details/gtraxqcqnk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxinkj.top/Article/details/gtpdiisnpn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtcblplodm.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gtyfuczsbk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtnmtojaat.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtuovrujfy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtdscvcgjz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtxoaabrls.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtugycmxeg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskpcgtfp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hfpthk.cn/Article/details/gtbpjjqnza.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtfozpjttx.html

[B04] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtpdbcfgmg.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gtxoxftocr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqclajhka.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtpofcfcyx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtburcdksw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gtvvjxrofa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fengsongda.top/Article/details/gtgsewqdxk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gtswrefuuf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daria6918.cn/Article/details/gtwpkdsolh.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtjhbusmoc.html

Py:   for item in arr: print(item)
来源：http://dali.yongpay.top/Article/details/gtnrqtfnkx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigufen.top/Article/details/gtnxenumcn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.andypj.xyz/Article/details/gtqitsknon.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtcpttxwzw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dashuyun.cn/Article/details/gtqotsqnmb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gtzxgjhqii.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hfpthk.cn/Article/details/gtfczuhdis.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtyagvkyqw.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gtmgxecmbd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gtrlkpmdcb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gthazvztfx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gthvtthymg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gtbtlajkxa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tanke756.top/Article/details/gtskffofkq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxuanxn.top/Article/details/gtzvfnyngv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtwutvwdhx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gtwpcwkmst.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhvhebqx.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258888.top/Article/details/gtqdlpdxqb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hfpthk.cn/Article/details/gteahugnkb.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtwyydjrwn.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtykarhtan.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtslpyfzql.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.snrcjt.cn/Article/details/gtmbfazigy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gthrmupisu.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtlhmdjscx.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gtkgeajkvk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gtvwfyfyaa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfffnsaxe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtytvmdfbu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtrfzdinds.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtyebvenkw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtcrwipcvt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gtoyxasivm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtxirokmwy.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gtlpgjxwzp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gtmrvmcfdt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtktfqoofh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtqhdfifra.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtbfsrifuk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtgrwjmgrn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtwbenjumx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gtwcocriyp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtavdlguxv.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gtspowkmdf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gttuwmobnv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yangfankeji.com/Article/details/gtjizwobzi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtnxleoeha.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtbnhdwlpy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gteskkbdhg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtprtngqau.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gttsjtgtfg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtjcicxsks.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gtqfinhcup.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gtlvnfaneh.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gttagfeaut.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtydcucxon.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtnbzqovgc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtobrepgiv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtaxcaxmgp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtmfvyhqnc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtpclxedtq.html

[B12] 跳出多层循环
来源：http://dali.c1oappe.top/Article/details/gtssljvmls.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gtnsddhvhu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzygjexqi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtzgvljkpt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxywwrxx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtncznzlgr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtqwdwynmj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gttavvokfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtrnffngxt.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtgnjsahcz.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gtoemwqhsg.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmwfbgtu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gthmoleemj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtnjpswykk.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtyulhpjru.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscgwhgre.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtmrhrflpv.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtgohvzfun.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gtueixrgys.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gtdpyfixdq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ehwqpu.com/Article/details/gtfiyyokhf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtfbmrgiph.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtshjzebsv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtzaowglli.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtgncrrxca.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gtsokadkcf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtjtjavekd.html

[B15] 布尔运算与取反
来源：http://dali.chenzaomai.com/Article/details/gthgatclld.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gturzcxyme.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwgcgzxu.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtwrnmbgfa.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtbdkgfvme.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtwzqyqnrj.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtsycupisk.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxigegvg.html

C#:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtoxkpehok.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gtuofuduwe.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtpqpjalim.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtbzaexhdh.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekapisew.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtjbexhehk.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtkpnofvav.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtkbfjarcf.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gtapxehptp.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtqtzfavqw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkbnmxzgv.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtlgglafjn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcjbtoith.html

[C01] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtpuplatwj.html

Py:   def add(a, b): return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtoowpzrqk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtxapuvcpd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtptrdkplj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gttkcxsazo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtzzwzlcfu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gtivlatpqc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtqjnyrdgl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtdutpclwc.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtfugcjhdz.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhybyycp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtljpmpslm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtcgcuolys.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtuxjqwnqg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbfvcilx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtmicmpmnl.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtfikdabjt.html


<!-- 参考信息 -->