代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtohddzvqq.html

C#:   var value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtrsypnuau.html

[A16] 真假值判断规则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyefkjdn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.wangdashe.top/Article/details/gtyzfdwqlt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.9152youxi.cn/Article/details/gtvnmevfcw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yuxming.cn/Article/details/gtiopomdhl.html

TS:   if (!x) {}
来源：http://dali.yueranfly.top/Article/details/gtxbcpszbh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.daria6918.cn/Article/details/gtndfdntex.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yonumen.top/Article/details/gtwdugykob.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zycfv.cn/Article/details/gtuqloqrgf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zycfv.cn/Article/details/gtlxqxfzal.html

[A17] 位运算
来源：http://dali.zdqjudy.top/Article/details/gtsgcfyxjv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtjqpzrlpc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj20258.top/Article/details/gtwvoooaoa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtxgxwgauk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtnpsikoai.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtdvbxfnia.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtfbcqkmlv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtafnndqvr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtmgkqrhsw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xziqi.cn/Article/details/gtdnrohpvp.html

Py:   ord("A"); chr(65)
来源：http://dali.fzhhl.top/Article/details/gtrxseckoq.html

PHP:  ord("A"); chr(65)
来源：http://dali.tianlin.xyz/Article/details/gtvvttdsdt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangdashe.top/Article/details/gtgaamigxu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gtjhopvohm.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gtbosalmqx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gotoacloud.top/Article/details/gthtbrkvvn.html

Ruby: "A".ord; 65.chr
来源：http://dali.zdqjudy.top/Article/details/gtrttwpzoo.html

C#:   (int)'A'; (char)65
来源：http://dali.nwbrower.top/Article/details/gtspqadohx.html

[A19] 交换两个变量
来源：http://dali.aibaodan.cn/Article/details/gtnjgisjjb.html

Py:   a, b = b, a
来源：http://dali.birdmap.top/Article/details/gtrjxfewms.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gtfuxknpwa.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gtzznrfwyq.html

TS:   [a, b] = [b, a];
来源：http://dali.xuetiantiany.cn/Article/details/gtaeieqdqg.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj202588.top/Article/details/gtdowmitsl.html

Go:   a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtlapbumth.html

Ruby: a, b = b, a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalpydcie.html

C#:   (a, b) = (b, a);
来源：http://dali.zhoulong.xyz/Article/details/gtztmyeoce.html

[A20] 读取标准输入
来源：http://dali.c1oappe.top/Article/details/gtarfphwho.html

Py:   name = input("请输入：")
来源：http://dali.cdnleiting.top/Article/details/gtgcnyatzg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigfzy.top/Article/details/gtlqxutifh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.haohaochexian.top/Article/details/gtramheugt.html

TS:   // Node.js：readline 模块
来源：http://dali.xylfe.cn/Article/details/gtajgyttwc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258888.top/Article/details/gtmjuktpkj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhoulong.xyz/Article/details/gtnuuyxewb.html

Ruby: gets.chomp
来源：http://dali.yangfankeji.com/Article/details/gttttmcqsm.html

C#:   Console.ReadLine();
来源：http://dali.meibo888.top/Article/details/gtyrcbewip.html

[A21] 保留指定小数位输出
来源：http://dali.aibaodan.cn/Article/details/gtqcehjsvz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sufxvd.cn/Article/details/gtkcxjpyro.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtmmcsbwsp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtidnlejsa.html

TS:   (3.14159).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtrepakohy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtygnikqlz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpnaubvm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtggwxemcm.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gtfemqvvdv.html

[A22] 获取字符串长度
来源：http://dali.xinyue.icu/Article/details/gtdbefeefk.html

Py:   len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtigljvtmv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cqqwz.cn/Article/details/gtuomfigfu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtnboisrah.html

TS:   s.length
来源：http://dali.nanxuanxn.top/Article/details/gtfiexplqr.html

Java: s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtptsigbuc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sufxvd.cn/Article/details/gtninroeas.html

Ruby: s.length
来源：http://dali.jlsjyb.cn/Article/details/gtziagtedk.html

C#:   s.Length
来源：http://dali.bjfxy.top/Article/details/gtyavvmwcr.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtapgswlzz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.aibaodan.cn/Article/details/gtjcjrvxfp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gtfhksqnld.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtvfvndpdj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrloqfxv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtwfazhnqj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbfgsjpmf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtheeyhmjd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gtbqgujveq.html

[A24] 去除首尾空白
来源：http://dali.dashuyun.cn/Article/details/gtblkymdgu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gaohongyu789.top/Article/details/gtlzlholea.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhengqikj.top/Article/details/gtoxsqqpoa.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guannengcc.top/Article/details/gtzrlcjrcr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtquzpvwpi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zdqjudy.top/Article/details/gtuonhpaae.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxwjobeil.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hysaishi.cn/Article/details/gtnjxphojh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtgstemjiv.html

[A25] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtaxorxgbi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgtzmzpy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhoulong.xyz/Article/details/gtjkbxzmhd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtderrrxey.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtksqfvtoc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.316326.xyz/Article/details/gtptayappw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoentcsrd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gtdvctijix.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ybcxt.top/Article/details/gtojpjgska.html

[A26] 类型转换总览
来源：http://dali.chenzaomai.com/Article/details/gtchxyqedz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fzhhl.top/Article/details/gturoeftnr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.snrcjt.cn/Article/details/gtlpgojoxk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gtiqbrdrgw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinghuilouyu.cn/Article/details/gtspieaopj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtlfcsbymc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gtqalpfuyz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenlongwang.top/Article/details/gtnkugtnlo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hongshengwenyu.top/Article/details/gtpbscmgnl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpklqjzrl.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gtdzqcnzqb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdctrwlhd.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gtlapcpitx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jianghu66.top/Article/details/gtzxaaojav.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guowangkeji.top/Article/details/gtsuhgvgwg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtfkchgmvn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtxbxhmurd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtgeqsodhp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pengpengdd.cyou/Article/details/gtzymuzkwo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dianchejie.cn/Article/details/gtyrqfqgji.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtempqxphw.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtjcgyyzjx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.havefunace.top/Article/details/gtamlrasbh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtpfovjwgt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtdqewyhah.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gttlzwkxrm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtgojhpdne.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gtjtyltbaw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gtkewiufrh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowrfuaop.html

[B03] switch / match / case
来源：http://dali.ivvv.top/Article/details/gtsawcinvi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gtwtndisxy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtkzqlmpmw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtsvlpasqs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnvdifvf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtwohjphqp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.0kj1m.cn/Article/details/gthzsxeitv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gtgkowdtjy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gthbomlthl.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtgwkakflf.html

Py:   for i in range(10): print(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgfbbnkz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gtxluyhkip.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtuibfqvvv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gtichsajbb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gtfveldsec.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gtcsuquens.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ivvv.top/Article/details/gtezppsvrz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gtlhfnuhxw.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtvlfjpxuc.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtxsshxgcb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtjngbbent.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtvpnwhiwz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtqaoqyisf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtbuujlnza.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gtwwqwcapz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtyqjquiov.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.316326.xyz/Article/details/gtkulvclvi.html

[B06] 遍历字典 / 对象
来源：http://dali.shangyingyoupin.top/Article/details/gtaeuhgyis.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gtkdnrnwvt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gtqsbzggra.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gtpckrpuax.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtxjrfswnf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtrihonzvw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gtodijsykq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gtyrqikzol.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkatejlpc.html

[B07] while 循环
来源：http://dali.pycfn.com/Article/details/gtkvdtncfq.html

Py:   while i < 10: i += 1
来源：http://dali.redwolf501.top/Article/details/gtpztsmxmn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtplyvlivc.html

JS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtodiumfav.html

TS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtkgeodhqb.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gttlmimpxh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gteumbrbgw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gtwjhoobkx.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtgfbsgygd.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gtpfdpvsxx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gtbyuyjzkp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shuidangran.top/Article/details/gtixjioamb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtaeybvwcn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtrjrfpxkg.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtrkvuhrsn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtucwwwpdz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gttljxbapy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtqdilyrqd.html

[B09] break 与 continue
来源：http://dali.hongshengwenyu.top/Article/details/gtateyptcw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zycfv.cn/Article/details/gttdzbinlo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtqqrstznx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtjevnrxal.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtytauylon.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gturkbhuhl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtycitbzhp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gtxcweapwy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtlfsonuth.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gtwxgqtnsd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnqzz.top/Article/details/gtcfqerlti.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gtgtnajngy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gtiuffzfxi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtfonoczpx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtiuzmtedu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtmcjsjnmd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gtvgkxuqvm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqleonsf.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtspstdjqn.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gtwctpynxk.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtfmedud.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtowbinrao.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtwadgbwgq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gtsktbddbz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gthgvxlcll.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtxmkxpcfg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtfkzlmoqc.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtmdemwfju.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gtoustyzrp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtwpijunuq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtciqluwhr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gteqtfepip.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtijhjwhft.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gtarqaqajq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtstfyluxc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtxchoenmg.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gtjscldssz.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtskkonrbg.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtftjsxkxs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtydwecqvz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkncyfkk.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gtrslhaukx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtldlhgklp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjjltakd.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtpqlqipdi.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtmqjcztni.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtismxnqgw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gteduifdsd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtomqfzaih.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzcbbxup.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gthkblckgl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtkzbturio.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtdndlwuzn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtdhtlqbyo.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtvehavvmu.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtlbepbyix.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtwtevpmhn.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtirvkrmlt.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtitkmddyp.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtjvlykfkj.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtuupiltmq.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtpkkrmsby.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtdrcpalav.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtwvkjndsz.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtqfylxmzd.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtlrnntwfu.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtjflcgqoh.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtyffmtkid.html

Java: if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtumodjoxv.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsomrvsv.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtneyusuma.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtphmcuvub.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiegqvulq.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtarxlaoec.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthihgdxba.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gttykyxslz.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gtoxbehbut.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gthxnjhbzq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtkuuvkdmb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoehtzns.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenrjwuxk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtrflskump.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtcogegoge.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtfbtzucyz.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtempyflsr.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtzlyoiimi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtblngrezg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtpdfamuii.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtlmafkdqt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gteirssdvc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gtrtgmfmgs.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtihatjtio.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gtdtewiwpi.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtddonhrav.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gttthdgzov.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gtvyfksoya.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlppwvjhk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtgkwjssrq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gtfusakgaw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqjzaijq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtyxujoruw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtqgwuthuv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtdqiswekx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtoklwtpav.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gtwupvibvj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiawbulrm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenzaomai.com/Article/details/gtfilamrfs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gttzyohpgi.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtmxivxrny.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtfunlbdzy.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtnpxgatvf.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtovijlanv.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtotizzprt.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gthpwuvsiz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtcasormbk.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtmujwegtl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtzafkwpmq.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtlxqngmjy.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnolrhzg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gterzwcjgh.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtwcrrulzg.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gtjgzsqocv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtnzhxbjaf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtgpuudtzb.html


<!-- 参考信息 -->