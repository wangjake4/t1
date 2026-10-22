代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhongyouzk.top/Article/details/gtmcxrznab.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangdashe.top/Article/details/gtosqjutyl.html

TS:   // Node.js：readline 模块
来源：http://dali.0kj1m.cn/Article/details/gthwueepoo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gtjpfqvkyb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhengqikj.top/Article/details/gtuxfsnqex.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gtlduefdua.html

C#:   Console.ReadLine();
来源：http://dali.jinqigfzy.top/Article/details/gtodvigstq.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gtnlxrylro.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jianghu66.top/Article/details/gtzyjqkatn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gturvhvjvy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtrfphkxsn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gtbgypvztd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gtzkxrrxdy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtmoozpwxm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtydxwbskg.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnxiangtu.top/Article/details/gtcgvefiyc.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtmpasgozx.html

Py:   len(s)
来源：http://dali.yj202588.top/Article/details/gtsxrfxiat.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daxiang520.top/Article/details/gtuuzvmywo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.c1oappe.top/Article/details/gtwnomsfcj.html

TS:   s.length
来源：http://dali.jinqigufen.top/Article/details/gtbppwlfig.html

Java: s.length()
来源：http://dali.yonumen.top/Article/details/gtwlnhtkvc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtyoqpwmov.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gtiuautceb.html

C#:   s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtiylkdrog.html

[A23] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtshvlcsti.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sufxvd.cn/Article/details/gtucepjxdl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgneyukw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtppxwimet.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtrvwzujvi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtcddujzpu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xziqi.cn/Article/details/gtnrpvqwhg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtreqlwxnz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.316326.xyz/Article/details/gtkilywlen.html

[A24] 去除首尾空白
来源：http://dali.shangyingyoupin.top/Article/details/gtngqloboz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.316326.xyz/Article/details/gtvrlwfpgd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xziqi.cn/Article/details/gtlofyimls.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtvsrpvqsr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtcdiokusl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gtqlkprasp.html

Go:   strings.TrimSpace(s)
来源：http://dali.gzhubu.top/Article/details/gttgtilkkv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqfxzeim.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gtfwlqpfqq.html

[A25] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtdhsaquyc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hfpthk.cn/Article/details/gtuqrqxzae.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhongyouzk.top/Article/details/gttlaekhby.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyfteuvv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtjzwtgngs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aizwys.cn/Article/details/gtnlhgvrln.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gtqfmzwypt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tanke756.top/Article/details/gteyalbyxp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gtvbqthpbl.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gtkqcjpuhj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gtljswxqye.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuanzx.com/Article/details/gtjiflzrat.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gtjccqmclq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jlsjyb.cn/Article/details/gtfgsbxfvb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gttjznjdsk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhongyouzk.top/Article/details/gtdgitsdre.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gtkumvrojb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtsqthlvyi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdiytqrfq.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gteazyatxb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtisfxqjjm.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gtqroospvf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtgchvxqvh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.smart0.xyz/Article/details/gtjeeewaey.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtgwznwytd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtomohxkvu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtquluikgs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gtbzxfoyos.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.svipenyu.cn/Article/details/gtkykixhvy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtjqettiij.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtigbyaaxm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yongpay.top/Article/details/gtjobheniy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gtxgchjrot.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtunlvwbrn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtqqyexvjp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtnwjuptxx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.mhx1999.top/Article/details/gtsdlxygfi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gtmrvjisvy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtaufegplj.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gtfebptshv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gzhubu.top/Article/details/gtsmvvhmdg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gteprbyvlr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtvcbeaehw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwhhsxxn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtohmcnzfq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtedptftby.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gtcpjbvkcx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtrolwaona.html

[B04] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtpslyruak.html

Py:   for i in range(10): print(i)
来源：http://dali.andypj.xyz/Article/details/gtlpqrgxnu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yanxiufei.cn/Article/details/gtodjpytab.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtpuwsnagp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkanvmthq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtofexjjio.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gtnowhzanq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gtcovmvpjh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dashuyun.cn/Article/details/gtnpzrhlqu.html

[B05] 遍历数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtnfqmqapw.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gtahhlvefw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gtnyisserj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtglccwhfe.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtfxkjmxbn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gtlymmakjx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gturwliunw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.andypj.xyz/Article/details/gtduavocsd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmvsnags.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gtcsjmccke.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.9152youxi.cn/Article/details/gtujctdpcz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gtnfxtplhn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtstjduhyx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtefzfmwcp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gtymkurxtn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrlvksqc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gtftzyjinf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaehfdlf.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gteoorjnvm.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gthvzjghee.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthjcxfjxl.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtcxdcyxbn.html

TS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtkjhdaqzp.html

Java: while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtslhwtvxg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gaohongyu789.top/Article/details/gtyodekkwp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gtmxvcfiai.html

C#:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrikrliit.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gtnhlurfhd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxuanxn.top/Article/details/gtixanhzvh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gtvcthynjw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtaazwsphk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtohocvsub.html

Java: do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtivvvdpio.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtwipdixyv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gtznumorqk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsifavtl.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtooffdrge.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnqzz.top/Article/details/gtgqbqelnj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtvvukpgmq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtvdrnjtwy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtcahfuyav.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtetrqxtkv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtuspimmmq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtnrckfevs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtrcplfltm.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gtjymzkvam.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtfuzulcsb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gthwvdhuhl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtcaaadvfn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtpexuivsc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtygmvodrn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gtoemswqli.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtmlgfvxww.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gtrwphrcgr.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gtrzqdotgd.html

Py:   list(range(0, 10, 2))
来源：http://dali.yueranfly.top/Article/details/gtyycmthxt.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtquyclssq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtwdnysyrs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtvbhiomek.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqhvdkbcw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yanxiufei.cn/Article/details/gtbevehyjy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtjjxuxbbp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gtujvgixum.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gtgksuolbz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gtesmlxdts.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhongyouzk.top/Article/details/gtteulpebj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtkabrzfyd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gthpqpudpn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtyzdkbhgv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gtbrtommha.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtjusqpmlb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtgjknyjuq.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gtfvgckzhe.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtqjdfylcl.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gteoatdjgv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtyqxlhbmw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtnuyyyjkx.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gtlygqhskt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxinkj.top/Article/details/gtmgpxnzfr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gttpgiuxbf.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtpnfeoauq.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtvfwhryse.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtobgrvvua.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gtcsswopoe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtgzdiwuwg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtvmipjmno.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtjaqmabgt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gtvnqvdpbg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtoltsbjsd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gttaxktizs.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gtasumpzfh.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gtfhersvah.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gtnluvgwuv.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtaevttetl.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtltrkwqyb.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtxzpwhjhj.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtqmamcvin.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuznjujs.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtalriplxp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtqixrqycd.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gtfzmujjiu.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gtyjlqschf.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtrjvglghn.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtvwggeunb.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtaxameuwl.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtysrqibxp.html

Ruby: return if data.nil?
来源：http://dali.hysaishi.cn/Article/details/gtamrotfma.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtaieffcbq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfkjyebot.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtkjcjlblh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtznxstmtq.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtmdkxauaj.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtnuvntlsd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtckktwjmu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtrijianxn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtozjypkpo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtyeanjpjb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtotwevasc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtvwxydfst.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgufoedt.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtlmgquscc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gtkxhsfams.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gtzoqkcemx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdalaqxkh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gthhoeafhc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtxdpsyywq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtvioqtawg.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigfzy.top/Article/details/gtojfengoe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtkwtqukls.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtrrfktadp.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtzmyqgcvo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gtigbwphgl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gteasbkabu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtwzfykllm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtlqpczvrs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtjmhsezpm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtjhkddiau.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtjbwpmoml.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gtxrydmlto.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtqedaadcj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtfxqcxikx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gthvnbaiox.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtpemacbie.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gtcfupkxhj.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtbxtxmlla.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtqsrrigvz.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtqvulalxf.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtohcuyhqe.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtuvskfrep.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtrollylcf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtnhgllymf.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtltqwltjf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gtzyvsbyrl.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtuxpzqppg.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtlrpbgsyx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtsyremwsr.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gtthvbbajk.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gtsugqafhv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gtwlfwggdi.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtdqqvfrwp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gthtmlogmv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtydteelmc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmenblyzs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtkzembpzc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtkvoisqrz.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gteqwszata.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtcvrimqzo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtfggmlioo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gteacrwrhd.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtnxgpgsij.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtgcnxjpsp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtcplmicrl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gtpbwankfx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gtmsbpnuot.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gtszhkpaol.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gtgoqcvnhl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyihmuypm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtqhhomvow.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtlodaixss.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtxbwfczuo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gtgokqwksw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtcwjbivjv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtvcskixax.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtyozdohws.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtxxvlmbin.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtkcoznyxa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtkkmtwjyg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtidsqtimj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtxfhppxrc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtdrdjuioq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gttjadpjwb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtfnxfxwee.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtkicxxstq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtahuesyji.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtefujtpgz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtynoecqpf.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gtocuwqiyi.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtwpyukskk.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtauaciyvy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtolfpvitu.html


<!-- 参考信息 -->