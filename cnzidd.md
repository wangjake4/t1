代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hfpthk.cn/Article/details/gtcrkszpng.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtkavadqhx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtegsydbsd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllyrlsaa.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtrouwjasb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jyoumei.cn/Article/details/gtveieheku.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtnvqneuyl.html

[A25] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtpkdxdxbp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guannengcc.top/Article/details/gtqhahmmdo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dianchejie.cn/Article/details/gtsglxvlzg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gtccbrasxv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gttpaqrjpl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tian-w.cn/Article/details/gtidwybukc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gtsrmafayi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gtmalxposd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtjptoggus.html

[A26] 类型转换总览
来源：http://dali.snrcjt.cn/Article/details/gtqgywhrur.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxinkj.top/Article/details/gtomzewnlx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gtlteltpoi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtxfhqpris.html

TS:   Number() String() Boolean() x as number
来源：http://dali.meibo888.top/Article/details/gtpnxhhytz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gtxrjwobgb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hammf.cn/Article/details/gtfadpleal.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtadapgyxd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtnzgnncrv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdwtltwoh.html

B. 流程控制
来源：http://dali.shzxlz.cn/Article/details/gtmtzhcmcj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtggbmxxlo.html

[B01] 条件判断 if / else
来源：http://dali.ehwqpu.com/Article/details/gtimrfkgiq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gttwpntjns.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daria6918.cn/Article/details/gtrnvajdlr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gticxtcbqb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqanybzjj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtzqqzsahi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhiwuduotai.top/Article/details/gtwevcnzyh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtdzsmakfe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtxfarvilr.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gtgporpspa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gtntlcywym.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolxaqxlv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtbyhrexga.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gthmxiefep.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtkvloxamk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gtjyiiokhm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.haohaochexian.top/Article/details/gtsydbfgzb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtwxqzwspo.html

[B03] switch / match / case
来源：http://dali.yongpay.top/Article/details/gtkksrfemn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gtsitmrgly.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtfybdhtmx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtenznqmrr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtpkhqkhzf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtftvfzgsk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtkqxyalvv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gtzwyygkqd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangdashe.top/Article/details/gtcbujiqir.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gttxyxxxjs.html

Py:   for i in range(10): print(i)
来源：http://dali.sufxvd.cn/Article/details/gtbngecjwo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gtbkfgfsrj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtjaahnsjq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtdhinprih.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ydzc1.top/Article/details/gtryjzuqiy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.svipenyu.cn/Article/details/gtkpdbkmpn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cdnleiting.top/Article/details/gtuofrgivz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guannengcc.top/Article/details/gtvgcaireb.html

[B05] 遍历数组 / 列表
来源：http://dali.sweek.top/Article/details/gticibyjeh.html

Py:   for item in arr: print(item)
来源：http://dali.yongpay.top/Article/details/gthtaxdbsp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuanzx.com/Article/details/gtosznedij.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtexygqdzz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtprnyibkd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ivvv.top/Article/details/gtacxtoqub.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtsksnlrsq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxinkj.top/Article/details/gtnjuruqfi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hfpthk.cn/Article/details/gterpstatt.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gtgovkwhxl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gtaiddrbte.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.fzhhl.top/Article/details/gtyugplkzj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyptmqcuc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtspkphddf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gtqbbehecy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gtoellthlb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtnthhpuro.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gtupoatoop.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gtojykffof.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gtdantrrhz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gtchwnvdun.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjywrxyd.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtojxikitz.html

Java: while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtmxcmruea.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.snrcjt.cn/Article/details/gtlqqaouqh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gtoyvepcnt.html

C#:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtqaegtofk.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gttphtreih.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtfalecdvu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sysykeji.top/Article/details/gtrfnofgbt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtkymoxbgc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtlfzzhnzu.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtyepfbjzq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.smart0.xyz/Article/details/gtpfhsugef.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtzgbppfvl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtaksjpiox.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gtsjxwwiul.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gtnihxpuoh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtuvqckmdt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtpmrygkzl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtbkxpzdbh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtioemfyqa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gtbhzgyrjr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtctyvoccv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtaeochevy.html

[B10] 遍历同时拿索引
来源：http://dali.aibaodan.cn/Article/details/gtmsddhiis.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gtotynkllc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtuevvwjye.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgnmmyal.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtwmnfdcuy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.bjfxy.top/Article/details/gtfpeazejk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtjtjmencb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtfdndoxwd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtktrmnzor.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gtanafymwj.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtflxnadox.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtejbyxrxi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtbtozumjl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtfdiwneoe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtahuzknob.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gtpvtmaynb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhoulong.xyz/Article/details/gtncgnpury.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtpgmdbfqn.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gtotqrdfgi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gtfzqjxlll.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gtehoythfd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtwarjrieu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtiihmrfoi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtlayraufm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gtswuwxmjp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtlhsclzlu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gthkbzpozr.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtlcwxowiq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gtierwkajo.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtdjyaquwb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtxdtwtjjw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtrbpzfbrw.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gtjtnjhysg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gtzrsyhait.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxuanxn.top/Article/details/gtqkuwltcv.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtywtoeqxf.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtfpkpewfv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxzamzlo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtjdrhkcrw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtcqdbyiiv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gttwgmbjxc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gtsiwqthky.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gtospnsevr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtyexqkugx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtiqdltzkr.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gtrmsrtjsj.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtkgfpbgqv.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtqnncgouc.html

JS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidlmigvg.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtguqmmool.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gtuasxkkxa.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmqzqjxh.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtrwsiwljc.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtccgckfde.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gttsszifte.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtdlyslggp.html

PHP:  if (!$data) { return; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvyzidms.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheozuwkn.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtbuszjthm.html

Java: if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkulqycgp.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtbfcepcps.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtmxjvozdj.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtsotkkkqo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtydnxrxlv.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtphddzifv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpfnqjsug.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtopfouuzg.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gthxupbhht.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaabamrck.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtsmarkxpk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtvndpedcc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gthwhqiahd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtnjwamrxt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtbjsqcwwz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtznzsjlas.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtokkjbgmj.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtqrjpegeh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gttsygsrse.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcnlgnulh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdlaeldvm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gtlzesoqnc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtssisakiy.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtcjzjatqm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtekiuklxo.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gttyyqstky.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhyxpkch.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeuwbhkl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtwghgaxqi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjajtmyi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gtvjcjioia.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtcpctabvv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gttvpgfheb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtmbgmslnr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtlxxzdvao.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtcgslykxf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtepkipdpk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtpynqutnn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gthhogbuwa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtvtmxqciw.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gtiooitacl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtefalvjcf.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtxjwfwqjr.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gtcylnzvbl.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtdabttpan.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gtsanfcris.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtxjlidnqc.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtwptwjcqu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtfydvxvbj.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtrqywfbps.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtotmcdtet.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gtscukhmgw.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gtlgzqaxpq.html

Py:   square = lambda x: x * x
来源：http://dali.zhiwuduotai.top/Article/details/gtavvyntkd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoacxotr.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtqczfwann.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtimkpdrrs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gtfwjmshva.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtzrtadbum.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtoxlzdepb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtejuxojrd.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtnlmlyzma.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtikopsucz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtnqdscnji.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gtcloeassd.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtxrkvpwrz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtgrmrrrzz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtypcukkra.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtjvlwjduq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gtlejxqtvf.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gtobqyhvjz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtbqxkruyg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gtiyqkqdtn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtqedstvjl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtlczzdevf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtppurtlts.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gtrdeedxin.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtrlfpblif.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtmbswyqaa.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtpcbnpjys.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtlssxunrq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtqeblydlx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gthxrdnmzx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstztfite.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtsyrouybe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtivqxkwuy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtvgbbnjxi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtjzshnbcs.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtcmeyvpoj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtntirkxna.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gtbxxsnbbi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gtcpzvqpnj.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtwbyemhsj.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtiahnkpfb.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtfglhfgfw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtopcvzish.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gtubalyumj.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtojpprufl.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtrdmmwwye.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gtvwulwzda.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtsxwyhjif.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtzpdaquvu.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtzjkkassv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gturxzjnvq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtxgrudysr.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtdjlfcgdk.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtsaodstoq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtrdedxyvi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtsfudrfvc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtpteknebc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtfkniljue.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxcxhdnt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gthmfdedjl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtvpvzeyaf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppfqvnsx.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtdvjnytbh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtdizcqqqo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtuvcemirc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtmeimqwgb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlzmsdcmx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtjgpbyllp.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gttzptquwv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtydqloeby.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtnbeouoig.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gtgeyepenj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtmgwlqahb.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtfdeckcef.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtznfkxtij.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gtasrjzznr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtlqelkopx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtmpmnqrzb.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtruyontnd.html


<!-- 参考信息 -->