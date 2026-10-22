代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtjhwdxuel.html

[A15] 空值判断与默认值
来源：http://dali.shuidangran.top/Article/details/gtjnlamlor.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gttxuoyxbj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gtjxeoyxji.html

JS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtudrayjoz.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtktececvm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenjidiqi.icu/Article/details/gthfwydaxs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gtrukklaxu.html

Ruby: value = data || "默认值"
来源：http://dali.fzhhl.top/Article/details/gtaolyszxi.html

C#:   var value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnzyjjqp.html

[A16] 真假值判断规则
来源：http://dali.jqgfzy.top/Article/details/gtsasxarif.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sysykeji.top/Article/details/gtopuovrun.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhongyouzk.top/Article/details/gtorivhjbv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gtoouzdnmu.html

TS:   if (!x) {}
来源：http://dali.zhengqikj.top/Article/details/gtrrdclnbb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvqdcjaz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hammf.cn/Article/details/gtfsvmhasm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hfpthk.cn/Article/details/gtclfzsvqf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yvedp.cn/Article/details/gtkdcqunzr.html

[A17] 位运算
来源：http://dali.sysykeji.top/Article/details/gtfszonwks.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gteichvnmz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtcoebynmq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtxycekunf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtanpskbxa.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtwlnjrhiq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtfdqvuihn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtasckqdke.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtnkzsvmus.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yanxiufei.cn/Article/details/gteefrbzze.html

Py:   ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gtmaeosrvp.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gteflswuiy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gtabqsgyqq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gtoszlzorg.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gtcrmcjxvz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.svipenyu.cn/Article/details/gtalrogvym.html

Ruby: "A".ord; 65.chr
来源：http://dali.ydzc1.top/Article/details/gtfilwsaad.html

C#:   (int)'A'; (char)65
来源：http://dali.xuanzx.com/Article/details/gtmtznqwec.html

[A19] 交换两个变量
来源：http://dali.redwolf501.top/Article/details/gthfcasgsy.html

Py:   a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gthmtlqkya.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.vqdsnc.cn/Article/details/gtqzxwkabn.html

JS:   [a, b] = [b, a];
来源：http://dali.smart0.xyz/Article/details/gtgdekyktu.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtvgoatebi.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj202588.top/Article/details/gtuphztlvk.html

Go:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gtgywbwbbw.html

Ruby: a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtntvixtfu.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gtkaxctdnn.html

[A20] 读取标准输入
来源：http://dali.zhongyouzk.top/Article/details/gtwoghtbps.html

Py:   name = input("请输入：")
来源：http://dali.cashguo.top/Article/details/gtojntibpv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gtallzqwua.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sxryk.cn/Article/details/gtkfkianhd.html

TS:   // Node.js：readline 模块
来源：http://dali.svipenyu.cn/Article/details/gtejeobzad.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pengpengdd.cyou/Article/details/gtuxtdbmnt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gtqmcualog.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gtuhsolkmq.html

C#:   Console.ReadLine();
来源：http://dali.zhengqikj.top/Article/details/gtnxptnvvg.html

[A21] 保留指定小数位输出
来源：http://dali.sysykeji.top/Article/details/gtltcofjbm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsujsijee.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtcvsxqiam.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtecvtnkxi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtuwrhzzyq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtohehtmmy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtekdmcwxh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtjzaoyhep.html

C#:   3.14159.ToString("F2")
来源：http://dali.ybcxt.top/Article/details/gtlygooplt.html

[A22] 获取字符串长度
来源：http://dali.yj202588.top/Article/details/gtnxevmuzn.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtlhbaxofz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cashguo.top/Article/details/gtdpmuvamy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gaohongyu789.top/Article/details/gtgzgzgwwe.html

TS:   s.length
来源：http://dali.jiagoushi.top/Article/details/gtcnyvjwmb.html

Java: s.length()
来源：http://dali.cdnleiting.top/Article/details/gtffmyemwe.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkazxkaxs.html

Ruby: s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjqsfmxu.html

C#:   s.Length
来源：http://dali.birdmap.top/Article/details/gtmzkjazhb.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtwyojbens.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zycfv.cn/Article/details/gtcohbhrvd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwssebtyn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtatdvhmqb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtftsoznuc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtqohjfvng.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gtzykgypvv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtvgtvbvvc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhengqikj.top/Article/details/gtqnpftorg.html

[A24] 去除首尾空白
来源：http://dali.zhiwuduotai.top/Article/details/gtqkzmqmis.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.316326.xyz/Article/details/gtstxgvdjz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.redwolf501.top/Article/details/gtllhrhzer.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gtenznyrzr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtreczsptr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gtduskyjld.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gtmskskeab.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenjidiqi.icu/Article/details/gtabrnbuux.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtjpchocod.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gthdwwihkn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gterpendot.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuanzx.com/Article/details/gtjpdcylop.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jianghu66.top/Article/details/gteqgoczox.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtbptyrzbf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gtcdhitjou.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gtiyjvviqx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.9152youxi.cn/Article/details/gtmwpuohbd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtqwkzbeoy.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtzljueoaf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nwbrower.top/Article/details/gtmgfcharz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daxiang520.top/Article/details/gtdpbdetrn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhhhcxaq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daria6918.cn/Article/details/gtfobrntro.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtrstxbqzg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.redwolf501.top/Article/details/gtlubxnujc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhengqikj.top/Article/details/gtaggspcee.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtmbtifuaa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtueqzlmgj.html

B. 流程控制
来源：http://dali.yj202588.top/Article/details/gtvdocmoxn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtysxxthxq.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtkruczpca.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gogol.net.cn/Article/details/gtzgpbtxlz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yvedp.cn/Article/details/gtbqwqnqwj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtvmxegecl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtpxkjbotr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtvrrzjpfq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aibaodan.cn/Article/details/gtxwwwwvzz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.haohaochexian.top/Article/details/gtbzioomtb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtehyrbhzd.html

[B02] 多分支 else if / elif
来源：http://dali.ivvv.top/Article/details/gtbvvcqncs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yueranfly.top/Article/details/gttutopdzq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gtrqzrkyzk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtuysulbhq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtpixuhryf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtavrcnzdv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gtlyezaohg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shzxlz.cn/Article/details/gttgnbozet.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtnsmgpdcp.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtqnuyimre.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.pycfn.com/Article/details/gtuwuuaupr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtugfansxa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtcubldlax.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtquinfckn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtfanwleux.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gtsysvcsac.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgjnxepo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtyyzwqjjr.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtzmtutliv.html

Py:   for i in range(10): print(i)
来源：http://dali.chenlongwang.top/Article/details/gtcxmtaknf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gtrefpjecu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtokzasqfq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtehjlqbvl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gtukikvzst.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdslztpp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gtzueuwlhb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gtegfnbgcd.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtvbwyaivg.html

Py:   for item in arr: print(item)
来源：http://dali.cashguo.top/Article/details/gtrxixndye.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gthyhfchvo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtoczwodyj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtafssrdda.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gtonqmshxa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shuidangran.top/Article/details/gtaczyebrs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgfzy.top/Article/details/gtwcxhnhfo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gtmdiugasp.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gtiwjctgob.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shuidangran.top/Article/details/gtfombxzon.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtfmpctczt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtjmnzwntp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gtnpfrrnmm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gtyucyqgke.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pycfn.com/Article/details/gtumzazvpq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gtdpyagzqv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgqyviugq.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gtckkgsiyg.html

Py:   while i < 10: i += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtcslagfbk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtodwjtpog.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtdbenpvnh.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtrbthkndp.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtqsrgwwfy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gtozrbzoym.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtdlqszvuv.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtaivzrixw.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtbgwadrdq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.316326.xyz/Article/details/gtyvxmyccy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gtcuixipmw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtfoydsziw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtjuweyefe.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtfmtimljj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtquzghysq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gthggtomlv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuajgtsgo.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtjxvyhruo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gtwapmqgou.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptrqwvhv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtwqaowyrx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtffuopppi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtkaicesto.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gzhubu.top/Article/details/gtqpveyddj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gtjeamsskz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtqaspiutg.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gtvndvxwwe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gtpkiexikp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtqxenebhe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtsiakhpjf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtexhaibmd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoubqpndi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtradboijc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtwfrwweiy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gtrlmlqdhu.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtdjnalssf.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gtrgbecygj.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtgkdivdox.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtbbhxdpcr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtdyduygmo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.0kj1m.cn/Article/details/gtexuylqag.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtddjmmwry.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtqmsjqfiq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtoemrvlac.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtpcyhbdts.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sufxvd.cn/Article/details/gtcnmlqhbu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gtdcqlnogy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtciwcdxdb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtsgocbxcm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtzubiwxnj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gttteunlwj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtlaldutxl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgufenzy.top/Article/details/gtzbjobhdz.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoqoeegh.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtjlmzcfiz.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gtdzvrtwma.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gturufwkmt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtyymhhtqg.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gtpbqfodla.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfqxlosg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtjyajbimr.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gteiaypefh.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtfmeglmks.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gtfqpdtkns.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gtuazxlpxo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtnqoscmya.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtzutpweoc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtaejuhkpt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gttnrqtxcp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gtcziixpbb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtcrjhlemd.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtcdtztkjb.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtviyyoctu.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gtgrgsmazd.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtcagpretf.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtrlwxfqee.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtnrnkryaa.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtmdhbomej.html

Ruby: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtnxswujqx.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtfzhmozcn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenzaomai.com/Article/details/gtjtiuhilg.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsqmuvxk.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gteybgehdv.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtspuswalt.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtyjbayjfw.html

Java: if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtqwotjykx.html

Go:   if data == nil { return }
来源：http://dali.gotoacloud.top/Article/details/gthivfhxul.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gtudlvcafs.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtstqnorkn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpimofabb.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gthiurbmnl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdkldokbp.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtdoerkbqf.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtxwlrmmdn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtjyrzjold.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtsenzgohf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqwzritw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtxqnhzcxx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtkathikvu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtnihunqze.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtomxwdpwu.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gthrsvamkg.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiaahkht.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtoyczkpxr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtepmlptqs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtoisqgfkb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtswkkbeim.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtcqgjosgw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyupbacsd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gtauakwajf.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtqtsaqhvz.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gtemgzzodd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdvecwbhj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtkomagaaj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtbvggvlrg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gtxonupnbp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtxvnafkwk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gtcjkbpoqm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gtomzxhjgn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gtgihmzmon.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtsxkusvjr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtereppbeu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtjrrlmuce.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtcdpnrmdo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gttxrrgdzo.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gtnyrubhjc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtzoiwlras.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtegtfsgxv.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gtsckrhkns.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtjpdcrdeo.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtlkedjzbk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtmvokbxzz.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtseoqvfmr.html


<!-- 参考信息 -->