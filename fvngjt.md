代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gteehiuizb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtmukbszwx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtcebdziie.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gthpoxzzxl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hysaishi.cn/Article/details/gtimbpmbzj.html

Py:   ord("A"); chr(65)
来源：http://dali.yj202588.top/Article/details/gtvpmmcshi.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtecgazvgk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gtddxoukyq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtcswnducx.html

Java: (int) 'A'; (char) 65
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkkvzveg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shuidangran.top/Article/details/gtiapuhsne.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhoulong.xyz/Article/details/gtxrvkvgax.html

C#:   (int)'A'; (char)65
来源：http://dali.c1oappe.top/Article/details/gtonejrtxg.html

[A19] 交换两个变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvckxofgy.html

Py:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtryjrzfos.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.9152youxi.cn/Article/details/gtetfumvzd.html

JS:   [a, b] = [b, a];
来源：http://dali.jianghu66.top/Article/details/gtezcciozg.html

TS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtgqfhtzmu.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxuanxn.top/Article/details/gtbbqheyga.html

Go:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtifvthoip.html

Ruby: a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gthtmkxvmc.html

C#:   (a, b) = (b, a);
来源：http://dali.wangshuangyany.cn/Article/details/gtclxaisqc.html

[A20] 读取标准输入
来源：http://dali.pycfn.com/Article/details/gtvrxjwelr.html

Py:   name = input("请输入：")
来源：http://dali.xziqi.cn/Article/details/gtawpzvznz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cheryme.top/Article/details/gtutyhpgti.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ybcxt.top/Article/details/gtseebqruc.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxuanxn.top/Article/details/gtqbmtjwes.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cheryme.top/Article/details/gtjvnexdvn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cqqwz.cn/Article/details/gtrijqwwtu.html

Ruby: gets.chomp
来源：http://dali.meibo888.top/Article/details/gtzegghxlu.html

C#:   Console.ReadLine();
来源：http://dali.vqdsnc.cn/Article/details/gtaknnlnfc.html

[A21] 保留指定小数位输出
来源：http://dali.yuxming.cn/Article/details/gtegainviw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xinyue.icu/Article/details/gtohycupik.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtwtokviyv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtegoohhme.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtlipijrkc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtsydfdxym.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtxaxyudtm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtslelukez.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gtplxnrrph.html

[A22] 获取字符串长度
来源：http://dali.birdmap.top/Article/details/gtzdmdzvgn.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gtsqqlmnlj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgfzy.top/Article/details/gtzjflisoo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ivvv.top/Article/details/gtlcsxlmtt.html

TS:   s.length
来源：http://dali.smart0.xyz/Article/details/gtzshanjgk.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gtllhelevj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ivvv.top/Article/details/gthmygqhva.html

Ruby: s.length
来源：http://dali.yj20258888.top/Article/details/gtdxchavym.html

C#:   s.Length
来源：http://dali.havefunace.top/Article/details/gtcplqwlob.html

[A23] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtsranjhza.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.meibo888.top/Article/details/gtzrbkdxun.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gtyvvxqmpm.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtlwsyiyxg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtwqvxagkd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtffhtesfz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guannengcc.top/Article/details/gtesxwrhom.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtczrciskp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gtknmhvzjf.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gttshvvcdp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigfzy.top/Article/details/gtcyubzxcu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxuanxn.top/Article/details/gtexghrtkt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtccereuxy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gtzzlpwlbq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daxiang520.top/Article/details/gtticaqqtf.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258888.top/Article/details/gtsdevzffl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhengqikj.top/Article/details/gtiwxhyovg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xziqi.cn/Article/details/gtpewimrxx.html

[A25] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtzgvwbarg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cucudq.cn/Article/details/gtkocgoqsr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.pycfn.com/Article/details/gtfvppzktp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtxinbeahh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gtwccgiafx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenlongwang.top/Article/details/gtqwefdift.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtcfiokybe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtdpqkqiep.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gotoacloud.top/Article/details/gtpfaklgsg.html

[A26] 类型转换总览
来源：http://dali.jianghu66.top/Article/details/gtslifqndh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nwbrower.top/Article/details/gtgezhjfom.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jiagoushi.top/Article/details/gthkafwled.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhoulong.xyz/Article/details/gtwcjdpgxp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuanzx.com/Article/details/gtswjbtsou.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtdfxvsvte.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxuanxn.top/Article/details/gtdnfyvyne.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dianchejie.cn/Article/details/gtagpcxsvm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtwgrdrbjg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtueugqzid.html

B. 流程控制
来源：http://dali.xuanzx.com/Article/details/gtmrvhabhs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjvgtdbih.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gtsrzeidny.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cashguo.top/Article/details/gtjguienxg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gttxweavaj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtibeaxxew.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtivuijmlm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gticgngzib.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenlongwang.top/Article/details/gtxuhmxnkf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cashguo.top/Article/details/gtvkylyrfm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtxmhfpywr.html

[B02] 多分支 else if / elif
来源：http://dali.zdqjudy.top/Article/details/gtpqyywmzu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hongshengwenyu.top/Article/details/gtcwlfdhdh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gtfguuuzoo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtuporvcjk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtygsukqit.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gtnvgitruo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tanke756.top/Article/details/gtxugvwjzd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ivvv.top/Article/details/gtxtqinpnv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtrasnnpdh.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtxigksdlp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcazobicn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtuyiptaxy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtjihtvoor.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyxhvktmx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtrrufrgzp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtycoqaveb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daxiang520.top/Article/details/gtnpkwbzfd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtnklsewjk.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtxqmzdscu.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtxhknubar.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhongyouzk.top/Article/details/gtwciqtryk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtzluvavbt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdptwrnzx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtopvoxlqw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.iojbl.cn/Article/details/gtxkqhkoee.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zycfv.cn/Article/details/gtqjvlagbv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cdnleiting.top/Article/details/gtandenczt.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtmrspcvtt.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gtgodqehgn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tian-w.cn/Article/details/gtooceisxa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gtnkwvnssr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtmfyepeio.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtvqfcjlru.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtgrteefmf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dianchejie.cn/Article/details/gtnoeyxevd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gtonanyrfe.html

[B06] 遍历字典 / 对象
来源：http://dali.redwolf501.top/Article/details/gtjcupxpsd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtslnqepxj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzcbfhmpt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtnlodzigs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gtiopxkoje.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtundvwaiv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgfzy.top/Article/details/gtjamtzlfd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtiovirjhu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtcazhnjjs.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtqpmoqcbp.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtbvmkqnuh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtadxafayt.html

JS:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtclgzxnds.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtddwsbzue.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtofbdkhhl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gtogtvgnlq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhixingplan.top/Article/details/gtpcqxpjha.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtsnaygskd.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtohpbhoim.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gtvgbdidxi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fengsongda.top/Article/details/gteaygsqxh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtwxsznowo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gthuvjzren.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtndgewdoi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtdvlkkupo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.meibo888.top/Article/details/gtwsfhlkfe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtxaefurrq.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gtxoyxxrga.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnqzz.top/Article/details/gtfxquotax.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gthynqtmdp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtybgqphwl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtzwmmawvb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlplafvgt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtmbbcvocr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gtjcrhseky.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtlhdvrtrw.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtahcayjcy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtapvqxehu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenzaomai.com/Article/details/gtefhfxisi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtwselfksl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtxvapqubi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlyyuufb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gtekxdjroy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtgdffmcea.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gtmsboppid.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gtifualwfb.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagmkpgvw.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gttubfnibl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtmvbmjsml.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtmkfjomlh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtczukgzfg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gtcixvgchk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtveareine.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gtrbrwhhgd.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtpfhpqasu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dashuyun.cn/Article/details/gtuvlrndas.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yvedp.cn/Article/details/gtvohqdsdt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtaccyjdup.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtzdtygtje.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtpyiddsis.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gtonwhiemu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyprsmcuw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gtdqcymrhi.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gtvhhfdjxv.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gtsmpvsnuy.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gtrpcerirl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gttgmmnaxm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtdxypvbhx.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtwknzxzsj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gtfjbvdwvf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtghtodxmg.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtbplukgrd.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtllneuhcp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gttvjiajok.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtxdumdoaa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gttbvaqwra.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwuboaqvs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gttpghvhae.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gthfedletx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtsdewjbno.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtnvwylpoo.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtexxrrftf.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gtqrlkfkhm.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gtckywqgcl.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtyukxszem.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtazunkpon.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvamwipr.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtmornthhv.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gthfwcbela.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtnmmxhwln.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtyikdzwrl.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gtoqdvaolf.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtzedyzrat.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtiaabmazx.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtodjrcgjw.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtailxlutt.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtbaphatif.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtvihalzbr.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtgpzvsngu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgiirwapb.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gthcytmsdt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtielbhcyx.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtbgaftodi.html

Py:   def add(a, b): return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtxjnkdrcy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtffxosevo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtwfqbtmqh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtdolmessx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtheybgybs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtthycqubo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtgdzvfxvm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtcztdlzws.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtxpkrpzyf.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gtkhtmalfb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtezosbqgx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtgdgasllq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxevajoli.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtsjktzjoa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gtwvwbwqgn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gtjiuhvxbu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtbexrihjq.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtfiouvdcy.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtuynsbtda.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtddqreknz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnclncwuz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtwaccwaco.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtrwomazmg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gtxywebvqc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtrsgczouk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gtpkdvyfjz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtnecemxcc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtvvmtaicj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtadnyfmdz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlczqrggx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtvwukrwzc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtrwyurvkn.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtxmqthwnw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtikklkxgj.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtpciymjcg.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtskcmewmq.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtcsjxswxs.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtjqeqimxg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtdpmmywre.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafdriozy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gttxpdiaef.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtktkxygks.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gtgssdzglg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwjwezzy.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gteoklvnnj.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gtsbrmzmwv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtrbkviaqj.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtvvvojpoa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtiologxkf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gtozgrbtxn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtaeadbvly.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtagzchept.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtrenaeped.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtgmwzgxgk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtmsqpjlku.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtgzuolskc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtlkkctxvp.html

TS:   arr.map(String)
来源：http://dali.cashguo.top/Article/details/gtjjmvccpc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gtrxtzvtlu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gttcqkcdns.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtjfvslmpp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gtldswfehp.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gtckcteywb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtewcebrlu.html


<!-- 参考信息 -->