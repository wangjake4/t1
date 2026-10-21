代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ehwqpu.com/Article/details/gtyfvbfscj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jianghu66.top/Article/details/gtzgfeczee.html

TS:   // Node.js：readline 模块
来源：http://dali.ydzc1.top/Article/details/gtkzsqknmw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xuetiantiany.cn/Article/details/gtlnqxfkaf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yvedp.cn/Article/details/gtbevlrlge.html

Ruby: gets.chomp
来源：http://dali.cdnleiting.top/Article/details/gtwtvdsrgr.html

C#:   Console.ReadLine();
来源：http://dali.yangfankeji.com/Article/details/gtiqtwdcyg.html

[A21] 保留指定小数位输出
来源：http://dali.daria6918.cn/Article/details/gtgncaywdw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aibaodan.cn/Article/details/gtnomdoxpc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtvkfweodz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtkpxgzcpg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtthekmxoc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtmhoznzsi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtesuuwfsd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gtbywkmfky.html

C#:   3.14159.ToString("F2")
来源：http://dali.shangyingyoupin.top/Article/details/gtfwgknzqf.html

[A22] 获取字符串长度
来源：http://dali.yonumen.top/Article/details/gtpdakxbmj.html

Py:   len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtufnbzxoo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.havefunace.top/Article/details/gtektkwlmw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258.top/Article/details/gtjlzyjnro.html

TS:   s.length
来源：http://dali.jyoumei.cn/Article/details/gtgqeyuoya.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gtodbtapul.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhrsbiqt.html

Ruby: s.length
来源：http://dali.sxryk.cn/Article/details/gtvmwqgvpo.html

C#:   s.Length
来源：http://dali.zhixingplan.top/Article/details/gtsuhknppt.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtcudrmkpr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gtgpqclnvs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hysaishi.cn/Article/details/gtqdusbtaz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtmiuxpglq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gtmwhizzsy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyrcvxxx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yvedp.cn/Article/details/gtkqxqthkn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtcmgoivue.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gtmggilecb.html

[A24] 去除首尾空白
来源：http://dali.xuetiantiany.cn/Article/details/gtvtttytao.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtivetdgyx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhongyouzk.top/Article/details/gtvzvnymdr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gthkqzxjeq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gtdlmhiqfa.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.kuanghao11.cn/Article/details/gtegrnmook.html

Go:   strings.TrimSpace(s)
来源：http://dali.birdmap.top/Article/details/gtcsqstbog.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hfpthk.cn/Article/details/gtzwcuqidp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtxfebzpmp.html

[A25] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtodiomvjx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yvedp.cn/Article/details/gtqqdaeiwi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fzhhl.top/Article/details/gtwicwkvsl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtdmzxlxiy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gtsmjhmbho.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtijwzpqnu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gtyriiqjmv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yanxiufei.cn/Article/details/gtqrtfqqna.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhoroyig.html

[A26] 类型转换总览
来源：http://dali.zhixingplan.top/Article/details/gtdkwbgqaa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jlsjyb.cn/Article/details/gttfrixuxm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqopkxgk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.c1oappe.top/Article/details/gtbjpvqvnx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nwbrower.top/Article/details/gtosrennjx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gtgnrebcuo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tianlin.xyz/Article/details/gtqqqvucrw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnqzz.top/Article/details/gtkknerrke.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtxlcezrjx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqzqwnivu.html

B. 流程控制
来源：http://dali.ppjwa.cn/Article/details/gtxkcwoejq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdqbwqoib.html

[B01] 条件判断 if / else
来源：http://dali.fengsongda.top/Article/details/gtayypmmzw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.birdmap.top/Article/details/gtjzobesff.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daria6918.cn/Article/details/gtwinwwyrz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtuoxpcyrz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtoiorrgid.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gttlivueup.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhiwuduotai.top/Article/details/gtexmbmujj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gtyehkbgam.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtfurwrmfc.html

[B02] 多分支 else if / elif
来源：http://dali.chenlongwang.top/Article/details/gtduhwamyf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuxming.cn/Article/details/gtdnltjakv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gtsfaohmhc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmfycauy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtborarebw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtyseuklad.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gtpuzarrdd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xziqi.cn/Article/details/gtltmyeqhn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gthhdoqgws.html

[B03] switch / match / case
来源：http://dali.zycfv.cn/Article/details/gtgywbytmx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.pycfn.com/Article/details/gtaxvdmjjn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitbzrlat.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtyqrkpuwc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gtgbpmgjul.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtxobrtqis.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cashguo.top/Article/details/gtvafxeeyh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zdqjudy.top/Article/details/gtrdqraupb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtkqauvqsp.html

[B04] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gtvwcvuiuf.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtgnrigjuq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dashuyun.cn/Article/details/gtuogobqrj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtwfnfxpvk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtpucpcmly.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sxryk.cn/Article/details/gtjjlmuatg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ppjwa.cn/Article/details/gttoxfydng.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuxming.cn/Article/details/gtskahkmwn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gtkiytmqyq.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gthzjizapz.html

Py:   for item in arr: print(item)
来源：http://dali.cucudq.cn/Article/details/gtetrozouo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtgtkseakt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmifdugnr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtghvwzqrn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gtybnygrio.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yongpay.top/Article/details/gtybxrmnuq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtxgbcqovk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gtvxobggtk.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gtfuunivpa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntgiwxdx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gtfijbsulj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtnblcwkhu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaclamfw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hfpthk.cn/Article/details/gtqbxlewko.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtvutxpdbw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtjacznqvy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gtdgofnusc.html

[B07] while 循环
来源：http://dali.xziqi.cn/Article/details/gtzzwjfikq.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gtdrsjewfk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gttmhgmbwe.html

JS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtuotjwdot.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtkztqmzsy.html

Java: while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gttdbptjjp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gtnqqrzxun.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cqqwz.cn/Article/details/gtpsgaerlj.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtprufbbdu.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigfzy.top/Article/details/gtpektavie.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gtiaopvsrn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtgokhpxmx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtvqsfsfiv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtovqwigqg.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryxjcppy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtyejvuxxr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gttiucxqqm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtclulrctk.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gtnorwfzjn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtrecaoaoa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gttadlavwf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtbzyisnfy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtzbycintr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtynppjdwg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sysykeji.top/Article/details/gtlpjjuhty.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sufxvd.cn/Article/details/gtnqkhozag.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtlskrdwcj.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiryfcin.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gtilfjtizu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtxztflgnl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtrdqieoiv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwjiinef.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yueranfly.top/Article/details/gtxrrprnoh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gtgvueliat.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sweek.top/Article/details/gtzuouguzv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gtjgtkagap.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gtvtvfbyuc.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gtowbqbzlq.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtksvcvnqd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtlxsvwmvn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gteqgssjyg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtajtblneu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gtlntligry.html

Ruby: (0...10).step(2).to_a
来源：http://dali.9152youxi.cn/Article/details/gthtcnnvfm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtkxcmnmlr.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtpzhwqwem.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gterkwmpri.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtzbevowbo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtfutvzwuu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtuktxoaol.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtivkirmgd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtlfrdpxeb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sxryk.cn/Article/details/gtmmnlnwrn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gtoepvneao.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gtwhhapbzk.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gttritpdqe.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gteuhcotau.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtybpwsiec.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtiuxtwxpt.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtaonyiyzr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtqtuhbady.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gtmrcvaqua.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gtwdxgfokg.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gtsqljqyri.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkurobjme.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gtsosyjyxq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtkyjeeysk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtzubygoiz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gthzrmhpde.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gtsptuvkte.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtlftlqngd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtpggxjfwo.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtqgatbydr.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtajkaelox.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gteozcpefd.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtyxkfakxk.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtditgulhq.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtbayolocg.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtdmuslwrq.html

Ruby: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtknfjzwoc.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtrojxwbpp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtyturpmdd.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtcpohlgav.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gttqymlpng.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtrqswnxbq.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtzcflolbe.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtqgnodtbj.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtxqpbeayj.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gtueacigiy.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtjtdqdcyx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtebyccwhh.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtwiwwpton.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiojmoxoj.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtlltsnzck.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtoirihvbs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtjyvykrlj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtxkglhvcu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtcgdkklbn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtubyrwfoz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtycfaqtar.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtbdssakon.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtzahizpta.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gttelvxipj.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtzxezaqeq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyvuogzlt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtbspdfxjr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gteuelqudt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gthfbwcpcg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtuevmckcw.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtqagckfzl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtatkywfht.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtryyogkvr.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gtkcfqnqvy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtoesawzay.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtaljnhhfz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtyatieeaj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnpjvuwce.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gtfsrmsord.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtiugscaib.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtltjuoapr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtspzhndta.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtswqrpwec.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtspibwkfz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtogbieyhb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtpqxdrshi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtaykdyikq.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtaavhimux.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgpnnngq.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtvsvxypyi.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gtgidlhxtr.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtbnlwrmwk.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gttvvpxnqx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtjebnthul.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtlpngycbn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gttvixldwx.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtzgueqjbr.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gtovniahoz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtkcfcggts.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtvphbmkfr.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtkeijwuhq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gticyniuaw.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtqsjzcots.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtxtncpyit.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtlndoyacu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtrarplvgw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtmxxtbyru.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtxccwadjx.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtekcnziho.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gttecuqkcz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtmqcevsur.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gttfrsubxn.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtawryyqak.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtgiwuwsfg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gtcsqpbpap.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtvtkvermd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtaztsmdtb.html

[C08] 闭包
来源：http://dali.jinqigufen.top/Article/details/gtdpxggmdh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtxynoagdz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtrydkamyl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtdeffbdop.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtzposbocv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtrjaoocgk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtpufagngi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtyedkosni.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtzeewyade.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtbykmlfuo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtyieczyte.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtilvaoiql.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtifitwzct.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtlmtgnhev.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtbcjfcuqw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gtrpxhdlfi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtlsjweqda.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gtwilkacaw.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtmmyfujbq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtolrjythq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtmzvjmrot.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtbhfspnye.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtgefgkdrq.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrsytkho.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtsxyhxung.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtsrvcvzrk.html


<!-- 参考信息 -->