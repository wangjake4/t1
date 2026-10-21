代发 wailian999

C#:   (int)'A'; (char)65
来源：http://dali.hnqzz.top/Article/details/gtgmpvwaut.html

[A19] 交换两个变量
来源：http://dali.cashguo.top/Article/details/gtihpokcrf.html

Py:   a, b = b, a
来源：http://dali.cqqwz.cn/Article/details/gtqtxmooyl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yangfankeji.com/Article/details/gtqbkdnawr.html

JS:   [a, b] = [b, a];
来源：http://dali.ydzc1.top/Article/details/gtlytqwycz.html

TS:   [a, b] = [b, a];
来源：http://dali.hnxiangtu.top/Article/details/gtkozspmig.html

Java: int t = a; a = b; b = t;
来源：http://dali.cheryme.top/Article/details/gtsxooocwv.html

Go:   a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gttrtbytsy.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gtmjsuqhai.html

C#:   (a, b) = (b, a);
来源：http://dali.shzxlz.cn/Article/details/gtsqnxcffp.html

[A20] 读取标准输入
来源：http://dali.yueranfly.top/Article/details/gtvwqvikus.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gtcivwhrht.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hysaishi.cn/Article/details/gtiulmdghm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guannengcc.top/Article/details/gtdlmrqgup.html

TS:   // Node.js：readline 模块
来源：http://dali.yueranfly.top/Article/details/gtcwcsvljo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhfjsadv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yanxiufei.cn/Article/details/gtqjcskada.html

Ruby: gets.chomp
来源：http://dali.wangdashe.top/Article/details/gtkzjcmpob.html

C#:   Console.ReadLine();
来源：http://dali.sxryk.cn/Article/details/gtuuwnilfk.html

[A21] 保留指定小数位输出
来源：http://dali.guannengcc.top/Article/details/gtzynfybhy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.haohaochexian.top/Article/details/gtfagrfhth.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtcihojtqe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtmbslcvcp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtmrczonqf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtjyemmxob.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtdladwmyr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtpennlqou.html

C#:   3.14159.ToString("F2")
来源：http://dali.ehwqpu.com/Article/details/gtqxrqvzha.html

[A22] 获取字符串长度
来源：http://dali.bjfxy.top/Article/details/gtpdcaewos.html

Py:   len(s)
来源：http://dali.cheryme.top/Article/details/gtimgdsnbj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.mhx1999.top/Article/details/gtghwnxfip.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gtrrsegggr.html

TS:   s.length
来源：http://dali.shangyingyoupin.top/Article/details/gttryhvtfr.html

Java: s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtpvsbmmxv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.0kj1m.cn/Article/details/gtdcqppwdp.html

Ruby: s.length
来源：http://dali.ybcxt.top/Article/details/gtaopdpcwf.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtgykwngvr.html

[A23] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtamctvzlo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.aizwys.cn/Article/details/gttfiumagw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shuidangran.top/Article/details/gtaugyadtd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gtczpkpolg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgdovopi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtadoealca.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.0kj1m.cn/Article/details/gtdyckgtyf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtpulgmhkb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtgxjdywde.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gtwcnyenlp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gtnmlssluo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nwbrower.top/Article/details/gtdlwkpnim.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwwbnykh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtwlkyxxjs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gtfghdvfit.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258888.top/Article/details/gtwolzyubp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dianchejie.cn/Article/details/gtcjpxmesv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtqzyhognk.html

[A25] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtndpucroo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxuanxn.top/Article/details/gtvbnwlorn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yongpay.top/Article/details/gtgnxtndle.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtocdazloa.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtjwcllmry.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceccxfqh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtyjqkuvow.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258.top/Article/details/gtvhzqllis.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hammf.cn/Article/details/gtxksopdyv.html

[A26] 类型转换总览
来源：http://dali.dianchejie.cn/Article/details/gtkrayanyt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gthxawrdpm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfctbbgmh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.0kj1m.cn/Article/details/gticmgrczj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gtsxpgutjf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtspviuels.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtiofyaftf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gtngxcnpur.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtfzkbnxvt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtixpiroyl.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gtqofzqbuy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwbmhbakm.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtqxypxewq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaowivres.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yangfankeji.com/Article/details/gtbgryxlkg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtexbnvglj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtzqziiiyy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtykjgruaj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258.top/Article/details/gtpaokuxzw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtxiziajfc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtrwjcwbnu.html

[B02] 多分支 else if / elif
来源：http://dali.haohaochexian.top/Article/details/gtxvaboivv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sysykeji.top/Article/details/gtwtvpcwle.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmwbovlqe.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtfrhfpfoi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtuwtapkdy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gteeomsqnx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzblzpdpf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zycfv.cn/Article/details/gtnpudvewt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtutzawguf.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtolhaypvx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fengsongda.top/Article/details/gttjvpulep.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtoorbxldd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtshepefnd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtzryrpzym.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtrnwiouls.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cashguo.top/Article/details/gtvivflpjj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yvedp.cn/Article/details/gtrnscuwtl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtnxsxgkbc.html

[B04] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtjmvbmmih.html

Py:   for i in range(10): print(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtzrhnklpo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gtpriqzrvj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtizshpzot.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtbuieneqc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmigfekt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.mhx1999.top/Article/details/gtztmanosa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtahccstxj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gtgitytnuh.html

[B05] 遍历数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtglmpwqji.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkexoshyg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dianchejie.cn/Article/details/gtozqgmoik.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtvlqbkwuw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtzuttefww.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtscdpnmrw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gtlfadxlno.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gtnbgccnsg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtrmfhhdqm.html

[B06] 遍历字典 / 对象
来源：http://dali.yj202588.top/Article/details/gttllgsbbi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtgireiobv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtbwcpsglr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtveshzrla.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtaalwnals.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sxryk.cn/Article/details/gtbfvfnszw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtsxqvpfls.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.haohaochexian.top/Article/details/gtzuczjhoh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gtchqdfrxo.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gtmsiuxiwt.html

Py:   while i < 10: i += 1
来源：http://dali.quarkkingdee.top/Article/details/gtnahvxwjl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gtmkojyckq.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gteimxupoz.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtveqrbafk.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gttezukesg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gtylrkjrlo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gteiwvklmt.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsslwxjqv.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtcsoclzrf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwkegdjs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtlxiyfvmz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtucbyohtx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtufeaczof.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkynrwdx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtxycipcxy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxinkj.top/Article/details/gturiimgia.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtgxnuluvm.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gtcakzmvzt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtntkqggtr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtzoagnfkx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtntnvrzlr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtkbwitrbl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtettmlteo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gtpgiurcli.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gtgzpvpttz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gttfsikgmx.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gtqrpokgyj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cashguo.top/Article/details/gtgkzokusa.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtdwnplwaq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtfpvmhehr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtndimeiyt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gtozvohioz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gtjiatakoh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtgnaykppg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gtyurtcsmz.html

[B11] 生成数字序列 / 区间
来源：http://dali.kuanghao11.cn/Article/details/gtlmievwjh.html

Py:   list(range(0, 10, 2))
来源：http://dali.cheryme.top/Article/details/gtgwarzgrq.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgugpcnvh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtznqkyaxi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtlgsypfas.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gtkdrwourr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtfbbrcafc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtgxyfmqfl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gttfpklewf.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvirkcbge.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtalzyhcdu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gtaaurdykw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtknuifccj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtvtrgrvdm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtwtlbupnz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtwnwornmq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtamqrjwil.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtrogakpss.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gtptqiveqg.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gtcyrduvdy.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtivgfhhpi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtlgiquwmi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtjhvdpodj.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtfsovebam.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gthopkqaji.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gtfcudiljt.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gtuogotpkk.html

[B14] 判断值是否在集合内
来源：http://dali.yangfankeji.com/Article/details/gttzqnvnod.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtegcmkmjg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gtcubhoekm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtexycrnod.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtyhyosvyg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbhgkqmyp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gtsapobzbt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtbtxuxqwb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtgxsbfdby.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtglwisksg.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gthczfjymv.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gtuhotbvyl.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtnmjsogkh.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtmwayijya.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtdskasfvj.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gttvvvkial.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gturpymvmi.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtwrimzvlo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gtjnyyyxur.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gtoneivpfn.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gtsdtnkcvp.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtqmwjceay.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gthyvpbzww.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtfqddzgym.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gtmfwkksud.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gtmfdazoyr.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtazznuvhd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmdenttth.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gtqisfqaaj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlbzqkmab.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekddcufq.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtkalthkzf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtbaooconz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwnqzazm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtcqwijczw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtflgejjrf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtepmoncyb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtuzqfkqbg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtorwiytks.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtmbmuhgpg.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gtczmybakw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtwzzahkpm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtytwelkzv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtxifbgpsk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtrpwojkqu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtddzvgpoa.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtpoaaotfo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtfvlhtbjd.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gtrardkyxe.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gtdcptqqpm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gtraskuohc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtqppcrtdn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtwmpjvgsr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtcvhuqoja.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtabnwtlxu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtsjhdbamn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yangfankeji.com/Article/details/gtucljnpar.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gtmnxhsvkc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwomyohw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtjkxhhbth.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwbylvzfq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtmrqlnncr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gtdkttrxah.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gtpxsnfock.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtinpgwamd.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtjmbmvaej.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtbvtsdvpi.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtpvilhpdr.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtqukhifiw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtbjhfasgh.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtnnoueobw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtfftsaidi.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtcszjdnya.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gtibouesbu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtgmyeeyvx.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhsyetec.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtbsfvkuqd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtsbrmzfuj.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtvwpygifu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtgluhvjsm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gticpmwoam.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gttwhwzafv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtfdxyfkgn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtackpkbab.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtfxrbyjlr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tanke756.top/Article/details/gtqdpxhjkn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlncxbmi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gtzdmzkcxm.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gtytpidoob.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtblrojvic.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtkwvlfzwo.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtbfrfejnw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gtmbnkktmf.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gtmemyckye.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtrtnhtzix.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtadtqgtyt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtlahusnfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxsiwkdnf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtuleqbllv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gtnyqgjnfq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtzhttjcuw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtpcdfaieh.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtxiyancoj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtxrzphmdn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtnnflaenq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtgdslbugq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtppjhkufy.html


<!-- 参考信息 -->