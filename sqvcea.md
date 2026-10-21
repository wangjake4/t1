代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.kuanghao11.cn/Article/details/gtrverzbba.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtiabvfcgv.html

TS:   if (!x) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkfybzame.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.smart0.xyz/Article/details/gtrwjrlwdo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj20258.top/Article/details/gtetockddm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhengqikj.top/Article/details/gtvhmgseyk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkbrsgryt.html

[A17] 位运算
来源：http://dali.pengpengdd.cyou/Article/details/gtmdawcfjy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtvlfrnacz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtpulytina.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtsghbxxot.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtzrfkmvbd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtgxkubyjq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsanhcgnf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtlltycclk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtkpbpmjwl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gaohongyu789.top/Article/details/gtygonmriv.html

Py:   ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gtlsjkzreh.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtyoktwqvh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yvedp.cn/Article/details/gtzimzhcos.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtukndbyyc.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenlongwang.top/Article/details/gtnbjuacoe.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daxiang520.top/Article/details/gtkhaxyhpt.html

Ruby: "A".ord; 65.chr
来源：http://dali.cashguo.top/Article/details/gtgtbrqecq.html

C#:   (int)'A'; (char)65
来源：http://dali.shuidangran.top/Article/details/gtsmbzoobl.html

[A19] 交换两个变量
来源：http://dali.zhiwuduotai.top/Article/details/gtotnhxrmv.html

Py:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gtqwowpkfy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.c1oappe.top/Article/details/gtlrbhhxbv.html

JS:   [a, b] = [b, a];
来源：http://dali.cqqwz.cn/Article/details/gtqfgwttsi.html

TS:   [a, b] = [b, a];
来源：http://dali.fzhhl.top/Article/details/gthnrtludt.html

Java: int t = a; a = b; b = t;
来源：http://dali.hongshengwenyu.top/Article/details/gtofniwzpl.html

Go:   a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gtlfzjktxe.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtxmvfhrsx.html

C#:   (a, b) = (b, a);
来源：http://dali.daria6918.cn/Article/details/gtjszxcwac.html

[A20] 读取标准输入
来源：http://dali.tanke756.top/Article/details/gtqjijviap.html

Py:   name = input("请输入：")
来源：http://dali.tanke756.top/Article/details/gtmadrcxax.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.svipenyu.cn/Article/details/gtrmodxugl.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xylfe.cn/Article/details/gtrjinbtpt.html

TS:   // Node.js：readline 模块
来源：http://dali.andypj.xyz/Article/details/gtnppjnqmp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gogol.net.cn/Article/details/gtaynfwzxs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gtayujzctu.html

Ruby: gets.chomp
来源：http://dali.fengsongda.top/Article/details/gtzcejhtuh.html

C#:   Console.ReadLine();
来源：http://dali.chenzaomai.com/Article/details/gtfjapmffc.html

[A21] 保留指定小数位输出
来源：http://dali.wangdashe.top/Article/details/gtarhqvtjt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xziqi.cn/Article/details/gtjkzyjtvc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtlpoydlkw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gthgoubqgi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtjqlcxpwf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtrsniowno.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtcctczgin.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gthqziaepj.html

C#:   3.14159.ToString("F2")
来源：http://dali.sweek.top/Article/details/gtjgiuivpj.html

[A22] 获取字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtmipuemtu.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtaaxyvjkw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.meibo888.top/Article/details/gtkiqvzphv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jiagoushi.top/Article/details/gtlgvoskhl.html

TS:   s.length
来源：http://dali.guannengcc.top/Article/details/gtyfnquvdy.html

Java: s.length()
来源：http://dali.tianlin.xyz/Article/details/gtmljsxhin.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gtjxochazq.html

Ruby: s.length
来源：http://dali.havefunace.top/Article/details/gtxnzwngmm.html

C#:   s.Length
来源：http://dali.ivvv.top/Article/details/gtdackqbdb.html

[A23] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtoibfshig.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenlongwang.top/Article/details/gttepxnktr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyaadotq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtywzsiubz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtlzzzcsod.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvorbipwo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.haohaochexian.top/Article/details/gtnakgcylu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbewlqcwt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmisttcme.html

[A24] 去除首尾空白
来源：http://dali.yueranfly.top/Article/details/gtbspuknhs.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.meibo888.top/Article/details/gtxfumamfp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hysaishi.cn/Article/details/gtvxxnrqsy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gtrpgnusyw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtiunghzyn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gteatubeqo.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gtiwqsqabu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gtjnaoyylv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shuidangran.top/Article/details/gtisqgizpw.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtjfqwyjbp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ppjwa.cn/Article/details/gtaeghxurb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gtkjwenxdr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtbdiyahoc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gtwgajbmkw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xziqi.cn/Article/details/gtbiibqstu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtzqbcobdu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gtwflbycco.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gtmoxsjexv.html

[A26] 类型转换总览
来源：http://dali.yuxming.cn/Article/details/gtrxsgzeis.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtkobvnlhr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ybcxt.top/Article/details/gtbhbckwxq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gthhddcydb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gttqjkgufi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gtrvyzixci.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gtwjjocnvs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuanzx.com/Article/details/gthivngghm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtrwwyqvti.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjkgwygha.html

B. 流程控制
来源：http://dali.cheryme.top/Article/details/gtxuovxxbq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjzttorlt.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gtaxztdzwc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cashguo.top/Article/details/gtvafmuohf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gtnjjppvrm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gttndpzsdb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtjzxzcyjn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtpmigvlty.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.haohaochexian.top/Article/details/gtybfwvkho.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gttuylnqof.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtxcvgkmfv.html

[B02] 多分支 else if / elif
来源：http://dali.cheryme.top/Article/details/gtsoscmnfc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zdqjudy.top/Article/details/gtlepfntxb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gttupgmibl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtywubpgtb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtgrbozebo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtsghwsoob.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwizfqbq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgcliyab.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtugzhonyo.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gtupceljjn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gtulndomef.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvyoyaaq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtggkpmrhy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gthpvwtldd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtrqtbllhm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxinkj.top/Article/details/gtslmmlxis.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cdnleiting.top/Article/details/gtcywdaqzw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtmugvinkh.html

[B04] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtgzxgsjag.html

Py:   for i in range(10): print(i)
来源：http://dali.tanke756.top/Article/details/gtygdbgqbb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tanke756.top/Article/details/gtmifayetq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtfufglqqw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtnncnmvyl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtxchsepah.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sufxvd.cn/Article/details/gtwfsxhnni.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gtlicrntev.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yongpay.top/Article/details/gtmddgatqy.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtozkuccdf.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtbiiffomy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.bjfxy.top/Article/details/gttmyfimov.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtpvxwkguw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtuepwkipa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gtdkgizwew.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtzmcbjqdq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeservnm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gtzcohxyos.html

[B06] 遍历字典 / 对象
来源：http://dali.shzxlz.cn/Article/details/gtihsmdzbq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gttupbyxlb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxvlctrt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gthirpryjk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtsmjykejn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gtrfcwivfa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gtkcefizxa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cqqwz.cn/Article/details/gtfzfxbory.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gtpbfdazzi.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gtapbnpfqw.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gthevepgsc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwezdlzj.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtasxepnhd.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gttyoxtfux.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtxyhtjwfi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxinkj.top/Article/details/gtjhcarivs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gtkjftbadq.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtqekwrpwg.html

[B08] do-while（至少执行一次）
来源：http://dali.tianlin.xyz/Article/details/gtipfakhrx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.iojbl.cn/Article/details/gtsighzzwf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ybcxt.top/Article/details/gtlgpqcgqu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtvxmouuks.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gturektfcs.html

Java: do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtiuznquxm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtftlohnhb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtazgpvdyq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtbvxijomw.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtvlobhhee.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gttaczskix.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlsdtdhp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gterzsuocs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtvrntspif.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtgewvzkmn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxqhhaor.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobnpydmb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtkkawjhfz.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtvpbfgcss.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gtxpymhtli.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtoeximfgz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtoxtvicns.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtbkxpvild.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gtwiqylros.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtpdqbkhbb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtfizmesbp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoogrjxcg.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmmmaegg.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gteyjxgfxc.html

PHP:  range(0, 10, 2);
来源：http://dali.dashuyun.cn/Article/details/gtdhfcvztj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtqtyrbckd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtklnorqct.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtghpnqoje.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtvjtzegln.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gtcyrtzubq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gtqskeipht.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtabnwgqpu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gteqcmyrxr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gthyuethzi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtdknonmen.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtcccfnodd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtjreoabbq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtqtvgsyok.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gtuhxyjbbl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtcwqfhfcr.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtapsdgios.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gtpjnqirij.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtoxcanpfq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gttnmwmqqx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtdjyndbfz.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gtpbfinzsh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtavktcbzq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gtvyrzjbmk.html

C#:   x is int or double or decimal
来源：http://dali.nwbrower.top/Article/details/gtalytlsyc.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtrcunprlg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtstbfubtt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gteofwsskw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtwhwffufj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtwgzgjkhy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gtdisvldpp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gtgskjmnws.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtdywzvjkl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtqubqlmlp.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gtjrgebruu.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtjlwyyyti.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtnkutiyzh.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtaitabtkv.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtmfsbuezs.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtdxlyftrs.html

Go:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtfniabewi.html

Ruby: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtwjjfyvdp.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtssunkskv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtjuicctjo.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtnkmovvep.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtnqnusrtz.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtuaxqhxvt.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtmajpzjyj.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtsrguwazv.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtmmupcieb.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gthecvrbjp.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtbymcubsm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsuxzvrtv.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqpabkkd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxzzfuynm.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtqkfpazjs.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gtnrlvauxu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtadgtpvad.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtonivdjss.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtiufrxkes.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtofheoedc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gtomtxhbvv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtefhzxgim.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtajxujtgh.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtdxcsnhuw.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gttvjjrtmi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtwlgyzhfd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtxaxvydcd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkelqxugr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtqnetdbwh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gtdkzxtvno.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gttlwgzkxj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecmaddkn.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gttlgnggbl.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtznnpxeds.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtzmqmvtgt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtxksvpoqe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtuvkusrfb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gtmjodwsea.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtazhrrxbl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtfsgkmwav.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gtdezxkspa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtitycvhid.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gtwvytbyqw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gtsgjystmn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtenslnrnd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenzaomai.com/Article/details/gtcdafhyyj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtvgfddqop.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gttjlrvuvq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdgjrvqyk.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gttrlpreok.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gtwkxtbuwm.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtzivqxfag.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtxtzsubhd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtrwreeyzm.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtcruxrmex.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gtjsviejxp.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtuviqjajy.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtrocudtcg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gttebahsga.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gtechlrhpz.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gthkvpxgkd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtgkenorvn.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtihrbzzwe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtgroeatyn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtpdzjazmz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtuockrjxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtgkmbfgkq.html


<!-- 参考信息 -->