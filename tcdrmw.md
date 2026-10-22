代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtnkawfxzv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtaapwhbrl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtnpjrrdhj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtjuccsqsk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jlsjyb.cn/Article/details/gtrxlwnucy.html

Py:   ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gtyhrtwods.html

PHP:  ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gtvduwxiwb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258888.top/Article/details/gtseleixbc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtoulbilar.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenzaomai.com/Article/details/gtvuqremaf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gotoacloud.top/Article/details/gtibjxnpdp.html

Ruby: "A".ord; 65.chr
来源：http://dali.bjfxy.top/Article/details/gtzsdtlsix.html

C#:   (int)'A'; (char)65
来源：http://dali.shzxlz.cn/Article/details/gttkvsiere.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gtalhypycu.html

Py:   a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtechujinb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gttuwchbxs.html

JS:   [a, b] = [b, a];
来源：http://dali.tian-w.cn/Article/details/gttrcyxxin.html

TS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtstqclrgs.html

Java: int t = a; a = b; b = t;
来源：http://dali.hnxiangtu.top/Article/details/gtvmphjomh.html

Go:   a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gtxdvruhwm.html

Ruby: a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtkkeiodms.html

C#:   (a, b) = (b, a);
来源：http://dali.zhongyouzk.top/Article/details/gtjminnfhw.html

[A20] 读取标准输入
来源：http://dali.tian-w.cn/Article/details/gtjkzwetig.html

Py:   name = input("请输入：")
来源：http://dali.andypj.xyz/Article/details/gtjjffqpff.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.vqdsnc.cn/Article/details/gtsdagfjmn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangshuangyany.cn/Article/details/gtxypomhlx.html

TS:   // Node.js：readline 模块
来源：http://dali.mhx1999.top/Article/details/gtkqmcsset.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hysaishi.cn/Article/details/gtmhiaoqly.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xinyue.icu/Article/details/gtvvfclmgd.html

Ruby: gets.chomp
来源：http://dali.cashguo.top/Article/details/gttwttbzwj.html

C#:   Console.ReadLine();
来源：http://dali.cheryme.top/Article/details/gtqtnphqcc.html

[A21] 保留指定小数位输出
来源：http://dali.sysykeji.top/Article/details/gtgcavpgfl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.feifeiyinyue.top/Article/details/gthpflcpyk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpiqiljj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtbbmrkiov.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtdzihedpq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtcaevwqlv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtdbetolqq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtcvewegxy.html

C#:   3.14159.ToString("F2")
来源：http://dali.aibaodan.cn/Article/details/gtotmwkhsn.html

[A22] 获取字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtjsyiivex.html

Py:   len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkwlqvov.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangdashe.top/Article/details/gttnsccpfb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gtoivfugjv.html

TS:   s.length
来源：http://dali.guannengcc.top/Article/details/gtcvsgcfyq.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtftadqodb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpmwoavoc.html

Ruby: s.length
来源：http://dali.zhoulong.xyz/Article/details/gthmiskbgv.html

C#:   s.Length
来源：http://dali.hysaishi.cn/Article/details/gtzbkxbbsz.html

[A23] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtfjnevweq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ehwqpu.com/Article/details/gttkzywwcu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhoulong.xyz/Article/details/gtofrhvedy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gttowdshys.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gticgukmak.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtsbucokpc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenlongwang.top/Article/details/gtyoiuyjfk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvxaqmhk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenlongwang.top/Article/details/gtfrsiavbc.html

[A24] 去除首尾空白
来源：http://dali.nwbrower.top/Article/details/gtgbqdrcrx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.guowangkeji.top/Article/details/gtlcmgnovr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxxnerjmc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtehyqecsc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtdmtzmbut.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yongpay.top/Article/details/gtuvngmmcu.html

Go:   strings.TrimSpace(s)
来源：http://dali.jyoumei.cn/Article/details/gtydpcfwhh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ydzc1.top/Article/details/gtuylmirhk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sufxvd.cn/Article/details/gthqtjqiky.html

[A25] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtoznpgkgb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.bjfxy.top/Article/details/gtcmlrfpwf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.snrcjt.cn/Article/details/gtkxctkwec.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnltfyizi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtovmdbqeg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtpsounfnr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsshbhrfk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gtaxnbpprv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gtlwmkdlmn.html

[A26] 类型转换总览
来源：http://dali.jinqigufen.top/Article/details/gtkqlggzlj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtlrjtmvmg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258.top/Article/details/gtexihoeon.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zycfv.cn/Article/details/gtuzgxltvx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ivvv.top/Article/details/gtbgypssre.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtkyajuyha.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuxming.cn/Article/details/gtvhgupvzx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fzhhl.top/Article/details/gtdvszdfue.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtxlbtgglq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlgrnflbl.html

B. 流程控制
来源：http://dali.cdnleiting.top/Article/details/gtdsfzazbo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzmcaszha.html

[B01] 条件判断 if / else
来源：http://dali.gaohongyu789.top/Article/details/gtqsunugjz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnqzz.top/Article/details/gtfkdelyqh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gtdkkfpflr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtwguamybj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtylrejhlc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gthmejtmut.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.havefunace.top/Article/details/gtmncsvxer.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yueranfly.top/Article/details/gtliiftodr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtvkfnomtu.html

[B02] 多分支 else if / elif
来源：http://dali.yuanzhike.top/Article/details/gtpnnppbyi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gtyfkzkkuq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.snrcjt.cn/Article/details/gtydrdrqek.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtxfejdrky.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtotbpmvzx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtdrxrqqqi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xziqi.cn/Article/details/gtspzgbyda.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxggigpa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtrwejzmjq.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gtqjhvyjbq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gogol.net.cn/Article/details/gtumqfzlel.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtldugujzq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtycwevmwi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtixjaosfy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtojhurgcn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtwohsiahm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtrqdjdjej.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtjpcwphfh.html

[B04] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtsmetyhqy.html

Py:   for i in range(10): print(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtpudckcxr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jlsjyb.cn/Article/details/gtcbaayiie.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gttlbzfzwc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtvbktdtwa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtaimgafek.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gogol.net.cn/Article/details/gtjskzrlti.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gtsfvizzrk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgufenzy.top/Article/details/gttdozavvz.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtlmqqrdxt.html

Py:   for item in arr: print(item)
来源：http://dali.ybcxt.top/Article/details/gtdcvuwrkq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gtezzgefip.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtwykvyxpd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtxdsnvaxa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqeprdem.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiwbexbx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gtvwvqwgth.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gtaszvaoni.html

[B06] 遍历字典 / 对象
来源：http://dali.jiagoushi.top/Article/details/gtpkykzhro.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatzqqeuu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gtkroozcez.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gtcmkqidzv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gtsqgiekhm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gtvculzkbt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yanxiufei.cn/Article/details/gtedmyxufr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gtwpwlfabr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gtkczdsltt.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gthzhflbhq.html

Py:   while i < 10: i += 1
来源：http://dali.guannengcc.top/Article/details/gtfsdcswky.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtzxqwsgpa.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtyegittlo.html

TS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtprkqwxbb.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtoaivxldf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gtnmyvfbei.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtxektwlsj.html

C#:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtaufhlksn.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gtujfcerbs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fzhhl.top/Article/details/gthikedzao.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtzalhdred.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtoaxmjkcd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtepqlxdaf.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtdwnukosh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.havefunace.top/Article/details/gtcbxzdbrd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtsrucvszh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtiywptdgv.html

[B09] break 与 continue
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcsqqknj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtxjncktul.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtnhbnkyak.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtqcjanjqd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkebroad.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtequtsdnl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtevugsgiv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpgrwfpq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtfwrfetug.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtdxypajgf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hysaishi.cn/Article/details/gtonnecyjt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gtteoobypy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtgtelrgat.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtkfojrqhc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gtlizmwhzo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gtrllpyjtd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258.top/Article/details/gtmrsiwzgb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gtfwlbpslm.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gtseeijbnl.html

Py:   list(range(0, 10, 2))
来源：http://dali.dianchejie.cn/Article/details/gtduhkitwm.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtnwbsagcn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtiktrycup.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtvxlgxzac.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gterkxvaos.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gtdobsidib.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gtoapwlekd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtqivfjyak.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gterkjcayz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gtmmhxyutd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtijhrkczz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtkmzjahne.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjufnpzcz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtjjjpczal.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gtmhfzwqya.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gthdsccpxa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtnfkbqgiz.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gtltrugbrs.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gtmyssbuwv.html

PHP:  is_numeric($x)
来源：http://dali.yonumen.top/Article/details/gtgzhrlfdx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtpjvxhiwb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtbxtcomqr.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gtccqfgonp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtefwgskhv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gtgmyzgugj.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtvhxwjrlw.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gtorszbrii.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gtilbcgdjr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtiarzdemr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtzyaxffut.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gthvszzqyn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtrnhwfn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.316326.xyz/Article/details/gtrrteelvx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtcaqploim.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtifkpszfk.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gtiahbbgpf.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtoqixmnoq.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtkqgwgevy.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtpuzifzgq.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtwuhukhcy.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gthyukcwhe.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtmrjxpnws.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtwetgwqwi.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtyqidwxuh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtxaunntbv.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gtrqhidfos.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gtgcnpwiwe.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtnqqegugi.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtjchacwyq.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtkzsbbngg.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gtfesmdult.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtvlmwwjpf.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gttuwtmhgk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsqfiedfa.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtoeujbnqo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlluyffhp.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtdxkgglck.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtzdejkwes.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtsoryuhpp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtslpyeqlw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwiwszcls.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtsqvwidws.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtwwobbugq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtkxkernoa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtypdpzpez.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gtuxwifwhe.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtrpxgymak.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gtqvplnjko.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gthggqrfpi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtcknjbpcd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtrxdpmghz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtmdczbkhf.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtfsprlmii.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtojsuaxkt.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gteesrjxxz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtawjdnwre.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtgckqvono.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhrkperm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtnsyslsyl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtwsjpsvkx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gtnpvkeusm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrynvufmy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtfjtsrhus.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gtfwpmdjdc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtacyzqyqs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtqoqhhdsh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtpkiauazb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gtzfurrdai.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtjmgbrjsz.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gtsojjisns.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtfpbucajg.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtfceirbuq.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gttnmqfemc.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtsdmuzenz.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtbvpzfsiy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtapkgvktp.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtaovschmx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gaohongyu789.top/Article/details/gtudrdweyh.html

Go:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtiawqxfss.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtxxqtmvct.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gtwbnxsils.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtpkaucwdp.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtrwaouhpe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gtibnzgxji.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtinhswpqn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtjxublsny.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gtmwskmmdw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtckqxmjtr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtczitsfnp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtzlkwuudl.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtbtjvzctk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtfglrkffh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gthshrbvlw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gtkufqkrki.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpelqlddw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtucvutmhe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtlvpffofx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtfvgdctry.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gtzbtroefd.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gtptibpobm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtdhbowjwc.html


<!-- 参考信息 -->