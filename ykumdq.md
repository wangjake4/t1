代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.zhixingplan.top/Article/details/gthunwtzui.html

C#:   var value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtlknukupo.html

[A16] 真假值判断规则
来源：http://dali.tanke756.top/Article/details/gtlyqvxttd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xziqi.cn/Article/details/gtbtbfmzsr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.vqdsnc.cn/Article/details/gtnmwjsrxt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxuanxn.top/Article/details/gtqlqsygup.html

TS:   if (!x) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpkqzoqkb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.316326.xyz/Article/details/gtrpeueufb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ppjwa.cn/Article/details/gtxsinphse.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrcdudkt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daria6918.cn/Article/details/gtvgujfvvn.html

[A17] 位运算
来源：http://dali.yanxiufei.cn/Article/details/gtwwcdjofn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtglhnyfii.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sweek.top/Article/details/gtoaibwupa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtjlketzwt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtzkawjvkn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gttmywktge.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtkisbwnhr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtcjefjmgp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtkcxzrvil.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xuanzx.com/Article/details/gtqkjhzble.html

Py:   ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gtigwvvaga.html

PHP:  ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtmmwlqeif.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtylbtfceu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtmowtpvwk.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnxiangtu.top/Article/details/gtmtodcaqw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sufxvd.cn/Article/details/gtlvauhrcg.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuanzx.com/Article/details/gtfhfrgnxy.html

C#:   (int)'A'; (char)65
来源：http://dali.sysykeji.top/Article/details/gtdbwfufij.html

[A19] 交换两个变量
来源：http://dali.bjfxy.top/Article/details/gtjzljnuuy.html

Py:   a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gtfmenysff.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aizwys.cn/Article/details/gtdfpfmqsm.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gtdjebwwel.html

TS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gtsppzyqkj.html

Java: int t = a; a = b; b = t;
来源：http://dali.haohaochexian.top/Article/details/gteeilqppq.html

Go:   a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gtaxvwkrzh.html

Ruby: a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gtykfpafat.html

C#:   (a, b) = (b, a);
来源：http://dali.pengpengdd.cyou/Article/details/gtxmhosjxo.html

[A20] 读取标准输入
来源：http://dali.0kj1m.cn/Article/details/gtftljoxsn.html

Py:   name = input("请输入：")
来源：http://dali.yj202588.top/Article/details/gtmvxiuwzr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.redwolf501.top/Article/details/gtaakypqfs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangshuangyany.cn/Article/details/gtlqgnxfhu.html

TS:   // Node.js：readline 模块
来源：http://dali.fengsongda.top/Article/details/gtjosmdebd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.svipenyu.cn/Article/details/gtaextcedu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ivvv.top/Article/details/gtucngsqah.html

Ruby: gets.chomp
来源：http://dali.jinqigufen.top/Article/details/gtinzgsioo.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gthhspziis.html

[A21] 保留指定小数位输出
来源：http://dali.zycfv.cn/Article/details/gtynrfpadu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.haohaochexian.top/Article/details/gtdjsktife.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtphgdaajt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtimxtrzvs.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdleykgzn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtdkhjwfwx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtipjhbana.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtqcjuqwbp.html

C#:   3.14159.ToString("F2")
来源：http://dali.feifeiyinyue.top/Article/details/gtkovqpoay.html

[A22] 获取字符串长度
来源：http://dali.birdmap.top/Article/details/gtpkussyyk.html

Py:   len(s)
来源：http://dali.birdmap.top/Article/details/gtmdqsvkcr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gtzlfdyrwe.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangshuangyany.cn/Article/details/gtxafwcllb.html

TS:   s.length
来源：http://dali.hysaishi.cn/Article/details/gtkoxbygrl.html

Java: s.length()
来源：http://dali.cashguo.top/Article/details/gtvwbmhsnv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtazralzvi.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gtwoebnkrn.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gttbiioryu.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtikfynvid.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.andypj.xyz/Article/details/gtlcooizcx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gtrtwelrxg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtbutabyqi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gtjoqlfllj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtrxkbilwx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuxming.cn/Article/details/gtijvzobps.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtmfyimhpz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuanzhike.top/Article/details/gtamlgglvk.html

[A24] 去除首尾空白
来源：http://dali.aizwys.cn/Article/details/gtkooxsosl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.quarkkingdee.top/Article/details/gtmkdvlbrr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gtlannpcjp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtiijcymhv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjebqndi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevjisrcg.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuanzhike.top/Article/details/gtjoeupegm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxinkj.top/Article/details/gtrzpzggrb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gtafkqqvig.html

[A25] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtlfvovyhg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fengsongda.top/Article/details/gtkmltkchq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fzhhl.top/Article/details/gtxhyfwapl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gtfuwzolfw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfvkgbak.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigufen.top/Article/details/gtpwyqlfxa.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gtxweyfxye.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgfzy.top/Article/details/gttuomujxd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtamouyvlr.html

[A26] 类型转换总览
来源：http://dali.316326.xyz/Article/details/gtdsizwsgt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtsmtlnljr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gtfprtruux.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoczzeoae.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gtukxceghc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtxjiggkgp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxinkj.top/Article/details/gtmsiprgpq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gtolbxwrtt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtmnvbknuw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqvapcdxq.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gtndtziibt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjzzphfif.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtxpmvblsp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigfzy.top/Article/details/gtorgmrvxt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.smart0.xyz/Article/details/gtzoptmgrx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtzdbmsfns.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtgdfvppvs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtmcefxznz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jiagoushi.top/Article/details/gthotoabyf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gtjnkcamtg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtjrnwrimw.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gtmxqxtslj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gtdhwjugox.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gtkouphcmz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtohmnudai.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtwnmslqwg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gteodbnkox.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ivvv.top/Article/details/gtuvrstpol.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shangyingyoupin.top/Article/details/gtwkkyysou.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtybmeqahp.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtkcvorxhv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtcxvqmgvp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtgzkqkinq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtxcgtqgdv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtojepajfh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtxaalbger.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aizwys.cn/Article/details/gtfpisqaef.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqhjikop.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtzeejqumb.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtofjmdzha.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtvbkcxrkq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258.top/Article/details/gtfddnvnst.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtyzybyuiu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gttgtzhxuo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gtirycrtdi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tian-w.cn/Article/details/gtlobmrptl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gtdpuiuecm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjzqbjmxa.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtzmrbhzwu.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gtjzwmntyr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtsxkctlnm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtokrpsijb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gthsxmbzod.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtjleyfmvs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gtkblovuuc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gtrtwlaoil.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gtlfxkzpbh.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtauoekugg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hfpthk.cn/Article/details/gtafensmqj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtruyodiub.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtrzzqjnvh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gtgrdusahp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjffvfktn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpybekhbi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gthobxcznb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gtrilmvdho.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gtleltzhxe.html

Py:   while i < 10: i += 1
来源：http://dali.zhixingplan.top/Article/details/gtxzakceml.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gtkuryqsez.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtlsdddiaz.html

TS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtruyndivp.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtynxzxnoq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gttpjonbmz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtfrsbvosh.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkhlgydoz.html

[B08] do-while（至少执行一次）
来源：http://dali.cdnleiting.top/Article/details/gthmzokovt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258.top/Article/details/gtturradhx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gtrymlwcrr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtcsvyfzsf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtkbvoflfe.html

Java: do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtzxzjrnvp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxinkj.top/Article/details/gtxvmijjsu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hysaishi.cn/Article/details/gtuezvlfqh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtjxyrvarz.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtqbwmqeyr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtqenruter.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtydyuypmc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtmjdocger.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtabsjdnhm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtowbsqfqa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtjgpvzolp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtwvnqavcp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtjjytnasg.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtvijmwmxn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gtbadkplbe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtcwirtxqa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtrdrihzok.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtbclulsof.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtcfttqsyu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gtwswltvcv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gtfvyiwdwk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cdnleiting.top/Article/details/gtqrkdwmyf.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtftkutjrx.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtydpakvrk.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtagjjpbqf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gteovqnzbk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtbwastqkw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtwxxxcbfu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtzehtblos.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gtoorwlzyw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtbptpaxbn.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtutaqjfty.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gtuyatklcp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtkttgwocy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtvqktlflu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtzzswrval.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtgxernyrf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtdrjiauag.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gttcwjbodi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtxgrozdmv.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gtswvvacuv.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtvqgbpijk.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gtiysqqntb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtkjtyoidr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtfkfxbcfv.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gtgzzkucje.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtabewvghb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.redwolf501.top/Article/details/gtnrcyhuhc.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gthblmqpvh.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtrhxxrpuu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtvkbpqkul.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtvqxbexfe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtuttiaxpw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gthkamdbnc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtjgyooxjw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhoulong.xyz/Article/details/gtqmynrauj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gtoettasrf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtrybbztak.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtumapvdac.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtpdojnnmu.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtvedjupqt.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtefcslszb.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmbouxbr.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gtxqzvyyyj.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtxxzqqkrx.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtakhfrtpk.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtaznagxrc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtunsoqtaz.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gtbstllmnw.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtmjwocmti.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtmwxmhsnz.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtlboexvxw.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtsuqkutei.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gteptsbbxz.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtirfblucz.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtqzdkynft.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbvblneni.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gtozuzpxjc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkhrghyqa.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gteehlmgwv.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gtclztgvco.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtexamgqje.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtygikrflf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtqivyymvv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtezxlqbcl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtzujaakek.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigfzy.top/Article/details/gtltvrbdoa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtkbeivoar.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtysmhfpdz.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtqveszhln.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtzwcerpau.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtabjtuzau.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtgcpzokqg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtrbfrjgdt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtdrhiblhb.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gttlwnlfhx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtlezxpznf.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gtwxdrxaxz.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gtaxkkroik.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gttbigseob.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtornrgxmn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtrobmytac.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwkonpunk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtkvlnstnn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtzafyljjz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gttmelvaxk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gtneekobfe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxqzooxq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtonsqqrfi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtmqygzejm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtandacico.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gtthcrrfls.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtzpjghhck.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtiqlefsns.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtxxfbdexv.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtlbbqxrjb.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtyfxyeagk.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtvgsfwzhi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtkgeiypzr.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtpcrehbdr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtnbzqauzo.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtkyapizww.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtyjlogtip.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtabigilkh.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtfjhabavi.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtonlzzeuw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gtjzxtgcop.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtqoozyvym.html


<!-- 参考信息 -->