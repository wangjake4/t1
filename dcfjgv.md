代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtzsxvnrxc.html

C#:   var value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gtqicmtmzq.html

[A16] 真假值判断规则
来源：http://dali.hysaishi.cn/Article/details/gtamfxhojn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hysaishi.cn/Article/details/gtidclapdd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.guannengcc.top/Article/details/gtiqopbdjl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tianlin.xyz/Article/details/gtupzcxafm.html

TS:   if (!x) {}
来源：http://dali.tianlin.xyz/Article/details/gthyprjmjb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebzbbcso.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gteqaiponj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhoulong.xyz/Article/details/gtobgcmcba.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuysfjnm.html

[A17] 位运算
来源：http://dali.zycfv.cn/Article/details/gtxsvwbfyq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqnkvera.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnqzz.top/Article/details/gtgdjroxtm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtlygsqqwz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtzbyahxem.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtjpxrncrq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtfiubbzmo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtmgtjushk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtwfrttdgp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.wangdashe.top/Article/details/gtvaxvquas.html

Py:   ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gtujmrhrpk.html

PHP:  ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtstqvjija.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtabseqbmi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gtzopydogs.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhengqikj.top/Article/details/gtuwancocq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.havefunace.top/Article/details/gtgdokjufr.html

Ruby: "A".ord; 65.chr
来源：http://dali.shangyingyoupin.top/Article/details/gtglqqmpad.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gtpsvunoyu.html

[A19] 交换两个变量
来源：http://dali.zhengqikj.top/Article/details/gtjsempsmd.html

Py:   a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtwhubukat.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.mhx1999.top/Article/details/gtzqkyrkwj.html

JS:   [a, b] = [b, a];
来源：http://dali.hnqzz.top/Article/details/gtejtkhybc.html

TS:   [a, b] = [b, a];
来源：http://dali.tanke756.top/Article/details/gtgpacanxc.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenlongwang.top/Article/details/gtzjjlojut.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gthmpwpqyo.html

Ruby: a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtojokwrij.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gtvgfwvaxq.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gtxdabdtcw.html

Py:   name = input("请输入：")
来源：http://dali.shuidangran.top/Article/details/gtxtbzzfxv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tanke756.top/Article/details/gtkzvhzoow.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xinyue.icu/Article/details/gtcyzpvocq.html

TS:   // Node.js：readline 模块
来源：http://dali.bjfxy.top/Article/details/gtgrzddmbe.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yvedp.cn/Article/details/gtdwsjziut.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenlongwang.top/Article/details/gthqlizkpo.html

Ruby: gets.chomp
来源：http://dali.yanxiufei.cn/Article/details/gtfdirbbnn.html

C#:   Console.ReadLine();
来源：http://dali.hnqzz.top/Article/details/gtlapwxslg.html

[A21] 保留指定小数位输出
来源：http://dali.ybcxt.top/Article/details/gtnvqkdfhe.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gaohongyu789.top/Article/details/gtjkaoghvw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtwxichagf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtjztwcbwe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtqqhnbnwc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtqxkdtzft.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtgdgkimoz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtlorigffu.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangtech.top/Article/details/gturrkpmqz.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktcvjzeo.html

Py:   len(s)
来源：http://dali.gzhubu.top/Article/details/gtpmfghxxh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gotoacloud.top/Article/details/gtwqrrhlhl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gtgzieoymn.html

TS:   s.length
来源：http://dali.nwbrower.top/Article/details/gtssxiddpu.html

Java: s.length()
来源：http://dali.sxryk.cn/Article/details/gtixawqoqy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtawmlskfo.html

Ruby: s.length
来源：http://dali.nwbrower.top/Article/details/gtnvndpwet.html

C#:   s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtgxqbniwg.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtlqtlpbps.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gthvysjbbk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gtasbvroaz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtytfpruaf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtobhdvoep.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtlqgyrbvd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbucmqcka.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtsywarfnj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xylfe.cn/Article/details/gtzvcawfgs.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gtramupnaa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ppjwa.cn/Article/details/gtjypslytr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj20258888.top/Article/details/gtyucpmnxq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtyxxlrovq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtblvhmzxq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gtteqprdnz.html

Go:   strings.TrimSpace(s)
来源：http://dali.jianghu66.top/Article/details/gtnfeufoff.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnxiangtu.top/Article/details/gtgzifbsuy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtldfmianw.html

[A25] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjfuzjak.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhengqikj.top/Article/details/gtdpjlatte.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gtdblhjhla.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpepbbcm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtaecpvsej.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnqzz.top/Article/details/gtfojdaeei.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtxhtcitbq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xziqi.cn/Article/details/gtmcvjpekb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gtxewcpuyg.html

[A26] 类型转换总览
来源：http://dali.wangshuangyany.cn/Article/details/gtlyadhnqh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtwdkjspql.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gtdhyvvgvs.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aizwys.cn/Article/details/gtyignoyiz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsjiablm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtctsvbzfq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtdcquifxa.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yonumen.top/Article/details/gtrbwwtzly.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtkznzsbcu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtixvnbyzk.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gtmhqvscjn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlluubqfs.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtgqsvpstk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtvzwyykgj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hywenlv.cn/Article/details/gtqjnvbdmh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtmpvvtlyf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtossflkbc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtdpljedyz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsulypxl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.0kj1m.cn/Article/details/gtiqdesqtd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtjwsujtwe.html

[B02] 多分支 else if / elif
来源：http://dali.fengsongda.top/Article/details/gtzihvkpmn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hongshengwenyu.top/Article/details/gtpdfvxmuq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cashguo.top/Article/details/gtblyspequ.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtbnexattr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtesmgdtst.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtnuspcbio.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gtzikvmtxd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gzhubu.top/Article/details/gtryslpsjh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtewbbjigm.html

[B03] switch / match / case
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdabjoghp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtdmkimtlo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtqloddbqk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gttqiitxoq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtkvugnpnd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtpqvoytzw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hywenlv.cn/Article/details/gtjivrashz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yvedp.cn/Article/details/gtxblfqrup.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.smart0.xyz/Article/details/gtqhxmogqh.html

[B04] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtezionqsy.html

Py:   for i in range(10): print(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbovohuc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gteediuvvb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtahyoqmev.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfgdabgpe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.smart0.xyz/Article/details/gtyndjacfu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gtcbwngjvp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258.top/Article/details/gtjjqviyae.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xylfe.cn/Article/details/gtwvmtvqyz.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtexbeveeg.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gtmkfitjcl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnxiangtu.top/Article/details/gtinxbfroc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtkdgjqzlp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtuffwakku.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtqelnvyvd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gtslarpmtz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yongpay.top/Article/details/gtpdnyvstf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gtcieubzec.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gtekdnjpmi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbnvebhy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtekwqwdvm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gttepmdtas.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtisgeetgr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtcugsyykw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuanzhike.top/Article/details/gtwvsqoube.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtireoptph.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemqbekfr.html

[B07] while 循环
来源：http://dali.wangshuangyany.cn/Article/details/gtnxvpgnce.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gtpgqfzzgs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuanzhike.top/Article/details/gtlnfghrku.html

JS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtbkvtebcq.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtcrxmnyhr.html

Java: while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtgowrboqz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gtlqyfcuro.html

Ruby: while i < 10; i += 1; end
来源：http://dali.birdmap.top/Article/details/gtpjvhuzdz.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtfhmkpaop.html

[B08] do-while（至少执行一次）
来源：http://dali.aizwys.cn/Article/details/gtammdcymu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gtesylmdbg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtvuuztsif.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtmgfffvsf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtvqhuxuag.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgznccgb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtevindsft.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gttnfzlfnk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtgkpvbgqt.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gtkxchpgly.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxinkj.top/Article/details/gtpiqntvqf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzrzymfj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtmbsvhquv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtqeyqzfow.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gthzpthizo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtzxkzwukh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gtkbvmmjdm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvsfyoqji.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gtsynnkvwo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gtzbphqxyg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gtydvifkjm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtznolypnh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtoyltilkt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gtldczkipb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gthzrvoemx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtkmictqir.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzbmkzong.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtxphvibab.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtpvlifnce.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtdfbeuknu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtfrqflkic.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnpldkft.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtomdianaa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtmhcwblrw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gtuxriuvvt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gtsvhuppum.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgfhndzw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gtwtoeuuel.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gtynuyfyxs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtimimrunh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtclahulka.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtsuzrubpy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gtdqwgbhob.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gtzjsoqvuh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtfvoxjsyl.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtymoyjszd.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gtnitfnryg.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gtmhioetok.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtwqaqvvwg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtsppiyooo.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gtdspdsbun.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtewwdqeqt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtmiubyvnu.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gthhklcifs.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtrwrywgox.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtkqogruut.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gtcarkcnrd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtqavqdfmv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtrnnnvyvq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtfkvojtzc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gtmrkdbkkv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtxlbjtcod.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtrjnoqyff.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvrjtbjz.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcilrhkpz.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtokzobtis.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtklwqyrkl.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspfrzznv.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtmfccnoqz.html

Go:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtwsianmft.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtwsclvyfe.html

C#:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtaubyauoy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtrloifbcp.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gtlvmxgfdt.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gttqvqdtae.html

JS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtykmvbyea.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtoqfhnxgi.html

Java: if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtttvsvvqr.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtcklstrnl.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gtnpscutqu.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtyxxwxrai.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbbsemcip.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gtrcemfkee.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwjdqswyk.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtrvkrkhed.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfmirjcs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcrbyrwaw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtxfvuqhgl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtlpesawpd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtprwcdqoa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtanklmjag.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtservgzod.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtetszqcuh.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtdhkiuxyd.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gtrehccofj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtzthjsm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtreggulac.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtzqyovqxm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gteuydkwcx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtabbustbp.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtajlppcxg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gtuboynden.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtjelghfyd.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gtvlixyntj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtrkiklhth.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtlexpurvb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtmannsgtp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyguonlpp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtrvgaonhm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtfdlpsqkq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtgzoplytd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ydzc1.top/Article/details/gtuxaseoov.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtqlgouzax.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtcyvgjnlq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtkmaqjdhz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtywuihibd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaofgolt.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtdmnhsuqm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gttksiasgy.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtshzpzlak.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gtydnmsope.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtqsomblkp.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtwjcrhfbn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gtnbzyscvd.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtjqbrmpqx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtbpkcjkqx.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtrzcdzppg.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtoylgdgxf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtcxqckapa.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gtpymeqkyz.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gttuvnmbws.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtkpqvijeu.html

JS:   const square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtcslefvyu.html


<!-- 参考信息 -->