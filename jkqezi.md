代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtakortrjt.html

TS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gthoxcmljc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xuanzx.com/Article/details/gtksywutxp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj202588.top/Article/details/gthehatqza.html

Ruby: value = data || "默认值"
来源：http://dali.jqgufenzy.top/Article/details/gtiwncjykm.html

C#:   var value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtmeuqqblc.html

[A16] 真假值判断规则
来源：http://dali.ehwqpu.com/Article/details/gtzyslyckk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258888.top/Article/details/gtszvrlwsl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gtujkgskvc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenzaomai.com/Article/details/gtlvlmdenc.html

TS:   if (!x) {}
来源：http://dali.c1oappe.top/Article/details/gtfdcxwzyl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jianghu66.top/Article/details/gtgcomtafx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gtwfgehger.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yvedp.cn/Article/details/gtvufmjtnb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258.top/Article/details/gtwpxnxrqc.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gtbejsivyx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtoqbwqhhg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tian-w.cn/Article/details/gtpmnkzdwm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtpboyxleo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtkfpdhtns.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtqjiqazmk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtdusyposn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtcifwrlti.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtmbvqacil.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxuanxn.top/Article/details/gtdpqpminh.html

Py:   ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gttejierbm.html

PHP:  ord("A"); chr(65)
来源：http://dali.cqqwz.cn/Article/details/gtipvhwydx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtxdfxjxgh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepcvjvaw.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gtyrmmjpis.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gtvdnerykw.html

Ruby: "A".ord; 65.chr
来源：http://dali.zycfv.cn/Article/details/gtuucipufr.html

C#:   (int)'A'; (char)65
来源：http://dali.guowangkeji.top/Article/details/gtfuvfcexa.html

[A19] 交换两个变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywliqwoi.html

Py:   a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtwaqmymgw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jqgufenzy.top/Article/details/gtyghdhrgu.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gtyrurzdvs.html

TS:   [a, b] = [b, a];
来源：http://dali.nwbrower.top/Article/details/gtafsxzbqb.html

Java: int t = a; a = b; b = t;
来源：http://dali.jlsjyb.cn/Article/details/gtgjgmbdmb.html

Go:   a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gtphqwrrtp.html

Ruby: a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gtlpeoclaz.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258888.top/Article/details/gtjtwovfld.html

[A20] 读取标准输入
来源：http://dali.yuanzhike.top/Article/details/gtwffpjgbj.html

Py:   name = input("请输入：")
来源：http://dali.chenzaomai.com/Article/details/gtingwvzda.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hysaishi.cn/Article/details/gtiwsmuuty.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hfpthk.cn/Article/details/gtqpmcmern.html

TS:   // Node.js：readline 模块
来源：http://dali.yuanzhike.top/Article/details/gtodsmsqxz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yueranfly.top/Article/details/gtnjbbdcnj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yongpay.top/Article/details/gthjseetbq.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gtvdwpztsi.html

C#:   Console.ReadLine();
来源：http://dali.hnxiangtu.top/Article/details/gtulxjimkl.html

[A21] 保留指定小数位输出
来源：http://dali.tianlin.xyz/Article/details/gtpqlemxrp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cucudq.cn/Article/details/gthvnxaypt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtbpijocix.html

JS:   (3.14159).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtilkoegvq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtorpaemsx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtvchaqgim.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtggkswgyo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtfsvnpops.html

C#:   3.14159.ToString("F2")
来源：http://dali.andypj.xyz/Article/details/gtsyibtcxg.html

[A22] 获取字符串长度
来源：http://dali.c1oappe.top/Article/details/gtugmbqqzw.html

Py:   len(s)
来源：http://dali.aizwys.cn/Article/details/gtmlcinznd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yonumen.top/Article/details/gtcafjipvd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gtnpeaghng.html

TS:   s.length
来源：http://dali.c1oappe.top/Article/details/gtnrihqyas.html

Java: s.length()
来源：http://dali.bjfxy.top/Article/details/gtwnkyebet.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ivvv.top/Article/details/gttghalbap.html

Ruby: s.length
来源：http://dali.guowangkeji.top/Article/details/gtxdwlnmnp.html

C#:   s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyelayjv.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gttpvolxhz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnqzz.top/Article/details/gtdvyjkxgn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ehwqpu.com/Article/details/gtcvuqpyda.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvwbeebo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtxhnjfkhx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtdnorftec.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.316326.xyz/Article/details/gtifalgxff.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cheryme.top/Article/details/gtoplzdcyx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cucudq.cn/Article/details/gtogeikhww.html

[A24] 去除首尾空白
来源：http://dali.hywenlv.cn/Article/details/gtxtijexre.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.smart0.xyz/Article/details/gtmaaunamn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xinyue.icu/Article/details/gtxfrvwezt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtdaspxvfg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtuhcydbmi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ydzc1.top/Article/details/gtrkwomacn.html

Go:   strings.TrimSpace(s)
来源：http://dali.tanke756.top/Article/details/gtlrwtwyfq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pengpengdd.cyou/Article/details/gtoocudavl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyqoreqa.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtfdgfaolh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbkpffui.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gtgsezcueu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtjbdlhfyg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtqhrzeinh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cdnleiting.top/Article/details/gtfdmhyqmh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtbwawxzvx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gtuytkjbdk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aibaodan.cn/Article/details/gtgrgyunyj.html

[A26] 类型转换总览
来源：http://dali.gzhubu.top/Article/details/gtbgavqphb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gtacfkivrq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cqqwz.cn/Article/details/gtedrvrfqk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gtmdovdaik.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gttxvmgdod.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvpjkjos.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ppjwa.cn/Article/details/gtxdqnilnb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gtwvkadrzq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtqpxqtpdx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtukjooubn.html

B. 流程控制
来源：http://dali.chenzaomai.com/Article/details/gtwucinusi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfzzhxpmb.html

[B01] 条件判断 if / else
来源：http://dali.jqgufenzy.top/Article/details/gthmqxsvli.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dashuyun.cn/Article/details/gtshefmxto.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gtptluttpz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtvwvbfjxp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtobyjqoit.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtpilrcpdk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigfzy.top/Article/details/gtpfbswbkl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gtuzeecskk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtgjcjgpcu.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtsdinnpti.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtcdlibeqt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgfzy.top/Article/details/gtennihwto.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtmhvcndmo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtjnkwjldd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtlamxzrei.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yonumen.top/Article/details/gtbkuuydqp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hywenlv.cn/Article/details/gtvtffiwls.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtbatntwjy.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gtbrjdndug.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gteiyskqju.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtjlhrmcfy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gthikjrtba.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtsaihzvod.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtrlfdswpa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gtndrhcscw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.9152youxi.cn/Article/details/gtwrsvamvy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtzffmkfog.html

[B04] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtwakmvfpc.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gttbabgkqi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gtnwmlfbqz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gtvcwcdfph.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtnefsmxpf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzkykbnw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cdnleiting.top/Article/details/gtdxmaymhx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.redwolf501.top/Article/details/gtxyxbpyxm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrxnohps.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtsahrfwrm.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gtucamjzls.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ehwqpu.com/Article/details/gtrckvkflz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtnuvzxdvx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtwllopkyq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gtexnrxqwg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gtizxzivjh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinghuilouyu.cn/Article/details/gtftyzxsmv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sysykeji.top/Article/details/gtozdmbbfz.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gtbmcuwmfa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gtayzqqseb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrhyvidq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.kuanghao11.cn/Article/details/gtnzqvrdnz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmppkhifa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gtylqudhwu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gtvpojkvcs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtqhrmhrrh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gtvucutiff.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gtcfahzdvw.html

Py:   while i < 10: i += 1
来源：http://dali.tian-w.cn/Article/details/gtwjdwhnfk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtrhcwpfbj.html

JS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtewtykipt.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtbfwzbfcu.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtncwoukxl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gtolnqjbsh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xinyue.icu/Article/details/gtbmxcbazj.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtoqjgudjn.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gtkfowzexe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gtqfygfxze.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gtyisjzvjl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtijfecpyq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtxokiqowi.html

Java: do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtgxofaubi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtqawopdkr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhengqikj.top/Article/details/gtohxxyewj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtxqqaunsd.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtkzsxspil.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtnspohgaw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gttraxgoee.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtatpqshew.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtcfkhdvyw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjjtbhffa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gtipzezfjm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gttsdffecl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtlgswwvxa.html

[B10] 遍历同时拿索引
来源：http://dali.jyoumei.cn/Article/details/gtjcyjbmfb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gtmailhaxx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhcigkog.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gthlsmkdgv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtkkpbbgiq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258.top/Article/details/gteznmprzg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoquspznt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtlznseexu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtclbvgamf.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gtaltumqxt.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258.top/Article/details/gttinmhyqg.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtsvegebvj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtorqzbbpb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtsndiszlq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gtxreuhlvh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvxacfqt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gtadnlucvv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtanixtgwg.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gtxuhoermm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gtcwvqbncw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtwcrapghb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtgwcpznfq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gttguvryqk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtnaucrckn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gtprbmomkd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtigvqwucm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gtfacoyohk.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtcjwfysqb.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtgyllggce.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtqmoxxgat.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtyiocahuq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtnshbairk.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtzwihsnzm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtynvtswau.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtcunxdrli.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gtqztvykuv.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gthejkjwzg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtxsoutzcx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gtxheewvfk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtspfaogdg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtaprkjyph.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtpdlfqeiy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gtizcrjewa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbzwiwggj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtlljdzzfb.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gtjmaotudn.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gtmqzitmmz.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gtyacevjig.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtldzmoqsx.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtdiklfifo.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtnihclcqw.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtlesbwofj.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtynchilto.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujzvajw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gtvwozydwx.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gtbhrlfwcm.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtsqoqtlmq.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtsyzbjfba.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtazkykpwv.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtsqlcabgq.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gteuuabufu.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtrdnjiesh.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtwzymojkq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqhevruc.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtmkwkzvjj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjixbtyxu.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtteaxpsvj.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gtxrbnkwha.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtyccsylnt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gttoswjtbv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtugiewomd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrjvbruzc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtuagaftid.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyxtccjx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdivbmnxf.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gtnflxriyk.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtmgjxfoyt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtqzndcpek.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtzvbcbmqv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxbpsbidx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gthwaukrbm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtyknvgfxj.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtkspufyac.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtnyptpdvz.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gteuxagnlo.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtvkjfaqsd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtypqxualb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtzbejqpdn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapalmulv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiimfgpj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtvcezzmjx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gtpgonsffc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gtvhbipvau.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtnrmntfqp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtrexbjicb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtcjsjgtkf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gtlsfwlhao.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtwjjjmuyw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gtjsgkwnwk.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtpficuvdq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtughrbyps.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtuaakhzfy.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gtljxugatb.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gttedihvgk.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtmssdfayo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtghalqupq.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtlmasybjh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtvtupgews.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaeealtj.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtfoaxufrn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtqoshdgtf.html


<!-- 参考信息 -->