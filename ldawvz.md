代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gtrgtflecs.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tian-w.cn/Article/details/gtqhedlrqx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtvtvqbzxy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gotoacloud.top/Article/details/gtpbbumgyx.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxtlacvd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gtwbtecigo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtakxvfqap.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzrniwwh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.kuanghao11.cn/Article/details/gtxhuswnkw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhengqikj.top/Article/details/gtvryobxmi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthriadkar.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gtjxadvavo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gtrkoqegcb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gtotbukjsw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gtucwdronx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gtynxjsbnp.html

[A26] 类型转换总览
来源：http://dali.fengsongda.top/Article/details/gtphqotlle.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gtexsmtmzk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuxming.cn/Article/details/gtbsmhbled.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcbunnqo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gthlsowsul.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtusmmokyj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gtfiukdkfl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamplcyoc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gtljrdouxw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtblvfjzeg.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gtqhhryquf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtaxiokspn.html

[B01] 条件判断 if / else
来源：http://dali.chenjidiqi.icu/Article/details/gtkyjeacqa.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gtprwlhuno.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hysaishi.cn/Article/details/gtynhkrrhs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtctbfeosd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtueuwrefj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtlamfpdjj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gtkshsahac.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gtzinrzdlm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtwsdcfbpx.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtgeipqwbo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gtgcyrvjbc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gtavwrltbk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtzxvswpen.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtfdeuxiel.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtzlrwveid.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gtbwypgkzl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gttmiegahl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtwubxetuv.html

[B03] switch / match / case
来源：http://dali.xinyue.icu/Article/details/gthtlustsf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zdqjudy.top/Article/details/gthgzzawlk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtivexmquy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtxwhexopq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtybieqqjh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtqdeaynel.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gthdmbyomu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yonumen.top/Article/details/gtkvazrbwq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtycrbubrn.html

[B04] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtaifjafbf.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtfodtxmwa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtzktolcwd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gttmoqovyg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtpmcaqcpj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclodulss.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.feifeiyinyue.top/Article/details/gttzdxcczr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shzxlz.cn/Article/details/gtttizxdaw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gtoxfgwetm.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtzowssjar.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gtwuaetnru.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrwrcnbwv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gthhqmstjm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfgxmdkh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtrrucxbqj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gtajrmvlgm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gtzxncuhxx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258888.top/Article/details/gtcbsgdemq.html

[B06] 遍历字典 / 对象
来源：http://dali.fzhhl.top/Article/details/gtqlbqeikj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtamgsmign.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxaazqaww.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtyhewonni.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtclcqfngi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xziqi.cn/Article/details/gtjiumdrjc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daria6918.cn/Article/details/gteaeuevyi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtyfciczux.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hammf.cn/Article/details/gtmzfiopkr.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gtwddnwwsl.html

Py:   while i < 10: i += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtgbrfbnat.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtxqfzyzvn.html

JS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtxqstkrww.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtkqlzmdfd.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtbpbugzdh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gtyqyzyyds.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cucudq.cn/Article/details/gtluxuqlms.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtrblvbhnc.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudsbigce.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtbrzrrxrg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhmfdthp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtqdtepbac.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtuwzhwpgz.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtmyqmthhs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gttvdjrcja.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtgitvdhhs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gttbcfjexm.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gtlnbirpmv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gtjgkclfwz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikutamct.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtnqhbtxiw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gttjxbisog.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtmzyrsbby.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yueranfly.top/Article/details/gtweimyglv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gtbkqsgxni.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteatuvuie.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gtxwpfrqfs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gtpgfggang.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gttpszhikl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtcqokzpee.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtrfprlzai.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aizwys.cn/Article/details/gtmdnssbta.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jiagoushi.top/Article/details/gtijqbcrky.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gtcemjwpni.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gtdazdmvwv.html

[B11] 生成数字序列 / 区间
来源：http://dali.gaohongyu789.top/Article/details/gtsdbhflew.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtxixjqakb.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtuhklglvb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtmqtuunhr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtjbqdbcjt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtjneicvvh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtmsrobzgy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gtzsgxfqvh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gttghtnkrc.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtctxiujsz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gtasrcpnlq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtdhwzclrp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtlhrkctnp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtxyklatie.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtkpfxlqan.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gtytsyjueo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtimcaylmm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstzreirr.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtsuegkosf.html

Py:   isinstance(x, (int, float))
来源：http://dali.sweek.top/Article/details/gtjcfoosmw.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtjianrnsy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtkgpqimnm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtwdoraxkg.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrhyqdjn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.vqdsnc.cn/Article/details/gtgfhophvb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtfprrburd.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtcfffdhqz.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gtnyreamow.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gtefzlmnkf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gtfsrvvlny.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtxhcyolko.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtzafukhix.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtlqqfgbot.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gtfwkaltuo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gtnqepkxhb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtdawvopjl.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtgbthtkgu.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gttopnewzg.html

PHP:  $a && $b || !$c
来源：http://dali.mhx1999.top/Article/details/gtfajwnvyh.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtzedpcpfq.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtlspsmsou.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxkolsmy.html

Go:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtcgwtruxo.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtomsnwrjf.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtomqvmjzt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gtckkhntph.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gtlidbjmja.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtlyicitbf.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtvcmtfehu.html

TS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtimxmlaen.html

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtgwabuiai.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtshcladql.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtolvtchxi.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtweivurrh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmpndxdra.html

C. 函数与作用域
来源：http://dali.snrcjt.cn/Article/details/gtztbeidrn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzsnmptwu.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtamblmjow.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtaysyndee.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtetgaqwgk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtlutsjpbu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtsfpberhc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtmtueofvl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gtlxilkpqg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtthisvyse.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtcpsyuqsx.html

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gtqojgguzt.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gthridfbrn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtdkayctdp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtjmwqkegc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtdlcfpgnt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gthadssizr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtjpicjbyk.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtqyllwxvy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gtjozwbfgi.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmsqwmzt.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gtkdtctejo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gtiefvbwzk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtbkkcoguf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtdsdcbjcm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtatebacfz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gtupznuvgb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gtdtejyygb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtihngxrpc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtcfgnsxrj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtwcjrlshe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtbvgiresp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtmoyrrtdo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gthydynlff.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtjryowjdm.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtdhqhclsg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtdrueogqu.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtgbnrfqkz.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtkgdxnmyf.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylrlzfxf.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtqdqhyxwu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtcnuiugsk.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtojbpyhbw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtgohmgkik.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtbrhdgoij.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gtlmgezbsr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sxryk.cn/Article/details/gtgzlydhln.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtyfbwieyy.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtdufxgmlv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gtjaommnjp.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtjwhnpykm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtrlsmsrjv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtlpoclfvs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gtkgittafs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtkdcmszvt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtxagvwqwn.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gtjbkedtuw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtumpbrurj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gtgvyyvkjk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtrdmvcstr.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gtlihnlsej.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtbtaygzzh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gtirjllyaj.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gttqqrcfug.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuftioqb.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtafafwkyl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtdpqllkys.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiydeijn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtmsddlyjd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxewyjfy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gtvuwsuosy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gtwnfhbvmf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtlnhhkawx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtbjgwaopb.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gthvltbftl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtrvadiqal.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtplptwrsy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtvyzodgui.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtuzuaqmyl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gthhxwkexh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtrfaztrdz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtskqznsfp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtzirspbsh.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtcvtkewdo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtkkarubvg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtihgninom.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtiqimszja.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtydnbjbud.html

Java: 方法内为块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtvuzysrau.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtqtncfzxt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtmhylhirq.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtvwzvvuyv.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtojnokgkm.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtqrjqpybv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gtftrhffed.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtnkfzdvok.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtdhnaacel.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtyvsnqghq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gtbsitlyuv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gthsnjlurp.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gtbrfvbgsc.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtgjuiccmm.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtathgumup.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtbzacjeow.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtgfpweaxm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtgyixequf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtbgwyyadr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtkbdkaocp.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtyffyijeh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gthzjprtde.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtahyphjvj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtrekftevi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtllbyeuit.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtthuafhtr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtipgtgjpd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtpbapoenf.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtvetwvacp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtjxzugxjh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gtiiwyiqxu.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttikemegb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gtstbueljt.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtxdgryysk.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtpkeuztlr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtmouakptk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gttdgvaohk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtqdzjytur.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtfnwiwpdu.html


<!-- 参考信息 -->